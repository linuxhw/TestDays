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

Total: 95

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | V15 G3 IAP 82TT             | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Dell          | Latitude 3420               | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| ASUSTek       | 1001PX                      | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Apple         | MacBookAir5,2               | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Unknown       | Unknown                     | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| HP            | Presario V2000 (ES307UA#... | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
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
| Alpine 3.16.0               | 6         | 7.79%   |
| Alpine 3.15.0               | 6         | 7.79%   |
| Alpine 3.18.3               | 4         | 5.19%   |
| Alpine 3.15.0_alpha20210804 | 4         | 5.19%   |
| Alpine 3.14.0               | 4         | 5.19%   |
| Alpine 3.12.0               | 4         | 5.19%   |
| Alpine 3.18.0               | 3         | 3.9%    |
| Alpine 3.17.2               | 3         | 3.9%    |
| Alpine 3.17.0               | 3         | 3.9%    |
| Alpine 3.15.4               | 3         | 3.9%    |
| Alpine 3.19_alpha20230901   | 2         | 2.6%    |
| Alpine 3.18_alpha20230329   | 2         | 2.6%    |
| Alpine 3.18.4               | 2         | 2.6%    |
| Alpine 3.17.1               | 2         | 2.6%    |
| Alpine 3.16.2               | 2         | 2.6%    |
| Alpine 3.14.2               | 2         | 2.6%    |
| Alpine 3.13.5               | 2         | 2.6%    |
| Alpine 3.13.0_alpha20201218 | 2         | 2.6%    |
| Alpine 3.13.0_alpha20200917 | 2         | 2.6%    |
| Alpine 3.11.2               | 2         | 2.6%    |
| Alpine 3.19.0_rc2           | 1         | 1.3%    |
| Alpine 3.19.0               | 1         | 1.3%    |
| Alpine 3.18.2               | 1         | 1.3%    |
| Alpine 3.17_alpha20220809   | 1         | 1.3%    |
| Alpine 3.17.3               | 1         | 1.3%    |
| Alpine 3.16.3               | 1         | 1.3%    |
| Alpine 3.16.1               | 1         | 1.3%    |
| Alpine 3.16.0_alpha20220316 | 1         | 1.3%    |
| Alpine 3.15.2               | 1         | 1.3%    |
| Alpine 3.15.0_rc5           | 1         | 1.3%    |
| Alpine 3.14.0_alpha20210212 | 1         | 1.3%    |
| Alpine 3.13.1               | 1         | 1.3%    |
| Alpine 3.13.0_rc2           | 1         | 1.3%    |
| Alpine 3.13.0_alpha20200626 | 1         | 1.3%    |
| Alpine 3.12.3               | 1         | 1.3%    |
| Alpine 3.12.1               | 1         | 1.3%    |
| Alpine 3.11.5               | 1         | 1.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 73        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.1.62-0-lts           | 2         | 2.56%   |
| 5.4.83-0-lts           | 2         | 2.56%   |
| 5.4.43-1-lts           | 2         | 2.56%   |
| 5.15.86-0-lts          | 2         | 2.56%   |
| 5.15.59-0-lts          | 2         | 2.56%   |
| 5.15.47-0-lts          | 2         | 2.56%   |
| 5.15.41-0-lts          | 2         | 2.56%   |
| 5.15.4-0-lts           | 2         | 2.56%   |
| 6.6.7-0-lts            | 1         | 1.28%   |
| 6.6.4-0-lts            | 1         | 1.28%   |
| 6.6.1-0-edge           | 1         | 1.28%   |
| 6.4.4-0-edge           | 1         | 1.28%   |
| 6.1.55-0-lts           | 1         | 1.28%   |
| 6.1.53-0-lts           | 1         | 1.28%   |
| 6.1.52-0-lts           | 1         | 1.28%   |
| 6.1.46-0-lts           | 1         | 1.28%   |
| 6.1.39-0-lts           | 1         | 1.28%   |
| 6.1.34                 | 1         | 1.28%   |
| 6.1.24-0-lts           | 1         | 1.28%   |
| 6.1.11-0-edge          | 1         | 1.28%   |
| 5.8.12-0-edge          | 1         | 1.28%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.28%   |
| 5.4.84-0-lts           | 1         | 1.28%   |
| 5.4.72-0-lts           | 1         | 1.28%   |
| 5.4.64-0-lts           | 1         | 1.28%   |
| 5.4.46-0-lts           | 1         | 1.28%   |
| 5.4.27-0-lts           | 1         | 1.28%   |
| 5.17.9-0-edge          | 1         | 1.28%   |
| 5.17.0-0-edge          | 1         | 1.28%   |
| 5.16.12-may            | 1         | 1.28%   |
| 5.16.1-may             | 1         | 1.28%   |
| 5.15.96-0-lts          | 1         | 1.28%   |
| 5.15.95-0-lts          | 1         | 1.28%   |
| 5.15.89-0-lts          | 1         | 1.28%   |
| 5.15.85-0-lts          | 1         | 1.28%   |
| 5.15.73-0-lts          | 1         | 1.28%   |
| 5.15.60-0-lts          | 1         | 1.28%   |
| 5.15.46-1-lts          | 1         | 1.28%   |
| 5.15.37-0-lts          | 1         | 1.28%   |
| 5.15.34                | 1         | 1.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.62  | 2         | 2.56%   |
| 5.4.83  | 2         | 2.56%   |
| 5.4.43  | 2         | 2.56%   |
| 5.15.86 | 2         | 2.56%   |
| 5.15.59 | 2         | 2.56%   |
| 5.15.47 | 2         | 2.56%   |
| 5.15.41 | 2         | 2.56%   |
| 5.15.4  | 2         | 2.56%   |
| 5.15.0  | 2         | 2.56%   |
| 6.6.7   | 1         | 1.28%   |
| 6.6.4   | 1         | 1.28%   |
| 6.6.1   | 1         | 1.28%   |
| 6.4.4   | 1         | 1.28%   |
| 6.1.55  | 1         | 1.28%   |
| 6.1.53  | 1         | 1.28%   |
| 6.1.52  | 1         | 1.28%   |
| 6.1.46  | 1         | 1.28%   |
| 6.1.39  | 1         | 1.28%   |
| 6.1.34  | 1         | 1.28%   |
| 6.1.24  | 1         | 1.28%   |
| 6.1.11  | 1         | 1.28%   |
| 5.8.12  | 1         | 1.28%   |
| 5.6.2   | 1         | 1.28%   |
| 5.4.84  | 1         | 1.28%   |
| 5.4.72  | 1         | 1.28%   |
| 5.4.64  | 1         | 1.28%   |
| 5.4.46  | 1         | 1.28%   |
| 5.4.27  | 1         | 1.28%   |
| 5.17.9  | 1         | 1.28%   |
| 5.17.0  | 1         | 1.28%   |
| 5.16.12 | 1         | 1.28%   |
| 5.16.1  | 1         | 1.28%   |
| 5.15.96 | 1         | 1.28%   |
| 5.15.95 | 1         | 1.28%   |
| 5.15.89 | 1         | 1.28%   |
| 5.15.85 | 1         | 1.28%   |
| 5.15.73 | 1         | 1.28%   |
| 5.15.60 | 1         | 1.28%   |
| 5.15.46 | 1         | 1.28%   |
| 5.15.37 | 1         | 1.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 30        | 39.47%  |
| 5.10    | 11        | 14.47%  |
| 6.1     | 10        | 13.16%  |
| 5.4     | 9         | 11.84%  |
| 6.6     | 3         | 3.95%   |
| 5.17    | 2         | 2.63%   |
| 5.14    | 2         | 2.63%   |
| 6.4     | 1         | 1.32%   |
| 5.8     | 1         | 1.32%   |
| 5.6     | 1         | 1.32%   |
| 5.16    | 1         | 1.32%   |
| 5.13    | 1         | 1.32%   |
| 5.12    | 1         | 1.32%   |
| 4.4     | 1         | 1.32%   |
| 3.18    | 1         | 1.32%   |
| 3.10    | 1         | 1.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 60        | 82.19%  |
| i686   | 10        | 13.7%   |
| armv7l | 2         | 2.74%   |
| i586   | 1         | 1.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 73.97%  |
| XFCE    | 10        | 13.7%   |
| GNOME   | 4         | 5.48%   |
| LXQt    | 2         | 2.74%   |
| KDE5    | 2         | 2.74%   |
| sway    | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 35        | 46.67%  |
| Unknown | 33        | 44%     |
| Wayland | 7         | 9.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 69.86%  |
| LightDM | 14        | 19.18%  |
| SDDM    | 3         | 4.11%   |
| LXDM    | 2         | 2.74%   |
| GDM     | 2         | 2.74%   |
| XDM     | 1         | 1.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 45        | 59.21%  |
| Unknown | 23        | 30.26%  |
| en_US   | 6         | 7.89%   |
| ru_RU   | 1         | 1.32%   |
| en_GB   | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 47        | 63.51%  |
| EFI  | 27        | 36.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 60        | 80%     |
| Btrfs   | 7         | 9.33%   |
| Overlay | 3         | 4%      |
| Tmpfs   | 2         | 2.67%   |
| F2fs    | 1         | 1.33%   |
| Ext2    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 62.67%  |
| GPT     | 20        | 26.67%  |
| MBR     | 8         | 10.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 91.89%  |
| Yes       | 6         | 8.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 93.24%  |
| Yes       | 5         | 6.76%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 13        | 17.81%  |
| Lenovo           | 12        | 16.44%  |
| Dell             | 10        | 13.7%   |
| ASUSTek Computer | 10        | 13.7%   |
| Acer             | 5         | 6.85%   |
| Toshiba          | 3         | 4.11%   |
| IBM              | 3         | 4.11%   |
| Google           | 3         | 4.11%   |
| Fujitsu          | 2         | 2.74%   |
| Unknown          | 2         | 2.74%   |
| Synology         | 1         | 1.37%   |
| Sony             | 1         | 1.37%   |
| Pegatron         | 1         | 1.37%   |
| Olivetti         | 1         | 1.37%   |
| Notebook         | 1         | 1.37%   |
| MSI              | 1         | 1.37%   |
| LG Electronics   | 1         | 1.37%   |
| Haier            | 1         | 1.37%   |
| Gateway          | 1         | 1.37%   |
| Apple            | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 2.74%   |
| Toshiba WT8-A                            | 1         | 1.37%   |
| Toshiba Satellite Pro L50-A              | 1         | 1.37%   |
| Toshiba Satellite M645                   | 1         | 1.37%   |
| Synology DS1019+                         | 1         | 1.37%   |
| Sony VGN-UX27GN                          | 1         | 1.37%   |
| Pegatron Deepcam                         | 1         | 1.37%   |
| Olivetti Spring Peak                     | 1         | 1.37%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 1.37%   |
| MSI GL72M 7REX                           | 1         | 1.37%   |
| LG LW25-B7HG                             | 1         | 1.37%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.37%   |
| Lenovo V15 G3 IAP 82TT                   | 1         | 1.37%   |
| Lenovo V14-ADA 82C6                      | 1         | 1.37%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 1.37%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.37%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.37%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.37%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 1.37%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.37%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.37%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.37%   |
| Lenovo Flex 2-14 20404                   | 1         | 1.37%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 1.37%   |
| IBM 26446AG                              | 1         | 1.37%   |
| IBM 264070A                              | 1         | 1.37%   |
| HP ZBook 15 G5                           | 1         | 1.37%   |
| HP ProBook 4310s                         | 1         | 1.37%   |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 1.37%   |
| HP Presario V2000 (ES307UA#ABL)          | 1         | 1.37%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 1.37%   |
| HP Mini 110-3500                         | 1         | 1.37%   |
| HP Laptop 17-cp0xxx                      | 1         | 1.37%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.37%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.37%   |
| HP EliteBook 8460p                       | 1         | 1.37%   |
| HP EliteBook 2740p                       | 1         | 1.37%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 1.37%   |
| HP Compaq Mini CQ10-600                  | 1         | 1.37%   |
| Haier U144S                              | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 7         | 9.59%   |
| Dell Inspiron     | 6         | 8.22%   |
| Acer Aspire       | 5         | 6.85%   |
| HP EliteBook      | 3         | 4.11%   |
| Toshiba Satellite | 2         | 2.74%   |
| HP Presario       | 2         | 2.74%   |
| HP Laptop         | 2         | 2.74%   |
| Dell Latitude     | 2         | 2.74%   |
| Unknown           | 2         | 2.74%   |
| Toshiba WT8-A     | 1         | 1.37%   |
| Synology DS1019+  | 1         | 1.37%   |
| Sony VGN-UX27GN   | 1         | 1.37%   |
| Pegatron Deepcam  | 1         | 1.37%   |
| Olivetti Spring   | 1         | 1.37%   |
| Notebook NV4XMB   | 1         | 1.37%   |
| MSI GL72M         | 1         | 1.37%   |
| LG LW25-B7HG      | 1         | 1.37%   |
| Lenovo Yoga       | 1         | 1.37%   |
| Lenovo V15        | 1         | 1.37%   |
| Lenovo V14-ADA    | 1         | 1.37%   |
| Lenovo IdeaPad    | 1         | 1.37%   |
| Lenovo Flex       | 1         | 1.37%   |
| IBM ThinkPad      | 1         | 1.37%   |
| IBM 26446AG       | 1         | 1.37%   |
| IBM 264070A       | 1         | 1.37%   |
| HP ZBook          | 1         | 1.37%   |
| HP ProBook        | 1         | 1.37%   |
| HP Pavilion       | 1         | 1.37%   |
| HP Mini           | 1         | 1.37%   |
| HP ENVY           | 1         | 1.37%   |
| HP Compaq         | 1         | 1.37%   |
| Haier U144S       | 1         | 1.37%   |
| Google Samus      | 1         | 1.37%   |
| Google Leona      | 1         | 1.37%   |
| Google Kefka      | 1         | 1.37%   |
| Gateway MX3631m   | 1         | 1.37%   |
| Fujitsu LIFEBOOK  | 1         | 1.37%   |
| Fujitsu FMVNP8AE  | 1         | 1.37%   |
| Dell XPS          | 1         | 1.37%   |
| Dell Studio       | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2014    | 8         | 10.96%  |
| 2019    | 7         | 9.59%   |
| 2018    | 6         | 8.22%   |
| 2012    | 6         | 8.22%   |
| 2010    | 6         | 8.22%   |
| 2006    | 6         | 8.22%   |
| 2021    | 5         | 6.85%   |
| 2017    | 3         | 4.11%   |
| 2016    | 3         | 4.11%   |
| 2013    | 3         | 4.11%   |
| 2011    | 3         | 4.11%   |
| Unknown | 3         | 4.11%   |
| 2022    | 2         | 2.74%   |
| 2020    | 2         | 2.74%   |
| 2015    | 2         | 2.74%   |
| 2009    | 2         | 2.74%   |
| 2005    | 2         | 2.74%   |
| 2023    | 1         | 1.37%   |
| 2008    | 1         | 1.37%   |
| 2007    | 1         | 1.37%   |
| 1999    | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 73        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 72        | 98.63%  |
| Enabled  | 1         | 1.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 95.89%  |
| Yes  | 3         | 4.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 26.67%  |
| 3.01-4.0    | 14        | 18.67%  |
| 8.01-16.0   | 10        | 13.33%  |
| 16.01-24.0  | 7         | 9.33%   |
| 1.01-2.0    | 7         | 9.33%   |
| 0.51-1.0    | 7         | 9.33%   |
| 32.01-64.0  | 4         | 5.33%   |
| 2.01-3.0    | 3         | 4%      |
| 0.01-0.5    | 2         | 2.67%   |
| 64.01-256.0 | 1         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 24        | 31.58%  |
| 1.01-2.0  | 17        | 22.37%  |
| 0.51-1.0  | 11        | 14.47%  |
| 2.01-3.0  | 9         | 11.84%  |
| 4.01-8.0  | 7         | 9.21%   |
| 3.01-4.0  | 3         | 3.95%   |
| 8.01-16.0 | 2         | 2.63%   |
| 0         | 2         | 2.63%   |
| Unknown   | 1         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 76%     |
| 2      | 14        | 18.67%  |
| 0      | 2         | 2.67%   |
| 7      | 1         | 1.33%   |
| 3      | 1         | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 71.62%  |
| Yes       | 21        | 28.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 78.08%  |
| No        | 16        | 21.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 89.19%  |
| No        | 8         | 10.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 60.81%  |
| No        | 29        | 39.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 17        | 22.97%  |
| Canada       | 8         | 10.81%  |
| Russia       | 6         | 8.11%   |
| Germany      | 6         | 8.11%   |
| UK           | 5         | 6.76%   |
| Brazil       | 4         | 5.41%   |
| Spain        | 3         | 4.05%   |
| Slovakia     | 2         | 2.7%    |
| Italy        | 2         | 2.7%    |
| Australia    | 2         | 2.7%    |
| Venezuela    | 1         | 1.35%   |
| UAE          | 1         | 1.35%   |
| South Africa | 1         | 1.35%   |
| Portugal     | 1         | 1.35%   |
| Poland       | 1         | 1.35%   |
| Philippines  | 1         | 1.35%   |
| Netherlands  | 1         | 1.35%   |
| Mexico       | 1         | 1.35%   |
| Kenya        | 1         | 1.35%   |
| Jamaica      | 1         | 1.35%   |
| Israel       | 1         | 1.35%   |
| Hungary      | 1         | 1.35%   |
| Guatemala    | 1         | 1.35%   |
| Greece       | 1         | 1.35%   |
| France       | 1         | 1.35%   |
| Egypt        | 1         | 1.35%   |
| Czechia      | 1         | 1.35%   |
| China        | 1         | 1.35%   |
| Austria      | 1         | 1.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vernon           | 3         | 4%      |
| St Petersburg    | 3         | 4%      |
| Springfield      | 3         | 4%      |
| Stratford        | 2         | 2.67%   |
| Moscow           | 2         | 2.67%   |
| Fulham           | 2         | 2.67%   |
| Zhangzhou        | 1         | 1.33%   |
| Vienna           | 1         | 1.33%   |
| Tymovskoye       | 1         | 1.33%   |
| Turin            | 1         | 1.33%   |
| Tampa            | 1         | 1.33%   |
| Sydney           | 1         | 1.33%   |
| Stewartstown     | 1         | 1.33%   |
| Sisteron         | 1         | 1.33%   |
| Semily           | 1         | 1.33%   |
| Seattle          | 1         | 1.33%   |
| Sao Paulo        | 1         | 1.33%   |
| San Mateo        | 1         | 1.33%   |
| Saarbrücken     | 1         | 1.33%   |
| Rzeszów         | 1         | 1.33%   |
| Rostock          | 1         | 1.33%   |
| Purdys           | 1         | 1.33%   |
| Oakville         | 1         | 1.33%   |
| Northampton      | 1         | 1.33%   |
| Nairobi          | 1         | 1.33%   |
| Montreal         | 1         | 1.33%   |
| Merrill          | 1         | 1.33%   |
| Mérida          | 1         | 1.33%   |
| Manitowoc        | 1         | 1.33%   |
| Manila           | 1         | 1.33%   |
| Madrid           | 1         | 1.33%   |
| Lindavista Norte | 1         | 1.33%   |
| Lincoln          | 1         | 1.33%   |
| Leipzig          | 1         | 1.33%   |
| Larkspur         | 1         | 1.33%   |
| Kingston         | 1         | 1.33%   |
| Kecskemét       | 1         | 1.33%   |
| Johannesburg     | 1         | 1.33%   |
| Heraklion        | 1         | 1.33%   |
| Hampstead        | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 11.63%  |
| Unknown             | 8         | 10     | 9.3%    |
| Toshiba             | 8         | 10     | 9.3%    |
| Hitachi             | 8         | 8      | 9.3%    |
| WDC                 | 6         | 7      | 6.98%   |
| Seagate             | 6         | 15     | 6.98%   |
| Kingston            | 6         | 7      | 6.98%   |
| HGST                | 5         | 5      | 5.81%   |
| SanDisk             | 3         | 3      | 3.49%   |
| Crucial             | 3         | 3      | 3.49%   |
| SK hynix            | 2         | 2      | 2.33%   |
| Micron Technology   | 2         | 2      | 2.33%   |
| Intel               | 2         | 4      | 2.33%   |
| Fujitsu             | 2         | 2      | 2.33%   |
| A-DATA Technology   | 2         | 2      | 2.33%   |
| SPCC                | 1         | 1      | 1.16%   |
| SINTECHI            | 1         | 1      | 1.16%   |
| LITEON              | 1         | 1      | 1.16%   |
| KC600               | 1         | 1      | 1.16%   |
| JMicron Technology  | 1         | 1      | 1.16%   |
| Intenso             | 1         | 1      | 1.16%   |
| INNOVATION IT       | 1         | 1      | 1.16%   |
| IBM                 | 1         | 1      | 1.16%   |
| Emtec               | 1         | 1      | 1.16%   |
| Dell                | 1         | 2      | 1.16%   |
| China               | 1         | 1      | 1.16%   |
| Aura                | 1         | 1      | 1.16%   |
| AMD                 | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                              | 3         | 3.33%   |
| Unknown MMC Card  64GB                              | 2         | 2.22%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 2.22%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 2.22%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 2.22%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 2.22%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 2.22%   |
| WDC WDS500G2X0C-00L350 500GB                        | 1         | 1.11%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1.11%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1.11%   |
| WDC WD10SPZX-60Z10T1 1TB                            | 1         | 1.11%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 1.11%   |
| Unknown SD32G  32GB                                 | 1         | 1.11%   |
| Unknown NVMe SSD Drive 1024GB                       | 1         | 1.11%   |
| Unknown MMC Card  32GB                              | 1         | 1.11%   |
| Unknown MMC Card                                    | 1         | 1.11%   |
| Toshiba NVMe SSD Drive 256GB                        | 1         | 1.11%   |
| Toshiba MQ01ABD1 1TB                                | 1         | 1.11%   |
| Toshiba MK6008GAH 64GB                              | 1         | 1.11%   |
| Toshiba MK4009GAL 40GB                              | 1         | 1.11%   |
| Toshiba KXG5AZNV256G 256GB                          | 1         | 1.11%   |
| Toshiba HDWL110 1TB                                 | 1         | 1.11%   |
| SPCC Solid State Disk 256GB                         | 1         | 1.11%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB           | 1         | 1.11%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1.11%   |
| SINTECHI HighSpeed SD to CF Adapter V1.0            | 1         | 1.11%   |
| Seagate ST98823A 80GB                               | 1         | 1.11%   |
| Seagate ST9250315AS 250GB                           | 1         | 1.11%   |
| Seagate ST8000VN004-2M2101 8TB                      | 1         | 1.11%   |
| Seagate ST2000LM015-2E81 2TB                        | 1         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.11%   |
| Seagate BUP Portable 5TB                            | 1         | 1.11%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB        | 1         | 1.11%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1.11%   |
| SanDisk Extreme Pro 55AF 1TB SSD                    | 1         | 1.11%   |
| Samsung SSD 970 EVO Plus 250GB                      | 1         | 1.11%   |
| Samsung Portable SSD T5 1TB                         | 1         | 1.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 1         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 8         | 8      | 24.24%  |
| Toshiba             | 7         | 8      | 21.21%  |
| Seagate             | 6         | 15     | 18.18%  |
| HGST                | 5         | 5      | 15.15%  |
| WDC                 | 2         | 2      | 6.06%   |
| Fujitsu             | 2         | 2      | 6.06%   |
| SINTECHI            | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 2      | 3.03%   |
| IBM                 | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 22.22%  |
| Crucial             | 3         | 3      | 11.11%  |
| WDC                 | 2         | 2      | 7.41%   |
| SanDisk             | 2         | 2      | 7.41%   |
| Samsung Electronics | 2         | 2      | 7.41%   |
| SPCC                | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| KC600               | 1         | 1      | 3.7%    |
| JMicron Technology  | 1         | 1      | 3.7%    |
| Intenso             | 1         | 1      | 3.7%    |
| INNOVATION IT       | 1         | 1      | 3.7%    |
| Emtec               | 1         | 1      | 3.7%    |
| Dell                | 1         | 2      | 3.7%    |
| China               | 1         | 1      | 3.7%    |
| AMD                 | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 33        | 44     | 41.25%  |
| SSD     | 23        | 29     | 28.75%  |
| NVMe    | 16        | 23     | 20%     |
| MMC     | 7         | 8      | 8.75%   |
| Unknown | 1         | 1      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 69     | 66.25%  |
| NVMe | 16        | 23     | 20%     |
| MMC  | 7         | 8      | 8.75%   |
| SAS  | 4         | 5      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 48     | 73.68%  |
| 0.51-1.0   | 12        | 13     | 21.05%  |
| 4.01-10.0  | 2         | 11     | 3.51%   |
| 1.01-2.0   | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 18        | 23.68%  |
| 1-20           | 16        | 21.05%  |
| 251-500        | 9         | 11.84%  |
| Unknown        | 9         | 11.84%  |
| 21-50          | 7         | 9.21%   |
| 501-1000       | 6         | 7.89%   |
| 1001-2000      | 4         | 5.26%   |
| More than 3000 | 3         | 3.95%   |
| 51-100         | 3         | 3.95%   |
| 2001-3000      | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 50        | 65.79%  |
| Unknown   | 9         | 11.84%  |
| 21-50     | 5         | 6.58%   |
| 51-100    | 4         | 5.26%   |
| 101-250   | 3         | 3.95%   |
| 251-500   | 2         | 2.63%   |
| 501-1000  | 2         | 2.63%   |
| 2001-3000 | 1         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 9.09%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 9.09%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 9.09%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 9.09%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 9.09%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 9.09%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 9.09%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 9.09%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 36.36%  |
| Seagate             | 2         | 2      | 18.18%  |
| HGST                | 2         | 2      | 18.18%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 2      | 9.09%   |
| Micron Technology   | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 40%     |
| Seagate             | 2         | 2      | 20%     |
| HGST                | 2         | 2      | 20%     |
| Toshiba             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Works    | 45        | 66     | 56.96%  |
| Detected | 23        | 27     | 29.11%  |
| Malfunc  | 11        | 12     | 13.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 51        | 64.56%  |
| AMD                          | 11        | 13.92%  |
| Samsung Electronics          | 7         | 8.86%   |
| SanDisk                      | 3         | 3.8%    |
| SK hynix                     | 2         | 2.53%   |
| ADATA Technology             | 2         | 2.53%   |
| Toshiba America Info Systems | 1         | 1.27%   |
| Micron Technology            | 1         | 1.27%   |
| Marvell Technology Group     | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 11.76%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 4.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 4.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 3.53%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 3.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 3.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 3.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 3.53%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 3.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 3.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 3.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 2.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.35%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 2.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.35%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 1.18%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 1.18%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.18%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 1.18%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.18%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.18%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.18%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1         | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.18%   |
| Intel SSD 600P Series                                                          | 1         | 1.18%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.18%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.18%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.18%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 60%     |
| NVMe | 16        | 20%     |
| IDE  | 12        | 15%     |
| RAID | 4         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 79.73%  |
| AMD    | 13        | 17.57%  |
| ARM    | 2         | 2.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz       | 2         | 2.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 2.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 2.7%    |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 2.7%    |
| Intel Atom CPU N455 @ 1.66GHz           | 2         | 2.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.7%    |
| Intel Xeon E-2176M CPU @ 2.70GHz        | 1         | 1.35%   |
| Intel Pentium M processor 1.60GHz       | 1         | 1.35%   |
| Intel Pentium M processor 1.50GHz       | 1         | 1.35%   |
| Intel Pentium III (Coppermine)          | 1         | 1.35%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.35%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 1.35%   |
| Intel Mobile Pentium MMX                | 1         | 1.35%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 1.35%   |
| Intel Core Solo CPU U1500 @ 1.33GHz     | 1         | 1.35%   |
| Intel Core m3-8100Y CPU @ 1.10GHz       | 1         | 1.35%   |
| Intel Core i9-9980HK CPU @ 2.40GHz      | 1         | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.35%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz       | 1         | 1.35%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.35%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.35%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.35%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.35%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 1         | 1.35%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.35%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 1.35%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz      | 1         | 1.35%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 1         | 1.35%   |
| Intel Core i5 CPU M 480 @ 2.67GHz       | 1         | 1.35%   |
| Intel Core i3-5020U CPU @ 2.20GHz       | 1         | 1.35%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 1         | 1.35%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 1.35%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 1         | 1.35%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz    | 1         | 1.35%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz    | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 18        | 24.32%  |
| Other                | 8         | 10.81%  |
| Intel Celeron        | 6         | 8.11%   |
| Intel Atom           | 6         | 8.11%   |
| Intel Pentium M      | 4         | 5.41%   |
| Intel Core i3        | 4         | 5.41%   |
| Intel Core i7        | 3         | 4.05%   |
| Intel Core 2 Duo     | 3         | 4.05%   |
| AMD Ryzen 5          | 3         | 4.05%   |
| Intel Pentium        | 2         | 2.7%    |
| AMD Ryzen 7          | 2         | 2.7%    |
| AMD A4               | 2         | 2.7%    |
| Intel Xeon           | 1         | 1.35%   |
| Intel Pentium III    | 1         | 1.35%   |
| Intel Genuine        | 1         | 1.35%   |
| Intel Core Solo      | 1         | 1.35%   |
| Intel Core m3        | 1         | 1.35%   |
| Intel Core i9        | 1         | 1.35%   |
| Intel Core 2         | 1         | 1.35%   |
| ARM ARMv7            | 1         | 1.35%   |
| AMD Turion 64 Mobile | 1         | 1.35%   |
| AMD Ryzen 3          | 1         | 1.35%   |
| AMD E2               | 1         | 1.35%   |
| AMD A6               | 1         | 1.35%   |
| AMD A10              | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 35        | 47.3%   |
| 4       | 19        | 25.68%  |
| 1       | 12        | 16.22%  |
| 6       | 3         | 4.05%   |
| 8       | 2         | 2.7%    |
| 16      | 1         | 1.35%   |
| 3       | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 72        | 98.63%  |
| Unknown | 1         | 1.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 37        | 50.68%  |
| 1       | 35        | 47.95%  |
| Unknown | 1         | 1.37%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 40        | 54.05%  |
| 32-bit, 64-bit | 31        | 41.89%  |
| 32-bit         | 3         | 4.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 56.58%  |
| 0x306a9    | 3         | 3.95%   |
| 0x30678    | 3         | 3.95%   |
| 0x106ca    | 3         | 3.95%   |
| 0x906ea    | 2         | 2.63%   |
| 0x806eb    | 2         | 2.63%   |
| 0x806c1    | 2         | 2.63%   |
| 0x206a7    | 2         | 2.63%   |
| 0x08108102 | 2         | 2.63%   |
| 0x06006704 | 2         | 2.63%   |
| 0x706e5    | 1         | 1.32%   |
| 0x683      | 1         | 1.32%   |
| 0x506c9    | 1         | 1.32%   |
| 0x406c4    | 1         | 1.32%   |
| 0x306d4    | 1         | 1.32%   |
| 0x306c3    | 1         | 1.32%   |
| 0x20655    | 1         | 1.32%   |
| 0x106e5    | 1         | 1.32%   |
| 0x1067a    | 1         | 1.32%   |
| 0x08608103 | 1         | 1.32%   |
| 0x08108109 | 1         | 1.32%   |
| 0x0810100b | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 12.16%  |
| P6               | 7         | 9.46%   |
| Silvermont       | 6         | 8.11%   |
| Unknown          | 5         | 6.76%   |
| IvyBridge        | 4         | 5.41%   |
| Goldmont         | 4         | 5.41%   |
| Bonnell          | 4         | 5.41%   |
| Zen+             | 3         | 4.05%   |
| Westmere         | 3         | 4.05%   |
| TigerLake        | 3         | 4.05%   |
| SandyBridge      | 3         | 4.05%   |
| Penryn           | 3         | 4.05%   |
| Haswell          | 3         | 4.05%   |
| Excavator        | 3         | 4.05%   |
| Broadwell        | 3         | 4.05%   |
| Zen 2            | 1         | 1.35%   |
| Zen              | 1         | 1.35%   |
| Skylake          | 1         | 1.35%   |
| Puma             | 1         | 1.35%   |
| Nehalem          | 1         | 1.35%   |
| K8 Hammer        | 1         | 1.35%   |
| Jaguar           | 1         | 1.35%   |
| IceLake          | 1         | 1.35%   |
| Core             | 1         | 1.35%   |
| Bobcat           | 1         | 1.35%   |
| Alderlake Hybrid | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 53        | 64.63%  |
| AMD      | 19        | 23.17%  |
| Nvidia   | 8         | 9.76%   |
| Neomagic | 2         | 2.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 4.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 3.49%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 3.49%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.49%   |
| Intel HD Graphics 500                                                                    | 3         | 3.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.49%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 3.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.16%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.16%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.16%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.16%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.16%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 1.16%   |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 1.16%   |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 1.16%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.16%   |
| Intel UHD Graphics 615                                                                   | 1         | 1.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.16%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.16%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.16%   |
| Intel HD Graphics 630                                                                    | 1         | 1.16%   |
| Intel HD Graphics 620                                                                    | 1         | 1.16%   |
| Intel Coffee Lake-S GT2 [UHD Graphics P630]                                              | 1         | 1.16%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.16%   |
| Intel AlderLake-S GT1                                                                    | 1         | 1.16%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 50%     |
| 1 x AMD        | 14        | 18.92%  |
| 2 x Intel      | 7         | 9.46%   |
| Intel + Nvidia | 6         | 8.11%   |
| Intel + AMD    | 3         | 4.05%   |
| Other          | 2         | 2.7%    |
| 1 x Neomagic   | 2         | 2.7%    |
| 2 x AMD        | 1         | 1.35%   |
| 1 x Nvidia     | 1         | 1.35%   |
| AMD + Nvidia   | 1         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 68        | 90.67%  |
| Unknown     | 5         | 6.67%   |
| Proprietary | 2         | 2.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 86.49%  |
| 0.01-0.5   | 5         | 6.76%   |
| 1.01-2.0   | 3         | 4.05%   |
| 2.01-3.0   | 1         | 1.35%   |
| 0.51-1.0   | 1         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 20.29%  |
| LG Display              | 11        | 15.94%  |
| BOE                     | 10        | 14.49%  |
| Chimei Innolux          | 7         | 10.14%  |
| Samsung Electronics     | 3         | 4.35%   |
| LG Philips              | 3         | 4.35%   |
| Chi Mei Optoelectronics | 3         | 4.35%   |
| Lenovo                  | 2         | 2.9%    |
| InfoVision              | 2         | 2.9%    |
| HannStar                | 2         | 2.9%    |
| Sharp                   | 1         | 1.45%   |
| Quanta Display          | 1         | 1.45%   |
| PANDA                   | 1         | 1.45%   |
| ONN                     | 1         | 1.45%   |
| Goldstar                | 1         | 1.45%   |
| Envision                | 1         | 1.45%   |
| DENON                   | 1         | 1.45%   |
| CSO                     | 1         | 1.45%   |
| CPT                     | 1         | 1.45%   |
| CHD                     | 1         | 1.45%   |
| Apple                   | 1         | 1.45%   |
| Acer                    | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 2.9%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 2.9%    |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch                  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 1.45%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch          | 1         | 1.45%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.45%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                     | 1         | 1.45%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 1.45%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch              | 1         | 1.45%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 1.45%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 1.45%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch              | 1         | 1.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 1.45%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 1.45%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch              | 1         | 1.45%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 1.45%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch                 | 1         | 1.45%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 1.45%   |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                         | 1         | 1.45%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 1.45%   |
| CPT LCD Monitor CPT04E2 1024x600 222x130mm 10.1-inch                     | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 309x173mm 13.9-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 25        | 36.23%  |
| 1920x1080 (FHD)   | 17        | 24.64%  |
| 1280x800 (WXGA)   | 6         | 8.7%    |
| 1024x600          | 4         | 5.8%    |
| 1600x900 (HD+)    | 3         | 4.35%   |
| 3840x2160 (4K)    | 2         | 2.9%    |
| 2560x1440 (QHD)   | 2         | 2.9%    |
| 1280x768          | 2         | 2.9%    |
| 2880x1800         | 1         | 1.45%   |
| 2560x1700         | 1         | 1.45%   |
| 2560x1080         | 1         | 1.45%   |
| 1920x1200 (WUXGA) | 1         | 1.45%   |
| 1440x900 (WXGA+)  | 1         | 1.45%   |
| 1360x768          | 1         | 1.45%   |
| 1280x1024 (SXGA)  | 1         | 1.45%   |
| 1024x768 (XGA)    | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 23        | 33.33%  |
| 14     | 12        | 17.39%  |
| 13     | 10        | 14.49%  |
| 17     | 6         | 8.7%    |
| 11     | 5         | 7.25%   |
| 12     | 4         | 5.8%    |
| 10     | 4         | 5.8%    |
| 31     | 2         | 2.9%    |
| 60     | 1         | 1.45%   |
| 32     | 1         | 1.45%   |
| 29     | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 62.32%  |
| 201-300     | 16        | 23.19%  |
| 351-400     | 5         | 7.25%   |
| 601-700     | 3         | 4.35%   |
| 701-800     | 1         | 1.45%   |
| 1001-1500   | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 80.3%   |
| 16/10 | 9         | 13.64%  |
| 5/4   | 1         | 1.52%   |
| 4/3   | 1         | 1.52%   |
| 3/2   | 1         | 1.52%   |
| 21/9  | 1         | 1.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 33.33%  |
| 81-90          | 19        | 27.54%  |
| 51-60          | 5         | 7.25%   |
| 71-80          | 4         | 5.8%    |
| 41-50          | 4         | 5.8%    |
| 121-130        | 4         | 5.8%    |
| 61-70          | 3         | 4.35%   |
| 351-500        | 3         | 4.35%   |
| More than 1000 | 1         | 1.45%   |
| 301-350        | 1         | 1.45%   |
| 141-150        | 1         | 1.45%   |
| 131-140        | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 39.71%  |
| 101-120       | 25        | 36.76%  |
| 51-100        | 10        | 14.71%  |
| More than 240 | 2         | 2.94%   |
| 1-50          | 2         | 2.94%   |
| 161-240       | 2         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 61        | 82.43%  |
| 0     | 7         | 9.46%   |
| 2     | 6         | 8.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 43        | 36.44%  |
| Intel                           | 37        | 31.36%  |
| Qualcomm Atheros                | 17        | 14.41%  |
| Broadcom                        | 9         | 7.63%   |
| Marvell Technology Group        | 3         | 2.54%   |
| LSI                             | 2         | 1.69%   |
| Broadcom Limited                | 2         | 1.69%   |
| Qualcomm Atheros Communications | 1         | 0.85%   |
| Qualcomm                        | 1         | 0.85%   |
| Google                          | 1         | 0.85%   |
| Dresden Elektronik              | 1         | 0.85%   |
| AMD                             | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 21        | 15.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 6.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 8         | 5.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 2.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 2.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.47%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.47%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.47%   |
| Intel Wireless 7265                                                            | 2         | 1.47%   |
| Intel Wireless 3160                                                            | 2         | 1.47%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.47%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.47%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 1.47%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 2         | 1.47%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.74%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.74%   |
| Qualcomm Fairphone 4 5G                                                        | 1         | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.74%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.74%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 0.74%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 0.74%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.74%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.74%   |
| LSI WinModem 56k                                                               | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 49.25%  |
| Qualcomm Atheros                | 16        | 23.88%  |
| Realtek Semiconductor           | 7         | 10.45%  |
| Broadcom                        | 7         | 10.45%  |
| Broadcom Limited                | 2         | 2.99%   |
| Qualcomm Atheros Communications | 1         | 1.49%   |
| Marvell Technology Group        | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 8         | 11.94%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 4.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 4.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 2.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.99%   |
| Intel Wireless-AC 9260                                                         | 2         | 2.99%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 2.99%   |
| Intel Wireless 7265                                                            | 2         | 2.99%   |
| Intel Wireless 3160                                                            | 2         | 2.99%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 2.99%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 2.99%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 2.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.49%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 1.49%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.49%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.49%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.49%   |
| Intel Wireless 8260                                                            | 1         | 1.49%   |
| Intel Wireless 7260                                                            | 1         | 1.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.49%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.49%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.49%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 1.49%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.49%   |
| Intel Centrino Wireless-N 100                                                  | 1         | 1.49%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                           | 1         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 1         | 1.49%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter           | 1         | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 62.3%   |
| Intel                    | 13        | 21.31%  |
| Qualcomm Atheros         | 3         | 4.92%   |
| Broadcom                 | 3         | 4.92%   |
| Marvell Technology Group | 2         | 3.28%   |
| Qualcomm                 | 1         | 1.64%   |
| LSI                      | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 33.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 14.52%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 6.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 4.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 3.23%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.61%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 1.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.61%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.61%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.61%   |
| LSI ET-131x PCI-E Ethernet Controller                             | 1         | 1.61%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 1.61%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.61%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.61%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.61%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 1.61%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express             | 1         | 1.61%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.61%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 51.16%  |
| Ethernet | 56        | 43.41%  |
| Modem    | 7         | 5.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 66.67%  |
| Ethernet | 24        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 68.49%  |
| 1     | 18        | 24.66%  |
| 0     | 5         | 6.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 83.78%  |
| Yes  | 12        | 16.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 42.22%  |
| Realtek Semiconductor           | 4         | 8.89%   |
| Qualcomm Atheros Communications | 4         | 8.89%   |
| Lite-On Technology              | 3         | 6.67%   |
| IMC Networks                    | 3         | 6.67%   |
| Broadcom                        | 3         | 6.67%   |
| ASUSTek Computer                | 2         | 4.44%   |
| Toshiba                         | 1         | 2.22%   |
| Marvell Semiconductor           | 1         | 2.22%   |
| Hewlett-Packard                 | 1         | 2.22%   |
| Foxconn / Hon Hai               | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |
| Apple                           | 1         | 2.22%   |
| Alps Electric                   | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 15.56%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.67%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 4.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 4.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.44%   |
| Intel AX201 Bluetooth                               | 2         | 4.44%   |
| Intel AX200 Bluetooth                               | 2         | 4.44%   |
| Toshiba Bluetooth Device                            | 1         | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.22%   |
| Realtek Bluetooth Radio                             | 1         | 2.22%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.22%   |
| Intel AX210 Bluetooth                               | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.22%   |
| IMC Networks Bluetooth Device                       | 1         | 2.22%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.22%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.22%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |
| Broadcom BCM20702A0                                 | 1         | 2.22%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.22%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.22%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 2.22%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.22%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.22%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 55        | 73.33%  |
| AMD                       | 15        | 20%     |
| Nvidia                    | 2         | 2.67%   |
| Sennheiser Communications | 1         | 1.33%   |
| Realtek Semiconductor     | 1         | 1.33%   |
| Cirrus Logic              | 1         | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 7.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 6.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 4.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 4.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 4.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 4.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.3%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 3.3%    |
| AMD FCH Azalia Controller                                                                         | 3         | 3.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 3.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 2.2%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.2%    |
| AMD High Definition Audio Controller                                                              | 2         | 2.2%    |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 1.1%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.1%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.1%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.1%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.1%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 1.1%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.1%    |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 1.1%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.1%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.1%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 23.88%  |
| Unknown             | 14        | 20.9%   |
| SK hynix            | 12        | 17.91%  |
| Micron Technology   | 7         | 10.45%  |
| Elpida              | 5         | 7.46%   |
| Crucial             | 5         | 7.46%   |
| Kingston            | 2         | 2.99%   |
| A-DATA Technology   | 2         | 2.99%   |
| Unknown (ABCD)      | 1         | 1.49%   |
| Ramaxel Technology  | 1         | 1.49%   |
| Nanya Technology    | 1         | 1.49%   |
| Gold Key            | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 4.17%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 2.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.78%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 2.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 2.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.78%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.39%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.39%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 1.39%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.39%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 3200MT/s        | 1         | 1.39%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.39%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.39%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s            | 1         | 1.39%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.39%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 1.39%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.39%   |
| Samsung RAM K4E6E304EC-EGCF 4096MB LPDDR3 1867MT/s               | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 22        | 38.6%   |
| DDR4   | 16        | 28.07%  |
| LPDDR3 | 5         | 8.77%   |
| DDR    | 4         | 7.02%   |
| SDRAM  | 3         | 5.26%   |
| DDR2   | 3         | 5.26%   |
| LPDDR4 | 2         | 3.51%   |
| DRAM   | 2         | 3.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 86.44%  |
| Row Of Chips | 5         | 8.47%   |
| Unknown      | 2         | 3.39%   |
| DIMM         | 1         | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 21        | 31.34%  |
| 8192  | 19        | 28.36%  |
| 2048  | 9         | 13.43%  |
| 1024  | 7         | 10.45%  |
| 512   | 5         | 7.46%   |
| 16384 | 4         | 5.97%   |
| 256   | 1         | 1.49%   |
| 128   | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 12        | 19.35%  |
| Unknown | 9         | 14.52%  |
| 1334    | 7         | 11.29%  |
| 3200    | 6         | 9.68%   |
| 2667    | 6         | 9.68%   |
| 2400    | 5         | 8.06%   |
| 2133    | 4         | 6.45%   |
| 1867    | 3         | 4.84%   |
| 1333    | 2         | 3.23%   |
| 4199    | 1         | 1.61%   |
| 3266    | 1         | 1.61%   |
| 1400    | 1         | 1.61%   |
| 1200    | 1         | 1.61%   |
| 1067    | 1         | 1.61%   |
| 1066    | 1         | 1.61%   |
| 667     | 1         | 1.61%   |
| 533     | 1         | 1.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Microdia                               | 7         | 12.28%  |
| IMC Networks                           | 7         | 12.28%  |
| Suyin                                  | 3         | 5.26%   |
| Quanta                                 | 3         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.26%   |
| Bison Electronics                      | 3         | 5.26%   |
| Sunplus Innovation Technology          | 2         | 3.51%   |
| Apple                                  | 2         | 3.51%   |
| Acer                                   | 2         | 3.51%   |
| Syntek                                 | 1         | 1.75%   |
| Silicon Motion                         | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Lenovo                                 | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                  | 3         | 5.26%   |
| Microdia Integrated_Webcam_HD                                 | 3         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 3         | 5.26%   |
| IMC Networks Integrated Camera                                | 3         | 5.26%   |
| Realtek Acer 640 x 480 laptop camera                          | 2         | 3.51%   |
| Microdia Laptop_Integrated_Webcam_2M                          | 2         | 3.51%   |
| Chicony Integrated Camera                                     | 2         | 3.51%   |
| Chicony HD WebCam                                             | 2         | 3.51%   |
| Syntek EasyCamera                                             | 1         | 1.75%   |
| Suyin Integrated_Webcam_HD                                    | 1         | 1.75%   |
| Suyin HP TrueVision HD                                        | 1         | 1.75%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.75%   |
| Sunplus HP Universal Camera                                   | 1         | 1.75%   |
| Sunplus HD WebCam                                             | 1         | 1.75%   |
| Silicon Motion NCM-G102                                       | 1         | 1.75%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870]           | 1         | 1.75%   |
| Realtek USB2.0 HD UVC WebCam                                  | 1         | 1.75%   |
| Realtek USB Camera                                            | 1         | 1.75%   |
| Quanta USB2.0 HD UVC WebCam                                   | 1         | 1.75%   |
| Quanta HP Wide Vision HD Camera                               | 1         | 1.75%   |
| Quanta HP TrueVision HD Camera                                | 1         | 1.75%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                | 1         | 1.75%   |
| Microdia Integrated Webcam                                    | 1         | 1.75%   |
| Lite-On TOSHIBA Web Camera - HD                               | 1         | 1.75%   |
| Lenovo Integrated Webcam                                      | 1         | 1.75%   |
| IMC Networks USB2.0 UVC VGA WebCam                            | 1         | 1.75%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 1.75%   |
| Chicony USB2.0 FHD UVC WebCam                                 | 1         | 1.75%   |
| Chicony Integrated Camera (1280x720@30)                       | 1         | 1.75%   |
| Chicony HP Webcam [2 MP Macro]                                | 1         | 1.75%   |
| Chicony HP TrueVision HD Camera                               | 1         | 1.75%   |
| Chicony HP HD Camera                                          | 1         | 1.75%   |
| Chicony CNF9055 Toshiba Webcam                                | 1         | 1.75%   |
| Chicony CNF8243 Webcam                                        | 1         | 1.75%   |
| Chicony 2.0M UVC Webcam / CNF7129                             | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                 | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam              | 1         | 1.75%   |
| Bison Lenovo Integrated Webcam                                | 1         | 1.75%   |
| Bison Lenovo EasyCamera                                       | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 42.86%  |
| AuthenTec          | 2         | 28.57%  |
| Synaptics          | 1         | 14.29%  |
| STMicroelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 14.29%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader                                      | 1         | 14.29%  |

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
| 0     | 44        | 57.89%  |
| 1     | 21        | 27.63%  |
| 2     | 9         | 11.84%  |
| 4     | 2         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 23.4%   |
| Modem                    | 7         | 14.89%  |
| Fingerprint reader       | 7         | 14.89%  |
| Camera                   | 4         | 8.51%   |
| Bluetooth                | 4         | 8.51%   |
| Net/wireless             | 3         | 6.38%   |
| Communication controller | 3         | 6.38%   |
| Chipcard                 | 2         | 4.26%   |
| Unclassified device      | 1         | 2.13%   |
| Storage                  | 1         | 2.13%   |
| Sound                    | 1         | 2.13%   |
| Network                  | 1         | 2.13%   |
| Multimedia controller    | 1         | 2.13%   |
| Card reader              | 1         | 2.13%   |

