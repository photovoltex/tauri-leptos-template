# Tauri + Leptos

> Replace all "tauri-leptos-template" with your app name before continuing.

This template should help get you started developing with Tauri and Leptos.

This template uses some opt-in features which intents to improve the overall developing experience. For example:
- `per-package-target` cargo-feature (used by the root project)
  - allows to configure a project so that cargo already knows how to compile it 
    > otherwise a whole project build wouldn't be possible without errors (due to different target between ui and app)


## Setup

- tauri-cli: 1.5.6
  - `cargo install tauri-cli@1.5.6`
- trunk: 0.17.5
  - `cargo install trunk@0.17.5`
- latest "wasm32-unknown-unknown" target
  - `rustup target add wasm32-unknown-unknown`
- nightly toolchain might be required
  - `rustup toolchain add nightly` (install)
  - `rustup default nightly` (set as default)

## Components/Theming
- [leptonic](https://leptonic.dev/)
