# zhxu0527_9103_tut9

## Part 1: Imaging Technique Inspiration

---

### Selected Technique: Interactive Geometric Scaling
> **Inspiration:** Interactive generative art using radial symmetry to create complex, mandala-like patterns.

![Image 1](readmeImages/image_1.jpg)
![Image 2](readmeImages/image_2.jpg)

**Discussion:**
I am inspired by interactive generative art that uses radial symmetry to create complex, mandala-like patterns. The specific aspect I want to incorporate is the **dynamic scaling mechanic** driven by user input. By moving the mouse or clicking, the geometric layers expand and contract, mimicking a breathing organism or a shifting lens. 

This technique is beneficial because it creates a highly responsive feedback loop, fulfilling the **"User Input"** mechanic requirement. It transforms simple mathematical lines into an immersive visual experience that encourages users to explore the relationship between movement and scale.

---

## Part 2: Coding Technique Exploration

---

### 💻 Selected Tool: p5.js (Mapping Function)

![Code Screenshot 1](readmeImages/coding_1.jpg)
![Code Screenshot 2](readmeImages/coding_2.jpg)

**Discussion:**
This coding technique is essential for my "User Input" mechanic. By using `let dynamicScale = map(mouseX, 0, width, 0.5, 3.0);`, I can translate the mouse's horizontal position into a multiplier for the radii of my geometric shapes. 

This allows for a **fluid transition** where the entire mandala grows or shrinks as the user moves their cursor. Using mapping ensures the interaction feels natural and constrained within a visual range that maintains the artistic integrity of the piece, making the complex scaling from Part 1 technically achievable.

### 🔗 Resources
* **Example Implementation and Code:** [p5.js Mouse Functions Reference](https://p5js.org/reference/p5/mousePressed/)