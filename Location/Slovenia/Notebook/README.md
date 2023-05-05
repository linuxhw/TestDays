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

Total: 296

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 27        | 13.17%  |
| Ubuntu 18.04        | 14        | 6.83%   |
| Ubuntu 22.04        | 11        | 5.37%   |
| Debian 11           | 8         | 3.9%    |
| KDE neon 20.04      | 5         | 2.44%   |
| Fedora 37           | 5         | 2.44%   |
| Zorin 16            | 4         | 1.95%   |
| Zorin 15            | 4         | 1.95%   |
| OpenMandriva 4.3    | 4         | 1.95%   |
| Kubuntu 22.04       | 4         | 1.95%   |
| Fedora 34           | 4         | 1.95%   |
| ArcoLinux Rolling   | 4         | 1.95%   |
| Arch                | 4         | 1.95%   |
| Xubuntu 20.04       | 3         | 1.46%   |
| Linux Mint 19.1     | 3         | 1.46%   |
| Kubuntu 21.10       | 3         | 1.46%   |
| Kubuntu 20.04       | 3         | 1.46%   |
| Fedora 33           | 3         | 1.46%   |
| Debian Testing      | 3         | 1.46%   |
| Ubuntu Unity 16.04  | 2         | 0.98%   |
| Ubuntu 21.10        | 2         | 0.98%   |
| Ubuntu 21.04        | 2         | 0.98%   |
| Ubuntu 20.10        | 2         | 0.98%   |
| Ubuntu 19.10        | 2         | 0.98%   |
| Pop!_OS 21.04       | 2         | 0.98%   |
| OpenMandriva 4.2    | 2         | 0.98%   |
| Manjaro 20.2        | 2         | 0.98%   |
| Manjaro             | 2         | 0.98%   |
| LMDE 5              | 2         | 0.98%   |
| Linux Mint 21       | 2         | 0.98%   |
| Linux Mint 19.3     | 2         | 0.98%   |
| Kubuntu 18.04       | 2         | 0.98%   |
| KDE neon 22.04      | 2         | 0.98%   |
| Gentoo 2.6          | 2         | 0.98%   |
| Endless 3.5.8       | 2         | 0.98%   |
| EndeavourOS         | 2         | 0.98%   |
| Arch Rolling        | 2         | 0.98%   |
| Xubuntu 22.04       | 1         | 0.49%   |
| Ubuntu MATE 22.04   | 1         | 0.49%   |
| Ubuntu Budgie 22.04 | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 59        | 30.26%  |
| Fedora        | 15        | 7.69%   |
| Kubuntu       | 14        | 7.18%   |
| Debian        | 13        | 6.67%   |
| Linux Mint    | 10        | 5.13%   |
| Zorin         | 8         | 4.1%    |
| Manjaro       | 8         | 4.1%    |
| KDE neon      | 8         | 4.1%    |
| Endless       | 8         | 4.1%    |
| OpenMandriva  | 7         | 3.59%   |
| Arch          | 6         | 3.08%   |
| Xubuntu       | 4         | 2.05%   |
| Pop!_OS       | 4         | 2.05%   |
| ArcoLinux     | 4         | 2.05%   |
| openSUSE      | 3         | 1.54%   |
| Ubuntu Unity  | 2         | 1.03%   |
| Ubuntu Budgie | 2         | 1.03%   |
| Lubuntu       | 2         | 1.03%   |
| LMDE          | 2         | 1.03%   |
| Gentoo        | 2         | 1.03%   |
| EndeavourOS   | 2         | 1.03%   |
| Elementary    | 2         | 1.03%   |
| Ubuntu MATE   | 1         | 0.51%   |
| ROSA          | 1         | 0.51%   |
| Q4OS          | 1         | 0.51%   |
| Nobara        | 1         | 0.51%   |
| NixOS         | 1         | 0.51%   |
| Kali          | 1         | 0.51%   |
| Garuda Linux  | 1         | 0.51%   |
| Clear Linux   | 1         | 0.51%   |
| Chrome OS     | 1         | 0.51%   |
| BlackPanther  | 1         | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 4         | 1.8%    |
| 4.18.0-15-generic        | 4         | 1.8%    |
| 5.8.0-41-generic         | 3         | 1.35%   |
| 5.3.0-40-generic         | 3         | 1.35%   |
| 5.16.7-desktop-1omv4003  | 3         | 1.35%   |
| 5.15.0-57-generic        | 3         | 1.35%   |
| 5.15.0-56-generic        | 3         | 1.35%   |
| 5.15.0-43-generic        | 3         | 1.35%   |
| 5.13.0-41-generic        | 3         | 1.35%   |
| 5.13.0-30-generic        | 3         | 1.35%   |
| 5.13.0-28-generic        | 3         | 1.35%   |
| 5.13.0-21-generic        | 3         | 1.35%   |
| 5.8.0-44-generic         | 2         | 0.9%    |
| 5.8.0-14-generic         | 2         | 0.9%    |
| 5.6.0-1-amd64            | 2         | 0.9%    |
| 5.4.0-70-generic         | 2         | 0.9%    |
| 5.4.0-56-generic         | 2         | 0.9%    |
| 5.4.0-54-generic         | 2         | 0.9%    |
| 5.4.0-48-generic         | 2         | 0.9%    |
| 5.4.0-40-generic         | 2         | 0.9%    |
| 5.4.0-33-generic         | 2         | 0.9%    |
| 5.4.0-28-generic         | 2         | 0.9%    |
| 5.4.0-26-generic         | 2         | 0.9%    |
| 5.15.0-47-generic        | 2         | 0.9%    |
| 5.15.0-46-generic        | 2         | 0.9%    |
| 5.13.19-2-MANJARO        | 2         | 0.9%    |
| 5.13.0-7614-generic      | 2         | 0.9%    |
| 5.11.0-43-generic        | 2         | 0.9%    |
| 5.11.0-40-generic        | 2         | 0.9%    |
| 5.11.0-35-generic        | 2         | 0.9%    |
| 5.10.14-desktop-1omv4002 | 2         | 0.9%    |
| 5.10.0-8-amd64           | 2         | 0.9%    |
| 4.15.0-128-generic       | 2         | 0.9%    |
| 6.2.8-200.fc37.x86_64    | 1         | 0.45%   |
| 6.2.2-1-default          | 1         | 0.45%   |
| 6.2.11-300.fc38.x86_64   | 1         | 0.45%   |
| 6.2.10-060210-generic    | 1         | 0.45%   |
| 6.2.0-20-generic         | 1         | 0.45%   |
| 6.1.9-200.fc37.x86_64    | 1         | 0.45%   |
| 6.1.5-arch2-1            | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 33        | 15.64%  |
| 5.15.0  | 17        | 8.06%   |
| 5.13.0  | 17        | 8.06%   |
| 5.11.0  | 12        | 5.69%   |
| 5.10.0  | 10        | 4.74%   |
| 4.15.0  | 10        | 4.74%   |
| 5.8.0   | 9         | 4.27%   |
| 5.3.0   | 8         | 3.79%   |
| 4.18.0  | 8         | 3.79%   |
| 5.19.0  | 6         | 2.84%   |
| 5.0.0   | 5         | 2.37%   |
| 5.6.0   | 3         | 1.42%   |
| 5.16.7  | 3         | 1.42%   |
| 5.10.14 | 3         | 1.42%   |
| 6.0.11  | 2         | 0.95%   |
| 5.13.19 | 2         | 0.95%   |
| 6.2.8   | 1         | 0.47%   |
| 6.2.2   | 1         | 0.47%   |
| 6.2.11  | 1         | 0.47%   |
| 6.2.10  | 1         | 0.47%   |
| 6.2.0   | 1         | 0.47%   |
| 6.1.9   | 1         | 0.47%   |
| 6.1.5   | 1         | 0.47%   |
| 6.1.18  | 1         | 0.47%   |
| 6.1.15  | 1         | 0.47%   |
| 6.1.11  | 1         | 0.47%   |
| 6.1.1   | 1         | 0.47%   |
| 6.0.7   | 1         | 0.47%   |
| 5.9.8   | 1         | 0.47%   |
| 5.9.2   | 1         | 0.47%   |
| 5.9.15  | 1         | 0.47%   |
| 5.9.14  | 1         | 0.47%   |
| 5.8.8   | 1         | 0.47%   |
| 5.8.5   | 1         | 0.47%   |
| 5.8.18  | 1         | 0.47%   |
| 5.8.10  | 1         | 0.47%   |
| 5.7.13  | 1         | 0.47%   |
| 5.6.14  | 1         | 0.47%   |
| 5.5.15  | 1         | 0.47%   |
| 5.5.0   | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 35        | 16.75%  |
| 5.15    | 22        | 10.53%  |
| 5.13    | 20        | 9.57%   |
| 5.11    | 14        | 6.7%    |
| 5.8     | 13        | 6.22%   |
| 5.10    | 13        | 6.22%   |
| 4.15    | 10        | 4.78%   |
| 5.3     | 9         | 4.31%   |
| 5.19    | 9         | 4.31%   |
| 4.18    | 9         | 4.31%   |
| 5.16    | 8         | 3.83%   |
| 6.1     | 6         | 2.87%   |
| 6.2     | 5         | 2.39%   |
| 5.0     | 5         | 2.39%   |
| 5.9     | 4         | 1.91%   |
| 5.6     | 4         | 1.91%   |
| 5.17    | 4         | 1.91%   |
| 5.14    | 4         | 1.91%   |
| 6.0     | 3         | 1.44%   |
| 5.12    | 3         | 1.44%   |
| 5.5     | 2         | 0.96%   |
| 4.19    | 2         | 0.96%   |
| 5.7     | 1         | 0.48%   |
| 5.18    | 1         | 0.48%   |
| 4.9     | 1         | 0.48%   |
| 4.14    | 1         | 0.48%   |
| 4.1     | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 178       | 96.74%  |
| i686   | 6         | 3.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| GNOME        | 79        | 40.51%  |
| KDE5         | 41        | 21.03%  |
| Unknown      | 26        | 13.33%  |
| XFCE         | 17        | 8.72%   |
| X-Cinnamon   | 7         | 3.59%   |
| LXQt         | 4         | 2.05%   |
| MATE         | 3         | 1.54%   |
| KDE          | 3         | 1.54%   |
| Unity        | 2         | 1.03%   |
| Pantheon     | 2         | 1.03%   |
| LXDE         | 2         | 1.03%   |
| Cinnamon     | 2         | 1.03%   |
| Budgie       | 2         | 1.03%   |
| Trinity      | 1         | 0.51%   |
| Openbox      | 1         | 0.51%   |
| none+awesome | 1         | 0.51%   |
| i3           | 1         | 0.51%   |
| DWM          | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 138       | 71.13%  |
| Wayland | 34        | 17.53%  |
| Unknown | 18        | 9.28%   |
| Tty     | 4         | 2.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 45.64%  |
| SDDM    | 35        | 17.95%  |
| GDM     | 22        | 11.28%  |
| LightDM | 20        | 10.26%  |
| GDM3    | 20        | 10.26%  |
| TDM     | 9         | 4.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 98        | 52.41%  |
| sl_SI   | 43        | 22.99%  |
| Unknown | 26        | 13.9%   |
| en_GB   | 7         | 3.74%   |
| en_SI   | 4         | 2.14%   |
| it_IT   | 3         | 1.6%    |
| C       | 2         | 1.07%   |
| pt_PT   | 1         | 0.53%   |
| nl_NL   | 1         | 0.53%   |
| hr_HR   | 1         | 0.53%   |
| en_BW   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 97        | 51.32%  |
| BIOS | 92        | 48.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 151       | 79.47%  |
| Btrfs   | 16        | 8.42%   |
| Overlay | 12        | 6.32%   |
| Unknown | 8         | 4.21%   |
| Zfs     | 1         | 0.53%   |
| Xfs     | 1         | 0.53%   |
| Ext2    | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 101       | 52.6%   |
| GPT     | 61        | 31.77%  |
| MBR     | 30        | 15.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 174       | 92.55%  |
| Yes       | 14        | 7.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 134       | 71.66%  |
| Yes       | 53        | 28.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 59        | 32.07%  |
| Lenovo              | 51        | 27.72%  |
| ASUSTek Computer    | 23        | 12.5%   |
| Dell                | 18        | 9.78%   |
| Toshiba             | 9         | 4.89%   |
| Acer                | 7         | 3.8%    |
| Fujitsu             | 4         | 2.17%   |
| MSI                 | 2         | 1.09%   |
| Fujitsu Siemens     | 2         | 1.09%   |
| TUXEDO              | 1         | 0.54%   |
| Razer               | 1         | 0.54%   |
| PC Specialist       | 1         | 0.54%   |
| Panasonic           | 1         | 0.54%   |
| Medion              | 1         | 0.54%   |
| HUAWEI              | 1         | 0.54%   |
| Gigabyte Technology | 1         | 0.54%   |
| Framework           | 1         | 0.54%   |
| eMachines           | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                      | 3         | 1.63%   |
| Toshiba Satellite L750                     | 2         | 1.09%   |
| Lenovo ThinkPad T410 2522A92               | 2         | 1.09%   |
| HP ProBook 4730s                           | 2         | 1.09%   |
| HP EliteBook 8760w                         | 2         | 1.09%   |
| HP 255 G8 Notebook PC                      | 2         | 1.09%   |
| Dell XPS 13 9310                           | 2         | 1.09%   |
| Dell Inspiron 5570                         | 2         | 1.09%   |
| Dell Inspiron 1501                         | 2         | 1.09%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 1.09%   |
| Unknown                                    | 2         | 1.09%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.54%   |
| Toshiba TECRA S10                          | 1         | 0.54%   |
| Toshiba TECRA A11                          | 1         | 0.54%   |
| Toshiba Satellite R630                     | 1         | 0.54%   |
| Toshiba Satellite Pro U400                 | 1         | 0.54%   |
| Toshiba Satellite Pro R50-E                | 1         | 0.54%   |
| Toshiba Satellite A100                     | 1         | 0.54%   |
| Toshiba QOSMIO X500                        | 1         | 0.54%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.54%   |
| PC Specialist Fusion IV                    | 1         | 0.54%   |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.54%   |
| MSI U210                                   | 1         | 0.54%   |
| MSI GP60 2OD                               | 1         | 0.54%   |
| Medion E7218                               | 1         | 0.54%   |
| Lenovo Yoga S740-14IIL 81RS                | 1         | 0.54%   |
| Lenovo Yoga 2 13 20344                     | 1         | 0.54%   |
| Lenovo V15 G2 ALC 82KD                     | 1         | 0.54%   |
| Lenovo ThinkPad X250 20CM004ESC            | 1         | 0.54%   |
| Lenovo ThinkPad X230 23202DG               | 1         | 0.54%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.54%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.54%   |
| Lenovo ThinkPad W530 24479K4               | 1         | 0.54%   |
| Lenovo ThinkPad T61 8897CTO                | 1         | 0.54%   |
| Lenovo ThinkPad T590 20N5S0YN00            | 1         | 0.54%   |
| Lenovo ThinkPad T590 20N5S0MR00            | 1         | 0.54%   |
| Lenovo ThinkPad T500 2055WYX               | 1         | 0.54%   |
| Lenovo ThinkPad T490s 20NYS4HL07           | 1         | 0.54%   |
| Lenovo ThinkPad T480 20L6S58700            | 1         | 0.54%   |
| Lenovo ThinkPad T480 20L6S01W00            | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 34        | 18.48%  |
| HP ProBook             | 13        | 7.07%   |
| HP EliteBook           | 12        | 6.52%   |
| Lenovo IdeaPad         | 7         | 3.8%    |
| HP ZBook               | 7         | 3.8%    |
| Dell Inspiron          | 7         | 3.8%    |
| Toshiba Satellite      | 6         | 3.26%   |
| Dell Latitude          | 6         | 3.26%   |
| HP 255                 | 5         | 2.72%   |
| HP Pavilion            | 4         | 2.17%   |
| HP Compaq              | 4         | 2.17%   |
| HP 250                 | 4         | 2.17%   |
| Fujitsu LIFEBOOK       | 4         | 2.17%   |
| ASUS VivoBook          | 4         | 2.17%   |
| Dell XPS               | 3         | 1.63%   |
| ASUS ASUS              | 3         | 1.63%   |
| Acer Aspire            | 3         | 1.63%   |
| Toshiba TECRA          | 2         | 1.09%   |
| Lenovo Yoga            | 2         | 1.09%   |
| HP Laptop              | 2         | 1.09%   |
| Acer Predator          | 2         | 1.09%   |
| Acer Nitro             | 2         | 1.09%   |
| Unknown                | 2         | 1.09%   |
| TUXEDO Aura            | 1         | 0.54%   |
| Toshiba QOSMIO         | 1         | 0.54%   |
| Razer Blade            | 1         | 0.54%   |
| PC Specialist Fusion   | 1         | 0.54%   |
| Panasonic CF-53SWWZ5MG | 1         | 0.54%   |
| MSI U210               | 1         | 0.54%   |
| MSI GP60               | 1         | 0.54%   |
| Medion E7218           | 1         | 0.54%   |
| Lenovo V15             | 1         | 0.54%   |
| Lenovo Legion          | 1         | 0.54%   |
| Lenovo G585            | 1         | 0.54%   |
| Lenovo G510            | 1         | 0.54%   |
| Lenovo G500            | 1         | 0.54%   |
| Lenovo G50-30          | 1         | 0.54%   |
| Lenovo B50-80          | 1         | 0.54%   |
| Lenovo B50-30          | 1         | 0.54%   |
| HUAWEI HKD-WXX         | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 24        | 13.04%  |
| 2020 | 19        | 10.33%  |
| 2011 | 16        | 8.7%    |
| 2018 | 15        | 8.15%   |
| 2017 | 12        | 6.52%   |
| 2014 | 12        | 6.52%   |
| 2013 | 12        | 6.52%   |
| 2010 | 12        | 6.52%   |
| 2008 | 11        | 5.98%   |
| 2012 | 10        | 5.43%   |
| 2021 | 9         | 4.89%   |
| 2015 | 9         | 4.89%   |
| 2009 | 8         | 4.35%   |
| 2006 | 5         | 2.72%   |
| 2007 | 4         | 2.17%   |
| 2022 | 3         | 1.63%   |
| 2016 | 3         | 1.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 184       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 166       | 88.77%  |
| Enabled  | 21        | 11.23%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 183       | 99.46%  |
| Yes  | 1         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 51        | 27.57%  |
| 8.01-16.0   | 37        | 20%     |
| 4.01-8.0    | 36        | 19.46%  |
| 16.01-24.0  | 32        | 17.3%   |
| 32.01-64.0  | 15        | 8.11%   |
| 1.01-2.0    | 6         | 3.24%   |
| 24.01-32.0  | 2         | 1.08%   |
| 2.01-3.0    | 2         | 1.08%   |
| 64.01-256.0 | 2         | 1.08%   |
| 0.51-1.0    | 2         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 67        | 32.06%  |
| 2.01-3.0   | 57        | 27.27%  |
| 4.01-8.0   | 26        | 12.44%  |
| 3.01-4.0   | 26        | 12.44%  |
| 0.51-1.0   | 19        | 9.09%   |
| 8.01-16.0  | 9         | 4.31%   |
| 0.01-0.5   | 3         | 1.44%   |
| 24.01-32.0 | 1         | 0.48%   |
| 16.01-24.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 144       | 76.19%  |
| 2      | 33        | 17.46%  |
| 3      | 7         | 3.7%    |
| 0      | 5         | 2.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 55.43%  |
| Yes       | 82        | 44.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 88.11%  |
| No        | 22        | 11.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 99.46%  |
| No        | 1         | 0.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 81.18%  |
| No        | 35        | 18.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovenia | 184       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 68        | 33.33%  |
| Kranj                   | 8         | 3.92%   |
| Celje                   | 6         | 2.94%   |
| Vrhnika                 | 4         | 1.96%   |
| Trzin                   | 4         | 1.96%   |
| Poljane nad Skofjo Loko | 4         | 1.96%   |
| Maribor                 | 4         | 1.96%   |
| Slovenske Konjice       | 3         | 1.47%   |
| Portorož               | 3         | 1.47%   |
| Nova Gorica             | 3         | 1.47%   |
| Murska Sobota           | 3         | 1.47%   |
| Koper                   | 3         | 1.47%   |
| Ajdovščina            | 3         | 1.47%   |
| Žalec                  | 2         | 0.98%   |
| Trbovlje                | 2         | 0.98%   |
| Smarje pri Jelsah       | 2         | 0.98%   |
| Slovenj Gradec          | 2         | 0.98%   |
| Sežana                 | 2         | 0.98%   |
| Puconci                 | 2         | 0.98%   |
| Petrovce                | 2         | 0.98%   |
| Medvode                 | 2         | 0.98%   |
| Kamnik                  | 2         | 0.98%   |
| Grosuplje               | 2         | 0.98%   |
| Blejska Dobrava         | 2         | 0.98%   |
| Žužemberk             | 1         | 0.49%   |
| Ziri                    | 1         | 0.49%   |
| Zgornji Leskovec        | 1         | 0.49%   |
| Zgornja Besnica         | 1         | 0.49%   |
| Zagorje ob Savi         | 1         | 0.49%   |
| Visoko                  | 1         | 0.49%   |
| Vipava                  | 1         | 0.49%   |
| Velenje                 | 1         | 0.49%   |
| Turnisce                | 1         | 0.49%   |
| Trzic                   | 1         | 0.49%   |
| Tabor                   | 1         | 0.49%   |
| Solkan                  | 1         | 0.49%   |
| Smartno ob Paki         | 1         | 0.49%   |
| Skofljica               | 1         | 0.49%   |
| Škofja Loka            | 1         | 0.49%   |
| Skocjan                 | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 35        | 48     | 16.13%  |
| Seagate                 | 21        | 25     | 9.68%   |
| Crucial                 | 18        | 25     | 8.29%   |
| WDC                     | 17        | 17     | 7.83%   |
| Toshiba                 | 17        | 25     | 7.83%   |
| Kingston                | 15        | 21     | 6.91%   |
| SK hynix                | 13        | 18     | 5.99%   |
| SanDisk                 | 13        | 15     | 5.99%   |
| Hitachi                 | 10        | 13     | 4.61%   |
| HGST                    | 9         | 10     | 4.15%   |
| Unknown                 | 7         | 8      | 3.23%   |
| Micron Technology       | 5         | 6      | 2.3%    |
| KIOXIA                  | 4         | 4      | 1.84%   |
| Intel                   | 4         | 4      | 1.84%   |
| JMicron Technology      | 3         | 3      | 1.38%   |
| Intenso                 | 3         | 3      | 1.38%   |
| Fujitsu                 | 3         | 4      | 1.38%   |
| Transcend               | 2         | 2      | 0.92%   |
| PNY                     | 2         | 2      | 0.92%   |
| OCZ                     | 2         | 2      | 0.92%   |
| LITEON                  | 2         | 2      | 0.92%   |
| Lenovo                  | 2         | 2      | 0.92%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.46%   |
| Team                    | 1         | 1      | 0.46%   |
| Silicon Motion          | 1         | 2      | 0.46%   |
| SABRENT                 | 1         | 1      | 0.46%   |
| Patriot                 | 1         | 2      | 0.46%   |
| LITEONIT                | 1         | 2      | 0.46%   |
| HGST HTS                | 1         | 1      | 0.46%   |
| Gigabyte Technology     | 1         | 2      | 0.46%   |
| Corsair                 | 1         | 3      | 0.46%   |
| Unknown                 | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                      | 5         | 2.23%   |
| HGST HTS721010A9E630 1TB                          | 5         | 2.23%   |
| Kingston SA400S37240G 240GB SSD                   | 3         | 1.34%   |
| Hitachi HTS547575A9E384 752GB                     | 3         | 1.34%   |
| Crucial CT240BX500SSD1 240GB                      | 3         | 1.34%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 0.89%   |
| Toshiba MQ01ABF050 500GB                          | 2         | 0.89%   |
| SK hynix SC311 SATA 256GB SSD                     | 2         | 0.89%   |
| Seagate ST9750420AS 752GB                         | 2         | 0.89%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.89%   |
| Seagate ST9320423AS 320GB                         | 2         | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 0.89%   |
| SanDisk NVMe SSD Drive 512GB                      | 2         | 0.89%   |
| Samsung SSD 860 EVO 250GB                         | 2         | 0.89%   |
| Samsung SSD 850 EVO 250GB                         | 2         | 0.89%   |
| Samsung NVMe SSD Drive 256GB                      | 2         | 0.89%   |
| Samsung NVMe SSD Drive 1024GB                     | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.89%   |
| PNY CS900 120GB SSD                               | 2         | 0.89%   |
| Lenovo NVMe SSD Drive 256GB                       | 2         | 0.89%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 0.89%   |
| Hitachi HTS725032A9A364 320GB                     | 2         | 0.89%   |
| HGST HTS545050A7E680 500GB                        | 2         | 0.89%   |
| Crucial CT250BX100SSD1 250GB                      | 2         | 0.89%   |
| Crucial CT2000MX500SSD1 2TB                       | 2         | 0.89%   |
| WDC WDS500G3X0C-00SJG0 500GB                      | 1         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 1         | 0.45%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                  | 1         | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 1         | 0.45%   |
| WDC WDS100T3X0C-00SJG0 1TB                        | 1         | 0.45%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 0.45%   |
| WDC WD7500BPVX-60JC3T0 752GB                      | 1         | 0.45%   |
| WDC WD3200BEKT-22KA9T0 320GB                      | 1         | 0.45%   |
| WDC WD2500BEVT-60ZCT1 250GB                       | 1         | 0.45%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 1         | 0.45%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.45%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB              | 1         | 0.45%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB              | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 21        | 25     | 33.87%  |
| Toshiba            | 10        | 16     | 16.13%  |
| Hitachi            | 10        | 13     | 16.13%  |
| HGST               | 9         | 10     | 14.52%  |
| WDC                | 6         | 6      | 9.68%   |
| Fujitsu            | 3         | 4      | 4.84%   |
| SABRENT            | 1         | 1      | 1.61%   |
| JMicron Technology | 1         | 1      | 1.61%   |
| HGST HTS           | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 17        | 24     | 20.73%  |
| Samsung Electronics | 16        | 19     | 19.51%  |
| Kingston            | 12        | 17     | 14.63%  |
| SanDisk             | 8         | 10     | 9.76%   |
| WDC                 | 5         | 5      | 6.1%    |
| SK hynix            | 4         | 4      | 4.88%   |
| Transcend           | 2         | 2      | 2.44%   |
| PNY                 | 2         | 2      | 2.44%   |
| OCZ                 | 2         | 2      | 2.44%   |
| Micron Technology   | 2         | 2      | 2.44%   |
| LITEON              | 2         | 2      | 2.44%   |
| Intenso             | 2         | 2      | 2.44%   |
| Toshiba             | 1         | 1      | 1.22%   |
| Team                | 1         | 1      | 1.22%   |
| Patriot             | 1         | 2      | 1.22%   |
| LITEONIT            | 1         | 2      | 1.22%   |
| JMicron Technology  | 1         | 1      | 1.22%   |
| Intel               | 1         | 1      | 1.22%   |
| Gigabyte Technology | 1         | 2      | 1.22%   |
| Corsair             | 1         | 3      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 76        | 104    | 36.89%  |
| NVMe    | 61        | 84     | 29.61%  |
| HDD     | 60        | 77     | 29.13%  |
| MMC     | 6         | 7      | 2.91%   |
| Unknown | 3         | 3      | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 123       | 175    | 62.44%  |
| NVMe | 61        | 84     | 30.96%  |
| SAS  | 7         | 9      | 3.55%   |
| MMC  | 6         | 7      | 3.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 128    | 69.63%  |
| 0.51-1.0   | 35        | 42     | 25.93%  |
| 1.01-2.0   | 5         | 9      | 3.7%    |
| 3.01-4.0   | 1         | 2      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 28.43%  |
| 251-500        | 53        | 26.9%   |
| 501-1000       | 27        | 13.71%  |
| 1-20           | 14        | 7.11%   |
| 1001-2000      | 13        | 6.6%    |
| 51-100         | 13        | 6.6%    |
| 21-50          | 9         | 4.57%   |
| 2001-3000      | 6         | 3.05%   |
| More than 3000 | 3         | 1.52%   |
| Unknown        | 3         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 83        | 40.89%  |
| 21-50     | 33        | 16.26%  |
| 101-250   | 31        | 15.27%  |
| 51-100    | 26        | 12.81%  |
| 251-500   | 16        | 7.88%   |
| 501-1000  | 8         | 3.94%   |
| Unknown   | 3         | 1.48%   |
| 1001-2000 | 2         | 0.99%   |
| 2001-3000 | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 2         | 2      | 12.5%   |
| Toshiba MQ01ABF050 500GB              | 1         | 5      | 6.25%   |
| SK hynix HFS256G32MND-2200A 256GB SSD | 1         | 1      | 6.25%   |
| Seagate ST98823AS 80GB                | 1         | 2      | 6.25%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 6.25%   |
| Seagate ST9500423AS 500GB             | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB             | 1         | 2      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 6.25%   |
| SanDisk SD7SB2Q512G1001 512GB SSD     | 1         | 1      | 6.25%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 6.25%   |
| Hitachi HTS727550A9E364 500GB         | 1         | 1      | 6.25%   |
| Hitachi HTS543280L9SA00 80GB          | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 6.25%   |
| Crucial CT250BX100SSD1 250GB          | 1         | 1      | 6.25%   |
| Crucial CT120M500SSD1 120GB           | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 7      | 31.25%  |
| HGST     | 3         | 3      | 18.75%  |
| Hitachi  | 2         | 2      | 12.5%   |
| Crucial  | 2         | 2      | 12.5%   |
| Toshiba  | 1         | 5      | 6.25%   |
| SK hynix | 1         | 1      | 6.25%   |
| SanDisk  | 1         | 1      | 6.25%   |
| Kingston | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 7      | 45.45%  |
| HGST    | 3         | 3      | 27.27%  |
| Hitachi | 2         | 2      | 18.18%  |
| Toshiba | 1         | 5      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 17     | 68.75%  |
| SSD  | 5         | 5      | 31.25%  |

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
| Detected | 107       | 162    | 55.73%  |
| Works    | 67        | 88     | 34.9%   |
| Malfunc  | 16        | 22     | 8.33%   |
| Failed   | 2         | 3      | 1.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 130       | 59.09%  |
| Samsung Electronics              | 23        | 10.45%  |
| AMD                              | 23        | 10.45%  |
| SanDisk                          | 11        | 5%      |
| Toshiba America Info Systems     | 9         | 4.09%   |
| SK hynix                         | 9         | 4.09%   |
| Micron Technology                | 3         | 1.36%   |
| Kingston Technology Company      | 3         | 1.36%   |
| Lenovo                           | 2         | 0.91%   |
| KIOXIA                           | 2         | 0.91%   |
| Union Memory (Shenzhen)          | 1         | 0.45%   |
| Silicon Motion                   | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Micron/Crucial Technology        | 1         | 0.45%   |
| Marvell Technology Group         | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 7.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 6.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 6.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 4.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 3%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 3%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 3%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 2.58%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 2.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 2.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.72%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.29%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 1.29%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.29%   |
| Micron NVMe Storage Controller                                                 | 3         | 1.29%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.29%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 3         | 1.29%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 0.86%   |
| SK hynix BC511                                                                 | 2         | 0.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.86%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.86%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.86%   |
| Intel SSD 660P Series                                                          | 2         | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 132       | 58.67%  |
| NVMe | 64        | 28.44%  |
| IDE  | 18        | 8%      |
| RAID | 11        | 4.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 153       | 83.15%  |
| AMD    | 31        | 16.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 3.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 2.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.72%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 2.72%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 2.17%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 4         | 2.17%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 1.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.63%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.63%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.63%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.09%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.09%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.09%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.09%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.09%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.09%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.09%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.09%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.09%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 1.09%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.09%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 1.09%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.09%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.09%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 1.09%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 53        | 28.8%   |
| Intel Core i5           | 43        | 23.37%  |
| Intel Core 2 Duo        | 16        | 8.7%    |
| Intel Core i3           | 13        | 7.07%   |
| Intel Celeron           | 10        | 5.43%   |
| Other                   | 7         | 3.8%    |
| Intel Pentium           | 6         | 3.26%   |
| AMD Ryzen 7             | 6         | 3.26%   |
| AMD Ryzen 5             | 6         | 3.26%   |
| AMD Ryzen 3             | 6         | 3.26%   |
| AMD Ryzen 9             | 3         | 1.63%   |
| Intel Genuine           | 2         | 1.09%   |
| Intel Pentium Silver    | 1         | 0.54%   |
| Intel Pentium Dual      | 1         | 0.54%   |
| Intel Core 2            | 1         | 0.54%   |
| AMD Turion II Dual-Core | 1         | 0.54%   |
| AMD Turion II           | 1         | 0.54%   |
| AMD Mobile Sempron      | 1         | 0.54%   |
| AMD E1                  | 1         | 0.54%   |
| AMD E                   | 1         | 0.54%   |
| AMD C-60                | 1         | 0.54%   |
| AMD Athlon Neo          | 1         | 0.54%   |
| AMD Athlon 64 X2        | 1         | 0.54%   |
| AMD A8                  | 1         | 0.54%   |
| AMD A6                  | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 50%     |
| 4      | 68        | 36.96%  |
| 6      | 12        | 6.52%   |
| 8      | 8         | 4.35%   |
| 1      | 3         | 1.63%   |
| 10     | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 184       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 137       | 74.46%  |
| 1      | 47        | 25.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 177       | 95.68%  |
| Unknown        | 6         | 3.24%   |
| 32-bit         | 2         | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 20.31%  |
| 0x206a7    | 13        | 6.77%   |
| 0x806ec    | 11        | 5.73%   |
| 0x306a9    | 10        | 5.21%   |
| 0x40651    | 9         | 4.69%   |
| 0x306c3    | 8         | 4.17%   |
| 0x20655    | 8         | 4.17%   |
| 0x806ea    | 6         | 3.13%   |
| 0x806c1    | 6         | 3.13%   |
| 0x6fd      | 6         | 3.13%   |
| 0x30678    | 5         | 2.6%    |
| 0x10676    | 5         | 2.6%    |
| 0x08108102 | 5         | 2.6%    |
| 0x906ea    | 4         | 2.08%   |
| 0x1067a    | 4         | 2.08%   |
| 0xa0652    | 3         | 1.56%   |
| 0x906e9    | 3         | 1.56%   |
| 0x706e5    | 3         | 1.56%   |
| 0x406e3    | 3         | 1.56%   |
| 0x306d4    | 3         | 1.56%   |
| 0x20652    | 3         | 1.56%   |
| 0x106e5    | 3         | 1.56%   |
| 0x08608103 | 3         | 1.56%   |
| 0x906ed    | 2         | 1.04%   |
| 0x806eb    | 2         | 1.04%   |
| 0x706a1    | 2         | 1.04%   |
| 0x6e8      | 2         | 1.04%   |
| 0x506c9    | 2         | 1.04%   |
| 0x08608102 | 2         | 1.04%   |
| 0x08600106 | 2         | 1.04%   |
| 0x0810100b | 2         | 1.04%   |
| 0x06001119 | 2         | 1.04%   |
| 0x05000119 | 2         | 1.04%   |
| 0xa0660    | 1         | 0.52%   |
| 0x906a4    | 1         | 0.52%   |
| 0x6fb      | 1         | 0.52%   |
| 0x406c4    | 1         | 0.52%   |
| 0x0a50000c | 1         | 0.52%   |
| 0x0a404102 | 1         | 0.52%   |
| 0x08600104 | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 20.11%  |
| Haswell          | 18        | 9.78%   |
| SandyBridge      | 15        | 8.15%   |
| IvyBridge        | 12        | 6.52%   |
| Westmere         | 11        | 5.98%   |
| Penryn           | 10        | 5.43%   |
| Core             | 8         | 4.35%   |
| Silvermont       | 7         | 3.8%    |
| Unknown          | 7         | 3.8%    |
| TigerLake        | 6         | 3.26%   |
| Zen+             | 5         | 2.72%   |
| Zen 2            | 5         | 2.72%   |
| Skylake          | 5         | 2.72%   |
| Broadwell        | 5         | 2.72%   |
| IceLake          | 4         | 2.17%   |
| CometLake        | 4         | 2.17%   |
| Nehalem          | 3         | 1.63%   |
| K8 Hammer        | 3         | 1.63%   |
| Goldmont plus    | 3         | 1.63%   |
| Zen 3            | 2         | 1.09%   |
| Zen              | 2         | 1.09%   |
| Piledriver       | 2         | 1.09%   |
| P6               | 2         | 1.09%   |
| K10              | 2         | 1.09%   |
| Goldmont         | 2         | 1.09%   |
| Bobcat           | 2         | 1.09%   |
| Jaguar           | 1         | 0.54%   |
| Alderlake Hybrid | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 132       | 55.23%  |
| AMD                              | 58        | 24.27%  |
| Nvidia                           | 48        | 20.08%  |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 12        | 4.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 4.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 11        | 4.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 4.05%   |
| Intel UHD Graphics 620                                                                | 9         | 3.64%   |
| Intel Core Processor Integrated Graphics Controller                                   | 8         | 3.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 2.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 2.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 2.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 2.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 6         | 2.43%   |
| AMD Lucienne                                                                          | 6         | 2.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 2.02%   |
| Intel HD Graphics 5500                                                                | 5         | 2.02%   |
| AMD Renoir                                                                            | 5         | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 2.02%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.62%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 1.21%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.21%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 3         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.81%   |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 2         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 0.81%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                             | 2         | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 2         | 0.81%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 0.81%   |
| Intel HD Graphics 630                                                                 | 2         | 0.81%   |
| Intel HD Graphics 530                                                                 | 2         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 2         | 0.81%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 2         | 0.81%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 2         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 2         | 0.81%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 2         | 0.81%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                               | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 45.11%  |
| 1 x AMD        | 33        | 17.93%  |
| Intel + Nvidia | 32        | 17.39%  |
| Intel + AMD    | 17        | 9.24%   |
| 1 x Nvidia     | 10        | 5.43%   |
| AMD + Nvidia   | 6         | 3.26%   |
| 2 x AMD        | 2         | 1.09%   |
| 1 x SiS        | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 153       | 82.7%   |
| Proprietary | 25        | 13.51%  |
| Unknown     | 7         | 3.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 61.9%   |
| 1.01-2.0   | 25        | 13.23%  |
| 0.01-0.5   | 19        | 10.05%  |
| 0.51-1.0   | 13        | 6.88%   |
| 3.01-4.0   | 9         | 4.76%   |
| 5.01-6.0   | 4         | 2.12%   |
| 7.01-8.0   | 1         | 0.53%   |
| 2.01-3.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 50        | 23.7%   |
| LG Display              | 26        | 12.32%  |
| Samsung Electronics     | 24        | 11.37%  |
| Chimei Innolux          | 21        | 9.95%   |
| BOE                     | 20        | 9.48%   |
| Lenovo                  | 12        | 5.69%   |
| Dell                    | 11        | 5.21%   |
| Chi Mei Optoelectronics | 9         | 4.27%   |
| Goldstar                | 4         | 1.9%    |
| Sharp                   | 3         | 1.42%   |
| LG Philips              | 3         | 1.42%   |
| AOC                     | 3         | 1.42%   |
| TMX                     | 2         | 0.95%   |
| PANDA                   | 2         | 0.95%   |
| Hewlett-Packard         | 2         | 0.95%   |
| HannStar                | 2         | 0.95%   |
| CSO                     | 2         | 0.95%   |
| CPT                     | 2         | 0.95%   |
| ViewSonic               | 1         | 0.47%   |
| Unknown (XXX)           | 1         | 0.47%   |
| Unknown                 | 1         | 0.47%   |
| Sony                    | 1         | 0.47%   |
| Philips                 | 1         | 0.47%   |
| NEC Computers           | 1         | 0.47%   |
| Medion                  | 1         | 0.47%   |
| LGD                     | 1         | 0.47%   |
| InfoVision              | 1         | 0.47%   |
| IBM                     | 1         | 0.47%   |
| Gericom                 | 1         | 0.47%   |
| BenQ                    | 1         | 0.47%   |
| ASUSTek Computer        | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 3.26%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 1.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 1.4%    |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 1.4%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 2         | 0.93%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 0.93%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 0.93%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 0.93%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 2         | 0.93%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.93%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 0.93%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 0.93%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.47%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.47%   |
| Unknown (XXX) L9W XXX076E 1440x900 410x256mm 19.0-inch                    | 1         | 0.47%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                   | 1         | 0.47%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.47%   |
| Sony TV SNYAA01 1920x1080 880x490mm 39.7-inch                             | 1         | 0.47%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                   | 1         | 0.47%   |
| Sharp LCD Monitor SHP1450 3840x2160 350x190mm 15.7-inch                   | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 440x300mm 21.0-inch      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM02B5 1920x1200 518x324mm 24.1-inch      | 1         | 0.47%   |
| Samsung Electronics S27D390 SAM0B66 1920x1080 598x336mm 27.0-inch         | 1         | 0.47%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch         | 1         | 0.47%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch      | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 90        | 45.92%  |
| 1366x768 (WXGA)    | 41        | 20.92%  |
| 1600x900 (HD+)     | 18        | 9.18%   |
| 1280x800 (WXGA)    | 8         | 4.08%   |
| 1920x1200 (WUXGA)  | 6         | 3.06%   |
| 3840x2160 (4K)     | 5         | 2.55%   |
| 3440x1440          | 5         | 2.55%   |
| 2560x1440 (QHD)    | 5         | 2.55%   |
| 1680x1050 (WSXGA+) | 5         | 2.55%   |
| 1440x900 (WXGA+)   | 5         | 2.55%   |
| 3456x2160          | 1         | 0.51%   |
| 2560x1600          | 1         | 0.51%   |
| 2520x1680          | 1         | 0.51%   |
| 2288x1287          | 1         | 0.51%   |
| 2256x1504          | 1         | 0.51%   |
| 2048x1152          | 1         | 0.51%   |
| 1400x1050          | 1         | 0.51%   |
| 1280x1024 (SXGA)   | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 93        | 43.66%  |
| 17      | 27        | 12.68%  |
| 13      | 21        | 9.86%   |
| 14      | 17        | 7.98%   |
| 24      | 10        | 4.69%   |
| 23      | 8         | 3.76%   |
| 34      | 5         | 2.35%   |
| 27      | 5         | 2.35%   |
| 21      | 4         | 1.88%   |
| 12      | 4         | 1.88%   |
| 22      | 3         | 1.41%   |
| 18      | 3         | 1.41%   |
| 54      | 2         | 0.94%   |
| 40      | 2         | 0.94%   |
| Unknown | 2         | 0.94%   |
| 142     | 1         | 0.47%   |
| 65      | 1         | 0.47%   |
| 39      | 1         | 0.47%   |
| 33      | 1         | 0.47%   |
| 19      | 1         | 0.47%   |
| 16      | 1         | 0.47%   |
| 11      | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 118       | 56.19%  |
| 351-400        | 29        | 13.81%  |
| 501-600        | 21        | 10%     |
| 201-300        | 18        | 8.57%   |
| 401-500        | 9         | 4.29%   |
| 701-800        | 6         | 2.86%   |
| 801-900        | 3         | 1.43%   |
| 1001-1500      | 3         | 1.43%   |
| Unknown        | 2         | 0.95%   |
| More than 2000 | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 151       | 79.89%  |
| 16/10   | 26        | 13.76%  |
| 21/9    | 5         | 2.65%   |
| 3/2     | 2         | 1.06%   |
| Unknown | 2         | 1.06%   |
| 5/4     | 1         | 0.53%   |
| 4/3     | 1         | 0.53%   |
| 1.00    | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 92        | 43.4%   |
| 81-90          | 26        | 12.26%  |
| 121-130        | 24        | 11.32%  |
| 201-250        | 19        | 8.96%   |
| 71-80          | 11        | 5.19%   |
| 351-500        | 6         | 2.83%   |
| 301-350        | 5         | 2.36%   |
| More than 1000 | 4         | 1.89%   |
| 61-70          | 4         | 1.89%   |
| 251-300        | 4         | 1.89%   |
| 151-200        | 3         | 1.42%   |
| 131-140        | 3         | 1.42%   |
| 501-1000       | 3         | 1.42%   |
| 141-150        | 2         | 0.94%   |
| 91-100         | 2         | 0.94%   |
| Unknown        | 2         | 0.94%   |
| 51-60          | 1         | 0.47%   |
| 111-120        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 84        | 40.19%  |
| 101-120       | 61        | 29.19%  |
| 51-100        | 43        | 20.57%  |
| 161-240       | 10        | 4.78%   |
| More than 240 | 5         | 2.39%   |
| 1-50          | 4         | 1.91%   |
| Unknown       | 2         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 152       | 79.17%  |
| 2     | 33        | 17.19%  |
| 0     | 4         | 2.08%   |
| 3     | 3         | 1.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 107       | 36.39%  |
| Realtek Semiconductor             | 94        | 31.97%  |
| Qualcomm Atheros                  | 38        | 12.93%  |
| Broadcom                          | 20        | 6.8%    |
| Ralink                            | 4         | 1.36%   |
| Marvell Technology Group          | 4         | 1.36%   |
| MediaTek                          | 3         | 1.02%   |
| Huawei Technologies               | 3         | 1.02%   |
| Hewlett-Packard                   | 3         | 1.02%   |
| ASUSTek Computer                  | 3         | 1.02%   |
| Sierra Wireless                   | 2         | 0.68%   |
| Samsung Electronics               | 2         | 0.68%   |
| Ralink Technology                 | 2         | 0.68%   |
| Ericsson Business Mobile Networks | 2         | 0.68%   |
| Broadcom Limited                  | 2         | 0.68%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.34%   |
| Lenovo                            | 1         | 0.34%   |
| JMicron Technology                | 1         | 0.34%   |
| Dell                              | 1         | 0.34%   |
| ASIX Electronics                  | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 17.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 4.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 2.97%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.7%    |
| Intel Wireless 7260                                               | 9         | 2.43%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 5         | 1.35%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.08%   |
| Intel Wireless 8260                                               | 4         | 1.08%   |
| Intel Wireless 7265                                               | 4         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.81%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.81%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 3         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.81%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.81%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 0.81%   |
| Huawei ATU-L21                                                    | 3         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 101       | 52.06%  |
| Qualcomm Atheros      | 33        | 17.01%  |
| Realtek Semiconductor | 25        | 12.89%  |
| Broadcom              | 17        | 8.76%   |
| Ralink                | 4         | 2.06%   |
| MediaTek              | 3         | 1.55%   |
| ASUSTek Computer      | 3         | 1.55%   |
| Ralink Technology     | 2         | 1.03%   |
| Hewlett-Packard       | 2         | 1.03%   |
| Broadcom Limited      | 2         | 1.03%   |
| Sierra Wireless       | 1         | 0.52%   |
| Dell                  | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 5.67%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 5.15%   |
| Intel Wireless 7260                                                     | 9         | 4.64%   |
| Intel Wireless 8265 / 8275                                              | 8         | 4.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 2.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.58%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.06%   |
| Intel Wireless 8260                                                     | 4         | 2.06%   |
| Intel Wireless 7265                                                     | 4         | 2.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.55%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.55%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.03%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.03%   |
| Intel Wireless 3165                                                     | 2         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.03%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.03%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 1.03%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.03%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                     | 2         | 1.03%   |
| Sierra Wireless MC8305 Modem                                            | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 87        | 50.29%  |
| Intel                            | 56        | 32.37%  |
| Qualcomm Atheros                 | 10        | 5.78%   |
| Broadcom                         | 6         | 3.47%   |
| Marvell Technology Group         | 4         | 2.31%   |
| Huawei Technologies              | 3         | 1.73%   |
| Samsung Electronics              | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Sierra Wireless                  | 1         | 0.58%   |
| Lenovo                           | 1         | 0.58%   |
| JMicron Technology               | 1         | 0.58%   |
| ASIX Electronics                 | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 36.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 8.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.89%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 2.89%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.31%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.73%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 3         | 1.73%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.73%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.73%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 1.73%   |
| Huawei ATU-L21                                                    | 3         | 1.73%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.16%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.16%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.16%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.16%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.16%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 1.16%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.58%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.58%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.58%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.58%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.58%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.58%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.58%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.58%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 52.57%  |
| Ethernet | 163       | 46.57%  |
| Modem    | 3         | 0.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 71.94%  |
| Ethernet | 55        | 28.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 157       | 84.86%  |
| 1     | 28        | 15.14%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 179       | 96.24%  |
| Yes  | 7         | 3.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 45.1%   |
| Realtek Semiconductor           | 14        | 9.15%   |
| Qualcomm Atheros Communications | 14        | 9.15%   |
| IMC Networks                    | 14        | 9.15%   |
| Broadcom                        | 14        | 9.15%   |
| Hewlett-Packard                 | 6         | 3.92%   |
| Toshiba                         | 3         | 1.96%   |
| Ralink                          | 3         | 1.96%   |
| Lite-On Technology              | 3         | 1.96%   |
| Cambridge Silicon Radio         | 3         | 1.96%   |
| Foxconn International           | 2         | 1.31%   |
| Foxconn / Hon Hai               | 2         | 1.31%   |
| ASUSTek Computer                | 2         | 1.31%   |
| Askey Computer                  | 2         | 1.31%   |
| Ralink Technology               | 1         | 0.65%   |
| Chicony Electronics             | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 24        | 15.69%  |
| Intel AX201 Bluetooth                               | 16        | 10.46%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 7.19%   |
| Intel AX200 Bluetooth                               | 10        | 6.54%   |
| Realtek Bluetooth Radio                             | 6         | 3.92%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 3.92%   |
| IMC Networks Bluetooth Radio                        | 6         | 3.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 3.27%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.61%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.96%   |
| IMC Networks Bluetooth Device                       | 3         | 1.96%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.96%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 1.31%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.31%   |
| Intel AX210 Bluetooth                               | 2         | 1.31%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.31%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.31%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.31%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.31%   |
| Askey Bluetooth Device                              | 2         | 1.31%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.65%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.65%   |
| Realtek CSR BS8510                                  | 1         | 0.65%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.65%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.65%   |
| Lite-On Bluetooth Device                            | 1         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.65%   |
| Intel Bluetooth Device                              | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 68.78%  |
| AMD                              | 38        | 17.19%  |
| Nvidia                           | 24        | 10.86%  |
| Texas Instruments                | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Logitech                         | 1         | 0.45%   |
| Lenovo                           | 1         | 0.45%   |
| JMTek                            | 1         | 0.45%   |
| Hewlett-Packard                  | 1         | 0.45%   |
| C-Media Electronics              | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 7.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 5.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 5.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 13        | 4.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 4.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 4.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 4.1%    |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 3.73%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 3.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 3.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.87%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.49%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.12%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.12%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.75%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 26.77%  |
| SK hynix            | 32        | 25.2%   |
| Micron Technology   | 17        | 13.39%  |
| Unknown             | 10        | 7.87%   |
| Crucial             | 9         | 7.09%   |
| Kingston            | 7         | 5.51%   |
| Nanya Technology    | 4         | 3.15%   |
| Elpida              | 4         | 3.15%   |
| Ramaxel Technology  | 3         | 2.36%   |
| Qimonda             | 2         | 1.57%   |
| A-DATA Technology   | 2         | 1.57%   |
| Team                | 1         | 0.79%   |
| Patriot             | 1         | 0.79%   |
| ChangXin Memory     | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.14%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 2.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 2.14%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 2         | 1.43%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.43%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 2         | 1.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 1.43%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 2         | 1.43%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 1.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 2         | 1.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.43%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 2         | 1.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.43%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 1.43%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s   | 2         | 1.43%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 1.43%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.71%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.71%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.71%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM DRAM                     | 1         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s     | 1         | 0.71%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s              | 1         | 0.71%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 0.71%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 0.71%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 1         | 0.71%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s             | 1         | 0.71%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s             | 1         | 0.71%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.71%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s      | 1         | 0.71%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR 667MT/s     | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 43.81%  |
| DDR3   | 37        | 35.24%  |
| DDR2   | 9         | 8.57%   |
| SDRAM  | 4         | 3.81%   |
| LPDDR4 | 4         | 3.81%   |
| LPDDR3 | 3         | 2.86%   |
| DRAM   | 1         | 0.95%   |
| DDR5   | 1         | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 97        | 90.65%  |
| Row Of Chips | 9         | 8.41%   |
| Chip         | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 37        | 33.04%  |
| 4096  | 29        | 25.89%  |
| 16384 | 20        | 17.86%  |
| 2048  | 17        | 15.18%  |
| 1024  | 4         | 3.57%   |
| 32768 | 3         | 2.68%   |
| 512   | 2         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 22.03%  |
| 2667    | 25        | 21.19%  |
| 3200    | 14        | 11.86%  |
| 1334    | 10        | 8.47%   |
| 2400    | 7         | 5.93%   |
| 2133    | 6         | 5.08%   |
| 1333    | 6         | 5.08%   |
| 667     | 5         | 4.24%   |
| Unknown | 4         | 3.39%   |
| 4267    | 3         | 2.54%   |
| 4199    | 2         | 1.69%   |
| 2048    | 2         | 1.69%   |
| 8400    | 1         | 0.85%   |
| 4800    | 1         | 0.85%   |
| 3733    | 1         | 0.85%   |
| 1867    | 1         | 0.85%   |
| 1067    | 1         | 0.85%   |
| 975     | 1         | 0.85%   |
| 800     | 1         | 0.85%   |
| 533     | 1         | 0.85%   |

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
| Chicony Electronics                    | 47        | 29.94%  |
| IMC Networks                           | 20        | 12.74%  |
| Quanta                                 | 15        | 9.55%   |
| Realtek Semiconductor                  | 12        | 7.64%   |
| Sunplus Innovation Technology          | 9         | 5.73%   |
| Microdia                               | 9         | 5.73%   |
| Lite-On Technology                     | 7         | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.82%   |
| Bison Electronics                      | 6         | 3.82%   |
| Acer                                   | 5         | 3.18%   |
| Syntek                                 | 3         | 1.91%   |
| Suyin                                  | 3         | 1.91%   |
| Primax Electronics                     | 3         | 1.91%   |
| Lenovo                                 | 3         | 1.91%   |
| Generalplus Technology                 | 2         | 1.27%   |
| Silicon Motion                         | 1         | 0.64%   |
| Samsung Electronics                    | 1         | 0.64%   |
| Ricoh                                  | 1         | 0.64%   |
| Qtech                                  | 1         | 0.64%   |
| Luxvisions Innotech Limited            | 1         | 0.64%   |
| Logitech                               | 1         | 0.64%   |
| Apple                                  | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 5.73%   |
| IMC Networks Integrated Camera                              | 8         | 5.1%    |
| Microdia Integrated_Webcam_HD                               | 7         | 4.46%   |
| Sunplus HP HD Webcam [Fixed]                                | 4         | 2.55%   |
| Quanta HP HD Camera                                         | 4         | 2.55%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2.55%   |
| Syntek Lenovo EasyCamera                                    | 3         | 1.91%   |
| Quanta HP TrueVision HD Camera                              | 3         | 1.91%   |
| Primax HP HD Webcam [Fixed]                                 | 3         | 1.91%   |
| Lite-On HP HD Webcam                                        | 3         | 1.91%   |
| Chicony HP HD Webcam                                        | 3         | 1.91%   |
| Chicony HP HD Camera                                        | 3         | 1.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 3         | 1.91%   |
| Bison Integrated Camera                                     | 3         | 1.91%   |
| Sunplus HD Webcam                                           | 2         | 1.27%   |
| Realtek USB Camera                                          | 2         | 1.27%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.27%   |
| Realtek Asus laptop camera                                  | 2         | 1.27%   |
| Quanta HP Webcam                                            | 2         | 1.27%   |
| Lite-On Integrated Camera                                   | 2         | 1.27%   |
| Lite-On HP HD Camera                                        | 2         | 1.27%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 1.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.27%   |
| IMC Networks Integrated Webcam                              | 2         | 1.27%   |
| Generalplus GENERAL WEBCAM                                  | 2         | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.27%   |
| Chicony USB2.0 UVC WebCam                                   | 2         | 1.27%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.27%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.27%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.27%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.27%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.27%   |
| Chicony HP Webcam                                           | 2         | 1.27%   |
| Chicony HP TrueVision HD Camera                             | 2         | 1.27%   |
| Chicony FJ Camera                                           | 2         | 1.27%   |
| Acer Integrated IR Camera                                   | 2         | 1.27%   |
| Suyin HP Webcam-50                                          | 1         | 0.64%   |
| Suyin HP Truevision HD                                      | 1         | 0.64%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.64%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 35.85%  |
| Validity Sensors           | 16        | 30.19%  |
| AuthenTec                  | 6         | 11.32%  |
| Shenzhen Goodix Technology | 5         | 9.43%   |
| Upek                       | 4         | 7.55%   |
| Elan Microelectronics      | 2         | 3.77%   |
| STMicroelectronics         | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 11.32%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 9.43%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 7.55%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 7.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 7.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.66%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 5.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.77%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 3.77%   |
| AuthenTec AES2810                                                          | 2         | 3.77%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.89%   |
| Validity Sensors VFS491                                                    | 1         | 1.89%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.89%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.89%   |
| Synaptics UWP WBDI                                                         | 1         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.89%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.89%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.89%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.89%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.89%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.89%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.89%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.89%   |
| AuthenTec AES1600                                                          | 1         | 1.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 8         | 50%     |
| Broadcom    | 5         | 31.25%  |
| O2 Micro    | 2         | 12.5%   |
| Upek        | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 50%     |
| Broadcom 58200                                                               | 3         | 18.75%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 98        | 52.41%  |
| 1     | 60        | 32.09%  |
| 2     | 27        | 14.44%  |
| 10    | 1         | 0.53%   |
| 3     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 43.8%   |
| Graphics card            | 20        | 16.53%  |
| Chipcard                 | 14        | 11.57%  |
| Net/wireless             | 12        | 9.92%   |
| Bluetooth                | 6         | 4.96%   |
| Multimedia controller    | 4         | 3.31%   |
| Communication controller | 4         | 3.31%   |
| Storage                  | 2         | 1.65%   |
| Camera                   | 2         | 1.65%   |
| Sound                    | 1         | 0.83%   |
| Net/ethernet             | 1         | 0.83%   |
| Flash memory             | 1         | 0.83%   |
| Card reader              | 1         | 0.83%   |

