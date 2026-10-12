# SPEC: Functional Fitness website (Phase 1)

Fictional client for the whole course. All business details are invented placeholders.

## 1. Who it is for

- Middle-aged adults living in central Santiago, Chile.
- Language of the site: **Spanish (Chile)**.
- What they want, in order: (1) lose weight, (2) gain lean muscle, (3) follow a clear plan instead of random workouts.
- Why group classes: structure, control and motivation, not just equipment to use alone.

## 2. Goal of the site

One main action for every visitor: **book a free trial class**.
In Phase 1 the button leads to a placeholder (a contact section). The real booking form comes in Phase 2.

## 3. Brand

- Name: **Functional Fitness**
- Feel: friendly and simple
- Colors:
  - Background: warm off-white `#FAF7F2`
  - Main: deep teal `#1F6F6B`
  - Action button: warm orange `#E8833A`
  - Text: charcoal `#2B2B2B`
- Photos: supplied by the owner (Alexander) in `images/` (stock photos allowed). Every image needs a text description (alt text).

## 4. Pages and content

### Page 1: Home (`index.html`)
- Header with the name and a menu: Inicio, Clases.
- Hero: headline about losing weight, building lean muscle and following a clear plan; button "Reserva tu clase de prueba gratis".
- How it works: 3 short steps (evaluation, personal plan, group classes).
- Trainers: 3 invented trainers (name, short bio).
- Prices: 3 invented plans.
- Contact: invented address in central Santiago, hours, WhatsApp placeholder.
- Footer.

### Page 2: Classes (`clases.html`)
- Same header and footer.
- Weekly schedule (Monday to Saturday), written directly in the page.
- Same "book a free trial" button.

## 5. Files

```
functional-fitness/
├── SPEC.md
├── index.html
├── clases.html
├── css/style.css
└── images/            (photos go here)
```

## 6. Out of scope (do NOT build now)

- Booking form that saves data (Phase 2)
- Database, server, any back end (Phase 2)
- Admin panel / tool to edit the schedule, login (Phase 3)
- Telegram or WhatsApp bots (Phases 5 and 7)
- Payments, online sign-up, user accounts

To change the schedule in Phase 1, the owner asks the AI to edit `clases.html`.

## 7. End-to-end check (done when)

- [ ] Both pages open from a browser, and the menu links go between them.
- [ ] The "book a free trial" button appears on both pages and points somewhere sensible.
- [ ] The page is readable on a phone-sized window.
- [ ] No text in English except the brand name.
- [ ] Every image has alt text.
- [ ] Owner has read the AI's result and found at least one thing to fix.
