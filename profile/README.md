<h1 align="center">HandyMan</h1>

<p align="center">
  A marketplace for work around the home.<br />
  Describe the job, compare priced offers from local professionals, hire with confidence.
</p>

<p align="center">
  <a href="https://get-handyman.com"><strong>get-handyman.com</strong></a> ·
  <a href="https://apps.apple.com/app/id6796590581">App Store</a> ·
  <a href="https://play.google.com/store/apps/details?id=com.gethandyman.app">Google Play</a> ·
  <a href="https://www.linkedin.com/company/gethandyman/">LinkedIn</a> ·
  <a href="https://www.trustpilot.com/review/get-handyman.com">Trustpilot</a> ·
  <a href="https://www.facebook.com/profile.php?id=61593633797048">Facebook</a>
</p>

---

## What it is

A leaking mixer. A socket that stopped working. A flat-pack wardrobe still in its
box. An end-of-tenancy clean with a deadline attached.

HandyMan puts the people who need that work done and the people who do it for a
living in the same place. You describe the job, add photos, set a budget if you
have one. Professionals who are free send offers **with their price attached**.
You compare profiles, past work and reviews, choose one, and the whole job stays
in a single conversation from request to review.

## For people who need work done

- **No calling round for quotes.** Offers arrive with a number on them.
- **Something to judge by.** Every profile shows past work and reviews from
  clients who actually hired that professional.
- **Nothing is booked until you choose.** Posting a request commits you to
  nothing.

## For professionals

- **Joining is free**, and so is seeing what is being asked for in your city.
- **You set your own rate** and quote only for the work you want.
- **A verified badge** once identity documents have been checked.

## Trust, and its limits

Reviews can only be left by a client who hired that professional *through the
platform*, so a profile cannot be padded with reviews from friends. Accounts are
protected by row-level access rules in the database, and every connection is
encrypted.

Some trades are regulated, and no marketplace badge replaces a licence. Our
[guides](https://get-handyman.com/guides/) say plainly which jobs need a
licensed trade — a DEWA-approved contractor for electrical and water work in
Dubai, a licensed contractor once a US job crosses the state's threshold — and
we would rather point you at the register than take the booking.

## Where we work

Two countries, opening city by city rather than everywhere at once —
**30 cities**:

| | |
| --- | --- |
| **United Arab Emirates** | All seven emirates: Dubai, Abu Dhabi, Sharjah, Ajman, Ras Al Khaimah, Fujairah, Umm Al Quwain |
| **United States** | 23 metros, from New York and Los Angeles to Minneapolis and Nashville |

That is the whole of it. The cities above are where professionals are being
signed up first — see [where we are hiring](https://get-handyman.com/jobs/).

## How it is built

| | |
| --- | --- |
| **Web** | Vite multi-page application, Tailwind, served from Cloudflare Workers |
| **Data & auth** | Supabase, with row-level security policies |
| **Mobile** | Native iOS and Android apps; one account across web and mobile |
| **Content** | 30 city pages, 50 price guides and 4 hiring guides generated at build time, 11 interface languages, four of them with their own indexed URLs |
| **Discovery** | Structured data, hreflang, a hand-maintained sitemap, IndexNow on deploy |
| **Quality** | ~950 unit tests and a Playwright end-to-end suite; CI gates every deploy |

## Contact

[feedback@get-handyman.com](mailto:feedback@get-handyman.com) — questions,
problems, press or partnership ideas. We read everything.
