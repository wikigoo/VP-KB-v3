---
title: "Universal AI Image Generation Workflow: Cross-Platform Guide"
subtitle: "Master image creation across DALL-E, Midjourney, Stable Diffusion, and more"
date: 2025-10-31
categories: [AI-Chatbot, Writing]
tags: [guide, ai-assisted, workflow, intermediate, chatgpt, gemini, image-generation]
description: >
  Complete step-by-step workflow for generating professional-quality images using AI platforms. Covers platform selection, prompt engineering, refinement techniques, and quality assurance across DALL-E 3, Midjourney, Stable Diffusion, Gemini, and Flux.
toc: true
---

# Universal AI Image Generation Workflow: Cross-Platform Guide

> **Purpose:** Learn to generate professional-quality AI images efficiently across multiple platforms. This comprehensive workflow covers platform selection, prompt engineering, iterative refinement, and quality assurance. Prerequisites: Basic descriptive language skills, willingness to iterate, and access to at least one AI image generation platform.

---

## Overview

AI image generation has evolved from experimental research tools to production-ready creative platforms. Whether you need photorealistic imagery for journalism, stylized graphics for social media, or conceptual visuals for presentations, modern AI tools can deliver professional results in minutes rather than days.

This guide provides a universal workflow that adapts to your specific needs while working across platforms including DALL-E 3, Gemini 2.0 Flash, Midjourney, Leonardo AI, Stable Diffusion 3.5, and Flux. Each platform has distinct strengths: DALL-E 3 excels at natural language understanding, Gemini enables conversational editing, Midjourney offers superior style consistency, and Stable Diffusion provides maximum technical control.

**What You'll Accomplish:**
- Generate professional images in 5-30 minutes
- Select optimal platforms for specific requirements
- Structure effective prompts using proven formulas
- Apply platform-specific refinement techniques
- Troubleshoot common issues systematically
- Document workflows for reproducible results

**Prerequisites:**
- Account on chosen platform (ChatGPT Plus $20/month for DALL-E 3, free Google account for Gemini/Imagen, Midjourney subscription $10-$120/month, or Stable Diffusion setup requiring 8GB+ VRAM GPU)
- Web browser (Chrome/Firefox recommended)
- Stable internet connection (10+ Mbps)
- Optional: Reference images in .png, .jpg, .gif, or .webp format

**Time Estimates:**
- Simple generation: 5-10 minutes
- Complex with refinement: 15-30 minutes  
- Production-ready professional: 30-60 minutes

> **Key Terms:**
> - **Prompt**: Text description that guides image generation
> - **Parameters**: Platform-specific settings (aspect ratio, quality, style)
> - **Iteration**: Refinement cycle to improve generated images
> - **Seed**: Number controlling randomness for reproducible results
> - **CFG Scale**: Classifier-Free Guidance scale controlling prompt adherence
{: .prompt-info }

---

## Step-by-Step Guide

### Step 1: Select and Configure Optimal Platform

Understanding each platform's strengths ensures you start with the right tool for your specific requirements, saving time and reducing iterations.

1. **Match requirements to platform capabilities**

   Analyze your priority factors:
   
   - **Speed Priority**: Flux (20-30 seconds), Gemini 2.0 Flash (10-30 seconds), Imagen 4 Fast (3-5 seconds)
   - **Quality Priority**: Stable Diffusion 3.5 with 40-50 steps, Imagen 4 Ultra, DALL-E 3
   - **Text Rendering**: Imagen 3/4 (95% accuracy), DALL-E 3 (85% accuracy)
   - **Ease of Use**: DALL-E 3 (automatic prompt enhancement), Gemini (conversational interface)
   - **Style Control**: Midjourney (style tuner with --stylize 0-1000), Stable Diffusion (LoRA models)
   
   **Expected**: Clear understanding of which platform suits your needs

