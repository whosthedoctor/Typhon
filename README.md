# Typhon

Windows auto-typer with human-like randomized keypress timing. Give it a
string and it types it — with natural variation in press duration and gaps
instead of robotic perfect intervals.

## What's here

- `Typhoon Code` (suggested rename: `typhon.cpp`) — the typer
- `Whirl.jpeg` — the mascot, presumably

## Build (Windows)

```
g++ "Typhoon Code" -o typhon.exe
```

(or open it in Visual Studio). Edit the string in `main()` to set what gets typed.

## Note

Windows-only (`windows.h`, `keybd_event`). Built for automating your own typing
tasks — don't be weird with it.
