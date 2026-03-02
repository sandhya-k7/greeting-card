# greeting-card
Jetpack Compose Greeting Card app built using Kotlin and Android Studio. Demonstrates setContent, @Composable functions, Scaffold layout, and Material 3 components. Includes troubleshooting of SDK setup, package refactoring, and build errors while implementing a simple dynamic greeting U
Greeting Card App – Jetpack Compose
Overview
This project is a foundational Android application built using Kotlin and Jetpack Compose. The
application demonstrates modern Android UI development using a declarative approach. Instead of
XML layouts, the UI is built entirely using composable functions in Kotlin.
Tech Stack
• Kotlin – Primary programming language
• Jetpack Compose – Declarative UI framework
• Material 3 – UI components and theming
• Android Studio – Development environment
• Gradle – Build automation
Architecture & Design
The app follows a single-activity Compose architecture. MainActivity serves as the entry point. UI is
defined using composable functions and styled using a Material 3 theme. Layout is structured using
Scaffold and Surface components.
Challenges & Debugging
• Resolved SDK installation error caused by DNS/network configuration issues.
• Corrected package name mismatch using Refactor → Rename.
• Fixed missing imports related to Scaffold, padding, and enableEdgeToEdge().
Key Learning Outcomes
• Understanding declarative UI with Jetpack Compose.
• Integrating Compose within the Android Activity lifecycle.
• Applying Material 3 theming structure.
• Debugging SDK and build configuration issues effectively.
• Maintaining consistent project structure and naming conventions.
Future Improvements
• Add user input and state management.
• Introduce ViewModel architecture.
• Implement multi-screen navigation.
• Enhance UI styling and layout responsiveness
