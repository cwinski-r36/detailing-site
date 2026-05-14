# Flatiron Detail Co — Next Steps Plan

---

## 1. Content to Finalize

### Still Needs to Be Filled In

| Page | Item | Status |
|------|------|--------|
| About | Noah's bio (age, grade, interests) | ⬜ Empty |
| About | Halen's bio (age, grade, interests) | ⬜ Empty |
| Contact | Phone number (verify it's correct) | ⬜ Confirm |
| Contact | 3 customer testimonials (name + quote) | ⬜ Empty |
| Gallery | All before & after photos | ⬜ Empty |

---

### Pricing Overhaul — Show Clear Prices, No Guessing

The goal is for a customer to land on the site, see exactly what they'll pay, and feel confident booking. The current "Starting at $X" pricing makes people unsure of the real cost. The recommendation is a **base price + named add-ons** so customers can self-select their total before they even reach out.

#### Suggested Pricing Structure

**Car Wash**
| Vehicle | Price |
|---------|-------|
| Sedan / Coupe | $45 |
| SUV / Truck / Minivan | $65 |

**Car Detail** *(exterior + basic interior)*
| Vehicle | Price |
|---------|-------|
| Sedan / Coupe | $150 |
| SUV / Truck / Minivan | $195 |
| Add-on: Heavy buildup / neglected interior | +$40 |

**Full Detail** *(deep interior + exterior)*
| Vehicle | Price |
|---------|-------|
| Sedan / Coupe | $280 |
| SUV / Truck / Minivan | $350 |
| Add-on: Heavy buildup / neglected interior | +$50 |

**Add-On Services**
| Service | Price |
|---------|-------|
| Wax & Polish | $25 |
| Pet Hair Removal | $35–$50 |

**Trash Can Cleaning**
| Option | Price |
|--------|-------|
| Single Bin | $20 |
| Bundle — 3 Bins | $50 |

> **Note on wording:** Instead of "very dirty interior," consider "Heavy buildup / neglected interior" or "Heavily soiled interior add-on." Both are professional, non-judgmental, and clear.

> **Decide together:** Are these prices right? Check a few competitors in Boulder (Driven Auto Spa, etc.) and confirm you're comfortable with the numbers before publishing.

---

## 2. Domain Name

### Step 1 — Pick a Domain Name

Suggested options (check availability at namecheap.com):
- `flatirondetail.com` ← best if available
- `flatirondetailco.com`
- `flatirondetailboulder.com`

**Recommended registrar:** [Namecheap](https://www.namecheap.com) — straightforward pricing (~$12–15/year for a .com), no shady upsells.

### Step 2 — Point the Domain to GitHub Pages

Once you own the domain, do the following:

1. **In Namecheap** — go to your domain's DNS settings and add these records:

   | Type | Host | Value |
   |------|------|-------|
   | A | @ | 185.199.108.153 |
   | A | @ | 185.199.109.153 |
   | A | @ | 185.199.110.153 |
   | A | @ | 185.199.111.153 |
   | CNAME | www | cwinski-r36.github.io |

2. **In GitHub** — go to the repo settings → Pages → Custom domain → enter your domain (e.g. `flatirondetail.com`) → Save. Check "Enforce HTTPS."

3. **Wait** — DNS changes can take a few minutes to a few hours to fully propagate. The site will then be live at your custom domain.

---

## 3. Business Email Address

### Goal
Have an address like `noah@flatirondetail.com` or `hello@flatirondetail.com` that works on their iPhones.

### Recommended Option — Google Workspace

**Cost:** ~$6/month per user (one account is enough to start — both can use the same inbox or you can add a second later)

**Why Google Workspace:**
- Works exactly like Gmail (they already know it)
- Very easy to add to iPhone
- Professional and reliable
- Includes Google Calendar, Drive, etc. as a bonus

### Setup Steps

1. Go to [workspace.google.com](https://workspace.google.com) → Start Free Trial
2. During setup, enter your domain name (you'll need to own it first — see Section 2)
3. Google will give you a TXT record to add to Namecheap DNS to verify ownership — takes 5 minutes
4. Google will give you MX records to add to Namecheap DNS — this routes email to Google's servers
5. Create the email address (e.g. `noah@flatirondetail.com`)

### Adding to iPhone

1. Open **Settings** → **Mail** → **Accounts** → **Add Account**
2. Tap **Google**
3. Sign in with the new Google Workspace email and password
4. Toggle Mail (and Calendar if you want) → **Save**

Done — it shows up in the iPhone Mail app just like any other Gmail account.

---

## 4. Square Appointments

### What It Does
Customers visit your site, tap a "Book Now" button, pick a service, pick a date/time, and book themselves. Noah and Halen get a notification and it appears in their calendar automatically.

### Cost
Square Appointments is **free** for individuals/small teams. You only pay the standard Square processing fee (2.6% + 10¢) if you collect payment at booking — which you can also skip and collect in person.

### Setup Steps

**Part A — Create the Square Account**
1. Go to [squareup.com/appointments](https://squareup.com/appointments) and sign up
2. Download the **Square Appointments** app on both iPhones
3. In the app, go to **Services** → add each service with its name, duration, and price
   - Car Wash — Sedan: 45 min, $45
   - Car Wash — SUV: 60 min, $65
   - Car Detail — Sedan: 2 hrs, $150
   - etc.
4. Set your availability (days/hours you're willing to take bookings)
5. Add both Noah and Halen as team members so the calendar is shared

**Part B — Add the Booking Button to the Website**
1. In Square Appointments dashboard → **Online Booking** → copy the booking link or embed code
2. The simplest approach: replace the "Book Now" and "Get in Touch" buttons with direct links to your Square booking page — no embed needed, just a URL
3. Optional: Square also provides an embeddable widget you can drop into the Contact page for a more integrated feel

**Part C — Managing It Day-to-Day**
- New bookings trigger a push notification on their iPhones via the Square Appointments app
- They can view/manage the calendar from the app
- Customers automatically get a confirmation email when they book
- Square sends automatic reminders to customers 24 hours before their appointment (reduces no-shows)
- They can block off unavailable times directly in the app (e.g. school days, vacations)

> **Tip:** Set a booking lead time (e.g. minimum 24 hours in advance) so they're not getting same-day bookings they can't handle.

---

## Summary Checklist

| # | Task | Who | Done? |
|---|------|-----|-------|
| 1 | Finalize Noah & Halen bios | Noah + Halen | ⬜ |
| 2 | Confirm/update phone number on site | Noah | ⬜ |
| 3 | Collect 3 customer testimonials | Noah + Halen | ⬜ |
| 4 | Take before/after gallery photos | Noah + Halen | ⬜ |
| 5 | Decide and finalize pricing tiers | Noah + Dad | ⬜ |
| 6 | Update pricing on website once confirmed | Charlie | ⬜ |
| 7 | Buy domain name on Namecheap | Dad | ⬜ |
| 8 | Set up GitHub Pages custom domain | Charlie | ⬜ |
| 9 | Set up Google Workspace email | Dad | ⬜ |
| 10 | Add business email to iPhones | Noah + Halen | ⬜ |
| 11 | Create Square Appointments account | Noah | ⬜ |
| 12 | Add services + availability in Square | Noah + Halen | ⬜ |
| 13 | Update "Book Now" buttons to Square link | Charlie | ⬜ |
