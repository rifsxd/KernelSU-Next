**Türkçe** | [English](README.md) | [简体中文](README_CN.md) | [繁體中文](README_TW.md) | [Português (Brasil)](README_PT-BR.md) | [한국어](README_KO.md) | [Français](README_FR.md) | [Bahasa Indonesia](README_ID.md) | [Русский](README_RU.md) | [ภาษาไทย](README_TH.md)

# KernelSU Next

<img src="/assets/kernelsu_next.png" style="width: 96px;" alt="logo">

Android cihazlar için çekirdek tabanlı bir root çözümü.

[![](https://img.shields.io/github/v/release/rifsxd/KernelSU-Next?label=Release&logo=github)](https://github.com/rifsxd/KernelSU-Next/releases/latest)
[![](https://img.shields.io/badge/Nightly%20Release-gray?logo=hackthebox&logoColor=fff)](https://nightly.link/rifsxd/KernelSU-Next/workflows/build-manager-ci/next/manager)
[![](https://img.shields.io/badge/License-GPL%20v2-orange.svg?logo=gnu)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![](https://img.shields.io/github/license/rifsxd/KernelSU-Next?logo=gnu)](/LICENSE)

## Özellikler

1. Çekirdek tabanlı `su` ve root erişim yönetimi.
2. Dinamik bağlama sistemine dayalı modül sistemi: [Magic Mount](https://topjohnwu.github.io/Magisk/details.html#magic-mount) / [OverlayFS](https://en.wikipedia.org/wiki/OverlayFS).
3. [Uygulama Profili](https://kernelsu.org/guide/app-profile.html): Root yetkilerini sınırlayın

## Uyumluluk Durumu

KernelSU Next, 4.4 ile 6.6 arasındaki çoğu Android çekirdeğini resmi olarak destekler.
 - GKI 2.0 (5.10+) çekirdekleri, önceden derlenmiş görüntüleri ve LKM/KMI'yi çalıştırabilir.
 - GKI 1.0 (4.19 - 5.4) çekirdekleri, KernelSU sürücüsüyle yeniden derlenmelidir.
 - EOL (<4.14) çekirdekleri de KernelSU sürücüsüyle yeniden derlenmelidir (3.18+ deneyseldir ve bazı işlevlerin geri taşınması gerekebilir).

Şu anda yalnızca `arm64-v8a` mimarisi desteklenmektedir.

## Kullanım

- [Kurulum talimatları](https://rifsxd.github.io/KernelSU-Next/)

## Güvenlik

KernelSU'daki güvenlik açıklarını bildirme hakkında bilgi için [SECURITY.md](/SECURITY.md) dosyasına bakın.

## Lisans

- `kernel` dizini altındaki dosyalar [GPL-2.0-only](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) lisansı altındadır.
- `kernel` dizini dışındaki tüm bölümler [GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html) lisansı altındadır.

## Katkıda Bulunanlar

- [kernel-assisted-superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): KernelSU fikri.
- [Magisk](https://github.com/topjohnwu/Magisk): Güçlü root aracı.
- [genuine](https://github.com/brevent/genuine/): APK v2 imza doğrulaması.
- [Diamorphine](https://github.com/m0nad/Diamorphine): Bazı rootkit teknikleri.
- [KernelSU](https://github.com/tiann/KernelSU): Tiann'e teşekkürler, aksi halde KernelSU Next var olmazdı.
- [Magic Mount Port](https://github.com/5ec1cff/KernelSU/blob/main/userspace/ksud/src/magic_mount.rs): 💜 5ec1cff, KernelSU'yu kurtardığın için teşekkürler!
