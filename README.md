PixelCraft
A procedural 2D world generation engine built in Python, featuring cellular automata caves, multi-layered strata, organic tunnel networks, and dynamic fluid simulations.

Features
Cellular Automata Caverns: Simulates natural rock erosion and smoothing iterations to generate realistic, navigable cave networks.

Biome & Strata Ores: Integrates Perlin noise generation to seed stratified mineral distribution throughout the rock face.

Subterranean Fluid Dynamics: Simulates fluid flow behavior for water and lava across open cavern spaces.

Extensible Architecture: Designed for modular chunk-based expansion and real-time world modification.

Project Structure
Plaintext
PixelCraft/
├── main.py              # Core world manager and execution entry point
├── caves.py             # Cellular automata cave generation logic
├── fluids.py            # Fluid simulation engine (water/lava)
└── noise.py             # Perlin noise generator for strata and ores
Getting Started
Prerequisites
Python 3.8+

Installation & Execution
Clone the repository:

Bash
git clone https://github.com/your-username/PixelCraft.git
cd PixelCraft
Run the generator script:

Bash
python main.py
Roadmap
[ ] Implement chunk-based world streaming

[ ] Add dynamic lighting and shadow occlusion

[ ] Integrate player digging and block destruction physics

[ ] Expand surface village generation algorithms

License
Distributed under the MIT License. See LICENSE for more information.
