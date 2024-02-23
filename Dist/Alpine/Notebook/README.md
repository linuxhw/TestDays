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

Total: 129

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBook5,1                  | [d3a48ce5b5](https://linux-hardware.org/?probe=d3a48ce5b5) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | [2fa13d832c](https://linux-hardware.org/?probe=2fa13d832c) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [876874e8b5](https://linux-hardware.org/?probe=876874e8b5) | Jan 24, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | [fb81d9ccfe](https://linux-hardware.org/?probe=fb81d9ccfe) | Jan 20, 2024 |
| Wortmann      | M660SE                      | [225361b7c3](https://linux-hardware.org/?probe=225361b7c3) | Jan 06, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [6f9241e288](https://linux-hardware.org/?probe=6f9241e288) | Jan 04, 2024 |
| Fujitsu       | LIFEBOOK AH530              | [9d5aa2f8ae](https://linux-hardware.org/?probe=9d5aa2f8ae) | Jan 02, 2024 |
| Fujitsu       | LIFEBOOK AH530              | [db0bed1921](https://linux-hardware.org/?probe=db0bed1921) | Jan 02, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| Acer          | Aspire A515-54              | [ea0b7cd870](https://linux-hardware.org/?probe=ea0b7cd870) | Dec 26, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| Dell          | Latitude 3420               | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| ASUSTek       | 1001PX                      | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Apple         | MacBookAir5,2               | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Lenovo        | Flex 2-14 20404             | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Unknown       | Unknown                     | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| Lenovo        | IdeaPad S145-15API 81V7     | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
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
| Lenovo        | IdeaPad S145-15API 81V7     | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Lenovo        | IdeaPad S145-15API 81V7     | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.16.0               | 6         | 7.06%   |
| Alpine 3.15.0               | 6         | 7.06%   |
| Alpine 3.19.0               | 5         | 5.88%   |
| Alpine 3.14.0               | 5         | 5.88%   |
| Alpine 3.12.0               | 5         | 5.88%   |
| Alpine 3.18.3               | 4         | 4.71%   |
| Alpine 3.15.4               | 4         | 4.71%   |
| Alpine 3.15.0_alpha20210804 | 4         | 4.71%   |
| Alpine 3.18.0               | 3         | 3.53%   |
| Alpine 3.17.2               | 3         | 3.53%   |
| Alpine 3.17.0               | 3         | 3.53%   |
| Alpine 3.19_alpha20230901   | 2         | 2.35%   |
| Alpine 3.18_alpha20230329   | 2         | 2.35%   |
| Alpine 3.18.4               | 2         | 2.35%   |
| Alpine 3.17.1               | 2         | 2.35%   |
| Alpine 3.16.2               | 2         | 2.35%   |
| Alpine 3.14.2               | 2         | 2.35%   |
| Alpine 3.13.5               | 2         | 2.35%   |
| Alpine 3.13.0_alpha20201218 | 2         | 2.35%   |
| Alpine 3.13.0_alpha20200917 | 2         | 2.35%   |
| Alpine 3.11.2               | 2         | 2.35%   |
| Alpine 3.19.0_rc2           | 1         | 1.18%   |
| Alpine 3.18.5               | 1         | 1.18%   |
| Alpine 3.18.2               | 1         | 1.18%   |
| Alpine 3.17_alpha20220809   | 1         | 1.18%   |
| Alpine 3.17.3               | 1         | 1.18%   |
| Alpine 3.16.3               | 1         | 1.18%   |
| Alpine 3.16.1               | 1         | 1.18%   |
| Alpine 3.16.0_alpha20220316 | 1         | 1.18%   |
| Alpine 3.15.2               | 1         | 1.18%   |
| Alpine 3.15.0_rc5           | 1         | 1.18%   |
| Alpine 3.14.0_alpha20210212 | 1         | 1.18%   |
| Alpine 3.13.1               | 1         | 1.18%   |
| Alpine 3.13.0_rc2           | 1         | 1.18%   |
| Alpine 3.13.0_alpha20200626 | 1         | 1.18%   |
| Alpine 3.12.3               | 1         | 1.18%   |
| Alpine 3.12.1               | 1         | 1.18%   |
| Alpine 3.11.5               | 1         | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 79        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.1.62-0-lts           | 2         | 2.2%    |
| 5.4.83-0-lts           | 2         | 2.2%    |
| 5.4.43-1-lts           | 2         | 2.2%    |
| 5.15.86-0-lts          | 2         | 2.2%    |
| 5.15.59-0-lts          | 2         | 2.2%    |
| 5.15.47-0-lts          | 2         | 2.2%    |
| 5.15.41-0-lts          | 2         | 2.2%    |
| 5.15.4-0-lts           | 2         | 2.2%    |
| 6.6.9-0-lts            | 1         | 1.1%    |
| 6.6.7-0-lts            | 1         | 1.1%    |
| 6.6.4-0-lts            | 1         | 1.1%    |
| 6.6.12-0-lts           | 1         | 1.1%    |
| 6.6.1-0-edge           | 1         | 1.1%    |
| 6.4.4-0-edge           | 1         | 1.1%    |
| 6.2.0-37-generic       | 1         | 1.1%    |
| 6.2.0-36-generic       | 1         | 1.1%    |
| 6.1.71-haos            | 1         | 1.1%    |
| 6.1.69-0-lts           | 1         | 1.1%    |
| 6.1.63-haos            | 1         | 1.1%    |
| 6.1.55-0-lts           | 1         | 1.1%    |
| 6.1.53-0-lts           | 1         | 1.1%    |
| 6.1.52-0-lts           | 1         | 1.1%    |
| 6.1.46-0-lts           | 1         | 1.1%    |
| 6.1.39-0-lts           | 1         | 1.1%    |
| 6.1.34                 | 1         | 1.1%    |
| 6.1.24-0-lts           | 1         | 1.1%    |
| 6.1.11-0-edge          | 1         | 1.1%    |
| 5.8.12-0-edge          | 1         | 1.1%    |
| 5.7.4                  | 1         | 1.1%    |
| 5.6.2-xanmod1-1-xanmod | 1         | 1.1%    |
| 5.4.84-0-lts           | 1         | 1.1%    |
| 5.4.72-0-lts           | 1         | 1.1%    |
| 5.4.64-0-lts           | 1         | 1.1%    |
| 5.4.46-0-lts           | 1         | 1.1%    |
| 5.4.27-0-lts           | 1         | 1.1%    |
| 5.4.0-77-generic       | 1         | 1.1%    |
| 5.19.0-50-generic      | 1         | 1.1%    |
| 5.19.0-35-generic      | 1         | 1.1%    |
| 5.17.9-0-edge          | 1         | 1.1%    |
| 5.17.0-0-edge          | 1         | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 3         | 3.41%   |
| 6.1.62  | 2         | 2.27%   |
| 5.4.83  | 2         | 2.27%   |
| 5.4.43  | 2         | 2.27%   |
| 5.15.86 | 2         | 2.27%   |
| 5.15.59 | 2         | 2.27%   |
| 5.15.47 | 2         | 2.27%   |
| 5.15.41 | 2         | 2.27%   |
| 5.15.4  | 2         | 2.27%   |
| 6.6.9   | 1         | 1.14%   |
| 6.6.7   | 1         | 1.14%   |
| 6.6.4   | 1         | 1.14%   |
| 6.6.12  | 1         | 1.14%   |
| 6.6.1   | 1         | 1.14%   |
| 6.4.4   | 1         | 1.14%   |
| 6.2.0   | 1         | 1.14%   |
| 6.1.71  | 1         | 1.14%   |
| 6.1.69  | 1         | 1.14%   |
| 6.1.63  | 1         | 1.14%   |
| 6.1.55  | 1         | 1.14%   |
| 6.1.53  | 1         | 1.14%   |
| 6.1.52  | 1         | 1.14%   |
| 6.1.46  | 1         | 1.14%   |
| 6.1.39  | 1         | 1.14%   |
| 6.1.34  | 1         | 1.14%   |
| 6.1.24  | 1         | 1.14%   |
| 6.1.11  | 1         | 1.14%   |
| 5.8.12  | 1         | 1.14%   |
| 5.7.4   | 1         | 1.14%   |
| 5.6.2   | 1         | 1.14%   |
| 5.4.84  | 1         | 1.14%   |
| 5.4.72  | 1         | 1.14%   |
| 5.4.64  | 1         | 1.14%   |
| 5.4.46  | 1         | 1.14%   |
| 5.4.27  | 1         | 1.14%   |
| 5.4.0   | 1         | 1.14%   |
| 5.19.0  | 1         | 1.14%   |
| 5.17.9  | 1         | 1.14%   |
| 5.17.0  | 1         | 1.14%   |
| 5.16.12 | 1         | 1.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 36.05%  |
| 6.1     | 13        | 15.12%  |
| 5.10    | 11        | 12.79%  |
| 5.4     | 10        | 11.63%  |
| 6.6     | 5         | 5.81%   |
| 5.17    | 2         | 2.33%   |
| 5.14    | 2         | 2.33%   |
| 6.4     | 1         | 1.16%   |
| 6.2     | 1         | 1.16%   |
| 5.8     | 1         | 1.16%   |
| 5.7     | 1         | 1.16%   |
| 5.6     | 1         | 1.16%   |
| 5.19    | 1         | 1.16%   |
| 5.16    | 1         | 1.16%   |
| 5.13    | 1         | 1.16%   |
| 5.12    | 1         | 1.16%   |
| 4.4     | 1         | 1.16%   |
| 3.18    | 1         | 1.16%   |
| 3.10    | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 82.28%  |
| i686   | 11        | 13.92%  |
| armv7l | 2         | 2.53%   |
| i586   | 1         | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 73.42%  |
| XFCE    | 11        | 13.92%  |
| GNOME   | 5         | 6.33%   |
| LXQt    | 2         | 2.53%   |
| KDE5    | 2         | 2.53%   |
| sway    | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 37        | 45.68%  |
| Unknown | 36        | 44.44%  |
| Wayland | 8         | 9.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 57        | 72.15%  |
| LightDM | 14        | 17.72%  |
| SDDM    | 3         | 3.8%    |
| LXDM    | 2         | 2.53%   |
| GDM     | 2         | 2.53%   |
| XDM     | 1         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 50        | 60.24%  |
| Unknown | 24        | 28.92%  |
| en_US   | 6         | 7.23%   |
| ru_RU   | 1         | 1.2%    |
| es_NI   | 1         | 1.2%    |
| en_GB   | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 52        | 64.2%   |
| EFI  | 29        | 35.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 78.05%  |
| Btrfs   | 7         | 8.54%   |
| Overlay | 6         | 7.32%   |
| Tmpfs   | 2         | 2.44%   |
| F2fs    | 1         | 1.22%   |
| Ext2    | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 64.63%  |
| GPT     | 21        | 25.61%  |
| MBR     | 8         | 9.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 91.36%  |
| Yes       | 7         | 8.64%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 92.59%  |
| Yes       | 6         | 7.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 17.72%  |
| Hewlett-Packard  | 13        | 16.46%  |
| Dell             | 10        | 12.66%  |
| ASUSTek Computer | 10        | 12.66%  |
| Acer             | 6         | 7.59%   |
| Toshiba          | 3         | 3.8%    |
| IBM              | 3         | 3.8%    |
| Google           | 3         | 3.8%    |
| Fujitsu          | 3         | 3.8%    |
| Apple            | 2         | 2.53%   |
| Unknown          | 2         | 2.53%   |
| Wortmann AG      | 1         | 1.27%   |
| Synology         | 1         | 1.27%   |
| Sony             | 1         | 1.27%   |
| Pegatron         | 1         | 1.27%   |
| Olivetti         | 1         | 1.27%   |
| Notebook         | 1         | 1.27%   |
| MSI              | 1         | 1.27%   |
| LG Electronics   | 1         | 1.27%   |
| Haier            | 1         | 1.27%   |
| Gateway          | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 2.53%   |
| Wortmann AG M660SE                       | 1         | 1.27%   |
| Toshiba WT8-A                            | 1         | 1.27%   |
| Toshiba Satellite Pro L50-A              | 1         | 1.27%   |
| Toshiba Satellite M645                   | 1         | 1.27%   |
| Synology DS1019+                         | 1         | 1.27%   |
| Sony VGN-UX27GN                          | 1         | 1.27%   |
| Pegatron Deepcam                         | 1         | 1.27%   |
| Olivetti Spring Peak                     | 1         | 1.27%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 1.27%   |
| MSI GL72M 7REX                           | 1         | 1.27%   |
| LG LW25-B7HG                             | 1         | 1.27%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 1.27%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 1.27%   |
| Lenovo V15 G3 IAP 82TT                   | 1         | 1.27%   |
| Lenovo V14-ADA 82C6                      | 1         | 1.27%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 1.27%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 1.27%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 1.27%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 1.27%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 1.27%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 1.27%   |
| Lenovo IdeaPad S145-15API 81V7           | 1         | 1.27%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 1.27%   |
| Lenovo Flex 2-14 20404                   | 1         | 1.27%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 1.27%   |
| IBM 26446AG                              | 1         | 1.27%   |
| IBM 264070A                              | 1         | 1.27%   |
| HP ZBook 15 G5                           | 1         | 1.27%   |
| HP ProBook 4310s                         | 1         | 1.27%   |
| HP Presario V4000 (EQ608PA#UUF)          | 1         | 1.27%   |
| HP Presario V2000 (ES307UA#ABL)          | 1         | 1.27%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 1.27%   |
| HP Mini 110-3500                         | 1         | 1.27%   |
| HP Laptop 17-cp0xxx                      | 1         | 1.27%   |
| HP Laptop 14-dq1xxx                      | 1         | 1.27%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 1.27%   |
| HP EliteBook 8460p                       | 1         | 1.27%   |
| HP EliteBook 2740p                       | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 7         | 8.86%   |
| Dell Inspiron      | 6         | 7.59%   |
| Acer Aspire        | 6         | 7.59%   |
| HP EliteBook       | 3         | 3.8%    |
| Toshiba Satellite  | 2         | 2.53%   |
| Lenovo IdeaPad     | 2         | 2.53%   |
| HP Presario        | 2         | 2.53%   |
| HP Laptop          | 2         | 2.53%   |
| Fujitsu LIFEBOOK   | 2         | 2.53%   |
| Dell Latitude      | 2         | 2.53%   |
| Unknown            | 2         | 2.53%   |
| Wortmann AG M660SE | 1         | 1.27%   |
| Toshiba WT8-A      | 1         | 1.27%   |
| Synology DS1019+   | 1         | 1.27%   |
| Sony VGN-UX27GN    | 1         | 1.27%   |
| Pegatron Deepcam   | 1         | 1.27%   |
| Olivetti Spring    | 1         | 1.27%   |
| Notebook NV4XMB    | 1         | 1.27%   |
| MSI GL72M          | 1         | 1.27%   |
| LG LW25-B7HG       | 1         | 1.27%   |
| Lenovo Yoga        | 1         | 1.27%   |
| Lenovo Y70-70      | 1         | 1.27%   |
| Lenovo V15         | 1         | 1.27%   |
| Lenovo V14-ADA     | 1         | 1.27%   |
| Lenovo Flex        | 1         | 1.27%   |
| IBM ThinkPad       | 1         | 1.27%   |
| IBM 26446AG        | 1         | 1.27%   |
| IBM 264070A        | 1         | 1.27%   |
| HP ZBook           | 1         | 1.27%   |
| HP ProBook         | 1         | 1.27%   |
| HP Pavilion        | 1         | 1.27%   |
| HP Mini            | 1         | 1.27%   |
| HP ENVY            | 1         | 1.27%   |
| HP Compaq          | 1         | 1.27%   |
| Haier U144S        | 1         | 1.27%   |
| Google Samus       | 1         | 1.27%   |
| Google Leona       | 1         | 1.27%   |
| Google Kefka       | 1         | 1.27%   |
| Gateway MX3631m    | 1         | 1.27%   |
| Fujitsu FMVNP8AE   | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2014    | 9         | 11.39%  |
| 2019    | 8         | 10.13%  |
| 2012    | 7         | 8.86%   |
| 2010    | 7         | 8.86%   |
| 2018    | 6         | 7.59%   |
| 2006    | 6         | 7.59%   |
| 2021    | 5         | 6.33%   |
| 2017    | 3         | 3.8%    |
| 2016    | 3         | 3.8%    |
| 2013    | 3         | 3.8%    |
| 2011    | 3         | 3.8%    |
| 2009    | 3         | 3.8%    |
| Unknown | 3         | 3.8%    |
| 2022    | 2         | 2.53%   |
| 2020    | 2         | 2.53%   |
| 2015    | 2         | 2.53%   |
| 2007    | 2         | 2.53%   |
| 2005    | 2         | 2.53%   |
| 2023    | 1         | 1.27%   |
| 2008    | 1         | 1.27%   |
| 1999    | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 79        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 78        | 97.5%   |
| Enabled  | 2         | 2.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 96.2%   |
| Yes  | 3         | 3.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 22        | 26.19%  |
| 3.01-4.0        | 15        | 17.86%  |
| 8.01-16.0       | 11        | 13.1%   |
| 16.01-24.0      | 9         | 10.71%  |
| 0.51-1.0        | 8         | 9.52%   |
| 1.01-2.0        | 7         | 8.33%   |
| 32.01-64.0      | 5         | 5.95%   |
| 2.01-3.0        | 3         | 3.57%   |
| 0.01-0.5        | 2         | 2.38%   |
| More than 256.0 | 1         | 1.19%   |
| 64.01-256.0     | 1         | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 25        | 29.76%  |
| 1.01-2.0  | 17        | 20.24%  |
| 0.51-1.0  | 13        | 15.48%  |
| 2.01-3.0  | 12        | 14.29%  |
| 4.01-8.0  | 8         | 9.52%   |
| 3.01-4.0  | 4         | 4.76%   |
| 8.01-16.0 | 2         | 2.38%   |
| 0         | 2         | 2.38%   |
| Unknown   | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 62        | 74.7%   |
| 2      | 16        | 19.28%  |
| 0      | 2         | 2.41%   |
| 7      | 1         | 1.2%    |
| 5      | 1         | 1.2%    |
| 3      | 1         | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 67.9%   |
| Yes       | 26        | 32.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 79.75%  |
| No        | 16        | 20.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 88.89%  |
| No        | 9         | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 61.73%  |
| No        | 31        | 38.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 19        | 22.09%  |
| Canada       | 9         | 10.47%  |
| Germany      | 7         | 8.14%   |
| Russia       | 6         | 6.98%   |
| UK           | 5         | 5.81%   |
| Brazil       | 5         | 5.81%   |
| Spain        | 4         | 4.65%   |
| Slovakia     | 2         | 2.33%   |
| Italy        | 2         | 2.33%   |
| Israel       | 2         | 2.33%   |
| Australia    | 2         | 2.33%   |
| Venezuela    | 1         | 1.16%   |
| UAE          | 1         | 1.16%   |
| Sweden       | 1         | 1.16%   |
| South Korea  | 1         | 1.16%   |
| South Africa | 1         | 1.16%   |
| Puerto Rico  | 1         | 1.16%   |
| Portugal     | 1         | 1.16%   |
| Poland       | 1         | 1.16%   |
| Philippines  | 1         | 1.16%   |
| Nicaragua    | 1         | 1.16%   |
| Netherlands  | 1         | 1.16%   |
| Mexico       | 1         | 1.16%   |
| Kenya        | 1         | 1.16%   |
| Jamaica      | 1         | 1.16%   |
| Hungary      | 1         | 1.16%   |
| Guatemala    | 1         | 1.16%   |
| Greece       | 1         | 1.16%   |
| France       | 1         | 1.16%   |
| Egypt        | 1         | 1.16%   |
| Czechia      | 1         | 1.16%   |
| Cyprus       | 1         | 1.16%   |
| China        | 1         | 1.16%   |
| Austria      | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vernon           | 3         | 3.41%   |
| St Petersburg    | 3         | 3.41%   |
| Springfield      | 3         | 3.41%   |
| Stratford        | 2         | 2.27%   |
| Moscow           | 2         | 2.27%   |
| Manitowoc        | 2         | 2.27%   |
| Fulham           | 2         | 2.27%   |
| Zhangzhou        | 1         | 1.14%   |
| Waukesha         | 1         | 1.14%   |
| Vienna           | 1         | 1.14%   |
| Ventura          | 1         | 1.14%   |
| Tymovskoye       | 1         | 1.14%   |
| Turin            | 1         | 1.14%   |
| Thornhill        | 1         | 1.14%   |
| Tampa            | 1         | 1.14%   |
| Sydney           | 1         | 1.14%   |
| Stuttgart        | 1         | 1.14%   |
| Stewartstown     | 1         | 1.14%   |
| Sisteron         | 1         | 1.14%   |
| Semily           | 1         | 1.14%   |
| Seattle          | 1         | 1.14%   |
| Sao Paulo        | 1         | 1.14%   |
| San Mateo        | 1         | 1.14%   |
| Saarbrücken     | 1         | 1.14%   |
| Rzeszów         | 1         | 1.14%   |
| Rostock          | 1         | 1.14%   |
| Ramat Gan        | 1         | 1.14%   |
| Purdys           | 1         | 1.14%   |
| Olofstorp        | 1         | 1.14%   |
| Oakville         | 1         | 1.14%   |
| Northampton      | 1         | 1.14%   |
| Nairobi          | 1         | 1.14%   |
| Montreal         | 1         | 1.14%   |
| Merrill          | 1         | 1.14%   |
| Mérida          | 1         | 1.14%   |
| Manila           | 1         | 1.14%   |
| Managua          | 1         | 1.14%   |
| Madrid           | 1         | 1.14%   |
| Lindavista Norte | 1         | 1.14%   |
| Lincoln          | 1         | 1.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 13        | 25     | 12.04%  |
| Toshiba                     | 10        | 13     | 9.26%   |
| Unknown                     | 8         | 10     | 7.41%   |
| Seagate                     | 8         | 19     | 7.41%   |
| Hitachi                     | 8         | 8      | 7.41%   |
| WDC                         | 7         | 11     | 6.48%   |
| Kingston                    | 7         | 11     | 6.48%   |
| HGST                        | 6         | 6      | 5.56%   |
| SanDisk                     | 4         | 4      | 3.7%    |
| Crucial                     | 4         | 4      | 3.7%    |
| SPCC                        | 3         | 3      | 2.78%   |
| SK hynix                    | 3         | 3      | 2.78%   |
| Micron Technology           | 3         | 4      | 2.78%   |
| Intel                       | 3         | 5      | 2.78%   |
| A-DATA Technology           | 3         | 4      | 2.78%   |
| Fujitsu                     | 2         | 2      | 1.85%   |
| SINTECHI                    | 1         | 1      | 0.93%   |
| Secure                      | 1         | 1      | 0.93%   |
| Netac                       | 1         | 1      | 0.93%   |
| LITEON                      | 1         | 1      | 0.93%   |
| Kingston Technology Company | 1         | 1      | 0.93%   |
| KingSpec                    | 1         | 1      | 0.93%   |
| KC600                       | 1         | 1      | 0.93%   |
| JMicron Technology          | 1         | 1      | 0.93%   |
| Intenso                     | 1         | 1      | 0.93%   |
| INNOVATION IT               | 1         | 1      | 0.93%   |
| IBM                         | 1         | 1      | 0.93%   |
| Emtec                       | 1         | 1      | 0.93%   |
| Dell                        | 1         | 2      | 0.93%   |
| China                       | 1         | 1      | 0.93%   |
| Aura                        | 1         | 1      | 0.93%   |
| AMD                         | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                      | 3         | 2.27%   |
| Unknown MMC Card  64GB                      | 2         | 1.52%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 1.52%   |
| Toshiba MQ01ABD075 752GB                    | 2         | 1.52%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 2         | 1.52%   |
| Samsung NVMe SSD Drive 1024GB               | 2         | 1.52%   |
| Kingston SV300S37A120G 120GB SSD            | 2         | 1.52%   |
| Crucial CT500MX500SSD1 500GB                | 2         | 1.52%   |
| WDC WDS500G2X0C-00L350 500GB                | 1         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD            | 1         | 0.76%   |
| WDC WDS500G2B0A 500GB SSD                   | 1         | 0.76%   |
| WDC WDS250G2B0A 250GB SSD                   | 1         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 0.76%   |
| WDC WD5000BEVT-7 500GB                      | 1         | 0.76%   |
| WDC WD5000BEVT-22ZAT0 500GB                 | 1         | 0.76%   |
| WDC WD10SPZX-60Z10T1 1TB                    | 1         | 0.76%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB        | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB        | 1         | 0.76%   |
| Unknown SD32G  32GB                         | 1         | 0.76%   |
| Unknown NVMe SSD Drive 1024GB               | 1         | 0.76%   |
| Unknown MMC Card  32GB                      | 1         | 0.76%   |
| Unknown MMC Card                            | 1         | 0.76%   |
| Toshiba NVMe SSD Drive 256GB                | 1         | 0.76%   |
| Toshiba MQ04ABF1 1TB                        | 1         | 0.76%   |
| Toshiba MQ01ABD1 1TB                        | 1         | 0.76%   |
| Toshiba MK6008GAH 64GB                      | 1         | 0.76%   |
| Toshiba MK4009GAL 40GB                      | 1         | 0.76%   |
| Toshiba MK1637GSX 160GB                     | 1         | 0.76%   |
| Toshiba KXG5AZNV256G 256GB                  | 1         | 0.76%   |
| Toshiba HDWL110 1TB                         | 1         | 0.76%   |
| Toshiba DT01ACA1 1TB                        | 1         | 0.76%   |
| SPCC Solid State Disk 256GB                 | 1         | 0.76%   |
| SPCC Solid State Disk                       | 1         | 0.76%   |
| SPCC Solid State 120GB                      | 1         | 0.76%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB   | 1         | 0.76%   |
| SINTECHI HighSpeed SD to CF Adapter V1.0    | 1         | 0.76%   |
| Secure Net 256GB SSD                        | 1         | 0.76%   |
| Seagate ST98823A 80GB                       | 1         | 0.76%   |
| Seagate ST9250315AS 250GB                   | 1         | 0.76%   |
| Seagate ST9160314AS 160GB                   | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 9         | 11     | 21.95%  |
| Seagate             | 8         | 19     | 19.51%  |
| Hitachi             | 8         | 8      | 19.51%  |
| HGST                | 6         | 6      | 14.63%  |
| WDC                 | 3         | 3      | 7.32%   |
| Samsung Electronics | 2         | 3      | 4.88%   |
| Fujitsu             | 2         | 2      | 4.88%   |
| SINTECHI            | 1         | 1      | 2.44%   |
| JMicron Technology  | 1         | 1      | 2.44%   |
| IBM                 | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 9      | 18.92%  |
| Samsung Electronics | 4         | 10     | 10.81%  |
| Crucial             | 4         | 4      | 10.81%  |
| WDC                 | 3         | 4      | 8.11%   |
| SPCC                | 3         | 3      | 8.11%   |
| SanDisk             | 2         | 2      | 5.41%   |
| Secure              | 1         | 1      | 2.7%    |
| Netac               | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEON              | 1         | 1      | 2.7%    |
| KingSpec            | 1         | 1      | 2.7%    |
| KC600               | 1         | 1      | 2.7%    |
| Intenso             | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| INNOVATION IT       | 1         | 1      | 2.7%    |
| Emtec               | 1         | 1      | 2.7%    |
| Dell                | 1         | 2      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| AMD                 | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 38        | 55     | 42.22%  |
| SSD     | 26        | 47     | 28.89%  |
| NVMe    | 18        | 38     | 20%     |
| MMC     | 7         | 8      | 7.78%   |
| Unknown | 1         | 1      | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 98     | 67.05%  |
| NVMe | 18        | 38     | 20.45%  |
| MMC  | 7         | 8      | 7.95%   |
| SAS  | 4         | 5      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 64     | 68.18%  |
| 0.51-1.0   | 16        | 22     | 24.24%  |
| 1.01-2.0   | 2         | 4      | 3.03%   |
| 4.01-10.0  | 2         | 11     | 3.03%   |
| 3.01-4.0   | 1         | 1      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 24.1%   |
| 1-20           | 16        | 19.28%  |
| Unknown        | 10        | 12.05%  |
| 251-500        | 9         | 10.84%  |
| 21-50          | 7         | 8.43%   |
| 501-1000       | 7         | 8.43%   |
| More than 3000 | 5         | 6.02%   |
| 1001-2000      | 4         | 4.82%   |
| 51-100         | 3         | 3.61%   |
| 2001-3000      | 2         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 52        | 62.65%  |
| Unknown   | 10        | 12.05%  |
| 21-50     | 6         | 7.23%   |
| 51-100    | 5         | 6.02%   |
| 251-500   | 3         | 3.61%   |
| 101-250   | 3         | 3.61%   |
| 501-1000  | 2         | 2.41%   |
| 2001-3000 | 1         | 1.2%    |
| 1001-2000 | 1         | 1.2%    |

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
| Works    | 47        | 99     | 54.02%  |
| Detected | 28        | 35     | 32.18%  |
| Malfunc  | 12        | 15     | 13.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 55        | 58.51%  |
| AMD                          | 12        | 12.77%  |
| Samsung Electronics          | 8         | 8.51%   |
| SanDisk                      | 4         | 4.26%   |
| SK hynix                     | 3         | 3.19%   |
| ADATA Technology             | 3         | 3.19%   |
| Nvidia                       | 2         | 2.13%   |
| Micron Technology            | 2         | 2.13%   |
| VIA Technologies             | 1         | 1.06%   |
| Toshiba America Info Systems | 1         | 1.06%   |
| Marvell Technology Group     | 1         | 1.06%   |
| Kingston Technology Company  | 1         | 1.06%   |
| Broadcom / LSI               | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 9.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 3.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.46%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 2.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 2.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 2.46%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 2.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.46%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.64%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.64%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.64%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.82%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.82%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.82%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 0.82%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.82%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.82%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.82%   |
| Micron 7300 MAX NVMe SSD                                                       | 1         | 0.82%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 0.82%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 53        | 59.55%  |
| NVMe | 18        | 20.22%  |
| IDE  | 13        | 14.61%  |
| RAID | 5         | 5.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 80.25%  |
| AMD    | 14        | 17.28%  |
| ARM    | 2         | 2.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz       | 2         | 2.3%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 2.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 2.3%    |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 2.3%    |
| Intel Atom CPU N455 @ 1.66GHz           | 2         | 2.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 2.3%    |
| Intel Xeon Gold 6336Y CPU @ 2.40GHz     | 1         | 1.15%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1         | 1.15%   |
| Intel Xeon E-2176M CPU @ 2.70GHz        | 1         | 1.15%   |
| Intel Pentium M processor 1.60GHz       | 1         | 1.15%   |
| Intel Pentium M processor 1.50GHz       | 1         | 1.15%   |
| Intel Pentium III (Coppermine)          | 1         | 1.15%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.15%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 1.15%   |
| Intel Mobile Pentium MMX                | 1         | 1.15%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 1.15%   |
| Intel Core Solo CPU U1500 @ 1.33GHz     | 1         | 1.15%   |
| Intel Core m3-8100Y CPU @ 1.10GHz       | 1         | 1.15%   |
| Intel Core i9-9980HK CPU @ 2.40GHz      | 1         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.15%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.15%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 1.15%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz      | 1         | 1.15%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 1         | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.15%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz       | 1         | 1.15%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.15%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.15%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.15%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.15%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 1         | 1.15%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.15%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 1.15%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz      | 1         | 1.15%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 1         | 1.15%   |
| Intel Core i5 CPU M 480 @ 2.67GHz       | 1         | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 18        | 21.43%  |
| Other                | 9         | 10.71%  |
| Intel Core i3        | 7         | 8.33%   |
| Intel Celeron        | 6         | 7.14%   |
| Intel Atom           | 6         | 7.14%   |
| Intel Core i7        | 5         | 5.95%   |
| Intel Pentium M      | 4         | 4.76%   |
| Intel Core 2 Duo     | 4         | 4.76%   |
| AMD Ryzen 5          | 3         | 3.57%   |
| Intel Pentium        | 2         | 2.38%   |
| AMD Ryzen 7          | 2         | 2.38%   |
| AMD A4               | 2         | 2.38%   |
| Intel Xeon Gold      | 1         | 1.19%   |
| Intel Xeon           | 1         | 1.19%   |
| Intel Pentium III    | 1         | 1.19%   |
| Intel Genuine        | 1         | 1.19%   |
| Intel Core Solo      | 1         | 1.19%   |
| Intel Core m3        | 1         | 1.19%   |
| Intel Core i9        | 1         | 1.19%   |
| Intel Core Duo       | 1         | 1.19%   |
| Intel Core 2         | 1         | 1.19%   |
| ARM ARMv7            | 1         | 1.19%   |
| AMD Turion 64 Mobile | 1         | 1.19%   |
| AMD Ryzen 3          | 1         | 1.19%   |
| AMD FX               | 1         | 1.19%   |
| AMD E2               | 1         | 1.19%   |
| AMD A6               | 1         | 1.19%   |
| AMD A10              | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 40        | 47.62%  |
| 4       | 21        | 25%     |
| 1       | 12        | 14.29%  |
| 6       | 3         | 3.57%   |
| 8       | 2         | 2.38%   |
| 48      | 1         | 1.19%   |
| 32      | 1         | 1.19%   |
| 16      | 1         | 1.19%   |
| 14      | 1         | 1.19%   |
| 3       | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 78        | 97.5%   |
| 2       | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 41        | 51.9%   |
| 1       | 37        | 46.84%  |
| Unknown | 1         | 1.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 44        | 54.32%  |
| 32-bit, 64-bit | 34        | 41.98%  |
| 32-bit         | 3         | 3.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 54.02%  |
| 0x306a9    | 3         | 3.45%   |
| 0x30678    | 3         | 3.45%   |
| 0x106ca    | 3         | 3.45%   |
| 0x906ea    | 2         | 2.3%    |
| 0x806eb    | 2         | 2.3%    |
| 0x806c1    | 2         | 2.3%    |
| 0x306c3    | 2         | 2.3%    |
| 0x206a7    | 2         | 2.3%    |
| 0x20655    | 2         | 2.3%    |
| 0x08108102 | 2         | 2.3%    |
| 0x06006704 | 2         | 2.3%    |
| 0xa0671    | 1         | 1.15%   |
| 0x906a3    | 1         | 1.15%   |
| 0x806ec    | 1         | 1.15%   |
| 0x806ea    | 1         | 1.15%   |
| 0x706e5    | 1         | 1.15%   |
| 0x683      | 1         | 1.15%   |
| 0x606a6    | 1         | 1.15%   |
| 0x506c9    | 1         | 1.15%   |
| 0x406c4    | 1         | 1.15%   |
| 0x306d4    | 1         | 1.15%   |
| 0x106e5    | 1         | 1.15%   |
| 0x1067a    | 1         | 1.15%   |
| 0x08608103 | 1         | 1.15%   |
| 0x08108109 | 1         | 1.15%   |
| 0x0810100b | 1         | 1.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 12.94%  |
| P6               | 8         | 9.41%   |
| Silvermont       | 6         | 7.06%   |
| Haswell          | 5         | 5.88%   |
| Unknown          | 5         | 5.88%   |
| Westmere         | 4         | 4.71%   |
| Penryn           | 4         | 4.71%   |
| IvyBridge        | 4         | 4.71%   |
| Goldmont         | 4         | 4.71%   |
| Bonnell          | 4         | 4.71%   |
| Zen+             | 3         | 3.53%   |
| TigerLake        | 3         | 3.53%   |
| SandyBridge      | 3         | 3.53%   |
| Excavator        | 3         | 3.53%   |
| Broadwell        | 3         | 3.53%   |
| Skylake          | 2         | 2.35%   |
| Icelake          | 2         | 2.35%   |
| Alderlake Hybrid | 2         | 2.35%   |
| Zen 2            | 1         | 1.18%   |
| Zen              | 1         | 1.18%   |
| Puma             | 1         | 1.18%   |
| Piledriver       | 1         | 1.18%   |
| Nehalem          | 1         | 1.18%   |
| K8 Hammer        | 1         | 1.18%   |
| Jaguar           | 1         | 1.18%   |
| Core             | 1         | 1.18%   |
| Bobcat           | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 57        | 61.29%  |
| AMD                        | 20        | 21.51%  |
| Nvidia                     | 11        | 11.83%  |
| Neomagic                   | 2         | 2.15%   |
| VIA Technologies           | 1         | 1.08%   |
| Matrox Electronics Systems | 1         | 1.08%   |
| ASPEED Technology          | 1         | 1.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 2.5%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 2.5%    |
| Intel HD Graphics 5500                                                                   | 3         | 2.5%    |
| Intel HD Graphics 500                                                                    | 3         | 2.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.67%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.67%   |
| Intel HD Graphics 630                                                                    | 2         | 1.67%   |
| Intel HD Graphics 620                                                                    | 2         | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.67%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.67%   |
| AMD Lucienne                                                                             | 2         | 1.67%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.83%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.83%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.83%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.83%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.83%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.83%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.83%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.83%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.83%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 0.83%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 40        | 47.06%  |
| 1 x AMD         | 15        | 17.65%  |
| Intel + Nvidia  | 8         | 9.41%   |
| 2 x Intel       | 7         | 8.24%   |
| Intel + AMD     | 4         | 4.71%   |
| Other           | 2         | 2.35%   |
| 1 x Nvidia      | 2         | 2.35%   |
| 1 x Neomagic    | 2         | 2.35%   |
| 2 x AMD         | 1         | 1.18%   |
| 1 x VIA         | 1         | 1.18%   |
| Nvidia + Matrox | 1         | 1.18%   |
| 1 x ASPEED      | 1         | 1.18%   |
| AMD + Nvidia    | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 73        | 89.02%  |
| Unknown     | 6         | 7.32%   |
| Proprietary | 3         | 3.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 86.42%  |
| 0.01-0.5   | 5         | 6.17%   |
| 1.01-2.0   | 3         | 3.7%    |
| 3.01-4.0   | 1         | 1.23%   |
| 2.01-3.0   | 1         | 1.23%   |
| 0.51-1.0   | 1         | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 18.18%  |
| LG Display              | 14        | 15.91%  |
| BOE                     | 11        | 12.5%   |
| Chimei Innolux          | 8         | 9.09%   |
| Samsung Electronics     | 4         | 4.55%   |
| LG Philips              | 3         | 3.41%   |
| InfoVision              | 3         | 3.41%   |
| Chi Mei Optoelectronics | 3         | 3.41%   |
| PANDA                   | 2         | 2.27%   |
| Lenovo                  | 2         | 2.27%   |
| HannStar                | 2         | 2.27%   |
| Goldstar                | 2         | 2.27%   |
| Apple                   | 2         | 2.27%   |
| Vizio                   | 1         | 1.14%   |
| Sharp                   | 1         | 1.14%   |
| Sceptre Tech            | 1         | 1.14%   |
| Quanta Display          | 1         | 1.14%   |
| Philips                 | 1         | 1.14%   |
| ONN                     | 1         | 1.14%   |
| KVM                     | 1         | 1.14%   |
| Envision                | 1         | 1.14%   |
| Element                 | 1         | 1.14%   |
| DENON                   | 1         | 1.14%   |
| Dell                    | 1         | 1.14%   |
| CSO                     | 1         | 1.14%   |
| CPT                     | 1         | 1.14%   |
| CHD                     | 1         | 1.14%   |
| BenQ                    | 1         | 1.14%   |
| Acer                    | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.98%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.98%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                  | 1         | 0.99%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.99%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch  | 1         | 0.99%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.99%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 0.99%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.99%   |
| PANDA LCD Monitor NCP0056 1920x1080 309x174mm 14.0-inch               | 1         | 0.99%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.99%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 0.99%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.99%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 0.99%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.99%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.99%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD01F0 1280x800 261x163mm 12.1-inch           | 1         | 0.99%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.99%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch              | 1         | 0.99%   |
| KVM LCD Monitor191919 KVM4308 1280x1024 376x301mm 19.0-inch           | 1         | 0.99%   |
| InfoVision M116NWR1 R0 IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 0.99%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 0.99%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch           | 1         | 0.99%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1         | 0.99%   |
| Goldstar ULTRAWIDE GSM5AE2 3440x1440 800x335mm 34.1-inch              | 1         | 0.99%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 27        | 32.53%  |
| 1920x1080 (FHD)    | 20        | 24.1%   |
| 1280x800 (WXGA)    | 7         | 8.43%   |
| 1600x900 (HD+)     | 4         | 4.82%   |
| 1024x600           | 4         | 4.82%   |
| 3840x2160 (4K)     | 3         | 3.61%   |
| 2560x1440 (QHD)    | 3         | 3.61%   |
| 2560x1080          | 2         | 2.41%   |
| 1920x1200 (WUXGA)  | 2         | 2.41%   |
| 1280x768           | 2         | 2.41%   |
| 1280x1024 (SXGA)   | 2         | 2.41%   |
| 3440x1440          | 1         | 1.2%    |
| 2880x1800          | 1         | 1.2%    |
| 2560x1700          | 1         | 1.2%    |
| 1680x1050 (WSXGA+) | 1         | 1.2%    |
| 1440x900 (WXGA+)   | 1         | 1.2%    |
| 1360x768           | 1         | 1.2%    |
| 1024x768 (XGA)     | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 29.55%  |
| 14     | 13        | 14.77%  |
| 13     | 11        | 12.5%   |
| 17     | 7         | 7.95%   |
| 11     | 5         | 5.68%   |
| 12     | 4         | 4.55%   |
| 10     | 4         | 4.55%   |
| 32     | 2         | 2.27%   |
| 31     | 2         | 2.27%   |
| 72     | 1         | 1.14%   |
| 60     | 1         | 1.14%   |
| 40     | 1         | 1.14%   |
| 34     | 1         | 1.14%   |
| 29     | 1         | 1.14%   |
| 27     | 1         | 1.14%   |
| 25     | 1         | 1.14%   |
| 24     | 1         | 1.14%   |
| 23     | 1         | 1.14%   |
| 22     | 1         | 1.14%   |
| 21     | 1         | 1.14%   |
| 20     | 1         | 1.14%   |
| 19     | 1         | 1.14%   |
| 16     | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 56.79%  |
| 201-300     | 17        | 20.99%  |
| 351-400     | 7         | 8.64%   |
| 601-700     | 4         | 4.94%   |
| 701-800     | 2         | 2.47%   |
| 801-900     | 1         | 1.23%   |
| 501-600     | 1         | 1.23%   |
| 401-500     | 1         | 1.23%   |
| 1501-2000   | 1         | 1.23%   |
| 1001-1500   | 1         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 77.03%  |
| 16/10 | 11        | 14.86%  |
| 5/4   | 2         | 2.7%    |
| 21/9  | 2         | 2.7%    |
| 4/3   | 1         | 1.35%   |
| 3/2   | 1         | 1.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 31.71%  |
| 81-90          | 20        | 24.39%  |
| 71-80          | 5         | 6.1%    |
| 51-60          | 5         | 6.1%    |
| 121-130        | 5         | 6.1%    |
| 351-500        | 4         | 4.88%   |
| 41-50          | 4         | 4.88%   |
| 61-70          | 3         | 3.66%   |
| More than 1000 | 2         | 2.44%   |
| 301-350        | 2         | 2.44%   |
| 251-300        | 1         | 1.22%   |
| 201-250        | 1         | 1.22%   |
| 151-200        | 1         | 1.22%   |
| 141-150        | 1         | 1.22%   |
| 131-140        | 1         | 1.22%   |
| 501-1000       | 1         | 1.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 30        | 39.47%  |
| 101-120       | 28        | 36.84%  |
| 51-100        | 11        | 14.47%  |
| 1-50          | 3         | 3.95%   |
| More than 240 | 2         | 2.63%   |
| 161-240       | 2         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 66        | 80.49%  |
| 0     | 8         | 9.76%   |
| 2     | 7         | 8.54%   |
| 3     | 1         | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 48        | 34.78%  |
| Intel                           | 39        | 28.26%  |
| Qualcomm Atheros                | 19        | 13.77%  |
| Broadcom                        | 11        | 7.97%   |
| Marvell Technology Group        | 3         | 2.17%   |
| Broadcom Limited                | 3         | 2.17%   |
| LSI                             | 2         | 1.45%   |
| VIA Technologies                | 1         | 0.72%   |
| TP-Link                         | 1         | 0.72%   |
| Qualcomm Atheros Communications | 1         | 0.72%   |
| Qualcomm                        | 1         | 0.72%   |
| Nvidia                          | 1         | 0.72%   |
| NetGear                         | 1         | 0.72%   |
| Mellanox Technologies           | 1         | 0.72%   |
| MediaTek                        | 1         | 0.72%   |
| Google                          | 1         | 0.72%   |
| Dresden Elektronik              | 1         | 0.72%   |
| DisplayLink                     | 1         | 0.72%   |
| ASIX Electronics                | 1         | 0.72%   |
| AMD                             | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 25        | 14.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 5.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 5.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.73%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 3         | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 1.16%   |
| Intel Wireless 7265                                                    | 2         | 1.16%   |
| Intel Wireless 3160                                                    | 2         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.16%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 1.16%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 1.16%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection               | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.16%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller       | 2         | 1.16%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.16%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter   | 2         | 1.16%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.58%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.58%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1         | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 0.58%   |
| Realtek RTL8187 Wireless Adapter                                       | 1         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 44.3%   |
| Qualcomm Atheros                | 18        | 22.78%  |
| Realtek Semiconductor           | 9         | 11.39%  |
| Broadcom                        | 9         | 11.39%  |
| Broadcom Limited                | 3         | 3.8%    |
| TP-Link                         | 1         | 1.27%   |
| Qualcomm Atheros Communications | 1         | 1.27%   |
| NetGear                         | 1         | 1.27%   |
| MediaTek                        | 1         | 1.27%   |
| Marvell Technology Group        | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 9         | 10.47%  |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 4.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 3.49%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 3.49%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 3         | 3.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 2.33%   |
| Intel Wireless 7265                                                            | 2         | 2.33%   |
| Intel Wireless 3160                                                            | 2         | 2.33%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 2.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 2.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 2         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 2         | 2.33%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter           | 2         | 2.33%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 1         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 1.16%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 1.16%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.16%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.16%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.16%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 1.16%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.16%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.16%   |
| Intel Wireless 8260                                                            | 1         | 1.16%   |
| Intel Wireless 7260                                                            | 1         | 1.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 1         | 1.16%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 42        | 58.33%  |
| Intel                    | 14        | 19.44%  |
| Broadcom                 | 4         | 5.56%   |
| Qualcomm Atheros         | 3         | 4.17%   |
| Marvell Technology Group | 2         | 2.78%   |
| VIA Technologies         | 1         | 1.39%   |
| Qualcomm                 | 1         | 1.39%   |
| Nvidia                   | 1         | 1.39%   |
| Mellanox Technologies    | 1         | 1.39%   |
| LSI                      | 1         | 1.39%   |
| DisplayLink              | 1         | 1.39%   |
| ASIX Electronics         | 1         | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 25        | 31.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 6.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.5%    |
| Intel 82579V Gigabit Network Connection                                | 2         | 2.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.25%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.25%   |
| Qualcomm Android                                                       | 1         | 1.25%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.25%   |
| Mellanox MT28908 Family [ConnectX-6]                                   | 1         | 1.25%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 1.25%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 1.25%   |
| LSI ET-131x PCI-E Ethernet Controller                                  | 1         | 1.25%   |
| Intel WiMAX Connection 2400m                                           | 1         | 1.25%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.25%   |
| Intel Ethernet Controller 10G X550T                                    | 1         | 1.25%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 1.25%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1         | 1.25%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.25%   |
| Intel 82541GI Gigabit Ethernet Controller                              | 1         | 1.25%   |
| DisplayLink Dell D3100 Docking Station                                 | 1         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.25%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                  | 1         | 1.25%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.25%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 1         | 1.25%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 51.06%  |
| Ethernet | 62        | 43.97%  |
| Modem    | 7         | 4.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 64.56%  |
| Ethernet | 28        | 35.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 55        | 68.75%  |
| 1     | 20        | 25%     |
| 0     | 5         | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 66        | 82.5%   |
| Yes  | 14        | 17.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 36.21%  |
| Realtek Semiconductor           | 5         | 8.62%   |
| Qualcomm Atheros Communications | 5         | 8.62%   |
| IMC Networks                    | 4         | 6.9%    |
| Broadcom                        | 4         | 6.9%    |
| Lite-On Technology              | 3         | 5.17%   |
| Foxconn / Hon Hai               | 3         | 5.17%   |
| Apple                           | 3         | 5.17%   |
| ASUSTek Computer                | 2         | 3.45%   |
| Toshiba                         | 1         | 1.72%   |
| Marvell Semiconductor           | 1         | 1.72%   |
| Hewlett-Packard                 | 1         | 1.72%   |
| Edimax Technology               | 1         | 1.72%   |
| Dell                            | 1         | 1.72%   |
| Cambridge Silicon Radio         | 1         | 1.72%   |
| Askey Computer                  | 1         | 1.72%   |
| Alps Electric                   | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 13.56%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 8.47%   |
| Realtek Bluetooth Radio                             | 4         | 6.78%   |
| Intel AX201 Bluetooth                               | 4         | 6.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.08%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.39%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.39%   |
| Intel AX200 Bluetooth                               | 2         | 3.39%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 3.39%   |
| Apple Bluetooth Host Controller                     | 2         | 3.39%   |
| Toshiba Bluetooth Device                            | 1         | 1.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.69%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.69%   |
| Intel Bluetooth Device                              | 1         | 1.69%   |
| Intel AX210 Bluetooth                               | 1         | 1.69%   |
| IMC Networks Wireless_Device                        | 1         | 1.69%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.69%   |
| IMC Networks Bluetooth Device                       | 1         | 1.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.69%   |
| Edimax Bluetooth Adapter                            | 1         | 1.69%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.69%   |
| Broadcom BCM20702A0                                 | 1         | 1.69%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.69%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.69%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.69%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.69%   |
| Askey Bluetooth Device                              | 1         | 1.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.69%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 59        | 67.82%  |
| AMD                       | 16        | 18.39%  |
| Nvidia                    | 4         | 4.6%    |
| VIA Technologies          | 1         | 1.15%   |
| Texas Instruments         | 1         | 1.15%   |
| SteelSeries ApS           | 1         | 1.15%   |
| Sennheiser Communications | 1         | 1.15%   |
| Realtek Semiconductor     | 1         | 1.15%   |
| Logitech                  | 1         | 1.15%   |
| Focusrite-Novation        | 1         | 1.15%   |
| Cirrus Logic              | 1         | 1.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 5.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 3.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 3.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.34%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.34%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 2.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.56%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.56%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.56%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.78%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.78%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.78%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 0.78%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.78%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.78%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 21.95%  |
| Unknown             | 16        | 19.51%  |
| SK hynix            | 14        | 17.07%  |
| Micron Technology   | 8         | 9.76%   |
| Crucial             | 6         | 7.32%   |
| Elpida              | 5         | 6.1%    |
| Kingston            | 3         | 3.66%   |
| A-DATA Technology   | 3         | 3.66%   |
| Unknown (ABCD)      | 2         | 2.44%   |
| Smart Brazil        | 1         | 1.22%   |
| Ramaxel Technology  | 1         | 1.22%   |
| Nanya Technology    | 1         | 1.22%   |
| Lexar               | 1         | 1.22%   |
| Gold Key            | 1         | 1.22%   |
| G.Skill             | 1         | 1.22%   |
| Corsair             | 1         | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                                 | 3         | 2.94%   |
| Unknown RAM Module 1GB SODIMM DRAM                                  | 2         | 1.96%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 2         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.96%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.96%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s               | 2         | 1.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.96%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.98%   |
| Unknown RAM Module 512MB SODIMM DRAM                                | 1         | 0.98%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.98%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                 | 1         | 0.98%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                       | 1         | 0.98%   |
| Unknown RAM Module 256MB SODIMM DDR                                 | 1         | 0.98%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 1         | 0.98%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                         | 1         | 0.98%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.98%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s                        | 1         | 0.98%   |
| Unknown RAM Module 128MB DIMM DRAM                                  | 1         | 0.98%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.98%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 1         | 0.98%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s              | 1         | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.98%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.98%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s        | 1         | 0.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.98%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.98%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 0.98%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 1         | 0.98%   |
| Samsung RAM M471B5273CH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 25        | 39.06%  |
| DDR4   | 17        | 26.56%  |
| LPDDR3 | 5         | 7.81%   |
| DDR    | 4         | 6.25%   |
| SDRAM  | 3         | 4.69%   |
| LPDDR4 | 3         | 4.69%   |
| DRAM   | 3         | 4.69%   |
| DDR2   | 3         | 4.69%   |
| DDR5   | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 84.62%  |
| Row Of Chips | 6         | 9.23%   |
| DIMM         | 2         | 3.08%   |
| Unknown      | 2         | 3.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 31.08%  |
| 8192  | 21        | 28.38%  |
| 2048  | 9         | 12.16%  |
| 1024  | 8         | 10.81%  |
| 16384 | 5         | 6.76%   |
| 512   | 5         | 6.76%   |
| 32768 | 1         | 1.35%   |
| 256   | 1         | 1.35%   |
| 128   | 1         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 20%     |
| Unknown | 10        | 13.33%  |
| 3200    | 7         | 9.33%   |
| 2667    | 7         | 9.33%   |
| 1334    | 7         | 9.33%   |
| 2400    | 6         | 8%      |
| 2133    | 4         | 5.33%   |
| 1867    | 3         | 4%      |
| 1333    | 3         | 4%      |
| 1067    | 2         | 2.67%   |
| 8400    | 1         | 1.33%   |
| 4800    | 1         | 1.33%   |
| 4199    | 1         | 1.33%   |
| 3800    | 1         | 1.33%   |
| 3266    | 1         | 1.33%   |
| 3066    | 1         | 1.33%   |
| 1400    | 1         | 1.33%   |
| 1200    | 1         | 1.33%   |
| 1066    | 1         | 1.33%   |
| 667     | 1         | 1.33%   |
| 533     | 1         | 1.33%   |

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
| Chicony Electronics                    | 15        | 20.55%  |
| Realtek Semiconductor                  | 8         | 10.96%  |
| Microdia                               | 8         | 10.96%  |
| IMC Networks                           | 8         | 10.96%  |
| Bison Electronics                      | 7         | 9.59%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 6.85%   |
| Suyin                                  | 3         | 4.11%   |
| Quanta                                 | 3         | 4.11%   |
| Apple                                  | 3         | 4.11%   |
| Syntek                                 | 2         | 2.74%   |
| Sunplus Innovation Technology          | 2         | 2.74%   |
| Trust                                  | 1         | 1.37%   |
| Silicon Motion                         | 1         | 1.37%   |
| Samsung Electronics                    | 1         | 1.37%   |
| Ricoh                                  | 1         | 1.37%   |
| Luxvisions Innotech Limited            | 1         | 1.37%   |
| Logitech                               | 1         | 1.37%   |
| Lite-On Technology                     | 1         | 1.37%   |
| Lenovo                                 | 1         | 1.37%   |
| Alcor Micro                            | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 4         | 5.41%   |
| Microdia Integrated_Webcam_HD                       | 4         | 5.41%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 4.05%   |
| IMC Networks Integrated Camera                      | 3         | 4.05%   |
| Chicony HD Webcam                                   | 3         | 4.05%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.7%    |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 2.7%    |
| Chicony Integrated Camera                           | 2         | 2.7%    |
| Bison Lenovo EasyCamera                             | 2         | 2.7%    |
| Bison Integrated Camera                             | 2         | 2.7%    |
| Trust QHD Webcam                                    | 1         | 1.35%   |
| Syntek Integrated Camera                            | 1         | 1.35%   |
| Syntek EasyCamera                                   | 1         | 1.35%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.35%   |
| Suyin HP TrueVision HD                              | 1         | 1.35%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.35%   |
| Sunplus HP Universal Camera                         | 1         | 1.35%   |
| Sunplus HD WebCam                                   | 1         | 1.35%   |
| Silicon Motion NCM-G102                             | 1         | 1.35%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.35%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.35%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.35%   |
| Realtek USB Camera                                  | 1         | 1.35%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1.35%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.35%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.35%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.35%   |
| Microdia Integrated Webcam                          | 1         | 1.35%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.35%   |
| Logitech Webcam C270                                | 1         | 1.35%   |
| Logitech Webcam C170                                | 1         | 1.35%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.35%   |
| Lenovo Integrated Webcam                            | 1         | 1.35%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.35%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.35%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 1.35%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.35%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 1.35%   |
| Chicony HP TrueVision HD Camera                     | 1         | 1.35%   |

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
| 0     | 48        | 55.81%  |
| 1     | 21        | 24.42%  |
| 2     | 13        | 15.12%  |
| 4     | 2         | 2.33%   |
| 3     | 2         | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 12        | 20.34%  |
| Fingerprint reader       | 8         | 13.56%  |
| Modem                    | 7         | 11.86%  |
| Communication controller | 6         | 10.17%  |
| Net/wireless             | 5         | 8.47%   |
| Camera                   | 5         | 8.47%   |
| Bluetooth                | 5         | 8.47%   |
| Multimedia controller    | 2         | 3.39%   |
| Chipcard                 | 2         | 3.39%   |
| Unclassified device      | 1         | 1.69%   |
| Unassigned class         | 1         | 1.69%   |
| Storage                  | 1         | 1.69%   |
| Sound                    | 1         | 1.69%   |
| Network                  | 1         | 1.69%   |
| Flash memory             | 1         | 1.69%   |
| Card reader              | 1         | 1.69%   |

