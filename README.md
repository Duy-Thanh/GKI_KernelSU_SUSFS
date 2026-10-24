<div align="center">

# Nekko Kernels for Android devices running GKI 2.0 (5.10+)

Based on WildKernels by TheWildJames

[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Third-Party Notices](https://img.shields.io/badge/notices-THIRD__PARTY_NOTICES-lightgrey.svg)](THIRD_PARTY_NOTICES.md)

</div>

> [!CAUTION]
> Nekko Kernels is not responsible for bricked devices or damage. By flashing, you assume all risk. Back up your data and understand the risks before flashing.

---

## About

Generic kernels built on [Google's GKI sources](https://android.googlesource.com/kernel/common/) with KernelSU and SUSFS for root hiding and detection evasion — broad compatibility, not guaranteed for every device.

---

## Features

- **KernelSU / KernelSU-Next / BakaSU / FinaSU / Suki-SU Ultra / KowSU** — root implementations
- **susfs4ksu** — root hiding (incl. Ptrace Leak Fix, Unicode Fix)
- **NoMount / Mountify** — mount metamodules
- **Baseband Guard** — partition protection
- **Networking** — WireGuard, BBR, IPSet, CIFS
- **TMPFS** — xattr / POSIX ACLs
- **BPF** — BTF / eBPF / FUSE-BPF
- **Performance** — incl. NTSync
- **DroidSpaces** — container runtime

---

## Build Your Own Kernel

Fork the repository and follow **[Build Your Own Kernel](docs/build-from-fork.md)** to select one kernel family, patch level, root implementation, and feature set in GitHub Actions.

---

## Special Thanks

**These amazing people and projects make this possible:**

- **WildKernels** — [TheWildJames](https://github.com/WildKernels/GKI_KernelSU_SUSFS)
- **KernelSU** — [tiann](https://github.com/tiann/KernelSU)
- **KernelSU-Next** — [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next)
- **KernelSU-Next SUSFS Fork** — [pershoot](https://github.com/pershoot/KernelSU-Next)
- **BakaSU** (formerly ReSukiSU) — [BakaSU](https://github.com/Baka-SU/BakaSU)
- **FinaSU** — [LyraVoid](https://github.com/LyraVoid/FinaSU)
- **Suki-SU Ultra** — [SukiSU Ultra](https://github.com/sukisu-ultra/sukisu-ultra)
- **KowSU** (KOWX712's KernelSU fork) — [KowSU](https://github.com/KOWX712/KernelSU)
- **Magic-KSU** — [5ec1cff](https://github.com/5ec1cff/KernelSU)
- **SUSFS** — [simonpunk](https://gitlab.com/simonpunk/susfs4ksu)
- **SUSFS Module** — [sidex15](https://github.com/sidex15)
- **NoMount** — [maxsteeel](https://github.com/maxsteeel/nomount)
- **DroidSpaces-OSS** — [ravindu644](https://github.com/ravindu644/Droidspaces-OSS)
- **Baseband-guard (BBG)** — [vc-teahouse](https://github.com/vc-teahouse/Baseband-guard)
- **Kernel Patches** — [WildKernels/kernel_patches](https://github.com/WildKernels/kernel_patches)
- **AnyKernel3** — [osm0sis](https://github.com/osm0sis/AnyKernel3)
- **Sultan Kernels (Pixel)** — [kerneltoast](https://github.com/kerneltoast)
- **Device Boot Fix** — [Boot fix commit](https://github.com/Anything-at-25-00/android_kernel_common_android12-5.10/commit/2476d262b597fe8af82cfb7aaf96676f51c6b4ed)

**Contributors to this repository:**

Have an idea or improvement in mind? Contributions are always welcome — feel free to open a pull request or share your thoughts!

## Donations

> [!IMPORTANT]
> **If you find this useful, please consider donating directly to the author who maintains the upstream repository: WildKernels (TheWildJames). Information for the upstream maintainer, WildKernels (TheWildJames), is provided below:**
> 
> **Kind note:** A donation is truly just a gift — not a payment for support, features, or priority. It doesn't unlock anything extra on our side and doesn't change how we help you; everyone gets the same community support whether you donate or not. Think of it as a kind “thank you” to help keep development going — not a transaction. If you do choose to give, we're genuinely grateful, but please never feel obligated.

- PayPal: [bauhd@outlook.com](mailto:bauhd@outlook.com)
- Card: <https://buy.stripe.com/5kQ28sdi08Nr0Xc2fU5os00>
- LTC: `MVaN1ToSuks2cdK9mB3M8EHCfzQSyEMf6h`
- BTC: `3BBXAMS4ZuCZwfbTXxWGczxHF4isymeyxG`
- ETH: `0x2b9C846c84d58717e784458406235C09a834274e`
- Patreon: <https://patreon.com/WildKernels>
