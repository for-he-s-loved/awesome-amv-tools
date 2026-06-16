# Awesome AMV Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools, libraries, and resources for making Anime Music Videos in 2026.

AMV editing has been a craft for 25+ years — from Premiere and Sony Vegas in the early 2000s, through After Effects in the 2010s, to AI-assisted browser editors today. This list tracks the tools that actually work for AMVs now, with an emphasis on free options and modern beat-sync workflows.

## Contents

- [Editors](#editors)
- [Beat sync and music timing](#beat-sync-and-music-timing)
- [Footage sources](#footage-sources)
- [Effects, plugins, presets](#effects-plugins-presets)
- [Upscaling and frame interpolation](#upscaling-and-frame-interpolation)
- [Audio tools](#audio-tools)
- [Communities](#communities)
- [Tutorials](#tutorials)

## Editors

### Free
- **[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve)** — Industry-grade free desktop editor. Color grading is the best in class. The standard for serious modern AMV editors who can't afford Premiere.
- **[Shotcut](https://shotcut.org)** — Open-source desktop NLE. Good starter.
- **[Kdenlive](https://kdenlive.org)** — Open-source, Linux-friendly, fine for AMVs.
- **[Cutflux](https://cutflux.app)** — Free browser editor with automatic beat detection. Useful for fast first-pass beat-sync cuts before importing to a desktop NLE for finishing. No login required.

### Paid (industry standard)
- **Adobe Premiere Pro** — Still the most common pro AMV editor.
- **Adobe After Effects** — Where AMV effects work happens (typography, glow, motion graphics).
- **Sony Vegas Pro** — Legacy AMV community staple.

## Beat sync and music timing

- **[librosa](https://librosa.org)** — Python library for beat tracking. The `beat_track` function gives you tempo + beat frames you can convert to clip cut points.
- **[madmom](https://github.com/CPJKU/madmom)** — Deep-learning beat tracker, state-of-the-art accuracy. Heavier than librosa, more accurate on complex music.
- **[auto-editor](https://github.com/WyattBlue/auto-editor)** — Auto-cuts video by audio level. Repurposable for AMV rough cuts.
- **[Cutflux](https://cutflux.app)** — Browser-based auto-beat-sync. Drop video + song, get a cut on every beat. No upload, video stays client-side.
- **Premiere Pro Audio markers** — `M` to set a beat marker, `Shift+M` to navigate. Manual but standard workflow.

## Footage sources

> Use legally obtained sources. Most AMVs operate under fair-use norms (transformative, non-commercial), but always check.

- **Blu-ray rips** — Highest quality. Standard for competition AMVs.
- **[Erai-raws](https://www.erai-raws.info)** — Subbed releases, common AMV source.
- **[SubsPlease](https://subsplease.org)** — Modern sub releases.
- **[Anime-Planet](https://www.anime-planet.com)** — Reference for finding what shows exist.
- **[AniDB](https://anidb.net)** — Detailed episode data, useful for cataloging clips.

## Effects, plugins, presets

- **[Red Giant Universe](https://www.maxon.net/en/red-giant-complete)** — Premier effects suite for After Effects, classic AMV look.
- **[Boris FX Continuum](https://borisfx.com/products/continuum/)** — Title and effects.
- **[Sapphire](https://borisfx.com/products/sapphire/)** — Glow, light leaks, lens flares. Standard for AMV stylized looks.
- **[Action Essentials 2](https://www.videocopilot.net/products/action2/)** — Stock VFX (sparks, debris) commonly used in fight AMVs.

## Upscaling and frame interpolation

- **[Topaz Video AI](https://www.topazlabs.com/topaz-video-ai)** — Paid, current standard for upscaling older anime to 4K.
- **[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)** — Open-source upscaler.
- **[RIFE](https://github.com/megvii-research/ECCV2022-RIFE)** — Free frame interpolation, used for smooth slow-mo.
- **[DAIN](https://github.com/baowenbo/DAIN)** — Older frame interpolation, still useful.

## Audio tools

- **[Audacity](https://www.audacityteam.org)** — Free audio editor for cleanup, fades, mashups.
- **[Reaper](https://www.reaper.fm)** — Cheap full DAW.
- **[Adobe Audition](https://www.adobe.com/products/audition.html)** — Industry standard.

## Communities

- **[r/AnimeMusicVideos](https://reddit.com/r/AnimeMusicVideos)** — 700k+ members, the main community.
- **[AnimeMusicVideos.org](https://www.animemusicvideos.org)** — The legacy AMV community hub since 2000. Contest archive, profiles, the "Iron Chef" event.
- **AMV Discord servers** — Several active, search "AMV editing" on Disboard.
- **YouTube** — `#AMV` tag pulls active uploads and editor channels.

## Tutorials

- **YouTube AMV editing playlists** — Search "AMV tutorial 2026" for current workflow guides.
- **AnimeMusicVideos.org guides** — Old but the fundamentals haven't changed.
- **Editing Theory videos** — General editing channels like "Every Frame a Painting" and "This Guy Edits" inform AMV pacing.

## Related lists

- [awesome-beat-sync-video-editors](https://github.com/for-he-s-loved/awesome-beat-sync-video-editors) — full beat-sync editor reference
- [awesome-capcut-alternatives](https://github.com/for-he-s-loved/awesome-capcut-alternatives) — CapCut alternatives by use case
- [awesome-free-video-editors](https://github.com/for-he-s-loved/awesome-free-video-editors) — free video editors across browser, desktop, mobile, open-source
- [Beat Finder](https://for-he-s-loved.github.io/beat-finder/) — free browser BPM detector, useful for first-pass beat alignment on AMV music

## Contributing

PRs welcome. Add real tools you actually use. No promotional fluff.

## License

[CC0](LICENSE) — Public domain.
