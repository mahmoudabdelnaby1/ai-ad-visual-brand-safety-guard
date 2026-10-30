# 25 Point Ai Visual Qa

## Executive Summary: AI-Generated Advertising Visuals Brand Safety & Distortion Guard
This document serves as the operational inspection standard for **AI-Generated Advertising Visuals Brand Safety & Distortion Guard** within the **content** domain, designed for **Regional Marketing & Growth Teams**.

### Context & Regional Scope
Create an enterprise quality control framework for AI-generated marketing imagery: 1) 25-point visual artifact checklist (Anatomy, Text & Logos, Lighting Consistency, Cultural Appropriateness for MENA), 2) Curated negative prompt library for Midjourney and Flux, 3) Real-world defect gallery with failure analysis, 4) Sign-off workflow template for agency art directors.

---

## Pre-Flight Verification Checklist

### Phase 1: Ingestion & Input Integrity
- [ ] **Data Hygiene & Schema Validation:** Confirm all inbound identifiers, payloads, or asset files conform to expected schemas without missing mandatory fields.
- [ ] **Regional Parameter Enforcement:** Verify country codes (KSA +966, UAE +971, Egypt +20), currency symbols (SAR, AED, EGP), and timezone alignment (Arabia Standard Time UTC+3 / Cairo UTC+2).
- [ ] **Character & Encoding Standards:** Check UTF-8 / Arabic script rendering, BiDi punctuation alignment, and segment length constraints.

### Phase 2: Regulatory & Policy Governance
- [ ] **Commercial Transparency Disclosures:** Verify inclusion of mandatory legal entity numbers (CR, VAT registration #, or Mawthooq/licensing permits where applicable).
- [ ] **Price & Tax Presentation:** Ensure all displayed prices explicitly state VAT inclusion (15% in KSA, 5% in UAE, 14% in Egypt) without hidden mandatory surcharges.
- [ ] **Substantiation of Empirical Claims:** Eliminate unverified superlatives ("#1", "الأفضل") or guarantee claims unless supported by auditable third-party documentation.

### Phase 3: Technical Execution & Telemetry QA
- [ ] **Event Telemetry Firing:** Test client-side and server-side tracking tags in staging environment; ensure 0 duplicate purchase/lead triggers.
- [ ] **Graceful Degradation & Fallbacks:** Confirm fallback behavior when network latency exceeds 2.5s or external webhooks return non-200 HTTP responses.
- [ ] **Mobile & Responsive Ergonomics:** Inspect viewport rendering across 390px (iPhone standard) and 412px (Android standard); confirm touch targets >= 48px.

### Phase 4: Sign-off & Deployment Gate
- [ ] **Owner Sign-off:** Lead growth engineer or compliance lead verification.
- [ ] **Telemetry Baseline Logged:** Initial snapshot recorded for post-launch discrepancy monitoring.

---
*Operational standard maintained by @mahmoudabdelnaby1.*
