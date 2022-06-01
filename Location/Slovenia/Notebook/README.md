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

Total: 216

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 24        | 16.67%  |
| Ubuntu 18.04        | 14        | 9.72%   |
| Debian 11           | 5         | 3.47%   |
| Zorin 16            | 4         | 2.78%   |
| KDE neon 20.04      | 4         | 2.78%   |
| Fedora 34           | 4         | 2.78%   |
| ArcoLinux Rolling   | 4         | 2.78%   |
| Zorin 15            | 3         | 2.08%   |
| Xubuntu 20.04       | 3         | 2.08%   |
| Linux Mint 19.1     | 3         | 2.08%   |
| Kubuntu 21.10       | 3         | 2.08%   |
| Fedora 33           | 3         | 2.08%   |
| Debian Testing      | 3         | 2.08%   |
| Arch                | 3         | 2.08%   |
| Ubuntu 22.04        | 2         | 1.39%   |
| Ubuntu 21.10        | 2         | 1.39%   |
| Ubuntu 21.04        | 2         | 1.39%   |
| Ubuntu 20.10        | 2         | 1.39%   |
| Ubuntu 19.10        | 2         | 1.39%   |
| Pop!_OS 21.04       | 2         | 1.39%   |
| Manjaro 20.2        | 2         | 1.39%   |
| Manjaro             | 2         | 1.39%   |
| Kubuntu 20.04       | 2         | 1.39%   |
| Kubuntu 18.04       | 2         | 1.39%   |
| Gentoo 2.6          | 2         | 1.39%   |
| Endless 3.5.8       | 2         | 1.39%   |
| Ubuntu Budgie 20.04 | 1         | 0.69%   |
| Ubuntu 19.04        | 1         | 0.69%   |
| Ubuntu 16.04        | 1         | 0.69%   |
| ROSA R9             | 1         | 0.69%   |
| ROSA R8             | 1         | 0.69%   |
| Q4OS 4              | 1         | 0.69%   |
| Pop!_OS 22.04       | 1         | 0.69%   |
| Pop!_OS 21.10       | 1         | 0.69%   |
| OpenMandriva 4.3    | 1         | 0.69%   |
| OpenMandriva 4.2    | 1         | 0.69%   |
| Manjaro 21.0.4      | 1         | 0.69%   |
| Manjaro 19.0.2      | 1         | 0.69%   |
| Manjaro 18.1.5      | 1         | 0.69%   |
| Lubuntu 21.04       | 1         | 0.69%   |
| Lubuntu 20.04       | 1         | 0.69%   |
| Linux Mint 20.2     | 1         | 0.69%   |
| Linux Mint 20.1     | 1         | 0.69%   |
| Linux Mint 19.3     | 1         | 0.69%   |
| Kubuntu 22.04       | 1         | 0.69%   |
| Kubuntu 21.04       | 1         | 0.69%   |
| Kubuntu 19.10       | 1         | 0.69%   |
| KDE neon 18.04      | 1         | 0.69%   |
| Garuda Linux        | 1         | 0.69%   |
| Fedora 35           | 1         | 0.69%   |
| Fedora 32           | 1         | 0.69%   |
| Fedora 31           | 1         | 0.69%   |
| Fedora 30           | 1         | 0.69%   |
| Endless 4.0.2       | 1         | 0.69%   |
| Endless 3.9.4       | 1         | 0.69%   |
| Endless 3.9.1       | 1         | 0.69%   |
| Endless 3.8.7       | 1         | 0.69%   |
| Endless 3.7.4       | 1         | 0.69%   |
| Endless 3.6.3       | 1         | 0.69%   |
| Endless 3.5.3       | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 47        | 34.81%  |
| Fedora        | 10        | 7.41%   |
| Kubuntu       | 9         | 6.67%   |
| Debian        | 9         | 6.67%   |
| Zorin         | 7         | 5.19%   |
| Endless       | 7         | 5.19%   |
| Manjaro       | 6         | 4.44%   |
| Linux Mint    | 6         | 4.44%   |
| KDE neon      | 5         | 3.7%    |
| Pop!_OS       | 4         | 2.96%   |
| ArcoLinux     | 4         | 2.96%   |
| Xubuntu       | 3         | 2.22%   |
| Arch          | 3         | 2.22%   |
| OpenMandriva  | 2         | 1.48%   |
| Lubuntu       | 2         | 1.48%   |
| Gentoo        | 2         | 1.48%   |
| Ubuntu Budgie | 1         | 0.74%   |
| ROSA          | 1         | 0.74%   |
| Q4OS          | 1         | 0.74%   |
| Garuda Linux  | 1         | 0.74%   |
| EndeavourOS   | 1         | 0.74%   |
| Elementary    | 1         | 0.74%   |
| Clear Linux   | 1         | 0.74%   |
| Chrome OS     | 1         | 0.74%   |
| BlackPanther  | 1         | 0.74%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.4.0-42-generic       | 4         | 2.53%   |
| 4.18.0-15-generic      | 4         | 2.53%   |
| 5.8.0-41-generic       | 3         | 1.9%    |
| 5.3.0-40-generic       | 3         | 1.9%    |
| 5.13.0-41-generic      | 3         | 1.9%    |
| 5.13.0-30-generic      | 3         | 1.9%    |
| 5.13.0-28-generic      | 3         | 1.9%    |
| 5.13.0-21-generic      | 3         | 1.9%    |
| 5.8.0-44-generic       | 2         | 1.27%   |
| 5.8.0-14-generic       | 2         | 1.27%   |
| 5.6.0-1-amd64          | 2         | 1.27%   |
| 5.4.0-70-generic       | 2         | 1.27%   |
| 5.4.0-56-generic       | 2         | 1.27%   |
| 5.4.0-54-generic       | 2         | 1.27%   |
| 5.4.0-48-generic       | 2         | 1.27%   |
| 5.4.0-40-generic       | 2         | 1.27%   |
| 5.4.0-33-generic       | 2         | 1.27%   |
| 5.4.0-28-generic       | 2         | 1.27%   |
| 5.4.0-26-generic       | 2         | 1.27%   |
| 5.13.19-2-MANJARO      | 2         | 1.27%   |
| 5.13.0-7614-generic    | 2         | 1.27%   |
| 5.11.0-43-generic      | 2         | 1.27%   |
| 5.11.0-40-generic      | 2         | 1.27%   |
| 5.10.0-8-amd64         | 2         | 1.27%   |
| 4.15.0-128-generic     | 2         | 1.27%   |
| 5.9.8-2-MANJARO        | 1         | 0.63%   |
| 5.9.2-arch1-1          | 1         | 0.63%   |
| 5.9.15-200.fc33.x86_64 | 1         | 0.63%   |
| 5.9.14-arch1-1         | 1         | 0.63%   |
| 5.8.8-arch1-1          | 1         | 0.63%   |
| 5.8.5-arch1-1          | 1         | 0.63%   |
| 5.8.18-300.fc33.x86_64 | 1         | 0.63%   |
| 5.8.10-200.fc32.x86_64 | 1         | 0.63%   |
| 5.8.0-48-generic       | 1         | 0.63%   |
| 5.8.0-36-generic       | 1         | 0.63%   |
| 5.8.0-2-amd64          | 1         | 0.63%   |
| 5.7.13-975.native      | 1         | 0.63%   |
| 5.6.14-desktop-2bP     | 1         | 0.63%   |
| 5.6.0-1036-oem         | 1         | 0.63%   |
| 5.5.15-200.fc31.x86_64 | 1         | 0.63%   |
| 5.5.0-1-MANJARO        | 1         | 0.63%   |
| 5.4.80-2-MANJARO       | 1         | 0.63%   |
| 5.4.53+                | 1         | 0.63%   |
| 5.4.27-1-MANJARO       | 1         | 0.63%   |
| 5.4.0-99-generic       | 1         | 0.63%   |
| 5.4.0-94-generic       | 1         | 0.63%   |
| 5.4.0-90-generic       | 1         | 0.63%   |
| 5.4.0-74-generic       | 1         | 0.63%   |
| 5.4.0-67-generic       | 1         | 0.63%   |
| 5.4.0-65-generic       | 1         | 0.63%   |
| 5.4.0-60-generic       | 1         | 0.63%   |
| 5.4.0-58-generic       | 1         | 0.63%   |
| 5.4.0-53-generic       | 1         | 0.63%   |
| 5.4.0-52-generic       | 1         | 0.63%   |
| 5.4.0-45-generic       | 1         | 0.63%   |
| 5.4.0-39-generic       | 1         | 0.63%   |
| 5.4.0-29-generic       | 1         | 0.63%   |
| 5.4.0-100-generic      | 1         | 0.63%   |
| 5.3.6-200.fc30.x86_64  | 1         | 0.63%   |
| 5.3.0-53-generic       | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 20%     |
| 5.13.0  | 16        | 10.67%  |
| 5.11.0  | 11        | 7.33%   |
| 5.8.0   | 9         | 6%      |
| 4.15.0  | 9         | 6%      |
| 5.3.0   | 8         | 5.33%   |
| 4.18.0  | 8         | 5.33%   |
| 5.10.0  | 5         | 3.33%   |
| 5.0.0   | 4         | 2.67%   |
| 5.6.0   | 3         | 2%      |
| 5.15.0  | 2         | 1.33%   |
| 5.13.19 | 2         | 1.33%   |
| 5.10.14 | 2         | 1.33%   |
| 5.9.8   | 1         | 0.67%   |
| 5.9.2   | 1         | 0.67%   |
| 5.9.15  | 1         | 0.67%   |
| 5.9.14  | 1         | 0.67%   |
| 5.8.8   | 1         | 0.67%   |
| 5.8.5   | 1         | 0.67%   |
| 5.8.18  | 1         | 0.67%   |
| 5.8.10  | 1         | 0.67%   |
| 5.7.13  | 1         | 0.67%   |
| 5.6.14  | 1         | 0.67%   |
| 5.5.15  | 1         | 0.67%   |
| 5.5.0   | 1         | 0.67%   |
| 5.4.80  | 1         | 0.67%   |
| 5.4.53  | 1         | 0.67%   |
| 5.4.27  | 1         | 0.67%   |
| 5.3.6   | 1         | 0.67%   |
| 5.17.5  | 1         | 0.67%   |
| 5.17.4  | 1         | 0.67%   |
| 5.17.1  | 1         | 0.67%   |
| 5.16.7  | 1         | 0.67%   |
| 5.16.4  | 1         | 0.67%   |
| 5.16.19 | 1         | 0.67%   |
| 5.16.16 | 1         | 0.67%   |
| 5.16.0  | 1         | 0.67%   |
| 5.15.5  | 1         | 0.67%   |
| 5.15.2  | 1         | 0.67%   |
| 5.15.10 | 1         | 0.67%   |
| 5.14.16 | 1         | 0.67%   |
| 5.14.11 | 1         | 0.67%   |
| 5.13.9  | 1         | 0.67%   |
| 5.12.9  | 1         | 0.67%   |
| 5.12.8  | 1         | 0.67%   |
| 5.12.2  | 1         | 0.67%   |
| 5.11.15 | 1         | 0.67%   |
| 5.11.11 | 1         | 0.67%   |
| 4.9.20  | 1         | 0.67%   |
| 4.19.72 | 1         | 0.67%   |
| 4.19.0  | 1         | 0.67%   |
| 4.18.16 | 1         | 0.67%   |
| 4.14.83 | 1         | 0.67%   |
| 4.1.34  | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 32        | 21.62%  |
| 5.13    | 19        | 12.84%  |
| 5.8     | 13        | 8.78%   |
| 5.11    | 13        | 8.78%   |
| 5.3     | 9         | 6.08%   |
| 4.18    | 9         | 6.08%   |
| 4.15    | 9         | 6.08%   |
| 5.10    | 7         | 4.73%   |
| 5.16    | 5         | 3.38%   |
| 5.9     | 4         | 2.7%    |
| 5.6     | 4         | 2.7%    |
| 5.15    | 4         | 2.7%    |
| 5.0     | 4         | 2.7%    |
| 5.17    | 3         | 2.03%   |
| 5.12    | 3         | 2.03%   |
| 5.5     | 2         | 1.35%   |
| 5.14    | 2         | 1.35%   |
| 4.19    | 2         | 1.35%   |
| 5.7     | 1         | 0.68%   |
| 4.9     | 1         | 0.68%   |
| 4.14    | 1         | 0.68%   |
| 4.1     | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 129       | 98.47%  |
| i686   | 2         | 1.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 58        | 42.65%  |
| Unknown    | 26        | 19.12%  |
| KDE5       | 21        | 15.44%  |
| XFCE       | 12        | 8.82%   |
| X-Cinnamon | 3         | 2.21%   |
| LXQt       | 3         | 2.21%   |
| KDE        | 3         | 2.21%   |
| Cinnamon   | 2         | 1.47%   |
| Unity      | 1         | 0.74%   |
| Trinity    | 1         | 0.74%   |
| Pantheon   | 1         | 0.74%   |
| Openbox    | 1         | 0.74%   |
| MATE       | 1         | 0.74%   |
| i3         | 1         | 0.74%   |
| dwm        | 1         | 0.74%   |
| Budgie     | 1         | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 102       | 73.91%  |
| Wayland | 18        | 13.04%  |
| Unknown | 17        | 12.32%  |
| Tty     | 1         | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 53.62%  |
| SDDM    | 22        | 15.94%  |
| GDM     | 17        | 12.32%  |
| TDM     | 9         | 6.52%   |
| LightDM | 8         | 5.8%    |
| GDM3    | 8         | 5.8%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 65        | 48.87%  |
| sl_SI   | 30        | 22.56%  |
| Unknown | 26        | 19.55%  |
| en_GB   | 6         | 4.51%   |
| en_SI   | 3         | 2.26%   |
| C       | 2         | 1.5%    |
| hr_HR   | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 72        | 53.73%  |
| BIOS | 62        | 46.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 109       | 80.15%  |
| Btrfs   | 9         | 6.62%   |
| Overlay | 8         | 5.88%   |
| Unknown | 8         | 5.88%   |
| Zfs     | 1         | 0.74%   |
| Ext2    | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 59.12%  |
| GPT     | 38        | 27.74%  |
| MBR     | 18        | 13.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 124       | 93.23%  |
| Yes       | 9         | 6.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 70.9%   |
| Yes       | 39        | 29.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 45        | 34.35%  |
| Lenovo              | 38        | 29.01%  |
| ASUSTek Computer    | 16        | 12.21%  |
| Dell                | 13        | 9.92%   |
| Acer                | 5         | 3.82%   |
| Toshiba             | 4         | 3.05%   |
| MSI                 | 2         | 1.53%   |
| Razer               | 1         | 0.76%   |
| PC Specialist       | 1         | 0.76%   |
| Panasonic           | 1         | 0.76%   |
| Medion              | 1         | 0.76%   |
| Gigabyte Technology | 1         | 0.76%   |
| Fujitsu Siemens     | 1         | 0.76%   |
| Fujitsu             | 1         | 0.76%   |
| eMachines           | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| HP 255 G7 Notebook PC                             | 3         | 2.29%   |
| Toshiba Satellite L750                            | 2         | 1.53%   |
| Lenovo ThinkPad T410 2522A92                      | 2         | 1.53%   |
| HP EliteBook 8760w                                | 2         | 1.53%   |
| Dell Inspiron 5570                                | 2         | 1.53%   |
| Toshiba Satellite Pro U400                        | 1         | 0.76%   |
| Toshiba QOSMIO X500                               | 1         | 0.76%   |
| Razer Blade 14 - RZ09-0370                        | 1         | 0.76%   |
| PC Specialist Fusion IV                           | 1         | 0.76%   |
| Panasonic CF-53SWWZ5MG                            | 1         | 0.76%   |
| MSI U210                                          | 1         | 0.76%   |
| MSI GP60 2OD                                      | 1         | 0.76%   |
| Medion E7218                                      | 1         | 0.76%   |
| Lenovo Yoga S740-14IIL 81RS                       | 1         | 0.76%   |
| Lenovo Yoga 2 13 20344                            | 1         | 0.76%   |
| Lenovo ThinkPad X250 20CM004ESC                   | 1         | 0.76%   |
| Lenovo ThinkPad X230 23202DG                      | 1         | 0.76%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW             | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW        | 1         | 0.76%   |
| Lenovo ThinkPad W530 24479K4                      | 1         | 0.76%   |
| Lenovo ThinkPad T61 8897CTO                       | 1         | 0.76%   |
| Lenovo ThinkPad T590 20N5S0YN00                   | 1         | 0.76%   |
| Lenovo ThinkPad T590 20N5S0MR00                   | 1         | 0.76%   |
| Lenovo ThinkPad T500 2055WYX                      | 1         | 0.76%   |
| Lenovo ThinkPad T480 20L6S01W00                   | 1         | 0.76%   |
| Lenovo ThinkPad T460s 20FAS7XT01                  | 1         | 0.76%   |
| Lenovo ThinkPad T420 4236A78                      | 1         | 0.76%   |
| Lenovo ThinkPad T420 423662G                      | 1         | 0.76%   |
| Lenovo ThinkPad T15 Gen 1 20S6000NSC              | 1         | 0.76%   |
| Lenovo ThinkPad S3 Yoga 14 20DM008FSC             | 1         | 0.76%   |
| Lenovo ThinkPad R61 8933W4F                       | 1         | 0.76%   |
| Lenovo ThinkPad P53 20QN000DGE                    | 1         | 0.76%   |
| Lenovo ThinkPad P52 20MAS5XN00                    | 1         | 0.76%   |
| Lenovo ThinkPad L520 785958G                      | 1         | 0.76%   |
| Lenovo ThinkPad Edge E540 20C60043SC              | 1         | 0.76%   |
| Lenovo ThinkPad Edge 326054G                      | 1         | 0.76%   |
| Lenovo ThinkPad E595 20NF0000GE                   | 1         | 0.76%   |
| Lenovo ThinkPad E590 20NB002BSC                   | 1         | 0.76%   |
| Lenovo ThinkPad E495 20NECTO1WW                   | 1         | 0.76%   |
| Lenovo ThinkPad E15 Gen 3 20YG003VGE              | 1         | 0.76%   |
| Lenovo ThinkPad E15 20RD0011SC                    | 1         | 0.76%   |
| Lenovo Legion 7 16ACHg6 82N6                      | 1         | 0.76%   |
| Lenovo IdeaPad 5 15IIL05 81YK                     | 1         | 0.76%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                     | 1         | 0.76%   |
| Lenovo IdeaPad 320-17ISK 80XJ                     | 1         | 0.76%   |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 0.76%   |
| Lenovo IdeaPad 100-15IBY 80MJ                     | 1         | 0.76%   |
| Lenovo G585 20137                                 | 1         | 0.76%   |
| Lenovo G510 20238                                 | 1         | 0.76%   |
| HP ZBook Firefly 15 inch G8 Mobile Workstation PC | 1         | 0.76%   |
| HP ZBook 17 G2                                    | 1         | 0.76%   |
| HP ZBook 15u G3                                   | 1         | 0.76%   |
| HP ZBook 14 G2                                    | 1         | 0.76%   |
| HP ProBook 4740s                                  | 1         | 0.76%   |
| HP ProBook 4730s                                  | 1         | 0.76%   |
| HP ProBook 4720s                                  | 1         | 0.76%   |
| HP ProBook 4710s                                  | 1         | 0.76%   |
| HP ProBook 470 G2                                 | 1         | 0.76%   |
| HP ProBook 4540s                                  | 1         | 0.76%   |
| HP ProBook 4515s (VC377ES#AKB)                    | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 28        | 21.37%  |
| HP EliteBook            | 10        | 7.63%   |
| HP ProBook              | 9         | 6.87%   |
| Lenovo IdeaPad          | 5         | 3.82%   |
| Dell Inspiron           | 5         | 3.82%   |
| HP ZBook                | 4         | 3.05%   |
| HP 250                  | 4         | 3.05%   |
| Dell Latitude           | 4         | 3.05%   |
| Toshiba Satellite       | 3         | 2.29%   |
| HP Pavilion             | 3         | 2.29%   |
| HP Compaq               | 3         | 2.29%   |
| HP 255                  | 3         | 2.29%   |
| ASUS VivoBook           | 3         | 2.29%   |
| Acer Aspire             | 3         | 2.29%   |
| Lenovo Yoga             | 2         | 1.53%   |
| HP Laptop               | 2         | 1.53%   |
| Dell XPS                | 2         | 1.53%   |
| Toshiba QOSMIO          | 1         | 0.76%   |
| Razer Blade             | 1         | 0.76%   |
| PC Specialist Fusion    | 1         | 0.76%   |
| Panasonic CF-53SWWZ5MG  | 1         | 0.76%   |
| MSI U210                | 1         | 0.76%   |
| MSI GP60                | 1         | 0.76%   |
| Medion E7218            | 1         | 0.76%   |
| Lenovo Legion           | 1         | 0.76%   |
| Lenovo G585             | 1         | 0.76%   |
| Lenovo G510             | 1         | 0.76%   |
| HP OMEN                 | 1         | 0.76%   |
| HP kip                  | 1         | 0.76%   |
| HP ENVY                 | 1         | 0.76%   |
| HP 470                  | 1         | 0.76%   |
| HP 2000                 | 1         | 0.76%   |
| HP 15                   | 1         | 0.76%   |
| Gigabyte P65            | 1         | 0.76%   |
| Fujitsu Siemens ESPRIMO | 1         | 0.76%   |
| Fujitsu LIFEBOOK        | 1         | 0.76%   |
| eMachines G730          | 1         | 0.76%   |
| Dell Vostro             | 1         | 0.76%   |
| Dell Precision          | 1         | 0.76%   |
| ASUS X751NV             | 1         | 0.76%   |
| ASUS X750LN             | 1         | 0.76%   |
| ASUS X750LB             | 1         | 0.76%   |
| ASUS X551CA             | 1         | 0.76%   |
| ASUS X550JX             | 1         | 0.76%   |
| ASUS UX31E              | 1         | 0.76%   |
| ASUS TUF                | 1         | 0.76%   |
| ASUS N71Vg              | 1         | 0.76%   |
| ASUS K72Jr              | 1         | 0.76%   |
| ASUS K52JT              | 1         | 0.76%   |
| ASUS G771JW             | 1         | 0.76%   |
| ASUS G751JT             | 1         | 0.76%   |
| ASUS ASUS               | 1         | 0.76%   |
| Acer Predator           | 1         | 0.76%   |
| Acer Nitro              | 1         | 0.76%   |
| Unknown                 | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 20        | 15.27%  |
| 2011 | 12        | 9.16%   |
| 2018 | 11        | 8.4%    |
| 2020 | 10        | 7.63%   |
| 2017 | 10        | 7.63%   |
| 2013 | 10        | 7.63%   |
| 2014 | 8         | 6.11%   |
| 2012 | 8         | 6.11%   |
| 2010 | 8         | 6.11%   |
| 2009 | 7         | 5.34%   |
| 2008 | 7         | 5.34%   |
| 2021 | 6         | 4.58%   |
| 2015 | 6         | 4.58%   |
| 2007 | 4         | 3.05%   |
| 2016 | 3         | 2.29%   |
| 2006 | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 131       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 119       | 89.47%  |
| Enabled  | 14        | 10.53%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 99.24%  |
| Yes  | 1         | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 37        | 28.03%  |
| 8.01-16.0   | 30        | 22.73%  |
| 4.01-8.0    | 26        | 19.7%   |
| 16.01-24.0  | 24        | 18.18%  |
| 32.01-64.0  | 9         | 6.82%   |
| 24.01-32.0  | 2         | 1.52%   |
| 1.01-2.0    | 2         | 1.52%   |
| 2.01-3.0    | 1         | 0.76%   |
| 64.01-256.0 | 1         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 52        | 34.9%   |
| 2.01-3.0   | 40        | 26.85%  |
| 3.01-4.0   | 18        | 12.08%  |
| 4.01-8.0   | 15        | 10.07%  |
| 0.51-1.0   | 13        | 8.72%   |
| 8.01-16.0  | 8         | 5.37%   |
| 0.01-0.5   | 2         | 1.34%   |
| 16.01-24.0 | 1         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 97        | 72.39%  |
| 2      | 29        | 21.64%  |
| 0      | 5         | 3.73%   |
| 3      | 3         | 2.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 51.91%  |
| Yes       | 63        | 48.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 90.08%  |
| No        | 13        | 9.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 99.24%  |
| No        | 1         | 0.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 81.2%   |
| No        | 25        | 18.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovenia | 131       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 52        | 35.62%  |
| Kranj                   | 6         | 4.11%   |
| Celje                   | 5         | 3.42%   |
| Maribor                 | 4         | 2.74%   |
| Vrhnika                 | 3         | 2.05%   |
| Trzin                   | 3         | 2.05%   |
| Portorož               | 3         | 2.05%   |
| Koper                   | 3         | 2.05%   |
| Slovenske Konjice       | 2         | 1.37%   |
| Slovenj Gradec          | 2         | 1.37%   |
| Puconci                 | 2         | 1.37%   |
| Poljane nad Skofjo Loko | 2         | 1.37%   |
| Petrovce                | 2         | 1.37%   |
| Murska Sobota           | 2         | 1.37%   |
| Ajdovščina            | 2         | 1.37%   |
| Žužemberk             | 1         | 0.68%   |
| Ziri                    | 1         | 0.68%   |
| Zgornji Leskovec        | 1         | 0.68%   |
| Zgornja Besnica         | 1         | 0.68%   |
| Žalec                  | 1         | 0.68%   |
| Zagorje ob Savi         | 1         | 0.68%   |
| Visoko                  | 1         | 0.68%   |
| Velenje                 | 1         | 0.68%   |
| Trzic                   | 1         | 0.68%   |
| Trbovlje                | 1         | 0.68%   |
| Tabor                   | 1         | 0.68%   |
| Solkan                  | 1         | 0.68%   |
| Smartno ob Paki         | 1         | 0.68%   |
| Smarje pri Jelsah       | 1         | 0.68%   |
| Škofja Loka            | 1         | 0.68%   |
| Skocjan                 | 1         | 0.68%   |
| Sežana                 | 1         | 0.68%   |
| Šentjernej             | 1         | 0.68%   |
| Ruše                   | 1         | 0.68%   |
| Rogasovci               | 1         | 0.68%   |
| Rogaška Slatina        | 1         | 0.68%   |
| Rence                   | 1         | 0.68%   |
| Ptuj                    | 1         | 0.68%   |
| Preserje pri Komnu      | 1         | 0.68%   |
| Preddvor                | 1         | 0.68%   |
| Pragersko               | 1         | 0.68%   |
| Pobegi                  | 1         | 0.68%   |
| Ormoz                   | 1         | 0.68%   |
| Orehova Vas             | 1         | 0.68%   |
| Oplotnica               | 1         | 0.68%   |
| Novo Mesto              | 1         | 0.68%   |
| Notranje Gorice         | 1         | 0.68%   |
| Muta                    | 1         | 0.68%   |
| Mozirje                 | 1         | 0.68%   |
| Medvode                 | 1         | 0.68%   |
| Loski Potok             | 1         | 0.68%   |
| Logatec                 | 1         | 0.68%   |
| Log pri Brezovici       | 1         | 0.68%   |
| Ljutomer                | 1         | 0.68%   |
| Lesicno                 | 1         | 0.68%   |
| Lendava                 | 1         | 0.68%   |
| Kotlje                  | 1         | 0.68%   |
| Komenda                 | 1         | 0.68%   |
| Kolomban                | 1         | 0.68%   |
| Klenovik                | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 20        | 31     | 13.07%  |
| Seagate                 | 16        | 19     | 10.46%  |
| WDC                     | 14        | 14     | 9.15%   |
| Toshiba                 | 14        | 22     | 9.15%   |
| Crucial                 | 14        | 20     | 9.15%   |
| Sandisk                 | 11        | 13     | 7.19%   |
| SK Hynix                | 10        | 13     | 6.54%   |
| Kingston                | 9         | 14     | 5.88%   |
| HGST                    | 9         | 10     | 5.88%   |
| Hitachi                 | 8         | 11     | 5.23%   |
| Unknown                 | 4         | 5      | 2.61%   |
| Intel                   | 4         | 4      | 2.61%   |
| Transcend               | 2         | 2      | 1.31%   |
| Micron Technology       | 2         | 2      | 1.31%   |
| LITEON                  | 2         | 2      | 1.31%   |
| Intenso                 | 2         | 2      | 1.31%   |
| Fujitsu                 | 2         | 3      | 1.31%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.65%   |
| SABRENT                 | 1         | 1      | 0.65%   |
| Patriot                 | 1         | 2      | 0.65%   |
| OCZ                     | 1         | 1      | 0.65%   |
| LITEONIT                | 1         | 1      | 0.65%   |
| Lenovo                  | 1         | 1      | 0.65%   |
| KIOXIA                  | 1         | 1      | 0.65%   |
| JMicron                 | 1         | 1      | 0.65%   |
| HGST HTS                | 1         | 1      | 0.65%   |
| Gigabyte Technology     | 1         | 2      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                     | 5         | 3.14%   |
| Samsung NVMe SSD Drive 512GB                 | 4         | 2.52%   |
| Hitachi HTS547575A9E384 752GB                | 3         | 1.89%   |
| Crucial CT240BX500SSD1 240GB                 | 3         | 1.89%   |
| Toshiba MQ04ABF100 1TB                       | 2         | 1.26%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 1.26%   |
| SK Hynix SC311 SATA 256GB SSD                | 2         | 1.26%   |
| Seagate ST9750420AS 752GB                    | 2         | 1.26%   |
| Seagate ST9500325AS 500GB                    | 2         | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 1.26%   |
| Sandisk NVMe SSD Drive 512GB                 | 2         | 1.26%   |
| Samsung NVMe SSD Drive 256GB                 | 2         | 1.26%   |
| Samsung NVMe SSD Drive 1024GB                | 2         | 1.26%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 1.26%   |
| Kingston SA400S37120G 120GB SSD              | 2         | 1.26%   |
| Hitachi HTS725032A9A364 320GB                | 2         | 1.26%   |
| HGST HTS545050A7E680 500GB                   | 2         | 1.26%   |
| Crucial CT2000MX500SSD1 2TB                  | 2         | 1.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1         | 0.63%   |
| WDC WDS100T3X0C-00SJG0 1TB                   | 1         | 0.63%   |
| WDC WDS100T2B0B-00YS70 1TB SSD               | 1         | 0.63%   |
| WDC WD7500BPVX-60JC3T0 752GB                 | 1         | 0.63%   |
| WDC WD3200BEKT-22KA9T0 320GB                 | 1         | 0.63%   |
| WDC WD2500BEVT-60ZCT1 250GB                  | 1         | 0.63%   |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 0.63%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 0.63%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB         | 1         | 0.63%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB         | 1         | 0.63%   |
| WDC PC SN520 NVMe 512GB                      | 1         | 0.63%   |
| Unknown SD128  128GB                         | 1         | 0.63%   |
| Unknown NVMe SSD Drive 512GB                 | 1         | 0.63%   |
| Unknown MMC Card  32GB                       | 1         | 0.63%   |
| Unknown MMC Card  16GB                       | 1         | 0.63%   |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 1         | 0.63%   |
| Transcend TS512GMTS800 512GB SSD             | 1         | 0.63%   |
| Transcend TS256GSSD370 256GB                 | 1         | 0.63%   |
| Toshiba THNSN5512GPUK NVMe 512GB             | 1         | 0.63%   |
| Toshiba THNSN5256GPUK 256GB                  | 1         | 0.63%   |
| Toshiba THNSFJ256GDNU A 256GB SSD            | 1         | 0.63%   |
| Toshiba NVMe SSD Drive 1024GB                | 1         | 0.63%   |
| Toshiba MK6475GSX 640GB                      | 1         | 0.63%   |
| Toshiba MK6465GSX 640GB                      | 1         | 0.63%   |
| Toshiba MK5055GSX 500GB                      | 1         | 0.63%   |
| Toshiba MK3265GSX 320GB                      | 1         | 0.63%   |
| Toshiba KBG40ZNT512G MEMORY 512GB            | 1         | 0.63%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD          | 1         | 0.63%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB         | 1         | 0.63%   |
| SK Hynix SKHynix_HFM512GD3HX015N 512GB       | 1         | 0.63%   |
| SK Hynix PC711 HFS512GDE9X073N 512GB         | 1         | 0.63%   |
| SK Hynix PC601 NVMe 1TB                      | 1         | 0.63%   |
| SK Hynix NVMe SSD Drive 512GB                | 1         | 0.63%   |
| SK Hynix NVMe SSD Drive 1024GB               | 1         | 0.63%   |
| SK Hynix HFS256G3BTND-N210A 256GB SSD        | 1         | 0.63%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB      | 1         | 0.63%   |
| SK Hynix BC501 HFM512GDJTNG-8310A 512GB      | 1         | 0.63%   |
| Seagate ST9500423AS 500GB                    | 1         | 0.63%   |
| Seagate ST9320423AS 320GB                    | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 16        | 19     | 31.37%  |
| HGST     | 9         | 10     | 17.65%  |
| Toshiba  | 8         | 14     | 15.69%  |
| Hitachi  | 8         | 11     | 15.69%  |
| WDC      | 6         | 6      | 11.76%  |
| Fujitsu  | 2         | 3      | 3.92%   |
| SABRENT  | 1         | 1      | 1.96%   |
| HGST HTS | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 13        | 19     | 23.21%  |
| Samsung Electronics | 9         | 12     | 16.07%  |
| Kingston            | 8         | 12     | 14.29%  |
| SanDisk             | 6         | 8      | 10.71%  |
| WDC                 | 4         | 4      | 7.14%   |
| SK Hynix            | 3         | 3      | 5.36%   |
| Transcend           | 2         | 2      | 3.57%   |
| LITEON              | 2         | 2      | 3.57%   |
| Intenso             | 2         | 2      | 3.57%   |
| Toshiba             | 1         | 1      | 1.79%   |
| Patriot             | 1         | 2      | 1.79%   |
| OCZ                 | 1         | 1      | 1.79%   |
| Micron Technology   | 1         | 1      | 1.79%   |
| LITEONIT            | 1         | 1      | 1.79%   |
| Intel               | 1         | 1      | 1.79%   |
| Gigabyte Technology | 1         | 2      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 54        | 73     | 36.73%  |
| HDD     | 49        | 65     | 33.33%  |
| NVMe    | 40        | 56     | 27.21%  |
| MMC     | 3         | 4      | 2.04%   |
| Unknown | 1         | 1      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 131    | 64.75%  |
| NVMe | 40        | 56     | 28.78%  |
| SAS  | 6         | 8      | 4.32%   |
| MMC  | 3         | 4      | 2.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 91     | 64.08%  |
| 0.51-1.0   | 31        | 38     | 30.1%   |
| 1.01-2.0   | 5         | 7      | 4.85%   |
| 3.01-4.0   | 1         | 2      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 41        | 29.08%  |
| 101-250        | 36        | 25.53%  |
| 501-1000       | 22        | 15.6%   |
| 1001-2000      | 11        | 7.8%    |
| 1-20           | 8         | 5.67%   |
| 21-50          | 7         | 4.96%   |
| 51-100         | 7         | 4.96%   |
| 2001-3000      | 5         | 3.55%   |
| Unknown        | 3         | 2.13%   |
| More than 3000 | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 62        | 43.66%  |
| 21-50     | 21        | 14.79%  |
| 101-250   | 18        | 12.68%  |
| 51-100    | 16        | 11.27%  |
| 251-500   | 15        | 10.56%  |
| 501-1000  | 5         | 3.52%   |
| Unknown   | 3         | 2.11%   |
| 1001-2000 | 2         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB         | 2         | 2      | 16.67%  |
| Toshiba MQ01ABF050 500GB           | 1         | 5      | 8.33%   |
| Seagate ST9750420AS 752GB          | 1         | 1      | 8.33%   |
| Seagate ST9500423AS 500GB          | 1         | 1      | 8.33%   |
| Seagate ST9500325AS 500GB          | 1         | 2      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 8.33%   |
| SanDisk SD7SB2Q512G1001 512GB SSD  | 1         | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD   | 1         | 1      | 8.33%   |
| Hitachi HTS727550A9E364 500GB      | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB           | 1         | 1      | 8.33%   |
| Crucial CT120M500SSD1 120GB        | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 5      | 33.33%  |
| HGST     | 3         | 3      | 25%     |
| Toshiba  | 1         | 5      | 8.33%   |
| SanDisk  | 1         | 1      | 8.33%   |
| Kingston | 1         | 1      | 8.33%   |
| Hitachi  | 1         | 1      | 8.33%   |
| Crucial  | 1         | 1      | 8.33%   |

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
| HDD  | 9         | 14     | 75%     |
| SSD  | 3         | 3      | 25%     |

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
| Detected | 80        | 124    | 59.26%  |
| Works    | 42        | 56     | 31.11%  |
| Malfunc  | 12        | 17     | 8.89%   |
| Failed   | 1         | 2      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 62.58%  |
| Samsung Electronics              | 14        | 9.03%   |
| AMD                              | 14        | 9.03%   |
| Sandisk                          | 9         | 5.81%   |
| SK Hynix                         | 7         | 4.52%   |
| Toshiba America Info Systems     | 6         | 3.87%   |
| Union Memory (Shenzhen)          | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Micron/Crucial Technology        | 1         | 0.65%   |
| Micron Technology                | 1         | 0.65%   |
| Marvell Technology Group         | 1         | 0.65%   |
| Lenovo                           | 1         | 0.65%   |
| KIOXIA                           | 1         | 0.65%   |
| Kingston Technology Company      | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 6.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 6.75%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 6.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 6.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 4.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 4.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 3.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 3.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 3.07%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 2.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.45%   |
| SK Hynix Gold P31 SSD                                                            | 3         | 1.84%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.23%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 1.23%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 1.23%   |
| SK Hynix BC511                                                                   | 2         | 1.23%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.23%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.23%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.23%   |
| Intel SSD 660P Series                                                            | 2         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.23%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.61%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.61%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.61%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.61%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.61%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.61%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.61%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.61%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 0.61%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.61%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.61%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.61%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                            | 1         | 0.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.61%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1         | 0.61%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.61%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.61%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 60.13%  |
| NVMe | 43        | 27.22%  |
| IDE  | 11        | 6.96%   |
| RAID | 9         | 5.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 111       | 84.73%  |
| AMD    | 20        | 15.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 3.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 3.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 3.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 2.29%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 2.29%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 2.29%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 2.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.29%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.53%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.53%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 1.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.53%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.53%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 1.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.53%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.53%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.53%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.53%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 1.53%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.53%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.53%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 1.53%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.76%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.76%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.76%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.76%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.76%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.76%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.76%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.76%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.76%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.76%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.76%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.76%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.76%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 0.76%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.76%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.76%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.76%   |
| Intel Core i5-9400H CPU @ 2.50GHz             | 1         | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.76%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 0.76%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.76%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.76%   |
| Intel Core i5-2557M CPU @ 1.70GHz             | 1         | 0.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 42        | 32.06%  |
| Intel Core i5           | 33        | 25.19%  |
| Intel Core 2 Duo        | 11        | 8.4%    |
| Intel Core i3           | 9         | 6.87%   |
| Intel Celeron           | 6         | 4.58%   |
| AMD Ryzen 5             | 5         | 3.82%   |
| Intel Pentium           | 4         | 3.05%   |
| AMD Ryzen 7             | 4         | 3.05%   |
| Other                   | 3         | 2.29%   |
| AMD Ryzen 3             | 3         | 2.29%   |
| AMD Ryzen 9             | 2         | 1.53%   |
| Intel Pentium Silver    | 1         | 0.76%   |
| Intel Pentium Dual      | 1         | 0.76%   |
| Intel Core 2            | 1         | 0.76%   |
| AMD Turion II Dual-Core | 1         | 0.76%   |
| AMD Turion II           | 1         | 0.76%   |
| AMD E1                  | 1         | 0.76%   |
| AMD E                   | 1         | 0.76%   |
| AMD Athlon Neo          | 1         | 0.76%   |
| AMD A8                  | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 51.15%  |
| 4      | 50        | 38.17%  |
| 6      | 8         | 6.11%   |
| 8      | 5         | 3.82%   |
| 1      | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 131       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 101       | 77.1%   |
| 1      | 30        | 22.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 95.45%  |
| Unknown        | 6         | 4.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 16.3%   |
| 0x206a7    | 11        | 8.15%   |
| 0x806ec    | 9         | 6.67%   |
| 0x306a9    | 9         | 6.67%   |
| 0x40651    | 7         | 5.19%   |
| 0x306c3    | 7         | 5.19%   |
| 0x20655    | 5         | 3.7%    |
| 0x08108102 | 5         | 3.7%    |
| 0x906ea    | 4         | 2.96%   |
| 0x806ea    | 4         | 2.96%   |
| 0x6fd      | 4         | 2.96%   |
| 0x906e9    | 3         | 2.22%   |
| 0x806c1    | 3         | 2.22%   |
| 0x406e3    | 3         | 2.22%   |
| 0x306d4    | 3         | 2.22%   |
| 0x30678    | 3         | 2.22%   |
| 0x106e5    | 3         | 2.22%   |
| 0x1067a    | 3         | 2.22%   |
| 0x10676    | 3         | 2.22%   |
| 0x906ed    | 2         | 1.48%   |
| 0x706e5    | 2         | 1.48%   |
| 0x506c9    | 2         | 1.48%   |
| 0x20652    | 2         | 1.48%   |
| 0x0810100b | 2         | 1.48%   |
| 0xa0660    | 1         | 0.74%   |
| 0xa0652    | 1         | 0.74%   |
| 0x806eb    | 1         | 0.74%   |
| 0x706a1    | 1         | 0.74%   |
| 0x6fb      | 1         | 0.74%   |
| 0x406c4    | 1         | 0.74%   |
| 0x0a50000c | 1         | 0.74%   |
| 0x08608103 | 1         | 0.74%   |
| 0x08608102 | 1         | 0.74%   |
| 0x08600106 | 1         | 0.74%   |
| 0x0700010f | 1         | 0.74%   |
| 0x06001119 | 1         | 0.74%   |
| 0x05000119 | 1         | 0.74%   |
| 0x010000c8 | 1         | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 20.61%  |
| Haswell       | 15        | 11.45%  |
| SandyBridge   | 12        | 9.16%   |
| IvyBridge     | 10        | 7.63%   |
| Westmere      | 7         | 5.34%   |
| Penryn        | 7         | 5.34%   |
| Core          | 6         | 4.58%   |
| Zen+          | 5         | 3.82%   |
| Broadwell     | 5         | 3.82%   |
| Silvermont    | 4         | 3.05%   |
| TigerLake     | 3         | 2.29%   |
| Skylake       | 3         | 2.29%   |
| Nehalem       | 3         | 2.29%   |
| IceLake       | 3         | 2.29%   |
| Unknown       | 3         | 2.29%   |
| Zen 3         | 2         | 1.53%   |
| Zen 2         | 2         | 1.53%   |
| Zen           | 2         | 1.53%   |
| K10           | 2         | 1.53%   |
| Goldmont plus | 2         | 1.53%   |
| Goldmont      | 2         | 1.53%   |
| CometLake     | 2         | 1.53%   |
| Piledriver    | 1         | 0.76%   |
| K8 Hammer     | 1         | 0.76%   |
| Jaguar        | 1         | 0.76%   |
| Bobcat        | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 93        | 53.76%  |
| AMD                              | 43        | 24.86%  |
| Nvidia                           | 36        | 20.81%  |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 9         | 5.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 9         | 5.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 8         | 4.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 3.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 3.93%   |
| Intel UHD Graphics 620                                                                | 5         | 2.81%   |
| Intel HD Graphics 5500                                                                | 5         | 2.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 5         | 2.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 2.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 2.81%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 2.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 2.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 2.25%   |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 2.25%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 1.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 1.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.69%   |
| AMD Lucienne                                                                          | 3         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 1.12%   |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 1.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 1.12%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 1.12%   |
| Intel HD Graphics 630                                                                 | 2         | 1.12%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 2         | 1.12%   |
| AMD Renoir                                                                            | 2         | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 2         | 1.12%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 2         | 1.12%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                               | 2         | 1.12%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 1.12%   |
| AMD Cezanne                                                                           | 2         | 1.12%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                     | 1         | 0.56%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.56%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 0.56%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.56%   |
| Nvidia GT215GLM [Quadro FX 1800M]                                                     | 1         | 0.56%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 0.56%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 0.56%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                          | 1         | 0.56%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 1         | 0.56%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.56%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 1         | 0.56%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.56%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.56%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 0.56%   |
| Nvidia GK107M [GeForce GT 650M]                                                       | 1         | 0.56%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 0.56%   |
| Nvidia GK104GLM [Quadro K3100M]                                                       | 1         | 0.56%   |
| Nvidia GF119M [GeForce GT 520M]                                                       | 1         | 0.56%   |
| Nvidia GF106M [GeForce GTX 460M]                                                      | 1         | 0.56%   |
| Nvidia GF104GLM [Quadro 3000M]                                                        | 1         | 0.56%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                              | 1         | 0.56%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 1         | 0.56%   |
| Nvidia G96CM [GeForce GT 220M]                                                        | 1         | 0.56%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                             | 1         | 0.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 41.22%  |
| Intel + Nvidia | 25        | 19.08%  |
| 1 x AMD        | 25        | 19.08%  |
| Intel + AMD    | 14        | 10.69%  |
| 1 x Nvidia     | 8         | 6.11%   |
| AMD + Nvidia   | 3         | 2.29%   |
| 2 x AMD        | 1         | 0.76%   |
| 1 x SiS        | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 110       | 83.33%  |
| Proprietary | 19        | 14.39%  |
| Unknown     | 3         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 55.88%  |
| 1.01-2.0   | 24        | 17.65%  |
| 0.51-1.0   | 12        | 8.82%   |
| 0.01-0.5   | 11        | 8.09%   |
| 3.01-4.0   | 9         | 6.62%   |
| 5.01-6.0   | 2         | 1.47%   |
| 7.01-8.0   | 1         | 0.74%   |
| 2.01-3.0   | 1         | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 25.16%  |
| Samsung Electronics     | 17        | 10.97%  |
| LG Display              | 17        | 10.97%  |
| Chimei Innolux          | 15        | 9.68%   |
| BOE                     | 15        | 9.68%   |
| Dell                    | 10        | 6.45%   |
| Lenovo                  | 9         | 5.81%   |
| Chi Mei Optoelectronics | 6         | 3.87%   |
| Sharp                   | 3         | 1.94%   |
| AOC                     | 3         | 1.94%   |
| LG Philips              | 2         | 1.29%   |
| Goldstar                | 2         | 1.29%   |
| CSO                     | 2         | 1.29%   |
| Unknown (XXX)           | 1         | 0.65%   |
| Unknown                 | 1         | 0.65%   |
| TMX                     | 1         | 0.65%   |
| Sony                    | 1         | 0.65%   |
| PANDA                   | 1         | 0.65%   |
| NEC Computers           | 1         | 0.65%   |
| LGD                     | 1         | 0.65%   |
| InfoVision              | 1         | 0.65%   |
| IBM                     | 1         | 0.65%   |
| Hewlett-Packard         | 1         | 0.65%   |
| HannStar                | 1         | 0.65%   |
| Gericom                 | 1         | 0.65%   |
| CPT                     | 1         | 0.65%   |
| BenQ                    | 1         | 0.65%   |
| ASUSTek Computer        | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 4.4%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 1.89%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 1.89%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 1.26%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 2         | 1.26%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 1.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.26%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 1.26%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 1.26%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 1.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.63%   |
| Unknown (XXX) M22EI4 XXX076E 1680x1050 474x296mm 22.0-inch                | 1         | 0.63%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 1         | 0.63%   |
| Sony TV SNYAA01 1360x768                                                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 1         | 0.63%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                   | 1         | 0.63%   |
| Sharp LCD Monitor SHP1450 3840x2160 350x190mm 15.7-inch                   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch      | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch      | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM02B5 1920x1200 518x324mm 24.1-inch      | 1         | 0.63%   |
| Samsung Electronics S27D390 SAM0B66 1920x1080 598x336mm 27.0-inch         | 1         | 0.63%   |
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch         | 1         | 0.63%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3448 1920x1200 367x230mm 17.1-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3251 1366x768 344x194mm 15.5-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch     | 1         | 0.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 1         | 0.63%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.63%   |
| NEC Computers EA234WMi NEC691E 1920x1080 509x286mm 23.0-inch              | 1         | 0.63%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.63%   |
| LG Philips LCD Monitor LPL0AA8 1440x900 331x207mm 15.4-inch               | 1         | 0.63%   |
| LG Philips LCD Monitor LPL0A01 1440x900 367x230mm 17.1-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD061C 1920x1080 294x165mm 13.3-inch              | 1         | 0.63%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 1         | 0.63%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch              | 1         | 0.63%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 1         | 0.63%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch              | 1         | 0.63%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch              | 1         | 0.63%   |
| LG Display LCD Monitor LGD03D2 1366x768 309x174mm 14.0-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch               | 1         | 0.63%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch               | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 46.15%  |
| 1366x768 (WXGA)    | 27        | 18.88%  |
| 1600x900 (HD+)     | 16        | 11.19%  |
| 2560x1440 (QHD)    | 5         | 3.5%    |
| 1920x1200 (WUXGA)  | 5         | 3.5%    |
| 1680x1050 (WSXGA+) | 5         | 3.5%    |
| 3840x2160 (4K)     | 4         | 2.8%    |
| 3440x1440          | 4         | 2.8%    |
| 1440x900 (WXGA+)   | 4         | 2.8%    |
| 1280x800 (WXGA)    | 2         | 1.4%    |
| 2560x1600          | 1         | 0.7%    |
| 2288x1287          | 1         | 0.7%    |
| 2048x1152          | 1         | 0.7%    |
| 1400x1050          | 1         | 0.7%    |
| 1280x1024 (SXGA)   | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 67        | 42.68%  |
| 17      | 22        | 14.01%  |
| 14      | 14        | 8.92%   |
| 13      | 11        | 7.01%   |
| 24      | 9         | 5.73%   |
| 27      | 5         | 3.18%   |
| 23      | 5         | 3.18%   |
| 34      | 4         | 2.55%   |
| 21      | 4         | 2.55%   |
| 22      | 3         | 1.91%   |
| 12      | 3         | 1.91%   |
| 54      | 2         | 1.27%   |
| 18      | 2         | 1.27%   |
| 142     | 1         | 0.64%   |
| 39      | 1         | 0.64%   |
| 33      | 1         | 0.64%   |
| 19      | 1         | 0.64%   |
| 16      | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 85        | 55.19%  |
| 351-400        | 24        | 15.58%  |
| 501-600        | 17        | 11.04%  |
| 201-300        | 10        | 6.49%   |
| 401-500        | 8         | 5.19%   |
| 701-800        | 5         | 3.25%   |
| 1001-1500      | 2         | 1.3%    |
| More than 2000 | 1         | 0.65%   |
| 801-900        | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 82.48%  |
| 16/10   | 16        | 11.68%  |
| 21/9    | 4         | 2.92%   |
| 5/4     | 1         | 0.73%   |
| 4/3     | 1         | 0.73%   |
| 1.00    | 1         | 0.73%   |
| Unknown | 1         | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 66        | 42.31%  |
| 121-130        | 20        | 12.82%  |
| 81-90          | 18        | 11.54%  |
| 201-250        | 16        | 10.26%  |
| 71-80          | 7         | 4.49%   |
| 351-500        | 5         | 3.21%   |
| 301-350        | 5         | 3.21%   |
| More than 1000 | 3         | 1.92%   |
| 61-70          | 3         | 1.92%   |
| 251-300        | 3         | 1.92%   |
| 151-200        | 2         | 1.28%   |
| 141-150        | 2         | 1.28%   |
| 131-140        | 2         | 1.28%   |
| 111-120        | 1         | 0.64%   |
| 501-1000       | 1         | 0.64%   |
| 91-100         | 1         | 0.64%   |
| Unknown        | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 63        | 41.18%  |
| 101-120       | 46        | 30.07%  |
| 51-100        | 29        | 18.95%  |
| 161-240       | 7         | 4.58%   |
| More than 240 | 4         | 2.61%   |
| 1-50          | 3         | 1.96%   |
| Unknown       | 1         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 106       | 77.37%  |
| 2     | 26        | 18.98%  |
| 3     | 3         | 2.19%   |
| 0     | 2         | 1.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 73        | 35.27%  |
| Realtek Semiconductor             | 66        | 31.88%  |
| Qualcomm Atheros                  | 30        | 14.49%  |
| Broadcom                          | 13        | 6.28%   |
| Ralink                            | 3         | 1.45%   |
| Huawei Technologies               | 3         | 1.45%   |
| Sierra Wireless                   | 2         | 0.97%   |
| Samsung Electronics               | 2         | 0.97%   |
| Marvell Technology Group          | 2         | 0.97%   |
| Hewlett-Packard                   | 2         | 0.97%   |
| Broadcom Limited                  | 2         | 0.97%   |
| ASUSTek Computer                  | 2         | 0.97%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.48%   |
| Ralink Technology                 | 1         | 0.48%   |
| MEDIATEK                          | 1         | 0.48%   |
| Lenovo                            | 1         | 0.48%   |
| JMicron Technology                | 1         | 0.48%   |
| Ericsson Business Mobile Networks | 1         | 0.48%   |
| ASIX Electronics                  | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 44        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 3.79%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.03%   |
| Intel Wireless 7260                                                     | 7         | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                                    | 5         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.52%   |
| Intel Wireless 7265                                                     | 4         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 1.14%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                    | 3         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 1.14%   |
| Huawei MAR-LX1A                                                         | 3         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.76%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                 | 2         | 0.76%   |
| Intel Wireless 8260                                                     | 2         | 0.76%   |
| Intel Wireless 3165                                                     | 2         | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.76%   |
| Intel Ethernet Connection (10) I219-V                                   | 2         | 0.76%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.76%   |
| Intel 82562GT 10/100 Network Connection                                 | 2         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.38%   |
| Sierra Wireless MC8305 Modem                                            | 1         | 0.38%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.38%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.38%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.38%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.38%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 50.72%  |
| Qualcomm Atheros      | 26        | 18.84%  |
| Realtek Semiconductor | 20        | 14.49%  |
| Broadcom              | 10        | 7.25%   |
| Ralink                | 3         | 2.17%   |
| Sierra Wireless       | 2         | 1.45%   |
| Broadcom Limited      | 2         | 1.45%   |
| ASUSTek Computer      | 2         | 1.45%   |
| Ralink Technology     | 1         | 0.72%   |
| MEDIATEK              | 1         | 0.72%   |
| Hewlett-Packard       | 1         | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 9         | 6.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 8         | 5.8%    |
| Intel Wireless 7260                                                                   | 7         | 5.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 7         | 5.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 3.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 3.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 5         | 3.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 4         | 2.9%    |
| Intel Wireless 7265                                                                   | 4         | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 4         | 2.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 2.17%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.17%   |
| Intel Wi-Fi 6 AX201                                                                   | 3         | 2.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                                        | 3         | 2.17%   |
| Intel Centrino Advanced-N 6200                                                        | 3         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.17%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 3         | 2.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 1.45%   |
| Intel Wireless 8260                                                                   | 2         | 1.45%   |
| Intel Wireless 3165                                                                   | 2         | 1.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 2         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 2         | 1.45%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.45%   |
| Sierra Wireless MC8305 Modem                                                          | 1         | 0.72%   |
| Sierra Wireless EM7345 4G LTE                                                         | 1         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.72%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.72%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.72%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                                   | 1         | 0.72%   |
| Intel Wireless-AC 9260                                                                | 1         | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 0.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.72%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 1         | 0.72%   |
| HP lt4112 Gobi 4G Module Network Device                                               | 1         | 0.72%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 0.72%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                  | 1         | 0.72%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 1         | 0.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 0.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 1         | 0.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 0.72%   |
| Broadcom BCM4311 802.11a/b/g                                                          | 1         | 0.72%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                                   | 1         | 0.72%   |
| ASUS 802.11n WLAN Adapter                                                             | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 60        | 48.39%  |
| Intel                            | 40        | 32.26%  |
| Qualcomm Atheros                 | 9         | 7.26%   |
| Broadcom                         | 4         | 3.23%   |
| Huawei Technologies              | 3         | 2.42%   |
| Samsung Electronics              | 2         | 1.61%   |
| Marvell Technology Group         | 2         | 1.61%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |
| Lenovo                           | 1         | 0.81%   |
| JMicron Technology               | 1         | 0.81%   |
| ASIX Electronics                 | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 35.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 9.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 8.06%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 4.03%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 2.42%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.42%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 2.42%   |
| Huawei MAR-LX1A                                                   | 3         | 2.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.61%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.61%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.61%   |
| Intel 82562GT 10/100 Network Connection                           | 2         | 1.61%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.81%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.81%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.81%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.81%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.81%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.81%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.81%   |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 52.19%  |
| Ethernet | 118       | 47.01%  |
| Modem    | 2         | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 73.91%  |
| Ethernet | 36        | 26.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 112       | 84.85%  |
| 1     | 20        | 15.15%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 99.24%  |
| Yes  | 1         | 0.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 44.04%  |
| Broadcom                        | 12        | 11.01%  |
| Realtek Semiconductor           | 11        | 10.09%  |
| Qualcomm Atheros Communications | 11        | 10.09%  |
| IMC Networks                    | 10        | 9.17%   |
| Hewlett-Packard                 | 5         | 4.59%   |
| Lite-On Technology              | 3         | 2.75%   |
| Ralink                          | 2         | 1.83%   |
| Cambridge Silicon Radio         | 2         | 1.83%   |
| ASUSTek Computer                | 2         | 1.83%   |
| Ralink Technology               | 1         | 0.92%   |
| Foxconn / Hon Hai               | 1         | 0.92%   |
| Chicony Electronics             | 1         | 0.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 14.68%  |
| Intel AX201 Bluetooth                               | 11        | 10.09%  |
| Intel AX200 Bluetooth                               | 9         | 8.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 6.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.67%   |
| Realtek Bluetooth Radio                             | 4         | 3.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 3.67%   |
| IMC Networks Bluetooth Radio                        | 4         | 3.67%   |
| IMC Networks Bluetooth Device                       | 3         | 2.75%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.83%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.83%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.83%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.83%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.83%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.92%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.92%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.92%   |
| Lite-On Bluetooth Device                            | 1         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.92%   |
| Intel AX210 Bluetooth                               | 1         | 0.92%   |
| IMC Networks Bluetooth                              | 1         | 0.92%   |
| Foxconn / Hon Hai BT                                | 1         | 0.92%   |
| Chicony Bluetooth Radio                             | 1         | 0.92%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.92%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.92%   |
| Broadcom BCM20702A0                                 | 1         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 110       | 68.32%  |
| AMD                              | 27        | 16.77%  |
| Nvidia                           | 17        | 10.56%  |
| Texas Instruments                | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] | 1         | 0.62%   |
| Logitech                         | 1         | 0.62%   |
| Lenovo                           | 1         | 0.62%   |
| JMTek                            | 1         | 0.62%   |
| Hewlett-Packard                  | 1         | 0.62%   |
| C-Media Electronics              | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 5.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 5.1%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 4.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 4.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.57%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 3.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 3.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.55%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.53%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.53%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.53%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 1.53%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.02%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.02%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.51%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.51%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.51%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 0.51%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.51%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.51%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.51%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.51%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.51%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.51%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.51%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.51%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 0.51%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 26        | 28.57%  |
| Samsung Electronics | 22        | 24.18%  |
| Micron Technology   | 11        | 12.09%  |
| Kingston            | 7         | 7.69%   |
| Crucial             | 7         | 7.69%   |
| Unknown             | 5         | 5.49%   |
| Elpida              | 4         | 4.4%    |
| Nanya Technology    | 3         | 3.3%    |
| Ramaxel Technology  | 2         | 2.2%    |
| A-DATA Technology   | 2         | 2.2%    |
| Qimonda             | 1         | 1.1%    |
| Patriot             | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 3.03%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 3.03%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.02%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 2.02%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 2.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.02%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 2         | 2.02%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.02%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s         | 2         | 2.02%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s       | 2         | 2.02%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s    | 2         | 2.02%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                    | 1         | 1.01%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 1         | 1.01%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.01%   |
| Unknown RAM Module 2048MB SODIMM DRAM                        | 1         | 1.01%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.01%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 1.01%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 1.01%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s              | 1         | 1.01%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.01%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 1         | 1.01%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 1.01%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2133MT/s                | 1         | 1.01%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s             | 1         | 1.01%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1024MB SODIMM DDR 667MT/s      | 1         | 1.01%   |
| SK Hynix RAM HYMP325S64AMP8-Y5 2048MB SODIMM DDR 667MT/s     | 1         | 1.01%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR 667MT/s      | 1         | 1.01%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.01%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.01%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.01%   |
| SK Hynix RAM HMT112S6BFR6C-H9 1GB SODIMM DDR3 1333MT/s       | 1         | 1.01%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 1.01%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.01%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 1         | 1.01%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.01%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 1         | 1.01%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 1.01%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 1.01%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 1.01%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 1.01%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s                 | 1         | 1.01%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s              | 1         | 1.01%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.01%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s        | 1         | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.01%   |
| Samsung RAM M471B5273BH1-CH9 4GB SODIMM 1333MT/s             | 1         | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.01%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 1.01%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.01%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.01%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.01%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.01%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s      | 1         | 1.01%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 1.01%   |
| Qimonda RAM 64T128021HDL3SB 1GB SODIMM DDR2 667MT/s          | 1         | 1.01%   |
| Patriot RAM PSD38G16002S 8GB SODIMM DDR3 1600MT/s            | 1         | 1.01%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s         | 1         | 1.01%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 31        | 42.47%  |
| DDR3   | 30        | 41.1%   |
| DDR2   | 5         | 6.85%   |
| SDRAM  | 2         | 2.74%   |
| LPDDR4 | 2         | 2.74%   |
| LPDDR3 | 2         | 2.74%   |
| DRAM   | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 91.89%  |
| Row Of Chips | 5         | 6.76%   |
| Chip         | 1         | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 32.47%  |
| 4096  | 24        | 31.17%  |
| 16384 | 15        | 19.48%  |
| 2048  | 9         | 11.69%  |
| 1024  | 3         | 3.9%    |
| 32768 | 1         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 22        | 27.16%  |
| 2667    | 20        | 24.69%  |
| 1334    | 7         | 8.64%   |
| 3200    | 6         | 7.41%   |
| 2400    | 5         | 6.17%   |
| 2133    | 4         | 4.94%   |
| 1333    | 4         | 4.94%   |
| 667     | 3         | 3.7%    |
| 4267    | 2         | 2.47%   |
| 4199    | 2         | 2.47%   |
| Unknown | 2         | 2.47%   |
| 1867    | 1         | 1.23%   |
| 1067    | 1         | 1.23%   |
| 975     | 1         | 1.23%   |
| 800     | 1         | 1.23%   |

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
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 34.82%  |
| IMC Networks                           | 13        | 11.61%  |
| Quanta                                 | 9         | 8.04%   |
| Realtek Semiconductor                  | 8         | 7.14%   |
| Sunplus Innovation Technology          | 6         | 5.36%   |
| Microdia                               | 6         | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 5.36%   |
| Acer                                   | 6         | 5.36%   |
| Lite-On Technology                     | 5         | 4.46%   |
| Lenovo                                 | 3         | 2.68%   |
| Suyin                                  | 2         | 1.79%   |
| Primax Electronics                     | 2         | 1.79%   |
| Generalplus Technology                 | 2         | 1.79%   |
| Syntek                                 | 1         | 0.89%   |
| Samsung Electronics                    | 1         | 0.89%   |
| Ricoh                                  | 1         | 0.89%   |
| Logitech                               | 1         | 0.89%   |
| Apple                                  | 1         | 0.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 7.96%   |
| Microdia Integrated_Webcam_HD                               | 6         | 5.31%   |
| IMC Networks Integrated Camera                              | 5         | 4.42%   |
| Acer Integrated Camera                                      | 4         | 3.54%   |
| Lite-On HP HD Camera                                        | 3         | 2.65%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 3         | 2.65%   |
| Chicony HP HD Webcam                                        | 3         | 2.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 3         | 2.65%   |
| Sunplus HP HD Webcam [Fixed]                                | 2         | 1.77%   |
| Sunplus HD WebCam                                           | 2         | 1.77%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.77%   |
| Realtek Asus laptop camera                                  | 2         | 1.77%   |
| Quanta HP Webcam                                            | 2         | 1.77%   |
| Quanta HP TrueVision HD Camera                              | 2         | 1.77%   |
| Quanta HP HD Camera                                         | 2         | 1.77%   |
| Primax HP HD Webcam [Fixed]                                 | 2         | 1.77%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 1.77%   |
| IMC Networks Integrated Webcam                              | 2         | 1.77%   |
| Generalplus CAMERA - UVC                                    | 2         | 1.77%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.77%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.77%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.77%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.77%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.77%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.77%   |
| Chicony HP Webcam                                           | 2         | 1.77%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.88%   |
| Suyin HP Truevision HD                                      | 1         | 0.88%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.88%   |
| Sunplus Integrated Camera                                   | 1         | 0.88%   |
| Sunplus HP Universal Camera                                 | 1         | 0.88%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 0.88%   |
| Ricoh Integrated Webcam                                     | 1         | 0.88%   |
| Realtek USB2.0-Camera                                       | 1         | 0.88%   |
| Realtek USB Camera                                          | 1         | 0.88%   |
| Realtek Integrated Webcam                                   | 1         | 0.88%   |
| Realtek Integrated Camera                                   | 1         | 0.88%   |
| Quanta VGA WebCam                                           | 1         | 0.88%   |
| Quanta HP TrueVision HD Webcam                              | 1         | 0.88%   |
| Quanta HD Webcam                                            | 1         | 0.88%   |
| Logitech Webcam C310                                        | 1         | 0.88%   |
| Lite-On Integrated Camera                                   | 1         | 0.88%   |
| Lite-On HP HD Webcam                                        | 1         | 0.88%   |
| Lenovo UVC Camera                                           | 1         | 0.88%   |
| IMC Networks USB2.0 VGA Webcam                              | 1         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 0.88%   |
| IMC Networks EasyCamera                                     | 1         | 0.88%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 0.88%   |
| Chicony USB 2.0 Camera                                      | 1         | 0.88%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 0.88%   |
| Chicony HP Truevision HD camera                             | 1         | 0.88%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed]            | 1         | 0.88%   |
| Chicony HP HD Webcam [Fixed]                                | 1         | 0.88%   |
| Chicony HP HD Camera                                        | 1         | 0.88%   |
| Chicony HD WebCam (Asus N-series)                           | 1         | 0.88%   |
| Chicony HD WebCam                                           | 1         | 0.88%   |
| Chicony HD User Facing                                      | 1         | 0.88%   |
| Chicony FJ Camera                                           | 1         | 0.88%   |
| Chicony CNF8243 Webcam                                      | 1         | 0.88%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 14        | 36.84%  |
| Validity Sensors           | 12        | 31.58%  |
| AuthenTec                  | 4         | 10.53%  |
| Upek                       | 3         | 7.89%   |
| Shenzhen Goodix Technology | 3         | 7.89%   |
| STMicroelectronics         | 1         | 2.63%   |
| Elan Microelectronics      | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 13.16%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 13.16%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 7.89%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 7.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 7.89%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 5.26%   |
| AuthenTec AES2810                                          | 2         | 5.26%   |
| Unknown                                                    | 2         | 5.26%   |
| Validity Sensors VFS491                                    | 1         | 2.63%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.63%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.63%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.63%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.63%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.63%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 2.63%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 58.33%  |
| Broadcom    | 3         | 25%     |
| Upek        | 1         | 8.33%   |
| O2 Micro    | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 7         | 58.33%  |
| Broadcom 58200                                             | 2         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 73        | 55.3%   |
| 1     | 39        | 29.55%  |
| 2     | 19        | 14.39%  |
| 3     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 48.72%  |
| Chipcard                 | 12        | 15.38%  |
| Graphics card            | 9         | 11.54%  |
| Net/wireless             | 5         | 6.41%   |
| Multimedia controller    | 4         | 5.13%   |
| Communication controller | 3         | 3.85%   |
| Bluetooth                | 3         | 3.85%   |
| Storage                  | 2         | 2.56%   |
| Net/ethernet             | 1         | 1.28%   |
| Camera                   | 1         | 1.28%   |

