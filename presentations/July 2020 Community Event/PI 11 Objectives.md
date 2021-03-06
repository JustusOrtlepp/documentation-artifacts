# PI 11 Objectives (draft)

## Performance/POC
* Decide if Event-sourcing benefits are worth it
* Provide a plan to implement this in production, along with required  migration and boostrapping tooling
* Provide a visibility and monitoring tools (or their design)

## Settlement
* Final delivery of a flexible and configurable Settlement service for the Mojaloop platform.

## ISO 20022
* ISO 20022 POC for Native Mojaloop Support 
* Cross Network ISO 20022 Support POC 
* Workshop and Comparison of the 2 streams to document similarities and differences (towards the end of the PI)
* Submit Draft Business Justification to ISO Standard Board to propose to extend the ISO standard to meet the Level One Objectives   

## Streamline Designs with Testing & QA
* Correlate and align tests/assertions with AS-IS documentation in the form of PlantUML sequence diagrams  for the Core services
* Run GP regression tests using TTK on demand or as scheduled using Helm
* Improve test coverage (include new features) - 1.5k to 3k tests [Stretch]

## Portals for Onboarding
* Functional PoC to demo Technology Framework
* Approved Guidance on how to add config specific pages
* Approved Guidance on security and Auditing

## PISP
* End to end transfers flow at the switch
* Account linking flow at switch
* Scheme Adapter + Mojaloop Simulator implementation for E2E Transfers 
* Working MojaPay PISP Demo App** (thanks to interns)
* Fully implemented Auth service

## Fraud Management
* Provide a set of documentation/tools/roadmaps for Mojaloop platform implementers to ensure they can implement the mandatory tasks required for fraud risk management at the Hub.

## Extend Bulk Transfer
* PoC Designs for advanced Bulk Payment Use Cases such as Bulk Lookup, Bulk Quote & Transfers for multiple Payee FSPs and present to the CCB

## Leadership & Community Management
* Restructure community governance committees: Community Leadership Comittee (CLC), Design Authority (DA), Change Control Board (CCB)
* Develop a new community membership model
* Review effectiveness of existing community workflows and revise where needed
* Engage entrepreneurs and Fintech companies to identify their needs and develop measures to respond to them
* Onboarding: Deploy and test new Dev Hub 

## Versioning
* Release a functional v1 of Mojaloop Operator
* Migrate Mojaloop codebases to semantic versioning
* Evangelize and Harmonize the Mojaloop Version

## Code Quality and Security
* Improve data protection measures, introduce a central cryptographic function and improve tools and measures to support the OSS Community

## DFSP Operational Controls
* Align technical development of payments manager and payments hub workstreams

## PDP - Testing Toolkit
* Support wider adoption of the testing toolkit by implementers
[Have two of the implementation teams use the toolkit by the end of the PI for Hub testing & Onboarding FSPs.]
* Implement a hosted version of Testing Toolkit that can be securely hosted by Schemes easily
[Can be deployed using helm charts, and is well-documented]
* (Stretch) Include a Reference OAuth Server in Helm Chart

Measuring criteria:
1.	An FSP can login securely to a hosted testing toolkit solution and use it to test its Mojaloop implementation.
2.	Secure means implementation of JWS, TLS and OAuth;
3.	Well-documented means Deployment / usage instructions are made available

## General Mojaloop Core Maintenance
* Support and general maintenance of ML OSS by making Helm releases, reviewing PRs, fixing priority bugs

