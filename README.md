# Pac-Man Linux build

Download `pacman-linux-x86_64.zip` using the file's download button.
This ZIP is the packaged game, not the repository's **Code > Download ZIP**.

Extract the archive on a Linux x86-64 computer, then run:

```bash
cd pacman
chmod +x pacman run-pacman.sh
./run-pacman.sh
```

Keep the executable, `_internal`, `assets`, `config.json`, and README
together. Python does not need to be installed. Extract into a writable
directory for persistent highscores. A graphical Linux desktop and SDL
system libraries are required.

Controls: arrows/WASD to move, P to pause/resume, Enter to confirm.
C enables reviewer cheats: I invincibility, F freeze ghosts, L extra life,
K skip level, +/- player speed, R reset effects.

Built from source commit `71d7583`
on Ubuntu 22.04 with Python 3.10 and PyInstaller.
Lint, strict type checking, twelve behavioral tests, and packaged headless
startup passed. A full graphical playthrough remains unverified.

Source and packaging script:
https://github.com/migdady5/pacman-linux-42

Build evidence:
https://github.com/migdady5/pacman-linux-42/actions/runs/37238984871

For itch.io: create a downloadable game, choose No payments, upload
`pacman-linux-x86_64.zip`, select Linux, and make the page unlisted in
search and browse. Download the archive from the published page and
test it on Linux.
