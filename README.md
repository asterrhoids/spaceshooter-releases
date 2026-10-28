# spaceshooter — downloads

Playable builds of **spaceshooter**, a small co-op FPS sandbox built in Godot 4.7.
The source lives in a private repository; only the builds are published here.

## Download

Grab the newest zip from the [Releases](../../releases/latest) page:

```
spaceshooter-<version>-windows.zip
```

Unzip it anywhere and run `spaceshooter.exe`. Nothing else to install — the engine and
the Steam libraries are inside the archive.

## Playing co-op

1. Start the game and press **Host co-op**.
2. Give a friend the lobby id (or invite them from the Steam overlay).
3. They press **Join by id**, paste it, and wait until the panel says *connected*.
4. The host presses **Start** once everyone shows as connected.

Needs the Steam client running, and both players on each other's Steam friends list.

## Known caveats

- **Unsigned build.** Windows SmartScreen says "unknown publisher": choose
  *More info → Run anyway*. There is no code-signing certificate.
- **AppID 480** (Valve's *Spacewar* test app), so Steam shows the game as **Spacewar**
  and friends need that app in their library.
- Co-op is friends-only, up to 4 players. No matchmaking, no public servers.
- Early build: no audio yet, placeholder art, enemies are capsules.

## Bugs

Tell whoever gave you this link. Issue tracking lives with the private source.