2. **Configure platform-specific settings**

   **For DALL-E 3 via ChatGPT:**
   ```plaintext
   Access: web.openai.com
   Configuration: Automatic (no manual settings)
   Cost: Included with ChatGPT Plus
   Time: <1 minute setup
   ```

   **For Gemini 2.0 Flash:**
   ```plaintext
   Access: aistudio.google.com or gemini.google.com
   Model: Select "Gemini 2.0 Flash Experimental (Image Generation)"
   Cost: Free with Google account
   Time: <1 minute setup
   ```

   **For Midjourney:**
   ```plaintext
   Access: Discord server or midjourney.com/imagine
   Command: Always prefix prompts with /imagine prompt:
   Time: 2-3 minutes initial setup
   ```

   **For Leonardo AI:**
   ```plaintext
   Access: leonardo.ai
   Model: Phoenix or Leonardo Diffusion XL
   PhotoReal: Toggle ON for realistic content
   Alchemy: Toggle ON for quality enhancement
   Guidance Scale: 7 (creative) to 12 (precise)
   Time: 2-3 minutes setup
   ```

   **For Stable Diffusion 3.5:**
   ```plaintext
   Sampler: DPM++ 2M Karras
   Steps: 25-35 (fast), 40-50 (quality)
   CFG Scale: 7-9 (balanced), 10-12 (strict)
   Resolution: 1024x1024 base
   Time: 3-5 minutes setup
   ```
   
   > ⚠️ **Warning:** Higher step counts increase generation time exponentially. Steps 50+ can take 2-3 minutes on slower systems.
   {: .prompt-warning }

   **For Flux:**
   ```plaintext
   Model: Flux.1-dev (quality) or Schnell (speed)
   Steps: 20-30
   Guidance: 3.5-7
   Time: 1-2 minutes setup
   ```

3. **Verify platform readiness**

   Test with simple prompt: "professional photograph of a red apple"
   
   - Check generation completes without errors
   - Verify interface is responsive
   - Confirm remaining credits/generations

**✓ Checkpoint:** Platform loads correctly, test image generates successfully within 30-60 seconds  
**Verify:** You can view and download the test image

> 💡 **Tips:**
> - Bookmark your preferred platforms for quick access
> - Keep multiple platforms ready - switch if one has issues or outages
> - Check platform status pages before starting critical projects
{: .prompt-info }

---

### Step 2: Structure Your Core Prompt

Effective prompts follow a hierarchical formula that ensures all critical visual elements are specified while maintaining clarity.

1. **Build base prompt using universal formula**

   Structure: `[STYLE 10%] + [SUBJECT 30%] + [COMPOSITION 20%] + [LIGHTING 15%] + [TECHNICAL 15%]`
   
   - Word count: 15-40 words (optimal), maximum 75 words
   - Time required: 3-5 minutes for first draft

2. **Define each component with specific language**

   **STYLE (10% of prompt weight):**
   - Photography: "professional photography", "documentary photograph", "editorial photo"
   - Artistic: "oil painting", "watercolor", "digital art", "3D render"
   - Cinematic: "cinematic scene", "movie still", "Hollywood production"
   - Hyperrealistic: "hyperrealistic", "photorealistic", "ultra-detailed"

   **SUBJECT (30% - most important):**
   - Use specific numbers: "three cats" NOT "cats" or "multiple cats"
   - Add descriptors: "three orange tabby cats" NOT just "three cats"
   - Include action: "three orange tabby cats playing with yarn"
   - Avoid negatives: Say "peaceful scene" NOT "scene without violence"

   **COMPOSITION (20%):**
   - Framing: "centered composition", "rule of thirds", "left third placement"
   - Perspective: "eye-level view", "bird's eye view", "low angle shot"
   - Distance: "close-up", "medium shot", "wide establishing shot"
   - Aspect ratio: 1:1 (square), 16:9 (landscape/video), 9:16 (portrait/mobile), 4:5 (social media)

   **LIGHTING (15%):**
   - Natural: "golden hour sunlight", "overcast daylight", "soft window light"
   - Studio: "three-point lighting", "dramatic studio lighting", "soft shadows"
   - Mood: "warm lighting", "cool blue tones", "high contrast lighting"

   **TECHNICAL (15%):**
   - Resolution: "8K resolution", "4K quality", "high resolution"
   - Camera: "shot with 85mm lens", "shallow depth of field", "bokeh background"
   - Quality: "professional quality", "masterpiece", "award-winning photography"

