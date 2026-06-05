<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/codesuab/codesuab/refs/heads/main/assets/deploysync.ico" width="100px" alt="DeploySync" />
  <h1>DeploySync</h1>
  <p><b>Smart FTP/SFTP deployment manager for cPanel hosting</b></p>

  <img alt="Version" src="https://img.shields.io/badge/version-v1.0.0-blue.svg" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green.svg" />
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg" />
</div>
<br/>
<div align="center">
  <a href="https://github.com/codesuab/deploysync/issues">Report Bug</a> ·
  <a href="https://github.com/codesuab/deploysync/issues">Request Feature</a> ·
  <a href="https://github.com/codesuab/deploysync/discussions">Discussions</a> ·
  <a href="https://github.com/codesuab">Developer</a>
</div>
<br/>

# Your Data Never Leaves Your Environment

> All project data is stored locally on your device. No cloud storage, no analytics, no telemetry.

> DeploySync combines smart file deployment, Git-aware sync, remote file management, database backup & restore, and real-time automation into a single desktop application.

## Features

### Incremental Sync

Uploads only new and modified files using MD5 hash comparison.

### Git-Aware Deployments

Deploy based on uncommitted changes or compare against the last commit.

### Auto-Sync on Save

Watches your project folder and deploys changes automatically when you save.

### FTP & SFTP

Works with both protocols. Credentials are stored encrypted locally.

### Multi-Project Workspace

Manage all your sites in one place with independent history and configs.

### Remote File Explorer

Browse, navigate, and inspect files on your server from the app.

### Deployment History

See every deployment — what was uploaded, when, and the result.

### Real-Time Logs

Live progress feed showing exactly which file is being uploaded.

### Import / Export Config

Share project setups as `.deploysync` files across machines.

### PIN Lock Screen

Optional security with auto-lock on inactivity, minimize, or close.

## Quick Start

1. Download and install the latest release
2. Create a project — enter your server details and pick a local folder
3. Click **Deploy** — only changed files are uploaded
4. Enable **Auto-Sync** to deploy automatically on save

## Tips

- **cPanel users**: If connection fails, try a relative path like `/` or just your domain folder instead of a full absolute path — cPanel often restricts FTP users to their home folder.
- **Ignore patterns**: By default, `node_modules`, `vendor`, `.git`, `.env`, and `*.sql` are skipped. Add custom patterns in project settings.
- **Git vs Scan mode**: Git mode is faster for Git repos. Scan mode hashes every file and works for any project.
- **Failed uploads**: Check the Logs page. The queue retries failed files up to 3 times — use **Retry Failed** to re-attempt them.

## Security

- Local encrypted credential storage
- No external tracking, analytics, or telemetry
- Only outbound connections to your own FTP/SFTP servers
- Optional PIN lock with configurable timeout
- All data is stored locally on your device
- No project files, credentials, databases, or deployment history are sent to external servers
- DeploySync does not collect or store your data

## License

MIT License
