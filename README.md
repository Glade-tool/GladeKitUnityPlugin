# GladeKit Unity Plugin

Desktop application that bridges Unity Editor with the GladeKit AI backend, providing a seamless interface for AI-assisted Unity game development.

## Overview

The GladeKit app serves as a bridge between Unity Editor and the GladeKit AI backend. It provides a modern chat interface where developers can interact with AI agents that directly manipulate Unity projects—creating scripts, editing GameObjects, managing components, and more—all in real-time.

The app:
- Connects to Unity Editor when it's running
- Communicates with the GladeKit AI backend
- Manages installation and updates of the Unity plugin from GitHub Releases
- Provides a user interface for AI-assisted game development

## Plugin Installation

The GladeKit app automatically manages the Unity plugin installation by downloading the latest version from the `Glade-tool/GladeKitUnityPlugin` GitHub repository. When a user connects to a Unity project, the app:

1. Checks if the plugin is installed
2. Downloads the latest release from GitHub if needed
3. Installs it to the Unity project's `Packages/` folder
4. Unity automatically detects and compiles the package

The app also checks for plugin updates and notifies users when new versions are available.

## Features

- **AI Chat Interface**: Real-time chat with AI models to assist with Unity development
- **Unity Integration**: Direct communication with Unity Editor to execute changes
- **Automatic Plugin Management**: Installs and updates the Unity plugin from GitHub Releases
- **Change Tracking**: Track and revert AI-generated changes
- **Multi-Project Support**: Work with multiple Unity projects


## License

ISC

## Links

- [GladeKit Documentation](https://www.gladekit.com/docs)
- [GladeKit Website](https://www.gladekit.com)
