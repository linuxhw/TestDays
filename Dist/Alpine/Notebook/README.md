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

Total: 121

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Chuwi         | HeroBook Pro                | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| Chuwi         | HeroBook Pro                | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| Acer          | Aspire A515-54              | [ea0b7cd870](https://linux-hardware.org/?probe=ea0b7cd870) | Dec 26, 2023 |
| Chuwi         | HeroBook Pro                | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Chuwi         | HeroBook Pro                | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| Dell          | Latitude 3420               | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| ASUSTek       | 1001PX                      | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| Chuwi         | HeroBook Pro                | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Chuwi         | HeroBook Pro                | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Apple         | MacBookAir5,2               | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Chuwi         | HeroBook Pro                | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| Chuwi         | HeroBook Pro                | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Lenovo        | Flex 2-14 20404             | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Chuwi         | HeroBook Pro                | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Chuwi         | HeroBook Pro                | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| Chuwi         | HeroBook Pro                | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Chuwi         | HeroBook Pro                | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Chuwi         | HeroBook Pro                | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Chuwi         | HeroBook Pro                | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Unknown       | Unknown                     | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Chuwi         | HeroBook Pro                | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Chuwi         | HeroBook Pro                | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Chuwi         | HeroBook Pro                | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Chuwi         | HeroBook Pro                | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Chuwi         | HeroBook Pro                | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Chuwi         | HeroBook Pro                | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Chuwi         | HeroBook Pro                | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Chuwi         | HeroBook Pro                | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| Chuwi         | HeroBook Pro                | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| Chuwi         | HeroBook Pro                | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Chuwi         | HeroBook Pro                | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.16.0               | 6         | 7.41%   |
| Alpine 3.15.0               | 6         | 7.41%   |
| Alpine 3.14.0               | 5         | 6.17%   |
| Alpine 3.12.0               | 5         | 6.17%   |
| Alpine 3.18.3               | 4         | 4.94%   |
| Alpine 3.15.4               | 4         | 4.94%   |
| Alpine 3.15.0_alpha20210804 | 4         | 4.94%   |
| Alpine 3.18.0               | 3         | 3.7%    |
| Alpine 3.17.2               | 3         | 3.7%    |
| Alpine 3.17.0               | 3         | 3.7%    |
| Alpine 3.19_alpha20230901   | 2         | 2.47%   |
| Alpine 3.18_alpha20230329   | 2         | 2.47%   |
| Alpine 3.18.4               | 2         | 2.47%   |
| Alpine 3.17.1               | 2         | 2.47%   |
| Alpine 3.16.2               | 2         | 2.47%   |
| Alpine 3.14.2               | 2         | 2.47%   |
| Alpine 3.13.5               | 2         | 2.47%   |
| Alpine 3.13.0_alpha20201218 | 2         | 2.47%   |
| Alpine 3.13.0_alpha20200917 | 2         | 2.47%   |
| Alpine 3.11.2               | 2         | 2.47%   |
| Alpine 3.19.0_rc2           | 1         | 1.23%   |
| Alpine 3.19.0               | 1         | 1.23%   |
| Alpine 3.18.5               | 1         | 1.23%   |
| Alpine 3.18.2               | 1         | 1.23%   |
| Alpine 3.17_alpha20220809   | 1         | 1.23%   |
| Alpine 3.17.3               | 1         | 1.23%   |
| Alpine 3.16.3               | 1         | 1.23%   |
| Alpine 3.16.1               | 1         | 1.23%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.23%   |
| Alpine 3.15.2               | 1         | 1.23%   |
| Alpine 3.15.0_rc5           | 1         | 1.23%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.23%   |
| Alpine 3.13.1               | 1         | 1.23%   |
| Alpine 3.13.0_rc2           | 1         | 1.23%   |
| Alpine 3.13.0_alpha20200626 | 1         | 1.23%   |
| Alpine 3.12.3               | 1         | 1.23%   |
| Alpine 3.12.1               | 1         | 1.23%   |
| Alpine 3.11.5               | 1         | 1.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 75        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.1.62-0-lts           | 2         | 2.33%   |
| 5.4.83-0-lts           | 2         | 2.33%   |
| 5.4.43-1-lts           | 2         | 2.33%   |
| 5.15.86-0-lts          | 2         | 2.33%   |
| 5.15.59-0-lts          | 2         | 2.33%   |
| 5.15.47-0-lts          | 2         | 2.33%   |
| 5.15.41-0-lts          | 2         | 2.33%   |
| 5.15.4-0-lts           | 2         | 2.33%   |
| 6.6.7-0-lts            | 1         | 1.16%   |
| 6.6.4-0-lts            | 1         | 1.16%   |
| 6.6.1-0-edge           | 1         | 1.16%   |
| 6.4.4-0-edge           | 1         | 1.16%   |
| 6.2.0-37-generic       | 1         | 1.16%   |
| 6.2.0-36-generic       | 1         | 1.16%   |
| 6.1.69-0-lts           | 1         | 1.16%   |
| 6.1.55-0-lts           | 1         | 1.16%   |
| 6.1.53-0-lts           | 1         | 1.16%   |
| 6.1.52-0-lts           | 1         | 1.16%   |
| 6.1.46-0-lts           | 1         | 1.16%   |
| 6.1.39-0-lts           | 1         | 1.16%   |
| 6.1.34                 | 1         | 1.16%   |
| 6.1.24-0-lts           | 1         | 1.16%   |
| 6.1.11-0-edge          | 1         | 1.16%   |
| 5.8.12-0-edge          | 1         | 1.16%   |
| 5.7.4                  | 1         | 1.16%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.16%   |
| 5.4.84-0-lts           | 1         | 1.16%   |
| 5.4.72-0-lts           | 1         | 1.16%   |
| 5.4.64-0-lts           | 1         | 1.16%   |
| 5.4.46-0-lts           | 1         | 1.16%   |
| 5.4.27-0-lts           | 1         | 1.16%   |
| 5.4.0-77-generic       | 1         | 1.16%   |
| 5.19.0-50-generic      | 1         | 1.16%   |
| 5.19.0-35-generic      | 1         | 1.16%   |
| 5.17.9-0-edge          | 1         | 1.16%   |
| 5.17.0-0-edge          | 1         | 1.16%   |
| 5.16.12-may            | 1         | 1.16%   |
| 5.16.1-may             | 1         | 1.16%   |
| 5.15.96-0-lts          | 1         | 1.16%   |
| 5.15.95-0-lts          | 1         | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 3         | 3.57%   |
| 6.1.62  | 2         | 2.38%   |
| 5.4.83  | 2         | 2.38%   |
| 5.4.43  | 2         | 2.38%   |
| 5.15.86 | 2         | 2.38%   |
| 5.15.59 | 2         | 2.38%   |
| 5.15.47 | 2         | 2.38%   |
| 5.15.41 | 2         | 2.38%   |
| 5.15.4  | 2         | 2.38%   |
| 6.6.7   | 1         | 1.19%   |
| 6.6.4   | 1         | 1.19%   |
| 6.6.1   | 1         | 1.19%   |
| 6.4.4   | 1         | 1.19%   |
| 6.2.0   | 1         | 1.19%   |
| 6.1.69  | 1         | 1.19%   |
| 6.1.55  | 1         | 1.19%   |
| 6.1.53  | 1         | 1.19%   |
| 6.1.52  | 1         | 1.19%   |
| 6.1.46  | 1         | 1.19%   |
| 6.1.39  | 1         | 1.19%   |
| 6.1.34  | 1         | 1.19%   |
| 6.1.24  | 1         | 1.19%   |
| 6.1.11  | 1         | 1.19%   |
| 5.8.12  | 1         | 1.19%   |
| 5.7.4   | 1         | 1.19%   |
| 5.6.2   | 1         | 1.19%   |
| 5.4.84  | 1         | 1.19%   |
| 5.4.72  | 1         | 1.19%   |
| 5.4.64  | 1         | 1.19%   |
| 5.4.46  | 1         | 1.19%   |
| 5.4.27  | 1         | 1.19%   |
| 5.4.0   | 1         | 1.19%   |
| 5.19.0  | 1         | 1.19%   |
| 5.17.9  | 1         | 1.19%   |
| 5.17.0  | 1         | 1.19%   |
| 5.16.12 | 1         | 1.19%   |
| 5.16.1  | 1         | 1.19%   |
| 5.15.96 | 1         | 1.19%   |
| 5.15.95 | 1         | 1.19%   |
| 5.15.89 | 1         | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 37.8%   |
| 6.1     | 11        | 13.41%  |
| 5.10    | 11        | 13.41%  |
| 5.4     | 10        | 12.2%   |
| 6.6     | 3         | 3.66%   |
| 5.17    | 2         | 2.44%   |
| 5.14    | 2         | 2.44%   |
| 6.4     | 1         | 1.22%   |
| 6.2     | 1         | 1.22%   |
| 5.8     | 1         | 1.22%   |
| 5.7     | 1         | 1.22%   |
| 5.6     | 1         | 1.22%   |
| 5.19    | 1         | 1.22%   |
| 5.16    | 1         | 1.22%   |
| 5.13    | 1         | 1.22%   |
| 5.12    | 1         | 1.22%   |
| 4.4     | 1         | 1.22%   |
| 3.18    | 1         | 1.22%   |
| 3.10    | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 62        | 82.67%  |
| i686   | 10        | 13.33%  |
| armv7l | 2         | 2.67%   |
| i586   | 1         | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 73.33%  |
| XFCE    | 11        | 14.67%  |
| GNOME   | 4         | 5.33%   |
| LXQt    | 2         | 2.67%   |
| KDE5    | 2         | 2.67%   |
| sway    | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 36        | 46.75%  |
| Unknown | 34        | 44.16%  |
| Wayland | 7         | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 70.67%  |
| LightDM | 14        | 18.67%  |
| SDDM    | 3         | 4%      |
| LXDM    | 2         | 2.67%   |
| GDM     | 2         | 2.67%   |
| XDM     | 1         | 1.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 46        | 58.23%  |
| Unknown | 24        | 30.38%  |
| en_US   | 6         | 7.59%   |
| ru_RU   | 1         | 1.27%   |
| es_NI   | 1         | 1.27%   |
| en_GB   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 49        | 63.64%  |
| EFI  | 28        | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 79.49%  |
| Btrfs   | 7         | 8.97%   |
| Overlay | 4         | 5.13%   |
| Tmpfs   | 2         | 2.56%   |
| F2fs    | 1         | 1.28%   |
| Ext2    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 62.82%  |
| GPT     | 21        | 26.92%  |
| MBR     | 8         | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 90.91%  |
| Yes       | 7         | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 92.21%  |
| Yes       | 6         | 7.79%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 13        | 17.33%  |
| Lenovo           | 12        | 16%     |
| Dell             | 10        | 13.33%  |
| ASUSTek Computer | 10        | 13.33%  |
| Acer             | 6         | 8%      |
| Toshiba          | 3         | 4%      |
| IBM              | 3         | 4%      |
| Google           | 3         | 4%      |
| Fujitsu          | 2         | 2.67%   |
| Unknown          | 2         | 2.67%   |
| Synology         | 1         | 1.33%   |
| Sony             | 1         | 1.33%   |
| Pegatron         | 1         | 1.33%   |
| Olivetti         | 1         | 1.33%   |
| Notebook         | 1         | 1.33%   |
| MSI              | 1         | 1.33%   |
| LG Electronics   | 1         | 1.33%   |
| Haier            | 1         | 1.33%   |
| Gateway          | 1         | 1.33%   |
| Chuwi            | 1         | 1.33%   |
| Apple            | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 2.67%   |
| Toshiba WT8-A                            | 1         | 1.33%   |
| Toshiba Satellite Pro L50-A              | 1         | 1.33%   |
| Toshiba Satellite M645                   | 1         | 1.33%   |
| Synology DS1019+                         | 1         | 1.33%   |
| Sony VGN-UX27GN                          | 1         | 1.33%   |
| Pegatron Deepcam                         | 1         | 1.33%   |
| Olivetti Spring Peak                     | 1         | 1.33%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 1.33%   |
| MSI GL72M 7REX                           | 1         | 1.33%   |
| LG LW25-B7HG                             | 1         | 1.33%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.33%   |
| Lenovo V15 G3 IAP 82TT                   | 1         | 1.33%   |
| Lenovo V14-ADA 82C6                      | 1         | 1.33%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 1.33%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.33%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.33%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.33%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 1.33%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.33%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.33%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.33%   |
| Lenovo Flex 2-14 20404                   | 1         | 1.33%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 1.33%   |
| IBM 26446AG                              | 1         | 1.33%   |
| IBM 264070A                              | 1         | 1.33%   |
| HP ZBook 15 G5                           | 1         | 1.33%   |
| HP ProBook 4310s                         | 1         | 1.33%   |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 1.33%   |
| HP Presario V2000 (ES307UA#ABL)          | 1         | 1.33%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 1.33%   |
| HP Mini 110-3500                         | 1         | 1.33%   |
| HP Laptop 17-cp0xxx                      | 1         | 1.33%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.33%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.33%   |
| HP EliteBook 8460p                       | 1         | 1.33%   |
| HP EliteBook 2740p                       | 1         | 1.33%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 1.33%   |
| HP Compaq Mini CQ10-600                  | 1         | 1.33%   |
| Haier U144S                              | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 7         | 9.33%   |
| Dell Inspiron     | 6         | 8%      |
| Acer Aspire       | 6         | 8%      |
| HP EliteBook      | 3         | 4%      |
| Toshiba Satellite | 2         | 2.67%   |
| HP Presario       | 2         | 2.67%   |
| HP Laptop         | 2         | 2.67%   |
| Dell Latitude     | 2         | 2.67%   |
| Unknown           | 2         | 2.67%   |
| Toshiba WT8-A     | 1         | 1.33%   |
| Synology DS1019+  | 1         | 1.33%   |
| Sony VGN-UX27GN   | 1         | 1.33%   |
| Pegatron Deepcam  | 1         | 1.33%   |
| Olivetti Spring   | 1         | 1.33%   |
| Notebook NV4XMB   | 1         | 1.33%   |
| MSI GL72M         | 1         | 1.33%   |
| LG LW25-B7HG      | 1         | 1.33%   |
| Lenovo Yoga       | 1         | 1.33%   |
| Lenovo V15        | 1         | 1.33%   |
| Lenovo V14-ADA    | 1         | 1.33%   |
| Lenovo IdeaPad    | 1         | 1.33%   |
| Lenovo Flex       | 1         | 1.33%   |
| IBM ThinkPad      | 1         | 1.33%   |
| IBM 26446AG       | 1         | 1.33%   |
| IBM 264070A       | 1         | 1.33%   |
| HP ZBook          | 1         | 1.33%   |
| HP ProBook        | 1         | 1.33%   |
| HP Pavilion       | 1         | 1.33%   |
| HP Mini           | 1         | 1.33%   |
| HP ENVY           | 1         | 1.33%   |
| HP Compaq         | 1         | 1.33%   |
| Haier U144S       | 1         | 1.33%   |
| Google Samus      | 1         | 1.33%   |
| Google Leona      | 1         | 1.33%   |
| Google Kefka      | 1         | 1.33%   |
| Gateway MX3631m   | 1         | 1.33%   |
| Fujitsu LIFEBOOK  | 1         | 1.33%   |
| Fujitsu FMVNP8AE  | 1         | 1.33%   |
| Dell XPS          | 1         | 1.33%   |
| Dell Studio       | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 8         | 10.67%  |
| 2014    | 8         | 10.67%  |
| 2012    | 7         | 9.33%   |
| 2018    | 6         | 8%      |
| 2010    | 6         | 8%      |
| 2006    | 6         | 8%      |
| 2021    | 5         | 6.67%   |
| 2017    | 3         | 4%      |
| 2016    | 3         | 4%      |
| 2013    | 3         | 4%      |
| 2011    | 3         | 4%      |
| Unknown | 3         | 4%      |
| 2022    | 2         | 2.67%   |
| 2020    | 2         | 2.67%   |
| 2015    | 2         | 2.67%   |
| 2009    | 2         | 2.67%   |
| 2005    | 2         | 2.67%   |
| 2023    | 1         | 1.33%   |
| 2008    | 1         | 1.33%   |
| 2007    | 1         | 1.33%   |
| 1999    | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 75        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 74        | 97.37%  |
| Enabled  | 2         | 2.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 72        | 96%     |
| Yes  | 3         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 21        | 26.25%  |
| 3.01-4.0        | 14        | 17.5%   |
| 8.01-16.0       | 11        | 13.75%  |
| 16.01-24.0      | 8         | 10%     |
| 1.01-2.0        | 7         | 8.75%   |
| 0.51-1.0        | 7         | 8.75%   |
| 32.01-64.0      | 5         | 6.25%   |
| 2.01-3.0        | 3         | 3.75%   |
| 0.01-0.5        | 2         | 2.5%    |
| More than 256.0 | 1         | 1.25%   |
| 64.01-256.0     | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 24        | 30%     |
| 1.01-2.0  | 17        | 21.25%  |
| 2.01-3.0  | 11        | 13.75%  |
| 0.51-1.0  | 11        | 13.75%  |
| 4.01-8.0  | 8         | 10%     |
| 3.01-4.0  | 4         | 5%      |
| 8.01-16.0 | 2         | 2.5%    |
| 0         | 2         | 2.5%    |
| Unknown   | 1         | 1.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 73.42%  |
| 2      | 16        | 20.25%  |
| 0      | 2         | 2.53%   |
| 7      | 1         | 1.27%   |
| 5      | 1         | 1.27%   |
| 3      | 1         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 71.43%  |
| Yes       | 22        | 28.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 78.67%  |
| No        | 16        | 21.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 88.31%  |
| No        | 9         | 11.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 61.04%  |
| No        | 30        | 38.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 18        | 21.95%  |
| Canada       | 9         | 10.98%  |
| Russia       | 6         | 7.32%   |
| Germany      | 6         | 7.32%   |
| UK           | 5         | 6.1%    |
| Brazil       | 5         | 6.1%    |
| Spain        | 4         | 4.88%   |
| Slovakia     | 2         | 2.44%   |
| Italy        | 2         | 2.44%   |
| Israel       | 2         | 2.44%   |
| Australia    | 2         | 2.44%   |
| Venezuela    | 1         | 1.22%   |
| UAE          | 1         | 1.22%   |
| Sweden       | 1         | 1.22%   |
| South Korea  | 1         | 1.22%   |
| South Africa | 1         | 1.22%   |
| Portugal     | 1         | 1.22%   |
| Poland       | 1         | 1.22%   |
| Philippines  | 1         | 1.22%   |
| Nicaragua    | 1         | 1.22%   |
| Netherlands  | 1         | 1.22%   |
| Mexico       | 1         | 1.22%   |
| Kenya        | 1         | 1.22%   |
| Jamaica      | 1         | 1.22%   |
| Hungary      | 1         | 1.22%   |
| Guatemala    | 1         | 1.22%   |
| Greece       | 1         | 1.22%   |
| France       | 1         | 1.22%   |
| Egypt        | 1         | 1.22%   |
| Czechia      | 1         | 1.22%   |
| China        | 1         | 1.22%   |
| Austria      | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vernon           | 3         | 3.61%   |
| St Petersburg    | 3         | 3.61%   |
| Springfield      | 3         | 3.61%   |
| Stratford        | 2         | 2.41%   |
| Moscow           | 2         | 2.41%   |
| Manitowoc        | 2         | 2.41%   |
| Fulham           | 2         | 2.41%   |
| Zhangzhou        | 1         | 1.2%    |
| Vienna           | 1         | 1.2%    |
| Tymovskoye       | 1         | 1.2%    |
| Turin            | 1         | 1.2%    |
| Thornhill        | 1         | 1.2%    |
| Tampa            | 1         | 1.2%    |
| Sydney           | 1         | 1.2%    |
| Stewartstown     | 1         | 1.2%    |
| Sisteron         | 1         | 1.2%    |
| Semily           | 1         | 1.2%    |
| Seattle          | 1         | 1.2%    |
| Sao Paulo        | 1         | 1.2%    |
| San Mateo        | 1         | 1.2%    |
| Saarbrücken     | 1         | 1.2%    |
| Rzeszów         | 1         | 1.2%    |
| Rostock          | 1         | 1.2%    |
| Ramat Gan        | 1         | 1.2%    |
| Purdys           | 1         | 1.2%    |
| Olofstorp        | 1         | 1.2%    |
| Oakville         | 1         | 1.2%    |
| Northampton      | 1         | 1.2%    |
| Nairobi          | 1         | 1.2%    |
| Montreal         | 1         | 1.2%    |
| Merrill          | 1         | 1.2%    |
| Mérida          | 1         | 1.2%    |
| Manila           | 1         | 1.2%    |
| Managua          | 1         | 1.2%    |
| Madrid           | 1         | 1.2%    |
| Lindavista Norte | 1         | 1.2%    |
| Lincoln          | 1         | 1.2%    |
| Leipzig          | 1         | 1.2%    |
| Lauro de Freitas | 1         | 1.2%    |
| Larkspur         | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 11        | 23     | 10.68%  |
| Toshiba                     | 9         | 12     | 8.74%   |
| Unknown                     | 8         | 10     | 7.77%   |
| Seagate                     | 8         | 19     | 7.77%   |
| Hitachi                     | 8         | 8      | 7.77%   |
| WDC                         | 7         | 11     | 6.8%    |
| Kingston                    | 7         | 11     | 6.8%    |
| HGST                        | 6         | 6      | 5.83%   |
| SanDisk                     | 4         | 4      | 3.88%   |
| Crucial                     | 4         | 4      | 3.88%   |
| SK hynix                    | 3         | 3      | 2.91%   |
| Micron Technology           | 3         | 3      | 2.91%   |
| Intel                       | 3         | 5      | 2.91%   |
| A-DATA Technology           | 3         | 4      | 2.91%   |
| SPCC                        | 2         | 2      | 1.94%   |
| Fujitsu                     | 2         | 2      | 1.94%   |
| SINTECHI                    | 1         | 1      | 0.97%   |
| Secure                      | 1         | 1      | 0.97%   |
| Netac                       | 1         | 1      | 0.97%   |
| LITEON                      | 1         | 1      | 0.97%   |
| Kingston Technology Company | 1         | 1      | 0.97%   |
| KC600                       | 1         | 1      | 0.97%   |
| JMicron Technology          | 1         | 1      | 0.97%   |
| Intenso                     | 1         | 1      | 0.97%   |
| INNOVATION IT               | 1         | 1      | 0.97%   |
| IBM                         | 1         | 1      | 0.97%   |
| Emtec                       | 1         | 1      | 0.97%   |
| Dell                        | 1         | 2      | 0.97%   |
| China                       | 1         | 1      | 0.97%   |
| Aura                        | 1         | 1      | 0.97%   |
| AMD                         | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                      | 3         | 2.38%   |
| Unknown MMC Card  64GB                      | 2         | 1.59%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 1.59%   |
| Toshiba MQ01ABD075 752GB                    | 2         | 1.59%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 2         | 1.59%   |
| Samsung NVMe SSD Drive 1024GB               | 2         | 1.59%   |
| Kingston SV300S37A120G 120GB SSD            | 2         | 1.59%   |
| Crucial CT500MX500SSD1 500GB                | 2         | 1.59%   |
| WDC WDS500G2X0C-00L350 500GB                | 1         | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD            | 1         | 0.79%   |
| WDC WDS500G2B0A 500GB SSD                   | 1         | 0.79%   |
| WDC WDS250G2B0A 250GB SSD                   | 1         | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 0.79%   |
| WDC WD5000BEVT-7 500GB                      | 1         | 0.79%   |
| WDC WD5000BEVT-22ZAT0 500GB                 | 1         | 0.79%   |
| WDC WD10SPZX-60Z10T1 1TB                    | 1         | 0.79%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB        | 1         | 0.79%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB        | 1         | 0.79%   |
| Unknown SD32G  32GB                         | 1         | 0.79%   |
| Unknown NVMe SSD Drive 1024GB               | 1         | 0.79%   |
| Unknown MMC Card  32GB                      | 1         | 0.79%   |
| Unknown MMC Card                            | 1         | 0.79%   |
| Toshiba NVMe SSD Drive 256GB                | 1         | 0.79%   |
| Toshiba MQ04ABF1 1TB                        | 1         | 0.79%   |
| Toshiba MQ01ABD1 1TB                        | 1         | 0.79%   |
| Toshiba MK6008GAH 64GB                      | 1         | 0.79%   |
| Toshiba MK4009GAL 40GB                      | 1         | 0.79%   |
| Toshiba KXG5AZNV256G 256GB                  | 1         | 0.79%   |
| Toshiba HDWL110 1TB                         | 1         | 0.79%   |
| Toshiba DT01ACA1 1TB                        | 1         | 0.79%   |
| SPCC Solid State Disk 256GB                 | 1         | 0.79%   |
| SPCC Solid State 120GB                      | 1         | 0.79%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB   | 1         | 0.79%   |
| SINTECHI HighSpeed SD to CF Adapter V1.0    | 1         | 0.79%   |
| Secure Net 256GB SSD                        | 1         | 0.79%   |
| Seagate ST98823A 80GB                       | 1         | 0.79%   |
| Seagate ST9250315AS 250GB                   | 1         | 0.79%   |
| Seagate ST9160314AS 40GB                    | 1         | 0.79%   |
| Seagate ST8000VN004-2M2101 8TB              | 1         | 0.79%   |
| Seagate ST6000DM003-2CY1 6TB                | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 10     | 21.05%  |
| Seagate             | 8         | 19     | 21.05%  |
| Hitachi             | 8         | 8      | 21.05%  |
| HGST                | 6         | 6      | 15.79%  |
| WDC                 | 3         | 3      | 7.89%   |
| Fujitsu             | 2         | 2      | 5.26%   |
| SINTECHI            | 1         | 1      | 2.63%   |
| Samsung Electronics | 1         | 2      | 2.63%   |
| IBM                 | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 9      | 20%     |
| Crucial             | 4         | 4      | 11.43%  |
| WDC                 | 3         | 4      | 8.57%   |
| Samsung Electronics | 3         | 9      | 8.57%   |
| SPCC                | 2         | 2      | 5.71%   |
| SanDisk             | 2         | 2      | 5.71%   |
| Secure              | 1         | 1      | 2.86%   |
| Netac               | 1         | 1      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| LITEON              | 1         | 1      | 2.86%   |
| KC600               | 1         | 1      | 2.86%   |
| JMicron Technology  | 1         | 1      | 2.86%   |
| Intenso             | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| INNOVATION IT       | 1         | 1      | 2.86%   |
| Emtec               | 1         | 1      | 2.86%   |
| Dell                | 1         | 2      | 2.86%   |
| China               | 1         | 1      | 2.86%   |
| AMD                 | 1         | 1      | 2.86%   |
| A-DATA Technology   | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 35        | 52     | 41.18%  |
| SSD     | 24        | 45     | 28.24%  |
| NVMe    | 18        | 37     | 21.18%  |
| MMC     | 7         | 8      | 8.24%   |
| Unknown | 1         | 1      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 55        | 93     | 65.48%  |
| NVMe | 18        | 37     | 21.43%  |
| MMC  | 7         | 8      | 8.33%   |
| SAS  | 4         | 5      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 61     | 67.19%  |
| 0.51-1.0   | 14        | 19     | 21.88%  |
| 1.01-2.0   | 3         | 4      | 4.69%   |
| 3.01-4.0   | 2         | 2      | 3.13%   |
| 4.01-10.0  | 2         | 11     | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 24.05%  |
| 1-20           | 16        | 20.25%  |
| Unknown        | 10        | 12.66%  |
| 251-500        | 9         | 11.39%  |
| 21-50          | 7         | 8.86%   |
| 501-1000       | 6         | 7.59%   |
| 1001-2000      | 4         | 5.06%   |
| More than 3000 | 3         | 3.8%    |
| 51-100         | 3         | 3.8%    |
| 2001-3000      | 2         | 2.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 50        | 63.29%  |
| Unknown   | 10        | 12.66%  |
| 21-50     | 6         | 7.59%   |
| 51-100    | 4         | 5.06%   |
| 251-500   | 3         | 3.8%    |
| 101-250   | 3         | 3.8%    |
| 501-1000  | 2         | 2.53%   |
| 2001-3000 | 1         | 1.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 7.14%   |
| Secure Net 256GB SSD                           | 1         | 1      | 7.14%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 7.14%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 7.14%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 7.14%   |
| Netac SSD 256GB                                | 1         | 1      | 7.14%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 7.14%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 7.14%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 7.14%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 7.14%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 7.14%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 7.14%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 7.14%   |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 28.57%  |
| Seagate             | 2         | 2      | 14.29%  |
| HGST                | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Secure              | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 2      | 7.14%   |
| Netac               | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

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
| HDD  | 10        | 11     | 76.92%  |
| SSD  | 2         | 3      | 15.38%  |
| NVMe | 1         | 1      | 7.69%   |

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
| Works    | 46        | 96     | 55.42%  |
| Detected | 25        | 32     | 30.12%  |
| Malfunc  | 12        | 15     | 14.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 53        | 58.89%  |
| AMD                          | 12        | 13.33%  |
| Samsung Electronics          | 8         | 8.89%   |
| SanDisk                      | 4         | 4.44%   |
| SK hynix                     | 3         | 3.33%   |
| ADATA Technology             | 3         | 3.33%   |
| Micron Technology            | 2         | 2.22%   |
| Toshiba America Info Systems | 1         | 1.11%   |
| Nvidia                       | 1         | 1.11%   |
| Marvell Technology Group     | 1         | 1.11%   |
| Kingston Technology Company  | 1         | 1.11%   |
| Broadcom / LSI               | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 9.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 3.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.61%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 2.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 2.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 2.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 2.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.61%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.74%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.74%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.74%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.87%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.87%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 0.87%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.87%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.87%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.87%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 0.87%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1         | 0.87%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1         | 0.87%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 1         | 0.87%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1         | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.87%   |
| Intel SSD 600P Series                                                          | 1         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 58.82%  |
| NVMe | 18        | 21.18%  |
| IDE  | 12        | 14.12%  |
| RAID | 5         | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 79.22%  |
| AMD    | 14        | 18.18%  |
| ARM    | 2         | 2.6%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz       | 2         | 2.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 2.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 2.44%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 2.44%   |
| Intel Atom CPU N455 @ 1.66GHz           | 2         | 2.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.44%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1         | 1.22%   |
| Intel Xeon E-2176M CPU @ 2.70GHz        | 1         | 1.22%   |
| Intel Pentium M processor 1.60GHz       | 1         | 1.22%   |
| Intel Pentium M processor 1.50GHz       | 1         | 1.22%   |
| Intel Pentium III (Coppermine)          | 1         | 1.22%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.22%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 1.22%   |
| Intel Mobile Pentium MMX                | 1         | 1.22%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 1.22%   |
| Intel Core Solo CPU U1500 @ 1.33GHz     | 1         | 1.22%   |
| Intel Core m3-8100Y CPU @ 1.10GHz       | 1         | 1.22%   |
| Intel Core i9-9980HK CPU @ 2.40GHz      | 1         | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 1.22%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.22%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz       | 1         | 1.22%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.22%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.22%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.22%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 1         | 1.22%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.22%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 1.22%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz      | 1         | 1.22%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 1         | 1.22%   |
| Intel Core i5 CPU M 480 @ 2.67GHz       | 1         | 1.22%   |
| Intel Core i3-7130U CPU @ 2.70GHz       | 1         | 1.22%   |
| Intel Core i3-5020U CPU @ 2.20GHz       | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 18        | 22.5%   |
| Other                | 9         | 11.25%  |
| Intel Core i3        | 6         | 7.5%    |
| Intel Celeron        | 6         | 7.5%    |
| Intel Atom           | 6         | 7.5%    |
| Intel Pentium M      | 4         | 5%      |
| Intel Core i7        | 4         | 5%      |
| Intel Core 2 Duo     | 3         | 3.75%   |
| AMD Ryzen 5          | 3         | 3.75%   |
| Intel Pentium        | 2         | 2.5%    |
| AMD Ryzen 7          | 2         | 2.5%    |
| AMD A4               | 2         | 2.5%    |
| Intel Xeon Gold      | 1         | 1.25%   |
| Intel Xeon           | 1         | 1.25%   |
| Intel Pentium III    | 1         | 1.25%   |
| Intel Genuine        | 1         | 1.25%   |
| Intel Core Solo      | 1         | 1.25%   |
| Intel Core m3        | 1         | 1.25%   |
| Intel Core i9        | 1         | 1.25%   |
| Intel Core 2         | 1         | 1.25%   |
| ARM ARMv7            | 1         | 1.25%   |
| AMD Turion 64 Mobile | 1         | 1.25%   |
| AMD Ryzen 3          | 1         | 1.25%   |
| AMD FX               | 1         | 1.25%   |
| AMD E2               | 1         | 1.25%   |
| AMD A6               | 1         | 1.25%   |
| AMD A10              | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 37        | 46.84%  |
| 4       | 20        | 25.32%  |
| 1       | 12        | 15.19%  |
| 6       | 3         | 3.8%    |
| 8       | 2         | 2.53%   |
| 32      | 1         | 1.27%   |
| 16      | 1         | 1.27%   |
| 14      | 1         | 1.27%   |
| 3       | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 74        | 97.37%  |
| 2       | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 39        | 52%     |
| 1       | 35        | 46.67%  |
| Unknown | 1         | 1.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 41        | 53.25%  |
| 32-bit, 64-bit | 33        | 42.86%  |
| 32-bit         | 3         | 3.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 54.88%  |
| 0x306a9    | 3         | 3.66%   |
| 0x30678    | 3         | 3.66%   |
| 0x106ca    | 3         | 3.66%   |
| 0x906ea    | 2         | 2.44%   |
| 0x806eb    | 2         | 2.44%   |
| 0x806c1    | 2         | 2.44%   |
| 0x206a7    | 2         | 2.44%   |
| 0x08108102 | 2         | 2.44%   |
| 0x06006704 | 2         | 2.44%   |
| 0xa0671    | 1         | 1.22%   |
| 0x906a3    | 1         | 1.22%   |
| 0x806ec    | 1         | 1.22%   |
| 0x806ea    | 1         | 1.22%   |
| 0x706e5    | 1         | 1.22%   |
| 0x683      | 1         | 1.22%   |
| 0x506c9    | 1         | 1.22%   |
| 0x406c4    | 1         | 1.22%   |
| 0x306d4    | 1         | 1.22%   |
| 0x306c3    | 1         | 1.22%   |
| 0x20655    | 1         | 1.22%   |
| 0x106e5    | 1         | 1.22%   |
| 0x1067a    | 1         | 1.22%   |
| 0x08608103 | 1         | 1.22%   |
| 0x08108109 | 1         | 1.22%   |
| 0x0810100b | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 13.75%  |
| P6               | 7         | 8.75%   |
| Silvermont       | 6         | 7.5%    |
| Unknown          | 5         | 6.25%   |
| IvyBridge        | 4         | 5%      |
| Haswell          | 4         | 5%      |
| Goldmont         | 4         | 5%      |
| Bonnell          | 4         | 5%      |
| Zen+             | 3         | 3.75%   |
| Westmere         | 3         | 3.75%   |
| TigerLake        | 3         | 3.75%   |
| SandyBridge      | 3         | 3.75%   |
| Penryn           | 3         | 3.75%   |
| Excavator        | 3         | 3.75%   |
| Broadwell        | 3         | 3.75%   |
| Skylake          | 2         | 2.5%    |
| Alderlake Hybrid | 2         | 2.5%    |
| Zen 2            | 1         | 1.25%   |
| Zen              | 1         | 1.25%   |
| Puma             | 1         | 1.25%   |
| Piledriver       | 1         | 1.25%   |
| Nehalem          | 1         | 1.25%   |
| K8 Hammer        | 1         | 1.25%   |
| Jaguar           | 1         | 1.25%   |
| IceLake          | 1         | 1.25%   |
| Core             | 1         | 1.25%   |
| Bobcat           | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 55        | 63.22%  |
| AMD                        | 20        | 22.99%  |
| Nvidia                     | 9         | 10.34%  |
| Neomagic                   | 2         | 2.3%    |
| Matrox Electronics Systems | 1         | 1.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.54%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.65%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 2.65%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 2.65%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.65%   |
| Intel HD Graphics 500                                                                    | 3         | 2.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.77%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.77%   |
| Intel HD Graphics 630                                                                    | 2         | 1.77%   |
| Intel HD Graphics 620                                                                    | 2         | 1.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.77%   |
| AMD Lucienne                                                                             | 2         | 1.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.88%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.88%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.88%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.88%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.88%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 0.88%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.88%   |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 0.88%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 1         | 0.88%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 39        | 48.75%  |
| 1 x AMD         | 15        | 18.75%  |
| 2 x Intel       | 7         | 8.75%   |
| Intel + Nvidia  | 7         | 8.75%   |
| Intel + AMD     | 4         | 5%      |
| Other           | 2         | 2.5%    |
| 1 x Neomagic    | 2         | 2.5%    |
| 2 x AMD         | 1         | 1.25%   |
| Nvidia + Matrox | 1         | 1.25%   |
| 1 x Nvidia      | 1         | 1.25%   |
| AMD + Nvidia    | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 89.74%  |
| Unknown     | 5         | 6.41%   |
| Proprietary | 3         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 85.71%  |
| 0.01-0.5   | 5         | 6.49%   |
| 1.01-2.0   | 3         | 3.9%    |
| 3.01-4.0   | 1         | 1.3%    |
| 2.01-3.0   | 1         | 1.3%    |
| 0.51-1.0   | 1         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 18.82%  |
| LG Display              | 12        | 14.12%  |
| BOE                     | 11        | 12.94%  |
| Chimei Innolux          | 8         | 9.41%   |
| Samsung Electronics     | 4         | 4.71%   |
| LG Philips              | 3         | 3.53%   |
| InfoVision              | 3         | 3.53%   |
| Chi Mei Optoelectronics | 3         | 3.53%   |
| PANDA                   | 2         | 2.35%   |
| Lenovo                  | 2         | 2.35%   |
| HannStar                | 2         | 2.35%   |
| Goldstar                | 2         | 2.35%   |
| Vizio                   | 1         | 1.18%   |
| Sharp                   | 1         | 1.18%   |
| Sceptre Tech            | 1         | 1.18%   |
| Quanta Display          | 1         | 1.18%   |
| Philips                 | 1         | 1.18%   |
| ONN                     | 1         | 1.18%   |
| KVM                     | 1         | 1.18%   |
| Envision                | 1         | 1.18%   |
| Element                 | 1         | 1.18%   |
| DENON                   | 1         | 1.18%   |
| Dell                    | 1         | 1.18%   |
| CSO                     | 1         | 1.18%   |
| CPT                     | 1         | 1.18%   |
| CHD                     | 1         | 1.18%   |
| BenQ                    | 1         | 1.18%   |
| Apple                   | 1         | 1.18%   |
| Acer                    | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 2.06%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 2.06%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                  | 1         | 1.03%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 1.03%   |
| Sceptre Tech Sceptre C24 SPT09AB 1920x1080 530x300mm 24.0-inch        | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch  | 1         | 1.03%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 1.03%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 1.03%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 1.03%   |
| PANDA LCD Monitor NCP0056 1920x1080 309x174mm 14.0-inch               | 1         | 1.03%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 1.03%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 1.03%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 1.03%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 1.03%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.03%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 1.03%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 1.03%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 1.03%   |
| KVM LCD Monitor191919 KVM4308 1280x1024 376x301mm 19.0-inch           | 1         | 1.03%   |
| InfoVision M116NWR1 R0 IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 1.03%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch           | 1         | 1.03%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 1.03%   |
| Goldstar ULTRAWIDE GSM5AE2 3440x1440 800x335mm 34.1-inch              | 1         | 1.03%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 1         | 1.03%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.03%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                 | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 26        | 32.5%   |
| 1920x1080 (FHD)    | 19        | 23.75%  |
| 1280x800 (WXGA)    | 6         | 7.5%    |
| 1600x900 (HD+)     | 4         | 5%      |
| 1024x600           | 4         | 5%      |
| 3840x2160 (4K)     | 3         | 3.75%   |
| 2560x1440 (QHD)    | 3         | 3.75%   |
| 2560x1080          | 2         | 2.5%    |
| 1920x1200 (WUXGA)  | 2         | 2.5%    |
| 1280x768           | 2         | 2.5%    |
| 1280x1024 (SXGA)   | 2         | 2.5%    |
| 3440x1440          | 1         | 1.25%   |
| 2880x1800          | 1         | 1.25%   |
| 2560x1700          | 1         | 1.25%   |
| 1680x1050 (WSXGA+) | 1         | 1.25%   |
| 1440x900 (WXGA+)   | 1         | 1.25%   |
| 1360x768           | 1         | 1.25%   |
| 1024x768 (XGA)     | 1         | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 29.41%  |
| 14     | 13        | 15.29%  |
| 13     | 10        | 11.76%  |
| 17     | 6         | 7.06%   |
| 11     | 5         | 5.88%   |
| 12     | 4         | 4.71%   |
| 10     | 4         | 4.71%   |
| 32     | 2         | 2.35%   |
| 31     | 2         | 2.35%   |
| 72     | 1         | 1.18%   |
| 60     | 1         | 1.18%   |
| 40     | 1         | 1.18%   |
| 34     | 1         | 1.18%   |
| 29     | 1         | 1.18%   |
| 27     | 1         | 1.18%   |
| 25     | 1         | 1.18%   |
| 24     | 1         | 1.18%   |
| 23     | 1         | 1.18%   |
| 22     | 1         | 1.18%   |
| 21     | 1         | 1.18%   |
| 20     | 1         | 1.18%   |
| 19     | 1         | 1.18%   |
| 16     | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 57.69%  |
| 201-300     | 16        | 20.51%  |
| 351-400     | 6         | 7.69%   |
| 601-700     | 4         | 5.13%   |
| 701-800     | 2         | 2.56%   |
| 801-900     | 1         | 1.28%   |
| 501-600     | 1         | 1.28%   |
| 401-500     | 1         | 1.28%   |
| 1501-2000   | 1         | 1.28%   |
| 1001-1500   | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 55        | 77.46%  |
| 16/10 | 10        | 14.08%  |
| 5/4   | 2         | 2.82%   |
| 21/9  | 2         | 2.82%   |
| 4/3   | 1         | 1.41%   |
| 3/2   | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 31.65%  |
| 81-90          | 20        | 25.32%  |
| 51-60          | 5         | 6.33%   |
| 71-80          | 4         | 5.06%   |
| 351-500        | 4         | 5.06%   |
| 41-50          | 4         | 5.06%   |
| 121-130        | 4         | 5.06%   |
| 61-70          | 3         | 3.8%    |
| More than 1000 | 2         | 2.53%   |
| 301-350        | 2         | 2.53%   |
| 251-300        | 1         | 1.27%   |
| 201-250        | 1         | 1.27%   |
| 151-200        | 1         | 1.27%   |
| 141-150        | 1         | 1.27%   |
| 131-140        | 1         | 1.27%   |
| 501-1000       | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 29        | 39.73%  |
| 101-120       | 26        | 35.62%  |
| 51-100        | 11        | 15.07%  |
| 1-50          | 3         | 4.11%   |
| More than 240 | 2         | 2.74%   |
| 161-240       | 2         | 2.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 63        | 80.77%  |
| 2     | 7         | 8.97%   |
| 0     | 7         | 8.97%   |
| 3     | 1         | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 45        | 34.88%  |
| Intel                           | 39        | 30.23%  |
| Qualcomm Atheros                | 18        | 13.95%  |
| Broadcom                        | 10        | 7.75%   |
| Marvell Technology Group        | 3         | 2.33%   |
| LSI                             | 2         | 1.55%   |
| Broadcom Limited                | 2         | 1.55%   |
| TP-Link                         | 1         | 0.78%   |
| Qualcomm Atheros Communications | 1         | 0.78%   |
| Qualcomm                        | 1         | 0.78%   |
| NetGear                         | 1         | 0.78%   |
| MediaTek                        | 1         | 0.78%   |
| Google                          | 1         | 0.78%   |
| Dresden Elektronik              | 1         | 0.78%   |
| DisplayLink                     | 1         | 0.78%   |
| ASIX Electronics                | 1         | 0.78%   |
| AMD                             | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 14.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.23%   |
| Intel Wireless-AC 9260                                            | 2         | 1.23%   |
| Intel Wireless 7265                                               | 2         | 1.23%   |
| Intel Wireless 3160                                               | 2         | 1.23%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.23%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.23%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 2         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.23%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 2         | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.62%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.62%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.62%   |
| Qualcomm CAPE-MTP _SN:14677F87                                    | 1         | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 46.67%  |
| Qualcomm Atheros                | 17        | 22.67%  |
| Realtek Semiconductor           | 8         | 10.67%  |
| Broadcom                        | 8         | 10.67%  |
| Broadcom Limited                | 2         | 2.67%   |
| TP-Link                         | 1         | 1.33%   |
| Qualcomm Atheros Communications | 1         | 1.33%   |
| NetGear                         | 1         | 1.33%   |
| MediaTek                        | 1         | 1.33%   |
| Marvell Technology Group        | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 9         | 11.11%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 4.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 3.7%    |
| Intel Wireless 8265 / 8275                                                     | 3         | 3.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                                | 3         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.47%   |
| Intel Wireless-AC 9260                                                         | 2         | 2.47%   |
| Intel Wireless 7265                                                            | 2         | 2.47%   |
| Intel Wireless 3160                                                            | 2         | 2.47%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 2.47%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 2.47%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 2         | 2.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 2         | 2.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 1         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 1.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 1.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 1.23%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.23%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.23%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.23%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.23%   |
| Intel Wireless 8260                                                            | 1         | 1.23%   |
| Intel Wireless 7260                                                            | 1         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.23%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 1.23%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.23%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 59.7%   |
| Intel                    | 14        | 20.9%   |
| Broadcom                 | 4         | 5.97%   |
| Qualcomm Atheros         | 3         | 4.48%   |
| Marvell Technology Group | 2         | 2.99%   |
| Qualcomm                 | 1         | 1.49%   |
| LSI                      | 1         | 1.49%   |
| DisplayLink              | 1         | 1.49%   |
| ASIX Electronics         | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 23        | 31.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 10        | 13.51%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 5         | 6.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 3         | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 4.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                             | 2         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                                 | 2         | 2.7%    |
| Intel 82579V Gigabit Network Connection                               | 2         | 2.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                 | 1         | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                     | 1         | 1.35%   |
| Qualcomm CAPE-MTP _SN:14677F87                                        | 1         | 1.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 1         | 1.35%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller               | 1         | 1.35%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                  | 1         | 1.35%   |
| LSI ET-131x PCI-E Ethernet Controller                                 | 1         | 1.35%   |
| Intel WiMAX Connection 2400m                                          | 1         | 1.35%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.35%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.35%   |
| Intel Ethernet Connection (2) I219-V                                  | 1         | 1.35%   |
| Intel Ethernet Connection (17) I219-LM                                | 1         | 1.35%   |
| Intel Ethernet Connection (13) I219-LM                                | 1         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.35%   |
| Intel 82567LM Gigabit Network Connection                              | 1         | 1.35%   |
| Intel 82541GI Gigabit Ethernet Controller                             | 1         | 1.35%   |
| DisplayLink Dell D3100 Docking Station                                | 1         | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                     | 1         | 1.35%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                 | 1         | 1.35%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                | 1         | 1.35%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.35%   |
| Broadcom BCM4401-B0 100Base-TX                                        | 1         | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1         | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 68        | 51.13%  |
| Ethernet | 58        | 43.61%  |
| Modem    | 7         | 5.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 66.67%  |
| Ethernet | 25        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 52        | 68.42%  |
| 1     | 19        | 25%     |
| 0     | 5         | 6.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 84.21%  |
| Yes  | 12        | 15.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 38.18%  |
| Realtek Semiconductor           | 5         | 9.09%   |
| Qualcomm Atheros Communications | 5         | 9.09%   |
| IMC Networks                    | 4         | 7.27%   |
| Broadcom                        | 4         | 7.27%   |
| Lite-On Technology              | 3         | 5.45%   |
| Foxconn / Hon Hai               | 2         | 3.64%   |
| ASUSTek Computer                | 2         | 3.64%   |
| Apple                           | 2         | 3.64%   |
| Toshiba                         | 1         | 1.82%   |
| Marvell Semiconductor           | 1         | 1.82%   |
| Hewlett-Packard                 | 1         | 1.82%   |
| Edimax Technology               | 1         | 1.82%   |
| Dell                            | 1         | 1.82%   |
| Cambridge Silicon Radio         | 1         | 1.82%   |
| Alps Electric                   | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 8.93%   |
| Realtek Bluetooth Radio                             | 4         | 7.14%   |
| Intel Bluetooth Device                              | 4         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.57%   |
| Intel AX200 Bluetooth                               | 2         | 3.57%   |
| Toshiba Bluetooth Device                            | 1         | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.79%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.79%   |
| Intel AX210 Bluetooth                               | 1         | 1.79%   |
| IMC Networks Wireless_Device                        | 1         | 1.79%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.79%   |
| IMC Networks Bluetooth Device                       | 1         | 1.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.79%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.79%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.79%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.79%   |
| Edimax Edimax Bluetooth Adapter                     | 1         | 1.79%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.79%   |
| Broadcom BCM20702A0                                 | 1         | 1.79%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.79%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.79%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.79%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.79%   |
| Apple Bluetooth Host Controller                     | 1         | 1.79%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 57        | 68.67%  |
| AMD                       | 16        | 19.28%  |
| Nvidia                    | 3         | 3.61%   |
| Texas Instruments         | 1         | 1.2%    |
| SteelSeries ApS           | 1         | 1.2%    |
| Sennheiser Communications | 1         | 1.2%    |
| Realtek Semiconductor     | 1         | 1.2%    |
| Logitech                  | 1         | 1.2%    |
| Focusrite-Novation        | 1         | 1.2%    |
| Cirrus Logic              | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 5.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 4.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 3.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 3.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.46%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.46%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.46%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.64%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.64%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.64%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.82%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.82%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 0.82%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.82%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia Audio device                                                                               | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 22.08%  |
| Unknown             | 14        | 18.18%  |
| SK hynix            | 13        | 16.88%  |
| Micron Technology   | 8         | 10.39%  |
| Crucial             | 6         | 7.79%   |
| Elpida              | 5         | 6.49%   |
| Kingston            | 3         | 3.9%    |
| A-DATA Technology   | 3         | 3.9%    |
| Unknown (ABCD)      | 2         | 2.6%    |
| Ramaxel Technology  | 1         | 1.3%    |
| Nanya Technology    | 1         | 1.3%    |
| Lexar               | 1         | 1.3%    |
| Gold Key            | 1         | 1.3%    |
| G.Skill             | 1         | 1.3%    |
| Corsair             | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 3.13%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 2.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.08%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.08%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 2.08%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 2.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 2.08%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.08%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.04%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.04%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 1.04%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.04%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.04%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.04%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.04%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.04%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.04%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s            | 1         | 1.04%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.04%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 23        | 37.7%   |
| DDR4   | 17        | 27.87%  |
| LPDDR3 | 5         | 8.2%    |
| DDR    | 4         | 6.56%   |
| SDRAM  | 3         | 4.92%   |
| LPDDR4 | 3         | 4.92%   |
| DDR2   | 3         | 4.92%   |
| DRAM   | 2         | 3.28%   |
| DDR5   | 1         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 83.87%  |
| Row Of Chips | 6         | 9.68%   |
| DIMM         | 2         | 3.23%   |
| Unknown      | 2         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 30.99%  |
| 8192  | 20        | 28.17%  |
| 2048  | 9         | 12.68%  |
| 1024  | 7         | 9.86%   |
| 16384 | 5         | 7.04%   |
| 512   | 5         | 7.04%   |
| 32768 | 1         | 1.41%   |
| 256   | 1         | 1.41%   |
| 128   | 1         | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 18.06%  |
| Unknown | 9         | 12.5%   |
| 3200    | 7         | 9.72%   |
| 2667    | 7         | 9.72%   |
| 1334    | 7         | 9.72%   |
| 2400    | 6         | 8.33%   |
| 2133    | 4         | 5.56%   |
| 1867    | 3         | 4.17%   |
| 1333    | 3         | 4.17%   |
| 1067    | 2         | 2.78%   |
| 8400    | 1         | 1.39%   |
| 4800    | 1         | 1.39%   |
| 4199    | 1         | 1.39%   |
| 3800    | 1         | 1.39%   |
| 3266    | 1         | 1.39%   |
| 3000    | 1         | 1.39%   |
| 1400    | 1         | 1.39%   |
| 1200    | 1         | 1.39%   |
| 1066    | 1         | 1.39%   |
| 667     | 1         | 1.39%   |
| 533     | 1         | 1.39%   |

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
| Chicony Electronics                    | 15        | 21.43%  |
| Realtek Semiconductor                  | 8         | 11.43%  |
| Microdia                               | 8         | 11.43%  |
| IMC Networks                           | 8         | 11.43%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.71%   |
| Bison Electronics                      | 4         | 5.71%   |
| Suyin                                  | 3         | 4.29%   |
| Quanta                                 | 3         | 4.29%   |
| Syntek                                 | 2         | 2.86%   |
| Sunplus Innovation Technology          | 2         | 2.86%   |
| Apple                                  | 2         | 2.86%   |
| Acer                                   | 2         | 2.86%   |
| Trust                                  | 1         | 1.43%   |
| Silicon Motion                         | 1         | 1.43%   |
| Samsung Electronics                    | 1         | 1.43%   |
| Ricoh                                  | 1         | 1.43%   |
| Luxvisions Innotech Limited            | 1         | 1.43%   |
| Logitech                               | 1         | 1.43%   |
| Lite-On Technology                     | 1         | 1.43%   |
| Lenovo                                 | 1         | 1.43%   |
| Alcor Micro                            | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 4         | 5.63%   |
| Microdia Integrated_Webcam_HD                       | 4         | 5.63%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 4.23%   |
| IMC Networks Integrated Camera                      | 3         | 4.23%   |
| Chicony HD Webcam                                   | 3         | 4.23%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.82%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 2.82%   |
| Chicony Integrated Camera                           | 2         | 2.82%   |
| Trust QHD Webcam                                    | 1         | 1.41%   |
| Syntek Integrated Camera                            | 1         | 1.41%   |
| Syntek EasyCamera                                   | 1         | 1.41%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.41%   |
| Suyin HP TrueVision HD                              | 1         | 1.41%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.41%   |
| Sunplus HP Universal Camera                         | 1         | 1.41%   |
| Sunplus HD WebCam                                   | 1         | 1.41%   |
| Silicon Motion NCM-G102                             | 1         | 1.41%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.41%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.41%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.41%   |
| Realtek USB Camera                                  | 1         | 1.41%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1.41%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.41%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.41%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.41%   |
| Microdia Integrated Webcam                          | 1         | 1.41%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.41%   |
| Logitech Webcam C270                                | 1         | 1.41%   |
| Logitech Webcam C170                                | 1         | 1.41%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.41%   |
| Lenovo Integrated Webcam                            | 1         | 1.41%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.41%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.41%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.41%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.41%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 1.41%   |
| Chicony HP TrueVision HD Camera                     | 1         | 1.41%   |
| Chicony HP HD Camera                                | 1         | 1.41%   |
| Chicony HD User Facing                              | 1         | 1.41%   |

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
| 0     | 47        | 57.32%  |
| 1     | 21        | 25.61%  |
| 2     | 10        | 12.2%   |
| 4     | 3         | 3.66%   |
| 3     | 1         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 20.37%  |
| Fingerprint reader       | 8         | 14.81%  |
| Modem                    | 7         | 12.96%  |
| Camera                   | 5         | 9.26%   |
| Bluetooth                | 5         | 9.26%   |
| Net/wireless             | 4         | 7.41%   |
| Communication controller | 4         | 7.41%   |
| Multimedia controller    | 2         | 3.7%    |
| Chipcard                 | 2         | 3.7%    |
| Unclassified device      | 1         | 1.85%   |
| Unassigned class         | 1         | 1.85%   |
| Storage                  | 1         | 1.85%   |
| Sound                    | 1         | 1.85%   |
| Network                  | 1         | 1.85%   |
| Card reader              | 1         | 1.85%   |