3. **Add platform-specific syntax**

   **DALL-E 3:**
   ```plaintext
   Use natural conversational language
   Let auto-enhancement work (don't over-specify)
   
   Example: "A professional photograph of three orange tabby cats 
   playing with blue yarn on a wooden floor, warm natural lighting, 
   shot with 85mm lens creating soft background blur, cozy home setting"
   ```

   **Midjourney:**
   ```plaintext
   Add parameters at end with double-dash
   No spaces in parameter values
   
   Example: "professional photograph three orange tabby cats playing 
   with yarn, warm lighting, 85mm lens, cozy home --ar 16:9 --v 6 --q 2"
   
   Common parameters:
   --ar 16:9 (aspect ratio)
   --v 6 (version)
   --q 2 (quality)
   --s 750 (stylize)
   --iw 1.5 (image weight)
   ```
   
   > ⚠️ **Warning:** Parameter syntax is strict. `--ar16:9` (no space) is incorrect and will fail.
   {: .prompt-warning }

   **Stable Diffusion:**
   ```plaintext
   Main prompt: Positive descriptors only
   
   Negative prompt: "bad anatomy, deformed, mutated, extra limbs, 
   malformed hands, poorly drawn face, low quality, blurry"
   
   Use emphasis: (keyword:1.3) for 30% more weight
   
   Example: "professional photograph, three orange tabby cats, 
   playing with blue yarn, wooden floor, warm natural lighting, 
   85mm lens, shallow depth of field, cozy home interior, 
   high resolution, masterpiece"
   ```

   **Gemini:**
   ```plaintext
   Start with action phrase
   
   Example: "Create an image: Professional photograph of three 
   orange tabby cats playfully tangled in blue yarn on a warm 
   wooden floor, natural sunlight streaming through a window, 
   shot with 85mm lens for beautiful background blur, cozy home setting"
   ```

4. **Document complete prompt before generation**

   - Copy to text file or notes app
   - Include platform name and settings
   - Save for iteration reference
   - Time: 1 minute

**✓ Checkpoint:** Complete prompt written with all 5 components, platform syntax correctly applied, saved for reference  
**Verify:** Read prompt aloud - does it paint a clear mental picture?

> 💡 **Tips:**
> - Start with subject, work outward (subject → lighting → style → technical)
> - Use power words: "stunning", "dramatic", "professional", "award-winning"
> - Front-load important details (first 5 words have strongest influence in most platforms)
> - Test on simple subjects before attempting complex multi-element scenes
{: .prompt-info }

---

### Step 3: Add Reference Images (Optional but Recommended)

Reference images guide composition, style, and visual elements more precisely than text alone, especially for complex poses or specific aesthetic requirements.

1. **Prepare reference images**

   ```plaintext
   Format: .png, .jpg, .jpeg, .gif, .webp
   Size: Under 10MB for most platforms
   Resolution: Minimum 512x512, optimal 1024x1024
   Quality: Clear, well-lit, uncompressed preferred
   Time: 2-3 minutes for preparation
   ```

2. **Upload/link by platform**

   **Midjourney:**
   - Web: Click image icon in Imagine bar, select files
   - Discord: Upload to Discord, right-click → Copy Link, paste URL at prompt start
   - Multiple images: Separate each URL with space
   
   ```plaintext
   Example: https://image1.jpg https://image2.jpg professional photograph of cats
   Time: 1-2 minutes
   ```

   **DALL-E 3 via ChatGPT:**
   - Click paperclip icon, select image
   - Add text description after image
   - Multiple images: Upload all at once
   - Time: 1-2 minutes

   **Stable Diffusion:**
   - img2img tab: Drop image in canvas
   - Denoising strength: 0.4-0.6 (light modification), 0.7-0.9 (heavy change)
   - ControlNet: For composition/pose control (advanced)
   - Time: 2-3 minutes

   **Gemini:**
   - Upload via file icon
   - Describe changes: "Make this image [description]"
   - Time: 1 minute

3. **Adjust reference influence**

   Control how strongly the reference affects the output:
   
   - **Midjourney**: `--iw 0.5` (subtle), `--iw 1` (default), `--iw 2-3` (strong)
   - **Stable Diffusion**: Denoising 0.3-0.5 (preserve original), 0.6-0.8 (major changes)
   - **Crop tip**: Match reference aspect ratio to desired output

