# MediaDroidXML

Welcome to **MediaDroidXML**, a collection of custom Android Studio hardware profile XML files.

When developing Android applications—especially when fine-tuning UIs with Kotlin and Jetpack Compose—having accurate hardware representations is essential. This repository provides exact device specifications that can be imported directly into the Android Studio Device Manager, allowing for precise emulation across a wide spectrum of mobile hardware.

## What's Included

This collection documents everything from modern rugged phones to classic legacy hardware. The profiles include accurate API levels, resolutions, and screen specifications for devices across various manufacturers:

*   **Samsung:** Galaxy S4 (useful for testing classic environments or specific carrier variants like the Cricket Wireless rollouts), Galaxy S5, Galaxy S9, Galaxy S2 Plus, Galaxy A14 5G, Galaxy Tab A7 Lite, Galaxy S7 active, and Galaxy S4 mini.
*   **Motorola:** Moto E5 Play, Moto G (2024), and Moto G (2025).
*   **LG:** G Pad 7.0 LTE and L60 Dual.
*   **ZTE:** Blade L110 and Grand X View 2.
*   **Rugged & Specialty:** CAT S22 Flip, CAT S60, Energizer Hardcase H550S, and Sonim XP8.
*   **Other Manufacturers:** Lenovo S5000, Micromax (A106 Unite 2, Canvas Sliver 5 Q450), and Umidigi G9x.

## How to Use

1. Download or clone this repository to your local machine.
2. Open **Android Studio**.
3. Navigate to the **Device Manager** (`Tools` > `Device Manager`).
4. Click on **Create Device**.
5. In the bottom-left corner of the hardware selection window, click **Import Hardware Profiles**.
6. Select the `.xml` files from this repository that you wish to add.
7. The imported devices will now appear in your hardware list, ready to be paired with a system image for your AVD.

## License

This project is open-source and available under the [Apache-2.0 License](LICENSE).
