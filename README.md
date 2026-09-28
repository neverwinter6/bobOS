# bobOS — A Privacy-First Desktop Experience 🖥️🔒

bobOS is a privacy-focused operating environment built with a single goal: your data stays yours. It runs entirely locally, includes no telemetry, no tracking, and no cloud dependencies of any kind. Every window, every app, every keystroke — nothing leaves your machine unless you explicitly make it do so.

Built as a lightweight web-based desktop environment, bobOS proves you don't need to sacrifice your privacy to have a modern, usable interface. It boots fast 🚀, lets you work, and gets out of your way.

Core Design Principles 🧭

- Zero tracking 🚫 — no analytics, no usage metrics, no spyware.
- Local-first 💻🏠 — everything runs on your device; your notes, your sessions, your data.
- Minimal and transparent 🔍📄 — the codebase is plain HTML, CSS, and JavaScript. Nothing hidden. Nothing obfuscated. You can read every line.

Features ✨

Desktop Environment 🖼️
- Multiple resizable, minimizable windows with drag-to-move, title-bar controls, and a taskbar.
- Keyboard-driven window switching (Alt+1 through Alt+4).
- Theme switcher with three color schemes: green (default terminal look 🌿), mono (grayscale terminal ⚫), and paper (light, low-contrast mode 📄).
- Live system clock in the taskbar ⏰.

Notes App 📝
- Create, view, edit, and delete notes in a split-panel interface.
- Notes are saved automatically to your local storage as you type — no manual save step 💾.
- Notes persist across page reloads and browser restarts (via localStorage), so nothing is lost if you accidentally close the window 🛡️.
- Each note shows a timestamp and title; you can search visually by scrolling.
- Keyboard shortcuts: Ctrl+N to create a new note, Ctrl+D to delete the current note.

Calculator App 🧮
- Full-featured scientific calculator with a retro terminal aesthetic.
- Supports basic arithmetic (+, -, *, /), parentheses, exponentiation (^), constants (pi ≈ 3.14159, e ≈ 2.71828), and functions: sin, cos, tan, ln, log, sqrt.
- Dark display with green numeric readout.
- Keyboard support: type numbers and operators directly, Enter to evaluate, Escape to clear, Backspace to delete the last character.
- Handles floating-point display cleanly and avoids common calculator pitfalls like trailing-operator errors.

Terminal Launcher 💻
- Central launchpad showing all installed apps with keyboard-style indicators ([N] for notes, [=] for calculator, [*] for settings).
- Quick-access footer with version info and privacy stats (3 apps - 0 tracking - 0 telemetry).
- Opens apps in their own windows; closes cleanly when you're done.

Settings App ⚙️
- Toggle between three themes without restarting anything.
- Persistent preference saved locally.
- Always-visible reminder of what bobOS is: a small, honest system with no hidden agendas.

What's Coming Next 🚧

bobOS is a living project. The current release is a working foundation; more tools are in active development:

- AI Assistant 🤖 — a built-in assistant designed to work locally and respect the same privacy principles as the rest of bobOS. It's meant to help you work without sending your prompts or data to any external service.
- Browser 🌐 — a privacy-first browser component, planned to integrate with bobOS's local-first mentality. Think of it as a web surface you control, not one that tracks you by default.

Both are early in development. The goal is the same as bobOS today: useful tools that don't compromise your data.

Technical Notes

bobOS is a single-file web application — one HTML file with embedded CSS and JavaScript. No build step, no bundler, no frameworks, no dependencies. You can open it directly in any modern browser, or serve it with any static server (python -m http.server, a CDN, a local proxy — it doesn't care).

It's intentionally simple. That simplicity is the privacy feature: there's no hidden network layer, no background service worker, no analytics tag. If you want to audit what bobOS does, you can read the entire source in one sitting.

A Note on How This Was Built

bobOS was written by a human. The structure, the design decisions, the app logic, and the window management system were all authored directly.

AI assistance was used only in two narrow ways:
1. Correcting code — catching bugs, typos, and logic errors during development.
2. Figuring out how to build certain features — for example, generating small reference snippets or clarifying an approach when the author was uncertain about a specific implementation detail.

AI did not write the application. It did not design the UI. It did not choose the features. It was a tool for polishing and problem-solving, not a substitute for authorship. The result is a system built by a person, with help only where it made sense.

License

bobOS is released into the public domain. You can use it, modify it, copy it, remix it, or ignore it — no permission needed, no attribution required, no restrictions of any kind.

