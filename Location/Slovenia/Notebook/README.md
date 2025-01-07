Linux in Slovenia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovenia.

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

Total: 408

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [d99505e615](https://linux-hardware.org/?probe=d99505e615) | Dec 31, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [ff70c71f76](https://linux-hardware.org/?probe=ff70c71f76) | Dec 26, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8e7f60e511](https://linux-hardware.org/?probe=8e7f60e511) | Dec 23, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b7da8ab4d5](https://linux-hardware.org/?probe=b7da8ab4d5) | Dec 23, 2024 |
| TUXEDO        | Aura 15 Gen1                | [c4af5fafe4](https://linux-hardware.org/?probe=c4af5fafe4) | Dec 21, 2024 |
| Clevo         | W35_37ET                    | [8c4d3d1caa](https://linux-hardware.org/?probe=8c4d3d1caa) | Nov 30, 2024 |
| Clevo         | W35_37ET                    | [4b7ce97c36](https://linux-hardware.org/?probe=4b7ce97c36) | Nov 30, 2024 |
| Dell          | Inspiron 5570               | [d8fe08107c](https://linux-hardware.org/?probe=d8fe08107c) | Nov 27, 2024 |
| ASUSTek       | X510UNR                     | [9fc9d25b5f](https://linux-hardware.org/?probe=9fc9d25b5f) | Nov 24, 2024 |
| Lenovo        | ThinkPad T410 253725G       | [2f352dba44](https://linux-hardware.org/?probe=2f352dba44) | Nov 11, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [d5e9aab0ad](https://linux-hardware.org/?probe=d5e9aab0ad) | Nov 08, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [6bfe7b8d66](https://linux-hardware.org/?probe=6bfe7b8d66) | Nov 02, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5404CMA... | [cb52c24436](https://linux-hardware.org/?probe=cb52c24436) | Oct 30, 2024 |
| Notebook      | NS5x_NS7xPU                 | [82b158b778](https://linux-hardware.org/?probe=82b158b778) | Oct 30, 2024 |
| HP            | 255 G7 Notebook PC          | [7547bc75a9](https://linux-hardware.org/?probe=7547bc75a9) | Oct 29, 2024 |
| Dell          | Latitude 7640               | [db98adb76d](https://linux-hardware.org/?probe=db98adb76d) | Oct 28, 2024 |
| ASUSTek       | N552VX                      | [125f09bd6b](https://linux-hardware.org/?probe=125f09bd6b) | Oct 27, 2024 |
| Dell          | XPS 15 9530                 | [22b47c8319](https://linux-hardware.org/?probe=22b47c8319) | Oct 25, 2024 |
| Apple         | MacBookPro11,5              | [7680c404f8](https://linux-hardware.org/?probe=7680c404f8) | Sep 29, 2024 |
| Dell          | Latitude 7640               | [c90fe866d1](https://linux-hardware.org/?probe=c90fe866d1) | Sep 26, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [62e1a9a394](https://linux-hardware.org/?probe=62e1a9a394) | Sep 20, 2024 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [ef8c47b1d9](https://linux-hardware.org/?probe=ef8c47b1d9) | Sep 12, 2024 |
| HP            | EliteBook 850 G2            | [564d24fc5f](https://linux-hardware.org/?probe=564d24fc5f) | Sep 10, 2024 |
| HP            | ProBook 450 G6              | [3c8383394f](https://linux-hardware.org/?probe=3c8383394f) | Aug 25, 2024 |
| HP            | ProBook 450 G6              | [6b40bb2382](https://linux-hardware.org/?probe=6b40bb2382) | Aug 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [d2bf0e7e39](https://linux-hardware.org/?probe=d2bf0e7e39) | Aug 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S03X1H    | [c4c6048c05](https://linux-hardware.org/?probe=c4c6048c05) | Aug 09, 2024 |
| Dell          | Latitude 7640               | [cd57286388](https://linux-hardware.org/?probe=cd57286388) | Aug 08, 2024 |
| HP            | Compaq 6820s                | [6a3adf5719](https://linux-hardware.org/?probe=6a3adf5719) | Aug 04, 2024 |
| HP            | EliteBook 830 G5            | [0eb2a6c9e7](https://linux-hardware.org/?probe=0eb2a6c9e7) | Aug 02, 2024 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [88e46768ac](https://linux-hardware.org/?probe=88e46768ac) | Jul 27, 2024 |
| Toshiba       | Satellite L650              | [c6baf57189](https://linux-hardware.org/?probe=c6baf57189) | Jul 20, 2024 |
| Acer          | Aspire A515-47              | [2d5cce174d](https://linux-hardware.org/?probe=2d5cce174d) | Jul 10, 2024 |
| Acer          | Aspire A515-47              | [5f4f7526e8](https://linux-hardware.org/?probe=5f4f7526e8) | Jul 10, 2024 |
| HP            | Compaq nw8440 (RH415EA#A... | [c12a51db40](https://linux-hardware.org/?probe=c12a51db40) | Jun 26, 2024 |
| HP            | Compaq nw8440 (RH415EA#A... | [5b21cd9393](https://linux-hardware.org/?probe=5b21cd9393) | Jun 26, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [a40ce4c093](https://linux-hardware.org/?probe=a40ce4c093) | Jun 18, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c9a4221ee5](https://linux-hardware.org/?probe=c9a4221ee5) | Jun 14, 2024 |
| SLIMBOOK      | EXCALIBUR-16-AMD7           | [5b9182e0c0](https://linux-hardware.org/?probe=5b9182e0c0) | Jun 10, 2024 |
| HP            | ProBook 470 G4              | [ad0c9b74a2](https://linux-hardware.org/?probe=ad0c9b74a2) | May 31, 2024 |
| HP            | Laptop 15-ra0xx             | [0be312cffc](https://linux-hardware.org/?probe=0be312cffc) | May 28, 2024 |
| SLIMBOOK      | EXCALIBUR-16-AMD7           | [aa1f7ff9ac](https://linux-hardware.org/?probe=aa1f7ff9ac) | May 21, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0c1cb2dc27](https://linux-hardware.org/?probe=0c1cb2dc27) | May 12, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e3f9b42de5](https://linux-hardware.org/?probe=e3f9b42de5) | May 12, 2024 |
| HP            | EliteBook 840 G4            | [d725ec8595](https://linux-hardware.org/?probe=d725ec8595) | May 09, 2024 |
| SLIMBOOK      | HERO-S-TGL-RTX              | [eac9faa98c](https://linux-hardware.org/?probe=eac9faa98c) | May 03, 2024 |
| Chuwi         | CoreBook X                  | [deafd4078a](https://linux-hardware.org/?probe=deafd4078a) | Apr 20, 2024 |
| HP            | Laptop 15s-eq2xxx           | [16bde4de91](https://linux-hardware.org/?probe=16bde4de91) | Apr 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1b76135004](https://linux-hardware.org/?probe=1b76135004) | Mar 24, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [32321231e1](https://linux-hardware.org/?probe=32321231e1) | Mar 24, 2024 |
| HP            | EliteBook 8570w             | [4b83d77529](https://linux-hardware.org/?probe=4b83d77529) | Mar 10, 2024 |
| HP            | EliteBook 830 G5            | [b999903479](https://linux-hardware.org/?probe=b999903479) | Mar 09, 2024 |
| Acer          | Aspire 5742G                | [ec33f6391f](https://linux-hardware.org/?probe=ec33f6391f) | Feb 27, 2024 |
| Acer          | Aspire 5742G                | [4ab95b25ed](https://linux-hardware.org/?probe=4ab95b25ed) | Feb 24, 2024 |
| HP            | ProBook 4730s               | [e3bd4bfeae](https://linux-hardware.org/?probe=e3bd4bfeae) | Feb 16, 2024 |
| HP            | ProBook 4730s               | [b71e2386cc](https://linux-hardware.org/?probe=b71e2386cc) | Feb 16, 2024 |
| Sony          | SVF1521V1EB                 | [ec01d30645](https://linux-hardware.org/?probe=ec01d30645) | Feb 12, 2024 |
| HP            | ProBook 450 G3              | [d367c2a560](https://linux-hardware.org/?probe=d367c2a560) | Feb 11, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | [4ee3aae45e](https://linux-hardware.org/?probe=4ee3aae45e) | Feb 11, 2024 |
| Sony          | SVF1521V1EB                 | [3ec5455de7](https://linux-hardware.org/?probe=3ec5455de7) | Feb 10, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | [f5fd1fd3ae](https://linux-hardware.org/?probe=f5fd1fd3ae) | Feb 09, 2024 |
| Acer          | Swift SFX14-51G             | [9649ed5351](https://linux-hardware.org/?probe=9649ed5351) | Feb 05, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [51c4f07d2f](https://linux-hardware.org/?probe=51c4f07d2f) | Feb 04, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [ba4fdf1b5b](https://linux-hardware.org/?probe=ba4fdf1b5b) | Feb 04, 2024 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [3e0e2fd80a](https://linux-hardware.org/?probe=3e0e2fd80a) | Feb 03, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5fac7fde98](https://linux-hardware.org/?probe=5fac7fde98) | Jan 27, 2024 |
| HP            | Pavilion Notebook           | [91f1ca34ad](https://linux-hardware.org/?probe=91f1ca34ad) | Jan 19, 2024 |
| HP            | Pavilion dv1000 (EW489EA... | [ea4b49f529](https://linux-hardware.org/?probe=ea4b49f529) | Jan 17, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [de6b5ead5b](https://linux-hardware.org/?probe=de6b5ead5b) | Dec 24, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | [d153c701cc](https://linux-hardware.org/?probe=d153c701cc) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | [398233e395](https://linux-hardware.org/?probe=398233e395) | Dec 23, 2023 |
| Dell          | XPS 15 9500                 | [941f6d849a](https://linux-hardware.org/?probe=941f6d849a) | Dec 18, 2023 |
| Dell          | Precision 5510              | [8157bb9bc9](https://linux-hardware.org/?probe=8157bb9bc9) | Dec 12, 2023 |
| Dell          | Precision 5510              | [a14acbd791](https://linux-hardware.org/?probe=a14acbd791) | Dec 12, 2023 |
| Dell          | Latitude 7490               | [c964863876](https://linux-hardware.org/?probe=c964863876) | Nov 20, 2023 |
| HP            | Stream Notebook PC 13       | [946612aeb4](https://linux-hardware.org/?probe=946612aeb4) | Nov 19, 2023 |
| HP            | Stream Notebook PC 13       | [9cf67aa27c](https://linux-hardware.org/?probe=9cf67aa27c) | Nov 19, 2023 |
| Dynabook      | Satellite Pro C40-G-109     | [32a21ea7ad](https://linux-hardware.org/?probe=32a21ea7ad) | Nov 10, 2023 |
| Lenovo        | ThinkPad T520 4243RU3       | [5095529d19](https://linux-hardware.org/?probe=5095529d19) | Nov 05, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [4ba182f0d5](https://linux-hardware.org/?probe=4ba182f0d5) | Nov 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d64009bcc1](https://linux-hardware.org/?probe=d64009bcc1) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f5d0c4d34a](https://linux-hardware.org/?probe=f5d0c4d34a) | Nov 01, 2023 |
| Fujitsu       | LIFEBOOK S792               | [5eaa7922e7](https://linux-hardware.org/?probe=5eaa7922e7) | Oct 27, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [38046f165d](https://linux-hardware.org/?probe=38046f165d) | Oct 26, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [7830b3ae27](https://linux-hardware.org/?probe=7830b3ae27) | Oct 26, 2023 |
| Acer          | Aspire A515-47              | [3c1e418bf0](https://linux-hardware.org/?probe=3c1e418bf0) | Sep 26, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [db906f78dd](https://linux-hardware.org/?probe=db906f78dd) | Sep 06, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3b0d2983a6](https://linux-hardware.org/?probe=3b0d2983a6) | Sep 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [aefedc3b34](https://linux-hardware.org/?probe=aefedc3b34) | Sep 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6dd95e8115](https://linux-hardware.org/?probe=6dd95e8115) | Aug 30, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| ASUSTek       | GL503VS                     | [767317b527](https://linux-hardware.org/?probe=767317b527) | Jun 20, 2023 |
| Dell          | XPS 15 9510                 | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | EliteBook Folio 9470m       | [73720c6437](https://linux-hardware.org/?probe=73720c6437) | Jun 12, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| Dell          | XPS 15 9510                 | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| HP            | ZBook 17 G2                 | [50b19fc413](https://linux-hardware.org/?probe=50b19fc413) | May 20, 2023 |
| Dell          | Latitude D630               | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ed72b68c39](https://linux-hardware.org/?probe=ed72b68c39) | May 13, 2023 |
| Dell          | XPS 15 9510                 | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Medion        | E6232                       | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| HP            | ProBook 4730s               | [c4f4cf46cf](https://linux-hardware.org/?probe=c4f4cf46cf) | May 01, 2023 |
| HP            | ProBook 4730s               | [bd90580b35](https://linux-hardware.org/?probe=bd90580b35) | May 01, 2023 |
| Acer          | Nitro AN517-42              | [5e54d08f91](https://linux-hardware.org/?probe=5e54d08f91) | Apr 25, 2023 |
| HP            | ZBook 17 G5                 | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | [ce9fd79431](https://linux-hardware.org/?probe=ce9fd79431) | Apr 23, 2023 |
| Dell          | XPS 13 9310                 | [5c9b8fef2e](https://linux-hardware.org/?probe=5c9b8fef2e) | Apr 21, 2023 |
| ASUSTek       | UX430UNR                    | [d8ed935b86](https://linux-hardware.org/?probe=d8ed935b86) | Apr 19, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| HP            | 255 G8 Notebook PC          | [4c46d2ae80](https://linux-hardware.org/?probe=4c46d2ae80) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [a316144991](https://linux-hardware.org/?probe=a316144991) | Mar 29, 2023 |
| HP            | Compaq 6730s                | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| HP            | ProBook 450 G6              | [acbfa27478](https://linux-hardware.org/?probe=acbfa27478) | Mar 20, 2023 |
| HP            | ProBook 450 G6              | [d8c39b84d1](https://linux-hardware.org/?probe=d8c39b84d1) | Mar 20, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [92d818d184](https://linux-hardware.org/?probe=92d818d184) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [60114cc9c8](https://linux-hardware.org/?probe=60114cc9c8) | Mar 16, 2023 |
| Dell          | Latitude 5530               | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| HP            | ZBook 17 G2                 | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Toshiba       | Satellite Pro R50-E         | [b039ed22c6](https://linux-hardware.org/?probe=b039ed22c6) | Mar 01, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| HP            | ProBook 4730s               | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Dell          | XPS 13 9310                 | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| HP            | ProBook 4530s               | [c081fdc9be](https://linux-hardware.org/?probe=c081fdc9be) | Feb 07, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [475265e1f8](https://linux-hardware.org/?probe=475265e1f8) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK A530               | [0698054de0](https://linux-hardware.org/?probe=0698054de0) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK A530               | [122005ade3](https://linux-hardware.org/?probe=122005ade3) | Jan 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [74bf687e30](https://linux-hardware.org/?probe=74bf687e30) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Lenovo        | ThinkPad E590 20NCS00800    | [8751d5b445](https://linux-hardware.org/?probe=8751d5b445) | Jan 15, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [b3c2be78b3](https://linux-hardware.org/?probe=b3c2be78b3) | Jan 14, 2023 |
| HP            | EliteBook 830 G5            | [6a11a77a53](https://linux-hardware.org/?probe=6a11a77a53) | Jan 12, 2023 |
| HP            | EliteBook 830 G5            | [09f51f5cd3](https://linux-hardware.org/?probe=09f51f5cd3) | Jan 12, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [82ca2971d9](https://linux-hardware.org/?probe=82ca2971d9) | Jan 12, 2023 |
| Lenovo        | G50-30 80G0                 | [7c432a386b](https://linux-hardware.org/?probe=7c432a386b) | Jan 11, 2023 |
| Lenovo        | G500 20236                  | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| Dell          | Inspiron 1501               | [1bb0000755](https://linux-hardware.org/?probe=1bb0000755) | Dec 16, 2022 |
| HUAWEI        | HKD-WXX                     | [a7b446df37](https://linux-hardware.org/?probe=a7b446df37) | Dec 08, 2022 |
| HP            | EliteBook 820 G1            | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Toshiba       | Satellite R630              | [3826be6846](https://linux-hardware.org/?probe=3826be6846) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | [eebafcab9e](https://linux-hardware.org/?probe=eebafcab9e) | Dec 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [f19b2c0b81](https://linux-hardware.org/?probe=f19b2c0b81) | Dec 03, 2022 |
| ASUSTek       | 1225B                       | [87f1b143de](https://linux-hardware.org/?probe=87f1b143de) | Nov 27, 2022 |
| HUAWEI        | HKD-WXX                     | [5271fa9ef9](https://linux-hardware.org/?probe=5271fa9ef9) | Nov 26, 2022 |
| ASUSTek       | X553MA                      | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| Toshiba       | TECRA A11                   | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| ASUSTek       | X510UQR                     | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a2e0ee2043](https://linux-hardware.org/?probe=a2e0ee2043) | Oct 15, 2022 |
| Toshiba       | Satellite A100              | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| HP            | Pavilion g7                 | [19b206ba2f](https://linux-hardware.org/?probe=19b206ba2f) | Sep 25, 2022 |
| HP            | ProBook 4340s               | [668ffa05ea](https://linux-hardware.org/?probe=668ffa05ea) | Sep 18, 2022 |
| HP            | ProBook 4340s               | [1abbd84e9c](https://linux-hardware.org/?probe=1abbd84e9c) | Sep 18, 2022 |
| Toshiba       | TECRA S10                   | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| HP            | Unknown                     | [692825c1eb](https://linux-hardware.org/?probe=692825c1eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [c55fef18c3](https://linux-hardware.org/?probe=c55fef18c3) | Sep 11, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | [273e5229a4](https://linux-hardware.org/?probe=273e5229a4) | Aug 30, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| Framework     | Laptop                      | [c52019fe10](https://linux-hardware.org/?probe=c52019fe10) | Aug 07, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [b9c35e80d2](https://linux-hardware.org/?probe=b9c35e80d2) | Aug 06, 2022 |
| Lenovo        | B50-30 20382                | [6ab4942a20](https://linux-hardware.org/?probe=6ab4942a20) | Jul 16, 2022 |
| Lenovo        | B50-30 20382                | [d9573dc3e6](https://linux-hardware.org/?probe=d9573dc3e6) | Jul 08, 2022 |
| Dell          | Inspiron 1501               | [f6efa72c1f](https://linux-hardware.org/?probe=f6efa72c1f) | Jul 01, 2022 |
| HP            | 255 G8 Notebook PC          | [cae0332804](https://linux-hardware.org/?probe=cae0332804) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | [e65ead281f](https://linux-hardware.org/?probe=e65ead281f) | Jun 17, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| Toshiba       | Satellite Pro U400          | [4aeeca648d](https://linux-hardware.org/?probe=4aeeca648d) | May 24, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| ASUSTek       | N71Vg                       | [33a6047c0b](https://linux-hardware.org/?probe=33a6047c0b) | May 14, 2022 |
| ASUSTek       | N71Vg                       | [86d9e911f1](https://linux-hardware.org/?probe=86d9e911f1) | May 13, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | Laptop 17-ca3xxx            | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | [81409450dc](https://linux-hardware.org/?probe=81409450dc) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | [d7b7a81cbb](https://linux-hardware.org/?probe=d7b7a81cbb) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [8570b5ab84](https://linux-hardware.org/?probe=8570b5ab84) | Apr 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| HP            | ZBook 17 G2                 | [f0efa22aa2](https://linux-hardware.org/?probe=f0efa22aa2) | Mar 27, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | [0bf3028253](https://linux-hardware.org/?probe=0bf3028253) | Mar 27, 2022 |
| Dell          | Precision 5540              | [38d9bed727](https://linux-hardware.org/?probe=38d9bed727) | Mar 21, 2022 |
| Fujitsu       | LIFEBOOK S792               | [55da3ab4e0](https://linux-hardware.org/?probe=55da3ab4e0) | Mar 09, 2022 |
| HP            | Compaq nw8440 (RH415EA#A... | [55a6d982b3](https://linux-hardware.org/?probe=55a6d982b3) | Mar 07, 2022 |
| HP            | ZBook 17 G2                 | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| HP            | kip                         | [4d6e1264c7](https://linux-hardware.org/?probe=4d6e1264c7) | Mar 02, 2022 |
| HP            | kip                         | [a6ab5d4d8a](https://linux-hardware.org/?probe=a6ab5d4d8a) | Mar 01, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| HP            | Pavilion dv7                | [46280b758c](https://linux-hardware.org/?probe=46280b758c) | Feb 25, 2022 |
| ASUSTek       | X550JX                      | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |
| HP            | Pavilion dv7                | [fd1bbe1769](https://linux-hardware.org/?probe=fd1bbe1769) | Feb 21, 2022 |
| HP            | Pavilion dv7                | [da9449422c](https://linux-hardware.org/?probe=da9449422c) | Feb 21, 2022 |
| ASUSTek       | X550JX                      | [0ee9dcd568](https://linux-hardware.org/?probe=0ee9dcd568) | Feb 20, 2022 |
| HP            | ProBook 4730s               | [5ffa4bce13](https://linux-hardware.org/?probe=5ffa4bce13) | Feb 19, 2022 |
| ASUSTek       | X550JX                      | [5ee5668ab1](https://linux-hardware.org/?probe=5ee5668ab1) | Feb 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [5323885713](https://linux-hardware.org/?probe=5323885713) | Feb 17, 2022 |
| HP            | EliteBook 8570w             | [df5a829402](https://linux-hardware.org/?probe=df5a829402) | Feb 09, 2022 |
| Acer          | Predator PH317-52           | [ec43c5baa2](https://linux-hardware.org/?probe=ec43c5baa2) | Feb 07, 2022 |
| ASUSTek       | X750LN                      | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| HP            | EliteBook 8570w             | [81e03a6b48](https://linux-hardware.org/?probe=81e03a6b48) | Jan 21, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [faba7de732](https://linux-hardware.org/?probe=faba7de732) | Jan 17, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [f2bae7651d](https://linux-hardware.org/?probe=f2bae7651d) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [22e51b8b41](https://linux-hardware.org/?probe=22e51b8b41) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [52db8d0bbf](https://linux-hardware.org/?probe=52db8d0bbf) | Jan 06, 2022 |
| Lenovo        | ThinkPad T590 20N5S0MR00    | [29040ecce5](https://linux-hardware.org/?probe=29040ecce5) | Jan 01, 2022 |
| MSI           | U210                        | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| HP            | ProBook 450 G5              | [8887022aa7](https://linux-hardware.org/?probe=8887022aa7) | Dec 23, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [6b40a0f2c5](https://linux-hardware.org/?probe=6b40a0f2c5) | Dec 21, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [31c2b40e84](https://linux-hardware.org/?probe=31c2b40e84) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6238c622ad](https://linux-hardware.org/?probe=6238c622ad) | Dec 18, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [45ac665485](https://linux-hardware.org/?probe=45ac665485) | Dec 10, 2021 |
| Dell          | Inspiron 5748               | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [6d9c31a411](https://linux-hardware.org/?probe=6d9c31a411) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [e005ddb405](https://linux-hardware.org/?probe=e005ddb405) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | EliteBook 8760w             | [febc9d2faa](https://linux-hardware.org/?probe=febc9d2faa) | Nov 28, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [e898d8c017](https://linux-hardware.org/?probe=e898d8c017) | Nov 20, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [e37febb0b3](https://linux-hardware.org/?probe=e37febb0b3) | Nov 18, 2021 |
| HP            | 250 G3                      | [8d370cbb27](https://linux-hardware.org/?probe=8d370cbb27) | Nov 16, 2021 |
| HP            | 250 G3                      | [fb9fe2f3fb](https://linux-hardware.org/?probe=fb9fe2f3fb) | Nov 16, 2021 |
| Dell          | XPS 13 7390                 | [c4e6de1315](https://linux-hardware.org/?probe=c4e6de1315) | Nov 15, 2021 |
| Dell          | XPS 13 9310                 | [0f6c2b21cf](https://linux-hardware.org/?probe=0f6c2b21cf) | Nov 14, 2021 |
| Dell          | XPS 13 9310                 | [01c20231f2](https://linux-hardware.org/?probe=01c20231f2) | Nov 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| HP            | Pavilion dv7                | [3c3e5bc872](https://linux-hardware.org/?probe=3c3e5bc872) | Nov 08, 2021 |
| HP            | EliteBook 8760w             | [99fb47dc2b](https://linux-hardware.org/?probe=99fb47dc2b) | Oct 28, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [4e5da9e4d3](https://linux-hardware.org/?probe=4e5da9e4d3) | Oct 24, 2021 |
| HP            | EliteBook Folio 9470m       | [f66ba65dc8](https://linux-hardware.org/?probe=f66ba65dc8) | Oct 22, 2021 |
| HP            | EliteBook Folio 9470m       | [1d50915627](https://linux-hardware.org/?probe=1d50915627) | Oct 21, 2021 |
| Toshiba       | Satellite L750              | [f18e793687](https://linux-hardware.org/?probe=f18e793687) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | [065ee91163](https://linux-hardware.org/?probe=065ee91163) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | [2cbf85194c](https://linux-hardware.org/?probe=2cbf85194c) | Oct 14, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [f424437bd1](https://linux-hardware.org/?probe=f424437bd1) | Oct 01, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [c85622ebee](https://linux-hardware.org/?probe=c85622ebee) | Sep 29, 2021 |
| HP            | ProBook 450 G1              | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [8c7e729202](https://linux-hardware.org/?probe=8c7e729202) | Aug 19, 2021 |
| HP            | 2000                        | [2909375db3](https://linux-hardware.org/?probe=2909375db3) | Aug 06, 2021 |
| HP            | 2000                        | [df5d5e05c6](https://linux-hardware.org/?probe=df5d5e05c6) | Aug 06, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| HP            | 2000                        | [9fbfcf95d2](https://linux-hardware.org/?probe=9fbfcf95d2) | Jul 29, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| HP            | 2000                        | [13aaafccdb](https://linux-hardware.org/?probe=13aaafccdb) | Jul 22, 2021 |
| HP            | 2000                        | [f3c7f85988](https://linux-hardware.org/?probe=f3c7f85988) | Jul 21, 2021 |
| HP            | 2000                        | [e6019f1bd3](https://linux-hardware.org/?probe=e6019f1bd3) | Jul 12, 2021 |
| HP            | 2000                        | [6a169f2d87](https://linux-hardware.org/?probe=6a169f2d87) | Jun 22, 2021 |
| HP            | 2000                        | [b2e5075aaf](https://linux-hardware.org/?probe=b2e5075aaf) | Jun 17, 2021 |
| HP            | EliteBook 8440p             | [330d2214c6](https://linux-hardware.org/?probe=330d2214c6) | Jun 10, 2021 |
| HP            | 2000                        | [6a1c91ae8d](https://linux-hardware.org/?probe=6a1c91ae8d) | Jun 07, 2021 |
| Acer          | Nitro AN517-52              | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| Lenovo        | ThinkPad T61 8897CTO        | [6cfc0271ba](https://linux-hardware.org/?probe=6cfc0271ba) | Jun 03, 2021 |
| HP            | 250 G7 Notebook PC          | [92d97521bc](https://linux-hardware.org/?probe=92d97521bc) | May 21, 2021 |
| HP            | 250 G7 Notebook PC          | [76598a468f](https://linux-hardware.org/?probe=76598a468f) | May 20, 2021 |
| HP            | 2000                        | [1469c94a5f](https://linux-hardware.org/?probe=1469c94a5f) | May 17, 2021 |
| HP            | EliteBook 830 G6            | [8fcf99f057](https://linux-hardware.org/?probe=8fcf99f057) | May 12, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| Panasonic     | CF-53SWWZ5MG                | [c59fd76192](https://linux-hardware.org/?probe=c59fd76192) | Apr 14, 2021 |
| HP            | EliteBook 8440p             | [d0a4124a2a](https://linux-hardware.org/?probe=d0a4124a2a) | Apr 10, 2021 |
| HP            | ProBook 4515s (VC377ES#A... | [2c84f60b0d](https://linux-hardware.org/?probe=2c84f60b0d) | Apr 09, 2021 |
| HP            | ProBook 4740s               | [cf941af09e](https://linux-hardware.org/?probe=cf941af09e) | Apr 08, 2021 |
| Dell          | Latitude 5501               | [474510883b](https://linux-hardware.org/?probe=474510883b) | Mar 22, 2021 |
| HP            | ProBook 450 G5              | [49b951896d](https://linux-hardware.org/?probe=49b951896d) | Mar 17, 2021 |
| ASUSTek       | K72Jr                       | [2d9ae8527d](https://linux-hardware.org/?probe=2d9ae8527d) | Mar 11, 2021 |
| ASUSTek       | K52JT                       | [e434a21940](https://linux-hardware.org/?probe=e434a21940) | Mar 04, 2021 |
| Panasonic     | CF-53SWWZ5MG                | [6fdf12c20c](https://linux-hardware.org/?probe=6fdf12c20c) | Feb 28, 2021 |
| Dell          | XPS 13 7390                 | [9dc547fceb](https://linux-hardware.org/?probe=9dc547fceb) | Feb 26, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| Panasonic     | CF-53SWWZ5MG                | [d1ade3e39d](https://linux-hardware.org/?probe=d1ade3e39d) | Feb 08, 2021 |
| Acer          | Aspire A315-42              | [95958aa225](https://linux-hardware.org/?probe=95958aa225) | Feb 08, 2021 |
| Dell          | XPS 13 7390                 | [0e552a01e6](https://linux-hardware.org/?probe=0e552a01e6) | Feb 03, 2021 |
| Dell          | XPS 13 7390                 | [1f3dc6c825](https://linux-hardware.org/?probe=1f3dc6c825) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [7e828e295f](https://linux-hardware.org/?probe=7e828e295f) | Jan 20, 2021 |
| HP            | ZBook 15u G3                | [812e100310](https://linux-hardware.org/?probe=812e100310) | Jan 12, 2021 |
| HP            | ZBook 15u G3                | [30332e1d71](https://linux-hardware.org/?probe=30332e1d71) | Jan 12, 2021 |
| HP            | Laptop 15-ra0xx             | [8227f44e5c](https://linux-hardware.org/?probe=8227f44e5c) | Jan 10, 2021 |
| HP            | ProBook 4730s               | [e7ab1bcd89](https://linux-hardware.org/?probe=e7ab1bcd89) | Jan 06, 2021 |
| HP            | EliteBook 6930p             | [e9c1683321](https://linux-hardware.org/?probe=e9c1683321) | Jan 04, 2021 |
| ASUSTek       | UX31E                       | [912f3fe702](https://linux-hardware.org/?probe=912f3fe702) | Dec 25, 2020 |
| HP            | 255 G7 Notebook PC          | [d759211bb6](https://linux-hardware.org/?probe=d759211bb6) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [6c3965a41f](https://linux-hardware.org/?probe=6c3965a41f) | Dec 18, 2020 |
| ASUSTek       | G771JW                      | [b103133d69](https://linux-hardware.org/?probe=b103133d69) | Dec 16, 2020 |
| Dell          | Inspiron 3542               | [4260174285](https://linux-hardware.org/?probe=4260174285) | Dec 11, 2020 |
| Lenovo        | ThinkPad T500 2055WYX       | [6f04a45e2e](https://linux-hardware.org/?probe=6f04a45e2e) | Dec 11, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | [dd93682c3c](https://linux-hardware.org/?probe=dd93682c3c) | Dec 09, 2020 |
| Dell          | Latitude D630               | [92ccc6100c](https://linux-hardware.org/?probe=92ccc6100c) | Dec 05, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [e2ffbd65b4](https://linux-hardware.org/?probe=e2ffbd65b4) | Dec 04, 2020 |
| Acer          | Aspire A315-42              | [1b5583ba18](https://linux-hardware.org/?probe=1b5583ba18) | Nov 23, 2020 |
| HP            | 250 G7 Notebook PC          | [bc3c7d8910](https://linux-hardware.org/?probe=bc3c7d8910) | Nov 22, 2020 |
| HP            | 250 G7 Notebook PC          | [db1f0e1247](https://linux-hardware.org/?probe=db1f0e1247) | Nov 22, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [5978ba6a13](https://linux-hardware.org/?probe=5978ba6a13) | Nov 22, 2020 |
| HP            | 470 G7 Notebook PC          | [f0d3574818](https://linux-hardware.org/?probe=f0d3574818) | Nov 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8783481f8a](https://linux-hardware.org/?probe=8783481f8a) | Nov 15, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [1298138505](https://linux-hardware.org/?probe=1298138505) | Nov 13, 2020 |
| HP            | ProBook 4720s               | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0b3fe9a6f2](https://linux-hardware.org/?probe=0b3fe9a6f2) | Nov 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [49bc5032be](https://linux-hardware.org/?probe=49bc5032be) | Nov 01, 2020 |
| HP            | 255 G7 Notebook PC          | [3ad72de5c7](https://linux-hardware.org/?probe=3ad72de5c7) | Oct 09, 2020 |
| HP            | 255 G7 Notebook PC          | [2c625d510e](https://linux-hardware.org/?probe=2c625d510e) | Oct 03, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | [3a0bc546cc](https://linux-hardware.org/?probe=3a0bc546cc) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [1a20b51c58](https://linux-hardware.org/?probe=1a20b51c58) | Sep 24, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [ca8c660b91](https://linux-hardware.org/?probe=ca8c660b91) | Sep 24, 2020 |
| HP            | 255 G7 Notebook PC          | [8bba4f976e](https://linux-hardware.org/?probe=8bba4f976e) | Sep 20, 2020 |
| Dell          | Vostro 3550                 | [ef71fe525d](https://linux-hardware.org/?probe=ef71fe525d) | Sep 17, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| ASUSTek       | VivoBook S14 X430UA         | [85ab9de98f](https://linux-hardware.org/?probe=85ab9de98f) | Sep 03, 2020 |
| PC Special... | Fusion IV                   | [55da1618ab](https://linux-hardware.org/?probe=55da1618ab) | Aug 30, 2020 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [a87567fe16](https://linux-hardware.org/?probe=a87567fe16) | Aug 27, 2020 |
| HP            | ProBook 4540s               | [32346e7861](https://linux-hardware.org/?probe=32346e7861) | Aug 26, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [438b0df832](https://linux-hardware.org/?probe=438b0df832) | Jul 21, 2020 |
| HP            | 2000                        | [1facf761c9](https://linux-hardware.org/?probe=1facf761c9) | Jul 19, 2020 |
| Lenovo        | ThinkPad T420 423662G       | [f0e52bdb36](https://linux-hardware.org/?probe=f0e52bdb36) | Jul 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | [b78049616e](https://linux-hardware.org/?probe=b78049616e) | Jul 09, 2020 |
| Lenovo        | ThinkPad T480 20L6S01W00    | [758a8710d7](https://linux-hardware.org/?probe=758a8710d7) | Jun 29, 2020 |
| HP            | ProBook 4540s               | [98a9e4902b](https://linux-hardware.org/?probe=98a9e4902b) | Jun 08, 2020 |
| HP            | ProBook 4540s               | [2b515ca642](https://linux-hardware.org/?probe=2b515ca642) | May 31, 2020 |
| HP            | EliteBook 8540w             | [a8e5567ca8](https://linux-hardware.org/?probe=a8e5567ca8) | May 30, 2020 |
| HP            | EliteBook 840 G6            | [bea6687b8b](https://linux-hardware.org/?probe=bea6687b8b) | May 27, 2020 |
| Acer          | Aspire V3-771               | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| HP            | ProBook 470 G2              | [d39ca7c5fa](https://linux-hardware.org/?probe=d39ca7c5fa) | May 15, 2020 |
| HP            | 15                          | [fa65501be6](https://linux-hardware.org/?probe=fa65501be6) | May 10, 2020 |
| Dell          | Inspiron 5570               | [91d3944426](https://linux-hardware.org/?probe=91d3944426) | May 10, 2020 |
| HP            | 250 G6 Notebook PC          | [ee92e64256](https://linux-hardware.org/?probe=ee92e64256) | May 07, 2020 |
| HP            | ProBook 4515s (VC377ES#A... | [3ec25a2e7a](https://linux-hardware.org/?probe=3ec25a2e7a) | May 01, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [a1de2f2fe9](https://linux-hardware.org/?probe=a1de2f2fe9) | Apr 18, 2020 |
| Lenovo        | ThinkPad T590 20N5S0YN00    | [0efab1d69f](https://linux-hardware.org/?probe=0efab1d69f) | Apr 08, 2020 |
| ASUSTek       | X750LB                      | [a7c5fb20f8](https://linux-hardware.org/?probe=a7c5fb20f8) | Mar 28, 2020 |
| Lenovo        | G510 20238                  | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [ff84ae40b8](https://linux-hardware.org/?probe=ff84ae40b8) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [0877aa97e7](https://linux-hardware.org/?probe=0877aa97e7) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [677f41b346](https://linux-hardware.org/?probe=677f41b346) | Mar 21, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | [48cd703e5b](https://linux-hardware.org/?probe=48cd703e5b) | Mar 05, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | [e6a4ad2c61](https://linux-hardware.org/?probe=e6a4ad2c61) | Mar 04, 2020 |
| HP            | EliteBook 8760w             | [624fd6f7fa](https://linux-hardware.org/?probe=624fd6f7fa) | Mar 01, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [608fef5510](https://linux-hardware.org/?probe=608fef5510) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB002BSC    | [b20e37d478](https://linux-hardware.org/?probe=b20e37d478) | Jan 06, 2020 |
| Dell          | Latitude 5500               | [84e2b9bc59](https://linux-hardware.org/?probe=84e2b9bc59) | Jan 03, 2020 |
| HP            | EliteBook 850 G6            | [0d7f336b82](https://linux-hardware.org/?probe=0d7f336b82) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [0d946e75f9](https://linux-hardware.org/?probe=0d946e75f9) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [be70af9da7](https://linux-hardware.org/?probe=be70af9da7) | Jan 03, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [d853ff31e4](https://linux-hardware.org/?probe=d853ff31e4) | Dec 08, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [25e0799d44](https://linux-hardware.org/?probe=25e0799d44) | Dec 08, 2019 |
| MSI           | GP60 2OD                    | [f450b0d5d4](https://linux-hardware.org/?probe=f450b0d5d4) | Oct 20, 2019 |
| HP            | EliteBook 6930p             | [b11cbf51cb](https://linux-hardware.org/?probe=b11cbf51cb) | Sep 28, 2019 |
| Lenovo        | G585 20137                  | [084d318c5c](https://linux-hardware.org/?probe=084d318c5c) | Sep 16, 2019 |
| Acer          | Aspire E5-573G              | [d2242a3cd4](https://linux-hardware.org/?probe=d2242a3cd4) | Sep 02, 2019 |
| eMachines     | G730                        | [af8b954f82](https://linux-hardware.org/?probe=af8b954f82) | Aug 29, 2019 |
| ASUSTek       | G751JT                      | [a5f96019bd](https://linux-hardware.org/?probe=a5f96019bd) | Aug 04, 2019 |
| eMachines     | G730                        | [5073ea0163](https://linux-hardware.org/?probe=5073ea0163) | Aug 02, 2019 |
| eMachines     | G730                        | [4f0fa60c8d](https://linux-hardware.org/?probe=4f0fa60c8d) | Jul 31, 2019 |
| HP            | Pavilion 15                 | [edf229fa5e](https://linux-hardware.org/?probe=edf229fa5e) | Jul 22, 2019 |
| Toshiba       | QOSMIO X500                 | [34905cb301](https://linux-hardware.org/?probe=34905cb301) | Jul 15, 2019 |
| ASUSTek       | G751JT                      | [3a17d38bdd](https://linux-hardware.org/?probe=3a17d38bdd) | Jul 09, 2019 |
| Lenovo        | ThinkPad T410 2522A92       | [68640c00d9](https://linux-hardware.org/?probe=68640c00d9) | Jun 09, 2019 |
| HP            | Compaq 325                  | [4161a93030](https://linux-hardware.org/?probe=4161a93030) | May 16, 2019 |
| HP            | ProBook 4710s               | [54ed79f58d](https://linux-hardware.org/?probe=54ed79f58d) | May 15, 2019 |
| HP            | Compaq 325                  | [b9dadeece3](https://linux-hardware.org/?probe=b9dadeece3) | May 12, 2019 |
| HP            | Compaq 6720s                | [0e2550055b](https://linux-hardware.org/?probe=0e2550055b) | May 07, 2019 |
| Gigabyte      | P65                         | [6dfb59f508](https://linux-hardware.org/?probe=6dfb59f508) | May 07, 2019 |
| HP            | ZBook 14 G2                 | [e1463c9ca8](https://linux-hardware.org/?probe=e1463c9ca8) | Apr 23, 2019 |
| Lenovo        | ThinkPad W530 24479K4       | [7d56ca80ca](https://linux-hardware.org/?probe=7d56ca80ca) | Apr 22, 2019 |
| ASUSTek       | X751NV                      | [a189d47b9a](https://linux-hardware.org/?probe=a189d47b9a) | Apr 09, 2019 |
| Dell          | Latitude E6500              | [abdbb02998](https://linux-hardware.org/?probe=abdbb02998) | Feb 23, 2019 |
| Medion        | E7218                       | [5d97b97758](https://linux-hardware.org/?probe=5d97b97758) | Dec 16, 2018 |
| HP            | Unknown                     | [696e11ac42](https://linux-hardware.org/?probe=696e11ac42) | Nov 29, 2018 |
| HP            | Unknown                     | [121bf767df](https://linux-hardware.org/?probe=121bf767df) | Nov 29, 2018 |
| Lenovo        | ThinkPad Edge 326054G       | [6754682a3b](https://linux-hardware.org/?probe=6754682a3b) | Sep 16, 2017 |
| Lenovo        | ThinkPad Edge 326054G       | [c208f4b144](https://linux-hardware.org/?probe=c208f4b144) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 28        | 9.96%   |
| Ubuntu 22.04                 | 21        | 7.47%   |
| Ubuntu 18.04                 | 14        | 4.98%   |
| Arch Rolling                 | 10        | 3.56%   |
| Debian 11                    | 9         | 3.2%    |
| Zorin 17                     | 6         | 2.14%   |
| Debian 12                    | 6         | 2.14%   |
| Kubuntu 22.04                | 5         | 1.78%   |
| KDE neon 22.04               | 5         | 1.78%   |
| KDE neon 20.04               | 5         | 1.78%   |
| Fedora 37                    | 5         | 1.78%   |
| ArcoLinux Rolling            | 5         | 1.78%   |
| Zorin 16                     | 4         | 1.42%   |
| Zorin 15                     | 4         | 1.42%   |
| OpenMandriva 4.3             | 4         | 1.42%   |
| Fedora 34                    | 4         | 1.42%   |
| Fedora 33                    | 4         | 1.42%   |
| Arch                         | 4         | 1.42%   |
| Xubuntu 22.04                | 3         | 1.07%   |
| Xubuntu 20.04                | 3         | 1.07%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.07%   |
| OpenMandriva 4.2             | 3         | 1.07%   |
| Manjaro                      | 3         | 1.07%   |
| Linux Mint 21.3              | 3         | 1.07%   |
| Linux Mint 19.1              | 3         | 1.07%   |
| Kubuntu 21.10                | 3         | 1.07%   |
| Kubuntu 20.04                | 3         | 1.07%   |
| Fedora 41                    | 3         | 1.07%   |
| Fedora 40                    | 3         | 1.07%   |
| Debian Testing               | 3         | 1.07%   |
| Ubuntu Unity 16.04           | 2         | 0.71%   |
| Ubuntu 21.10                 | 2         | 0.71%   |
| Ubuntu 21.04                 | 2         | 0.71%   |
| Ubuntu 20.10                 | 2         | 0.71%   |
| Ubuntu 19.10                 | 2         | 0.71%   |
| Pop!_OS 22.04                | 2         | 0.71%   |
| Pop!_OS 21.04                | 2         | 0.71%   |
| Manjaro 20.2                 | 2         | 0.71%   |
| LMDE 5                       | 2         | 0.71%   |
| Linux Mint 21                | 2         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 70        | 26.12%  |
| Fedora        | 25        | 9.33%   |
| Debian        | 20        | 7.46%   |
| Kubuntu       | 18        | 6.72%   |
| Zorin         | 14        | 5.22%   |
| Linux Mint    | 14        | 5.22%   |
| Arch          | 14        | 5.22%   |
| OpenMandriva  | 11        | 4.1%    |
| KDE neon      | 11        | 4.1%    |
| Manjaro       | 10        | 3.73%   |
| Endless       | 9         | 3.36%   |
| Xubuntu       | 6         | 2.24%   |
| openSUSE      | 6         | 2.24%   |
| Pop!_OS       | 5         | 1.87%   |
| ArcoLinux     | 5         | 1.87%   |
| EndeavourOS   | 3         | 1.12%   |
| Ubuntu Unity  | 2         | 0.75%   |
| Ubuntu Budgie | 2         | 0.75%   |
| Q4OS          | 2         | 0.75%   |
| Lubuntu       | 2         | 0.75%   |
| LMDE          | 2         | 0.75%   |
| Kali          | 2         | 0.75%   |
| Gentoo        | 2         | 0.75%   |
| Garuda Linux  | 2         | 0.75%   |
| Elementary    | 2         | 0.75%   |
| Ubuntu MATE   | 1         | 0.37%   |
| ROSA          | 1         | 0.37%   |
| Nobara        | 1         | 0.37%   |
| NixOS         | 1         | 0.37%   |
| Dts-distro    | 1         | 0.37%   |
| Clear Linux   | 1         | 0.37%   |
| Chrome OS     | 1         | 0.37%   |
| BlackPanther  | 1         | 0.37%   |
| Artix         | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 4         | 1.29%   |
| 4.18.0-15-generic        | 4         | 1.29%   |
| 5.8.0-41-generic         | 3         | 0.97%   |
| 5.3.0-40-generic         | 3         | 0.97%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.97%   |
| 5.15.0-57-generic        | 3         | 0.97%   |
| 5.15.0-56-generic        | 3         | 0.97%   |
| 5.15.0-43-generic        | 3         | 0.97%   |
| 5.13.0-41-generic        | 3         | 0.97%   |
| 5.13.0-30-generic        | 3         | 0.97%   |
| 5.13.0-28-generic        | 3         | 0.97%   |
| 5.13.0-21-generic        | 3         | 0.97%   |
| 5.10.14-desktop-1omv4002 | 3         | 0.97%   |
| 6.8.0-48-generic         | 2         | 0.65%   |
| 6.8.0-47-generic         | 2         | 0.65%   |
| 6.5.0-45-generic         | 2         | 0.65%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.65%   |
| 6.3.9-arch1-1            | 2         | 0.65%   |
| 6.2.0-36-generic         | 2         | 0.65%   |
| 6.2.0-31-generic         | 2         | 0.65%   |
| 5.8.0-44-generic         | 2         | 0.65%   |
| 5.8.0-14-generic         | 2         | 0.65%   |
| 5.6.0-1-amd64            | 2         | 0.65%   |
| 5.4.0-70-generic         | 2         | 0.65%   |
| 5.4.0-56-generic         | 2         | 0.65%   |
| 5.4.0-54-generic         | 2         | 0.65%   |
| 5.4.0-48-generic         | 2         | 0.65%   |
| 5.4.0-40-generic         | 2         | 0.65%   |
| 5.4.0-33-generic         | 2         | 0.65%   |
| 5.4.0-28-generic         | 2         | 0.65%   |
| 5.4.0-26-generic         | 2         | 0.65%   |
| 5.19.0-41-generic        | 2         | 0.65%   |
| 5.15.0-47-generic        | 2         | 0.65%   |
| 5.15.0-46-generic        | 2         | 0.65%   |
| 5.13.19-2-MANJARO        | 2         | 0.65%   |
| 5.13.0-7614-generic      | 2         | 0.65%   |
| 5.11.0-43-generic        | 2         | 0.65%   |
| 5.11.0-40-generic        | 2         | 0.65%   |
| 5.11.0-35-generic        | 2         | 0.65%   |
| 5.10.0-8-amd64           | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 11.64%  |
| 5.15.0  | 23        | 7.88%   |
| 5.13.0  | 17        | 5.82%   |
| 6.5.0   | 12        | 4.11%   |
| 5.11.0  | 12        | 4.11%   |
| 5.10.0  | 11        | 3.77%   |
| 4.15.0  | 10        | 3.42%   |
| 5.8.0   | 9         | 3.08%   |
| 6.8.0   | 8         | 2.74%   |
| 6.2.0   | 8         | 2.74%   |
| 6.1.0   | 8         | 2.74%   |
| 5.3.0   | 8         | 2.74%   |
| 4.18.0  | 8         | 2.74%   |
| 5.19.0  | 7         | 2.4%    |
| 5.0.0   | 5         | 1.71%   |
| 5.10.14 | 4         | 1.37%   |
| 6.4.11  | 3         | 1.03%   |
| 5.6.0   | 3         | 1.03%   |
| 5.16.7  | 3         | 1.03%   |
| 6.8.9   | 2         | 0.68%   |
| 6.3.9   | 2         | 0.68%   |
| 6.2.6   | 2         | 0.68%   |
| 6.12.1  | 2         | 0.68%   |
| 6.11.0  | 2         | 0.68%   |
| 6.0.11  | 2         | 0.68%   |
| 5.14.21 | 2         | 0.68%   |
| 5.13.19 | 2         | 0.68%   |
| 6.9.3   | 1         | 0.34%   |
| 6.9.10  | 1         | 0.34%   |
| 6.9.1   | 1         | 0.34%   |
| 6.8.8   | 1         | 0.34%   |
| 6.8.7   | 1         | 0.34%   |
| 6.7.1   | 1         | 0.34%   |
| 6.6.7   | 1         | 0.34%   |
| 6.6.26  | 1         | 0.34%   |
| 6.6.21  | 1         | 0.34%   |
| 6.5.9   | 1         | 0.34%   |
| 6.5.5   | 1         | 0.34%   |
| 6.4.7   | 1         | 0.34%   |
| 6.3.2   | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 12.41%  |
| 5.15    | 29        | 10%     |
| 5.13    | 20        | 6.9%    |
| 6.2     | 15        | 5.17%   |
| 5.10    | 15        | 5.17%   |
| 6.5     | 14        | 4.83%   |
| 6.1     | 14        | 4.83%   |
| 5.11    | 14        | 4.83%   |
| 5.8     | 13        | 4.48%   |
| 6.8     | 12        | 4.14%   |
| 5.19    | 10        | 3.45%   |
| 4.15    | 10        | 3.45%   |
| 5.3     | 9         | 3.1%    |
| 4.18    | 9         | 3.1%    |
| 5.16    | 8         | 2.76%   |
| 5.14    | 6         | 2.07%   |
| 5.0     | 5         | 1.72%   |
| 6.4     | 4         | 1.38%   |
| 6.3     | 4         | 1.38%   |
| 6.11    | 4         | 1.38%   |
| 5.9     | 4         | 1.38%   |
| 5.6     | 4         | 1.38%   |
| 5.17    | 4         | 1.38%   |
| 6.9     | 3         | 1.03%   |
| 6.6     | 3         | 1.03%   |
| 6.12    | 3         | 1.03%   |
| 6.0     | 3         | 1.03%   |
| 5.12    | 3         | 1.03%   |
| 6.10    | 2         | 0.69%   |
| 5.5     | 2         | 0.69%   |
| 4.19    | 2         | 0.69%   |
| 6.7     | 1         | 0.34%   |
| 5.7     | 1         | 0.34%   |
| 5.18    | 1         | 0.34%   |
| 4.9     | 1         | 0.34%   |
| 4.14    | 1         | 0.34%   |
| 4.1     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 247       | 97.24%  |
| i686   | 7         | 2.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 105       | 39.33%  |
| KDE5          | 56        | 20.97%  |
| Unknown       | 32        | 11.99%  |
| XFCE          | 22        | 8.24%   |
| X-Cinnamon    | 11        | 4.12%   |
| MATE          | 5         | 1.87%   |
| KDE6          | 5         | 1.87%   |
| LXQt          | 4         | 1.5%    |
| i3            | 4         | 1.5%    |
| KDE           | 3         | 1.12%   |
| Cinnamon      | 3         | 1.12%   |
| Budgie        | 3         | 1.12%   |
| Unity         | 2         | 0.75%   |
| Trinity       | 2         | 0.75%   |
| Pantheon      | 2         | 0.75%   |
| LXDE          | 2         | 0.75%   |
| Openbox       | 1         | 0.37%   |
| none+awesome  | 1         | 0.37%   |
| KDE4          | 1         | 0.37%   |
| Endless:GNOME | 1         | 0.37%   |
| DWM           | 1         | 0.37%   |
| bspwm         | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 179       | 67.04%  |
| Wayland | 63        | 23.6%   |
| Unknown | 20        | 7.49%   |
| Tty     | 5         | 1.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 40.45%  |
| SDDM    | 58        | 21.72%  |
| GDM3    | 32        | 11.99%  |
| GDM     | 31        | 11.61%  |
| LightDM | 28        | 10.49%  |
| TDM     | 10        | 3.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 142       | 54.83%  |
| sl_SI   | 60        | 23.17%  |
| Unknown | 28        | 10.81%  |
| en_GB   | 12        | 4.63%   |
| en_SI   | 4         | 1.54%   |
| C       | 4         | 1.54%   |
| it_IT   | 3         | 1.16%   |
| hr_HR   | 2         | 0.77%   |
| pt_PT   | 1         | 0.39%   |
| POSIX   | 1         | 0.39%   |
| nl_NL   | 1         | 0.39%   |
| en_BW   | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 143       | 55%     |
| BIOS | 117       | 45%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 195       | 73.86%  |
| Btrfs   | 30        | 11.36%  |
| Overlay | 18        | 6.82%   |
| Tmpfs   | 9         | 3.41%   |
| Unknown | 8         | 3.03%   |
| Zfs     | 1         | 0.38%   |
| Xfs     | 1         | 0.38%   |
| Rootfs  | 1         | 0.38%   |
| Ext2    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 117       | 44.32%  |
| GPT     | 109       | 41.29%  |
| MBR     | 38        | 14.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 240       | 91.95%  |
| Yes       | 21        | 8.05%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 185       | 70.88%  |
| Yes       | 76        | 29.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 74        | 29.13%  |
| Lenovo              | 67        | 26.38%  |
| ASUSTek Computer    | 36        | 14.17%  |
| Dell                | 26        | 10.24%  |
| Toshiba             | 10        | 3.94%   |
| Acer                | 10        | 3.94%   |
| Fujitsu             | 4         | 1.57%   |
| TUXEDO              | 3         | 1.18%   |
| HUAWEI              | 3         | 1.18%   |
| SLIMBOOK            | 2         | 0.79%   |
| MSI                 | 2         | 0.79%   |
| Medion              | 2         | 0.79%   |
| Fujitsu Siemens     | 2         | 0.79%   |
| Sony                | 1         | 0.39%   |
| Schenker            | 1         | 0.39%   |
| Razer               | 1         | 0.39%   |
| PC Specialist       | 1         | 0.39%   |
| Panasonic           | 1         | 0.39%   |
| Notebook            | 1         | 0.39%   |
| Gigabyte Technology | 1         | 0.39%   |
| Framework           | 1         | 0.39%   |
| eMachines           | 1         | 0.39%   |
| Dynabook            | 1         | 0.39%   |
| Clevo               | 1         | 0.39%   |
| Chuwi               | 1         | 0.39%   |
| Apple               | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                      | 4         | 1.57%   |
| Dell Inspiron 5570                         | 3         | 1.18%   |
| TUXEDO Aura 15 Gen1                        | 2         | 0.79%   |
| Toshiba Satellite L750                     | 2         | 0.79%   |
| Lenovo V15 G2 ALC 82KD                     | 2         | 0.79%   |
| Lenovo ThinkPad T410 2522A92               | 2         | 0.79%   |
| HP ProBook 4730s                           | 2         | 0.79%   |
| HP ProBook 450 G6                          | 2         | 0.79%   |
| HP Laptop 15-ra0xx                         | 2         | 0.79%   |
| HP EliteBook 8760w                         | 2         | 0.79%   |
| HP EliteBook 8570w                         | 2         | 0.79%   |
| HP Compaq nw8440 (RH415EA#ABB)             | 2         | 0.79%   |
| HP 255 G8 Notebook PC                      | 2         | 0.79%   |
| Dell XPS 13 9310                           | 2         | 0.79%   |
| Dell Latitude D630                         | 2         | 0.79%   |
| Dell Inspiron 1501                         | 2         | 0.79%   |
| ASUS VivoBook 17_ASUS Laptop X705MA_X705MA | 2         | 0.79%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.79%   |
| Unknown                                    | 2         | 0.79%   |
| TUXEDO Polaris AMD Gen2 (REN)              | 1         | 0.39%   |
| Toshiba TECRA S10                          | 1         | 0.39%   |
| Toshiba TECRA A11                          | 1         | 0.39%   |
| Toshiba Satellite R630                     | 1         | 0.39%   |
| Toshiba Satellite Pro U400                 | 1         | 0.39%   |
| Toshiba Satellite Pro R50-E                | 1         | 0.39%   |
| Toshiba Satellite L650                     | 1         | 0.39%   |
| Toshiba Satellite A100                     | 1         | 0.39%   |
| Toshiba QOSMIO X500                        | 1         | 0.39%   |
| Sony SVF1521V1EB                           | 1         | 0.39%   |
| SLIMBOOK HERO-S-TGL-RTX                    | 1         | 0.39%   |
| SLIMBOOK EXCALIBUR-16-AMD7                 | 1         | 0.39%   |
| Schenker XMG FUSION 15 (XFU15M22)          | 1         | 0.39%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.39%   |
| PC Specialist Fusion IV                    | 1         | 0.39%   |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.39%   |
| Notebook NS5x_NS7xPU                       | 1         | 0.39%   |
| MSI U210                                   | 1         | 0.39%   |
| MSI GP60 2OD                               | 1         | 0.39%   |
| Medion E7218                               | 1         | 0.39%   |
| Medion E6232                               | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 43        | 16.93%  |
| HP ProBook                 | 17        | 6.69%   |
| HP EliteBook               | 15        | 5.91%   |
| Lenovo IdeaPad             | 10        | 3.94%   |
| Dell Latitude              | 9         | 3.54%   |
| Dell Inspiron              | 8         | 3.15%   |
| Toshiba Satellite          | 7         | 2.76%   |
| HP ZBook                   | 7         | 2.76%   |
| ASUS VivoBook              | 7         | 2.76%   |
| HP Pavilion                | 6         | 2.36%   |
| HP Compaq                  | 6         | 2.36%   |
| HP 255                     | 6         | 2.36%   |
| Dell XPS                   | 6         | 2.36%   |
| ASUS ASUS                  | 5         | 1.97%   |
| Acer Aspire                | 5         | 1.97%   |
| HP Laptop                  | 4         | 1.57%   |
| HP 250                     | 4         | 1.57%   |
| Fujitsu LIFEBOOK           | 4         | 1.57%   |
| Lenovo Yoga                | 3         | 1.18%   |
| Lenovo Legion              | 3         | 1.18%   |
| ASUS Zenbook               | 3         | 1.18%   |
| TUXEDO Aura                | 2         | 0.79%   |
| Toshiba TECRA              | 2         | 0.79%   |
| Lenovo V15                 | 2         | 0.79%   |
| Dell Precision             | 2         | 0.79%   |
| ASUS ROG                   | 2         | 0.79%   |
| Acer Predator              | 2         | 0.79%   |
| Acer Nitro                 | 2         | 0.79%   |
| Unknown                    | 2         | 0.79%   |
| TUXEDO Polaris             | 1         | 0.39%   |
| Toshiba QOSMIO             | 1         | 0.39%   |
| Sony SVF1521V1EB           | 1         | 0.39%   |
| SLIMBOOK HERO-S-TGL-RTX    | 1         | 0.39%   |
| SLIMBOOK EXCALIBUR-16-AMD7 | 1         | 0.39%   |
| Schenker XMG               | 1         | 0.39%   |
| Razer Blade                | 1         | 0.39%   |
| PC Specialist Fusion       | 1         | 0.39%   |
| Panasonic CF-53SWWZ5MG     | 1         | 0.39%   |
| Notebook NS5x              | 1         | 0.39%   |
| MSI U210                   | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 27        | 10.63%  |
| 2018 | 22        | 8.66%   |
| 2021 | 21        | 8.27%   |
| 2020 | 21        | 8.27%   |
| 2011 | 17        | 6.69%   |
| 2017 | 16        | 6.3%    |
| 2013 | 14        | 5.51%   |
| 2012 | 14        | 5.51%   |
| 2010 | 14        | 5.51%   |
| 2022 | 12        | 4.72%   |
| 2015 | 12        | 4.72%   |
| 2014 | 12        | 4.72%   |
| 2008 | 12        | 4.72%   |
| 2009 | 10        | 3.94%   |
| 2016 | 8         | 3.15%   |
| 2023 | 7         | 2.76%   |
| 2007 | 7         | 2.76%   |
| 2006 | 6         | 2.36%   |
| 2024 | 2         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 254       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 230       | 88.8%   |
| Enabled  | 29        | 11.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 253       | 99.61%  |
| Yes  | 1         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 60        | 23.35%  |
| 8.01-16.0   | 52        | 20.23%  |
| 4.01-8.0    | 51        | 19.84%  |
| 16.01-24.0  | 46        | 17.9%   |
| 32.01-64.0  | 24        | 9.34%   |
| 1.01-2.0    | 8         | 3.11%   |
| 24.01-32.0  | 6         | 2.33%   |
| 2.01-3.0    | 4         | 1.56%   |
| 64.01-256.0 | 4         | 1.56%   |
| 0.51-1.0    | 2         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 84        | 29.58%  |
| 2.01-3.0   | 72        | 25.35%  |
| 4.01-8.0   | 42        | 14.79%  |
| 3.01-4.0   | 41        | 14.44%  |
| 0.51-1.0   | 21        | 7.39%   |
| 8.01-16.0  | 17        | 5.99%   |
| 0.01-0.5   | 3         | 1.06%   |
| 24.01-32.0 | 2         | 0.7%    |
| 16.01-24.0 | 2         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 203       | 77.78%  |
| 2      | 44        | 16.86%  |
| 3      | 8         | 3.07%   |
| 0      | 5         | 1.92%   |
| 4      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 60.63%  |
| Yes       | 100       | 39.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 218       | 85.16%  |
| No        | 38        | 14.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 98.43%  |
| No        | 4         | 1.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 215       | 83.66%  |
| No        | 42        | 16.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovenia | 254       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 99        | 34.86%  |
| Kranj                   | 21        | 7.39%   |
| Celje                   | 9         | 3.17%   |
| Poljane nad Skofjo Loko | 7         | 2.46%   |
| Trzin                   | 6         | 2.11%   |
| Maribor                 | 6         | 2.11%   |
| Žalec                  | 4         | 1.41%   |
| Vrhnika                 | 4         | 1.41%   |
| Portorož               | 4         | 1.41%   |
| Koper                   | 4         | 1.41%   |
| Turnisce                | 3         | 1.06%   |
| Slovenske Konjice       | 3         | 1.06%   |
| Škofja Loka            | 3         | 1.06%   |
| Sempeter pri Gorici     | 3         | 1.06%   |
| Novo Mesto              | 3         | 1.06%   |
| Murska Sobota           | 3         | 1.06%   |
| Medvode                 | 3         | 1.06%   |
| Ajdovščina            | 3         | 1.06%   |
| Velenje                 | 2         | 0.7%    |
| Smarje pri Jelsah       | 2         | 0.7%    |
| Slovenj Gradec          | 2         | 0.7%    |
| Skofljica               | 2         | 0.7%    |
| Sežana                 | 2         | 0.7%    |
| Ruše                   | 2         | 0.7%    |
| Puconci                 | 2         | 0.7%    |
| Petrovce                | 2         | 0.7%    |
| Nova Gorica             | 2         | 0.7%    |
| Lesce                   | 2         | 0.7%    |
| Kidricevo               | 2         | 0.7%    |
| Kamnik                  | 2         | 0.7%    |
| Grosuplje               | 2         | 0.7%    |
| Domžale                | 2         | 0.7%    |
| Blejska Dobrava         | 2         | 0.7%    |
| Žužemberk             | 1         | 0.35%   |
| Zrece                   | 1         | 0.35%   |
| Ziri                    | 1         | 0.35%   |
| Zgornji Leskovec        | 1         | 0.35%   |
| Zgornja Besnica         | 1         | 0.35%   |
| Zagorje ob Savi         | 1         | 0.35%   |
| Visoko                  | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 60        | 87     | 19.93%  |
| Seagate                     | 25        | 30     | 8.31%   |
| SanDisk                     | 23        | 27     | 7.64%   |
| Toshiba                     | 22        | 30     | 7.31%   |
| Kingston                    | 21        | 27     | 6.98%   |
| Crucial                     | 20        | 29     | 6.64%   |
| SK hynix                    | 19        | 26     | 6.31%   |
| WDC                         | 18        | 19     | 5.98%   |
| Micron Technology           | 10        | 11     | 3.32%   |
| Hitachi                     | 10        | 13     | 3.32%   |
| Unknown                     | 9         | 10     | 2.99%   |
| HGST                        | 9         | 10     | 2.99%   |
| Intel                       | 7         | 8      | 2.33%   |
| Intenso                     | 6         | 6      | 1.99%   |
| KIOXIA                      | 5         | 6      | 1.66%   |
| Fujitsu                     | 4         | 5      | 1.33%   |
| JMicron Technology          | 3         | 3      | 1%      |
| Transcend                   | 2         | 2      | 0.66%   |
| Silicon Motion              | 2         | 3      | 0.66%   |
| PNY                         | 2         | 2      | 0.66%   |
| OCZ                         | 2         | 2      | 0.66%   |
| Micron/Crucial Technology   | 2         | 2      | 0.66%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.66%   |
| LITEON                      | 2         | 2      | 0.66%   |
| Lenovo                      | 2         | 2      | 0.66%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.33%   |
| Union Memory                | 1         | 1      | 0.33%   |
| Team                        | 1         | 1      | 0.33%   |
| SABRENT                     | 1         | 1      | 0.33%   |
| Phison                      | 1         | 1      | 0.33%   |
| Patriot                     | 1         | 2      | 0.33%   |
| LITEONIT                    | 1         | 2      | 0.33%   |
| HGST HTS                    | 1         | 1      | 0.33%   |
| Gigabyte Technology         | 1         | 2      | 0.33%   |
| Corsair                     | 1         | 3      | 0.33%   |
| Apple                       | 1         | 1      | 0.33%   |
| Apacer                      | 1         | 1      | 0.33%   |
| A-DATA Technology           | 1         | 1      | 0.33%   |
| Unknown                     | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 6         | 1.94%   |
| Samsung SSD 850 EVO 250GB                            | 5         | 1.61%   |
| Samsung NVMe SSD Drive 512GB                         | 5         | 1.61%   |
| HGST HTS721010A9E630 1TB                             | 5         | 1.61%   |
| Kingston SA400S37240G 240GB SSD                      | 4         | 1.29%   |
| Toshiba MQ01ABF050 500GB                             | 3         | 0.97%   |
| Seagate ST2000LM015-2E8174 2TB                       | 3         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 0.97%   |
| Hitachi HTS547575A9E384 752GB                        | 3         | 0.97%   |
| Crucial CT240BX500SSD1 240GB                         | 3         | 0.97%   |
| Unknown MMC Card  32GB                               | 2         | 0.65%   |
| Unknown MMC Card  128GB                              | 2         | 0.65%   |
| Toshiba THNSN5256GPUK 256GB                          | 2         | 0.65%   |
| Toshiba MQ04ABF100 1TB                               | 2         | 0.65%   |
| SK hynix SC311 SATA 256GB SSD                        | 2         | 0.65%   |
| SK hynix HFM512GD3JX013N 512GB                       | 2         | 0.65%   |
| Seagate ST9750420AS 752GB                            | 2         | 0.65%   |
| Seagate ST9500325AS 500GB                            | 2         | 0.65%   |
| Seagate ST9320423AS 320GB                            | 2         | 0.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 2         | 0.65%   |
| SanDisk SD9SB8W256G1002 256GB SSD                    | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 0.65%   |
| Samsung SSD 860 EVO 500GB                            | 2         | 0.65%   |
| Samsung SSD 860 EVO 250GB                            | 2         | 0.65%   |
| Samsung SSD 850 EVO 500GB                            | 2         | 0.65%   |
| Samsung NVMe SSD Drive 256GB                         | 2         | 0.65%   |
| Samsung NVMe SSD Drive 1024GB                        | 2         | 0.65%   |
| Samsung MZVL21T0HCLR-00BL2 1TB                       | 2         | 0.65%   |
| PNY CS900 120GB SSD                                  | 2         | 0.65%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                        | 2         | 0.65%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 2         | 0.65%   |
| Lenovo NVMe SSD Drive 256GB                          | 2         | 0.65%   |
| Kingston SV300S37A60G 64GB SSD                       | 2         | 0.65%   |
| Kingston SA400S37480G 480GB SSD                      | 2         | 0.65%   |
| Kingston SA400S37120G 120GB SSD                      | 2         | 0.65%   |
| Intenso SSD 128GB                                    | 2         | 0.65%   |
| Hitachi HTS725032A9A364 320GB                        | 2         | 0.65%   |
| HGST HTS545050A7E680 500GB                           | 2         | 0.65%   |
| Crucial CT500MX500SSD1 500GB                         | 2         | 0.65%   |
| Crucial CT250BX100SSD1 250GB                         | 2         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 25        | 30     | 35.71%  |
| Toshiba            | 12        | 18     | 17.14%  |
| Hitachi            | 10        | 13     | 14.29%  |
| HGST               | 9         | 10     | 12.86%  |
| WDC                | 6         | 6      | 8.57%   |
| Fujitsu            | 4         | 5      | 5.71%   |
| SABRENT            | 1         | 1      | 1.43%   |
| JMicron Technology | 1         | 1      | 1.43%   |
| Intenso            | 1         | 1      | 1.43%   |
| HGST HTS           | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 36     | 23.42%  |
| Kingston            | 18        | 23     | 16.22%  |
| Crucial             | 18        | 27     | 16.22%  |
| SanDisk             | 13        | 15     | 11.71%  |
| WDC                 | 5         | 5      | 4.5%    |
| SK hynix            | 4         | 4      | 3.6%    |
| Intenso             | 4         | 4      | 3.6%    |
| Micron Technology   | 3         | 3      | 2.7%    |
| Transcend           | 2         | 2      | 1.8%    |
| PNY                 | 2         | 2      | 1.8%    |
| OCZ                 | 2         | 2      | 1.8%    |
| LITEON              | 2         | 2      | 1.8%    |
| Toshiba             | 1         | 1      | 0.9%    |
| Team                | 1         | 1      | 0.9%    |
| Phison              | 1         | 1      | 0.9%    |
| Patriot             | 1         | 2      | 0.9%    |
| LITEONIT            | 1         | 2      | 0.9%    |
| JMicron Technology  | 1         | 1      | 0.9%    |
| Intel               | 1         | 1      | 0.9%    |
| Gigabyte Technology | 1         | 2      | 0.9%    |
| Corsair             | 1         | 3      | 0.9%    |
| Apple               | 1         | 1      | 0.9%    |
| Apacer              | 1         | 1      | 0.9%    |
| A-DATA Technology   | 1         | 1      | 0.9%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 103       | 142    | 36.4%   |
| SSD     | 100       | 142    | 35.34%  |
| HDD     | 68        | 86     | 24.03%  |
| MMC     | 9         | 10     | 3.18%   |
| Unknown | 3         | 3      | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 152       | 221    | 55.88%  |
| NVMe | 103       | 142    | 37.87%  |
| MMC  | 9         | 10     | 3.31%   |
| SAS  | 8         | 10     | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 122       | 164    | 71.76%  |
| 0.51-1.0   | 38        | 48     | 22.35%  |
| 1.01-2.0   | 10        | 16     | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 27.41%  |
| 251-500        | 69        | 25.56%  |
| 501-1000       | 38        | 14.07%  |
| 1-20           | 20        | 7.41%   |
| 51-100         | 18        | 6.67%   |
| 1001-2000      | 16        | 5.93%   |
| 21-50          | 13        | 4.81%   |
| More than 3000 | 8         | 2.96%   |
| 2001-3000      | 8         | 2.96%   |
| Unknown        | 6         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 107       | 38.35%  |
| 21-50          | 44        | 15.77%  |
| 51-100         | 41        | 14.7%   |
| 101-250        | 39        | 13.98%  |
| 251-500        | 24        | 8.6%    |
| 501-1000       | 11        | 3.94%   |
| Unknown        | 6         | 2.15%   |
| 1001-2000      | 5         | 1.79%   |
| More than 3000 | 1         | 0.36%   |
| 2001-3000      | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                                      | 2         | 2      | 10%     |
| Toshiba MQ01ABF050 500GB                                        | 1         | 5      | 5%      |
| SK hynix HFS256G32MND-2200A 256GB SSD                           | 1         | 1      | 5%      |
| Seagate ST98823AS 80GB                                          | 1         | 3      | 5%      |
| Seagate ST9750420AS 752GB                                       | 1         | 1      | 5%      |
| Seagate ST9500423AS 500GB                                       | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB                                       | 1         | 2      | 5%      |
| Seagate ST9160314AS 160GB                                       | 1         | 1      | 5%      |
| Seagate ST2000LM015-2E8174 2TB                                  | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 1         | 1      | 5%      |
| SanDisk SD7SB2Q512G1001 512GB SSD                               | 1         | 1      | 5%      |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 1         | 1      | 5%      |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD                  | 1         | 1      | 5%      |
| Kingston SV300S37A120G 120GB SSD                                | 1         | 1      | 5%      |
| Hitachi HTS727550A9E364 500GB                                   | 1         | 1      | 5%      |
| Hitachi HTS543280L9SA00 80GB                                    | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 5%      |
| Crucial CT250BX100SSD1 250GB                                    | 1         | 1      | 5%      |
| Crucial CT120M500SSD1 120GB                                     | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 35%     |
| HGST                | 3         | 3      | 15%     |
| Hitachi             | 2         | 2      | 10%     |
| Crucial             | 2         | 2      | 10%     |
| Toshiba             | 1         | 5      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 10     | 53.85%  |
| HGST    | 3         | 3      | 23.08%  |
| Hitachi | 2         | 2      | 15.38%  |
| Toshiba | 1         | 5      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 20     | 65%     |
| SSD  | 6         | 6      | 30%     |
| NVMe | 1         | 1      | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MK6465GSX 640GB                          | 1         | 2      | 50%     |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 133       | 204    | 50%     |
| Works    | 111       | 149    | 41.73%  |
| Malfunc  | 20        | 27     | 7.52%   |
| Failed   | 2         | 3      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 167       | 55.3%   |
| Samsung Electronics              | 39        | 12.91%  |
| AMD                              | 27        | 8.94%   |
| SanDisk                          | 16        | 5.3%    |
| SK hynix                         | 15        | 4.97%   |
| Toshiba America Info Systems     | 12        | 3.97%   |
| Micron Technology                | 7         | 2.32%   |
| Micron/Crucial Technology        | 3         | 0.99%   |
| KIOXIA                           | 3         | 0.99%   |
| Kingston Technology Company      | 3         | 0.99%   |
| Union Memory (Shenzhen)          | 2         | 0.66%   |
| Silicon Motion                   | 2         | 0.66%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.66%   |
| Lenovo                           | 2         | 0.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Marvell Technology Group         | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 6.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 4.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 10        | 3.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.8%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 2.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 2.49%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 2.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 7         | 2.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 2.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 1.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.25%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 3         | 0.93%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 3         | 0.93%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 0.93%   |
| Intel SSD 660P Series                                                          | 3         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 3         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.93%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 3         | 0.93%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.62%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.62%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 2         | 0.62%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.62%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 166       | 53.38%  |
| NVMe | 106       | 34.08%  |
| IDE  | 22        | 7.07%   |
| RAID | 17        | 5.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 204       | 80.31%  |
| AMD    | 50        | 19.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 2.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.97%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.97%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 5         | 1.97%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 4         | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.57%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.18%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.18%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.18%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.18%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 1.18%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.18%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.18%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.18%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.18%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.18%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.79%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.79%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.79%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.79%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 0.79%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.79%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.79%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.79%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.79%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.79%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 66        | 25.98%  |
| Intel Core i5           | 53        | 20.87%  |
| Other                   | 21        | 8.27%   |
| Intel Core 2 Duo        | 18        | 7.09%   |
| Intel Core i3           | 16        | 6.3%    |
| Intel Celeron           | 15        | 5.91%   |
| AMD Ryzen 7             | 15        | 5.91%   |
| AMD Ryzen 5             | 9         | 3.54%   |
| AMD Ryzen 3             | 9         | 3.54%   |
| Intel Pentium           | 7         | 2.76%   |
| AMD Ryzen 9             | 4         | 1.57%   |
| Intel Genuine           | 3         | 1.18%   |
| Intel Core 2            | 2         | 0.79%   |
| AMD Ryzen 7 PRO         | 2         | 0.79%   |
| AMD A8                  | 2         | 0.79%   |
| Intel Pentium Silver    | 1         | 0.39%   |
| Intel Pentium Dual      | 1         | 0.39%   |
| Intel Core              | 1         | 0.39%   |
| AMD Turion II Dual-Core | 1         | 0.39%   |
| AMD Turion II           | 1         | 0.39%   |
| AMD Mobile Sempron      | 1         | 0.39%   |
| AMD E1                  | 1         | 0.39%   |
| AMD E                   | 1         | 0.39%   |
| AMD C-60                | 1         | 0.39%   |
| AMD Athlon Neo          | 1         | 0.39%   |
| AMD Athlon 64 X2        | 1         | 0.39%   |
| AMD A6                  | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 45.28%  |
| 4      | 88        | 34.65%  |
| 8      | 23        | 9.06%   |
| 6      | 15        | 5.91%   |
| 10     | 4         | 1.57%   |
| 12     | 3         | 1.18%   |
| 1      | 3         | 1.18%   |
| 16     | 2         | 0.79%   |
| 14     | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 254       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 196       | 77.17%  |
| 1      | 58        | 22.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 246       | 96.47%  |
| Unknown        | 6         | 2.35%   |
| 32-bit         | 3         | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 34.34%  |
| 0x206a7    | 13        | 4.91%   |
| 0x306a9    | 12        | 4.53%   |
| 0x806ec    | 11        | 4.15%   |
| 0x40651    | 9         | 3.4%    |
| 0x20655    | 9         | 3.4%    |
| 0x806ea    | 8         | 3.02%   |
| 0x306c3    | 8         | 3.02%   |
| 0x6fd      | 7         | 2.64%   |
| 0x806c1    | 6         | 2.26%   |
| 0x30678    | 5         | 1.89%   |
| 0x10676    | 5         | 1.89%   |
| 0x08108102 | 5         | 1.89%   |
| 0x906ea    | 4         | 1.51%   |
| 0x906e9    | 4         | 1.51%   |
| 0x406e3    | 4         | 1.51%   |
| 0x20652    | 4         | 1.51%   |
| 0x1067a    | 4         | 1.51%   |
| 0x08608103 | 4         | 1.51%   |
| 0xa0652    | 3         | 1.13%   |
| 0x706e5    | 3         | 1.13%   |
| 0x6e8      | 3         | 1.13%   |
| 0x306d4    | 3         | 1.13%   |
| 0x106e5    | 3         | 1.13%   |
| 0x0a50000c | 3         | 1.13%   |
| 0x08608102 | 3         | 1.13%   |
| 0x08600106 | 3         | 1.13%   |
| 0x906ed    | 2         | 0.75%   |
| 0x806eb    | 2         | 0.75%   |
| 0x706a1    | 2         | 0.75%   |
| 0x506c9    | 2         | 0.75%   |
| 0x0a404102 | 2         | 0.75%   |
| 0x0810100b | 2         | 0.75%   |
| 0x06001119 | 2         | 0.75%   |
| 0x05000119 | 2         | 0.75%   |
| 0xa0660    | 1         | 0.38%   |
| 0x906a4    | 1         | 0.38%   |
| 0x806e9    | 1         | 0.38%   |
| 0x6fb      | 1         | 0.38%   |
| 0x6f6      | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 48        | 18.9%   |
| Unknown           | 20        | 7.87%   |
| Haswell           | 19        | 7.48%   |
| SandyBridge       | 16        | 6.3%    |
| IvyBridge         | 16        | 6.3%    |
| Westmere          | 15        | 5.91%   |
| Core              | 11        | 4.33%   |
| Skylake           | 10        | 3.94%   |
| Silvermont        | 10        | 3.94%   |
| Penryn            | 10        | 3.94%   |
| TigerLake         | 9         | 3.54%   |
| Zen+              | 7         | 2.76%   |
| Zen 2             | 7         | 2.76%   |
| IceLake           | 7         | 2.76%   |
| Alderlake Hybrid  | 7         | 2.76%   |
| Broadwell         | 6         | 2.36%   |
| Zen 3             | 5         | 1.97%   |
| CometLake         | 5         | 1.97%   |
| Goldmont plus     | 4         | 1.57%   |
| Piledriver        | 3         | 1.18%   |
| P6                | 3         | 1.18%   |
| Nehalem           | 3         | 1.18%   |
| K8 Hammer         | 3         | 1.18%   |
| Zen               | 2         | 0.79%   |
| K10               | 2         | 0.79%   |
| Goldmont          | 2         | 0.79%   |
| Bobcat            | 2         | 0.79%   |
| Meteorlake Hybrid | 1         | 0.39%   |
| Jaguar            | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 176       | 53.17%  |
| AMD                              | 83        | 25.08%  |
| Nvidia                           | 71        | 21.45%  |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 3.81%   |
| Intel UHD Graphics 620                                                                   | 13        | 3.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 3.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.64%   |
| AMD Lucienne                                                                             | 9         | 2.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.05%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 7         | 2.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.05%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.76%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 1.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.47%   |
| Intel HD Graphics 530                                                                    | 5         | 1.47%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.17%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 1.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.17%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.17%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.88%   |
| Intel HD Graphics 620                                                                    | 3         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.88%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 0.88%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.59%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 2         | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 108       | 42.19%  |
| 1 x AMD        | 54        | 21.09%  |
| Intel + Nvidia | 49        | 19.14%  |
| Intel + AMD    | 18        | 7.03%   |
| 1 x Nvidia     | 13        | 5.08%   |
| AMD + Nvidia   | 9         | 3.52%   |
| 2 x Intel      | 2         | 0.78%   |
| 2 x AMD        | 2         | 0.78%   |
| 1 x SiS        | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 207       | 80.54%  |
| Proprietary | 40        | 15.56%  |
| Unknown     | 10        | 3.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 65.65%  |
| 1.01-2.0   | 28        | 10.69%  |
| 0.01-0.5   | 28        | 10.69%  |
| 0.51-1.0   | 15        | 5.73%   |
| 3.01-4.0   | 12        | 4.58%   |
| 5.01-6.0   | 4         | 1.53%   |
| 7.01-8.0   | 2         | 0.76%   |
| 2.01-3.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 60        | 20.13%  |
| LG Display              | 36        | 12.08%  |
| Samsung Electronics     | 33        | 11.07%  |
| Chimei Innolux          | 33        | 11.07%  |
| BOE                     | 33        | 11.07%  |
| Lenovo                  | 17        | 5.7%    |
| Dell                    | 14        | 4.7%    |
| Chi Mei Optoelectronics | 10        | 3.36%   |
| Sharp                   | 7         | 2.35%   |
| AOC                     | 7         | 2.35%   |
| Goldstar                | 6         | 2.01%   |
| CSO                     | 6         | 2.01%   |
| LG Philips              | 5         | 1.68%   |
| PANDA                   | 3         | 1.01%   |
| TMX                     | 2         | 0.67%   |
| InfoVision              | 2         | 0.67%   |
| Hewlett-Packard         | 2         | 0.67%   |
| HannStar                | 2         | 0.67%   |
| CPT                     | 2         | 0.67%   |
| ViewSonic               | 1         | 0.34%   |
| Unknown (XXX)           | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |
| Tianma XM               | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| Philips                 | 1         | 0.34%   |
| NEC Computers           | 1         | 0.34%   |
| Medion                  | 1         | 0.34%   |
| LGD                     | 1         | 0.34%   |
| Iiyama                  | 1         | 0.34%   |
| IBM                     | 1         | 0.34%   |
| HUAWEI                  | 1         | 0.34%   |
| HCG                     | 1         | 0.34%   |
| Gericom                 | 1         | 0.34%   |
| BenQ                    | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |
| Apple                   | 1         | 0.34%   |
| Acer                    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 2.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 1.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 3         | 0.99%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 3         | 0.99%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 3         | 0.99%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 3         | 0.99%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 0.99%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 2         | 0.66%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch         | 2         | 0.66%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch              | 2         | 0.66%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 2         | 0.66%   |
| Goldstar 34GN850 GSM774A 3440x1440 800x335mm 34.1-inch                    | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch           | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.66%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.66%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.66%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 2         | 0.66%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch             | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 2         | 0.66%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 2         | 0.66%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.33%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch                    | 1         | 0.33%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                   | 1         | 0.33%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 125       | 44.96%  |
| 1366x768 (WXGA)    | 48        | 17.27%  |
| 1600x900 (HD+)     | 20        | 7.19%   |
| 1920x1200 (WUXGA)  | 14        | 5.04%   |
| 3840x2160 (4K)     | 11        | 3.96%   |
| 2560x1440 (QHD)    | 10        | 3.6%    |
| 1440x900 (WXGA+)   | 9         | 3.24%   |
| 1280x800 (WXGA)    | 9         | 3.24%   |
| 1680x1050 (WSXGA+) | 7         | 2.52%   |
| 3440x1440          | 6         | 2.16%   |
| 2560x1600          | 5         | 1.8%    |
| 2880x1800          | 2         | 0.72%   |
| 1280x1024 (SXGA)   | 2         | 0.72%   |
| 3456x2160          | 1         | 0.36%   |
| 3072x1920          | 1         | 0.36%   |
| 3000x2000          | 1         | 0.36%   |
| 2520x1680          | 1         | 0.36%   |
| 2288x1287          | 1         | 0.36%   |
| 2256x1504          | 1         | 0.36%   |
| 2240x1400          | 1         | 0.36%   |
| 2160x1440          | 1         | 0.36%   |
| 2048x1152          | 1         | 0.36%   |
| 1400x1050          | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 125       | 41.67%  |
| 17      | 31        | 10.33%  |
| 14      | 31        | 10.33%  |
| 13      | 30        | 10%     |
| 24      | 15        | 5%      |
| 27      | 11        | 3.67%   |
| 23      | 9         | 3%      |
| 34      | 7         | 2.33%   |
| 16      | 7         | 2.33%   |
| 21      | 6         | 2%      |
| 22      | 4         | 1.33%   |
| 12      | 4         | 1.33%   |
| 19      | 3         | 1%      |
| 18      | 3         | 1%      |
| 54      | 2         | 0.67%   |
| 40      | 2         | 0.67%   |
| 33      | 2         | 0.67%   |
| Unknown | 2         | 0.67%   |
| 142     | 1         | 0.33%   |
| 65      | 1         | 0.33%   |
| 64      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 38      | 1         | 0.33%   |
| 11      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 174       | 58.78%  |
| 351-400        | 34        | 11.49%  |
| 501-600        | 30        | 10.14%  |
| 201-300        | 23        | 7.77%   |
| 401-500        | 13        | 4.39%   |
| 701-800        | 9         | 3.04%   |
| 801-900        | 4         | 1.35%   |
| 1001-1500      | 4         | 1.35%   |
| 601-700        | 2         | 0.68%   |
| Unknown        | 2         | 0.68%   |
| More than 2000 | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 202       | 75.37%  |
| 16/10   | 49        | 18.28%  |
| 21/9    | 7         | 2.61%   |
| 3/2     | 4         | 1.49%   |
| 5/4     | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 4/3     | 1         | 0.37%   |
| 1.00    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 123       | 41.14%  |
| 81-90          | 46        | 15.38%  |
| 121-130        | 27        | 9.03%   |
| 201-250        | 24        | 8.03%   |
| 71-80          | 13        | 4.35%   |
| 301-350        | 11        | 3.68%   |
| 351-500        | 9         | 3.01%   |
| 111-120        | 8         | 2.68%   |
| 251-300        | 7         | 2.34%   |
| 151-200        | 6         | 2.01%   |
| More than 1000 | 5         | 1.67%   |
| 61-70          | 4         | 1.34%   |
| 131-140        | 4         | 1.34%   |
| 501-1000       | 4         | 1.34%   |
| 91-100         | 3         | 1%      |
| 141-150        | 2         | 0.67%   |
| Unknown        | 2         | 0.67%   |
| 51-60          | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 122       | 41.64%  |
| 101-120       | 78        | 26.62%  |
| 51-100        | 56        | 19.11%  |
| 161-240       | 22        | 7.51%   |
| More than 240 | 9         | 3.07%   |
| 1-50          | 4         | 1.37%   |
| Unknown       | 2         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 206       | 77.74%  |
| 2     | 47        | 17.74%  |
| 3     | 7         | 2.64%   |
| 0     | 5         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 150       | 36.59%  |
| Realtek Semiconductor             | 127       | 30.98%  |
| Qualcomm Atheros                  | 45        | 10.98%  |
| Broadcom                          | 28        | 6.83%   |
| MediaTek                          | 10        | 2.44%   |
| ASIX Electronics                  | 5         | 1.22%   |
| Samsung Electronics               | 4         | 0.98%   |
| Ralink                            | 4         | 0.98%   |
| Marvell Technology Group          | 4         | 0.98%   |
| Huawei Technologies               | 4         | 0.98%   |
| Hewlett-Packard                   | 4         | 0.98%   |
| Qualcomm                          | 3         | 0.73%   |
| ASUSTek Computer                  | 3         | 0.73%   |
| Sierra Wireless                   | 2         | 0.49%   |
| Ralink Technology                 | 2         | 0.49%   |
| Lenovo                            | 2         | 0.49%   |
| Ericsson Business Mobile Networks | 2         | 0.49%   |
| Dell                              | 2         | 0.49%   |
| Broadcom Limited                  | 2         | 0.49%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.24%   |
| Xiaomi                            | 1         | 0.24%   |
| TP-Link                           | 1         | 0.24%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.24%   |
| JMicron Technology                | 1         | 0.24%   |
| ICS Advent                        | 1         | 0.24%   |
| Google                            | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 86        | 16.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16        | 3.15%   |
| Intel Wireless 8265 / 8275                                             | 14        | 2.76%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 11        | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.77%   |
| Intel Wireless 7260                                                    | 9         | 1.77%   |
| Intel Wireless 7265                                                    | 8         | 1.57%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 7         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 6         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.18%   |
| Intel Wireless 8260                                                    | 6         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.18%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 5         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.98%   |
| Intel Centrino Advanced-N 6200                                         | 5         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 4         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.79%   |
| Intel 82562GT 10/100 Network Connection                                | 4         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.59%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 54.34%  |
| Qualcomm Atheros      | 39        | 14.72%  |
| Realtek Semiconductor | 33        | 12.45%  |
| Broadcom              | 22        | 8.3%    |
| MediaTek              | 8         | 3.02%   |
| Ralink                | 4         | 1.51%   |
| ASUSTek Computer      | 3         | 1.13%   |
| Sierra Wireless       | 2         | 0.75%   |
| Ralink Technology     | 2         | 0.75%   |
| Qualcomm              | 2         | 0.75%   |
| Hewlett-Packard       | 2         | 0.75%   |
| Dell                  | 2         | 0.75%   |
| Broadcom Limited      | 2         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 14        | 5.28%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 4.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 4.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.4%    |
| Intel Wireless 7260                                                     | 9         | 3.4%    |
| Intel Wireless 7265                                                     | 8         | 3.02%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 3.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 3.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 2.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.26%   |
| Intel Wireless 8260                                                     | 6         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 2.26%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.89%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.13%   |
| Intel Wireless 3165                                                     | 3         | 1.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.13%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 0.75%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 117       | 50%     |
| Intel                            | 70        | 29.91%  |
| Qualcomm Atheros                 | 11        | 4.7%    |
| Broadcom                         | 9         | 3.85%   |
| ASIX Electronics                 | 5         | 2.14%   |
| Marvell Technology Group         | 4         | 1.71%   |
| Samsung Electronics              | 3         | 1.28%   |
| Huawei Technologies              | 3         | 1.28%   |
| MediaTek                         | 2         | 0.85%   |
| Lenovo                           | 2         | 0.85%   |
| Xiaomi                           | 1         | 0.43%   |
| TP-Link                          | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| Qualcomm                         | 1         | 0.43%   |
| JMicron Technology               | 1         | 0.43%   |
| ICS Advent                       | 1         | 0.43%   |
| Hewlett-Packard                  | 1         | 0.43%   |
| Google                           | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 86        | 36.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16        | 6.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 5.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 4.22%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 2.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 2.11%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 1.69%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.69%   |
| Intel 82562GT 10/100 Network Connection                                | 4         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.69%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.27%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 1.27%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 3         | 1.27%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.27%   |
| Huawei FOA-LX9                                                         | 3         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.84%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 0.84%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.84%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.84%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.84%   |
| Intel 82577LC Gigabit Network Connection                               | 2         | 0.84%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 2         | 0.84%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express               | 2         | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.84%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.42%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.42%   |
| Qualcomm POCO F3                                                       | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 52.84%  |
| Ethernet | 218       | 45.89%  |
| Modem    | 6         | 1.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 194       | 71.85%  |
| Ethernet | 75        | 27.78%  |
| Modem    | 1         | 0.37%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 201       | 78.82%  |
| 1     | 54        | 21.18%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 238       | 92.97%  |
| Yes  | 18        | 7.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 47.47%  |
| IMC Networks                    | 21        | 9.68%   |
| Realtek Semiconductor           | 19        | 8.76%   |
| Broadcom                        | 18        | 8.29%   |
| Qualcomm Atheros Communications | 17        | 7.83%   |
| Hewlett-Packard                 | 8         | 3.69%   |
| Foxconn / Hon Hai               | 6         | 2.76%   |
| Lite-On Technology              | 4         | 1.84%   |
| Toshiba                         | 3         | 1.38%   |
| Ralink                          | 3         | 1.38%   |
| Cambridge Silicon Radio         | 3         | 1.38%   |
| Foxconn International           | 2         | 0.92%   |
| ASUSTek Computer                | 2         | 0.92%   |
| Askey Computer                  | 2         | 0.92%   |
| USI                             | 1         | 0.46%   |
| Realtek                         | 1         | 0.46%   |
| Ralink Technology               | 1         | 0.46%   |
| Dell                            | 1         | 0.46%   |
| Chicony Electronics             | 1         | 0.46%   |
| Apple                           | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 17.51%  |
| Intel AX201 Bluetooth                               | 23        | 10.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.45%   |
| Intel AX200 Bluetooth                               | 13        | 5.99%   |
| Realtek Bluetooth Radio                             | 8         | 3.69%   |
| Intel AX211 Bluetooth                               | 7         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 2.76%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.76%   |
| IMC Networks Bluetooth Device                       | 6         | 2.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.3%    |
| IMC Networks Wireless_Device                        | 5         | 2.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 2.3%    |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 1.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.84%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 1.38%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.38%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.92%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.92%   |
| Intel AX210 Bluetooth                               | 2         | 0.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.92%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.92%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.92%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.92%   |
| Askey Bluetooth Device                              | 2         | 0.92%   |
| USI Bluetooth Device                                | 1         | 0.46%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.46%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.46%   |
| Realtek CSR BS8510                                  | 1         | 0.46%   |
| Realtek Bluetooth Radio                             | 1         | 0.46%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 203       | 65.48%  |
| AMD                              | 60        | 19.35%  |
| Nvidia                           | 35        | 11.29%  |
| Lenovo                           | 2         | 0.65%   |
| Hewlett-Packard                  | 2         | 0.65%   |
| Texas Instruments                | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Samsung Electronics              | 1         | 0.32%   |
| Logitech                         | 1         | 0.32%   |
| KTMicro                          | 1         | 0.32%   |
| JMTek                            | 1         | 0.32%   |
| Generalplus Technology           | 1         | 0.32%   |
| C-Media Electronics              | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 39        | 10.4%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 5.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 4.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 4.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 4%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 3.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.67%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.6%    |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.33%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.33%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.07%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.07%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.8%    |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 52        | 27.08%  |
| SK hynix            | 48        | 25%     |
| Micron Technology   | 27        | 14.06%  |
| Crucial             | 14        | 7.29%   |
| Kingston            | 13        | 6.77%   |
| Unknown             | 12        | 6.25%   |
| Nanya Technology    | 6         | 3.13%   |
| Ramaxel Technology  | 5         | 2.6%    |
| Elpida              | 4         | 2.08%   |
| Qimonda             | 2         | 1.04%   |
| A-DATA Technology   | 2         | 1.04%   |
| Wilk                | 1         | 0.52%   |
| Team                | 1         | 0.52%   |
| Shenzhen Longsys    | 1         | 0.52%   |
| Patriot             | 1         | 0.52%   |
| GOODRAM             | 1         | 0.52%   |
| ChangXin Memory     | 1         | 0.52%   |
| Unknown             | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.92%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 3         | 1.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 3         | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.44%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 3         | 1.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.44%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 3         | 1.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 2         | 0.96%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.96%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 0.96%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 0.96%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 2         | 0.96%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 2         | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s               | 2         | 0.96%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.96%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 2         | 0.96%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s      | 2         | 0.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 0.96%   |
| Micron RAM 16HTF25664HY-667E1 2048MB SODIMM DDR2 667MT/s  | 2         | 0.96%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 0.96%   |
| Kingston RAM HP16D3LS1KBGH/4G 4GB SODIMM DDR3 1600MT/s    | 2         | 0.96%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s   | 2         | 0.96%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 0.96%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s       | 1         | 0.48%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.48%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DRAM                     | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 72        | 45.57%  |
| DDR3   | 47        | 29.75%  |
| DDR2   | 12        | 7.59%   |
| LPDDR4 | 7         | 4.43%   |
| DDR5   | 7         | 4.43%   |
| LPDDR5 | 5         | 3.16%   |
| SDRAM  | 4         | 2.53%   |
| LPDDR3 | 3         | 1.9%    |
| DRAM   | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 144       | 90%     |
| Row Of Chips | 15        | 9.38%   |
| Chip         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 57        | 32.76%  |
| 4096  | 41        | 23.56%  |
| 16384 | 38        | 21.84%  |
| 2048  | 22        | 12.64%  |
| 32768 | 8         | 4.6%    |
| 1024  | 6         | 3.45%   |
| 512   | 2         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 36        | 20.57%  |
| 1600    | 31        | 17.71%  |
| 3200    | 27        | 15.43%  |
| 2400    | 12        | 6.86%   |
| 1334    | 12        | 6.86%   |
| 2133    | 8         | 4.57%   |
| 667     | 8         | 4.57%   |
| 1333    | 6         | 3.43%   |
| 6400    | 4         | 2.29%   |
| 4800    | 4         | 2.29%   |
| Unknown | 4         | 2.29%   |
| 5600    | 3         | 1.71%   |
| 4267    | 3         | 1.71%   |
| 1067    | 3         | 1.71%   |
| 4266    | 2         | 1.14%   |
| 4199    | 2         | 1.14%   |
| 2048    | 2         | 1.14%   |
| 975     | 2         | 1.14%   |
| 8400    | 1         | 0.57%   |
| 7500    | 1         | 0.57%   |
| 3733    | 1         | 0.57%   |
| 1867    | 1         | 0.57%   |
| 800     | 1         | 0.57%   |
| 533     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 50%     |
| Xerox           | 1         | 25%     |
| Canon           | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Xerox Phaser 3010       | 1         | 25%     |
| HP DeskJet F4200 series | 1         | 25%     |
| HP DeskJet F300 series  | 1         | 25%     |
| Canon PIXMA MP250       | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 50%     |
| Canon CanoScan 4200F               | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 70        | 32.26%  |
| IMC Networks                           | 27        | 12.44%  |
| Quanta                                 | 17        | 7.83%   |
| Realtek Semiconductor                  | 15        | 6.91%   |
| Microdia                               | 13        | 5.99%   |
| Bison Electronics                      | 12        | 5.53%   |
| Sunplus Innovation Technology          | 11        | 5.07%   |
| Lite-On Technology                     | 8         | 3.69%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.69%   |
| Acer                                   | 5         | 2.3%    |
| Syntek                                 | 4         | 1.84%   |
| Primax Electronics                     | 4         | 1.84%   |
| Lenovo                                 | 4         | 1.84%   |
| Suyin                                  | 3         | 1.38%   |
| Samsung Electronics                    | 2         | 0.92%   |
| Ricoh                                  | 2         | 0.92%   |
| Generalplus Technology                 | 2         | 0.92%   |
| Sonix Technology                       | 1         | 0.46%   |
| Silicon Motion                         | 1         | 0.46%   |
| ShineTech                              | 1         | 0.46%   |
| Qtech                                  | 1         | 0.46%   |
| Microsoft                              | 1         | 0.46%   |
| Luxvisions Innotech Limited            | 1         | 0.46%   |
| Logitech                               | 1         | 0.46%   |
| DX-230705-A                            | 1         | 0.46%   |
| BillionPixels                          | 1         | 0.46%   |
| Apple                                  | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 15        | 6.88%   |
| Microdia Integrated_Webcam_HD                    | 10        | 4.59%   |
| IMC Networks Integrated Camera                   | 8         | 3.67%   |
| IMC Networks USB2.0 HD UVC WebCam                | 7         | 3.21%   |
| Chicony HP HD Camera                             | 7         | 3.21%   |
| Bison Integrated Camera                          | 5         | 2.29%   |
| Sunplus HP HD Webcam [Fixed]                     | 4         | 1.83%   |
| Quanta HP TrueVision HD Camera                   | 4         | 1.83%   |
| Quanta HP HD Camera                              | 4         | 1.83%   |
| Primax HP HD Webcam [Fixed]                      | 4         | 1.83%   |
| Lite-On HP HD Webcam                             | 4         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 4         | 1.83%   |
| Syntek Lenovo EasyCamera                         | 3         | 1.38%   |
| Sunplus HD WebCam                                | 3         | 1.38%   |
| Lenovo Integrated Webcam [R5U877]                | 3         | 1.38%   |
| IMC Networks VGA UVC WebCam                      | 3         | 1.38%   |
| Chicony USB2.0 VGA UVC WebCam                    | 3         | 1.38%   |
| Chicony HP Webcam                                | 3         | 1.38%   |
| Chicony HP HD Webcam                             | 3         | 1.38%   |
| Bison SunplusIT Integrated Camera                | 3         | 1.38%   |
| Samsung Galaxy series, misc. (MTP mode)          | 2         | 0.92%   |
| Realtek USB Camera                               | 2         | 0.92%   |
| Realtek Integrated_Webcam_HD                     | 2         | 0.92%   |
| Realtek Asus laptop camera                       | 2         | 0.92%   |
| Quanta HP Webcam                                 | 2         | 0.92%   |
| Quanta ACER HD User Facing                       | 2         | 0.92%   |
| Lite-On Integrated Camera                        | 2         | 0.92%   |
| Lite-On HP HD Camera                             | 2         | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.92%   |
| IMC Networks Integrated Webcam                   | 2         | 0.92%   |
| Generalplus GENERAL WEBCAM                       | 2         | 0.92%   |
| Chicony USB2.0 UVC WebCam                        | 2         | 0.92%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 0.92%   |
| Chicony Lenovo EasyCamera                        | 2         | 0.92%   |
| Chicony Integrated IR Camera                     | 2         | 0.92%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 0.92%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 0.92%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 0.92%   |
| Chicony HP TrueVision HD Camera                  | 2         | 0.92%   |
| Chicony HD WebCam (Asus N-series)                | 2         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 31.25%  |
| Synaptics                  | 20        | 31.25%  |
| Shenzhen Goodix Technology | 8         | 12.5%   |
| AuthenTec                  | 7         | 10.94%  |
| Upek                       | 5         | 7.81%   |
| STMicroelectronics         | 2         | 3.13%   |
| Elan Microelectronics      | 2         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 9.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 7.81%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 7.81%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 7.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 4.69%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 4.69%   |
| Validity Sensors VFS491                                                    | 2         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.13%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.13%   |
| AuthenTec AES2810                                                          | 2         | 3.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 3.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.56%   |
| Synaptics UWP WBDI                                                         | 1         | 1.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.56%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.56%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.56%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.56%   |
| AuthenTec AES1600                                                          | 1         | 1.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 11        | 50%     |
| Broadcom    | 7         | 31.82%  |
| O2 Micro    | 3         | 13.64%  |
| Upek        | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 50%     |
| Broadcom 58200                                                               | 4         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4.55%   |
| Broadcom 5880                                                                | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 132       | 50.77%  |
| 1     | 88        | 33.85%  |
| 2     | 34        | 13.08%  |
| 3     | 5         | 1.92%   |
| 10    | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 64        | 36.57%  |
| Graphics card            | 34        | 19.43%  |
| Net/wireless             | 19        | 10.86%  |
| Chipcard                 | 18        | 10.29%  |
| Camera                   | 9         | 5.14%   |
| Multimedia controller    | 8         | 4.57%   |
| Bluetooth                | 7         | 4%      |
| Communication controller | 6         | 3.43%   |
| Card reader              | 4         | 2.29%   |
| Storage                  | 2         | 1.14%   |
| Sound                    | 1         | 0.57%   |
| Network                  | 1         | 0.57%   |
| Net/ethernet             | 1         | 0.57%   |
| Flash memory             | 1         | 0.57%   |

