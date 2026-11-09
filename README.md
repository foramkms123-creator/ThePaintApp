# Custom Paint & Sketch Application

A feature-rich, interactive drawing application developed natively for Android. This project provides a custom digital canvas for users to create freehand artwork, featuring a streamlined toolset for drawing, editing, and exporting images directly to the device's local storage.

## Core Features
*   **Interactive Canvas:** A custom `View` drawing surface that accurately tracks user touch events for smooth, real-time freehand sketching.
*   **Color Selection Palette:** Integrated options allowing users to quickly switch between multiple active paint colors dynamically.
*   **Unified Stroke Sizing:** A single, intuitive slider control (`SeekBar`) that simultaneously adjusts the stroke width for both the paintbrush and the eraser, providing a consistent stroke weight when transitioning between drawing and correcting.
*   **Eraser Tool:** A dedicated toggle that switches the paint configuration to clear pixels, utilizing the shared stroke size parameter to remove specific parts of the drawing.
*   **Undo Action:** A state-management feature that stores previous drawing paths, allowing users to revert their most recent strokes step-by-step.
*   **Gallery Export:** Built-in rendering functionality that securely saves the finalized `Bitmap` file directly to the device's native photo gallery.

## Technical Stack
*   **User Interface:** XML
*   **Application Logic:** Java (Android SDK)
*   **Graphics Engine:** Native Android `Canvas`, `Paint`, `Path`, and `Bitmap` classes
*   **Storage:** Android `MediaStore` API

## Academic Context
Developed as part of the Diploma in Computer Engineering coursework at Government Polytechnic Mumbai.

## Developer
Developed by Foram Mitesh Shah.