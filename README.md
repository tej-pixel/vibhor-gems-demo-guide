# Vibhor Gems — Demo Guide

Internal Salesforce AE playbook for walking a prospect through the Vibhor Gems B2B wholesale jewelry Sales Cloud POC.

**Live:** https://tej-pixel.github.io/vibhor-gems-demo-guide/

## What's in here

- `index.html` — 9-step demo guide with screenshots, click paths, talking points, an interactive order-anatomy walkthrough, an automation reference, and an objection-handling appendix
- `screenshots/` — full captures from the live trial org against seeded demo data

## Build context

- B2B wholesale jewelry: Account = retail store, Opportunity = wholesale order
- Order lifecycle (Sales Path): **Quoted → In Manufacturing → QC → Shipped → Delivered**
- 8 custom Opportunity fields · 6 custom Account fields · 7 flows · custom Sales Path · `Log Shipment Note` + `Mark Paid` quick actions
- 8 list views · 8 reports + the Vibhor Gems POC Dashboard
- Seeded demo data: 8 retail-store accounts, 9 contacts, 16 orders across every stage, logged activities

## Reproducing the screenshots

Captured via browser automation against the live trial org (`data-computing-2855`), full-page record/list captures saved to `screenshots/`.

Built by SaaScend.
