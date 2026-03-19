---
description: 48-Hour Website Delivery SOP
---
# 48-Hour Website Delivery SOP

**Total time:** 5-6 hours of actual work spread across 48 hours
**Tech stack:** Astro, Tailwind CSS, Cloudflare Pages
**Target clients:** Plumbers, electricians, barbers, contractors, local service businesses

**Timeline breakdown:**
- Phase 0: Pre-kick-off (30 min)
- Phase 1: Setup (30 min)
- Phase 2: Development (3-4 hours)
- Phase 3: Review (1 hour)
- Phase 4: Launch (30 min)

## Phase 0: Pre-Kick-off (30 min)
### Content Collection Checklist
Send this to the client immediately after signing:
- REQUIRED: Business name, Phone, Email, Address, Hours, Services, About section, Photos (5-10)
- OPTIONAL: Tagline, Social links, Certifications, Years in business, Testimonials

### Content Audit
When content arrives, verify text volume, high-res images, contact info, business details. If incomplete, request specific missing items with a deadline.

### Set Expectations
Before starting, confirm with client: "I'll have a first draft ready in [24 hours]..."

## Phase 1: Setup (30 min)
### 1.1 Create Project from Template (5 min)
Create a new Astro project with Tailwind CSS, static output, mobile-first design, contact form ready, SEO-friendly structure.
`npm create astro@latest [project-name]`
`npx astro add tailwind`

### 1.2 Set Up Git Repository (5 min)
Initialize git, add, commit, create GitHub repo.

### 1.3 Configure Cloudflare Pages (10 min)
Connect to Git, set build command `npm run build` and output `dist`, deploy initial version.

### 1.4 Create Project Folder Structure (10 min)
Components: Header, Footer, Hero, Services, Gallery, Contact, Testimonials. Pages: index, about, services, gallery, contact, privacy. Styles: global.css.

## Phase 2: Development (3-4 hours)
### 2.1 Hero Section (30 min)
Full-width, prominent name, clear value prop, primary CTA, phone number, mobile-responsive.

### 2.2 Services Section (45 min)
Grid layout (2-3 cols desktop, 1 mobile), icon/image, title, brief description, consistent cards.

### 2.3 Gallery/Portfolio (30 min)
Responsive image grid, optimized via Astro Image, consistent aspect ratio, alt text, lazy loading.

### 2.4 Contact Section (30 min)
Form (Name, Email, Phone, Message) via Formspark, phone (click-to-call), email, address, hours, maps embed.

### 2.5 Footer (20 min)
Name, tagline, contact info, hours, social links, copyright with dynamic year, privacy policy link.

### 2.6 Privacy Policy (15 min)
Basic policy covering contact form metrics, analytics, cookies. 

### 2.7 SEO & Meta Tags (15 min)
Title (under 60 char), Description (under 160 char), Open Graph tags, Twitter card. JSON-LD for LocalBusiness, Sitemap, robots.txt.

## Phase 3: Review (1 hour)
### 3.1 Quality Gates Checklist
1. Interactive elements work
2. Mobile responsive (375px)
3. Meta tags present
4. No placeholder content ("lorem", "TODO")
5. Loading states on forms
6. Consistent spacing
7. Testimonials real

### 3.2 Performance Check
Target scores (90+) for Performance, Accessibility, Best Practices, SEO via Lighthouse.

### 3.3 Mobile Testing
Test at 375px and 768px in Chrome DevTools. Check form submits and navigation.

### 3.4 Send Preview Link
Email client with the link and checklist for review.

## Phase 4: Launch (30 min)
### 4.1 Apply Client Feedback
Edit text, replace images, evaluate layout scope. Push to trigger Cloudflare build.

### 4.2 Connect Custom Domain
Add www and apex domains in Cloudflare. Configure DNS (CNAME).

### 4.3 Post-Launch Setup
Google Search Console setup, submit sitemap, Google Analytics (if requested).

### 4.4 Client Handoff
Email handoff confirming site is live, SSL active, Google indexed, mobile optimized. Note 30-day post-launch support for minor changes.

## Quick Reference
- Common Blockers: Missing content, small images, unresponsive client, DNS issues. Manage closely.
