# NexoBreak downloads

Latest testing version: **0.0.3 Beta**. Windows, Rhino 8.34+ and .NET 8 required.

[Download this version](https://github.com/Hossein-Nazari-Dev/NexoNest---Products/releases/tag/nexobreak-v0.0.3)

- Drag the `.yak` package into Rhino, then restart Rhino and run `NexoBreak`.
- For a manual install, extract the ZIP to a permanent folder and install `NexoBreak.rhp` through Options > Plug-ins > Install. The RHP also works alone.
- Rename the versioned standalone RHP download to `NexoBreak.rhp` before installing it; keep that filename for in-app manual updates.
- Use one installation method and remove duplicate older copies.
- Verify downloads using the release's SHA256SUMS.txt.

Inside NexoBreak: **Account > Check for updates > Download update** (called Install when Rhino closes in 0.0.2). A current version offers only Close. No account is required. The updater verifies size and SHA-256, waits for all Rhino windows to close, then uses Rhino Yak for package installs or replaces the manual RHP atomically with a backup. Save your work, close Rhino normally and wait before reopening it. Check the installed version afterwards; failed attempts offer a retry hint and retain details in the local result.json.

Work data stays local. Update requests go anonymously to GitHub; no task, model or Game Club identity is sent. Staged files, results and previous plug-in backups are stored in `%LOCALAPPDATA%\NexoBreak\updates`. A manual installation also keeps a `.rhp.bak` beside the previous RHP. Keep backups until the new version works; remove them manually when no longer needed.

This folder contains the product-specific update feed. Release tags use `nexobreak-v<version>`; releases for other products do not change this feed. Product source is maintained separately. This is a beta with automated checks; native Rhino UI/update acceptance is still pending.

Support: nexonest.contact@gmail.com
