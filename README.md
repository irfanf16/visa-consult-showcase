# Visa Consult — Immigration Consultancy Platform

**Case management · Laravel**

Immigration case management — applications modelled as a state machine with per-stage document requirements, plus scheduling and reporting.

> **Source code is private.** This repository documents the architecture and engineering work.

## My role
Full-stack engineer — case workflow, document handling and reporting.

## Engineering highlights

**Document-centric workflow.** Visa applications are document-heavy and stateful; the system models each case as a state machine with per-stage required documents, so a case cannot advance until its evidence is complete.

**Image and document processing.** `intervention/image` normalises and compresses uploaded passport scans and supporting documents on ingest, keeping storage predictable.

**Bulk reporting.** `maatwebsite/excel` for case exports and consultant reporting, with Yajra DataTables handling server-side pagination and filtering across large case tables.

**Appointment scheduling.** Consultant availability and client booking integrated into the case timeline.


## Screenshots

<!-- ![Case Timeline](docs/case-timeline.png) -->
<!-- ![Document Checklist](docs/document-checklist.png) -->

_Screenshots pending — see `docs/README.md`._

## Stack

`Laravel` · `PHP` · `MySQL` · `Blade` · `JavaScript` · `DataTables` · `Excel` · `Sanctum`
