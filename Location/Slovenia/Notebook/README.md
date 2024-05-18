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

Total: 363

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 28        | 11.34%  |
| Ubuntu 22.04       | 19        | 7.69%   |
| Ubuntu 18.04       | 14        | 5.67%   |
| Debian 11          | 8         | 3.24%   |
| Arch Rolling       | 8         | 3.24%   |
| Kubuntu 22.04      | 5         | 2.02%   |
| KDE neon 22.04     | 5         | 2.02%   |
| KDE neon 20.04     | 5         | 2.02%   |
| Fedora 37          | 5         | 2.02%   |
| Zorin 16           | 4         | 1.62%   |
| Zorin 15           | 4         | 1.62%   |
| OpenMandriva 4.3   | 4         | 1.62%   |
| Fedora 34          | 4         | 1.62%   |
| Fedora 33          | 4         | 1.62%   |
| ArcoLinux Rolling  | 4         | 1.62%   |
| Arch               | 4         | 1.62%   |
| Xubuntu 20.04      | 3         | 1.21%   |
| OpenMandriva 4.2   | 3         | 1.21%   |
| Linux Mint 19.1    | 3         | 1.21%   |
| Kubuntu 21.10      | 3         | 1.21%   |
| Kubuntu 20.04      | 3         | 1.21%   |
| Debian Testing     | 3         | 1.21%   |
| Debian 12          | 3         | 1.21%   |
| Xubuntu 22.04      | 2         | 0.81%   |
| Ubuntu Unity 16.04 | 2         | 0.81%   |
| Ubuntu 21.10       | 2         | 0.81%   |
| Ubuntu 21.04       | 2         | 0.81%   |
| Ubuntu 20.10       | 2         | 0.81%   |
| Ubuntu 19.10       | 2         | 0.81%   |
| Pop!_OS 22.04      | 2         | 0.81%   |
| Pop!_OS 21.04      | 2         | 0.81%   |
| Manjaro 20.2       | 2         | 0.81%   |
| Manjaro            | 2         | 0.81%   |
| LMDE 5             | 2         | 0.81%   |
| Linux Mint 21      | 2         | 0.81%   |
| Linux Mint 19.3    | 2         | 0.81%   |
| Kubuntu 18.04      | 2         | 0.81%   |
| Gentoo 2.6         | 2         | 0.81%   |
| Fedora 39          | 2         | 0.81%   |
| Fedora 38          | 2         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 67        | 28.51%  |
| Fedora        | 19        | 8.09%   |
| Kubuntu       | 16        | 6.81%   |
| Debian        | 16        | 6.81%   |
| Arch          | 12        | 5.11%   |
| Linux Mint    | 11        | 4.68%   |
| KDE neon      | 11        | 4.68%   |
| OpenMandriva  | 10        | 4.26%   |
| Manjaro       | 9         | 3.83%   |
| Endless       | 9         | 3.83%   |
| Zorin         | 8         | 3.4%    |
| Xubuntu       | 5         | 2.13%   |
| Pop!_OS       | 5         | 2.13%   |
| openSUSE      | 4         | 1.7%    |
| ArcoLinux     | 4         | 1.7%    |
| EndeavourOS   | 3         | 1.28%   |
| Ubuntu Unity  | 2         | 0.85%   |
| Ubuntu Budgie | 2         | 0.85%   |
| Q4OS          | 2         | 0.85%   |
| Lubuntu       | 2         | 0.85%   |
| LMDE          | 2         | 0.85%   |
| Kali          | 2         | 0.85%   |
| Gentoo        | 2         | 0.85%   |
| Garuda Linux  | 2         | 0.85%   |
| Elementary    | 2         | 0.85%   |
| Ubuntu MATE   | 1         | 0.43%   |
| ROSA          | 1         | 0.43%   |
| Nobara        | 1         | 0.43%   |
| NixOS         | 1         | 0.43%   |
| Clear Linux   | 1         | 0.43%   |
| Chrome OS     | 1         | 0.43%   |
| BlackPanther  | 1         | 0.43%   |
| Artix         | 1         | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 4         | 1.48%   |
| 4.18.0-15-generic        | 4         | 1.48%   |
| 5.8.0-41-generic         | 3         | 1.11%   |
| 5.3.0-40-generic         | 3         | 1.11%   |
| 5.16.7-desktop-1omv4003  | 3         | 1.11%   |
| 5.15.0-57-generic        | 3         | 1.11%   |
| 5.15.0-56-generic        | 3         | 1.11%   |
| 5.15.0-43-generic        | 3         | 1.11%   |
| 5.13.0-41-generic        | 3         | 1.11%   |
| 5.13.0-30-generic        | 3         | 1.11%   |
| 5.13.0-28-generic        | 3         | 1.11%   |
| 5.13.0-21-generic        | 3         | 1.11%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.11%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.74%   |
| 6.3.9-arch1-1            | 2         | 0.74%   |
| 6.2.0-36-generic         | 2         | 0.74%   |
| 6.2.0-31-generic         | 2         | 0.74%   |
| 5.8.0-44-generic         | 2         | 0.74%   |
| 5.8.0-14-generic         | 2         | 0.74%   |
| 5.6.0-1-amd64            | 2         | 0.74%   |
| 5.4.0-70-generic         | 2         | 0.74%   |
| 5.4.0-56-generic         | 2         | 0.74%   |
| 5.4.0-54-generic         | 2         | 0.74%   |
| 5.4.0-48-generic         | 2         | 0.74%   |
| 5.4.0-40-generic         | 2         | 0.74%   |
| 5.4.0-33-generic         | 2         | 0.74%   |
| 5.4.0-28-generic         | 2         | 0.74%   |
| 5.4.0-26-generic         | 2         | 0.74%   |
| 5.19.0-41-generic        | 2         | 0.74%   |
| 5.15.0-47-generic        | 2         | 0.74%   |
| 5.15.0-46-generic        | 2         | 0.74%   |
| 5.13.19-2-MANJARO        | 2         | 0.74%   |
| 5.13.0-7614-generic      | 2         | 0.74%   |
| 5.11.0-43-generic        | 2         | 0.74%   |
| 5.11.0-40-generic        | 2         | 0.74%   |
| 5.11.0-35-generic        | 2         | 0.74%   |
| 5.10.0-8-amd64           | 2         | 0.74%   |
| 4.15.0-128-generic       | 2         | 0.74%   |
| 6.8.8-200.fc39.x86_64    | 1         | 0.37%   |
| 6.8.7-arch1-1            | 1         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 13.28%  |
| 5.15.0  | 20        | 7.81%   |
| 5.13.0  | 17        | 6.64%   |
| 5.11.0  | 12        | 4.69%   |
| 5.10.0  | 10        | 3.91%   |
| 4.15.0  | 10        | 3.91%   |
| 5.8.0   | 9         | 3.52%   |
| 6.2.0   | 8         | 3.13%   |
| 5.3.0   | 8         | 3.13%   |
| 4.18.0  | 8         | 3.13%   |
| 6.5.0   | 7         | 2.73%   |
| 5.19.0  | 7         | 2.73%   |
| 6.1.0   | 5         | 1.95%   |
| 5.0.0   | 5         | 1.95%   |
| 5.10.14 | 4         | 1.56%   |
| 6.4.11  | 3         | 1.17%   |
| 5.6.0   | 3         | 1.17%   |
| 5.16.7  | 3         | 1.17%   |
| 6.3.9   | 2         | 0.78%   |
| 6.2.6   | 2         | 0.78%   |
| 6.0.11  | 2         | 0.78%   |
| 5.14.21 | 2         | 0.78%   |
| 5.13.19 | 2         | 0.78%   |
| 6.8.8   | 1         | 0.39%   |
| 6.8.7   | 1         | 0.39%   |
| 6.7.1   | 1         | 0.39%   |
| 6.6.7   | 1         | 0.39%   |
| 6.6.26  | 1         | 0.39%   |
| 6.5.9   | 1         | 0.39%   |
| 6.5.5   | 1         | 0.39%   |
| 6.4.7   | 1         | 0.39%   |
| 6.3.2   | 1         | 0.39%   |
| 6.3.1   | 1         | 0.39%   |
| 6.2.8   | 1         | 0.39%   |
| 6.2.2   | 1         | 0.39%   |
| 6.2.15  | 1         | 0.39%   |
| 6.2.11  | 1         | 0.39%   |
| 6.2.10  | 1         | 0.39%   |
| 6.1.9   | 1         | 0.39%   |
| 6.1.5   | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 14.17%  |
| 5.15    | 25        | 9.84%   |
| 5.13    | 20        | 7.87%   |
| 6.2     | 15        | 5.91%   |
| 5.11    | 14        | 5.51%   |
| 5.10    | 14        | 5.51%   |
| 5.8     | 13        | 5.12%   |
| 6.1     | 11        | 4.33%   |
| 5.19    | 10        | 3.94%   |
| 4.15    | 10        | 3.94%   |
| 6.5     | 9         | 3.54%   |
| 5.3     | 9         | 3.54%   |
| 4.18    | 9         | 3.54%   |
| 5.16    | 8         | 3.15%   |
| 5.14    | 6         | 2.36%   |
| 5.0     | 5         | 1.97%   |
| 6.4     | 4         | 1.57%   |
| 6.3     | 4         | 1.57%   |
| 5.9     | 4         | 1.57%   |
| 5.6     | 4         | 1.57%   |
| 5.17    | 4         | 1.57%   |
| 6.0     | 3         | 1.18%   |
| 5.12    | 3         | 1.18%   |
| 6.8     | 2         | 0.79%   |
| 6.6     | 2         | 0.79%   |
| 5.5     | 2         | 0.79%   |
| 4.19    | 2         | 0.79%   |
| 6.7     | 1         | 0.39%   |
| 5.7     | 1         | 0.39%   |
| 5.18    | 1         | 0.39%   |
| 4.9     | 1         | 0.39%   |
| 4.14    | 1         | 0.39%   |
| 4.1     | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 215       | 96.85%  |
| i686   | 7         | 3.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 93        | 39.91%  |
| KDE5          | 53        | 22.75%  |
| Unknown       | 28        | 12.02%  |
| XFCE          | 19        | 8.15%   |
| X-Cinnamon    | 8         | 3.43%   |
| MATE          | 4         | 1.72%   |
| LXQt          | 4         | 1.72%   |
| KDE           | 3         | 1.29%   |
| i3            | 3         | 1.29%   |
| Unity         | 2         | 0.86%   |
| Trinity       | 2         | 0.86%   |
| Pantheon      | 2         | 0.86%   |
| LXDE          | 2         | 0.86%   |
| Cinnamon      | 2         | 0.86%   |
| Budgie        | 2         | 0.86%   |
| Openbox       | 1         | 0.43%   |
| none+awesome  | 1         | 0.43%   |
| KDE6          | 1         | 0.43%   |
| Endless:GNOME | 1         | 0.43%   |
| DWM           | 1         | 0.43%   |
| bspwm         | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 162       | 69.23%  |
| Wayland | 48        | 20.51%  |
| Unknown | 19        | 8.12%   |
| Tty     | 5         | 2.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 41.45%  |
| SDDM    | 47        | 20.09%  |
| GDM3    | 28        | 11.97%  |
| GDM     | 28        | 11.97%  |
| LightDM | 24        | 10.26%  |
| TDM     | 10        | 4.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 123       | 54.42%  |
| sl_SI   | 52        | 23.01%  |
| Unknown | 27        | 11.95%  |
| en_GB   | 10        | 4.42%   |
| en_SI   | 4         | 1.77%   |
| it_IT   | 3         | 1.33%   |
| C       | 3         | 1.33%   |
| pt_PT   | 1         | 0.44%   |
| nl_NL   | 1         | 0.44%   |
| hr_HR   | 1         | 0.44%   |
| en_BW   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 122       | 53.51%  |
| BIOS | 106       | 46.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 176       | 76.19%  |
| Btrfs   | 22        | 9.52%   |
| Overlay | 14        | 6.06%   |
| Tmpfs   | 8         | 3.46%   |
| Unknown | 8         | 3.46%   |
| Zfs     | 1         | 0.43%   |
| Xfs     | 1         | 0.43%   |
| Ext2    | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 46.75%  |
| GPT     | 87        | 37.66%  |
| MBR     | 36        | 15.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 92.54%  |
| Yes       | 17        | 7.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 165       | 72.69%  |
| Yes       | 62        | 27.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 66        | 29.73%  |
| Lenovo              | 60        | 27.03%  |
| ASUSTek Computer    | 28        | 12.61%  |
| Dell                | 23        | 10.36%  |
| Acer                | 10        | 4.5%    |
| Toshiba             | 9         | 4.05%   |
| Fujitsu             | 4         | 1.8%    |
| HUAWEI              | 3         | 1.35%   |
| TUXEDO              | 2         | 0.9%    |
| MSI                 | 2         | 0.9%    |
| Medion              | 2         | 0.9%    |
| Fujitsu Siemens     | 2         | 0.9%    |
| Sony                | 1         | 0.45%   |
| SLIMBOOK            | 1         | 0.45%   |
| Schenker            | 1         | 0.45%   |
| Razer               | 1         | 0.45%   |
| PC Specialist       | 1         | 0.45%   |
| Panasonic           | 1         | 0.45%   |
| Gigabyte Technology | 1         | 0.45%   |
| Framework           | 1         | 0.45%   |
| eMachines           | 1         | 0.45%   |
| Dynabook            | 1         | 0.45%   |
| Chuwi               | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                      | 3         | 1.35%   |
| Toshiba Satellite L750                     | 2         | 0.9%    |
| Lenovo V15 G2 ALC 82KD                     | 2         | 0.9%    |
| Lenovo ThinkPad T410 2522A92               | 2         | 0.9%    |
| HP ProBook 4730s                           | 2         | 0.9%    |
| HP EliteBook 8760w                         | 2         | 0.9%    |
| HP EliteBook 8570w                         | 2         | 0.9%    |
| HP 255 G8 Notebook PC                      | 2         | 0.9%    |
| Dell XPS 13 9310                           | 2         | 0.9%    |
| Dell Latitude D630                         | 2         | 0.9%    |
| Dell Inspiron 5570                         | 2         | 0.9%    |
| Dell Inspiron 1501                         | 2         | 0.9%    |
| ASUS VivoBook 17_ASUS Laptop X705MA_X705MA | 2         | 0.9%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.9%    |
| Unknown                                    | 2         | 0.9%    |
| TUXEDO Polaris AMD Gen2 (REN)              | 1         | 0.45%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.45%   |
| Toshiba TECRA S10                          | 1         | 0.45%   |
| Toshiba TECRA A11                          | 1         | 0.45%   |
| Toshiba Satellite R630                     | 1         | 0.45%   |
| Toshiba Satellite Pro U400                 | 1         | 0.45%   |
| Toshiba Satellite Pro R50-E                | 1         | 0.45%   |
| Toshiba Satellite A100                     | 1         | 0.45%   |
| Toshiba QOSMIO X500                        | 1         | 0.45%   |
| Sony SVF1521V1EB                           | 1         | 0.45%   |
| SLIMBOOK HERO-S-TGL-RTX                    | 1         | 0.45%   |
| Schenker XMG FUSION 15 (XFU15M22)          | 1         | 0.45%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.45%   |
| PC Specialist Fusion IV                    | 1         | 0.45%   |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.45%   |
| MSI U210                                   | 1         | 0.45%   |
| MSI GP60 2OD                               | 1         | 0.45%   |
| Medion E7218                               | 1         | 0.45%   |
| Medion E6232                               | 1         | 0.45%   |
| Lenovo Yoga S740-14IIL 81RS                | 1         | 0.45%   |
| Lenovo Yoga 2 13 20344                     | 1         | 0.45%   |
| Lenovo ThinkPad X250 20CM004ESC            | 1         | 0.45%   |
| Lenovo ThinkPad X230 23202DG               | 1         | 0.45%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.45%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 39        | 17.57%  |
| HP ProBook              | 15        | 6.76%   |
| HP EliteBook            | 13        | 5.86%   |
| Lenovo IdeaPad          | 9         | 4.05%   |
| Dell Latitude           | 8         | 3.6%    |
| HP ZBook                | 7         | 3.15%   |
| Dell Inspiron           | 7         | 3.15%   |
| Toshiba Satellite       | 6         | 2.7%    |
| HP Pavilion             | 6         | 2.7%    |
| ASUS VivoBook           | 6         | 2.7%    |
| HP 255                  | 5         | 2.25%   |
| Dell XPS                | 5         | 2.25%   |
| Acer Aspire             | 5         | 2.25%   |
| HP Compaq               | 4         | 1.8%    |
| HP 250                  | 4         | 1.8%    |
| Fujitsu LIFEBOOK        | 4         | 1.8%    |
| ASUS ASUS               | 4         | 1.8%    |
| HP Laptop               | 3         | 1.35%   |
| Toshiba TECRA           | 2         | 0.9%    |
| Lenovo Yoga             | 2         | 0.9%    |
| Lenovo V15              | 2         | 0.9%    |
| Lenovo Legion           | 2         | 0.9%    |
| Dell Precision          | 2         | 0.9%    |
| Acer Predator           | 2         | 0.9%    |
| Acer Nitro              | 2         | 0.9%    |
| Unknown                 | 2         | 0.9%    |
| TUXEDO Polaris          | 1         | 0.45%   |
| TUXEDO Aura             | 1         | 0.45%   |
| Toshiba QOSMIO          | 1         | 0.45%   |
| Sony SVF1521V1EB        | 1         | 0.45%   |
| SLIMBOOK HERO-S-TGL-RTX | 1         | 0.45%   |
| Schenker XMG            | 1         | 0.45%   |
| Razer Blade             | 1         | 0.45%   |
| PC Specialist Fusion    | 1         | 0.45%   |
| Panasonic CF-53SWWZ5MG  | 1         | 0.45%   |
| MSI U210                | 1         | 0.45%   |
| MSI GP60                | 1         | 0.45%   |
| Medion E7218            | 1         | 0.45%   |
| Medion E6232            | 1         | 0.45%   |
| Lenovo G585             | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 25        | 11.26%  |
| 2020 | 20        | 9.01%   |
| 2021 | 19        | 8.56%   |
| 2018 | 17        | 7.66%   |
| 2011 | 17        | 7.66%   |
| 2017 | 13        | 5.86%   |
| 2013 | 13        | 5.86%   |
| 2012 | 13        | 5.86%   |
| 2010 | 13        | 5.86%   |
| 2014 | 12        | 5.41%   |
| 2008 | 12        | 5.41%   |
| 2015 | 10        | 4.5%    |
| 2009 | 9         | 4.05%   |
| 2022 | 7         | 3.15%   |
| 2016 | 6         | 2.7%    |
| 2007 | 6         | 2.7%    |
| 2023 | 5         | 2.25%   |
| 2006 | 5         | 2.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 222       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 203       | 89.43%  |
| Enabled  | 24        | 10.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 221       | 99.55%  |
| Yes  | 1         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 55        | 24.55%  |
| 8.01-16.0   | 45        | 20.09%  |
| 4.01-8.0    | 42        | 18.75%  |
| 16.01-24.0  | 42        | 18.75%  |
| 32.01-64.0  | 21        | 9.38%   |
| 1.01-2.0    | 8         | 3.57%   |
| 2.01-3.0    | 4         | 1.79%   |
| 24.01-32.0  | 3         | 1.34%   |
| 64.01-256.0 | 2         | 0.89%   |
| 0.51-1.0    | 2         | 0.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 76        | 30.4%   |
| 2.01-3.0   | 68        | 27.2%   |
| 4.01-8.0   | 34        | 13.6%   |
| 3.01-4.0   | 32        | 12.8%   |
| 0.51-1.0   | 21        | 8.4%    |
| 8.01-16.0  | 13        | 5.2%    |
| 0.01-0.5   | 3         | 1.2%    |
| 24.01-32.0 | 2         | 0.8%    |
| 16.01-24.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 178       | 78.07%  |
| 2      | 38        | 16.67%  |
| 3      | 7         | 3.07%   |
| 0      | 5         | 2.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 127       | 57.21%  |
| Yes       | 95        | 42.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 86.61%  |
| No        | 30        | 13.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 99.55%  |
| No        | 1         | 0.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 83.93%  |
| No        | 36        | 16.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovenia | 222       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 85        | 34.41%  |
| Kranj                   | 18        | 7.29%   |
| Celje                   | 8         | 3.24%   |
| Trzin                   | 6         | 2.43%   |
| Poljane nad Skofjo Loko | 6         | 2.43%   |
| Maribor                 | 5         | 2.02%   |
| Vrhnika                 | 4         | 1.62%   |
| Žalec                  | 3         | 1.21%   |
| Slovenske Konjice       | 3         | 1.21%   |
| Škofja Loka            | 3         | 1.21%   |
| Portorož               | 3         | 1.21%   |
| Murska Sobota           | 3         | 1.21%   |
| Koper                   | 3         | 1.21%   |
| Ajdovščina            | 3         | 1.21%   |
| Velenje                 | 2         | 0.81%   |
| Turnisce                | 2         | 0.81%   |
| Smarje pri Jelsah       | 2         | 0.81%   |
| Slovenj Gradec          | 2         | 0.81%   |
| Sežana                 | 2         | 0.81%   |
| Sempeter pri Gorici     | 2         | 0.81%   |
| Puconci                 | 2         | 0.81%   |
| Petrovce                | 2         | 0.81%   |
| Nova Gorica             | 2         | 0.81%   |
| Medvode                 | 2         | 0.81%   |
| Lesce                   | 2         | 0.81%   |
| Kamnik                  | 2         | 0.81%   |
| Grosuplje               | 2         | 0.81%   |
| Domžale                | 2         | 0.81%   |
| Blejska Dobrava         | 2         | 0.81%   |
| Žužemberk             | 1         | 0.4%    |
| Ziri                    | 1         | 0.4%    |
| Zgornji Leskovec        | 1         | 0.4%    |
| Zgornja Besnica         | 1         | 0.4%    |
| Zagorje ob Savi         | 1         | 0.4%    |
| Visoko                  | 1         | 0.4%    |
| Vipava                  | 1         | 0.4%    |
| Trzic                   | 1         | 0.4%    |
| Trbovlje                | 1         | 0.4%    |
| Tabor                   | 1         | 0.4%    |
| Solkan                  | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 47        | 66     | 18.01%  |
| Seagate                     | 23        | 28     | 8.81%   |
| Toshiba                     | 19        | 27     | 7.28%   |
| Kingston                    | 19        | 25     | 7.28%   |
| Crucial                     | 19        | 28     | 7.28%   |
| WDC                         | 18        | 19     | 6.9%    |
| SK hynix                    | 16        | 21     | 6.13%   |
| SanDisk                     | 16        | 20     | 6.13%   |
| Hitachi                     | 10        | 13     | 3.83%   |
| HGST                        | 9         | 10     | 3.45%   |
| Unknown                     | 8         | 9      | 3.07%   |
| Micron Technology           | 8         | 9      | 3.07%   |
| Intel                       | 6         | 7      | 2.3%    |
| KIOXIA                      | 4         | 4      | 1.53%   |
| Intenso                     | 4         | 4      | 1.53%   |
| Fujitsu                     | 4         | 5      | 1.53%   |
| JMicron Technology          | 3         | 3      | 1.15%   |
| Transcend                   | 2         | 2      | 0.77%   |
| Silicon Motion              | 2         | 3      | 0.77%   |
| PNY                         | 2         | 2      | 0.77%   |
| OCZ                         | 2         | 2      | 0.77%   |
| Micron/Crucial Technology   | 2         | 2      | 0.77%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.77%   |
| LITEON                      | 2         | 2      | 0.77%   |
| Lenovo                      | 2         | 2      | 0.77%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.38%   |
| Union Memory                | 1         | 1      | 0.38%   |
| Team                        | 1         | 1      | 0.38%   |
| SABRENT                     | 1         | 1      | 0.38%   |
| Phison                      | 1         | 1      | 0.38%   |
| Patriot                     | 1         | 2      | 0.38%   |
| LITEONIT                    | 1         | 2      | 0.38%   |
| HGST HTS                    | 1         | 1      | 0.38%   |
| Gigabyte Technology         | 1         | 2      | 0.38%   |
| Corsair                     | 1         | 3      | 0.38%   |
| A-DATA Technology           | 1         | 1      | 0.38%   |
| Unknown                     | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                       | 5         | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 5         | 1.87%   |
| HGST HTS721010A9E630 1TB                           | 5         | 1.87%   |
| Samsung SSD 850 EVO 250GB                          | 4         | 1.49%   |
| Kingston SA400S37240G 240GB SSD                    | 4         | 1.49%   |
| Hitachi HTS547575A9E384 752GB                      | 3         | 1.12%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 1.12%   |
| Unknown MMC Card  32GB                             | 2         | 0.75%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 0.75%   |
| Toshiba MQ01ABF050 500GB                           | 2         | 0.75%   |
| SK hynix SC311 SATA 256GB SSD                      | 2         | 0.75%   |
| Seagate ST9750420AS 752GB                          | 2         | 0.75%   |
| Seagate ST9500325AS 500GB                          | 2         | 0.75%   |
| Seagate ST9320423AS 320GB                          | 2         | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 0.75%   |
| SanDisk SD9SB8W256G1002 256GB SSD                  | 2         | 0.75%   |
| SanDisk NVMe SSD Drive 512GB                       | 2         | 0.75%   |
| Samsung SSD 860 EVO 250GB                          | 2         | 0.75%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 0.75%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 2         | 0.75%   |
| Samsung NVMe SSD Drive 1024GB                      | 2         | 0.75%   |
| PNY CS900 120GB SSD                                | 2         | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB | 2         | 0.75%   |
| Lenovo NVMe SSD Drive 256GB                        | 2         | 0.75%   |
| Kingston SV300S37A60G 64GB SSD                     | 2         | 0.75%   |
| Kingston SA400S37120G 120GB SSD                    | 2         | 0.75%   |
| Intenso SSD 128GB                                  | 2         | 0.75%   |
| Hitachi HTS725032A9A364 320GB                      | 2         | 0.75%   |
| HGST HTS545050A7E680 500GB                         | 2         | 0.75%   |
| Crucial CT250BX100SSD1 250GB                       | 2         | 0.75%   |
| Crucial CT2000MX500SSD1 2TB                        | 2         | 0.75%   |
| WDC WDS500G3X0C-00SJG0 500GB                       | 1         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 1         | 0.37%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 0.37%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                   | 1         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 1         | 0.37%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 1         | 0.37%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                     | 1         | 0.37%   |
| WDC WD7500BPVX-60JC3T0 752GB                       | 1         | 0.37%   |
| WDC WD3200BEKT-22KA9T0 320GB                       | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 23        | 28     | 34.85%  |
| Toshiba            | 11        | 17     | 16.67%  |
| Hitachi            | 10        | 13     | 15.15%  |
| HGST               | 9         | 10     | 13.64%  |
| WDC                | 6         | 6      | 9.09%   |
| Fujitsu            | 4         | 5      | 6.06%   |
| SABRENT            | 1         | 1      | 1.52%   |
| JMicron Technology | 1         | 1      | 1.52%   |
| HGST HTS           | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 26     | 21.05%  |
| Crucial             | 17        | 26     | 17.89%  |
| Kingston            | 16        | 21     | 16.84%  |
| SanDisk             | 9         | 11     | 9.47%   |
| WDC                 | 5         | 5      | 5.26%   |
| SK hynix            | 4         | 4      | 4.21%   |
| Micron Technology   | 3         | 3      | 3.16%   |
| Intenso             | 3         | 3      | 3.16%   |
| Transcend           | 2         | 2      | 2.11%   |
| PNY                 | 2         | 2      | 2.11%   |
| OCZ                 | 2         | 2      | 2.11%   |
| LITEON              | 2         | 2      | 2.11%   |
| Toshiba             | 1         | 1      | 1.05%   |
| Team                | 1         | 1      | 1.05%   |
| Phison              | 1         | 1      | 1.05%   |
| Patriot             | 1         | 2      | 1.05%   |
| LITEONIT            | 1         | 2      | 1.05%   |
| JMicron Technology  | 1         | 1      | 1.05%   |
| Intel               | 1         | 1      | 1.05%   |
| Gigabyte Technology | 1         | 2      | 1.05%   |
| Corsair             | 1         | 3      | 1.05%   |
| A-DATA Technology   | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 87        | 122    | 35.37%  |
| NVMe    | 85        | 117    | 34.55%  |
| HDD     | 64        | 82     | 26.02%  |
| MMC     | 7         | 8      | 2.85%   |
| Unknown | 3         | 3      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 137       | 198    | 58.05%  |
| NVMe | 85        | 117    | 36.02%  |
| SAS  | 7         | 9      | 2.97%   |
| MMC  | 7         | 8      | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 107       | 146    | 71.33%  |
| 0.51-1.0   | 35        | 44     | 23.33%  |
| 1.01-2.0   | 8         | 14     | 5.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 28.27%  |
| 251-500        | 64        | 27%     |
| 501-1000       | 33        | 13.92%  |
| 1-20           | 16        | 6.75%   |
| 51-100         | 16        | 6.75%   |
| 1001-2000      | 14        | 5.91%   |
| 21-50          | 10        | 4.22%   |
| 2001-3000      | 7         | 2.95%   |
| More than 3000 | 5         | 2.11%   |
| Unknown        | 5         | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 96        | 39.18%  |
| 21-50          | 39        | 15.92%  |
| 51-100         | 36        | 14.69%  |
| 101-250        | 34        | 13.88%  |
| 251-500        | 22        | 8.98%   |
| 501-1000       | 8         | 3.27%   |
| Unknown        | 5         | 2.04%   |
| 1001-2000      | 3         | 1.22%   |
| More than 3000 | 1         | 0.41%   |
| 2001-3000      | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 2         | 2      | 11.11%  |
| Toshiba MQ01ABF050 500GB                       | 1         | 5      | 5.56%   |
| SK hynix HFS256G32MND-2200A 256GB SSD          | 1         | 1      | 5.56%   |
| Seagate ST98823AS 80GB                         | 1         | 3      | 5.56%   |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 5.56%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB                      | 1         | 2      | 5.56%   |
| Seagate ST9160314AS 160GB                      | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 5.56%   |
| SanDisk SD7SB2Q512G1001 512GB SSD              | 1         | 1      | 5.56%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 5.56%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 5.56%   |
| Hitachi HTS727550A9E364 500GB                  | 1         | 1      | 5.56%   |
| Hitachi HTS543280L9SA00 80GB                   | 1         | 1      | 5.56%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 5.56%   |
| Crucial CT250BX100SSD1 250GB                   | 1         | 1      | 5.56%   |
| Crucial CT120M500SSD1 120GB                    | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 9      | 33.33%  |
| HGST              | 3         | 3      | 16.67%  |
| Hitachi           | 2         | 2      | 11.11%  |
| Crucial           | 2         | 2      | 11.11%  |
| Toshiba           | 1         | 5      | 5.56%   |
| SK hynix          | 1         | 1      | 5.56%   |
| SanDisk           | 1         | 1      | 5.56%   |
| Micron Technology | 1         | 1      | 5.56%   |
| Kingston          | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 9      | 50%     |
| HGST    | 3         | 3      | 25%     |
| Hitachi | 2         | 2      | 16.67%  |
| Toshiba | 1         | 5      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 19     | 66.67%  |
| SSD  | 6         | 6      | 33.33%  |

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
| Detected | 123       | 186    | 52.79%  |
| Works    | 90        | 118    | 38.63%  |
| Malfunc  | 18        | 25     | 7.73%   |
| Failed   | 2         | 3      | 0.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 149       | 56.23%  |
| Samsung Electronics              | 31        | 11.7%   |
| AMD                              | 26        | 9.81%   |
| SanDisk                          | 14        | 5.28%   |
| SK hynix                         | 12        | 4.53%   |
| Toshiba America Info Systems     | 10        | 3.77%   |
| Micron Technology                | 5         | 1.89%   |
| Micron/Crucial Technology        | 3         | 1.13%   |
| Kingston Technology Company      | 3         | 1.13%   |
| Union Memory (Shenzhen)          | 2         | 0.75%   |
| Silicon Motion                   | 2         | 0.75%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.75%   |
| Lenovo                           | 2         | 0.75%   |
| KIOXIA                           | 2         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| Marvell Technology Group         | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20        | 7.12%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 7.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 5.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 4.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 3.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 2.49%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 2.14%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 1.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.42%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 3         | 1.07%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 1.07%   |
| Intel SSD 660P Series                                                          | 3         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.07%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 3         | 1.07%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.71%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 0.71%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.71%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.71%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 2         | 0.71%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                 | 2         | 0.71%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 149       | 54.78%  |
| NVMe | 88        | 32.35%  |
| IDE  | 20        | 7.35%   |
| RAID | 15        | 5.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 182       | 81.98%  |
| AMD    | 40        | 18.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 2.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 2.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.25%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 2.25%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 5         | 2.25%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 4         | 1.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.8%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.35%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.35%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.35%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.35%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.35%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.35%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.9%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.9%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.9%    |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.9%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.9%    |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.9%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.9%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.9%    |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.9%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.9%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 0.9%    |
| Intel 12th Gen Core i7-1255U                  | 2         | 0.9%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 60        | 27.03%  |
| Intel Core i5           | 46        | 20.72%  |
| Other                   | 18        | 8.11%   |
| Intel Core 2 Duo        | 17        | 7.66%   |
| Intel Core i3           | 15        | 6.76%   |
| Intel Celeron           | 13        | 5.86%   |
| AMD Ryzen 7             | 9         | 4.05%   |
| AMD Ryzen 5             | 9         | 4.05%   |
| AMD Ryzen 3             | 8         | 3.6%    |
| Intel Pentium           | 7         | 3.15%   |
| Intel Genuine           | 3         | 1.35%   |
| AMD Ryzen 9             | 3         | 1.35%   |
| AMD A8                  | 2         | 0.9%    |
| Intel Pentium Silver    | 1         | 0.45%   |
| Intel Pentium Dual      | 1         | 0.45%   |
| Intel Core 2            | 1         | 0.45%   |
| AMD Turion II Dual-Core | 1         | 0.45%   |
| AMD Turion II           | 1         | 0.45%   |
| AMD Mobile Sempron      | 1         | 0.45%   |
| AMD E1                  | 1         | 0.45%   |
| AMD E                   | 1         | 0.45%   |
| AMD C-60                | 1         | 0.45%   |
| AMD Athlon Neo          | 1         | 0.45%   |
| AMD Athlon 64 X2        | 1         | 0.45%   |
| AMD A6                  | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 105       | 47.3%   |
| 4      | 79        | 35.59%  |
| 6      | 15        | 6.76%   |
| 8      | 14        | 6.31%   |
| 10     | 3         | 1.35%   |
| 1      | 3         | 1.35%   |
| 12     | 2         | 0.9%    |
| 16     | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 222       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 169       | 76.13%  |
| 1      | 53        | 23.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 214       | 95.96%  |
| Unknown        | 6         | 2.69%   |
| 32-bit         | 3         | 1.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 28.33%  |
| 0x206a7    | 13        | 5.58%   |
| 0x806ec    | 11        | 4.72%   |
| 0x306a9    | 11        | 4.72%   |
| 0x40651    | 9         | 3.86%   |
| 0x20655    | 9         | 3.86%   |
| 0x306c3    | 8         | 3.43%   |
| 0x806ea    | 7         | 3%      |
| 0x6fd      | 7         | 3%      |
| 0x806c1    | 6         | 2.58%   |
| 0x30678    | 5         | 2.15%   |
| 0x10676    | 5         | 2.15%   |
| 0x08108102 | 5         | 2.15%   |
| 0x906ea    | 4         | 1.72%   |
| 0x906e9    | 4         | 1.72%   |
| 0x406e3    | 4         | 1.72%   |
| 0x20652    | 4         | 1.72%   |
| 0x1067a    | 4         | 1.72%   |
| 0xa0652    | 3         | 1.29%   |
| 0x706e5    | 3         | 1.29%   |
| 0x6e8      | 3         | 1.29%   |
| 0x306d4    | 3         | 1.29%   |
| 0x106e5    | 3         | 1.29%   |
| 0x0a50000c | 3         | 1.29%   |
| 0x08608103 | 3         | 1.29%   |
| 0x08608102 | 3         | 1.29%   |
| 0x08600106 | 3         | 1.29%   |
| 0x906ed    | 2         | 0.86%   |
| 0x806eb    | 2         | 0.86%   |
| 0x706a1    | 2         | 0.86%   |
| 0x506c9    | 2         | 0.86%   |
| 0x0810100b | 2         | 0.86%   |
| 0x06001119 | 2         | 0.86%   |
| 0x05000119 | 2         | 0.86%   |
| 0xa0660    | 1         | 0.43%   |
| 0x906a4    | 1         | 0.43%   |
| 0x6fb      | 1         | 0.43%   |
| 0x406c4    | 1         | 0.43%   |
| 0x0a704101 | 1         | 0.43%   |
| 0x0a404102 | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 18.02%  |
| Haswell          | 18        | 8.11%   |
| SandyBridge      | 16        | 7.21%   |
| IvyBridge        | 15        | 6.76%   |
| Westmere         | 13        | 5.86%   |
| Unknown          | 12        | 5.41%   |
| Penryn           | 10        | 4.5%    |
| TigerLake        | 9         | 4.05%   |
| Skylake          | 9         | 4.05%   |
| Core             | 9         | 4.05%   |
| Silvermont       | 8         | 3.6%    |
| IceLake          | 7         | 3.15%   |
| Zen+             | 6         | 2.7%    |
| Zen 2            | 6         | 2.7%    |
| CometLake        | 5         | 2.25%   |
| Broadwell        | 5         | 2.25%   |
| Alderlake Hybrid | 5         | 2.25%   |
| Zen 3            | 4         | 1.8%    |
| Goldmont plus    | 4         | 1.8%    |
| Piledriver       | 3         | 1.35%   |
| P6               | 3         | 1.35%   |
| Nehalem          | 3         | 1.35%   |
| K8 Hammer        | 3         | 1.35%   |
| Zen              | 2         | 0.9%    |
| K10              | 2         | 0.9%    |
| Goldmont         | 2         | 0.9%    |
| Bobcat           | 2         | 0.9%    |
| Jaguar           | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 158       | 54.67%  |
| AMD                              | 68        | 23.53%  |
| Nvidia                           | 62        | 21.45%  |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 13        | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 13        | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 3.68%   |
| Intel UHD Graphics 620                                                                | 10        | 3.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 3.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 9         | 3.01%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 3.01%   |
| AMD Lucienne                                                                          | 8         | 2.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 2.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 2.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 6         | 2.01%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 6         | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 2.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 5         | 1.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 5         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 1.67%   |
| Intel HD Graphics 5500                                                                | 5         | 1.67%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 1.34%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 4         | 1.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 4         | 1.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 1.34%   |
| Intel HD Graphics 530                                                                 | 4         | 1.34%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 3         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 1%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 3         | 1%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 3         | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1%      |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 3         | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 0.67%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 2         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.67%   |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 0.67%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 2         | 0.67%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 2         | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 0.67%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                             | 2         | 0.67%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 43.75%  |
| Intel + Nvidia | 42        | 18.75%  |
| 1 x AMD        | 42        | 18.75%  |
| Intel + AMD    | 17        | 7.59%   |
| 1 x Nvidia     | 13        | 5.8%    |
| AMD + Nvidia   | 7         | 3.13%   |
| 2 x Intel      | 2         | 0.89%   |
| 2 x AMD        | 2         | 0.89%   |
| 1 x SiS        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 182       | 80.89%  |
| Proprietary | 35        | 15.56%  |
| Unknown     | 8         | 3.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 147       | 64.19%  |
| 1.01-2.0   | 26        | 11.35%  |
| 0.01-0.5   | 24        | 10.48%  |
| 0.51-1.0   | 14        | 6.11%   |
| 3.01-4.0   | 11        | 4.8%    |
| 5.01-6.0   | 4         | 1.75%   |
| 7.01-8.0   | 2         | 0.87%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 21.79%  |
| LG Display              | 31        | 12.06%  |
| Samsung Electronics     | 29        | 11.28%  |
| Chimei Innolux          | 29        | 11.28%  |
| BOE                     | 24        | 9.34%   |
| Lenovo                  | 15        | 5.84%   |
| Dell                    | 12        | 4.67%   |
| Chi Mei Optoelectronics | 10        | 3.89%   |
| Sharp                   | 7         | 2.72%   |
| LG Philips              | 4         | 1.56%   |
| Goldstar                | 4         | 1.56%   |
| CSO                     | 4         | 1.56%   |
| AOC                     | 4         | 1.56%   |
| TMX                     | 2         | 0.78%   |
| PANDA                   | 2         | 0.78%   |
| InfoVision              | 2         | 0.78%   |
| Hewlett-Packard         | 2         | 0.78%   |
| HannStar                | 2         | 0.78%   |
| CPT                     | 2         | 0.78%   |
| ViewSonic               | 1         | 0.39%   |
| Unknown (XXX)           | 1         | 0.39%   |
| Unknown                 | 1         | 0.39%   |
| Tianma XM               | 1         | 0.39%   |
| Sony                    | 1         | 0.39%   |
| Philips                 | 1         | 0.39%   |
| NEC Computers           | 1         | 0.39%   |
| Medion                  | 1         | 0.39%   |
| LGD                     | 1         | 0.39%   |
| Iiyama                  | 1         | 0.39%   |
| IBM                     | 1         | 0.39%   |
| HUAWEI                  | 1         | 0.39%   |
| Gericom                 | 1         | 0.39%   |
| BenQ                    | 1         | 0.39%   |
| ASUSTek Computer        | 1         | 0.39%   |
| Acer                    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 2.67%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 1.53%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 1.15%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 2         | 0.76%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 0.76%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 0.76%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 2         | 0.76%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch           | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.76%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.76%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.76%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.76%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.76%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 0.76%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch             | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 2         | 0.76%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.38%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.38%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch                    | 1         | 0.38%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                   | 1         | 0.38%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.38%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch               | 1         | 0.38%   |
| Sony TV SNYAA01 1360x768                                                  | 1         | 0.38%   |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch                   | 1         | 0.38%   |
| Sharp LCD Monitor SHP153A 1366x768 309x174mm 14.0-inch                    | 1         | 0.38%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 1         | 0.38%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.38%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                   | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 109       | 45.42%  |
| 1366x768 (WXGA)    | 47        | 19.58%  |
| 1600x900 (HD+)     | 20        | 8.33%   |
| 1280x800 (WXGA)    | 9         | 3.75%   |
| 1920x1200 (WUXGA)  | 8         | 3.33%   |
| 3840x2160 (4K)     | 7         | 2.92%   |
| 2560x1440 (QHD)    | 7         | 2.92%   |
| 1440x900 (WXGA+)   | 7         | 2.92%   |
| 3440x1440          | 6         | 2.5%    |
| 1680x1050 (WSXGA+) | 5         | 2.08%   |
| 2560x1600          | 3         | 1.25%   |
| 1280x1024 (SXGA)   | 2         | 0.83%   |
| 3456x2160          | 1         | 0.42%   |
| 3000x2000          | 1         | 0.42%   |
| 2880x1800          | 1         | 0.42%   |
| 2520x1680          | 1         | 0.42%   |
| 2288x1287          | 1         | 0.42%   |
| 2256x1504          | 1         | 0.42%   |
| 2240x1400          | 1         | 0.42%   |
| 2160x1440          | 1         | 0.42%   |
| 2048x1152          | 1         | 0.42%   |
| 1400x1050          | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 112       | 43.24%  |
| 17      | 29        | 11.2%   |
| 13      | 27        | 10.42%  |
| 14      | 25        | 9.65%   |
| 24      | 13        | 5.02%   |
| 27      | 7         | 2.7%    |
| 23      | 7         | 2.7%    |
| 34      | 6         | 2.32%   |
| 21      | 5         | 1.93%   |
| 12      | 4         | 1.54%   |
| 22      | 3         | 1.16%   |
| 19      | 3         | 1.16%   |
| 18      | 3         | 1.16%   |
| 16      | 3         | 1.16%   |
| 54      | 2         | 0.77%   |
| 40      | 2         | 0.77%   |
| Unknown | 2         | 0.77%   |
| 142     | 1         | 0.39%   |
| 65      | 1         | 0.39%   |
| 39      | 1         | 0.39%   |
| 38      | 1         | 0.39%   |
| 33      | 1         | 0.39%   |
| 11      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 149       | 58.2%   |
| 351-400        | 32        | 12.5%   |
| 501-600        | 24        | 9.38%   |
| 201-300        | 22        | 8.59%   |
| 401-500        | 11        | 4.3%    |
| 701-800        | 7         | 2.73%   |
| 801-900        | 4         | 1.56%   |
| 1001-1500      | 3         | 1.17%   |
| Unknown        | 2         | 0.78%   |
| More than 2000 | 1         | 0.39%   |
| 601-700        | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 180       | 77.92%  |
| 16/10   | 35        | 15.15%  |
| 21/9    | 6         | 2.6%    |
| 3/2     | 4         | 1.73%   |
| 5/4     | 2         | 0.87%   |
| Unknown | 2         | 0.87%   |
| 4/3     | 1         | 0.43%   |
| 1.00    | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 42.64%  |
| 81-90          | 39        | 15.12%  |
| 121-130        | 26        | 10.08%  |
| 201-250        | 20        | 7.75%   |
| 71-80          | 12        | 4.65%   |
| 351-500        | 7         | 2.71%   |
| 301-350        | 7         | 2.71%   |
| 151-200        | 6         | 2.33%   |
| 251-300        | 5         | 1.94%   |
| More than 1000 | 4         | 1.55%   |
| 61-70          | 4         | 1.55%   |
| 111-120        | 4         | 1.55%   |
| 501-1000       | 4         | 1.55%   |
| 131-140        | 3         | 1.16%   |
| 141-150        | 2         | 0.78%   |
| 91-100         | 2         | 0.78%   |
| Unknown        | 2         | 0.78%   |
| 51-60          | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 41.11%  |
| 101-120       | 74        | 29.25%  |
| 51-100        | 47        | 18.58%  |
| 161-240       | 15        | 5.93%   |
| More than 240 | 7         | 2.77%   |
| 1-50          | 4         | 1.58%   |
| Unknown       | 2         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 182       | 78.79%  |
| 2     | 40        | 17.32%  |
| 3     | 5         | 2.16%   |
| 0     | 4         | 1.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 131       | 36.49%  |
| Realtek Semiconductor             | 112       | 31.2%   |
| Qualcomm Atheros                  | 42        | 11.7%   |
| Broadcom                          | 25        | 6.96%   |
| MediaTek                          | 7         | 1.95%   |
| Ralink                            | 4         | 1.11%   |
| Marvell Technology Group          | 4         | 1.11%   |
| Huawei Technologies               | 4         | 1.11%   |
| Samsung Electronics               | 3         | 0.84%   |
| Hewlett-Packard                   | 3         | 0.84%   |
| ASUSTek Computer                  | 3         | 0.84%   |
| Sierra Wireless                   | 2         | 0.56%   |
| Ralink Technology                 | 2         | 0.56%   |
| Lenovo                            | 2         | 0.56%   |
| Ericsson Business Mobile Networks | 2         | 0.56%   |
| Dell                              | 2         | 0.56%   |
| Broadcom Limited                  | 2         | 0.56%   |
| ASIX Electronics                  | 2         | 0.56%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.28%   |
| Xiaomi                            | 1         | 0.28%   |
| TP-Link                           | 1         | 0.28%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.28%   |
| JMicron Technology                | 1         | 0.28%   |
| ICS Advent                        | 1         | 0.28%   |
| Google                            | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 76        | 17%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 3.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 2.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 11        | 2.46%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.46%   |
| Intel Wireless 8265 / 8275                                             | 10        | 2.24%   |
| Intel Wireless 7260                                                    | 9         | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.79%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 1.79%   |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.34%   |
| Intel Wireless 8260                                                    | 6         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 5         | 1.12%   |
| Intel Wireless 7265                                                    | 5         | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 5         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 5         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 4         | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.89%   |
| Intel Centrino Advanced-N 6200                                         | 4         | 0.89%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.67%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.67%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 3         | 0.67%   |
| Intel Wireless 3165                                                    | 3         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 125       | 53.19%  |
| Qualcomm Atheros      | 37        | 15.74%  |
| Realtek Semiconductor | 29        | 12.34%  |
| Broadcom              | 20        | 8.51%   |
| MediaTek              | 7         | 2.98%   |
| Ralink                | 4         | 1.7%    |
| ASUSTek Computer      | 3         | 1.28%   |
| Sierra Wireless       | 2         | 0.85%   |
| Ralink Technology     | 2         | 0.85%   |
| Hewlett-Packard       | 2         | 0.85%   |
| Dell                  | 2         | 0.85%   |
| Broadcom Limited      | 2         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 4.68%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 4.68%   |
| Intel Wireless 8265 / 8275                                              | 10        | 4.26%   |
| Intel Wireless 7260                                                     | 9         | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.4%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 3.4%    |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 3.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.55%   |
| Intel Wireless 8260                                                     | 6         | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 2.13%   |
| Intel Wireless 7265                                                     | 5         | 2.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.7%    |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.28%   |
| Intel Wireless 3165                                                     | 3         | 1.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.28%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 0.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.85%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.85%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.85%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 103       | 50%     |
| Intel                            | 64        | 31.07%  |
| Qualcomm Atheros                 | 10        | 4.85%   |
| Broadcom                         | 8         | 3.88%   |
| Marvell Technology Group         | 4         | 1.94%   |
| Samsung Electronics              | 3         | 1.46%   |
| Huawei Technologies              | 3         | 1.46%   |
| Lenovo                           | 2         | 0.97%   |
| ASIX Electronics                 | 2         | 0.97%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.49%   |
| Xiaomi                           | 1         | 0.49%   |
| TP-Link                          | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| JMicron Technology               | 1         | 0.49%   |
| ICS Advent                       | 1         | 0.49%   |
| Google                           | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 76        | 36.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 7.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 5.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 3.85%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 2.4%    |
| Intel 82577LM Gigabit Network Connection                               | 5         | 2.4%    |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.92%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.44%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 1.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 1.44%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 3         | 1.44%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1.44%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.44%   |
| Intel 82562GT 10/100 Network Connection                                | 3         | 1.44%   |
| Huawei VTR-L09                                                         | 3         | 1.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.96%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 0.96%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.96%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.96%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.96%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.96%   |
| Intel 82577LC Gigabit Network Connection                               | 2         | 0.96%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 2         | 0.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.96%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 2         | 0.96%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                    | 1         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.48%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.48%   |
| Lenovo ThinkPad TBT3 LAN                                               | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 222       | 52.86%  |
| Ethernet | 194       | 46.19%  |
| Modem    | 4         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 72.69%  |
| Ethernet | 65        | 27.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 181       | 81.17%  |
| 1     | 42        | 18.83%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 214       | 95.54%  |
| Yes  | 10        | 4.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 46.32%  |
| IMC Networks                    | 18        | 9.47%   |
| Broadcom                        | 18        | 9.47%   |
| Realtek Semiconductor           | 16        | 8.42%   |
| Qualcomm Atheros Communications | 16        | 8.42%   |
| Hewlett-Packard                 | 6         | 3.16%   |
| Foxconn / Hon Hai               | 5         | 2.63%   |
| Lite-On Technology              | 4         | 2.11%   |
| Toshiba                         | 3         | 1.58%   |
| Ralink                          | 3         | 1.58%   |
| Cambridge Silicon Radio         | 3         | 1.58%   |
| Foxconn International           | 2         | 1.05%   |
| ASUSTek Computer                | 2         | 1.05%   |
| Askey Computer                  | 2         | 1.05%   |
| Realtek                         | 1         | 0.53%   |
| Ralink Technology               | 1         | 0.53%   |
| Dell                            | 1         | 0.53%   |
| Chicony Electronics             | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 22        | 11.58%  |
| Intel Bluetooth wireless interface                  | 16        | 8.42%   |
| Intel Bluetooth Device                              | 14        | 7.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 6.32%   |
| Intel AX200 Bluetooth                               | 11        | 5.79%   |
| Realtek Bluetooth Radio                             | 6         | 3.16%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 3.16%   |
| IMC Networks Bluetooth Radio                        | 6         | 3.16%   |
| Intel AX211 Bluetooth                               | 5         | 2.63%   |
| IMC Networks Bluetooth Device                       | 5         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.11%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 2.11%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.58%   |
| IMC Networks Wireless_Device                        | 3         | 1.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.58%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 1.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.58%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 1.05%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.05%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.05%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.05%   |
| Intel AX210 Bluetooth                               | 2         | 1.05%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.05%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.05%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.05%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.05%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.05%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.05%   |
| Askey Bluetooth Device                              | 2         | 1.05%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.53%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.53%   |
| Realtek CSR BS8510                                  | 1         | 0.53%   |
| Realtek Bluetooth Radio                             | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 181       | 66.79%  |
| AMD                              | 48        | 17.71%  |
| Nvidia                           | 31        | 11.44%  |
| Lenovo                           | 2         | 0.74%   |
| Hewlett-Packard                  | 2         | 0.74%   |
| Texas Instruments                | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Samsung Electronics              | 1         | 0.37%   |
| Logitech                         | 1         | 0.37%   |
| JMTek                            | 1         | 0.37%   |
| DCMT Technology                  | 1         | 0.37%   |
| C-Media Electronics              | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 29        | 8.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 4.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 4.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 4.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 3.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 3.07%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 3.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 2.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 2.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 8         | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.53%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.53%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.53%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.23%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.92%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.92%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 0.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 26.99%  |
| SK hynix            | 42        | 25.77%  |
| Micron Technology   | 23        | 14.11%  |
| Unknown             | 11        | 6.75%   |
| Crucial             | 11        | 6.75%   |
| Kingston            | 8         | 4.91%   |
| Nanya Technology    | 6         | 3.68%   |
| Ramaxel Technology  | 4         | 2.45%   |
| Elpida              | 4         | 2.45%   |
| Qimonda             | 2         | 1.23%   |
| A-DATA Technology   | 2         | 1.23%   |
| Wilk                | 1         | 0.61%   |
| Team                | 1         | 0.61%   |
| Shenzhen Longsys    | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |
| GOODRAM             | 1         | 0.61%   |
| ChangXin Memory     | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 3         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.69%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 3         | 1.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.69%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 3         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 2         | 1.12%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.12%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 1.12%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 1.12%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 2         | 1.12%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.12%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 2         | 1.12%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.12%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s  | 2         | 1.12%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 2         | 1.12%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s      | 2         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.12%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 1.12%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s   | 2         | 1.12%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 1.12%   |
| Wilk RAM GR3200S464L22S/8G 8GB SODIMM DDR4 3200MT/s       | 1         | 0.56%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.56%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.56%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.56%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DRAM                     | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.56%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                | 1         | 0.56%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 1         | 0.56%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s      | 1         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s              | 1         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 0.56%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 0.56%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 62        | 46.62%  |
| DDR3   | 42        | 31.58%  |
| DDR2   | 11        | 8.27%   |
| LPDDR4 | 5         | 3.76%   |
| SDRAM  | 4         | 3.01%   |
| LPDDR3 | 3         | 2.26%   |
| DDR5   | 3         | 2.26%   |
| LPDDR5 | 2         | 1.5%    |
| DRAM   | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 122       | 89.71%  |
| Row Of Chips | 13        | 9.56%   |
| Chip         | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 31.08%  |
| 4096  | 35        | 23.65%  |
| 16384 | 34        | 22.97%  |
| 2048  | 21        | 14.19%  |
| 1024  | 6         | 4.05%   |
| 32768 | 4         | 2.7%    |
| 512   | 2         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 29        | 19.59%  |
| 1600    | 27        | 18.24%  |
| 3200    | 25        | 16.89%  |
| 1334    | 12        | 8.11%   |
| 2400    | 10        | 6.76%   |
| 1333    | 7         | 4.73%   |
| 667     | 7         | 4.73%   |
| 2133    | 6         | 4.05%   |
| Unknown | 4         | 2.7%    |
| 4267    | 3         | 2.03%   |
| 4800    | 2         | 1.35%   |
| 4199    | 2         | 1.35%   |
| 2048    | 2         | 1.35%   |
| 1067    | 2         | 1.35%   |
| 8400    | 1         | 0.68%   |
| 7500    | 1         | 0.68%   |
| 6400    | 1         | 0.68%   |
| 5600    | 1         | 0.68%   |
| 4266    | 1         | 0.68%   |
| 3733    | 1         | 0.68%   |
| 1867    | 1         | 0.68%   |
| 975     | 1         | 0.68%   |
| 800     | 1         | 0.68%   |
| 533     | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Xerox           | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Xerox Phaser 3010       | 1         | 33.33%  |
| HP DeskJet F4200 series | 1         | 33.33%  |
| Canon PIXMA MP250       | 1         | 33.33%  |

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
| Chicony Electronics                    | 62        | 32.46%  |
| IMC Networks                           | 23        | 12.04%  |
| Quanta                                 | 17        | 8.9%    |
| Realtek Semiconductor                  | 14        | 7.33%   |
| Microdia                               | 12        | 6.28%   |
| Sunplus Innovation Technology          | 10        | 5.24%   |
| Bison Electronics                      | 10        | 5.24%   |
| Lite-On Technology                     | 7         | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.66%   |
| Syntek                                 | 4         | 2.09%   |
| Primax Electronics                     | 4         | 2.09%   |
| Lenovo                                 | 4         | 2.09%   |
| Suyin                                  | 3         | 1.57%   |
| Ricoh                                  | 2         | 1.05%   |
| Generalplus Technology                 | 2         | 1.05%   |
| Acer                                   | 2         | 1.05%   |
| Sonix Technology                       | 1         | 0.52%   |
| Silicon Motion                         | 1         | 0.52%   |
| ShineTech                              | 1         | 0.52%   |
| Samsung Electronics                    | 1         | 0.52%   |
| Qtech                                  | 1         | 0.52%   |
| Luxvisions Innotech Limited            | 1         | 0.52%   |
| Logitech                               | 1         | 0.52%   |
| Apple                                  | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 13        | 6.77%   |
| Microdia Integrated_Webcam_HD                    | 9         | 4.69%   |
| IMC Networks Integrated Camera                   | 8         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                | 6         | 3.13%   |
| Bison Integrated Camera                          | 5         | 2.6%    |
| Sunplus HP HD Webcam [Fixed]                     | 4         | 2.08%   |
| Quanta HP TrueVision HD Camera                   | 4         | 2.08%   |
| Quanta HP HD Camera                              | 4         | 2.08%   |
| Primax HP HD Webcam [Fixed]                      | 4         | 2.08%   |
| Chicony HP HD Camera                             | 4         | 2.08%   |
| Syntek Lenovo EasyCamera                         | 3         | 1.56%   |
| Realtek USB Camera                               | 3         | 1.56%   |
| Lite-On HP HD Webcam                             | 3         | 1.56%   |
| Lenovo Integrated Webcam [R5U877]                | 3         | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                    | 3         | 1.56%   |
| Chicony HP HD Webcam                             | 3         | 1.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 1.56%   |
| Sunplus HD WebCam                                | 2         | 1.04%   |
| Realtek Integrated_Webcam_HD                     | 2         | 1.04%   |
| Realtek Asus laptop camera                       | 2         | 1.04%   |
| Quanta HP Webcam                                 | 2         | 1.04%   |
| Quanta ACER HD User Facing                       | 2         | 1.04%   |
| Lite-On Integrated Camera                        | 2         | 1.04%   |
| Lite-On HP HD Camera                             | 2         | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.04%   |
| IMC Networks Integrated Webcam                   | 2         | 1.04%   |
| Generalplus CAMERA - UVC                         | 2         | 1.04%   |
| Chicony USB2.0 UVC WebCam                        | 2         | 1.04%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 1.04%   |
| Chicony Lenovo EasyCamera                        | 2         | 1.04%   |
| Chicony Integrated IR Camera                     | 2         | 1.04%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 1.04%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 1.04%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 1.04%   |
| Chicony HP Webcam                                | 2         | 1.04%   |
| Chicony HP TrueVision HD Camera                  | 2         | 1.04%   |
| Chicony FJ Camera                                | 2         | 1.04%   |
| Syntek Integrated Camera                         | 1         | 0.52%   |
| Suyin HP Webcam-50                               | 1         | 0.52%   |
| Suyin HP Truevision HD                           | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 32.2%   |
| Validity Sensors           | 18        | 30.51%  |
| Shenzhen Goodix Technology | 8         | 13.56%  |
| AuthenTec                  | 6         | 10.17%  |
| Upek                       | 4         | 6.78%   |
| STMicroelectronics         | 2         | 3.39%   |
| Elan Microelectronics      | 2         | 3.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 10.17%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 10.17%  |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 8.47%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 6.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 6.78%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 6.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.08%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 5.08%   |
| Validity Sensors VFS491                                                    | 2         | 3.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.39%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.39%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.39%   |
| AuthenTec AES2810                                                          | 2         | 3.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.69%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.69%   |
| Synaptics UWP WBDI                                                         | 1         | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.69%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.69%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.69%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.69%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.69%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.69%   |
| AuthenTec AES1600                                                          | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 9         | 47.37%  |
| Broadcom    | 6         | 31.58%  |
| O2 Micro    | 3         | 15.79%  |
| Upek        | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 47.37%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 15.79%  |
| Broadcom 58200                                                               | 3         | 15.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.26%   |
| Broadcom 5880                                                                | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 117       | 51.54%  |
| 1     | 78        | 34.36%  |
| 2     | 29        | 12.78%  |
| 3     | 2         | 0.88%   |
| 10    | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 39.86%  |
| Graphics card            | 24        | 16.22%  |
| Net/wireless             | 16        | 10.81%  |
| Chipcard                 | 16        | 10.81%  |
| Camera                   | 9         | 6.08%   |
| Bluetooth                | 6         | 4.05%   |
| Multimedia controller    | 5         | 3.38%   |
| Communication controller | 5         | 3.38%   |
| Storage                  | 2         | 1.35%   |
| Card reader              | 2         | 1.35%   |
| Sound                    | 1         | 0.68%   |
| Network                  | 1         | 0.68%   |
| Net/ethernet             | 1         | 0.68%   |
| Flash memory             | 1         | 0.68%   |

