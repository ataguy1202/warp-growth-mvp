# Multi-State Employer Cost Calculator

A growth engineering prototype for [Warp](https://www.warp.co), demonstrating how a free tool can drive organic acquisition and serve as a top-of-funnel lead magnet for multi-state payroll customers.

## What This Is

An interactive calculator that estimates total employer obligations (FICA, FUTA, SUTA, workers' compensation, state disability, paid family leave) across all 50 states, adjusted by industry and headcount.

## Growth Thesis

Payroll-adjacent free tools are proven organic traffic drivers in this space. Companies like Gusto and Deel generate significant inbound volume through state-specific calculators and compliance tools. This prototype demonstrates the concept applied to Warp's positioning: helping companies understand the true cost of multi-state hiring before they commit.

**Acquisition funnel:**
1. Founder or HR lead searches "employer cost by state" or "payroll tax calculator [state]"
2. Lands on this tool, gets immediate value
3. Sees Warp CTA: "We handle all of this automatically"
4. Enters product evaluation

**SEO opportunity:** Each state breakdown can be expanded into a standalone landing page (e.g., `/employer-costs/california`), creating 50+ indexable pages targeting long-tail compliance queries. This is a high-leverage growth engineering project that compounds over time.

## Technical Details

- Single-file implementation (HTML/CSS/JS), zero dependencies
- Matches Warp's dark-mode design language and visual identity
- Responsive layout with sortable table, interactive state selection, and detailed per-state breakdowns
- Tax calculations cover: Social Security, Medicare, FUTA, SUTA (with state-specific wage bases), workers' compensation (industry-adjusted), SDI, PFML, transit taxes, and local tax flags
- Designed for easy integration into a Next.js or similar framework

## To Run

Open `index.html` in any browser. No build step required.