4. **Describe relationship between references and prompt**

   Be explicit about how each reference should influence the output:
   - "Use first image for composition, second for color palette"
   - "Match the lighting style of this reference"
   - "Keep the pose from this image but change background"

**✓ Checkpoint:** Reference images uploaded successfully, influence level set appropriately  
**Verify:** Image thumbnails visible in interface, no upload errors

> 💡 **Tips:**
> - Use references for complex poses/compositions difficult to describe in text
> - Combine 2-3 references to merge different elements (style + subject + composition)
> - Screenshot desired layouts from other AI outputs as composition guides
> - For Midjourney: Lock reference images to reuse across multiple prompts
{: .prompt-info }

> ⚠️ **Common Issue:** If image won't upload, check file size <10MB and convert to .jpg if needed
{: .prompt-warning }

---

### Step 4: Generate Initial Image

Execute the generation with platform-specific methods, monitor progress, and review all variations produced.

1. **Submit prompt using platform-specific method**

   **DALL-E 3:**
   ```plaintext
   Action: Press Enter or click Send
   Generation time: 30-60 seconds
   Output: 1 image (1024x1024, 1792x1024, or 1024x1792)
   ```

   **Gemini 2.0 Flash:**
   ```plaintext
   Action: Click Generate or press Enter
   Generation time: 10-30 seconds
   Output: 1-4 variations
   ```

   **Midjourney:**
   ```plaintext
   Action: Press Enter after /imagine prompt:
   Generation time: 40-60 seconds
   Output: 4 variations in grid
   Next: Click U1-U4 to upscale preferred version
   ```

   **Leonardo AI:**
   ```plaintext
   Action: Click Generate Images button
   Generation time: 30-90 seconds
   Output: Number set in settings (default 4)
   ```

   **Stable Diffusion:**
   ```plaintext
   Action: Click Generate button
   Generation time: 
     - Steps 25-35: 30-60 seconds
     - Steps 40-50: 60-120 seconds
   Output: Batch count as configured (default 1)
   ```
   
   > ⚠️ **Warning:** High step counts (50+) can timeout on slower systems. Start with lower values for testing.
   {: .prompt-warning }

   **Flux:**
   ```plaintext
   Action: Click Generate
   Generation time: 20-30 seconds
   Output: 1-4 images based on settings
   ```

2. **Monitor generation progress**

   - Watch progress bar/loading indicator
   - Note any error messages immediately
   - Don't close browser tab during generation
   - Track actual generation time for future estimation

3. **Review all generated variations**

   - Open each image at full size
   - Check for artifacts, errors, or unexpected elements
   - Compare against mental vision of desired result
   - Identify closest match to requirements
   - Time: 2-3 minutes for thorough review

**✓ Checkpoint:** Image(s) generated without errors, visible in interface, at least one usable variation present  
**Verify:** You can click/download image successfully without corruption

> 💡 **Tips:**
> - Generate 4 variations at once (when possible) to compare options
> - Save generation seed numbers (Midjourney, SD) for reproducibility
> - Screenshot unexpected but interesting results for reference library
> - Document what worked and what didn't for prompt refinement
{: .prompt-info }

---

### Step 5: Refine and Iterate

Systematic refinement addresses specific issues while preserving successful elements, leading to professional results in 2-5 iterations.

1. **Analyze generated image systematically**

   Check each quality dimension:
   - **Composition**: Framing and perspective correct?
   - **Subject accuracy**: All elements present and correct?
   - **Quality**: Resolution, sharpness, artifacts?
   - **Colors**: Match description and mood?
   - **Lighting**: As specified?
   - **Anatomy**: Hands, faces, proportions correct?
   - **Style**: Consistent throughout?
   
   Time: 2-3 minutes for thorough analysis

