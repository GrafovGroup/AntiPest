# AntiPest.ca — Phase 1A Codex Master Prompt

## Objective
Build a premium bilingual (English and Canadian French) pest control website for residential, commercial, and industrial customers across Canada. Position AntiPest.ca as a direct service provider, not a directory or lead broker. Do not imply unverified operational coverage.

## Approved identity
- Wordmark: **AntiPest.ca**; descriptor **PEST CONTROL SERVICES**.
- Light logo: navy Anti and .ca (#08264A), red Pest (#E30613), on white.
- Dark logo: white Anti and .ca, red Pest, on dark navy.
- Bold italic sans-serif; small tapered red accents flanking descriptor.
- No shields, pests, maple leaves, independent emblems, elaborate frames or gradients.
- Produce editable SVG light/dark, compact, monochrome and favicon variants. Match approved visual direction; validate appearance before launch.

## Design standards
- Wide responsive containers, strong mobile usability, uppercase navigation, rounded buttons, clear hierarchy.
- EN/FR switch in top bar; accurate Québec French, localized navigation, forms and metadata.
- Realistic pest-control-specific photography, no irrelevant scenery, no repetitive images, no artificial claims or AI credits.
- Accessible contrast, keyboard navigation, alt text, Core Web Vitals optimization.

## Architecture
Home; Residential; Commercial; Industrial; individual pest services (rodents, ants, cockroaches, bed bugs, wasps, termites, spiders, fleas); preventive programs; Industries (restaurants, warehouses, food processing, hospitality, retail, property management, healthcare); Locations; About; Resources; Contact; Request Quote.
Build templates for province/territory and major city plus surrounding-area pages, but publish only substantive unique local content. Do not claim an office or active technicians without confirmation.

## Conversion
Phone (833) 696-9996; email info@antipest.ca (verify mailbox before live launch).
Primary CTA REQUEST A QUOTE; secondary CALL NOW.
Separate residential/commercial forms capturing pest concern, service location, property/facility type, urgency, contact details, consent; commercial adds site count, facility size and recurring service interest. Secure server-side validation, anti-spam, privacy-aware handling; no fake success messages.

## Technical and SEO

**Editorial standard · Google E-E-A-T**

Start with the decision the reader came to make. Where first-hand experience helps, use work the publisher can document and share. Identify who produced or reviewed technical guidance where readers would expect it, and explain the method when it affects interpretation. Support consequential claims with the most relevant original source. Claim outside recognition or credentials only when readers can verify them.

Identify the applicable jurisdiction and current public authority or product label for pesticide and wildlife claims. Seek qualified review where health or safety is involved. Publish technician experience, licensing and treatment outcomes only when verified for that service and region.

At content review, trace a material claim on a representative page back to its source. Correct, qualify or omit an unsupported claim, including in translated copy and structured data where present. [Google Search Central](https://developers.google.com/search/docs/fundamentals/creating-helpful-content) · [Universal master prompt](https://github.com/GrafovGroup/MasterPrompt/blob/main/MASTER_PROMPT.md).

Use a maintainable static-first modern stack deployable to WHC.ca Pro hosting; document build and cPanel deployment requirements. Responsive components, semantic HTML, EN/FR routing, canonical URLs, hreflang, sitemap, robots.txt, Open Graph, relevant schema.org structured data without invented ratings. Unique titles/descriptions and useful FAQs. Avoid doorway pages and duplicated city text.

## Compliance
Pesticide application and pest-control business licensing, insurance, technician qualifications and wildlife rules vary by province. Never assert licences, guarantees, environmentally safe treatment, emergency response, testimonials, local offices or nationwide field capacity without verified evidence. Treat geographic pages as service information only until coverage is confirmed.

## Deliverables and execution order
1. Inspect repository; preserve existing code if present.
2. Implement brand tokens and logo SVG variants.
3. Build bilingual homepage and shared navigation/footer.
4. Build reusable service, industry and location templates.
5. Add validated quote forms and contact flows.
6. Add SEO/accessibility/performance checks and deployment README.
7. Run tests/build, provide preview and report remaining operational prerequisites.
Pause for approval after homepage foundation before mass-generating location pages.

Repository: GrafovGroup/AntiPest
Hosting target: WHC.ca Pro
