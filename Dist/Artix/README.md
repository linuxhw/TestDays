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

Total: 315

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 136       | 59.39%  |
| Artix          | 77        | 33.62%  |
| Artix 20220123 | 3         | 1.31%   |
| Artix 20230710 | 2         | 0.87%   |
| Artix 20220713 | 2         | 0.87%   |
| Artix 20210726 | 2         | 0.87%   |
| Artix 20230814 | 1         | 0.44%   |
| Artix 20230501 | 1         | 0.44%   |
| Artix 20230320 | 1         | 0.44%   |
| Artix 20230306 | 1         | 0.44%   |
| Artix 20230215 | 1         | 0.44%   |
| Artix 20201207 | 1         | 0.44%   |
| Artix 20201128 | 1         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 220       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.14-artix1-1   | 8         | 3.1%    |
| 5.7.6-artix1-1    | 5         | 1.94%   |
| 6.5.5-artix1-1    | 4         | 1.55%   |
| 6.4.10-artix1-1   | 4         | 1.55%   |
| 6.3.2-artix1-1    | 4         | 1.55%   |
| 6.1.8-artix1-1    | 4         | 1.55%   |
| 6.0.7-artix1-1    | 4         | 1.55%   |
| 5.7.12-artix1-1   | 4         | 1.55%   |
| 5.15.12-artix1-1  | 4         | 1.55%   |
| 5.12.12-artix1-1  | 4         | 1.55%   |
| 5.10.4-artix2-1   | 4         | 1.55%   |
| 6.5.7-artix1-1    | 3         | 1.16%   |
| 6.2.13-artix1-1   | 3         | 1.16%   |
| 5.8.8-artix1-1    | 3         | 1.16%   |
| 5.8.12-artix1-1   | 3         | 1.16%   |
| 5.18.16-artix1-1  | 3         | 1.16%   |
| 5.16.3-artix1-1   | 3         | 1.16%   |
| 5.16.10-artix1-1  | 3         | 1.16%   |
| 5.12.8-artix1-1   | 3         | 1.16%   |
| 5.12.14-artix1-1  | 3         | 1.16%   |
| 5.10.8-artix1-1   | 3         | 1.16%   |
| 5.10.6-artix1-1   | 3         | 1.16%   |
| 5.10.16-artix1-1  | 3         | 1.16%   |
| 6.5.2-artix1-1    | 2         | 0.78%   |
| 6.3.6-artix1-1    | 2         | 0.78%   |
| 6.3.3-artix1-1    | 2         | 0.78%   |
| 6.3.1-artix1-1    | 2         | 0.78%   |
| 6.2.6-artix1-1    | 2         | 0.78%   |
| 6.1.6-artix1-1    | 2         | 0.78%   |
| 6.1.32-1-lts      | 2         | 0.78%   |
| 6.1.12-artix1-1   | 2         | 0.78%   |
| 6.1.10-zen1-1-zen | 2         | 0.78%   |
| 6.0.12-artix1-1   | 2         | 0.78%   |
| 5.9.14-zen1-1-zen | 2         | 0.78%   |
| 5.9.12-artix1-1   | 2         | 0.78%   |
| 5.8.14-artix1-1   | 2         | 0.78%   |
| 5.7.2-artix1-1    | 2         | 0.78%   |
| 5.19.12-artix1-1  | 2         | 0.78%   |
| 5.18.9-zen1-1-zen | 2         | 0.78%   |
| 5.18.6-artix1-1   | 2         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 3.88%   |
| 5.12.12 | 6         | 2.33%   |
| 6.5.5   | 5         | 1.94%   |
| 6.3.2   | 5         | 1.94%   |
| 6.0.7   | 5         | 1.94%   |
| 5.7.6   | 5         | 1.94%   |
| 5.15.12 | 5         | 1.94%   |
| 6.4.10  | 4         | 1.55%   |
| 6.1.8   | 4         | 1.55%   |
| 6.1.10  | 4         | 1.55%   |
| 5.7.12  | 4         | 1.55%   |
| 5.12.8  | 4         | 1.55%   |
| 5.12.14 | 4         | 1.55%   |
| 5.10.4  | 4         | 1.55%   |
| 6.5.7   | 3         | 1.16%   |
| 6.5.2   | 3         | 1.16%   |
| 6.3.1   | 3         | 1.16%   |
| 6.2.13  | 3         | 1.16%   |
| 5.8.8   | 3         | 1.16%   |
| 5.8.14  | 3         | 1.16%   |
| 5.8.12  | 3         | 1.16%   |
| 5.18.16 | 3         | 1.16%   |
| 5.17.1  | 3         | 1.16%   |
| 5.16.3  | 3         | 1.16%   |
| 5.16.10 | 3         | 1.16%   |
| 5.13.8  | 3         | 1.16%   |
| 5.11.16 | 3         | 1.16%   |
| 5.10.8  | 3         | 1.16%   |
| 5.10.6  | 3         | 1.16%   |
| 5.10.16 | 3         | 1.16%   |
| 5.10.15 | 3         | 1.16%   |
| 6.4.4   | 2         | 0.78%   |
| 6.3.6   | 2         | 0.78%   |
| 6.3.3   | 2         | 0.78%   |
| 6.2.6   | 2         | 0.78%   |
| 6.1.6   | 2         | 0.78%   |
| 6.1.32  | 2         | 0.78%   |
| 6.1.12  | 2         | 0.78%   |
| 6.0.12  | 2         | 0.78%   |
| 5.9.12  | 2         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 8.47%   |
| 5.15    | 20        | 8.06%   |
| 6.1     | 19        | 7.66%   |
| 5.12    | 19        | 7.66%   |
| 5.9     | 17        | 6.85%   |
| 5.18    | 15        | 6.05%   |
| 6.3     | 14        | 5.65%   |
| 5.16    | 13        | 5.24%   |
| 5.11    | 13        | 5.24%   |
| 6.5     | 11        | 4.44%   |
| 6.4     | 11        | 4.44%   |
| 5.8     | 11        | 4.44%   |
| 5.17    | 11        | 4.44%   |
| 6.0     | 10        | 4.03%   |
| 5.7     | 10        | 4.03%   |
| 6.2     | 7         | 2.82%   |
| 5.14    | 7         | 2.82%   |
| 5.19    | 6         | 2.42%   |
| 5.13    | 6         | 2.42%   |
| 5.4     | 2         | 0.81%   |
| 4.19    | 2         | 0.81%   |
| 6.0.5   | 1         | 0.4%    |
| 5.6     | 1         | 0.4%    |
| 5.5     | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 220       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 61        | 26.18%  |
| XFCE           | 36        | 15.45%  |
| Unknown        | 33        | 14.16%  |
| GNOME          | 28        | 12.02%  |
| X-Cinnamon     | 14        | 6.01%   |
| MATE           | 14        | 6.01%   |
| i3             | 8         | 3.43%   |
| LXQt           | 7         | 3%      |
| Cinnamon       | 6         | 2.58%   |
| LXDE           | 5         | 2.15%   |
| bspwm          | 5         | 2.15%   |
| KDE            | 4         | 1.72%   |
| sway           | 3         | 1.29%   |
| xmonad         | 1         | 0.43%   |
| xinitrc        | 1         | 0.43%   |
| sway-dbus      | 1         | 0.43%   |
| openbox        | 1         | 0.43%   |
| nxde           | 1         | 0.43%   |
| Hyprland       | 1         | 0.43%   |
| DWM            | 1         | 0.43%   |
| awesomeminimal | 1         | 0.43%   |
| awesome        | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 159       | 70.35%  |
| Tty     | 29        | 12.83%  |
| Wayland | 24        | 10.62%  |
| Unknown | 14        | 6.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 87        | 38.16%  |
| LightDM | 67        | 29.39%  |
| SDDM    | 61        | 26.75%  |
| GDM     | 4         | 1.75%   |
| XDM     | 3         | 1.32%   |
| SLiM    | 2         | 0.88%   |
| Ly      | 2         | 0.88%   |
| LXDM    | 2         | 0.88%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 100       | 44.25%  |
| Unknown | 26        | 11.5%   |
| ru_RU   | 16        | 7.08%   |
| C       | 14        | 6.19%   |
| en_GB   | 10        | 4.42%   |
| fr_FR   | 9         | 3.98%   |
| de_DE   | 8         | 3.54%   |
| pt_BR   | 4         | 1.77%   |
| pt_PT   | 3         | 1.33%   |
| it_IT   | 3         | 1.33%   |
| es_ES   | 3         | 1.33%   |
| en_AU   | 3         | 1.33%   |
| tr_TR   | 2         | 0.88%   |
| pl_PL   | 2         | 0.88%   |
| es_MX   | 2         | 0.88%   |
| en_CA   | 2         | 0.88%   |
| en_AG   | 2         | 0.88%   |
| el_GR   | 2         | 0.88%   |
| vi_VN   | 1         | 0.44%   |
| uk_UA   | 1         | 0.44%   |
| ro_RO   | 1         | 0.44%   |
| lt_LT   | 1         | 0.44%   |
| ja_JP   | 1         | 0.44%   |
| fi_FI   | 1         | 0.44%   |
| es_GT   | 1         | 0.44%   |
| es_CO   | 1         | 0.44%   |
| es_AR   | 1         | 0.44%   |
| en_NZ   | 1         | 0.44%   |
| en_IN   | 1         | 0.44%   |
| en_IE   | 1         | 0.44%   |
| de_AT   | 1         | 0.44%   |
| cs_CZ   | 1         | 0.44%   |
| bg_BG   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 152       | 68.47%  |
| BIOS | 70        | 31.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 158       | 71.17%  |
| Btrfs   | 48        | 21.62%  |
| Xfs     | 7         | 3.15%   |
| F2fs    | 5         | 2.25%   |
| Overlay | 2         | 0.9%    |
| Tmpfs   | 1         | 0.45%   |
| Jfs     | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 159       | 71.3%   |
| Unknown | 40        | 17.94%  |
| MBR     | 24        | 10.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 179       | 80.27%  |
| Yes       | 44        | 19.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 164       | 74.21%  |
| Yes       | 57        | 25.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 41        | 18.64%  |
| ASUSTek Computer       | 36        | 16.36%  |
| Hewlett-Packard        | 25        | 11.36%  |
| Dell                   | 23        | 10.45%  |
| MSI                    | 19        | 8.64%   |
| Gigabyte Technology    | 19        | 8.64%   |
| Acer                   | 16        | 7.27%   |
| ASRock                 | 7         | 3.18%   |
| Apple                  | 4         | 1.82%   |
| Timi                   | 3         | 1.36%   |
| Samsung Electronics    | 3         | 1.36%   |
| Intel                  | 3         | 1.36%   |
| HUAWEI                 | 3         | 1.36%   |
| Notebook               | 2         | 0.91%   |
| GPD                    | 2         | 0.91%   |
| Biostar                | 2         | 0.91%   |
| UNOWHY                 | 1         | 0.45%   |
| Toshiba                | 1         | 0.45%   |
| Quanta                 | 1         | 0.45%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.45%   |
| MOTILE                 | 1         | 0.45%   |
| Microsoft              | 1         | 0.45%   |
| MACHINIST              | 1         | 0.45%   |
| LG Electronics         | 1         | 0.45%   |
| HONOR                  | 1         | 0.45%   |
| Fujitsu                | 1         | 0.45%   |
| AXIOO                  | 1         | 0.45%   |
| Alienware              | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| MSI MS-7A38                                           | 3         | 1.36%   |
| HP 15                                                 | 3         | 1.36%   |
| Timi RedmiBook 14 II                                  | 2         | 0.91%   |
| MSI MS-7C37                                           | 2         | 0.91%   |
| MSI MS-7C02                                           | 2         | 0.91%   |
| Lenovo IdeaPad 5 15IIL05 81YK                         | 2         | 0.91%   |
| GPD P2 MAX                                            | 2         | 0.91%   |
| Gigabyte 970A-DS3P                                    | 2         | 0.91%   |
| Dell Precision M6600                                  | 2         | 0.91%   |
| Dell Precision 7550                                   | 2         | 0.91%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA               | 2         | 0.91%   |
| Apple MacBookAir7,2                                   | 2         | 0.91%   |
| Acer Nitro AN515-52                                   | 2         | 0.91%   |
| UNOWHY Y13G010S4EI                                    | 1         | 0.45%   |
| Toshiba Satellite P775                                | 1         | 0.45%   |
| Timi A30                                              | 1         | 0.45%   |
| Samsung R425D/R525D                                   | 1         | 0.45%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.45%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.45%   |
| Quanta SWH                                            | 1         | 0.45%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro                   | 1         | 0.45%   |
| Notebook N141CU                                       | 1         | 0.45%   |
| Notebook N130BU                                       | 1         | 0.45%   |
| MSI MS-7E07                                           | 1         | 0.45%   |
| MSI MS-7C89                                           | 1         | 0.45%   |
| MSI MS-7C56                                           | 1         | 0.45%   |
| MSI MS-7B79                                           | 1         | 0.45%   |
| MSI MS-7B09                                           | 1         | 0.45%   |
| MSI MS-7A69                                           | 1         | 0.45%   |
| MSI MS-7A15                                           | 1         | 0.45%   |
| MSI MS-7982                                           | 1         | 0.45%   |
| MSI MS-7850                                           | 1         | 0.45%   |
| MSI Modern 15 A11M                                    | 1         | 0.45%   |
| MSI GP72 7RDX                                         | 1         | 0.45%   |
| MSI GF65 Thin 10SDR                                   | 1         | 0.45%   |
| MOTILE M141                                           | 1         | 0.45%   |
| Microsoft Surface Pro                                 | 1         | 0.45%   |
| MACHINIST X99-MR9D PLUS V1.0                          | 1         | 0.45%   |
| LG 17Z990-R.AAC9U1                                    | 1         | 0.45%   |
| Lenovo ThinkPad W520 4284W2U                          | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 20        | 9.09%   |
| Lenovo IdeaPad                  | 11        | 5%      |
| Acer Aspire                     | 11        | 5%      |
| Dell Inspiron                   | 8         | 3.64%   |
| Dell Precision                  | 7         | 3.18%   |
| HP Laptop                       | 6         | 2.73%   |
| Dell Latitude                   | 5         | 2.27%   |
| ASUS ROG                        | 5         | 2.27%   |
| ASUS VivoBook                   | 4         | 1.82%   |
| MSI MS-7A38                     | 3         | 1.36%   |
| HP 250                          | 3         | 1.36%   |
| HP 15                           | 3         | 1.36%   |
| Gigabyte X570                   | 3         | 1.36%   |
| ASUS TUF                        | 3         | 1.36%   |
| ASUS PRIME                      | 3         | 1.36%   |
| ASUS ASUS                       | 3         | 1.36%   |
| Acer Nitro                      | 3         | 1.36%   |
| Timi RedmiBook                  | 2         | 0.91%   |
| MSI MS-7C37                     | 2         | 0.91%   |
| MSI MS-7C02                     | 2         | 0.91%   |
| Lenovo IdeaPadFlex              | 2         | 0.91%   |
| HP ProBook                      | 2         | 0.91%   |
| HP Pavilion                     | 2         | 0.91%   |
| HP 255                          | 2         | 0.91%   |
| GPD P2                          | 2         | 0.91%   |
| Gigabyte 970A-DS3P              | 2         | 0.91%   |
| Dell OptiPlex                   | 2         | 0.91%   |
| Apple MacBookAir7               | 2         | 0.91%   |
| UNOWHY Y13G010S4EI              | 1         | 0.45%   |
| Toshiba Satellite               | 1         | 0.45%   |
| Timi A30                        | 1         | 0.45%   |
| Samsung R425D                   | 1         | 0.45%   |
| Samsung 350V5C                  | 1         | 0.45%   |
| Samsung 300E5EV                 | 1         | 0.45%   |
| Quanta SWH                      | 1         | 0.45%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.45%   |
| Notebook N141CU                 | 1         | 0.45%   |
| Notebook N130BU                 | 1         | 0.45%   |
| MSI MS-7E07                     | 1         | 0.45%   |
| MSI MS-7C89                     | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 42        | 19.09%  |
| 2019 | 28        | 12.73%  |
| 2018 | 24        | 10.91%  |
| 2017 | 17        | 7.73%   |
| 2013 | 16        | 7.27%   |
| 2012 | 16        | 7.27%   |
| 2011 | 15        | 6.82%   |
| 2021 | 14        | 6.36%   |
| 2015 | 12        | 5.45%   |
| 2014 | 11        | 5%      |
| 2022 | 8         | 3.64%   |
| 2016 | 8         | 3.64%   |
| 2010 | 5         | 2.27%   |
| 2008 | 2         | 0.91%   |
| 2009 | 1         | 0.45%   |
| 2007 | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 146       | 66.36%  |
| Desktop     | 70        | 31.82%  |
| Convertible | 2         | 0.91%   |
| Tablet      | 1         | 0.45%   |
| Mini pc     | 1         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 218       | 99.09%  |
| Enabled  | 2         | 0.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 218       | 99.09%  |
| Yes  | 2         | 0.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 56        | 25.23%  |
| 8.01-16.0   | 50        | 22.52%  |
| 4.01-8.0    | 48        | 21.62%  |
| 3.01-4.0    | 28        | 12.61%  |
| 32.01-64.0  | 20        | 9.01%   |
| 64.01-256.0 | 11        | 4.95%   |
| 1.01-2.0    | 6         | 2.7%    |
| 24.01-32.0  | 3         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 59        | 24.08%  |
| 4.01-8.0   | 57        | 23.27%  |
| 1.01-2.0   | 55        | 22.45%  |
| 3.01-4.0   | 38        | 15.51%  |
| 0.51-1.0   | 19        | 7.76%   |
| 8.01-16.0  | 10        | 4.08%   |
| 0.01-0.5   | 4         | 1.63%   |
| 16.01-24.0 | 3         | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 132       | 58.93%  |
| 2      | 56        | 25%     |
| 3      | 23        | 10.27%  |
| 4      | 6         | 2.68%   |
| 6      | 4         | 1.79%   |
| 8      | 2         | 0.89%   |
| 7      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 75.45%  |
| Yes       | 54        | 24.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 82.27%  |
| No        | 39        | 17.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 82.27%  |
| No        | 39        | 17.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 69.37%  |
| No        | 68        | 30.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 41        | 18.47%  |
| Russia          | 23        | 10.36%  |
| Germany         | 19        | 8.56%   |
| France          | 12        | 5.41%   |
| Brazil          | 12        | 5.41%   |
| India           | 8         | 3.6%    |
| UK              | 7         | 3.15%   |
| Turkey          | 6         | 2.7%    |
| Poland          | 6         | 2.7%    |
| Canada          | 6         | 2.7%    |
| Switzerland     | 5         | 2.25%   |
| Italy           | 5         | 2.25%   |
| Bulgaria        | 5         | 2.25%   |
| Ukraine         | 4         | 1.8%    |
| Spain           | 4         | 1.8%    |
| Romania         | 4         | 1.8%    |
| Netherlands     | 4         | 1.8%    |
| Indonesia       | 4         | 1.8%    |
| Greece          | 4         | 1.8%    |
| Finland         | 3         | 1.35%   |
| Australia       | 3         | 1.35%   |
| Argentina       | 3         | 1.35%   |
| Portugal        | 2         | 0.9%    |
| Pakistan        | 2         | 0.9%    |
| Lithuania       | 2         | 0.9%    |
| Japan           | 2         | 0.9%    |
| Iran            | 2         | 0.9%    |
| Guatemala       | 2         | 0.9%    |
| Czechia         | 2         | 0.9%    |
| Bangladesh      | 2         | 0.9%    |
| Vietnam         | 1         | 0.45%   |
| Uzbekistan      | 1         | 0.45%   |
| Sweden          | 1         | 0.45%   |
| Slovenia        | 1         | 0.45%   |
| Slovakia        | 1         | 0.45%   |
| Peru            | 1         | 0.45%   |
| North Macedonia | 1         | 0.45%   |
| Mexico          | 1         | 0.45%   |
| Israel          | 1         | 0.45%   |
| Hong Kong       | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 6         | 2.59%   |
| Moscow            | 4         | 1.72%   |
| Frankfurt am Main | 4         | 1.72%   |
| St Petersburg     | 3         | 1.29%   |
| Sofia             | 3         | 1.29%   |
| Los Angeles       | 3         | 1.29%   |
| Jakarta           | 3         | 1.29%   |
| Dnipro            | 3         | 1.29%   |
| Charlotte         | 3         | 1.29%   |
| Ankara            | 3         | 1.29%   |
| Vilnius           | 2         | 0.86%   |
| Vancouver         | 2         | 0.86%   |
| Toronto           | 2         | 0.86%   |
| Sorocaba          | 2         | 0.86%   |
| Snohomish         | 2         | 0.86%   |
| San Ramon         | 2         | 0.86%   |
| Samara            | 2         | 0.86%   |
| Rio de Janeiro    | 2         | 0.86%   |
| Prague            | 2         | 0.86%   |
| Omaha             | 2         | 0.86%   |
| Neuchatel         | 2         | 0.86%   |
| Mira              | 2         | 0.86%   |
| Milton            | 2         | 0.86%   |
| Kłodzko          | 2         | 0.86%   |
| Iasi              | 2         | 0.86%   |
| Helsinki          | 2         | 0.86%   |
| Guatemala City    | 2         | 0.86%   |
| Brisbane          | 2         | 0.86%   |
| Bern              | 2         | 0.86%   |
| Athens            | 2         | 0.86%   |
| Amsterdam         | 2         | 0.86%   |
| Zurich            | 1         | 0.43%   |
| Zaporizhzhya      | 1         | 0.43%   |
| Zagreb            | 1         | 0.43%   |
| Woodbridge        | 1         | 0.43%   |
| Wigan             | 1         | 0.43%   |
| Wettringen        | 1         | 0.43%   |
| Wem               | 1         | 0.43%   |
| Warsaw            | 1         | 0.43%   |
| Vladivostok       | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 57        | 77     | 16.57%  |
| WDC                          | 46        | 74     | 13.37%  |
| Seagate                      | 42        | 50     | 12.21%  |
| Toshiba                      | 23        | 24     | 6.69%   |
| Kingston                     | 22        | 24     | 6.4%    |
| Crucial                      | 17        | 25     | 4.94%   |
| SanDisk                      | 16        | 19     | 4.65%   |
| Intel                        | 12        | 17     | 3.49%   |
| SK hynix                     | 9         | 15     | 2.62%   |
| HGST                         | 9         | 10     | 2.62%   |
| Phison Electronics           | 8         | 14     | 2.33%   |
| Hitachi                      | 8         | 9      | 2.33%   |
| China                        | 6         | 7      | 1.74%   |
| A-DATA Technology            | 5         | 5      | 1.45%   |
| Unknown                      | 4         | 4      | 1.16%   |
| Micron Technology            | 4         | 4      | 1.16%   |
| JMicron Technology           | 3         | 3      | 0.87%   |
| Apple                        | 3         | 4      | 0.87%   |
| WALRAM                       | 2         | 2      | 0.58%   |
| SPCC                         | 2         | 2      | 0.58%   |
| Solid State Storage          | 2         | 2      | 0.58%   |
| Silicon Motion               | 2         | 2      | 0.58%   |
| PNY                          | 2         | 2      | 0.58%   |
| Phison                       | 2         | 2      | 0.58%   |
| Micron/Crucial Technology    | 2         | 2      | 0.58%   |
| Maxtor                       | 2         | 2      | 0.58%   |
| LITEON                       | 2         | 2      | 0.58%   |
| Linux                        | 2         | 2      | 0.58%   |
| Hewlett-Packard              | 2         | 2      | 0.58%   |
| Corsair                      | 2         | 2      | 0.58%   |
| Unknown                      | 2         | 4      | 0.58%   |
| XUM                          | 1         | 1      | 0.29%   |
| USB3.0                       | 1         | 1      | 0.29%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.29%   |
| Union Memory                 | 1         | 1      | 0.29%   |
| TS512GMT                     | 1         | 5      | 0.29%   |
| Transcend                    | 1         | 1      | 0.29%   |
| Timetec                      | 1         | 2      | 0.29%   |
| SPCC Sol                     | 1         | 1      | 0.29%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 9         | 2.39%   |
| Toshiba DT01ACA100 1TB                            | 5         | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB                    | 5         | 1.33%   |
| Crucial CT240BX500SSD1 240GB                      | 5         | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 4         | 1.06%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                | 4         | 1.06%   |
| SanDisk NVMe SSD Drive 512GB                      | 4         | 1.06%   |
| Samsung SSD 860 EVO 250GB                         | 4         | 1.06%   |
| Kingston SA400S37240G 240GB SSD                   | 4         | 1.06%   |
| Crucial CT1000MX500SSD1 1TB                       | 4         | 1.06%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3         | 0.8%    |
| Toshiba MQ01ABF050 500GB                          | 3         | 0.8%    |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 0.8%    |
| Seagate ST3500418AS 500GB                         | 3         | 0.8%    |
| Seagate ST1000DM010-2EP102 1TB                    | 3         | 0.8%    |
| Samsung SSD 970 EVO 1TB                           | 3         | 0.8%    |
| Samsung NVMe SSD Drive 1TB                        | 3         | 0.8%    |
| Phison E12 NVMe Controller 1TB                    | 3         | 0.8%    |
| HGST HTS545050A7E680 500GB                        | 3         | 0.8%    |
| China SATA SSD 960GB                              | 3         | 0.8%    |
| WDC WD80EZAZ-11TDBA0 8TB                          | 2         | 0.53%   |
| WDC WD40EZRZ-00WN9B0 4TB                          | 2         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.53%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 2         | 0.53%   |
| WDC WD100EMAZ-00WJTA0 10TB                        | 2         | 0.53%   |
| WALRAM 240G                                       | 2         | 0.53%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 0.53%   |
| Toshiba MQ01ABD100 1TB                            | 2         | 0.53%   |
| SK hynix SC311 SATA 256GB SSD                     | 2         | 0.53%   |
| Seagate ST500DM002-1BD142 500GB                   | 2         | 0.53%   |
| SanDisk NVMe SSD Drive 500GB                      | 2         | 0.53%   |
| Samsung SSD 980 1TB                               | 2         | 0.53%   |
| Samsung SSD 870 EVO 250GB                         | 2         | 0.53%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.53%   |
| Samsung SSD 850 EVO 250GB                         | 2         | 0.53%   |
| Samsung SSD 840 EVO 250GB                         | 2         | 0.53%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD              | 2         | 0.53%   |
| Samsung MZNLH512HALU-00000 512GB SSD              | 2         | 0.53%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 2         | 0.53%   |
| Phison PCIe SSD 512GB                             | 2         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 50     | 33.6%   |
| WDC                 | 40        | 62     | 32%     |
| Toshiba             | 20        | 21     | 16%     |
| HGST                | 9         | 10     | 7.2%    |
| Hitachi             | 8         | 9      | 6.4%    |
| Maxtor              | 2         | 2      | 1.6%    |
| USB3.0              | 1         | 1      | 0.8%    |
| Unknown             | 1         | 1      | 0.8%    |
| Samsung Electronics | 1         | 1      | 0.8%    |
| JMicron Technology  | 1         | 1      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 29     | 22.43%  |
| Kingston            | 17        | 18     | 15.89%  |
| Crucial             | 17        | 25     | 15.89%  |
| WDC                 | 6         | 9      | 5.61%   |
| China               | 6         | 7      | 5.61%   |
| SanDisk             | 3         | 3      | 2.8%    |
| Intel               | 3         | 4      | 2.8%    |
| Apple               | 3         | 4      | 2.8%    |
| A-DATA Technology   | 3         | 3      | 2.8%    |
| SPCC                | 2         | 2      | 1.87%   |
| SK hynix            | 2         | 2      | 1.87%   |
| Micron Technology   | 2         | 2      | 1.87%   |
| Linux               | 2         | 2      | 1.87%   |
| XUM                 | 1         | 1      | 0.93%   |
| Toshiba             | 1         | 1      | 0.93%   |
| SPCC Sol            | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Plextor             | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| LITEON              | 1         | 1      | 0.93%   |
| LDLC                | 1         | 5      | 0.93%   |
| KingSpec            | 1         | 1      | 0.93%   |
| Intenso             | 1         | 1      | 0.93%   |
| Hewlett-Packard     | 1         | 1      | 0.93%   |
| GOODRAM             | 1         | 1      | 0.93%   |
| Dogfish             | 1         | 1      | 0.93%   |
| Biostar             | 1         | 1      | 0.93%   |
| AMD                 | 1         | 1      | 0.93%   |
| AGI                 | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 109       | 158    | 35.28%  |
| NVMe    | 95        | 142    | 30.74%  |
| SSD     | 95        | 131    | 30.74%  |
| Unknown | 7         | 14     | 2.27%   |
| MMC     | 3         | 3      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 285    | 59.63%  |
| NVMe | 94        | 141    | 34.81%  |
| SAS  | 12        | 19     | 4.44%   |
| MMC  | 3         | 3      | 1.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 152    | 52.58%  |
| 0.51-1.0   | 68        | 93     | 31.92%  |
| 1.01-2.0   | 16        | 18     | 7.51%   |
| 3.01-4.0   | 6         | 8      | 2.82%   |
| 4.01-10.0  | 6         | 13     | 2.82%   |
| 2.01-3.0   | 5         | 5      | 2.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 23.79%  |
| 251-500        | 50        | 22.03%  |
| 501-1000       | 32        | 14.1%   |
| 1001-2000      | 30        | 13.22%  |
| More than 3000 | 20        | 8.81%   |
| 2001-3000      | 14        | 6.17%   |
| Unknown        | 9         | 3.96%   |
| 51-100         | 8         | 3.52%   |
| 1-20           | 6         | 2.64%   |
| 21-50          | 4         | 1.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 55        | 23.21%  |
| 101-250        | 39        | 16.46%  |
| 251-500        | 28        | 11.81%  |
| 21-50          | 25        | 10.55%  |
| 501-1000       | 25        | 10.55%  |
| 51-100         | 24        | 10.13%  |
| 1001-2000      | 18        | 7.59%   |
| More than 3000 | 9         | 3.8%    |
| Unknown        | 9         | 3.8%    |
| 2001-3000      | 4         | 1.69%   |
| 0              | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 5.56%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 5.56%   |
| HGST HTS541010A9E680 1TB                         | 2         | 2      | 5.56%   |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 2.78%   |
| WDC WD5000AVCS-632DY1 500GB                      | 1         | 1      | 2.78%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 2.78%   |
| WDC WD3200BEKT-60F3T1 320GB                      | 1         | 1      | 2.78%   |
| WDC WD3200AAKX-00ERMA0 320GB                     | 1         | 1      | 2.78%   |
| WDC WD30EZRX-00DC0B0 3TB                         | 1         | 1      | 2.78%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 2.78%   |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 2.78%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.78%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 2.78%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 2.78%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.78%   |
| Seagate ST8000DM004-2CX188 8TB                   | 1         | 1      | 2.78%   |
| Seagate ST6000VN0033-2EE110 6TB                  | 1         | 1      | 2.78%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.78%   |
| Seagate ST2000DX002-2DV164 2TB                   | 1         | 1      | 2.78%   |
| Seagate ST2000DM006-2DM164 2TB                   | 1         | 1      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 2.78%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.78%   |
| Maxtor 6Y080M0 80GB                              | 1         | 1      | 2.78%   |
| LDLC SSD 120GB                                   | 1         | 3      | 2.78%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 2.78%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 2.78%   |
| Intel SSDSC2BW480A4 480GB                        | 1         | 2      | 2.78%   |
| Intel SSDPEKKW128G7 128GB                        | 1         | 1      | 2.78%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 2.78%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 2.78%   |
| Hewlett-Packard SSD EX900 250GB                  | 1         | 1      | 2.78%   |
| A-DATA Technology SU650 240GB SSD                | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 19.44%  |
| Toshiba             | 7         | 7      | 19.44%  |
| Seagate             | 7         | 7      | 19.44%  |
| HGST                | 4         | 4      | 11.11%  |
| Kingston            | 2         | 2      | 5.56%   |
| Intel               | 2         | 3      | 5.56%   |
| Hitachi             | 2         | 2      | 5.56%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| Maxtor              | 1         | 1      | 2.78%   |
| LDLC                | 1         | 3      | 2.78%   |
| Hewlett-Packard     | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 25%     |
| Toshiba | 7         | 7      | 25%     |
| Seagate | 7         | 7      | 25%     |
| HGST    | 4         | 4      | 14.29%  |
| Hitachi | 2         | 2      | 7.14%   |
| Maxtor  | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 28     | 77.14%  |
| SSD  | 6         | 9      | 17.14%  |
| NVMe | 2         | 2      | 5.71%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 123       | 225    | 49.4%   |
| Detected | 91        | 183    | 36.55%  |
| Malfunc  | 34        | 39     | 13.65%  |
| Fixed    | 1         | 1      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 126       | 42.42%  |
| AMD                            | 61        | 20.54%  |
| Samsung Electronics            | 37        | 12.46%  |
| SanDisk                        | 15        | 5.05%   |
| Phison Electronics             | 11        | 3.7%    |
| SK hynix                       | 7         | 2.36%   |
| Marvell Technology Group       | 6         | 2.02%   |
| Kingston Technology Company    | 5         | 1.68%   |
| Silicon Motion                 | 4         | 1.35%   |
| ASMedia Technology             | 4         | 1.35%   |
| Union Memory (Shenzhen)        | 3         | 1.01%   |
| ADATA Technology               | 3         | 1.01%   |
| Toshiba America Info Systems   | 2         | 0.67%   |
| Solid State Storage Technology | 2         | 0.67%   |
| Micron/Crucial Technology      | 2         | 0.67%   |
| Micron Technology              | 2         | 0.67%   |
| Shenzhen Longsys Electronics   | 1         | 0.34%   |
| Nvidia                         | 1         | 0.34%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.34%   |
| Lite-On Technology             | 1         | 0.34%   |
| Lenovo                         | 1         | 0.34%   |
| JMicron Technology             | 1         | 0.34%   |
| Broadcom / LSI                 | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 48        | 14.55%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 6.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 4.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 2.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.42%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 2.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 2.12%   |
| AMD 300 Series Chipset SATA Controller                                         | 7         | 2.12%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.82%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 5         | 1.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.21%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.21%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 3         | 0.91%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.91%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 0.91%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 3         | 0.91%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.91%   |
| Intel SSD 660P Series                                                          | 3         | 0.91%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 0.91%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 0.61%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.61%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.61%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 0.61%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 171       | 58.76%  |
| NVMe | 95        | 32.65%  |
| RAID | 14        | 4.81%   |
| IDE  | 10        | 3.44%   |
| SAS  | 1         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 147       | 66.82%  |
| AMD    | 73        | 33.18%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 1.81%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 1.81%   |
| AMD FX-8350 Eight-Core Processor              | 4         | 1.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.36%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.36%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 1.36%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 3         | 1.36%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.9%    |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.9%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.9%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.9%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.9%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i5-6600K CPU @ 3.50GHz             | 2         | 0.9%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.9%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5-10400F CPU @ 2.90GHz            | 2         | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.9%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.9%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.9%    |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.9%    |
| AMD Ryzen 7 1700 Eight-Core Processor         | 2         | 0.9%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 52        | 23.64%  |
| Intel Core i7           | 35        | 15.91%  |
| AMD Ryzen 7             | 21        | 9.55%   |
| AMD Ryzen 5             | 20        | 9.09%   |
| Other                   | 15        | 6.82%   |
| Intel Core i3           | 14        | 6.36%   |
| Intel Celeron           | 10        | 4.55%   |
| Intel Pentium           | 6         | 2.73%   |
| AMD Ryzen 3             | 6         | 2.73%   |
| AMD Ryzen 9             | 5         | 2.27%   |
| AMD FX                  | 5         | 2.27%   |
| Intel Core 2 Duo        | 4         | 1.82%   |
| Intel Xeon              | 3         | 1.36%   |
| Intel Core m3           | 3         | 1.36%   |
| AMD Athlon              | 3         | 1.36%   |
| AMD A10                 | 3         | 1.36%   |
| Intel Core i9           | 2         | 0.91%   |
| AMD Ryzen Threadripper  | 2         | 0.91%   |
| AMD A6                  | 2         | 0.91%   |
| Intel Pentium Silver    | 1         | 0.45%   |
| Intel Pentium Dual-Core | 1         | 0.45%   |
| Intel Atom              | 1         | 0.45%   |
| AMD Ryzen 7 PRO         | 1         | 0.45%   |
| AMD Ryzen 5 PRO         | 1         | 0.45%   |
| AMD Phenom II X4        | 1         | 0.45%   |
| AMD Phenom II           | 1         | 0.45%   |
| AMD E1                  | 1         | 0.45%   |
| AMD A4                  | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 77        | 35%     |
| 4      | 69        | 31.36%  |
| 6      | 31        | 14.09%  |
| 8      | 28        | 12.73%  |
| 12     | 6         | 2.73%   |
| 14     | 2         | 0.91%   |
| 10     | 2         | 0.91%   |
| 3      | 2         | 0.91%   |
| 32     | 1         | 0.45%   |
| 16     | 1         | 0.45%   |
| 1      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 220       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 168       | 76.36%  |
| 1      | 52        | 23.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 220       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 29.65%  |
| 0x206a7    | 12        | 5.31%   |
| 0x306a9    | 11        | 4.87%   |
| 0xa0652    | 6         | 2.65%   |
| 0x08701013 | 6         | 2.65%   |
| 0x08600106 | 6         | 2.65%   |
| 0x0800820d | 6         | 2.65%   |
| 0x806ec    | 5         | 2.21%   |
| 0x806e9    | 5         | 2.21%   |
| 0x806c1    | 5         | 2.21%   |
| 0x40651    | 5         | 2.21%   |
| 0x306d4    | 5         | 2.21%   |
| 0x906ed    | 4         | 1.77%   |
| 0x906e9    | 4         | 1.77%   |
| 0x806ea    | 4         | 1.77%   |
| 0x706e5    | 4         | 1.77%   |
| 0x706a1    | 4         | 1.77%   |
| 0x08701021 | 4         | 1.77%   |
| 0x08108109 | 4         | 1.77%   |
| 0x906ea    | 3         | 1.33%   |
| 0x506e3    | 3         | 1.33%   |
| 0x306c3    | 3         | 1.33%   |
| 0x1067a    | 3         | 1.33%   |
| 0x06000822 | 3         | 1.33%   |
| 0xa0655    | 2         | 0.88%   |
| 0x30678    | 2         | 0.88%   |
| 0x0a201016 | 2         | 0.88%   |
| 0x08608103 | 2         | 0.88%   |
| 0x08600103 | 2         | 0.88%   |
| 0x08108102 | 2         | 0.88%   |
| 0x08101007 | 2         | 0.88%   |
| 0x08001137 | 2         | 0.88%   |
| 0x06003106 | 2         | 0.88%   |
| 0x06000852 | 2         | 0.88%   |
| 0xa0653    | 1         | 0.44%   |
| 0x906a3    | 1         | 0.44%   |
| 0x806eb    | 1         | 0.44%   |
| 0x806d1    | 1         | 0.44%   |
| 0x806c2    | 1         | 0.44%   |
| 0x6fd      | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 17.73%  |
| Zen 2            | 22        | 10%     |
| Zen+             | 18        | 8.18%   |
| IvyBridge        | 18        | 8.18%   |
| SandyBridge      | 16        | 7.27%   |
| Haswell          | 11        | 5%      |
| CometLake        | 11        | 5%      |
| Zen              | 8         | 3.64%   |
| TigerLake        | 8         | 3.64%   |
| Broadwell        | 8         | 3.64%   |
| Zen 3            | 7         | 3.18%   |
| Skylake          | 6         | 2.73%   |
| Piledriver       | 6         | 2.73%   |
| Unknown          | 6         | 2.73%   |
| Silvermont       | 5         | 2.27%   |
| IceLake          | 5         | 2.27%   |
| Penryn           | 4         | 1.82%   |
| Goldmont plus    | 4         | 1.82%   |
| Alderlake Hybrid | 4         | 1.82%   |
| Westmere         | 3         | 1.36%   |
| Steamroller      | 3         | 1.36%   |
| K10              | 2         | 0.91%   |
| Puma             | 1         | 0.45%   |
| Jaguar           | 1         | 0.45%   |
| Goldmont         | 1         | 0.45%   |
| Excavator        | 1         | 0.45%   |
| Core             | 1         | 0.45%   |
| Bonnell          | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 117       | 45.17%  |
| AMD    | 79        | 30.5%   |
| Nvidia | 63        | 24.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 14        | 5.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 4.15%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 10        | 3.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 10        | 3.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 9         | 3.4%    |
| Intel UHD Graphics 620                                                    | 7         | 2.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 2.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 2.64%   |
| Intel HD Graphics 620                                                     | 6         | 2.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 2.26%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 6         | 2.26%   |
| Intel HD Graphics 5500                                                    | 5         | 1.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 1.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 4         | 1.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 1.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 1.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 1.51%   |
| AMD Lucienne                                                              | 4         | 1.51%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.13%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.13%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 3         | 1.13%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 2         | 0.75%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 0.75%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 2         | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 0.75%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 2         | 0.75%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.75%   |
| Intel UHD Graphics 615                                                    | 2         | 0.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 0.75%   |
| Intel HD Graphics 630                                                     | 2         | 0.75%   |
| Intel HD Graphics 6000                                                    | 2         | 0.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2         | 0.75%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 0.75%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 2         | 0.75%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 81        | 36.49%  |
| 1 x AMD        | 68        | 30.63%  |
| 1 x Nvidia     | 30        | 13.51%  |
| Intel + Nvidia | 30        | 13.51%  |
| 2 x AMD        | 5         | 2.25%   |
| Intel + AMD    | 4         | 1.8%    |
| AMD + Nvidia   | 3         | 1.35%   |
| 2 x Intel      | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 179       | 80.63%  |
| Proprietary | 42        | 18.92%  |
| Unknown     | 1         | 0.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 57.08%  |
| 1.01-2.0   | 24        | 10.62%  |
| 7.01-8.0   | 18        | 7.96%   |
| 3.01-4.0   | 16        | 7.08%   |
| 0.01-0.5   | 16        | 7.08%   |
| 0.51-1.0   | 12        | 5.31%   |
| 8.01-16.0  | 6         | 2.65%   |
| 5.01-6.0   | 4         | 1.77%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 12.31%  |
| Samsung Electronics     | 27        | 10.07%  |
| BOE                     | 27        | 10.07%  |
| LG Display              | 25        | 9.33%   |
| Chimei Innolux          | 25        | 9.33%   |
| Goldstar                | 14        | 5.22%   |
| Acer                    | 13        | 4.85%   |
| Philips                 | 10        | 3.73%   |
| Dell                    | 10        | 3.73%   |
| AOC                     | 9         | 3.36%   |
| ASUSTek Computer        | 8         | 2.99%   |
| BenQ                    | 7         | 2.61%   |
| Chi Mei Optoelectronics | 5         | 1.87%   |
| Lenovo                  | 4         | 1.49%   |
| Hewlett-Packard         | 4         | 1.49%   |
| Apple                   | 4         | 1.49%   |
| Ancor Communications    | 4         | 1.49%   |
| PANDA                   | 3         | 1.12%   |
| MSI                     | 3         | 1.12%   |
| InfoVision              | 3         | 1.12%   |
| ViewSonic               | 2         | 0.75%   |
| Unknown                 | 2         | 0.75%   |
| Sony                    | 2         | 0.75%   |
| Sharp                   | 2         | 0.75%   |
| Vestel Elektronik       | 1         | 0.37%   |
| Packard Bell            | 1         | 0.37%   |
| LGD                     | 1         | 0.37%   |
| LG Electronics          | 1         | 0.37%   |
| Lenovo Group Limited    | 1         | 0.37%   |
| KTC                     | 1         | 0.37%   |
| KDC                     | 1         | 0.37%   |
| Jean                    | 1         | 0.37%   |
| Iiyama                  | 1         | 0.37%   |
| Idek Iiyama             | 1         | 0.37%   |
| HVR                     | 1         | 0.37%   |
| HUAWEI                  | 1         | 0.37%   |
| HKC                     | 1         | 0.37%   |
| Hitachi                 | 1         | 0.37%   |
| GAOMON                  | 1         | 0.37%   |
| Envision Peripherals    | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 4         | 1.47%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                        | 3         | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 3         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.1%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 3         | 1.1%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 0.74%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 2         | 0.74%   |
| Philips PHL 245E1 PHLC20B 1920x1080 527x296mm 23.8-inch                   | 2         | 0.74%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.74%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.74%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.74%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch               | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.74%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.74%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 0.74%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.74%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 0.74%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                      | 2         | 0.74%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.74%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch              | 2         | 0.74%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 0.74%   |
| AOC 2200W AOC2200 1920x1080 476x268mm 21.5-inch                           | 2         | 0.74%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch     | 2         | 0.74%   |
| ViewSonic VA2256 Series VSC3136 1920x1080 476x268mm 21.5-inch             | 1         | 0.37%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                             | 1         | 0.37%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 1         | 0.37%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.37%   |
| Sony BW8 MS_9001 1200x1920                                                | 1         | 0.37%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.37%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.37%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch         | 1         | 0.37%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch         | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.37%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch        | 1         | 0.37%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.37%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch         | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 115       | 45.28%  |
| 1366x768 (WXGA)    | 55        | 21.65%  |
| 3840x2160 (4K)     | 22        | 8.66%   |
| 2560x1440 (QHD)    | 11        | 4.33%   |
| 1600x900 (HD+)     | 7         | 2.76%   |
| 2560x1600          | 5         | 1.97%   |
| 1440x900 (WXGA+)   | 5         | 1.97%   |
| 3440x1440          | 4         | 1.57%   |
| 1280x1024 (SXGA)   | 4         | 1.57%   |
| 2560x1080          | 3         | 1.18%   |
| Unknown            | 3         | 1.18%   |
| 3840x1080          | 2         | 0.79%   |
| 2288x1287          | 2         | 0.79%   |
| 1920x1200 (WUXGA)  | 2         | 0.79%   |
| 1680x1050 (WSXGA+) | 2         | 0.79%   |
| 1360x768           | 2         | 0.79%   |
| 4480x1080          | 1         | 0.39%   |
| 3600x1080          | 1         | 0.39%   |
| 3456x2160          | 1         | 0.39%   |
| 3072x1920          | 1         | 0.39%   |
| 2736x1824          | 1         | 0.39%   |
| 2160x1440          | 1         | 0.39%   |
| 2160x1200          | 1         | 0.39%   |
| 1280x960           | 1         | 0.39%   |
| 1280x800 (WXGA)    | 1         | 0.39%   |
| 1024x768 (XGA)     | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 77        | 29.28%  |
| 14      | 25        | 9.51%   |
| 13      | 25        | 9.51%   |
| 27      | 22        | 8.37%   |
| 21      | 19        | 7.22%   |
| 24      | 18        | 6.84%   |
| 23      | 18        | 6.84%   |
| 17      | 11        | 4.18%   |
| 34      | 7         | 2.66%   |
| Unknown | 6         | 2.28%   |
| 19      | 5         | 1.9%    |
| 84      | 4         | 1.52%   |
| 31      | 4         | 1.52%   |
| 16      | 4         | 1.52%   |
| 11      | 4         | 1.52%   |
| 142     | 2         | 0.76%   |
| 32      | 2         | 0.76%   |
| 20      | 2         | 0.76%   |
| 12      | 2         | 0.76%   |
| 72      | 1         | 0.38%   |
| 52      | 1         | 0.38%   |
| 48      | 1         | 0.38%   |
| 28      | 1         | 0.38%   |
| 18      | 1         | 0.38%   |
| 8       | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 119       | 45.77%  |
| 501-600        | 51        | 19.62%  |
| 401-500        | 24        | 9.23%   |
| 351-400        | 17        | 6.54%   |
| 201-300        | 14        | 5.38%   |
| 601-700        | 10        | 3.85%   |
| 701-800        | 9         | 3.46%   |
| Unknown        | 6         | 2.31%   |
| 1501-2000      | 5         | 1.92%   |
| More than 2000 | 2         | 0.77%   |
| 1001-1500      | 2         | 0.77%   |
| 101-200        | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 187       | 81.3%   |
| 16/10   | 18        | 7.83%   |
| 21/9    | 7         | 3.04%   |
| 5/4     | 5         | 2.17%   |
| Unknown | 5         | 2.17%   |
| 4/3     | 2         | 0.87%   |
| 3/2     | 2         | 0.87%   |
| 1.00    | 2         | 0.87%   |
| 32/9    | 1         | 0.43%   |
| 0.62    | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 29.77%  |
| 201-250        | 49        | 18.7%   |
| 81-90          | 41        | 15.65%  |
| 301-350        | 22        | 8.4%    |
| 351-500        | 14        | 5.34%   |
| 71-80          | 9         | 3.44%   |
| 151-200        | 9         | 3.44%   |
| More than 1000 | 8         | 3.05%   |
| 121-130        | 8         | 3.05%   |
| Unknown        | 6         | 2.29%   |
| 51-60          | 4         | 1.53%   |
| 251-300        | 4         | 1.53%   |
| 141-150        | 3         | 1.15%   |
| 131-140        | 2         | 0.76%   |
| 111-120        | 2         | 0.76%   |
| 61-70          | 1         | 0.38%   |
| 1-40           | 1         | 0.38%   |
| 501-1000       | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 84        | 33.6%   |
| 101-120       | 71        | 28.4%   |
| 51-100        | 67        | 26.8%   |
| 161-240       | 14        | 5.6%    |
| Unknown       | 6         | 2.4%    |
| More than 240 | 4         | 1.6%    |
| 1-50          | 4         | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 173       | 76.89%  |
| 2     | 47        | 20.89%  |
| 3     | 3         | 1.33%   |
| 4     | 1         | 0.44%   |
| 0     | 1         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 140       | 42.42%  |
| Intel                                 | 108       | 32.73%  |
| Qualcomm Atheros                      | 28        | 8.48%   |
| Broadcom                              | 13        | 3.94%   |
| TP-Link                               | 4         | 1.21%   |
| Broadcom Limited                      | 4         | 1.21%   |
| Ralink Technology                     | 3         | 0.91%   |
| MediaTek                              | 3         | 0.91%   |
| D-Link System                         | 3         | 0.91%   |
| Xiaomi                                | 2         | 0.61%   |
| Samsung Electronics                   | 2         | 0.61%   |
| Ralink                                | 2         | 0.61%   |
| Qualcomm                              | 2         | 0.61%   |
| Marvell Technology Group              | 2         | 0.61%   |
| Aquantia                              | 2         | 0.61%   |
| Sierra Wireless                       | 1         | 0.3%    |
| Qualcomm Atheros Communications       | 1         | 0.3%    |
| OPPO Electronics                      | 1         | 0.3%    |
| Microsoft                             | 1         | 0.3%    |
| Linksys                               | 1         | 0.3%    |
| Lenovo                                | 1         | 0.3%    |
| Huawei Technologies                   | 1         | 0.3%    |
| Google                                | 1         | 0.3%    |
| DisplayLink                           | 1         | 0.3%    |
| ASIX Electronics                      | 1         | 0.3%    |
| Apple                                 | 1         | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 94        | 23.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 18        | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 12        | 2.99%   |
| Intel Wi-Fi 6 AX200                                                  | 11        | 2.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 10        | 2.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 10        | 2.49%   |
| Intel Wireless 8265 / 8275                                           | 10        | 2.49%   |
| Intel I211 Gigabit Network Connection                                | 10        | 2.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 1.5%    |
| Intel Wi-Fi 6 AX201                                                  | 6         | 1.5%    |
| Intel Wireless 7265                                                  | 5         | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 5         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 1%      |
| Intel Ethernet Connection (4) I219-LM                                | 4         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                        | 4         | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 3         | 0.75%   |
| Realtek 802.11ac NIC                                                 | 3         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 3         | 0.75%   |
| Intel Wireless 7260                                                  | 3         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                 | 3         | 0.75%   |
| Intel Ethernet Connection (11) I219-LM                               | 3         | 0.75%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 0.75%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 0.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 90        | 47.62%  |
| Realtek Semiconductor                 | 40        | 21.16%  |
| Qualcomm Atheros                      | 24        | 12.7%   |
| Broadcom                              | 12        | 6.35%   |
| TP-Link                               | 4         | 2.12%   |
| Broadcom Limited                      | 4         | 2.12%   |
| Ralink Technology                     | 3         | 1.59%   |
| MediaTek                              | 3         | 1.59%   |
| Ralink                                | 2         | 1.06%   |
| Sierra Wireless                       | 1         | 0.53%   |
| Qualcomm Atheros Communications       | 1         | 0.53%   |
| Qualcomm                              | 1         | 0.53%   |
| Microsoft                             | 1         | 0.53%   |
| Marvell Technology Group              | 1         | 0.53%   |
| D-Link System                         | 1         | 0.53%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 11        | 5.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 5.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 10        | 5.21%   |
| Intel Wireless 8265 / 8275                                           | 10        | 5.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 3.65%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 3.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 3.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 6         | 3.13%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 3.13%   |
| Intel Wireless 7265                                                  | 5         | 2.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 5         | 2.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 2.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 5         | 2.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                        | 4         | 2.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.56%   |
| Realtek 802.11ac NIC                                                 | 3         | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 3         | 1.56%   |
| Intel Wireless 7260                                                  | 3         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.56%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 1.56%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 1.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 1.04%   |
| Ralink RT5370 Wireless Adapter                                       | 2         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.04%   |
| Intel Wireless-AC 9260                                               | 2         | 1.04%   |
| Intel Wireless 3165                                                  | 2         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.04%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 1.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 123       | 61.19%  |
| Intel                    | 50        | 24.88%  |
| Qualcomm Atheros         | 8         | 3.98%   |
| Xiaomi                   | 2         | 1%      |
| Samsung Electronics      | 2         | 1%      |
| D-Link System            | 2         | 1%      |
| Broadcom                 | 2         | 1%      |
| Aquantia                 | 2         | 1%      |
| Qualcomm                 | 1         | 0.5%    |
| OPPO Electronics         | 1         | 0.5%    |
| Marvell Technology Group | 1         | 0.5%    |
| Linksys                  | 1         | 0.5%    |
| Lenovo                   | 1         | 0.5%    |
| Huawei Technologies      | 1         | 0.5%    |
| Google                   | 1         | 0.5%    |
| DisplayLink              | 1         | 0.5%    |
| ASIX Electronics         | 1         | 0.5%    |
| Apple                    | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 44.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 8.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 5.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 4.78%   |
| Intel I211 Gigabit Network Connection                             | 10        | 4.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.91%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.96%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.96%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.48%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.48%   |
| Qualcomm A0001                                                    | 1         | 0.48%   |
| OPPO RMX2027                                                      | 1         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.48%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.48%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.48%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.48%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.48%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.48%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.48%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 182       | 50.14%  |
| Ethernet | 181       | 49.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 62.61%  |
| Ethernet | 86        | 37.39%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 127       | 57.47%  |
| 1     | 84        | 38.01%  |
| 3     | 6         | 2.71%   |
| 4     | 2         | 0.9%    |
| 0     | 2         | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 184       | 81.78%  |
| Yes  | 41        | 18.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 47.77%  |
| Realtek Semiconductor           | 23        | 14.65%  |
| Broadcom                        | 11        | 7.01%   |
| Cambridge Silicon Radio         | 9         | 5.73%   |
| Qualcomm Atheros Communications | 8         | 5.1%    |
| IMC Networks                    | 8         | 5.1%    |
| Lite-On Technology              | 5         | 3.18%   |
| ASUSTek Computer                | 4         | 2.55%   |
| Apple                           | 4         | 2.55%   |
| Foxconn / Hon Hai               | 3         | 1.91%   |
| Realtek                         | 2         | 1.27%   |
| Ralink                          | 1         | 0.64%   |
| MediaTek                        | 1         | 0.64%   |
| Marvell Semiconductor           | 1         | 0.64%   |
| HTC (High Tech Computer)        | 1         | 0.64%   |
| Dynex                           | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 20        | 12.66%  |
| Realtek Bluetooth Radio                                              | 17        | 10.76%  |
| Intel AX201 Bluetooth                                                | 17        | 10.76%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 11        | 6.96%   |
| Intel AX200 Bluetooth                                                | 11        | 6.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 9         | 5.7%    |
| Qualcomm Atheros  Bluetooth Device                                   | 5         | 3.16%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 5         | 3.16%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 2.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 4         | 2.53%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4         | 2.53%   |
| Intel AX210 Bluetooth                                                | 4         | 2.53%   |
| IMC Networks Bluetooth Radio                                         | 4         | 2.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 1.9%    |
| Realtek Bluetooth Radio                                              | 2         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.27%   |
| Intel Bluetooth Device                                               | 2         | 1.27%   |
| IMC Networks Wireless_Device                                         | 2         | 1.27%   |
| IMC Networks Bluetooth Device                                        | 2         | 1.27%   |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 2         | 1.27%   |
| Apple Bluetooth USB Host Controller                                  | 2         | 1.27%   |
| Apple Bluetooth Host Controller                                      | 2         | 1.27%   |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.63%   |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.63%   |
| Ralink RT3290 Bluetooth                                              | 1         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 0.63%   |
| MediaTek Wireless_Device                                             | 1         | 0.63%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 0.63%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1         | 0.63%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1         | 0.63%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1         | 0.63%   |
| Broadcom HP Portable Valentine                                       | 1         | 0.63%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.63%   |
| Broadcom BCM2070 Bluetooth Device                                    | 1         | 0.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 0.63%   |
| ASUS BT-270 Bluetooth Adapter                                        | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 145       | 43.28%  |
| AMD                                             | 87        | 25.97%  |
| Nvidia                                          | 50        | 14.93%  |
| C-Media Electronics                             | 12        | 3.58%   |
| Realtek Semiconductor                           | 5         | 1.49%   |
| Creative Labs                                   | 5         | 1.49%   |
| Logitech                                        | 3         | 0.9%    |
| Generalplus Technology                          | 2         | 0.6%    |
| Creative Technology                             | 2         | 0.6%    |
| Corsair                                         | 2         | 0.6%    |
| Texas Instruments                               | 1         | 0.3%    |
| TC Electronic                                   | 1         | 0.3%    |
| SteelSeries ApS                                 | 1         | 0.3%    |
| Shure                                           | 1         | 0.3%    |
| Razer USA                                       | 1         | 0.3%    |
| PreSonus Audio Electronics                      | 1         | 0.3%    |
| Plantronics                                     | 1         | 0.3%    |
| Native Instruments                              | 1         | 0.3%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.3%    |
| Lenovo                                          | 1         | 0.3%    |
| JMTek                                           | 1         | 0.3%    |
| Hewlett-Packard                                 | 1         | 0.3%    |
| Harman                                          | 1         | 0.3%    |
| GN Netcom                                       | 1         | 0.3%    |
| Focusrite-Novation                              | 1         | 0.3%    |
| EVGA                                            | 1         | 0.3%    |
| DSEA A/S                                        | 1         | 0.3%    |
| Blue Microphones                                | 1         | 0.3%    |
| AudioQuest                                      | 1         | 0.3%    |
| ASUSTek Computer                                | 1         | 0.3%    |
| Arylic                                          | 1         | 0.3%    |
| Apple                                           | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 30        | 7.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 19        | 4.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 4.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 3.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 3.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13        | 3.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 2.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 2.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 1.94%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 1.7%    |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.7%    |
| AMD Navi 10 HDMI Audio                                                     | 7         | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.46%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.46%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.46%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.21%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 1.21%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.21%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5         | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.97%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 0.97%   |
| C-Media Electronics USB Audio Device                                       | 4         | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.73%   |
| Intel Comet Lake PCH-V cAVS                                                | 3         | 0.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 52        | 23.11%  |
| SK hynix            | 39        | 17.33%  |
| Kingston            | 28        | 12.44%  |
| Micron Technology   | 16        | 7.11%   |
| Corsair             | 16        | 7.11%   |
| Unknown             | 12        | 5.33%   |
| G.Skill             | 12        | 5.33%   |
| Crucial             | 9         | 4%      |
| A-DATA Technology   | 7         | 3.11%   |
| Patriot             | 5         | 2.22%   |
| Unknown             | 4         | 1.78%   |
| Team                | 3         | 1.33%   |
| Smart               | 3         | 1.33%   |
| Silicon Power       | 3         | 1.33%   |
| Ramaxel Technology  | 3         | 1.33%   |
| Nanya Technology    | 3         | 1.33%   |
| Unknown (ABCD)      | 2         | 0.89%   |
| AMD                 | 2         | 0.89%   |
| Transcend           | 1         | 0.44%   |
| Smart Brazil        | 1         | 0.44%   |
| Golden Empire       | 1         | 0.44%   |
| Elpida              | 1         | 0.44%   |
| Avant               | 1         | 0.44%   |
| ASint Technology    | 1         | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 2.12%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.69%   |
| Unknown                                                          | 4         | 1.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.27%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 1.27%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 1.27%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 3         | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.85%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 0.85%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.85%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.85%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s              | 2         | 0.85%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s            | 2         | 0.85%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s             | 2         | 0.85%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s         | 2         | 0.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.85%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 2         | 0.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                          | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 103       | 55.98%  |
| DDR3    | 61        | 33.15%  |
| LPDDR4  | 4         | 2.17%   |
| LPDDR3  | 4         | 2.17%   |
| DDR5    | 4         | 2.17%   |
| SDRAM   | 3         | 1.63%   |
| Unknown | 3         | 1.63%   |
| DDR2    | 2         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 60%     |
| DIMM         | 58        | 31.35%  |
| Row Of Chips | 14        | 7.57%   |
| Chip         | 1         | 0.54%   |
| Unknown      | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 74        | 35.75%  |
| 4096  | 69        | 33.33%  |
| 16384 | 34        | 16.43%  |
| 2048  | 16        | 7.73%   |
| 32768 | 12        | 5.8%    |
| 1024  | 2         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 25%     |
| 3200    | 43        | 21.5%   |
| 2667    | 31        | 15.5%   |
| 2400    | 15        | 7.5%    |
| 1333    | 11        | 5.5%    |
| 3600    | 6         | 3%      |
| 2133    | 5         | 2.5%    |
| 3733    | 4         | 2%      |
| 1334    | 4         | 2%      |
| 2933    | 3         | 1.5%    |
| 4800    | 2         | 1%      |
| 4199    | 2         | 1%      |
| 3666    | 2         | 1%      |
| 3533    | 2         | 1%      |
| 3400    | 2         | 1%      |
| 3266    | 2         | 1%      |
| 3000    | 2         | 1%      |
| 800     | 2         | 1%      |
| 6000    | 1         | 0.5%    |
| 4802    | 1         | 0.5%    |
| 4267    | 1         | 0.5%    |
| 4133    | 1         | 0.5%    |
| 2800    | 1         | 0.5%    |
| 2481    | 1         | 0.5%    |
| 2465    | 1         | 0.5%    |
| 1328    | 1         | 0.5%    |
| 1067    | 1         | 0.5%    |
| 1066    | 1         | 0.5%    |
| 667     | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Ricoh               | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 1         | 20%     |
| Ricoh SP 210SU                | 1         | 20%     |
| HP Officejet Pro L7400        | 1         | 20%     |
| Brother HL-L3270CDW series    | 1         | 20%     |
| Brother HL-2030 Laser Printer | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 19.86%  |
| IMC Networks                           | 16        | 10.96%  |
| Realtek Semiconductor                  | 12        | 8.22%   |
| Quanta                                 | 12        | 8.22%   |
| Bison Electronics                      | 11        | 7.53%   |
| Microdia                               | 10        | 6.85%   |
| Suyin                                  | 6         | 4.11%   |
| Logitech                               | 6         | 4.11%   |
| Syntek                                 | 5         | 3.42%   |
| Sunplus Innovation Technology          | 5         | 3.42%   |
| Alcor Micro                            | 5         | 3.42%   |
| Sonix Technology                       | 4         | 2.74%   |
| Silicon Motion                         | 4         | 2.74%   |
| Luxvisions Innotech Limited            | 4         | 2.74%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.05%   |
| Creative Technology                    | 2         | 1.37%   |
| Acer                                   | 2         | 1.37%   |
| WaveRider Communications               | 1         | 0.68%   |
| Microsoft                              | 1         | 0.68%   |
| Lite-On Technology                     | 1         | 0.68%   |
| LG Electronics                         | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| KYE Systems (Mouse Systems)            | 1         | 0.68%   |
| GEMBIRD                                | 1         | 0.68%   |
| Cubeternet                             | 1         | 0.68%   |
| ARC International                      | 1         | 0.68%   |
| Apple                                  | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 9         | 6.16%   |
| Chicony HD WebCam                                   | 6         | 4.11%   |
| Chicony integrated camera                           | 5         | 3.42%   |
| Bison Integrated Camera                             | 5         | 3.42%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 2.74%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.74%   |
| Syntek EasyCamera                                   | 3         | 2.05%   |
| Quanta HP TrueVision HD Camera                      | 3         | 2.05%   |
| Microdia Integrated_Webcam_HD                       | 3         | 2.05%   |
| Microdia Integrated Webcam                          | 3         | 2.05%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 2.05%   |
| Syntek Integrated Camera                            | 2         | 1.37%   |
| Suyin HP Webcam                                     | 2         | 1.37%   |
| Sunplus HD WebCam                                   | 2         | 1.37%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 1.37%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 1.37%   |
| Realtek HD WebCam                                   | 2         | 1.37%   |
| Quanta VGA WebCam                                   | 2         | 1.37%   |
| Quanta HP Webcam                                    | 2         | 1.37%   |
| Quanta HD Webcam                                    | 2         | 1.37%   |
| Logitech Webcam C270                                | 2         | 1.37%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.37%   |
| Chicony USB2.0 Camera                               | 2         | 1.37%   |
| Chicony thinkpad t430s camera                       | 2         | 1.37%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.37%   |
| Bison Lenovo EasyCamera                             | 2         | 1.37%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 1.37%   |
| WaveRider USB 2.0 Camera                            | 1         | 0.68%   |
| Suyin USB Webcam                                    | 1         | 0.68%   |
| Suyin NEC HD WebCam                                 | 1         | 0.68%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.68%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.68%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.68%   |
| Sunplus Aukey-PC-LM1E Camera                        | 1         | 0.68%   |
| Silicon Motion WebCam SCB-0355N                     | 1         | 0.68%   |
| Silicon Motion WebCam SC-10HDD12636N                | 1         | 0.68%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.68%   |
| Realtek Integrated Webcam                           | 1         | 0.68%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| Alcor Micro | 2         | 22.22%  |
| Lenovo      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 22.22%  |
| Broadcom 58200                                                               | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 22.22%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 163       | 73.09%  |
| 1     | 52        | 23.32%  |
| 2     | 6         | 2.69%   |
| 3     | 2         | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 23.19%  |
| Graphics card            | 9         | 13.04%  |
| Net/wireless             | 8         | 11.59%  |
| Chipcard                 | 8         | 11.59%  |
| Multimedia controller    | 6         | 8.7%    |
| Communication controller | 5         | 7.25%   |
| Camera                   | 5         | 7.25%   |
| Bluetooth                | 4         | 5.8%    |
| Unassigned class         | 2         | 2.9%    |
| Storage                  | 2         | 2.9%    |
| Net/ethernet             | 2         | 2.9%    |
| Network                  | 1         | 1.45%   |
| Dvb card                 | 1         | 1.45%   |

