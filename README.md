# Android Activity Lifecycle Demonstration

This project is a simple Android application created to demonstrate the fundamental lifecycle of an Android `Activity` and display a basic UI screen.

## AIM

The main goal of this application is to showcase the different states of an Activity's lifecycle. It does this by displaying log messages, toasts, and snackbars for each lifecycle callback method (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onRestart`, and `onDestroy`).

The secondary goal is to create a basic user interface with a styled `TextView` centered on the screen.

### UI Requirements:
*   **Activity Background:** Yellow (`#FFFF00`)
*   **TextView:**
    *   **Text:** "Hello World!"
    *   **Text Color:** Holo Blue Bright (`@android:color/holo_blue_bright`)
    *   **Text Size:** `27sp`
    *   **Text Style:** Bold and Italic

## Core Concepts Demonstrated

This project provides a practical study of several fundamental Android concepts:

-   **Activity Lifecycle:** The core focus of the project. It demonstrates the sequence of states an `Activity` goes through from when it is first created until it is destroyed.
-   **UI Notifications:**
    *   **`Log` Message:** Used to print information to the **Logcat** window for debugging.
    *   **`Toast` Message:** A small pop-up message that appears on the screen for a short duration.
    *   **`Snackbar` Message:** A modern alternative to a `Toast`, which appears at the bottom of the screen.
-   **Basic UI Design:**
    *   **`TextView`:** A standard UI widget used to display text with various style properties.
    *   **`ConstraintLayout`:** A flexible layout manager used here to center the `TextView`.
    *   **In-built Android Resources:** The project uses a pre-defined Android color (`@android:color/holo_blue_bright`).

## Lifecycle Output Demonstration

The application provides real-time feedback for each lifecycle event using three different methods simultaneously.

### 1. Logcat Output

For every lifecycle event, a message is printed to Logcat. You can filter by the tag `ActivityLifeCycle` to see a clean sequence of events as you interact with the app.

<img width="500" height="150" alt="image" src="https://github.com/user-attachments/assets/f3931937-b50c-4d7f-8633-e5a791dea843" />



### 2. Snackbar and Toast Message Output

A `Toast` and a `Snackbar` message are displayed on the screen for each lifecycle event, providing immediate visual feedback directly within the app's UI.

<img width="180" height="424" alt="Screenshot_20250929_215151" src="https://github.com/user-attachments/assets/1591e5e4-b4bd-4b72-9213-858238ffc0b6" />

