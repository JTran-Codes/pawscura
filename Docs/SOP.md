Pawscura — Standard Operating Procedure (SOP)

Goal: Turn a customer’s pet photos + chosen art style into an accurate, print-ready AI portrait—without changing the pet’s identity.

Tools:
Order form (collects pet details + photos)
ChatGPT (for style research + precise photo description)
ChatGPT Image Generator (for the actual artwork)
Photo editor (final touch-ups)

Inputs (from the Order Form):
Pet name & breed
Chosen art style
2–5 reference photos of the pet

Step-by-step:
1) Intake from Order Form
Receive order with:
Pet name/breed
Style choice (e.g., Pop Art, Anime, High Renaissance)
2–5 photos

Pick the best single reference photo to replicate (clear face, correct markings, good lighting).

2) Style Research (ChatGPT)
Ask ChatGPT to extract the defining concepts for the chosen style.

Prompt:
What are the best artworks for the “[STYLE]” aesthetic? Act as an art researcher and describe what makes these artworks the greatest. 
Give me concise bullet points I can reuse in an image prompt (composition cues, color/lighting, texture/linework, mood, common motifs).

Output you need: A short list of style concepts (not long essays) that you can drop into a generation prompt.

3) Exact Photo Description (ChatGPT)
Upload/paste the client’s chosen reference photo and ask ChatGPT to describe it with identity-preserving detail.

Prompt:
Describe this photo so we can prompt an image generation to replicate this exact photo; 
the pet should not look different compared to the original photo supplied. 
Focus on pose, angle, facial features, fur/markings, colors, lighting, background elements that must remain consistent.

Output you need: A precise description that captures the pet’s identity (pose, markings, colors, ear shape, blaze/patches, eye color, collar, etc.).

4) Build the Generation Prompt (combine #2 + #3):
Create one prompt that merges:
The style concepts (from Step 2)
The exact photo description (from Step 3)

Template you can reuse:
Create an illustration in the [STYLE] aesthetic.

STYLE NOTES (from art research):
- [bullet 1]
- [bullet 2]
- [bullet 3]

REPLICATE THIS EXACT PHOTO (identity must not change):
- [pose/angle]
- [fur colors & patterns/markings]
- [ears/eyes/nose/muzzle]
- [collar/bandana/tag if present]
- [lighting/background elements to keep]

Hard rules:
- The pet must look exactly like the photo (no new/missing markings, no breed changes).
- Keep proportions and pose as described.

5) Generate & Iterate (ChatGPT Image Generator)
Paste the combined prompt into ChatGPT’s image generator.
Generate a couple times; compare outputs to the reference photo.
If needed, edit the prompt to tighten identity details (e.g., “white blaze stops at nose,” “ears large and upright,” “red-and-white coat,” “no tabby stripes,” etc.).
Repeat until the output is an accurate match to the pet and the chosen style.

6) Final Touch-Up (Photo Editor)
Open the selected image in your photo editor.
Do light cleanup only (e.g., edges, minor color/contrast, dust/remove artifacts).
Do not alter identity (do not change markings, pose, or facial structure).

7) Export (Print-Ready)
Color: sRGB IEC61966-2.1
Resolution: ≥ 4000 px on the long edge (aim 3500–5000+)
Clean, anti-aliased edges; no compression artifacts
Preserve natural shadow detail (avoid crushed blacks)

Export formats:
PNG for transparencies or crisp edges
High-quality JPG for photos/prints

8) Delivery
Send the final print-ready file to the customer.
(Optional) Provide a small web preview.
Archive the prompt + final image in your project files.

Quick Checklists
Identity Accuracy (must pass):
Markings/patches (shape, size, position) match the photo
Correct fur colours; no invented stripes/patches
Pose/angle and proportions match
Accessories (collar/bandana/tag) consistent
Expression/ears/eyes consistent

Style Fit:
Colour/lighting/mood align with the researched style notes
Linework/texture appropriate for the style
Readable at thumbnail size

Notes
If two outputs tie, pick the one that best preserves identity over style exaggeration.
If reference photos conflict, follow the main chosen photo and keep the rest for context only.
