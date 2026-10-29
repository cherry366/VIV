# VIV Health Platform｜Device Control · Real-Time BLE Connectivity · Closed-Loop Health Data

> The official companion app for VIV smart massage hardware — from a "hardware remote" to a "health butler"

`Platform: iOS / Android`　`Connectivity: BLE / OTA`　`Focus: Device Control + Health Data`　`Role: Product Manager (Owner)`

[简体中文](README.md) | **English**

---

## 1. Overview

VIV Health Platform is the official companion app for VIV smart massage devices. Built around a **dual-core strategy — device control and health data** — it connects the full journey from *pairing → massage control → technique marketplace → health reports*, addressing a common problem in smart hardware: devices sell well, yet their value is never fully unlocked.

Rather than stacking platform features, V1.0 deliberately stays a focused utility product and does three things exceptionally well: **connect reliably, control precisely, and make data visible**. The technique marketplace and OTA updates continuously supply new content, extending the lifecycle of the hardware.

---

## 2. Core Capabilities

| Capability | Description |
|---|---|
| **Device Remote Control** | Full BLE control over modes, intensity (1–9 levels), heat levels and duration; end-to-end command latency ≤300 ms; auto-stop protection on disconnection |
| **Fast Pairing** | Long-press power to enter pairing mode → scan → authenticated binding, completing in ~15 s with a pairing success rate ≥98% |
| **Content Supply** | Browse and download techniques in the marketplace, sync them to the device over BLE, and launch with one tap from "My Techniques" |
| **Health Butler** | Automatic usage logging, daily/weekly/monthly trend charts, and weekly relaxation reports that make consistency visible |
| **Cross-Device Consistency** | Local-first caching with no data loss offline; timestamp-based deduplication and re-upload once connectivity returns |

---

## 3. Product Metrics

| Stage | Metric | Target |
|---|---|---|
| Activation | Device pairing success rate | ≥ 98% |
| Activation | New-user completion rate (first ≥5-min massage within 24h) | ≥ 70% |
| Usage | Weekly sessions per device | ≥ 4 |
| Usage | Share of sessions controlled via app | ≥ 60% |
| Retention | 30-day retention of bound users | ≥ 45% |
| Content | Technique download penetration | ≥ 30% |
| Quality | Crash rate / ANR rate | ≤ 0.1% / ≤ 0.05% |

> **North Star Metric**: weekly effective massage sessions per device (a session ≥5 minutes counts as effective) — measuring whether the hardware is genuinely being used.

---

## 4. Live Preview

- **GitHub Pages**: https://cherry366.github.io/VIV/
- **Gitee Pages**: https://cherry366.gitee.io/VIV/
- **Local**: open `index.html` in any browser — no dependencies, no server required

---

## 5. Repository Structure

```
VIV/
├── index.html                              # Product portfolio showcase page (single-file, no external dependencies)
├── VIV健康平台App_PRD_v1.0.docx            # Product Requirements Document (PRD)
├── README.md                               # Project overview (Chinese)
└── README_EN.md                            # Project overview (English)
```

---

## 6. Showcase Structure

1. **Background** — three pain points and the opportunity
2. **User Research** — four core personas and key insights
3. **Positioning & Goals** — product positioning, North Star metric, target dashboard
4. **Feature Plan** — 4-tab information architecture, 8 modules prioritized P0/P1/P2, acceptance criteria
5. **Core Flows** — five-step pairing flow, massage and content-consumption loops
6. **Metrics** — pairing funnel and AARRR dashboard
7. **Retrospective** — three things done right and three lessons learned

---

## 7. Notes

- This repository serves as a **product manager portfolio**; all figures are product target values, not live operational data.
- The showcase is a pure static single-file HTML page with inline styles and interactions, responsive for desktop and mobile.
- The PRD is version V1.0, covering the core device-control and health-data modules.

---

<p align="center"><sub>VIV Health Platform · Product Requirements & Showcase</sub></p>
