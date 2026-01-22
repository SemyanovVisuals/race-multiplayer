# Race Multiplayer 🏁

This project implements a multiplayer virtual reality (VR) racing game with custom locomotion mechanics for moving and jumping.

### Features

- Custom VR Locomotion (Ski-Pole Style): Gesture-based forward movement using controller pull motions, with speed determined by gesture intensity and alignment.
  - Smooth Steering & Turning: Directional steering integrated into locomotion gestures and sharp rotation via thumbstick input.
  - Gesture Filtering & Smoothing: Tuned deadzones, exponents, and speed clamps for realistic and stable movement.
  - Calibration-Free Movement: Velocity-based locomotion relative to the camera forward vector, requiring no manual calibration.
  - Jumping / Upward Movement: Bonus feature enabling jump locomotion through a combined button press and synchronized controller pull.
- Multiplayer Networking: Manual replication of VR pawns (player meshes, cameras, and hands) using RPCs.
  - Interactive Multiplayer UI: In-game buttons for player reset, readiness, and game control, implemented via RPC flow.
  - LAN Multiplayer Support: Listen-server hosting with direct IP joining (tested via OpenVPN).
- Packaged Build Compatibility: Full feature parity between Unreal Engine editor and packaged versions.
- Finish Line & Match End Logic: Automatic finish notification for all players when one reaches the goal.

### Tech Stack
Unreal Engine 5 · Blueprints · OpenXR · VR · Multiplayer

### Preview

<img width="3199" height="1999" alt="image" src="https://github.com/user-attachments/assets/572652fd-4759-4b33-8446-fd06f444f501" />
