# ESPFlight Application v1.0.0

First public Android release of the ESPFlight Application.

ESPFlight Application is the official companion app for discovering, configuring, monitoring, and controlling compatible ESPFlight-based drones.

## Highlights

- Automatic discovery of compatible ESPFlight controllers
- Live telemetry and connection status
- ARM / DISARM control
- Beginner and Advanced control modes
- Head Lock
- Takeoff and Landing flows
- PID configuration and tuning
- Flight-state and failsafe feedback
- ESPFlight Protocol 2 compatibility
- English and Persian interface support

## Validated Release Baseline

This release was validated with:

- ESPFlight Firmware v1.0.0
- ESPFlight Hardware Reference v1.0
- Android application ID: `com.espflight.app`
- Application version: `1.0.0`

The assisted Landing flow uses the validated application throttle ramp from 1500 to 1050 over approximately 3 seconds. Firmware safety and final-disarm conditions remain authoritative.

## Release Assets

- `ESPFlight_Application_v1.0.0.apk`
- `ESPFlight_Application_v1.0.0.sha256`

Validated APK SHA-256:

`936d1065f7f7a5efcbe303851db138e64e33983be88ee9dd29763d761a0d2025`

## Installation

Download the APK only from the official ESPFlight website or the official `espflight/application` GitHub Releases page.

Android may ask for permission to install applications from the browser or file manager used to open the APK. Review the prompt carefully and disable that permission again afterward if you do not need it.

## Safety

ESPFlight Application can control real motors and flying hardware. Verify the connected Drone, control directions, ARM / DISARM behavior, and failsafe operation before flight. Perform initial tests with propellers removed whenever practical.

## License

ESPFlight Application is proprietary software. Copyright © 2026 ESPFlight. All rights reserved.

The open-source licenses covering ESPFlight Firmware and the open-hardware license covering the ESPFlight Hardware Reference do not apply to the ESPFlight Application.

**Learn. Build. Fly.**

https://espflight.com
