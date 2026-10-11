<p align="center">
  <img width="746" alt="imagen" src="https://github.com/user-attachments/assets/5ecc8720-4eaa-4cf7-a659-d72c07445f47" />
  <br />
  <img width="380" alt="imagen-removebg-preview" src="https://github.com/user-attachments/assets/41dbd45b-3586-436a-ae8d-0f2667cce2aa" />
</p>

<p align="center">
  <a href="https://github.com/EdddySh/TizenTube-Script-Changer/releases/latest">
    <img src="https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge&logo=github" alt="Download Latest Release" />
  </a>
</p>

<p align="center">
  📥 <b><a href="https://github.com/EdddySh/TizenTube-Script-Changer/releases/latest">Click here to download the Script (ZIP)</a></b>
</p>

---

A simple PowerShell tool to decompile, inject/update scripts, and rebuild/sign TizenTube APKs without manual setup.

The entire process is fully transparent and guided via console. You can right-click both the `.bat` launcher and the `.ps1` script to inspect the code—everything is cleanly commented so you can verify exactly what each line does.

#### 📦 What's included:
- **Batch launcher (`##Lanzador.bat`)**: Quick launcher (just triggers the PowerShell script).
- **Main automation script (`.ps1`)**: Step-by-step commented automation script.
- **Preconfigured tools**: Apktool, zipalign, apksigner, and a default keystore.
- **Portable setup**: Just extract and run (no manual environment variables or tool installation needed).

#### ⚙️ How it works:
1. Decompiles the base APK.
2. Injects or updates the TizenTube script directly into the assets.
3. Rebuilds the APK with a new name and icon.
4. Aligns and signs it, ready to install on your device.

#### 🚀 How to use:
1. Download the portable package from the [Releases section](https://github.com/EdddySh/TizenTube-Script-Changer/releases/latest).
2. Extract the archive and place your base APK inside the folder.
3. Double-click `##Lanzador.bat` (or right-click the `.ps1` script and run it with PowerShell).
4. Follow the on-screen instructions. The patched and signed APK will be generated inside the `Modified APK` subfolder.

#### ⚠️ Disclaimer:
This tool is intended for educational and personal use only. It is an independent contribution made to simplify the process and improve user experience; it is not affiliated with, endorsed by, or connected to Google, YouTube, or the original creators/developers of the TizenTube project. Use at your own risk.
