### **Phase 1: The "Master Blueprint" (Do This First)**

Before you make the character drive or celebrate, you need a **Character Model Sheet**. In game design, this is called an "Orthographic View." This image will serve as the "Truth" for all future generations.

**The Goal:** A flat, shadow-less view of the character from Front, Side, and Back.

**Sample Prompt for the Blueprint:**
> "Create a professional character design model sheet (turnaround) for a video game character.
> **Subject:** A cute, energetic 10-year-old girl race car driver. She is wearing a futuristic, bright orange and white racing suit with a star logo on the chest. She has goggles resting on her forehead and messy blue hair.
> **Views:** Generate three distinct views side-by-side: 1. Front View (T-pose), 2. Side Profile View, 3. Back View.
> **Style:** Vibrant 3D Pixar-style animation render, clean lines.
> **Lighting:** Flat, neutral studio lighting (no heavy shadows) to reveal all details.
> **Background:** Pure white background."

**Why this works:**
*   **Neutral Lighting:** Prevents baked-in shadows that look weird when you move the character to a night track.
*   **Three Views:** Gives the AI (and you) a 360-degree understanding of the costume.

**Action:** Once you generate a result you love, **save it immediately.** This is your "Source Image."

---

### **Phase 2: The "Digital Costume" Technique (Consistency)**

Now you want to put this character in different lighting (e.g., a night race) or change their outfit.

**The Workflow:**
1.  **Upload** your "Master Blueprint" from Phase 1 into the prompt box.
2.  Tell Nano Banana to "Use this character."

**Sample Prompt for Changing Environment/Lighting:**
> "[Upload Master Blueprint here]
> **Role:** Use the character in the attached image as the reference. Maintain strictly consistent facial features, hair color, and racing suit details.
> **Action:** The character is sitting in a small go-kart, gripping the steering wheel tight, looking ahead with determination.
> **Setting:** A neon-lit cyberpunk race track at night.
> **Lighting:** Pink and blue neon lights reflecting off her helmet and suit.
> **Style:** Keep the same Pixar-style 3D render as the reference."

**Sample Prompt for Changing Costumes (e.g., Winter Track):**
> "[Upload Master Blueprint here]
> **Role:** Use the character in the attached image as the base.
> **Modification:** Keep her face and hair exactly the same, but change her outfit to a 'Winter Racing' theme.
> **Outfit Details:** Add a thick fluffy scarf, a beanie over her blue hair, and a thicker insulated version of her orange racing suit.
> **Pose:** Standing victoriously holding a trophy."

---

### **Phase 3: Creating Game Assets (Sprites/UI)**

Since this is a simple racing game, you likely need "Sprites" (2D images) or UI elements (faces for the leaderboard).

#### **Scenario A: The "Headshot" (For UI/Health Bars)**
> "[Upload Master Blueprint]
> Create a UI character icon based on this reference.
> **Subject:** A close-up square portrait of the character's face smiling.
> **Style:** 2D vector art sticker style with a thick white outline (for easy cutting).
> **Background:** Solid green background (easy to remove)."

#### **Scenario B: The "Kart Sprite" (For the actual gameplay)**
If your game is top-down or isometric (like old Mario Kart or Zelda):
> "[Upload Master Blueprint]
> Generate an isometric game sprite of this character driving her go-kart.
> **Angle:** 45-degree top-down view.
> **Vehicle:** A chunky, cartoonish go-kart matching her orange and white color scheme.
> **Background:** Pure solid black background."

---

### **Guidance for You & Your Daughter**

To make the most of this during your coding sessions:

1.  **Iterate on the Text, Not the Image:** When designing the Master Blueprint, ask Nano Banana to check the spelling of any logos.
    *   *Prompt:* "Ensure the text 'TURBO' is written clearly on the back of the jacket."
2.  **Define the "Art Bible":** Decide on a style keyword and use it in **every single prompt**.
    *   Examples: "Low-poly 3D," "16-bit Pixel Art," "Claymation," or "Disney/Pixar style."
3.  **Don't worry about transparency yet:** Nano Banana Pro generates rectangular images. You will need to use a free tool (like Adobe Express background remover or simply "Remove.bg") to make the backgrounds transparent before putting them into your game engine.

### **Summary Checklist for Your Game Character**
1.  **Step 1:** Generate the **Model Sheet** (Front/Side/Back).
2.  **Step 2:** **Upload** that sheet for every subsequent prompt.
3.  **Step 3:** Describe the **New Context** (Night, Snow, Desert) while asking for "Strict Character Consistency."
