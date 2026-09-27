# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Hiring managers and recruiters filling full-time Instructional Designer, E-learning Developer and Multimedia Designer roles (confirmed primary audience). They arrive from a CV, LinkedIn or a job application link, usually skim within a minute, open one or two projects, and either download the CV or copy the contact details.

## Product Purpose

The personal portfolio of Prince Jashmar M. Mosqueda. It exists to get Prince shortlisted: show real e-learning, UI, static-ad and illustration work at full fidelity, make the CV one click away, and make contacting him effortless. Success means a recruiter opens the work, sees the craft, and downloads the CV or reaches out.

## Positioning

Prince presents first as a graphic and multimedia designer (adverts, characters, interfaces, brand visuals) who also brings instructional design: when the goal is learning, he builds the whole course in Storyline/Rise and draws its screens, characters and UI kits himself. The owner asked that the site not read as limited to instructional design. Hero tagline: "Ideas, Drawn to Be Understood." (title case, with "Understood" highlighted in the lime accent at 60%); the hero description stays in the owner's instructional-design-first wording.

## Operating Context

- Single static page (`index.html`, inline CSS and JS, no build step), deployed from the `My-Portfolio` GitHub repo (Vercel is in the listed toolkit).
- All project images, the profile photo and the Open Graph image are served from the separate `Jashmare/Portfolio-Storage` repo via `raw.githubusercontent.com`. Prince adds work by uploading to that repo and adding an entry to the page's project data.
- CV PDF lives at `Jashmare/My-Curriculum-Vitae` (`Prince Mosqueda CV.pdf`).
- Toolkit icons live in `My-Portfolio/icons/`.

## Capabilities and Constraints

- Must keep: project gallery modal with thumbnails and keyboard navigation, fullscreen image viewer, interaction animations on buttons, light and dark theme, CV download, copy-to-clipboard for email and phone, LinkedIn and Instagram links.
- Unfinished projects ("Logos and Branding" / Tsuki bunny, "Coming Soon") stay in the data but are hidden until ready.
- Toolkit keeps every current tool, grouped by purpose (design, e-learning authoring, audio, build and AI, workflow and collaboration).
- No image converter on the build machine; assets ship in their stored formats.

## Brand Commitments

- Name: Prince Jashmar M. Mosqueda (short form "Prince Mosqueda").
- Roles as he states them: Instructional Designer, Multimedia Designer, Graphic Illustrator, E-Learning Developer.
- The About section's personal voice ("There is a life behind all that work." Curiosity / Family / Still Becoming) is his own writing and stays.

## Evidence on Hand

- E-learning module screens: Cotton yarn / "Unravelling the Textile Chain" (Cotton_01-04), Takaful & Re-Takaful certification (BlueDesign_*), CyanDesign_01a-c.
- Static advert designs: StaticDesign_01_A, 02, 03, 04.
- E-learning UI kits / templates: UI_Tempalte_A/B, UI_Design_01/02.
- Illustration: owl mascot (Full view.jpg), Character Poses 01-05.png.
- Profile cutout photo: Profile Cropped PNG.png.
- No testimonials, client logos, metrics or module counts. The "100+ modules delivered" stat was removed at the owner's request; do not invent numbers.

## Product Principles

1. The work leads. Screens are shown large and legibly; the site's chrome never competes with them.
2. A recruiter should reach the work, the CV and the contact details within seconds, on any device.
3. Only true claims. Proof is the work itself, not adjectives or numbers.
4. Adding a new project should stay a one-entry edit.

## Accessibility & Inclusion

WCAG 2.2 AA: keyboard-operable gallery and fullscreen viewer, visible focus, text contrast at least 4.5:1, and reduced-motion support for all animation.
