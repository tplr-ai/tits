# Templar Improvement Tenets (TIPs)

Welcome to the Templar Improvement Tenets (TIPs)
[repository](https://github.com/opentensor/bits). This repository serves as the central
location for submitting, discussing, and tracking proposals for changes and improvements to the
Templar protocol.

## What are TIPs?

A Templar Improvement Tenet (TIPs) is a technical design document providing information to
the Templar community or describing new features for the Templar protocol and surrounding
ecosystem. A TIPs should provide a convincing rationale for and a concise technical
specification of any underlying features described in the TIPs. TIPs are intended to be the
primary mechanism for proposing new features and changes, collecting community input on an
issue, and documenting design decisions that impact the protocol.

## Types of TIPs

TIPs are classified into the following categories:

- **Core:** Proposals that impact the core Templar protocol and consensus rules.
- **Subtensor:** Proposals that relate to the Subtensor blockchain and related functionality.
- **Networking:** Proposals related to networking protocols, node interactions, or networking
  infrastructure.
- **Interface:** Proposals related to API, CLI, or user interface improvements.
- **Meta:** Proposals about processes or changes to the TIPs system itself.
- **Informational:** Proposals that provide general guidelines or information to the Templar
  community but do not propose a new feature.

## TIPs Lifecycle

TIPs pass through several stages before it becomes final:

- **Draft:** The initial state of a TIPs when submitted as a pull request. In this stage, the
  TIPs is open for discussion and feedback.
- **Review:** The TIPs has passed the initial review and is now under formal review by the TIPs
  editors and the community.
- **Last Call:** The TIPs is nearing finalization and has a set period for final comments and
  objections.
- **Final:** The TIPs is considered complete and implemented (or ready for implementation).
- **Stagnant:** The TIPs has not been updated for a significant period or lacks consensus, so it
  is no longer considered active.
- **Withdrawn:** The author of the TIPs has decided to withdraw the proposal.
- **Living:** The TIPs is a living document that is continually updated with new information
  (e.g., coding standards or best practices).

## How to Submit TIPs

1. **Fork this repository.**
2. **Create a new file** in the `bits/` directory named `TIPs-XXXX.md`, where `XXXX` is the next
   available TIPs number. You can use the [TIPs tenet](bits/TIPs-0000-tenet.md) as a starting
   point.
3. **Fill in the tenet** with your proposal details.
4. **Submit a pull request** with your new TIPs. The title should be "TIPs-XXXX: [Title]" where
   `XXXX` is your TIPs number.
5. **Engage in the discussion**: Address any feedback from the community and TIPs editors during
   the review process.

## TIPs Numbering

TIPs are assigned numbers in the order they are proposed. The number `0000` is reserved for the
TIPs tenet. Once a TIPs is accepted and merged, its number is locked and cannot be changed.

## Roles and Responsibilities

- **Author:** The person who wrote and is responsible for the TIPs.
- **Editor:** A member of the community who is responsible for ensuring that TIPs are clear,
  concise, and meet the repository's standards. Editors do not make decisions about TIPs
  approval but facilitate the process.
- **Reviewer:** Any community member who reviews and provides feedback on TIPs during the Draft
  and Review stages.

## Discussions

A discussion forum is provided at https://github.com/opentensor/bits/discussions for discussing
preliminary ideas and collecting informal feedback before submitting a TIPs.

## FAQs

### What is the purpose of TIPs?
TIPs serve as the primary mechanism for proposing new features or changes to the Templar
protocol, fostering open-source development, transparency, and structured decision-making.

### How are TIPs approved?
TIPs are approved through community consensus during the Review and Last Call stages. Editors
facilitate the process but do not unilaterally approve TIPs.

### Can I update TIPs after they are finalized?
Once TIPs are finalized, they are generally considered complete. However, living TIPs are an
exception and can be updated regularly.

## Related Links

- [Ethereum Improvement Proposals (EIPs)](https://eips.ethereum.org/)
- [Bitcoin Improvement Proposals (BIPs)](https://github.com/bitcoin/BIPs)

## License

This repository and all TIPs are licensed under [The Unlicense](LICENSE).

---

This repository is a work in progress, and we welcome your contributions and feedback to
improve the TIPs process.
