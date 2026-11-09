# Particle Imagineer

## Repository
<https://github.com/florida-11/pfda_vfxcreator>

## Description
Particle Imagineer is a interactive 2D VFX sandbox made with Python and Pygame. Its abilities will let digital artists and game developers experiment with particle effects, colors, and motion in an interactive, real-time setting. 

## Features
- Three Modes
	- Ability to create a spark burst that shoots outwad from a left-mouse click, an aura that emits particles around the cursor, and a trail apinter that leaves fading particles as the mouse moves.
- Animation and Fading
	- Particles will have a Pygame loop that update their positions each frame while the transparency causes them to fade and disappear.
- Color Presets and controls
	- Keybinds will switch between several coordinated color palettes and the ability to adjust basic particle properties.
- On-Screen Controls
	- Small text overlay that will show the current effect mode and avaliable control. 
- Saving artwork as a PNG
    - Keybind that will save the current VFX canvas as an image so users can keep their designs as references.

## Challenges
- Learning how to give particles different movement patterns (outward burts, motion that follows the mouse instead of downward).
- To keep particle animation smooth while tracking and removing particles in real-time.
- Learning how to render VFX on a screen and save the artwork as an image file

## Outcomes
Ideal Outcome:
- A responsive particle sandbox that has 3 different effects, multiple color palettes, adjustable settings, and a PNG export. Can be used to brainstorm VFX and experiment.

Minimal Viable Outcome:
- A functional program that lets users trigger at least 2 different particle effects and switch between color palettes. 

## Milestones

- Week 1
  1. Make the basic Pygame window, game loop, and particle class.
  2. Implement interactive spark-burst effect with fading particles.

- Week 2
  1. Add the aura and mouse-trail effects using the existing particle system.
  2. Add color palettes and keyboard controls

- Week N (Final)
  1. Add control instructions and PNG image export
  2. Polish the sandbox and refine if needed