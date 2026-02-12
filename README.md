# 🍞 Reclame pe Pâine: High-Conversion Digital Marketing Platform

> **Responsive Lead Generation Engine & Brand Presentation Interface**
> *Deployed for Production | HTML5 • CSS3 • ES6 JavaScript*

[![Status](https://img.shields.io/badge/Status-Production-success)]()
[![Platform](https://img.shields.io/badge/Platform-Web-blue)]()
[![Compliance](https://img.shields.io/badge/Compliance-GDPR%20Ready-orange)]()
[![Performance](https://img.shields.io/badge/Performance-High-brightgreen)]()

## 📖 Overview

**Reclame pe Pâine** is a commercial web platform developed for a Bucharest-based digital marketing agency specializing in TikTok advertising. Unlike standard template-based websites, this project features a hand-coded, **mobile-first architecture** designed to maximize user engagement and lead conversion rates.

The platform integrates **real-time form validation**, asynchronous data transmission for lead capture, and a fully compliant legal framework (GDPR/Cookies), bridging the gap between creative marketing and technical reliability.

### 🔗 Live Demo: [Click here](https://xorture.github.io/reclame-pe-paine-website/)

---

## 🚀 Key Technical Features

### 1. Performance-Driven UX (Intersection Observer API)
To ensure 60fps scrolling performance even on low-end mobile devices, the site utilizes the modern **Intersection Observer API** instead of expensive scroll-event listeners.
- **Lazy Loading Logic:** Elements (pricing boxes, testimonials) are rendered with CSS transforms only when they enter the viewport.
- **Resource Optimization:** Reduces the initial Time to Interactive (TTI) by deferring non-critical visual computations.

### 2. Client-Side Input Sanitization & Validation
The lead generation engine features a robust JavaScript validation layer before any data is sent to the server:
- **Regex Pattern Matching:** Enforces strict validation for Romanian phone numbers (`^0[2-7][0-9]{8}$`) and name formats, preventing SQL injection or malformed data entry.
- **Dynamic Feedback:** Provides real-time visual cues (Green/Red borders) to guide the user, significantly reducing form abandonment rates.

### 3. Asynchronous Lead Dispatch (Fetch API)
The platform bypasses traditional synchronous form submissions (which reload the page) in favor of a modern **AJAX/Fetch** workflow.
- **Endpoint:** Integrates securely with `formsubmit.co` for backend processing.
- **User Experience:** Maintains the user's state on the page while processing the submission in the background, delivering instant success/error feedback via the DOM.

### 4. Regulatory Compliance Module (GDPR)
Built with strict adherence to EU directives:
- **Dedicated Legal Routing:** Separate, fully routed pages for *Terms & Conditions*, *Cookie Policy*, and *GDPR*.
- **ANPC Integration:** Mandatory direct links to consumer protection authorities (SOL/SAL) are hardcoded into the footer architecture.

---

## ⚙️ Business Logic & Conversion Strategy

The codebase reflects a specific sales funnel strategy:

1.  **Hero Section:** Immediate value proposition ("Bread/Sales" metaphor) to capture attention (< 3 seconds).
2.  **Social Proof:** Integrated HTML5 Video Players showcasing portfolio examples directly.
3.  **Trust Building:** Animated statistics section using CSS transitions to visualize ROI.
4.  **Conversion:** A sticky "Call to Action" (CTA) mechanism that programmatically scrolls the user to the lead capture form.

---
