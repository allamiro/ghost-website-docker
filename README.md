# Install Docker and Docker Compose 



## A. Linux

### 1. Prerequisites (all distros)

- A 64-bit Linux distribution (Ubuntu, Debian, RHEL, CentOS, Rocky, Alma, etc.).
- `sudo` access.
- Remove any old/conflicting Docker packages:

```bash
sudo apt remove docker docker-engine docker.io containerd runc 2>/dev/null || true
sudo dnf remove docker docker-client docker-client-latest docker-common docker-latest docker-latest-logrotate docker-logrotate docker-engine podman runc 2>/dev/null || true


## B. Windows (Docker Desktop)

The simplest way on Windows is Docker Desktop, which includes Docker Engine, Docker CLI, and Docker Compose in one installer. 
Docker Documentation

1. Requirements

* Windows 10/11 64-bit (Pro/Enterprise/Education recommended).

Hardware virtualization enabled in BIOS.

WSL2 or Hyper-V available (Docker Desktop can configure this). 
Docker Documentation

2. Install Docker Desktop

Download Docker Desktop for Windows from the official site or the Microsoft Store. 
Docker Documentation

https://docs.docker.com/desktop/setup/install/windows-install/

Run the installer:

Keep “Use WSL 2 instead of Hyper-V” checked (recommended).

Complete the installation and reboot if prompted.

Launch Docker Desktop and wait until it shows “Docker Desktop is running”.

3. Verify Docker and Docker Compose

Open PowerShell or Windows Terminal:
