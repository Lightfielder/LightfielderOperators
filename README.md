# Lightfielder Operators v26.05

> [!NOTE]
> This repository is still acting as a placeholder. The latest Ops content is in the process of being individually validated and added to the public facing repo that has GitHub visibility enabled.

## Overview

Ops is a [rust language](https://rust-lang.org/) based agentic interface to control and visualize distributed render tasks running on HPC systems. It is cross-platform compatible and works across Linux, Windows, and macOS. A Swift UI based iOS and VisionOS app acts as a thin client to interface with Ops when you are on the go.

The Ops development effort was bootstrapped using open-source LGPL licensed [Kartaverse](https://github.com/Kartaverse) technology.

## Ops Thin Client App

This video shows a pre-alpha version of the Lightfielder Ops thin-client app running on iPadOS. This interface lets you quickly build automation friendly node graphs using the same ideas found in the existing "[Vonk Ultra](https://kartaverse.github.io/VonkUltra/)" data nodes toolset in [Kartaverse](https://kartaverse.github.io/).

With the toolbar controls on the left side of the window, you can hide and show the timeline or the mini-map view, perform file operations, add nodes to the flow, or show the scripts panel.

The docked panel on the right side of the view makes it easy to view and edit scripts / text formatted documents. The object model viewer works with formats like JSON, YAML, and XML. There is a Sheet interface to view table based data like CSV files or an IFL (image file list).

[![Watch the video](https://img.youtube.com/vi/g-jWZtoyN_4/maxresdefault.jpg)](https://www.youtube.com/watch?v=g-jWZtoyN_4)

## GitHub Downloads

Go to the [Releases page](https://github.com/Lightfielder/LightfielderOperators/releases/) to access the latest builds (when they are shipped publicly). The v26.05 update adds initial support for Apple Vision Pro HMDs.

## Table of Contents

- [ReadMe (You are here)](README.md)
- [Install Python](Ops/Docs/Install_Python.md)
- [Install Ops](Ops/Docs/Install.md)
- [Uninstalling Ops](Ops/Docs/Uninstall.md)
- [ChangeLog](Ops/Docs/ChangeLog.md)
- [Presets](Ops/Docs/Presets.md)
- [Unit Tests](Ops/Docs/Unit_Tests.md)
