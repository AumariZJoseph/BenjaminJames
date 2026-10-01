# Benjamin James Construction & Equipment Rental — Website

## Project Overview

A marketing/brochure website for **Benjamin James Construction & Equipment Rental**, a
construction and heavy-equipment services company based in Dennery, Saint Lucia.

The site's job is to **establish a credible web presence** for a business that currently has
none, generate inbound leads (calls, quote requests), and give prospective clients — both
local and regional — a clear picture of what the company does and how to reach them.

This README describes **the business**. Visual design, typography, spacing, and component
styling are defined separately in `DESIGN_SYSTEM.md` — follow that file for anything visual.

---

## Business Details

| Field | Value |
|---|---|
| Business name | Benjamin James Construction & Equipment Rental |
| Owner | Benjamin James |
| Location | Dennery, Saint Lucia, W.I. |
| Phone | (758) 719-8180 |
| Phone (link format) | `tel:+17587198180` |
| Phone 2 | (758) 732-8142 |
| Phone 2 (link format) | `tel:+17587328142` |
| Email | **TBD** — not yet provided |
| Website domain | **TBD** — not yet purchased |
| Hours of operation | **TBD** — not yet provided |
| Social media | **None.** Do not invent or link to any social profiles. |

**Brand colors:** The owner favors **blue**, and the company's equipment is predominantly
**yellow**. Both should be present in the brand palette. Exact values and usage rules live in
`DESIGN_SYSTEM.md`.

---

## What the Business Does

Benjamin James Construction & Equipment Rental is a **civil works and heavy equipment
contractor** — not a residential home builder. Core service lines:

### 1. Equipment Rental
Heavy machinery rented out to other contractors, developers, and individuals.
Confirmed/standard equipment to plan for (exact fleet list pending from owner):
- Excavators( large and small)
- Double drum mini roller
- 20 ton truck
- Trailer head + lowboy

### 2. Trucking Services
Hauling and transport of materials, spoil, aggregate, and equipment for construction projects.

### 3. Moving of Heavy Machinery
Transport and relocation of heavy equipment — likely both their own fleet and client-owned
machines.

### 4. Civil Works
Large-scale infrastructure and site work, such as:
- Road construction and repair
- Bridge works
- Land clearing and site preparation
- Drainage and general civil engineering support

---

## Target Audience

- **Local Saint Lucian clients** — developers, other contractors, homeowners needing site work
- **Government / public sector** — infrastructure tenders, road and drainage projects
- **Regional / CARICOM clients** — contractors needing equipment or haulage on-island
- **Diaspora & overseas property owners** — people developing land in Saint Lucia remotely

Primary conversion action is a **phone call**. Secondary is a quote/contact form.

---

## Website Goals

1. Establish a professional, trustworthy online presence where none exists today.
2. Rank for local Saint Lucian construction and equipment rental searches (see SEO below).
3. Convert visitors into phone calls or quote requests.
4. Serve as a portfolio/showcase that can grow as photos of completed work arrive.
5. Act as a single source of truth for the business — services, fleet, contact, location.

---

## Required Pages / Sections

Build these as a **single-page site with anchored sections** initially. Some of these sections must link to their standalone page, but these standalone pages can be built later. Either way, all of the following must exist:

- **Hero** — company name, one-line positioning, primary CTA (call now / get a quote)
- **About** — who Benjamin James is, the company's experience and service area
- **Services** — the four service lines above, each with its own subsection
- **Equipment Rental** — what's available to rent; 
- **Trucking Services**
- **Moving of Heavy Machinery**
- **Civil Works**
- **Gallery** — showcase of projects and equipment. Must be **easy to add images to later**.
  Structure it now with placeholder slots even though real photos aren't available yet.
- **Contact** — phone, location, contact form, map/area served, hours (once provided)
- **Footer** — business name, phone, location, service area. **No social links.**

---

## SEO Requirements

This is a core goal, not an afterthought. Bake it in from the start:

- **Local SEO is the priority.** Target terms like:
  - "equipment rental Saint Lucia"
  - "excavator rental St Lucia"
  - "heavy equipment rental Dennery"
  - "trucking services Saint Lucia"
  - "civil works contractor Saint Lucia"
  - "land clearing Saint Lucia"
  - "heavy machinery moving St Lucia"
- Proper semantic HTML: one `<h1>`, logical heading hierarchy, descriptive `alt` text on
  every image.
- **Structured data (JSON-LD)** — `LocalBusiness` schema with name, address (Dennery, Saint
  Lucia), telephone `+17587198180`, area served, and `Service` entries for each service line.
- **Open Graph / Twitter card** meta tags for link sharing.
- Fast load times — optimize images, lazy-load gallery items.
- Mobile-first. Most local traffic will come from phones. The phone number must be a
  tap-to-call link everywhere it appears.
- Clean, descriptive URLs and a sitemap if multiple pages are used.
- Meta title/description per page targeting the keywords above.
- **Recommend** (mention in handoff notes, don't build): Google Business Profile setup, since
  there's currently no web footprint at all. This will matter more than the site itself for
  local search.

---

## Content Status — What Exists vs. What's Pending

**Available now:**
- Business name, owner name, location, phone number
- The four service categories
- Brand color direction (yellow + blue)

**Pending from owner (Feel free to utilize placeholders):**
- Exact equipment/fleet list available for rent
- Equipment used in their own operations
- Photos of completed projects and machinery
- Years in business / company history
- Certifications, licenses, insurance details
- Email address, hours, service radius
- Testimonials or client references (only if real ones are provided)


---

## Open Questions for the Owner

2. Do you want rates shown publicly, or "call for quote"? --> Call for quote
3. What areas of Saint Lucia do you serve — island-wide or a specific radius? --> Island wide
4. Do you have an email address and business hours to list? --> not yet
5. Any photos of past projects or the fleet we can start with? --> useplaceholders initially
6. Is there a preferred domain name? --> not yet
7. Any certifications, licenses, or insurance you want displayed for credibility? --> no, do not display
