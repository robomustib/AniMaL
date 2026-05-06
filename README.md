# AniMaL
### Animal-based Machine Learning — a hands-on ML teaching tool
 
AniMaL is a browser-based learning game that introduces children and young learners to the core concepts of machine learning through play. Learners take on the role of teacher: they show an AI which food each animal likes — and watch in real time as the system's internal weights shift in response.
 
The name says it all: **Ani**mal + **Ma**chine **L**earning.
 
---
 
## What it teaches
 
AniMaL makes three core ML concepts tangible without any math or prior knowledge:
 
- **Learning from examples** — the AI knows nothing at the start and only improves through the examples it is shown
- **Weights as memory** — every interaction visibly strengthens or weakens a connection, making the abstract idea of a weight concrete
- **Training vs. testing** — the two-phase structure mirrors the real ML workflow: first you train a model, then you evaluate it
---
 
## How it works
 
**Training Mode** — the learner is the teacher. An animal appears on screen and the learner picks what it should eat. The AI observes, updates its internal weights, and explains what it just learned. The animal always accepts the food happily — because in this phase, the learner defines what is correct.
 
**Test Mode** — the AI makes its own predictions. The learner picks first, then sees whether the AI agrees. A side-by-side result shows what the learner chose, what the AI guessed, and what the correct answer is.
 
A live weight panel shows the shifting confidence scores for each animal–food pair after every interaction, making the learning process fully transparent.
 
---
 
## Features
 
- 6 animals · 8 food types
- Live weight visualization with delta indicators after each training step
- Plain-language explanation of what the AI just learned
- Training progress tracker per animal
- Full training history log
- Responsive layout for desktop and mobile
- Zero dependencies — single HTML file, no framework, no build step
---
 
## Usage
 
### Standalone
Open `animal.html` directly in any modern browser. No server required.
 
### WordPress / CMS
Paste the contents of `animal-wordpress.html` into any HTML block in the Gutenberg editor or a plugin like Shortcoder. The tool is fully scoped — all CSS classes carry the `gbnn-` prefix and no styles leak into the surrounding theme.
 
---
 
## Files
 
| File | Description |
|---|---|
| `AniMaL_v1.html` | First prototype version |
| `AniMaL_v2.html` | Final version |
 
---
 
## Educational context
 
AniMaL was developed as a didactic tool for technology and computer science education at secondary school level. It accompanies classroom instruction on artificial intelligence and machine learning, targeting learners with no prior programming experience.
 
---
 
## License
CC.
