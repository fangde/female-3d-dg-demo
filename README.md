# 3D Face + Hair Local Triangle SfM & Embedded Deformation Graph Demo

Interactive Three.js viewer for the 240-frame 3D reconstruction:
- **Face**: 100-Node Per-Frame Embedded Deformation Graph (`cos_lens > 0.35` normal-gated, tangent-locked, $C^2$ smoothed) + 2K texture (`13,727` tris)
- **Hair**: 150-Node Per-Frame Embedded Deformation Graph (360° short-span tracks, zero-flip `L-BFGS` canonical mesh, $C^2$ smoothed) + 2K sharp 66-keyframe texture (`44,000` tris)
- **Camera**: 240-frame BA loop-closed camera trajectory
