# Unit Tests project

## Introduction

Unit Test project that validates and test the Fulfillment and metering service API calls generated from the SaaS SDK Client Library.

## Description

The Unit Tests project will continue to evolve to include a larger set of tests and would include mocks to validate the API calls done by the **[Fulfillment v2](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-api-v2)** and **[Metering service](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/marketplace-metering-service-apis)** APIs

## Source Code

The Project is located in the **SaaS.SDK.UnitTest** folder. The project is composed of the following sections:

| Section Name | Description |
| --- | --- |  
| Dependencies | SaaS.SDK.Client, MSTest Framework MSTest TestAdapter, and Microsoft Configuration Extensions |
| FullfillmentAPItest.cs | Contains the Unit tests for the **[Fulfillment v2](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-api-v2)** API  |
| MeteredAPITest.cs | Contains the Unit tests for the **[Metering service](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/marketplace-metering-service-apis)** API |
