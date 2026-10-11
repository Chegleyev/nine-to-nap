# Nine to Nap

*«Рабочий полдень»* — an ordinary day of a programmer in a typical office.

**▶ https://chegleyev.github.io/nine-to-nap/**

![Nine to Nap](preview.png)

## How it's made

- **Engine.** Plain TypeScript and raw WebGL, with no game engine.
- **Hero.** The hero is a 2D cut-out (skeletal) rig: rigid parts with round joints, narrow smooth bends at the knees and
  hips, and separate drawings for a bent knee and for sitting.
- **Movement.** Legs and arms are solved by two-bone IK. The floor walk follows curves taken from a motion-capture walk;
  on the stairs, the feet are placed procedurally, one tread per step.
- **Directing.** A small scene director sequences everything: camera moves, speech bubbles and background animation.
- **Artwork.** The artwork was made with AI image generation, then cut into parts, registered and assembled by
  hand-written tools.
