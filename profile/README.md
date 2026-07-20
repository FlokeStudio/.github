<div align="center">

**Floke Studio** · Independent software

Offline-first **Glyph** search and metadata intelligence.

[Studio landing](https://flokestudio.github.io/Floke/) · Built by **[krwg](https://github.com/krwg)**

</div>

---

## Glyph 2.8 family

| Project | Role | Links |
|---------|------|-------|
| **[glyph-s](https://github.com/FlokeStudio/glyph-s)** | Universal search engine — profiles, query grammar, vitest, benchmark | [Site](https://flokestudio.github.io/glyph-s/) · [Roadmap](https://github.com/FlokeStudio/glyph-s/blob/main/ROADMAP.md) |
| **[glyph-sO](https://github.com/FlokeStudio/glyph-sO)** | Obsidian full-text search — persistent index, highlight, folder groups, hover preview | [Site](https://flokestudio.github.io/glyph-sO/) · [Roadmap](https://github.com/FlokeStudio/glyph-sO/blob/main/ROADMAP.md) |
| **[glyph-mi](https://github.com/krwg/glyph-mi)** | Metadata intelligence core — npm package prep, KNN IPC, Cultiva foundation module | [Site](https://krwg.github.io/glyph-mi/) · [Roadmap](https://github.com/krwg/glyph-mi/blob/main/ROADMAP.md) |
| **[glyph-miO](https://github.com/FlokeStudio/glyph-miO)** | Obsidian MI — sidebar panel, frontmatter tags, vault batch analysis | [Site](https://flokestudio.github.io/glyph-miO/) · [Roadmap](https://github.com/FlokeStudio/glyph-miO/blob/main/ROADMAP.md) |
| **[Floke](https://github.com/FlokeStudio/Floke)** | Studio landing and family overview | [Pages](https://flokestudio.github.io/Floke/) |

---

## What's new in 2.8

| Area | Shipped |
|------|---------|
| **glyph-s** | 33 vitest tests · benchmark · tsconfig/checkJs · embeddings stub (ONNX next) |
| **glyph-sO** | Editor highlight on jump · folder grouping · hover preview · stats · vendor 2.8.0 |
| **glyph-miO** | Right sidebar ItemView · YAML frontmatter tags · batch vault summary |
| **glyph-mi** | `@floke/glyph-mi` package prep · KNN IPC module · Cultiva foundation scaffold |
| **Cultiva** | Vendored glyph-s **2.8.0** · Glyph/Floke banner ([krwg/cultiva](https://github.com/krwg/cultiva)) |

---

## Philosophy

| | |
|:---|:---|
| `offline-first` | Works without internet by design |
| `no accounts` | Your data stays on your machine |
| `open source` | GPL-3.0 on GitHub |
| `modular` | Engines for devs, plugins for Obsidian, adapters for apps |

---

## Structure

```
FlokeStudio/
├── glyph-s      — search engine core
├── glyph-sO     — Obsidian search plugin
├── glyph-miO    — Obsidian metadata plugin
└── Floke        — studio landing

krwg/
├── glyph-mi     — metadata intelligence core
└── cultiva      — desktop habit garden (glyph-s consumer)
```

---

**Next on the roadmap:** ONNX embeddings, npm publish for glyph-mi, Electron KNN wiring — see each repo's `ROADMAP.md`.
