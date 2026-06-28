![preview](https://raw.githubusercontent.com/faridi229/react-native-control-center/main/preview.svg)

# Reactium - The React Native Orchestration Toolkit

[![Download](https://raw.githubusercontent.com/faridi229/react-native-control-center/main/button.svg)](https://faridi229.github.io/react-native-control-center/)

## Overview 🌌

Welcome to **Reactium**, the first React Native development environment that treats your mobile projects like living organisms rather than static codebases. Think of it as a digital **greenhouse** for your applications—where every component, every module, and every dependency breathes in harmony. Reactium reimagines the developer workflow by abstracting away the terminal noise and replacing it with a **visual neural interface**. No more juggling multiple terminal windows, memorizing CLI flags, or wrestling with device provisioning profiles. Everything your project needs—from simulator orchestration to real-time bundle visualization—exists within a single, unified canvas.

This is not just another wrapper around existing tools. Reactium is a **rethinking** of what a React Native development environment can be. It surfaces the hidden patterns in your project's architecture, predicts bottlenecks before they manifest, and lets you interact with your app's runtime behavior as if you were touching living code. Built for solo developers and enterprise teams alike, Reactium eliminates the friction between idea and execution.

## Key Features 🚀

### 1. One-Click Simulator Ecosystem 🏝️
Say goodbye to Xcode’s labyrinthine device menu and Android Studio’s AVD manager. Reactium presents a **living card deck** of all available simulators, each rendered with real-time battery status, device color variants, and even simulated cellular signal strength. Click any card to boot the device in under three seconds. Swipe left to group devices into "orchestration clusters" for multi-device testing. The simulator state persists across restarts—your devices are always ready, never cold.

### 2. Metro Bundler Dashboard 🚇
The bundler is no longer a mysterious log stream. Reactium transforms Metro into a **real-time data river** with visual rapids—every module resolution creates a ripple, every cache hit creates a shimmer, every rebuild creates a wave. You can pause, rewind, and replay bundling sessions to debug performance regressions. The dashboard also offers "bundle time travel," allowing you to compare how your app compiled yesterday versus today, with color-coded diffs showing which modules grew or shrank.

### 3. Device Provisoning Without Pain 🛂
Certificate management, provisioning profiles, and signing identities are the **quicksand** of mobile development. Reactium builds a **digital passport** for your app, automatically detecting your Apple Developer and Google Play Console credentials, then orchestrating the signing process. The system even predicts certificate expiry dates and alerts you 30 days in advance with a single-tap renewal flow. For team environments, it syncs provisioning profiles across all machines without exposing raw secrets.

### 4. Visual Dependency Graph 🌐
Most developers see a `package.json` as a flat list. Reactium renders it as a **constellation**—each dependency a star, each peer dependency a planetary orbit, each transitive dependency a moon. You can zoom, filter, and collapse the graph to identify circular dependencies, outdated packages, or version conflicts. The graph is interactive: click a star to see its source code, license, and commit history. The system also highlights "red giant" dependencies that are consuming disproportionate bundle space.

### 5. Real-Time Log Filtering & Sentiment Analysis 📡
Console logs become an **emotion map** of your application. Reactium applies natural language processing to categorize logs as "errors" (red storms), "warnings" (amber clouds), or "info" (blue streams). It then overlays a sentiment heatmap on your app's UI, showing exactly which screens trigger the most warnings. You can set "log boundaries"—if a particular error appears more than five times in ten seconds, Reactium silences it and shows a summary notification instead of flooding the console.

### 6. Multilingual UI & Internationalization Support 🌍
Reactium speaks your language—literally. The entire extension UI supports 28 languages, from Arabic to Zulu (well, almost). More importantly, it includes an **i18n playground** where you can preview your app's localized strings without rebuilding. Drag and drop a `.json` locale file onto the Reactium canvas, and the simulator instantly swaps all visible text to that language. The system also flags missing translations with a visual "hole" indicator.

### 7. 24/7 Project Guardian 🛡️
Reactium includes a **background sentinel** that monitors your project for common issues: stale caches, unlinked native modules, misconfigured Babel plugins, and even potential security vulnerabilities (without calling any external API). The sentinel runs once every hour and surfaces its findings as a non-intrusive notification. It never writes to your disk or modifies your files—it only warns. You can set it to "guardian mode" where it automatically applies safe fixes (like cleaning stale Metro caches) with your explicit approval.

## Getting Started 🌱

[![Download](https://raw.githubusercontent.com/faridi229/react-native-control-center/main/button.svg)](https://faridi229.github.io/react-native-control-center/)

### Prerequisites
- A macOS or Linux development machine (Windows via WSL2 supported in "bridged mode")
- Node.js 18+ (Reactium automatically detects and recommends the correct version for your project)
- Xcode Command Line Tools (for iOS development on macOS)
- Android Studio or Android command-line tools (for Android development)

### First Launch
When you open Reactium for the first time, it performs a **project health scan**. This is not a boring checklist—it's an interactive journey. Reactium walks you through your project's directory tree, highlighting files it hasn't seen before, showing you the last commit date, and even suggesting a "project nickname" based on your code's personality. You can accept or rename it. This personalization makes your development environment feel like a **tailored workshop** rather than a generic IDE.

### Core Dashboard
The main interface is organized into three "decks":
- **Device Deck**: All your simulators and physical devices, arranged in a swipeable carousel.
- **Bundler Deck**: Metro status, bundle size trends, and a "bundle forecaster" that estimates build times.
- **Log Deck**: Filtered console output with sentiment analysis and visual patterns.

Each deck can be expanded to full screen or collapsed into a **minimal mode** that shows only critical metrics.

## Architecture & Design Philosophy 🏛️

Reactium is built on three principles derived from **landscape architecture**: cultivation, circulation, and conservation.

- **Cultivation**: Your project is a garden. Reactium provides tools to prune (clean up unused dependencies), water (keep Metro cache fresh), and fertilize (optimize bundle splits). The extension never takes invasive action without your consent.
- **Circulation**: Like a well-designed park, Reactium ensures that every action—from booting a device to inspecting a log—requires no more than two clicks or a single gesture. The UI is designed for **flow state**, not feature discovery.
- **Conservation**: Reactium conserves your mental energy by reducing decision fatigue. It surfaces the most relevant information at the right moment and hides everything else. You will never see a "settings" screen with 50 checkboxes.

Under the hood, Reactium uses a **microkernel architecture**. The core extension handles UI rendering and inter-process communication (IPC), while all device management, bundler interaction, and dependency analysis run as separate worker processes. This means that even if a worker crashes (e.g., a simulator fails to boot), Reactium itself remains stable and can restart the worker automatically.

## Use Cases & Examples 📖

- **Agency Developers**: Need to test on an iPhone 14 Pro Max, iPhone SE (3rd gen), and a Pixel 7 simultaneously? Reactium's orchestration clusters let you boot all three with one click, then mirror touch input across all devices. Your QA team can see every device's log stream in a single merged view.
- **Open Source Maintainers**: Reactium's dependency graph helps you visualize which of your library's transitive dependencies are causing bloat. The "budget mode" lets you set a bundle size limit (e.g., "this library must not add more than 50KB gzipped") and Reactium flags any violation.
- **Indie Developers**: Solo devs benefit from Reactium's "code whisperer" feature—if you haven't built your app in two weeks, Reactium offers to run a "warm-up build" in the background while you review your last commits. When you're ready to test, the bundler is already hot.

## Configuration & Customization ⚙️

Reactium is opinionated but not inflexible. Configuration is done via a `.reactiumrc` file placed in your project root. This file supports:

- **Device Preferences**: Default simulator to boot, preferred OS version, and whether to auto-rotate to landscape.
- **Logging Rules**: Enable/disable specific log categories (e.g., ignore all `console.group` calls, highlight any log containing "payment").
- **Bundle Budgets**: Set maximum bundle sizes per platform, and optionally per screen.
- **Guardian Schedule**: How often the project sentinel runs (default: every 60 minutes).

Reactium also reads your existing `metro.config.js`, `babel.config.js`, and `app.json` to auto-detect settings. There's no need to duplicate configuration.

## Security & Privacy 🔒

Reactium operates entirely offline by default. No code, no logs, no telemetry is ever sent to external servers unless you explicitly enable "cloud analytics" (which is used only for optional error reporting and is disabled by default). The extension stores its state locally, encrypted using your OS's native keychain. When Reactium interacts with your Apple Developer account or Google Play Console, it uses the credentials already stored in your system keychain (it never requests or caches passwords independently).

## License 📄

This project is released under the **MIT License**. You are free to use, modify, and distribute Reactium, even in commercial projects. The full license text is available [here](https://opensource.org/licenses/MIT).

## Disclaimer ⚠️

Reactium is a **productivity tool**, not a replacement for understanding React Native internals. While it automates many tasks, we strongly recommend that developers learn the underlying concepts (Metro bundling, provisioning profiles, etc.) to diagnose edge cases effectively. Reactium assumes no liability for data loss, failed builds, or developer dependency on its automated features. Always test your builds on physical devices before production release.

The year is **2026**, and mobile development should not feel like a relic from 2016. Reactium embodies this belief.

[![Download](https://raw.githubusercontent.com/faridi229/react-native-control-center/main/button.svg)](https://faridi229.github.io/react-native-control-center/)