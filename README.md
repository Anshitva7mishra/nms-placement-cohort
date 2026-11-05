# NMS: No More Struggle

**Placement Cohort for CS/IT, BCA/MCA and Mechanical students**

> Hum wahi hain jo kal tak aapki jagah the.

![Status](https://img.shields.io/badge/status-pre--launch-blue)
![Stage](https://img.shields.io/badge/stage-planning-lightgrey)
![Docs](https://img.shields.io/badge/docs-living-green)
![License](https://img.shields.io/badge/license-proprietary-red)

---

## About

NMS is an instructor-led placement cohort powered by a 24/7 AI Assistant and supported by recently placed graduates. The program operates two streams: a **Combined Tech Track (CS/IT, BCA/MCA)** and an **Independent Mechanical Track**. With live teacher masterclasses, 24/7 AI-driven code feedback and doubt resolution, weekly mock interviews, and personal reviews, NMS scales without losing individualized student support.

This repository is the single source of truth for the business model, curriculum, operations and launch plan. It is maintained by the NMS core team.

> Scope note: This repository covers the cohort business model, operations, and AI-assisted delivery architecture. Product application code is tracked separately.

---

## At a Glance

| Item | Detail |
|---|---|
| Tracks | 1. Combined Tech Track (CS/IT + BCA/MCA)<br/>2. Mechanical Track (Separate) |
| Cohort 1 Size | 250 to 300 students |
| Target Audience | Primarily 2nd and 3rd year students (plus 4th and 1st years) |
| Delivery Model | Lead Teacher live masterclasses + 24/7 AI Assistant + Mock Evaluators |
| Cohort length | 12 weeks |
| Practice | 24/7 AI doubt resolution, weekly coding tests, weekly mocks with written feedback |
| Certification | NMS Certificate of Completion with unique Verification ID (Udyam MSME registered).<br/>Post-founding batch: College MoUs & AICTE/NSDC exploration |
| Promise | Honest roadmap. No placement guarantee. |

---

## Repository Map

```text
nms-placement-cohort/
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── CHANGELOG.md
├── LICENSE
├── .gitignore
├── .github/
│   ├── CODEOWNERS
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── ISSUE_TEMPLATE/
│       ├── task.md
│       ├── decision-request.md
│       └── content-update.md
├── docs/
│   ├── 00-overview.md
│   ├── business/
│   │   ├── business-model.md
│   │   ├── market-and-audience.md
│   │   ├── pricing.md
│   │   ├── certification.md
│   │   ├── go-to-market.md
│   │   ├── roadmap.md
│   │   ├── metrics.md
│   │   └── risks-and-compliance.md
│   ├── tracks/
│   │   ├── cs-it.md
│   │   ├── bca-mca.md
│   │   ├── mechanical.md
│   │   └── common-modules.md
│   ├── operations/
│   │   ├── student-journey.md
│   │   ├── weekly-cycle.md
│   │   ├── mentor-structure.md
│   │   └── cohort-timeline.md
│   └── decisions/
│       ├── README.md
│       ├── ADR-TEMPLATE.md
│       └── 0001-no-placement-guarantee.md
├── team/
│   └── roles.md
└── assets/
    └── README.md
```

---

## Where to Start

| If you want to... | Read |
|---|---|
| Understand the idea quickly | [docs/00-overview.md](docs/00-overview.md) |
| Answer "Why Us?" | [docs/business/business-model.md](docs/business/business-model.md) |
| Review a track curriculum | [docs/tracks/](docs/tracks/) |
| See weekly operations | [docs/operations/weekly-cycle.md](docs/operations/weekly-cycle.md) |
| Check pricing approach | [docs/business/pricing.md](docs/business/pricing.md) |
| Track the launch plan | [docs/business/roadmap.md](docs/business/roadmap.md) |
| Know who owns what | [team/roles.md](team/roles.md) |
| Contribute | [CONTRIBUTING.md](CONTRIBUTING.md) |

---

## Diagrams

All diagrams use [Mermaid](https://mermaid.js.org/) and render natively on GitHub, GitLab, Notion and VS Code (with the Markdown Preview Mermaid extension). If your viewer does not render them, paste the code into [mermaid.live](https://mermaid.live).

---

## Open Decisions

Tracked in [docs/decisions/](docs/decisions/) and as GitHub issues labelled `decision`.

1. Final name, logo and brand visuals (In progress — see [assets/README.md](assets/README.md))
2. Pricing price-points, after student survey (In progress — see [docs/business/pricing.md](docs/business/pricing.md))
3. Platform and community channel (Discord / Slack / LMS)
4. AI Assistant tech stack and bot integration architecture
5. Udyam MSME registration and payment gateway integration (In progress — ADR 0003)

*Note: Program scale (250–300 students), track streams (Combined Tech + Mechanical), delivery architecture (Teacher + AI Assistant), target audience (2nd/3rd years primary), and certification roadmap are finalized in [ADR 0002](docs/decisions/0002-cohort-scale-tech-merger-ai-assistant.md) and [ADR 0003](docs/decisions/0003-certification-and-institutional-recognition.md).*

---

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. All changes go through a branch and a review.

## License

Proprietary. See [LICENSE](LICENSE). Internal use by the NMS team only.
