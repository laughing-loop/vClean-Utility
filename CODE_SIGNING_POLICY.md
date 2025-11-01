# Code Signing Policy

## Certificate Provider

Free code signing provided by [SignPath.io](https://signpath.io), certificate by [SignPath Foundation](https://signpath.foundation).

## Team Roles

### Committers and Reviewers
- **LaughingLoop** ([@laughing-loop](https://github.com/laughing-loop)) - Project Owner and Maintainer

### Approvers
- **LaughingLoop** ([@laughing-loop](https://github.com/laughing-loop)) - Release Approver

All team members use multi-factor authentication for both GitHub and SignPath access.

## Privacy Policy

This program will not transfer any information to other networked systems unless specifically requested by the user or the person installing or operating it.

### Data Collection
V-Clean Enterprise does **not** collect, store, or transmit any user data. All operations are performed locally on the user's system.

### Network Activity
The application only makes network requests for:
- **Update checking**: Connects to GitHub API to check for new releases (user-initiated via Help menu)
- No analytics, telemetry, or tracking of any kind

### Third-Party Components
V-Clean Enterprise uses the following components:
- **Windows Forms**: Built-in Windows UI framework (no external data transmission)
- **PowerShell**: Built-in Windows scripting environment (no external data transmission)
- **GitHub API**: Used only for update checking (public API, no authentication required)

## Build and Signing Process

### Source Code
All signed binaries are built from source code in this public GitHub repository: https://github.com/laughing-loop/vClean-Utility

### Build Process
1. Source code is compiled using PS2EXE (PowerShell to EXE converter)
2. MSI installer is built using WiX Toolset
3. All builds are reproducible and verifiable

### Signing Approval
Each release requires manual approval by a designated approver before signing.

## Security Best Practices

- All team members use multi-factor authentication
- All code changes are reviewed before merging
- Release branches are protected
- Binary artifacts are built from verified source code

## Reporting Issues

If you believe that software signed with our SignPath Foundation certificate violates the SignPath Foundation Code of Conduct, please report it to:
- **SignPath Foundation**: support@signpath.io
- **Project Maintainer**: Via GitHub Issues at https://github.com/laughing-loop/vClean-Utility/issues

## Compliance

This project complies with the [SignPath Foundation Code of Conduct](https://about.signpath.io/code-signing/foundation-code-conduct) for Open Source projects.

---

**Last Updated**: 2025-11-01  
**Project**: V-Clean Enterprise v3.0.0  
**Repository**: https://github.com/laughing-loop/vClean-Utility
