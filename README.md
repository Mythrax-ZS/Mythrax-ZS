# MYTHRAX

```text
[  0.000] mythrax.sys: boot entry point reached
[  0.014] jit: rustarmic online (aarch64 -> x86_64, zero C++ harmed)
[  0.029] gpu: maxwell pipeline up, translating SASS like it owes me money
[  0.041] fs: mounted /preservation (read-write, forever)
[  0.056] nvdrv: ioctl storm survived
[  0.062] boot complete. welcome to the archive.
```

i build and revive Nintendo Switch emulators. if a project dies, i dig it up. if hardware is undocumented, i document it the hard way: one hexdump at a time.

[mythrax-rs.org](https://mythrax-rs.org/) • rust, c++, armv8, vulkan • windows, unapologetically

<br>

## compatibility list

| title | status | notes |
|---|---|---|
| ⚡ [NeXium](https://github.com/nexium-emu) | 🟢 in active development | Switch emulator written from scratch in Rust. my main quest. |
| 🍋 [Citron NEO](https://github.com/citron-neo) | 🟢 playable | "the switch fell off" • [citron-neo.org](https://citron-neo.org/) |
| 🐉 [yuzu-revived](https://github.com/yuzu-revived) | 🔵 preserved | yuzu and its whole dependency tree, kept breathing |
| 🦀 [rustarmic](https://github.com/nexium-emu/rustarmic) | 🟡 in-game | ARMv8 JIT recompiler in pure Rust |
| 🔗 [dynarmic-sys](https://github.com/Mythrax-ZS/dynarmic-sys) | 🟢 playable | Rust FFI bindings for the dynarmic JIT |
| 🌑 [DarkMatter](https://github.com/Mythrax-ZS/DarkMatter) | ⚫ dark type | theming, because light mode is a crime |
| 🏠 homebrew stack | 🔵 preserved | [emuMMC](https://github.com/Mythrax-ZS/emuMMC) · [libnx](https://github.com/Mythrax-ZS/libnx) · [nx-hbmenu](https://github.com/Mythrax-ZS/nx-hbmenu) · [Checkpoint](https://github.com/Mythrax-ZS/Checkpoint) |

🟢 runs great · 🟡 boots, being tamed · 🔵 archived alive · ⚫ intentionally dark

<br>

## trainer card

<a href="https://github.com/Leorev01/pokemon-profile-card"><img src="https://profile-card-ten-green.vercel.app/api/card?username=Mythrax-ZS&type=ghost" width="60%"></a>

*ghost type. i specialize in resurrections.*

<details>
<summary>📁 load save file</summary>
<br>
<p>
  <img src="https://github-readme-stats-fast.vercel.app/api?username=Mythrax-ZS&show_icons=true&theme=github_dark&show=reviews,prs_merged,prs_merged_percentage" width="47%">
  <img src="https://github-readme-stats-fast.vercel.app/api/streak?username=Mythrax-ZS&theme=github_dark" width="47%">
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Mythrax-ZS&layout=compact&theme=github_dark" width="47%">
</p>
</details>

<br>

## loaded modules

```rust
static STACK: &[(&str, &str)] = &[
    ("rust",    "emulator core, JIT, everything that matters"),
    ("c/c++",   "dynarmic, homebrew, upstream archaeology"),
    ("vulkan",  "maxwell -> spir-v, one draw call at a time"),
    ("re",      "armv8 + gpu reverse engineering, hexdumps included"),
];
```

<br>

###### emulation is preservation. preservation is forever. `[EOF]`
