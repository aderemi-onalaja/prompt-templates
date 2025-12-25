# Photorealistic Image Generation – JSON Prompt Template

Use this template for high-realism image generation.
Primary goal: **natural, photographic realism** (not illustration or stylised AI art).

Only modify:
- Subject details
- Environment
- **Camera / technical specifications**

---

## JSON Prompt Template

```json
{
  "generation_parameters": {
    "resolution": "1200x1200px",
    "quality": "8K Ultra HD",
    "seed_reference": "Seedream",
    "reference_inputs": {
      "face": "Natural facial features, realistic proportions (no exaggeration)",
      "wardrobe": "Realistic outfit appropriate to setting (natural fit, not stylised)"
    }
  },

  "subject_details": {
    "pose": {
      "body": "[Describe natural body position]",
      "hands": "[Describe what hands are doing]",
      "orientation": "[Describe angle to camera]"
    },
    "expression": {
      "mood": "[Emotion or vibe]",
      "eyes": "[Eye contact or gaze direction]",
      "lips": "[Neutral / subtle expression]"
    },
    "appearance": {
      "hair": "[Hair style and condition]",
      "makeup": "[Minimal / natural unless specified]"
    }
  },

  "environment": {
    "setting": "[Real-world location]",
    "decor": "[Key environmental details]",
    "atmosphere": "[Lighting, mood, weather, ambience]"
  },

  "technical_specifications": {
    "camera_gear": "[CAMERA MODEL – e.g. iPhone 17 Pro Max, Leica Q3, Canon R5]",
    "lens": "[Lens or equivalent focal length]",
    "settings": "[ISO, shutter speed, aperture, white balance]",
    "computational_features": [
      "[HDR / Deep Fusion / Portrait depth / etc – if applicable]"
    ],
    "lighting_style": {
      "type": "[Natural light / flash / mixed]",
      "effects": "[How light interacts with subject and environment]",
      "aesthetic": "[Overall lighting character]"
    },
    "focus": "[What is sharp vs softly out of focus]"
  },

  "visual_style": {
    "genre": "[Travel photography / documentary / lifestyle / editorial]",
    "color_palette": "[Dominant natural colours]",
    "mood_keywords": [
      "[Keyword 1]",
      "[Keyword 2]",
      "[Keyword 3]"
    ]
  }
}
