# SubSystems

**Acoustic prediction software for live subwoofer system design.**

SubSystems simulates the coherent sum, in magnitude and phase, of every subwoofer (and main and fill speaker) over the listening area. It lets you compare layouts, optimise delays and polarity, and export the rigging and tuning documentation. It also recommends which layouts and configurations to use for your venue, based on its geometry, the audience, the stage and the obstacles.

## Features

* **SPL map** in 2D plan and 3D view, with vertical sections and virtual microphones (frequency response and A/C/Z weighted level).
* **Typical sub configurations**: ground L/R, centre line, line with electronic arc, cardioid blocks, end-fire. Each comes with a recommended tuning, spacing and opening.
* **Palco pulito** (stage cancellation): a dedicated group of subs that removes low-frequency energy from the stage while protecting the audience.
* **Mixed**: multi-criteria optimisation that tries every layout and applies the best one for your priorities.
* **Score**: coverage, frequency response, distance, obstacles, stage level and summation efficiency, rated 0 to 5 stars.
* **Mains and fills**: point sources and line arrays with 3D directivity, recommended splays, crossover, all-pass, EQ and linear-phase FIR design.
* **Environment**: rigid or porous ground, temperature and humidity, sloping terrain, obstacles with diffraction and reflections.
* **Global alignment** of mains, fills and sub groups with one click.
* **PDF export** for rigging and tuning: sub plan to the millimetre, front views, settings tables for every output, issues and advice.
* **GPU acceleration** with automatic fallback to CPU.

## System requirements

* Windows 10 or 11, 64-bit.
* A DirectX 12 capable graphics card. A card with compute shader support speeds up the calculation; without one, the CPU is used.
* An internet connection for the first sign-in and to renew the licence.

## Installation

1. Download `SubSystems.zip` from the assets of this release.
2. Extract it to a folder of your choice, for example `C:\\Program Files\\SubSystems`.
3. Run the executable inside the extracted folder.

No installer is needed. To uninstall, delete the folder.

If Windows SmartScreen shows "Windows protected your PC", click **More info** and then **Run anyway**.

## Account and licence

* On first launch, sign in with your account or register a new one.
* A new account gets a **7-day free trial** straight away. The trial can be claimed once per account.
* The full licence is **annual** and can be activated on up to **2 computers**.
* After signing in, the software also works **offline** for up to 72 hours and 7 launches, never beyond the licence expiry. Connect to the internet to renew.

## Documentation

The user manual is included in the zip, in Italian and English:

`

* `SubSimulator-user-manual-EN.pdf`
* `SubSimulator-manuale-utente.pdf`

Hover over any control in the software for an explanation of what it does. The guided setup reopens at any time with the **Guida** button.

## Notes

* The interface is currently in Italian. The English manual keeps the Italian names of the controls, with a translation.
* Projects are saved as `.subsim.json` files wherever you choose. The current session is also saved automatically.
* Every library model has its DSP latency set to 0 ms. If you combine models from different product families, enter their real latency in a custom model.

## Support

For questions, bug reports or licence requests, contact: **\[info@ledwell.it]**

\---

© 2026 SubSystems. All rights reserved. This software is licensed, not sold; redistribution is not permitted.

