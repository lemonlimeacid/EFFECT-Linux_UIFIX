# Linux Sharp UI patch

This patch changes the shared egui theme, not KDE/GNOME settings:
- zero corner radius for widgets, menus, and windows
- disable gradients regardless of saved appearance preference
- remove popup/window shadows

## Displacement Map note

The Linux-specific Displacement Map issue is **not claimed fixed** by this visual patch. The effect already uses the shared WGSL GPU shader (`crates/gpu/src/shaders/fx_distort.wgsl`) and CPU implementation (`crates/effects/src/distort2.rs`). A reliable fix requires reproducing the reported project and recording the active WGPU backend/adapter, selected map layer, channel source, map behavior, and effect settings. Do not apply a guessed platform-specific workaround before that test.

Build from the repository root with the project's documented Cargo command. This source archive has not been compiled or visually verified in this environment.
