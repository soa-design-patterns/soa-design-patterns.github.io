---
layout: default
comments: true
---

# [](#summery) Summary

How can services be designed to avoid data model transformation?

## [](#problem) Problem
Services with disparate models for similar data impose transformation requirements that increase development effort, design complexity, and runtime performance overhead.

## [](#solution) Solution
Data models for common information sets are standardized across service contracts within an inventory boundary.

## [](#application) Application
Design standards are applied to schemas used by service contracts as part of a formal design process.

## [](#impacts) Impacts
Maintaining the standardization of contract schemas can introduce significant governance effort and cultural challenges.

## [](#priciples) Principles
Standardized Service Contract

## [](#Architecture) Architecture
Inventory, Service

# [](#profile) (Semi)Formalized Profile
## [](#vocabulary) Vocabulary
![vocabulary](./images/CanonicalSchema-vocabulary.png)

## [](#problem) Problem Variants
### [](#problem1) Model transformation is required
![problem1](./images/CanonicalSchemaTransformationIsRequired.png)

### [](#problem2) Model transformation is implemented
![problem2](./images/CanonicalSchemaTransformationExists.png)

## [](#solution) Solution Variants
### [](#solution1) Standardized model for data is defined
![solution](./images/CanonicalSchemaSolution.png)

## [](#application) Application
### [](#application1) Tranformation implmenentation is removed
![application1](./images/CanonicalSchemaTransformationExistsPR.png)

### [](#application2) Standardized model is defined
![application1](./images/CanonicalSchemaTransformationIsRequiredPR.png)



**[Back](./)**

{% disqus %}