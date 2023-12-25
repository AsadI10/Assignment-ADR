## Context

FOr my visa application system which will enable user to apply for visas and view the dashboard information, i require a cleam architectural layout with a focus on maintability scalability and security.

## Decison

I've chosen to employ the component-based architecture depicted in the diagram, which conists of an external email and file storage system differnet controllers for various functionalities security components and a single page application servinf as the user interface.

## Rationale

The rationale for this architecture is to:
1.Decouple the user interface from the server side logic, allowin independent scaling and updates.

## Implications

The selected technologies - Oracle database, angluar, and spring MVC, call for specialised knowledge.

## Status

Accepted and completed

## Date

15/10/2023

## Decision Maker

Asad Imtiaz

## Reference

Technology stack evaluation report
C4 Model
Security policy and compliance guidelines
