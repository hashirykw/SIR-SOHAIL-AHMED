# Sir Sohail Ahmed · Business website

A multi-page website for Sir Sohail Ahmed: O Level, IGCSE and A Level Business, Karachi. Every page is one self-contained HTML file, and every file sits in one flat folder, with no asset sub-folders.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: annual-report cover hero with live candlestick strip, key figures, the pinned "mark ladder" (how an answer climbs AO1→AO4 on an example case), course covers, live break-even studio, the syllabus as a company org chart, command-word rail, study tools, campuses |
| `courses.html` | O Level 7081 (replaces 7115), AS & A Level 9609, IGCSE 0264 (replaces 0450): papers, weightings, assessment objectives, what changes in 2027 |
| `syllabus.html` | Every topic, unit by unit, for 7081, 0264 and 9609, with key points, key terms, formulas and a progress tracker |
| `past-papers.html` | 7115, 0450 and 9609 question papers + mark schemes, attempt tracker with scores, exam timer and focus mode |
| `lab.html` | Business Lab: break-even with what-ifs, ratio analysis, 6-month cash-flow forecast, investment appraisal (payback, ARR, NPV), key-term flashcards and quiz |
| `notes.html` | Notes store with cart and WhatsApp checkout |
| `about.html` | About Sir Sohail and where he teaches |
| `contact.html` | Enrolment form that opens WhatsApp, contacts, FAQ |
| `404.html` | Not-found page |
| `sohail-ahmed.webp` | Portrait cutout (transparent background) |
| `sohail-ahmed.jpg` | Share image for WhatsApp and social previews (1200×630) |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

## Check these before going live

1. **WhatsApp number.** The site uses 0312 826 2570 (+92 312 8262570), with 0333 262 2283 as the second number. Both were taken from public search results for Sir Sohail Ahmed. Confirm them with him. To change one, find and replace `923128262570` across the folder; the display text is `0312 826 2570`.
2. **Figures.**
   - "20+ years" comes from his Facebook post ("teaching Business Studies O & A Levels since past 20 plus years").
   - "500+ A* students" and "Cambridge certified" come from his Cambridge Online faculty profile.
   - Confirm all three with him.
3. **Notes prices and titles** are demo values. Search for `PRODUCTS` in any page.
4. **Campuses.** SWK Gulshan, Credo College and SMAF Horizon Online Academy are taken from public listings.
5. **Social links.** The links are instagram.com/bizbysohail and facebook.com/Bizbysohail.
6. **Domain.** `sitemap.xml`, `robots.txt` and each page's `<head>` use `https://sirsohailahmed.vercel.app`. Change these if you use another domain.

Each page carries its own copy of the shared code, so a change like the phone number must be made in every HTML file. A find-and-replace across the folder does it in one go.

## Notes on content

- The "Chai Corner" case on the home page and the Lab presets are clearly labelled examples, not real businesses.
- Key-term definitions are standard textbook wording, not quoted from Cambridge.
- Past papers open from PapaCambridge's public archive. Years are limited to the current paper format (7115 and 0450 from 2020, 9609 from 2023), so the durations and marks shown are right for every listed year. 7081 and 0264 are first examined in 2027, so they have no past papers yet.
- Progress (tracker, ticked topics, known key terms, cart, theme, sound) is saved in the visitor's own browser only.

## Deploy

- **Vercel:** drag the folder into vercel.com/new, or run `vercel` inside it. `vercel.json` gives clean URLs (`/lab` instead of `/lab.html`).
- **Netlify / GitHub Pages / any host:** upload the folder as is. There is no build step.

## Sources

- Cambridge O Level Business 7081 syllabus 2027–2029: https://www.cambridgeinternational.org/Images/718211-2027-2029-syllabus.pdf
- Cambridge O Level Business Studies 7115 syllabus 2026: https://www.cambridgeinternational.org/Images/697338-2026-syllabus.pdf
- Cambridge IGCSE Business 0264 syllabus 2027–2029: https://www.cambridgeinternational.org/Images/718123-2027-2029-syllabus.pdf
- Cambridge International AS & A Level Business 9609 syllabus 2026–2028: https://www.cambridgeinternational.org/Images/697371-2026-2028-syllabus.pdf
