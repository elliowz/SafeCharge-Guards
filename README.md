# ⚡ SafeCharge Guard
**Smart Charging Temperature Protection for Android**

SafeCharge Guard is a universal Android root module designed to provide smarter battery temperature monitoring and charging protection through an intuitive **KernelSU WebUI**.

Featuring a modern and easy-to-use interface, SafeCharge Guard gives users control over the module's temperature protection system. You can freely enable or disable temperature protection depending on your preferences.

### ✨ Features
- **KernelSU WebUI** — Modern interface for managing and monitoring the module.
- **Temperature Protection Toggle** — Easily enable or disable the temperature protection system.
- **Flexible Protection** — Use temperature protection or disable the module's guard functionality entirely.
- **Battery Temperature Monitoring** — Monitor real-time battery temperature.
- **Charging Current Monitoring** — View battery charging current when supported by your device.
- **Battery Cycle Count** — Monitor battery charge cycles when available.
- **Universal Compatibility Design** — Designed for a wide range of Android devices running Magisk or KernelSU.
- **Lightweight Background Service** — Minimal background monitoring overhead.

### 🔧 Compatibility
- Magisk
- KernelSU / KernelSU Next
- Android devices with compatible battery interfaces.


### ⚙️ How It Works
SafeCharge Guard monitors battery temperature and provides a configurable temperature protection mechanism.

By default, the temperature threshold is set to **42°C**, with automatic recovery at **40°C** to prevent repeated charging state changes.

Device-level charging cutoff requires a validated, device-specific kernel control interface. Without it, the module operates in monitoring-only mode.

### ⚠️ Disclaimer
SafeCharge Guard does not force fast charging, increase charging voltage/current, or bypass OEM charging protocols. Actual charging speed remains controlled by your device, charger, kernel, and firmware.

Device compatibility and charging-control functionality may vary depending on kernel and hardware implementation.

**Developed by Elliowz**
