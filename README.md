# Online Exam Simulator with Anti-Cheat System — Project Documentation

This repository contains the **system analysis and design documentation** for the existing [Online Exam Simulator with Anti-Cheat System (OES-ACS)](https://github.com/RZBv2/Online_Exam_Simulator_with_ACS) project. It is a companion documentation repository, not the application’s source-code repository. Visit the linked project repository for the application source code, requirements, and run instructions.

## About the documented project

OES-ACS is a Python desktop application for managing and taking examinations. Teachers can create and manage exams, while students can take timed exams and submit answers. The application uses local SQLite storage and includes anti-cheat event monitoring intended to record certain suspicious activities, such as attempted window switching. These records are supporting evidence only; they do not prove misconduct or eliminate cheating.

## Documents in this repository

- [`Document.pdf`](Document.pdf) — system analysis and design report, covering project scope, requirements, feasibility, structured analysis, database and interface design, prototype screens, testing, implementation, security, and ethical considerations.

- [`Team_Underscore.pptx`](Team_Underscore.pptx) — presentation for the project.

## Project authors

The presentation credits **Team Underscore** as the project team. The current project documents do not list the individual team members by name. The initial commit in this documentation repository is attributed to **MD. Razab Ali**; this is a repository commit attribution, not a substitute for an individual author list.

## Documented technology and scope

The report describes a desktop solution built with Python, Tkinter, and SQLite, with password hashing and local application logging. It presents the system as a small-scale academic prototype. The full anti-cheat behavior is Windows-dependent and may require optional packages such as `keyboard` and `pywin32`.

The documented scope does not include cloud synchronization, camera-based remote proctoring, biometric verification, multi-institution support, email notifications, or web/mobile clients. The report also notes that technical faults or accessibility tools can affect anti-cheat signals. Monitoring should be disclosed to students, and a log must not be used as the sole basis for disciplinary action.

## Related repository

[Open the OES-ACS application project](https://github.com/RZBv2/Online_Exam_Simulator_with_ACS) for the existing application, its README, source code, and setup instructions.