2. **Apply platform-specific refinement techniques**

   **DALL-E 3 (Conversational Editing):**
   ```plaintext
   Direct modifications: "Make the sky darker"
   Additive changes: "Add mountains in the background"
   Color changes: "Change the cats to black and white"
   Removal: "Remove the vase on the left"
   
   Time: 30-60 seconds per iteration
   Max iterations: ~5 before context loss
   ```

   **Gemini (Iterative Conversational):**
   ```plaintext
   Sequential edits: 
   "Change color to yellow" → 
   "Add trees around it" → 
   "Make it nighttime"
   
   Time: 10-30 seconds per edit
   Advantage: Very fast iteration cycle
   ```

   **Midjourney (Variation System):**
   ```plaintext
   V1-V4 buttons: Variations of selected image
   Vary (Strong/Subtle): Controlled changes
   Pan buttons: Extend image in any direction
   Zoom Out: Add context around image
   Modify prompt: For major changes
   
   Time: 40-60 seconds per variation
   Use --seed from original for consistency
   ```

   **Leonardo AI (Canvas Editor):**
   ```plaintext
   Inpainting: Select area, describe change
   Erase tool: Remove unwanted elements
   Expand canvas: Add content beyond borders
   Layer editing: Composite multiple generations
   
   Time: 2-5 minutes for manual editing
   ```

   **Stable Diffusion (Parameter Adjustment):**
   ```plaintext
   Increase CFG scale to 10-12 for better prompt adherence
   Add problems to negative prompt
   img2img with high denoising (0.7-0.9) for major changes
   Inpainting: Mask problem areas, regenerate only those
   
   Time: 2-3 minutes per regeneration
   ```

3. **Address common issues with specific fixes**

   **Anatomy Problems (Hands, Faces):**
   ```plaintext
   Prompt additions: "correct anatomy, natural proportions, 
   realistic human form, perfect hands"
   
   Negative prompt (SD): "bad anatomy, deformed hands, 
   mutated fingers, extra limbs"
   
   Increase CFG scale to 10-12
   Use reference image of correct anatomy
   Iterations needed: Usually 2-3 attempts
   ```

   **Text Rendering Issues:**
   ```plaintext
   Be explicit: "readable text saying '[exact text]' in [font style]"
   
   Best platforms: DALL-E 3/Imagen for text
   Specify: "clear calligraphy, legible text"
   Keep text short: Max 5-10 characters for best results
   Iterations needed: 3-5 attempts for complex text
   ```

   **Style Inconsistency:**
   ```plaintext
   Strengthen style terms: "(photorealistic:1.5)" for SD
   Midjourney: Increase --stylize value (default 100, max 1000)
   Place style at beginning of prompt (most influential position)
   Use style-specific LoRA models (SD)
   ```

   **Content Policy Blocks:**
   ```plaintext
   Rephrase sensitively:
   "battle" → "historical commemoration"
   "violence" → "conflict"
   "martyrdom" → "sacrifice"
   
   Add context: "artistic representation", 
   "cultural documentation", "educational purpose"
   
   Remove named individuals, use generic descriptions
   Iterations needed: 2-3 rephrase attempts
   ```

   **Poor Quality/Blurriness:**
   ```plaintext
   Add quality boosters: "professional quality, high resolution, 
   masterpiece, ultra-detailed, sharp focus"
   
   Increase steps (SD): From 25-35 to 40-50
   Enable quality settings:
     - Leonardo: Alchemy
     - Midjourney: --q 2
   
   Usually requires single regeneration
   ```

