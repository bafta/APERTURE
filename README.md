# APERTURE -  Paillier Encryption Approach

Advancing Participation, Equity, Representation, and Trust in  Unified Research for EDI

## Overview

This repository contains a technical paper describing a proposed approach to using **Paillier homomorphic encryption** to support privacy-preserving aggregation of workforce diversity data.

The work forms part of Project *Aperture*, an R&D initiative exploring how sensitive equality, diversity and inclusion (EDI) data can be:

* Collected transparently
* Stored securely
* Aggregated without exposing individual-level responses
* Used to generate compliant, privacy-preserving reports

The document outlines the architectural model, threat considerations, and the rationale for selecting an additive homomorphic scheme.

Further to defining the architecture here, a working prototype has been built which uses Javascript to Paillier encrypt user responses to a simple diversity questionnaire, which are then stored and aggregated on the server in PHP. The code for thie protorype implementation can be found here:
* [PHP wrapper for exsiting RUST Paillier library](https://github.com/bafta/APERTURE_paillier-php)
* [Prototype for questionnaire and reporting UI](https://github.com/bafta/APERTURE_poc-ui)

---

## External Security Review

The proposed approach has undergone independent external review by **Radically Open Security**.

The repository includes:

* The technical approach document
* The independent review report

This review provides critical assessment of the cryptographic design and its suitability for the intended use case.

---

## Current Status

There is no code in this repository at present.

We are currently developing a proof-of-concept implementation of the proposed approach, which will be added here later this year.

---

## Purpose

The materials are published to:

* Provide transparency around the proposed cryptographic approach
* Enable technical scrutiny and discussion
* Support wider research into secure diversity data systems

---
