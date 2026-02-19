# ArcaScience Website Proofreading & Content Recommendations

**Date:** 2026-02-19
**Scope:** `arcascience.ai`
**Priority levels:** CRITICAL | HIGH | MEDIUM | LOW

---

## Table of Contents

1. [Placeholder / Unfinished Content](#1-placeholder--unfinished-content)
2. [Spelling & Grammar Errors](#2-spelling--grammar-errors)
3. [Content & Factual Issues](#3-content--factual-issues)
4. [Missing Content & Improvements](#4-missing-content--improvements)
5. [UX / Copy Improvements](#5-ux--copy-improvements)
6. [SEO & Metadata](#6-seo--metadata)
7. [Missing or Broken Pages](#7-missing-or-broken-pages)

---

## 1. Placeholder / Unfinished Content

### [CRITICAL-01] Lorem Ipsum in Lifecycle Section

**Location:** Homepage > "Accelerate Decisions Across the Drug Lifecycle" > Phase tabs
**Issue:** The phase-specific content under the lifecycle tabs (Phase 1, Phase 2, Phase 3, Submission, Post-Marketing, Market Access) contains **Lorem ipsum placeholder text** instead of actual content.
**Action:** Replace placeholder text in each tab with real descriptions. Suggested content:

| Tab | Suggested content |
|-----|-------------------|
| **Phase I-II** | "Safety signal identification, DDI screening, comparator selection, early benefit-risk framing before Phase 3 investment." |
| **Phase III / Submission** | "CTD 2.5 benefit-risk sections, advisory committee preparation, quantified benefit-risk aligned with FDA and EMA." |
| **Post-Marketing** | "PSUR/PBRER generation, signal management, RMP updates, continuous benefit-risk monitoring across spontaneous reporting and RWE." |
| **Market Access** | "Value dossiers, comparative effectiveness, payer evidence packages for NICE, G-BA, HAS, CADTH, PBAC." |

---

## 2. Spelling & Grammar Errors

### [HIGH-01] Inconsistent Dash Usage Throughout

**Location:** Multiple sections across the site
**Issue:** Inconsistent use of em dashes, en dashes, and hyphens.
**Examples:**
- "Time-Consuming Manual Analysis" followed by an em dash after the title
- "benefit-risk" correctly hyphenated in most places
- Some sections use spaced em dashes, others don't

**Action:** Standardize to unspaced em dashes for all parenthetical breaks, and hyphens for compound modifiers. Audit all dash usage site-wide.

### [MEDIUM-01] "go/no-go" Capitalization

**Location:** Homepage > "The Benefit-Risk Evaluation Challenge" > Problem 1
**Current:** "delaying critical go/no-go decisions"
**Action:** Acceptable in body text but ensure consistency if used elsewhere on the site.

### [MEDIUM-02] Undefined BRTM Acronym in Step 2

**Location:** Homepage > Step 2 description
**Current:** "Our BRTM then validates these insights, isolating key risks and benefits for regulatory decisions."
**Issue:** BRTM acronym is never defined on the page.
**Action:** Define the acronym on first use. Suggested: "Our **Benefit-Risk Triage Model (BRTM)** then validates these insights..."

### [MEDIUM-03] Mixed Use of "benefit-risk" vs "Benefit-Risk"

**Location:** Throughout the site
**Issue:** Capitalized in headlines ("Benefit-Risk Decision Engine") but inconsistently capitalized mid-sentence. Sometimes "benefit-risk intelligence" and sometimes "Benefit-Risk Intelligence" in body copy.
**Action:** Establish a style guide rule:
- **Capitalized** when part of a product name or section heading (e.g., "Benefit-Risk Decision Engine")
- **Lowercase** in running text (e.g., "benefit-risk intelligence", "benefit-risk assessment")

### [MEDIUM-04] "day 1" Formatting in Hero

**Location:** Hero section
**Current:** "anticipate your drug's success from day 1"
**Issue:** "day 1" should be either "Day 1" or "day one" for consistency with the overall professional tone.
**Action:** Change to "Day 1" (capitalized, as it refers to a specific milestone concept in pharma).

---

## 3. Content & Factual Issues

### [CRITICAL-02] Unverifiable / Risky Claims

**Location:** Multiple sections

| Claim | Location | Issue | Recommendation |
|-------|----------|-------|----------------|
| "9 out of 10 drugs failing" | Challenge section | Well-known stat but should cite a source (e.g., MIT/Tufts study) | Add footnote/source |
| "$2.3B per approval" | Challenge section | This figure is from a 2020 Tufts CSDD study; verify it's still the accepted figure | Add footnote: "Source: Tufts CSDD, 2020" |
| "ArcaScience won 100% of its deals when facing traditional consulting companies" | About section | Bold claim, needs context (sample size, time period) | Rephrase: "In competitive evaluations against traditional consulting firms, ArcaScience has consistently been selected" or add specifics |
| "By 2025, 80% of pharma will have adopted AI benefit-risk-enabled solutions" | About section | **We are now in 2026**, this prediction is outdated. The citation "(IDC Top 10 Predictions for Life Sciences, 2024)" should be verified | Remove or update to reflect actual 2025/2026 data |
| "60% faster evaluation time" | Step 3 | Compared to what baseline? | Add clarifier: "compared to traditional manual BRA processes" |
| "9x more insights detected" | Step 3 | What counts as an "insight"? Vague metric | Consider rephrasing: "9x more safety signals detected" |
| "70% cost reduction vs. CROs" | Step 3 | Compared to which CROs? Average or specific? | Add footnote with methodology |

### [CRITICAL-03] Outdated IDC Prediction

**Location:** About section
**Current:** "By 2025, 80% of pharma will have adopted AI benefit-risk-enabled solutions. (IDC Top 10 Predictions for Life Sciences, 2024)"
**Issue:** It is now 2026. This forward-looking prediction is now in the past.
**Action:** Either:
- Update with actual 2025/2026 adoption data
- Replace with a current analyst quote
- Remove entirely and replace with a verifiable present-tense statement

### [CRITICAL-04] PSUR Timeline Needs Clarification

**Location:** Homepage > Challenge section
**Current:** "Traditional benefit-risk assessments can take **up to 18 months** per drug"
**Issue:** The 18-month figure conflates the full benefit-risk assessment lifecycle with the PSUR/PBRER cycle time (typically 12-16 weeks). This makes the claim seem inflated or vague.
**Action:** Clarify the distinction. Suggested revision:
> "Full benefit-risk assessments across the drug lifecycle can span 12-18 months, while individual PSUR/PBRER cycles alone take 12-16 weeks, each one a manual, resource-intensive process."

### [MEDIUM-05] "100+ billion data points" Precision

**Location:** Multiple sections
**Issue:** Used interchangeably as "100+ billion data points" and "100B+ data points." The branded product name is "AS Profiling Base 100b(R)", and the "100b" in the product name may become outdated as the database grows.
**Action:** Ensure consistent formatting. Recommend using "100+ billion" in body text and "100B+" only in stat badges/counters.

### [MEDIUM-06] "Founded in 2018" Repetition

**Location:** Appears 3 times on the homepage alone (About section, Science section, footer schema)
**Action:** Keep in the About section and footer. Remove from the Science section to reduce redundancy.

---

## 4. Missing Content & Improvements

### [CRITICAL-05] Add Partner Logos

**Location:** Homepage social proof section
**Issue:** Only Sanofi is mentioned as a client. If other partnerships exist (AstraZeneca, GSK, Takeda, ICON, Paris Brain Institute, etc.), they should be displayed.
**Action:** Add confirmed partner logos to the homepage. A single client reference is a significant credibility gap for a B2B pharma platform.

### [HIGH-02] Add Hero Stats Bar

**Location:** Hero section
**Issue:** Key statistics (100B+ data points, 24 AI models, 50+ submissions, 20+ clients, 12 therapeutic areas) are buried throughout the page instead of being displayed prominently.
**Action:** Add a stats bar directly below the hero headline to surface these numbers at first glance. This immediately builds credibility.

### [HIGH-03] Strengthen Testimonial Attribution

**Location:** Testimonial section
**Current:** "Global R&D Team, Sanofi" (anonymous)
**Issue:** An anonymous team attribution is far less convincing than a named individual.
**Action:** If authorized, replace with a named attribution (e.g., a VP-level contact at the client). Confirm with the Sanofi contact which level of attribution is approved.

### [HIGH-04] Add Team Size / Company Stats

**Location:** About section or a dedicated Company page
**Issue:** No team size or company growth information is shown.
**Action:** Add key company stats: team size (60+), number of nationalities, office locations (Paris, Sunnyvale), investor backing. This humanizes the company and builds trust.

---

## 5. UX / Copy Improvements

### [HIGH-05] Too Many CTAs with Same Label

**Location:** Throughout the homepage
**Issue:** "Book a demo" appears **4+ times** on the homepage. While repetition is fine for a primary CTA, it becomes noise. Additionally, the secondary CTA labels vary without clear hierarchy:
- "See how it works"
- "Explore documentation"
- "Explore Use Cases"
- "Talk to an Expert"
- "See our mission"
- "Meet the team"
- "Any question?"

**Action:** Establish a CTA hierarchy:
1. **Primary CTA:** "Book a Demo" (keep 2-3 instances max: hero, mid-page, footer)
2. **Secondary CTA:** Standardize to 2-3 consistent alternatives (e.g., "See How It Works", "Explore Use Cases")
3. Remove "Any question?", it's weak and informal for a pharma B2B product

### [MEDIUM-07] Hero Tagline Could Be Stronger

**Location:** Hero section
**Current:** "Trusted by Pharmaceutical Leaders"
**Issue:** Generic, could apply to any pharma vendor.
**Suggestion:** Add concrete proof points:
> "Trusted by 20+ pharmaceutical leaders across 50+ regulatory submissions"

### [MEDIUM-08] Step Numbering Mismatch

**Location:** Homepage > Six-step process
**Issue:** Steps are labeled "Step 1" through "Step 6" but the section header says "Five Integrated Stages." There are actually six steps listed.
**Current header:** "From Clinical Framing to Automated Outputs - **Five** Integrated Stages for Comprehensive Benefit-Risk Intelligence."
**Action:** Change "Five" to "Six", or restructure to genuinely have five stages by merging two steps.

### [MEDIUM-09] Inconsistent Section Tone

**Location:** Across homepage
**Issue:** The page oscillates between:
- Direct/confident tone: "anticipate your drug's success from day 1"
- Formal/passive tone: "Our methodologies are grounded in pharmacoepidemiology best practices"
- Marketing superlatives: "Building the world's largest benefit-risk intelligence database"

**Action:** Pick a consistent voice. For pharma B2B, recommend confident but measured. Avoid superlatives like "world's largest" unless backed by a verifiable benchmark.

### [LOW-01] "Connection" Navigation Item

**Location:** Secondary nav
**Issue:** "Connection" is likely a login/portal link but the label is ambiguous. In English, "Connection" sounds like "networking" rather than "sign in."
**Action:** Rename to "Sign In", "Log In", or "Client Portal" depending on what it links to.

### [LOW-02] Address Formatting

**Location:** Footer
**Current:** "8, rue Jean-Antoine de Baif" (French formatting with comma after number)
**Issue:** This is correct for French formatting, but the rest of the site is in English.
**Action:** Consider using English formatting: "8 Rue Jean-Antoine de Baif" (no comma, capitalized "Rue"). Alternatively, keep the French format and add "Paris, France" for international clarity.

---

## 6. SEO & Metadata

### [MEDIUM-10] Schema Markup Has Only 1 Review

**Location:** Homepage structured data
**Current:** Rating 5/5 based on "1 review"
**Issue:** A single 5-star review in schema markup looks artificial to Google and could trigger spam filters.
**Action:** Either remove the review schema entirely, or add genuine aggregated review data once you have multiple reviews (e.g., from G2, Capterra, or client surveys).

### [MEDIUM-11] Meta Description Could Be More Targeted

**Location:** Site meta
**Current:** "AI-powered benefit-risk decision engine for pharmaceutical drug safety and regulatory compliance. Supporting 50+ regulatory submissions across 12 therapeutic areas since 2018."
**Issue:** Decent but could include more high-value keywords.
**Suggested:** "ArcaScience: AI-powered benefit-risk analysis platform for pharma. 24 proprietary models, 100B+ data points. Trusted for 50+ FDA/EMA/PMDA regulatory submissions across 12 therapeutic areas."

---

## 7. Missing or Broken Pages

### [CRITICAL-06] Subpages Return 404

**Location:** Direct URL access to `/about`, `/team`, `/faq`, `/use-case`, `/vision`, `/publications`
**Issue:** Navigating directly to these paths returns 404 errors. This is likely a SPA routing issue where the server doesn't have fallback routes configured.
**Action:** Configure server-side redirects so that all routes fall back to `index.html` (for SPA) or return proper pages. This also affects SEO crawling, as Google will see 404s for these pages.

### [HIGH-06] No Accessibility Statement

**Location:** Footer / Legal section
**Issue:** No accessibility page or statement is present on the site.
**Action:** Add an accessibility page/statement. For pharma B2B clients (especially US-based), WCAG 2.1 AA compliance is increasingly expected.

### [HIGH-07] Social Media Links: Verify Active Presence

**Location:** Footer
**Listed:** Instagram, X.com, LinkedIn
**Action:** Verify these profiles exist and are active. An inactive or empty social media profile is worse than no link at all. Instagram is unusual for a B2B pharma SaaS; consider whether it adds value.

---

## Summary of Priority Actions

### Immediate Fixes (This Sprint)

| # | Issue | Action |
|---|-------|--------|
| CRITICAL-01 | Lorem ipsum in lifecycle tabs | Replace with real content (see suggested copy above) |
| CRITICAL-03 | Outdated IDC 2025 prediction | Remove or update |
| CRITICAL-06 | 404 on direct subpage URLs | Configure server-side routing fallback |
| MEDIUM-08 | "Five Integrated Stages" but six listed | Change to "Six" or merge steps |
| MEDIUM-02 | BRTM acronym undefined | Define on first use |

### Short-Term Improvements (Next Sprint)

| # | Issue | Action |
|---|-------|--------|
| CRITICAL-02 | Unverifiable claims need sources | Add footnotes/citations |
| CRITICAL-04 | PSUR timeline conflation | Clarify 18 months vs 12-16 weeks |
| CRITICAL-05 | Only one client logo shown | Add confirmed partner logos |
| HIGH-02 | Key stats buried in page | Add hero stats bar |
| HIGH-03 | Anonymous testimonial | Get named attribution approved |
| HIGH-05 | CTA overload | Reduce to 2-3 "Book a Demo" instances |

### Polish & Optimization (Backlog)

| # | Issue | Action |
|---|-------|--------|
| HIGH-01 | Inconsistent dash usage | Standardize site-wide |
| HIGH-04 | No company stats shown | Add team size, offices, investors |
| HIGH-06 | Missing accessibility page | Add WCAG statement |
| HIGH-07 | Social media links | Verify profiles, consider removing Instagram |
| MEDIUM-03 | Benefit-Risk capitalization | Create style guide rule |
| MEDIUM-07 | Generic hero tagline | Add specifics |
| MEDIUM-09 | Inconsistent tone | Align to confident-but-measured voice |
| MEDIUM-10 | Single review in schema | Remove or expand review data |
| LOW-01 | "Connection" nav label | Rename to "Sign In" or "Client Portal" |
| LOW-02 | French address format | Align to English or add country clarifier |

---

## Notes for Web Developers

- All issues reference sections by their heading text for easy location in the codebase.
- For the SPA routing fix (CRITICAL-06), if using Vercel/Netlify, add a `_redirects` file or `vercel.json` rewrite rule. If using Nginx, add `try_files $uri /index.html`.
- For the outdated claims, coordinate with the marketing/regulatory team before publishing changes, as some stats may require internal approval.
