# Xila — a Rust operating system for embedded experiences

**Build embedded applications with Rust and WebAssembly.** Xila is a modular,
open-source embedded operating system that brings together Wasm apps, an LVGL
graphical interface, task management, networking, and storage.

[Website](https://www.xila.dev/) ·
[Documentation](https://www.xila.dev/docs/) ·
[Source code](https://github.com/xila-project/core) ·
[Community](https://matrix.to/#/#xila:anneraud.fr)

## Explore Xila

- **Run it locally:** follow the [native tutorial](https://www.xila.dev/tutorials/native)
  to explore Xila on Linux with Wayland.
- **Try a Wasm application:** follow the [browser tutorial](https://www.xila.dev/tutorials/browser)
  to build Calculator and run it in browser-hosted Xila.
- **Build an app:** use the [guest application guide](https://www.xila.dev/how-to/build-guest)
  to get started with Xila's WebAssembly application model.
- **Understand the system:** explore the [architecture and component map](https://www.xila.dev/explanation/architecture/components)
  for tasks, filesystems, graphics, networking, and platform drivers.

## Why Xila?

- **Rust at the core:** reusable OS modules with explicit ownership and
  resource management for embedded development.
- **WebAssembly applications:** a Wasmi-based runtime for guest programs,
  with Xila graphics bindings and a supported WASI subset.
- **A shared graphical foundation:** LVGL widgets and a Shadcn theme for
  applications and the desktop shell.
- **A practical development path:** native and browser examples help you
  explore shared code before validating it on your intended device.

Xila is under active development. Hardware support, guest APIs, and runtime
capabilities vary by target. Read the [reference and current limits](https://www.xila.dev/reference/)
before selecting a board or depending on an interface.

## Repositories

| Repository                                                   | What you will find                                                                                          |
| ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| [Core](https://github.com/xila-project/core)                 | The Rust embedded OS, device drivers, graphical shell, Wasm runtime, and example applications.              |
| [Website](https://github.com/xila-project/website)           | The source for xila.dev, tutorials, task guides, architecture explanations, and API reference entry points. |
| [Community profile](https://github.com/xila-project/.github) | This organization overview and links to the project and community.                                          |

## Get involved

Explore [Core issues](https://github.com/xila-project/core/issues), report a bug
with reproduction steps, improve a guide, or help with
[translations](https://translate.anneraud.fr/engage/xila-core/).
Start with the [Core contributor guide](https://www.xila.dev/how-to/contribute-core)
or the [documentation contribution guide](https://www.xila.dev/how-to/write-documentation).

Questions or ideas? Join the [Xila Matrix room](https://matrix.to/#/#xila:anneraud.fr)
or contact [contact@xila.dev](mailto:contact@xila.dev).

Xila is created by [Alix ANNERAUD](https://alix.anneraud.fr) and contributors,
and released under the [GNU General Public License v2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).
