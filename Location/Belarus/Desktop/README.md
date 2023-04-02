Linux in Belarus - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

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

Total: 526

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-A75-UD4H                 | [e5433e75fb](https://linux-hardware.org/?probe=e5433e75fb) | Mar 29, 2023 |
| Gigabyte      | B85M-D3V-A                  | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| MSI           | X79A-GD45 Plus              | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| Iskratel, ... | IN6011AX                    | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | [8023b22765](https://linux-hardware.org/?probe=8023b22765) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | [5e9cf8fb44](https://linux-hardware.org/?probe=5e9cf8fb44) | Mar 22, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [7d8950b25b](https://linux-hardware.org/?probe=7d8950b25b) | Mar 21, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [c58012d73d](https://linux-hardware.org/?probe=c58012d73d) | Mar 21, 2023 |
| Intel         | JSL MRD                     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| ASUSTek       | PRIME H410M-E               | [9cd0a2ea25](https://linux-hardware.org/?probe=9cd0a2ea25) | Mar 01, 2023 |
| ASRock        | H61M-DGS R2.0               | [630c0e41b1](https://linux-hardware.org/?probe=630c0e41b1) | Feb 25, 2023 |
| Partner       | S1-J1900                    | [0dd4327553](https://linux-hardware.org/?probe=0dd4327553) | Feb 19, 2023 |
| ASUSTek       | P5GD1 PRO                   | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| Intel         | SKYBAY                      | [7f8e95e496](https://linux-hardware.org/?probe=7f8e95e496) | Feb 02, 2023 |
| Intel         | SKYBAY                      | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASUSTek       | Z170M-E D3                  | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| Gigabyte      | 990XA-UD3                   | [43e346516e](https://linux-hardware.org/?probe=43e346516e) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| Gigabyte      | 990XA-UD3                   | [d23fb14f2e](https://linux-hardware.org/?probe=d23fb14f2e) | Jan 07, 2023 |
| MSI           | MS-7519                     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Unknown       | Intel X79                   | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [6f0f984312](https://linux-hardware.org/?probe=6f0f984312) | Dec 29, 2022 |
| ASRock        | Brazos                      | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| ASRock        | X570 Pro4                   | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| Intel         | SHARKBAY                    | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| Gigabyte      | GA-M56S-S3                  | [077f863ca3](https://linux-hardware.org/?probe=077f863ca3) | Dec 15, 2022 |
| Biostar       | A520MH                      | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Biostar       | A520MH                      | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Gigabyte      | M61SME-S2                   | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ad6dc99c8a](https://linux-hardware.org/?probe=ad6dc99c8a) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| Gigabyte      | Z68XP-UD3                   | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | [6e83c73646](https://linux-hardware.org/?probe=6e83c73646) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [25e3064dd2](https://linux-hardware.org/?probe=25e3064dd2) | Sep 29, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | EP45-DS3L                   | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | GA-M56S-S3                  | [8b8ba6c7f9](https://linux-hardware.org/?probe=8b8ba6c7f9) | Sep 05, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| Gigabyte      | M61SME-S2                   | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| ASRock        | N68-VGS3 FX                 | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| Huanan        | X99-BD4 V1.33               | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| Gigabyte      | Z270-Gaming K3              | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Gigabyte      | Z390 UD                     | [1ee2492f24](https://linux-hardware.org/?probe=1ee2492f24) | Jul 23, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [2d2a17094e](https://linux-hardware.org/?probe=2d2a17094e) | Jul 23, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [7142849ed0](https://linux-hardware.org/?probe=7142849ed0) | Jul 17, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| ASRock        | B550M-HDV                   | [3f20ad2267](https://linux-hardware.org/?probe=3f20ad2267) | Jul 11, 2022 |
| ASRock        | B550M-HDV                   | [b7adccb849](https://linux-hardware.org/?probe=b7adccb849) | Jul 09, 2022 |
| Gigabyte      | Z68AP-D3                    | [26cbd669e4](https://linux-hardware.org/?probe=26cbd669e4) | Jul 05, 2022 |
| ASRock        | H61M-HVGS                   | [2b31833bfe](https://linux-hardware.org/?probe=2b31833bfe) | Jul 02, 2022 |
| Biostar       | TA790GX 128M                | [c7021e0b8c](https://linux-hardware.org/?probe=c7021e0b8c) | Jul 01, 2022 |
| Gigabyte      | B85M-D3V-A                  | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Gigabyte      | B450M S2H                   | [6dd752fab5](https://linux-hardware.org/?probe=6dd752fab5) | Jun 23, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASRock        | B450 Gaming K4              | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| ECS           | IC780M-A2                   | [135f0a4328](https://linux-hardware.org/?probe=135f0a4328) | May 21, 2022 |
| MSI           | MS-7309                     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Gigabyte      | Z87P-D3                     | [2a916e3eb5](https://linux-hardware.org/?probe=2a916e3eb5) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| ASRock        | N68-GS4 FX                  | [8926d96550](https://linux-hardware.org/?probe=8926d96550) | May 07, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| Gigabyte      | Z270P-D3-CF                 | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | B75M-D2V                    | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASRock        | B450M Pro4-F                | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASRock        | B560M Steel Legend          | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Gigabyte      | Z87P-D3                     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| Gigabyte      | Z270-Gaming K3              | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| Gigabyte      | EP45-DS3L                   | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| Gigabyte      | B450M S2H V2                | [a8e8d6dd5e](https://linux-hardware.org/?probe=a8e8d6dd5e) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| ASRock        | FM2A55M-VG3                 | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | [517ef58b87](https://linux-hardware.org/?probe=517ef58b87) | Mar 11, 2022 |
| ASUSTek       | M5A78L-M LX3                | [55ce4f1460](https://linux-hardware.org/?probe=55ce4f1460) | Mar 11, 2022 |
| ASUSTek       | P8H61-M LE                  | [a6fc7b9f12](https://linux-hardware.org/?probe=a6fc7b9f12) | Mar 10, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | [800bc08dbd](https://linux-hardware.org/?probe=800bc08dbd) | Mar 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| ASRock        | N68C-GS FX                  | [bdba90c583](https://linux-hardware.org/?probe=bdba90c583) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASRock        | N68-VS3 UCC                 | [39389b9ddf](https://linux-hardware.org/?probe=39389b9ddf) | Feb 26, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| ASRock        | N68-VGS3 FX                 | [601f46e5a4](https://linux-hardware.org/?probe=601f46e5a4) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [a32dfea06a](https://linux-hardware.org/?probe=a32dfea06a) | Feb 07, 2022 |
| ASRock        | B560M Steel Legend          | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Gigabyte      | M61SME-S2                   | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| MSI           | B150M PRO-VH                | [583a1313c8](https://linux-hardware.org/?probe=583a1313c8) | Feb 01, 2022 |
| ASUSTek       | M2A74-AM SE                 | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | H87M-E35                    | [0cfdd2b772](https://linux-hardware.org/?probe=0cfdd2b772) | Jan 28, 2022 |
| Kllisre       | X79 V1.2                    | [84bd3ccecf](https://linux-hardware.org/?probe=84bd3ccecf) | Jan 21, 2022 |
| MSI           | B150M PRO-VH                | [de22d479a4](https://linux-hardware.org/?probe=de22d479a4) | Jan 20, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [291a3e234b](https://linux-hardware.org/?probe=291a3e234b) | Jan 14, 2022 |
| Kllisre       | X79 V1.2                    | [239547a419](https://linux-hardware.org/?probe=239547a419) | Jan 09, 2022 |
| ASRock        | N68-VS3 UCC                 | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| ASRock        | AB350M Pro4                 | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Gigabyte      | EP45-DS3L                   | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| MSI           | MS-7922                     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| Gigabyte      | M61SME-S2                   | [be9f6cac13](https://linux-hardware.org/?probe=be9f6cac13) | Dec 20, 2021 |
| MSI           | A320M PRO-VD PLUS           | [7f0853c09e](https://linux-hardware.org/?probe=7f0853c09e) | Dec 19, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Gigabyte      | B450M S2H                   | [a2e037ba0e](https://linux-hardware.org/?probe=a2e037ba0e) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [f9ada169fd](https://linux-hardware.org/?probe=f9ada169fd) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [7d39826b60](https://linux-hardware.org/?probe=7d39826b60) | Dec 09, 2021 |
| Gigabyte      | B85M-D3V-A                  | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| ASUSTek       | P5B-VM SE                   | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [039315b907](https://linux-hardware.org/?probe=039315b907) | Nov 10, 2021 |
| Gigabyte      | EP45-DS3L                   | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| ASRock        | B365 Pro4                   | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| Gigabyte      | EP45-DS3L                   | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| ASRock        | N68C-S UCC                  | [0f23350175](https://linux-hardware.org/?probe=0f23350175) | Oct 27, 2021 |
| ASRock        | B365 Pro4                   | [8061e7314a](https://linux-hardware.org/?probe=8061e7314a) | Oct 23, 2021 |
| ASRock        | J3455B-ITX                  | [9fd17a6579](https://linux-hardware.org/?probe=9fd17a6579) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | [9b4b3c9f77](https://linux-hardware.org/?probe=9b4b3c9f77) | Oct 09, 2021 |
| Gigabyte      | Z87P-D3                     | [b99c6d022e](https://linux-hardware.org/?probe=b99c6d022e) | Oct 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | [0d6bbd5c75](https://linux-hardware.org/?probe=0d6bbd5c75) | Oct 05, 2021 |
| Intel         | H61M-S1                     | [ba0b4c102b](https://linux-hardware.org/?probe=ba0b4c102b) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Gigabyte      | EP45-DS3L                   | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASRock        | N68C-GS FX                  | [bea6762fb6](https://linux-hardware.org/?probe=bea6762fb6) | Sep 26, 2021 |
| Gigabyte      | Z87P-D3                     | [80b6244981](https://linux-hardware.org/?probe=80b6244981) | Sep 21, 2021 |
| ASRock        | B365 Pro4                   | [bc0974da01](https://linux-hardware.org/?probe=bc0974da01) | Sep 19, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [f8bb575441](https://linux-hardware.org/?probe=f8bb575441) | Sep 16, 2021 |
| Gigabyte      | B85M-D3V-A                  | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| Biostar       | A960D+V3                    | [f65660cdbe](https://linux-hardware.org/?probe=f65660cdbe) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| Intel         | H61M-S1                     | [46407e3bfe](https://linux-hardware.org/?probe=46407e3bfe) | Aug 24, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [240d31631f](https://linux-hardware.org/?probe=240d31631f) | Aug 19, 2021 |
| Biostar       | Hi-Fi A75S3                 | [f75bdb68fa](https://linux-hardware.org/?probe=f75bdb68fa) | Aug 14, 2021 |
| Acer          | Veriton N4660G              | [7ee989172f](https://linux-hardware.org/?probe=7ee989172f) | Aug 13, 2021 |
| ASRock        | B550M-ITX/ac                | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| ASUSTek       | M5A78L-M LX3                | [11621d5877](https://linux-hardware.org/?probe=11621d5877) | Aug 07, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| Gigabyte      | H87-HD3                     | [92c5d52e50](https://linux-hardware.org/?probe=92c5d52e50) | Jul 27, 2021 |
| MSI           | H110M PRO-D                 | [960c966e4b](https://linux-hardware.org/?probe=960c966e4b) | Jul 24, 2021 |
| Gigabyte      | H57M-USB3                   | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| ASRock        | B365 Pro4                   | [af87c52a43](https://linux-hardware.org/?probe=af87c52a43) | Jul 20, 2021 |
| MSI           | MS-7369                     | [caf783ce91](https://linux-hardware.org/?probe=caf783ce91) | Jul 10, 2021 |
| ASRock        | B550M-ITX/ac                | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| Intel         | H61M-S1                     | [10ef09acce](https://linux-hardware.org/?probe=10ef09acce) | Jun 28, 2021 |
| ASUSTek       | A68HM-K                     | [b34ddd69c9](https://linux-hardware.org/?probe=b34ddd69c9) | Jun 21, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [7fe08a233a](https://linux-hardware.org/?probe=7fe08a233a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | [f6436bedb8](https://linux-hardware.org/?probe=f6436bedb8) | Jun 16, 2021 |
| Gigabyte      | EP45-DS3L                   | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [0c5e09b00c](https://linux-hardware.org/?probe=0c5e09b00c) | Jun 14, 2021 |
| MSI           | MS-7369                     | [9852368309](https://linux-hardware.org/?probe=9852368309) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| Gigabyte      | B85M-D3V-A                  | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| ASRock        | N68-VS3 UCC                 | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| ASRock        | N68-VS3 UCC                 | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ECS           | Livermore8                  | [fba5a0dbb7](https://linux-hardware.org/?probe=fba5a0dbb7) | May 12, 2021 |
| ASRock        | N68-VS3 FX                  | [3eefcf4b58](https://linux-hardware.org/?probe=3eefcf4b58) | May 11, 2021 |
| Biostar       | H81MLC                      | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [ec9321bd41](https://linux-hardware.org/?probe=ec9321bd41) | May 08, 2021 |
| Dell          | 0CRH6C A02                  | [69cbbfec14](https://linux-hardware.org/?probe=69cbbfec14) | Apr 30, 2021 |
| Intel         | H61M-S1                     | [36129cbfda](https://linux-hardware.org/?probe=36129cbfda) | Apr 25, 2021 |
| ASUSTek       | PRIME B360M-A               | [309d8603b2](https://linux-hardware.org/?probe=309d8603b2) | Apr 15, 2021 |
| ASUSTek       | PRIME B360M-A               | [d945be0db8](https://linux-hardware.org/?probe=d945be0db8) | Apr 15, 2021 |
| ASUSTek       | P5Q-EM                      | [d6c3e7cb89](https://linux-hardware.org/?probe=d6c3e7cb89) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| HP            | 304Ah                       | [66228ce4df](https://linux-hardware.org/?probe=66228ce4df) | Apr 09, 2021 |
| HP            | 304Ah                       | [5d8e8d559a](https://linux-hardware.org/?probe=5d8e8d559a) | Apr 09, 2021 |
| ASRock        | B450M Pro4                  | [1dc07212db](https://linux-hardware.org/?probe=1dc07212db) | Mar 28, 2021 |
| Gigabyte      | GA-770T-D3L                 | [eeeb3a5b5d](https://linux-hardware.org/?probe=eeeb3a5b5d) | Mar 27, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [35964432d7](https://linux-hardware.org/?probe=35964432d7) | Mar 26, 2021 |
| ASUSTek       | P8H77-V LE                  | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| Gigabyte      | G31M-ES2L                   | [d2e63cfaa6](https://linux-hardware.org/?probe=d2e63cfaa6) | Mar 22, 2021 |
| ASUSTek       | P5B                         | [a24c9c6d6a](https://linux-hardware.org/?probe=a24c9c6d6a) | Mar 22, 2021 |
| Gigabyte      | P55A-UD3                    | [c947af2b99](https://linux-hardware.org/?probe=c947af2b99) | Mar 21, 2021 |
| ASRock        | Z390 Taichi Ultimate        | [3e2336037f](https://linux-hardware.org/?probe=3e2336037f) | Mar 20, 2021 |
| ASUSTek       | M5A97 PRO                   | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [e688898ed8](https://linux-hardware.org/?probe=e688898ed8) | Mar 17, 2021 |
| ASUSTek       | P5Q-E                       | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| Gigabyte      | H87-HD3                     | [658c4e0d17](https://linux-hardware.org/?probe=658c4e0d17) | Mar 17, 2021 |
| Gigabyte      | Z270-Gaming K3              | [1b6cfd046e](https://linux-hardware.org/?probe=1b6cfd046e) | Mar 17, 2021 |
| ASRock        | 990FX Extreme4              | [d1536bcdfa](https://linux-hardware.org/?probe=d1536bcdfa) | Mar 17, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [72f398fcff](https://linux-hardware.org/?probe=72f398fcff) | Mar 11, 2021 |
| MSI           | MS-7250                     | [bd7bbadaad](https://linux-hardware.org/?probe=bd7bbadaad) | Feb 23, 2021 |
| Gigabyte      | 970A-UD3P                   | [77748ba0e4](https://linux-hardware.org/?probe=77748ba0e4) | Feb 22, 2021 |
| ASRock        | N68C-GS FX                  | [8d2b36f7c1](https://linux-hardware.org/?probe=8d2b36f7c1) | Feb 20, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [80cea1a03a](https://linux-hardware.org/?probe=80cea1a03a) | Feb 19, 2021 |
| Gigabyte      | G41M-Combo                  | [c500f1eff8](https://linux-hardware.org/?probe=c500f1eff8) | Feb 14, 2021 |
| Gigabyte      | H77-DS3H                    | [76e29e229d](https://linux-hardware.org/?probe=76e29e229d) | Feb 13, 2021 |
| MSI           | Z370 KRAIT GAMING           | [6262cc3afd](https://linux-hardware.org/?probe=6262cc3afd) | Feb 13, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [6969353956](https://linux-hardware.org/?probe=6969353956) | Feb 13, 2021 |
| ASUSTek       | P8H77-V                     | [bbc60c2820](https://linux-hardware.org/?probe=bbc60c2820) | Feb 13, 2021 |
| Gigabyte      | H77-DS3H                    | [02fd7c81f6](https://linux-hardware.org/?probe=02fd7c81f6) | Feb 11, 2021 |
| Gigabyte      | G41M-Combo                  | [d9218caa35](https://linux-hardware.org/?probe=d9218caa35) | Feb 05, 2021 |
| Gigabyte      | G41M-Combo                  | [f4611ac89e](https://linux-hardware.org/?probe=f4611ac89e) | Feb 04, 2021 |
| Gigabyte      | G41M-Combo                  | [6f78493e97](https://linux-hardware.org/?probe=6f78493e97) | Jan 29, 2021 |
| MSI           | 760GM-P33                   | [f7dbe6391b](https://linux-hardware.org/?probe=f7dbe6391b) | Jan 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | [14022d5350](https://linux-hardware.org/?probe=14022d5350) | Jan 20, 2021 |
| ASUSTek       | P5Q-E                       | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| MSI           | 760GM-P33                   | [9af10be990](https://linux-hardware.org/?probe=9af10be990) | Jan 03, 2021 |
| Gigabyte      | GA-MA770T-UD3               | [1b0941ddec](https://linux-hardware.org/?probe=1b0941ddec) | Dec 26, 2020 |
| VIA Techno... | P4M266A-8235                | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| Gigabyte      | P35-S3G                     | [be95d225fe](https://linux-hardware.org/?probe=be95d225fe) | Dec 22, 2020 |
| Gigabyte      | GA-MA770-DS3                | [cf0c42c323](https://linux-hardware.org/?probe=cf0c42c323) | Dec 18, 2020 |
| Gigabyte      | GA-MA770-DS3                | [43c86b0f1e](https://linux-hardware.org/?probe=43c86b0f1e) | Dec 18, 2020 |
| ASUSTek       | Z170I PRO GAMING            | [5e1b23e45c](https://linux-hardware.org/?probe=5e1b23e45c) | Dec 14, 2020 |
| Gigabyte      | H81M-S2H                    | [c6b4560c3e](https://linux-hardware.org/?probe=c6b4560c3e) | Dec 07, 2020 |
| ASUSTek       | P5K WS                      | [89a2e1b515](https://linux-hardware.org/?probe=89a2e1b515) | Nov 28, 2020 |
| Gigabyte      | H81M-S2H                    | [05314304a4](https://linux-hardware.org/?probe=05314304a4) | Nov 19, 2020 |
| ASUSTek       | V200IB                      | [910d5a3bfd](https://linux-hardware.org/?probe=910d5a3bfd) | Nov 19, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [6abee99a84](https://linux-hardware.org/?probe=6abee99a84) | Nov 18, 2020 |
| Gigabyte      | H81M-S2H                    | [72f585d3fd](https://linux-hardware.org/?probe=72f585d3fd) | Nov 18, 2020 |
| Gigabyte      | GA-M56S-S3                  | [f8de57d305](https://linux-hardware.org/?probe=f8de57d305) | Nov 16, 2020 |
| Gigabyte      | 945GZM-S2                   | [4eefad2a8b](https://linux-hardware.org/?probe=4eefad2a8b) | Nov 13, 2020 |
| ASRock        | 970 Pro3 R2.0               | [df41815a21](https://linux-hardware.org/?probe=df41815a21) | Nov 06, 2020 |
| ASRock        | Z370M Pro4                  | [85e45a95e0](https://linux-hardware.org/?probe=85e45a95e0) | Nov 04, 2020 |
| MSI           | 760GM-P33                   | [c611e5bbe5](https://linux-hardware.org/?probe=c611e5bbe5) | Oct 26, 2020 |
| Gigabyte      | 970A-DS3P                   | [7ae3293c6d](https://linux-hardware.org/?probe=7ae3293c6d) | Oct 26, 2020 |
| ASUSTek       | H81M-E                      | [e149fb7dc2](https://linux-hardware.org/?probe=e149fb7dc2) | Oct 23, 2020 |
| Gigabyte      | Z390 D                      | [1610651aa5](https://linux-hardware.org/?probe=1610651aa5) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [2fa1f3048b](https://linux-hardware.org/?probe=2fa1f3048b) | Oct 13, 2020 |
| Gigabyte      | Z68XP-UD3                   | [ee0649427b](https://linux-hardware.org/?probe=ee0649427b) | Oct 12, 2020 |
| MSI           | MS-7250                     | [c4ef765de1](https://linux-hardware.org/?probe=c4ef765de1) | Oct 10, 2020 |
| ASUSTek       | H61M-K                      | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| ASRock        | 970 Pro3                    | [c4459c622c](https://linux-hardware.org/?probe=c4459c622c) | Sep 27, 2020 |
| ASRock        | H81 Pro BTC R2.0            | [271a7bcbeb](https://linux-hardware.org/?probe=271a7bcbeb) | Sep 19, 2020 |
| ASUSTek       | P5KPL-C                     | [6812da21fd](https://linux-hardware.org/?probe=6812da21fd) | Sep 15, 2020 |
| HP            | 304Ah                       | [5acd57b9db](https://linux-hardware.org/?probe=5acd57b9db) | Sep 15, 2020 |
| ASUSTek       | P9X79                       | [52a401fb4d](https://linux-hardware.org/?probe=52a401fb4d) | Sep 08, 2020 |
| ASRock        | FM2A75M-DGS                 | [a827ce3df1](https://linux-hardware.org/?probe=a827ce3df1) | Sep 02, 2020 |
| ASRock        | H61M-HVS                    | [4052b1ff8b](https://linux-hardware.org/?probe=4052b1ff8b) | Aug 25, 2020 |
| ASRock        | 990FX Extreme4              | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | P9X79                       | [16796af2c3](https://linux-hardware.org/?probe=16796af2c3) | Aug 06, 2020 |
| ASUSTek       | P8H61 R2.0                  | [b9790bef81](https://linux-hardware.org/?probe=b9790bef81) | Aug 02, 2020 |
| ASRock        | Z77 Extreme4-M              | [8d5ce15006](https://linux-hardware.org/?probe=8d5ce15006) | Jul 29, 2020 |
| ASUSTek       | P9X79                       | [b5e0ef963b](https://linux-hardware.org/?probe=b5e0ef963b) | Jul 26, 2020 |
| ASUSTek       | P9X79                       | [def2e542ec](https://linux-hardware.org/?probe=def2e542ec) | Jul 25, 2020 |
| ASUSTek       | P8H77-V                     | [ad01a90f9c](https://linux-hardware.org/?probe=ad01a90f9c) | Jul 23, 2020 |
| Gigabyte      | 970A-DS3P                   | [791afa1495](https://linux-hardware.org/?probe=791afa1495) | Jul 16, 2020 |
| ASUSTek       | H170 PRO GAMING             | [220af5d9fe](https://linux-hardware.org/?probe=220af5d9fe) | Jul 15, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [986a151279](https://linux-hardware.org/?probe=986a151279) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [322ef5e555](https://linux-hardware.org/?probe=322ef5e555) | Jul 06, 2020 |
| ASRock        | 960GC-GS FX                 | [0e0fe8368c](https://linux-hardware.org/?probe=0e0fe8368c) | Jun 30, 2020 |
| ASRock        | N68C-GS FX                  | [b439507f1a](https://linux-hardware.org/?probe=b439507f1a) | Jun 25, 2020 |
| ASRock        | N68C-GS FX                  | [4d3573e05d](https://linux-hardware.org/?probe=4d3573e05d) | Jun 18, 2020 |
| ASRock        | N68C-GS FX                  | [31fcf823d4](https://linux-hardware.org/?probe=31fcf823d4) | Jun 18, 2020 |
| ASRock        | N68C-GS4 FX                 | [53eafad041](https://linux-hardware.org/?probe=53eafad041) | Jun 02, 2020 |
| ASRock        | P43D1600Twins-1394          | [9eb0959f24](https://linux-hardware.org/?probe=9eb0959f24) | May 25, 2020 |
| ASRock        | H81M-VG4 R2.0               | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [670301a3f3](https://linux-hardware.org/?probe=670301a3f3) | May 25, 2020 |
| ASRock        | FM2A68M-DG3+                | [f27378d43f](https://linux-hardware.org/?probe=f27378d43f) | May 25, 2020 |
| Gigabyte      | P55M-UD4                    | [cb5f5644c1](https://linux-hardware.org/?probe=cb5f5644c1) | May 21, 2020 |
| ASRock        | Z77 Extreme3                | [46d7fb23b0](https://linux-hardware.org/?probe=46d7fb23b0) | May 21, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [9b3d9029ea](https://linux-hardware.org/?probe=9b3d9029ea) | May 03, 2020 |
| ASUSTek       | P7P55D-E LX                 | [828fc9a788](https://linux-hardware.org/?probe=828fc9a788) | Apr 26, 2020 |
| MSI           | MS-7250                     | [9aafa9594b](https://linux-hardware.org/?probe=9aafa9594b) | Apr 18, 2020 |
| MSI           | MS-7507                     | [f33b052aed](https://linux-hardware.org/?probe=f33b052aed) | Apr 14, 2020 |
| Gigabyte      | D525TUD                     | [16b44a22f0](https://linux-hardware.org/?probe=16b44a22f0) | Apr 13, 2020 |
| ASUSTek       | P7H55D-M PRO                | [b0522c8711](https://linux-hardware.org/?probe=b0522c8711) | Mar 19, 2020 |
| Gigabyte      | GA-970A-DS3                 | [a451b0d94d](https://linux-hardware.org/?probe=a451b0d94d) | Mar 07, 2020 |
| Gigabyte      | GA-780T-D3L                 | [18f5afd1ed](https://linux-hardware.org/?probe=18f5afd1ed) | Feb 28, 2020 |
| ASRock        | 960GC-GS FX                 | [88acae56fa](https://linux-hardware.org/?probe=88acae56fa) | Feb 28, 2020 |
| ASRock        | H110M-HDV R3.0              | [fe39ad1f52](https://linux-hardware.org/?probe=fe39ad1f52) | Feb 13, 2020 |
| ASUSTek       | M5A97 PRO                   | [38709aec79](https://linux-hardware.org/?probe=38709aec79) | Jan 25, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [659e0d3a62](https://linux-hardware.org/?probe=659e0d3a62) | Jan 24, 2020 |
| ASUSTek       | P8H61-M LX3                 | [1c4e4c5a2d](https://linux-hardware.org/?probe=1c4e4c5a2d) | Jan 24, 2020 |
| ASRock        | H310CM-HDV                  | [3e955a15c1](https://linux-hardware.org/?probe=3e955a15c1) | Jan 22, 2020 |
| ASRock        | H310CM-HDV                  | [adc392749f](https://linux-hardware.org/?probe=adc392749f) | Jan 22, 2020 |
| ASRock        | Z77 Extreme4-M              | [14e729f5aa](https://linux-hardware.org/?probe=14e729f5aa) | Jan 13, 2020 |
| Gigabyte      | 970A-DS3P                   | [87e363c1ed](https://linux-hardware.org/?probe=87e363c1ed) | Jan 10, 2020 |
| Biostar       | NF520-A2 TE                 | [cd41d93f63](https://linux-hardware.org/?probe=cd41d93f63) | Jan 06, 2020 |
| Gigabyte      | H67MA-USB3-B3               | [a3ff07d84b](https://linux-hardware.org/?probe=a3ff07d84b) | Jan 04, 2020 |
| Acer          | Veriton N4660G              | [9afe548805](https://linux-hardware.org/?probe=9afe548805) | Dec 29, 2019 |
| ASRock        | Z390 Phantom Gaming SLI     | [02221c3f6b](https://linux-hardware.org/?probe=02221c3f6b) | Dec 19, 2019 |
| ASRock        | Z390 Phantom Gaming SLI     | [60a1413416](https://linux-hardware.org/?probe=60a1413416) | Dec 19, 2019 |
| Gigabyte      | H310M S2H x.x               | [2575da9f64](https://linux-hardware.org/?probe=2575da9f64) | Dec 18, 2019 |
| ASRock        | B450M-HDV R4.0              | [3d3f27a3f9](https://linux-hardware.org/?probe=3d3f27a3f9) | Dec 04, 2019 |
| ASRock        | B450M-HDV R4.0              | [559d304205](https://linux-hardware.org/?probe=559d304205) | Dec 04, 2019 |
| ASRock        | 960GM-VGS3 FX               | [08835d6477](https://linux-hardware.org/?probe=08835d6477) | Dec 03, 2019 |
| ASRock        | G31M-S                      | [674951f8cf](https://linux-hardware.org/?probe=674951f8cf) | Dec 03, 2019 |
| MSI           | 760GM-P33                   | [b14d738927](https://linux-hardware.org/?probe=b14d738927) | Dec 02, 2019 |
| Gigabyte      | Z390 AORUS PRO-CF           | [15a59f41a1](https://linux-hardware.org/?probe=15a59f41a1) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | [a7b57eaddf](https://linux-hardware.org/?probe=a7b57eaddf) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | [bcb59e4acf](https://linux-hardware.org/?probe=bcb59e4acf) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | [67a75ff7c4](https://linux-hardware.org/?probe=67a75ff7c4) | Nov 26, 2019 |
| ASUSTek       | V200IB                      | [61357ecaed](https://linux-hardware.org/?probe=61357ecaed) | Nov 26, 2019 |
| ASRock        | H61M-VG4                    | [787fad97da](https://linux-hardware.org/?probe=787fad97da) | Nov 26, 2019 |
| Gigabyte      | B450M S2H                   | [1fc5f15d9a](https://linux-hardware.org/?probe=1fc5f15d9a) | Nov 23, 2019 |
| Gigabyte      | B450M S2H                   | [4de9a6fdb0](https://linux-hardware.org/?probe=4de9a6fdb0) | Nov 23, 2019 |
| ASRock        | G31M-S                      | [9a60dcb468](https://linux-hardware.org/?probe=9a60dcb468) | Nov 22, 2019 |
| ASUSTek       | M2N-X                       | [69669b5bdd](https://linux-hardware.org/?probe=69669b5bdd) | Nov 18, 2019 |
| ASRock        | G31M-S                      | [26c06abca8](https://linux-hardware.org/?probe=26c06abca8) | Nov 11, 2019 |
| MSI           | Z77A-G41                    | [213b4c47a0](https://linux-hardware.org/?probe=213b4c47a0) | Nov 04, 2019 |
| Gigabyte      | F2A88X-D3H                  | [a1b106dc08](https://linux-hardware.org/?probe=a1b106dc08) | Nov 04, 2019 |
| Gigabyte      | GA-MA770T-UD3               | [c43d48a7e8](https://linux-hardware.org/?probe=c43d48a7e8) | Oct 31, 2019 |
| ASRock        | H61M-HVGS                   | [04ed30a83f](https://linux-hardware.org/?probe=04ed30a83f) | Oct 30, 2019 |
| ASRock        | G31M-S                      | [e78c58b8f7](https://linux-hardware.org/?probe=e78c58b8f7) | Oct 30, 2019 |
| Gigabyte      | GA-MA770T-UD3               | [9f3722cd19](https://linux-hardware.org/?probe=9f3722cd19) | Oct 27, 2019 |
| Gigabyte      | GA-880GM-UD2H               | [a5ccfe7480](https://linux-hardware.org/?probe=a5ccfe7480) | Oct 23, 2019 |
| Gigabyte      | GA-MA74GM-S2H               | [c9b3479419](https://linux-hardware.org/?probe=c9b3479419) | Oct 05, 2019 |
| ASRock        | H97 Anniversary             | [f9f19da3b0](https://linux-hardware.org/?probe=f9f19da3b0) | Sep 29, 2019 |
| ASRock        | H97 Anniversary             | [48920360b7](https://linux-hardware.org/?probe=48920360b7) | Sep 29, 2019 |
| ASUSTek       | PRIME A320M-K               | [ab7f8a4bba](https://linux-hardware.org/?probe=ab7f8a4bba) | Sep 25, 2019 |
| Gigabyte      | C847N                       | [dd58b111d2](https://linux-hardware.org/?probe=dd58b111d2) | Sep 20, 2019 |
| ASRock        | H61M-HVGS                   | [8fba013175](https://linux-hardware.org/?probe=8fba013175) | Sep 15, 2019 |
| Gigabyte      | 970A-DS3P                   | [65edd09a48](https://linux-hardware.org/?probe=65edd09a48) | Sep 02, 2019 |
| ASRock        | N68C-GS FX                  | [df9e40504c](https://linux-hardware.org/?probe=df9e40504c) | Sep 02, 2019 |
| ASRock        | N68C-GS FX                  | [df615d6ccf](https://linux-hardware.org/?probe=df615d6ccf) | Aug 29, 2019 |
| MSI           | 0A90                        | [64c0075cf9](https://linux-hardware.org/?probe=64c0075cf9) | Aug 18, 2019 |
| ASRock        | H61M-HVGS                   | [48c5aab4be](https://linux-hardware.org/?probe=48c5aab4be) | Aug 17, 2019 |
| Gigabyte      | 970A-DS3P                   | [ce436327da](https://linux-hardware.org/?probe=ce436327da) | Aug 16, 2019 |
| Gigabyte      | 945PL-S3                    | [f235798c9e](https://linux-hardware.org/?probe=f235798c9e) | Aug 09, 2019 |
| Intel         | SKYBAY                      | [cdcd16d077](https://linux-hardware.org/?probe=cdcd16d077) | Aug 09, 2019 |
| Gigabyte      | H81M-S2H                    | [98c28c0cba](https://linux-hardware.org/?probe=98c28c0cba) | Aug 08, 2019 |
| Gigabyte      | 970A-DS3P                   | [5fe6d47df5](https://linux-hardware.org/?probe=5fe6d47df5) | Aug 05, 2019 |
| HP            | 0A54h                       | [ff6685ad25](https://linux-hardware.org/?probe=ff6685ad25) | Aug 02, 2019 |
| ASUSTek       | P8H67-M PRO                 | [66a5ea0be5](https://linux-hardware.org/?probe=66a5ea0be5) | Jul 26, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | [34021fd6bd](https://linux-hardware.org/?probe=34021fd6bd) | Jul 25, 2019 |
| ASRock        | H310M-HDV                   | [39c0fbe126](https://linux-hardware.org/?probe=39c0fbe126) | Jul 25, 2019 |
| ASUSTek       | PRIME A320M-K               | [03b0e6294f](https://linux-hardware.org/?probe=03b0e6294f) | Jul 19, 2019 |
| ASUSTek       | B150M-A                     | [b724162662](https://linux-hardware.org/?probe=b724162662) | Jul 10, 2019 |
| Gigabyte      | H310M S2H x.x               | [0c91aab0ff](https://linux-hardware.org/?probe=0c91aab0ff) | Jun 27, 2019 |
| Gigabyte      | Z68A-D3H-B3                 | [b147e4676b](https://linux-hardware.org/?probe=b147e4676b) | Jun 25, 2019 |
| ASRock        | 960GC-GS FX                 | [7c80bf6fda](https://linux-hardware.org/?probe=7c80bf6fda) | Jun 20, 2019 |
| MSI           | MS-7250                     | [005023ee9d](https://linux-hardware.org/?probe=005023ee9d) | Jun 19, 2019 |
| MSI           | MS-7250                     | [cd4ecc0b42](https://linux-hardware.org/?probe=cd4ecc0b42) | Jun 19, 2019 |
| Gigabyte      | 945PL-S3                    | [7b106b9427](https://linux-hardware.org/?probe=7b106b9427) | Jun 17, 2019 |
| Gigabyte      | P55M-UD4                    | [98980d3cde](https://linux-hardware.org/?probe=98980d3cde) | Jun 17, 2019 |
| Biostar       | A780L3L                     | [2de6892c13](https://linux-hardware.org/?probe=2de6892c13) | Jun 15, 2019 |
| MSI           | A320M PRO-VH PLUS           | [a3afa44f01](https://linux-hardware.org/?probe=a3afa44f01) | Jun 11, 2019 |
| Gigabyte      | F2A88X-D3H                  | [13b9b4e6e9](https://linux-hardware.org/?probe=13b9b4e6e9) | Jun 09, 2019 |
| Gigabyte      | GA-MA74GM-S2H               | [9c885eb562](https://linux-hardware.org/?probe=9c885eb562) | May 25, 2019 |
| ASRock        | N68C-GS FX                  | [becfb6b881](https://linux-hardware.org/?probe=becfb6b881) | May 14, 2019 |
| Jetway        | TI41M                       | [5c923195ab](https://linux-hardware.org/?probe=5c923195ab) | May 12, 2019 |
| Lenovo        | 3000                        | [de702ed343](https://linux-hardware.org/?probe=de702ed343) | May 10, 2019 |
| ASRock        | N68C-GS4 FX                 | [988dbccf88](https://linux-hardware.org/?probe=988dbccf88) | May 09, 2019 |
| ASUSTek       | WS X299 PRO                 | [b31f25bbb7](https://linux-hardware.org/?probe=b31f25bbb7) | May 07, 2019 |
| MSI           | Z97 GAMING 5                | [fd97593820](https://linux-hardware.org/?probe=fd97593820) | May 01, 2019 |
| Gigabyte      | PH67A-D3-B3                 | [d90cc4cbe3](https://linux-hardware.org/?probe=d90cc4cbe3) | Apr 27, 2019 |
| Lenovo        | 3000                        | [08b71be3a2](https://linux-hardware.org/?probe=08b71be3a2) | Apr 26, 2019 |
| MSI           | Z97 GAMING 5                | [f7e37a8a8d](https://linux-hardware.org/?probe=f7e37a8a8d) | Apr 23, 2019 |
| Gigabyte      | P35-DS3L                    | [626c138c66](https://linux-hardware.org/?probe=626c138c66) | Apr 22, 2019 |
| Gigabyte      | Z68P-DS3                    | [4a9dc9c551](https://linux-hardware.org/?probe=4a9dc9c551) | Apr 21, 2019 |
| Biostar       | TA75A+                      | [5bd842f25a](https://linux-hardware.org/?probe=5bd842f25a) | Apr 06, 2019 |
| Gigabyte      | 970A-DS3                    | [8ad8dd2388](https://linux-hardware.org/?probe=8ad8dd2388) | Apr 02, 2019 |
| Gigabyte      | M4HM87P-00                  | [831597ffda](https://linux-hardware.org/?probe=831597ffda) | Mar 31, 2019 |
| MSI           | H87M-E35                    | [a4408c4eea](https://linux-hardware.org/?probe=a4408c4eea) | Mar 29, 2019 |
| ASRock        | Z87 Pro4                    | [0fdbdd7257](https://linux-hardware.org/?probe=0fdbdd7257) | Mar 28, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | [18af0d2322](https://linux-hardware.org/?probe=18af0d2322) | Mar 26, 2019 |
| Gigabyte      | GA-MA74GM-S2H               | [29d403e18d](https://linux-hardware.org/?probe=29d403e18d) | Mar 15, 2019 |
| MSI           | MS-7369                     | [5824a23fe2](https://linux-hardware.org/?probe=5824a23fe2) | Mar 08, 2019 |
| ASRock        | 960GM-GS3 FX                | [48438c8714](https://linux-hardware.org/?probe=48438c8714) | Feb 14, 2019 |
| Gigabyte      | 970A-DS3P                   | [4c611c79d7](https://linux-hardware.org/?probe=4c611c79d7) | Feb 13, 2019 |
| Gigabyte      | 970A-DS3P                   | [cbe60f7c7a](https://linux-hardware.org/?probe=cbe60f7c7a) | Feb 13, 2019 |
| Biostar       | MCP6P3                      | [68bd47f661](https://linux-hardware.org/?probe=68bd47f661) | Feb 03, 2019 |
| MSI           | Z97-G43                     | [186dbb4515](https://linux-hardware.org/?probe=186dbb4515) | Feb 03, 2019 |
| Gigabyte      | 970A-DS3P                   | [f41b882a8e](https://linux-hardware.org/?probe=f41b882a8e) | Jan 19, 2019 |
| ASRock        | G31M-S                      | [e8737c8ac8](https://linux-hardware.org/?probe=e8737c8ac8) | Jan 17, 2019 |
| Gigabyte      | P67A-D3-B3                  | [e9c51ee187](https://linux-hardware.org/?probe=e9c51ee187) | Jan 13, 2019 |
| Biostar       | MCP6P3                      | [b324f9754a](https://linux-hardware.org/?probe=b324f9754a) | Jan 10, 2019 |
| MSI           | Z77A-G45 GAMING             | [a0f7438599](https://linux-hardware.org/?probe=a0f7438599) | Jan 01, 2019 |
| ASRock        | Z77 Extreme4-M              | [c65b222ea1](https://linux-hardware.org/?probe=c65b222ea1) | Dec 25, 2018 |
| MSI           | MS-7309                     | [a77abcc8cf](https://linux-hardware.org/?probe=a77abcc8cf) | Dec 22, 2018 |
| MSI           | Z77A-G45 GAMING             | [c0dd7b7123](https://linux-hardware.org/?probe=c0dd7b7123) | Dec 01, 2018 |
| Gigabyte      | GA-780T-D3L                 | [da78c40bba](https://linux-hardware.org/?probe=da78c40bba) | Nov 30, 2018 |
| Gigabyte      | GA-780T-D3L                 | [b41b61d2c4](https://linux-hardware.org/?probe=b41b61d2c4) | Nov 29, 2018 |
| Gigabyte      | GA-780T-D3L                 | [14a756e743](https://linux-hardware.org/?probe=14a756e743) | Nov 29, 2018 |
| ASUSTek       | P5K PRO                     | [a92cebea4d](https://linux-hardware.org/?probe=a92cebea4d) | Nov 28, 2018 |
| Intel         | SKYBAY                      | [00c8a206a0](https://linux-hardware.org/?probe=00c8a206a0) | Oct 19, 2018 |
| Gigabyte      | M61PME-S2                   | [c1bd028326](https://linux-hardware.org/?probe=c1bd028326) | Oct 17, 2018 |
| Gigabyte      | GA-880GM-UD2H               | [94ac1919d7](https://linux-hardware.org/?probe=94ac1919d7) | Sep 22, 2018 |
| ASRock        | H81M-DGS R2.0               | [392729da7e](https://linux-hardware.org/?probe=392729da7e) | Sep 21, 2018 |
| ASUSTek       | A68HM-K                     | [b1808c2eb4](https://linux-hardware.org/?probe=b1808c2eb4) | Sep 18, 2018 |
| ASRock        | N68-S3 UCC                  | [e2a67e2574](https://linux-hardware.org/?probe=e2a67e2574) | Sep 09, 2018 |
| Gigabyte      | GA-MA74GM-S2H               | [9e22b8f4c0](https://linux-hardware.org/?probe=9e22b8f4c0) | Sep 06, 2018 |
| ASUSTek       | P5B SE                      | [46ab71b84f](https://linux-hardware.org/?probe=46ab71b84f) | Sep 04, 2018 |
| Nvidia        | NF-MCP61                    | [92a93942ed](https://linux-hardware.org/?probe=92a93942ed) | Aug 27, 2018 |
| MSI           | MS-7922                     | [77fd2cc323](https://linux-hardware.org/?probe=77fd2cc323) | Aug 23, 2018 |
| ZOTAC         | NM10                        | [e9be5383cf](https://linux-hardware.org/?probe=e9be5383cf) | Aug 22, 2018 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [ac4484fb91](https://linux-hardware.org/?probe=ac4484fb91) | Aug 06, 2018 |
| ASRock        | N68C-S UCC                  | [b3239b74e2](https://linux-hardware.org/?probe=b3239b74e2) | Aug 06, 2018 |
| ASRock        | AB350 Gaming-ITX/ac         | [f0bef09470](https://linux-hardware.org/?probe=f0bef09470) | Jul 13, 2018 |
| Gigabyte      | 970A-DS3                    | [a8cb099c5a](https://linux-hardware.org/?probe=a8cb099c5a) | Jul 06, 2018 |
| MSI           | MS-7309                     | [85c343f098](https://linux-hardware.org/?probe=85c343f098) | Jun 20, 2018 |
| Gigabyte      | 970A-DS3P                   | [1558d7c30e](https://linux-hardware.org/?probe=1558d7c30e) | Jun 10, 2018 |
| ASRock        | N68C-GS FX                  | [a742697557](https://linux-hardware.org/?probe=a742697557) | May 28, 2018 |
| Gigabyte      | 970A-DS3P                   | [493526b0cd](https://linux-hardware.org/?probe=493526b0cd) | May 27, 2018 |
| ASRock        | N68C-GS FX                  | [6ba14be353](https://linux-hardware.org/?probe=6ba14be353) | May 18, 2018 |
| ASUSTek       | P5P800-MX                   | [f1ce220fd5](https://linux-hardware.org/?probe=f1ce220fd5) | May 15, 2018 |
| ASUSTek       | P5P800-MX                   | [060a56de61](https://linux-hardware.org/?probe=060a56de61) | May 15, 2018 |
| ASRock        | A780LM-S                    | [5b53dd6dd0](https://linux-hardware.org/?probe=5b53dd6dd0) | May 05, 2018 |
| Nvidia        | NF-MCP61                    | [65c435fd00](https://linux-hardware.org/?probe=65c435fd00) | Apr 29, 2018 |
| ASRock        | G31M-VS2                    | [37efe4e43f](https://linux-hardware.org/?probe=37efe4e43f) | Apr 28, 2018 |
| Gigabyte      | H110M-S2-CF                 | [f3c9a3eb76](https://linux-hardware.org/?probe=f3c9a3eb76) | Apr 24, 2018 |
| ASUSTek       | P8Z77-V PRO                 | [dff9b15427](https://linux-hardware.org/?probe=dff9b15427) | Apr 22, 2018 |
| MSI           | MS-7309 10                  | [71b8fc0632](https://linux-hardware.org/?probe=71b8fc0632) | Apr 16, 2018 |
| MSI           | MS-7309 10                  | [7b960f4558](https://linux-hardware.org/?probe=7b960f4558) | Apr 16, 2018 |
| ASUSTek       | VM60                        | [c123099e37](https://linux-hardware.org/?probe=c123099e37) | Apr 15, 2018 |
| ASUSTek       | VM60                        | [bd1d814d83](https://linux-hardware.org/?probe=bd1d814d83) | Apr 15, 2018 |
| ASRock        | A780LM-S                    | [aa1be7d4e9](https://linux-hardware.org/?probe=aa1be7d4e9) | Mar 25, 2018 |
| ASUSTek       | P8Z77-V LX2                 | [27e9317f47](https://linux-hardware.org/?probe=27e9317f47) | Mar 22, 2018 |
| Gigabyte      | GA-780T-D3L                 | [7190c0818e](https://linux-hardware.org/?probe=7190c0818e) | Mar 18, 2018 |
| Gigabyte      | GA-A75-D3H                  | [235900b4b2](https://linux-hardware.org/?probe=235900b4b2) | Mar 17, 2018 |
| Gigabyte      | P31-DS3L                    | [c1417adcb7](https://linux-hardware.org/?probe=c1417adcb7) | Feb 26, 2018 |
| Gigabyte      | B85M-HD3                    | [3202c90e49](https://linux-hardware.org/?probe=3202c90e49) | Feb 25, 2018 |
| ASUSTek       | P5B SE                      | [cda181fdbf](https://linux-hardware.org/?probe=cda181fdbf) | Feb 17, 2018 |
| ASRock        | N68-VS3 UCC                 | [ebdd218c0a](https://linux-hardware.org/?probe=ebdd218c0a) | Feb 17, 2018 |
| ASUSTek       | M2N-MX                      | [586a8fc1a0](https://linux-hardware.org/?probe=586a8fc1a0) | Feb 16, 2018 |
| Gigabyte      | GA-780T-D3L                 | [72636405d7](https://linux-hardware.org/?probe=72636405d7) | Feb 11, 2018 |
| ASUSTek       | P5B                         | [64a6603145](https://linux-hardware.org/?probe=64a6603145) | Feb 11, 2018 |
| ASUSTek       | A88XM-A                     | [3694e448ee](https://linux-hardware.org/?probe=3694e448ee) | Feb 09, 2018 |
| ASUSTek       | P5K PRO                     | [fb241733d7](https://linux-hardware.org/?probe=fb241733d7) | Feb 08, 2018 |
| ASUSTek       | P5W DH Deluxe               | [e4820de986](https://linux-hardware.org/?probe=e4820de986) | Feb 08, 2018 |
| MSI           | MS-7250                     | [00cf2d12a7](https://linux-hardware.org/?probe=00cf2d12a7) | Jan 29, 2018 |
| MSI           | MS-7250                     | [e7ad29832b](https://linux-hardware.org/?probe=e7ad29832b) | Jan 29, 2018 |
| MSI           | MS-7369                     | [67881bd907](https://linux-hardware.org/?probe=67881bd907) | Jan 27, 2018 |
| ASUSTek       | P4S800-MX SE                | [fa04955b88](https://linux-hardware.org/?probe=fa04955b88) | Jan 22, 2018 |
| ASRock        | FM2A55 Pro+                 | [5eeb1370c2](https://linux-hardware.org/?probe=5eeb1370c2) | Jan 17, 2018 |
| ASRock        | N68-VS3 UCC                 | [3880e14ae9](https://linux-hardware.org/?probe=3880e14ae9) | Jan 16, 2018 |
| Gigabyte      | M4HM87P-00                  | [518ffe426a](https://linux-hardware.org/?probe=518ffe426a) | Dec 31, 2017 |
| ASRock        | G31M-S                      | [6bf5a923b3](https://linux-hardware.org/?probe=6bf5a923b3) | Dec 20, 2017 |
| ASRock        | G31M-S                      | [57cbfce000](https://linux-hardware.org/?probe=57cbfce000) | Dec 20, 2017 |
| ASUSTek       | M2N-E                       | [7a7af75075](https://linux-hardware.org/?probe=7a7af75075) | Dec 19, 2017 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [855c603767](https://linux-hardware.org/?probe=855c603767) | Dec 17, 2017 |
| ASRock        | N68C-GS FX                  | [c88c80e415](https://linux-hardware.org/?probe=c88c80e415) | Dec 14, 2017 |
| ASRock        | Z97M Pro4                   | [beedba2b85](https://linux-hardware.org/?probe=beedba2b85) | Dec 13, 2017 |
| ASUSTek       | P4S800-MX SE                | [c34c626f63](https://linux-hardware.org/?probe=c34c626f63) | Dec 13, 2017 |
| Gigabyte      | H61M-USB3-B3                | [3547011cc9](https://linux-hardware.org/?probe=3547011cc9) | Dec 07, 2017 |
| Gigabyte      | GA-MA770-DS3                | [3aac9757b6](https://linux-hardware.org/?probe=3aac9757b6) | Dec 03, 2017 |
| MSI           | K9A2GM V3                   | [b340e7a1b4](https://linux-hardware.org/?probe=b340e7a1b4) | Nov 29, 2017 |
| ASRock        | Z77 Extreme4-M              | [9a96bd84af](https://linux-hardware.org/?probe=9a96bd84af) | Nov 28, 2017 |
| Gigabyte      | 945PL-S3                    | [28a334bdb8](https://linux-hardware.org/?probe=28a334bdb8) | Nov 21, 2017 |
| Gigabyte      | 945PL-S3                    | [82f58ad883](https://linux-hardware.org/?probe=82f58ad883) | Nov 16, 2017 |
| Gigabyte      | H81M-S2H                    | [eb798e5e53](https://linux-hardware.org/?probe=eb798e5e53) | Nov 15, 2017 |
| Biostar       | N520D-A2                    | [b130eb7077](https://linux-hardware.org/?probe=b130eb7077) | Nov 11, 2017 |
| ASUSTek       | M2N-VM DVI                  | [85f6c5411f](https://linux-hardware.org/?probe=85f6c5411f) | Nov 08, 2017 |
| ASUSTek       | M2N-VM DVI                  | [09112fec20](https://linux-hardware.org/?probe=09112fec20) | Nov 02, 2017 |
| ASUSTek       | SABERTOOTH Z77              | [fa20a27efd](https://linux-hardware.org/?probe=fa20a27efd) | Oct 17, 2017 |
| ASRock        | Z77 Extreme4-M              | [66a51f97dc](https://linux-hardware.org/?probe=66a51f97dc) | Oct 15, 2017 |
| ASUSTek       | M2N-VM DVI                  | [89e0964dc9](https://linux-hardware.org/?probe=89e0964dc9) | Oct 14, 2017 |
| Gigabyte      | GA-A75-D3H                  | [6d696fe86b](https://linux-hardware.org/?probe=6d696fe86b) | Sep 20, 2017 |
| MSI           | MS-7369                     | [70b368bd84](https://linux-hardware.org/?probe=70b368bd84) | Sep 12, 2017 |
| Gigabyte      | EP45-UD3R                   | [e9e5ce8e71](https://linux-hardware.org/?probe=e9e5ce8e71) | Sep 10, 2017 |
| ASRock        | A75M-HVS                    | [9500615990](https://linux-hardware.org/?probe=9500615990) | Sep 06, 2017 |
| Gigabyte      | H81M-S2H                    | [29cbcdc9d8](https://linux-hardware.org/?probe=29cbcdc9d8) | Sep 05, 2017 |
| ASRock        | H61M-VG3                    | [c9d4e962d5](https://linux-hardware.org/?probe=c9d4e962d5) | Aug 29, 2017 |
| Gigabyte      | 945PL-S3                    | [1d54471054](https://linux-hardware.org/?probe=1d54471054) | Aug 18, 2017 |
| ASRock        | H61M-VG4                    | [7eb620e199](https://linux-hardware.org/?probe=7eb620e199) | Aug 18, 2017 |
| Gigabyte      | H81M-S2H                    | [76e8046e3a](https://linux-hardware.org/?probe=76e8046e3a) | Aug 17, 2017 |
| MSI           | G41M-P28                    | [60a8e2650b](https://linux-hardware.org/?probe=60a8e2650b) | Aug 16, 2017 |
| MSI           | MS-7369                     | [5b8fc5f2a5](https://linux-hardware.org/?probe=5b8fc5f2a5) | Aug 16, 2017 |
| Gigabyte      | H81M-S2H                    | [4021bd50a2](https://linux-hardware.org/?probe=4021bd50a2) | Aug 14, 2017 |
| Gigabyte      | GA-78LMT-S2                 | [835629a8a7](https://linux-hardware.org/?probe=835629a8a7) | Aug 02, 2017 |
| MSI           | 880GMS-E35                  | [fb3a9b38ae](https://linux-hardware.org/?probe=fb3a9b38ae) | Jul 25, 2017 |
| Gigabyte      | 945PL-S3                    | [28f8ab3aa3](https://linux-hardware.org/?probe=28f8ab3aa3) | Jul 25, 2017 |
| Gigabyte      | G31M-S2L                    | [c40f9d969e](https://linux-hardware.org/?probe=c40f9d969e) | Jul 23, 2017 |
| Gigabyte      | G31M-S2L                    | [bb1624ea3a](https://linux-hardware.org/?probe=bb1624ea3a) | Jul 21, 2017 |
| ASUSTek       | M2N-E                       | [535b9a0e13](https://linux-hardware.org/?probe=535b9a0e13) | Jul 03, 2017 |
| ASUSTek       | H81M-K                      | [4081269972](https://linux-hardware.org/?probe=4081269972) | Jun 21, 2017 |
| Foxconn       | G41MXP/G41MXP-V             | [6ca14da0fa](https://linux-hardware.org/?probe=6ca14da0fa) | Jun 13, 2017 |
| ASUSTek       | B85M-G                      | [019ca7700b](https://linux-hardware.org/?probe=019ca7700b) | Jun 11, 2017 |
| ASUSTek       | A88XM-A                     | [d8164c7f9b](https://linux-hardware.org/?probe=d8164c7f9b) | Jun 11, 2017 |
| ASRock        | Z87 Pro4                    | [97b7d095b4](https://linux-hardware.org/?probe=97b7d095b4) | Jun 02, 2017 |
| ASUSTek       | F1A55-M LE R2.0             | [e8697ba8fa](https://linux-hardware.org/?probe=e8697ba8fa) | Jun 01, 2017 |
| ASUSTek       | A88XM-A                     | [eea79c39d3](https://linux-hardware.org/?probe=eea79c39d3) | May 24, 2017 |
| Gigabyte      | M68M-S2P                    | [8713e6047d](https://linux-hardware.org/?probe=8713e6047d) | May 20, 2017 |
| ASUSTek       | P8H77-V                     | [17efba7efa](https://linux-hardware.org/?probe=17efba7efa) | May 15, 2017 |
| MSI           | MS-7235                     | [d02a8f3ba9](https://linux-hardware.org/?probe=d02a8f3ba9) | May 14, 2017 |
| MSI           | MS-7235                     | [4960ca8e5b](https://linux-hardware.org/?probe=4960ca8e5b) | May 14, 2017 |
| ASRock        | H81M-VG4 R3.0               | [04edba406f](https://linux-hardware.org/?probe=04edba406f) | May 03, 2017 |
| MSI           | MS-7507                     | [949758a7bb](https://linux-hardware.org/?probe=949758a7bb) | May 02, 2017 |
| MSI           | MS-7507                     | [2ceaf8753e](https://linux-hardware.org/?probe=2ceaf8753e) | Apr 26, 2017 |
| Gigabyte      | GA-A75-D3H                  | [8b50649a40](https://linux-hardware.org/?probe=8b50649a40) | Apr 22, 2017 |
| Biostar       | TZ77B                       | [6933983fab](https://linux-hardware.org/?probe=6933983fab) | Apr 14, 2017 |
| ASUSTek       | M5A78L-M/USB3               | [a85e718859](https://linux-hardware.org/?probe=a85e718859) | Apr 11, 2017 |
| Gigabyte      | GA-A75-D3H                  | [3b7982d37e](https://linux-hardware.org/?probe=3b7982d37e) | Apr 08, 2017 |
| MSI           | 870-C45                     | [425f287926](https://linux-hardware.org/?probe=425f287926) | Apr 04, 2017 |
| ASRock        | Z77 Extreme4-M              | [b0529aa0d7](https://linux-hardware.org/?probe=b0529aa0d7) | Mar 28, 2017 |
| MSI           | MS-7369                     | [34d1480ef5](https://linux-hardware.org/?probe=34d1480ef5) | Mar 26, 2017 |
| ASUSTek       | H81M-K                      | [8f8055f6cd](https://linux-hardware.org/?probe=8f8055f6cd) | Mar 22, 2017 |
| MSI           | 0A90                        | [34768ffe2a](https://linux-hardware.org/?probe=34768ffe2a) | Mar 19, 2017 |
| ASUSTek       | P8H77-M LE                  | [e67693985e](https://linux-hardware.org/?probe=e67693985e) | Mar 19, 2017 |
| Gigabyte      | M68M-S2P                    | [e924c4feaf](https://linux-hardware.org/?probe=e924c4feaf) | Mar 10, 2017 |
| ASUSTek       | B85-PLUS                    | [50d7b843c4](https://linux-hardware.org/?probe=50d7b843c4) | Feb 22, 2017 |
| ASUSTek       | B85-PLUS                    | [349264c475](https://linux-hardware.org/?probe=349264c475) | Feb 22, 2017 |
| Gigabyte      | GA-78LMT-S2P                | [1e85560547](https://linux-hardware.org/?probe=1e85560547) | Feb 22, 2017 |
| ASUSTek       | M5A97 R2.0                  | [eccb2a2c63](https://linux-hardware.org/?probe=eccb2a2c63) | Feb 14, 2017 |
| MSI           | MS-7250                     | [0950917e81](https://linux-hardware.org/?probe=0950917e81) | Jan 20, 2017 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [37e989c6f3](https://linux-hardware.org/?probe=37e989c6f3) | Jan 18, 2017 |
| ECS           | GeForce7050M-M              | [2322d5cb22](https://linux-hardware.org/?probe=2322d5cb22) | Jan 17, 2017 |
| MSI           | G41M-P26                    | [2c92dfc348](https://linux-hardware.org/?probe=2c92dfc348) | Jan 05, 2017 |
| Gigabyte      | GA-MA74GM-S2                | [b73f9cc351](https://linux-hardware.org/?probe=b73f9cc351) | Dec 21, 2016 |
| ECS           | GeForce7050M-M              | [ea41b9c6cf](https://linux-hardware.org/?probe=ea41b9c6cf) | Dec 21, 2016 |
| EPoX Compu... | i915P DDR + DDR2: 5EDAI     | [bb2baf4caa](https://linux-hardware.org/?probe=bb2baf4caa) | Dec 11, 2016 |
| Gigabyte      | GA-MA74GM-S2H               | [5201188f4f](https://linux-hardware.org/?probe=5201188f4f) | Dec 09, 2016 |
| Gigabyte      | M68M-S2P                    | [a39dfe883b](https://linux-hardware.org/?probe=a39dfe883b) | Dec 05, 2016 |
| MSI           | Z77A-G45 GAMING             | [ef3b22aa83](https://linux-hardware.org/?probe=ef3b22aa83) | Nov 28, 2016 |
| Gigabyte      | Z87-HD3                     | [7e7a86540c](https://linux-hardware.org/?probe=7e7a86540c) | Nov 13, 2016 |
| ASUSTek       | P8P67                       | [5a00910b95](https://linux-hardware.org/?probe=5a00910b95) | Nov 09, 2016 |
| ASUSTek       | P5W DH Deluxe               | [f8433b752a](https://linux-hardware.org/?probe=f8433b752a) | Nov 03, 2016 |
| Nvidia        | NF-MCP61                    | [5c7c6bc310](https://linux-hardware.org/?probe=5c7c6bc310) | Nov 02, 2016 |
| MSI           | 760GM-P33                   | [05c4ad2044](https://linux-hardware.org/?probe=05c4ad2044) | Oct 28, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belarus/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ROSA R11           | 49       | 13.14%  |
| ROSA R10           | 45       | 12.06%  |
| ROSA R8.1          | 34       | 9.12%   |
| ROSA R9            | 17       | 4.56%   |
| ROSA R11.1         | 17       | 4.56%   |
| ROSA R8            | 16       | 4.29%   |
| Ubuntu 18.04       | 13       | 3.49%   |
| OpenMandriva 4.2   | 12       | 3.22%   |
| ROSA 12.2          | 11       | 2.95%   |
| Ubuntu 20.04       | 8        | 2.14%   |
| Linux Mint 20.3    | 7        | 1.88%   |
| Debian 11          | 7        | 1.88%   |
| OpenMandriva 4.3   | 6        | 1.61%   |
| Manjaro            | 6        | 1.61%   |
| Linux Mint 19.3    | 6        | 1.61%   |
| KDE neon 20.04     | 5        | 1.34%   |
| Fedora 31          | 5        | 1.34%   |
| ROSA 12.3          | 4        | 1.07%   |
| Fedora 36          | 4        | 1.07%   |
| Fedora 35          | 4        | 1.07%   |
| Fedora 34          | 4        | 1.07%   |
| Debian 10          | 4        | 1.07%   |
| Arch Rolling       | 4        | 1.07%   |
| Ubuntu 22.04       | 3        | 0.8%    |
| Linux Mint 21.1    | 3        | 0.8%    |
| Linux Mint 20.1    | 3        | 0.8%    |
| Linux Mint 19.1    | 3        | 0.8%    |
| Linux Mint 18.3    | 3        | 0.8%    |
| Kubuntu 20.04      | 3        | 0.8%    |
| Fedora 37          | 3        | 0.8%    |
| Fedora 33          | 3        | 0.8%    |
| Zorin 16           | 2        | 0.54%   |
| Xubuntu 22.04      | 2        | 0.54%   |
| Ubuntu 21.04       | 2        | 0.54%   |
| Pop!_OS 20.04      | 2        | 0.54%   |
| OpenMandriva 23.03 | 2        | 0.54%   |
| Linux Mint 18      | 2        | 0.54%   |
| Gentoo 2.7         | 2        | 0.54%   |
| Fedora 32          | 2        | 0.54%   |
| Debian Unstable    | 2        | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 169      | 51.21%  |
| Ubuntu       | 27       | 8.18%   |
| Linux Mint   | 27       | 8.18%   |
| OpenMandriva | 21       | 6.36%   |
| Debian       | 15       | 4.55%   |
| Manjaro      | 13       | 3.94%   |
| Fedora       | 13       | 3.94%   |
| KDE neon     | 6        | 1.82%   |
| Arch         | 5        | 1.52%   |
| Kubuntu      | 4        | 1.21%   |
| Gentoo       | 4        | 1.21%   |
| Xubuntu      | 3        | 0.91%   |
| Pop!_OS      | 3        | 0.91%   |
| Zorin        | 2        | 0.61%   |
| openSUSE     | 2        | 0.61%   |
| Elementary   | 2        | 0.61%   |
| BlackPanther | 2        | 0.61%   |
| ArcoLinux    | 2        | 0.61%   |
| Ubuntu Unity | 1        | 0.3%    |
| Ubuntu MATE  | 1        | 0.3%    |
| RHEL         | 1        | 0.3%    |
| Mageia       | 1        | 0.3%    |
| Lubuntu      | 1        | 0.3%    |
| LMDE         | 1        | 0.3%    |
| Kali         | 1        | 0.3%    |
| Endless      | 1        | 0.3%    |
| CentOS       | 1        | 0.3%    |
| ALT Linux    | 1        | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64    | 22       | 5.01%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 17       | 3.87%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 17       | 3.87%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 12       | 2.73%   |
| 5.10.14-desktop-1omv4002           | 11       | 2.51%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 10       | 2.28%   |
| 4.9.76-nrj-desktop-1rosa-x86_64    | 9        | 2.05%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 8        | 1.82%   |
| 4.15.0-desktop-45.1rosa-i586       | 7        | 1.59%   |
| 4.1.38-nrj-desktop-2rosa-x86_64    | 7        | 1.59%   |
| 5.4.83-generic-2rosa-x86_64        | 6        | 1.37%   |
| 5.16.7-desktop-1omv4003            | 6        | 1.37%   |
| 5.15.0-56-generic                  | 6        | 1.37%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 6        | 1.37%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 6        | 1.37%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 5        | 1.14%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 5        | 1.14%   |
| 4.15.0-desktop-47.2rosa-x86_64     | 5        | 1.14%   |
| 4.9.111-nrj-desktop-2rosa-x86_64   | 4        | 0.91%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 4        | 0.91%   |
| 4.1.38-nrj-desktop-2rosa-i586      | 4        | 0.91%   |
| 5.16.5-200.fc35.x86_64             | 3        | 0.68%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 3        | 0.68%   |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 3        | 0.68%   |
| 4.9.76-nrj-desktop-1rosa-i586      | 3        | 0.68%   |
| 4.9.34-nrj-desktop-1rosa-x86_64    | 3        | 0.68%   |
| 4.15.0-desktop-94.1rosa-x86_64     | 3        | 0.68%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 3        | 0.68%   |
| 4.15.0-desktop-54.1rosa-x86_64     | 3        | 0.68%   |
| 4.1.34-nrj-desktop-2rosa-i586      | 3        | 0.68%   |
| 5.8.0-48-generic                   | 2        | 0.46%   |
| 5.8.0-45-generic                   | 2        | 0.46%   |
| 5.4.83-generic-2rosa-i586          | 2        | 0.46%   |
| 5.4.32-generic-2rosa-x86_64        | 2        | 0.46%   |
| 5.4.0-65-generic                   | 2        | 0.46%   |
| 5.4.0-58-generic                   | 2        | 0.46%   |
| 5.4.0-48-generic                   | 2        | 0.46%   |
| 5.4.0-42-generic                   | 2        | 0.46%   |
| 5.17.5-300.fc36.x86_64             | 2        | 0.46%   |
| 5.12.9-300.fc34.x86_64             | 2        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15.0  | 56       | 13.05%  |
| 5.4.0   | 27       | 6.29%   |
| 4.9.60  | 27       | 6.29%   |
| 4.9.20  | 19       | 4.43%   |
| 4.1.38  | 14       | 3.26%   |
| 4.9.155 | 13       | 3.03%   |
| 5.15.0  | 12       | 2.8%    |
| 4.9.76  | 12       | 2.8%    |
| 5.10.14 | 11       | 2.56%   |
| 4.1.34  | 11       | 2.56%   |
| 5.10.74 | 10       | 2.33%   |
| 5.10.0  | 10       | 2.33%   |
| 5.8.0   | 9        | 2.1%    |
| 5.4.83  | 8        | 1.86%   |
| 4.9.9   | 7        | 1.63%   |
| 4.9.41  | 7        | 1.63%   |
| 4.9.124 | 7        | 1.63%   |
| 5.16.7  | 6        | 1.4%    |
| 5.0.0   | 6        | 1.4%    |
| 5.13.0  | 5        | 1.17%   |
| 5.11.0  | 5        | 1.17%   |
| 4.18.0  | 5        | 1.17%   |
| 4.9.34  | 4        | 0.93%   |
| 4.9.111 | 4        | 0.93%   |
| 4.19.0  | 4        | 0.93%   |
| 5.3.0   | 3        | 0.7%    |
| 5.16.5  | 3        | 0.7%    |
| 5.15.75 | 3        | 0.7%    |
| 4.9.95  | 3        | 0.7%    |
| 6.2.2   | 2        | 0.47%   |
| 6.1.0   | 2        | 0.47%   |
| 5.9.11  | 2        | 0.47%   |
| 5.6.14  | 2        | 0.47%   |
| 5.4.60  | 2        | 0.47%   |
| 5.4.32  | 2        | 0.47%   |
| 5.3.12  | 2        | 0.47%   |
| 5.3.11  | 2        | 0.47%   |
| 5.19.0  | 2        | 0.47%   |
| 5.17.5  | 2        | 0.47%   |
| 5.17.0  | 2        | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 80       | 20.73%  |
| 4.15    | 56       | 14.51%  |
| 5.4     | 43       | 11.14%  |
| 5.10    | 33       | 8.55%   |
| 4.1     | 25       | 6.48%   |
| 5.15    | 24       | 6.22%   |
| 5.8     | 12       | 3.11%   |
| 5.16    | 9        | 2.33%   |
| 5.3     | 8        | 2.07%   |
| 5.13    | 8        | 2.07%   |
| 5.11    | 8        | 2.07%   |
| 5.0     | 7        | 1.81%   |
| 4.19    | 7        | 1.81%   |
| 4.18    | 7        | 1.81%   |
| 6.2     | 5        | 1.3%    |
| 6.1     | 5        | 1.3%    |
| 5.6     | 5        | 1.3%    |
| 5.19    | 5        | 1.3%    |
| 5.12    | 5        | 1.3%    |
| 5.9     | 4        | 1.04%   |
| 5.17    | 4        | 1.04%   |
| 6.0     | 3        | 0.78%   |
| 5.7     | 3        | 0.78%   |
| 5.18    | 3        | 0.78%   |
| 5.14    | 3        | 0.78%   |
| 4.8     | 3        | 0.78%   |
| 4.4     | 3        | 0.78%   |
| 5.5     | 2        | 0.52%   |
| 4.14    | 2        | 0.52%   |
| 4.20    | 1        | 0.26%   |
| 4.17    | 1        | 0.26%   |
| 4.13    | 1        | 0.26%   |
| 4.12    | 1        | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 290      | 90.34%  |
| i686   | 31       | 9.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE4       | 113      | 33.04%  |
| KDE5       | 95       | 27.78%  |
| GNOME      | 58       | 16.96%  |
| Unknown    | 21       | 6.14%   |
| X-Cinnamon | 16       | 4.68%   |
| XFCE       | 15       | 4.39%   |
| MATE       | 7        | 2.05%   |
| LXQt       | 5        | 1.46%   |
| KDE        | 3        | 0.88%   |
| Pantheon   | 2        | 0.58%   |
| Unity      | 1        | 0.29%   |
| Trinity    | 1        | 0.29%   |
| Openbox    | 1        | 0.29%   |
| LXDE       | 1        | 0.29%   |
| Deepin     | 1        | 0.29%   |
| Cinnamon   | 1        | 0.29%   |
| bspwm      | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 286      | 87.2%   |
| Wayland | 29       | 8.84%   |
| Unknown | 7        | 2.13%   |
| Tty     | 6        | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 113      | 33.14%  |
| SDDM    | 101      | 29.62%  |
| Unknown | 63       | 18.48%  |
| GDM     | 28       | 8.21%   |
| LightDM | 15       | 4.4%    |
| TDM     | 12       | 3.52%   |
| GDM3    | 7        | 2.05%   |
| MDM     | 2        | 0.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 165      | 49.55%  |
| ru_RU       | 115      | 34.53%  |
| en_US       | 37       | 11.11%  |
| be_BY       | 6        | 1.8%    |
| en_GB       | 4        | 1.2%    |
| C           | 3        | 0.9%    |
| ru_RU.UTF_8 | 1        | 0.3%    |
| ru_BY       | 1        | 0.3%    |
| en_CA       | 1        | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 218      | 66.46%  |
| EFI  | 110      | 33.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 212      | 60.92%  |
| Unknown | 93       | 26.72%  |
| Overlay | 19       | 5.46%   |
| Btrfs   | 14       | 4.02%   |
| Xfs     | 3        | 0.86%   |
| Ext2    | 2        | 0.57%   |
| Zfs     | 1        | 0.29%   |
| Tmpfs   | 1        | 0.29%   |
| SAMSUNG | 1        | 0.29%   |
| F2fs    | 1        | 0.29%   |
| Ext3    | 1        | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 139      | 39.94%  |
| GPT     | 107      | 30.75%  |
| Unknown | 102      | 29.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 280      | 84.59%  |
| Yes       | 51       | 15.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 212      | 62.17%  |
| Yes       | 129      | 37.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 95       | 29.69%  |
| ASUSTek Computer    | 81       | 25.31%  |
| ASRock              | 70       | 21.88%  |
| MSI                 | 35       | 10.94%  |
| Biostar             | 11       | 3.44%   |
| Intel               | 6        | 1.88%   |
| ECS                 | 3        | 0.94%   |
| Nvidia              | 2        | 0.63%   |
| Lenovo              | 2        | 0.63%   |
| Hewlett-Packard     | 2        | 0.63%   |
| EPoX Computer       | 2        | 0.63%   |
| ZOTAC               | 1        | 0.31%   |
| VIA Technologies    | 1        | 0.31%   |
| Partner             | 1        | 0.31%   |
| Kllisre             | 1        | 0.31%   |
| Jetway              | 1        | 0.31%   |
| Iskratel, Kranj     | 1        | 0.31%   |
| Huanan              | 1        | 0.31%   |
| Foxconn             | 1        | 0.31%   |
| Dell                | 1        | 0.31%   |
| Acer                | 1        | 0.31%   |
| Unknown             | 1        | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASRock N68C-GS FX        | 5        | 1.56%   |
| MSI MS-7369              | 4        | 1.25%   |
| Gigabyte 970A-DS3P       | 4        | 1.25%   |
| ASUS All Series          | 4        | 1.25%   |
| ASRock N68-VS3 UCC       | 4        | 1.25%   |
| MSI MS-7309              | 3        | 0.94%   |
| Gigabyte M61SME-S2       | 3        | 0.94%   |
| Gigabyte H81M-S2H        | 3        | 0.94%   |
| Gigabyte GA-MA74GM-S2H   | 3        | 0.94%   |
| Gigabyte GA-780T-D3L     | 3        | 0.94%   |
| Gigabyte B450M S2H       | 3        | 0.94%   |
| Gigabyte B450M DS3H      | 3        | 0.94%   |
| ASUS TUF B450-PRO GAMING | 3        | 0.94%   |
| ASUS P8H77-V             | 3        | 0.94%   |
| ASRock N68-VGS3 FX       | 3        | 0.94%   |
| Nvidia NF-MCP61          | 2        | 0.63%   |
| MSI MS-7996              | 2        | 0.63%   |
| MSI MS-7846              | 2        | 0.63%   |
| MSI MS-7623              | 2        | 0.63%   |
| MSI MS-7592              | 2        | 0.63%   |
| MSI MS-7250              | 2        | 0.63%   |
| Lenovo 3000              | 2        | 0.63%   |
| Intel SKYBAY             | 2        | 0.63%   |
| Gigabyte Z68XP-UD3       | 2        | 0.63%   |
| Gigabyte Z390 AORUS PRO  | 2        | 0.63%   |
| Gigabyte P67A-D3-B3      | 2        | 0.63%   |
| Gigabyte M56S-S3         | 2        | 0.63%   |
| Gigabyte GA-MA770-DS3    | 2        | 0.63%   |
| Gigabyte 945PL-S3        | 2        | 0.63%   |
| ASUS Z170I PRO GAMING    | 2        | 0.63%   |
| ASUS PRIME H310M-R R2.0  | 2        | 0.63%   |
| ASUS PRIME A320M-K       | 2        | 0.63%   |
| ASUS P5B                 | 2        | 0.63%   |
| ASUS M5A97 PRO           | 2        | 0.63%   |
| ASUS A88XM-A             | 2        | 0.63%   |
| ASUS A68HM-K             | 2        | 0.63%   |
| ASRock N68C-S UCC        | 2        | 0.63%   |
| ASRock N68C-GS4 FX       | 2        | 0.63%   |
| ASRock B450M Pro4        | 2        | 0.63%   |
| ASRock 990FX Extreme4    | 2        | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 9        | 2.81%   |
| Gigabyte B450M         | 7        | 2.19%   |
| ASRock N68C-GS         | 5        | 1.56%   |
| ASRock N68-VS3         | 5        | 1.56%   |
| MSI MS-7369            | 4        | 1.25%   |
| Gigabyte Z390          | 4        | 1.25%   |
| Gigabyte 970A-DS3P     | 4        | 1.25%   |
| ASUS TUF               | 4        | 1.25%   |
| ASUS P8H77-V           | 4        | 1.25%   |
| ASUS All               | 4        | 1.25%   |
| MSI MS-7309            | 3        | 0.94%   |
| Gigabyte X570          | 3        | 0.94%   |
| Gigabyte M61SME-S2     | 3        | 0.94%   |
| Gigabyte H81M-S2H      | 3        | 0.94%   |
| Gigabyte GA-MA74GM-S2H | 3        | 0.94%   |
| Gigabyte GA-780T-D3L   | 3        | 0.94%   |
| ASUS ROG               | 3        | 0.94%   |
| ASUS P8Z77-V           | 3        | 0.94%   |
| ASUS P5B               | 3        | 0.94%   |
| ASUS M5A97             | 3        | 0.94%   |
| ASRock N68-VGS3        | 3        | 0.94%   |
| ASRock B450M           | 3        | 0.94%   |
| Nvidia NF-MCP61        | 2        | 0.63%   |
| MSI MS-7996            | 2        | 0.63%   |
| MSI MS-7846            | 2        | 0.63%   |
| MSI MS-7623            | 2        | 0.63%   |
| MSI MS-7592            | 2        | 0.63%   |
| MSI MS-7250            | 2        | 0.63%   |
| Lenovo 3000            | 2        | 0.63%   |
| Intel SKYBAY           | 2        | 0.63%   |
| HP Compaq              | 2        | 0.63%   |
| Gigabyte Z68XP-UD3     | 2        | 0.63%   |
| Gigabyte P67A-D3-B3    | 2        | 0.63%   |
| Gigabyte M56S-S3       | 2        | 0.63%   |
| Gigabyte GA-MA770-DS3  | 2        | 0.63%   |
| Gigabyte 945PL-S3      | 2        | 0.63%   |
| ASUS Z170I             | 2        | 0.63%   |
| ASUS SABERTOOTH        | 2        | 0.63%   |
| ASUS P8H61-M           | 2        | 0.63%   |
| ASUS P5K               | 2        | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 41       | 12.81%  |
| 2011 | 36       | 11.25%  |
| 2018 | 35       | 10.94%  |
| 2013 | 34       | 10.63%  |
| 2007 | 27       | 8.44%   |
| 2010 | 22       | 6.88%   |
| 2014 | 19       | 5.94%   |
| 2008 | 17       | 5.31%   |
| 2006 | 16       | 5%      |
| 2009 | 14       | 4.38%   |
| 2017 | 12       | 3.75%   |
| 2019 | 10       | 3.13%   |
| 2015 | 10       | 3.13%   |
| 2020 | 8        | 2.5%    |
| 2016 | 8        | 2.5%    |
| 2005 | 5        | 1.56%   |
| 2021 | 3        | 0.94%   |
| 2022 | 2        | 0.63%   |
| 2003 | 1        | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 320      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 319      | 99.38%  |
| Enabled  | 2        | 0.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 320      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 86       | 26.14%  |
| 8.01-16.0   | 75       | 22.8%   |
| 16.01-24.0  | 52       | 15.81%  |
| 4.01-8.0    | 39       | 11.85%  |
| 32.01-64.0  | 22       | 6.69%   |
| 1.01-2.0    | 22       | 6.69%   |
| 2.01-3.0    | 18       | 5.47%   |
| 24.01-32.0  | 5        | 1.52%   |
| 0.51-1.0    | 5        | 1.52%   |
| 64.01-256.0 | 4        | 1.22%   |
| 0.01-0.5    | 1        | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 135      | 36.49%  |
| 0.51-1.0   | 104      | 28.11%  |
| 2.01-3.0   | 55       | 14.86%  |
| 4.01-8.0   | 26       | 7.03%   |
| 3.01-4.0   | 24       | 6.49%   |
| 8.01-16.0  | 11       | 2.97%   |
| 0.01-0.5   | 10       | 2.7%    |
| 16.01-24.0 | 3        | 0.81%   |
| 32.01-64.0 | 1        | 0.27%   |
| 24.01-32.0 | 1        | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 147      | 43.11%  |
| 2      | 106      | 31.09%  |
| 3      | 56       | 16.42%  |
| 4      | 18       | 5.28%   |
| 5      | 9        | 2.64%   |
| 9      | 2        | 0.59%   |
| 0      | 2        | 0.59%   |
| 6      | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 53.11%  |
| Yes       | 151      | 46.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 316      | 98.75%  |
| No        | 4        | 1.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 230      | 70.99%  |
| Yes       | 94       | 29.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 278      | 86.07%  |
| Yes       | 45       | 13.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Belarus | 320      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Minsk          | 136      | 38.97%  |
| Gomel          | 40       | 11.46%  |
| Vitebsk        | 37       | 10.6%   |
| Hrodna         | 22       | 6.3%    |
| Brest          | 21       | 6.02%   |
| Mogilev        | 19       | 5.44%   |
| Polatsk        | 8        | 2.29%   |
| Baranovichi    | 6        | 1.72%   |
| Slutsk         | 5        | 1.43%   |
| Vawkavysk      | 4        | 1.15%   |
| Zhlobin        | 2        | 0.57%   |
| Syanno         | 2        | 0.57%   |
| Svyetlahorsk   | 2        | 0.57%   |
| Slonim         | 2        | 0.57%   |
| Rechytsa       | 2        | 0.57%   |
| Rahachow       | 2        | 0.57%   |
| Ogorodniki     | 2        | 0.57%   |
| Mazyr          | 2        | 0.57%   |
| Masty          | 2        | 0.57%   |
| Lida           | 2        | 0.57%   |
| Klyetsk        | 2        | 0.57%   |
| Dubovka        | 2        | 0.57%   |
| Bogushevichi   | 2        | 0.57%   |
| Babruysk       | 2        | 0.57%   |
| Stolin         | 1        | 0.29%   |
| Snitovo        | 1        | 0.29%   |
| Smalyavichy    | 1        | 0.29%   |
| Skoki          | 1        | 0.29%   |
| Pruzhany       | 1        | 0.29%   |
| Osipovichi     | 1        | 0.29%   |
| Orsha          | 1        | 0.29%   |
| Olekhnoviche   | 1        | 0.29%   |
| Novolukoml'    | 1        | 0.29%   |
| Navapolatsk    | 1        | 0.29%   |
| Murava         | 1        | 0.29%   |
| Magistral'naya | 1        | 0.29%   |
| Lyepyel'       | 1        | 0.29%   |
| Korobchicy     | 1        | 0.29%   |
| Kamyenka       | 1        | 0.29%   |
| Iwye           | 1        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 112      | 195    | 20.04%  |
| Seagate             | 109      | 192    | 19.5%   |
| Samsung Electronics | 79       | 125    | 14.13%  |
| Toshiba             | 56       | 104    | 10.02%  |
| Hitachi             | 40       | 59     | 7.16%   |
| Kingston            | 33       | 49     | 5.9%    |
| Crucial             | 14       | 17     | 2.5%    |
| Patriot             | 10       | 14     | 1.79%   |
| OCZ                 | 9        | 10     | 1.61%   |
| Intel               | 9        | 9      | 1.61%   |
| China               | 8        | 9      | 1.43%   |
| HGST                | 6        | 22     | 1.07%   |
| Gigabyte Technology | 6        | 6      | 1.07%   |
| A-DATA Technology   | 6        | 7      | 1.07%   |
| Apacer              | 5        | 6      | 0.89%   |
| Plextor             | 4        | 5      | 0.72%   |
| Maxtor              | 4        | 4      | 0.72%   |
| GOODRAM             | 4        | 4      | 0.72%   |
| Unknown             | 3        | 3      | 0.54%   |
| SPCC                | 3        | 6      | 0.54%   |
| Silicon Motion      | 3        | 4      | 0.54%   |
| KingSpec            | 3        | 5      | 0.54%   |
| SanDisk             | 2        | 2      | 0.36%   |
| Kllisre             | 2        | 3      | 0.36%   |
| JMicron Technology  | 2        | 2      | 0.36%   |
| Fujitsu             | 2        | 2      | 0.36%   |
| External            | 2        | 2      | 0.36%   |
| XrayDisk            | 1        | 1      | 0.18%   |
| XPG                 | 1        | 1      | 0.18%   |
| WD MediaMax         | 1        | 1      | 0.18%   |
| USB3.0              | 1        | 1      | 0.18%   |
| Transcend           | 1        | 1      | 0.18%   |
| Team                | 1        | 1      | 0.18%   |
| Synopsys            | 1        | 1      | 0.18%   |
| Smartbuy            | 1        | 1      | 0.18%   |
| SINTECHI            | 1        | 1      | 0.18%   |
| Phison              | 1        | 1      | 0.18%   |
| OCZ-VERTEX3         | 1        | 2      | 0.18%   |
| Netac               | 1        | 1      | 0.18%   |
| Micron Technology   | 1        | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba DT01ACA050 500GB         | 20       | 3.12%   |
| Toshiba DT01ACA100 1TB           | 15       | 2.34%   |
| Toshiba DT01ACA200 2TB           | 12       | 1.87%   |
| Kingston SA400S37120G 120GB SSD  | 10       | 1.56%   |
| Seagate ST500DM002-1BD142 500GB  | 9        | 1.4%    |
| Samsung SSD 860 EVO 500GB        | 9        | 1.4%    |
| Samsung SSD 860 EVO 250GB        | 8        | 1.25%   |
| Hitachi HDS721010CLA330 1TB      | 6        | 0.94%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 5        | 0.78%   |
| Toshiba HDWD110 1TB              | 5        | 0.78%   |
| Toshiba DT01ACA300 3TB           | 5        | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 0.78%   |
| Samsung HD160JJ/ 160GB           | 5        | 0.78%   |
| OCZ VERTEX4 128GB SSD            | 5        | 0.78%   |
| Kingston SA400S37240G 240GB SSD  | 5        | 0.78%   |
| Hitachi HDP725050GLA360 500GB    | 5        | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB      | 4        | 0.62%   |
| WDC WD20EARS-00MVWB0 2TB         | 4        | 0.62%   |
| Seagate ST380817AS 80GB          | 4        | 0.62%   |
| Seagate ST3500413AS 500GB        | 4        | 0.62%   |
| Seagate ST3160815AS 160GB        | 4        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB   | 4        | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 0.62%   |
| Samsung SSD 850 EVO 250GB        | 4        | 0.62%   |
| Samsung SP0802N 80GB             | 4        | 0.62%   |
| Samsung NVMe SSD Drive 500GB     | 4        | 0.62%   |
| Patriot Burst 120GB SSD          | 4        | 0.62%   |
| Kingston SUV400S37120G 120GB SSD | 4        | 0.62%   |
| Hitachi HDS721050CLA360 500GB    | 4        | 0.62%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 3        | 0.47%   |
| WDC WD5000AADS-00M2B0 500GB      | 3        | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB         | 3        | 0.47%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3        | 0.47%   |
| Seagate ST500DM005 HD502HJ 500GB | 3        | 0.47%   |
| Seagate ST340016A 40GB           | 3        | 0.47%   |
| Seagate ST340014A 40GB           | 3        | 0.47%   |
| Seagate ST3250820AS 250GB        | 3        | 0.47%   |
| Seagate ST3160812A 160GB         | 3        | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 109      | 169    | 29.62%  |
| Seagate             | 109      | 191    | 29.62%  |
| Toshiba             | 56       | 104    | 15.22%  |
| Hitachi             | 40       | 59     | 10.87%  |
| Samsung Electronics | 38       | 51     | 10.33%  |
| HGST                | 6        | 22     | 1.63%   |
| Maxtor              | 4        | 4      | 1.09%   |
| Fujitsu             | 2        | 2      | 0.54%   |
| WD MediaMax         | 1        | 1      | 0.27%   |
| USB3.0              | 1        | 1      | 0.27%   |
| SINTECHI            | 1        | 1      | 0.27%   |
| External            | 1        | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 55     | 20.73%  |
| Kingston            | 29       | 44     | 17.68%  |
| Crucial             | 13       | 16     | 7.93%   |
| OCZ                 | 9        | 10     | 5.49%   |
| WDC                 | 8        | 26     | 4.88%   |
| Patriot             | 8        | 12     | 4.88%   |
| China               | 8        | 9      | 4.88%   |
| Intel               | 7        | 7      | 4.27%   |
| Apacer              | 5        | 6      | 3.05%   |
| Plextor             | 4        | 5      | 2.44%   |
| A-DATA Technology   | 4        | 5      | 2.44%   |
| Unknown             | 3        | 3      | 1.83%   |
| SPCC                | 3        | 6      | 1.83%   |
| KingSpec            | 3        | 5      | 1.83%   |
| GOODRAM             | 3        | 3      | 1.83%   |
| Gigabyte Technology | 3        | 3      | 1.83%   |
| SanDisk             | 2        | 2      | 1.22%   |
| JMicron Technology  | 2        | 2      | 1.22%   |
| XrayDisk            | 1        | 1      | 0.61%   |
| Transcend           | 1        | 1      | 0.61%   |
| Team                | 1        | 1      | 0.61%   |
| Smartbuy            | 1        | 1      | 0.61%   |
| Seagate             | 1        | 1      | 0.61%   |
| OCZ-VERTEX3         | 1        | 2      | 0.61%   |
| Netac               | 1        | 1      | 0.61%   |
| Micron Technology   | 1        | 1      | 0.61%   |
| M500                | 1        | 1      | 0.61%   |
| KingDian            | 1        | 1      | 0.61%   |
| Kimtigo             | 1        | 1      | 0.61%   |
| Hoodisk             | 1        | 1      | 0.61%   |
| Dahua               | 1        | 1      | 0.61%   |
| Corsair             | 1        | 3      | 0.61%   |
| Acer                | 1        | 1      | 0.61%   |
| 2.5"                | 1        | 2      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 284      | 606    | 60.94%  |
| SSD  | 145      | 239    | 31.12%  |
| NVMe | 37       | 48     | 7.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 314      | 838    | 87.71%  |
| NVMe | 37       | 47     | 10.34%  |
| SAS  | 7        | 8      | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 271      | 526    | 60.76%  |
| 0.51-1.0   | 107      | 183    | 23.99%  |
| 1.01-2.0   | 38       | 83     | 8.52%   |
| 2.01-3.0   | 11       | 18     | 2.47%   |
| 3.01-4.0   | 9        | 11     | 2.02%   |
| 4.01-10.0  | 7        | 20     | 1.57%   |
| 10.01-20.0 | 3        | 4      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 93       | 25.69%  |
| 251-500        | 66       | 18.23%  |
| 501-1000       | 46       | 12.71%  |
| 51-100         | 40       | 11.05%  |
| 1-20           | 35       | 9.67%   |
| 1001-2000      | 34       | 9.39%   |
| More than 3000 | 20       | 5.52%   |
| 21-50          | 17       | 4.7%    |
| 2001-3000      | 7        | 1.93%   |
| Unknown        | 4        | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 157      | 41.42%  |
| 101-250        | 48       | 12.66%  |
| 51-100         | 40       | 10.55%  |
| 21-50          | 39       | 10.29%  |
| 501-1000       | 31       | 8.18%   |
| 251-500        | 29       | 7.65%   |
| 1001-2000      | 12       | 3.17%   |
| 2001-3000      | 10       | 2.64%   |
| More than 3000 | 9        | 2.37%   |
| Unknown        | 4        | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB             | 4        | 5      | 2.92%   |
| Hitachi HDP725050GLA360 500GB      | 4        | 8      | 2.92%   |
| WDC WD20EARS-00MVWB0 2TB           | 3        | 6      | 2.19%   |
| Toshiba DT01ACA200 2TB             | 3        | 5      | 2.19%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 10     | 2.19%   |
| Samsung Electronics HD160JJ/ 160GB | 3        | 3      | 2.19%   |
| Hitachi HDS721010CLA330 1TB        | 3        | 4      | 2.19%   |
| WDC WD5000AAKS-00A7B0 500GB        | 2        | 2      | 1.46%   |
| WDC WD30EFRX-68EUZN0 3TB           | 2        | 3      | 1.46%   |
| Seagate STM3500418AS 500GB         | 2        | 2      | 1.46%   |
| Seagate ST3500320AS 500GB          | 2        | 3      | 1.46%   |
| Seagate ST340016A 40GB             | 2        | 3      | 1.46%   |
| Seagate ST3250820AS 250GB          | 2        | 2      | 1.46%   |
| Seagate ST3160812A 160GB           | 2        | 4      | 1.46%   |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 2      | 1.46%   |
| Samsung Electronics SP0802N 80GB   | 2        | 2      | 1.46%   |
| Samsung Electronics HD161HJ 160GB  | 2        | 3      | 1.46%   |
| Samsung Electronics HD103SJ 1TB    | 2        | 2      | 1.46%   |
| OCZ VERTEX4 128GB SSD              | 2        | 2      | 1.46%   |
| Hitachi HDS721010DLE630 1TB        | 2        | 2      | 1.46%   |
| Fujitsu MHZ2160BH G2 160GB         | 2        | 2      | 1.46%   |
| WDC WD800BB-56JKC0 80GB            | 1        | 1      | 0.73%   |
| WDC WD6000HLHX-01JJPV0 600GB       | 1        | 1      | 0.73%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1        | 2      | 0.73%   |
| WDC WD5000AAKX-083CA1 500GB        | 1        | 1      | 0.73%   |
| WDC WD5000AAKX-00U6AA0 500GB       | 1        | 1      | 0.73%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 1      | 0.73%   |
| WDC WD5000AAKS-08WWPA0 500GB       | 1        | 1      | 0.73%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 1      | 0.73%   |
| WDC WD5000AAKB-00H8A0 500GB        | 1        | 1      | 0.73%   |
| WDC WD5000AADS-56S9B0 500GB        | 1        | 1      | 0.73%   |
| WDC WD400EB-00CPF0 40GB            | 1        | 1      | 0.73%   |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1        | 1      | 0.73%   |
| WDC WD3200BEVT-22A23T0 320GB       | 1        | 2      | 0.73%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1        | 1      | 0.73%   |
| WDC WD3200AAKS-00SBA0 320GB        | 1        | 1      | 0.73%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1        | 1      | 0.73%   |
| WDC WD2500KS-00MJB0 250GB          | 1        | 1      | 0.73%   |
| WDC WD2500JS-63MHB5 250GB          | 1        | 2      | 0.73%   |
| WDC WD2500AAJS-65M0A0 250GB        | 1        | 2      | 0.73%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 39       | 50     | 30.23%  |
| Seagate             | 30       | 47     | 23.26%  |
| Samsung Electronics | 17       | 20     | 13.18%  |
| Hitachi             | 17       | 26     | 13.18%  |
| Toshiba             | 8        | 11     | 6.2%    |
| OCZ                 | 3        | 3      | 2.33%   |
| Kingston            | 3        | 3      | 2.33%   |
| Maxtor              | 2        | 2      | 1.55%   |
| Fujitsu             | 2        | 2      | 1.55%   |
| Crucial             | 2        | 2      | 1.55%   |
| WD MediaMax         | 1        | 1      | 0.78%   |
| OCZ-VERTEX3         | 1        | 2      | 0.78%   |
| Intel               | 1        | 1      | 0.78%   |
| Corsair             | 1        | 3      | 0.78%   |
| Apacer              | 1        | 1      | 0.78%   |
| A-DATA Technology   | 1        | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 39       | 50     | 33.62%  |
| Seagate             | 30       | 47     | 25.86%  |
| Samsung Electronics | 17       | 20     | 14.66%  |
| Hitachi             | 17       | 26     | 14.66%  |
| Toshiba             | 8        | 11     | 6.9%    |
| Maxtor              | 2        | 2      | 1.72%   |
| Fujitsu             | 2        | 2      | 1.72%   |
| WD MediaMax         | 1        | 1      | 0.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 100      | 159    | 88.5%   |
| SSD  | 12       | 15     | 10.62%  |
| NVMe | 1        | 1      | 0.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics SP0802N 80GB  | 1        | 1      | 25%     |
| Samsung Electronics HD252HJ 250GB | 1        | 1      | 25%     |
| Maxtor STM380211AS 80GB           | 1        | 1      | 25%     |
| Hitachi HTS545050A7E380 500GB     | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 50%     |
| Maxtor              | 1        | 1      | 25%     |
| Hitachi             | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 211      | 523    | 52.49%  |
| Malfunc  | 111      | 175    | 27.61%  |
| Detected | 76       | 191    | 18.91%  |
| Failed   | 4        | 4      | 1%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 165      | 41.35%  |
| AMD                              | 106      | 26.57%  |
| Nvidia                           | 48       | 12.03%  |
| JMicron Technology               | 18       | 4.51%   |
| Samsung Electronics              | 14       | 3.51%   |
| Marvell Technology Group         | 11       | 2.76%   |
| ASMedia Technology               | 8        | 2.01%   |
| Silicon Motion                   | 7        | 1.75%   |
| Phison Electronics               | 6        | 1.5%    |
| Kingston Technology Company      | 5        | 1.25%   |
| VIA Technologies                 | 4        | 1%      |
| Realtek Semiconductor            | 3        | 0.75%   |
| Synopsys                         | 1        | 0.25%   |
| Silicon Integrated Systems [SiS] | 1        | 0.25%   |
| Micron Technology                | 1        | 0.25%   |
| Integrated Technology Express    | 1        | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40       | 7.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 39       | 6.84%   |
| Nvidia MCP61 SATA Controller                                                            | 32       | 5.61%   |
| Nvidia MCP61 IDE                                                                        | 32       | 5.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 29       | 5.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 22       | 3.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 20       | 3.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13       | 2.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 2.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 1.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 1.93%   |
| AMD FCH IDE Controller                                                                  | 11       | 1.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 1.75%   |
| JMicron JMB368 IDE controller                                                           | 9        | 1.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1.58%   |
| Nvidia MCP65 IDE                                                                        | 8        | 1.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7        | 1.23%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 1.23%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 1.23%   |
| Nvidia MCP65 SATA Controller                                                            | 6        | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 0.88%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.88%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 0.88%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 5        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.88%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 5        | 0.88%   |
| AMD FCH SATA Controller D                                                               | 5        | 0.88%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 0.7%    |
| Intel SATA Controller [RAID mode]                                                       | 4        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4        | 0.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.7%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4        | 0.7%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.53%   |
| Nvidia MCP67 AHCI Controller                                                            | 3        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 217      | 51.67%  |
| IDE  | 161      | 38.33%  |
| NVMe | 37       | 8.81%   |
| RAID | 5        | 1.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 167      | 52.19%  |
| AMD    | 153      | 47.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Athlon 64 X2 Dual Core Processor 5600+  | 6        | 1.87%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.56%   |
| AMD Athlon II X2 240 Processor              | 5        | 1.56%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.25%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 4        | 1.25%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 4        | 1.25%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 1.25%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 1.25%   |
| AMD Athlon II X2 245 Processor              | 4        | 1.25%   |
| AMD Athlon II X2 215 Processor              | 4        | 1.25%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 4        | 1.25%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.93%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.93%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 0.93%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.93%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.93%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 3        | 0.93%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.93%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.93%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.93%   |
| AMD FX-4300 Quad-Core Processor             | 3        | 0.93%   |
| AMD Athlon II X3 450 Processor              | 3        | 0.93%   |
| AMD Athlon II X2 250 Processor              | 3        | 0.93%   |
| Intel Xeon CPU E5430 @ 2.66GHz              | 2        | 0.62%   |
| Intel Pentium Dual-Core CPU E6800 @ 3.33GHz | 2        | 0.62%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 0.62%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.62%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 2        | 0.62%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 2        | 0.62%   |
| Intel Pentium 4 CPU 3.20GHz                 | 2        | 0.62%   |
| Intel Pentium 4 CPU 2.80GHz                 | 2        | 0.62%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.62%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.62%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.62%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.62%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.62%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 49       | 15.26%  |
| AMD Athlon 64 X2        | 24       | 7.48%   |
| Intel Core i7           | 21       | 6.54%   |
| AMD Athlon II X2        | 21       | 6.54%   |
| AMD FX                  | 20       | 6.23%   |
| Intel Celeron           | 18       | 5.61%   |
| AMD Ryzen 5             | 18       | 5.61%   |
| Intel Pentium           | 15       | 4.67%   |
| Intel Xeon              | 11       | 3.43%   |
| Intel Core i3           | 11       | 3.43%   |
| Intel Core 2 Duo        | 11       | 3.43%   |
| AMD Athlon II X3        | 10       | 3.12%   |
| AMD Ryzen 7             | 9        | 2.8%    |
| AMD Ryzen 3             | 8        | 2.49%   |
| Intel Atom              | 6        | 1.87%   |
| AMD Phenom II X4        | 6        | 1.87%   |
| Intel Pentium Dual-Core | 5        | 1.56%   |
| Intel Pentium 4         | 5        | 1.56%   |
| AMD Athlon X4           | 5        | 1.56%   |
| AMD Athlon II X4        | 4        | 1.25%   |
| Other                   | 3        | 0.93%   |
| Intel Pentium Dual      | 3        | 0.93%   |
| Intel Core i9           | 3        | 0.93%   |
| Intel Core 2            | 3        | 0.93%   |
| AMD Athlon 64           | 3        | 0.93%   |
| AMD Athlon              | 3        | 0.93%   |
| AMD A8                  | 3        | 0.93%   |
| AMD A10                 | 3        | 0.93%   |
| Intel Core 2 Quad       | 2        | 0.62%   |
| AMD Sempron             | 2        | 0.62%   |
| AMD A6                  | 2        | 0.62%   |
| AMD A4                  | 2        | 0.62%   |
| Intel Pentium Gold      | 1        | 0.31%   |
| Intel Genuine           | 1        | 0.31%   |
| Intel Core 2 Extreme    | 1        | 0.31%   |
| AMD Ryzen 9             | 1        | 0.31%   |
| AMD Ryzen 3 PRO         | 1        | 0.31%   |
| AMD Phenom II X6        | 1        | 0.31%   |
| AMD Phenom II X3        | 1        | 0.31%   |
| AMD Phenom II X2        | 1        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 130      | 39.27%  |
| 4       | 87       | 26.28%  |
| 6       | 32       | 9.67%   |
| Unknown | 26       | 7.85%   |
| 8       | 20       | 6.04%   |
| 3       | 17       | 5.14%   |
| 1       | 16       | 4.83%   |
| 10      | 2        | 0.6%    |
| 12      | 1        | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 319      | 99.69%  |
| 2      | 1        | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 192      | 58.01%  |
| 2       | 113      | 34.14%  |
| Unknown | 26       | 7.85%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 317      | 98.45%  |
| Unknown        | 3        | 0.93%   |
| 32-bit         | 2        | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 55       | 16.87%  |
| 0x010000c8 | 25       | 7.67%   |
| 0x306c3    | 24       | 7.36%   |
| 0x306a9    | 20       | 6.13%   |
| 0x206a7    | 19       | 5.83%   |
| 0x1067a    | 15       | 4.6%    |
| 0x010000c7 | 13       | 3.99%   |
| 0x06000852 | 10       | 3.07%   |
| 0x506e3    | 8        | 2.45%   |
| 0x06001119 | 8        | 2.45%   |
| 0x906ea    | 7        | 2.15%   |
| 0x08101016 | 7        | 2.15%   |
| 0x0800820d | 7        | 2.15%   |
| 0x906e9    | 6        | 1.84%   |
| 0x0600084f | 6        | 1.84%   |
| 0x10676    | 5        | 1.53%   |
| 0x010000db | 5        | 1.53%   |
| 0x6fd      | 4        | 1.23%   |
| 0x03000027 | 4        | 1.23%   |
| 0x906ed    | 3        | 0.92%   |
| 0x106e5    | 3        | 0.92%   |
| 0x106ca    | 3        | 0.92%   |
| 0x10661    | 3        | 0.92%   |
| 0x08001137 | 3        | 0.92%   |
| 0x06003106 | 3        | 0.92%   |
| 0xf49      | 2        | 0.61%   |
| 0x6fb      | 2        | 0.61%   |
| 0x6f6      | 2        | 0.61%   |
| 0x206d7    | 2        | 0.61%   |
| 0x20655    | 2        | 0.61%   |
| 0x106c2    | 2        | 0.61%   |
| 0x0a50000c | 2        | 0.61%   |
| 0x0a201016 | 2        | 0.61%   |
| 0x0a201009 | 2        | 0.61%   |
| 0x08701021 | 2        | 0.61%   |
| 0x08701013 | 2        | 0.61%   |
| 0x0600063e | 2        | 0.61%   |
| 0x01000095 | 2        | 0.61%   |
| 0xf65      | 1        | 0.31%   |
| 0xf43      | 1        | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| K10         | 47       | 14.6%   |
| K8 Hammer   | 29       | 9.01%   |
| Haswell     | 28       | 8.7%    |
| KabyLake    | 25       | 7.76%   |
| Piledriver  | 24       | 7.45%   |
| SandyBridge | 23       | 7.14%   |
| IvyBridge   | 21       | 6.52%   |
| Penryn      | 19       | 5.9%    |
| Core        | 15       | 4.66%   |
| Zen         | 14       | 4.35%   |
| Zen+        | 11       | 3.42%   |
| Skylake     | 10       | 3.11%   |
| Zen 3       | 8        | 2.48%   |
| NetBurst    | 7        | 2.17%   |
| Zen 2       | 6        | 1.86%   |
| Bonnell     | 6        | 1.86%   |
| K10 Llano   | 5        | 1.55%   |
| Westmere    | 4        | 1.24%   |
| Bulldozer   | 4        | 1.24%   |
| Steamroller | 3        | 0.93%   |
| Nehalem     | 3        | 0.93%   |
| Silvermont  | 2        | 0.62%   |
| Unknown     | 2        | 0.62%   |
| Tremont     | 1        | 0.31%   |
| Icelake     | 1        | 0.31%   |
| Goldmont    | 1        | 0.31%   |
| Excavator   | 1        | 0.31%   |
| CometLake   | 1        | 0.31%   |
| Bobcat      | 1        | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 187      | 55.49%  |
| AMD              | 80       | 23.74%  |
| Intel            | 69       | 20.47%  |
| ATI Technologies | 1        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 2.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 2.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 2.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 9        | 2.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 8        | 2.28%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 8        | 2.28%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 8        | 2.28%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 1.99%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 7        | 1.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 1.99%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 1.71%   |
| Nvidia G92 [GeForce GTS 250]                                                | 6        | 1.71%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 6        | 1.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.42%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 1.42%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 5        | 1.42%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 5        | 1.42%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 5        | 1.42%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 5        | 1.42%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.14%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 4        | 1.14%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 4        | 1.14%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 1.14%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 1.14%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.14%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 4        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.85%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 3        | 0.85%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 3        | 0.85%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 0.85%   |
| Nvidia GF108 [GeForce GT 440]                                               | 3        | 0.85%   |
| Nvidia GF108 [GeForce GT 430]                                               | 3        | 0.85%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 3        | 0.85%   |
| Intel HD Graphics 530                                                       | 3        | 0.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.85%   |
| AMD RV730 XT [Radeon HD 4670]                                               | 3        | 0.85%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                   | 3        | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 179      | 55.42%  |
| 1 x AMD        | 76       | 23.53%  |
| 1 x Intel      | 56       | 17.34%  |
| Intel + Nvidia | 6        | 1.86%   |
| 2 x AMD        | 5        | 1.55%   |
| 2 x Nvidia     | 1        | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 231      | 68.55%  |
| Proprietary | 86       | 25.52%  |
| Unknown     | 20       | 5.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 90       | 26.95%  |
| 1.01-2.0   | 74       | 22.16%  |
| Unknown    | 67       | 20.06%  |
| 0.51-1.0   | 56       | 16.77%  |
| 3.01-4.0   | 18       | 5.39%   |
| 7.01-8.0   | 13       | 3.89%   |
| 5.01-6.0   | 8        | 2.4%    |
| 2.01-3.0   | 4        | 1.2%    |
| 8.01-16.0  | 3        | 0.9%    |
| 4.01-5.0   | 1        | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 81       | 25.16%  |
| Goldstar             | 75       | 23.29%  |
| Philips              | 30       | 9.32%   |
| BenQ                 | 24       | 7.45%   |
| Dell                 | 22       | 6.83%   |
| AOC                  | 22       | 6.83%   |
| ViewSonic            | 13       | 4.04%   |
| Acer                 | 9        | 2.8%    |
| NEC Computers        | 7        | 2.17%   |
| Ancor Communications | 7        | 2.17%   |
| Hewlett-Packard      | 5        | 1.55%   |
| LG Electronics       | 4        | 1.24%   |
| XYK                  | 3        | 0.93%   |
| Unknown              | 3        | 0.93%   |
| Iiyama               | 3        | 0.93%   |
| Plain Tree Systems   | 2        | 0.62%   |
| ASUSTek Computer     | 2        | 0.62%   |
| Toshiba              | 1        | 0.31%   |
| Sony                 | 1        | 0.31%   |
| SKK                  | 1        | 0.31%   |
| Packard Bell         | 1        | 0.31%   |
| MStar                | 1        | 0.31%   |
| IBM                  | 1        | 0.31%   |
| HannStar             | 1        | 0.31%   |
| Eizo                 | 1        | 0.31%   |
| BBK                  | 1        | 0.31%   |
| Apple                | 1        | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 5        | 1.5%    |
| Goldstar L1919S GSM4AF2 1280x1024 376x301mm 19.0-inch                 | 4        | 1.2%    |
| XYK DVI XYK2360 1920x1080 477x268mm 21.5-inch                         | 3        | 0.9%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 3        | 0.9%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 3        | 0.9%    |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 3        | 0.9%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 0.9%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 3        | 0.9%    |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                 | 3        | 0.9%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 3        | 0.9%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.9%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3        | 0.9%    |
| BenQ G2220HD BNQ7820 1920x1080 477x268mm 21.5-inch                    | 3        | 0.9%    |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 521x293mm 23.5-inch     | 2        | 0.6%    |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch  | 2        | 0.6%    |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch   | 2        | 0.6%    |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 2        | 0.6%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 2        | 0.6%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 2        | 0.6%    |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 2        | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.6%    |
| Samsung Electronics S22B350 SAM08D3 1920x1080 477x268mm 21.5-inch     | 2        | 0.6%    |
| Samsung Electronics LCD Monitor SAM07BF 1920x1080 886x498mm 40.0-inch | 2        | 0.6%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.6%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.6%    |
| Philips PHL 284E5 PHLC0DE 1920x1080 621x341mm 27.9-inch               | 2        | 0.6%    |
| Philips PHL 246E7 PHLC107 1920x1080 521x293mm 23.5-inch               | 2        | 0.6%    |
| Philips 220SW PHL086F 1680x1050 474x296mm 22.0-inch                   | 2        | 0.6%    |
| Philips 19S PHL0878 1280x1024 376x301mm 19.0-inch                     | 2        | 0.6%    |
| NEC Computers LCD2090UXi NEC66B0 1600x1200 408x306mm 20.1-inch        | 2        | 0.6%    |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch              | 2        | 0.6%    |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                 | 2        | 0.6%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.6%    |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                      | 2        | 0.6%    |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 2        | 0.6%    |
| BenQ G2222HDL BNQ7859 1920x1080 477x268mm 21.5-inch                   | 2        | 0.6%    |
| BenQ E2420HD BNQ7916 1920x1080 531x299mm 24.0-inch                    | 2        | 0.6%    |
| AOC 2770 AOC2770 1920x1080 598x336mm 27.0-inch                        | 2        | 0.6%    |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 0.6%    |
| AOC 2475WR AOC2475 1920x1200 520x320mm 24.0-inch                      | 2        | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 145      | 45.45%  |
| 1280x1024 (SXGA)   | 54       | 16.93%  |
| 1680x1050 (WSXGA+) | 24       | 7.52%   |
| 1440x900 (WXGA+)   | 19       | 5.96%   |
| 2560x1440 (QHD)    | 16       | 5.02%   |
| 1366x768 (WXGA)    | 14       | 4.39%   |
| 3840x2160 (4K)     | 11       | 3.45%   |
| 2560x1080          | 8        | 2.51%   |
| 1600x900 (HD+)     | 7        | 2.19%   |
| 1920x1200 (WUXGA)  | 4        | 1.25%   |
| 1024x768 (XGA)     | 4        | 1.25%   |
| 3440x1440          | 2        | 0.63%   |
| 1600x1200          | 2        | 0.63%   |
| 1360x768           | 2        | 0.63%   |
| 1152x864           | 2        | 0.63%   |
| 4480x1200          | 1        | 0.31%   |
| 2288x1287          | 1        | 0.31%   |
| 1920x540           | 1        | 0.31%   |
| 1400x1050          | 1        | 0.31%   |
| Unknown            | 1        | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 56       | 17.28%  |
| 19      | 50       | 15.43%  |
| 23      | 44       | 13.58%  |
| 24      | 29       | 8.95%   |
| 27      | 26       | 8.02%   |
| 17      | 21       | 6.48%   |
| Unknown | 17       | 5.25%   |
| 22      | 16       | 4.94%   |
| 18      | 16       | 4.94%   |
| 20      | 11       | 3.4%    |
| 34      | 9        | 2.78%   |
| 31      | 6        | 1.85%   |
| 15      | 6        | 1.85%   |
| 40      | 4        | 1.23%   |
| 54      | 3        | 0.93%   |
| 84      | 2        | 0.62%   |
| 46      | 2        | 0.62%   |
| 142     | 1        | 0.31%   |
| 72      | 1        | 0.31%   |
| 55      | 1        | 0.31%   |
| 52      | 1        | 0.31%   |
| 42      | 1        | 0.31%   |
| 13      | 1        | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 115      | 36.51%  |
| 501-600        | 90       | 28.57%  |
| 351-400        | 33       | 10.48%  |
| 301-350        | 26       | 8.25%   |
| Unknown        | 17       | 5.4%    |
| 701-800        | 9        | 2.86%   |
| 601-700        | 8        | 2.54%   |
| 1001-1500      | 7        | 2.22%   |
| 801-900        | 4        | 1.27%   |
| 1501-2000      | 3        | 0.95%   |
| More than 2000 | 1        | 0.32%   |
| 201-300        | 1        | 0.32%   |
| 901-1000       | 1        | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 170      | 55.02%  |
| 5/4     | 52       | 16.83%  |
| 16/10   | 47       | 15.21%  |
| Unknown | 16       | 5.18%   |
| 4/3     | 11       | 3.56%   |
| 21/9    | 9        | 2.91%   |
| 3/2     | 3        | 0.97%   |
| 1.00    | 1        | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 124      | 38.75%  |
| 151-200        | 74       | 23.13%  |
| 141-150        | 34       | 10.63%  |
| 301-350        | 26       | 8.13%   |
| Unknown        | 17       | 5.31%   |
| 351-500        | 15       | 4.69%   |
| More than 1000 | 9        | 2.81%   |
| 251-300        | 7        | 2.19%   |
| 501-1000       | 7        | 2.19%   |
| 101-110        | 4        | 1.25%   |
| 111-120        | 2        | 0.63%   |
| 91-100         | 1        | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 210      | 68.4%   |
| 101-120 | 64       | 20.85%  |
| Unknown | 17       | 5.54%   |
| 1-50    | 11       | 3.58%   |
| 121-160 | 3        | 0.98%   |
| 161-240 | 2        | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 272      | 84.74%  |
| 2     | 34       | 10.59%  |
| 0     | 15       | 4.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 219      | 52.39%  |
| Qualcomm Atheros                       | 38       | 9.09%   |
| Nvidia                                 | 37       | 8.85%   |
| Intel                                  | 37       | 8.85%   |
| Ralink Technology                      | 18       | 4.31%   |
| TP-Link                                | 15       | 3.59%   |
| Marvell Technology Group               | 6        | 1.44%   |
| VIA Technologies                       | 5        | 1.2%    |
| D-Link                                 | 5        | 1.2%    |
| Qualcomm Atheros Communications        | 4        | 0.96%   |
| Huawei Technologies                    | 4        | 0.96%   |
| D-Link System                          | 4        | 0.96%   |
| Broadcom                               | 4        | 0.96%   |
| Xiaomi                                 | 3        | 0.72%   |
| Sundance Technology Inc / IC Plus      | 3        | 0.72%   |
| Ralink                                 | 2        | 0.48%   |
| IMC Networks                           | 2        | 0.48%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.24%   |
| Texas Instruments                      | 1        | 0.24%   |
| STMicroelectronics                     | 1        | 0.24%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.24%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.24%   |
| Motorola PCS                           | 1        | 0.24%   |
| Microsoft                              | 1        | 0.24%   |
| HTC (High Tech Computer)               | 1        | 0.24%   |
| HMD Global                             | 1        | 0.24%   |
| Davicom Semiconductor                  | 1        | 0.24%   |
| Broadcom Limited                       | 1        | 0.24%   |
| Aquantia                               | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 189      | 42%     |
| Nvidia MCP61 Ethernet                                                      | 26       | 5.78%   |
| Ralink MT7601U Wireless Adapter                                            | 14       | 3.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 9        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 9        | 2%      |
| Intel I211 Gigabit Network Connection                                      | 9        | 2%      |
| Intel Ethernet Connection (2) I219-V                                       | 9        | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 7        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 1.11%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 4        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4        | 0.89%   |
| Ralink RT5370 Wireless Adapter                                             | 4        | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 4        | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 4        | 0.89%   |
| Nvidia MCP65 Ethernet                                                      | 4        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 0.89%   |
| Intel 82579V Gigabit Network Connection                                    | 4        | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 0.67%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 3        | 0.67%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 3        | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 3        | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 3        | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 3        | 0.67%   |
| Qualcomm Atheros AR9271 802.11n                                            | 3        | 0.67%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 3        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 3        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.67%   |
| Nvidia MCP55 Ethernet                                                      | 3        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 0.67%   |
| Huawei ANA-NX9                                                             | 3        | 0.67%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                            | 3        | 0.67%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 2        | 0.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2        | 0.44%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                  | 2        | 0.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 2        | 0.44%   |
| TP-Link 802.11n NIC                                                        | 2        | 0.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 0.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2        | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2        | 0.44%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                  | 2        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 24       | 24%     |
| Ralink Technology               | 18       | 18%     |
| Qualcomm Atheros                | 16       | 16%     |
| TP-Link                         | 15       | 15%     |
| Intel                           | 9        | 9%      |
| D-Link                          | 5        | 5%      |
| Qualcomm Atheros Communications | 4        | 4%      |
| Ralink                          | 2        | 2%      |
| IMC Networks                    | 2        | 2%      |
| Texas Instruments               | 1        | 1%      |
| Microsoft                       | 1        | 1%      |
| D-Link System                   | 1        | 1%      |
| Broadcom Limited                | 1        | 1%      |
| Broadcom                        | 1        | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                      | 14       | 13.86%  |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 7        | 6.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 3.96%   |
| Ralink RT5370 Wireless Adapter                                                       | 4        | 3.96%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 3        | 2.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 2.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 3        | 2.97%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 3        | 2.97%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 2        | 1.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 1.98%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                            | 2        | 1.98%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 2        | 1.98%   |
| TP-Link 802.11n NIC                                                                  | 2        | 1.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 2        | 1.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.98%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 2        | 1.98%   |
| Realtek 802.11ac NIC                                                                 | 2        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 1.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 2        | 1.98%   |
| Intel Wi-Fi 6 AX200                                                                  | 2        | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 2        | 1.98%   |
| IMC Networks RTL8191S WLAN Adapter                                                   | 2        | 1.98%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 2        | 1.98%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                 | 2        | 1.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.99%   |
| TP-Link Archer T4UH v2 [Realtek RTL8812AU]                                           | 1        | 0.99%   |
| Texas Instruments ACX 111 54Mbps Wireless Interface                                  | 1        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1        | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.99%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                              | 1        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1        | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 0.99%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.99%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1        | 0.99%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 1        | 0.99%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 1        | 0.99%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 0.99%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 1        | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 213      | 62.46%  |
| Nvidia                                 | 37       | 10.85%  |
| Intel                                  | 34       | 9.97%   |
| Qualcomm Atheros                       | 23       | 6.74%   |
| Marvell Technology Group               | 6        | 1.76%   |
| VIA Technologies                       | 5        | 1.47%   |
| Xiaomi                                 | 3        | 0.88%   |
| Sundance Technology Inc / IC Plus      | 3        | 0.88%   |
| Huawei Technologies                    | 3        | 0.88%   |
| D-Link System                          | 3        | 0.88%   |
| Broadcom                               | 3        | 0.88%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.29%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.29%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.29%   |
| Motorola PCS                           | 1        | 0.29%   |
| HTC (High Tech Computer)               | 1        | 0.29%   |
| HMD Global                             | 1        | 0.29%   |
| Davicom Semiconductor                  | 1        | 0.29%   |
| Aquantia                               | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 189      | 54.47%  |
| Nvidia MCP61 Ethernet                                                      | 26       | 7.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 9        | 2.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 9        | 2.59%   |
| Intel I211 Gigabit Network Connection                                      | 9        | 2.59%   |
| Intel Ethernet Connection (2) I219-V                                       | 9        | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 1.44%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 4        | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 4        | 1.15%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 4        | 1.15%   |
| Nvidia MCP65 Ethernet                                                      | 4        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.15%   |
| Intel 82579V Gigabit Network Connection                                    | 4        | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 0.86%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 3        | 0.86%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 3        | 0.86%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 3        | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 3        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 3        | 0.86%   |
| Nvidia MCP55 Ethernet                                                      | 3        | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 3        | 0.86%   |
| Huawei ANA-NX9                                                             | 3        | 0.86%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                            | 3        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.58%   |
| Nvidia MCP67 Ethernet                                                      | 2        | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                    | 2        | 0.58%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.58%   |
| ZTE WCDMA MSM Spreadtrum Phone                                             | 1        | 0.29%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.29%   |
| Sony Ericsson Mobile AB Android                                            | 1        | 0.29%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                  | 1        | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.29%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.29%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.29%   |
| Nvidia MCP79 Ethernet                                                      | 1        | 0.29%   |
| Nvidia CK8S Ethernet Controller                                            | 1        | 0.29%   |
| Motorola PCS moto g pure                                                   | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 316      | 76.7%   |
| WiFi     | 94       | 22.82%  |
| Modem    | 2        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 264      | 80.49%  |
| WiFi     | 64       | 19.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 251      | 77.95%  |
| 2     | 63       | 19.57%  |
| 3     | 5        | 1.55%   |
| 0     | 3        | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 319      | 99.38%  |
| Yes  | 2        | 0.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 21       | 45.65%  |
| Intel                      | 7        | 15.22%  |
| ASUSTek Computer           | 5        | 10.87%  |
| Realtek Semiconductor      | 4        | 8.7%    |
| IMC Networks               | 3        | 6.52%   |
| Integrated System Solution | 2        | 4.35%   |
| Broadcom                   | 2        | 4.35%   |
| TP-Link                    | 1        | 2.17%   |
| Lite-On Technology         | 1        | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21       | 45.65%  |
| Realtek Bluetooth Radio                             | 4        | 8.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4.35%   |
| Intel Bluetooth wireless interface                  | 2        | 4.35%   |
| Intel AX200 Bluetooth                               | 2        | 4.35%   |
| Integrated System Solution Bluetooth Device         | 2        | 4.35%   |
| IMC Networks Bluetooth Radio                        | 2        | 4.35%   |
| ASUS Qualcomm Bluetooth 4.1                         | 2        | 4.35%   |
| ASUS Bluetooth Radio                                | 2        | 4.35%   |
| TP-Link UB500 Adapter                               | 1        | 2.17%   |
| Lite-On Bluetooth Device                            | 1        | 2.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1        | 2.17%   |
| Broadcom Bluetooth 2.0+eDR dongle                   | 1        | 2.17%   |
| Broadcom BCM2035B3 Bluetooth Adapter                | 1        | 2.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 165      | 32.23%  |
| Intel                            | 160      | 31.25%  |
| AMD                              | 129      | 25.2%   |
| C-Media Electronics              | 13       | 2.54%   |
| Creative Labs                    | 10       | 1.95%   |
| Logitech                         | 4        | 0.78%   |
| Texas Instruments                | 3        | 0.59%   |
| JMTek                            | 3        | 0.59%   |
| SteelSeries ApS                  | 2        | 0.39%   |
| M-Audio                          | 2        | 0.39%   |
| Yamaha                           | 1        | 0.2%    |
| VIA Technologies                 | 1        | 0.2%    |
| Tenx Technology                  | 1        | 0.2%    |
| Silicon Integrated Systems [SiS] | 1        | 0.2%    |
| ROCCAT                           | 1        | 0.2%    |
| Realtek Semiconductor            | 1        | 0.2%    |
| Plantronics                      | 1        | 0.2%    |
| Pixart Imaging                   | 1        | 0.2%    |
| NXP Semiconductors               | 1        | 0.2%    |
| iCreate Technologies             | 1        | 0.2%    |
| Huawei Technologies              | 1        | 0.2%    |
| GYROCOM C&C                      | 1        | 0.2%    |
| Generalplus Technology           | 1        | 0.2%    |
| ESS Technology                   | 1        | 0.2%    |
| Edifier Technology               | 1        | 0.2%    |
| Creative Technology              | 1        | 0.2%    |
| Conexant Systems                 | 1        | 0.2%    |
| BR36                             | 1        | 0.2%    |
| BEHRINGER International          | 1        | 0.2%    |
| ATI Technologies                 | 1        | 0.2%    |
| Unknown                          | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 48       | 8.22%   |
| Nvidia MCP61 High Definition Audio                                         | 31       | 5.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 23       | 3.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22       | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22       | 3.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18       | 3.08%   |
| AMD FCH Azalia Controller                                                  | 17       | 2.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 2.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 13       | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13       | 2.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 2.23%   |
| Nvidia High Definition Audio Controller                                    | 12       | 2.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12       | 2.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 12       | 2.05%   |
| Intel 200 Series PCH HD Audio                                              | 11       | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 1.54%   |
| Nvidia MCP65 High Definition Audio                                         | 8        | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 1.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8        | 1.37%   |
| Nvidia GK106 HDMI Audio Controller                                         | 8        | 1.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 1.37%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7        | 1.2%    |
| Nvidia GF116 High Definition Audio Controller                              | 7        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 1.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.03%   |
| Nvidia GK104 HDMI Audio Controller                                         | 6        | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6        | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.86%   |
| Nvidia GF106 High Definition Audio Controller                              | 5        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 0.86%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 123      | 41%     |
| Kingston            | 46       | 15.33%  |
| Crucial             | 29       | 9.67%   |
| SK hynix            | 16       | 5.33%   |
| Samsung Electronics | 13       | 4.33%   |
| Patriot             | 11       | 3.67%   |
| Micron Technology   | 10       | 3.33%   |
| G.Skill             | 8        | 2.67%   |
| GOODRAM             | 7        | 2.33%   |
| Corsair             | 7        | 2.33%   |
| Silicon Power       | 6        | 2%      |
| GeIL                | 3        | 1%      |
| A-DATA Technology   | 3        | 1%      |
| Unknown             | 3        | 1%      |
| Transcend           | 2        | 0.67%   |
| TakeMS              | 2        | 0.67%   |
| Elpida              | 2        | 0.67%   |
| Wilk Elektronik     | 1        | 0.33%   |
| Team                | 1        | 0.33%   |
| Qumo                | 1        | 0.33%   |
| Nanya Technology    | 1        | 0.33%   |
| Kllisre             | 1        | 0.33%   |
| Kingmax             | 1        | 0.33%   |
| ASint Technology    | 1        | 0.33%   |
| Apacer              | 1        | 0.33%   |
| AMD                 | 1        | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 7        | 2.08%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 6        | 1.78%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 6        | 1.78%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 5        | 1.48%   |
| Unknown RAM Module 2048MB DIMM DDR2                    | 5        | 1.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 4        | 1.19%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                 | 4        | 1.19%   |
| Unknown RAM Module 1024MB DIMM DDR2                    | 4        | 1.19%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 4        | 1.19%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 3        | 0.89%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 3        | 0.89%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                | 3        | 0.89%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 3        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s            | 3        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s             | 3        | 0.89%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 3        | 0.89%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 3        | 0.89%   |
| Unknown RAM Module 1024MB DIMM                         | 3        | 0.89%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 3        | 0.89%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 3        | 0.89%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 3        | 0.89%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3           | 3        | 0.89%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s  | 3        | 0.89%   |
| Unknown                                                | 3        | 0.89%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 2        | 0.59%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 2        | 0.59%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 2        | 0.59%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s             | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s            | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 800MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s           | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s           | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s            | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s            | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 2        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                | 2        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 89       | 32.48%  |
| Unknown | 64       | 23.36%  |
| DDR4    | 57       | 20.8%   |
| DDR2    | 35       | 12.77%  |
| SDRAM   | 23       | 8.39%   |
| DDR     | 6        | 2.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 260      | 96.65%  |
| SODIMM | 9        | 3.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 90       | 29.41%  |
| 2048  | 88       | 28.76%  |
| 8192  | 59       | 19.28%  |
| 1024  | 35       | 11.44%  |
| 16384 | 21       | 6.86%   |
| 512   | 9        | 2.94%   |
| 256   | 2        | 0.65%   |
| 32768 | 1        | 0.33%   |
| 16    | 1        | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 60       | 20.41%  |
| 1333    | 32       | 10.88%  |
| 800     | 29       | 9.86%   |
| Unknown | 26       | 8.84%   |
| 2400    | 20       | 6.8%    |
| 667     | 16       | 5.44%   |
| 400     | 11       | 3.74%   |
| 3600    | 10       | 3.4%    |
| 3200    | 10       | 3.4%    |
| 1066    | 10       | 3.4%    |
| 2133    | 8        | 2.72%   |
| 533     | 8        | 2.72%   |
| 3466    | 6        | 2.04%   |
| 2667    | 5        | 1.7%    |
| 1866    | 5        | 1.7%    |
| 1867    | 4        | 1.36%   |
| 333     | 4        | 1.36%   |
| 1067    | 3        | 1.02%   |
| 49926   | 2        | 0.68%   |
| 3733    | 2        | 0.68%   |
| 3400    | 2        | 0.68%   |
| 2666    | 2        | 0.68%   |
| 1800    | 2        | 0.68%   |
| 266     | 2        | 0.68%   |
| 3866    | 1        | 0.34%   |
| 3800    | 1        | 0.34%   |
| 3007    | 1        | 0.34%   |
| 3000    | 1        | 0.34%   |
| 2733    | 1        | 0.34%   |
| 2187    | 1        | 0.34%   |
| 2134    | 1        | 0.34%   |
| 2048    | 1        | 0.34%   |
| 1648    | 1        | 0.34%   |
| 1639    | 1        | 0.34%   |
| 792     | 1        | 0.34%   |
| 666     | 1        | 0.34%   |
| 200     | 1        | 0.34%   |
| 133     | 1        | 0.34%   |
| 66      | 1        | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Canon                 | 6        | 33.33%  |
| Hewlett-Packard       | 5        | 27.78%  |
| Seiko Epson           | 4        | 22.22%  |
| Samsung Electronics   | 1        | 5.56%   |
| QinHeng Electronics   | 1        | 5.56%   |
| Lexmark International | 1        | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Canon LBP6030w/6018w              | 2        | 10.53%  |
| Seiko Epson M100 Series           | 1        | 5.26%   |
| Seiko Epson L805 Series           | 1        | 5.26%   |
| Seiko Epson L220 Series           | 1        | 5.26%   |
| Seiko Epson L1250 Series          | 1        | 5.26%   |
| Samsung SCX-4200 series           | 1        | 5.26%   |
| QinHeng CH340S                    | 1        | 5.26%   |
| Lexmark International Z35 Printer | 1        | 5.26%   |
| HP LaserJet P2055 series          | 1        | 5.26%   |
| HP LaserJet P1006                 | 1        | 5.26%   |
| HP LaserJet P1005                 | 1        | 5.26%   |
| HP LaserJet 1300                  | 1        | 5.26%   |
| HP DeskJet 840c                   | 1        | 5.26%   |
| Canon MF4410                      | 1        | 5.26%   |
| Canon MF4010 series               | 1        | 5.26%   |
| Canon MF3010                      | 1        | 5.26%   |
| Canon LBP6020                     | 1        | 5.26%   |
| Canon G1000 series                | 1        | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 4        | 66.67%  |
| Ultima Electronics | 1        | 16.67%  |
| Seiko Epson        | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 16.67%  |
| Seiko Epson Stylus Photo RX500/510                                                    | 1        | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1        | 16.67%  |
| Canon CanoScan LiDE 600F                                                              | 1        | 16.67%  |
| Canon CanoScan LiDE 60                                                                | 1        | 16.67%  |
| Canon CanoScan LIDE 25                                                                | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 29       | 40.28%  |
| Z-Star Microelectronics     | 12       | 16.67%  |
| Microdia                    | 6        | 8.33%   |
| Realtek Semiconductor       | 4        | 5.56%   |
| Microsoft                   | 3        | 4.17%   |
| lihappe8                    | 3        | 4.17%   |
| Cubeternet                  | 3        | 4.17%   |
| Aveo Technology             | 3        | 4.17%   |
| Silicon Motion              | 1        | 1.39%   |
| Samsung Electronics         | 1        | 1.39%   |
| Nokia Mobile Phones         | 1        | 1.39%   |
| KYE Systems (Mouse Systems) | 1        | 1.39%   |
| IMC Networks                | 1        | 1.39%   |
| GEMBIRD                     | 1        | 1.39%   |
| Fly                         | 1        | 1.39%   |
| Arkmicro Technologies       | 1        | 1.39%   |
| Alcor Micro                 | 1        | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 13       | 18.06%  |
| Z-Star A4 TECH USB2.0 PC Camera J                  | 5        | 6.94%   |
| Logitech Webcam C310                               | 5        | 6.94%   |
| Z-Star Venus USB2.0 Camera                         | 4        | 5.56%   |
| Microdia Camera                                    | 4        | 5.56%   |
| Logitech Webcam C210                               | 3        | 4.17%   |
| lihappe8 USB 2.0 Camera                            | 3        | 4.17%   |
| Z-Star Vimicro USB Camera (Altair)                 | 2        | 2.78%   |
| Realtek FULL HD 1080P Webcam                       | 2        | 2.78%   |
| Microdia USB 2.0 Camera                            | 2        | 2.78%   |
| Logitech HD Pro Webcam C920                        | 2        | 2.78%   |
| Cubeternet USB2.0 Camera                           | 2        | 2.78%   |
| Aveo USB2.0 Camera                                 | 2        | 2.78%   |
| Z-Star A4 TECH HD PC Camera                        | 1        | 1.39%   |
| Silicon Motion Silicon Motion Camera               | 1        | 1.39%   |
| Samsung Galaxy A5 (MTP)                            | 1        | 1.39%   |
| Realtek USB Video device                           | 1        | 1.39%   |
| Realtek USB Camera                                 | 1        | 1.39%   |
| Nokia Mobile Phones Lumia 620/920                  | 1        | 1.39%   |
| Microsoft LifeCam Studio                           | 1        | 1.39%   |
| Microsoft LifeCam NX-6000                          | 1        | 1.39%   |
| Microsoft LifeCam Cinema                           | 1        | 1.39%   |
| Logitech Webcam C200                               | 1        | 1.39%   |
| Logitech Webcam C170                               | 1        | 1.39%   |
| Logitech Webcam C110                               | 1        | 1.39%   |
| Logitech Quickcam 3000 For Business                | 1        | 1.39%   |
| Logitech HD Webcam C510                            | 1        | 1.39%   |
| Logitech BRIO Ultra HD Webcam                      | 1        | 1.39%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 1.39%   |
| IMC Networks USB2.0 UVC HD Webcam                  | 1        | 1.39%   |
| GEMBIRD USB2.0 PC CAMERA                           | 1        | 1.39%   |
| Fly Life Jet                                       | 1        | 1.39%   |
| Cubeternet GL-UPC822 UVC WebCam                    | 1        | 1.39%   |
| Aveo Camera                                        | 1        | 1.39%   |
| Arkmicro USB2.0 PC CAMERA                          | 1        | 1.39%   |
| Alcor Micro USB 2.0 Camera                         | 1        | 1.39%   |

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
| 0     | 290      | 88.15%  |
| 1     | 38       | 11.55%  |
| 3     | 1        | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 65%     |
| Net/wireless             | 5        | 12.5%   |
| Sound                    | 2        | 5%      |
| Multimedia controller    | 2        | 5%      |
| Communication controller | 2        | 5%      |
| Camera                   | 2        | 5%      |
| Bluetooth                | 1        | 2.5%    |

