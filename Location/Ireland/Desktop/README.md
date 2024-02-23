Linux in Ireland - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

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

Total: 335

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 21D0                        | [b9cb80ae88](https://linux-hardware.org/?probe=b9cb80ae88) | Jan 23, 2024 |
| Gigabyte      | GA-MA790X-UD4P              | [4e5951814a](https://linux-hardware.org/?probe=4e5951814a) | Jan 09, 2024 |
| MSI           | B550 GAMING GEN3            | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| HP            | 8643 SMVB                   | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| Gigabyte      | B85M-D3H                    | [1dd35fdb02](https://linux-hardware.org/?probe=1dd35fdb02) | Dec 19, 2023 |
| Dell          | 051FJ8 A00                  | [18f1d4c5d0](https://linux-hardware.org/?probe=18f1d4c5d0) | Dec 18, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [647f96ad2c](https://linux-hardware.org/?probe=647f96ad2c) | Dec 08, 2023 |
| ASRock        | H310CM-DVS                  | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [8425b9dc62](https://linux-hardware.org/?probe=8425b9dc62) | Nov 30, 2023 |
| Dell          | 03NVJ6 A03                  | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| AZW           | Green G3                    | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Dell          | 0X4H68 A00                  | [9fe4290fb6](https://linux-hardware.org/?probe=9fe4290fb6) | Nov 21, 2023 |
| Dell          | 0X4H68 A00                  | [93d573033d](https://linux-hardware.org/?probe=93d573033d) | Nov 21, 2023 |
| MSI           | 970 GAMING                  | [1d3516385d](https://linux-hardware.org/?probe=1d3516385d) | Nov 16, 2023 |
| Unknown       | Unknown                     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| Dell          | 0J8H4R A00                  | [d743b33cc7](https://linux-hardware.org/?probe=d743b33cc7) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| HP            | 3399                        | [3dca1c2950](https://linux-hardware.org/?probe=3dca1c2950) | Oct 22, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO             | [88057db3aa](https://linux-hardware.org/?probe=88057db3aa) | Oct 11, 2023 |
| Dell          | 0YJPT1 A00                  | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| HP            | 0B54h D                     | [f5259ad0b1](https://linux-hardware.org/?probe=f5259ad0b1) | Sep 16, 2023 |
| Gigabyte      | B75M-D2V                    | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| ASUSTek       | TALAS                       | [094153c6f4](https://linux-hardware.org/?probe=094153c6f4) | Sep 04, 2023 |
| Dell          | 0TDG4V A01                  | [0f98d77b72](https://linux-hardware.org/?probe=0f98d77b72) | Sep 01, 2023 |
| Gigabyte      | X58A-UD7                    | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| Dell          | 0WR7PY A02                  | [db091802b1](https://linux-hardware.org/?probe=db091802b1) | Aug 26, 2023 |
| ASUSTek       | P8P67 PRO                   | [8f51778271](https://linux-hardware.org/?probe=8f51778271) | Aug 25, 2023 |
| ASUSTek       | A68HM-PLUS                  | [7e397373d8](https://linux-hardware.org/?probe=7e397373d8) | Aug 25, 2023 |
| Dell          | 0200DY A02                  | [0182dad759](https://linux-hardware.org/?probe=0182dad759) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-K               | [ea4d9240fb](https://linux-hardware.org/?probe=ea4d9240fb) | Aug 05, 2023 |
| HP            | 21D0                        | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| HP            | 21D0                        | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| Dell          | 0D28YY A00                  | [08fd0fea6a](https://linux-hardware.org/?probe=08fd0fea6a) | Jul 26, 2023 |
| HP            | 21D0                        | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| ASUSTek       | M5A78L/USB3                 | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| HP            | 21D0                        | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| Dell          | 0M5DCD A00                  | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [b24c1d471d](https://linux-hardware.org/?probe=b24c1d471d) | Jul 04, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Dell          | 0WR7PY A02                  | [ae5f4be943](https://linux-hardware.org/?probe=ae5f4be943) | Jun 20, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| HP            | 0AECh D                     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| MSI           | 970 GAMING                  | [2bed616680](https://linux-hardware.org/?probe=2bed616680) | May 23, 2023 |
| MSI           | 970 GAMING                  | [785f4bad86](https://linux-hardware.org/?probe=785f4bad86) | May 23, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [f543ce6c65](https://linux-hardware.org/?probe=f543ce6c65) | Apr 29, 2023 |
| Dell          | 051FJ8 A00                  | [f2b702b631](https://linux-hardware.org/?probe=f2b702b631) | Apr 28, 2023 |
| Dell          | 040DDP A00                  | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Gigabyte      | Z690 UD DDR4                | [690ed7960a](https://linux-hardware.org/?probe=690ed7960a) | Apr 13, 2023 |
| Dell          | 0J3C2F A00                  | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| HP            | 21D0                        | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| Gigabyte      | Z68A-D3-B3                  | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| Dell          | 0TP412                      | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Dell          | 0200DY A02                  | [4f8515b9ed](https://linux-hardware.org/?probe=4f8515b9ed) | Mar 27, 2023 |
| HP            | 0B54h D                     | [3edc678017](https://linux-hardware.org/?probe=3edc678017) | Mar 26, 2023 |
| MSI           | X470 GAMING PRO             | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| HP            | 83E9                        | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Dell          | 0JP3NX A00                  | [9d0ac027df](https://linux-hardware.org/?probe=9d0ac027df) | Mar 14, 2023 |
| ASRock        | X99 Extreme4                | [a541fe5881](https://linux-hardware.org/?probe=a541fe5881) | Mar 07, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| Dell          | 0F5C5X A00                  | [0496d0bbcf](https://linux-hardware.org/?probe=0496d0bbcf) | Feb 18, 2023 |
| Dell          | 0F5C5X A00                  | [ba5a46ec10](https://linux-hardware.org/?probe=ba5a46ec10) | Feb 18, 2023 |
| Dell          | 0200DY A02                  | [fdab522500](https://linux-hardware.org/?probe=fdab522500) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | [dd863b4bdf](https://linux-hardware.org/?probe=dd863b4bdf) | Feb 17, 2023 |
| Foxconn       | H67M-S/H67M-V/H67M          | [78dc1c5856](https://linux-hardware.org/?probe=78dc1c5856) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | [8de835c5da](https://linux-hardware.org/?probe=8de835c5da) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | [e689bce0ca](https://linux-hardware.org/?probe=e689bce0ca) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | [bc1c7ec97f](https://linux-hardware.org/?probe=bc1c7ec97f) | Feb 14, 2023 |
| Pegatron      | 2A94h                       | [b1b8672218](https://linux-hardware.org/?probe=b1b8672218) | Feb 13, 2023 |
| Shenzhen M... | F7BFC                       | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| MSI           | X470 GAMING PRO             | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| Gigabyte      | M68MT-S2P                   | [09735072af](https://linux-hardware.org/?probe=09735072af) | Jan 23, 2023 |
| Dell          | 0GXM1W A01                  | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Dell          | 0JP3NX A00                  | [21b5ec2d81](https://linux-hardware.org/?probe=21b5ec2d81) | Jan 03, 2023 |
| HP            | 21B4 A01                    | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Intel         | DQ77CP AAG67261-300         | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | [0b63acf3b2](https://linux-hardware.org/?probe=0b63acf3b2) | Dec 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| MSI           | Z170M MORTAR                | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| Dell          | 0JP3NX A00                  | [8b457c11e8](https://linux-hardware.org/?probe=8b457c11e8) | Oct 23, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| Dell          | 0WR7PY A02                  | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-A                | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b389a760a8](https://linux-hardware.org/?probe=b389a760a8) | Sep 12, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Dell          | 0TP412                      | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| MSI           | MEG Z490I UNIFY             | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Dell          | 0GY6Y8 A02                  | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| Dell          | 0JP3NX A00                  | [531e4340a6](https://linux-hardware.org/?probe=531e4340a6) | Aug 07, 2022 |
| MSI           | AMETHYST-M                  | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Dell          | 0J3C2F A00                  | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Gigabyte      | B85M-D3H                    | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| ASUSTek       | Maximus VII IMPACT          | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| Dell          | 02YYK5 A01                  | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| Dell          | 02YYK5 A01                  | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| ASUSTek       | PRIME X470-PRO              | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Foxconn       | 2ABF                        | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| ASRock        | Z68 Pro3                    | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| HP            | 21D0                        | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Dell          | 0X4H68 A00                  | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Dell          | 0X4H68 A00                  | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| ASRock        | Z68 Pro3                    | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| ASUSTek       | PRIME Z370-P                | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| HP            | 1495                        | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| MSI           | B450 GAMING PLUS            | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Gigabyte      | 970A-DS3P                   | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| Gigabyte      | B450M DS3H-CF               | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| MSI           | MS-7270                     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| ASUSTek       | PRIME X570-P                | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| Dell          | 0J37VM A01                  | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| MSI           | B450 GAMING PLUS            | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Dell          | 0X9M3X A01                  | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| ASRock        | J4105M                      | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| ASRock        | Z77 Extreme3                | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| ASUSTek       | P6X58D-E                    | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Gigabyte      | GA-MA770-UD3                | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Dell          | 07F37C A01                  | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| MSI           | MS-7270                     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | 3397                        | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| Shuttle       | FS35V4                      | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| ASUSTek       | M5A78L/USB3                 | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Dell          | 0NNNCT A01                  | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| ASUSTek       | M5A78L/USB3                 | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| Pegatron      | 2A94h                       | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| Dell          | 0GDG8Y A00                  | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| HP            | 1495                        | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| ASUSTek       | Maximus IV Extreme          | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| ASUSTek       | F2A55-M LK2                 | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| MSI           | MEG X399 CREATION           | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| MSI           | MS-7270                     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| MSI           | MS-7270                     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| HP            | 1495                        | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| MSI           | MS-7270                     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Dell          | Dimension 5100              | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| HP            | 1497                        | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| HP            | 1497                        | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Dell          | Dimension 5100              | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| ASUSTek       | H81M-PLUS                   | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| HP            | 1495                        | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| ASUSTek       | H81M-PLUS                   | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Unknown       | RS780-SB700 Unknox          | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| Foxconn       | 2ABF                        | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| HP            | 8648                        | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Foxconn       | 2ABF                        | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| HP            | 8425                        | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | M5A97 R2.0                  | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| MSI           | MEG X399 CREATION           | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| Lenovo        | ThinkCentre M58 7373BVU     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| ASUSTek       | M5A97 R2.0                  | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| ASRock        | H97M Pro4                   | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Dell          | 0FH884                      | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | 0FH884                      | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| ABIT          | KN9                         | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| ABIT          | KN9                         | [be7c3f4dc9](https://linux-hardware.org/?probe=be7c3f4dc9) | Apr 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [79ceb06042](https://linux-hardware.org/?probe=79ceb06042) | Apr 05, 2020 |
| ASUSTek       | Z87-K                       | [2ccf545fb8](https://linux-hardware.org/?probe=2ccf545fb8) | Apr 03, 2020 |
| Dell          | 0P301D A00                  | [5996aa0d7b](https://linux-hardware.org/?probe=5996aa0d7b) | Apr 02, 2020 |
| ASUSTek       | Z87-PRO                     | [cf7a7cb442](https://linux-hardware.org/?probe=cf7a7cb442) | Mar 21, 2020 |
| Lenovo        | ThinkCentre A70 7844Q2G     | [7a3df56f82](https://linux-hardware.org/?probe=7a3df56f82) | Mar 20, 2020 |
| Gigabyte      | F2A58M-DS2                  | [b5c9d31ae9](https://linux-hardware.org/?probe=b5c9d31ae9) | Mar 18, 2020 |
| Dell          | 0J3C2F A00                  | [3a37c7a548](https://linux-hardware.org/?probe=3a37c7a548) | Mar 11, 2020 |
| Lenovo        | ThinkStation D20 415892G    | [6672072cc5](https://linux-hardware.org/?probe=6672072cc5) | Mar 03, 2020 |
| ABIT          | KN9                         | [dafc30ae16](https://linux-hardware.org/?probe=dafc30ae16) | Mar 02, 2020 |
| ABIT          | KN9                         | [e26e7f08ca](https://linux-hardware.org/?probe=e26e7f08ca) | Feb 23, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [11d467ac47](https://linux-hardware.org/?probe=11d467ac47) | Feb 22, 2020 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [e53a35010c](https://linux-hardware.org/?probe=e53a35010c) | Feb 22, 2020 |
| HP            | 1998                        | [edb9bba986](https://linux-hardware.org/?probe=edb9bba986) | Jan 19, 2020 |
| ASUSTek       | P8P67 PRO                   | [0c3d1fcefe](https://linux-hardware.org/?probe=0c3d1fcefe) | Dec 05, 2019 |
| MSI           | Z77 MPower                  | [ab7afebfb6](https://linux-hardware.org/?probe=ab7afebfb6) | Nov 26, 2019 |
| MSI           | Z77 MPower                  | [77c87b6b71](https://linux-hardware.org/?probe=77c87b6b71) | Nov 26, 2019 |
| Seco          | C40 C                       | [a3f6f85e6a](https://linux-hardware.org/?probe=a3f6f85e6a) | Sep 15, 2019 |
| Seco          | C40 C                       | [16208d3700](https://linux-hardware.org/?probe=16208d3700) | Sep 04, 2019 |
| Seco          | C40 C                       | [3a7afd413f](https://linux-hardware.org/?probe=3a7afd413f) | Aug 28, 2019 |
| ASUSTek       | K5130                       | [72b7a5b445](https://linux-hardware.org/?probe=72b7a5b445) | Aug 08, 2019 |
| DFI           | INF P35                     | [7987560cdc](https://linux-hardware.org/?probe=7987560cdc) | Aug 02, 2019 |
| DFI           | INF P35                     | [0379ced795](https://linux-hardware.org/?probe=0379ced795) | Aug 02, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | [b7db1f6d08](https://linux-hardware.org/?probe=b7db1f6d08) | Jul 27, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | [bf4c96625e](https://linux-hardware.org/?probe=bf4c96625e) | Jul 27, 2019 |
| Apple         | Mac-F42C88C8 Proto1         | [649ff143ad](https://linux-hardware.org/?probe=649ff143ad) | Jul 08, 2019 |
| ASUSTek       | F2A55-M LK2                 | [93d8ad05a1](https://linux-hardware.org/?probe=93d8ad05a1) | Jun 30, 2019 |
| Shuttle       | XS35V3                      | [de0cc0ab6f](https://linux-hardware.org/?probe=de0cc0ab6f) | Jun 16, 2019 |
| Dell          | 0FJ030                      | [c3dfb2bea5](https://linux-hardware.org/?probe=c3dfb2bea5) | Jun 05, 2019 |
| Lenovo        | MAHOBAY                     | [71dd964fb5](https://linux-hardware.org/?probe=71dd964fb5) | Jun 04, 2019 |
| ASRock        | G31M-S                      | [213f2f20b6](https://linux-hardware.org/?probe=213f2f20b6) | May 24, 2019 |
| Dell          | 0Y2MRG A00                  | [f32755062c](https://linux-hardware.org/?probe=f32755062c) | May 23, 2019 |
| Dell          | 03NVJ6 A02                  | [915e0bab53](https://linux-hardware.org/?probe=915e0bab53) | May 12, 2019 |
| ASUSTek       | P8P67 PRO                   | [b0dcc92563](https://linux-hardware.org/?probe=b0dcc92563) | Apr 03, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6bae84797a](https://linux-hardware.org/?probe=6bae84797a) | Mar 22, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [9e86bfbcc2](https://linux-hardware.org/?probe=9e86bfbcc2) | Mar 22, 2019 |
| Shuttle       | FS35V4                      | [03af7dbe17](https://linux-hardware.org/?probe=03af7dbe17) | Mar 20, 2019 |
| Dell          | 0CRH6C A00                  | [300a99b1d0](https://linux-hardware.org/?probe=300a99b1d0) | Feb 10, 2019 |
| Shuttle       | XS35V3                      | [ae76390fb4](https://linux-hardware.org/?probe=ae76390fb4) | Jan 18, 2019 |
| ASUSTek       | P8P67 PRO                   | [1cfe678b48](https://linux-hardware.org/?probe=1cfe678b48) | Jan 16, 2019 |
| ASRock        | X370 Gaming-ITX/ac          | [2311962133](https://linux-hardware.org/?probe=2311962133) | Sep 30, 2018 |
| ASUSTek       | P8P67 PRO                   | [6a91010c14](https://linux-hardware.org/?probe=6a91010c14) | Jul 07, 2018 |
| ASUSTek       | P8P67 PRO                   | [e5e3ed1c7c](https://linux-hardware.org/?probe=e5e3ed1c7c) | Jun 01, 2018 |
| ASUSTek       | P8P67 PRO                   | [1b14483855](https://linux-hardware.org/?probe=1b14483855) | Feb 23, 2018 |
| ASUSTek       | P8P67 PRO                   | [bbe4f7f994](https://linux-hardware.org/?probe=bbe4f7f994) | Feb 11, 2018 |
| ASUSTek       | P8P67 PRO                   | [b32d7f9bc2](https://linux-hardware.org/?probe=b32d7f9bc2) | Jan 12, 2018 |
| Gigabyte      | H61M-S2PV                   | [7cf734ce05](https://linux-hardware.org/?probe=7cf734ce05) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 29       | 12.24%  |
| Ubuntu 18.04                 | 12       | 5.06%   |
| Debian 11                    | 9        | 3.8%    |
| ArcoLinux Rolling            | 7        | 2.95%   |
| Arch Rolling                 | 7        | 2.95%   |
| OpenMandriva 4.2             | 6        | 2.53%   |
| Manjaro                      | 6        | 2.53%   |
| Ubuntu 22.04                 | 5        | 2.11%   |
| Ubuntu 19.04                 | 5        | 2.11%   |
| Pop!_OS 22.04                | 5        | 2.11%   |
| Linux Mint 20.2              | 5        | 2.11%   |
| Linux Mint 20                | 5        | 2.11%   |
| Arch                         | 5        | 2.11%   |
| ROSA R11                     | 4        | 1.69%   |
| Pop!_OS 21.10                | 4        | 1.69%   |
| Pop!_OS 20.10                | 4        | 1.69%   |
| OpenMandriva 4.3             | 4        | 1.69%   |
| Linux Mint 20.3              | 4        | 1.69%   |
| Fedora 38                    | 4        | 1.69%   |
| Zorin 16                     | 3        | 1.27%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.27%   |
| Linux Mint 20.1              | 3        | 1.27%   |
| KDE neon 22.04               | 3        | 1.27%   |
| Gentoo 2.14                  | 3        | 1.27%   |
| Fedora 35                    | 3        | 1.27%   |
| Fedora 32                    | 3        | 1.27%   |
| BlackPanther 18.1            | 3        | 1.27%   |
| SteamOS 3.4                  | 2        | 0.84%   |
| ROSA R10                     | 2        | 0.84%   |
| OpenMandriva 4.50            | 2        | 0.84%   |
| OpenMandriva 23.03           | 2        | 0.84%   |
| OpenMandriva 23.01           | 2        | 0.84%   |
| Linux Mint 21.2              | 2        | 0.84%   |
| Linux Mint 21.1              | 2        | 0.84%   |
| Linux Mint 19                | 2        | 0.84%   |
| Linux Mint 18.3              | 2        | 0.84%   |
| KDE neon 20.04               | 2        | 0.84%   |
| Fedora 37                    | 2        | 0.84%   |
| Fedora 36                    | 2        | 0.84%   |
| Fedora 33                    | 2        | 0.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 54       | 25%     |
| Linux Mint   | 22       | 10.19%  |
| OpenMandriva | 15       | 6.94%   |
| Fedora       | 14       | 6.48%   |
| Pop!_OS      | 13       | 6.02%   |
| Debian       | 13       | 6.02%   |
| Arch         | 12       | 5.56%   |
| Manjaro      | 10       | 4.63%   |
| ROSA         | 7        | 3.24%   |
| ArcoLinux    | 7        | 3.24%   |
| KDE neon     | 6        | 2.78%   |
| Zorin        | 4        | 1.85%   |
| Xubuntu      | 4        | 1.85%   |
| Gentoo       | 4        | 1.85%   |
| SteamOS      | 3        | 1.39%   |
| openSUSE     | 3        | 1.39%   |
| BlackPanther | 3        | 1.39%   |
| MX           | 2        | 0.93%   |
| Lubuntu      | 2        | 0.93%   |
| Kubuntu      | 2        | 0.93%   |
| Kali         | 2        | 0.93%   |
| Endless      | 2        | 0.93%   |
| Elementary   | 2        | 0.93%   |
| Solus        | 1        | 0.46%   |
| Peppermint   | 1        | 0.46%   |
| Parrot       | 1        | 0.46%   |
| Nobara       | 1        | 0.46%   |
| NixOS        | 1        | 0.46%   |
| Linux Lite   | 1        | 0.46%   |
| Garuda Linux | 1        | 0.46%   |
| Feren OS     | 1        | 0.46%   |
| Clear Linux  | 1        | 0.46%   |
| Alpine       | 1        | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.4.0-42-generic                 | 7        | 2.55%   |
| 5.10.14-desktop-1omv4002         | 6        | 2.18%   |
| 5.4.0-48-generic                 | 4        | 1.45%   |
| 5.16.7-desktop-1omv4003          | 4        | 1.45%   |
| 5.10.0-23-amd64                  | 4        | 1.45%   |
| 6.2.0-26-generic                 | 3        | 1.09%   |
| 5.8.0-7630-generic               | 3        | 1.09%   |
| 5.4.0-91-generic                 | 3        | 1.09%   |
| 5.4.0-47-generic                 | 3        | 1.09%   |
| 5.3.0-28-generic                 | 3        | 1.09%   |
| 5.17.5-arch1-1                   | 3        | 1.09%   |
| 5.15.11-76051511-generic         | 3        | 1.09%   |
| 4.18.16-desktop-1bP              | 3        | 1.09%   |
| 6.2.6-desktop-1omv2390           | 2        | 0.73%   |
| 5.8.14-arch1-1                   | 2        | 0.73%   |
| 5.8.0-43-generic                 | 2        | 0.73%   |
| 5.8.0-41-generic                 | 2        | 0.73%   |
| 5.4.0-88-generic                 | 2        | 0.73%   |
| 5.4.0-77-generic                 | 2        | 0.73%   |
| 5.4.0-72-generic                 | 2        | 0.73%   |
| 5.4.0-37-generic                 | 2        | 0.73%   |
| 5.3.0-45-generic                 | 2        | 0.73%   |
| 5.19.0-35-generic                | 2        | 0.73%   |
| 5.17.5-76051705-generic          | 2        | 0.73%   |
| 5.16.15-76051615-generic         | 2        | 0.73%   |
| 5.15.0-56-generic                | 2        | 0.73%   |
| 5.15.0-46-generic                | 2        | 0.73%   |
| 5.13.13-arch1-1                  | 2        | 0.73%   |
| 5.13.0-39-generic                | 2        | 0.73%   |
| 5.12.4-desktop-1omv4050          | 2        | 0.73%   |
| 5.11.0-43-generic                | 2        | 0.73%   |
| 5.0.0-23-generic                 | 2        | 0.73%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 2        | 0.73%   |
| 4.9.60-nrj-desktop-1rosa-i586    | 2        | 0.73%   |
| 4.9.155-nrj-desktop-1rosa-x86_64 | 2        | 0.73%   |
| 4.18.0-25-generic                | 2        | 0.73%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 2        | 0.73%   |
| 4.10.0-38-generic                | 2        | 0.73%   |
| 6.7.0-1-ck-generic-v3            | 1        | 0.36%   |
| 6.6.4-1-liquorix-amd64           | 1        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 37       | 14.29%  |
| 5.15.0  | 13       | 5.02%   |
| 5.8.0   | 10       | 3.86%   |
| 4.15.0  | 10       | 3.86%   |
| 5.10.0  | 9        | 3.47%   |
| 5.3.0   | 8        | 3.09%   |
| 5.19.0  | 8        | 3.09%   |
| 5.13.0  | 7        | 2.7%    |
| 5.11.0  | 7        | 2.7%    |
| 5.0.0   | 7        | 2.7%    |
| 6.2.0   | 6        | 2.32%   |
| 5.17.5  | 6        | 2.32%   |
| 5.10.14 | 6        | 2.32%   |
| 4.18.0  | 5        | 1.93%   |
| 5.16.7  | 4        | 1.54%   |
| 6.1.0   | 3        | 1.16%   |
| 5.15.11 | 3        | 1.16%   |
| 4.18.16 | 3        | 1.16%   |
| 6.3.8   | 2        | 0.77%   |
| 6.2.8   | 2        | 0.77%   |
| 6.2.6   | 2        | 0.77%   |
| 6.2.11  | 2        | 0.77%   |
| 6.0.6   | 2        | 0.77%   |
| 5.8.14  | 2        | 0.77%   |
| 5.18.10 | 2        | 0.77%   |
| 5.17.6  | 2        | 0.77%   |
| 5.16.15 | 2        | 0.77%   |
| 5.16.11 | 2        | 0.77%   |
| 5.15.6  | 2        | 0.77%   |
| 5.15.12 | 2        | 0.77%   |
| 5.13.13 | 2        | 0.77%   |
| 5.12.4  | 2        | 0.77%   |
| 5.11.11 | 2        | 0.77%   |
| 5.11.10 | 2        | 0.77%   |
| 4.9.60  | 2        | 0.77%   |
| 4.9.155 | 2        | 0.77%   |
| 4.19.0  | 2        | 0.77%   |
| 4.10.0  | 2        | 0.77%   |
| 6.7.0   | 1        | 0.39%   |
| 6.6.4   | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 39       | 15.48%  |
| 5.15    | 24       | 9.52%   |
| 5.10    | 19       | 7.54%   |
| 5.8     | 15       | 5.95%   |
| 6.2     | 14       | 5.56%   |
| 5.11    | 13       | 5.16%   |
| 5.16    | 10       | 3.97%   |
| 5.13    | 10       | 3.97%   |
| 4.15    | 10       | 3.97%   |
| 5.19    | 9        | 3.57%   |
| 5.17    | 9        | 3.57%   |
| 6.1     | 8        | 3.17%   |
| 5.3     | 8        | 3.17%   |
| 4.18    | 8        | 3.17%   |
| 5.0     | 7        | 2.78%   |
| 6.4     | 6        | 2.38%   |
| 6.0     | 5        | 1.98%   |
| 5.12    | 5        | 1.98%   |
| 6.3     | 4        | 1.59%   |
| 6.6     | 3        | 1.19%   |
| 6.5     | 3        | 1.19%   |
| 5.7     | 3        | 1.19%   |
| 5.6     | 3        | 1.19%   |
| 5.18    | 3        | 1.19%   |
| 4.9     | 3        | 1.19%   |
| 4.19    | 2        | 0.79%   |
| 4.10    | 2        | 0.79%   |
| 6.7     | 1        | 0.4%    |
| 5.9     | 1        | 0.4%    |
| 5.5     | 1        | 0.4%    |
| 5.14    | 1        | 0.4%    |
| 4.4     | 1        | 0.4%    |
| 4.20    | 1        | 0.4%    |
| 4.1     | 1        | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 204      | 98.08%  |
| i686   | 4        | 1.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 79       | 35.59%  |
| KDE5            | 51       | 22.97%  |
| Unknown         | 28       | 12.61%  |
| XFCE            | 25       | 11.26%  |
| X-Cinnamon      | 12       | 5.41%   |
| MATE            | 8        | 3.6%    |
| KDE             | 6        | 2.7%    |
| KDE4            | 4        | 1.8%    |
| LXQt            | 3        | 1.35%   |
| Pantheon        | 2        | 0.9%    |
| LXDE            | 1        | 0.45%   |
| LeftWM          | 1        | 0.45%   |
| GNOME Flashback | 1        | 0.45%   |
| Cinnamon        | 1        | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 167      | 79.15%  |
| Wayland | 23       | 10.9%   |
| Unknown | 17       | 8.06%   |
| Tty     | 4        | 1.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 108      | 48.87%  |
| SDDM    | 47       | 21.27%  |
| LightDM | 23       | 10.41%  |
| GDM     | 21       | 9.5%    |
| GDM3    | 11       | 4.98%   |
| TDM     | 5        | 2.26%   |
| KDM     | 4        | 1.81%   |
| MDM     | 1        | 0.45%   |
| LXDM    | 1        | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_IE   | 98       | 44.75%  |
| en_GB   | 45       | 20.55%  |
| en_US   | 35       | 15.98%  |
| Unknown | 28       | 12.79%  |
| C       | 4        | 1.83%   |
| pl_PL   | 2        | 0.91%   |
| es_ES   | 2        | 0.91%   |
| pt_BR   | 1        | 0.46%   |
| hu_HU   | 1        | 0.46%   |
| en_BW   | 1        | 0.46%   |
| de_DE   | 1        | 0.46%   |
| C.UTF8  | 1        | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 131      | 61.79%  |
| EFI  | 81       | 38.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 157      | 73.36%  |
| Btrfs   | 24       | 11.21%  |
| Overlay | 16       | 7.48%   |
| Unknown | 7        | 3.27%   |
| Tmpfs   | 4        | 1.87%   |
| Xfs     | 3        | 1.4%    |
| Zfs     | 2        | 0.93%   |
| Fake    | 1        | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 105      | 47.51%  |
| GPT     | 89       | 40.27%  |
| MBR     | 27       | 12.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 77%     |
| Yes       | 49       | 23%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 68.37%  |
| Yes       | 68       | 31.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 44       | 21.36%  |
| Dell                                 | 43       | 20.87%  |
| Gigabyte Technology                  | 32       | 15.53%  |
| MSI                                  | 18       | 8.74%   |
| Hewlett-Packard                      | 18       | 8.74%   |
| ASRock                               | 14       | 6.8%    |
| Lenovo                               | 12       | 5.83%   |
| Foxconn                              | 5        | 2.43%   |
| Intel                                | 3        | 1.46%   |
| Shuttle                              | 2        | 0.97%   |
| Seco                                 | 2        | 0.97%   |
| Apple                                | 2        | 0.97%   |
| Unknown                              | 2        | 0.97%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.49%   |
| Pegatron                             | 1        | 0.49%   |
| Packard Bell                         | 1        | 0.49%   |
| MiTAC                                | 1        | 0.49%   |
| Medion                               | 1        | 0.49%   |
| DFI                                  | 1        | 0.49%   |
| AZW                                  | 1        | 0.49%   |
| ANGXUN                               | 1        | 0.49%   |
| ABIT                                 | 1        | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex 7010                         | 8        | 3.88%   |
| ASUS All Series                            | 7        | 3.4%    |
| Gigabyte B450M DS3H                        | 5        | 2.43%   |
| Dell OptiPlex 790                          | 4        | 1.94%   |
| Dell OptiPlex 780                          | 4        | 1.94%   |
| HP Compaq 8200 Elite SFF PC                | 3        | 1.46%   |
| Dell OptiPlex 7020                         | 3        | 1.46%   |
| ASUS ROG STRIX B450-F GAMING               | 3        | 1.46%   |
| ASUS P8P67 PRO                             | 3        | 1.46%   |
| Seco C40                                   | 2        | 0.97%   |
| MSI MS-7C37                                | 2        | 0.97%   |
| MSI MS-7B86                                | 2        | 0.97%   |
| MSI MS-7B79                                | 2        | 0.97%   |
| Lenovo ThinkStation D20 415892G            | 2        | 0.97%   |
| Lenovo ThinkCentre E73 10DS000TUK          | 2        | 0.97%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 0.97%   |
| Gigabyte X570 AORUS ULTRA                  | 2        | 0.97%   |
| Gigabyte A320M-S2H                         | 2        | 0.97%   |
| Foxconn Pro 3500 Series                    | 2        | 0.97%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 0.97%   |
| ASUS M5A78L/USB3                           | 2        | 0.97%   |
| Unknown                                    | 2        | 0.97%   |
| Shuttle XS35V4                             | 1        | 0.49%   |
| Shuttle XS35V3                             | 1        | 0.49%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.49%   |
| Pegatron Pro 3010 Microtower PC            | 1        | 0.49%   |
| Packard Bell Vegas2                        | 1        | 0.49%   |
| MSI Pro 3515 Series                        | 1        | 0.49%   |
| MSI MS-7C84                                | 1        | 0.49%   |
| MSI MS-7C77                                | 1        | 0.49%   |
| MSI MS-7C02                                | 1        | 0.49%   |
| MSI MS-7B92                                | 1        | 0.49%   |
| MSI MS-7B89                                | 1        | 0.49%   |
| MSI MS-7972                                | 1        | 0.49%   |
| MSI MS-7751                                | 1        | 0.49%   |
| MSI MS-7693                                | 1        | 0.49%   |
| MSI MS-7636                                | 1        | 0.49%   |
| MSI MS-7270                                | 1        | 0.49%   |
| MSI ER883AA-ABA M7470N                     | 1        | 0.49%   |
| MiTAC PD14TI AAPD14TI-101                  | 1        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 27       | 13.11%  |
| Lenovo ThinkCentre                         | 9        | 4.37%   |
| ASUS PRIME                                 | 8        | 3.88%   |
| HP Compaq                                  | 7        | 3.4%    |
| ASUS TUF                                   | 7        | 3.4%    |
| ASUS All                                   | 7        | 3.4%    |
| Gigabyte B450M                             | 5        | 2.43%   |
| Dell Precision                             | 5        | 2.43%   |
| HP EliteDesk                               | 4        | 1.94%   |
| Foxconn Pro                                | 3        | 1.46%   |
| ASUS ROG                                   | 3        | 1.46%   |
| ASUS P8P67                                 | 3        | 1.46%   |
| Seco C40                                   | 2        | 0.97%   |
| MSI MS-7C37                                | 2        | 0.97%   |
| MSI MS-7B86                                | 2        | 0.97%   |
| MSI MS-7B79                                | 2        | 0.97%   |
| Lenovo ThinkStation                        | 2        | 0.97%   |
| Intel DESKTOP                              | 2        | 0.97%   |
| Gigabyte X570                              | 2        | 0.97%   |
| Gigabyte TRX40                             | 2        | 0.97%   |
| Gigabyte B450                              | 2        | 0.97%   |
| Gigabyte A320M-S2H                         | 2        | 0.97%   |
| Dell XPS                                   | 2        | 0.97%   |
| Dell Vostro                                | 2        | 0.97%   |
| Dell Inspiron                              | 2        | 0.97%   |
| ASUS Maximus                               | 2        | 0.97%   |
| ASUS M5A78L                                | 2        | 0.97%   |
| ASUS Crosshair                             | 2        | 0.97%   |
| ASRock Z77                                 | 2        | 0.97%   |
| Unknown                                    | 2        | 0.97%   |
| Shuttle XS35V4                             | 1        | 0.49%   |
| Shuttle XS35V3                             | 1        | 0.49%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.49%   |
| Pegatron Pro                               | 1        | 0.49%   |
| Packard Bell Vegas2                        | 1        | 0.49%   |
| MSI Pro                                    | 1        | 0.49%   |
| MSI MS-7C84                                | 1        | 0.49%   |
| MSI MS-7C77                                | 1        | 0.49%   |
| MSI MS-7C02                                | 1        | 0.49%   |
| MSI MS-7B92                                | 1        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 26       | 12.62%  |
| 2013    | 24       | 11.65%  |
| 2012    | 23       | 11.17%  |
| 2011    | 21       | 10.19%  |
| 2010    | 17       | 8.25%   |
| 2019    | 15       | 7.28%   |
| 2020    | 12       | 5.83%   |
| 2014    | 12       | 5.83%   |
| 2008    | 11       | 5.34%   |
| 2017    | 9        | 4.37%   |
| 2015    | 9        | 4.37%   |
| 2009    | 6        | 2.91%   |
| 2022    | 5        | 2.43%   |
| 2006    | 5        | 2.43%   |
| 2007    | 3        | 1.46%   |
| 2023    | 2        | 0.97%   |
| 2021    | 2        | 0.97%   |
| 2005    | 2        | 0.97%   |
| 2016    | 1        | 0.49%   |
| Unknown | 1        | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 206      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 201      | 97.1%   |
| Enabled  | 6        | 2.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 206      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 52       | 24.53%  |
| 8.01-16.0       | 50       | 23.58%  |
| 3.01-4.0        | 32       | 15.09%  |
| 32.01-64.0      | 30       | 14.15%  |
| 4.01-8.0        | 25       | 11.79%  |
| 64.01-256.0     | 11       | 5.19%   |
| 24.01-32.0      | 7        | 3.3%    |
| 1.01-2.0        | 3        | 1.42%   |
| More than 256.0 | 1        | 0.47%   |
| 0.51-1.0        | 1        | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 91       | 37.92%  |
| 2.01-3.0   | 50       | 20.83%  |
| 4.01-8.0   | 35       | 14.58%  |
| 3.01-4.0   | 30       | 12.5%   |
| 8.01-16.0  | 16       | 6.67%   |
| 0.51-1.0   | 15       | 6.25%   |
| 32.01-64.0 | 1        | 0.42%   |
| 0.01-0.5   | 1        | 0.42%   |
| Unknown    | 1        | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 34.5%   |
| 2      | 53       | 23.14%  |
| 3      | 33       | 14.41%  |
| 4      | 29       | 12.66%  |
| 5      | 14       | 6.11%   |
| 7      | 6        | 2.62%   |
| 6      | 5        | 2.18%   |
| 0      | 4        | 1.75%   |
| 10     | 3        | 1.31%   |
| 11     | 1        | 0.44%   |
| 9      | 1        | 0.44%   |
| 8      | 1        | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 113      | 52.8%   |
| No        | 101      | 47.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 203      | 98.54%  |
| No        | 3        | 1.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 56.28%  |
| No        | 94       | 43.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 133      | 62.44%  |
| Yes       | 80       | 37.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ireland | 206      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Dublin       | 117      | 53.18%  |
| Cork         | 13       | 5.91%   |
| Limerick     | 8        | 3.64%   |
| Sligo        | 4        | 1.82%   |
| Kenmare      | 4        | 1.82%   |
| Gorey        | 4        | 1.82%   |
| Tuam         | 3        | 1.36%   |
| Portlaoise   | 3        | 1.36%   |
| Naas         | 3        | 1.36%   |
| Ennis        | 3        | 1.36%   |
| Athlone      | 3        | 1.36%   |
| Wexford      | 2        | 0.91%   |
| Swords       | 2        | 0.91%   |
| Oranmore     | 2        | 0.91%   |
| Nenagh       | 2        | 0.91%   |
| Kildare      | 2        | 0.91%   |
| Drogheda     | 2        | 0.91%   |
| Cavan        | 2        | 0.91%   |
| Blackrock    | 2        | 0.91%   |
| Ballincollig | 2        | 0.91%   |
| Waterford    | 1        | 0.45%   |
| Tullamore    | 1        | 0.45%   |
| Tralee       | 1        | 0.45%   |
| Tobercurry   | 1        | 0.45%   |
| Tipperary    | 1        | 0.45%   |
| Summerhill   | 1        | 0.45%   |
| Shanagolden  | 1        | 0.45%   |
| Roscommon    | 1        | 0.45%   |
| Navan        | 1        | 0.45%   |
| Moyne        | 1        | 0.45%   |
| Maynooth     | 1        | 0.45%   |
| Mallow       | 1        | 0.45%   |
| Lucan        | 1        | 0.45%   |
| Loughrea     | 1        | 0.45%   |
| Listowel     | 1        | 0.45%   |
| Letterkenny  | 1        | 0.45%   |
| Killorglin   | 1        | 0.45%   |
| Killarney    | 1        | 0.45%   |
| Kilkenny     | 1        | 0.45%   |
| Kilcoole     | 1        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 83       | 175    | 20.39%  |
| Seagate                     | 77       | 143    | 18.92%  |
| Samsung Electronics         | 54       | 101    | 13.27%  |
| Crucial                     | 26       | 31     | 6.39%   |
| Toshiba                     | 21       | 34     | 5.16%   |
| Hitachi                     | 18       | 29     | 4.42%   |
| SanDisk                     | 16       | 29     | 3.93%   |
| Kingston                    | 14       | 29     | 3.44%   |
| A-DATA Technology           | 9        | 15     | 2.21%   |
| China                       | 7        | 7      | 1.72%   |
| Phison                      | 6        | 11     | 1.47%   |
| Intel                       | 5        | 5      | 1.23%   |
| Verbatim                    | 4        | 4      | 0.98%   |
| Micron/Crucial Technology   | 4        | 8      | 0.98%   |
| Micron Technology           | 4        | 4      | 0.98%   |
| HGST                        | 4        | 4      | 0.98%   |
| OCZ                         | 3        | 3      | 0.74%   |
| Transcend                   | 2        | 2      | 0.49%   |
| Team                        | 2        | 2      | 0.49%   |
| Silicon Motion              | 2        | 9      | 0.49%   |
| Patriot                     | 2        | 3      | 0.49%   |
| Netac                       | 2        | 2      | 0.49%   |
| Maxtor                      | 2        | 2      | 0.49%   |
| LITEON                      | 2        | 2      | 0.49%   |
| Kingston Technology Company | 2        | 2      | 0.49%   |
| ADATA Technology            | 2        | 2      | 0.49%   |
| Unknown                     | 2        | 2      | 0.49%   |
| Western Digital             | 1        | 2      | 0.25%   |
| WDS100T1                    | 1        | 1      | 0.25%   |
| USB3.0                      | 1        | 1      | 0.25%   |
| Unknown                     | 1        | 1      | 0.25%   |
| Union Memory (Shenzhen)     | 1        | 1      | 0.25%   |
| Union Memory                | 1        | 1      | 0.25%   |
| SABRENT                     | 1        | 1      | 0.25%   |
| QNAP                        | 1        | 17     | 0.25%   |
| PNY                         | 1        | 1      | 0.25%   |
| Palit                       | 1        | 1      | 0.25%   |
| MaxDigital                  | 1        | 1      | 0.25%   |
| KIOXIA                      | 1        | 3      | 0.25%   |
| KingSpec                    | 1        | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 7        | 1.43%   |
| Seagate ST1000DM010-2EP102 1TB   | 7        | 1.43%   |
| Seagate ST8000DM004-2CX188 8TB   | 6        | 1.22%   |
| Seagate ST2000DL003-9VT166 2TB   | 6        | 1.22%   |
| WDC WD10EURX-83UY4Y0 1TB         | 5        | 1.02%   |
| Kingston SA400S37240G 240GB SSD  | 5        | 1.02%   |
| Crucial CT500MX500SSD1 500GB     | 5        | 1.02%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 0.81%   |
| Verbatim Vi550 S3 SSD 512GB      | 4        | 0.81%   |
| Seagate ST3500312CS 500GB        | 4        | 0.81%   |
| Samsung SSD 850 EVO 500GB        | 4        | 0.81%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 0.81%   |
| A-DATA SU650 240GB SSD           | 4        | 0.81%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 3        | 0.61%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 3        | 0.61%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.61%   |
| WDC WD10EALX-009BA0 1TB          | 3        | 0.61%   |
| Toshiba DT01ACA100 1TB           | 3        | 0.61%   |
| Seagate ST3500418AS 500GB        | 3        | 0.61%   |
| Seagate ST31000528AS 1TB         | 3        | 0.61%   |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 0.61%   |
| Seagate Expansion Desk 8TB       | 3        | 0.61%   |
| SanDisk NVMe SSD Drive 500GB     | 3        | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.61%   |
| Samsung SSD 870 EVO 1TB          | 3        | 0.61%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.61%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.61%   |
| Phison Sabrent 2TB               | 3        | 0.61%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.61%   |
| Hitachi HDS721616PLA380 160GB    | 3        | 0.61%   |
| Hitachi HDS721032CLA362 320GB    | 3        | 0.61%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.41%   |
| WDC WD5000BPKT-60PK4T0 500GB     | 2        | 0.41%   |
| WDC WD5000AZLX-08K2TA0 500GB     | 2        | 0.41%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 0.41%   |
| WDC WD40EZRZ-19GXCB0 4TB         | 2        | 0.41%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.41%   |
| WDC WD4005FZBX-00K5WB0 4TB       | 2        | 0.41%   |
| WDC WD3200AVJS-63B6A0 320GB      | 2        | 0.41%   |
| WDC WD2500AAKX-753CA1 250GB      | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 76       | 141    | 36.02%  |
| WDC                 | 75       | 163    | 35.55%  |
| Toshiba             | 18       | 30     | 8.53%   |
| Hitachi             | 18       | 29     | 8.53%   |
| Samsung Electronics | 9        | 13     | 4.27%   |
| HGST                | 4        | 4      | 1.9%    |
| Maxtor              | 2        | 2      | 0.95%   |
| Unknown             | 1        | 1      | 0.47%   |
| QNAP                | 1        | 17     | 0.47%   |
| KESU                | 1        | 1      | 0.47%   |
| Inateck             | 1        | 1      | 0.47%   |
| Fujitsu             | 1        | 3      | 0.47%   |
| FNK TECH            | 1        | 1      | 0.47%   |
| ExcelStor           | 1        | 2      | 0.47%   |
| DAS                 | 1        | 4      | 0.47%   |
| ASMT                | 1        | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 33       | 59     | 23.74%  |
| Crucial             | 24       | 29     | 17.27%  |
| Kingston            | 13       | 27     | 9.35%   |
| SanDisk             | 11       | 16     | 7.91%   |
| China               | 7        | 7      | 5.04%   |
| A-DATA Technology   | 7        | 12     | 5.04%   |
| WDC                 | 5        | 8      | 3.6%    |
| Verbatim            | 4        | 4      | 2.88%   |
| Intel               | 4        | 4      | 2.88%   |
| OCZ                 | 3        | 3      | 2.16%   |
| Transcend           | 2        | 2      | 1.44%   |
| Team                | 2        | 2      | 1.44%   |
| Patriot             | 2        | 3      | 1.44%   |
| Netac               | 2        | 2      | 1.44%   |
| Micron Technology   | 2        | 2      | 1.44%   |
| LITEON              | 2        | 2      | 1.44%   |
| Unknown             | 2        | 2      | 1.44%   |
| USB3.0              | 1        | 1      | 0.72%   |
| Toshiba             | 1        | 1      | 0.72%   |
| SABRENT             | 1        | 1      | 0.72%   |
| PNY                 | 1        | 1      | 0.72%   |
| Palit               | 1        | 1      | 0.72%   |
| KingSpec            | 1        | 1      | 0.72%   |
| KingDian            | 1        | 1      | 0.72%   |
| Integral            | 1        | 1      | 0.72%   |
| Hikvision           | 1        | 1      | 0.72%   |
| Hewlett-Packard     | 1        | 2      | 0.72%   |
| Fanxiang            | 1        | 1      | 0.72%   |
| DRVEO               | 1        | 1      | 0.72%   |
| Corsair             | 1        | 2      | 0.72%   |
| Apple               | 1        | 1      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 149      | 413    | 46.27%  |
| SSD     | 114      | 200    | 35.4%   |
| NVMe    | 52       | 99     | 16.15%  |
| Unknown | 7        | 7      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 190      | 592    | 72.24%  |
| NVMe | 52       | 99     | 19.77%  |
| SAS  | 21       | 28     | 7.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 140      | 299    | 46.2%   |
| 0.51-1.0   | 91       | 175    | 30.03%  |
| 1.01-2.0   | 33       | 51     | 10.89%  |
| 3.01-4.0   | 15       | 32     | 4.95%   |
| 4.01-10.0  | 13       | 39     | 4.29%   |
| 2.01-3.0   | 9        | 14     | 2.97%   |
| 10.01-20.0 | 2        | 3      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 44       | 18.72%  |
| 251-500        | 39       | 16.6%   |
| 501-1000       | 37       | 15.74%  |
| More than 3000 | 33       | 14.04%  |
| 1001-2000      | 23       | 9.79%   |
| 51-100         | 16       | 6.81%   |
| 2001-3000      | 14       | 5.96%   |
| 1-20           | 11       | 4.68%   |
| Unknown        | 11       | 4.68%   |
| 21-50          | 7        | 2.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 74       | 30.45%  |
| 51-100         | 29       | 11.93%  |
| 101-250        | 28       | 11.52%  |
| 501-1000       | 28       | 11.52%  |
| 21-50          | 24       | 9.88%   |
| More than 3000 | 17       | 7%      |
| 251-500        | 12       | 4.94%   |
| 1001-2000      | 11       | 4.53%   |
| Unknown        | 11       | 4.53%   |
| 2001-3000      | 9        | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST2000DL003-9VT166 2TB           | 4        | 6      | 8.33%   |
| WDC WD10EALX-009BA0 1TB                  | 3        | 8      | 6.25%   |
| WDC WD3200AVJS-63B6A0 320GB              | 2        | 2      | 4.17%   |
| WDC WD2500AAKX-753CA1 250GB              | 2        | 4      | 4.17%   |
| Western Digital SN730 500GB              | 1        | 2      | 2.08%   |
| WDC WD7500BPKX-00HPJT0 752GB             | 1        | 1      | 2.08%   |
| WDC WD5000HHTZ-04N21V0 500GB             | 1        | 3      | 2.08%   |
| WDC WD5000BEVT-35A0RT0 500GB             | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-001CA0 500GB              | 1        | 2      | 2.08%   |
| WDC WD400JB-00FMA0 40GB                  | 1        | 2      | 2.08%   |
| WDC WD2500BEKT-75A25T0 250GB             | 1        | 1      | 2.08%   |
| WDC WD2500AAKX-603CA0 250GB              | 1        | 1      | 2.08%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1        | 2      | 2.08%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1      | 2.08%   |
| WDC WD1001FALS-00E8B0 1TB                | 1        | 2      | 2.08%   |
| Toshiba MK1059GSM 1TB                    | 1        | 1      | 2.08%   |
| Toshiba DT01ACA050 500GB                 | 1        | 3      | 2.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 2.08%   |
| Seagate ST4000DX001-1CE168 4TB           | 1        | 1      | 2.08%   |
| Seagate ST3500418AS 500GB                | 1        | 3      | 2.08%   |
| Seagate ST320LT009-9WC142 320GB          | 1        | 1      | 2.08%   |
| Seagate ST31500541AS 1TB                 | 1        | 1      | 2.08%   |
| Seagate ST3120026A 120GB                 | 1        | 1      | 2.08%   |
| Seagate ST31000333AS 1TB                 | 1        | 2      | 2.08%   |
| Seagate ST3000DM001-1ER166 3TB           | 1        | 1      | 2.08%   |
| SanDisk SSD PLUS 480GB                   | 1        | 1      | 2.08%   |
| Samsung Electronics SSD 970 EVO Plus 2TB | 1        | 1      | 2.08%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 2.08%   |
| Netac SSD 128GB                          | 1        | 1      | 2.08%   |
| Micron Technology 2300 NVMe 512GB        | 1        | 1      | 2.08%   |
| Maxtor STM3250310AS 250GB                | 1        | 1      | 2.08%   |
| Intel SSDSA2M080G2GC 80GB                | 1        | 1      | 2.08%   |
| Inateck ASM1153E 240GB                   | 1        | 1      | 2.08%   |
| Hitachi HUS724030ALA640 3TB              | 1        | 2      | 2.08%   |
| Hitachi HDT721016SLA380 160GB            | 1        | 2      | 2.08%   |
| Hitachi HDS721010CLA332 1TB              | 1        | 1      | 2.08%   |
| Hitachi HDS721010CLA330 1TB              | 1        | 1      | 2.08%   |
| HGST HTS541010A7E630 1TB                 | 1        | 1      | 2.08%   |
| DRVEO X1 SSD 480GB                       | 1        | 1      | 2.08%   |
| China T480 480GB SSD                     | 1        | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 30     | 31.11%  |
| Seagate             | 12       | 17     | 26.67%  |
| Hitachi             | 4        | 6      | 8.89%   |
| Toshiba             | 2        | 4      | 4.44%   |
| Samsung Electronics | 2        | 2      | 4.44%   |
| Western Digital     | 1        | 2      | 2.22%   |
| SanDisk             | 1        | 1      | 2.22%   |
| Netac               | 1        | 1      | 2.22%   |
| Micron Technology   | 1        | 1      | 2.22%   |
| Maxtor              | 1        | 1      | 2.22%   |
| Intel               | 1        | 1      | 2.22%   |
| Inateck             | 1        | 1      | 2.22%   |
| HGST                | 1        | 1      | 2.22%   |
| DRVEO               | 1        | 1      | 2.22%   |
| China               | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 30     | 38.89%  |
| Seagate             | 12       | 17     | 33.33%  |
| Hitachi             | 4        | 6      | 11.11%  |
| Toshiba             | 2        | 4      | 5.56%   |
| Samsung Electronics | 1        | 1      | 2.78%   |
| Maxtor              | 1        | 1      | 2.78%   |
| Inateck             | 1        | 1      | 2.78%   |
| HGST                | 1        | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 61     | 75.68%  |
| SSD  | 6        | 6      | 16.22%  |
| NVMe | 3        | 4      | 8.11%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 118      | 353    | 47.58%  |
| Works    | 94       | 295    | 37.9%   |
| Malfunc  | 36       | 71     | 14.52%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 129      | 43.88%  |
| AMD                          | 67       | 22.79%  |
| Samsung Electronics          | 20       | 6.8%    |
| SanDisk                      | 10       | 3.4%    |
| Marvell Technology Group     | 10       | 3.4%    |
| ASMedia Technology           | 10       | 3.4%    |
| JMicron Technology           | 7        | 2.38%   |
| Phison Electronics           | 6        | 2.04%   |
| Micron/Crucial Technology    | 6        | 2.04%   |
| Nvidia                       | 5        | 1.7%    |
| LSI Logic / Symbios Logic    | 4        | 1.36%   |
| Toshiba America Info Systems | 3        | 1.02%   |
| Kingston Technology Company  | 3        | 1.02%   |
| Union Memory (Shenzhen)      | 2        | 0.68%   |
| Silicon Motion               | 2        | 0.68%   |
| Realtek Semiconductor        | 2        | 0.68%   |
| Micron Technology            | 2        | 0.68%   |
| ADATA Technology             | 2        | 0.68%   |
| ULi Electronics              | 1        | 0.34%   |
| Seagate Technology           | 1        | 0.34%   |
| KIOXIA                       | 1        | 0.34%   |
| Broadcom / LSI               | 1        | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43       | 11.38%  |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 5.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 4.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 3.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 2.91%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 10       | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.38%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 2.12%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.85%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.59%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 1.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.32%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.32%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4        | 1.06%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.06%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 0.79%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 0.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.79%   |
| AMD 600 Series Chipset SATA Controller                                                  | 3        | 0.79%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                                   | 2        | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.53%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 167      | 57.59%  |
| IDE  | 54       | 18.62%  |
| NVMe | 52       | 17.93%  |
| RAID | 14       | 4.83%   |
| SCSI | 3        | 1.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 132      | 64.08%  |
| AMD    | 73       | 35.44%  |
| iSH    | 1        | 0.49%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz               | 7        | 3.33%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 7        | 3.33%   |
| AMD Ryzen 5 3600 6-Core Processor              | 7        | 3.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 5        | 2.38%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 4        | 1.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz               | 4        | 1.9%    |
| Intel Core i3-2100 CPU @ 3.10GHz               | 4        | 1.9%    |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 1.9%    |
| AMD Ryzen 5 2600X Six-Core Processor           | 4        | 1.9%    |
| Intel Pentium 4 CPU 3.00GHz                    | 3        | 1.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 3        | 1.43%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 3        | 1.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 3        | 1.43%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.43%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 3        | 1.43%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 1.43%   |
| AMD Athlon II X4 620 Processor                 | 3        | 1.43%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 2        | 0.95%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 2        | 0.95%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 0.95%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 2        | 0.95%   |
| Intel Core i5-8500T CPU @ 2.10GHz              | 2        | 0.95%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 2        | 0.95%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 2        | 0.95%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 0.95%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 2        | 0.95%   |
| Intel Core i5-4460S CPU @ 2.90GHz              | 2        | 0.95%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 0.95%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 2        | 0.95%   |
| Intel Core i5-10500 CPU @ 3.10GHz              | 2        | 0.95%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 0.95%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 2        | 0.95%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz          | 2        | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 0.95%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx | 2        | 0.95%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 0.95%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 2        | 0.95%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 2        | 0.95%   |
| AMD FX-6300 Six-Core Processor                 | 2        | 0.95%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+     | 2        | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 40       | 19.05%  |
| Intel Core i7           | 35       | 16.67%  |
| Intel Core i3           | 21       | 10%     |
| AMD Ryzen 5             | 21       | 10%     |
| Intel Xeon              | 10       | 4.76%   |
| AMD Ryzen 9             | 10       | 4.76%   |
| Intel Core 2 Quad       | 8        | 3.81%   |
| AMD Ryzen 7             | 5        | 2.38%   |
| AMD FX                  | 5        | 2.38%   |
| AMD Athlon 64 X2        | 5        | 2.38%   |
| Intel Pentium 4         | 4        | 1.9%    |
| Intel Core 2 Duo        | 4        | 1.9%    |
| Intel Celeron           | 4        | 1.9%    |
| AMD Ryzen 3             | 4        | 1.9%    |
| Intel Pentium Dual-Core | 3        | 1.43%   |
| AMD Ryzen Threadripper  | 3        | 1.43%   |
| AMD Phenom II X4        | 3        | 1.43%   |
| AMD Athlon II X4        | 3        | 1.43%   |
| AMD A6                  | 3        | 1.43%   |
| Other                   | 2        | 0.95%   |
| Intel Pentium           | 2        | 0.95%   |
| Intel Atom              | 2        | 0.95%   |
| AMD Ryzen Embedded      | 2        | 0.95%   |
| AMD Phenom II X6        | 2        | 0.95%   |
| AMD A4                  | 2        | 0.95%   |
| Intel Pentium Silver    | 1        | 0.48%   |
| Intel Pentium D         | 1        | 0.48%   |
| AMD Ryzen 5 PRO         | 1        | 0.48%   |
| AMD PRO A10             | 1        | 0.48%   |
| AMD GX                  | 1        | 0.48%   |
| AMD Athlon II X2        | 1        | 0.48%   |
| AMD Athlon Dual Core    | 1        | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 99       | 47.6%   |
| 2       | 39       | 18.75%  |
| 6       | 30       | 14.42%  |
| 12      | 14       | 6.73%   |
| 8       | 9        | 4.33%   |
| 1       | 9        | 4.33%   |
| 3       | 2        | 0.96%   |
| Unknown | 2        | 0.96%   |
| 32      | 1        | 0.48%   |
| 24      | 1        | 0.48%   |
| 16      | 1        | 0.48%   |
| 10      | 1        | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 200      | 97.09%  |
| 2       | 5        | 2.43%   |
| Unknown | 1        | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 119      | 56.67%  |
| 1       | 89       | 42.38%  |
| Unknown | 2        | 0.95%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 202      | 98.06%  |
| Unknown        | 4        | 1.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 70       | 32.26%  |
| 0x306a9    | 18       | 8.29%   |
| 0x206a7    | 16       | 7.37%   |
| 0x306c3    | 15       | 6.91%   |
| 0x1067a    | 10       | 4.61%   |
| 0x08701021 | 7        | 3.23%   |
| 0x08108109 | 5        | 2.3%    |
| 0x0800820d | 5        | 2.3%    |
| 0x206c2    | 4        | 1.84%   |
| 0xf43      | 3        | 1.38%   |
| 0xa0653    | 3        | 1.38%   |
| 0x906ea    | 3        | 1.38%   |
| 0x6fb      | 3        | 1.38%   |
| 0x506e3    | 3        | 1.38%   |
| 0x0810100b | 3        | 1.38%   |
| 0x06000852 | 3        | 1.38%   |
| 0x010000db | 3        | 1.38%   |
| 0x906e9    | 2        | 0.92%   |
| 0x30661    | 2        | 0.92%   |
| 0x106a5    | 2        | 0.92%   |
| 0x0a601203 | 2        | 0.92%   |
| 0x08701013 | 2        | 0.92%   |
| 0x0600611a | 2        | 0.92%   |
| 0x010000c8 | 2        | 0.92%   |
| 0xf47      | 1        | 0.46%   |
| 0xf41      | 1        | 0.46%   |
| 0xa0655    | 1        | 0.46%   |
| 0x906ed    | 1        | 0.46%   |
| 0x906eb    | 1        | 0.46%   |
| 0x906c0    | 1        | 0.46%   |
| 0x706a1    | 1        | 0.46%   |
| 0x6f7      | 1        | 0.46%   |
| 0x406f1    | 1        | 0.46%   |
| 0x306e4    | 1        | 0.46%   |
| 0x30678    | 1        | 0.46%   |
| 0x106e5    | 1        | 0.46%   |
| 0x10677    | 1        | 0.46%   |
| 0x10676    | 1        | 0.46%   |
| 0x0a601206 | 1        | 0.46%   |
| 0x0a20120a | 1        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 28       | 13.53%  |
| SandyBridge   | 23       | 11.11%  |
| Haswell       | 23       | 11.11%  |
| Zen 2         | 17       | 8.21%   |
| Zen+          | 15       | 7.25%   |
| Penryn        | 12       | 5.8%    |
| KabyLake      | 11       | 5.31%   |
| K10           | 9        | 4.35%   |
| Zen           | 7        | 3.38%   |
| Piledriver    | 7        | 3.38%   |
| Westmere      | 6        | 2.9%    |
| K8 Hammer     | 6        | 2.9%    |
| Unknown       | 6        | 2.9%    |
| NetBurst      | 5        | 2.42%   |
| Nehalem       | 5        | 2.42%   |
| Skylake       | 4        | 1.93%   |
| Core          | 4        | 1.93%   |
| CometLake     | 4        | 1.93%   |
| Zen 3         | 3        | 1.45%   |
| Goldmont plus | 2        | 0.97%   |
| Excavator     | 2        | 0.97%   |
| Bonnell       | 2        | 0.97%   |
| Tremont       | 1        | 0.48%   |
| Steamroller   | 1        | 0.48%   |
| Silvermont    | 1        | 0.48%   |
| Jaguar        | 1        | 0.48%   |
| Bulldozer     | 1        | 0.48%   |
| Broadwell     | 1        | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 88       | 38.6%   |
| Nvidia | 76       | 33.33%  |
| Intel  | 64       | 28.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 7.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 4.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 4.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 3.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 3.32%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 8        | 3.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 2.49%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 2.07%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 5        | 2.07%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.66%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.66%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.66%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 1.24%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.24%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.24%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 3        | 1.24%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.24%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.24%   |
| Intel HD Graphics 630                                                       | 3        | 1.24%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.24%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.24%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.83%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.83%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 0.83%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 2        | 0.83%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 2        | 0.83%   |
| AMD Raphael                                                                 | 2        | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 0.83%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 0.83%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 0.83%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 0.83%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 0.83%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 0.83%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.41%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 77       | 35.81%  |
| 1 x Nvidia     | 71       | 33.02%  |
| 1 x Intel      | 50       | 23.26%  |
| 2 x AMD        | 7        | 3.26%   |
| Intel + Nvidia | 3        | 1.4%    |
| Intel + AMD    | 2        | 0.93%   |
| AMD + Nvidia   | 2        | 0.93%   |
| Other          | 1        | 0.47%   |
| 2 x Nvidia     | 1        | 0.47%   |
| 2 x Intel      | 1        | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 162      | 76.06%  |
| Proprietary | 41       | 19.25%  |
| Unknown     | 10       | 4.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 41.55%  |
| 1.01-2.0   | 28       | 12.79%  |
| 0.51-1.0   | 27       | 12.33%  |
| 7.01-8.0   | 23       | 10.5%   |
| 3.01-4.0   | 18       | 8.22%   |
| 0.01-0.5   | 12       | 5.48%   |
| 5.01-6.0   | 11       | 5.02%   |
| 8.01-16.0  | 5        | 2.28%   |
| 2.01-3.0   | 2        | 0.91%   |
| 16.01-24.0 | 2        | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 45       | 20.36%  |
| Samsung Electronics  | 18       | 8.14%   |
| BenQ                 | 18       | 8.14%   |
| Acer                 | 18       | 8.14%   |
| Hewlett-Packard      | 16       | 7.24%   |
| AOC                  | 13       | 5.88%   |
| Philips              | 11       | 4.98%   |
| Iiyama               | 11       | 4.98%   |
| Goldstar             | 9        | 4.07%   |
| Lenovo               | 5        | 2.26%   |
| Sony                 | 4        | 1.81%   |
| Ancor Communications | 4        | 1.81%   |
| Vestel Elektronik    | 3        | 1.36%   |
| HKC                  | 3        | 1.36%   |
| HannStar             | 3        | 1.36%   |
| ASUSTek Computer     | 3        | 1.36%   |
| Apple                | 3        | 1.36%   |
| ___                  | 2        | 0.9%    |
| ViewSonic            | 2        | 0.9%    |
| Unknown              | 2        | 0.9%    |
| Toshiba              | 2        | 0.9%    |
| NEC Computers        | 2        | 0.9%    |
| MSI                  | 2        | 0.9%    |
| MiTAC                | 2        | 0.9%    |
| HannStar Display     | 2        | 0.9%    |
| WIT                  | 1        | 0.45%   |
| UGD                  | 1        | 0.45%   |
| Targa Visionary      | 1        | 0.45%   |
| Targa                | 1        | 0.45%   |
| RTK                  | 1        | 0.45%   |
| Packard Bell         | 1        | 0.45%   |
| OEM                  | 1        | 0.45%   |
| Medion               | 1        | 0.45%   |
| LG Electronics       | 1        | 0.45%   |
| Idek Iiyama          | 1        | 0.45%   |
| HYO                  | 1        | 0.45%   |
| HUAWEI               | 1        | 0.45%   |
| Gigabyte Technology  | 1        | 0.45%   |
| Daewoo               | 1        | 0.45%   |
| CVT                  | 1        | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                 | 5        | 2.04%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch | 4        | 1.63%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch              | 4        | 1.63%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 4        | 1.63%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch | 3        | 1.22%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                     | 3        | 1.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 3        | 1.22%   |
| ___ LCDTV16 ___9000 1360x768                                         | 2        | 0.82%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 2        | 0.82%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 2        | 0.82%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 2        | 0.82%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2        | 0.82%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 2        | 0.82%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch            | 2        | 0.82%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                    | 2        | 0.82%   |
| Dell E171FP DEL300F 1280x1024 338x270mm 17.0-inch                    | 2        | 0.82%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                    | 2        | 0.82%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch              | 2        | 0.82%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch               | 2        | 0.82%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                  | 2        | 0.82%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 2        | 0.82%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 2        | 0.82%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                   | 2        | 0.82%   |
| WIT HDMI WIT0267 1920x1080 531x299mm 24.0-inch                       | 1        | 0.41%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch        | 1        | 0.41%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 1        | 0.41%   |
| UGD Artist13.3pro UGD1302 1920x1080 294x165mm 13.3-inch              | 1        | 0.41%   |
| Toshiba TV TSB1206 1360x768                                          | 1        | 0.41%   |
| Toshiba 55UHD_LCD_TV TSB3700 3840x2160 1872x1053mm 84.6-inch         | 1        | 0.41%   |
| Targa Visionary LCD22-1 Wide TARA229 1680x1050 474x297mm 22.0-inch   | 1        | 0.41%   |
| Targa LCD Monitor LCDTV16 1360x768                                   | 1        | 0.41%   |
| Sony TV SNY4302 1920x1080                                            | 1        | 0.41%   |
| Sony TV *02 SNYC603 1920x1080 1085x610mm 49.0-inch                   | 1        | 0.41%   |
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                   | 1        | 0.41%   |
| Sony SDM-HS95P SNY2600 1280x1024 376x301mm 19.0-inch                 | 1        | 0.41%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch | 1        | 0.41%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch | 1        | 0.41%   |
| Samsung Electronics SMS27A650 SAM082E 1920x1080 598x336mm 27.0-inch  | 1        | 0.41%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 1        | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 104      | 48.37%  |
| 2560x1440 (QHD)    | 23       | 10.7%   |
| 3840x2160 (4K)     | 16       | 7.44%   |
| 1280x1024 (SXGA)   | 15       | 6.98%   |
| 1440x900 (WXGA+)   | 7        | 3.26%   |
| 3440x1440          | 6        | 2.79%   |
| 1366x768 (WXGA)    | 6        | 2.79%   |
| 1360x768           | 6        | 2.79%   |
| Unknown            | 6        | 2.79%   |
| 1920x1200 (WUXGA)  | 5        | 2.33%   |
| 3840x1080          | 4        | 1.86%   |
| 1680x1050 (WSXGA+) | 4        | 1.86%   |
| 1600x900 (HD+)     | 4        | 1.86%   |
| 1024x768 (XGA)     | 2        | 0.93%   |
| 6400x2160          | 1        | 0.47%   |
| 5280x2560          | 1        | 0.47%   |
| 4480x1440          | 1        | 0.47%   |
| 3600x1080          | 1        | 0.47%   |
| 2560x1080          | 1        | 0.47%   |
| 1920x540           | 1        | 0.47%   |
| 1600x1200          | 1        | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 35       | 16.28%  |
| 24      | 35       | 16.28%  |
| 23      | 29       | 13.49%  |
| 21      | 27       | 12.56%  |
| Unknown | 17       | 7.91%   |
| 19      | 13       | 6.05%   |
| 17      | 9        | 4.19%   |
| 34      | 7        | 3.26%   |
| 31      | 6        | 2.79%   |
| 84      | 5        | 2.33%   |
| 18      | 5        | 2.33%   |
| 33      | 4        | 1.86%   |
| 32      | 4        | 1.86%   |
| 72      | 3        | 1.4%    |
| 22      | 3        | 1.4%    |
| 20      | 3        | 1.4%    |
| 49      | 2        | 0.93%   |
| 15      | 2        | 0.93%   |
| 65      | 1        | 0.47%   |
| 46      | 1        | 0.47%   |
| 35      | 1        | 0.47%   |
| 25      | 1        | 0.47%   |
| 13      | 1        | 0.47%   |
| 12      | 1        | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 90       | 42.86%  |
| 401-500     | 46       | 21.9%   |
| Unknown     | 17       | 8.1%    |
| 701-800     | 15       | 7.14%   |
| 601-700     | 10       | 4.76%   |
| 301-350     | 10       | 4.76%   |
| 1501-2000   | 8        | 3.81%   |
| 351-400     | 7        | 3.33%   |
| 1001-1500   | 4        | 1.9%    |
| 201-300     | 2        | 0.95%   |
| 801-900     | 1        | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 134      | 69.07%  |
| 16/10   | 18       | 9.28%   |
| 5/4     | 14       | 7.22%   |
| Unknown | 14       | 7.22%   |
| 21/9    | 7        | 3.61%   |
| 4/3     | 5        | 2.58%   |
| 32/9    | 1        | 0.52%   |
| 3/2     | 1        | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 76       | 35.35%  |
| 301-350        | 35       | 16.28%  |
| 151-200        | 22       | 10.23%  |
| 351-500        | 21       | 9.77%   |
| Unknown        | 17       | 7.91%   |
| 251-300        | 16       | 7.44%   |
| 141-150        | 12       | 5.58%   |
| More than 1000 | 9        | 4.19%   |
| 501-1000       | 3        | 1.4%    |
| 71-80          | 2        | 0.93%   |
| 101-110        | 2        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 122      | 58.94%  |
| 101-120 | 46       | 22.22%  |
| Unknown | 17       | 8.21%   |
| 1-50    | 10       | 4.83%   |
| 121-160 | 7        | 3.38%   |
| 161-240 | 5        | 2.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 159      | 73.27%  |
| 2     | 42       | 19.35%  |
| 0     | 11       | 5.07%   |
| 3     | 5        | 2.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 112      | 34.36%  |
| Intel                             | 104      | 31.9%   |
| Qualcomm Atheros                  | 16       | 4.91%   |
| TP-Link                           | 14       | 4.29%   |
| Ralink Technology                 | 14       | 4.29%   |
| Broadcom                          | 13       | 3.99%   |
| Ralink                            | 8        | 2.45%   |
| Microsoft                         | 6        | 1.84%   |
| MediaTek                          | 6        | 1.84%   |
| Nvidia                            | 4        | 1.23%   |
| Marvell Technology Group          | 4        | 1.23%   |
| Broadcom Limited                  | 3        | 0.92%   |
| Qualcomm Atheros Communications   | 2        | 0.61%   |
| NetGear                           | 2        | 0.61%   |
| Huawei Technologies               | 2        | 0.61%   |
| Belkin Components                 | 2        | 0.61%   |
| Van Ooijen Technische Informatica | 1        | 0.31%   |
| ULi Electronics                   | 1        | 0.31%   |
| Samsung Electronics               | 1        | 0.31%   |
| NetXen Incorporated               | 1        | 0.31%   |
| Microchip Technology              | 1        | 0.31%   |
| JMicron Technology                | 1        | 0.31%   |
| IMC Networks                      | 1        | 0.31%   |
| HMD Global                        | 1        | 0.31%   |
| DisplayLink                       | 1        | 0.31%   |
| Dexcom                            | 1        | 0.31%   |
| ASUSTek Computer                  | 1        | 0.31%   |
| ASIX Electronics                  | 1        | 0.31%   |
| Aquantia                          | 1        | 0.31%   |
| ADMtek                            | 1        | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 87       | 23.84%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23       | 6.3%    |
| Intel Wi-Fi 6 AX200                                                    | 18       | 4.93%   |
| Intel I211 Gigabit Network Connection                                  | 11       | 3.01%   |
| Realtek 802.11ac NIC                                                   | 10       | 2.74%   |
| Ralink MT7601U Wireless Adapter                                        | 9        | 2.47%   |
| Intel Ethernet Connection I217-LM                                      | 8        | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7        | 1.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 7        | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7        | 1.92%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 6        | 1.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 5        | 1.37%   |
| Intel Ethernet Connection (2) I218-V                                   | 5        | 1.37%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 1.1%    |
| Ralink RT2561/RT61 802.11g PCI                                         | 4        | 1.1%    |
| Intel 82579V Gigabit Network Connection                                | 4        | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3        | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 0.82%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 3        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 0.82%   |
| Intel Wireless 7265                                                    | 3        | 0.82%   |
| Intel Ethernet Connection I217-V                                       | 3        | 0.82%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 0.82%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3        | 0.82%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3        | 0.82%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.55%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 0.55%   |
| MediaTek File-CD Gadget                                                | 2        | 0.55%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.55%   |
| Intel Ethernet Controller I225-V                                       | 2        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2        | 0.55%   |
| Intel 82583V Gigabit Network Connection                                | 2        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 37       | 26.81%  |
| Realtek Semiconductor           | 27       | 19.57%  |
| Qualcomm Atheros                | 15       | 10.87%  |
| TP-Link                         | 14       | 10.14%  |
| Ralink Technology               | 14       | 10.14%  |
| Ralink                          | 8        | 5.8%    |
| Microsoft                       | 6        | 4.35%   |
| Broadcom                        | 4        | 2.9%    |
| MediaTek                        | 3        | 2.17%   |
| Qualcomm Atheros Communications | 2        | 1.45%   |
| NetGear                         | 2        | 1.45%   |
| Belkin Components               | 2        | 1.45%   |
| Marvell Technology Group        | 1        | 0.72%   |
| IMC Networks                    | 1        | 0.72%   |
| Broadcom Limited                | 1        | 0.72%   |
| ASUSTek Computer                | 1        | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 18       | 12.77%  |
| Realtek 802.11ac NIC                                                | 10       | 7.09%   |
| Ralink MT7601U Wireless Adapter                                     | 9        | 6.38%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]             | 7        | 4.96%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 6        | 4.26%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 5        | 3.55%   |
| Ralink RT5370 Wireless Adapter                                      | 4        | 2.84%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 4        | 2.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 3        | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 3        | 2.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 3        | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 3        | 2.13%   |
| Intel Wireless 7265                                                 | 3        | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 3        | 2.13%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter        | 3        | 2.13%   |
| TP-Link 802.11ac WLAN Adapter                                       | 2        | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 2        | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2        | 1.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 2        | 1.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2        | 1.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                 | 1        | 0.71%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                               | 1        | 0.71%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                           | 1        | 0.71%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller         | 1        | 0.71%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1        | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 1        | 0.71%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.71%   |
| Ralink Wireless Adapter Canyon CN-WF511                             | 1        | 0.71%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1        | 0.71%   |
| Ralink RT5592 PCIe Wireless Network Adapter                         | 1        | 0.71%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 1        | 0.71%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                           | 1        | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 97       | 45.54%  |
| Intel                    | 83       | 38.97%  |
| Broadcom                 | 10       | 4.69%   |
| Nvidia                   | 4        | 1.88%   |
| Marvell Technology Group | 3        | 1.41%   |
| Qualcomm Atheros         | 2        | 0.94%   |
| MediaTek                 | 2        | 0.94%   |
| Broadcom Limited         | 2        | 0.94%   |
| ULi Electronics          | 1        | 0.47%   |
| Samsung Electronics      | 1        | 0.47%   |
| NetXen Incorporated      | 1        | 0.47%   |
| JMicron Technology       | 1        | 0.47%   |
| Huawei Technologies      | 1        | 0.47%   |
| HMD Global               | 1        | 0.47%   |
| DisplayLink              | 1        | 0.47%   |
| ASIX Electronics         | 1        | 0.47%   |
| Aquantia                 | 1        | 0.47%   |
| ADMtek                   | 1        | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 87       | 39.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 23       | 10.5%   |
| Intel I211 Gigabit Network Connection                                          | 11       | 5.02%   |
| Intel Ethernet Connection I217-LM                                              | 8        | 3.65%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7        | 3.2%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 7        | 3.2%    |
| Intel Ethernet Connection (2) I218-V                                           | 5        | 2.28%   |
| Intel 82579V Gigabit Network Connection                                        | 4        | 1.83%   |
| Intel Ethernet Connection I217-V                                               | 3        | 1.37%   |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 1.37%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 3        | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 0.91%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 0.91%   |
| MediaTek File-CD Gadget                                                        | 2        | 0.91%   |
| Intel I210 Gigabit Network Connection                                          | 2        | 0.91%   |
| Intel Ethernet Controller I225-V                                               | 2        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 0.91%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 0.91%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 2        | 0.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 0.91%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 2        | 0.91%   |
| ULi ULi 1689,1573 integrated ethernet.                                         | 1        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 0.46%   |
| Nvidia MCP55 Ethernet                                                          | 1        | 0.46%   |
| Nvidia MCP51 Ethernet Controller                                               | 1        | 0.46%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter           | 1        | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1        | 0.46%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1        | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.46%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.46%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 203      | 61.7%   |
| WiFi     | 121      | 36.78%  |
| Modem    | 5        | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 160      | 70.48%  |
| WiFi     | 67       | 29.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 124      | 59.05%  |
| 2     | 69       | 32.86%  |
| 3     | 10       | 4.76%   |
| 0     | 5        | 2.38%   |
| 6     | 1        | 0.48%   |
| 4     | 1        | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 186      | 89%     |
| Yes  | 23       | 11%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 39.29%  |
| Cambridge Silicon Radio         | 20       | 23.81%  |
| Broadcom                        | 7        | 8.33%   |
| ASUSTek Computer                | 6        | 7.14%   |
| Realtek Semiconductor           | 4        | 4.76%   |
| Qualcomm Atheros Communications | 3        | 3.57%   |
| TP-Link                         | 2        | 2.38%   |
| IMC Networks                    | 2        | 2.38%   |
| Belkin Components               | 2        | 2.38%   |
| Apple                           | 2        | 2.38%   |
| MediaTek                        | 1        | 1.19%   |
| Dell                            | 1        | 1.19%   |
| Conwise Technology              | 1        | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 23.53%  |
| Intel AX200 Bluetooth                               | 16       | 18.82%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6        | 7.06%   |
| Intel Bluetooth wireless interface                  | 6        | 7.06%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6        | 7.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 3.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3        | 3.53%   |
| TP-Link UB500 Adapter                               | 2        | 2.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 2.35%   |
| Realtek Bluetooth Radio                             | 2        | 2.35%   |
| Intel AX201 Bluetooth                               | 2        | 2.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.18%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.18%   |
| MediaTek Wireless_Device                            | 1        | 1.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.18%   |
| IMC Networks Wireless_Device                        | 1        | 1.18%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.18%   |
| Dell BT Mini-Receiver                               | 1        | 1.18%   |
| Conwise CW6622                                      | 1        | 1.18%   |
| Broadcom BCM92045B3 ROM                             | 1        | 1.18%   |
| Belkin Components F8T012 Bluetooth Adapter          | 1        | 1.18%   |
| Belkin Components Bluetooth Mini Dongle             | 1        | 1.18%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.18%   |
| ASUS Bluetooth Device                               | 1        | 1.18%   |
| ASUS BCM20702A0                                     | 1        | 1.18%   |
| Apple Bluetooth Host Controller                     | 1        | 1.18%   |
| Apple Bluetooth HCI                                 | 1        | 1.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 127      | 34.51%  |
| AMD                                             | 108      | 29.35%  |
| Nvidia                                          | 72       | 19.57%  |
| Creative Labs                                   | 7        | 1.9%    |
| C-Media Electronics                             | 6        | 1.63%   |
| Kingston Technology                             | 5        | 1.36%   |
| Plantronics                                     | 4        | 1.09%   |
| Texas Instruments                               | 3        | 0.82%   |
| Creative Technology                             | 3        | 0.82%   |
| Micronas                                        | 2        | 0.54%   |
| Logitech                                        | 2        | 0.54%   |
| JMTek                                           | 2        | 0.54%   |
| Giga-Byte Technology                            | 2        | 0.54%   |
| Ensoniq                                         | 2        | 0.54%   |
| Dell                                            | 2        | 0.54%   |
| Blue Microphones                                | 2        | 0.54%   |
| ULi Electronics                                 | 1        | 0.27%   |
| Turtle Beach                                    | 1        | 0.27%   |
| Sony                                            | 1        | 0.27%   |
| SAVITECH                                        | 1        | 0.27%   |
| RODE Microphones                                | 1        | 0.27%   |
| Razer USA                                       | 1        | 0.27%   |
| Native Instruments                              | 1        | 0.27%   |
| M-Audio                                         | 1        | 0.27%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.27%   |
| KTMicro                                         | 1        | 0.27%   |
| GN Netcom                                       | 1        | 0.27%   |
| Generalplus Technology                          | 1        | 0.27%   |
| Focusrite-Novation                              | 1        | 0.27%   |
| FiiO Electronics Technology                     | 1        | 0.27%   |
| Corsair                                         | 1        | 0.27%   |
| BEHRINGER International                         | 1        | 0.27%   |
| AudioQuest                                      | 1        | 0.27%   |
| Audio-Technica                                  | 1        | 0.27%   |
| AOKEO                                           | 1        | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 27       | 6.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 22       | 5.06%   |
| AMD Starship/Matisse HD Audio Controller                                          | 20       | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18       | 4.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 17       | 3.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 17       | 3.91%   |
| AMD Family 17h/19h HD Audio Controller                                            | 15       | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 3.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 14       | 3.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 11       | 2.53%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 2.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 2.07%   |
| Nvidia GP106 High Definition Audio Controller                                     | 8        | 1.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 1.84%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 7        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 1.38%   |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.15%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 1.15%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.15%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 5        | 1.15%   |
| AMD Navi 10 HDMI Audio                                                            | 5        | 1.15%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.15%   |
| Nvidia High Definition Audio Controller                                           | 4        | 0.92%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 0.92%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.69%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 0.69%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 0.69%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 0.69%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 3        | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                          | 3        | 0.69%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 3        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 29       | 21.64%  |
| Unknown             | 19       | 14.18%  |
| Crucial             | 16       | 11.94%  |
| SK hynix            | 15       | 11.19%  |
| Kingston            | 14       | 10.45%  |
| Samsung Electronics | 8        | 5.97%   |
| Micron Technology   | 8        | 5.97%   |
| G.Skill             | 8        | 5.97%   |
| Team                | 3        | 2.24%   |
| Ramaxel Technology  | 3        | 2.24%   |
| Patriot             | 2        | 1.49%   |
| A-DATA Technology   | 2        | 1.49%   |
| Toshiba             | 1        | 0.75%   |
| Nanya Technology    | 1        | 0.75%   |
| Infineon            | 1        | 0.75%   |
| Elpida              | 1        | 0.75%   |
| BiNFUL              | 1        | 0.75%   |
| Apacer              | 1        | 0.75%   |
| A Force             | 1        | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 6        | 4%      |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s    | 3        | 2%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s   | 3        | 2%      |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 2        | 1.33%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 1.33%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s              | 2        | 1.33%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 2        | 1.33%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 1.33%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 2        | 1.33%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s     | 2        | 1.33%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s   | 2        | 1.33%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 1.33%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s  | 2        | 1.33%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s   | 2        | 1.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                 | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM 800MT/s                     | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s            | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s            | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                  | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM                          | 1        | 0.67%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 0.67%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 0.67%   |
| Unknown RAM Module 128MB DIMM SDRAM                     | 1        | 0.67%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s    | 1        | 0.67%   |
| Toshiba RAM 99U5702-094.A00G 8GB DIMM DDR4 2400MT/s     | 1        | 0.67%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 0.67%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.67%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1067MT/s           | 1        | 0.67%   |
| SK hynix RAM Module 16GB DIMM DDR3 1866MT/s             | 1        | 0.67%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s     | 1        | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 0.67%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s | 1        | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 45       | 38.79%  |
| DDR4    | 43       | 37.07%  |
| Unknown | 14       | 12.07%  |
| SDRAM   | 6        | 5.17%   |
| DDR2    | 5        | 4.31%   |
| DDR5    | 2        | 1.72%   |
| DDR     | 1        | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 107      | 94.69%  |
| SODIMM | 6        | 5.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 46       | 35.94%  |
| 4096  | 34       | 26.56%  |
| 2048  | 18       | 14.06%  |
| 16384 | 17       | 13.28%  |
| 1024  | 6        | 4.69%   |
| 32768 | 5        | 3.91%   |
| 512   | 1        | 0.78%   |
| 128   | 1        | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 19.7%   |
| 1333    | 15       | 11.36%  |
| 3600    | 9        | 6.82%   |
| 3200    | 9        | 6.82%   |
| 800     | 8        | 6.06%   |
| 2667    | 7        | 5.3%    |
| 2400    | 7        | 5.3%    |
| 667     | 6        | 4.55%   |
| 2133    | 5        | 3.79%   |
| 1867    | 4        | 3.03%   |
| 3800    | 3        | 2.27%   |
| 3533    | 3        | 2.27%   |
| 1866    | 3        | 2.27%   |
| 1800    | 3        | 2.27%   |
| 1066    | 3        | 2.27%   |
| 3400    | 2        | 1.52%   |
| 2666    | 2        | 1.52%   |
| 1648    | 2        | 1.52%   |
| 533     | 2        | 1.52%   |
| Unknown | 2        | 1.52%   |
| 5600    | 1        | 0.76%   |
| 5200    | 1        | 0.76%   |
| 4800    | 1        | 0.76%   |
| 3733    | 1        | 0.76%   |
| 3266    | 1        | 0.76%   |
| 3000    | 1        | 0.76%   |
| 2933    | 1        | 0.76%   |
| 2733    | 1        | 0.76%   |
| 1639    | 1        | 0.76%   |
| 1067    | 1        | 0.76%   |
| 400     | 1        | 0.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 2        | 40%     |
| Samsung Electronics | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Samsung M2070 Series      | 1        | 20%     |
| HP Officejet 4500 G510g-m | 1        | 20%     |
| Canon PIXMA MG3600 Series | 1        | 20%     |
| Canon PIXMA MG2500 Series | 1        | 20%     |
| Brother MFC-L2700DW       | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 19       | 46.34%  |
| Microsoft                              | 4        | 9.76%   |
| Microdia                               | 3        | 7.32%   |
| Sunplus Innovation Technology          | 2        | 4.88%   |
| Generalplus Technology                 | 2        | 4.88%   |
| Creative Technology                    | 2        | 4.88%   |
| WaveRider Communications               | 1        | 2.44%   |
| Samsung Electronics                    | 1        | 2.44%   |
| Realtek Semiconductor                  | 1        | 2.44%   |
| Razer USA                              | 1        | 2.44%   |
| GenesysLogic Technology                | 1        | 2.44%   |
| GEMBIRD                                | 1        | 2.44%   |
| Chicony Electronics                    | 1        | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 2.44%   |
| Apple                                  | 1        | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                            | 8        | 19.05%  |
| Microsoft LifeCam HD-3000                                              | 3        | 7.14%   |
| Logitech Webcam C270                                                   | 3        | 7.14%   |
| Logitech Webcam C925e                                                  | 2        | 4.76%   |
| Creative Live! Cam Sync HD [VF0770]                                    | 2        | 4.76%   |
| WaveRider USB 2.0 Camera                                               | 1        | 2.38%   |
| Sunplus HD 720P webcam                                                 | 1        | 2.38%   |
| Sunplus Full HD webcam                                                 | 1        | 2.38%   |
| Samsung Galaxy series, misc. (MTP mode)                                | 1        | 2.38%   |
| Realtek Full HD webcam                                                 | 1        | 2.38%   |
| Razer USA Gaming Webcam [Kiyo]                                         | 1        | 2.38%   |
| Microsoft LifeCam NX-3000 (UVC-compliant)                              | 1        | 2.38%   |
| Microdia Webcam Vitade AF                                              | 1        | 2.38%   |
| Microdia USB 2.0 Camera                                                | 1        | 2.38%   |
| Microdia CyberTrack H6                                                 | 1        | 2.38%   |
| Logitech Webcam C930e                                                  | 1        | 2.38%   |
| Logitech Webcam C310                                                   | 1        | 2.38%   |
| Logitech Webcam C210                                                   | 1        | 2.38%   |
| Logitech Webcam C120                                                   | 1        | 2.38%   |
| Logitech QuickCam Vision Pro                                           | 1        | 2.38%   |
| Logitech Logitech Webcam C160                                          | 1        | 2.38%   |
| Logitech C922 Pro Stream Webcam                                        | 1        | 2.38%   |
| GenesysLogic USB2.0 UVC PC Camera                                      | 1        | 2.38%   |
| Generalplus GENERAL WEBCAM                                             | 1        | 2.38%   |
| Generalplus 808 Camera                                                 | 1        | 2.38%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                      | 1        | 2.38%   |
| Chicony USB2.0 2MP UVC Camera                                          | 1        | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP 2.0MP High Definition Webcam | 1        | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                     | 1        | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 172      | 80.37%  |
| 1     | 35       | 16.36%  |
| 2     | 5        | 2.34%   |
| 5     | 1        | 0.47%   |
| 4     | 1        | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 25       | 52.08%  |
| Graphics card            | 13       | 27.08%  |
| Multimedia controller    | 3        | 6.25%   |
| Net/ethernet             | 2        | 4.17%   |
| Unassigned class         | 1        | 2.08%   |
| Sound                    | 1        | 2.08%   |
| Firewire controller      | 1        | 2.08%   |
| Communication controller | 1        | 2.08%   |
| Camera                   | 1        | 2.08%   |

