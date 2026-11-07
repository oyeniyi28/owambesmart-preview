# OwambeSmart — Frontend Prototype (Stage 1)

This is the **working browser prototype** for OwambeSmart, a Nigerian event-budgeting and vendor-discovery platform. It includes the previously approved green-and-ivory editorial styling and a ₦7,000,000 example event budget.

## How to open it (no coding knowledge needed)

1. Extract the ZIP file to a folder on your computer.
2. Double-click `index.html` in that folder.
3. Use the top navigation and **Plan my event** button to explore the screens.

You do **not** need Node.js, an IDE, hosting, or an internet connection to view this prototype.

## Design and budget behaviour

The homepage keeps the previously approved compact seven-category summary and the ₦7 million illustration. The detailed 19-line breakdown is shown **only** after opening **Budgets** or clicking **View sample budget**. The example allocations total 100%, with event coordination set to 8%. Conditional services (Gele artist and Alaga) are clearly identified. These are proposed demonstration percentages, not verified prices.

## Screens included

- Home: Nigerian celebration hero, how it works, vendor categories, ₦7m sample, referrals, image gallery.
- Signup and login screen **designs**, with safety notices; no real authentication.
- User dashboard with sample data.
- Event creation form: occasion, date, location, guests and Naira budget.
- Sample budget overview with the detailed wedding allocation (food, snacks, drinks, individual entertainment and photo/video services, outfits, security, cake, stylists, Alaga and other costs). Event coordination is fixed at 8%. The homepage stays intentionally concise with seven summary groups.
- Vendor directory **mock listings**, clearly marked as examples.
- Wallet view: 25 suggested welcome coins, 10 for budget creation, 15 for premium recommendations.
- Referral view: proposed 10-coin referrer and 5-coin invitee rewards.
- Vendor portal concept.
- Mobile-friendly layout and navigation.

## Important limitations

**Frontend only** — the prototype has no backend, authentication, database, live vendor integration, payments, or functional coin transactions. Signup/login forms are cosmetic: **do not enter real passwords**. Vendor listings are fictional placeholders, not verified suppliers. It does not send data to a remote service.

The event form only saves its current details temporarily in browser `sessionStorage` where available; it is not a secure storage system. Sample budget categories and percentages are for demonstrating the screen, **not real current Lagos vendor quotations**. All displayed photos are illustrative concept imagery.

## Files

```
index.html       Entry point — open this file
styles.css       Layout, typography, colors, responsiveness
app.js           Frontend routes, UI, demo form and sample budget
assets/          Local offline images used by the screens
```

## Next build stage

After the visual design is approved, we can set up GitHub and the hosted preview, then create real signup/login with Supabase and connect a secure backend and event-budget calculation system. Coins, referrals and vendor APIs follow once that foundation is in place.

_OwambeSmart — Stage 1 preview. Not a production system._
