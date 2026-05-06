# Barbados Severance Pay Calculator (alpha prototype)

A clickable HTML prototype for an alpha.gov.bb service that estimates statutory severance pay in Barbados.

## What this is

- A **static prototype** (no build step)
- Styled with the **GovTech Barbados design system** (`@govtech-bb/styles`)
- A simple journey that reduces reading load:
  - Service guide → Start → Questions → Check your answers → Estimate

## What it covers

- Asks for:
  - Why you lost your job
  - Complete years worked
  - Usual pay (weekly or monthly)
- Calculates using the tiered rate bands (years 1–10, 11–20, 21–33)
- Shows a breakdown and “What to do next” after a successful estimate

## What it does not do

- Does not use Trident ID (not required for this service)
- Does not submit or store personal data
- Does not calculate late-payment interest rates (the rate is set by order)

## Run locally

Open the HTML file in a browser:

- `gov-tech/severance_calculator.html`

## Design system

- CSS is loaded from UNPKG:
  - `https://unpkg.com/@govtech-bb/styles@1.0.0-alpha.16/dist/styles.css`
- Design-system index:
  - `https://govtech-bb.github.io/design-system/llm/llms.txt`

## Notes

This prototype provides an **estimate of a minimum** and is meant for early testing and iteration.

