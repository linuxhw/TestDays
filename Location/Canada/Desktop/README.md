Linux in Canada - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

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

Total: 3368

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 0AACh                       | [f41abcf7f9](https://linux-hardware.org/?probe=f41abcf7f9) | Feb 01, 2023 |
| Dell          | 09KPNV A01                  | [5dcda0d3e5](https://linux-hardware.org/?probe=5dcda0d3e5) | Feb 01, 2023 |
| ASUSTek       | Z87-A                       | [1b880dbac2](https://linux-hardware.org/?probe=1b880dbac2) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| Dell          | 0PU052                      | [d2f241353d](https://linux-hardware.org/?probe=d2f241353d) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| HP            | 0AACh                       | [32961ffb11](https://linux-hardware.org/?probe=32961ffb11) | Jan 31, 2023 |
| HP            | 0AACh                       | [94baf3c57c](https://linux-hardware.org/?probe=94baf3c57c) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [d59770af38](https://linux-hardware.org/?probe=d59770af38) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [3a5ae3d1e8](https://linux-hardware.org/?probe=3a5ae3d1e8) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| MSI           | 870-G45                     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| Dell          | 0NW6H5 A00                  | [6296345ebb](https://linux-hardware.org/?probe=6296345ebb) | Jan 31, 2023 |
| HP            | 339A                        | [e3078cd4d7](https://linux-hardware.org/?probe=e3078cd4d7) | Jan 31, 2023 |
| ASUSTek       | PRIME B360M-A               | [1196b501d5](https://linux-hardware.org/?probe=1196b501d5) | Jan 31, 2023 |
| ASUSTek       | P8H77-V LE                  | [9edd1a1969](https://linux-hardware.org/?probe=9edd1a1969) | Jan 30, 2023 |
| Intel         | DQ77MK AAG39642-500         | [3e004045f7](https://linux-hardware.org/?probe=3e004045f7) | Jan 30, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [cbfcb68cc6](https://linux-hardware.org/?probe=cbfcb68cc6) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [f0000c6ae7](https://linux-hardware.org/?probe=f0000c6ae7) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | B150M-C                     | [6eb1a5b38e](https://linux-hardware.org/?probe=6eb1a5b38e) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [9f2e4066f6](https://linux-hardware.org/?probe=9f2e4066f6) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [f2bf9c3c82](https://linux-hardware.org/?probe=f2bf9c3c82) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [2d2e42ae23](https://linux-hardware.org/?probe=2d2e42ae23) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| ASUSTek       | PRIME Z590-A                | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Dell          | 057FFP A01                  | [ec0e3da69d](https://linux-hardware.org/?probe=ec0e3da69d) | Jan 27, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [06c6af6032](https://linux-hardware.org/?probe=06c6af6032) | Jan 27, 2023 |
| ASUSTek       | P5K                         | [6d496e6965](https://linux-hardware.org/?probe=6d496e6965) | Jan 27, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c7e2bde422](https://linux-hardware.org/?probe=c7e2bde422) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [38e4843e09](https://linux-hardware.org/?probe=38e4843e09) | Jan 27, 2023 |
| Gigabyte      | GA-MA770-UD3                | [6766a92ee5](https://linux-hardware.org/?probe=6766a92ee5) | Jan 27, 2023 |
| HP            | Compaq 8200 Elite SFF PC    | [73f629ca61](https://linux-hardware.org/?probe=73f629ca61) | Jan 27, 2023 |
| MSI           | X99A SLI PLUS               | [931a186515](https://linux-hardware.org/?probe=931a186515) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | Z87-A                       | [755bed02ff](https://linux-hardware.org/?probe=755bed02ff) | Jan 25, 2023 |
| ASUSTek       | Z87-A                       | [6ccfafe0d6](https://linux-hardware.org/?probe=6ccfafe0d6) | Jan 24, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [0300fb4b9a](https://linux-hardware.org/?probe=0300fb4b9a) | Jan 24, 2023 |
| ASUSTek       | Z87-PRO                     | [ea0a73ca90](https://linux-hardware.org/?probe=ea0a73ca90) | Jan 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [610ffedb4c](https://linux-hardware.org/?probe=610ffedb4c) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASUSTek       | Z87-PRO                     | [8bbff4abbd](https://linux-hardware.org/?probe=8bbff4abbd) | Jan 24, 2023 |
| HP            | 339A                        | [a2784a6575](https://linux-hardware.org/?probe=a2784a6575) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | 990FX Killer                | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| ASUSTek       | P5K                         | [dc5b823cb5](https://linux-hardware.org/?probe=dc5b823cb5) | Jan 22, 2023 |
| ASUSTek       | P8P67 LE                    | [6afc30df3b](https://linux-hardware.org/?probe=6afc30df3b) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| Alienware     | 0N43JM A00                  | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| ASUSTek       | PRIME X570-P                | [8af55733d7](https://linux-hardware.org/?probe=8af55733d7) | Jan 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9a99559833](https://linux-hardware.org/?probe=9a99559833) | Jan 18, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [d173b719da](https://linux-hardware.org/?probe=d173b719da) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| ASUSTek       | P5K-E                       | [2b7ce8a40b](https://linux-hardware.org/?probe=2b7ce8a40b) | Jan 17, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [c5387e7fd9](https://linux-hardware.org/?probe=c5387e7fd9) | Jan 17, 2023 |
| Foxconn       | ALOE                        | [0b3564ef16](https://linux-hardware.org/?probe=0b3564ef16) | Jan 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| MSI           | 990FXA-GD80                 | [bbddcc3653](https://linux-hardware.org/?probe=bbddcc3653) | Jan 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9b1e965bca](https://linux-hardware.org/?probe=9b1e965bca) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| ASRock        | A320M-HDV R4.0              | [f7422d49df](https://linux-hardware.org/?probe=f7422d49df) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| Dell          | 0WK833                      | [100d6694e5](https://linux-hardware.org/?probe=100d6694e5) | Jan 15, 2023 |
| ASUSTek       | Crosshair IV Formula        | [227b58bf8f](https://linux-hardware.org/?probe=227b58bf8f) | Jan 15, 2023 |
| ASUSTek       | Crosshair IV Formula        | [23748f30aa](https://linux-hardware.org/?probe=23748f30aa) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | P5B-VM                      | [53b563ef2f](https://linux-hardware.org/?probe=53b563ef2f) | Jan 15, 2023 |
| Dell          | 0UW457 A04                  | [0c637493cc](https://linux-hardware.org/?probe=0c637493cc) | Jan 15, 2023 |
| ASUSTek       | P8H61-M LE/CSM              | [06aff9f10a](https://linux-hardware.org/?probe=06aff9f10a) | Jan 14, 2023 |
| MSI           | X99A SLI PLUS               | [4ab9753ab5](https://linux-hardware.org/?probe=4ab9753ab5) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| Lenovo        | ThinkCentre XXXX 7360EHF    | [fdfe8c5881](https://linux-hardware.org/?probe=fdfe8c5881) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Acer          | Aspire X1800                | [16f6ad749f](https://linux-hardware.org/?probe=16f6ad749f) | Jan 13, 2023 |
| Dell          | 0UW457 A04                  | [4c5689de9c](https://linux-hardware.org/?probe=4c5689de9c) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| Acer          | Aspire X1800                | [929228726d](https://linux-hardware.org/?probe=929228726d) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | [da5cb78b32](https://linux-hardware.org/?probe=da5cb78b32) | Jan 12, 2023 |
| ASUSTek       | M3N78-VM                    | [dad2489f95](https://linux-hardware.org/?probe=dad2489f95) | Jan 12, 2023 |
| ASUSTek       | P5K                         | [ec9ba21c49](https://linux-hardware.org/?probe=ec9ba21c49) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASRockRack    | E3C246D4U2-2T               | [354d25ae30](https://linux-hardware.org/?probe=354d25ae30) | Jan 12, 2023 |
| Acer          | Aspire M3450                | [0ed84a21b2](https://linux-hardware.org/?probe=0ed84a21b2) | Jan 12, 2023 |
| ASUSTek       | G11CD                       | [f39178befb](https://linux-hardware.org/?probe=f39178befb) | Jan 12, 2023 |
| Dell          | 0DXJD9 A01                  | [78549912fa](https://linux-hardware.org/?probe=78549912fa) | Jan 12, 2023 |
| ECS           | A55F-M2                     | [b891de98a1](https://linux-hardware.org/?probe=b891de98a1) | Jan 11, 2023 |
| ASUSTek       | Z97-E/USB                   | [b4b3e05975](https://linux-hardware.org/?probe=b4b3e05975) | Jan 11, 2023 |
| HP            | 18E4                        | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [1705a3f042](https://linux-hardware.org/?probe=1705a3f042) | Jan 11, 2023 |
| HP            | 18E4                        | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 8433 11                     | [2036bb2c1a](https://linux-hardware.org/?probe=2036bb2c1a) | Jan 10, 2023 |
| ASUSTek       | P5K                         | [64c746ef0b](https://linux-hardware.org/?probe=64c746ef0b) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | [66ffdd11c5](https://linux-hardware.org/?probe=66ffdd11c5) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | [0a2fd6c8e7](https://linux-hardware.org/?probe=0a2fd6c8e7) | Jan 10, 2023 |
| ASUSTek       | P7H55-M PRO                 | [f2895e4b94](https://linux-hardware.org/?probe=f2895e4b94) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Dell          | 084J0R A00                  | [7aaeb8fbfc](https://linux-hardware.org/?probe=7aaeb8fbfc) | Jan 08, 2023 |
| HP            | 2B05                        | [a6f3a8c157](https://linux-hardware.org/?probe=a6f3a8c157) | Jan 08, 2023 |
| Gigabyte      | B450 AORUS M                | [e8e8ca3959](https://linux-hardware.org/?probe=e8e8ca3959) | Jan 08, 2023 |
| Gigabyte      | H81M-S2PV                   | [2dfeda8d20](https://linux-hardware.org/?probe=2dfeda8d20) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| ASRock        | H470M-STX                   | [60b8fb9dc4](https://linux-hardware.org/?probe=60b8fb9dc4) | Jan 07, 2023 |
| ASUSTek       | M4A785-M                    | [be50406f89](https://linux-hardware.org/?probe=be50406f89) | Jan 07, 2023 |
| ASUSTek       | Z97-C                       | [2b61136e8d](https://linux-hardware.org/?probe=2b61136e8d) | Jan 07, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [1720ed7ed6](https://linux-hardware.org/?probe=1720ed7ed6) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1608711aa0](https://linux-hardware.org/?probe=1608711aa0) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [f9f6df3b14](https://linux-hardware.org/?probe=f9f6df3b14) | Jan 06, 2023 |
| Dell          | 096JG8 A01                  | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| ASUSTek       | P5WD2-E Premium             | [c97e28eb76](https://linux-hardware.org/?probe=c97e28eb76) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [0ff94735bd](https://linux-hardware.org/?probe=0ff94735bd) | Jan 04, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [872a58377f](https://linux-hardware.org/?probe=872a58377f) | Jan 04, 2023 |
| HP            | 1998                        | [7c067688db](https://linux-hardware.org/?probe=7c067688db) | Jan 04, 2023 |
| HP            | 1998                        | [1eb07196f7](https://linux-hardware.org/?probe=1eb07196f7) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| Dell          | 0M9KCM A02                  | [dc9d77448b](https://linux-hardware.org/?probe=dc9d77448b) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| Pegatron      | 2ACF                        | [50da80ab44](https://linux-hardware.org/?probe=50da80ab44) | Jan 04, 2023 |
| Lenovo        | MAHOBAY No DPK              | [b829ec9d52](https://linux-hardware.org/?probe=b829ec9d52) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| HP            | 0AACh                       | [216ba22b5a](https://linux-hardware.org/?probe=216ba22b5a) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| HP            | 0AACh                       | [0730634b36](https://linux-hardware.org/?probe=0730634b36) | Jan 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | [f252f31761](https://linux-hardware.org/?probe=f252f31761) | Jan 01, 2023 |
| MSI           | PRO B550-VC                 | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [b79de349a9](https://linux-hardware.org/?probe=b79de349a9) | Jan 01, 2023 |
| HP            | 18E4                        | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| HP            | 18E4                        | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Foxconn       | 2ADA                        | [92ce347d5f](https://linux-hardware.org/?probe=92ce347d5f) | Dec 31, 2022 |
| Dell          | 0XPDFK A01                  | [37d47ff0dc](https://linux-hardware.org/?probe=37d47ff0dc) | Dec 30, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [4f3bc75747](https://linux-hardware.org/?probe=4f3bc75747) | Dec 30, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [e0f8b8c7b9](https://linux-hardware.org/?probe=e0f8b8c7b9) | Dec 30, 2022 |
| ASUSTek       | PRIME X399-A                | [d8ae46ad2b](https://linux-hardware.org/?probe=d8ae46ad2b) | Dec 30, 2022 |
| Dell          | 0UW457 A04                  | [047e7036d4](https://linux-hardware.org/?probe=047e7036d4) | Dec 29, 2022 |
| Dell          | 0VRWRC A00                  | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| ASUSTek       | M4N72-E                     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| ASUSTek       | PRIME X570-P                | [fba6e6e090](https://linux-hardware.org/?probe=fba6e6e090) | Dec 27, 2022 |
| Acer          | Aspire M3970                | [c2232f44d6](https://linux-hardware.org/?probe=c2232f44d6) | Dec 27, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [bfc68f7816](https://linux-hardware.org/?probe=bfc68f7816) | Dec 27, 2022 |
| HP            | 3397                        | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| Gigabyte      | GA-970A-D3                  | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [7b965d8da8](https://linux-hardware.org/?probe=7b965d8da8) | Dec 25, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | [61be8271df](https://linux-hardware.org/?probe=61be8271df) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [dc6cc81a73](https://linux-hardware.org/?probe=dc6cc81a73) | Dec 24, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [7fe5933133](https://linux-hardware.org/?probe=7fe5933133) | Dec 23, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [723811132a](https://linux-hardware.org/?probe=723811132a) | Dec 23, 2022 |
| Dell          | 0T10XW A00                  | [b8f7268dcf](https://linux-hardware.org/?probe=b8f7268dcf) | Dec 22, 2022 |
| Gigabyte      | B75M-D3H                    | [77bf96f401](https://linux-hardware.org/?probe=77bf96f401) | Dec 20, 2022 |
| ASUSTek       | P8P67 PRO                   | [51c1da3d29](https://linux-hardware.org/?probe=51c1da3d29) | Dec 20, 2022 |
| Supermicro    | X9DR3-F                     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| HP            | 18E7                        | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| MSI           | H81M-E34                    | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | [a5f6a25d72](https://linux-hardware.org/?probe=a5f6a25d72) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | [2b955ca3b3](https://linux-hardware.org/?probe=2b955ca3b3) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| Alienware     | 02XRCM A02                  | [ece4e302f1](https://linux-hardware.org/?probe=ece4e302f1) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a0f5be3bf](https://linux-hardware.org/?probe=2a0f5be3bf) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASUSTek       | M51BC                       | [3b744c3d0c](https://linux-hardware.org/?probe=3b744c3d0c) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| MSI           | Z170A PC MATE               | [e6f5c32627](https://linux-hardware.org/?probe=e6f5c32627) | Dec 15, 2022 |
| HP            | 18E4                        | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| MSI           | A88X-G45 GAMING             | [7b92a8398f](https://linux-hardware.org/?probe=7b92a8398f) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| Dell          | 0R6PCT A01                  | [c0c28e38d0](https://linux-hardware.org/?probe=c0c28e38d0) | Dec 14, 2022 |
| ASUSTek       | PRIME Z590-A                | [2d1d10e6b9](https://linux-hardware.org/?probe=2d1d10e6b9) | Dec 14, 2022 |
| MSI           | B250 GAMING M3              | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| HP            | 18E4                        | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| ASUSTek       | P8H77-M                     | [32901a2ae5](https://linux-hardware.org/?probe=32901a2ae5) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | [c3ad967780](https://linux-hardware.org/?probe=c3ad967780) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | [a6ca46d45a](https://linux-hardware.org/?probe=a6ca46d45a) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | [4059f02137](https://linux-hardware.org/?probe=4059f02137) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | [f89f577056](https://linux-hardware.org/?probe=f89f577056) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | [667ee69b40](https://linux-hardware.org/?probe=667ee69b40) | Dec 13, 2022 |
| Acer          | Aspire T3-100               | [918ad73eb1](https://linux-hardware.org/?probe=918ad73eb1) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e583774bc6](https://linux-hardware.org/?probe=e583774bc6) | Dec 13, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | [51ddf66bff](https://linux-hardware.org/?probe=51ddf66bff) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [51263f4a54](https://linux-hardware.org/?probe=51263f4a54) | Dec 11, 2022 |
| ASUSTek       | P5K                         | [7cef6adb1e](https://linux-hardware.org/?probe=7cef6adb1e) | Dec 11, 2022 |
| HP            | 8860 A                      | [c039452bd4](https://linux-hardware.org/?probe=c039452bd4) | Dec 11, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [1a83431b77](https://linux-hardware.org/?probe=1a83431b77) | Dec 11, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [4e829bc252](https://linux-hardware.org/?probe=4e829bc252) | Dec 10, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | [fc58d30c61](https://linux-hardware.org/?probe=fc58d30c61) | Dec 10, 2022 |
| HP            | 18E4                        | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| ASUSTek       | P5K                         | [9db010e6f2](https://linux-hardware.org/?probe=9db010e6f2) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e61897fa56](https://linux-hardware.org/?probe=e61897fa56) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [b2aa17a680](https://linux-hardware.org/?probe=b2aa17a680) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [416ad70d66](https://linux-hardware.org/?probe=416ad70d66) | Dec 08, 2022 |
| Lenovo        | Annapurna CRB NOK           | [548e2f6cd0](https://linux-hardware.org/?probe=548e2f6cd0) | Dec 08, 2022 |
| ASUSTek       | P5K                         | [832ef547a1](https://linux-hardware.org/?probe=832ef547a1) | Dec 08, 2022 |
| Gigabyte      | 990FXA-UD3                  | [6ff5feb92c](https://linux-hardware.org/?probe=6ff5feb92c) | Dec 06, 2022 |
| MSI           | B150M MORTAR                | [9a87b35e1c](https://linux-hardware.org/?probe=9a87b35e1c) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [c0f26cbe79](https://linux-hardware.org/?probe=c0f26cbe79) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| HP            | 18E4                        | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | [cda3502c1e](https://linux-hardware.org/?probe=cda3502c1e) | Dec 06, 2022 |
| HP            | 18E4                        | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1421946e24](https://linux-hardware.org/?probe=1421946e24) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b9d333782f](https://linux-hardware.org/?probe=b9d333782f) | Dec 05, 2022 |
| ASRock        | 970M Pro3                   | [8fc8a7552b](https://linux-hardware.org/?probe=8fc8a7552b) | Dec 04, 2022 |
| ASUSTek       | P8H67-M PRO                 | [a57440ec11](https://linux-hardware.org/?probe=a57440ec11) | Dec 04, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [831d9e3a99](https://linux-hardware.org/?probe=831d9e3a99) | Dec 04, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [6ac526e02a](https://linux-hardware.org/?probe=6ac526e02a) | Dec 04, 2022 |
| Dell          | 0DFRFW A01                  | [a3ee070c79](https://linux-hardware.org/?probe=a3ee070c79) | Dec 03, 2022 |
| Dell          | 0DFRFW A01                  | [45543562ff](https://linux-hardware.org/?probe=45543562ff) | Dec 03, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | [bee1776fbf](https://linux-hardware.org/?probe=bee1776fbf) | Dec 03, 2022 |
| HP            | 1494                        | [d9dd7b9fc1](https://linux-hardware.org/?probe=d9dd7b9fc1) | Dec 03, 2022 |
| Pegatron      | 2AC2                        | [29d43d4af8](https://linux-hardware.org/?probe=29d43d4af8) | Dec 03, 2022 |
| ASUSTek       | P7P55D PRO                  | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [3c05de2bb5](https://linux-hardware.org/?probe=3c05de2bb5) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [17e6d4dbb5](https://linux-hardware.org/?probe=17e6d4dbb5) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [0e0ed0822c](https://linux-hardware.org/?probe=0e0ed0822c) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [adeb151478](https://linux-hardware.org/?probe=adeb151478) | Dec 02, 2022 |
| HP            | 18E4                        | [b0254c66c7](https://linux-hardware.org/?probe=b0254c66c7) | Dec 01, 2022 |
| Pegatron      | 2AC2                        | [3d92c6cbc8](https://linux-hardware.org/?probe=3d92c6cbc8) | Dec 01, 2022 |
| Dell          | 0WWJRX A00                  | [83ef480c7d](https://linux-hardware.org/?probe=83ef480c7d) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| ASUSTek       | P8H77-M                     | [4aafb7e858](https://linux-hardware.org/?probe=4aafb7e858) | Nov 29, 2022 |
| ASRock        | Z77 Extreme3                | [e473c1c45c](https://linux-hardware.org/?probe=e473c1c45c) | Nov 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [cc75562371](https://linux-hardware.org/?probe=cc75562371) | Nov 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [a6ea0d5259](https://linux-hardware.org/?probe=a6ea0d5259) | Nov 29, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [66525e5501](https://linux-hardware.org/?probe=66525e5501) | Nov 29, 2022 |
| Dell          | 09WH54 A00                  | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [0149d91a8d](https://linux-hardware.org/?probe=0149d91a8d) | Nov 28, 2022 |
| HP            | 212B                        | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [cbd36eefe1](https://linux-hardware.org/?probe=cbd36eefe1) | Nov 27, 2022 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [508e04de6e](https://linux-hardware.org/?probe=508e04de6e) | Nov 27, 2022 |
| HP            | 18E4                        | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| HP            | 1589                        | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| Dell          | 0VRWRC A00                  | [26bfa13122](https://linux-hardware.org/?probe=26bfa13122) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Dell          | 088DT1 A01                  | [eb243079e8](https://linux-hardware.org/?probe=eb243079e8) | Nov 25, 2022 |
| HP            | 18E4                        | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| Dell          | 0Y2MRG A00                  | [581cd43952](https://linux-hardware.org/?probe=581cd43952) | Nov 24, 2022 |
| ASUSTek       | Z87-PRO                     | [95ebdc23ea](https://linux-hardware.org/?probe=95ebdc23ea) | Nov 24, 2022 |
| HP            | 339A                        | [13c1a4b520](https://linux-hardware.org/?probe=13c1a4b520) | Nov 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [0e778da8b6](https://linux-hardware.org/?probe=0e778da8b6) | Nov 22, 2022 |
| ASUSTek       | P8H67-M PRO                 | [d7f34b8543](https://linux-hardware.org/?probe=d7f34b8543) | Nov 21, 2022 |
| HP            | 18E4                        | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| ASUSTek       | M2N-E                       | [150565ed00](https://linux-hardware.org/?probe=150565ed00) | Nov 20, 2022 |
| ASUSTek       | PRIME Z370-A                | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| Dell          | 0C522T A01                  | [7a475c6f79](https://linux-hardware.org/?probe=7a475c6f79) | Nov 19, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [ea98e803d1](https://linux-hardware.org/?probe=ea98e803d1) | Nov 18, 2022 |
| MSI           | MAG B550M MORTAR            | [57c6327e27](https://linux-hardware.org/?probe=57c6327e27) | Nov 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1d9ddf9f3](https://linux-hardware.org/?probe=d1d9ddf9f3) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [da04bee118](https://linux-hardware.org/?probe=da04bee118) | Nov 18, 2022 |
| ASUSTek       | P8H77-M LE                  | [42f0e4b33e](https://linux-hardware.org/?probe=42f0e4b33e) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| MSI           | B350M MORTAR                | [f85255857d](https://linux-hardware.org/?probe=f85255857d) | Nov 17, 2022 |
| HP            | 18E4                        | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Dell          | 09KPNV A01                  | [b21e07c887](https://linux-hardware.org/?probe=b21e07c887) | Nov 16, 2022 |
| ASRock        | B450M Pro4                  | [39aedb7818](https://linux-hardware.org/?probe=39aedb7818) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| MSI           | 870-G45                     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| ASUSTek       | PRIME H370-A                | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| Dell          | 0RY007                      | [84453b7c4b](https://linux-hardware.org/?probe=84453b7c4b) | Nov 15, 2022 |
| Dell          | 0RY007                      | [dc49babf5c](https://linux-hardware.org/?probe=dc49babf5c) | Nov 15, 2022 |
| ASRock        | Z77 Extreme3                | [1485faa2cc](https://linux-hardware.org/?probe=1485faa2cc) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [80cce966ce](https://linux-hardware.org/?probe=80cce966ce) | Nov 14, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [25df2f9dc5](https://linux-hardware.org/?probe=25df2f9dc5) | Nov 14, 2022 |
| ASUSTek       | P8P67 LE                    | [970f0b9990](https://linux-hardware.org/?probe=970f0b9990) | Nov 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [4788a2a91d](https://linux-hardware.org/?probe=4788a2a91d) | Nov 13, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [18b42b8ead](https://linux-hardware.org/?probe=18b42b8ead) | Nov 13, 2022 |
| HP            | 18E4                        | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [2d2cdbb40b](https://linux-hardware.org/?probe=2d2cdbb40b) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [632037506d](https://linux-hardware.org/?probe=632037506d) | Nov 12, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| ASRock        | Z77 Extreme3                | [d8638412d9](https://linux-hardware.org/?probe=d8638412d9) | Nov 09, 2022 |
| AZW           | Gemini T34                  | [b8aee41f46](https://linux-hardware.org/?probe=b8aee41f46) | Nov 08, 2022 |
| Unknown       | Unknown                     | [be28c34da3](https://linux-hardware.org/?probe=be28c34da3) | Nov 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [f18ccfd249](https://linux-hardware.org/?probe=f18ccfd249) | Nov 07, 2022 |
| HP            | 0B4Ch D                     | [4f7462e06e](https://linux-hardware.org/?probe=4f7462e06e) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Gigabyte      | B85M-D3H                    | [6491b1d525](https://linux-hardware.org/?probe=6491b1d525) | Nov 04, 2022 |
| HP            | 18E4                        | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| MSI           | 870-G45                     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [7255a61579](https://linux-hardware.org/?probe=7255a61579) | Nov 03, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [953e399168](https://linux-hardware.org/?probe=953e399168) | Nov 03, 2022 |
| ASRock        | Z270 Taichi                 | [60996cd2dc](https://linux-hardware.org/?probe=60996cd2dc) | Nov 02, 2022 |
| HP            | 18E4                        | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| Acer          | Aspire X1430                | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| HP            | 8054                        | [9e1b99d9bb](https://linux-hardware.org/?probe=9e1b99d9bb) | Nov 01, 2022 |
| ASUSTek       | Crosshair V Formula         | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| ASUSTek       | P8H77-M                     | [2ae72e7e22](https://linux-hardware.org/?probe=2ae72e7e22) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-201        | [b3403874f4](https://linux-hardware.org/?probe=b3403874f4) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-A                | [b1027d78bc](https://linux-hardware.org/?probe=b1027d78bc) | Oct 31, 2022 |
| ASUSTek       | PRIME H370-A                | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | [768d0e85c9](https://linux-hardware.org/?probe=768d0e85c9) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| ASUSTek       | PRIME A320I-K               | [91f4cd151f](https://linux-hardware.org/?probe=91f4cd151f) | Oct 29, 2022 |
| HP            | 18E4                        | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| Acer          | Aspire TC-710 V:1.1         | [b9c0f59afa](https://linux-hardware.org/?probe=b9c0f59afa) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| Gigabyte      | GA-990FXA-UD5               | [6faf6b40b1](https://linux-hardware.org/?probe=6faf6b40b1) | Oct 26, 2022 |
| Alienware     | 0PGRP5 A02                  | [126f440ca7](https://linux-hardware.org/?probe=126f440ca7) | Oct 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ce143b473f](https://linux-hardware.org/?probe=ce143b473f) | Oct 24, 2022 |
| ASRock        | Z97 Anniversary             | [9c94714d56](https://linux-hardware.org/?probe=9c94714d56) | Oct 24, 2022 |
| MSI           | B350M MORTAR                | [9312be9510](https://linux-hardware.org/?probe=9312be9510) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [3d217d0a43](https://linux-hardware.org/?probe=3d217d0a43) | Oct 23, 2022 |
| ASRock        | B550M Pro4                  | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [9042357a86](https://linux-hardware.org/?probe=9042357a86) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| HP            | 18E4                        | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [6be0c6ee5f](https://linux-hardware.org/?probe=6be0c6ee5f) | Oct 20, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [a753c7bd58](https://linux-hardware.org/?probe=a753c7bd58) | Oct 20, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [f275b2167f](https://linux-hardware.org/?probe=f275b2167f) | Oct 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [3c91e0c6ec](https://linux-hardware.org/?probe=3c91e0c6ec) | Oct 19, 2022 |
| Pegatron      | 2AD5                        | [9fb7d8bf7f](https://linux-hardware.org/?probe=9fb7d8bf7f) | Oct 17, 2022 |
| ASUSTek       | Rampage V EXTREME           | [ac8367f142](https://linux-hardware.org/?probe=ac8367f142) | Oct 17, 2022 |
| ASUSTek       | Rampage V EXTREME           | [8c187fa369](https://linux-hardware.org/?probe=8c187fa369) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [3f4c203116](https://linux-hardware.org/?probe=3f4c203116) | Oct 15, 2022 |
| HP            | 2B5B                        | [fc24a4bc99](https://linux-hardware.org/?probe=fc24a4bc99) | Oct 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f57f16d11b](https://linux-hardware.org/?probe=f57f16d11b) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [55e6578ade](https://linux-hardware.org/?probe=55e6578ade) | Oct 13, 2022 |
| Dell          | 0D735T A00                  | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [eca505496f](https://linux-hardware.org/?probe=eca505496f) | Oct 10, 2022 |
| Alienware     | 0NWN7M A00                  | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| ASRock        | B365M Pro4                  | [669c570a2e](https://linux-hardware.org/?probe=669c570a2e) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [11fb952122](https://linux-hardware.org/?probe=11fb952122) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| HP            | 18E4                        | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| Gigabyte      | Z370P D3-CF                 | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [c2193db5fb](https://linux-hardware.org/?probe=c2193db5fb) | Oct 09, 2022 |
| Dell          | 088DT1 A01                  | [0709f63ca7](https://linux-hardware.org/?probe=0709f63ca7) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [dfeb0c2791](https://linux-hardware.org/?probe=dfeb0c2791) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [60c519a7dd](https://linux-hardware.org/?probe=60c519a7dd) | Oct 07, 2022 |
| HP            | 18E4                        | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| Dell          | 082WXT A03                  | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| MSI           | B350M MORTAR                | [4e56098080](https://linux-hardware.org/?probe=4e56098080) | Oct 04, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [56fbace4f2](https://linux-hardware.org/?probe=56fbace4f2) | Oct 03, 2022 |
| ASRock        | Z77 Extreme3                | [c92633e1ee](https://linux-hardware.org/?probe=c92633e1ee) | Oct 01, 2022 |
| ASRock        | X570 Steel Legend           | [40e65e38cf](https://linux-hardware.org/?probe=40e65e38cf) | Sep 30, 2022 |
| HP            | 3398                        | [2f7b1d28b4](https://linux-hardware.org/?probe=2f7b1d28b4) | Sep 30, 2022 |
| HP            | 1496                        | [e89f06542b](https://linux-hardware.org/?probe=e89f06542b) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | [aa0eeeda6b](https://linux-hardware.org/?probe=aa0eeeda6b) | Sep 29, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| Acer          | Veriton X6610G              | [66733e59e2](https://linux-hardware.org/?probe=66733e59e2) | Sep 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [75c8af47c2](https://linux-hardware.org/?probe=75c8af47c2) | Sep 29, 2022 |
| MSI           | Z87-GD65 GAMING             | [fe6539c021](https://linux-hardware.org/?probe=fe6539c021) | Sep 28, 2022 |
| HP            | 212B                        | [38aa6e5478](https://linux-hardware.org/?probe=38aa6e5478) | Sep 28, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [45031620df](https://linux-hardware.org/?probe=45031620df) | Sep 27, 2022 |
| Gateway       | IPISB-VR                    | [21ee50eb69](https://linux-hardware.org/?probe=21ee50eb69) | Sep 24, 2022 |
| ASUSTek       | SABERTOOTH P67              | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| MSI           | 870-G45                     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| HP            | 8309                        | [118f235878](https://linux-hardware.org/?probe=118f235878) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3R                   | [920bf9a750](https://linux-hardware.org/?probe=920bf9a750) | Sep 22, 2022 |
| Lenovo        | 1052 NOK                    | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| Acer          | Aspire M3450                | [ff7d0a2394](https://linux-hardware.org/?probe=ff7d0a2394) | Sep 21, 2022 |
| ASRock        | Z77 Extreme3                | [deb21d492d](https://linux-hardware.org/?probe=deb21d492d) | Sep 21, 2022 |
| ASUSTek       | A68HM-K                     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H AC               | [9d26eb4243](https://linux-hardware.org/?probe=9d26eb4243) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| ASUSTek       | Z97-A                       | [d984474cba](https://linux-hardware.org/?probe=d984474cba) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| ASUSTek       | F2A85-V PRO                 | [943bb9e023](https://linux-hardware.org/?probe=943bb9e023) | Sep 19, 2022 |
| ASUSTek       | SABERTOOTH P67              | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | [06f5febda2](https://linux-hardware.org/?probe=06f5febda2) | Sep 19, 2022 |
| BESSTAR Te... | TH50                        | [916e9d7e5e](https://linux-hardware.org/?probe=916e9d7e5e) | Sep 18, 2022 |
| Unknown       | T3 MRD                      | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| MSI           | 870-G45                     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| MSI           | 870-G45                     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1b40e531b5](https://linux-hardware.org/?probe=1b40e531b5) | Sep 17, 2022 |
| Lenovo        | MAHOBAY NOK                 | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | LITHIUM                     | [3aab1aa49f](https://linux-hardware.org/?probe=3aab1aa49f) | Sep 16, 2022 |
| HP            | 1998                        | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [31f9854044](https://linux-hardware.org/?probe=31f9854044) | Sep 16, 2022 |
| AZW           | GK mini                     | [19b8b4dc85](https://linux-hardware.org/?probe=19b8b4dc85) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a4dad191d2](https://linux-hardware.org/?probe=a4dad191d2) | Sep 15, 2022 |
| IBT.ca (IB... | MI836                       | [a180af0292](https://linux-hardware.org/?probe=a180af0292) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| HP            | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [f614aa6ae7](https://linux-hardware.org/?probe=f614aa6ae7) | Sep 14, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | [fc1d1cb3bc](https://linux-hardware.org/?probe=fc1d1cb3bc) | Sep 14, 2022 |
| Dell          | 0DR845                      | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| HP            | 3031h                       | [9312c20d49](https://linux-hardware.org/?probe=9312c20d49) | Sep 13, 2022 |
| HP            | 3031h                       | [1bbfd867b0](https://linux-hardware.org/?probe=1bbfd867b0) | Sep 13, 2022 |
| Dell          | 0DR845                      | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| DFI           | HD631-Q87CRM                | [b7ed9b1d64](https://linux-hardware.org/?probe=b7ed9b1d64) | Sep 12, 2022 |
| ECS           | Nettle3                     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| HP            | 1998                        | [37cd896e72](https://linux-hardware.org/?probe=37cd896e72) | Sep 10, 2022 |
| HP            | 1998                        | [3da9c3ef8e](https://linux-hardware.org/?probe=3da9c3ef8e) | Sep 10, 2022 |
| ASRock        | B450M Pro4                  | [9ce6958b9c](https://linux-hardware.org/?probe=9ce6958b9c) | Sep 09, 2022 |
| IBT.ca (IB... | MI836                       | [6155d5bd47](https://linux-hardware.org/?probe=6155d5bd47) | Sep 09, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| MSI           | B350M PRO-VDH               | [e5067297e8](https://linux-hardware.org/?probe=e5067297e8) | Sep 07, 2022 |
| ASUSTek       | ET2040I                     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ab4f06e457](https://linux-hardware.org/?probe=ab4f06e457) | Sep 05, 2022 |
| ASUSTek       | Q170M-C                     | [6710f3ecd0](https://linux-hardware.org/?probe=6710f3ecd0) | Sep 04, 2022 |
| ASUSTek       | KCMA-D8                     | [df5fdfccf0](https://linux-hardware.org/?probe=df5fdfccf0) | Sep 04, 2022 |
| HP            | 2ADC                        | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Intel         | DQ67SW AAG12527-306         | [9ab6c11be2](https://linux-hardware.org/?probe=9ab6c11be2) | Sep 04, 2022 |
| MSI           | H81M-E34                    | [0fa7f79fdc](https://linux-hardware.org/?probe=0fa7f79fdc) | Sep 03, 2022 |
| Acer          | Aspire M3910                | [17c1079582](https://linux-hardware.org/?probe=17c1079582) | Sep 02, 2022 |
| Gigabyte      | GA-870A-UD3                 | [27840cf8d2](https://linux-hardware.org/?probe=27840cf8d2) | Sep 02, 2022 |
| Acer          | Aspire TC-605               | [fa13174432](https://linux-hardware.org/?probe=fa13174432) | Sep 02, 2022 |
| Dell          | 0R6PCT A01                  | [02af50752e](https://linux-hardware.org/?probe=02af50752e) | Sep 01, 2022 |
| Acer          | Aspire TC-605               | [fdc6b95d8b](https://linux-hardware.org/?probe=fdc6b95d8b) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a2878122de](https://linux-hardware.org/?probe=a2878122de) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [836d60c547](https://linux-hardware.org/?probe=836d60c547) | Sep 01, 2022 |
| ASRock        | B450M Pro4-F                | [d48b9efca4](https://linux-hardware.org/?probe=d48b9efca4) | Sep 01, 2022 |
| JGINYUE       | B85I PLUS V2.1              | [d171691ef3](https://linux-hardware.org/?probe=d171691ef3) | Aug 31, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [3ce9a33fed](https://linux-hardware.org/?probe=3ce9a33fed) | Aug 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [2adf8e9ff6](https://linux-hardware.org/?probe=2adf8e9ff6) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [505d987d1e](https://linux-hardware.org/?probe=505d987d1e) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| Intel         | DH87RL AAG74240-401         | [814718547c](https://linux-hardware.org/?probe=814718547c) | Aug 27, 2022 |
| HP            | 18E4                        | [13d5c6848a](https://linux-hardware.org/?probe=13d5c6848a) | Aug 24, 2022 |
| Dell          | 0F5C5X A00                  | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| Dell          | 0F5C5X A00                  | [5e62f9adde](https://linux-hardware.org/?probe=5e62f9adde) | Aug 24, 2022 |
| Dell          | 0YJPT1 A00                  | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | Z97-P                       | [bcd3bcb389](https://linux-hardware.org/?probe=bcd3bcb389) | Aug 22, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [5f90bb65a6](https://linux-hardware.org/?probe=5f90bb65a6) | Aug 21, 2022 |
| ASUSTek       | M4A78-E                     | [76028e78e9](https://linux-hardware.org/?probe=76028e78e9) | Aug 19, 2022 |
| Intel         | DH87RL AAG74240-401         | [ebc0328fe0](https://linux-hardware.org/?probe=ebc0328fe0) | Aug 19, 2022 |
| ASUSTek       | PRIME Z390-A                | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| Dell          | 054KM3 A01                  | [3f966fdafa](https://linux-hardware.org/?probe=3f966fdafa) | Aug 17, 2022 |
| Intel         | DH87RL AAG74240-401         | [a8c5b732f4](https://linux-hardware.org/?probe=a8c5b732f4) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [1ab8003e04](https://linux-hardware.org/?probe=1ab8003e04) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [2a3c6446e5](https://linux-hardware.org/?probe=2a3c6446e5) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Dell          | 0PC5F7 A03                  | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [239daef655](https://linux-hardware.org/?probe=239daef655) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| ASUSTek       | B85M-G                      | [b44e802677](https://linux-hardware.org/?probe=b44e802677) | Aug 14, 2022 |
| HP            | 805D                        | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| MSI           | MS-B9351                    | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| ASRock        | B450M Pro4                  | [286fd1791a](https://linux-hardware.org/?probe=286fd1791a) | Aug 14, 2022 |
| Dell          | 07PR60 A02                  | [7ed59c8c10](https://linux-hardware.org/?probe=7ed59c8c10) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| ASUSTek       | PRIME B550M-A               | [64e8ddf1c9](https://linux-hardware.org/?probe=64e8ddf1c9) | Aug 07, 2022 |
| Dell          | 0NV0M7 A02                  | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [dca6f9dfbd](https://linux-hardware.org/?probe=dca6f9dfbd) | Aug 06, 2022 |
| ASUSTek       | PRIME B450M-A               | [3b290b6c0b](https://linux-hardware.org/?probe=3b290b6c0b) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Biostar       | TA880GU3+                   | [323c68d80f](https://linux-hardware.org/?probe=323c68d80f) | Aug 03, 2022 |
| HP            | 339A                        | [27ddbfd51d](https://linux-hardware.org/?probe=27ddbfd51d) | Aug 03, 2022 |
| HP            | 8433 11                     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [80512402c0](https://linux-hardware.org/?probe=80512402c0) | Aug 02, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [4bd0f9e461](https://linux-hardware.org/?probe=4bd0f9e461) | Aug 02, 2022 |
| Dell          | 0GXM1W A01                  | [91d2f28256](https://linux-hardware.org/?probe=91d2f28256) | Aug 01, 2022 |
| Dell          | 0GXM1W A01                  | [ab895fc1a2](https://linux-hardware.org/?probe=ab895fc1a2) | Aug 01, 2022 |
| Apple         | Mac-F221BEC8                | [13cbc87486](https://linux-hardware.org/?probe=13cbc87486) | Jul 31, 2022 |
| ASUSTek       | PRIME Z490-A                | [a1923838e1](https://linux-hardware.org/?probe=a1923838e1) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [22b4bcc010](https://linux-hardware.org/?probe=22b4bcc010) | Jul 31, 2022 |
| EVGA          | 134-KS-E377                 | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Dell          | 0WMJ54 A01                  | [7682000c35](https://linux-hardware.org/?probe=7682000c35) | Jul 30, 2022 |
| HP            | 339A                        | [7f2505acd4](https://linux-hardware.org/?probe=7f2505acd4) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [38fae80720](https://linux-hardware.org/?probe=38fae80720) | Jul 29, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [a6237b3a28](https://linux-hardware.org/?probe=a6237b3a28) | Jul 29, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | [5a12531bf9](https://linux-hardware.org/?probe=5a12531bf9) | Jul 29, 2022 |
| ASUSTek       | G10DK                       | [70a71d84a6](https://linux-hardware.org/?probe=70a71d84a6) | Jul 28, 2022 |
| HP            | 18E6                        | [60d1a8e6da](https://linux-hardware.org/?probe=60d1a8e6da) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| Dell          | 05DN3X A00                  | [e4c1d0bdeb](https://linux-hardware.org/?probe=e4c1d0bdeb) | Jul 27, 2022 |
| Dell          | 0WMJ54 A01                  | [fc499e7600](https://linux-hardware.org/?probe=fc499e7600) | Jul 27, 2022 |
| Dell          | 042P49 A01                  | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [b61b6b5fa5](https://linux-hardware.org/?probe=b61b6b5fa5) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| Gateway       | DX4840                      | [0df8a716b1](https://linux-hardware.org/?probe=0df8a716b1) | Jul 24, 2022 |
| MSI           | 970 GAMING                  | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| Pegatron      | 2ACD                        | [c8ce65cd26](https://linux-hardware.org/?probe=c8ce65cd26) | Jul 23, 2022 |
| ASUSTek       | P8P67 PRO                   | [54e6e291bd](https://linux-hardware.org/?probe=54e6e291bd) | Jul 22, 2022 |
| Dell          | 0WMJ54 A01                  | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2e97c3de0b](https://linux-hardware.org/?probe=2e97c3de0b) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d567131bf9](https://linux-hardware.org/?probe=d567131bf9) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| HP            | 158B                        | [017875f5a5](https://linux-hardware.org/?probe=017875f5a5) | Jul 21, 2022 |
| Unknown       | T3 MRD                      | [afbe55b100](https://linux-hardware.org/?probe=afbe55b100) | Jul 20, 2022 |
| Dell          | 04Y8V0 A02                  | [f843e569ed](https://linux-hardware.org/?probe=f843e569ed) | Jul 20, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [0ce9af7993](https://linux-hardware.org/?probe=0ce9af7993) | Jul 20, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [6aac7a75e7](https://linux-hardware.org/?probe=6aac7a75e7) | Jul 18, 2022 |
| MSI           | MEG B550 UNIFY              | [d6ecbbbfda](https://linux-hardware.org/?probe=d6ecbbbfda) | Jul 17, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [ec770759cd](https://linux-hardware.org/?probe=ec770759cd) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | [38ebe8f368](https://linux-hardware.org/?probe=38ebe8f368) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | [129bcce64f](https://linux-hardware.org/?probe=129bcce64f) | Jul 17, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [236812ea49](https://linux-hardware.org/?probe=236812ea49) | Jul 17, 2022 |
| ASUSTek       | M51BC                       | [d5a6b5628b](https://linux-hardware.org/?probe=d5a6b5628b) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [386dd1ac4b](https://linux-hardware.org/?probe=386dd1ac4b) | Jul 14, 2022 |
| MSI           | A320M PRO-VH PLUS           | [e007a2fbc2](https://linux-hardware.org/?probe=e007a2fbc2) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [fdae528732](https://linux-hardware.org/?probe=fdae528732) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [063f846aad](https://linux-hardware.org/?probe=063f846aad) | Jul 12, 2022 |
| OEM_MB        | NARRA3                      | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| Dell          | 09WH54 A00                  | [8570e35470](https://linux-hardware.org/?probe=8570e35470) | Jul 11, 2022 |
| Acer          | Nitro N50-610               | [48c007b4e2](https://linux-hardware.org/?probe=48c007b4e2) | Jul 10, 2022 |
| Gigabyte      | Z270M-D3H-CF                | [df9ed91803](https://linux-hardware.org/?probe=df9ed91803) | Jul 10, 2022 |
| MSI           | 2AE0                        | [4732ee97fb](https://linux-hardware.org/?probe=4732ee97fb) | Jul 10, 2022 |
| Apple         | Mac-F221BEC8                | [2efb274f31](https://linux-hardware.org/?probe=2efb274f31) | Jul 10, 2022 |
| MSI           | B450-A PRO MAX              | [00495f3422](https://linux-hardware.org/?probe=00495f3422) | Jul 09, 2022 |
| Dell          | 0R849J A01                  | [3ea68d63c3](https://linux-hardware.org/?probe=3ea68d63c3) | Jul 08, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| ASUSTek       | P7H55-M PRO                 | [35e1af0d15](https://linux-hardware.org/?probe=35e1af0d15) | Jul 08, 2022 |
| ASRock        | B450M Pro4                  | [ff75212757](https://linux-hardware.org/?probe=ff75212757) | Jul 07, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [ebaa969297](https://linux-hardware.org/?probe=ebaa969297) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [d14ad254ca](https://linux-hardware.org/?probe=d14ad254ca) | Jul 05, 2022 |
| ASRock        | G41C-GS R2.0                | [a9a0f46cc7](https://linux-hardware.org/?probe=a9a0f46cc7) | Jul 05, 2022 |
| MSI           | Z170-A PRO                  | [24a76119e1](https://linux-hardware.org/?probe=24a76119e1) | Jul 04, 2022 |
| MSI           | 970A SLI Krait Edition      | [3199c023cb](https://linux-hardware.org/?probe=3199c023cb) | Jul 04, 2022 |
| Dell          | 0M6C7G A00                  | [5eee0db64f](https://linux-hardware.org/?probe=5eee0db64f) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| Acer          | Aspire TC-280               | [7322461b76](https://linux-hardware.org/?probe=7322461b76) | Jul 03, 2022 |
| Acer          | Aspire TC-280               | [0e497c1c13](https://linux-hardware.org/?probe=0e497c1c13) | Jul 02, 2022 |
| ASRock        | B450M Pro4                  | [64eae559ae](https://linux-hardware.org/?probe=64eae559ae) | Jul 02, 2022 |
| ASRock        | Z97 Anniversary             | [1e650b504d](https://linux-hardware.org/?probe=1e650b504d) | Jul 01, 2022 |
| Dell          | 0HJ054                      | [bb9d7a3a58](https://linux-hardware.org/?probe=bb9d7a3a58) | Jun 30, 2022 |
| Dell          | 0M858N A01                  | [6cc8dcd51e](https://linux-hardware.org/?probe=6cc8dcd51e) | Jun 29, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [cf7b4fb7e1](https://linux-hardware.org/?probe=cf7b4fb7e1) | Jun 29, 2022 |
| MSI           | H310M PRO-VD                | [1aec9e08e9](https://linux-hardware.org/?probe=1aec9e08e9) | Jun 28, 2022 |
| MSI           | H310M PRO-VD                | [1812911a41](https://linux-hardware.org/?probe=1812911a41) | Jun 28, 2022 |
| ASRock        | A320M-HDV R4.0              | [547346f0a9](https://linux-hardware.org/?probe=547346f0a9) | Jun 26, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [2c1f55aa8f](https://linux-hardware.org/?probe=2c1f55aa8f) | Jun 23, 2022 |
| ASUSTek       | P5W DH Deluxe               | [71f0d32783](https://linux-hardware.org/?probe=71f0d32783) | Jun 23, 2022 |
| Gigabyte      | Z77X-UD3H                   | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| ASRock        | A320M-HDV R4.0              | [cf4479fbe9](https://linux-hardware.org/?probe=cf4479fbe9) | Jun 22, 2022 |
| ASUSTek       | PRIME Z370-A                | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| MSI           | H310M PRO-VD                | [6516a467b5](https://linux-hardware.org/?probe=6516a467b5) | Jun 17, 2022 |
| ASUSTek       | P8B75-M                     | [9ab6f4690f](https://linux-hardware.org/?probe=9ab6f4690f) | Jun 16, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [bce90f59c8](https://linux-hardware.org/?probe=bce90f59c8) | Jun 16, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [6c1c388f3a](https://linux-hardware.org/?probe=6c1c388f3a) | Jun 15, 2022 |
| MSI           | B450 TOMAHAWK               | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| ASRock        | H310M-ITX/ac                | [17063e8cc6](https://linux-hardware.org/?probe=17063e8cc6) | Jun 15, 2022 |
| Acer          | Aspire X1400                | [a90701fd86](https://linux-hardware.org/?probe=a90701fd86) | Jun 15, 2022 |
| Lenovo        | 0B98401 PRO                 | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| ASUSTek       | PRIME B550M-A               | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| ASUSTek       | PRIME B450M-A II            | [148d14437b](https://linux-hardware.org/?probe=148d14437b) | Jun 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | [693e499a6d](https://linux-hardware.org/?probe=693e499a6d) | Jun 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [e92127f694](https://linux-hardware.org/?probe=e92127f694) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| Dell          | 0WR7PY A03                  | [630d0bc381](https://linux-hardware.org/?probe=630d0bc381) | Jun 08, 2022 |
| Intel         | DG33FB AAD81072-306         | [78abe45a29](https://linux-hardware.org/?probe=78abe45a29) | Jun 08, 2022 |
| Lenovo        | ThinkStation S20 410599U    | [072870fb4e](https://linux-hardware.org/?probe=072870fb4e) | Jun 07, 2022 |
| HP            | 8433 11                     | [fa4c4f5c0e](https://linux-hardware.org/?probe=fa4c4f5c0e) | Jun 07, 2022 |
| Lenovo        | ThinkStation S20 410599U    | [20df21f5d9](https://linux-hardware.org/?probe=20df21f5d9) | Jun 07, 2022 |
| Unknown       | Unknown                     | [44afb95fbb](https://linux-hardware.org/?probe=44afb95fbb) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [e636b14f58](https://linux-hardware.org/?probe=e636b14f58) | Jun 05, 2022 |
| ASRock        | Z97 Anniversary             | [b6a332c085](https://linux-hardware.org/?probe=b6a332c085) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| HP            | 3397                        | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| HP            | 3397                        | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| BESSTAR Te... | UM700                       | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [c50bbae3e1](https://linux-hardware.org/?probe=c50bbae3e1) | Jun 02, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [536c6e19de](https://linux-hardware.org/?probe=536c6e19de) | Jun 01, 2022 |
| HP            | 339A                        | [c3c520f59b](https://linux-hardware.org/?probe=c3c520f59b) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| Dell          | 0R6PCT A01                  | [08c460e0a3](https://linux-hardware.org/?probe=08c460e0a3) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | [89aadb96f3](https://linux-hardware.org/?probe=89aadb96f3) | May 30, 2022 |
| ASUSTek       | M5A97 R2.0                  | [5e75c2d00d](https://linux-hardware.org/?probe=5e75c2d00d) | May 29, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [33a2de91a2](https://linux-hardware.org/?probe=33a2de91a2) | May 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [c07bfd58f1](https://linux-hardware.org/?probe=c07bfd58f1) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [24b4b7cb04](https://linux-hardware.org/?probe=24b4b7cb04) | May 26, 2022 |
| Lenovo        | ThinkCentre M90p 5864AL2    | [679cfd5a27](https://linux-hardware.org/?probe=679cfd5a27) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [db51e7c435](https://linux-hardware.org/?probe=db51e7c435) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| Dell          | 0YJPT1 A00                  | [f4afc8ed1d](https://linux-hardware.org/?probe=f4afc8ed1d) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [7260e3bf3b](https://linux-hardware.org/?probe=7260e3bf3b) | May 24, 2022 |
| ASUSTek       | PRIME B660M-A AC D4         | [286688e46b](https://linux-hardware.org/?probe=286688e46b) | May 23, 2022 |
| Gigabyte      | Z390 UD                     | [d49bf6427c](https://linux-hardware.org/?probe=d49bf6427c) | May 23, 2022 |
| MSI           | 2AE0                        | [ea14a764bb](https://linux-hardware.org/?probe=ea14a764bb) | May 22, 2022 |
| HP            | 3398                        | [d7e6c0c903](https://linux-hardware.org/?probe=d7e6c0c903) | May 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [42338941c5](https://linux-hardware.org/?probe=42338941c5) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Dell          | 0D6H9T A02                  | [3f87c84f7a](https://linux-hardware.org/?probe=3f87c84f7a) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| HP            | 8704                        | [84fd199efc](https://linux-hardware.org/?probe=84fd199efc) | May 17, 2022 |
| MSI           | H310M PRO-VD                | [70a3302b36](https://linux-hardware.org/?probe=70a3302b36) | May 17, 2022 |
| MSI           | H310M PRO-VD                | [a04d3bd332](https://linux-hardware.org/?probe=a04d3bd332) | May 17, 2022 |
| HP            | 8704                        | [863dcbe2ae](https://linux-hardware.org/?probe=863dcbe2ae) | May 17, 2022 |
| Dell          | 0T656F A01                  | [2df08f807d](https://linux-hardware.org/?probe=2df08f807d) | May 15, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b061586ff0](https://linux-hardware.org/?probe=b061586ff0) | May 14, 2022 |
| ASUSTek       | F2A85-V PRO                 | [35209e0a61](https://linux-hardware.org/?probe=35209e0a61) | May 14, 2022 |
| ASUSTek       | Acacia                      | [4b633150fa](https://linux-hardware.org/?probe=4b633150fa) | May 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [2d1e8a0642](https://linux-hardware.org/?probe=2d1e8a0642) | May 14, 2022 |
| ASRock        | B450M Pro4-F                | [423fbd3a54](https://linux-hardware.org/?probe=423fbd3a54) | May 14, 2022 |
| HP            | 8704                        | [979caa0192](https://linux-hardware.org/?probe=979caa0192) | May 13, 2022 |
| ASUSTek       | B85M-G                      | [6dee77b5ca](https://linux-hardware.org/?probe=6dee77b5ca) | May 13, 2022 |
| Acer          | Aspire X3400                | [9dd76b4599](https://linux-hardware.org/?probe=9dd76b4599) | May 13, 2022 |
| Acer          | Aspire X3400                | [b590b149fc](https://linux-hardware.org/?probe=b590b149fc) | May 13, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| MSI           | Z390-A PRO                  | [58c45bf845](https://linux-hardware.org/?probe=58c45bf845) | May 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [5de8d1f805](https://linux-hardware.org/?probe=5de8d1f805) | May 11, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| MSI           | X470 GAMING PLUS            | [565dfeea66](https://linux-hardware.org/?probe=565dfeea66) | May 11, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c5bad2fcf9](https://linux-hardware.org/?probe=c5bad2fcf9) | May 10, 2022 |
| MSI           | A68HM-E33 V2                | [dedc4ce0d5](https://linux-hardware.org/?probe=dedc4ce0d5) | May 10, 2022 |
| ASUSTek       | PRIME Z370-A                | [e930eaf7f8](https://linux-hardware.org/?probe=e930eaf7f8) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Dell          | 0Y2MRG A00                  | [ab85a57857](https://linux-hardware.org/?probe=ab85a57857) | May 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [1899727b8b](https://linux-hardware.org/?probe=1899727b8b) | May 09, 2022 |
| ASUSTek       | P5QL PRO                    | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| HP            | 3397                        | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| MSI           | H310M PRO-VD                | [5f977ecef6](https://linux-hardware.org/?probe=5f977ecef6) | May 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| ASUSTek       | VM42                        | [cb73da6c51](https://linux-hardware.org/?probe=cb73da6c51) | May 05, 2022 |
| ASUSTek       | VM42                        | [1fb131686b](https://linux-hardware.org/?probe=1fb131686b) | May 05, 2022 |
| MSI           | Z390-A PRO                  | [21e3f8a718](https://linux-hardware.org/?probe=21e3f8a718) | May 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [a23da6e2be](https://linux-hardware.org/?probe=a23da6e2be) | May 05, 2022 |
| MSI           | Z390-A PRO                  | [145317db95](https://linux-hardware.org/?probe=145317db95) | May 05, 2022 |
| ASRock        | X570 Extreme4               | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| ASUSTek       | Rampage III Extreme         | [30ff3d44b0](https://linux-hardware.org/?probe=30ff3d44b0) | May 04, 2022 |
| HP            | 2AF7                        | [de6583780a](https://linux-hardware.org/?probe=de6583780a) | May 04, 2022 |
| Gigabyte      | B75M-HD3                    | [7dc76bf420](https://linux-hardware.org/?probe=7dc76bf420) | May 04, 2022 |
| HP            | 2AF7                        | [ee82d627d6](https://linux-hardware.org/?probe=ee82d627d6) | May 04, 2022 |
| Acer          | Aspire XC-230               | [b80fa8b04f](https://linux-hardware.org/?probe=b80fa8b04f) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| MSI           | B450 GAMING PLUS            | [a792e309de](https://linux-hardware.org/?probe=a792e309de) | May 02, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f157b373a1](https://linux-hardware.org/?probe=f157b373a1) | Apr 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f339d2405b](https://linux-hardware.org/?probe=f339d2405b) | Apr 29, 2022 |
| Dell          | 0VNP2H A00                  | [bb480c7f9c](https://linux-hardware.org/?probe=bb480c7f9c) | Apr 29, 2022 |
| Alienware     | 07W25T A00                  | [b989838f70](https://linux-hardware.org/?probe=b989838f70) | Apr 29, 2022 |
| HP            | 8433 11                     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| HP            | 1495                        | [b6e482940f](https://linux-hardware.org/?probe=b6e482940f) | Apr 28, 2022 |
| HP            | 1495                        | [632386ed8d](https://linux-hardware.org/?probe=632386ed8d) | Apr 28, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| ASUSTek       | M51BC                       | [f997f2d1c1](https://linux-hardware.org/?probe=f997f2d1c1) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z170 S           | [21663dc8b3](https://linux-hardware.org/?probe=21663dc8b3) | Apr 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | [185c64fa0d](https://linux-hardware.org/?probe=185c64fa0d) | Apr 27, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [3c53a0e59d](https://linux-hardware.org/?probe=3c53a0e59d) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| Dell          | 06JWJY A01                  | [938679bafe](https://linux-hardware.org/?probe=938679bafe) | Apr 26, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [486215d495](https://linux-hardware.org/?probe=486215d495) | Apr 26, 2022 |
| HP            | 3397                        | [754e703cc5](https://linux-hardware.org/?probe=754e703cc5) | Apr 25, 2022 |
| Dell          | 0J3C2F A02                  | [833d1610d5](https://linux-hardware.org/?probe=833d1610d5) | Apr 25, 2022 |
| Dell          | 0HY9JP A00                  | [9a884ccaa8](https://linux-hardware.org/?probe=9a884ccaa8) | Apr 23, 2022 |
| MSI           | Z77A-GD65                   | [75dc6c44e5](https://linux-hardware.org/?probe=75dc6c44e5) | Apr 23, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [8e31efa5fa](https://linux-hardware.org/?probe=8e31efa5fa) | Apr 23, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [d35c4838f2](https://linux-hardware.org/?probe=d35c4838f2) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [61e0546ed7](https://linux-hardware.org/?probe=61e0546ed7) | Apr 22, 2022 |
| Gateway       | SX2185                      | [d22bb794a1](https://linux-hardware.org/?probe=d22bb794a1) | Apr 22, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| Gigabyte      | Z97X-UD5H                   | [15bba912da](https://linux-hardware.org/?probe=15bba912da) | Apr 21, 2022 |
| MSI           | B550-A PRO                  | [212c60ebc5](https://linux-hardware.org/?probe=212c60ebc5) | Apr 21, 2022 |
| Lenovo        | ThinkStation XXXX 415852... | [afabe3060d](https://linux-hardware.org/?probe=afabe3060d) | Apr 21, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9a6d4db5b7](https://linux-hardware.org/?probe=9a6d4db5b7) | Apr 21, 2022 |
| ASUSTek       | M4A785-M                    | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
| Dell          | 0HJ054                      | [8289626c00](https://linux-hardware.org/?probe=8289626c00) | Apr 20, 2022 |
| ASUSTek       | P5GC-MX                     | [810607b312](https://linux-hardware.org/?probe=810607b312) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| HP            | 82B4                        | [d15212b522](https://linux-hardware.org/?probe=d15212b522) | Apr 19, 2022 |
| HP            | 2820h                       | [21046a0077](https://linux-hardware.org/?probe=21046a0077) | Apr 19, 2022 |
| HP            | 82B4                        | [c3ed060808](https://linux-hardware.org/?probe=c3ed060808) | Apr 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4c8ca0d53f](https://linux-hardware.org/?probe=4c8ca0d53f) | Apr 18, 2022 |
| ASRock        | Z68 Extreme4                | [36da46e911](https://linux-hardware.org/?probe=36da46e911) | Apr 18, 2022 |
| ASUSTek       | P5GC-MX                     | [55cd1e5c8f](https://linux-hardware.org/?probe=55cd1e5c8f) | Apr 17, 2022 |
| MSI           | 970 GAMING                  | [10ad704b03](https://linux-hardware.org/?probe=10ad704b03) | Apr 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [0d1f53febb](https://linux-hardware.org/?probe=0d1f53febb) | Apr 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [90486ad164](https://linux-hardware.org/?probe=90486ad164) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | [76a80df275](https://linux-hardware.org/?probe=76a80df275) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | [74b8687993](https://linux-hardware.org/?probe=74b8687993) | Apr 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [37e172faec](https://linux-hardware.org/?probe=37e172faec) | Apr 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [247cd43da9](https://linux-hardware.org/?probe=247cd43da9) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [843c3d4758](https://linux-hardware.org/?probe=843c3d4758) | Apr 14, 2022 |
| Gigabyte      | B85M-D3H                    | [a0c2314e31](https://linux-hardware.org/?probe=a0c2314e31) | Apr 14, 2022 |
| ASRock        | AB350 Pro4                  | [137e25f240](https://linux-hardware.org/?probe=137e25f240) | Apr 14, 2022 |
| MSI           | X79A-GD45 Plus              | [fd93542a14](https://linux-hardware.org/?probe=fd93542a14) | Apr 14, 2022 |
| ASUSTek       | Crosshair V Formula         | [3b66db6997](https://linux-hardware.org/?probe=3b66db6997) | Apr 14, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [a0b6dfe7e4](https://linux-hardware.org/?probe=a0b6dfe7e4) | Apr 13, 2022 |
| ASRock        | X570M Pro4                  | [b7373e1f8f](https://linux-hardware.org/?probe=b7373e1f8f) | Apr 13, 2022 |
| MSI           | X470 GAMING PLUS            | [5100c45b65](https://linux-hardware.org/?probe=5100c45b65) | Apr 13, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [c28c553d03](https://linux-hardware.org/?probe=c28c553d03) | Apr 13, 2022 |
| ASUSTek       | H81M-E                      | [b26d147ae3](https://linux-hardware.org/?probe=b26d147ae3) | Apr 13, 2022 |
| ASUSTek       | PRIME Z370-P                | [3b91a78742](https://linux-hardware.org/?probe=3b91a78742) | Apr 13, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [13ad3d5cb4](https://linux-hardware.org/?probe=13ad3d5cb4) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e05e4dc47b](https://linux-hardware.org/?probe=e05e4dc47b) | Apr 13, 2022 |
| Lenovo        | ThinkCentre M90p 5536A76    | [f594adac1d](https://linux-hardware.org/?probe=f594adac1d) | Apr 13, 2022 |
| Dell          | 0XCR8D A00                  | [d0f55067b0](https://linux-hardware.org/?probe=d0f55067b0) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [71d793e054](https://linux-hardware.org/?probe=71d793e054) | Apr 13, 2022 |
| Dell          | 042P49 A02                  | [f7b6132f34](https://linux-hardware.org/?probe=f7b6132f34) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [438f675016](https://linux-hardware.org/?probe=438f675016) | Apr 13, 2022 |
| MSI           | B450M PRO-VDH MAX           | [3656e85663](https://linux-hardware.org/?probe=3656e85663) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | [4c52c99ee9](https://linux-hardware.org/?probe=4c52c99ee9) | Apr 12, 2022 |
| Dell          | 0N867P A01                  | [749dc04756](https://linux-hardware.org/?probe=749dc04756) | Apr 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [be0d616e99](https://linux-hardware.org/?probe=be0d616e99) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | [162850d6b3](https://linux-hardware.org/?probe=162850d6b3) | Apr 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [921b858e18](https://linux-hardware.org/?probe=921b858e18) | Apr 11, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [3d3f67170e](https://linux-hardware.org/?probe=3d3f67170e) | Apr 11, 2022 |
| Lenovo        | ThinkCentre M58p 7484ANU    | [2d7d0de436](https://linux-hardware.org/?probe=2d7d0de436) | Apr 10, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [63df7871b0](https://linux-hardware.org/?probe=63df7871b0) | Apr 10, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [6884809c79](https://linux-hardware.org/?probe=6884809c79) | Apr 10, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [28114b7924](https://linux-hardware.org/?probe=28114b7924) | Apr 10, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [1638359c7b](https://linux-hardware.org/?probe=1638359c7b) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [9f3f45d840](https://linux-hardware.org/?probe=9f3f45d840) | Apr 09, 2022 |
| HP            | 18E5                        | [5c24443112](https://linux-hardware.org/?probe=5c24443112) | Apr 09, 2022 |
| Acer          | Veriton M6660G V:1.0        | [a41ffdc22b](https://linux-hardware.org/?probe=a41ffdc22b) | Apr 09, 2022 |
| HP            | 1998                        | [0ed4dbebcb](https://linux-hardware.org/?probe=0ed4dbebcb) | Apr 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ac05d8917](https://linux-hardware.org/?probe=8ac05d8917) | Apr 07, 2022 |
| Gigabyte      | B365M GAMING HD             | [94b6fc5131](https://linux-hardware.org/?probe=94b6fc5131) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| ASRock        | Z390 Phantom Gaming 4S/a... | [836d139ea0](https://linux-hardware.org/?probe=836d139ea0) | Apr 07, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [d1f213c4f0](https://linux-hardware.org/?probe=d1f213c4f0) | Apr 07, 2022 |
| Unknown       | Unknown                     | [c8049ac14a](https://linux-hardware.org/?probe=c8049ac14a) | Apr 06, 2022 |
| ASUSTek       | P5GC-MX                     | [ce2aaa12ab](https://linux-hardware.org/?probe=ce2aaa12ab) | Apr 06, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [cc10884386](https://linux-hardware.org/?probe=cc10884386) | Apr 06, 2022 |
| Gigabyte      | H270N-WIFI-CF               | [fe6d2db0dd](https://linux-hardware.org/?probe=fe6d2db0dd) | Apr 05, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [65c7660b74](https://linux-hardware.org/?probe=65c7660b74) | Apr 05, 2022 |
| ASUSTek       | Z97-A-USB31                 | [cd6f73403e](https://linux-hardware.org/?probe=cd6f73403e) | Apr 05, 2022 |
| Acer          | Aspire XC-603               | [ef344607ad](https://linux-hardware.org/?probe=ef344607ad) | Apr 04, 2022 |
| ASRock        | Z270 Killer SLI/ac          | [cd29715a0d](https://linux-hardware.org/?probe=cd29715a0d) | Apr 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [73ecbc62b1](https://linux-hardware.org/?probe=73ecbc62b1) | Apr 04, 2022 |
| Apple         | Mac-F221BEC8                | [e72fc44e1d](https://linux-hardware.org/?probe=e72fc44e1d) | Apr 03, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fc477a4cb4](https://linux-hardware.org/?probe=fc477a4cb4) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [23b384fa80](https://linux-hardware.org/?probe=23b384fa80) | Apr 02, 2022 |
| Unknown       | Unknown                     | [9ea14bf201](https://linux-hardware.org/?probe=9ea14bf201) | Apr 02, 2022 |
| Gigabyte      | Q77M-D2H                    | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| ASUSTek       | Z97-A-USB31                 | [6f40a4ebce](https://linux-hardware.org/?probe=6f40a4ebce) | Apr 02, 2022 |
| Gigabyte      | H97M-D3H                    | [72d527b649](https://linux-hardware.org/?probe=72d527b649) | Apr 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | [069ce7ef8f](https://linux-hardware.org/?probe=069ce7ef8f) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M81 5049E7F     | [cfb0af9c1b](https://linux-hardware.org/?probe=cfb0af9c1b) | Mar 29, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [a10bdc00e2](https://linux-hardware.org/?probe=a10bdc00e2) | Mar 28, 2022 |
| ASRock        | B365M Pro4                  | [6920de7907](https://linux-hardware.org/?probe=6920de7907) | Mar 28, 2022 |
| Gigabyte      | GA-770T-USB3                | [787cb334c2](https://linux-hardware.org/?probe=787cb334c2) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [5dae1dd2a5](https://linux-hardware.org/?probe=5dae1dd2a5) | Mar 28, 2022 |
| HP            | 339A                        | [e3c5312cd4](https://linux-hardware.org/?probe=e3c5312cd4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B350-I GAMING     | [36e8a83674](https://linux-hardware.org/?probe=36e8a83674) | Mar 27, 2022 |
| MSI           | X79A-GD45 Plus              | [e12c979369](https://linux-hardware.org/?probe=e12c979369) | Mar 27, 2022 |
| MSI           | X79A-GD45 Plus              | [23eab958e6](https://linux-hardware.org/?probe=23eab958e6) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [9c0577803f](https://linux-hardware.org/?probe=9c0577803f) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [a296d4597c](https://linux-hardware.org/?probe=a296d4597c) | Mar 27, 2022 |
| HP            | 339A                        | [8795c4a222](https://linux-hardware.org/?probe=8795c4a222) | Mar 27, 2022 |
| MSI           | PRO Z690-P DDR4             | [7aac216113](https://linux-hardware.org/?probe=7aac216113) | Mar 26, 2022 |
| ASUSTek       | B85M-G                      | [1d78876e0c](https://linux-hardware.org/?probe=1d78876e0c) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [a68ce8edaf](https://linux-hardware.org/?probe=a68ce8edaf) | Mar 26, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [dc2a2c1054](https://linux-hardware.org/?probe=dc2a2c1054) | Mar 25, 2022 |
| ASUSTek       | SABERTOOTH X58              | [bce45f36b9](https://linux-hardware.org/?probe=bce45f36b9) | Mar 25, 2022 |
| Pegatron      | Benicia                     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| Acer          | Veriton M6660G V:1.0        | [ee5d755daf](https://linux-hardware.org/?probe=ee5d755daf) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [55171208ed](https://linux-hardware.org/?probe=55171208ed) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7c46f54dc](https://linux-hardware.org/?probe=d7c46f54dc) | Mar 24, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [f1007aa153](https://linux-hardware.org/?probe=f1007aa153) | Mar 24, 2022 |
| Alienware     | 0R3FWM A00                  | [fcbc77d9e4](https://linux-hardware.org/?probe=fcbc77d9e4) | Mar 24, 2022 |
| Lenovo        | ThinkStation C20 426593U    | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [39b19d4ecf](https://linux-hardware.org/?probe=39b19d4ecf) | Mar 22, 2022 |
| HP            | 3397                        | [51dd330f09](https://linux-hardware.org/?probe=51dd330f09) | Mar 22, 2022 |
| Acer          | Veriton M6660G V:1.0        | [228974c486](https://linux-hardware.org/?probe=228974c486) | Mar 22, 2022 |
| Dell          | 0K3CM7 A00                  | [8f5ec6c004](https://linux-hardware.org/?probe=8f5ec6c004) | Mar 22, 2022 |
| HP            | 0AECh D                     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [66f133fcf0](https://linux-hardware.org/?probe=66f133fcf0) | Mar 22, 2022 |
| ASUSTek       | SABERTOOTH X79              | [9e6ccdc0e4](https://linux-hardware.org/?probe=9e6ccdc0e4) | Mar 21, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [3c97963539](https://linux-hardware.org/?probe=3c97963539) | Mar 21, 2022 |
| HP            | 3397                        | [60dc930e32](https://linux-hardware.org/?probe=60dc930e32) | Mar 20, 2022 |
| ASUSTek       | H170 PRO GAMING             | [8ce1eed900](https://linux-hardware.org/?probe=8ce1eed900) | Mar 20, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [9cdf9a4b0b](https://linux-hardware.org/?probe=9cdf9a4b0b) | Mar 19, 2022 |
| ASRock        | B560M-ITX/ac                | [58d3e7c461](https://linux-hardware.org/?probe=58d3e7c461) | Mar 18, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [d2378fc2ac](https://linux-hardware.org/?probe=d2378fc2ac) | Mar 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f43e92acdd](https://linux-hardware.org/?probe=f43e92acdd) | Mar 18, 2022 |
| Alienware     | 0PGRP5 A02                  | [8a28919b48](https://linux-hardware.org/?probe=8a28919b48) | Mar 17, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [355c14014e](https://linux-hardware.org/?probe=355c14014e) | Mar 17, 2022 |
| Alienware     | 0PGRP5 A02                  | [de0e243d72](https://linux-hardware.org/?probe=de0e243d72) | Mar 16, 2022 |
| ASUSTek       | PRIME B450M-A               | [2d053651b5](https://linux-hardware.org/?probe=2d053651b5) | Mar 16, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [11bc08ed1f](https://linux-hardware.org/?probe=11bc08ed1f) | Mar 16, 2022 |
| ASUSTek       | A68HM-K                     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| TYAN Compu... | D2568 S26361-D2568-A11      | [fd7cbc2300](https://linux-hardware.org/?probe=fd7cbc2300) | Mar 15, 2022 |
| MSI           | X99A SLI PLUS               | [3e6960fead](https://linux-hardware.org/?probe=3e6960fead) | Mar 14, 2022 |
| HP            | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| ASUSTek       | H87-PLUS                    | [41d61ba64b](https://linux-hardware.org/?probe=41d61ba64b) | Mar 14, 2022 |
| MSI           | B450M BAZOOKA V2            | [3dcd349d64](https://linux-hardware.org/?probe=3dcd349d64) | Mar 14, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [e062006ffe](https://linux-hardware.org/?probe=e062006ffe) | Mar 13, 2022 |
| Biostar       | TZ590-BTC DUO               | [fa2f8683b7](https://linux-hardware.org/?probe=fa2f8683b7) | Mar 13, 2022 |
| Acer          | Aspire M3420                | [ab930c70e0](https://linux-hardware.org/?probe=ab930c70e0) | Mar 13, 2022 |
| Dell          | 0RW199                      | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| ASUSTek       | Maximus VII HERO            | [f21f05d1ab](https://linux-hardware.org/?probe=f21f05d1ab) | Mar 13, 2022 |
| Lenovo        | ThinkCentre M90p 5536K6M    | [353245bef3](https://linux-hardware.org/?probe=353245bef3) | Mar 12, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [92a248bac7](https://linux-hardware.org/?probe=92a248bac7) | Mar 11, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b2c8c04a66](https://linux-hardware.org/?probe=b2c8c04a66) | Mar 11, 2022 |
| HP            | 1497                        | [3c01ac84d3](https://linux-hardware.org/?probe=3c01ac84d3) | Mar 11, 2022 |
| ASUSTek       | PRIME B450M-A               | [b179a5048f](https://linux-hardware.org/?probe=b179a5048f) | Mar 10, 2022 |
| ASUSTek       | H110M-E/M.2                 | [0a6b13d126](https://linux-hardware.org/?probe=0a6b13d126) | Mar 10, 2022 |
| ASUSTek       | H110M-E/M.2                 | [d998726441](https://linux-hardware.org/?probe=d998726441) | Mar 10, 2022 |
| Dell          | 088DT1 A01                  | [7d57d04480](https://linux-hardware.org/?probe=7d57d04480) | Mar 09, 2022 |
| Dell          | 0427JK A00                  | [96996cefb1](https://linux-hardware.org/?probe=96996cefb1) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| MSI           | X79A-GD45                   | [ab71ffe574](https://linux-hardware.org/?probe=ab71ffe574) | Mar 09, 2022 |
| ASRock        | H670M-ITX/ax                | [066930734a](https://linux-hardware.org/?probe=066930734a) | Mar 07, 2022 |
| HP            | 2AFB                        | [59ed587f49](https://linux-hardware.org/?probe=59ed587f49) | Mar 06, 2022 |
| ASUSTek       | P5QC                        | [2f4a501c6a](https://linux-hardware.org/?probe=2f4a501c6a) | Mar 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [91bb2e28fe](https://linux-hardware.org/?probe=91bb2e28fe) | Mar 05, 2022 |
| Dell          | 0427JK A00                  | [11b2bc7970](https://linux-hardware.org/?probe=11b2bc7970) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1a5f917071](https://linux-hardware.org/?probe=1a5f917071) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [000e4e07d6](https://linux-hardware.org/?probe=000e4e07d6) | Mar 03, 2022 |
| HP            | 0A9Ch                       | [0403520776](https://linux-hardware.org/?probe=0403520776) | Mar 03, 2022 |
| HP            | 2AFB                        | [a44da1443a](https://linux-hardware.org/?probe=a44da1443a) | Mar 03, 2022 |
| ASUSTek       | LITHIUM                     | [94a08d2468](https://linux-hardware.org/?probe=94a08d2468) | Mar 02, 2022 |
| MSI           | B350 TOMAHAWK ARCTIC        | [933aecdfff](https://linux-hardware.org/?probe=933aecdfff) | Mar 02, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [4f264071dd](https://linux-hardware.org/?probe=4f264071dd) | Mar 01, 2022 |
| Foxconn       | 2A92                        | [d41fb8dda1](https://linux-hardware.org/?probe=d41fb8dda1) | Feb 28, 2022 |
| ASUSTek       | X99-DELUXE                  | [27513a5e2d](https://linux-hardware.org/?probe=27513a5e2d) | Feb 28, 2022 |
| HP            | 2AFB                        | [dc64c96b48](https://linux-hardware.org/?probe=dc64c96b48) | Feb 28, 2022 |
| Dell          | 0HY9JP A02                  | [398b45ed60](https://linux-hardware.org/?probe=398b45ed60) | Feb 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [03f2fa46f2](https://linux-hardware.org/?probe=03f2fa46f2) | Feb 26, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [922a24d848](https://linux-hardware.org/?probe=922a24d848) | Feb 25, 2022 |
| Dell          | 042P49 A02                  | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [ded367a62c](https://linux-hardware.org/?probe=ded367a62c) | Feb 25, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [b6891f77df](https://linux-hardware.org/?probe=b6891f77df) | Feb 24, 2022 |
| Dell          | 00V62H A01                  | [e6564282e5](https://linux-hardware.org/?probe=e6564282e5) | Feb 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a4e64da15a](https://linux-hardware.org/?probe=a4e64da15a) | Feb 22, 2022 |
| Alienware     | 0FPV4P A00                  | [a80e15326f](https://linux-hardware.org/?probe=a80e15326f) | Feb 20, 2022 |
| Unknown       | Intel X79                   | [4da7793470](https://linux-hardware.org/?probe=4da7793470) | Feb 20, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [9244fdd04c](https://linux-hardware.org/?probe=9244fdd04c) | Feb 20, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [bcae2aafa6](https://linux-hardware.org/?probe=bcae2aafa6) | Feb 20, 2022 |
| MSI           | PRO Z690-A                  | [3767b10050](https://linux-hardware.org/?probe=3767b10050) | Feb 20, 2022 |
| Dell          | 03NVJ6 A03                  | [88a9e6e59c](https://linux-hardware.org/?probe=88a9e6e59c) | Feb 19, 2022 |
| ASUSTek       | M4A78LT-M-LE                | [a4aca283a8](https://linux-hardware.org/?probe=a4aca283a8) | Feb 19, 2022 |
| HP            | 1497                        | [afdb7b3de7](https://linux-hardware.org/?probe=afdb7b3de7) | Feb 19, 2022 |
| Alienware     | 07W25T A00                  | [645416ce96](https://linux-hardware.org/?probe=645416ce96) | Feb 19, 2022 |
| HP            | 828A                        | [e947d909e2](https://linux-hardware.org/?probe=e947d909e2) | Feb 18, 2022 |
| ASRock        | B450M-HDV R4.0              | [78d585ee32](https://linux-hardware.org/?probe=78d585ee32) | Feb 18, 2022 |
| Dell          | 0J3C2F A02                  | [bbd3dfcc18](https://linux-hardware.org/?probe=bbd3dfcc18) | Feb 17, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [3dc3e4c8c8](https://linux-hardware.org/?probe=3dc3e4c8c8) | Feb 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [37f7024a37](https://linux-hardware.org/?probe=37f7024a37) | Feb 17, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [913928e6e9](https://linux-hardware.org/?probe=913928e6e9) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | [c80545d294](https://linux-hardware.org/?probe=c80545d294) | Feb 16, 2022 |
| ASUSTek       | M5A97 EVO                   | [98e8879090](https://linux-hardware.org/?probe=98e8879090) | Feb 16, 2022 |
| HP            | 18E5                        | [5832416e72](https://linux-hardware.org/?probe=5832416e72) | Feb 16, 2022 |
| ASUSTek       | PRIME Z370-P II             | [2780adec26](https://linux-hardware.org/?probe=2780adec26) | Feb 16, 2022 |
| ASRock        | H97M Pro4                   | [dfa4523477](https://linux-hardware.org/?probe=dfa4523477) | Feb 16, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [f3d0b52776](https://linux-hardware.org/?probe=f3d0b52776) | Feb 15, 2022 |
| HP            | 2AF8                        | [b336741b02](https://linux-hardware.org/?probe=b336741b02) | Feb 14, 2022 |
| ASUSTek       | PRIME X570-P                | [d9407827ef](https://linux-hardware.org/?probe=d9407827ef) | Feb 13, 2022 |
| MSI           | B350 TOMAHAWK ARCTIC        | [b0829a9cb6](https://linux-hardware.org/?probe=b0829a9cb6) | Feb 13, 2022 |
| ASUSTek       | Berkeley                    | [e189134b88](https://linux-hardware.org/?probe=e189134b88) | Feb 12, 2022 |
| Acer          | Aspire TC-330               | [07a9d7bbd1](https://linux-hardware.org/?probe=07a9d7bbd1) | Feb 12, 2022 |
| Gigabyte      | B460 HD3                    | [f3368b9129](https://linux-hardware.org/?probe=f3368b9129) | Feb 11, 2022 |
| Gateway       | FX6860                      | [c5d971a94c](https://linux-hardware.org/?probe=c5d971a94c) | Feb 11, 2022 |
| Pegatron      | NARRA5                      | [63b943e081](https://linux-hardware.org/?probe=63b943e081) | Feb 10, 2022 |
| Pegatron      | NARRA5                      | [b44567ac7d](https://linux-hardware.org/?probe=b44567ac7d) | Feb 10, 2022 |
| Acer          | Aspire X1470                | [323c95ffdc](https://linux-hardware.org/?probe=323c95ffdc) | Feb 10, 2022 |
| ASUSTek       | Q87M-E                      | [a34ad8b81e](https://linux-hardware.org/?probe=a34ad8b81e) | Feb 09, 2022 |
| ASRock        | X570M Pro4                  | [ebf8ed89a1](https://linux-hardware.org/?probe=ebf8ed89a1) | Feb 09, 2022 |
| AOpen         | i945GCt-DN 558ET10I120      | [b18526bb51](https://linux-hardware.org/?probe=b18526bb51) | Feb 09, 2022 |
| Gigabyte      | 970A-D3P                    | [23ac2f5563](https://linux-hardware.org/?probe=23ac2f5563) | Feb 08, 2022 |
| Dell          | 0HP962                      | [3dd3f98208](https://linux-hardware.org/?probe=3dd3f98208) | Feb 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [11369f4292](https://linux-hardware.org/?probe=11369f4292) | Feb 08, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [583f0f5bcc](https://linux-hardware.org/?probe=583f0f5bcc) | Feb 08, 2022 |
| Shuttle       | FH270                       | [d43be8b1a4](https://linux-hardware.org/?probe=d43be8b1a4) | Feb 08, 2022 |
| HP            | 82F2                        | [75ddf923ec](https://linux-hardware.org/?probe=75ddf923ec) | Feb 07, 2022 |
| Dell          | 0CKCXH A04                  | [a9815c1942](https://linux-hardware.org/?probe=a9815c1942) | Feb 07, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [487aa43e66](https://linux-hardware.org/?probe=487aa43e66) | Feb 07, 2022 |
| ASUSTek       | P5Q                         | [52e57261d3](https://linux-hardware.org/?probe=52e57261d3) | Feb 07, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [a87409099b](https://linux-hardware.org/?probe=a87409099b) | Feb 07, 2022 |
| ASUSTek       | Maximus VIII HERO           | [e0da1ac4f2](https://linux-hardware.org/?probe=e0da1ac4f2) | Feb 06, 2022 |
| ASUSTek       | P5Q                         | [1fc7c3bed9](https://linux-hardware.org/?probe=1fc7c3bed9) | Feb 06, 2022 |
| MSI           | 2AE0                        | [e9c3abdda9](https://linux-hardware.org/?probe=e9c3abdda9) | Feb 06, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [9315814633](https://linux-hardware.org/?probe=9315814633) | Feb 06, 2022 |
| MSI           | B450M GAMING PLUS           | [5bcf69d905](https://linux-hardware.org/?probe=5bcf69d905) | Feb 06, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [4c27e1f600](https://linux-hardware.org/?probe=4c27e1f600) | Feb 05, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [055aea6734](https://linux-hardware.org/?probe=055aea6734) | Feb 05, 2022 |
| Gigabyte      | X170-Extreme ECC            | [0ffb32b32d](https://linux-hardware.org/?probe=0ffb32b32d) | Feb 05, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [e6ff5f1893](https://linux-hardware.org/?probe=e6ff5f1893) | Feb 04, 2022 |
| MSI           | A320M-A PRO MAX             | [6f0d60dffa](https://linux-hardware.org/?probe=6f0d60dffa) | Feb 04, 2022 |
| ASUSTek       | P8H61-M LX PLUS             | [943e822e1c](https://linux-hardware.org/?probe=943e822e1c) | Feb 04, 2022 |
| ASUSTek       | P8H77-M                     | [9f9151546a](https://linux-hardware.org/?probe=9f9151546a) | Feb 03, 2022 |
| ASUSTek       | P8H77-M                     | [401d8111bd](https://linux-hardware.org/?probe=401d8111bd) | Feb 03, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [a62e52fe98](https://linux-hardware.org/?probe=a62e52fe98) | Feb 03, 2022 |
| ASUSTek       | SABERTOOTH X79              | [52d5157fd9](https://linux-hardware.org/?probe=52d5157fd9) | Feb 02, 2022 |
| ASUSTek       | SABERTOOTH X79              | [c70d2672d3](https://linux-hardware.org/?probe=c70d2672d3) | Feb 02, 2022 |
| HP            | 1905                        | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| ASRock        | B450 Pro4                   | [01eb76fa65](https://linux-hardware.org/?probe=01eb76fa65) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [b4c7f57d86](https://linux-hardware.org/?probe=b4c7f57d86) | Feb 01, 2022 |
| Dell          | 0T2HR0 A02                  | [2cfe7d7f31](https://linux-hardware.org/?probe=2cfe7d7f31) | Jan 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [96e168beb8](https://linux-hardware.org/?probe=96e168beb8) | Jan 31, 2022 |
| MSI           | B450-A PRO MAX              | [8ee3d68631](https://linux-hardware.org/?probe=8ee3d68631) | Jan 30, 2022 |
| Gigabyte      | A520M S2H                   | [ccbf2ec4f5](https://linux-hardware.org/?probe=ccbf2ec4f5) | Jan 29, 2022 |
| ASUSTek       | P5G41T-M LX PLUS            | [f3a447ef83](https://linux-hardware.org/?probe=f3a447ef83) | Jan 29, 2022 |
| MSI           | A68HM-E33 V2                | [42abbebf28](https://linux-hardware.org/?probe=42abbebf28) | Jan 29, 2022 |
| Dell          | 0PP150 A00                  | [e8326f9b39](https://linux-hardware.org/?probe=e8326f9b39) | Jan 29, 2022 |
| Acer          | EG43M                       | [c1f5473ce0](https://linux-hardware.org/?probe=c1f5473ce0) | Jan 28, 2022 |
| Acer          | Aspire X1800                | [913dd4dcac](https://linux-hardware.org/?probe=913dd4dcac) | Jan 27, 2022 |
| ASUSTek       | SABERTOOTH X79              | [e7e1ef7da5](https://linux-hardware.org/?probe=e7e1ef7da5) | Jan 27, 2022 |
| ASUSTek       | M51BC                       | [b491c2ea72](https://linux-hardware.org/?probe=b491c2ea72) | Jan 27, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [b628f59fb9](https://linux-hardware.org/?probe=b628f59fb9) | Jan 26, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [9e892d9ea3](https://linux-hardware.org/?probe=9e892d9ea3) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [00cdb626d7](https://linux-hardware.org/?probe=00cdb626d7) | Jan 26, 2022 |
| ASUSTek       | SABERTOOTH X79              | [1a7bb804ea](https://linux-hardware.org/?probe=1a7bb804ea) | Jan 25, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a2ed61ffcd](https://linux-hardware.org/?probe=a2ed61ffcd) | Jan 24, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f48fe5a028](https://linux-hardware.org/?probe=f48fe5a028) | Jan 24, 2022 |
| Dell          | 0WF810                      | [254dc6cb82](https://linux-hardware.org/?probe=254dc6cb82) | Jan 24, 2022 |
| ASUSTek       | A68HM-K                     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| Gigabyte      | GA-870A-UD3                 | [5f82282e71](https://linux-hardware.org/?probe=5f82282e71) | Jan 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [3db2b36704](https://linux-hardware.org/?probe=3db2b36704) | Jan 23, 2022 |
| Gigabyte      | H97M-D3H                    | [1930d43eed](https://linux-hardware.org/?probe=1930d43eed) | Jan 22, 2022 |
| Intel         | DQ67EP AAG12529-306         | [f9da2268d2](https://linux-hardware.org/?probe=f9da2268d2) | Jan 22, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | [fd86396422](https://linux-hardware.org/?probe=fd86396422) | Jan 22, 2022 |
| Gigabyte      | B550M DS3H                  | [3bde56dd51](https://linux-hardware.org/?probe=3bde56dd51) | Jan 22, 2022 |
| HP            | 3396                        | [ab9f7e40a6](https://linux-hardware.org/?probe=ab9f7e40a6) | Jan 21, 2022 |
| Acer          | Aspire XC-230               | [432efbf702](https://linux-hardware.org/?probe=432efbf702) | Jan 21, 2022 |
| BESSTAR Te... | HM50                        | [ddc2e44fcc](https://linux-hardware.org/?probe=ddc2e44fcc) | Jan 21, 2022 |
| Acer          | Aspire XC-230               | [89352dde8f](https://linux-hardware.org/?probe=89352dde8f) | Jan 19, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [6aa075ea12](https://linux-hardware.org/?probe=6aa075ea12) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [ca7197e116](https://linux-hardware.org/?probe=ca7197e116) | Jan 18, 2022 |
| QTQD          | Unknown                     | [c339476e37](https://linux-hardware.org/?probe=c339476e37) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7451fd2f02](https://linux-hardware.org/?probe=7451fd2f02) | Jan 17, 2022 |
| Acer          | Predator G5900              | [ac6748b172](https://linux-hardware.org/?probe=ac6748b172) | Jan 17, 2022 |
| HP            | 828A                        | [63316bc040](https://linux-hardware.org/?probe=63316bc040) | Jan 16, 2022 |
| HP            | 828A                        | [5ecf3c1b51](https://linux-hardware.org/?probe=5ecf3c1b51) | Jan 15, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 371      | 15.74%  |
| Ubuntu 18.04                 | 201      | 8.53%   |
| Ubuntu 22.04                 | 87       | 3.69%   |
| OpenMandriva 4.2             | 62       | 2.63%   |
| OpenMandriva 4.3             | 53       | 2.25%   |
| Linux Mint 20.3              | 50       | 2.12%   |
| Pop!_OS 20.04                | 48       | 2.04%   |
| Xubuntu 20.04                | 47       | 1.99%   |
| Pop!_OS 22.04                | 43       | 1.82%   |
| Linux Mint 20.1              | 43       | 1.82%   |
| KDE neon 20.04               | 43       | 1.82%   |
| Debian 11                    | 43       | 1.82%   |
| Manjaro                      | 42       | 1.78%   |
| Pop!_OS 21.04                | 41       | 1.74%   |
| Zorin 16                     | 33       | 1.4%    |
| Linux Mint 19.3              | 33       | 1.4%    |
| Fedora 33                    | 32       | 1.36%   |
| Arch Rolling                 | 32       | 1.36%   |
| Linux Mint 20                | 30       | 1.27%   |
| Pop!_OS 20.10                | 29       | 1.23%   |
| Linux Mint 20.2              | 29       | 1.23%   |
| OpenMandriva 23.01           | 28       | 1.19%   |
| Arch                         | 28       | 1.19%   |
| Fedora 32                    | 27       | 1.15%   |
| ArcoLinux Rolling            | 27       | 1.15%   |
| Ubuntu 19.10                 | 25       | 1.06%   |
| Fedora 34                    | 25       | 1.06%   |
| Ubuntu 21.10                 | 24       | 1.02%   |
| Ubuntu 20.10                 | 24       | 1.02%   |
| Zorin 15                     | 23       | 0.98%   |
| Ubuntu 21.04                 | 21       | 0.89%   |
| Pop!_OS 21.10                | 21       | 0.89%   |
| Fedora 35                    | 21       | 0.89%   |
| Fedora 36                    | 19       | 0.81%   |
| Ubuntu 19.04                 | 18       | 0.76%   |
| OpenMandriva 4.50            | 18       | 0.76%   |
| Debian 10                    | 17       | 0.72%   |
| Linux Mint 19.2              | 15       | 0.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 13       | 0.55%   |
| CentOS 7                     | 13       | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 765      | 34.18%  |
| Linux Mint    | 208      | 9.29%   |
| Pop!_OS       | 176      | 7.86%   |
| OpenMandriva  | 164      | 7.33%   |
| Fedora        | 134      | 5.99%   |
| Manjaro       | 96       | 4.29%   |
| Debian        | 79       | 3.53%   |
| Xubuntu       | 68       | 3.04%   |
| Zorin         | 60       | 2.68%   |
| Arch          | 60       | 2.68%   |
| KDE neon      | 53       | 2.37%   |
| ROSA          | 38       | 1.7%    |
| Kubuntu       | 34       | 1.52%   |
| ArcoLinux     | 28       | 1.25%   |
| Gentoo        | 23       | 1.03%   |
| CentOS        | 20       | 0.89%   |
| Elementary    | 17       | 0.76%   |
| openSUSE      | 16       | 0.71%   |
| Ubuntu MATE   | 15       | 0.67%   |
| Lubuntu       | 15       | 0.67%   |
| EndeavourOS   | 14       | 0.63%   |
| Ubuntu Unity  | 12       | 0.54%   |
| BlackPanther  | 12       | 0.54%   |
| LMDE          | 11       | 0.49%   |
| Endless       | 11       | 0.49%   |
| Ubuntu Budgie | 8        | 0.36%   |
| Nobara        | 8        | 0.36%   |
| Clear Linux   | 7        | 0.31%   |
| Solus         | 5        | 0.22%   |
| RHEL          | 5        | 0.22%   |
| RHCOS         | 5        | 0.22%   |
| Garuda Linux  | 5        | 0.22%   |
| Reborn OS     | 4        | 0.18%   |
| Makulu        | 4        | 0.18%   |
| LinuxFX       | 4        | 0.18%   |
| Linux Lite    | 4        | 0.18%   |
| Slackware     | 3        | 0.13%   |
| Rocky Linux   | 3        | 0.13%   |
| NixOS         | 3        | 0.13%   |
| MX            | 3        | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 61       | 2.32%   |
| 5.16.7-desktop-1omv4003         | 52       | 1.98%   |
| 5.4.0-42-generic                | 34       | 1.29%   |
| 5.4.0-58-generic                | 29       | 1.1%    |
| 5.15.0-56-generic               | 28       | 1.07%   |
| 6.1.1-desktop-1omv2290          | 26       | 0.99%   |
| 5.4.0-48-generic                | 25       | 0.95%   |
| 5.11.0-40-generic               | 24       | 0.91%   |
| 5.13.0-39-generic               | 23       | 0.87%   |
| 5.4.0-52-generic                | 22       | 0.84%   |
| 5.8.0-7630-generic              | 20       | 0.76%   |
| 5.4.0-54-generic                | 20       | 0.76%   |
| 5.3.0-40-generic                | 20       | 0.76%   |
| 5.15.0-48-generic               | 20       | 0.76%   |
| 5.11.0-7620-generic             | 20       | 0.76%   |
| 5.4.0-66-generic                | 18       | 0.68%   |
| 5.4.0-29-generic                | 18       | 0.68%   |
| 5.4.0-26-generic                | 18       | 0.68%   |
| 5.15.0-52-generic               | 17       | 0.65%   |
| 5.8.0-50-generic                | 16       | 0.61%   |
| 5.4.0-7634-generic              | 16       | 0.61%   |
| 5.4.0-56-generic                | 16       | 0.61%   |
| 5.15.0-58-generic               | 16       | 0.61%   |
| 5.15.0-47-generic               | 16       | 0.61%   |
| 5.4.0-37-generic                | 15       | 0.57%   |
| 5.4.0-33-generic                | 15       | 0.57%   |
| 5.15.0-41-generic               | 15       | 0.57%   |
| 5.0.0-37-generic                | 15       | 0.57%   |
| 5.4.0-74-generic                | 14       | 0.53%   |
| 5.4.0-40-generic                | 14       | 0.53%   |
| 5.3.0-46-generic                | 14       | 0.53%   |
| 6.0.6-76060006-generic          | 13       | 0.49%   |
| 5.8.0-44-generic                | 12       | 0.46%   |
| 5.3.0-42-generic                | 12       | 0.46%   |
| 5.15.0-53-generic               | 12       | 0.46%   |
| 5.13.0-40-generic               | 12       | 0.46%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 12       | 0.46%   |
| 5.4.0-47-generic                | 11       | 0.42%   |
| 5.11.0-27-generic               | 11       | 0.42%   |
| 4.18.16-desktop-1bP             | 11       | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 501      | 20.49%  |
| 4.15.0  | 165      | 6.75%   |
| 5.15.0  | 160      | 6.54%   |
| 5.8.0   | 151      | 6.18%   |
| 5.11.0  | 141      | 5.77%   |
| 5.13.0  | 123      | 5.03%   |
| 5.3.0   | 109      | 4.46%   |
| 5.10.14 | 62       | 2.54%   |
| 5.0.0   | 55       | 2.25%   |
| 4.18.0  | 53       | 2.17%   |
| 5.16.7  | 52       | 2.13%   |
| 5.10.0  | 40       | 1.64%   |
| 6.1.1   | 31       | 1.27%   |
| 4.19.0  | 17       | 0.7%    |
| 6.0.6   | 15       | 0.61%   |
| 5.19.0  | 15       | 0.61%   |
| 4.4.0   | 13       | 0.53%   |
| 5.17.5  | 12       | 0.49%   |
| 4.9.20  | 12       | 0.49%   |
| 3.10.0  | 12       | 0.49%   |
| 6.0.12  | 11       | 0.45%   |
| 5.14.0  | 11       | 0.45%   |
| 4.18.16 | 11       | 0.45%   |
| 5.16.11 | 9        | 0.37%   |
| 5.12.4  | 9        | 0.37%   |
| 4.9.60  | 9        | 0.37%   |
| 6.0.0   | 8        | 0.33%   |
| 5.15.5  | 8        | 0.33%   |
| 5.5.7   | 7        | 0.29%   |
| 5.4.12  | 7        | 0.29%   |
| 5.19.9  | 7        | 0.29%   |
| 5.18.12 | 6        | 0.25%   |
| 5.15.7  | 6        | 0.25%   |
| 5.13.19 | 6        | 0.25%   |
| 5.11.16 | 6        | 0.25%   |
| 6.0.8   | 5        | 0.2%    |
| 5.9.16  | 5        | 0.2%    |
| 5.9.1   | 5        | 0.2%    |
| 5.9.0   | 5        | 0.2%    |
| 5.8.15  | 5        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 540      | 22.4%   |
| 5.15    | 224      | 9.29%   |
| 5.8     | 192      | 7.96%   |
| 5.11    | 168      | 6.97%   |
| 4.15    | 165      | 6.84%   |
| 5.13    | 150      | 6.22%   |
| 5.10    | 149      | 6.18%   |
| 5.3     | 120      | 4.98%   |
| 5.16    | 91       | 3.77%   |
| 4.18    | 64       | 2.65%   |
| 5.0     | 60       | 2.49%   |
| 6.0     | 55       | 2.28%   |
| 5.19    | 43       | 1.78%   |
| 6.1     | 41       | 1.7%    |
| 5.12    | 37       | 1.53%   |
| 5.9     | 36       | 1.49%   |
| 5.17    | 35       | 1.45%   |
| 5.14    | 35       | 1.45%   |
| 4.9     | 35       | 1.45%   |
| 5.18    | 34       | 1.41%   |
| 5.6     | 30       | 1.24%   |
| 5.7     | 24       | 1%      |
| 4.19    | 23       | 0.95%   |
| 5.5     | 14       | 0.58%   |
| 4.4     | 13       | 0.54%   |
| 3.10    | 12       | 0.5%    |
| 5.2     | 6        | 0.25%   |
| 4.13    | 4        | 0.17%   |
| 4.1     | 4        | 0.17%   |
| 5.1     | 1        | 0.04%   |
| 4.17    | 1        | 0.04%   |
| 4.16    | 1        | 0.04%   |
| 4.14    | 1        | 0.04%   |
| 4.12    | 1        | 0.04%   |
| 4.11    | 1        | 0.04%   |
| 4.10    | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2107     | 98.27%  |
| i686   | 35       | 1.63%   |
| mips64 | 1        | 0.05%   |
| armv7l | 1        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 963      | 42.69%  |
| KDE5             | 355      | 15.74%  |
| Unknown          | 316      | 14.01%  |
| X-Cinnamon       | 164      | 7.27%   |
| XFCE             | 152      | 6.74%   |
| KDE              | 67       | 2.97%   |
| MATE             | 53       | 2.35%   |
| KDE4             | 30       | 1.33%   |
| Cinnamon         | 28       | 1.24%   |
| LXQt             | 21       | 0.93%   |
| Pantheon         | 16       | 0.71%   |
| i3               | 16       | 0.71%   |
| Budgie           | 16       | 0.71%   |
| Unity            | 12       | 0.53%   |
| LXDE             | 10       | 0.44%   |
| GNOME Flashback  | 9        | 0.4%    |
| Deepin           | 6        | 0.27%   |
| GNOME Classic    | 5        | 0.22%   |
| awesome          | 4        | 0.18%   |
| sway             | 2        | 0.09%   |
| Openbox          | 2        | 0.09%   |
| DWM              | 2        | 0.09%   |
| ubuntustudio     | 1        | 0.04%   |
| trinity          | 1        | 0.04%   |
| river            | 1        | 0.04%   |
| qtile            | 1        | 0.04%   |
| Lubuntu          | 1        | 0.04%   |
| lightdm-xsession | 1        | 0.04%   |
| LeftWM           | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1784     | 80.98%  |
| Wayland | 214      | 9.71%   |
| Unknown | 145      | 6.58%   |
| Tty     | 58       | 2.63%   |
| Web     | 2        | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1265     | 56.93%  |
| SDDM    | 316      | 14.22%  |
| GDM     | 214      | 9.63%   |
| GDM3    | 170      | 7.65%   |
| LightDM | 156      | 7.02%   |
| TDM     | 58       | 2.61%   |
| KDM     | 25       | 1.13%   |
| XDM     | 7        | 0.32%   |
| SLiM    | 7        | 0.32%   |
| GREETD  | 2        | 0.09%   |
| MDM     | 1        | 0.05%   |
| LXDM    | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_CA      | 1161     | 52.39%  |
| en_US      | 536      | 24.19%  |
| Unknown    | 267      | 12.05%  |
| fr_CA      | 156      | 7.04%   |
| C          | 38       | 1.71%   |
| fr_FR      | 22       | 0.99%   |
| en_GB      | 9        | 0.41%   |
| en_AU      | 4        | 0.18%   |
| POSIX      | 3        | 0.14%   |
| zh_TW      | 2        | 0.09%   |
| zh_CN      | 2        | 0.09%   |
| ru_RU      | 2        | 0.09%   |
| de_DE      | 2        | 0.09%   |
| uk_UA      | 1        | 0.05%   |
| pt_BR      | 1        | 0.05%   |
| pa_IN      | 1        | 0.05%   |
| iu_CA      | 1        | 0.05%   |
| hu_HU      | 1        | 0.05%   |
| es_ES      | 1        | 0.05%   |
| es_BO      | 1        | 0.05%   |
| en_ZM      | 1        | 0.05%   |
| en_US.UTF8 | 1        | 0.05%   |
| en_IN      | 1        | 0.05%   |
| de_CH      | 1        | 0.05%   |
| C.UTF8     | 1        | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1324     | 60.21%  |
| EFI  | 875      | 39.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1665     | 75.48%  |
| Overlay | 195      | 8.84%   |
| Btrfs   | 156      | 7.07%   |
| Unknown | 89       | 4.03%   |
| Xfs     | 53       | 2.4%    |
| Zfs     | 20       | 0.91%   |
| Ext2    | 10       | 0.45%   |
| Ext3    | 6        | 0.27%   |
| F2fs    | 5        | 0.23%   |
| Tmpfs   | 4        | 0.18%   |
| Jfs     | 2        | 0.09%   |
| XXX4    | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1296     | 58.99%  |
| GPT     | 648      | 29.49%  |
| MBR     | 253      | 11.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1750     | 79.37%  |
| Yes       | 455      | 20.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1509     | 68.68%  |
| Yes       | 688      | 31.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 622      | 29.05%  |
| Gigabyte Technology | 288      | 13.45%  |
| MSI                 | 233      | 10.88%  |
| Dell                | 229      | 10.7%   |
| Hewlett-Packard     | 181      | 8.45%   |
| ASRock              | 123      | 5.74%   |
| Lenovo              | 121      | 5.65%   |
| Acer                | 109      | 5.09%   |
| Intel               | 45       | 2.1%    |
| Pegatron            | 27       | 1.26%   |
| Foxconn             | 26       | 1.21%   |
| Alienware           | 17       | 0.79%   |
| Unknown             | 15       | 0.7%    |
| Gateway             | 14       | 0.65%   |
| ECS                 | 10       | 0.47%   |
| Biostar             | 10       | 0.47%   |
| Supermicro          | 8        | 0.37%   |
| Apple               | 8        | 0.37%   |
| ZOTAC               | 4        | 0.19%   |
| EVGA                | 4        | 0.19%   |
| BESSTAR Tech        | 4        | 0.19%   |
| ASRockRack          | 4        | 0.19%   |
| TYAN Computer       | 3        | 0.14%   |
| Huanan              | 3        | 0.14%   |
| XFX                 | 2        | 0.09%   |
| Shuttle             | 2        | 0.09%   |
| OEM_MB              | 2        | 0.09%   |
| Minix               | 2        | 0.09%   |
| eMachines           | 2        | 0.09%   |
| AZW                 | 2        | 0.09%   |
| AMI                 | 2        | 0.09%   |
| System76            | 1        | 0.05%   |
| Sun Microsystems    | 1        | 0.05%   |
| Samsung Electronics | 1        | 0.05%   |
| Quanta              | 1        | 0.05%   |
| QTQD                | 1        | 0.05%   |
| PCChips             | 1        | 0.05%   |
| NCR                 | 1        | 0.05%   |
| MACHINIST           | 1        | 0.05%   |
| JGINYUE             | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 57       | 2.66%   |
| ASUS TUF Gaming X570-PLUS      | 19       | 0.89%   |
| Unknown                        | 18       | 0.84%   |
| MSI MS-7C02                    | 13       | 0.61%   |
| Dell OptiPlex 790              | 13       | 0.61%   |
| MSI MS-7C37                    | 12       | 0.56%   |
| HP Z400 Workstation            | 12       | 0.56%   |
| ASUS PRIME B450M-A             | 12       | 0.56%   |
| ASRock B450M Pro4              | 11       | 0.51%   |
| Dell OptiPlex 780              | 10       | 0.47%   |
| ASUS ROG STRIX B450-F GAMING   | 10       | 0.47%   |
| ASUS M5A97 LE R2.0             | 10       | 0.47%   |
| MSI MS-7C84                    | 9        | 0.42%   |
| MSI MS-7C56                    | 9        | 0.42%   |
| Gigabyte B450 AORUS PRO WIFI   | 9        | 0.42%   |
| Dell OptiPlex 7010             | 9        | 0.42%   |
| ASUS M5A99FX PRO R2.0          | 9        | 0.42%   |
| MSI MS-7C95                    | 8        | 0.37%   |
| MSI MS-7693                    | 8        | 0.37%   |
| HP Compaq Pro 6300 SFF         | 8        | 0.37%   |
| ASUS M5A97 R2.0                | 8        | 0.37%   |
| MSI MS-7B85                    | 7        | 0.33%   |
| MSI MS-7B79                    | 7        | 0.33%   |
| HP EliteDesk 800 G1 SFF        | 7        | 0.33%   |
| HP Compaq Elite 8300 SFF       | 7        | 0.33%   |
| HP Compaq 8200 Elite SFF PC    | 7        | 0.33%   |
| Gigabyte B450M DS3H            | 7        | 0.33%   |
| Dell OptiPlex 760              | 7        | 0.33%   |
| Dell OptiPlex 755              | 7        | 0.33%   |
| ASUS PRIME X570-P              | 7        | 0.33%   |
| ASUS PRIME A320M-K             | 7        | 0.33%   |
| MSI MS-7C91                    | 6        | 0.28%   |
| MSI MS-7B86                    | 6        | 0.28%   |
| MSI MS-7885                    | 6        | 0.28%   |
| MSI MS-7721                    | 6        | 0.28%   |
| Gigabyte X570 AORUS ELITE WIFI | 6        | 0.28%   |
| Gigabyte GA-78LMT-USB3         | 6        | 0.28%   |
| Gigabyte 990FXA-UD3            | 6        | 0.28%   |
| Gateway DX4860                 | 6        | 0.28%   |
| Dell XPS 8940                  | 6        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 113      | 5.28%   |
| ASUS PRIME             | 101      | 4.72%   |
| Lenovo ThinkCentre     | 92       | 4.3%    |
| Acer Aspire            | 92       | 4.3%    |
| ASUS ROG               | 76       | 3.55%   |
| HP Compaq              | 72       | 3.36%   |
| ASUS All               | 57       | 2.66%   |
| ASUS TUF               | 44       | 2.06%   |
| Dell XPS               | 28       | 1.31%   |
| Dell Precision         | 25       | 1.17%   |
| HP EliteDesk           | 23       | 1.07%   |
| Gigabyte X570          | 23       | 1.07%   |
| Dell Inspiron          | 23       | 1.07%   |
| ASUS M5A97             | 23       | 1.07%   |
| Gigabyte B450          | 20       | 0.93%   |
| Lenovo ThinkStation    | 18       | 0.84%   |
| ASRock B450M           | 18       | 0.84%   |
| Unknown                | 18       | 0.84%   |
| ASUS SABERTOOTH        | 17       | 0.79%   |
| Gigabyte Z390          | 15       | 0.7%    |
| Dell Vostro            | 15       | 0.7%    |
| ASUS P8Z77-V           | 14       | 0.65%   |
| MSI MS-7C02            | 13       | 0.61%   |
| Dell Studio            | 13       | 0.61%   |
| MSI MS-7C37            | 12       | 0.56%   |
| HP Z400                | 12       | 0.56%   |
| Alienware Aurora       | 11       | 0.51%   |
| Gigabyte GA-78LMT-USB3 | 10       | 0.47%   |
| MSI MS-7C84            | 9        | 0.42%   |
| MSI MS-7C56            | 9        | 0.42%   |
| HP ProDesk             | 9        | 0.42%   |
| HP Pavilion            | 9        | 0.42%   |
| Gigabyte B450M         | 9        | 0.42%   |
| ASUS P8H61-M           | 9        | 0.42%   |
| ASUS M5A99FX           | 9        | 0.42%   |
| ASUS CROSSHAIR         | 9        | 0.42%   |
| MSI MS-7C95            | 8        | 0.37%   |
| MSI MS-7693            | 8        | 0.37%   |
| ASUS P8P67             | 8        | 0.37%   |
| ASUS M5A78L-M          | 8        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 218      | 10.18%  |
| 2012    | 209      | 9.76%   |
| 2013    | 185      | 8.64%   |
| 2011    | 181      | 8.45%   |
| 2019    | 176      | 8.22%   |
| 2020    | 155      | 7.24%   |
| 2014    | 138      | 6.45%   |
| 2017    | 132      | 6.17%   |
| 2010    | 132      | 6.17%   |
| 2009    | 124      | 5.79%   |
| 2008    | 112      | 5.23%   |
| 2015    | 76       | 3.55%   |
| 2007    | 76       | 3.55%   |
| 2016    | 71       | 3.32%   |
| 2021    | 64       | 2.99%   |
| 2006    | 39       | 1.82%   |
| 2022    | 32       | 1.49%   |
| 2005    | 14       | 0.65%   |
| 2004    | 4        | 0.19%   |
| Unknown | 3        | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2141     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2086     | 96.89%  |
| Enabled  | 67       | 3.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2138     | 99.86%  |
| Yes  | 3        | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 604      | 27.67%  |
| 8.01-16.0       | 404      | 18.51%  |
| 32.01-64.0      | 375      | 17.18%  |
| 4.01-8.0        | 266      | 12.19%  |
| 3.01-4.0        | 251      | 11.5%   |
| 64.01-256.0     | 118      | 5.41%   |
| 24.01-32.0      | 71       | 3.25%   |
| 1.01-2.0        | 58       | 2.66%   |
| 2.01-3.0        | 22       | 1.01%   |
| 0.51-1.0        | 12       | 0.55%   |
| More than 256.0 | 1        | 0.05%   |
| Unknown         | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 844      | 35.09%  |
| 2.01-3.0    | 555      | 23.08%  |
| 4.01-8.0    | 371      | 15.43%  |
| 3.01-4.0    | 289      | 12.02%  |
| 0.51-1.0    | 154      | 6.4%    |
| 8.01-16.0   | 123      | 5.11%   |
| 0.01-0.5    | 27       | 1.12%   |
| 32.01-64.0  | 16       | 0.67%   |
| 24.01-32.0  | 12       | 0.5%    |
| 16.01-24.0  | 11       | 0.46%   |
| 64.01-256.0 | 2        | 0.08%   |
| Unknown     | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 835      | 36.82%  |
| 2      | 578      | 25.49%  |
| 3      | 340      | 14.99%  |
| 4      | 228      | 10.05%  |
| 5      | 127      | 5.6%    |
| 6      | 56       | 2.47%   |
| 7      | 35       | 1.54%   |
| 0      | 26       | 1.15%   |
| 8      | 17       | 0.75%   |
| 9      | 10       | 0.44%   |
| 10     | 7        | 0.31%   |
| 11     | 5        | 0.22%   |
| 13     | 2        | 0.09%   |
| 12     | 2        | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1133     | 51.97%  |
| No        | 1047     | 48.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2118     | 98.93%  |
| No        | 23       | 1.07%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1117     | 51.33%  |
| Yes       | 1059     | 48.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1394     | 64%     |
| Yes       | 784      | 36%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 2141     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Toronto         | 220      | 9.73%   |
| Montreal        | 206      | 9.11%   |
| Vancouver       | 100      | 4.42%   |
| Ottawa          | 95       | 4.2%    |
| Calgary         | 85       | 3.76%   |
| Edmonton        | 64       | 2.83%   |
| Québec         | 39       | 1.72%   |
| Winnipeg        | 36       | 1.59%   |
| Surrey          | 29       | 1.28%   |
| Saskatoon       | 26       | 1.15%   |
| Mississauga     | 26       | 1.15%   |
| Kitchener       | 23       | 1.02%   |
| Hamilton        | 23       | 1.02%   |
| Laval           | 22       | 0.97%   |
| Gatineau        | 21       | 0.93%   |
| Victoria        | 20       | 0.88%   |
| Oshawa          | 20       | 0.88%   |
| Windsor         | 19       | 0.84%   |
| London          | 18       | 0.8%    |
| Regina          | 17       | 0.75%   |
| Halifax         | 16       | 0.71%   |
| Burnaby         | 16       | 0.71%   |
| Trois-Rivières | 15       | 0.66%   |
| Sherbrooke      | 15       | 0.66%   |
| Scarborough     | 15       | 0.66%   |
| Kingston        | 15       | 0.66%   |
| Richmond Hill   | 14       | 0.62%   |
| Oakville        | 14       | 0.62%   |
| Barrie          | 13       | 0.57%   |
| Sherwood Park   | 12       | 0.53%   |
| Red Deer        | 12       | 0.53%   |
| North Vancouver | 12       | 0.53%   |
| Kelowna         | 12       | 0.53%   |
| Brampton        | 12       | 0.53%   |
| Thornhill       | 11       | 0.49%   |
| Airdrie         | 11       | 0.49%   |
| Spruce Grove    | 10       | 0.44%   |
| Coquitlam       | 10       | 0.44%   |
| Chilliwack      | 10       | 0.44%   |
| Waterloo        | 9        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 926      | 1671   | 23.01%  |
| Seagate                   | 907      | 1680   | 22.54%  |
| Samsung Electronics       | 522      | 867    | 12.97%  |
| Kingston                  | 264      | 380    | 6.56%   |
| SanDisk                   | 163      | 205    | 4.05%   |
| Hitachi                   | 149      | 207    | 3.7%    |
| Toshiba                   | 134      | 183    | 3.33%   |
| Crucial                   | 130      | 183    | 3.23%   |
| A-DATA Technology         | 120      | 162    | 2.98%   |
| Intel                     | 95       | 148    | 2.36%   |
| Unknown                   | 59       | 89     | 1.47%   |
| Phison                    | 39       | 63     | 0.97%   |
| OCZ                       | 29       | 40     | 0.72%   |
| HGST                      | 29       | 42     | 0.72%   |
| Corsair                   | 25       | 31     | 0.62%   |
| Micron Technology         | 24       | 29     | 0.6%    |
| Silicon Motion            | 22       | 33     | 0.55%   |
| SK hynix                  | 21       | 22     | 0.52%   |
| SPCC                      | 19       | 22     | 0.47%   |
| PNY                       | 17       | 23     | 0.42%   |
| Micron/Crucial Technology | 17       | 28     | 0.42%   |
| Patriot                   | 16       | 20     | 0.4%    |
| Mushkin                   | 16       | 18     | 0.4%    |
| Maxtor                    | 16       | 22     | 0.4%    |
| XPG                       | 15       | 24     | 0.37%   |
| Team                      | 14       | 15     | 0.35%   |
| Hewlett-Packard           | 13       | 23     | 0.32%   |
| China                     | 13       | 16     | 0.32%   |
| ASMT                      | 12       | 15     | 0.3%    |
| JMicron Technology        | 10       | 16     | 0.25%   |
| SABRENT                   | 8        | 12     | 0.2%    |
| LITEONIT                  | 8        | 9      | 0.2%    |
| KingFast                  | 8        | 9      | 0.2%    |
| Phison Electronics        | 7        | 9      | 0.17%   |
| Realtek Semiconductor     | 6        | 7      | 0.15%   |
| ADATA Technology          | 6        | 8      | 0.15%   |
| TO Exter                  | 5        | 5      | 0.12%   |
| T-FORCE                   | 5        | 5      | 0.12%   |
| KingDian                  | 5        | 5      | 0.12%   |
| Fujitsu                   | 5        | 6      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 65       | 1.33%   |
| Seagate ST2000DM008-2FR102 2TB   | 63       | 1.29%   |
| Samsung SSD 850 EVO 250GB        | 63       | 1.29%   |
| Samsung SSD 860 EVO 500GB        | 51       | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB   | 49       | 1.01%   |
| Samsung SSD 850 EVO 500GB        | 44       | 0.9%    |
| WDC WD10EZEX-08WN4A0 1TB         | 42       | 0.86%   |
| Seagate ST500DM002-1BD142 500GB  | 42       | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB   | 41       | 0.84%   |
| SanDisk NVMe SSD Drive 500GB     | 38       | 0.78%   |
| Samsung NVMe SSD Drive 500GB     | 38       | 0.78%   |
| Seagate ST2000DM006-2DM164 2TB   | 37       | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB   | 36       | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB   | 36       | 0.74%   |
| Kingston SA400S37120G 120GB SSD  | 36       | 0.74%   |
| Unknown SD/MMC/MS PRO 2GB        | 35       | 0.72%   |
| Kingston SA400S37480G 480GB SSD  | 35       | 0.72%   |
| Toshiba DT01ACA200 2TB           | 34       | 0.7%    |
| Seagate ST1000DM003-1ER162 1TB   | 34       | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 33       | 0.68%   |
| Samsung SSD 860 EVO 1TB          | 32       | 0.66%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 31       | 0.64%   |
| SanDisk NVMe SSD Drive 1TB       | 31       | 0.64%   |
| WDC WD20EARS-00MVWB0 2TB         | 28       | 0.57%   |
| Toshiba DT01ACA100 1TB           | 28       | 0.57%   |
| Seagate Expansion Desk 6TB       | 28       | 0.57%   |
| Seagate ST31000528AS 1TB         | 27       | 0.55%   |
| Seagate ST8000DM004-2CX188 8TB   | 26       | 0.53%   |
| Seagate ST3500418AS 500GB        | 26       | 0.53%   |
| Kingston SV300S37A120G 120GB SSD | 26       | 0.53%   |
| Seagate ST2000DM001-1CH164 2TB   | 25       | 0.51%   |
| Samsung SSD 860 EVO 250GB        | 23       | 0.47%   |
| Crucial CT1000MX500SSD1 1TB      | 23       | 0.47%   |
| Hitachi HDS721010CLA332 1TB      | 21       | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB   | 20       | 0.41%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 19       | 0.39%   |
| Seagate Expansion 240GB          | 19       | 0.39%   |
| Samsung NVMe SSD Drive 1TB       | 18       | 0.37%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 17       | 0.35%   |
| Seagate ST31000524AS 1TB         | 17       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 880      | 1617   | 41.57%  |
| WDC                 | 799      | 1412   | 37.74%  |
| Hitachi             | 149      | 207    | 7.04%   |
| Toshiba             | 124      | 171    | 5.86%   |
| Samsung Electronics | 37       | 48     | 1.75%   |
| Unknown             | 35       | 47     | 1.65%   |
| HGST                | 29       | 42     | 1.37%   |
| Maxtor              | 16       | 22     | 0.76%   |
| ASMT                | 11       | 14     | 0.52%   |
| SABRENT             | 8        | 12     | 0.38%   |
| Fujitsu             | 5        | 6      | 0.24%   |
| JMicron Technology  | 4        | 6      | 0.19%   |
| Apple               | 3        | 3      | 0.14%   |
| Maxone              | 2        | 3      | 0.09%   |
| Hewlett-Packard     | 2        | 9      | 0.09%   |
| USB3.0              | 1        | 2      | 0.05%   |
| USB 3.0             | 1        | 4      | 0.05%   |
| Quantum             | 1        | 1      | 0.05%   |
| QNAP                | 1        | 6      | 0.05%   |
| Pioneer             | 1        | 1      | 0.05%   |
| PHD 3.0             | 1        | 1      | 0.05%   |
| Maxtor 6            | 1        | 1      | 0.05%   |
| MaxDigital          | 1        | 1      | 0.05%   |
| KESU                | 1        | 2      | 0.05%   |
| External            | 1        | 1      | 0.05%   |
| DAS                 | 1        | 9      | 0.05%   |
| ASMT109x            | 1        | 1      | 0.05%   |
| ASMedia             | 1        | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 358      | 556    | 26.36%  |
| Kingston            | 233      | 337    | 17.16%  |
| WDC                 | 143      | 196    | 10.53%  |
| Crucial             | 117      | 159    | 8.62%   |
| A-DATA Technology   | 106      | 143    | 7.81%   |
| SanDisk             | 66       | 79     | 4.86%   |
| Intel               | 52       | 68     | 3.83%   |
| OCZ                 | 28       | 36     | 2.06%   |
| Seagate             | 23       | 31     | 1.69%   |
| Micron Technology   | 18       | 22     | 1.33%   |
| SPCC                | 17       | 20     | 1.25%   |
| PNY                 | 17       | 23     | 1.25%   |
| Patriot             | 16       | 20     | 1.18%   |
| Mushkin             | 15       | 17     | 1.1%    |
| Corsair             | 15       | 17     | 1.1%    |
| Team                | 14       | 15     | 1.03%   |
| China               | 13       | 16     | 0.96%   |
| LITEONIT            | 8        | 9      | 0.59%   |
| Hewlett-Packard     | 8        | 10     | 0.59%   |
| Toshiba             | 7        | 7      | 0.52%   |
| SK hynix            | 6        | 6      | 0.44%   |
| TO Exter            | 5        | 5      | 0.37%   |
| Transcend           | 4        | 4      | 0.29%   |
| TCSUNBOW            | 4        | 4      | 0.29%   |
| OWC                 | 4        | 11     | 0.29%   |
| LITEON              | 4        | 4      | 0.29%   |
| Lexar               | 4        | 5      | 0.29%   |
| KingDian            | 4        | 4      | 0.29%   |
| T-FORCE             | 3        | 3      | 0.22%   |
| KingFast            | 3        | 3      | 0.22%   |
| JMicron Technology  | 3        | 6      | 0.22%   |
| Dogfish             | 3        | 3      | 0.22%   |
| Vaseky              | 2        | 3      | 0.15%   |
| Timetec             | 2        | 5      | 0.15%   |
| SUNEAST             | 2        | 2      | 0.15%   |
| OCZ-VERTEX3         | 2        | 2      | 0.15%   |
| Drevo               | 2        | 2      | 0.15%   |
| ZOTAC               | 1        | 2      | 0.07%   |
| WDC WDBA            | 1        | 1      | 0.07%   |
| Verbatim            | 1        | 1      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1580     | 3650   | 48.04%  |
| SSD     | 1098     | 1885   | 33.38%  |
| NVMe    | 535      | 885    | 16.27%  |
| Unknown | 69       | 96     | 2.1%    |
| MMC     | 7        | 10     | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1971     | 5250   | 71.39%  |
| NVMe | 531      | 874    | 19.23%  |
| SAS  | 252      | 392    | 9.13%   |
| MMC  | 7        | 10     | 0.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1431     | 2539   | 45.4%   |
| 0.51-1.0   | 865      | 1465   | 27.44%  |
| 1.01-2.0   | 424      | 738    | 13.45%  |
| 3.01-4.0   | 153      | 250    | 4.85%   |
| 4.01-10.0  | 152      | 287    | 4.82%   |
| 2.01-3.0   | 117      | 228    | 3.71%   |
| 10.01-20.0 | 9        | 22     | 0.29%   |
| 20.01-50.0 | 1        | 6      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 456      | 19.64%  |
| 251-500        | 396      | 17.05%  |
| 501-1000       | 357      | 15.37%  |
| More than 3000 | 304      | 13.09%  |
| 1001-2000      | 272      | 11.71%  |
| 1-20           | 149      | 6.42%   |
| 2001-3000      | 141      | 6.07%   |
| Unknown        | 96       | 4.13%   |
| 51-100         | 87       | 3.75%   |
| 21-50          | 64       | 2.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 836      | 34.79%  |
| 21-50          | 344      | 14.32%  |
| 101-250        | 262      | 10.9%   |
| 51-100         | 203      | 8.45%   |
| 251-500        | 174      | 7.24%   |
| 501-1000       | 164      | 6.82%   |
| 1001-2000      | 145      | 6.03%   |
| More than 3000 | 115      | 4.79%   |
| Unknown        | 96       | 4%      |
| 2001-3000      | 63       | 2.62%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 8        | 9      | 2.69%   |
| WDC WD2500HHTZ-04N21V0 250GB        | 5        | 5      | 1.68%   |
| WDC WD20EARS-00MVWB0 2TB            | 5        | 6      | 1.68%   |
| Seagate ST3500418AS 500GB           | 5        | 5      | 1.68%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4        | 17     | 1.35%   |
| Seagate ST31000528AS 1TB            | 4        | 4      | 1.35%   |
| Kingston SV300S37A120G 120GB SSD    | 4        | 6      | 1.35%   |
| Intel SSDSA1M080G2LE 80GB           | 4        | 4      | 1.35%   |
| WDC WD6400AAKS-22A7B2 640GB         | 3        | 3      | 1.01%   |
| WDC WD30EFRX-68EUZN0 3TB            | 3        | 3      | 1.01%   |
| WDC WD10EARX-00N0YB0 1TB            | 3        | 4      | 1.01%   |
| Seagate ST9500420AS 500GB           | 3        | 3      | 1.01%   |
| Seagate ST500LM021-1KJ152 500GB     | 3        | 4      | 1.01%   |
| Seagate ST31500341AS 1TB            | 3        | 3      | 1.01%   |
| Seagate ST2000DM001-1CH164 2TB      | 3        | 3      | 1.01%   |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 4      | 1.01%   |
| Samsung Electronics SSD 870 EVO 1TB | 3        | 4      | 1.01%   |
| Hitachi HDS721010CLA332 1TB         | 3        | 3      | 1.01%   |
| WDC WD6400AAKS-65Z7B0 640GB         | 2        | 3      | 0.67%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 2        | 2      | 0.67%   |
| WDC WD20EARS-00J2GB0 2TB            | 2        | 2      | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 2      | 0.67%   |
| WDC WD1001FALS-00J7B1 1TB           | 2        | 3      | 0.67%   |
| Seagate ST8000DM004-2CX188 8TB      | 2        | 4      | 0.67%   |
| Seagate ST500LT012-1DG142 500GB     | 2        | 2      | 0.67%   |
| Seagate ST500LM000-1EJ162 500GB     | 2        | 2      | 0.67%   |
| Seagate ST380013AS 80GB             | 2        | 2      | 0.67%   |
| Seagate ST3500630AS 500GB           | 2        | 2      | 0.67%   |
| Seagate ST3500410AS 500GB           | 2        | 2      | 0.67%   |
| Seagate ST3250823AS 250GB           | 2        | 2      | 0.67%   |
| Seagate ST32000542AS 2TB            | 2        | 3      | 0.67%   |
| Seagate ST31000524AS 1TB            | 2        | 2      | 0.67%   |
| Seagate ST31000333AS 1TB            | 2        | 2      | 0.67%   |
| Seagate ST3000DM001-1ER166 3TB      | 2        | 5      | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 3      | 0.67%   |
| Samsung Electronics HD642JJ 640GB   | 2        | 2      | 0.67%   |
| Samsung Electronics HD103SI 1TB     | 2        | 2      | 0.67%   |
| Kingston SA400S37480G 480GB SSD     | 2        | 2      | 0.67%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 2      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 103      | 136    | 36.27%  |
| Seagate             | 91       | 115    | 32.04%  |
| Samsung Electronics | 19       | 21     | 6.69%   |
| Hitachi             | 19       | 20     | 6.69%   |
| Kingston            | 14       | 19     | 4.93%   |
| Intel               | 8        | 8      | 2.82%   |
| A-DATA Technology   | 6        | 7      | 2.11%   |
| Crucial             | 5        | 6      | 1.76%   |
| Toshiba             | 4        | 4      | 1.41%   |
| Mushkin             | 2        | 2      | 0.7%    |
| LITEONIT            | 2        | 2      | 0.7%    |
| HGST                | 2        | 2      | 0.7%    |
| SK hynix            | 1        | 1      | 0.35%   |
| OCZ                 | 1        | 1      | 0.35%   |
| Maxtor              | 1        | 1      | 0.35%   |
| Hewlett-Packard     | 1        | 1      | 0.35%   |
| Fujitsu             | 1        | 1      | 0.35%   |
| Drevo               | 1        | 1      | 0.35%   |
| DAS                 | 1        | 3      | 0.35%   |
| China               | 1        | 1      | 0.35%   |
| ASMT                | 1        | 2      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 103      | 136    | 44.98%  |
| Seagate             | 91       | 115    | 39.74%  |
| Hitachi             | 19       | 20     | 8.3%    |
| Samsung Electronics | 7        | 8      | 3.06%   |
| Toshiba             | 3        | 3      | 1.31%   |
| HGST                | 2        | 2      | 0.87%   |
| Maxtor              | 1        | 1      | 0.44%   |
| Fujitsu             | 1        | 1      | 0.44%   |
| DAS                 | 1        | 3      | 0.44%   |
| ASMT                | 1        | 2      | 0.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 208      | 291    | 79.09%  |
| SSD  | 49       | 57     | 18.63%  |
| NVMe | 6        | 6      | 2.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Intel SSDSA1M160G2HP 160GB        | 1        | 1      | 50%     |
| Hewlett-Packard EF0450FARMV 450GB | 1        | 4      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Intel           | 1        | 1      | 50%     |
| Hewlett-Packard | 1        | 4      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1424     | 4197   | 58.05%  |
| Works    | 777      | 1970   | 31.68%  |
| Malfunc  | 250      | 354    | 10.19%  |
| Failed   | 2        | 5      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1357     | 43.24%  |
| AMD                              | 723      | 23.04%  |
| Samsung Electronics              | 192      | 6.12%   |
| SanDisk                          | 145      | 4.62%   |
| ASMedia Technology               | 134      | 4.27%   |
| Marvell Technology Group         | 111      | 3.54%   |
| JMicron Technology               | 86       | 2.74%   |
| Nvidia                           | 71       | 2.26%   |
| Phison Electronics               | 55       | 1.75%   |
| Kingston Technology Company      | 35       | 1.12%   |
| ADATA Technology                 | 34       | 1.08%   |
| Micron/Crucial Technology        | 31       | 0.99%   |
| Silicon Motion                   | 29       | 0.92%   |
| LSI Logic / Symbios Logic        | 22       | 0.7%    |
| SK hynix                         | 15       | 0.48%   |
| Silicon Image                    | 15       | 0.48%   |
| Broadcom / LSI                   | 13       | 0.41%   |
| Seagate Technology               | 11       | 0.35%   |
| Realtek Semiconductor            | 11       | 0.35%   |
| VIA Technologies                 | 9        | 0.29%   |
| Toshiba America Info Systems     | 6        | 0.19%   |
| Micron Technology                | 6        | 0.19%   |
| HighPoint Technologies           | 4        | 0.13%   |
| Silicon Integrated Systems [SiS] | 3        | 0.1%    |
| KIOXIA                           | 3        | 0.1%    |
| Integrated Technology Express    | 3        | 0.1%    |
| Hewlett-Packard                  | 3        | 0.1%    |
| Adaptec                          | 3        | 0.1%    |
| INNOGRIT                         | 2        | 0.06%   |
| ULi Electronics                  | 1        | 0.03%   |
| Shenzhen Longsys Electronics     | 1        | 0.03%   |
| Promise Technology               | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Loongson Technology              | 1        | 0.03%   |
| Apple                            | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 413      | 10.37%  |
| AMD 400 Series Chipset SATA Controller                                                  | 162      | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 147      | 3.69%   |
| Intel SATA Controller [RAID mode]                                                       | 136      | 3.41%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 127      | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 119      | 2.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 116      | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 113      | 2.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 112      | 2.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 91       | 2.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 84       | 2.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 84       | 2.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 70       | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 65       | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 62       | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 57       | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 51       | 1.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 47       | 1.18%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 46       | 1.15%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 42       | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 40       | 1%      |
| Intel 4 Series Chipset PT IDER Controller                                               | 40       | 1%      |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 37       | 0.93%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 36       | 0.9%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 35       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 35       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 35       | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 35       | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 33       | 0.83%   |
| Nvidia MCP61 SATA Controller                                                            | 33       | 0.83%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 33       | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 32       | 0.8%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 32       | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 32       | 0.8%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 32       | 0.8%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 31       | 0.78%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 31       | 0.78%   |
| Intel SSD 660P Series                                                                   | 29       | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 29       | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 28       | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1691     | 55.46%  |
| NVMe | 545      | 17.87%  |
| IDE  | 543      | 17.81%  |
| RAID | 230      | 7.54%   |
| SAS  | 29       | 0.95%   |
| SCSI | 11       | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 1355     | 63.29%  |
| AMD     | 783      | 36.57%  |
| Unknown | 2        | 0.09%   |
| ARM     | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 45       | 2.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 37       | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 35       | 1.63%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 34       | 1.58%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 33       | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 33       | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 31       | 1.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 27       | 1.26%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 26       | 1.21%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 24       | 1.12%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 24       | 1.12%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 22       | 1.02%   |
| AMD FX-8350 Eight-Core Processor       | 22       | 1.02%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 21       | 0.98%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 20       | 0.93%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 20       | 0.93%   |
| AMD FX-8320 Eight-Core Processor       | 20       | 0.93%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 19       | 0.88%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 18       | 0.84%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 18       | 0.84%   |
| AMD FX-6300 Six-Core Processor         | 18       | 0.84%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 17       | 0.79%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 17       | 0.79%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 17       | 0.79%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 16       | 0.74%   |
| AMD Ryzen 7 3800X 8-Core Processor     | 16       | 0.74%   |
| Intel Core i5 CPU 650 @ 3.20GHz        | 15       | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz      | 14       | 0.65%   |
| AMD Ryzen 7 2700 Eight-Core Processor  | 14       | 0.65%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 13       | 0.6%    |
| Intel Core i5-4460 CPU @ 3.20GHz       | 13       | 0.6%    |
| AMD Ryzen 5 2600X Six-Core Processor   | 13       | 0.6%    |
| Intel Core i9-9900K CPU @ 3.60GHz      | 12       | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 12       | 0.56%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 12       | 0.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 12       | 0.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 12       | 0.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 12       | 0.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 12       | 0.56%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 12       | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 392      | 18.26%  |
| Intel Core i5           | 371      | 17.28%  |
| AMD Ryzen 5             | 174      | 8.1%    |
| AMD Ryzen 7             | 149      | 6.94%   |
| Intel Xeon              | 122      | 5.68%   |
| AMD FX                  | 101      | 4.7%    |
| Intel Core i3           | 96       | 4.47%   |
| Intel Core 2 Duo        | 80       | 3.73%   |
| AMD Ryzen 9             | 75       | 3.49%   |
| Intel Core 2 Quad       | 60       | 2.79%   |
| Other                   | 49       | 2.28%   |
| Intel Celeron           | 35       | 1.63%   |
| AMD Athlon 64 X2        | 34       | 1.58%   |
| AMD A10                 | 29       | 1.35%   |
| Intel Core i9           | 28       | 1.3%    |
| Intel Pentium Dual-Core | 27       | 1.26%   |
| Intel Pentium           | 27       | 1.26%   |
| AMD Ryzen 3             | 25       | 1.16%   |
| AMD Athlon II X2        | 20       | 0.93%   |
| Intel Core 2            | 19       | 0.88%   |
| AMD Phenom II X4        | 19       | 0.88%   |
| AMD A8                  | 19       | 0.88%   |
| AMD A6                  | 18       | 0.84%   |
| AMD Phenom II X6        | 17       | 0.79%   |
| AMD Phenom              | 17       | 0.79%   |
| Intel Pentium D         | 16       | 0.75%   |
| Intel Pentium Dual      | 15       | 0.7%    |
| AMD Ryzen Threadripper  | 14       | 0.65%   |
| Intel Pentium 4         | 13       | 0.61%   |
| Intel Atom              | 12       | 0.56%   |
| AMD Athlon              | 10       | 0.47%   |
| AMD Athlon II X3        | 9        | 0.42%   |
| AMD Phenom II X2        | 8        | 0.37%   |
| AMD Athlon II X4        | 7        | 0.33%   |
| AMD A4                  | 7        | 0.33%   |
| Intel Pentium Gold      | 5        | 0.23%   |
| AMD E                   | 5        | 0.23%   |
| AMD Athlon X4           | 5        | 0.23%   |
| Intel Pentium Silver    | 2        | 0.09%   |
| AMD Sempron             | 2        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 900      | 41.82%  |
| 2       | 464      | 21.56%  |
| 6       | 317      | 14.73%  |
| 8       | 236      | 10.97%  |
| 12      | 77       | 3.58%   |
| 3       | 47       | 2.18%   |
| 1       | 40       | 1.86%   |
| 16      | 37       | 1.72%   |
| 10      | 19       | 0.88%   |
| 24      | 8        | 0.37%   |
| 20      | 4        | 0.19%   |
| Unknown | 3        | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2098     | 97.95%  |
| 2       | 43       | 2.01%   |
| Unknown | 1        | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1257     | 58.6%   |
| 1       | 885      | 41.26%  |
| Unknown | 3        | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2111     | 98.23%  |
| Unknown        | 35       | 1.63%   |
| 32-bit         | 3        | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 522      | 23.39%  |
| 0x306c3    | 154      | 6.9%    |
| 0x306a9    | 124      | 5.56%   |
| 0x206a7    | 115      | 5.15%   |
| 0x1067a    | 89       | 3.99%   |
| 0x08701021 | 84       | 3.76%   |
| 0x506e3    | 70       | 3.14%   |
| 0x906ea    | 56       | 2.51%   |
| 0x08701013 | 48       | 2.15%   |
| 0x0800820d | 48       | 2.15%   |
| 0x06000852 | 47       | 2.11%   |
| 0x906e9    | 36       | 1.61%   |
| 0x6fb      | 36       | 1.61%   |
| 0x106a5    | 30       | 1.34%   |
| 0x010000c8 | 29       | 1.3%    |
| 0x06001119 | 28       | 1.25%   |
| 0x206d7    | 27       | 1.21%   |
| 0x106e5    | 27       | 1.21%   |
| 0x6fd      | 23       | 1.03%   |
| 0xa0655    | 21       | 0.94%   |
| 0x906ed    | 21       | 0.94%   |
| 0x08001137 | 21       | 0.94%   |
| 0x0600063e | 21       | 0.94%   |
| 0x0a201009 | 20       | 0.9%    |
| 0x306f2    | 18       | 0.81%   |
| 0x206c2    | 18       | 0.81%   |
| 0x0a201016 | 18       | 0.81%   |
| 0x08001138 | 18       | 0.81%   |
| 0x10676    | 16       | 0.72%   |
| 0x20655    | 15       | 0.67%   |
| 0x20652    | 15       | 0.67%   |
| 0x08108109 | 15       | 0.67%   |
| 0x010000dc | 15       | 0.67%   |
| 0x906ec    | 14       | 0.63%   |
| 0x90672    | 14       | 0.63%   |
| 0x06003106 | 14       | 0.63%   |
| 0xa0653    | 13       | 0.58%   |
| 0xa0671    | 12       | 0.54%   |
| 0x01000083 | 11       | 0.49%   |
| 0x6f6      | 10       | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 223      | 10.41%  |
| SandyBridge      | 174      | 8.12%   |
| Zen 2            | 173      | 8.07%   |
| KabyLake         | 173      | 8.07%   |
| IvyBridge        | 167      | 7.79%   |
| Penryn           | 133      | 6.21%   |
| Piledriver       | 105      | 4.9%    |
| K10              | 105      | 4.9%    |
| Skylake          | 98       | 4.57%   |
| Zen+             | 91       | 4.25%   |
| Core             | 89       | 4.15%   |
| Zen 3            | 86       | 4.01%   |
| Zen              | 85       | 3.97%   |
| Nehalem          | 75       | 3.5%    |
| Westmere         | 59       | 2.75%   |
| CometLake        | 47       | 2.19%   |
| K8 Hammer        | 39       | 1.82%   |
| NetBurst         | 34       | 1.59%   |
| Bulldozer        | 31       | 1.45%   |
| Unknown          | 30       | 1.4%    |
| Silvermont       | 18       | 0.84%   |
| Steamroller      | 17       | 0.79%   |
| Excavator        | 14       | 0.65%   |
| Alderlake Hybrid | 14       | 0.65%   |
| K10 Llano        | 12       | 0.56%   |
| Icelake          | 9        | 0.42%   |
| Broadwell        | 7        | 0.33%   |
| Jaguar           | 6        | 0.28%   |
| Goldmont         | 6        | 0.28%   |
| Bonnell          | 6        | 0.28%   |
| Bobcat           | 6        | 0.28%   |
| Goldmont plus    | 5        | 0.23%   |
| Puma             | 4        | 0.19%   |
| Tremont          | 1        | 0.05%   |
| TigerLake        | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 952      | 41.48%  |
| AMD                                          | 715      | 31.15%  |
| Intel                                        | 607      | 26.45%  |
| Matrox Electronics Systems                   | 6        | 0.26%   |
| ASPEED Technology                            | 6        | 0.26%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.13%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.09%   |
| VIA Technologies                             | 2        | 0.09%   |
| Loongson Technology                          | 1        | 0.04%   |
| ATI Technologies                             | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 133      | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 100      | 4.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 69       | 2.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 57       | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 57       | 2.38%   |
| Intel HD Graphics 530                                                       | 53       | 2.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 52       | 2.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 48       | 2.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 46       | 1.92%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 43       | 1.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 40       | 1.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 35       | 1.46%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 33       | 1.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 32       | 1.34%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 32       | 1.34%   |
| Nvidia GK208B [GeForce GT 730]                                              | 26       | 1.09%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 25       | 1.05%   |
| Nvidia GT218 [GeForce 210]                                                  | 24       | 1%      |
| Nvidia GM204 [GeForce GTX 970]                                              | 24       | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 22       | 0.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 21       | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 21       | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                               | 21       | 0.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 20       | 0.84%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 18       | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 18       | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                         | 18       | 0.75%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 18       | 0.75%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 17       | 0.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 17       | 0.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 17       | 0.71%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 16       | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 15       | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 15       | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 15       | 0.63%   |
| Intel HD Graphics 630                                                       | 14       | 0.59%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 14       | 0.59%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 14       | 0.59%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 13       | 0.54%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 13       | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| 1 x Nvidia                | 863      | 39.62%  |
| 1 x AMD                   | 640      | 29.38%  |
| 1 x Intel                 | 508      | 23.32%  |
| 2 x AMD                   | 37       | 1.7%    |
| 2 x Nvidia                | 34       | 1.56%   |
| Intel + Nvidia            | 28       | 1.29%   |
| AMD + Nvidia              | 21       | 0.96%   |
| Intel + AMD               | 14       | 0.64%   |
| 1 x Matrox                | 5        | 0.23%   |
| Other                     | 4        | 0.18%   |
| 1 x ASPEED                | 4        | 0.18%   |
| 2 x Intel                 | 3        | 0.14%   |
| 1 x SiS                   | 3        | 0.14%   |
| Intel + 2 x Nvidia        | 3        | 0.14%   |
| 1 x VIA                   | 2        | 0.09%   |
| 5 x Nvidia                | 1        | 0.05%   |
| 2 x Loongson Technology   | 1        | 0.05%   |
| 1 x XGI                   | 1        | 0.05%   |
| Nvidia + ASPEED           | 1        | 0.05%   |
| 1 x Intel + 3 x AMD       | 1        | 0.05%   |
| AMD + 2 x Nvidia          | 1        | 0.05%   |
| AMD + XGI                 | 1        | 0.05%   |
| AMD + Nvidia + 1 x ASPEED | 1        | 0.05%   |
| AMD + Matrox              | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1496     | 68.31%  |
| Proprietary | 584      | 26.67%  |
| Unknown     | 110      | 5.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 858      | 38.24%  |
| 1.01-2.0   | 296      | 13.19%  |
| 0.51-1.0   | 251      | 11.19%  |
| 7.01-8.0   | 249      | 11.1%   |
| 0.01-0.5   | 222      | 9.89%   |
| 3.01-4.0   | 167      | 7.44%   |
| 5.01-6.0   | 95       | 4.23%   |
| 8.01-16.0  | 67       | 2.99%   |
| 2.01-3.0   | 33       | 1.47%   |
| 4.01-5.0   | 3        | 0.13%   |
| 16.01-24.0 | 3        | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 352      | 14.83%  |
| Dell                 | 275      | 11.58%  |
| Goldstar             | 255      | 10.74%  |
| Acer                 | 242      | 10.19%  |
| Hewlett-Packard      | 174      | 7.33%   |
| Ancor Communications | 168      | 7.08%   |
| BenQ                 | 121      | 5.1%    |
| ViewSonic            | 84       | 3.54%   |
| ASUSTek Computer     | 69       | 2.91%   |
| LG Electronics       | 61       | 2.57%   |
| Unknown              | 51       | 2.15%   |
| Philips              | 42       | 1.77%   |
| AOC                  | 37       | 1.56%   |
| Toshiba              | 33       | 1.39%   |
| Sony                 | 33       | 1.39%   |
| Lenovo               | 29       | 1.22%   |
| Sharp                | 27       | 1.14%   |
| NEC Computers        | 17       | 0.72%   |
| MSI                  | 16       | 0.67%   |
| Gateway              | 13       | 0.55%   |
| Gigabyte Technology  | 12       | 0.51%   |
| AUS                  | 12       | 0.51%   |
| HannStar             | 11       | 0.46%   |
| Unknown              | 11       | 0.46%   |
| Vizio                | 9        | 0.38%   |
| Sceptre Tech         | 9        | 0.38%   |
| Insignia             | 9        | 0.38%   |
| Panasonic            | 8        | 0.34%   |
| HKC                  | 8        | 0.34%   |
| Hitachi              | 8        | 0.34%   |
| DENON                | 8        | 0.34%   |
| ___                  | 7        | 0.29%   |
| eMachines            | 7        | 0.29%   |
| Apple                | 6        | 0.25%   |
| Microstep            | 5        | 0.21%   |
| Lenovo Group Limited | 5        | 0.21%   |
| Westinghouse         | 4        | 0.17%   |
| Unknown (AAA)        | 4        | 0.17%   |
| MStar                | 4        | 0.17%   |
| IBM                  | 4        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 18       | 0.69%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 15       | 0.58%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 14       | 0.54%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 12       | 0.46%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 11       | 0.42%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 11       | 0.42%   |
| Unknown                                                               | 11       | 0.42%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 9        | 0.35%   |
| Sharp HDMI SHP0FFB 1920x1080 820x460mm 37.0-inch                      | 9        | 0.35%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 9        | 0.35%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 9        | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8        | 0.31%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 8        | 0.31%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 8        | 0.31%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 8        | 0.31%   |
| Dell E228WFP DELD015 1680x1050 473x296mm 22.0-inch                    | 8        | 0.31%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 8        | 0.31%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                     | 8        | 0.31%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 7        | 0.27%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 7        | 0.27%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 7        | 0.27%   |
| Dell P2411H DELA06D 1920x1080 531x299mm 24.0-inch                     | 7        | 0.27%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 7        | 0.27%   |
| Acer S230HL ACR0280 1920x1080 509x286mm 23.0-inch                     | 7        | 0.27%   |
| Toshiba TSB-TV TSB0205 1920x1080 531x398mm 26.1-inch                  | 6        | 0.23%   |
| Sharp LC55LBU591C SHP4353 3840x2160 800x450mm 36.1-inch               | 6        | 0.23%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 6        | 0.23%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 6        | 0.23%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 6        | 0.23%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 6        | 0.23%   |
| Acer S242HL ACR0216 1920x1080 531x299mm 24.0-inch                     | 6        | 0.23%   |
| ___ LCDTV16 ___0101 1360x768                                          | 5        | 0.19%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 5        | 0.19%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 5        | 0.19%   |
| Unknown LCD Monitor SAMSUNG                                           | 5        | 0.19%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 820x460mm 37.0-inch | 5        | 0.19%   |
| LG Electronics LCD Monitor LG TV                                      | 5        | 0.19%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 5        | 0.19%   |
| Hewlett-Packard w2007 HWP26A6 1680x1050 433x271mm 20.1-inch           | 5        | 0.19%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                  | 5        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1026     | 44.09%  |
| 3840x2160 (4K)     | 196      | 8.42%   |
| 1680x1050 (WSXGA+) | 177      | 7.61%   |
| 1280x1024 (SXGA)   | 158      | 6.79%   |
| 2560x1440 (QHD)    | 151      | 6.49%   |
| Unknown            | 98       | 4.21%   |
| 1920x1200 (WUXGA)  | 70       | 3.01%   |
| 1600x900 (HD+)     | 66       | 2.84%   |
| 1440x900 (WXGA+)   | 63       | 2.71%   |
| 3840x1080          | 44       | 1.89%   |
| 3440x1440          | 43       | 1.85%   |
| 1366x768 (WXGA)    | 42       | 1.8%    |
| 1360x768           | 41       | 1.76%   |
| 2560x1080          | 17       | 0.73%   |
| 1920x540           | 17       | 0.73%   |
| 1600x1200          | 14       | 0.6%    |
| 1280x720 (HD)      | 8        | 0.34%   |
| 5760x1080          | 7        | 0.3%    |
| 3600x1080          | 7        | 0.3%    |
| 1024x768 (XGA)     | 6        | 0.26%   |
| 3840x1200          | 5        | 0.21%   |
| 3200x1080          | 5        | 0.21%   |
| 2048x1152          | 5        | 0.21%   |
| 7680x2160          | 4        | 0.17%   |
| 5760x2160          | 3        | 0.13%   |
| 5120x1440          | 3        | 0.13%   |
| 4480x1440          | 3        | 0.13%   |
| 1280x960           | 3        | 0.13%   |
| 5360x1440          | 2        | 0.09%   |
| 4480x1080          | 2        | 0.09%   |
| 3280x1080          | 2        | 0.09%   |
| 2560x1600          | 2        | 0.09%   |
| 2288x1287          | 2        | 0.09%   |
| 1400x1050          | 2        | 0.09%   |
| 1280x768           | 2        | 0.09%   |
| 8320x2160          | 1        | 0.04%   |
| 7360x2160          | 1        | 0.04%   |
| 6400x2160          | 1        | 0.04%   |
| 5520x1080          | 1        | 0.04%   |
| 5200x2160          | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 314      | 13.43%  |
| Unknown | 309      | 13.22%  |
| 23      | 284      | 12.15%  |
| 24      | 269      | 11.51%  |
| 21      | 241      | 10.31%  |
| 19      | 143      | 6.12%   |
| 22      | 110      | 4.7%    |
| 31      | 102      | 4.36%   |
| 20      | 101      | 4.32%   |
| 17      | 77       | 3.29%   |
| 18      | 47       | 2.01%   |
| 34      | 45       | 1.92%   |
| 72      | 40       | 1.71%   |
| 84      | 36       | 1.54%   |
| 32      | 25       | 1.07%   |
| 40      | 18       | 0.77%   |
| 25      | 16       | 0.68%   |
| 15      | 14       | 0.6%    |
| 37      | 13       | 0.56%   |
| 54      | 10       | 0.43%   |
| 74      | 9        | 0.38%   |
| 43      | 9        | 0.38%   |
| 26      | 9        | 0.38%   |
| 49      | 8        | 0.34%   |
| 28      | 8        | 0.34%   |
| 48      | 7        | 0.3%    |
| 47      | 6        | 0.26%   |
| 46      | 6        | 0.26%   |
| 14      | 6        | 0.26%   |
| 52      | 5        | 0.21%   |
| 36      | 5        | 0.21%   |
| 35      | 5        | 0.21%   |
| 39      | 4        | 0.17%   |
| 69      | 3        | 0.13%   |
| 64      | 3        | 0.13%   |
| 42      | 3        | 0.13%   |
| 38      | 3        | 0.13%   |
| 29      | 3        | 0.13%   |
| 65      | 2        | 0.09%   |
| 61      | 2        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 776      | 34.47%  |
| 401-500        | 545      | 24.21%  |
| Unknown        | 309      | 13.73%  |
| 601-700        | 154      | 6.84%   |
| 351-400        | 92       | 4.09%   |
| 301-350        | 90       | 4%      |
| 1501-2000      | 90       | 4%      |
| 701-800        | 74       | 3.29%   |
| 1001-1500      | 56       | 2.49%   |
| 801-900        | 44       | 1.95%   |
| 901-1000       | 14       | 0.62%   |
| 201-300        | 6        | 0.27%   |
| More than 2000 | 1        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1281     | 60.08%  |
| 16/10   | 303      | 14.21%  |
| Unknown | 273      | 12.8%   |
| 5/4     | 146      | 6.85%   |
| 21/9    | 53       | 2.49%   |
| 4/3     | 28       | 1.31%   |
| 32/9    | 17       | 0.8%    |
| 3/2     | 16       | 0.75%   |
| 6/5     | 12       | 0.56%   |
| 1.96    | 2        | 0.09%   |
| 1.00    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 733      | 32.3%   |
| 301-350        | 321      | 14.15%  |
| Unknown        | 309      | 13.62%  |
| 151-200        | 301      | 13.27%  |
| 351-500        | 181      | 7.98%   |
| More than 1000 | 122      | 5.38%   |
| 141-150        | 105      | 4.63%   |
| 251-300        | 91       | 4.01%   |
| 501-1000       | 80       | 3.53%   |
| 101-110        | 12       | 0.53%   |
| 81-90          | 4        | 0.18%   |
| 131-140        | 3        | 0.13%   |
| 111-120        | 3        | 0.13%   |
| 71-80          | 2        | 0.09%   |
| 121-130        | 1        | 0.04%   |
| 91-100         | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1244     | 57.67%  |
| 101-120 | 367      | 17.01%  |
| Unknown | 309      | 14.33%  |
| 1-50    | 123      | 5.7%    |
| 121-160 | 79       | 3.66%   |
| 161-240 | 35       | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1591     | 72.42%  |
| 2     | 397      | 18.07%  |
| 0     | 129      | 5.87%   |
| 3     | 68       | 3.1%    |
| 4     | 9        | 0.41%   |
| 5     | 2        | 0.09%   |
| 6     | 1        | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 1128     | 35.68%  |
| Intel                                 | 1097     | 34.7%   |
| Qualcomm Atheros                      | 246      | 7.78%   |
| Broadcom                              | 130      | 4.11%   |
| Ralink                                | 71       | 2.25%   |
| Nvidia                                | 61       | 1.93%   |
| Ralink Technology                     | 52       | 1.65%   |
| D-Link                                | 38       | 1.2%    |
| Marvell Technology Group              | 35       | 1.11%   |
| TP-Link                               | 31       | 0.98%   |
| D-Link System                         | 25       | 0.79%   |
| Linksys                               | 21       | 0.66%   |
| ASUSTek Computer                      | 21       | 0.66%   |
| Aquantia                              | 17       | 0.54%   |
| Samsung Electronics                   | 16       | 0.51%   |
| Qualcomm Atheros Communications       | 16       | 0.51%   |
| Broadcom Limited                      | 16       | 0.51%   |
| ASIX Electronics                      | 15       | 0.47%   |
| NetGear                               | 14       | 0.44%   |
| Microsoft                             | 14       | 0.44%   |
| MediaTek                              | 13       | 0.41%   |
| Belkin Components                     | 10       | 0.32%   |
| VIA Technologies                      | 4        | 0.13%   |
| Micro Star International              | 4        | 0.13%   |
| ZyDAS                                 | 3        | 0.09%   |
| Motorola PCS                          | 3        | 0.09%   |
| Gemtek                                | 3        | 0.09%   |
| Edimax Technology                     | 3        | 0.09%   |
| DisplayLink                           | 3        | 0.09%   |
| Arduino SA                            | 3        | 0.09%   |
| 3Com                                  | 3        | 0.09%   |
| Silicon Integrated Systems [SiS]      | 2        | 0.06%   |
| Netchip Technology                    | 2        | 0.06%   |
| Microchip Technology                  | 2        | 0.06%   |
| Mellanox Technologies                 | 2        | 0.06%   |
| LG Electronics                        | 2        | 0.06%   |
| InterBiometrics                       | 2        | 0.06%   |
| Google                                | 2        | 0.06%   |
| Apple                                 | 2        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 898      | 25.1%   |
| Intel I211 Gigabit Network Connection                             | 153      | 4.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140      | 3.91%   |
| Intel Wi-Fi 6 AX200                                               | 128      | 3.58%   |
| Intel Ethernet Connection (2) I219-V                              | 87       | 2.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81       | 2.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 70       | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 50       | 1.4%    |
| Intel Ethernet Controller I225-V                                  | 47       | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 47       | 1.31%   |
| Intel Ethernet Connection (7) I219-V                              | 41       | 1.15%   |
| Intel Wireless-AC 9260                                            | 36       | 1.01%   |
| Intel 82574L Gigabit Network Connection                           | 35       | 0.98%   |
| Intel Ethernet Connection (2) I218-V                              | 34       | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 32       | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 31       | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 30       | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 30       | 0.84%   |
| Nvidia MCP61 Ethernet                                             | 29       | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28       | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 28       | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 28       | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 26       | 0.73%   |
| Ralink MT7601U Wireless Adapter                                   | 22       | 0.62%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 22       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 20       | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 20       | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 20       | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19       | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 19       | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 18       | 0.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18       | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 18       | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 18       | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18       | 0.5%    |
| Intel Wireless 8260                                               | 17       | 0.48%   |
| Intel Wireless 7260                                               | 17       | 0.48%   |
| Realtek 802.11ac NIC                                              | 16       | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15       | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 404      | 34.89%  |
| Realtek Semiconductor                 | 183      | 15.8%   |
| Qualcomm Atheros                      | 176      | 15.2%   |
| Ralink                                | 71       | 6.13%   |
| Broadcom                              | 56       | 4.84%   |
| Ralink Technology                     | 52       | 4.49%   |
| D-Link                                | 38       | 3.28%   |
| TP-Link                               | 30       | 2.59%   |
| Linksys                               | 21       | 1.81%   |
| ASUSTek Computer                      | 21       | 1.81%   |
| Qualcomm Atheros Communications       | 16       | 1.38%   |
| NetGear                               | 14       | 1.21%   |
| Microsoft                             | 13       | 1.12%   |
| D-Link System                         | 13       | 1.12%   |
| MediaTek                              | 12       | 1.04%   |
| Belkin Components                     | 10       | 0.86%   |
| Broadcom Limited                      | 7        | 0.6%    |
| Micro Star International              | 4        | 0.35%   |
| ZyDAS                                 | 3        | 0.26%   |
| Gemtek                                | 3        | 0.26%   |
| Edimax Technology                     | 3        | 0.26%   |
| Marvell Technology Group              | 2        | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.17%   |
| Wilocity                              | 1        | 0.09%   |
| Wacom                                 | 1        | 0.09%   |
| BUFFALO                               | 1        | 0.09%   |
| Belkin                                | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 128      | 10.91%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 70       | 5.97%   |
| Intel Wireless-AC 9260                                                 | 36       | 3.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 32       | 2.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 31       | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 30       | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 28       | 2.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 26       | 2.22%   |
| Ralink MT7601U Wireless Adapter                                        | 22       | 1.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 22       | 1.88%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19       | 1.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 18       | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 18       | 1.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 18       | 1.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 18       | 1.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 18       | 1.53%   |
| Intel Wireless 8260                                                    | 17       | 1.45%   |
| Intel Wireless 7260                                                    | 17       | 1.45%   |
| Realtek 802.11ac NIC                                                   | 16       | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 15       | 1.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 14       | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 13       | 1.11%   |
| Intel Wireless 7265                                                    | 13       | 1.11%   |
| Ralink RT5370 Wireless Adapter                                         | 12       | 1.02%   |
| Intel Wireless 3165                                                    | 12       | 1.02%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 12       | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 11       | 0.94%   |
| Intel Wireless 8265 / 8275                                             | 11       | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                        | 10       | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 9        | 0.77%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                 | 9        | 0.77%   |
| D-Link 802.11ac NIC                                                    | 9        | 0.77%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 9        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8        | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 8        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7        | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 7        | 0.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7        | 0.6%    |
| NetGear A6210                                                          | 7        | 0.6%    |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU] | 7        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1050     | 45.67%  |
| Intel                                  | 889      | 38.67%  |
| Qualcomm Atheros                       | 87       | 3.78%   |
| Broadcom                               | 78       | 3.39%   |
| Nvidia                                 | 61       | 2.65%   |
| Marvell Technology Group               | 33       | 1.44%   |
| Aquantia                               | 17       | 0.74%   |
| Samsung Electronics                    | 16       | 0.7%    |
| ASIX Electronics                       | 15       | 0.65%   |
| D-Link System                          | 12       | 0.52%   |
| Broadcom Limited                       | 9        | 0.39%   |
| VIA Technologies                       | 4        | 0.17%   |
| DisplayLink                            | 3        | 0.13%   |
| 3Com                                   | 3        | 0.13%   |
| TP-Link                                | 2        | 0.09%   |
| Silicon Integrated Systems [SiS]       | 2        | 0.09%   |
| Mellanox Technologies                  | 2        | 0.09%   |
| LG Electronics                         | 2        | 0.09%   |
| Apple                                  | 2        | 0.09%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.04%   |
| OPPO Electronics                       | 1        | 0.04%   |
| Microsoft                              | 1        | 0.04%   |
| MediaTek                               | 1        | 0.04%   |
| Huawei Technologies                    | 1        | 0.04%   |
| Google                                 | 1        | 0.04%   |
| Databook                               | 1        | 0.04%   |
| Chelsio Communications                 | 1        | 0.04%   |
| American Megatrends                    | 1        | 0.04%   |
| ADMtek                                 | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 898      | 37.84%  |
| Intel I211 Gigabit Network Connection                             | 153      | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140      | 5.9%    |
| Intel Ethernet Connection (2) I219-V                              | 87       | 3.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 80       | 3.37%   |
| Intel Ethernet Connection I217-LM                                 | 50       | 2.11%   |
| Intel Ethernet Controller I225-V                                  | 47       | 1.98%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.98%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 47       | 1.98%   |
| Intel Ethernet Connection (7) I219-V                              | 41       | 1.73%   |
| Intel 82574L Gigabit Network Connection                           | 35       | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 34       | 1.43%   |
| Intel Ethernet Connection I217-V                                  | 30       | 1.26%   |
| Nvidia MCP61 Ethernet                                             | 29       | 1.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28       | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 28       | 1.18%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 20       | 0.84%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 20       | 0.84%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 20       | 0.84%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 19       | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14       | 0.59%   |
| Intel 82578DM Gigabit Network Connection                          | 14       | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12       | 0.51%   |
| Nvidia MCP77 Ethernet                                             | 12       | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 12       | 0.51%   |
| Intel 82578DC Gigabit Network Connection                          | 12       | 0.51%   |
| Intel 82562V-2 10/100 Network Connection                          | 12       | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 12       | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11       | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11       | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 11       | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 10       | 0.42%   |
| Intel Ethernet Connection (2) I218-LM                             | 10       | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10       | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9        | 0.38%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 9        | 0.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 9        | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                            | 8        | 0.34%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 8        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2118     | 66.04%  |
| WiFi     | 1058     | 32.99%  |
| Modem    | 25       | 0.78%   |
| Unknown  | 6        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1694     | 74.92%  |
| WiFi     | 567      | 25.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1209     | 55.74%  |
| 2     | 822      | 37.9%   |
| 3     | 105      | 4.84%   |
| 0     | 11       | 0.51%   |
| 4     | 10       | 0.46%   |
| 5     | 9        | 0.41%   |
| 21    | 1        | 0.05%   |
| 8     | 1        | 0.05%   |
| 6     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1901     | 87.64%  |
| Yes  | 268      | 12.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 374      | 46.23%  |
| Cambridge Silicon Radio         | 124      | 15.33%  |
| ASUSTek Computer                | 66       | 8.16%   |
| Broadcom                        | 60       | 7.42%   |
| Qualcomm Atheros Communications | 50       | 6.18%   |
| Realtek Semiconductor           | 36       | 4.45%   |
| IMC Networks                    | 22       | 2.72%   |
| Lite-On Technology              | 16       | 1.98%   |
| Dynex                           | 11       | 1.36%   |
| Apple                           | 11       | 1.36%   |
| MediaTek                        | 6        | 0.74%   |
| Realtek                         | 5        | 0.62%   |
| Micro Star International        | 4        | 0.49%   |
| Dell                            | 4        | 0.49%   |
| Logitech                        | 3        | 0.37%   |
| Foxconn / Hon Hai               | 3        | 0.37%   |
| Toshiba                         | 2        | 0.25%   |
| Primax Electronics              | 2        | 0.25%   |
| Integrated System Solution      | 2        | 0.25%   |
| Zeevo                           | 1        | 0.12%   |
| TP-Link                         | 1        | 0.12%   |
| Ralink                          | 1        | 0.12%   |
| Nintendo                        | 1        | 0.12%   |
| Marvell Semiconductor           | 1        | 0.12%   |
| HTC (High Tech Computer)        | 1        | 0.12%   |
| Edimax Technology               | 1        | 0.12%   |
| Belkin Components               | 1        | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 124      | 15.33%  |
| Intel AX200 Bluetooth                                        | 123      | 15.2%   |
| Intel Wireless-AC 3168 Bluetooth                             | 69       | 8.53%   |
| Intel Bluetooth wireless interface                           | 64       | 7.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                            | 43       | 5.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 37       | 4.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 31       | 3.83%   |
| Intel Bluetooth Device                                       | 29       | 3.58%   |
| Realtek Bluetooth Radio                                      | 26       | 3.21%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 24       | 2.97%   |
| Intel AX210 Bluetooth                                        | 19       | 2.35%   |
| Qualcomm Atheros  Bluetooth Device                           | 18       | 2.22%   |
| IMC Networks Bluetooth Radio                                 | 16       | 1.98%   |
| Qualcomm Atheros AR3011 Bluetooth                            | 13       | 1.61%   |
| Lite-On Bluetooth Device                                     | 12       | 1.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller               | 11       | 1.36%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]     | 11       | 1.36%   |
| ASUS Bluetooth Radio                                         | 10       | 1.24%   |
| ASUS Bluetooth Device                                        | 9        | 1.11%   |
| Realtek  Bluetooth 4.2 Adapter                               | 7        | 0.87%   |
| ASUS BCM20702A0                                              | 7        | 0.87%   |
| MediaTek Wireless_Device                                     | 6        | 0.74%   |
| ASUS Bluetooth Adapter                                       | 6        | 0.74%   |
| Realtek Bluetooth Radio                                      | 5        | 0.62%   |
| Qualcomm Atheros AR9462 Bluetooth                            | 4        | 0.49%   |
| Micro Star International Bluetooth Device                    | 4        | 0.49%   |
| IMC Networks Bluetooth Device                                | 4        | 0.49%   |
| Broadcom HP Bluethunder                                      | 4        | 0.49%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE        | 4        | 0.49%   |
| ASUS ASUS USB-BT500                                          | 4        | 0.49%   |
| Apple Bluetooth USB Host Controller                          | 4        | 0.49%   |
| Logitech BT Mini-Receiver (HCI mode)                         | 3        | 0.37%   |
| Lite-On Bluetooth Radio                                      | 3        | 0.37%   |
| Foxconn / Hon Hai Wireless_Device                            | 3        | 0.37%   |
| Broadcom HP Portable Bumble Bee                              | 3        | 0.37%   |
| Broadcom BCM2045 Bluetooth                                   | 3        | 0.37%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 3        | 0.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                         | 3        | 0.37%   |
| Apple Bluetooth HCI                                          | 3        | 0.37%   |
| Toshiba Atheros AR3012 Bluetooth                             | 2        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 1278     | 33.81%  |
| AMD                                             | 984      | 26.03%  |
| Nvidia                                          | 903      | 23.89%  |
| C-Media Electronics                             | 120      | 3.17%   |
| Creative Labs                                   | 55       | 1.46%   |
| Logitech                                        | 53       | 1.4%    |
| Texas Instruments                               | 22       | 0.58%   |
| Corsair                                         | 21       | 0.56%   |
| Blue Microphones                                | 20       | 0.53%   |
| Focusrite-Novation                              | 18       | 0.48%   |
| SteelSeries ApS                                 | 16       | 0.42%   |
| Razer USA                                       | 15       | 0.4%    |
| JMTek                                           | 15       | 0.4%    |
| ASUSTek Computer                                | 15       | 0.4%    |
| Samson Technologies                             | 12       | 0.32%   |
| GYROCOM C&C                                     | 12       | 0.32%   |
| Creative Technology                             | 12       | 0.32%   |
| Kingston Technology                             | 11       | 0.29%   |
| M-Audio                                         | 9        | 0.24%   |
| VIA Technologies                                | 8        | 0.21%   |
| Sony                                            | 8        | 0.21%   |
| Generalplus Technology                          | 8        | 0.21%   |
| Yamaha                                          | 6        | 0.16%   |
| SAVITECH                                        | 6        | 0.16%   |
| GN Netcom                                       | 6        | 0.16%   |
| FiiO Electronics Technology                     | 6        | 0.16%   |
| Thesycon Systemsoftware & Consulting            | 5        | 0.13%   |
| Realtek Semiconductor                           | 5        | 0.13%   |
| Plantronics                                     | 5        | 0.13%   |
| Micro Star International                        | 5        | 0.13%   |
| Cambridge Silicon Radio                         | 5        | 0.13%   |
| Bose                                            | 5        | 0.13%   |
| Audio-Technica                                  | 5        | 0.13%   |
| XMOS                                            | 4        | 0.11%   |
| Tenx Technology                                 | 4        | 0.11%   |
| Licensed by Sony Computer Entertainment America | 4        | 0.11%   |
| Dell                                            | 4        | 0.11%   |
| Valve Software                                  | 3        | 0.08%   |
| Silicon Integrated Systems [SiS]                | 3        | 0.08%   |
| Medeli Electronics                              | 3        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 229      | 5.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 182      | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 155      | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 155      | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 135      | 3.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 133      | 3.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 130      | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 107      | 2.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 94       | 2.16%   |
| Intel 200 Series PCH HD Audio                                              | 93       | 2.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 90       | 2.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 90       | 2.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 76       | 1.75%   |
| AMD FCH Azalia Controller                                                  | 75       | 1.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 72       | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                 | 69       | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 66       | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 65       | 1.5%    |
| Nvidia GP104 High Definition Audio Controller                              | 63       | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 63       | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 60       | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 53       | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 51       | 1.17%   |
| AMD Navi 10 HDMI Audio                                                     | 51       | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 46       | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 44       | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 43       | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 41       | 0.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 39       | 0.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 38       | 0.87%   |
| Nvidia TU104 HD Audio Controller                                           | 37       | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 37       | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 36       | 0.83%   |
| Nvidia High Definition Audio Controller                                    | 34       | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 34       | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 33       | 0.76%   |
| Nvidia MCP61 High Definition Audio                                         | 32       | 0.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 32       | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 31       | 0.71%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 29       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 208      | 17.3%   |
| Unknown             | 163      | 13.56%  |
| G.Skill             | 161      | 13.39%  |
| Corsair             | 150      | 12.48%  |
| SK hynix            | 118      | 9.82%   |
| Samsung Electronics | 106      | 8.82%   |
| Micron Technology   | 64       | 5.32%   |
| Crucial             | 57       | 4.74%   |
| Nanya Technology    | 27       | 2.25%   |
| A-DATA Technology   | 25       | 2.08%   |
| Patriot             | 20       | 1.66%   |
| Ramaxel Technology  | 19       | 1.58%   |
| Elpida              | 19       | 1.58%   |
| Team                | 12       | 1%      |
| Unknown             | 12       | 1%      |
| Unifosa             | 6        | 0.5%    |
| Transcend           | 5        | 0.42%   |
| ASint Technology    | 4        | 0.33%   |
| Timetec             | 3        | 0.25%   |
| Qimonda             | 2        | 0.17%   |
| OCZ                 | 2        | 0.17%   |
| Mushkin             | 2        | 0.17%   |
| CSX                 | 2        | 0.17%   |
| Unknown (ABCD)      | 1        | 0.08%   |
| Undefi              | 1        | 0.08%   |
| Toshiba             | 1        | 0.08%   |
| Thermaltake         | 1        | 0.08%   |
| Super Talent        | 1        | 0.08%   |
| Sesame              | 1        | 0.08%   |
| Innodisk            | 1        | 0.08%   |
| Infineon            | 1        | 0.08%   |
| Hewlett-Packard     | 1        | 0.08%   |
| HBS                 | 1        | 0.08%   |
| Goldenmars          | 1        | 0.08%   |
| Avant               | 1        | 0.08%   |
| Asgard              | 1        | 0.08%   |
| Apacer              | 1        | 0.08%   |
| AMD                 | 1        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 18       | 1.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 17       | 1.27%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 12       | 0.89%   |
| Unknown                                                 | 12       | 0.89%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s   | 11       | 0.82%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3              | 10       | 0.75%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 8        | 0.6%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 8        | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 7        | 0.52%   |
| Nanya RAM NT4GC64B8HG0NF-CG 4GB DIMM DDR3 1333MT/s      | 7        | 0.52%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 7        | 0.52%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 7        | 0.52%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 7        | 0.52%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s   | 7        | 0.52%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 6        | 0.45%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s    | 6        | 0.45%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 6        | 0.45%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s    | 6        | 0.45%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 6        | 0.45%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 6        | 0.45%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s             | 6        | 0.45%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 5        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 5        | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 5        | 0.37%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 5        | 0.37%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 5        | 0.37%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s | 5        | 0.37%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s   | 5        | 0.37%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 5        | 0.37%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s  | 5        | 0.37%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 4        | 0.3%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 4        | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 4        | 0.3%    |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 4        | 0.3%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s     | 4        | 0.3%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 4        | 0.3%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s    | 4        | 0.3%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 4        | 0.3%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 4        | 0.3%    |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s    | 4        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 449      | 43.55%  |
| DDR3    | 379      | 36.76%  |
| DDR2    | 74       | 7.18%   |
| Unknown | 50       | 4.85%   |
| SDRAM   | 44       | 4.27%   |
| DDR     | 24       | 2.33%   |
| DDR5    | 9        | 0.87%   |
| LPDDR4  | 1        | 0.1%    |
| DRAM    | 1        | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 958      | 95.04%  |
| SODIMM  | 47       | 4.66%   |
| FB-DIMM | 3        | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 407      | 35.45%  |
| 4096  | 265      | 23.08%  |
| 2048  | 178      | 15.51%  |
| 16384 | 177      | 15.42%  |
| 1024  | 67       | 5.84%   |
| 32768 | 44       | 3.83%   |
| 512   | 10       | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 199      | 17.46%  |
| 1333    | 167      | 14.65%  |
| 3200    | 98       | 8.6%    |
| 3600    | 89       | 7.81%   |
| 2400    | 66       | 5.79%   |
| 800     | 55       | 4.82%   |
| 2133    | 52       | 4.56%   |
| 2667    | 44       | 3.86%   |
| 667     | 38       | 3.33%   |
| 1867    | 27       | 2.37%   |
| 1066    | 21       | 1.84%   |
| 3866    | 19       | 1.67%   |
| 3400    | 18       | 1.58%   |
| Unknown | 18       | 1.58%   |
| 2666    | 17       | 1.49%   |
| 1866    | 17       | 1.49%   |
| 3466    | 16       | 1.4%    |
| 3800    | 15       | 1.32%   |
| 3000    | 15       | 1.32%   |
| 2933    | 15       | 1.32%   |
| 3733    | 13       | 1.14%   |
| 1067    | 11       | 0.96%   |
| 1800    | 7        | 0.61%   |
| 2800    | 6        | 0.53%   |
| 2465    | 6        | 0.53%   |
| 2000    | 6        | 0.53%   |
| 533     | 6        | 0.53%   |
| 400     | 6        | 0.53%   |
| 4800    | 5        | 0.44%   |
| 3100    | 5        | 0.44%   |
| 49926   | 4        | 0.35%   |
| 3333    | 4        | 0.35%   |
| 3066    | 4        | 0.35%   |
| 2733    | 4        | 0.35%   |
| 2048    | 4        | 0.35%   |
| 1648    | 4        | 0.35%   |
| 1639    | 4        | 0.35%   |
| 1334    | 4        | 0.35%   |
| 3334    | 3        | 0.26%   |
| 3007    | 3        | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Brother Industries       | 58       | 36.94%  |
| Hewlett-Packard          | 44       | 28.03%  |
| Canon                    | 22       | 14.01%  |
| Samsung Electronics      | 19       | 12.1%   |
| Seiko Epson              | 8        | 5.1%    |
| Lexmark International    | 2        | 1.27%   |
| Dymo-CoStar              | 2        | 1.27%   |
| Zhuhai Poskey Technology | 1        | 0.64%   |
| Dell                     | 1        | 0.64%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Brother Printer                      | 8        | 5%      |
| Seiko Epson ET-3750 Series           | 4        | 2.5%    |
| HP LaserJet 1020                     | 4        | 2.5%    |
| Brother HL-L2390DW                   | 4        | 2.5%    |
| Brother HL-L2320D series             | 4        | 2.5%    |
| Brother HL-5370DW series             | 4        | 2.5%    |
| Samsung ML-1670 Series               | 3        | 1.88%   |
| HP LaserJet 4250                     | 3        | 1.88%   |
| HP LaserJet 1018                     | 3        | 1.88%   |
| HP DeskJet 3630 series               | 3        | 1.88%   |
| Canon PIXMA MX920 Series             | 3        | 1.88%   |
| Brother MFC-J480DW                   | 3        | 1.88%   |
| Brother MFC-9130CW                   | 3        | 1.88%   |
| Brother HL-L2360D series             | 3        | 1.88%   |
| Brother DCP-L2540DW                  | 3        | 1.88%   |
| Samsung ML-216x Series Laser Printer | 2        | 1.25%   |
| Samsung ML-1660 Series               | 2        | 1.25%   |
| HP LaserJet Pro M202dw               | 2        | 1.25%   |
| HP ENVY 4520 series                  | 2        | 1.25%   |
| HP DeskJet 3700 series               | 2        | 1.25%   |
| HP DeskJet 2600 series               | 2        | 1.25%   |
| Dymo-CoStar LabelWriter 450          | 2        | 1.25%   |
| Canon MF4410                         | 2        | 1.25%   |
| Brother MFC-J485DW                   | 2        | 1.25%   |
| Brother HL-L3290CDW series           | 2        | 1.25%   |
| Brother HL-2270DW Laser Printer      | 2        | 1.25%   |
| Brother HL-2140 series               | 2        | 1.25%   |
| Zhuhai Poskey Printer                | 1        | 0.63%   |
| Seiko Epson XP-4100 Series           | 1        | 0.63%   |
| Seiko Epson WF-3520 Series           | 1        | 0.63%   |
| Seiko Epson L3160 Series             | 1        | 0.63%   |
| Seiko Epson ET-4760 Series           | 1        | 0.63%   |
| Seiko Epson ET-3850 Series           | 1        | 0.63%   |
| Samsung SCX-483x 5x3x Series         | 1        | 0.63%   |
| Samsung SCX-3200 Series              | 1        | 0.63%   |
| Samsung ML-2950 Series               | 1        | 0.63%   |
| Samsung ML-1865                      | 1        | 0.63%   |
| Samsung ML-1740 Printer              | 1        | 0.63%   |
| Samsung M301x Series                 | 1        | 0.63%   |
| Samsung M267x 287x Series            | 1        | 0.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 45.83%  |
| Hewlett-Packard | 8        | 33.33%  |
| Seiko Epson     | 5        | 20.83%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                 | 3        | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2        | 8.33%   |
| Canon CanoScan LiDE 220                                 | 2        | 8.33%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1        | 4.17%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 4.17%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1        | 4.17%   |
| HP ScanJet G4050                                        | 1        | 4.17%   |
| HP ScanJet G4010                                        | 1        | 4.17%   |
| HP ScanJet 82x0C                                        | 1        | 4.17%   |
| HP ScanJet 5590                                         | 1        | 4.17%   |
| HP ScanJet 5200c                                        | 1        | 4.17%   |
| HP ScanJet 3670                                         | 1        | 4.17%   |
| HP ScanJet 3400cse                                      | 1        | 4.17%   |
| HP ScanJet 2200c                                        | 1        | 4.17%   |
| Canon CanoScan LiDE 700F                                | 1        | 4.17%   |
| Canon CanoScan LiDE 70                                  | 1        | 4.17%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1        | 4.17%   |
| Canon CanoScan LiDE 200                                 | 1        | 4.17%   |
| Canon CanoScan LiDE 110                                 | 1        | 4.17%   |
| Canon CanoScan                                          | 1        | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 200      | 43.01%  |
| Microsoft                              | 51       | 10.97%  |
| Microdia                               | 45       | 9.68%   |
| Samsung Electronics                    | 19       | 4.09%   |
| Apple                                  | 19       | 4.09%   |
| Realtek Semiconductor                  | 17       | 3.66%   |
| AVerMedia Technologies                 | 12       | 2.58%   |
| Chicony Electronics                    | 11       | 2.37%   |
| Z-Star Microelectronics                | 8        | 1.72%   |
| MacroSilicon                           | 8        | 1.72%   |
| Cubeternet                             | 7        | 1.51%   |
| Creative Technology                    | 6        | 1.29%   |
| 2M UVC CAMERA                          | 6        | 1.29%   |
| Sunplus Innovation Technology          | 4        | 0.86%   |
| Razer USA                              | 4        | 0.86%   |
| LG Electronics                         | 4        | 0.86%   |
| Huawei Technologies                    | 4        | 0.86%   |
| Generalplus Technology                 | 4        | 0.86%   |
| Valve Software                         | 3        | 0.65%   |
| Linux Foundation                       | 3        | 0.65%   |
| Hewlett-Packard                        | 3        | 0.65%   |
| Genesys Logic                          | 3        | 0.65%   |
| GEMBIRD                                | 3        | 0.65%   |
| Jieli Technology                       | 2        | 0.43%   |
| HD WEBCAM                              | 2        | 0.43%   |
| Aveo Technology                        | 2        | 0.43%   |
| ARC International                      | 2        | 0.43%   |
| WaveRider Communications               | 1        | 0.22%   |
| Unknown                                | 1        | 0.22%   |
| Sonix Technology                       | 1        | 0.22%   |
| Ruision                                | 1        | 0.22%   |
| OmniVision Technologies                | 1        | 0.22%   |
| Olympus Optical                        | 1        | 0.22%   |
| Nintendo                               | 1        | 0.22%   |
| Intel                                  | 1        | 0.22%   |
| IMC Networks                           | 1        | 0.22%   |
| Google                                 | 1        | 0.22%   |
| Dynex                                  | 1        | 0.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.22%   |
| Canon                                  | 1        | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 46       | 9.87%   |
| Logitech Webcam C270                                  | 43       | 9.23%   |
| Microdia Webcam Vitade AF                             | 21       | 4.51%   |
| Samsung Galaxy A5 (MTP)                               | 19       | 4.08%   |
| Microsoft LifeCam HD-3000                             | 18       | 3.86%   |
| Microdia USB 2.0 Camera                               | 18       | 3.86%   |
| Apple iPhone 5/5C/5S/6/SE                             | 16       | 3.43%   |
| Logitech C922 Pro Stream Webcam                       | 15       | 3.22%   |
| Logitech HD Webcam C615                               | 10       | 2.15%   |
| AVerMedia Live Streamer CAM 313                       | 10       | 2.15%   |
| Microsoft LifeCam Cinema                              | 9        | 1.93%   |
| Logitech Webcam C930e                                 | 9        | 1.93%   |
| Logitech QuickCam Pro 9000                            | 8        | 1.72%   |
| MacroSilicon USB Video                                | 7        | 1.5%    |
| Logitech BRIO Ultra HD Webcam                         | 7        | 1.5%    |
| Logitech Webcam C170                                  | 6        | 1.29%   |
| Logitech HD Webcam C525                               | 6        | 1.29%   |
| Logitech C920 PRO HD Webcam                           | 6        | 1.29%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam                  | 6        | 1.29%   |
| Realtek USB Camera                                    | 5        | 1.07%   |
| Microsoft LifeCam VX-2000                             | 5        | 1.07%   |
| Logitech Webcam Pro 9000                              | 5        | 1.07%   |
| Realtek Full HD webcam                                | 4        | 0.86%   |
| Microsoft LifeCam VX-5000                             | 4        | 0.86%   |
| Logitech Webcam C925e                                 | 4        | 0.86%   |
| Logitech Webcam C310                                  | 4        | 0.86%   |
| Huawei UVC Camera                                     | 4        | 0.86%   |
| Z-Star Lenovo USB 2.0 UVC Camera                      | 3        | 0.64%   |
| Valve Software 3D Camera                              | 3        | 0.64%   |
| Realtek NexiGo N660P FHD Webcam                       | 3        | 0.64%   |
| Razer USA Gaming Webcam [Kiyo]                        | 3        | 0.64%   |
| Microsoft LifeCam VX-800                              | 3        | 0.64%   |
| Microsoft LifeCam Studio                              | 3        | 0.64%   |
| Logitech Webcam C200                                  | 3        | 0.64%   |
| Logitech HD Webcam C910                               | 3        | 0.64%   |
| Logitech HD Webcam C510                               | 3        | 0.64%   |
| Linux Foundation EEM Gadget                           | 3        | 0.64%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 3        | 0.64%   |
| Generalplus GENERAL WEBCAM                            | 3        | 0.64%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 3        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| STMicroelectronics    | 1        | 25%     |
| Microsoft             | 1        | 25%     |
| LighTuning Technology | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader       | 1        | 25%     |
| Microsoft Fingerprint Reader                | 1        | 25%     |
| LighTuning ES603 Swipe Fingerprint Sensor   | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| SCM Microsystems          | 2        | 28.57%  |
| Yubico.com                | 1        | 14.29%  |
| In Focus Systems          | 1        | 14.29%  |
| Clay Logic                | 1        | 14.29%  |
| Alcor Micro               | 1        | 14.29%  |
| Aladdin Knowledge Systems | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 CCID                            | 1        | 14.29%  |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 14.29%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 14.29%  |
| In Focus Systems EMV Smartcard Reader                  | 1        | 14.29%  |
| Clay Logic Nitrokey Pro                                | 1        | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 14.29%  |
| Aladdin Knowledge Systems Token JC                     | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1788     | 81.09%  |
| 1     | 355      | 16.1%   |
| 2     | 44       | 2%      |
| 3     | 9        | 0.41%   |
| 4     | 4        | 0.18%   |
| 5     | 3        | 0.14%   |
| 8     | 2        | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 151      | 31.66%  |
| Net/wireless             | 134      | 28.09%  |
| Communication controller | 50       | 10.48%  |
| Unassigned class         | 30       | 6.29%   |
| Sound                    | 22       | 4.61%   |
| Multimedia controller    | 14       | 2.94%   |
| Bluetooth                | 13       | 2.73%   |
| Net/ethernet             | 11       | 2.31%   |
| Network                  | 9        | 1.89%   |
| Storage/raid             | 7        | 1.47%   |
| Camera                   | 7        | 1.47%   |
| Dvb card                 | 6        | 1.26%   |
| Storage/ide              | 5        | 1.05%   |
| Chipcard                 | 4        | 0.84%   |
| Modem                    | 3        | 0.63%   |
| Fingerprint reader       | 3        | 0.63%   |
| Firewire controller      | 2        | 0.42%   |
| Video                    | 1        | 0.21%   |
| Tv card                  | 1        | 0.21%   |
| Storage/nvme             | 1        | 0.21%   |
| Storage/ata              | 1        | 0.21%   |
| Storage                  | 1        | 0.21%   |
| Card reader              | 1        | 0.21%   |

