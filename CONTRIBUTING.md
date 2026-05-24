# Contribution Reference & Guidelines

## Setup

Prerequisites and local setup steps (how to clone, install dependencies, and run the project).

Unreal Engine verision 5.5.4 and download plugins: core OpenXR plugin (standard for modern VR) and device-specific plugins like Meta XR (for Quest) or SteamVR
Meta Link Quest (or other linking software for your headset)
Data link cable to connect VR headset to computer.

## Commands

Commands for running CI, linters, and formatters locally.

There are no linters or formatters as we are working with binary files.
Open the uproject file to open in unreal.

# Contribution Workflow

The expected contribution workflow (branch naming, how to open a PR, and what information to include). Reference your Definition of Done (DoD). Describe code review expectations.

Andy and Sunil are working on streamlining the merging process in perforce.

1. Open Perforce
2. Use stream graph and right click to diff your files.
3. If there are no complicated changes (like new files or deleted files), simply merge which version by revising the merge conflicts and choosing either "keep target" or "keep source"
4. If there are complicated changes:
5. Create backup of the feature branch.
6. Configure Perforce and Unreal workspace such that it is located in that backup, but points to the cloud version of the target branch.
7. Open Unreal and right click the assets that you want to visually diff.
8. Use Unreal's version control system to open visual diff window.
9. Approve/modify changes.
10. Save.
11. Push changes to changelist.
12. Push changelist all together back on Perforce.

## Bug Reporting & Requests

How to report bugs / request changes (where issues live and what details to include).

Post about it in Discord channels, bring it up in Dev Team Weekly meetings, meet with the original dev to inquire about it.

## Contact

Where to ask for help (the team channel or point of contact).

Our team member's emails are listed in the [README](https://github.com/osu-vryu/VRyu/blob/main/README.md) on this repo
