# School Bell Studio

A dark, English-language school bell web app.

## Features
- Hold-to-play soundboard: press and hold `HOLD TO TEST`; release to stop.
- Original built-in WAV sound effects included in `assets/`.
- Import your own audio files during a session.
- Build and save custom bells using one or more sounds at once.
- Schedule saved bells for selected days and times.
- Dark responsive interface.
- PWA files (`manifest.json` and `sw.js`) for installable use from a secure hosted URL.

## Run locally
Open `index.html` in a browser. Built-in WAV sounds work locally. For install/PWA support, host it on HTTPS (for example, GitHub Pages).

## Install on Windows after publishing
1. Publish the contents of this folder to a GitHub repository.
2. In the repository, open Settings -> Pages and select Deploy from a branch, `main`, `/ (root)`.
3. Open the published HTTPS URL in Microsoft Edge on Windows.
4. Choose `...` -> Apps -> Install this site as an app (wording can vary).
5. The app will open in its own window and can be pinned to Start or taskbar.

## Notes
- Keep the app open for scheduled bells. Browser restrictions and computer sleep can prevent a web page from firing a schedule on time.
- Saved bell definitions and schedules are stored in local browser storage on that device.
- Imported files are temporary for the current session; choose them again after reopening.
- This is not a certified emergency warning system.
- To use external speakers, connect the computer's audio output to a compatible amplifier's LINE/AUX input. Never connect a computer directly to speaker wires.
