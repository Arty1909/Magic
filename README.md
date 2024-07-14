# Magic

Fluid Simulation
This project is a fluid simulation implemented using WebGL. It provides an interactive experience where users can manipulate the fluid by moving their mouse or touching the screen. The simulation reacts to these inputs, creating visually appealing fluid effects.

Features
Fluid Dynamics: Simulates fluid behavior with dissipation, pressure, vorticity, and advection.
Interactive Input: Users can interact with the fluid by moving the mouse or touching the screen.
WebGL Context: Utilizes WebGL for rendering, supporting both WebGL 1 and WebGL 2 contexts.
Shaders: Implements various shaders for different stages of the simulation, including base, clear, display, splat, advection, divergence, curl, vorticity, pressure, and gradient subtraction shaders.
Framebuffers: Manages framebuffers for different textures like density, velocity, divergence, curl, and pressure.
How It Works
Initialization: Sets up the WebGL context, compiles shaders, and initializes framebuffers.
Interaction: Captures mouse and touch events to create splats in the fluid simulation.
Rendering Loop: Continuously updates and renders the fluid simulation using WebGL shaders and framebuffers.
Shaders: Each shader handles a specific aspect of the simulation, such as advecting fluid properties, calculating divergence, applying pressure, and more.
Usage
Mouse Interaction: Move the mouse over the canvas to interact with the fluid.
Touch Interaction: Touch and move your finger on touch-enabled devices to interact with the fluid.
