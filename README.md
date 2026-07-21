# Midjourney Product Mockup Prompts

A categorized collection of Midjourney prompts for generating blank product mockups — drinkware, apparel, packaging, beauty, tech, wall art, books, home decor, accessories, and footwear. Each prompt includes an explanation of the mechanics behind it (lighting, composition, material rendering) rather than generic marketing claims, plus variants you can swap in.

Compatible with Midjourney V7 and V6. Syntax like `--ar` and `--no` has stayed stable across recent versions, but keyword weighting may shift slightly in future releases — re-test before relying on exact output.

## Requirements

You'll need an active Midjourney subscription and access to the bot through Discord or the web interface. Commercial usage rights depend on your specific plan tier, so check Midjourney's current terms before using generated images in a storefront or ad campaign.

## How to use these prompts

Every prompt follows the same structural order: **product → material/finish → environment → lighting → camera angle → aspect ratio → negative prompt.** Keeping that order consistent makes it easy to swap individual pieces without breaking the rest of the sentence. Copy a prompt, paste it into Midjourney, generate four variations, and pick the strongest one. Then swap the bracketed material, color, or environment terms to match your actual product.

---

## Drinkware

### Ceramic Mug

```text
white ceramic mug, wooden table, morning sunlight, soft shadows, minimalist kitchen, commercial photography, 8k --ar 4:5 --no text
```

Low-angle directional light produces a shadow gradient along the mug's curvature, which is what reads as roundness rather than a flat printed circle. Eye-level framing keeps proportions undistorted, which matters for listing photos where buyers judge handle size and cup capacity. The wood grain gives texture contrast against the glazed ceramic without competing for attention, and 4:5 matches most Etsy thumbnail crops. `--no text` suppresses Midjourney's tendency to add illegible label-like marks on blank surfaces.

**Variants:** swap `white ceramic` for matte black stoneware or speckled clay · add `steam rising from coffee` for a motion cue · swap the table for a marble countertop or linen tablecloth.

---

## Apparel

### Canvas Tote Bag

```text
blank canvas tote bag, hanging on wooden door, soft natural light, cozy bedroom, lifestyle product photography, highly detailed --ar 4:5 --no text
```

Diffused, non-directional light minimizes harsh shadows on woven fabric, which would otherwise read as visual noise on canvas texture. Hanging the bag against a vertical door line gives it natural drape, closer to how it looks carried than a flat lay would. The domestic setting implies daily-use context, which matters if this is for lifestyle marketing rather than an isolated listing photo.

**Variants:** try waxed canvas, jute, or recycled cotton · add a leather strap detail · swap the door for an entryway hook or coat rack.

### Cotton T-Shirt

```text
blank white cotton t-shirt, laid flat on concrete floor, bright studio lighting, top down view, apparel mockups, clean background, sharp focus --ar 1:1 --no text
```

A top-down flat lay eliminates perspective distortion, so seam lines and print placement stay geometrically accurate — important if a design will be overlaid later. Even studio lighting avoids fold shadows that could be mistaken for fabric defects. Concrete gives a neutral mid-gray tone and texture contrast without pulling focus from the garment, and 1:1 is Shopify's default product crop.

**Variants:** fold the sleeves inward · swap concrete for light oak flooring or a white studio backdrop · change the shirt color directly in the prompt.

---

## Home Decor

### Glass Candle

```text
glass candle jar, marble surface, warm glowing light, dark moody background, cosmetic mockups, macro photography, highly detailed --ar 4:5 --no text
```

A warm internal glow against a dark background increases dynamic range, which is what makes glass refraction and wax translucency visible — flat lighting tends to flatten glass into a solid gray shape. Marble's veining adds reflective highlights without introducing clutter, and macro framing brings out surface detail (wax texture, glass thickness) that a wider shot would lose.

**Variants:** change the wax color · add a wooden wick · swap marble for dark slate or linen fabric.

### Throw Pillow

