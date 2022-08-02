Reborn OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Reborn OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Reborn_OS/Desktop/README.md) and [notebooks](/Dist/Reborn_OS/Notebook/README.md).

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

Total: 182

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3410               | Notebook    | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| Biostar       | A320MH                      | Desktop     | [7580882598](https://linux-hardware.org/?probe=7580882598) | Jul 10, 2022 |
| HP            | ProBook 6565b               | Notebook    | [2d35057d85](https://linux-hardware.org/?probe=2d35057d85) | Jul 03, 2022 |
| HP            | ProBook 6565b               | Notebook    | [947c54ac42](https://linux-hardware.org/?probe=947c54ac42) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [58e0a1814b](https://linux-hardware.org/?probe=58e0a1814b) | Apr 21, 2022 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Shuttle       | FZ270                       | Desktop     | [ed3e018227](https://linux-hardware.org/?probe=ed3e018227) | Mar 09, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [5ac6cdc8fb](https://linux-hardware.org/?probe=5ac6cdc8fb) | Feb 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bc31f5f2bd](https://linux-hardware.org/?probe=bc31f5f2bd) | Jan 17, 2022 |
| Dell          | 0V8DVD A01                  | All in one  | [1645dd96fd](https://linux-hardware.org/?probe=1645dd96fd) | Jan 04, 2022 |
| HP            | ProBook 6550b               | Notebook    | [c09879cfcd](https://linux-hardware.org/?probe=c09879cfcd) | Dec 15, 2021 |
| HUAWEI        | MRC-WX0                     | Notebook    | [714f759476](https://linux-hardware.org/?probe=714f759476) | Dec 06, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [7dba1540ad](https://linux-hardware.org/?probe=7dba1540ad) | Dec 06, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [66c592a074](https://linux-hardware.org/?probe=66c592a074) | Nov 05, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [6b0d6d003d](https://linux-hardware.org/?probe=6b0d6d003d) | Nov 03, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [9fd4c9e3a2](https://linux-hardware.org/?probe=9fd4c9e3a2) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de36837a42](https://linux-hardware.org/?probe=de36837a42) | Nov 02, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [fd68d44a6a](https://linux-hardware.org/?probe=fd68d44a6a) | Oct 16, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [409fb80ae5](https://linux-hardware.org/?probe=409fb80ae5) | Sep 10, 2021 |
| Acer          | Aspire V3-111P              | Notebook    | [8c38c04148](https://linux-hardware.org/?probe=8c38c04148) | Sep 05, 2021 |
| Acer          | Aspire V3-111P              | Notebook    | [af61c27b54](https://linux-hardware.org/?probe=af61c27b54) | Sep 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [13aee77624](https://linux-hardware.org/?probe=13aee77624) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [19226582d9](https://linux-hardware.org/?probe=19226582d9) | May 31, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [dd4a0707ba](https://linux-hardware.org/?probe=dd4a0707ba) | May 19, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Dell          | 0200DY A01                  | Desktop     | [426fc0381c](https://linux-hardware.org/?probe=426fc0381c) | May 08, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [58fbf7553b](https://linux-hardware.org/?probe=58fbf7553b) | May 03, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [27595787eb](https://linux-hardware.org/?probe=27595787eb) | Apr 26, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec119e020d](https://linux-hardware.org/?probe=ec119e020d) | Apr 26, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [989604544a](https://linux-hardware.org/?probe=989604544a) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1b1d0bc44f](https://linux-hardware.org/?probe=1b1d0bc44f) | Mar 27, 2021 |
| CyberPower... | Tracer Series               | Notebook    | [295977bfa3](https://linux-hardware.org/?probe=295977bfa3) | Mar 24, 2021 |
| HP            | 3048h                       | Desktop     | [b61eb90220](https://linux-hardware.org/?probe=b61eb90220) | Mar 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [890d530c6a](https://linux-hardware.org/?probe=890d530c6a) | Mar 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0e8f323e0f](https://linux-hardware.org/?probe=0e8f323e0f) | Mar 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a949911df6](https://linux-hardware.org/?probe=a949911df6) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4a76fb93d3](https://linux-hardware.org/?probe=4a76fb93d3) | Mar 16, 2021 |
| Dell          | Latitude E6320              | Notebook    | [9439943a67](https://linux-hardware.org/?probe=9439943a67) | Mar 15, 2021 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [926ae13f69](https://linux-hardware.org/?probe=926ae13f69) | Mar 09, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [1f0a994797](https://linux-hardware.org/?probe=1f0a994797) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6c98f8666d](https://linux-hardware.org/?probe=6c98f8666d) | Feb 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [e6476ce804](https://linux-hardware.org/?probe=e6476ce804) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6042185966](https://linux-hardware.org/?probe=6042185966) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8c4549fed4](https://linux-hardware.org/?probe=8c4549fed4) | Feb 05, 2021 |
| Dell          | Precision M4600             | Notebook    | [661670d030](https://linux-hardware.org/?probe=661670d030) | Jan 27, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0bb6c600d0](https://linux-hardware.org/?probe=0bb6c600d0) | Jan 25, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [cb03a43d6b](https://linux-hardware.org/?probe=cb03a43d6b) | Jan 18, 2021 |
| ASUSTek       | Q87M-E                      | Desktop     | [e95dad9e90](https://linux-hardware.org/?probe=e95dad9e90) | Jan 14, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b07052df59](https://linux-hardware.org/?probe=b07052df59) | Jan 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| MSI           | MEG X570 ACE                | Desktop     | [5b061048ce](https://linux-hardware.org/?probe=5b061048ce) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [f50fd232e1](https://linux-hardware.org/?probe=f50fd232e1) | Jan 06, 2021 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3e1cc88a](https://linux-hardware.org/?probe=ed3e1cc88a) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fb77017d74](https://linux-hardware.org/?probe=fb77017d74) | Jan 04, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [a8ba58ce8d](https://linux-hardware.org/?probe=a8ba58ce8d) | Jan 03, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [99c0e6fe8e](https://linux-hardware.org/?probe=99c0e6fe8e) | Jan 03, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [60d4c9b8f1](https://linux-hardware.org/?probe=60d4c9b8f1) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bab82e261e](https://linux-hardware.org/?probe=bab82e261e) | Jan 02, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [253b9e5126](https://linux-hardware.org/?probe=253b9e5126) | Jan 01, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [016282f72d](https://linux-hardware.org/?probe=016282f72d) | Jan 01, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [45b5f0850b](https://linux-hardware.org/?probe=45b5f0850b) | Dec 30, 2020 |
| HP            | Pavilion g7                 | Notebook    | [4df7168c54](https://linux-hardware.org/?probe=4df7168c54) | Dec 27, 2020 |
| HP            | Pavilion g7                 | Notebook    | [e2b98139df](https://linux-hardware.org/?probe=e2b98139df) | Dec 27, 2020 |
| Acer          | Aspire E5-523               | Notebook    | [ff03816a1e](https://linux-hardware.org/?probe=ff03816a1e) | Dec 16, 2020 |
| Lenovo        | ThinkPad E570 20H50048US    | Notebook    | [db0d5b5a47](https://linux-hardware.org/?probe=db0d5b5a47) | Dec 15, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [c537d4854e](https://linux-hardware.org/?probe=c537d4854e) | Dec 14, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [f1f14b545e](https://linux-hardware.org/?probe=f1f14b545e) | Dec 13, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [d0fc564ec7](https://linux-hardware.org/?probe=d0fc564ec7) | Dec 11, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [c5a5070a6f](https://linux-hardware.org/?probe=c5a5070a6f) | Dec 10, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [f5429557cc](https://linux-hardware.org/?probe=f5429557cc) | Dec 10, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [2385d54def](https://linux-hardware.org/?probe=2385d54def) | Dec 09, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [6ea56336d8](https://linux-hardware.org/?probe=6ea56336d8) | Dec 03, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [a4e4cd792d](https://linux-hardware.org/?probe=a4e4cd792d) | Dec 02, 2020 |
| Lenovo        | IdeaPad Y450                | Notebook    | [a5ec379304](https://linux-hardware.org/?probe=a5ec379304) | Dec 01, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [67aeba9d99](https://linux-hardware.org/?probe=67aeba9d99) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y450                | Notebook    | [300a14fb31](https://linux-hardware.org/?probe=300a14fb31) | Nov 29, 2020 |
| HP            | ProBook 640 G5              | Notebook    | [fc9abd07f4](https://linux-hardware.org/?probe=fc9abd07f4) | Nov 20, 2020 |
| Lenovo        | G470 20078                  | Notebook    | [98c4778da6](https://linux-hardware.org/?probe=98c4778da6) | Nov 18, 2020 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [a135ed4b82](https://linux-hardware.org/?probe=a135ed4b82) | Nov 08, 2020 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [151ca5d99e](https://linux-hardware.org/?probe=151ca5d99e) | Nov 08, 2020 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [9153f43376](https://linux-hardware.org/?probe=9153f43376) | Nov 02, 2020 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [d6fd55eee0](https://linux-hardware.org/?probe=d6fd55eee0) | Nov 01, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Lenovo        | ThinkCentre M58 6258WCY     | Desktop     | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| Dell          | Latitude 5500               | Notebook    | [b1f5e9ea7a](https://linux-hardware.org/?probe=b1f5e9ea7a) | Oct 25, 2020 |
| Sony          | VPCEH10EB                   | Notebook    | [167720fe57](https://linux-hardware.org/?probe=167720fe57) | Oct 25, 2020 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [5f4ab6b326](https://linux-hardware.org/?probe=5f4ab6b326) | Oct 18, 2020 |
| Foxconn       | H61S                        | Desktop     | [0fd947c658](https://linux-hardware.org/?probe=0fd947c658) | Oct 12, 2020 |
| Razer         | Blade                       | Notebook    | [14ed46b628](https://linux-hardware.org/?probe=14ed46b628) | Oct 04, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [337abf3073](https://linux-hardware.org/?probe=337abf3073) | Sep 30, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [6141f19045](https://linux-hardware.org/?probe=6141f19045) | Sep 17, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [a34a40a5ff](https://linux-hardware.org/?probe=a34a40a5ff) | Sep 17, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4fcaaadd6e](https://linux-hardware.org/?probe=4fcaaadd6e) | Sep 12, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [e0551a0a1c](https://linux-hardware.org/?probe=e0551a0a1c) | Sep 10, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [69b6d5e2e2](https://linux-hardware.org/?probe=69b6d5e2e2) | Sep 08, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [66006c461d](https://linux-hardware.org/?probe=66006c461d) | Sep 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [524f57a765](https://linux-hardware.org/?probe=524f57a765) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [3fe15728ad](https://linux-hardware.org/?probe=3fe15728ad) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [e3f12cdd9b](https://linux-hardware.org/?probe=e3f12cdd9b) | Sep 05, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [8af1b0565b](https://linux-hardware.org/?probe=8af1b0565b) | Sep 03, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| HP            | 630                         | Notebook    | [baf66f73a2](https://linux-hardware.org/?probe=baf66f73a2) | Aug 14, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [49170a6643](https://linux-hardware.org/?probe=49170a6643) | Aug 12, 2020 |
| HP            | 630                         | Notebook    | [1f0b52b96d](https://linux-hardware.org/?probe=1f0b52b96d) | Aug 12, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [27ed844469](https://linux-hardware.org/?probe=27ed844469) | Aug 08, 2020 |
| MSI           | IONA                        | Desktop     | [0510d0f8ef](https://linux-hardware.org/?probe=0510d0f8ef) | Aug 06, 2020 |
| MSI           | IONA                        | Desktop     | [446e406f22](https://linux-hardware.org/?probe=446e406f22) | Aug 06, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [d40ce43d66](https://linux-hardware.org/?probe=d40ce43d66) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9c79ef0e1c](https://linux-hardware.org/?probe=9c79ef0e1c) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [242b101828](https://linux-hardware.org/?probe=242b101828) | Jul 31, 2020 |
| Toshiba       | Satellite C850-C1S          | Notebook    | [3b431d9c9a](https://linux-hardware.org/?probe=3b431d9c9a) | Jul 31, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [3fea05b48d](https://linux-hardware.org/?probe=3fea05b48d) | Jul 30, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [52b8fcb9b0](https://linux-hardware.org/?probe=52b8fcb9b0) | Jul 26, 2020 |
| Dell          | Latitude E6430              | Notebook    | [d14e88e089](https://linux-hardware.org/?probe=d14e88e089) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [56cc69c796](https://linux-hardware.org/?probe=56cc69c796) | Jun 27, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [3eff281cc0](https://linux-hardware.org/?probe=3eff281cc0) | Jun 27, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [a1aaa82c04](https://linux-hardware.org/?probe=a1aaa82c04) | Jun 25, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [1bab33423f](https://linux-hardware.org/?probe=1bab33423f) | Jun 25, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [9db3e10b4f](https://linux-hardware.org/?probe=9db3e10b4f) | Jun 21, 2020 |
| Lenovo        | ThinkPad T510 4349BS9       | Notebook    | [c525e8d7d2](https://linux-hardware.org/?probe=c525e8d7d2) | May 18, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [acc88c72e9](https://linux-hardware.org/?probe=acc88c72e9) | May 06, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [34b28c7178](https://linux-hardware.org/?probe=34b28c7178) | May 06, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [cd1f7d692d](https://linux-hardware.org/?probe=cd1f7d692d) | May 01, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7f1a8c200a](https://linux-hardware.org/?probe=7f1a8c200a) | Apr 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [ddff2712b8](https://linux-hardware.org/?probe=ddff2712b8) | Apr 17, 2020 |
| Dell          | G7 7588                     | Notebook    | [68c487eb50](https://linux-hardware.org/?probe=68c487eb50) | Apr 15, 2020 |
| Lenovo        | ThinkPad 10 20C10026UK      | Tablet      | [6460dcf515](https://linux-hardware.org/?probe=6460dcf515) | Apr 13, 2020 |
| Gigabyte      | F2A75-D3H                   | Desktop     | [59a8d5230f](https://linux-hardware.org/?probe=59a8d5230f) | Apr 09, 2020 |
| Pegatron      | 2A99                        | Desktop     | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [c27fa8aa9c](https://linux-hardware.org/?probe=c27fa8aa9c) | Apr 06, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [97ffeec17e](https://linux-hardware.org/?probe=97ffeec17e) | Mar 23, 2020 |
| Dell          | Latitude E6410              | Notebook    | [9d64ff0beb](https://linux-hardware.org/?probe=9d64ff0beb) | Mar 22, 2020 |
| Dell          | Inspiron 5421               | Notebook    | [2d8871e6ac](https://linux-hardware.org/?probe=2d8871e6ac) | Mar 19, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aaac6f9d4d](https://linux-hardware.org/?probe=aaac6f9d4d) | Mar 17, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [63b8db155d](https://linux-hardware.org/?probe=63b8db155d) | Mar 02, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [ed0b979970](https://linux-hardware.org/?probe=ed0b979970) | Mar 01, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [85c6480266](https://linux-hardware.org/?probe=85c6480266) | Mar 01, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [0f180375d6](https://linux-hardware.org/?probe=0f180375d6) | Feb 25, 2020 |
| HP            | Pavilion 17                 | Notebook    | [5d3ccb9ed7](https://linux-hardware.org/?probe=5d3ccb9ed7) | Feb 24, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [55c569be56](https://linux-hardware.org/?probe=55c569be56) | Feb 23, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [98ae2a8227](https://linux-hardware.org/?probe=98ae2a8227) | Feb 22, 2020 |
| HP            | Pavilion dm1                | Notebook    | [e2e4a2c41f](https://linux-hardware.org/?probe=e2e4a2c41f) | Feb 13, 2020 |
| HP            | Pavilion 17                 | Notebook    | [26bdca3832](https://linux-hardware.org/?probe=26bdca3832) | Feb 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [48487463eb](https://linux-hardware.org/?probe=48487463eb) | Feb 09, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [b189e00138](https://linux-hardware.org/?probe=b189e00138) | Jan 16, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [ecb6ade802](https://linux-hardware.org/?probe=ecb6ade802) | Jan 16, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [9c202df9eb](https://linux-hardware.org/?probe=9c202df9eb) | Jan 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [12d0a26c62](https://linux-hardware.org/?probe=12d0a26c62) | Jan 12, 2020 |
| HP            | Pavilion 17                 | Notebook    | [baeaa7afdc](https://linux-hardware.org/?probe=baeaa7afdc) | Jan 11, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [3b1545354e](https://linux-hardware.org/?probe=3b1545354e) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [25229b0eaf](https://linux-hardware.org/?probe=25229b0eaf) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [3d68993148](https://linux-hardware.org/?probe=3d68993148) | Jan 08, 2020 |
| Avell High... | G1550 FOX                   | Notebook    | [b2380e6e7a](https://linux-hardware.org/?probe=b2380e6e7a) | Dec 30, 2019 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [64266b67a2](https://linux-hardware.org/?probe=64266b67a2) | Dec 26, 2019 |
| HP            | 82F2 A01                    | Desktop     | [0b8306e086](https://linux-hardware.org/?probe=0b8306e086) | Nov 18, 2019 |
| Dell          | 0773VG A00                  | Desktop     | [adf2d5daca](https://linux-hardware.org/?probe=adf2d5daca) | Oct 31, 2019 |
| Dell          | 0773VG A00                  | Desktop     | [2f3044da6d](https://linux-hardware.org/?probe=2f3044da6d) | Oct 31, 2019 |
| MSI           | C236A WORKSTATION           | Desktop     | [fcc16b2804](https://linux-hardware.org/?probe=fcc16b2804) | Oct 11, 2019 |
| MSI           | C236A WORKSTATION           | Desktop     | [f68bc503a9](https://linux-hardware.org/?probe=f68bc503a9) | Oct 11, 2019 |
| ASUSTek       | X555YI                      | Notebook    | [728d78c48c](https://linux-hardware.org/?probe=728d78c48c) | Sep 25, 2019 |
| Dell          | Inspiron 5520               | Notebook    | [26951086cf](https://linux-hardware.org/?probe=26951086cf) | Aug 29, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2560a1cb4e](https://linux-hardware.org/?probe=2560a1cb4e) | Aug 28, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b013eab87a](https://linux-hardware.org/?probe=b013eab87a) | Aug 27, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [81c929f40d](https://linux-hardware.org/?probe=81c929f40d) | Jan 23, 2019 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [2180eb318a](https://linux-hardware.org/?probe=2180eb318a) | Dec 30, 2018 |
| Lenovo        | G570 20079                  | Notebook    | [b1b5baaf85](https://linux-hardware.org/?probe=b1b5baaf85) | Dec 12, 2018 |
| ASRock        | H97M Pro4                   | Desktop     | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [812afde3d9](https://linux-hardware.org/?probe=812afde3d9) | Nov 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Reborn OS         | 115       | 89.15%  |
| Reborn OS Rolling | 14        | 10.85%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Reborn OS | 129       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.9.14-arch1-1       | 8         | 5.84%   |
| 5.9.1-arch1-1        | 4         | 2.92%   |
| 5.7.12-arch1-1       | 4         | 2.92%   |
| 5.5.9-arch1-2        | 4         | 2.92%   |
| 5.10.3-arch1-1       | 4         | 2.92%   |
| 5.9.10-arch1-1       | 3         | 2.19%   |
| 5.8.5-arch1-1        | 3         | 2.19%   |
| 5.5.2-arch1-1        | 3         | 2.19%   |
| 5.4.10-arch1-1       | 3         | 2.19%   |
| 5.9.13-arch1-1       | 2         | 1.46%   |
| 5.9.11-arch2-1       | 2         | 1.46%   |
| 5.8.7-arch1-1        | 2         | 1.46%   |
| 5.7.11-arch1-1       | 2         | 1.46%   |
| 5.7.10-arch1-1       | 2         | 1.46%   |
| 5.6.4-arch1-1        | 2         | 1.46%   |
| 5.6.3-arch1-1        | 2         | 1.46%   |
| 5.2.9-arch1-1-ARCH   | 2         | 1.46%   |
| 5.16.9-arch1-1       | 2         | 1.46%   |
| 5.16.12-arch1-1      | 2         | 1.46%   |
| 5.14.16-arch1-1      | 2         | 1.46%   |
| 5.11.7-arch1-1       | 2         | 1.46%   |
| 5.11.6-arch1-1       | 2         | 1.46%   |
| 5.11.1-arch1-1       | 2         | 1.46%   |
| 5.10.4-arch2-1       | 2         | 1.46%   |
| 5.10.13-arch1-1      | 2         | 1.46%   |
| 5.9.6-arch1-1        | 1         | 0.73%   |
| 5.9.3-arch1-1        | 1         | 0.73%   |
| 5.9.2-zen1-1-zen     | 1         | 0.73%   |
| 5.9.2-arch1-1        | 1         | 0.73%   |
| 5.9.12-arch1-1       | 1         | 0.73%   |
| 5.9.10-zen1-1-zen    | 1         | 0.73%   |
| 5.8.8-arch1-1        | 1         | 0.73%   |
| 5.8.6-arch1-1        | 1         | 0.73%   |
| 5.8.14-arch1-1       | 1         | 0.73%   |
| 5.8.13-arch1-1       | 1         | 0.73%   |
| 5.8.12-arch1-1       | 1         | 0.73%   |
| 5.8.1-arch1-1        | 1         | 0.73%   |
| 5.7.8-arch1-1        | 1         | 0.73%   |
| 5.7.6-arch1-1-custom | 1         | 0.73%   |
| 5.7.6-arch1-1        | 1         | 0.73%   |
| 5.7.5-arch1-1        | 1         | 0.73%   |
| 5.6.6-arch1-1        | 1         | 0.73%   |
| 5.6.2-arch1-2        | 1         | 0.73%   |
| 5.6.13-arch1-1       | 1         | 0.73%   |
| 5.6.10-arch1-1       | 1         | 0.73%   |
| 5.5.5-arch1-1        | 1         | 0.73%   |
| 5.5.11-arch1-1       | 1         | 0.73%   |
| 5.4.8-arch1-1        | 1         | 0.73%   |
| 5.4.78-1-lts         | 1         | 0.73%   |
| 5.4.77-1-lts         | 1         | 0.73%   |
| 5.4.72-1-lts         | 1         | 0.73%   |
| 5.4.6-arch3-1        | 1         | 0.73%   |
| 5.3.7-arch1-2-ARCH   | 1         | 0.73%   |
| 5.3.5-arch1-1-ARCH   | 1         | 0.73%   |
| 5.3.11-arch1-1       | 1         | 0.73%   |
| 5.3.1-arch1-1-ARCH   | 1         | 0.73%   |
| 5.18.9-arch1-1       | 1         | 0.73%   |
| 5.18.8-arch1-1       | 1         | 0.73%   |
| 5.18.12-arch1-1      | 1         | 0.73%   |
| 5.16.0-zen1-1-zen    | 1         | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 8         | 5.88%   |
| 5.9.10  | 4         | 2.94%   |
| 5.9.1   | 4         | 2.94%   |
| 5.7.12  | 4         | 2.94%   |
| 5.5.9   | 4         | 2.94%   |
| 5.10.3  | 4         | 2.94%   |
| 5.8.5   | 3         | 2.21%   |
| 5.5.2   | 3         | 2.21%   |
| 5.4.10  | 3         | 2.21%   |
| 5.9.2   | 2         | 1.47%   |
| 5.9.13  | 2         | 1.47%   |
| 5.9.11  | 2         | 1.47%   |
| 5.8.7   | 2         | 1.47%   |
| 5.7.6   | 2         | 1.47%   |
| 5.7.11  | 2         | 1.47%   |
| 5.7.10  | 2         | 1.47%   |
| 5.6.4   | 2         | 1.47%   |
| 5.6.3   | 2         | 1.47%   |
| 5.2.9   | 2         | 1.47%   |
| 5.16.9  | 2         | 1.47%   |
| 5.16.12 | 2         | 1.47%   |
| 5.14.16 | 2         | 1.47%   |
| 5.11.7  | 2         | 1.47%   |
| 5.11.6  | 2         | 1.47%   |
| 5.11.11 | 2         | 1.47%   |
| 5.11.1  | 2         | 1.47%   |
| 5.10.4  | 2         | 1.47%   |
| 5.10.13 | 2         | 1.47%   |
| 5.9.6   | 1         | 0.74%   |
| 5.9.3   | 1         | 0.74%   |
| 5.9.12  | 1         | 0.74%   |
| 5.8.8   | 1         | 0.74%   |
| 5.8.6   | 1         | 0.74%   |
| 5.8.14  | 1         | 0.74%   |
| 5.8.13  | 1         | 0.74%   |
| 5.8.12  | 1         | 0.74%   |
| 5.8.1   | 1         | 0.74%   |
| 5.7.8   | 1         | 0.74%   |
| 5.7.5   | 1         | 0.74%   |
| 5.6.6   | 1         | 0.74%   |
| 5.6.2   | 1         | 0.74%   |
| 5.6.13  | 1         | 0.74%   |
| 5.6.10  | 1         | 0.74%   |
| 5.5.5   | 1         | 0.74%   |
| 5.5.11  | 1         | 0.74%   |
| 5.4.8   | 1         | 0.74%   |
| 5.4.78  | 1         | 0.74%   |
| 5.4.77  | 1         | 0.74%   |
| 5.4.72  | 1         | 0.74%   |
| 5.4.6   | 1         | 0.74%   |
| 5.3.7   | 1         | 0.74%   |
| 5.3.5   | 1         | 0.74%   |
| 5.3.11  | 1         | 0.74%   |
| 5.3.1   | 1         | 0.74%   |
| 5.18.9  | 1         | 0.74%   |
| 5.18.8  | 1         | 0.74%   |
| 5.18.12 | 1         | 0.74%   |
| 5.16.0  | 1         | 0.74%   |
| 5.15.7  | 1         | 0.74%   |
| 5.15.6  | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9     | 25        | 18.66%  |
| 5.10    | 16        | 11.94%  |
| 5.7     | 12        | 8.96%   |
| 5.8     | 11        | 8.21%   |
| 5.11    | 11        | 8.21%   |
| 5.5     | 9         | 6.72%   |
| 5.6     | 8         | 5.97%   |
| 5.4     | 8         | 5.97%   |
| 5.16    | 5         | 3.73%   |
| 5.14    | 5         | 3.73%   |
| 5.3     | 4         | 2.99%   |
| 5.12    | 4         | 2.99%   |
| 4.19    | 4         | 2.99%   |
| 5.18    | 3         | 2.24%   |
| 5.15    | 3         | 2.24%   |
| 5.2     | 2         | 1.49%   |
| 5.13    | 2         | 1.49%   |
| 4.20    | 1         | 0.75%   |
| 4.18    | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 129       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 29        | 22.31%  |
| KDE               | 17        | 13.08%  |
| X-Cinnamon        | 16        | 12.31%  |
| Deepin            | 16        | 12.31%  |
| XFCE              | 14        | 10.77%  |
| KDE5              | 10        | 7.69%   |
| Unknown           | 10        | 7.69%   |
| Budgie            | 5         | 3.85%   |
| LXQt              | 4         | 3.08%   |
| MATE              | 3         | 2.31%   |
| i3                | 3         | 2.31%   |
| Yaru:ubuntu:GNOME | 1         | 0.77%   |
| Enlightenment     | 1         | 0.77%   |
| Cinnamon          | 1         | 0.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 107       | 82.31%  |
| Wayland | 23        | 17.69%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 111       | 85.38%  |
| LightDM | 7         | 5.38%   |
| TDM     | 6         | 4.62%   |
| GDM     | 3         | 2.31%   |
| SDDM    | 2         | 1.54%   |
| XDM     | 1         | 0.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 46        | 35.66%  |
| Unknown | 11        | 8.53%   |
| pt_BR   | 9         | 6.98%   |
| de_DE   | 9         | 6.98%   |
| en_AU   | 8         | 6.2%    |
| es_ES   | 7         | 5.43%   |
| en_GB   | 7         | 5.43%   |
| ru_RU   | 5         | 3.88%   |
| en_CA   | 4         | 3.1%    |
| es_MX   | 3         | 2.33%   |
| pl_PL   | 2         | 1.55%   |
| nl_NL   | 2         | 1.55%   |
| es_AR   | 2         | 1.55%   |
| sv_SE   | 1         | 0.78%   |
| ru_UA   | 1         | 0.78%   |
| pt_PT   | 1         | 0.78%   |
| fr_FR   | 1         | 0.78%   |
| fr_BE   | 1         | 0.78%   |
| fi_FI   | 1         | 0.78%   |
| es_PA   | 1         | 0.78%   |
| es_CL   | 1         | 0.78%   |
| en_PH   | 1         | 0.78%   |
| en_DK   | 1         | 0.78%   |
| el_GR   | 1         | 0.78%   |
| de_CH   | 1         | 0.78%   |
| de_AT   | 1         | 0.78%   |
| cs_CZ   | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 92        | 70.77%  |
| EFI  | 38        | 29.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 102       | 78.46%  |
| Unknown | 11        | 8.46%   |
| Tmpfs   | 9         | 6.92%   |
| Btrfs   | 4         | 3.08%   |
| Xfs     | 3         | 2.31%   |
| Ext3    | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 111       | 86.05%  |
| GPT     | 14        | 10.85%  |
| MBR     | 4         | 3.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 123       | 95.35%  |
| Yes       | 6         | 4.65%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 121       | 93.08%  |
| Yes       | 9         | 6.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 26        | 20.16%  |
| ASUSTek Computer       | 22        | 17.05%  |
| Dell                   | 21        | 16.28%  |
| Hewlett-Packard        | 12        | 9.3%    |
| Gigabyte Technology    | 9         | 6.98%   |
| Acer                   | 9         | 6.98%   |
| ASRock                 | 7         | 5.43%   |
| MSI                    | 6         | 4.65%   |
| Avell High Performance | 2         | 1.55%   |
| Toshiba                | 1         | 0.78%   |
| Sony                   | 1         | 0.78%   |
| Shuttle                | 1         | 0.78%   |
| Razer                  | 1         | 0.78%   |
| Pegatron               | 1         | 0.78%   |
| OEM                    | 1         | 0.78%   |
| Microsoft              | 1         | 0.78%   |
| Medion                 | 1         | 0.78%   |
| Intel                  | 1         | 0.78%   |
| HUAWEI                 | 1         | 0.78%   |
| Huanan                 | 1         | 0.78%   |
| Foxconn                | 1         | 0.78%   |
| Digma                  | 1         | 0.78%   |
| CyberPowerPC           | 1         | 0.78%   |
| Biostar                | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU          | 3         | 2.33%   |
| Dell Inspiron 5520                     | 3         | 2.33%   |
| MSI MS-7721                            | 2         | 1.55%   |
| Dell Latitude E6430                    | 2         | 1.55%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 2         | 1.55%   |
| ASRock X570 Phantom Gaming 4           | 2         | 1.55%   |
| Toshiba Satellite C850-C1S             | 1         | 0.78%   |
| Sony VPCEH10EB                         | 1         | 0.78%   |
| Shuttle SZ270                          | 1         | 0.78%   |
| Razer Blade                            | 1         | 0.78%   |
| Pegatron CQ3476L                       | 1         | 0.78%   |
| OEM G41 775 ICH7 8712                  | 1         | 0.78%   |
| MSI WK711AA-ACB HPE-110ru              | 1         | 0.78%   |
| MSI MS-7C35                            | 1         | 0.78%   |
| MSI MS-7A36                            | 1         | 0.78%   |
| MSI MS-7998                            | 1         | 0.78%   |
| Microsoft Surface Pro 4                | 1         | 0.78%   |
| Medion P961x                           | 1         | 0.78%   |
| Lenovo Z70-80 80FG                     | 1         | 0.78%   |
| Lenovo Yoga Book C930 ZA3S             | 1         | 0.78%   |
| Lenovo Y50-70 20378                    | 1         | 0.78%   |
| Lenovo ThinkPad T510 4349BS9           | 1         | 0.78%   |
| Lenovo ThinkPad T440p 20AWS0Y800       | 1         | 0.78%   |
| Lenovo ThinkPad T410 253725G           | 1         | 0.78%   |
| Lenovo ThinkPad Edge E431 62775AU      | 1         | 0.78%   |
| Lenovo ThinkPad E570 20H50048US        | 1         | 0.78%   |
| Lenovo ThinkPad E490 20N8CTO1WW        | 1         | 0.78%   |
| Lenovo ThinkPad 10 20C10026UK          | 1         | 0.78%   |
| Lenovo ThinkCentre M92 32071F5         | 1         | 0.78%   |
| Lenovo ThinkCentre M91p 0266RZ1        | 1         | 0.78%   |
| Lenovo ThinkCentre M75q-1 11A4001WUS   | 1         | 0.78%   |
| Lenovo ThinkCentre M58 6258WCY         | 1         | 0.78%   |
| Lenovo IdeaPad Y580                    | 1         | 0.78%   |
| Lenovo IdeaPad Y450                    | 1         | 0.78%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 1         | 0.78%   |
| Lenovo IdeaPad S145-15API 81UT         | 1         | 0.78%   |
| Lenovo IdeaPad L340-17API 81LY         | 1         | 0.78%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 0.78%   |
| Lenovo IdeaPad 330-17IKB 81DM          | 1         | 0.78%   |
| Lenovo G570 20079                      | 1         | 0.78%   |
| Lenovo G470 20078                      | 1         | 0.78%   |
| Intel DH55HC AAE70933-501              | 1         | 0.78%   |
| HUAWEI MRC-WX0                         | 1         | 0.78%   |
| Huanan X79-8D VAA31                    | 1         | 0.78%   |
| HP ProBook 6565b                       | 1         | 0.78%   |
| HP ProBook 6550b                       | 1         | 0.78%   |
| HP ProBook 640 G5                      | 1         | 0.78%   |
| HP Pavilion Laptop 15-cw0xxx           | 1         | 0.78%   |
| HP Pavilion g7                         | 1         | 0.78%   |
| HP Pavilion dm1                        | 1         | 0.78%   |
| HP Pavilion Desktop PC 570-p0XX        | 1         | 0.78%   |
| HP Pavilion 17                         | 1         | 0.78%   |
| HP ENVY x360 m6 Convertible            | 1         | 0.78%   |
| HP EliteBook 8460p                     | 1         | 0.78%   |
| HP EliteBook 2560p                     | 1         | 0.78%   |
| HP Compaq 6000 Pro MT PC               | 1         | 0.78%   |
| Gigabyte Z87-HD3                       | 1         | 0.78%   |
| Gigabyte X570 AORUS ELITE              | 1         | 0.78%   |
| Gigabyte H61M-DS2                      | 1         | 0.78%   |
| Gigabyte H110M-S2PT-CF                 | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 10        | 7.75%   |
| Lenovo ThinkPad              | 7         | 5.43%   |
| Acer Aspire                  | 7         | 5.43%   |
| Dell Latitude                | 6         | 4.65%   |
| Dell Inspiron                | 6         | 4.65%   |
| HP Pavilion                  | 5         | 3.88%   |
| Dell OptiPlex                | 5         | 3.88%   |
| ASUS PRIME                   | 5         | 3.88%   |
| Lenovo ThinkCentre           | 4         | 3.1%    |
| HP ProBook                   | 3         | 2.33%   |
| ASUS ROG                     | 3         | 2.33%   |
| ASRock X570                  | 3         | 2.33%   |
| MSI MS-7721                  | 2         | 1.55%   |
| HP EliteBook                 | 2         | 1.55%   |
| ASUS VivoBook                | 2         | 1.55%   |
| Toshiba Satellite            | 1         | 0.78%   |
| Sony VPCEH10EB               | 1         | 0.78%   |
| Shuttle SZ270                | 1         | 0.78%   |
| Razer Blade                  | 1         | 0.78%   |
| Pegatron CQ3476L             | 1         | 0.78%   |
| OEM G41                      | 1         | 0.78%   |
| MSI WK711AA-ACB              | 1         | 0.78%   |
| MSI MS-7C35                  | 1         | 0.78%   |
| MSI MS-7A36                  | 1         | 0.78%   |
| MSI MS-7998                  | 1         | 0.78%   |
| Microsoft Surface            | 1         | 0.78%   |
| Medion P961x                 | 1         | 0.78%   |
| Lenovo Z70-80                | 1         | 0.78%   |
| Lenovo Yoga                  | 1         | 0.78%   |
| Lenovo Y50-70                | 1         | 0.78%   |
| Lenovo G570                  | 1         | 0.78%   |
| Lenovo G470                  | 1         | 0.78%   |
| Intel DH55HC                 | 1         | 0.78%   |
| HUAWEI MRC-WX0               | 1         | 0.78%   |
| Huanan X79-8D                | 1         | 0.78%   |
| HP ENVY                      | 1         | 0.78%   |
| HP Compaq                    | 1         | 0.78%   |
| Gigabyte Z87-HD3             | 1         | 0.78%   |
| Gigabyte X570                | 1         | 0.78%   |
| Gigabyte H61M-DS2            | 1         | 0.78%   |
| Gigabyte H110M-S2PT-CF       | 1         | 0.78%   |
| Gigabyte GA-880GM-UD2H       | 1         | 0.78%   |
| Gigabyte F2A85X-UP4          | 1         | 0.78%   |
| Gigabyte F2A75-D3H           | 1         | 0.78%   |
| Gigabyte EP43-UD3L           | 1         | 0.78%   |
| Gigabyte B450                | 1         | 0.78%   |
| Foxconn H61S                 | 1         | 0.78%   |
| Digma EVE                    | 1         | 0.78%   |
| Dell XPS                     | 1         | 0.78%   |
| Dell Studio                  | 1         | 0.78%   |
| Dell Precision               | 1         | 0.78%   |
| Dell G7                      | 1         | 0.78%   |
| CyberPowerPC Tracer          | 1         | 0.78%   |
| Biostar A320MH               | 1         | 0.78%   |
| Avell High Performance G1550 | 1         | 0.78%   |
| Avell High Performance A62   | 1         | 0.78%   |
| ASUS Z8NA-D6                 | 1         | 0.78%   |
| ASUS X555YI                  | 1         | 0.78%   |
| ASUS X540SA                  | 1         | 0.78%   |
| ASUS UX430UAR                | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 18        | 13.95%  |
| 2012 | 17        | 13.18%  |
| 2018 | 13        | 10.08%  |
| 2013 | 12        | 9.3%    |
| 2011 | 11        | 8.53%   |
| 2020 | 10        | 7.75%   |
| 2016 | 10        | 7.75%   |
| 2009 | 10        | 7.75%   |
| 2010 | 8         | 6.2%    |
| 2014 | 7         | 5.43%   |
| 2017 | 5         | 3.88%   |
| 2015 | 5         | 3.88%   |
| 2008 | 2         | 1.55%   |
| 2021 | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 63        | 48.84%  |
| Desktop     | 59        | 45.74%  |
| Tablet      | 3         | 2.33%   |
| Convertible | 2         | 1.55%   |
| Mini pc     | 1         | 0.78%   |
| All in one  | 1         | 0.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 129       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 42        | 32.06%  |
| 8.01-16.0   | 29        | 22.14%  |
| 16.01-24.0  | 25        | 19.08%  |
| 3.01-4.0    | 19        | 14.5%   |
| 32.01-64.0  | 13        | 9.92%   |
| 2.01-3.0    | 1         | 0.76%   |
| 64.01-256.0 | 1         | 0.76%   |
| 1.01-2.0    | 1         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 59        | 43.7%   |
| 2.01-3.0  | 42        | 31.11%  |
| 3.01-4.0  | 13        | 9.63%   |
| 4.01-8.0  | 12        | 8.89%   |
| 0.51-1.0  | 6         | 4.44%   |
| 8.01-16.0 | 3         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 54.55%  |
| 2      | 38        | 28.79%  |
| 3      | 9         | 6.82%   |
| 4      | 8         | 6.06%   |
| 0      | 2         | 1.52%   |
| 7      | 1         | 0.76%   |
| 6      | 1         | 0.76%   |
| 5      | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 53.85%  |
| Yes       | 60        | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 85.27%  |
| No        | 19        | 14.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 78.29%  |
| No        | 28        | 21.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 55.04%  |
| No        | 58        | 44.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 33        | 25.58%  |
| Germany     | 11        | 8.53%   |
| Brazil      | 10        | 7.75%   |
| Spain       | 8         | 6.2%    |
| Canada      | 7         | 5.43%   |
| UK          | 6         | 4.65%   |
| Russia      | 6         | 4.65%   |
| Australia   | 6         | 4.65%   |
| Netherlands | 5         | 3.88%   |
| Mexico      | 3         | 2.33%   |
| Turkey      | 2         | 1.55%   |
| Thailand    | 2         | 1.55%   |
| Portugal    | 2         | 1.55%   |
| Poland      | 2         | 1.55%   |
| Panama      | 2         | 1.55%   |
| India       | 2         | 1.55%   |
| Greece      | 2         | 1.55%   |
| Estonia     | 2         | 1.55%   |
| Argentina   | 2         | 1.55%   |
| Ukraine     | 1         | 0.78%   |
| Switzerland | 1         | 0.78%   |
| Sweden      | 1         | 0.78%   |
| Philippines | 1         | 0.78%   |
| Malaysia    | 1         | 0.78%   |
| Hungary     | 1         | 0.78%   |
| Finland     | 1         | 0.78%   |
| Egypt       | 1         | 0.78%   |
| Czechia     | 1         | 0.78%   |
| Costa Rica  | 1         | 0.78%   |
| Colombia    | 1         | 0.78%   |
| Chile       | 1         | 0.78%   |
| Benin       | 1         | 0.78%   |
| Belgium     | 1         | 0.78%   |
| Azerbaijan  | 1         | 0.78%   |
| Austria     | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Melbourne      | 3         | 2.26%   |
| Aleksandrov    | 3         | 2.26%   |
| Tres Cantos    | 2         | 1.5%    |
| Toronto        | 2         | 1.5%    |
| Tallinn        | 2         | 1.5%    |
| Sao Paulo      | 2         | 1.5%    |
| Santa Clara    | 2         | 1.5%    |
| Miami          | 2         | 1.5%    |
| Lelystad       | 2         | 1.5%    |
| Cologne        | 2         | 1.5%    |
| Buffalo        | 2         | 1.5%    |
| Athens         | 2         | 1.5%    |
| Zutphen        | 1         | 0.75%   |
| Zabrze         | 1         | 0.75%   |
| Yadrin         | 1         | 0.75%   |
| Wuppertal      | 1         | 0.75%   |
| Winsted        | 1         | 0.75%   |
| Watford        | 1         | 0.75%   |
| Warsaw         | 1         | 0.75%   |
| Villahermosa   | 1         | 0.75%   |
| Verwood        | 1         | 0.75%   |
| Toledo         | 1         | 0.75%   |
| The Hague      | 1         | 0.75%   |
| Szekszárd     | 1         | 0.75%   |
| Sydney         | 1         | 0.75%   |
| Surrey         | 1         | 0.75%   |
| Stuttgart      | 1         | 0.75%   |
| Streatham      | 1         | 0.75%   |
| St Louis       | 1         | 0.75%   |
| Spremberg      | 1         | 0.75%   |
| Southampton    | 1         | 0.75%   |
| Smithfield     | 1         | 0.75%   |
| Si Racha       | 1         | 0.75%   |
| Seville        | 1         | 0.75%   |
| Santiago       | 1         | 0.75%   |
| Salt Lake City | 1         | 0.75%   |
| Roebel         | 1         | 0.75%   |
| Reno           | 1         | 0.75%   |
| Quezon City    | 1         | 0.75%   |
| Queens         | 1         | 0.75%   |
| Purdon         | 1         | 0.75%   |
| Potts Camp     | 1         | 0.75%   |
| Portsmouth     | 1         | 0.75%   |
| Porto Uniao    | 1         | 0.75%   |
| Pont-y-clun    | 1         | 0.75%   |
| Phoenix        | 1         | 0.75%   |
| Perth          | 1         | 0.75%   |
| Orem           | 1         | 0.75%   |
| Novosibirsk    | 1         | 0.75%   |
| North Bay      | 1         | 0.75%   |
| Nijmegen       | 1         | 0.75%   |
| Newport News   | 1         | 0.75%   |
| Newcastle      | 1         | 0.75%   |
| New Orleans    | 1         | 0.75%   |
| New Delhi      | 1         | 0.75%   |
| Mogi Mirim     | 1         | 0.75%   |
| Mexico City    | 1         | 0.75%   |
| Mascouche      | 1         | 0.75%   |
| Madrid         | 1         | 0.75%   |
| Littleton      | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 45     | 19.31%  |
| Samsung Electronics | 29        | 35     | 14.36%  |
| Seagate             | 28        | 36     | 13.86%  |
| Toshiba             | 16        | 18     | 7.92%   |
| Unknown             | 10        | 12     | 4.95%   |
| Kingston            | 9         | 10     | 4.46%   |
| Crucial             | 8         | 9      | 3.96%   |
| SanDisk             | 7         | 9      | 3.47%   |
| Hitachi             | 7         | 7      | 3.47%   |
| Phison              | 6         | 7      | 2.97%   |
| Intel               | 5         | 5      | 2.48%   |
| HGST                | 5         | 5      | 2.48%   |
| ZOTAC               | 2         | 2      | 0.99%   |
| SPCC                | 2         | 3      | 0.99%   |
| SK hynix            | 2         | 2      | 0.99%   |
| PNY                 | 2         | 2      | 0.99%   |
| Patriot             | 2         | 2      | 0.99%   |
| Emtec               | 2         | 3      | 0.99%   |
| Dell                | 2         | 2      | 0.99%   |
| XPG                 | 1         | 1      | 0.5%    |
| Transcend           | 1         | 1      | 0.5%    |
| Phison Electronics  | 1         | 2      | 0.5%    |
| OYUNKEY             | 1         | 1      | 0.5%    |
| OCZ                 | 1         | 2      | 0.5%    |
| Micron Technology   | 1         | 1      | 0.5%    |
| LITEONIT            | 1         | 1      | 0.5%    |
| KIOXIA              | 1         | 1      | 0.5%    |
| KingSpec            | 1         | 1      | 0.5%    |
| JMicron Technology  | 1         | 1      | 0.5%    |
| Hewlett-Packard     | 1         | 2      | 0.5%    |
| Gigabyte Technology | 1         | 2      | 0.5%    |
| Drevo               | 1         | 1      | 0.5%    |
| ASMT                | 1         | 1      | 0.5%    |
| AMD                 | 1         | 1      | 0.5%    |
| addlink             | 1         | 1      | 0.5%    |
| ADATA Technology    | 1         | 1      | 0.5%    |
| A-DATA Technology   | 1         | 1      | 0.5%    |
| Unknown             | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 5         | 2.27%   |
| Samsung SSD 860 EVO 500GB          | 4         | 1.82%   |
| Intel NVMe SSD Drive 512GB         | 4         | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.36%   |
| HGST HTS725050A7E630 500GB         | 3         | 1.36%   |
| WDC WD10JPVT-08A1YT2 1TB           | 2         | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.91%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2         | 0.91%   |
| WDC WD1001FALS-403AA0 1TB          | 2         | 0.91%   |
| Unknown SD/MMC/MS PRO 64GB         | 2         | 0.91%   |
| Toshiba NVMe SSD Drive 512GB       | 2         | 0.91%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.91%   |
| SK hynix NVMe SSD Drive 256GB      | 2         | 0.91%   |
| Seagate ST9500325AS 500GB          | 2         | 0.91%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.91%   |
| Seagate ST3500312CS 500GB          | 2         | 0.91%   |
| Seagate ST2000DM006-2DM164 2TB     | 2         | 0.91%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 0.91%   |
| Seagate Expansion Desk 4TB         | 2         | 0.91%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.91%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.91%   |
| Samsung NVMe SSD Drive 512GB       | 2         | 0.91%   |
| Samsung NVMe SSD Drive 500GB       | 2         | 0.91%   |
| PNY CS900 120GB SSD                | 2         | 0.91%   |
| Phison NVMe SSD Drive 960GB        | 2         | 0.91%   |
| Phison NVMe SSD Drive 240GB        | 2         | 0.91%   |
| Phison NVMe SSD Drive 1TB          | 2         | 0.91%   |
| Kingston SA400S37480G 480GB SSD    | 2         | 0.91%   |
| ZOTAC ZTSSD-S11-120G-P 120GB       | 1         | 0.45%   |
| ZOTAC ZTSSD-A4P-120G               | 1         | 0.45%   |
| XPG NVMe SSD Drive 1TB             | 1         | 0.45%   |
| WDC WDS500G2X0C-00L350 500GB       | 1         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.45%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1         | 0.45%   |
| WDC WD7500LPCX-60HWST0 752GB       | 1         | 0.45%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1         | 0.45%   |
| WDC WD6400AAKS-00A7B2 640GB        | 1         | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.45%   |
| WDC WD5000LPVX-00V0TT0 500GB       | 1         | 0.45%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 0.45%   |
| WDC WD5000AZLX-00JKKA0 500GB       | 1         | 0.45%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1         | 0.45%   |
| WDC WD5000AAKX-753CA1 500GB        | 1         | 0.45%   |
| WDC WD5000AADS-00S9B0 500GB        | 1         | 0.45%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 0.45%   |
| WDC WD3200AAKS-00UU3A0 320GB       | 1         | 0.45%   |
| WDC WD30PURX-64P6ZY0 3TB           | 1         | 0.45%   |
| WDC WD2500JS-00MHB0 250GB          | 1         | 0.45%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1         | 0.45%   |
| WDC WD20EURX-63T0FY0 2TB           | 1         | 0.45%   |
| WDC WD2003FZEX-00SRLA0 2TB         | 1         | 0.45%   |
| WDC WD2003FYPS-27Y2B0 2TB          | 1         | 0.45%   |
| WDC WD15EADS-65P8B1 1TB            | 1         | 0.45%   |
| WDC WD10SPZX-22Z10T0 1TB           | 1         | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 0.45%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1         | 0.45%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1         | 0.45%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 39     | 38.2%   |
| Seagate             | 28        | 36     | 31.46%  |
| Toshiba             | 9         | 10     | 10.11%  |
| Hitachi             | 7         | 7      | 7.87%   |
| HGST                | 5         | 5      | 5.62%   |
| Samsung Electronics | 3         | 3      | 3.37%   |
| Unknown             | 2         | 2      | 2.25%   |
| ASMT                | 1         | 1      | 1.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 23     | 30.77%  |
| Kingston            | 9         | 10     | 13.85%  |
| Crucial             | 7         | 8      | 10.77%  |
| SanDisk             | 6         | 8      | 9.23%   |
| WDC                 | 3         | 3      | 4.62%   |
| ZOTAC               | 2         | 2      | 3.08%   |
| Toshiba             | 2         | 2      | 3.08%   |
| PNY                 | 2         | 2      | 3.08%   |
| Patriot             | 2         | 2      | 3.08%   |
| Transcend           | 1         | 1      | 1.54%   |
| SPCC                | 1         | 2      | 1.54%   |
| OCZ                 | 1         | 2      | 1.54%   |
| LITEONIT            | 1         | 1      | 1.54%   |
| KingSpec            | 1         | 1      | 1.54%   |
| JMicron Technology  | 1         | 1      | 1.54%   |
| Hewlett-Packard     | 1         | 2      | 1.54%   |
| Gigabyte Technology | 1         | 2      | 1.54%   |
| EMTEC               | 1         | 1      | 1.54%   |
| Drevo               | 1         | 1      | 1.54%   |
| AMD                 | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 73        | 103    | 41.71%  |
| SSD     | 55        | 76     | 31.43%  |
| NVMe    | 35        | 42     | 20%     |
| MMC     | 7         | 10     | 4%      |
| Unknown | 5         | 6      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 173    | 67.52%  |
| NVMe | 35        | 42     | 22.29%  |
| SAS  | 9         | 12     | 5.73%   |
| MMC  | 7         | 10     | 4.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 78        | 102    | 54.93%  |
| 0.51-1.0   | 51        | 60     | 35.92%  |
| 1.01-2.0   | 7         | 9      | 4.93%   |
| 3.01-4.0   | 3         | 4      | 2.11%   |
| 2.01-3.0   | 3         | 4      | 2.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 39        | 29.32%  |
| 101-250        | 31        | 23.31%  |
| 501-1000       | 27        | 20.3%   |
| 51-100         | 12        | 9.02%   |
| 1001-2000      | 7         | 5.26%   |
| More than 3000 | 6         | 4.51%   |
| Unknown        | 6         | 4.51%   |
| 2001-3000      | 3         | 2.26%   |
| 21-50          | 2         | 1.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 49        | 36.03%  |
| 21-50     | 35        | 25.74%  |
| 101-250   | 15        | 11.03%  |
| 51-100    | 13        | 9.56%   |
| 251-500   | 8         | 5.88%   |
| 501-1000  | 6         | 4.41%   |
| Unknown   | 6         | 4.41%   |
| 2001-3000 | 3         | 2.21%   |
| 1001-2000 | 1         | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 116       | 202    | 88.55%  |
| Works    | 15        | 35     | 11.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 88        | 55.35%  |
| AMD                          | 33        | 20.75%  |
| Samsung Electronics          | 9         | 5.66%   |
| Phison Electronics           | 8         | 5.03%   |
| Toshiba America Info Systems | 5         | 3.14%   |
| SanDisk                      | 3         | 1.89%   |
| JMicron Technology           | 3         | 1.89%   |
| ADATA Technology             | 3         | 1.89%   |
| SK hynix                     | 2         | 1.26%   |
| Nvidia                       | 1         | 0.63%   |
| Micron/Crucial Technology    | 1         | 0.63%   |
| Micron Technology            | 1         | 0.63%   |
| KIOXIA                       | 1         | 0.63%   |
| ASMedia Technology           | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29        | 15.43%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 3.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 3.19%   |
| Phison E12 NVMe Controller                                                              | 5         | 2.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 2.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 2.66%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 2.13%   |
| Intel SSD 660P Series                                                                   | 3         | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.6%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 1.06%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.06%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 1.06%   |
| JMicron JMB368 IDE controller                                                           | 2         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.06%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.06%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.06%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2         | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.06%   |
| AMD FCH SATA Controller D                                                               | 2         | 1.06%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.53%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.53%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.53%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.53%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.53%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.53%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.53%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.53%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.53%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.53%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 1         | 0.53%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.53%   |
| Intel SSD 600P Series                                                                   | 1         | 0.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.53%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.53%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 100       | 62.5%   |
| NVMe | 34        | 21.25%  |
| IDE  | 19        | 11.88%  |
| RAID | 7         | 4.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 93        | 72.09%  |
| AMD    | 36        | 27.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 4         | 3.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 2.31%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.54%   |
| Intel Core i7-4770S CPU @ 3.10GHz             | 2         | 1.54%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.54%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.54%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.54%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.54%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 1.54%   |
| AMD A4-5300 APU with Radeon HD Graphics       | 2         | 1.54%   |
| AMD A10-5800K APU with Radeon HD Graphics     | 2         | 1.54%   |
| Intel Xeon CPU E5530 @ 2.40GHz                | 1         | 0.77%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz           | 1         | 0.77%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz           | 1         | 0.77%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz           | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.77%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.77%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.77%   |
| Intel Pentium CPU G3258 @ 3.20GHz             | 1         | 0.77%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.77%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.77%   |
| Intel Core i7-6700T CPU @ 2.80GHz             | 1         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.77%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.77%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.77%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.77%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.77%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.77%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.77%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.77%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.77%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.77%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.77%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 0.77%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.77%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.77%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.77%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.77%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 1         | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.77%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 0.77%   |
| Intel Core i5-4570T CPU @ 2.90GHz             | 1         | 0.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.77%   |
| Intel Core i5-3340 CPU @ 3.10GHz              | 1         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 27.69%  |
| Intel Core i7           | 24        | 18.46%  |
| AMD Ryzen 5             | 10        | 7.69%   |
| Intel Core 2 Duo        | 8         | 6.15%   |
| Intel Core i3           | 7         | 5.38%   |
| Intel Celeron           | 7         | 5.38%   |
| AMD Ryzen 7             | 7         | 5.38%   |
| Intel Xeon              | 4         | 3.08%   |
| Intel Pentium           | 4         | 3.08%   |
| AMD FX                  | 3         | 2.31%   |
| Intel Pentium Dual-Core | 2         | 1.54%   |
| AMD Ryzen 3             | 2         | 1.54%   |
| AMD A8                  | 2         | 1.54%   |
| AMD A4                  | 2         | 1.54%   |
| AMD A10                 | 2         | 1.54%   |
| Other                   | 1         | 0.77%   |
| Intel Core m3           | 1         | 0.77%   |
| Intel Atom              | 1         | 0.77%   |
| AMD Ryzen 9             | 1         | 0.77%   |
| AMD Ryzen 5 PRO         | 1         | 0.77%   |
| AMD Phenom II X4        | 1         | 0.77%   |
| AMD E                   | 1         | 0.77%   |
| AMD Athlon II X2        | 1         | 0.77%   |
| AMD A6                  | 1         | 0.77%   |
| AMD A12                 | 1         | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 56        | 43.41%  |
| 4      | 49        | 37.98%  |
| 6      | 13        | 10.08%  |
| 8      | 6         | 4.65%   |
| 1      | 2         | 1.55%   |
| 24     | 1         | 0.78%   |
| 12     | 1         | 0.78%   |
| 3      | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 127       | 98.45%  |
| 2      | 2         | 1.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 86        | 66.67%  |
| 1      | 43        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 92.25%  |
| Unknown        | 10        | 7.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 29.77%  |
| 0x306a9    | 11        | 8.4%    |
| 0x206a7    | 9         | 6.87%   |
| 0x306c3    | 7         | 5.34%   |
| 0x506e3    | 5         | 3.82%   |
| 0x906ea    | 4         | 3.05%   |
| 0x1067a    | 4         | 3.05%   |
| 0x0800820d | 4         | 3.05%   |
| 0x06001119 | 4         | 3.05%   |
| 0x906e9    | 3         | 2.29%   |
| 0x806e9    | 3         | 2.29%   |
| 0x20652    | 3         | 2.29%   |
| 0x806ec    | 2         | 1.53%   |
| 0x806eb    | 2         | 1.53%   |
| 0x40651    | 2         | 1.53%   |
| 0x20655    | 2         | 1.53%   |
| 0x106e5    | 2         | 1.53%   |
| 0x08108109 | 2         | 1.53%   |
| 0x806ea    | 1         | 0.76%   |
| 0x6fb      | 1         | 0.76%   |
| 0x406e3    | 1         | 0.76%   |
| 0x406c3    | 1         | 0.76%   |
| 0x306e4    | 1         | 0.76%   |
| 0x306d4    | 1         | 0.76%   |
| 0x30678    | 1         | 0.76%   |
| 0x106a5    | 1         | 0.76%   |
| 0x10676    | 1         | 0.76%   |
| 0x0a201016 | 1         | 0.76%   |
| 0x0a201009 | 1         | 0.76%   |
| 0x08701021 | 1         | 0.76%   |
| 0x08600102 | 1         | 0.76%   |
| 0x0810100b | 1         | 0.76%   |
| 0x08001138 | 1         | 0.76%   |
| 0x07030106 | 1         | 0.76%   |
| 0x06006704 | 1         | 0.76%   |
| 0x06006113 | 1         | 0.76%   |
| 0x0600081c | 1         | 0.76%   |
| 0x06000817 | 1         | 0.76%   |
| 0x05000119 | 1         | 0.76%   |
| 0x010000c8 | 1         | 0.76%   |
| 0x010000b6 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 15.5%   |
| IvyBridge     | 15        | 11.63%  |
| SandyBridge   | 13        | 10.08%  |
| Zen+          | 11        | 8.53%   |
| Haswell       | 11        | 8.53%   |
| Penryn        | 8         | 6.2%    |
| Skylake       | 7         | 5.43%   |
| Westmere      | 6         | 4.65%   |
| Piledriver    | 6         | 4.65%   |
| Zen 2         | 5         | 3.88%   |
| Zen           | 3         | 2.33%   |
| Silvermont    | 3         | 2.33%   |
| Nehalem       | 3         | 2.33%   |
| Goldmont plus | 3         | 2.33%   |
| Excavator     | 3         | 2.33%   |
| Zen 3         | 2         | 1.55%   |
| Puma          | 2         | 1.55%   |
| K10           | 2         | 1.55%   |
| K10 Llano     | 1         | 0.78%   |
| Goldmont      | 1         | 0.78%   |
| Core          | 1         | 0.78%   |
| CometLake     | 1         | 0.78%   |
| Broadwell     | 1         | 0.78%   |
| Bobcat        | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 67        | 44.97%  |
| Nvidia            | 41        | 27.52%  |
| AMD               | 40        | 26.85%  |
| ASPEED Technology | 1         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 7.79%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 5.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6         | 3.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 2.6%    |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 2.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 2.6%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.95%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3         | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.95%   |
| Intel UHD Graphics 620                                                      | 3         | 1.95%   |
| Intel HD Graphics 530                                                       | 3         | 1.95%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.95%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                   | 3         | 1.95%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.3%    |
| Intel HD Graphics 620                                                       | 2         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.3%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2         | 1.3%    |
| AMD Trinity [Radeon HD 7660D]                                               | 2         | 1.3%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.3%    |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2         | 1.3%    |
| Nvidia TU117M                                                               | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.65%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1         | 0.65%   |
| Nvidia GT218M [NVS 3100M]                                                   | 1         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.65%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.65%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 0.65%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 1         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.65%   |
| Nvidia GM206M [GeForce GTX 965M]                                            | 1         | 0.65%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1         | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 0.65%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.65%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 0.65%   |
| Nvidia GK208M [GeForce GT 730M]                                             | 1         | 0.65%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 0.65%   |
| Nvidia GK104GL [Tesla K10]                                                  | 1         | 0.65%   |
| Nvidia GF119 [NVS 310]                                                      | 1         | 0.65%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.65%   |
| Nvidia GF108GLM [Quadro 1000M]                                              | 1         | 0.65%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.65%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 0.65%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1         | 0.65%   |
| Nvidia G96CM [GeForce GT 130M]                                              | 1         | 0.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 0.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 0.65%   |
| Intel HD Graphics P530                                                      | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 36.43%  |
| 1 x AMD        | 33        | 25.58%  |
| 1 x Nvidia     | 28        | 21.71%  |
| Intel + Nvidia | 12        | 9.3%    |
| Intel + AMD    | 5         | 3.88%   |
| 2 x AMD        | 2         | 1.55%   |
| 3 x Nvidia     | 1         | 0.78%   |
| 1 x ASPEED     | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 112       | 86.15%  |
| Proprietary | 17        | 13.08%  |
| Unknown     | 1         | 0.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 58.14%  |
| 0.51-1.0   | 13        | 10.08%  |
| 1.01-2.0   | 11        | 8.53%   |
| 0.01-0.5   | 10        | 7.75%   |
| 7.01-8.0   | 8         | 6.2%    |
| 3.01-4.0   | 6         | 4.65%   |
| 8.01-16.0  | 3         | 2.33%   |
| 2.01-3.0   | 2         | 1.55%   |
| 5.01-6.0   | 1         | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 16.55%  |
| AU Optronics            | 21        | 15.11%  |
| LG Display              | 15        | 10.79%  |
| Hewlett-Packard         | 8         | 5.76%   |
| BOE                     | 8         | 5.76%   |
| Dell                    | 7         | 5.04%   |
| Chimei Innolux          | 7         | 5.04%   |
| BenQ                    | 6         | 4.32%   |
| Goldstar                | 5         | 3.6%    |
| Acer                    | 5         | 3.6%    |
| Philips                 | 4         | 2.88%   |
| Chi Mei Optoelectronics | 4         | 2.88%   |
| AOC                     | 3         | 2.16%   |
| Ancor Communications    | 3         | 2.16%   |
| Sony                    | 2         | 1.44%   |
| MSI                     | 2         | 1.44%   |
| Vizio                   | 1         | 0.72%   |
| Vestel                  | 1         | 0.72%   |
| Unknown                 | 1         | 0.72%   |
| Sharp                   | 1         | 0.72%   |
| Sceptre Tech            | 1         | 0.72%   |
| Plain Tree Systems      | 1         | 0.72%   |
| ONN                     | 1         | 0.72%   |
| MStar                   | 1         | 0.72%   |
| Microstep               | 1         | 0.72%   |
| Medion                  | 1         | 0.72%   |
| Lenovo                  | 1         | 0.72%   |
| InfoVision              | 1         | 0.72%   |
| Iiyama                  | 1         | 0.72%   |
| GRM                     | 1         | 0.72%   |
| CSO                     | 1         | 0.72%   |
| ASUSTek Computer        | 1         | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 2.7%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 2.03%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 2.03%   |
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch    | 2         | 1.35%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                  | 2         | 1.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 1.35%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 1.35%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                    | 1         | 0.68%   |
| Vestel LCD Monitor 32W_LCD_TV                                            | 1         | 0.68%   |
| Unknown LCD Monitor DAC Moniter 5760x1080                                | 1         | 0.68%   |
| Sony TV SNYF301 1920x1080                                                | 1         | 0.68%   |
| Sony TV *30 SNY7105 3840x2160 952x535mm 43.0-inch                        | 1         | 0.68%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 0.68%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch           | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch     | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 0.68%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 1         | 0.68%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 0.68%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 0.68%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch        | 1         | 0.68%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch        | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC5744 1920x1080 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor S24D300 1920x1080                        | 1         | 0.68%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                        | 1         | 0.68%   |
| Plain Tree Systems TFT19DXP PTS03A0 1280x1024 376x301mm 19.0-inch        | 1         | 0.68%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                 | 1         | 0.68%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                  | 1         | 0.68%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                 | 1         | 0.68%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                                 | 1         | 0.68%   |
| Philips LCD Monitor PHL 276E8V                                           | 1         | 0.68%   |
| ONN onn. TV ONN007D 3840x2160 800x450mm 36.1-inch                        | 1         | 0.68%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 0.68%   |
| MSI Optix MAG24C MSI1462 1920x1080 520x290mm 23.4-inch                   | 1         | 0.68%   |
| MSI MPG341CQR MSI3DA0 3440x1440 797x334mm 34.0-inch                      | 1         | 0.68%   |
| Microstep LCD Monitor Optix MAG24C 3840x1200                             | 1         | 0.68%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch               | 1         | 0.68%   |
| LG Display LCD Monitor LGD05FF 1920x1080 344x194mm 15.5-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 0.68%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 0.68%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 1         | 0.68%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 0.68%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 39.42%  |
| 1366x768 (WXGA)    | 37        | 27.01%  |
| 1600x900 (HD+)     | 8         | 5.84%   |
| 3840x2160 (4K)     | 7         | 5.11%   |
| 1680x1050 (WSXGA+) | 7         | 5.11%   |
| 1440x900 (WXGA+)   | 4         | 2.92%   |
| Unknown            | 4         | 2.92%   |
| 1280x1024 (SXGA)   | 3         | 2.19%   |
| 7680x2160          | 2         | 1.46%   |
| 3440x1440          | 2         | 1.46%   |
| 2560x1440 (QHD)    | 2         | 1.46%   |
| 1920x1200 (WUXGA)  | 2         | 1.46%   |
| 5760x1080          | 1         | 0.73%   |
| 3840x1200          | 1         | 0.73%   |
| 2736x1824          | 1         | 0.73%   |
| 2560x1600          | 1         | 0.73%   |
| 1360x768           | 1         | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 24.82%  |
| 23      | 12        | 8.51%   |
| 14      | 12        | 8.51%   |
| 21      | 10        | 7.09%   |
| Unknown | 9         | 6.38%   |
| 24      | 7         | 4.96%   |
| 17      | 7         | 4.96%   |
| 13      | 7         | 4.96%   |
| 22      | 6         | 4.26%   |
| 27      | 5         | 3.55%   |
| 19      | 5         | 3.55%   |
| 18      | 4         | 2.84%   |
| 54      | 2         | 1.42%   |
| 34      | 2         | 1.42%   |
| 31      | 2         | 1.42%   |
| 20      | 2         | 1.42%   |
| 11      | 2         | 1.42%   |
| 84      | 1         | 0.71%   |
| 72      | 1         | 0.71%   |
| 65      | 1         | 0.71%   |
| 52      | 1         | 0.71%   |
| 49      | 1         | 0.71%   |
| 46      | 1         | 0.71%   |
| 36      | 1         | 0.71%   |
| 33      | 1         | 0.71%   |
| 28      | 1         | 0.71%   |
| 16      | 1         | 0.71%   |
| 12      | 1         | 0.71%   |
| 10      | 1         | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 38.13%  |
| 401-500     | 24        | 17.27%  |
| 501-600     | 21        | 15.11%  |
| 351-400     | 10        | 7.19%   |
| Unknown     | 9         | 6.47%   |
| 201-300     | 6         | 4.32%   |
| 1001-1500   | 6         | 4.32%   |
| 701-800     | 4         | 2.88%   |
| 601-700     | 4         | 2.88%   |
| 1501-2000   | 2         | 1.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 78.46%  |
| 16/10   | 13        | 10%     |
| Unknown | 9         | 6.92%   |
| 5/4     | 3         | 2.31%   |
| 21/9    | 2         | 1.54%   |
| 3/2     | 1         | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 25.36%  |
| 201-250        | 29        | 21.01%  |
| 81-90          | 17        | 12.32%  |
| 151-200        | 10        | 7.25%   |
| Unknown        | 9         | 6.52%   |
| More than 1000 | 7         | 5.07%   |
| 121-130        | 7         | 5.07%   |
| 351-500        | 5         | 3.62%   |
| 301-350        | 5         | 3.62%   |
| 141-150        | 4         | 2.9%    |
| 71-80          | 2         | 1.45%   |
| 51-60          | 2         | 1.45%   |
| 501-1000       | 2         | 1.45%   |
| 61-70          | 1         | 0.72%   |
| 41-50          | 1         | 0.72%   |
| 251-300        | 1         | 0.72%   |
| 111-120        | 1         | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 46        | 33.09%  |
| 51-100        | 45        | 32.37%  |
| 121-160       | 29        | 20.86%  |
| Unknown       | 9         | 6.47%   |
| 1-50          | 6         | 4.32%   |
| 161-240       | 3         | 2.16%   |
| More than 240 | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 112       | 86.15%  |
| 2     | 15        | 11.54%  |
| 0     | 2         | 1.54%   |
| 3     | 1         | 0.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 71        | 36.22%  |
| Intel                             | 62        | 31.63%  |
| Qualcomm Atheros                  | 25        | 12.76%  |
| Broadcom                          | 9         | 4.59%   |
| Ralink Technology                 | 4         | 2.04%   |
| TP-Link                           | 3         | 1.53%   |
| Microsoft                         | 3         | 1.53%   |
| Huawei Technologies               | 3         | 1.53%   |
| Xiaomi                            | 2         | 1.02%   |
| Ralink                            | 2         | 1.02%   |
| Spreadtrum Communications         | 1         | 0.51%   |
| Sierra Wireless                   | 1         | 0.51%   |
| Samsung Electronics               | 1         | 0.51%   |
| Qualcomm Atheros Communications   | 1         | 0.51%   |
| Nvidia                            | 1         | 0.51%   |
| NetXen Incorporated               | 1         | 0.51%   |
| Marvell Technology Group          | 1         | 0.51%   |
| Ericsson Business Mobile Networks | 1         | 0.51%   |
| DisplayLink                       | 1         | 0.51%   |
| Dell                              | 1         | 0.51%   |
| Broadcom Limited                  | 1         | 0.51%   |
| Belkin Components                 | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 48        | 20.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 4.35%   |
| Intel I211 Gigabit Network Connection                                   | 10        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 3.91%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 3.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 2.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.74%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.74%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.74%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                              | 3         | 1.3%    |
| Huawei E353/E3131                                                       | 3         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.87%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.87%   |
| Ralink RT5572 Wireless Adapter                                          | 2         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.87%   |
| Intel Wireless 7265                                                     | 2         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                    | 2         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.43%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.43%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1         | 0.43%   |
| Spreadtrum Unisoc Phone                                                 | 1         | 0.43%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.43%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.43%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.43%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.43%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1         | 0.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.43%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.43%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter    | 1         | 0.43%   |
| Microsoft XBOX ACC                                                      | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 39.62%  |
| Qualcomm Atheros                | 23        | 21.7%   |
| Realtek Semiconductor           | 19        | 17.92%  |
| Broadcom                        | 6         | 5.66%   |
| Ralink Technology               | 4         | 3.77%   |
| TP-Link                         | 3         | 2.83%   |
| Ralink                          | 2         | 1.89%   |
| Microsoft                       | 2         | 1.89%   |
| Sierra Wireless                 | 1         | 0.94%   |
| Qualcomm Atheros Communications | 1         | 0.94%   |
| Marvell Technology Group        | 1         | 0.94%   |
| Broadcom Limited                | 1         | 0.94%   |
| Belkin Components               | 1         | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 8         | 7.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 5.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.67%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 4.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 3.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.74%   |
| Intel Wireless-AC 9260                                                  | 4         | 3.74%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.87%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 1.87%   |
| Ralink RT5572 Wireless Adapter                                          | 2         | 1.87%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.87%   |
| Intel Wireless 7265                                                     | 2         | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.87%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.93%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1         | 0.93%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.93%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.93%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.93%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Microsoft XBOX ACC                                                      | 1         | 0.93%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.93%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.93%   |
| Intel Wireless 7260                                                     | 1         | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.93%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.93%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.93%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.93%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.93%   |
| Broadcom BCM43217 802.11b/g/n                                           | 1         | 0.93%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]  | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 60        | 50%     |
| Intel                     | 40        | 33.33%  |
| Qualcomm Atheros          | 6         | 5%      |
| Huawei Technologies       | 3         | 2.5%    |
| Broadcom                  | 3         | 2.5%    |
| Xiaomi                    | 2         | 1.67%   |
| Spreadtrum Communications | 1         | 0.83%   |
| Samsung Electronics       | 1         | 0.83%   |
| Nvidia                    | 1         | 0.83%   |
| NetXen Incorporated       | 1         | 0.83%   |
| Microsoft                 | 1         | 0.83%   |
| DisplayLink               | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 48        | 39.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 10        | 8.26%   |
| Intel I211 Gigabit Network Connection                                | 10        | 8.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 9         | 7.44%   |
| Intel Ethernet Connection I217-LM                                    | 4         | 3.31%   |
| Intel 82577LM Gigabit Network Connection                             | 3         | 2.48%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 3         | 2.48%   |
| Huawei E353/E3131                                                    | 3         | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 1.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 2         | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                 | 2         | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 1         | 0.83%   |
| Spreadtrum Unisoc Phone                                              | 1         | 0.83%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1         | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 1         | 0.83%   |
| Nvidia MCP61 Ethernet                                                | 1         | 0.83%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.83%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                    | 1         | 0.83%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.83%   |
| Intel Ethernet Connection (2) I218-V                                 | 1         | 0.83%   |
| Intel 82579V Gigabit Network Connection                              | 1         | 0.83%   |
| Intel 82578DC Gigabit Network Connection                             | 1         | 0.83%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 0.83%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.83%   |
| DisplayLink Dell Universal Dock D6000                                | 1         | 0.83%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 1         | 0.83%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 1         | 0.83%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 110       | 51.64%  |
| WiFi     | 101       | 47.42%  |
| Modem    | 2         | 0.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 67        | 50.38%  |
| WiFi     | 66        | 49.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 67        | 51.94%  |
| 1     | 54        | 41.86%  |
| 0     | 4         | 3.1%    |
| 3     | 3         | 2.33%   |
| 6     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 119       | 91.54%  |
| Yes  | 11        | 8.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 42.25%  |
| Cambridge Silicon Radio         | 7         | 9.86%   |
| Realtek Semiconductor           | 6         | 8.45%   |
| Qualcomm Atheros Communications | 6         | 8.45%   |
| Lite-On Technology              | 5         | 7.04%   |
| IMC Networks                    | 3         | 4.23%   |
| Dell                            | 3         | 4.23%   |
| Broadcom                        | 3         | 4.23%   |
| Hewlett-Packard                 | 2         | 2.82%   |
| Foxconn / Hon Hai               | 2         | 2.82%   |
| ASUSTek Computer                | 2         | 2.82%   |
| Marvell Semiconductor           | 1         | 1.41%   |
| Foxconn International           | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 11.27%  |
| Intel AX200 Bluetooth                               | 8         | 11.27%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 9.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 7.04%   |
| Realtek Bluetooth Radio                             | 4         | 5.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 5.63%   |
| Intel Bluetooth Device                              | 4         | 5.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.82%   |
| Intel AX201 Bluetooth                               | 2         | 2.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.82%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 2.82%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.41%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.41%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.41%   |
| Lite-On BCM43142A0                                  | 1         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.41%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.41%   |
| IMC Networks Bluetooth Module                       | 1         | 1.41%   |
| IMC Networks Bluetooth Device                       | 1         | 1.41%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.41%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.41%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.41%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.41%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.41%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.41%   |
| ASUS BCM20702A0                                     | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 91        | 49.19%  |
| AMD                    | 43        | 23.24%  |
| Nvidia                 | 35        | 18.92%  |
| C-Media Electronics    | 4         | 2.16%   |
| JMTek                  | 2         | 1.08%   |
| GN Netcom              | 2         | 1.08%   |
| Plantronics            | 1         | 0.54%   |
| Microsoft              | 1         | 0.54%   |
| Logitech               | 1         | 0.54%   |
| Generalplus Technology | 1         | 0.54%   |
| Focusrite-Novation     | 1         | 0.54%   |
| Creative Labs          | 1         | 0.54%   |
| Blue Microphones       | 1         | 0.54%   |
| Alesis                 | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 3.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.17%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 3.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 2.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.26%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 2.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.26%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 2.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.81%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 1.36%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 1.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.36%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.9%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.9%    |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.9%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.9%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.9%    |
| Plantronics RIG 800HD                                                                             | 1         | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.45%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Microsoft Surface Pro 3 Docking Station Audio Device                                              | 1         | 0.45%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.45%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.45%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.45%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.45%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 17.39%  |
| SK hynix            | 3         | 13.04%  |
| Micron Technology   | 3         | 13.04%  |
| Kingston            | 3         | 13.04%  |
| Unknown             | 2         | 8.7%    |
| Team                | 2         | 8.7%    |
| Crucial             | 2         | 8.7%    |
| Smart               | 1         | 4.35%   |
| Ramaxel Technology  | 1         | 4.35%   |
| G.Skill             | 1         | 4.35%   |
| Corsair             | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s         | 2         | 7.69%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1         | 3.85%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                        | 1         | 3.85%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s     | 1         | 3.85%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s          | 1         | 3.85%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s       | 1         | 3.85%   |
| Samsung RAM K3QF3F30BM-AGCF 2GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.85%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s      | 1         | 3.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 1         | 3.85%   |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s  | 1         | 3.85%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8192MB DIMM DDR4 2400MT/s       | 1         | 3.85%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s            | 1         | 3.85%   |
| Kingston RAM 99P5471-002.A00LF 2GB DIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Kingston RAM 99P5471-001.A01LF 2GB DIMM DDR3 1333MT/s        | 1         | 3.85%   |
| Kingston RAM 99P5471-001.A00LF 2GB DIMM DDR3 1333MT/s        | 1         | 3.85%   |
| Kingston RAM 9905584-023.A00LF 4GB DIMM DDR3 1600MT/s        | 1         | 3.85%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s          | 1         | 3.85%   |
| Crucial RAM BLT4G3D1869DT 4096MB DIMM DDR3 1333MT/s          | 1         | 3.85%   |
| Crucial RAM BL16G36C16U4W.M16FE1 16GB DIMM DDR4 3733MT/s     | 1         | 3.85%   |
| Corsair RAM CMK64GX4M2D3000C16 32GB DIMM DDR4 3000MT/s       | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 45.45%  |
| DDR3    | 8         | 36.36%  |
| SDRAM   | 1         | 4.55%   |
| LPDDR4  | 1         | 4.55%   |
| LPDDR3  | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 45%     |
| DIMM         | 9         | 45%     |
| Row Of Chips | 2         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 34.78%  |
| 4096  | 7         | 30.43%  |
| 2048  | 4         | 17.39%  |
| 32768 | 3         | 13.04%  |
| 16384 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 25%     |
| 3200  | 3         | 12.5%   |
| 2667  | 3         | 12.5%   |
| 2400  | 2         | 8.33%   |
| 1867  | 2         | 8.33%   |
| 1333  | 2         | 8.33%   |
| 3733  | 1         | 4.17%   |
| 3600  | 1         | 4.17%   |
| 3500  | 1         | 4.17%   |
| 3000  | 1         | 4.17%   |
| 1067  | 1         | 4.17%   |
| 800   | 1         | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 2         | 33.33%  |
| Seiko Epson     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L120 Series            | 1         | 16.67%  |
| HP LaserJet 1300                   | 1         | 16.67%  |
| HP DeskJet 3830 series             | 1         | 16.67%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 16.67%  |
| Canon PIXMA MX920 Series           | 1         | 16.67%  |
| Canon PIXMA MG2500 Series          | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 18.92%  |
| Microdia                               | 11        | 14.86%  |
| IMC Networks                           | 7         | 9.46%   |
| Realtek Semiconductor                  | 6         | 8.11%   |
| Acer                                   | 6         | 8.11%   |
| Logitech                               | 5         | 6.76%   |
| Syntek                                 | 3         | 4.05%   |
| Suyin                                  | 3         | 4.05%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.05%   |
| Sunplus Innovation Technology          | 2         | 2.7%    |
| Samsung Electronics                    | 2         | 2.7%    |
| Quanta                                 | 2         | 2.7%    |
| Generalplus Technology                 | 2         | 2.7%    |
| Alcor Micro                            | 2         | 2.7%    |
| Ricoh                                  | 1         | 1.35%   |
| Lite-On Technology                     | 1         | 1.35%   |
| Lenovo                                 | 1         | 1.35%   |
| KYE Systems (Mouse Systems)            | 1         | 1.35%   |
| GEMBIRD                                | 1         | 1.35%   |
| Cubeternet                             | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                          | 5         | 6.76%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 3         | 4.05%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 4.05%   |
| Logitech HD Pro Webcam C920                                                | 3         | 4.05%   |
| IMC Networks Integrated Camera                                             | 3         | 4.05%   |
| Chicony Integrated Camera                                                  | 3         | 4.05%   |
| Acer EasyCamera                                                            | 3         | 4.05%   |
| Syntek Integrated Camera                                                   | 2         | 2.7%    |
| Samsung Galaxy A5 (MTP)                                                    | 2         | 2.7%    |
| Generalplus 808 Camera                                                     | 2         | 2.7%    |
| Chicony Integrated HP HD Webcam                                            | 2         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 2.7%    |
| Acer Lenovo EasyCamera                                                     | 2         | 2.7%    |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.35%   |
| Suyin Sony Visual Communication Camera                                     | 1         | 1.35%   |
| Suyin Lenovo EasyCamera                                                    | 1         | 1.35%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 1.35%   |
| Sunplus USB 2.0 Camera                                                     | 1         | 1.35%   |
| Sunplus HD Webcam                                                          | 1         | 1.35%   |
| Ricoh HD Webcam                                                            | 1         | 1.35%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 1.35%   |
| Realtek USB Camera                                                         | 1         | 1.35%   |
| Realtek Laptop_Integrated_Webcam_HD                                        | 1         | 1.35%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.35%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 1.35%   |
| Realtek HD WebCam                                                          | 1         | 1.35%   |
| Quanta hm1091_techfront                                                    | 1         | 1.35%   |
| Quanta HD User Facing                                                      | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 1.35%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 1.35%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.35%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 1.35%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.35%   |
| Logitech Webcam C110                                                       | 1         | 1.35%   |
| Logitech C922 Pro Stream Webcam                                            | 1         | 1.35%   |
| Lite-On HP Wide Vision HD Camera                                           | 1         | 1.35%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.35%   |
| KYE Systems (Mouse Systems) Slim 1322AF                                    | 1         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.35%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.35%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.35%   |
| IMC Networks EasyCamera                                                    | 1         | 1.35%   |
| GEMBIRD USB2.0 PC CAMERA                                                   | 1         | 1.35%   |
| Cubeternet USB2.0 Camera                                                   | 1         | 1.35%   |
| Chicony TOSHIBA Web Camera                                                 | 1         | 1.35%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.35%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.35%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 1         | 1.35%   |
| Alcor Micro USB 2.0 PC Camera                                              | 1         | 1.35%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 1.35%   |
| Acer HD Webcam                                                             | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 63.64%  |
| Synaptics             | 2         | 18.18%  |
| Elan Microelectronics | 2         | 18.18%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 27.27%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 18.18%  |
| Elan ELAN:Fingerprint                                      | 2         | 18.18%  |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 9.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 92        | 71.32%  |
| 1     | 30        | 23.26%  |
| 2     | 7         | 5.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 12        | 27.91%  |
| Fingerprint reader       | 11        | 25.58%  |
| Chipcard                 | 6         | 13.95%  |
| Graphics card            | 5         | 11.63%  |
| Multimedia controller    | 4         | 9.3%    |
| Storage                  | 2         | 4.65%   |
| Tv card                  | 1         | 2.33%   |
| Communication controller | 1         | 2.33%   |
| Camera                   | 1         | 2.33%   |

