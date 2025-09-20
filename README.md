Canvas2D Constellation Scaffold

Purpose

This is a self-contained HTML5 Canvas2D animation.
It uses JavaScript to simulate ~10,000 “embers” (particles of light) and organizes them into different visual scenes.

The file is meant to be portable: open it in any modern browser and it runs locally, no server needed.

⸻

Structure
	•	HTML container: <canvas> element sized square, responsive to viewport.
	•	CSS: Minimal, sets black background, caption overlay, HUD (debug info), and control buttons.
	•	JavaScript:
	•	Particle system: An Ember class defines each glowing particle.
	•	Scene manager: An array of scene objects, each with .enter() and .frame() functions.
	•	Scenes implemented (as examples of transformations):
	•	Flight — upward drift with orbiting attractor.
	•	Beams — particles align into vertical columns.
	•	Drowned Coast — wave-like motion, color shift toward blue.
	•	Lens — camera flash effects and focus brackets.
	•	Signs — constellation lines between nearby particles.
	•	Exile Hearth — particles drawn to a central fire.
	•	Error → Rebirth — spiral ascent, warm → cool color shift.
	•	UI Controls: play/pause, next/prev scene, toggle captions.
	•	Keyboard Shortcuts:
	•	Space = play/pause
	•	Left/Right arrows = prev/next scene
	•	T = toggle captions

⸻

How to Run
	1.	Save the file as constellation_canvas2d.html.
	2.	Open in any modern browser (Chrome, Safari, Firefox, Edge).
	3.	That’s it — no server or build tools required.

⸻

Notes
	•	Performance: Starts with ~10,000 embers, auto-reduces if frame rate drops.
	•	Device Adaptivity: Scales number of embers and pixel density for mobile/desktop.
	•	Self-contained: No external libraries, just plain HTML/CSS/JS.

⸻

This README is the generic scaffold: it describes the machinery, not the specific narrative content you load into it.
