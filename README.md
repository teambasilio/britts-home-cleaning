# Britt's Home Cleaning — Website (Preview)

Single-page website for Britt's Home Cleaning. White / black / blush pink, mobile-first, no build step — the whole site is one `index.html` (photos are embedded and optimized, so the file works anywhere).

## Preview it
- Open `index.html` in any browser, **or**
- Turn on GitHub Pages: repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**. The site will appear at `https://teambasilio.github.io/britts-home-cleaning/` within a few minutes.

## What's in this preview (Phase 1 + booking interface)
- Home with logo, headline, and supplied cleaning photos
- Services & Pricing — November 2026 specials: 3-Hour Deep Clean $125 · 6-Hour $230 · 8-Hour $300
- What's Included — expandable deep-clean checklist
- Before & After photos supplied by the business
- About + Contact with call/text buttons and a spam-protected contact form (honeypot)
- Booking form: package → date/time → details → price summary → required 48-hour cancellation-policy acceptance (acceptance + timestamp are recorded with the booking). Booked times are disabled to prevent double booking.
- Privacy Policy and Cancellation Policy in the footer

## Activates at launch (Phase 2)
- Secure card checkout through the business's existing billing/Stripe setup (full payment at booking, transaction IDs stored, no card data ever touches this site)
- Booking confirmation + cancellation emails, automatic 48-hour refund handling
- Owner admin dashboard: appointments, blocked dates/times, booking hours, package/price editing, payment/refund status, photo and text editing
- Contact form delivery to the business email

## Before launch — details to confirm with the owner
1. ~~Business phone number~~ — SET 2026-11-15 from her Instagram bio: (505) 635-2523 (Call/Text buttons live)
2. ~~Service area~~ — SET 2026-11-15: San Juan County
3. Business email for booking notifications and the contact form
4. Regular pricing after the November 2026 specials
5. Booking availability: days/hours open, closed weekdays (`CONFIG.closedWeekdays`, `CONFIG.slots`)
6. Final cancellation/rescheduling policy confirmation
7. ~~Social media links~~ — SET 2026-11-15: Instagram @brittshomecleaning
8. Owner/team photo for the About section (placeholder photo used until supplied)

## Custom domain (after approval)
Buy the domain, then point it at the host (GitHub Pages or Render) and update the repo's Pages custom-domain setting — no site changes needed.
