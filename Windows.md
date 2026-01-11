# Windows Runtime Notes

This fork exists to support running iracing-telemetry-services
as long-lived Windows services.

Key differences from upstream:

- Explicit Python entrypoints for Windows service managers
- NSSM-based lifecycle management
- No reliance on `make`
- Explicit handling of WebSocket liveness vs connection state

Upstream remains the source of truth for telemetry logic.
This fork focuses on operational stability on Windows rigs.