# 📚 MKS Robin Nano V1 Firmware Configuration (Tuorum Repo)

## 📖 Overview
This repository contains **Marlin firmware configuration files** (`Configuration.h` and `Configuration_adv.h`) tailored for the **MKS Robin Nano V1** mainboard, commonly used in Toybox Alpha 3D printers. Developed by **Tuorum**, these configurations optimize hardware performance and enable advanced features.

---

## 🛠️ Key Features
- **Custom Configuration Files:** `Configuration.h` and `Configuration_adv.h` tailored for Toybox Alpha hardware.
- **Compatibility:** Optimized for the MKS Robin Nano V1 controller.
- **Ready for Compilation:** Easily compile with Marlin firmware.
- **SD Card Flashing Support:** Firmware can be flashed directly using an SD card slot on your printer.

---

## 🚀 How to Flash the Firmware

### 📤 **Method 1: Flash via SD Card**
1. **Rename the Firmware File:**  
   - Ensure the firmware file is named **`Robin_nano35.bin`**.
2. **Copy to SD Card:**  
   - Place the renamed file in the **root directory** of your SD card.
3. **Insert SD Card:**  
   - Insert the SD card into your printer's SD card slot.
4. **Power Cycle the Printer:**  
   - Turn on the printer. The firmware will automatically flash.
5. **Verify Installation:**  
   - After flashing, the file may rename itself to `Robin_nano35.cur`, indicating a successful installation.

### 🛠️ **Method 2: Flash via USB (STM32CubeProgrammer)**
1. Replace `Configuration.h` and `Configuration_adv.h` in your Marlin source directory.
2. Compile firmware using [PlatformIO](https://platformio.org/).
3. Flash via [STM32CubeProgrammer](https://www.st.com/en/development-tools/stm32cubeprog.html).

---

## 📂 Available Files
- **`MKS_Marlin_2x`:** Custom configuration files for Marlin 2.x firmware.
- **`MKS_Robin_Nano_V1_old_firmware`:** Legacy configuration files.
- **`Marlin-2.1.2`:** Stable version with updated configurations.
- **`Toybox-ALPHA-main-controller-firmware.bin`:** Pre-compiled firmware binary.
- **`Toybox-Controller-Top.jpg`, `Toybox-Controller-Bottom.jpg`:** Reference hardware images.

---

## 💡 Tips & Troubleshooting
- Backup your firmware before flashing.
- Verify your printer supports SD card flashing.
- If flashing via SD card fails, use the USB method as a fallback.
- Check the `Robin_nano35.cur` file to confirm successful firmware flashing.

---

## 🤝 Credits
- **Firmware Configurations by:** [Tuorum](https://github.com/tuorum)
- Integrated with permission into **Project: I.M.P**

---

## 💬 Community Support
- Join our [Discord Server](https://discord.gg/MRNPytp6)
- Explore the [Project: I.M.P Wiki](https://github.com/ProtoModder/Project-I.M.P/wiki)

## 🔗 Useful Links
- [Marlin Firmware Documentation](https://marlinfw.org/docs/)
- [MKS Robin Nano V1 Details](https://reprap.org/wiki/MKS_Robin_Nano_V1.2)

---

This README now includes accurate SD card flashing instructions with the correct filename and structure. Let me know if there’s anything else you’d like to tweak! 🚀
