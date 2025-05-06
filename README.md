# macOS Python Package Management

This repository is used to centrally manage Python packages across macOS devices managed via Kandji.

## Usage

1. Add or update Python package names and versions in `requirements.txt`.
2. The Kandji Custom Script on each device will pull this file and update packages accordingly.
3. Packages are installed system-wide using pip with `--no-user`.
