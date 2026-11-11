---
layout: post
title:  "specification writing"
date:   2000-03-01 00:45:00 +0000
categories: jekyll update
---

- 1. Problem & Success (Why): Building a customer energy quote currently takes 10 hours because analysts manually clean and upload dozens of raw meter files. Success means simplifying inputs to just a postcode and meter ID, cutting modelling time to under 30 minutes with 95% accuracy.
- 2. User Flows (The Journey): A FigJam flow comparing the old 12-step manual spreadsheet upload against a new 2-step automated lookup flow.
- 3. Requirements (What to Build): Jira tickets paired with Figma screens—like auto-fetching historical half-hourly usage via API instead of requiring manual CSV uploads.
- 4. Design Specs (Final Screens): "Ready for Dev" Figma screens showing the simplified 2-field input form, smart default assumptions, and an instant model-ready preview.
- 5. Scope & Decisions (Guardrails): Custom multi-site industrial overrides are excluded from the fast-track flow for v1, and analysts can still unlock advanced inputs if a default estimate looks off.