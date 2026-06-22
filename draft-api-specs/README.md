# Draft API Specifications

> [!WARNING] 
> This repository is for the working group to use while drafting documentation and specifications before they are formally ratified.  Users outside of the working group **SHOULD NOT** begin implementing solutions based on the content in this repository as it is likely to change without notice.

The working group's draft OpenAPI specification is available in this directory.  Once the API specification has been reviewed and approved by the [Governance Committee](https://www.irionline.org/member-programs/operations-technology/committee-hub/governance/), it will be moved into the [Digital-First-Specifications](https://github.com/Insured-Retirement-Institute/Digital-First-Specifications) repository and published at [specs.dfa.irionline.org](https://specs.dfa.irionline.org).

Please refer to the [Digital-First-Specifications](https://github.com/Insured-Retirement-Institute/Digital-First-Specifications) repository for technical governance of standards, style guide, data dictionary, and the code of conduct.

# Version Numbering for Working Drafts

All API specification MUST use [SemVer 2.0.0](https://semver.org/) version strings.

**Pre-ratification (no prior approved version exists)**: The major version MUST be 0. Working groups MAY freely increment minor and patch versions (e.g. `0.1.0`, `0.2.0`, `0.14.0`). A major version of 0 signals that no stability guarantees exist.

**Post-ratification (one or more approved versions exist)**: Once the API specification has been published in the [Digital-First-Specifications](https://github.com/Insured-Retirement-Institute/Digital-First-Specifications) repository,  proposed changes to the specification MUST select a target version number consistent with semver, for example:
* A breaking change to a ratified spec requires a major version bump
* Backward-compatible additions require a minor bump.
* Drafts in this repository MUST append a pre-release identifier to the target version using the form <target>-draft.<N> (e.g. `2.0.0-draft.1`). When a working group considers a draft ready for ratification, it SHOULD advance the suffix to -rc.<N> (e.g. `2.0.0-rc.1`). The clean version (no suffix) is reserved for the versions ratified by IRI and published to the [Digital-First-Specifications](https://github.com/Insured-Retirement-Institute/Digital-First-Specifications) repository.

**General rules**:
* Major versions MUST NOT be skipped (e.g. ratifying 3.0.0 requires a prior ratified 2.0.0).
* IRI will ratify the final version number. Working group target numbers are proposals; IRI MAY require a different version if the semver classification is incorrect (e.g. a breaking change labeled as minor).
* Multiple working drafts targeting different versions MAY coexist (e.g. a 1.1.0-draft.2 adding features alongside a 2.0.0-draft.1 introducing a breaking redesign).

## Supporting documentation

- [Application-Status_OpenAPI_2.0.0-rc.1.yaml](Application-Status_OpenAPI_2.0.0-rc.1.yaml)
- [Application-Status-Push-Notifications_OpenAPI_1.0.0-rc.1.yaml](Application-Status-Push-Notifications_OpenAPI_1.0.0-rc.1.yaml)
