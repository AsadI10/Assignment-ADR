# Assignment-ADR

## Context

1. The visa processing system, in order to process visa requests and get updated visa regulations in real time, the system will need to communicate with the visa issuing authorities of various nations such as UKVI for the United Kingdom.
2. The system needs to be able to manage a large number of users and data, including real-time changes from different nations authorities about visa regulations.

## Decison

Introduce a microservice architecture for the visa processing system.

## Rationale

1. To solve issues with scalability, maitanability and agality, a microservice archiecture is selected.
2. Because of the system broad breadth microservive can aid in matching development with certain business domains.

## Implications

1. Compared to a massive model, individual microservice deisgn and implementation will take more work.
2. A strong mechanism for microservice coodination and communication will be needed for the system.
3. Better scalability is made possible by microservice deisign, which is line with the system's scalability need.

## Status

This ADR is successful and approved to use for the visa processing system.

## Date

27/10/2023

## Decision Maker

Asad Imtiaz
