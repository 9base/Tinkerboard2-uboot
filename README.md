> [!NOTE]
> **9base status: Preserved** · **Lifecycle: archived reference copy.**
>
> This is a historical fork of [TinkerBoard2/u-boot](https://github.com/TinkerBoard2/u-boot).
> 9base retains it for provenance and reference and does not actively maintain it.
> Upstream source and inherited authorship remain attributed to their original contributors.

# Tinkerboard2-uboot — 9base preservation notes

## Role and branch index

This is the vendor U-Boot bootloader source component for the Tinker Board 2
Linux BSP family. The default `linux4.4-rk3399-debian10` branch and
`linux4.4-rk3399` were identical to their respective same-named upstream
branches in the 8 October 2026 audit. The non-default
[linux4.19-rk3399-debian10 branch](https://github.com/9base/Tinkerboard2-uboot/tree/linux4.19-rk3399-debian10)
was 0 ahead / 849 behind upstream. No fork-only commits were exposed on these
branches.

No account-linked Zaryob-authored commits were returned across the exposed
branches; that filter is not exhaustive evidence about every unlinked
historical identity. Distinct current 9base bootloader work was not established.

The substantial upstream [README](README), [license material](Licenses), credits
and source history are preserved unchanged. Historical upstream statements
about board support are not a claim that this curation tested a contemporary
Tinker Board 2 build or deployment.

## Tinker Board 2 platform family

| Layer | Preserved 9base repository |
| --- | --- |
| Linux checkout manifests | [Tinkerboard2-manifest](https://github.com/9base/Tinkerboard2-manifest) |
| Linux kernel | [Tinkerboard2-kernel](https://github.com/9base/Tinkerboard2-kernel) |
| U-Boot bootloader | [Tinkerboard2-uboot](https://github.com/9base/Tinkerboard2-uboot) |
| Buildroot build system | [Tinkerboard2-buildroot](https://github.com/9base/Tinkerboard2-buildroot) |
| Debian/rootfs scripts | [Tinkerboard2-debian](https://github.com/9base/Tinkerboard2-debian) |
| Rockchip firmware and loaders | [Tinkerboard2-rkbin](https://github.com/9base/Tinkerboard2-rkbin) |
| Poky/OpenEmbedded/BitBake | [yocto-poky](https://github.com/9base/yocto-poky) |
| Android checkout manifests | [Tinkerboard2Android-manifest](https://github.com/9base/Tinkerboard2Android-manifest) |

The [Linux release manifest](https://github.com/9base/Tinkerboard2-manifest/blob/linux4.19-rk3399-debian10/default.xml) explicitly names the kernel, U-Boot,
Buildroot, Debian, rkbin and yocto-poky components. Its remote still points to
`TinkerBoard2`, not these 9base forks; it does not automatically select 9base's
historical Debian fix. This family is only a retained subset of the vendor's
larger source graph, not a self-contained complete BSP checkout.

The Android manifests concern the same board family but target a separate
`TinkerBoard2-Android` source graph; they do not establish use of these 9base
Linux components.

## Historical note

These preservation notes were reconstructed on **8 October 2026** from the
repository tree, exposed branches, commit history and upstream comparisons.
They are new archival documentation, not evidence that this explanation existed
at the historical fork date. The original reason for retention or any deployment
is not established by the inspected record. No contemporary build, support or
upstream synchronization commitment is implied.

The original upstream [README](README) is retained as a separate,
unchanged file. Its historical content and other README variants are preserved.
