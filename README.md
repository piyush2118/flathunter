# Property Scanner MVP 🏠

A zero-recurring-cost Minimum Viable Product (MVP) designed to aggregate property listings from major Indian real estate platforms without relying on expensive APIs or automated WhatsApp business accounts. This workflow prioritizes manual review and direct outreach to keep operational costs at ₹0.

## Overview
Instead of paying for complex automation infrastructure, this setup leverages free-tier browsing, email alerts, and manual WhatsApp messaging to find and contact property owners.

### Financial Strategy
* **Target Recurring Cost:** ₹0
* **Optional Budget:** ₹1,200 – ₹1,600 one-time expenditure for unlocking additional owner contacts if free limits are exhausted.

---

## Supported Platforms & Sourcing Strategy

The project utilizes data from three primary platforms based on pricing structures as of October 2026:

| Platform | Cost Structure | Implementation Strategy |
| :--- | :--- | :--- |
| **NoBroker** | Free browsing; historically offers 9 free owner contacts. Paid packages start around ₹999. | Integrate with existing Gmail alerts; selectively unlock owner contacts. |
| **Ghosla** | Free application and public listings. No API costs. | Utilize direct tenant-posted listings and leverage its cross-platform scanning capabilities. |
| **MagicBricks** | 2 free contacts. Paid packages: ₹1,199 (10 contacts) or ₹1,599 (30 contacts) valid for 3 months. | Use free contacts first; fallback to paid contact packages if inventory is low. |

---

## Workflow

1. **Scan & Aggregate:** Monitor incoming Gmail alerts from NoBroker and browse free public listings on Ghosla and MagicBricks.
2. **Review:** Manually screen the aggregated flats to filter out irrelevant listings.
3. **Outreach:** Use standard WhatsApp (personal/business app) to manually send pre-drafted messages to verified owners, bypassing the need for a paid WhatsApp API.
