# linux-sysadmin-lab
Practical, reproducible labs for Linux SysAdmin work using Ubuntu Server and Docker Compose.

This repository is built to demonstrate:
- clean project structure
- reproducible services (Docker Compose + scripts)
- clear documentation and realistic Git workflow

## Repository structure
- docs/ : standards and lab notes
- projects/ : independent reproducible projects

## How to run a project (Ubuntu Server)
cd projects/00-template
cp .env.example .env
chmod +x scripts/*.sh
./scripts/up.sh

Stop and clean
./scripts/down.sh

## Documentation
- docs/00-about-this-repo.md
- docs/10-lab-setup.md
- docs/20-workflow.md

## Notes
Projects are designed to run on Linux.
On Windows, edit and commit normally, then run on Ubuntu.