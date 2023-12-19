## Context

1. It is expcted that the visa processing system would manage a wide range of data types, each with unique properties and speficifications.
2. It's essential to make sure that the system runs smoothly, keeps data integrity and offers rapid access to both organized and unstructurred data.

## Decison

For the visa processing system, implement a NoSQL database alongside a relational database

## Rationale

1. Rule changes and other partially or unstructered data are best stored in a NoSQL database.
2. Structured data such as application history and user profiels is best stored in a relational database.

## Implications

1. Techniques for data syncronizaiton across relational and NoSQL databases will be required
2. Depending on the use cases of the two types of databases different scalability issues will be applied.

## Status

This ADR is somewhat approved to use for the visa processing system.

## Date

27/10/2023

## Decision Maker

Asad Imtiaz

## References

Patterns of enterprise application architecture: ""By Marin Fowler, 2002, Addison-Wesley Professional.
https://books.google.co.uk/books?hl=en&lr=&id=vqTfNFDzzdIC&oi=fnd&pg=PR7&dq=Fowler,+Martin.+%22Patterns+of+Enterprise+Application+Architecture.%22+Addison-Wesley+Professional,+2002.&ots=oVzjywKLtA&sig=cAvktQ9S1_mhqTXGVvoyIE111RQ#v=onepage&q&f=false
