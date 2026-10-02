# The Elder Scrolls V: Skyrim VR

## Pack metadata

- **Game:** The Elder Scrolls V: Skyrim VR
- **Crowd Control game ID:** `SkyrimVR`
- **Connector:** `SimpleTCPServerConnector`
- **Port:** `59420`

This folder contains the C# Crowd Control pack definition and VR-specific plugin/source components for **Skyrim VR**.

## Connector and setup

`SkyrimVR.cs` selects `SimpleTCPServerConnector`. A VR plugin/source layout is present; no root installation command is documented.

## Layout

- `SkyrimVR.cs` — pack definition and effect catalog.
- `Skyrim VR Plugin\` and `Source\` — game-side plugin and source.

## Development

Validate changes against the VR-specific plugin rather than an SE/AE variant.
