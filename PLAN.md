NEON REQUIEM — Autonomous 3D FPS Development Plan

Mission

Build a polished, genuinely playable 3D first-person shooter with high-quality combat feedback, intelligent enemies, atmospheric environments, and responsive controls.

Technology

- Use the repository's existing stack when viable.
- For a browser-based game, prefer Three.js and WebGL.
- Keep the game runnable throughout development.
- Support keyboard/mouse and mobile touch controls where practical.
- Use original or permissively licensed assets; never rely on unauthorized asset downloads.

Core Gameplay

1. Responsive first-person movement, sprinting, jumping, and collision.
2. Multiple distinct weapons with firing, recoil, reload, ammo, and weapon switching.
3. Reliable hitscan or projectile collision and damage calculations.
4. Enemy AI with detection, pursuit, attack, and death states.
5. Combat feedback: muzzle flashes, tracers, impacts, explosions, sound, and camera effects.
6. Health, ammunition, objectives, pause, game over, and restart.
7. At least one complete mission with a beginning, combat encounters, and a clear victory condition.

Visual Quality

- Atmospheric lighting and shadows where supported.
- Detailed modular environments and strong material contrast.
- Responsive HUD, damage indicators, crosshair, ammo display, and objective markers.
- Particle effects with performance-aware limits.
- Smooth animation and polished transitions.
- Quality settings for weaker devices.

Engineering Requirements

- Inspect the repository before making changes.
- Maintain a persistent PLAN.md and update PROGRESS.md.
- Select the highest-priority unfinished task each iteration.
- Implement real gameplay, not mock interfaces or decorative placeholders.
- Run available tests, builds, and runtime checks after meaningful changes.
- Fix discovered regressions before proceeding where practical.
- Never claim tests passed unless they actually ran successfully.
- Preserve working features and avoid unnecessary rewrites.
- Do not commit secrets, API keys, or unrelated generated files.

Development Loop

Repeat:

1. Read the roadmap and progress report.
2. Identify the next concrete, testable improvement.
3. Implement it.
4. Run tests and relevant checks.
5. Diagnose and fix failures.
6. Update PROGRESS.md with evidence and remaining work.
7. Commit and push changes.
8. Continue with the next task.

Definition of Done

The project must launch successfully, support a complete playable mission, feature functional weapons and enemies, provide a reliable restart flow, and pass all available automated checks. Report any unverified browser, graphics, or device-specific behavior honestly.
