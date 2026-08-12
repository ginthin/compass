# NOVA — the complete creation kit

Everything needed to create, draw, animate and write Nova: character, world, locations, story, style, voice and rig.

**Compass Labs · Compass Learn · the education mascot.**

**How to use this file:** paste the whole thing into Claude at the start of a chat and say "this is Nova, use it as context." Everything below is canon. If something is not in here, it is not decided yet — ask before inventing it.

---

## 0 · The one-paragraph version

Nova is a little star-compass, about beach-ball size, who floats. She hosts Compass Learn, our education engine, and guides people through onchain finance. She lives in the Onchain Sea, a glowing ocean where a grey Fog hides the islands (the products) and travelers sail in circles. Nova reads the North Star, points her red needle, and the fog parts. She never sails the boat for anyone — they hold the wheel. That is the brand promise and the character in one move.

---

## 1 · WHO NOVA IS

Half compass, half star. Warm, curious, a little cheeky, endlessly optimistic, and she cannot stand seeing anyone lost. That is her whole reason to exist.

- **Form:** round lavender body, soft face plate, big readable eyes, rosy cheeks, a wide friendly smile. She floats; she never walks.
- **Signatures (must keep, every time):** a **red needle** on top (points, spins when curious) and a **gold star third-eye** on her forehead (flares when it clicks).
- **No arms, no legs.** The needle is her pointing hand. This is deliberate — it keeps her cheap to animate and impossible to draw off-model.
- **Personality:** warm, curious, cheeky, optimistic, hates confusion.
- **Motion tells:** bobs while idle, needle spins when curious, star flares + happy wobble when it clicks, dims a touch when someone is stuck.

**Her hello:** "Hi! I'm Nova. Lost in the fog? Don't worry, that's literally my whole job. Point the needle, and I'll get you there."

**Her closing line (the series signature):** "You held the wheel the whole time."

### Construction ratios — this is what keeps her on-model

- Body = **1.0** (one circle) · face plate = **0.65** of the body, dropped slightly below centre · star = **0.23**.
- Thick ink outline on the body (roughly 8/190 of the body diameter) and on the face plate.
- One inner compass ring inside the body, with three cream ticks at E, W and S. North is where the needle hub sits.
- Needle mounted on an **ink hub at true north** (top of the body). The **red half always leads**.
- Gold five-point star on the forehead, **above the eye line, never off-centre**. It is the only thing in the whole world that glows.
- Eyes on the eye line, well apart, with a small white highlight up and to the outside.
- Cheeks: two soft pink circles, low and wide.

### The five expressions

Everything she feels is carried by exactly four parts: **eyes, mouth, needle angle, star brightness.** Nothing else moves. This is the rule that makes her animatable forever.

| Face | Eyes | Mouth | Needle | Star |
| --- | --- | --- | --- | --- |
| **Happy** (default) | Round, bright, highlight | Wide smile arc | Swaying gently ~-16° to -32° | Steady |
| **Curious** | Brows up, eyes bright, looking up | Small open smile | Spinning a full turn | Steady, slightly soft |
| **It clicks** | Happy arcs (closed) | Big open smile, filled | Cocked at ~-34° | **Flares** + happy wobble |
| **Dim** | Half-lidded, downturned | Small soft mouth | Muted colour, ~-6° | Muted gold |
| **Pointing** | Following the needle | Confident smile | Out at ~58°, long red half | Steady, gentle flare |

**Curious, not worried.** When Nova does not know something yet she is *eager* — brows up, eyes bright, needle spinning happily. She is never anxious, never stressed, never frowning at the problem. Confusion is the Fog's fault, not the traveler's.

**Dim is sympathy, not sadness.** She never scowls, never scolds, never looks disappointed in anyone. She dims because someone else is stuck, and she comes straight back up the moment the fog parts.

### Palette

| Role | Hex |
| --- | --- |
| Lavender body | `#5B47D6` |
| Deep lavender (shadow, land) | `#3b2ea0` |
| Soft lavender / face plate | `#EFEAFF` |
| Red needle | `#FF6B5E` |
| Gold star | `#FFD23F` |
| Ink features | `#16121F` |
| Page ink | `#1a1230` |
| Teal accent | `#2BC2B0` |
| Pink cheeks | `#FF9ECB` |
| Paper | `#fbf9ff` |
| Night sky (deep) | `#160f2e` |
| Night sky (mid) | `#2a1d52` |

Never more than two background colours in one piece. Gold is reserved for the star, the North Star and lamplight — do not spend it elsewhere.

