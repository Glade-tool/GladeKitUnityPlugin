# GladeKit Unity Plugin

Unity package that connects Unity Editor to the GladeKit desktop application, enabling AI-assisted Unity game development.

## Overview
v1.1.0

This repository contains the **GladeKit Unity Plugin**—a Unity package that gets installed into Unity projects to bridge Unity Editor with the GladeKit desktop app. The plugin enables the GladeKit app to directly interact with Unity projects, allowing AI agents to create scripts, edit GameObjects, manage components, and more in real-time.

The plugin:
- Runs a local HTTP server in Unity Editor to communicate with the GladeKit app
- Provides APIs for the GladeKit app to execute tools and gather project context
- Enables real-time synchronization between the GladeKit app and Unity Editor
- Manages backups and change tracking for AI-generated modifications

## Installation

To install the plugin into a Unity project:

1. Open the GladeKit desktop app
2. Click the install button to install the plugin into your Unity project
3. The app downloads the latest release from this GitHub repository
4. Installs it to your Unity project's `Packages/` folder
5. Unity automatically detects and compiles the package

### Updates

The GladeKit app automatically checks for plugin updates and notifies you when new versions are available. Updates are installed automatically and prompts user when available.

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
