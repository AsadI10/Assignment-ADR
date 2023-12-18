## Context

User at the visa processing system must use a password to verify on the system. Because these passwords protect the users information and system access. One elelment of the system security arhitecture that we cannot compromise on is the secure saving of passwords

## Decison

I've made the decision to store user passwords using cryptographic hashing. In particlar, I'll be using in the system SHA-256 hashing.

## Rationale

A cryptographic hash function from the SHA-256 is selected for its combination of speed and ofcourse the attack resistance. In the IT World this combination is highly recommended and regarded as best practice.

## Implications

Positive: The passwords are never kept in plaintext, there is much less chance of data breach within the system.
Negative: It will be important to regularly update hashing algortihms in order to stay up with development in computing capacity and cryptografhic research.

## Status

This ADR approved to be used

## Date

04/12/2023

## Decision Maker

Asad Imtiaz

## References

The National Institute of standard and technlogoy(NIST) password security and recommendations. https://pages.nist.gov/800-63-3/sp800-63b.html