---

## 2 · HER WORLD — THE ONCHAIN SEA

A vast glowing ocean where value moves in rivers of light, trillions of it. It should be paradise, but a grey Fog hides the islands, and travelers cannot reach the products they came for. The **North Star** above is the direction everything is sailing toward. Nova is the only one who can read it.

### The cast

- **The Fog** — the villain. Jargon, twelve tabs, "build it yourself." It has **no face and never speaks**; it just sits between a traveler and what they wanted. Nova burns it off with her star-light. That beam cutting through the fog is the money shot of the whole series.
- **The Travelers** — a **Wallet**, a **Fintech**, and a little robot **Agent**. Simple, lovable, on-model with Nova. Nova never sails for them; they hold the wheel (non-custodial). This is not a metaphor we can drop — it is the product.
- **The Tangle** — the old way. A knot of ropes: integrating each protocol by hand. Compass hands them one clean rope.

### The islands (each one is a product)

| Island | Product | Its gold landmark |
| --- | --- | --- |
| **Earn Isle** | yield | a lantern |
| **Loan Cove** | borrow, keep your treasure | a vault door |
| **RWA Reef** | tokenized stocks & T-bills | stacked blocks |
| **Perps Peak** | perps | a sharp peak with a red chart line |
| **Rebalance Bay** | one-signature rebalance | twin scales |
| **Studio Lighthouse** | try before you sail | a lighthouse |

**Island recipe (so all six are drawn once and reused):** a round green-lavender landmass, **one gold landmark on top** that says what the island is for, a small dock, and a traveler's boat pulling in. Swap the landmark and you have the next island without redesigning anything.

### Newcomer's Harbor — where everyone lands

Where every traveler first lands, overwhelmed. *"They're talking about a million things, what even IS all this?"* This is where Nova teaches the basics, one tiny stop at a time, **so a definition becomes a place you visit**.

Warm lamplit docks on solid ground at the edge of the Fog. Little houses with red and teal roofs, boats tied up rocking gently, sails in Compass colours, travelers milling about with no idea which way is out. Deliberately cozy — the world is not scary, it is just unmapped. Nova hangs above the pier, needle already pointing.

**The docks — the words of the Sea.** Each is a 30-second Nova stop. She points at the thing, names it in plain words, and you never have to read a glossary again.

| Place | Word | What Nova says |
| --- | --- | --- |
| The Keyhouse | **Wallet** | The tool you control your assets with, and where you sign. You hold the keys, you hold the wheel. |
| The steady buoy | **Stablecoin** | A token built to track a dollar. It never rocks. The calm money of the Sea. |
| The wind | **Gas** | A little fee to get a transaction moving. Compass can pay it for your users. |
| Your stamp | **Signing** | You stamp your own message. Nobody else can. That's how an action gets approved. |
| The wheel | **Custody** | Who can actually move the funds. With Compass, always the user. Never us. |
| The Sea itself | **Onchain** | Anything that lives and runs on a blockchain. It's the whole Sea we're sailing. |

**The weather — reading the market.** Newcomers don't just miss the words, they miss the **market**. Nova reads the weather so "why now" finally makes sense.

- **The rising tide** — money is moving onchain, trillions of it. That's the wave everyone is trying to catch.
- **The currents** — yield and risk. Where the water pulls, and how strong. Nova always names the risk, never hides it.
- **The open water** — DeFi. Financial products with no bank in the middle, out on the Sea.
- **The native builders** — the protocols (Aave, Morpho, Pendle). The ones who built each island. Compass connects you to them.

---

## 3 · THE STORY ENGINE

Every video is the same little voyage, so Nova always has a story and it is always short.

1. **A traveler is lost in the fog**, near the thing they want.
2. **Nova appears**, star glowing. She names the confusion in one plain sentence.
3. **She points the needle.** The fog parts, one clean route lights up.
4. **The traveler arrives and ships.** Star flare, happy wobble. *"You held the wheel the whole time."*

Four beats, 30 to 60 seconds. If an episode does not fit these beats, it is not a Nova episode.

**Two episode shapes:** *a Harbor stop* (one basic word, 30s, one dock) or *a voyage* (one island / one product, 45-60s, harbor → fog → island).

---

## 4 · ART DIRECTION — THE QUALITY BAR

Cozy, expressive 2D cartoon. Thick friendly outlines, squash-and-stretch, big emotion. Warm saturated world with depth, light and atmosphere: drifting fog, twinkling stars, gentle waves, lamplight. It must feel **hand-made and alive**, never a flat corporate explainer with clip-art.

