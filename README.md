# Dynamic Island Media Player for Windows

![Dynamic Island Preview](https://raw.githubusercontent.com/BOG090909/dynamic-island-media-player/main/assets/preview.png)

A focused, customizable Dynamic Island overlay for Windows that becomes an interactive media player when music or video is playing. This standalone mod is based on the original [Dynamic Island for Windows](https://github.com/devcode90/Dynamic-Island-for-Windows), but removes unrelated dashboard modules and concentrates on media playback.

## Features

### Media playback

- Reads the current media session through Windows System Media Transport Controls.
- Displays track title, artist, album, source-app badge, album artwork, and playback state.
- Provides play/pause, previous-track, and next-track controls.
- Supports progress display and scrubbing.
- Lets you choose the track-change animation: **Fade** (crossfade) or **Slide** (horizontal slide).
- Keeps track-change transitions independent from the option that disables the island's hover and movement animations.
- Refreshes album artwork when the track, artist, or album identity changes, and scales large artwork for display.

### Interaction and window behavior

- Expands on hover, with configurable behavior.
- Supports click-through mode; hold **Ctrl** to interact with the island.
- Provides configurable hotkeys for show/hide, next track, previous track, and play/pause.
- Supports per-application saved positions, so the island can appear at different locations for different apps.
- Includes always-on-top, above-games, taskbar-layering, and fullscreen options.
- Provides a right-click context menu for quick access to settings and playback-related options.

### Appearance and customization

- Multiple island shapes, including the default pill, Windows 11-style rounded box, and top-edge notch.
- Adjustable size, text scale, font, target monitor, and screen offsets.
- Theme presets and separate background, primary-text, and secondary-text colors.
- Accent color modes: automatic from album artwork, system accent, or custom color.
- User-managed color-morphing palette with add/remove/reset controls and adjustable speed.
- Configurable button style, shadow, and window opacity.
- Ukrainian, Russian, and English interface languages.
- Optional media-source filtering.

## Context menu and settings

Right-click the island to open its context menu. The menu includes window behavior, idle/paused visibility, opacity, color settings, color morphing, track-transition style, button style, language, animation and shadow options, hotkeys, media-source filtering, and per-app position controls.

The **Disable player animations** option affects the island's hover and movement animations. It does not disable Fade or Slide transitions between tracks.

## Credits

- **Himanshu (devcode90):** Original Dynamic Island for Windows framework, rendering foundation, and core interface design.
- **BOG090909:** Standalone media-player adaptation, per-app positioning, customization features, localization, playback integration, and performance improvements.