```text
blank linen throw pillow, resting on grey sofa, soft diffused light, modern living room, lifestyle product photography, cozy aesthetic --ar 16:9 --no text
```

Diffused light preserves linen's woven texture without harsh highlights that could read as wrinkles or defects. The widescreen crop includes enough of the sofa and room to establish scale and context, which is the point for a lifestyle shot rather than an isolated product photo.

**Variants:** change the pillow color · swap the sofa for velvet or leather · try a Scandinavian or mid-century room style.

---

## Books

### Hardcover Book

```text
blank hardcover book, standing on dark wood desk, warm desk lamp light, cozy library, realistic product mockups, sharp focus --ar 4:5 --no text
```

A single warm light source at a low angle creates a visible spine shadow that separates the book from the background without needing a distinct backdrop color. The library and desk context signal a reading environment, which is useful when the mockup will later have a cover design composited onto the blank spine and front.

**Variants:** change the cover color · add a bookmark ribbon · add reading glasses or a stack of books nearby.

---

## Tech

### Phone Case

```text
blank phone case, resting on pastel pink bedsheet, bright daylight, soft shadows, lifestyle product photography, minimalist aesthetic --ar 4:5 --no text
```

Bright, near-overhead daylight keeps color saturation high on a small object, which matters for legibility at thumbnail size in ad placements. The fabric backdrop gives soft contrast without hard reflections that would compete with the case's own finish.

**Variants:** try a matte, glossy, or clear finish · add a visible phone screen · change the bedsheet color.

### Laptop Sleeve

```text
blank neoprene laptop sleeve, on minimalist desk, soft overhead light, clean workspace, lifestyle product photography, sharp focus --ar 16:9 --no text
```

Soft overhead light minimizes specular highlights on neoprene's matte surface, keeping the material reading as fabric rather than plastic. The wide crop leaves negative space around the sleeve, useful if you plan to overlay text or UI elements for an ad or banner.

**Variants:** change the sleeve color · add a notebook, pen, or coffee cup to the desk · switch to cool white light for a more clinical tech feel.

---

## Beauty

### Serum Bottle

```text
blank glass serum bottle, wet stone surface, water droplets, bright soft lighting, cosmetic mockups, commercial photography, ultra realistic --ar 4:5 --no text
```

Water droplets increase specular highlights on the surrounding stone, which by contrast makes the glass bottle's own reflections read as clean rather than dusty. Bright, non-directional light avoids the glare that would otherwise obscure the liquid level and cap detail.

**Variants:** change the liquid color · swap in a dropper or pump cap · try frosted glass or white ceramic tile as the surface.

---

## Wall Art

### Art Poster

```text
blank art poster, pinned to textured white wall, natural window light, subtle shadows, realistic product mockups, interior design style --ar 4:5 --no text
```

Window light produces a soft, angled shadow from the pin, giving the poster physical presence against the wall instead of looking like a flat overlay. Subtle wall texture keeps the poster's edges from blending into a pure white void.

**Variants:** swap the pin for a wooden clip or a thin black frame · try exposed brick or board-and-batten walls · adjust the light angle to imply a different time of day.

---

## Packaging

### Coffee Pouch

```text
blank kraft coffee bag, rustic wooden table, scattered coffee beans, warm morning light, packaging mockup prompts, commercial photography --ar 4:5 --no text
```

Kraft paper's fibrous texture shows clearly under warm, low-angle light; flat lighting tends to make it look like plain cardstock. Scattered beans establish the product category at a glance without needing label text, which matters since `--no text` suppresses any printed labeling.

**Variants:** try a matte black pouch with a visible resealable zipper · add a coffee scoop or steam from a mug in the background · swap the table for a burlap sack or stone counter.

### Wine Bottle

```text
blank wine bottle, dark wood wine rack, moody cellar lighting, glass reflections, packaging mockup prompts, realistic product mockups --ar 4:5 --no text
```

