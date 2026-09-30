# Reef Cube

Reef Cube is a standalone sparse voxel ecosystem where life makes an invisible volume visible.

## First prototype

- Logical world size: 100 × 100 × 100.
- Soil substrate with irregular height.
- Plant colonies that grow upward.
- Microorganism field.
- Red shrimp near the substrate.
- Small fish and larger fish entities.
- Local movement, energy, food, predator-pressure, plant growth, and trail memory.
- Drag-to-orbit and scroll-to-zoom view.
- Population and active-voxel telemetry.

The first renderer is intentionally lightweight: it projects sparse voxel-like entities onto a canvas so the ecological rules can be explored before moving to a full GPU voxel renderer.

## Model direction

The full project can grow toward nutrient diffusion, reproduction, decay, explicit predation, school behavior, chunked voxel storage, and instanced WebGL rendering. The central design principle remains: life makes the cube visible.

## Deployment

Enable GitHub Pages for the `main` branch. The intended path is `tallkidd23.github.io/reefcube`.
