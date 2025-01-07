Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 4999

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X600M-STX                   | [4a348f5b49](https://linux-hardware.org/?probe=4a348f5b49) | Jan 04, 2025 |
| ASUSTek       | PRIME B450M-A               | [e6a453b673](https://linux-hardware.org/?probe=e6a453b673) | Jan 04, 2025 |
| Gigabyte      | Z390 AORUS PRO-CF           | [52f8310052](https://linux-hardware.org/?probe=52f8310052) | Jan 04, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3cf34c48](https://linux-hardware.org/?probe=1f3cf34c48) | Jan 04, 2025 |
| MSI           | PRO H610M-G                 | [c0a5a2e654](https://linux-hardware.org/?probe=c0a5a2e654) | Jan 02, 2025 |
| MSI           | PRO B650-P WIFI             | [14aa7fadc3](https://linux-hardware.org/?probe=14aa7fadc3) | Jan 01, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [16c8ddaca9](https://linux-hardware.org/?probe=16c8ddaca9) | Jan 01, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [c720ec722a](https://linux-hardware.org/?probe=c720ec722a) | Dec 31, 2024 |
| Tianbei       | GEM10                       | [036fe3371f](https://linux-hardware.org/?probe=036fe3371f) | Dec 30, 2024 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [6d4070f742](https://linux-hardware.org/?probe=6d4070f742) | Dec 30, 2024 |
| HP            | 212B                        | [0bb6c8d253](https://linux-hardware.org/?probe=0bb6c8d253) | Dec 29, 2024 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [a4bfa8bfd5](https://linux-hardware.org/?probe=a4bfa8bfd5) | Dec 29, 2024 |
| Intel         | H55                         | [608b05160e](https://linux-hardware.org/?probe=608b05160e) | Dec 29, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V3      | [3ff4946888](https://linux-hardware.org/?probe=3ff4946888) | Dec 29, 2024 |
| ASUSTek       | PRIME B760M-A D4            | [574c4a2b92](https://linux-hardware.org/?probe=574c4a2b92) | Dec 26, 2024 |
| Gigabyte      | P55M-UD2                    | [112d1ed038](https://linux-hardware.org/?probe=112d1ed038) | Dec 25, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [edc0d78348](https://linux-hardware.org/?probe=edc0d78348) | Dec 25, 2024 |
| Gigabyte      | Z390 UD                     | [bbcf88b5f3](https://linux-hardware.org/?probe=bbcf88b5f3) | Dec 25, 2024 |
| MSI           | PRO X670-P WIFI             | [603c73537a](https://linux-hardware.org/?probe=603c73537a) | Dec 25, 2024 |
| MSI           | PRO X670-P WIFI             | [9713f44b0a](https://linux-hardware.org/?probe=9713f44b0a) | Dec 24, 2024 |
| ASUSTek       | Pro WS X299 SAGE II         | [82572a2f0c](https://linux-hardware.org/?probe=82572a2f0c) | Dec 24, 2024 |
| MSI           | B550-A PRO                  | [2ceed545b9](https://linux-hardware.org/?probe=2ceed545b9) | Dec 24, 2024 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [a97fbd8b52](https://linux-hardware.org/?probe=a97fbd8b52) | Dec 23, 2024 |
| HP            | 2129                        | [7c281863fb](https://linux-hardware.org/?probe=7c281863fb) | Dec 23, 2024 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [a00f095086](https://linux-hardware.org/?probe=a00f095086) | Dec 23, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | [dd462ce2a6](https://linux-hardware.org/?probe=dd462ce2a6) | Dec 22, 2024 |
| ASRock        | B550M-HDV                   | [820e985b85](https://linux-hardware.org/?probe=820e985b85) | Dec 22, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [53f26e91a1](https://linux-hardware.org/?probe=53f26e91a1) | Dec 22, 2024 |
| AMI           | Intel                       | [b2d4a45180](https://linux-hardware.org/?probe=b2d4a45180) | Dec 21, 2024 |
| ASRock        | B450 Gaming K4              | [0247ba4dfc](https://linux-hardware.org/?probe=0247ba4dfc) | Dec 19, 2024 |
| Gigabyte      | P55-UD4                     | [687d0cebbc](https://linux-hardware.org/?probe=687d0cebbc) | Dec 19, 2024 |
| Gigabyte      | B550 AORUS ELITE            | [dfb9ab7ad3](https://linux-hardware.org/?probe=dfb9ab7ad3) | Dec 18, 2024 |
| MSI           | MPG Z790 EDGE MONSTER HU... | [9362ff5af5](https://linux-hardware.org/?probe=9362ff5af5) | Dec 18, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f294cbd961](https://linux-hardware.org/?probe=f294cbd961) | Dec 17, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8d7adb7ecd](https://linux-hardware.org/?probe=8d7adb7ecd) | Dec 17, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME E... | [332bbb3a71](https://linux-hardware.org/?probe=332bbb3a71) | Dec 17, 2024 |
| Shenzhen M... | F7BRC                       | [957f74af52](https://linux-hardware.org/?probe=957f74af52) | Dec 16, 2024 |
| ASUSTek       | PRIME A320M-K               | [cb6994a81c](https://linux-hardware.org/?probe=cb6994a81c) | Dec 15, 2024 |
| HP            | 304Ah                       | [f4ecd569d3](https://linux-hardware.org/?probe=f4ecd569d3) | Dec 13, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [231ffcb252](https://linux-hardware.org/?probe=231ffcb252) | Dec 13, 2024 |
| Dell          | 0TTDMJ A00                  | [4ee281d915](https://linux-hardware.org/?probe=4ee281d915) | Dec 11, 2024 |
| HP            | 8396                        | [eef8330bfa](https://linux-hardware.org/?probe=eef8330bfa) | Dec 10, 2024 |
| MSI           | B450M BAZOOKA V2            | [7b9add187d](https://linux-hardware.org/?probe=7b9add187d) | Dec 09, 2024 |
| MSI           | MS-7253                     | [06a8a5402f](https://linux-hardware.org/?probe=06a8a5402f) | Dec 07, 2024 |
| ASUSTek       | PRIME A320M-K               | [2d2064c328](https://linux-hardware.org/?probe=2d2064c328) | Dec 06, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [31412e1466](https://linux-hardware.org/?probe=31412e1466) | Dec 05, 2024 |
| Lenovo        | 3750 SDK0T76528 WIN 3556... | [0f56b0600a](https://linux-hardware.org/?probe=0f56b0600a) | Dec 04, 2024 |
| Intel         | DQ57TM AAE70931-403         | [4cf044143a](https://linux-hardware.org/?probe=4cf044143a) | Dec 04, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [3c075a4675](https://linux-hardware.org/?probe=3c075a4675) | Dec 03, 2024 |
| ASRock        | B450 Gaming K4              | [13516885f4](https://linux-hardware.org/?probe=13516885f4) | Dec 03, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [71dbf99e53](https://linux-hardware.org/?probe=71dbf99e53) | Dec 02, 2024 |
| Gigabyte      | H97M-D3H                    | [f8e5244664](https://linux-hardware.org/?probe=f8e5244664) | Dec 02, 2024 |
| MSI           | PRO B650M-A WIFI            | [0b6eff9251](https://linux-hardware.org/?probe=0b6eff9251) | Dec 01, 2024 |
| ASRock        | X570 Steel Legend           | [1f64e1379e](https://linux-hardware.org/?probe=1f64e1379e) | Dec 01, 2024 |
| ASRock        | B650E Taichi Lite           | [fd3b50600a](https://linux-hardware.org/?probe=fd3b50600a) | Nov 30, 2024 |
| Dell          | 0GDG8Y A00                  | [6af006cbe8](https://linux-hardware.org/?probe=6af006cbe8) | Nov 30, 2024 |
| ASUSTek       | PRIME B550M-A               | [1666d53ef2](https://linux-hardware.org/?probe=1666d53ef2) | Nov 29, 2024 |
| Dell          | 0GDG8Y A00                  | [df9775b867](https://linux-hardware.org/?probe=df9775b867) | Nov 29, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [0e4f7f6345](https://linux-hardware.org/?probe=0e4f7f6345) | Nov 28, 2024 |
| ASRock        | B75M                        | [54a8c00779](https://linux-hardware.org/?probe=54a8c00779) | Nov 28, 2024 |
| ASUSTek       | PRIME B450M-A II            | [e8f597bc75](https://linux-hardware.org/?probe=e8f597bc75) | Nov 28, 2024 |
| HP            | 2129                        | [c42783b47a](https://linux-hardware.org/?probe=c42783b47a) | Nov 28, 2024 |
| Gigabyte      | Z690 UD AX                  | [880222f8da](https://linux-hardware.org/?probe=880222f8da) | Nov 28, 2024 |
| MSI           | Z270 SLI PLUS               | [0298a65f1d](https://linux-hardware.org/?probe=0298a65f1d) | Nov 28, 2024 |
| Gigabyte      | B550 AORUS ELITE            | [0df7b81985](https://linux-hardware.org/?probe=0df7b81985) | Nov 27, 2024 |
| Gigabyte      | B360M D3H-CF                | [f24b6c8c5c](https://linux-hardware.org/?probe=f24b6c8c5c) | Nov 24, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [88c8f0e6d0](https://linux-hardware.org/?probe=88c8f0e6d0) | Nov 24, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [d1aafc3e2a](https://linux-hardware.org/?probe=d1aafc3e2a) | Nov 24, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [9e94883925](https://linux-hardware.org/?probe=9e94883925) | Nov 24, 2024 |
| HP            | 2129                        | [3a95c03859](https://linux-hardware.org/?probe=3a95c03859) | Nov 23, 2024 |
| ASUSTek       | PRIME H610M-A D4            | [54f6f19483](https://linux-hardware.org/?probe=54f6f19483) | Nov 23, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [d3dc594f2a](https://linux-hardware.org/?probe=d3dc594f2a) | Nov 23, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [6089d004eb](https://linux-hardware.org/?probe=6089d004eb) | Nov 22, 2024 |
| ASUSTek       | M5A78L-M LX3                | [29613a4747](https://linux-hardware.org/?probe=29613a4747) | Nov 22, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [4647245b41](https://linux-hardware.org/?probe=4647245b41) | Nov 21, 2024 |
| ASRock        | B450 Pro4                   | [7198d4dd59](https://linux-hardware.org/?probe=7198d4dd59) | Nov 21, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a56921a744](https://linux-hardware.org/?probe=a56921a744) | Nov 21, 2024 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [852ffac66b](https://linux-hardware.org/?probe=852ffac66b) | Nov 21, 2024 |
| MSI           | 760GM-P21                   | [7c2250da16](https://linux-hardware.org/?probe=7c2250da16) | Nov 21, 2024 |
| HP            | 0A58h                       | [8063748e4e](https://linux-hardware.org/?probe=8063748e4e) | Nov 20, 2024 |
| ASUSTek       | P6T DELUXE V2               | [74d8354490](https://linux-hardware.org/?probe=74d8354490) | Nov 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [59b193fae9](https://linux-hardware.org/?probe=59b193fae9) | Nov 20, 2024 |
| ASUSTek       | P6T DELUXE V2               | [be63d0b85f](https://linux-hardware.org/?probe=be63d0b85f) | Nov 20, 2024 |
| MSI           | B450-A PRO MAX              | [d24344a88b](https://linux-hardware.org/?probe=d24344a88b) | Nov 19, 2024 |
| MSI           | MPG Z790 EDGE MONSTER HU... | [dbee9a2410](https://linux-hardware.org/?probe=dbee9a2410) | Nov 19, 2024 |
| Gigabyte      | TRX40 DESIGNARE             | [96735d84cb](https://linux-hardware.org/?probe=96735d84cb) | Nov 18, 2024 |
| ASUSTek       | A58M-A/USB3                 | [3c826c2a94](https://linux-hardware.org/?probe=3c826c2a94) | Nov 17, 2024 |
| ASUSTek       | A58M-A/USB3                 | [1db84a0c21](https://linux-hardware.org/?probe=1db84a0c21) | Nov 17, 2024 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | [8b148efe27](https://linux-hardware.org/?probe=8b148efe27) | Nov 17, 2024 |
| MSI           | MAG X870 TOMAHAWK WIFI      | [f407eb8cc5](https://linux-hardware.org/?probe=f407eb8cc5) | Nov 16, 2024 |
| ASUSTek       | PRIME X470-PRO              | [cc1f1fc7a8](https://linux-hardware.org/?probe=cc1f1fc7a8) | Nov 16, 2024 |
| ASUSTek       | X99-PRO/USB                 | [259b4c7c59](https://linux-hardware.org/?probe=259b4c7c59) | Nov 15, 2024 |
| ASUSTek       | P8H61-MX USB3               | [7b361ec797](https://linux-hardware.org/?probe=7b361ec797) | Nov 15, 2024 |
| MSI           | 890FXA-GD70                 | [10ce427ae8](https://linux-hardware.org/?probe=10ce427ae8) | Nov 15, 2024 |
| Dell          | 0T7D40 A01                  | [ff59806797](https://linux-hardware.org/?probe=ff59806797) | Nov 15, 2024 |
| Dell          | 0T7D40 A01                  | [1fcfdd6e0f](https://linux-hardware.org/?probe=1fcfdd6e0f) | Nov 15, 2024 |
| Dell          | 0WR7PY A02                  | [d528220481](https://linux-hardware.org/?probe=d528220481) | Nov 15, 2024 |
| MSI           | PRO X670-P WIFI             | [4be0aebcd2](https://linux-hardware.org/?probe=4be0aebcd2) | Nov 15, 2024 |
| MSI           | PRO Z690-A DDR4             | [7806627c9a](https://linux-hardware.org/?probe=7806627c9a) | Nov 13, 2024 |
| Gigabyte      | G1.Guerrilla                | [73ef034954](https://linux-hardware.org/?probe=73ef034954) | Nov 12, 2024 |
| MSI           | PRO Z690-A DDR4             | [1b1cb41bb3](https://linux-hardware.org/?probe=1b1cb41bb3) | Nov 12, 2024 |
| MSI           | PRO B550M-VC WIFI           | [666f6b86ca](https://linux-hardware.org/?probe=666f6b86ca) | Nov 12, 2024 |
| Gigabyte      | 970A-D3                     | [8b39d5f772](https://linux-hardware.org/?probe=8b39d5f772) | Nov 11, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [136a3d6103](https://linux-hardware.org/?probe=136a3d6103) | Nov 11, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [33618bc34b](https://linux-hardware.org/?probe=33618bc34b) | Nov 09, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [9d7404555c](https://linux-hardware.org/?probe=9d7404555c) | Nov 09, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [56a7d1166d](https://linux-hardware.org/?probe=56a7d1166d) | Nov 09, 2024 |
| ASUSTek       | PRIME B560M-A               | [e519c240a9](https://linux-hardware.org/?probe=e519c240a9) | Nov 08, 2024 |
| Gigabyte      | Z170X-Gaming 5              | [ac49d10d4b](https://linux-hardware.org/?probe=ac49d10d4b) | Nov 08, 2024 |
| MSI           | P55-GD55                    | [495c5eb870](https://linux-hardware.org/?probe=495c5eb870) | Nov 06, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [eeaba99859](https://linux-hardware.org/?probe=eeaba99859) | Nov 05, 2024 |
| Dell          | 02J54D A01                  | [b01ff9360e](https://linux-hardware.org/?probe=b01ff9360e) | Nov 05, 2024 |
| Gigabyte      | B550 VISION D               | [11e1ff56bd](https://linux-hardware.org/?probe=11e1ff56bd) | Nov 05, 2024 |
| Lenovo        | MAHOBAY NO DPK              | [d32cfbf998](https://linux-hardware.org/?probe=d32cfbf998) | Nov 05, 2024 |
| Dell          | 06X1TJ A00                  | [73582cb9db](https://linux-hardware.org/?probe=73582cb9db) | Nov 04, 2024 |
| MSI           | H97 PC Mate                 | [b887d2c9f3](https://linux-hardware.org/?probe=b887d2c9f3) | Nov 04, 2024 |
| MSI           | B450M PRO-VDH MAX           | [726890cf92](https://linux-hardware.org/?probe=726890cf92) | Nov 03, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [f24090eaec](https://linux-hardware.org/?probe=f24090eaec) | Nov 03, 2024 |
| ASRock        | H170 Pro4                   | [b7b97b0699](https://linux-hardware.org/?probe=b7b97b0699) | Nov 03, 2024 |
| ASUSTek       | Q87M-E                      | [e45e88ac29](https://linux-hardware.org/?probe=e45e88ac29) | Nov 03, 2024 |
| Lenovo        | MAHOBAY NO DPK              | [74c2014e44](https://linux-hardware.org/?probe=74c2014e44) | Nov 02, 2024 |
| HP            | 86E9 A                      | [3cdb636ab2](https://linux-hardware.org/?probe=3cdb636ab2) | Oct 31, 2024 |
| MSI           | A320M-A PRO MAX             | [37d93fcb8c](https://linux-hardware.org/?probe=37d93fcb8c) | Oct 31, 2024 |
| MSI           | PRO A620M-E                 | [1d5498d1f7](https://linux-hardware.org/?probe=1d5498d1f7) | Oct 31, 2024 |
| AZW           | MINI S                      | [25901cc388](https://linux-hardware.org/?probe=25901cc388) | Oct 29, 2024 |
| Gigabyte      | X870 EAGLE WIFI7            | [f02048f788](https://linux-hardware.org/?probe=f02048f788) | Oct 28, 2024 |
| Dell          | 06X1TJ A00                  | [ec05ccbf2e](https://linux-hardware.org/?probe=ec05ccbf2e) | Oct 28, 2024 |
| Gigabyte      | Z790 UD                     | [68afa8fd74](https://linux-hardware.org/?probe=68afa8fd74) | Oct 26, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | [f23e8cfc13](https://linux-hardware.org/?probe=f23e8cfc13) | Oct 24, 2024 |
| HP            | 8643 SMVB                   | [d8f502fc39](https://linux-hardware.org/?probe=d8f502fc39) | Oct 24, 2024 |
| MSI           | MPG Z790 EDGE MONSTER HU... | [623a3231f2](https://linux-hardware.org/?probe=623a3231f2) | Oct 23, 2024 |
| Gigabyte      | B550M DS3H                  | [2294f95e84](https://linux-hardware.org/?probe=2294f95e84) | Oct 22, 2024 |
| OEM           | X79G                        | [c7b397916e](https://linux-hardware.org/?probe=c7b397916e) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | [1e81679f39](https://linux-hardware.org/?probe=1e81679f39) | Oct 22, 2024 |
| Gigabyte      | GA-990FXA-UD3 Ultra-CF      | [305a5ef7f9](https://linux-hardware.org/?probe=305a5ef7f9) | Oct 22, 2024 |
| HP            | 843B                        | [aad1968eb8](https://linux-hardware.org/?probe=aad1968eb8) | Oct 21, 2024 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [d0987d6dca](https://linux-hardware.org/?probe=d0987d6dca) | Oct 20, 2024 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [99917c7138](https://linux-hardware.org/?probe=99917c7138) | Oct 20, 2024 |
| MSI           | PRO Z790-P WIFI DDR4        | [69b436f31f](https://linux-hardware.org/?probe=69b436f31f) | Oct 19, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [4a640a3c83](https://linux-hardware.org/?probe=4a640a3c83) | Oct 19, 2024 |
| Apple         | Mac-F221BEC8                | [3fe9aff632](https://linux-hardware.org/?probe=3fe9aff632) | Oct 19, 2024 |
| ASUSTek       | P5K-E                       | [034970d3a2](https://linux-hardware.org/?probe=034970d3a2) | Oct 18, 2024 |
| ASUSTek       | M4N68T-M-LE-V2              | [041eb0280b](https://linux-hardware.org/?probe=041eb0280b) | Oct 18, 2024 |
| ASUSTek       | M4N68T-M-LE-V2              | [6ab3638a8e](https://linux-hardware.org/?probe=6ab3638a8e) | Oct 18, 2024 |
| Apple         | Mac-F221BEC8                | [4d690686b2](https://linux-hardware.org/?probe=4d690686b2) | Oct 18, 2024 |
| Alienware     | 0H869M A00                  | [ea3e650527](https://linux-hardware.org/?probe=ea3e650527) | Oct 18, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f5d05ce104](https://linux-hardware.org/?probe=f5d05ce104) | Oct 18, 2024 |
| MSI           | PRO B550M-VC WIFI           | [45d96e7a1e](https://linux-hardware.org/?probe=45d96e7a1e) | Oct 18, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | [8f9499e8d0](https://linux-hardware.org/?probe=8f9499e8d0) | Oct 16, 2024 |
| Gigabyte      | B360M DS3H                  | [099c019653](https://linux-hardware.org/?probe=099c019653) | Oct 14, 2024 |
| Gigabyte      | B360M DS3H                  | [cacbc768dd](https://linux-hardware.org/?probe=cacbc768dd) | Oct 14, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [907aac3378](https://linux-hardware.org/?probe=907aac3378) | Oct 14, 2024 |
| ASUSTek       | B85-PLUS                    | [8bf9815ee9](https://linux-hardware.org/?probe=8bf9815ee9) | Oct 13, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [cf2a1639b2](https://linux-hardware.org/?probe=cf2a1639b2) | Oct 13, 2024 |
| Gigabyte      | Z490 UD                     | [ee833d893b](https://linux-hardware.org/?probe=ee833d893b) | Oct 12, 2024 |
| Gigabyte      | Z490 UD                     | [6588ad5982](https://linux-hardware.org/?probe=6588ad5982) | Oct 12, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [da59756930](https://linux-hardware.org/?probe=da59756930) | Oct 11, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [26a9598044](https://linux-hardware.org/?probe=26a9598044) | Oct 10, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [564884a276](https://linux-hardware.org/?probe=564884a276) | Oct 09, 2024 |
| Gigabyte      | B650M AORUS ELITE AX ICE    | [be22a62090](https://linux-hardware.org/?probe=be22a62090) | Oct 08, 2024 |
| Lenovo        | 1066 NOK                    | [197f6c315a](https://linux-hardware.org/?probe=197f6c315a) | Oct 07, 2024 |
| ASUSTek       | PRIME H370-A                | [24ed3d9fde](https://linux-hardware.org/?probe=24ed3d9fde) | Oct 06, 2024 |
| MSI           | B560M PRO                   | [305ee3ff23](https://linux-hardware.org/?probe=305ee3ff23) | Oct 06, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | [9538d0528d](https://linux-hardware.org/?probe=9538d0528d) | Oct 05, 2024 |
| MSI           | B560M PRO                   | [855e013fa7](https://linux-hardware.org/?probe=855e013fa7) | Oct 05, 2024 |
| ASUSTek       | Q87M-E                      | [21cda763c8](https://linux-hardware.org/?probe=21cda763c8) | Oct 02, 2024 |
| Gigabyte      | B75M-D2V                    | [f101a1bc47](https://linux-hardware.org/?probe=f101a1bc47) | Oct 02, 2024 |
| Gigabyte      | B85-HD3                     | [7b518dcbc1](https://linux-hardware.org/?probe=7b518dcbc1) | Sep 29, 2024 |
| Gigabyte      | B85-HD3                     | [1f52e1a158](https://linux-hardware.org/?probe=1f52e1a158) | Sep 29, 2024 |
| MSI           | PRO Z790-P WIFI DDR4        | [4c6b7c9a4c](https://linux-hardware.org/?probe=4c6b7c9a4c) | Sep 28, 2024 |
| MSI           | PRO Z790-P WIFI DDR4        | [edaeafea27](https://linux-hardware.org/?probe=edaeafea27) | Sep 28, 2024 |
| Gigabyte      | B550M DS3H                  | [d1a71cd34c](https://linux-hardware.org/?probe=d1a71cd34c) | Sep 28, 2024 |
| Lenovo        | T530-28ICB                  | [10c4a94075](https://linux-hardware.org/?probe=10c4a94075) | Sep 27, 2024 |
| HP            | 8719                        | [f1362a1ffe](https://linux-hardware.org/?probe=f1362a1ffe) | Sep 26, 2024 |
| ASRock        | AB350 Gaming-ITX/ac         | [6bff48f34e](https://linux-hardware.org/?probe=6bff48f34e) | Sep 26, 2024 |
| ASUSTek       | H87-PRO                     | [3b71228744](https://linux-hardware.org/?probe=3b71228744) | Sep 26, 2024 |
| ASUSTek       | H87-PRO                     | [2ec60febf9](https://linux-hardware.org/?probe=2ec60febf9) | Sep 26, 2024 |
| ASUSTek       | H87-PRO                     | [1d0fe473d6](https://linux-hardware.org/?probe=1d0fe473d6) | Sep 26, 2024 |
| ASUSTek       | PRIME A320M-K               | [c65c6e145d](https://linux-hardware.org/?probe=c65c6e145d) | Sep 25, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [7579b1ab9b](https://linux-hardware.org/?probe=7579b1ab9b) | Sep 24, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | [a7df032b16](https://linux-hardware.org/?probe=a7df032b16) | Sep 24, 2024 |
| Gigabyte      | A520M K V2                  | [252d984741](https://linux-hardware.org/?probe=252d984741) | Sep 24, 2024 |
| HP            | 212A                        | [e464208487](https://linux-hardware.org/?probe=e464208487) | Sep 23, 2024 |
| ASUSTek       | M4A78T-E                    | [c32bc077b2](https://linux-hardware.org/?probe=c32bc077b2) | Sep 23, 2024 |
| ASUSTek       | G11CD-K                     | [98a0bd1025](https://linux-hardware.org/?probe=98a0bd1025) | Sep 22, 2024 |
| ASUSTek       | Rampage V EXTREME           | [85bb4b05c0](https://linux-hardware.org/?probe=85bb4b05c0) | Sep 22, 2024 |
| ASUSTek       | PRIME X370-PRO              | [4eb9594398](https://linux-hardware.org/?probe=4eb9594398) | Sep 19, 2024 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f480b14c3c](https://linux-hardware.org/?probe=f480b14c3c) | Sep 18, 2024 |
| ASUSTek       | P9X79 PRO                   | [dc58a63e60](https://linux-hardware.org/?probe=dc58a63e60) | Sep 17, 2024 |
| HP            | 8054                        | [37a4790243](https://linux-hardware.org/?probe=37a4790243) | Sep 17, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [d9252b3a92](https://linux-hardware.org/?probe=d9252b3a92) | Sep 16, 2024 |
| Gigabyte      | Z390 UD                     | [a69ad92a61](https://linux-hardware.org/?probe=a69ad92a61) | Sep 16, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b6e942427b](https://linux-hardware.org/?probe=b6e942427b) | Sep 16, 2024 |
| Dell          | 0GY6Y8 A02                  | [c6976e2431](https://linux-hardware.org/?probe=c6976e2431) | Sep 15, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [f9dd180792](https://linux-hardware.org/?probe=f9dd180792) | Sep 15, 2024 |
| Gigabyte      | H61M-HD2                    | [51d64e17f3](https://linux-hardware.org/?probe=51d64e17f3) | Sep 13, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [5a9b439eae](https://linux-hardware.org/?probe=5a9b439eae) | Sep 13, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3987ccca17](https://linux-hardware.org/?probe=3987ccca17) | Sep 13, 2024 |
| ASUSTek       | A88XM-E                     | [7eb7662e43](https://linux-hardware.org/?probe=7eb7662e43) | Sep 12, 2024 |
| ASUSTek       | P8H77-V                     | [ff26cf431a](https://linux-hardware.org/?probe=ff26cf431a) | Sep 12, 2024 |
| ASUSTek       | A88XM-E                     | [d92ffcb137](https://linux-hardware.org/?probe=d92ffcb137) | Sep 12, 2024 |
| Gigabyte      | Z390 UD                     | [2ac856efbb](https://linux-hardware.org/?probe=2ac856efbb) | Sep 12, 2024 |
| MSI           | A520M PRO                   | [f5741e4d81](https://linux-hardware.org/?probe=f5741e4d81) | Sep 11, 2024 |
| Lenovo        | 31900058 STD or WIN         | [ce3389610d](https://linux-hardware.org/?probe=ce3389610d) | Sep 10, 2024 |
| MSI           | MEG X570 ACE                | [86504d2098](https://linux-hardware.org/?probe=86504d2098) | Sep 10, 2024 |
| ASUSTek       | PRIME A620-PLUS WIFI6       | [b70dcc4cc4](https://linux-hardware.org/?probe=b70dcc4cc4) | Sep 10, 2024 |
| ASUSTek       | PRIME A620-PLUS WIFI6       | [e2b0e5489b](https://linux-hardware.org/?probe=e2b0e5489b) | Sep 09, 2024 |
| ASRock        | B560M-C                     | [f2ecad1659](https://linux-hardware.org/?probe=f2ecad1659) | Sep 08, 2024 |
| ASUSTek       | Z170M-PLUS                  | [6532896d24](https://linux-hardware.org/?probe=6532896d24) | Sep 07, 2024 |
| ASUSTek       | Z170M-PLUS                  | [03187646eb](https://linux-hardware.org/?probe=03187646eb) | Sep 07, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [bac6274ee1](https://linux-hardware.org/?probe=bac6274ee1) | Sep 06, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [685786d1c7](https://linux-hardware.org/?probe=685786d1c7) | Sep 05, 2024 |
| MSI           | Z370 GAMING M5              | [390e9ff312](https://linux-hardware.org/?probe=390e9ff312) | Sep 05, 2024 |
| ASRock        | H61M-HG4                    | [2c1e1045bc](https://linux-hardware.org/?probe=2c1e1045bc) | Sep 04, 2024 |
| ASRock        | H61M-HG4                    | [aa15d54a45](https://linux-hardware.org/?probe=aa15d54a45) | Sep 04, 2024 |
| Dell          | 0WR7PY A02                  | [bd63a70cd8](https://linux-hardware.org/?probe=bd63a70cd8) | Sep 04, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [7ebdefecdb](https://linux-hardware.org/?probe=7ebdefecdb) | Sep 04, 2024 |
| Gigabyte      | X299 UD4 Pro-CF             | [a2599a2d08](https://linux-hardware.org/?probe=a2599a2d08) | Sep 03, 2024 |
| DFI           | BI P45-T2R                  | [cef2a3926b](https://linux-hardware.org/?probe=cef2a3926b) | Sep 03, 2024 |
| PCWare        | IPMH81G1                    | [88ec731122](https://linux-hardware.org/?probe=88ec731122) | Sep 03, 2024 |
| Dell          | 008PGD A00                  | [88de1510fd](https://linux-hardware.org/?probe=88de1510fd) | Sep 02, 2024 |
| Gigabyte      | H410M S2H V3                | [47b3c8ff2f](https://linux-hardware.org/?probe=47b3c8ff2f) | Sep 02, 2024 |
| Gigabyte      | B450M GAMING                | [f7096e28ed](https://linux-hardware.org/?probe=f7096e28ed) | Aug 30, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [f4202099ef](https://linux-hardware.org/?probe=f4202099ef) | Aug 30, 2024 |
| ASRock        | X600M-STX                   | [86b4ecf63c](https://linux-hardware.org/?probe=86b4ecf63c) | Aug 30, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [046c71fca6](https://linux-hardware.org/?probe=046c71fca6) | Aug 30, 2024 |
| Biostar       | H410MH S2                   | [7f9a0e2e20](https://linux-hardware.org/?probe=7f9a0e2e20) | Aug 29, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [95b0d22a8a](https://linux-hardware.org/?probe=95b0d22a8a) | Aug 29, 2024 |
| ASUSTek       | Maximus IX FORMULA          | [a6d67a9626](https://linux-hardware.org/?probe=a6d67a9626) | Aug 28, 2024 |
| AZW           | GTR V02                     | [d9f34edd52](https://linux-hardware.org/?probe=d9f34edd52) | Aug 28, 2024 |
| MSI           | B550-A PRO                  | [54d02a441b](https://linux-hardware.org/?probe=54d02a441b) | Aug 27, 2024 |
| Lenovo        | 317E NOK                    | [082324eb87](https://linux-hardware.org/?probe=082324eb87) | Aug 27, 2024 |
| Gigabyte      | B660 GAMING X AX DDR4       | [d9f6f3838f](https://linux-hardware.org/?probe=d9f6f3838f) | Aug 27, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [1c2f7c43d7](https://linux-hardware.org/?probe=1c2f7c43d7) | Aug 27, 2024 |
| Gigabyte      | H61M-D2-B3                  | [a59e598a06](https://linux-hardware.org/?probe=a59e598a06) | Aug 26, 2024 |
| Gigabyte      | H61M-D2-B3                  | [9c6f6f0afb](https://linux-hardware.org/?probe=9c6f6f0afb) | Aug 26, 2024 |
| GEEKOM        | A5                          | [bea9f96908](https://linux-hardware.org/?probe=bea9f96908) | Aug 26, 2024 |
| QTQD          | Unknown                     | [3f8f01a343](https://linux-hardware.org/?probe=3f8f01a343) | Aug 25, 2024 |
| QTQD          | Unknown                     | [b78df80c75](https://linux-hardware.org/?probe=b78df80c75) | Aug 25, 2024 |
| Olidata       | ALICON AI2S-A21 0.41        | [df62aa88dc](https://linux-hardware.org/?probe=df62aa88dc) | Aug 24, 2024 |
| ASUSTek       | ROG Maximus XI CODE         | [cd90d865f1](https://linux-hardware.org/?probe=cd90d865f1) | Aug 23, 2024 |
| MSI           | B560M PRO                   | [d03a677894](https://linux-hardware.org/?probe=d03a677894) | Aug 23, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [a47e47619d](https://linux-hardware.org/?probe=a47e47619d) | Aug 23, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [656517aca1](https://linux-hardware.org/?probe=656517aca1) | Aug 20, 2024 |
| Gigabyte      | P55M-UD2                    | [d0502d4b48](https://linux-hardware.org/?probe=d0502d4b48) | Aug 19, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [7dcd3dd92a](https://linux-hardware.org/?probe=7dcd3dd92a) | Aug 19, 2024 |
| GEEKOM        | A5                          | [464fe39877](https://linux-hardware.org/?probe=464fe39877) | Aug 18, 2024 |
| Intel         | DG45ID AAE27729-310         | [af26cce747](https://linux-hardware.org/?probe=af26cce747) | Aug 17, 2024 |
| Intel         | DG45ID AAE27729-310         | [2564478b2d](https://linux-hardware.org/?probe=2564478b2d) | Aug 17, 2024 |
| ASRock        | B660 Steel Legend           | [be5f6f854e](https://linux-hardware.org/?probe=be5f6f854e) | Aug 15, 2024 |
| MSI           | X570-A PRO                  | [9e0a08aa6e](https://linux-hardware.org/?probe=9e0a08aa6e) | Aug 15, 2024 |
| ASUSTek       | P9X79 PRO                   | [6cc8e215fd](https://linux-hardware.org/?probe=6cc8e215fd) | Aug 14, 2024 |
| Gigabyte      | Z690 AERO G                 | [b37e901355](https://linux-hardware.org/?probe=b37e901355) | Aug 12, 2024 |
| Gigabyte      | H61M-S2V-B3                 | [7101790e8c](https://linux-hardware.org/?probe=7101790e8c) | Aug 11, 2024 |
| HP            | 83E0                        | [8a50d98f8d](https://linux-hardware.org/?probe=8a50d98f8d) | Aug 11, 2024 |
| MSI           | Z370 GAMING M5              | [5cd926df4f](https://linux-hardware.org/?probe=5cd926df4f) | Aug 11, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [dc93057966](https://linux-hardware.org/?probe=dc93057966) | Aug 09, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [de83a181b0](https://linux-hardware.org/?probe=de83a181b0) | Aug 09, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [8dadafde08](https://linux-hardware.org/?probe=8dadafde08) | Aug 09, 2024 |
| HP            | 18E5                        | [859cb9444d](https://linux-hardware.org/?probe=859cb9444d) | Aug 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [99722da50c](https://linux-hardware.org/?probe=99722da50c) | Aug 08, 2024 |
| ASUSTek       | PRIME Z370-P                | [f1b1c8064f](https://linux-hardware.org/?probe=f1b1c8064f) | Aug 07, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9f4c2d2d97](https://linux-hardware.org/?probe=9f4c2d2d97) | Aug 06, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | [f0791a3f01](https://linux-hardware.org/?probe=f0791a3f01) | Aug 03, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [99e5eb0e27](https://linux-hardware.org/?probe=99e5eb0e27) | Aug 03, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [8a17f84ab5](https://linux-hardware.org/?probe=8a17f84ab5) | Aug 02, 2024 |
| Dell          | 0GY6Y8 A02                  | [6987f25560](https://linux-hardware.org/?probe=6987f25560) | Aug 01, 2024 |
| Acer          | Predator PO3-640            | [8e58ed0479](https://linux-hardware.org/?probe=8e58ed0479) | Aug 01, 2024 |
| Acer          | Predator PO3-640            | [53f05960f1](https://linux-hardware.org/?probe=53f05960f1) | Aug 01, 2024 |
| ASUSTek       | PRIME B450M-A               | [d31bc372dd](https://linux-hardware.org/?probe=d31bc372dd) | Jul 30, 2024 |
| ASRock        | B660 Steel Legend           | [0497d15b64](https://linux-hardware.org/?probe=0497d15b64) | Jul 29, 2024 |
| HP            | 212B                        | [188ef53aa1](https://linux-hardware.org/?probe=188ef53aa1) | Jul 27, 2024 |
| Dell          | 0JCTF8 A00                  | [609271b737](https://linux-hardware.org/?probe=609271b737) | Jul 26, 2024 |
| Huanan        | X99-QD4 V1.0                | [e9b329a245](https://linux-hardware.org/?probe=e9b329a245) | Jul 25, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [79ffedea38](https://linux-hardware.org/?probe=79ffedea38) | Jul 25, 2024 |
| MSI           | X370 GAMING M7 ACK          | [f4a8fc4903](https://linux-hardware.org/?probe=f4a8fc4903) | Jul 24, 2024 |
| Dell          | 0JCTF8 A00                  | [d156d05e40](https://linux-hardware.org/?probe=d156d05e40) | Jul 24, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [d50a40ed2b](https://linux-hardware.org/?probe=d50a40ed2b) | Jul 23, 2024 |
| ASUSTek       | P9X79 PRO                   | [ef9ee1317d](https://linux-hardware.org/?probe=ef9ee1317d) | Jul 21, 2024 |
| Gigabyte      | B650I AORUS ULTRA           | [c1228312f5](https://linux-hardware.org/?probe=c1228312f5) | Jul 21, 2024 |
| MSI           | B450M PRO-M2                | [00e9d64750](https://linux-hardware.org/?probe=00e9d64750) | Jul 21, 2024 |
| MSI           | B450M PRO-M2                | [bad73c1312](https://linux-hardware.org/?probe=bad73c1312) | Jul 21, 2024 |
| Gigabyte      | B550M H                     | [94de635efb](https://linux-hardware.org/?probe=94de635efb) | Jul 20, 2024 |
| Dell          | 00V62H A00                  | [c4f389a0c4](https://linux-hardware.org/?probe=c4f389a0c4) | Jul 19, 2024 |
| MSI           | A320M PRO-M2                | [3aa1f1ce61](https://linux-hardware.org/?probe=3aa1f1ce61) | Jul 19, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [0a12b25be4](https://linux-hardware.org/?probe=0a12b25be4) | Jul 17, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [8caedf9b79](https://linux-hardware.org/?probe=8caedf9b79) | Jul 17, 2024 |
| Dell          | 0NRKPK A01                  | [0d4d762792](https://linux-hardware.org/?probe=0d4d762792) | Jul 17, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [42391c2183](https://linux-hardware.org/?probe=42391c2183) | Jul 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b0b956f71b](https://linux-hardware.org/?probe=b0b956f71b) | Jul 16, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [acb91cea98](https://linux-hardware.org/?probe=acb91cea98) | Jul 16, 2024 |
| Gigabyte      | Z690 UD AX DDR4             | [83f7dc4e07](https://linux-hardware.org/?probe=83f7dc4e07) | Jul 15, 2024 |
| Gigabyte      | 970A-DS3P                   | [74b27af0c7](https://linux-hardware.org/?probe=74b27af0c7) | Jul 14, 2024 |
| Intel         | B75                         | [019139cea6](https://linux-hardware.org/?probe=019139cea6) | Jul 13, 2024 |
| Intel         | DQ45CB                      | [056671de2c](https://linux-hardware.org/?probe=056671de2c) | Jul 12, 2024 |
| ASRock        | A320M-HDV R4.0              | [ab1d6d4f02](https://linux-hardware.org/?probe=ab1d6d4f02) | Jul 11, 2024 |
| MSI           | B350M MORTAR ARCTIC         | [23bb574c8c](https://linux-hardware.org/?probe=23bb574c8c) | Jul 11, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [675a9a3345](https://linux-hardware.org/?probe=675a9a3345) | Jul 10, 2024 |
| Gigabyte      | X570 GAMING X               | [44c554858a](https://linux-hardware.org/?probe=44c554858a) | Jul 09, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [d7bfcac4c4](https://linux-hardware.org/?probe=d7bfcac4c4) | Jul 07, 2024 |
| ASRock        | X670E PG Lightning          | [1cc396bb97](https://linux-hardware.org/?probe=1cc396bb97) | Jul 07, 2024 |
| HP            | 844C                        | [d582e995e1](https://linux-hardware.org/?probe=d582e995e1) | Jul 06, 2024 |
| MSI           | Z170A GAMING M3             | [381081c48f](https://linux-hardware.org/?probe=381081c48f) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | [a12c62a640](https://linux-hardware.org/?probe=a12c62a640) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | [9f0a26445e](https://linux-hardware.org/?probe=9f0a26445e) | Jul 04, 2024 |
| ASUSTek       | A58M-A/USB3                 | [331c17dec6](https://linux-hardware.org/?probe=331c17dec6) | Jul 03, 2024 |
| ASUSTek       | A58M-A/USB3                 | [b81d9e2bef](https://linux-hardware.org/?probe=b81d9e2bef) | Jul 03, 2024 |
| MSI           | H97 PC Mate                 | [192aecfe03](https://linux-hardware.org/?probe=192aecfe03) | Jul 01, 2024 |
| Dell          | 0NRKPK A01                  | [4a057de067](https://linux-hardware.org/?probe=4a057de067) | Jun 30, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [556ca7b28c](https://linux-hardware.org/?probe=556ca7b28c) | Jun 30, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [b235ef679c](https://linux-hardware.org/?probe=b235ef679c) | Jun 30, 2024 |
| ASUSTek       | PRIME B560M-A               | [f1e2857c3c](https://linux-hardware.org/?probe=f1e2857c3c) | Jun 28, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [52a7324bbd](https://linux-hardware.org/?probe=52a7324bbd) | Jun 27, 2024 |
| Gigabyte      | Z77X-D3H                    | [ac5a906625](https://linux-hardware.org/?probe=ac5a906625) | Jun 26, 2024 |
| HP            | 3048h                       | [d2376a292e](https://linux-hardware.org/?probe=d2376a292e) | Jun 26, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [0d6775faa4](https://linux-hardware.org/?probe=0d6775faa4) | Jun 25, 2024 |
| MSI           | B450M GAMING PLUS           | [5ff25875e7](https://linux-hardware.org/?probe=5ff25875e7) | Jun 25, 2024 |
| HP            | 8053                        | [65f199a428](https://linux-hardware.org/?probe=65f199a428) | Jun 21, 2024 |
| ASUSTek       | PRIME B450M-A               | [c141bd23d2](https://linux-hardware.org/?probe=c141bd23d2) | Jun 20, 2024 |
| TYAN Compu... | S8225                       | [28cfbc1a5f](https://linux-hardware.org/?probe=28cfbc1a5f) | Jun 19, 2024 |
| TYAN Compu... | S8225                       | [a69b6fedc1](https://linux-hardware.org/?probe=a69b6fedc1) | Jun 19, 2024 |
| Gigabyte      | H270-Gaming 3               | [7b5b8138a4](https://linux-hardware.org/?probe=7b5b8138a4) | Jun 19, 2024 |
| Intel         | D54250WYK H13922-305        | [4ad2612e06](https://linux-hardware.org/?probe=4ad2612e06) | Jun 17, 2024 |
| MSI           | Z170A PC MATE               | [b607045dd6](https://linux-hardware.org/?probe=b607045dd6) | Jun 17, 2024 |
| MSI           | H97 PC Mate                 | [2925d8d33c](https://linux-hardware.org/?probe=2925d8d33c) | Jun 17, 2024 |
| Gigabyte      | H470 HD3                    | [ea194468c8](https://linux-hardware.org/?probe=ea194468c8) | Jun 16, 2024 |
| Gigabyte      | H470 HD3                    | [0106eb3156](https://linux-hardware.org/?probe=0106eb3156) | Jun 16, 2024 |
| ASUSTek       | H170 PRO GAMING             | [565b36a3ad](https://linux-hardware.org/?probe=565b36a3ad) | Jun 15, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [627864177d](https://linux-hardware.org/?probe=627864177d) | Jun 15, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [40fe92193e](https://linux-hardware.org/?probe=40fe92193e) | Jun 14, 2024 |
| Intel         | KBL-U V1.x                  | [ecb0a6788e](https://linux-hardware.org/?probe=ecb0a6788e) | Jun 14, 2024 |
| Intel         | KBL-U V1.x                  | [af4503033d](https://linux-hardware.org/?probe=af4503033d) | Jun 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8219ec1dff](https://linux-hardware.org/?probe=8219ec1dff) | Jun 13, 2024 |
| Gigabyte      | GA-880GM-USB3L              | [9a39054d68](https://linux-hardware.org/?probe=9a39054d68) | Jun 13, 2024 |
| Intel         | D54250WYK H13922-305        | [6c2d594571](https://linux-hardware.org/?probe=6c2d594571) | Jun 12, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [bf7847f9e5](https://linux-hardware.org/?probe=bf7847f9e5) | Jun 12, 2024 |
| ASUSTek       | X99-E WS                    | [3d3178dd91](https://linux-hardware.org/?probe=3d3178dd91) | Jun 12, 2024 |
| Gigabyte      | B450M DS3H-CF               | [3e5ff4568e](https://linux-hardware.org/?probe=3e5ff4568e) | Jun 11, 2024 |
| Gigabyte      | B450M DS3H-CF               | [0d7497fff3](https://linux-hardware.org/?probe=0d7497fff3) | Jun 11, 2024 |
| MSI           | X370 GAMING PRO CARBON      | [581618d4c4](https://linux-hardware.org/?probe=581618d4c4) | Jun 10, 2024 |
| Gigabyte      | H61MA-D3V                   | [3dda04a065](https://linux-hardware.org/?probe=3dda04a065) | Jun 10, 2024 |
| Dell          | 0MWYPT A00                  | [7f56e32c62](https://linux-hardware.org/?probe=7f56e32c62) | Jun 09, 2024 |
| Dell          | 0YXT71 A03                  | [5d6ff440ad](https://linux-hardware.org/?probe=5d6ff440ad) | Jun 08, 2024 |
| Dell          | 0MWYPT A00                  | [411eda45bc](https://linux-hardware.org/?probe=411eda45bc) | Jun 07, 2024 |
| HP            | 8459                        | [a50a1ed6d1](https://linux-hardware.org/?probe=a50a1ed6d1) | Jun 07, 2024 |
| Gigabyte      | B450M DS3H-CF               | [232d5224cb](https://linux-hardware.org/?probe=232d5224cb) | Jun 06, 2024 |
| Gigabyte      | B450M DS3H-CF               | [9cb484e2bb](https://linux-hardware.org/?probe=9cb484e2bb) | Jun 06, 2024 |
| MSI           | B450M BAZOOKA V2            | [91bfbb5ab7](https://linux-hardware.org/?probe=91bfbb5ab7) | Jun 05, 2024 |
| Intel         | H81                         | [ce9c224872](https://linux-hardware.org/?probe=ce9c224872) | Jun 05, 2024 |
| Gigabyte      | H61M-D2-B3                  | [3fd69b766e](https://linux-hardware.org/?probe=3fd69b766e) | Jun 04, 2024 |
| Gigabyte      | H61M-D2-B3                  | [23f0243cb5](https://linux-hardware.org/?probe=23f0243cb5) | Jun 04, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [068bb70c47](https://linux-hardware.org/?probe=068bb70c47) | Jun 02, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5efcba88f9](https://linux-hardware.org/?probe=5efcba88f9) | May 30, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [831b8198e7](https://linux-hardware.org/?probe=831b8198e7) | May 30, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [51e8937b76](https://linux-hardware.org/?probe=51e8937b76) | May 29, 2024 |
| ASUSTek       | A68HM-PLUS                  | [7269a7665a](https://linux-hardware.org/?probe=7269a7665a) | May 29, 2024 |
| ASRock        | B450M/ac                    | [e9aef9b33c](https://linux-hardware.org/?probe=e9aef9b33c) | May 27, 2024 |
| ASRock        | B450M/ac                    | [4d00c25f68](https://linux-hardware.org/?probe=4d00c25f68) | May 26, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [aba2c65423](https://linux-hardware.org/?probe=aba2c65423) | May 25, 2024 |
| Gigabyte      | H610M S2H DDR4              | [3180a36aee](https://linux-hardware.org/?probe=3180a36aee) | May 25, 2024 |
| Gigabyte      | H610M S2H DDR4              | [4ab7e9396e](https://linux-hardware.org/?probe=4ab7e9396e) | May 25, 2024 |
| MSI           | Z170A PC MATE               | [387b5b6e54](https://linux-hardware.org/?probe=387b5b6e54) | May 24, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [f2ea369d5b](https://linux-hardware.org/?probe=f2ea369d5b) | May 23, 2024 |
| MSI           | H310M PRO-VDH PLUS          | [643f194265](https://linux-hardware.org/?probe=643f194265) | May 23, 2024 |
| Gigabyte      | H61M-S2PV                   | [c3c1a833e5](https://linux-hardware.org/?probe=c3c1a833e5) | May 22, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [926895f86c](https://linux-hardware.org/?probe=926895f86c) | May 22, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [40e67dc05a](https://linux-hardware.org/?probe=40e67dc05a) | May 21, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [7c52810282](https://linux-hardware.org/?probe=7c52810282) | May 21, 2024 |
| Gigabyte      | G41MT-S2                    | [339885c4a5](https://linux-hardware.org/?probe=339885c4a5) | May 19, 2024 |
| Biostar       | TA870+                      | [c855a150d8](https://linux-hardware.org/?probe=c855a150d8) | May 19, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [95e403024b](https://linux-hardware.org/?probe=95e403024b) | May 19, 2024 |
| ASRock        | X300M-STX                   | [df3903c990](https://linux-hardware.org/?probe=df3903c990) | May 18, 2024 |
| MSI           | B450M PRO-VDH MAX           | [c666b55f28](https://linux-hardware.org/?probe=c666b55f28) | May 17, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3a252c1b3a](https://linux-hardware.org/?probe=3a252c1b3a) | May 17, 2024 |
| ASUSTek       | ProArt Z790-CREATOR WIFI    | [94895721a5](https://linux-hardware.org/?probe=94895721a5) | May 16, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [af0a64b92e](https://linux-hardware.org/?probe=af0a64b92e) | May 16, 2024 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [4a8bbe7243](https://linux-hardware.org/?probe=4a8bbe7243) | May 16, 2024 |
| ASUSTek       | PRIME B450M-A               | [88e8009735](https://linux-hardware.org/?probe=88e8009735) | May 16, 2024 |
| MSI           | B450M BAZOOKA V2            | [3edea8d2ba](https://linux-hardware.org/?probe=3edea8d2ba) | May 16, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [3be85d5c39](https://linux-hardware.org/?probe=3be85d5c39) | May 16, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a9bf894541](https://linux-hardware.org/?probe=a9bf894541) | May 15, 2024 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [f87bbfe315](https://linux-hardware.org/?probe=f87bbfe315) | May 15, 2024 |
| Dell          | 0V8WGR A00                  | [0952eedc0e](https://linux-hardware.org/?probe=0952eedc0e) | May 14, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [1a960af612](https://linux-hardware.org/?probe=1a960af612) | May 13, 2024 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [b4942ac2e3](https://linux-hardware.org/?probe=b4942ac2e3) | May 13, 2024 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [edbc392c50](https://linux-hardware.org/?probe=edbc392c50) | May 13, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [b4f59c93bb](https://linux-hardware.org/?probe=b4f59c93bb) | May 12, 2024 |
| Biostar       | TA870+                      | [ea7273eab0](https://linux-hardware.org/?probe=ea7273eab0) | May 11, 2024 |
| Gigabyte      | A520M S2H                   | [e2c5085b17](https://linux-hardware.org/?probe=e2c5085b17) | May 10, 2024 |
| Gigabyte      | A520M S2H                   | [213160142e](https://linux-hardware.org/?probe=213160142e) | May 10, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [526b09a8b5](https://linux-hardware.org/?probe=526b09a8b5) | May 09, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [c0b370e4f5](https://linux-hardware.org/?probe=c0b370e4f5) | May 09, 2024 |
| Gigabyte      | B450 AORUS M                | [b0cdb15b35](https://linux-hardware.org/?probe=b0cdb15b35) | May 09, 2024 |
| ASRock        | B450 Gaming K4              | [5283cfbe48](https://linux-hardware.org/?probe=5283cfbe48) | May 08, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | [541eebe872](https://linux-hardware.org/?probe=541eebe872) | May 08, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [ab440c0aca](https://linux-hardware.org/?probe=ab440c0aca) | May 08, 2024 |
| ASUSTek       | B150 PRO GAMING             | [d559ef5203](https://linux-hardware.org/?probe=d559ef5203) | May 08, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [af6bde9c97](https://linux-hardware.org/?probe=af6bde9c97) | May 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [1755d8da2b](https://linux-hardware.org/?probe=1755d8da2b) | May 07, 2024 |
| ASUSTek       | P8Z77-I DELUXE              | [6aa44077ff](https://linux-hardware.org/?probe=6aa44077ff) | May 07, 2024 |
| ASUSTek       | PRIME Z490-A                | [a68c1a8752](https://linux-hardware.org/?probe=a68c1a8752) | May 07, 2024 |
| Dell          | 0V8WGR A00                  | [826e11d8af](https://linux-hardware.org/?probe=826e11d8af) | May 05, 2024 |
| Dell          | 06FW8P A01                  | [41be164658](https://linux-hardware.org/?probe=41be164658) | May 04, 2024 |
| HP            | 1494                        | [7b5806585f](https://linux-hardware.org/?probe=7b5806585f) | May 04, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [3c5e2db28c](https://linux-hardware.org/?probe=3c5e2db28c) | May 04, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | [58453faaf6](https://linux-hardware.org/?probe=58453faaf6) | May 03, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | [024f668f69](https://linux-hardware.org/?probe=024f668f69) | May 03, 2024 |
| ECS           | H110M-SI02                  | [6e2344c648](https://linux-hardware.org/?probe=6e2344c648) | May 03, 2024 |
| Dell          | 0HD5W2 A01                  | [b44b5a5556](https://linux-hardware.org/?probe=b44b5a5556) | May 03, 2024 |
| ASUSTek       | B150 PRO GAMING             | [94e57165f0](https://linux-hardware.org/?probe=94e57165f0) | May 03, 2024 |
| ASUSTek       | B150 PRO GAMING             | [4d38c7926c](https://linux-hardware.org/?probe=4d38c7926c) | May 02, 2024 |
| HP            | 8643 SMVB                   | [8c77e42bdd](https://linux-hardware.org/?probe=8c77e42bdd) | May 02, 2024 |
| ASUSTek       | A88XM-E                     | [df8ef63dc3](https://linux-hardware.org/?probe=df8ef63dc3) | May 02, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | [1b914f7922](https://linux-hardware.org/?probe=1b914f7922) | May 01, 2024 |
| Acer          | RS880M05                    | [bc549ed290](https://linux-hardware.org/?probe=bc549ed290) | Apr 30, 2024 |
| EVGA          | Z790 CLASSIFIED.0           | [10ac75bfd8](https://linux-hardware.org/?probe=10ac75bfd8) | Apr 30, 2024 |
| MSI           | B450M BAZOOKA V2            | [12ec4389e8](https://linux-hardware.org/?probe=12ec4389e8) | Apr 30, 2024 |
| Gigabyte      | B550M DS3H AC               | [2d51e08cd6](https://linux-hardware.org/?probe=2d51e08cd6) | Apr 29, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [74c797eef3](https://linux-hardware.org/?probe=74c797eef3) | Apr 29, 2024 |
| HP            | 89EB 11                     | [dd5549c4d7](https://linux-hardware.org/?probe=dd5549c4d7) | Apr 28, 2024 |
| ASUSTek       | PRIME A520M-K               | [e76da56567](https://linux-hardware.org/?probe=e76da56567) | Apr 28, 2024 |
| Gigabyte      | F2A68HM-H                   | [03f841c32a](https://linux-hardware.org/?probe=03f841c32a) | Apr 26, 2024 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [fbeb4be390](https://linux-hardware.org/?probe=fbeb4be390) | Apr 25, 2024 |
| Gigabyte      | B660 GAMING X AX DDR4       | [84b2ad73d1](https://linux-hardware.org/?probe=84b2ad73d1) | Apr 25, 2024 |
| ASRock        | B75 Pro3                    | [87a8013072](https://linux-hardware.org/?probe=87a8013072) | Apr 24, 2024 |
| Gigabyte      | H110M-S2PH-CF               | [f35a83875e](https://linux-hardware.org/?probe=f35a83875e) | Apr 24, 2024 |
| ASRock        | B450M Pro4-F                | [e8d54dd61b](https://linux-hardware.org/?probe=e8d54dd61b) | Apr 23, 2024 |
| MSI           | PRO B650-P WIFI             | [2edbe2e138](https://linux-hardware.org/?probe=2edbe2e138) | Apr 23, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [4485a9e6db](https://linux-hardware.org/?probe=4485a9e6db) | Apr 22, 2024 |
| Dell          | 0N185P A02                  | [1193feda44](https://linux-hardware.org/?probe=1193feda44) | Apr 22, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5b37288076](https://linux-hardware.org/?probe=5b37288076) | Apr 21, 2024 |
| MSI           | PRO Z690-A DDR4             | [f426cfb62e](https://linux-hardware.org/?probe=f426cfb62e) | Apr 21, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | [03eb665cce](https://linux-hardware.org/?probe=03eb665cce) | Apr 20, 2024 |
| Gigabyte      | B85-HD3                     | [110fafe0b0](https://linux-hardware.org/?probe=110fafe0b0) | Apr 20, 2024 |
| ASUSTek       | H81M-A                      | [1ef3d038c5](https://linux-hardware.org/?probe=1ef3d038c5) | Apr 19, 2024 |
| ASUSTek       | A68HM-PLUS                  | [94cd362057](https://linux-hardware.org/?probe=94cd362057) | Apr 19, 2024 |
| ASUSTek       | G10CES                      | [a040e8acd4](https://linux-hardware.org/?probe=a040e8acd4) | Apr 18, 2024 |
| Gigabyte      | GA-870A-UD3                 | [7cd79d20e0](https://linux-hardware.org/?probe=7cd79d20e0) | Apr 18, 2024 |
| Gigabyte      | B360M D3H-CF                | [708c7e8551](https://linux-hardware.org/?probe=708c7e8551) | Apr 18, 2024 |
| Gigabyte      | B360M D3H-CF                | [42b026296c](https://linux-hardware.org/?probe=42b026296c) | Apr 18, 2024 |
| ASRock        | B450M Pro4                  | [36dcccf3ea](https://linux-hardware.org/?probe=36dcccf3ea) | Apr 17, 2024 |
| ASRock        | X670E Taichi                | [aebc928b10](https://linux-hardware.org/?probe=aebc928b10) | Apr 17, 2024 |
| ASUSTek       | A68HM-PLUS                  | [ff144e4ebc](https://linux-hardware.org/?probe=ff144e4ebc) | Apr 17, 2024 |
| ASUSTek       | PRIME Z490-A                | [1e41083adc](https://linux-hardware.org/?probe=1e41083adc) | Apr 17, 2024 |
| Gigabyte      | H110M-S2-CF                 | [8b14a90950](https://linux-hardware.org/?probe=8b14a90950) | Apr 16, 2024 |
| Dell          | 09WH54 A01                  | [a444b54a3b](https://linux-hardware.org/?probe=a444b54a3b) | Apr 14, 2024 |
| Dell          | 09WH54 A01                  | [bc7aeec1d0](https://linux-hardware.org/?probe=bc7aeec1d0) | Apr 14, 2024 |
| MSI           | B360M MORTAR                | [e915eb334e](https://linux-hardware.org/?probe=e915eb334e) | Apr 14, 2024 |
| HP            | 304Ah                       | [912a8508e6](https://linux-hardware.org/?probe=912a8508e6) | Apr 13, 2024 |
| Gigabyte      | GA-870A-UD3                 | [bd4be0124b](https://linux-hardware.org/?probe=bd4be0124b) | Apr 12, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [66b49c3998](https://linux-hardware.org/?probe=66b49c3998) | Apr 12, 2024 |
| Gigabyte      | B550 AORUS PRO              | [5858a2ed28](https://linux-hardware.org/?probe=5858a2ed28) | Apr 12, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [c19812eddd](https://linux-hardware.org/?probe=c19812eddd) | Apr 11, 2024 |
| ASRock        | B450 Gaming K4              | [57a6443eb0](https://linux-hardware.org/?probe=57a6443eb0) | Apr 11, 2024 |
| ASRock        | B450M Pro4-F                | [72a3752add](https://linux-hardware.org/?probe=72a3752add) | Apr 11, 2024 |
| ASRock        | Z790 Riptide WiFi           | [778af9df5e](https://linux-hardware.org/?probe=778af9df5e) | Apr 11, 2024 |
| MSI           | B560M PRO                   | [8fb8045266](https://linux-hardware.org/?probe=8fb8045266) | Apr 10, 2024 |
| MSI           | NF725M-P43                  | [ff3656c7c8](https://linux-hardware.org/?probe=ff3656c7c8) | Apr 10, 2024 |
| MSI           | B560M PRO                   | [9f35872df2](https://linux-hardware.org/?probe=9f35872df2) | Apr 09, 2024 |
| HP            | 2215                        | [7e6e6d5a8e](https://linux-hardware.org/?probe=7e6e6d5a8e) | Apr 09, 2024 |
| ASUSTek       | PRIME X470-PRO              | [35615a89f1](https://linux-hardware.org/?probe=35615a89f1) | Apr 09, 2024 |
| ASUSTek       | PRIME X470-PRO              | [dfc1c56c57](https://linux-hardware.org/?probe=dfc1c56c57) | Apr 09, 2024 |
| Dell          | 0NW73C A00                  | [f6bbc9ee86](https://linux-hardware.org/?probe=f6bbc9ee86) | Apr 08, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [078e1e4a08](https://linux-hardware.org/?probe=078e1e4a08) | Apr 07, 2024 |
| HP            | 2215                        | [eb7f7c122d](https://linux-hardware.org/?probe=eb7f7c122d) | Apr 07, 2024 |
| MSI           | PRO B550M-VC WIFI           | [f8d2db509c](https://linux-hardware.org/?probe=f8d2db509c) | Apr 05, 2024 |
| HP            | 18E7                        | [32fb4595f3](https://linux-hardware.org/?probe=32fb4595f3) | Apr 05, 2024 |
| Biostar       | H410MH S2                   | [c2d62789b8](https://linux-hardware.org/?probe=c2d62789b8) | Apr 04, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [57bfb487f6](https://linux-hardware.org/?probe=57bfb487f6) | Apr 04, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [66aa317734](https://linux-hardware.org/?probe=66aa317734) | Apr 03, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [0ddecde36c](https://linux-hardware.org/?probe=0ddecde36c) | Apr 02, 2024 |
| ASRock        | B450 Gaming K4              | [999ca6d09e](https://linux-hardware.org/?probe=999ca6d09e) | Apr 02, 2024 |
| Intel         | X99                         | [b9d21bc637](https://linux-hardware.org/?probe=b9d21bc637) | Apr 02, 2024 |
| Dell          | 0PTTT9 A01                  | [00d2c75a39](https://linux-hardware.org/?probe=00d2c75a39) | Apr 01, 2024 |
| Huanan        | X99-8M-F V1.2               | [3005ead43c](https://linux-hardware.org/?probe=3005ead43c) | Apr 01, 2024 |
| ASUSTek       | A68HM-PLUS                  | [d346c3ccc9](https://linux-hardware.org/?probe=d346c3ccc9) | Mar 31, 2024 |
| ASRock        | B450M Pro4                  | [58b0db3dfb](https://linux-hardware.org/?probe=58b0db3dfb) | Mar 29, 2024 |
| ASRock        | H310CM-HDV/M.2 SE           | [89b9fc26fd](https://linux-hardware.org/?probe=89b9fc26fd) | Mar 29, 2024 |
| Apple         | Mac-F221BEC8                | [806306c660](https://linux-hardware.org/?probe=806306c660) | Mar 28, 2024 |
| Dell          | 00V62H A01                  | [01dc610c0f](https://linux-hardware.org/?probe=01dc610c0f) | Mar 26, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [9cd1b54ee4](https://linux-hardware.org/?probe=9cd1b54ee4) | Mar 26, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [94f974defe](https://linux-hardware.org/?probe=94f974defe) | Mar 26, 2024 |
| ASUSTek       | P8B75-M                     | [a67e18a770](https://linux-hardware.org/?probe=a67e18a770) | Mar 25, 2024 |
| ASRock        | B550 Taichi                 | [2e2354955b](https://linux-hardware.org/?probe=2e2354955b) | Mar 25, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [932ab537fb](https://linux-hardware.org/?probe=932ab537fb) | Mar 24, 2024 |
| Unknown       | Unknown                     | [a510e47285](https://linux-hardware.org/?probe=a510e47285) | Mar 24, 2024 |
| Dell          | 00V62H A01                  | [ba1cc89018](https://linux-hardware.org/?probe=ba1cc89018) | Mar 24, 2024 |
| MSI           | Z87-G45 GAMING              | [8a396f9c6f](https://linux-hardware.org/?probe=8a396f9c6f) | Mar 24, 2024 |
| Gigabyte      | A520M S2H                   | [9e6a2e1fee](https://linux-hardware.org/?probe=9e6a2e1fee) | Mar 24, 2024 |
| ASUSTek       | P8H61-M LX2 R2.0            | [2eb4acdd5d](https://linux-hardware.org/?probe=2eb4acdd5d) | Mar 23, 2024 |
| MSI           | PRO X670-P WIFI             | [a4cf76123c](https://linux-hardware.org/?probe=a4cf76123c) | Mar 23, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [085d42e647](https://linux-hardware.org/?probe=085d42e647) | Mar 23, 2024 |
| HP            | 83EF                        | [34c1c23a84](https://linux-hardware.org/?probe=34c1c23a84) | Mar 23, 2024 |
| MSI           | MEG X570 UNIFY              | [4c1e8684a4](https://linux-hardware.org/?probe=4c1e8684a4) | Mar 23, 2024 |
| Gigabyte      | Z170X-Gaming 6              | [741bd1ee57](https://linux-hardware.org/?probe=741bd1ee57) | Mar 23, 2024 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [d6d7a1ee5c](https://linux-hardware.org/?probe=d6d7a1ee5c) | Mar 23, 2024 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [d2f79931db](https://linux-hardware.org/?probe=d2f79931db) | Mar 21, 2024 |
| ASRock        | B650E Taichi Lite           | [c8860b992b](https://linux-hardware.org/?probe=c8860b992b) | Mar 21, 2024 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [1971c7bb7b](https://linux-hardware.org/?probe=1971c7bb7b) | Mar 21, 2024 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [527f84d0be](https://linux-hardware.org/?probe=527f84d0be) | Mar 21, 2024 |
| ASRock        | B550M Pro4                  | [2b2b92392e](https://linux-hardware.org/?probe=2b2b92392e) | Mar 20, 2024 |
| MSI           | H97 PC Mate                 | [aea5049f9f](https://linux-hardware.org/?probe=aea5049f9f) | Mar 19, 2024 |
| MSI           | PRO B760-P WIFI             | [f23497e346](https://linux-hardware.org/?probe=f23497e346) | Mar 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [dc6ef0d174](https://linux-hardware.org/?probe=dc6ef0d174) | Mar 19, 2024 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [6f5261ec20](https://linux-hardware.org/?probe=6f5261ec20) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [34e98be7ae](https://linux-hardware.org/?probe=34e98be7ae) | Mar 18, 2024 |
| Dell          | 0WMJ54 A00                  | [306aac13ae](https://linux-hardware.org/?probe=306aac13ae) | Mar 18, 2024 |
| Gigabyte      | B360HD3                     | [a82720d3a4](https://linux-hardware.org/?probe=a82720d3a4) | Mar 18, 2024 |
| MSI           | MEG X570 UNIFY              | [45753de529](https://linux-hardware.org/?probe=45753de529) | Mar 17, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [5d30af07da](https://linux-hardware.org/?probe=5d30af07da) | Mar 16, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [cf14560ac7](https://linux-hardware.org/?probe=cf14560ac7) | Mar 16, 2024 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | [7953afffd9](https://linux-hardware.org/?probe=7953afffd9) | Mar 16, 2024 |
| MSI           | B560M PRO                   | [c51f942cae](https://linux-hardware.org/?probe=c51f942cae) | Mar 15, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [6c0b3fb84c](https://linux-hardware.org/?probe=6c0b3fb84c) | Mar 15, 2024 |
| MSI           | B450M-A PRO MAX             | [80f8e06be3](https://linux-hardware.org/?probe=80f8e06be3) | Mar 15, 2024 |
| HP            | 83EE                        | [3c8891b8fd](https://linux-hardware.org/?probe=3c8891b8fd) | Mar 14, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a507f29fed](https://linux-hardware.org/?probe=a507f29fed) | Mar 14, 2024 |
| Gigabyte      | B550M DS3H                  | [3842a72ce8](https://linux-hardware.org/?probe=3842a72ce8) | Mar 14, 2024 |
| AZW           | MINI S 10                   | [605b7f6b25](https://linux-hardware.org/?probe=605b7f6b25) | Mar 13, 2024 |
| Gigabyte      | Z370 HD3-CF                 | [fe9632e966](https://linux-hardware.org/?probe=fe9632e966) | Mar 13, 2024 |
| Gigabyte      | B550M DS3H                  | [26e6e1854e](https://linux-hardware.org/?probe=26e6e1854e) | Mar 13, 2024 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [5790181302](https://linux-hardware.org/?probe=5790181302) | Mar 12, 2024 |
| ASUSTek       | STRIX Z270G GAMING          | [cd02271f4a](https://linux-hardware.org/?probe=cd02271f4a) | Mar 11, 2024 |
| Gigabyte      | B365M DS3H                  | [f8eeb3ce24](https://linux-hardware.org/?probe=f8eeb3ce24) | Mar 09, 2024 |
| ASRock        | B660 Steel Legend           | [4905884d5a](https://linux-hardware.org/?probe=4905884d5a) | Mar 09, 2024 |
| ASRock        | B660 Steel Legend           | [e439bd4f0e](https://linux-hardware.org/?probe=e439bd4f0e) | Mar 09, 2024 |
| MSI           | GF615M-P33                  | [e90ec20e06](https://linux-hardware.org/?probe=e90ec20e06) | Mar 09, 2024 |
| Gigabyte      | G1.Guerrilla                | [24f2da961a](https://linux-hardware.org/?probe=24f2da961a) | Mar 08, 2024 |
| ASUSTek       | Q87M-E                      | [6c1f8f0b34](https://linux-hardware.org/?probe=6c1f8f0b34) | Mar 08, 2024 |
| ASUSTek       | SABERTOOTH X99              | [c79364c133](https://linux-hardware.org/?probe=c79364c133) | Mar 08, 2024 |
| ASRock        | B450 Gaming K4              | [9f6eb2e3c7](https://linux-hardware.org/?probe=9f6eb2e3c7) | Mar 08, 2024 |
| Gigabyte      | B460M DS3H                  | [334ee373c4](https://linux-hardware.org/?probe=334ee373c4) | Mar 08, 2024 |
| ASUSTek       | PRIME Z790-V WIFI           | [659032a1ad](https://linux-hardware.org/?probe=659032a1ad) | Mar 06, 2024 |
| Huanan        | X99-TF                      | [37d9e7a46b](https://linux-hardware.org/?probe=37d9e7a46b) | Mar 06, 2024 |
| Huanan        | X99-TF                      | [8adcbbcd8e](https://linux-hardware.org/?probe=8adcbbcd8e) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [eb80b5ba45](https://linux-hardware.org/?probe=eb80b5ba45) | Mar 05, 2024 |
| Gigabyte      | G1.Guerrilla                | [a6cb9cdd68](https://linux-hardware.org/?probe=a6cb9cdd68) | Mar 05, 2024 |
| ASUSTek       | PRIME Z790-V WIFI           | [32d4f3439c](https://linux-hardware.org/?probe=32d4f3439c) | Mar 04, 2024 |
| Dell          | 09M8Y8 A01                  | [19c0ac380a](https://linux-hardware.org/?probe=19c0ac380a) | Mar 03, 2024 |
| Gigabyte      | B365M H                     | [513d4bbee5](https://linux-hardware.org/?probe=513d4bbee5) | Mar 02, 2024 |
| Dell          | 0J3C2F A01                  | [9bd2d372ef](https://linux-hardware.org/?probe=9bd2d372ef) | Mar 02, 2024 |
| ASRock        | X470 Master SLI/ac          | [d35d9477d1](https://linux-hardware.org/?probe=d35d9477d1) | Mar 01, 2024 |
| Dell          | 0J3C2F A01                  | [b24ab60b59](https://linux-hardware.org/?probe=b24ab60b59) | Feb 29, 2024 |
| ASUSTek       | Maximus VIII HERO           | [bc62cff5e5](https://linux-hardware.org/?probe=bc62cff5e5) | Feb 28, 2024 |
| ASRock        | Z170 Extreme4               | [20b4c67043](https://linux-hardware.org/?probe=20b4c67043) | Feb 28, 2024 |
| Gigabyte      | 970A-UD3P                   | [b104cb1d44](https://linux-hardware.org/?probe=b104cb1d44) | Feb 28, 2024 |
| Unknown       | Unknown                     | [9c1c3068b1](https://linux-hardware.org/?probe=9c1c3068b1) | Feb 27, 2024 |
| ASUSTek       | H61M-K                      | [9bf9a75794](https://linux-hardware.org/?probe=9bf9a75794) | Feb 26, 2024 |
| ASUSTek       | H61M-K                      | [4fa6f03992](https://linux-hardware.org/?probe=4fa6f03992) | Feb 26, 2024 |
| ASUSTek       | H81M-K                      | [2e7804bd0c](https://linux-hardware.org/?probe=2e7804bd0c) | Feb 25, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [48f560e40a](https://linux-hardware.org/?probe=48f560e40a) | Feb 25, 2024 |
| MSI           | A320M GRENADE               | [540e4beff6](https://linux-hardware.org/?probe=540e4beff6) | Feb 25, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [a8f2561414](https://linux-hardware.org/?probe=a8f2561414) | Feb 25, 2024 |
| MSI           | Z170A PC MATE               | [f2f9a7b540](https://linux-hardware.org/?probe=f2f9a7b540) | Feb 25, 2024 |
| HP            | 158A                        | [dfc6ee3932](https://linux-hardware.org/?probe=dfc6ee3932) | Feb 25, 2024 |
| HP            | 158A                        | [a31b6f549f](https://linux-hardware.org/?probe=a31b6f549f) | Feb 25, 2024 |
| ASUSTek       | H81M-K                      | [0319862f8e](https://linux-hardware.org/?probe=0319862f8e) | Feb 24, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [623fa9174e](https://linux-hardware.org/?probe=623fa9174e) | Feb 24, 2024 |
| MSI           | B560M PRO                   | [baf7dd1c4f](https://linux-hardware.org/?probe=baf7dd1c4f) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [b5c3a0469b](https://linux-hardware.org/?probe=b5c3a0469b) | Feb 23, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | [30442eac39](https://linux-hardware.org/?probe=30442eac39) | Feb 23, 2024 |
| MSI           | MAG B550M MORTAR            | [143d44040c](https://linux-hardware.org/?probe=143d44040c) | Feb 23, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [5f1e566662](https://linux-hardware.org/?probe=5f1e566662) | Feb 22, 2024 |
| Gigabyte      | B450 AORUS M                | [6d096929a9](https://linux-hardware.org/?probe=6d096929a9) | Feb 22, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [b9e21044bf](https://linux-hardware.org/?probe=b9e21044bf) | Feb 21, 2024 |
| HP            | 3047h                       | [c427822595](https://linux-hardware.org/?probe=c427822595) | Feb 20, 2024 |
| HP            | 3047h                       | [ea79dc34bf](https://linux-hardware.org/?probe=ea79dc34bf) | Feb 20, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [9ce3fca007](https://linux-hardware.org/?probe=9ce3fca007) | Feb 19, 2024 |
| Intel         | H61 V1.1                    | [b737c0174f](https://linux-hardware.org/?probe=b737c0174f) | Feb 18, 2024 |
| ASUSTek       | P7H55-M BR                  | [3b30479368](https://linux-hardware.org/?probe=3b30479368) | Feb 18, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [efd4bd356f](https://linux-hardware.org/?probe=efd4bd356f) | Feb 17, 2024 |
| ASUSTek       | H81M-C                      | [0c55d1c68f](https://linux-hardware.org/?probe=0c55d1c68f) | Feb 17, 2024 |
| HP            | 1998                        | [88acae11a0](https://linux-hardware.org/?probe=88acae11a0) | Feb 16, 2024 |
| MSI           | P55-GD55                    | [d6f0f7a03b](https://linux-hardware.org/?probe=d6f0f7a03b) | Feb 16, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [b5a153ca03](https://linux-hardware.org/?probe=b5a153ca03) | Feb 15, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5f0c5d682f](https://linux-hardware.org/?probe=5f0c5d682f) | Feb 15, 2024 |
| Medion        | MS-7797                     | [b557534cdc](https://linux-hardware.org/?probe=b557534cdc) | Feb 14, 2024 |
| HP            | 8643 SMVB                   | [74b837c864](https://linux-hardware.org/?probe=74b837c864) | Feb 13, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [89dc16a204](https://linux-hardware.org/?probe=89dc16a204) | Feb 12, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [d8095f4230](https://linux-hardware.org/?probe=d8095f4230) | Feb 12, 2024 |
| MSI           | Z390-A PRO                  | [310c126d3c](https://linux-hardware.org/?probe=310c126d3c) | Feb 12, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [2ae73a83dc](https://linux-hardware.org/?probe=2ae73a83dc) | Feb 12, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a964ee2b60](https://linux-hardware.org/?probe=a964ee2b60) | Feb 12, 2024 |
| MSI           | B560M PRO                   | [8d6bc7570e](https://linux-hardware.org/?probe=8d6bc7570e) | Feb 10, 2024 |
| Shenzhen M... | F7BSC                       | [ea6f15d115](https://linux-hardware.org/?probe=ea6f15d115) | Feb 10, 2024 |
| ASUSTek       | PRIME A320M-K               | [07c2f9cf19](https://linux-hardware.org/?probe=07c2f9cf19) | Feb 09, 2024 |
| Dell          | 0WN7Y6 A01                  | [8b5a2a98cf](https://linux-hardware.org/?probe=8b5a2a98cf) | Feb 06, 2024 |
| ASRock        | X300M-STX                   | [7e8a301da3](https://linux-hardware.org/?probe=7e8a301da3) | Feb 06, 2024 |
| Gigabyte      | B550M H                     | [a2e43ce689](https://linux-hardware.org/?probe=a2e43ce689) | Feb 05, 2024 |
| MSI           | Z370 PC PRO                 | [980dc7c8ae](https://linux-hardware.org/?probe=980dc7c8ae) | Feb 04, 2024 |
| HP            | 1998                        | [093236a7d8](https://linux-hardware.org/?probe=093236a7d8) | Feb 04, 2024 |
| ASRock        | B450M Pro4                  | [25223a0282](https://linux-hardware.org/?probe=25223a0282) | Feb 03, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [aaebf4ea23](https://linux-hardware.org/?probe=aaebf4ea23) | Feb 02, 2024 |
| MSI           | B450-A PRO                  | [10f58dc52e](https://linux-hardware.org/?probe=10f58dc52e) | Feb 01, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [0d5790b907](https://linux-hardware.org/?probe=0d5790b907) | Feb 01, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [5ec61e07a8](https://linux-hardware.org/?probe=5ec61e07a8) | Feb 01, 2024 |
| MSI           | B450-A PRO                  | [aecf5f7bf1](https://linux-hardware.org/?probe=aecf5f7bf1) | Feb 01, 2024 |
| Gigabyte      | B550M K                     | [1ead3418ae](https://linux-hardware.org/?probe=1ead3418ae) | Jan 31, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [78b2648ff3](https://linux-hardware.org/?probe=78b2648ff3) | Jan 30, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | [d1d5004095](https://linux-hardware.org/?probe=d1d5004095) | Jan 30, 2024 |
| ASUSTek       | P8H61-MX                    | [1d7356527b](https://linux-hardware.org/?probe=1d7356527b) | Jan 30, 2024 |
| MSI           | B450-A PRO                  | [afb7d75f84](https://linux-hardware.org/?probe=afb7d75f84) | Jan 28, 2024 |
| Gigabyte      | A520M S2H                   | [960d1543c0](https://linux-hardware.org/?probe=960d1543c0) | Jan 28, 2024 |
| Gigabyte      | GA-MA770T-UD3P              | [13d6b2dc0a](https://linux-hardware.org/?probe=13d6b2dc0a) | Jan 27, 2024 |
| MSI           | B560M PRO                   | [773f3d7e1c](https://linux-hardware.org/?probe=773f3d7e1c) | Jan 27, 2024 |
| ASUSTek       | M5A97 PLUS                  | [f06a700136](https://linux-hardware.org/?probe=f06a700136) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | [2d860764f7](https://linux-hardware.org/?probe=2d860764f7) | Jan 27, 2024 |
| ASRock        | AB350M Pro4                 | [ab39d263d5](https://linux-hardware.org/?probe=ab39d263d5) | Jan 27, 2024 |
| MSI           | MAG B550 TORPEDO            | [73f56ca35a](https://linux-hardware.org/?probe=73f56ca35a) | Jan 26, 2024 |
| MSI           | MS-B9181                    | [6575c3c5ad](https://linux-hardware.org/?probe=6575c3c5ad) | Jan 25, 2024 |
| MSI           | B560M PRO-E                 | [898383016a](https://linux-hardware.org/?probe=898383016a) | Jan 25, 2024 |
| ASUSTek       | PRIME A320M-K               | [0bdecdf839](https://linux-hardware.org/?probe=0bdecdf839) | Jan 24, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [89d705627b](https://linux-hardware.org/?probe=89d705627b) | Jan 24, 2024 |
| ASUSTek       | A55BM-E                     | [3d3b63f7c5](https://linux-hardware.org/?probe=3d3b63f7c5) | Jan 22, 2024 |
| Gigabyte      | A520M S2H                   | [bbfb471169](https://linux-hardware.org/?probe=bbfb471169) | Jan 22, 2024 |
| ASRock        | B460M Pro4                  | [65b69b2422](https://linux-hardware.org/?probe=65b69b2422) | Jan 21, 2024 |
| MSI           | B350M MORTAR                | [e65dc0f60c](https://linux-hardware.org/?probe=e65dc0f60c) | Jan 21, 2024 |
| MSI           | B450-A PRO                  | [e11e6780da](https://linux-hardware.org/?probe=e11e6780da) | Jan 20, 2024 |
| Apple         | Mac-F221BEC8                | [e435385c77](https://linux-hardware.org/?probe=e435385c77) | Jan 20, 2024 |
| MSI           | H510M-A PRO                 | [d82c1229a9](https://linux-hardware.org/?probe=d82c1229a9) | Jan 20, 2024 |
| Gigabyte      | B450M DS3H-CF               | [30d4375ab2](https://linux-hardware.org/?probe=30d4375ab2) | Jan 20, 2024 |
| HP            | 8298                        | [9702f87120](https://linux-hardware.org/?probe=9702f87120) | Jan 18, 2024 |
| ASUSTek       | PRIME X570-PRO              | [fe59a3038f](https://linux-hardware.org/?probe=fe59a3038f) | Jan 16, 2024 |
| ASUSTek       | Z87-PLUS                    | [8636e544df](https://linux-hardware.org/?probe=8636e544df) | Jan 15, 2024 |
| MSI           | Z170A PC MATE               | [9df326ae6f](https://linux-hardware.org/?probe=9df326ae6f) | Jan 15, 2024 |
| ASUSTek       | H81M-C                      | [3437acb566](https://linux-hardware.org/?probe=3437acb566) | Jan 15, 2024 |
| ASRock        | X300M-STX                   | [2802b8b35f](https://linux-hardware.org/?probe=2802b8b35f) | Jan 14, 2024 |
| Intel         | H81                         | [fee8b2f668](https://linux-hardware.org/?probe=fee8b2f668) | Jan 13, 2024 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [5688ffafb8](https://linux-hardware.org/?probe=5688ffafb8) | Jan 13, 2024 |
| Dell          | 0YXT71 A00                  | [c82074b2f4](https://linux-hardware.org/?probe=c82074b2f4) | Jan 12, 2024 |
| ASRock        | B450M Pro4-F                | [99dfb1abed](https://linux-hardware.org/?probe=99dfb1abed) | Jan 11, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [80799f979c](https://linux-hardware.org/?probe=80799f979c) | Jan 10, 2024 |
| MSI           | B450M-A PRO MAX             | [09ec307e39](https://linux-hardware.org/?probe=09ec307e39) | Jan 10, 2024 |
| ASUSTek       | H81M-C                      | [234e6e24b3](https://linux-hardware.org/?probe=234e6e24b3) | Jan 10, 2024 |
| ASUSTek       | SABERTOOTH X99              | [a8116aaf03](https://linux-hardware.org/?probe=a8116aaf03) | Jan 10, 2024 |
| ASRock        | B550M Pro SE                | [2a7c9822b3](https://linux-hardware.org/?probe=2a7c9822b3) | Jan 10, 2024 |
| MSI           | H510M-A PRO                 | [625e6af2b6](https://linux-hardware.org/?probe=625e6af2b6) | Jan 09, 2024 |
| ASRock        | B450 Gaming K4              | [9446a22c53](https://linux-hardware.org/?probe=9446a22c53) | Jan 09, 2024 |
| ASUSTek       | M5A97 PLUS                  | [d22d465f0f](https://linux-hardware.org/?probe=d22d465f0f) | Jan 09, 2024 |
| MSI           | 970 GAMING                  | [68c61980ac](https://linux-hardware.org/?probe=68c61980ac) | Jan 08, 2024 |
| ASUSTek       | Maximus V FORMULA           | [4380071e4e](https://linux-hardware.org/?probe=4380071e4e) | Jan 08, 2024 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [5f59758f89](https://linux-hardware.org/?probe=5f59758f89) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [345ae1cb3d](https://linux-hardware.org/?probe=345ae1cb3d) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [280d389295](https://linux-hardware.org/?probe=280d389295) | Jan 05, 2024 |
| ASUSTek       | B85M-E                      | [6207f6a6cc](https://linux-hardware.org/?probe=6207f6a6cc) | Jan 04, 2024 |
| Dell          | 0NDYHG A00                  | [3eb6487c6e](https://linux-hardware.org/?probe=3eb6487c6e) | Jan 04, 2024 |
| ASUSTek       | Maximus V FORMULA           | [6c4433d5e3](https://linux-hardware.org/?probe=6c4433d5e3) | Jan 03, 2024 |
| HP            | 2B36                        | [adbdd18377](https://linux-hardware.org/?probe=adbdd18377) | Jan 03, 2024 |
| HP            | 2B36                        | [5c8c804c7e](https://linux-hardware.org/?probe=5c8c804c7e) | Jan 03, 2024 |
| ASUSTek       | PRIME B550M-K               | [54c131d794](https://linux-hardware.org/?probe=54c131d794) | Jan 03, 2024 |
| ASRock        | 970 Pro3 R2.0               | [508424d991](https://linux-hardware.org/?probe=508424d991) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [769bd9153a](https://linux-hardware.org/?probe=769bd9153a) | Jan 01, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [9c99c1bf71](https://linux-hardware.org/?probe=9c99c1bf71) | Dec 31, 2023 |
| ASRock        | B75M-DGS                    | [3a2df88d60](https://linux-hardware.org/?probe=3a2df88d60) | Dec 31, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [080172526c](https://linux-hardware.org/?probe=080172526c) | Dec 31, 2023 |
| HP            | 8949 11                     | [1add0bc0e2](https://linux-hardware.org/?probe=1add0bc0e2) | Dec 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | [2f24e45b02](https://linux-hardware.org/?probe=2f24e45b02) | Dec 29, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [0daa9bd3eb](https://linux-hardware.org/?probe=0daa9bd3eb) | Dec 29, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [3bf93539f3](https://linux-hardware.org/?probe=3bf93539f3) | Dec 28, 2023 |
| ASUSTek       | H170-PRO                    | [969aa3e243](https://linux-hardware.org/?probe=969aa3e243) | Dec 26, 2023 |
| MSI           | H510M-A PRO                 | [0260c1a342](https://linux-hardware.org/?probe=0260c1a342) | Dec 26, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [25e443386a](https://linux-hardware.org/?probe=25e443386a) | Dec 26, 2023 |
| ASUSTek       | PRIME Z370-A II             | [2013c4457a](https://linux-hardware.org/?probe=2013c4457a) | Dec 26, 2023 |
| ASRock        | X670E Taichi                | [281602cb0e](https://linux-hardware.org/?probe=281602cb0e) | Dec 26, 2023 |
| MSI           | GF615M-P33                  | [9e99d63708](https://linux-hardware.org/?probe=9e99d63708) | Dec 25, 2023 |
| MSI           | H510M-A PRO                 | [9f369b34fa](https://linux-hardware.org/?probe=9f369b34fa) | Dec 24, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [cccb18ead9](https://linux-hardware.org/?probe=cccb18ead9) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | [d845a3492b](https://linux-hardware.org/?probe=d845a3492b) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | [a6e1fc3b29](https://linux-hardware.org/?probe=a6e1fc3b29) | Dec 24, 2023 |
| MSI           | PRO B650-S WIFI             | [c084478d6e](https://linux-hardware.org/?probe=c084478d6e) | Dec 24, 2023 |
| MSI           | H510M-A PRO                 | [fe19f4de86](https://linux-hardware.org/?probe=fe19f4de86) | Dec 23, 2023 |
| MSI           | B560M PRO                   | [3885df62ab](https://linux-hardware.org/?probe=3885df62ab) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| ASUSTek       | Maximus VI GENE             | [178aab1062](https://linux-hardware.org/?probe=178aab1062) | Dec 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [98298e164f](https://linux-hardware.org/?probe=98298e164f) | Dec 20, 2023 |
| HP            | 83E0                        | [8f41483d26](https://linux-hardware.org/?probe=8f41483d26) | Dec 19, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [df369cf5be](https://linux-hardware.org/?probe=df369cf5be) | Dec 19, 2023 |
| Lenovo        | 3704 SDK0K17763 WIN 1801... | [9a2472e628](https://linux-hardware.org/?probe=9a2472e628) | Dec 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [448a2dec7d](https://linux-hardware.org/?probe=448a2dec7d) | Dec 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ebfec06632](https://linux-hardware.org/?probe=ebfec06632) | Dec 17, 2023 |
| ASRock        | H310CM-HG4                  | [4e47d91bc7](https://linux-hardware.org/?probe=4e47d91bc7) | Dec 17, 2023 |
| Dell          | 0VHWTR A01                  | [78ef6792a1](https://linux-hardware.org/?probe=78ef6792a1) | Dec 16, 2023 |
| ASRock        | 760GM-HDV                   | [c1403f5d52](https://linux-hardware.org/?probe=c1403f5d52) | Dec 15, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [ebfb65701f](https://linux-hardware.org/?probe=ebfb65701f) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [25b995fdda](https://linux-hardware.org/?probe=25b995fdda) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [52ffec69ce](https://linux-hardware.org/?probe=52ffec69ce) | Dec 12, 2023 |
| Gigabyte      | Z97N-WIFI                   | [514227865f](https://linux-hardware.org/?probe=514227865f) | Dec 12, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2cfceea8dc](https://linux-hardware.org/?probe=2cfceea8dc) | Dec 12, 2023 |
| Gigabyte      | Z270-Gaming K3 2017-06-1... | [5292573e8d](https://linux-hardware.org/?probe=5292573e8d) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [098d790720](https://linux-hardware.org/?probe=098d790720) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [090ebbd9dd](https://linux-hardware.org/?probe=090ebbd9dd) | Dec 10, 2023 |
| ASRock        | B450 Gaming K4              | [581807905e](https://linux-hardware.org/?probe=581807905e) | Dec 10, 2023 |
| Dell          | 0NDYHG A01                  | [f7f70db230](https://linux-hardware.org/?probe=f7f70db230) | Dec 08, 2023 |
| ASRock        | B550M Steel Legend          | [eac155f5e6](https://linux-hardware.org/?probe=eac155f5e6) | Dec 08, 2023 |
| Unknown       | Unknown                     | [c652e80145](https://linux-hardware.org/?probe=c652e80145) | Dec 08, 2023 |
| Gigabyte      | B550M DS3H                  | [650771c55d](https://linux-hardware.org/?probe=650771c55d) | Dec 07, 2023 |
| Unknown       | Unknown                     | [1dd3b89bd1](https://linux-hardware.org/?probe=1dd3b89bd1) | Dec 07, 2023 |
| HP            | 83E0                        | [a4266f2a5e](https://linux-hardware.org/?probe=a4266f2a5e) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7d7cf8fd3d](https://linux-hardware.org/?probe=7d7cf8fd3d) | Dec 06, 2023 |
| ASRock        | B450 Pro4                   | [1d99a563c9](https://linux-hardware.org/?probe=1d99a563c9) | Dec 05, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [3a8de1659a](https://linux-hardware.org/?probe=3a8de1659a) | Dec 05, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [362161fd73](https://linux-hardware.org/?probe=362161fd73) | Dec 04, 2023 |
| Gigabyte      | Z97N-WIFI                   | [aeae361474](https://linux-hardware.org/?probe=aeae361474) | Dec 04, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [8b11ad9f77](https://linux-hardware.org/?probe=8b11ad9f77) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ae8ecce4bd](https://linux-hardware.org/?probe=ae8ecce4bd) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [0b017377f1](https://linux-hardware.org/?probe=0b017377f1) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [0338afa4db](https://linux-hardware.org/?probe=0338afa4db) | Dec 01, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [940148ec06](https://linux-hardware.org/?probe=940148ec06) | Dec 01, 2023 |
| Unknown       | Unknown                     | [cd167c532c](https://linux-hardware.org/?probe=cd167c532c) | Dec 01, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [bb6640572b](https://linux-hardware.org/?probe=bb6640572b) | Nov 30, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [a139e1830c](https://linux-hardware.org/?probe=a139e1830c) | Nov 29, 2023 |
| ASRock        | H310CM-HG4                  | [bd3a1b9c9a](https://linux-hardware.org/?probe=bd3a1b9c9a) | Nov 28, 2023 |
| Gigabyte      | A55M-DS2                    | [bb5c7bef3f](https://linux-hardware.org/?probe=bb5c7bef3f) | Nov 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [77e8b3479a](https://linux-hardware.org/?probe=77e8b3479a) | Nov 27, 2023 |
| HP            | 2820h                       | [e9bdfab0be](https://linux-hardware.org/?probe=e9bdfab0be) | Nov 27, 2023 |
| HP            | 2B36                        | [3e8b681ec7](https://linux-hardware.org/?probe=3e8b681ec7) | Nov 27, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [bb98eb3ce9](https://linux-hardware.org/?probe=bb98eb3ce9) | Nov 26, 2023 |
| ASRock        | N68C-S UCC                  | [a5b04f6fdb](https://linux-hardware.org/?probe=a5b04f6fdb) | Nov 24, 2023 |
| Apple         | Mac-F221BEC8                | [b11d29c96b](https://linux-hardware.org/?probe=b11d29c96b) | Nov 24, 2023 |
| MSI           | B550M PRO                   | [e834bc66b9](https://linux-hardware.org/?probe=e834bc66b9) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [2a14b62cf5](https://linux-hardware.org/?probe=2a14b62cf5) | Nov 24, 2023 |
| ASRock        | B450 Gaming K4              | [ee82d7417c](https://linux-hardware.org/?probe=ee82d7417c) | Nov 23, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [bc11e1264c](https://linux-hardware.org/?probe=bc11e1264c) | Nov 22, 2023 |
| Dell          | 0WPMFG A00                  | [9cf9520fc3](https://linux-hardware.org/?probe=9cf9520fc3) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [7a4e5e7709](https://linux-hardware.org/?probe=7a4e5e7709) | Nov 19, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [5368b237d8](https://linux-hardware.org/?probe=5368b237d8) | Nov 18, 2023 |
| Gigabyte      | P35-DS3                     | [ece45e3b1c](https://linux-hardware.org/?probe=ece45e3b1c) | Nov 18, 2023 |
| Gigabyte      | P35-DS3                     | [1f7e5feb84](https://linux-hardware.org/?probe=1f7e5feb84) | Nov 17, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [7af93dbd28](https://linux-hardware.org/?probe=7af93dbd28) | Nov 17, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [e57d2d64f5](https://linux-hardware.org/?probe=e57d2d64f5) | Nov 17, 2023 |
| Unknown       | Unknown                     | [90f5f3a274](https://linux-hardware.org/?probe=90f5f3a274) | Nov 14, 2023 |
| ASRock        | A320M-HDV R4.0              | [a09eca53d5](https://linux-hardware.org/?probe=a09eca53d5) | Nov 14, 2023 |
| Gigabyte      | P35-DS3                     | [fac1d1b119](https://linux-hardware.org/?probe=fac1d1b119) | Nov 14, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [f29ef35eec](https://linux-hardware.org/?probe=f29ef35eec) | Nov 13, 2023 |
| Gigabyte      | H510M S2H V2                | [8599ff1b2c](https://linux-hardware.org/?probe=8599ff1b2c) | Nov 13, 2023 |
| ASUSTek       | Z87-A                       | [08f1651d1f](https://linux-hardware.org/?probe=08f1651d1f) | Nov 12, 2023 |
| Gigabyte      | H510M S2H V2                | [238ea043b4](https://linux-hardware.org/?probe=238ea043b4) | Nov 10, 2023 |
| Dell          | 04YP6J A02                  | [b7f860630b](https://linux-hardware.org/?probe=b7f860630b) | Nov 10, 2023 |
| ASRock        | B760M PG Riptide            | [6c0d3672d5](https://linux-hardware.org/?probe=6c0d3672d5) | Nov 10, 2023 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [10234424e1](https://linux-hardware.org/?probe=10234424e1) | Nov 09, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [14438106c9](https://linux-hardware.org/?probe=14438106c9) | Nov 09, 2023 |
| ASRock        | A320M-HDV R4.0              | [8ba89e650a](https://linux-hardware.org/?probe=8ba89e650a) | Nov 08, 2023 |
| HP            | 158B                        | [b8bd2429fa](https://linux-hardware.org/?probe=b8bd2429fa) | Nov 07, 2023 |
| MSI           | MAG B550 TORPEDO            | [fc34295ec7](https://linux-hardware.org/?probe=fc34295ec7) | Nov 07, 2023 |
| HP            | 8053                        | [c46468ecb6](https://linux-hardware.org/?probe=c46468ecb6) | Nov 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7152c7ed2c](https://linux-hardware.org/?probe=7152c7ed2c) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | [034b113ac8](https://linux-hardware.org/?probe=034b113ac8) | Nov 05, 2023 |
| Gigabyte      | B650M DS3H                  | [a424739d4f](https://linux-hardware.org/?probe=a424739d4f) | Nov 05, 2023 |
| HP            | 1998                        | [d454314b77](https://linux-hardware.org/?probe=d454314b77) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [f45893cbf7](https://linux-hardware.org/?probe=f45893cbf7) | Nov 05, 2023 |
| MSI           | H110I PRO                   | [c335c71c4b](https://linux-hardware.org/?probe=c335c71c4b) | Nov 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [8841ab599e](https://linux-hardware.org/?probe=8841ab599e) | Nov 04, 2023 |
| MSI           | B560M PRO                   | [903907b7c0](https://linux-hardware.org/?probe=903907b7c0) | Nov 04, 2023 |
| Lenovo        | 317E NOK                    | [1d038af880](https://linux-hardware.org/?probe=1d038af880) | Nov 04, 2023 |
| ASRock        | B550M Pro4                  | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [798cba826c](https://linux-hardware.org/?probe=798cba826c) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2c601304f7](https://linux-hardware.org/?probe=2c601304f7) | Nov 04, 2023 |
| HP            | 0B54h D                     | [574e5fd946](https://linux-hardware.org/?probe=574e5fd946) | Nov 03, 2023 |
| ASRock        | A320M-HDV R4.0              | [44890192a1](https://linux-hardware.org/?probe=44890192a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2aa4f1a7f7](https://linux-hardware.org/?probe=2aa4f1a7f7) | Nov 03, 2023 |
| ASUSTek       | PRIME H770-PLUS D4          | [62645c6b56](https://linux-hardware.org/?probe=62645c6b56) | Nov 02, 2023 |
| Dell          | 0200DY A02                  | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| MSI           | B560M PRO                   | [adf6c161fa](https://linux-hardware.org/?probe=adf6c161fa) | Nov 02, 2023 |
| Unknown       | 1.0                         | [6265787d93](https://linux-hardware.org/?probe=6265787d93) | Nov 01, 2023 |
| ASUSTek       | PRIME B450M-A II            | [08ee10dc83](https://linux-hardware.org/?probe=08ee10dc83) | Nov 01, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [e03b553957](https://linux-hardware.org/?probe=e03b553957) | Nov 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [7b71031ba1](https://linux-hardware.org/?probe=7b71031ba1) | Oct 31, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [3ab77e3324](https://linux-hardware.org/?probe=3ab77e3324) | Oct 31, 2023 |
| ASRock        | A320M-HDV R4.0              | [7941dfd8cf](https://linux-hardware.org/?probe=7941dfd8cf) | Oct 31, 2023 |
| ASRock        | B550M Steel Legend          | [f123c19bb4](https://linux-hardware.org/?probe=f123c19bb4) | Oct 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | [6cafea6b4c](https://linux-hardware.org/?probe=6cafea6b4c) | Oct 30, 2023 |
| GEEKOM        | Mini IT12                   | [b9509f49f1](https://linux-hardware.org/?probe=b9509f49f1) | Oct 28, 2023 |
| MSI           | GF615M-P33                  | [10af2377c2](https://linux-hardware.org/?probe=10af2377c2) | Oct 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | [80b9cb5e56](https://linux-hardware.org/?probe=80b9cb5e56) | Oct 28, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | [52e07e7ffe](https://linux-hardware.org/?probe=52e07e7ffe) | Oct 28, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | [7610254116](https://linux-hardware.org/?probe=7610254116) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | [484d866dc6](https://linux-hardware.org/?probe=484d866dc6) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | [a619c8a955](https://linux-hardware.org/?probe=a619c8a955) | Oct 27, 2023 |
| ASRock        | B450 Gaming K4              | [15488b723a](https://linux-hardware.org/?probe=15488b723a) | Oct 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e8432e79c8](https://linux-hardware.org/?probe=e8432e79c8) | Oct 26, 2023 |
| MSI           | B450-A PRO                  | [e71634ac32](https://linux-hardware.org/?probe=e71634ac32) | Oct 26, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [3a1039b4b6](https://linux-hardware.org/?probe=3a1039b4b6) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9cb0b1ec27](https://linux-hardware.org/?probe=9cb0b1ec27) | Oct 26, 2023 |
| ASUSTek       | Z170-P                      | [62bbdaec23](https://linux-hardware.org/?probe=62bbdaec23) | Oct 24, 2023 |
| HP            | 212B                        | [714373878e](https://linux-hardware.org/?probe=714373878e) | Oct 24, 2023 |
| HP            | 83EF                        | [9953e14c0a](https://linux-hardware.org/?probe=9953e14c0a) | Oct 24, 2023 |
| ASUSTek       | Z170-P                      | [47b5a808aa](https://linux-hardware.org/?probe=47b5a808aa) | Oct 24, 2023 |
| MSI           | Z390-A PRO                  | [48233204f6](https://linux-hardware.org/?probe=48233204f6) | Oct 23, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [07e8b4df09](https://linux-hardware.org/?probe=07e8b4df09) | Oct 23, 2023 |
| ASRock        | B760M PG Riptide            | [d1f12415b9](https://linux-hardware.org/?probe=d1f12415b9) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [cb6130951a](https://linux-hardware.org/?probe=cb6130951a) | Oct 23, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [ce9770538c](https://linux-hardware.org/?probe=ce9770538c) | Oct 22, 2023 |
| Dell          | 09WH54 A01                  | [4211349cc4](https://linux-hardware.org/?probe=4211349cc4) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [67c6d6e482](https://linux-hardware.org/?probe=67c6d6e482) | Oct 21, 2023 |
| ASRock        | H97M Pro4                   | [04f6bc7f0c](https://linux-hardware.org/?probe=04f6bc7f0c) | Oct 21, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1ae8f16052](https://linux-hardware.org/?probe=1ae8f16052) | Oct 21, 2023 |
| ASUSTek       | PRIME B450M-K               | [a0b48d8a7e](https://linux-hardware.org/?probe=a0b48d8a7e) | Oct 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [17f5bf3cef](https://linux-hardware.org/?probe=17f5bf3cef) | Oct 20, 2023 |
| ASRock        | B450 Gaming K4              | [65f3d76afa](https://linux-hardware.org/?probe=65f3d76afa) | Oct 19, 2023 |
| MSI           | Z390-A PRO                  | [7fd0eeaeec](https://linux-hardware.org/?probe=7fd0eeaeec) | Oct 19, 2023 |
| Biostar       | A320MH                      | [e2c20a6c0c](https://linux-hardware.org/?probe=e2c20a6c0c) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-PRO              | [84517c1f4c](https://linux-hardware.org/?probe=84517c1f4c) | Oct 19, 2023 |
| Biostar       | A320MH                      | [62a3d049b2](https://linux-hardware.org/?probe=62a3d049b2) | Oct 18, 2023 |
| ASRock        | AB350 Pro4                  | [71eba7e232](https://linux-hardware.org/?probe=71eba7e232) | Oct 18, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [f824921cbb](https://linux-hardware.org/?probe=f824921cbb) | Oct 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5f780203e2](https://linux-hardware.org/?probe=5f780203e2) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [9b7bc3fc9d](https://linux-hardware.org/?probe=9b7bc3fc9d) | Oct 16, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [c976b314a2](https://linux-hardware.org/?probe=c976b314a2) | Oct 16, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [af4857609e](https://linux-hardware.org/?probe=af4857609e) | Oct 15, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [f71ad29f6a](https://linux-hardware.org/?probe=f71ad29f6a) | Oct 15, 2023 |
| Gigabyte      | A520M DS3H                  | [e79f4b834d](https://linux-hardware.org/?probe=e79f4b834d) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [ac840f060f](https://linux-hardware.org/?probe=ac840f060f) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | [d1386e080d](https://linux-hardware.org/?probe=d1386e080d) | Oct 12, 2023 |
| MSI           | B560M PRO                   | [3ad673132a](https://linux-hardware.org/?probe=3ad673132a) | Oct 12, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [17b8025f8d](https://linux-hardware.org/?probe=17b8025f8d) | Oct 11, 2023 |
| Lenovo        | 317E NOK                    | [618b7ebe59](https://linux-hardware.org/?probe=618b7ebe59) | Oct 11, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [e185192929](https://linux-hardware.org/?probe=e185192929) | Oct 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [a5c5f58ddb](https://linux-hardware.org/?probe=a5c5f58ddb) | Oct 11, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [2c7e31eb6f](https://linux-hardware.org/?probe=2c7e31eb6f) | Oct 09, 2023 |
| ASRock        | B760M PG Riptide            | [9b5474fee0](https://linux-hardware.org/?probe=9b5474fee0) | Oct 09, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [90041fa012](https://linux-hardware.org/?probe=90041fa012) | Oct 09, 2023 |
| ASUSTek       | P8H67-M EVO                 | [146bc4cb2c](https://linux-hardware.org/?probe=146bc4cb2c) | Oct 08, 2023 |
| MSI           | B450M MORTAR MAX            | [b03eea6d75](https://linux-hardware.org/?probe=b03eea6d75) | Oct 08, 2023 |
| HP            | 212B                        | [faa56daf1d](https://linux-hardware.org/?probe=faa56daf1d) | Oct 07, 2023 |
| HP            | 83E8                        | [c1028de72b](https://linux-hardware.org/?probe=c1028de72b) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e401b0c370](https://linux-hardware.org/?probe=e401b0c370) | Oct 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [ad60cd6e18](https://linux-hardware.org/?probe=ad60cd6e18) | Oct 06, 2023 |
| ASUSTek       | B85-PRO GAMER               | [10baa7a046](https://linux-hardware.org/?probe=10baa7a046) | Oct 06, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f68374e7cd](https://linux-hardware.org/?probe=f68374e7cd) | Oct 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cbf93da8d0](https://linux-hardware.org/?probe=cbf93da8d0) | Oct 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | [573f1da6a9](https://linux-hardware.org/?probe=573f1da6a9) | Oct 03, 2023 |
| Gigabyte      | X570S UD                    | [5d8ef7c003](https://linux-hardware.org/?probe=5d8ef7c003) | Oct 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2e1316fb48](https://linux-hardware.org/?probe=2e1316fb48) | Oct 03, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [6a2fa93249](https://linux-hardware.org/?probe=6a2fa93249) | Oct 03, 2023 |
| Gigabyte      | B365M DS3H                  | [c9a7b94ace](https://linux-hardware.org/?probe=c9a7b94ace) | Oct 03, 2023 |
| MSI           | B560M PRO                   | [1312550a66](https://linux-hardware.org/?probe=1312550a66) | Oct 02, 2023 |
| ASRock        | B450 Gaming K4              | [8311d775a9](https://linux-hardware.org/?probe=8311d775a9) | Oct 01, 2023 |
| MSI           | B560M PRO                   | [1dc06a927c](https://linux-hardware.org/?probe=1dc06a927c) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| MSI           | B560M PRO                   | [ce2f5b7349](https://linux-hardware.org/?probe=ce2f5b7349) | Sep 29, 2023 |
| Gigabyte      | H610M S2H DDR4              | [9d767beb12](https://linux-hardware.org/?probe=9d767beb12) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [7ed50e5e43](https://linux-hardware.org/?probe=7ed50e5e43) | Sep 27, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7cfa1007ee](https://linux-hardware.org/?probe=7cfa1007ee) | Sep 27, 2023 |
| Gigabyte      | H61MA-D3V                   | [a9c8158139](https://linux-hardware.org/?probe=a9c8158139) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [65369ae480](https://linux-hardware.org/?probe=65369ae480) | Sep 25, 2023 |
| HP            | 8949 11                     | [acb62cff2b](https://linux-hardware.org/?probe=acb62cff2b) | Sep 25, 2023 |
| ASUSTek       | P5G41T-M LX3                | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [fbeac0cab4](https://linux-hardware.org/?probe=fbeac0cab4) | Sep 23, 2023 |
| HP            | 8055                        | [d8ea4bc33a](https://linux-hardware.org/?probe=d8ea4bc33a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [537e551c45](https://linux-hardware.org/?probe=537e551c45) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [a9f9ccb4f9](https://linux-hardware.org/?probe=a9f9ccb4f9) | Sep 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [c2c49834e5](https://linux-hardware.org/?probe=c2c49834e5) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [8b39e51416](https://linux-hardware.org/?probe=8b39e51416) | Sep 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [816502caea](https://linux-hardware.org/?probe=816502caea) | Sep 21, 2023 |
| Dell          | 00V62H A00                  | [66262df4c4](https://linux-hardware.org/?probe=66262df4c4) | Sep 21, 2023 |
| ASRock        | A320M-HD                    | [01d8f27500](https://linux-hardware.org/?probe=01d8f27500) | Sep 20, 2023 |
| HP            | 212B                        | [1d71ef5e64](https://linux-hardware.org/?probe=1d71ef5e64) | Sep 19, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [6088e9b2fa](https://linux-hardware.org/?probe=6088e9b2fa) | Sep 19, 2023 |
| HP            | 3047h                       | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| Gigabyte      | B450M S2H                   | [75f2d2b31d](https://linux-hardware.org/?probe=75f2d2b31d) | Sep 18, 2023 |
| ASRock        | B450M-HDV R4.0              | [e517de2d8f](https://linux-hardware.org/?probe=e517de2d8f) | Sep 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [78535377d6](https://linux-hardware.org/?probe=78535377d6) | Sep 18, 2023 |
| HP            | 212B                        | [a041c8b5a9](https://linux-hardware.org/?probe=a041c8b5a9) | Sep 17, 2023 |
| ASRock        | B450 Gaming K4              | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| ASUSTek       | B85M-G                      | [1398fa87b2](https://linux-hardware.org/?probe=1398fa87b2) | Sep 17, 2023 |
| ASRock        | A320M-HD                    | [8db77afc82](https://linux-hardware.org/?probe=8db77afc82) | Sep 17, 2023 |
| HP            | 3647h                       | [89c406366a](https://linux-hardware.org/?probe=89c406366a) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [b7ff5a9cf2](https://linux-hardware.org/?probe=b7ff5a9cf2) | Sep 16, 2023 |
| Shenzhen M... | F7BSC                       | [a6d51b9c90](https://linux-hardware.org/?probe=a6d51b9c90) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [c40357b67a](https://linux-hardware.org/?probe=c40357b67a) | Sep 16, 2023 |
| Biostar       | X370GTN                     | [1ac44acadd](https://linux-hardware.org/?probe=1ac44acadd) | Sep 16, 2023 |
| MSI           | PRO B660M-B DDR4            | [9463a6f106](https://linux-hardware.org/?probe=9463a6f106) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | [43f6a3bfc1](https://linux-hardware.org/?probe=43f6a3bfc1) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | [dcd2b90824](https://linux-hardware.org/?probe=dcd2b90824) | Sep 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | [ba15fb6ed7](https://linux-hardware.org/?probe=ba15fb6ed7) | Sep 14, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7769de42b0](https://linux-hardware.org/?probe=7769de42b0) | Sep 13, 2023 |
| HP            | 0A60h                       | [107f849e6b](https://linux-hardware.org/?probe=107f849e6b) | Sep 13, 2023 |
| ASUSTek       | PRIME X570-P                | [c6f2b822c7](https://linux-hardware.org/?probe=c6f2b822c7) | Sep 12, 2023 |
| HP            | 870C                        | [3de222afdb](https://linux-hardware.org/?probe=3de222afdb) | Sep 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0ac203a0c5](https://linux-hardware.org/?probe=0ac203a0c5) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [793d3e47ff](https://linux-hardware.org/?probe=793d3e47ff) | Sep 10, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | [6e5224fa1d](https://linux-hardware.org/?probe=6e5224fa1d) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3f937bad2e](https://linux-hardware.org/?probe=3f937bad2e) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | [1474c70336](https://linux-hardware.org/?probe=1474c70336) | Sep 09, 2023 |
| HP            | 2B36                        | [20552523c6](https://linux-hardware.org/?probe=20552523c6) | Sep 08, 2023 |
| HP            | 339A                        | [4ba272aaf9](https://linux-hardware.org/?probe=4ba272aaf9) | Sep 08, 2023 |
| HP            | 2B36                        | [7697b6ff27](https://linux-hardware.org/?probe=7697b6ff27) | Sep 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [b5ea617856](https://linux-hardware.org/?probe=b5ea617856) | Sep 08, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [7cbd11709c](https://linux-hardware.org/?probe=7cbd11709c) | Sep 07, 2023 |
| MSI           | B360M GAMING PLUS           | [1faaa87b61](https://linux-hardware.org/?probe=1faaa87b61) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [9e7c97275d](https://linux-hardware.org/?probe=9e7c97275d) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [04d60f1b2d](https://linux-hardware.org/?probe=04d60f1b2d) | Sep 06, 2023 |
| MSI           | 2A9Ch                       | [68fe74d684](https://linux-hardware.org/?probe=68fe74d684) | Sep 06, 2023 |
| HP            | 1905                        | [e0da3a1a45](https://linux-hardware.org/?probe=e0da3a1a45) | Sep 06, 2023 |
| MSI           | B550-A PRO                  | [4a5a98638e](https://linux-hardware.org/?probe=4a5a98638e) | Sep 06, 2023 |
| ASRock        | Z690 PG Velocita            | [0064d9d9e2](https://linux-hardware.org/?probe=0064d9d9e2) | Sep 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [0f5597eb7e](https://linux-hardware.org/?probe=0f5597eb7e) | Sep 05, 2023 |
| MSI           | MS-B0A81                    | [2c4cc9e78f](https://linux-hardware.org/?probe=2c4cc9e78f) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [590b5224d9](https://linux-hardware.org/?probe=590b5224d9) | Sep 04, 2023 |
| ASRock        | Z790 Taichi Carrara         | [80f9f3915b](https://linux-hardware.org/?probe=80f9f3915b) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [908a64b09a](https://linux-hardware.org/?probe=908a64b09a) | Sep 04, 2023 |
| MSI           | B350M PRO-VDH               | [4ee783a52f](https://linux-hardware.org/?probe=4ee783a52f) | Sep 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | [49101faf53](https://linux-hardware.org/?probe=49101faf53) | Sep 02, 2023 |
| Biostar       | A320MH                      | [8791e4dd20](https://linux-hardware.org/?probe=8791e4dd20) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [a19ece12f0](https://linux-hardware.org/?probe=a19ece12f0) | Sep 01, 2023 |
| HP            | 82F1                        | [6fca2da71a](https://linux-hardware.org/?probe=6fca2da71a) | Sep 01, 2023 |
| ASRock        | B550M-ITX/ac                | [42eb5f3ad4](https://linux-hardware.org/?probe=42eb5f3ad4) | Aug 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [88b6c0365c](https://linux-hardware.org/?probe=88b6c0365c) | Aug 31, 2023 |
| ASUSTek       | PRIME B450M-A II            | [bec8171350](https://linux-hardware.org/?probe=bec8171350) | Aug 30, 2023 |
| Dell          | 07KY25 A00                  | [9346896df5](https://linux-hardware.org/?probe=9346896df5) | Aug 30, 2023 |
| Gigabyte      | P55-UD4                     | [071fa35482](https://linux-hardware.org/?probe=071fa35482) | Aug 29, 2023 |
| Intel         | DH61CR AAG14064-204         | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [85640356ad](https://linux-hardware.org/?probe=85640356ad) | Aug 28, 2023 |
| MSI           | 970A-G46                    | [5b4c3411dc](https://linux-hardware.org/?probe=5b4c3411dc) | Aug 28, 2023 |
| Gigabyte      | P55-UD4                     | [db36b0429d](https://linux-hardware.org/?probe=db36b0429d) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| ASRock        | X670E Steel Legend          | [c675cc9767](https://linux-hardware.org/?probe=c675cc9767) | Aug 27, 2023 |
| ASUSTek       | H61M-K                      | [9c34344e6d](https://linux-hardware.org/?probe=9c34344e6d) | Aug 26, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [2eb35196a6](https://linux-hardware.org/?probe=2eb35196a6) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [99448eedb6](https://linux-hardware.org/?probe=99448eedb6) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [50af29acb9](https://linux-hardware.org/?probe=50af29acb9) | Aug 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [28b621194b](https://linux-hardware.org/?probe=28b621194b) | Aug 18, 2023 |
| ASRock        | H61M-HG4                    | [6fbc46fea9](https://linux-hardware.org/?probe=6fbc46fea9) | Aug 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | [54a5786749](https://linux-hardware.org/?probe=54a5786749) | Aug 17, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [b63e7d3466](https://linux-hardware.org/?probe=b63e7d3466) | Aug 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c093ae6eb5](https://linux-hardware.org/?probe=c093ae6eb5) | Aug 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4907b10657](https://linux-hardware.org/?probe=4907b10657) | Aug 15, 2023 |
| ASRock        | B760M PG Riptide            | [0d11484b59](https://linux-hardware.org/?probe=0d11484b59) | Aug 15, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f4bcea527c](https://linux-hardware.org/?probe=f4bcea527c) | Aug 14, 2023 |
| ASUSTek       | G15CE                       | [a9ac3a3ce4](https://linux-hardware.org/?probe=a9ac3a3ce4) | Aug 13, 2023 |
| Dell          | 0TTDMJ A00                  | [e0c6e5b185](https://linux-hardware.org/?probe=e0c6e5b185) | Aug 13, 2023 |
| ASRock        | B550M Pro4                  | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| Dell          | 0NC2VH A01                  | [e39fddb92c](https://linux-hardware.org/?probe=e39fddb92c) | Aug 12, 2023 |
| Gigabyte      | B550 GAMING X V2            | [1f4aa5bf97](https://linux-hardware.org/?probe=1f4aa5bf97) | Aug 12, 2023 |
| Gigabyte      | M720-US3                    | [222bc02e4f](https://linux-hardware.org/?probe=222bc02e4f) | Aug 11, 2023 |
| HP            | 83E8                        | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Gigabyte      | X570S AERO G                | [22916d4c12](https://linux-hardware.org/?probe=22916d4c12) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [0521e62bf9](https://linux-hardware.org/?probe=0521e62bf9) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [198fcb1fc2](https://linux-hardware.org/?probe=198fcb1fc2) | Aug 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | [00bb870b78](https://linux-hardware.org/?probe=00bb870b78) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4a7cc2835f](https://linux-hardware.org/?probe=4a7cc2835f) | Aug 09, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [f50b51555f](https://linux-hardware.org/?probe=f50b51555f) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| Gigabyte      | B550M DS3H                  | [7889f62638](https://linux-hardware.org/?probe=7889f62638) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [121b892fa8](https://linux-hardware.org/?probe=121b892fa8) | Aug 08, 2023 |
| MSI           | B550-A PRO                  | [61c59e48d2](https://linux-hardware.org/?probe=61c59e48d2) | Aug 08, 2023 |
| AZW           | U59                         | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| Gigabyte      | F2A68HM-H                   | [4323af2ade](https://linux-hardware.org/?probe=4323af2ade) | Aug 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [230032816b](https://linux-hardware.org/?probe=230032816b) | Aug 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [97505d521e](https://linux-hardware.org/?probe=97505d521e) | Aug 06, 2023 |
| Gigabyte      | X570 GAMING X               | [34dc1bc754](https://linux-hardware.org/?probe=34dc1bc754) | Aug 06, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| HP            | 8055                        | [21c8e1fdc2](https://linux-hardware.org/?probe=21c8e1fdc2) | Aug 03, 2023 |
| ASRock        | B650M PG Riptide            | [2e309e76d7](https://linux-hardware.org/?probe=2e309e76d7) | Aug 03, 2023 |
| HP            | 2215                        | [f0589325fc](https://linux-hardware.org/?probe=f0589325fc) | Aug 03, 2023 |
| Unknown       | Unknown                     | [92f3b39535](https://linux-hardware.org/?probe=92f3b39535) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| ASUSTek       | P8Z77-V                     | [65dcccd422](https://linux-hardware.org/?probe=65dcccd422) | Jul 30, 2023 |
| MSI           | PRO X670-P WIFI             | [19b97459c1](https://linux-hardware.org/?probe=19b97459c1) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [c8116c748a](https://linux-hardware.org/?probe=c8116c748a) | Jul 29, 2023 |
| Dell          | 0PU052                      | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [06731541dd](https://linux-hardware.org/?probe=06731541dd) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| ASUSTek       | P8Z77-V                     | [e550626a11](https://linux-hardware.org/?probe=e550626a11) | Jul 27, 2023 |
| Gigabyte      | B360M HD3                   | [900f299e10](https://linux-hardware.org/?probe=900f299e10) | Jul 26, 2023 |
| ASRock        | X570 Pro4                   | [96dcaad094](https://linux-hardware.org/?probe=96dcaad094) | Jul 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| MSI           | ZH77A-G41                   | [8528da5360](https://linux-hardware.org/?probe=8528da5360) | Jul 24, 2023 |
| MSI           | PRO Z690-A WIFI             | [8f3dc1cb65](https://linux-hardware.org/?probe=8f3dc1cb65) | Jul 24, 2023 |
| ASUSTek       | P8Z77-V                     | [a8f7397fcf](https://linux-hardware.org/?probe=a8f7397fcf) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [6094ce5501](https://linux-hardware.org/?probe=6094ce5501) | Jul 23, 2023 |
| Gigabyte      | X570 GAMING X               | [b0e064a98a](https://linux-hardware.org/?probe=b0e064a98a) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| AMI           | Intel                       | [fe2999b2aa](https://linux-hardware.org/?probe=fe2999b2aa) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [42fc5ff144](https://linux-hardware.org/?probe=42fc5ff144) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [65972dbe80](https://linux-hardware.org/?probe=65972dbe80) | Jul 21, 2023 |
| ASRock        | B450 Pro4                   | [6df8743ac8](https://linux-hardware.org/?probe=6df8743ac8) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2dbb6f2466](https://linux-hardware.org/?probe=2dbb6f2466) | Jul 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | [3014bea7d8](https://linux-hardware.org/?probe=3014bea7d8) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [765ac65603](https://linux-hardware.org/?probe=765ac65603) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-P                | [e6bbbc4d41](https://linux-hardware.org/?probe=e6bbbc4d41) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3d605ad77f](https://linux-hardware.org/?probe=3d605ad77f) | Jul 19, 2023 |
| ASRock        | B450 Gaming K4              | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| HP            | 83E0                        | [35abf30fff](https://linux-hardware.org/?probe=35abf30fff) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [b8b0b27baf](https://linux-hardware.org/?probe=b8b0b27baf) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | [4092f45d41](https://linux-hardware.org/?probe=4092f45d41) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | [1ee27caac4](https://linux-hardware.org/?probe=1ee27caac4) | Jul 14, 2023 |
| HP            | 3397                        | [d20efc761c](https://linux-hardware.org/?probe=d20efc761c) | Jul 13, 2023 |
| ASRock        | B450 Gaming K4              | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| Dell          | 0T10XW A01                  | [51cf410b69](https://linux-hardware.org/?probe=51cf410b69) | Jul 12, 2023 |
| MSI           | X370 GAMING M7 ACK          | [e62935623d](https://linux-hardware.org/?probe=e62935623d) | Jul 12, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [611ea83c30](https://linux-hardware.org/?probe=611ea83c30) | Jul 11, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [8aadac9d4b](https://linux-hardware.org/?probe=8aadac9d4b) | Jul 11, 2023 |
| ASUSTek       | SABERTOOTH X99              | [1473d3cd3b](https://linux-hardware.org/?probe=1473d3cd3b) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V                     | [1e5cf5e071](https://linux-hardware.org/?probe=1e5cf5e071) | Jul 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Manjaro        | 1511     | 43.58%  |
| Manjaro 20.1   | 135      | 3.89%   |
| Manjaro 20.2.1 | 108      | 3.12%   |
| Manjaro 22.0.0 | 103      | 2.97%   |
| Manjaro 20.2   | 89       | 2.57%   |
| Manjaro 20.0.3 | 81       | 2.34%   |
| Manjaro 23.0.0 | 62       | 1.79%   |
| Manjaro 18.1.5 | 56       | 1.62%   |
| Manjaro 21.2.6 | 53       | 1.53%   |
| Manjaro 21.2.5 | 53       | 1.53%   |
| Manjaro 21.1.0 | 53       | 1.53%   |
| Manjaro 23.1.3 | 48       | 1.38%   |
| Manjaro 18.0.4 | 46       | 1.33%   |
| Manjaro 21.2.0 | 45       | 1.3%    |
| Manjaro 20.0   | 45       | 1.3%    |
| Manjaro 21.1.6 | 38       | 1.1%    |
| Manjaro 21.0.7 | 36       | 1.04%   |
| Manjaro 21.0.5 | 35       | 1.01%   |
| Manjaro 21.0   | 35       | 1.01%   |
| Manjaro 23.1.0 | 33       | 0.95%   |
| Manjaro 19.0.2 | 31       | 0.89%   |
| Manjaro 20.1.2 | 29       | 0.84%   |
| Manjaro 20.0.1 | 29       | 0.84%   |
| Manjaro 23.1.4 | 28       | 0.81%   |
| Manjaro 21.2.3 | 27       | 0.78%   |
| Manjaro 22.1.0 | 25       | 0.72%   |
| Manjaro 20.1.1 | 24       | 0.69%   |
| Manjaro 24.1.2 | 23       | 0.66%   |
| Manjaro 21.2.1 | 23       | 0.66%   |
| Manjaro 21.3.7 | 20       | 0.58%   |
| Manjaro 24.0.8 | 18       | 0.52%   |
| Manjaro 21.3.6 | 18       | 0.52%   |
| Manjaro 23.0.4 | 17       | 0.49%   |
| Manjaro 22.0.4 | 16       | 0.46%   |
| Manjaro 21.0.4 | 16       | 0.46%   |
| Manjaro 21.0.1 | 14       | 0.4%    |
| Manjaro 21.0.2 | 13       | 0.37%   |
| Manjaro 24.2.1 | 12       | 0.35%   |
| Manjaro 22.1.1 | 12       | 0.35%   |
| Manjaro 21.2rc | 12       | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 3171     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 115      | 2.92%   |
| 5.8.6-1-MANJARO   | 68       | 1.73%   |
| 5.13.19-2-MANJARO | 67       | 1.7%    |
| 5.9.11-3-MANJARO  | 48       | 1.22%   |
| 5.15.28-1-MANJARO | 48       | 1.22%   |
| 5.8.11-1-MANJARO  | 46       | 1.17%   |
| 5.10.42-1-MANJARO | 40       | 1.02%   |
| 6.10.13-3-MANJARO | 39       | 0.99%   |
| 6.1.1-1-MANJARO   | 38       | 0.97%   |
| 5.8.18-1-MANJARO  | 38       | 0.97%   |
| 6.5.5-1-MANJARO   | 34       | 0.86%   |
| 5.15.32-1-MANJARO | 33       | 0.84%   |
| 6.1.31-2-MANJARO  | 32       | 0.81%   |
| 6.1.12-1-MANJARO  | 32       | 0.81%   |
| 5.6.16-1-MANJARO  | 31       | 0.79%   |
| 6.9.12-3-MANJARO  | 30       | 0.76%   |
| 5.10.36-2-MANJARO | 30       | 0.76%   |
| 5.7.9-1-MANJARO   | 29       | 0.74%   |
| 5.15.60-1-MANJARO | 29       | 0.74%   |
| 6.6.19-1-MANJARO  | 28       | 0.71%   |
| 5.15.12-1-MANJARO | 28       | 0.71%   |
| 6.6.26-1-MANJARO  | 27       | 0.69%   |
| 6.6.10-1-MANJARO  | 27       | 0.69%   |
| 5.8.3-2-MANJARO   | 25       | 0.64%   |
| 5.8.16-2-MANJARO  | 25       | 0.64%   |
| 5.6.19-2-MANJARO  | 24       | 0.61%   |
| 5.6.15-1-MANJARO  | 24       | 0.61%   |
| 5.17.1-3-MANJARO  | 24       | 0.61%   |
| 5.7.0-3-MANJARO   | 23       | 0.58%   |
| 5.10.2-2-MANJARO  | 23       | 0.58%   |
| 5.6.7-1-MANJARO   | 22       | 0.56%   |
| 5.6.12-1-MANJARO  | 22       | 0.56%   |
| 5.16.14-1-MANJARO | 22       | 0.56%   |
| 5.15.2-2-MANJARO  | 22       | 0.56%   |
| 5.10.23-1-MANJARO | 22       | 0.56%   |
| 5.9.1-1-MANJARO   | 21       | 0.53%   |
| 5.11.6-1-MANJARO  | 21       | 0.53%   |
| 5.4.15-2-MANJARO  | 20       | 0.51%   |
| 6.12.4-1-MANJARO  | 19       | 0.48%   |
| 5.7.17-2-MANJARO  | 19       | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 115      | 2.93%   |
| 5.8.6   | 68       | 1.73%   |
| 5.13.19 | 67       | 1.71%   |
| 5.9.11  | 51       | 1.3%    |
| 5.15.28 | 48       | 1.22%   |
| 5.8.11  | 47       | 1.2%    |
| 5.10.42 | 40       | 1.02%   |
| 6.10.13 | 39       | 0.99%   |
| 6.1.1   | 38       | 0.97%   |
| 5.8.18  | 38       | 0.97%   |
| 6.5.5   | 35       | 0.89%   |
| 6.9.12  | 33       | 0.84%   |
| 6.1.31  | 33       | 0.84%   |
| 5.15.32 | 33       | 0.84%   |
| 6.1.12  | 32       | 0.81%   |
| 5.6.16  | 31       | 0.79%   |
| 5.10.36 | 30       | 0.76%   |
| 5.7.9   | 29       | 0.74%   |
| 5.7.0   | 29       | 0.74%   |
| 5.17.1  | 29       | 0.74%   |
| 5.15.60 | 29       | 0.74%   |
| 6.6.19  | 28       | 0.71%   |
| 6.6.10  | 28       | 0.71%   |
| 5.9.1   | 28       | 0.71%   |
| 5.15.12 | 28       | 0.71%   |
| 6.6.26  | 27       | 0.69%   |
| 5.6.19  | 27       | 0.69%   |
| 5.8.3   | 26       | 0.66%   |
| 6.5.13  | 25       | 0.64%   |
| 5.8.16  | 25       | 0.64%   |
| 5.6.15  | 24       | 0.61%   |
| 5.6.12  | 23       | 0.59%   |
| 5.15.2  | 23       | 0.59%   |
| 5.10.2  | 23       | 0.59%   |
| 5.6.7   | 22       | 0.56%   |
| 5.16.14 | 22       | 0.56%   |
| 5.10.23 | 22       | 0.56%   |
| 5.11.6  | 21       | 0.53%   |
| 5.7.17  | 20       | 0.51%   |
| 5.4.15  | 20       | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 463      | 12.69%  |
| 5.10    | 366      | 10.03%  |
| 6.1     | 290      | 7.95%   |
| 5.4     | 254      | 6.96%   |
| 5.9     | 230      | 6.3%    |
| 5.8     | 228      | 6.25%   |
| 6.6     | 204      | 5.59%   |
| 5.6     | 172      | 4.71%   |
| 5.13    | 128      | 3.51%   |
| 5.7     | 109      | 2.99%   |
| 6.5     | 107      | 2.93%   |
| 5.11    | 91       | 2.49%   |
| 6.9     | 75       | 2.06%   |
| 4.19    | 68       | 1.86%   |
| 5.17    | 65       | 1.78%   |
| 5.16    | 63       | 1.73%   |
| 6.0     | 62       | 1.7%    |
| 6.10    | 61       | 1.67%   |
| 5.14    | 61       | 1.67%   |
| 5.19    | 55       | 1.51%   |
| 5.18    | 55       | 1.51%   |
| 5.12    | 49       | 1.34%   |
| 6.11    | 42       | 1.15%   |
| 6.7     | 39       | 1.07%   |
| 6.3     | 39       | 1.07%   |
| 6.2     | 39       | 1.07%   |
| 5.5     | 39       | 1.07%   |
| 4.14    | 32       | 0.88%   |
| 6.4     | 27       | 0.74%   |
| 6.8     | 25       | 0.69%   |
| 6.12    | 23       | 0.63%   |
| 5.3     | 23       | 0.63%   |
| 5.2     | 17       | 0.47%   |
| 5.1     | 13       | 0.36%   |
| 5.0     | 11       | 0.3%    |
| 4.20    | 5        | 0.14%   |
| 4.18    | 5        | 0.14%   |
| 4.17    | 3        | 0.08%   |
| 4.16    | 3        | 0.08%   |
| 4.9     | 2        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3171     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 1265     | 37.99%  |
| XFCE                     | 656      | 19.7%   |
| GNOME                    | 604      | 18.14%  |
| KDE                      | 252      | 7.57%   |
| KDE6                     | 168      | 5.05%   |
| Unknown                  | 114      | 3.42%   |
| X-Cinnamon               | 98       | 2.94%   |
| i3                       | 50       | 1.5%    |
| MATE                     | 27       | 0.81%   |
| Cinnamon                 | 23       | 0.69%   |
| Deepin                   | 22       | 0.66%   |
| Budgie                   | 15       | 0.45%   |
| LXQt                     | 8        | 0.24%   |
| awesome                  | 6        | 0.18%   |
| sway                     | 5        | 0.15%   |
| GNOME Classic            | 4        | 0.12%   |
| Bspwm                    | 3        | 0.09%   |
| ICEWM                    | 2        | 0.06%   |
| Yaru:ubuntu:GNOME        | 1        | 0.03%   |
| qtile                    | 1        | 0.03%   |
| openbox                  | 1        | 0.03%   |
| LXDE                     | 1        | 0.03%   |
| Hyprland                 | 1        | 0.03%   |
| Enlightenment            | 1        | 0.03%   |
| DWM                      | 1        | 0.03%   |
| /usr/bin/openbox-session | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2809     | 86.59%  |
| Wayland | 348      | 10.73%  |
| Unknown | 57       | 1.76%   |
| Tty     | 30       | 0.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1508     | 46.12%  |
| SDDM    | 814      | 24.89%  |
| LightDM | 515      | 15.75%  |
| GDM     | 332      | 10.15%  |
| TDM     | 89       | 2.72%   |
| LXDM    | 5        | 0.15%   |
| GREETD  | 3        | 0.09%   |
| SLiM    | 2        | 0.06%   |
| XDM     | 1        | 0.03%   |
| LYNDE   | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1261     | 39.16%  |
| de_DE   | 279      | 8.66%   |
| ru_RU   | 246      | 7.64%   |
| en_GB   | 215      | 6.68%   |
| Unknown | 161      | 5%      |
| pt_BR   | 145      | 4.5%    |
| fr_FR   | 97       | 3.01%   |
| en_CA   | 90       | 2.8%    |
| it_IT   | 87       | 2.7%    |
| es_ES   | 77       | 2.39%   |
| pl_PL   | 56       | 1.74%   |
| en_AU   | 48       | 1.49%   |
| de_AT   | 24       | 0.75%   |
| es_MX   | 23       | 0.71%   |
| es_AR   | 23       | 0.71%   |
| nl_NL   | 22       | 0.68%   |
| en_IN   | 22       | 0.68%   |
| zh_CN   | 19       | 0.59%   |
| ru_UA   | 18       | 0.56%   |
| fi_FI   | 16       | 0.5%    |
| sv_SE   | 15       | 0.47%   |
| hu_HU   | 14       | 0.43%   |
| fr_CA   | 14       | 0.43%   |
| en_PH   | 13       | 0.4%    |
| en_ZA   | 12       | 0.37%   |
| en_IE   | 12       | 0.37%   |
| cs_CZ   | 11       | 0.34%   |
| tr_TR   | 9        | 0.28%   |
| ja_JP   | 9        | 0.28%   |
| es_CL   | 9        | 0.28%   |
| en_NZ   | 9        | 0.28%   |
| en_DK   | 9        | 0.28%   |
| de_CH   | 9        | 0.28%   |
| da_DK   | 9        | 0.28%   |
| pt_PT   | 8        | 0.25%   |
| es_UY   | 7        | 0.22%   |
| uk_UA   | 6        | 0.19%   |
| fr_BE   | 6        | 0.19%   |
| en_IL   | 6        | 0.19%   |
| el_GR   | 6        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2047     | 63.18%  |
| EFI  | 1193     | 36.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 2635     | 81.23%  |
| Btrfs    | 382      | 11.78%  |
| Tmpfs    | 73       | 2.25%   |
| Xfs      | 51       | 1.57%   |
| Unknown  | 40       | 1.23%   |
| Overlay  | 38       | 1.17%   |
| F2fs     | 13       | 0.4%    |
| Zfs      | 4        | 0.12%   |
| Ext2     | 3        | 0.09%   |
| Ext3     | 2        | 0.06%   |
| XXXX     | 1        | 0.03%   |
| XXXfs    | 1        | 0.03%   |
| Reiserfs | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1594     | 48.97%  |
| GPT     | 1363     | 41.87%  |
| MBR     | 298      | 9.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2692     | 83.09%  |
| Yes       | 548      | 16.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2112     | 65.29%  |
| Yes       | 1123     | 34.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 929      | 29.3%   |
| Gigabyte Technology                  | 646      | 20.37%  |
| MSI                                  | 521      | 16.43%  |
| ASRock                               | 343      | 10.82%  |
| Dell                                 | 168      | 5.3%    |
| Hewlett-Packard                      | 166      | 5.23%   |
| Intel                                | 73       | 2.3%    |
| Lenovo                               | 68       | 2.14%   |
| Acer                                 | 29       | 0.91%   |
| Unknown                              | 27       | 0.85%   |
| Biostar                              | 24       | 0.76%   |
| Pegatron                             | 16       | 0.5%    |
| Huanan                               | 16       | 0.5%    |
| Foxconn                              | 12       | 0.38%   |
| Apple                                | 12       | 0.38%   |
| Medion                               | 9        | 0.28%   |
| Fujitsu                              | 9        | 0.28%   |
| ECS                                  | 8        | 0.25%   |
| AZW                                  | 7        | 0.22%   |
| Shuttle                              | 5        | 0.16%   |
| Shenzhen Meigao Electronic Equipment | 5        | 0.16%   |
| Positivo                             | 5        | 0.16%   |
| BESSTAR Tech                         | 5        | 0.16%   |
| Alienware                            | 5        | 0.16%   |
| PCWare                               | 4        | 0.13%   |
| OEM                                  | 3        | 0.09%   |
| ZOTAC                                | 2        | 0.06%   |
| Minix                                | 2        | 0.06%   |
| MACHINIST                            | 2        | 0.06%   |
| Inventec                             | 2        | 0.06%   |
| Google                               | 2        | 0.06%   |
| GEEKOM                               | 2        | 0.06%   |
| Gateway                              | 2        | 0.06%   |
| Fujitsu Siemens                      | 2        | 0.06%   |
| EVGA                                 | 2        | 0.06%   |
| AMI                                  | 2        | 0.06%   |
| Acidanthera                          | 2        | 0.06%   |
| XFX                                  | 1        | 0.03%   |
| VS Company                           | 1        | 0.03%   |
| TYAN Computer                        | 1        | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 86       | 2.71%   |
| MSI MS-7C37                      | 36       | 1.14%   |
| Gigabyte B450M DS3H              | 32       | 1.01%   |
| MSI MS-7C02                      | 31       | 0.98%   |
| Unknown                          | 30       | 0.95%   |
| ASUS TUF Gaming X570-PLUS        | 27       | 0.85%   |
| MSI MS-7C91                      | 26       | 0.82%   |
| ASUS PRIME A320M-K               | 24       | 0.76%   |
| MSI MS-7B86                      | 19       | 0.6%    |
| ASRock B450M Pro4                | 19       | 0.6%    |
| MSI MS-7A38                      | 17       | 0.54%   |
| ASUS ROG STRIX B550-F GAMING     | 17       | 0.54%   |
| MSI MS-7B79                      | 16       | 0.5%    |
| Gigabyte X570 AORUS ELITE        | 16       | 0.5%    |
| Dell OptiPlex 9020               | 16       | 0.5%    |
| ASUS TUF Gaming B550M-PLUS       | 16       | 0.5%    |
| Dell OptiPlex 7010               | 15       | 0.47%   |
| ASUS ROG STRIX B450-F GAMING     | 15       | 0.47%   |
| ASUS PRIME B450M-A               | 15       | 0.47%   |
| Gigabyte B450 AORUS M            | 13       | 0.41%   |
| Gigabyte B450 AORUS ELITE        | 13       | 0.41%   |
| ASUS PRIME B350-PLUS             | 13       | 0.41%   |
| ASUS ROG STRIX X570-E GAMING     | 12       | 0.38%   |
| MSI MS-7B89                      | 11       | 0.35%   |
| MSI MS-7693                      | 11       | 0.35%   |
| Gigabyte X470 AORUS ULTRA GAMING | 11       | 0.35%   |
| Gigabyte 970A-DS3P               | 11       | 0.35%   |
| ASUS ROG CROSSHAIR VIII HERO     | 11       | 0.35%   |
| ASUS PRIME X470-PRO              | 11       | 0.35%   |
| ASUS PRIME X370-PRO              | 11       | 0.35%   |
| ASUS PRIME B450-PLUS             | 11       | 0.35%   |
| MSI MS-7C95                      | 10       | 0.32%   |
| MSI MS-7C94                      | 10       | 0.32%   |
| Gigabyte X570 AORUS MASTER       | 10       | 0.32%   |
| ASRock B450 Pro4                 | 10       | 0.32%   |
| MSI MS-7C84                      | 9        | 0.28%   |
| MSI MS-7C56                      | 9        | 0.28%   |
| MSI MS-7817                      | 9        | 0.28%   |
| ASUS TUF Gaming B550-PLUS        | 9        | 0.28%   |
| ASUS M5A97 R2.0                  | 9        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 211      | 6.65%   |
| ASUS ROG            | 179      | 5.64%   |
| ASUS TUF            | 109      | 3.44%   |
| Dell OptiPlex       | 105      | 3.31%   |
| ASUS All            | 86       | 2.71%   |
| Gigabyte X570       | 57       | 1.8%    |
| Gigabyte B450M      | 50       | 1.58%   |
| HP Compaq           | 45       | 1.42%   |
| Gigabyte B450       | 42       | 1.32%   |
| MSI MS-7C37         | 36       | 1.14%   |
| ASRock B450M        | 33       | 1.04%   |
| MSI MS-7C02         | 31       | 0.98%   |
| Lenovo ThinkCentre  | 31       | 0.98%   |
| Gigabyte B550       | 30       | 0.95%   |
| Unknown             | 30       | 0.95%   |
| HP EliteDesk        | 29       | 0.91%   |
| Dell Precision      | 29       | 0.91%   |
| MSI MS-7C91         | 26       | 0.82%   |
| ASRock X570         | 22       | 0.69%   |
| ASRock B450         | 21       | 0.66%   |
| ASUS M5A78L-M       | 20       | 0.63%   |
| MSI MS-7B86         | 19       | 0.6%    |
| ASUS M5A97          | 19       | 0.6%    |
| MSI MS-7A38         | 17       | 0.54%   |
| Gigabyte B550M      | 17       | 0.54%   |
| Acer Aspire         | 17       | 0.54%   |
| MSI MS-7B79         | 16       | 0.5%    |
| Gigabyte Z390       | 16       | 0.5%    |
| ASUS P8Z77-V        | 16       | 0.5%    |
| ASUS Maximus        | 15       | 0.47%   |
| HP ProDesk          | 13       | 0.41%   |
| Gigabyte X470       | 13       | 0.41%   |
| ASUS P8H61-M        | 13       | 0.41%   |
| ASRock B550M        | 13       | 0.41%   |
| Gigabyte 970A-DS3P  | 12       | 0.38%   |
| MSI MS-7B89         | 11       | 0.35%   |
| MSI MS-7693         | 11       | 0.35%   |
| Lenovo ThinkStation | 11       | 0.35%   |
| HP Pavilion         | 11       | 0.35%   |
| ASRock AB350        | 11       | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 479      | 15.11%  |
| 2019    | 376      | 11.86%  |
| 2020    | 348      | 10.97%  |
| 2012    | 259      | 8.17%   |
| 2017    | 253      | 7.98%   |
| 2013    | 206      | 6.5%    |
| 2014    | 192      | 6.05%   |
| 2011    | 162      | 5.11%   |
| 2021    | 148      | 4.67%   |
| 2016    | 136      | 4.29%   |
| 2015    | 124      | 3.91%   |
| 2022    | 109      | 3.44%   |
| 2010    | 106      | 3.34%   |
| 2009    | 90       | 2.84%   |
| 2008    | 50       | 1.58%   |
| 2007    | 49       | 1.55%   |
| 2023    | 44       | 1.39%   |
| 2024    | 20       | 0.63%   |
| 2006    | 15       | 0.47%   |
| 2005    | 4        | 0.13%   |
| Unknown | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3171     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3169     | 99.91%  |
| Enabled  | 3        | 0.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3169     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1112     | 34.31%  |
| 32.01-64.0      | 733      | 22.62%  |
| 8.01-16.0       | 540      | 16.66%  |
| 4.01-8.0        | 287      | 8.86%   |
| 64.01-256.0     | 208      | 6.42%   |
| 3.01-4.0        | 192      | 5.92%   |
| 24.01-32.0      | 130      | 4.01%   |
| 1.01-2.0        | 31       | 0.96%   |
| 2.01-3.0        | 7        | 0.22%   |
| More than 256.0 | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1001     | 27.54%  |
| 2.01-3.0    | 776      | 21.35%  |
| 1.01-2.0    | 727      | 20%     |
| 3.01-4.0    | 607      | 16.7%   |
| 8.01-16.0   | 335      | 9.22%   |
| 0.51-1.0    | 81       | 2.23%   |
| 16.01-24.0  | 64       | 1.76%   |
| 24.01-32.0  | 17       | 0.47%   |
| 32.01-64.0  | 15       | 0.41%   |
| 0.01-0.5    | 11       | 0.3%    |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 998      | 29.77%  |
| 1      | 777      | 23.18%  |
| 3      | 694      | 20.7%   |
| 4      | 436      | 13.01%  |
| 5      | 243      | 7.25%   |
| 6      | 100      | 2.98%   |
| 7      | 46       | 1.37%   |
| 8      | 22       | 0.66%   |
| 0      | 12       | 0.36%   |
| 9      | 11       | 0.33%   |
| 11     | 5        | 0.15%   |
| 12     | 3        | 0.09%   |
| 10     | 3        | 0.09%   |
| 27     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2169     | 67.42%  |
| Yes       | 1048     | 32.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3134     | 98.83%  |
| No        | 37       | 1.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1689     | 52.27%  |
| Yes       | 1542     | 47.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1830     | 56.64%  |
| Yes       | 1401     | 43.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 623      | 19.51%  |
| Germany      | 386      | 12.09%  |
| Russia       | 287      | 8.99%   |
| Brazil       | 198      | 6.2%    |
| Canada       | 133      | 4.16%   |
| France       | 121      | 3.79%   |
| Italy        | 111      | 3.48%   |
| UK           | 109      | 3.41%   |
| Spain        | 102      | 3.19%   |
| Poland       | 89       | 2.79%   |
| Netherlands  | 58       | 1.82%   |
| Ukraine      | 55       | 1.72%   |
| Sweden       | 51       | 1.6%    |
| Australia    | 51       | 1.6%    |
| Austria      | 43       | 1.35%   |
| Finland      | 37       | 1.16%   |
| Argentina    | 36       | 1.13%   |
| Mexico       | 32       | 1%      |
| Belgium      | 27       | 0.85%   |
| Switzerland  | 26       | 0.81%   |
| India        | 26       | 0.81%   |
| Hungary      | 26       | 0.81%   |
| Greece       | 26       | 0.81%   |
| Romania      | 25       | 0.78%   |
| Denmark      | 24       | 0.75%   |
| Bulgaria     | 23       | 0.72%   |
| Portugal     | 22       | 0.69%   |
| Norway       | 22       | 0.69%   |
| South Africa | 19       | 0.59%   |
| Turkey       | 17       | 0.53%   |
| Czechia      | 17       | 0.53%   |
| Belarus      | 16       | 0.5%    |
| China        | 15       | 0.47%   |
| Israel       | 14       | 0.44%   |
| Philippines  | 13       | 0.41%   |
| Chile        | 13       | 0.41%   |
| New Zealand  | 12       | 0.38%   |
| Japan        | 12       | 0.38%   |
| Lithuania    | 11       | 0.34%   |
| Bangladesh   | 11       | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 72       | 2.12%   |
| St Petersburg     | 30       | 0.88%   |
| Warsaw            | 23       | 0.68%   |
| Berlin            | 22       | 0.65%   |
| Toronto           | 20       | 0.59%   |
| Vienna            | 19       | 0.56%   |
| Sao Paulo         | 19       | 0.56%   |
| Sydney            | 17       | 0.5%    |
| Kyiv              | 17       | 0.5%    |
| Madrid            | 16       | 0.47%   |
| Athens            | 16       | 0.47%   |
| Amsterdam         | 16       | 0.47%   |
| Rome              | 15       | 0.44%   |
| Portland          | 15       | 0.44%   |
| Paris             | 15       | 0.44%   |
| Milan             | 15       | 0.44%   |
| Stockholm         | 14       | 0.41%   |
| Hamburg           | 14       | 0.41%   |
| Rio de Janeiro    | 13       | 0.38%   |
| Helsinki          | 13       | 0.38%   |
| Frankfurt am Main | 13       | 0.38%   |
| Barcelona         | 13       | 0.38%   |
| Dallas            | 11       | 0.32%   |
| Austin            | 11       | 0.32%   |
| Stuttgart         | 10       | 0.29%   |
| Sofia             | 10       | 0.29%   |
| Montreal          | 10       | 0.29%   |
| Melbourne         | 10       | 0.29%   |
| Krakow            | 10       | 0.29%   |
| Copenhagen        | 10       | 0.29%   |
| Bucharest         | 10       | 0.29%   |
| Yekaterinburg     | 9        | 0.27%   |
| Seattle           | 9        | 0.27%   |
| New York          | 9        | 0.27%   |
| Munich            | 9        | 0.27%   |
| Minsk             | 9        | 0.27%   |
| Miami             | 9        | 0.27%   |
| Mexico City       | 9        | 0.27%   |
| London            | 9        | 0.27%   |
| Indianapolis      | 9        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 1186     | 2056   | 16.87%  |
| Seagate                     | 1166     | 1940   | 16.58%  |
| Samsung Electronics         | 1153     | 2105   | 16.4%   |
| Kingston                    | 448      | 639    | 6.37%   |
| Sandisk                     | 383      | 542    | 5.45%   |
| Crucial                     | 368      | 561    | 5.23%   |
| Toshiba                     | 366      | 524    | 5.2%    |
| Hitachi                     | 165      | 238    | 2.35%   |
| Intel                       | 141      | 197    | 2.01%   |
| A-DATA Technology           | 109      | 157    | 1.55%   |
| Phison                      | 87       | 116    | 1.24%   |
| Phison Electronics          | 81       | 98     | 1.15%   |
| HGST                        | 75       | 114    | 1.07%   |
| Micron/Crucial Technology   | 74       | 95     | 1.05%   |
| China                       | 74       | 108    | 1.05%   |
| Silicon Motion              | 60       | 82     | 0.85%   |
| PNY                         | 54       | 82     | 0.77%   |
| Unknown                     | 48       | 109    | 0.68%   |
| SPCC                        | 47       | 59     | 0.67%   |
| Patriot                     | 44       | 64     | 0.63%   |
| OCZ                         | 42       | 58     | 0.6%    |
| SK hynix                    | 41       | 48     | 0.58%   |
| Intenso                     | 41       | 63     | 0.58%   |
| Micron Technology           | 37       | 46     | 0.53%   |
| XPG                         | 33       | 37     | 0.47%   |
| Realtek Semiconductor       | 33       | 40     | 0.47%   |
| Kingston Technology Company | 33       | 39     | 0.47%   |
| Corsair                     | 30       | 41     | 0.43%   |
| ADATA Technology            | 29       | 42     | 0.41%   |
| Transcend                   | 28       | 29     | 0.4%    |
| JMicron Technology          | 28       | 36     | 0.4%    |
| Team                        | 25       | 32     | 0.36%   |
| Lexar                       | 25       | 31     | 0.36%   |
| Plextor                     | 21       | 25     | 0.3%    |
| GOODRAM                     | 21       | 37     | 0.3%    |
| MAXIO Technology (Hangzhou) | 20       | 29     | 0.28%   |
| Apacer                      | 19       | 21     | 0.27%   |
| Maxtor                      | 18       | 22     | 0.26%   |
| Gigabyte Technology         | 17       | 29     | 0.24%   |
| Hewlett-Packard             | 15       | 19     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                      | 111      | 1.32%   |
| Samsung SSD 860 EVO 500GB                            | 106      | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB                       | 98       | 1.16%   |
| Seagate ST2000DM008-2FR102 2TB                       | 94       | 1.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 93       | 1.11%   |
| Samsung SSD 850 EVO 500GB                            | 75       | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 74       | 0.88%   |
| Samsung SSD 850 EVO 250GB                            | 73       | 0.87%   |
| Toshiba DT01ACA100 1TB                               | 67       | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB                             | 66       | 0.78%   |
| Crucial CT500MX500SSD1 500GB                         | 65       | 0.77%   |
| Samsung NVMe SSD Drive 500GB                         | 63       | 0.75%   |
| Kingston SA400S37120G 120GB SSD                      | 63       | 0.75%   |
| Samsung SSD 860 EVO 1TB                              | 60       | 0.71%   |
| Kingston SA400S37480G 480GB SSD                      | 58       | 0.69%   |
| Crucial CT1000MX500SSD1 1TB                          | 55       | 0.65%   |
| Seagate ST500DM002-1BD142 500GB                      | 54       | 0.64%   |
| Samsung NVMe SSD Drive 1TB                           | 49       | 0.58%   |
| Crucial CT240BX500SSD1 240GB                         | 49       | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB                       | 46       | 0.55%   |
| Toshiba HDWD110 1TB                                  | 45       | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                       | 45       | 0.53%   |
| Samsung SSD 860 EVO 250GB                            | 44       | 0.52%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 42       | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB                       | 42       | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB                       | 38       | 0.45%   |
| Samsung SSD 980 1TB                                  | 38       | 0.45%   |
| Seagate ST3500418AS 500GB                            | 37       | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB                       | 36       | 0.43%   |
| Toshiba DT01ACA200 2TB                               | 33       | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                     | 33       | 0.39%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 32       | 0.38%   |
| Seagate Expansion 1TB                                | 31       | 0.37%   |
| SanDisk NVMe SSD Drive 500GB                         | 31       | 0.37%   |
| Phison E12 NVMe Controller 480GB                     | 31       | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 30       | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 29       | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 29       | 0.34%   |
| Toshiba DT01ACA050 500GB                             | 29       | 0.34%   |
| Seagate ST31000524AS 1TB                             | 29       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1142     | 1885   | 37.5%   |
| WDC                 | 1053     | 1767   | 34.58%  |
| Toshiba             | 325      | 460    | 10.67%  |
| Hitachi             | 165      | 238    | 5.42%   |
| Samsung Electronics | 155      | 243    | 5.09%   |
| HGST                | 73       | 112    | 2.4%    |
| Unknown             | 19       | 31     | 0.62%   |
| Maxtor              | 17       | 19     | 0.56%   |
| JMicron Technology  | 16       | 20     | 0.53%   |
| ASMT                | 12       | 16     | 0.39%   |
| Fujitsu             | 10       | 23     | 0.33%   |
| SABRENT             | 9        | 9      | 0.3%    |
| Intenso             | 7        | 15     | 0.23%   |
| Hewlett-Packard     | 5        | 5      | 0.16%   |
| Apple               | 5        | 8      | 0.16%   |
| TO Exter            | 4        | 5      | 0.13%   |
| External            | 4        | 5      | 0.13%   |
| MaxDigital          | 3        | 3      | 0.1%    |
| HGST HTS            | 3        | 3      | 0.1%    |
| ASMedia             | 3        | 3      | 0.1%    |
| USB                 | 2        | 2      | 0.07%   |
| StoreJet            | 2        | 3      | 0.07%   |
| Maxone              | 2        | 3      | 0.07%   |
| USB3.0              | 1        | 1      | 0.03%   |
| TPH01204000GB       | 1        | 1      | 0.03%   |
| Lenovo              | 1        | 1      | 0.03%   |
| Initio              | 1        | 1      | 0.03%   |
| IBM/Hitachi         | 1        | 1      | 0.03%   |
| IBM-ESXS            | 1        | 2      | 0.03%   |
| IB-377U3            | 1        | 1      | 0.03%   |
| HPE                 | 1        | 1      | 0.03%   |
| Unknown             | 1        | 2      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 678      | 1052   | 25.75%  |
| Kingston            | 380      | 524    | 14.43%  |
| Crucial             | 341      | 525    | 12.95%  |
| SanDisk             | 212      | 275    | 8.05%   |
| WDC                 | 168      | 241    | 6.38%   |
| A-DATA Technology   | 95       | 138    | 3.61%   |
| China               | 74       | 108    | 2.81%   |
| Intel               | 62       | 82     | 2.35%   |
| PNY                 | 49       | 77     | 1.86%   |
| Patriot             | 42       | 62     | 1.6%    |
| OCZ                 | 42       | 58     | 1.6%    |
| SPCC                | 41       | 53     | 1.56%   |
| Toshiba             | 30       | 42     | 1.14%   |
| Lexar               | 25       | 31     | 0.95%   |
| Intenso             | 25       | 37     | 0.95%   |
| Transcend           | 23       | 24     | 0.87%   |
| Corsair             | 22       | 31     | 0.84%   |
| Team                | 21       | 28     | 0.8%    |
| GOODRAM             | 20       | 36     | 0.76%   |
| Plextor             | 19       | 23     | 0.72%   |
| Micron Technology   | 19       | 22     | 0.72%   |
| Apacer              | 19       | 21     | 0.72%   |
| SK hynix            | 15       | 16     | 0.57%   |
| Gigabyte Technology | 15       | 22     | 0.57%   |
| Seagate             | 12       | 15     | 0.46%   |
| Leven               | 10       | 10     | 0.38%   |
| KingSpec            | 10       | 12     | 0.38%   |
| KingDian            | 10       | 10     | 0.38%   |
| LITEONIT            | 8        | 12     | 0.3%    |
| LITEON              | 6        | 10     | 0.23%   |
| Apple               | 6        | 6      | 0.23%   |
| Unknown             | 6        | 6      | 0.23%   |
| Netac               | 5        | 7      | 0.19%   |
| Hewlett-Packard     | 5        | 6      | 0.19%   |
| Verbatim            | 4        | 5      | 0.15%   |
| USB3.0              | 4        | 4      | 0.15%   |
| NGFF                | 4        | 4      | 0.15%   |
| Mushkin             | 4        | 4      | 0.15%   |
| Kingmax             | 4        | 5      | 0.15%   |
| Hoodisk             | 4        | 5      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2216     | 4889   | 39.07%  |
| SSD     | 2037     | 3778   | 35.91%  |
| NVMe    | 1303     | 2212   | 22.97%  |
| Unknown | 110      | 179    | 1.94%   |
| MMC     | 6        | 6      | 0.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2869     | 8330   | 64.2%   |
| NVMe | 1301     | 2199   | 29.11%  |
| SAS  | 293      | 529    | 6.56%   |
| MMC  | 6        | 6      | 0.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2112     | 4138   | 43.53%  |
| 0.51-1.0   | 1486     | 2520   | 30.63%  |
| 1.01-2.0   | 678      | 1031   | 13.97%  |
| 3.01-4.0   | 239      | 387    | 4.93%   |
| 2.01-3.0   | 157      | 252    | 3.24%   |
| 4.01-10.0  | 150      | 279    | 3.09%   |
| 10.01-20.0 | 30       | 60     | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 578      | 17.02%  |
| 1001-2000      | 577      | 16.99%  |
| 251-500        | 566      | 16.67%  |
| 101-250        | 554      | 16.31%  |
| More than 3000 | 515      | 15.16%  |
| 2001-3000      | 291      | 8.57%   |
| Unknown        | 119      | 3.5%    |
| 51-100         | 113      | 3.33%   |
| 1-20           | 46       | 1.35%   |
| 21-50          | 37       | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 539      | 15.22%  |
| 1-20           | 483      | 13.64%  |
| 501-1000       | 468      | 13.21%  |
| 251-500        | 444      | 12.54%  |
| 21-50          | 424      | 11.97%  |
| 51-100         | 367      | 10.36%  |
| 1001-2000      | 350      | 9.88%   |
| More than 3000 | 212      | 5.99%   |
| 2001-3000      | 135      | 3.81%   |
| Unknown        | 119      | 3.36%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                                 | 9        | 12     | 2.26%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 6        | 8      | 1.51%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 6        | 6      | 1.51%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 6        | 6      | 1.51%   |
| Samsung Electronics HD103SJ 1TB                                 | 6        | 6      | 1.51%   |
| Hitachi HDS721010CLA332 1TB                                     | 5        | 5      | 1.26%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 4        | 4      | 1.01%   |
| Seagate ST3500413AS 500GB                                       | 4        | 5      | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 4        | 4      | 1.01%   |
| Seagate ST1000DX001-1CM162 1TB                                  | 4        | 6      | 1.01%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 4        | 6      | 1.01%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 4        | 5      | 1.01%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 4        | 4      | 1.01%   |
| Samsung Electronics HD103UJ 1TB                                 | 4        | 6      | 1.01%   |
| Kingston SV300S37A120G 120GB SSD                                | 4        | 4      | 1.01%   |
| WDC WD20EFRX-68EUZN0 2TB                                        | 3        | 6      | 0.75%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 3        | 3      | 0.75%   |
| WDC WD15EARS-00MVWB0 1TB                                        | 3        | 3      | 0.75%   |
| WDC WD10EZEX-00RKKA0 1TB                                        | 3        | 3      | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB                                        | 3        | 3      | 0.75%   |
| WDC WD10EARX-00N0YB0 1TB                                        | 3        | 4      | 0.75%   |
| Toshiba MQ01ABD050 500GB                                        | 3        | 3      | 0.75%   |
| Seagate ST4000DM000-1F2168 4TB                                  | 3        | 13     | 0.75%   |
| Seagate ST3250318AS 250GB                                       | 3        | 3      | 0.75%   |
| Seagate ST31000524AS 1TB                                        | 3        | 5      | 0.75%   |
| Seagate ST2000DX001-1CM164 2TB                                  | 3        | 3      | 0.75%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 3        | 8      | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 3        | 3      | 0.75%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 3        | 3      | 0.75%   |
| Kingston SA400S37240G 240GB SSD                                 | 3        | 3      | 0.75%   |
| Crucial CT525MX300SSD1 528GB                                    | 3        | 3      | 0.75%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 2        | 2      | 0.5%    |
| WDC WD5000AAKX-003CA0 500GB                                     | 2        | 2      | 0.5%    |
| WDC WD5000AACS-00G8B1 500GB                                     | 2        | 2      | 0.5%    |
| WDC WD40EFRX-68WT0N0 4TB                                        | 2        | 3      | 0.5%    |
| WDC WD30EZRZ-00Z5HB0 3TB                                        | 2        | 2      | 0.5%    |
| WDC WD30EFRX-68EUZN0 3TB                                        | 2        | 2      | 0.5%    |
| WDC WD20EZRX-00DC0B0 2TB                                        | 2        | 2      | 0.5%    |
| WDC WD20EARX-00PASB0 2TB                                        | 2        | 2      | 0.5%    |
| WDC WD10EZEX-22MFCA0 1TB                                        | 2        | 2      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 119      | 142    | 31.23%  |
| Seagate               | 109      | 162    | 28.61%  |
| Samsung Electronics   | 35       | 42     | 9.19%   |
| Hitachi               | 20       | 23     | 5.25%   |
| Toshiba               | 14       | 17     | 3.67%   |
| Kingston              | 13       | 13     | 3.41%   |
| SanDisk               | 10       | 13     | 2.62%   |
| Intel                 | 10       | 11     | 2.62%   |
| Crucial               | 9        | 10     | 2.36%   |
| HGST                  | 7        | 7      | 1.84%   |
| A-DATA Technology     | 5        | 5      | 1.31%   |
| SK hynix              | 2        | 3      | 0.52%   |
| OCZ                   | 2        | 2      | 0.52%   |
| Micron Technology     | 2        | 2      | 0.52%   |
| Maxtor                | 2        | 2      | 0.52%   |
| Corsair               | 2        | 6      | 0.52%   |
| Apacer                | 2        | 2      | 0.52%   |
| Unknown               | 2        | 3      | 0.52%   |
| Transcend             | 1        | 1      | 0.26%   |
| SPCC                  | 1        | 1      | 0.26%   |
| Realtek Semiconductor | 1        | 1      | 0.26%   |
| Phison Electronics    | 1        | 1      | 0.26%   |
| Phison                | 1        | 2      | 0.26%   |
| Patriot               | 1        | 1      | 0.26%   |
| MaxDigital            | 1        | 1      | 0.26%   |
| KingSpec              | 1        | 2      | 0.26%   |
| JMicron Technology    | 1        | 1      | 0.26%   |
| Intenso               | 1        | 4      | 0.26%   |
| Hewlett-Packard       | 1        | 1      | 0.26%   |
| Fujitsu               | 1        | 1      | 0.26%   |
| Drevo                 | 1        | 1      | 0.26%   |
| China                 | 1        | 2      | 0.26%   |
| ASMT                  | 1        | 5      | 0.26%   |
| ADATA Technology      | 1        | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 117      | 140    | 39.93%  |
| Seagate             | 108      | 159    | 36.86%  |
| Samsung Electronics | 21       | 26     | 7.17%   |
| Hitachi             | 20       | 23     | 6.83%   |
| Toshiba             | 14       | 17     | 4.78%   |
| HGST                | 7        | 7      | 2.39%   |
| Maxtor              | 2        | 2      | 0.68%   |
| MaxDigital          | 1        | 1      | 0.34%   |
| JMicron Technology  | 1        | 1      | 0.34%   |
| Fujitsu             | 1        | 1      | 0.34%   |
| Unknown             | 1        | 2      | 0.34%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 268      | 379    | 75.49%  |
| SSD  | 70       | 93     | 19.72%  |
| NVMe | 17       | 19     | 4.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2139     | 7135   | 58.47%  |
| Works    | 1170     | 3425   | 31.98%  |
| Malfunc  | 337      | 491    | 9.21%   |
| Failed   | 12       | 13     | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1652     | 32.56%  |
| AMD                              | 1500     | 29.56%  |
| Samsung Electronics              | 526      | 10.37%  |
| SanDisk                          | 215      | 4.24%   |
| ASMedia Technology               | 214      | 4.22%   |
| Phison Electronics               | 175      | 3.45%   |
| Kingston Technology Company      | 109      | 2.15%   |
| Micron/Crucial Technology        | 103      | 2.03%   |
| Marvell Technology Group         | 82       | 1.62%   |
| Silicon Motion                   | 76       | 1.5%    |
| JMicron Technology               | 74       | 1.46%   |
| ADATA Technology                 | 62       | 1.22%   |
| Realtek Semiconductor            | 44       | 0.87%   |
| Nvidia                           | 41       | 0.81%   |
| SK hynix                         | 26       | 0.51%   |
| MAXIO Technology (Hangzhou)      | 19       | 0.37%   |
| Micron Technology                | 18       | 0.35%   |
| Toshiba America Info Systems     | 15       | 0.3%    |
| Shenzhen Longsys Electronics     | 13       | 0.26%   |
| LSI Logic / Symbios Logic        | 13       | 0.26%   |
| Seagate Technology               | 12       | 0.24%   |
| VIA Technologies                 | 11       | 0.22%   |
| KIOXIA                           | 11       | 0.22%   |
| Broadcom / LSI                   | 9        | 0.18%   |
| Lite-On Technology               | 8        | 0.16%   |
| INNOGRIT                         | 7        | 0.14%   |
| Silicon Image                    | 6        | 0.12%   |
| Adaptec                          | 4        | 0.08%   |
| Union Memory (Shenzhen)          | 3        | 0.06%   |
| Integrated Technology Express    | 3        | 0.06%   |
| Yangtze Memory Technologies      | 2        | 0.04%   |
| Transcend                        | 2        | 0.04%   |
| Solidigm                         | 2        | 0.04%   |
| Netac Technology                 | 2        | 0.04%   |
| Lenovo                           | 2        | 0.04%   |
| HighPoint Technologies           | 2        | 0.04%   |
| Unknown                          | 2        | 0.04%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| PMC-Sierra                       | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 901      | 14.42%  |
| AMD 400 Series Chipset SATA Controller                                                  | 401      | 6.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 289      | 4.63%   |
| AMD 500 Series Chipset SATA Controller                                                  | 228      | 3.65%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 204      | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 189      | 3.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 157      | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 137      | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 125      | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 123      | 1.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 121      | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 119      | 1.9%    |
| Intel SATA Controller [RAID mode]                                                       | 115      | 1.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 105      | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 104      | 1.66%   |
| AMD 300 Series Chipset SATA Controller                                                  | 98       | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 83       | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 80       | 1.28%   |
| Phison E12 NVMe Controller                                                              | 78       | 1.25%   |
| AMD 600 Series Chipset SATA Controller                                                  | 75       | 1.2%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 70       | 1.12%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 64       | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 61       | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 58       | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 55       | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 53       | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 50       | 0.8%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 50       | 0.8%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 50       | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 50       | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 50       | 0.8%    |
| AMD X370 Series Chipset SATA Controller                                                 | 49       | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 49       | 0.78%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 45       | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 45       | 0.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 44       | 0.7%    |
| Intel SSD 660P Series                                                                   | 43       | 0.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 42       | 0.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 42       | 0.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 42       | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2822     | 58.87%  |
| NVMe | 1306     | 27.24%  |
| IDE  | 447      | 9.32%   |
| RAID | 189      | 3.94%   |
| SAS  | 26       | 0.54%   |
| SCSI | 4        | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1620     | 51.07%  |
| AMD    | 1552     | 48.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 153      | 4.8%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 89       | 2.79%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 70       | 2.2%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 70       | 2.2%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 56       | 1.76%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 50       | 1.57%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 43       | 1.35%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 39       | 1.22%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 38       | 1.19%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 33       | 1.03%   |
| AMD FX-8350 Eight-Core Processor            | 32       | 1%      |
| AMD FX-6300 Six-Core Processor              | 31       | 0.97%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 30       | 0.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 29       | 0.91%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 29       | 0.91%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 29       | 0.91%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 28       | 0.88%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 27       | 0.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 27       | 0.85%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 27       | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 26       | 0.82%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 26       | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 25       | 0.78%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 25       | 0.78%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 25       | 0.78%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 25       | 0.78%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 25       | 0.78%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 25       | 0.78%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 24       | 0.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 24       | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 0.69%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 22       | 0.69%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 21       | 0.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 20       | 0.63%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 20       | 0.63%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 19       | 0.6%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 19       | 0.6%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 18       | 0.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 18       | 0.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 17       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 532      | 16.71%  |
| Intel Core i5           | 513      | 16.12%  |
| Intel Core i7           | 418      | 13.13%  |
| AMD Ryzen 7             | 386      | 12.13%  |
| AMD Ryzen 9             | 184      | 5.78%   |
| Intel Core i3           | 163      | 5.12%   |
| Intel Xeon              | 152      | 4.78%   |
| AMD FX                  | 131      | 4.12%   |
| Other                   | 119      | 3.74%   |
| AMD Ryzen 3             | 62       | 1.95%   |
| Intel Core 2 Duo        | 51       | 1.6%    |
| Intel Celeron           | 39       | 1.23%   |
| Intel Pentium           | 38       | 1.19%   |
| AMD Phenom II X4        | 34       | 1.07%   |
| Intel Core 2 Quad       | 32       | 1.01%   |
| Intel Core i9           | 31       | 0.97%   |
| AMD Ryzen Threadripper  | 31       | 0.97%   |
| Intel Pentium Dual-Core | 24       | 0.75%   |
| AMD Athlon II X2        | 21       | 0.66%   |
| AMD A8                  | 20       | 0.63%   |
| AMD A10                 | 20       | 0.63%   |
| AMD A4                  | 19       | 0.6%    |
| AMD Phenom II X6        | 15       | 0.47%   |
| AMD Athlon              | 14       | 0.44%   |
| Intel Core 2            | 12       | 0.38%   |
| AMD Athlon 64 X2        | 12       | 0.38%   |
| AMD Athlon II X4        | 11       | 0.35%   |
| AMD Athlon X4           | 10       | 0.31%   |
| AMD Ryzen 5 PRO         | 9        | 0.28%   |
| Intel Atom              | 8        | 0.25%   |
| Intel Pentium Dual      | 7        | 0.22%   |
| AMD Phenom              | 7        | 0.22%   |
| Intel Pentium Gold      | 6        | 0.19%   |
| AMD Ryzen 7 PRO         | 6        | 0.19%   |
| Intel Genuine           | 5        | 0.16%   |
| AMD Sempron             | 5        | 0.16%   |
| AMD Athlon II X3        | 5        | 0.16%   |
| Intel Pentium D         | 4        | 0.13%   |
| AMD A6                  | 4        | 0.13%   |
| AMD Phenom II X2        | 3        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1051     | 33.01%  |
| 6       | 758      | 23.81%  |
| 8       | 506      | 15.89%  |
| 2       | 447      | 14.04%  |
| 12      | 164      | 5.15%   |
| 16      | 110      | 3.45%   |
| 3       | 52       | 1.63%   |
| 1       | 32       | 1.01%   |
| 10      | 26       | 0.82%   |
| 24      | 13       | 0.41%   |
| 14      | 11       | 0.35%   |
| 20      | 4        | 0.13%   |
| 32      | 3        | 0.09%   |
| Unknown | 2        | 0.06%   |
| 64      | 1        | 0.03%   |
| 40      | 1        | 0.03%   |
| 28      | 1        | 0.03%   |
| 22      | 1        | 0.03%   |
| 7       | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3137     | 98.93%  |
| 2      | 34       | 1.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2205     | 69.36%  |
| 1       | 972      | 30.58%  |
| Unknown | 2        | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3143     | 98.96%  |
| Unknown        | 33       | 1.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1846     | 56.11%  |
| 0x08701021 | 150      | 4.56%   |
| 0x0800820d | 111      | 3.37%   |
| 0x306c3    | 109      | 3.31%   |
| 0x08701013 | 76       | 2.31%   |
| 0x306a9    | 69       | 2.1%    |
| 0x206a7    | 64       | 1.95%   |
| 0x906ea    | 60       | 1.82%   |
| 0x06000852 | 55       | 1.67%   |
| 0x506e3    | 51       | 1.55%   |
| 0x1067a    | 35       | 1.06%   |
| 0x08001138 | 33       | 1%      |
| 0x906e9    | 28       | 0.85%   |
| 0x0a201016 | 27       | 0.82%   |
| 0x08108109 | 25       | 0.76%   |
| 0x0a201009 | 24       | 0.73%   |
| 0x010000c8 | 24       | 0.73%   |
| 0x306f2    | 23       | 0.7%    |
| 0x0a601203 | 22       | 0.67%   |
| 0x206d7    | 20       | 0.61%   |
| 0x08001137 | 20       | 0.61%   |
| 0x0a20120a | 19       | 0.58%   |
| 0x08101016 | 19       | 0.58%   |
| 0x0a50000d | 17       | 0.52%   |
| 0x90672    | 15       | 0.46%   |
| 0x06003106 | 15       | 0.46%   |
| 0xa0655    | 14       | 0.43%   |
| 0x0a50000c | 14       | 0.43%   |
| 0x06001119 | 14       | 0.43%   |
| 0x906ed    | 13       | 0.4%    |
| 0x106e5    | 13       | 0.4%    |
| 0x08600106 | 11       | 0.33%   |
| 0xa0671    | 9        | 0.27%   |
| 0x906eb    | 9        | 0.27%   |
| 0x206c2    | 9        | 0.27%   |
| 0x08001129 | 9        | 0.27%   |
| 0xa0653    | 8        | 0.24%   |
| 0x906ec    | 8        | 0.24%   |
| 0x6fd      | 8        | 0.24%   |
| 0x010000dc | 8        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 413      | 12.96%  |
| Haswell          | 313      | 9.82%   |
| KabyLake         | 309      | 9.7%    |
| Zen 3            | 270      | 8.47%   |
| Zen+             | 269      | 8.44%   |
| Zen              | 192      | 6.03%   |
| IvyBridge        | 188      | 5.9%    |
| SandyBridge      | 180      | 5.65%   |
| Unknown          | 159      | 4.99%   |
| Skylake          | 145      | 4.55%   |
| Piledriver       | 144      | 4.52%   |
| Penryn           | 102      | 3.2%    |
| K10              | 97       | 3.04%   |
| CometLake        | 70       | 2.2%    |
| Core             | 45       | 1.41%   |
| Westmere         | 44       | 1.38%   |
| Alderlake Hybrid | 40       | 1.26%   |
| Nehalem          | 38       | 1.19%   |
| Steamroller      | 30       | 0.94%   |
| Broadwell        | 25       | 0.78%   |
| Bulldozer        | 20       | 0.63%   |
| K8 Hammer        | 16       | 0.5%    |
| Icelake          | 12       | 0.38%   |
| Excavator        | 11       | 0.35%   |
| Silvermont       | 7        | 0.22%   |
| Goldmont plus    | 7        | 0.22%   |
| Bonnell          | 7        | 0.22%   |
| NetBurst         | 6        | 0.19%   |
| K10 Llano        | 6        | 0.19%   |
| Goldmont         | 6        | 0.19%   |
| Jaguar           | 4        | 0.13%   |
| Bobcat           | 4        | 0.13%   |
| TigerLake        | 2        | 0.06%   |
| Puma             | 2        | 0.06%   |
| Gracemont        | 2        | 0.06%   |
| Tremont          | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1586     | 46.02%  |
| AMD                        | 1250     | 36.27%  |
| Intel                      | 607      | 17.61%  |
| VIA Technologies           | 1        | 0.03%   |
| Matrox Electronics Systems | 1        | 0.03%   |
| ATI Technologies           | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 271      | 7.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 111      | 3.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 102      | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 102      | 2.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 96       | 2.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 72       | 2.01%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 69       | 1.93%   |
| Nvidia GK208B [GeForce GT 710]                                              | 67       | 1.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 58       | 1.62%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 57       | 1.59%   |
| AMD Raphael                                                                 | 53       | 1.48%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 52       | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 49       | 1.37%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 48       | 1.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 47       | 1.31%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 46       | 1.28%   |
| Intel HD Graphics 530                                                       | 46       | 1.28%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 46       | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 43       | 1.2%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 41       | 1.15%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 38       | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 37       | 1.03%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 37       | 1.03%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 36       | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 36       | 1.01%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 35       | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 35       | 0.98%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 34       | 0.95%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 32       | 0.89%   |
| Nvidia GK208B [GeForce GT 730]                                              | 29       | 0.81%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 29       | 0.81%   |
| Intel HD Graphics 630                                                       | 29       | 0.81%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 29       | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 28       | 0.78%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 28       | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 27       | 0.75%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 26       | 0.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 25       | 0.7%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 24       | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 24       | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1422     | 44.07%  |
| 1 x AMD                  | 1096     | 33.96%  |
| 1 x Intel                | 445      | 13.79%  |
| AMD + Nvidia             | 69       | 2.14%   |
| 2 x AMD                  | 68       | 2.11%   |
| Intel + Nvidia           | 64       | 1.98%   |
| 2 x Nvidia               | 32       | 0.99%   |
| Intel + AMD              | 22       | 0.68%   |
| 2 x Intel                | 2        | 0.06%   |
| 3 x AMD                  | 1        | 0.03%   |
| 1 x VIA                  | 1        | 0.03%   |
| 1 x Matrox               | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| Intel + 2 x AMD          | 1        | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1911     | 59.42%  |
| Proprietary | 1282     | 39.86%  |
| Unknown     | 23       | 0.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1369     | 41.76%  |
| 7.01-8.0   | 496      | 15.13%  |
| 1.01-2.0   | 349      | 10.65%  |
| 3.01-4.0   | 310      | 9.46%   |
| 5.01-6.0   | 203      | 6.19%   |
| 8.01-16.0  | 189      | 5.77%   |
| 0.51-1.0   | 172      | 5.25%   |
| 0.01-0.5   | 94       | 2.87%   |
| 2.01-3.0   | 55       | 1.68%   |
| 16.01-24.0 | 39       | 1.19%   |
| 4.01-5.0   | 2        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 606      | 15.7%   |
| Goldstar             | 419      | 10.85%  |
| Dell                 | 357      | 9.25%   |
| Acer                 | 303      | 7.85%   |
| AOC                  | 230      | 5.96%   |
| BenQ                 | 211      | 5.46%   |
| Ancor Communications | 203      | 5.26%   |
| Hewlett-Packard      | 194      | 5.02%   |
| Philips              | 154      | 3.99%   |
| LG Electronics       | 123      | 3.19%   |
| ASUSTek Computer     | 91       | 2.36%   |
| ViewSonic            | 90       | 2.33%   |
| Unknown              | 71       | 1.84%   |
| Iiyama               | 57       | 1.48%   |
| Unknown              | 56       | 1.45%   |
| Lenovo               | 55       | 1.42%   |
| MSI                  | 38       | 0.98%   |
| Sony                 | 32       | 0.83%   |
| Gigabyte Technology  | 28       | 0.73%   |
| Vizio                | 22       | 0.57%   |
| Eizo                 | 22       | 0.57%   |
| Sceptre Tech         | 18       | 0.47%   |
| Fujitsu Siemens      | 18       | 0.47%   |
| NEC Computers        | 17       | 0.44%   |
| Idek Iiyama          | 17       | 0.44%   |
| AUS                  | 17       | 0.44%   |
| Medion               | 15       | 0.39%   |
| Panasonic            | 13       | 0.34%   |
| Vestel Elektronik    | 10       | 0.26%   |
| Sharp                | 10       | 0.26%   |
| Pixio                | 9        | 0.23%   |
| Microstep            | 9        | 0.23%   |
| Lenovo Group Limited | 9        | 0.23%   |
| HannStar             | 9        | 0.23%   |
| Toshiba              | 8        | 0.21%   |
| Mi                   | 8        | 0.21%   |
| Apple                | 8        | 0.21%   |
| HPN                  | 7        | 0.18%   |
| DENON                | 7        | 0.18%   |
| Packard Bell         | 6        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 56       | 1.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 27       | 0.64%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 23       | 0.55%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 22       | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 19       | 0.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 18       | 0.43%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 15       | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 13       | 0.31%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 13       | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.28%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 11       | 0.26%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 10       | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 10       | 0.24%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 10       | 0.24%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 9        | 0.21%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 9        | 0.21%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                      | 9        | 0.21%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 9        | 0.21%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 9        | 0.21%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 8        | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 8        | 0.19%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 8        | 0.19%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 8        | 0.19%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 8        | 0.19%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 8        | 0.19%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 8        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 7        | 0.17%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 7        | 0.17%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 7        | 0.17%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 7        | 0.17%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 7        | 0.17%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 7        | 0.17%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 7        | 0.17%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch    | 6        | 0.14%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 6        | 0.14%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 6        | 0.14%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 6        | 0.14%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch              | 6        | 0.14%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 6        | 0.14%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 6        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1599     | 42.5%   |
| 2560x1440 (QHD)    | 402      | 10.69%  |
| 3840x2160 (4K)     | 373      | 9.91%   |
| Unknown            | 202      | 5.37%   |
| 1680x1050 (WSXGA+) | 144      | 3.83%   |
| 1280x1024 (SXGA)   | 144      | 3.83%   |
| 3440x1440          | 110      | 2.92%   |
| 1366x768 (WXGA)    | 95       | 2.53%   |
| 1920x1200 (WUXGA)  | 92       | 2.45%   |
| 2560x1080          | 90       | 2.39%   |
| 1440x900 (WXGA+)   | 89       | 2.37%   |
| 3840x1080          | 76       | 2.02%   |
| 1600x900 (HD+)     | 72       | 1.91%   |
| 1360x768           | 30       | 0.8%    |
| 4480x1440          | 18       | 0.48%   |
| 2288x1287          | 18       | 0.48%   |
| 5120x1440          | 16       | 0.43%   |
| 1920x540           | 16       | 0.43%   |
| 1280x720 (HD)      | 13       | 0.35%   |
| 2560x1600          | 12       | 0.32%   |
| 1024x768 (XGA)     | 11       | 0.29%   |
| 5760x1080          | 10       | 0.27%   |
| 3600x1080          | 8        | 0.21%   |
| 5760x2160          | 7        | 0.19%   |
| 3840x1600          | 7        | 0.19%   |
| 1600x1200          | 7        | 0.19%   |
| 6400x2160          | 6        | 0.16%   |
| 3200x1080          | 6        | 0.16%   |
| 7680x2160          | 4        | 0.11%   |
| 7680x1080          | 4        | 0.11%   |
| 3840x1200          | 4        | 0.11%   |
| 3520x1080          | 4        | 0.11%   |
| 3360x1080          | 4        | 0.11%   |
| 4480x1080          | 3        | 0.08%   |
| 3360x1050          | 3        | 0.08%   |
| 3286x1080          | 3        | 0.08%   |
| 6000x1440          | 2        | 0.05%   |
| 5504x1440          | 2        | 0.05%   |
| 5120x1080          | 2        | 0.05%   |
| 4240x1440          | 2        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 641      | 17.17%  |
| 27      | 539      | 14.44%  |
| 24      | 531      | 14.22%  |
| 23      | 393      | 10.53%  |
| 21      | 331      | 8.87%   |
| 31      | 211      | 5.65%   |
| 19      | 156      | 4.18%   |
| 34      | 155      | 4.15%   |
| 22      | 102      | 2.73%   |
| 18      | 81       | 2.17%   |
| 20      | 79       | 2.12%   |
| 17      | 63       | 1.69%   |
| 84      | 43       | 1.15%   |
| 32      | 35       | 0.94%   |
| 40      | 33       | 0.88%   |
| 54      | 31       | 0.83%   |
| 72      | 30       | 0.8%    |
| 25      | 26       | 0.7%    |
| 28      | 21       | 0.56%   |
| 15      | 19       | 0.51%   |
| 142     | 18       | 0.48%   |
| 48      | 14       | 0.38%   |
| 26      | 14       | 0.38%   |
| 65      | 13       | 0.35%   |
| 33      | 11       | 0.29%   |
| 29      | 11       | 0.29%   |
| 42      | 10       | 0.27%   |
| 49      | 9        | 0.24%   |
| 37      | 9        | 0.24%   |
| 43      | 8        | 0.21%   |
| 47      | 7        | 0.19%   |
| 46      | 7        | 0.19%   |
| 39      | 7        | 0.19%   |
| 35      | 7        | 0.19%   |
| 14      | 7        | 0.19%   |
| 12      | 7        | 0.19%   |
| 52      | 6        | 0.16%   |
| 36      | 6        | 0.16%   |
| 16      | 5        | 0.13%   |
| 74      | 4        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1311     | 36.61%  |
| 401-500        | 655      | 18.29%  |
| Unknown        | 641      | 17.9%   |
| 601-700        | 294      | 8.21%   |
| 701-800        | 206      | 5.75%   |
| 1001-1500      | 98       | 2.74%   |
| 351-400        | 96       | 2.68%   |
| 1501-2000      | 83       | 2.32%   |
| 301-350        | 78       | 2.18%   |
| 801-900        | 63       | 1.76%   |
| 901-1000       | 19       | 0.53%   |
| More than 2000 | 18       | 0.5%    |
| 201-300        | 18       | 0.5%    |
| 101-200        | 1        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2018     | 60.24%  |
| Unknown | 594      | 17.73%  |
| 16/10   | 326      | 9.73%   |
| 21/9    | 175      | 5.22%   |
| 5/4     | 131      | 3.91%   |
| 4/3     | 36       | 1.07%   |
| 3/2     | 21       | 0.63%   |
| 1.00    | 19       | 0.57%   |
| 32/9    | 16       | 0.48%   |
| 6/5     | 5        | 0.15%   |
| 1.96    | 2        | 0.06%   |
| 1.03    | 2        | 0.06%   |
| 0.89    | 2        | 0.06%   |
| 3.20    | 1        | 0.03%   |
| 0.80    | 1        | 0.03%   |
| 0.56    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1075     | 29.45%  |
| Unknown        | 641      | 17.56%  |
| 301-350        | 547      | 14.99%  |
| 351-500        | 436      | 11.95%  |
| 151-200        | 314      | 8.6%    |
| 251-300        | 194      | 5.32%   |
| More than 1000 | 168      | 4.6%    |
| 141-150        | 115      | 3.15%   |
| 501-1000       | 108      | 2.96%   |
| 101-110        | 24       | 0.66%   |
| 131-140        | 9        | 0.25%   |
| 71-80          | 8        | 0.22%   |
| 81-90          | 3        | 0.08%   |
| 51-60          | 2        | 0.05%   |
| 121-130        | 2        | 0.05%   |
| 91-100         | 2        | 0.05%   |
| 1-40           | 1        | 0.03%   |
| 111-120        | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1819     | 52.83%  |
| Unknown | 642      | 18.65%  |
| 101-120 | 639      | 18.56%  |
| 121-160 | 142      | 4.12%   |
| 1-50    | 138      | 4.01%   |
| 161-240 | 63       | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2300     | 70.55%  |
| 2     | 769      | 23.59%  |
| 3     | 130      | 3.99%   |
| 0     | 45       | 1.38%   |
| 4     | 15       | 0.46%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1972     | 42.97%  |
| Intel                                  | 1437     | 31.31%  |
| Qualcomm Atheros                       | 221      | 4.82%   |
| Broadcom                               | 127      | 2.77%   |
| TP-Link                                | 113      | 2.46%   |
| Ralink Technology                      | 108      | 2.35%   |
| MediaTek                               | 95       | 2.07%   |
| Microsoft                              | 49       | 1.07%   |
| Aquantia                               | 39       | 0.85%   |
| Samsung Electronics                    | 36       | 0.78%   |
| Nvidia                                 | 33       | 0.72%   |
| Ralink                                 | 30       | 0.65%   |
| Qualcomm Atheros Communications        | 26       | 0.57%   |
| Xiaomi                                 | 23       | 0.5%    |
| NetGear                                | 20       | 0.44%   |
| D-Link                                 | 19       | 0.41%   |
| Marvell Technology Group               | 18       | 0.39%   |
| ASUSTek Computer                       | 18       | 0.39%   |
| Huawei Technologies                    | 14       | 0.31%   |
| Broadcom Limited                       | 14       | 0.31%   |
| Linksys                                | 12       | 0.26%   |
| Mellanox Technologies                  | 11       | 0.24%   |
| Edimax Technology                      | 9        | 0.2%    |
| D-Link System                          | 9        | 0.2%    |
| Microchip Technology                   | 8        | 0.17%   |
| Motorola PCS                           | 7        | 0.15%   |
| ASIX Electronics                       | 7        | 0.15%   |
| ZyXEL Communications                   | 6        | 0.13%   |
| OPPO Electronics                       | 5        | 0.11%   |
| Qualcomm                               | 4        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 4        | 0.09%   |
| InterBiometrics                        | 4        | 0.09%   |
| Google                                 | 4        | 0.09%   |
| DisplayLink                            | 4        | 0.09%   |
| AVM                                    | 4        | 0.09%   |
| ZyDAS                                  | 3        | 0.07%   |
| T & A Mobile Phones                    | 3        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.07%   |
| SEGGER                                 | 3        | 0.07%   |
| JMicron Technology                     | 3        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1544     | 29.14%  |
| Intel I211 Gigabit Network Connection                                          | 322      | 6.08%   |
| Realtek RTL8125 2.5GbE Controller                                              | 253      | 4.78%   |
| Intel Wi-Fi 6 AX200                                                            | 239      | 4.51%   |
| Intel Ethernet Connection (2) I219-V                                           | 145      | 2.74%   |
| Intel Ethernet Controller I225-V                                               | 123      | 2.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 94       | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 75       | 1.42%   |
| Intel Ethernet Connection (7) I219-V                                           | 65       | 1.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 57       | 1.08%   |
| Intel 82579V Gigabit Network Connection                                        | 54       | 1.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 52       | 0.98%   |
| Intel Ethernet Connection I217-LM                                              | 50       | 0.94%   |
| Intel Ethernet Connection (2) I218-V                                           | 47       | 0.89%   |
| Intel Ethernet Connection I217-V                                               | 42       | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 40       | 0.76%   |
| Realtek 802.11ac NIC                                                           | 39       | 0.74%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 39       | 0.74%   |
| Ralink MT7601U Wireless Adapter                                                | 38       | 0.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 37       | 0.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 36       | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 34       | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 33       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 30       | 0.57%   |
| Intel 82574L Gigabit Network Connection                                        | 30       | 0.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 29       | 0.55%   |
| Intel Wireless 7265                                                            | 28       | 0.53%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 27       | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 26       | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                                | 26       | 0.49%   |
| Microsoft Xbox 360 Wireless Adapter                                            | 26       | 0.49%   |
| Intel Wireless 8265 / 8275                                                     | 25       | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24       | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 24       | 0.45%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 24       | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                                          | 23       | 0.43%   |
| Nvidia MCP61 Ethernet                                                          | 22       | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 21       | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 21       | 0.4%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 21       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 617      | 37.03%  |
| Realtek Semiconductor                 | 333      | 19.99%  |
| TP-Link                               | 113      | 6.78%   |
| Qualcomm Atheros                      | 110      | 6.6%    |
| Ralink Technology                     | 108      | 6.48%   |
| Broadcom                              | 84       | 5.04%   |
| MediaTek                              | 68       | 4.08%   |
| Microsoft                             | 49       | 2.94%   |
| Ralink                                | 30       | 1.8%    |
| Qualcomm Atheros Communications       | 26       | 1.56%   |
| NetGear                               | 20       | 1.2%    |
| D-Link                                | 19       | 1.14%   |
| ASUSTek Computer                      | 18       | 1.08%   |
| Linksys                               | 12       | 0.72%   |
| Edimax Technology                     | 9        | 0.54%   |
| ZyXEL Communications                  | 6        | 0.36%   |
| D-Link System                         | 6        | 0.36%   |
| Broadcom Limited                      | 6        | 0.36%   |
| AVM                                   | 4        | 0.24%   |
| ZyDAS                                 | 3        | 0.18%   |
| IMC Networks                          | 3        | 0.18%   |
| Belkin Components                     | 3        | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.18%   |
| Xiaomi                                | 2        | 0.12%   |
| Tenda                                 | 2        | 0.12%   |
| Samsung Electronics                   | 2        | 0.12%   |
| Mercucys                              | 2        | 0.12%   |
| Wacom                                 | 1        | 0.06%   |
| Senao                                 | 1        | 0.06%   |
| Qualcomm Technologies                 | 1        | 0.06%   |
| Philips (or NXP)                      | 1        | 0.06%   |
| Micro Star International              | 1        | 0.06%   |
| Marvell Technology Group              | 1        | 0.06%   |
| Fujitsu Siemens Computers             | 1        | 0.06%   |
| Encore Electronics                    | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 239      | 14.19%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 75       | 4.45%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 57       | 3.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 52       | 3.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 40       | 2.38%   |
| Realtek 802.11ac NIC                                           | 39       | 2.32%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 39       | 2.32%   |
| Ralink MT7601U Wireless Adapter                                | 38       | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 34       | 2.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 33       | 1.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 29       | 1.72%   |
| Intel Wireless 7265                                            | 28       | 1.66%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 27       | 1.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 26       | 1.54%   |
| Qualcomm Atheros AR9271 802.11n                                | 26       | 1.54%   |
| Microsoft Xbox 360 Wireless Adapter                            | 26       | 1.54%   |
| Intel Wireless 8265 / 8275                                     | 25       | 1.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 24       | 1.43%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 24       | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 21       | 1.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 21       | 1.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 1.19%   |
| Ralink RT5370 Wireless Adapter                                 | 20       | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19       | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 19       | 1.13%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 19       | 1.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17       | 1.01%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 16       | 0.95%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 16       | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 15       | 0.89%   |
| Intel Wireless 7260                                            | 14       | 0.83%   |
| Intel Wireless 3165                                            | 14       | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 12       | 0.71%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 12       | 0.71%   |
| TP-Link 802.11ac NIC                                           | 11       | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11       | 0.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 11       | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 11       | 0.65%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 11       | 0.65%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 10       | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1862     | 54.4%   |
| Intel                                  | 1143     | 33.39%  |
| Qualcomm Atheros                       | 126      | 3.68%   |
| Broadcom                               | 46       | 1.34%   |
| Aquantia                               | 39       | 1.14%   |
| Nvidia                                 | 33       | 0.96%   |
| MediaTek                               | 23       | 0.67%   |
| Xiaomi                                 | 21       | 0.61%   |
| Samsung Electronics                    | 20       | 0.58%   |
| Marvell Technology Group               | 17       | 0.5%    |
| Mellanox Technologies                  | 11       | 0.32%   |
| Huawei Technologies                    | 11       | 0.32%   |
| Broadcom Limited                       | 8        | 0.23%   |
| Motorola PCS                           | 7        | 0.2%    |
| ASIX Electronics                       | 7        | 0.2%    |
| OPPO Electronics                       | 5        | 0.15%   |
| Google                                 | 4        | 0.12%   |
| DisplayLink                            | 4        | 0.12%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.09%   |
| Qualcomm                               | 3        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.09%   |
| JMicron Technology                     | 3        | 0.09%   |
| HMD Global                             | 3        | 0.09%   |
| D-Link System                          | 3        | 0.09%   |
| VIA Technologies                       | 2        | 0.06%   |
| T & A Mobile Phones                    | 2        | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.06%   |
| National Semiconductor                 | 2        | 0.06%   |
| TP-Link Corporation Limited.           | 1        | 0.03%   |
| Spreadtrum Communications              | 1        | 0.03%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |
| LG Electronics                         | 1        | 0.03%   |
| ICS Advent                             | 1        | 0.03%   |
| Foxconn / Hon Hai                      | 1        | 0.03%   |
| Apple                                  | 1        | 0.03%   |
| Accton Technology                      | 1        | 0.03%   |
| 3Com                                   | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1544     | 43.52%  |
| Intel I211 Gigabit Network Connection                                          | 322      | 9.08%   |
| Realtek RTL8125 2.5GbE Controller                                              | 253      | 7.13%   |
| Intel Ethernet Connection (2) I219-V                                           | 145      | 4.09%   |
| Intel Ethernet Controller I225-V                                               | 123      | 3.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 94       | 2.65%   |
| Intel Ethernet Connection (7) I219-V                                           | 65       | 1.83%   |
| Intel 82579V Gigabit Network Connection                                        | 54       | 1.52%   |
| Intel Ethernet Connection I217-LM                                              | 50       | 1.41%   |
| Intel Ethernet Connection (2) I218-V                                           | 47       | 1.32%   |
| Intel Ethernet Connection I217-V                                               | 42       | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 36       | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 30       | 0.85%   |
| Intel 82574L Gigabit Network Connection                                        | 30       | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24       | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                                          | 23       | 0.65%   |
| Nvidia MCP61 Ethernet                                                          | 22       | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 21       | 0.59%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 21       | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 20       | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 18       | 0.51%   |
| Intel I210 Gigabit Network Connection                                          | 18       | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 18       | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 17       | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 16       | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 16       | 0.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 16       | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                                          | 16       | 0.45%   |
| Intel Ethernet Connection (14) I219-V                                          | 15       | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 14       | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 13       | 0.37%   |
| Intel Ethernet Connection (2) I218-LM                                          | 13       | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 12       | 0.34%   |
| Intel Ethernet Connection (11) I219-V                                          | 12       | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 11       | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 10       | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 9        | 0.25%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 8        | 0.23%   |
| Intel Ethernet Connection (12) I219-V                                          | 8        | 0.23%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 8        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3135     | 66.17%  |
| WiFi     | 1540     | 32.5%   |
| Modem    | 54       | 1.14%   |
| Unknown  | 9        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2505     | 75.36%  |
| WiFi     | 817      | 24.58%  |
| Modem    | 2        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1962     | 61.16%  |
| 2     | 1051     | 32.76%  |
| 3     | 146      | 4.55%   |
| 0     | 25       | 0.78%   |
| 4     | 12       | 0.37%   |
| 5     | 10       | 0.31%   |
| 8     | 1        | 0.03%   |
| 7     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2561     | 79.17%  |
| Yes  | 674      | 20.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 585      | 39.93%  |
| Cambridge Silicon Radio         | 360      | 24.57%  |
| ASUSTek Computer                | 122      | 8.33%   |
| Realtek Semiconductor           | 100      | 6.83%   |
| Broadcom                        | 67       | 4.57%   |
| MediaTek                        | 43       | 2.94%   |
| TP-Link                         | 35       | 2.39%   |
| IMC Networks                    | 29       | 1.98%   |
| Foxconn / Hon Hai               | 27       | 1.84%   |
| Apple                           | 20       | 1.37%   |
| Qualcomm Atheros Communications | 19       | 1.3%    |
| Edimax Technology               | 11       | 0.75%   |
| Dynex                           | 7        | 0.48%   |
| Realtek                         | 6        | 0.41%   |
| Integrated System Solution      | 6        | 0.41%   |
| HTC (High Tech Computer)        | 5        | 0.34%   |
| Belkin Components               | 5        | 0.34%   |
| Lite-On Technology              | 4        | 0.27%   |
| Conwise Technology              | 4        | 0.27%   |
| SINO WEALTH                     | 3        | 0.2%    |
| Ralink                          | 2        | 0.14%   |
| Sitecom Europe                  | 1        | 0.07%   |
| Micro Star International        | 1        | 0.07%   |
| D-Link                          | 1        | 0.07%   |
| Actions                         | 1        | 0.07%   |
| Unknown                         | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 360      | 24.51%  |
| Intel AX200 Bluetooth                                                | 221      | 15.04%  |
| Intel Bluetooth wireless interface                                   | 89       | 6.06%   |
| Realtek Bluetooth Radio                                              | 80       | 5.45%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 74       | 5.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 56       | 3.81%   |
| Intel AX210 Bluetooth                                                | 49       | 3.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 47       | 3.2%    |
| MediaTek Wireless_Device                                             | 43       | 2.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 36       | 2.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 36       | 2.45%   |
| TP-Link TP-Link Bluetooth USB Adapter                                | 35       | 2.38%   |
| Intel AX201 Bluetooth                                                | 35       | 2.38%   |
| ASUS ASUS USB-BT500                                                  | 27       | 1.84%   |
| Intel AX211 Bluetooth                                                | 23       | 1.57%   |
| Foxconn / Hon Hai Wireless_Device                                    | 18       | 1.23%   |
| ASUS Bluetooth Radio                                                 | 17       | 1.16%   |
| IMC Networks Bluetooth Radio                                         | 16       | 1.09%   |
| ASUS Bluetooth Adapter                                               | 15       | 1.02%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 12       | 0.82%   |
| ASUS BCM20702A0                                                      | 12       | 0.82%   |
| Edimax Bluetooth Adapter                                             | 9        | 0.61%   |
| Apple Bluetooth Host Controller                                      | 9        | 0.61%   |
| Qualcomm Atheros  Bluetooth Device                                   | 8        | 0.54%   |
| IMC Networks Wireless_Device                                         | 8        | 0.54%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 8        | 0.54%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 7        | 0.48%   |
| Realtek Bluetooth Radio                                              | 6        | 0.41%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 6        | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6        | 0.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 5        | 0.34%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.34%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 5        | 0.34%   |
| Integrated System Solution Bluetooth Device                          | 4        | 0.27%   |
| Conwise CW6622                                                       | 4        | 0.27%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 4        | 0.27%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 4        | 0.27%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.2%    |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 3        | 0.2%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1838     | 29.43%  |
| Intel                                | 1571     | 25.16%  |
| Nvidia                               | 1528     | 24.47%  |
| C-Media Electronics                  | 206      | 3.3%    |
| Logitech                             | 95       | 1.52%   |
| Creative Labs                        | 75       | 1.2%    |
| Kingston Technology                  | 62       | 0.99%   |
| JMTek                                | 50       | 0.8%    |
| Texas Instruments                    | 49       | 0.78%   |
| Focusrite-Novation                   | 44       | 0.7%    |
| Corsair                              | 43       | 0.69%   |
| ASUSTek Computer                     | 42       | 0.67%   |
| Razer USA                            | 40       | 0.64%   |
| Creative Technology                  | 36       | 0.58%   |
| SteelSeries ApS                      | 34       | 0.54%   |
| Generalplus Technology               | 30       | 0.48%   |
| Blue Microphones                     | 27       | 0.43%   |
| BEHRINGER International              | 22       | 0.35%   |
| Sony                                 | 16       | 0.26%   |
| Micro Star International             | 16       | 0.26%   |
| Plantronics                          | 15       | 0.24%   |
| Realtek Semiconductor                | 14       | 0.22%   |
| Samson Technologies                  | 13       | 0.21%   |
| GN Netcom                            | 13       | 0.21%   |
| GYROCOM C&C                          | 12       | 0.19%   |
| Giga-Byte Technology                 | 12       | 0.19%   |
| VIA Technologies                     | 11       | 0.18%   |
| Yamaha                               | 10       | 0.16%   |
| RODE Microphones                     | 10       | 0.16%   |
| M-Audio                              | 10       | 0.16%   |
| Astro Gaming                         | 10       | 0.16%   |
| Turtle Beach                         | 9        | 0.14%   |
| Thesycon Systemsoftware & Consulting | 8        | 0.13%   |
| SAVITECH                             | 8        | 0.13%   |
| Microsoft                            | 8        | 0.13%   |
| KTMicro                              | 8        | 0.13%   |
| DSEA A/S                             | 8        | 0.13%   |
| Dell                                 | 8        | 0.13%   |
| Audio-Technica                       | 8        | 0.13%   |
| XMOS                                 | 7        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 562      | 7.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 341      | 4.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 280      | 3.8%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 261      | 3.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 198      | 2.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 197      | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 176      | 2.39%   |
| Intel 200 Series PCH HD Audio                                              | 164      | 2.23%   |
| Nvidia GP104 High Definition Audio Controller                              | 143      | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 143      | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 142      | 1.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 137      | 1.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 136      | 1.85%   |
| AMD Navi 10 HDMI Audio                                                     | 135      | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 130      | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 123      | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 114      | 1.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 99       | 1.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 90       | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 87       | 1.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 86       | 1.17%   |
| Nvidia GA104 High Definition Audio Controller                              | 81       | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 80       | 1.09%   |
| AMD FCH Azalia Controller                                                  | 76       | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 75       | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 72       | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 71       | 0.96%   |
| Nvidia TU104 HD Audio Controller                                           | 70       | 0.95%   |
| Nvidia GM204 High Definition Audio Controller                              | 66       | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 66       | 0.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 66       | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 57       | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 57       | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 56       | 0.76%   |
| Intel Alder Lake-S HD Audio Controller                                     | 55       | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 52       | 0.71%   |
| Nvidia GA102 High Definition Audio Controller                              | 49       | 0.67%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 47       | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                              | 46       | 0.62%   |
| Nvidia GK104 HDMI Audio Controller                                         | 45       | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 358      | 18.56%  |
| Corsair                      | 358      | 18.56%  |
| G.Skill                      | 269      | 13.95%  |
| Unknown                      | 206      | 10.68%  |
| Crucial                      | 170      | 8.81%   |
| Samsung Electronics          | 112      | 5.81%   |
| SK hynix                     | 76       | 3.94%   |
| Micron Technology            | 64       | 3.32%   |
| Team                         | 52       | 2.7%    |
| A-DATA Technology            | 47       | 2.44%   |
| Patriot                      | 34       | 1.76%   |
| Unknown                      | 21       | 1.09%   |
| GOODRAM                      | 13       | 0.67%   |
| Nanya Technology             | 12       | 0.62%   |
| Elpida                       | 11       | 0.57%   |
| Ramaxel Technology           | 10       | 0.52%   |
| Unknown (ABCD)               | 7        | 0.36%   |
| Patriot Memory (PDP Systems) | 5        | 0.26%   |
| Kllisre                      | 5        | 0.26%   |
| GeIL                         | 5        | 0.26%   |
| AMD                          | 5        | 0.26%   |
| Transcend                    | 4        | 0.21%   |
| Smart                        | 4        | 0.21%   |
| Silicon Power                | 4        | 0.21%   |
| PNY                          | 4        | 0.21%   |
| Neo Forza                    | 4        | 0.21%   |
| KLEVV                        | 4        | 0.21%   |
| Kingmax                      | 4        | 0.21%   |
| CSX                          | 3        | 0.16%   |
| Apacer                       | 3        | 0.16%   |
| Unknown (08C8)               | 2        | 0.1%    |
| SemsoTai                     | 2        | 0.1%    |
| Qumo                         | 2        | 0.1%    |
| Patriot Memory               | 2        | 0.1%    |
| Lexar Co Limited             | 2        | 0.1%    |
| Hewlett-Packard              | 2        | 0.1%    |
| Wilk Elektronik              | 1        | 0.05%   |
| Wilk                         | 1        | 0.05%   |
| Unknown (AB)                 | 1        | 0.05%   |
| Unknown (0xAD44594E45540000) | 1        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 49       | 2.3%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s        | 35       | 1.64%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s          | 24       | 1.13%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 22       | 1.03%   |
| Unknown                                                      | 21       | 0.98%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 20       | 0.94%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 19       | 0.89%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 19       | 0.89%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 18       | 0.84%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 15       | 0.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 14       | 0.66%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s       | 14       | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s           | 13       | 0.61%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 12       | 0.56%   |
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s           | 11       | 0.52%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s          | 11       | 0.52%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s        | 11       | 0.52%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                  | 11       | 0.52%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 10       | 0.47%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s        | 10       | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 9        | 0.42%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 9        | 0.42%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 3000MT/s          | 9        | 0.42%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 9        | 0.42%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s          | 9        | 0.42%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s               | 8        | 0.38%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s          | 8        | 0.38%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 8        | 0.38%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s        | 8        | 0.38%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s          | 8        | 0.38%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 8        | 0.38%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 7        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s | 7        | 0.33%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s        | 7        | 0.33%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s          | 7        | 0.33%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s       | 7        | 0.33%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s        | 7        | 0.33%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s       | 7        | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 6        | 0.28%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s        | 6        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1017     | 58.75%  |
| DDR3    | 457      | 26.4%   |
| Unknown | 84       | 4.85%   |
| DDR5    | 60       | 3.47%   |
| DDR2    | 45       | 2.6%    |
| SDRAM   | 41       | 2.37%   |
| DDR     | 11       | 0.64%   |
| LPDDR4  | 8        | 0.46%   |
| DRAM    | 6        | 0.35%   |
| LPDDR5  | 1        | 0.06%   |
| LPDDR3  | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1653     | 96.5%   |
| SODIMM       | 52       | 3.04%   |
| RIMM         | 3        | 0.18%   |
| FB-DIMM      | 3        | 0.18%   |
| Row Of Chips | 2        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 792      | 42.17%  |
| 16384 | 423      | 22.52%  |
| 4096  | 355      | 18.9%   |
| 2048  | 152      | 8.09%   |
| 32768 | 109      | 5.8%    |
| 1024  | 39       | 2.08%   |
| 512   | 4        | 0.21%   |
| 49152 | 2        | 0.11%   |
| 24576 | 1        | 0.05%   |
| 3072  | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 250      | 12.9%   |
| 3600    | 243      | 12.54%  |
| 3200    | 238      | 12.28%  |
| 1333    | 152      | 7.84%   |
| 2400    | 102      | 5.26%   |
| 2133    | 82       | 4.23%   |
| 2667    | 75       | 3.87%   |
| 3800    | 62       | 3.2%    |
| 3000    | 60       | 3.1%    |
| 1867    | 56       | 2.89%   |
| 3400    | 52       | 2.68%   |
| 3733    | 51       | 2.63%   |
| 800     | 50       | 2.58%   |
| 1866    | 39       | 2.01%   |
| 4000    | 33       | 1.7%    |
| 3466    | 32       | 1.65%   |
| 667     | 30       | 1.55%   |
| 1800    | 28       | 1.44%   |
| 2666    | 24       | 1.24%   |
| 2933    | 22       | 1.14%   |
| 6000    | 18       | 0.93%   |
| Unknown | 17       | 0.88%   |
| 2800    | 15       | 0.77%   |
| 1066    | 14       | 0.72%   |
| 3666    | 13       | 0.67%   |
| 4800    | 12       | 0.62%   |
| 3866    | 12       | 0.62%   |
| 5600    | 10       | 0.52%   |
| 5200    | 10       | 0.52%   |
| 6400    | 8        | 0.41%   |
| 3534    | 8        | 0.41%   |
| 3334    | 8        | 0.41%   |
| 3100    | 7        | 0.36%   |
| 1334    | 7        | 0.36%   |
| 3266    | 6        | 0.31%   |
| 2448    | 6        | 0.31%   |
| 3066    | 5        | 0.26%   |
| 333     | 5        | 0.26%   |
| 3500    | 4        | 0.21%   |
| 2048    | 4        | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 54       | 39.42%  |
| Brother Industries    | 24       | 17.52%  |
| Canon                 | 20       | 14.6%   |
| Seiko Epson           | 10       | 7.3%    |
| Samsung Electronics   | 8        | 5.84%   |
| Pantum                | 3        | 2.19%   |
| Apple                 | 3        | 2.19%   |
| Xerox                 | 2        | 1.46%   |
| STMicroelectronics    | 2        | 1.46%   |
| Ricoh                 | 2        | 1.46%   |
| Prolific Technology   | 2        | 1.46%   |
| Zebra                 | 1        | 0.73%   |
| QinHeng Electronics   | 1        | 0.73%   |
| Oki Data              | 1        | 0.73%   |
| Lexmark International | 1        | 0.73%   |
| Graphtec America      | 1        | 0.73%   |
| Dymo-CoStar           | 1        | 0.73%   |
| Dell                  | 1        | 0.73%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                                  | 4        | 2.9%    |
| HP LaserJet 1300                                          | 3        | 2.17%   |
| Apple Gamesir-T1s 2.0b                                    | 3        | 2.17%   |
| Xerox Phaser 3020                                         | 2        | 1.45%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2        | 1.45%   |
| Seiko Epson L6270 Series                                  | 2        | 1.45%   |
| Seiko Epson L120 Series                                   | 2        | 1.45%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.45%   |
| Samsung M2020 Series                                      | 2        | 1.45%   |
| Prolific PL2305 Parallel Port                             | 2        | 1.45%   |
| HP Officejet 2620 series                                  | 2        | 1.45%   |
| HP LaserJet 3020                                          | 2        | 1.45%   |
| HP ENVY 6000 series                                       | 2        | 1.45%   |
| HP DeskJet F4200 series                                   | 2        | 1.45%   |
| HP DeskJet 4530 series                                    | 2        | 1.45%   |
| HP DeskJet 3630 series                                    | 2        | 1.45%   |
| HP DeskJet 2700 series                                    | 2        | 1.45%   |
| HP DeskJet 2620 All-in-One Printer                        | 2        | 1.45%   |
| HP DeskJet 2130 series                                    | 2        | 1.45%   |
| HP Color LaserJet Pro M453-4                              | 2        | 1.45%   |
| Canon PIXMA MX340                                         | 2        | 1.45%   |
| Canon PIXMA MP250                                         | 2        | 1.45%   |
| Canon PIXMA MG2500 Series                                 | 2        | 1.45%   |
| Canon MG5700 series                                       | 2        | 1.45%   |
| Canon LiDE 400                                            | 2        | 1.45%   |
| Canon G3010 series                                        | 2        | 1.45%   |
| Brother HL-5370DW series                                  | 2        | 1.45%   |
| Brother DCP-7040                                          | 2        | 1.45%   |
| Brother DCP-1610W                                         | 2        | 1.45%   |
| Zebra ZTC ZC100                                           | 1        | 0.72%   |
| Seiko Epson XP-4100 Series                                | 1        | 0.72%   |
| Seiko Epson XP-3100 Series                                | 1        | 0.72%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 0.72%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.72%   |
| Seiko Epson L805 Series                                   | 1        | 0.72%   |
| Seiko Epson L3150 Series                                  | 1        | 0.72%   |
| Seiko Epson ET-4760 Series                                | 1        | 0.72%   |
| Samsung ML-216x Series Laser Printer                      | 1        | 0.72%   |
| Samsung ML-1660 Series                                    | 1        | 0.72%   |
| Samsung CLX-3300 Series                                   | 1        | 0.72%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 16       | 55.17%  |
| Seiko Epson        | 7        | 24.14%  |
| Hewlett-Packard    | 2        | 6.9%    |
| Visioneer          | 1        | 3.45%   |
| Ultima Electronics | 1        | 3.45%   |
| Mustek Systems     | 1        | 3.45%   |
| AGFA-Gevaert NV    | 1        | 3.45%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 13.79%  |
| Canon CanoScan LiDE 220                                                               | 3        | 10.34%  |
| Canon CanoScan LiDE 210                                                               | 3        | 10.34%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 6.9%    |
| Canon CanoScan LIDE 25                                                                | 2        | 6.9%    |
| Visioneer OneTouch 5300 USB                                                           | 1        | 3.45%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 3.45%   |
| Seiko Epson Perfection V37/V370                                                       | 1        | 3.45%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 3.45%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 3.45%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 3.45%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 3.45%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 3.45%   |
| HP ScanJet 3500c                                                                      | 1        | 3.45%   |
| HP ScanJet 3400cse                                                                    | 1        | 3.45%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1        | 3.45%   |
| Canon CanoScan LiDE 90                                                                | 1        | 3.45%   |
| Canon CanoScan LiDE 120                                                               | 1        | 3.45%   |
| Canon CanoScan                                                                        | 1        | 3.45%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 3.45%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 306      | 39.64%  |
| Microdia                      | 64       | 8.29%   |
| Microsoft                     | 53       | 6.87%   |
| Samsung Electronics           | 30       | 3.89%   |
| Sunplus Innovation Technology | 27       | 3.5%    |
| Z-Star Microelectronics       | 21       | 2.72%   |
| Creative Technology           | 16       | 2.07%   |
| Apple                         | 14       | 1.81%   |
| MacroSilicon                  | 13       | 1.68%   |
| Generalplus Technology        | 12       | 1.55%   |
| GEMBIRD                       | 12       | 1.55%   |
| Cubeternet                    | 11       | 1.42%   |
| ARC International             | 10       | 1.3%    |
| KYE Systems (Mouse Systems)   | 8        | 1.04%   |
| Chicony Electronics           | 8        | 1.04%   |
| Realtek Semiconductor         | 7        | 0.91%   |
| Razer USA                     | 6        | 0.78%   |
| LG Electronics                | 6        | 0.78%   |
| Google                        | 6        | 0.78%   |
| Genesys Logic                 | 6        | 0.78%   |
| Aveo Technology               | 6        | 0.78%   |
| 2M UVC CAMERA                 | 6        | 0.78%   |
| Valve Software                | 5        | 0.65%   |
| Pixart Imaging                | 5        | 0.65%   |
| Huawei Technologies           | 5        | 0.65%   |
| AVerMedia Technologies        | 5        | 0.65%   |
| Alcor Micro                   | 5        | 0.65%   |
| Sonix Technology              | 4        | 0.52%   |
| Linux Foundation              | 4        | 0.52%   |
| Jieli Technology              | 4        | 0.52%   |
| eMeet                         | 4        | 0.52%   |
| Elgato Systems                | 4        | 0.52%   |
| Arkmicro Technologies         | 4        | 0.52%   |
| Xiongmai                      | 3        | 0.39%   |
| WCM_USB                       | 3        | 0.39%   |
| SunplusIT                     | 3        | 0.39%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.39%   |
| Philips (or NXP)              | 3        | 0.39%   |
| Bison Electronics             | 3        | 0.39%   |
| A4Tech                        | 3        | 0.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 67       | 8.63%   |
| Logitech Webcam C270                                  | 65       | 8.38%   |
| Samsung Galaxy series, misc. (MTP mode)               | 30       | 3.87%   |
| Logitech C922 Pro Stream Webcam                       | 28       | 3.61%   |
| Microsoft LifeCam HD-3000                             | 23       | 2.96%   |
| Microdia Webcam Vitade AF                             | 23       | 2.96%   |
| Microdia USB 2.0 Camera                               | 20       | 2.58%   |
| MacroSilicon USB Video                                | 13       | 1.68%   |
| Logitech Webcam C310                                  | 13       | 1.68%   |
| Logitech HD Webcam C615                               | 13       | 1.68%   |
| Logitech Webcam C170                                  | 12       | 1.55%   |
| Logitech BRIO Ultra HD Webcam                         | 12       | 1.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                    | 12       | 1.55%   |
| Z-Star Venus USB2.0 Camera                            | 11       | 1.42%   |
| Sunplus DICOTA 4K                                     | 10       | 1.29%   |
| Logitech Webcam C930e                                 | 10       | 1.29%   |
| Sunplus Full HD webcam                                | 9        | 1.16%   |
| Logitech HD Webcam C525                               | 9        | 1.16%   |
| ARC International Camera                              | 9        | 1.16%   |
| Generalplus GENERAL WEBCAM                            | 8        | 1.03%   |
| GEMBIRD USB2.0 PC CAMERA                              | 8        | 1.03%   |
| Logitech StreamCam                                    | 7        | 0.9%    |
| Logitech HD Webcam C910                               | 7        | 0.9%    |
| Microsoft LifeCam VX-2000                             | 6        | 0.77%   |
| Logitech Webcam Pro 9000                              | 6        | 0.77%   |
| Logitech HD Webcam C510                               | 6        | 0.77%   |
| Logitech B525 HD Webcam                               | 6        | 0.77%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam                   | 6        | 0.77%   |
| Valve Software 3D Camera                              | 5        | 0.64%   |
| Microsoft LifeCam Cinema                              | 5        | 0.64%   |
| Microdia Camera                                       | 5        | 0.64%   |
| Logitech BRIO 4K Stream Edition                       | 5        | 0.64%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 5        | 0.64%   |
| Huawei HiCamera                                       | 5        | 0.64%   |
| Z-Star Vimicro USB Camera (Altair)                    | 4        | 0.52%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 4        | 0.52%   |
| Microsoft LifeCam Studio                              | 4        | 0.52%   |
| Microdia Integrated Camera                            | 4        | 0.52%   |
| Linux Foundation EEM Gadget                           | 4        | 0.52%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 4        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 30%     |
| LighTuning Technology | 2        | 20%     |
| Validity Sensors      | 1        | 10%     |
| STMicroelectronics    | 1        | 10%     |
| Futronic Technology   | 1        | 10%     |
| Dell                  | 1        | 10%     |
| AuthenTec             | 1        | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]                 | 3        | 30%     |
| LighTuning Fingerprint Sensor                               | 2        | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 10%     |
| STMicroelectronics Fingerprint Reader                       | 1        | 10%     |
| Futronic FS81 Fingerprint Scanner Module                    | 1        | 10%     |
| Dell MS819 Wired Mouse With Fingerprint Reader              | 1        | 10%     |
| AuthenTec AES1600                                           | 1        | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 7        | 22.58%  |
| Alcor Micro                       | 7        | 22.58%  |
| VASCO Data Security International | 4        | 12.9%   |
| Realtek Semiconductor             | 4        | 12.9%   |
| OmniKey                           | 2        | 6.45%   |
| Yubico.com                        | 1        | 3.23%   |
| SCM Microsystems                  | 1        | 3.23%   |
| CHERRY                            | 1        | 3.23%   |
| Bit4id                            | 1        | 3.23%   |
| ASK-RFID                          | 1        | 3.23%   |
| Aladdin Knowledge Systems         | 1        | 3.23%   |
| Aktiv                             | 1        | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 6        | 19.35%  |
| Alcor Micro AU9540 Smartcard Reader                             | 5        | 16.13%  |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 12.9%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 6.45%   |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 6.45%   |
| Alcor Micro Watchdata W 1981                                    | 2        | 6.45%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                 | 1        | 3.23%   |
| VASCO Data Security International DIGIPASS 920                  | 1        | 3.23%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 3.23%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 3.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                | 1        | 3.23%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                     | 1        | 3.23%   |
| Bit4id miniLector EVO                                           | 1        | 3.23%   |
| ASK-RFID GEN5XX CCID                                            | 1        | 3.23%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 3.23%   |
| Aktiv Rutoken lite                                              | 1        | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2770     | 85.57%  |
| 1     | 417      | 12.88%  |
| 2     | 44       | 1.36%   |
| 3     | 5        | 0.15%   |
| 5     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 182      | 36.62%  |
| Graphics card            | 86       | 17.3%   |
| Unassigned class         | 64       | 12.88%  |
| Camera                   | 26       | 5.23%   |
| Chipcard                 | 21       | 4.23%   |
| Multimedia controller    | 18       | 3.62%   |
| Net/ethernet             | 17       | 3.42%   |
| Communication controller | 15       | 3.02%   |
| Sound                    | 13       | 2.62%   |
| Bluetooth                | 12       | 2.41%   |
| Dvb card                 | 10       | 2.01%   |
| Network                  | 9        | 1.81%   |
| Storage/raid             | 8        | 1.61%   |
| Fingerprint reader       | 8        | 1.61%   |
| Tv card                  | 2        | 0.4%    |
| Storage/ide              | 2        | 0.4%    |
| Video                    | 1        | 0.2%    |
| Storage/ata              | 1        | 0.2%    |
| Storage                  | 1        | 0.2%    |
| Modem                    | 1        | 0.2%    |

