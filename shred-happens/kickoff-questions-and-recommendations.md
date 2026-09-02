# Shred Happens Challenge — Page Revision Kickoff

Working notes for the Wix landing page revision (`/group-courses/shred-happens-challenge`).
Goal: 5,000 waitlist sign-ups by Oct 5, then convert that list to challenge sign-ups Oct 6–17.

## Questions before I start building

**Access & platform**
1. Can I get Wix Editor access (not just the mobile app) so I can actually rebuild the page — what permission level, and is there a staging/duplicate page I should build on so the live page stays untouched until we're ready to swap?
2. Right now the waitlist button links out to a separate Mailchimp landing page. Is that separation required (compliance, existing automation, tracking), or can I embed the signup form directly on the Wix page? Embedding almost always lifts conversion because it removes a click and a page load — worth doing unless there's a reason not to.
3. For the Oct 12–17 sign-up window, is the checkout link/embed code from Hailey's app platform ready now, or does that come later? I'll leave a placeholder block either way, but want to know if I'm building against a real URL.
4. Is there a Meta/TikTok/Google pixel already firing on this page (you mentioned Instagram is a channel) that I need to confirm stays intact through the rebuild?

**Content — experts, testimonials, proof**
5. Which 1–2 experts are being added for the October lineup, and do you have bio copy + headshots for them yet, or should I draft placeholder bios pending your review?
6. From the testimonials spreadsheet, can you flag (or let me pull) the 4–6 strongest quotes for the page itself — I'll use the rest as rotating/carousel content. Photo testimonials > text-only where we have them.
7. Any updated aggregate stats we can put in the hero or a stat bar — e.g. total women who've done the challenge, average results, number of challenges run? A number like "3,000+ women already joined" (which you mentioned) is strong, honest social proof and I'd like to use it prominently — confirm I can quote that.
8. The current page shows a private Facebook accountability group. With the new app in development, is the community still FB-based for October, or should that copy change?
9. Any change to program mechanics (6 weeks, live calls, macro/calorie plan, gym + home options, pricing) from what's currently on the page, or is this purely a copy/proof/UX refresh with the same offer?

**Positioning & compliance**
10. You said "40+, not excluding women in their 30s" — do you want that stated explicitly on the page (e.g., in the hero or an FAQ), or kept implicit through testimonial ages/photos?
11. Keep the existing disordered-eating disclaimer as-is, or has legal/compliance language changed?

**Urgency mechanism**
12. Is there an actual incentive for joining the waitlist before Oct 5 (bonus, locked-in price, early-bird perk), or is the deadline just "waitlist emails go out Oct 6"? If there's a real incentive I can build urgency copy and a countdown around it — if not, I'd rather not fake urgency.

---

## Copy & structure recommendations (my first pass — tell me what to adjust before you finalize tomorrow)

### 1. Waitlist form goes above the fold, embedded — not a button to another page
Every extra click between "I'm interested" and "I'm on the list" costs sign-ups. Recommend replacing the "Priority Waitlist" button with an inline email-capture field (name + email, one button) directly in the hero, still linking to a secondary full-page waitlist option below for anyone who scrolls. If Mailchimp can be embedded via their form embed code or a Wix-native form piped into Mailchimp (via Wix's built-in Mailchimp integration or an automation tool), that's the highest-leverage single change on this whole page.

### 2. Hero gets a proof line + urgency line immediately under the headline
Something like:
> **6 weeks. Real macros, real coaching, real results — built for women 40+ (and every woman who's done "starting over" before).**
> Join 3,000+ women already on the waitlist for October 2026.

Short, concrete, and puts the social proof number to work instead of burying it below the fold.

### 3. Add a slim trust/stat bar right under the hero
Small horizontal strip: number of past participants · number of experts on faculty · years running · "gym or home" — scannable in two seconds, and doubles as a place to hide a countdown to Oct 5 if we have a real reason for one.

### 4. Refresh before/after + testimonials before anything else content-wise
These are the two elements doing the most conversion work on the page and they're the ones you flagged as stale. Once you send the approved spreadsheet + drive folder, I'll rebuild the carousel and pull 1–2 of the strongest quotes into a second, larger testimonial block lower on the page (right before the FAQ, where objection-handling matters most).

### 5. Guest experts section: add the 1–2 missing names, and consider adding one authority signal per expert as a subhead (credential, publication, follower count) rather than only degree + title, since that's what builds trust fast when someone's scrolling.

### 6. FAQ: add these if not already answered elsewhere
- "Who is this program for?" (age range, fitness level — this is an easy SEO/AI-answer target, see below)
- "What happens after I join the waitlist?" (sets expectation for the Oct 6 email sequence, reduces waitlist drop-off/no-opens)
- "Is there a deadline to join the waitlist?" (only if #12 above gives us a real answer)
- "How is this different from a generic weight-loss program?" (menopause/midlife-specific positioning is your differentiator — make it explicit)

### 7. Mobile-first pass
A lot of this traffic is coming from Instagram links per the assets you shared — the current page is fairly text-dense in the FAQ and expert bios. I'll tighten line length and make sure the embedded waitlist field is usable one-handed on mobile, since that's most of the funnel traffic.

---

## SEO recommendations
- **Page title / meta description**: current title likely isn't optimized around the actual search terms ("fitness challenge for women over 40", "midlife women weight loss program"). I'll draft options once experts/copy are locked.
- **H1**: make sure "Shred Happens Challenge" or the descriptive line is an actual `<h1>`, not just styled text in an image/graphic.
- **Image alt text**: before/after photos, expert headshots, and the hero image all need descriptive alt text — currently likely missing since a lot of the page is graphic-driven.
- **FAQ schema markup**: the page already has an FAQ accordion — adding `FAQPage` structured data is close to free (no visual change) and makes individual Q&As eligible for rich results in Google, which also feeds AI answer engines (see below).
- **Page speed**: hero graphics and before/after carousels are often large image files on Wix; I'll check compression/lazy-loading once I have edit access.

## "Generative AI optimization" (AI/answer-engine visibility)
This is really the same discipline as good SEO plus a few extra habits, since tools like ChatGPT, Gemini, and Google's AI Overviews lean heavily on structured data and clearly-stated facts rather than marketing copy:
- State plain facts in text (not just inside images): what it is, who it's for, how long, what's included — the way the FAQ already does. AI answer engines pull directly from FAQ schema and clearly labeled Q&A text.
- Keep one consistent, quotable definition of the program near the top of the page (e.g., "Shred Happens Challenge is a 6-week fat-loss and strength program for midlife women, led by [experts], running twice a year") — this is the sentence most likely to get lifted verbatim into an AI answer.
- Structured data (FAQPage, and possibly Course or Event schema) helps both traditional SEO and AI crawlers parse the page correctly.
- Make sure the page is indexable and not blocked, and that Hailey's brand name + program name are consistent across the site, Instagram, and any directories — entity consistency matters more for AI answer engines than for traditional search.

---

## What I need from you to move from "questions" to "building"
1. Wix access
2. Answers to the numbered questions above (especially #2, #5, #6, #7, #12 — those change the actual layout)
3. The finalized approved testimonials + before/after selects (understood the drive folder cleanup is in progress — happy to start with what's ready and swap in the rest as it lands)
4. New expert bios/headshots
