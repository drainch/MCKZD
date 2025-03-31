# MCKZD Prompt Logic

---

## INPUTS

- Text prompts: freeform mood, feeling, moment, or use-case
- Optional vibe slider: Soft / Grounded / Focused / Expansive
- Future: voice input, body/energy tagging, time-of-day preference

---

## EXAMPLES

User says:  
> "Make a playlist for decompressing after a long day."  
→ GPT parses for: tempo (70–95), tone (warm, mellow), genre blend (neo-soul, ambient, soft indie)

User says:  
> "Rebuild my YouTube 2021 playlist with my Apple Music taste now."  
→ Uses cross-platform listening data to create an updated, personalized version.

---

## AI WORKFLOW (BASIC)

1. GPT parses prompt for:
   - Mood
   - Tempo
   - Texture
   - Genre lean
   - Exclusions (e.g. emotional spikes, certain instruments)

2. Cross-references:
   - User’s listening history (via Spotify API or Last.fm)
   - Track metadata (via Musixmatch, AudioDB, Spotify audio features)

3. Builds playlist
4. Titles and sends it to user account (or in-app)

---

Future versions: adaptive learning based on user feedback per playlist.
