# C# Paint V2 (Creative Mode)

A modern, feature-rich painting application built using C# and Windows Forms (.NET 9.0). This application offers a traditional "MS Paint" style experience with several creative additions, providing both basic drawing functionality and advanced features like a rainbow pen and spray can.

## Features

- **Standard Drawing Tools:** 
    - ✏️ Pencil
    - 📏 Line
    - ⬜ Rectangle
    - ⭕ Ellipse
    - 🧽 Eraser
    - 🪣 Fill Bucket
- **Creative Tools:**
    - 💨 Spray Can: Add textured spray effects configurable by brush size.
    - 🌈 Rainbow Pen: A dynamic pen that cycles through the HSL color spectrum as you draw.
- **Workflow & Usability:**
    - ↩️ Undo / ↪️ Redo support: Safely revert or re-apply changes (Shortcuts: `Ctrl+Z` / `Ctrl+Y`).
    - 🌓 Dynamic Theming: Switch securely between Dark and Light mode.
    - 🎨 Color Picker: Easily select any custom color for your tools.
    - Size adjusting dropdown: Increase or decrease brush thickness (sizes from 1 to 48).
- **File Management:** Create New drawings, Open existing image files (`.png`, `.jpg`, `.bmp`), and Save your creative work.

## Requirements

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0) or later.
- Visual Studio 2022 (or any compatible IDE) supporting Windows Forms development.

## Running the Application

1. Open the project in Visual Studio or your preferred IDE.
2. Build the solution.
3. Run the `PaintingApp` project.

Alternatively, you can run it from the command line using the .NET CLI:
```bash
dotnet run
```

## Shortcuts
- `Ctrl+N` : New Drawing
- `Ctrl+O` : Open Image
- `Ctrl+S` : Save As...
- `Ctrl+Z` : Undo
- `Ctrl+Y` : Redo

## Code Structure

- `MainForm.cs`: Handles all form UI elements, tool initialization, drawing logic, theming, undo/redo stack, and file operations.
- `Enums.cs`: Custom enumerations for tools (e.g., `ToolType`).
- `Program.cs`: Setup and entry point of the Windows Forms Application.
