<div align="center">

# E-Commerce Conversion Audit

### Homepage · Product Page · Checkout · Trust · Mobile UX · WhatsApp Follow-Up

A practical audit framework for identifying conversion leaks in Sri Lankan e-commerce websites and turning more existing traffic into completed orders.

![Audit](https://img.shields.io/badge/Framework-Conversion%20Audit-0D1B2A?style=for-the-badge)
![Audience](https://img.shields.io/badge/Audience-Sri%20Lankan%20E--Commerce-CDAA67?style=for-the-badge)
![Mobile](https://img.shields.io/badge/Focus-Mobile%20First-3C9CD7?style=for-the-badge)
![Status](https://img.shields.io/badge/Template-Public%20Safe-2E8B57?style=for-the-badge)

</div>

> **Purpose:** This repository is a public, reusable audit framework. It does not contain private client data, confidential analytics, payment credentials, or guaranteed revenue claims.

---

## What This Audit Solves

Many e-commerce businesses try to fix low sales by buying more traffic.

But more traffic does not automatically solve:

- unclear product information
- weak trust signals
- confusing delivery details
- difficult mobile navigation
- hidden or weak calls to action
- slow or complicated checkout
- payment uncertainty
- poor WhatsApp follow-up
- failed-payment recovery gaps

This framework helps identify those leaks before more money is spent on ads.

---

## Core Principle

> Conversion optimisation is the process of removing unnecessary doubt, effort, and risk from the customer journey.

The audit follows the path:

```text
Traffic
  ↓
Homepage / Landing Page
  ↓
Category / Search
  ↓
Product Page
  ↓
Cart
  ↓
Checkout
  ↓
Payment
  ↓
Order Confirmation
  ↓
Follow-Up / Recovery
```

---

## Audit Categories

| Category | Weight |
|---|---:|
| Homepage & First Impression | 10 |
| Navigation & Product Discovery | 10 |
| Product Page Clarity | 20 |
| Trust & Risk Reduction | 15 |
| Cart & Checkout | 20 |
| Mobile Experience | 10 |
| Performance & Technical Friction | 5 |
| WhatsApp & Lead Follow-Up | 5 |
| Payment Failure Recovery | 5 |
| **Total** | **100** |

---

## Score Interpretation

| Score | Meaning |
|---|---|
| 85–100 | Strong foundation; optimise specific weak points |
| 70–84 | Good, but meaningful leaks still exist |
| 50–69 | Several conversion blockers need attention |
| Below 50 | High-friction journey; prioritised fixes required |

The score is a diagnostic tool, not a promise of sales growth.

---

## Quick Audit Checklist

### Homepage

- Is the business offer clear within five seconds?
- Is the primary action obvious?
- Are delivery, payment, and trust signals visible?
- Does the page guide visitors toward products?
- Is the mobile hero area useful rather than decorative?

### Navigation

- Can users find categories quickly?
- Is search visible and usable?
- Are filters clear?
- Are product names and categories understandable?
- Can users recover after reaching an empty result?

### Product Page

- Are the images clear, consistent, and sufficient?
- Is pricing visible?
- Are product benefits easy to scan?
- Are specifications and dimensions available?
- Are stock, delivery, and customisation rules clear?
- Is Add to Cart obvious and mobile-friendly?
- Are objections answered before checkout?

### Trust

- Are contact details visible?
- Are delivery expectations explained?
- Are payment methods clear?
- Are returns, exchanges, and warranty terms accessible?
- Are reviews or other credible proof available?
- Does the site look maintained and secure?

### Cart & Checkout

- Is the cart easy to edit?
- Are extra charges shown early?
- Are form fields limited to what is necessary?
- Are validation messages specific?
- Is guest checkout available where appropriate?
- Are payment options understandable?
- Is the confirmation step clear?

### WhatsApp & Recovery

- Is WhatsApp used as a helpful support channel rather than a replacement for basic site information?
- Are inquiries tracked?
- Is there a follow-up status?
- Are failed or pending payments prioritised?
- Is the message personalised and context-aware?
- Is recovery measured without treating every click as a confirmed conversation?

---

## Prioritisation Model

Every issue is classified by:

1. **Impact** — How much could this affect buying decisions?
2. **Effort** — How difficult is the fix?
3. **Confidence** — How strong is the evidence?
4. **Urgency** — Is the issue blocking transactions now?

### Priority formula

```text
Priority Score = (Impact × Confidence × Urgency) ÷ Effort
```

Use a 1–5 scale for each factor.

---

## Example Finding

### Finding

The Add to Cart button appears below a long content block on mobile and is not visually distinct.

### Why it matters

Users may understand the product but fail to see the next action.

### Evidence

- button not visible in the first mobile viewport
- low visual contrast
- competing secondary links
- no sticky purchase action

### Recommendation

- increase contrast and tap area
- move the action closer to price and stock
- consider a mobile sticky action
- reduce competing actions near the main CTA

### Priority

High impact · Low-to-medium effort · High confidence

---

## Repository Guide

| Document | Purpose |
|---|---|
| [Audit Method](docs/01-audit-method.md) | How to run the audit |
| [Homepage & Navigation](docs/02-homepage-and-navigation.md) | First impression and product discovery |
| [Product Page](docs/03-product-page.md) | Product-information and CTA checks |
| [Trust & Checkout](docs/04-trust-and-checkout.md) | Risk reduction and purchase flow |
| [Mobile & Performance](docs/05-mobile-and-performance.md) | Mobile UX and technical friction |
| [WhatsApp & Recovery](docs/06-whatsapp-and-recovery.md) | Lead handling and failed-payment recovery |
| [Scoring & Prioritisation](docs/07-scoring-and-prioritisation.md) | Score and action order |
| [Evidence & Testing](docs/08-evidence-and-testing.md) | How to support findings honestly |
| [Sri Lankan Context](docs/09-sri-lankan-context.md) | Local delivery, payment, and trust considerations |
| [Audit Report Template](templates/audit-report-template.md) | Client-ready report structure |
| [Finding Template](templates/finding-template.md) | Standard issue format |
| [Action Plan Template](templates/90-day-action-plan.md) | Prioritised implementation plan |

---

## What This Framework Does Not Claim

- It does not guarantee a conversion-rate increase.
- It does not invent customer research.
- It does not treat clicks as completed conversations.
- It does not replace analytics, usability testing, or customer interviews.
- It does not recommend dark patterns.
- It does not require publishing client analytics publicly.

---

## Author

**Ishara Subasinghe**  
E-Commerce Growth Specialist · Laravel Developer · AI Automation

**Positioning:** Helping Sri Lankan e-commerce businesses turn website traffic and WhatsApp inquiries into more completed orders.

[GitHub Profile](https://github.com/ish30)