**References:** the warmth of a Pixar short · the friendliness of Duolingo's Duo · the cozy hand-made feel of a Headspace animation · the world-depth of a Studio Ghibli sky.

**The six things that make it chafa. Avoid all six:**
1. stiff sliding movement
2. flat clip-art
3. generic stock
4. robotic voices
5. a character that looks different every video
6. no sound design

**Composition rules:** left-aligned, roomy. Nova floats in the upper third with her shadow on the water below her. The horizon sits low. Fog drifts horizontally, always. Water gets three or four wave lines at different speeds, never one.

---

## 5 · VOICE & WRITING

Nova speaks plainly and briefly. She names the confusion out loud before she solves it. She never uses a jargon word without immediately giving it a place ("gas — the wind"). She is cheeky but never sarcastic, never condescending, and she never makes the traveler feel stupid.

She **always names the risk** and never hides it. She never promises returns. Compass is non-custodial: users hold custody, always.

Voice production is **ElevenLabs** — warm, a little playful — lip-synced to the rig.

---

## 6 · THE RIG (so the team produces episodes forever)

Design Nova once, beautifully, and rig her so anyone can make new episodes fast and consistent without redrawing.

| Pipeline | Best for | What we get |
| --- | --- | --- |
| **Adobe Character Animator** | Talking-head Nova, fast turnaround | Real-time lip-sync + expressions from voice; a live puppet the team drives |
| **Rive** | Crisp vector, web + app, tiny files | Interactive rig: bob, blink, point, star-flare; embeddable on the site |
| **After Effects** (+ Duik/RubberHose) | Premium 2D film look | The richest animation; templated scenes we refill per episode |

**The rig must be:** audio-drivable, repeatable, and documented. Deliverables from whoever builds it: source files, an on-model guide, and a short "how to make a new episode" doc so the team is self-sufficient. Output 1:1 and 9:16, plus a web-embeddable Nova (Rive/Lottie) if possible.

**Deliverables from the illustrator:** Nova turnaround (front, 3/4, side) + the five-expression sheet · the Onchain Sea world map + the six islands + Newcomer's Harbor + the Fog · the supporting cast (Wallet, Fintech, Agent, the Fog) · the rig + one sample episode + the handoff doc.

**Timeline:** Phase 1 design ~1-2 weeks. Phase 2 rig ~1-2 weeks. Then the team ships on a 2-per-week cadence.

**The one upfront investment:** pay once for great character design + world art + a reusable rig. After that every episode is cheap and fast. Quality is one art investment, then infinite scale.

---

## 7 · NOVA AS CODE (drop-in animated SVG)

This is Nova, on-model, animated (floats, blinks, needle sways). Save as `nova.svg` or paste inline into any HTML.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="-170 -215 340 400" width="340" height="400" role="img" aria-label="Nova">
  <title>Nova</title>
  <style>
    @keyframes novaBob { 0%,100% { transform: translateY(6px) } 50% { transform: translateY(-10px) } }
    @keyframes novaBlink { 0%,90%,100% { transform: scaleY(1) } 94% { transform: scaleY(.08) } }
    @keyframes novaSway { 0%,100% { transform: rotate(-16deg) } 50% { transform: rotate(-32deg) } }
    @keyframes novaPulse { 0%,100% { opacity: .18 } 50% { opacity: .5 } }
    .bob { animation: novaBob 3.4s ease-in-out infinite }
    .blink { transform-box: fill-box; transform-origin: center; animation: novaBlink 5.2s ease-in-out infinite }
    .sway { animation: novaSway 4.6s ease-in-out infinite }
    .shadow { animation: novaPulse 3.4s ease-in-out infinite }
  </style>
  <ellipse cx="0" cy="152" rx="74" ry="15" fill="#16121F" class="shadow"/>
  <g class="bob">
    <circle cx="0" cy="0" r="95" fill="#5B47D6" stroke="#16121F" stroke-width="8"/>
    <circle cx="0" cy="0" r="79" fill="none" stroke="#4634b8" stroke-width="5"/>
    <rect x="80" y="-4.5" width="13" height="9" rx="4.5" fill="#EFEAFF" opacity=".75"/>
    <rect x="-93" y="-4.5" width="13" height="9" rx="4.5" fill="#EFEAFF" opacity=".75"/>
    <rect x="-4.5" y="80" width="9" height="13" rx="4.5" fill="#EFEAFF" opacity=".75"/>
    <circle cx="0" cy="12" r="62" fill="#EFEAFF" stroke="#16121F" stroke-width="6"/>
    <circle cx="-44" cy="44" r="11" fill="#FF9ECB" opacity=".85"/>
    <circle cx="44" cy="44" r="11" fill="#FF9ECB" opacity=".85"/>
    <circle cx="0" cy="-95" r="9" fill="#16121F"/>
    <g transform="translate(0,-95)"><g class="sway">
      <path d="M0,-10 L54,0 L0,10 Z" fill="#FF6B5E" stroke="#16121F" stroke-width="4" stroke-linejoin="round"/>
      <path d="M0,-10 L-54,0 L0,10 Z" fill="#EFEAFF" stroke="#16121F" stroke-width="4" stroke-linejoin="round"/>
    </g></g>
    <path d="M0,-22 L5.3,-7.3 L20.9,-6.8 L8.6,2.8 L12.9,17.8 L0,9 L-12.9,17.8 L-8.6,2.8 L-20.9,-6.8 L-5.3,-7.3 Z" transform="translate(0,-26)" fill="#FFD23F" stroke="#16121F" stroke-width="5" stroke-linejoin="round"/>
    <g class="blink">
      <circle cx="-28" cy="20" r="13" fill="#16121F"/>
      <circle cx="28" cy="20" r="13" fill="#16121F"/>
      <circle cx="-23" cy="15" r="4.2" fill="#fff"/>
      <circle cx="33" cy="15" r="4.2" fill="#fff"/>
    </g>
    <path d="M-22,48 Q0,66 22,48" fill="none" stroke="#16121F" stroke-width="6" stroke-linecap="round"/>
  </g>
