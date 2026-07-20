<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0f12,50:3dd6c6,100:0d0f12&height=160&section=header&text=GLYPH&fontSize=68&fontColor=ffffff&fontAlignY=38&desc=Offline-first%20search%20and%20metadata%20intelligence.&descSize=14&descAlignY=65&descColor=ffffff&animation=fadeIn" width="100%"/>
<br/>

<a href="https://flokestudio.github.io/Floke/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=2800&pause=900&color=3DD6C6&center=true&vCenter=true&repeat=true&width=540&lines=Search+your+vault.+Understand+your+notes.;Offline-first.+No+cloud.+No+accounts.;Glyph+2.8+%C2%B7+Floke+Studio.;Built+by+krwg" alt="typing"/>
</a>

<br/><br/>

<a href="https://flokestudio.github.io/Floke/">
  <img src="https://img.shields.io/badge/Website-flokestudio.github.io%2FFloke-3dd6c6?style=for-the-badge&logo=githubpages&logoColor=white&labelColor=0d0f12" alt="Website"/>
</a>
<a href="https://github.com/FlokeStudio">
  <img src="https://img.shields.io/badge/GitHub-FlokeStudio-ffffff?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0f12" alt="GitHub"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Glyph-2.8-3dd6c6?style=flat-square&labelColor=0d0f12" alt="Glyph 2.8"/>
<img src="https://img.shields.io/badge/Obsidian-plugins-6eb5ff?style=flat-square&labelColor=0d0f12&logo=obsidian&logoColor=white" alt="Obsidian"/>
<img src="https://img.shields.io/badge/Offline--first-3dd6c6?style=flat-square&labelColor=0d0f12" alt="offline-first"/>
<img src="https://img.shields.io/badge/GPL--3.0-4a7c59?style=flat-square&labelColor=0d0f12" alt="GPL-3.0"/>

</div>

<br/>

<h2 align="center">〔 Glyph 2.8 family 〕</h2>

<br/>

<table>
<tr>
<td width="50%">

**glyph-s** · Core search engine

Profile-based ranking, extended query grammar, vitest + benchmark, optional ONNX embeddings hook, public `.d.ts`.

<p>
  <a href="https://flokestudio.github.io/glyph-s/"><img src="https://img.shields.io/badge/Site-3dd6c6?style=flat-square&labelColor=0d0f12" alt="Site"/></a>
  <a href="https://github.com/FlokeStudio/glyph-s"><img src="https://img.shields.io/badge/GitHub-ffffff?style=flat-square&labelColor=0d0f12&logo=github" alt="GitHub"/></a>
</p>

</td>
<td width="50%">

**glyph-sO** · Obsidian search

Persistent vault index, editor highlight on jump, folder groups, hover preview, pinned queries.

<p>
  <a href="https://flokestudio.github.io/glyph-sO/"><img src="https://img.shields.io/badge/Site-3dd6c6?style=flat-square&labelColor=0d0f12" alt="Site"/></a>
  <a href="https://github.com/FlokeStudio/glyph-sO"><img src="https://img.shields.io/badge/GitHub-ffffff?style=flat-square&labelColor=0d0f12&logo=github" alt="GitHub"/></a>
</p>

</td>
</tr>
<tr>
<td width="50%">

**glyph-mi** · Metadata intelligence core

`@floke/glyph-mi` npm package, KNN IPC module, ONNX train/export script, Cultiva foundation scaffold.

<p>
  <a href="https://krwg.github.io/glyph-mi/"><img src="https://img.shields.io/badge/Site-6eb5ff?style=flat-square&labelColor=0d0f12" alt="Site"/></a>
  <a href="https://github.com/krwg/glyph-mi"><img src="https://img.shields.io/badge/GitHub-ffffff?style=flat-square&labelColor=0d0f12&logo=github" alt="GitHub"/></a>
</p>

</td>
<td width="50%">

**glyph-miO** · Obsidian MI

Right sidebar `ItemView`, YAML frontmatter tags, vault batch analysis, vendored glyph-mi notes module.

<p>
  <a href="https://flokestudio.github.io/glyph-miO/"><img src="https://img.shields.io/badge/Site-6eb5ff?style=flat-square&labelColor=0d0f12" alt="Site"/></a>
  <a href="https://github.com/FlokeStudio/glyph-miO"><img src="https://img.shields.io/badge/GitHub-ffffff?style=flat-square&labelColor=0d0f12&logo=github" alt="GitHub"/></a>
</p>

</td>
</tr>
</table>

<br/>

<h2 align="center">〔 What’s new in 2.8 〕</h2>

<br/>

<div align="center">

| Area | Highlights |
|:---|:---|
| **glyph-s** | 33 vitest tests · benchmark · `checkJs` · embeddings hook + `.d.ts` · optional hash/ONNX semantic boost |
| **glyph-sO** | Editor highlight · folder grouping · hover preview · search stats · **pinned queries** · vendor 2.8.0 |
| **glyph-miO** | Sidebar panel · frontmatter tags · batch vault summary · **glyph-mi notes vendor** |
| **glyph-mi** | npm publish prep · KNN IPC · ONNX train script · Cultiva foundation module |
| **Cultiva** | Vendored glyph-s **2.8.0** · compact Glyph/Floke banner · main-process KNN IPC scaffold |

</div>

<br/>

<h2 align="center">〔 Philosophy 〕</h2>

<br/>

<div align="center">

| | |
|:---|:---|
| `offline-first` | Works without internet by design |
| `no accounts` | Your vault stays on your machine |
| `open source` | GPL-3.0 on GitHub |
| `modular` | Engines for devs, plugins for Obsidian, adapters for apps |

</div>

<br/>

<h2 align="center">〔 Structure 〕</h2>

<br/>

<div align="center">

```
FlokeStudio/
├── glyph-s      — search engine core
├── glyph-sO     — Obsidian search plugin
├── glyph-miO    — Obsidian metadata plugin
└── Floke        — studio landing

krwg/
├── glyph-mi     — metadata intelligence core
└── cultiva      — habit tracker (glyph-s consumer)
```

</div>

<br/>

---

<div align="center">

**Floke Studio** · Independent software · [flokestudio.github.io/Floke](https://flokestudio.github.io/Floke/)

<br/>

Built by **[krwg](https://github.com/krwg)**

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0f12,50:3dd6c6,100:0d0f12&height=100&section=footer" width="100%"/>

</div>
