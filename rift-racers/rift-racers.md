# Rift Racers

## Core Gameplay Loop
Race through procedurally generated tracks that shift between dimensions, where every corner warps the laws of physics and the environment actively fights your momentum.

## Unique Mechanic
Dimensional rifts that split a single track into parallel realities - players can phase between them mid-race to exploit shortcuts, dodge obstacles, or steal power-ups from alternate versions of themselves.

## Brief Description
In a fractured multiverse where speed is the only currency, you pilot a Rift-Runner - a vehicle built from salvaged quantum technology. Tracks exist simultaneously across multiple dimensions: neon-drenched cyberpunk streets, overgrown post-apocalyptic highways, floating celestial roads, and gravity-defying orbital loops. Master the art of dimensional phasing to outmaneuver rivals who exist across all realities at once.

## Game Concept Overview

**Setting**: The Rift - a collapsing nexus point between infinite parallel worlds.

**Player Role**: Rift-Runner pilot, a dimension-hopping racer seeking the ultimate speed.

**Core Mechanics**:
- **Dimensional Phasing**: Tap a button to shift your car into a parallel track layer; each dimension has unique physics (low gravity, magnetic rails, time dilation zones)
- **Rift Drafting**: Slipstream behind rivals across dimensions to build quantum charge
- **Track Morphing**: The track reconfigures mid-race based on which dimension is dominant
- **Quantum Boost**: Accumulated charge lets you briefly exist in ALL dimensions simultaneously, becoming intangible and passing through obstacles

**Dimension Types**:
1. **Neon Circuit** - Cyberpunk city grid with holographic barriers and mag-lev turns
2. **Verdant Wreck** - Overgrown ruins where vines slow you down but grant speed bursts on destruction
3. **Orbital Drift** - Zero-G space highway with asteroid hazards and loop-the-loops
4. **Temporal Blur** - Time-fractured zone where the track ahead shows 3 seconds into the future

**Technical Architecture**:
- **Multi-Layer Track System**: 4 parallel track states rendered simultaneously with seamless transitions
- **Physics Engine Per Dimension**: Each reality applies different gravity, friction, and acceleration values
- **Procedural Generation**: Track segments combine from dimension-specific modules
- **Quantum State Management**: Player position tracked across all dimensions for phasing accuracy

**Vehicle Progression**:
1. **Scrap Runner** - Starter, balanced across dimensions
2. **Phase Striker** - Faster phasing cooldown, lower top speed
3. **Void Leviathan** - Heavy, high momentum, resists dimension-specific hazards
4. **Neon Specter** - Lightweight, excels in Neon Circuit,弱点 in Orbital Drift

**Race Modes**:
- **Rift Grand Prix**: 8-race championship across all dimensions
- **Phantom Sprint**: Single-dimension time trials with global leaderboards
- **Dimensional Battle**: Combat racing where phasing attacks opponents in other layers
- **Endless Drift**: Procedurally infinite track that increases in complexity
