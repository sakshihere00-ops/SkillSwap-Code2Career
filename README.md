# SkillSwap — Code2Career

Creator gig marketplace implementing the five required SkillSwap features.

## Features
1. Post a gig — title, category, rate, description and creator.
2. Browse & search — searchable marketplace with category filters.
3. Book a gig — booking form and confirmation/toast.
4. Creator dashboard — incoming requests with Accept / Decline.
5. My bookings — client bookings with Pending, Accepted or Declined.

## Decision Points
- **DP1 — Rejection:** A declined booking remains visible to the client with a Declined status, while the client can return to the marketplace and book another creator. This preserves transparency and avoids making a request disappear.
- **DP2 — Double booking:** A gig can receive multiple booking requests while one is Pending. The creator controls which requests to accept or decline, which keeps the marketplace open to competing client requests without automatically committing the creator.
- **DP3 — Discovery:** Gigs are ranked newest-first. This gives newly listed creators a predictable chance to be discovered and makes the marketplace feel fresh without favoring price.

## Tech
- HTML
- CSS
- Vanilla JavaScript
- Browser localStorage for prototype persistence
- No authentication, as required by the brief

## Run
Open `index.html` in a browser, or serve the folder with any static web server.

## Hackathon ID
**REPLACE_WITH_YOUR_HACKATHON_ID**

## Standard API
Not implemented; this version uses a browser-driven UI with localStorage.
