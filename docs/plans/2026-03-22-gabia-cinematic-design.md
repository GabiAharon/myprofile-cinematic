# Gabi Aharon Cinematic Homepage Design

## Objective
Replace the existing link-aggregator style homepage with one cinematic landing page that presents three worlds:
1. Body language and public speaking
2. AI projects
3. Music

Each world should feel like a full-screen chapter, support navigation between chapters, and open the related site on click.

## Inputs Used
- `https://www.gabiaharon.com/` for current homepage structure and social links
- `https://gabrielaharon.com/` for public speaking copy and tone
- `https://myaiworld.xyz/` for AI positioning and meta description
- `https://gabismusic.xyz/` for music positioning and meta description
- `https://basketball-cinematic-146x.vercel.app/` as interaction reference

## Design Direction
- Cinematic and editorial, not a generic portfolio carousel
- One persistent stage with poster imagery, ambient light, glass panels, and dramatic typography
- Hebrew-first copy with English accent language only where it adds mood
- Strong contrast between the three worlds through color shifts:
  - warm gold for speaking
  - electric cyan for AI
  - pink-magenta for music

## Interaction Model
- Sidebar chapter navigation on desktop
- Dot navigation on mobile
- Arrow navigation between adjacent worlds
- Entire main content card acts as the primary link target
- Bottom social dock keeps all current network links available at all times

## Video Strategy
- The page is implemented as video-ready, but does not require video files to work
- If transition files exist under `videos/`, the page will play them
- If no video files exist, the page falls back to cinematic poster transitions

## Scope
- Create a single static `index.html`
- Add a short local design note for traceability
- Add a `videos/README.md` with expected filenames for future asset drop-in

## Out of Scope
- Deploying the page
- Generating actual transition videos
- Rebuilding the three destination sites themselves

## Risks
- No local video assets were provided, so final motion currently uses fallback transitions
- AI and music site copy is inferred mostly from live metadata and site framing, not from full rendered body content
