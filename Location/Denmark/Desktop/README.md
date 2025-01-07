Linux in Denmark - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

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

Total: 687

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z97M-PLUS                   | [92c4bf7d7e](https://linux-hardware.org/?probe=92c4bf7d7e) | Jan 04, 2025 |
| MSI           | B550-A PRO                  | [b689309781](https://linux-hardware.org/?probe=b689309781) | Jan 04, 2025 |
| Gigabyte      | X670E AORUS MASTER          | [30d29839dc](https://linux-hardware.org/?probe=30d29839dc) | Jan 04, 2025 |
| Gigabyte      | X670E AORUS MASTER          | [ea5e598ed5](https://linux-hardware.org/?probe=ea5e598ed5) | Jan 01, 2025 |
| HP            | 845A                        | [6dd10c7e63](https://linux-hardware.org/?probe=6dd10c7e63) | Dec 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [90cec85bd7](https://linux-hardware.org/?probe=90cec85bd7) | Dec 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9e7734f37f](https://linux-hardware.org/?probe=9e7734f37f) | Dec 30, 2024 |
| ASUSTek       | P5E-VM HDMI                 | [241c643172](https://linux-hardware.org/?probe=241c643172) | Dec 29, 2024 |
| HP            | 845A                        | [d529dc1efc](https://linux-hardware.org/?probe=d529dc1efc) | Dec 24, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [976a838d5e](https://linux-hardware.org/?probe=976a838d5e) | Dec 22, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | [c64e9ff809](https://linux-hardware.org/?probe=c64e9ff809) | Dec 22, 2024 |
| Gigabyte      | B550 GAMING X               | [5e7733d216](https://linux-hardware.org/?probe=5e7733d216) | Dec 19, 2024 |
| Dell          | 0KC9NP A01                  | [40ceb358f9](https://linux-hardware.org/?probe=40ceb358f9) | Dec 12, 2024 |
| Gigabyte      | A520M S2H                   | [f9989a915e](https://linux-hardware.org/?probe=f9989a915e) | Dec 11, 2024 |
| HP            | 1905                        | [925e9c6a14](https://linux-hardware.org/?probe=925e9c6a14) | Dec 03, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [283e9a8b40](https://linux-hardware.org/?probe=283e9a8b40) | Dec 01, 2024 |
| HP            | 1905                        | [a3ed3e5797](https://linux-hardware.org/?probe=a3ed3e5797) | Dec 01, 2024 |
| ASUSTek       | PRIME Z690-A                | [bd4c200cbb](https://linux-hardware.org/?probe=bd4c200cbb) | Nov 15, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [01063d0f9e](https://linux-hardware.org/?probe=01063d0f9e) | Nov 08, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [eeaba99859](https://linux-hardware.org/?probe=eeaba99859) | Nov 05, 2024 |
| ASRock        | Z370 Pro4                   | [176e8e71c8](https://linux-hardware.org/?probe=176e8e71c8) | Nov 04, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2d99ad254b](https://linux-hardware.org/?probe=2d99ad254b) | Oct 31, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [d549dd1d0b](https://linux-hardware.org/?probe=d549dd1d0b) | Oct 31, 2024 |
| ASUSTek       | PRIME B650M-A II            | [84cfce45dd](https://linux-hardware.org/?probe=84cfce45dd) | Oct 30, 2024 |
| Gigabyte      | B650 GAMING X AX            | [d0efe8b27c](https://linux-hardware.org/?probe=d0efe8b27c) | Oct 27, 2024 |
| ASUSTek       | PRIME X470-PRO              | [6001ee3845](https://linux-hardware.org/?probe=6001ee3845) | Oct 26, 2024 |
| Gigabyte      | B650 GAMING X AX            | [502ef34bb8](https://linux-hardware.org/?probe=502ef34bb8) | Oct 26, 2024 |
| Pegatron      | 2A9A                        | [24640d55b1](https://linux-hardware.org/?probe=24640d55b1) | Oct 25, 2024 |
| HP            | 1495                        | [5f83604bb5](https://linux-hardware.org/?probe=5f83604bb5) | Oct 24, 2024 |
| Shenzhen M... | MTBSD                       | [6420cd8647](https://linux-hardware.org/?probe=6420cd8647) | Oct 18, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [817f8a9799](https://linux-hardware.org/?probe=817f8a9799) | Oct 17, 2024 |
| Gigabyte      | X570S AORUS MASTER          | [30fd511ed4](https://linux-hardware.org/?probe=30fd511ed4) | Oct 15, 2024 |
| ASRock        | X300-ITX                    | [b824ddb718](https://linux-hardware.org/?probe=b824ddb718) | Oct 13, 2024 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [5e90b0c4ed](https://linux-hardware.org/?probe=5e90b0c4ed) | Oct 11, 2024 |
| Dell          | 09KPNV A00                  | [87a6011b62](https://linux-hardware.org/?probe=87a6011b62) | Oct 09, 2024 |
| Gigabyte      | Z270X-Gaming K5             | [77b29b3523](https://linux-hardware.org/?probe=77b29b3523) | Oct 06, 2024 |
| HP            | 1495                        | [b374728264](https://linux-hardware.org/?probe=b374728264) | Oct 05, 2024 |
| MSI           | MS-7318                     | [94581471da](https://linux-hardware.org/?probe=94581471da) | Oct 03, 2024 |
| Dell          | 0D24M8 A01                  | [f4d0cccdf1](https://linux-hardware.org/?probe=f4d0cccdf1) | Sep 26, 2024 |
| Dell          | 0D24M8 A01                  | [93b881282f](https://linux-hardware.org/?probe=93b881282f) | Sep 26, 2024 |
| ASRock        | Z77 Extreme4-M              | [db437433af](https://linux-hardware.org/?probe=db437433af) | Sep 25, 2024 |
| Sugon         | X9DR3-FA                    | [637613a6fd](https://linux-hardware.org/?probe=637613a6fd) | Sep 23, 2024 |
| ASRock        | ION3D-HT                    | [0904b2ade3](https://linux-hardware.org/?probe=0904b2ade3) | Sep 14, 2024 |
| ASUSTek       | P6T DELUXE V2               | [8d1d2d8b47](https://linux-hardware.org/?probe=8d1d2d8b47) | Sep 13, 2024 |
| ASUSTek       | PRIME X570-P                | [9a0e29b5dd](https://linux-hardware.org/?probe=9a0e29b5dd) | Sep 09, 2024 |
| ASUSTek       | ROG Maximus XII HERO        | [547ecee59b](https://linux-hardware.org/?probe=547ecee59b) | Sep 09, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4ca41527c4](https://linux-hardware.org/?probe=4ca41527c4) | Sep 07, 2024 |
| ASUSTek       | PRIME B650M-A II            | [f6a7476614](https://linux-hardware.org/?probe=f6a7476614) | Sep 05, 2024 |
| ASUSTek       | PRIME X570-P                | [70ddee6281](https://linux-hardware.org/?probe=70ddee6281) | Sep 02, 2024 |
| ASUSTek       | PRIME A520M-R               | [e989d74788](https://linux-hardware.org/?probe=e989d74788) | Aug 25, 2024 |
| Pegatron      | 2AD5                        | [d57e937e5c](https://linux-hardware.org/?probe=d57e937e5c) | Aug 20, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [8fbb0e280b](https://linux-hardware.org/?probe=8fbb0e280b) | Aug 15, 2024 |
| ASUSTek       | PRIME B650M-A II            | [e9650bcedb](https://linux-hardware.org/?probe=e9650bcedb) | Aug 14, 2024 |
| MSI           | MEG X570 ACE                | [90b92d4581](https://linux-hardware.org/?probe=90b92d4581) | Aug 08, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [30943d6c8b](https://linux-hardware.org/?probe=30943d6c8b) | Aug 07, 2024 |
| ASUSTek       | PRIME Z370-P                | [f1b1c8064f](https://linux-hardware.org/?probe=f1b1c8064f) | Aug 07, 2024 |
| HP            | 1495                        | [09892140b3](https://linux-hardware.org/?probe=09892140b3) | Aug 06, 2024 |
| Acer          | Predator PO3-640            | [efe0a9a9ec](https://linux-hardware.org/?probe=efe0a9a9ec) | Aug 01, 2024 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [c87538bad4](https://linux-hardware.org/?probe=c87538bad4) | Jul 31, 2024 |
| HP            | ProLiant ML350p Gen8        | [b489c928ed](https://linux-hardware.org/?probe=b489c928ed) | Jul 30, 2024 |
| Lenovo        | SHARKBAY NOK                | [30bb835251](https://linux-hardware.org/?probe=30bb835251) | Jul 28, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | [007a26742b](https://linux-hardware.org/?probe=007a26742b) | Jul 27, 2024 |
| HP            | 8767 A                      | [d377d98814](https://linux-hardware.org/?probe=d377d98814) | Jul 26, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [4e32c4d0df](https://linux-hardware.org/?probe=4e32c4d0df) | Jul 25, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d222ae3b6b](https://linux-hardware.org/?probe=d222ae3b6b) | Jul 23, 2024 |
| ASRock        | Z370M-ITX/ac                | [aa41a92ff7](https://linux-hardware.org/?probe=aa41a92ff7) | Jul 16, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | [be094b7023](https://linux-hardware.org/?probe=be094b7023) | Jul 09, 2024 |
| MSI           | IONA                        | [7cd2bb087a](https://linux-hardware.org/?probe=7cd2bb087a) | Jul 07, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | [deca980aa2](https://linux-hardware.org/?probe=deca980aa2) | Jul 07, 2024 |
| Shenzhen M... | F7BFD                       | [84568865fd](https://linux-hardware.org/?probe=84568865fd) | Jul 03, 2024 |
| ASUSTek       | PRIME B250M-K               | [a8c85afdc3](https://linux-hardware.org/?probe=a8c85afdc3) | Jul 01, 2024 |
| ASUSTek       | G20CB                       | [f9758121e7](https://linux-hardware.org/?probe=f9758121e7) | Jun 28, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [397a4095b5](https://linux-hardware.org/?probe=397a4095b5) | Jun 25, 2024 |
| Pegatron      | 2AD5                        | [aa9dbd9aef](https://linux-hardware.org/?probe=aa9dbd9aef) | Jun 24, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [500ecbdf4d](https://linux-hardware.org/?probe=500ecbdf4d) | Jun 22, 2024 |
| ASUSTek       | PRIME B450M-A II            | [b66ab73d20](https://linux-hardware.org/?probe=b66ab73d20) | Jun 21, 2024 |
| ASRock        | 980DE3/U3S3 R2.0            | [f336a3694c](https://linux-hardware.org/?probe=f336a3694c) | Jun 18, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [627864177d](https://linux-hardware.org/?probe=627864177d) | Jun 15, 2024 |
| ASUSTek       | M5A78L-M LE/USB3            | [de724a5157](https://linux-hardware.org/?probe=de724a5157) | Jun 13, 2024 |
| HP            | 8B3B A                      | [4113887db5](https://linux-hardware.org/?probe=4113887db5) | Jun 01, 2024 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [7dc90447a3](https://linux-hardware.org/?probe=7dc90447a3) | May 28, 2024 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [0664d5b66b](https://linux-hardware.org/?probe=0664d5b66b) | May 22, 2024 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [ac7c8fc84c](https://linux-hardware.org/?probe=ac7c8fc84c) | May 20, 2024 |
| Dell          | 00V62H A00                  | [a2ede20616](https://linux-hardware.org/?probe=a2ede20616) | May 18, 2024 |
| ASUSTek       | PRIME Z790-P                | [cdc3686d63](https://linux-hardware.org/?probe=cdc3686d63) | May 17, 2024 |
| ASUSTek       | PRIME Z790-P                | [0429d68cf1](https://linux-hardware.org/?probe=0429d68cf1) | May 16, 2024 |
| MSI           | MPG Z390M GAMING EDGE AC    | [d0a537372c](https://linux-hardware.org/?probe=d0a537372c) | May 12, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9c65ad705b](https://linux-hardware.org/?probe=9c65ad705b) | May 12, 2024 |
| Intel         | X79G-A V2.0                 | [b4f5becaad](https://linux-hardware.org/?probe=b4f5becaad) | May 10, 2024 |
| MSI           | X570-A PRO                  | [6ee8d65521](https://linux-hardware.org/?probe=6ee8d65521) | May 05, 2024 |
| MSI           | X570-A PRO                  | [2fdf2caa36](https://linux-hardware.org/?probe=2fdf2caa36) | May 05, 2024 |
| Intel         | DP45SG AAE27733-405         | [a255bc14ce](https://linux-hardware.org/?probe=a255bc14ce) | May 03, 2024 |
| ASUSTek       | PRO H410T                   | [88ac4bb06e](https://linux-hardware.org/?probe=88ac4bb06e) | May 01, 2024 |
| ASUSTek       | PRIME X570-P                | [7011148205](https://linux-hardware.org/?probe=7011148205) | Apr 27, 2024 |
| ASUSTek       | PRO H410T                   | [9111d77eb9](https://linux-hardware.org/?probe=9111d77eb9) | Apr 26, 2024 |
| Gigabyte      | Z68X-UD7-B3                 | [6d342ea232](https://linux-hardware.org/?probe=6d342ea232) | Apr 26, 2024 |
| ASRock        | X399 Taichi                 | [0aeb871159](https://linux-hardware.org/?probe=0aeb871159) | Apr 22, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [f2d598a8a4](https://linux-hardware.org/?probe=f2d598a8a4) | Apr 19, 2024 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [58afd7824e](https://linux-hardware.org/?probe=58afd7824e) | Apr 19, 2024 |
| Dell          | 0VD5HY A07                  | [2ebf9fa814](https://linux-hardware.org/?probe=2ebf9fa814) | Apr 18, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [31768a3251](https://linux-hardware.org/?probe=31768a3251) | Apr 13, 2024 |
| ASUSTek       | P6X58D-E                    | [143efb64e8](https://linux-hardware.org/?probe=143efb64e8) | Apr 12, 2024 |
| ASUSTek       | Maximus IX FORMULA          | [0bb98b6d5d](https://linux-hardware.org/?probe=0bb98b6d5d) | Apr 06, 2024 |
| ASUSTek       | Maximus IX FORMULA          | [a7245399da](https://linux-hardware.org/?probe=a7245399da) | Apr 05, 2024 |
| Gigabyte      | Z370 AORUS Gaming 7         | [63429edd54](https://linux-hardware.org/?probe=63429edd54) | Apr 01, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [10b376d6b8](https://linux-hardware.org/?probe=10b376d6b8) | Apr 01, 2024 |
| HP            | 1495                        | [dd31afc968](https://linux-hardware.org/?probe=dd31afc968) | Mar 29, 2024 |
| HP            | 1495                        | [36d31b0971](https://linux-hardware.org/?probe=36d31b0971) | Mar 24, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [45e2102834](https://linux-hardware.org/?probe=45e2102834) | Mar 23, 2024 |
| ASUSTek       | P9X79                       | [3764bad531](https://linux-hardware.org/?probe=3764bad531) | Mar 21, 2024 |
| Gigabyte      | B550 GAMING X V2            | [fc818b5a1b](https://linux-hardware.org/?probe=fc818b5a1b) | Mar 18, 2024 |
| Intel         | X79G-A V2.0                 | [87e5ff547d](https://linux-hardware.org/?probe=87e5ff547d) | Mar 12, 2024 |
| ASRock        | Z170 Gaming-ITX/ac          | [7531c7cfa0](https://linux-hardware.org/?probe=7531c7cfa0) | Mar 09, 2024 |
| Dell          | 0D24M8 A01                  | [cdf2cddb43](https://linux-hardware.org/?probe=cdf2cddb43) | Mar 08, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [16b3359307](https://linux-hardware.org/?probe=16b3359307) | Mar 07, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4d569e557d](https://linux-hardware.org/?probe=4d569e557d) | Mar 07, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [3a49dcc141](https://linux-hardware.org/?probe=3a49dcc141) | Mar 02, 2024 |
| Dell          | 0WMJ54 A01                  | [6678e6f966](https://linux-hardware.org/?probe=6678e6f966) | Mar 01, 2024 |
| ASRock        | Z170 Gaming-ITX/ac          | [0e48c7f78f](https://linux-hardware.org/?probe=0e48c7f78f) | Mar 01, 2024 |
| Dell          | 0D24M8 A01                  | [6573368c36](https://linux-hardware.org/?probe=6573368c36) | Mar 01, 2024 |
| ASRock        | H97M Pro4                   | [a23d199357](https://linux-hardware.org/?probe=a23d199357) | Feb 29, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [d8df626171](https://linux-hardware.org/?probe=d8df626171) | Feb 25, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [5f1e566662](https://linux-hardware.org/?probe=5f1e566662) | Feb 22, 2024 |
| Gigabyte      | EP45T-UD3R                  | [e79901c3be](https://linux-hardware.org/?probe=e79901c3be) | Feb 19, 2024 |
| ASRock        | B650 PG Lightning           | [a3c86997db](https://linux-hardware.org/?probe=a3c86997db) | Feb 11, 2024 |
| Shenzhen M... | F7BSC                       | [ea6f15d115](https://linux-hardware.org/?probe=ea6f15d115) | Feb 10, 2024 |
| HP            | 8876 11                     | [79f1a90d1b](https://linux-hardware.org/?probe=79f1a90d1b) | Feb 04, 2024 |
| ASUSTek       | T-P5G31A                    | [ca450a3a63](https://linux-hardware.org/?probe=ca450a3a63) | Jan 28, 2024 |
| MSI           | Z170A TOMAHAWK AC           | [bd66397010](https://linux-hardware.org/?probe=bd66397010) | Jan 23, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [a3bc588c07](https://linux-hardware.org/?probe=a3bc588c07) | Jan 13, 2024 |
| ASRock        | B450M-HDV R4.0              | [b98e94bfb3](https://linux-hardware.org/?probe=b98e94bfb3) | Jan 13, 2024 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | [7049dd3f9a](https://linux-hardware.org/?probe=7049dd3f9a) | Jan 12, 2024 |
| Lenovo        | NO DPK                      | [739397b2fd](https://linux-hardware.org/?probe=739397b2fd) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [af48a525ff](https://linux-hardware.org/?probe=af48a525ff) | Jan 06, 2024 |
| HP            | 1495                        | [90db2bac77](https://linux-hardware.org/?probe=90db2bac77) | Jan 05, 2024 |
| HP            | 18E4                        | [e89784f165](https://linux-hardware.org/?probe=e89784f165) | Jan 05, 2024 |
| ASUSTek       | A4320A6420                  | [5df0f2025e](https://linux-hardware.org/?probe=5df0f2025e) | Jan 04, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [080172526c](https://linux-hardware.org/?probe=080172526c) | Dec 31, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [a80537094f](https://linux-hardware.org/?probe=a80537094f) | Dec 15, 2023 |
| HP            | 1497                        | [f2951d81c8](https://linux-hardware.org/?probe=f2951d81c8) | Dec 12, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [f47146cdb9](https://linux-hardware.org/?probe=f47146cdb9) | Dec 07, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| ASUSTek       | Z97-P                       | [109cecbcba](https://linux-hardware.org/?probe=109cecbcba) | Dec 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [a8e3339ba9](https://linux-hardware.org/?probe=a8e3339ba9) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| MSI           | IONA                        | [ccadf6afaf](https://linux-hardware.org/?probe=ccadf6afaf) | Nov 21, 2023 |
| ADLINK Tec... | MXE5400                     | [ae09533003](https://linux-hardware.org/?probe=ae09533003) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| Intel         | STK2MV64CC H89290-502       | [041670b7d8](https://linux-hardware.org/?probe=041670b7d8) | Nov 13, 2023 |
| Gigabyte      | EP45T-UD3R                  | [0940fc528f](https://linux-hardware.org/?probe=0940fc528f) | Nov 09, 2023 |
| HP            | 1495                        | [fe18b89530](https://linux-hardware.org/?probe=fe18b89530) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [bc3444ed2f](https://linux-hardware.org/?probe=bc3444ed2f) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3c1e4ea8bf](https://linux-hardware.org/?probe=3c1e4ea8bf) | Nov 04, 2023 |
| ASUSTek       | PRIME X570-P                | [f54d8e7dea](https://linux-hardware.org/?probe=f54d8e7dea) | Nov 01, 2023 |
| ASUSTek       | PRIME X570-P                | [9a2f1f7750](https://linux-hardware.org/?probe=9a2f1f7750) | Nov 01, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| Packard Be... | IMEDIA S2380                | [905b7ea7f0](https://linux-hardware.org/?probe=905b7ea7f0) | Oct 20, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [f824921cbb](https://linux-hardware.org/?probe=f824921cbb) | Oct 17, 2023 |
| ASUSTek       | PRIME B365M-K               | [e5e897e96a](https://linux-hardware.org/?probe=e5e897e96a) | Oct 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f68374e7cd](https://linux-hardware.org/?probe=f68374e7cd) | Oct 05, 2023 |
| ASRock        | B450 Gaming K4              | [8311d775a9](https://linux-hardware.org/?probe=8311d775a9) | Oct 01, 2023 |
| ASUSTek       | P9X79                       | [d663285ae0](https://linux-hardware.org/?probe=d663285ae0) | Sep 19, 2023 |
| ASRock        | B450 Gaming K4              | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| Acer          | Aspire X1470                | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| ASUSTek       | P5GC-MX                     | [7d13cd846d](https://linux-hardware.org/?probe=7d13cd846d) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | [595afb8cf0](https://linux-hardware.org/?probe=595afb8cf0) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| HP            | 1905                        | [f680d1c561](https://linux-hardware.org/?probe=f680d1c561) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| Dell          | 0XCR8D A02                  | [1f5f734faa](https://linux-hardware.org/?probe=1f5f734faa) | Aug 26, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | [7a89f9b5a7](https://linux-hardware.org/?probe=7a89f9b5a7) | Aug 26, 2023 |
| ASRock        | AB350 Pro4                  | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [a5eb82b4f9](https://linux-hardware.org/?probe=a5eb82b4f9) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| HP            | 844C                        | [36185008dc](https://linux-hardware.org/?probe=36185008dc) | Aug 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [3f09ac4cae](https://linux-hardware.org/?probe=3f09ac4cae) | Jul 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| ASRock        | X670E Steel Legend          | [8744428bf6](https://linux-hardware.org/?probe=8744428bf6) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| ASRock        | B450 Gaming K4              | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| Lenovo        | MAHOBAY                     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| ASRock        | B450 Gaming K4              | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [7573efcc6c](https://linux-hardware.org/?probe=7573efcc6c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [4b2cf13c22](https://linux-hardware.org/?probe=4b2cf13c22) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [ed171ca808](https://linux-hardware.org/?probe=ed171ca808) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| Acer          | Aspire XC600 v1.0           | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| ASUSTek       | PRIME Z590-P                | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| ASRock        | B450 Gaming K4              | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| ASUSTek       | PRIME Z390-A                | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [807dd44df4](https://linux-hardware.org/?probe=807dd44df4) | May 28, 2023 |
| MSI           | B150M MORTAR                | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| BESSTAR Te... | HM90                        | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| Gigabyte      | EP45T-UD3R                  | [848d0db1b2](https://linux-hardware.org/?probe=848d0db1b2) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | [9caca8f4cc](https://linux-hardware.org/?probe=9caca8f4cc) | May 10, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c8ab230418](https://linux-hardware.org/?probe=c8ab230418) | May 08, 2023 |
| Dell          | 0NW6H5 A00                  | [11e8fb1ecd](https://linux-hardware.org/?probe=11e8fb1ecd) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | [2675aa56c4](https://linux-hardware.org/?probe=2675aa56c4) | May 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| ASUSTek       | Z170-P                      | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| HP            | 339A                        | [1be48a395d](https://linux-hardware.org/?probe=1be48a395d) | Apr 21, 2023 |
| Acer          | Aspire XC-230               | [d31e8d7c7d](https://linux-hardware.org/?probe=d31e8d7c7d) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebdd0f2a6a](https://linux-hardware.org/?probe=ebdd0f2a6a) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [878d249691](https://linux-hardware.org/?probe=878d249691) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | [245db62c73](https://linux-hardware.org/?probe=245db62c73) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | [ad23efbf03](https://linux-hardware.org/?probe=ad23efbf03) | Apr 14, 2023 |
| HP            | 339A                        | [57e1af32cd](https://linux-hardware.org/?probe=57e1af32cd) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Lenovo        | NO DPK                      | [4d84f3549a](https://linux-hardware.org/?probe=4d84f3549a) | Apr 13, 2023 |
| MSI           | 970 GAMING                  | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| HP            | 3398                        | [ed9f84a231](https://linux-hardware.org/?probe=ed9f84a231) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASUSTek       | PRIME X570-P                | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| Acer          | Aspire X1935                | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [fd33b65218](https://linux-hardware.org/?probe=fd33b65218) | Mar 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | [80720d46a2](https://linux-hardware.org/?probe=80720d46a2) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH P67              | [dd01af3afe](https://linux-hardware.org/?probe=dd01af3afe) | Mar 03, 2023 |
| HP            | 3032h                       | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| Dell          | 01TN68 A02                  | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | [0dd1f15a92](https://linux-hardware.org/?probe=0dd1f15a92) | Feb 21, 2023 |
| HP            | 1497                        | [47ffeac7cf](https://linux-hardware.org/?probe=47ffeac7cf) | Feb 20, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [9f6834d4a9](https://linux-hardware.org/?probe=9f6834d4a9) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [131f8f99a2](https://linux-hardware.org/?probe=131f8f99a2) | Feb 17, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [01355a0714](https://linux-hardware.org/?probe=01355a0714) | Feb 17, 2023 |
| ASRock        | H81M-HDS                    | [b744809cc2](https://linux-hardware.org/?probe=b744809cc2) | Feb 14, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| HP            | 1905                        | [9ddf75323e](https://linux-hardware.org/?probe=9ddf75323e) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ef9c1299e6](https://linux-hardware.org/?probe=ef9c1299e6) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| ASRock        | B550M-ITX/ac                | [a7ac9067b0](https://linux-hardware.org/?probe=a7ac9067b0) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fd99b07929](https://linux-hardware.org/?probe=fd99b07929) | Jan 18, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [286de51ef8](https://linux-hardware.org/?probe=286de51ef8) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| ASRock        | B450M-HDV R4.0              | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | P85-D3                      | [8d017ea6af](https://linux-hardware.org/?probe=8d017ea6af) | Jan 01, 2023 |
| Gigabyte      | P85-D3                      | [aebeaf8b5e](https://linux-hardware.org/?probe=aebeaf8b5e) | Jan 01, 2023 |
| ASUSTek       | PRIME Z390-A                | [da48bed048](https://linux-hardware.org/?probe=da48bed048) | Dec 24, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [e964534175](https://linux-hardware.org/?probe=e964534175) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d367461182](https://linux-hardware.org/?probe=d367461182) | Dec 19, 2022 |
| ASUSTek       | PRIME Z270-A                | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| Gigabyte      | B650 GAMING X AX            | [2473215632](https://linux-hardware.org/?probe=2473215632) | Dec 10, 2022 |
| ASUSTek       | M80CJ-O                     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| Lenovo        | SHARKBAY NOK                | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [6b2389329d](https://linux-hardware.org/?probe=6b2389329d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9282404406](https://linux-hardware.org/?probe=9282404406) | Nov 30, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [1cc37489d5](https://linux-hardware.org/?probe=1cc37489d5) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [de3eac26e1](https://linux-hardware.org/?probe=de3eac26e1) | Nov 18, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [07b8a83017](https://linux-hardware.org/?probe=07b8a83017) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [75ffcfaf88](https://linux-hardware.org/?probe=75ffcfaf88) | Nov 11, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| Inventec      | DQ Class A02                | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| MSI           | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| Unknown       | TB-4000                     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Gigabyte      | P85-D3                      | [06b934d14f](https://linux-hardware.org/?probe=06b934d14f) | Aug 26, 2022 |
| Unknown       | TB-4000                     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Gigabyte      | B460M DS3H V2               | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Unknown       | TB-4000                     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| Gigabyte      | MJPLNAB-00                  | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| HP            | 805D                        | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b0c272ff93](https://linux-hardware.org/?probe=b0c272ff93) | Jun 26, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [d3fdbc7413](https://linux-hardware.org/?probe=d3fdbc7413) | Jun 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| Unknown       | TB-4000                     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| BESSTAR Te... | HM90                        | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| MSI           | 970A-G43                    | [92dd93dd78](https://linux-hardware.org/?probe=92dd93dd78) | May 24, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Unknown       | TB-4000                     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| MSI           | MS-1T11                     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [91aa85fff9](https://linux-hardware.org/?probe=91aa85fff9) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B250M-A               | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| ASUSTek       | PRIME A320M-K               | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| Dell          | 0KC9NP A01                  | [f9a0fa24f8](https://linux-hardware.org/?probe=f9a0fa24f8) | Feb 18, 2022 |
| ASRock        | FM2A55M-DGS                 | [efe38992bd](https://linux-hardware.org/?probe=efe38992bd) | Feb 15, 2022 |
| Dell          | 0GTK4K A02                  | [466029e620](https://linux-hardware.org/?probe=466029e620) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e63f72d407](https://linux-hardware.org/?probe=e63f72d407) | Feb 07, 2022 |
| Medion        | MS-7800                     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40ed6ce0c5](https://linux-hardware.org/?probe=40ed6ce0c5) | Feb 04, 2022 |
| Unknown       | TB-4000                     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b8f4a15736](https://linux-hardware.org/?probe=b8f4a15736) | Jan 25, 2022 |
| ASUSTek       | P8H67-M                     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| Gigabyte      | B460M AORUS PRO             | [1e301a4129](https://linux-hardware.org/?probe=1e301a4129) | Jan 19, 2022 |
| Acer          | Predator G6-710             | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASUSTek       | P8H67-M                     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| MSI           | A68HM GRENADE               | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| MSI           | X470 GAMING PRO             | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| HP            | 3031h                       | [8a8888c824](https://linux-hardware.org/?probe=8a8888c824) | Dec 17, 2021 |
| ABIT          | I-G31                       | [048b7bcf6a](https://linux-hardware.org/?probe=048b7bcf6a) | Dec 13, 2021 |
| Dell          | 0YXT71 A01                  | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| ASUSTek       | Z170-P                      | [6e857bc210](https://linux-hardware.org/?probe=6e857bc210) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASUSTek       | PRIME Z390-A                | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| HP            | 3031h                       | [68cf960e7f](https://linux-hardware.org/?probe=68cf960e7f) | Dec 02, 2021 |
| HP            | 3031h                       | [1c49cd6404](https://linux-hardware.org/?probe=1c49cd6404) | Dec 02, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Acer          | Aspire X3995                | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| ASRock        | Z170 Gaming K4              | [53281d6c95](https://linux-hardware.org/?probe=53281d6c95) | Nov 17, 2021 |
| Dell          | 0YXT71 A01                  | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| T-bao         | MINI PC V1.0                | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [be8c7e44de](https://linux-hardware.org/?probe=be8c7e44de) | Oct 23, 2021 |
| MSI           | Z77A-G45                    | [7a31ca9e22](https://linux-hardware.org/?probe=7a31ca9e22) | Oct 23, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [a36474b9ff](https://linux-hardware.org/?probe=a36474b9ff) | Oct 04, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASRock        | H470M-ITX/ac                | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [201176552b](https://linux-hardware.org/?probe=201176552b) | Sep 21, 2021 |
| Medion        | B360H4-EM V1.0              | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Dell          | 0XCR8D A02                  | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| ASRock        | P55M Pro                    | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASRock        | 980DE3/U3S3                 | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Medion        | MS-7616                     | [cbd20c24d8](https://linux-hardware.org/?probe=cbd20c24d8) | Aug 20, 2021 |
| HP            | 212B                        | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | P8B75-M                     | [4d29ffa0f7](https://linux-hardware.org/?probe=4d29ffa0f7) | Aug 03, 2021 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4135f29492](https://linux-hardware.org/?probe=4135f29492) | Aug 02, 2021 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [59cd9e3edd](https://linux-hardware.org/?probe=59cd9e3edd) | Aug 01, 2021 |
| Pegatron      | 2AB6                        | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | [51f83ebd4a](https://linux-hardware.org/?probe=51f83ebd4a) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Lenovo        | ThinkCentre Edge71 1577G... | [cf7f13e31c](https://linux-hardware.org/?probe=cf7f13e31c) | Jul 29, 2021 |
| ASRock        | H310CM-DVS                  | [5ae2994458](https://linux-hardware.org/?probe=5ae2994458) | Jul 28, 2021 |
| Medion        | Z370H4-EM                   | [f19570a630](https://linux-hardware.org/?probe=f19570a630) | Jul 24, 2021 |
| Shuttle       | FH67                        | [611a7c28dc](https://linux-hardware.org/?probe=611a7c28dc) | Jul 22, 2021 |
| Shuttle       | FH67                        | [3d3fb6c381](https://linux-hardware.org/?probe=3d3fb6c381) | Jul 22, 2021 |
| ASRock        | 980DE3/U3S3                 | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5fcfefa75a](https://linux-hardware.org/?probe=5fcfefa75a) | Jul 19, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [0c0d9cc784](https://linux-hardware.org/?probe=0c0d9cc784) | Jul 15, 2021 |
| ASUSTek       | PRIME Z370-A                | [208a9ee715](https://linux-hardware.org/?probe=208a9ee715) | Jun 23, 2021 |
| ASUSTek       | PRIME Z370-A                | [86fce52939](https://linux-hardware.org/?probe=86fce52939) | Jun 23, 2021 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [ca43a33e1d](https://linux-hardware.org/?probe=ca43a33e1d) | Jun 18, 2021 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [4a0a83693b](https://linux-hardware.org/?probe=4a0a83693b) | Jun 14, 2021 |
| ASRock        | P55M Pro                    | [cac3198045](https://linux-hardware.org/?probe=cac3198045) | Jun 14, 2021 |
| HP            | 212B                        | [b72ab2aea5](https://linux-hardware.org/?probe=b72ab2aea5) | Jun 09, 2021 |
| ASRock        | P55M Pro                    | [b994c1917a](https://linux-hardware.org/?probe=b994c1917a) | Jun 03, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| MSI           | Z87 MPOWER                  | [848def4822](https://linux-hardware.org/?probe=848def4822) | May 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [e0217f85a6](https://linux-hardware.org/?probe=e0217f85a6) | May 28, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| ASUSTek       | PRIME B450M-A               | [787c1b3a8c](https://linux-hardware.org/?probe=787c1b3a8c) | May 26, 2021 |
| ASUSTek       | B85M-G                      | [92f19ca1e6](https://linux-hardware.org/?probe=92f19ca1e6) | May 25, 2021 |
| ASUSTek       | NARRA2                      | [0b2cf24d70](https://linux-hardware.org/?probe=0b2cf24d70) | May 25, 2021 |
| Medion        | MS-7646                     | [799be90f9c](https://linux-hardware.org/?probe=799be90f9c) | May 11, 2021 |
| ASRock        | J4105-ITX                   | [2cb8135a58](https://linux-hardware.org/?probe=2cb8135a58) | May 08, 2021 |
| ASUSTek       | PRIME B450M-K               | [a8271c73ee](https://linux-hardware.org/?probe=a8271c73ee) | May 02, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9e0202e76a](https://linux-hardware.org/?probe=9e0202e76a) | Apr 27, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [31cb6e83ed](https://linux-hardware.org/?probe=31cb6e83ed) | Apr 19, 2021 |
| Acer          | Veriton M275                | [246a662951](https://linux-hardware.org/?probe=246a662951) | Apr 17, 2021 |
| Gigabyte      | B75M-D3H                    | [cd772af567](https://linux-hardware.org/?probe=cd772af567) | Apr 14, 2021 |
| Gigabyte      | EP35-DS4                    | [e37cf6fc8d](https://linux-hardware.org/?probe=e37cf6fc8d) | Apr 12, 2021 |
| MSI           | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09cf1ed052](https://linux-hardware.org/?probe=09cf1ed052) | Apr 08, 2021 |
| ASRock        | Z270 Pro4                   | [b90dd1b4d2](https://linux-hardware.org/?probe=b90dd1b4d2) | Apr 02, 2021 |
| Medion        | MS-7797                     | [947bc894eb](https://linux-hardware.org/?probe=947bc894eb) | Apr 01, 2021 |
| ASUSTek       | PRIME Z370-A                | [757d1d0707](https://linux-hardware.org/?probe=757d1d0707) | Mar 31, 2021 |
| ASUSTek       | PRIME Z370-A                | [eb1782ad49](https://linux-hardware.org/?probe=eb1782ad49) | Mar 31, 2021 |
| Dell          | 0CU409                      | [53a8c28aed](https://linux-hardware.org/?probe=53a8c28aed) | Mar 24, 2021 |
| Acer          | Aspire XC-605               | [f8ad366bd9](https://linux-hardware.org/?probe=f8ad366bd9) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [54288c23c9](https://linux-hardware.org/?probe=54288c23c9) | Mar 18, 2021 |
| ECS           | Nettle3                     | [f7ec16d7e7](https://linux-hardware.org/?probe=f7ec16d7e7) | Mar 16, 2021 |
| HP            | 3032h                       | [79b0bf2416](https://linux-hardware.org/?probe=79b0bf2416) | Mar 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [9ebf280981](https://linux-hardware.org/?probe=9ebf280981) | Mar 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | [efa91095ab](https://linux-hardware.org/?probe=efa91095ab) | Mar 05, 2021 |
| ASUSTek       | M4N75TD                     | [9daf1b6529](https://linux-hardware.org/?probe=9daf1b6529) | Feb 28, 2021 |
| ASUSTek       | P5P43TD                     | [3a2604a18a](https://linux-hardware.org/?probe=3a2604a18a) | Feb 27, 2021 |
| HP            | 1998                        | [43bd925171](https://linux-hardware.org/?probe=43bd925171) | Feb 27, 2021 |
| ASUSTek       | PRIME Z270-A                | [66ce820cff](https://linux-hardware.org/?probe=66ce820cff) | Feb 25, 2021 |
| ASRock        | QC5000-ITX/WiFi             | [d321b1eb90](https://linux-hardware.org/?probe=d321b1eb90) | Feb 21, 2021 |
| ASRock        | Z270 Pro4                   | [7114de29ed](https://linux-hardware.org/?probe=7114de29ed) | Feb 20, 2021 |
| Medion        | MS-7797                     | [3c4d9332e4](https://linux-hardware.org/?probe=3c4d9332e4) | Feb 19, 2021 |
| MSI           | B150M PRO-VH                | [255e61b850](https://linux-hardware.org/?probe=255e61b850) | Feb 13, 2021 |
| Medion        | MS-7797                     | [7e6811c842](https://linux-hardware.org/?probe=7e6811c842) | Feb 10, 2021 |
| Medion        | MS-7797                     | [394c3c87f4](https://linux-hardware.org/?probe=394c3c87f4) | Feb 10, 2021 |
| ASRock        | B550M-ITX/ac                | [909d040ae4](https://linux-hardware.org/?probe=909d040ae4) | Feb 07, 2021 |
| Medion        | MS-7708                     | [53ba901c28](https://linux-hardware.org/?probe=53ba901c28) | Feb 01, 2021 |
| Medion        | MS-7708                     | [8ef1638192](https://linux-hardware.org/?probe=8ef1638192) | Feb 01, 2021 |
| Lenovo        | ThinkServer TS140           | [8f911a91ca](https://linux-hardware.org/?probe=8f911a91ca) | Jan 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [34257c05a5](https://linux-hardware.org/?probe=34257c05a5) | Jan 27, 2021 |
| Gigabyte      | GA-780T-D3L                 | [2f2ede94cb](https://linux-hardware.org/?probe=2f2ede94cb) | Jan 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [fc3f785613](https://linux-hardware.org/?probe=fc3f785613) | Jan 15, 2021 |
| NEXCOM        | NDIS B322                   | [c2789ca746](https://linux-hardware.org/?probe=c2789ca746) | Jan 06, 2021 |
| Gigabyte      | B550M DS3H                  | [16d30d3356](https://linux-hardware.org/?probe=16d30d3356) | Dec 30, 2020 |
| Gigabyte      | B550M DS3H                  | [944fc761f4](https://linux-hardware.org/?probe=944fc761f4) | Dec 30, 2020 |
| ASUSTek       | Z97-K                       | [3eacdc5965](https://linux-hardware.org/?probe=3eacdc5965) | Dec 28, 2020 |
| MSI           | B150M PRO-VH                | [f225de5ed7](https://linux-hardware.org/?probe=f225de5ed7) | Dec 25, 2020 |
| MSI           | B150M PRO-VH                | [6971a673ec](https://linux-hardware.org/?probe=6971a673ec) | Dec 25, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [13d6a7172d](https://linux-hardware.org/?probe=13d6a7172d) | Dec 15, 2020 |
| Gigabyte      | J3455N-D3H                  | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [968983910f](https://linux-hardware.org/?probe=968983910f) | Dec 08, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [b3c78e0e70](https://linux-hardware.org/?probe=b3c78e0e70) | Dec 07, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [1a5eee726d](https://linux-hardware.org/?probe=1a5eee726d) | Dec 05, 2020 |
| MSI           | MPG Z490 GAMING PLUS        | [95b94bfe02](https://linux-hardware.org/?probe=95b94bfe02) | Dec 04, 2020 |
| MSI           | X570-A PRO                  | [0c57860179](https://linux-hardware.org/?probe=0c57860179) | Dec 02, 2020 |
| Medion        | B360H4-EM V1.0              | [718acb9fc0](https://linux-hardware.org/?probe=718acb9fc0) | Dec 02, 2020 |
| MSI           | B150M PRO-VH                | [ed280391f2](https://linux-hardware.org/?probe=ed280391f2) | Nov 30, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [f49b6c5048](https://linux-hardware.org/?probe=f49b6c5048) | Nov 27, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [ce4048d43f](https://linux-hardware.org/?probe=ce4048d43f) | Nov 24, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [9845e5eb1e](https://linux-hardware.org/?probe=9845e5eb1e) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [91207c72e3](https://linux-hardware.org/?probe=91207c72e3) | Nov 15, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [d2afbbe9f9](https://linux-hardware.org/?probe=d2afbbe9f9) | Nov 10, 2020 |
| Lenovo        | ThinkCentre Edge72 3484F... | [8864ed7825](https://linux-hardware.org/?probe=8864ed7825) | Nov 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [54f14d0d27](https://linux-hardware.org/?probe=54f14d0d27) | Nov 02, 2020 |
| ASRock        | Z170 OC Formula             | [067d0719a1](https://linux-hardware.org/?probe=067d0719a1) | Oct 30, 2020 |
| ASRock        | TRX40 Creator               | [3b1961ec14](https://linux-hardware.org/?probe=3b1961ec14) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2e111f0b77](https://linux-hardware.org/?probe=2e111f0b77) | Oct 29, 2020 |
| Dell          | 0CT017                      | [4f36a920b3](https://linux-hardware.org/?probe=4f36a920b3) | Oct 26, 2020 |
| ASRock        | B450M Pro4                  | [375a230939](https://linux-hardware.org/?probe=375a230939) | Oct 26, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [97ae9ff8fd](https://linux-hardware.org/?probe=97ae9ff8fd) | Oct 16, 2020 |
| ASUSTek       | PRIME B250M-A               | [afee01c14d](https://linux-hardware.org/?probe=afee01c14d) | Oct 11, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [734e996f73](https://linux-hardware.org/?probe=734e996f73) | Oct 07, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ce1874a3be](https://linux-hardware.org/?probe=ce1874a3be) | Oct 07, 2020 |
| ASRock        | Z170 Extreme4               | [39a631ad3c](https://linux-hardware.org/?probe=39a631ad3c) | Oct 06, 2020 |
| Pegatron      | 2AD5                        | [4d341edca9](https://linux-hardware.org/?probe=4d341edca9) | Oct 05, 2020 |
| MSI           | Z87 MPOWER                  | [c361400ba5](https://linux-hardware.org/?probe=c361400ba5) | Oct 02, 2020 |
| HP            | 3398                        | [95d758781c](https://linux-hardware.org/?probe=95d758781c) | Oct 01, 2020 |
| ASUSTek       | Z170-DELUXE                 | [619ac1f764](https://linux-hardware.org/?probe=619ac1f764) | Sep 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09b275ac93](https://linux-hardware.org/?probe=09b275ac93) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS PRO              | [1fd3e30c8e](https://linux-hardware.org/?probe=1fd3e30c8e) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5032W3M     | [b6dc69bcc6](https://linux-hardware.org/?probe=b6dc69bcc6) | Sep 23, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [4298ad10c2](https://linux-hardware.org/?probe=4298ad10c2) | Sep 05, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [d98e57a21a](https://linux-hardware.org/?probe=d98e57a21a) | Sep 05, 2020 |
| Gigabyte      | X570 GAMING X               | [9cd1bda591](https://linux-hardware.org/?probe=9cd1bda591) | Sep 04, 2020 |
| Medion        | MS-7366                     | [ff7271711d](https://linux-hardware.org/?probe=ff7271711d) | Aug 25, 2020 |
| HP            | 2AFA                        | [b60453f85a](https://linux-hardware.org/?probe=b60453f85a) | Aug 23, 2020 |
| HP            | 2AFA                        | [4c206cac6d](https://linux-hardware.org/?probe=4c206cac6d) | Aug 22, 2020 |
| ASUSTek       | Z170-PRO                    | [7a14a06010](https://linux-hardware.org/?probe=7a14a06010) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [9ac43f513b](https://linux-hardware.org/?probe=9ac43f513b) | Aug 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5c7a68d981](https://linux-hardware.org/?probe=5c7a68d981) | Aug 07, 2020 |
| Gigabyte      | Z77P-D3                     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| MSI           | B450 TOMAHAWK               | [c44d7421b8](https://linux-hardware.org/?probe=c44d7421b8) | Jul 24, 2020 |
| MSI           | X470 GAMING PRO             | [c12505e247](https://linux-hardware.org/?probe=c12505e247) | Jul 21, 2020 |
| MSI           | X470 GAMING PRO             | [ca1dac6b45](https://linux-hardware.org/?probe=ca1dac6b45) | Jul 21, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [861ca18aab](https://linux-hardware.org/?probe=861ca18aab) | Jul 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [ce07e0a768](https://linux-hardware.org/?probe=ce07e0a768) | Jul 14, 2020 |
| Lenovo        | ThinkCentre M58 7359WQR     | [73e0df5013](https://linux-hardware.org/?probe=73e0df5013) | Jul 09, 2020 |
| Gigabyte      | X570 UD                     | [ab1e04310e](https://linux-hardware.org/?probe=ab1e04310e) | Jul 07, 2020 |
| Gigabyte      | X570 UD                     | [319bbe63a2](https://linux-hardware.org/?probe=319bbe63a2) | Jul 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [1fa9af511a](https://linux-hardware.org/?probe=1fa9af511a) | Jul 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [57643353ce](https://linux-hardware.org/?probe=57643353ce) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9546ca8c2a](https://linux-hardware.org/?probe=9546ca8c2a) | Jun 29, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [b92d2bdb9d](https://linux-hardware.org/?probe=b92d2bdb9d) | Jun 28, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [8f5fc60880](https://linux-hardware.org/?probe=8f5fc60880) | Jun 20, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fdabb9483a](https://linux-hardware.org/?probe=fdabb9483a) | Jun 19, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [bef7a799cc](https://linux-hardware.org/?probe=bef7a799cc) | Jun 18, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [415c3a4a20](https://linux-hardware.org/?probe=415c3a4a20) | Jun 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [1bd41519c5](https://linux-hardware.org/?probe=1bd41519c5) | Jun 13, 2020 |
| ASUSTek       | Maximus VIII HERO           | [3e632a857d](https://linux-hardware.org/?probe=3e632a857d) | Jun 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [c83816398c](https://linux-hardware.org/?probe=c83816398c) | Jun 05, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [82591ffa30](https://linux-hardware.org/?probe=82591ffa30) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [637d3d6ccc](https://linux-hardware.org/?probe=637d3d6ccc) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bde3e045ca](https://linux-hardware.org/?probe=bde3e045ca) | May 31, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [58f57667ee](https://linux-hardware.org/?probe=58f57667ee) | May 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [8ab04c0e95](https://linux-hardware.org/?probe=8ab04c0e95) | May 22, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a1a244d013](https://linux-hardware.org/?probe=a1a244d013) | May 21, 2020 |
| AMI           | Cherry Trail FFD            | [2646be2c9b](https://linux-hardware.org/?probe=2646be2c9b) | May 17, 2020 |
| AMI           | Cherry Trail FFD            | [1abe48ca91](https://linux-hardware.org/?probe=1abe48ca91) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [aa8b123cdd](https://linux-hardware.org/?probe=aa8b123cdd) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [c6f0fde0d2](https://linux-hardware.org/?probe=c6f0fde0d2) | May 16, 2020 |
| Gigabyte      | GA-870A-UD3                 | [9d150cc443](https://linux-hardware.org/?probe=9d150cc443) | May 16, 2020 |
| ASUSTek       | B85M-G                      | [f575cb11cb](https://linux-hardware.org/?probe=f575cb11cb) | May 08, 2020 |
| ASRock        | B450 Gaming K4              | [d82dc4eb4f](https://linux-hardware.org/?probe=d82dc4eb4f) | May 01, 2020 |
| ASRock        | B450 Gaming K4              | [c08ec23742](https://linux-hardware.org/?probe=c08ec23742) | May 01, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [3d3bc60c59](https://linux-hardware.org/?probe=3d3bc60c59) | Apr 28, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [ed1abce019](https://linux-hardware.org/?probe=ed1abce019) | Apr 23, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [0cbe6fdb9b](https://linux-hardware.org/?probe=0cbe6fdb9b) | Apr 21, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [61d4286e96](https://linux-hardware.org/?probe=61d4286e96) | Apr 06, 2020 |
| ECS           | Nettle3                     | [51538f1902](https://linux-hardware.org/?probe=51538f1902) | Apr 02, 2020 |
| ECS           | Nettle3                     | [5a8f6b27a0](https://linux-hardware.org/?probe=5a8f6b27a0) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [fee80882b4](https://linux-hardware.org/?probe=fee80882b4) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [309423fc5a](https://linux-hardware.org/?probe=309423fc5a) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [cc7be1cc44](https://linux-hardware.org/?probe=cc7be1cc44) | Apr 02, 2020 |
| Dell          | 0F373D A00                  | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fbc59a267b](https://linux-hardware.org/?probe=fbc59a267b) | Mar 23, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [548b742928](https://linux-hardware.org/?probe=548b742928) | Mar 22, 2020 |
| HP            | ProLiant MicroServer        | [b8fc545d86](https://linux-hardware.org/?probe=b8fc545d86) | Mar 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [73276b8f74](https://linux-hardware.org/?probe=73276b8f74) | Mar 09, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [da8bd96ca5](https://linux-hardware.org/?probe=da8bd96ca5) | Mar 07, 2020 |
| ASUSTek       | Z97-A-USB31                 | [63b94ee87e](https://linux-hardware.org/?probe=63b94ee87e) | Mar 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [da2608360d](https://linux-hardware.org/?probe=da2608360d) | Feb 23, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [078b188645](https://linux-hardware.org/?probe=078b188645) | Feb 16, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [700eabb523](https://linux-hardware.org/?probe=700eabb523) | Feb 15, 2020 |
| HP            | 86D3                        | [83613548dc](https://linux-hardware.org/?probe=83613548dc) | Feb 13, 2020 |
| Alienware     | 06G6JW A00                  | [f3eab06bb2](https://linux-hardware.org/?probe=f3eab06bb2) | Feb 10, 2020 |
| MSI           | Z97-G43                     | [01c2993ade](https://linux-hardware.org/?probe=01c2993ade) | Jan 25, 2020 |
| HP            | ProLiant ML350 G6           | [3472820868](https://linux-hardware.org/?probe=3472820868) | Jan 17, 2020 |
| HP            | ProLiant ML350 G6           | [86fb31ed72](https://linux-hardware.org/?probe=86fb31ed72) | Jan 16, 2020 |
| ASUSTek       | M4A88T-M                    | [643a92956a](https://linux-hardware.org/?probe=643a92956a) | Jan 13, 2020 |
| Gigabyte      | EG41M-US2H                  | [697f2f05e2](https://linux-hardware.org/?probe=697f2f05e2) | Jan 12, 2020 |
| eMachines     | ET1850                      | [7c1a93e022](https://linux-hardware.org/?probe=7c1a93e022) | Dec 23, 2019 |
| Gigabyte      | Z77P-D3                     | [3de82df337](https://linux-hardware.org/?probe=3de82df337) | Dec 17, 2019 |
| Gigabyte      | H61N-USB3                   | [ee74c9e54c](https://linux-hardware.org/?probe=ee74c9e54c) | Dec 12, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | [44e3d900f5](https://linux-hardware.org/?probe=44e3d900f5) | Dec 02, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ed930b473b](https://linux-hardware.org/?probe=ed930b473b) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [e2bc0cfec5](https://linux-hardware.org/?probe=e2bc0cfec5) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [53e0ab44e0](https://linux-hardware.org/?probe=53e0ab44e0) | Nov 23, 2019 |
| Gigabyte      | Z77P-D3                     | [9a1e3d5db9](https://linux-hardware.org/?probe=9a1e3d5db9) | Nov 23, 2019 |
| Packard Be... | IMEDIA L4880                | [a9a53bf7f4](https://linux-hardware.org/?probe=a9a53bf7f4) | Nov 18, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [0029decba2](https://linux-hardware.org/?probe=0029decba2) | Nov 08, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6b013738c6](https://linux-hardware.org/?probe=6b013738c6) | Oct 24, 2019 |
| HP            | 3397                        | [27d2857bca](https://linux-hardware.org/?probe=27d2857bca) | Sep 30, 2019 |
| Gigabyte      | EG41M-US2H                  | [9717827455](https://linux-hardware.org/?probe=9717827455) | Sep 27, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [6298b19758](https://linux-hardware.org/?probe=6298b19758) | Sep 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [6d7e7fdc51](https://linux-hardware.org/?probe=6d7e7fdc51) | Sep 23, 2019 |
| ASUSTek       | Z10PA-D8 Series             | [7436c74dcb](https://linux-hardware.org/?probe=7436c74dcb) | Sep 11, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [340c34926f](https://linux-hardware.org/?probe=340c34926f) | Aug 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [d1e5249043](https://linux-hardware.org/?probe=d1e5249043) | Aug 19, 2019 |
| ASRock        | HM65-MXM                    | [0d687e29cb](https://linux-hardware.org/?probe=0d687e29cb) | Aug 12, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [fbdbd66417](https://linux-hardware.org/?probe=fbdbd66417) | Aug 11, 2019 |
| Dell          | 06X1TJ A01                  | [faf781dda9](https://linux-hardware.org/?probe=faf781dda9) | Aug 05, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [2ed5b5afc5](https://linux-hardware.org/?probe=2ed5b5afc5) | Jul 21, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [aa7226b798](https://linux-hardware.org/?probe=aa7226b798) | Jul 21, 2019 |
| Lenovo        | ThinkCentre M81 5032W3M     | [cb4983baf6](https://linux-hardware.org/?probe=cb4983baf6) | Jul 18, 2019 |
| ASRock        | FM2A78M-HD+                 | [4c45eb1803](https://linux-hardware.org/?probe=4c45eb1803) | Jul 10, 2019 |
| Intel         | DH77EB AAG39073-304         | [08b86f6f4c](https://linux-hardware.org/?probe=08b86f6f4c) | Jul 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [706e1e0baf](https://linux-hardware.org/?probe=706e1e0baf) | Jun 30, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [11a091fb81](https://linux-hardware.org/?probe=11a091fb81) | Jun 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [8fc47ce184](https://linux-hardware.org/?probe=8fc47ce184) | Jun 15, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [7ba347026e](https://linux-hardware.org/?probe=7ba347026e) | Jun 13, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3f7e0702b6](https://linux-hardware.org/?probe=3f7e0702b6) | Jun 12, 2019 |
| Dell          | 088DT1 A01                  | [5ea359299f](https://linux-hardware.org/?probe=5ea359299f) | Jun 11, 2019 |
| ASUSTek       | X99-A/USB                   | [d1e49be03d](https://linux-hardware.org/?probe=d1e49be03d) | Jun 11, 2019 |
| Gigabyte      | P85-D3                      | [16a7890585](https://linux-hardware.org/?probe=16a7890585) | Jun 09, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [9f8322e22a](https://linux-hardware.org/?probe=9f8322e22a) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [0c0c2eca20](https://linux-hardware.org/?probe=0c0c2eca20) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3608798d1a](https://linux-hardware.org/?probe=3608798d1a) | May 24, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e50d4d260b](https://linux-hardware.org/?probe=e50d4d260b) | May 23, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [1cbc7d5be7](https://linux-hardware.org/?probe=1cbc7d5be7) | May 16, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [cb3502a316](https://linux-hardware.org/?probe=cb3502a316) | May 09, 2019 |
| MSI           | B350 TOMAHAWK               | [3db9496e05](https://linux-hardware.org/?probe=3db9496e05) | May 08, 2019 |
| MSI           | B450 TOMAHAWK               | [0f966d6a2d](https://linux-hardware.org/?probe=0f966d6a2d) | May 08, 2019 |
| ASUSTek       | CROSSHAIR VI HERO           | [7653740066](https://linux-hardware.org/?probe=7653740066) | May 04, 2019 |
| HP            | 0A58h                       | [ec6b93d879](https://linux-hardware.org/?probe=ec6b93d879) | May 02, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [ca0ce2b4fc](https://linux-hardware.org/?probe=ca0ce2b4fc) | Apr 26, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e08bb193b2](https://linux-hardware.org/?probe=e08bb193b2) | Apr 24, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [79831da7d2](https://linux-hardware.org/?probe=79831da7d2) | Apr 15, 2019 |
| Dell          | 04JGCK A02                  | [fd0e8a37d1](https://linux-hardware.org/?probe=fd0e8a37d1) | Apr 09, 2019 |
| ASRock        | 4Core1600Twins-P35          | [a5f4c15c85](https://linux-hardware.org/?probe=a5f4c15c85) | Apr 07, 2019 |
| ASUSTek       | P7P55D                      | [b25ec7e75a](https://linux-hardware.org/?probe=b25ec7e75a) | Mar 18, 2019 |
| Shuttle       | FN68S V10                   | [10121de278](https://linux-hardware.org/?probe=10121de278) | Mar 04, 2019 |
| Shuttle       | FN68S V10                   | [d15d7c5f21](https://linux-hardware.org/?probe=d15d7c5f21) | Mar 04, 2019 |
| ASRock        | 4Core1600Twins-P35          | [98b19f2fc7](https://linux-hardware.org/?probe=98b19f2fc7) | Feb 25, 2019 |
| ASRock        | Z77 Pro4                    | [08a0af469d](https://linux-hardware.org/?probe=08a0af469d) | Feb 20, 2019 |
| ASRock        | 4Core1600Twins-P35          | [e94ef5e02e](https://linux-hardware.org/?probe=e94ef5e02e) | Feb 16, 2019 |
| ASRock        | Z77 Pro4                    | [ba845b8712](https://linux-hardware.org/?probe=ba845b8712) | Feb 15, 2019 |
| ASRock        | Z77 Pro4                    | [e104fbc941](https://linux-hardware.org/?probe=e104fbc941) | Feb 14, 2019 |
| Acer          | FMCP7A-ION                  | [22a3849e3a](https://linux-hardware.org/?probe=22a3849e3a) | Dec 05, 2018 |
| Medion        | MS-7646                     | [cb720a4df0](https://linux-hardware.org/?probe=cb720a4df0) | Nov 25, 2018 |
| Medion        | MS-7713                     | [94a415c6c3](https://linux-hardware.org/?probe=94a415c6c3) | Nov 23, 2018 |
| Medion        | MS-7646                     | [7ff447b20e](https://linux-hardware.org/?probe=7ff447b20e) | Nov 22, 2018 |
| Lenovo        | 5025a26                     | [75a078fe71](https://linux-hardware.org/?probe=75a078fe71) | Nov 15, 2018 |
| ASUSTek       | PRIME Z370-P                | [89bfd874c0](https://linux-hardware.org/?probe=89bfd874c0) | Nov 03, 2018 |
| MSI           | B75MA-E31                   | [b1600ef31c](https://linux-hardware.org/?probe=b1600ef31c) | Nov 02, 2018 |
| ASUSTek       | H81M-P PLUS                 | [67c13bd391](https://linux-hardware.org/?probe=67c13bd391) | Oct 25, 2018 |
| Pegatron      | 2AB5                        | [85d0b75160](https://linux-hardware.org/?probe=85d0b75160) | Oct 24, 2018 |
| Pegatron      | 2AB5                        | [25cf879f80](https://linux-hardware.org/?probe=25cf879f80) | Oct 24, 2018 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f67b4afee6](https://linux-hardware.org/?probe=f67b4afee6) | Aug 11, 2018 |
| HP            | 82FE 11                     | [bd284d1c9d](https://linux-hardware.org/?probe=bd284d1c9d) | Dec 11, 2017 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [0f0a556912](https://linux-hardware.org/?probe=0f0a556912) | Jul 03, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 43       | 8.58%   |
| Ubuntu 18.04                 | 30       | 5.99%   |
| Arch Rolling                 | 27       | 5.39%   |
| Ubuntu 22.04                 | 19       | 3.79%   |
| Debian 12                    | 17       | 3.39%   |
| Zorin 16                     | 16       | 3.19%   |
| Pop!_OS 22.04                | 15       | 2.99%   |
| OpenMandriva 4.2             | 13       | 2.59%   |
| Manjaro                      | 11       | 2.2%    |
| Fedora 40                    | 10       | 2%      |
| Ubuntu 24.04                 | 9        | 1.8%    |
| Debian 11                    | 9        | 1.8%    |
| ArcoLinux Rolling            | 9        | 1.8%    |
| Pop!_OS 21.04                | 7        | 1.4%    |
| OpenMandriva 4.3             | 7        | 1.4%    |
| Linux Mint 21.1              | 7        | 1.4%    |
| Linux Mint 20.2              | 7        | 1.4%    |
| Ubuntu 22.10                 | 6        | 1.2%    |
| OpenMandriva 23.03           | 6        | 1.2%    |
| Linux Mint 21.2              | 6        | 1.2%    |
| Linux Mint 20.1              | 6        | 1.2%    |
| Fedora 38                    | 6        | 1.2%    |
| Zorin 17                     | 5        | 1%      |
| Ubuntu 20.10                 | 5        | 1%      |
| Ubuntu 19.04                 | 5        | 1%      |
| Pop!_OS 20.10                | 5        | 1%      |
| openSUSE Tumbleweed-XXXXXXXX | 5        | 1%      |
| Linux Mint 20.3              | 5        | 1%      |
| Zorin 15                     | 4        | 0.8%    |
| Ubuntu 21.10                 | 4        | 0.8%    |
| OpenMandriva 23.08           | 4        | 0.8%    |
| KDE neon 22.04               | 4        | 0.8%    |
| KDE neon 20.04               | 4        | 0.8%    |
| Garuda Linux Soaring         | 4        | 0.8%    |
| Ubuntu 19.10                 | 3        | 0.6%    |
| Pop!_OS 21.10                | 3        | 0.6%    |
| Linux Mint 20                | 3        | 0.6%    |
| Linux Mint 19.1              | 3        | 0.6%    |
| Fedora 36                    | 3        | 0.6%    |
| Fedora 32                    | 3        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 127      | 26.79%  |
| Linux Mint   | 42       | 8.86%   |
| Fedora       | 36       | 7.59%   |
| OpenMandriva | 35       | 7.38%   |
| Debian       | 34       | 7.17%   |
| Pop!_OS      | 33       | 6.96%   |
| Arch         | 29       | 6.12%   |
| Zorin        | 24       | 5.06%   |
| Manjaro      | 24       | 5.06%   |
| Kubuntu      | 12       | 2.53%   |
| ArcoLinux    | 11       | 2.32%   |
| KDE neon     | 10       | 2.11%   |
| Ubuntu MATE  | 6        | 1.27%   |
| openSUSE     | 5        | 1.05%   |
| Nobara       | 5        | 1.05%   |
| NixOS        | 5        | 1.05%   |
| Gentoo       | 5        | 1.05%   |
| Garuda Linux | 4        | 0.84%   |
| EndeavourOS  | 4        | 0.84%   |
| ROSA         | 3        | 0.63%   |
| MX           | 3        | 0.63%   |
| Xubuntu      | 2        | 0.42%   |
| Lubuntu      | 2        | 0.42%   |
| Elementary   | 2        | 0.42%   |
| Ubuntu Unity | 1        | 0.21%   |
| Ubuntu Kylin | 1        | 0.21%   |
| SteamOS      | 1        | 0.21%   |
| Solus        | 1        | 0.21%   |
| Parrot       | 1        | 0.21%   |
| LMDE         | 1        | 0.21%   |
| Endless      | 1        | 0.21%   |
| Devuan       | 1        | 0.21%   |
| CachyOS      | 1        | 0.21%   |
| BlackPanther | 1        | 0.21%   |
| Anarchy      | 1        | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 11       | 2.02%   |
| 6.8.0-45-generic         | 6        | 1.1%    |
| 6.2.6-desktop-1omv2390   | 6        | 1.1%    |
| 5.4.0-52-generic         | 6        | 1.1%    |
| 5.16.7-desktop-1omv4003  | 6        | 1.1%    |
| 6.8.0-31-generic         | 5        | 0.92%   |
| 5.15.0-58-generic        | 5        | 0.92%   |
| 5.15.0-56-generic        | 5        | 0.92%   |
| 5.8.0-43-generic         | 4        | 0.74%   |
| 5.4.0-42-generic         | 4        | 0.74%   |
| 5.19.0-38-generic        | 4        | 0.74%   |
| 5.11.12-desktop-1omv4002 | 4        | 0.74%   |
| 4.15.0-48-generic        | 4        | 0.74%   |
| 4.15.0-45-generic        | 4        | 0.74%   |
| 6.9.3-76060903-generic   | 3        | 0.55%   |
| 6.8.0-51-generic         | 3        | 0.55%   |
| 6.8.0-40-generic         | 3        | 0.55%   |
| 6.6.2-desktop-1omv2390   | 3        | 0.55%   |
| 6.5.0-21-generic         | 3        | 0.55%   |
| 6.4.11-desktop-1omv2390  | 3        | 0.55%   |
| 6.2.6-76060206-generic   | 3        | 0.55%   |
| 6.1.0-21-amd64           | 3        | 0.55%   |
| 6.1.0-18-amd64           | 3        | 0.55%   |
| 5.8.5-arch1-1            | 3        | 0.55%   |
| 5.4.0-91-generic         | 3        | 0.55%   |
| 5.4.0-90-generic         | 3        | 0.55%   |
| 5.4.0-73-generic         | 3        | 0.55%   |
| 5.4.0-58-generic         | 3        | 0.55%   |
| 5.4.0-29-generic         | 3        | 0.55%   |
| 5.3.0-28-generic         | 3        | 0.55%   |
| 5.15.0-88-generic        | 3        | 0.55%   |
| 5.15.0-69-generic        | 3        | 0.55%   |
| 5.15.0-46-generic        | 3        | 0.55%   |
| 5.15.0-41-generic        | 3        | 0.55%   |
| 5.13.0-28-generic        | 3        | 0.55%   |
| 5.11.0-7620-generic      | 3        | 0.55%   |
| 5.11.0-41-generic        | 3        | 0.55%   |
| 5.11.0-37-generic        | 3        | 0.55%   |
| 5.11.0-27-generic        | 3        | 0.55%   |
| 5.10.0-20-amd64          | 3        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 53       | 10.23%  |
| 5.15.0  | 34       | 6.56%   |
| 4.15.0  | 29       | 5.6%    |
| 6.8.0   | 21       | 4.05%   |
| 5.8.0   | 21       | 4.05%   |
| 5.13.0  | 19       | 3.67%   |
| 5.11.0  | 19       | 3.67%   |
| 5.19.0  | 17       | 3.28%   |
| 6.1.0   | 16       | 3.09%   |
| 6.5.0   | 12       | 2.32%   |
| 6.2.6   | 11       | 2.12%   |
| 5.3.0   | 11       | 2.12%   |
| 5.10.14 | 11       | 2.12%   |
| 5.10.0  | 10       | 1.93%   |
| 5.0.0   | 8        | 1.54%   |
| 6.2.0   | 7        | 1.35%   |
| 5.16.7  | 6        | 1.16%   |
| 6.9.3   | 5        | 0.97%   |
| 4.18.0  | 5        | 0.97%   |
| 6.11.5  | 4        | 0.77%   |
| 6.10.0  | 4        | 0.77%   |
| 5.11.12 | 4        | 0.77%   |
| 4.19.0  | 4        | 0.77%   |
| 6.6.2   | 3        | 0.58%   |
| 6.6.0   | 3        | 0.58%   |
| 6.5.5   | 3        | 0.58%   |
| 6.4.8   | 3        | 0.58%   |
| 6.4.11  | 3        | 0.58%   |
| 5.8.5   | 3        | 0.58%   |
| 5.8.18  | 3        | 0.58%   |
| 5.6.15  | 3        | 0.58%   |
| 6.9.7   | 2        | 0.39%   |
| 6.9.5   | 2        | 0.39%   |
| 6.9.0   | 2        | 0.39%   |
| 6.8.7   | 2        | 0.39%   |
| 6.7.0   | 2        | 0.39%   |
| 6.6.8   | 2        | 0.39%   |
| 6.6.41  | 2        | 0.39%   |
| 6.6.21  | 2        | 0.39%   |
| 6.5.3   | 2        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 57       | 11.24%  |
| 5.15    | 42       | 8.28%   |
| 5.8     | 31       | 6.11%   |
| 4.15    | 29       | 5.72%   |
| 6.1     | 28       | 5.52%   |
| 6.8     | 27       | 5.33%   |
| 5.11    | 27       | 5.33%   |
| 5.10    | 23       | 4.54%   |
| 5.13    | 22       | 4.34%   |
| 6.2     | 21       | 4.14%   |
| 6.5     | 20       | 3.94%   |
| 5.19    | 20       | 3.94%   |
| 6.6     | 18       | 3.55%   |
| 6.9     | 14       | 2.76%   |
| 5.16    | 13       | 2.56%   |
| 5.3     | 11       | 2.17%   |
| 6.4     | 10       | 1.97%   |
| 6.3     | 10       | 1.97%   |
| 6.10    | 9        | 1.78%   |
| 6.11    | 8        | 1.58%   |
| 5.0     | 8        | 1.58%   |
| 5.6     | 7        | 1.38%   |
| 6.0     | 6        | 1.18%   |
| 6.7     | 5        | 0.99%   |
| 5.7     | 5        | 0.99%   |
| 5.17    | 5        | 0.99%   |
| 4.19    | 5        | 0.99%   |
| 4.18    | 5        | 0.99%   |
| 6.12    | 4        | 0.79%   |
| 5.9     | 3        | 0.59%   |
| 5.14    | 3        | 0.59%   |
| 4.9     | 3        | 0.59%   |
| 5.18    | 2        | 0.39%   |
| 5.12    | 2        | 0.39%   |
| 5.1     | 2        | 0.39%   |
| 5.2     | 1        | 0.2%    |
| 4.17    | 1        | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 448      | 99.12%  |
| i686   | 4        | 0.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 189      | 39.62%  |
| KDE5          | 90       | 18.87%  |
| Unknown       | 69       | 14.47%  |
| X-Cinnamon    | 34       | 7.13%   |
| XFCE          | 30       | 6.29%   |
| KDE6          | 16       | 3.35%   |
| MATE          | 10       | 2.1%    |
| KDE           | 9        | 1.89%   |
| Cinnamon      | 5        | 1.05%   |
| LXQt          | 4        | 0.84%   |
| i3            | 4        | 0.84%   |
| Pantheon      | 2        | 0.42%   |
| KDE4          | 2        | 0.42%   |
| Hyprland      | 2        | 0.42%   |
| Deepin        | 2        | 0.42%   |
| Unity         | 1        | 0.21%   |
| UKUI          | 1        | 0.21%   |
| openbox       | 1        | 0.21%   |
| none+xsession | 1        | 0.21%   |
| LXDE          | 1        | 0.21%   |
| gtk           | 1        | 0.21%   |
| enlightenment | 1        | 0.21%   |
| COSMIC        | 1        | 0.21%   |
| bspwm         | 1        | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 334      | 70.17%  |
| Wayland | 92       | 19.33%  |
| Unknown | 32       | 6.72%   |
| Tty     | 18       | 3.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 249      | 52.75%  |
| SDDM    | 87       | 18.43%  |
| GDM3    | 51       | 10.81%  |
| LightDM | 36       | 7.63%   |
| GDM     | 29       | 6.14%   |
| TDM     | 15       | 3.18%   |
| KDM     | 2        | 0.42%   |
| SLiM    | 1        | 0.21%   |
| LXDM    | 1        | 0.21%   |
| GREETD  | 1        | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 162      | 34.62%  |
| da_DK      | 145      | 30.98%  |
| en_DK      | 71       | 15.17%  |
| Unknown    | 45       | 9.62%   |
| en_GB      | 21       | 4.49%   |
| C          | 7        | 1.5%    |
| de_DE      | 3        | 0.64%   |
| ru_RU      | 2        | 0.43%   |
| pl_PL      | 2        | 0.43%   |
| it_IT      | 2        | 0.43%   |
| UTF-8      | 1        | 0.21%   |
| io_001     | 1        | 0.21%   |
| es_ES      | 1        | 0.21%   |
| en_US.UTF8 | 1        | 0.21%   |
| en_IE      | 1        | 0.21%   |
| en_CA      | 1        | 0.21%   |
| de_CH      | 1        | 0.21%   |
| de_AT      | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 259      | 55.82%  |
| EFI  | 205      | 44.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 333      | 70.11%  |
| Btrfs   | 67       | 14.11%  |
| Overlay | 32       | 6.74%   |
| Tmpfs   | 20       | 4.21%   |
| Unknown | 13       | 2.74%   |
| Zfs     | 5        | 1.05%   |
| Xfs     | 3        | 0.63%   |
| F2fs    | 2        | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 242      | 51.38%  |
| GPT     | 187      | 39.7%   |
| MBR     | 42       | 8.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 362      | 77.19%  |
| Yes       | 107      | 22.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 340      | 73.28%  |
| Yes       | 124      | 26.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 163      | 36.06%  |
| Gigabyte Technology                  | 60       | 13.27%  |
| ASRock                               | 46       | 10.18%  |
| MSI                                  | 43       | 9.51%   |
| Lenovo                               | 35       | 7.74%   |
| Hewlett-Packard                      | 30       | 6.64%   |
| Dell                                 | 17       | 3.76%   |
| Medion                               | 11       | 2.43%   |
| Acer                                 | 11       | 2.43%   |
| Pegatron                             | 5        | 1.11%   |
| Intel                                | 5        | 1.11%   |
| Shuttle                              | 3        | 0.66%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.66%   |
| Fujitsu                              | 3        | 0.66%   |
| Packard Bell                         | 2        | 0.44%   |
| BESSTAR Tech                         | 2        | 0.44%   |
| T-bao                                | 1        | 0.22%   |
| Sugon                                | 1        | 0.22%   |
| NEXCOM                               | 1        | 0.22%   |
| Inventec                             | 1        | 0.22%   |
| IceWhale Technology                  | 1        | 0.22%   |
| Fujitsu Siemens                      | 1        | 0.22%   |
| eMachines                            | 1        | 0.22%   |
| ECS                                  | 1        | 0.22%   |
| AMI                                  | 1        | 0.22%   |
| Alienware                            | 1        | 0.22%   |
| ADLINK Technology                    | 1        | 0.22%   |
| ABIT                                 | 1        | 0.22%   |
| Unknown                              | 1        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 7        | 1.55%   |
| ASUS TUF Gaming X570-PLUS           | 5        | 1.11%   |
| ASUS ROG STRIX X570-E GAMING        | 5        | 1.11%   |
| ASUS ROG STRIX B450-E GAMING        | 5        | 1.11%   |
| MSI MS-7C37                         | 4        | 0.88%   |
| Dell OptiPlex 9020                  | 4        | 0.88%   |
| ASUS Z170 PRO GAMING                | 4        | 0.88%   |
| ASUS ROG STRIX B550-F GAMING        | 4        | 0.88%   |
| ASUS PRIME X570-P                   | 4        | 0.88%   |
| MSI MS-7C02                         | 3        | 0.66%   |
| Gigabyte X570 AORUS MASTER          | 3        | 0.66%   |
| ASUS TUF Gaming B550-PLUS           | 3        | 0.66%   |
| ASUS PRIME Z390-A                   | 3        | 0.66%   |
| ASUS PRIME Z370-P                   | 3        | 0.66%   |
| MSI MS-7C84                         | 2        | 0.44%   |
| MSI MS-7C56                         | 2        | 0.44%   |
| MSI MS-7B79                         | 2        | 0.44%   |
| MSI MS-7A34                         | 2        | 0.44%   |
| MSI MS-7693                         | 2        | 0.44%   |
| Medion MS-7797                      | 2        | 0.44%   |
| Medion MS-7646                      | 2        | 0.44%   |
| Lenovo ThinkStation P500 30A6S14F00 | 2        | 0.44%   |
| Lenovo H30-05 90BJ00CNMT            | 2        | 0.44%   |
| HP Z230 Tower Workstation           | 2        | 0.44%   |
| HP Compaq 8200 Elite SFF PC         | 2        | 0.44%   |
| HP Compaq 6200 Pro SFF PC           | 2        | 0.44%   |
| Gigabyte Z68X-UD7-B3                | 2        | 0.44%   |
| Gigabyte P85-D3                     | 2        | 0.44%   |
| Gigabyte B650 GAMING X AX           | 2        | 0.44%   |
| Dell OptiPlex 7050                  | 2        | 0.44%   |
| BESSTAR Tech HM90                   | 2        | 0.44%   |
| ASUS Z170-P                         | 2        | 0.44%   |
| ASUS ROG STRIX X670E-E GAMING WIFI  | 2        | 0.44%   |
| ASUS ROG STRIX X470-I GAMING        | 2        | 0.44%   |
| ASUS ROG STRIX B450-F GAMING        | 2        | 0.44%   |
| ASUS ROG Maximus X HERO             | 2        | 0.44%   |
| ASUS PRIME-B650M-A-II-10DE          | 2        | 0.44%   |
| ASUS PRIME Z690M-PLUS D4            | 2        | 0.44%   |
| ASUS PRIME Z370-A                   | 2        | 0.44%   |
| ASUS PRIME X470-PRO                 | 2        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 40       | 8.85%   |
| ASUS ROG             | 37       | 8.19%   |
| ASUS TUF             | 21       | 4.65%   |
| Lenovo ThinkCentre   | 14       | 3.1%    |
| HP Compaq            | 10       | 2.21%   |
| Dell OptiPlex        | 9        | 1.99%   |
| Gigabyte X570        | 8        | 1.77%   |
| Lenovo ThinkStation  | 7        | 1.55%   |
| ASUS All             | 7        | 1.55%   |
| Acer Aspire          | 7        | 1.55%   |
| Lenovo IdeaCentre    | 6        | 1.33%   |
| ASUS M5A78L-M        | 5        | 1.11%   |
| MSI MS-7C37          | 4        | 0.88%   |
| HP ProLiant          | 4        | 0.88%   |
| HP EliteDesk         | 4        | 0.88%   |
| Gigabyte B550        | 4        | 0.88%   |
| ASUS Z170            | 4        | 0.88%   |
| ASUS SABERTOOTH      | 4        | 0.88%   |
| ASRock Z170          | 4        | 0.88%   |
| ASRock B450          | 4        | 0.88%   |
| MSI MS-7C02          | 3        | 0.66%   |
| HP Pavilion          | 3        | 0.66%   |
| Gigabyte Z390        | 3        | 0.66%   |
| Gigabyte B650        | 3        | 0.66%   |
| Fujitsu ESPRIMO      | 3        | 0.66%   |
| Dell Precision       | 3        | 0.66%   |
| ASUS PRO             | 3        | 0.66%   |
| ASUS Maximus         | 3        | 0.66%   |
| ASRock Z77           | 3        | 0.66%   |
| MSI MS-7C84          | 2        | 0.44%   |
| MSI MS-7C56          | 2        | 0.44%   |
| MSI MS-7B79          | 2        | 0.44%   |
| MSI MS-7A34          | 2        | 0.44%   |
| MSI MS-7693          | 2        | 0.44%   |
| Medion MS-7797       | 2        | 0.44%   |
| Medion MS-7646       | 2        | 0.44%   |
| Lenovo H30-05        | 2        | 0.44%   |
| HP Z230              | 2        | 0.44%   |
| HP OMEN              | 2        | 0.44%   |
| Gigabyte Z68X-UD7-B3 | 2        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 52       | 11.5%   |
| 2020 | 47       | 10.4%   |
| 2019 | 47       | 10.4%   |
| 2021 | 34       | 7.52%   |
| 2012 | 33       | 7.3%    |
| 2017 | 30       | 6.64%   |
| 2016 | 26       | 5.75%   |
| 2011 | 25       | 5.53%   |
| 2015 | 24       | 5.31%   |
| 2013 | 24       | 5.31%   |
| 2022 | 22       | 4.87%   |
| 2014 | 20       | 4.42%   |
| 2010 | 19       | 4.2%    |
| 2008 | 14       | 3.1%    |
| 2009 | 12       | 2.65%   |
| 2023 | 10       | 2.21%   |
| 2007 | 8        | 1.77%   |
| 2024 | 3        | 0.66%   |
| 2006 | 2        | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 452      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 443      | 97.79%  |
| Enabled  | 10       | 2.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 452      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 140      | 30.11%  |
| 32.01-64.0      | 110      | 23.66%  |
| 8.01-16.0       | 67       | 14.41%  |
| 64.01-256.0     | 41       | 8.82%   |
| 4.01-8.0        | 39       | 8.39%   |
| 3.01-4.0        | 37       | 7.96%   |
| 24.01-32.0      | 21       | 4.52%   |
| 1.01-2.0        | 5        | 1.08%   |
| More than 256.0 | 2        | 0.43%   |
| 2.01-3.0        | 2        | 0.43%   |
| 0.51-1.0        | 1        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 147      | 28.71%  |
| 2.01-3.0    | 122      | 23.83%  |
| 4.01-8.0    | 100      | 19.53%  |
| 3.01-4.0    | 76       | 14.84%  |
| 8.01-16.0   | 32       | 6.25%   |
| 0.51-1.0    | 16       | 3.13%   |
| 24.01-32.0  | 6        | 1.17%   |
| 16.01-24.0  | 5        | 0.98%   |
| 0.01-0.5    | 5        | 0.98%   |
| 32.01-64.0  | 2        | 0.39%   |
| 64.01-256.0 | 1        | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 160      | 33.97%  |
| 2      | 121      | 25.69%  |
| 3      | 88       | 18.68%  |
| 4      | 49       | 10.4%   |
| 5      | 27       | 5.73%   |
| 6      | 10       | 2.12%   |
| 7      | 6        | 1.27%   |
| 0      | 4        | 0.85%   |
| 8      | 3        | 0.64%   |
| 9      | 2        | 0.42%   |
| 10     | 1        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 290      | 63.88%  |
| Yes       | 164      | 36.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 449      | 99.34%  |
| No        | 3        | 0.66%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 238      | 51.74%  |
| Yes       | 222      | 48.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 278      | 60.83%  |
| Yes       | 179      | 39.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Denmark | 452      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Copenhagen               | 110      | 23.21%  |
| Odense                   | 24       | 5.06%   |
| Frederiksberg            | 22       | 4.64%   |
| Aarhus                   | 17       | 3.59%   |
| Slagelse                 | 11       | 2.32%   |
| Horsens                  | 10       | 2.11%   |
| Aalborg                  | 10       | 2.11%   |
| Silkeborg                | 9        | 1.9%    |
| Esbjerg                  | 8        | 1.69%   |
| Valby                    | 7        | 1.48%   |
| Bronshoj                 | 7        | 1.48%   |
| Aabenraa                 | 6        | 1.27%   |
| Taastrup                 | 5        | 1.05%   |
| Ishøj                   | 5        | 1.05%   |
| Hjørring                | 5        | 1.05%   |
| Glostrup Municipality    | 5        | 1.05%   |
| Viby J                   | 4        | 0.84%   |
| Vejle                    | 4        | 0.84%   |
| Tilst                    | 4        | 0.84%   |
| Rødovre Municipality    | 4        | 0.84%   |
| Roskilde                 | 4        | 0.84%   |
| Ringsted                 | 4        | 0.84%   |
| Kolding                  | 4        | 0.84%   |
| Herlev                   | 4        | 0.84%   |
| Allinge                  | 4        | 0.84%   |
| Albertslund Municipality | 4        | 0.84%   |
| Trige                    | 3        | 0.63%   |
| Svendborg                | 3        | 0.63%   |
| Pandrup                  | 3        | 0.63%   |
| Odder                    | 3        | 0.63%   |
| Nyborg                   | 3        | 0.63%   |
| Norresundby              | 3        | 0.63%   |
| Naestved                 | 3        | 0.63%   |
| Ikast                    | 3        | 0.63%   |
| Hvidovre                 | 3        | 0.63%   |
| Holstebro                | 3        | 0.63%   |
| Haderslev                | 3        | 0.63%   |
| Gistrup                  | 3        | 0.63%   |
| Gentofte Municipality    | 3        | 0.63%   |
| Fredericia               | 3        | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 194      | 371    | 22.17%  |
| Seagate                     | 130      | 202    | 14.86%  |
| WDC                         | 127      | 199    | 14.51%  |
| Kingston                    | 88       | 134    | 10.06%  |
| Crucial                     | 39       | 52     | 4.46%   |
| SanDisk                     | 37       | 50     | 4.23%   |
| Toshiba                     | 31       | 42     | 3.54%   |
| Intel                       | 25       | 29     | 2.86%   |
| Kingston Technology Company | 18       | 19     | 2.06%   |
| Hitachi                     | 17       | 26     | 1.94%   |
| Phison Electronics          | 14       | 22     | 1.6%    |
| Intenso                     | 12       | 15     | 1.37%   |
| Corsair                     | 11       | 14     | 1.26%   |
| Unknown                     | 10       | 15     | 1.14%   |
| A-DATA Technology           | 9        | 10     | 1.03%   |
| Phison                      | 7        | 10     | 0.8%    |
| HGST                        | 7        | 10     | 0.8%    |
| PNY                         | 6        | 8      | 0.69%   |
| Micron Technology           | 6        | 7      | 0.69%   |
| SK hynix                    | 5        | 5      | 0.57%   |
| OCZ                         | 5        | 5      | 0.57%   |
| Micron/Crucial Technology   | 5        | 5      | 0.57%   |
| LITEON                      | 4        | 6      | 0.46%   |
| Verbatim                    | 3        | 6      | 0.34%   |
| Realtek Semiconductor       | 3        | 4      | 0.34%   |
| Patriot                     | 3        | 4      | 0.34%   |
| JMicron Technology          | 3        | 3      | 0.34%   |
| Fujitsu                     | 3        | 7      | 0.34%   |
| Apple                       | 3        | 6      | 0.34%   |
| Unknown                     | 3        | 5      | 0.34%   |
| XPG                         | 2        | 2      | 0.23%   |
| Transcend                   | 2        | 2      | 0.23%   |
| Team                        | 2        | 2      | 0.23%   |
| Silicon Motion              | 2        | 2      | 0.23%   |
| Seagate Technology          | 2        | 3      | 0.23%   |
| Maxtor                      | 2        | 2      | 0.23%   |
| Leven                       | 2        | 2      | 0.23%   |
| KIOXIA                      | 2        | 2      | 0.23%   |
| HUAWEI                      | 2        | 2      | 0.23%   |
| Hewlett-Packard             | 2        | 11     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 19       | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 16       | 1.53%   |
| Samsung SSD 850 EVO 250GB                             | 15       | 1.44%   |
| Samsung SSD 850 EVO 500GB                             | 13       | 1.24%   |
| Samsung SSD 860 QVO 1TB                               | 12       | 1.15%   |
| Kingston SA400S37480G 480GB SSD                       | 12       | 1.15%   |
| Seagate ST2000DM001-1ER164 2TB                        | 10       | 0.96%   |
| Samsung SSD 860 EVO 1TB                               | 10       | 0.96%   |
| Kingston SV300S37A120G 120GB SSD                      | 10       | 0.96%   |
| Samsung SSD 860 EVO 500GB                             | 9        | 0.86%   |
| Samsung SSD 840 EVO 250GB                             | 9        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                       | 9        | 0.86%   |
| Samsung NVMe SSD Drive 500GB                          | 8        | 0.77%   |
| Seagate ST500DM002-1BD142 500GB                       | 7        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                        | 7        | 0.67%   |
| Samsung NVMe SSD Drive 1TB                            | 7        | 0.67%   |
| Phison E12 NVMe Controller 480GB                      | 7        | 0.67%   |
| Kingston Company SNV2S2000G 2TB                       | 7        | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                           | 7        | 0.67%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 6        | 0.57%   |
| Kingston SUV400S37120G 120GB SSD                      | 6        | 0.57%   |
| Kingston SKC3000D2048G 2TB                            | 6        | 0.57%   |
| Kingston SA400S37960G 960GB SSD                       | 6        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                       | 6        | 0.57%   |
| Seagate ST4000VN008-2DR166 4TB                        | 5        | 0.48%   |
| Seagate ST1000DM003-1SB10C 1TB                        | 5        | 0.48%   |
| Seagate ST1000DM003-1SB102 1TB                        | 5        | 0.48%   |
| Samsung SSD 970 EVO 1TB                               | 5        | 0.48%   |
| Samsung SSD 870 EVO 1TB                               | 5        | 0.48%   |
| Samsung SSD 840 EVO 500GB                             | 5        | 0.48%   |
| Unknown SD/MMC/MS PRO 128GB                           | 4        | 0.38%   |
| Unknown Compact Flash 977MB                           | 4        | 0.38%   |
| Toshiba DT01ACA050 500GB                              | 4        | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB                        | 4        | 0.38%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 512GB | 4        | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                            | 4        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB                        | 4        | 0.38%   |
| Samsung SSD 870 QVO 2TB                               | 4        | 0.38%   |
| Samsung SSD 850 EVO 120GB                             | 4        | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 4        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 126      | 195    | 39.62%  |
| WDC                 | 102      | 170    | 32.08%  |
| Toshiba             | 28       | 39     | 8.81%   |
| Hitachi             | 17       | 26     | 5.35%   |
| Samsung Electronics | 14       | 22     | 4.4%    |
| HGST                | 7        | 10     | 2.2%    |
| Unknown             | 4        | 5      | 1.26%   |
| JMicron Technology  | 3        | 3      | 0.94%   |
| Fujitsu             | 3        | 7      | 0.94%   |
| Apple               | 3        | 6      | 0.94%   |
| Maxtor              | 2        | 2      | 0.63%   |
| Hewlett-Packard     | 2        | 11     | 0.63%   |
| Unknown             | 2        | 4      | 0.63%   |
| USB                 | 1        | 1      | 0.31%   |
| Unknown (CF)        | 1        | 1      | 0.31%   |
| Intenso             | 1        | 2      | 0.31%   |
| ASMT109x            | 1        | 1      | 0.31%   |
| ASMT                | 1        | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 122      | 211    | 35.99%  |
| Kingston            | 66       | 93     | 19.47%  |
| Crucial             | 34       | 47     | 10.03%  |
| WDC                 | 15       | 16     | 4.42%   |
| SanDisk             | 14       | 14     | 4.13%   |
| Intel               | 12       | 14     | 3.54%   |
| Intenso             | 9        | 9      | 2.65%   |
| A-DATA Technology   | 8        | 9      | 2.36%   |
| PNY                 | 6        | 8      | 1.77%   |
| Micron Technology   | 6        | 7      | 1.77%   |
| OCZ                 | 5        | 5      | 1.47%   |
| Corsair             | 5        | 6      | 1.47%   |
| LITEON              | 4        | 6      | 1.18%   |
| Verbatim            | 3        | 6      | 0.88%   |
| Patriot             | 3        | 4      | 0.88%   |
| Transcend           | 2        | 2      | 0.59%   |
| Team                | 2        | 2      | 0.59%   |
| SK hynix            | 2        | 2      | 0.59%   |
| Leven               | 2        | 2      | 0.59%   |
| China               | 2        | 2      | 0.59%   |
| AFOX                | 2        | 2      | 0.59%   |
| Vaseky              | 1        | 1      | 0.29%   |
| Toshiba             | 1        | 1      | 0.29%   |
| Supersonic          | 1        | 1      | 0.29%   |
| Shark               | 1        | 1      | 0.29%   |
| Ramaxel Technology  | 1        | 1      | 0.29%   |
| OCZ-VERTEX3         | 1        | 3      | 0.29%   |
| Netac               | 1        | 1      | 0.29%   |
| LITEONIT            | 1        | 1      | 0.29%   |
| KingDian            | 1        | 1      | 0.29%   |
| INDMEM              | 1        | 1      | 0.29%   |
| GOODRAM             | 1        | 5      | 0.29%   |
| FORESEE             | 1        | 1      | 0.29%   |
| ADATA SU            | 1        | 1      | 0.29%   |
| 2-Power             | 1        | 2      | 0.29%   |
| Unknown             | 1        | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 269      | 489    | 37.26%  |
| HDD     | 240      | 506    | 33.24%  |
| NVMe    | 195      | 340    | 27.01%  |
| Unknown | 14       | 15     | 1.94%   |
| MMC     | 4        | 4      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 372      | 948    | 60.69%  |
| NVMe | 195      | 335    | 31.81%  |
| SAS  | 42       | 67     | 6.85%   |
| MMC  | 4        | 4      | 0.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 272      | 495    | 47.06%  |
| 0.51-1.0   | 152      | 238    | 26.3%   |
| 1.01-2.0   | 71       | 123    | 12.28%  |
| 3.01-4.0   | 30       | 44     | 5.19%   |
| 2.01-3.0   | 24       | 37     | 4.15%   |
| 4.01-10.0  | 20       | 43     | 3.46%   |
| 10.01-20.0 | 9        | 15     | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 85       | 17.49%  |
| 101-250        | 84       | 17.28%  |
| 251-500        | 78       | 16.05%  |
| 1001-2000      | 67       | 13.79%  |
| More than 3000 | 64       | 13.17%  |
| 2001-3000      | 34       | 7%      |
| 1-20           | 30       | 6.17%   |
| Unknown        | 18       | 3.7%    |
| 21-50          | 14       | 2.88%   |
| 51-100         | 12       | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 143      | 28.95%  |
| 21-50          | 76       | 15.38%  |
| 101-250        | 59       | 11.94%  |
| 501-1000       | 50       | 10.12%  |
| 251-500        | 44       | 8.91%   |
| 51-100         | 40       | 8.1%    |
| 1001-2000      | 31       | 6.28%   |
| More than 3000 | 22       | 4.45%   |
| Unknown        | 18       | 3.64%   |
| 2001-3000      | 11       | 2.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD      | 3        | 5      | 6.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2        | 2      | 4.44%   |
| Kingston SHPM2280P2H 480G SSD         | 2        | 2      | 4.44%   |
| WDC WD5000AAKX-001CA0 500GB           | 1        | 1      | 2.22%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 2.22%   |
| WDC WD10EZRX-00A8LB0 1TB              | 1        | 1      | 2.22%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1        | 1      | 2.22%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1        | 1      | 2.22%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1      | 2.22%   |
| Toshiba MQ01ABD100 1TB                | 1        | 1      | 2.22%   |
| Toshiba MK6475GSX 640GB               | 1        | 1      | 2.22%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.22%   |
| Seagate ST380013AS 80GB               | 1        | 1      | 2.22%   |
| Seagate ST3400633AS 400GB             | 1        | 1      | 2.22%   |
| Seagate ST3250318AS 250GB             | 1        | 1      | 2.22%   |
| Seagate ST320LT020-9YG142 320GB       | 1        | 1      | 2.22%   |
| Seagate ST3200822AS 200GB             | 1        | 1      | 2.22%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.22%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 2.22%   |
| Seagate ST2000DX002-2DV164 2TB        | 1        | 1      | 2.22%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 2.22%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 2      | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 1      | 2.22%   |
| SanDisk SDSSDX240GG25 240GB           | 1        | 1      | 2.22%   |
| Samsung Electronics SSD 840 EVO 500GB | 1        | 1      | 2.22%   |
| Samsung Electronics SSD 750 EVO 250GB | 1        | 1      | 2.22%   |
| Samsung Electronics SP0812C 80GB      | 1        | 1      | 2.22%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 1      | 2.22%   |
| Samsung Electronics HD103SJ 1TB       | 1        | 1      | 2.22%   |
| OCZ AGILITY3 240GB SSD                | 1        | 1      | 2.22%   |
| Leven JAJS300M480C 480GB SSD          | 1        | 1      | 2.22%   |
| Kingston SA400S37480G 480GB SSD       | 1        | 1      | 2.22%   |
| Kingston SA400S37240G 240GB SSD       | 1        | 1      | 2.22%   |
| Kingston SA400S37120G 120GB SSD       | 1        | 1      | 2.22%   |
| Intel SSDSC2BW480H6 480GB             | 1        | 1      | 2.22%   |
| Intel SSDPEKKF256G7L 256GB            | 1        | 1      | 2.22%   |
| Hitachi HDT721025SLA380 250GB         | 1        | 1      | 2.22%   |
| Hitachi HDS721616PLA380 160GB         | 1        | 1      | 2.22%   |
| Hitachi HDP725032GLA360 320GB         | 1        | 2      | 2.22%   |
| Crucial CT275MX300SSD1 275GB          | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 12     | 22.5%   |
| Kingston            | 8        | 10     | 20%     |
| WDC                 | 7        | 8      | 17.5%   |
| Samsung Electronics | 4        | 5      | 10%     |
| Toshiba             | 3        | 3      | 7.5%    |
| Intel               | 2        | 2      | 5%      |
| Hitachi             | 2        | 4      | 5%      |
| SanDisk             | 1        | 1      | 2.5%    |
| OCZ                 | 1        | 1      | 2.5%    |
| Leven               | 1        | 1      | 2.5%    |
| Crucial             | 1        | 1      | 2.5%    |
| Unknown             | 1        | 2      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 12     | 40.91%  |
| WDC                 | 5        | 6      | 22.73%  |
| Toshiba             | 3        | 3      | 13.64%  |
| Samsung Electronics | 2        | 3      | 9.09%   |
| Hitachi             | 2        | 4      | 9.09%   |
| Unknown             | 1        | 2      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 30     | 51.43%  |
| SSD  | 16       | 19     | 45.71%  |
| NVMe | 1        | 1      | 2.86%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 301      | 802    | 58%     |
| Works    | 185      | 502    | 35.65%  |
| Malfunc  | 33       | 50     | 6.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 268      | 36.12%  |
| AMD                          | 171      | 23.05%  |
| Samsung Electronics          | 89       | 11.99%  |
| Kingston Technology Company  | 46       | 6.2%    |
| SanDisk                      | 31       | 4.18%   |
| ASMedia Technology           | 30       | 4.04%   |
| Phison Electronics           | 26       | 3.5%    |
| Marvell Technology Group     | 15       | 2.02%   |
| JMicron Technology           | 15       | 2.02%   |
| Micron/Crucial Technology    | 10       | 1.35%   |
| Nvidia                       | 9        | 1.21%   |
| Seagate Technology           | 6        | 0.81%   |
| ADATA Technology             | 4        | 0.54%   |
| VIA Technologies             | 3        | 0.4%    |
| SK hynix                     | 3        | 0.4%    |
| Realtek Semiconductor        | 3        | 0.4%    |
| Toshiba America Info Systems | 2        | 0.27%   |
| Silicon Motion               | 2        | 0.27%   |
| KIOXIA                       | 2        | 0.27%   |
| Hewlett-Packard              | 2        | 0.27%   |
| Silicon Image                | 1        | 0.13%   |
| Shenzhen Longsys Electronics | 1        | 0.13%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.13%   |
| HighPoint Technologies       | 1        | 0.13%   |
| Broadcom / LSI               | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 105      | 11.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 51       | 5.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 38       | 4.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 29       | 3.23%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 27       | 3.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26       | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 2.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 23       | 2.56%   |
| AMD 500 Series Chipset SATA Controller                                                  | 22       | 2.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 20       | 2.23%   |
| Intel SATA Controller [RAID mode]                                                       | 19       | 2.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18       | 2.01%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 17       | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17       | 1.9%    |
| AMD 600 Series Chipset SATA Controller                                                  | 17       | 1.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12       | 1.34%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 12       | 1.34%   |
| Phison E12 NVMe Controller                                                              | 12       | 1.34%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 12       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 1.34%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 11       | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11       | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 1%      |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 0.89%   |
| Intel SSD 660P Series                                                                   | 8        | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 0.89%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 7        | 0.78%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 7        | 0.78%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 7        | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 0.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.67%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 5        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 392      | 55.52%  |
| NVMe | 197      | 27.9%   |
| IDE  | 75       | 10.62%  |
| RAID | 41       | 5.81%   |
| SAS  | 1        | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 270      | 59.73%  |
| AMD    | 182      | 40.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 14       | 3.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 10       | 2.2%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 10       | 2.2%    |
| AMD Ryzen 7 5800X 8-Core Processor     | 9        | 1.98%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 9        | 1.98%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 8        | 1.76%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 6        | 1.32%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 6        | 1.32%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 5        | 1.1%    |
| Intel Core i7-8700K CPU @ 3.70GHz      | 5        | 1.1%    |
| Intel Core i7-4790K CPU @ 4.00GHz      | 5        | 1.1%    |
| Intel Core i5-10400F CPU @ 2.90GHz     | 5        | 1.1%    |
| AMD Ryzen 9 5950X 16-Core Processor    | 5        | 1.1%    |
| AMD Ryzen 9 5900X 12-Core Processor    | 5        | 1.1%    |
| AMD Ryzen 7 1700 Eight-Core Processor  | 5        | 1.1%    |
| AMD Ryzen 5 5600G with Radeon Graphics | 5        | 1.1%    |
| AMD Ryzen 5 2600 Six-Core Processor    | 5        | 1.1%    |
| Intel Core i7-8700 CPU @ 3.20GHz       | 4        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 4        | 0.88%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 4        | 0.88%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 4        | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 4        | 0.88%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 4        | 0.88%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 4        | 0.88%   |
| Intel 13th Gen Core i7-13700K          | 4        | 0.88%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 4        | 0.88%   |
| AMD Ryzen 7 3800X 8-Core Processor     | 4        | 0.88%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 4        | 0.88%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 4        | 0.88%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 0.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 0.66%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 3        | 0.66%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 3        | 0.66%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 3        | 0.66%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 3        | 0.66%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 3        | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 3        | 0.66%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 3        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 80       | 17.66%  |
| Intel Core i7           | 73       | 16.11%  |
| AMD Ryzen 7             | 52       | 11.48%  |
| AMD Ryzen 5             | 46       | 10.15%  |
| AMD Ryzen 9             | 32       | 7.06%   |
| Other                   | 25       | 5.52%   |
| Intel Xeon              | 21       | 4.64%   |
| Intel Core i3           | 18       | 3.97%   |
| Intel Core 2 Duo        | 13       | 2.87%   |
| AMD FX                  | 11       | 2.43%   |
| Intel Core i9           | 9        | 1.99%   |
| Intel Celeron           | 7        | 1.55%   |
| AMD Ryzen 3             | 7        | 1.55%   |
| AMD Ryzen Threadripper  | 6        | 1.32%   |
| Intel Pentium           | 5        | 1.1%    |
| Intel Core 2 Quad       | 5        | 1.1%    |
| AMD Phenom II X4        | 5        | 1.1%    |
| Intel Atom              | 4        | 0.88%   |
| AMD Athlon 64 X2        | 4        | 0.88%   |
| AMD A8                  | 4        | 0.88%   |
| AMD A6                  | 4        | 0.88%   |
| Intel Core 2            | 3        | 0.66%   |
| AMD Athlon II X4        | 3        | 0.66%   |
| AMD A10                 | 3        | 0.66%   |
| Intel Pentium Dual-Core | 2        | 0.44%   |
| AMD A4                  | 2        | 0.44%   |
| Intel Pentium Silver    | 1        | 0.22%   |
| Intel Pentium Dual      | 1        | 0.22%   |
| Intel Core m5           | 1        | 0.22%   |
| Intel Core 2 Extreme    | 1        | 0.22%   |
| Intel Core              | 1        | 0.22%   |
| AMD Phenom II X2        | 1        | 0.22%   |
| AMD GX                  | 1        | 0.22%   |
| AMD E                   | 1        | 0.22%   |
| AMD Athlon II Neo       | 1        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 160      | 35.16%  |
| 6      | 87       | 19.12%  |
| 8      | 70       | 15.38%  |
| 2      | 69       | 15.16%  |
| 12     | 26       | 5.71%   |
| 16     | 23       | 5.05%   |
| 10     | 7        | 1.54%   |
| 1      | 3        | 0.66%   |
| 32     | 2        | 0.44%   |
| 24     | 2        | 0.44%   |
| 14     | 2        | 0.44%   |
| 3      | 2        | 0.44%   |
| 64     | 1        | 0.22%   |
| 20     | 1        | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 448      | 99.12%  |
| 2      | 4        | 0.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 305      | 67.48%  |
| 1      | 147      | 32.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 448      | 98.46%  |
| Unknown        | 7        | 1.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 190      | 40.25%  |
| 0x306c3    | 24       | 5.08%   |
| 0x306a9    | 17       | 3.6%    |
| 0x506e3    | 16       | 3.39%   |
| 0x206a7    | 16       | 3.39%   |
| 0x08701021 | 13       | 2.75%   |
| 0x0800820d | 13       | 2.75%   |
| 0x906ea    | 9        | 1.91%   |
| 0x08001138 | 9        | 1.91%   |
| 0x906e9    | 8        | 1.69%   |
| 0x90672    | 8        | 1.69%   |
| 0x1067a    | 8        | 1.69%   |
| 0x08701013 | 8        | 1.69%   |
| 0x0a601203 | 7        | 1.48%   |
| 0x0a201009 | 7        | 1.48%   |
| 0x906ed    | 5        | 1.06%   |
| 0x6fd      | 5        | 1.06%   |
| 0x06000852 | 5        | 1.06%   |
| 0x010000c8 | 5        | 1.06%   |
| 0xa0655    | 4        | 0.85%   |
| 0xa0653    | 4        | 0.85%   |
| 0x906ec    | 4        | 0.85%   |
| 0x08600106 | 4        | 0.85%   |
| 0xa0671    | 3        | 0.64%   |
| 0x106e5    | 3        | 0.64%   |
| 0x10676    | 3        | 0.64%   |
| 0x0a201205 | 3        | 0.64%   |
| 0x0a201016 | 3        | 0.64%   |
| 0x08701030 | 3        | 0.64%   |
| 0x08001129 | 3        | 0.64%   |
| 0x06001119 | 3        | 0.64%   |
| 0x6f6      | 2        | 0.42%   |
| 0x506c9    | 2        | 0.42%   |
| 0x306e4    | 2        | 0.42%   |
| 0x206c2    | 2        | 0.42%   |
| 0x0a50000c | 2        | 0.42%   |
| 0x08108109 | 2        | 0.42%   |
| 0x08001137 | 2        | 0.42%   |
| 0x06003106 | 2        | 0.42%   |
| 0x0600063e | 2        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| KabyLake          | 54       | 11.89%  |
| Zen 2             | 51       | 11.23%  |
| Haswell           | 43       | 9.47%   |
| Zen 3             | 37       | 8.15%   |
| Unknown           | 32       | 7.05%   |
| Skylake           | 29       | 6.39%   |
| IvyBridge         | 27       | 5.95%   |
| SandyBridge       | 26       | 5.73%   |
| Zen+              | 19       | 4.19%   |
| Penryn            | 17       | 3.74%   |
| Zen               | 15       | 3.3%    |
| Alderlake Hybrid  | 13       | 2.86%   |
| Piledriver        | 12       | 2.64%   |
| CometLake         | 12       | 2.64%   |
| K10               | 10       | 2.2%    |
| Core              | 10       | 2.2%    |
| Nehalem           | 9        | 1.98%   |
| Westmere          | 5        | 1.1%    |
| K8 Hammer         | 4        | 0.88%   |
| Icelake           | 4        | 0.88%   |
| Steamroller       | 3        | 0.66%   |
| Puma              | 3        | 0.66%   |
| Bulldozer         | 3        | 0.66%   |
| Broadwell         | 3        | 0.66%   |
| Bonnell           | 3        | 0.66%   |
| Jaguar            | 2        | 0.44%   |
| Goldmont          | 2        | 0.44%   |
| Silvermont        | 1        | 0.22%   |
| Meteorlake Hybrid | 1        | 0.22%   |
| K10 Llano         | 1        | 0.22%   |
| Goldmont plus     | 1        | 0.22%   |
| Excavator         | 1        | 0.22%   |
| Bobcat            | 1        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 246      | 50.1%   |
| AMD                        | 138      | 28.11%  |
| Intel                      | 102      | 20.77%  |
| Matrox Electronics Systems | 3        | 0.61%   |
| ASPEED Technology          | 2        | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 19       | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 18       | 3.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 2.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13       | 2.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 2.37%   |
| AMD Raphael                                                                 | 12       | 2.37%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 11       | 2.17%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 10       | 1.98%   |
| Intel HD Graphics 530                                                       | 10       | 1.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 1.78%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 9        | 1.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 1.58%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 8        | 1.58%   |
| Intel HD Graphics 630                                                       | 8        | 1.58%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 1.38%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 1.38%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 7        | 1.38%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 7        | 1.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 1.38%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6        | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 1.19%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 5        | 0.99%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 5        | 0.99%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 5        | 0.99%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 0.99%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 0.99%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 4        | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.79%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.79%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.79%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 0.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 3        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 226      | 49.45%  |
| 1 x AMD         | 114      | 24.95%  |
| 1 x Intel       | 78       | 17.07%  |
| 2 x AMD         | 10       | 2.19%   |
| AMD + Nvidia    | 9        | 1.97%   |
| Intel + Nvidia  | 7        | 1.53%   |
| Intel + AMD     | 4        | 0.88%   |
| 2 x Nvidia      | 2        | 0.44%   |
| 2 x Intel       | 2        | 0.44%   |
| Nvidia + ASPEED | 2        | 0.44%   |
| 1 x Matrox      | 2        | 0.44%   |
| Nvidia + Matrox | 1        | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 295      | 63.17%  |
| Proprietary | 154      | 32.98%  |
| Unknown     | 18       | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 196      | 41.88%  |
| 1.01-2.0   | 69       | 14.74%  |
| 7.01-8.0   | 61       | 13.03%  |
| 3.01-4.0   | 28       | 5.98%   |
| 8.01-16.0  | 28       | 5.98%   |
| 0.01-0.5   | 26       | 5.56%   |
| 5.01-6.0   | 25       | 5.34%   |
| 0.51-1.0   | 19       | 4.06%   |
| 16.01-24.0 | 10       | 2.14%   |
| 2.01-3.0   | 5        | 1.07%   |
| 4.01-5.0   | 1        | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 116      | 22.48%  |
| Dell                 | 49       | 9.5%    |
| AOC                  | 37       | 7.17%   |
| Acer                 | 32       | 6.2%    |
| Ancor Communications | 31       | 6.01%   |
| Philips              | 30       | 5.81%   |
| Hewlett-Packard      | 27       | 5.23%   |
| Goldstar             | 26       | 5.04%   |
| Lenovo               | 25       | 4.84%   |
| BenQ                 | 25       | 4.84%   |
| ASUSTek Computer     | 24       | 4.65%   |
| Sony                 | 9        | 1.74%   |
| Unknown              | 8        | 1.55%   |
| Medion               | 7        | 1.36%   |
| Lenovo Group Limited | 5        | 0.97%   |
| LG Electronics       | 4        | 0.78%   |
| Fujitsu Siemens      | 4        | 0.78%   |
| Vestel Elektronik    | 3        | 0.58%   |
| MSI                  | 3        | 0.58%   |
| IBM                  | 3        | 0.58%   |
| Gigabyte Technology  | 3        | 0.58%   |
| Unknown              | 3        | 0.58%   |
| ViewSonic            | 2        | 0.39%   |
| Tech Concepts        | 2        | 0.39%   |
| RTK                  | 2        | 0.39%   |
| Mi                   | 2        | 0.39%   |
| Iiyama               | 2        | 0.39%   |
| Idek Iiyama          | 2        | 0.39%   |
| DENON                | 2        | 0.39%   |
| AUS                  | 2        | 0.39%   |
| Apple                | 2        | 0.39%   |
| Wacom                | 1        | 0.19%   |
| Vestel               | 1        | 0.19%   |
| Valve                | 1        | 0.19%   |
| UGD                  | 1        | 0.19%   |
| TopView              | 1        | 0.19%   |
| Pixio                | 1        | 0.19%   |
| Pioneer              | 1        | 0.19%   |
| Panasonic            | 1        | 0.19%   |
| Packard Bell         | 1        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 1.04%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 0.87%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 5        | 0.87%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 5        | 0.87%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                     | 4        | 0.7%    |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 3        | 0.52%   |
| Sony TV SNYEE01 1920x1080                                             | 3        | 0.52%   |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 700x400mm 31.7-inch    | 3        | 0.52%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch    | 3        | 0.52%   |
| Lenovo G27q-20 LEN66C3 2560x1440 597x336mm 27.0-inch                  | 3        | 0.52%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 3        | 0.52%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 3        | 0.52%   |
| BenQ EX3501R BNQ7F5E 3440x1440 819x346mm 35.0-inch                    | 3        | 0.52%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3        | 0.52%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 3        | 0.52%   |
| AOC 2460G4 AOC246A 1920x1080 531x299mm 24.0-inch                      | 3        | 0.52%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 3        | 0.52%   |
| Unknown                                                               | 3        | 0.52%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 2        | 0.35%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                      | 2        | 0.35%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 2        | 0.35%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.35%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 2        | 0.35%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch  | 2        | 0.35%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 2        | 0.35%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 0.35%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 2        | 0.35%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 2        | 0.35%   |
| Samsung Electronics LCD Monitor LF27T35 1920x1080                     | 2        | 0.35%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 2        | 0.35%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch    | 2        | 0.35%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 2        | 0.35%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 2        | 0.35%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch              | 2        | 0.35%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 2        | 0.35%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 2        | 0.35%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.35%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2        | 0.35%   |
| Philips 244E PHLC036 1920x1080 521x293mm 23.5-inch                    | 2        | 0.35%   |
| Medion MD20444 MED3661 1920x1080 521x293mm 23.5-inch                  | 2        | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 210      | 41.83%  |
| 2560x1440 (QHD)    | 77       | 15.34%  |
| 3840x2160 (4K)     | 58       | 11.55%  |
| 1680x1050 (WSXGA+) | 28       | 5.58%   |
| 1280x1024 (SXGA)   | 22       | 4.38%   |
| Unknown            | 18       | 3.59%   |
| 3440x1440          | 17       | 3.39%   |
| 1920x1200 (WUXGA)  | 13       | 2.59%   |
| 3840x1080          | 10       | 1.99%   |
| 1600x900 (HD+)     | 8        | 1.59%   |
| 1440x900 (WXGA+)   | 7        | 1.39%   |
| 3840x1200          | 5        | 1%      |
| 1360x768           | 5        | 1%      |
| 2560x1080          | 3        | 0.6%    |
| 2288x1287          | 2        | 0.4%    |
| 1920x540           | 2        | 0.4%    |
| 9840x3840          | 1        | 0.2%    |
| 6400x2160          | 1        | 0.2%    |
| 5760x1440          | 1        | 0.2%    |
| 5760x1080          | 1        | 0.2%    |
| 5120x1440          | 1        | 0.2%    |
| 4608x1440          | 1        | 0.2%    |
| 4480x1440          | 1        | 0.2%    |
| 3840x1600          | 1        | 0.2%    |
| 3280x1080          | 1        | 0.2%    |
| 3200x1200          | 1        | 0.2%    |
| 3200x1080          | 1        | 0.2%    |
| 2560x1600          | 1        | 0.2%    |
| 2560x1024          | 1        | 0.2%    |
| 2048x1152          | 1        | 0.2%    |
| 1600x1200          | 1        | 0.2%    |
| 1366x768 (WXGA)    | 1        | 0.2%    |
| 1360x765           | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 106      | 20.66%  |
| 24      | 84       | 16.37%  |
| Unknown | 60       | 11.7%   |
| 23      | 52       | 10.14%  |
| 31      | 40       | 7.8%    |
| 21      | 26       | 5.07%   |
| 19      | 22       | 4.29%   |
| 22      | 20       | 3.9%    |
| 34      | 17       | 3.31%   |
| 20      | 14       | 2.73%   |
| 72      | 10       | 1.95%   |
| 84      | 9        | 1.75%   |
| 40      | 6        | 1.17%   |
| 48      | 5        | 0.97%   |
| 17      | 5        | 0.97%   |
| 15      | 5        | 0.97%   |
| 32      | 4        | 0.78%   |
| 43      | 3        | 0.58%   |
| 35      | 3        | 0.58%   |
| 65      | 2        | 0.39%   |
| 39      | 2        | 0.39%   |
| 38      | 2        | 0.39%   |
| 33      | 2        | 0.39%   |
| 28      | 2        | 0.39%   |
| 25      | 2        | 0.39%   |
| 142     | 1        | 0.19%   |
| 74      | 1        | 0.19%   |
| 60      | 1        | 0.19%   |
| 54      | 1        | 0.19%   |
| 52      | 1        | 0.19%   |
| 42      | 1        | 0.19%   |
| 30      | 1        | 0.19%   |
| 29      | 1        | 0.19%   |
| 26      | 1        | 0.19%   |
| 18      | 1        | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 210      | 42.86%  |
| 401-500        | 69       | 14.08%  |
| Unknown        | 60       | 12.24%  |
| 601-700        | 55       | 11.22%  |
| 701-800        | 23       | 4.69%   |
| 1501-2000      | 20       | 4.08%   |
| 351-400        | 15       | 3.06%   |
| 1001-1500      | 13       | 2.65%   |
| 801-900        | 12       | 2.45%   |
| 301-350        | 10       | 2.04%   |
| 901-1000       | 2        | 0.41%   |
| More than 2000 | 1        | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 298      | 63.95%  |
| 16/10   | 57       | 12.23%  |
| Unknown | 53       | 11.37%  |
| 21/9    | 23       | 4.94%   |
| 5/4     | 20       | 4.29%   |
| 32/9    | 6        | 1.29%   |
| 3.20    | 3        | 0.64%   |
| 4/3     | 2        | 0.43%   |
| 3/2     | 2        | 0.43%   |
| 6/5     | 1        | 0.21%   |
| 1.00    | 1        | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 140      | 27.94%  |
| 301-350        | 106      | 21.16%  |
| 351-500        | 68       | 13.57%  |
| Unknown        | 60       | 11.98%  |
| 151-200        | 41       | 8.18%   |
| 251-300        | 32       | 6.39%   |
| More than 1000 | 25       | 4.99%   |
| 501-1000       | 19       | 3.79%   |
| 141-150        | 5        | 1%      |
| 101-110        | 4        | 0.8%    |
| 111-120        | 1        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 278      | 59.78%  |
| 101-120 | 89       | 19.14%  |
| Unknown | 60       | 12.9%   |
| 121-160 | 21       | 4.52%   |
| 1-50    | 12       | 2.58%   |
| 161-240 | 5        | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 318      | 68.98%  |
| 2     | 103      | 22.34%  |
| 0     | 22       | 4.77%   |
| 3     | 18       | 3.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 266      | 40.36%  |
| Intel                           | 223      | 33.84%  |
| Broadcom                        | 24       | 3.64%   |
| Qualcomm Atheros                | 23       | 3.49%   |
| MediaTek                        | 13       | 1.97%   |
| Ralink Technology               | 10       | 1.52%   |
| Ralink                          | 10       | 1.52%   |
| TP-Link                         | 9        | 1.37%   |
| Nvidia                          | 9        | 1.37%   |
| Aquantia                        | 9        | 1.37%   |
| Microsoft                       | 7        | 1.06%   |
| ASUSTek Computer                | 6        | 0.91%   |
| Samsung Electronics             | 4        | 0.61%   |
| Qualcomm Atheros Communications | 4        | 0.61%   |
| IMC Networks                    | 4        | 0.61%   |
| Huawei Technologies             | 4        | 0.61%   |
| OnePlus Technology (Shenzhen)   | 3        | 0.46%   |
| NetGear                         | 3        | 0.46%   |
| Edimax Technology               | 3        | 0.46%   |
| D-Link                          | 3        | 0.46%   |
| ASIX Electronics                | 3        | 0.46%   |
| ZyXEL Communications            | 2        | 0.3%    |
| Marvell Technology Group        | 2        | 0.3%    |
| D-Link System                   | 2        | 0.3%    |
| VIA Technologies                | 1        | 0.15%   |
| Unknown                         | 1        | 0.15%   |
| Texas Instruments               | 1        | 0.15%   |
| Solarflare Communications       | 1        | 0.15%   |
| ROCCAT                          | 1        | 0.15%   |
| Motorola PCS                    | 1        | 0.15%   |
| Linksys                         | 1        | 0.15%   |
| Lenovo                          | 1        | 0.15%   |
| JMicron Technology              | 1        | 0.15%   |
| InterBiometrics                 | 1        | 0.15%   |
| ICS Advent                      | 1        | 0.15%   |
| HMD Global                      | 1        | 0.15%   |
| Conexant Systems                | 1        | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 195      | 25.56%  |
| Realtek RTL8125 2.5GbE Controller                                              | 43       | 5.64%   |
| Intel I211 Gigabit Network Connection                                          | 41       | 5.37%   |
| Intel Wi-Fi 6 AX200                                                            | 29       | 3.8%    |
| Intel Ethernet Connection (2) I219-V                                           | 29       | 3.8%    |
| Intel Ethernet Controller I225-V                                               | 20       | 2.62%   |
| Intel Ethernet Connection I217-LM                                              | 16       | 2.1%    |
| Intel Ethernet Connection (7) I219-V                                           | 14       | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 12       | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12       | 1.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 11       | 1.44%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 10       | 1.31%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 9        | 1.18%   |
| Realtek 802.11ac NIC                                                           | 8        | 1.05%   |
| Intel 82579V Gigabit Network Connection                                        | 7        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6        | 0.79%   |
| Ralink RT5370 Wireless Adapter                                                 | 6        | 0.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 6        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                                           | 6        | 0.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 6        | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 5        | 0.66%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 5        | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 0.66%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                   | 5        | 0.66%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 5        | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 4        | 0.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4        | 0.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4        | 0.52%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4        | 0.52%   |
| Intel Ethernet Connection (11) I219-V                                          | 4        | 0.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 4        | 0.52%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                           | 4        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3        | 0.39%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 3        | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3        | 0.39%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 3        | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3        | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 88       | 36.82%  |
| Realtek Semiconductor           | 46       | 19.25%  |
| Broadcom                        | 18       | 7.53%   |
| Qualcomm Atheros                | 12       | 5.02%   |
| MediaTek                        | 11       | 4.6%    |
| Ralink Technology               | 10       | 4.18%   |
| Ralink                          | 10       | 4.18%   |
| TP-Link                         | 9        | 3.77%   |
| Microsoft                       | 7        | 2.93%   |
| ASUSTek Computer                | 6        | 2.51%   |
| Qualcomm Atheros Communications | 4        | 1.67%   |
| IMC Networks                    | 4        | 1.67%   |
| NetGear                         | 3        | 1.26%   |
| Edimax Technology               | 3        | 1.26%   |
| D-Link                          | 3        | 1.26%   |
| ZyXEL Communications            | 2        | 0.84%   |
| D-Link System                   | 2        | 0.84%   |
| Linksys                         | 1        | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 29       | 11.93%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 12       | 4.94%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 11       | 4.53%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 10       | 4.12%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 9        | 3.7%    |
| Realtek 802.11ac NIC                                                                 | 8        | 3.29%   |
| Ralink RT5370 Wireless Adapter                                                       | 6        | 2.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 6        | 2.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 6        | 2.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 5        | 2.06%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 5        | 2.06%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                         | 5        | 2.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 4        | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 4        | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 1.65%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 3        | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                      | 3        | 1.23%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                            | 3        | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 3        | 1.23%   |
| Intel Wireless 8260                                                                  | 3        | 1.23%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                    | 3        | 1.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 2        | 0.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 2        | 0.82%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 2        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 2        | 0.82%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2        | 0.82%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 0.82%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 0.82%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 2        | 0.82%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                          | 2        | 0.82%   |
| Microsoft Xbox 360 Wireless Adapter                                                  | 2        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 248      | 50.41%  |
| Intel                         | 185      | 37.6%   |
| Qualcomm Atheros              | 13       | 2.64%   |
| Nvidia                        | 9        | 1.83%   |
| Aquantia                      | 9        | 1.83%   |
| Broadcom                      | 6        | 1.22%   |
| Samsung Electronics           | 3        | 0.61%   |
| OnePlus Technology (Shenzhen) | 3        | 0.61%   |
| ASIX Electronics              | 3        | 0.61%   |
| MediaTek                      | 2        | 0.41%   |
| Marvell Technology Group      | 2        | 0.41%   |
| Huawei Technologies           | 2        | 0.41%   |
| VIA Technologies              | 1        | 0.2%    |
| Solarflare Communications     | 1        | 0.2%    |
| Motorola PCS                  | 1        | 0.2%    |
| Lenovo                        | 1        | 0.2%    |
| JMicron Technology            | 1        | 0.2%    |
| ICS Advent                    | 1        | 0.2%    |
| HMD Global                    | 1        | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 195      | 38.09%  |
| Realtek RTL8125 2.5GbE Controller                                               | 43       | 8.4%    |
| Intel I211 Gigabit Network Connection                                           | 41       | 8.01%   |
| Intel Ethernet Connection (2) I219-V                                            | 29       | 5.66%   |
| Intel Ethernet Controller I225-V                                                | 20       | 3.91%   |
| Intel Ethernet Connection I217-LM                                               | 16       | 3.13%   |
| Intel Ethernet Connection (7) I219-V                                            | 14       | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 12       | 2.34%   |
| Intel 82579V Gigabit Network Connection                                         | 7        | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 6        | 1.17%   |
| Intel Ethernet Connection (2) I218-V                                            | 6        | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                                      | 5        | 0.98%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 5        | 0.98%   |
| Intel I210 Gigabit Network Connection                                           | 4        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                           | 4        | 0.78%   |
| Intel Ethernet Connection (11) I219-V                                           | 4        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 3        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                 | 3        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 3        | 0.59%   |
| OnePlus (Shenzhen) OnePlus                                                      | 3        | 0.59%   |
| Nvidia MCP73 Ethernet                                                           | 3        | 0.59%   |
| Intel Ethernet Connection (5) I219-LM                                           | 3        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                           | 3        | 0.59%   |
| Intel Ethernet Connection (2) I218-LM                                           | 3        | 0.59%   |
| Intel Ethernet Connection (17) I219-V                                           | 3        | 0.59%   |
| Intel 82574L Gigabit Network Connection                                         | 3        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 3        | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 2        | 0.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 2        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 2        | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 2        | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 2        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 2        | 0.39%   |
| Nvidia MCP61 Ethernet                                                           | 2        | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                         | 2        | 0.39%   |
| Intel I350 Gigabit Network Connection                                           | 2        | 0.39%   |
| Intel Ethernet Connection I217-V                                                | 2        | 0.39%   |
| Intel 82576 Gigabit Network Connection                                          | 2        | 0.39%   |
| Huawei FOA-LX9                                                                  | 2        | 0.39%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 2        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 448      | 66.17%  |
| WiFi     | 221      | 32.64%  |
| Modem    | 6        | 0.89%   |
| Unknown  | 2        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 363      | 76.91%  |
| WiFi     | 108      | 22.88%  |
| Modem    | 1        | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 251      | 55.16%  |
| 2     | 164      | 36.04%  |
| 3     | 30       | 6.59%   |
| 0     | 5        | 1.1%    |
| 4     | 3        | 0.66%   |
| 5     | 2        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 421      | 92.73%  |
| Yes  | 33       | 7.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 85       | 45.45%  |
| Cambridge Silicon Radio         | 36       | 19.25%  |
| ASUSTek Computer                | 13       | 6.95%   |
| Realtek Semiconductor           | 11       | 5.88%   |
| IMC Networks                    | 11       | 5.88%   |
| MediaTek                        | 10       | 5.35%   |
| Broadcom                        | 6        | 3.21%   |
| Qualcomm Atheros Communications | 5        | 2.67%   |
| TP-Link                         | 3        | 1.6%    |
| Edimax Technology               | 2        | 1.07%   |
| Belkin Components               | 2        | 1.07%   |
| Integrated System Solution      | 1        | 0.53%   |
| HTC (High Tech Computer)        | 1        | 0.53%   |
| Actions                         | 1        | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 36       | 19.25%  |
| Intel AX200 Bluetooth                                                | 25       | 13.37%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 12       | 6.42%   |
| Intel Bluetooth wireless interface                                   | 11       | 5.88%   |
| Intel AX210 Bluetooth                                                | 11       | 5.88%   |
| MediaTek Wireless_Device                                             | 10       | 5.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 9        | 4.81%   |
| ASUS ASUS USB-BT500                                                  | 7        | 3.74%   |
| Intel AX201 Bluetooth                                                | 6        | 3.21%   |
| IMC Networks Bluetooth Radio                                         | 6        | 3.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5        | 2.67%   |
| Intel AX211 Bluetooth                                                | 5        | 2.67%   |
| Realtek Bluetooth Radio                                              | 4        | 2.14%   |
| TP-Link TP-Link Bluetooth USB Adapter                                | 3        | 1.6%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 3        | 1.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3        | 1.6%    |
| ASUS Bluetooth Radio                                                 | 3        | 1.6%    |
| Realtek RTL8821A Bluetooth                                           | 2        | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2        | 1.07%   |
| IMC Networks Wireless_Device                                         | 2        | 1.07%   |
| IMC Networks Bluetooth Device                                        | 2        | 1.07%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 1.07%   |
| Realtek Bluetooth 5.3 Radio                                          | 1        | 0.53%   |
| Realtek 802.11ac WLAN Adapter                                        | 1        | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.53%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.53%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.53%   |
| IMC Networks BCM20702A0                                              | 1        | 0.53%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.53%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.53%   |
| Edimax Bluetooth Adapter                                             | 1        | 0.53%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 0.53%   |
| Broadcom HP Bluetooth Module                                         | 1        | 0.53%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.53%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.53%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.53%   |
| Actions general adapter                                              | 1        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 245      | 27.59%  |
| Nvidia                               | 242      | 27.25%  |
| AMD                                  | 211      | 23.76%  |
| SteelSeries ApS                      | 19       | 2.14%   |
| Kingston Technology                  | 18       | 2.03%   |
| Logitech                             | 17       | 1.91%   |
| C-Media Electronics                  | 15       | 1.69%   |
| ASUSTek Computer                     | 12       | 1.35%   |
| Creative Technology                  | 11       | 1.24%   |
| Creative Labs                        | 11       | 1.24%   |
| Texas Instruments                    | 7        | 0.79%   |
| GN Netcom                            | 6        | 0.68%   |
| Corsair                              | 6        | 0.68%   |
| XMOS                                 | 5        | 0.56%   |
| Focusrite-Novation                   | 5        | 0.56%   |
| BEHRINGER International              | 4        | 0.45%   |
| VIA Technologies                     | 3        | 0.34%   |
| RODE Microphones                     | 3        | 0.34%   |
| Realtek Semiconductor                | 3        | 0.34%   |
| Razer USA                            | 3        | 0.34%   |
| Yamaha                               | 2        | 0.23%   |
| Tenx Technology                      | 2        | 0.23%   |
| Sony                                 | 2        | 0.23%   |
| JMTek                                | 2        | 0.23%   |
| Hewlett-Packard                      | 2        | 0.23%   |
| Astro Gaming                         | 2        | 0.23%   |
| Valve Software                       | 1        | 0.11%   |
| Turtle Beach                         | 1        | 0.11%   |
| Trust                                | 1        | 0.11%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.11%   |
| Tempest                              | 1        | 0.11%   |
| Syntek                               | 1        | 0.11%   |
| Shure                                | 1        | 0.11%   |
| Setek Elektronik                     | 1        | 0.11%   |
| SAVITECH                             | 1        | 0.11%   |
| Samsung Electronics                  | 1        | 0.11%   |
| ROCCAT                               | 1        | 0.11%   |
| Nordic Semiconductor ASA             | 1        | 0.11%   |
| Musical Fidelity                     | 1        | 0.11%   |
| Medeli Electronics                   | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 69       | 6.74%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                      | 36       | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 30       | 2.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 30       | 2.93%   |
| Intel 200 Series PCH HD Audio                                                                   | 29       | 2.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 27       | 2.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 24       | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 24       | 2.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 23       | 2.25%   |
| AMD Navi 10 HDMI Audio                                                                          | 21       | 2.05%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 20       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 20       | 1.95%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 18       | 1.76%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 18       | 1.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 18       | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                                      | 17       | 1.66%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 17       | 1.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 17       | 1.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 17       | 1.66%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 16       | 1.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 15       | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 14       | 1.37%   |
| Kingston Technology HyperX 7.1 Audio                                                            | 14       | 1.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 14       | 1.37%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 12       | 1.17%   |
| AMD Navi 31 HDMI/DP Audio                                                                       | 12       | 1.17%   |
| AMD FCH Azalia Controller                                                                       | 12       | 1.17%   |
| Nvidia TU104 HD Audio Controller                                                                | 11       | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 11       | 1.07%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 10       | 0.98%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 10       | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 10       | 0.98%   |
| ASUSTek Computer USB Audio                                                                      | 10       | 0.98%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 8        | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 8        | 0.78%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 8        | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 7        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 7        | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 7        | 0.68%   |
| Intel Comet Lake PCH cAVS                                                                       | 7        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 59       | 22.26%  |
| G.Skill             | 48       | 18.11%  |
| Kingston            | 45       | 16.98%  |
| Samsung Electronics | 25       | 9.43%   |
| Unknown             | 23       | 8.68%   |
| Crucial             | 17       | 6.42%   |
| Micron Technology   | 14       | 5.28%   |
| SK hynix            | 12       | 4.53%   |
| Ramaxel Technology  | 4        | 1.51%   |
| Nanya Technology    | 4        | 1.51%   |
| Team                | 3        | 1.13%   |
| Unknown             | 3        | 1.13%   |
| Patriot             | 2        | 0.75%   |
| Elpida              | 2        | 0.75%   |
| Unknown (ABCD)      | 1        | 0.38%   |
| Unifosa             | 1        | 0.38%   |
| GOODRAM             | 1        | 0.38%   |
| A-DATA Technology   | 1        | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 9        | 3.21%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s | 4        | 1.43%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 4        | 1.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s | 4        | 1.43%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s  | 4        | 1.43%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 3        | 1.07%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s    | 3        | 1.07%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 3        | 1.07%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s | 3        | 1.07%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 3        | 1.07%   |
| Unknown                                                | 3        | 1.07%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 2        | 0.71%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 2        | 0.71%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                   | 2        | 0.71%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 2        | 0.71%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 2        | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 2        | 0.71%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s    | 2        | 0.71%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s    | 2        | 0.71%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s    | 2        | 0.71%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s    | 2        | 0.71%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s       | 2        | 0.71%   |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 12800MT/s      | 2        | 0.71%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s       | 2        | 0.71%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 0.71%   |
| Kingston RAM HP24D4U7S8MBP-8 8GB DIMM DDR4 2400MT/s    | 2        | 0.71%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s   | 2        | 0.71%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 2        | 0.71%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3200MT/s  | 2        | 0.71%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s  | 2        | 0.71%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s    | 2        | 0.71%   |
| Corsair RAM CMY32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s   | 2        | 0.71%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 2        | 0.71%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3200MT/s   | 2        | 0.71%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s | 2        | 0.71%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s | 2        | 0.71%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s | 2        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.36%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 1        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 135      | 56.72%  |
| DDR3    | 57       | 23.95%  |
| DDR5    | 19       | 7.98%   |
| Unknown | 12       | 5.04%   |
| SDRAM   | 8        | 3.36%   |
| DDR2    | 3        | 1.26%   |
| DDR     | 2        | 0.84%   |
| LPDDR4  | 1        | 0.42%   |
| LPDDR3  | 1        | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 218      | 92.77%  |
| SODIMM | 17       | 7.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 98       | 38.43%  |
| 16384 | 73       | 28.63%  |
| 4096  | 40       | 15.69%  |
| 2048  | 23       | 9.02%   |
| 32768 | 17       | 6.67%   |
| 1024  | 3        | 1.18%   |
| 512   | 1        | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 36       | 13.95%  |
| 3600    | 29       | 11.24%  |
| 3200    | 28       | 10.85%  |
| 2400    | 19       | 7.36%   |
| 1333    | 19       | 7.36%   |
| 3800    | 12       | 4.65%   |
| 2667    | 7        | 2.71%   |
| 2133    | 7        | 2.71%   |
| 6000    | 6        | 2.33%   |
| 3866    | 5        | 1.94%   |
| 3733    | 5        | 1.94%   |
| 3400    | 5        | 1.94%   |
| 3000    | 5        | 1.94%   |
| 1800    | 5        | 1.94%   |
| 5200    | 4        | 1.55%   |
| 3666    | 4        | 1.55%   |
| 3466    | 4        | 1.55%   |
| 2933    | 4        | 1.55%   |
| 667     | 4        | 1.55%   |
| 4800    | 3        | 1.16%   |
| 4000    | 3        | 1.16%   |
| 3534    | 3        | 1.16%   |
| 2666    | 3        | 1.16%   |
| 1867    | 3        | 1.16%   |
| 1866    | 3        | 1.16%   |
| 12800   | 2        | 0.78%   |
| 5600    | 2        | 0.78%   |
| 3500    | 2        | 0.78%   |
| 3266    | 2        | 0.78%   |
| 2800    | 2        | 0.78%   |
| 2048    | 2        | 0.78%   |
| 1639    | 2        | 0.78%   |
| 1066    | 2        | 0.78%   |
| Unknown | 2        | 0.78%   |
| 20306   | 1        | 0.39%   |
| 7200    | 1        | 0.39%   |
| 6400    | 1        | 0.39%   |
| 4400    | 1        | 0.39%   |
| 3333    | 1        | 0.39%   |
| 3100    | 1        | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 44.44%  |
| Brother Industries  | 5        | 27.78%  |
| Canon               | 3        | 16.67%  |
| Xerox               | 1        | 5.56%   |
| Prolific Technology | 1        | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Brother DCP-J140W                  | 2        | 11.11%  |
| Xerox Phaser 6125N                 | 1        | 5.56%   |
| Prolific PL2305 Parallel Port      | 1        | 5.56%   |
| HP LaserJet 1020                   | 1        | 5.56%   |
| HP ENVY Photo 6200 series          | 1        | 5.56%   |
| HP ENVY 4520 series                | 1        | 5.56%   |
| HP Deskjet D4300 series            | 1        | 5.56%   |
| HP DeskJet 5940                    | 1        | 5.56%   |
| HP DeskJet 5550                    | 1        | 5.56%   |
| HP DeskJet 2700 series             | 1        | 5.56%   |
| HP DeskJet 2620 All-in-One Printer | 1        | 5.56%   |
| Canon LiDE 400                     | 1        | 5.56%   |
| Canon iP7200 series                | 1        | 5.56%   |
| Canon CanoScan LiDE 300            | 1        | 5.56%   |
| Brother HL-5250DN Printer          | 1        | 5.56%   |
| Brother HL-2240D series            | 1        | 5.56%   |
| Brother HL-2030 Laser Printer      | 1        | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 50%     |
| Hewlett-Packard | 2        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]       | 1        | 25%     |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1        | 25%     |
| HP ScanJet 5470c/5490c                            | 1        | 25%     |
| HP PSC 1200                                       | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 34       | 49.28%  |
| Microsoft                              | 5        | 7.25%   |
| Trust                                  | 4        | 5.8%    |
| Creative Technology                    | 3        | 4.35%   |
| Chicony Electronics                    | 3        | 4.35%   |
| Sunplus Innovation Technology          | 2        | 2.9%    |
| Samsung Electronics                    | 2        | 2.9%    |
| YLX-231212-H                           | 1        | 1.45%   |
| vivo                                   | 1        | 1.45%   |
| Valve Software                         | 1        | 1.45%   |
| SunplusIT                              | 1        | 1.45%   |
| Quanta                                 | 1        | 1.45%   |
| Oculus VR                              | 1        | 1.45%   |
| Microdia                               | 1        | 1.45%   |
| MacroSilicon                           | 1        | 1.45%   |
| Intel                                  | 1        | 1.45%   |
| Hewlett-Packard                        | 1        | 1.45%   |
| GenesysLogic Technology                | 1        | 1.45%   |
| Generalplus Technology                 | 1        | 1.45%   |
| eMeet                                  | 1        | 1.45%   |
| Cubeternet                             | 1        | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 1.45%   |
| Apple                                  | 1        | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 5        | 7.25%   |
| Trust Trust USB Camera                  | 4        | 5.8%    |
| Logitech StreamCam                      | 4        | 5.8%    |
| Logitech HD Webcam C525                 | 4        | 5.8%    |
| Microsoft LifeCam Cinema                | 3        | 4.35%   |
| Logitech Webcam Pro 9000                | 3        | 4.35%   |
| Logitech C922 Pro Stream Webcam         | 3        | 4.35%   |
| Samsung Galaxy series, misc. (MTP mode) | 2        | 2.9%    |
| Logitech Webcam C270                    | 2        | 2.9%    |
| Logitech Logitech Webcam C925e          | 2        | 2.9%    |
| Logitech C930c                          | 2        | 2.9%    |
| Logitech BRIO Ultra HD Webcam           | 2        | 2.9%    |
| YLX-231212-H Streaming Webcams          | 1        | 1.45%   |
| vivo 1904                               | 1        | 1.45%   |
| Valve Software 3D Camera                | 1        | 1.45%   |
| SunplusIT USB camera                    | 1        | 1.45%   |
| Sunplus SunplusIT PC Camera             | 1        | 1.45%   |
| Sunplus Sandberg USB Webcam Pro         | 1        | 1.45%   |
| Quanta FREETALK Conference              | 1        | 1.45%   |
| Oculus VR Quest 2                       | 1        | 1.45%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 1        | 1.45%   |
| Microsoft LifeCam HD-3000               | 1        | 1.45%   |
| Microdia USB 2.0 Camera                 | 1        | 1.45%   |
| MacroSilicon USB Video                  | 1        | 1.45%   |
| Logitech Webcam C930e                   | 1        | 1.45%   |
| Logitech QuickCam Pro 5000              | 1        | 1.45%   |
| Logitech QuickCam E 3500                | 1        | 1.45%   |
| Logitech MeetUp                         | 1        | 1.45%   |
| Logitech HD Webcam C615                 | 1        | 1.45%   |
| Logitech HD Webcam C510                 | 1        | 1.45%   |
| Logitech C670i FHD Webcam               | 1        | 1.45%   |
| Intel RealSense SR300                   | 1        | 1.45%   |
| HP HD-4110 Webcam                       | 1        | 1.45%   |
| GenesysLogic USB2.0 UVC PC Camera       | 1        | 1.45%   |
| Generalplus GENERAL WEBCAM              | 1        | 1.45%   |
| eMeet HD Webcam C960                    | 1        | 1.45%   |
| Cubeternet USB2.0 Camera                | 1        | 1.45%   |
| Creative VF0610 Live! Cam Socialize HD  | 1        | 1.45%   |
| Creative Live! Cam Sync [VF0520]        | 1        | 1.45%   |
| Creative Live! Cam Sync 1080p           | 1        | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Advanced Card Systems ACR1252 Dual Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 382      | 83.04%  |
| 1     | 62       | 13.48%  |
| 2     | 11       | 2.39%   |
| 3     | 3        | 0.65%   |
| 6     | 1        | 0.22%   |
| 4     | 1        | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 28       | 30.77%  |
| Net/wireless             | 26       | 28.57%  |
| Unassigned class         | 7        | 7.69%   |
| Sound                    | 7        | 7.69%   |
| Communication controller | 7        | 7.69%   |
| Multimedia controller    | 6        | 6.59%   |
| Storage/raid             | 2        | 2.2%    |
| Net/ethernet             | 2        | 2.2%    |
| Card reader              | 2        | 2.2%    |
| Network                  | 1        | 1.1%    |
| Fingerprint reader       | 1        | 1.1%    |
| Chipcard                 | 1        | 1.1%    |
| Camera                   | 1        | 1.1%    |

