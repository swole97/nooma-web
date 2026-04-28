# Nooma — Design & Product Brief

*The cutest way to remember your meds.*

---

## 1. The Product in One Paragraph

Nooma is a medication reminder app for women aged 22–35. The core mechanic is a small ghost-like companion who lives on your phone. Take your meds and she's there — having tea, reading the paper, watching the rain. Skip a day and she's still there, no streaks broken, no guilt. Over time you build a small sanctuary together. Reminders, snooze, refills, and unlimited medications are free forever; cosmetics and seasonal scenes are paid.

The wedge: every other med app feels like a productivity tool with red alerts and broken streaks. Nooma feels like a small companion you actually want to open.

---

## 2. Audience

### Mia, 28
- Marketing or design role, urban
- On an SSRI, the pill, possibly ADHD meds
- Heavy TikTok user, design-aware, cottagecore-adjacent
- Forgets her morning pill half the time
- Acquisition target — the influencer-driven download

### Hannah, 33
- Chronic illness (endometriosis, Crohn's, thyroid, similar)
- 4+ daily medications
- Tired of being optimized; suspicious of wellness culture
- "Spoonie" community member or adjacent
- Retention and subscription target — the loyal long-term user

### What both share
- They take medication daily; this is just life, not a wellness goal
- They're worn down by other med apps that yell, shame, or break streaks
- They want a tool that respects their dignity
- They are not looking for self-care content; they want to remember a pill

---

## 3. Brand

### Name
**Nooma** — six characters, soft phonetics, globally pronounceable, no harsh consonants. Made-up word in this category — no medical / pill / dose suffix. Sounds like "noo-mah". Not the character's name.

### URL
**nooma.care** — the URL is the tagline. *Nooma. Cares.*

### Tagline
**Never forget your meds again.**

### Sub-tagline (longer form)
*Nooma is the medication reminder that doesn't feel like one. Soft notifications, refill alerts, and a tiny companion who lives on your phone — gently making sure you take care of yourself.*

### Brand voice
- Warm, gentle, slightly cottagecore
- Plant Nanny–adjacent: friendly, simple, slightly cheesy in places
- **Problem-led benefits** — name what the user is experiencing, then explain how Nooma solves it
- **Show, don't tell** — describe what the character is doing, never what the brand is "trying to be"
- Never defensive — never lead with "no streaks" or "no shame" because that activates the very frame we want to avoid

### What we never say
- "Self-care app" — wellness-coded, exhausted vocabulary
- "Wellness journey" — same
- "Track your habits" — too productivity-coded
- "Build a streak" — opposite of brand
- "Don't break your streak" — opposite of brand
- "You can do this!" — patronizing

### Tone references
- Plant Nanny (Sparkful) — for warmth, simplicity, friendly cheesiness
- Glossier — for the brand discipline (one colour, owned hard)
- Notion — for the confident, slightly understated presentation
- NOT Calm, NOT Headspace — those are wellness-coded; Nooma is medical-utility-coded with charm

---

## 4. Visual Identity (LOCKED)

### Colour System

**One signature, one neutral, one ink. Two minor accents only inside illustrations.**

| Variable | Hex | Use |
|---|---|---|
| `--nooma` | `#C9453B` | The signature brand colour. Section backgrounds (used twice on the page), CTAs, brand mark, italic emphasis on cream sections. |
| `--nooma-deep` | `#A8362E` | Hover state for Nooma red. Tie knot detail. |
| `--cream` | `#FAF4ED` | Neutral. Dominant background colour. |
| `--cream-warm` | `#F5EBDC` | Soft secondary cream for testimonial avatars and accents. |
| `--ink` | `#2A1F1F` | All body text. Footer background. |
| `--ink-soft` | `#6B5757` | Secondary text and meta. |
| `--ink-faded` | `#A89A95` | Tertiary text and FAQ icons. |
| `--gold` | `#D8A845` | Italic emphasis on red sections. Star ratings. Sparkle highlights. **Tiny doses only.** |

**Auxiliary colours that exist only inside illustrations** (sanctuary scenes, character cheeks, sparkles):
- Sky/sun gradients in phone mockups
- Sage `#7FAA52` only in sanctuary ground
- Pink cheek blush `#FFB5B0` only on character
- Yellow aura `#FFE89A` only around character

These never appear as section backgrounds. They are evidence of the brand world but not the brand colour.

### Colour Discipline Rules

1. **Signature colour rule**: Nooma red `#C9453B` is THE brand colour. It must appear in the logo, all primary CTAs, and at least two full-section moments per page.
2. **Section backgrounds**: cream OR Nooma red OR ink. Never anything else. Never gradients.
3. **No gradients on section backgrounds.** Gradients are only allowed inside illustrations (sky, sun glow, ground) where they represent real visual phenomena.
4. **Ratio target**: ~70% cream, ~25% Nooma red, ~5% ink/other.
5. **Accents stay accent-sized** — gold appears only on italic emphasis or stars. Sage appears only in sanctuary illustrations.

### Typography

- **Display & headers**: [Fraunces](https://fonts.google.com/specimen/Fraunces) — variable serif, used at weight 500, italic for emphasis. Loaded from Google Fonts.
- **Body**: [Instrument Sans](https://fonts.google.com/specimen/Instrument+Sans) — clean modern sans. Weights 400/500/600/700.
- **Letter spacing**: tight headers (`-0.02em` to `-0.025em`), wider eyebrows (`0.18em` to `0.2em`)
- **Italic emphasis** — used in section titles to highlight one phrase per heading. Always in Nooma red on cream backgrounds, always in gold on red backgrounds.

### Logo

The wordmark is "nooma" in lowercase Fraunces italic, weight 500, letter-spacing -0.015em. Paired with the character's face icon (small ghost head with eyes and smile, 28px square).

The character icon stays cream-bodied with ink outlines and pink cheeks. Small enough that the red tie is implied rather than visible at logo scale.

---

## 5. Character (LOCKED)

### Visual specification
A small cel-shaded ghost with a red necktie:
- Body: three tones — dark base `#E8DCB8`, cream mid `#FFF8E8`, white highlight `#FFFEF8`
- Outline: 5px deep warm brown-black `#1F1610` (never pure black)
- Eyes: large dot eyes `#1F1610` with small white crescent highlights upper-right
- Cheeks: soft pink ovals `#FFB5B0`
- Freckles: three tiny `#D89890` dots under each eye
- Specular streak: cream highlight on upper body
- Mouth: small smile curve (NOT open oval)
- Bottom: wavy ghost silhouette
- Aura: soft yellow glow `#FFE4A8`
- Tie: knot `#A8362E`, body `#C9453B` (these match the brand colour exactly)

### Naming convention
**The character is unnamed in marketing copy.** Users name their own when they first open the app. Marketing always refers to her generically:
- "your little one"
- "a tiny companion"
- "your companion"
- "she" / "her" (lowercase pronoun)

The internal codename for design files is "Pippi" but this name appears nowhere in the user-facing brand.

### Idle animation system (six layers, never synced)
| Layer | Duration | Notes |
|---|---|---|
| Breathe + bob | 3.8s | Vertical floating motion |
| Side sway | 5.2s | Gentle rotation, transform-origin: center bottom |
| Blink | 5.5s base, randomised | Eyes close briefly every few seconds |
| Look around | 8s | Pupils drift gently |
| Tie sway | 4.4s | Tie rotates around knot |
| Cheek pulse | 4s | Opacity 0.7 → 0.85 → 0.7 |

In React: each layer is a separate `motion.g` or `motion.div` with its own animate prop. In CSS: each layer is a separate keyframe with its own duration.

### Interactive behaviours (web only)
- **Eyes follow cursor**: pupils track mouse position, capped at ~4px offset from center so they never slide off the eye whites
- **Click reaction**: character does a small bounce + wobble + brief reaction message ("she likes you" / "✨ a little hello ✨" / etc.)
- **Time of day**: hero gradient and phone mockups display morning/midday/evening/night based on `new Date().getHours()`

### Costume system
- **Default**: red tie
- **Plus tier**: gold crown + stardust purple tie (lavender + gold dots)
- **Future hats/scenes**: monthly seasonal drops, all paid

---

## 6. Component Patterns

### Buttons

**Primary CTA (download buttons, nav download, price card CTAs)**
- Background: `--nooma`
- Text: `--cream`
- Border: 1.5px solid `--nooma`
- Border radius: 14px
- Padding: 12px 20px
- Hover: background shifts to `--nooma-deep`, lifts -2px with red glow shadow
- App Store / Google Play badges follow the same treatment with platform icons

**Secondary CTA (nav links)**
- Plain text, opacity 0.7 default, opacity 1 on hover
- Same Instrument Sans 13px / weight 500

### Cards

**Standard card (problem cards, testimonial cards, pricing cards)**
- Background: white or cream
- Border: 1px solid `rgba(42, 31, 31, 0.06)`
- Border radius: 20-24px
- Padding: 24-36px depending on content density
- Subtle shadow on hover (lift -4px)

**Featured card (Plus tier pricing)**
- Background: `--nooma`
- Text: `--cream`
- "Most loved" badge: `--ink` background, `--cream` text, positioned -12px above top-right
- CTA inside: cream background, ink text (reverses the page convention)

### Section structure

Every section follows the same skeleton:
1. **Eyebrow** — 11px uppercase letter-spaced label (e.g., "why people switch to nooma")
2. **Title** — Fraunces 32-50px, weight 500, with one italic phrase emphasized in `--nooma` (or `--gold` on red backgrounds)
3. **Sub** — Fraunces italic 17-20px, `--ink-soft`, max-width 620px
4. **Content** — grid, cards, phones, etc.

Section padding: 100px top and bottom.

### Mini-phone mockup

A 300×620px iPhone-style frame used inside feature blocks:
- Outer body: `#0A0A0A` rounded corners 40px
- Notch: `#000` 95×22px centered top
- Screen: 32px corner radius
- Sky / sun / ground rendered inline as gradients (this is the only place gradients live)
- Topbar: date pill (left), streak pill (right) — but "streak" here means days-in-a-row of *being remembered*, not punishment
- Character: 130px wide, positioned bottom 30%, centered
- Dose card: 80px from bottom, cream surface, dose icon + title + sub
- Bottom nav: Home / Meds / Sanctuary / History tabs

### Spark (decorative twinkle)
- Fraunces italic ✦ character
- Position absolute, opacity animated 0 → 0.85 → 0
- Scale 0.4 → 1 → 0.4, rotate 0 → 360
- 4 second loop, randomized delays
- Used in hero and final CTA only — sparingly, no more than 6 per section

---

## 7. Page Structure (Funnel)

The landing page funnel, top to bottom:

| # | Section | Background | Purpose |
|---|---|---|---|
| 1 | Sticky nav | cream (translucent) | Logo + 3 anchor links + Download CTA |
| 2 | Hero | `--cream` | Headline + sub + CTAs + animated character + 3 stats |
| 3 | Press strip | `--cream` | "As seen in" with publication names |
| 4 | Problem | `--cream` | "Med apps shouldn't shame you" — 3 named pain points |
| 5 | Feature 1: Reminders | `--cream` | "You'll actually take your meds" + evening phone mockup |
| 6 | **Feature 2: No streaks** | **`--nooma`** | "Consistency without the guilt" + morning sanctuary phone with collected items — **first big brand colour moment** |
| 7 | Feature 3: Refills | `--cream` | "Refills before you're down to crumbs" + Plus-tier phone (lavender scene, gold crown) |
| 8 | Testimonials | `--cream` | 9 review cards with stars, handles, locations |
| 9 | Pricing | `--cream` | Free vs Plus £4.99/mo (Plus card is `--nooma`) |
| 10 | FAQ | `--cream` | 6 expandable questions |
| 11 | **Final CTA** | **`--nooma`** | "Stop forgetting. Start smiling." + cream-on-red CTAs — **second big brand colour moment** |
| 12 | Footer | `--ink` | Logo, tagline, 4 columns of links, copyright |

The colour rhythm: cream cream cream cream **RED** cream cream cream cream **RED** ink.

Two confident red moments. Cream everywhere else. Footer grounds the page in deep brown.

---

## 8. Voice & Copy Patterns

### Headline pattern
Lead with the user benefit, not the product feature.

**Right**: "Never forget your meds again."
**Wrong**: "The cutest way to remember your meds." *(Pippi-the-character was the headline; now the user's outcome leads.)*

### Italic emphasis pattern
One phrase per headline, italicized in the brand colour:
- "Never forget your <em>meds</em> again."
- "Med apps shouldn't <em>shame you</em>."
- "You'll actually <em>take your meds</em>."
- "Consistency without the <em>guilt</em>."
- "Refills before <em>you're down to crumbs</em>."
- "People who <em>take their meds now</em>."
- "Free where it <em>matters</em>."
- "The <em>boring stuff</em>."
- "Stop forgetting. <em>Start smiling</em>."

Each emphasizes the most punchy or specific phrase. Never the brand name. Never a verb generic like "love" or "delight".

### Sub-headline pattern
Fraunces italic. One sentence. Amplifies the headline with concrete detail.

**Right**: "Nooma is the medication reminder that doesn't feel like one. Soft notifications, refill alerts, and a tiny companion who lives on your phone — gently making sure you take care of yourself."

### Body copy pattern
- Two paragraphs per feature block, max
- First paragraph: how the feature solves the user's problem
- Second paragraph: what the character does (the charming "show" layer)
- Sentences mostly short, occasional em-dash, occasional list
- Voice is *one specific kind person* — not corporate, not breathless

### Notification copy
- Always uses the user's chosen character name (lowercase, possessive)
- Examples (using "Penelope" as the placeholder):
  - "Penelope's looking for you"
  - "a quick note from Penelope"
  - "Penelope brought you something"
  - "Penelope missed you"
- **Never** says the medication name on the lock screen
- **Never** uses urgent / alarming language ("OVERDUE!", "URGENT", "MISSED")

### Testimonial pattern
Real-feeling user quotes that *demonstrate* the brand without explaining it. Specific moments, not brand-mission monologues.

**Right**: "I named mine Penelope! She's wearing the cutest little scarf this week. I check on her like four times a day 🥺💕"

**Wrong**: "I take my SSRI every morning and forget half the time. The other apps yell at me. Nooma just sits there being cute and I actually remember."
*(That sounds like the founder writing through the user. Real users say what they did and how they felt, not how the app fits the mission.)*

---

## 9. Pricing & Monetization (LOCKED)

### Free tier (forever)
- Unlimited medications
- Smart reminders & snooze
- Refill alerts & tracking
- Default companion look
- Time-of-day variations (character changes through the day)
- Default sanctuary scene

### Nooma Plus — £4.99/month or £49/year (saves 18%)
- Everything in Free
- 40+ hats & accessories
- 12 sanctuary scene packs
- Floating auras (hearts, fireflies, more)
- Monthly seasonal drops
- 7-day free trial

### Cosmetic shop (one-time purchases also available)
- Hats: £0.99
- Outfits: £1.99
- Scene packs: £4.99
- Premium pets / variants: £2.99
- Holiday bundles: £6.99

### What we never charge for
- Reminders, snooze, refill alerts, tracking, multiple medications — all free forever
- We will never paywall the part of the app that helps you remember your meds

### Revenue projections (from earlier analysis)
- ~£217k/year at 100k downloads
- ~£2M/year at 1M downloads
- Both based on a ~5–8% Plus conversion + cosmetic micro-purchases

### What we will never add
- ❌ Watch-an-ad-for-coins (predatory, off-brand)
- ❌ Streaks that break (anti-brand)
- ❌ Points / XP / leveling systems
- ❌ Mini-games gated behind med completion
- ❌ Social features / friend lists / leaderboards
- ❌ Ads of any kind
- ❌ Selling user data
- ❌ Health-data sharing with third parties

---

## 10. Tech Stack (LOCKED)

### Mobile app
- **React Native + Expo** (Expo Router, Expo Notifications)
- **MMKV or expo-sqlite** for local encrypted storage
- **Reanimated 3** for animations (NOT Lottie, NOT Rive for V1)
- **react-native-svg** for character (separable parts pattern)
- **TypeScript** throughout

### Web (landing page)
- **Static HTML** for the production landing page (zero JS dependencies, deploys anywhere)
- Optional **React + Vite** version available for richer interactivity (eye tracking, click reactions, time-of-day)
- **Fraunces + Instrument Sans** loaded from Google Fonts
- Tailwind for the React version, plain CSS for the HTML version

### Privacy
- All medication data lives encrypted on-device
- We never see what users take
- Notifications never include medication name on lock screen
- No analytics on health data
- Aggregated/anonymous product analytics only (e.g., feature usage, retention)

---

## 11. Page-Level Design Rules (LOCKED)

These are decisions we made and will not revisit:

### Section colour rules
- ✅ Cream sections (default)
- ✅ Two Nooma red sections per page (Feature 2 + Final CTA)
- ✅ One ink section (footer)
- ❌ No gradient backgrounds on sections
- ❌ No sage / lavender / butter / aubergine sections
- ❌ No fading from one colour to another at section level

### CTA rules
- ✅ All CTAs are Nooma red on cream sections
- ✅ All CTAs flip to cream-on-red on Nooma red sections
- ✅ Hover states use `--nooma-deep` for the darker red
- ❌ No black CTAs
- ❌ No outline-only CTAs

### Typography rules
- ✅ Headers in Fraunces, body in Instrument Sans
- ✅ One italic emphasis per headline, in Nooma red (cream sections) or gold (red sections)
- ❌ No multiple italic phrases per headline
- ❌ No emphasis on the brand name itself

### What we never put on the page
- ❌ "Streaks" (we have a small "🌱 12d" pill in the phone mockup but it represents *days remembered*, not a punishable streak — and never appears in the brand copy)
- ❌ Red exclamation alerts
- ❌ Wellness vocabulary
- ❌ "Self-care" framing
- ❌ Defensive framing ("no shame", "no streaks" — these activate the very frame we want to avoid)
- ❌ Character's name (users name their own)

---

## 12. What's Locked vs What's Open

### LOCKED — do not change without explicit reason
- Brand name (Nooma)
- Domain (nooma.care)
- Tagline ("Never forget your meds again.")
- Colour system (3 colours + 1 minor accent)
- Character design (cel-shaded ghost with red tie)
- Six-layer idle animation system
- Voice and copy patterns
- Pricing structure (Free + Plus £4.99/mo)
- Page funnel structure (12 sections in this order)
- 4-tab nav (Home / Meds / Sanctuary / History)
- Settings live in top-right `⋯` menu, not in a tab
- No streaks, no shame, no wellness, no social

### OPEN — to be decided / built
- Trademark clearance for Nooma in classes 9 (apps) + 44 (medical) across US/UK/EU
- Domain purchase (nooma.care + backups: trynooma.com, hellonooma.com)
- Real press coverage (currently placeholder logos: The Cut, Vogue, The Verge, Refinery29, App Store, Bustle)
- Real user testimonials (currently 9 placeholder quotes — replace with real beta voices)
- Real App Store / Google Play URLs in badges
- Real social handles (TikTok, Instagram, X, Discord)
- Privacy policy + terms of service
- Onboarding flow (the "name your companion" first-run moment)
- Add-medication flow
- Apple Watch / lock screen widget designs
- Cosmetic shop / Sanctuary tab content
- Meds tab full design
- History tab calendar view
- 30+ notification copy variants
- 12-month seasonal drops calendar
- Hire RN contractor or build with Claude Code

---

## 13. Working File Reference

The following HTML/React files exist as production-ready brand assets (in `/mnt/user-data/outputs/`):

### Primary
- `nooma-landing.html` — final, production-ready landing page (post-launch funnel structure with the locked colour discipline)
- `nooma-app.zip` — full Vite + React + Tailwind + Framer Motion project for an interactive React version of the landing page

### Character & animation references
- `pippi-character.html` — standalone character with full 6-layer idle
- `pippi-style-test.html` — locked style reference
- `pippi-tie.html` — character with red tie + 8 colour options
- `pippi-hats.html` — 8 swappable hats (note: hat placement needs to be lowered 25-30px)
- `pippi-flying.html` — three flight animation variations
- `pippi-speeding.html` — treadmill-style movement
- `pippi-digging.html` — 8s digging-for-rock loop
- `pippi-scene.html` — 16s multi-stage scene
- `pippi-reading.html` — character reading book
- `pippi-idea.html` — lightbulb → watering plant scene

### App screen references
- `pippi-app-home.html` — home/sanctuary screen
- `pippi-app-reading.html` — character reading newspaper variant
- `pippi-app-greeting.html` — 6-second greeting sequence
- `pippi-app-multi.html` — Free vs Plus tier home comparison
- `pippi-plus.html` — Plus subscription paywall
- `pippi-home-reference.html` — locked v5 home with 4-tab nav
- `pippi-time-of-day.html` — 4 phones showing morning/midday/evening/night
- `pippi-treehouse.html` — side-quest mockup (3 build stages + project detail)

### Earlier funnel iterations
- `pippi-landing.html` — earlier iteration before Nooma rename
- `pippi-prototype.html` — 6-screen clickable prototype
- `pippi-rn-demo.html` — React Native–style animation demo

### Briefs
- `pippi-design-brief.md` — the previous brief (now superseded by this Nooma brief)

---

## 14. The Spirit of the Brand (in one paragraph)

Nooma is a small, gentle thing on your phone that helps you take your medication. It is not a wellness app, not a productivity tool, not a health tracker. It is a companion product, designed for people whose medications are just life — not a goal to optimize, not a habit to gamify. The app remembers so the user doesn't have to. It charges only for cosmetics, never for the part that helps. It treats every user as a person doing their best, not a project to fix. It speaks softly, shows up reliably, and never makes its presence about itself. The brand colour is red — confident, warm, present. The world it lives in is cream — soft, neutral, breathable. The character at its heart has a name, but it isn't ours to give. That belongs to the user.

---

*This brief is the locked source of truth as of April 2026. Anything not specified here should be designed in this spirit, with this discipline, and in this voice.*
