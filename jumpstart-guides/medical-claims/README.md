# Facilitator's Guide - Jump Start Workshop: Medical Claims Transaction Processing

Facilitator's guide for conducting the [Jump Start workshop on Medical Claims Transaction Processing](https://github.com/Capgemini/Jump-Start-Medical-Claims-Processing).

## Introduction for Facilitators

Jump Start workshops are immersive experiences where participants collaborate in a working environment, utilizing provided resources and requirements. These workshops are not traditional training sessions or labs but rather hands-on experiences designed to foster learning through problem-solving and exploration.

As a facilitator, your role is to guide and encourage attendees to talk through their real world challenges. While you may offer guidance and insights, it's important not to provide direct solutions. The value participants derive from the workshop lies in the satisfaction of coming up with solutions and the deep learning that accompanies the experience.

So, what does facilitating entail?

- **Facilitating Team Collaboration**: Lead team discussions, ensure all members are involved, and provide a platform for brainstorming while keeping the focus on long term challenge resolution.

- **Addressing Technical Issues**: Assist with technical hurdles unrelated to the workshop, such as command line usage or network authentication.

- **Explaining Concepts**: Clarify underlying concepts when necessary to aid understanding, beyond simply providing code solutions.

- **Managing Team Morale**: Recognize and manage team morale, especially during challenging moments. Guide teams through obstacles with leading questions or suggestions.

- **Validating Solutions**: Assess workshop solutions against criteria and celebrate team successes.

> [!NOTE]
> For additional guidance, refer to the [Facilitator's Guide](facilitator/README.md).

## Preparation for Facilitating the Medical Claims Transaction Processing Jump Start Workshop

Before facilitating the workshop, ensure you are fully prepared.

### 1. Build Foundational Knowledge

Facilitators for the Medical Claims Transaction Processing workshop require knowledge about Azure Cosmos DB, event sourcing, Azure OpenAI, application development, Azure Synapse Analytics, and Semantic Kernel orchestration.

Familiarize yourself with the following services and concepts:

**Services:**
- [Azure Cosmos DB](https://learn.microsoft.com/azure/cosmos-db/)
- [Azure OpenAI](https://learn.microsoft.com/azure/cognitive-services/openai/overview)
- [Integrate with Azure Synapse Analytics pipelines](https://learn.microsoft.com/azure/synapse-analytics/get-started-pipelines)
- [Semantic Kernel](https://learn.microsoft.com/semantic-kernel/overview/)

**Concepts:**
- [Prompt engineering](https://learn.microsoft.com/semantic-kernel/overview/)
- [Effective system prompts](https://learn.microsoft.com/azure/cognitive-services/openai/concepts/system-message)

Understanding the solution accelerator and its functionalities is crucial.

> Watch the [walkthrough video](https://aka.ms/MedicalClaimsWalkThroughVideo) to see the solution in action.

> Watch the [solution deep dive walkthrough video](https://aka.ms/MedicalClaimsDeepDiveVideo) for a comprehensive understanding of the architecture, source code, and application flow. Please do not share this video with attendees.

> Utilize the provided [Deep Dive PowerPoint Presentation](./deep-dive/Medical_Claims_Trx_Processing_Solution_Deep_Dive.pptx) with included talk track to redeliver the deep dive video yourself. **NOTE: you should not deliver this to customers before the workshop.**

### 2. Complete the Workshop Topics

Ideally, participate in the workshop as a learner or complete the workshop independently to understand the experience firsthand. Attempt to solve business challenges using provided instructions, referring to this guide for additional context only when necessary.

> **Note**: The provided solutions are for reference, but encourage teams to explore alternative paths.

### 3. Prepare to Support Your Attendees

This document incorporates insights from content authors and experienced facilitators. Read through the guidance to ensure your team has a positive and successful workshop experience.

## Jump Start Guidance

The following sections provide guidance for supporting your team as they navigate through the topics.

### General Expectations

The workshop comprises topics structured to emulate the process of building a relatively complex line of business application for medical claims transaction processing. Participants must work as a team to implement business rules within an event sourcing pattern, load data, and leverage Semantic Kernel for orchestration. Encourage participants to follow a logical progression, akin to real-world scenario implementations.
