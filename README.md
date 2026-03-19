# ai-workshop-documentation

Exploration of AI as a design material through prompt engineering, dataset curation, and LoRA training. Focus on semantic gap, facture, and connectionist learning.

---

## AI Workshop Documentation  
Anubhuti Raj | UX Design Student @ ESAD Orléans

---

## Project Overview

This project explores AI not as a tool, but as a design material.  
Through prompt engineering, dataset curation, and LoRA training, it investigates how generative models interpret visual logic, texture, and meaning.

The work focuses on:
- The semantic gap between text and image  
- The role of facture (texture, rhythm, materiality)  
- The shift from symbolic AI to connectionist learning  

---

## Intent and Approach

Instead of treating AI as an image generator, this project approaches it as a system that learns visual language through data.

The goal was to:
- Understand how AI perceives and reconstructs images  
- Explore how datasets influence outputs  
- Train models to capture both objects and artistic styles  
- Extend this into speculative design within a fictional world  

---

## Key Concepts

- Connectionism: AI learns through patterns and statistical relationships  
- Latent Space: A multi dimensional space where visual concepts exist  
- Semantic Gap: The disconnect between language (prompt) and image (output)  
- Facture: The physical and visual texture of an image  
- LoRA (Low-Rank Adaptation): A lightweight training method to teach models new subjects or styles  

---

## Exercise 1: Bridging the Semantic Gap

### Goal  
To learn how to translate visual perception into precise prompts.

### Process  
- Analyzed reference images  
- Broke them down into lighting, material textures, and composition  
- Converted observations into structured prompts  

### Key Learning  
AI outputs are heavily influenced by statistical bias.  
Without specificity, the model defaults to generic representations.

Detailed prompting and negative prompting are necessary to control output.

---

## Exercise 2: Subject Training (Yellow Flower Clip)

### Goal  
To train a LoRA on a physical object and understand how AI learns form and scale.

### Dataset  
- 12 curated images  
- Varied angles (macro, profile, in use)  
- Controlled lighting  
- Trigger word: `yellowflowerclip`

### Challenges  
- Scale distortion: object appearing disproportionately large  
- Lack of environmental context  

### Iteration  
- Refined annotations (.txt files)  
- Added contextual descriptions (size, surroundings)  

### Insight  
The model learns from labels, not intention.  
Precise annotation directly impacts accuracy.

---

## Exercise 3: Style Training (Madhubani / mdhstyll)

### Goal  
To train a LoRA on an artistic style rather than a physical object.

### Dataset  
- 15 Madhubani artworks  
- Focus on color palettes, line patterns, and graphic density
- Trigger word: `mdhstyll` 

### Iterations  

First run:
- Captured color  
- Failed to replicate line quality  

Second run:
- Improved dataset consistency  
- Refined annotations (patterns, line weights, geometry)  

### Outcome  
The model successfully applied Madhubani style to new subjects.

Style is learned through repetition, consistency, and density of visual features.

---

## Final Project: Speculative Worldbuilding with AI (Tumbbad)

### Concept

The final project is inspired by the fictional universe of Tumbbad.

This world contains:
- A hidden underground cave  
- A mysterious creature that produces gold coins  
- A dark, wet, and dangerous environment  

Humans enter this space secretly to collect gold, navigating risk and uncertainty.

---

### Design Question

How can AI generate objects that belong to a specific fictional world?

Instead of designing objects manually, AI is used to:
- Learn the visual language of the world  
- Generate artifacts that could exist within it  

---

### Methodology

#### Training LoRA 1: Environment Model

A LoRA was trained on the Tumbbad universe to capture:
- Lighting conditions (low visibility, warm gold tones)  
- Materials (mud, stone, wet surfaces)  
- Atmosphere (dense, claustrophobic, eerie)  

This model encodes the environmental logic.

---

#### Training LoRA 2: Artifact Model

A second LoRA was trained on objects such as:
- Gloves  
- Containers  
- Lanterns  
- Utility tools  

The dataset emphasized:
- Functionality  
- Material response (metal, leather, wear)  
- Interaction with environment  

---

#### Generative Exploration

Both LoRAs were combined to generate contextual artifacts.

---

### Example Output: Gold Gauntlet

The first generated object was a gold gauntlet:
- A protective glove for collecting coins  
- Prevents direct contact with the creature  
- Reflects environmental constraints  

This object emerges as a response to the world rather than a purely aesthetic design.

---

### Further Object Exploration

Additional generated artifacts include:
- Containers for storing gold coins  
- Lanterns for navigation  
- Tools for extracting and collecting gold  

Each object reflects survival needs, environmental adaptation, and material logic.

---

## Final Reflection

This project demonstrates that:
- AI can act as a co-designer when guided properly  
- Design shifts from creating to curating datasets and constraints  
- Fictional worlds can serve as frameworks for generative design  

AI does not imagine; it recombines.  
The role of the designer is to define the rules of imagination.

---

## Repository Structure

- [exercise1_prompting](./exercise1_prompting)
- [exercise2_subject_lora](./exercise2_subject_lora)
- [exercise3_style_lora](./exercise3_style_lora)
- [final_project_tumbbad](./final_project_tumbbad)

---

## Conclusion

This workshop reframes AI from a tool into a material system.

It highlights a shift in design practice:
Designing not outputs, but systems that generate outputs.
