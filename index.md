---
layout: default
---

# BerryWorks Software

**EDI technology for developers and integration projects**

BerryWorks Software develops and maintains EDIReader, a family of Java-based EDI technologies for processing X12, EDIFACT, and HL7 data.

EDIReader began as an open-source EDI parser and has evolved into a broader framework for building EDI applications, integrations, APIs, automation, and specialized trading-partner solutions.

The goal is straightforward: provide developers with proven EDI processing technology so they can concentrate on the business integration they need to build.

---

## The EDIReader Technology Stack

### EDIReader — Open Source EDI Parser

**A lightweight, streaming EDI parser for Java**

[EDIReader on GitHub](https://github.com/BerryWorksSoftware/edireader)

EDIReader is the foundation of the EDIReader technology stack. Written in pure Java and based on the SAX API, it provides streaming parsing of EDI without requiring the entire document to be loaded into memory.

It supports:

- X12
- EDIFACT
- HL7
- Automatic detection of EDI syntax and delimiters
- Multiple interchanges, groups, and transactions
- Streaming processing of large EDI files
- Java integration through standard SAX interfaces
- Detailed EDI syntax error reporting
- X12 997/999 and EDIFACT CONTRL acknowledgments

EDIReader has been used in production EDI systems across industries and integration environments for many years.

**License:** GNU GPL v3 open source. Commercial licensing is also available for applications where GPL licensing is not appropriate.

---

### EDIReader Framework — Community Edition

**EDI to JSON for Java**

[EDI to JSON on GitHub](https://github.com/BerryWorksSoftware/edi-json)

The EDIReader Framework builds on the core parser with higher-level EDI processing capabilities.

The **Community Edition** provides a simple way for Java developers to convert X12, EDIFACT, and HL7 documents into structured JSON.

It is intended for developers who need practical EDI processing without deploying a complete commercial EDI platform.

Typical uses include:

- Receiving EDI from a customer, supplier, payer, or other trading partner
- Converting EDI into JSON for application processing
- Feeding EDI data into databases, APIs, automation, or integration workflows
- Building a focused trading-partner integration
- Adding EDI support to an existing Java application

The repository includes both a simple command-line converter and a small Java example demonstrating how to embed EDI-to-JSON conversion directly into an application.

The Community Edition is available from Maven Central and is free for commercial use under its license.

**The EDIReader Framework Community Edition is not open-source software.**

---

### EDIReader Framework — Enterprise Edition

**A complete EDI processing engine for custom integration**

The Enterprise Edition extends the Framework beyond EDI-to-JSON conversion for applications requiring more complete EDI processing.

Capabilities include:

- EDI to JSON
- JSON to EDI
- EDI validation and compliance checking
- Splitting multi-transaction EDI streams
- EDI document generation
- Technical acknowledgments
- Business transaction responses
- EDI annotations and metadata
- Support for building specialized EDI workflows

The Framework is designed to be embedded in applications and services rather than requiring EDI data to be sent to an external processing platform.

This makes it particularly useful for custom integration projects where performance, data control, security, or specialized business logic are important.

The Enterprise Edition is commercially licensed by BerryWorks Software.

---

## Choosing the Right Level

| | EDIReader Parser | Framework Community | Framework Enterprise |
|---|---|---|---|
| X12 / EDIFACT / HL7 parsing | ✓ | ✓ | ✓ |
| Streaming processing | ✓ | ✓ | ✓ |
| EDI → JSON | | ✓ | ✓ |
| JSON → EDI | | | ✓ |
| Advanced validation | | | ✓ |
| Split EDI transactions | | | ✓ |
| Generate EDI documents | | | ✓ |
| Open source | ✓ | | |
| Free for commercial use | GPLv3* | ✓ | |
| Commercial license | Available | | ✓ |

\* Use of the open-source EDIReader parser is subject to the GPLv3 license. A separate commercial license is available when GPL licensing is not appropriate.

---

## Build the EDI Solution You Actually Need

Not every organization needs a large EDI platform.

A company with development resources and a well-defined trading-partner requirement may need something much narrower: receive a few EDI transaction types, extract the information needed by an existing application, generate responses, or connect EDI with an internal API or database.

The EDIReader Framework is designed to support that kind of development.

Instead of implementing the EDI syntax, standards, parsing, validation, and document generation layers from scratch, developers can use the Framework as the EDI engine and concentrate on the application-specific integration.

Examples include:

- Healthcare claim and remittance processing
- Purchase order and fulfillment workflows
- Supplier and customer EDI integrations
- EDI-to-database pipelines
- EDI-to-REST integration
- Automated EDI processing
- High-volume EDI processing
- Specialized trading-partner solutions

---

## Consulting and Custom EDI Development

BerryWorks Software also provides software development and consulting for organizations with specific EDI integration requirements.

The emphasis is on **focused engineering solutions**: understanding the trading-partner requirement, selecting the EDI capabilities actually needed, and integrating them cleanly with the organization's existing systems.

Areas of experience include:

- X12 healthcare transactions such as 837, 835, 277, 999, and related workflows
- X12 supply-chain transactions such as 850, 855, 856, 810, and 824
- EDIFACT
- HL7
- Java and REST API development
- Python integration
- High-throughput EDI processing
- EDI validation
- EDI-to-database pipelines
- Custom EDI transformation and business-response workflows

Engagements can range from helping design an EDI architecture to implementing a focused integration or embedding EDIReader into an existing product.

---

## Additional Open Source

### JQuantify — Lightweight Java Application Metrics

[JQuantify on GitHub](https://github.com/BerryWorksSoftware/jquantify)

JQuantify is an open-source library from BerryWorks Software for measuring how often application events occur, how long operations take, and how many operations overlap. Developers add simple counters or start/stop calls to collect statistics within their Java applications.

The project includes examples and utilities for reporting metrics in CSV and HTML formats.

---

## BerryWave Software

The EDIReader Framework also provides the underlying EDI processing technology for products developed by **BerryWave Software**.

### BerryWave API for EDI

The BerryWave API exposes EDI processing through an on-premises REST API.

Applications and automation platforms can use standard HTTP operations to perform EDI processing without embedding the Java Framework directly.

[BerryWave API for EDI](https://www.berrywave-edi.com/)

### BerryWave Python EDI SDK

The BerryWave Python EDI SDK provides Python-native access to the EDI processing engine.

It is intended for Python applications, data pipelines, automation, and AI/agent-based systems that need to parse, create, validate, acknowledge, or otherwise process EDI.

[BerryWave Python EDI SDK on PyPI](https://pypi.org/project/berrywave-edi/)

---

## A Proven EDI Foundation

EDIReader has been developed and refined over many years of real-world EDI processing.

Its architecture emphasizes:

- Streaming rather than memory-intensive document processing
- High throughput
- Thread-safe operation
- Minimal dependencies
- Embeddability
- Local and on-premises processing
- Developer-oriented APIs

The same underlying technology can therefore serve very different requirements—from a developer parsing an EDI file in a Java application to an enterprise processing large volumes of business transactions.

---

## Projects

**Open Source EDI Parser**  
[BerryWorksSoftware/edireader](https://github.com/BerryWorksSoftware/edireader)

**EDIReader Framework Community Edition — EDI to JSON**  
[BerryWorksSoftware/edi-json](https://github.com/BerryWorksSoftware/edi-json)

**JQuantify — Java Application Metrics**  
[BerryWorksSoftware/jquantify](https://github.com/BerryWorksSoftware/jquantify)

**BerryWave API for EDI**  
[berrywave-edi.com](https://www.berrywave-edi.com/)

**BerryWave Python EDI SDK**  
[PyPI: berrywave-edi](https://pypi.org/project/berrywave-edi/)

---

## About BerryWorks Software

BerryWorks Software develops EDI processing technology and provides software engineering expertise for custom EDI integration.

The EDIReader technology has evolved from an open-source Java EDI parser into a reusable foundation for modern EDI applications, APIs, Python integration, automation, and specialized enterprise workflows.

For questions about EDIReader, commercial licensing, or custom EDI development, contact BerryWorks Software.
