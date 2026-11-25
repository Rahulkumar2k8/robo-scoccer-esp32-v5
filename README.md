# RoboSoccer ESP32 RC Wokwi Lab — V6

The current Android application build is **V6**.

## Android APK

The V6 APK is built by GitHub Actions:

- Workflow: [Build RoboSoccer ESP32 RC Wokwi Lab V6 APK](.github/workflows/build-v6-apk.yml)
- Artifact: `ESP32_RC_Wokwi_Lab-V6-Android-APK`
- Latest verified build: [GitHub Actions run #45680975615](https://github.com/Rahulkumar2k8/robo-scoccer-esp32-v5/actions/runs/45680975615)

Open the workflow run and download the APK from its Artifacts section.

## Source

The V6 Android source archive is stored under `source/v6/chunks/`. The V6 workflow reconstructs and validates the archive before compiling the ESP32 preset firmware and packaging the Android application with Capacitor and the USB-OTG serial bridge.

## Previous version

The V5 source archive and V5 APK workflow are retained in this repository as the previous build baseline. The V6 update does not overwrite the V5 workflow or source archive.
