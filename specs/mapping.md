# Mapping to External Standards and Regulations

## Introduction

This ontology is not developed in isolation. It is designed with a forward-looking perspective to align with, support, and provide a concrete technical foundation for major international standards and regulations concerning Artificial Intelligence, digital identity, and data governance.

By mapping our core concepts to these frameworks, we aim to ensure that systems built on this ontology can more easily demonstrate compliance and interoperability within a global regulatory landscape.

This document outlines the relationship between the key concepts of the Semantic Agent Ontology and several significant external standards.

---

## Mapping Table

| Ontology Concept(s) | Related Standard / Regulation | Relationship and Rationale |
| :--- | :--- | :--- |
| **`core:Agent`** | **EU AI Act** | Provides a clear, machine-readable definition for what constitutes an "AI system" or "agent". This allows for precise classification of agents according to risk levels (e.g., limited, high-risk) and facilitates automated conformity assessments and registration in the EU database as required by the Act. |
| **`del:Delegation`** | **EU Digital Identity Wallet (EUDI) & eIDAS 2.0** | The `Delegation` model directly aligns with the concept of **Mandates** and **Attestations of Attributes** within the EUDI Architecture and Reference Framework (ARF). It provides a semantic structure for a wallet holder (a natural or legal person) to delegate rights to another party, such as an AI agent, to act legally on their behalf. |
| **`ledger:LedgerEvent`** <br> **`acc:AccountabilityEvent`** | **EU AI Act (Articles 13, 15, 20)** | Directly supports the stringent requirements for **logging, traceability, and post-market monitoring** for high-risk AI systems. The immutable, ledger-based record of every agent action provides a reliable and auditable data source for quality management systems, incident reporting, and regulatory oversight. |
| **TEE/DID/Audit Chain Binding** | **ISO/IEC 42001 (AI Management System)** <br> **Cyber Resilience Act (CRA)** | Provides a concrete technical mechanism for ensuring the **integrity, authenticity, and confidentiality** of AI system records and operations. This cryptographic binding is a cornerstone for building a robust AI Management System (AIMS) as specified by ISO 42001 and for demonstrating the security-by-design principles required by the CRA. |
| **`core:Capability`** | **EU Data Act** | The `Capability` concept can be used to formally and granularly define the scope of data access and usage rights granted to third parties (or their agents). This supports the Data Act's goal of ensuring that data is used fairly and only for its intended, agreed-upon purpose, by making the permissions machine-interpretable. |
| **`core:Agent`** <br> **`del:Delegation`** | **UN/CEFACT** <br> **(Cross-border Trade)** | In the context of international trade, an `Agent` can represent a legal entity (e.g., an importer, exporter, or logistics provider). The `Delegation` model provides a standardized way to manage complex authorization chains for trade documents and processes (e.g., authorizing a customs broker agent to file declarations), enhancing automation and traceability in cross-border supply chains. |

---

This mapping is a living document and will be updated as both the ontology and the regulatory landscape evolve.
