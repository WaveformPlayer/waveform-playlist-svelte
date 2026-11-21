> [!IMPORTANT]
> **Replaced by [`@arraypress/waveform-svelte`](https://www.npmjs.com/package/@arraypress/waveform-svelte) 2.0.** Import from `@arraypress/waveform-svelte/playlist` instead — one package per framework, with a sub-path per component ([repo](https://github.com/WaveformPlayer/svelte), [migration guide](https://docs.waveformplayer.com/getting-started/migrating-from-1x/)).
> This repository is archived and the npm package is deprecated; its 1.x releases keep working.

<div align="center">

# Waveform Playlist for Svelte

**Svelte 5 component wrapper for `@arraypress/waveform-playlist`.**
Declarative `tracks`, typed props for every option, and an exported imperative navigation API.

[![npm version](https://img.shields.io/npm/v/@arraypress/waveform-playlist-svelte?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-playlist-svelte)
[![license](https://img.shields.io/npm/l/@arraypress/waveform-playlist-svelte?style=flat-square&labelColor=09090b&color=3f3f46)](https://github.com/arraypress)

**[Documentation](https://docs.waveformplayer.com/)** · [npm](https://www.npmjs.com/package/@arraypress/waveform-playlist-svelte)

</div>

---

## Install

```bash
npm install @arraypress/waveform-playlist-svelte @arraypress/waveform-playlist @arraypress/waveform-player svelte
```

```svelte
<script lang="ts">
  import { WaveformPlaylist } from '@arraypress/waveform-playlist-svelte';
</script>

<WaveformPlaylist tracks={[{ url: '/a.mp3', title: 'A', artist: 'Artist' }]} />
```

## Documentation

Every prop, the imperative API, and SSR notes live in the docs.

### -> [docs.waveformplayer.com](https://docs.waveformplayer.com/)

[Svelte guide](https://docs.waveformplayer.com/frameworks/svelte/) — install, props, the imperative API, and SSR notes. All four Svelte wrappers (player / bar / playlist) are on that page.

## License

MIT © [ArrayPress](https://github.com/arraypress)
