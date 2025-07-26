# 🐋🛳️ zero-to-ubuntu-docker

Welcome to the ultimate minimal setup — running a fully-functional Ubuntu container using Docker, directly from a Windows machine.

This project is perfect for DevOps engineers, system tinkerers, who want to understand how containers abstract and isolate OS-level environments.

No fluff. No bloat. Just Ubuntu, raw and ready.

> ⚙️ From `hello-world` to full-blown Ubuntu container with `nano`, in under 1 minute.

---

## What is This?

This repository documents the steps and environment used to launch and interact with an Ubuntu container using Docker Desktop on **Windows 10**.
Ideal for sandbox testing, fast prototyping, or container bootstrapping.

✔️ Start from zero  
✔️ Pull official Ubuntu image  
✔️ Run it interactively  
✔️ Update + install tools inside container (e.g. `nano`)  
✔️ All in a secure, disposable environment  

---

## Why This Matters?

- Start from scratch
- Pull the official Ubuntu image
- Run it interactively
-  Explore a disposable, secure Linux environment

---

## Why This Matters

- 🗒️ Sandboxed Linux playground — safely test bash scripts, configs, or tools

- 🦕 Clean every launch — no system clutter, no long-term impact

- 🏃🏻‍♂️ Fast onboarding — perfect for students, bootcamps, or tech demos

- 🪟 Runs natively on Windows — via Docker Desktop with WSL2 backend

---

## Prerequisites

- Windows 10 or 11
- Docker Desktop installed & running
- Internet connection to pull Ubuntu image

---

## Steps Taken

# ✅  Check Docker installation
```
docker info
```

# ⚗️ Test Docker
```
docker run hello-world
```

# 🦆 Launch Ubuntu interactively
```
docker run -it ubuntu bash
```

# 🗄️ Inside the container:
```
apt update
apt install nano
```

# 🔧 Environment Details

```
OS: Windows 10 (Build 26100.4652)

Docker Version: 27.3.1

Ubuntu Image: ubuntu:latest (Noble)

Kernel: WSL2-backed Linux 5.15.x

Container runtime: runc

Memory: 7.6 GiB

CPUs: 16
```

--- 

#  License

This project is licensed under the MIT License — feel free to fork, adapt, or remix with credit.
See LICENSE file for more.

--- 

# Author

🍃 Rico Aprilla Nanda
