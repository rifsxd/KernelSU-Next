[English](README.md) | [简体中文](README_CN.md) | [繁體中文](README_TW.md) | **Türkçe** | [Português (Brasil)](README_PT-BR.md) | [한국어](README_KO.md) | [Français](README_FR.md) | [Bahasa Indonesia](README_ID.md) | [Русский](README_RU.md) | [ภาษาไทย](README_TH.md)

# KernelSU Next

<img src="/assets/kernelsu_next.png" style="width: 96px;" alt="logo">

Android cihazlar için Kernel tabanlı bir root çözümü.

[![Latest Release](https://img.shields.io/github/v/release/rifsxd/KernelSU-Next?label=Release&logo=github)](https://github.com/rifsxd/KernelSU-Next/releases/latest)
[![Nightly Release](https://img.shields.io/badge/Nightly%20Release-gray?logo=hackthebox&logoColor=fff)](https://nightly.link/rifsxd/KernelSU-Next/workflows/build-manager-ci/next/Manager)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-orange.svg?logo=gnu)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![GitHub License](https://img.shields.io/github/license/rifsxd/KernelSU-Next?logo=gnu)](/LICENSE)

## Özellikler

1. Çekirdek tabanlı `su` ve kök erişim yönetimi.
2. Dinamik montaj sistemine dayalı modül sistemi [Magic Mount](https://topjohnwu.github.io/Magisk/details.html#magic-mount) / [OverlayFS](https://en.wikipedia.org/wiki/OverlayFS).
3. [App Profile](https://kernelsu.org/guide/app-profile.html): Kök gücünü bir kafese kilitleyin.

## Uyumluluk Durumu

KernelSU Next, 4.4'dan başlayarak 6.6'ya kadar çoğu Android çekirdeğini resmi olarak desteklemektedir.
 - GKI 2.0 (5.10+) çekirdekleri önceden oluşturulmuş görüntüleri ve LKM/KMI'yi çalıştırabilir.
 - GKI 1.0 (4.19 - 5.4) çekirdeklerinin KernelSU sürücüsü ile yeniden oluşturulması gerekir.
 - EOL (<4.14) çekirdeklerinin de KernelSU sürücüsü ile yeniden oluşturulması gerekir. (3.18+ deneyseldir ve bazı fonksiyon geri yüklemelerine ihtiyaç duyulabilir.)

Şu anda sadece `arm64-v8a` desteklenmektedir.

## Kullanım

- [Kurulum Talimatı](https://rifsxd.github.io/KernelSU-Next/)

## Güvenlik

KernelSU'daki güvenlik açıklarını bildirme hakkında bilgi için [SECURITY.md](/SECURITY.md) bölümüne bakın.

## Lisans

- `kernel` dizini altındaki dosyalar sadece [GPL-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) lisansına tabiidir.
- `kernel` dizini dışındaki diğer tüm kısımlar [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html) ya da daha sonraki bir sürüm lisansa tabiidir.

## Krediler

- [Kernel-Assisted Superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): KernelSU fikri.
- [Magisk](https://github.com/topjohnwu/Magisk): Güçlü kök aracı.
- [genuine](https://github.com/brevent/genuine/): APK v2 imza doğrulama.
- [Diamorphine](https://github.com/m0nad/Diamorphine): Bazı rootkit becerileri.
- [KernelSU](https://github.com/tiann/KernelSU): tiann'a teşekkürler, yoksa KernelSU Next var olamazdı bile.
- [Magic Mount Port](https://github.com/5ec1cff/KernelSU/blob/main/userspace/ksud/src/magic_mount.rs): 💜 5ec1cff KernelSU'yu kurtardığınız için!
