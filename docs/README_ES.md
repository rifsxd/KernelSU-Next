**English** | [简体中文](README_CN.md) | [繁體中文](README_TW.md) | [Türkçe](README_TR.md) | [Português (Brasil)](README_PT-BR.md) | [한국어](README_KO.md) | [Français](README_FR.md) | [Bahasa Indonesia](README_ID.md) | [Русский](README_RU.md) | [ภาษาไทย](README_TH.md)
(README_ES.md) | [Español]

# KernelSU Next

<img src="/assets/kernelsu_next.png" style="width: 96px;" alt="logo">

Una solución basada en el kernel para hacer root en dispositivos android.

[![Ultima Version](https://img.shields.io/github/v/release/rifsxd/KernelSU-Next?label=Release&logo=github)](https://github.com/rifsxd/KernelSU-Next/releases/latest)
[![Version Nightly](https://img.shields.io/badge/Nightly%20Release-gray?logo=hackthebox&logoColor=fff)](https://nightly.link/rifsxd/KernelSU-Next/workflows/build-manager/next/manager)
[![Licencia: GPL v2](https://img.shields.io/badge/License-GPL%20v2-orange.svg?logo=gnu)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![Licencia de GitHub](https://img.shields.io/github/license/rifsxd/KernelSU-Next?logo=gnu)](/LICENSE)

## Funciones

 1. Acceso root y administración basados en su del kernel.
 2. Sistema de módulos basado en sistema de montaje dinámico Magic Mount / OverlayFS.
 3. Perfil de la app: Encierra el poder root en una jaula.


## Estado de Compatibilidad
KernelSU Next es compatible oficialmente con la mayoría de los kernels de Android desde 4.4 hasta 6.6.
 * Kernels GKI 2.0 (5.10+): Pueden ejecutar imágenes precompiladas y LKM/KMI.
 * Kernels GKI 1.0 (4.19 - 5.4): Deben ser reconstruidos con el controlador KernelSU.
 * Kernels EOL (<4.14): También deben ser reconstruidos con el controlador KernelSU (3.18+ es experimental y puede requerir algunos retrocesos de funciones).


Por ahora, solo `arm64-v8a` esta soportado.

## Uso

- [Instrucciones de instalacion](https://rifsxd.github.io/KernelSU-Next/)

## Seguridad

Para informacion para reportar vulnerabilidades en la seguridad de KernelSU, mira [SECURITY.md](/SECURITY.md).

## Licencia

 * Los archivos bajo el directorio kernel tienen licencia GPL-2.0-only.
 * Todas las demás partes excepto el directorio kernel tienen licencia GPL-3.0-o-posterior.


## Donaciones

- 0x12b5224b7aca0121c2f003240a901e1d064371c1 [ USDT BEP20 ]

- TYUVMWGTcnR5svnDoX85DWHyqUAeyQcdjh [ USDT TRC20 ]

- 0x12b5224b7aca0121c2f003240a901e1d064371c1 [ USDT ERC20 ]

- 0x12b5224b7aca0121c2f003240a901e1d064371c1 [ ETH ERC20 ]

- Ld238uYBuRQdZB5YwdbkuU6ektBAAUByoL [ LTC ]

- 19QgifcjMjSr1wB2DJcea5cxitvWVcXMT6 [ BTC ]

## Creditos

- [kernel-assisted-superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): the KernelSU idea.
- [Magisk](https://github.com/topjohnwu/Magisk): the powerful root tool.
- [genuine](https://github.com/brevent/genuine/): apk v2 signature validation.
- [Diamorphine](https://github.com/m0nad/Diamorphine): some rootkit skills.
- [KernelSU](https://github.com/tiann/KernelSU): thanks to tiann, or else KernelSU Next wouldn't even exist.
- [Magic Mount Port](https://github.com/5ec1cff/KernelSU/blob/main/userspace/ksud/src/magic_mount.rs): 💜 5ec1cff for saving KernelSU!