Low-key lighting with a single accent light produces defined reflections along the bottle's curvature — the standard way glass bottle photography signals a premium feel without extra props. The wine rack backdrop implies storage and aging, useful for label mockups aimed at cellar or vineyard branding.

**Variants:** try green, clear, or amber glass · add a visible cork or foil capsule · swap the wood rack for a metal one.

---

## Accessories

### Sunglasses

```text
blank sunglasses, resting on a mirror, bright sunny lighting, sharp reflections, fashion commercial photography, high contrast, ultra detailed --ar 1:1 --no text
```

A mirror beneath the product doubles the visible surface area of the frame in a single shot and creates strong specular highlights, which is the main visual cue associated with sunglasses photography specifically. Direct, high-contrast sunlight intensifies lens reflections further.

**Variants:** change the frame color · add a gradient or mirrored lens tint · swap the mirror for polished chrome or wet pavement.

### Jewelry Box

```text
blank velvet jewelry box, dark slate surface, dramatic spotlight, luxury commercial photography, rich shadows, highly detailed --ar 4:5 --no text
```

A single, narrow spotlight creates a strong falloff into shadow at the frame edges, isolating the subject without needing a separate background element. Velvet absorbs rather than reflects light, so directional lighting is what reveals its nap and texture — flat lighting would render it as a flat dark shape.

**Variants:** change the velvet color · add a gold hinge or brass clasp · swap slate for black marble or dark wood.

---

## Footwear

### Sneaker

```text
blank white sneaker, floating in mid-air, dynamic studio lighting, clean grey background, apparel mockups, sharp focus, 8k resolution --ar 1:1 --no text
```

Removing ground contact avoids surface-shadow interpretation issues and lets the model render the sole and side profile at the same time. Multiple studio light sources reduce single-shadow harshness while still defining panel seams and sole texture.

**Variants:** change the colorway · add a visible tread pattern · match the background to your brand's color palette.

---

## Building your own prompt

Every prompt above follows this structure, in this order:

`[Product] [Material/Finish], [Environment], [Lighting], [Camera Angle], [Style], --ar [Aspect Ratio] --no [Negative Terms]`

Name the material explicitly (glazed ceramic, brushed steel, waxed canvas) rather than relying on the product name alone — vague material terms are the most common reason output looks like the wrong substance. Pick a lighting description that matches the mood you want (soft/diffused for calm and even, dramatic/spotlight for contrast and depth) and stay consistent across a full product line so the catalog looks cohesive. 

For aspect ratio, use 1:1 for Shopify's default grid, 4:5 for Instagram, Pinterest, and most Etsy listings, and 16:9 for banners or wide lifestyle shots. Always generate at least four variations before picking a final image — the first result is rarely the strongest.

## Troubleshooting

If text or letters show up on the product, add `--no text` explicitly and regenerate — it's Midjourney's default tendency on blank surfaces, not a one-off glitch. If reflections look unrealistic, you likely have conflicting light source descriptions in the prompt; specify a single dominant light and direction. 

If the background feels too busy, trim the environment description down to one or two terms instead of stacking props. If the product gets cropped, check that the aspect ratio matches the subject's natural orientation — a tall bottle needs 4:5, not 16:9. 

If materials look plastic instead of what you intended, add an explicit material term rather than relying on the product name. If texture detail looks flat, switch from even lighting to directional or low-angle lighting, since shadows are what create the appearance of texture in the first place.

## FAQ

**Does this work in Midjourney V7?** Yes — these were written for V7 and remain compatible with V6. Minor adjustments may be needed as future versions change how they weight lighting and material keywords.

**Can I use the generated images commercially?** That depends on your Midjourney subscription plan. Check Midjourney's current terms, since licensing details can change between tiers and over time.

**Which aspect ratio should I use?** Match it to the destination platform: 1:1 for Shopify, 4:5 for Etsy/Instagram/Pinterest, 16:9 for banners and wide lifestyle shots.

**How do I stop unwanted text from appearing?** Add `--no text` at the end of the prompt. If it persists, the environment description may be implying a label — simplify it.
