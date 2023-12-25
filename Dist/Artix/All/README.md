Artix - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Artix.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Artix/Desktop/README.md) and [notebooks](/Dist/Artix/Notebook/README.md).

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

Total: 332

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 2B29                        | Desktop     | [93ef9f39bd](https://linux-hardware.org/?probe=93ef9f39bd) | Dec 24, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [498753636e](https://linux-hardware.org/?probe=498753636e) | Dec 22, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [9109738b7f](https://linux-hardware.org/?probe=9109738b7f) | Dec 22, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4017c676bf](https://linux-hardware.org/?probe=4017c676bf) | Dec 22, 2023 |
| Dell          | Latitude E6440              | Notebook    | [cf0bb02399](https://linux-hardware.org/?probe=cf0bb02399) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [82fd570b21](https://linux-hardware.org/?probe=82fd570b21) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b706d26f30](https://linux-hardware.org/?probe=b706d26f30) | Dec 07, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f150b37e9f](https://linux-hardware.org/?probe=f150b37e9f) | Dec 03, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [96ff1ae1f7](https://linux-hardware.org/?probe=96ff1ae1f7) | Nov 28, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [59580145e5](https://linux-hardware.org/?probe=59580145e5) | Nov 22, 2023 |
| Intel         | X99H                        | Desktop     | [056d58d460](https://linux-hardware.org/?probe=056d58d460) | Nov 19, 2023 |
| Intel         | X99H                        | Desktop     | [409013cb66](https://linux-hardware.org/?probe=409013cb66) | Nov 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [4174372199](https://linux-hardware.org/?probe=4174372199) | Nov 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e55e321a2e](https://linux-hardware.org/?probe=e55e321a2e) | Nov 09, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [749f236b5d](https://linux-hardware.org/?probe=749f236b5d) | Nov 09, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [94dac5876f](https://linux-hardware.org/?probe=94dac5876f) | Nov 07, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [77879ace29](https://linux-hardware.org/?probe=77879ace29) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [7814bb818a](https://linux-hardware.org/?probe=7814bb818a) | Oct 23, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | Desktop     | [aaeff9a386](https://linux-hardware.org/?probe=aaeff9a386) | Oct 20, 2023 |
| Biostar       | A320MH                      | Desktop     | [d797fd8fa3](https://linux-hardware.org/?probe=d797fd8fa3) | Oct 15, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [f83f9bba48](https://linux-hardware.org/?probe=f83f9bba48) | Oct 15, 2023 |
| HP            | Grunt                       | Notebook    | [af80cd9bd6](https://linux-hardware.org/?probe=af80cd9bd6) | Oct 13, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [6e2fa2dc88](https://linux-hardware.org/?probe=6e2fa2dc88) | Oct 07, 2023 |
| Dell          | Precision 7560              | Notebook    | [7cffa06ab3](https://linux-hardware.org/?probe=7cffa06ab3) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [58552d0532](https://linux-hardware.org/?probe=58552d0532) | Sep 30, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | Notebook    | [e28cf08ffe](https://linux-hardware.org/?probe=e28cf08ffe) | Sep 24, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [20ba60e073](https://linux-hardware.org/?probe=20ba60e073) | Sep 21, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | Notebook    | [46ee09f5bd](https://linux-hardware.org/?probe=46ee09f5bd) | Sep 21, 2023 |
| Timi          | A30                         | Notebook    | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [7ae653c6c1](https://linux-hardware.org/?probe=7ae653c6c1) | Sep 05, 2023 |
| HP            | 15                          | Notebook    | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [3713bc7b70](https://linux-hardware.org/?probe=3713bc7b70) | Aug 29, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [08efa3dcf3](https://linux-hardware.org/?probe=08efa3dcf3) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | Notebook    | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| Acer          | Aspire S5-371               | Notebook    | [210e2bbe4d](https://linux-hardware.org/?probe=210e2bbe4d) | Aug 16, 2023 |
| Acer          | Aspire S5-371               | Notebook    | [c5b4372bbf](https://linux-hardware.org/?probe=c5b4372bbf) | Aug 16, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [0eb433075b](https://linux-hardware.org/?probe=0eb433075b) | Aug 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5b67a1f9cf](https://linux-hardware.org/?probe=5b67a1f9cf) | Aug 06, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | Desktop     | [29f8d73c0e](https://linux-hardware.org/?probe=29f8d73c0e) | Aug 05, 2023 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [6c542a6490](https://linux-hardware.org/?probe=6c542a6490) | Aug 03, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [3b317edaf6](https://linux-hardware.org/?probe=3b317edaf6) | Jul 25, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | Desktop     | [d1ef825b01](https://linux-hardware.org/?probe=d1ef825b01) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [25f87e7de3](https://linux-hardware.org/?probe=25f87e7de3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T420 4180AG3       | Notebook    | [21fe808c05](https://linux-hardware.org/?probe=21fe808c05) | Jul 02, 2023 |
| ASUSTek       | K53E                        | Notebook    | [8e1f4ee31f](https://linux-hardware.org/?probe=8e1f4ee31f) | Jun 27, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [b9bef208f1](https://linux-hardware.org/?probe=b9bef208f1) | Jun 26, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [7a56496149](https://linux-hardware.org/?probe=7a56496149) | Jun 16, 2023 |
| Dell          | 0DWPVW A00                  | Desktop     | [94a28f2fec](https://linux-hardware.org/?probe=94a28f2fec) | Jun 16, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8649d41483](https://linux-hardware.org/?probe=8649d41483) | Jun 15, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [1c7cc37995](https://linux-hardware.org/?probe=1c7cc37995) | Jun 03, 2023 |
| Notebook      | N141CU                      | Notebook    | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| GPD           | P2 MAX                      | Notebook    | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| ASUSTek       | GL702ZC                     | Notebook    | [c60d7fabbb](https://linux-hardware.org/?probe=c60d7fabbb) | May 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [b5a283de1d](https://linux-hardware.org/?probe=b5a283de1d) | May 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [0a65452634](https://linux-hardware.org/?probe=0a65452634) | May 24, 2023 |
| ASUSTek       | GL702ZC                     | Notebook    | [9764417bf8](https://linux-hardware.org/?probe=9764417bf8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [14985fd04f](https://linux-hardware.org/?probe=14985fd04f) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | Notebook    | [429d4451c9](https://linux-hardware.org/?probe=429d4451c9) | May 16, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [2a50b288f8](https://linux-hardware.org/?probe=2a50b288f8) | May 15, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [cc4f992884](https://linux-hardware.org/?probe=cc4f992884) | May 12, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [ea808c2e80](https://linux-hardware.org/?probe=ea808c2e80) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [382b81c0d1](https://linux-hardware.org/?probe=382b81c0d1) | May 08, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [f115dd1851](https://linux-hardware.org/?probe=f115dd1851) | May 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [a15fa484d4](https://linux-hardware.org/?probe=a15fa484d4) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [18111d76fc](https://linux-hardware.org/?probe=18111d76fc) | Apr 17, 2023 |
| Intel         | X99H                        | Desktop     | [b91cbf41c0](https://linux-hardware.org/?probe=b91cbf41c0) | Apr 06, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [a2ba637448](https://linux-hardware.org/?probe=a2ba637448) | Mar 29, 2023 |
| Dell          | G3 3500                     | Notebook    | [aa79addc8c](https://linux-hardware.org/?probe=aa79addc8c) | Mar 29, 2023 |
| ASRock        | Z690 Taichi                 | Desktop     | [fbad15ab18](https://linux-hardware.org/?probe=fbad15ab18) | Mar 24, 2023 |
| ASRock        | Z690 Taichi                 | Desktop     | [76159d5fc4](https://linux-hardware.org/?probe=76159d5fc4) | Mar 22, 2023 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [47c7f6e38d](https://linux-hardware.org/?probe=47c7f6e38d) | Mar 03, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6c74aa3736](https://linux-hardware.org/?probe=6c74aa3736) | Mar 02, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [245d23aff3](https://linux-hardware.org/?probe=245d23aff3) | Feb 26, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| ONE-NETBOO... | One-Mix3 Pro                | Notebook    | [9869b4dd9c](https://linux-hardware.org/?probe=9869b4dd9c) | Feb 15, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [92cac1a802](https://linux-hardware.org/?probe=92cac1a802) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7ad97f8b6d](https://linux-hardware.org/?probe=7ad97f8b6d) | Feb 09, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | Notebook    | [84411df81a](https://linux-hardware.org/?probe=84411df81a) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [84fb689a7e](https://linux-hardware.org/?probe=84fb689a7e) | Feb 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [405641895c](https://linux-hardware.org/?probe=405641895c) | Jan 18, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [4ac7834c5f](https://linux-hardware.org/?probe=4ac7834c5f) | Jan 16, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [99e632c9a9](https://linux-hardware.org/?probe=99e632c9a9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [3ca2dd056d](https://linux-hardware.org/?probe=3ca2dd056d) | Jan 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [b79de349a9](https://linux-hardware.org/?probe=b79de349a9) | Jan 01, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [815525e6d2](https://linux-hardware.org/?probe=815525e6d2) | Dec 27, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | Notebook    | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [f17f99d4e6](https://linux-hardware.org/?probe=f17f99d4e6) | Nov 30, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [f42473e3f6](https://linux-hardware.org/?probe=f42473e3f6) | Nov 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [85d17374e7](https://linux-hardware.org/?probe=85d17374e7) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| HP            | Pavilion 15                 | Notebook    | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d72c486584](https://linux-hardware.org/?probe=d72c486584) | Oct 22, 2022 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [debce2faa6](https://linux-hardware.org/?probe=debce2faa6) | Oct 20, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| HP            | Pavilion g4                 | Notebook    | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| Notebook      | N141CU                      | Notebook    | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a37633e1e2](https://linux-hardware.org/?probe=a37633e1e2) | Aug 24, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [6b03bfc62e](https://linux-hardware.org/?probe=6b03bfc62e) | Aug 13, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Latitude E7440              | Notebook    | [deea307e9b](https://linux-hardware.org/?probe=deea307e9b) | Jul 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [e2d8510882](https://linux-hardware.org/?probe=e2d8510882) | Jul 27, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [304f750248](https://linux-hardware.org/?probe=304f750248) | Jul 08, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [f07968d013](https://linux-hardware.org/?probe=f07968d013) | Jul 07, 2022 |
| MOTILE        | M141                        | Notebook    | [59c616a04e](https://linux-hardware.org/?probe=59c616a04e) | Jun 30, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [8ddbebd4b1](https://linux-hardware.org/?probe=8ddbebd4b1) | Jun 28, 2022 |
| AXIOO         | Mybook 14E                  | Notebook    | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [a4b535cdee](https://linux-hardware.org/?probe=a4b535cdee) | Jun 15, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [a4054a2ac8](https://linux-hardware.org/?probe=a4054a2ac8) | Jun 10, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [009ea9b40a](https://linux-hardware.org/?probe=009ea9b40a) | Jun 09, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0MV0... | Notebook    | [3c23c9dfc6](https://linux-hardware.org/?probe=3c23c9dfc6) | Jun 08, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Dell          | Precision M6600             | Notebook    | [bb044c066c](https://linux-hardware.org/?probe=bb044c066c) | Jun 05, 2022 |
| Dell          | Latitude 5490               | Notebook    | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [dfacdafc7f](https://linux-hardware.org/?probe=dfacdafc7f) | May 11, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | Notebook    | [9792863fc7](https://linux-hardware.org/?probe=9792863fc7) | May 08, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | Notebook    | [bba77106b4](https://linux-hardware.org/?probe=bba77106b4) | May 08, 2022 |
| HP            | 15                          | Notebook    | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | Notebook    | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 246                         | Notebook    | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Lenovo        | ThinkPad T430 2347H76       | Notebook    | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [313e83e0ef](https://linux-hardware.org/?probe=313e83e0ef) | Mar 10, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [604362a51f](https://linux-hardware.org/?probe=604362a51f) | Feb 18, 2022 |
| Notebook      | N141CU                      | Notebook    | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| Acer          | Aspire V3-472PG             | Notebook    | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [6cf7935dcc](https://linux-hardware.org/?probe=6cf7935dcc) | Feb 14, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [e02c6336d6](https://linux-hardware.org/?probe=e02c6336d6) | Feb 03, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [b16ba2b14a](https://linux-hardware.org/?probe=b16ba2b14a) | Jan 31, 2022 |
| ASRock        | B150M Pro4S/D3              | Desktop     | [b7a65f897c](https://linux-hardware.org/?probe=b7a65f897c) | Jan 29, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [6a49ff6317](https://linux-hardware.org/?probe=6a49ff6317) | Jan 18, 2022 |
| Lenovo        | G400s 20244                 | Notebook    | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [29b6159e9c](https://linux-hardware.org/?probe=29b6159e9c) | Jan 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ca93455055](https://linux-hardware.org/?probe=ca93455055) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1a7ef57da7](https://linux-hardware.org/?probe=1a7ef57da7) | Jan 07, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bef1d4552a](https://linux-hardware.org/?probe=bef1d4552a) | Jan 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell          | Latitude E6440              | Notebook    | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell          | Latitude E6440              | Notebook    | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [44ccc8eb49](https://linux-hardware.org/?probe=44ccc8eb49) | Nov 24, 2021 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9fca12db52](https://linux-hardware.org/?probe=9fca12db52) | Nov 22, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | Notebook    | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | Notebook    | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [65a49b7280](https://linux-hardware.org/?probe=65a49b7280) | Oct 30, 2021 |
| HP            | 1495                        | Desktop     | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e2c619e8dd](https://linux-hardware.org/?probe=e2c619e8dd) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [1e612081c8](https://linux-hardware.org/?probe=1e612081c8) | Oct 02, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell          | Precision M6600             | Notebook    | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d5871d0e2a](https://linux-hardware.org/?probe=d5871d0e2a) | Aug 25, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ec331e992a](https://linux-hardware.org/?probe=ec331e992a) | Aug 08, 2021 |
| GPD           | P2 MAX                      | Notebook    | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [558e1369e9](https://linux-hardware.org/?probe=558e1369e9) | Jul 25, 2021 |
| GPD           | P2 MAX                      | Notebook    | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP            | 250 G3                      | Notebook    | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [156577ba27](https://linux-hardware.org/?probe=156577ba27) | Jul 18, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo        | LaVie Z 20FF0012US          | Notebook    | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f8e9ea8ffa](https://linux-hardware.org/?probe=f8e9ea8ffa) | Jun 26, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| MSI           | Z270M MORTAR                | Desktop     | [5c54607559](https://linux-hardware.org/?probe=5c54607559) | Jun 22, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell          | Precision 7550              | Notebook    | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell          | Precision 7550              | Notebook    | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [cc7cb4a34e](https://linux-hardware.org/?probe=cc7cb4a34e) | May 22, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3f10e6610b](https://linux-hardware.org/?probe=3f10e6610b) | May 18, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| HP            | Laptop 17z-ca300            | Notebook    | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d1cf148ec4](https://linux-hardware.org/?probe=d1cf148ec4) | Apr 24, 2021 |
| Acer          | Aspire V3-572PG             | Notebook    | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [dbd940a4f3](https://linux-hardware.org/?probe=dbd940a4f3) | Mar 29, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI           | GP72 7RDX                   | Notebook    | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta        | SWH                         | Notebook    | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ce4b5362ed](https://linux-hardware.org/?probe=ce4b5362ed) | Mar 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Precision 7550              | Notebook    | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [91a16f1c67](https://linux-hardware.org/?probe=91a16f1c67) | Feb 21, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [f93e302542](https://linux-hardware.org/?probe=f93e302542) | Feb 15, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Alienware     | 02XRCM A01                  | Desktop     | [554d3ebf2f](https://linux-hardware.org/?probe=554d3ebf2f) | Feb 14, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b4c4d7f99c](https://linux-hardware.org/?probe=b4c4d7f99c) | Feb 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [70eabb568f](https://linux-hardware.org/?probe=70eabb568f) | Jan 30, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [fb3e2ec12b](https://linux-hardware.org/?probe=fb3e2ec12b) | Jan 24, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fda5fabbf5](https://linux-hardware.org/?probe=fda5fabbf5) | Jan 21, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell          | 0K216C                      | Desktop     | [524206eff9](https://linux-hardware.org/?probe=524206eff9) | Jan 20, 2021 |
| Dell          | 0D9JG3 A00                  | Desktop     | [6c44448201](https://linux-hardware.org/?probe=6c44448201) | Jan 19, 2021 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [c53595bd26](https://linux-hardware.org/?probe=c53595bd26) | Jan 16, 2021 |
| Dell          | Precision 5520              | Notebook    | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [335ee823bd](https://linux-hardware.org/?probe=335ee823bd) | Jan 16, 2021 |
| ASUSTek       | E402NA                      | Notebook    | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| ASUSTek       | G11CD                       | Desktop     | [145a13d355](https://linux-hardware.org/?probe=145a13d355) | Jan 07, 2021 |
| ASUSTek       | G11CD                       | Desktop     | [dc70a6fae2](https://linux-hardware.org/?probe=dc70a6fae2) | Jan 07, 2021 |
| HP            | 2B34                        | Desktop     | [e48dc00e0a](https://linux-hardware.org/?probe=e48dc00e0a) | Jan 04, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [6dbd029143](https://linux-hardware.org/?probe=6dbd029143) | Jan 03, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [7dd04be8aa](https://linux-hardware.org/?probe=7dd04be8aa) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3f9f87f288](https://linux-hardware.org/?probe=3f9f87f288) | Dec 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2acc15f485](https://linux-hardware.org/?probe=2acc15f485) | Dec 27, 2020 |
| Dell          | Latitude E6530              | Notebook    | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD           | P2 MAX                      | Notebook    | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [cefff6c6c3](https://linux-hardware.org/?probe=cefff6c6c3) | Dec 05, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [cbcb59eb96](https://linux-hardware.org/?probe=cbcb59eb96) | Dec 03, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [28b680c91d](https://linux-hardware.org/?probe=28b680c91d) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer          | Aspire A315-53              | Notebook    | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [42a67a5d5e](https://linux-hardware.org/?probe=42a67a5d5e) | Nov 18, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [848672f794](https://linux-hardware.org/?probe=848672f794) | Oct 13, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [1193653309](https://linux-hardware.org/?probe=1193653309) | Oct 04, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Dell          | Precision 7550              | Notebook    | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [b062c35766](https://linux-hardware.org/?probe=b062c35766) | Sep 16, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [962d52b690](https://linux-hardware.org/?probe=962d52b690) | Sep 14, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [a663586db5](https://linux-hardware.org/?probe=a663586db5) | Sep 14, 2020 |
| Dell          | Precision 7550              | Notebook    | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [86215bb4fb](https://linux-hardware.org/?probe=86215bb4fb) | Aug 29, 2020 |
| Dell          | Precision 7550              | Notebook    | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e988296384](https://linux-hardware.org/?probe=e988296384) | Aug 19, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [d86cfc12cc](https://linux-hardware.org/?probe=d86cfc12cc) | Aug 19, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [937f502004](https://linux-hardware.org/?probe=937f502004) | Aug 18, 2020 |
| Acer          | Nitro AN515-51              | Notebook    | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [5d992bbc09](https://linux-hardware.org/?probe=5d992bbc09) | Aug 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ff7915ae78](https://linux-hardware.org/?probe=ff7915ae78) | Aug 07, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | Notebook    | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a57e5d7e84](https://linux-hardware.org/?probe=a57e5d7e84) | Jul 08, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook      | N130BU                      | Notebook    | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9623b5be2b](https://linux-hardware.org/?probe=9623b5be2b) | Jun 16, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4125763b79](https://linux-hardware.org/?probe=4125763b79) | Jun 12, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [82af1cec2f](https://linux-hardware.org/?probe=82af1cec2f) | May 30, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [40adc1a5f5](https://linux-hardware.org/?probe=40adc1a5f5) | Apr 03, 2020 |
| Dell          | Precision 3540              | Notebook    | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell          | Precision 3540              | Notebook    | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Biostar       | G31D-M7                     | Desktop     | [9f6a5c0f39](https://linux-hardware.org/?probe=9f6a5c0f39) | Oct 25, 2018 |
| Lenovo        | B590 20206                  | Notebook    | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 140       | 58.58%  |
| Artix          | 83        | 34.73%  |
| Artix 20220123 | 3         | 1.26%   |
| Artix 20230710 | 2         | 0.84%   |
| Artix 20220713 | 2         | 0.84%   |
| Artix 20210726 | 2         | 0.84%   |
| Artix 20230814 | 1         | 0.42%   |
| Artix 20230501 | 1         | 0.42%   |
| Artix 20230320 | 1         | 0.42%   |
| Artix 20230306 | 1         | 0.42%   |
| Artix 20230215 | 1         | 0.42%   |
| Artix 20201207 | 1         | 0.42%   |
| Artix 20201128 | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 230       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.14-artix1-1   | 8         | 2.99%   |
| 6.5.7-artix1-1    | 6         | 2.24%   |
| 5.7.6-artix1-1    | 5         | 1.87%   |
| 6.5.5-artix1-1    | 4         | 1.49%   |
| 6.4.10-artix1-1   | 4         | 1.49%   |
| 6.3.2-artix1-1    | 4         | 1.49%   |
| 6.1.8-artix1-1    | 4         | 1.49%   |
| 6.0.7-artix1-1    | 4         | 1.49%   |
| 5.7.12-artix1-1   | 4         | 1.49%   |
| 5.15.12-artix1-1  | 4         | 1.49%   |
| 5.12.12-artix1-1  | 4         | 1.49%   |
| 5.10.4-artix2-1   | 4         | 1.49%   |
| 6.6.4-artix1-1    | 3         | 1.12%   |
| 6.2.13-artix1-1   | 3         | 1.12%   |
| 5.8.8-artix1-1    | 3         | 1.12%   |
| 5.8.12-artix1-1   | 3         | 1.12%   |
| 5.18.16-artix1-1  | 3         | 1.12%   |
| 5.16.3-artix1-1   | 3         | 1.12%   |
| 5.16.10-artix1-1  | 3         | 1.12%   |
| 5.12.8-artix1-1   | 3         | 1.12%   |
| 5.12.14-artix1-1  | 3         | 1.12%   |
| 5.10.8-artix1-1   | 3         | 1.12%   |
| 5.10.6-artix1-1   | 3         | 1.12%   |
| 5.10.16-artix1-1  | 3         | 1.12%   |
| 6.5.2-artix1-1    | 2         | 0.75%   |
| 6.3.6-artix1-1    | 2         | 0.75%   |
| 6.3.3-artix1-1    | 2         | 0.75%   |
| 6.3.1-artix1-1    | 2         | 0.75%   |
| 6.2.6-artix1-1    | 2         | 0.75%   |
| 6.1.6-artix1-1    | 2         | 0.75%   |
| 6.1.32-1-lts      | 2         | 0.75%   |
| 6.1.12-artix1-1   | 2         | 0.75%   |
| 6.1.10-zen1-1-zen | 2         | 0.75%   |
| 6.0.12-artix1-1   | 2         | 0.75%   |
| 5.9.14-zen1-1-zen | 2         | 0.75%   |
| 5.9.12-artix1-1   | 2         | 0.75%   |
| 5.8.14-artix1-1   | 2         | 0.75%   |
| 5.7.2-artix1-1    | 2         | 0.75%   |
| 5.19.12-artix1-1  | 2         | 0.75%   |
| 5.18.9-zen1-1-zen | 2         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 3.73%   |
| 6.5.7   | 6         | 2.24%   |
| 5.12.12 | 6         | 2.24%   |
| 6.5.5   | 5         | 1.87%   |
| 6.3.2   | 5         | 1.87%   |
| 6.0.7   | 5         | 1.87%   |
| 5.7.6   | 5         | 1.87%   |
| 5.15.12 | 5         | 1.87%   |
| 6.4.10  | 4         | 1.49%   |
| 6.1.8   | 4         | 1.49%   |
| 6.1.10  | 4         | 1.49%   |
| 5.7.12  | 4         | 1.49%   |
| 5.12.8  | 4         | 1.49%   |
| 5.12.14 | 4         | 1.49%   |
| 5.10.4  | 4         | 1.49%   |
| 6.6.4   | 3         | 1.12%   |
| 6.5.2   | 3         | 1.12%   |
| 6.3.1   | 3         | 1.12%   |
| 6.2.13  | 3         | 1.12%   |
| 5.8.8   | 3         | 1.12%   |
| 5.8.14  | 3         | 1.12%   |
| 5.8.12  | 3         | 1.12%   |
| 5.18.16 | 3         | 1.12%   |
| 5.17.1  | 3         | 1.12%   |
| 5.16.3  | 3         | 1.12%   |
| 5.16.10 | 3         | 1.12%   |
| 5.13.8  | 3         | 1.12%   |
| 5.11.16 | 3         | 1.12%   |
| 5.10.8  | 3         | 1.12%   |
| 5.10.6  | 3         | 1.12%   |
| 5.10.16 | 3         | 1.12%   |
| 5.10.15 | 3         | 1.12%   |
| 6.4.4   | 2         | 0.75%   |
| 6.3.6   | 2         | 0.75%   |
| 6.3.3   | 2         | 0.75%   |
| 6.2.6   | 2         | 0.75%   |
| 6.1.6   | 2         | 0.75%   |
| 6.1.32  | 2         | 0.75%   |
| 6.1.12  | 2         | 0.75%   |
| 6.0.12  | 2         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 8.14%   |
| 6.1     | 20        | 7.75%   |
| 5.15    | 20        | 7.75%   |
| 5.12    | 19        | 7.36%   |
| 5.9     | 17        | 6.59%   |
| 5.18    | 15        | 5.81%   |
| 6.5     | 14        | 5.43%   |
| 6.3     | 14        | 5.43%   |
| 5.16    | 13        | 5.04%   |
| 5.11    | 13        | 5.04%   |
| 6.4     | 11        | 4.26%   |
| 5.8     | 11        | 4.26%   |
| 5.17    | 11        | 4.26%   |
| 6.0     | 10        | 3.88%   |
| 5.7     | 10        | 3.88%   |
| 6.2     | 7         | 2.71%   |
| 5.14    | 7         | 2.71%   |
| 6.6     | 6         | 2.33%   |
| 5.19    | 6         | 2.33%   |
| 5.13    | 6         | 2.33%   |
| 5.4     | 2         | 0.78%   |
| 4.19    | 2         | 0.78%   |
| 6.0.5   | 1         | 0.39%   |
| 5.6     | 1         | 0.39%   |
| 5.5     | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 230       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 67        | 27.57%  |
| XFCE           | 38        | 15.64%  |
| Unknown        | 33        | 13.58%  |
| GNOME          | 29        | 11.93%  |
| X-Cinnamon     | 14        | 5.76%   |
| MATE           | 14        | 5.76%   |
| i3             | 8         | 3.29%   |
| LXQt           | 7         | 2.88%   |
| Cinnamon       | 6         | 2.47%   |
| LXDE           | 5         | 2.06%   |
| bspwm          | 5         | 2.06%   |
| sway           | 4         | 1.65%   |
| KDE            | 4         | 1.65%   |
| xmonad         | 1         | 0.41%   |
| xinitrc        | 1         | 0.41%   |
| sway-dbus      | 1         | 0.41%   |
| openbox        | 1         | 0.41%   |
| nxde           | 1         | 0.41%   |
| Hyprland       | 1         | 0.41%   |
| DWM            | 1         | 0.41%   |
| awesomeminimal | 1         | 0.41%   |
| awesome        | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 168       | 71.19%  |
| Tty     | 29        | 12.29%  |
| Wayland | 24        | 10.17%  |
| Unknown | 15        | 6.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 95        | 39.92%  |
| LightDM | 67        | 28.15%  |
| SDDM    | 63        | 26.47%  |
| GDM     | 4         | 1.68%   |
| XDM     | 3         | 1.26%   |
| SLiM    | 2         | 0.84%   |
| Ly      | 2         | 0.84%   |
| LXDM    | 2         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 105       | 44.49%  |
| Unknown | 27        | 11.44%  |
| ru_RU   | 17        | 7.2%    |
| C       | 14        | 5.93%   |
| en_GB   | 10        | 4.24%   |
| fr_FR   | 9         | 3.81%   |
| de_DE   | 8         | 3.39%   |
| pt_BR   | 4         | 1.69%   |
| es_ES   | 4         | 1.69%   |
| pt_PT   | 3         | 1.27%   |
| pl_PL   | 3         | 1.27%   |
| it_IT   | 3         | 1.27%   |
| en_AU   | 3         | 1.27%   |
| tr_TR   | 2         | 0.85%   |
| es_MX   | 2         | 0.85%   |
| en_CA   | 2         | 0.85%   |
| en_AG   | 2         | 0.85%   |
| el_GR   | 2         | 0.85%   |
| vi_VN   | 1         | 0.42%   |
| uk_UA   | 1         | 0.42%   |
| ro_RO   | 1         | 0.42%   |
| lt_LT   | 1         | 0.42%   |
| ja_JP   | 1         | 0.42%   |
| fi_FI   | 1         | 0.42%   |
| es_GT   | 1         | 0.42%   |
| es_CO   | 1         | 0.42%   |
| es_AR   | 1         | 0.42%   |
| en_NZ   | 1         | 0.42%   |
| en_IN   | 1         | 0.42%   |
| en_IE   | 1         | 0.42%   |
| de_CH   | 1         | 0.42%   |
| de_AT   | 1         | 0.42%   |
| cs_CZ   | 1         | 0.42%   |
| bg_BG   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 156       | 67.24%  |
| BIOS | 76        | 32.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 71.98%  |
| Btrfs   | 49        | 21.12%  |
| Xfs     | 7         | 3.02%   |
| F2fs    | 5         | 2.16%   |
| Overlay | 2         | 0.86%   |
| Tmpfs   | 1         | 0.43%   |
| Jfs     | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 163       | 69.96%  |
| Unknown | 45        | 19.31%  |
| MBR     | 25        | 10.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 79.83%  |
| Yes       | 47        | 20.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 74.46%  |
| Yes       | 59        | 25.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 41        | 17.83%  |
| ASUSTek Computer       | 37        | 16.09%  |
| Hewlett-Packard        | 28        | 12.17%  |
| Dell                   | 24        | 10.43%  |
| MSI                    | 20        | 8.7%    |
| Gigabyte Technology    | 20        | 8.7%    |
| Acer                   | 16        | 6.96%   |
| ASRock                 | 9         | 3.91%   |
| Intel                  | 4         | 1.74%   |
| Apple                  | 4         | 1.74%   |
| Timi                   | 3         | 1.3%    |
| Samsung Electronics    | 3         | 1.3%    |
| HUAWEI                 | 3         | 1.3%    |
| Notebook               | 2         | 0.87%   |
| GPD                    | 2         | 0.87%   |
| Biostar                | 2         | 0.87%   |
| UNOWHY                 | 1         | 0.43%   |
| Toshiba                | 1         | 0.43%   |
| Quanta                 | 1         | 0.43%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.43%   |
| MOTILE                 | 1         | 0.43%   |
| Microsoft              | 1         | 0.43%   |
| MACHINIST              | 1         | 0.43%   |
| LG Electronics         | 1         | 0.43%   |
| HONOR                  | 1         | 0.43%   |
| Fujitsu                | 1         | 0.43%   |
| AXIOO                  | 1         | 0.43%   |
| Alienware              | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| MSI MS-7A38                                           | 3         | 1.3%    |
| HP 15                                                 | 3         | 1.3%    |
| Timi RedmiBook 14 II                                  | 2         | 0.87%   |
| MSI MS-7C37                                           | 2         | 0.87%   |
| MSI MS-7C02                                           | 2         | 0.87%   |
| Lenovo IdeaPad 5 15IIL05 81YK                         | 2         | 0.87%   |
| Intel X99                                             | 2         | 0.87%   |
| HP Laptop 15s-eq2xxx                                  | 2         | 0.87%   |
| GPD P2 MAX                                            | 2         | 0.87%   |
| Gigabyte 970A-DS3P                                    | 2         | 0.87%   |
| Dell Precision M6600                                  | 2         | 0.87%   |
| Dell Precision 7550                                   | 2         | 0.87%   |
| Dell Latitude E6440                                   | 2         | 0.87%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA               | 2         | 0.87%   |
| Apple MacBookAir7,2                                   | 2         | 0.87%   |
| Acer Nitro AN515-52                                   | 2         | 0.87%   |
| UNOWHY Y13G010S4EI                                    | 1         | 0.43%   |
| Toshiba Satellite P775                                | 1         | 0.43%   |
| Timi A30                                              | 1         | 0.43%   |
| Samsung R425D/R525D                                   | 1         | 0.43%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.43%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.43%   |
| Quanta SWH                                            | 1         | 0.43%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro                   | 1         | 0.43%   |
| Notebook N141CU                                       | 1         | 0.43%   |
| Notebook N130BU                                       | 1         | 0.43%   |
| MSI MS-7E07                                           | 1         | 0.43%   |
| MSI MS-7C89                                           | 1         | 0.43%   |
| MSI MS-7C56                                           | 1         | 0.43%   |
| MSI MS-7B79                                           | 1         | 0.43%   |
| MSI MS-7B09                                           | 1         | 0.43%   |
| MSI MS-7A69                                           | 1         | 0.43%   |
| MSI MS-7A15                                           | 1         | 0.43%   |
| MSI MS-7982                                           | 1         | 0.43%   |
| MSI MS-7850                                           | 1         | 0.43%   |
| MSI MS-7693                                           | 1         | 0.43%   |
| MSI Modern 15 A11M                                    | 1         | 0.43%   |
| MSI GP72 7RDX                                         | 1         | 0.43%   |
| MSI GF65 Thin 10SDR                                   | 1         | 0.43%   |
| MOTILE M141                                           | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 20        | 8.7%    |
| Lenovo IdeaPad                  | 11        | 4.78%   |
| Acer Aspire                     | 11        | 4.78%   |
| Dell Inspiron                   | 8         | 3.48%   |
| HP Laptop                       | 7         | 3.04%   |
| Dell Precision                  | 7         | 3.04%   |
| Dell Latitude                   | 6         | 2.61%   |
| ASUS VivoBook                   | 5         | 2.17%   |
| ASUS ROG                        | 5         | 2.17%   |
| MSI MS-7A38                     | 3         | 1.3%    |
| HP 250                          | 3         | 1.3%    |
| HP 15                           | 3         | 1.3%    |
| Gigabyte X570                   | 3         | 1.3%    |
| ASUS TUF                        | 3         | 1.3%    |
| ASUS PRIME                      | 3         | 1.3%    |
| ASUS ASUS                       | 3         | 1.3%    |
| Acer Nitro                      | 3         | 1.3%    |
| Timi RedmiBook                  | 2         | 0.87%   |
| MSI MS-7C37                     | 2         | 0.87%   |
| MSI MS-7C02                     | 2         | 0.87%   |
| Lenovo IdeaPadFlex              | 2         | 0.87%   |
| Intel X99                       | 2         | 0.87%   |
| HP ProBook                      | 2         | 0.87%   |
| HP Pavilion                     | 2         | 0.87%   |
| HP 255                          | 2         | 0.87%   |
| GPD P2                          | 2         | 0.87%   |
| Gigabyte 970A-DS3P              | 2         | 0.87%   |
| Dell OptiPlex                   | 2         | 0.87%   |
| ASRock B450                     | 2         | 0.87%   |
| Apple MacBookAir7               | 2         | 0.87%   |
| UNOWHY Y13G010S4EI              | 1         | 0.43%   |
| Toshiba Satellite               | 1         | 0.43%   |
| Timi A30                        | 1         | 0.43%   |
| Samsung R425D                   | 1         | 0.43%   |
| Samsung 350V5C                  | 1         | 0.43%   |
| Samsung 300E5EV                 | 1         | 0.43%   |
| Quanta SWH                      | 1         | 0.43%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.43%   |
| Notebook N141CU                 | 1         | 0.43%   |
| Notebook N130BU                 | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 44        | 19.13%  |
| 2019 | 28        | 12.17%  |
| 2018 | 25        | 10.87%  |
| 2017 | 17        | 7.39%   |
| 2013 | 17        | 7.39%   |
| 2012 | 17        | 7.39%   |
| 2021 | 15        | 6.52%   |
| 2011 | 15        | 6.52%   |
| 2014 | 12        | 5.22%   |
| 2015 | 11        | 4.78%   |
| 2022 | 10        | 4.35%   |
| 2016 | 8         | 3.48%   |
| 2010 | 5         | 2.17%   |
| 2007 | 3         | 1.3%    |
| 2008 | 2         | 0.87%   |
| 2009 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 150       | 65.22%  |
| Desktop     | 76        | 33.04%  |
| Convertible | 2         | 0.87%   |
| Tablet      | 1         | 0.43%   |
| Mini pc     | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 228       | 99.13%  |
| Enabled  | 2         | 0.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 228       | 99.13%  |
| Yes  | 2         | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 58        | 25%     |
| 8.01-16.0   | 54        | 23.28%  |
| 4.01-8.0    | 51        | 21.98%  |
| 3.01-4.0    | 28        | 12.07%  |
| 32.01-64.0  | 20        | 8.62%   |
| 64.01-256.0 | 11        | 4.74%   |
| 1.01-2.0    | 6         | 2.59%   |
| 24.01-32.0  | 4         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 62        | 24.31%  |
| 4.01-8.0   | 60        | 23.53%  |
| 1.01-2.0   | 56        | 21.96%  |
| 3.01-4.0   | 39        | 15.29%  |
| 0.51-1.0   | 19        | 7.45%   |
| 8.01-16.0  | 12        | 4.71%   |
| 0.01-0.5   | 4         | 1.57%   |
| 16.01-24.0 | 3         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 137       | 58.55%  |
| 2      | 59        | 25.21%  |
| 3      | 25        | 10.68%  |
| 4      | 6         | 2.56%   |
| 6      | 4         | 1.71%   |
| 8      | 2         | 0.85%   |
| 7      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 75.22%  |
| Yes       | 57        | 24.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 82.17%  |
| No        | 41        | 17.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 82.17%  |
| No        | 41        | 17.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 68.53%  |
| No        | 73        | 31.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 43        | 18.53%  |
| Russia          | 26        | 11.21%  |
| Germany         | 19        | 8.19%   |
| France          | 12        | 5.17%   |
| Brazil          | 12        | 5.17%   |
| India           | 8         | 3.45%   |
| UK              | 7         | 3.02%   |
| Turkey          | 7         | 3.02%   |
| Poland          | 7         | 3.02%   |
| Switzerland     | 6         | 2.59%   |
| Italy           | 6         | 2.59%   |
| Canada          | 6         | 2.59%   |
| Spain           | 5         | 2.16%   |
| Bulgaria        | 5         | 2.16%   |
| Ukraine         | 4         | 1.72%   |
| Romania         | 4         | 1.72%   |
| Netherlands     | 4         | 1.72%   |
| Indonesia       | 4         | 1.72%   |
| Greece          | 4         | 1.72%   |
| Finland         | 3         | 1.29%   |
| Australia       | 3         | 1.29%   |
| Argentina       | 3         | 1.29%   |
| Portugal        | 2         | 0.86%   |
| Pakistan        | 2         | 0.86%   |
| Lithuania       | 2         | 0.86%   |
| Japan           | 2         | 0.86%   |
| Iran            | 2         | 0.86%   |
| Guatemala       | 2         | 0.86%   |
| Czechia         | 2         | 0.86%   |
| Bangladesh      | 2         | 0.86%   |
| Vietnam         | 1         | 0.43%   |
| Uzbekistan      | 1         | 0.43%   |
| Sweden          | 1         | 0.43%   |
| Slovenia        | 1         | 0.43%   |
| Slovakia        | 1         | 0.43%   |
| Peru            | 1         | 0.43%   |
| North Macedonia | 1         | 0.43%   |
| Mexico          | 1         | 0.43%   |
| Israel          | 1         | 0.43%   |
| Hong Kong       | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 6         | 2.48%   |
| St Petersburg     | 5         | 2.07%   |
| Moscow            | 4         | 1.65%   |
| Frankfurt am Main | 4         | 1.65%   |
| Sofia             | 3         | 1.24%   |
| Los Angeles       | 3         | 1.24%   |
| Jakarta           | 3         | 1.24%   |
| Dnipro            | 3         | 1.24%   |
| Charlotte         | 3         | 1.24%   |
| Ankara            | 3         | 1.24%   |
| Warsaw            | 2         | 0.83%   |
| Vilnius           | 2         | 0.83%   |
| Vancouver         | 2         | 0.83%   |
| Toronto           | 2         | 0.83%   |
| Sorocaba          | 2         | 0.83%   |
| Snohomish         | 2         | 0.83%   |
| San Ramon         | 2         | 0.83%   |
| Samara            | 2         | 0.83%   |
| Rio de Janeiro    | 2         | 0.83%   |
| Prague            | 2         | 0.83%   |
| Omaha             | 2         | 0.83%   |
| Neuchatel         | 2         | 0.83%   |
| Mira              | 2         | 0.83%   |
| Milton            | 2         | 0.83%   |
| Kłodzko          | 2         | 0.83%   |
| Iasi              | 2         | 0.83%   |
| Helsinki          | 2         | 0.83%   |
| Guatemala City    | 2         | 0.83%   |
| Brisbane          | 2         | 0.83%   |
| Bern              | 2         | 0.83%   |
| Athens            | 2         | 0.83%   |
| Amsterdam         | 2         | 0.83%   |
| Zurich            | 1         | 0.41%   |
| Zaporizhzhya      | 1         | 0.41%   |
| Zagreb            | 1         | 0.41%   |
| Woodbridge        | 1         | 0.41%   |
| Wigan             | 1         | 0.41%   |
| Wettringen        | 1         | 0.41%   |
| Wem               | 1         | 0.41%   |
| Vladivostok       | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 59        | 79     | 16.3%   |
| WDC                       | 47        | 75     | 12.98%  |
| Seagate                   | 44        | 53     | 12.15%  |
| Toshiba                   | 24        | 25     | 6.63%   |
| Kingston                  | 23        | 25     | 6.35%   |
| Crucial                   | 20        | 28     | 5.52%   |
| SanDisk                   | 18        | 21     | 4.97%   |
| Intel                     | 12        | 17     | 3.31%   |
| HGST                      | 10        | 11     | 2.76%   |
| SK hynix                  | 9         | 15     | 2.49%   |
| Phison Electronics        | 8         | 14     | 2.21%   |
| Hitachi                   | 8         | 9      | 2.21%   |
| Unknown                   | 6         | 6      | 1.66%   |
| China                     | 6         | 7      | 1.66%   |
| A-DATA Technology         | 5         | 5      | 1.38%   |
| Micron Technology         | 4         | 4      | 1.1%    |
| JMicron Technology        | 3         | 3      | 0.83%   |
| Apple                     | 3         | 4      | 0.83%   |
| WALRAM                    | 2         | 2      | 0.55%   |
| SPCC                      | 2         | 2      | 0.55%   |
| Solid State Storage       | 2         | 2      | 0.55%   |
| Silicon Motion            | 2         | 2      | 0.55%   |
| PNY                       | 2         | 2      | 0.55%   |
| Phison                    | 2         | 2      | 0.55%   |
| Micron/Crucial Technology | 2         | 2      | 0.55%   |
| Maxtor                    | 2         | 2      | 0.55%   |
| LITEON                    | 2         | 2      | 0.55%   |
| Linux                     | 2         | 2      | 0.55%   |
| Hewlett-Packard           | 2         | 2      | 0.55%   |
| Corsair                   | 2         | 2      | 0.55%   |
| AMD                       | 2         | 2      | 0.55%   |
| Unknown                   | 2         | 4      | 0.55%   |
| XUM                       | 1         | 1      | 0.28%   |
| USB3.0                    | 1         | 1      | 0.28%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.28%   |
| Union Memory              | 1         | 1      | 0.28%   |
| TS512GMT                  | 1         | 5      | 0.28%   |
| Transcend                 | 1         | 1      | 0.28%   |
| Timetec                   | 1         | 2      | 0.28%   |
| SPCC Sol                  | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 11        | 2.78%   |
| Crucial CT1000MX500SSD1 1TB                         | 6         | 1.52%   |
| Toshiba DT01ACA100 1TB                              | 5         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 1.27%   |
| Crucial CT240BX500SSD1 240GB                        | 5         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 1.01%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 4         | 1.01%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 1.01%   |
| Samsung SSD 860 EVO 250GB                           | 4         | 1.01%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 0.76%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.76%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 0.76%   |
| Seagate ST3500418AS 500GB                           | 3         | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 0.76%   |
| Samsung SSD 970 EVO 1TB                             | 3         | 0.76%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 0.76%   |
| Phison E12 NVMe Controller 512GB                    | 3         | 0.76%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.76%   |
| HGST HTS541010A9E680 1TB                            | 3         | 0.76%   |
| China SATA SSD 960GB                                | 3         | 0.76%   |
| WDC WD80EZAZ-11TDBA0 8TB                            | 2         | 0.51%   |
| WDC WD40EZRZ-00WN9B0 4TB                            | 2         | 0.51%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 2         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.51%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 2         | 0.51%   |
| WDC WD100EMAZ-00WJTA0 10TB                          | 2         | 0.51%   |
| WALRAM 240G                                         | 2         | 0.51%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.51%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.51%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.51%   |
| Toshiba DT01ACA050 500GB                            | 2         | 0.51%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 0.51%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.51%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.51%   |
| Samsung SSD 980 1TB                                 | 2         | 0.51%   |
| Samsung SSD 870 EVO 250GB                           | 2         | 0.51%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.51%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.51%   |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 53     | 33.59%  |
| WDC                 | 41        | 63     | 31.3%   |
| Toshiba             | 21        | 22     | 16.03%  |
| HGST                | 10        | 11     | 7.63%   |
| Hitachi             | 8         | 9      | 6.11%   |
| Unknown             | 2         | 2      | 1.53%   |
| Maxtor              | 2         | 2      | 1.53%   |
| USB3.0              | 1         | 1      | 0.76%   |
| Samsung Electronics | 1         | 1      | 0.76%   |
| JMicron Technology  | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 29     | 21.05%  |
| Crucial             | 20        | 28     | 17.54%  |
| Kingston            | 17        | 18     | 14.91%  |
| WDC                 | 6         | 9      | 5.26%   |
| China               | 6         | 7      | 5.26%   |
| SanDisk             | 4         | 4      | 3.51%   |
| Intel               | 3         | 4      | 2.63%   |
| Apple               | 3         | 4      | 2.63%   |
| A-DATA Technology   | 3         | 3      | 2.63%   |
| SPCC                | 2         | 2      | 1.75%   |
| SK hynix            | 2         | 2      | 1.75%   |
| Micron Technology   | 2         | 2      | 1.75%   |
| Linux               | 2         | 2      | 1.75%   |
| AMD                 | 2         | 2      | 1.75%   |
| XUM                 | 1         | 1      | 0.88%   |
| Toshiba             | 1         | 1      | 0.88%   |
| SPCC Sol            | 1         | 1      | 0.88%   |
| PNY                 | 1         | 1      | 0.88%   |
| Plextor             | 1         | 1      | 0.88%   |
| Patriot             | 1         | 1      | 0.88%   |
| Netac               | 1         | 1      | 0.88%   |
| LITEON              | 1         | 1      | 0.88%   |
| LDLC                | 1         | 5      | 0.88%   |
| KingSpec            | 1         | 1      | 0.88%   |
| JMicron Technology  | 1         | 1      | 0.88%   |
| Intenso             | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| GOODRAM             | 1         | 1      | 0.88%   |
| Dogfish             | 1         | 1      | 0.88%   |
| Biostar             | 1         | 1      | 0.88%   |
| Apacer              | 1         | 1      | 0.88%   |
| AGI                 | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 114       | 165    | 35.08%  |
| SSD     | 101       | 138    | 31.08%  |
| NVMe    | 99        | 146    | 30.46%  |
| Unknown | 7         | 14     | 2.15%   |
| MMC     | 4         | 4      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 168       | 297    | 59.15%  |
| NVMe | 99        | 146    | 34.86%  |
| SAS  | 13        | 20     | 4.58%   |
| MMC  | 4         | 4      | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 161    | 52.68%  |
| 0.51-1.0   | 72        | 97     | 32.14%  |
| 1.01-2.0   | 17        | 19     | 7.59%   |
| 4.01-10.0  | 8         | 15     | 3.57%   |
| 3.01-4.0   | 5         | 7      | 2.23%   |
| 2.01-3.0   | 4         | 4      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 24.47%  |
| 251-500        | 52        | 21.94%  |
| 1001-2000      | 33        | 13.92%  |
| 501-1000       | 33        | 13.92%  |
| More than 3000 | 20        | 8.44%   |
| 2001-3000      | 14        | 5.91%   |
| Unknown        | 9         | 3.8%    |
| 51-100         | 8         | 3.38%   |
| 1-20           | 6         | 2.53%   |
| 21-50          | 4         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 57        | 23.08%  |
| 101-250        | 39        | 15.79%  |
| 251-500        | 29        | 11.74%  |
| 21-50          | 27        | 10.93%  |
| 501-1000       | 27        | 10.93%  |
| 51-100         | 26        | 10.53%  |
| 1001-2000      | 19        | 7.69%   |
| More than 3000 | 9         | 3.64%   |
| Unknown        | 9         | 3.64%   |
| 2001-3000      | 4         | 1.62%   |
| 0              | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB                         | 3         | 3      | 8.11%   |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 5.41%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 5.41%   |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 2.7%    |
| WDC WD5000AVCS-632DY1 500GB                      | 1         | 1      | 2.7%    |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 2.7%    |
| WDC WD3200BEKT-60F3T1 320GB                      | 1         | 1      | 2.7%    |
| WDC WD3200AAKX-00ERMA0 320GB                     | 1         | 1      | 2.7%    |
| WDC WD30EZRX-00DC0B0 3TB                         | 1         | 1      | 2.7%    |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 2.7%    |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 2.7%    |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.7%    |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 2.7%    |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 2.7%    |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.7%    |
| Seagate ST8000DM004-2CX188 8TB                   | 1         | 1      | 2.7%    |
| Seagate ST6000VN0033-2EE110 6TB                  | 1         | 1      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST2000DX002-2DV164 2TB                   | 1         | 1      | 2.7%    |
| Seagate ST2000DM006-2DM164 2TB                   | 1         | 1      | 2.7%    |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 2.7%    |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.7%    |
| Maxtor 6Y080M0 82GB                              | 1         | 1      | 2.7%    |
| LDLC SSD 120GB                                   | 1         | 3      | 2.7%    |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 2.7%    |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 2.7%    |
| Intel SSDSC2BW480A4 480GB                        | 1         | 2      | 2.7%    |
| Intel SSDPEKKW128G7 128GB                        | 1         | 1      | 2.7%    |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 2.7%    |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 2.7%    |
| Hewlett-Packard SSD EX900 250GB                  | 1         | 1      | 2.7%    |
| A-DATA Technology SU650 240GB SSD                | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 18.92%  |
| Toshiba             | 7         | 7      | 18.92%  |
| Seagate             | 7         | 7      | 18.92%  |
| HGST                | 5         | 5      | 13.51%  |
| Kingston            | 2         | 2      | 5.41%   |
| Intel               | 2         | 3      | 5.41%   |
| Hitachi             | 2         | 2      | 5.41%   |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 1      | 2.7%    |
| LDLC                | 1         | 3      | 2.7%    |
| Hewlett-Packard     | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 24.14%  |
| Toshiba | 7         | 7      | 24.14%  |
| Seagate | 7         | 7      | 24.14%  |
| HGST    | 5         | 5      | 17.24%  |
| Hitachi | 2         | 2      | 6.9%    |
| Maxtor  | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 29     | 77.78%  |
| SSD  | 6         | 9      | 16.67%  |
| NVMe | 2         | 2      | 5.56%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 127       | 230    | 48.29%  |
| Detected | 100       | 196    | 38.02%  |
| Malfunc  | 35        | 40     | 13.31%  |
| Fixed    | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 130       | 41.8%   |
| AMD                            | 65        | 20.9%   |
| Samsung Electronics            | 39        | 12.54%  |
| SanDisk                        | 16        | 5.14%   |
| Phison Electronics             | 11        | 3.54%   |
| SK hynix                       | 7         | 2.25%   |
| Marvell Technology Group       | 6         | 1.93%   |
| Kingston Technology Company    | 6         | 1.93%   |
| ASMedia Technology             | 5         | 1.61%   |
| Silicon Motion                 | 4         | 1.29%   |
| Union Memory (Shenzhen)        | 3         | 0.96%   |
| ADATA Technology               | 3         | 0.96%   |
| Toshiba America Info Systems   | 2         | 0.64%   |
| Solid State Storage Technology | 2         | 0.64%   |
| Micron/Crucial Technology      | 2         | 0.64%   |
| Micron Technology              | 2         | 0.64%   |
| Shenzhen Longsys Electronics   | 1         | 0.32%   |
| Nvidia                         | 1         | 0.32%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.32%   |
| Lite-On Technology             | 1         | 0.32%   |
| Lenovo                         | 1         | 0.32%   |
| KIOXIA                         | 1         | 0.32%   |
| JMicron Technology             | 1         | 0.32%   |
| Broadcom / LSI                 | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 51        | 14.74%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 23        | 6.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 4.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 3.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 2.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 2.6%    |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 2.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 2.02%   |
| AMD 300 Series Chipset SATA Controller                                         | 7         | 2.02%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.73%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 5         | 1.45%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.16%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 4         | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.16%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.16%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 3         | 0.87%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.87%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 0.87%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.87%   |
| Intel SSD 660P Series                                                          | 3         | 0.87%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.87%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 0.58%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.58%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.58%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 0.58%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 177       | 58.03%  |
| NVMe | 100       | 32.79%  |
| RAID | 16        | 5.25%   |
| IDE  | 11        | 3.61%   |
| SAS  | 1         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 151       | 65.65%  |
| AMD    | 79        | 34.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD FX-8350 Eight-Core Processor              | 5         | 2.16%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 1.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 1.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.3%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.3%    |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 1.3%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.3%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.3%    |
| AMD Ryzen 5 2600X Six-Core Processor          | 3         | 1.3%    |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 1.3%    |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.87%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.87%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.87%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.87%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.87%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 2         | 0.87%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.87%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.87%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 2         | 0.87%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.87%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.87%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 2         | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.87%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 0.87%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.87%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.87%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 53        | 23.04%  |
| Intel Core i7           | 36        | 15.65%  |
| AMD Ryzen 7             | 22        | 9.57%   |
| AMD Ryzen 5             | 22        | 9.57%   |
| Other                   | 16        | 6.96%   |
| Intel Core i3           | 14        | 6.09%   |
| Intel Celeron           | 10        | 4.35%   |
| AMD Ryzen 3             | 7         | 3.04%   |
| Intel Pentium           | 6         | 2.61%   |
| AMD FX                  | 6         | 2.61%   |
| AMD Ryzen 9             | 5         | 2.17%   |
| Intel Xeon              | 4         | 1.74%   |
| Intel Core 2 Duo        | 4         | 1.74%   |
| Intel Core m3           | 3         | 1.3%    |
| AMD Athlon              | 3         | 1.3%    |
| AMD A10                 | 3         | 1.3%    |
| Intel Core i9           | 2         | 0.87%   |
| AMD Ryzen Threadripper  | 2         | 0.87%   |
| AMD A6                  | 2         | 0.87%   |
| Intel Pentium Silver    | 1         | 0.43%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Atom              | 1         | 0.43%   |
| AMD Ryzen 7 PRO         | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD Phenom II X4        | 1         | 0.43%   |
| AMD Phenom II           | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD A8                  | 1         | 0.43%   |
| AMD A4                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 78        | 33.91%  |
| 4      | 74        | 32.17%  |
| 6      | 32        | 13.91%  |
| 8      | 30        | 13.04%  |
| 12     | 6         | 2.61%   |
| 10     | 3         | 1.3%    |
| 14     | 2         | 0.87%   |
| 3      | 2         | 0.87%   |
| 32     | 1         | 0.43%   |
| 16     | 1         | 0.43%   |
| 1      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 230       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 176       | 76.52%  |
| 1      | 54        | 23.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 230       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 31.78%  |
| 0x206a7    | 12        | 5.08%   |
| 0x306a9    | 11        | 4.66%   |
| 0xa0652    | 6         | 2.54%   |
| 0x08701013 | 6         | 2.54%   |
| 0x08600106 | 6         | 2.54%   |
| 0x0800820d | 6         | 2.54%   |
| 0x806ec    | 5         | 2.12%   |
| 0x806e9    | 5         | 2.12%   |
| 0x806c1    | 5         | 2.12%   |
| 0x40651    | 5         | 2.12%   |
| 0x306d4    | 5         | 2.12%   |
| 0x906ed    | 4         | 1.69%   |
| 0x906e9    | 4         | 1.69%   |
| 0x806ea    | 4         | 1.69%   |
| 0x706e5    | 4         | 1.69%   |
| 0x706a1    | 4         | 1.69%   |
| 0x08701021 | 4         | 1.69%   |
| 0x08108109 | 4         | 1.69%   |
| 0x906ea    | 3         | 1.27%   |
| 0x506e3    | 3         | 1.27%   |
| 0x306c3    | 3         | 1.27%   |
| 0x1067a    | 3         | 1.27%   |
| 0x08608103 | 3         | 1.27%   |
| 0x06000822 | 3         | 1.27%   |
| 0xa0655    | 2         | 0.85%   |
| 0x30678    | 2         | 0.85%   |
| 0x0a201016 | 2         | 0.85%   |
| 0x08600103 | 2         | 0.85%   |
| 0x08108102 | 2         | 0.85%   |
| 0x08101007 | 2         | 0.85%   |
| 0x08001137 | 2         | 0.85%   |
| 0x06003106 | 2         | 0.85%   |
| 0x06000852 | 2         | 0.85%   |
| 0xa0653    | 1         | 0.42%   |
| 0x906a3    | 1         | 0.42%   |
| 0x806eb    | 1         | 0.42%   |
| 0x806d1    | 1         | 0.42%   |
| 0x806c2    | 1         | 0.42%   |
| 0x6fd      | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 16.96%  |
| Zen 2            | 23        | 10%     |
| Zen+             | 19        | 8.26%   |
| IvyBridge        | 19        | 8.26%   |
| SandyBridge      | 16        | 6.96%   |
| Haswell          | 13        | 5.65%   |
| CometLake        | 11        | 4.78%   |
| Zen 3            | 8         | 3.48%   |
| Zen              | 8         | 3.48%   |
| TigerLake        | 8         | 3.48%   |
| Broadwell        | 8         | 3.48%   |
| Unknown          | 8         | 3.48%   |
| Piledriver       | 7         | 3.04%   |
| Skylake          | 6         | 2.61%   |
| Silvermont       | 5         | 2.17%   |
| IceLake          | 5         | 2.17%   |
| Penryn           | 4         | 1.74%   |
| Goldmont plus    | 4         | 1.74%   |
| Alderlake Hybrid | 4         | 1.74%   |
| Westmere         | 3         | 1.3%    |
| Steamroller      | 3         | 1.3%    |
| Puma             | 2         | 0.87%   |
| K10              | 2         | 0.87%   |
| Jaguar           | 1         | 0.43%   |
| Goldmont         | 1         | 0.43%   |
| Excavator        | 1         | 0.43%   |
| Core             | 1         | 0.43%   |
| Bonnell          | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 119       | 44.07%  |
| AMD    | 84        | 31.11%  |
| Nvidia | 67        | 24.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 14        | 5.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 3.99%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 10        | 3.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 10        | 3.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 10        | 3.62%   |
| Intel UHD Graphics 620                                                    | 7         | 2.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 2.54%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 2.54%   |
| Intel HD Graphics 620                                                     | 6         | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 2.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 6         | 2.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 1.81%   |
| Intel HD Graphics 5500                                                    | 5         | 1.81%   |
| AMD Lucienne                                                              | 5         | 1.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 4         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 1.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 1.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 1.45%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.09%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 3         | 1.09%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 2         | 0.72%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 0.72%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 2         | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2         | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 0.72%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 2         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.72%   |
| Intel UHD Graphics 615                                                    | 2         | 0.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 0.72%   |
| Intel HD Graphics 630                                                     | 2         | 0.72%   |
| Intel HD Graphics 6000                                                    | 2         | 0.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2         | 0.72%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 2         | 0.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 0.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 82        | 35.34%  |
| 1 x AMD        | 73        | 31.47%  |
| 1 x Nvidia     | 33        | 14.22%  |
| Intel + Nvidia | 31        | 13.36%  |
| 2 x AMD        | 5         | 2.16%   |
| Intel + AMD    | 4         | 1.72%   |
| AMD + Nvidia   | 3         | 1.29%   |
| 2 x Intel      | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 186       | 80.17%  |
| Proprietary | 45        | 19.4%   |
| Unknown     | 1         | 0.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 57.2%   |
| 1.01-2.0   | 24        | 10.17%  |
| 7.01-8.0   | 18        | 7.63%   |
| 0.01-0.5   | 18        | 7.63%   |
| 3.01-4.0   | 16        | 6.78%   |
| 0.51-1.0   | 12        | 5.08%   |
| 8.01-16.0  | 7         | 2.97%   |
| 5.01-6.0   | 5         | 2.12%   |
| 2.01-3.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 12.19%  |
| BOE                     | 28        | 10.04%  |
| Samsung Electronics     | 27        | 9.68%   |
| Chimei Innolux          | 27        | 9.68%   |
| LG Display              | 25        | 8.96%   |
| Goldstar                | 15        | 5.38%   |
| Acer                    | 13        | 4.66%   |
| Philips                 | 11        | 3.94%   |
| Dell                    | 10        | 3.58%   |
| ASUSTek Computer        | 10        | 3.58%   |
| AOC                     | 9         | 3.23%   |
| BenQ                    | 7         | 2.51%   |
| Chi Mei Optoelectronics | 5         | 1.79%   |
| Ancor Communications    | 5         | 1.79%   |
| Lenovo                  | 4         | 1.43%   |
| Hewlett-Packard         | 4         | 1.43%   |
| Apple                   | 4         | 1.43%   |
| PANDA                   | 3         | 1.08%   |
| MSI                     | 3         | 1.08%   |
| InfoVision              | 3         | 1.08%   |
| ViewSonic               | 2         | 0.72%   |
| Unknown                 | 2         | 0.72%   |
| Sony                    | 2         | 0.72%   |
| Sharp                   | 2         | 0.72%   |
| Vestel Elektronik       | 1         | 0.36%   |
| Packard Bell            | 1         | 0.36%   |
| LGD                     | 1         | 0.36%   |
| LG Electronics          | 1         | 0.36%   |
| Lenovo Group Limited    | 1         | 0.36%   |
| KTC                     | 1         | 0.36%   |
| KDC                     | 1         | 0.36%   |
| Jean                    | 1         | 0.36%   |
| Iiyama                  | 1         | 0.36%   |
| Idek Iiyama             | 1         | 0.36%   |
| HVR                     | 1         | 0.36%   |
| HUAWEI                  | 1         | 0.36%   |
| HKC                     | 1         | 0.36%   |
| Hitachi                 | 1         | 0.36%   |
| GAOMON                  | 1         | 0.36%   |
| Envision Peripherals    | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 4         | 1.41%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                   | 3         | 1.06%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 3         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.06%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 3         | 1.06%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 0.71%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 2         | 0.71%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 2         | 0.71%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.71%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.71%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.71%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.71%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.71%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 0.71%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.71%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 0.71%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                      | 2         | 0.71%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch            | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.71%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch              | 2         | 0.71%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 0.71%   |
| AOC 2200W AOC2200 1920x1080 476x268mm 21.5-inch                           | 2         | 0.71%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch     | 2         | 0.71%   |
| ViewSonic VA2256 Series VSC3136 1920x1080 476x268mm 21.5-inch             | 1         | 0.35%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                             | 1         | 0.35%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch        | 1         | 0.35%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.35%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                             | 1         | 0.35%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.35%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch         | 1         | 0.35%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch         | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch       | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.35%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch        | 1         | 0.35%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 121       | 45.66%  |
| 1366x768 (WXGA)    | 56        | 21.13%  |
| 3840x2160 (4K)     | 23        | 8.68%   |
| 2560x1440 (QHD)    | 11        | 4.15%   |
| 1600x900 (HD+)     | 7         | 2.64%   |
| 3440x1440          | 5         | 1.89%   |
| 2560x1600          | 5         | 1.89%   |
| 1440x900 (WXGA+)   | 5         | 1.89%   |
| 1280x1024 (SXGA)   | 5         | 1.89%   |
| 2560x1080          | 3         | 1.13%   |
| 1920x1200 (WUXGA)  | 3         | 1.13%   |
| Unknown            | 3         | 1.13%   |
| 3840x1080          | 2         | 0.75%   |
| 2288x1287          | 2         | 0.75%   |
| 1680x1050 (WSXGA+) | 2         | 0.75%   |
| 1360x768           | 2         | 0.75%   |
| 4480x1080          | 1         | 0.38%   |
| 3600x1080          | 1         | 0.38%   |
| 3456x2160          | 1         | 0.38%   |
| 3072x1920          | 1         | 0.38%   |
| 2736x1824          | 1         | 0.38%   |
| 2160x1440          | 1         | 0.38%   |
| 2160x1200          | 1         | 0.38%   |
| 1280x960           | 1         | 0.38%   |
| 1280x800 (WXGA)    | 1         | 0.38%   |
| 1024x768 (XGA)     | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 79        | 28.83%  |
| 14      | 27        | 9.85%   |
| 13      | 25        | 9.12%   |
| 27      | 22        | 8.03%   |
| 24      | 22        | 8.03%   |
| 21      | 19        | 6.93%   |
| 23      | 16        | 5.84%   |
| 17      | 11        | 4.01%   |
| 34      | 8         | 2.92%   |
| Unknown | 7         | 2.55%   |
| 19      | 6         | 2.19%   |
| 84      | 4         | 1.46%   |
| 31      | 4         | 1.46%   |
| 16      | 4         | 1.46%   |
| 11      | 4         | 1.46%   |
| 142     | 2         | 0.73%   |
| 72      | 2         | 0.73%   |
| 32      | 2         | 0.73%   |
| 20      | 2         | 0.73%   |
| 12      | 2         | 0.73%   |
| 52      | 1         | 0.36%   |
| 48      | 1         | 0.36%   |
| 28      | 1         | 0.36%   |
| 25      | 1         | 0.36%   |
| 18      | 1         | 0.36%   |
| 8       | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 123       | 45.56%  |
| 501-600        | 53        | 19.63%  |
| 401-500        | 24        | 8.89%   |
| 351-400        | 18        | 6.67%   |
| 201-300        | 14        | 5.19%   |
| 701-800        | 10        | 3.7%    |
| 601-700        | 10        | 3.7%    |
| Unknown        | 7         | 2.59%   |
| 1501-2000      | 6         | 2.22%   |
| More than 2000 | 2         | 0.74%   |
| 1001-1500      | 2         | 0.74%   |
| 101-200        | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 194       | 80.5%   |
| 16/10   | 19        | 7.88%   |
| 21/9    | 8         | 3.32%   |
| 5/4     | 6         | 2.49%   |
| Unknown | 6         | 2.49%   |
| 4/3     | 2         | 0.83%   |
| 3/2     | 2         | 0.83%   |
| 1.00    | 2         | 0.83%   |
| 32/9    | 1         | 0.41%   |
| 0.62    | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 29.41%  |
| 201-250        | 50        | 18.38%  |
| 81-90          | 43        | 15.81%  |
| 301-350        | 22        | 8.09%   |
| 351-500        | 15        | 5.51%   |
| More than 1000 | 9         | 3.31%   |
| 71-80          | 9         | 3.31%   |
| 151-200        | 9         | 3.31%   |
| 121-130        | 8         | 2.94%   |
| Unknown        | 7         | 2.57%   |
| 251-300        | 6         | 2.21%   |
| 51-60          | 4         | 1.47%   |
| 141-150        | 3         | 1.1%    |
| 131-140        | 2         | 0.74%   |
| 111-120        | 2         | 0.74%   |
| 61-70          | 1         | 0.37%   |
| 1-40           | 1         | 0.37%   |
| 501-1000       | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 87        | 33.46%  |
| 101-120       | 73        | 28.08%  |
| 51-100        | 70        | 26.92%  |
| 161-240       | 14        | 5.38%   |
| Unknown       | 7         | 2.69%   |
| 1-50          | 5         | 1.92%   |
| More than 240 | 4         | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 182       | 77.45%  |
| 2     | 48        | 20.43%  |
| 3     | 3         | 1.28%   |
| 4     | 1         | 0.43%   |
| 0     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 148       | 42.53%  |
| Intel                                 | 110       | 31.61%  |
| Qualcomm Atheros                      | 29        | 8.33%   |
| Broadcom                              | 14        | 4.02%   |
| TP-Link                               | 5         | 1.44%   |
| Ralink Technology                     | 4         | 1.15%   |
| MediaTek                              | 4         | 1.15%   |
| Broadcom Limited                      | 4         | 1.15%   |
| Samsung Electronics                   | 3         | 0.86%   |
| D-Link System                         | 3         | 0.86%   |
| Xiaomi                                | 2         | 0.57%   |
| Ralink                                | 2         | 0.57%   |
| Qualcomm                              | 2         | 0.57%   |
| Marvell Technology Group              | 2         | 0.57%   |
| ASIX Electronics                      | 2         | 0.57%   |
| Aquantia                              | 2         | 0.57%   |
| Sierra Wireless                       | 1         | 0.29%   |
| Qualcomm Atheros Communications       | 1         | 0.29%   |
| OPPO Electronics                      | 1         | 0.29%   |
| Microsoft                             | 1         | 0.29%   |
| Linksys                               | 1         | 0.29%   |
| Lenovo                                | 1         | 0.29%   |
| Huawei Technologies                   | 1         | 0.29%   |
| Google                                | 1         | 0.29%   |
| DisplayLink                           | 1         | 0.29%   |
| Dell                                  | 1         | 0.29%   |
| Apple                                 | 1         | 0.29%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 99        | 23.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 19        | 4.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 12        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 12        | 2.86%   |
| Intel Wi-Fi 6 AX200                                                  | 11        | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 10        | 2.38%   |
| Intel Wireless 8265 / 8275                                           | 10        | 2.38%   |
| Intel I211 Gigabit Network Connection                                | 10        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 6         | 1.43%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 1.43%   |
| Intel Wireless 7265                                                  | 5         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                | 4         | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 3         | 0.71%   |
| Realtek 802.11ac NIC                                                 | 3         | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 0.71%   |
| Intel Wireless 7260                                                  | 3         | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                 | 3         | 0.71%   |
| Intel Ethernet Connection (11) I219-LM                               | 3         | 0.71%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 0.48%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 2         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 2         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.48%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 92        | 46.46%  |
| Realtek Semiconductor                 | 42        | 21.21%  |
| Qualcomm Atheros                      | 24        | 12.12%  |
| Broadcom                              | 13        | 6.57%   |
| TP-Link                               | 5         | 2.53%   |
| Ralink Technology                     | 4         | 2.02%   |
| MediaTek                              | 4         | 2.02%   |
| Broadcom Limited                      | 4         | 2.02%   |
| Ralink                                | 2         | 1.01%   |
| Sierra Wireless                       | 1         | 0.51%   |
| Qualcomm Atheros Communications       | 1         | 0.51%   |
| Qualcomm                              | 1         | 0.51%   |
| Microsoft                             | 1         | 0.51%   |
| Marvell Technology Group              | 1         | 0.51%   |
| Dell                                  | 1         | 0.51%   |
| D-Link System                         | 1         | 0.51%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 12        | 5.97%   |
| Intel Wi-Fi 6 AX200                                                  | 11        | 5.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 4.98%   |
| Intel Wireless 8265 / 8275                                           | 10        | 4.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 3.48%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 3.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 3.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 2.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 6         | 2.99%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 2.99%   |
| Intel Wireless 7265                                                  | 5         | 2.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 2.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 2.49%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 2.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 2.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 1.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 1.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.49%   |
| Realtek 802.11ac NIC                                                 | 3         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.49%   |
| Intel Wireless 7260                                                  | 3         | 1.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.49%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 1.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 1.49%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 1%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 2         | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 1%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 1%      |
| Ralink RT5370 Wireless Adapter                                       | 2         | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1%      |
| Intel Wireless-AC 9260                                               | 2         | 1%      |
| Intel Wireless 3165                                                  | 2         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1%      |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1%      |
| Intel Centrino Advanced-N 6235                                       | 2         | 1%      |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 129       | 61.72%  |
| Intel                    | 51        | 24.4%   |
| Qualcomm Atheros         | 9         | 4.31%   |
| Xiaomi                   | 2         | 0.96%   |
| D-Link System            | 2         | 0.96%   |
| Broadcom                 | 2         | 0.96%   |
| ASIX Electronics         | 2         | 0.96%   |
| Aquantia                 | 2         | 0.96%   |
| Samsung Electronics      | 1         | 0.48%   |
| Qualcomm                 | 1         | 0.48%   |
| OPPO Electronics         | 1         | 0.48%   |
| Marvell Technology Group | 1         | 0.48%   |
| Linksys                  | 1         | 0.48%   |
| Lenovo                   | 1         | 0.48%   |
| Huawei Technologies      | 1         | 0.48%   |
| Google                   | 1         | 0.48%   |
| DisplayLink              | 1         | 0.48%   |
| Apple                    | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 99        | 45.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 8.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 5.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 4.61%   |
| Intel I211 Gigabit Network Connection                             | 10        | 4.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.84%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.38%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.92%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.92%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.46%   |
| Qualcomm A0001                                                    | 1         | 0.46%   |
| OPPO RMX3623                                                      | 1         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.46%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.46%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.46%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.46%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.46%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 190       | 49.87%  |
| Ethernet | 189       | 49.61%  |
| Modem    | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 62.92%  |
| Ethernet | 89        | 37.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 131       | 56.71%  |
| 1     | 90        | 38.96%  |
| 3     | 6         | 2.6%    |
| 4     | 2         | 0.87%   |
| 0     | 2         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 193       | 82.13%  |
| Yes  | 42        | 17.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 46.91%  |
| Realtek Semiconductor           | 24        | 14.81%  |
| Broadcom                        | 12        | 7.41%   |
| IMC Networks                    | 10        | 6.17%   |
| Cambridge Silicon Radio         | 9         | 5.56%   |
| Qualcomm Atheros Communications | 8         | 4.94%   |
| Lite-On Technology              | 5         | 3.09%   |
| ASUSTek Computer                | 4         | 2.47%   |
| Apple                           | 4         | 2.47%   |
| Foxconn / Hon Hai               | 3         | 1.85%   |
| Realtek                         | 2         | 1.23%   |
| Ralink                          | 1         | 0.62%   |
| MediaTek                        | 1         | 0.62%   |
| Marvell Semiconductor           | 1         | 0.62%   |
| HTC (High Tech Computer)        | 1         | 0.62%   |
| Dynex                           | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 20        | 12.27%  |
| Intel AX201 Bluetooth                                                | 17        | 10.43%  |
| Realtek Bluetooth Radio                                              | 15        | 9.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 11        | 6.75%   |
| Intel AX200 Bluetooth                                                | 11        | 6.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 9         | 5.52%   |
| Qualcomm Atheros  Bluetooth Device                                   | 5         | 3.07%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 5         | 3.07%   |
| Intel AX210 Bluetooth                                                | 5         | 3.07%   |
| IMC Networks Bluetooth Radio                                         | 5         | 3.07%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 2.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 4         | 2.45%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4         | 2.45%   |
| Realtek 802.11ac WLAN Adapter                                        | 3         | 1.84%   |
| IMC Networks Wireless_Device                                         | 3         | 1.84%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 1.84%   |
| Realtek Bluetooth Radio                                              | 2         | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2         | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.23%   |
| Intel Bluetooth Device                                               | 2         | 1.23%   |
| IMC Networks Bluetooth Device                                        | 2         | 1.23%   |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 2         | 1.23%   |
| Apple Bluetooth USB Host Controller                                  | 2         | 1.23%   |
| Apple Bluetooth Host Controller                                      | 2         | 1.23%   |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.61%   |
| Realtek Bluetooth 5.1 Radio                                          | 1         | 0.61%   |
| Ralink RT3290 Bluetooth                                              | 1         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 0.61%   |
| MediaTek Wireless_Device                                             | 1         | 0.61%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1         | 0.61%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1         | 0.61%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1         | 0.61%   |
| Broadcom HP Portable Valentine                                       | 1         | 0.61%   |
| Broadcom BCM43142A0 Bluetooth Device                                 | 1         | 0.61%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.61%   |
| Broadcom BCM2070 Bluetooth Device                                    | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 149       | 42.69%  |
| AMD                                             | 94        | 26.93%  |
| Nvidia                                          | 53        | 15.19%  |
| C-Media Electronics                             | 12        | 3.44%   |
| Realtek Semiconductor                           | 5         | 1.43%   |
| Creative Labs                                   | 5         | 1.43%   |
| Logitech                                        | 3         | 0.86%   |
| Generalplus Technology                          | 2         | 0.57%   |
| Creative Technology                             | 2         | 0.57%   |
| Corsair                                         | 2         | 0.57%   |
| Texas Instruments                               | 1         | 0.29%   |
| TC Electronic                                   | 1         | 0.29%   |
| SteelSeries ApS                                 | 1         | 0.29%   |
| Shure                                           | 1         | 0.29%   |
| Razer USA                                       | 1         | 0.29%   |
| PreSonus Audio Electronics                      | 1         | 0.29%   |
| Plantronics                                     | 1         | 0.29%   |
| Native Instruments                              | 1         | 0.29%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.29%   |
| Lenovo                                          | 1         | 0.29%   |
| JMTek                                           | 1         | 0.29%   |
| Hewlett-Packard                                 | 1         | 0.29%   |
| Harman                                          | 1         | 0.29%   |
| GN Netcom                                       | 1         | 0.29%   |
| Focusrite-Novation                              | 1         | 0.29%   |
| EVGA                                            | 1         | 0.29%   |
| DSEA A/S                                        | 1         | 0.29%   |
| Blue Microphones                                | 1         | 0.29%   |
| AudioQuest                                      | 1         | 0.29%   |
| ASUSTek Computer                                | 1         | 0.29%   |
| Arylic                                          | 1         | 0.29%   |
| Apple                                           | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 7.66%   |
| Intel Sunrise Point-LP HD Audio                                            | 19        | 4.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 4.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 3.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 14        | 3.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 3.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13        | 3.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 1.86%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 1.62%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.62%   |
| AMD Navi 10 HDMI Audio                                                     | 7         | 1.62%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.39%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.16%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.93%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 0.93%   |
| C-Media Electronics USB Audio Device                                       | 4         | 0.93%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 23.18%  |
| SK hynix            | 41        | 17.6%   |
| Kingston            | 30        | 12.88%  |
| Corsair             | 17        | 7.3%    |
| Micron Technology   | 16        | 6.87%   |
| Unknown             | 13        | 5.58%   |
| G.Skill             | 12        | 5.15%   |
| Crucial             | 9         | 3.86%   |
| A-DATA Technology   | 7         | 3%      |
| Patriot             | 5         | 2.15%   |
| Unknown             | 4         | 1.72%   |
| Team                | 3         | 1.29%   |
| Smart               | 3         | 1.29%   |
| Silicon Power       | 3         | 1.29%   |
| Ramaxel Technology  | 3         | 1.29%   |
| Nanya Technology    | 3         | 1.29%   |
| Unknown (ABCD)      | 2         | 0.86%   |
| AMD                 | 2         | 0.86%   |
| Transcend           | 1         | 0.43%   |
| Smart Brazil        | 1         | 0.43%   |
| Golden Empire       | 1         | 0.43%   |
| Elpida              | 1         | 0.43%   |
| Avant               | 1         | 0.43%   |
| ASint Technology    | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 2.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.64%   |
| Unknown                                                          | 4         | 1.64%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.23%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 1.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.23%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 1.23%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 3         | 1.23%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 2         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 0.82%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.82%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.82%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s              | 2         | 0.82%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s            | 2         | 0.82%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s             | 2         | 0.82%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s         | 2         | 0.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.82%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 2         | 0.82%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 107       | 56.32%  |
| DDR3    | 63        | 33.16%  |
| LPDDR4  | 4         | 2.11%   |
| LPDDR3  | 4         | 2.11%   |
| DDR5    | 4         | 2.11%   |
| SDRAM   | 3         | 1.58%   |
| Unknown | 3         | 1.58%   |
| DDR2    | 2         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 60.21%  |
| DIMM         | 60        | 31.41%  |
| Row Of Chips | 14        | 7.33%   |
| Chip         | 1         | 0.52%   |
| Unknown      | 1         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 77        | 36.15%  |
| 4096  | 70        | 32.86%  |
| 16384 | 35        | 16.43%  |
| 2048  | 16        | 7.51%   |
| 32768 | 13        | 6.1%    |
| 1024  | 2         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 52        | 25.12%  |
| 3200    | 45        | 21.74%  |
| 2667    | 33        | 15.94%  |
| 2400    | 15        | 7.25%   |
| 1333    | 12        | 5.8%    |
| 3600    | 6         | 2.9%    |
| 2133    | 5         | 2.42%   |
| 3733    | 4         | 1.93%   |
| 2933    | 4         | 1.93%   |
| 1334    | 4         | 1.93%   |
| 4800    | 2         | 0.97%   |
| 4199    | 2         | 0.97%   |
| 3666    | 2         | 0.97%   |
| 3533    | 2         | 0.97%   |
| 3400    | 2         | 0.97%   |
| 3266    | 2         | 0.97%   |
| 3000    | 2         | 0.97%   |
| 800     | 2         | 0.97%   |
| 6000    | 1         | 0.48%   |
| 4802    | 1         | 0.48%   |
| 4267    | 1         | 0.48%   |
| 4133    | 1         | 0.48%   |
| 2800    | 1         | 0.48%   |
| 2481    | 1         | 0.48%   |
| 2465    | 1         | 0.48%   |
| 1328    | 1         | 0.48%   |
| 1066    | 1         | 0.48%   |
| 667     | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Ricoh               | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 1         | 20%     |
| Ricoh SP 211SU                | 1         | 20%     |
| HP Officejet Pro L7400        | 1         | 20%     |
| Brother HL-L3270CDW series    | 1         | 20%     |
| Brother HL-2030 Laser Printer | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 30        | 19.87%  |
| IMC Networks                           | 16        | 10.6%   |
| Quanta                                 | 14        | 9.27%   |
| Realtek Semiconductor                  | 12        | 7.95%   |
| Microdia                               | 11        | 7.28%   |
| Bison Electronics                      | 10        | 6.62%   |
| Suyin                                  | 6         | 3.97%   |
| Logitech                               | 6         | 3.97%   |
| Syntek                                 | 5         | 3.31%   |
| Sunplus Innovation Technology          | 5         | 3.31%   |
| Alcor Micro                            | 5         | 3.31%   |
| Sonix Technology                       | 4         | 2.65%   |
| Silicon Motion                         | 4         | 2.65%   |
| Luxvisions Innotech Limited            | 4         | 2.65%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.99%   |
| Acer                                   | 3         | 1.99%   |
| Creative Technology                    | 2         | 1.32%   |
| WaveRider Communications               | 1         | 0.66%   |
| Microsoft                              | 1         | 0.66%   |
| Lite-On Technology                     | 1         | 0.66%   |
| LG Electronics                         | 1         | 0.66%   |
| Lenovo                                 | 1         | 0.66%   |
| KYE Systems (Mouse Systems)            | 1         | 0.66%   |
| Google                                 | 1         | 0.66%   |
| GEMBIRD                                | 1         | 0.66%   |
| Cubeternet                             | 1         | 0.66%   |
| ARC International                      | 1         | 0.66%   |
| Apple                                  | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 9         | 5.96%   |
| Chicony HD WebCam                                   | 6         | 3.97%   |
| Chicony integrated camera                           | 5         | 3.31%   |
| Bison Integrated Camera                             | 5         | 3.31%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 2.65%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.65%   |
| Microdia Integrated Webcam                          | 4         | 2.65%   |
| Syntek EasyCamera                                   | 3         | 1.99%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.99%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.99%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.99%   |
| Syntek Integrated Camera                            | 2         | 1.32%   |
| Suyin HP Webcam                                     | 2         | 1.32%   |
| Sunplus HD WebCam                                   | 2         | 1.32%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 1.32%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 1.32%   |
| Realtek HD WebCam                                   | 2         | 1.32%   |
| Quanta VGA WebCam                                   | 2         | 1.32%   |
| Quanta USB2.0 VGA UVC WebCam                        | 2         | 1.32%   |
| Quanta HP Webcam                                    | 2         | 1.32%   |
| Quanta HD Webcam                                    | 2         | 1.32%   |
| Logitech Webcam C270                                | 2         | 1.32%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.32%   |
| Chicony thinkpad t430s camera                       | 2         | 1.32%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.32%   |
| Chicony HP TrueVision HD Camera                     | 2         | 1.32%   |
| Bison Lenovo EasyCamera                             | 2         | 1.32%   |
| WaveRider USB 2.0 Camera                            | 1         | 0.66%   |
| Suyin USB Webcam                                    | 1         | 0.66%   |
| Suyin NEC HD WebCam                                 | 1         | 0.66%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.66%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.66%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.66%   |
| Sunplus 5Mega Webcam                                | 1         | 0.66%   |
| Silicon Motion WebCam SCB-0355N                     | 1         | 0.66%   |
| Silicon Motion WebCam SC-10HDD12636N                | 1         | 0.66%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.66%   |
| Realtek Integrated Webcam                           | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 7         | 41.18%  |
| Synaptics                  | 5         | 29.41%  |
| Validity Sensors           | 3         | 17.65%  |
| STMicroelectronics         | 1         | 5.88%   |
| AuthenTec                  | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                       | 5         | 29.41%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 17.65%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 11.76%  |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 11.76%  |
| Validity Sensors VFS491                                   | 1         | 5.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 5.88%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 5.88%   |
| AuthenTec AES2810                                         | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 70%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Broadcom 58200                                                               | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 171       | 73.39%  |
| 1     | 53        | 22.75%  |
| 2     | 7         | 3%      |
| 3     | 2         | 0.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 22.54%  |
| Net/wireless             | 9         | 12.68%  |
| Graphics card            | 9         | 12.68%  |
| Chipcard                 | 8         | 11.27%  |
| Multimedia controller    | 6         | 8.45%   |
| Communication controller | 5         | 7.04%   |
| Camera                   | 5         | 7.04%   |
| Bluetooth                | 4         | 5.63%   |
| Unassigned class         | 2         | 2.82%   |
| Storage                  | 2         | 2.82%   |
| Net/ethernet             | 2         | 2.82%   |
| Sound                    | 1         | 1.41%   |
| Network                  | 1         | 1.41%   |
| Dvb card                 | 1         | 1.41%   |

