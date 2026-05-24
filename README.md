
# Git-PROSPERO: Immutable Protocol Registration

A decentralized, Git-backed framework for registering systematic review protocols.

## The Bottleneck
Registering a systematic review protocol on PROSPERO currently takes 6-12 months due to editorial backlogs. This delays research and defeats the purpose of rapid, living evidence synthesis.

## The Solution
Per ICMJE 2023 guidelines, an immutable timestamp on a publicly accessible server constitutes a verifiable pre-registration record. 

This repository provides a standard template and a GitHub Actions workflow that:
1. Validates your PROTOCOL.md against PRISMA-P reporting standards.
2. Cryptographically locks the protocol file.
3. Uses the GitHub SHA-256 commit hash as the authoritative, immutable registration ID.

Any subsequent amendments to the protocol are inherently tracked via Git blame, providing perfect transparency into outcome switching or eligibility changes.

