# Agnej

> The Ultimate Reverse Block Stacking Game
> Build up. Don't tear down.

Agnej is a physics-based tower-building game inspired by classic block-stacking games. Instead of removing blocks from an existing tower, players start with a small foundation and build upward by placing new blocks.

Bad placements are allowed.

Gravity decides the rest.

Play online when you forgot your bricks.

---

## Gameplay

The rules are simple:

1. Start with a small base.
2. Place a new block anywhere it does not intersect another block.
3. Rotate and position the block carefully.
4. Release it and let physics take over.
5. If blocks fall and touch the ground, an **AGNEJ** event occurs.
6. Remove fallen blocks and continue building.
7. Build the tallest and most ridiculous structure possible.

Unlike the traditional game, instability is part of the game. Risky placements can create spectacular collapses.

---

## Features

- Real-time 3D rendering using Three.js
- Physics simulation powered by Rapier
- Mobile-friendly controls
- Touch-based camera controls
- Interactive rotation gizmo
- Physics-based tower collapse
- Collapse scoring system
- Continue-after-collapse gameplay
- Single-file deployment

---

## Controls

### Camera

- Drag in **Scene** mode to rotate the camera
- Pinch to zoom

### Move Block

- Select **Move Brick**
- Swipe to move the ghost block relative to the camera

### Rotate Block

- Drag one of the colored rotation rings
- Red = X axis
- Green = Y axis
- Blue = Z axis

### Height

- Use the vertical slider on the right
- Height is measured relative to the ground plane

### Place

- Press **Place**
- The block becomes a physical object
- Physics takes over

---

## Scoring

### Block Score

The block counter tracks the number of blocks successfully placed.

### Collapse Score

Whenever blocks touch the ground during an AGNEJ event:

- Those blocks are removed when continuing
- The number of removed blocks is added to the collapse score

Lower collapse scores are generally better.

---

## Technology

> 100% Vibes

### Three.js

Used for rendering and interaction.

License: MIT

https://threejs.org/

### Rapier Physics

Used for rigid body simulation and collision detection.

License: MIT

https://rapier.rs/

---

## Goals

Agnej is intentionally simple, but there are many ideas for future development.

### Near-term

- Better visual effects
- Improved mobile controls
- Sound effects
- Microphone input to detect "AGNEJ" shouts for less punishment
- Haptic feedback
- Improved collapse statistics
- Better shadows and lighting

### Mid-term

- Daily challenge mode
- Replay system
- Screenshot sharing
- Challenge seeds
- Tower height leaderboard
- Collapse leaderboard

### Long-term

- Multiplayer pass-and-play
- Online multiplayer
- Tournament mode
- Custom block types
- Physics modifiers
- Community challenges

---

## Contributing

Contributions are welcome.

### Areas where help is appreciated

#### Physics

- Stability tuning
- Better collision handling
- Performance improvements
- Mobile optimization

#### Gameplay

- New game modes
- Scoring systems
- Accessibility improvements
- UX improvements

#### Visuals

- Materials
- Effects
- Animations
- UI polish

### Development Guidelines

- Keep gameplay intuitive
- Mobile-first design
- Maintain high performance
- Avoid unnecessary dependencies
- Preserve the "simple to learn, difficult to master" philosophy

### Submitting Changes

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test on desktop and mobile
5. Open a pull request

Bug reports and gameplay suggestions are always welcome.

---

## License

Copyright © 2026 Lars Dekker

All rights reserved.

Third-party software:

- Three.js (MIT License)
- Rapier Physics (MIT License)

See the respective projects for their license texts.
