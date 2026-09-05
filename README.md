<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="profile/assets/Logo.V1.png">
  <source media="(prefers-color-scheme: light)" srcset="profile/assets/Logo.V2.png">
  <img alt="FixByte" src="profile/assets/Logo.V2.png" width="220">
</picture>

**Organization defaults for [@FixbyteStudio](https://github.com/FixbyteStudio)**

[![Profile README](https://img.shields.io/badge/profile-README-00A79A?style=flat-square&labelColor=000D1F&logo=github&logoColor=F8F8F8)](profile/README.md)
[![Brand Style Guide](https://img.shields.io/badge/brand-style_guide_v1.0-007A70?style=flat-square&labelColor=000D1F&logo=readthedocs&logoColor=F8F8F8)](docs/assets/brand/brand-style-guide.jpg)

</div>

---

This is the `.github` repository. It holds the content GitHub renders on the
[organization profile page](https://github.com/FixbyteStudio) and the brand assets those
surfaces depend on.

> [!IMPORTANT]
> The repository must be named `.github` and be **public** for the profile README to render.
> See [Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

## Layout

```
.
├── profile/
│   ├── README.md              → rendered at github.com/FixbyteStudio
│   └── assets/
│       ├── Logo.V1.png        → wordmark, Paper on dark (300×140)
│       ├── Logo.V2.png        → wordmark, Ink on light (300×140)
│       └── Forme.png          → the Forme, the mark alone (512×512)
└── docs/assets/brand/
    ├── brand-logo-lockup.jpg  → logo lockup reference
    └── brand-style-guide.jpg  → full brand style guide, v1.0
```

## Rules of the road

- **Images in `profile/README.md` use absolute `raw.githubusercontent.com` URLs.**
  Relative paths do not resolve reliably once GitHub renders the file on the profile page.
- **Light and dark logos ship as a `<picture>` pair** — `Logo.V2.png` on light, `Logo.V1.png` on dark.
- **Badges follow the brand:** `style=flat-square`, `labelColor=000D1F`.
  Teal `00A79A` for the primary fact, Deep Teal `007A70` for secondary metadata,
  Slate `1F2D3D` for neutral or third-party status.
- **Colour and type are fixed** by [`brand-style-guide.jpg`](docs/assets/brand/brand-style-guide.jpg).
  Change the guide first, the surfaces second.

## Brand tokens

| Token | Hex | Role |
|---|---|---|
| FixByte Teal | `#00A79A` | Primary accent — the Forme, links, primary actions |
| Deep Teal | `#007A70` | Hover and pressed states, secondary metadata |
| Ink | `#000D1F` | Primary dark surface, body text on light |
| Carbon | `#080C0F` | Secondary dark surface — code, cards, footers |
| Paper | `#F8F8F8` | Light surface, reversed text |
| Slate | `#8A97A8` | Muted text — captions, metadata, disabled |

Type: **Roobert** (display and interface) · **JetBrains Mono** (code and technical labels).

## Also possible here

This repo can additionally host org-wide community health defaults, inherited by every
FixByte repository that does not define its own: `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`,
`SECURITY.md`, `SUPPORT.md`, `FUNDING.yml` and `.github/ISSUE_TEMPLATE/`.

---

<div align="center">
<sub>◆ &nbsp;&copy; 2026 FixByte — Belgium &nbsp;·&nbsp; <a href="https://fixbyte.be">fixbyte.be</a> &nbsp;·&nbsp; <a href="mailto:contact@fixbyte.be">contact@fixbyte.be</a></sub>
</div>
