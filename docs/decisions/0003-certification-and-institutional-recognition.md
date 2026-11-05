# ADR 0003: Certification and Institutional Recognition Roadmap

- Status: Accepted
- Date: 2026-11-05
- Deciders: NMS core team

## Context

Students and campus placement candidates require verified credentials that carry credibility with recruiters, colleges, and parents. NMS needed to determine:
1. What certification credential to issue for the founding cohort (Cohort 1) immediately.
2. What legal business standing will support certificate authenticity.
3. How to scale institutional credibility post-Cohort 1 without taking on premature regulatory complexity.

## Options Considered

| Option | Pros | Cons |
|---|---|---|
| Issue unverified generic PDF certificates | Zero operational overhead | Low recruiter trust, easy to forge, zero brand equity |
| Pursue immediate AICTE/NSDC accreditation before Cohort 1 | Highest institutional prestige | Requires established company track record, lengthy approval cycles, impractical before launch |
| **Two-stage roadmap: Udyam-backed verifiable certificate now, college MoUs and AICTE/NSDC later** | Agile launch, immediate authenticity via unique ID, clear institutional growth path | Requires building lookup infrastructure and post-batch partnership outreach |

## Decision

NMS will follow a **two-phase certification roadmap**:

1. **Phase 1 (Immediate / Cohort 1):**
   - Issue the **NMS Certificate of Completion** featuring a unique **Verification ID** and online validation link.
   - Ground the entity legally through **Udyam (MSME) Registration**, citing the registration number on official documentation.
   - Award certificates only upon satisfying strict completion criteria (attendance, weekly tests, project review, and mock interview completion).

2. **Phase 2 (Post-Founding Batch Scale):**
   - Partner with **1 to 2 engineering/technical colleges** via formal Memorandums of Understanding (MoUs) for co-branded placement training.
   - Use verified performance improvements and placement data from Cohort 1 to explore formal **AICTE (NEAT)** or **NSDC** skilling alignment.

## Consequences

1. Certificate generation workflow must generate a unique credential ID and verification URL for each student.
2. Compliance checklist updated to include MSME Udyam registration prior to launch.
3. College outreach strategy drafted for Phase 4 roadmap.
4. Added dedicated reference doc: [docs/business/certification.md](../business/certification.md).

## Related Documents

- [Certification and Accreditation Strategy](../business/certification.md)
- [Risks and Compliance](../business/risks-and-compliance.md)
- [Launch Roadmap](../business/roadmap.md)
- [Student Journey](../operations/student-journey.md)

