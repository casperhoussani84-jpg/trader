---
format: 1080x1920
duration: 20s
message: "PHOENIX PLAST's lunch box is a premium, precision-engineered product — built to feel as good as it looks."
arc: Hero reveal → Engineering proof → In-use warmth → Perfected close → Brand outro
audience: parents shopping for premium kids' lunch gear
mode: autonomous
music: none
---

## Video direction

- **Palette** — canvas `#FFFFFF` (studio white, never pure-flat — slight warm-gray floor shadow); ink `#2B2B2B` (from the box's smoked shell); accent `#C9A227`→`#E8C766` gold gradient (logo only, Frame 5); the product's own light-blue `#A9C9D6` reads naturally from the photos — never recolor it.
- **Motion grammar** — long-tail `power3` settles everywhere, no bounce/overshoot anywhere (this is a luxury object, not a toy ad). Reveal model: since the video is silent, each frame paces its reveals across its own duration on a fixed internal clock instead of a VO cue — never dump the whole shot at t=0; the entrance carries only the hero element, supporting moves (light sweeps, pulses, secondary text) land in the back ~50%, then hold.
- **Single-photo constraint** — every frame has exactly ONE real photo of the product (no multi-angle capture, no generated video). "360° rotation" and "locks closing" are sold through camera-move + compositing on that still (3D perspective tilt, parallax layering, a moving specular highlight, depth-of-field blur, a light-pulse at the lock point) — never a literal multi-frame rotation or a redrawn mechanism. Frame workers must not fabricate additional angles or invent moving geometry that isn't in the source photo.
- **Rhythm / held frames** — Frame 1 settles into a held presentational hold in its back third; Frame 3 is the video's warm "breather" (slow reveal, minimal camera work); Frame 4 is a deliberate held climax (the "perfect close" payoff); Frame 5 holds to the end on the brand lockup. No frame holds via breathing — subtle jitter only.
- **Negative list** — no slideshow front-load, no lazy breathing/circular scale loops, no bad slow pan/push in a frame's back half, no bouncy easing, no invented second product angle, no floating generic "AI" gradients/bokeh.
- **Caption band** — no captions/VO in this build, but Frame 5's text still respects the top ~83% safe area for consistency with the format.

## Frame 1 — Hero rotation

- scene: The closed lunch box floats alone on a glossy white studio floor, slowly rotating to show its full form under soft daylight
- voiceover: ""
- duration: 5s
- transition_in: cut
- status: outline
- src: compositions/frames/01-hero-rotation.html
- type: product_intro
- persuasion: Status seeking
- beat: awe
- blueprint: device-surface-showcase — the product itself is the whole surface being shown
- asset_candidates: assets/images/product-04.jpeg — closed lunch box, angled hero shot, light-blue latches, sharp floor reflection

narrativeRole: Cold open on the product as an object of desire — no claims yet, just presence and craft.
keyMessage: This is a premium object, not a toy.

blueprint: compose — no UI/typographic blueprint fits a pure hero-object presentation; built from the camera vocabulary directly.
focal: assets/images/product-04.jpeg
roles: product-04.jpeg = cutout (the entire hero subject; floor reflection treated as part of the same asset, not a separate layer)

Scene 1 (0.0–1.5s): centered, ~55% of frame, layered-depth (soft radial floor-shadow behind, product mid-ground, a faint top-key highlight foreground). Box enters via a smooth **fromTo** scale+opacity settle (`spring-pop-entrance`, long-tail `power3`, no overshoot) onto the glossy white floor.
Scene 2 (1.5–4.0s): same centered framing. A slow 3D **perspective tilt** on the product layer (`multi-phase-camera`) sells dimensionality — a few degrees of rotateY/rotateX drift, one direction only, settling by ~3.5s; a soft **specular highlight sweeps** once across the shell in the same window (`ambient-glow-bloom`, single pass, not looping) to read as "premium reflections."
Scene 3 (4.0–5.0s): hold the settled 3/4 angle; at most **subtle jitter** (`sine-wave-loop`, low amplitude) — no further push, no breathing.

## Frame 2 — Locks close

- scene: Macro push-in on the two side locks snapping shut, a light flash sells the "click" since audio is silent
- voiceover: ""
- duration: 4s
- transition_in: crossfade
- status: outline
- src: compositions/frames/02-locks-close.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: confidence
- blueprint: cursor-ui-demo — a close, hands-on mechanism proof
- asset_candidates: assets/images/product-01.jpeg — lid open, tray with utensils, light-blue hinge locks visible

narrativeRole: Prove the engineering — the locks are precise and satisfying, not flimsy.
keyMessage: Built to seal properly, every time.

blueprint: cursor-ui-demo (Adapt) — keep the "close, hands-on mechanism proof" signature (an in-frame push toward the working part); drop the cursor itself, since there's no UI to point at — the camera push stands in for it.
focal: assets/images/product-01.jpeg
roles: product-01.jpeg = cutout (cropped tight to the visible hinge-lock region, not the whole lid)

Scene 1 (0.0–1.2s): asymmetric 60/30, 2 depth layers — crop enters on the lock/hinge area (upper-left of the tray) via a short **zoom-to-target** (`coordinate-target-zoom`) from the wider lid view; rest of the tray falls into soft **depth-of-field blur** (`depth-of-field-blur`) so the lock reads as the one sharp thing.
Scene 2 (1.2–2.8s): continued push, macro, centered on the latch point. On arrival, a single bright **light-pulse** (`spring-pop-entrance`, fast attack, no repeat) flashes at the latch to sell the "click" the missing audio can't — one pulse only, not a strobe.
Scene 3 (2.8–4.0s): hold the macro framing; **subtle jitter** only, no further push (avoids the doctrine's back-half bad-push rule).

## Frame 3 — Fresh lunch inside

- scene: A bright, family-friendly lunch — chicken, rice, vegetables, fruit — settles into the open compartments
- voiceover: ""
- duration: 5s
- transition_in: crossfade
- status: outline
- src: compositions/frames/03-fresh-lunch.html
- type: benefit_highlight
- persuasion: Future pacing
- beat: warmth
- blueprint: titlecard-reveal — a calm, held value beat
- asset_candidates: assets/images/product-03.webp — open box filled with chicken, rice, broccoli, carrots, fruit/cheese bites

narrativeRole: Let the parent picture their own kid's lunch in it — the emotional payoff of Frame 2's engineering.
keyMessage: This is where a real, healthy lunch goes every day.

blueprint: titlecard-reveal (Adapt) — keep the "calm, held value beat" signature; the food photo itself is the value beat, no card/text needed.
focal: assets/images/product-03.webp
roles: product-03.webp = cutout (full-bleed hero, centered, ~65% of frame)

Scene 1 (0.0–1.5s): centered, full-width strip. The open, filled box **fromTo** settles in (smooth long-tail scale+opacity, `power3`) — this is the video's designated breather, so the entrance is calm, not punchy.
Scene 2 (1.5–3.8s): a soft warm **ambient glow blooms** (`ambient-glow-bloom`) behind the box once, low-amplitude, reading as daylight rather than an effect; no camera push, no pan (this frame stays still — the warmth is in the light, not the motion).
Scene 3 (3.8–5.0s): hold the settled, lit frame; **subtle jitter** only.

## Frame 4 — Perfect close

- scene: The lid closes flush and clean; held hero shot on the glossy white surface
- voiceover: ""
- duration: 3s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/04-perfect-close.html
- type: benefit_highlight
- persuasion: Show-don't-tell proof
- beat: satisfaction
- blueprint: titlecard-reveal — near-still, the calm confirms the claim
- asset_candidates: assets/images/product-04.jpeg — closed lunch box, angled hero shot, light-blue latches, sharp floor reflection

narrativeRole: Section boundary — from "in use" back to the pristine hero object, resolving the demo.
keyMessage: It closes as perfectly as it looks.

blueprint: titlecard-reveal (Adapt) — keep the "near-still, the calm confirms the claim" signature.
focal: assets/images/product-04.jpeg
roles: product-04.jpeg = cutout (same hero asset as Frame 1, reused deliberately to bookend the film)

Scene 1 (0.0–1.0s): centered, ~55% of frame. The closed box **scale-swaps** into place (`scale-swap-transition`) at the tail of the `zoom-through` transition already carrying it in from Frame 3 — arrival lands settled, no extra motion layered on top of the harness transition.
Scene 2 (1.0–3.0s): held climax — box sits centered, still, on the glossy floor; one quiet **ambient glow bloom** (`ambient-glow-bloom`) low-amplitude behind it for warmth; **subtle jitter** only. This is the deliberate "perfect" hold — no push, no pan, no breathing.

## Frame 5 — Brand outro

- scene: The PHOENIX PLAST logo settles center-frame with "Premium Lunch Box" beneath it, held on a clean white ground
- voiceover: ""
- duration: 3s
- transition_in: crossfade
- status: outline
- src: compositions/frames/05-brand-outro.html
- type: branding
- persuasion: Authority by association
- beat: trust
- blueprint: logo-assemble-lockup — wordless premium sting
- asset_candidates: assets/images/product-02.png — PHOENIX PLAST gold phoenix logo + wordmark on white

narrativeRole: Close on brand identity — leave the name and the promise, nothing else.
keyMessage: PHOENIX PLAST. Premium Lunch Box.

blueprint: logo-assemble-lockup (Adapt) — keep the "wordless premium sting, mark lands and holds" signature; no dispersing UI elements to clear (nothing preceded it in-frame), so the mark simply settles rather than assembling from scattered pieces.
focal: assets/images/product-02.png
roles: product-02.png = cutout (logo lockup, centered)

Scene 1 (0.0–1.0s): centered, upper-middle third, top ~83% safe. Logo **fromTo** settles in (`spring-pop-entrance`, long-tail `power3`, no overshoot) on a clean white ground.
Scene 2 (1.0–2.0s): directly beneath the logo, the line "Premium Lunch Box" reveals via **per-word staggered reveal** (`dynamic-content-sequencing`) — two words, one beat each — display type per `frame.md`.
Scene 3 (2.0–3.0s): hold the completed lockup + line; **subtle jitter** only — this is the film's real exit (final frame), so it simply holds to the last frame rather than animating off.
