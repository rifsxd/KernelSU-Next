**English** | [简体中文](README_CN.md) | [繁體中文](README_TW.md) | [Türkçe](README_TR.md) | [Português (Brasil)](README_PT-BR.md) | [한국어](README_KO.md) | [Français](README_FR.md) | [Bahasa Indonesia](README_ID.md)
| [Polish](README_PL.md)

# KernelSU Next

<img src="/assets/kernelsu_next.png" style="width: 96px;" alt="logo">

Bazowane na kernelu rozwiązanie roota.

[![Najnowsze Wydanie](https://img.shields.io/github/v/release/rifsxd/KernelSU-Next?label=Release&logo=github)](https://github.com/rifsxd/KernelSU-Next/releases/latest)
[![Nightly Wydanie](https://img.shields.io/badge/Nightly%20Release-gray?logo=hackthebox&logoColor=fff)](https://nightly.link/rifsxd/KernelSU-Next/workflows/build-manager/next/manager)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-orange.svg?logo=gnu)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![GitHub License](https://img.shields.io/github/license/rifsxd/KernelSU-Next?logo=gnu)](/LICENSE)

## Funkcje

1. Bazowane na kernelu `su` i zarządzanie rootem.
2. Modułowe bazowanie montowania systemu. [Magic Mount](https://topjohnwu.github.io/Magisk/details.html#magic-mount) / [OverlayFS](https://en.wikipedia.org/wiki/OverlayFS).
3. [App Profile](https://kernelsu.org/guide/app-profile.html): Zamknąć funkcje roota w klatce.

## Kompatybilność 

KernelSU Next oficjalnie wspiera kernele od 4.14 do 6.6
 - GKI 2.0 (5.10+) kernele mogą być zainstalowane przez LKM/KMI (zbudowane).
 - GKI 1.0 (4.19 - 5.4) kernele muszą być skompilowane z sterownikiem KernelSU.
 - EOL (<4.14) kernele też muszą być przebudowane z sterownikiem KernelSU (3.18+ jest eksperemyntalne i raczej potrzebuje backporyy niektórych funkcji).

Na ten czas, tylko `arm64-v8a` jest wspierane.

## Użytkowanie

- [Instrukcja Instalacji [EN](https://rifsxd.github.io/KernelSU-Next/)

## Bezpieczeństwo

Żeby zgłaszac problemy związane z KernelSU, proszę zobaczyć [SECURITY.md](/SECURITY.md).

## License

- Wszystkie pliki pod folderem `kernel` są [GPL-2.0-only](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).
- Wszystkie inne części w folderze `kernel` są [GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html).

## Podziękowania

- [kernel-assisted-superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): pomysł na KernelSU.
- [Magisk](https://github.com/topjohnwu/Magisk): mocarny menedżer rootu..
- [genuine](https://github.com/brevent/genuine/): weryfikowanie certyfikatów plików apk v2.
- [Diamorphine](https://github.com/m0nad/Diamorphine): umiejętności rootkita.
- [KernelSU](https://github.com/tiann/KernelSU): thanks to tiann, or else KernelSU Next wouldn't even exist.
- [Magic Mount Port](https://github.com/5ec1cff/KernelSU/blob/main/userspace/ksud/src/magic_mount.rs): 💜 5ec1cff for saving KernelSU!
