# GladeKit Unity Plugin

Unity package that connects Unity Editor to the GladeKit desktop application, enabling AI-assisted Unity game development.

## Overview

This repository contains the **GladeKit Unity Plugin**—a Unity package that gets installed into Unity projects to bridge Unity Editor with the GladeKit desktop app. The plugin enables the GladeKit app to directly interact with Unity projects, allowing AI agents to create scripts, edit GameObjects, manage components, and more in real-time.

The plugin:
- Runs a local HTTP server in Unity Editor to communicate with the GladeKit app
- Provides APIs for the GladeKit app to execute tools and gather project context
- Enables real-time synchronization between the GladeKit app and Unity Editor
- Manages backups and change tracking for AI-generated modifications

## Installation

The GladeKit desktop app automatically installs this plugin into Unity projects. When you connect a Unity project in the GladeKit app, it:

1. Checks if the plugin is already installed
2. Downloads the latest release from this GitHub repository if needed
3. Installs it to your Unity project's `Packages/` folder
4. Unity automatically detects and compiles the package

The GladeKit app also checks for plugin updates and notifies you when new versions are available.

## How It Works

The Unity plugin acts as a bridge between Unity Editor and the GladeKit desktop application:

- **Unity Editor** ↔ **Unity Plugin** (this package): Local HTTP server running in Unity
- **Unity Plugin** ↔ **GladeKit App**: The plugin exposes APIs that the GladeKit app calls
- **GladeKit App** ↔ **AI Backend**: The app communicates with the cloud-based AI service

This architecture allows the GladeKit app to control Unity Editor remotely while you interact with the AI through the GladeKit app's chat interface.


## License

© 2026 Glade Tool Inc. All Rights Reserved.

This software is proprietary and licensed under the GladeKit Unity Plugin End User License Agreement (EULA). See the [EULA](../EULA.md) for full terms and conditions.

## Links

- [GladeKit Documentation](https://www.gladekit.com/docs)
- [GladeKit Website](https://www.gladekit.com)