4. **Iterate systematically**

   - Change ONE element per iteration (isolate what works)
   - Save each version (don't overwrite)
   - Document what changes improved results
   - Stop when 80-90% satisfied (perfect = diminishing returns)
   - Typical iterations: 2-5 for good results
   - Time budget: 5-15 minutes total for refinement

**✓ Checkpoint:** Image meets minimum quality standards, major issues resolved, meets 80%+ of requirements  
**Verify:** Compare to original vision, check technical quality, confirm all critical elements present

> 💡 **Tips:**
> - Make bold changes early, fine-tune later in the process
> - Keep successful prompts and seed numbers for similar future projects
> - Use "remix" mode on Midjourney for controlled variation
> - Don't over-iterate - fresh start sometimes faster than endless tweaking
> - Compare variations side-by-side before committing to direction
{: .prompt-info }

---

### Step 6: Finalize and Export

Final quality assurance, upscaling if needed, proper file formatting, and documentation ensure reproducible professional results.

1. **Perform comprehensive quality check**

   Examine at 100% zoom:
   - **Resolution**: Check sharpness and detail
   - **Artifacts**: Look for distortions, duplications, weird textures (zoom to edges/corners)
   - **Composition**: Rule of thirds, visual balance, clear focal point
   - **Elements**: Count items if numbers specified, verify all requested items present
   - **Colors**: Accurate to description, proper saturation, no weird color casts
   - **Lighting**: Consistent direction, appropriate shadows, no impossible light sources
   - **Text**: If included, verify legibility and correct spelling
   - **Anatomy**: Check hands (correct finger count), faces, body proportions
   - **Context**: Background makes sense, no floating objects, appropriate scale
   
   Time: 3-5 minutes for thorough inspection

2. **Upscale for higher resolution (if needed)**

   **Midjourney:**
   ```plaintext
   Click Upscale button (U1-U4) on preferred grid image
   For higher: Use Upscale (2x) or Upscale (4x) buttons
   Final resolution: Up to 2048x2048 or higher
   Time: 30-60 seconds per upscale
   ```

   **Stable Diffusion:**
   ```plaintext
   Use SD Upscale script or RealESRGAN
   Settings: 4x-UltraSharp (recommended), scale by 2x-4x
   Time: 1-3 minutes depending on size
   ```

   **Leonardo AI:**
   ```plaintext
   Click Upscale button, select scale factor (2x or 4x)
   Enable "Add Details" for enhancement
   Time: 1-2 minutes
   ```

   **Imagen via API:**
   ```plaintext
   Request 2K resolution in initial generation
   No separate upscaling needed
   ```

3. **Download with appropriate settings**

   **Format Selection:**
   - **PNG**: Transparency needs, highest quality, larger file size
   - **JPG**: Standard use, smaller files, web optimization
   - **WebP**: Modern format, good compression (if workflow supports)

   **Naming Convention:**
   ```plaintext
   Include date: 2025-10-31_cats_playing
   Include platform: 2025-10-31_midjourney_cats
   Include version: 2025-10-31_cats_v3
   ```

   **Organization:**
   - Create project folders
   - Save by category or client
   - Keep originals separate from edited versions
   
   Time: 1-2 minutes

4. **Document for reproducibility**

   Save complete information:
   ```yaml
   Prompt: [Full prompt text with parameters]
   Platform: [DALL-E 3 / Midjourney / etc.]
   Settings: [All relevant configuration]
   Seed: [Number if applicable]
   Date: [YYYY-MM-DD]
   Reference Images: [File paths if used]
   ```
   
   Create prompt library:
   - Categorize by style, subject, platform
   - Tag for easy searching
   - Include thumbnails for visual reference
   - Use Notion, Obsidian, or spreadsheet
   
   Time: 3-5 minutes

5. **Verify embedded metadata (for authenticity tracking)**

   ```plaintext
   DALL-E 3: Check for C2PA watermark (invisible, in metadata)
   Imagen: Check for SynthID watermark
   View metadata: Use ExifTool or image properties
   ```
   
   > ⚠️ **Warning:** Screenshots and re-saves strip metadata. Download directly from platform.
   {: .prompt-warning }

**✓ Checkpoint:** Final image downloaded in correct format, quality verified at 100% zoom, prompt documented, files organized  
**Verify:** Open file outside browser, confirm resolution matches requirements, check appropriate file size

> 💡 **Tips:**
> - Download multiple versions as insurance (don't delete variations too quickly)
> - Keep master project file with all prompts and generations
> - Back up to cloud storage immediately (Google Drive, Dropbox)
> - For professional use: Maintain audit trail of all iterations
> - Test image in actual use context (website, print, presentation) before finalizing
{: .prompt-info }

---

## Examples

### Example 1: Professional Product Photography

**Context:** Need clean product shot for e-commerce listing, white background, professional lighting

**Platform:** DALL-E 3 (best for clean, professional results with minimal iteration)

**Prompt:**
```plaintext
Professional product photography of red wireless headphones on pure 
white background, studio lighting with soft shadows, shot with 
100mm macro lens, sharp focus on product, commercial photography 
quality, 8K resolution
```

**Result:** Generated professional product image in single attempt, no refinement needed

**Key Points:**
- Specified "pure white background" explicitly (critical for e-commerce)
- Used "studio lighting" for professional appearance
- Added "commercial photography quality" for production-ready output
- Single iteration because prompt was complete and specific

---

### Example 2: Editorial Illustration with Style Consistency

**Context:** Need illustrated portrait for article series, must match previous illustrations in style

**Platform:** Midjourney (superior style consistency with seed numbers)

**Initial Prompt:**
```plaintext
editorial illustration portrait of female scientist in lab coat, 
warm color palette, flat design style, minimal shading, 
professional illustration --ar 4:5 --v 6 --s 500
```

**Refinement:** After first generation, noted seed number (e.g., --seed 123456), used for next 10 portraits in series

**Follow-up Prompts:**
```plaintext
editorial illustration portrait of male engineer with blueprints, 
warm color palette, flat design style, minimal shading, 
professional illustration --ar 4:5 --v 6 --s 500 --seed 123456

editorial illustration portrait of young artist with paintbrush, 
warm color palette, flat design style, minimal shading, 
professional illustration --ar 4:5 --v 6 --s 500 --seed 123456
```

**Result:** Consistent style across entire article series

**Key Points:**
- Used seed number for style consistency across multiple generations
- Set stylize value (--s 500) for moderate artistic interpretation
- Kept prompt structure identical, only changed subject
- 4:5 aspect ratio perfect for article layouts

---

### Example 3: Iterative Photo Editing with Gemini

**Context:** Starting with existing photo, need to remove people and change time of day

**Platform:** Gemini 2.0 Flash (excels at conversational editing)

**Workflow:**
```plaintext
Initial: Upload photo of park with people

Edit 1: "Remove all the people from this photo"
Wait: 15 seconds
Result: Clean park scene

Edit 2: "Change it to golden hour lighting"
Wait: 15 seconds
Result: Warm sunset tones

Edit 3: "Add some autumn leaves on the ground"
Wait: 15 seconds
Result: Seasonal atmosphere added

Total time: 2 minutes for 3 major edits
```

**Key Points:**
- Sequential editing maintained context across changes
- Each edit took 15-30 seconds (very fast iteration)
- Conversational commands (no complex syntax needed)
- Preserved good elements while changing specific aspects

---

## Best Practices

**✅ Do These:**

- **Test prompts on simple subjects first** before attempting complex multi-element scenes
- **Save successful prompts** in organized library with thumbnails for future reference
- **Use specific numbers** ("three cats") instead of vague plurals ("cats")
- **Front-load important keywords** in first 5 words of prompt (highest influence)
- **Generate multiple variations** when possible to have options (4+ variations ideal)
- **Document seed numbers and settings** for reproducible results on similar projects
- **Make bold changes early** in iteration process, fine-tune details later
- **Verify at 100% zoom** before considering image final
- **Match aspect ratio** of reference images to desired output for best composition transfer
- **Use platform-specific strengths** (DALL-E for text, Midjourney for style, SD for control)

**❌ Avoid These:**

- **Over-specifying prompts** - let AI fill reasonable details (diminishing returns after 40-50 words)
- **Using negative phrasing** - say "peaceful scene" not "scene without violence"
- **Ignoring platform syntax** - wrong parameter format causes failures
- **Over-iterating past 80% satisfaction** - fresh start often faster than endless tweaking
- **Forgetting to save seed numbers** before moving to next generation
- **Mixing styles in single prompt** - "photorealistic watercolor painting" creates confusion
- **Using copyrighted terms** - "in style of [living artist]" will be blocked
- **Closing browser tabs during generation** - causes loss of unsaved work
- **Skipping documentation** - can't reproduce good results without saved prompts
- **Using only one platform** - different tools excel at different tasks

> 💡 **Pro Tip:** Create a "prompt pattern library" with your 10-20 most successful prompt structures. When starting new projects, adapt proven patterns rather than writing from scratch. This reduces iteration time by 50-70%.
{: .prompt-tip }

---

## Related Guides

**Prerequisites:**
- *AI Image Generation Actionable Guide* - Comprehensive platform comparison and capabilities reference

**Related Workflows:**
- *Platform-Specific Prompt Engineering Templates* - Deep dive into optimizing for each platform
- *AI-Assisted Content Creation Workflow* - Integrating image generation into broader content pipelines

**Next Steps:**
- *Advanced Stable Diffusion Techniques* - ControlNet, LoRA models, and custom training
- *Batch Processing AI Images for Production* - Scaling workflows for high-volume needs
- *Ethical AI Image Use Guidelines* - Copyright, attribution, and responsible practices

---

## References

**Official Documentation:**
- [OpenAI DALL-E Guide](https://platform.openai.com/docs/guides/images) - DALL-E 3 API and capabilities
- [Midjourney Documentation](https://docs.midjourney.com/) - Parameters and features reference
- [Google Imagen on Vertex AI](https://cloud.google.com/vertex-ai/docs/generative-ai/image/overview) - Imagen 3/4 technical specs
- [Stable Diffusion Guide](https://github.com/CompVis/stable-diffusion) - Open source documentation
- [Gemini API Documentation](https://ai.google.dev/gemini-api/docs/image-generation) - Image generation features

**Platform Comparisons:**
- [AI Image Generator Benchmark 2025](https://artificialanalysis.ai/models/image) - Performance metrics
- [Text-to-Image Model Comparison](https://huggingface.co/spaces/IDEA-Research/T2I-CompBench) - Quality benchmarks

**Best Practices:**
- [Prompt Engineering Guide](https://www.promptingguide.ai/) - Cross-platform techniques
- [AI Image Generation Ethics](https://www.wired.com/story/guide-ai-generated-art-images/) - Responsible use guidelines

---

## Quick Reference

| Task | DALL-E 3 | Midjourney | Stable Diffusion | Gemini | Best Choice |
|------|----------|------------|------------------|--------|-------------|
| Speed | 30-60s | 40-60s | 30-120s | 10-30s | **Gemini** |
| Text Rendering | 85% | 50% | 60% | 95% | **Gemini/Imagen** |
| Style Control | Low | **High** | **High** | Medium | **MJ/SD** |
| Ease of Use | **High** | Medium | Low | **High** | **DALL-E/Gemini** |
| Iterations | Good | **Best** | Good | **Fast** | **Depends** |
| Quality | **High** | **High** | **Highest** | High | **SD (config)** |
| Cost | $20/mo | $10-120/mo | Free-$$ | Free | **Gemini** |

### Common Parameters Quick Reference

**Midjourney:**
```plaintext
--ar 16:9        Aspect ratio (landscape)
--ar 9:16        Aspect ratio (portrait)
--v 6            Version 6
--q 2            Quality (higher = better)
--s 750          Stylize (0-1000)
--iw 1.5         Image weight (0-3)
--seed 12345     Reproducibility
```

**Stable Diffusion:**
```plaintext
Steps: 25-35     Fast generation
Steps: 40-50     Quality generation
CFG Scale: 7-9   Balanced prompt following
CFG Scale: 10-12 Strict prompt adherence
Denoising: 0.4-0.6   Light changes (img2img)
Denoising: 0.7-0.9   Heavy changes (img2img)
```

---

**Word Count:** 4,847  
**Last Updated:** 2025-10-31

---

## Internal Notes (For KB Organization)

**Alternative Search Terms:**
AI art generation, text-to-image guide, DALL-E tutorial, Midjourney workflow, Stable Diffusion guide, AI image creation, prompt engineering tutorial, generative AI images

**Common Questions This Answers:**
- "How do I generate professional AI images?"
- "What's the best AI image generator for [specific use case]?"
- "How do I improve my AI image prompts?"
- "Why are my AI images low quality?"
- "How do I get consistent results across multiple AI images?"
- "Which AI platform should I use for text rendering?"

**Quick Answer:**
Use platform-specific workflow (6 steps): Select platform based on needs → Structure prompt with 5-component formula → Add reference images → Generate → Refine iteratively → Finalize and document. DALL-E for ease, Midjourney for style, SD for control, Gemini for speed.