Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 2390

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | H61 V1.6B                   | [699b915313](https://linux-hardware.org/?probe=699b915313) | Jan 03, 2025 |
| Gigabyte      | A320M-S2H-CF                | [0e08cf46c1](https://linux-hardware.org/?probe=0e08cf46c1) | Dec 22, 2024 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [f6869ae032](https://linux-hardware.org/?probe=f6869ae032) | Dec 21, 2024 |
| ASUSTek       | P8P67                       | [6322c78de6](https://linux-hardware.org/?probe=6322c78de6) | Dec 15, 2024 |
| ASUSTek       | P8P67                       | [ee3b9d1e1e](https://linux-hardware.org/?probe=ee3b9d1e1e) | Dec 15, 2024 |
| HP            | 81C5 MVB                    | [d1d4415deb](https://linux-hardware.org/?probe=d1d4415deb) | Dec 14, 2024 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [2ea7e62746](https://linux-hardware.org/?probe=2ea7e62746) | Dec 08, 2024 |
| Gigabyte      | A320M-S2H-CF                | [cff02d6c2f](https://linux-hardware.org/?probe=cff02d6c2f) | Nov 28, 2024 |
| HP            | 0B4Ch D                     | [8ce4158fcc](https://linux-hardware.org/?probe=8ce4158fcc) | Nov 26, 2024 |
| HP            | 0B4Ch D                     | [5565676cca](https://linux-hardware.org/?probe=5565676cca) | Nov 26, 2024 |
| Dell          | 0XPDFK A01                  | [31b83f832c](https://linux-hardware.org/?probe=31b83f832c) | Nov 26, 2024 |
| MSI           | A320M-A PRO MAX             | [2ab5021d2a](https://linux-hardware.org/?probe=2ab5021d2a) | Nov 15, 2024 |
| ASUSTek       | P8Z77-V PRO                 | [d4267ac21d](https://linux-hardware.org/?probe=d4267ac21d) | Nov 10, 2024 |
| Gigabyte      | Z77-DS3H                    | [6a09c5bd87](https://linux-hardware.org/?probe=6a09c5bd87) | Nov 04, 2024 |
| Dell          | 0N826N A03                  | [c3e4a08e65](https://linux-hardware.org/?probe=c3e4a08e65) | Oct 29, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [abc719cbd3](https://linux-hardware.org/?probe=abc719cbd3) | Oct 24, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [ea01741e08](https://linux-hardware.org/?probe=ea01741e08) | Oct 20, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [5c0c4c8a95](https://linux-hardware.org/?probe=5c0c4c8a95) | Oct 20, 2024 |
| HP            | 1588h                       | [786517e71e](https://linux-hardware.org/?probe=786517e71e) | Oct 16, 2024 |
| MSI           | 2AE0                        | [5bc9ad1a3b](https://linux-hardware.org/?probe=5bc9ad1a3b) | Oct 13, 2024 |
| ASUSTek       | M5A97 R2.0                  | [8646abd860](https://linux-hardware.org/?probe=8646abd860) | Oct 13, 2024 |
| Gigabyte      | 965P-DS3                    | [ef897b50d1](https://linux-hardware.org/?probe=ef897b50d1) | Oct 02, 2024 |
| Huanan        | X99-F8                      | [619b6f5845](https://linux-hardware.org/?probe=619b6f5845) | Oct 02, 2024 |
| Dell          | 0GDG8Y A00                  | [6ecee0fbfa](https://linux-hardware.org/?probe=6ecee0fbfa) | Sep 26, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | [8d920340a6](https://linux-hardware.org/?probe=8d920340a6) | Sep 25, 2024 |
| HP            | 1588h                       | [8ffd21442a](https://linux-hardware.org/?probe=8ffd21442a) | Sep 20, 2024 |
| MACHINIST     | X99-RS9 V1.11               | [845631b912](https://linux-hardware.org/?probe=845631b912) | Sep 17, 2024 |
| Dell          | 0XCR8D A01                  | [193c008674](https://linux-hardware.org/?probe=193c008674) | Sep 11, 2024 |
| Dell          | 0XCR8D A01                  | [54958cec9e](https://linux-hardware.org/?probe=54958cec9e) | Sep 05, 2024 |
| Dell          | 0XCR8D A01                  | [9a5f1a7fc5](https://linux-hardware.org/?probe=9a5f1a7fc5) | Sep 05, 2024 |
| Dell          | 0XPDFK A01                  | [1a28c32ab7](https://linux-hardware.org/?probe=1a28c32ab7) | Sep 02, 2024 |
| MSI           | B85M-E45                    | [7869cac8af](https://linux-hardware.org/?probe=7869cac8af) | Aug 28, 2024 |
| Intel         | DQ67SW AAG12527-310         | [cc5d283911](https://linux-hardware.org/?probe=cc5d283911) | Aug 27, 2024 |
| Gigabyte      | 965P-DS3                    | [2c84d9fba6](https://linux-hardware.org/?probe=2c84d9fba6) | Aug 25, 2024 |
| Gigabyte      | 965P-DS3                    | [f710d2efd4](https://linux-hardware.org/?probe=f710d2efd4) | Aug 23, 2024 |
| ASUSTek       | P8Z77-V LX                  | [5155a3774a](https://linux-hardware.org/?probe=5155a3774a) | Aug 22, 2024 |
| ASUSTek       | P8Z77-V LX                  | [74426e6a03](https://linux-hardware.org/?probe=74426e6a03) | Aug 19, 2024 |
| Biostar       | TA970 Plus                  | [377448fd65](https://linux-hardware.org/?probe=377448fd65) | Aug 18, 2024 |
| Biostar       | TA970 Plus                  | [acb6724986](https://linux-hardware.org/?probe=acb6724986) | Aug 18, 2024 |
| HC Technol... | HCAR5000-MI                 | [94a808c7bd](https://linux-hardware.org/?probe=94a808c7bd) | Aug 11, 2024 |
| MSI           | PRO Z790-A WIFI             | [8fed693674](https://linux-hardware.org/?probe=8fed693674) | Aug 07, 2024 |
| HC Technol... | HCAR5000-MI                 | [cc25e78cc9](https://linux-hardware.org/?probe=cc25e78cc9) | Aug 04, 2024 |
| Biostar       | TA970 Plus                  | [b9ca2cb935](https://linux-hardware.org/?probe=b9ca2cb935) | Aug 02, 2024 |
| Acer          | Predator PO3-640            | [efe0a9a9ec](https://linux-hardware.org/?probe=efe0a9a9ec) | Aug 01, 2024 |
| Dell          | 0VYXHD A00                  | [179bff5118](https://linux-hardware.org/?probe=179bff5118) | Jul 31, 2024 |
| ASRock        | H510M-HDV/M.2               | [2e993c4215](https://linux-hardware.org/?probe=2e993c4215) | Jul 27, 2024 |
| ASRock        | H510M-HDV/M.2               | [a9d457cbfe](https://linux-hardware.org/?probe=a9d457cbfe) | Jul 27, 2024 |
| Biostar       | A78MD                       | [b290e933bc](https://linux-hardware.org/?probe=b290e933bc) | Jul 18, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [03b1e14dfa](https://linux-hardware.org/?probe=03b1e14dfa) | Jul 13, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [9f531c5ee5](https://linux-hardware.org/?probe=9f531c5ee5) | Jul 10, 2024 |
| ASRock        | H61M-DGS                    | [02c4a7193c](https://linux-hardware.org/?probe=02c4a7193c) | Jul 10, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [39a502bca7](https://linux-hardware.org/?probe=39a502bca7) | Jul 02, 2024 |
| ASRock        | H61M-DGS                    | [c4e9309c19](https://linux-hardware.org/?probe=c4e9309c19) | Jun 26, 2024 |
| ASRock        | H61M-DGS                    | [a7a6fdf1ad](https://linux-hardware.org/?probe=a7a6fdf1ad) | Jun 24, 2024 |
| HP            | 0AA8h                       | [bb1f36cf41](https://linux-hardware.org/?probe=bb1f36cf41) | Jun 17, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [2b6170b0aa](https://linux-hardware.org/?probe=2b6170b0aa) | Jun 16, 2024 |
| Dell          | 0478VN A00                  | [3c2b013a6a](https://linux-hardware.org/?probe=3c2b013a6a) | Jun 13, 2024 |
| ASUSTek       | P8Z68-V GEN3                | [0f19c1f26e](https://linux-hardware.org/?probe=0f19c1f26e) | Jun 10, 2024 |
| HP            | 3047h                       | [dfd7376062](https://linux-hardware.org/?probe=dfd7376062) | Jun 07, 2024 |
| ASUSTek       | P8Z68-V GEN3                | [2a4b7aab93](https://linux-hardware.org/?probe=2a4b7aab93) | Jun 07, 2024 |
| HP            | 18E7                        | [ba9c5c09c3](https://linux-hardware.org/?probe=ba9c5c09c3) | May 31, 2024 |
| ASUSTek       | SABERTOOTH P67              | [7c94b2b143](https://linux-hardware.org/?probe=7c94b2b143) | May 25, 2024 |
| Dell          | 0HJ054                      | [8d6c3f640c](https://linux-hardware.org/?probe=8d6c3f640c) | May 22, 2024 |
| Dell          | 0NW6H5 A00                  | [e3518a98e8](https://linux-hardware.org/?probe=e3518a98e8) | May 21, 2024 |
| HP            | 3047h                       | [689ae554d7](https://linux-hardware.org/?probe=689ae554d7) | May 19, 2024 |
| Dell          | 0RCPW3 A03                  | [fc65edcfa7](https://linux-hardware.org/?probe=fc65edcfa7) | May 17, 2024 |
| Dell          | 0G261D A00                  | [614c8593f0](https://linux-hardware.org/?probe=614c8593f0) | May 15, 2024 |
| ASUSTek       | Benicia                     | [b35fe58600](https://linux-hardware.org/?probe=b35fe58600) | May 14, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [7b6f52d80d](https://linux-hardware.org/?probe=7b6f52d80d) | May 10, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [15a3aa2281](https://linux-hardware.org/?probe=15a3aa2281) | May 10, 2024 |
| Fujitsu Si... | D2598-A1 S26361-D2598-A1    | [3ed0f3bd70](https://linux-hardware.org/?probe=3ed0f3bd70) | May 09, 2024 |
| Intel         | H55                         | [83c1ac4239](https://linux-hardware.org/?probe=83c1ac4239) | May 07, 2024 |
| Dell          | 0M5DCD A00                  | [f390e47ea1](https://linux-hardware.org/?probe=f390e47ea1) | May 03, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [257f9cdad4](https://linux-hardware.org/?probe=257f9cdad4) | May 03, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [1a3ebd462f](https://linux-hardware.org/?probe=1a3ebd462f) | May 02, 2024 |
| AOpen         | D1009 A1A4                  | [f5399e68ef](https://linux-hardware.org/?probe=f5399e68ef) | Apr 27, 2024 |
| ASUSTek       | M4A78 PRO                   | [4a79911a5b](https://linux-hardware.org/?probe=4a79911a5b) | Apr 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [12f44c7a5a](https://linux-hardware.org/?probe=12f44c7a5a) | Apr 23, 2024 |
| Lenovo        | 3098 SDK0E50510 WIN         | [6f1ba910cd](https://linux-hardware.org/?probe=6f1ba910cd) | Apr 23, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [b3fc204759](https://linux-hardware.org/?probe=b3fc204759) | Apr 14, 2024 |
| ASUSTek       | P8Z68-V GEN3                | [39d3eeda79](https://linux-hardware.org/?probe=39d3eeda79) | Apr 12, 2024 |
| ASUSTek       | CM6870                      | [0c29f72def](https://linux-hardware.org/?probe=0c29f72def) | Apr 10, 2024 |
| Dell          | 0XCR8D A01                  | [9d38e92df0](https://linux-hardware.org/?probe=9d38e92df0) | Apr 09, 2024 |
| Dell          | 0XCR8D A01                  | [a0b8193ba4](https://linux-hardware.org/?probe=a0b8193ba4) | Apr 09, 2024 |
| Dell          | 0VYXHD A00                  | [c0cfa74664](https://linux-hardware.org/?probe=c0cfa74664) | Apr 09, 2024 |
| MSI           | H81M-E34                    | [62882b5228](https://linux-hardware.org/?probe=62882b5228) | Apr 02, 2024 |
| ASUSTek       | PRIME X570-PRO              | [740eb90402](https://linux-hardware.org/?probe=740eb90402) | Mar 30, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [00e4cbdc6e](https://linux-hardware.org/?probe=00e4cbdc6e) | Mar 29, 2024 |
| ASUSTek       | M5A78L-M LX3                | [a549e35cf7](https://linux-hardware.org/?probe=a549e35cf7) | Mar 26, 2024 |
| HP            | 3029h                       | [1913f87768](https://linux-hardware.org/?probe=1913f87768) | Mar 25, 2024 |
| HP            | 8767 A                      | [167796eedc](https://linux-hardware.org/?probe=167796eedc) | Mar 25, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [f8ca0e66e2](https://linux-hardware.org/?probe=f8ca0e66e2) | Mar 24, 2024 |
| MSI           | H81M-E34                    | [5ab741f203](https://linux-hardware.org/?probe=5ab741f203) | Mar 21, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f7f667d127](https://linux-hardware.org/?probe=f7f667d127) | Mar 21, 2024 |
| Intel         | DQ45CB AAE30148-207         | [779eb3b38f](https://linux-hardware.org/?probe=779eb3b38f) | Mar 20, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9ce06e146a](https://linux-hardware.org/?probe=9ce06e146a) | Mar 19, 2024 |
| Dell          | 0T656F A01                  | [325c5efb6e](https://linux-hardware.org/?probe=325c5efb6e) | Mar 18, 2024 |
| ASUSTek       | PRIME B250M-A               | [6477033da6](https://linux-hardware.org/?probe=6477033da6) | Mar 18, 2024 |
| eMachines     | MCP61PM-GM                  | [c92849e391](https://linux-hardware.org/?probe=c92849e391) | Mar 18, 2024 |
| Dell          | 0M9KCM A02                  | [7823cafa72](https://linux-hardware.org/?probe=7823cafa72) | Mar 15, 2024 |
| Dell          | 0M9KCM A02                  | [6dd5b76d21](https://linux-hardware.org/?probe=6dd5b76d21) | Mar 15, 2024 |
| Supermicro    | C7Q67 V1.01                 | [4fe003a84f](https://linux-hardware.org/?probe=4fe003a84f) | Mar 13, 2024 |
| Foxconn       | 946 7MA Series              | [7453cdde18](https://linux-hardware.org/?probe=7453cdde18) | Mar 09, 2024 |
| Biostar       | G41-M7                      | [54836e3fbe](https://linux-hardware.org/?probe=54836e3fbe) | Mar 08, 2024 |
| ASUSTek       | P8Z77-V PRO                 | [b18d2c6cab](https://linux-hardware.org/?probe=b18d2c6cab) | Mar 08, 2024 |
| ASUSTek       | M5A78L-M LX3                | [445ff9dc64](https://linux-hardware.org/?probe=445ff9dc64) | Feb 28, 2024 |
| ASUSTek       | P8Z77-V LX                  | [4d913de0c0](https://linux-hardware.org/?probe=4d913de0c0) | Feb 21, 2024 |
| ASUSTek       | P8Z77-V LX                  | [bddbc049f7](https://linux-hardware.org/?probe=bddbc049f7) | Feb 21, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [9d5c5dfeb7](https://linux-hardware.org/?probe=9d5c5dfeb7) | Feb 20, 2024 |
| Gigabyte      | H61M-DS2                    | [581dd97a4d](https://linux-hardware.org/?probe=581dd97a4d) | Feb 20, 2024 |
| ASUSTek       | B85M-E                      | [d1bbdc0a03](https://linux-hardware.org/?probe=d1bbdc0a03) | Feb 19, 2024 |
| AZW           | Gemini T45                  | [9a81383d10](https://linux-hardware.org/?probe=9a81383d10) | Feb 19, 2024 |
| Gigabyte      | M720-US3                    | [79c1cffeae](https://linux-hardware.org/?probe=79c1cffeae) | Feb 17, 2024 |
| Gigabyte      | M720-US3                    | [340b590f33](https://linux-hardware.org/?probe=340b590f33) | Feb 17, 2024 |
| ASUSTek       | P8Z77-V LX                  | [2d74906a7d](https://linux-hardware.org/?probe=2d74906a7d) | Feb 16, 2024 |
| ASUSTek       | Rampage II Extreme          | [42f4db38c2](https://linux-hardware.org/?probe=42f4db38c2) | Feb 16, 2024 |
| ASUSTek       | M5A78L-M LX3                | [78b9324e29](https://linux-hardware.org/?probe=78b9324e29) | Feb 16, 2024 |
| Dell          | 0C522T A00                  | [fc865abc9f](https://linux-hardware.org/?probe=fc865abc9f) | Feb 16, 2024 |
| ASRock        | AB350 Pro4                  | [5b8e7f1992](https://linux-hardware.org/?probe=5b8e7f1992) | Feb 14, 2024 |
| Acer          | Acadia V1.34                | [6807342689](https://linux-hardware.org/?probe=6807342689) | Feb 13, 2024 |
| Dell          | 0VYXHD A00                  | [134cac2a6d](https://linux-hardware.org/?probe=134cac2a6d) | Feb 11, 2024 |
| Dell          | 0VYXHD A00                  | [8178dd22d5](https://linux-hardware.org/?probe=8178dd22d5) | Feb 11, 2024 |
| Dell          | 0VRWRC A00                  | [1dfe3721a8](https://linux-hardware.org/?probe=1dfe3721a8) | Feb 09, 2024 |
| ASRock        | B250M-HDV PS                | [b18ea679bb](https://linux-hardware.org/?probe=b18ea679bb) | Feb 08, 2024 |
| MSI           | B450M GAMING PLUS           | [62af32fc16](https://linux-hardware.org/?probe=62af32fc16) | Feb 07, 2024 |
| ASUSTek       | M2N68-AM Plus               | [8800fba01e](https://linux-hardware.org/?probe=8800fba01e) | Feb 06, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [927466a797](https://linux-hardware.org/?probe=927466a797) | Feb 05, 2024 |
| Dell          | 0G214D A00                  | [1a1b425da2](https://linux-hardware.org/?probe=1a1b425da2) | Feb 04, 2024 |
| ASRock        | 4Core1600-D800              | [70cc10cb2c](https://linux-hardware.org/?probe=70cc10cb2c) | Feb 04, 2024 |
| Gigabyte      | GA-990FXA-UD7               | [50c2a07f8a](https://linux-hardware.org/?probe=50c2a07f8a) | Feb 04, 2024 |
| ASRock        | 4Core1600-D800              | [c34e1b1365](https://linux-hardware.org/?probe=c34e1b1365) | Feb 04, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [39712fdfe2](https://linux-hardware.org/?probe=39712fdfe2) | Feb 03, 2024 |
| ASRock        | G31M-S                      | [a596a04111](https://linux-hardware.org/?probe=a596a04111) | Feb 03, 2024 |
| Gigabyte      | GA-990FXA-UD7               | [66768ccdf7](https://linux-hardware.org/?probe=66768ccdf7) | Feb 02, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [3074b7c2a6](https://linux-hardware.org/?probe=3074b7c2a6) | Feb 02, 2024 |
| Gigabyte      | GA-990FXA-UD7               | [4726161c35](https://linux-hardware.org/?probe=4726161c35) | Feb 02, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [62dc25b8b6](https://linux-hardware.org/?probe=62dc25b8b6) | Feb 02, 2024 |
| Unknown       | Unknown                     | [4fa0768f2b](https://linux-hardware.org/?probe=4fa0768f2b) | Feb 01, 2024 |
| Unknown       | Unknown                     | [69b18742b6](https://linux-hardware.org/?probe=69b18742b6) | Feb 01, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [3cedb3c573](https://linux-hardware.org/?probe=3cedb3c573) | Feb 01, 2024 |
| Huanan        | X99-8M-F V1.4               | [7625188b91](https://linux-hardware.org/?probe=7625188b91) | Jan 31, 2024 |
| Gigabyte      | H110M-H-CF                  | [d1065a1aca](https://linux-hardware.org/?probe=d1065a1aca) | Jan 30, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [073f673b78](https://linux-hardware.org/?probe=073f673b78) | Jan 29, 2024 |
| Dell          | 0RY007                      | [151f303198](https://linux-hardware.org/?probe=151f303198) | Jan 29, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [292b1b06ca](https://linux-hardware.org/?probe=292b1b06ca) | Jan 28, 2024 |
| ASRock        | G31M-S                      | [3030db55a6](https://linux-hardware.org/?probe=3030db55a6) | Jan 28, 2024 |
| MSI           | Z490-A PRO                  | [a851d2d2fe](https://linux-hardware.org/?probe=a851d2d2fe) | Jan 28, 2024 |
| Gigabyte      | Z97X-UD5H                   | [fd0ab9a9ac](https://linux-hardware.org/?probe=fd0ab9a9ac) | Jan 28, 2024 |
| Dell          | 0GDG8Y A00                  | [47f8ef1ba6](https://linux-hardware.org/?probe=47f8ef1ba6) | Jan 27, 2024 |
| Dell          | 0Y5DDC A00                  | [1912506274](https://linux-hardware.org/?probe=1912506274) | Jan 26, 2024 |
| ASUSTek       | CM6870                      | [1abc8128a3](https://linux-hardware.org/?probe=1abc8128a3) | Jan 26, 2024 |
| HP            | 3647h                       | [14bc5e74bc](https://linux-hardware.org/?probe=14bc5e74bc) | Jan 26, 2024 |
| Dell          | 048DY8 A01                  | [d5e6914489](https://linux-hardware.org/?probe=d5e6914489) | Jan 26, 2024 |
| Dell          | 0GDG8Y A00                  | [18de9933d4](https://linux-hardware.org/?probe=18de9933d4) | Jan 24, 2024 |
| Alienware     | 07W25T A01                  | [538d2e2b5f](https://linux-hardware.org/?probe=538d2e2b5f) | Jan 24, 2024 |
| Dell          | 0D28YY A00                  | [8d8d8005b1](https://linux-hardware.org/?probe=8d8d8005b1) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | [eed9a3591f](https://linux-hardware.org/?probe=eed9a3591f) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | [8479b771e4](https://linux-hardware.org/?probe=8479b771e4) | Jan 23, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [41a378391c](https://linux-hardware.org/?probe=41a378391c) | Jan 22, 2024 |
| Alienware     | 07W25T A01                  | [2a7a6fd405](https://linux-hardware.org/?probe=2a7a6fd405) | Jan 22, 2024 |
| MSI           | 760GM-P34                   | [3eb4ebb737](https://linux-hardware.org/?probe=3eb4ebb737) | Jan 21, 2024 |
| Foxconn       | 946 7MA Series              | [40261803d6](https://linux-hardware.org/?probe=40261803d6) | Jan 21, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [c3733ef1e3](https://linux-hardware.org/?probe=c3733ef1e3) | Jan 18, 2024 |
| ASUSTek       | PRIME B460M-A               | [518ca600f6](https://linux-hardware.org/?probe=518ca600f6) | Jan 18, 2024 |
| Dell          | 0GTK4K A02                  | [a4aef81553](https://linux-hardware.org/?probe=a4aef81553) | Jan 18, 2024 |
| Intel         | DQ67SW AAG12527-310         | [4c5f54d07e](https://linux-hardware.org/?probe=4c5f54d07e) | Jan 15, 2024 |
| Dell          | OptiPlex 7050               | [f0c2b782ff](https://linux-hardware.org/?probe=f0c2b782ff) | Jan 15, 2024 |
| Intel         | X99-P4 V5.0                 | [574a971f93](https://linux-hardware.org/?probe=574a971f93) | Jan 14, 2024 |
| ASUSTek       | Z170-P                      | [b3d8c3265d](https://linux-hardware.org/?probe=b3d8c3265d) | Jan 14, 2024 |
| Lenovo        | ThinkCentre M70E 0830W36    | [f28fd8d379](https://linux-hardware.org/?probe=f28fd8d379) | Jan 14, 2024 |
| HP            | 3647h                       | [e9767a4e96](https://linux-hardware.org/?probe=e9767a4e96) | Jan 12, 2024 |
| HP            | 3647h                       | [39414040e7](https://linux-hardware.org/?probe=39414040e7) | Jan 12, 2024 |
| Gateway       | SX2851                      | [0cbcae7c27](https://linux-hardware.org/?probe=0cbcae7c27) | Jan 11, 2024 |
| Acer          | Veriton X490G               | [1110362d9a](https://linux-hardware.org/?probe=1110362d9a) | Jan 11, 2024 |
| Dell          | 0T1D10 A01                  | [0c1256487e](https://linux-hardware.org/?probe=0c1256487e) | Jan 11, 2024 |
| Unknown       | Unknown                     | [ca7b5632f4](https://linux-hardware.org/?probe=ca7b5632f4) | Jan 09, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [d5486716d1](https://linux-hardware.org/?probe=d5486716d1) | Jan 09, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [50877161c2](https://linux-hardware.org/?probe=50877161c2) | Jan 08, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [cb7c295dc6](https://linux-hardware.org/?probe=cb7c295dc6) | Jan 08, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [ac3aa9697a](https://linux-hardware.org/?probe=ac3aa9697a) | Jan 07, 2024 |
| Intel         | H61                         | [a0d05acffb](https://linux-hardware.org/?probe=a0d05acffb) | Jan 07, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [8f181c2fb8](https://linux-hardware.org/?probe=8f181c2fb8) | Jan 07, 2024 |
| Biostar       | A320MH                      | [9bec9420ab](https://linux-hardware.org/?probe=9bec9420ab) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | [1f5304b336](https://linux-hardware.org/?probe=1f5304b336) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | [7c7fb3af69](https://linux-hardware.org/?probe=7c7fb3af69) | Jan 06, 2024 |
| ASRock        | G31M-S                      | [1b44835106](https://linux-hardware.org/?probe=1b44835106) | Jan 06, 2024 |
| Dell          | 0HN7XN A01                  | [f154d2ee51](https://linux-hardware.org/?probe=f154d2ee51) | Jan 06, 2024 |
| ASUSTek       | PRIME X399-A                | [5f016cc67b](https://linux-hardware.org/?probe=5f016cc67b) | Jan 05, 2024 |
| Dell          | 0T1D10 A01                  | [36fd42ae37](https://linux-hardware.org/?probe=36fd42ae37) | Jan 05, 2024 |
| Dell          | 0HN7XN A01                  | [91b070152e](https://linux-hardware.org/?probe=91b070152e) | Jan 05, 2024 |
| Lenovo        | ThinkCentre M71e 3156PT5    | [53089d138d](https://linux-hardware.org/?probe=53089d138d) | Jan 03, 2024 |
| Intel         | DQ67SW AAG12527-310         | [64811dfb22](https://linux-hardware.org/?probe=64811dfb22) | Jan 03, 2024 |
| Dell          | 0D28YY A01                  | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| Gigabyte      | Z590 UD AC                  | [0db9ec67ac](https://linux-hardware.org/?probe=0db9ec67ac) | Jan 02, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| ASUSTek       | CM6870                      | [bdc19328ef](https://linux-hardware.org/?probe=bdc19328ef) | Dec 31, 2023 |
| Dell          | 0RW199                      | [62dc9ffa33](https://linux-hardware.org/?probe=62dc9ffa33) | Dec 31, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| ASUSTek       | PRIME X399-A                | [ac506b01e6](https://linux-hardware.org/?probe=ac506b01e6) | Dec 30, 2023 |
| HP            | 82F1                        | [9fc9cb3de0](https://linux-hardware.org/?probe=9fc9cb3de0) | Dec 30, 2023 |
| Dell          | 0VRWRC A00                  | [c58ff5350b](https://linux-hardware.org/?probe=c58ff5350b) | Dec 30, 2023 |
| Pegatron      | 2A9A                        | [92def1bf4a](https://linux-hardware.org/?probe=92def1bf4a) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7dca6779be](https://linux-hardware.org/?probe=7dca6779be) | Dec 29, 2023 |
| ASRock        | B550M-C                     | [ba3fa09385](https://linux-hardware.org/?probe=ba3fa09385) | Dec 29, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [7a34810f0e](https://linux-hardware.org/?probe=7a34810f0e) | Dec 29, 2023 |
| ASUSTek       | PRIME X399-A                | [4d46811257](https://linux-hardware.org/?probe=4d46811257) | Dec 29, 2023 |
| Dell          | 0GDG8Y A00                  | [59c76d34e1](https://linux-hardware.org/?probe=59c76d34e1) | Dec 27, 2023 |
| ASUSTek       | M4A79T Deluxe               | [167d330ef0](https://linux-hardware.org/?probe=167d330ef0) | Dec 27, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [bc9feace53](https://linux-hardware.org/?probe=bc9feace53) | Dec 27, 2023 |
| Pegatron      | 2A9A                        | [e67022179a](https://linux-hardware.org/?probe=e67022179a) | Dec 26, 2023 |
| Dell          | 0GDG8Y A00                  | [52a5621ef8](https://linux-hardware.org/?probe=52a5621ef8) | Dec 25, 2023 |
| Intel         | DH77EB AAG39073-304         | [0cee3977a0](https://linux-hardware.org/?probe=0cee3977a0) | Dec 25, 2023 |
| Dell          | 0MN1TX A04                  | [ba94c75ba0](https://linux-hardware.org/?probe=ba94c75ba0) | Dec 25, 2023 |
| HP            | 2AF7                        | [2fc4d5dd6b](https://linux-hardware.org/?probe=2fc4d5dd6b) | Dec 24, 2023 |
| HP            | 2AF7                        | [baa5012432](https://linux-hardware.org/?probe=baa5012432) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | [2f8f606e9f](https://linux-hardware.org/?probe=2f8f606e9f) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | [6ee70cb266](https://linux-hardware.org/?probe=6ee70cb266) | Dec 24, 2023 |
| ASUSTek       | M2V                         | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| HP            | 1998                        | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| Gigabyte      | B650 GAMING X AX            | [9c0210d1ed](https://linux-hardware.org/?probe=9c0210d1ed) | Dec 22, 2023 |
| Gigabyte      | B450 AORUS M                | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [83183dbb01](https://linux-hardware.org/?probe=83183dbb01) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| Dell          | 0FM586                      | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| HP            | 1998                        | [bc41363911](https://linux-hardware.org/?probe=bc41363911) | Dec 20, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| Dell          | 0FM586                      | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| Gigabyte      | H410M H V3                  | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| Dell          | 0GDG8Y A00                  | [85f532c1c5](https://linux-hardware.org/?probe=85f532c1c5) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| ASUSTek       | Maximus VII HERO            | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Dell          | 0FM586                      | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| MSI           | 2AE0                        | [29c5d75dcf](https://linux-hardware.org/?probe=29c5d75dcf) | Dec 10, 2023 |
| MSI           | 2AE0                        | [63543021ec](https://linux-hardware.org/?probe=63543021ec) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-K               | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [955f530c70](https://linux-hardware.org/?probe=955f530c70) | Dec 08, 2023 |
| MSI           | MS-7309                     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| Gateway       | SX2851                      | [2ec497373d](https://linux-hardware.org/?probe=2ec497373d) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B365M DS3H                  | [0d13c9a0b6](https://linux-hardware.org/?probe=0d13c9a0b6) | Dec 04, 2023 |
| Unknown       | Unknown                     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [6bc5e84b91](https://linux-hardware.org/?probe=6bc5e84b91) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [813edffc94](https://linux-hardware.org/?probe=813edffc94) | Dec 04, 2023 |
| HP            | 3031h                       | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| MSI           | 870A-G54                    | [46f9552be9](https://linux-hardware.org/?probe=46f9552be9) | Dec 03, 2023 |
| Unknown       | Unknown                     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [7d6885561f](https://linux-hardware.org/?probe=7d6885561f) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e106315577](https://linux-hardware.org/?probe=e106315577) | Nov 28, 2023 |
| Acer          | Aspire TC-280               | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| AZW           | Green G3                    | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e4062fc1e4](https://linux-hardware.org/?probe=e4062fc1e4) | Nov 25, 2023 |
| HP            | 82F1                        | [09c7b87413](https://linux-hardware.org/?probe=09c7b87413) | Nov 24, 2023 |
| HP            | 82F1                        | [9ed00910d4](https://linux-hardware.org/?probe=9ed00910d4) | Nov 24, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| HP            | 3029h                       | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| MSI           | Z390-A PRO                  | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| AZW           | MINI S 10                   | [47bd270ae8](https://linux-hardware.org/?probe=47bd270ae8) | Nov 21, 2023 |
| Gigabyte      | H77N-WIFI                   | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | [8047aac511](https://linux-hardware.org/?probe=8047aac511) | Nov 20, 2023 |
| MSI           | Z97-G55 SLI                 | [9137a70965](https://linux-hardware.org/?probe=9137a70965) | Nov 20, 2023 |
| AZW           | MINI S 10                   | [a1358be402](https://linux-hardware.org/?probe=a1358be402) | Nov 20, 2023 |
| Intel         | H61                         | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| Intel         | H61                         | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [cb10d99771](https://linux-hardware.org/?probe=cb10d99771) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [d087235304](https://linux-hardware.org/?probe=d087235304) | Nov 17, 2023 |
| ECS           | H61H2-M2                    | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| JHZD          | BQM5                        | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | Z390 UD                     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Dell          | 0RW199                      | [e3b364ccd6](https://linux-hardware.org/?probe=e3b364ccd6) | Nov 13, 2023 |
| Intel         | H61                         | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [8bcc86ef17](https://linux-hardware.org/?probe=8bcc86ef17) | Nov 12, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | [f5de128dd1](https://linux-hardware.org/?probe=f5de128dd1) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [d46548a5e6](https://linux-hardware.org/?probe=d46548a5e6) | Nov 12, 2023 |
| Dell          | 0HN7XN A01                  | [cd4230cf5b](https://linux-hardware.org/?probe=cd4230cf5b) | Nov 12, 2023 |
| Intel         | H61                         | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| Gigabyte      | H510M H                     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [97e4b3093b](https://linux-hardware.org/?probe=97e4b3093b) | Nov 09, 2023 |
| Dell          | 0RW199                      | [11e414d343](https://linux-hardware.org/?probe=11e414d343) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [abb549b943](https://linux-hardware.org/?probe=abb549b943) | Nov 07, 2023 |
| Dell          | 0KWVT8 A03                  | [864f50cabf](https://linux-hardware.org/?probe=864f50cabf) | Nov 07, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| HP            | 1497                        | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | STI 001359                  | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| HP            | 21F5 0A                     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| HP            | 1998                        | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| MSI           | Boston                      | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| HP            | 2215                        | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| ASUSTek       | SABERTOOTH P67              | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| ASRock        | B450 Pro4                   | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| EPSON DIRE... | AT992E                      | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| ASUSTek       | P7H55-M LX                  | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| AMI           | Intel                       | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Unknown       | Unknown                     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| MSI           | G41M-P33 Combo              | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| Pegatron      | EVANS                       | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Intel         | X99                         | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Dell          | 0RW199                      | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Pegatron      | EVANS                       | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| MSI           | B85M-E45                    | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| Intel         | X79M-S                      | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Acer          | Predator G3610              | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| HP            | 2B35                        | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | 0Y5DDC A00                  | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Dell          | 0HN7XN A01                  | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Dell          | 0F3KHR A00                  | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| Biostar       | H61MLC                      | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| MSI           | B550-A PRO                  | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| MSI           | Z170A-G45 GAMING            | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| ASUSTek       | CG8270                      | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| HP            | 8299                        | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| HP            | 0B54h D                     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Gigabyte      | Z97X-UD5H                   | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | X79M-S                      | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| Intel         | DB85FL AAG89861-201         | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| HP            | 8054                        | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| Intel         | H61                         | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| GuoGuang      | IC2M1028N                   | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| MSI           | Z87 MPOWER MAX              | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| AZW           | MINI S                      | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| HP            | 8299                        | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| Unknown       | Unknown                     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Dell          | 0GY6Y8 A02                  | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| HP            | 3047h                       | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| HP            | 3032h                       | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| Intel         | X79M-S                      | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| Biostar       | H410MH                      | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| MSI           | 2AE0                        | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| HP            | 3032h                       | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Intel         | DZ68BC AAG30742-401         | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| Dell          | 0WMJ54 A01                  | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Pegatron      | IPMMB-MQ1                   | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Unknown       | Unknown                     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | 89B5 A                      | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| ASUSTek       | M4N68T-M LE                 | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | M68MT-S2                    | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| Pegatron      | BOWIE                       | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| MP            | MS-7848                     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Acer          | Elena                       | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Dell          | 088DT1 A01                  | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Dell          | 0MN1TX A04                  | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3048h                       | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| HP            | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | 0C27VV A02                  | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| HP            | 8299                        | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Dell          | 0HN7XN A01                  | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| ASRock        | FP6D4-P1                    | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | 21F5 0A                     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Dell          | 0GY6Y8 A02                  | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Win Elemen... | M9                          | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| ASUSTek       | P5B                         | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-304        | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| AZW           | GTR V02                     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| HP            | 18E5                        | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| ECS           | H510H6-M2                   | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ECS           | H510H6-M2                   | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| HP            | 18E5                        | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Acer          | Revo 70                     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| HP            | 2B02                        | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Gigabyte      | GA-970A-UD3                 | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| HP            | 339A                        | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Unknown       | Unknown                     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| Unknown       | Unknown                     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| MSI           | B75MA-E33                   | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Acer          | Predator G3-605             | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | 0K240Y A02                  | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| HP            | 2B01                        | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| MSI           | B75MA-E33                   | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| HP            | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| HP            | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Pegatron      | 2ACB                        | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| Unknown       | HX90                        | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| MSI           | B75MA-E33                   | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | 2AF7                        | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| HP            | 2129                        | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| Dell          | 0HN7XN A01                  | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| HP            | 2129                        | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | 1850                        | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| MSI           | Z370M MORTAR                | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Alienware     | 0N43JM A00                  | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Unknown       | Unknown                     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| Unknown       | Unknown                     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Gigabyte      | X570 GAMING X               | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 73       | 4.13%   |
| 5.11.0-38-generic | 62       | 3.51%   |
| 5.15.0-67-generic | 58       | 3.28%   |
| 5.15.0-91-generic | 56       | 3.17%   |
| 5.15.0-69-generic | 56       | 3.17%   |
| 5.15.0-46-generic | 56       | 3.17%   |
| 5.11.0-27-generic | 55       | 3.11%   |
| 5.15.0-52-generic | 50       | 2.83%   |
| 5.11.0-40-generic | 50       | 2.83%   |
| 5.13.0-39-generic | 49       | 2.77%   |
| 5.15.0-78-generic | 48       | 2.72%   |
| 5.15.0-60-generic | 46       | 2.6%    |
| 5.15.0-58-generic | 46       | 2.6%    |
| 5.11.0-41-generic | 42       | 2.38%   |
| 5.15.0-71-generic | 41       | 2.32%   |
| 5.15.0-48-generic | 41       | 2.32%   |
| 5.13.0-30-generic | 40       | 2.26%   |
| 5.13.0-40-generic | 38       | 2.15%   |
| 5.15.0-76-generic | 37       | 2.09%   |
| 5.11.0-43-generic | 36       | 2.04%   |
| 5.15.0-41-generic | 35       | 1.98%   |
| 5.11.0-37-generic | 35       | 1.98%   |
| 5.15.0-84-generic | 34       | 1.92%   |
| 5.11.0-34-generic | 32       | 1.81%   |
| 5.13.0-28-generic | 31       | 1.75%   |
| 5.15.0-88-generic | 29       | 1.64%   |
| 5.15.0-53-generic | 29       | 1.64%   |
| 5.15.0-73-generic | 28       | 1.58%   |
| 5.13.0-35-generic | 28       | 1.58%   |
| 5.13.0-27-generic | 27       | 1.53%   |
| 5.15.0-83-generic | 25       | 1.41%   |
| 5.13.0-41-generic | 25       | 1.41%   |
| 5.15.0-89-generic | 24       | 1.36%   |
| 5.15.0-72-generic | 24       | 1.36%   |
| 5.13.0-52-generic | 24       | 1.36%   |
| 5.15.0-87-generic | 21       | 1.19%   |
| 5.13.0-44-generic | 21       | 1.19%   |
| 5.15.0-92-generic | 19       | 1.08%   |
| 5.15.0-79-generic | 19       | 1.08%   |
| 5.15.0-86-generic | 18       | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 881      | 56.77%  |
| 5.11.0  | 332      | 21.39%  |
| 5.13.0  | 294      | 18.94%  |
| 5.8.0   | 25       | 1.61%   |
| 5.4.0   | 2        | 0.13%   |
| 6.5.7   | 1        | 0.06%   |
| 6.3.2   | 1        | 0.06%   |
| 6.3.0   | 1        | 0.06%   |
| 6.2.7   | 1        | 0.06%   |
| 6.2.16  | 1        | 0.06%   |
| 6.10.2  | 1        | 0.06%   |
| 6.1.8   | 1        | 0.06%   |
| 6.1.7   | 1        | 0.06%   |
| 6.0.9   | 1        | 0.06%   |
| 6.0.8   | 1        | 0.06%   |
| 5.19.6  | 1        | 0.06%   |
| 5.19.2  | 1        | 0.06%   |
| 5.19.12 | 1        | 0.06%   |
| 5.17.9  | 1        | 0.06%   |
| 5.17.5  | 1        | 0.06%   |
| 5.17.1  | 1        | 0.06%   |
| 5.15.13 | 1        | 0.06%   |
| 5.14.0  | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 882      | 56.87%  |
| 5.11    | 332      | 21.41%  |
| 5.13    | 294      | 18.96%  |
| 5.8     | 25       | 1.61%   |
| 5.19    | 3        | 0.19%   |
| 5.17    | 3        | 0.19%   |
| 6.3     | 2        | 0.13%   |
| 6.2     | 2        | 0.13%   |
| 6.0     | 2        | 0.13%   |
| 5.4     | 2        | 0.13%   |
| 6.5     | 1        | 0.06%   |
| 6.10    | 1        | 0.06%   |
| 6.1     | 1        | 0.06%   |
| 5.14    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1491     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1270     | 84.67%  |
| XFCE       | 217      | 14.47%  |
| Unknown    | 5        | 0.33%   |
| X-Cinnamon | 3        | 0.2%    |
| KDE5       | 2        | 0.13%   |
| Cinnamon   | 2        | 0.13%   |
| MATE       | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1474     | 98.53%  |
| Wayland | 19       | 1.27%   |
| Tty     | 2        | 0.13%   |
| Unknown | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1247     | 82.42%  |
| GDM3    | 115      | 7.6%    |
| GDM     | 110      | 7.27%   |
| LightDM | 40       | 2.64%   |
| TDM     | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 603      | 40.33%  |
| de_DE       | 148      | 9.9%    |
| en_GB       | 102      | 6.82%   |
| pt_BR       | 97       | 6.49%   |
| fr_FR       | 54       | 3.61%   |
| en_CA       | 49       | 3.28%   |
| it_IT       | 41       | 2.74%   |
| pl_PL       | 33       | 2.21%   |
| es_ES       | 33       | 2.21%   |
| en_IN       | 29       | 1.94%   |
| en_AU       | 28       | 1.87%   |
| nl_NL       | 27       | 1.81%   |
| ru_RU       | 18       | 1.2%    |
| es_AR       | 18       | 1.2%    |
| hu_HU       | 17       | 1.14%   |
| es_MX       | 14       | 0.94%   |
| en_ZA       | 14       | 0.94%   |
| cs_CZ       | 10       | 0.67%   |
| pt_PT       | 9        | 0.6%    |
| nl_BE       | 8        | 0.54%   |
| fr_CA       | 8        | 0.54%   |
| tr_TR       | 6        | 0.4%    |
| sv_SE       | 6        | 0.4%    |
| sk_SK       | 6        | 0.4%    |
| nb_NO       | 6        | 0.4%    |
| fi_FI       | 6        | 0.4%    |
| es_VE       | 6        | 0.4%    |
| es_CL       | 6        | 0.4%    |
| en_NZ       | 6        | 0.4%    |
| el_GR       | 6        | 0.4%    |
| da_DK       | 6        | 0.4%    |
| sr_RS@latin | 5        | 0.33%   |
| ja_JP       | 5        | 0.33%   |
| ar_EG       | 5        | 0.33%   |
| en_PH       | 4        | 0.27%   |
| de_CH       | 4        | 0.27%   |
| zh_CN       | 3        | 0.2%    |
| sr_RS       | 3        | 0.2%    |
| sl_SI       | 3        | 0.2%    |
| fr_BE       | 3        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 809      | 53.68%  |
| EFI  | 698      | 46.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1380     | 91.88%  |
| Tmpfs    | 45       | 3%      |
| Zfs      | 31       | 2.06%   |
| Overlay  | 21       | 1.4%    |
| Btrfs    | 13       | 0.87%   |
| Xfs      | 5        | 0.33%   |
| Ext3     | 3        | 0.2%    |
| Ext2     | 3        | 0.2%    |
| Reiserfs | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1297     | 85.84%  |
| GPT     | 134      | 8.87%   |
| MBR     | 80       | 5.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1445     | 96.59%  |
| Yes       | 51       | 3.41%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1350     | 90%     |
| Yes       | 150      | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 342      | 22.94%  |
| Gigabyte Technology | 227      | 15.22%  |
| Dell                | 165      | 11.07%  |
| MSI                 | 155      | 10.4%   |
| Hewlett-Packard     | 145      | 9.73%   |
| ASRock              | 98       | 6.57%   |
| Lenovo              | 71       | 4.76%   |
| Intel               | 45       | 3.02%   |
| Acer                | 29       | 1.95%   |
| Unknown             | 25       | 1.68%   |
| Biostar             | 23       | 1.54%   |
| Pegatron            | 21       | 1.41%   |
| Fujitsu             | 18       | 1.21%   |
| Foxconn             | 16       | 1.07%   |
| AZW                 | 9        | 0.6%    |
| Alienware           | 6        | 0.4%    |
| Positivo            | 5        | 0.34%   |
| Huanan              | 5        | 0.34%   |
| ECS                 | 5        | 0.34%   |
| Apple               | 5        | 0.34%   |
| OEM                 | 4        | 0.27%   |
| Google              | 4        | 0.27%   |
| BESSTAR Tech        | 4        | 0.27%   |
| Shuttle             | 3        | 0.2%    |
| Medion              | 3        | 0.2%    |
| Gateway             | 3        | 0.2%    |
| Fujitsu Siemens     | 3        | 0.2%    |
| eMachines           | 3        | 0.2%    |
| QIYIDA              | 2        | 0.13%   |
| PCWare              | 2        | 0.13%   |
| Packard Bell        | 2        | 0.13%   |
| MAXSUN              | 2        | 0.13%   |
| MACHINIST           | 2        | 0.13%   |
| LORD ELECTRONICS    | 2        | 0.13%   |
| JGINYUE             | 2        | 0.13%   |
| Wortmann AG         | 1        | 0.07%   |
| WIPRO               | 1        | 0.07%   |
| Win Element         | 1        | 0.07%   |
| Vorke               | 1        | 0.07%   |
| TYAN Computer       | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 33       | 2.21%   |
| Unknown                          | 26       | 1.74%   |
| Dell OptiPlex 7010               | 13       | 0.87%   |
| MSI MS-7817                      | 10       | 0.67%   |
| Dell OptiPlex 790                | 9        | 0.6%    |
| ASUS TUF Gaming X570-PLUS        | 9        | 0.6%    |
| Intel H61                        | 8        | 0.54%   |
| Gigabyte A320M-S2H               | 8        | 0.54%   |
| Dell Precision WorkStation T3500 | 7        | 0.47%   |
| Dell OptiPlex 780                | 7        | 0.47%   |
| Dell OptiPlex 380                | 7        | 0.47%   |
| ASUS M5A78L-M/USB3               | 7        | 0.47%   |
| MSI MS-7C37                      | 6        | 0.4%    |
| MSI MS-7C02                      | 6        | 0.4%    |
| Gigabyte B450 AORUS M            | 6        | 0.4%    |
| Dell OptiPlex 3010               | 6        | 0.4%    |
| ASUS M5A97 R2.0                  | 6        | 0.4%    |
| HP ProDesk 600 G1 SFF            | 5        | 0.34%   |
| HP EliteDesk 800 G1 SFF          | 5        | 0.34%   |
| HP Compaq Pro 6300 SFF           | 5        | 0.34%   |
| Dell OptiPlex 990                | 5        | 0.34%   |
| Dell OptiPlex 7050               | 5        | 0.34%   |
| Dell OptiPlex 360                | 5        | 0.34%   |
| Dell OptiPlex 3020               | 5        | 0.34%   |
| ASUS P8Z77-V LX                  | 5        | 0.34%   |
| ASRock B450 Pro4                 | 5        | 0.34%   |
| MSI MS-7C75                      | 4        | 0.27%   |
| MSI MS-7B89                      | 4        | 0.27%   |
| MSI MS-7B86                      | 4        | 0.27%   |
| Intel X79M-S                     | 4        | 0.27%   |
| Intel H55                        | 4        | 0.27%   |
| HP Compaq Elite 8300 SFF         | 4        | 0.27%   |
| HP Compaq 6005 Pro SFF PC        | 4        | 0.27%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.27%   |
| Gigabyte H110M-H                 | 4        | 0.27%   |
| Gigabyte GA-78LMT-USB3 6.0       | 4        | 0.27%   |
| Gigabyte GA-78LMT-S2             | 4        | 0.27%   |
| Dell OptiPlex 9020               | 4        | 0.27%   |
| Dell OptiPlex 7040               | 4        | 0.27%   |
| Dell OptiPlex 7020               | 4        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 103      | 6.91%   |
| ASUS PRIME             | 52       | 3.49%   |
| Lenovo ThinkCentre     | 50       | 3.35%   |
| HP Compaq              | 42       | 2.82%   |
| ASUS ROG               | 42       | 2.82%   |
| ASUS TUF               | 39       | 2.62%   |
| ASUS All               | 33       | 2.21%   |
| Unknown                | 26       | 1.74%   |
| HP EliteDesk           | 22       | 1.48%   |
| Dell Precision         | 21       | 1.41%   |
| Dell Inspiron          | 15       | 1.01%   |
| Fujitsu ESPRIMO        | 14       | 0.94%   |
| Acer Aspire            | 14       | 0.94%   |
| HP ProDesk             | 13       | 0.87%   |
| Gigabyte B450          | 13       | 0.87%   |
| HP Pavilion            | 12       | 0.8%    |
| ASUS M5A78L-M          | 12       | 0.8%    |
| ASUS M5A97             | 11       | 0.74%   |
| MSI MS-7817            | 10       | 0.67%   |
| Gigabyte X570          | 9        | 0.6%    |
| Gigabyte A320M-S2H     | 9        | 0.6%    |
| Lenovo IdeaCentre      | 8        | 0.54%   |
| Intel H61              | 8        | 0.54%   |
| Gigabyte B450M         | 8        | 0.54%   |
| ASRock B450            | 8        | 0.54%   |
| Gigabyte GA-78LMT-USB3 | 7        | 0.47%   |
| Dell XPS               | 7        | 0.47%   |
| Dell Vostro            | 7        | 0.47%   |
| ASUS P8Z77-V           | 7        | 0.47%   |
| ASUS P8H61-M           | 7        | 0.47%   |
| ASRock B450M           | 7        | 0.47%   |
| MSI MS-7C37            | 6        | 0.4%    |
| MSI MS-7C02            | 6        | 0.4%    |
| Gigabyte B550M         | 6        | 0.4%    |
| ASRock 970             | 5        | 0.34%   |
| Alienware Aurora       | 5        | 0.34%   |
| Acer Veriton           | 5        | 0.34%   |
| MSI MS-7C75            | 4        | 0.27%   |
| MSI MS-7B89            | 4        | 0.27%   |
| MSI MS-7B86            | 4        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 142      | 9.52%   |
| 2012    | 133      | 8.92%   |
| 2011    | 126      | 8.45%   |
| 2018    | 125      | 8.38%   |
| 2014    | 111      | 7.44%   |
| 2019    | 100      | 6.71%   |
| 2020    | 97       | 6.51%   |
| 2010    | 93       | 6.24%   |
| 2021    | 90       | 6.04%   |
| 2017    | 89       | 5.97%   |
| 2009    | 78       | 5.23%   |
| 2008    | 69       | 4.63%   |
| 2016    | 60       | 4.02%   |
| 2015    | 50       | 3.35%   |
| 2022    | 46       | 3.09%   |
| 2007    | 35       | 2.35%   |
| 2023    | 21       | 1.41%   |
| 2006    | 17       | 1.14%   |
| 2005    | 6        | 0.4%    |
| Unknown | 3        | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1491     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1404     | 93.79%  |
| Enabled  | 93       | 6.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1487     | 99.73%  |
| Yes  | 4        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 369      | 24.37%  |
| 8.01-16.0       | 317      | 20.94%  |
| 4.01-8.0        | 253      | 16.71%  |
| 3.01-4.0        | 213      | 14.07%  |
| 32.01-64.0      | 207      | 13.67%  |
| 64.01-256.0     | 60       | 3.96%   |
| 24.01-32.0      | 40       | 2.64%   |
| 1.01-2.0        | 30       | 1.98%   |
| 2.01-3.0        | 21       | 1.39%   |
| 0.51-1.0        | 3        | 0.2%    |
| More than 256.0 | 1        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 588      | 35.64%  |
| 2.01-3.0   | 507      | 30.73%  |
| 4.01-8.0   | 235      | 14.24%  |
| 3.01-4.0   | 234      | 14.18%  |
| 8.01-16.0  | 44       | 2.67%   |
| 0.51-1.0   | 27       | 1.64%   |
| 16.01-24.0 | 10       | 0.61%   |
| 32.01-64.0 | 2        | 0.12%   |
| 24.01-32.0 | 2        | 0.12%   |
| 0.01-0.5   | 1        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 683      | 44.47%  |
| 2      | 435      | 28.32%  |
| 3      | 187      | 12.17%  |
| 4      | 113      | 7.36%   |
| 5      | 57       | 3.71%   |
| 6      | 33       | 2.15%   |
| 7      | 11       | 0.72%   |
| 8      | 8        | 0.52%   |
| 0      | 6        | 0.39%   |
| 51     | 1        | 0.07%   |
| 11     | 1        | 0.07%   |
| 9      | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 763      | 50.83%  |
| Yes       | 738      | 49.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1474     | 98.86%  |
| No        | 17       | 1.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 772      | 51.26%  |
| No        | 734      | 48.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 991      | 65.8%   |
| Yes       | 515      | 34.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 389      | 26%     |
| Germany      | 157      | 10.49%  |
| Brazil       | 105      | 7.02%   |
| UK           | 98       | 6.55%   |
| Canada       | 62       | 4.14%   |
| Italy        | 50       | 3.34%   |
| France       | 50       | 3.34%   |
| Netherlands  | 42       | 2.81%   |
| Poland       | 38       | 2.54%   |
| Spain        | 34       | 2.27%   |
| India        | 30       | 2.01%   |
| Australia    | 29       | 1.94%   |
| Argentina    | 21       | 1.4%    |
| Hungary      | 20       | 1.34%   |
| Belgium      | 19       | 1.27%   |
| Mexico       | 18       | 1.2%    |
| Denmark      | 16       | 1.07%   |
| Russia       | 15       | 1%      |
| South Africa | 14       | 0.94%   |
| Serbia       | 14       | 0.94%   |
| Portugal     | 14       | 0.94%   |
| Sweden       | 13       | 0.87%   |
| Greece       | 13       | 0.87%   |
| Czechia      | 13       | 0.87%   |
| Norway       | 12       | 0.8%    |
| Egypt        | 11       | 0.74%   |
| Turkey       | 10       | 0.67%   |
| Switzerland  | 10       | 0.67%   |
| Finland      | 9        | 0.6%    |
| Chile        | 9        | 0.6%    |
| Slovakia     | 8        | 0.53%   |
| Malaysia     | 8        | 0.53%   |
| Venezuela    | 7        | 0.47%   |
| Romania      | 7        | 0.47%   |
| New Zealand  | 7        | 0.47%   |
| Slovenia     | 6        | 0.4%    |
| Japan        | 6        | 0.4%    |
| Indonesia    | 6        | 0.4%    |
| Bulgaria     | 5        | 0.33%   |
| Philippines  | 4        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 13       | 0.83%   |
| Rio de Janeiro | 12       | 0.76%   |
| Munich         | 10       | 0.64%   |
| Houston        | 9        | 0.57%   |
| Milan          | 8        | 0.51%   |
| Cape Town      | 8        | 0.51%   |
| Athens         | 8        | 0.51%   |
| Sao Paulo      | 7        | 0.45%   |
| Copenhagen     | 7        | 0.45%   |
| Sydney         | 6        | 0.38%   |
| Rome           | 6        | 0.38%   |
| Phoenix        | 6        | 0.38%   |
| Montreal       | 6        | 0.38%   |
| Hamburg        | 6        | 0.38%   |
| Denver         | 6        | 0.38%   |
| Calgary        | 6        | 0.38%   |
| Atlanta        | 6        | 0.38%   |
| Portland       | 5        | 0.32%   |
| Perth          | 5        | 0.32%   |
| Lisbon         | 5        | 0.32%   |
| Dallas         | 5        | 0.32%   |
| Buenos Aires   | 5        | 0.32%   |
| Budapest       | 5        | 0.32%   |
| Adelaide       | 5        | 0.32%   |
| Wylie          | 4        | 0.25%   |
| The Hague      | 4        | 0.25%   |
| Santiago       | 4        | 0.25%   |
| San José      | 4        | 0.25%   |
| Salt Lake City | 4        | 0.25%   |
| Richmond       | 4        | 0.25%   |
| Prague         | 4        | 0.25%   |
| Minneapolis    | 4        | 0.25%   |
| Melbourne      | 4        | 0.25%   |
| Krakow         | 4        | 0.25%   |
| Johannesburg   | 4        | 0.25%   |
| Dayton         | 4        | 0.25%   |
| Cincinnati     | 4        | 0.25%   |
| Brussels       | 4        | 0.25%   |
| Brasília      | 4        | 0.25%   |
| Bolton         | 4        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 500      | 801    | 18.85%  |
| WDC                         | 443      | 671    | 16.7%   |
| Samsung Electronics         | 339      | 534    | 12.78%  |
| Kingston                    | 171      | 250    | 6.45%   |
| Toshiba                     | 142      | 215    | 5.35%   |
| Sandisk                     | 139      | 195    | 5.24%   |
| Crucial                     | 107      | 130    | 4.03%   |
| Hitachi                     | 104      | 131    | 3.92%   |
| China                       | 45       | 53     | 1.7%    |
| A-DATA Technology           | 36       | 50     | 1.36%   |
| Unknown                     | 31       | 60     | 1.17%   |
| Silicon Motion              | 28       | 38     | 1.06%   |
| Intel                       | 27       | 32     | 1.02%   |
| Intenso                     | 22       | 25     | 0.83%   |
| PNY                         | 21       | 30     | 0.79%   |
| HGST                        | 21       | 30     | 0.79%   |
| SK hynix                    | 20       | 25     | 0.75%   |
| Phison                      | 20       | 22     | 0.75%   |
| Micron/Crucial Technology   | 18       | 24     | 0.68%   |
| Patriot                     | 15       | 21     | 0.57%   |
| SPCC                        | 14       | 22     | 0.53%   |
| Maxtor                      | 14       | 18     | 0.53%   |
| GOODRAM                     | 14       | 18     | 0.53%   |
| Micron Technology           | 13       | 13     | 0.49%   |
| Phison Electronics          | 12       | 15     | 0.45%   |
| MAXIO Technology (Hangzhou) | 12       | 12     | 0.45%   |
| Lexar                       | 12       | 13     | 0.45%   |
| JMicron Technology          | 12       | 14     | 0.45%   |
| Unknown                     | 12       | 13     | 0.45%   |
| OCZ                         | 11       | 13     | 0.41%   |
| KingSpec                    | 11       | 14     | 0.41%   |
| Realtek Semiconductor       | 10       | 10     | 0.38%   |
| Netac                       | 10       | 15     | 0.38%   |
| Hewlett-Packard             | 10       | 14     | 0.38%   |
| Gigabyte Technology         | 10       | 13     | 0.38%   |
| Apple                       | 9        | 10     | 0.34%   |
| Apacer                      | 9        | 12     | 0.34%   |
| Kingston Technology Company | 8        | 11     | 0.3%    |
| XPG                         | 7        | 8      | 0.26%   |
| Team                        | 7        | 9      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 49       | 1.6%    |
| Kingston SA400S37240G 240GB SSD                       | 44       | 1.44%   |
| Seagate ST1000DM010-2EP102 1TB                        | 31       | 1.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 28       | 0.92%   |
| Samsung SSD 860 EVO 500GB                             | 27       | 0.88%   |
| Crucial CT240BX500SSD1 240GB                          | 26       | 0.85%   |
| Seagate ST1000DM003-1CH162 1TB                        | 23       | 0.75%   |
| Samsung SSD 850 EVO 250GB                             | 22       | 0.72%   |
| Kingston SA400S37120G 120GB SSD                       | 22       | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 21       | 0.69%   |
| Toshiba HDWD110 1TB                                   | 20       | 0.66%   |
| Kingston SA400S37480G 480GB SSD                       | 19       | 0.62%   |
| Samsung NVMe SSD Drive 1TB                            | 17       | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB                        | 16       | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB                        | 16       | 0.52%   |
| Toshiba DT01ACA100 1TB                                | 15       | 0.49%   |
| Seagate ST3500418AS 500GB                             | 15       | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                        | 14       | 0.46%   |
| Samsung NVMe SSD Drive 500GB                          | 14       | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 14       | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                      | 14       | 0.46%   |
| Unknown SD/MMC/MS PRO 128GB                           | 13       | 0.43%   |
| Toshiba DT01ACA050 500GB                              | 13       | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB                        | 13       | 0.43%   |
| Seagate ST3500413AS 500GB                             | 13       | 0.43%   |
| Seagate ST3500312CS 500GB                             | 13       | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                           | 13       | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB                        | 12       | 0.39%   |
| SanDisk NVMe SSD Drive 500GB                          | 12       | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                            | 12       | 0.39%   |
| Samsung SSD 870 EVO 1TB                               | 12       | 0.39%   |
| Samsung SSD 850 EVO 500GB                             | 12       | 0.39%   |
| Crucial CT500MX500SSD1 500GB                          | 12       | 0.39%   |
| Unknown                                               | 12       | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 11       | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB                        | 11       | 0.36%   |
| Samsung SSD 870 EVO 500GB                             | 11       | 0.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 11       | 0.36%   |
| Toshiba DT01ACA200 2TB                                | 10       | 0.33%   |
| Seagate ST31000528AS 1TB                              | 10       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 493      | 775    | 38.4%   |
| WDC                 | 403      | 596    | 31.39%  |
| Toshiba             | 124      | 194    | 9.66%   |
| Hitachi             | 104      | 131    | 8.1%    |
| Samsung Electronics | 73       | 94     | 5.69%   |
| HGST                | 21       | 30     | 1.64%   |
| Unknown             | 14       | 19     | 1.09%   |
| Maxtor              | 14       | 18     | 1.09%   |
| JMicron Technology  | 9        | 10     | 0.7%    |
| Apple               | 6        | 7      | 0.47%   |
| SABRENT             | 5        | 6      | 0.39%   |
| Hewlett-Packard     | 4        | 7      | 0.31%   |
| USB3.0              | 2        | 3      | 0.16%   |
| Fujitsu             | 2        | 3      | 0.16%   |
| WD MediaMax         | 1        | 1      | 0.08%   |
| Unknown (CF)        | 1        | 1      | 0.08%   |
| TDAS                | 1        | 3      | 0.08%   |
| QUANTUM             | 1        | 1      | 0.08%   |
| Intenso             | 1        | 1      | 0.08%   |
| IBM/Hitachi         | 1        | 1      | 0.08%   |
| HGST HTS            | 1        | 1      | 0.08%   |
| External            | 1        | 1      | 0.08%   |
| ASMT                | 1        | 1      | 0.08%   |
| ACASIS              | 1        | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 180      | 266    | 19.11%  |
| Kingston            | 139      | 190    | 14.76%  |
| Crucial             | 102      | 125    | 10.83%  |
| SanDisk             | 81       | 111    | 8.6%    |
| WDC                 | 49       | 65     | 5.2%    |
| China               | 45       | 53     | 4.78%   |
| A-DATA Technology   | 34       | 48     | 3.61%   |
| PNY                 | 21       | 30     | 2.23%   |
| Intel               | 17       | 19     | 1.8%    |
| Intenso             | 16       | 19     | 1.7%    |
| SPCC                | 14       | 22     | 1.49%   |
| Patriot             | 14       | 20     | 1.49%   |
| GOODRAM             | 13       | 17     | 1.38%   |
| Lexar               | 12       | 13     | 1.27%   |
| Toshiba             | 11       | 13     | 1.17%   |
| OCZ                 | 11       | 13     | 1.17%   |
| Netac               | 10       | 14     | 1.06%   |
| KingSpec            | 10       | 13     | 1.06%   |
| Apacer              | 9        | 12     | 0.96%   |
| SK hynix            | 8        | 8      | 0.85%   |
| Micron Technology   | 8        | 8      | 0.85%   |
| Gigabyte Technology | 8        | 10     | 0.85%   |
| Team                | 7        | 9      | 0.74%   |
| Transcend           | 6        | 9      | 0.64%   |
| Hewlett-Packard     | 6        | 7      | 0.64%   |
| Leven               | 5        | 6      | 0.53%   |
| Unknown             | 5        | 6      | 0.53%   |
| Super Talent        | 4        | 5      | 0.42%   |
| Seagate             | 4        | 8      | 0.42%   |
| KIOXIA-EXCERIA      | 4        | 8      | 0.42%   |
| Fanxiang            | 4        | 5      | 0.42%   |
| Verbatim            | 3        | 3      | 0.32%   |
| LITEON              | 3        | 3      | 0.32%   |
| Corsair             | 3        | 8      | 0.32%   |
| Acer                | 3        | 5      | 0.32%   |
| XrayDisk            | 2        | 4      | 0.21%   |
| Teclast             | 2        | 2      | 0.21%   |
| Plextor             | 2        | 3      | 0.21%   |
| Pioneer             | 2        | 2      | 0.21%   |
| ORTIAL              | 2        | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 989      | 1905   | 44.45%  |
| SSD     | 792      | 1270   | 35.6%   |
| NVMe    | 367      | 567    | 16.49%  |
| Unknown | 70       | 96     | 3.15%   |
| MMC     | 7        | 9      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1372     | 3092   | 73.76%  |
| NVMe | 365      | 563    | 19.62%  |
| SAS  | 116      | 183    | 6.24%   |
| MMC  | 7        | 9      | 0.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1025     | 1755   | 53.55%  |
| 0.51-1.0   | 525      | 826    | 27.43%  |
| 1.01-2.0   | 210      | 311    | 10.97%  |
| 3.01-4.0   | 70       | 143    | 3.66%   |
| 4.01-10.0  | 41       | 61     | 2.14%   |
| 2.01-3.0   | 35       | 51     | 1.83%   |
| 10.01-20.0 | 7        | 26     | 0.37%   |
| 20.01-50.0 | 1        | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 461      | 29.25%  |
| 251-500        | 362      | 22.97%  |
| 501-1000       | 258      | 16.37%  |
| 1001-2000      | 157      | 9.96%   |
| More than 3000 | 119      | 7.55%   |
| 51-100         | 84       | 5.33%   |
| 2001-3000      | 49       | 3.11%   |
| 21-50          | 34       | 2.16%   |
| 1-20           | 33       | 2.09%   |
| Unknown        | 19       | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 516      | 31.27%  |
| 21-50          | 428      | 25.94%  |
| 51-100         | 207      | 12.55%  |
| 101-250        | 168      | 10.18%  |
| 251-500        | 112      | 6.79%   |
| 501-1000       | 83       | 5.03%   |
| More than 3000 | 55       | 3.33%   |
| 1001-2000      | 44       | 2.67%   |
| Unknown        | 19       | 1.15%   |
| 2001-3000      | 18       | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB                 | 2        | 2      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB          | 2        | 2      | 3.85%   |
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 3.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1      | 1.92%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 1.92%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 1.92%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 1.92%   |
| WDC WD20EZRX-22D8PB0 2TB                 | 1        | 1      | 1.92%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 1.92%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 1.92%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 1.92%   |
| WDC WD Green 2.5 1000GB SSD              | 1        | 1      | 1.92%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 1.92%   |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 1.92%   |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 1.92%   |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 1.92%   |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 1.92%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 1.92%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 1.92%   |
| Seagate ST9500420AS 500GB                | 1        | 1      | 1.92%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 1.92%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 1.92%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 1.92%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 1.92%   |
| Seagate ST3500312CS 500GB                | 1        | 1      | 1.92%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 1.92%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 1.92%   |
| Seagate ST3250318AS 250GB                | 1        | 1      | 1.92%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 1.92%   |
| Seagate ST320LT009-9WC142 320GB          | 1        | 1      | 1.92%   |
| Seagate ST3160310CS 160GB                | 1        | 1      | 1.92%   |
| Seagate ST2000LM007-1R8174 2TB           | 1        | 1      | 1.92%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 1.92%   |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 1.92%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 1.92%   |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 1.92%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 1.92%   |
| Samsung Electronics HD161HJ 160GB        | 1        | 1      | 1.92%   |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 1.92%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 37.25%  |
| WDC                 | 11       | 12     | 21.57%  |
| Toshiba             | 6        | 6      | 11.76%  |
| HGST                | 3        | 3      | 5.88%   |
| Samsung Electronics | 2        | 2      | 3.92%   |
| Kingston            | 2        | 2      | 3.92%   |
| A-DATA Technology   | 2        | 2      | 3.92%   |
| Silicon Motion      | 1        | 1      | 1.96%   |
| OCZ                 | 1        | 1      | 1.96%   |
| Maxtor              | 1        | 1      | 1.96%   |
| Intel               | 1        | 1      | 1.96%   |
| Fanxiang            | 1        | 2      | 1.96%   |
| China               | 1        | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 48.72%  |
| WDC                 | 9        | 10     | 23.08%  |
| Toshiba             | 5        | 5      | 12.82%  |
| HGST                | 3        | 3      | 7.69%   |
| Samsung Electronics | 2        | 2      | 5.13%   |
| Maxtor              | 1        | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 41     | 74.47%  |
| SSD  | 10       | 11     | 21.28%  |
| NVMe | 2        | 2      | 4.26%   |

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
| Detected | 1379     | 3472   | 88.74%  |
| Works    | 129      | 321    | 8.3%    |
| Malfunc  | 46       | 54     | 2.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 981      | 48.09%  |
| AMD                            | 461      | 22.6%   |
| Samsung Electronics            | 119      | 5.83%   |
| SanDisk                        | 68       | 3.33%   |
| ASMedia Technology             | 59       | 2.89%   |
| Kingston Technology Company    | 46       | 2.25%   |
| JMicron Technology             | 42       | 2.06%   |
| Nvidia                         | 35       | 1.72%   |
| Phison Electronics             | 34       | 1.67%   |
| Marvell Technology Group       | 32       | 1.57%   |
| Silicon Motion                 | 31       | 1.52%   |
| Micron/Crucial Technology      | 23       | 1.13%   |
| MAXIO Technology (Hangzhou)    | 13       | 0.64%   |
| ADATA Technology               | 12       | 0.59%   |
| SK hynix                       | 11       | 0.54%   |
| Realtek Semiconductor          | 10       | 0.49%   |
| VIA Technologies               | 8        | 0.39%   |
| Silicon Image                  | 8        | 0.39%   |
| Seagate Technology             | 8        | 0.39%   |
| KIOXIA                         | 8        | 0.39%   |
| Toshiba America Info Systems   | 6        | 0.29%   |
| Micron Technology              | 5        | 0.25%   |
| Shenzhen Longsys Electronics   | 4        | 0.2%    |
| INNOGRIT                       | 3        | 0.15%   |
| Broadcom / LSI                 | 3        | 0.15%   |
| TenaFe                         | 1        | 0.05%   |
| Solid State Storage Technology | 1        | 0.05%   |
| OCZ Technology Group           | 1        | 0.05%   |
| Nextorage                      | 1        | 0.05%   |
| Netac Technology               | 1        | 0.05%   |
| Lite-On Technology             | 1        | 0.05%   |
| Integrated Technology Express  | 1        | 0.05%   |
| HighPoint Technologies         | 1        | 0.05%   |
| Beijing Starblaze Technology   | 1        | 0.05%   |
| Apple                          | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 238      | 9.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 150      | 5.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 96       | 3.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 88       | 3.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 87       | 3.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 83       | 3.23%   |
| Intel SATA Controller [RAID mode]                                                       | 75       | 2.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 72       | 2.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 70       | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 64       | 2.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 57       | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 57       | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 53       | 2.06%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 53       | 2.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 49       | 1.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 48       | 1.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 37       | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 36       | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 35       | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 34       | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 30       | 1.17%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 27       | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 25       | 0.97%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 25       | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 23       | 0.89%   |
| Nvidia MCP61 SATA Controller                                                            | 21       | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                                  | 21       | 0.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 19       | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 18       | 0.7%    |
| Phison E12 NVMe Controller                                                              | 18       | 0.7%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 17       | 0.66%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 17       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 17       | 0.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 16       | 0.62%   |
| Nvidia MCP61 IDE                                                                        | 16       | 0.62%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 16       | 0.62%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 16       | 0.62%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 15       | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 15       | 0.58%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 15       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1178     | 57.18%  |
| IDE  | 390      | 18.93%  |
| NVMe | 364      | 17.67%  |
| RAID | 119      | 5.78%   |
| SAS  | 6        | 0.29%   |
| SCSI | 3        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 996      | 66.8%   |
| AMD    | 495      | 33.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 29       | 1.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 26       | 1.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 24       | 1.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 24       | 1.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 17       | 1.13%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 17       | 1.13%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 16       | 1.07%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 16       | 1.07%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 16       | 1.07%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 15       | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor         | 15       | 1%      |
| Intel Core i7-6700 CPU @ 3.40GHz            | 14       | 0.93%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 14       | 0.93%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 14       | 0.93%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 14       | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 13       | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 13       | 0.87%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 13       | 0.87%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 13       | 0.87%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 13       | 0.87%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11       | 0.73%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11       | 0.73%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 11       | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 10       | 0.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.67%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 9        | 0.6%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 9        | 0.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 9        | 0.6%    |
| Intel Core i5-4690K CPU @ 3.50GHz           | 8        | 0.53%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 8        | 0.53%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 8        | 0.53%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 8        | 0.53%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 8        | 0.53%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 8        | 0.53%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 8        | 0.53%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 0.53%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 0.53%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 0.53%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 7        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 294      | 19.67%  |
| Intel Core i7           | 172      | 11.51%  |
| Intel Core i3           | 134      | 8.96%   |
| AMD Ryzen 5             | 124      | 8.29%   |
| Intel Xeon              | 83       | 5.55%   |
| AMD Ryzen 7             | 61       | 4.08%   |
| AMD FX                  | 59       | 3.95%   |
| Other                   | 53       | 3.55%   |
| Intel Core 2 Duo        | 52       | 3.48%   |
| AMD Ryzen 9             | 47       | 3.14%   |
| Intel Celeron           | 40       | 2.68%   |
| Intel Core 2 Quad       | 37       | 2.47%   |
| Intel Pentium Dual-Core | 33       | 2.21%   |
| Intel Pentium           | 31       | 2.07%   |
| AMD Ryzen 3             | 26       | 1.74%   |
| AMD Athlon II X2        | 26       | 1.74%   |
| Intel Pentium Dual      | 22       | 1.47%   |
| AMD Phenom II X4        | 20       | 1.34%   |
| AMD A10                 | 16       | 1.07%   |
| AMD A8                  | 15       | 1%      |
| Intel Core i9           | 14       | 0.94%   |
| AMD A6                  | 14       | 0.94%   |
| AMD Athlon 64 X2        | 12       | 0.8%    |
| AMD Phenom II X6        | 11       | 0.74%   |
| Intel Core 2            | 9        | 0.6%    |
| Intel Atom              | 9        | 0.6%    |
| AMD Athlon              | 8        | 0.54%   |
| Intel Pentium 4         | 7        | 0.47%   |
| AMD Athlon II X4        | 7        | 0.47%   |
| Intel Pentium Gold      | 5        | 0.33%   |
| AMD Athlon II X3        | 5        | 0.33%   |
| AMD A4                  | 5        | 0.33%   |
| AMD Phenom              | 4        | 0.27%   |
| AMD E1                  | 4        | 0.27%   |
| Intel Pentium D         | 3        | 0.2%    |
| AMD Sempron             | 3        | 0.2%    |
| AMD Ryzen 5 PRO         | 3        | 0.2%    |
| AMD PRO A10             | 3        | 0.2%    |
| AMD GX                  | 3        | 0.2%    |
| AMD Ryzen Threadripper  | 2        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 615      | 41.11%  |
| 2      | 427      | 28.54%  |
| 6      | 198      | 13.24%  |
| 8      | 121      | 8.09%   |
| 12     | 38       | 2.54%   |
| 1      | 30       | 2.01%   |
| 16     | 23       | 1.54%   |
| 3      | 23       | 1.54%   |
| 10     | 14       | 0.94%   |
| 24     | 3        | 0.2%    |
| 28     | 2        | 0.13%   |
| 14     | 2        | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1481     | 99.33%  |
| 2      | 10       | 0.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 795      | 53.21%  |
| 1      | 699      | 46.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1491     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 171      | 11.28%  |
| Unknown    | 125      | 8.25%   |
| 0x306a9    | 114      | 7.52%   |
| 0x206a7    | 104      | 6.86%   |
| 0x1067a    | 91       | 6%      |
| 0x506e3    | 59       | 3.89%   |
| 0x08701021 | 51       | 3.36%   |
| 0x06000852 | 41       | 2.7%    |
| 0x906e9    | 32       | 2.11%   |
| 0x906ea    | 31       | 2.04%   |
| 0x0800820d | 29       | 1.91%   |
| 0x010000c8 | 28       | 1.85%   |
| 0x6fd      | 27       | 1.78%   |
| 0xa0655    | 25       | 1.65%   |
| 0xa0653    | 24       | 1.58%   |
| 0x0a201016 | 20       | 1.32%   |
| 0x08108109 | 20       | 1.32%   |
| 0x06001119 | 18       | 1.19%   |
| 0x0600063e | 16       | 1.06%   |
| 0xa0671    | 15       | 0.99%   |
| 0x6fb      | 15       | 0.99%   |
| 0x20655    | 15       | 0.99%   |
| 0x08001138 | 15       | 0.99%   |
| 0x906ed    | 14       | 0.92%   |
| 0x906eb    | 13       | 0.86%   |
| 0x010000dc | 13       | 0.86%   |
| 0x010000db | 13       | 0.86%   |
| 0x106a5    | 12       | 0.79%   |
| 0x10676    | 12       | 0.79%   |
| 0x0a50000d | 12       | 0.79%   |
| 0x306f2    | 11       | 0.73%   |
| 0x306e4    | 11       | 0.73%   |
| 0x206d7    | 11       | 0.73%   |
| 0x106e5    | 11       | 0.73%   |
| 0x08701013 | 11       | 0.73%   |
| 0x90672    | 10       | 0.66%   |
| 0x20652    | 10       | 0.66%   |
| 0x06003106 | 10       | 0.66%   |
| 0x0a601203 | 9        | 0.59%   |
| 0x0a20120a | 9        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 199      | 13.33%  |
| IvyBridge        | 128      | 8.57%   |
| SandyBridge      | 119      | 7.97%   |
| Penryn           | 109      | 7.3%    |
| KabyLake         | 104      | 6.97%   |
| Zen 2            | 82       | 5.49%   |
| K10              | 76       | 5.09%   |
| Zen 3            | 72       | 4.82%   |
| Skylake          | 62       | 4.15%   |
| Piledriver       | 62       | 4.15%   |
| Core             | 57       | 3.82%   |
| Zen+             | 53       | 3.55%   |
| CometLake        | 52       | 3.48%   |
| Zen              | 46       | 3.08%   |
| Unknown          | 42       | 2.81%   |
| Westmere         | 33       | 2.21%   |
| Nehalem          | 29       | 1.94%   |
| K8 Hammer        | 18       | 1.21%   |
| Bulldozer        | 17       | 1.14%   |
| Icelake          | 16       | 1.07%   |
| Excavator        | 15       | 1%      |
| Alderlake Hybrid | 14       | 0.94%   |
| Silvermont       | 13       | 0.87%   |
| Steamroller      | 11       | 0.74%   |
| NetBurst         | 11       | 0.74%   |
| Broadwell        | 8        | 0.54%   |
| Puma             | 7        | 0.47%   |
| Jaguar           | 7        | 0.47%   |
| Bonnell          | 7        | 0.47%   |
| K10 Llano        | 6        | 0.4%    |
| Goldmont plus    | 5        | 0.33%   |
| Bobcat           | 5        | 0.33%   |
| Tremont          | 4        | 0.27%   |
| Goldmont         | 3        | 0.2%    |
| TigerLake        | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 585      | 36.59%  |
| Intel                      | 520      | 32.52%  |
| AMD                        | 489      | 30.58%  |
| VIA Technologies           | 2        | 0.13%   |
| Matrox Electronics Systems | 1        | 0.06%   |
| ATI Technologies           | 1        | 0.06%   |
| ASPEED Technology          | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 95       | 5.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 61       | 3.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 56       | 3.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 51       | 3.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 40       | 2.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 38       | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 33       | 2.02%   |
| Intel HD Graphics 530                                                       | 30       | 1.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 27       | 1.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 26       | 1.59%   |
| Intel HD Graphics 630                                                       | 22       | 1.35%   |
| Nvidia GK208B [GeForce GT 730]                                              | 21       | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 21       | 1.29%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 20       | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                         | 20       | 1.23%   |
| Nvidia GF119 [GeForce GT 610]                                               | 18       | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 18       | 1.1%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 18       | 1.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 1.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 17       | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 16       | 0.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 15       | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                  | 15       | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15       | 0.92%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 15       | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 0.92%   |
| AMD RS780L [Radeon 3000]                                                    | 15       | 0.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 13       | 0.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 13       | 0.8%    |
| Nvidia GF108 [GeForce GT 730]                                               | 12       | 0.74%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 12       | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 11       | 0.67%   |
| Nvidia GF108 [GeForce GT 630]                                               | 11       | 0.67%   |
| AMD Raphael                                                                 | 11       | 0.67%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 11       | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 0.61%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 0.55%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 9        | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 0.49%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 8        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 541      | 35.85%  |
| 1 x Intel            | 456      | 30.22%  |
| 1 x AMD              | 447      | 29.62%  |
| Intel + Nvidia       | 16       | 1.06%   |
| 2 x AMD              | 15       | 0.99%   |
| AMD + Nvidia         | 15       | 0.99%   |
| Intel + AMD          | 11       | 0.73%   |
| 2 x Nvidia           | 3        | 0.2%    |
| 1 x VIA              | 2        | 0.13%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.07%   |
| 1 x Matrox           | 1        | 0.07%   |
| 1 x ASPEED           | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1044     | 69.18%  |
| Proprietary | 368      | 24.39%  |
| Unknown     | 97       | 6.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 664      | 43.57%  |
| 1.01-2.0   | 188      | 12.34%  |
| 0.51-1.0   | 182      | 11.94%  |
| 0.01-0.5   | 152      | 9.97%   |
| 3.01-4.0   | 124      | 8.14%   |
| 7.01-8.0   | 112      | 7.35%   |
| 8.01-16.0  | 41       | 2.69%   |
| 5.01-6.0   | 37       | 2.43%   |
| 2.01-3.0   | 19       | 1.25%   |
| 16.01-24.0 | 4        | 0.26%   |
| 4.01-5.0   | 1        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 233      | 15.84%  |
| Dell                 | 144      | 9.79%   |
| Goldstar             | 135      | 9.18%   |
| Hewlett-Packard      | 113      | 7.68%   |
| Acer                 | 101      | 6.87%   |
| AOC                  | 84       | 5.71%   |
| Philips              | 75       | 5.1%    |
| Ancor Communications | 53       | 3.6%    |
| BenQ                 | 51       | 3.47%   |
| LG Electronics       | 30       | 2.04%   |
| ViewSonic            | 28       | 1.9%    |
| Unknown              | 27       | 1.84%   |
| Lenovo               | 26       | 1.77%   |
| Unknown              | 24       | 1.63%   |
| Sony                 | 20       | 1.36%   |
| Sceptre Tech         | 16       | 1.09%   |
| Iiyama               | 16       | 1.09%   |
| ASUSTek Computer     | 16       | 1.09%   |
| Fujitsu Siemens      | 14       | 0.95%   |
| NEC Computers        | 13       | 0.88%   |
| Vizio                | 10       | 0.68%   |
| HPN                  | 10       | 0.68%   |
| Eizo                 | 10       | 0.68%   |
| Toshiba              | 9        | 0.61%   |
| MSI                  | 8        | 0.54%   |
| FUS                  | 8        | 0.54%   |
| Panasonic            | 6        | 0.41%   |
| Microstep            | 6        | 0.41%   |
| Idek Iiyama          | 6        | 0.41%   |
| AUS                  | 6        | 0.41%   |
| Vestel               | 5        | 0.34%   |
| Pixio                | 5        | 0.34%   |
| Medion               | 5        | 0.34%   |
| Gigabyte Technology  | 5        | 0.34%   |
| Unknown (XXX)        | 4        | 0.27%   |
| RTK                  | 4        | 0.27%   |
| Lenovo Group Limited | 4        | 0.27%   |
| ITE                  | 4        | 0.27%   |
| HannStar             | 4        | 0.27%   |
| Envision             | 4        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 24       | 1.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 10       | 0.64%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                | 9        | 0.58%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 7        | 0.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 6        | 0.38%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                 | 5        | 0.32%   |
| Philips LCD Monitor FTV 1920x1080                                       | 5        | 0.32%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 5        | 0.32%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1210x680mm 54.6-inch          | 4        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 4        | 0.26%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 4        | 0.26%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                        | 4        | 0.26%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch               | 4        | 0.26%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 4        | 0.26%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 4        | 0.26%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 3        | 0.19%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch   | 3        | 0.19%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 3        | 0.19%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 3        | 0.19%   |
| Unknown LCD Monitor SAMSUNG                                             | 3        | 0.19%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch                | 3        | 0.19%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 3        | 0.19%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch       | 3        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 3        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch   | 3        | 0.19%   |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch                 | 3        | 0.19%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 3        | 0.19%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 3        | 0.19%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch            | 3        | 0.19%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 3        | 0.19%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 3        | 0.19%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                      | 3        | 0.19%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                       | 3        | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 3        | 0.19%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                       | 3        | 0.19%   |
| Dell LCD Monitor E228WFP                                                | 3        | 0.19%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                       | 3        | 0.19%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                       | 3        | 0.19%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                       | 3        | 0.19%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 3        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 610      | 41.9%   |
| 3840x2160 (4K)     | 131      | 9%      |
| 1280x1024 (SXGA)   | 86       | 5.91%   |
| 1680x1050 (WSXGA+) | 81       | 5.56%   |
| 2560x1440 (QHD)    | 71       | 4.88%   |
| 1600x900 (HD+)     | 67       | 4.6%    |
| Unknown            | 63       | 4.33%   |
| 1366x768 (WXGA)    | 59       | 4.05%   |
| 1440x900 (WXGA+)   | 55       | 3.78%   |
| 1920x1200 (WUXGA)  | 33       | 2.27%   |
| 1360x768           | 33       | 2.27%   |
| 3440x1440          | 32       | 2.2%    |
| 3840x1080          | 31       | 2.13%   |
| 2560x1080          | 17       | 1.17%   |
| 1920x540           | 12       | 0.82%   |
| 1024x768 (XGA)     | 11       | 0.76%   |
| 1600x1200          | 8        | 0.55%   |
| 3840x1600          | 4        | 0.27%   |
| 1280x720 (HD)      | 4        | 0.27%   |
| 4480x1440          | 3        | 0.21%   |
| 2560x1600          | 3        | 0.21%   |
| 5760x2160          | 2        | 0.14%   |
| 5760x1080          | 2        | 0.14%   |
| 5120x1440          | 2        | 0.14%   |
| 4480x1080          | 2        | 0.14%   |
| 3600x1080          | 2        | 0.14%   |
| 3360x1080          | 2        | 0.14%   |
| 3200x1200          | 2        | 0.14%   |
| 3120x1050          | 2        | 0.14%   |
| 2944x1080          | 2        | 0.14%   |
| 1280x960           | 2        | 0.14%   |
| 7680x2160          | 1        | 0.07%   |
| 6880x1440          | 1        | 0.07%   |
| 6400x1440          | 1        | 0.07%   |
| 5440x1080          | 1        | 0.07%   |
| 5040x1050          | 1        | 0.07%   |
| 4480x1600          | 1        | 0.07%   |
| 4160x1440          | 1        | 0.07%   |
| 3780x2160          | 1        | 0.07%   |
| 3440x2138          | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 274      | 19.03%  |
| 24      | 152      | 10.56%  |
| 27      | 144      | 10%     |
| 21      | 126      | 8.75%   |
| 23      | 123      | 8.54%   |
| 19      | 94       | 6.53%   |
| 20      | 75       | 5.21%   |
| 31      | 74       | 5.14%   |
| 22      | 56       | 3.89%   |
| 18      | 55       | 3.82%   |
| 17      | 41       | 2.85%   |
| 34      | 33       | 2.29%   |
| 40      | 22       | 1.53%   |
| 15      | 22       | 1.53%   |
| 84      | 17       | 1.18%   |
| 32      | 15       | 1.04%   |
| 72      | 14       | 0.97%   |
| 54      | 14       | 0.97%   |
| 26      | 9        | 0.63%   |
| 25      | 7        | 0.49%   |
| 65      | 5        | 0.35%   |
| 52      | 5        | 0.35%   |
| 49      | 5        | 0.35%   |
| 28      | 5        | 0.35%   |
| 48      | 4        | 0.28%   |
| 46      | 4        | 0.28%   |
| 36      | 4        | 0.28%   |
| 29      | 4        | 0.28%   |
| 64      | 3        | 0.21%   |
| 43      | 3        | 0.21%   |
| 35      | 3        | 0.21%   |
| 33      | 3        | 0.21%   |
| 74      | 2        | 0.14%   |
| 60      | 2        | 0.14%   |
| 58      | 2        | 0.14%   |
| 57      | 2        | 0.14%   |
| 42      | 2        | 0.14%   |
| 41      | 2        | 0.14%   |
| 37      | 2        | 0.14%   |
| 142     | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 386      | 27.73%  |
| 401-500        | 348      | 25%     |
| Unknown        | 274      | 19.68%  |
| 601-700        | 102      | 7.33%   |
| 301-350        | 62       | 4.45%   |
| 701-800        | 55       | 3.95%   |
| 1001-1500      | 48       | 3.45%   |
| 351-400        | 44       | 3.16%   |
| 1501-2000      | 36       | 2.59%   |
| 801-900        | 28       | 2.01%   |
| 901-1000       | 7        | 0.5%    |
| More than 2000 | 1        | 0.07%   |
| 201-300        | 1        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 767      | 57.11%  |
| Unknown | 252      | 18.76%  |
| 16/10   | 167      | 12.43%  |
| 5/4     | 76       | 5.66%   |
| 21/9    | 42       | 3.13%   |
| 4/3     | 23       | 1.71%   |
| 32/9    | 9        | 0.67%   |
| 6/5     | 5        | 0.37%   |
| 3/2     | 1        | 0.07%   |
| 1.00    | 1        | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 367      | 25.92%  |
| Unknown        | 274      | 19.35%  |
| 151-200        | 210      | 14.83%  |
| 301-350        | 147      | 10.38%  |
| 351-500        | 133      | 9.39%   |
| 141-150        | 79       | 5.58%   |
| More than 1000 | 74       | 5.23%   |
| 251-300        | 60       | 4.24%   |
| 501-1000       | 46       | 3.25%   |
| 101-110        | 17       | 1.2%    |
| 111-120        | 4        | 0.28%   |
| 81-90          | 1        | 0.07%   |
| 71-80          | 1        | 0.07%   |
| 131-140        | 1        | 0.07%   |
| 121-130        | 1        | 0.07%   |
| 91-100         | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 770      | 56.99%  |
| Unknown | 274      | 20.28%  |
| 101-120 | 186      | 13.77%  |
| 1-50    | 68       | 5.03%   |
| 121-160 | 37       | 2.74%   |
| 161-240 | 16       | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1203     | 78.94%  |
| 2     | 201      | 13.19%  |
| 0     | 99       | 6.5%    |
| 3     | 19       | 1.25%   |
| 4     | 2        | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 945      | 42.7%   |
| Intel                             | 608      | 27.47%  |
| Qualcomm Atheros                  | 139      | 6.28%   |
| Broadcom                          | 78       | 3.52%   |
| Ralink Technology                 | 74       | 3.34%   |
| TP-Link                           | 61       | 2.76%   |
| Nvidia                            | 30       | 1.36%   |
| MediaTek                          | 30       | 1.36%   |
| Ralink                            | 29       | 1.31%   |
| NetGear                           | 18       | 0.81%   |
| Samsung Electronics               | 17       | 0.77%   |
| Marvell Technology Group          | 13       | 0.59%   |
| Broadcom Limited                  | 13       | 0.59%   |
| Microsoft                         | 12       | 0.54%   |
| D-Link                            | 12       | 0.54%   |
| Qualcomm Atheros Communications   | 11       | 0.5%    |
| Xiaomi                            | 10       | 0.45%   |
| D-Link System                     | 10       | 0.45%   |
| ASIX Electronics                  | 10       | 0.45%   |
| Huawei Technologies               | 8        | 0.36%   |
| Edimax Technology                 | 7        | 0.32%   |
| ASUSTek Computer                  | 7        | 0.32%   |
| Aquantia                          | 7        | 0.32%   |
| OPPO Electronics                  | 4        | 0.18%   |
| Motorola PCS                      | 4        | 0.18%   |
| Linksys                           | 4        | 0.18%   |
| DisplayLink                       | 4        | 0.18%   |
| Belkin Components                 | 4        | 0.18%   |
| ZyDAS                             | 2        | 0.09%   |
| VIA Technologies                  | 2        | 0.09%   |
| Sundance Technology Inc / IC Plus | 2        | 0.09%   |
| QinHeng Electronics               | 2        | 0.09%   |
| Motorola                          | 2        | 0.09%   |
| Gemtek                            | 2        | 0.09%   |
| AVM                               | 2        | 0.09%   |
| Arduino SA                        | 2        | 0.09%   |
| ZyXEL Communications              | 1        | 0.05%   |
| U-Blox                            | 1        | 0.05%   |
| TRENDnet                          | 1        | 0.05%   |
| T & A Mobile Phones               | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 703      | 28%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 83       | 3.31%   |
| Realtek RTL8125 2.5GbE Controller                                      | 74       | 2.95%   |
| Intel Wi-Fi 6 AX200                                                    | 60       | 2.39%   |
| Intel I211 Gigabit Network Connection                                  | 60       | 2.39%   |
| Intel Ethernet Connection I217-LM                                      | 58       | 2.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 55       | 2.19%   |
| Intel Ethernet Connection (2) I219-V                                   | 43       | 1.71%   |
| Realtek 802.11ac NIC                                                   | 37       | 1.47%   |
| Intel Ethernet Controller I225-V                                       | 37       | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 36       | 1.43%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 33       | 1.31%   |
| Ralink MT7601U Wireless Adapter                                        | 32       | 1.27%   |
| Intel Ethernet Connection I217-V                                       | 25       | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 25       | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 23       | 0.92%   |
| Intel Wireless 7265                                                    | 21       | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 20       | 0.8%    |
| Nvidia MCP61 Ethernet                                                  | 20       | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 19       | 0.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 17       | 0.68%   |
| Intel 82579V Gigabit Network Connection                                | 17       | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 16       | 0.64%   |
| Ralink RT5370 Wireless Adapter                                         | 16       | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 15       | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 14       | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 14       | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14       | 0.56%   |
| Intel Ethernet Connection (2) I218-V                                   | 14       | 0.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 14       | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13       | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 13       | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 12       | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 11       | 0.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 11       | 0.44%   |
| Intel Wireless 7260                                                    | 11       | 0.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 10       | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 10       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 235      | 27.42%  |
| Intel                                 | 232      | 27.07%  |
| Ralink Technology                     | 74       | 8.63%   |
| Qualcomm Atheros                      | 70       | 8.17%   |
| TP-Link                               | 59       | 6.88%   |
| Broadcom                              | 33       | 3.85%   |
| Ralink                                | 29       | 3.38%   |
| MediaTek                              | 23       | 2.68%   |
| NetGear                               | 18       | 2.1%    |
| Microsoft                             | 12       | 1.4%    |
| D-Link                                | 12       | 1.4%    |
| Qualcomm Atheros Communications       | 11       | 1.28%   |
| D-Link System                         | 8        | 0.93%   |
| Edimax Technology                     | 7        | 0.82%   |
| ASUSTek Computer                      | 6        | 0.7%    |
| Broadcom Limited                      | 5        | 0.58%   |
| Linksys                               | 4        | 0.47%   |
| Belkin Components                     | 4        | 0.47%   |
| ZyDAS                                 | 2        | 0.23%   |
| Gemtek                                | 2        | 0.23%   |
| AVM                                   | 2        | 0.23%   |
| ZyXEL Communications                  | 1        | 0.12%   |
| Xiaomi                                | 1        | 0.12%   |
| TRENDnet                              | 1        | 0.12%   |
| Sitecom Europe                        | 1        | 0.12%   |
| Panasonic (Matsushita)                | 1        | 0.12%   |
| Ovislink                              | 1        | 0.12%   |
| Marvell Technology Group              | 1        | 0.12%   |
| ADMtek                                | 1        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 60       | 6.89%   |
| Realtek 802.11ac NIC                                           | 37       | 4.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 36       | 4.13%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 33       | 3.79%   |
| Ralink MT7601U Wireless Adapter                                | 32       | 3.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 25       | 2.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 23       | 2.64%   |
| Intel Wireless 7265                                            | 21       | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20       | 2.3%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 17       | 1.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 16       | 1.84%   |
| Ralink RT5370 Wireless Adapter                                 | 16       | 1.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 14       | 1.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 14       | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14       | 1.61%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 14       | 1.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 12       | 1.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 11       | 1.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.26%   |
| Intel Wireless 7260                                            | 11       | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 10       | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10       | 1.15%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 9        | 1.03%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 9        | 1.03%   |
| Intel Wireless 3165                                            | 9        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9        | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 9        | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8        | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                | 8        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7        | 0.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7        | 0.8%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 7        | 0.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.69%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 6        | 0.69%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 6        | 0.69%   |
| Microsoft Xbox 360 Wireless Adapter                            | 6        | 0.69%   |
| MediaTek WiFi                                                  | 6        | 0.69%   |
| TP-Link Archer T4U ver.3                                       | 5        | 0.57%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 5        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 858      | 54.17%  |
| Intel                             | 474      | 29.92%  |
| Qualcomm Atheros                  | 73       | 4.61%   |
| Broadcom                          | 46       | 2.9%    |
| Nvidia                            | 30       | 1.89%   |
| Samsung Electronics               | 13       | 0.82%   |
| Marvell Technology Group          | 12       | 0.76%   |
| ASIX Electronics                  | 10       | 0.63%   |
| Xiaomi                            | 9        | 0.57%   |
| Broadcom Limited                  | 8        | 0.51%   |
| MediaTek                          | 7        | 0.44%   |
| Huawei Technologies               | 7        | 0.44%   |
| Aquantia                          | 7        | 0.44%   |
| OPPO Electronics                  | 4        | 0.25%   |
| Motorola PCS                      | 4        | 0.25%   |
| DisplayLink                       | 4        | 0.25%   |
| VIA Technologies                  | 2        | 0.13%   |
| TP-Link                           | 2        | 0.13%   |
| Sundance Technology Inc / IC Plus | 2        | 0.13%   |
| D-Link System                     | 2        | 0.13%   |
| Research In Motion                | 1        | 0.06%   |
| Qualcomm                          | 1        | 0.06%   |
| JMicron Technology                | 1        | 0.06%   |
| ICS Advent                        | 1        | 0.06%   |
| HMD Global                        | 1        | 0.06%   |
| Google                            | 1        | 0.06%   |
| ASUSTek Computer                  | 1        | 0.06%   |
| Apple                             | 1        | 0.06%   |
| Accton Technology                 | 1        | 0.06%   |
| 3Com                              | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 703      | 43.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 83       | 5.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 74       | 4.58%   |
| Intel I211 Gigabit Network Connection                                  | 60       | 3.71%   |
| Intel Ethernet Connection I217-LM                                      | 58       | 3.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 55       | 3.4%    |
| Intel Ethernet Connection (2) I219-V                                   | 43       | 2.66%   |
| Intel Ethernet Controller I225-V                                       | 37       | 2.29%   |
| Intel Ethernet Connection I217-V                                       | 25       | 1.55%   |
| Nvidia MCP61 Ethernet                                                  | 20       | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 19       | 1.18%   |
| Intel 82579V Gigabit Network Connection                                | 17       | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15       | 0.93%   |
| Intel Ethernet Connection (2) I218-V                                   | 14       | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13       | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13       | 0.8%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 13       | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 10       | 0.62%   |
| Intel 82574L Gigabit Network Connection                                | 10       | 0.62%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 10       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 9        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9        | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8        | 0.5%    |
| Intel Ethernet Connection (12) I219-V                                  | 8        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7        | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                  | 7        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 7        | 0.43%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 6        | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 6        | 0.37%   |
| Intel Ethernet Controller I226-V                                       | 6        | 0.37%   |
| Intel Ethernet Connection (14) I219-V                                  | 6        | 0.37%   |
| Intel 82578DM Gigabit Network Connection                               | 6        | 0.37%   |
| Intel 82578DC Gigabit Network Connection                               | 6        | 0.37%   |
| Huawei FOA-LX9                                                         | 6        | 0.37%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 6        | 0.37%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 5        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1474     | 64.93%  |
| WiFi     | 774      | 34.1%   |
| Modem    | 19       | 0.84%   |
| Unknown  | 3        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1110     | 70.66%  |
| WiFi     | 457      | 29.09%  |
| Modem    | 2        | 0.13%   |
| Unknown  | 2        | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 964      | 64.1%   |
| 2     | 467      | 31.05%  |
| 3     | 52       | 3.46%   |
| 0     | 15       | 1%      |
| 4     | 3        | 0.2%    |
| 5     | 2        | 0.13%   |
| 7     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 994      | 65.52%  |
| Yes  | 523      | 34.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 195      | 37%     |
| Cambridge Silicon Radio         | 105      | 19.92%  |
| Realtek Semiconductor           | 73       | 13.85%  |
| Broadcom                        | 30       | 5.69%   |
| ASUSTek Computer                | 24       | 4.55%   |
| Qualcomm Atheros Communications | 19       | 3.61%   |
| IMC Networks                    | 14       | 2.66%   |
| MediaTek                        | 12       | 2.28%   |
| TP-Link                         | 8        | 1.52%   |
| Apple                           | 8        | 1.52%   |
| Dynex                           | 5        | 0.95%   |
| Foxconn / Hon Hai               | 4        | 0.76%   |
| Unknown                         | 4        | 0.76%   |
| Realtek                         | 3        | 0.57%   |
| Lite-On Technology              | 3        | 0.57%   |
| Integrated System Solution      | 3        | 0.57%   |
| Belkin Components               | 3        | 0.57%   |
| Actions                         | 3        | 0.57%   |
| Edimax Technology               | 2        | 0.38%   |
| Dell                            | 2        | 0.38%   |
| Sitecom Europe                  | 1        | 0.19%   |
| Ralink                          | 1        | 0.19%   |
| National Semiconductor          | 1        | 0.19%   |
| Micro Star International        | 1        | 0.19%   |
| Marvell Semiconductor           | 1        | 0.19%   |
| Logitech                        | 1        | 0.19%   |
| D-Link System                   | 1        | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 105      | 19.92%  |
| Realtek Bluetooth Radio                                  | 62       | 11.76%  |
| Intel AX200 Bluetooth                                    | 46       | 8.73%   |
| Intel Bluetooth wireless interface                       | 44       | 8.35%   |
| Intel AX210 Bluetooth                                    | 29       | 5.5%    |
| Intel Wireless-AC 3168 Bluetooth                         | 24       | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 18       | 3.42%   |
| Intel AX201 Bluetooth                                    | 13       | 2.47%   |
| MediaTek Wireless_Device                                 | 12       | 2.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 12       | 2.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 11       | 2.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 11       | 2.09%   |
| IMC Networks Bluetooth Radio                             | 9        | 1.71%   |
| TP-Link TP-Link Bluetooth USB Adapter                    | 8        | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                           | 7        | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 5        | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5        | 0.95%   |
| Intel AX211 Bluetooth                                    | 5        | 0.95%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 5        | 0.95%   |
| Apple Bluetooth Host Controller                          | 5        | 0.95%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 0.76%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 4        | 0.76%   |
| ASUS Bluetooth Radio                                     | 4        | 0.76%   |
| ASUS ASUS USB-BT500                                      | 4        | 0.76%   |
| Unknown                                                  | 4        | 0.76%   |
| Realtek RTL8821A Bluetooth                               | 3        | 0.57%   |
| Realtek Bluetooth Radio                                  | 3        | 0.57%   |
| Lite-On Bluetooth Device                                 | 3        | 0.57%   |
| IMC Networks Wireless_Device                             | 3        | 0.57%   |
| Foxconn / Hon Hai Wireless_Device                        | 3        | 0.57%   |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.57%   |
| Broadcom Bluetooth 2.0+EDR dongle                        | 3        | 0.57%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 3        | 0.57%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.57%   |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.57%   |
| Actions general adapter                                  | 3        | 0.57%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.38%   |
| Integrated System Solution Bluetooth Device              | 2        | 0.38%   |
| Edimax Bluetooth Adapter                                 | 2        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 970      | 38.99%  |
| AMD                                          | 640      | 25.72%  |
| Nvidia                                       | 550      | 22.11%  |
| C-Media Electronics                          | 59       | 2.37%   |
| Creative Labs                                | 27       | 1.09%   |
| Logitech                                     | 18       | 0.72%   |
| JMTek                                        | 17       | 0.68%   |
| ASUSTek Computer                             | 16       | 0.64%   |
| Kingston Technology                          | 15       | 0.6%    |
| Generalplus Technology                       | 12       | 0.48%   |
| Texas Instruments                            | 9        | 0.36%   |
| VIA Technologies                             | 8        | 0.32%   |
| Razer USA                                    | 8        | 0.32%   |
| Plantronics                                  | 8        | 0.32%   |
| Micro Star International                     | 7        | 0.28%   |
| Creative Technology                          | 7        | 0.28%   |
| KTMicro                                      | 6        | 0.24%   |
| GN Netcom                                    | 6        | 0.24%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.2%    |
| Tenx Technology                              | 5        | 0.2%    |
| Realtek Semiconductor                        | 5        | 0.2%    |
| Jieli Technology                             | 5        | 0.2%    |
| Focusrite-Novation                           | 4        | 0.16%   |
| SteelSeries ApS                              | 3        | 0.12%   |
| RODE Microphones                             | 3        | 0.12%   |
| Astro Gaming                                 | 3        | 0.12%   |
| Asahi Kasei Microsystems                     | 3        | 0.12%   |
| Yamaha                                       | 2        | 0.08%   |
| Sony                                         | 2        | 0.08%   |
| Samsung Electronics                          | 2        | 0.08%   |
| Microsoft                                    | 2        | 0.08%   |
| Lenovo                                       | 2        | 0.08%   |
| DSEA A/S                                     | 2        | 0.08%   |
| Corsair                                      | 2        | 0.08%   |
| Cambridge Audio                              | 2        | 0.08%   |
| Blue Microphones                             | 2        | 0.08%   |
| BEHRINGER International                      | 2        | 0.08%   |
| Audio-Technica                               | 2        | 0.08%   |
| ZOOM                                         | 1        | 0.04%   |
| XMOS                                         | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 160      | 5.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 138      | 4.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 124      | 4.27%   |
| AMD Starship/Matisse HD Audio Controller                                          | 122      | 4.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 111      | 3.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 92       | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 90       | 3.1%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 84       | 2.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 66       | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 60       | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 59       | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 55       | 1.89%   |
| Intel 200 Series PCH HD Audio                                                     | 54       | 1.86%   |
| AMD FCH Azalia Controller                                                         | 52       | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                        | 44       | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 42       | 1.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 37       | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 37       | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 35       | 1.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 35       | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                     | 34       | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 33       | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 33       | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                                     | 32       | 1.1%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 31       | 1.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 30       | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 28       | 0.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 28       | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                                | 27       | 0.93%   |
| Nvidia High Definition Audio Controller                                           | 25       | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                                     | 24       | 0.83%   |
| AMD Navi 10 HDMI Audio                                                            | 24       | 0.83%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 23       | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 23       | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                                     | 22       | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                     | 21       | 0.72%   |
| Nvidia MCP61 High Definition Audio                                                | 21       | 0.72%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 21       | 0.72%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 21       | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                                     | 20       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 36       | 16.07%  |
| Kingston            | 30       | 13.39%  |
| Samsung Electronics | 27       | 12.05%  |
| Corsair             | 23       | 10.27%  |
| G.Skill             | 20       | 8.93%   |
| SK hynix            | 18       | 8.04%   |
| Crucial             | 17       | 7.59%   |
| Team                | 11       | 4.91%   |
| Micron Technology   | 9        | 4.02%   |
| Unknown             | 5        | 2.23%   |
| Nanya Technology    | 3        | 1.34%   |
| A-DATA Technology   | 3        | 1.34%   |
| Wilk                | 2        | 0.89%   |
| Unifosa             | 2        | 0.89%   |
| Ramaxel Technology  | 2        | 0.89%   |
| Patriot             | 2        | 0.89%   |
| Avant               | 2        | 0.89%   |
| V-GEN               | 1        | 0.45%   |
| Transcend           | 1        | 0.45%   |
| Timetec             | 1        | 0.45%   |
| SUPER KINGSTEK      | 1        | 0.45%   |
| Qimonda             | 1        | 0.45%   |
| Patriot Memory      | 1        | 0.45%   |
| Goldkey             | 1        | 0.45%   |
| Golden Empire       | 1        | 0.45%   |
| F7852C80            | 1        | 0.45%   |
| Elpida              | 1        | 0.45%   |
| Apacer              | 1        | 0.45%   |
| AMD                 | 1        | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 6        | 2.44%   |
| Unknown                                                 | 5        | 2.03%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s     | 3        | 1.22%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 3        | 1.22%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.22%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 3        | 1.22%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 1.22%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.81%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.81%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 0.81%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 2        | 0.81%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s      | 2        | 0.81%   |
| Team RAM TEAMGROUP-UD4-2666 4GB DIMM DDR4               | 2        | 0.81%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s      | 2        | 0.81%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.81%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 0.81%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 0.81%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s     | 2        | 0.81%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 2        | 0.81%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s          | 2        | 0.81%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 2        | 0.81%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 0.81%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 2        | 0.81%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.81%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s     | 2        | 0.81%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 2        | 0.81%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3600MT/s   | 2        | 0.81%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 2        | 0.81%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2        | 0.81%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s   | 2        | 0.81%   |
| Wilk RAM IRX3200D464L16A/16G 16GB DIMM DDR4 3200MT/s    | 1        | 0.41%   |
| Wilk RAM GX3236D464S/8GSBS1 8192MB DIMM DDR4 3467MT/s   | 1        | 0.41%   |
| V-GEN RAM D4H8GL26A8TS6 8192MB DIMM DDR4 2400MT/s       | 1        | 0.41%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM SDRAM                       | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s               | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 86       | 43.43%  |
| DDR3    | 73       | 36.87%  |
| Unknown | 11       | 5.56%   |
| SDRAM   | 9        | 4.55%   |
| DDR2    | 8        | 4.04%   |
| DDR5    | 5        | 2.53%   |
| DDR     | 3        | 1.52%   |
| LPDDR4  | 2        | 1.01%   |
| DRAM    | 1        | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 181      | 93.3%   |
| SODIMM       | 10       | 5.15%   |
| Row Of Chips | 2        | 1.03%   |
| FB-DIMM      | 1        | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 89       | 41.01%  |
| 4096  | 56       | 25.81%  |
| 2048  | 25       | 11.52%  |
| 16384 | 23       | 10.6%   |
| 32768 | 16       | 7.37%   |
| 1024  | 7        | 3.23%   |
| 512   | 1        | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 39       | 17.97%  |
| 1333    | 27       | 12.44%  |
| 3200    | 22       | 10.14%  |
| 3600    | 16       | 7.37%   |
| 2133    | 11       | 5.07%   |
| 2667    | 9        | 4.15%   |
| 2400    | 8        | 3.69%   |
| 3000    | 7        | 3.23%   |
| 3733    | 6        | 2.76%   |
| 1866    | 6        | 2.76%   |
| 1800    | 6        | 2.76%   |
| 800     | 6        | 2.76%   |
| Unknown | 5        | 2.3%    |
| 4800    | 3        | 1.38%   |
| 4000    | 3        | 1.38%   |
| 3800    | 3        | 1.38%   |
| 2666    | 3        | 1.38%   |
| 1867    | 3        | 1.38%   |
| 667     | 3        | 1.38%   |
| 3666    | 2        | 0.92%   |
| 3500    | 2        | 0.92%   |
| 3467    | 2        | 0.92%   |
| 3466    | 2        | 0.92%   |
| 3400    | 2        | 0.92%   |
| 1066    | 2        | 0.92%   |
| 400     | 2        | 0.92%   |
| 6000    | 1        | 0.46%   |
| 5354    | 1        | 0.46%   |
| 5200    | 1        | 0.46%   |
| 4266    | 1        | 0.46%   |
| 3933    | 1        | 0.46%   |
| 3866    | 1        | 0.46%   |
| 3534    | 1        | 0.46%   |
| 2933    | 1        | 0.46%   |
| 2800    | 1        | 0.46%   |
| 2733    | 1        | 0.46%   |
| 2465    | 1        | 0.46%   |
| 2200    | 1        | 0.46%   |
| 2000    | 1        | 0.46%   |
| 1400    | 1        | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 24       | 27.59%  |
| Brother Industries    | 17       | 19.54%  |
| Canon                 | 16       | 18.39%  |
| Seiko Epson           | 11       | 12.64%  |
| Samsung Electronics   | 11       | 12.64%  |
| Lexmark International | 2        | 2.3%    |
| Konica Minolta        | 2        | 2.3%    |
| Ricoh                 | 1        | 1.15%   |
| QinHeng Electronics   | 1        | 1.15%   |
| Oki Data              | 1        | 1.15%   |
| GG IMAGE              | 1        | 1.15%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson L3110 Series                     | 2        | 2.3%    |
| Samsung M2070 Series                         | 2        | 2.3%    |
| Samsung C460 Series                          | 2        | 2.3%    |
| HP OfficeJet 6950                            | 2        | 2.3%    |
| HP LaserJet Professional P1102w              | 2        | 2.3%    |
| HP ENVY 4520 series                          | 2        | 2.3%    |
| HP DeskJet 2700 series                       | 2        | 2.3%    |
| HP DeskJet 2130 series                       | 2        | 2.3%    |
| Canon PIXMA MG3600 Series                    | 2        | 2.3%    |
| Canon LiDE 400                               | 2        | 2.3%    |
| Seiko Epson XP-7100 Series                   | 1        | 1.15%   |
| Seiko Epson XP-205 207 Series                | 1        | 1.15%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.15%   |
| Seiko Epson L805 Series                      | 1        | 1.15%   |
| Seiko Epson L6270 Series                     | 1        | 1.15%   |
| Seiko Epson L355 Series                      | 1        | 1.15%   |
| Seiko Epson L3150 Series                     | 1        | 1.15%   |
| Seiko Epson ET-2820 Series                   | 1        | 1.15%   |
| Seiko Epson ET-2800 Series                   | 1        | 1.15%   |
| Samsung SCX-483x 5x3x Series                 | 1        | 1.15%   |
| Samsung SCX-4623 Series                      | 1        | 1.15%   |
| Samsung SCX-4200 series                      | 1        | 1.15%   |
| Samsung SCX-3400 Series                      | 1        | 1.15%   |
| Samsung ML-2950 Series                       | 1        | 1.15%   |
| Samsung ML-216x Series Laser Printer         | 1        | 1.15%   |
| Samsung M2020 Series                         | 1        | 1.15%   |
| Ricoh SP 111SU                               | 1        | 1.15%   |
| QinHeng CH340S                               | 1        | 1.15%   |
| Oki Data USB Device                          | 1        | 1.15%   |
| Lexmark International MX310dn                | 1        | 1.15%   |
| Lexmark International Laser Printer E232     | 1        | 1.15%   |
| Konica Minolta PagePro 1380MF                | 1        | 1.15%   |
| Konica Minolta C364Series                    | 1        | 1.15%   |
| HP Smart Tank 510 series                     | 1        | 1.15%   |
| HP PSC 1100 series                           | 1        | 1.15%   |
| HP Officejet 6600                            | 1        | 1.15%   |
| HP OfficeJet 5600 (USBHUB)                   | 1        | 1.15%   |
| HP OfficeJet 4650 series                     | 1        | 1.15%   |
| HP LaserJet Pro M148-M149                    | 1        | 1.15%   |
| HP LaserJet 1320                             | 1        | 1.15%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 73.33%  |
| Hewlett-Packard | 3        | 20%     |
| Seiko Epson     | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                | 2        | 12.5%   |
| Seiko Epson Scanner                    | 1        | 6.25%   |
| HP ScanJet 2400c                       | 1        | 6.25%   |
| HP Scanjet 200                         | 1        | 6.25%   |
| HP PSC 1200                            | 1        | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20     | 1        | 6.25%   |
| Canon CanoScan LiDE 90                 | 1        | 6.25%   |
| Canon CanoScan LiDE 60                 | 1        | 6.25%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1        | 6.25%   |
| Canon CanoScan LiDE 210                | 1        | 6.25%   |
| Canon CanoScan LiDE 110                | 1        | 6.25%   |
| Canon CanoScan LiDE 100                | 1        | 6.25%   |
| Canon CanoScan D660U                   | 1        | 6.25%   |
| Canon CanoScan 8800F                   | 1        | 6.25%   |
| Canon CanoScan 5600F                   | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 69       | 27.82%  |
| Microdia                      | 24       | 9.68%   |
| Microsoft                     | 16       | 6.45%   |
| Sunplus Innovation Technology | 15       | 6.05%   |
| Generalplus Technology        | 10       | 4.03%   |
| Apple                         | 10       | 4.03%   |
| Chicony Electronics           | 9        | 3.63%   |
| Samsung Electronics           | 8        | 3.23%   |
| ARC International             | 7        | 2.82%   |
| Z-Star Microelectronics       | 5        | 2.02%   |
| Jieli Technology              | 5        | 2.02%   |
| Realtek Semiconductor         | 4        | 1.61%   |
| Razer USA                     | 4        | 1.61%   |
| Creative Technology           | 4        | 1.61%   |
| A4Tech                        | 4        | 1.61%   |
| Tobii Technology AB           | 3        | 1.21%   |
| GEMBIRD                       | 3        | 1.21%   |
| 2M UVC CAMERA                 | 3        | 1.21%   |
| Xiongmai                      | 2        | 0.81%   |
| WaveRider Communications      | 2        | 0.81%   |
| Trust                         | 2        | 0.81%   |
| Suyin                         | 2        | 0.81%   |
| MacroSilicon                  | 2        | 0.81%   |
| lihappe8                      | 2        | 0.81%   |
| IMC Networks                  | 2        | 0.81%   |
| Guillemot                     | 2        | 0.81%   |
| Genesys Logic                 | 2        | 0.81%   |
| Cubeternet                    | 2        | 0.81%   |
| Aveo Technology               | 2        | 0.81%   |
| Xiaomi                        | 1        | 0.4%    |
| Unknown                       | 1        | 0.4%    |
| Teslong Camera                | 1        | 0.4%    |
| Sweex                         | 1        | 0.4%    |
| Sunplus Technology            | 1        | 0.4%    |
| Sonix Technology              | 1        | 0.4%    |
| Silicon Motion                | 1        | 0.4%    |
| Ruision                       | 1        | 0.4%    |
| Pixart Imaging                | 1        | 0.4%    |
| OmniVision Technologies       | 1        | 0.4%    |
| Lenovo                        | 1        | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 18       | 7.2%    |
| Logitech Webcam C270                     | 17       | 6.8%    |
| Microsoft LifeCam HD-3000                | 9        | 3.6%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 9        | 3.6%    |
| Samsung Galaxy series, misc. (MTP mode)  | 8        | 3.2%    |
| Microdia USB 2.0 Camera                  | 7        | 2.8%    |
| ARC International Camera                 | 7        | 2.8%    |
| Sunplus DICOTA 4K                        | 6        | 2.4%    |
| Microdia Webcam Vitade AF                | 6        | 2.4%    |
| Logitech HD Webcam C615                  | 6        | 2.4%    |
| Generalplus GENERAL WEBCAM               | 6        | 2.4%    |
| Jieli USB PHY 2.0                        | 5        | 2%      |
| Sunplus HD 720P webcam                   | 4        | 1.6%    |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 1.6%    |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 1.6%    |
| Chicony HP High Definition 1MP Webcam    | 4        | 1.6%    |
| Tobii AB EyeChip                         | 3        | 1.2%    |
| Microsoft LifeCam VX-500 [1357]          | 3        | 1.2%    |
| Microdia Integrated Camera               | 3        | 1.2%    |
| Logitech Logitech Webcam C925e           | 3        | 1.2%    |
| Logitech HD Webcam C910                  | 3        | 1.2%    |
| Chicony CNF8050 Webcam                   | 3        | 1.2%    |
| A4Tech PK-635G                           | 3        | 1.2%    |
| 2M UVC CAMERA NexiGo N60 FHD Webcam      | 3        | 1.2%    |
| Z-Star Venus USB2.0 Camera               | 2        | 0.8%    |
| Z-Star Integrated Camera                 | 2        | 0.8%    |
| Xiongmai web camera                      | 2        | 0.8%    |
| WaveRider USB Live camera                | 2        | 0.8%    |
| Suyin HD WebCam                          | 2        | 0.8%    |
| Microsoft MicrosoftÂ LifeCam Cinema     | 2        | 0.8%    |
| Microdia USB Live camera                 | 2        | 0.8%    |
| Microdia Streaming Camera W8GS           | 2        | 0.8%    |
| Logitech Webcam C310                     | 2        | 0.8%    |
| Logitech QuickCam Pro for Notebooks      | 2        | 0.8%    |
| Logitech QuickCam Orbit/Sphere AF        | 2        | 0.8%    |
| Logitech HD Webcam C525                  | 2        | 0.8%    |
| Logitech C922 Pro Stream Webcam          | 2        | 0.8%    |
| lihappe8 USB 2.0 Camera                  | 2        | 0.8%    |
| GEMBIRD USB2.0 PC CAMERA                 | 2        | 0.8%    |
| Creative Live! Cam Sync HD [VF0770]      | 2        | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 66.67%  |
| AuthenTec             | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor        | 2        | 66.67%  |
| AuthenTec AES2501 Fingerprint Sensor | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 16.67%  |
| Advanced Card Systems             | 2        | 16.67%  |
| VASCO Data Security International | 1        | 8.33%   |
| SCM Microsystems                  | 1        | 8.33%   |
| Reiner SCT Kartensysteme          | 1        | 8.33%   |
| Jing-Mold Enterprise              | 1        | 8.33%   |
| Gemalto (was Gemplus)             | 1        | 8.33%   |
| Fujitsu Siemens Computers         | 1        | 8.33%   |
| Chicony Electronics               | 1        | 8.33%   |
| Alcor Micro                       | 1        | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 16.67%  |
| VASCO Data Security International Digipass 905 SmartCard Reader   | 1        | 8.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 1        | 8.33%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                   | 1        | 8.33%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 8.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                 | 1        | 8.33%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                     | 1        | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                               | 1        | 8.33%   |
| Advanced Card Systems ACR39U                                      | 1        | 8.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader                      | 1        | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1199     | 78.73%  |
| 1     | 283      | 18.58%  |
| 2     | 36       | 2.36%   |
| 3     | 4        | 0.26%   |
| 4     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 143      | 40.74%  |
| Net/wireless             | 131      | 37.32%  |
| Communication controller | 16       | 4.56%   |
| Unassigned class         | 10       | 2.85%   |
| Multimedia controller    | 10       | 2.85%   |
| Chipcard                 | 8        | 2.28%   |
| Storage/raid             | 7        | 1.99%   |
| Bluetooth                | 5        | 1.42%   |
| Modem                    | 4        | 1.14%   |
| Sound                    | 3        | 0.85%   |
| Fingerprint reader       | 3        | 0.85%   |
| Storage/ide              | 2        | 0.57%   |
| Network                  | 2        | 0.57%   |
| Net/ethernet             | 2        | 0.57%   |
| Card reader              | 2        | 0.57%   |
| Camera                   | 2        | 0.57%   |
| Dvb card                 | 1        | 0.28%   |

