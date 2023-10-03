Alpine - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 101

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Unknown       | Unknown                     | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| Dell          | Latitude 5430 Rugged        | [051aebd1a2](https://linux-hardware.org/?probe=051aebd1a2) | Jul 24, 2023 |
| ASUSTek       | A3AC                        | [1bf0a25c8e](https://linux-hardware.org/?probe=1bf0a25c8e) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | [f7fb9875de](https://linux-hardware.org/?probe=f7fb9875de) | Jul 22, 2023 |
| Toshiba       | Satellite Pro L50-A         | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Google        | Kefka                       | [c5d9002e23](https://linux-hardware.org/?probe=c5d9002e23) | Jun 23, 2023 |
| Lenovo        | ThinkPad T440p              | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| Toshiba       | WT8-A                       | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| MSI           | U200                        | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Olivetti      | Spring Peak                 | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Fujitsu       | FMVNP8AE                    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| Acer          | Aspire ES1-132              | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Lenovo        | V14-ADA 82C6                | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| Google        | Leona                       | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| Dell          | Inspiron 3558               | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
| Dell          | Inspiron N5010              | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Dell          | Inspiron 5447               | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Toshiba       | Satellite M645              | [b342f11704](https://linux-hardware.org/?probe=b342f11704) | Aug 16, 2022 |
| Toshiba       | Satellite M645              | [f64d98a9e1](https://linux-hardware.org/?probe=f64d98a9e1) | Aug 16, 2022 |
| Dell          | Inspiron 3180               | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Fujitsu       | LIFEBOOK P702               | [fdbe6c32cd](https://linux-hardware.org/?probe=fdbe6c32cd) | Aug 06, 2022 |
| Sony          | VGN-UX27GN                  | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| HP            | EliteBook 8460p             | [a0a6c37152](https://linux-hardware.org/?probe=a0a6c37152) | Jun 19, 2022 |
| ASUSTek       | X555LAB                     | [e47cf70de1](https://linux-hardware.org/?probe=e47cf70de1) | Jun 17, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| ASUSTek       | N10Jc                       | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| HP            | ProBook 4310s               | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| Haier         | U144S                       | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer          | Aspire E5-553G              | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX431FA             | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| ASUSTek       | ZenBook UX431FA             | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP            | EliteBook 1040 G3 Notebo... | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| MSI           | GL72M 7REX                  | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Lenovo        | ThinkPad W700 2752RZ2       | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Dell          | Inspiron MM061              | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| ASUSTek       | X550EA                      | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP            | Compaq Mini CQ10-600        | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown       | Unknown                     | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| Pegatron      | Deepcam                     | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | EliteBook 2740p             | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP            | EliteBook 2740p             | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek       | X200MA                      | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP            | Laptop 14-dq1xxx            | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM           | 264070A                     | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP            | Mini 110-3500               | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP            | ENVY Sleekbook 6 PC         | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Acer          | Aspire ES1-512              | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer          | Aspire 5920G                | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP            | Compaq Mini CQ10-600        | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway       | MX3631m                     | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell          | Studio 1747                 | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| Dell          | Inspiron 3180               | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek       | E502SA                      | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM           | 26446AG                     | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM           | 26446AG                     | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| Google        | Samus                       | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Dell          | Inspiron 5566               | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Apple         | MacBook7,1                  | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
| Lenovo        | ThinkPad 11e 20ED001HUS     | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer          | Aspire ES1-111M             | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| HP            | ZBook 15 G5                 | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology      | DS1019+                     | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology      | DS1019+                     | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology      | DS1019+                     | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.16.0               | 6         | 8.22%   |
| Alpine 3.15.0               | 6         | 8.22%   |
| Alpine 3.14.0               | 5         | 6.85%   |
| Alpine 3.12.0               | 5         | 6.85%   |
| Alpine 3.18.3               | 4         | 5.48%   |
| Alpine 3.15.0_alpha20210804 | 4         | 5.48%   |
| Alpine 3.18.0               | 3         | 4.11%   |
| Alpine 3.17.2               | 3         | 4.11%   |
| Alpine 3.17.0               | 3         | 4.11%   |
| Alpine 3.15.4               | 3         | 4.11%   |
| Alpine 3.18_alpha20230329   | 2         | 2.74%   |
| Alpine 3.17.1               | 2         | 2.74%   |
| Alpine 3.16.2               | 2         | 2.74%   |
| Alpine 3.14.2               | 2         | 2.74%   |
| Alpine 3.13.5               | 2         | 2.74%   |
| Alpine 3.13.0_alpha20201218 | 2         | 2.74%   |
| Alpine 3.13.0_alpha20200917 | 2         | 2.74%   |
| Alpine 3.11.2               | 2         | 2.74%   |
| Alpine 3.18.2               | 1         | 1.37%   |
| Alpine 3.17_alpha20220809   | 1         | 1.37%   |
| Alpine 3.17.3               | 1         | 1.37%   |
| Alpine 3.16.3               | 1         | 1.37%   |
| Alpine 3.16.1               | 1         | 1.37%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.37%   |
| Alpine 3.15.2               | 1         | 1.37%   |
| Alpine 3.15.0_rc5           | 1         | 1.37%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.37%   |
| Alpine 3.13.1               | 1         | 1.37%   |
| Alpine 3.13.0_rc2           | 1         | 1.37%   |
| Alpine 3.13.0_alpha20200626 | 1         | 1.37%   |
| Alpine 3.12.3               | 1         | 1.37%   |
| Alpine 3.12.1               | 1         | 1.37%   |
| Alpine 3.11.5               | 1         | 1.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 67        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.4.83-0-lts           | 2         | 2.67%   |
| 5.4.43-1-lts           | 2         | 2.67%   |
| 5.15.86-0-lts          | 2         | 2.67%   |
| 5.15.59-0-lts          | 2         | 2.67%   |
| 5.15.47-0-lts          | 2         | 2.67%   |
| 5.15.41-0-lts          | 2         | 2.67%   |
| 5.15.4-0-lts           | 2         | 2.67%   |
| 6.4.4-0-edge           | 1         | 1.33%   |
| 6.1.53-0-lts           | 1         | 1.33%   |
| 6.1.52-0-lts           | 1         | 1.33%   |
| 6.1.46-0-lts           | 1         | 1.33%   |
| 6.1.39-0-lts           | 1         | 1.33%   |
| 6.1.34                 | 1         | 1.33%   |
| 6.1.24-0-lts           | 1         | 1.33%   |
| 6.1.11-0-edge          | 1         | 1.33%   |
| 5.8.12-0-edge          | 1         | 1.33%   |
| 5.7.4                  | 1         | 1.33%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.33%   |
| 5.4.84-0-lts           | 1         | 1.33%   |
| 5.4.72-0-lts           | 1         | 1.33%   |
| 5.4.64-0-lts           | 1         | 1.33%   |
| 5.4.46-0-lts           | 1         | 1.33%   |
| 5.4.27-0-lts           | 1         | 1.33%   |
| 5.4.0-77-generic       | 1         | 1.33%   |
| 5.19.0-50-generic      | 1         | 1.33%   |
| 5.17.9-0-edge          | 1         | 1.33%   |
| 5.17.0-0-edge          | 1         | 1.33%   |
| 5.16.12-may            | 1         | 1.33%   |
| 5.16.1-may             | 1         | 1.33%   |
| 5.15.96-0-lts          | 1         | 1.33%   |
| 5.15.95-0-lts          | 1         | 1.33%   |
| 5.15.89-0-lts          | 1         | 1.33%   |
| 5.15.85-0-lts          | 1         | 1.33%   |
| 5.15.73-0-lts          | 1         | 1.33%   |
| 5.15.60-0-lts          | 1         | 1.33%   |
| 5.15.46-1-lts          | 1         | 1.33%   |
| 5.15.37-0-lts          | 1         | 1.33%   |
| 5.15.34                | 1         | 1.33%   |
| 5.15.30-0-lts          | 1         | 1.33%   |
| 5.15.28-0-lts          | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.83  | 2         | 2.67%   |
| 5.4.43  | 2         | 2.67%   |
| 5.15.86 | 2         | 2.67%   |
| 5.15.59 | 2         | 2.67%   |
| 5.15.47 | 2         | 2.67%   |
| 5.15.41 | 2         | 2.67%   |
| 5.15.4  | 2         | 2.67%   |
| 5.15.0  | 2         | 2.67%   |
| 6.4.4   | 1         | 1.33%   |
| 6.1.53  | 1         | 1.33%   |
| 6.1.52  | 1         | 1.33%   |
| 6.1.46  | 1         | 1.33%   |
| 6.1.39  | 1         | 1.33%   |
| 6.1.34  | 1         | 1.33%   |
| 6.1.24  | 1         | 1.33%   |
| 6.1.11  | 1         | 1.33%   |
| 5.8.12  | 1         | 1.33%   |
| 5.7.4   | 1         | 1.33%   |
| 5.6.2   | 1         | 1.33%   |
| 5.4.84  | 1         | 1.33%   |
| 5.4.72  | 1         | 1.33%   |
| 5.4.64  | 1         | 1.33%   |
| 5.4.46  | 1         | 1.33%   |
| 5.4.27  | 1         | 1.33%   |
| 5.4.0   | 1         | 1.33%   |
| 5.19.0  | 1         | 1.33%   |
| 5.17.9  | 1         | 1.33%   |
| 5.17.0  | 1         | 1.33%   |
| 5.16.12 | 1         | 1.33%   |
| 5.16.1  | 1         | 1.33%   |
| 5.15.96 | 1         | 1.33%   |
| 5.15.95 | 1         | 1.33%   |
| 5.15.89 | 1         | 1.33%   |
| 5.15.85 | 1         | 1.33%   |
| 5.15.73 | 1         | 1.33%   |
| 5.15.60 | 1         | 1.33%   |
| 5.15.46 | 1         | 1.33%   |
| 5.15.37 | 1         | 1.33%   |
| 5.15.34 | 1         | 1.33%   |
| 5.15.30 | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 30        | 41.1%   |
| 5.10    | 11        | 15.07%  |
| 5.4     | 10        | 13.7%   |
| 6.1     | 7         | 9.59%   |
| 5.17    | 2         | 2.74%   |
| 5.14    | 2         | 2.74%   |
| 6.4     | 1         | 1.37%   |
| 5.8     | 1         | 1.37%   |
| 5.7     | 1         | 1.37%   |
| 5.6     | 1         | 1.37%   |
| 5.19    | 1         | 1.37%   |
| 5.16    | 1         | 1.37%   |
| 5.13    | 1         | 1.37%   |
| 5.12    | 1         | 1.37%   |
| 4.4     | 1         | 1.37%   |
| 3.18    | 1         | 1.37%   |
| 3.10    | 1         | 1.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 80.6%   |
| i686   | 10        | 14.93%  |
| armv7l | 2         | 2.99%   |
| i586   | 1         | 1.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 76.12%  |
| XFCE    | 9         | 13.43%  |
| GNOME   | 4         | 5.97%   |
| sway    | 1         | 1.49%   |
| LXQt    | 1         | 1.49%   |
| KDE5    | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 32        | 46.38%  |
| Unknown | 31        | 44.93%  |
| Wayland | 6         | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 70.15%  |
| LightDM | 13        | 19.4%   |
| SDDM    | 2         | 2.99%   |
| LXDM    | 2         | 2.99%   |
| GDM     | 2         | 2.99%   |
| XDM     | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 43        | 60.56%  |
| Unknown | 20        | 28.17%  |
| en_US   | 6         | 8.45%   |
| ru_RU   | 1         | 1.41%   |
| en_GB   | 1         | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 45        | 65.22%  |
| EFI  | 24        | 34.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 78.57%  |
| Btrfs   | 6         | 8.57%   |
| Overlay | 4         | 5.71%   |
| Tmpfs   | 2         | 2.86%   |
| F2fs    | 1         | 1.43%   |
| Ext2    | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 64.29%  |
| GPT     | 17        | 24.29%  |
| MBR     | 8         | 11.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 91.18%  |
| Yes       | 6         | 8.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 91.3%   |
| Yes       | 6         | 8.7%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 12        | 17.91%  |
| Lenovo           | 11        | 16.42%  |
| Dell             | 9         | 13.43%  |
| ASUSTek Computer | 8         | 11.94%  |
| Acer             | 5         | 7.46%   |
| Toshiba          | 3         | 4.48%   |
| IBM              | 3         | 4.48%   |
| Google           | 3         | 4.48%   |
| Fujitsu          | 2         | 2.99%   |
| Unknown          | 2         | 2.99%   |
| Synology         | 1         | 1.49%   |
| Sony             | 1         | 1.49%   |
| Pegatron         | 1         | 1.49%   |
| Olivetti         | 1         | 1.49%   |
| Notebook         | 1         | 1.49%   |
| MSI              | 1         | 1.49%   |
| LG Electronics   | 1         | 1.49%   |
| Haier            | 1         | 1.49%   |
| Gateway          | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 2.99%   |
| Toshiba WT8-A                            | 1         | 1.49%   |
| Toshiba Satellite Pro L50-A              | 1         | 1.49%   |
| Toshiba Satellite M645                   | 1         | 1.49%   |
| Synology DS1019+                         | 1         | 1.49%   |
| Sony VGN-UX27GN                          | 1         | 1.49%   |
| Pegatron Deepcam                         | 1         | 1.49%   |
| Olivetti Spring Peak                     | 1         | 1.49%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 1.49%   |
| MSI GL72M 7REX                           | 1         | 1.49%   |
| LG LW25-B7HG                             | 1         | 1.49%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.49%   |
| Lenovo V14-ADA 82C6                      | 1         | 1.49%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.49%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.49%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.49%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 1.49%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.49%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.49%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 1         | 1.49%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.49%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 1.49%   |
| IBM 26446AG                              | 1         | 1.49%   |
| IBM 264070A                              | 1         | 1.49%   |
| HP ZBook 15 G5                           | 1         | 1.49%   |
| HP ProBook 4310s                         | 1         | 1.49%   |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 1.49%   |
| HP Presario V2000 (ES307UA#ABL)          | 1         | 1.49%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 1.49%   |
| HP Mini 110-3500                         | 1         | 1.49%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.49%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.49%   |
| HP EliteBook 8460p                       | 1         | 1.49%   |
| HP EliteBook 2740p                       | 1         | 1.49%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 1.49%   |
| HP Compaq Mini CQ10-600                  | 1         | 1.49%   |
| Haier U144S                              | 1         | 1.49%   |
| Google Samus                             | 1         | 1.49%   |
| Google Leona                             | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 7         | 10.45%  |
| Dell Inspiron     | 6         | 8.96%   |
| Acer Aspire       | 5         | 7.46%   |
| HP EliteBook      | 3         | 4.48%   |
| Toshiba Satellite | 2         | 2.99%   |
| HP Presario       | 2         | 2.99%   |
| Unknown           | 2         | 2.99%   |
| Toshiba WT8-A     | 1         | 1.49%   |
| Synology DS1019+  | 1         | 1.49%   |
| Sony VGN-UX27GN   | 1         | 1.49%   |
| Pegatron Deepcam  | 1         | 1.49%   |
| Olivetti Spring   | 1         | 1.49%   |
| Notebook NV4XMB   | 1         | 1.49%   |
| MSI GL72M         | 1         | 1.49%   |
| LG LW25-B7HG      | 1         | 1.49%   |
| Lenovo Yoga       | 1         | 1.49%   |
| Lenovo V14-ADA    | 1         | 1.49%   |
| Lenovo ThinkBook  | 1         | 1.49%   |
| Lenovo IdeaPad    | 1         | 1.49%   |
| IBM ThinkPad      | 1         | 1.49%   |
| IBM 26446AG       | 1         | 1.49%   |
| IBM 264070A       | 1         | 1.49%   |
| HP ZBook          | 1         | 1.49%   |
| HP ProBook        | 1         | 1.49%   |
| HP Pavilion       | 1         | 1.49%   |
| HP Mini           | 1         | 1.49%   |
| HP Laptop         | 1         | 1.49%   |
| HP ENVY           | 1         | 1.49%   |
| HP Compaq         | 1         | 1.49%   |
| Haier U144S       | 1         | 1.49%   |
| Google Samus      | 1         | 1.49%   |
| Google Leona      | 1         | 1.49%   |
| Google Kefka      | 1         | 1.49%   |
| Gateway MX3631m   | 1         | 1.49%   |
| Fujitsu LIFEBOOK  | 1         | 1.49%   |
| Fujitsu FMVNP8AE  | 1         | 1.49%   |
| Dell XPS          | 1         | 1.49%   |
| Dell Studio       | 1         | 1.49%   |
| Dell Latitude     | 1         | 1.49%   |
| ASUS ZenBook      | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2014    | 7         | 10.45%  |
| 2019    | 6         | 8.96%   |
| 2018    | 6         | 8.96%   |
| 2012    | 6         | 8.96%   |
| 2006    | 6         | 8.96%   |
| 2010    | 5         | 7.46%   |
| 2021    | 3         | 4.48%   |
| 2017    | 3         | 4.48%   |
| 2016    | 3         | 4.48%   |
| 2013    | 3         | 4.48%   |
| 2011    | 3         | 4.48%   |
| Unknown | 3         | 4.48%   |
| 2020    | 2         | 2.99%   |
| 2015    | 2         | 2.99%   |
| 2009    | 2         | 2.99%   |
| 2005    | 2         | 2.99%   |
| 2023    | 1         | 1.49%   |
| 2022    | 1         | 1.49%   |
| 2008    | 1         | 1.49%   |
| 2007    | 1         | 1.49%   |
| 1999    | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 67        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 95.52%  |
| Yes  | 3         | 4.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 18        | 25.35%  |
| 3.01-4.0        | 14        | 19.72%  |
| 8.01-16.0       | 8         | 11.27%  |
| 1.01-2.0        | 7         | 9.86%   |
| 16.01-24.0      | 6         | 8.45%   |
| 0.51-1.0        | 6         | 8.45%   |
| 32.01-64.0      | 5         | 7.04%   |
| 2.01-3.0        | 3         | 4.23%   |
| 0.01-0.5        | 2         | 2.82%   |
| More than 256.0 | 1         | 1.41%   |
| 64.01-256.0     | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 23        | 31.94%  |
| 1.01-2.0  | 14        | 19.44%  |
| 0.51-1.0  | 11        | 15.28%  |
| 2.01-3.0  | 9         | 12.5%   |
| 4.01-8.0  | 6         | 8.33%   |
| 3.01-4.0  | 4         | 5.56%   |
| 8.01-16.0 | 2         | 2.78%   |
| 0         | 2         | 2.78%   |
| Unknown   | 1         | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 74.29%  |
| 2      | 15        | 21.43%  |
| 0      | 2         | 2.86%   |
| 7      | 1         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 68.12%  |
| Yes       | 22        | 31.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 79.1%   |
| No        | 14        | 20.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 86.96%  |
| No        | 9         | 13.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 57.97%  |
| No        | 29        | 42.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 17        | 23.94%  |
| Canada       | 9         | 12.68%  |
| Russia       | 6         | 8.45%   |
| UK           | 5         | 7.04%   |
| Spain        | 4         | 5.63%   |
| Germany      | 4         | 5.63%   |
| Brazil       | 3         | 4.23%   |
| Italy        | 2         | 2.82%   |
| Australia    | 2         | 2.82%   |
| Venezuela    | 1         | 1.41%   |
| UAE          | 1         | 1.41%   |
| South Korea  | 1         | 1.41%   |
| South Africa | 1         | 1.41%   |
| Slovakia     | 1         | 1.41%   |
| Portugal     | 1         | 1.41%   |
| Poland       | 1         | 1.41%   |
| Netherlands  | 1         | 1.41%   |
| Mexico       | 1         | 1.41%   |
| Kenya        | 1         | 1.41%   |
| Jamaica      | 1         | 1.41%   |
| Israel       | 1         | 1.41%   |
| Hungary      | 1         | 1.41%   |
| Guatemala    | 1         | 1.41%   |
| Greece       | 1         | 1.41%   |
| France       | 1         | 1.41%   |
| Egypt        | 1         | 1.41%   |
| Czechia      | 1         | 1.41%   |
| China        | 1         | 1.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Vernon               | 3         | 4.17%   |
| St Petersburg        | 3         | 4.17%   |
| Springfield          | 3         | 4.17%   |
| Stratford            | 2         | 2.78%   |
| Moscow               | 2         | 2.78%   |
| Manitowoc            | 2         | 2.78%   |
| Fulham               | 2         | 2.78%   |
| Zhangzhou            | 1         | 1.39%   |
| Tymovskoye           | 1         | 1.39%   |
| Turin                | 1         | 1.39%   |
| Thornhill            | 1         | 1.39%   |
| Tampa                | 1         | 1.39%   |
| Sydney               | 1         | 1.39%   |
| Stewartstown         | 1         | 1.39%   |
| Sisteron             | 1         | 1.39%   |
| Semily               | 1         | 1.39%   |
| Seattle              | 1         | 1.39%   |
| Sao Paulo            | 1         | 1.39%   |
| San Mateo            | 1         | 1.39%   |
| Saarbrücken         | 1         | 1.39%   |
| Rzeszów             | 1         | 1.39%   |
| Rostock              | 1         | 1.39%   |
| Purdys               | 1         | 1.39%   |
| Oakville             | 1         | 1.39%   |
| Northampton          | 1         | 1.39%   |
| Nairobi              | 1         | 1.39%   |
| Montreal             | 1         | 1.39%   |
| Merrill              | 1         | 1.39%   |
| Mérida              | 1         | 1.39%   |
| Madrid               | 1         | 1.39%   |
| Lindavista Norte     | 1         | 1.39%   |
| Lincoln              | 1         | 1.39%   |
| Leipzig              | 1         | 1.39%   |
| Larkspur             | 1         | 1.39%   |
| Kingston             | 1         | 1.39%   |
| Kecskemét           | 1         | 1.39%   |
| Johannesburg         | 1         | 1.39%   |
| Jerez de la Frontera | 1         | 1.39%   |
| Heraklion            | 1         | 1.39%   |
| Hampstead            | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 11        | 15     | 12.5%   |
| Unknown                     | 8         | 10     | 9.09%   |
| Toshiba                     | 8         | 10     | 9.09%   |
| Hitachi                     | 8         | 8      | 9.09%   |
| Kingston                    | 7         | 9      | 7.95%   |
| WDC                         | 6         | 8      | 6.82%   |
| Seagate                     | 5         | 16     | 5.68%   |
| HGST                        | 5         | 5      | 5.68%   |
| SanDisk                     | 3         | 3      | 3.41%   |
| Intel                       | 3         | 5      | 3.41%   |
| Crucial                     | 3         | 3      | 3.41%   |
| SPCC                        | 2         | 2      | 2.27%   |
| SK hynix                    | 2         | 2      | 2.27%   |
| Fujitsu                     | 2         | 2      | 2.27%   |
| A-DATA Technology           | 2         | 3      | 2.27%   |
| SINTECHI                    | 1         | 1      | 1.14%   |
| Secure                      | 1         | 1      | 1.14%   |
| Micron Technology           | 1         | 1      | 1.14%   |
| LITEON                      | 1         | 1      | 1.14%   |
| Kingston Technology Company | 1         | 1      | 1.14%   |
| KC600                       | 1         | 1      | 1.14%   |
| JMicron Technology          | 1         | 1      | 1.14%   |
| Intenso                     | 1         | 1      | 1.14%   |
| IBM                         | 1         | 1      | 1.14%   |
| Emtec                       | 1         | 1      | 1.14%   |
| Dell                        | 1         | 2      | 1.14%   |
| China                       | 1         | 1      | 1.14%   |
| AMD                         | 1         | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                       | 3         | 3%      |
| Unknown MMC Card  64GB                       | 2         | 2%      |
| Toshiba MQ01ABD100 1TB                       | 2         | 2%      |
| Toshiba MQ01ABD075 752GB                     | 2         | 2%      |
| Samsung NVMe SSD Drive 1024GB                | 2         | 2%      |
| Kingston SV300S37A120G 120GB SSD             | 2         | 2%      |
| Crucial CT500MX500SSD1 500GB                 | 2         | 2%      |
| WDC WDS500G2X0C-00L350 500GB                 | 1         | 1%      |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1%      |
| WDC WDS500G2B0A 500GB SSD                    | 1         | 1%      |
| WDC WDS250G2B0A 250GB SSD                    | 1         | 1%      |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1%      |
| WDC WD5000BEVT-22ZAT0 500GB                  | 1         | 1%      |
| WDC PC SN520 SDAPNUW-512G-1002 512GB         | 1         | 1%      |
| Unknown SD32G  32GB                          | 1         | 1%      |
| Unknown NVMe SSD Drive 1024GB                | 1         | 1%      |
| Unknown MMC Card  32GB                       | 1         | 1%      |
| Unknown MMC Card                             | 1         | 1%      |
| Toshiba MQ01ABD1 1TB                         | 1         | 1%      |
| Toshiba MK6008GAH 64GB                       | 1         | 1%      |
| Toshiba MK4009GAL 40GB                       | 1         | 1%      |
| Toshiba KXG5AZNV256G 256GB                   | 1         | 1%      |
| Toshiba KBG30ZMS128G 128GB NVMe SSD          | 1         | 1%      |
| Toshiba HDWL110 1TB                          | 1         | 1%      |
| SPCC Solid State Disk 256GB                  | 1         | 1%      |
| SPCC Solid State 120GB                       | 1         | 1%      |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB    | 1         | 1%      |
| SK hynix BC501 NVMe Solid State Drive 512GB  | 1         | 1%      |
| SINTECHI HighSpeed SD to CF Adapter V1.0     | 1         | 1%      |
| Secure Net 256GB SSD                         | 1         | 1%      |
| Seagate ST98823A 80GB                        | 1         | 1%      |
| Seagate ST9160314AS 160GB                    | 1         | 1%      |
| Seagate ST8000VN004-2M2101 8TB               | 1         | 1%      |
| Seagate ST6000DM003-2CY1 6TB                 | 1         | 1%      |
| Seagate ST4000DM004-2U91 4TB                 | 1         | 1%      |
| Seagate ST2000LM015-2E81 2TB                 | 1         | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1%      |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 1%      |
| SanDisk SSD PLUS 480GB                       | 1         | 1%      |
| SanDisk NVMe SSD Drive 512GB                 | 1         | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 8         | 8      | 25.81%  |
| Toshiba             | 7         | 8      | 22.58%  |
| Seagate             | 5         | 16     | 16.13%  |
| HGST                | 5         | 5      | 16.13%  |
| Fujitsu             | 2         | 2      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| SINTECHI            | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 2      | 3.23%   |
| IBM                 | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 20%     |
| WDC                 | 3         | 4      | 10%     |
| Samsung Electronics | 3         | 3      | 10%     |
| Crucial             | 3         | 3      | 10%     |
| SPCC                | 2         | 2      | 6.67%   |
| Secure              | 1         | 1      | 3.33%   |
| SanDisk             | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| KC600               | 1         | 1      | 3.33%   |
| JMicron Technology  | 1         | 1      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| Emtec               | 1         | 1      | 3.33%   |
| Dell                | 1         | 2      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| AMD                 | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 44     | 40%     |
| SSD  | 23        | 33     | 30.67%  |
| NVMe | 15        | 30     | 20%     |
| MMC  | 7         | 8      | 9.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 74     | 66.22%  |
| NVMe | 15        | 30     | 20.27%  |
| MMC  | 7         | 8      | 9.46%   |
| SAS  | 3         | 3      | 4.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 52     | 72.73%  |
| 0.51-1.0   | 11        | 12     | 20%     |
| 4.01-10.0  | 2         | 11     | 3.64%   |
| 3.01-4.0   | 1         | 1      | 1.82%   |
| 1.01-2.0   | 1         | 1      | 1.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 23.94%  |
| 1-20           | 15        | 21.13%  |
| Unknown        | 9         | 12.68%  |
| 251-500        | 8         | 11.27%  |
| 21-50          | 6         | 8.45%   |
| 501-1000       | 5         | 7.04%   |
| 1001-2000      | 4         | 5.63%   |
| 51-100         | 3         | 4.23%   |
| More than 3000 | 2         | 2.82%   |
| 2001-3000      | 2         | 2.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 46        | 64.79%  |
| Unknown  | 9         | 12.68%  |
| 21-50    | 4         | 5.63%   |
| 51-100   | 4         | 5.63%   |
| 251-500  | 3         | 4.23%   |
| 101-250  | 3         | 4.23%   |
| 501-1000 | 2         | 2.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 8.33%   |
| Secure Net 256GB SSD                           | 1         | 1      | 8.33%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 8.33%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 8.33%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 8.33%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 8.33%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 8.33%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 8.33%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 8.33%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 8.33%   |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 33.33%  |
| HGST                | 2         | 2      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| Secure              | 1         | 1      | 8.33%   |
| Seagate             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 2      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 44.44%  |
| HGST                | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Seagate             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 75%     |
| SSD  | 2         | 2      | 16.67%  |
| NVMe | 1         | 1      | 8.33%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 42        | 76     | 56.76%  |
| Detected | 21        | 26     | 28.38%  |
| Malfunc  | 11        | 13     | 14.86%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 47        | 60.26%  |
| AMD                          | 10        | 12.82%  |
| Samsung Electronics          | 8         | 10.26%  |
| SanDisk                      | 4         | 5.13%   |
| SK hynix                     | 2         | 2.56%   |
| ADATA Technology             | 2         | 2.56%   |
| Toshiba America Info Systems | 1         | 1.28%   |
| Nvidia                       | 1         | 1.28%   |
| Marvell Technology Group     | 1         | 1.28%   |
| Kingston Technology Company  | 1         | 1.28%   |
| Broadcom / LSI               | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 9.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 5.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 4.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 3.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 3.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 3.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 3.23%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 3.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 3.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 2.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.15%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.15%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 1.08%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 1.08%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.08%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.08%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.08%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.08%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.08%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.08%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.08%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.08%   |
| Kingston Company KC3000/Renegade NVMe SSD                                      | 1         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.08%   |
| Intel SSD 600P Series                                                          | 1         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.08%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.08%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1         | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 42        | 57.53%  |
| NVMe | 15        | 20.55%  |
| IDE  | 12        | 16.44%  |
| RAID | 4         | 5.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 79.71%  |
| AMD    | 12        | 17.39%  |
| ARM    | 2         | 2.9%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz    | 2         | 2.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 2         | 2.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz    | 2         | 2.82%   |
| Intel Atom CPU N455 @ 1.66GHz        | 2         | 2.82%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz   | 1         | 1.41%   |
| Intel Xeon E-2176M CPU @ 2.70GHz     | 1         | 1.41%   |
| Intel Pentium M processor 1.60GHz    | 1         | 1.41%   |
| Intel Pentium M processor 1.50GHz    | 1         | 1.41%   |
| Intel Pentium III (Coppermine)       | 1         | 1.41%   |
| Intel Pentium CPU N4200 @ 1.10GHz    | 1         | 1.41%   |
| Intel Pentium CPU N3710 @ 1.60GHz    | 1         | 1.41%   |
| Intel Mobile Pentium MMX             | 1         | 1.41%   |
| Intel Genuine CPU T2400 @ 1.83GHz    | 1         | 1.41%   |
| Intel Core Solo CPU U1500 @ 1.33GHz  | 1         | 1.41%   |
| Intel Core m3-8100Y CPU @ 1.10GHz    | 1         | 1.41%   |
| Intel Core i9-9980HK CPU @ 2.40GHz   | 1         | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz    | 1         | 1.41%   |
| Intel Core i7-5500U CPU @ 2.40GHz    | 1         | 1.41%   |
| Intel Core i7-10610U CPU @ 1.80GHz   | 1         | 1.41%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz    | 1         | 1.41%   |
| Intel Core i5-8350U CPU @ 1.70GHz    | 1         | 1.41%   |
| Intel Core i5-8300H CPU @ 2.30GHz    | 1         | 1.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 1         | 1.41%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz   | 1         | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 1         | 1.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 1         | 1.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 1         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.41%   |
| Intel Core i5-4200M CPU @ 2.50GHz    | 1         | 1.41%   |
| Intel Core i5-3340M CPU @ 2.70GHz    | 1         | 1.41%   |
| Intel Core i5-3317U CPU @ 1.70GHz    | 1         | 1.41%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz   | 1         | 1.41%   |
| Intel Core i5 CPU M 560 @ 2.67GHz    | 1         | 1.41%   |
| Intel Core i5 CPU M 480 @ 2.67GHz    | 1         | 1.41%   |
| Intel Core i3-5020U CPU @ 2.20GHz    | 1         | 1.41%   |
| Intel Core i3-3110M CPU @ 2.40GHz    | 1         | 1.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz    | 1         | 1.41%   |
| Intel Core i3 CPU M 350 @ 2.27GHz    | 1         | 1.41%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz | 1         | 1.41%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 16        | 22.54%  |
| Other                | 7         | 9.86%   |
| Intel Celeron        | 6         | 8.45%   |
| Intel Atom           | 5         | 7.04%   |
| Intel Pentium M      | 4         | 5.63%   |
| Intel Core i7        | 4         | 5.63%   |
| Intel Core i3        | 4         | 5.63%   |
| Intel Core 2 Duo     | 3         | 4.23%   |
| Intel Pentium        | 2         | 2.82%   |
| AMD Ryzen 5          | 2         | 2.82%   |
| AMD A4               | 2         | 2.82%   |
| Intel Xeon Gold      | 1         | 1.41%   |
| Intel Xeon           | 1         | 1.41%   |
| Intel Pentium III    | 1         | 1.41%   |
| Intel Genuine        | 1         | 1.41%   |
| Intel Core Solo      | 1         | 1.41%   |
| Intel Core m3        | 1         | 1.41%   |
| Intel Core i9        | 1         | 1.41%   |
| Intel Core 2         | 1         | 1.41%   |
| ARM ARMv7            | 1         | 1.41%   |
| AMD Turion 64 Mobile | 1         | 1.41%   |
| AMD Ryzen 7          | 1         | 1.41%   |
| AMD Ryzen 3          | 1         | 1.41%   |
| AMD FX               | 1         | 1.41%   |
| AMD E2               | 1         | 1.41%   |
| AMD A6               | 1         | 1.41%   |
| AMD A10              | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 33        | 47.14%  |
| 4       | 18        | 25.71%  |
| 1       | 11        | 15.71%  |
| 8       | 2         | 2.86%   |
| 32      | 1         | 1.43%   |
| 16      | 1         | 1.43%   |
| 14      | 1         | 1.43%   |
| 6       | 1         | 1.43%   |
| 3       | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 66        | 97.06%  |
| 2       | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 34        | 50.75%  |
| 2       | 32        | 47.76%  |
| Unknown | 1         | 1.49%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 38        | 55.07%  |
| 32-bit, 64-bit | 28        | 40.58%  |
| 32-bit         | 3         | 4.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 56.94%  |
| 0x306a9    | 3         | 4.17%   |
| 0x30678    | 3         | 4.17%   |
| 0x906ea    | 2         | 2.78%   |
| 0x806eb    | 2         | 2.78%   |
| 0x206a7    | 2         | 2.78%   |
| 0x106ca    | 2         | 2.78%   |
| 0x06006704 | 2         | 2.78%   |
| 0x906a3    | 1         | 1.39%   |
| 0x806ec    | 1         | 1.39%   |
| 0x806c1    | 1         | 1.39%   |
| 0x706e5    | 1         | 1.39%   |
| 0x683      | 1         | 1.39%   |
| 0x506c9    | 1         | 1.39%   |
| 0x406c4    | 1         | 1.39%   |
| 0x306d4    | 1         | 1.39%   |
| 0x306c3    | 1         | 1.39%   |
| 0x20655    | 1         | 1.39%   |
| 0x106e5    | 1         | 1.39%   |
| 0x1067a    | 1         | 1.39%   |
| 0x08108109 | 1         | 1.39%   |
| 0x08108102 | 1         | 1.39%   |
| 0x0810100b | 1         | 1.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 14.08%  |
| P6               | 7         | 9.86%   |
| Silvermont       | 6         | 8.45%   |
| Goldmont         | 4         | 5.63%   |
| Unknown          | 4         | 5.63%   |
| Westmere         | 3         | 4.23%   |
| SandyBridge      | 3         | 4.23%   |
| Penryn           | 3         | 4.23%   |
| IvyBridge        | 3         | 4.23%   |
| Excavator        | 3         | 4.23%   |
| Broadwell        | 3         | 4.23%   |
| Bonnell          | 3         | 4.23%   |
| Zen+             | 2         | 2.82%   |
| TigerLake        | 2         | 2.82%   |
| Skylake          | 2         | 2.82%   |
| Haswell          | 2         | 2.82%   |
| Zen 2            | 1         | 1.41%   |
| Zen              | 1         | 1.41%   |
| Puma             | 1         | 1.41%   |
| Piledriver       | 1         | 1.41%   |
| Nehalem          | 1         | 1.41%   |
| K8 Hammer        | 1         | 1.41%   |
| Jaguar           | 1         | 1.41%   |
| IceLake          | 1         | 1.41%   |
| Core             | 1         | 1.41%   |
| Bobcat           | 1         | 1.41%   |
| Alderlake Hybrid | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 49        | 62.82%  |
| AMD                        | 18        | 23.08%  |
| Nvidia                     | 8         | 10.26%  |
| Neomagic                   | 2         | 2.56%   |
| Matrox Electronics Systems | 1         | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 4.26%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 3.19%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 3.19%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.19%   |
| Intel HD Graphics 500                                                                    | 3         | 3.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.13%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.13%   |
| Intel HD Graphics 630                                                                    | 2         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.13%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.13%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 2.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.06%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.06%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.06%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.06%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.06%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.06%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.06%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.06%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 1.06%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.06%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1         | 1.06%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.06%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.06%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.06%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.06%   |
| Intel UHD Graphics 615                                                                   | 1         | 1.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.06%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 35        | 49.3%   |
| 1 x AMD         | 13        | 18.31%  |
| 2 x Intel       | 6         | 8.45%   |
| Intel + Nvidia  | 6         | 8.45%   |
| Intel + AMD     | 3         | 4.23%   |
| Other           | 2         | 2.82%   |
| 1 x Neomagic    | 2         | 2.82%   |
| 2 x AMD         | 1         | 1.41%   |
| Nvidia + Matrox | 1         | 1.41%   |
| 1 x Nvidia      | 1         | 1.41%   |
| AMD + Nvidia    | 1         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 88.57%  |
| Unknown     | 5         | 7.14%   |
| Proprietary | 3         | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 88.24%  |
| 0.01-0.5   | 4         | 5.88%   |
| 1.01-2.0   | 2         | 2.94%   |
| 2.01-3.0   | 1         | 1.47%   |
| 0.51-1.0   | 1         | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 19.72%  |
| LG Display              | 10        | 14.08%  |
| BOE                     | 8         | 11.27%  |
| Chimei Innolux          | 7         | 9.86%   |
| Samsung Electronics     | 4         | 5.63%   |
| LG Philips              | 3         | 4.23%   |
| InfoVision              | 3         | 4.23%   |
| Chi Mei Optoelectronics | 3         | 4.23%   |
| Lenovo                  | 2         | 2.82%   |
| Goldstar                | 2         | 2.82%   |
| Sharp                   | 1         | 1.41%   |
| Quanta Display          | 1         | 1.41%   |
| Philips                 | 1         | 1.41%   |
| PANDA                   | 1         | 1.41%   |
| ONN                     | 1         | 1.41%   |
| KVM                     | 1         | 1.41%   |
| HannStar                | 1         | 1.41%   |
| Envision                | 1         | 1.41%   |
| Element                 | 1         | 1.41%   |
| DENON                   | 1         | 1.41%   |
| Dell                    | 1         | 1.41%   |
| CSO                     | 1         | 1.41%   |
| CPT                     | 1         | 1.41%   |
| BenQ                    | 1         | 1.41%   |
| Acer                    | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 2.56%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 1.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 1.28%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 1.28%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 1.28%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 1.28%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 1         | 1.28%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 1.28%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 1.28%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.28%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 1.28%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 1.28%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 1.28%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 1.28%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.28%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 1.28%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch          | 1         | 1.28%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.28%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch           | 1         | 1.28%   |
| InfoVision LCD Monitor IVO0489 1366x768 344x193mm 15.5-inch           | 1         | 1.28%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.28%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 1.28%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 1         | 1.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.28%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                 | 1         | 1.28%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1         | 1.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.28%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch            | 1         | 1.28%   |
| Element ELCFW329 ELE1366 1366x768 700x390mm 31.5-inch                 | 1         | 1.28%   |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                      | 1         | 1.28%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 1         | 1.28%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 1         | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 26        | 37.14%  |
| 1920x1080 (FHD)   | 14        | 20%     |
| 1280x800 (WXGA)   | 6         | 8.57%   |
| 3840x2160 (4K)    | 3         | 4.29%   |
| 1600x900 (HD+)    | 3         | 4.29%   |
| 1024x600          | 3         | 4.29%   |
| 2560x1440 (QHD)   | 2         | 2.86%   |
| 2560x1080         | 2         | 2.86%   |
| 1920x1200 (WUXGA) | 2         | 2.86%   |
| 1280x768          | 2         | 2.86%   |
| 1280x1024 (SXGA)  | 2         | 2.86%   |
| 3440x1440         | 1         | 1.43%   |
| 2880x1800         | 1         | 1.43%   |
| 2560x1700         | 1         | 1.43%   |
| 1360x768          | 1         | 1.43%   |
| 1024x768 (XGA)    | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 23        | 31.51%  |
| 14     | 12        | 16.44%  |
| 13     | 8         | 10.96%  |
| 11     | 5         | 6.85%   |
| 17     | 4         | 5.48%   |
| 12     | 4         | 5.48%   |
| 10     | 3         | 4.11%   |
| 72     | 1         | 1.37%   |
| 60     | 1         | 1.37%   |
| 34     | 1         | 1.37%   |
| 32     | 1         | 1.37%   |
| 31     | 1         | 1.37%   |
| 29     | 1         | 1.37%   |
| 27     | 1         | 1.37%   |
| 25     | 1         | 1.37%   |
| 24     | 1         | 1.37%   |
| 23     | 1         | 1.37%   |
| 21     | 1         | 1.37%   |
| 20     | 1         | 1.37%   |
| 19     | 1         | 1.37%   |
| 16     | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 60.29%  |
| 201-300     | 14        | 20.59%  |
| 351-400     | 4         | 5.88%   |
| 601-700     | 3         | 4.41%   |
| 701-800     | 2         | 2.94%   |
| 501-600     | 1         | 1.47%   |
| 401-500     | 1         | 1.47%   |
| 1501-2000   | 1         | 1.47%   |
| 1001-1500   | 1         | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 48        | 76.19%  |
| 16/10 | 9         | 14.29%  |
| 5/4   | 2         | 3.17%   |
| 21/9  | 2         | 3.17%   |
| 4/3   | 1         | 1.59%   |
| 3/2   | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 33.33%  |
| 81-90          | 18        | 26.09%  |
| 51-60          | 5         | 7.25%   |
| 71-80          | 3         | 4.35%   |
| 61-70          | 3         | 4.35%   |
| 351-500        | 3         | 4.35%   |
| 41-50          | 3         | 4.35%   |
| More than 1000 | 2         | 2.9%    |
| 301-350        | 2         | 2.9%    |
| 121-130        | 2         | 2.9%    |
| 251-300        | 1         | 1.45%   |
| 201-250        | 1         | 1.45%   |
| 151-200        | 1         | 1.45%   |
| 141-150        | 1         | 1.45%   |
| 131-140        | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 24        | 37.5%   |
| 121-160       | 23        | 35.94%  |
| 51-100        | 10        | 15.63%  |
| 1-50          | 3         | 4.69%   |
| More than 240 | 2         | 3.13%   |
| 161-240       | 2         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 80%     |
| 0     | 7         | 10%     |
| 2     | 6         | 8.57%   |
| 3     | 1         | 1.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 39        | 34.51%  |
| Intel                           | 34        | 30.09%  |
| Qualcomm Atheros                | 16        | 14.16%  |
| Broadcom                        | 9         | 7.96%   |
| Marvell Technology Group        | 3         | 2.65%   |
| LSI                             | 2         | 1.77%   |
| Broadcom Limited                | 2         | 1.77%   |
| Qualcomm Atheros Communications | 1         | 0.88%   |
| Qualcomm                        | 1         | 0.88%   |
| MediaTek                        | 1         | 0.88%   |
| Google                          | 1         | 0.88%   |
| Dresden Elektronik              | 1         | 0.88%   |
| DisplayLink                     | 1         | 0.88%   |
| ASIX Electronics                | 1         | 0.88%   |
| AMD                             | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 19        | 13.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 7.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 8         | 5.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.45%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.45%   |
| Intel Wireless 7265                                                            | 2         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.45%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 1.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 2         | 1.45%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 0.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.72%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.72%   |
| Qualcomm POCO M2 Pro                                                           | 1         | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.72%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.72%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.72%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 0.72%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.72%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.72%   |
| LSI WinModem 56k                                                               | 1         | 0.72%   |
| LSI ET-131x PCI-E Ethernet Controller                                          | 1         | 0.72%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 46.88%  |
| Qualcomm Atheros                | 15        | 23.44%  |
| Realtek Semiconductor           | 7         | 10.94%  |
| Broadcom                        | 7         | 10.94%  |
| Broadcom Limited                | 2         | 3.13%   |
| Qualcomm Atheros Communications | 1         | 1.56%   |
| MediaTek                        | 1         | 1.56%   |
| Marvell Technology Group        | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 8         | 12.31%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 4.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 3.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 3.08%   |
| Intel Wireless-AC 9260                                                         | 2         | 3.08%   |
| Intel Wireless 7265                                                            | 2         | 3.08%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 3.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 3.08%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 3.08%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 3.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 1.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.54%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 1.54%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.54%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.54%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.54%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.54%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.54%   |
| Intel Wireless 8260                                                            | 1         | 1.54%   |
| Intel Wireless 7260                                                            | 1         | 1.54%   |
| Intel Wireless 3160                                                            | 1         | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.54%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 1.54%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 1         | 1.54%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.54%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 1.54%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.54%   |
| Intel Centrino Wireless-N 100                                                  | 1         | 1.54%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 1         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 35        | 57.38%  |
| Intel                    | 14        | 22.95%  |
| Broadcom                 | 4         | 6.56%   |
| Qualcomm Atheros         | 2         | 3.28%   |
| Marvell Technology Group | 2         | 3.28%   |
| Qualcomm                 | 1         | 1.64%   |
| LSI                      | 1         | 1.64%   |
| DisplayLink              | 1         | 1.64%   |
| ASIX Electronics         | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 19        | 28.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 10        | 15.15%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 4         | 6.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 3         | 4.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 2         | 3.03%   |
| Intel 82579V Gigabit Network Connection                               | 2         | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2         | 3.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                                 | 1         | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                     | 1         | 1.52%   |
| Qualcomm POCO M2 Pro                                                  | 1         | 1.52%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller               | 1         | 1.52%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                  | 1         | 1.52%   |
| LSI ET-131x PCI-E Ethernet Controller                                 | 1         | 1.52%   |
| Intel WiMAX Connection 2400m                                          | 1         | 1.52%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection (17) I219-LM                                | 1         | 1.52%   |
| Intel Ethernet Connection (13) I219-LM                                | 1         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.52%   |
| Intel 82567LM Gigabit Network Connection                              | 1         | 1.52%   |
| Intel 82541GI Gigabit Ethernet Controller                             | 1         | 1.52%   |
| DisplayLink Dell D3100 Docking Station                                | 1         | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                     | 1         | 1.52%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                 | 1         | 1.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                | 1         | 1.52%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.52%   |
| Broadcom BCM4401-B0 100Base-TX                                        | 1         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 50.42%  |
| Ethernet | 52        | 43.7%   |
| Modem    | 7         | 5.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 65.67%  |
| Ethernet | 23        | 34.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 69.12%  |
| 1     | 16        | 23.53%  |
| 0     | 5         | 7.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 86.76%  |
| Yes  | 9         | 13.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 37.78%  |
| Qualcomm Atheros Communications | 4         | 8.89%   |
| IMC Networks                    | 4         | 8.89%   |
| Broadcom                        | 4         | 8.89%   |
| Realtek Semiconductor           | 3         | 6.67%   |
| Lite-On Technology              | 3         | 6.67%   |
| Foxconn / Hon Hai               | 2         | 4.44%   |
| Toshiba                         | 1         | 2.22%   |
| Marvell Semiconductor           | 1         | 2.22%   |
| Hewlett-Packard                 | 1         | 2.22%   |
| Edimax Technology               | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |
| ASUSTek Computer                | 1         | 2.22%   |
| Apple                           | 1         | 2.22%   |
| Alps Electric                   | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8.89%   |
| Realtek Bluetooth Radio                             | 2         | 4.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 4.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4.44%   |
| Intel AX201 Bluetooth                               | 2         | 4.44%   |
| Intel AX200 Bluetooth                               | 2         | 4.44%   |
| Toshiba Bluetooth Device                            | 1         | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.22%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.22%   |
| Intel AX210 Bluetooth                               | 1         | 2.22%   |
| IMC Networks Wireless_Device                        | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.22%   |
| IMC Networks Bluetooth Device                       | 1         | 2.22%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.22%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.22%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 2.22%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 2.22%   |
| Edimax Bluetooth Adapter                            | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.22%   |
| Broadcom BCM20702A0                                 | 1         | 2.22%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.22%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.22%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.22%   |
| Apple Bluetooth Host Controller                     | 1         | 2.22%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 51        | 69.86%  |
| AMD                       | 14        | 19.18%  |
| Nvidia                    | 3         | 4.11%   |
| Texas Instruments         | 1         | 1.37%   |
| Sennheiser Communications | 1         | 1.37%   |
| Realtek Semiconductor     | 1         | 1.37%   |
| Logitech                  | 1         | 1.37%   |
| Cirrus Logic              | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 5.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.95%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 3.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 3.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.96%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 2.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.97%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 2.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.98%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.98%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.98%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.98%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.99%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 0.99%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.99%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Nvidia Audio device                                                                               | 1         | 0.99%   |
| Nvidia AD102 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Logitech PRO                                                                                      | 1         | 0.99%   |
| Logitech G935 Gaming Headset                                                                      | 1         | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 23.08%  |
| Unknown             | 13        | 20%     |
| SK hynix            | 11        | 16.92%  |
| Micron Technology   | 6         | 9.23%   |
| Elpida              | 5         | 7.69%   |
| Crucial             | 5         | 7.69%   |
| Kingston            | 3         | 4.62%   |
| A-DATA Technology   | 2         | 3.08%   |
| Unknown (ABCD)      | 1         | 1.54%   |
| Ramaxel Technology  | 1         | 1.54%   |
| Nanya Technology    | 1         | 1.54%   |
| Gold Key            | 1         | 1.54%   |
| Corsair             | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 3.85%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 2.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.56%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 2.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.56%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.28%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.28%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.28%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 1.28%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.28%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.28%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.28%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.28%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 1.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.28%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.28%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.28%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.28%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s            | 1         | 1.28%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.28%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 1.28%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.28%   |
| Samsung RAM K4E6E304EC-EGCF 4096MB LPDDR3 1867MT/s               | 1         | 1.28%   |
| Ramaxel RAM RMT3170EB68E9W160 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 23        | 41.07%  |
| DDR4   | 14        | 25%     |
| LPDDR3 | 5         | 8.93%   |
| DDR    | 4         | 7.14%   |
| SDRAM  | 3         | 5.36%   |
| LPDDR4 | 2         | 3.57%   |
| DRAM   | 2         | 3.57%   |
| DDR2   | 2         | 3.57%   |
| DDR5   | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 84.21%  |
| Row Of Chips | 5         | 8.77%   |
| DIMM         | 2         | 3.51%   |
| Unknown      | 2         | 3.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 20        | 31.25%  |
| 8192  | 19        | 29.69%  |
| 2048  | 9         | 14.06%  |
| 1024  | 6         | 9.38%   |
| 512   | 5         | 7.81%   |
| 16384 | 2         | 3.13%   |
| 32768 | 1         | 1.56%   |
| 256   | 1         | 1.56%   |
| 128   | 1         | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 19.7%   |
| Unknown | 9         | 13.64%  |
| 1334    | 7         | 10.61%  |
| 2400    | 6         | 9.09%   |
| 3200    | 5         | 7.58%   |
| 2667    | 5         | 7.58%   |
| 2133    | 4         | 6.06%   |
| 1867    | 3         | 4.55%   |
| 1333    | 3         | 4.55%   |
| 1067    | 2         | 3.03%   |
| 8400    | 1         | 1.52%   |
| 4800    | 1         | 1.52%   |
| 4199    | 1         | 1.52%   |
| 3266    | 1         | 1.52%   |
| 3000    | 1         | 1.52%   |
| 1400    | 1         | 1.52%   |
| 1200    | 1         | 1.52%   |
| 1066    | 1         | 1.52%   |
| 533     | 1         | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1020 | 1         | 50%     |
| HP Deskjet 3050A | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 22.81%  |
| Realtek Semiconductor                  | 7         | 12.28%  |
| Microdia                               | 6         | 10.53%  |
| IMC Networks                           | 5         | 8.77%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.02%   |
| Suyin                                  | 3         | 5.26%   |
| Quanta                                 | 3         | 5.26%   |
| Bison Electronics                      | 3         | 5.26%   |
| Sunplus Innovation Technology          | 2         | 3.51%   |
| Trust                                  | 1         | 1.75%   |
| Syntek                                 | 1         | 1.75%   |
| Silicon Motion                         | 1         | 1.75%   |
| Samsung Electronics                    | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| Luxvisions Innotech Limited            | 1         | 1.75%   |
| Logitech                               | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Lenovo                                 | 1         | 1.75%   |
| Apple                                  | 1         | 1.75%   |
| Acer                                   | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                  | 3         | 5.17%   |
| IMC Networks Integrated Camera                                | 3         | 5.17%   |
| Chicony HD Webcam                                             | 3         | 5.17%   |
| Realtek Acer 640 x 480 laptop camera                          | 2         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_2M                          | 2         | 3.45%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 3.45%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 2         | 3.45%   |
| Chicony Integrated Camera                                     | 2         | 3.45%   |
| Trust QHD Webcam                                              | 1         | 1.72%   |
| Syntek EasyCamera                                             | 1         | 1.72%   |
| Suyin Integrated_Webcam_HD                                    | 1         | 1.72%   |
| Suyin HP TrueVision HD                                        | 1         | 1.72%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.72%   |
| Sunplus HP Universal Camera                                   | 1         | 1.72%   |
| Sunplus HD WebCam                                             | 1         | 1.72%   |
| Silicon Motion NCM-G102                                       | 1         | 1.72%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 1         | 1.72%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870]           | 1         | 1.72%   |
| Realtek USB2.0 HD UVC WebCam                                  | 1         | 1.72%   |
| Realtek USB Camera                                            | 1         | 1.72%   |
| Quanta USB2.0 HD UVC WebCam                                   | 1         | 1.72%   |
| Quanta HP Wide Vision HD Camera                               | 1         | 1.72%   |
| Quanta HP TrueVision HD Camera                                | 1         | 1.72%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                | 1         | 1.72%   |
| Microdia Integrated Webcam                                    | 1         | 1.72%   |
| Luxvisions Innotech Limited HP HD Camera                      | 1         | 1.72%   |
| Logitech Webcam C270                                          | 1         | 1.72%   |
| Logitech Webcam C170                                          | 1         | 1.72%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 1.72%   |
| Lenovo Integrated Webcam                                      | 1         | 1.72%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 1.72%   |
| Chicony USB2.0 FHD UVC WebCam                                 | 1         | 1.72%   |
| Chicony Integrated Camera (1280x720@30)                       | 1         | 1.72%   |
| Chicony HP Webcam [2 MP Macro]                                | 1         | 1.72%   |
| Chicony HP HD Camera                                          | 1         | 1.72%   |
| Chicony CNF9055 Toshiba Webcam                                | 1         | 1.72%   |
| Chicony CNF8243 Webcam                                        | 1         | 1.72%   |
| Chicony 2.0M UVC Webcam / CNF7129                             | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                 | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Synaptics                  | 2         | 22.22%  |
| AuthenTec                  | 2         | 22.22%  |
| STMicroelectronics         | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 11.11%  |
| STMicroelectronics Fingerprint Reader                                      | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 39        | 53.42%  |
| 1     | 20        | 27.4%   |
| 2     | 10        | 13.7%   |
| 4     | 2         | 2.74%   |
| 3     | 2         | 2.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 21.15%  |
| Fingerprint reader       | 8         | 15.38%  |
| Modem                    | 7         | 13.46%  |
| Bluetooth                | 5         | 9.62%   |
| Communication controller | 4         | 7.69%   |
| Camera                   | 4         | 7.69%   |
| Net/wireless             | 3         | 5.77%   |
| Multimedia controller    | 2         | 3.85%   |
| Chipcard                 | 2         | 3.85%   |
| Unclassified device      | 1         | 1.92%   |
| Unassigned class         | 1         | 1.92%   |
| Storage                  | 1         | 1.92%   |
| Sound                    | 1         | 1.92%   |
| Network                  | 1         | 1.92%   |
| Card reader              | 1         | 1.92%   |

