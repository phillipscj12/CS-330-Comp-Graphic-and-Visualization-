# CS330: Portfolio Artifact — 3D Scene

## Reflection

### Software Design Approach  
I begin each project by sketching out the major systems—scene graph, camera controls, physics engine—on paper or in a lightweight diagram. From there I identify key data structures (e.g. a `GameObject` base class, `Mesh` and `Material` types) and their relationships before writing any code.

### New Design Skills  
Building the backyard barbecue scene taught me to think in terms of reusable components (e.g. a generic `MeshRenderer`) and to separate “what” from “how” by defining clear interfaces for scene setup versus rendering logic.

### Design Process Followed  
1. **Conceptualize** the overall layout and user interactions.  
2. **Decompose** into objects (pyramids, ground plane, smoker, patio).  
3. **Prototype** one shape at a time in code, verifying transforms.  
4. **Integrate** objects into a scene graph with a single render pass.

### Applying These Tactics in Future Work  
This component-based mindset scales well to larger engines: I can add new object types or behaviors without touching existing code, simply by implementing the same interface.

---

### Development Approach  
I develop in small, testable increments—first drawing a single cube, then adding textures, then camera movement, and finally lighting. Frequent builds and playtests ensure I catch errors early.

### New Development Strategies  
For this scene I used GLM’s transformation library (translate, rotate, scale) extensively, and I set up a simple profiler to measure frame time as I added more objects and textures.

### Role of Iteration  
Each milestone focused on one feature: Milestone 1 (basic shapes), Milestone 2 (camera controls), … Milestone 5 (textures), Milestone 6 (lighting). Iteration let me validate each feature in isolation before combining them.

### Evolving My Coding Style  
My code started as one monolithic `main()`, but over six milestones I refactored it into `SceneManager`, `ViewManager`, and shader helper classes—improving readability and maintainability.

---

### Broader CS Goals  
Computer science gives me the tools to solve complex spatial and performance problems—skills I’ll use in game development, data visualization, or any performance-critical application.

### Educational Pathway  
By mastering shaders, transformations, and scene graphs, I’m well prepared for advanced graphics courses such as Real-Time Rendering and GPU Programming.

### Professional Pathway  
Industry studios and AR/VR teams look for engineers who can bridge mathematics, data structures, and real-time code. This project demonstrates my ability to architect and implement a complete 3D pipeline from scratch.

