# GO ON WAY

This repository contains two separate Flutter demo applications:

- `customer_app` — customer ride-booking demo
- `driver_app` — driver-side demo

## Codemagic

The root `codemagic.yaml` defines two workflows:

- `customer-apk`
- `driver-apk`

Each workflow runs `flutter create .`, installs packages, analyzes the app, and builds a debug APK.

## Important

This is source code, not a finished production ride-hailing service. Real maps/GPS, OTP/authentication, payments, backend APIs, notifications, and production signing are not implemented.
