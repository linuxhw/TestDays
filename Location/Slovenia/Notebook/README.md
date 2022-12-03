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

Total: 251

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 25        | 14.71%  |
| Ubuntu 18.04                 | 14        | 8.24%   |
| Debian 11                    | 7         | 4.12%   |
| Ubuntu 22.04                 | 6         | 3.53%   |
| KDE neon 20.04               | 5         | 2.94%   |
| Zorin 16                     | 4         | 2.35%   |
| Fedora 34                    | 4         | 2.35%   |
| ArcoLinux Rolling            | 4         | 2.35%   |
| Arch                         | 4         | 2.35%   |
| Zorin 15                     | 3         | 1.76%   |
| Xubuntu 20.04                | 3         | 1.76%   |
| OpenMandriva 4.3             | 3         | 1.76%   |
| Linux Mint 19.1              | 3         | 1.76%   |
| Kubuntu 22.04                | 3         | 1.76%   |
| Kubuntu 21.10                | 3         | 1.76%   |
| Kubuntu 20.04                | 3         | 1.76%   |
| Fedora 33                    | 3         | 1.76%   |
| Debian Testing               | 3         | 1.76%   |
| Ubuntu Unity 16.04           | 2         | 1.18%   |
| Ubuntu 21.10                 | 2         | 1.18%   |
| Ubuntu 21.04                 | 2         | 1.18%   |
| Ubuntu 20.10                 | 2         | 1.18%   |
| Ubuntu 19.10                 | 2         | 1.18%   |
| Pop!_OS 21.04                | 2         | 1.18%   |
| Manjaro 20.2                 | 2         | 1.18%   |
| Manjaro                      | 2         | 1.18%   |
| Linux Mint 21                | 2         | 1.18%   |
| Kubuntu 18.04                | 2         | 1.18%   |
| Gentoo 2.6                   | 2         | 1.18%   |
| Endless 3.5.8                | 2         | 1.18%   |
| EndeavourOS                  | 2         | 1.18%   |
| Ubuntu Budgie 22.04          | 1         | 0.59%   |
| Ubuntu Budgie 20.04          | 1         | 0.59%   |
| Ubuntu 19.04                 | 1         | 0.59%   |
| ROSA R9                      | 1         | 0.59%   |
| ROSA R8                      | 1         | 0.59%   |
| Q4OS 4                       | 1         | 0.59%   |
| Pop!_OS 22.04                | 1         | 0.59%   |
| Pop!_OS 21.10                | 1         | 0.59%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 51        | 31.68%  |
| Kubuntu       | 12        | 7.45%   |
| Debian        | 12        | 7.45%   |
| Fedora        | 10        | 6.21%   |
| Linux Mint    | 8         | 4.97%   |
| Endless       | 8         | 4.97%   |
| Zorin         | 7         | 4.35%   |
| Manjaro       | 7         | 4.35%   |
| KDE neon      | 6         | 3.73%   |
| Pop!_OS       | 4         | 2.48%   |
| OpenMandriva  | 4         | 2.48%   |
| ArcoLinux     | 4         | 2.48%   |
| Arch          | 4         | 2.48%   |
| Xubuntu       | 3         | 1.86%   |
| Ubuntu Unity  | 2         | 1.24%   |
| Ubuntu Budgie | 2         | 1.24%   |
| Lubuntu       | 2         | 1.24%   |
| Gentoo        | 2         | 1.24%   |
| EndeavourOS   | 2         | 1.24%   |
| Elementary    | 2         | 1.24%   |
| ROSA          | 1         | 0.62%   |
| Q4OS          | 1         | 0.62%   |
| openSUSE      | 1         | 0.62%   |
| LMDE          | 1         | 0.62%   |
| Kali          | 1         | 0.62%   |
| Garuda Linux  | 1         | 0.62%   |
| Clear Linux   | 1         | 0.62%   |
| Chrome OS     | 1         | 0.62%   |
| BlackPanther  | 1         | 0.62%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 4         | 2.16%   |
| 4.18.0-15-generic       | 4         | 2.16%   |
| 5.8.0-41-generic        | 3         | 1.62%   |
| 5.3.0-40-generic        | 3         | 1.62%   |
| 5.16.7-desktop-1omv4003 | 3         | 1.62%   |
| 5.15.0-43-generic       | 3         | 1.62%   |
| 5.13.0-41-generic       | 3         | 1.62%   |
| 5.13.0-30-generic       | 3         | 1.62%   |
| 5.13.0-28-generic       | 3         | 1.62%   |
| 5.13.0-21-generic       | 3         | 1.62%   |
| 5.8.0-44-generic        | 2         | 1.08%   |
| 5.8.0-14-generic        | 2         | 1.08%   |
| 5.6.0-1-amd64           | 2         | 1.08%   |
| 5.4.0-70-generic        | 2         | 1.08%   |
| 5.4.0-56-generic        | 2         | 1.08%   |
| 5.4.0-54-generic        | 2         | 1.08%   |
| 5.4.0-48-generic        | 2         | 1.08%   |
| 5.4.0-40-generic        | 2         | 1.08%   |
| 5.4.0-33-generic        | 2         | 1.08%   |
| 5.4.0-28-generic        | 2         | 1.08%   |
| 5.4.0-26-generic        | 2         | 1.08%   |
| 5.15.0-47-generic       | 2         | 1.08%   |
| 5.15.0-46-generic       | 2         | 1.08%   |
| 5.13.19-2-MANJARO       | 2         | 1.08%   |
| 5.13.0-7614-generic     | 2         | 1.08%   |
| 5.11.0-43-generic       | 2         | 1.08%   |
| 5.11.0-40-generic       | 2         | 1.08%   |
| 5.11.0-35-generic       | 2         | 1.08%   |
| 5.10.0-8-amd64          | 2         | 1.08%   |
| 4.15.0-128-generic      | 2         | 1.08%   |
| 6.0.7-1-default         | 1         | 0.54%   |
| 5.9.8-2-MANJARO         | 1         | 0.54%   |
| 5.9.2-arch1-1           | 1         | 0.54%   |
| 5.9.15-200.fc33.x86_64  | 1         | 0.54%   |
| 5.9.14-arch1-1          | 1         | 0.54%   |
| 5.8.8-arch1-1           | 1         | 0.54%   |
| 5.8.5-arch1-1           | 1         | 0.54%   |
| 5.8.18-300.fc33.x86_64  | 1         | 0.54%   |
| 5.8.10-200.fc32.x86_64  | 1         | 0.54%   |
| 5.8.0-48-generic        | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 17.05%  |
| 5.13.0  | 17        | 9.66%   |
| 5.15.0  | 12        | 6.82%   |
| 5.11.0  | 12        | 6.82%   |
| 4.15.0  | 10        | 5.68%   |
| 5.8.0   | 9         | 5.11%   |
| 5.3.0   | 8         | 4.55%   |
| 5.10.0  | 8         | 4.55%   |
| 4.18.0  | 8         | 4.55%   |
| 5.0.0   | 4         | 2.27%   |
| 5.6.0   | 3         | 1.7%    |
| 5.16.7  | 3         | 1.7%    |
| 5.13.19 | 2         | 1.14%   |
| 5.10.14 | 2         | 1.14%   |
| 6.0.7   | 1         | 0.57%   |
| 5.9.8   | 1         | 0.57%   |
| 5.9.2   | 1         | 0.57%   |
| 5.9.15  | 1         | 0.57%   |
| 5.9.14  | 1         | 0.57%   |
| 5.8.8   | 1         | 0.57%   |
| 5.8.5   | 1         | 0.57%   |
| 5.8.18  | 1         | 0.57%   |
| 5.8.10  | 1         | 0.57%   |
| 5.7.13  | 1         | 0.57%   |
| 5.6.14  | 1         | 0.57%   |
| 5.5.15  | 1         | 0.57%   |
| 5.5.0   | 1         | 0.57%   |
| 5.4.80  | 1         | 0.57%   |
| 5.4.53  | 1         | 0.57%   |
| 5.4.27  | 1         | 0.57%   |
| 5.3.6   | 1         | 0.57%   |
| 5.19.7  | 1         | 0.57%   |
| 5.19.0  | 1         | 0.57%   |
| 5.18.0  | 1         | 0.57%   |
| 5.17.5  | 1         | 0.57%   |
| 5.17.4  | 1         | 0.57%   |
| 5.17.1  | 1         | 0.57%   |
| 5.17.0  | 1         | 0.57%   |
| 5.16.4  | 1         | 0.57%   |
| 5.16.19 | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 32        | 18.39%  |
| 5.13    | 20        | 11.49%  |
| 5.15    | 16        | 9.2%    |
| 5.11    | 14        | 8.05%   |
| 5.8     | 13        | 7.47%   |
| 5.10    | 10        | 5.75%   |
| 4.15    | 10        | 5.75%   |
| 5.3     | 9         | 5.17%   |
| 4.18    | 9         | 5.17%   |
| 5.16    | 7         | 4.02%   |
| 5.9     | 4         | 2.3%    |
| 5.6     | 4         | 2.3%    |
| 5.17    | 4         | 2.3%    |
| 5.0     | 4         | 2.3%    |
| 5.14    | 3         | 1.72%   |
| 5.12    | 3         | 1.72%   |
| 5.5     | 2         | 1.15%   |
| 5.19    | 2         | 1.15%   |
| 4.19    | 2         | 1.15%   |
| 6.0     | 1         | 0.57%   |
| 5.7     | 1         | 0.57%   |
| 5.18    | 1         | 0.57%   |
| 4.9     | 1         | 0.57%   |
| 4.14    | 1         | 0.57%   |
| 4.1     | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 150       | 97.4%   |
| i686   | 4         | 2.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 64        | 39.75%  |
| KDE5       | 31        | 19.25%  |
| Unknown    | 26        | 16.15%  |
| XFCE       | 14        | 8.7%    |
| X-Cinnamon | 4         | 2.48%   |
| LXQt       | 3         | 1.86%   |
| KDE        | 3         | 1.86%   |
| Unity      | 2         | 1.24%   |
| Pantheon   | 2         | 1.24%   |
| MATE       | 2         | 1.24%   |
| LXDE       | 2         | 1.24%   |
| Cinnamon   | 2         | 1.24%   |
| Budgie     | 2         | 1.24%   |
| Trinity    | 1         | 0.62%   |
| Openbox    | 1         | 0.62%   |
| i3         | 1         | 0.62%   |
| DWM        | 1         | 0.62%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 119       | 73.91%  |
| Wayland | 21        | 13.04%  |
| Unknown | 18        | 11.18%  |
| Tty     | 3         | 1.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 50%     |
| SDDM    | 28        | 17.28%  |
| GDM     | 18        | 11.11%  |
| LightDM | 13        | 8.02%   |
| GDM3    | 13        | 8.02%   |
| TDM     | 9         | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 78        | 49.68%  |
| sl_SI   | 36        | 22.93%  |
| Unknown | 26        | 16.56%  |
| en_GB   | 6         | 3.82%   |
| en_SI   | 4         | 2.55%   |
| it_IT   | 2         | 1.27%   |
| C       | 2         | 1.27%   |
| pt_PT   | 1         | 0.64%   |
| nl_NL   | 1         | 0.64%   |
| hr_HR   | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 81        | 51.59%  |
| BIOS | 76        | 48.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 81.76%  |
| Overlay | 10        | 6.29%   |
| Btrfs   | 9         | 5.66%   |
| Unknown | 8         | 5.03%   |
| Zfs     | 1         | 0.63%   |
| Ext2    | 1         | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 93        | 58.13%  |
| GPT     | 46        | 28.75%  |
| MBR     | 21        | 13.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 146       | 92.99%  |
| Yes       | 11        | 7.01%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 71.34%  |
| Yes       | 45        | 28.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 50        | 32.47%  |
| Lenovo              | 44        | 28.57%  |
| ASUSTek Computer    | 22        | 14.29%  |
| Dell                | 14        | 9.09%   |
| Toshiba             | 7         | 4.55%   |
| Acer                | 5         | 3.25%   |
| MSI                 | 2         | 1.3%    |
| Razer               | 1         | 0.65%   |
| PC Specialist       | 1         | 0.65%   |
| Panasonic           | 1         | 0.65%   |
| Medion              | 1         | 0.65%   |
| HUAWEI              | 1         | 0.65%   |
| Gigabyte Technology | 1         | 0.65%   |
| Fujitsu Siemens     | 1         | 0.65%   |
| Fujitsu             | 1         | 0.65%   |
| Framework           | 1         | 0.65%   |
| eMachines           | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                      | 3         | 1.95%   |
| Toshiba Satellite L750                     | 2         | 1.3%    |
| Lenovo ThinkPad T410 2522A92               | 2         | 1.3%    |
| HP EliteBook 8760w                         | 2         | 1.3%    |
| Dell Inspiron 5570                         | 2         | 1.3%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 1.3%    |
| Unknown                                    | 2         | 1.3%    |
| Toshiba TECRA S10                          | 1         | 0.65%   |
| Toshiba TECRA A11                          | 1         | 0.65%   |
| Toshiba Satellite Pro U400                 | 1         | 0.65%   |
| Toshiba Satellite A100                     | 1         | 0.65%   |
| Toshiba QOSMIO X500                        | 1         | 0.65%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.65%   |
| PC Specialist Fusion IV                    | 1         | 0.65%   |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.65%   |
| MSI U210                                   | 1         | 0.65%   |
| MSI GP60 2OD                               | 1         | 0.65%   |
| Medion E7218                               | 1         | 0.65%   |
| Lenovo Yoga S740-14IIL 81RS                | 1         | 0.65%   |
| Lenovo Yoga 2 13 20344                     | 1         | 0.65%   |
| Lenovo ThinkPad X250 20CM004ESC            | 1         | 0.65%   |
| Lenovo ThinkPad X230 23202DG               | 1         | 0.65%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.65%   |
| Lenovo ThinkPad W530 24479K4               | 1         | 0.65%   |
| Lenovo ThinkPad T61 8897CTO                | 1         | 0.65%   |
| Lenovo ThinkPad T590 20N5S0YN00            | 1         | 0.65%   |
| Lenovo ThinkPad T590 20N5S0MR00            | 1         | 0.65%   |
| Lenovo ThinkPad T500 2055WYX               | 1         | 0.65%   |
| Lenovo ThinkPad T490s 20NYS4HL07           | 1         | 0.65%   |
| Lenovo ThinkPad T480 20L6S58700            | 1         | 0.65%   |
| Lenovo ThinkPad T480 20L6S01W00            | 1         | 0.65%   |
| Lenovo ThinkPad T460s 20FAS7XT01           | 1         | 0.65%   |
| Lenovo ThinkPad T420 4236A78               | 1         | 0.65%   |
| Lenovo ThinkPad T420 423662G               | 1         | 0.65%   |
| Lenovo ThinkPad T15 Gen 1 20S6000NSC       | 1         | 0.65%   |
| Lenovo ThinkPad SL500 27464DG              | 1         | 0.65%   |
| Lenovo ThinkPad S3 Yoga 14 20DM008FSC      | 1         | 0.65%   |
| Lenovo ThinkPad R61 8933W4F                | 1         | 0.65%   |
| Lenovo ThinkPad P53 20QN000DGE             | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 31        | 20.13%  |
| HP ProBook             | 10        | 6.49%   |
| HP EliteBook           | 10        | 6.49%   |
| Dell Inspiron          | 6         | 3.9%    |
| Lenovo IdeaPad         | 5         | 3.25%   |
| HP ZBook               | 5         | 3.25%   |
| Toshiba Satellite      | 4         | 2.6%    |
| HP Pavilion            | 4         | 2.6%    |
| HP 255                 | 4         | 2.6%    |
| HP 250                 | 4         | 2.6%    |
| Dell Latitude          | 4         | 2.6%    |
| ASUS VivoBook          | 4         | 2.6%    |
| HP Compaq              | 3         | 1.95%   |
| ASUS ASUS              | 3         | 1.95%   |
| Acer Aspire            | 3         | 1.95%   |
| Toshiba TECRA          | 2         | 1.3%    |
| Lenovo Yoga            | 2         | 1.3%    |
| HP Laptop              | 2         | 1.3%    |
| Dell XPS               | 2         | 1.3%    |
| Unknown                | 2         | 1.3%    |
| Toshiba QOSMIO         | 1         | 0.65%   |
| Razer Blade            | 1         | 0.65%   |
| PC Specialist Fusion   | 1         | 0.65%   |
| Panasonic CF-53SWWZ5MG | 1         | 0.65%   |
| MSI U210               | 1         | 0.65%   |
| MSI GP60               | 1         | 0.65%   |
| Medion E7218           | 1         | 0.65%   |
| Lenovo Legion          | 1         | 0.65%   |
| Lenovo G585            | 1         | 0.65%   |
| Lenovo G510            | 1         | 0.65%   |
| Lenovo G500            | 1         | 0.65%   |
| Lenovo B50-80          | 1         | 0.65%   |
| Lenovo B50-30          | 1         | 0.65%   |
| HUAWEI HKD-WXX         | 1         | 0.65%   |
| HP OMEN                | 1         | 0.65%   |
| HP kip                 | 1         | 0.65%   |
| HP ENVY                | 1         | 0.65%   |
| HP 470                 | 1         | 0.65%   |
| HP 2000                | 1         | 0.65%   |
| HP 15                  | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 22        | 14.29%  |
| 2011 | 14        | 9.09%   |
| 2020 | 13        | 8.44%   |
| 2018 | 12        | 7.79%   |
| 2017 | 11        | 7.14%   |
| 2013 | 11        | 7.14%   |
| 2014 | 10        | 6.49%   |
| 2012 | 9         | 5.84%   |
| 2010 | 9         | 5.84%   |
| 2008 | 9         | 5.84%   |
| 2021 | 8         | 5.19%   |
| 2009 | 8         | 5.19%   |
| 2015 | 7         | 4.55%   |
| 2007 | 4         | 2.6%    |
| 2016 | 3         | 1.95%   |
| 2006 | 3         | 1.95%   |
| 2022 | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 154       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 141       | 90.38%  |
| Enabled  | 15        | 9.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 153       | 99.35%  |
| Yes  | 1         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 43        | 27.74%  |
| 8.01-16.0   | 33        | 21.29%  |
| 4.01-8.0    | 30        | 19.35%  |
| 16.01-24.0  | 27        | 17.42%  |
| 32.01-64.0  | 12        | 7.74%   |
| 1.01-2.0    | 5         | 3.23%   |
| 24.01-32.0  | 2         | 1.29%   |
| 2.01-3.0    | 2         | 1.29%   |
| 64.01-256.0 | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 58        | 33.33%  |
| 2.01-3.0   | 47        | 27.01%  |
| 3.01-4.0   | 22        | 12.64%  |
| 4.01-8.0   | 19        | 10.92%  |
| 0.51-1.0   | 16        | 9.2%    |
| 8.01-16.0  | 8         | 4.6%    |
| 0.01-0.5   | 3         | 1.72%   |
| 16.01-24.0 | 1         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 75.16%  |
| 2      | 30        | 19.11%  |
| 0      | 5         | 3.18%   |
| 3      | 4         | 2.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 53.25%  |
| Yes       | 72        | 46.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 87.74%  |
| No        | 19        | 12.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 99.35%  |
| No        | 1         | 0.65%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 81.41%  |
| No        | 29        | 18.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovenia | 154       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 58        | 34.12%  |
| Kranj                   | 7         | 4.12%   |
| Celje                   | 5         | 2.94%   |
| Vrhnika                 | 4         | 2.35%   |
| Poljane nad Skofjo Loko | 4         | 2.35%   |
| Maribor                 | 4         | 2.35%   |
| Trzin                   | 3         | 1.76%   |
| Slovenske Konjice       | 3         | 1.76%   |
| Portorož               | 3         | 1.76%   |
| Murska Sobota           | 3         | 1.76%   |
| Koper                   | 3         | 1.76%   |
| Ajdovščina            | 3         | 1.76%   |
| Smarje pri Jelsah       | 2         | 1.18%   |
| Slovenj Gradec          | 2         | 1.18%   |
| Puconci                 | 2         | 1.18%   |
| Petrovce                | 2         | 1.18%   |
| Grosuplje               | 2         | 1.18%   |
| Žužemberk             | 1         | 0.59%   |
| Ziri                    | 1         | 0.59%   |
| Zgornji Leskovec        | 1         | 0.59%   |
| Zgornja Besnica         | 1         | 0.59%   |
| Žalec                  | 1         | 0.59%   |
| Zagorje ob Savi         | 1         | 0.59%   |
| Visoko                  | 1         | 0.59%   |
| Vipava                  | 1         | 0.59%   |
| Velenje                 | 1         | 0.59%   |
| Trzic                   | 1         | 0.59%   |
| Trbovlje                | 1         | 0.59%   |
| Tabor                   | 1         | 0.59%   |
| Solkan                  | 1         | 0.59%   |
| Smartno ob Paki         | 1         | 0.59%   |
| Skofljica               | 1         | 0.59%   |
| Škofja Loka            | 1         | 0.59%   |
| Skocjan                 | 1         | 0.59%   |
| Sežana                 | 1         | 0.59%   |
| Šentjernej             | 1         | 0.59%   |
| Sempeter pri Gorici     | 1         | 0.59%   |
| Ruše                   | 1         | 0.59%   |
| Rogasovci               | 1         | 0.59%   |
| Rogaška Slatina        | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 24        | 36     | 13.41%  |
| Seagate                 | 20        | 23     | 11.17%  |
| WDC                     | 16        | 16     | 8.94%   |
| Toshiba                 | 15        | 23     | 8.38%   |
| Crucial                 | 14        | 20     | 7.82%   |
| SK hynix                | 12        | 15     | 6.7%    |
| SanDisk                 | 12        | 14     | 6.7%    |
| Kingston                | 12        | 18     | 6.7%    |
| HGST                    | 9         | 10     | 5.03%   |
| Hitachi                 | 8         | 11     | 4.47%   |
| Unknown                 | 5         | 6      | 2.79%   |
| Intel                   | 4         | 4      | 2.23%   |
| Fujitsu                 | 3         | 4      | 1.68%   |
| Transcend               | 2         | 2      | 1.12%   |
| PNY                     | 2         | 2      | 1.12%   |
| Micron Technology       | 2         | 2      | 1.12%   |
| LITEON                  | 2         | 2      | 1.12%   |
| Lenovo                  | 2         | 2      | 1.12%   |
| KIOXIA                  | 2         | 2      | 1.12%   |
| Intenso                 | 2         | 2      | 1.12%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.56%   |
| Team                    | 1         | 1      | 0.56%   |
| Silicon Motion          | 1         | 1      | 0.56%   |
| SABRENT                 | 1         | 1      | 0.56%   |
| Patriot                 | 1         | 2      | 0.56%   |
| OCZ                     | 1         | 1      | 0.56%   |
| LITEONIT                | 1         | 2      | 0.56%   |
| JMicron Technology      | 1         | 1      | 0.56%   |
| HGST HTS                | 1         | 1      | 0.56%   |
| Gigabyte Technology     | 1         | 2      | 0.56%   |
| Corsair                 | 1         | 2      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB           | 5         | 2.7%    |
| HGST HTS721010A9E630 1TB               | 5         | 2.7%    |
| Hitachi HTS547575A9E384 752GB          | 3         | 1.62%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 1.62%   |
| Toshiba MQ04ABF100 1TB                 | 2         | 1.08%   |
| Toshiba MQ01ABF050 500GB               | 2         | 1.08%   |
| SK hynix SC311 SATA 256GB SSD          | 2         | 1.08%   |
| Seagate ST9750420AS 752GB              | 2         | 1.08%   |
| Seagate ST9500325AS 500GB              | 2         | 1.08%   |
| Seagate ST9320423AS 320GB              | 2         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 1.08%   |
| SanDisk NVMe SSD Drive 512GB           | 2         | 1.08%   |
| Samsung SSD 860 EVO 250GB              | 2         | 1.08%   |
| Samsung SSD 850 EVO 250GB              | 2         | 1.08%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 1.08%   |
| Samsung NVMe SSD Drive 1024GB          | 2         | 1.08%   |
| PNY CS900 120GB SSD                    | 2         | 1.08%   |
| Lenovo NVMe SSD Drive 256GB            | 2         | 1.08%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 1.08%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 1.08%   |
| Hitachi HTS725032A9A364 320GB          | 2         | 1.08%   |
| HGST HTS545050A7E680 500GB             | 2         | 1.08%   |
| Crucial CT2000MX500SSD1 2TB            | 2         | 1.08%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 1         | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 1         | 0.54%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD       | 1         | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.54%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.54%   |
| WDC WDS100T2B0B-00YS70 1TB SSD         | 1         | 0.54%   |
| WDC WD7500BPVX-60JC3T0 752GB           | 1         | 0.54%   |
| WDC WD3200BEKT-22KA9T0 320GB           | 1         | 0.54%   |
| WDC WD2500BEVT-60ZCT1 250GB            | 1         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB               | 1         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.54%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.54%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 1         | 0.54%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB   | 1         | 0.54%   |
| WDC PC SN520 NVMe 512GB                | 1         | 0.54%   |
| Unknown SD128  128GB                   | 1         | 0.54%   |

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
| Crucial             | 13        | 19     | 19.4%   |
| Samsung Electronics | 11        | 14     | 16.42%  |
| Kingston            | 10        | 15     | 14.93%  |
| SanDisk             | 7         | 9      | 10.45%  |
| WDC                 | 5         | 5      | 7.46%   |
| SK hynix            | 4         | 4      | 5.97%   |
| Transcend           | 2         | 2      | 2.99%   |
| PNY                 | 2         | 2      | 2.99%   |
| LITEON              | 2         | 2      | 2.99%   |
| Intenso             | 2         | 2      | 2.99%   |
| Toshiba             | 1         | 1      | 1.49%   |
| Team                | 1         | 1      | 1.49%   |
| Patriot             | 1         | 2      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 2      | 1.49%   |
| Intel               | 1         | 1      | 1.49%   |
| Gigabyte Technology | 1         | 2      | 1.49%   |
| Corsair             | 1         | 2      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 63        | 87     | 36.84%  |
| HDD     | 55        | 71     | 32.16%  |
| NVMe    | 48        | 65     | 28.07%  |
| MMC     | 4         | 5      | 2.34%   |
| Unknown | 1         | 1      | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 105       | 151    | 64.42%  |
| NVMe | 48        | 65     | 29.45%  |
| SAS  | 6         | 8      | 3.68%   |
| MMC  | 4         | 5      | 2.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 110    | 67.8%   |
| 0.51-1.0   | 33        | 41     | 27.97%  |
| 1.01-2.0   | 5         | 7      | 4.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 48        | 29.09%  |
| 101-250        | 45        | 27.27%  |
| 501-1000       | 24        | 14.55%  |
| 1001-2000      | 11        | 6.67%   |
| 1-20           | 11        | 6.67%   |
| 21-50          | 9         | 5.45%   |
| 51-100         | 8         | 4.85%   |
| 2001-3000      | 5         | 3.03%   |
| Unknown        | 3         | 1.82%   |
| More than 3000 | 1         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 72        | 43.11%  |
| 21-50     | 27        | 16.17%  |
| 101-250   | 22        | 13.17%  |
| 51-100    | 20        | 11.98%  |
| 251-500   | 15        | 8.98%   |
| 501-1000  | 6         | 3.59%   |
| Unknown   | 3         | 1.8%    |
| 1001-2000 | 2         | 1.2%    |

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
| Detected | 93        | 141    | 58.86%  |
| Works    | 51        | 68     | 32.28%  |
| Malfunc  | 13        | 18     | 8.23%   |
| Failed   | 1         | 2      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 109       | 60.56%  |
| AMD                              | 19        | 10.56%  |
| Samsung Electronics              | 16        | 8.89%   |
| SanDisk                          | 10        | 5.56%   |
| SK hynix                         | 8         | 4.44%   |
| Toshiba America Info Systems     | 6         | 3.33%   |
| Lenovo                           | 2         | 1.11%   |
| KIOXIA                           | 2         | 1.11%   |
| Kingston Technology Company      | 2         | 1.11%   |
| Union Memory (Shenzhen)          | 1         | 0.56%   |
| Silicon Motion                   | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Micron/Crucial Technology        | 1         | 0.56%   |
| Micron Technology                | 1         | 0.56%   |
| Marvell Technology Group         | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 7.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 6.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 5.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 5.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 4.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 3.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 3.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 3.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 3.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 2.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 2.62%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 2.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.09%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.05%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 1.05%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.05%   |
| SK hynix BC511                                                                 | 2         | 1.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.05%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 1.05%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.05%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.05%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.05%   |
| Intel SSD 660P Series                                                          | 2         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2         | 1.05%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.05%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.05%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 2         | 1.05%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 110       | 59.46%  |
| NVMe | 51        | 27.57%  |
| IDE  | 15        | 8.11%   |
| RAID | 9         | 4.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 128       | 83.12%  |
| AMD    | 26        | 16.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 3.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 3.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.25%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 3.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.95%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.95%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.95%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.3%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.3%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.3%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.3%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.3%    |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 1.3%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.3%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.3%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.3%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.3%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.3%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.3%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.3%    |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 1.3%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.3%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.3%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.3%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.3%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.3%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.3%    |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.3%    |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 1.3%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.65%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.65%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.65%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.65%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.65%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.65%   |
| Intel Genuine CPU T2250 @ 1.73GHz             | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 46        | 29.87%  |
| Intel Core i5           | 35        | 22.73%  |
| Intel Core 2 Duo        | 14        | 9.09%   |
| Intel Core i3           | 11        | 7.14%   |
| Intel Celeron           | 9         | 5.84%   |
| Other                   | 5         | 3.25%   |
| AMD Ryzen 7             | 5         | 3.25%   |
| AMD Ryzen 5             | 5         | 3.25%   |
| Intel Pentium           | 4         | 2.6%    |
| AMD Ryzen 3             | 4         | 2.6%    |
| AMD Ryzen 9             | 3         | 1.95%   |
| Intel Pentium Silver    | 1         | 0.65%   |
| Intel Pentium Dual      | 1         | 0.65%   |
| Intel Genuine           | 1         | 0.65%   |
| Intel Core 2            | 1         | 0.65%   |
| AMD Turion II Dual-Core | 1         | 0.65%   |
| AMD Turion II           | 1         | 0.65%   |
| AMD E1                  | 1         | 0.65%   |
| AMD E                   | 1         | 0.65%   |
| AMD C-60                | 1         | 0.65%   |
| AMD Athlon Neo          | 1         | 0.65%   |
| AMD Athlon 64 X2        | 1         | 0.65%   |
| AMD A8                  | 1         | 0.65%   |
| AMD A6                  | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 79        | 51.3%   |
| 4      | 58        | 37.66%  |
| 6      | 8         | 5.19%   |
| 8      | 7         | 4.55%   |
| 1      | 2         | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 154       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 74.68%  |
| 1      | 39        | 25.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 148       | 95.48%  |
| Unknown        | 6         | 3.87%   |
| 32-bit         | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 17.09%  |
| 0x206a7    | 11        | 6.96%   |
| 0x806ec    | 10        | 6.33%   |
| 0x306a9    | 10        | 6.33%   |
| 0x40651    | 8         | 5.06%   |
| 0x306c3    | 7         | 4.43%   |
| 0x6fd      | 6         | 3.8%    |
| 0x20655    | 6         | 3.8%    |
| 0x806ea    | 5         | 3.16%   |
| 0x806c1    | 5         | 3.16%   |
| 0x30678    | 5         | 3.16%   |
| 0x08108102 | 5         | 3.16%   |
| 0x906ea    | 4         | 2.53%   |
| 0x10676    | 4         | 2.53%   |
| 0x906e9    | 3         | 1.9%    |
| 0x406e3    | 3         | 1.9%    |
| 0x306d4    | 3         | 1.9%    |
| 0x106e5    | 3         | 1.9%    |
| 0x1067a    | 3         | 1.9%    |
| 0x906ed    | 2         | 1.27%   |
| 0x706e5    | 2         | 1.27%   |
| 0x706a1    | 2         | 1.27%   |
| 0x506c9    | 2         | 1.27%   |
| 0x20652    | 2         | 1.27%   |
| 0x08600106 | 2         | 1.27%   |
| 0x0810100b | 2         | 1.27%   |
| 0x06001119 | 2         | 1.27%   |
| 0x05000119 | 2         | 1.27%   |
| 0xa0660    | 1         | 0.63%   |
| 0xa0652    | 1         | 0.63%   |
| 0x806eb    | 1         | 0.63%   |
| 0x6fb      | 1         | 0.63%   |
| 0x6e8      | 1         | 0.63%   |
| 0x406c4    | 1         | 0.63%   |
| 0x0a50000c | 1         | 0.63%   |
| 0x08608103 | 1         | 0.63%   |
| 0x08608102 | 1         | 0.63%   |
| 0x08600104 | 1         | 0.63%   |
| 0x0700010f | 1         | 0.63%   |
| 0x010000c8 | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 31        | 20.13%  |
| Haswell       | 16        | 10.39%  |
| SandyBridge   | 12        | 7.79%   |
| IvyBridge     | 12        | 7.79%   |
| Westmere      | 8         | 5.19%   |
| Penryn        | 8         | 5.19%   |
| Core          | 8         | 5.19%   |
| Silvermont    | 6         | 3.9%    |
| Zen+          | 5         | 3.25%   |
| TigerLake     | 5         | 3.25%   |
| Broadwell     | 5         | 3.25%   |
| Zen 2         | 4         | 2.6%    |
| Unknown       | 4         | 2.6%    |
| Skylake       | 3         | 1.95%   |
| Nehalem       | 3         | 1.95%   |
| IceLake       | 3         | 1.95%   |
| Goldmont plus | 3         | 1.95%   |
| Zen 3         | 2         | 1.3%    |
| Zen           | 2         | 1.3%    |
| Piledriver    | 2         | 1.3%    |
| K8 Hammer     | 2         | 1.3%    |
| K10           | 2         | 1.3%    |
| Goldmont      | 2         | 1.3%    |
| CometLake     | 2         | 1.3%    |
| Bobcat        | 2         | 1.3%    |
| P6            | 1         | 0.65%   |
| Jaguar        | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 109       | 54.5%   |
| AMD                              | 49        | 24.5%   |
| Nvidia                           | 41        | 20.5%   |
| Silicon Integrated Systems [SiS] | 1         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 11        | 5.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 9         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 9         | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 8         | 3.86%   |
| Intel UHD Graphics 620                                                                | 7         | 3.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 3.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 2.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 5         | 2.42%   |
| Intel HD Graphics 5500                                                                | 5         | 2.42%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 5         | 2.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 2.42%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 1.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.93%   |
| AMD Renoir                                                                            | 4         | 1.93%   |
| AMD Lucienne                                                                          | 4         | 1.93%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 1.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.97%   |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 0.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 0.97%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                             | 2         | 0.97%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.97%   |
| Intel HD Graphics 630                                                                 | 2         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 0.97%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 2         | 0.97%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 2         | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 2         | 0.97%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 2         | 0.97%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                               | 2         | 0.97%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 0.97%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                     | 1         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.48%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 0.48%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 44.16%  |
| 1 x AMD        | 28        | 18.18%  |
| Intel + Nvidia | 27        | 17.53%  |
| Intel + AMD    | 14        | 9.09%   |
| 1 x Nvidia     | 9         | 5.84%   |
| AMD + Nvidia   | 5         | 3.25%   |
| 2 x AMD        | 2         | 1.3%    |
| 1 x SiS        | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 129       | 83.23%  |
| Proprietary | 22        | 14.19%  |
| Unknown     | 4         | 2.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 59.12%  |
| 1.01-2.0   | 24        | 15.09%  |
| 0.01-0.5   | 16        | 10.06%  |
| 0.51-1.0   | 12        | 7.55%   |
| 3.01-4.0   | 9         | 5.66%   |
| 5.01-6.0   | 2         | 1.26%   |
| 7.01-8.0   | 1         | 0.63%   |
| 2.01-3.0   | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 24.44%  |
| LG Display              | 22        | 12.22%  |
| Samsung Electronics     | 19        | 10.56%  |
| Chimei Innolux          | 18        | 10%     |
| BOE                     | 17        | 9.44%   |
| Lenovo                  | 10        | 5.56%   |
| Dell                    | 10        | 5.56%   |
| Chi Mei Optoelectronics | 7         | 3.89%   |
| Sharp                   | 3         | 1.67%   |
| LG Philips              | 3         | 1.67%   |
| AOC                     | 3         | 1.67%   |
| TMX                     | 2         | 1.11%   |
| HannStar                | 2         | 1.11%   |
| Goldstar                | 2         | 1.11%   |
| CSO                     | 2         | 1.11%   |
| ViewSonic               | 1         | 0.56%   |
| Unknown (XXX)           | 1         | 0.56%   |
| Unknown                 | 1         | 0.56%   |
| Sony                    | 1         | 0.56%   |
| Philips                 | 1         | 0.56%   |
| PANDA                   | 1         | 0.56%   |
| NEC Computers           | 1         | 0.56%   |
| Medion                  | 1         | 0.56%   |
| LGD                     | 1         | 0.56%   |
| InfoVision              | 1         | 0.56%   |
| IBM                     | 1         | 0.56%   |
| Hewlett-Packard         | 1         | 0.56%   |
| Gericom                 | 1         | 0.56%   |
| CPT                     | 1         | 0.56%   |
| BenQ                    | 1         | 0.56%   |
| ASUSTek Computer        | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 3.8%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 1.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 1.63%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 1.63%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 1.09%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 1.09%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 1.09%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 2         | 1.09%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 2         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 1.09%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.09%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 1.09%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 1.09%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 1.09%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 1.09%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 1.09%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.54%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.54%   |
| Unknown (XXX) M22EI4 XXX076E 1680x1050 474x296mm 22.0-inch                | 1         | 0.54%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                   | 1         | 0.54%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.54%   |
| Sony TV SNYAA01 1360x768                                                  | 1         | 0.54%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 1         | 0.54%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                   | 1         | 0.54%   |
| Sharp LCD Monitor SHP1450 3840x2160 350x190mm 15.7-inch                   | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch      | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 440x300mm 21.0-inch      | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM02B5 1920x1200 518x324mm 24.1-inch      | 1         | 0.54%   |
| Samsung Electronics S27D390 SAM0B66 1920x1080 598x336mm 27.0-inch         | 1         | 0.54%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 530x300mm 24.0-inch         | 1         | 0.54%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch      | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch      | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 76        | 45.51%  |
| 1366x768 (WXGA)    | 33        | 19.76%  |
| 1600x900 (HD+)     | 17        | 10.18%  |
| 1280x800 (WXGA)    | 6         | 3.59%   |
| 2560x1440 (QHD)    | 5         | 2.99%   |
| 1920x1200 (WUXGA)  | 5         | 2.99%   |
| 1680x1050 (WSXGA+) | 5         | 2.99%   |
| 1440x900 (WXGA+)   | 5         | 2.99%   |
| 3840x2160 (4K)     | 4         | 2.4%    |
| 3440x1440          | 4         | 2.4%    |
| 2560x1600          | 1         | 0.6%    |
| 2520x1680          | 1         | 0.6%    |
| 2288x1287          | 1         | 0.6%    |
| 2256x1504          | 1         | 0.6%    |
| 2048x1152          | 1         | 0.6%    |
| 1400x1050          | 1         | 0.6%    |
| 1280x1024 (SXGA)   | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 43.41%  |
| 17      | 24        | 13.19%  |
| 14      | 16        | 8.79%   |
| 13      | 15        | 8.24%   |
| 24      | 9         | 4.95%   |
| 27      | 6         | 3.3%    |
| 23      | 6         | 3.3%    |
| 34      | 4         | 2.2%    |
| 21      | 4         | 2.2%    |
| 22      | 3         | 1.65%   |
| 18      | 3         | 1.65%   |
| 12      | 3         | 1.65%   |
| 54      | 2         | 1.1%    |
| 142     | 1         | 0.55%   |
| 65      | 1         | 0.55%   |
| 39      | 1         | 0.55%   |
| 33      | 1         | 0.55%   |
| 19      | 1         | 0.55%   |
| 16      | 1         | 0.55%   |
| 11      | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 100       | 55.87%  |
| 351-400        | 26        | 14.53%  |
| 501-600        | 19        | 10.61%  |
| 201-300        | 14        | 7.82%   |
| 401-500        | 9         | 5.03%   |
| 701-800        | 5         | 2.79%   |
| 1001-1500      | 3         | 1.68%   |
| More than 2000 | 1         | 0.56%   |
| 801-900        | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 129       | 80.63%  |
| 16/10   | 21        | 13.13%  |
| 21/9    | 4         | 2.5%    |
| 3/2     | 2         | 1.25%   |
| 5/4     | 1         | 0.63%   |
| 4/3     | 1         | 0.63%   |
| 1.00    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 43.09%  |
| 81-90          | 22        | 12.15%  |
| 121-130        | 22        | 12.15%  |
| 201-250        | 17        | 9.39%   |
| 71-80          | 8         | 4.42%   |
| 301-350        | 6         | 3.31%   |
| 351-500        | 5         | 2.76%   |
| More than 1000 | 4         | 2.21%   |
| 61-70          | 3         | 1.66%   |
| 251-300        | 3         | 1.66%   |
| 151-200        | 3         | 1.66%   |
| 141-150        | 2         | 1.1%    |
| 131-140        | 2         | 1.1%    |
| 91-100         | 2         | 1.1%    |
| 51-60          | 1         | 0.55%   |
| 111-120        | 1         | 0.55%   |
| 501-1000       | 1         | 0.55%   |
| Unknown        | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 72        | 40.45%  |
| 101-120       | 51        | 28.65%  |
| 51-100        | 37        | 20.79%  |
| 161-240       | 9         | 5.06%   |
| More than 240 | 4         | 2.25%   |
| 1-50          | 4         | 2.25%   |
| Unknown       | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 126       | 78.75%  |
| 2     | 29        | 18.13%  |
| 3     | 3         | 1.88%   |
| 0     | 2         | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 86        | 35.25%  |
| Realtek Semiconductor             | 78        | 31.97%  |
| Qualcomm Atheros                  | 34        | 13.93%  |
| Broadcom                          | 16        | 6.56%   |
| Ralink                            | 4         | 1.64%   |
| Huawei Technologies               | 3         | 1.23%   |
| ASUSTek Computer                  | 3         | 1.23%   |
| Sierra Wireless                   | 2         | 0.82%   |
| Samsung Electronics               | 2         | 0.82%   |
| Ralink Technology                 | 2         | 0.82%   |
| MediaTek                          | 2         | 0.82%   |
| Marvell Technology Group          | 2         | 0.82%   |
| Hewlett-Packard                   | 2         | 0.82%   |
| Ericsson Business Mobile Networks | 2         | 0.82%   |
| Broadcom Limited                  | 2         | 0.82%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.41%   |
| Lenovo                            | 1         | 0.41%   |
| JMicron Technology                | 1         | 0.41%   |
| ASIX Electronics                  | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 16.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 4.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.24%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 2.59%   |
| Intel Wireless 7260                                               | 8         | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.62%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.62%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.29%   |
| Intel Wireless 7265                                               | 4         | 1.29%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.29%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.29%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.97%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.97%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 0.97%   |
| Huawei SNE-LX1                                                    | 3         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 82        | 50.31%  |
| Qualcomm Atheros      | 29        | 17.79%  |
| Realtek Semiconductor | 23        | 14.11%  |
| Broadcom              | 13        | 7.98%   |
| Ralink                | 4         | 2.45%   |
| ASUSTek Computer      | 3         | 1.84%   |
| Sierra Wireless       | 2         | 1.23%   |
| Ralink Technology     | 2         | 1.23%   |
| MediaTek              | 2         | 1.23%   |
| Broadcom Limited      | 2         | 1.23%   |
| Hewlett-Packard       | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 9         | 5.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 4.91%   |
| Intel Wireless 7260                                                     | 8         | 4.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 4.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 3.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.07%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.45%   |
| Intel Wireless 7265                                                     | 4         | 2.45%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.84%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.84%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.84%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.23%   |
| Intel Wireless 8260                                                     | 2         | 1.23%   |
| Intel Wireless 3165                                                     | 2         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.23%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.23%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.23%   |
| ASUS 802.11n NIC                                                        | 2         | 1.23%   |
| Sierra Wireless MC8305 Modem                                            | 1         | 0.61%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 71        | 49.65%  |
| Intel                            | 46        | 32.17%  |
| Qualcomm Atheros                 | 10        | 6.99%   |
| Broadcom                         | 5         | 3.5%    |
| Huawei Technologies              | 3         | 2.1%    |
| Samsung Electronics              | 2         | 1.4%    |
| Marvell Technology Group         | 2         | 1.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.7%    |
| Lenovo                           | 1         | 0.7%    |
| JMicron Technology               | 1         | 0.7%    |
| ASIX Electronics                 | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 35.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 10.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 6.99%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 3.5%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.8%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 2.1%    |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.1%    |
| Intel 82562GT 10/100 Network Connection                           | 3         | 2.1%    |
| Huawei SNE-LX1                                                    | 3         | 2.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.4%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 1.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.4%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.4%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.7%    |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.7%    |
| Intel PRO/100 VE Network Connection                               | 1         | 0.7%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.7%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.7%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.7%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.7%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.7%    |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.7%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.7%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 52.56%  |
| Ethernet | 136       | 46.42%  |
| Modem    | 3         | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 119       | 73.01%  |
| Ethernet | 44        | 26.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 130       | 83.87%  |
| 1     | 25        | 16.13%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 98.06%  |
| Yes  | 3         | 1.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 43.41%  |
| IMC Networks                    | 14        | 10.85%  |
| Broadcom                        | 13        | 10.08%  |
| Realtek Semiconductor           | 12        | 9.3%    |
| Qualcomm Atheros Communications | 12        | 9.3%    |
| Hewlett-Packard                 | 5         | 3.88%   |
| Ralink                          | 3         | 2.33%   |
| Lite-On Technology              | 3         | 2.33%   |
| Cambridge Silicon Radio         | 3         | 2.33%   |
| Toshiba                         | 2         | 1.55%   |
| ASUSTek Computer                | 2         | 1.55%   |
| Ralink Technology               | 1         | 0.78%   |
| Foxconn International           | 1         | 0.78%   |
| Foxconn / Hon Hai               | 1         | 0.78%   |
| Chicony Electronics             | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 15.5%   |
| Intel AX201 Bluetooth                               | 13        | 10.08%  |
| Intel AX200 Bluetooth                               | 9         | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 6.2%    |
| Realtek Bluetooth Radio                             | 7         | 5.43%   |
| IMC Networks Bluetooth Radio                        | 6         | 4.65%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.1%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 3.1%    |
| Ralink RT3290 Bluetooth                             | 3         | 2.33%   |
| IMC Networks Bluetooth Device                       | 3         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.33%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 1.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.55%   |
| Intel AX210 Bluetooth                               | 2         | 1.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.55%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.55%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.55%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.55%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.78%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.78%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.78%   |
| Lite-On Bluetooth Device                            | 1         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.78%   |
| IMC Networks Wireless_Device                        | 1         | 0.78%   |
| IMC Networks Bluetooth module                       | 1         | 0.78%   |
| IMC Networks Bluetooth                              | 1         | 0.78%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.78%   |
| Foxconn / Hon Hai BT                                | 1         | 0.78%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 127       | 68.28%  |
| AMD                              | 33        | 17.74%  |
| Nvidia                           | 19        | 10.22%  |
| Texas Instruments                | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Logitech                         | 1         | 0.54%   |
| Lenovo                           | 1         | 0.54%   |
| JMTek                            | 1         | 0.54%   |
| Hewlett-Packard                  | 1         | 0.54%   |
| C-Media Electronics              | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 7.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 5.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 4.85%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 4.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 3.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.52%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 3.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.52%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 3.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 3.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 3.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.2%    |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 2.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 2.2%    |
| AMD FCH Azalia Controller                                                  | 4         | 1.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.32%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.32%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.88%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.88%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.88%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.44%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.44%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.44%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 28        | 27.45%  |
| Samsung Electronics | 23        | 22.55%  |
| Micron Technology   | 15        | 14.71%  |
| Crucial             | 8         | 7.84%   |
| Unknown             | 7         | 6.86%   |
| Kingston            | 7         | 6.86%   |
| Elpida              | 4         | 3.92%   |
| Nanya Technology    | 3         | 2.94%   |
| Ramaxel Technology  | 2         | 1.96%   |
| A-DATA Technology   | 2         | 1.96%   |
| Qimonda             | 1         | 0.98%   |
| Patriot             | 1         | 0.98%   |
| ChangXin Memory     | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 3         | 2.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 3         | 2.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3         | 2.63%   |
| Unknown RAM Module 2GB SODIMM DDR2                         | 2         | 1.75%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 2         | 1.75%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 2         | 1.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 1.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 1.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 2         | 1.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.75%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s       | 2         | 1.75%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s     | 2         | 1.75%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s  | 2         | 1.75%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                | 1         | 0.88%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                  | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 1         | 0.88%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s        | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DRAM                      | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 1         | 0.88%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s               | 1         | 0.88%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 0.88%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.88%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s            | 1         | 0.88%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.88%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s              | 1         | 0.88%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s              | 1         | 0.88%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s              | 1         | 0.88%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.88%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s      | 1         | 0.88%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR2 667MT/s     | 1         | 0.88%   |
| SK hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR2 667MT/s   | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.88%   |
| SK hynix RAM HMT112S6BFR6C-H9 1GB SODIMM DDR3 1333MT/s     | 1         | 0.88%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.88%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 35        | 41.67%  |
| DDR3   | 33        | 39.29%  |
| DDR2   | 7         | 8.33%   |
| SDRAM  | 3         | 3.57%   |
| LPDDR4 | 3         | 3.57%   |
| LPDDR3 | 2         | 2.38%   |
| DRAM   | 1         | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 78        | 91.76%  |
| Row Of Chips | 6         | 7.06%   |
| Chip         | 1         | 1.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 32.22%  |
| 4096  | 26        | 28.89%  |
| 16384 | 16        | 17.78%  |
| 2048  | 13        | 14.44%  |
| 1024  | 3         | 3.33%   |
| 32768 | 2         | 2.22%   |
| 512   | 1         | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 24        | 25.81%  |
| 2667    | 21        | 22.58%  |
| 3200    | 8         | 8.6%    |
| 1334    | 7         | 7.53%   |
| 2400    | 5         | 5.38%   |
| 1333    | 5         | 5.38%   |
| 2133    | 4         | 4.3%    |
| 667     | 4         | 4.3%    |
| Unknown | 3         | 3.23%   |
| 4267    | 2         | 2.15%   |
| 4199    | 2         | 2.15%   |
| 8400    | 1         | 1.08%   |
| 3733    | 1         | 1.08%   |
| 2048    | 1         | 1.08%   |
| 1867    | 1         | 1.08%   |
| 1067    | 1         | 1.08%   |
| 975     | 1         | 1.08%   |
| 800     | 1         | 1.08%   |
| 533     | 1         | 1.08%   |

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
| Chicony Electronics                    | 42        | 32.31%  |
| IMC Networks                           | 18        | 13.85%  |
| Realtek Semiconductor                  | 11        | 8.46%   |
| Quanta                                 | 9         | 6.92%   |
| Acer                                   | 8         | 6.15%   |
| Sunplus Innovation Technology          | 7         | 5.38%   |
| Microdia                               | 6         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.62%   |
| Lite-On Technology                     | 5         | 3.85%   |
| Suyin                                  | 3         | 2.31%   |
| Lenovo                                 | 3         | 2.31%   |
| Syntek                                 | 2         | 1.54%   |
| Primax Electronics                     | 2         | 1.54%   |
| Generalplus Technology                 | 2         | 1.54%   |
| Unknown (3730304231393931415053)       | 1         | 0.77%   |
| Samsung Electronics                    | 1         | 0.77%   |
| Ricoh                                  | 1         | 0.77%   |
| Luxvisions Innotech Limited            | 1         | 0.77%   |
| Logitech                               | 1         | 0.77%   |
| Apple                                  | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 6.82%   |
| Microdia Integrated_Webcam_HD                               | 6         | 4.55%   |
| IMC Networks Integrated Camera                              | 6         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 3.03%   |
| Acer Integrated Camera                                      | 4         | 3.03%   |
| Sunplus HP HD Webcam [Fixed]                                | 3         | 2.27%   |
| Realtek USB Camera                                          | 3         | 2.27%   |
| Chicony HP HD Webcam                                        | 3         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 3         | 2.27%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.52%   |
| Sunplus HD WebCam                                           | 2         | 1.52%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.52%   |
| Realtek Asus laptop camera                                  | 2         | 1.52%   |
| Quanta HP Webcam                                            | 2         | 1.52%   |
| Quanta HP TrueVision HD Camera                              | 2         | 1.52%   |
| Quanta HP HD Camera                                         | 2         | 1.52%   |
| Primax HP HD Webcam [Fixed]                                 | 2         | 1.52%   |
| Lite-On HP HD Webcam                                        | 2         | 1.52%   |
| Lite-On HP HD Camera                                        | 2         | 1.52%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 1.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.52%   |
| IMC Networks Integrated Webcam                              | 2         | 1.52%   |
| Generalplus GENERAL WEBCAM                                  | 2         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.52%   |
| Chicony USB2.0 UVC WebCam                                   | 2         | 1.52%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.52%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.52%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.52%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.52%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.52%   |
| Chicony HP Webcam                                           | 2         | 1.52%   |
| Chicony HP TrueVision HD Camera                             | 2         | 1.52%   |
| Acer Integrated IR Camera                                   | 2         | 1.52%   |
| Unknown (3730304231393931415053) USB Camera                 | 1         | 0.76%   |
| Suyin HP Webcam-50                                          | 1         | 0.76%   |
| Suyin HP Truevision HD                                      | 1         | 0.76%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.76%   |
| Sunplus Integrated Camera                                   | 1         | 0.76%   |
| Sunplus HP Universal Camera                                 | 1         | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 36.96%  |
| Validity Sensors           | 13        | 28.26%  |
| AuthenTec                  | 6         | 13.04%  |
| Upek                       | 4         | 8.7%    |
| Shenzhen Goodix Technology | 4         | 8.7%    |
| STMicroelectronics         | 1         | 2.17%   |
| Elan Microelectronics      | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 6         | 13.04%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 10.87%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 8.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 4         | 8.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 6.52%   |
| Shenzhen Goodix  Fingerprint Device                        | 3         | 6.52%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 4.35%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 4.35%   |
| AuthenTec AES2810                                          | 2         | 4.35%   |
| Unknown                                                    | 2         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.17%   |
| Validity Sensors VFS491                                    | 1         | 2.17%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.17%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.17%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.17%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.17%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.17%   |
| AuthenTec Fingerprint Sensor                               | 1         | 2.17%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 2.17%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.17%   |
| AuthenTec AES1600                                          | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 53.85%  |
| Broadcom    | 3         | 23.08%  |
| O2 Micro    | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 7         | 53.85%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 2         | 15.38%  |
| Broadcom 58200                                             | 2         | 15.38%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 85        | 54.84%  |
| 1     | 47        | 30.32%  |
| 2     | 22        | 14.19%  |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 50%     |
| Chipcard                 | 13        | 14.13%  |
| Graphics card            | 11        | 11.96%  |
| Net/wireless             | 7         | 7.61%   |
| Multimedia controller    | 4         | 4.35%   |
| Bluetooth                | 4         | 4.35%   |
| Communication controller | 3         | 3.26%   |
| Storage                  | 2         | 2.17%   |
| Net/ethernet             | 1         | 1.09%   |
| Camera                   | 1         | 1.09%   |

