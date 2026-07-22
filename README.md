# MitchIvin XP

An interactive **Windows XP desktop** in the browser. Boot the machine, log in, and explore design and UI work by [Mitch Ivin](https://mitchivin.com/).

Live at **[mitchivin.com](https://mitchivin.com/)**.

Vanilla HTML, CSS, and ES modules. Window chrome uses self-hosted [XP.css](https://botoxparty.github.io/XP.css/). No framework, no runtime dependencies.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6c141ad7-3cd1-4f93-85bd-c91b888a2252" alt="MitchIvin XP desktop apps including Mi Boy Color and MiPod Classic" width="460" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/a441f996-a3f8-4bb5-b6e2-2a3b6279de18" alt="MitchIvin XP Windows XP portfolio desktop with Start menu and taskbar" width="460" />
</p>

## About

MitchIvin XP is a full Luna-era shell: boot screen, login, Bliss wallpaper, Start menu, taskbar, system tray, XP context menus, and a working window manager. Portfolio pages live as real programs alongside interactive apps: a Game Boy Color emulator, a click-wheel music player, Live Messenger with MitchBot, and more.

Desktop includes drag, resize, Aero snap with linked split-screen resizing, and the full system tray. Mobile view provides a portrait-first XP desktop with freeform icons, long-press menus, scroll-stack navigation, and automatic top-window focusing. CRT scanlines stay on by default and can be toggled from the tray or desktop context menu.

## Features

**Shell**
- Boot sequence, Luna login, and welcome balloon into a full desktop
- Start menu, taskbar, system tray, XP tooltips, and context menus
- Window manager: drag, resize, minimize, maximize, restore, focus stacking, menu bars, toolbars, address bars, and status bars
- Desktop Aero snap (left / right / maximize) with **linked split-screen dual-window resizing** when side-by-side edges touch
- Chronological taskbar button ordering matching the exact sequence programs are opened
- CRT effect (default on), fullscreen toggle, and site-wide master volume flyout (-16 LUFS normalized audio)
- Quick Start and Help layouts that snap portfolio windows into place

**Desktop & mobile**
- Freeform snap-grid icons with drag, lock, arrange, copy / paste, desktop shortcuts, and Reset Desktop on desktop and phone
- Desktop: full right-click context menus, tray overflow, taskband scrolling
- Mobile: long-press menus, scroll-stack of open programs, distance-aware touch zoom protection, top-window auto-focusing, portrait only (landscape blocked)
- Session-friendly refresh: desktop icon grid, shortcuts, clipboard, and Messenger mute survive a page reload while staying logged in

**Programs (15)**
- Portfolio: About Me, My Projects, Resume, Contact Me, Image Viewer
- Chromeless widgets: **MiPod Classic** (click-wheel player + Now Playing) and **Mi Boy Color** (Game Boy Color emulator) with Big Mode checkbox toggles, Controls mode, and full-face Drag
- **Live Messenger**: contacts list, MitchBot chat, tray toasts / nudges, mute notifications, soft-close to tray
- Media & tools: Media Player, Paint, DoodleDev, Notepad, Command Prompt, World of Warcraft login

## Stack

- Vanilla HTML / CSS / ES modules
- [XP.css](https://botoxparty.github.io/XP.css/) (self-hosted with fonts) for XP UI chrome
- Custom window manager, Start menu, taskbar, boot sequence, and Web Audio SFX hub
- [JS Paint](https://jspaint.app/) (MIT) for Paint
- [GameBoy-Online](https://github.com/taisel/GameBoy-Online) for Mi Boy Color emulator core
- [WLMOnline](https://codepen.io/androidwg/full/XWXYZGb) for Live Messenger UI layout
- [WoWLoginScreens](https://github.com/Xiexe/WoWLoginScreens) for World of Warcraft login UI
- [YouTube IFrame Player API](https://developers.google.com/youtube/iframe_api_reference) for Media Player and video showcases

## Related

- [Mi Boy Color](https://github.com/mitchivin/miboy): Game Boy Color emulator in the browser
- [MiPod](https://github.com/mitchivin/mipod): click-wheel music player

## Credits

Built by **[Mitch Ivin](https://mitchivin.com/)**.

- [XP.css](https://botoxparty.github.io/XP.css/) by botoxparty.
- [JS Paint](https://jspaint.app/) by Isaiah Odhner.
- [WLMOnline](https://codepen.io/annarodrigues/) by Anna Rodrigues.
- [WoWLoginScreens](https://github.com/Xiexe/WoWLoginScreens) by Xiexe.
- [GameBoy-Online](https://github.com/taisel/GameBoy-Online) by Grant Galitz.
- World of Warcraft Vanilla imagery and audio belong to Blizzard Entertainment.

Game Boy and Game Boy Color trademarks belong to Nintendo. Windows XP imagery, sounds, and trademarks belong to Microsoft Corporation. This is a portfolio piece and parody, not an official product.

## License

Source stays private. The live site is the product.
