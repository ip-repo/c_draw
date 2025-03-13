# Drawing On the Screen using C
In this tutorial, we will learn how to draw directly on the screen using the Windows API, starting with simple shapes. 
This involves utilizing powerful `Graphics Device Interface` (GDI) tools provided by `windows.h.`

## Getting Started: Setting up your Environment:
Before we begin, ensure you have:

* A C compiler (e.g., GCC via MinGW for Windows).
* Basic familiarity with C programming.
* Access to the Windows API (`windows.h`), which allows interaction with the graphical interface.

## About windows.h
`windows.h` is the primary header file for the Windows API, and it provides access to a wide range of system functionalities, such as:

* Graphics and User Interface: Functions for drawing (GDI), managing windows, buttons, dialogs, etc.
* File and Process Management: Tools to manage files, processes, and system resources.
* System Events: Capture input from the keyboard and mouse or handle system messages.
* ...

### How to Use windows.h:
On Windows systems, the file is readily available with most C/C++ compilers.

If you're using `MinGW` (Minimal GNU for Windows):
* Install MinGW, and ensure the "Windows API" package is selected during installation.
* Verify that the `windows.h` file exists in your MinGW installation directory (usually under include/).

### Yeah, but what is GDI (`Graphics Device Interface`)?!
The **Graphics Device Interface (GDI)** is a core component of the Windows operating system that allows developers to draw graphics on screens, printers, or other display devices. It is part of the Windows API and provides various tools to create shapes, render text, and handle graphical elements.

**Key Features of GDI:**
* Basic Drawing Functions: GDI allows you to create and manipulate shapes (like rectangles, lines, ellipses), images, and text.
* Device Context (DC): A key concept in GDI, the DC is a handle that links to a drawing surface (screen, window, or printer) and enables you to issue drawing commands.
* High-Level Graphics: GDI abstracts away the hardware details of your display, making it easy to render visuals without worrying about the specifics of the graphics card.



<a href="https://learn.microsoft.com/en-us/windows/win32/gdi/windows-gdi"> Read More About GDI </a>



