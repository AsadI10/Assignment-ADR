## Context

The architecture of the system for processing visa includes several subsystems that interact carefully to manage user infrmation application and the admin duties
The complexity of the system makes it difficutl to maintain and use so a more efficient way for the visa applicant to interact with the backend service is required

## Decison

I have decided to implement a Facade pattern in form of a "mainframeVisaSystemFacade". This will serve as a single entry point to the backend sysbsytem making it easy for the visa applicant to intercat with the system

## Rationale

The ability of the facade pattern to offer a reduced interface to a complicated susbsyetm improves its usability and maintanability this is according to(Gamma95).

## Implications

The backend susbsytem canbe updated with less risk of breaking the client-side code.

## Status

Aceppted and created

## Date

01/10/2023

## Decision Maker

Asad Imtiaz

## Reference

Gamma95, Gamma, E., Helm,R.,Johnson, R & Vlissides, J.1994 - (Design Patterns:Elements of resusable object oriented software. Addison-Wesley).
Martin03. Martic,R.C. (2003). (Agile Software Development:Principles Patterns, and Practices. Prentice Hall.)
