# zhxu0527_9103_tut9

## Part 1: Imaging Technique Inspiration

![Image 1](readmeImages/Image 1.jpg)
![Image 2](readmeImages/Image 2.jpg)

**Discussion:**
I am inspired by interactive generative art that uses radial symmetry to create complex, mandala-like patterns. The specific aspect I want to incorporate is the dynamic scaling mechanic driven by user input. By moving the mouse or clicking, the geometric layers expand and contract, mimicking a breathing organism or a shifting lens. This technique is beneficial because it creates a highly responsive feedback loop, fulfilling the "User Input" mechanic requirement. It transforms simple mathematical lines into an immersive visual experience that encourages users to explore the relationship between movement and scale.
---

## Part 2: Coding Technique Exploration

### Selected Tool: p5.js 

![Code Screenshot](readmeImages/coding technique 1.jpg)
![Code Screenshot](readmeImages/coding technique 2.jpg)

**Discussion:**
This coding technique is essential for my "User Input" mechanic. By using `let dynamicScale = map(mouseX, 0, width, 0.5, 3.0);`, I can translate the mouse's horizontal position into a multiplier for the radii of my geometric shapes. This allows for a fluid transition where the entire mandala grows or shrinks as the user moves their cursor. Using mapping ensures the interaction feels natural and constrained within a visual range that maintains the artistic integrity of the piece, making the complex scaling from Part 1 technically achievable. (98 words)

**Resources:**
* **Example Implementation and code:** [p5.js Mouse Functions link](https://p5js.org/reference/p5/mousePressed/)