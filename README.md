# Carry releases

Installers for the Carry desktop app, published by the build workflow of our private repository. Each release carries:

- `Carry_<version>_x64-setup.exe` and `Carry_<version>_x64_en-US.msi` for Windows
- `Carry_<version>_amd64.AppImage` and `Carry_<version>_amd64.deb` for Linux
- one `SHA256SUMS.txt` covering all four packages

The builds are unsigned for now, so Windows shows its unknown-publisher warning once. Verify a download against `SHA256SUMS.txt` before installing. Download Carry from https://trycarry.ai.
