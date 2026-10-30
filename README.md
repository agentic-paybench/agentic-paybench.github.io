# agentic-paybench

> **Start here.** Everyday AI Ltd, a UK research company, measures the payment rails that software agents use to pay each other. Each method, frozen and anchored before any of its results was published, is applied identically to every rail; no rail is recommended and no ordering is published. This index links what exists: the method and its harness, the signed capability records for six rails, the two published measurements, and the three public pre-registrations.

Research artefacts for **measuring agent-to-agent payment rails**: a pre-registered evaluation methodology and a capability oracle. Rail-neutral by design: the method is designed for pairwise comparison, neither published measurement asserts a merit ordering of named rails, and the work holds no commercial relationship with any rail it measures.

| Repository | What it is |
|---|---|
| [payhelm](https://github.com/agentic-paybench/payhelm) | PayBench: the measurement methodology (frozen v1.2), harness, and calibrated fixtures, as a fork of HELM. Pre-registered and anchored before publication of any result: OSF DOIs [10.17605/OSF.IO/XGFUJ](https://doi.org/10.17605/OSF.IO/XGFUJ), [10.17605/OSF.IO/UFQG5](https://doi.org/10.17605/OSF.IO/UFQG5) and [10.17605/OSF.IO/UETFW](https://doi.org/10.17605/OSF.IO/UETFW) (the test-network confirmatory data pre-registration, registered 2026-10-15, on top of the v1.2 methodology). |
| [oracle](https://github.com/agentic-paybench/oracle) | The capability oracle: schema, ingestion, methodology, and the static read surface, live at [oracle.agentic-paybench.dev](https://oracle.agentic-paybench.dev/). |

**What is published, and what is not.** The methods are public. The authorization-primitive latency (DIM-02) findings for six named rails and the settlement-finality (DIM-01) measurement of five named rails on test networks are published as measurements at [oracle.agentic-paybench.dev/results/](https://oracle.agentic-paybench.dev/results/). The settlement-finality league table (the Bradley-Terry strengths and the pairwise win matrix the method computes) is withheld by choice, not omission. Nothing here recommends a rail or routes a payment.

<!-- family:posture labelled -->

**Rails covered by the methodology:** x402, AP2, the Machine Payments Protocol (the Stripe and Tempo HTTP 402 protocol, on more than one settlement rail), and Lightning-based rails, measured on test networks and first-party traffic.

This page is the research index for the `agentic-paybench` GitHub organisation. Nothing here is a product, a service, or an invitation to transact.