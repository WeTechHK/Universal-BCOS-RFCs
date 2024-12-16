# Universal BCOS Improvement Proposal (UBIP) Guide

The Universal BCOS Improvement Proposal (UBIP) serves as a standardized framework for introducing, discussing, and refining new requirements, features, or optimizations for Universal BCOS. By utilizing the UBIP process, community members can collaboratively improve Universal BCOS’s design and functionality, ensuring the project’s sustained growth and iterative updates.

## Objectives

The primary objective of UBIP is to provide clear, actionable suggestions for feature enhancements, interface specifications, protocol designs, or logical flow optimizations for one or more modules of Universal BCOS. Through collaborative discussions and reviews, UBIPs form the foundation for planning Universal BCOS’s future development.

## Roles and Responsibilities

1. **Proposal Author**: Submits a UBIP, ensuring it adheres to the required standards and templates.
2. **Proposal Reviewer**: Selected from the core development team, responsible for conducting a preliminary review of submitted proposals.
3. **Review Committee**: Composed of Maintainers, tasked with voting on proposals in the `Draft` and `Accepted` stages. They determine whether a proposal is approved and ready for release.

## How to Submit a UBIP

**All proposals are managed through GitHub issues within the designated repository.** A proposal is archived in the repository’s codebase only after it reaches the `Final` stage.

Before initiating a UBIP, ensure that your ideas are well-prepared and clearly articulated. Below are the steps and recommendations for submitting a UBIP:

### Preparation

- **Define Objectives**: Ensure your proposal aligns with Universal BCOS’s development roadmap and addresses existing issues or introduces meaningful improvements.
- **Engage the Community**: Before formally submitting a proposal, share your ideas within the community to gather initial feedback from developers and users. This helps validate the proposal’s feasibility and necessity.
- **Use the Template**: Draft your proposal using the standard UBIP template to ensure clarity and facilitate community understanding and review.

### Proposal Workflow

The UBIP lifecycle consists of the following stages:

#### **Stage: `Proposal`**

- The author drafts the UBIP using the provided template and submits it as a [GitHub issue](https://github.com/WeTechHK/Universal-BCOS-RFCs/issues/new/choose).
- Community members engage in discussions to evaluate the proposal’s necessity and feasibility.
- If the Proposal Reviewer deems the submission valid, it is assigned a unique ID, tagged as `Draft`, and moves to the next stage.

#### **Stage: `Draft`**

- The author refines the proposal based on community feedback, incorporating technical details and implementation plans.
- Community members participate in ongoing discussions, providing suggestions for improvement.
- The Review Committee votes on the proposal. If more than half of the Maintainers approve, the proposal is tagged as `Accepted` and progresses to the next stage. Otherwise, the author may revise and resubmit the proposal or mark it as `Canceled`.

#### **Stage: `Accepted`**

- A feature or bugfix branch is created for the proposal.
- Community developers contribute to the implementation, submitting code to the designated branch.
- Smoke testing is conducted to validate development progress.
- Following successful smoke testing, the Review Committee votes to integrate the proposal into a specific version. If the majority approves, the proposal is tagged as `Implemented` and moves to the next stage. Otherwise, further revisions are required.

#### **Stage: `Implemented`**

- The proposal enters the implementation phase, where the testing team performs rigorous validation of the code.
- Proposal developers address issues raised during testing and provide necessary fixes.

#### **Stage: `Final`**

- Once the proposed functionality is included in a release, the proposal is marked as `Final` and archived in the UBIP repository’s codebase.
