# Path Robotics

Path Robotics is a **Columbus, Ohio** autonomous welding robotics company
founded in 2018 by brothers **Andy Lonsberry** (CEO) and **Alex Lonsberry**
(CTO) out of Case Western Reserve University. Path builds AI-powered
**intelligent welding cells** that automate metal fabrication for defense
shipyards, utility and energy infrastructure, data centers, and heavy
industry.

> "AI-powered welding that adapts in real time — seam by seam, just like a
> human would."
> — path-robotics.com/obsidian

## Products & Technology

| Product / Tech | What it is |
| --- | --- |
| **Obsidian** | Physical-AI reinforcement-learning agent trained inside Path's proprietary Weld World Model on tens of millions of welded inches. Runs at the edge of each cell. |
| **Weld World Model** | Proprietary simulator/world model that captures pre-, during-, and post-weld data; feeds back into Obsidian training. |
| **Intelligent Welding Cells** | Fully autonomous welding cells sold on a consumption / CapEx-free model. Claimed 4x productivity, 30% lower cost, 97%+ first-pass yield. |
| **Rove** *(April 2026)* | Mobile welding system mounted on a quadruped platform; extends Path beyond fixed-cell applications. |
| **Sensor Stack** | 2 cameras + 4 lasers delivering 360-degree sub-millimeter awareness around the torch; neural-network filtering removes false reflections in real time. |

## Markets

- Defense (shipyards, military manufacturing)
- Utility & energy infrastructure
- Data centers
- Heavy industry / large fabrications

Notable customers and announced deployments include **HII** (America's
largest military shipbuilder), **Saronic**, **LAD Services**, **Tycrop**,
**Mine Rite Technologies**, and **Millerbernd**.

## Leadership

- **Andy Lonsberry** — CEO, Co-Founder
- **Alex Lonsberry** — CTO, Co-Founder
- **Frank Klein** — Board member (Rocket Lab COO)
- **Geoffrey Chatas** — Board member (Yale University CFO)
- **Heather Carroll** — Chief Revenue Officer
- **Joe Onderko** — Chief Evangelist
- **Mike Renn** — EVP, Global Operations
- **Andrew Lein** — VP of Product
- **Matthew Randle** — CISO & VP of Product Reliability Engineering

## Funding

| Round | Date | Amount | Notes |
| --- | --- | --- | --- |
| Series C | 2021 | $100M | Reported by Robotics 24/7 |
| Series D | Oct 2024 | $100M | Led by Matter Venture Partners and Drive Capital |
| **Total raised** | | **≈$271M** | Investors include Drive Capital, Matter Venture Partners, Tiger Global, Addition, Yamaha Motor Ventures |

Headcount as of Q1 2026: ~198 employees.

## Developer / API Surface

| Surface | Status |
| --- | --- |
| Public REST/GraphQL API | None |
| Developer portal | None |
| OpenAPI / AsyncAPI / Postman | None |
| Public SDKs / CLIs | None |
| Webhooks / Events | None |
| Public GitHub organization | [github.com/path-robotics](https://github.com/path-robotics) — 50 public repos, **almost entirely upstream open-source forks** (ROS, protobuf, abseil, ceres-solver, pytorch3d, gRPC, OpenTelemetry C++, tensorflow, fmt, mimalloc, etc.) used as internal build dependencies. No published developer artifacts, no documented external API surface. |
| RSS / Changelog | None public |
| Status page | None public |

Path Robotics' commercial surface is **physical welding cells sold on a
consumption / per-weld basis**, not a developer API. Obsidian is a
closed, proprietary on-device model; the Weld World Model is internal
training infrastructure. This repo is profiled **for portfolio and
landscape completeness** — to anchor the autonomous-welding and
physical-AI segment of the API Evangelist network alongside Figure
Robotics, Agility Robotics, Boston Dynamics, and other embodied-AI
players where Naftiko's governed-AI thesis intersects with industrial
deployment.

## Key Links

- Website: <https://www.path-robotics.com>
- About: <https://www.path-robotics.com/about>
- Obsidian: <https://www.path-robotics.com/obsidian>
- Demo / Contact: <https://www.path-robotics.com/demo>
- News: <https://www.path-robotics.com/news>
- Careers: <https://www.path-robotics.com/careers>
- GitHub: <https://github.com/path-robotics>
- LinkedIn: <https://www.linkedin.com/company/path-robotics>
- Crunchbase: <https://www.crunchbase.com/organization/path-robotics>

## Pipeline Run

- **x-type**: company
- **x-tier**: 3 (no-apis)
- **Profiled**: 2026-05
- **Artifacts**: `apis.yml`, `README.md` only — no OpenAPI / AsyncAPI /
  JSON Schema / capabilities generated because no public API surface
  exists to model. The GitHub org was reviewed; no first-party Path
  Robotics SDK, CLI, or spec was identified — only upstream OSS forks.

---
Maintained by [Kin Lane](https://apievangelist.com), API Evangelist.
