
# 🎲 Dice Roller Android App

A simple Android app built using **Kotlin** and **Jetpack Compose** that simulates the rolling of a dice. On each tap of the "Roll" button, a new dice face is displayed at random.

---

## 📱 Overview

This project was developed and submitted as part of the **Mobile Application Development** unit at **Strathmore University**.

**Contributors:**
- Celestine Kariuki – Student No. **116533**
- Mumo Mwangangi – Student No. **165437**

---

## 🚀 Features

- Dice face changes randomly between 1 to 6 when the "Roll" button is clicked.
- Built with **Jetpack Compose**, Android’s modern declarative UI toolkit.
- Responsive and state-driven UI with smooth recomposition on state updates.

---

## 🛠️ Tech Stack

| Tech | Version | Description |
|------|---------|-------------|
| Kotlin | 1.9+ | Primary language |
| Jetpack Compose | 1.6+ | Declarative UI framework |
| Android Gradle Plugin | 8.3+ | Build system |
| Min SDK | 21 | Compatible with most Android devices |
| Target SDK | 34 | Optimized for Android 14 |
| Material 3 | ✓ | Used for buttons and text styling |

---

## 📁 Project Structure

```plaintext
/app
 └── src
     └── main
         ├── java/com/example/diceroller
         │   └── MainActivity.kt
         └── res
             ├── drawable/
             │   ├── dice_1.png
             │   ├── dice_2.png
             │   └── ... up to dice_6.png
             └── values/
                 └── strings.xml
````

---

## 🔧 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/dice-roller.git
   cd dice-roller
   ```

2. **Open the project in Android Studio:**

   * File > Open > Select the project folder.

3. **Check minimum setup:**

   * Android Studio Giraffe or later.
   * Kotlin plugin updated.
   * Gradle sync should complete successfully.

4. **Ensure resource images are present:**

   * Inside `res/drawable/`, add six PNGs named: `dice_1.png`, `dice_2.png`, ..., `dice_6.png`.

5. **Run on emulator or physical device:**

   * Hit the **Run** ▶️ button.

---

## 📸 Screenshot

<img src="Screenshot 2025-06-14 212104.png" width="300" alt="App Screenshot" />

---

## 🧾 License

This project is submitted for academic purposes. All rights reserved to the contributors and Strathmore University.

```

