# Facilitator's Guide - Jump Start Workshop: Payment & Transaction Processing

This is the facilitator's guide for the [Payment & Transaction Processing Jump Start workshop](https://github.com/Azure/Real-Time-Transactions-Hackathon).

## Introduction for Facilitators

Jump Start workshops are immersive experiences where participants collaborate in a working environment, utilizing provided resources and requirements. These workshops are not traditional training sessions or labs but rather hands-on experiences designed to foster learning through problem-solving and exploration.

As a facilitator, your role is to guide and encourage attendees to talk through their real world challenges. While you may offer guidance and insights, it's important not to provide direct solutions. The value participants derive from the workshop lies in the satisfaction of coming up with solutions and the deep learning that accompanies the experience.

> [!NOTE]
> For additional guidance, refer to the [Facilitator's Guide](facilitator/README.md).

## Preparing to Facilitate the Payment & Transaction Processing Jump Start Workshop

Before facilitating the workshop, ensure you are fully prepared.

### 1. Build Foundational Knowledge

Facilitators for the Payment & Transaction Processing workshop require knowledge about Azure Cosmos DB, event sourcing, Azure OpenAI, application development, Azure Synapse Analytics, and orchestration using Semantic Kernel.

Familiarize yourself with the following services and concepts:

- [Azure Cosmos DB](https://learn.microsoft.com/azure/cosmos-db/)
- [Azure OpenAI](https://learn.microsoft.com/azure/cognitive-services/openai/overview)
- [Azure Cosmos DB partial document update (patch operation)](https://learn.microsoft.com/azure/cosmos-db/partial-document-update)
- [Semantic Kernel](https://learn.microsoft.com/semantic-kernel/overview/)

Understanding prompt engineering and effective system prompts is crucial.

> Watch the [walkthrough video](https://aka.ms/TxProcessingWalkThroughVideo) to see the solution in action.

> Watch the [solution deep dive walkthrough video](https://aka.ms/TxProcessingDeepDiveVideo) for a comprehensive understanding of the architecture, source code, and application flow. Please do not share this video with attendees.

> Utilize the [Deep Dive PowerPoint Presentation](./deep-dive/Real_Time_Payment_Trx_Processing_Solution_Deep_Dive.pptx) with included talk track to redeliver the deep dive video yourself. **NOTE: you should not deliver this to customers before the workshop.**

### 2. Complete the Workshop Topics

Ideally, participate in the workshop as a learner or complete the workshop independently to understand the experience firsthand. Attempt to solve business challenges using provided instructions, referring to this guide for additional context only when necessary.

> **Note**: The provided solutions are for reference, but encourage teams to explore alternative paths.

### 3. Prepare to Support Your Team

This document incorporates insights from content authors and experienced facilitators. Read through the guidance to ensure your team has a positive and successful workshop experience.

## Jump Start Guidance

The following sections provide guidance for supporting your team as they navigate through the workshop.

### General Expectations

The workshop consists of a series of topics guiding participants to explore and complete a proof of concept (POC) of a financial application. The solution implements high availability through a multi-region deployment of resources, including the Cosmos DB workspace. It involves implementing a global index for efficient member/account lookups and a CQRS pattern (Command and Query Responsibility Segregation) through event sourcing.

Attendees must work as a team to deploy a multi-region solution, implement an event sourcing pattern with the change feed, enforce business rules within transactions, efficiently patch data, use Semantic Kernel as an orchestrator, and extend Semantic Kernel to add new functionality. If participants worked for an organization tasked with building a POC of a line of business application providing similar functionality, they would likely follow a similar path.
