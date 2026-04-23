
##  Project Overview

We’re building an **AI-powered grocery copilot** that transforms any recipe or dish into a ready-to-order Instamart cart using Swiggy MCP APIs.

Users can simply input:

> “Make Paneer Butter Masala for 2 people”

The system:

* Extracts ingredients using an LLM
* Maps them to real Instamart products
* Optimizes selection (price, availability, substitutes)
* Builds a ready-to-checkout cart

---

##  What Makes It Unique

Unlike traditional grocery apps, this is **agent-driven, not UI-driven**:

* Converts **intent → structured data → real actions**
* Uses AI to **reason, not just respond**
* Handles ambiguity (e.g., ingredient substitutions, quantity scaling)

This turns grocery ordering into a **one-command experience**.

---

##  Key Capabilities

*  Recipe → Ingredient extraction (via Anthropic Claude)
*  Autonomous cart creation via MCP (Instamart APIs)
*  Smart product matching & substitutions
* Cost-aware optimization
*  Real-time availability handling

---

##  MCP Integration

We use Swiggy MCP as a **tool layer for the AI agent**, enabling:

* Product search from Instamart catalog
* Cart creation and updates
* Action execution (add/remove items)

The AI agent orchestrates these APIs to complete tasks end-to-end.

---

##  Vision

To evolve this into a **daily life commerce copilot** that can:

* Auto-restock groceries
* Plan meals weekly
* Optimize spending
* Integrate across Food, Instamart, and Dineout

---

##  Current Status

* Working prototype with:

  * Recipe input → ingredient extraction
  * Simulated cart generation
* Integrating live MCP APIs next

---

##  Why This Matters

This project demonstrates how **AI agents can move beyond chat** and take **real-world actions on top of commerce platforms** — making everyday tasks faster, smarter, and frictionless.

---
* A *landing page copy*
* Or a *GitHub README that gets attention*
