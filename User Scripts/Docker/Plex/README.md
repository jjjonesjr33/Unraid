# 📺 Plex Auto-Update Checker & Notifier

This Bash script checks for the latest **public release** of Plex Media Server, compares it with the currently running version inside a Docker container, and restarts the container if an update is available. It also sends notifications using the [Apprise API server](https://github.com/caronc/apprise-api), supporting services like Discord, Gotify, and more.

---

## ✅ Features

- Automatically compares the current Plex version with the latest official release
- Restarts the Docker container if an update is detected
- Sends a notification via Apprise with the current version, latest version, and status
- Includes the **hostname** of the server in messages for easy tracking across multiple machines
- Works on Unraid and other Docker-based systems

---

## 🧰 Requirements

- [Docker](https://www.docker.com/)
- Apprise API server running and configured with your desired notification URLs
- `jq` installed (`apt install jq` or `apk add jq`, depending on your base OS)



