# Part C: Practical Task — Greeting App

## Introduction

This Flutter application allows the user to type their name into a **TextField**.  
When the user presses the **“Say Hello”** button, the app displays a personalized greeting message:  
**“Hello, [Name]!”** below the button.

---

## How the App Works

### **Single Screen App**
- The app begins with the `main()` function, which runs the `MyApp` widget.
- The `MyApp` widget loads the home screen — `GreetingApp` — which is a **StatefulWidget**.
- The `TextField` lets the user input their name.
- When the **“Say Hello”** button is pressed:
    - The app retrieves the text from the input field.
    - It then updates the screen to display a greeting message using **setState()**.
- If the input is empty, the app asks the user to enter their name instead of displaying a greeting.

---

- **Developed by:** Janlee Estoy
- **Course:** Computer Engineering
- **Part C:** Practical Task — Greeting App

