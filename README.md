# Flux - To-Do List

This project is a Wayland compositor written in C++ with a Vulkan-based rendering backend. The goal is to create a tiling window manager with complete control over the Wayland server and rendering pipeline.

---

## To-Do List

### Core Components
- [ ] **Custom Wayland Server**
  - [ ] Set up `wl_display` and `wl_event_loop`.
  - [ ] Handle client connections and communication.
  - [ ] Implement input management (keyboard, mouse).
  - [ ] Manage outputs (e.g., multiple monitors).

### Rendering Backend (Vulkan)
- [ ] **Vulkan Initialization**
  - [ ] Create Vulkan instance, physical and logical device.
  - [ ] Setup swapchain for rendering.
  
- [ ] **Rendering Pipeline**
  - [ ] Design the rendering pipeline for window surfaces.
  - [ ] Implement shaders (vertex, fragment).
  - [ ] Synchronize rendering with semaphores and fences.

### Window Management
- [ ] **Tiling Window Manager**
  - [ ] Basic tiling layout (vertical/horizontal split).
  - [ ] Window focus and resizing.
  - [ ] Multi-monitor support with independent layouts.

### Wayland Protocols
- [ ] **Wayland Protocols**
  - [ ] Implement `xdg-shell` for window management.
  - [ ] Implement `wl_seat` for input handling.
  - [ ] Implement `wl_output` for monitor management.

### Advanced Features
- [ ] **Configuration System**
  - [ ] Dynamic configuration via a config file.
  
- [ ] **Hotkey Support**
  - [ ] Implement customizable key bindings for window management.

### Miscellaneous
- [ ] **Logging**
  - [ ] Add logging for debugging and performance tracking.

---

## Summary of Key Goals
1. Build a **custom Wayland server** without `wlroots`.
2. Use **Vulkan** for rendering windows and managing graphics.

---

This is the core roadmap to help guide the development of the Flux compositor. Each section can be expanded as progress is made.
