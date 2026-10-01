# Reef Cube

Reef Cube is a freshwater voxel observatory: a 100 × 100 × 100 logical volume whose shape is revealed by the life occupying and moving through its cells.

## Freshwater upgrade

- Visible adaptive unit-edge grid.
- Whole-cube orbit view with zoom into local habitat regions.
- Connected voxel fish from 2 to 7 cells.
- Minnows, perch, bass, northern pike, and muskie.
- Seaweed rooted in the substrate with current-driven sway.
- Microorganism field.
- Discrete cell transfers with short visual interpolation.
- Occupancy telemetry for water, life, and life/water ratio.
- Species-specific movement cadence and colors.

## Simulation model

The cube has one million logical cells. Occupancy is tracked from soil, seaweed, microorganisms, and connected fish shapes. Fish test neighboring cells, orient toward a legal direction, release their current arrangement, and transfer into the new cells.

The current is visualized with local seaweed sway. The first version uses a lightweight canvas projection; a later GPU pass can replace it with instanced WebGL cubes while preserving the same cell and organism model.

## Deployment

Enable GitHub Pages for `main`. The existing CNAME points to the project's custom domain.
