# GOMZI Landing Page – Developer Notes

## Files
- `index.html` – complete responsive page (HTML + inline CSS, no JavaScript needed)
- `images/` – all images used on the page

Open `index.html` in a browser to preview. Fonts load from Google Fonts (Bebas Neue, Poppins).

## Brand
- Black `#141414`, Brown `#5A2D1A`, Light grey `#F4F4F2`, Border `#E6E6E3`, White `#FFFFFF`
- Headings: Bebas Neue. Body: Poppins 400/500/600.

## Sections (in order)
1. Header – logo, menu (Offer, Packs, Prices, Visit us), WhatsApp button
2. Hero – "Buy supplements. Get the gym free."
3. Offer – 3 rules
4. Price promise – "Bhai, GOMZI ki taraf se."
5. Transformation Packs – Fat Loss ₹8,500, Muscle Building ₹11,500
6. Price list
7. Member photos
8. Visit us – 3 branches + final CTA
9. Footer – address + terms

## Offer rules (for cart / checkout logic)
- Bill ≥ ₹999 → 1 month gym pass (one per bill)
- Each 1kg Whey (Blend / Concentrate / Isolate) → ATP Creatine 250g free
- Each 2kg Whey (Blend / Concentrate / Isolate) → BCAA 250g free
- Free Creatine/BCAA does NOT apply to whey inside packs
- Packs include: gym 1 month, personal trainer 1 month, dietitian + diet plan, blood test, full body analysis
- Gym pass activated within 15 days; pack services booked within 30 days
- Diwali Launch Bonus: free shaker + 15 extra gym days on packs, till 30 Nov 2026

## Links
- All WhatsApp buttons: https://wa.me/919875270200?text=Hi%20GOMZI%2C%20I%20want%20the%20free%20gym%20offer

## To complete before going live
- Replace "[Full address]" for Vesu, Katargam and Adajan (add Google Maps links)
- Optional: add crossed-out prices for gym / trainer / dietitian / tests once fees are confirmed
- Add Meta Pixel and Google Analytics if required
- Confirm customers in member photos have given permission
