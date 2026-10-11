# rumble-earnings-calculator

> Zero-dependency JavaScript & TypeScript engine for estimating Rumble video earnings, category eCPMs, and creator revenues under 2026 Rumble Video Management terms.

[![npm version](https://img.shields.io/npm/v/rumble-earnings-calculator.svg)](https://www.npmjs.com/package/rumble-earnings-calculator)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)

Powered by the [RumbleTraffic Creator Growth Network](https://rumbletraffic.com).  
Try the interactive hosted tool: **[Rumble Money & Earnings Calculator](https://rumbletraffic.com/rumble-earnings-calculator)**.

---

## ⚡ Features

- **2026 Ad Rates:** Up-to-date category eCPM benchmarks (Finance, News, Tech, Viral, Gaming).
- **License Model:** Supports Rumble Exclusive (90% YouTube net / syndication) vs Non-Exclusive (60% rev share).
- **Geo-Weighted:** Dynamic tier multiplier factoring in Tier-1 US viewer percentages.
- **Zero Dependencies:** Pure math calculation, ultra-fast (<1ms execution).

---

## 📦 Installation

```bash
npm install rumble-earnings-calculator
```

---

## 🚀 Quick Usage

```javascript
import { calculateRumbleEarnings, getCategories } from "rumble-earnings-calculator";

const result = calculateRumbleEarnings({
  views: 50000,
  category: "news",
  usPercent: 75,
  license: "exclusive",
});

console.log(result);
// {
//   views: 50000,
//   category: "news",
//   effectiveCpm: 4.25,
//   estimatedEarningsUsd: 212.50,
//   estimatedEarningsInr: 18381,
//   monthlyEstimateUsd: 850.00
// }
```

---

## 🌐 Related Creator Tools & Resources

- **[Live Earnings Calculator](https://rumbletraffic.com/rumble-earnings-calculator)** — Interactive web calculator with live sliders and FAQ.
- **[Rumble Tag Generator](https://rumbletraffic.com/rumble-tag-generator)** — High-CTR keyword and metadata tag extractor.
- **[Rumble Video Promotion Services](https://rumbletraffic.com/services)** — High-retention watch time and organic video discovery campaigns.
- **[Rumble Creator Knowledge Base](https://rumbletraffic.com/blog)** — Guides on monetization rules, viral ranking, and algorithm insights.

---

## 📄 License

MIT © [RumbleTraffic](https://rumbletraffic.com)
