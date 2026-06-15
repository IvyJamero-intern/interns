# Phase 5 — Launch Campaign, Book Calls, Report

**Product:** msg2ai Events Assistant  
**From address:** ivy@msg2ai.xyz  
**Target:** 72 event-industry accounts (83 contacts) across PH  
**Launch date:** 2026-06-15  
**Week ending:** 2026-06-19  

---

## 1. Launch Order — Touch 1 (Email 1)

### Batch 1 — Top 15 Venues (use personalized Email 1 from `outreach-sequence-top15.md`)

Send Day 1. These are the highest-value, most-researched accounts. Each gets a custom hook referencing their property.

| # | Contact | Company | Segment | Use Template |
|---|---------|---------|---------|-------------|
| 1 | Melissa Ferrer | New World Makati Hotel | Venue | Top-15 Account 1 — "200+ events/year" |
| 2 | Pamela Correa | Edsa Shangri-La, Manila | Venue | Top-15 Account 2 — "Shangri-La already uses us" |
| 3 | Christopher Canadella | NUSTAR Resort | Venue | Top-15 Account 3 — "premier Visayas resort" |
| 4 | Ronie Reyes | Crimson Hotel Filinvest City | Venue | Top-15 Account 4 — "Filinvest MICE market" |
| 5 | Dulce Sy | Kingsford Hotel Manila | Venue | Top-15 Account 5 — "NAIA proximity" |
| 6 | Edwin Ulep | The Heritage Hotel Manila | Venue | Top-15 Account 6 — "events + catering workflow" |
| 7 | Victor Ote | Grand Westside Manila Bay | Venue | Top-15 Account 7 — "new property advantage" |
| 8 | Juvy Agudon | Clark Marriott Hotel | Venue | Top-15 Account 8 — "Clark MICE growth" |
| 9 | Arabella Barz | Mercure Mactan Cebu | Venue | Top-15 Account 9 — "Cebu MICE" |
| 10 | Daryl Tan | The Lind Hotels | Venue | Top-15 Account 10 — "premium service" |
| 11 | Amie Villena | Megaworld Hotels & Resorts | Venue | Top-15 Account 11 — "multi-property CRM" |
| 12 | Andrea Liamzon | Villa Milagros Events Venue | Venue | Top-15 Account 12 — "Tagaytay boom" |
| 13 | Lea Wong | TAG Resort Coron | Venue | Top-15 Account 13 — "Coron MICE destination" |
| 14 | Carolin Dekeyser | NAY PALAD Hideaway | Venue | Top-15 Account 14 — "luxury retreats" |
| 15 | Daphne Guinto | Shangri-La Group | Venue | Top-15 Account 15 — "Manila events coordination" |

**Action:** Open `outreach-sequence-top15.md`, copy each account's Email 1, replace `[Your name]` with `Ivy`, send individually from ivy@msg2ai.xyz.

### Batch 2 — Remaining Venues + Pick of MICE (use Segment A/B Email 1 from `phase4-outreach-prep.md`)

Send Day 2 (or same day, 3+ hours after Batch 1).

| # | Contact | Company | Segment | Template |
|---|---------|---------|---------|----------|
| 16 | Sapphira Chua | Edsa Shangri-La | Venue | Segment A — "Quick thought for {{first_name}}" |
| 17 | Pia Depayso | Edsa Shangri-La | Venue | Segment A |
| 18 | Helen Segador | New World Makati | Venue | Segment A |
| 19 | Jose Refugia | Shangri-La Group | Venue | Segment A |
| 20 | Juzmine Encinas | Shangri-La Group | Venue | Segment A |
| 21 | Elijah Canzana | Marriott Manila | Venue | Segment A |
| 22 | Vincent Rosario | Aman | Venue | Segment A |
| 23 | Ryon Tionloc | Sunlight Hotels | Venue | Segment A |
| 24 | Princess Sanico | Grand Tradition | Venue | Segment A |
| 25 | Kris Aralar | SiGMA World | MICE/PCO | Segment B — "Idea for {{first_name}}" |
| 26 | Dhaniel Mariano | SiGMA World | MICE/PCO | Segment B |
| 27 | Sean Zuniga | SiGMA World | MICE/PCO | Segment B |
| 28 | Olga Yaroshevsky | AIBC World | MICE/PCO | Segment B |
| 29 | Diana Klinteberg | M&SE | MICE/PCO | Segment B |
| 30 | Carla Rabe | The Conference Group | MICE/PCO | Segment B |

### Batch 3 — MICE/PCO (use Segment B Email 1)

Send Day 3.

| # | Contact | Company | Template |
|---|---------|---------|----------|
| 31–45 | Clyde Villanueva → Blancajoy Bustamante | Ortus Club → Fireworks Trade Media | Segment B |

Full list in `phase4-outreach-prep.md` Batch 3 (15 contacts).

### Batch 4 — Corporate Events (use Segment C Email 1)

Send Day 4.

| # | Contact | Company | Template |
|---|---------|---------|----------|
| 46–60 | Joie Rocacorba → Hanna Agura | AvePoint → Fireworks Trade Media | Segment C |

Full list in `phase4-outreach-prep.md` Batch 4 (14 corporate + 1 MICE leftover).

### Batch 5 — PR/Agencies (use Segment C Email 1, optional)

