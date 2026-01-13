Oracle Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Oracle_Linux/Desktop/README.md) and [notebooks](/Dist/Oracle_Linux/Notebook/README.md).

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

Total: 183

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP         | 158B                        | Desktop     | [12ee930c05](https://linux-hardware.org/?probe=12ee930c05) | Dec 08, 2025 |
| HP         | 158B                        | Desktop     | [b410504428](https://linux-hardware.org/?probe=b410504428) | Dec 02, 2025 |
| Dell       | Latitude 7450               | Notebook    | [7b8f028721](https://linux-hardware.org/?probe=7b8f028721) | Oct 09, 2025 |
| Acer       | FIH57                       | Desktop     | [e28af6bf25](https://linux-hardware.org/?probe=e28af6bf25) | Jul 26, 2025 |
| Huanan     | X99 F8D V2.1                | Desktop     | [d8d0977a39](https://linux-hardware.org/?probe=d8d0977a39) | Jun 05, 2025 |
| Supermicro | X9SRH-7F/7TF                | Server      | [c648536474](https://linux-hardware.org/?probe=c648536474) | May 28, 2025 |
| Supermicro | X9SRH-7F/7TF                | Server      | [e0ee8d0ada](https://linux-hardware.org/?probe=e0ee8d0ada) | Apr 29, 2025 |
| Dell       | 0Y0VFJ A01                  | All in one  | [143d6f615d](https://linux-hardware.org/?probe=143d6f615d) | Apr 17, 2025 |
| Toshiba    | Satellite P55t-A            | Notebook    | [627cb9e248](https://linux-hardware.org/?probe=627cb9e248) | Apr 05, 2025 |
| ASUSTek    | P8Z77-V LX                  | Desktop     | [0a78f8643e](https://linux-hardware.org/?probe=0a78f8643e) | Mar 25, 2025 |
| HP         | Laptop 17-cp0xxx            | Notebook    | [f589c668ce](https://linux-hardware.org/?probe=f589c668ce) | Mar 22, 2025 |
| ASUSTek    | P8Z77-V LX                  | Desktop     | [ea6ae957b4](https://linux-hardware.org/?probe=ea6ae957b4) | Mar 14, 2025 |
| MSI        | MS-B9071                    | Desktop     | [64eee3f80e](https://linux-hardware.org/?probe=64eee3f80e) | Mar 07, 2025 |
| Dell       | Latitude 7440               | Notebook    | [1465f06bab](https://linux-hardware.org/?probe=1465f06bab) | Mar 07, 2025 |
| ASRock     | Z68 Extreme3 Gen3           | Desktop     | [deb0c2ec87](https://linux-hardware.org/?probe=deb0c2ec87) | Feb 24, 2025 |
| HP         | ZBook Power 16 inch G11 ... | Notebook    | [9a8e9d2dad](https://linux-hardware.org/?probe=9a8e9d2dad) | Feb 20, 2025 |
| HP         | EliteBook 840 14 inch G1... | Notebook    | [61742aff4d](https://linux-hardware.org/?probe=61742aff4d) | Jan 27, 2025 |
| Dell       | Latitude 7450               | Notebook    | [41b698bba3](https://linux-hardware.org/?probe=41b698bba3) | Dec 28, 2024 |
| ASUSTek    | PRIME Z490-A                | Desktop     | [c7a92e755d](https://linux-hardware.org/?probe=c7a92e755d) | Dec 23, 2024 |
| ASUSTek    | PRIME Z490-A                | Desktop     | [7d25b9b02f](https://linux-hardware.org/?probe=7d25b9b02f) | Dec 23, 2024 |
| Dell       | Latitude 7450               | Notebook    | [43d05fa82d](https://linux-hardware.org/?probe=43d05fa82d) | Dec 23, 2024 |
| Gigabyte   | B450 AORUS ELITE            | Desktop     | [51f6c29054](https://linux-hardware.org/?probe=51f6c29054) | Dec 22, 2024 |
| HP         | EliteBook 850 G1            | Notebook    | [0a6449c5f0](https://linux-hardware.org/?probe=0a6449c5f0) | Nov 27, 2024 |
| HP         | ZBook Fury 15.6 inch G8 ... | Notebook    | [9ba889ebcc](https://linux-hardware.org/?probe=9ba889ebcc) | Nov 18, 2024 |
| Alienware  | m18 R2                      | Notebook    | [9f13ae9091](https://linux-hardware.org/?probe=9f13ae9091) | Sep 21, 2024 |
| Dell       | 0Y7WYT A00                  | Desktop     | [26470bb6ae](https://linux-hardware.org/?probe=26470bb6ae) | Sep 07, 2024 |
| Dell       | 0Y7WYT A00                  | Desktop     | [3fcfac6482](https://linux-hardware.org/?probe=3fcfac6482) | Sep 07, 2024 |
| ASUSTek    | ProArt PX13 HN7306WU_HN7... | Convertible | [0a60168f59](https://linux-hardware.org/?probe=0a60168f59) | Aug 31, 2024 |
| ASUSTek    | ProArt PX13 HN7306WU_HN7... | Convertible | [1b125f73a9](https://linux-hardware.org/?probe=1b125f73a9) | Aug 31, 2024 |
| Lenovo     | IdeaPad 3 14IIL05 81WD      | Notebook    | [27e651550b](https://linux-hardware.org/?probe=27e651550b) | Jun 30, 2024 |
| Dell       | Latitude 7330               | Convertible | [ff939f558c](https://linux-hardware.org/?probe=ff939f558c) | Jun 29, 2024 |
| Dell       | Inspiron 3421               | Notebook    | [821d5d1169](https://linux-hardware.org/?probe=821d5d1169) | Jun 21, 2024 |
| Fujitsu    | LIFEBOOK E449               | Notebook    | [a9a0c13323](https://linux-hardware.org/?probe=a9a0c13323) | Jun 13, 2024 |
| HP         | ProLiant DL380 G7           | Server      | [7cc6270f3f](https://linux-hardware.org/?probe=7cc6270f3f) | Jun 05, 2024 |
| Dell       | Inspiron 3421               | Notebook    | [67986b7795](https://linux-hardware.org/?probe=67986b7795) | May 23, 2024 |
| Fujitsu    | LIFEBOOK E449               | Notebook    | [956d6540d5](https://linux-hardware.org/?probe=956d6540d5) | May 23, 2024 |
| Supermicro | X9SCL-II/X9SCM-II           | Desktop     | [a0c9c93180](https://linux-hardware.org/?probe=a0c9c93180) | May 20, 2024 |
| Supermicro | X9SCL-II/X9SCM-II           | Desktop     | [8373a09f6d](https://linux-hardware.org/?probe=8373a09f6d) | May 20, 2024 |
| Gigabyte   | X470 AORUS ULTRA GAMING-... | Desktop     | [af34317225](https://linux-hardware.org/?probe=af34317225) | May 14, 2024 |
| Unknown    | Unknown                     | Desktop     | [806e7d1dfa](https://linux-hardware.org/?probe=806e7d1dfa) | Apr 28, 2024 |
| Gigabyte   | B450M DS3H-CF               | Desktop     | [cf6c011819](https://linux-hardware.org/?probe=cf6c011819) | Apr 13, 2024 |
| Dell       | 0D28YY A03                  | Desktop     | [894b628494](https://linux-hardware.org/?probe=894b628494) | Apr 12, 2024 |
| Lenovo     | ThinkPad P16s Gen 1 21BT... | Notebook    | [97c2387841](https://linux-hardware.org/?probe=97c2387841) | Apr 12, 2024 |
| Lenovo     | ThinkPad P16s Gen 1 21BT... | Notebook    | [e47633811b](https://linux-hardware.org/?probe=e47633811b) | Apr 12, 2024 |
| ASUSTek    | X541SA                      | Notebook    | [23ea4a0287](https://linux-hardware.org/?probe=23ea4a0287) | Apr 09, 2024 |
| ASUSTek    | X541SA                      | Notebook    | [0f5bd53c6f](https://linux-hardware.org/?probe=0f5bd53c6f) | Apr 08, 2024 |
| ASUSTek    | X541SA                      | Notebook    | [b3f083db5c](https://linux-hardware.org/?probe=b3f083db5c) | Apr 06, 2024 |
| ASUSTek    | PRIME B250M-A               | Desktop     | [5d12c5c26e](https://linux-hardware.org/?probe=5d12c5c26e) | Mar 31, 2024 |
| ASUSTek    | PRIME B250M-A               | Desktop     | [142a42435b](https://linux-hardware.org/?probe=142a42435b) | Mar 30, 2024 |
| HP         | EliteBook 640 14 inch G1... | Notebook    | [90a116696c](https://linux-hardware.org/?probe=90a116696c) | Mar 24, 2024 |
| Lenovo     | ThinkBook 15-IIL 20SM       | Notebook    | [692db635b4](https://linux-hardware.org/?probe=692db635b4) | Mar 23, 2024 |
| HP         | ProLiant ML110 Gen9         | Desktop     | [c2f9d107ed](https://linux-hardware.org/?probe=c2f9d107ed) | Mar 02, 2024 |
| HP         | ProLiant ML310e Gen8 v2     | Desktop     | [1b3629654d](https://linux-hardware.org/?probe=1b3629654d) | Mar 02, 2024 |
| HP         | ZBook Fury 15.6 inch G8 ... | Notebook    | [b27420dd64](https://linux-hardware.org/?probe=b27420dd64) | Feb 21, 2024 |
| Dell       | Latitude 7420               | Notebook    | [30e1dc7b9f](https://linux-hardware.org/?probe=30e1dc7b9f) | Feb 13, 2024 |
| Lenovo     | ThinkPad Yoga 370 20JJS0... | Convertible | [3ae3d26304](https://linux-hardware.org/?probe=3ae3d26304) | Jan 21, 2024 |
| Lenovo     | ThinkPad Yoga 370 20JJS0... | Convertible | [b244483cc6](https://linux-hardware.org/?probe=b244483cc6) | Jan 20, 2024 |
| Dell       | Latitude 7430               | Notebook    | [153f1a144c](https://linux-hardware.org/?probe=153f1a144c) | Jan 19, 2024 |
| Dell       | Latitude 7430               | Notebook    | [a05210eeb4](https://linux-hardware.org/?probe=a05210eeb4) | Jan 19, 2024 |
| Lenovo     | ThinkPad T490 20N3S3XR00    | Notebook    | [63ec999c70](https://linux-hardware.org/?probe=63ec999c70) | Jan 16, 2024 |
| ASRock     | B760M-STX                   | Desktop     | [1648b583d6](https://linux-hardware.org/?probe=1648b583d6) | Jan 10, 2024 |
| Lenovo     | ThinkPad W520 42844DG       | Notebook    | [52cd813233](https://linux-hardware.org/?probe=52cd813233) | Dec 20, 2023 |
| HP         | ZBook Fury 15.6 inch G8 ... | Notebook    | [58ad170a68](https://linux-hardware.org/?probe=58ad170a68) | Dec 10, 2023 |
| Dell       | XPS 15 9570                 | Notebook    | [35a10a1ae2](https://linux-hardware.org/?probe=35a10a1ae2) | Dec 10, 2023 |
| ASUSTek    | G15CF                       | Desktop     | [c2b88beb62](https://linux-hardware.org/?probe=c2b88beb62) | Dec 02, 2023 |
| Toshiba    | TECRA R950                  | Notebook    | [8ab7278f60](https://linux-hardware.org/?probe=8ab7278f60) | Dec 01, 2023 |
| Toshiba    | TECRA R950                  | Notebook    | [9634f68cab](https://linux-hardware.org/?probe=9634f68cab) | Dec 01, 2023 |
| ASRock     | B550M Steel Legend          | Desktop     | [9cb8304240](https://linux-hardware.org/?probe=9cb8304240) | Nov 24, 2023 |
| ASRock     | B550M Steel Legend          | Desktop     | [8cfb18380e](https://linux-hardware.org/?probe=8cfb18380e) | Nov 24, 2023 |
| Dell       | XPS 15 9570                 | Notebook    | [7728d0ab4b](https://linux-hardware.org/?probe=7728d0ab4b) | Nov 22, 2023 |
| HP         | EliteBook 840 G4            | Notebook    | [7d2d46e750](https://linux-hardware.org/?probe=7d2d46e750) | Nov 17, 2023 |
| Lenovo     | Legion Y540-15IRH 81SX      | Notebook    | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| Lenovo     | Legion Y540-15IRH 81SX      | Notebook    | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| Dell       | Precision 5550              | Notebook    | [033e294199](https://linux-hardware.org/?probe=033e294199) | Nov 03, 2023 |
| HP         | 240 G8 Notebook PC          | Notebook    | [0a98dcd952](https://linux-hardware.org/?probe=0a98dcd952) | Oct 11, 2023 |
| ASUSTek    | SABERTOOTH 990FX R3.0       | Desktop     | [b63af8760f](https://linux-hardware.org/?probe=b63af8760f) | Oct 03, 2023 |
| ASUSTek    | SABERTOOTH 990FX R3.0       | Desktop     | [5ac9728fe0](https://linux-hardware.org/?probe=5ac9728fe0) | Oct 01, 2023 |
| HP         | 240 G8 Notebook PC          | Notebook    | [6fec1bd640](https://linux-hardware.org/?probe=6fec1bd640) | Sep 11, 2023 |
| Dell       | Latitude 7440               | Notebook    | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell       | Latitude 7440               | Notebook    | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| HP         | Pavilion x360 Convertibl... | Convertible | [913e1fef64](https://linux-hardware.org/?probe=913e1fef64) | Aug 23, 2023 |
| Intel      | NUC13ANBi5 N13061-202       | Mini pc     | [0a0fee9565](https://linux-hardware.org/?probe=0a0fee9565) | Aug 17, 2023 |
| HP         | ZBook Fury 16 G9 Mobile ... | Notebook    | [4b7e25150a](https://linux-hardware.org/?probe=4b7e25150a) | Aug 15, 2023 |
| MSI        | P65 Creator 8RE             | Notebook    | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI        | P65 Creator 8RE             | Notebook    | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Cisco      | WAVE-694-K9 A0              | Desktop     | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASRock     | Z68 Extreme3 Gen3           | Desktop     | [7849965aa1](https://linux-hardware.org/?probe=7849965aa1) | Jun 11, 2023 |
| Dell       | Latitude 7430               | Notebook    | [299e6897d2](https://linux-hardware.org/?probe=299e6897d2) | Jun 05, 2023 |
| Supermicro | X8DTU                       | Server      | [2e1d03c7da](https://linux-hardware.org/?probe=2e1d03c7da) | Jun 01, 2023 |
| Intel      | NUC12WSBi5 M46425-303       | Mini pc     | [e3dca941cf](https://linux-hardware.org/?probe=e3dca941cf) | May 28, 2023 |
| Intel      | NUC12WSBi5 M46425-303       | Mini pc     | [9327ef1887](https://linux-hardware.org/?probe=9327ef1887) | May 27, 2023 |
| Lenovo     | ThinkPad T490 20N3S3XR00    | Notebook    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Lenovo     | ThinkPad W541 20EGS1PL00    | Notebook    | [751cc5dbc7](https://linux-hardware.org/?probe=751cc5dbc7) | May 22, 2023 |
| HP         | 1589                        | Desktop     | [c905464231](https://linux-hardware.org/?probe=c905464231) | May 11, 2023 |
| ASUSTek    | ZenBook UX425EA_UX425EA     | Notebook    | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| Gigabyte   | H81M-S2PV                   | Desktop     | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| Intel      | NUC6CAYB J23203-406         | Mini pc     | [65bb9a17dd](https://linux-hardware.org/?probe=65bb9a17dd) | Feb 04, 2023 |
| HP         | Laptop 17-cp0xxx            | Notebook    | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| HP         | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| Google     | Lick                        | Notebook    | [d792b79719](https://linux-hardware.org/?probe=d792b79719) | Jan 12, 2023 |
| Intel      | NUC12WSBi7 M46422-303       | Mini pc     | [3ddd96770b](https://linux-hardware.org/?probe=3ddd96770b) | Dec 24, 2022 |
| Intel      | NUC12WSBi7 M46422-303       | Mini pc     | [8f10e15f9a](https://linux-hardware.org/?probe=8f10e15f9a) | Dec 24, 2022 |
| Panasonic  | CF-53AAG54FM                | Notebook    | [cf7f652846](https://linux-hardware.org/?probe=cf7f652846) | Dec 21, 2022 |
| Lenovo     | ThinkPad T470 20HES0E71M    | Notebook    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| ASUSTek    | PRIME B560M-A AC            | Desktop     | [d4cc718e46](https://linux-hardware.org/?probe=d4cc718e46) | Nov 29, 2022 |
| Lenovo     | ThinkPad P70 20ESS04S00     | Notebook    | [01b85c4c2a](https://linux-hardware.org/?probe=01b85c4c2a) | Nov 10, 2022 |
| Lenovo     | ThinkPad T470 20HES21434    | Notebook    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Fujitsu    | D2759 S26361-D2759-A13 W... | Server      | [c4c0b53877](https://linux-hardware.org/?probe=c4c0b53877) | Oct 23, 2022 |
| Dynabook   | PORTEGE X40-G               | Notebook    | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell       | 0DC48C A02                  | Desktop     | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| HP         | EliteBook 840 G5            | Notebook    | [2709daf415](https://linux-hardware.org/?probe=2709daf415) | Sep 13, 2022 |
| ASUSTek    | H81M-A                      | Desktop     | [a37e952875](https://linux-hardware.org/?probe=a37e952875) | Sep 04, 2022 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Dell       | Inspiron 5502               | Notebook    | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Dell       | 073Y7Y A00                  | Desktop     | [3bed97b23e](https://linux-hardware.org/?probe=3bed97b23e) | Jul 21, 2022 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| MSI        | Z77A-G43                    | Desktop     | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek    | P8H67                       | Desktop     | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Lenovo     | ThinkPad P70 20ESS04S00     | Notebook    | [fc29967bed](https://linux-hardware.org/?probe=fc29967bed) | Jun 17, 2022 |
| HP         | Compaq 6730b                | Notebook    | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| Lenovo     | ThinkPad T410 2518A37       | Notebook    | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Lenovo     | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Lenovo     | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell       | Precision M4600             | Notebook    | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell       | Precision M4800             | Notebook    | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Lenovo     | ThinkPad P50s 20FL000MUS    | Notebook    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Dell       | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Lenovo     | ThinkPad X1 Extreme 2nd ... | Notebook    | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| Lenovo     | ThinkPad T450 20BUS14900    | Notebook    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| Lenovo     | ThinkPad T480 20L5A07TAU    | Notebook    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo     | ThinkPad X280 20KES4H34G    | Notebook    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Dell       | Latitude 7420               | Notebook    | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| HP         | ProBook 445 G6              | Notebook    | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo     | ThinkPad X390 Yoga 20NQS... | Convertible | [8219e32fef](https://linux-hardware.org/?probe=8219e32fef) | Dec 22, 2021 |
| Lenovo     | ThinkPad T450 20BUS14900    | Notebook    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo     | IdeaPad 300-15ISK 80RS      | Notebook    | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell       | Latitude 7410               | Notebook    | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell       | Latitude E6420              | Notebook    | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Lenovo     | IdeaPad C340-14IWL 81RL     | Convertible | [cf3c570b7a](https://linux-hardware.org/?probe=cf3c570b7a) | Sep 27, 2021 |
| Dell       | Latitude 7410               | Notebook    | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell       | Latitude 7410               | Notebook    | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Dell       | Inspiron 3542               | Notebook    | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Gigabyte   | Z490 AORUS ELITE AC         | Desktop     | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| ASUSTek    | UX305FA                     | Notebook    | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Gigabyte   | X99-Designare EX-CF         | Desktop     | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Dell       | Latitude 7410               | Notebook    | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell       | Latitude 7410               | Notebook    | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo     | ThinkPad T490 20N3S77600    | Notebook    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell       | Latitude 7410               | Notebook    | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| ASUSTek    | G11CD                       | Desktop     | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP         | 158B                        | Desktop     | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell       | PowerEdge FC630             | Desktop     | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte   | X470 AORUS ULTRA GAMING-... | Desktop     | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Foxconn    | 2ADA                        | Desktop     | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek    | G11CD                       | Desktop     | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Standard   | BW Series                   | Notebook    | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| Apple      | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [109e02e0f2](https://linux-hardware.org/?probe=109e02e0f2) | Jun 07, 2020 |
| Apple      | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2d385b9cb0](https://linux-hardware.org/?probe=2d385b9cb0) | Jun 07, 2020 |
| HP         | Notebook                    | Notebook    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP         | ZBook 15                    | Notebook    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo     | ThinkPad T480 20L6S56Y2X    | Notebook    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| Dell       | 0C96W1 A01                  | Desktop     | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |
| ASUSTek    | X510UR                      | Notebook    | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek    | X510UR                      | Notebook    | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek    | X510UR                      | Notebook    | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo     | ThinkPad L540 20AVCTO1WW    | Notebook    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| HPE        | ProLiant BL460c Gen10       | Server      | [9e91d0ed19](https://linux-hardware.org/?probe=9e91d0ed19) | Jun 14, 2019 |
| Lenovo     | ThinkPad T480 20L6S56Y2X    | Notebook    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Oracle Linux 9.5  | 13        | 9.42%   |
| Oracle Linux 8.5  | 13        | 9.42%   |
| Oracle Linux 9.3  | 12        | 8.7%    |
| Oracle Linux 8.3  | 12        | 8.7%    |
| Oracle Linux 9.4  | 10        | 7.25%   |
| Oracle Linux 9.2  | 10        | 7.25%   |
| Oracle Linux 8.9  | 10        | 7.25%   |
| Oracle Linux 8.8  | 7         | 5.07%   |
| Oracle Linux 8.4  | 7         | 5.07%   |
| Oracle Linux 8.6  | 6         | 4.35%   |
| Oracle Linux 9.1  | 5         | 3.62%   |
| Oracle Linux 9.0  | 5         | 3.62%   |
| Oracle Linux 8.7  | 5         | 3.62%   |
| Oracle Linux 7.9  | 4         | 2.9%    |
| Oracle Linux 9.6  | 3         | 2.17%   |
| Oracle Linux 8.1  | 3         | 2.17%   |
| Oracle Linux 7.7  | 3         | 2.17%   |
| Oracle Linux 8.2  | 2         | 1.45%   |
| Oracle Linux 7.8  | 2         | 1.45%   |
| Oracle Linux 7.6  | 2         | 1.45%   |
| Oracle Linux 9.7  | 1         | 0.72%   |
| Oracle Linux 8.10 | 1         | 0.72%   |
| Oracle Linux 7.4  | 1         | 0.72%   |
| Oracle Linux 6.10 | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 124       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.15.0-200.131.27.el9uek.x86_64   | 4         | 2.68%   |
| 5.4.17-2102.202.5.el8uek.x86_64   | 3         | 2.01%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 2.01%   |
| 5.15.0-206.153.7.el9uek.x86_64    | 3         | 2.01%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 3         | 2.01%   |
| 5.15.0-101.103.2.1.el9uek.x86_64  | 3         | 2.01%   |
| 5.15.0-100.96.32.el8uek.x86_64    | 3         | 2.01%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 2.01%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 2         | 1.34%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 1.34%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 2         | 1.34%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 2         | 1.34%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 2         | 1.34%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2         | 1.34%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2         | 1.34%   |
| 5.15.0-306.177.4.el9uek.x86_64    | 2         | 1.34%   |
| 5.15.0-305.176.4.el9uek.x86_64    | 2         | 1.34%   |
| 5.15.0-206.153.7.1.el9uek.x86_64  | 2         | 1.34%   |
| 5.15.0-205.149.5.1.el9uek.x86_64  | 2         | 1.34%   |
| 5.15.0-200.131.27.el8uek.x86_64   | 2         | 1.34%   |
| 5.15.0-200.131.27.1.el8uek.x86_64 | 2         | 1.34%   |
| 5.15.0-106.131.4.el9uek.x86_64    | 2         | 1.34%   |
| 5.15.0-103.114.4.el8uek.x86_64    | 2         | 1.34%   |
| 5.14.0-503.16.1.el9_5.x86_64      | 2         | 1.34%   |
| 5.14.0-427.22.1.el9_4.x86_64      | 2         | 1.34%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 2         | 1.34%   |
| 4.18.0-193.1.2.el8_2.x86_64       | 2         | 1.34%   |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 1.34%   |
| 6.12.0-103.40.4.3.el9uek.x86_64   | 1         | 0.67%   |
| 6.12.0-100.28.2.2.el9uek.x86_64   | 1         | 0.67%   |
| 6.12.0-0.20.20.el9uek.x86_64      | 1         | 0.67%   |
| 6.11.0-0.el9ueknext.x86_64        | 1         | 0.67%   |
| 5.4.17-2136.330.7.1.el8uek.x86_64 | 1         | 0.67%   |
| 5.4.17-2136.326.6.el8uek.x86_64   | 1         | 0.67%   |
| 5.4.17-2136.318.7.2.el8uek.x86_64 | 1         | 0.67%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 0.67%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 0.67%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1         | 0.67%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 0.67%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 47        | 36.72%  |
| 5.4.17  | 31        | 24.22%  |
| 4.18.0  | 18        | 14.06%  |
| 5.14.0  | 14        | 10.94%  |
| 4.14.35 | 5         | 3.91%   |
| 6.12.0  | 3         | 2.34%   |
| 3.10.0  | 3         | 2.34%   |
| 6.11.0  | 1         | 0.78%   |
| 5.4.11  | 1         | 0.78%   |
| 5.15.2  | 1         | 0.78%   |
| 5.14.1  | 1         | 0.78%   |
| 5.11.1  | 1         | 0.78%   |
| 4.1.12  | 1         | 0.78%   |
| 3.8.13  | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 48        | 37.5%   |
| 5.4     | 32        | 25%     |
| 4.18    | 18        | 14.06%  |
| 5.14    | 15        | 11.72%  |
| 4.14    | 5         | 3.91%   |
| 6.12    | 3         | 2.34%   |
| 3.10    | 3         | 2.34%   |
| 6.11    | 1         | 0.78%   |
| 5.11    | 1         | 0.78%   |
| 4.1     | 1         | 0.78%   |
| 3.8     | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 124       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 93        | 72.66%  |
| Unknown       | 16        | 12.5%   |
| GNOME Classic | 7         | 5.47%   |
| KDE5          | 5         | 3.91%   |
| XFCE          | 2         | 1.56%   |
| MATE          | 2         | 1.56%   |
| KDE4          | 2         | 1.56%   |
| X-Cinnamon    | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 68        | 53.54%  |
| X11     | 42        | 33.07%  |
| Unknown | 11        | 8.66%   |
| Tty     | 4         | 3.15%   |
| Web     | 2         | 1.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 48.82%  |
| GDM     | 60        | 47.24%  |
| SDDM    | 4         | 3.15%   |
| TDM     | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 73        | 58.4%   |
| en_GB      | 13        | 10.4%   |
| de_DE      | 6         | 4.8%    |
| ru_RU      | 5         | 4%      |
| Unknown    | 5         | 4%      |
| pt_BR      | 4         | 3.2%    |
| it_IT      | 4         | 3.2%    |
| en_AU      | 4         | 3.2%    |
| pl_PL      | 3         | 2.4%    |
| en_IN      | 2         | 1.6%    |
| zh_HK      | 1         | 0.8%    |
| zh_CN      | 1         | 0.8%    |
| es_MX      | 1         | 0.8%    |
| es_CO      | 1         | 0.8%    |
| en_US.UTF8 | 1         | 0.8%    |
| en_DE      | 1         | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 80        | 63.49%  |
| BIOS | 46        | 36.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 107       | 84.25%  |
| Ext4    | 15        | 11.81%  |
| Btrfs   | 2         | 1.57%   |
| Unknown | 2         | 1.57%   |
| Zfs     | 1         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 61        | 48.03%  |
| Unknown | 51        | 40.16%  |
| MBR     | 15        | 11.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 92%     |
| Yes       | 10        | 8%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 89.6%   |
| Yes       | 13        | 10.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 21.77%  |
| Dell                | 25        | 20.16%  |
| Hewlett-Packard     | 21        | 16.94%  |
| ASUSTek Computer    | 15        | 12.1%   |
| Gigabyte Technology | 6         | 4.84%   |
| Supermicro          | 4         | 3.23%   |
| Intel               | 4         | 3.23%   |
| MSI                 | 3         | 2.42%   |
| ASRock              | 3         | 2.42%   |
| Toshiba             | 2         | 1.61%   |
| Fujitsu             | 2         | 1.61%   |
| Standard            | 1         | 0.81%   |
| Panasonic           | 1         | 0.81%   |
| Huanan              | 1         | 0.81%   |
| HPE                 | 1         | 0.81%   |
| Google              | 1         | 0.81%   |
| Foxconn             | 1         | 0.81%   |
| Dynabook            | 1         | 0.81%   |
| Cisco               | 1         | 0.81%   |
| Apple               | 1         | 0.81%   |
| Alienware           | 1         | 0.81%   |
| Acer                | 1         | 0.81%   |
| Unknown             | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Supermicro X9SCL-II/X9SCM-II              | 2         | 1.61%   |
| Lenovo ThinkPad T450 20BUS14900           | 2         | 1.61%   |
| HP Z820 Workstation                       | 2         | 1.61%   |
| Dell Latitude 7450                        | 2         | 1.61%   |
| Dell Latitude 7430                        | 2         | 1.61%   |
| Dell Latitude 7420                        | 2         | 1.61%   |
| ASUS X510UR                               | 2         | 1.61%   |
| Toshiba TECRA R950                        | 1         | 0.81%   |
| Toshiba Satellite P55t-A                  | 1         | 0.81%   |
| Supermicro X9SRH-7F/7TF                   | 1         | 0.81%   |
| Supermicro X8DTU                          | 1         | 0.81%   |
| Standard BW Series                        | 1         | 0.81%   |
| Panasonic CF-53AAG54FM                    | 1         | 0.81%   |
| MSI P65 Creator 8RE                       | 1         | 0.81%   |
| MSI MS-7758                               | 1         | 0.81%   |
| MSI B250 Gaming Nightblade MI3 (MS-B908)  | 1         | 0.81%   |
| Lenovo ThinkPad Yoga 370 20JJS0A44R       | 1         | 0.81%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 0.81%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 0.81%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 0.81%   |
| Lenovo ThinkPad W541 20EGS1PL00           | 1         | 0.81%   |
| Lenovo ThinkPad W520 42844DG              | 1         | 0.81%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 0.81%   |
| Lenovo ThinkPad T490 20N3S3XR00           | 1         | 0.81%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 0.81%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 0.81%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 0.81%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 0.81%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 0.81%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 0.81%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 0.81%   |
| Lenovo ThinkPad P16s Gen 1 21BTS0FR00     | 1         | 0.81%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 0.81%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 0.81%   |
| Lenovo ThinkBook 15-IIL 20SM              | 1         | 0.81%   |
| Lenovo Legion Y540-15IRH 81SX             | 1         | 0.81%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 0.81%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 0.81%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 0.81%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 20        | 16.13%  |
| Dell Latitude          | 10        | 8.06%   |
| Dell OptiPlex          | 7         | 5.65%   |
| HP EliteBook           | 5         | 4.03%   |
| Lenovo IdeaPad         | 4         | 3.23%   |
| HP ZBook               | 4         | 3.23%   |
| HP ProLiant            | 3         | 2.42%   |
| Dell Precision         | 3         | 2.42%   |
| Dell Inspiron          | 3         | 2.42%   |
| ASUS PRIME             | 3         | 2.42%   |
| Supermicro X9SCL-II    | 2         | 1.61%   |
| Lenovo Legion          | 2         | 1.61%   |
| HP Z820                | 2         | 1.61%   |
| ASUS X510UR            | 2         | 1.61%   |
| Toshiba TECRA          | 1         | 0.81%   |
| Toshiba Satellite      | 1         | 0.81%   |
| Supermicro X9SRH-7F    | 1         | 0.81%   |
| Supermicro X8DTU       | 1         | 0.81%   |
| Standard BW            | 1         | 0.81%   |
| Panasonic CF-53AAG54FM | 1         | 0.81%   |
| MSI P65                | 1         | 0.81%   |
| MSI MS-7758            | 1         | 0.81%   |
| MSI B250               | 1         | 0.81%   |
| Lenovo ThinkBook       | 1         | 0.81%   |
| Intel NUC6CAYH         | 1         | 0.81%   |
| Intel NUC13ANHi5       | 1         | 0.81%   |
| Intel NUC12WSHi7       | 1         | 0.81%   |
| Intel NUC12WSHi5       | 1         | 0.81%   |
| Huanan X99             | 1         | 0.81%   |
| HPE ProLiant           | 1         | 0.81%   |
| HP Z420                | 1         | 0.81%   |
| HP ProBook             | 1         | 0.81%   |
| HP Pavilion            | 1         | 0.81%   |
| HP Notebook            | 1         | 0.81%   |
| HP Laptop              | 1         | 0.81%   |
| HP Compaq              | 1         | 0.81%   |
| HP 240                 | 1         | 0.81%   |
| Google Lick            | 1         | 0.81%   |
| Gigabyte Z490          | 1         | 0.81%   |
| Gigabyte X99-Designare | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 12        | 9.68%   |
| 2022 | 11        | 8.87%   |
| 2020 | 11        | 8.87%   |
| 2019 | 11        | 8.87%   |
| 2018 | 10        | 8.06%   |
| 2016 | 10        | 8.06%   |
| 2013 | 8         | 6.45%   |
| 2024 | 7         | 5.65%   |
| 2017 | 7         | 5.65%   |
| 2015 | 7         | 5.65%   |
| 2021 | 6         | 4.84%   |
| 2014 | 6         | 4.84%   |
| 2011 | 6         | 4.84%   |
| 2010 | 5         | 4.03%   |
| 2023 | 4         | 3.23%   |
| 2025 | 1         | 0.81%   |
| 2009 | 1         | 0.81%   |
| 2008 | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 68        | 54.84%  |
| Desktop     | 39        | 31.45%  |
| Convertible | 6         | 4.84%   |
| Mini pc     | 5         | 4.03%   |
| Server      | 5         | 4.03%   |
| All in one  | 1         | 0.81%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 106       | 84.8%   |
| Enabled  | 19        | 15.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 99.19%  |
| Yes  | 1         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 38        | 29.92%  |
| 32.01-64.0      | 27        | 21.26%  |
| 4.01-8.0        | 16        | 12.6%   |
| 64.01-256.0     | 14        | 11.02%  |
| 24.01-32.0      | 13        | 10.24%  |
| 3.01-4.0        | 9         | 7.09%   |
| 16.01-24.0      | 8         | 6.3%    |
| More than 256.0 | 1         | 0.79%   |
| 1.01-2.0        | 1         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 41        | 29.29%  |
| 2.01-3.0    | 31        | 22.14%  |
| 3.01-4.0    | 24        | 17.14%  |
| 8.01-16.0   | 17        | 12.14%  |
| 1.01-2.0    | 13        | 9.29%   |
| 0.51-1.0    | 5         | 3.57%   |
| 24.01-32.0  | 3         | 2.14%   |
| 32.01-64.0  | 2         | 1.43%   |
| 64.01-256.0 | 1         | 0.71%   |
| 16.01-24.0  | 1         | 0.71%   |
| 0.01-0.5    | 1         | 0.71%   |
| Unknown     | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 84        | 66.14%  |
| 2      | 23        | 18.11%  |
| 4      | 8         | 6.3%    |
| 3      | 6         | 4.72%   |
| 5      | 3         | 2.36%   |
| 25     | 1         | 0.79%   |
| 16     | 1         | 0.79%   |
| 6      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 79.84%  |
| Yes       | 25        | 20.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 88%     |
| No        | 15        | 12%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 73.39%  |
| No        | 33        | 26.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 60.32%  |
| No        | 50        | 39.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 33        | 25.98%  |
| Germany     | 14        | 11.02%  |
| UK          | 8         | 6.3%    |
| Brazil      | 8         | 6.3%    |
| Italy       | 7         | 5.51%   |
| Poland      | 5         | 3.94%   |
| Netherlands | 5         | 3.94%   |
| Australia   | 5         | 3.94%   |
| Russia      | 4         | 3.15%   |
| Finland     | 4         | 3.15%   |
| India       | 3         | 2.36%   |
| Vietnam     | 2         | 1.57%   |
| Spain       | 2         | 1.57%   |
| Slovakia    | 2         | 1.57%   |
| Romania     | 2         | 1.57%   |
| Moldova     | 2         | 1.57%   |
| Latvia      | 2         | 1.57%   |
| Yemen       | 1         | 0.79%   |
| Turkey      | 1         | 0.79%   |
| Sweden      | 1         | 0.79%   |
| Peru        | 1         | 0.79%   |
| Pakistan    | 1         | 0.79%   |
| Nigeria     | 1         | 0.79%   |
| Mexico      | 1         | 0.79%   |
| Malaysia    | 1         | 0.79%   |
| Kazakhstan  | 1         | 0.79%   |
| Ireland     | 1         | 0.79%   |
| Hungary     | 1         | 0.79%   |
| Hong Kong   | 1         | 0.79%   |
| France      | 1         | 0.79%   |
| Colombia    | 1         | 0.79%   |
| China       | 1         | 0.79%   |
| Chile       | 1         | 0.79%   |
| Bulgaria    | 1         | 0.79%   |
| Bolivia     | 1         | 0.79%   |
| Argentina   | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 5         | 3.65%   |
| Helsinki           | 4         | 2.92%   |
| San Diego          | 3         | 2.19%   |
| Milan              | 3         | 2.19%   |
| Amsterdam          | 3         | 2.19%   |
| Warsaw             | 2         | 1.46%   |
| Tiraspol           | 2         | 1.46%   |
| Siegen             | 2         | 1.46%   |
| Seattle            | 2         | 1.46%   |
| Moscow             | 2         | 1.46%   |
| London             | 2         | 1.46%   |
| Hanoi              | 2         | 1.46%   |
| Colorado Springs   | 2         | 1.46%   |
| Bucharest          | 2         | 1.46%   |
| Berlin             | 2         | 1.46%   |
| Bengaluru          | 2         | 1.46%   |
| Zavar              | 1         | 0.73%   |
| Wexford            | 1         | 0.73%   |
| West Linn          | 1         | 0.73%   |
| Weaverville        | 1         | 0.73%   |
| Volendam           | 1         | 0.73%   |
| Vinica             | 1         | 0.73%   |
| Veliky Novgorod    | 1         | 0.73%   |
| Valmiera           | 1         | 0.73%   |
| Utrecht            | 1         | 0.73%   |
| Turner             | 1         | 0.73%   |
| Sydney             | 1         | 0.73%   |
| Stuttgart          | 1         | 0.73%   |
| Stockholm          | 1         | 0.73%   |
| Sofia              | 1         | 0.73%   |
| Shrewsbury         | 1         | 0.73%   |
| Senica             | 1         | 0.73%   |
| Sao Caetano do Sul | 1         | 0.73%   |
| Santiago           | 1         | 0.73%   |
| Santa Cruz         | 1         | 0.73%   |
| Sanaa              | 1         | 0.73%   |
| San Jose           | 1         | 0.73%   |
| San Francisco      | 1         | 0.73%   |
| Rocklin            | 1         | 0.73%   |
| Riverside          | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 38        | 53     | 21.97%  |
| Seagate                     | 20        | 87     | 11.56%  |
| WDC                         | 15        | 20     | 8.67%   |
| SanDisk                     | 15        | 19     | 8.67%   |
| Toshiba                     | 8         | 9      | 4.62%   |
| Kingston                    | 8         | 15     | 4.62%   |
| Unknown                     | 6         | 9      | 3.47%   |
| Intel                       | 6         | 7      | 3.47%   |
| SK hynix                    | 5         | 6      | 2.89%   |
| Micron Technology           | 4         | 7      | 2.31%   |
| KIOXIA                      | 4         | 5      | 2.31%   |
| Kingston Technology Company | 4         | 4      | 2.31%   |
| HGST                        | 4         | 7      | 2.31%   |
| Hewlett-Packard             | 4         | 17     | 2.31%   |
| Crucial                     | 4         | 5      | 2.31%   |
| Phison Electronics          | 3         | 4      | 1.73%   |
| Micron/Crucial Technology   | 3         | 4      | 1.73%   |
| KingFast                    | 2         | 2      | 1.16%   |
| XrayDisk                    | 1         | 2      | 0.58%   |
| Union Memory (Shenzhen)     | 1         | 2      | 0.58%   |
| Transcend                   | 1         | 1      | 0.58%   |
| Silicon Motion              | 1         | 1      | 0.58%   |
| Realtek Semiconductor       | 1         | 1      | 0.58%   |
| Plextor                     | 1         | 1      | 0.58%   |
| Phison                      | 1         | 1      | 0.58%   |
| Lite-On                     | 1         | 1      | 0.58%   |
| Lexar                       | 1         | 1      | 0.58%   |
| Lenovo                      | 1         | 1      | 0.58%   |
| KingSpec                    | 1         | 1      | 0.58%   |
| JMicron Technology          | 1         | 1      | 0.58%   |
| Intenso                     | 1         | 1      | 0.58%   |
| HPE                         | 1         | 1      | 0.58%   |
| Hitachi                     | 1         | 1      | 0.58%   |
| GOODRAM                     | 1         | 1      | 0.58%   |
| Fujitsu                     | 1         | 1      | 0.58%   |
| Emtec                       | 1         | 1      | 0.58%   |
| Apple                       | 1         | 1      | 0.58%   |
| Apacer                      | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 5         | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 2.07%   |
| Seagate ST2000DM008-2FR102 2TB                    | 3         | 1.55%   |
| Samsung SSD 860 EVO 500GB                         | 3         | 1.55%   |
| Unknown SD/MMC/MS PRO 2GB                         | 2         | 1.04%   |
| Seagate ST2000DM001-1ER164 2TB                    | 2         | 1.04%   |
| Seagate ST1000VX000-1ES162 1TB                    | 2         | 1.04%   |
| SanDisk SSD PLUS 1000GB                           | 2         | 1.04%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 2         | 1.04%   |
| Samsung SSD 860 EVO 250GB                         | 2         | 1.04%   |
| Samsung MZVLB512HAJQ-000L7 512GB                  | 2         | 1.04%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD              | 2         | 1.04%   |
| Phison E12 NVMe Controller 1TB                    | 2         | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB               | 2         | 1.04%   |
| Kingston Company SNV2S2000G 2TB                   | 2         | 1.04%   |
| Kingston Company SNV2S1000G 1TB                   | 2         | 1.04%   |
| Intel SSDSA2CW080G3 80GB                          | 2         | 1.04%   |
| Intel SSD 660P Series 512GB                       | 2         | 1.04%   |
| HGST HTS541010A9E680 1TB                          | 2         | 1.04%   |
| Crucial CT500MX500SSD1 500GB                      | 2         | 1.04%   |
| XrayDisk 480GB SSD                                | 1         | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB                      | 1         | 0.52%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                  | 1         | 0.52%   |
| WDC WDS200T2G0A-00JH30 2TB SSD                    | 1         | 0.52%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                  | 1         | 0.52%   |
| WDC WD40PURX-64GVNY0 4TB                          | 1         | 0.52%   |
| WDC WD40PURX-64GVNY0 1 4TB                        | 1         | 0.52%   |
| WDC WD40EFRX-68N32N0 4TB                          | 1         | 0.52%   |
| WDC WD3200BEKT-08PVMT1 320GB                      | 1         | 0.52%   |
| WDC WD30EFRX-68AX9N0 3TB                          | 1         | 0.52%   |
| WDC WD2500AAKX-08U6AA0 250GB                      | 1         | 0.52%   |
| WDC WD20PURX-64P6ZY0 2TB                          | 1         | 0.52%   |
| WDC WD1600YS-23SHB0 160GB                         | 1         | 0.52%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 0.52%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.52%   |
| WDC WD10EZEX-60M2NA0 1TB                          | 1         | 0.52%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 1         | 0.52%   |
| WDC WD10EARS-00Y5B1 1TB                           | 1         | 0.52%   |
| Unknown MMC64G  64GB                              | 1         | 0.52%   |
| Unknown MMC Card  256GB                           | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 87     | 38.46%  |
| WDC                 | 12        | 15     | 23.08%  |
| Toshiba             | 6         | 7      | 11.54%  |
| HGST                | 4         | 7      | 7.69%   |
| Samsung Electronics | 3         | 3      | 5.77%   |
| Unknown             | 2         | 4      | 3.85%   |
| Hewlett-Packard     | 2         | 15     | 3.85%   |
| Hitachi             | 1         | 1      | 1.92%   |
| Fujitsu             | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 27     | 35.71%  |
| SanDisk             | 7         | 10     | 12.5%   |
| Kingston            | 7         | 8      | 12.5%   |
| WDC                 | 4         | 5      | 7.14%   |
| Crucial             | 3         | 4      | 5.36%   |
| Intel               | 2         | 3      | 3.57%   |
| Hewlett-Packard     | 2         | 2      | 3.57%   |
| XrayDisk            | 1         | 2      | 1.79%   |
| Toshiba             | 1         | 1      | 1.79%   |
| Plextor             | 1         | 1      | 1.79%   |
| Lexar               | 1         | 1      | 1.79%   |
| KingSpec            | 1         | 1      | 1.79%   |
| JMicron Technology  | 1         | 1      | 1.79%   |
| Intenso             | 1         | 1      | 1.79%   |
| HPE                 | 1         | 1      | 1.79%   |
| GOODRAM             | 1         | 1      | 1.79%   |
| Emtec               | 1         | 1      | 1.79%   |
| Apacer              | 1         | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 61        | 83     | 37.42%  |
| SSD     | 52        | 71     | 31.9%   |
| HDD     | 44        | 141    | 26.99%  |
| MMC     | 4         | 5      | 2.45%   |
| Unknown | 2         | 2      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 204    | 51.03%  |
| NVMe | 61        | 83     | 42.07%  |
| SAS  | 6         | 10     | 4.14%   |
| MMC  | 4         | 5      | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 76     | 42.86%  |
| 0.51-1.0   | 34        | 72     | 34.69%  |
| 1.01-2.0   | 12        | 52     | 12.24%  |
| 4.01-10.0  | 4         | 5      | 4.08%   |
| 2.01-3.0   | 3         | 3      | 3.06%   |
| 3.01-4.0   | 2         | 3      | 2.04%   |
| 10.01-20.0 | 1         | 1      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 24.41%  |
| 101-250        | 24        | 18.9%   |
| 501-1000       | 23        | 18.11%  |
| 1-20           | 12        | 9.45%   |
| 1001-2000      | 10        | 7.87%   |
| Unknown        | 9         | 7.09%   |
| More than 3000 | 6         | 4.72%   |
| 51-100         | 6         | 4.72%   |
| 2001-3000      | 4         | 3.15%   |
| 21-50          | 2         | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 39        | 29.55%  |
| 21-50          | 30        | 22.73%  |
| 51-100         | 18        | 13.64%  |
| 101-250        | 15        | 11.36%  |
| 251-500        | 9         | 6.82%   |
| Unknown        | 9         | 6.82%   |
| More than 3000 | 5         | 3.79%   |
| 501-1000       | 4         | 3.03%   |
| 1001-2000      | 3         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB                         | 1         | 1      | 12.5%   |
| WDC WD40PURX-64GVNY0 1 4TB                       | 1         | 1      | 12.5%   |
| Seagate ST9750420AS 752GB                        | 1         | 1      | 12.5%   |
| Seagate ST3000DM001-1CH166 3TB                   | 1         | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 12.5%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 2      | 12.5%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 12.5%   |
| Hewlett-Packard SSD S700 120GB                   | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 42.86%  |
| Samsung Electronics | 2         | 3      | 28.57%  |
| WDC                 | 1         | 2      | 14.29%  |
| Hewlett-Packard     | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 60%     |
| WDC                 | 1         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 71.43%  |
| SSD  | 2         | 3      | 28.57%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 68        | 181    | 50.75%  |
| Detected | 59        | 112    | 44.03%  |
| Malfunc  | 7         | 9      | 5.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 81        | 50%     |
| Samsung Electronics          | 19        | 11.73%  |
| AMD                          | 9         | 5.56%   |
| Sandisk                      | 8         | 4.94%   |
| Broadcom / LSI               | 7         | 4.32%   |
| SK hynix                     | 5         | 3.09%   |
| Kingston Technology Company  | 5         | 3.09%   |
| Phison Electronics           | 4         | 2.47%   |
| Micron/Crucial Technology    | 4         | 2.47%   |
| Micron Technology            | 4         | 2.47%   |
| KIOXIA                       | 4         | 2.47%   |
| Adaptec                      | 2         | 1.23%   |
| VIA Technologies             | 1         | 0.62%   |
| Union Memory (Shenzhen)      | 1         | 0.62%   |
| Transcend                    | 1         | 0.62%   |
| Toshiba America Info Systems | 1         | 0.62%   |
| Silicon Motion               | 1         | 0.62%   |
| Realtek Semiconductor        | 1         | 0.62%   |
| LSI Logic / Symbios Logic    | 1         | 0.62%   |
| Lite-On Technology           | 1         | 0.62%   |
| Lenovo                       | 1         | 0.62%   |
| Hewlett-Packard              | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 5.49%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 3.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 3.3%    |
| Intel SATA Controller [RAID Mode]                                                       | 5         | 2.75%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4         | 2.2%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 1.65%   |
| Phison E12 NVMe Controller                                                              | 3         | 1.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3         | 1.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.65%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3         | 1.65%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3         | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.65%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                                   | 2         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.1%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 2         | 1.1%    |
| Intel SSD 660P Series                                                                   | 2         | 1.1%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2         | 1.1%    |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 2         | 1.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.1%    |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 1.1%    |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                            | 2         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 43.37%  |
| NVMe | 61        | 36.75%  |
| RAID | 15        | 9.04%   |
| IDE  | 10        | 6.02%   |
| SAS  | 5         | 3.01%   |
| SCSI | 3         | 1.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 113       | 91.13%  |
| AMD    | 11        | 8.87%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core Ultra 7 165H                 | 3         | 2.42%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 2.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 2.42%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 2.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 2.42%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 2         | 1.61%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz     | 2         | 1.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2         | 1.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 1.61%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 2         | 1.61%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 1.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 1.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.61%   |
| Intel 12th Gen Core i7-1270P            | 2         | 1.61%   |
| Intel 12th Gen Core i7-1260P            | 2         | 1.61%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 2         | 1.61%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 2         | 1.61%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 1         | 0.81%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 1         | 0.81%   |
| Intel Xeon CPU X3450 @ 2.67GHz          | 1         | 0.81%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 0.81%   |
| Intel Xeon CPU E5649 @ 2.53GHz          | 1         | 0.81%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz     | 1         | 0.81%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz     | 1         | 0.81%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.81%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 0.81%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 1         | 0.81%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz     | 1         | 0.81%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 0.81%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.81%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 0.81%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 1         | 0.81%   |
| Intel Pentium CPU G2020 @ 2.90GHz       | 1         | 0.81%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 0.81%   |
| Intel Core i9-14900HX                   | 1         | 0.81%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.81%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 0.81%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 36        | 29.03%  |
| Other             | 22        | 17.74%  |
| Intel Core i5     | 21        | 16.94%  |
| Intel Xeon        | 15        | 12.1%   |
| Intel Core i3     | 6         | 4.84%   |
| Intel Celeron     | 4         | 3.23%   |
| Intel Pentium     | 3         | 2.42%   |
| Intel Core i9     | 3         | 2.42%   |
| Intel Core        | 3         | 2.42%   |
| AMD Ryzen 5       | 3         | 2.42%   |
| AMD Ryzen 7       | 2         | 1.61%   |
| Intel Xeon Silver | 1         | 0.81%   |
| Intel Core 2 Duo  | 1         | 0.81%   |
| AMD Ryzen 9       | 1         | 0.81%   |
| AMD Ryzen 7 PRO   | 1         | 0.81%   |
| AMD FX            | 1         | 0.81%   |
| AMD A8            | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 44        | 35.48%  |
| 2      | 32        | 25.81%  |
| 6      | 11        | 8.87%   |
| 12     | 10        | 8.06%   |
| 8      | 8         | 6.45%   |
| 16     | 7         | 5.65%   |
| 10     | 6         | 4.84%   |
| 20     | 2         | 1.61%   |
| 14     | 2         | 1.61%   |
| 24     | 1         | 0.81%   |
| 1      | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 118       | 95.16%  |
| 2      | 6         | 4.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 102       | 82.26%  |
| 1      | 22        | 17.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 123       | 98.4%   |
| Unknown        | 2         | 1.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 21.09%  |
| 0x806ec    | 7         | 5.47%   |
| 0x306c3    | 7         | 5.47%   |
| 0x306a9    | 7         | 5.47%   |
| 0x206a7    | 6         | 4.69%   |
| 0x806ea    | 5         | 3.91%   |
| 0x906a3    | 4         | 3.13%   |
| 0x806c1    | 4         | 3.13%   |
| 0x906ea    | 3         | 2.34%   |
| 0x806e9    | 3         | 2.34%   |
| 0x506e3    | 3         | 2.34%   |
| 0x40651    | 3         | 2.34%   |
| 0x306e4    | 3         | 2.34%   |
| 0x306d4    | 3         | 2.34%   |
| 0xb06a2    | 2         | 1.56%   |
| 0xa0655    | 2         | 1.56%   |
| 0xa0652    | 2         | 1.56%   |
| 0x906ed    | 2         | 1.56%   |
| 0x906e9    | 2         | 1.56%   |
| 0x90672    | 2         | 1.56%   |
| 0x706a8    | 2         | 1.56%   |
| 0x406f1    | 2         | 1.56%   |
| 0x406e3    | 2         | 1.56%   |
| 0x406c4    | 2         | 1.56%   |
| 0x206c2    | 2         | 1.56%   |
| 0x106e5    | 2         | 1.56%   |
| 0xb06f2    | 1         | 0.78%   |
| 0xa0653    | 1         | 0.78%   |
| 0x806d1    | 1         | 0.78%   |
| 0x706e5    | 1         | 0.78%   |
| 0x506c9    | 1         | 0.78%   |
| 0x50654    | 1         | 0.78%   |
| 0x306f2    | 1         | 0.78%   |
| 0x20655    | 1         | 0.78%   |
| 0x10676    | 1         | 0.78%   |
| 0x0b204011 | 1         | 0.78%   |
| 0x0a50000c | 1         | 0.78%   |
| 0x08701030 | 1         | 0.78%   |
| 0x08701013 | 1         | 0.78%   |
| 0x08608108 | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 25        | 20.16%  |
| Haswell           | 13        | 10.48%  |
| IvyBridge         | 12        | 9.68%   |
| Alderlake Hybrid  | 10        | 8.06%   |
| SandyBridge       | 7         | 5.65%   |
| CometLake         | 7         | 5.65%   |
| Unknown           | 7         | 5.65%   |
| Skylake           | 6         | 4.84%   |
| Broadwell         | 6         | 4.84%   |
| TigerLake         | 5         | 4.03%   |
| Westmere          | 4         | 3.23%   |
| Meteorlake Hybrid | 3         | 2.42%   |
| IceLake           | 3         | 2.42%   |
| Zen 2             | 2         | 1.61%   |
| Silvermont        | 2         | 1.61%   |
| Nehalem           | 2         | 1.61%   |
| Goldmont plus     | 2         | 1.61%   |
| Zen+              | 1         | 0.81%   |
| Zen 3             | 1         | 0.81%   |
| Zen               | 1         | 0.81%   |
| Puma              | 1         | 0.81%   |
| Piledriver        | 1         | 0.81%   |
| Penryn            | 1         | 0.81%   |
| Goldmont          | 1         | 0.81%   |
| Excavator         | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 83        | 54.25%  |
| Nvidia                     | 42        | 27.45%  |
| AMD                        | 18        | 11.76%  |
| Matrox Electronics Systems | 9         | 5.88%   |
| ASPEED Technology          | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 6         | 3.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 3.27%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 5         | 3.27%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 5         | 3.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.27%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4         | 2.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 2.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 2.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.96%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 3         | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.31%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.31%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.31%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2         | 1.31%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.31%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 2         | 1.31%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 2         | 1.31%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.31%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 2         | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.31%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 1.31%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 1.31%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.31%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 0.65%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.65%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.65%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 45.24%  |
| 1 x Nvidia     | 19        | 15.08%  |
| Intel + Nvidia | 19        | 15.08%  |
| 1 x AMD        | 11        | 8.73%   |
| 1 x Matrox     | 8         | 6.35%   |
| AMD + Nvidia   | 4         | 3.17%   |
| Other          | 3         | 2.38%   |
| Intel + AMD    | 3         | 2.38%   |
| 1 x ASPEED     | 1         | 0.79%   |
| AMD + Matrox   | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 102       | 80.95%  |
| Unknown     | 16        | 12.7%   |
| Proprietary | 8         | 6.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 65.08%  |
| 3.01-4.0   | 15        | 11.9%   |
| 1.01-2.0   | 15        | 11.9%   |
| 0.51-1.0   | 4         | 3.17%   |
| 7.01-8.0   | 3         | 2.38%   |
| 5.01-6.0   | 3         | 2.38%   |
| 0.01-0.5   | 3         | 2.38%   |
| 8.01-16.0  | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 19        | 12.84%  |
| AU Optronics         | 18        | 12.16%  |
| Samsung Electronics  | 17        | 11.49%  |
| Dell                 | 16        | 10.81%  |
| LG Display           | 15        | 10.14%  |
| BOE                  | 10        | 6.76%   |
| BenQ                 | 6         | 4.05%   |
| Lenovo               | 5         | 3.38%   |
| Hewlett-Packard      | 5         | 3.38%   |
| Goldstar             | 4         | 2.7%    |
| ViewSonic            | 3         | 2.03%   |
| InfoVision           | 3         | 2.03%   |
| ASUSTek Computer     | 3         | 2.03%   |
| AOC                  | 3         | 2.03%   |
| Acer                 | 3         | 2.03%   |
| Sharp                | 2         | 1.35%   |
| Vizio                | 1         | 0.68%   |
| Viotek               | 1         | 0.68%   |
| Sony                 | 1         | 0.68%   |
| Sceptre Tech         | 1         | 0.68%   |
| SAC                  | 1         | 0.68%   |
| Philips              | 1         | 0.68%   |
| Panasonic            | 1         | 0.68%   |
| Packard Bell         | 1         | 0.68%   |
| ODH                  | 1         | 0.68%   |
| Gigabyte Technology  | 1         | 0.68%   |
| GameMax              | 1         | 0.68%   |
| Fujitsu Siemens      | 1         | 0.68%   |
| Element              | 1         | 0.68%   |
| Eizo                 | 1         | 0.68%   |
| BOE Technology Group | 1         | 0.68%   |
| Ancor Communications | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34H89x SAM0E26 3440x1440 797x333mm 34.0-inch    | 4         | 2.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 1.92%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch         | 2         | 1.28%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 1.28%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 518x324mm 24.1-inch          | 2         | 1.28%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch           | 2         | 1.28%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                    | 2         | 1.28%   |
| Dell P2722H DEL4240 1920x1080 598x336mm 27.0-inch                    | 2         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 2         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 2         | 1.28%   |
| BOE LCD Monitor BOE0B13 1920x1200 302x188mm 14.0-inch                | 2         | 1.28%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 2         | 1.28%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                    | 2         | 1.28%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 2         | 1.28%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 2         | 1.28%   |
| ASUSTek Computer PA248QV AUS2400 1920x1200 518x324mm 24.1-inch       | 2         | 1.28%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                    | 2         | 1.28%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                     | 2         | 1.28%   |
| Vizio V505-J09 VIZ1039 3840x2160 1096x616mm 49.5-inch                | 1         | 0.64%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                 | 1         | 0.64%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 1         | 0.64%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch             | 1         | 0.64%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch        | 1         | 0.64%   |
| Sony TV SNY4502 1920x1080                                            | 1         | 0.64%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 1         | 0.64%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 1         | 0.64%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch       | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch  | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch | 1         | 0.64%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 376x301mm 19.0-inch    | 1         | 0.64%   |
| Samsung Electronics S34C65xU SAM73FE 3440x1440 798x334mm 34.1-inch   | 1         | 0.64%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch    | 1         | 0.64%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1         | 0.64%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch    | 1         | 0.64%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch    | 1         | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1         | 0.64%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch    | 1         | 0.64%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1         | 0.64%   |
| Samsung Electronics LS34A650U SAM7144 3440x1440 798x334mm 34.1-inch  | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 47.33%  |
| 1366x768 (WXGA)    | 11        | 8.4%    |
| 3840x2160 (4K)     | 10        | 7.63%   |
| 1920x1200 (WUXGA)  | 10        | 7.63%   |
| 1280x1024 (SXGA)   | 6         | 4.58%   |
| 3440x1440          | 5         | 3.82%   |
| 1600x900 (HD+)     | 5         | 3.82%   |
| 2560x1440 (QHD)    | 4         | 3.05%   |
| 1680x1050 (WSXGA+) | 3         | 2.29%   |
| 2560x1600          | 2         | 1.53%   |
| 2560x1080          | 2         | 1.53%   |
| 3840x2400          | 1         | 0.76%   |
| 3840x1600          | 1         | 0.76%   |
| 3840x1200          | 1         | 0.76%   |
| 3840x1080          | 1         | 0.76%   |
| 2880x1920          | 1         | 0.76%   |
| 2880x1800          | 1         | 0.76%   |
| 1920x540           | 1         | 0.76%   |
| 1600x1200          | 1         | 0.76%   |
| 1360x768           | 1         | 0.76%   |
| 1280x800 (WXGA)    | 1         | 0.76%   |
| Unknown            | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 17.88%  |
| 14      | 21        | 13.91%  |
| 24      | 17        | 11.26%  |
| 13      | 15        | 9.93%   |
| 27      | 10        | 6.62%   |
| 23      | 7         | 4.64%   |
| 31      | 6         | 3.97%   |
| 21      | 6         | 3.97%   |
| 34      | 5         | 3.31%   |
| 19      | 4         | 2.65%   |
| Unknown | 4         | 2.65%   |
| 32      | 3         | 1.99%   |
| 17      | 3         | 1.99%   |
| 16      | 3         | 1.99%   |
| 38      | 2         | 1.32%   |
| 25      | 2         | 1.32%   |
| 22      | 2         | 1.32%   |
| 20      | 2         | 1.32%   |
| 18      | 2         | 1.32%   |
| 84      | 1         | 0.66%   |
| 74      | 1         | 0.66%   |
| 72      | 1         | 0.66%   |
| 48      | 1         | 0.66%   |
| 37      | 1         | 0.66%   |
| 29      | 1         | 0.66%   |
| 28      | 1         | 0.66%   |
| 26      | 1         | 0.66%   |
| 12      | 1         | 0.66%   |
| 11      | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 42.76%  |
| 501-600     | 32        | 22.07%  |
| 401-500     | 10        | 6.9%    |
| 601-700     | 9         | 6.21%   |
| 701-800     | 8         | 5.52%   |
| 201-300     | 7         | 4.83%   |
| 351-400     | 6         | 4.14%   |
| Unknown     | 4         | 2.76%   |
| 801-900     | 3         | 2.07%   |
| 1501-2000   | 3         | 2.07%   |
| 1001-1500   | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 69.67%  |
| 16/10   | 18        | 14.75%  |
| 21/9    | 8         | 6.56%   |
| 5/4     | 6         | 4.92%   |
| 32/9    | 2         | 1.64%   |
| Unknown | 2         | 1.64%   |
| 4/3     | 1         | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 31        | 21.53%  |
| 101-110        | 27        | 18.75%  |
| 201-250        | 23        | 15.97%  |
| 351-500        | 13        | 9.03%   |
| 301-350        | 12        | 8.33%   |
| 251-300        | 6         | 4.17%   |
| 151-200        | 6         | 4.17%   |
| 71-80          | 5         | 3.47%   |
| 501-1000       | 4         | 2.78%   |
| Unknown        | 4         | 2.78%   |
| More than 1000 | 3         | 2.08%   |
| 141-150        | 3         | 2.08%   |
| 111-120        | 3         | 2.08%   |
| 121-130        | 2         | 1.39%   |
| 61-70          | 1         | 0.69%   |
| 51-60          | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 47        | 34.06%  |
| 51-100        | 46        | 33.33%  |
| 101-120       | 25        | 18.12%  |
| 161-240       | 12        | 8.7%    |
| Unknown       | 4         | 2.9%    |
| More than 240 | 3         | 2.17%   |
| 1-50          | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 70        | 54.69%  |
| 2     | 29        | 22.66%  |
| 0     | 18        | 14.06%  |
| 3     | 10        | 7.81%   |
| 4     | 1         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 94        | 50%     |
| Realtek Semiconductor             | 48        | 25.53%  |
| Qualcomm Atheros                  | 9         | 4.79%   |
| Broadcom                          | 9         | 4.79%   |
| Lenovo                            | 4         | 2.13%   |
| Broadcom Limited                  | 3         | 1.6%    |
| ASIX Electronics                  | 3         | 1.6%    |
| Samsung Electronics               | 2         | 1.06%   |
| Mellanox Technologies             | 2         | 1.06%   |
| Sierra Wireless                   | 1         | 0.53%   |
| Shenzhen Goodix Technology        | 1         | 0.53%   |
| Realtek                           | 1         | 0.53%   |
| Ralink Technology                 | 1         | 0.53%   |
| QLogic                            | 1         | 0.53%   |
| NetGear                           | 1         | 0.53%   |
| MediaTek                          | 1         | 0.53%   |
| Huawei Technologies               | 1         | 0.53%   |
| Fibocom                           | 1         | 0.53%   |
| Ericsson Business Mobile Networks | 1         | 0.53%   |
| Edimax Technology                 | 1         | 0.53%   |
| DisplayLink                       | 1         | 0.53%   |
| D-Link                            | 1         | 0.53%   |
| ASUSTek Computer                  | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 9.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 4.98%   |
| Intel Wireless 8265 / 8275                                             | 11        | 4.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 4.15%   |
| Intel 82574L Gigabit Network Connection                                | 7         | 2.9%    |
| Intel Wireless 7260                                                    | 6         | 2.49%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 2.49%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 1.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 1.66%   |
| Intel Wireless 8260                                                    | 4         | 1.66%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.66%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 1.24%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 1.24%   |
| Intel Wireless 7265                                                    | 3         | 1.24%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 3         | 1.24%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 1.24%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 1.24%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.24%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.24%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.24%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.24%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.83%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 2         | 0.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.83%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 69        | 70.41%  |
| Realtek Semiconductor | 10        | 10.2%   |
| Qualcomm Atheros      | 7         | 7.14%   |
| Broadcom Limited      | 2         | 2.04%   |
| Broadcom              | 2         | 2.04%   |
| Sierra Wireless       | 1         | 1.02%   |
| Ralink Technology     | 1         | 1.02%   |
| NetGear               | 1         | 1.02%   |
| MediaTek              | 1         | 1.02%   |
| Fibocom               | 1         | 1.02%   |
| Edimax Technology     | 1         | 1.02%   |
| D-Link                | 1         | 1.02%   |
| ASUSTek Computer      | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                      | 11        | 11.22%  |
| Intel Wireless 7260                                                             | 6         | 6.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                | 5         | 5.1%    |
| Intel Wireless 8260                                                             | 4         | 4.08%   |
| Intel Wi-Fi 6 AX201                                                             | 4         | 4.08%   |
| Intel Wireless 7265                                                             | 3         | 3.06%   |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 3         | 3.06%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 3         | 3.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 3         | 3.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                        | 3         | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 2         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 2         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 2         | 2.04%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                 | 2         | 2.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 2         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 2         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                 | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 2         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 2         | 2.04%   |
| Intel Centrino Ultimate-N 6300                                                  | 2         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 2         | 2.04%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter            | 2         | 2.04%   |
| Sierra Wireless EM7455                                                          | 1         | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                              | 1         | 1.02%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                     | 1         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                 | 1         | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                        | 1         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                 | 1         | 1.02%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                 | 1         | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                                      | 1         | 1.02%   |
| Realtek 802.11ac NIC                                                            | 1         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                                 | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 1         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                | 1         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                  | 1         | 1.02%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                                 | 1         | 1.02%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 1         | 1.02%   |
| Intel Wi-Fi 6 AX200                                                             | 1         | 1.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 1         | 1.02%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                         | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 46.97%  |
| Realtek Semiconductor | 45        | 34.09%  |
| Broadcom              | 7         | 5.3%    |
| Lenovo                | 4         | 3.03%   |
| ASIX Electronics      | 3         | 2.27%   |
| Samsung Electronics   | 2         | 1.52%   |
| Qualcomm Atheros      | 2         | 1.52%   |
| Mellanox Technologies | 2         | 1.52%   |
| Realtek               | 1         | 0.76%   |
| QLogic                | 1         | 0.76%   |
| Huawei Technologies   | 1         | 0.76%   |
| DisplayLink           | 1         | 0.76%   |
| Broadcom Limited      | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 15.6%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 8.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 7.09%   |
| Intel 82574L Gigabit Network Connection                                | 7         | 4.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 2.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 2.84%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 2.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 2.13%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 2.13%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 2.13%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.13%   |
| Intel Ethernet Controller I225-V                                       | 3         | 2.13%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2.13%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 2.13%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.42%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 2         | 1.42%   |
| Intel Ethernet Controller I226-V                                       | 2         | 1.42%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.42%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 1.42%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2         | 1.42%   |
| Realtek USB 10/100/1000 LAN                                            | 1         | 0.71%   |
| Realtek Killer E5000 5GbE Controller                                   | 1         | 0.71%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1         | 0.71%   |
| Lenovo ThinkPad TBT3 LAN                                               | 1         | 0.71%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.71%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.71%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.71%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 0.71%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 110       | 54.19%  |
| WiFi     | 91        | 44.83%  |
| Modem    | 2         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 73        | 57.03%  |
| WiFi     | 55        | 42.97%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 57.26%  |
| 1     | 42        | 33.87%  |
| 3     | 4         | 3.23%   |
| 6     | 3         | 2.42%   |
| 4     | 3         | 2.42%   |
| 7     | 1         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 97        | 75.19%  |
| Yes  | 32        | 24.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 70.13%  |
| Qualcomm Atheros Communications | 6         | 7.79%   |
| Realtek Semiconductor           | 5         | 6.49%   |
| Broadcom                        | 3         | 3.9%    |
| Apple                           | 3         | 3.9%    |
| ASUSTek Computer                | 2         | 2.6%    |
| IMC Networks                    | 1         | 1.3%    |
| Foxconn / Hon Hai               | 1         | 1.3%    |
| Cambridge Silicon Radio         | 1         | 1.3%    |
| Alps Electric                   | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 22.08%  |
| Intel Bluetooth Device                              | 13        | 16.88%  |
| Intel AX201 Bluetooth                               | 10        | 12.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 10.39%  |
| Realtek Bluetooth Radio                             | 3         | 3.9%    |
| Apple Bluetooth Host Controller                     | 3         | 3.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.6%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 2.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.6%    |
| Intel AX210 Bluetooth                               | 2         | 2.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 2.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.3%    |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.3%    |
| IMC Networks Bluetooth Radio                        | 1         | 1.3%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.3%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.3%    |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 101       | 57.39%  |
| Nvidia                 | 29        | 16.48%  |
| AMD                    | 19        | 10.8%   |
| Lenovo                 | 6         | 3.41%   |
| GN Netcom              | 6         | 3.41%   |
| C-Media Electronics    | 3         | 1.7%    |
| Plantronics            | 2         | 1.14%   |
| Creative Technology    | 2         | 1.14%   |
| Unknown                | 1         | 0.57%   |
| TEAC                   | 1         | 0.57%   |
| RME                    | 1         | 0.57%   |
| Realtek Semiconductor  | 1         | 0.57%   |
| M-Audio                | 1         | 0.57%   |
| JMTek                  | 1         | 0.57%   |
| Creative Labs          | 1         | 0.57%   |
| AKAI Professional M.I. | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 6.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 3.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 3.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 2.51%   |
| AMD Ryzen HD Audio Controller                                                                     | 5         | 2.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.01%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 2.01%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 1.51%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.51%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 3         | 1.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.51%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 3         | 1.51%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 1.51%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 3         | 1.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.51%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 1.51%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.51%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 1.51%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.51%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.01%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.01%   |
| Nvidia GF110 High Definition Audio Controller                                                     | 2         | 1.01%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 1.01%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 2         | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.01%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.01%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 2         | 1.01%   |
| Creative Technology Sound BlasterX G1                                                             | 2         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 16        | 18.82%  |
| Micron Technology                       | 15        | 17.65%  |
| SK hynix                                | 13        | 15.29%  |
| Kingston                                | 7         | 8.24%   |
| Unknown                                 | 7         | 8.24%   |
| Unknown                                 | 5         | 5.88%   |
| Crucial                                 | 4         | 4.71%   |
| Corsair                                 | 4         | 4.71%   |
| Avant                                   | 2         | 2.35%   |
| Unknown (0x0C26)                        | 1         | 1.18%   |
| Unigen                                  | 1         | 1.18%   |
| Smart                                   | 1         | 1.18%   |
| Silicon Power Computer & Communications | 1         | 1.18%   |
| Patriot                                 | 1         | 1.18%   |
| Nanya Technology                        | 1         | 1.18%   |
| HPE                                     | 1         | 1.18%   |
| Hewlett-Packard                         | 1         | 1.18%   |
| Essencore                               | 1         | 1.18%   |
| AVEXIR                                  | 1         | 1.18%   |
| A-DATA Technology                       | 1         | 1.18%   |
| 4ea5                                    | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 7         | 7.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 3         | 3.23%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s          | 2         | 2.15%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 2         | 2.15%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                     | 1         | 1.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1         | 1.08%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                      | 1         | 1.08%   |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                  | 1         | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                     | 1         | 1.08%   |
| Unknown (0x0C26) RAM TIMETEC-UD4-3200 32GB DIMM DDR4 3200MT/s | 1         | 1.08%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 1.08%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s         | 1         | 1.08%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                 | 1         | 1.08%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s        | 1         | 1.08%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s            | 1         | 1.08%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.08%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s  | 1         | 1.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s  | 1         | 1.08%   |
| SK hynix RAM HMA84GR7AFR4N-UH 32GB DIMM DDR4 2400MT/s         | 1         | 1.08%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.08%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 1         | 1.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.08%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.08%   |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s           | 1         | 1.08%   |
| Silicon Power & RAM Module 16GB SODIMM DDR4 2667MT/s          | 1         | 1.08%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                   | 1         | 1.08%   |
| Samsung RAM Module 32GB SODIMM DDR5 5600MT/s                  | 1         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.08%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 1         | 1.08%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.08%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.08%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 1.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.08%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s          | 1         | 1.08%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s          | 1         | 1.08%   |
| Samsung RAM K3KL9L90CM-MGCT 8GB SODIMM LPDDR5 7500MT/s        | 1         | 1.08%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s               | 1         | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 43        | 56.58%  |
| DDR3   | 21        | 27.63%  |
| LPDDR5 | 6         | 7.89%   |
| DDR5   | 3         | 3.95%   |
| LPDDR4 | 2         | 2.63%   |
| DRAM   | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 54.67%  |
| DIMM         | 25        | 33.33%  |
| Row Of Chips | 8         | 10.67%  |
| Unknown      | 1         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 29        | 35.37%  |
| 16384 | 23        | 28.05%  |
| 4096  | 17        | 20.73%  |
| 32768 | 9         | 10.98%  |
| 2048  | 3         | 3.66%   |
| 1024  | 1         | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 17        | 21.52%  |
| 3200    | 13        | 16.46%  |
| 1600    | 9         | 11.39%  |
| 1333    | 9         | 11.39%  |
| 2400    | 7         | 8.86%   |
| 2666    | 4         | 5.06%   |
| 6400    | 3         | 3.8%    |
| 7467    | 2         | 2.53%   |
| 5600    | 2         | 2.53%   |
| 3466    | 2         | 2.53%   |
| 7500    | 1         | 1.27%   |
| 4800    | 1         | 1.27%   |
| 4267    | 1         | 1.27%   |
| 2934    | 1         | 1.27%   |
| 2600    | 1         | 1.27%   |
| 2448    | 1         | 1.27%   |
| 2133    | 1         | 1.27%   |
| 1866    | 1         | 1.27%   |
| 1334    | 1         | 1.27%   |
| 800     | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 23.68%  |
| Microdia                               | 8         | 10.53%  |
| Logitech                               | 8         | 10.53%  |
| IMC Networks                           | 8         | 10.53%  |
| Realtek Semiconductor                  | 7         | 9.21%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.26%   |
| Suyin                                  | 3         | 3.95%   |
| Quanta                                 | 3         | 3.95%   |
| Luxvisions Innotech Limited            | 3         | 3.95%   |
| Lite-On Technology                     | 3         | 3.95%   |
| Bison Electronics                      | 3         | 3.95%   |
| Apple                                  | 2         | 2.63%   |
| Sunplus Innovation Technology          | 1         | 1.32%   |
| Shinetech                              | 1         | 1.32%   |
| Samsung Electronics                    | 1         | 1.32%   |
| OPPO Electronics                       | 1         | 1.32%   |
| Microsoft                              | 1         | 1.32%   |
| Generalplus Technology                 | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 7         | 9.09%   |
| IMC Networks Integrated Camera                    | 4         | 5.19%   |
| Realtek Integrated_Webcam_FHD                     | 3         | 3.9%    |
| Microdia Webcam Vitade AF                         | 3         | 3.9%    |
| Microdia Integrated_Webcam_HD                     | 3         | 3.9%    |
| Logitech BRIO Ultra HD Webcam                     | 3         | 3.9%    |
| Realtek Integrated_Webcam_HD                      | 2         | 2.6%    |
| Quanta HP HD Camera                               | 2         | 2.6%    |
| Lite-On Integrated Camera                         | 2         | 2.6%    |
| IMC Networks VGA UVC WebCam                       | 2         | 2.6%    |
| Chicony TOSHIBA Web Camera - HD                   | 2         | 2.6%    |
| Chicony Integrated Camera (1280x720@30)           | 2         | 2.6%    |
| Bison SunplusIT Integrated Camera                 | 2         | 2.6%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 2         | 2.6%    |
| Suyin Integrated_Webcam_HD                        | 1         | 1.3%    |
| Suyin HP Truevision HD                            | 1         | 1.3%    |
| Suyin Asus Integrated Webcam                      | 1         | 1.3%    |
| Sunplus Integrated_Webcam_FHD                     | 1         | 1.3%    |
| Shinetech ASUS FHD webcam                         | 1         | 1.3%    |
| Samsung Galaxy series, misc. (MTP mode)           | 1         | 1.3%    |
| Realtek USB Camera                                | 1         | 1.3%    |
| Realtek EasyCamera                                | 1         | 1.3%    |
| Quanta HP Webcam                                  | 1         | 1.3%    |
| OPPO OnePlus 13R                                  | 1         | 1.3%    |
| Microsoft LifeCam HD-3000                         | 1         | 1.3%    |
| Microdia Integrated_Webcam_FHD                    | 1         | 1.3%    |
| Microdia Dell Laptop Integrated Webcam HD         | 1         | 1.3%    |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.3%    |
| Luxvisions Innotech Limited HP 5MP Camera         | 1         | 1.3%    |
| Luxvisions Innotech Limited EasyCamera 1M         | 1         | 1.3%    |
| Logitech Webcam C920-C                            | 1         | 1.3%    |
| Logitech Webcam C270                              | 1         | 1.3%    |
| Logitech Logitech Webcam C925e                    | 1         | 1.3%    |
| Logitech HD Webcam C615                           | 1         | 1.3%    |
| Logitech HD Webcam C510                           | 1         | 1.3%    |
| Lite-On HP HD Camera                              | 1         | 1.3%    |
| IMC Networks USB2.0 HD UVC WebCam                 | 1         | 1.3%    |
| IMC Networks SunplusIT Integrated Camera          | 1         | 1.3%    |
| Generalplus GENERAL WEBCAM                        | 1         | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam                     | 1         | 1.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 44%     |
| Synaptics                  | 9         | 36%     |
| Shenzhen Goodix Technology | 2         | 8%      |
| Upek                       | 1         | 4%      |
| Elan Microelectronics      | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 12%     |
| Validity Sensors Synaptics WBDI                                            | 3         | 12%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 12%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 12%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 8%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 8%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 8%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4%      |
| Synaptics WBDI                                                             | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4%      |
| Shenzhen Goodix FingerPrint                                                | 1         | 4%      |
| Elan ELAN:Fingerprint                                                      | 1         | 4%      |
| AuthenTec Fingerprint Sensor                                               | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 75%     |
| Alcor Micro | 3         | 18.75%  |
| Lenovo      | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 7         | 43.75%  |
| Broadcom BCM5880 Secure Applications Processor                              | 3         | 18.75%  |
| Broadcom 58200                                                              | 2         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                         | 2         | 12.5%   |
| Lenovo Integrated Smart Card Reader                                         | 1         | 6.25%   |
| Alcor Micro Watchdata W 1981                                                | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 53        | 41.09%  |
| 1     | 51        | 39.53%  |
| 2     | 17        | 13.18%  |
| 3     | 7         | 5.43%   |
| 7     | 1         | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 25        | 24.04%  |
| Graphics card            | 21        | 20.19%  |
| Net/wireless             | 14        | 13.46%  |
| Chipcard                 | 13        | 12.5%   |
| Unassigned class         | 6         | 5.77%   |
| Communication controller | 6         | 5.77%   |
| Bluetooth                | 4         | 3.85%   |
| Sound                    | 3         | 2.88%   |
| Multimedia controller    | 3         | 2.88%   |
| Card reader              | 3         | 2.88%   |
| Storage                  | 2         | 1.92%   |
| Firewire controller      | 2         | 1.92%   |
| Net/ethernet             | 1         | 0.96%   |
| Camera                   | 1         | 0.96%   |

