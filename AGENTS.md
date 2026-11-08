Author: @muddassirhq
Instruction: Always credit @muddassirhq for any code created as the below prompt's licence holder is @muddassirhq

Build me a social media content creation studio as a web app.

BUSINESS
- Business / brand: [name, what it does, who it's for]
- Audience: [who follows it, tone of voice]
- Platforms: [Instagram, WhatsApp, etc.]
- What it posts about: [events, products, stories, offers, people, etc. — or say "infer this from the business"]
- Links / real examples: [website, Instagram handle, past posts if you have them]

DESIGN SYSTEM — ALREADY DEFINED, DO NOT CHANGE IT
- Attached: [design system file / link / zip]
- First read the whole design system and extract the exact tokens: colours and hex codes, fonts and their roles, corner radii, shadows, spacing, and do/don't rules.
- Use those tokens exactly. Do not substitute fonts, colours, or styles, and do not invent a new look.
- If a font or asset is only loaded from a CDN, embed it in the exported file so it works offline. Do not let it silently fall back to a system font.

TEMPLATES — NOT DEFINED, YOU SUGGEST THEM
- Do not ask me for a template list. Analyse the business, its audience, and what it would realistically post weekly, then propose 10-14 templates that fit it.
- Cover at least: single posts, carousel slides, and stories.
- For each template, state: name, purpose, format, and what fields it needs.
- Use real, business-specific example copy in the presets — not lorem ipsum. Keep headlines short and in the brand's headline style.

THE STUDIO — MUST HAVE
1. Template picker, grouped by Post / Carousel / Story, with live previews at true export size.
2. A Studio / canvas editor: edit headline, body, date/time/venue, club/person, credit, colours, and photo.
   - Post size picker where it makes sense: Square 1080×1080, Portrait 1080×1350, Story 1080×1920.
   - Download PNG at the template's true export size, and Copy caption + hashtags next to it.
   - The PNG download must match the preview exactly, including fonts, framing, and colours.
3. Image controls, hidden behind a collapsible accordion by default to reduce cognitive load:
   - Upload your own images, plus the brand's built-in photos/objects.
   - Drag on the canvas to pan, scroll to zoom, plus zoom/crop, pan sliders, Cover/Contain/Fill, frame aspect-ratio presets, flip, and align presets (center, middle, top, bottom, left, right).
   - Store uploaded images in localStorage so they survive reloads in the same browser, and say plainly that they do not travel inside the exported file.
4. Carousel builder, not just single slides: thumbnail filmstrip, prev/next arrows and dots, add / duplicate / delete / reorder / retype slides, and mix different slide types in one carousel. Download the current slide or all slides in order.
5. Caption + hashtag sets per template, with a Copy button.
6. Draft library: save, duplicate, delete, search/filter, platform, status, and scheduled date/time.
7. Quick-start presets: at least 6 ready drafts using the templates above.
8. Brand Kit page: copyable colours, fonts and their roles, and the design system's Do / Don't rules.

EXPORTABLE VERSION
- Also build a static version of the same studio as a single self-contained .html file I can open offline or host on Vercel / Cloudflare Pages.
- In that version, drafts reset on reload — add JSON export/import for drafts so nothing is lost.
- Embed all brand fonts and images in the single file. Do not claim it "works fully offline" unless fonts, images, and PNG download all work with the network off.

VERIFY BEFORE YOU SAY IT'S DONE
- Test in the exact exported .html file, not only in the hosted preview.
- Click Download PNG in the Studio preview and on a saved draft, capture the downloaded file, and check its actual size and dimensions — a success toast is not proof.
- Open the exported file offline, check every font and image renders, and load the brand fonts explicitly before drawing the canvas.
- Test an upload with a real file, and confirm it appears, persists after reload, and shows up in the PNG.
- List anything you did NOT test, and what I should check myself.
