# Templar Improvement Tenets (TITss)

Welcome to the Templar Improvement Tenets (TITss)
[repository](https://github.com/opentensor/bits). This repository serves as the central
location for submitting, discussing, and tracking proposals for changes and improvements to the
Templar protocol.

## What are TITss?

A Templar Improvement Tenet (TITs) is a technical design document providing information to
the Templar community or describing new features for the Templar protocol and surrounding
ecosystem. A TITs should provide a convincing rationale for and a concise technical
specification of any underlying features described in the TITs. TITss are intended to be the
primary mechanism for proposing new features and changes, collecting community input on an
issue, and documenting design decisions that impact the protocol.

## Types of TITss

TITss are classified into the following categories:

- **Core:** Proposals that impact the core Templar protocol and consensus rules.
- **Subtensor:** Proposals that relate to the Subtensor blockchain and related functionality.
- **Networking:** Proposals related to networking protocols, node interactions, or networking
  infrastructure.
- **Interface:** Proposals related to API, CLI, or user interface improvements.
- **Meta:** Proposals about processes or changes to the TITss system itself.
- **Informational:** Proposals that provide general guidelines or information to the Templar
  community but do not propose a new feature.

## TITss Lifecycle

TITss pass through several stages before it becomes final:

- **Draft:** The initial state of a TITs when submitted as a pull request. In this stage, the
  TITs is open for discussion and feedback.
- **Review:** The TITs has passed the initial review and is now under formal review by the TITs
  editors and the community.
- **Last Call:** The TITs is nearing finalization and has a set period for final comments and
  objections.
- **Final:** The TITs is considered complete and implemented (or ready for implementation).
- **Stagnant:** The TITs has not been updated for a significant period or lacks consensus, so it
  is no longer considered active.
- **Withdrawn:** The author of the TITs has decided to withdraw the proposal.
- **Living:** The TITs is a living document that is continually updated with new information
  (e.g., coding standards or best practices).

## How to Submit TITss

1. **Fork this repository.**
2. **Create a new file** in the `bits/` directory named `TITs-XXXX.md`, where `XXXX` is the next
   available TITs number. You can use the [TITs tenet](bits/TITs-0000-tenet.md) as a starting
   point.
3. **Fill in the tenet** with your proposal details.
4. **Submit a pull request** with your new TITs. The title should be "TITs-XXXX: [Title]" where
   `XXXX` is your TITs number.
5. **Engage in the discussion**: Address any feedback from the community and TITs editors during
   the review process.

## TITss Numbering

TITss are assigned numbers in the order they are proposed. The number `0000` is reserved for the
TITs tenet. Once a TITs is accepted and merged, its number is locked and cannot be changed.

## Roles and Responsibilities

- **Author:** The person who wrote and is responsible for the TITs.
- **Editor:** A member of the community who is responsible for ensuring that TITss are clear,
  concise, and meet the repository's standards. Editors do not make decisions about TITs
  approval but facilitate the process.
- **Reviewer:** Any community member who reviews and provides feedback on TITss during the Draft
  and Review stages.

## Discussions

A discussion forum is provided at https://github.com/opentensor/bits/discussions for discussing
preliminary ideas and collecting informal feedback before submitting a TITs.

## FAQs

### What is the purpose of TITss?
TITss serve as the primary mechanism for proposing new features or changes to the Templar
protocol, fostering open-source development, transparency, and structured decision-making.

### How are TITss approved?
TITss are approved through community consensus during the Review and Last Call stages. Editors
facilitate the process but do not unilaterally approve TITss.

### Can I update TITss after they are finalized?
Once TITss are finalized, they are generally considered complete. However, living TITss are an
exception and can be updated regularly.

## Related Links

- [Ethereum Improvement Proposals (EIPs)](https://eips.ethereum.org/)
- [Bitcoin Improvement Proposals (BIPs)](https://github.com/bitcoin/BIPs)

## License

This repository and all TITss are licensed under [The Unlicense](LICENSE).

---

This repository is a work in progress, and we welcome your contributions and feedback to
improve the TITss process.
