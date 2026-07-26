# Weez Pixel

Weez Pixel is a Codex-compatible v2 animated orange-and-white tabby rendered in a charming 16-bit retro RPG style.

The package contains:

- `pet.json` — pet metadata with `spriteVersionNumber: 2`
- `spritesheet.webp` — an 8×11 RGBA atlas using 192×208 cells

The atlas includes all nine standard Codex pet animations plus 16 clockwise look directions. Its definitive facial map follows the close-up reference: a narrow white blaze around the pink nose, a light muted tan image-left muzzle pad, a soft-white image-right pad, and a broad low rounded tan/orange chin above the white throat and bib. The asymmetric markings rotate and occlude with the head rather than mirroring.

Gesture animations preserve four-legged feline anatomy: raised, clasped, and working paws reposition the existing forelegs instead of adding extra arms, while hind legs may remain naturally occluded by the torso.

The final rear-right look pose also anchors the tail at the sacrum on the spinal midline between the hips before it curves right.

The 1536×2288 atlas has passed structural, transparency, chroma-cleanup, limb-anatomy, blind-direction, continuity, and independent visual QA.
