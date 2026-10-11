# Tube Pocket

A YouTube player for Windows built for handheld gaming PCs. It gives you a floating Picture-in-Picture window you can drive with your fingers, a mouse or a gamepad, and it filters ads and sponsor segments out of the video.

It was made for the MSI Claw 8 AI+, and it works on any Windows 10 or 11 PC.

## What it does

- **Floating Picture-in-Picture window.** The video stays on top of your other windows. Pinch with two fingers to resize it, drag it with one finger or the mouse, tap it to play or pause.
- **Full gamepad control.** Pick a video with the D-pad or the left stick, open it with A, scroll with the right stick. No keyboard or mouse needed.
- **Ad filtering.** The app filters ads before and during the video and hides ad banners on the page.
- **SponsorBlock built in.** Sponsor and self-promotion segments are skipped automatically. Only an anonymous fragment of the video ID is sent to the SponsorBlock service.
- **Ambient light.** A soft glow extends the colours of the video into the page around it. Eight settings: intensity, blur, spread, opacity, colour saturation, brightness, edge thickness and smoothness. It can also be turned off.
- **Light mode for handhelds.** On a handheld, the app turns off the effects that cost frames: translucent windows, background blurs and rounded video corners.
- **Quality capped at your screen.** Video quality never exceeds the screen resolution, so a 1200-line screen does not decode 4K.
- **Downloads.** Save a video as MP4 or its audio as MP3/M4A (uses yt-dlp, installed on demand).

## Download

Open the **Releases** page (right-hand column) and pick one file:

| File | Use |
| --- | --- |
| `Tube-Pocket-Setup-0.1.9.exe` | Installer. Recommended: the app then starts in about a second. |
| `Tube-Pocket-Portable-0.1.9.exe` | No installation, just double-click. Slower to start (5 to 7 seconds). |

The app is not code-signed, so Windows shows a warning on first launch: click **More info**, then **Run anyway**.

## Controls

**Touch (floating window)**

- Pinch with two fingers to resize. Pinch above or below the row of buttons.
- Drag with one finger to move the window.
- Tap to play or pause.

**Gamepad**

| Button | While browsing | While watching |
| --- | --- | --- |
| D-pad / left stick | Move the selection between videos | Select a suggested video |
| A | Open the selected video | Play / pause |
| B | Cancel the selection, or go back | Close the floating window |
| X / Y | | Next / previous video |
| LB / RB | | Back / forward 10 seconds |
| Right stick | Scroll the page | Scroll the page |

## Privacy

- No account is required and the app collects nothing.
- Websites cannot get your location, camera, microphone or notifications: those requests are refused.
- The app presents itself to websites as an ordinary Chrome browser, and local network addresses are not exposed through WebRTC.

## Good to know

- The interface is in French.
- Closing the window with the cross quits the app completely. To keep listening in the background, minimise the window or use the floating window.
- Settings include a diagnostic block (light mode, graphics acceleration, dropped frames) that helps when reporting a performance problem.
- Blocking ads may be against YouTube's terms of service. Use it responsibly.

Personal project, provided as is, with no warranty.
