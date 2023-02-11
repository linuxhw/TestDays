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

Total: 270

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 27        | 14.75%  |
| Ubuntu 18.04        | 14        | 7.65%   |
| Ubuntu 22.04        | 8         | 4.37%   |
| Debian 11           | 7         | 3.83%   |
| KDE neon 20.04      | 5         | 2.73%   |
| Zorin 16            | 4         | 2.19%   |
| Fedora 34           | 4         | 2.19%   |
| ArcoLinux Rolling   | 4         | 2.19%   |
| Arch                | 4         | 2.19%   |
| Zorin 15            | 3         | 1.64%   |
| Xubuntu 20.04       | 3         | 1.64%   |
| OpenMandriva 4.3    | 3         | 1.64%   |
| Linux Mint 19.1     | 3         | 1.64%   |
| Kubuntu 22.04       | 3         | 1.64%   |
| Kubuntu 21.10       | 3         | 1.64%   |
| Kubuntu 20.04       | 3         | 1.64%   |
| Fedora 33           | 3         | 1.64%   |
| Debian Testing      | 3         | 1.64%   |
| Ubuntu Unity 16.04  | 2         | 1.09%   |
| Ubuntu 21.10        | 2         | 1.09%   |
| Ubuntu 21.04        | 2         | 1.09%   |
| Ubuntu 20.10        | 2         | 1.09%   |
| Ubuntu 19.10        | 2         | 1.09%   |
| Pop!_OS 21.04       | 2         | 1.09%   |
| Manjaro 20.2        | 2         | 1.09%   |
| Manjaro             | 2         | 1.09%   |
| Linux Mint 21       | 2         | 1.09%   |
| Kubuntu 18.04       | 2         | 1.09%   |
| Gentoo 2.6          | 2         | 1.09%   |
| Endless 3.5.8       | 2         | 1.09%   |
| EndeavourOS         | 2         | 1.09%   |
| Arch Rolling        | 2         | 1.09%   |
| Xubuntu 22.04       | 1         | 0.55%   |
| Ubuntu MATE 22.04   | 1         | 0.55%   |
| Ubuntu Budgie 22.04 | 1         | 0.55%   |
| Ubuntu Budgie 20.04 | 1         | 0.55%   |
| Ubuntu 19.04        | 1         | 0.55%   |
| ROSA R9             | 1         | 0.55%   |
| ROSA R8             | 1         | 0.55%   |
| Q4OS 4              | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 55        | 31.61%  |
| Kubuntu       | 12        | 6.9%    |
| Debian        | 12        | 6.9%    |
| Fedora        | 11        | 6.32%   |
| Linux Mint    | 9         | 5.17%   |
| Manjaro       | 8         | 4.6%    |
| Endless       | 8         | 4.6%    |
| Zorin         | 7         | 4.02%   |
| KDE neon      | 7         | 4.02%   |
| Arch          | 6         | 3.45%   |
| OpenMandriva  | 5         | 2.87%   |
| Xubuntu       | 4         | 2.3%    |
| Pop!_OS       | 4         | 2.3%    |
| ArcoLinux     | 4         | 2.3%    |
| Ubuntu Unity  | 2         | 1.15%   |
| Ubuntu Budgie | 2         | 1.15%   |
| Lubuntu       | 2         | 1.15%   |
| Gentoo        | 2         | 1.15%   |
| EndeavourOS   | 2         | 1.15%   |
| Elementary    | 2         | 1.15%   |
| Ubuntu MATE   | 1         | 0.57%   |
| ROSA          | 1         | 0.57%   |
| Q4OS          | 1         | 0.57%   |
| openSUSE      | 1         | 0.57%   |
| LMDE          | 1         | 0.57%   |
| Kali          | 1         | 0.57%   |
| Garuda Linux  | 1         | 0.57%   |
| Clear Linux   | 1         | 0.57%   |
| Chrome OS     | 1         | 0.57%   |
| BlackPanther  | 1         | 0.57%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 4         | 2%      |
| 4.18.0-15-generic       | 4         | 2%      |
| 5.8.0-41-generic        | 3         | 1.5%    |
| 5.3.0-40-generic        | 3         | 1.5%    |
| 5.16.7-desktop-1omv4003 | 3         | 1.5%    |
| 5.15.0-57-generic       | 3         | 1.5%    |
| 5.15.0-56-generic       | 3         | 1.5%    |
| 5.15.0-43-generic       | 3         | 1.5%    |
| 5.13.0-41-generic       | 3         | 1.5%    |
| 5.13.0-30-generic       | 3         | 1.5%    |
| 5.13.0-28-generic       | 3         | 1.5%    |
| 5.13.0-21-generic       | 3         | 1.5%    |
| 5.8.0-44-generic        | 2         | 1%      |
| 5.8.0-14-generic        | 2         | 1%      |
| 5.6.0-1-amd64           | 2         | 1%      |
| 5.4.0-70-generic        | 2         | 1%      |
| 5.4.0-56-generic        | 2         | 1%      |
| 5.4.0-54-generic        | 2         | 1%      |
| 5.4.0-48-generic        | 2         | 1%      |
| 5.4.0-40-generic        | 2         | 1%      |
| 5.4.0-33-generic        | 2         | 1%      |
| 5.4.0-28-generic        | 2         | 1%      |
| 5.4.0-26-generic        | 2         | 1%      |
| 5.15.0-47-generic       | 2         | 1%      |
| 5.15.0-46-generic       | 2         | 1%      |
| 5.13.19-2-MANJARO       | 2         | 1%      |
| 5.13.0-7614-generic     | 2         | 1%      |
| 5.11.0-43-generic       | 2         | 1%      |
| 5.11.0-40-generic       | 2         | 1%      |
| 5.11.0-35-generic       | 2         | 1%      |
| 5.10.0-8-amd64          | 2         | 1%      |
| 4.15.0-128-generic      | 2         | 1%      |
| 6.1.5-arch2-1           | 1         | 0.5%    |
| 6.1.1-desktop-1omv2290  | 1         | 0.5%    |
| 6.0.7-1-default         | 1         | 0.5%    |
| 6.0.11-zen1-1-zen       | 1         | 0.5%    |
| 6.0.11-300.fc37.x86_64  | 1         | 0.5%    |
| 5.9.8-2-MANJARO         | 1         | 0.5%    |
| 5.9.2-arch1-1           | 1         | 0.5%    |
| 5.9.15-200.fc33.x86_64  | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 16.93%  |
| 5.15.0  | 17        | 8.99%   |
| 5.13.0  | 17        | 8.99%   |
| 5.11.0  | 12        | 6.35%   |
| 4.15.0  | 10        | 5.29%   |
| 5.8.0   | 9         | 4.76%   |
| 5.3.0   | 8         | 4.23%   |
| 5.10.0  | 8         | 4.23%   |
| 4.18.0  | 8         | 4.23%   |
| 5.0.0   | 4         | 2.12%   |
| 5.6.0   | 3         | 1.59%   |
| 5.16.7  | 3         | 1.59%   |
| 6.0.11  | 2         | 1.06%   |
| 5.13.19 | 2         | 1.06%   |
| 5.10.14 | 2         | 1.06%   |
| 6.1.5   | 1         | 0.53%   |
| 6.1.1   | 1         | 0.53%   |
| 6.0.7   | 1         | 0.53%   |
| 5.9.8   | 1         | 0.53%   |
| 5.9.2   | 1         | 0.53%   |
| 5.9.15  | 1         | 0.53%   |
| 5.9.14  | 1         | 0.53%   |
| 5.8.8   | 1         | 0.53%   |
| 5.8.5   | 1         | 0.53%   |
| 5.8.18  | 1         | 0.53%   |
| 5.8.10  | 1         | 0.53%   |
| 5.7.13  | 1         | 0.53%   |
| 5.6.14  | 1         | 0.53%   |
| 5.5.15  | 1         | 0.53%   |
| 5.5.0   | 1         | 0.53%   |
| 5.4.80  | 1         | 0.53%   |
| 5.4.53  | 1         | 0.53%   |
| 5.4.27  | 1         | 0.53%   |
| 5.3.6   | 1         | 0.53%   |
| 5.19.7  | 1         | 0.53%   |
| 5.19.5  | 1         | 0.53%   |
| 5.19.16 | 1         | 0.53%   |
| 5.19.0  | 1         | 0.53%   |
| 5.18.0  | 1         | 0.53%   |
| 5.17.5  | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 18.18%  |
| 5.15    | 21        | 11.23%  |
| 5.13    | 20        | 10.7%   |
| 5.11    | 14        | 7.49%   |
| 5.8     | 13        | 6.95%   |
| 5.10    | 10        | 5.35%   |
| 4.15    | 10        | 5.35%   |
| 5.3     | 9         | 4.81%   |
| 4.18    | 9         | 4.81%   |
| 5.16    | 7         | 3.74%   |
| 5.9     | 4         | 2.14%   |
| 5.6     | 4         | 2.14%   |
| 5.19    | 4         | 2.14%   |
| 5.17    | 4         | 2.14%   |
| 5.0     | 4         | 2.14%   |
| 6.0     | 3         | 1.6%    |
| 5.14    | 3         | 1.6%    |
| 5.12    | 3         | 1.6%    |
| 6.1     | 2         | 1.07%   |
| 5.5     | 2         | 1.07%   |
| 4.19    | 2         | 1.07%   |
| 5.7     | 1         | 0.53%   |
| 5.18    | 1         | 0.53%   |
| 4.9     | 1         | 0.53%   |
| 4.14    | 1         | 0.53%   |
| 4.1     | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 162       | 97.59%  |
| i686   | 4         | 2.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 71        | 40.8%   |
| KDE5       | 33        | 18.97%  |
| Unknown    | 26        | 14.94%  |
| XFCE       | 15        | 8.62%   |
| X-Cinnamon | 5         | 2.87%   |
| LXQt       | 4         | 2.3%    |
| MATE       | 3         | 1.72%   |
| KDE        | 3         | 1.72%   |
| Unity      | 2         | 1.15%   |
| Pantheon   | 2         | 1.15%   |
| LXDE       | 2         | 1.15%   |
| Cinnamon   | 2         | 1.15%   |
| Budgie     | 2         | 1.15%   |
| Trinity    | 1         | 0.57%   |
| Openbox    | 1         | 0.57%   |
| i3         | 1         | 0.57%   |
| DWM        | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 127       | 72.99%  |
| Wayland | 26        | 14.94%  |
| Unknown | 18        | 10.34%  |
| Tty     | 3         | 1.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 48%     |
| SDDM    | 29        | 16.57%  |
| GDM     | 21        | 12%     |
| LightDM | 16        | 9.14%   |
| GDM3    | 16        | 9.14%   |
| TDM     | 9         | 5.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 85        | 50.3%   |
| sl_SI   | 39        | 23.08%  |
| Unknown | 26        | 15.38%  |
| en_GB   | 7         | 4.14%   |
| en_SI   | 4         | 2.37%   |
| it_IT   | 3         | 1.78%   |
| C       | 2         | 1.18%   |
| pt_PT   | 1         | 0.59%   |
| nl_NL   | 1         | 0.59%   |
| hr_HR   | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 50.59%  |
| BIOS | 84        | 49.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 140       | 81.87%  |
| Overlay | 11        | 6.43%   |
| Btrfs   | 10        | 5.85%   |
| Unknown | 8         | 4.68%   |
| Zfs     | 1         | 0.58%   |
| Ext2    | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 96        | 55.49%  |
| GPT     | 52        | 30.06%  |
| MBR     | 25        | 14.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 92.31%  |
| Yes       | 13        | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 122       | 72.19%  |
| Yes       | 47        | 27.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 52        | 31.33%  |
| Lenovo              | 47        | 28.31%  |
| ASUSTek Computer    | 22        | 13.25%  |
| Dell                | 16        | 9.64%   |
| Toshiba             | 8         | 4.82%   |
| Acer                | 6         | 3.61%   |
| Fujitsu             | 3         | 1.81%   |
| MSI                 | 2         | 1.2%    |
| TUXEDO              | 1         | 0.6%    |
| Razer               | 1         | 0.6%    |
| PC Specialist       | 1         | 0.6%    |
| Panasonic           | 1         | 0.6%    |
| Medion              | 1         | 0.6%    |
| HUAWEI              | 1         | 0.6%    |
| Gigabyte Technology | 1         | 0.6%    |
| Fujitsu Siemens     | 1         | 0.6%    |
| Framework           | 1         | 0.6%    |
| eMachines           | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                      | 3         | 1.81%   |
| Toshiba Satellite L750                     | 2         | 1.2%    |
| Lenovo ThinkPad T410 2522A92               | 2         | 1.2%    |
| HP EliteBook 8760w                         | 2         | 1.2%    |
| Dell Inspiron 5570                         | 2         | 1.2%    |
| Dell Inspiron 1501                         | 2         | 1.2%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 1.2%    |
| Unknown                                    | 2         | 1.2%    |
| TUXEDO Aura 15 Gen1                        | 1         | 0.6%    |
| Toshiba TECRA S10                          | 1         | 0.6%    |
| Toshiba TECRA A11                          | 1         | 0.6%    |
| Toshiba Satellite R630                     | 1         | 0.6%    |
| Toshiba Satellite Pro U400                 | 1         | 0.6%    |
| Toshiba Satellite A100                     | 1         | 0.6%    |
| Toshiba QOSMIO X500                        | 1         | 0.6%    |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.6%    |
| PC Specialist Fusion IV                    | 1         | 0.6%    |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.6%    |
| MSI U210                                   | 1         | 0.6%    |
| MSI GP60 2OD                               | 1         | 0.6%    |
| Medion E7218                               | 1         | 0.6%    |
| Lenovo Yoga S740-14IIL 81RS                | 1         | 0.6%    |
| Lenovo Yoga 2 13 20344                     | 1         | 0.6%    |
| Lenovo V15 G2 ALC 82KD                     | 1         | 0.6%    |
| Lenovo ThinkPad X250 20CM004ESC            | 1         | 0.6%    |
| Lenovo ThinkPad X230 23202DG               | 1         | 0.6%    |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.6%    |
| Lenovo ThinkPad W530 24479K4               | 1         | 0.6%    |
| Lenovo ThinkPad T61 8897CTO                | 1         | 0.6%    |
| Lenovo ThinkPad T590 20N5S0YN00            | 1         | 0.6%    |
| Lenovo ThinkPad T590 20N5S0MR00            | 1         | 0.6%    |
| Lenovo ThinkPad T500 2055WYX               | 1         | 0.6%    |
| Lenovo ThinkPad T490s 20NYS4HL07           | 1         | 0.6%    |
| Lenovo ThinkPad T480 20L6S58700            | 1         | 0.6%    |
| Lenovo ThinkPad T480 20L6S01W00            | 1         | 0.6%    |
| Lenovo ThinkPad T460s 20FAS7XT01           | 1         | 0.6%    |
| Lenovo ThinkPad T420 4236A78               | 1         | 0.6%    |
| Lenovo ThinkPad T420 423662G               | 1         | 0.6%    |
| Lenovo ThinkPad T15 Gen 1 20S6000NSC       | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 32        | 19.28%  |
| HP EliteBook           | 12        | 7.23%   |
| HP ProBook             | 10        | 6.02%   |
| Dell Inspiron          | 7         | 4.22%   |
| Toshiba Satellite      | 5         | 3.01%   |
| Lenovo IdeaPad         | 5         | 3.01%   |
| HP ZBook               | 5         | 3.01%   |
| Dell Latitude          | 5         | 3.01%   |
| HP Pavilion            | 4         | 2.41%   |
| HP 255                 | 4         | 2.41%   |
| HP 250                 | 4         | 2.41%   |
| ASUS VivoBook          | 4         | 2.41%   |
| HP Compaq              | 3         | 1.81%   |
| Fujitsu LIFEBOOK       | 3         | 1.81%   |
| ASUS ASUS              | 3         | 1.81%   |
| Acer Aspire            | 3         | 1.81%   |
| Toshiba TECRA          | 2         | 1.2%    |
| Lenovo Yoga            | 2         | 1.2%    |
| HP Laptop              | 2         | 1.2%    |
| Dell XPS               | 2         | 1.2%    |
| Acer Predator          | 2         | 1.2%    |
| Unknown                | 2         | 1.2%    |
| TUXEDO Aura            | 1         | 0.6%    |
| Toshiba QOSMIO         | 1         | 0.6%    |
| Razer Blade            | 1         | 0.6%    |
| PC Specialist Fusion   | 1         | 0.6%    |
| Panasonic CF-53SWWZ5MG | 1         | 0.6%    |
| MSI U210               | 1         | 0.6%    |
| MSI GP60               | 1         | 0.6%    |
| Medion E7218           | 1         | 0.6%    |
| Lenovo V15             | 1         | 0.6%    |
| Lenovo Legion          | 1         | 0.6%    |
| Lenovo G585            | 1         | 0.6%    |
| Lenovo G510            | 1         | 0.6%    |
| Lenovo G500            | 1         | 0.6%    |
| Lenovo G50-30          | 1         | 0.6%    |
| Lenovo B50-80          | 1         | 0.6%    |
| Lenovo B50-30          | 1         | 0.6%    |
| HUAWEI HKD-WXX         | 1         | 0.6%    |
| HP OMEN                | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 23        | 13.86%  |
| 2020 | 16        | 9.64%   |
| 2011 | 14        | 8.43%   |
| 2018 | 13        | 7.83%   |
| 2014 | 12        | 7.23%   |
| 2013 | 12        | 7.23%   |
| 2017 | 11        | 6.63%   |
| 2010 | 11        | 6.63%   |
| 2021 | 9         | 5.42%   |
| 2012 | 9         | 5.42%   |
| 2008 | 9         | 5.42%   |
| 2009 | 8         | 4.82%   |
| 2015 | 7         | 4.22%   |
| 2007 | 4         | 2.41%   |
| 2006 | 4         | 2.41%   |
| 2016 | 3         | 1.81%   |
| 2022 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 166       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 153       | 90.53%  |
| Enabled  | 16        | 9.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 165       | 99.4%   |
| Yes  | 1         | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 46        | 27.54%  |
| 4.01-8.0    | 35        | 20.96%  |
| 8.01-16.0   | 34        | 20.36%  |
| 16.01-24.0  | 29        | 17.37%  |
| 32.01-64.0  | 12        | 7.19%   |
| 1.01-2.0    | 6         | 3.59%   |
| 24.01-32.0  | 2         | 1.2%    |
| 2.01-3.0    | 2         | 1.2%    |
| 64.01-256.0 | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 62        | 32.8%   |
| 2.01-3.0   | 53        | 28.04%  |
| 4.01-8.0   | 23        | 12.17%  |
| 3.01-4.0   | 23        | 12.17%  |
| 0.51-1.0   | 16        | 8.47%   |
| 8.01-16.0  | 8         | 4.23%   |
| 0.01-0.5   | 3         | 1.59%   |
| 16.01-24.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 128       | 75.29%  |
| 2      | 33        | 19.41%  |
| 0      | 5         | 2.94%   |
| 3      | 4         | 2.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 53.61%  |
| Yes       | 77        | 46.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 88.62%  |
| No        | 19        | 11.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 99.4%   |
| No        | 1         | 0.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 80.95%  |
| No        | 32        | 19.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovenia | 166       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 62        | 33.51%  |
| Kranj                   | 7         | 3.78%   |
| Celje                   | 6         | 3.24%   |
| Vrhnika                 | 4         | 2.16%   |
| Trzin                   | 4         | 2.16%   |
| Poljane nad Skofjo Loko | 4         | 2.16%   |
| Maribor                 | 4         | 2.16%   |
| Slovenske Konjice       | 3         | 1.62%   |
| Portorož               | 3         | 1.62%   |
| Murska Sobota           | 3         | 1.62%   |
| Koper                   | 3         | 1.62%   |
| Ajdovščina            | 3         | 1.62%   |
| Žalec                  | 2         | 1.08%   |
| Smarje pri Jelsah       | 2         | 1.08%   |
| Slovenj Gradec          | 2         | 1.08%   |
| Sežana                 | 2         | 1.08%   |
| Puconci                 | 2         | 1.08%   |
| Petrovce                | 2         | 1.08%   |
| Nova Gorica             | 2         | 1.08%   |
| Grosuplje               | 2         | 1.08%   |
| Blejska Dobrava         | 2         | 1.08%   |
| Žužemberk             | 1         | 0.54%   |
| Ziri                    | 1         | 0.54%   |
| Zgornji Leskovec        | 1         | 0.54%   |
| Zgornja Besnica         | 1         | 0.54%   |
| Zagorje ob Savi         | 1         | 0.54%   |
| Visoko                  | 1         | 0.54%   |
| Vipava                  | 1         | 0.54%   |
| Velenje                 | 1         | 0.54%   |
| Trzic                   | 1         | 0.54%   |
| Trbovlje                | 1         | 0.54%   |
| Tabor                   | 1         | 0.54%   |
| Solkan                  | 1         | 0.54%   |
| Smartno ob Paki         | 1         | 0.54%   |
| Skofljica               | 1         | 0.54%   |
| Škofja Loka            | 1         | 0.54%   |
| Skocjan                 | 1         | 0.54%   |
| Šentjernej             | 1         | 0.54%   |
| Sempeter pri Gorici     | 1         | 0.54%   |
| Ruše                   | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 31        | 43     | 15.98%  |
| Seagate                 | 20        | 23     | 10.31%  |
| Crucial                 | 17        | 23     | 8.76%   |
| WDC                     | 16        | 16     | 8.25%   |
| Toshiba                 | 16        | 24     | 8.25%   |
| Kingston                | 13        | 19     | 6.7%    |
| SK hynix                | 12        | 16     | 6.19%   |
| SanDisk                 | 12        | 14     | 6.19%   |
| HGST                    | 9         | 10     | 4.64%   |
| Hitachi                 | 8         | 11     | 4.12%   |
| Unknown                 | 5         | 6      | 2.58%   |
| Intel                   | 4         | 4      | 2.06%   |
| Intenso                 | 3         | 3      | 1.55%   |
| Fujitsu                 | 3         | 4      | 1.55%   |
| Transcend               | 2         | 2      | 1.03%   |
| PNY                     | 2         | 2      | 1.03%   |
| OCZ                     | 2         | 2      | 1.03%   |
| Micron Technology       | 2         | 2      | 1.03%   |
| LITEON                  | 2         | 2      | 1.03%   |
| Lenovo                  | 2         | 2      | 1.03%   |
| KIOXIA                  | 2         | 2      | 1.03%   |
| JMicron Technology      | 2         | 2      | 1.03%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.52%   |
| Team                    | 1         | 1      | 0.52%   |
| Silicon Motion          | 1         | 2      | 0.52%   |
| SABRENT                 | 1         | 1      | 0.52%   |
| Patriot                 | 1         | 2      | 0.52%   |
| LITEONIT                | 1         | 2      | 0.52%   |
| HGST HTS                | 1         | 1      | 0.52%   |
| Gigabyte Technology     | 1         | 2      | 0.52%   |
| Corsair                 | 1         | 3      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                        | 5         | 2.5%    |
| HGST HTS721010A9E630 1TB                            | 5         | 2.5%    |
| Hitachi HTS547575A9E384 752GB                       | 3         | 1.5%    |
| Crucial CT240BX500SSD1 240GB                        | 3         | 1.5%    |
| Toshiba MQ04ABF100 1TB                              | 2         | 1%      |
| Toshiba MQ01ABF050 500GB                            | 2         | 1%      |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 1%      |
| Seagate ST9750420AS 752GB                           | 2         | 1%      |
| Seagate ST9500325AS 500GB                           | 2         | 1%      |
| Seagate ST9320423AS 320GB                           | 2         | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1%      |
| SanDisk NVMe SSD Drive 512GB                        | 2         | 1%      |
| Samsung SSD 860 EVO 250GB                           | 2         | 1%      |
| Samsung SSD 850 EVO 250GB                           | 2         | 1%      |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 2         | 1%      |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 1%      |
| PNY CS900 120GB SSD                                 | 2         | 1%      |
| Lenovo NVMe SSD Drive 256GB                         | 2         | 1%      |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1%      |
| Kingston SA400S37120G 120GB SSD                     | 2         | 1%      |
| Hitachi HTS725032A9A364 320GB                       | 2         | 1%      |
| HGST HTS545050A7E680 500GB                          | 2         | 1%      |
| Crucial CT2000MX500SSD1 2TB                         | 2         | 1%      |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.5%    |
| WDC WDS120G2G0B-00EPW0 120GB SSD                    | 1         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1         | 0.5%    |
| WDC WDS100T3X0C-00SJG0 1TB                          | 1         | 0.5%    |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.5%    |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 0.5%    |
| WDC WD3200BEKT-22KA9T0 320GB                        | 1         | 0.5%    |
| WDC WD2500BEVT-60ZCT1 250GB                         | 1         | 0.5%    |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.5%    |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 0.5%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 1         | 0.5%    |
| WDC PC SN520 SDAPMUW-512G-1001 512GB                | 1         | 0.5%    |
| WDC PC SN520 NVMe 512GB                             | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 20        | 23     | 35.09%  |
| Toshiba  | 9         | 15     | 15.79%  |
| HGST     | 9         | 10     | 15.79%  |
| Hitachi  | 8         | 11     | 14.04%  |
| WDC      | 6         | 6      | 10.53%  |
| Fujitsu  | 3         | 4      | 5.26%   |
| SABRENT  | 1         | 1      | 1.75%   |
| HGST HTS | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 16        | 22     | 21.33%  |
| Samsung Electronics | 14        | 17     | 18.67%  |
| Kingston            | 10        | 15     | 13.33%  |
| SanDisk             | 7         | 9      | 9.33%   |
| WDC                 | 5         | 5      | 6.67%   |
| SK hynix            | 4         | 4      | 5.33%   |
| Transcend           | 2         | 2      | 2.67%   |
| PNY                 | 2         | 2      | 2.67%   |
| OCZ                 | 2         | 2      | 2.67%   |
| LITEON              | 2         | 2      | 2.67%   |
| Intenso             | 2         | 2      | 2.67%   |
| Toshiba             | 1         | 1      | 1.33%   |
| Team                | 1         | 1      | 1.33%   |
| Patriot             | 1         | 2      | 1.33%   |
| Micron Technology   | 1         | 1      | 1.33%   |
| LITEONIT            | 1         | 2      | 1.33%   |
| JMicron Technology  | 1         | 1      | 1.33%   |
| Intel               | 1         | 1      | 1.33%   |
| Gigabyte Technology | 1         | 2      | 1.33%   |
| Corsair             | 1         | 3      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 70        | 96     | 38.04%  |
| HDD     | 55        | 71     | 29.89%  |
| NVMe    | 53        | 73     | 28.8%   |
| MMC     | 4         | 5      | 2.17%   |
| Unknown | 2         | 2      | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 112       | 160    | 63.64%  |
| NVMe | 53        | 73     | 30.11%  |
| SAS  | 7         | 9      | 3.98%   |
| MMC  | 4         | 5      | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 120    | 70.16%  |
| 0.51-1.0   | 32        | 40     | 25.81%  |
| 1.01-2.0   | 5         | 7      | 4.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 50        | 28.09%  |
| 101-250        | 50        | 28.09%  |
| 501-1000       | 25        | 14.04%  |
| 1-20           | 13        | 7.3%    |
| 1001-2000      | 11        | 6.18%   |
| 51-100         | 10        | 5.62%   |
| 21-50          | 9         | 5.06%   |
| 2001-3000      | 5         | 2.81%   |
| Unknown        | 3         | 1.69%   |
| More than 3000 | 2         | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 77        | 42.31%  |
| 21-50     | 31        | 17.03%  |
| 101-250   | 26        | 14.29%  |
| 51-100    | 20        | 10.99%  |
| 251-500   | 16        | 8.79%   |
| 501-1000  | 6         | 3.3%    |
| Unknown   | 3         | 1.65%   |
| 1001-2000 | 2         | 1.1%    |
| 2001-3000 | 1         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 2         | 2      | 15.38%  |
| Toshiba MQ01ABF050 500GB              | 1         | 5      | 7.69%   |
| SK hynix HFS256G32MND-2200A 256GB SSD | 1         | 1      | 7.69%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 7.69%   |
| Seagate ST9500423AS 500GB             | 1         | 1      | 7.69%   |
| Seagate ST9500325AS 500GB             | 1         | 2      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 7.69%   |
| SanDisk SD7SB2Q512G1001 512GB SSD     | 1         | 1      | 7.69%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 7.69%   |
| Hitachi HTS727550A9E364 500GB         | 1         | 1      | 7.69%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 7.69%   |
| Crucial CT120M500SSD1 120GB           | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 5      | 30.77%  |
| HGST     | 3         | 3      | 23.08%  |
| Toshiba  | 1         | 5      | 7.69%   |
| SK hynix | 1         | 1      | 7.69%   |
| SanDisk  | 1         | 1      | 7.69%   |
| Kingston | 1         | 1      | 7.69%   |
| Hitachi  | 1         | 1      | 7.69%   |
| Crucial  | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 5      | 44.44%  |
| HGST    | 3         | 3      | 33.33%  |
| Toshiba | 1         | 5      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 14     | 69.23%  |
| SSD  | 4         | 4      | 30.77%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK6465GSX 640GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 100       | 152    | 58.48%  |
| Works    | 57        | 75     | 33.33%  |
| Malfunc  | 13        | 18     | 7.6%    |
| Failed   | 1         | 2      | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 116       | 59.18%  |
| AMD                              | 22        | 11.22%  |
| Samsung Electronics              | 20        | 10.2%   |
| SanDisk                          | 10        | 5.1%    |
| SK hynix                         | 8         | 4.08%   |
| Toshiba America Info Systems     | 7         | 3.57%   |
| Kingston Technology Company      | 3         | 1.53%   |
| Lenovo                           | 2         | 1.02%   |
| KIOXIA                           | 2         | 1.02%   |
| Union Memory (Shenzhen)          | 1         | 0.51%   |
| Silicon Motion                   | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |
| Micron/Crucial Technology        | 1         | 0.51%   |
| Micron Technology                | 1         | 0.51%   |
| Marvell Technology Group         | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 7.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 5.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 5.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 4.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 3.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 3.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 2.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 2.4%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.44%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.44%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.44%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 3         | 1.44%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.96%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 0.96%   |
| SK hynix BC511                                                                 | 2         | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.96%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.96%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.96%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.96%   |
| Intel SSD 660P Series                                                          | 2         | 0.96%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2         | 0.96%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 119       | 59.2%   |
| NVMe | 56        | 27.86%  |
| IDE  | 16        | 7.96%   |
| RAID | 10        | 4.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 82.53%  |
| AMD    | 29        | 17.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 3.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 3.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 3.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.81%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.81%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.81%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 1.81%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 1.2%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.2%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.2%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.2%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.2%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.2%    |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.2%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.2%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.2%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.2%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.2%    |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 1.2%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.2%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.2%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.2%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.2%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 1.2%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.6%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.6%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 48        | 28.92%  |
| Intel Core i5           | 39        | 23.49%  |
| Intel Core 2 Duo        | 14        | 8.43%   |
| Intel Core i3           | 12        | 7.23%   |
| Intel Celeron           | 10        | 6.02%   |
| AMD Ryzen 5             | 6         | 3.61%   |
| Other                   | 5         | 3.01%   |
| Intel Pentium           | 5         | 3.01%   |
| AMD Ryzen 7             | 5         | 3.01%   |
| AMD Ryzen 3             | 5         | 3.01%   |
| AMD Ryzen 9             | 3         | 1.81%   |
| Intel Pentium Silver    | 1         | 0.6%    |
| Intel Pentium Dual      | 1         | 0.6%    |
| Intel Genuine           | 1         | 0.6%    |
| Intel Core 2            | 1         | 0.6%    |
| AMD Turion II Dual-Core | 1         | 0.6%    |
| AMD Turion II           | 1         | 0.6%    |
| AMD Mobile Sempron      | 1         | 0.6%    |
| AMD E1                  | 1         | 0.6%    |
| AMD E                   | 1         | 0.6%    |
| AMD C-60                | 1         | 0.6%    |
| AMD Athlon Neo          | 1         | 0.6%    |
| AMD Athlon 64 X2        | 1         | 0.6%    |
| AMD A8                  | 1         | 0.6%    |
| AMD A6                  | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 84        | 50.6%   |
| 4      | 62        | 37.35%  |
| 6      | 10        | 6.02%   |
| 8      | 7         | 4.22%   |
| 1      | 3         | 1.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 166       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 123       | 74.1%   |
| 1      | 43        | 25.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 160       | 95.81%  |
| Unknown        | 6         | 3.59%   |
| 32-bit         | 1         | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 18.71%  |
| 0x206a7    | 11        | 6.43%   |
| 0x806ec    | 10        | 5.85%   |
| 0x306a9    | 10        | 5.85%   |
| 0x40651    | 9         | 5.26%   |
| 0x306c3    | 7         | 4.09%   |
| 0x20655    | 7         | 4.09%   |
| 0x806ea    | 6         | 3.51%   |
| 0x6fd      | 6         | 3.51%   |
| 0x806c1    | 5         | 2.92%   |
| 0x30678    | 5         | 2.92%   |
| 0x08108102 | 5         | 2.92%   |
| 0x906ea    | 4         | 2.34%   |
| 0x10676    | 4         | 2.34%   |
| 0x906e9    | 3         | 1.75%   |
| 0x706e5    | 3         | 1.75%   |
| 0x406e3    | 3         | 1.75%   |
| 0x306d4    | 3         | 1.75%   |
| 0x20652    | 3         | 1.75%   |
| 0x106e5    | 3         | 1.75%   |
| 0x1067a    | 3         | 1.75%   |
| 0xa0652    | 2         | 1.17%   |
| 0x906ed    | 2         | 1.17%   |
| 0x806eb    | 2         | 1.17%   |
| 0x706a1    | 2         | 1.17%   |
| 0x506c9    | 2         | 1.17%   |
| 0x08608102 | 2         | 1.17%   |
| 0x08600106 | 2         | 1.17%   |
| 0x0810100b | 2         | 1.17%   |
| 0x06001119 | 2         | 1.17%   |
| 0x05000119 | 2         | 1.17%   |
| 0xa0660    | 1         | 0.58%   |
| 0x6fb      | 1         | 0.58%   |
| 0x6e8      | 1         | 0.58%   |
| 0x406c4    | 1         | 0.58%   |
| 0x0a50000c | 1         | 0.58%   |
| 0x08608103 | 1         | 0.58%   |
| 0x08600104 | 1         | 0.58%   |
| 0x0700010f | 1         | 0.58%   |
| 0x010000c8 | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 33        | 19.88%  |
| Haswell       | 18        | 10.84%  |
| SandyBridge   | 12        | 7.23%   |
| IvyBridge     | 12        | 7.23%   |
| Westmere      | 10        | 6.02%   |
| Penryn        | 8         | 4.82%   |
| Core          | 8         | 4.82%   |
| Silvermont    | 7         | 4.22%   |
| Zen+          | 5         | 3.01%   |
| Zen 2         | 5         | 3.01%   |
| TigerLake     | 5         | 3.01%   |
| Broadwell     | 5         | 3.01%   |
| Unknown       | 5         | 3.01%   |
| IceLake       | 4         | 2.41%   |
| Skylake       | 3         | 1.81%   |
| Nehalem       | 3         | 1.81%   |
| K8 Hammer     | 3         | 1.81%   |
| Goldmont plus | 3         | 1.81%   |
| CometLake     | 3         | 1.81%   |
| Zen 3         | 2         | 1.2%    |
| Zen           | 2         | 1.2%    |
| Piledriver    | 2         | 1.2%    |
| K10           | 2         | 1.2%    |
| Goldmont      | 2         | 1.2%    |
| Bobcat        | 2         | 1.2%    |
| P6            | 1         | 0.6%    |
| Jaguar        | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 118       | 55.14%  |
| AMD                              | 53        | 24.77%  |
| Nvidia                           | 42        | 19.63%  |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 11        | 4.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 10        | 4.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 4.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 9         | 4.07%   |
| Intel UHD Graphics 620                                                                | 8         | 3.62%   |
| Intel Core Processor Integrated Graphics Controller                                   | 7         | 3.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 3.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 2.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 6         | 2.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 5         | 2.26%   |
| Intel HD Graphics 5500                                                                | 5         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 2.26%   |
| AMD Renoir                                                                            | 5         | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 2.26%   |
| AMD Lucienne                                                                          | 5         | 2.26%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.81%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 1.36%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.9%    |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 0.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 0.9%    |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                             | 2         | 0.9%    |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 0.9%    |
| Intel HD Graphics 630                                                                 | 2         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 0.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 2         | 0.9%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 2         | 0.9%    |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 2         | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 2         | 0.9%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 2         | 0.9%    |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                               | 2         | 0.9%    |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 0.9%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                     | 1         | 0.45%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 45.18%  |
| 1 x AMD        | 31        | 18.67%  |
| Intel + Nvidia | 28        | 16.87%  |
| Intel + AMD    | 15        | 9.04%   |
| 1 x Nvidia     | 9         | 5.42%   |
| AMD + Nvidia   | 5         | 3.01%   |
| 2 x AMD        | 2         | 1.2%    |
| 1 x SiS        | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 139       | 83.23%  |
| Proprietary | 23        | 13.77%  |
| Unknown     | 5         | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 60.82%  |
| 1.01-2.0   | 25        | 14.62%  |
| 0.01-0.5   | 17        | 9.94%   |
| 0.51-1.0   | 12        | 7.02%   |
| 3.01-4.0   | 9         | 5.26%   |
| 5.01-6.0   | 2         | 1.17%   |
| 7.01-8.0   | 1         | 0.58%   |
| 2.01-3.0   | 1         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 47        | 24.48%  |
| LG Display              | 24        | 12.5%   |
| Samsung Electronics     | 19        | 9.9%    |
| Chimei Innolux          | 19        | 9.9%    |
| BOE                     | 19        | 9.9%    |
| Lenovo                  | 11        | 5.73%   |
| Dell                    | 10        | 5.21%   |
| Chi Mei Optoelectronics | 7         | 3.65%   |
| Goldstar                | 4         | 2.08%   |
| Sharp                   | 3         | 1.56%   |
| LG Philips              | 3         | 1.56%   |
| AOC                     | 3         | 1.56%   |
| TMX                     | 2         | 1.04%   |
| PANDA                   | 2         | 1.04%   |
| HannStar                | 2         | 1.04%   |
| CSO                     | 2         | 1.04%   |
| ViewSonic               | 1         | 0.52%   |
| Unknown (XXX)           | 1         | 0.52%   |
| Unknown                 | 1         | 0.52%   |
| Sony                    | 1         | 0.52%   |
| Philips                 | 1         | 0.52%   |
| NEC Computers           | 1         | 0.52%   |
| Medion                  | 1         | 0.52%   |
| LGD                     | 1         | 0.52%   |
| InfoVision              | 1         | 0.52%   |
| IBM                     | 1         | 0.52%   |
| Hewlett-Packard         | 1         | 0.52%   |
| Gericom                 | 1         | 0.52%   |
| CPT                     | 1         | 0.52%   |
| BenQ                    | 1         | 0.52%   |
| ASUSTek Computer        | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 3.57%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 2.04%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 3         | 1.53%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 1.53%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 1.02%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 1.02%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 1.02%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 2         | 1.02%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 1.02%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.02%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 1.02%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 1.02%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 1.02%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 1.02%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 1.02%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.51%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.51%   |
| Unknown (XXX) M22EI4 XXX076E 1680x1050 474x296mm 22.0-inch                | 1         | 0.51%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                   | 1         | 0.51%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.51%   |
| Sony TV SNYAA01 1360x768                                                  | 1         | 0.51%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 1         | 0.51%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                   | 1         | 0.51%   |
| Sharp LCD Monitor SHP1450 3840x2160 350x190mm 15.7-inch                   | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch      | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 440x300mm 21.0-inch      | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM02B5 1920x1200 518x324mm 24.1-inch      | 1         | 0.51%   |
| Samsung Electronics S27D390 SAM0B66 1920x1080 598x336mm 27.0-inch         | 1         | 0.51%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 530x300mm 24.0-inch         | 1         | 0.51%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch      | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch      | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 83        | 46.37%  |
| 1366x768 (WXGA)    | 37        | 20.67%  |
| 1600x900 (HD+)     | 17        | 9.5%    |
| 1280x800 (WXGA)    | 6         | 3.35%   |
| 3440x1440          | 5         | 2.79%   |
| 2560x1440 (QHD)    | 5         | 2.79%   |
| 1920x1200 (WUXGA)  | 5         | 2.79%   |
| 1680x1050 (WSXGA+) | 5         | 2.79%   |
| 1440x900 (WXGA+)   | 5         | 2.79%   |
| 3840x2160 (4K)     | 4         | 2.23%   |
| 2560x1600          | 1         | 0.56%   |
| 2520x1680          | 1         | 0.56%   |
| 2288x1287          | 1         | 0.56%   |
| 2256x1504          | 1         | 0.56%   |
| 2048x1152          | 1         | 0.56%   |
| 1400x1050          | 1         | 0.56%   |
| 1280x1024 (SXGA)   | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 85        | 43.81%  |
| 17      | 24        | 12.37%  |
| 13      | 18        | 9.28%   |
| 14      | 16        | 8.25%   |
| 24      | 9         | 4.64%   |
| 23      | 7         | 3.61%   |
| 34      | 5         | 2.58%   |
| 27      | 5         | 2.58%   |
| 21      | 4         | 2.06%   |
| 12      | 4         | 2.06%   |
| 22      | 3         | 1.55%   |
| 18      | 3         | 1.55%   |
| 54      | 2         | 1.03%   |
| 142     | 1         | 0.52%   |
| 65      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 39      | 1         | 0.52%   |
| 33      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |
| 16      | 1         | 0.52%   |
| 11      | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 108       | 56.54%  |
| 351-400        | 26        | 13.61%  |
| 501-600        | 19        | 9.95%   |
| 201-300        | 16        | 8.38%   |
| 401-500        | 9         | 4.71%   |
| 701-800        | 6         | 3.14%   |
| 1001-1500      | 3         | 1.57%   |
| 801-900        | 2         | 1.05%   |
| More than 2000 | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 81.4%   |
| 16/10   | 21        | 12.21%  |
| 21/9    | 5         | 2.91%   |
| 3/2     | 2         | 1.16%   |
| 5/4     | 1         | 0.58%   |
| 4/3     | 1         | 0.58%   |
| 1.00    | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 84        | 43.52%  |
| 81-90          | 24        | 12.44%  |
| 121-130        | 22        | 11.4%   |
| 201-250        | 18        | 9.33%   |
| 71-80          | 9         | 4.66%   |
| 351-500        | 6         | 3.11%   |
| 301-350        | 5         | 2.59%   |
| More than 1000 | 4         | 2.07%   |
| 61-70          | 4         | 2.07%   |
| 251-300        | 3         | 1.55%   |
| 151-200        | 3         | 1.55%   |
| 141-150        | 2         | 1.04%   |
| 131-140        | 2         | 1.04%   |
| 501-1000       | 2         | 1.04%   |
| 91-100         | 2         | 1.04%   |
| 51-60          | 1         | 0.52%   |
| 111-120        | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 41.05%  |
| 101-120       | 55        | 28.95%  |
| 51-100        | 38        | 20%     |
| 161-240       | 10        | 5.26%   |
| More than 240 | 4         | 2.11%   |
| 1-50          | 4         | 2.11%   |
| Unknown       | 1         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 137       | 79.19%  |
| 2     | 30        | 17.34%  |
| 3     | 3         | 1.73%   |
| 0     | 3         | 1.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 94        | 35.07%  |
| Realtek Semiconductor             | 86        | 32.09%  |
| Qualcomm Atheros                  | 36        | 13.43%  |
| Broadcom                          | 20        | 7.46%   |
| Ralink                            | 4         | 1.49%   |
| Huawei Technologies               | 3         | 1.12%   |
| Hewlett-Packard                   | 3         | 1.12%   |
| ASUSTek Computer                  | 3         | 1.12%   |
| Sierra Wireless                   | 2         | 0.75%   |
| Samsung Electronics               | 2         | 0.75%   |
| Ralink Technology                 | 2         | 0.75%   |
| MediaTek                          | 2         | 0.75%   |
| Marvell Technology Group          | 2         | 0.75%   |
| Ericsson Business Mobile Networks | 2         | 0.75%   |
| Broadcom Limited                  | 2         | 0.75%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.37%   |
| Lenovo                            | 1         | 0.37%   |
| JMicron Technology                | 1         | 0.37%   |
| Dell                              | 1         | 0.37%   |
| ASIX Electronics                  | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 16.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 4.46%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 2.68%   |
| Intel Wireless 7260                                               | 9         | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.79%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.19%   |
| Intel Wireless 7265                                               | 4         | 1.19%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.19%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.19%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.19%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.89%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.89%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 0.89%   |
| Huawei ELS-NX9                                                    | 3         | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 88        | 49.72%  |
| Qualcomm Atheros      | 31        | 17.51%  |
| Realtek Semiconductor | 23        | 12.99%  |
| Broadcom              | 17        | 9.6%    |
| Ralink                | 4         | 2.26%   |
| ASUSTek Computer      | 3         | 1.69%   |
| Sierra Wireless       | 2         | 1.13%   |
| Ralink Technology     | 2         | 1.13%   |
| MediaTek              | 2         | 1.13%   |
| Hewlett-Packard       | 2         | 1.13%   |
| Broadcom Limited      | 2         | 1.13%   |
| Dell                  | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 5.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 5.08%   |
| Intel Wireless 7260                                                     | 9         | 5.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.39%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.26%   |
| Intel Wireless 7265                                                     | 4         | 2.26%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.26%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.69%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.13%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.13%   |
| Intel Wireless 8260                                                     | 2         | 1.13%   |
| Intel Wireless 3165                                                     | 2         | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.13%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.13%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 1.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.13%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                     | 2         | 1.13%   |
| Sierra Wireless MC8305 Modem                                            | 1         | 0.56%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 79        | 50.64%  |
| Intel                            | 50        | 32.05%  |
| Qualcomm Atheros                 | 10        | 6.41%   |
| Broadcom                         | 6         | 3.85%   |
| Huawei Technologies              | 3         | 1.92%   |
| Samsung Electronics              | 2         | 1.28%   |
| Marvell Technology Group         | 2         | 1.28%   |
| Silicon Integrated Systems [SiS] | 1         | 0.64%   |
| Lenovo                           | 1         | 0.64%   |
| JMicron Technology               | 1         | 0.64%   |
| ASIX Electronics                 | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 36.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 9.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 6.41%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 3.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.56%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.56%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.92%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.92%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 1.92%   |
| Huawei ELS-NX9                                                    | 3         | 1.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.28%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 1.28%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.28%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.28%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.28%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.28%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.28%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 1.28%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 1.28%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.64%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.64%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.64%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.64%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.64%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 52.37%  |
| Ethernet | 148       | 46.69%  |
| Modem    | 3         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 127       | 72.57%  |
| Ethernet | 48        | 27.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 142       | 85.03%  |
| 1     | 25        | 14.97%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 98.2%   |
| Yes  | 3         | 1.8%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 43.48%  |
| IMC Networks                    | 14        | 10.14%  |
| Broadcom                        | 14        | 10.14%  |
| Qualcomm Atheros Communications | 13        | 9.42%   |
| Realtek Semiconductor           | 12        | 8.7%    |
| Hewlett-Packard                 | 5         | 3.62%   |
| Toshiba                         | 3         | 2.17%   |
| Ralink                          | 3         | 2.17%   |
| Lite-On Technology              | 3         | 2.17%   |
| Cambridge Silicon Radio         | 3         | 2.17%   |
| Foxconn International           | 2         | 1.45%   |
| ASUSTek Computer                | 2         | 1.45%   |
| Ralink Technology               | 1         | 0.72%   |
| Foxconn / Hon Hai               | 1         | 0.72%   |
| Chicony Electronics             | 1         | 0.72%   |
| Askey Computer                  | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 15.22%  |
| Intel Bluetooth Device                              | 14        | 10.14%  |
| Intel AX200 Bluetooth                               | 10        | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 6.52%   |
| IMC Networks Bluetooth Radio                        | 6         | 4.35%   |
| Realtek Bluetooth Radio                             | 5         | 3.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 2.9%    |
| Ralink RT3290 Bluetooth                             | 3         | 2.17%   |
| IMC Networks Bluetooth Device                       | 3         | 2.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.17%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 1.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.45%   |
| Lite-On Bluetooth Device                            | 2         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.45%   |
| Intel AX210 Bluetooth                               | 2         | 1.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.45%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.45%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.45%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.72%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.72%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.72%   |
| IMC Networks Wireless_Device                        | 1         | 0.72%   |
| IMC Networks Bluetooth module                       | 1         | 0.72%   |
| IMC Networks Bluetooth                              | 1         | 0.72%   |
| Foxconn / Hon Hai BT                                | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 136       | 68.34%  |
| AMD                              | 36        | 18.09%  |
| Nvidia                           | 20        | 10.05%  |
| Texas Instruments                | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] | 1         | 0.5%    |
| Logitech                         | 1         | 0.5%    |
| Lenovo                           | 1         | 0.5%    |
| JMTek                            | 1         | 0.5%    |
| Hewlett-Packard                  | 1         | 0.5%    |
| C-Media Electronics              | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 7.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 5.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 5.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.51%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 4.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 4.1%    |
| Intel 8 Series HD Audio Controller                                         | 10        | 4.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 2.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.05%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.64%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.23%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.82%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.82%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.82%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.82%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.41%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.41%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 29        | 26.13%  |
| Samsung Electronics | 28        | 25.23%  |
| Micron Technology   | 17        | 15.32%  |
| Crucial             | 8         | 7.21%   |
| Unknown             | 7         | 6.31%   |
| Kingston            | 7         | 6.31%   |
| Elpida              | 4         | 3.6%    |
| Ramaxel Technology  | 3         | 2.7%    |
| Nanya Technology    | 3         | 2.7%    |
| A-DATA Technology   | 2         | 1.8%    |
| Qimonda             | 1         | 0.9%    |
| Patriot             | 1         | 0.9%    |
| ChangXin Memory     | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 3         | 2.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 2.42%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 2         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 1.61%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 1.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.61%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 2         | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.61%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 2         | 1.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.61%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 1.61%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 1.61%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.81%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.81%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.81%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM DRAM                     | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.81%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 0.81%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 0.81%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.81%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 1         | 0.81%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 1         | 0.81%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s             | 1         | 0.81%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s             | 1         | 0.81%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.81%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s     | 1         | 0.81%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR2 667MT/s    | 1         | 0.81%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR2 667MT/s     | 1         | 0.81%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 41        | 44.57%  |
| DDR3   | 35        | 38.04%  |
| DDR2   | 7         | 7.61%   |
| SDRAM  | 3         | 3.26%   |
| LPDDR4 | 3         | 3.26%   |
| LPDDR3 | 2         | 2.17%   |
| DRAM   | 1         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 91.49%  |
| Row Of Chips | 7         | 7.45%   |
| Chip         | 1         | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 33        | 33.67%  |
| 4096  | 28        | 28.57%  |
| 16384 | 17        | 17.35%  |
| 2048  | 14        | 14.29%  |
| 1024  | 3         | 3.06%   |
| 32768 | 2         | 2.04%   |
| 512   | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 24.51%  |
| 2667    | 22        | 21.57%  |
| 3200    | 12        | 11.76%  |
| 1334    | 9         | 8.82%   |
| 2400    | 6         | 5.88%   |
| 1333    | 5         | 4.9%    |
| 2133    | 4         | 3.92%   |
| 667     | 4         | 3.92%   |
| Unknown | 3         | 2.94%   |
| 4267    | 2         | 1.96%   |
| 4199    | 2         | 1.96%   |
| 8400    | 1         | 0.98%   |
| 3733    | 1         | 0.98%   |
| 2048    | 1         | 0.98%   |
| 1867    | 1         | 0.98%   |
| 1067    | 1         | 0.98%   |
| 975     | 1         | 0.98%   |
| 800     | 1         | 0.98%   |
| 533     | 1         | 0.98%   |

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
| Chicony Electronics                    | 44        | 31.43%  |
| IMC Networks                           | 20        | 14.29%  |
| Realtek Semiconductor                  | 11        | 7.86%   |
| Quanta                                 | 10        | 7.14%   |
| Acer                                   | 9         | 6.43%   |
| Sunplus Innovation Technology          | 8         | 5.71%   |
| Microdia                               | 7         | 5%      |
| Lite-On Technology                     | 6         | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.29%   |
| Suyin                                  | 3         | 2.14%   |
| Lenovo                                 | 3         | 2.14%   |
| Syntek                                 | 2         | 1.43%   |
| Primax Electronics                     | 2         | 1.43%   |
| Generalplus Technology                 | 2         | 1.43%   |
| Unknown (3730304231393931415053)       | 1         | 0.71%   |
| Silicon Motion                         | 1         | 0.71%   |
| Samsung Electronics                    | 1         | 0.71%   |
| Ricoh                                  | 1         | 0.71%   |
| Luxvisions Innotech Limited            | 1         | 0.71%   |
| Logitech                               | 1         | 0.71%   |
| Apple                                  | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 6.34%   |
| IMC Networks Integrated Camera                              | 8         | 5.63%   |
| Microdia Integrated_Webcam_HD                               | 6         | 4.23%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2.82%   |
| Acer Integrated Camera                                      | 4         | 2.82%   |
| Sunplus HP HD Webcam [Fixed]                                | 3         | 2.11%   |
| Realtek USB Camera                                          | 3         | 2.11%   |
| Lite-On HP HD Webcam                                        | 3         | 2.11%   |
| Chicony HP HD Webcam                                        | 3         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 3         | 2.11%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.41%   |
| Sunplus HD WebCam                                           | 2         | 1.41%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.41%   |
| Realtek Asus laptop camera                                  | 2         | 1.41%   |
| Quanta HP Webcam                                            | 2         | 1.41%   |
| Quanta HP TrueVision HD Camera                              | 2         | 1.41%   |
| Quanta HP HD Camera                                         | 2         | 1.41%   |
| Primax HP HD Webcam [Fixed]                                 | 2         | 1.41%   |
| Lite-On HP HD Camera                                        | 2         | 1.41%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 1.41%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.41%   |
| IMC Networks Integrated Webcam                              | 2         | 1.41%   |
| Generalplus GENERAL WEBCAM                                  | 2         | 1.41%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.41%   |
| Chicony USB2.0 UVC WebCam                                   | 2         | 1.41%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.41%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.41%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.41%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.41%   |
| Chicony HP Webcam                                           | 2         | 1.41%   |
| Chicony HP TrueVision HD Camera                             | 2         | 1.41%   |
| Chicony HP HD Camera                                        | 2         | 1.41%   |
| Chicony FJ Camera                                           | 2         | 1.41%   |
| Acer Integrated IR Camera                                   | 2         | 1.41%   |
| Unknown (3730304231393931415053) USB Camera                 | 1         | 0.7%    |
| Suyin HP Webcam-50                                          | 1         | 0.7%    |
| Suyin HP Truevision HD                                      | 1         | 0.7%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.7%    |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 36.17%  |
| Validity Sensors           | 14        | 29.79%  |
| AuthenTec                  | 6         | 12.77%  |
| Upek                       | 4         | 8.51%   |
| Shenzhen Goodix Technology | 4         | 8.51%   |
| STMicroelectronics         | 1         | 2.13%   |
| Elan Microelectronics      | 1         | 2.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 12.77%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 10.64%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 8.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 8.51%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 6.38%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 6.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4.26%   |
| AuthenTec AES2810                                                          | 2         | 4.26%   |
| Unknown                                                                    | 2         | 4.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.13%   |
| Validity Sensors VFS491                                                    | 1         | 2.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 2.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.13%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.13%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.13%   |
| Elan ELAN:ARM-M4                                                           | 1         | 2.13%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.13%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 2.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.13%   |
| AuthenTec AES1600                                                          | 1         | 2.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 50%     |
| Broadcom    | 4         | 28.57%  |
| O2 Micro    | 2         | 14.29%  |
| Upek        | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 14.29%  |
| Broadcom 58200                                                               | 2         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 89        | 52.98%  |
| 1     | 53        | 31.55%  |
| 2     | 24        | 14.29%  |
| 3     | 2         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 44.76%  |
| Graphics card            | 18        | 17.14%  |
| Chipcard                 | 14        | 13.33%  |
| Net/wireless             | 10        | 9.52%   |
| Bluetooth                | 5         | 4.76%   |
| Multimedia controller    | 4         | 3.81%   |
| Communication controller | 3         | 2.86%   |
| Storage                  | 2         | 1.9%    |
| Net/ethernet             | 1         | 0.95%   |
| Camera                   | 1         | 0.95%   |