Send Day 5 if bandwidth allows. Contacts 61–83: NuWorks, Paint it Red, Steady Rise, Stratworks, TA-FBDI, Team One, TNC, RedTorch, KreativDen, Bull.ish, Clutch, Ideascape, Grupo Agatep, GeengerGrp, Bridges PR, Nino Reantaso, Pamela Sanchez-Piedad, Kyzia Benosa, Audrey Gendrala, Cedie Dantes, Nicole Tizon, Sophia Meniado, Ryan Tolley.

---

## 2. Reply Tracking Log

Create this in Twenty CRM. For every reply, log immediately.

### Fields per Contact

| Field | Value | How |
|-------|-------|-----|
| **Stage** | Contacted → Replied → Call Booked → Signup | Update manually |
| **Reply type** | Positive / Neutral / Negative / OOO / Bounce | Manual tag |
| **Reply summary** | 1-line quote or gist | Note field |
| **Call booked?** | Yes / No + date/time | Calendar link |
| **Demo done?** | Yes / No | Task completed |
| **Signup?** | Yes / No | Stage = Signup |
| **Notes** | Objections, hot buttons, competitor mentions | Free text |

### Saved View: "Inbox — Needs Reply"

```
Stage: Contacted
AND Days since last activity: < 7
AND Reply type is empty
→ Open conversations waiting for a human response
```

### Saved View: "Follow-Up Needed (Stalled)"

```
Stage: Contacted OR Replied
AND Last activity: > 3 days ago
AND No upcoming task
→ These need a nudge (Email 2 if Day 7+)
```

---

## 3. Warm-Lead Signup Offer Script

When someone replies positively — interested, wants to see more — use this:

### Email Reply

> Hi {{first_name}},
>
> Great to hear! Here's the easiest way to try it:
>
> **1. Test it right now** — text "hello" to +63 XXX-XXX-XXXX and you'll see the Events Assistant respond instantly.
>
> **2. Free trial** — I can set you up with a 14-day test account. No credit card, no commitment. You'll have a working WhatsApp bot for your venue in under 30 minutes.
>
> **3. Live walkthrough** — prefer a guided tour? Pick a time that works: [Calendly link]
>
> What works best for you?
>
> Ivy

### Phone / Video Call Script

> "Here's what I'd suggest: I can spin up a free test account for you right now. You'll get a dedicated WhatsApp number that handles event inquiries automatically. Play with it for 14 days — if it saves your team time, we keep going. If not, no hard feelings."
>
> → Offer to set it up on the call (5 min setup)
> → If they want to think about it, send the Calendly link + test number in a follow-up email

### In-Call: Free Test Setup Steps

1. Ask for their venue name, contact number, typical event types
2. Set up msg2ai Events Assistant in test mode
3. Share the test number with them immediately
4. Schedule a 15-min check-in call for Day 3 of their trial

---

## 4. Inbox Cadence — Reply Workflow

| Scenario | Action |
|----------|--------|
| **Positive — "tell me more"** | Send warm-lead signup offer (section 3) |
| **Positive — "let's talk"** | Book discovery call via Calendly link, move to Call Booked |
| **Neutral — "send info"** | Reply with Loom link + 2-line summary, mention free trial |
| **Negative — "not interested"** | Thank them, mark as Negative, keep for Touch 3 breakup |
| **OOO / Auto-reply** | Move to Contacted, do nothing, auto-send next touch on schedule |
| **Hard bounce** | Remove from list, log in CRM notes |
| **Soft bounce** | Retry once after 48h, then remove |

### Daily Reply Check

- Check ivy@msg2ai.xyz inbox 2x/day (midday + EOD)
- Log every reply in Twenty CRM within 1 hour
- Reply to positives within 4 hours
- Stage updates happen same-day

---

## 5. Deliverability Reminders

| Rule | This Week |
|------|-----------|
| **Batch size** | 10–15/day max (spread across 2–3 hours) |
| **From** | ivy@msg2ai.xyz only |
| **Content** | Plain text, 1 link max, no images, no spam triggers |
| **Personalization** | Every email has `{{first_name}}` and `{{company}}` filled in |
| **Unsubscribe** | "Reply STOP to opt out" footer on every email |
| **Bounces** | Check after each batch; remove hard bounces immediately |

---

## 6. End-of-Week Report Template

File: `Interns/ivy/progress-reports/2026-06-19.md`

See that file for the completed weekly report. Fill in the metrics as the week progresses:

### Metrics to Track

| Metric | How to Measure |
|--------|---------------|
| **Emails sent** | Count by batch. Target: 60–83 by Friday |
| **Open rate** | If open tracking available. Target: 40%+ |
| **Reply rate** | Replies / sent. Target: 10–15% |
| **Calls booked** | Count. Target: 3–5 |
| **Signups** | Count. Target: 2–3 |
| **Bounces** | Count. Remove from list |
| **Unsubscribes** | Count. Note any patterns |

### What to Capture in Report

- **What resonated** — which hooks got replies, which segments engaged most
- **Objections heard** — common reasons for "not interested" (price? timing? fit?)
- **Next-week plan** — Touch 2 (case/value) to non-replied, Touch 3 (breakup) to non-replied from week 1, expand list with new searches (SMX, PICC, Hilton, DMCs), add WhatsApp outreach where appropriate
