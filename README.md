# Universal Clicker Pro v2.0

A powerful, lightweight, and customizable automation tool for Windows. Map any keyboard hotkey to specific screen coordinates and execute complex actions like `Alt + Click`, `Shift + Right Click`, or simple key presses.

![Interface Preview](https://via.placeholder.com/600x400?text=Universal+Clicker+Pro+UI) *(Note: Replace this with a real screenshot of your app)*

## 🚀 Features

*   **Dynamic Slots:** Add or remove as many macro buttons as you need.
*   **Custom Actions:** Supports complex combinations (e.g., `alt+left`, `ctrl+shift+v`, `right`, `f5`).
*   **Coordinate Picker:** Built-in tool to capture X/Y screen coordinates with a 3-second delay.
*   **Active/Inactive Toggles:** Enable or disable specific macros without deleting them.
*   **Persistent Settings:** Automatically saves your configuration to a `config.json` file.
*   **Modern UI:** Clean dark-themed interface built with `CustomTkinter`.
*   **Global Hotkeys:** Works even when the application is minimized.

## 🛠 Installation

### Option 1: Running from Source
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/universal-clicker-pro.git
   cd universal-clicker-pro
   ```
2. Install dependencies:
   ```bash
   pip install customtkinter pyautogui keyboard
   ```
3. Run the app:
   ```bash
   python app.py
   ```

### Option 2: Portable EXE
Download the latest `app.exe` from the [Releases](https://github.com/yourusername/universal-clicker-pro/releases) page.

## 📖 How to Use

1.  **Add a Slot:** Click "+ Добавить кнопку" (Add Button) to create a new macro.
2.  **Pick Coordinates:** Click "Узнать коорд." (Get Coords). You have 3 seconds to move your mouse to the desired spot.
3.  **Set Hotkey:** Enter the key you want to press (e.g., `1`, `f`, `g`).
4.  **Define Action:** Specify what should happen at those coordinates:
    *   `left` - Simple Left Click
    *   `alt+left` - Alt + Left Click
    *   `shift+right` - Shift + Right Click
    *   `f5` - Press F5 key
5.  **Run:** Click the green "ЗАПУСТИТЬ" (START) button.

## ⚠️ Important Notes

*   **Admin Rights:** This application requires **Administrative Privileges** to simulate mouse and keyboard input in most games and system windows. Right-click the EXE and select **"Run as Administrator"**.
*   **Game Compatibility:** For best results in games, use **"Windowed"** or **"Borderless Windowed"** mode.
*   **Safety:** This tool is for personal productivity. Use responsibly in online games to avoid anti-cheat detection.

## 🔧 Technical Stack

*   **Language:** Python 3.x
*   **GUI Framework:** [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)
*   **Input Simulation:** [PyAutoGUI](https://github.com/asweigart/pyautogui)
*   **Hotkey Management:** [Keyboard](https://github.com/boppreh/keyboard)

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
