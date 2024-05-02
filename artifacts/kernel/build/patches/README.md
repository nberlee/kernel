| Patch file                                                    | Description                                | Upstream status | Link                                                                                                                                                                                                         |
|---------------------------------------------------------------|--------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0001-arm64-dts-rockchip-Add-Turing-RK1-SoM-support.patch      | Add DTS overlay support for the Turing RK1 | 6.7             | [Patchwork](https://patchwork.kernel.org/project/linux-rockchip/patch/20231011225823.2542262-4-CFSworks@gmail.com/) / [mailing-list](https://lore.kernel.org/all/20231011225823.2542262-4-CFSworks@gmail.com/) |
| 0002-arm64-dts-rockchip-add-rk1-system-power-controller-and-remove-startup-delay-us-from-pci2.patch | Add system-power-controller and remove startup-delay making pci devices recognised earlier in boot process | Talos exclusive | Talos exclusive |
| 0003-arm64-dts-rockchip-Add-PCIe-pinctrls-to-Turing-RK1.patch | fix boot hang when the NVMe slot is not populated            | Not upstreamed  | [Github](https://github.com/Joshua-Riek/linux/commit/f4f691267440b371a4f46fd0e3c63cd514cdfa04)                                                                                                               |
| 0004-xhci-Introduce-disable-usb3-DT-property-quirk.patch | Add USB3 disable DT property quirk       | Not Upstreamed, USB-DP patch in 6.8 is an alternative but patchset is large             | [Github](https://github.com/CFSworks/alpine-rk1/blob/db2b5df883b6bcbfd812f12c998fa42613f08c56/main/linux-turing/0004-xhci-Introduce-disable-usb3-DT-property-quirk.patch)
| 0005-arm64-dts-rockchip-enable-built-in-thermal-monitoring-on-rk3588.patch | Enable built-in thermal monitoring on RK3588 | WIP             | [Patchwork](https://patchwork.kernel.org/project/linux-rockchip/patch/20240229-rk-dts-additions-v3-1-6afe8473a631@gmail.com/) / [mailing-list](https://lore.kernel.org/all/20240229-rk-dts-additions-v3-1-6afe8473a631@gmail.com/) |
| 0006-arm64-dts-rockchip-enable-temperature-driven-fan-control.patch | Enable temperature driven fan control on Rock 5B. Added Turing RK1 based on Rock 5B  | WIP             | [Patchwork](https://patchwork.kernel.org/project/linux-rockchip/patch/20240229-rk-dts-additions-v3-2-6afe8473a631@gmail.com/) / [mailing-list](https://lore.kernel.org/all/20240229-rk-dts-additions-v3-2-6afe8473a631@gmail.com/) |
| 0007-arm64-dts-rockchip-Add-OPP-data-for-CPU-cores-on-RK3588.patch | Add OPP data for CPU cores on RK3588     | WIP            | [Patchwork](https://patchwork.kernel.org/project/linux-rockchip/patch/20240229-rk-dts-additions-v3-4-6afe8473a631@gmail.com/) / [Patchwork](https://patchwork.kernel.org/project/linux-rockchip/patch/20240229-rk-dts-additions-v3-5-6afe8473a631@gmail.com/) / [mailing-list](https://lore.kernel.org/all/20240229-rk-dts-additions-v3-4-6afe8473a631@gmail.com/) / [mailing-list](https://patchwork.kernel.org/project/linux-rockchip/patch/20240229-rk-dts-additions-v3-5-6afe8473a631@gmail.com/) |
| 0008-cpufreq-rockchip-Introduce-driver-for-rk3588.patch | Collabora downstream port of Rockchip Kernel CPUfreq to support memory frequency scaling. cpufreq-dt could be used as an alternative without memory frequency scaling             | Not upstreamed             | [Gitlab](https://gitlab.collabora.com/hardware-enablement/rockchip-3588/linux/-/commit/e76454dab456ca5e0f51e8c4fbbd15649a329648) [Gitlab](https://gitlab.collabora.com/hardware-enablement/rockchip-3588/linux/-/commit/84eaf9e41a76a75542bbc281a7fe73e044e4cb52) |
| 0009-rk1-USB-2.0-OTG.patch | USB 2.0 OTG on Turing RK1 removed the cpufreq as it is part of 0001-arm64-dts-rockchip-Add-Turing-RK1-SoM-support.patch  | Not upstreamed             | [Github](https://github.com/CFSworks/alpine-rk1/blob/db2b5df883b6bcbfd812f12c998fa42613f08c56/main/linux-turing/0010-rk1-Enable-cpufreq-thermal-USB-2.0-OTG.patch) |
| 0010-arm64-dts-rockchip-fix-Turing-RK1-interrupt-pinctrls.patch | Fix interrupt pinctrls on Turing RK1             | 6.7             | [Patchwork](https://patchwork.kernel.org/project/linux-arm-kernel/patch/20231202071212.1606800-1-CFSworks@gmail.com/) / [mailing-list](https://lore.kernel.org/all/20231202071212.1606800-1-CFSworks@gmail.com/) |
| 0011-upstream-rockchip-dfi.patch | Memory monitoring for thermal shutdown using devfreq             | 6.7             | Diff from 6.7 |
| 0012-rockchip-dfi-dts.patch | Memory monitoring for thermal shutdown using devfreq (dts overlay)             | 6.7             | Diff from 6.7 |
| 0014-hwrng-rockchip.patch | Rockchip HW RNG support backported from Rockchips Kernel            | Not upstreamed             | [Github](https://github.com/armbian/build/pull/5928) |
| 0015-arm64-dts-rockchip-rk3588-rng.patch | Rockchip HW RNG support for RK3588            | Not upstreamed             | [Github](https://github.com/armbian/build/pull/5928) |
| 0016-drivers-clk-rockchip-rst-rk3588-secure-reset.patch | Add secure reset support for RK3588            | Not upstreamed             | [Patchwork](https://patchwork.kernel.org/project/linux-arm-kernel/patch/20231107155532.3747113-6-clabbe@baylibre.com/) / [mailing-list](https://lore.kernel.org/all/20231107155532.3747113-6-clabbe@baylibre.com/) |
| 0017-crypto-rockchip-add-rk3588-driver.patch | Add RK3588 crypto driver            | Not upstreamed             | [Patchwork](https://patchwork.kernel.org/project/linux-arm-kernel/patch/20231107155532.3747113-7-clabbe@baylibre.com/) / [mailing-list](https://lore.kernel.org/all/20231107155532.3747113-7-clabbe@baylibre.com/) |
| 0018-arch-arm64-boot-dts-rockchip-add-crypto.patch | Add crypto node to RK3588 dts            | Not upstreamed             | [Patchwork](https://patchwork.kernel.org/project/linux-arm-kernel/patch/20231107155532.3747113-4-clabbe@baylibre.com/) / [mailing-list](https://lore.kernel.org/all/20231107155532.3747113-4-clabbe@baylibre.com/) |
| 0019-net-stmmac-improve-tx-timer-logic.patch | Improve TX timer logic for stmmac            | 6.7             | [Patchwork](https://patchwork.kernel.org/project/linux-arm-kernel/list/?series=794317&state=%2A&archive=both) |
| 0020-net-stmmac-Add-support-for-HW-accelerated-VLAN-stripping.patch | Make VLANs work on stmmac (more than 210 bytes per frame)           | 6.8             | [Patchwork](https://patchwork.kernel.org/project/linux-arm-kernel/patch/20231121053842.719531-1-yi.fang.gan@intel.com/) |