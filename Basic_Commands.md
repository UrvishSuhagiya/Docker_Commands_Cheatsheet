# 🚀 Docker_Commands_Cheatsheet

## 📚 Basic Docker Commands

| Command | Description |
|---|---|
| `docker --version` | 🐳 Displays Docker version. |
| `docker help` | 🆘 Displays Docker CLI help. |
| `docker ps -a` | 📋 Lists all containers (active and inactive). |
| `docker ps` | 📋 Lists running containers. |
| `docker start <container_id>` | ▶️ Starts a container. |
| `docker stop <container_id>` | ⏹️ Stops a container. |
| `docker restart <container_id>` | 🔄 Restarts a container. |
| `docker pause <container_id>` | ⏸️ Pauses all processes within a container. |
| `docker unpause <container_id>` | ▶️ Unpauses a container. |
| `docker kill <container_id>` | ❌ Kills a container (forcefully stops). |
| `docker attach <container_id>` | 📶 Attaches local standard input, output, and error streams to a running container. |
| `docker logs <container_id>` | 📝 Displays logs of a container. |
| `docker inspect <container_id>` | 🔍 Inspects the configuration of a container. |
| `docker stats` | 📊 Checks resource usage statistics of running containers. |
| `docker events` | ⚡ Views real-time events from the Docker server. |
| `docker export <container_id> > <filename>.tar` | 📦 Exports a container's filesystem as a tar archive. |
| `docker import <filename>.tar` | 📥 Imports the contents from a tarball to create a filesystem image. |
| `docker save -o <filename>.tar <image_name>` | 💾 Saves an image to a tar archive. |
| `docker load -i <filename>.tar` | 📂 Loads an image from a tar archive. |
| `docker system prune` | 🧹 Removes all stopped containers, unused networks, and dangling images. |
| `docker volume prune` | 🧹 Removes all unused volumes. |
| `docker history <image_name>` | 🕒 Displays the history of an image. |
| `docker exec -it <container_id> <command>` | 🔧 Runs a command in a running container. |

---

Feel free to use this cheat-sheet as a quick reference guide for all your Docker-related tasks! 📘✨
