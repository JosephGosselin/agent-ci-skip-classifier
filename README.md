# agent-ci-skip-classifier
AI coding agents often complete a task through many small commits, and each commit can trigger a full CI run, which wastes CI minutes and resources when the change doesn’t need it. This project studies how AI agents use CI-skip mechanisms compared with human developers and how many unnecessary CI runs their iterations cause. In response to these findings, we built a classifier that predicts whether an agent’s commit can safely skip CI, deployed as an advise-only GitHub Action that recommends a decision without skipping any runs.

## Research Questions

-Note that this project is currently in progress and these research questions will be filled out after the completion of this project.

**RQ1: How do AI coding agents use CI-skip mechanisms compared with human developers?**
- Current CI skip mechanisms were designed based on human commits, and it unknown how AI agents use these skip mechanisms and whether there skips are appropriate.

**Research in progress**

**RQ2: How many unnecessary CI runs do agent iterations cause?**
- Agents work on completing a task through small commits until the task is completed. Each commit can trigger a CI run, which wastes CI minutes, increase CI queue times, and increase the costs of running CI.

**Research in progress**

**RQ3: Can existing CI-skip models accurately predict which agent commits can safely skip CI?**
- Existing CI models already exist and perform well under human commits, but agent commits differ in message style, size, and frequency when compared to human commits. It is unknown if they can accurately predict which agent commits can safely skip CI.

**Research in progress**

**RQ4: How much CI could the tool save, and at what risk?**
- Skipping CI saving both time and resources, but an invalid CI skip can lead to letting a failure through or delaying when it is caught.

**Research in progress**

## Example

**Picture of action component giving a recommendation on a pull request (In progress)**

## Workflow Diagram 

**In progress**

## Quick Start
**In progress**

## Tech stack
**In progress**


## Contributions
- Joseph Gosselin:
- Krish Chougule:
- Henry Lee:
- Gian Dampor: 
