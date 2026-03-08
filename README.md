# 🎫 IT Support Performance Analytics — Ticket to Resolution

**Analyzing IT support ticket patterns to help teams resolve faster, reduce recurring issues, and optimize workflows.**

> 🏆 Built as part of the **Onyx Data FP20 Analytics Challenge**

---

## 🔗 [View Live Interactive Dashboard](https://lnkd.in/gbn7Upgg)
*Add your Power BI publish link here*

---

## 🛠 Tech Stack

- 📊 Power BI Desktop
- 🧠 DAX (custom KPI measures)
- 📝 Data Modeling
- 🔍 ZoomCharts Drill Down Visuals

---

## 📂 Data Source

Dataset provided by **Onyx Data / FP20 Analytics Challenge**. Contains 1,000+ IT support tickets structured like a real Jira Service Management export: including ticket type, priority, queue, tags, resolution dates, and country-level location data.

---

## 💡 Dashboard Breakdown

### Business Problem
IT support teams often lack visibility into what's driving ticket volume, which issues take longest to resolve, and where workflows are breaking down which making it hard to improve service quality or plan resources effectively.

### Goal
Build a diagnostic analytics report that helps IT teams spot recurring issues, benchmark resolution performance, and identify process improvement opportunities across teams, ticket types, and regions.

---

### 🖥️ Walkthrough of Key Pages

---

**Page 1 — Ticket Overview & Workload**

![Ticket Overview](https://raw.githubusercontent.com/Mariarais24/it-support-analytics-powerbi/main/ticket-overview.png)

The operational entry point. Tracks total tickets (707), resolution rate, average resolution days (2.82), and high-priority ticket share (38%). Three ranking charts surface the top technical tags, primary issue categories, and busiest support teams with Technical Support handling 206 tickets alone. A monthly trend chart reveals volume consistency across 2024–2025, while a donut chart shows Incidents (38%) dominate ticket type distribution.

---

**Page 2 — Resolution Performance**

![Resolution Performance](https://raw.githubusercontent.com/Mariarais24/it-support-analytics-powerbi/main/resolution-performance.png)

Focused on how efficiently tickets are being closed. A key finding: **low priority tickets take longer to resolve (4 days) than high priority ones (2 days)**  suggesting triage and prioritization logic is working, but low-priority queues may be deprioritized too aggressively. 79% of tickets resolve within 3 days. A daily resolution trend chart shows consistent throughput with occasional spikes.

---

**Page 3 — Deep Dive & Process Insights**

![Deep Dive](https://raw.githubusercontent.com/Mariarais24/it-support-analytics-powerbi/main/deep-dive.png)

Country-level and queue-level diagnostic layer. Portugal, Latvia, Poland, and Sweden are the highest-volume countries. A detailed table breaks down every queue by technical tag, priority, ticket count, tickets resolved, unresolved difference, and average resolution days which making it easy to pinpoint exactly where backlogs or delays exist.

---

### Business Impact & Insights

- ⚡ **99.4% resolution rate** (703 of 707 tickets resolved) — strong overall throughput.
- 🐛 **Incidents make up 38% of all tickets** — the most common type, pointing to systemic issues worth investigating for root cause elimination.
- ⏱️ **Low priority tickets take 2x longer than high priority** — an opportunity to tighten SLA enforcement on lower-tier queues.
- 🌍 **Portugal leads ticket volume (80 tickets)** — regional patterns may point to product, language, or infrastructure issues.
- 🔐 **Security is the #2 primary tag (113 tickets)** — a recurring area that may benefit from self-service documentation or automation.

---

## ✅ Recommendations

| # | Action |
|---|---|
| 1 | Investigate recurring **Incident tickets** for root causes & reduce repeat volume through fixes or help articles. |
| 2 | Set SLA targets for **low-priority queues** 4-day average resolution is too slow for service quality. |
| 3 | Build knowledge base articles for top **Security and Tech Support tags** to deflect common tickets. |
| 4 | Review **Portugal and Latvia** regional tickets for localized patterns or infrastructure gaps. |

---

## 🏆 Challenge Context

This dashboard was submitted to the **Onyx Data FP20 Analytics Challenge**. The dataset and business brief were provided by Onyx Data. The analytical approach, dashboard design, and insights are original work.
