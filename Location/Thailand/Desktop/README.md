Linux in Thailand - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

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

Total: 530

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Z270 GAMING M5              | [6cac3c4292](https://linux-hardware.org/?probe=6cac3c4292) | Jan 02, 2026 |
| ASUSTek       | H170-PRO                    | [a8a9697752](https://linux-hardware.org/?probe=a8a9697752) | Jan 02, 2026 |
| Fujitsu       | JIM76YK3                    | [38e37e4978](https://linux-hardware.org/?probe=38e37e4978) | Dec 24, 2025 |
| Fujitsu       | JIM76YK3                    | [65d187f09a](https://linux-hardware.org/?probe=65d187f09a) | Dec 24, 2025 |
| MSI           | MPG X870E CARBON WIFI       | [5b798d9208](https://linux-hardware.org/?probe=5b798d9208) | Dec 23, 2025 |
| MSI           | A520M PRO-VH                | [904442a876](https://linux-hardware.org/?probe=904442a876) | Dec 22, 2025 |
| MSI           | MEG X570 ACE                | [d3c4133215](https://linux-hardware.org/?probe=d3c4133215) | Dec 20, 2025 |
| Dell          | 0N4YC8 A00                  | [ad2dfcd1b6](https://linux-hardware.org/?probe=ad2dfcd1b6) | Dec 13, 2025 |
| Dell          | 0JP3NX A01                  | [72a648b662](https://linux-hardware.org/?probe=72a648b662) | Dec 10, 2025 |
| ASRock        | B550M Steel Legend          | [d483f94145](https://linux-hardware.org/?probe=d483f94145) | Dec 09, 2025 |
| ASRock        | B650M PG Lightning          | [a23007c264](https://linux-hardware.org/?probe=a23007c264) | Dec 07, 2025 |
| Lenovo        | 3704 SDK0Q55756 WIN 3273... | [9b1ccbb763](https://linux-hardware.org/?probe=9b1ccbb763) | Dec 07, 2025 |
| Huanan        | X79 249PC V2.1              | [443e7c4662](https://linux-hardware.org/?probe=443e7c4662) | Dec 06, 2025 |
| Dell          | 0FDY5C A00                  | [e2b445fa22](https://linux-hardware.org/?probe=e2b445fa22) | Dec 06, 2025 |
| MSI           | MPG X870E CARBON WIFI       | [50962e3f4a](https://linux-hardware.org/?probe=50962e3f4a) | Dec 02, 2025 |
| ASUSTek       | P8Z68-V LX                  | [37b7e444e6](https://linux-hardware.org/?probe=37b7e444e6) | Nov 29, 2025 |
| MiTAC         | PD10EHI                     | [d0468751ee](https://linux-hardware.org/?probe=d0468751ee) | Nov 26, 2025 |
| Acer          | Veriton X4630G V:1.0        | [722edb4ffc](https://linux-hardware.org/?probe=722edb4ffc) | Nov 21, 2025 |
| MSI           | PRO B650M-A WIFI            | [a3f7256f32](https://linux-hardware.org/?probe=a3f7256f32) | Nov 14, 2025 |
| MiTAC         | PD10EHI                     | [eef8a0a628](https://linux-hardware.org/?probe=eef8a0a628) | Nov 12, 2025 |
| Dell          | 0T10XW A02                  | [f0dfc6359f](https://linux-hardware.org/?probe=f0dfc6359f) | Nov 06, 2025 |
| Intel         | X99                         | [6e3b113f1e](https://linux-hardware.org/?probe=6e3b113f1e) | Nov 01, 2025 |
| Unknown       | Unknown                     | [ef117f837d](https://linux-hardware.org/?probe=ef117f837d) | Oct 27, 2025 |
| Gigabyte      | X570 AORUS ELITE            | [e1b6411f96](https://linux-hardware.org/?probe=e1b6411f96) | Oct 27, 2025 |
| ASUSTek       | Rampage IV FORMULA          | [602ef1894b](https://linux-hardware.org/?probe=602ef1894b) | Oct 16, 2025 |
| ASUSTek       | Rampage IV FORMULA          | [63ade5755c](https://linux-hardware.org/?probe=63ade5755c) | Oct 16, 2025 |
| AMI           | Intel                       | [c609343d97](https://linux-hardware.org/?probe=c609343d97) | Oct 10, 2025 |
| ASRock        | B850 Pro-A WiFi             | [fbec14ce83](https://linux-hardware.org/?probe=fbec14ce83) | Oct 07, 2025 |
| ASUSTek       | P8H61-M LE                  | [0e2f07ffb0](https://linux-hardware.org/?probe=0e2f07ffb0) | Oct 05, 2025 |
| ASUSTek       | P8H61-M LE                  | [dc7ab616f6](https://linux-hardware.org/?probe=dc7ab616f6) | Oct 05, 2025 |
| ASRock        | H610M-H2/M.2                | [61f654fb96](https://linux-hardware.org/?probe=61f654fb96) | Oct 05, 2025 |
| ASRock        | H610M-H2/M.2                | [91ca51a852](https://linux-hardware.org/?probe=91ca51a852) | Oct 04, 2025 |
| MSI           | PRO Z790-S WIFI             | [ba2a67d6ee](https://linux-hardware.org/?probe=ba2a67d6ee) | Oct 03, 2025 |
| MSI           | PRO Z790-S WIFI             | [25068aa0fd](https://linux-hardware.org/?probe=25068aa0fd) | Oct 02, 2025 |
| Dell          | 0YXT71 A01                  | [ef314092c0](https://linux-hardware.org/?probe=ef314092c0) | Sep 19, 2025 |
| T-bao         | MINI PC V1.0                | [aea3873660](https://linux-hardware.org/?probe=aea3873660) | Sep 15, 2025 |
| ASUSTek       | F1A55-M LX PLUS             | [42633bdec8](https://linux-hardware.org/?probe=42633bdec8) | Sep 12, 2025 |
| Gigabyte      | H97M-D3H                    | [4a89568676](https://linux-hardware.org/?probe=4a89568676) | Sep 02, 2025 |
| MSI           | A320M PRO-VH PLUS           | [68eadaa0d0](https://linux-hardware.org/?probe=68eadaa0d0) | Aug 20, 2025 |
| Acer          | Veriton M490G               | [a40a11bcbd](https://linux-hardware.org/?probe=a40a11bcbd) | Aug 13, 2025 |
| Dell          | 0FDY5C A00                  | [44964b5147](https://linux-hardware.org/?probe=44964b5147) | Aug 11, 2025 |
| AZW           | MINI S 10                   | [faad910f30](https://linux-hardware.org/?probe=faad910f30) | Aug 09, 2025 |
| Gigabyte      | Z890 GAMING X WIFI7         | [09c8808cb4](https://linux-hardware.org/?probe=09c8808cb4) | Aug 01, 2025 |
| OEM           | X79G                        | [f26c9f61af](https://linux-hardware.org/?probe=f26c9f61af) | Jul 21, 2025 |
| Dell          | 0FDY5C A00                  | [5a675c1a27](https://linux-hardware.org/?probe=5a675c1a27) | Jul 20, 2025 |
| OEM           | X79G                        | [50e0c2a875](https://linux-hardware.org/?probe=50e0c2a875) | Jul 13, 2025 |
| HP            | 3397                        | [40e1acdd71](https://linux-hardware.org/?probe=40e1acdd71) | Jul 11, 2025 |
| Gigabyte      | B760M H DDR4                | [f1b3064887](https://linux-hardware.org/?probe=f1b3064887) | Jul 09, 2025 |
| Dell          | 0FDY5C A00                  | [d0260dff30](https://linux-hardware.org/?probe=d0260dff30) | Jul 06, 2025 |
| HP            | 2AF7                        | [897760d1a4](https://linux-hardware.org/?probe=897760d1a4) | Jul 06, 2025 |
| HP            | 2AF7                        | [61af7a9b97](https://linux-hardware.org/?probe=61af7a9b97) | Jul 06, 2025 |
| Dell          | 0HD5W2 A01                  | [c868f28b57](https://linux-hardware.org/?probe=c868f28b57) | Jul 01, 2025 |
| Dell          | 0HD5W2 A01                  | [3c15261113](https://linux-hardware.org/?probe=3c15261113) | Jul 01, 2025 |
| ASRock        | B850 Pro RS WiFi            | [2f2e6d18c9](https://linux-hardware.org/?probe=2f2e6d18c9) | Jun 30, 2025 |
| HP            | 3397                        | [0a48b078c6](https://linux-hardware.org/?probe=0a48b078c6) | Jun 30, 2025 |
| MSI           | MPG B650I EDGE WIFI         | [397b932838](https://linux-hardware.org/?probe=397b932838) | Jun 25, 2025 |
| MiTAC         | PD10EHI                     | [6cca9e4e89](https://linux-hardware.org/?probe=6cca9e4e89) | Jun 23, 2025 |
| Dell          | 040DDP A01                  | [da6531ebf3](https://linux-hardware.org/?probe=da6531ebf3) | Jun 23, 2025 |
| Gigabyte      | X570 AORUS ELITE            | [90756ebb1d](https://linux-hardware.org/?probe=90756ebb1d) | Jun 21, 2025 |
| ASRock        | H170 Pro4                   | [ed0151cf03](https://linux-hardware.org/?probe=ed0151cf03) | Jun 20, 2025 |
| MSI           | H410M PRO-VH                | [042a1bcc08](https://linux-hardware.org/?probe=042a1bcc08) | Jun 20, 2025 |
| HP            | 1497                        | [8b1d2a089b](https://linux-hardware.org/?probe=8b1d2a089b) | Jun 18, 2025 |
| ASUSTek       | PRIME A520M-K               | [73e9ad5501](https://linux-hardware.org/?probe=73e9ad5501) | Jun 16, 2025 |
| ASUSTek       | PRIME A520M-K               | [797a0b684c](https://linux-hardware.org/?probe=797a0b684c) | Jun 16, 2025 |
| Dell          | 0FDY5C A00                  | [c7b1fe7f3c](https://linux-hardware.org/?probe=c7b1fe7f3c) | Jun 12, 2025 |
| AZW           | MINI S 10                   | [7b33ce8247](https://linux-hardware.org/?probe=7b33ce8247) | Jun 12, 2025 |
| ASRock        | A320M-HDV R4.0              | [f9ff00f8e9](https://linux-hardware.org/?probe=f9ff00f8e9) | Jun 12, 2025 |
| ASRock        | A320M-HDV R4.0              | [a2ab28c7cf](https://linux-hardware.org/?probe=a2ab28c7cf) | Jun 10, 2025 |
| Dell          | 0FDY5C A00                  | [d706a0b2cc](https://linux-hardware.org/?probe=d706a0b2cc) | Jun 05, 2025 |
| ASRock        | A320M-HDV                   | [f9bf55893d](https://linux-hardware.org/?probe=f9bf55893d) | May 31, 2025 |
| Intel         | D34010WYK H14771-304        | [2456f2f96a](https://linux-hardware.org/?probe=2456f2f96a) | May 25, 2025 |
| Gigabyte      | 970A-D3P                    | [ee39802eab](https://linux-hardware.org/?probe=ee39802eab) | May 23, 2025 |
| Gigabyte      | H61M-DS2                    | [6d76e9b384](https://linux-hardware.org/?probe=6d76e9b384) | May 08, 2025 |
| ASRock        | H310CM-HDV/M.2 SE           | [df208ebc40](https://linux-hardware.org/?probe=df208ebc40) | May 06, 2025 |
| MSI           | B760M GAMING PLUS WIFI      | [ec6b5c9cd4](https://linux-hardware.org/?probe=ec6b5c9cd4) | May 04, 2025 |
| Acer          | Aspire TC-780               | [bd0e9c6249](https://linux-hardware.org/?probe=bd0e9c6249) | May 04, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [67449ae815](https://linux-hardware.org/?probe=67449ae815) | May 03, 2025 |
| Gigabyte      | F2A88XM-HD3                 | [e6f4fdf96f](https://linux-hardware.org/?probe=e6f4fdf96f) | Apr 29, 2025 |
| Acer          | Aspire TC-780               | [84a56523eb](https://linux-hardware.org/?probe=84a56523eb) | Apr 29, 2025 |
| ASUSTek       | F1A55-M LX PLUS             | [17d18e45a2](https://linux-hardware.org/?probe=17d18e45a2) | Apr 29, 2025 |
| Gigabyte      | Z390 UD                     | [45ec489c61](https://linux-hardware.org/?probe=45ec489c61) | Apr 26, 2025 |
| ASUSTek       | PRIME A520M-K               | [3e459dab89](https://linux-hardware.org/?probe=3e459dab89) | Apr 25, 2025 |
| Acer          | Aspire TC-780               | [0a70185899](https://linux-hardware.org/?probe=0a70185899) | Apr 23, 2025 |
| AMI           | Intel                       | [0bc298db7d](https://linux-hardware.org/?probe=0bc298db7d) | Apr 19, 2025 |
| Fujitsu       | MSH61JP                     | [613aca382d](https://linux-hardware.org/?probe=613aca382d) | Apr 12, 2025 |
| ASUSTek       | M4A77T/USB3                 | [134815140e](https://linux-hardware.org/?probe=134815140e) | Apr 11, 2025 |
| ASUSTek       | M4A77T/USB3                 | [482939e3b5](https://linux-hardware.org/?probe=482939e3b5) | Apr 11, 2025 |
| ASUSTek       | F1A55-M LX PLUS             | [0a979675cf](https://linux-hardware.org/?probe=0a979675cf) | Apr 11, 2025 |
| HP            | 8713                        | [4ded837789](https://linux-hardware.org/?probe=4ded837789) | Apr 02, 2025 |
| Dell          | 02YYK5 A01                  | [448bd03bf0](https://linux-hardware.org/?probe=448bd03bf0) | Apr 02, 2025 |
| Dell          | 02YYK5 A01                  | [80f2a1878e](https://linux-hardware.org/?probe=80f2a1878e) | Apr 02, 2025 |
| Gigabyte      | GA-78LMT-USB3 R2            | [9591932d49](https://linux-hardware.org/?probe=9591932d49) | Mar 27, 2025 |
| MSI           | A68HM-E33 V2                | [f2e463ed70](https://linux-hardware.org/?probe=f2e463ed70) | Mar 18, 2025 |
| Lenovo        | 0x30F617AA NOK              | [3ecccff26d](https://linux-hardware.org/?probe=3ecccff26d) | Feb 25, 2025 |
| HP            | 802F                        | [4e8e61b80d](https://linux-hardware.org/?probe=4e8e61b80d) | Feb 23, 2025 |
| HP            | 802F                        | [6c1bb43f14](https://linux-hardware.org/?probe=6c1bb43f14) | Feb 22, 2025 |
| Dell          | 02YYK5 A00                  | [cfeff84442](https://linux-hardware.org/?probe=cfeff84442) | Feb 20, 2025 |
| Dell          | 02YYK5 A00                  | [a01372ff5b](https://linux-hardware.org/?probe=a01372ff5b) | Feb 20, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [a02d9b1acd](https://linux-hardware.org/?probe=a02d9b1acd) | Feb 17, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [f717eb9902](https://linux-hardware.org/?probe=f717eb9902) | Feb 14, 2025 |
| HP            | ProLiant MicroServer        | [adbe77db46](https://linux-hardware.org/?probe=adbe77db46) | Feb 13, 2025 |
| ASRock        | B450 Steel Legend           | [a53ef15961](https://linux-hardware.org/?probe=a53ef15961) | Feb 12, 2025 |
| Gigabyte      | B650M DS3H                  | [75dd0b7f14](https://linux-hardware.org/?probe=75dd0b7f14) | Feb 09, 2025 |
| Unknown       | Unknown                     | [c71f336b50](https://linux-hardware.org/?probe=c71f336b50) | Feb 06, 2025 |
| Gigabyte      | H110M-DS2-CF                | [d746ea1c0c](https://linux-hardware.org/?probe=d746ea1c0c) | Jan 30, 2025 |
| Gigabyte      | H97M-D3H                    | [d1c02c66a7](https://linux-hardware.org/?probe=d1c02c66a7) | Jan 27, 2025 |
| AZW           | MINI S 10                   | [384628cf02](https://linux-hardware.org/?probe=384628cf02) | Jan 25, 2025 |
| Gigabyte      | X570 UD                     | [a4d1571f26](https://linux-hardware.org/?probe=a4d1571f26) | Jan 11, 2025 |
| T-bao         | MINI PC V1.0                | [ce27bbd33e](https://linux-hardware.org/?probe=ce27bbd33e) | Jan 10, 2025 |
| ASRock        | B450 Steel Legend           | [4fd31b0d22](https://linux-hardware.org/?probe=4fd31b0d22) | Jan 08, 2025 |
| ASRock        | B450 Steel Legend           | [5320a7c488](https://linux-hardware.org/?probe=5320a7c488) | Dec 27, 2024 |
| MiTAC         | PD10EHI                     | [0879837e1b](https://linux-hardware.org/?probe=0879837e1b) | Dec 24, 2024 |
| MiTAC         | PD10EHI                     | [677c9d3ee3](https://linux-hardware.org/?probe=677c9d3ee3) | Dec 18, 2024 |
| Intel         | X99                         | [1a147ad6e0](https://linux-hardware.org/?probe=1a147ad6e0) | Dec 16, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [7aebeb376d](https://linux-hardware.org/?probe=7aebeb376d) | Dec 14, 2024 |
| ASUSTek       | M5A78L-M LX V2              | [94bf662079](https://linux-hardware.org/?probe=94bf662079) | Dec 11, 2024 |
| Gigabyte      | EP45-UD3R                   | [dbee87ee50](https://linux-hardware.org/?probe=dbee87ee50) | Dec 10, 2024 |
| ASRock        | A520M-HVS                   | [13eb428010](https://linux-hardware.org/?probe=13eb428010) | Dec 01, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [74716c6624](https://linux-hardware.org/?probe=74716c6624) | Nov 28, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [b5f2062c2c](https://linux-hardware.org/?probe=b5f2062c2c) | Nov 18, 2024 |
| MSI           | B365M PRO-VDH               | [82d0c85a4c](https://linux-hardware.org/?probe=82d0c85a4c) | Nov 12, 2024 |
| MiTAC         | PD10EHI                     | [378a9691e4](https://linux-hardware.org/?probe=378a9691e4) | Nov 09, 2024 |
| Lenovo        | 31900059 STD                | [eb4e9fd174](https://linux-hardware.org/?probe=eb4e9fd174) | Oct 31, 2024 |
| Gigabyte      | Z77X-D3H                    | [566d913cf0](https://linux-hardware.org/?probe=566d913cf0) | Oct 31, 2024 |
| ASRock        | X570 Pro4                   | [aeb453702e](https://linux-hardware.org/?probe=aeb453702e) | Oct 25, 2024 |
| HP            | 1497                        | [f60b700334](https://linux-hardware.org/?probe=f60b700334) | Oct 21, 2024 |
| ASRock        | B550 Steel Legend           | [c4ffd7734d](https://linux-hardware.org/?probe=c4ffd7734d) | Oct 19, 2024 |
| Gigabyte      | Z77X-D3H                    | [3113b0c26d](https://linux-hardware.org/?probe=3113b0c26d) | Oct 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [627376d603](https://linux-hardware.org/?probe=627376d603) | Oct 17, 2024 |
| Dell          | 0C3YXR A01                  | [702872562a](https://linux-hardware.org/?probe=702872562a) | Oct 15, 2024 |
| HP            | 802F                        | [2678cdc4b4](https://linux-hardware.org/?probe=2678cdc4b4) | Oct 10, 2024 |
| MiTAC         | PD10EHI                     | [d3d62dd202](https://linux-hardware.org/?probe=d3d62dd202) | Oct 03, 2024 |
| ASUSTek       | PRIME A320M-K               | [4c14174367](https://linux-hardware.org/?probe=4c14174367) | Sep 29, 2024 |
| ASUSTek       | PRIME A320M-K               | [b5dd25d1cb](https://linux-hardware.org/?probe=b5dd25d1cb) | Sep 28, 2024 |
| ASRock        | B450 Steel Legend           | [2f3706f0c5](https://linux-hardware.org/?probe=2f3706f0c5) | Sep 21, 2024 |
| HP            | 802F                        | [8f5648baef](https://linux-hardware.org/?probe=8f5648baef) | Sep 20, 2024 |
| ASRock        | B450 Steel Legend           | [068811de2e](https://linux-hardware.org/?probe=068811de2e) | Sep 19, 2024 |
| HP            | 8298                        | [33696766f2](https://linux-hardware.org/?probe=33696766f2) | Sep 15, 2024 |
| ASUSTek       | PRIME H610M-E D4            | [c6d88ef79f](https://linux-hardware.org/?probe=c6d88ef79f) | Sep 13, 2024 |
| Gigabyte      | B650M DS3H                  | [2f3b657d09](https://linux-hardware.org/?probe=2f3b657d09) | Sep 09, 2024 |
| ASUSTek       | H61M-A/USB3                 | [727745c91c](https://linux-hardware.org/?probe=727745c91c) | Sep 09, 2024 |
| ASUSTek       | Maximus VI HERO             | [64da4e01a4](https://linux-hardware.org/?probe=64da4e01a4) | Sep 07, 2024 |
| Gigabyte      | B650M DS3H                  | [9214328551](https://linux-hardware.org/?probe=9214328551) | Sep 05, 2024 |
| JINGSHA       | B85M-I                      | [0ec5002083](https://linux-hardware.org/?probe=0ec5002083) | Aug 31, 2024 |
| JINGSHA       | B85M-I                      | [d7094aabed](https://linux-hardware.org/?probe=d7094aabed) | Aug 21, 2024 |
| ASUSTek       | M5A78L-M LE/USB3            | [90f8587ff4](https://linux-hardware.org/?probe=90f8587ff4) | Aug 09, 2024 |
| Lenovo        | 315F NO DPK                 | [f2ab02a574](https://linux-hardware.org/?probe=f2ab02a574) | Aug 04, 2024 |
| Lenovo        | 315F NO DPK                 | [f5da233c67](https://linux-hardware.org/?probe=f5da233c67) | Aug 04, 2024 |
| MSI           | Z270 GAMING M5              | [c094b9de0f](https://linux-hardware.org/?probe=c094b9de0f) | Aug 02, 2024 |
| Intel         | X99-P4 V5.1                 | [def260ec4e](https://linux-hardware.org/?probe=def260ec4e) | Jul 28, 2024 |
| Gigabyte      | H61M-DS2                    | [31381d6558](https://linux-hardware.org/?probe=31381d6558) | Jul 22, 2024 |
| Dell          | 0T7D40 A00                  | [bea004e3ba](https://linux-hardware.org/?probe=bea004e3ba) | Jul 20, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [77d830aa2e](https://linux-hardware.org/?probe=77d830aa2e) | Jul 12, 2024 |
| HP            | 802F                        | [287eec5051](https://linux-hardware.org/?probe=287eec5051) | Jul 08, 2024 |
| ASUSTek       | H97-PRO GAMER               | [5cef5a4211](https://linux-hardware.org/?probe=5cef5a4211) | Jul 07, 2024 |
| Shenzhen M... | DRFXI                       | [d5d17b7674](https://linux-hardware.org/?probe=d5d17b7674) | Jul 03, 2024 |
| Acer          | Veriton N4640G              | [316499457a](https://linux-hardware.org/?probe=316499457a) | Jul 01, 2024 |
| AMI           | Intel                       | [aefdd71c5e](https://linux-hardware.org/?probe=aefdd71c5e) | May 18, 2024 |
| HP            | 1998                        | [7d652e5edc](https://linux-hardware.org/?probe=7d652e5edc) | May 13, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | [92d8a990de](https://linux-hardware.org/?probe=92d8a990de) | Apr 29, 2024 |
| Dell          | 088DT1 A01                  | [0d725519b9](https://linux-hardware.org/?probe=0d725519b9) | Apr 29, 2024 |
| ASRock        | B450 Steel Legend           | [eae63cf682](https://linux-hardware.org/?probe=eae63cf682) | Apr 15, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [11963d204b](https://linux-hardware.org/?probe=11963d204b) | Mar 21, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [908360069c](https://linux-hardware.org/?probe=908360069c) | Mar 21, 2024 |
| Gigabyte      | H81M-DS2                    | [dde5a90821](https://linux-hardware.org/?probe=dde5a90821) | Mar 12, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | [3890a0c9b5](https://linux-hardware.org/?probe=3890a0c9b5) | Mar 09, 2024 |
| Gigabyte      | H61M-DS2                    | [68d8ddbe50](https://linux-hardware.org/?probe=68d8ddbe50) | Mar 04, 2024 |
| ASRock        | X299 Taichi                 | [5a5309bb52](https://linux-hardware.org/?probe=5a5309bb52) | Mar 03, 2024 |
| ASUSTek       | P8Z77-V LX                  | [dae19ec723](https://linux-hardware.org/?probe=dae19ec723) | Feb 18, 2024 |
| Dell          | 08WKV3 A00                  | [5bff5d79c2](https://linux-hardware.org/?probe=5bff5d79c2) | Feb 16, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [0fbc4b07a6](https://linux-hardware.org/?probe=0fbc4b07a6) | Feb 12, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c7ad65ef28](https://linux-hardware.org/?probe=c7ad65ef28) | Feb 10, 2024 |
| Dell          | 0VFD52 A00                  | [cc2714d2cf](https://linux-hardware.org/?probe=cc2714d2cf) | Feb 07, 2024 |
| MSI           | X99A SLI PLUS               | [216026fc45](https://linux-hardware.org/?probe=216026fc45) | Jan 30, 2024 |
| ASRock        | H470 Phantom Gaming 4       | [dc402c3f43](https://linux-hardware.org/?probe=dc402c3f43) | Jan 27, 2024 |
| Gigabyte      | B560M AORUS PRO             | [93137ffd8d](https://linux-hardware.org/?probe=93137ffd8d) | Jan 21, 2024 |
| Gigabyte      | H310M DS2 x.x               | [dcbb993ea5](https://linux-hardware.org/?probe=dcbb993ea5) | Jan 18, 2024 |
| ASRock        | B450 Steel Legend           | [d01ee5a226](https://linux-hardware.org/?probe=d01ee5a226) | Jan 02, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [19be3bdc5b](https://linux-hardware.org/?probe=19be3bdc5b) | Dec 31, 2023 |
| HP            | 82B4                        | [02bcf6a9d1](https://linux-hardware.org/?probe=02bcf6a9d1) | Dec 31, 2023 |
| Gigabyte      | H310M DS2 x.x               | [47c95a8cc5](https://linux-hardware.org/?probe=47c95a8cc5) | Dec 26, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [518e259c3c](https://linux-hardware.org/?probe=518e259c3c) | Dec 23, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [3dee3cb4bf](https://linux-hardware.org/?probe=3dee3cb4bf) | Dec 19, 2023 |
| ASRock        | B550M Pro4                  | [a32cb7798b](https://linux-hardware.org/?probe=a32cb7798b) | Dec 19, 2023 |
| Dell          | 0HD5W2 A01                  | [cf61f7b65b](https://linux-hardware.org/?probe=cf61f7b65b) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [7866cd7449](https://linux-hardware.org/?probe=7866cd7449) | Dec 16, 2023 |
| MSI           | B450 TOMAHAWK               | [8e66dfbc28](https://linux-hardware.org/?probe=8e66dfbc28) | Dec 12, 2023 |
| Intel         | X99                         | [6988251bb1](https://linux-hardware.org/?probe=6988251bb1) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| ASRock        | B550M Steel Legend          | [eac155f5e6](https://linux-hardware.org/?probe=eac155f5e6) | Dec 08, 2023 |
| MSI           | B450 TOMAHAWK               | [254b936002](https://linux-hardware.org/?probe=254b936002) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [fa61806ea8](https://linux-hardware.org/?probe=fa61806ea8) | Dec 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4552c13bb1](https://linux-hardware.org/?probe=4552c13bb1) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | [284f7d2451](https://linux-hardware.org/?probe=284f7d2451) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [420d9baddf](https://linux-hardware.org/?probe=420d9baddf) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [ab7e55f5b9](https://linux-hardware.org/?probe=ab7e55f5b9) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [9d8548f39a](https://linux-hardware.org/?probe=9d8548f39a) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [36763f453f](https://linux-hardware.org/?probe=36763f453f) | Nov 13, 2023 |
| Google        | Panther                     | [bd2af6ba92](https://linux-hardware.org/?probe=bd2af6ba92) | Nov 13, 2023 |
| HP            | 802F                        | [e5d90a5987](https://linux-hardware.org/?probe=e5d90a5987) | Nov 09, 2023 |
| Gigabyte      | A520M S2H                   | [701d46485b](https://linux-hardware.org/?probe=701d46485b) | Nov 09, 2023 |
| ASRock        | B550M Steel Legend          | [f123c19bb4](https://linux-hardware.org/?probe=f123c19bb4) | Oct 30, 2023 |
| Gigabyte      | H61MA-D3V                   | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| HP            | 802F                        | [d01e0550a3](https://linux-hardware.org/?probe=d01e0550a3) | Oct 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [e44d1b7e3c](https://linux-hardware.org/?probe=e44d1b7e3c) | Oct 14, 2023 |
| AMI           | Intel                       | [888a4e1a0f](https://linux-hardware.org/?probe=888a4e1a0f) | Oct 13, 2023 |
| ASRock        | H81M-DGS R2.0               | [4bb18fddab](https://linux-hardware.org/?probe=4bb18fddab) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [423d2de75a](https://linux-hardware.org/?probe=423d2de75a) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [cce7c03059](https://linux-hardware.org/?probe=cce7c03059) | Sep 29, 2023 |
| Dell          | 00V62H A01                  | [f46006f6ce](https://linux-hardware.org/?probe=f46006f6ce) | Sep 28, 2023 |
| MiTAC         | PD10EHI                     | [29716ecb18](https://linux-hardware.org/?probe=29716ecb18) | Sep 27, 2023 |
| Dell          | 0D4MD1 A04                  | [5e6e35397a](https://linux-hardware.org/?probe=5e6e35397a) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [4d7943532f](https://linux-hardware.org/?probe=4d7943532f) | Sep 24, 2023 |
| Dell          | 0NW6H5 A00                  | [7df92bb8f5](https://linux-hardware.org/?probe=7df92bb8f5) | Sep 22, 2023 |
| Intel         | DN2820FYK H24582-204        | [bec0346d1d](https://linux-hardware.org/?probe=bec0346d1d) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Acer          | Veriton N4640G              | [73af90ca23](https://linux-hardware.org/?probe=73af90ca23) | Sep 16, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| Dell          | 048DY8 A00                  | [3cc67a5e62](https://linux-hardware.org/?probe=3cc67a5e62) | Sep 15, 2023 |
| Google        | Panther                     | [1adc816fcb](https://linux-hardware.org/?probe=1adc816fcb) | Sep 12, 2023 |
| Biostar       | TB360-BTC Expert            | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| Dell          | 088DT1 A00                  | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Acer          | Veriton N4640G              | [4ad00f4c17](https://linux-hardware.org/?probe=4ad00f4c17) | Sep 10, 2023 |
| Lenovo        | SHARKBAY NOK                | [a09c6ad4a9](https://linux-hardware.org/?probe=a09c6ad4a9) | Sep 08, 2023 |
| Biostar       | TB360-BTC Expert            | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [9d45d79cb0](https://linux-hardware.org/?probe=9d45d79cb0) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASRock        | NF6-GLAN                    | [80d9233886](https://linux-hardware.org/?probe=80d9233886) | Sep 04, 2023 |
| ViewSonic     | VPC14-WP                    | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| ECS           | A780GM-A                    | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HP            | 802F                        | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| Acer          | Veriton N4640G              | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| ASRock        | B450 Steel Legend           | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| MiTAC         | PD10EHI                     | [972fe64be0](https://linux-hardware.org/?probe=972fe64be0) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c711cf46d7](https://linux-hardware.org/?probe=c711cf46d7) | Aug 14, 2023 |
| Dell          | 0HY9JP A01                  | [48d92d85c7](https://linux-hardware.org/?probe=48d92d85c7) | Aug 11, 2023 |
| HP            | 304Ah                       | [81682ebb2d](https://linux-hardware.org/?probe=81682ebb2d) | Jul 20, 2023 |
| Gigabyte      | P75-D3P                     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| Apple         | Mac-F221BEC8                | [83e08e8aca](https://linux-hardware.org/?probe=83e08e8aca) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| HP            | 802F                        | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| HP            | 802F                        | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| ASRock        | B450 Steel Legend           | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| Lenovo        | SHARKBAY NOK                | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| ASRock        | B450 Steel Legend           | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| Dell          | 07WP95 A01                  | [b9f3afed0c](https://linux-hardware.org/?probe=b9f3afed0c) | May 31, 2023 |
| ASRock        | B450M Steel Legend          | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| Dell          | 07WP95 A01                  | [a58adc500e](https://linux-hardware.org/?probe=a58adc500e) | May 30, 2023 |
| Lenovo        | SHARKBAY NOK                | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| Lenovo        | 313A NOK                    | [a1ffbc1e1e](https://linux-hardware.org/?probe=a1ffbc1e1e) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| Gigabyte      | A520M S2H                   | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| Acer          | Veriton M2610G              | [001e547ddf](https://linux-hardware.org/?probe=001e547ddf) | May 18, 2023 |
| ASUSTek       | D320SF                      | [bbfd29fb88](https://linux-hardware.org/?probe=bbfd29fb88) | May 08, 2023 |
| ASUSTek       | D320SF                      | [fdb3953309](https://linux-hardware.org/?probe=fdb3953309) | May 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [e35b234e43](https://linux-hardware.org/?probe=e35b234e43) | May 07, 2023 |
| Dell          | 0YXT71 A01                  | [bbe145a1a2](https://linux-hardware.org/?probe=bbe145a1a2) | May 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [2ebe14f5d0](https://linux-hardware.org/?probe=2ebe14f5d0) | May 04, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [71bf54960f](https://linux-hardware.org/?probe=71bf54960f) | May 02, 2023 |
| Dell          | 040DDP A01                  | [bb212aa105](https://linux-hardware.org/?probe=bb212aa105) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | [2b839be032](https://linux-hardware.org/?probe=2b839be032) | Apr 19, 2023 |
| Lenovo        | No DPK                      | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| ASRock        | B450 Steel Legend           | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| Acer          | Veriton N4630G              | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| ASUSTek       | PRIME B550M-K               | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| HP            | 802F                        | [89dadeeea6](https://linux-hardware.org/?probe=89dadeeea6) | Mar 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [fda0ab85e6](https://linux-hardware.org/?probe=fda0ab85e6) | Mar 18, 2023 |
| ASUSTek       | Z97-K R2.0                  | [8c266d3142](https://linux-hardware.org/?probe=8c266d3142) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [9f33a01f8d](https://linux-hardware.org/?probe=9f33a01f8d) | Mar 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [2a40386fb8](https://linux-hardware.org/?probe=2a40386fb8) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [89194cffbe](https://linux-hardware.org/?probe=89194cffbe) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| Acer          | Aspire TC-390               | [2d092d008e](https://linux-hardware.org/?probe=2d092d008e) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASRock        | G41M-GS3                    | [388f28c258](https://linux-hardware.org/?probe=388f28c258) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| Dell          | 088DT1 A01                  | [715d043ec7](https://linux-hardware.org/?probe=715d043ec7) | Mar 01, 2023 |
| HP            | 1998                        | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| Dell          | 088DT1 A01                  | [990ffa68f4](https://linux-hardware.org/?probe=990ffa68f4) | Feb 23, 2023 |
| Dell          | 088DT1 A01                  | [73dde5b3db](https://linux-hardware.org/?probe=73dde5b3db) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| Supermicro    | X10DRiB                     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| Dell          | 040DDP A01                  | [6094b799d7](https://linux-hardware.org/?probe=6094b799d7) | Jan 31, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [0fc911e254](https://linux-hardware.org/?probe=0fc911e254) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Dell          | 054KM3 A00                  | [4ea59c00f3](https://linux-hardware.org/?probe=4ea59c00f3) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [e6ecb9037e](https://linux-hardware.org/?probe=e6ecb9037e) | Jan 10, 2023 |
| Gigabyte      | B650M DS3H                  | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| HP            | 802F                        | [22444b4b2c](https://linux-hardware.org/?probe=22444b4b2c) | Dec 31, 2022 |
| Gigabyte      | H61M-DS2                    | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [2e23d15c25](https://linux-hardware.org/?probe=2e23d15c25) | Dec 24, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| Gigabyte      | P75-D3P                     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| Gigabyte      | 970A-D3                     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | H81M-C                      | [8b44a7deaa](https://linux-hardware.org/?probe=8b44a7deaa) | Nov 21, 2022 |
| ASUSTek       | H81M-C                      | [e60a1f8fc4](https://linux-hardware.org/?probe=e60a1f8fc4) | Nov 20, 2022 |
| HP            | 82F2 A01                    | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| ASRock        | B550M-ITX/ac                | [685e484cbd](https://linux-hardware.org/?probe=685e484cbd) | Aug 31, 2022 |
| Dell          | 0773VG A00                  | [576dfabbf6](https://linux-hardware.org/?probe=576dfabbf6) | Aug 29, 2022 |
| OEM           | Intel H81                   | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| OEM           | Intel H81                   | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| Gigabyte      | H81M-DS2                    | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Gigabyte      | H81M-DS2                    | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| HP            | 8062                        | [0f24b44d56](https://linux-hardware.org/?probe=0f24b44d56) | Aug 14, 2022 |
| Dell          | 088DT1 A01                  | [eab28163ce](https://linux-hardware.org/?probe=eab28163ce) | Aug 09, 2022 |
| SHARKBAY      | Unknown                     | [a35fff735f](https://linux-hardware.org/?probe=a35fff735f) | Aug 09, 2022 |
| ASUSTek       | ROG Maximus X APEX          | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [334719e6a2](https://linux-hardware.org/?probe=334719e6a2) | Jun 30, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| AFOX          | AF IH81-MA3 V1.0            | [4ce7ccc125](https://linux-hardware.org/?probe=4ce7ccc125) | Jun 24, 2022 |
| Dell          | 04YP6J A02                  | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Gigabyte      | H310M S2H x.x               | [1cc4490d99](https://linux-hardware.org/?probe=1cc4490d99) | Jun 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [e3bb4dee4b](https://linux-hardware.org/?probe=e3bb4dee4b) | Jun 17, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [3dbf1858d0](https://linux-hardware.org/?probe=3dbf1858d0) | May 27, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Intel         | D54250WYK H13922-305        | [6d1745c79b](https://linux-hardware.org/?probe=6d1745c79b) | May 11, 2022 |
| Dell          | 00V62H A00                  | [e765b34181](https://linux-hardware.org/?probe=e765b34181) | May 11, 2022 |
| HP            | 18E7                        | [52a59840d8](https://linux-hardware.org/?probe=52a59840d8) | May 09, 2022 |
| ASRock        | H370 Pro4                   | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| ASUSTek       | H81M-E                      | [b485d8f932](https://linux-hardware.org/?probe=b485d8f932) | Apr 28, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [be1e468728](https://linux-hardware.org/?probe=be1e468728) | Apr 17, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| Gigabyte      | GA-970A-DS3                 | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | B450M S2H                   | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| ASRock        | B450 Steel Legend           | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7a484a0d61](https://linux-hardware.org/?probe=7a484a0d61) | Mar 11, 2022 |
| ASRock        | H410M-HDV R2.0              | [0c91f1563f](https://linux-hardware.org/?probe=0c91f1563f) | Feb 14, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [9544722d31](https://linux-hardware.org/?probe=9544722d31) | Feb 12, 2022 |
| ASUSTek       | Z170-K                      | [ad24d41607](https://linux-hardware.org/?probe=ad24d41607) | Feb 08, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| HP            | 1998                        | [263c4b1a93](https://linux-hardware.org/?probe=263c4b1a93) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| HP            | 82B4                        | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| ASRock        | M3A770DE                    | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| ASRock        | M3A770DE                    | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| HP            | 82B4                        | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| ASRock        | H510M-HVS R2.0              | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| MiTAC         | PD14RI                      | [e4dc1c326a](https://linux-hardware.org/?probe=e4dc1c326a) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| MSI           | Boston                      | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| ASRock        | M3A770DE                    | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| MiTAC         | PD14RI                      | [acf3343fe7](https://linux-hardware.org/?probe=acf3343fe7) | Dec 13, 2021 |
| Gigabyte      | GA-970A-DS3                 | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| Dell          | 0YXT71 A02                  | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [3bf6f778dc](https://linux-hardware.org/?probe=3bf6f778dc) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [f873a240d5](https://linux-hardware.org/?probe=f873a240d5) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [71820e1f85](https://linux-hardware.org/?probe=71820e1f85) | Sep 18, 2021 |
| Gigabyte      | F2A68HM-DS2                 | [8ab840927b](https://linux-hardware.org/?probe=8ab840927b) | Sep 17, 2021 |
| HP            | 1497                        | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASRock        | 880GM-LE FX                 | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [04e6db02f9](https://linux-hardware.org/?probe=04e6db02f9) | Sep 02, 2021 |
| ASUSTek       | M2N68-AM Plus               | [57b648bd45](https://linux-hardware.org/?probe=57b648bd45) | Aug 23, 2021 |
| VIA Techno... | EITX-3002                   | [db8b46aea5](https://linux-hardware.org/?probe=db8b46aea5) | Aug 21, 2021 |
| ASUSTek       | H81M-A                      | [ae7b04d5d3](https://linux-hardware.org/?probe=ae7b04d5d3) | Aug 12, 2021 |
| Dell          | 0D24M8 A00                  | [c56bb51edc](https://linux-hardware.org/?probe=c56bb51edc) | Aug 03, 2021 |
| ASRock        | B450M Steel Legend          | [73a47bf698](https://linux-hardware.org/?probe=73a47bf698) | Aug 02, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [71aae9e020](https://linux-hardware.org/?probe=71aae9e020) | Jul 26, 2021 |
| Dell          | 0NK5PH A00                  | [3db5dd7ea0](https://linux-hardware.org/?probe=3db5dd7ea0) | Jul 26, 2021 |
| ASRock        | B450M Steel Legend          | [b1d25f1e88](https://linux-hardware.org/?probe=b1d25f1e88) | Jul 22, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [568a71080e](https://linux-hardware.org/?probe=568a71080e) | Jul 21, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [6bf04f98f6](https://linux-hardware.org/?probe=6bf04f98f6) | Jul 21, 2021 |
| MSI           | MEG X570 UNIFY              | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| ASRock        | H81M-HDS R2.0               | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | B450M Steel Legend          | [c298371b89](https://linux-hardware.org/?probe=c298371b89) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| ASRock        | H110M-DVS R3.0              | [2c6fd223a1](https://linux-hardware.org/?probe=2c6fd223a1) | Jul 07, 2021 |
| ASRock        | H110M-DVS R3.0              | [1270256228](https://linux-hardware.org/?probe=1270256228) | Jul 07, 2021 |
| Gigabyte      | H370M D3H-CF                | [e8c3804e26](https://linux-hardware.org/?probe=e8c3804e26) | Jun 25, 2021 |
| MSI           | B450M MORTAR MAX            | [db886610f5](https://linux-hardware.org/?probe=db886610f5) | Jun 11, 2021 |
| MSI           | A320M-A PRO MAX             | [45b8d7ca02](https://linux-hardware.org/?probe=45b8d7ca02) | Jun 08, 2021 |
| Intel         | H61M S1                     | [f60c55c8c4](https://linux-hardware.org/?probe=f60c55c8c4) | May 27, 2021 |
| Acer          | Veriton X2665G              | [f23ed8abd1](https://linux-hardware.org/?probe=f23ed8abd1) | Apr 20, 2021 |
| Huanan        | X79 249PC V2.2              | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| ASRock        | G31M-S                      | [ee71002286](https://linux-hardware.org/?probe=ee71002286) | Mar 26, 2021 |
| Huanan        | X79 V6.11                   | [85cbe2c1ed](https://linux-hardware.org/?probe=85cbe2c1ed) | Mar 16, 2021 |
| ASRock        | M3A770DE                    | [bca1dbaafd](https://linux-hardware.org/?probe=bca1dbaafd) | Mar 10, 2021 |
| ASRock        | B450M Steel Legend          | [465d5f43f1](https://linux-hardware.org/?probe=465d5f43f1) | Mar 08, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Gigabyte      | Z490 UD                     | [ec3e24bbcc](https://linux-hardware.org/?probe=ec3e24bbcc) | Mar 02, 2021 |
| Gigabyte      | F2A75M-HD2                  | [d8037b520e](https://linux-hardware.org/?probe=d8037b520e) | Feb 26, 2021 |
| Gigabyte      | H110M-DS2-CF                | [f1e66dfcc2](https://linux-hardware.org/?probe=f1e66dfcc2) | Feb 22, 2021 |
| ASUSTek       | P7P55D EVO                  | [90a83f66fc](https://linux-hardware.org/?probe=90a83f66fc) | Feb 21, 2021 |
| HP            | 1998                        | [c415742b9e](https://linux-hardware.org/?probe=c415742b9e) | Feb 13, 2021 |
| Dell          | 0F8096                      | [d6748871e7](https://linux-hardware.org/?probe=d6748871e7) | Feb 13, 2021 |
| Gigabyte      | H67MA-USB3-B3               | [bd0fcefe9f](https://linux-hardware.org/?probe=bd0fcefe9f) | Feb 13, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Dell          | 0F8096                      | [d6ce430a08](https://linux-hardware.org/?probe=d6ce430a08) | Feb 04, 2021 |
| Gigabyte      | G41M-ES2H                   | [53c32c80a6](https://linux-hardware.org/?probe=53c32c80a6) | Feb 03, 2021 |
| Acer          | Aspire M1935                | [64d53ff0ad](https://linux-hardware.org/?probe=64d53ff0ad) | Jan 28, 2021 |
| Fujitsu       | JIM76YK3                    | [4c5225559f](https://linux-hardware.org/?probe=4c5225559f) | Jan 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [6ba43f198a](https://linux-hardware.org/?probe=6ba43f198a) | Jan 22, 2021 |
| Fujitsu       | JIM76YK3                    | [b33ad621e1](https://linux-hardware.org/?probe=b33ad621e1) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | [26d33eb0de](https://linux-hardware.org/?probe=26d33eb0de) | Jan 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [9bcae82db8](https://linux-hardware.org/?probe=9bcae82db8) | Dec 16, 2020 |
| ASUSTek       | PRIME A320M-K               | [039b541097](https://linux-hardware.org/?probe=039b541097) | Dec 16, 2020 |
| ASRock        | Z390 Pro4                   | [3befcf341c](https://linux-hardware.org/?probe=3befcf341c) | Dec 14, 2020 |
| ASUSTek       | Z87-PRO                     | [a5170be239](https://linux-hardware.org/?probe=a5170be239) | Dec 11, 2020 |
| ASUSTek       | P8H61-M LE                  | [86f61c5fce](https://linux-hardware.org/?probe=86f61c5fce) | Dec 11, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [813b0a40eb](https://linux-hardware.org/?probe=813b0a40eb) | Dec 01, 2020 |
| Unknown       | Unknown                     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| ASRock        | Z270 Killer SLI             | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| Gigabyte      | F2A85XM-HD3                 | [4a8bc27a98](https://linux-hardware.org/?probe=4a8bc27a98) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [924b361628](https://linux-hardware.org/?probe=924b361628) | Oct 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [cce759037c](https://linux-hardware.org/?probe=cce759037c) | Oct 01, 2020 |
| ASUSTek       | P8H61-M LE                  | [93a29298d7](https://linux-hardware.org/?probe=93a29298d7) | Sep 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [c9ece9190b](https://linux-hardware.org/?probe=c9ece9190b) | Sep 27, 2020 |
| ASRock        | B460M Steel Legend          | [5398b2247d](https://linux-hardware.org/?probe=5398b2247d) | Sep 12, 2020 |
| ASRock        | B460M Steel Legend          | [44abe999aa](https://linux-hardware.org/?probe=44abe999aa) | Sep 12, 2020 |
| ASUSTek       | H110M-E/M.2                 | [25c77e6927](https://linux-hardware.org/?probe=25c77e6927) | Sep 11, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2b4fe70eaf](https://linux-hardware.org/?probe=2b4fe70eaf) | Sep 04, 2020 |
| ASRock        | B450M Steel Legend          | [2aa3eef6bd](https://linux-hardware.org/?probe=2aa3eef6bd) | Sep 02, 2020 |
| Dell          | 0X8DXD A01                  | [0c6362ecb0](https://linux-hardware.org/?probe=0c6362ecb0) | Aug 24, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | Z77 Extreme6                | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| Gigabyte      | 970A-DS3P                   | [211cb85a6f](https://linux-hardware.org/?probe=211cb85a6f) | Aug 08, 2020 |
| ASRock        | B450 Pro4                   | [c318976f19](https://linux-hardware.org/?probe=c318976f19) | Jul 26, 2020 |
| Gigabyte      | P67A-UD3P-B3                | [d68a3e43ab](https://linux-hardware.org/?probe=d68a3e43ab) | Jul 25, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f395c86ea3](https://linux-hardware.org/?probe=f395c86ea3) | Jul 05, 2020 |
| ASUSTek       | H61M-D                      | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | S340MF                      | [e8b7344421](https://linux-hardware.org/?probe=e8b7344421) | Jun 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | [262f40d535](https://linux-hardware.org/?probe=262f40d535) | Jun 20, 2020 |
| Gigabyte      | Z390 UD                     | [1bd38851f2](https://linux-hardware.org/?probe=1bd38851f2) | Jun 13, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [79456b5994](https://linux-hardware.org/?probe=79456b5994) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [f839493f2c](https://linux-hardware.org/?probe=f839493f2c) | Jun 05, 2020 |
| ASUSTek       | Z170-P D3                   | [859b71baa9](https://linux-hardware.org/?probe=859b71baa9) | Jun 01, 2020 |
| ASUSTek       | Z170-P D3                   | [2c3fadf526](https://linux-hardware.org/?probe=2c3fadf526) | Jun 01, 2020 |
| ASUSTek       | M2N                         | [383651de63](https://linux-hardware.org/?probe=383651de63) | May 26, 2020 |
| ASUSTek       | Z170-P D3                   | [94ad6c90d4](https://linux-hardware.org/?probe=94ad6c90d4) | May 21, 2020 |
| Unknown       | Unknown                     | [6f211d004a](https://linux-hardware.org/?probe=6f211d004a) | May 10, 2020 |
| Unknown       | Unknown                     | [b3ddb6ef68](https://linux-hardware.org/?probe=b3ddb6ef68) | May 09, 2020 |
| Unknown       | Unknown                     | [0a74b9927c](https://linux-hardware.org/?probe=0a74b9927c) | May 09, 2020 |
| ASUSTek       | PRIME X470-PRO              | [1275e05c7b](https://linux-hardware.org/?probe=1275e05c7b) | Apr 20, 2020 |
| Pegatron      | 2A99                        | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Gigabyte      | B250-HD3-CF                 | [8958ee3446](https://linux-hardware.org/?probe=8958ee3446) | Apr 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | [4a07604dd5](https://linux-hardware.org/?probe=4a07604dd5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | [c5b4596173](https://linux-hardware.org/?probe=c5b4596173) | Apr 06, 2020 |
| Packard Be... | IMEDIA S3720                | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Acer          | Aspire XC-330               | [168e69a32d](https://linux-hardware.org/?probe=168e69a32d) | Feb 11, 2020 |
| Acer          | Aspire XC-330               | [f1cbd72914](https://linux-hardware.org/?probe=f1cbd72914) | Feb 10, 2020 |
| Acer          | Aspire XC-330               | [0e517066e2](https://linux-hardware.org/?probe=0e517066e2) | Feb 08, 2020 |
| Acer          | Aspire XC-330               | [687cbfa242](https://linux-hardware.org/?probe=687cbfa242) | Feb 08, 2020 |
| HP            | 3048h                       | [ff1cde7e50](https://linux-hardware.org/?probe=ff1cde7e50) | Feb 04, 2020 |
| HP            | 3048h                       | [398e00244e](https://linux-hardware.org/?probe=398e00244e) | Feb 04, 2020 |
| HP            | 3048h                       | [69ac011884](https://linux-hardware.org/?probe=69ac011884) | Feb 04, 2020 |
| Gigabyte      | B250-HD3-CF                 | [a79eea9131](https://linux-hardware.org/?probe=a79eea9131) | Jan 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d47fbd4f5c](https://linux-hardware.org/?probe=d47fbd4f5c) | Jan 30, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [00b99ed436](https://linux-hardware.org/?probe=00b99ed436) | Jan 20, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [1c91ad30fd](https://linux-hardware.org/?probe=1c91ad30fd) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | [eb0d14b4ad](https://linux-hardware.org/?probe=eb0d14b4ad) | Jan 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [8827da4dc1](https://linux-hardware.org/?probe=8827da4dc1) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [dd045a2aef](https://linux-hardware.org/?probe=dd045a2aef) | Jan 13, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [3fb9d0e024](https://linux-hardware.org/?probe=3fb9d0e024) | Jan 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [4fae95f520](https://linux-hardware.org/?probe=4fae95f520) | Jan 10, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f78dc97f63](https://linux-hardware.org/?probe=f78dc97f63) | Jan 07, 2020 |
| ASUSTek       | H110M-E/M.2                 | [0e11277c74](https://linux-hardware.org/?probe=0e11277c74) | Jan 06, 2020 |
| HP            | 2B15A                       | [24dd32836d](https://linux-hardware.org/?probe=24dd32836d) | Dec 14, 2019 |
| Acer          | Aspire TC-885 V:1.1         | [6d7723d13c](https://linux-hardware.org/?probe=6d7723d13c) | Dec 08, 2019 |
| MSI           | 760GM-P23                   | [bbd22621aa](https://linux-hardware.org/?probe=bbd22621aa) | Dec 05, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [9f6b248a62](https://linux-hardware.org/?probe=9f6b248a62) | Nov 22, 2019 |
| ASUSTek       | H110M-E/M.2                 | [6a6a0d614e](https://linux-hardware.org/?probe=6a6a0d614e) | Oct 29, 2019 |
| ASUSTek       | H110M-E/M.2                 | [3d932d77ba](https://linux-hardware.org/?probe=3d932d77ba) | Oct 29, 2019 |
| MSI           | H110M PRO-VD PLUS           | [73bfd283e5](https://linux-hardware.org/?probe=73bfd283e5) | Oct 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [7da594325d](https://linux-hardware.org/?probe=7da594325d) | Oct 07, 2019 |
| ASUSTek       | H81M-CS                     | [577f91eb8a](https://linux-hardware.org/?probe=577f91eb8a) | Aug 18, 2019 |
| ASUSTek       | H81M-E                      | [18e73b61d9](https://linux-hardware.org/?probe=18e73b61d9) | Aug 02, 2019 |
| MSI           | H170 GAMING M3              | [8b7204fcba](https://linux-hardware.org/?probe=8b7204fcba) | Jul 23, 2019 |
| Gigabyte      | F2A88XM-HD3P                | [7136ff50b4](https://linux-hardware.org/?probe=7136ff50b4) | Jul 04, 2019 |
| MSI           | 2A9C                        | [e4de30c7e4](https://linux-hardware.org/?probe=e4de30c7e4) | Jun 25, 2019 |
| Biostar       | A10N-8800E                  | [e160dec9cf](https://linux-hardware.org/?probe=e160dec9cf) | Jun 08, 2019 |
| ASUSTek       | P7P55 LX                    | [349a68f1f0](https://linux-hardware.org/?probe=349a68f1f0) | May 20, 2019 |
| ASUSTek       | P7P55 LX                    | [7c9e75ec67](https://linux-hardware.org/?probe=7c9e75ec67) | May 20, 2019 |
| MSI           | 2A9C                        | [d810098335](https://linux-hardware.org/?probe=d810098335) | May 09, 2019 |
| ASRock        | Z77 Pro4                    | [f0f2be33be](https://linux-hardware.org/?probe=f0f2be33be) | Apr 04, 2019 |
| ASRock        | Z77 Pro4                    | [04a8af85b2](https://linux-hardware.org/?probe=04a8af85b2) | Apr 03, 2019 |
| ASUSTek       | P8H61-M LE                  | [31229ee6d4](https://linux-hardware.org/?probe=31229ee6d4) | Feb 04, 2019 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [64fa4eaf5e](https://linux-hardware.org/?probe=64fa4eaf5e) | Nov 30, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Thailand/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 31       | 8.54%   |
| Ubuntu 22.04                 | 23       | 6.34%   |
| Ubuntu 18.04                 | 23       | 6.34%   |
| Ubuntu 24.04                 | 22       | 6.06%   |
| OpenMandriva 4.3             | 9        | 2.48%   |
| Manjaro                      | 8        | 2.2%    |
| Fedora 38                    | 8        | 2.2%    |
| Arch Rolling                 | 8        | 2.2%    |
| OpenMandriva 4.2             | 7        | 1.93%   |
| OpenMandriva 23.08           | 7        | 1.93%   |
| Fedora 42                    | 7        | 1.93%   |
| Debian 12                    | 7        | 1.93%   |
| Zorin 17                     | 6        | 1.65%   |
| OpenMandriva 24.12           | 6        | 1.65%   |
| OpenMandriva 25.06           | 5        | 1.38%   |
| ArcoLinux Rolling            | 5        | 1.38%   |
| Pop!_OS 22.04                | 4        | 1.1%    |
| OpenMandriva 23.01           | 4        | 1.1%    |
| Kubuntu 24.04                | 4        | 1.1%    |
| Fedora 43                    | 4        | 1.1%    |
| Fedora 39                    | 4        | 1.1%    |
| Fedora 37                    | 4        | 1.1%    |
| Zorin 16                     | 3        | 0.83%   |
| Xubuntu 20.04                | 3        | 0.83%   |
| Xubuntu 18.04                | 3        | 0.83%   |
| Ubuntu 22.10                 | 3        | 0.83%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 0.83%   |
| OpenMandriva 5.0             | 3        | 0.83%   |
| OpenMandriva 25.04           | 3        | 0.83%   |
| Linux Mint 22.1              | 3        | 0.83%   |
| KDE neon 20.04               | 3        | 0.83%   |
| Fedora 40                    | 3        | 0.83%   |
| Debian 11                    | 3        | 0.83%   |
| Bazzite 43                   | 3        | 0.83%   |
| Zorin 15                     | 2        | 0.55%   |
| Ubuntu 23.04                 | 2        | 0.55%   |
| Ubuntu 21.10                 | 2        | 0.55%   |
| Ubuntu 21.04                 | 2        | 0.55%   |
| Ubuntu 19.10                 | 2        | 0.55%   |
| Reborn OS                    | 2        | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 109      | 32.06%  |
| OpenMandriva  | 54       | 15.88%  |
| Fedora        | 32       | 9.41%   |
| Linux Mint    | 17       | 5%      |
| Debian        | 15       | 4.41%   |
| Zorin         | 12       | 3.53%   |
| Arch          | 10       | 2.94%   |
| Pop!_OS       | 8        | 2.35%   |
| Manjaro       | 8        | 2.35%   |
| Xubuntu       | 7        | 2.06%   |
| Kubuntu       | 7        | 2.06%   |
| Endless       | 6        | 1.76%   |
| KDE neon      | 5        | 1.47%   |
| ArcoLinux     | 5        | 1.47%   |
| openSUSE      | 4        | 1.18%   |
| Kali          | 4        | 1.18%   |
| Elementary    | 3        | 0.88%   |
| CachyOS       | 3        | 0.88%   |
| Bazzite       | 3        | 0.88%   |
| Ubuntu MATE   | 2        | 0.59%   |
| TUXEDO OS     | 2        | 0.59%   |
| Reborn OS     | 2        | 0.59%   |
| Nobara        | 2        | 0.59%   |
| NixOS         | 2        | 0.59%   |
| Clear Linux   | 2        | 0.59%   |
| CentOS        | 2        | 0.59%   |
| Xero          | 1        | 0.29%   |
| UbuntuDDE     | 1        | 0.29%   |
| Ubuntu Budgie | 1        | 0.29%   |
| SteamOS       | 1        | 0.29%   |
| Solus         | 1        | 0.29%   |
| Mageia        | 1        | 0.29%   |
| Lubuntu       | 1        | 0.29%   |
| LMDE          | 1        | 0.29%   |
| Gxde          | 1        | 0.29%   |
| GNOME OS      | 1        | 0.29%   |
| Gentoo        | 1        | 0.29%   |
| BlackPanther  | 1        | 0.29%   |
| Athenaos      | 1        | 0.29%   |
| Archcraft     | 1        | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.4.11-desktop-1omv2390       | 7        | 1.75%   |
| 6.14.2-desktop-3omv2590       | 7        | 1.75%   |
| 5.16.7-desktop-1omv4003       | 7        | 1.75%   |
| 5.10.14-desktop-1omv4002      | 7        | 1.75%   |
| 6.8.0-60-generic              | 4        | 1%      |
| 6.12.1-desktop-1omv2490       | 4        | 1%      |
| 6.1.1-desktop-1omv2290        | 4        | 1%      |
| 5.4.0-48-generic              | 4        | 1%      |
| 5.15.0-56-generic             | 4        | 1%      |
| 5.15.0-46-generic             | 4        | 1%      |
| 6.8.0-85-generic              | 3        | 0.75%   |
| 6.8.0-49-generic              | 3        | 0.75%   |
| 6.8.0-48-generic              | 3        | 0.75%   |
| 6.6.2-desktop-1omv2390        | 3        | 0.75%   |
| 6.2.0-32-generic              | 3        | 0.75%   |
| 6.15.0-desktop-0.rc2.3omv2590 | 3        | 0.75%   |
| 6.12.6-desktop-1omv2490       | 3        | 0.75%   |
| 6.11.0-17-generic             | 3        | 0.75%   |
| 5.8.0-14-generic              | 3        | 0.75%   |
| 5.4.0-42-generic              | 3        | 0.75%   |
| 5.15.0-43-generic             | 3        | 0.75%   |
| 6.8.0-87-generic              | 2        | 0.5%    |
| 6.8.0-57-generic              | 2        | 0.5%    |
| 6.8.0-55-generic              | 2        | 0.5%    |
| 6.8.0-51-generic              | 2        | 0.5%    |
| 6.8.0-47-generic              | 2        | 0.5%    |
| 6.8.0-45-generic              | 2        | 0.5%    |
| 6.8.0-44-generic              | 2        | 0.5%    |
| 6.8.0-40-generic              | 2        | 0.5%    |
| 6.4.15-200.fc38.x86_64        | 2        | 0.5%    |
| 6.2.6-desktop-1omv2390        | 2        | 0.5%    |
| 6.2.15-300.fc38.x86_64        | 2        | 0.5%    |
| 6.2.0-37-generic              | 2        | 0.5%    |
| 6.2.0-26-generic              | 2        | 0.5%    |
| 6.17.9-300.fc43.x86_64        | 2        | 0.5%    |
| 6.17.7-ba20.fc43.x86_64       | 2        | 0.5%    |
| 6.14.0-15-generic             | 2        | 0.5%    |
| 6.11.0-29-generic             | 2        | 0.5%    |
| 6.11.0-28-generic             | 2        | 0.5%    |
| 6.11.0-26-generic             | 2        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 34       | 8.72%   |
| 6.8.0   | 31       | 7.95%   |
| 5.15.0  | 23       | 5.9%    |
| 5.8.0   | 12       | 3.08%   |
| 5.13.0  | 12       | 3.08%   |
| 4.15.0  | 11       | 2.82%   |
| 6.5.0   | 10       | 2.56%   |
| 6.2.0   | 10       | 2.56%   |
| 6.11.0  | 10       | 2.56%   |
| 6.14.2  | 9        | 2.31%   |
| 6.4.11  | 8        | 2.05%   |
| 5.3.0   | 8        | 2.05%   |
| 6.14.0  | 7        | 1.79%   |
| 6.1.0   | 7        | 1.79%   |
| 5.19.0  | 7        | 1.79%   |
| 5.16.7  | 7        | 1.79%   |
| 5.11.0  | 7        | 1.79%   |
| 5.10.14 | 7        | 1.79%   |
| 5.0.0   | 7        | 1.79%   |
| 4.18.0  | 5        | 1.28%   |
| 6.17.7  | 4        | 1.03%   |
| 6.12.1  | 4        | 1.03%   |
| 6.1.1   | 4        | 1.03%   |
| 6.6.2   | 3        | 0.77%   |
| 6.2.6   | 3        | 0.77%   |
| 6.15.0  | 3        | 0.77%   |
| 6.12.6  | 3        | 0.77%   |
| 5.17.5  | 3        | 0.77%   |
| 5.10.0  | 3        | 0.77%   |
| 6.9.8   | 2        | 0.51%   |
| 6.6.1   | 2        | 0.51%   |
| 6.5.7   | 2        | 0.51%   |
| 6.5.5   | 2        | 0.51%   |
| 6.4.15  | 2        | 0.51%   |
| 6.2.15  | 2        | 0.51%   |
| 6.2.14  | 2        | 0.51%   |
| 6.17.9  | 2        | 0.51%   |
| 6.12.9  | 2        | 0.51%   |
| 6.12.10 | 2        | 0.51%   |
| 6.10.0  | 2        | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 9.61%   |
| 6.8     | 33       | 8.57%   |
| 5.15    | 26       | 6.75%   |
| 6.2     | 20       | 5.19%   |
| 6.5     | 19       | 4.94%   |
| 6.14    | 19       | 4.94%   |
| 6.12    | 15       | 3.9%    |
| 6.1     | 15       | 3.9%    |
| 5.13    | 15       | 3.9%    |
| 5.16    | 14       | 3.64%   |
| 5.8     | 13       | 3.38%   |
| 6.6     | 12       | 3.12%   |
| 6.4     | 11       | 2.86%   |
| 6.11    | 11       | 2.86%   |
| 5.10    | 11       | 2.86%   |
| 4.15    | 11       | 2.86%   |
| 6.17    | 10       | 2.6%    |
| 5.3     | 9        | 2.34%   |
| 5.19    | 8        | 2.08%   |
| 5.17    | 8        | 2.08%   |
| 5.0     | 8        | 2.08%   |
| 5.11    | 7        | 1.82%   |
| 6.3     | 6        | 1.56%   |
| 6.15    | 6        | 1.56%   |
| 6.10    | 6        | 1.56%   |
| 6.9     | 5        | 1.3%    |
| 4.18    | 5        | 1.3%    |
| 6.7     | 3        | 0.78%   |
| 6.13    | 3        | 0.78%   |
| 5.6     | 3        | 0.78%   |
| 6.16    | 2        | 0.52%   |
| 6.0     | 2        | 0.52%   |
| 5.5     | 2        | 0.52%   |
| 5.14    | 2        | 0.52%   |
| 6.18    | 1        | 0.26%   |
| 5.9     | 1        | 0.26%   |
| 5.7     | 1        | 0.26%   |
| 5.18    | 1        | 0.26%   |
| 5.12    | 1        | 0.26%   |
| 5.1     | 1        | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 323      | 99.69%  |
| i686   | 1        | 0.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 166      | 48.26%  |
| KDE5             | 48       | 13.95%  |
| KDE6             | 31       | 9.01%   |
| Unknown          | 30       | 8.72%   |
| XFCE             | 20       | 5.81%   |
| X-Cinnamon       | 17       | 4.94%   |
| LXQt             | 6        | 1.74%   |
| KDE              | 5        | 1.45%   |
| MATE             | 4        | 1.16%   |
| Pantheon         | 3        | 0.87%   |
| Deepin           | 3        | 0.87%   |
| Cinnamon         | 3        | 0.87%   |
| Budgie           | 2        | 0.58%   |
| sway             | 1        | 0.29%   |
| niri             | 1        | 0.29%   |
| lightdm-xsession | 1        | 0.29%   |
| KDE4             | 1        | 0.29%   |
| i3               | 1        | 0.29%   |
| bspwm            | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 198      | 58.93%  |
| Wayland | 112      | 33.33%  |
| Unknown | 18       | 5.36%   |
| Tty     | 8        | 2.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 156      | 46.02%  |
| SDDM    | 71       | 20.94%  |
| GDM3    | 62       | 18.29%  |
| GDM     | 29       | 8.55%   |
| LightDM | 17       | 5.01%   |
| TDM     | 3        | 0.88%   |
| GREETD  | 1        | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 241      | 72.81%  |
| th_TH   | 22       | 6.65%   |
| Unknown | 18       | 5.44%   |
| de_DE   | 15       | 4.53%   |
| en_GB   | 14       | 4.23%   |
| C       | 8        | 2.42%   |
| it_IT   | 5        | 1.51%   |
| fi_FI   | 2        | 0.6%    |
| zh_CN   | 1        | 0.3%    |
| sv_SE   | 1        | 0.3%    |
| fr_FR   | 1        | 0.3%    |
| en_CA   | 1        | 0.3%    |
| de_CH   | 1        | 0.3%    |
| C.UTF8  | 1        | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 184      | 54.93%  |
| EFI  | 151      | 45.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 205      | 60.29%  |
| Btrfs   | 47       | 13.82%  |
| Tmpfs   | 42       | 12.35%  |
| Overlay | 35       | 10.29%  |
| Xfs     | 6        | 1.76%   |
| Unknown | 4        | 1.18%   |
| Zfs     | 1        | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 160      | 47.48%  |
| Unknown | 159      | 47.18%  |
| MBR     | 18       | 5.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 269      | 80.54%  |
| Yes       | 65       | 19.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 223      | 66.57%  |
| Yes       | 112      | 33.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte Technology                  | 63       | 19.44%  |
| ASUSTek Computer                     | 55       | 16.98%  |
| ASRock                               | 48       | 14.81%  |
| Dell                                 | 34       | 10.49%  |
| MSI                                  | 30       | 9.26%   |
| Hewlett-Packard                      | 21       | 6.48%   |
| Acer                                 | 16       | 4.94%   |
| Lenovo                               | 9        | 2.78%   |
| Intel                                | 8        | 2.47%   |
| Unknown                              | 5        | 1.54%   |
| AMI                                  | 4        | 1.23%   |
| OEM                                  | 3        | 0.93%   |
| MiTAC                                | 3        | 0.93%   |
| Huanan                               | 3        | 0.93%   |
| T-bao                                | 2        | 0.62%   |
| Fujitsu                              | 2        | 0.62%   |
| Biostar                              | 2        | 0.62%   |
| AZW                                  | 2        | 0.62%   |
| Apple                                | 2        | 0.62%   |
| ViewSonic                            | 1        | 0.31%   |
| VIA Technologies                     | 1        | 0.31%   |
| Supermicro                           | 1        | 0.31%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.31%   |
| SHARKBAY                             | 1        | 0.31%   |
| Pegatron                             | 1        | 0.31%   |
| Packard Bell                         | 1        | 0.31%   |
| JINGSHA                              | 1        | 0.31%   |
| Google                               | 1        | 0.31%   |
| ECS                                  | 1        | 0.31%   |
| BESSTAR Tech                         | 1        | 0.31%   |
| AFOX                                 | 1        | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 9        | 2.78%   |
| Unknown                      | 6        | 1.85%   |
| Dell OptiPlex 7010           | 4        | 1.23%   |
| ASUS P8H61-M LE              | 4        | 1.23%   |
| ASRock B450 Steel Legend     | 4        | 1.23%   |
| AMI Intel                    | 4        | 1.23%   |
| Intel X99                    | 3        | 0.93%   |
| Gigabyte H61M-DS2            | 3        | 0.93%   |
| Gigabyte H110M-DS2           | 3        | 0.93%   |
| Dell OptiPlex 9020           | 3        | 0.93%   |
| Dell OptiPlex 7020           | 3        | 0.93%   |
| Dell Inspiron 3847           | 3        | 0.93%   |
| Acer Veriton N4640G          | 3        | 0.93%   |
| T-bao MINI PC                | 2        | 0.62%   |
| OEM X79G                     | 2        | 0.62%   |
| MSI MS-7C35                  | 2        | 0.62%   |
| MSI MS-7A78                  | 2        | 0.62%   |
| MiTAC PD10EHI                | 2        | 0.62%   |
| HP Z240 Tower Workstation    | 2        | 0.62%   |
| HP EliteDesk 800 G1 SFF PC   | 2        | 0.62%   |
| HP Compaq 6200 Pro SFF PC    | 2        | 0.62%   |
| Gigabyte Z97X-UD3H-BK        | 2        | 0.62%   |
| Gigabyte Z390 UD             | 2        | 0.62%   |
| Gigabyte X570 AORUS ELITE    | 2        | 0.62%   |
| Gigabyte H81M-DS2            | 2        | 0.62%   |
| Gigabyte F2A88XM-HD3P        | 2        | 0.62%   |
| Gigabyte F2A88XM-HD3         | 2        | 0.62%   |
| Gigabyte F2A68HM-DS2         | 2        | 0.62%   |
| Gigabyte B250-HD3            | 2        | 0.62%   |
| Dell OptiPlex 7050           | 2        | 0.62%   |
| Dell OptiPlex 7040           | 2        | 0.62%   |
| Dell OptiPlex 3020           | 2        | 0.62%   |
| Dell OptiPlex 3010           | 2        | 0.62%   |
| AZW MINI S                   | 2        | 0.62%   |
| ASUS TUF Gaming B550M-E      | 2        | 0.62%   |
| ASUS H110M-E/M.2             | 2        | 0.62%   |
| ASUS F1A55-M LX PLUS         | 2        | 0.62%   |
| ASRock X570 Phantom Gaming 4 | 2        | 0.62%   |
| ASRock B550M Steel Legend    | 2        | 0.62%   |
| ASRock B450M Steel Legend    | 2        | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 24       | 7.41%   |
| ASUS PRIME             | 10       | 3.09%   |
| ASUS All               | 9        | 2.78%   |
| Acer Veriton           | 9        | 2.78%   |
| Acer Aspire            | 7        | 2.16%   |
| HP Compaq              | 6        | 1.85%   |
| ASRock B450            | 6        | 1.85%   |
| Unknown                | 6        | 1.85%   |
| Dell Precision         | 5        | 1.54%   |
| Lenovo ThinkCentre     | 4        | 1.23%   |
| HP ProDesk             | 4        | 1.23%   |
| HP EliteDesk           | 4        | 1.23%   |
| Gigabyte X570          | 4        | 1.23%   |
| ASUS ROG               | 4        | 1.23%   |
| ASUS P8H61-M           | 4        | 1.23%   |
| ASUS M5A78L-M          | 4        | 1.23%   |
| ASRock B450M           | 4        | 1.23%   |
| AMI Intel              | 4        | 1.23%   |
| Intel X99              | 3        | 0.93%   |
| Huanan X79             | 3        | 0.93%   |
| Gigabyte Z390          | 3        | 0.93%   |
| Gigabyte H61M-DS2      | 3        | 0.93%   |
| Gigabyte H110M-DS2     | 3        | 0.93%   |
| Dell Inspiron          | 3        | 0.93%   |
| ASUS TUF               | 3        | 0.93%   |
| ASRock X570            | 3        | 0.93%   |
| ASRock B550M           | 3        | 0.93%   |
| T-bao MINI             | 2        | 0.62%   |
| OEM X79G               | 2        | 0.62%   |
| MSI Pro                | 2        | 0.62%   |
| MSI MS-7C35            | 2        | 0.62%   |
| MSI MS-7A78            | 2        | 0.62%   |
| MiTAC PD10EHI          | 2        | 0.62%   |
| HP Z240                | 2        | 0.62%   |
| Gigabyte Z97X-UD3H-BK  | 2        | 0.62%   |
| Gigabyte H81M-DS2      | 2        | 0.62%   |
| Gigabyte H310M         | 2        | 0.62%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.62%   |
| Gigabyte F2A88XM-HD3P  | 2        | 0.62%   |
| Gigabyte F2A88XM-HD3   | 2        | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 33       | 10.19%  |
| 2020 | 30       | 9.26%   |
| 2019 | 29       | 8.95%   |
| 2018 | 29       | 8.95%   |
| 2014 | 27       | 8.33%   |
| 2016 | 26       | 8.02%   |
| 2017 | 21       | 6.48%   |
| 2012 | 21       | 6.48%   |
| 2011 | 18       | 5.56%   |
| 2023 | 13       | 4.01%   |
| 2015 | 13       | 4.01%   |
| 2021 | 12       | 3.7%    |
| 2009 | 10       | 3.09%   |
| 2024 | 9        | 2.78%   |
| 2022 | 9        | 2.78%   |
| 2010 | 9        | 2.78%   |
| 2008 | 8        | 2.47%   |
| 2025 | 3        | 0.93%   |
| 2006 | 2        | 0.62%   |
| 2007 | 1        | 0.31%   |
| 2005 | 1        | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 324      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 317      | 96.65%  |
| Enabled  | 11       | 3.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 323      | 99.69%  |
| Yes  | 1        | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 84       | 24.71%  |
| 8.01-16.0       | 66       | 19.41%  |
| 4.01-8.0        | 64       | 18.82%  |
| 32.01-64.0      | 52       | 15.29%  |
| 3.01-4.0        | 41       | 12.06%  |
| 64.01-256.0     | 13       | 3.82%   |
| 24.01-32.0      | 10       | 2.94%   |
| 1.01-2.0        | 8        | 2.35%   |
| More than 256.0 | 1        | 0.29%   |
| 0.51-1.0        | 1        | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 119      | 31.99%  |
| 2.01-3.0   | 104      | 27.96%  |
| 4.01-8.0   | 64       | 17.2%   |
| 3.01-4.0   | 53       | 14.25%  |
| 0.51-1.0   | 14       | 3.76%   |
| 8.01-16.0  | 13       | 3.49%   |
| 16.01-24.0 | 3        | 0.81%   |
| 24.01-32.0 | 1        | 0.27%   |
| 0.01-0.5   | 1        | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 137      | 39.71%  |
| 2      | 101      | 29.28%  |
| 3      | 56       | 16.23%  |
| 4      | 21       | 6.09%   |
| 5      | 12       | 3.48%   |
| 0      | 6        | 1.74%   |
| 6      | 5        | 1.45%   |
| 7      | 3        | 0.87%   |
| 10     | 2        | 0.58%   |
| 51     | 1        | 0.29%   |
| 32     | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 229      | 69.82%  |
| Yes       | 99       | 30.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 315      | 97.22%  |
| No        | 9        | 2.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 186      | 55.86%  |
| No        | 147      | 44.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 193      | 58.13%  |
| Yes       | 139      | 41.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 324      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bangkok                  | 130      | 37.46%  |
| Chiang Mai               | 30       | 8.65%   |
| Nakhon Ratchasima        | 13       | 3.75%   |
| Nakhon Pathom            | 12       | 3.46%   |
| Khon Kaen                | 11       | 3.17%   |
| Chon Buri                | 9        | 2.59%   |
| Phuket                   | 8        | 2.31%   |
| Mueang Samut Prakan      | 8        | 2.31%   |
| Nonthaburi               | 7        | 2.02%   |
| Bang Lamung              | 7        | 2.02%   |
| Songkhla                 | 5        | 1.44%   |
| Ban Nong Sala            | 5        | 1.44%   |
| Surin                    | 4        | 1.15%   |
| Si Racha                 | 4        | 1.15%   |
| Pattaya                  | 4        | 1.15%   |
| Pathum Thani             | 4        | 1.15%   |
| Phitsanulok              | 3        | 0.86%   |
| Ban Phan Don             | 3        | 0.86%   |
| Ban Du                   | 3        | 0.86%   |
| Surat Thani              | 2        | 0.58%   |
| Si Sa Ket                | 2        | 0.58%   |
| Phra Nakhon Si Ayutthaya | 2        | 0.58%   |
| Pak Kret                 | 2        | 0.58%   |
| Nakhon Sawan             | 2        | 0.58%   |
| Lampang                  | 2        | 0.58%   |
| Ko Samui                 | 2        | 0.58%   |
| Hua Hin                  | 2        | 0.58%   |
| Bang Khae                | 2        | 0.58%   |
| Ban Chang                | 2        | 0.58%   |
| Ban Bang Tanot           | 2        | 0.58%   |
| Yarang                   | 1        | 0.29%   |
| Wihan Daeng              | 1        | 0.29%   |
| Wichian Buri             | 1        | 0.29%   |
| Udon Thani               | 1        | 0.29%   |
| Ubon Ratchathani         | 1        | 0.29%   |
| Trat                     | 1        | 0.29%   |
| Thung Song               | 1        | 0.29%   |
| Tha Tako                 | 1        | 0.29%   |
| Suan Luang               | 1        | 0.29%   |
| Sawang Daen Din          | 1        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 129      | 229    | 21.43%  |
| Seagate                     | 93       | 168    | 15.45%  |
| Samsung Electronics         | 58       | 91     | 9.63%   |
| SanDisk                     | 45       | 73     | 7.48%   |
| Kingston                    | 30       | 34     | 4.98%   |
| Toshiba                     | 25       | 76     | 4.15%   |
| MAXIO Technology (Hangzhou) | 13       | 17     | 2.16%   |
| HS-SSD-C100                 | 13       | 29     | 2.16%   |
| China                       | 12       | 24     | 1.99%   |
| Hitachi                     | 11       | 11     | 1.83%   |
| Crucial                     | 11       | 12     | 1.83%   |
| Apacer                      | 11       | 13     | 1.83%   |
| Unknown                     | 10       | 16     | 1.66%   |
| Silicon Motion              | 10       | 12     | 1.66%   |
| Hikvision                   | 9        | 9      | 1.5%    |
| Intel                       | 7        | 7      | 1.16%   |
| HS-SSD-E100                 | 7        | 8      | 1.16%   |
| Realtek Semiconductor       | 6        | 6      | 1%      |
| A-DATA Technology           | 6        | 10     | 1%      |
| Phison Electronics          | 5        | 6      | 0.83%   |
| Phison                      | 5        | 10     | 0.83%   |
| Colorful                    | 5        | 7      | 0.83%   |
| SPCC                        | 4        | 4      | 0.66%   |
| SK hynix                    | 4        | 5      | 0.66%   |
| KingSpec                    | 4        | 6      | 0.66%   |
| JMicron Technology          | 4        | 4      | 0.66%   |
| USB3.0                      | 3        | 3      | 0.5%    |
| TO Exter                    | 3        | 3      | 0.5%    |
| Micron Technology           | 3        | 3      | 0.5%    |
| Lexar                       | 3        | 4      | 0.5%    |
| Kingston Technology Company | 3        | 4      | 0.5%    |
| HGST                        | 3        | 11     | 0.5%    |
| Hewlett-Packard             | 3        | 5      | 0.5%    |
| GALAX                       | 3        | 3      | 0.5%    |
| Corsair                     | 3        | 3      | 0.5%    |
| Unknown                     | 3        | 4      | 0.5%    |
| WALRAM                      | 2        | 3      | 0.33%   |
| Transcend                   | 2        | 2      | 0.33%   |
| Plextor                     | 2        | 2      | 0.33%   |
| Micron/Crucial Technology   | 2        | 2      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 12       | 1.73%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 1.59%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB      | 10       | 1.44%   |
| WDC WD10EZEX-00WN4A0 1TB                              | 9        | 1.3%    |
| Seagate ST1000DM003-1ER162 1TB                        | 9        | 1.3%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 7        | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 7        | 1.01%   |
| Toshiba DT01ACA100 1TB                                | 7        | 1.01%   |
| HS-SSD-C100 120G                                      | 7        | 1.01%   |
| Seagate ST2000VX008-2E3164 2TB                        | 6        | 0.87%   |
| SanDisk NVMe SSD Drive 1TB                            | 6        | 0.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 6        | 0.87%   |
| Kingston SA400S37240G 240GB SSD                       | 6        | 0.87%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 5        | 0.72%   |
| WDC WD20EZAZ-00GGJB0 2TB                              | 5        | 0.72%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 5        | 0.72%   |
| Samsung HD103SJ 1TB                                   | 5        | 0.72%   |
| Kingston SUV400S37120G 120GB SSD                      | 5        | 0.72%   |
| HS-SSD-C100 240G                                      | 5        | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 4        | 0.58%   |
| WDC WD5000AAKX-001CA0 500GB                           | 4        | 0.58%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 4        | 0.58%   |
| Unknown SD/MMC/MS PRO 2GB                             | 4        | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 4        | 0.58%   |
| Seagate ST3500418AS 500GB                             | 4        | 0.58%   |
| Seagate ST1000DM003-1SB102 1TB                        | 4        | 0.58%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 512GB | 4        | 0.58%   |
| SanDisk SDSSDA120G 120GB                              | 4        | 0.58%   |
| Samsung SSD 850 EVO 250GB                             | 4        | 0.58%   |
| Crucial CT500MX500SSD1 500GB                          | 4        | 0.58%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 3        | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB                              | 3        | 0.43%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 3        | 0.43%   |
| WDC WD2003FZEX-00SRLA0 2TB                            | 3        | 0.43%   |
| WDC WD2002FAEX-007BA0 2TB                             | 3        | 0.43%   |
| WDC WD10EZEX-00MFCA0 1TB                              | 3        | 0.43%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 3        | 0.43%   |
| WDC WD Blue SA510 2.5 250GB                           | 3        | 0.43%   |
| USB3.0 Super Speed 500GB                              | 3        | 0.43%   |
| TO Exter nal USB 3.0 250GB                            | 3        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 103      | 170    | 39.02%  |
| Seagate             | 91       | 158    | 34.47%  |
| Toshiba             | 24       | 75     | 9.09%   |
| Samsung Electronics | 13       | 20     | 4.92%   |
| Hitachi             | 11       | 11     | 4.17%   |
| Unknown             | 5        | 11     | 1.89%   |
| USB3.0              | 3        | 3      | 1.14%   |
| TO Exter            | 3        | 3      | 1.14%   |
| HGST                | 3        | 11     | 1.14%   |
| Hewlett-Packard     | 2        | 4      | 0.76%   |
| External            | 2        | 2      | 0.76%   |
| JMicron Technology  | 1        | 1      | 0.38%   |
| HGST HTS            | 1        | 1      | 0.38%   |
| Fujitsu             | 1        | 2      | 0.38%   |
| ASMedia             | 1        | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 47     | 16%     |
| Samsung Electronics | 30       | 46     | 15%     |
| Kingston            | 22       | 24     | 11%     |
| SanDisk             | 14       | 23     | 7%      |
| China               | 12       | 24     | 6%      |
| Crucial             | 11       | 12     | 5.5%    |
| Apacer              | 11       | 13     | 5.5%    |
| Hikvision           | 6        | 6      | 3%      |
| Intel               | 5        | 5      | 2.5%    |
| A-DATA Technology   | 5        | 9      | 2.5%    |
| KingSpec            | 4        | 6      | 2%      |
| Colorful            | 4        | 6      | 2%      |
| SPCC                | 3        | 3      | 1.5%    |
| Lexar               | 3        | 4      | 1.5%    |
| GALAX               | 3        | 3      | 1.5%    |
| WALRAM              | 2        | 2      | 1%      |
| Plextor             | 2        | 2      | 1%      |
| Micron Technology   | 2        | 2      | 1%      |
| HS-SSD-E100         | 2        | 2      | 1%      |
| Acer                | 2        | 6      | 1%      |
| Verbatim            | 1        | 1      | 0.5%    |
| Unknown             | 1        | 1      | 0.5%    |
| Transcend           | 1        | 1      | 0.5%    |
| Team                | 1        | 1      | 0.5%    |
| SPCC M.2            | 1        | 1      | 0.5%    |
| SK hynix            | 1        | 2      | 0.5%    |
| PNY                 | 1        | 1      | 0.5%    |
| Pioneer             | 1        | 1      | 0.5%    |
| OCZ                 | 1        | 1      | 0.5%    |
| LITEON              | 1        | 1      | 0.5%    |
| Kingmax             | 1        | 1      | 0.5%    |
| KINGBANK            | 1        | 1      | 0.5%    |
| JMicron Technology  | 1        | 1      | 0.5%    |
| Intenso             | 1        | 12     | 0.5%    |
| HS-SSD-WAVE(S)      | 1        | 1      | 0.5%    |
| HS-SSD-E100N        | 1        | 1      | 0.5%    |
| HS-SSD-C100         | 1        | 1      | 0.5%    |
| Hewlett-Packard     | 1        | 1      | 0.5%    |
| GAMER               | 1        | 1      | 0.5%    |
| DGM                 | 1        | 1      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 203      | 473    | 40.04%  |
| SSD     | 162      | 283    | 31.95%  |
| NVMe    | 113      | 173    | 22.29%  |
| Unknown | 28       | 52     | 5.52%   |
| MMC     | 1        | 1      | 0.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 290      | 754    | 66.36%  |
| NVMe | 113      | 172    | 25.86%  |
| SAS  | 33       | 55     | 7.55%   |
| MMC  | 1        | 1      | 0.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 195      | 348    | 47.56%  |
| 0.51-1.0   | 121      | 199    | 29.51%  |
| 1.01-2.0   | 54       | 85     | 13.17%  |
| 3.01-4.0   | 20       | 73     | 4.88%   |
| 4.01-10.0  | 9        | 22     | 2.2%    |
| 2.01-3.0   | 8        | 17     | 1.95%   |
| 10.01-20.0 | 3        | 12     | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 98       | 28.16%  |
| 251-500        | 54       | 15.52%  |
| 501-1000       | 51       | 14.66%  |
| 1-20           | 34       | 9.77%   |
| More than 3000 | 28       | 8.05%   |
| 1001-2000      | 28       | 8.05%   |
| 2001-3000      | 24       | 6.9%    |
| 51-100         | 14       | 4.02%   |
| 21-50          | 10       | 2.87%   |
| Unknown        | 7        | 2.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 127      | 34.89%  |
| 21-50          | 60       | 16.48%  |
| 101-250        | 46       | 12.64%  |
| 51-100         | 39       | 10.71%  |
| 501-1000       | 26       | 7.14%   |
| 251-500        | 23       | 6.32%   |
| More than 3000 | 14       | 3.85%   |
| 1001-2000      | 13       | 3.57%   |
| 2001-3000      | 9        | 2.47%   |
| Unknown        | 7        | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                    | Desktops | Drives | Percent |
|----------------------------------------------------------|----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                                | 3        | 3      | 7.5%    |
| WDC WD10EZEX-00WN4A0 1TB                                 | 2        | 2      | 5%      |
| WDC WD10EARX-00N0YB0 1TB                                 | 2        | 2      | 5%      |
| Seagate ST500DM002-1BD142 500GB                          | 2        | 2      | 5%      |
| Seagate ST500DM002-1BD14 500GB                           | 2        | 3      | 5%      |
| Samsung Electronics SSD 830 Series 128GB                 | 2        | 2      | 5%      |
| WDC WDS240G2G0A-00JH30 240GB SSD                         | 1        | 1      | 2.5%    |
| WDC WD6402AAEX-00Y9A0 640GB                              | 1        | 1      | 2.5%    |
| WDC WD20EZRX-00DC0B0 2TB                                 | 1        | 1      | 2.5%    |
| WDC WD20EARS-00MVWB0 2TB                                 | 1        | 1      | 2.5%    |
| WDC WD10PURX-64E5EY0 1TB                                 | 1        | 1      | 2.5%    |
| WDC WD10EZEX-08WN4A0 1TB                                 | 1        | 1      | 2.5%    |
| WDC WD1002FAEX-00Y9A0 1TB                                | 1        | 1      | 2.5%    |
| USB3.0 Super Speed 500GB                                 | 1        | 1      | 2.5%    |
| Toshiba HDWL110 1TB                                      | 1        | 1      | 2.5%    |
| Seagate ST9120822AS 120GB                                | 1        | 1      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB                          | 1        | 1      | 2.5%    |
| Seagate ST4000DM004-2CV104 4TB                           | 1        | 1      | 2.5%    |
| Seagate ST3500418AS 500GB                                | 1        | 2      | 2.5%    |
| Seagate ST2000DM006-2DM164 2TB                           | 1        | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                       | 1        | 1      | 2.5%    |
| Seagate ST1000LM014-1EJ164 1TB                           | 1        | 1      | 2.5%    |
| Seagate ST1000DM003-1SB102 1TB                           | 1        | 1      | 2.5%    |
| Samsung Electronics HD502HI 500GB                        | 1        | 1      | 2.5%    |
| Samsung Electronics HD322GJ 320GB                        | 1        | 2      | 2.5%    |
| Samsung Electronics HD253GJ 250GB                        | 1        | 2      | 2.5%    |
| Samsung Electronics HD103SJ 1TB                          | 1        | 1      | 2.5%    |
| Realtek Semiconductor KLEVV CRAS C715 M.2 NVMe SSD 512GB | 1        | 1      | 2.5%    |
| Lexar 128GB SSD                                          | 1        | 1      | 2.5%    |
| Kingston SV300S37A120G 120GB SSD                         | 1        | 1      | 2.5%    |
| Hitachi HTS541612J9SA00 120GB                            | 1        | 1      | 2.5%    |
| Hitachi HDS721064CLA332 640GB                            | 1        | 1      | 2.5%    |
| A-DATA Technology SU800 2TB SSD                          | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 13       | 14     | 33.33%  |
| Seagate               | 12       | 14     | 30.77%  |
| Samsung Electronics   | 6        | 8      | 15.38%  |
| Hitachi               | 2        | 2      | 5.13%   |
| USB3.0                | 1        | 1      | 2.56%   |
| Toshiba               | 1        | 1      | 2.56%   |
| Realtek Semiconductor | 1        | 1      | 2.56%   |
| Lexar                 | 1        | 1      | 2.56%   |
| Kingston              | 1        | 1      | 2.56%   |
| A-DATA Technology     | 1        | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 37.5%   |
| Seagate             | 12       | 14     | 37.5%   |
| Samsung Electronics | 4        | 6      | 12.5%   |
| Hitachi             | 2        | 2      | 6.25%   |
| USB3.0              | 1        | 1      | 3.13%   |
| Toshiba             | 1        | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 37     | 81.58%  |
| SSD  | 6        | 6      | 15.79%  |
| NVMe | 1        | 1      | 2.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB | 2        | 2      | 66.67%  |
| WDC WD30EFRX-68EUZN0 3TB        | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 66.67%  |
| WDC                 | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 217      | 568    | 57.87%  |
| Works    | 120      | 367    | 32%     |
| Malfunc  | 35       | 44     | 9.33%   |
| Failed   | 3        | 3      | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 213      | 45.22%  |
| AMD                          | 98       | 20.81%  |
| SanDisk                      | 39       | 8.28%   |
| Samsung Electronics          | 18       | 3.82%   |
| ASMedia Technology           | 18       | 3.82%   |
| MAXIO Technology (Hangzhou)  | 17       | 3.61%   |
| Phison Electronics           | 12       | 2.55%   |
| Kingston Technology Company  | 11       | 2.34%   |
| Silicon Motion               | 10       | 2.12%   |
| Realtek Semiconductor        | 7        | 1.49%   |
| Nvidia                       | 7        | 1.49%   |
| SK hynix                     | 3        | 0.64%   |
| Marvell Technology Group     | 3        | 0.64%   |
| VIA Technologies             | 2        | 0.42%   |
| Micron/Crucial Technology    | 2        | 0.42%   |
| JMicron Technology           | 2        | 0.42%   |
| Broadcom / LSI               | 2        | 0.42%   |
| Yangtze Memory Technologies  | 1        | 0.21%   |
| Transcend                    | 1        | 0.21%   |
| Toshiba America Info Systems | 1        | 0.21%   |
| Micron Technology            | 1        | 0.21%   |
| LSI Logic / Symbios Logic    | 1        | 0.21%   |
| Hosin Global Electronics     | 1        | 0.21%   |
| ADATA Technology             | 1        | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 49       | 8.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 30       | 5.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 4.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 22       | 3.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 3.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 18       | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 2.7%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 15       | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 2.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 2.16%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 12       | 2.16%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 2.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 2.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11       | 1.98%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 10       | 1.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.8%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 8        | 1.44%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 7        | 1.26%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7        | 1.26%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 1.26%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.26%   |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 1.26%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                            | 6        | 1.08%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 6        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 1.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 5        | 0.9%    |
| Nvidia MCP61 SATA Controller                                                            | 5        | 0.9%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                | 5        | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 0.9%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 5        | 0.9%    |
| Nvidia MCP61 IDE                                                                        | 4        | 0.72%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 4        | 0.72%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4        | 0.72%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 279      | 60%     |
| NVMe | 114      | 24.52%  |
| IDE  | 52       | 11.18%  |
| RAID | 18       | 3.87%   |
| SAS  | 1        | 0.22%   |
| SCSI | 1        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 218      | 67.28%  |
| AMD          | 105      | 32.41%  |
| CentaurHauls | 1        | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i3-2120 CPU @ 3.30GHz       | 8        | 2.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 7        | 2.13%   |
| AMD Ryzen 5 3600 6-Core Processor      | 7        | 2.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 6        | 1.83%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 6        | 1.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 5        | 1.52%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 5        | 1.52%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 5        | 1.52%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 4        | 1.22%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 4        | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 4        | 1.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 4        | 1.22%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 3        | 0.91%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 3        | 0.91%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 0.91%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 3        | 0.91%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 3        | 0.91%   |
| Intel Core i5-6400T CPU @ 2.20GHz      | 3        | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 3        | 0.91%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 3        | 0.91%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 3        | 0.91%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 3        | 0.91%   |
| Intel Core i3-4160 CPU @ 3.60GHz       | 3        | 0.91%   |
| Intel Core i3-4130 CPU @ 3.40GHz       | 3        | 0.91%   |
| Intel 13th Gen Core i5-13500           | 3        | 0.91%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 0.91%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 3        | 0.91%   |
| AMD Ryzen 7 2700 Eight-Core Processor  | 3        | 0.91%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 0.91%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 3        | 0.91%   |
| AMD Phenom II X6 1055T Processor       | 3        | 0.91%   |
| Intel Pentium N6415 @ 1.20GHz          | 2        | 0.61%   |
| Intel N95                              | 2        | 0.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 2        | 0.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 2        | 0.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 0.61%   |
| Intel Core i7-10700 CPU @ 2.90GHz      | 2        | 0.61%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 2        | 0.61%   |
| Intel Core i5-7600K CPU @ 3.80GHz      | 2        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 67       | 20.49%  |
| Intel Core i3           | 47       | 14.37%  |
| Intel Core i7           | 46       | 14.07%  |
| AMD Ryzen 5             | 35       | 10.7%   |
| Intel Xeon              | 22       | 6.73%   |
| AMD Ryzen 7             | 15       | 4.59%   |
| AMD Ryzen 9             | 11       | 3.36%   |
| Other                   | 8        | 2.45%   |
| AMD Ryzen 3             | 7        | 2.14%   |
| AMD FX                  | 7        | 2.14%   |
| Intel Pentium           | 6        | 1.83%   |
| Intel Core 2 Quad       | 5        | 1.53%   |
| AMD Athlon II X2        | 5        | 1.53%   |
| Intel Core i9           | 4        | 1.22%   |
| Intel Celeron           | 4        | 1.22%   |
| AMD Athlon 64 X2        | 4        | 1.22%   |
| AMD A6                  | 4        | 1.22%   |
| AMD A10                 | 4        | 1.22%   |
| Intel Pentium Dual-Core | 3        | 0.92%   |
| AMD Phenom II X6        | 3        | 0.92%   |
| Intel Core 2 Duo        | 2        | 0.61%   |
| AMD Phenom II X4        | 2        | 0.61%   |
| AMD Athlon              | 2        | 0.61%   |
| AMD A8                  | 2        | 0.61%   |
| AMD A4                  | 2        | 0.61%   |
| Intel Pentium Dual      | 1        | 0.31%   |
| Intel Pentium D         | 1        | 0.31%   |
| Intel Pentium 4         | 1        | 0.31%   |
| Intel Core              | 1        | 0.31%   |
| Intel Atom              | 1        | 0.31%   |
| CentaurHauls VIA Eden   | 1        | 0.31%   |
| AMD Turion II Neo       | 1        | 0.31%   |
| AMD Ryzen 3 PRO         | 1        | 0.31%   |
| AMD Phenom II X3        | 1        | 0.31%   |
| AMD Phenom II X2        | 1        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 131      | 40.06%  |
| 2      | 79       | 24.16%  |
| 6      | 51       | 15.6%   |
| 8      | 31       | 9.48%   |
| 12     | 10       | 3.06%   |
| 14     | 5        | 1.53%   |
| 16     | 4        | 1.22%   |
| 10     | 4        | 1.22%   |
| 1      | 4        | 1.22%   |
| 3      | 3        | 0.92%   |
| 28     | 2        | 0.61%   |
| 40     | 1        | 0.31%   |
| 24     | 1        | 0.31%   |
| 20     | 1        | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 316      | 97.53%  |
| 2      | 7        | 2.16%   |
| 14     | 1        | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 203      | 62.46%  |
| 1      | 122      | 37.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 324      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 193      | 55.94%  |
| 0x306c3    | 19       | 5.51%   |
| 0x206a7    | 11       | 3.19%   |
| 0x506e3    | 10       | 2.9%    |
| 0x906ea    | 7        | 2.03%   |
| 0x906e9    | 7        | 2.03%   |
| 0x306a9    | 7        | 2.03%   |
| 0x1067a    | 6        | 1.74%   |
| 0x0800820d | 6        | 1.74%   |
| 0x06001119 | 5        | 1.45%   |
| 0x08701021 | 4        | 1.16%   |
| 0x010000c8 | 4        | 1.16%   |
| 0xa0655    | 3        | 0.87%   |
| 0x906ec    | 3        | 0.87%   |
| 0x406f1    | 3        | 0.87%   |
| 0x20655    | 3        | 0.87%   |
| 0x08001138 | 3        | 0.87%   |
| 0x906eb    | 2        | 0.58%   |
| 0x40651    | 2        | 0.58%   |
| 0x106e5    | 2        | 0.58%   |
| 0x0a50000c | 2        | 0.58%   |
| 0x0a201009 | 2        | 0.58%   |
| 0x08600106 | 2        | 0.58%   |
| 0x08108109 | 2        | 0.58%   |
| 0x06003106 | 2        | 0.58%   |
| 0x06000852 | 2        | 0.58%   |
| 0xf65      | 1        | 0.29%   |
| 0xf49      | 1        | 0.29%   |
| 0xa0653    | 1        | 0.29%   |
| 0x906ed    | 1        | 0.29%   |
| 0x6fd      | 1        | 0.29%   |
| 0x6fb      | 1        | 0.29%   |
| 0x50654    | 1        | 0.29%   |
| 0x406c3    | 1        | 0.29%   |
| 0x306e4    | 1        | 0.29%   |
| 0x30678    | 1        | 0.29%   |
| 0x206c2    | 1        | 0.29%   |
| 0x106ca    | 1        | 0.29%   |
| 0x10677    | 1        | 0.29%   |
| 0x10676    | 1        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 46       | 14.15%  |
| KabyLake         | 37       | 11.38%  |
| IvyBridge        | 28       | 8.62%   |
| Skylake          | 27       | 8.31%   |
| Zen 2            | 22       | 6.77%   |
| SandyBridge      | 19       | 5.85%   |
| Unknown          | 18       | 5.54%   |
| Zen 3            | 15       | 4.62%   |
| Zen+             | 14       | 4.31%   |
| CometLake        | 12       | 3.69%   |
| Zen              | 11       | 3.38%   |
| K10              | 11       | 3.38%   |
| Piledriver       | 10       | 3.08%   |
| Penryn           | 10       | 3.08%   |
| Westmere         | 7        | 2.15%   |
| Broadwell        | 6        | 1.85%   |
| Steamroller      | 4        | 1.23%   |
| Silvermont       | 4        | 1.23%   |
| K8 Hammer        | 4        | 1.23%   |
| Gracemont        | 3        | 0.92%   |
| NetBurst         | 2        | 0.62%   |
| Nehalem          | 2        | 0.62%   |
| K10 Llano        | 2        | 0.62%   |
| IceLake          | 2        | 0.62%   |
| Excavator        | 2        | 0.62%   |
| Core             | 2        | 0.62%   |
| Alderlake Hybrid | 2        | 0.62%   |
| Goldmont         | 1        | 0.31%   |
| Bulldozer        | 1        | 0.31%   |
| Bonnell          | 1        | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 129      | 35.54%  |
| Intel             | 126      | 34.71%  |
| AMD               | 106      | 29.2%   |
| VIA Technologies  | 1        | 0.28%   |
| ASPEED Technology | 1        | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 19       | 5.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 18       | 4.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16       | 4.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 12       | 3.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 3.2%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 2.4%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 2.4%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 2.13%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 8        | 2.13%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.87%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 1.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.87%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 1.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.33%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4        | 1.07%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 4        | 1.07%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 4        | 1.07%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 1.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.8%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 0.8%    |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.8%    |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 3        | 0.8%    |
| Intel Alder Lake-N [UHD Graphics]                                           | 3        | 0.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 0.8%    |
| AMD Raphael                                                                 | 3        | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 0.8%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 0.8%    |
| AMD Granite Ridge [Radeon Graphics]                                         | 3        | 0.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 0.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 109      | 32.15%  |
| 1 x Intel            | 103      | 30.38%  |
| 1 x AMD              | 95       | 28.02%  |
| Intel + Nvidia       | 10       | 2.95%   |
| AMD + Nvidia         | 9        | 2.65%   |
| 2 x AMD              | 3        | 0.88%   |
| Intel + AMD          | 2        | 0.59%   |
| 3 x Nvidia           | 1        | 0.29%   |
| 2 x Nvidia           | 1        | 0.29%   |
| 2 x AMD + 2 x Nvidia | 1        | 0.29%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.29%   |
| 1 x VIA              | 1        | 0.29%   |
| Intel + 2 x Nvidia   | 1        | 0.29%   |
| 1 x ASPEED           | 1        | 0.29%   |
| AMD + 2 x Nvidia     | 1        | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 253      | 76.2%   |
| Proprietary | 64       | 19.28%  |
| Unknown     | 15       | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 182      | 53.37%  |
| 1.01-2.0   | 38       | 11.14%  |
| 7.01-8.0   | 31       | 9.09%   |
| 3.01-4.0   | 26       | 7.62%   |
| 0.51-1.0   | 24       | 7.04%   |
| 0.01-0.5   | 23       | 6.74%   |
| 5.01-6.0   | 9        | 2.64%   |
| 2.01-3.0   | 3        | 0.88%   |
| 8.01-16.0  | 3        | 0.88%   |
| 4.01-5.0   | 1        | 0.29%   |
| 16.01-24.0 | 1        | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 58       | 17.21%  |
| Acer                 | 52       | 15.43%  |
| Goldstar             | 51       | 15.13%  |
| Dell                 | 29       | 8.61%   |
| AOC                  | 20       | 5.93%   |
| Hewlett-Packard      | 19       | 5.64%   |
| Lenovo               | 13       | 3.86%   |
| BenQ                 | 10       | 2.97%   |
| ViewSonic            | 8        | 2.37%   |
| MSI                  | 7        | 2.08%   |
| LG Electronics       | 6        | 1.78%   |
| Unknown (XXX)        | 4        | 1.19%   |
| Unknown              | 3        | 0.89%   |
| RTK                  | 3        | 0.89%   |
| Philips              | 3        | 0.89%   |
| MStar                | 3        | 0.89%   |
| ASUSTek Computer     | 3        | 0.89%   |
| Ancor Communications | 3        | 0.89%   |
| Wacom                | 2        | 0.59%   |
| Sharp                | 2        | 0.59%   |
| SGT                  | 2        | 0.59%   |
| Microstep            | 2        | 0.59%   |
| Mi                   | 2        | 0.59%   |
| MHH                  | 2        | 0.59%   |
| ITE                  | 2        | 0.59%   |
| IPA                  | 2        | 0.59%   |
| IOD                  | 2        | 0.59%   |
| Fujitsu              | 2        | 0.59%   |
| AVX                  | 2        | 0.59%   |
| Apple                | 2        | 0.59%   |
| ___                  | 1        | 0.3%    |
| VIZTA                | 1        | 0.3%    |
| Toshiba              | 1        | 0.3%    |
| Sony                 | 1        | 0.3%    |
| SKY                  | 1        | 0.3%    |
| MIG                  | 1        | 0.3%    |
| JRY                  | 1        | 0.3%    |
| Intehill             | 1        | 0.3%    |
| HUYINIUDA            | 1        | 0.3%    |
| HPN                  | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                        | 6        | 1.68%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 5        | 1.4%    |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                       | 4        | 1.12%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                       | 4        | 1.12%   |
| Acer K222HQL ACR0512 1920x1080 480x270mm 21.7-inch                      | 4        | 1.12%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 3        | 0.84%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch        | 3        | 0.84%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                        | 3        | 0.84%   |
| Philips 236V4 PHLC0B3 1920x1080 510x287mm 23.0-inch                     | 3        | 0.84%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 3        | 0.84%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 3        | 0.84%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                  | 3        | 0.84%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                        | 3        | 0.84%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                        | 3        | 0.84%   |
| AOC 2381 AOC2381 1920x1080 509x286mm 23.0-inch                          | 3        | 0.84%   |
| Acer K242HQL ACR042E 1920x1080 521x293mm 23.5-inch                      | 3        | 0.84%   |
| Wacom One 13 WAC1070 1920x1080 294x166mm 13.3-inch                      | 2        | 0.56%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                  | 2        | 0.56%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch    | 2        | 0.56%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch        | 2        | 0.56%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 2        | 0.56%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x287mm 23.0-inch       | 2        | 0.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 2        | 0.56%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 2        | 0.56%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 2        | 0.56%   |
| Samsung Electronics LS27CG51x SAM72FC 2560x1440 597x336mm 27.0-inch     | 2        | 0.56%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch     | 2        | 0.56%   |
| Samsung Electronics LCD Monitor SAM7557 3840x2160 1872x1053mm 84.6-inch | 2        | 0.56%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 2        | 0.56%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 2        | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2        | 0.56%   |
| MSI MP251 MSI30C2 1920x1080 543x302mm 24.5-inch                         | 2        | 0.56%   |
| MHH HDMI1 MHH2024 1920x1080 527x296mm 23.8-inch                         | 2        | 0.56%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                      | 2        | 0.56%   |
| Lenovo LEN T2224dA LEN60EB 1920x1080 476x268mm 21.5-inch                | 2        | 0.56%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch              | 2        | 0.56%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2        | 0.56%   |
| Goldstar E2042 GSM4ED8 1600x900 443x249mm 20.0-inch                     | 2        | 0.56%   |
| Goldstar E1940 GSM4BD7 1360x768 406x229mm 18.4-inch                     | 2        | 0.56%   |
| Goldstar 34GL750 GSM773B 2560x1080 798x334mm 34.1-inch                  | 2        | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 162      | 49.85%  |
| 3840x2160 (4K)     | 30       | 9.23%   |
| 1600x900 (HD+)     | 25       | 7.69%   |
| 1366x768 (WXGA)    | 20       | 6.15%   |
| 2560x1440 (QHD)    | 19       | 5.85%   |
| 1440x900 (WXGA+)   | 11       | 3.38%   |
| 1680x1050 (WSXGA+) | 10       | 3.08%   |
| 2560x1080          | 8        | 2.46%   |
| 1360x768           | 8        | 2.46%   |
| Unknown            | 6        | 1.85%   |
| 3440x1440          | 5        | 1.54%   |
| 1280x1024 (SXGA)   | 5        | 1.54%   |
| 3840x1080          | 2        | 0.62%   |
| 1920x1200 (WUXGA)  | 2        | 0.62%   |
| 1600x1200          | 2        | 0.62%   |
| 1280x720 (HD)      | 2        | 0.62%   |
| 5120x1440          | 1        | 0.31%   |
| 3840x2400          | 1        | 0.31%   |
| 3520x1080          | 1        | 0.31%   |
| 2732x768           | 1        | 0.31%   |
| 2560x1600          | 1        | 0.31%   |
| 2288x1287          | 1        | 0.31%   |
| 2160x1440          | 1        | 0.31%   |
| 1280x960           | 1        | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 54       | 15.98%  |
| 24      | 41       | 12.13%  |
| 21      | 40       | 11.83%  |
| 27      | 35       | 10.36%  |
| Unknown | 27       | 7.99%   |
| 18      | 22       | 6.51%   |
| 20      | 20       | 5.92%   |
| 19      | 20       | 5.92%   |
| 31      | 11       | 3.25%   |
| 34      | 9        | 2.66%   |
| 22      | 7        | 2.07%   |
| 84      | 5        | 1.48%   |
| 63      | 5        | 1.48%   |
| 17      | 5        | 1.48%   |
| 32      | 4        | 1.18%   |
| 15      | 4        | 1.18%   |
| 72      | 3        | 0.89%   |
| 54      | 3        | 0.89%   |
| 52      | 3        | 0.89%   |
| 13      | 3        | 0.89%   |
| 40      | 2        | 0.59%   |
| 29      | 2        | 0.59%   |
| 26      | 2        | 0.59%   |
| 16      | 2        | 0.59%   |
| 142     | 1        | 0.3%    |
| 74      | 1        | 0.3%    |
| 60      | 1        | 0.3%    |
| 46      | 1        | 0.3%    |
| 43      | 1        | 0.3%    |
| 39      | 1        | 0.3%    |
| 36      | 1        | 0.3%    |
| 28      | 1        | 0.3%    |
| 25      | 1        | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 122      | 37.77%  |
| 401-500        | 105      | 32.51%  |
| Unknown        | 27       | 8.36%   |
| 701-800        | 14       | 4.33%   |
| 601-700        | 13       | 4.02%   |
| 1001-1500      | 13       | 4.02%   |
| 301-350        | 9        | 2.79%   |
| 1501-2000      | 8        | 2.48%   |
| 351-400        | 4        | 1.24%   |
| 801-900        | 3        | 0.93%   |
| 201-300        | 3        | 0.93%   |
| More than 2000 | 1        | 0.31%   |
| 901-1000       | 1        | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 236      | 76.62%  |
| 16/10   | 30       | 9.74%   |
| Unknown | 22       | 7.14%   |
| 21/9    | 10       | 3.25%   |
| 5/4     | 7        | 2.27%   |
| 4/3     | 1        | 0.32%   |
| 2.00    | 1        | 0.32%   |
| 1.00    | 1        | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 120      | 36.25%  |
| 151-200        | 49       | 14.8%   |
| 301-350        | 37       | 11.18%  |
| Unknown        | 27       | 8.16%   |
| 351-500        | 25       | 7.55%   |
| 141-150        | 23       | 6.95%   |
| More than 1000 | 21       | 6.34%   |
| 251-300        | 12       | 3.63%   |
| 501-1000       | 6        | 1.81%   |
| 101-110        | 4        | 1.21%   |
| 71-80          | 3        | 0.91%   |
| 131-140        | 2        | 0.6%    |
| 121-130        | 1        | 0.3%    |
| 111-120        | 1        | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 192      | 61.34%  |
| 101-120       | 62       | 19.81%  |
| Unknown       | 27       | 8.63%   |
| 1-50          | 15       | 4.79%   |
| 121-160       | 9        | 2.88%   |
| 161-240       | 7        | 2.24%   |
| More than 240 | 1        | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 272      | 80.47%  |
| 2     | 39       | 11.54%  |
| 0     | 20       | 5.92%   |
| 3     | 7        | 2.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 229      | 46.17%  |
| Intel                           | 129      | 26.01%  |
| Qualcomm Atheros                | 29       | 5.85%   |
| Ralink Technology               | 16       | 3.23%   |
| Broadcom                        | 13       | 2.62%   |
| TP-Link                         | 11       | 2.22%   |
| D-Link                          | 11       | 2.22%   |
| MediaTek                        | 9        | 1.81%   |
| Nvidia                          | 6        | 1.21%   |
| Xiaomi                          | 4        | 0.81%   |
| Samsung Electronics             | 4        | 0.81%   |
| Mercucys                        | 4        | 0.81%   |
| Edimax Technology               | 4        | 0.81%   |
| D-Link System                   | 4        | 0.81%   |
| Broadcom Limited                | 4        | 0.81%   |
| ASUSTek Computer                | 4        | 0.81%   |
| Ralink                          | 3        | 0.6%    |
| OPPO Electronics                | 2        | 0.4%    |
| VIA Technologies                | 1        | 0.2%    |
| Qualcomm Technologies           | 1        | 0.2%    |
| Qualcomm Atheros Communications | 1        | 0.2%    |
| OpenMoko                        | 1        | 0.2%    |
| OnePlus Technology (Shenzhen)   | 1        | 0.2%    |
| Huawei Technologies             | 1        | 0.2%    |
| BUFFALO                         | 1        | 0.2%    |
| AVM                             | 1        | 0.2%    |
| Aquantia                        | 1        | 0.2%    |
| Adafruit                        | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 181      | 32.09%  |
| Realtek RTL8125 2.5GbE Controller                                      | 20       | 3.55%   |
| Intel Wi-Fi 6 AX200                                                    | 17       | 3.01%   |
| Intel I211 Gigabit Network Connection                                  | 14       | 2.48%   |
| Intel Ethernet Connection I217-LM                                      | 13       | 2.3%    |
| Intel Ethernet Connection (2) I219-V                                   | 10       | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10       | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8        | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8        | 1.42%   |
| Realtek 802.11ac NIC                                                   | 8        | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8        | 1.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7        | 1.24%   |
| Ralink MT7601U Wireless Adapter                                        | 7        | 1.24%   |
| Intel Wireless 7260                                                    | 6        | 1.06%   |
| Intel Ethernet Connection I217-V                                       | 6        | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 0.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 0.89%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.89%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]          | 5        | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4        | 0.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 4        | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4        | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 4        | 0.71%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 0.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 0.71%   |
| Intel Wireless 7265                                                    | 4        | 0.71%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4        | 0.71%   |
| Intel Ethernet Controller I225-V                                       | 4        | 0.71%   |
| Intel Ethernet Connection (2) I218-V                                   | 4        | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3        | 0.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 3        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3        | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3        | 0.53%   |
| Mercucys 802.11n NIC                                                   | 3        | 0.53%   |
| Intel Ethernet Connection (12) I219-V                                  | 3        | 0.53%   |
| Intel Ethernet Connection (11) I219-LM                                 | 3        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 0.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 55       | 26.44%  |
| Intel                           | 52       | 25%     |
| Qualcomm Atheros                | 24       | 11.54%  |
| Ralink Technology               | 16       | 7.69%   |
| TP-Link                         | 11       | 5.29%   |
| D-Link                          | 11       | 5.29%   |
| MediaTek                        | 9        | 4.33%   |
| Broadcom                        | 7        | 3.37%   |
| Mercucys                        | 4        | 1.92%   |
| Edimax Technology               | 4        | 1.92%   |
| ASUSTek Computer                | 4        | 1.92%   |
| Ralink                          | 3        | 1.44%   |
| Broadcom Limited                | 3        | 1.44%   |
| D-Link System                   | 2        | 0.96%   |
| Qualcomm Atheros Communications | 1        | 0.48%   |
| BUFFALO                         | 1        | 0.48%   |
| AVM                             | 1        | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 17       | 8.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 8        | 3.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 8        | 3.81%   |
| Realtek 802.11ac NIC                                                 | 8        | 3.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8        | 3.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 7        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                      | 7        | 3.33%   |
| Intel Wireless 7260                                                  | 6        | 2.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 5        | 2.38%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]        | 5        | 2.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 4        | 1.9%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 4        | 1.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 4        | 1.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 4        | 1.9%    |
| Intel Wireless 7265                                                  | 4        | 1.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4        | 1.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 3        | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 3        | 1.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3        | 1.43%   |
| Mercucys 802.11n NIC                                                 | 3        | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 1.43%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 3        | 1.43%   |
| D-Link 802.11 n WLAN                                                 | 3        | 1.43%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3        | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3        | 1.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 0.95%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 0.95%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 2        | 0.95%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 2        | 0.95%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2        | 0.95%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 2        | 0.95%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 2        | 0.95%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 2        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2        | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 0.95%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 2        | 0.95%   |
| Intel Wireless 3165                                                  | 2        | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 209      | 61.47%  |
| Intel                         | 95       | 27.94%  |
| Qualcomm Atheros              | 7        | 2.06%   |
| Nvidia                        | 6        | 1.76%   |
| Broadcom                      | 6        | 1.76%   |
| Xiaomi                        | 4        | 1.18%   |
| Samsung Electronics           | 4        | 1.18%   |
| OPPO Electronics              | 2        | 0.59%   |
| D-Link System                 | 2        | 0.59%   |
| VIA Technologies              | 1        | 0.29%   |
| Qualcomm Technologies         | 1        | 0.29%   |
| OnePlus Technology (Shenzhen) | 1        | 0.29%   |
| Broadcom Limited              | 1        | 0.29%   |
| Aquantia                      | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 181      | 51.57%  |
| Realtek RTL8125 2.5GbE Controller                                      | 20       | 5.7%    |
| Intel I211 Gigabit Network Connection                                  | 14       | 3.99%   |
| Intel Ethernet Connection I217-LM                                      | 13       | 3.7%    |
| Intel Ethernet Connection (2) I219-V                                   | 10       | 2.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10       | 2.85%   |
| Intel Ethernet Connection I217-V                                       | 6        | 1.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 1.42%   |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 1.42%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5        | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 1.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4        | 1.14%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 1.14%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.14%   |
| Intel Ethernet Connection (2) I218-V                                   | 4        | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3        | 0.85%   |
| Intel Ethernet Connection (12) I219-V                                  | 3        | 0.85%   |
| Intel Ethernet Connection (11) I219-LM                                 | 3        | 0.85%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2        | 0.57%   |
| OPPO Ace 3V                                                            | 2        | 0.57%   |
| Nvidia MCP73 Ethernet                                                  | 2        | 0.57%   |
| Intel Ethernet Connection I218-V                                       | 2        | 0.57%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.57%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 0.57%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 0.57%   |
| Xiaomi 100Mbps Network Card Adapter                                    | 1        | 0.28%   |
| VIA VT6120/VT6121/VT6122/VT6130 Gigabit Ethernet Adapter               | 1        | 0.28%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter               | 1        | 0.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.28%   |
| Realtek RTL8126 5GbE Controller                                        | 1        | 0.28%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.28%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 1        | 0.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 315      | 62.62%  |
| WiFi     | 185      | 36.78%  |
| Modem    | 3        | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 209      | 61.83%  |
| WiFi     | 129      | 38.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 193      | 58.84%  |
| 2     | 116      | 35.37%  |
| 3     | 10       | 3.05%   |
| 0     | 6        | 1.83%   |
| 4     | 2        | 0.61%   |
| 5     | 1        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 216      | 64.29%  |
| Yes  | 120      | 35.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 48       | 32.21%  |
| Cambridge Silicon Radio         | 38       | 25.5%   |
| Realtek Semiconductor           | 16       | 10.74%  |
| Qualcomm Atheros Communications | 7        | 4.7%    |
| MediaTek                        | 7        | 4.7%    |
| TP-Link                         | 6        | 4.03%   |
| Apple                           | 5        | 3.36%   |
| ASUSTek Computer                | 4        | 2.68%   |
| Unknown                         | 4        | 2.68%   |
| Lite-On Technology              | 3        | 2.01%   |
| IMC Networks                    | 3        | 2.01%   |
| Foxconn / Hon Hai               | 2        | 1.34%   |
| Broadcom                        | 2        | 1.34%   |
| Actions                         | 2        | 1.34%   |
| Toshiba                         | 1        | 0.67%   |
| Foxconn International           | 1        | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 38       | 25.5%   |
| Intel AX200 Bluetooth                               | 17       | 11.41%  |
| Realtek Bluetooth Radio                             | 13       | 8.72%   |
| Intel Bluetooth wireless interface                  | 13       | 8.72%   |
| MediaTek Wireless_Device                            | 7        | 4.7%    |
| TP-Link TP-T@- UB500 Adapter                        | 6        | 4.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 5        | 3.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 2.68%   |
| Intel AX210 Bluetooth                               | 4        | 2.68%   |
| Unknown                                             | 4        | 2.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 2.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 2.01%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 1.34%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2        | 1.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2        | 1.34%   |
| Intel Bluetooth Device                              | 2        | 1.34%   |
| Intel AX201 Bluetooth                               | 2        | 1.34%   |
| IMC Networks Bluetooth Device                       | 2        | 1.34%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 1.34%   |
| Apple Bluetooth USB Host Controller                 | 2        | 1.34%   |
| Actions general adapter                             | 2        | 1.34%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 0.67%   |
| Realtek Bluetooth 5.4 Radio                         | 1        | 0.67%   |
| Lite-On Bluetooth Device                            | 1        | 0.67%   |
| IMC Networks Bluetooth Radio                        | 1        | 0.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 0.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 0.67%   |
| Broadcom HP Portable Valentine                      | 1        | 0.67%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 0.67%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 0.67%   |
| ASUS Bluetooth Device                               | 1        | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 0.67%   |
| Apple Bluetooth Host Controller                     | 1        | 0.67%   |
| Apple Bluetooth HCI                                 | 1        | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 216      | 38.57%  |
| AMD                                          | 136      | 24.29%  |
| Nvidia                                       | 122      | 21.79%  |
| C-Media Electronics                          | 16       | 2.86%   |
| JMTek                                        | 8        | 1.43%   |
| Generalplus Technology                       | 7        | 1.25%   |
| Razer USA                                    | 4        | 0.71%   |
| Creative Labs                                | 4        | 0.71%   |
| Logitech                                     | 3        | 0.54%   |
| Elan Microelectronics                        | 3        | 0.54%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.36%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.36%   |
| Texas Instruments                            | 2        | 0.36%   |
| SAVITECH                                     | 2        | 0.36%   |
| Micro Star International                     | 2        | 0.36%   |
| Lenovo                                       | 2        | 0.36%   |
| Kingston Technology                          | 2        | 0.36%   |
| Focusrite-Novation                           | 2        | 0.36%   |
| Astro Gaming                                 | 2        | 0.36%   |
| Walmart                                      | 1        | 0.18%   |
| VIA Technologies                             | 1        | 0.18%   |
| Syntek                                       | 1        | 0.18%   |
| Soundprese                                   | 1        | 0.18%   |
| Solid State Logic                            | 1        | 0.18%   |
| Nordic Semiconductor ASA                     | 1        | 0.18%   |
| MV-SILICON                                   | 1        | 0.18%   |
| KTMicro                                      | 1        | 0.18%   |
| Jieli Technology                             | 1        | 0.18%   |
| Hewlett-Packard                              | 1        | 0.18%   |
| ESS Technology                               | 1        | 0.18%   |
| Ensoniq                                      | 1        | 0.18%   |
| Elgato Systems                               | 1        | 0.18%   |
| Earth Computer Technologies                  | 1        | 0.18%   |
| Creative Technology                          | 1        | 0.18%   |
| Corsair                                      | 1        | 0.18%   |
| Cambridge Silicon Radio                      | 1        | 0.18%   |
| Blue Microphones                             | 1        | 0.18%   |
| Barco Display Systems                        | 1        | 0.18%   |
| Audio-Technica                               | 1        | 0.18%   |
| Audient                                      | 1        | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 34       | 5.04%   |
| AMD Ryzen HD Audio Controller                                              | 28       | 4.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 26       | 3.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 26       | 3.86%   |
| Intel 200 Series PCH HD Audio                                              | 24       | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23       | 3.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 23       | 3.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19       | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17       | 2.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 2.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 1.93%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 12       | 1.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 11       | 1.63%   |
| AMD FCH Azalia Controller                                                  | 11       | 1.63%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10       | 1.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 9        | 1.34%   |
| Nvidia High Definition Audio Controller                                    | 9        | 1.34%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 1.34%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 1.34%   |
| AMD Radeon High Definition Audio Controller                                | 8        | 1.19%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.04%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 7        | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7        | 1.04%   |
| Generalplus Technology USB Audio Device                                    | 7        | 1.04%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 0.89%   |
| JMTek USB PnP Audio Device                                                 | 6        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 6        | 0.89%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 6        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 0.74%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 5        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 67       | 37.22%  |
| SK hynix            | 26       | 14.44%  |
| Samsung Electronics | 19       | 10.56%  |
| Corsair             | 18       | 10%     |
| Unknown             | 15       | 8.33%   |
| Team                | 5        | 2.78%   |
| Micron Technology   | 5        | 2.78%   |
| Ramaxel Technology  | 4        | 2.22%   |
| Unknown             | 4        | 2.22%   |
| G.Skill             | 3        | 1.67%   |
| A-DATA Technology   | 3        | 1.67%   |
| Transcend           | 2        | 1.11%   |
| Hikvision           | 2        | 1.11%   |
| Apacer              | 2        | 1.11%   |
| Unknown (ABCD)      | 1        | 0.56%   |
| Unknown (0x02BA)    | 1        | 0.56%   |
| KLEVV               | 1        | 0.56%   |
| KingFast            | 1        | 0.56%   |
| ASint Technology    | 1        | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 5        | 2.51%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s    | 5        | 2.51%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s  | 5        | 2.51%   |
| Unknown                                                | 4        | 2.01%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 3        | 1.51%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s   | 3        | 1.51%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s     | 3        | 1.51%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.01%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 2        | 1.01%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s   | 2        | 1.01%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s   | 2        | 1.01%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s | 2        | 1.01%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s | 2        | 1.01%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 3200MT/s  | 2        | 1.01%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 2        | 1.01%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 2        | 1.01%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3             | 2        | 1.01%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s    | 2        | 1.01%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 2        | 1.01%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s         | 2        | 1.01%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s    | 2        | 1.01%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 2        | 1.01%   |
| Kingston RAM KF556C40-16 16GB DIMM DDR5 6800MT/s       | 2        | 1.01%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s    | 2        | 1.01%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s   | 2        | 1.01%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1600MT/s  | 2        | 1.01%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM SDRAM 1800MT/s   | 2        | 1.01%   |
| Corsair RAM CMK64GX5M2B5600C40 32GB DIMM DDR5 5600MT/s | 2        | 1.01%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3600MT/s | 2        | 1.01%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s  | 2        | 1.01%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s              | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 0.5%    |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s           | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s               | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 73       | 46.5%   |
| DDR3    | 51       | 32.48%  |
| SDRAM   | 9        | 5.73%   |
| DDR5    | 9        | 5.73%   |
| LPDDR4  | 4        | 2.55%   |
| DDR2    | 4        | 2.55%   |
| Unknown | 4        | 2.55%   |
| DDR     | 2        | 1.27%   |
| DRAM    | 1        | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 132      | 88%     |
| SODIMM       | 15       | 10%     |
| Row Of Chips | 1        | 0.67%   |
| RIMM         | 1        | 0.67%   |
| FB-DIMM      | 1        | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 70       | 41.18%  |
| 4096  | 43       | 25.29%  |
| 16384 | 23       | 13.53%  |
| 2048  | 17       | 10%     |
| 32768 | 10       | 5.88%   |
| 1024  | 6        | 3.53%   |
| 24576 | 1        | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 28       | 15.82%  |
| 1333    | 21       | 11.86%  |
| 2400    | 15       | 8.47%   |
| 2133    | 15       | 8.47%   |
| 3200    | 14       | 7.91%   |
| 3733    | 13       | 7.34%   |
| 2667    | 10       | 5.65%   |
| 3600    | 8        | 4.52%   |
| 1866    | 6        | 3.39%   |
| 3400    | 4        | 2.26%   |
| 6000    | 3        | 1.69%   |
| 3466    | 3        | 1.69%   |
| 3000    | 3        | 1.69%   |
| 2666    | 3        | 1.69%   |
| 1867    | 3        | 1.69%   |
| 1800    | 3        | 1.69%   |
| 667     | 3        | 1.69%   |
| 6800    | 2        | 1.13%   |
| 5600    | 2        | 1.13%   |
| 3800    | 2        | 1.13%   |
| 3151    | 2        | 1.13%   |
| 533     | 2        | 1.13%   |
| 8400    | 1        | 0.56%   |
| 6200    | 1        | 0.56%   |
| 5200    | 1        | 0.56%   |
| 3333    | 1        | 0.56%   |
| 2800    | 1        | 0.56%   |
| 2448    | 1        | 0.56%   |
| 2000    | 1        | 0.56%   |
| 1648    | 1        | 0.56%   |
| 1334    | 1        | 0.56%   |
| 800     | 1        | 0.56%   |
| 333     | 1        | 0.56%   |
| Unknown | 1        | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 6        | 50%     |
| Seiko Epson        | 2        | 16.67%  |
| STMicroelectronics | 1        | 8.33%   |
| Pantum             | 1        | 8.33%   |
| Hewlett-Packard    | 1        | 8.33%   |
| Canon              | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| STMicroelectronics USB Printing Support | 1        | 8.33%   |
| Seiko Epson LQ-310                      | 1        | 8.33%   |
| Seiko Epson EPSON L220 Series           | 1        | 8.33%   |
| Pantum P2500W series                    | 1        | 8.33%   |
| HP HP LaserJet Pro M404-M405            | 1        | 8.33%   |
| Canon E4200 series                      | 1        | 8.33%   |
| Brother HL-L2370DN series               | 1        | 8.33%   |
| Brother HL-1110 series                  | 1        | 8.33%   |
| Brother DCP-T510W                       | 1        | 8.33%   |
| Brother DCP-T300                        | 1        | 8.33%   |
| Brother DCP-L3551CDW                    | 1        | 8.33%   |
| Brother DCP-1510                        | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 13       | 26%     |
| Microdia                      | 7        | 14%     |
| Microsoft                     | 5        | 10%     |
| Sunplus Innovation Technology | 3        | 6%      |
| Generalplus Technology        | 3        | 6%      |
| Aveo Technology               | 3        | 6%      |
| Realtek Semiconductor         | 2        | 4%      |
| MacroSilicon                  | 2        | 4%      |
| Apple                         | 2        | 4%      |
| Z-Star Microelectronics       | 1        | 2%      |
| WCM_USB                       | 1        | 2%      |
| vivo                          | 1        | 2%      |
| Suyin                         | 1        | 2%      |
| Silicon Motion                | 1        | 2%      |
| Owon                          | 1        | 2%      |
| Jieli Technology              | 1        | 2%      |
| Huawei Technologies           | 1        | 2%      |
| eMeet                         | 1        | 2%      |
| AVerMedia Technologies        | 1        | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Microsoft Microsoft LifeCam Cinema    | 4        | 7.84%   |
| Microdia Camera                       | 4        | 7.84%   |
| Logitech Webcam C270                  | 4        | 7.84%   |
| MacroSilicon USB Video                | 2        | 3.92%   |
| Logitech Webcam C310                  | 2        | 3.92%   |
| Logitech C922 Pro Stream Webcam       | 2        | 3.92%   |
| Generalplus WEB CAM                   | 2        | 3.92%   |
| Generalplus GENERAL WEBCAM            | 2        | 3.92%   |
| Aveo USB2.0 Camera                    | 2        | 3.92%   |
| Z-Star Venus USB2.0 Camera            | 1        | 1.96%   |
| WCM_USB WEB CAM                       | 1        | 1.96%   |
| vivo V2514                            | 1        | 1.96%   |
| Suyin HP Integrated Webcam            | 1        | 1.96%   |
| Sunplus SPCA2281 Web Camera           | 1        | 1.96%   |
| Sunplus HK 5M WebCAM                  | 1        | 1.96%   |
| Sunplus FULL HD webcam                | 1        | 1.96%   |
| Silicon Motion 300k Pixel Camera      | 1        | 1.96%   |
| Realtek USB Boot                      | 1        | 1.96%   |
| Realtek Thronmax Stream Go Pro Webcam | 1        | 1.96%   |
| Owon USB CAMERA                       | 1        | 1.96%   |
| Microsoft LifeCam VX-2000             | 1        | 1.96%   |
| Microdia USB 2.0 Camera               | 1        | 1.96%   |
| Microdia Sonix USB 2.0 Camera         | 1        | 1.96%   |
| Microdia Integrated Camera            | 1        | 1.96%   |
| Logitech Webcam C600                  | 1        | 1.96%   |
| Logitech Mic (Notebooks Pro)          | 1        | 1.96%   |
| Logitech HD Webcam C525               | 1        | 1.96%   |
| Logitech HD Webcam C510               | 1        | 1.96%   |
| Logitech HD Pro Webcam C920           | 1        | 1.96%   |
| Jieli USB PHY 2.0                     | 1        | 1.96%   |
| Huawei HiCamera                       | 1        | 1.96%   |
| eMeet SmartCam C60E 4K                | 1        | 1.96%   |
| AVerMedia Live Gamer Mini             | 1        | 1.96%   |
| Aveo UVC camera (Bresser microscope)  | 1        | 1.96%   |
| Apple iSight in LED Cinema Display    | 1        | 1.96%   |
| Apple iPad 2 (3G; 64GB)               | 1        | 1.96%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 276      | 84.4%   |
| 1     | 45       | 13.76%  |
| 2     | 4        | 1.22%   |
| 7     | 1        | 0.31%   |
| 5     | 1        | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 20       | 33.9%   |
| Graphics card            | 15       | 25.42%  |
| Unassigned class         | 8        | 13.56%  |
| Sound                    | 6        | 10.17%  |
| Communication controller | 4        | 6.78%   |
| Net/ethernet             | 2        | 3.39%   |
| Storage/raid             | 1        | 1.69%   |
| Network                  | 1        | 1.69%   |
| Chipcard                 | 1        | 1.69%   |
| Camera                   | 1        | 1.69%   |