</svg>
```

**Expression swaps** — keep everything above and replace only the eyes/mouth/needle/star group:

- **Curious:** needle `animation: novaSpin 2.4s linear infinite` (`@keyframes novaSpin { to { transform: rotate(360deg) } }`); add brows `<path d="M-42,3 Q-29,-10 -15,0" stroke="#16121F" stroke-width="5" fill="none" stroke-linecap="round"/>` and the mirror; eyes at `cy="22" r="14"`; mouth `<path d="M-15,48 Q0,66 15,48 Z" fill="#16121F"/>`.
- **It clicks:** star gets `animation: novaFlare 1.1s ease-in-out infinite` (`@keyframes novaFlare { 50% { transform: scale(1.28); filter: drop-shadow(0 0 14px #FFD23F) } }`); eyes become arcs `<path d="M-40,22 Q-28,6 -16,22" stroke-width="7"/>` + mirror; mouth `<path d="M-24,44 Q0,74 24,44 Z" fill="#16121F"/>`; whole body wobbles ±5°.
- **Dim:** needle `#c9564c`/`#d8d2e4`, star `#c9a94f`, eyes as downturned arcs, small mouth, plus `<circle r="99" fill="#16121F" opacity=".16"/>` over the body.
- **Pointing:** needle `rotate(58)` with a longer red half (`L64,0`), eyes shifted toward it, confident smile.

---

## 8 · WHAT EXISTS ALREADY IN THIS PROJECT

- `Nova Character.dc.html` — Nova alive, all five expressions switchable, construction guide with ratios, expression sheet, palette, motion tells.
- `Nova World Compass.dc.html` — the Onchain Sea: the map with the North Star, three establishing shots (Harbor, the Fog, an island), the six islands, the cast, the story engine.
- `Newcomers Harbor.dc.html` — the Harbor as its own place: animated scene, the six docks, the weather.
- `Nova Design and Rig Brief.dc.html` — the brief to hand an illustrator/animator or studio.
- `nova.svg` — standalone animated Nova, drop anywhere.
- `NOVA-COMPLETE-KIT.md` — this file.

---

## 9 · GOOD PROMPTS TO GIVE CLAUDE WITH THIS FILE

- "Write me episode 1: a Wallet lost in the Fog looking for yield. Four beats, 45 seconds, Nova's voice."
- "Draw Loan Cove following the island recipe."
- "Write six Harbor stops as 30-second scripts, one per dock."
- "Turn the story engine into a storyboard for Perps Peak."
- "Write the ElevenLabs voice direction for Nova, plus three sample lines per expression."
- "Keep Nova on-model and tell me if anything I asked for breaks the construction ratios."

---

Compass Labs · Nova Creation Kit · non-custodial infrastructure, users hold custody.
