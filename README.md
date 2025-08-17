# Argon40 Offline Installer (Mirror Repository)

This repository contains a **local mirror of all scripts, services, and assets** required by the official Argon40 setup script (`argon1.sh`).  
The original installation script from Argon40 downloads dozens of files dynamically from `https://download.argon40.com`.  
This approach works but has two major drawbacks:

1. **Reproducibility**  
   The installation always pulls the "latest" versions from Argon40 servers.  
   If Argon40 updates, removes, or reorganizes files, your setup may break or behave differently than expected.

2. **Stability**  
   If the Argon40 website or download server is offline, the installer will fail.  
   Having a local copy in a Git repository ensures that all required components are always available.

3. **Security & Control**  
   Blindly executing remote scripts (`curl ... | bash`) is not a safe practice.  
   By keeping all files in your own repository, you can **review, version, and audit** every script that runs on your devices.

## 📜 License

All original Argon40 scripts and assets belong to **Argon40 Technologies**.  
This repository is only a **mirror for educational and operational purposes** to ensure offline reproducibility.  

If you are the copyright owner and have concerns, please open an issue.

