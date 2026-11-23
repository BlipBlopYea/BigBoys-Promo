# BIGBOYS Rental Promotional Website

A lightweight, static promotional website and narrative landing page for **BIGBOYS Rental**, a localized heavy equipment marketplace serving contractors, builders, and fleet owners across the Davao Region and Mindanao[cite: 3].

---

## The Problem & Market Context

The Philippine construction industry recorded over **181,000 approved construction projects valued at ₱601+ billion in 2025**, backed by **2,500+ formal establishments**[cite: 4]. Despite this scale, equipment rental across local hubs (Davao City, Tagum, Digos, Bansalan) remains inefficient[cite: 3, 4]:

* **Opaque Pricing & Mobilization:** Rental ads rely on informal Facebook posts ("PM for rate/availability"), hiding distance-based mobilization fees until extensive messaging occurs[cite: 3].
* **High Capital Barrier:** Purchasing excavators, backhoes, or dump trucks is cost-prohibitive for small-to-medium builders who only need units for short-term jobs[cite: 1, 2].
* **Underutilized Fleets:** Equipment yards lose revenue when heavy machinery sits idle between bookings without a centralized booking channel[cite: 2, 5].

---

## What We Do

BIGBOYS Rental centralizes equipment access through three core platform features[cite: 5]:

1. **Instant Equipment Discovery:** Filter and locate excavators, backhoes, and dump trucks nearby within seconds (`LocationBasedListingSearch.png`)[cite: 1, 5].
2. **Automated Rate Calculator:** Clear calculation of hourly/daily rates, baseline mobilization fees, and distance-based mileage before booking (`RateCalculator.png`)[cite: 1, 5].
3. **Direct Fleet & Yard Management:** Dedicated inventory management dashboard for equipment owners to list idle units and manage availability schedules (`Availability.png`)[cite: 1, 5].

---

## Founding Team

* **Lorenz Yap**
* **Zahid Miranda**
* **Jan Eduard Olan**

---

## Landing Page Structure

The single-page promotional layout (`index.html`) follows a structured narrative flow:

1. **Hero:** High-impact value proposition and equipment categories.
2. **About & Mission:** Bridging regional construction logistics.
3. **Meet the Team:** Core builders and founders.
4. **The Problem:** Grounded operational friction paired with real local inquiry/FB citation context[cite: 3].
5. **Our Prototype:** Interactive UI walkthrough showcasing the search filter, rate calculator, and availability calendar[cite: 5].
6. **Promotional Video:** High-definition video showcase (`BIGBOYSPromovid.mp4`)[cite: 1].
7. **Contact & Inquiries:** Direct intake form for contractor and fleet owner onboarding.

---

## Project Structure

```text
BIGBOYSPromo/
├── assets/
│   ├── Availability.png                # Prototype UI: Yard fleet availability & booking calendar
│   ├── backhoe.png                     # Equipment category preview: Backhoes & loaders
│   ├── BigBoys.jpg                     # Brand / identity asset
│   ├── BIGBOYSPromovid.mp4             # High-definition promotional video
│   ├── dumptruck.png                   # Equipment category preview: Dump & haul trucks
│   ├── excavator.png                   # Equipment category preview: Excavators
│   ├── heroimage.jpg                   # Main landing page banner
│   ├── LocationBasedListingSearch.png  # Prototype UI: Distance & location-based machine filter
│   └── RateCalculator.png              # Prototype UI: Real-time rental & mobilization calculator
├── index.html                          # Semantic landing page structure
├── style.css                           # Modular stylesheet with strict line-budget discipline
└── README.md                           # Documentation & project overview
