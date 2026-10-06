# ProjectDock

ProjectDock is a lightweight Windows desktop tool for managing local development projects from one place.

It is designed to solve a simple problem: switching between projects, folders, terminals, VS Code windows, and Git repositories gets annoying.

## Features

* View all your development projects in one dashboard
* Open a project directly in VS Code
* Open PowerShell in a project directory
* Open the project folder in File Explorer
* View the current Git branch
* Detect uncommitted Git changes
* Open a project's GitHub repository
* Search projects quickly
* Store projects locally

## Tech Stack

* Electron
* Node.js
* HTML
* CSS
* JavaScript
* Git

## Project Structure

```text
ProjectDock/
├── main.js
├── preload.js
├── package.json
└── src/
    ├── index.html
    ├── renderer.js
    └── style.css
```

## Running ProjectDock

Clone the repository:

```bash
git clone <repository-url>
cd ProjectDock
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm start
```

## Why ProjectDock?

ProjectDock started as a personal tool to reduce the friction of working across multiple development projects.

Instead of repeatedly navigating through folders and opening terminals manually, ProjectDock provides a single place to launch and inspect projects.

## Roadmap

* [ ] Project auto-discovery
* [ ] Project favorites
* [ ] Git status details
* [ ] Git commit/push shortcuts
* [ ] Dev-server launcher
* [ ] Project notes
* [ ] Custom project icons
* [ ] Keyboard shortcuts
* [ ] Project templates
* [ ] Windows startup option

## Status

ProjectDock is currently in early development.

The initial goal is to build a small, fast, useful tool first and expand it based on real usage.

## License

This project is currently private and is not licensed for redistribution.
