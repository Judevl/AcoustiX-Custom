# AcoustiX - Custom Version

This is a **Custom Version of AcoustiX** designed to provide advanced control over filter generation. It introduces the ability to define multiple manual frequency zones for automated filter creation.

---

### 🙏 Acknowledgments

Special thanks to **OCA** for authorizing the share of this custom version. This project is a modification based on his original work.

- **Watch the original project video here:** [https://youtu.be/QvL7ZhcV0dc](https://youtu.be/QvL7ZhcV0dc)

---

## 📥 Download

> [!IMPORTANT]
> **Get the latest version:** Go to the [**Releases**](https://github.com/Judevl/AcoustiX-Custom/releases/latest) section of this repository and download the `.zip` file .

---

## ⚙️ Setup Instructions

### 1. Mandatory Pre-requisites (REW API)

Before launching the software, you must ensure **REW (Room EQ Wizard)** is configured correctly:

- **Open REW.**
- Go to **Preferences** -> **API**.
- Click **"Start Server"**
- The port should be set to the default (**4735**).

### 2. Prepare the original A1 Evo AcoustiX

- **Find your OS version:** Open the folder named `AcoustiX_v2026_03_26`.
- **Copy & Paste:** Copy the original file (e.g., `a1-evo-acoustix-win.exe`, `a1-evo-acoustix-macos`, etc.).
- **Place at Root:** Paste it into the **root directory** of this project.

### 3. Prepare the AcoustiX Custom Version

- **Locate your build:** Open the folder named `AcoustiX_custom`.
- **Copy & Paste:** Copy the file matching your OS (e.g., `AcoustiX-Custom-win-x64.exe`).
- **Place at Root:** Paste it into the **root directory** (the same folder as the original file).

---

## 🚀 How to use

### Step 1: Pre-requisites (Original Version)

Before using the custom version, you must use the **original A1 Evo AcoustiX** file to:

- Perform your measurements.
- Generate the `receiver_config.avr` file.
- Ensure the `measurements.ady` file is present in the root folder.

### Step 2: Running the Software

Follow this specific order to ensure the files interact correctly:

1.  **Launch the original A1 Evo AcoustiX** file first.
2.  **Launch the AcoustiX Custom Version** (e.g., `AcoustiX-Custom-win-x64.exe`).
3.  Your browser will automatically open the interface at: `http://localhost:8090`
4.  All your generated calibrations and logs will be saved in the `OCA_Files` folder at the root.

---

## 📥 Transferring to AVR

Once you have generated your `.oca` file with the custom version, follow these steps to send it to your receiver:

1.  Open the `OCA_Files` folder and **copy** your generated `.oca` file.
2.  **Paste** it directly into the **root directory** of the project.
3.  Use the **original A1 Evo AcoustiX** file to perform the transfer to your AVR.

---

## ✨ Key Feature

- **Multiple Frequency Zones:** Ability to define several frequency ranges where filters will be automatically generated to follow the target curve.

---

> [!TIP]
> **Note for macOS/Linux users:** You might need to authorize the execution of the files. Open your terminal in the root folder and run:  
> `chmod +x AcoustiX-Custom-macos-x64` (or your specific version).
