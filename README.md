# GovBridge AI: demo prototype

**Live demo:** https://humaimeedy.github.io/govbridge-demo/

GovBridge AI connects AI governance requirements (laws, standards and ethics principles) to the controls, actions and evidence that AI systems need: one traceable bridge from each source to the system that must meet it.

This prototype shows three roles:

- **Users** find which requirements apply to an AI system, get implementation guidance, and assess specifications and evidence.
- **Institutional proposers** propose new requirements, which are checked with SHACL before review, and evaluate existing rules.
- **Policymakers** vote on validated proposals and review how existing rules are recorded.

Behind the interface is a small GovBridge-O ontology in OWL (Turtle): 6 harmonised requirements drawn from 17 provisions of the EU AI Act, ISO/IEC 42001:2023, NIST AI RMF 1.0 and the SDAIA AI Ethics Principles. Applicability is computed with SPARQL and validation uses SHACL (rdflib and pySHACL), with results embedded in the page.

## Notes

- Prototype with illustrative data. Not legal advice.
- Provisions are paraphrased. ISO/IEC 42001 clause numbers come from secondary sources, and mappings are proposed pending expert validation.
- The login is for demonstration only. Nothing typed is stored or sent anywhere, and demo progress is kept only in the visitor's own browser.
- GovBridge AI has been selected to be featured in the UN AI Dialogue Partnerships Hub. This gives visibility to an independent initiative; it is not UN endorsement, funding, adoption or ownership.

Dr. Abeer S. Al-Humaimeedy · Blockchain & Web3 Lab, King Saud University
