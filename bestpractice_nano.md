**Nano Banana Pro** (officially known as **Gemini 3 Pro Image**) is Google's state-of-the-art image generation and editing model. Unlike older models that just "draw" what you say, this model "thinks" before it generates—meaning it can plan layouts, spell text correctly, and understand complex logic.

Here is the best way to use it, including a structured framework for your prompts and examples.

---

### **1. The Golden Rule: Use "Thinking Mode" & Structure**
Because Nano Banana Pro has a reasoning engine, it works best when you treat it like a professional designer rather than a slot machine. It excels when you give it a **Job to Do** rather than just a list of keywords.

#### **The Prompt Structure Formula**
Use this formula to get consistent, high-quality results:

> **[Role/Intent]** + **[Subject & Action]** + **[Context/Setting]** + **[Technical Specs]** + **[Text/Data Constraints]**

*   **Role/Intent:** What is the image for? (e.g., "A movie poster," "A wiring diagram," "A product macro shot").
*   **Subject:** Who or what is the focus? Be descriptive.
*   **Context:** Where are they? What is the lighting?
*   **Technical Specs:** Camera angle, art style, aspect ratio (e.g., "16:9 cinematic," "flat vector art").
*   **Constraints:** Specific text to write, colors to avoid, or reference images to use.

---

### **2. Key Guidelines for Maximum Performance**

#### **A. Text is Finally Usable**
Unlike Midjourney or older DALL-E versions, Nano Banana Pro can render perfect text.
*   **Guideline:** Explicitly state the text and the font style.
*   *Bad:* "A sign that says welcome."
*   *Good:* "A neon sign hanging in a window. The text 'OPEN LATE' is written in bright pink cursive script. Ensure the spelling is correct and legible."

#### **B. Use "Search Grounding" for Accuracy**
This model can browse the web to get details right.
*   **Guideline:** Ask it to use real-world data.
*   *Example:* "Generate an infographic showing the anatomy of a 1967 Ford Mustang engine. Use search grounding to ensure the placement of the alternator and fan belt is historically accurate."

#### **C. Reference Images (The "14-Image" Context)**
You can upload up to 14 reference images. This is powerful for keeping characters consistent.
*   **Guideline:** Label your uploaded images in the prompt.
*   *Example:* "Use [Image A] as the character reference. Put this character into the pose shown in [Image B]. Change the background to a forest."

#### **D. Positive Framing > Negative Prompts**
The model responds better to being told *what to do* rather than what *not* to do.
*   *Avoid:* "No blurry background, no bad hands."
*   *Use:* "Ensure the background is sharp and in focus. Render hands with anatomically correct fingers and distinct joints."

---

### **3. Sample Prompts by Use Case**

Here are copy-paste templates you can adapt.

#### **Use Case 1: Marketing & Product Photography**
*This prompts for high fidelity and specific branding.*
> **Prompt:**
> "Create a luxury product shot for a high-end organic honey brand.
> **Subject:** A hexagonal glass jar of golden honey sitting on a polished dark wood table.
> **Lighting:** Golden hour sunlight streaming from the left, creating soft shadows and highlighting the texture of the honey.
> **Text:** The label on the jar should read 'PURE GOLD' in a clean, serif white font.
> **Style:** Photorealistic, 85mm lens, f/1.8 aperture, cinematic lighting. High resolution, 4k."

#### **Use Case 2: Educational Infographics (Text-Heavy)**
*This leverages the model's ability to plan layouts.*
> **Prompt:**
> "Design a vertical educational infographic explaining the water cycle for grade school students.
> **Layout:** Divide the image into four clear sections connected by arrows.
> **Content:**
> 1. Top: Sun heating the ocean (Label: 'Evaporation').
> 2. Middle: Clouds forming (Label: 'Condensation').
> 3. Bottom: Rain falling on mountains (Label: 'Precipitation').
> 4. Base: Water flowing into a river (Label: 'Collection').
> **Style:** Flat vector illustration style, bright pastel colors, clean sans-serif text. Ensure all labels are spelled correctly."

#### **Use Case 3: Character Consistency (Storyboarding)**
*Requires uploading a reference image of a character first.*
> **Prompt:**
> "Using the character from the uploaded reference image [Image 1], create a wide-angle action shot.
> **Action:** The character is running through a cyberpunk neon alleyway, looking over their shoulder in fear.
> **Consistency:** Keep the exact same green jacket and facial features as the reference image.
> **Atmosphere:** Rainy, dark, illuminated by blue and purple neon signs.
> **Style:** Graphic novel style, cel-shaded."

#### **Use Case 4: Editing / In-painting**
*Use this when you want to change an existing image.*
> **Prompt:**
> "Change the background of this uploaded photo.
> **Instruction:** Replace the busy city street with a calm, blurred beach at sunset.
> **Lighting:** Adjust the lighting on the subject to match the warm orange glow of the sunset behind them.
> **Constraint:** Do not change the subject's face or clothing."

---

### **4. Advanced Technique: The "Thinking" Prompt**

Since Nano Banana Pro has a "reasoning" phase, you can ask it to plan before it draws. This is unique to this model.

**Try starting your prompt with:**
> "Analyze the request to create a diagram of a jet engine. First, determine the correct major components needed for accuracy. Then, generate a cross-section diagram labeling the Intake, Compression, Combustion, and Exhaust stages. Ensure the visual flow is logical from left to right."

**Summary Checklist for Success:**
1.  **Did you specify the text?** (If text is needed).
2.  **Did you define the lighting/camera?** (e.g., "Cinematic," "Macro").
3.  **Did you upload references?** (For consistent characters/styles).
4.  **Is it positive?** (Describe what you want, not what you don't want).
