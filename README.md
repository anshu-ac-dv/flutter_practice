# Flutter Learning

## 🟢 Level 1: Flutter & Dart Foundations (The "Junior" Base)
Target: Being able to build a functional, multi-screen app from scratch.

### Dart Basics
>* Null Safety: Mastery of ?, !, late, and required.
>* Collections: Using .map(), .where(), and .fold() to manipulate data.
>* Asynchronous Basics: Future, async, and await for simple API calls.

### Flutter UI
>* The Big Three: StatelessWidget, StatefulWidget, and BuildContext.
>* Layout Engine: Understanding constraints ("Constraints go down, sizes go up, parent sets position").
>* Navigation: Basic Navigator.push/pop and the concept of a "Route."

## 🟡 Level 2: Scalable Development (The "Mid-Level" Standard)
Target: Building apps that can handle 1,000+ users and complex data.

### Architecture & Clean Code
>* SOLID Principles: Learning how to write code that is easy to change and test.
>* Separation of Concerns: Moving logic out of widgets and into Controllers or BLoCs.
>* Dependency Injection (DI): Using tools like get_it or Provider to manage object lifecycles.

### State Management
>* Riverpod 3.0 (2026 Trend): Currently the industry favorite for its compile-time safety and lack of boilerplate.
>* BLoC / Cubit: The enterprise standard. If you want a job at a large bank or fintech company, you must know BLoC for its strict event-driven audit trails.

### Networking & Persistence
>* Http: Advanced usage like Interceptors (for refreshing tokens) and request cancellation.
>* Local Databases: Isar (the successor to Hive) or Sqflite for offline-first apps.

## 🔴 Level 3: Performance & Mastery (The "High-Paying" Skillset)
Target: Optimizing apps for low-end devices and complex enterprise needs.

### Advanced Dart
>* Isolates: Moving heavy JSON parsing or image processing to a background thread to prevent UI "jank."
>* Streams & RxDart: Handling real-time data (chat apps, stock tickers, or sensor data).
>* Extensions & Mixins: Creating high-quality, reusable utility libraries.

### Flutter Internals
>* The Three Trees: How the Widget, Element, and RenderObject trees interact.
>* Impeller vs Skia: Understanding the rendering engine to fix frame-rate drops.
>* Custom Painting: Using CustomPainter to build unique, high-performance UI components that standard widgets can't handle.

### DevOps & Testing (The Hiring Decider)
>* Testing: Writing Unit Tests for logic, Widget Tests for components, and Integration Tests (Patrol) for end-to-end flows.
>* CI/CD: Setting up GitHub Actions or Codemagic to automate app deployments.
>* Platform Channels: Writing native code (Swift/Kotlin) when Flutter doesn't have a specific plugin.