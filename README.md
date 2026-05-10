**1. Overview**
The Psychology Assessment System is a Windows desktop application built in C# (.NET 8) using Windows Forms. It was developed across two tasks — Task 7.3 (Custom Program Code) and Task 7.4 (Something Awesome) — as part of SIT771 Object-Oriented Development at Deakin University, Trimester 1 2026.
The program implements a multi-instrument psychological assessment engine. Participants select an assessment instrument, enter a participant ID, and respond to a series of questions. The system scores their responses, generates a detailed personalised report, and produces a data visualisation of their results. All results can be saved to and loaded from disk.
The program was designed with three architectural goals that directly mirror the unit learning outcomes: clean object-oriented design (abstraction, encapsulation, inheritance, polymorphism), a data-driven instrument architecture (any well-formed JSON file dropped into the data/ folder is automatically discovered and usable without code changes), and a staged development process documented through a detailed devlog.

**2. How to Run**

Requirements:
.NET 8 SDK (or .NET 8 Runtime)
Windows 10 or later
Visual Studio 2022 (recommended) or the .NET CLI

**   

Clone or download the repository from GitHub
run PsychologyAssessment.exe**


**Important — data/ folder**
The application reads assessment instrument files from a data/ subfolder located next to the compiled executable. The program auto-discovers all valid JSON files in this folder at startup — no code changes are needed to add new instruments.

