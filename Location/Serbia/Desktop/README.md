Linux in Serbia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Serbia.

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

Total: 434

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| NCR        | Pocono                      | [1a1c878e10](https://linux-hardware.org/?probe=1a1c878e10) | Jan 31, 2023 |
| ASRock     | FM2A68M-DG3+                | [7fb4a85c09](https://linux-hardware.org/?probe=7fb4a85c09) | Jan 30, 2023 |
| Lenovo     | 312A NOK                    | [ef4e303beb](https://linux-hardware.org/?probe=ef4e303beb) | Jan 23, 2023 |
| ASUSTek    | PRIME A320M-K               | [b20da22e41](https://linux-hardware.org/?probe=b20da22e41) | Jan 23, 2023 |
| Gigabyte   | G41MT-S2                    | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| ASUSTek    | A68HM-K                     | [770d2f3bb4](https://linux-hardware.org/?probe=770d2f3bb4) | Jan 22, 2023 |
| Lenovo     | SHARKBAY NOK                | [bc8b02043e](https://linux-hardware.org/?probe=bc8b02043e) | Jan 20, 2023 |
| ASUSTek    | M4A89GTD-PRO/USB3           | [61a73fa103](https://linux-hardware.org/?probe=61a73fa103) | Jan 12, 2023 |
| Medion     | MS-7621                     | [da2d61d475](https://linux-hardware.org/?probe=da2d61d475) | Jan 07, 2023 |
| ASRock     | X570 Pro4                   | [db00fde012](https://linux-hardware.org/?probe=db00fde012) | Jan 07, 2023 |
| Gigabyte   | A320M-H-CF                  | [b4511daea8](https://linux-hardware.org/?probe=b4511daea8) | Dec 30, 2022 |
| Gigabyte   | A320M-H-CF                  | [aff2b93aa5](https://linux-hardware.org/?probe=aff2b93aa5) | Dec 28, 2022 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| ASUSTek    | M4A89GTD-PRO/USB3           | [f51a366bc2](https://linux-hardware.org/?probe=f51a366bc2) | Dec 26, 2022 |
| NCR        | Pocono                      | [d50ad710fb](https://linux-hardware.org/?probe=d50ad710fb) | Dec 26, 2022 |
| Gigabyte   | B450M S2H                   | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek    | M4A89GTD-PRO/USB3           | [73c8ec2eb1](https://linux-hardware.org/?probe=73c8ec2eb1) | Dec 22, 2022 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [caaddcd344](https://linux-hardware.org/?probe=caaddcd344) | Dec 18, 2022 |
| MSI        | MPG X570S EDGE MAX WIFI     | [45eafa4ade](https://linux-hardware.org/?probe=45eafa4ade) | Dec 17, 2022 |
| ASUSTek    | P5KPL-AM/PS                 | [1fb1bc61c1](https://linux-hardware.org/?probe=1fb1bc61c1) | Dec 10, 2022 |
| ASUSTek    | P5KPL-AM/PS                 | [4cfe094684](https://linux-hardware.org/?probe=4cfe094684) | Dec 10, 2022 |
| Gigabyte   | B550 AORUS PRO V2           | [def749869a](https://linux-hardware.org/?probe=def749869a) | Dec 07, 2022 |
| ASUSTek    | ROG STRIX B550-E GAMING     | [6abdbbb7e7](https://linux-hardware.org/?probe=6abdbbb7e7) | Dec 07, 2022 |
| Gigabyte   | B450M DS3H-CF               | [9789efe96c](https://linux-hardware.org/?probe=9789efe96c) | Dec 07, 2022 |
| Gigabyte   | B450M DS3H-CF               | [9b5a24a1a2](https://linux-hardware.org/?probe=9b5a24a1a2) | Dec 07, 2022 |
| ASUSTek    | P7P55D DELUXE               | [a0864dbdc7](https://linux-hardware.org/?probe=a0864dbdc7) | Dec 06, 2022 |
| ASUSTek    | P7P55D DELUXE               | [ecb93d2406](https://linux-hardware.org/?probe=ecb93d2406) | Dec 06, 2022 |
| Gigabyte   | B250M-DS3H-CF               | [3fb8809375](https://linux-hardware.org/?probe=3fb8809375) | Dec 06, 2022 |
| ASUSTek    | PRIME A320M-K               | [a15aba2f94](https://linux-hardware.org/?probe=a15aba2f94) | Dec 04, 2022 |
| Gigabyte   | B450M DS3H-CF               | [660b9b7529](https://linux-hardware.org/?probe=660b9b7529) | Dec 01, 2022 |
| Gigabyte   | B450M DS3H-CF               | [9d7fdf83b6](https://linux-hardware.org/?probe=9d7fdf83b6) | Dec 01, 2022 |
| ASRock     | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| ASUSTek    | PRIME B450M-K               | [944ade9560](https://linux-hardware.org/?probe=944ade9560) | Nov 28, 2022 |
| ASUSTek    | PRIME A320M-K               | [37b51f19ef](https://linux-hardware.org/?probe=37b51f19ef) | Nov 27, 2022 |
| ASRock     | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock     | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| ASUSTek    | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| HP         | 212B                        | [d2ccd70744](https://linux-hardware.org/?probe=d2ccd70744) | Nov 05, 2022 |
| Gigabyte   | AB350M-DS3H V2-CF           | [27b07caa39](https://linux-hardware.org/?probe=27b07caa39) | Oct 31, 2022 |
| ASUSTek    | H97-PRO                     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| Gigabyte   | F2A88X-D3H                  | [7290b40608](https://linux-hardware.org/?probe=7290b40608) | Oct 27, 2022 |
| MSI        | MS-7309                     | [fe0fae3528](https://linux-hardware.org/?probe=fe0fae3528) | Oct 26, 2022 |
| MSI        | MS-7309                     | [2db582d6dd](https://linux-hardware.org/?probe=2db582d6dd) | Oct 25, 2022 |
| ASUSTek    | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte   | P35C-DS3R                   | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte   | P35C-DS3R                   | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| MSI        | H61M-P20                    | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| ASUSTek    | P5B-Deluxe                  | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| ASUSTek    | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| ASUSTek    | H61M-K                      | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [24c93934d4](https://linux-hardware.org/?probe=24c93934d4) | Sep 26, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [29f2bd4304](https://linux-hardware.org/?probe=29f2bd4304) | Sep 25, 2022 |
| Biostar    | TB250-BTC                   | [0a4522a059](https://linux-hardware.org/?probe=0a4522a059) | Sep 24, 2022 |
| ASUSTek    | PRIME A320M-K               | [815fe42722](https://linux-hardware.org/?probe=815fe42722) | Sep 23, 2022 |
| Gigabyte   | A320M-S2H-CF                | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| ASUSTek    | P5Q PRO TURBO               | [96564b490b](https://linux-hardware.org/?probe=96564b490b) | Sep 15, 2022 |
| ASUSTek    | P5Q PRO TURBO               | [846849e46c](https://linux-hardware.org/?probe=846849e46c) | Sep 15, 2022 |
| Foxconn    | 2AA9                        | [b671b09c1a](https://linux-hardware.org/?probe=b671b09c1a) | Sep 11, 2022 |
| ASUSTek    | PRIME A320M-K               | [cb47ce6e71](https://linux-hardware.org/?probe=cb47ce6e71) | Sep 09, 2022 |
| ASUSTek    | M4A89GTD-PRO/USB3           | [a355222b61](https://linux-hardware.org/?probe=a355222b61) | Sep 07, 2022 |
| HP         | 304Bh                       | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| Gigabyte   | 965P-DS3                    | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| HP         | 0980h                       | [1b4bdc2dd3](https://linux-hardware.org/?probe=1b4bdc2dd3) | Aug 25, 2022 |
| HP         | 0980h                       | [28433ca1db](https://linux-hardware.org/?probe=28433ca1db) | Aug 25, 2022 |
| HP         | 304Bh                       | [1e3d59e493](https://linux-hardware.org/?probe=1e3d59e493) | Aug 21, 2022 |
| Fujitsu    | D2990-A2 S26361-D2990-A2    | [bbeebdd421](https://linux-hardware.org/?probe=bbeebdd421) | Aug 01, 2022 |
| Gigabyte   | B450M DS3H-CF               | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte   | B450M DS3H-CF               | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [bece300d92](https://linux-hardware.org/?probe=bece300d92) | Jul 20, 2022 |
| Gigabyte   | B550M AORUS PRO-P           | [0c4f85c70e](https://linux-hardware.org/?probe=0c4f85c70e) | Jul 13, 2022 |
| MSI        | H61M-P20                    | [c86cefdaa6](https://linux-hardware.org/?probe=c86cefdaa6) | Jun 26, 2022 |
| ASUSTek    | H110M-R                     | [74d3cc8728](https://linux-hardware.org/?probe=74d3cc8728) | Jun 14, 2022 |
| ASRock     | G41C-GS                     | [c498f6f3bd](https://linux-hardware.org/?probe=c498f6f3bd) | Jun 13, 2022 |
| Gigabyte   | GA-H310TN-R2                | [2fecd41e0b](https://linux-hardware.org/?probe=2fecd41e0b) | Jun 03, 2022 |
| Gigabyte   | X570 GAMING X               | [2dba625d78](https://linux-hardware.org/?probe=2dba625d78) | May 28, 2022 |
| ASUSTek    | B85-PLUS                    | [ea1d17f234](https://linux-hardware.org/?probe=ea1d17f234) | May 27, 2022 |
| ASUSTek    | B85-PLUS                    | [e1efc36540](https://linux-hardware.org/?probe=e1efc36540) | May 27, 2022 |
| ASRock     | X570 Pro4                   | [da35dd6295](https://linux-hardware.org/?probe=da35dd6295) | May 22, 2022 |
| Gigabyte   | Z97P-D3                     | [1b7bdd0f65](https://linux-hardware.org/?probe=1b7bdd0f65) | May 21, 2022 |
| Gigabyte   | A520 AORUS ELITE            | [2fdd079ebc](https://linux-hardware.org/?probe=2fdd079ebc) | May 21, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| Gigabyte   | H110M-DS2-CF                | [7166bb5a53](https://linux-hardware.org/?probe=7166bb5a53) | May 14, 2022 |
| ASUSTek    | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| Fujitsu    | D3041-A1 S26361-D3041-A1    | [bc84347b65](https://linux-hardware.org/?probe=bc84347b65) | May 11, 2022 |
| ASUSTek    | M4A89GTD-PRO/USB3           | [38e20673c2](https://linux-hardware.org/?probe=38e20673c2) | May 09, 2022 |
| HP         | 3396                        | [468c2975ee](https://linux-hardware.org/?probe=468c2975ee) | Apr 30, 2022 |
| ASUSTek    | PRIME A320M-K               | [f4f8108d1e](https://linux-hardware.org/?probe=f4f8108d1e) | Apr 25, 2022 |
| ASUSTek    | P7H55                       | [d619f35fb8](https://linux-hardware.org/?probe=d619f35fb8) | Apr 16, 2022 |
| HP         | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| ASUSTek    | B150-PRO                    | [1ebe5f0e99](https://linux-hardware.org/?probe=1ebe5f0e99) | Apr 15, 2022 |
| Gigabyte   | 945PL-S3                    | [ef7f30cc40](https://linux-hardware.org/?probe=ef7f30cc40) | Apr 07, 2022 |
| Lenovo     | SHARKBAY 0B98401 PRO        | [55568ec828](https://linux-hardware.org/?probe=55568ec828) | Apr 06, 2022 |
| Apple      | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| ASRock     | B560M Steel Legend          | [8caaa96b19](https://linux-hardware.org/?probe=8caaa96b19) | Mar 28, 2022 |
| HP         | 3398                        | [b84864ecc4](https://linux-hardware.org/?probe=b84864ecc4) | Mar 25, 2022 |
| HP         | 3032h                       | [e57d52908c](https://linux-hardware.org/?probe=e57d52908c) | Mar 21, 2022 |
| HP         | 3398                        | [5f018df1dd](https://linux-hardware.org/?probe=5f018df1dd) | Mar 17, 2022 |
| ASUSTek    | M5A99X EVO                  | [117ebec9fc](https://linux-hardware.org/?probe=117ebec9fc) | Mar 15, 2022 |
| MSI        | AM1I                        | [f19c9ef173](https://linux-hardware.org/?probe=f19c9ef173) | Mar 14, 2022 |
| MSI        | A68HM-E33 V2                | [9f17c99bb5](https://linux-hardware.org/?probe=9f17c99bb5) | Mar 06, 2022 |
| MSI        | B450M PRO-M2                | [723ab179b6](https://linux-hardware.org/?probe=723ab179b6) | Mar 06, 2022 |
| Gigabyte   | H81M-S2PH                   | [4a1c505260](https://linux-hardware.org/?probe=4a1c505260) | Mar 05, 2022 |
| ASUSTek    | PRIME A320M-K               | [65b41a7a67](https://linux-hardware.org/?probe=65b41a7a67) | Feb 26, 2022 |
| Gigabyte   | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Fujitsu    | D3041-A1 S26361-D3041-A1    | [1f607a3c8c](https://linux-hardware.org/?probe=1f607a3c8c) | Feb 21, 2022 |
| Gigabyte   | MJPLNCB-00                  | [d9a5169bbc](https://linux-hardware.org/?probe=d9a5169bbc) | Feb 16, 2022 |
| MSI        | A55M-P33                    | [31c0a9c67c](https://linux-hardware.org/?probe=31c0a9c67c) | Feb 15, 2022 |
| MSI        | GF615M-P33 V2               | [b5bfcbf8dc](https://linux-hardware.org/?probe=b5bfcbf8dc) | Feb 13, 2022 |
| Gigabyte   | B450 AORUS PRO-CF           | [1eb72bde90](https://linux-hardware.org/?probe=1eb72bde90) | Feb 12, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [d6c5c1a6d2](https://linux-hardware.org/?probe=d6c5c1a6d2) | Feb 10, 2022 |
| ASUSTek    | P5KPL-AM/PS                 | [a530f2976f](https://linux-hardware.org/?probe=a530f2976f) | Feb 10, 2022 |
| ASUSTek    | P5KPL-AM/PS                 | [5480f2aa6c](https://linux-hardware.org/?probe=5480f2aa6c) | Feb 10, 2022 |
| ASUSTek    | M4A785TD-V EVO              | [b28eb819f0](https://linux-hardware.org/?probe=b28eb819f0) | Feb 09, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [1c829ba8dd](https://linux-hardware.org/?probe=1c829ba8dd) | Feb 07, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [80b24c2689](https://linux-hardware.org/?probe=80b24c2689) | Feb 03, 2022 |
| ASUSTek    | PRIME B450M-K               | [d644756f37](https://linux-hardware.org/?probe=d644756f37) | Feb 03, 2022 |
| MSI        | B450 TOMAHAWK               | [b5ae920f3b](https://linux-hardware.org/?probe=b5ae920f3b) | Feb 02, 2022 |
| ASRock     | P75 Pro3                    | [76bb99305c](https://linux-hardware.org/?probe=76bb99305c) | Jan 24, 2022 |
| Gigabyte   | 970A-DS3P                   | [b50f284364](https://linux-hardware.org/?probe=b50f284364) | Jan 23, 2022 |
| ASUSTek    | PRIME B450M-K               | [fa62cb2996](https://linux-hardware.org/?probe=fa62cb2996) | Jan 11, 2022 |
| Biostar    | TB250-BTC+                  | [ef57a01461](https://linux-hardware.org/?probe=ef57a01461) | Jan 06, 2022 |
| ASUSTek    | H110M-R                     | [8b6fab3f89](https://linux-hardware.org/?probe=8b6fab3f89) | Jan 05, 2022 |
| ASRock     | X570 Pro4                   | [0396ef9c72](https://linux-hardware.org/?probe=0396ef9c72) | Dec 30, 2021 |
| ASUSTek    | TUF B450M-PLUS GAMING       | [6324598512](https://linux-hardware.org/?probe=6324598512) | Dec 30, 2021 |
| ASUSTek    | TUF B450M-PLUS GAMING       | [38dda4af6b](https://linux-hardware.org/?probe=38dda4af6b) | Dec 30, 2021 |
| Gigabyte   | B550M DS3H                  | [9fb08ebeb4](https://linux-hardware.org/?probe=9fb08ebeb4) | Dec 26, 2021 |
| Gigabyte   | MJPLNCB-00                  | [fe81720eae](https://linux-hardware.org/?probe=fe81720eae) | Dec 23, 2021 |
| ASUSTek    | A68HM-K                     | [a6fc4a2adb](https://linux-hardware.org/?probe=a6fc4a2adb) | Dec 22, 2021 |
| MSI        | A55M-P33                    | [de87849301](https://linux-hardware.org/?probe=de87849301) | Dec 18, 2021 |
| MSI        | FM2-A55M-E33                | [85e65dae6a](https://linux-hardware.org/?probe=85e65dae6a) | Dec 15, 2021 |
| MSI        | FM2-A55M-E33                | [3ff4885854](https://linux-hardware.org/?probe=3ff4885854) | Dec 15, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [048c623b7a](https://linux-hardware.org/?probe=048c623b7a) | Dec 12, 2021 |
| Biostar    | NF520-A2 TE                 | [5878187120](https://linux-hardware.org/?probe=5878187120) | Dec 07, 2021 |
| MSI        | H61M-P20                    | [614ffcb196](https://linux-hardware.org/?probe=614ffcb196) | Dec 07, 2021 |
| ASUSTek    | PRIME A320M-K               | [19fbf0d287](https://linux-hardware.org/?probe=19fbf0d287) | Dec 04, 2021 |
| ASUSTek    | PRIME A320M-K               | [478ab590ac](https://linux-hardware.org/?probe=478ab590ac) | Dec 01, 2021 |
| ASUSTek    | P8B75-M LE                  | [7a8c29f7ba](https://linux-hardware.org/?probe=7a8c29f7ba) | Nov 23, 2021 |
| ASUSTek    | P8Z68-V LX                  | [0415c0798f](https://linux-hardware.org/?probe=0415c0798f) | Nov 18, 2021 |
| MSI        | G41M-P23                    | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| MSI        | G41M-P23                    | [ce4c8636f0](https://linux-hardware.org/?probe=ce4c8636f0) | Nov 04, 2021 |
| Gigabyte   | AB350M-Gaming 3-CF          | [b6338a1294](https://linux-hardware.org/?probe=b6338a1294) | Oct 25, 2021 |
| Gigabyte   | B450M S2H                   | [71c19b42fc](https://linux-hardware.org/?probe=71c19b42fc) | Oct 21, 2021 |
| Lenovo     | ThinkCentre M57 6075Y3W     | [a5e2419919](https://linux-hardware.org/?probe=a5e2419919) | Oct 19, 2021 |
| Gigabyte   | B450M DS3H-CF               | [f1fc83e719](https://linux-hardware.org/?probe=f1fc83e719) | Oct 17, 2021 |
| Gigabyte   | B450M DS3H-CF               | [2802b3ba4f](https://linux-hardware.org/?probe=2802b3ba4f) | Oct 17, 2021 |
| Gigabyte   | P35-S3G                     | [0582e2316b](https://linux-hardware.org/?probe=0582e2316b) | Oct 12, 2021 |
| ASUSTek    | M5A97 EVO R2.0              | [c8b4b9444e](https://linux-hardware.org/?probe=c8b4b9444e) | Oct 11, 2021 |
| ASRock     | QC5000-ITX/WiFi             | [74391da331](https://linux-hardware.org/?probe=74391da331) | Oct 09, 2021 |
| Biostar    | A320MH                      | [85950c5033](https://linux-hardware.org/?probe=85950c5033) | Sep 25, 2021 |
| ASUSTek    | H81M-R                      | [dfe4dc9048](https://linux-hardware.org/?probe=dfe4dc9048) | Sep 22, 2021 |
| MSI        | MS-7309                     | [f2ac6eb80a](https://linux-hardware.org/?probe=f2ac6eb80a) | Sep 18, 2021 |
| Lenovo     | ThinkCentre M57 6075Y3W     | [f133dd54a3](https://linux-hardware.org/?probe=f133dd54a3) | Sep 18, 2021 |
| HP         | 212B                        | [9a7f2627a3](https://linux-hardware.org/?probe=9a7f2627a3) | Sep 15, 2021 |
| HP         | 212B                        | [289f117cde](https://linux-hardware.org/?probe=289f117cde) | Sep 14, 2021 |
| ASUSTek    | H81M-R                      | [6a9795f23f](https://linux-hardware.org/?probe=6a9795f23f) | Sep 13, 2021 |
| Gigabyte   | X570 AORUS MASTER           | [67285c1d5d](https://linux-hardware.org/?probe=67285c1d5d) | Sep 11, 2021 |
| ASUSTek    | AM1M-A                      | [ab6a989deb](https://linux-hardware.org/?probe=ab6a989deb) | Sep 09, 2021 |
| ASRock     | Q1900M                      | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock     | Q1900M                      | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| ASUSTek    | AM1M-A                      | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| MSI        | 740GM-P25                   | [e1d245e0a3](https://linux-hardware.org/?probe=e1d245e0a3) | Aug 19, 2021 |
| ASUSTek    | AM1M-A                      | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| ASRock     | X570 Pro4                   | [3f122964da](https://linux-hardware.org/?probe=3f122964da) | Aug 14, 2021 |
| Gigabyte   | H61M-S2PV                   | [3985c521c2](https://linux-hardware.org/?probe=3985c521c2) | Aug 12, 2021 |
| ASUSTek    | M5A97 PLUS                  | [bf5a5f589f](https://linux-hardware.org/?probe=bf5a5f589f) | Aug 05, 2021 |
| Gigabyte   | B450M DS3H-CF               | [fda988dc8a](https://linux-hardware.org/?probe=fda988dc8a) | Jul 30, 2021 |
| Gigabyte   | H61M-S2PV                   | [766df6d543](https://linux-hardware.org/?probe=766df6d543) | Jul 30, 2021 |
| ASUSTek    | B75M-A                      | [d86a526a9b](https://linux-hardware.org/?probe=d86a526a9b) | Jul 28, 2021 |
| Gigabyte   | P31-DS3L                    | [48b32724e2](https://linux-hardware.org/?probe=48b32724e2) | Jul 27, 2021 |
| ASUSTek    | B75M-A                      | [25113d73cc](https://linux-hardware.org/?probe=25113d73cc) | Jul 21, 2021 |
| ASUSTek    | M2N-MX                      | [b5def43240](https://linux-hardware.org/?probe=b5def43240) | Jun 23, 2021 |
| MSI        | 760GM-P23                   | [2a7524175d](https://linux-hardware.org/?probe=2a7524175d) | Jun 20, 2021 |
| MSI        | 970A-G43                    | [447e2a364c](https://linux-hardware.org/?probe=447e2a364c) | Jun 18, 2021 |
| ASUSTek    | PRIME A320M-K               | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| MSI        | 970A-G43                    | [009fc99fc0](https://linux-hardware.org/?probe=009fc99fc0) | Jun 11, 2021 |
| ASUSTek    | P8Z77-V DELUXE              | [09f134f35d](https://linux-hardware.org/?probe=09f134f35d) | Jun 11, 2021 |
| Gigabyte   | 945PL-S3                    | [885dc78ef1](https://linux-hardware.org/?probe=885dc78ef1) | Jun 08, 2021 |
| MSI        | 970A-G43                    | [c0523d2ed9](https://linux-hardware.org/?probe=c0523d2ed9) | Jun 08, 2021 |
| Gigabyte   | H61M-DS2                    | [b527e6a2a9](https://linux-hardware.org/?probe=b527e6a2a9) | Jun 08, 2021 |
| ASUSTek    | PRIME A320M-K               | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| ASRock     | A320M-HDV R4.0              | [094ade14ae](https://linux-hardware.org/?probe=094ade14ae) | May 27, 2021 |
| ASRock     | B450M Pro4                  | [229b36f7f9](https://linux-hardware.org/?probe=229b36f7f9) | May 25, 2021 |
| Dell       | 0C27VV A01                  | [5824a76242](https://linux-hardware.org/?probe=5824a76242) | May 23, 2021 |
| Gigabyte   | B450M DS3H-CF               | [631e15df6a](https://linux-hardware.org/?probe=631e15df6a) | May 18, 2021 |
| ASRock     | H110 Pro BTC+               | [ff29bdd7f7](https://linux-hardware.org/?probe=ff29bdd7f7) | May 14, 2021 |
| ASUSTek    | PRIME A320M-K               | [7b5519e189](https://linux-hardware.org/?probe=7b5519e189) | May 10, 2021 |
| ASUSTek    | PRIME A320M-K               | [5ea8612591](https://linux-hardware.org/?probe=5ea8612591) | May 09, 2021 |
| ASUSTek    | PRIME A320M-K               | [e3f1850f8e](https://linux-hardware.org/?probe=e3f1850f8e) | May 07, 2021 |
| Gigabyte   | B450M DS3H-CF               | [211622d161](https://linux-hardware.org/?probe=211622d161) | May 05, 2021 |
| Gigabyte   | A320M-H-CF                  | [07a49be491](https://linux-hardware.org/?probe=07a49be491) | May 03, 2021 |
| Gigabyte   | H61M-S2PV                   | [325c441d47](https://linux-hardware.org/?probe=325c441d47) | Apr 27, 2021 |
| Gigabyte   | GA-890GPA-UD3H              | [15e01ddb68](https://linux-hardware.org/?probe=15e01ddb68) | Apr 27, 2021 |
| Inventec   | R CLASS A02                 | [d678a44af1](https://linux-hardware.org/?probe=d678a44af1) | Apr 18, 2021 |
| Lenovo     | 312A NOK                    | [5db737f928](https://linux-hardware.org/?probe=5db737f928) | Apr 16, 2021 |
| Gigabyte   | EP43-UD3L                   | [9988abc6d1](https://linux-hardware.org/?probe=9988abc6d1) | Mar 30, 2021 |
| HP         | 3032h                       | [04ae8fc721](https://linux-hardware.org/?probe=04ae8fc721) | Mar 26, 2021 |
| Acer       | FIH57                       | [ddb03d82a0](https://linux-hardware.org/?probe=ddb03d82a0) | Mar 24, 2021 |
| ASRock     | QC5000-ITX/WiFi             | [7940fddf34](https://linux-hardware.org/?probe=7940fddf34) | Mar 24, 2021 |
| HP         | 1497                        | [8a761041cb](https://linux-hardware.org/?probe=8a761041cb) | Mar 17, 2021 |
| MSI        | B450 TOMAHAWK               | [9d190d0899](https://linux-hardware.org/?probe=9d190d0899) | Mar 17, 2021 |
| ASRock     | Z390 Pro4                   | [5fe5bdf357](https://linux-hardware.org/?probe=5fe5bdf357) | Mar 16, 2021 |
| MSI        | 880GM-E41                   | [4f6b84a8c0](https://linux-hardware.org/?probe=4f6b84a8c0) | Mar 15, 2021 |
| MSI        | H61M-P20                    | [6c184c27d1](https://linux-hardware.org/?probe=6c184c27d1) | Mar 15, 2021 |
| Gigabyte   | GA-890GPA-UD3H              | [9aea38338d](https://linux-hardware.org/?probe=9aea38338d) | Mar 15, 2021 |
| Gigabyte   | H61M-D2H-USB3               | [7e3e20bba4](https://linux-hardware.org/?probe=7e3e20bba4) | Mar 15, 2021 |
| ASUSTek    | M5A88-V EVO                 | [3163da0fc6](https://linux-hardware.org/?probe=3163da0fc6) | Mar 12, 2021 |
| Intel      | 945                         | [87a90ecd5e](https://linux-hardware.org/?probe=87a90ecd5e) | Mar 11, 2021 |
| Intel      | 945                         | [4644c2d3dd](https://linux-hardware.org/?probe=4644c2d3dd) | Mar 10, 2021 |
| Intel      | 945                         | [bdcdd4c2c9](https://linux-hardware.org/?probe=bdcdd4c2c9) | Mar 09, 2021 |
| ASUSTek    | M5A88-V EVO                 | [54b1a7993c](https://linux-hardware.org/?probe=54b1a7993c) | Mar 09, 2021 |
| ASUSTek    | M5A88-V EVO                 | [20dd877fba](https://linux-hardware.org/?probe=20dd877fba) | Mar 09, 2021 |
| MSI        | MS-7369                     | [6b76ab1b0c](https://linux-hardware.org/?probe=6b76ab1b0c) | Mar 06, 2021 |
| MSI        | MS-7369                     | [c26816dad0](https://linux-hardware.org/?probe=c26816dad0) | Mar 06, 2021 |
| Supermicro | X8SIL                       | [5750984770](https://linux-hardware.org/?probe=5750984770) | Mar 05, 2021 |
| Supermicro | X8SIL                       | [c79eedd353](https://linux-hardware.org/?probe=c79eedd353) | Mar 04, 2021 |
| Lenovo     | 312A NOK                    | [10e16e0f14](https://linux-hardware.org/?probe=10e16e0f14) | Mar 02, 2021 |
| Gigabyte   | G31M-S2C                    | [a10534e0ba](https://linux-hardware.org/?probe=a10534e0ba) | Mar 02, 2021 |
| Supermicro | X8SIL                       | [325e488c16](https://linux-hardware.org/?probe=325e488c16) | Feb 28, 2021 |
| Supermicro | X8SIL                       | [58108e8eb1](https://linux-hardware.org/?probe=58108e8eb1) | Feb 28, 2021 |
| MSI        | 0A90                        | [36e73df6d5](https://linux-hardware.org/?probe=36e73df6d5) | Feb 26, 2021 |
| Intel      | 945                         | [de9b7b0ef0](https://linux-hardware.org/?probe=de9b7b0ef0) | Feb 25, 2021 |
| Intel      | 945                         | [d0b22beef3](https://linux-hardware.org/?probe=d0b22beef3) | Feb 25, 2021 |
| ASRock     | M3N78D                      | [c40a449681](https://linux-hardware.org/?probe=c40a449681) | Feb 23, 2021 |
| Gigabyte   | GA-890GPA-UD3H              | [888ff52208](https://linux-hardware.org/?probe=888ff52208) | Feb 21, 2021 |
| ASUSTek    | M4A89GTD-PRO/USB3           | [d2b9f26b16](https://linux-hardware.org/?probe=d2b9f26b16) | Feb 15, 2021 |
| ASUSTek    | P8B75-M LX                  | [dc49777ce8](https://linux-hardware.org/?probe=dc49777ce8) | Feb 14, 2021 |
| ASUSTek    | P5G41T-M LX3                | [d282a8d18c](https://linux-hardware.org/?probe=d282a8d18c) | Feb 14, 2021 |
| MSI        | 0A90                        | [bb71cea5b4](https://linux-hardware.org/?probe=bb71cea5b4) | Feb 09, 2021 |
| ASUSTek    | M4N78-AM                    | [4c528f55f3](https://linux-hardware.org/?probe=4c528f55f3) | Feb 07, 2021 |
| Gigabyte   | P31-ES3G                    | [5aca50689e](https://linux-hardware.org/?probe=5aca50689e) | Jan 29, 2021 |
| ASUSTek    | P5Q-EM                      | [e67f35f505](https://linux-hardware.org/?probe=e67f35f505) | Jan 28, 2021 |
| ASUSTek    | P5Q-EM                      | [d3ee3b13ef](https://linux-hardware.org/?probe=d3ee3b13ef) | Jan 28, 2021 |
| Gigabyte   | B450 AORUS ELITE            | [c7807c2ac4](https://linux-hardware.org/?probe=c7807c2ac4) | Jan 10, 2021 |
| ASRock     | B450M Steel Legend          | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| Gigabyte   | B85M-HD3                    | [e3a87784d6](https://linux-hardware.org/?probe=e3a87784d6) | Dec 29, 2020 |
| Biostar    | A320MH                      | [42b6908594](https://linux-hardware.org/?probe=42b6908594) | Dec 29, 2020 |
| Gigabyte   | Z87-HD3                     | [2f46386da3](https://linux-hardware.org/?probe=2f46386da3) | Dec 27, 2020 |
| Biostar    | NF520D3                     | [12a6b07515](https://linux-hardware.org/?probe=12a6b07515) | Dec 27, 2020 |
| Biostar    | NF520D3                     | [c78780427f](https://linux-hardware.org/?probe=c78780427f) | Dec 27, 2020 |
| Biostar    | NF520D3                     | [60a378a184](https://linux-hardware.org/?probe=60a378a184) | Dec 27, 2020 |
| ASUSTek    | M4N78-AM                    | [9973c728ba](https://linux-hardware.org/?probe=9973c728ba) | Dec 26, 2020 |
| MSI        | K9N6PGM2-V2                 | [e62cf453c7](https://linux-hardware.org/?probe=e62cf453c7) | Dec 26, 2020 |
| MSI        | MAG B550M BAZOOKA           | [a5084b2336](https://linux-hardware.org/?probe=a5084b2336) | Dec 26, 2020 |
| ASUSTek    | H110M-R                     | [3d6c26aa3c](https://linux-hardware.org/?probe=3d6c26aa3c) | Dec 18, 2020 |
| HP         | 1497                        | [b93a804d52](https://linux-hardware.org/?probe=b93a804d52) | Dec 09, 2020 |
| Gigabyte   | H310M S2H x.x               | [5fe883b8c8](https://linux-hardware.org/?probe=5fe883b8c8) | Dec 06, 2020 |
| Gigabyte   | E3000N                      | [2861121763](https://linux-hardware.org/?probe=2861121763) | Dec 03, 2020 |
| HP         | 1495                        | [260725df5b](https://linux-hardware.org/?probe=260725df5b) | Dec 02, 2020 |
| MSI        | H110M ECO                   | [d848b46f0e](https://linux-hardware.org/?probe=d848b46f0e) | Nov 29, 2020 |
| MSI        | H110M ECO                   | [3789cd7ccf](https://linux-hardware.org/?probe=3789cd7ccf) | Nov 29, 2020 |
| MSI        | 880GMS-E35                  | [821743caaa](https://linux-hardware.org/?probe=821743caaa) | Nov 29, 2020 |
| MSI        | A320M-A PRO                 | [ce774acedc](https://linux-hardware.org/?probe=ce774acedc) | Nov 27, 2020 |
| Gigabyte   | G31M-S2C                    | [d09ca3fed0](https://linux-hardware.org/?probe=d09ca3fed0) | Nov 24, 2020 |
| Dell       | 0F6X5P A00                  | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek    | H81M-R                      | [10a0831d44](https://linux-hardware.org/?probe=10a0831d44) | Nov 19, 2020 |
| ASUSTek    | PRIME A320M-K               | [546d681a51](https://linux-hardware.org/?probe=546d681a51) | Nov 18, 2020 |
| Dell       | 0KRC95 A02                  | [fb7486ffb1](https://linux-hardware.org/?probe=fb7486ffb1) | Nov 16, 2020 |
| Unknown    | MCP61                       | [c4aa33a4dc](https://linux-hardware.org/?probe=c4aa33a4dc) | Nov 16, 2020 |
| ASUSTek    | ROG STRIX B360-G GAMING     | [dc19b696c9](https://linux-hardware.org/?probe=dc19b696c9) | Nov 15, 2020 |
| ASRock     | A320M-HDV R4.0              | [c15d88af85](https://linux-hardware.org/?probe=c15d88af85) | Nov 12, 2020 |
| ASUSTek    | A55BM-K                     | [bff939ac49](https://linux-hardware.org/?probe=bff939ac49) | Nov 09, 2020 |
| ASUSTek    | ROG STRIX X470-F GAMING     | [579d5eed69](https://linux-hardware.org/?probe=579d5eed69) | Nov 07, 2020 |
| Supermicro | X8SIL                       | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| MSI        | H110M ECO                   | [bc31d5e177](https://linux-hardware.org/?probe=bc31d5e177) | Nov 01, 2020 |
| Supermicro | X8SIL                       | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASUSTek    | PRIME A320M-K               | [4c29ca1b5a](https://linux-hardware.org/?probe=4c29ca1b5a) | Oct 31, 2020 |
| Supermicro | X8SIL                       | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro | X8SIL                       | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| Gigabyte   | 945PL-S3P                   | [b72f72f621](https://linux-hardware.org/?probe=b72f72f621) | Oct 26, 2020 |
| Intel      | D946GZIS AAD66165-302       | [ba9fec911f](https://linux-hardware.org/?probe=ba9fec911f) | Oct 20, 2020 |
| Dell       | 0GM819                      | [e0cbe10449](https://linux-hardware.org/?probe=e0cbe10449) | Oct 17, 2020 |
| Gigabyte   | X399 DESIGNARE EX-CF        | [a5f35bd977](https://linux-hardware.org/?probe=a5f35bd977) | Oct 12, 2020 |
| ASUSTek    | PRIME A320M-K               | [ca6c1b562d](https://linux-hardware.org/?probe=ca6c1b562d) | Oct 05, 2020 |
| MSI        | H87-G41 PC Mate             | [ee0ab6bf04](https://linux-hardware.org/?probe=ee0ab6bf04) | Oct 02, 2020 |
| Biostar    | A320MH                      | [ee41403938](https://linux-hardware.org/?probe=ee41403938) | Oct 02, 2020 |
| Fujitsu    | D3220-A1 S26361-D3220-A1    | [3e7beef386](https://linux-hardware.org/?probe=3e7beef386) | Sep 30, 2020 |
| Gigabyte   | B360M DS3H                  | [61dcf65bfa](https://linux-hardware.org/?probe=61dcf65bfa) | Sep 30, 2020 |
| Gigabyte   | G31M-S2C                    | [d73874f616](https://linux-hardware.org/?probe=d73874f616) | Sep 29, 2020 |
| Gigabyte   | G31M-S2C                    | [d662ed85f8](https://linux-hardware.org/?probe=d662ed85f8) | Sep 29, 2020 |
| Gigabyte   | F2A68HM-S1                  | [b886a607be](https://linux-hardware.org/?probe=b886a607be) | Sep 28, 2020 |
| MSI        | 760GM-P21                   | [b23305b1f3](https://linux-hardware.org/?probe=b23305b1f3) | Sep 12, 2020 |
| ASUSTek    | H97-PLUS                    | [a5726bfa80](https://linux-hardware.org/?probe=a5726bfa80) | Sep 10, 2020 |
| Gigabyte   | F2A58M-DS2H                 | [41b9e1526c](https://linux-hardware.org/?probe=41b9e1526c) | Sep 10, 2020 |
| MSI        | 970 GAMING                  | [44041b729e](https://linux-hardware.org/?probe=44041b729e) | Sep 06, 2020 |
| HP         | 2AF3                        | [75f15238ce](https://linux-hardware.org/?probe=75f15238ce) | Aug 31, 2020 |
| ASRock     | X570 Pro4                   | [0d7778cc62](https://linux-hardware.org/?probe=0d7778cc62) | Aug 29, 2020 |
| MSI        | K9N6PGM2-V2                 | [cb65aa7264](https://linux-hardware.org/?probe=cb65aa7264) | Aug 25, 2020 |
| Gigabyte   | GA-890GPA-UD3H              | [6bb8820098](https://linux-hardware.org/?probe=6bb8820098) | Aug 22, 2020 |
| HP         | 3398                        | [8590b22254](https://linux-hardware.org/?probe=8590b22254) | Aug 15, 2020 |
| Dell       | 0DR845                      | [a4ddbdc998](https://linux-hardware.org/?probe=a4ddbdc998) | Aug 11, 2020 |
| MSI        | GF615M-P33                  | [b5c3471e8b](https://linux-hardware.org/?probe=b5c3471e8b) | Aug 09, 2020 |
| MSI        | GF615M-P33                  | [50b0587266](https://linux-hardware.org/?probe=50b0587266) | Aug 09, 2020 |
| HP         | 3032h                       | [9abca57bf3](https://linux-hardware.org/?probe=9abca57bf3) | Aug 06, 2020 |
| ASUSTek    | PRIME X570-P                | [801277e6be](https://linux-hardware.org/?probe=801277e6be) | Aug 05, 2020 |
| ECS        | H61H2-M12                   | [2ac9b3f866](https://linux-hardware.org/?probe=2ac9b3f866) | Aug 02, 2020 |
| ASUSTek    | H110M-R                     | [09dac438f3](https://linux-hardware.org/?probe=09dac438f3) | Jul 31, 2020 |
| ASUSTek    | A58M-E                      | [6cb4e9e3e5](https://linux-hardware.org/?probe=6cb4e9e3e5) | Jul 30, 2020 |
| Gigabyte   | GA-MA770T-UD3P              | [200bdd5138](https://linux-hardware.org/?probe=200bdd5138) | Jul 25, 2020 |
| Gigabyte   | 970A-DS3P                   | [c5a0f02633](https://linux-hardware.org/?probe=c5a0f02633) | Jul 24, 2020 |
| Gigabyte   | Z77X-UD5H                   | [4f0031f39f](https://linux-hardware.org/?probe=4f0031f39f) | Jul 21, 2020 |
| Gigabyte   | F2A68HM-S1                  | [9bdd60ecdf](https://linux-hardware.org/?probe=9bdd60ecdf) | Jul 19, 2020 |
| Gigabyte   | H61M-S2P                    | [a30442ec07](https://linux-hardware.org/?probe=a30442ec07) | Jul 19, 2020 |
| Gigabyte   | H61M-S2P                    | [57b85cdafa](https://linux-hardware.org/?probe=57b85cdafa) | Jul 19, 2020 |
| MSI        | GF615M-P33 V2               | [64d092bac7](https://linux-hardware.org/?probe=64d092bac7) | Jul 18, 2020 |
| MSI        | GF615M-P33 V2               | [ca930a9e05](https://linux-hardware.org/?probe=ca930a9e05) | Jul 17, 2020 |
| ASUSTek    | H110M-R                     | [26e1de29bc](https://linux-hardware.org/?probe=26e1de29bc) | Jul 14, 2020 |
| HP         | 1497                        | [c26aebcc5f](https://linux-hardware.org/?probe=c26aebcc5f) | Jul 13, 2020 |
| Gigabyte   | Z77X-UD5H                   | [dbc59ac760](https://linux-hardware.org/?probe=dbc59ac760) | Jul 12, 2020 |
| Dell       | 0GTK4K A02                  | [d40a7e2ced](https://linux-hardware.org/?probe=d40a7e2ced) | Jul 11, 2020 |
| Dell       | 0GTK4K A02                  | [085d13e046](https://linux-hardware.org/?probe=085d13e046) | Jul 11, 2020 |
| HP         | 18E7                        | [d277840c01](https://linux-hardware.org/?probe=d277840c01) | Jul 03, 2020 |
| Gigabyte   | F2A58M-DS2H                 | [3ed1463dd4](https://linux-hardware.org/?probe=3ed1463dd4) | Jun 17, 2020 |
| Pegatron   | 2AB6                        | [f886c11963](https://linux-hardware.org/?probe=f886c11963) | Jun 12, 2020 |
| Pegatron   | 2AB6                        | [c9954b4a26](https://linux-hardware.org/?probe=c9954b4a26) | Jun 11, 2020 |
| ASUSTek    | H110M-R                     | [c201f6d857](https://linux-hardware.org/?probe=c201f6d857) | Jun 11, 2020 |
| MSI        | G41M-P28                    | [b0ce30ab32](https://linux-hardware.org/?probe=b0ce30ab32) | Jun 11, 2020 |
| ASUSTek    | A58M-K                      | [117bf5197f](https://linux-hardware.org/?probe=117bf5197f) | Jun 10, 2020 |
| ASUSTek    | A58M-K                      | [f8f58eaad6](https://linux-hardware.org/?probe=f8f58eaad6) | Jun 09, 2020 |
| ASUSTek    | P5Q-VM DO                   | [346628ed49](https://linux-hardware.org/?probe=346628ed49) | Jun 09, 2020 |
| MSI        | G31TM-P21                   | [a63d6c107a](https://linux-hardware.org/?probe=a63d6c107a) | Jun 08, 2020 |
| MSI        | MS-7519                     | [27185a4dad](https://linux-hardware.org/?probe=27185a4dad) | Jun 05, 2020 |
| MSI        | B75MA-E33                   | [e7156806db](https://linux-hardware.org/?probe=e7156806db) | May 25, 2020 |
| MSI        | B75MA-E33                   | [508ff9a8bd](https://linux-hardware.org/?probe=508ff9a8bd) | May 25, 2020 |
| ASUSTek    | P5N73-AM                    | [3258ee8b5d](https://linux-hardware.org/?probe=3258ee8b5d) | May 23, 2020 |
| ASUSTek    | P7H55-M LX                  | [9799c4742b](https://linux-hardware.org/?probe=9799c4742b) | May 23, 2020 |
| ASUSTek    | P5QL PRO                    | [c8e5e768fd](https://linux-hardware.org/?probe=c8e5e768fd) | May 21, 2020 |
| Gigabyte   | P55-USB3                    | [59982dc231](https://linux-hardware.org/?probe=59982dc231) | May 14, 2020 |
| Gigabyte   | P31-DS3L                    | [507a4c1c74](https://linux-hardware.org/?probe=507a4c1c74) | May 12, 2020 |
| Gigabyte   | G1.Sniper A88X-CF           | [9de43ba1db](https://linux-hardware.org/?probe=9de43ba1db) | May 07, 2020 |
| HP         | 3398                        | [86c6f07f18](https://linux-hardware.org/?probe=86c6f07f18) | May 06, 2020 |
| Gigabyte   | P31-DS3L                    | [63fea1c9cd](https://linux-hardware.org/?probe=63fea1c9cd) | May 03, 2020 |
| ASUSTek    | A58M-K                      | [b40e7fdbef](https://linux-hardware.org/?probe=b40e7fdbef) | May 03, 2020 |
| Gigabyte   | P31-ES3G                    | [33279e03d0](https://linux-hardware.org/?probe=33279e03d0) | Apr 30, 2020 |
| Gigabyte   | G1.Sniper A88X-CF           | [4cae21a722](https://linux-hardware.org/?probe=4cae21a722) | Apr 22, 2020 |
| ASUSTek    | P5Q-VM DO                   | [fc60d56b77](https://linux-hardware.org/?probe=fc60d56b77) | Apr 19, 2020 |
| ASUSTek    | A58M-K                      | [c86917f5cc](https://linux-hardware.org/?probe=c86917f5cc) | Apr 17, 2020 |
| MSI        | FM2-A55M-E33                | [2e15f64ca6](https://linux-hardware.org/?probe=2e15f64ca6) | Apr 14, 2020 |
| Pegatron   | 2AB5                        | [b041763dea](https://linux-hardware.org/?probe=b041763dea) | Apr 11, 2020 |
| ASUSTek    | PRIME A320M-K               | [1418f2501e](https://linux-hardware.org/?probe=1418f2501e) | Apr 10, 2020 |
| Biostar    | TB250-BTC                   | [fd92f418b8](https://linux-hardware.org/?probe=fd92f418b8) | Apr 08, 2020 |
| HP         | 18E7                        | [4d9f332c70](https://linux-hardware.org/?probe=4d9f332c70) | Apr 08, 2020 |
| HP         | 18E7                        | [6f953f68bd](https://linux-hardware.org/?probe=6f953f68bd) | Apr 08, 2020 |
| Gigabyte   | P31-DS3L                    | [b713dcca4f](https://linux-hardware.org/?probe=b713dcca4f) | Apr 08, 2020 |
| ASUSTek    | PRIME A320M-K               | [a34d2ffc57](https://linux-hardware.org/?probe=a34d2ffc57) | Apr 08, 2020 |
| ASUSTek    | A58M-K                      | [2d7bcf65f9](https://linux-hardware.org/?probe=2d7bcf65f9) | Apr 07, 2020 |
| ASUSTek    | A58M-K                      | [7db11256da](https://linux-hardware.org/?probe=7db11256da) | Apr 05, 2020 |
| ASUSTek    | P5Q-VM DO                   | [f1dcc22829](https://linux-hardware.org/?probe=f1dcc22829) | Apr 05, 2020 |
| MSI        | 760GM-P23                   | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| Gigabyte   | A320M-DS2-CF                | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte   | GA-890GPA-UD3H              | [d51cbbf880](https://linux-hardware.org/?probe=d51cbbf880) | Mar 07, 2020 |
| Gigabyte   | F2A55M-DS2                  | [a82780cd8c](https://linux-hardware.org/?probe=a82780cd8c) | Mar 04, 2020 |
| Fujitsu    | D3028-A1 S26361-D3028-A1    | [68b9561775](https://linux-hardware.org/?probe=68b9561775) | Mar 03, 2020 |
| ASUSTek    | P8B75-M LE                  | [6140664ce7](https://linux-hardware.org/?probe=6140664ce7) | Feb 26, 2020 |
| Gigabyte   | F2A55M-DS2                  | [d79a2cce0d](https://linux-hardware.org/?probe=d79a2cce0d) | Feb 25, 2020 |
| ASUSTek    | H110M-R                     | [2d9562d0e1](https://linux-hardware.org/?probe=2d9562d0e1) | Feb 24, 2020 |
| ASUSTek    | P5Q                         | [f22209135d](https://linux-hardware.org/?probe=f22209135d) | Feb 22, 2020 |
| ASUSTek    | P5Q                         | [6d0cd87c90](https://linux-hardware.org/?probe=6d0cd87c90) | Feb 22, 2020 |
| Biostar    | TB85                        | [ee5bd25897](https://linux-hardware.org/?probe=ee5bd25897) | Feb 13, 2020 |
| MSI        | MS-7309                     | [3a6ec44dd2](https://linux-hardware.org/?probe=3a6ec44dd2) | Feb 11, 2020 |
| Gigabyte   | G1.Sniper A88X-CF           | [034e07f7f9](https://linux-hardware.org/?probe=034e07f7f9) | Jan 28, 2020 |
| Gigabyte   | B360M DS3H                  | [eab9be2c36](https://linux-hardware.org/?probe=eab9be2c36) | Jan 25, 2020 |
| ASUSTek    | F2A55-M LK2 PLUS            | [a292515c70](https://linux-hardware.org/?probe=a292515c70) | Jan 24, 2020 |
| ASUSTek    | P5B                         | [149a63defe](https://linux-hardware.org/?probe=149a63defe) | Jan 15, 2020 |
| ASUSTek    | TUF X299 MARK 2             | [afa0b93a9a](https://linux-hardware.org/?probe=afa0b93a9a) | Jan 13, 2020 |
| ASUSTek    | TUF X299 MARK 2             | [3b4ed71c09](https://linux-hardware.org/?probe=3b4ed71c09) | Jan 13, 2020 |
| Gigabyte   | GA-880GA-UD3H               | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| MSI        | A55M-P33                    | [96778949af](https://linux-hardware.org/?probe=96778949af) | Jan 12, 2020 |
| Gigabyte   | GA-890GPA-UD3H              | [e722d70419](https://linux-hardware.org/?probe=e722d70419) | Dec 26, 2019 |
| ASUSTek    | M2V-MX SE                   | [476f99ff1b](https://linux-hardware.org/?probe=476f99ff1b) | Dec 25, 2019 |
| ASUSTek    | M2V-MX SE                   | [b3a4634787](https://linux-hardware.org/?probe=b3a4634787) | Dec 11, 2019 |
| HP         | 18E7                        | [df3ebe7dbd](https://linux-hardware.org/?probe=df3ebe7dbd) | Dec 05, 2019 |
| ASUSTek    | PRIME A320M-K               | [3d62acc94f](https://linux-hardware.org/?probe=3d62acc94f) | Nov 23, 2019 |
| Gigabyte   | Z170-D3H-CF                 | [38d61517b0](https://linux-hardware.org/?probe=38d61517b0) | Nov 18, 2019 |
| Gigabyte   | Z170-D3H-CF                 | [5e619cb47c](https://linux-hardware.org/?probe=5e619cb47c) | Nov 14, 2019 |
| Gigabyte   | H61M-S2PV                   | [e4374eaa46](https://linux-hardware.org/?probe=e4374eaa46) | Nov 13, 2019 |
| ASUSTek    | P5VD2-VM                    | [be44322d10](https://linux-hardware.org/?probe=be44322d10) | Nov 10, 2019 |
| HP         | 18E7                        | [92ce2d6aee](https://linux-hardware.org/?probe=92ce2d6aee) | Nov 01, 2019 |
| HP         | 18E7                        | [bddfdd0942](https://linux-hardware.org/?probe=bddfdd0942) | Oct 30, 2019 |
| ASUSTek    | H81M-PLUS                   | [dab482c9fe](https://linux-hardware.org/?probe=dab482c9fe) | Oct 17, 2019 |
| Gigabyte   | EX58-UD5                    | [e9b8af35f1](https://linux-hardware.org/?probe=e9b8af35f1) | Sep 18, 2019 |
| HP         | 0AECh D                     | [269249911a](https://linux-hardware.org/?probe=269249911a) | Sep 12, 2019 |
| HP         | 0AECh D                     | [ba5eb5e765](https://linux-hardware.org/?probe=ba5eb5e765) | Sep 10, 2019 |
| HP         | 0AECh D                     | [ced13a5341](https://linux-hardware.org/?probe=ced13a5341) | Sep 10, 2019 |
| HP         | 0AECh D                     | [a21951a4db](https://linux-hardware.org/?probe=a21951a4db) | Sep 10, 2019 |
| MSI        | K9A2 Neo2                   | [282a00eec9](https://linux-hardware.org/?probe=282a00eec9) | Sep 09, 2019 |
| ASUSTek    | STRIX B250F GAMING          | [8310a10125](https://linux-hardware.org/?probe=8310a10125) | Sep 04, 2019 |
| ASUSTek    | STRIX B250F GAMING          | [7dfedd3f65](https://linux-hardware.org/?probe=7dfedd3f65) | Sep 04, 2019 |
| Gigabyte   | Z77X-UD5H                   | [9795f4c856](https://linux-hardware.org/?probe=9795f4c856) | Aug 08, 2019 |
| MSI        | G31TM-P21                   | [95c164bfe9](https://linux-hardware.org/?probe=95c164bfe9) | Jul 09, 2019 |
| HP         | 18E7                        | [9f42078526](https://linux-hardware.org/?probe=9f42078526) | Jun 17, 2019 |
| Gigabyte   | Z370N WIFI-CF               | [1920d53d00](https://linux-hardware.org/?probe=1920d53d00) | Jun 14, 2019 |
| Gigabyte   | nForce                      | [bb385761f8](https://linux-hardware.org/?probe=bb385761f8) | Jun 13, 2019 |
| Gigabyte   | nForce                      | [8f095ad1ed](https://linux-hardware.org/?probe=8f095ad1ed) | Jun 13, 2019 |
| Gigabyte   | H77-DS3H                    | [2c88acf8c6](https://linux-hardware.org/?probe=2c88acf8c6) | May 09, 2019 |
| ASUSTek    | Z87-PRO                     | [d4224e0573](https://linux-hardware.org/?probe=d4224e0573) | May 07, 2019 |
| ASUSTek    | P5KPL-AM                    | [93fe493cc6](https://linux-hardware.org/?probe=93fe493cc6) | May 05, 2019 |
| Gigabyte   | Z68X-UD3H-B3                | [df39cb5ee3](https://linux-hardware.org/?probe=df39cb5ee3) | May 02, 2019 |
| ASUSTek    | P5KPL-AM                    | [b9c9d59c4d](https://linux-hardware.org/?probe=b9c9d59c4d) | Apr 29, 2019 |
| ASUSTek    | P5KPL-AM                    | [7e9b6e595f](https://linux-hardware.org/?probe=7e9b6e595f) | Apr 27, 2019 |
| ASUSTek    | P5KPL-AM                    | [cd90126cd9](https://linux-hardware.org/?probe=cd90126cd9) | Apr 27, 2019 |
| Gigabyte   | 945GZM-S2                   | [9b7c085767](https://linux-hardware.org/?probe=9b7c085767) | Apr 19, 2019 |
| ASRock     | Z370 Pro4                   | [4e2a505f4c](https://linux-hardware.org/?probe=4e2a505f4c) | Apr 14, 2019 |
| Biostar    | A320MH                      | [ec3de6c8f3](https://linux-hardware.org/?probe=ec3de6c8f3) | Apr 14, 2019 |
| HP         | 3397                        | [de1f50edc6](https://linux-hardware.org/?probe=de1f50edc6) | Apr 10, 2019 |
| ASUSTek    | P5KPL-AM SE                 | [d0387d6f7f](https://linux-hardware.org/?probe=d0387d6f7f) | Feb 14, 2019 |
| HP         | 304Bh                       | [d0e9c381f4](https://linux-hardware.org/?probe=d0e9c381f4) | Jan 30, 2019 |
| HP         | 304Bh                       | [20b87b0499](https://linux-hardware.org/?probe=20b87b0499) | Jan 30, 2019 |
| Gigabyte   | GA-M55PLUS-S3G              | [00e0d03d08](https://linux-hardware.org/?probe=00e0d03d08) | Dec 31, 2018 |
| Gigabyte   | GA-M55PLUS-S3G              | [bee5cfec2b](https://linux-hardware.org/?probe=bee5cfec2b) | Dec 31, 2018 |
| ASUSTek    | H81M-K                      | [feb3df641a](https://linux-hardware.org/?probe=feb3df641a) | Dec 30, 2018 |
| Sapphire   | PI-AM3RS785G                | [056357df30](https://linux-hardware.org/?probe=056357df30) | Nov 23, 2018 |
| Gigabyte   | GA-MA790XT-UD4P             | [4dc8527429](https://linux-hardware.org/?probe=4dc8527429) | Oct 18, 2018 |
| Gigabyte   | B360M DS3H                  | [28d5f5c509](https://linux-hardware.org/?probe=28d5f5c509) | Jun 07, 2018 |
| ASUSTek    | P5G41T-M LX                 | [5af7396727](https://linux-hardware.org/?probe=5af7396727) | May 09, 2018 |
| ASUSTek    | P5KPL-SE                    | [89e7fd236e](https://linux-hardware.org/?probe=89e7fd236e) | May 06, 2018 |
| ASUSTek    | P5K PRO                     | [56d1969bce](https://linux-hardware.org/?probe=56d1969bce) | Apr 17, 2018 |
| HP         | 18E7                        | [271b2e5f68](https://linux-hardware.org/?probe=271b2e5f68) | Mar 30, 2018 |
| HP         | 18E7                        | [5a5c8eb33e](https://linux-hardware.org/?probe=5a5c8eb33e) | Mar 09, 2018 |
| MSI        | Z77A-G41                    | [b153017c21](https://linux-hardware.org/?probe=b153017c21) | Dec 06, 2017 |
| Gigabyte   | EX58-UD5                    | [fa09aec26e](https://linux-hardware.org/?probe=fa09aec26e) | Nov 14, 2017 |
| ASUSTek    | P5KPL-SE                    | [28a8c15f9f](https://linux-hardware.org/?probe=28a8c15f9f) | Oct 05, 2017 |
| MSI        | Z77A-G41                    | [f58e7ca8f5](https://linux-hardware.org/?probe=f58e7ca8f5) | Jun 08, 2017 |
| MSI        | Z77A-G41                    | [c8b35c8a55](https://linux-hardware.org/?probe=c8b35c8a55) | May 14, 2017 |
| MSI        | Z77A-G41                    | [38f8ac507c](https://linux-hardware.org/?probe=38f8ac507c) | May 14, 2017 |
| Gigabyte   | M68MT-S2                    | [22698f1708](https://linux-hardware.org/?probe=22698f1708) | May 09, 2017 |
| Gigabyte   | H61M-S2PV                   | [1f46bc5de5](https://linux-hardware.org/?probe=1f46bc5de5) | May 01, 2017 |
| MSI        | A68HM-E33                   | [10a8c09f6f](https://linux-hardware.org/?probe=10a8c09f6f) | Feb 01, 2017 |
| Gigabyte   | EX58-UD5                    | [e05aaad3af](https://linux-hardware.org/?probe=e05aaad3af) | Jan 06, 2017 |
| MSI        | A68HM-E33                   | [d8ef39f103](https://linux-hardware.org/?probe=d8ef39f103) | Dec 23, 2016 |
| HP         | 18E7                        | [1c4f5fdfe5](https://linux-hardware.org/?probe=1c4f5fdfe5) | Nov 07, 2016 |
| HP         | 18E7                        | [b4c03f5538](https://linux-hardware.org/?probe=b4c03f5538) | Nov 07, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 47       | 15.06%  |
| Ubuntu 18.04                 | 22       | 7.05%   |
| OpenMandriva 4.2             | 18       | 5.77%   |
| OpenMandriva 4.3             | 15       | 4.81%   |
| Ubuntu 22.04                 | 9        | 2.88%   |
| BlackPanther 18.1            | 9        | 2.88%   |
| KDE neon 20.04               | 8        | 2.56%   |
| ROSA R10                     | 7        | 2.24%   |
| Arch Rolling                 | 7        | 2.24%   |
| Zorin 16                     | 6        | 1.92%   |
| Linux Mint 20                | 6        | 1.92%   |
| Ubuntu 21.10                 | 5        | 1.6%    |
| Pop!_OS 20.04                | 5        | 1.6%    |
| Arch                         | 5        | 1.6%    |
| Ubuntu 22.10                 | 4        | 1.28%   |
| Ubuntu 21.04                 | 4        | 1.28%   |
| Ubuntu 19.10                 | 4        | 1.28%   |
| ROSA R8                      | 4        | 1.28%   |
| ROSA R11                     | 4        | 1.28%   |
| OpenMandriva 23.01           | 4        | 1.28%   |
| Linux Mint 19.3              | 4        | 1.28%   |
| Kubuntu 20.04                | 4        | 1.28%   |
| Zorin 15                     | 3        | 0.96%   |
| ROSA R9                      | 3        | 0.96%   |
| ROSA R11.1                   | 3        | 0.96%   |
| ROSA 12.2                    | 3        | 0.96%   |
| Pop!_OS 22.04                | 3        | 0.96%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 0.96%   |
| Linux Mint 20.3              | 3        | 0.96%   |
| Linux Mint 20.2              | 3        | 0.96%   |
| Linux Mint 19.2              | 3        | 0.96%   |
| Fedora 36                    | 3        | 0.96%   |
| Debian 10                    | 3        | 0.96%   |
| Zorin 12                     | 2        | 0.64%   |
| Ubuntu Unity 20.04           | 2        | 0.64%   |
| Ubuntu 18.10                 | 2        | 0.64%   |
| Pop!_OS 21.10                | 2        | 0.64%   |
| Pop!_OS 20.10                | 2        | 0.64%   |
| openSUSE Leap-15.2           | 2        | 0.64%   |
| Nobara 36                    | 2        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 97       | 32.88%  |
| OpenMandriva | 39       | 13.22%  |
| Linux Mint   | 19       | 6.44%   |
| ROSA         | 18       | 6.1%    |
| Pop!_OS      | 12       | 4.07%   |
| Arch         | 12       | 4.07%   |
| Zorin        | 11       | 3.73%   |
| BlackPanther | 10       | 3.39%   |
| Kubuntu      | 9        | 3.05%   |
| KDE neon     | 9        | 3.05%   |
| Fedora       | 9        | 3.05%   |
| Debian       | 7        | 2.37%   |
| openSUSE     | 6        | 2.03%   |
| Manjaro      | 5        | 1.69%   |
| Ubuntu Unity | 3        | 1.02%   |
| MX           | 3        | 1.02%   |
| Endless      | 3        | 1.02%   |
| Clear Linux  | 3        | 1.02%   |
| ArcoLinux    | 3        | 1.02%   |
| Nobara       | 2        | 0.68%   |
| LinuxFX      | 2        | 0.68%   |
| Kali         | 2        | 0.68%   |
| Xubuntu      | 1        | 0.34%   |
| Slackware    | 1        | 0.34%   |
| Serbian      | 1        | 0.34%   |
| PCLinuxOS    | 1        | 0.34%   |
| NixOS        | 1        | 0.34%   |
| LMDE         | 1        | 0.34%   |
| Garuda Linux | 1        | 0.34%   |
| EndeavourOS  | 1        | 0.34%   |
| Elementary   | 1        | 0.34%   |
| Drauger OS   | 1        | 0.34%   |
| CentOS       | 1        | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 18       | 5.34%   |
| 5.16.7-desktop-1omv4003         | 15       | 4.45%   |
| 5.4.0-42-generic                | 12       | 3.56%   |
| 4.18.16-desktop-1bP             | 7        | 2.08%   |
| 5.15.0-56-generic               | 5        | 1.48%   |
| 5.15.0-53-generic               | 5        | 1.48%   |
| 6.1.1-desktop-1omv2290          | 4        | 1.19%   |
| 5.4.0-91-generic                | 4        | 1.19%   |
| 5.13.0-28-generic               | 4        | 1.19%   |
| 4.18.0-17-generic               | 4        | 1.19%   |
| 5.4.0-54-generic                | 3        | 0.89%   |
| 5.4.0-48-generic                | 3        | 0.89%   |
| 5.4.0-40-generic                | 3        | 0.89%   |
| 5.4.0-31-generic                | 3        | 0.89%   |
| 5.4.0-26-generic                | 3        | 0.89%   |
| 5.3.0-46-generic                | 3        | 0.89%   |
| 5.11.0-34-generic               | 3        | 0.89%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 0.89%   |
| 5.9.14-arch1-1                  | 2        | 0.59%   |
| 5.8.0-7642-generic              | 2        | 0.59%   |
| 5.8.0-7630-generic              | 2        | 0.59%   |
| 5.8.0-44-generic                | 2        | 0.59%   |
| 5.8.0-41-generic                | 2        | 0.59%   |
| 5.7.8-windowsfx-generic         | 2        | 0.59%   |
| 5.6.14-desktop-2bP              | 2        | 0.59%   |
| 5.4.32-generic-2rosa-x86_64     | 2        | 0.59%   |
| 5.4.0-74-generic                | 2        | 0.59%   |
| 5.4.0-58-generic                | 2        | 0.59%   |
| 5.4.0-56-generic                | 2        | 0.59%   |
| 5.4.0-53-generic                | 2        | 0.59%   |
| 5.4.0-52-generic                | 2        | 0.59%   |
| 5.4.0-37-generic                | 2        | 0.59%   |
| 5.4.0-29-generic                | 2        | 0.59%   |
| 5.4.0-28-generic                | 2        | 0.59%   |
| 5.4.0-110-generic               | 2        | 0.59%   |
| 5.3.18-lp152.106-preempt        | 2        | 0.59%   |
| 5.3.11-300.fc31.x86_64          | 2        | 0.59%   |
| 5.3.0-51-generic                | 2        | 0.59%   |
| 5.3.0-40-generic                | 2        | 0.59%   |
| 5.3.0-24-generic                | 2        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 60       | 19.17%  |
| 4.15.0  | 22       | 7.03%   |
| 5.10.14 | 18       | 5.75%   |
| 5.11.0  | 16       | 5.11%   |
| 5.8.0   | 15       | 4.79%   |
| 5.16.7  | 15       | 4.79%   |
| 5.15.0  | 14       | 4.47%   |
| 5.13.0  | 14       | 4.47%   |
| 5.3.0   | 10       | 3.19%   |
| 4.18.16 | 7        | 2.24%   |
| 4.18.0  | 7        | 2.24%   |
| 6.1.1   | 5        | 1.6%    |
| 5.19.0  | 5        | 1.6%    |
| 5.0.0   | 4        | 1.28%   |
| 4.9.60  | 4        | 1.28%   |
| 4.19.0  | 4        | 1.28%   |
| 5.7.8   | 3        | 0.96%   |
| 4.9.20  | 3        | 0.96%   |
| 6.0.8   | 2        | 0.64%   |
| 5.9.14  | 2        | 0.64%   |
| 5.6.14  | 2        | 0.64%   |
| 5.4.32  | 2        | 0.64%   |
| 5.3.18  | 2        | 0.64%   |
| 5.3.11  | 2        | 0.64%   |
| 5.2.0   | 2        | 0.64%   |
| 5.19.9  | 2        | 0.64%   |
| 5.17.9  | 2        | 0.64%   |
| 5.10.74 | 2        | 0.64%   |
| 5.10.0  | 2        | 0.64%   |
| 4.9.87  | 2        | 0.64%   |
| 4.4.0   | 2        | 0.64%   |
| 4.1.34  | 2        | 0.64%   |
| 6.1.0   | 1        | 0.32%   |
| 6.0.6   | 1        | 0.32%   |
| 6.0.2   | 1        | 0.32%   |
| 6.0.12  | 1        | 0.32%   |
| 6.0.11  | 1        | 0.32%   |
| 6.0.0   | 1        | 0.32%   |
| 5.9.8   | 1        | 0.32%   |
| 5.9.6   | 1        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 67       | 21.61%  |
| 5.10    | 24       | 7.74%   |
| 4.15    | 22       | 7.1%    |
| 5.15    | 18       | 5.81%   |
| 5.11    | 18       | 5.81%   |
| 5.8     | 16       | 5.16%   |
| 5.16    | 16       | 5.16%   |
| 5.13    | 16       | 5.16%   |
| 5.3     | 15       | 4.84%   |
| 4.18    | 14       | 4.52%   |
| 5.19    | 12       | 3.87%   |
| 4.9     | 9        | 2.9%    |
| 6.0     | 7        | 2.26%   |
| 5.6     | 7        | 2.26%   |
| 6.1     | 6        | 1.94%   |
| 5.9     | 6        | 1.94%   |
| 5.7     | 6        | 1.94%   |
| 5.0     | 5        | 1.61%   |
| 4.19    | 5        | 1.61%   |
| 4.1     | 4        | 1.29%   |
| 5.17    | 3        | 0.97%   |
| 5.14    | 3        | 0.97%   |
| 5.2     | 2        | 0.65%   |
| 5.18    | 2        | 0.65%   |
| 5.1     | 2        | 0.65%   |
| 4.4     | 2        | 0.65%   |
| 5.5     | 1        | 0.32%   |
| 4.8     | 1        | 0.32%   |
| 4.13    | 1        | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 274      | 97.16%  |
| i686   | 8        | 2.84%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 123      | 42.56%  |
| KDE5            | 77       | 26.64%  |
| Unknown         | 23       | 7.96%   |
| XFCE            | 17       | 5.88%   |
| X-Cinnamon      | 15       | 5.19%   |
| KDE             | 11       | 3.81%   |
| KDE4            | 10       | 3.46%   |
| Unity           | 3        | 1.04%   |
| Cinnamon        | 3        | 1.04%   |
| i3              | 2        | 0.69%   |
| qtile           | 1        | 0.35%   |
| Pantheon        | 1        | 0.35%   |
| MATE            | 1        | 0.35%   |
| LXDE            | 1        | 0.35%   |
| GNOME Flashback | 1        | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 251      | 86.25%  |
| Wayland | 30       | 10.31%  |
| Unknown | 8        | 2.75%   |
| Tty     | 2        | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 154      | 52.2%   |
| SDDM    | 63       | 21.36%  |
| GDM3    | 24       | 8.14%   |
| GDM     | 20       | 6.78%   |
| LightDM | 15       | 5.08%   |
| KDM     | 10       | 3.39%   |
| TDM     | 6        | 2.03%   |
| XDM     | 1        | 0.34%   |
| MDM     | 1        | 0.34%   |
| Ly      | 1        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 191      | 65.41%  |
| Unknown     | 52       | 17.81%  |
| sr_RS       | 26       | 8.9%    |
| hu_HU       | 7        | 2.4%    |
| C           | 5        | 1.71%   |
| sr_RS@latin | 4        | 1.37%   |
| en_AU       | 2        | 0.68%   |
| sk_SK       | 1        | 0.34%   |
| ru_RU       | 1        | 0.34%   |
| en_GB       | 1        | 0.34%   |
| de_DE       | 1        | 0.34%   |
| Default     | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 189      | 66.55%  |
| EFI  | 95       | 33.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 204      | 69.86%  |
| Overlay | 50       | 17.12%  |
| Unknown | 18       | 6.16%   |
| Btrfs   | 10       | 3.42%   |
| Zfs     | 4        | 1.37%   |
| Xfs     | 3        | 1.03%   |
| Ext2    | 2        | 0.68%   |
| Ext3    | 1        | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 164      | 56.94%  |
| GPT     | 72       | 25%     |
| MBR     | 52       | 18.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 235      | 81.6%   |
| Yes       | 53       | 18.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 176      | 61.11%  |
| Yes       | 112      | 38.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 82       | 29.18%  |
| ASUSTek Computer    | 81       | 28.83%  |
| MSI                 | 45       | 16.01%  |
| Hewlett-Packard     | 17       | 6.05%   |
| ASRock              | 17       | 6.05%   |
| Biostar             | 10       | 3.56%   |
| Dell                | 6        | 2.14%   |
| Fujitsu             | 5        | 1.78%   |
| Lenovo              | 4        | 1.42%   |
| Pegatron            | 2        | 0.71%   |
| Intel               | 2        | 0.71%   |
| Supermicro          | 1        | 0.36%   |
| Sapphire            | 1        | 0.36%   |
| NCR                 | 1        | 0.36%   |
| Medion              | 1        | 0.36%   |
| Inventec            | 1        | 0.36%   |
| Foxconn             | 1        | 0.36%   |
| ECS                 | 1        | 0.36%   |
| Apple               | 1        | 0.36%   |
| Acer                | 1        | 0.36%   |
| Unknown             | 1        | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME A320M-K       | 13       | 4.63%   |
| ASUS All Series          | 10       | 3.56%   |
| MSI MS-7309              | 5        | 1.78%   |
| Gigabyte B450M DS3H      | 5        | 1.78%   |
| MSI MS-7641              | 4        | 1.42%   |
| Gigabyte H61M-S2PV       | 4        | 1.42%   |
| Biostar A320MH           | 4        | 1.42%   |
| MSI MS-7788              | 3        | 1.07%   |
| MSI MS-7721              | 3        | 1.07%   |
| MSI MS-7597              | 3        | 1.07%   |
| ASUS H110M-R             | 3        | 1.07%   |
| MSI MS-7C84              | 2        | 0.71%   |
| MSI MS-7C02              | 2        | 0.71%   |
| MSI MS-7786              | 2        | 0.71%   |
| MSI MS-7693              | 2        | 0.71%   |
| MSI MS-7623              | 2        | 0.71%   |
| MSI MS-7592              | 2        | 0.71%   |
| MSI MS-7529              | 2        | 0.71%   |
| HP Z800 Workstation      | 2        | 0.71%   |
| HP Z440 Workstation      | 2        | 0.71%   |
| HP ProDesk 600 G1 TWR    | 2        | 0.71%   |
| HP Compaq 6200 Pro MT PC | 2        | 0.71%   |
| Gigabyte Z77X-UD5H       | 2        | 0.71%   |
| Gigabyte P31-DS3L        | 2        | 0.71%   |
| Gigabyte GB-BMCE-4500C   | 2        | 0.71%   |
| Gigabyte GA-890GPA-UD3H  | 2        | 0.71%   |
| Gigabyte F2A68HM-S1      | 2        | 0.71%   |
| Gigabyte EX58-UD5        | 2        | 0.71%   |
| Gigabyte B450M S2H       | 2        | 0.71%   |
| Gigabyte B360M-DS3H      | 2        | 0.71%   |
| Gigabyte A320M-H         | 2        | 0.71%   |
| Gigabyte 970A-DS3P       | 2        | 0.71%   |
| Dell OptiPlex 755        | 2        | 0.71%   |
| Biostar TB250-BTC        | 2        | 0.71%   |
| ASUS M4A89GTD-PRO/USB3   | 2        | 0.71%   |
| ASUS A68HM-K             | 2        | 0.71%   |
| ASUS A58M-K              | 2        | 0.71%   |
| Supermicro X8SIL         | 1        | 0.36%   |
| Sapphire PI-AM3RS785G    | 1        | 0.36%   |
| Pegatron HPE-540ch       | 1        | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 15       | 5.34%   |
| ASUS All                | 10       | 3.56%   |
| HP Compaq               | 9        | 3.2%    |
| Gigabyte B450M          | 7        | 2.49%   |
| ASUS ROG                | 6        | 2.14%   |
| MSI MS-7309             | 5        | 1.78%   |
| Fujitsu ESPRIMO         | 5        | 1.78%   |
| Dell OptiPlex           | 5        | 1.78%   |
| MSI MS-7641             | 4        | 1.42%   |
| Lenovo ThinkCentre      | 4        | 1.42%   |
| Gigabyte H61M-S2PV      | 4        | 1.42%   |
| Biostar A320MH          | 4        | 1.42%   |
| MSI MS-7788             | 3        | 1.07%   |
| MSI MS-7721             | 3        | 1.07%   |
| MSI MS-7597             | 3        | 1.07%   |
| Gigabyte X570           | 3        | 1.07%   |
| Gigabyte B450           | 3        | 1.07%   |
| ASUS TUF                | 3        | 1.07%   |
| ASUS P5KPL-AM           | 3        | 1.07%   |
| ASUS H110M-R            | 3        | 1.07%   |
| MSI MS-7C84             | 2        | 0.71%   |
| MSI MS-7C02             | 2        | 0.71%   |
| MSI MS-7786             | 2        | 0.71%   |
| MSI MS-7693             | 2        | 0.71%   |
| MSI MS-7623             | 2        | 0.71%   |
| MSI MS-7592             | 2        | 0.71%   |
| MSI MS-7529             | 2        | 0.71%   |
| HP Z800                 | 2        | 0.71%   |
| HP Z440                 | 2        | 0.71%   |
| HP ProDesk              | 2        | 0.71%   |
| Gigabyte Z77X-UD5H      | 2        | 0.71%   |
| Gigabyte P31-DS3L       | 2        | 0.71%   |
| Gigabyte GB-BMCE-4500C  | 2        | 0.71%   |
| Gigabyte GA-890GPA-UD3H | 2        | 0.71%   |
| Gigabyte F2A68HM-S1     | 2        | 0.71%   |
| Gigabyte EX58-UD5       | 2        | 0.71%   |
| Gigabyte B550M          | 2        | 0.71%   |
| Gigabyte B360M-DS3H     | 2        | 0.71%   |
| Gigabyte A320M-H        | 2        | 0.71%   |
| Gigabyte 970A-DS3P      | 2        | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 36       | 12.81%  |
| 2012 | 29       | 10.32%  |
| 2010 | 26       | 9.25%   |
| 2014 | 24       | 8.54%   |
| 2017 | 23       | 8.19%   |
| 2009 | 23       | 8.19%   |
| 2013 | 21       | 7.47%   |
| 2011 | 18       | 6.41%   |
| 2008 | 15       | 5.34%   |
| 2007 | 15       | 5.34%   |
| 2019 | 11       | 3.91%   |
| 2006 | 11       | 3.91%   |
| 2020 | 9        | 3.2%    |
| 2015 | 8        | 2.85%   |
| 2016 | 6        | 2.14%   |
| 2021 | 4        | 1.42%   |
| 2022 | 1        | 0.36%   |
| 2004 | 1        | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 281      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 272      | 96.8%   |
| Enabled  | 9        | 3.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 281      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 79       | 27.43%  |
| 4.01-8.0    | 57       | 19.79%  |
| 3.01-4.0    | 52       | 18.06%  |
| 16.01-24.0  | 45       | 15.63%  |
| 32.01-64.0  | 17       | 5.9%    |
| 1.01-2.0    | 17       | 5.9%    |
| 24.01-32.0  | 7        | 2.43%   |
| 64.01-256.0 | 6        | 2.08%   |
| 0.51-1.0    | 5        | 1.74%   |
| 2.01-3.0    | 3        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 130      | 40.37%  |
| 2.01-3.0   | 66       | 20.5%   |
| 4.01-8.0   | 42       | 13.04%  |
| 0.51-1.0   | 31       | 9.63%   |
| 3.01-4.0   | 30       | 9.32%   |
| 0.01-0.5   | 12       | 3.73%   |
| 8.01-16.0  | 5        | 1.55%   |
| 16.01-24.0 | 4        | 1.24%   |
| 24.01-32.0 | 2        | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 120      | 40.68%  |
| 2       | 89       | 30.17%  |
| 3       | 39       | 13.22%  |
| 4       | 23       | 7.8%    |
| 5       | 11       | 3.73%   |
| 0       | 5        | 1.69%   |
| 7       | 2        | 0.68%   |
| 6       | 2        | 0.68%   |
| Unknown | 2        | 0.68%   |
| 10      | 1        | 0.34%   |
| 8       | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 55.17%  |
| Yes       | 130      | 44.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 280      | 99.64%  |
| No        | 1        | 0.36%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 209      | 74.11%  |
| Yes       | 73       | 25.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 242      | 85.82%  |
| Yes       | 40       | 14.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Serbia  | 281      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Belgrade           | 146      | 48.83%  |
| Novi Sad           | 33       | 11.04%  |
| Niš               | 16       | 5.35%   |
| Kragujevac         | 7        | 2.34%   |
| Subotica           | 6        | 2.01%   |
| Pančevo           | 6        | 2.01%   |
| Zrenjanin          | 5        | 1.67%   |
| Becej              | 4        | 1.34%   |
| Backa Topola       | 4        | 1.34%   |
| Senta              | 3        | 1%      |
| Požarevac         | 3        | 1%      |
| Leskovac           | 3        | 1%      |
| Cuprija            | 3        | 1%      |
| Zvecka             | 2        | 0.67%   |
| Rumenka            | 2        | 0.67%   |
| Ruma               | 2        | 0.67%   |
| Pirot              | 2        | 0.67%   |
| Palanka            | 2        | 0.67%   |
| Obrenovac          | 2        | 0.67%   |
| Novi Knezevac      | 2        | 0.67%   |
| New Belgrade       | 2        | 0.67%   |
| Kraljevo           | 2        | 0.67%   |
| Crvenka            | 2        | 0.67%   |
| Banatsko Novo Selo | 2        | 0.67%   |
| Zajecar            | 1        | 0.33%   |
| Zabari             | 1        | 0.33%   |
| Veliko Orasje      | 1        | 0.33%   |
| Tutin              | 1        | 0.33%   |
| Trstenik           | 1        | 0.33%   |
| Stara Pazova       | 1        | 0.33%   |
| Smederevo          | 1        | 0.33%   |
| Semlin             | 1        | 0.33%   |
| Savski Venac       | 1        | 0.33%   |
| Pukovac            | 1        | 0.33%   |
| Petrovac           | 1        | 0.33%   |
| Odzaci             | 1        | 0.33%   |
| Novi Karlovci      | 1        | 0.33%   |
| Loznica            | 1        | 0.33%   |
| Lebane             | 1        | 0.33%   |
| Kruševac          | 1        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 115      | 202    | 23.52%  |
| Seagate                     | 59       | 88     | 12.07%  |
| Kingston                    | 58       | 84     | 11.86%  |
| Toshiba                     | 50       | 71     | 10.22%  |
| Samsung Electronics         | 45       | 76     | 9.2%    |
| Hitachi                     | 24       | 38     | 4.91%   |
| SanDisk                     | 14       | 16     | 2.86%   |
| Patriot                     | 14       | 16     | 2.86%   |
| SPCC                        | 13       | 21     | 2.66%   |
| Biostar                     | 13       | 15     | 2.66%   |
| Maxtor                      | 11       | 11     | 2.25%   |
| Gigabyte Technology         | 11       | 13     | 2.25%   |
| Transcend                   | 7        | 8      | 1.43%   |
| Intel                       | 6        | 9      | 1.23%   |
| Crucial                     | 6        | 6      | 1.23%   |
| Apacer                      | 6        | 8      | 1.23%   |
| Silicon Motion              | 4        | 4      | 0.82%   |
| A-DATA Technology           | 3        | 3      | 0.61%   |
| StoreJet                    | 2        | 2      | 0.41%   |
| Phison Electronics          | 2        | 3      | 0.41%   |
| Phison                      | 2        | 9      | 0.41%   |
| Kingston Technology Company | 2        | 3      | 0.41%   |
| HGST                        | 2        | 3      | 0.41%   |
| ExcelStor                   | 2        | 2      | 0.41%   |
| China                       | 2        | 2      | 0.41%   |
| AMD                         | 2        | 2      | 0.41%   |
| Verbatim                    | 1        | 1      | 0.2%    |
| Realtek Semiconductor       | 1        | 1      | 0.2%    |
| QUANTUM                     | 1        | 1      | 0.2%    |
| PNY                         | 1        | 3      | 0.2%    |
| OCZ                         | 1        | 2      | 0.2%    |
| Mushkin                     | 1        | 1      | 0.2%    |
| Lexar                       | 1        | 4      | 0.2%    |
| Leven                       | 1        | 1      | 0.2%    |
| KingDian                    | 1        | 1      | 0.2%    |
| Intenso                     | 1        | 1      | 0.2%    |
| GeIL                        | 1        | 1      | 0.2%    |
| Apple                       | 1        | 1      | 0.2%    |
| ADATA Technology            | 1        | 1      | 0.2%    |
| ADATA SU                    | 1        | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD                      | 17       | 3.05%   |
| Toshiba DT01ACA100 1TB                               | 14       | 2.51%   |
| Kingston SA400S37240G 240GB SSD                      | 12       | 2.15%   |
| Kingston SA400S37480G 480GB SSD                      | 10       | 1.79%   |
| Toshiba DT01ACA050 500GB                             | 9        | 1.61%   |
| Seagate ST1000DM003-1ER162 1TB                       | 7        | 1.25%   |
| Toshiba HDWD110 1TB                                  | 6        | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB                       | 6        | 1.08%   |
| Samsung NVMe SSD Drive 500GB                         | 6        | 1.08%   |
| Patriot Burst 240GB SSD                              | 6        | 1.08%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD                 | 6        | 1.08%   |
| WDC WD5000AAKX-001CA0 500GB                          | 5        | 0.9%    |
| WDC WD3200AAJS-56B4A0 320GB                          | 5        | 0.9%    |
| Toshiba DT01ACA200 2TB                               | 5        | 0.9%    |
| Seagate ST1000DM003-1CH162 1TB                       | 5        | 0.9%    |
| Hitachi HDS721050CLA362 500GB                        | 5        | 0.9%    |
| WDC WD10EZEX-08WN4A0 1TB                             | 4        | 0.72%   |
| WDC WD1003FZEX-00K3CA0 1TB                           | 4        | 0.72%   |
| Toshiba HDWD120 2TB                                  | 4        | 0.72%   |
| SPCC Solid State Disk 256GB                          | 4        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB                      | 4        | 0.72%   |
| Samsung SSD 860 EVO 500GB                            | 4        | 0.72%   |
| Samsung SSD 860 EVO 250GB                            | 4        | 0.72%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                 | 4        | 0.72%   |
| Biostar S100-120GB                                   | 4        | 0.72%   |
| WDC WD3200AAJS-56M0A0 320GB                          | 3        | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB                             | 3        | 0.54%   |
| WDC WD2500BEVS-22UST0 250GB                          | 3        | 0.54%   |
| WDC WD2500AAKX-753CA1 250GB                          | 3        | 0.54%   |
| WDC WD20EFRX-68EUZN0 2TB                             | 3        | 0.54%   |
| WDC WD1600AAJS-00L7A0 160GB                          | 3        | 0.54%   |
| SPCC Solid State Disk 512GB                          | 3        | 0.54%   |
| Seagate ST380815AS 80GB                              | 3        | 0.54%   |
| Seagate ST31000528AS 1TB                             | 3        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                       | 3        | 0.54%   |
| SanDisk SSD PLUS 120GB                               | 3        | 0.54%   |
| SanDisk SDSSDA120G 120GB                             | 3        | 0.54%   |
| Samsung NVMe SSD Drive 1TB                           | 3        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3        | 0.54%   |
| Samsung HD502HJ 500GB                                | 3        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 111      | 194    | 40.07%  |
| Seagate             | 57       | 85     | 20.58%  |
| Toshiba             | 49       | 70     | 17.69%  |
| Hitachi             | 24       | 38     | 8.66%   |
| Samsung Electronics | 18       | 24     | 6.5%    |
| Maxtor              | 11       | 11     | 3.97%   |
| HGST                | 2        | 3      | 0.72%   |
| ExcelStor           | 2        | 2      | 0.72%   |
| QUANTUM             | 1        | 1      | 0.36%   |
| Intenso             | 1        | 1      | 0.36%   |
| Apple               | 1        | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 53       | 77     | 30.29%  |
| Samsung Electronics | 17       | 22     | 9.71%   |
| SPCC                | 13       | 21     | 7.43%   |
| Patriot             | 12       | 14     | 6.86%   |
| SanDisk             | 11       | 13     | 6.29%   |
| Gigabyte Technology | 11       | 13     | 6.29%   |
| Biostar             | 10       | 12     | 5.71%   |
| Transcend           | 7        | 8      | 4%      |
| Intel               | 6        | 9      | 3.43%   |
| Crucial             | 6        | 6      | 3.43%   |
| WDC                 | 5        | 5      | 2.86%   |
| Apacer              | 5        | 7      | 2.86%   |
| A-DATA Technology   | 3        | 3      | 1.71%   |
| StoreJet            | 2        | 2      | 1.14%   |
| China               | 2        | 2      | 1.14%   |
| AMD                 | 2        | 2      | 1.14%   |
| Verbatim            | 1        | 1      | 0.57%   |
| Seagate             | 1        | 1      | 0.57%   |
| PNY                 | 1        | 3      | 0.57%   |
| OCZ                 | 1        | 2      | 0.57%   |
| Mushkin             | 1        | 1      | 0.57%   |
| Lexar               | 1        | 4      | 0.57%   |
| Leven               | 1        | 1      | 0.57%   |
| KingDian            | 1        | 1      | 0.57%   |
| GeIL                | 1        | 1      | 0.57%   |
| ADATA SU            | 1        | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 213      | 430    | 52.46%  |
| SSD     | 146      | 232    | 35.96%  |
| NVMe    | 42       | 68     | 10.34%  |
| Unknown | 5        | 5      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 265      | 657    | 83.33%  |
| NVMe | 42       | 68     | 13.21%  |
| SAS  | 11       | 10     | 3.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 227      | 425    | 61.35%  |
| 0.51-1.0   | 95       | 142    | 25.68%  |
| 1.01-2.0   | 31       | 56     | 8.38%   |
| 3.01-4.0   | 7        | 12     | 1.89%   |
| 2.01-3.0   | 6        | 19     | 1.62%   |
| 4.01-10.0  | 4        | 8      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 70       | 22.95%  |
| 251-500        | 50       | 16.39%  |
| 501-1000       | 41       | 13.44%  |
| 1-20           | 37       | 12.13%  |
| 1001-2000      | 29       | 9.51%   |
| 51-100         | 18       | 5.9%    |
| Unknown        | 18       | 5.9%    |
| 21-50          | 17       | 5.57%   |
| More than 3000 | 14       | 4.59%   |
| 2001-3000      | 11       | 3.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 123      | 39.55%  |
| 21-50          | 39       | 12.54%  |
| 101-250        | 37       | 11.9%   |
| 251-500        | 33       | 10.61%  |
| 51-100         | 23       | 7.4%    |
| Unknown        | 18       | 5.79%   |
| 1001-2000      | 17       | 5.47%   |
| 501-1000       | 13       | 4.18%   |
| 2001-3000      | 5        | 1.61%   |
| More than 3000 | 3        | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB         | 3        | 3      | 6.12%   |
| Seagate ST500DM002-1BD142 500GB     | 2        | 5      | 4.08%   |
| Seagate ST380815AS 80GB             | 2        | 2      | 4.08%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 2      | 4.08%   |
| Intel SSDSC2CW120A3 120GB           | 2        | 2      | 4.08%   |
| WDC WD5002AALX-00J37A0 500GB        | 1        | 1      | 2.04%   |
| WDC WD5000AAKX-603CA0 500GB         | 1        | 1      | 2.04%   |
| WDC WD5000AAKS-65A7B0 500GB         | 1        | 1      | 2.04%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1        | 1      | 2.04%   |
| WDC WD5000AAKS-00TMA0 500GB         | 1        | 1      | 2.04%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1      | 2.04%   |
| WDC WD3200AVVS-63L2B0 320GB         | 1        | 1      | 2.04%   |
| WDC WD3200AVVS-56L2B0 320GB         | 1        | 1      | 2.04%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 2.04%   |
| WDC WD2002FAEX-007BA0 2TB           | 1        | 2      | 2.04%   |
| WDC WD1600AAJS-00L7A0 160GB         | 1        | 1      | 2.04%   |
| WDC WD15EARS-00Z5B1 1TB             | 1        | 1      | 2.04%   |
| WDC WD15EARS-00MVWB0 1TB            | 1        | 1      | 2.04%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 1      | 2.04%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 1      | 2.04%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1      | 2.04%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1      | 2.04%   |
| WDC WD10EALX-009BA0 1TB             | 1        | 2      | 2.04%   |
| WDC WD10EADS-00M2B0 1TB             | 1        | 2      | 2.04%   |
| WDC WD1001FALS-00J7B1 1TB           | 1        | 1      | 2.04%   |
| Toshiba MG03ACA200 2TB              | 1        | 1      | 2.04%   |
| Toshiba DT01ACA100 1TB              | 1        | 1      | 2.04%   |
| SPCC Solid State Disk 120GB         | 1        | 1      | 2.04%   |
| Seagate STM3250318AS 250GB          | 1        | 2      | 2.04%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 1      | 2.04%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 1      | 2.04%   |
| Samsung Electronics HD753LJ 752GB   | 1        | 2      | 2.04%   |
| Samsung Electronics HD154UI 1TB     | 1        | 1      | 2.04%   |
| Samsung Electronics HD080HJ 80GB    | 1        | 1      | 2.04%   |
| Samsung Electronics HD040GJ/ 40GB   | 1        | 1      | 2.04%   |
| Maxtor STM380211AS 80GB             | 1        | 1      | 2.04%   |
| Maxtor STM3250310AS 250GB           | 1        | 1      | 2.04%   |
| Maxtor STM3160811AS 160GB           | 1        | 1      | 2.04%   |
| Maxtor 6Y160P0 163GB                | 1        | 1      | 2.04%   |
| Kingston SA400S37 120GB SSD         | 1        | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 26     | 43.48%  |
| Seagate             | 8        | 12     | 17.39%  |
| Samsung Electronics | 5        | 6      | 10.87%  |
| Maxtor              | 4        | 4      | 8.7%    |
| Toshiba             | 2        | 2      | 4.35%   |
| Intel               | 2        | 2      | 4.35%   |
| Hitachi             | 2        | 2      | 4.35%   |
| SPCC                | 1        | 1      | 2.17%   |
| Kingston            | 1        | 1      | 2.17%   |
| Crucial             | 1        | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 26     | 50%     |
| Seagate             | 8        | 12     | 20%     |
| Samsung Electronics | 4        | 5      | 10%     |
| Maxtor              | 4        | 4      | 10%     |
| Toshiba             | 2        | 2      | 5%      |
| Hitachi             | 2        | 2      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 51     | 84.62%  |
| SSD  | 6        | 6      | 15.38%  |

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
| Detected | 175      | 467    | 57.19%  |
| Works    | 92       | 211    | 30.07%  |
| Malfunc  | 39       | 57     | 12.75%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 147      | 40.61%  |
| AMD                          | 112      | 30.94%  |
| Nvidia                       | 20       | 5.52%   |
| Samsung Electronics          | 18       | 4.97%   |
| JMicron Technology           | 18       | 4.97%   |
| Marvell Technology Group     | 8        | 2.21%   |
| Kingston Technology Company  | 8        | 2.21%   |
| ASMedia Technology           | 7        | 1.93%   |
| Silicon Motion               | 5        | 1.38%   |
| VIA Technologies             | 4        | 1.1%    |
| SanDisk                      | 4        | 1.1%    |
| Phison Electronics           | 4        | 1.1%    |
| LSI Logic / Symbios Logic    | 2        | 0.55%   |
| Toshiba America Info Systems | 1        | 0.28%   |
| Shenzhen Longsys Electronics | 1        | 0.28%   |
| Realtek Semiconductor        | 1        | 0.28%   |
| Broadcom / LSI               | 1        | 0.28%   |
| ADATA Technology             | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 70       | 14.2%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 24       | 4.87%   |
| AMD FCH SATA Controller D                                                               | 23       | 4.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 4.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 3.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 2.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 2.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 2.64%   |
| Nvidia MCP61 SATA Controller                                                            | 12       | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 12       | 2.43%   |
| Nvidia MCP61 IDE                                                                        | 11       | 2.23%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 11       | 2.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 1.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.42%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 1.42%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.22%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 6        | 1.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1.01%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 1.01%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.81%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.81%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.81%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.81%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.81%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.61%   |
| JMicron JMB361 AHCI/IDE                                                                 | 3        | 0.61%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.61%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 207      | 57.66%  |
| IDE  | 100      | 27.86%  |
| NVMe | 42       | 11.7%   |
| RAID | 7        | 1.95%   |
| SCSI | 2        | 0.56%   |
| SAS  | 1        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 150      | 53.38%  |
| AMD    | 131      | 46.62%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 9        | 3.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.78%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 1.78%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 1.78%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 4        | 1.42%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 1.42%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 4        | 1.42%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.42%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 3        | 1.07%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.07%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 3        | 1.07%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.07%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 1.07%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3        | 1.07%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.07%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.07%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.07%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.07%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.07%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.07%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.07%   |
| AMD Phenom II X4 965 Processor              | 3        | 1.07%   |
| AMD Phenom II X4 945 Processor              | 3        | 1.07%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.07%   |
| AMD Athlon X4 750K Quad Core Processor      | 3        | 1.07%   |
| AMD A4-4020 APU with Radeon HD Graphics     | 3        | 1.07%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 2        | 0.71%   |
| Intel Xeon CPU E5-1630 v3 @ 3.70GHz         | 2        | 0.71%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 0.71%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 0.71%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.71%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 0.71%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 2        | 0.71%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 0.71%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.71%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.71%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.71%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 38       | 13.52%  |
| Intel Core i5           | 29       | 10.32%  |
| Intel Core i3           | 27       | 9.61%   |
| Intel Core i7           | 20       | 7.12%   |
| Intel Core 2 Duo        | 20       | 7.12%   |
| Intel Celeron           | 12       | 4.27%   |
| AMD Phenom II X4        | 11       | 3.91%   |
| Intel Xeon              | 10       | 3.56%   |
| Intel Pentium Dual-Core | 9        | 3.2%    |
| Intel Pentium           | 8        | 2.85%   |
| AMD Ryzen 3             | 8        | 2.85%   |
| AMD FX                  | 8        | 2.85%   |
| AMD Athlon X4           | 8        | 2.85%   |
| Intel Core 2 Quad       | 7        | 2.49%   |
| AMD Ryzen 7             | 7        | 2.49%   |
| AMD Athlon II X2        | 7        | 2.49%   |
| AMD A4                  | 6        | 2.14%   |
| AMD Ryzen 9             | 5        | 1.78%   |
| AMD Athlon 64 X2        | 5        | 1.78%   |
| AMD Athlon II X4        | 4        | 1.42%   |
| AMD Athlon II X3        | 4        | 1.42%   |
| AMD Athlon              | 3        | 1.07%   |
| Intel Pentium Gold      | 2        | 0.71%   |
| Intel Core 2            | 2        | 0.71%   |
| AMD Sempron             | 2        | 0.71%   |
| AMD Ryzen Threadripper  | 2        | 0.71%   |
| AMD Phenom II X6        | 2        | 0.71%   |
| AMD Phenom              | 2        | 0.71%   |
| AMD A6                  | 2        | 0.71%   |
| AMD A10                 | 2        | 0.71%   |
| Other                   | 1        | 0.36%   |
| Intel Pentium Dual      | 1        | 0.36%   |
| Intel Pentium D         | 1        | 0.36%   |
| Intel Pentium 4         | 1        | 0.36%   |
| AMD Ryzen 5 PRO         | 1        | 0.36%   |
| AMD Ryzen 3 PRO         | 1        | 0.36%   |
| AMD Phenom II X2        | 1        | 0.36%   |
| AMD E2                  | 1        | 0.36%   |
| AMD A8                  | 1        | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 106      | 37.72%  |
| 2       | 102      | 36.3%   |
| 6       | 36       | 12.81%  |
| 1       | 12       | 4.27%   |
| 8       | 9        | 3.2%    |
| 3       | 8        | 2.85%   |
| 12      | 4        | 1.42%   |
| 16      | 2        | 0.71%   |
| 32      | 1        | 0.36%   |
| Unknown | 1        | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 280      | 99.64%  |
| 2      | 1        | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 150      | 53.38%  |
| 2       | 130      | 46.26%  |
| Unknown | 1        | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 277      | 98.58%  |
| Unknown        | 4        | 1.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 20.96%  |
| 0x1067a    | 23       | 7.9%    |
| 0x306c3    | 19       | 6.53%   |
| 0x306a9    | 16       | 5.5%    |
| 0x206a7    | 14       | 4.81%   |
| 0x0800820d | 13       | 4.47%   |
| 0x06001119 | 9        | 3.09%   |
| 0x010000c8 | 8        | 2.75%   |
| 0x906e9    | 7        | 2.41%   |
| 0x6fd      | 7        | 2.41%   |
| 0x08101016 | 7        | 2.41%   |
| 0x506e3    | 6        | 2.06%   |
| 0x106e5    | 6        | 2.06%   |
| 0x08701021 | 6        | 2.06%   |
| 0x08108109 | 6        | 2.06%   |
| 0x906ea    | 5        | 1.72%   |
| 0x10676    | 5        | 1.72%   |
| 0x06003106 | 5        | 1.72%   |
| 0x906eb    | 4        | 1.37%   |
| 0x6fb      | 4        | 1.37%   |
| 0x08701013 | 4        | 1.37%   |
| 0x010000db | 4        | 1.37%   |
| 0x08001138 | 3        | 1.03%   |
| 0x08001137 | 3        | 1.03%   |
| 0x06000852 | 3        | 1.03%   |
| 0x906c0    | 2        | 0.69%   |
| 0x206c2    | 2        | 0.69%   |
| 0x106a4    | 2        | 0.69%   |
| 0x0a50000c | 2        | 0.69%   |
| 0x0a201016 | 2        | 0.69%   |
| 0x0700010f | 2        | 0.69%   |
| 0x0700010b | 2        | 0.69%   |
| 0x06000822 | 2        | 0.69%   |
| 0x03000027 | 2        | 0.69%   |
| 0x010000b6 | 2        | 0.69%   |
| 0x01000086 | 2        | 0.69%   |
| 0xf65      | 1        | 0.34%   |
| 0xf41      | 1        | 0.34%   |
| 0xa0671    | 1        | 0.34%   |
| 0x906ed    | 1        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 32       | 11.39%  |
| K10         | 30       | 10.68%  |
| Zen+        | 27       | 9.61%   |
| Haswell     | 24       | 8.54%   |
| KabyLake    | 19       | 6.76%   |
| IvyBridge   | 19       | 6.76%   |
| SandyBridge | 18       | 6.41%   |
| Piledriver  | 18       | 6.41%   |
| Zen         | 14       | 4.98%   |
| Core        | 14       | 4.98%   |
| Zen 3       | 11       | 3.91%   |
| Zen 2       | 9        | 3.2%    |
| Nehalem     | 8        | 2.85%   |
| Skylake     | 7        | 2.49%   |
| K8 Hammer   | 7        | 2.49%   |
| Steamroller | 6        | 2.14%   |
| Jaguar      | 4        | 1.42%   |
| Westmere    | 3        | 1.07%   |
| Tremont     | 2        | 0.71%   |
| NetBurst    | 2        | 0.71%   |
| K10 Llano   | 2        | 0.71%   |
| Silvermont  | 1        | 0.36%   |
| Icelake     | 1        | 0.36%   |
| Excavator   | 1        | 0.36%   |
| Bulldozer   | 1        | 0.36%   |
| Unknown     | 1        | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 137      | 46.6%   |
| Nvidia | 94       | 31.97%  |
| Intel  | 63       | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20       | 6.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9        | 2.94%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 8        | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 2.29%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.29%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 2.29%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 6        | 1.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.63%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.63%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 5        | 1.63%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 5        | 1.63%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 1.31%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 1.31%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.31%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 4        | 1.31%   |
| Intel HD Graphics 530                                                       | 4        | 1.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 1.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 1.31%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 4        | 1.31%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 4        | 1.31%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 1.31%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 0.98%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 0.98%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.98%   |
| Intel HD Graphics 630                                                       | 3        | 0.98%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 3        | 0.98%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 0.98%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 3        | 0.98%   |
| AMD RS880 [Radeon HD 4250]                                                  | 3        | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 0.98%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 3        | 0.98%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 0.98%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 0.98%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 0.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 126      | 44.37%  |
| 1 x Nvidia     | 89       | 31.34%  |
| 1 x Intel      | 54       | 19.01%  |
| 2 x AMD        | 9        | 3.17%   |
| Intel + Nvidia | 2        | 0.7%    |
| Intel + AMD    | 2        | 0.7%    |
| 2 x Nvidia     | 1        | 0.35%   |
| AMD + Nvidia   | 1        | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 223      | 77.7%   |
| Proprietary | 52       | 18.12%  |
| Unknown     | 12       | 4.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 30.27%  |
| 1.01-2.0   | 54       | 18.37%  |
| 0.51-1.0   | 51       | 17.35%  |
| 0.01-0.5   | 44       | 14.97%  |
| 3.01-4.0   | 31       | 10.54%  |
| 7.01-8.0   | 13       | 4.42%   |
| 5.01-6.0   | 6        | 2.04%   |
| 8.01-16.0  | 4        | 1.36%   |
| 2.01-3.0   | 2        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 55       | 20%     |
| Goldstar             | 41       | 14.91%  |
| Dell                 | 31       | 11.27%  |
| Philips              | 27       | 9.82%   |
| Hewlett-Packard      | 16       | 5.82%   |
| BenQ                 | 16       | 5.82%   |
| Acer                 | 15       | 5.45%   |
| ViewSonic            | 13       | 4.73%   |
| Ancor Communications | 12       | 4.36%   |
| AOC                  | 8        | 2.91%   |
| Lenovo               | 6        | 2.18%   |
| LG Electronics       | 5        | 1.82%   |
| Belinea              | 4        | 1.45%   |
| ASUSTek Computer     | 4        | 1.45%   |
| OEM                  | 3        | 1.09%   |
| Unknown              | 2        | 0.73%   |
| Toshiba              | 2        | 0.73%   |
| KTC                  | 2        | 0.73%   |
| HIC                  | 2        | 0.73%   |
| Unknown              | 2        | 0.73%   |
| Vestel Elektronik    | 1        | 0.36%   |
| SUNNY                | 1        | 0.36%   |
| SKY                  | 1        | 0.36%   |
| Panasonic            | 1        | 0.36%   |
| Medion               | 1        | 0.36%   |
| LED                  | 1        | 0.36%   |
| GDH                  | 1        | 0.36%   |
| Fujitsu Siemens      | 1        | 0.36%   |
| Arnos Instruments    | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 1.72%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 477x268mm 21.5-inch              | 4        | 1.38%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 4        | 1.38%   |
| Goldstar W2240 GSM57A0 1920x1080 477x268mm 21.5-inch                  | 4        | 1.38%   |
| Samsung Electronics S22B300 SAM08AA 1920x1080 477x268mm 21.5-inch     | 3        | 1.03%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.03%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 3        | 1.03%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                       | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch  | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 2        | 0.69%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 2        | 0.69%   |
| Samsung Electronics SMBX2440 SAM068B 1920x1080 531x299mm 24.0-inch    | 2        | 0.69%   |
| Samsung Electronics S24R65x SAM1027 1920x1080 527x296mm 23.8-inch     | 2        | 0.69%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.69%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 2        | 0.69%   |
| Samsung Electronics S23C350 SAM0A35 1920x1080 510x287mm 23.0-inch     | 2        | 0.69%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.69%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 0.69%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 2        | 0.69%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 2        | 0.69%   |
| Lenovo L24i-10 LEN65D6 1920x1080 530x300mm 24.0-inch                  | 2        | 0.69%   |
| HIC LCD Monitor HIC0001 1920x1080 256x192mm 12.6-inch                 | 2        | 0.69%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 2        | 0.69%   |
| Goldstar W2252 GSM567E 1680x1050 474x296mm 22.0-inch                  | 2        | 0.69%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.69%   |
| Goldstar 24MP55 GSM5A20 1920x1080 510x290mm 23.1-inch                 | 2        | 0.69%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 2        | 0.69%   |
| Dell S2421HN DEL41F1 1920x1080 527x296mm 23.8-inch                    | 2        | 0.69%   |
| Dell P2717H DEL40F6 1920x1080 598x336mm 27.0-inch                     | 2        | 0.69%   |
| Dell 1908FP DEL4026 1280x1024 376x301mm 19.0-inch                     | 2        | 0.69%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 2        | 0.69%   |
| Acer V196HQL ACR033D 1366x768 410x230mm 18.5-inch                     | 2        | 0.69%   |
| Unknown                                                               | 2        | 0.69%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1        | 0.34%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1        | 0.34%   |
| ViewSonic VX2209 SERIES VSC662E 1920x1080 477x268mm 21.5-inch         | 1        | 0.34%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1        | 0.34%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 0.34%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 509x286mm 23.0-inch         | 1        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 141      | 52.42%  |
| 1280x1024 (SXGA)   | 35       | 13.01%  |
| 1680x1050 (WSXGA+) | 18       | 6.69%   |
| 3840x2160 (4K)     | 16       | 5.95%   |
| 1440x900 (WXGA+)   | 11       | 4.09%   |
| 2560x1440 (QHD)    | 9        | 3.35%   |
| 1366x768 (WXGA)    | 9        | 3.35%   |
| 1920x540           | 5        | 1.86%   |
| 1920x1200 (WUXGA)  | 5        | 1.86%   |
| 1360x768           | 4        | 1.49%   |
| 3840x1080          | 3        | 1.12%   |
| Unknown            | 3        | 1.12%   |
| 2560x1080          | 2        | 0.74%   |
| 1600x900 (HD+)     | 2        | 0.74%   |
| 1600x1200          | 2        | 0.74%   |
| 3440x1440          | 1        | 0.37%   |
| 1834x1031          | 1        | 0.37%   |
| 1400x1050          | 1        | 0.37%   |
| 1024x768 (XGA)     | 1        | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 54       | 19.64%  |
| 23      | 45       | 16.36%  |
| 24      | 36       | 13.09%  |
| Unknown | 24       | 8.73%   |
| 27      | 21       | 7.64%   |
| 17      | 21       | 7.64%   |
| 19      | 20       | 7.27%   |
| 18      | 14       | 5.09%   |
| 22      | 12       | 4.36%   |
| 20      | 5        | 1.82%   |
| 72      | 3        | 1.09%   |
| 34      | 3        | 1.09%   |
| 84      | 2        | 0.73%   |
| 52      | 2        | 0.73%   |
| 31      | 2        | 0.73%   |
| 15      | 2        | 0.73%   |
| 12      | 2        | 0.73%   |
| 65      | 1        | 0.36%   |
| 46      | 1        | 0.36%   |
| 40      | 1        | 0.36%   |
| 33      | 1        | 0.36%   |
| 32      | 1        | 0.36%   |
| 26      | 1        | 0.36%   |
| 25      | 1        | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 94       | 35.88%  |
| 401-500     | 87       | 33.21%  |
| Unknown     | 24       | 9.16%   |
| 301-350     | 22       | 8.4%    |
| 351-400     | 15       | 5.73%   |
| 701-800     | 5        | 1.91%   |
| 1501-2000   | 5        | 1.91%   |
| 1001-1500   | 4        | 1.53%   |
| 601-700     | 3        | 1.15%   |
| 201-300     | 2        | 0.76%   |
| 801-900     | 1        | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 163      | 62.45%  |
| 5/4     | 31       | 11.88%  |
| 16/10   | 29       | 11.11%  |
| Unknown | 22       | 8.43%   |
| 4/3     | 7        | 2.68%   |
| 3/2     | 4        | 1.53%   |
| 21/9    | 3        | 1.15%   |
| 6/5     | 1        | 0.38%   |
| 32/9    | 1        | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 121      | 45.32%  |
| 151-200        | 38       | 14.23%  |
| 141-150        | 32       | 11.99%  |
| Unknown        | 24       | 8.99%   |
| 301-350        | 22       | 8.24%   |
| 251-300        | 9        | 3.37%   |
| More than 1000 | 8        | 3%      |
| 351-500        | 7        | 2.62%   |
| 71-80          | 2        | 0.75%   |
| 501-1000       | 2        | 0.75%   |
| 111-120        | 1        | 0.37%   |
| 101-110        | 1        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 163      | 62.21%  |
| 101-120 | 60       | 22.9%   |
| Unknown | 24       | 9.16%   |
| 1-50    | 7        | 2.67%   |
| 161-240 | 6        | 2.29%   |
| 121-160 | 2        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 234      | 80.97%  |
| 2     | 36       | 12.46%  |
| 0     | 16       | 5.54%   |
| 3     | 3        | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 197      | 55.65%  |
| Intel                             | 61       | 17.23%  |
| Qualcomm Atheros                  | 28       | 7.91%   |
| Nvidia                            | 12       | 3.39%   |
| TP-Link                           | 10       | 2.82%   |
| Qualcomm Atheros Communications   | 9        | 2.54%   |
| Ralink Technology                 | 8        | 2.26%   |
| Broadcom                          | 4        | 1.13%   |
| VIA Technologies                  | 2        | 0.56%   |
| Ralink                            | 2        | 0.56%   |
| OPPO Electronics                  | 2        | 0.56%   |
| MediaTek                          | 2        | 0.56%   |
| Marvell Technology Group          | 2        | 0.56%   |
| Edimax Technology                 | 2        | 0.56%   |
| ZyXEL Communications              | 1        | 0.28%   |
| Xiaomi                            | 1        | 0.28%   |
| Texas Instruments                 | 1        | 0.28%   |
| Sundance Technology Inc / IC Plus | 1        | 0.28%   |
| Sigma Designs                     | 1        | 0.28%   |
| NetGear                           | 1        | 0.28%   |
| LSI                               | 1        | 0.28%   |
| DisplayLink                       | 1        | 0.28%   |
| D-Link System                     | 1        | 0.28%   |
| D-Link                            | 1        | 0.28%   |
| ASUSTek Computer                  | 1        | 0.28%   |
| ASIX Electronics                  | 1        | 0.28%   |
| ADMtek                            | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 167      | 44.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11       | 2.91%   |
| Intel I211 Gigabit Network Connection                                         | 10       | 2.65%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 2.12%   |
| Qualcomm Atheros AR9271 802.11n                                               | 7        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                                          | 7        | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 1.59%   |
| Nvidia MCP61 Ethernet                                                         | 6        | 1.59%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 5        | 1.32%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 4        | 1.06%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 4        | 1.06%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 4        | 1.06%   |
| Intel Ethernet Connection I217-LM                                             | 4        | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 0.79%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3        | 0.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 3        | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 3        | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3        | 0.79%   |
| Intel Wireless 8265 / 8275                                                    | 3        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 0.79%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.79%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 3        | 0.79%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2        | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.53%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 2        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.53%   |
| OPPO SDM710-MTP _SN:2396E2D4                                                  | 2        | 0.53%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.53%   |
| Intel Ethernet Controller I225-V                                              | 2        | 0.53%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.53%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros                | 15       | 20.27%  |
| Realtek Semiconductor           | 12       | 16.22%  |
| TP-Link                         | 10       | 13.51%  |
| Intel                           | 10       | 13.51%  |
| Qualcomm Atheros Communications | 9        | 12.16%  |
| Ralink Technology               | 8        | 10.81%  |
| Ralink                          | 2        | 2.7%    |
| Edimax Technology               | 2        | 2.7%    |
| ZyXEL Communications            | 1        | 1.35%   |
| NetGear                         | 1        | 1.35%   |
| MediaTek                        | 1        | 1.35%   |
| D-Link                          | 1        | 1.35%   |
| Broadcom                        | 1        | 1.35%   |
| ASUSTek Computer                | 1        | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 7        | 9.46%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 5        | 6.76%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 6.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 4        | 5.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 4.05%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 4.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3        | 4.05%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 3        | 4.05%   |
| Intel Wireless 8265 / 8275                                                    | 3        | 4.05%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 2.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2        | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 2.7%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 2.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 2.7%    |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 2        | 2.7%    |
| Edimax AC600 USB                                                              | 2        | 2.7%    |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                                    | 1        | 1.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.35%   |
| TP-Link 802.11n NIC                                                           | 1        | 1.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 1.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1        | 1.35%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1        | 1.35%   |
| Ralink RT5372 Wireless Adapter                                                | 1        | 1.35%   |
| Ralink RT3072 Wireless Adapter                                                | 1        | 1.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 1.35%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 1        | 1.35%   |
| Ralink RT2070 Wireless Adapter                                                | 1        | 1.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.35%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 1        | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 1.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 1.35%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 1.35%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                       | 1        | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 1.35%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 1.35%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 1.35%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                            | 1        | 1.35%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1        | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 195      | 66.33%  |
| Intel                             | 56       | 19.05%  |
| Qualcomm Atheros                  | 15       | 5.1%    |
| Nvidia                            | 12       | 4.08%   |
| Broadcom                          | 3        | 1.02%   |
| VIA Technologies                  | 2        | 0.68%   |
| OPPO Electronics                  | 2        | 0.68%   |
| Marvell Technology Group          | 2        | 0.68%   |
| Xiaomi                            | 1        | 0.34%   |
| Sundance Technology Inc / IC Plus | 1        | 0.34%   |
| MediaTek                          | 1        | 0.34%   |
| DisplayLink                       | 1        | 0.34%   |
| D-Link System                     | 1        | 0.34%   |
| ASIX Electronics                  | 1        | 0.34%   |
| ADMtek                            | 1        | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 167      | 55.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 11       | 3.65%   |
| Intel I211 Gigabit Network Connection                                      | 10       | 3.32%   |
| Realtek RTL8125 2.5GbE Controller                                          | 8        | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 8        | 2.66%   |
| Intel Ethernet Connection (2) I219-V                                       | 7        | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 6        | 1.99%   |
| Nvidia MCP61 Ethernet                                                      | 6        | 1.99%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 4        | 1.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 4        | 1.33%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 1.33%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 3        | 1%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3        | 1%      |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 1%      |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1%      |
| Intel 82566DM-2 Gigabit Network Connection                                 | 3        | 1%      |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.66%   |
| OPPO SDM710-MTP _SN:2396E2D4                                               | 2        | 0.66%   |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.66%   |
| Intel Ethernet Controller I225-V                                           | 2        | 0.66%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 0.66%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.33%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 1        | 0.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.33%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.33%   |
| Nvidia MCP73 Ethernet                                                      | 1        | 0.33%   |
| Nvidia MCP65 Ethernet                                                      | 1        | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                           | 1        | 0.33%   |
| Nvidia CK8S Ethernet Controller                                            | 1        | 0.33%   |
| MediaTek File-CD Gadget                                                    | 1        | 0.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 1        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 280      | 78.87%  |
| WiFi     | 73       | 20.56%  |
| Modem    | 2        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 242      | 84.91%  |
| WiFi     | 43       | 15.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 229      | 81.21%  |
| 2     | 45       | 15.96%  |
| 3     | 5        | 1.77%   |
| 5     | 2        | 0.71%   |
| 0     | 1        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 277      | 98.58%  |
| Yes  | 4        | 1.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 19       | 47.5%   |
| Intel                   | 10       | 25%     |
| ASUSTek Computer        | 5        | 12.5%   |
| Lite-On Technology      | 2        | 5%      |
| IMC Networks            | 2        | 5%      |
| Foxconn / Hon Hai       | 1        | 2.5%    |
| Apple                   | 1        | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19       | 47.5%   |
| Intel AX200 Bluetooth                               | 5        | 12.5%   |
| Intel Bluetooth wireless interface                  | 3        | 7.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3        | 7.5%    |
| Lite-On Bluetooth Device                            | 2        | 5%      |
| IMC Networks Bluetooth Radio                        | 2        | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.5%    |
| Intel AX210 Bluetooth                               | 1        | 2.5%    |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 2.5%    |
| ASUS Bluetooth Device                               | 1        | 2.5%    |
| ASUS ASUS USB-BT500                                 | 1        | 2.5%    |
| Apple Bluetooth HCI                                 | 1        | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 166      | 37.73%  |
| Intel                    | 146      | 33.18%  |
| Nvidia                   | 93       | 21.14%  |
| Generalplus Technology   | 4        | 0.91%   |
| Creative Labs            | 4        | 0.91%   |
| C-Media Electronics      | 4        | 0.91%   |
| Focusrite-Novation       | 3        | 0.68%   |
| VIA Technologies         | 2        | 0.45%   |
| RODE Microphones         | 2        | 0.45%   |
| ASUSTek Computer         | 2        | 0.45%   |
| XMOS                     | 1        | 0.23%   |
| Veho                     | 1        | 0.23%   |
| Turtle Beach             | 1        | 0.23%   |
| Syntek                   | 1        | 0.23%   |
| Sony                     | 1        | 0.23%   |
| Razer USA                | 1        | 0.23%   |
| Plantronics              | 1        | 0.23%   |
| Oculus                   | 1        | 0.23%   |
| Native Instruments       | 1        | 0.23%   |
| Micro Star International | 1        | 0.23%   |
| Meizu                    | 1        | 0.23%   |
| M-Audio                  | 1        | 0.23%   |
| Logitech                 | 1        | 0.23%   |
| JMTek                    | 1        | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 25       | 4.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 24       | 4.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 23       | 4.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 23       | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22       | 4.12%   |
| AMD FCH Azalia Controller                                                         | 22       | 4.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 19       | 3.56%   |
| AMD Family 17h/19h HD Audio Controller                                            | 19       | 3.56%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17       | 3.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 16       | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14       | 2.62%   |
| Nvidia MCP61 High Definition Audio                                                | 12       | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 12       | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 1.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 10       | 1.87%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9        | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                        | 9        | 1.69%   |
| Intel 200 Series PCH HD Audio                                                     | 9        | 1.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 9        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8        | 1.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 8        | 1.5%    |
| Nvidia GP104 High Definition Audio Controller                                     | 7        | 1.31%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 1.31%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 7        | 1.31%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6        | 1.12%   |
| Nvidia High Definition Audio Controller                                           | 5        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 0.94%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 5        | 0.94%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                                | 4        | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 0.75%   |
| Generalplus Technology USB Audio Device                                           | 4        | 0.75%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 4        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                          | 4        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 56       | 35.44%  |
| Unknown             | 34       | 21.52%  |
| Samsung Electronics | 11       | 6.96%   |
| Patriot             | 10       | 6.33%   |
| SK hynix            | 6        | 3.8%    |
| Apacer              | 6        | 3.8%    |
| Transcend           | 5        | 3.16%   |
| Crucial             | 5        | 3.16%   |
| Corsair             | 4        | 2.53%   |
| A-DATA Technology   | 3        | 1.9%    |
| GeIL                | 2        | 1.27%   |
| G.Skill             | 2        | 1.27%   |
| Elpida              | 2        | 1.27%   |
| Unknown             | 2        | 1.27%   |
| Unifosa             | 1        | 0.63%   |
| Swissbit            | 1        | 0.63%   |
| Silicon Power       | 1        | 0.63%   |
| Ramos Technology    | 1        | 0.63%   |
| Ramaxel Technology  | 1        | 0.63%   |
| Qimonda             | 1        | 0.63%   |
| Nanya Technology    | 1        | 0.63%   |
| Mushkin             | 1        | 0.63%   |
| Micron Technology   | 1        | 0.63%   |
| Exceleram           | 1        | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 5        | 2.78%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 4        | 2.22%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 3        | 1.67%   |
| Unknown RAM CL19-19-19 D4-2666 8192MB DIMM DDR4 2400MT/s | 3        | 1.67%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 3        | 1.67%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 2133MT/s   | 3        | 1.67%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 3        | 1.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 2        | 1.11%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 1.11%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 2        | 1.11%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 2        | 1.11%   |
| Transcend RAM TS512MLK64V6H 4GB DIMM DDR3 1600MT/s       | 2        | 1.11%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s        | 2        | 1.11%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s     | 2        | 1.11%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 1.11%   |
| Samsung RAM M393B1K70DH0-CH9 8GB DIMM DDR3 1333MT/s      | 2        | 1.11%   |
| Samsung RAM M393B1K70CH0-CH9 8GB DIMM DDR3 1333MT/s      | 2        | 1.11%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 2        | 1.11%   |
| Patriot RAM PSD34G133381 4GB DIMM DDR3 1333MT/s          | 2        | 1.11%   |
| Patriot RAM 3000 C16 Series 16GB DIMM DDR4 3200MT/s      | 2        | 1.11%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 2        | 1.11%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 2        | 1.11%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3               | 2        | 1.11%   |
| Kingston RAM 9905595-010.A00LF 2048MB DIMM DDR3 1600MT/s | 2        | 1.11%   |
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s       | 2        | 1.11%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s    | 2        | 1.11%   |
| Unknown                                                  | 2        | 1.11%   |
| Unknown RAM Module 8GB DIMM DDR 1333MT/s                 | 1        | 0.56%   |
| Unknown RAM Module 512MB DIMM DDR                        | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 667MT/s                      | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s              | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s              | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM                              | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s              | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 50       | 36.5%   |
| DDR4    | 48       | 35.04%  |
| Unknown | 18       | 13.14%  |
| DDR2    | 12       | 8.76%   |
| SDRAM   | 5        | 3.65%   |
| DDR     | 3        | 2.19%   |
| DDR5    | 1        | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 130      | 97.01%  |
| SODIMM  | 3        | 2.24%   |
| FB-DIMM | 1        | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 46       | 29.49%  |
| 8192  | 42       | 26.92%  |
| 2048  | 33       | 21.15%  |
| 16384 | 21       | 13.46%  |
| 1024  | 9        | 5.77%   |
| 32768 | 4        | 2.56%   |
| 512   | 1        | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 29       | 18.24%  |
| 1600    | 26       | 16.35%  |
| 800     | 13       | 8.18%   |
| 3600    | 12       | 7.55%   |
| 2400    | 10       | 6.29%   |
| 2667    | 8        | 5.03%   |
| 3200    | 7        | 4.4%    |
| 2133    | 7        | 4.4%    |
| 667     | 7        | 4.4%    |
| 3400    | 4        | 2.52%   |
| 1867    | 4        | 2.52%   |
| 3466    | 3        | 1.89%   |
| 2666    | 3        | 1.89%   |
| 400     | 3        | 1.89%   |
| 3733    | 2        | 1.26%   |
| 2933    | 2        | 1.26%   |
| 1866    | 2        | 1.26%   |
| 1648    | 2        | 1.26%   |
| 1067    | 2        | 1.26%   |
| Unknown | 2        | 1.26%   |
| 5200    | 1        | 0.63%   |
| 4333    | 1        | 0.63%   |
| 3334    | 1        | 0.63%   |
| 3333    | 1        | 0.63%   |
| 3266    | 1        | 0.63%   |
| 3151    | 1        | 0.63%   |
| 2800    | 1        | 0.63%   |
| 2048    | 1        | 0.63%   |
| 2000    | 1        | 0.63%   |
| 1400    | 1        | 0.63%   |
| 1066    | 1        | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 8        | 57.14%  |
| Canon                 | 3        | 21.43%  |
| Xerox                 | 1        | 7.14%   |
| Samsung Electronics   | 1        | 7.14%   |
| Lexmark International | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155                 | 1        | 7.14%   |
| Samsung SCX-3400 Series                    | 1        | 7.14%   |
| Lexmark International InkJet Color Printer | 1        | 7.14%   |
| HP LaserJet P2015 series                   | 1        | 7.14%   |
| HP LaserJet P2014                          | 1        | 7.14%   |
| HP LaserJet P1005                          | 1        | 7.14%   |
| HP LaserJet M101-M106                      | 1        | 7.14%   |
| HP LaserJet CP 1025                        | 1        | 7.14%   |
| HP LaserJet 1200                           | 1        | 7.14%   |
| HP LaserJet 1018                           | 1        | 7.14%   |
| HP LaserJet 1010                           | 1        | 7.14%   |
| Canon LBP810                               | 1        | 7.14%   |
| Canon LBP2900                              | 1        | 7.14%   |
| Canon CanoScan LiDE 300                    | 1        | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 4        | 57.14%  |
| Ultima Electronics | 1        | 14.29%  |
| Mustek Systems     | 1        | 14.29%  |
| Hewlett-Packard    | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 100                                                               | 2        | 28.57%  |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 14.29%  |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1        | 14.29%  |
| HP ScanJet 2200c                                                                      | 1        | 14.29%  |
| Canon CanoScan N1240U/LiDE 30                                                         | 1        | 14.29%  |
| Canon CanoScan LiDE 120                                                               | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 19       | 42.22%  |
| KYE Systems (Mouse Systems) | 7        | 15.56%  |
| Microdia                    | 5        | 11.11%  |
| Realtek Semiconductor       | 2        | 4.44%   |
| Hewlett-Packard             | 2        | 4.44%   |
| Aveo Technology             | 2        | 4.44%   |
| Z-Star Microelectronics     | 1        | 2.22%   |
| Sony                        | 1        | 2.22%   |
| Nokia Mobile Phones         | 1        | 2.22%   |
| Cubeternet                  | 1        | 2.22%   |
| Chicony Electronics         | 1        | 2.22%   |
| Asuscom Network             | 1        | 2.22%   |
| Arkmicro Technologies       | 1        | 2.22%   |
| Apple                       | 1        | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 5        | 11.11%  |
| Microdia Camera                                 | 4        | 8.89%   |
| Logitech Webcam C170                            | 4        | 8.89%   |
| KYE Systems (Mouse Systems) FaceCam 1000X       | 3        | 6.67%   |
| Realtek NexiGo N660P FHD Webcam                 | 2        | 4.44%   |
| Logitech Webcam C200                            | 2        | 4.44%   |
| Logitech QuickCam Orbit/Sphere AF               | 2        | 4.44%   |
| Logitech QuickCam Communicate MP/S5500          | 2        | 4.44%   |
| Logitech BRIO Ultra HD Webcam                   | 2        | 4.44%   |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam | 2        | 4.44%   |
| HP HD-4110 Webcam                               | 2        | 4.44%   |
| Z-Star Venus USB2.0 Camera                      | 1        | 2.22%   |
| Sony CEVCECM                                    | 1        | 2.22%   |
| Nokia Mobile Phones Lumia 640 Phone             | 1        | 2.22%   |
| Microdia Webcam Vitade AF                       | 1        | 2.22%   |
| Logitech Webcam C310                            | 1        | 2.22%   |
| Logitech HD Webcam C525                         | 1        | 2.22%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320  | 1        | 2.22%   |
| KYE Systems (Mouse Systems) Eye 320             | 1        | 2.22%   |
| Cubeternet WebCam                               | 1        | 2.22%   |
| Chicony WebCam                                  | 1        | 2.22%   |
| Aveo USB2.0 Camera                              | 1        | 2.22%   |
| Aveo Camera                                     | 1        | 2.22%   |
| Asuscom Network Depstech webcam                 | 1        | 2.22%   |
| Arkmicro USB2.0 PC CAMERA                       | 1        | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE                       | 1        | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 9        | 81.82%  |
| Precise Biometrics    | 1        | 9.09%   |
| OmniKey               | 1        | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 9        | 81.82%  |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader | 1        | 9.09%   |
| OmniKey CardMan 3021 / 3121                                | 1        | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 245      | 85.07%  |
| 1     | 40       | 13.89%  |
| 2     | 3        | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 34.09%  |
| Chipcard                 | 9        | 20.45%  |
| Net/wireless             | 7        | 15.91%  |
| Unassigned class         | 2        | 4.55%   |
| Communication controller | 2        | 4.55%   |
| Camera                   | 2        | 4.55%   |
| Storage/ide              | 1        | 2.27%   |
| Sound                    | 1        | 2.27%   |
| Multimedia controller    | 1        | 2.27%   |
| Modem                    | 1        | 2.27%   |
| Fingerprint reader       | 1        | 2.27%   |
| Dvb card                 | 1        | 2.27%   |
| Card reader              | 1        | 2.27%   |

