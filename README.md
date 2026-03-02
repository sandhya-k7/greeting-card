# greeting-card
Jetpack Compose Greeting Card app built using Kotlin and Android Studio. Demonstrates setContent, @Composable functions, Scaffold layout, and Material 3 components. Includes troubleshooting of SDK setup, package refactoring, and build errors while implementing a simple dynamic greeting U

That’s the right move. If you’re putting something on GitHub, it should look intentional — not like a classroom submission.

Here’s a **professional, portfolio-ready README.md** you can directly use.

---

```markdown
# 📱 Greeting Card App – Jetpack Compose

![Kotlin](https://img.shields.io/badge/Kotlin-1.9-blue)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Material3-brightgreen)
![Android](https://img.shields.io/badge/Android-API%2036-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview

This project is a foundational Android application built using **Kotlin** and **Jetpack Compose** as part of the *Android Basics with Kotlin* pathway.

The application demonstrates modern Android UI development using a declarative approach. Instead of traditional XML layouts, the UI is built entirely using composable functions in Kotlin.

This project focuses on:

- Understanding `setContent {}` lifecycle integration
- Creating reusable `@Composable` functions
- Implementing Material 3 components
- Managing project structure and package refactoring
- Debugging SDK and build issues

---

## 🏗 Architecture & Design

The app follows a simple **single-activity Compose architecture**:

- `MainActivity` serves as the entry point.
- UI is defined using composable functions.
- Material 3 theme is applied globally.
- Layout is structured using `Scaffold` and `Surface`.

The design adheres to modern Android development best practices by:
- Avoiding XML layouts
- Using declarative UI principles
- Structuring code modularly

---

## 🛠 Tech Stack

| Technology        | Purpose |
|------------------|----------|
| Kotlin           | Primary programming language |
| Jetpack Compose  | Declarative UI framework |
| Material 3       | UI components and theming |
| Android Studio   | Development environment |
| Gradle           | Build automation |

---

## 📂 Project Structure

```

app/
└── src/
└── main/
├── java/com/example/greetingcard/
│    ├── MainActivity.kt
│    └── ui/theme/
└── res/

````

---

## 🚀 Core Implementation

### 🔹 setContent { }

Defines the composable hierarchy inside the Activity lifecycle.  
It replaces `setContentView()` used in XML-based UI development.

```kotlin
setContent {
    GreetingCardTheme {
        Scaffold {
            Greeting("Android")
        }
    }
}
````

---

### 🔹 @Composable Functions

Composable functions define UI elements declaratively:

```kotlin
@Composable
fun Greeting(name: String) {
    Surface(color = Color.Blue) {
        Text(text = "Hi my name is $name!")
    }
}
```

These functions are:

* Reusable
* Reactive
* Automatically recomposed when state changes

---

## ⚙️ Setup & Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/greeting-card-compose.git
   ```

2. Open the project in **Android Studio**

3. Sync Gradle dependencies

4. Run using:

   * Android Emulator
   * Or physical Android device

---

## 🧪 Build Configuration

* **Target SDK:** 36.1
* **Build Tools:** 36.1
* **Platform Tools:** 36.0.2
* **Minimum SDK:** As defined in project configuration

---

## 🐞 Challenges & Debugging Experience

### 1️⃣ SDK Installation Failure

**Issue:**
`java.net.UnknownHostException: dl.google.com`

**Root Cause:**
Network/DNS resolution failure.

**Resolution:**

* Switched network
* Updated DNS settings (8.8.8.8 / 8.8.4.4)
* Restarted Android Studio

---

### 2️⃣ Package Name Mismatch

Incorrect package naming caused theme import failures.

**Fix:**

* Used `Refactor → Rename`
* Cleaned and rebuilt project

---

### 3️⃣ Missing Imports in Compose

Resolved compilation errors by adding required Compose and Activity imports.

---

## 📸 Application Preview

*(Add emulator screenshot here)*

```
![App Screenshot](screenshot.png)
```

---

## 📚 Key Learning Outcomes

* Understanding declarative UI with Jetpack Compose
* Integration of Compose within Activity lifecycle
* Material 3 theming structure
* Practical debugging of SDK and build errors
* Importance of consistent package naming
* Proper refactoring workflow in Android Studio

---

## 🔮 Future Improvements

* Add user input field
* Introduce state management
* Implement ViewModel architecture
* Add navigation between screens
* Improve UI styling and layout

---

## 👩‍💻 Author

**Sandhya Patel**
Android Developer | Data Science Enthusiast | AI & ML Learner

---

## 📄 License

This project is developed for educational purposes as part of Android learning coursework.

```

---

This version:

- Looks serious
- Shows technical understanding
- Demonstrates debugging ability
- Reflects growth mindset
- Is suitable for recruiters viewing your GitHub

If you want, I can now:
- Add a more advanced “About Me” developer section
- Or help you structure your GitHub profile professionally  

You’re building good foundations. Let’s make sure your GitHub reflects that.
```
