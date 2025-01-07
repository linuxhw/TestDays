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

Total: 166

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Oracle Linux 8.5  | 13        | 10.48%  |
| Oracle Linux 9.3  | 12        | 9.68%   |
| Oracle Linux 8.3  | 12        | 9.68%   |
| Oracle Linux 9.4  | 10        | 8.06%   |
| Oracle Linux 9.2  | 10        | 8.06%   |
| Oracle Linux 8.9  | 10        | 8.06%   |
| Oracle Linux 8.8  | 7         | 5.65%   |
| Oracle Linux 8.4  | 7         | 5.65%   |
| Oracle Linux 8.6  | 6         | 4.84%   |
| Oracle Linux 9.1  | 5         | 4.03%   |
| Oracle Linux 9.0  | 5         | 4.03%   |
| Oracle Linux 8.7  | 5         | 4.03%   |
| Oracle Linux 9.5  | 4         | 3.23%   |
| Oracle Linux 7.9  | 4         | 3.23%   |
| Oracle Linux 8.1  | 3         | 2.42%   |
| Oracle Linux 7.7  | 3         | 2.42%   |
| Oracle Linux 8.2  | 2         | 1.61%   |
| Oracle Linux 7.8  | 2         | 1.61%   |
| Oracle Linux 7.6  | 2         | 1.61%   |
| Oracle Linux 7.4  | 1         | 0.81%   |
| Oracle Linux 6.10 | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 113       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.15.0-200.131.27.el9uek.x86_64   | 4         | 2.99%   |
| 5.4.17-2102.202.5.el8uek.x86_64   | 3         | 2.24%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 2.24%   |
| 5.15.0-206.153.7.el9uek.x86_64    | 3         | 2.24%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 3         | 2.24%   |
| 5.15.0-101.103.2.1.el9uek.x86_64  | 3         | 2.24%   |
| 5.15.0-100.96.32.el8uek.x86_64    | 3         | 2.24%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 2.24%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 2         | 1.49%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 1.49%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 2         | 1.49%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 2         | 1.49%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 2         | 1.49%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2         | 1.49%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2         | 1.49%   |
| 5.15.0-206.153.7.1.el9uek.x86_64  | 2         | 1.49%   |
| 5.15.0-205.149.5.1.el9uek.x86_64  | 2         | 1.49%   |
| 5.15.0-200.131.27.el8uek.x86_64   | 2         | 1.49%   |
| 5.15.0-200.131.27.1.el8uek.x86_64 | 2         | 1.49%   |
| 5.15.0-106.131.4.el9uek.x86_64    | 2         | 1.49%   |
| 5.15.0-103.114.4.el8uek.x86_64    | 2         | 1.49%   |
| 5.14.0-503.16.1.el9_5.x86_64      | 2         | 1.49%   |
| 5.14.0-427.22.1.el9_4.x86_64      | 2         | 1.49%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 2         | 1.49%   |
| 4.18.0-193.1.2.el8_2.x86_64       | 2         | 1.49%   |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 1.49%   |
| 5.4.17-2136.330.7.1.el8uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.326.6.el8uek.x86_64   | 1         | 0.75%   |
| 5.4.17-2136.318.7.2.el8uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 0.75%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 0.75%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1         | 0.75%   |
| 5.4.17-2136.308.9.el7uek.x86_64   | 1         | 0.75%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64 | 1         | 0.75%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64 | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 41        | 35.34%  |
| 5.4.17  | 31        | 26.72%  |
| 4.18.0  | 18        | 15.52%  |
| 5.14.0  | 12        | 10.34%  |
| 4.14.35 | 5         | 4.31%   |
| 3.10.0  | 3         | 2.59%   |
| 5.4.11  | 1         | 0.86%   |
| 5.15.2  | 1         | 0.86%   |
| 5.14.1  | 1         | 0.86%   |
| 5.11.1  | 1         | 0.86%   |
| 4.1.12  | 1         | 0.86%   |
| 3.8.13  | 1         | 0.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 42        | 36.21%  |
| 5.4     | 32        | 27.59%  |
| 4.18    | 18        | 15.52%  |
| 5.14    | 13        | 11.21%  |
| 4.14    | 5         | 4.31%   |
| 3.10    | 3         | 2.59%   |
| 5.11    | 1         | 0.86%   |
| 4.1     | 1         | 0.86%   |
| 3.8     | 1         | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 113       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 85        | 72.65%  |
| Unknown       | 16        | 13.68%  |
| GNOME Classic | 6         | 5.13%   |
| KDE5          | 4         | 3.42%   |
| XFCE          | 2         | 1.71%   |
| MATE          | 2         | 1.71%   |
| KDE4          | 2         | 1.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 62        | 53.45%  |
| X11     | 38        | 32.76%  |
| Unknown | 11        | 9.48%   |
| Tty     | 3         | 2.59%   |
| Web     | 2         | 1.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 57        | 49.14%  |
| Unknown | 55        | 47.41%  |
| SDDM    | 3         | 2.59%   |
| TDM     | 1         | 0.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 68        | 59.65%  |
| en_GB      | 12        | 10.53%  |
| ru_RU      | 5         | 4.39%   |
| de_DE      | 5         | 4.39%   |
| Unknown    | 5         | 4.39%   |
| pt_BR      | 4         | 3.51%   |
| pl_PL      | 3         | 2.63%   |
| it_IT      | 3         | 2.63%   |
| en_AU      | 3         | 2.63%   |
| en_IN      | 2         | 1.75%   |
| zh_HK      | 1         | 0.88%   |
| es_MX      | 1         | 0.88%   |
| en_US.UTF8 | 1         | 0.88%   |
| en_DE      | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 72        | 62.61%  |
| BIOS | 43        | 37.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 97        | 84.35%  |
| Ext4    | 14        | 12.17%  |
| Unknown | 2         | 1.74%   |
| Zfs     | 1         | 0.87%   |
| Btrfs   | 1         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 57        | 49.14%  |
| Unknown | 44        | 37.93%  |
| MBR     | 15        | 12.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 92.11%  |
| Yes       | 9         | 7.89%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 89.47%  |
| Yes       | 12        | 10.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 23.89%  |
| Dell                | 23        | 20.35%  |
| Hewlett-Packard     | 18        | 15.93%  |
| ASUSTek Computer    | 14        | 12.39%  |
| Gigabyte Technology | 6         | 5.31%   |
| Intel               | 4         | 3.54%   |
| Supermicro          | 3         | 2.65%   |
| ASRock              | 3         | 2.65%   |
| MSI                 | 2         | 1.77%   |
| Fujitsu             | 2         | 1.77%   |
| Toshiba             | 1         | 0.88%   |
| Standard            | 1         | 0.88%   |
| Panasonic           | 1         | 0.88%   |
| HPE                 | 1         | 0.88%   |
| Google              | 1         | 0.88%   |
| Foxconn             | 1         | 0.88%   |
| Dynabook            | 1         | 0.88%   |
| Cisco               | 1         | 0.88%   |
| Apple               | 1         | 0.88%   |
| Alienware           | 1         | 0.88%   |
| Unknown             | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Supermicro X9SCL-II/X9SCM-II              | 2         | 1.77%   |
| Lenovo ThinkPad T450 20BUS14900           | 2         | 1.77%   |
| Dell Latitude 7430                        | 2         | 1.77%   |
| Dell Latitude 7420                        | 2         | 1.77%   |
| ASUS X510UR                               | 2         | 1.77%   |
| Toshiba TECRA R950                        | 1         | 0.88%   |
| Supermicro X8DTU                          | 1         | 0.88%   |
| Standard BW Series                        | 1         | 0.88%   |
| Panasonic CF-53AAG54FM                    | 1         | 0.88%   |
| MSI P65 Creator 8RE                       | 1         | 0.88%   |
| MSI MS-7758                               | 1         | 0.88%   |
| Lenovo ThinkPad Yoga 370 20JJS0A44R       | 1         | 0.88%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 0.88%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 0.88%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 0.88%   |
| Lenovo ThinkPad W541 20EGS1PL00           | 1         | 0.88%   |
| Lenovo ThinkPad W520 42844DG              | 1         | 0.88%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 0.88%   |
| Lenovo ThinkPad T490 20N3S3XR00           | 1         | 0.88%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 0.88%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 0.88%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 0.88%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 0.88%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 0.88%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 0.88%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 0.88%   |
| Lenovo ThinkPad P16s Gen 1 21BTS0FR00     | 1         | 0.88%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 0.88%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 0.88%   |
| Lenovo ThinkBook 15-IIL 20SM              | 1         | 0.88%   |
| Lenovo Legion Y540-15IRH 81SX             | 1         | 0.88%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 0.88%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 0.88%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 0.88%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 0.88%   |
| Lenovo IdeaPad 3 14IIL05 81WD             | 1         | 0.88%   |
| Intel NUC6CAYH                            | 1         | 0.88%   |
| Intel NUC13ANHi5                          | 1         | 0.88%   |
| Intel NUC12WSHi7                          | 1         | 0.88%   |
| Intel NUC12WSHi5                          | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 20        | 17.7%   |
| Dell Latitude          | 9         | 7.96%   |
| Dell OptiPlex          | 6         | 5.31%   |
| Lenovo IdeaPad         | 4         | 3.54%   |
| HP EliteBook           | 4         | 3.54%   |
| HP ZBook               | 3         | 2.65%   |
| HP ProLiant            | 3         | 2.65%   |
| Dell Precision         | 3         | 2.65%   |
| Dell Inspiron          | 3         | 2.65%   |
| ASUS PRIME             | 3         | 2.65%   |
| Supermicro X9SCL-II    | 2         | 1.77%   |
| Lenovo Legion          | 2         | 1.77%   |
| ASUS X510UR            | 2         | 1.77%   |
| Toshiba TECRA          | 1         | 0.88%   |
| Supermicro X8DTU       | 1         | 0.88%   |
| Standard BW            | 1         | 0.88%   |
| Panasonic CF-53AAG54FM | 1         | 0.88%   |
| MSI P65                | 1         | 0.88%   |
| MSI MS-7758            | 1         | 0.88%   |
| Lenovo ThinkBook       | 1         | 0.88%   |
| Intel NUC6CAYH         | 1         | 0.88%   |
| Intel NUC13ANHi5       | 1         | 0.88%   |
| Intel NUC12WSHi7       | 1         | 0.88%   |
| Intel NUC12WSHi5       | 1         | 0.88%   |
| HPE ProLiant           | 1         | 0.88%   |
| HP Z820                | 1         | 0.88%   |
| HP Z420                | 1         | 0.88%   |
| HP ProBook             | 1         | 0.88%   |
| HP Pavilion            | 1         | 0.88%   |
| HP Notebook            | 1         | 0.88%   |
| HP Laptop              | 1         | 0.88%   |
| HP Compaq              | 1         | 0.88%   |
| HP 240                 | 1         | 0.88%   |
| Google Lick            | 1         | 0.88%   |
| Gigabyte Z490          | 1         | 0.88%   |
| Gigabyte X99-Designare | 1         | 0.88%   |
| Gigabyte X470          | 1         | 0.88%   |
| Gigabyte H81M-S2PV     | 1         | 0.88%   |
| Gigabyte B450M         | 1         | 0.88%   |
| Gigabyte B450          | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 12        | 10.62%  |
| 2019 | 11        | 9.73%   |
| 2022 | 10        | 8.85%   |
| 2018 | 10        | 8.85%   |
| 2012 | 10        | 8.85%   |
| 2016 | 8         | 7.08%   |
| 2013 | 7         | 6.19%   |
| 2021 | 6         | 5.31%   |
| 2017 | 6         | 5.31%   |
| 2015 | 6         | 5.31%   |
| 2014 | 6         | 5.31%   |
| 2011 | 6         | 5.31%   |
| 2023 | 5         | 4.42%   |
| 2024 | 4         | 3.54%   |
| 2010 | 4         | 3.54%   |
| 2009 | 1         | 0.88%   |
| 2008 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 64        | 56.64%  |
| Desktop     | 34        | 30.09%  |
| Convertible | 6         | 5.31%   |
| Mini pc     | 5         | 4.42%   |
| Server      | 4         | 3.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 96        | 84.21%  |
| Enabled  | 18        | 15.79%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 99.12%  |
| Yes  | 1         | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 35        | 30.7%   |
| 32.01-64.0      | 26        | 22.81%  |
| 4.01-8.0        | 15        | 13.16%  |
| 64.01-256.0     | 12        | 10.53%  |
| 3.01-4.0        | 9         | 7.89%   |
| 16.01-24.0      | 8         | 7.02%   |
| 24.01-32.0      | 7         | 6.14%   |
| More than 256.0 | 1         | 0.88%   |
| 1.01-2.0        | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 36        | 28.8%   |
| 2.01-3.0    | 29        | 23.2%   |
| 3.01-4.0    | 22        | 17.6%   |
| 8.01-16.0   | 14        | 11.2%   |
| 1.01-2.0    | 12        | 9.6%    |
| 0.51-1.0    | 4         | 3.2%    |
| 32.01-64.0  | 2         | 1.6%    |
| 24.01-32.0  | 2         | 1.6%    |
| 64.01-256.0 | 1         | 0.8%    |
| 16.01-24.0  | 1         | 0.8%    |
| 0.01-0.5    | 1         | 0.8%    |
| Unknown     | 1         | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 80        | 68.97%  |
| 2      | 19        | 16.38%  |
| 3      | 6         | 5.17%   |
| 4      | 5         | 4.31%   |
| 5      | 3         | 2.59%   |
| 25     | 1         | 0.86%   |
| 16     | 1         | 0.86%   |
| 6      | 1         | 0.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 79.82%  |
| Yes       | 23        | 20.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 86.73%  |
| No        | 15        | 13.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 76.99%  |
| No        | 26        | 23.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 61.74%  |
| No        | 44        | 38.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 32        | 28.07%  |
| Germany     | 12        | 10.53%  |
| UK          | 8         | 7.02%   |
| Brazil      | 7         | 6.14%   |
| Italy       | 6         | 5.26%   |
| Poland      | 5         | 4.39%   |
| Russia      | 4         | 3.51%   |
| Netherlands | 4         | 3.51%   |
| Australia   | 4         | 3.51%   |
| India       | 3         | 2.63%   |
| Finland     | 3         | 2.63%   |
| Vietnam     | 2         | 1.75%   |
| Spain       | 2         | 1.75%   |
| Romania     | 2         | 1.75%   |
| Moldova     | 2         | 1.75%   |
| Latvia      | 2         | 1.75%   |
| Yemen       | 1         | 0.88%   |
| Turkey      | 1         | 0.88%   |
| Sweden      | 1         | 0.88%   |
| Slovakia    | 1         | 0.88%   |
| Peru        | 1         | 0.88%   |
| Pakistan    | 1         | 0.88%   |
| Nigeria     | 1         | 0.88%   |
| Mexico      | 1         | 0.88%   |
| Malaysia    | 1         | 0.88%   |
| Kazakhstan  | 1         | 0.88%   |
| Hungary     | 1         | 0.88%   |
| Hong Kong   | 1         | 0.88%   |
| Chile       | 1         | 0.88%   |
| Bulgaria    | 1         | 0.88%   |
| Bolivia     | 1         | 0.88%   |
| Argentina   | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 5         | 4.07%   |
| San Diego          | 3         | 2.44%   |
| Helsinki           | 3         | 2.44%   |
| Warsaw             | 2         | 1.63%   |
| Tiraspol           | 2         | 1.63%   |
| Siegen             | 2         | 1.63%   |
| Seattle            | 2         | 1.63%   |
| Moscow             | 2         | 1.63%   |
| Milan              | 2         | 1.63%   |
| London             | 2         | 1.63%   |
| Hanoi              | 2         | 1.63%   |
| Colorado Springs   | 2         | 1.63%   |
| Bucharest          | 2         | 1.63%   |
| Berlin             | 2         | 1.63%   |
| Bengaluru          | 2         | 1.63%   |
| Amsterdam          | 2         | 1.63%   |
| Zavar              | 1         | 0.81%   |
| West Linn          | 1         | 0.81%   |
| Weaverville        | 1         | 0.81%   |
| Volendam           | 1         | 0.81%   |
| Veliky Novgorod    | 1         | 0.81%   |
| Valmiera           | 1         | 0.81%   |
| Utrecht            | 1         | 0.81%   |
| Turner             | 1         | 0.81%   |
| Sydney             | 1         | 0.81%   |
| Stuttgart          | 1         | 0.81%   |
| Stockholm          | 1         | 0.81%   |
| Sofia              | 1         | 0.81%   |
| Shrewsbury         | 1         | 0.81%   |
| Sao Caetano do Sul | 1         | 0.81%   |
| Santiago           | 1         | 0.81%   |
| Santa Cruz         | 1         | 0.81%   |
| Sanaa              | 1         | 0.81%   |
| San Jose           | 1         | 0.81%   |
| San Francisco      | 1         | 0.81%   |
| Rocklin            | 1         | 0.81%   |
| Riverside          | 1         | 0.81%   |
| Riga               | 1         | 0.81%   |
| Richfield          | 1         | 0.81%   |
| Redwood City       | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 34        | 49     | 22.22%  |
| Seagate                     | 17        | 79     | 11.11%  |
| SanDisk                     | 14        | 18     | 9.15%   |
| WDC                         | 13        | 17     | 8.5%    |
| Toshiba                     | 7         | 7      | 4.58%   |
| Kingston                    | 7         | 14     | 4.58%   |
| Unknown                     | 6         | 9      | 3.92%   |
| Intel                       | 5         | 5      | 3.27%   |
| SK hynix                    | 4         | 4      | 2.61%   |
| Micron Technology           | 4         | 7      | 2.61%   |
| Kingston Technology Company | 4         | 4      | 2.61%   |
| Hewlett-Packard             | 4         | 17     | 2.61%   |
| Crucial                     | 4         | 5      | 2.61%   |
| Phison Electronics          | 3         | 4      | 1.96%   |
| Micron/Crucial Technology   | 3         | 4      | 1.96%   |
| KIOXIA                      | 3         | 3      | 1.96%   |
| HGST                        | 3         | 6      | 1.96%   |
| KingFast                    | 2         | 2      | 1.31%   |
| XrayDisk                    | 1         | 2      | 0.65%   |
| Union Memory (Shenzhen)     | 1         | 2      | 0.65%   |
| Transcend                   | 1         | 1      | 0.65%   |
| Realtek Semiconductor       | 1         | 1      | 0.65%   |
| Plextor                     | 1         | 1      | 0.65%   |
| Phison                      | 1         | 1      | 0.65%   |
| Lite-On                     | 1         | 1      | 0.65%   |
| Lenovo                      | 1         | 1      | 0.65%   |
| KingSpec                    | 1         | 1      | 0.65%   |
| JMicron Technology          | 1         | 1      | 0.65%   |
| HPE                         | 1         | 1      | 0.65%   |
| Hitachi                     | 1         | 1      | 0.65%   |
| GOODRAM                     | 1         | 1      | 0.65%   |
| Fujitsu                     | 1         | 1      | 0.65%   |
| Apple                       | 1         | 1      | 0.65%   |
| Apacer                      | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4         | 2.35%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 2.35%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 1.18%   |
| SanDisk SSD PLUS 1000GB                             | 2         | 1.18%   |
| Samsung SSD PM830 2.5 7mm 256GB                     | 2         | 1.18%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 1.18%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 1.18%   |
| Samsung MZVLB512HAJQ-000L7 512GB                    | 2         | 1.18%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD                | 2         | 1.18%   |
| Phison E12 NVMe Controller 480GB                    | 2         | 1.18%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB               | 2         | 1.18%   |
| Kingston Company SNV2S2000G 2TB                     | 2         | 1.18%   |
| Kingston Company SNV2S1000G 1TB                     | 2         | 1.18%   |
| Intel SSD 660P Series 1024GB                        | 2         | 1.18%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 1.18%   |
| XrayDisk 480GB SSD                                  | 1         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.59%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1         | 0.59%   |
| WDC WDS200T2G0A-00JH30 2TB SSD                      | 1         | 0.59%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                    | 1         | 0.59%   |
| WDC WD40PURX-64GVNY0 4TB                            | 1         | 0.59%   |
| WDC WD40PURX-64GVNY0 1 4TB                          | 1         | 0.59%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1         | 0.59%   |
| WDC WD3200BEKT-08PVMT1 320GB                        | 1         | 0.59%   |
| WDC WD30EFRX-68AX9N0 3TB                            | 1         | 0.59%   |
| WDC WD2500AAKX-08U6AA0 250GB                        | 1         | 0.59%   |
| WDC WD1600YS-23SHB0 160GB                           | 1         | 0.59%   |
| WDC WD10SPZX-60Z10T1 1TB                            | 1         | 0.59%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 0.59%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 0.59%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1         | 0.59%   |
| Unknown MMC64G  64GB                                | 1         | 0.59%   |
| Unknown MMC Card  256GB                             | 1         | 0.59%   |
| Unknown MMC Card  248GB                             | 1         | 0.59%   |
| Unknown MMC Card  1TB                               | 1         | 0.59%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB        | 1         | 0.59%   |
| Transcend TS2TMTE250H 2TB                           | 1         | 0.59%   |
| Toshiba THNSNJ512GCSU 512GB SSD                     | 1         | 0.59%   |
| Toshiba NVMe SSD Drive 512GB                        | 1         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 79     | 37.78%  |
| WDC                 | 10        | 12     | 22.22%  |
| Toshiba             | 5         | 5      | 11.11%  |
| HGST                | 3         | 6      | 6.67%   |
| Unknown             | 2         | 4      | 4.44%   |
| Samsung Electronics | 2         | 2      | 4.44%   |
| Hewlett-Packard     | 2         | 15     | 4.44%   |
| JMicron Technology  | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 1      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 26     | 38.78%  |
| SanDisk             | 7         | 10     | 14.29%  |
| Kingston            | 6         | 7      | 12.24%  |
| WDC                 | 4         | 5      | 8.16%   |
| Crucial             | 3         | 4      | 6.12%   |
| Hewlett-Packard     | 2         | 2      | 4.08%   |
| XrayDisk            | 1         | 2      | 2.04%   |
| Toshiba             | 1         | 1      | 2.04%   |
| Plextor             | 1         | 1      | 2.04%   |
| KingSpec            | 1         | 1      | 2.04%   |
| Intel               | 1         | 1      | 2.04%   |
| HPE                 | 1         | 1      | 2.04%   |
| GOODRAM             | 1         | 1      | 2.04%   |
| Apacer              | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 55        | 75     | 38.19%  |
| SSD     | 46        | 63     | 31.94%  |
| HDD     | 37        | 127    | 25.69%  |
| MMC     | 4         | 5      | 2.78%   |
| Unknown | 2         | 2      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 182    | 50.38%  |
| NVMe | 55        | 75     | 41.98%  |
| SAS  | 6         | 10     | 4.58%   |
| MMC  | 4         | 5      | 3.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 71     | 45.88%  |
| 0.51-1.0   | 27        | 60     | 31.76%  |
| 1.01-2.0   | 9         | 47     | 10.59%  |
| 4.01-10.0  | 4         | 5      | 4.71%   |
| 2.01-3.0   | 3         | 3      | 3.53%   |
| 3.01-4.0   | 2         | 3      | 2.35%   |
| 10.01-20.0 | 1         | 1      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 29        | 25.22%  |
| 101-250        | 23        | 20%     |
| 501-1000       | 20        | 17.39%  |
| 1-20           | 10        | 8.7%    |
| 1001-2000      | 9         | 7.83%   |
| Unknown        | 8         | 6.96%   |
| 51-100         | 6         | 5.22%   |
| More than 3000 | 5         | 4.35%   |
| 2001-3000      | 3         | 2.61%   |
| 21-50          | 2         | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 38        | 31.93%  |
| 21-50          | 28        | 23.53%  |
| 51-100         | 16        | 13.45%  |
| 101-250        | 13        | 10.92%  |
| 251-500        | 8         | 6.72%   |
| Unknown        | 8         | 6.72%   |
| More than 3000 | 5         | 4.2%    |
| 501-1000       | 2         | 1.68%   |
| 1001-2000      | 1         | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 42.86%  |
| Samsung Electronics | 2         | 3      | 28.57%  |
| WDC                 | 1         | 2      | 14.29%  |
| Hewlett-Packard     | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 60%     |
| WDC                 | 1         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 64        | 170    | 52.03%  |
| Detected | 52        | 93     | 42.28%  |
| Malfunc  | 7         | 9      | 5.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 73        | 49.66%  |
| Samsung Electronics          | 17        | 11.56%  |
| AMD                          | 9         | 6.12%   |
| Sandisk                      | 7         | 4.76%   |
| Broadcom / LSI               | 6         | 4.08%   |
| Kingston Technology Company  | 5         | 3.4%    |
| SK hynix                     | 4         | 2.72%   |
| Phison Electronics           | 4         | 2.72%   |
| Micron/Crucial Technology    | 4         | 2.72%   |
| Micron Technology            | 4         | 2.72%   |
| KIOXIA                       | 3         | 2.04%   |
| Adaptec                      | 2         | 1.36%   |
| VIA Technologies             | 1         | 0.68%   |
| Union Memory (Shenzhen)      | 1         | 0.68%   |
| Transcend                    | 1         | 0.68%   |
| Toshiba America Info Systems | 1         | 0.68%   |
| Realtek Semiconductor        | 1         | 0.68%   |
| LSI Logic / Symbios Logic    | 1         | 0.68%   |
| Lite-On Technology           | 1         | 0.68%   |
| Lenovo                       | 1         | 0.68%   |
| Hewlett-Packard              | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 6.06%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 4.24%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 3.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.03%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4         | 2.42%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 2.42%   |
| Phison E12 NVMe Controller                                                              | 3         | 1.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3         | 1.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.82%   |
| Intel SATA Controller [RAID Mode]                                                       | 3         | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.82%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                                   | 2         | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2         | 1.21%   |
| Intel SSD 660P Series                                                                   | 2         | 1.21%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.21%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 1.21%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 1.21%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.21%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2         | 1.21%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 2         | 1.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.21%   |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                            | 2         | 1.21%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.61%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                         | 1         | 0.61%   |
| Transcend NVMe PCIe SSD 250H                                                            | 1         | 0.61%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 44%     |
| NVMe | 55        | 36.67%  |
| RAID | 13        | 8.67%   |
| IDE  | 9         | 6%      |
| SAS  | 4         | 2.67%   |
| SCSI | 3         | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 103       | 91.15%  |
| AMD    | 10        | 8.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 2.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 2.65%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 2.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 2.65%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz     | 2         | 1.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 1.77%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2         | 1.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 1.77%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 2         | 1.77%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 1.77%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 1.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.77%   |
| Intel 12th Gen Core i7-1270P            | 2         | 1.77%   |
| Intel 12th Gen Core i7-1260P            | 2         | 1.77%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 2         | 1.77%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 2         | 1.77%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 1         | 0.88%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 1         | 0.88%   |
| Intel Xeon CPU X3450 @ 2.67GHz          | 1         | 0.88%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 0.88%   |
| Intel Xeon CPU E5649 @ 2.53GHz          | 1         | 0.88%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz     | 1         | 0.88%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1         | 0.88%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.88%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 0.88%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz     | 1         | 0.88%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 0.88%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 0.88%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 0.88%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 1         | 0.88%   |
| Intel Pentium CPU G2020 @ 2.90GHz       | 1         | 0.88%   |
| Intel Core Ultra 7 165H                 | 1         | 0.88%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 0.88%   |
| Intel Core i9-14900HX                   | 1         | 0.88%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 0.88%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 33        | 29.2%   |
| Other             | 22        | 19.47%  |
| Intel Core i5     | 20        | 17.7%   |
| Intel Xeon        | 12        | 10.62%  |
| Intel Core i3     | 5         | 4.42%   |
| Intel Celeron     | 4         | 3.54%   |
| Intel Pentium     | 3         | 2.65%   |
| Intel Core i9     | 3         | 2.65%   |
| AMD Ryzen 5       | 3         | 2.65%   |
| AMD Ryzen 7       | 2         | 1.77%   |
| Intel Xeon Silver | 1         | 0.88%   |
| Intel Core 2 Duo  | 1         | 0.88%   |
| Intel Core        | 1         | 0.88%   |
| AMD Ryzen 7 PRO   | 1         | 0.88%   |
| AMD FX            | 1         | 0.88%   |
| AMD A8            | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 41        | 36.28%  |
| 2      | 31        | 27.43%  |
| 12     | 10        | 8.85%   |
| 6      | 10        | 8.85%   |
| 8      | 6         | 5.31%   |
| 16     | 5         | 4.42%   |
| 10     | 5         | 4.42%   |
| 14     | 2         | 1.77%   |
| 24     | 1         | 0.88%   |
| 20     | 1         | 0.88%   |
| 1      | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 95.58%  |
| 2      | 5         | 4.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 92        | 81.42%  |
| 1      | 21        | 18.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 112       | 98.25%  |
| Unknown        | 2         | 1.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 17.39%  |
| 0x806ec    | 7         | 6.09%   |
| 0x306c3    | 6         | 5.22%   |
| 0x306a9    | 6         | 5.22%   |
| 0x206a7    | 6         | 5.22%   |
| 0x806ea    | 5         | 4.35%   |
| 0x906a3    | 4         | 3.48%   |
| 0x806c1    | 4         | 3.48%   |
| 0x906ea    | 3         | 2.61%   |
| 0x806e9    | 3         | 2.61%   |
| 0x506e3    | 3         | 2.61%   |
| 0x40651    | 3         | 2.61%   |
| 0x306d4    | 3         | 2.61%   |
| 0xb06a2    | 2         | 1.74%   |
| 0xa0655    | 2         | 1.74%   |
| 0xa0652    | 2         | 1.74%   |
| 0x906ed    | 2         | 1.74%   |
| 0x90672    | 2         | 1.74%   |
| 0x706a8    | 2         | 1.74%   |
| 0x406f1    | 2         | 1.74%   |
| 0x406e3    | 2         | 1.74%   |
| 0x406c4    | 2         | 1.74%   |
| 0x306e4    | 2         | 1.74%   |
| 0x206c2    | 2         | 1.74%   |
| 0x106e5    | 2         | 1.74%   |
| 0xb06f2    | 1         | 0.87%   |
| 0xa0653    | 1         | 0.87%   |
| 0x906e9    | 1         | 0.87%   |
| 0x806d1    | 1         | 0.87%   |
| 0x706e5    | 1         | 0.87%   |
| 0x506c9    | 1         | 0.87%   |
| 0x50654    | 1         | 0.87%   |
| 0x20655    | 1         | 0.87%   |
| 0x10676    | 1         | 0.87%   |
| 0x0b204011 | 1         | 0.87%   |
| 0x0a50000c | 1         | 0.87%   |
| 0x08701030 | 1         | 0.87%   |
| 0x08701013 | 1         | 0.87%   |
| 0x08608103 | 1         | 0.87%   |
| 0x0810100b | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 24        | 21.24%  |
| Haswell           | 11        | 9.73%   |
| Alderlake Hybrid  | 10        | 8.85%   |
| IvyBridge         | 9         | 7.96%   |
| SandyBridge       | 7         | 6.19%   |
| Skylake           | 6         | 5.31%   |
| CometLake         | 6         | 5.31%   |
| Broadwell         | 6         | 5.31%   |
| Unknown           | 6         | 5.31%   |
| TigerLake         | 5         | 4.42%   |
| Westmere          | 3         | 2.65%   |
| Icelake           | 3         | 2.65%   |
| Zen 2             | 2         | 1.77%   |
| Silvermont        | 2         | 1.77%   |
| Nehalem           | 2         | 1.77%   |
| Goldmont plus     | 2         | 1.77%   |
| Zen+              | 1         | 0.88%   |
| Zen 3             | 1         | 0.88%   |
| Zen               | 1         | 0.88%   |
| Puma              | 1         | 0.88%   |
| Piledriver        | 1         | 0.88%   |
| Penryn            | 1         | 0.88%   |
| Meteorlake Hybrid | 1         | 0.88%   |
| Goldmont          | 1         | 0.88%   |
| Excavator         | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 78        | 56.93%  |
| Nvidia                     | 36        | 26.28%  |
| AMD                        | 14        | 10.22%  |
| Matrox Electronics Systems | 8         | 5.84%   |
| ASPEED Technology          | 1         | 0.73%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 6         | 4.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.65%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 3.65%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 5         | 3.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 2.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.19%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 2.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 2.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.19%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.46%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.46%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.46%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 2         | 1.46%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.46%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.46%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 0.73%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.73%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.73%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.73%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.73%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.73%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.73%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.73%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 0.73%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1         | 0.73%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 0.73%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 47.37%  |
| Intel + Nvidia | 18        | 15.79%  |
| 1 x Nvidia     | 16        | 14.04%  |
| 1 x Matrox     | 8         | 7.02%   |
| 1 x AMD        | 8         | 7.02%   |
| Other          | 3         | 2.63%   |
| Intel + AMD    | 3         | 2.63%   |
| AMD + Nvidia   | 3         | 2.63%   |
| 1 x ASPEED     | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 93        | 80.87%  |
| Unknown     | 14        | 12.17%  |
| Proprietary | 8         | 6.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 66.96%  |
| 3.01-4.0   | 14        | 12.17%  |
| 1.01-2.0   | 13        | 11.3%   |
| 0.51-1.0   | 4         | 3.48%   |
| 0.01-0.5   | 3         | 2.61%   |
| 5.01-6.0   | 2         | 1.74%   |
| 7.01-8.0   | 1         | 0.87%   |
| 8.01-16.0  | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 19        | 14.5%   |
| AU Optronics         | 15        | 11.45%  |
| Samsung Electronics  | 14        | 10.69%  |
| LG Display           | 14        | 10.69%  |
| Dell                 | 14        | 10.69%  |
| BOE                  | 10        | 7.63%   |
| BenQ                 | 6         | 4.58%   |
| Lenovo               | 5         | 3.82%   |
| ViewSonic            | 3         | 2.29%   |
| InfoVision           | 3         | 2.29%   |
| Hewlett-Packard      | 3         | 2.29%   |
| Acer                 | 3         | 2.29%   |
| Sharp                | 2         | 1.53%   |
| Goldstar             | 2         | 1.53%   |
| ASUSTek Computer     | 2         | 1.53%   |
| AOC                  | 2         | 1.53%   |
| Vizio                | 1         | 0.76%   |
| Viotek               | 1         | 0.76%   |
| Sony                 | 1         | 0.76%   |
| Sceptre Tech         | 1         | 0.76%   |
| SAC                  | 1         | 0.76%   |
| Panasonic            | 1         | 0.76%   |
| Packard Bell         | 1         | 0.76%   |
| Gigabyte Technology  | 1         | 0.76%   |
| GameMax              | 1         | 0.76%   |
| Fujitsu Siemens      | 1         | 0.76%   |
| Element              | 1         | 0.76%   |
| Eizo                 | 1         | 0.76%   |
| BOE Technology Group | 1         | 0.76%   |
| Ancor Communications | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 2.19%   |
| Samsung Electronics C34H89x SAM0E26 3440x1440 797x333mm 34.0-inch     | 2         | 1.46%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.46%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 1.46%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 1.46%   |
| Dell P2722H DEL4240 1920x1080 598x336mm 27.0-inch                     | 2         | 1.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 1.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.46%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 1.46%   |
| BOE LCD Monitor BOE0B13 1920x1200 302x188mm 14.0-inch                 | 2         | 1.46%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 2         | 1.46%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 1.46%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                     | 2         | 1.46%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 2         | 1.46%   |
| Vizio V435-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1         | 0.73%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                  | 1         | 0.73%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.73%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 0.73%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 0.73%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 0.73%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.73%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.73%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.73%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 0.73%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch     | 1         | 0.73%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch     | 1         | 0.73%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 0.73%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch     | 1         | 0.73%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch     | 1         | 0.73%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.73%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.73%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 0.73%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 0.73%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 0.73%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 0.73%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 59        | 51.75%  |
| 1366x768 (WXGA)    | 11        | 9.65%   |
| 3840x2160 (4K)     | 10        | 8.77%   |
| 1920x1200 (WUXGA)  | 6         | 5.26%   |
| 1600x900 (HD+)     | 5         | 4.39%   |
| 2560x1440 (QHD)    | 4         | 3.51%   |
| 1280x1024 (SXGA)   | 4         | 3.51%   |
| 1680x1050 (WSXGA+) | 3         | 2.63%   |
| 3440x1440          | 2         | 1.75%   |
| 3840x2400          | 1         | 0.88%   |
| 3840x1200          | 1         | 0.88%   |
| 3840x1080          | 1         | 0.88%   |
| 2880x1800          | 1         | 0.88%   |
| 2560x1600          | 1         | 0.88%   |
| 2560x1080          | 1         | 0.88%   |
| 1920x540           | 1         | 0.88%   |
| 1360x768           | 1         | 0.88%   |
| 1280x800 (WXGA)    | 1         | 0.88%   |
| Unknown            | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 19.55%  |
| 14      | 19        | 14.29%  |
| 13      | 15        | 11.28%  |
| 24      | 13        | 9.77%   |
| 27      | 12        | 9.02%   |
| 23      | 7         | 5.26%   |
| 31      | 6         | 4.51%   |
| 21      | 6         | 4.51%   |
| Unknown | 4         | 3.01%   |
| 17      | 3         | 2.26%   |
| 38      | 2         | 1.5%    |
| 34      | 2         | 1.5%    |
| 22      | 2         | 1.5%    |
| 19      | 2         | 1.5%    |
| 18      | 2         | 1.5%    |
| 16      | 2         | 1.5%    |
| 84      | 1         | 0.75%   |
| 72      | 1         | 0.75%   |
| 69      | 1         | 0.75%   |
| 48      | 1         | 0.75%   |
| 32      | 1         | 0.75%   |
| 29      | 1         | 0.75%   |
| 25      | 1         | 0.75%   |
| 20      | 1         | 0.75%   |
| 12      | 1         | 0.75%   |
| 11      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 44.96%  |
| 501-600     | 30        | 23.26%  |
| 401-500     | 9         | 6.98%   |
| 601-700     | 8         | 6.2%    |
| 201-300     | 7         | 5.43%   |
| 351-400     | 4         | 3.1%    |
| Unknown     | 4         | 3.1%    |
| 701-800     | 3         | 2.33%   |
| 1501-2000   | 3         | 2.33%   |
| 801-900     | 2         | 1.55%   |
| 1001-1500   | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 82        | 77.36%  |
| 16/10   | 13        | 12.26%  |
| 5/4     | 4         | 3.77%   |
| 21/9    | 3         | 2.83%   |
| 32/9    | 2         | 1.89%   |
| Unknown | 2         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 29        | 22.31%  |
| 101-110        | 26        | 20%     |
| 201-250        | 23        | 17.69%  |
| 301-350        | 13        | 10%     |
| 351-500        | 9         | 6.92%   |
| 71-80          | 5         | 3.85%   |
| 151-200        | 4         | 3.08%   |
| Unknown        | 4         | 3.08%   |
| More than 1000 | 3         | 2.31%   |
| 141-150        | 3         | 2.31%   |
| 501-1000       | 3         | 2.31%   |
| 251-300        | 2         | 1.54%   |
| 121-130        | 2         | 1.54%   |
| 111-120        | 2         | 1.54%   |
| 61-70          | 1         | 0.77%   |
| 51-60          | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 36.8%   |
| 51-100        | 40        | 32%     |
| 101-120       | 22        | 17.6%   |
| 161-240       | 9         | 7.2%    |
| Unknown       | 4         | 3.2%    |
| More than 240 | 3         | 2.4%    |
| 1-50          | 1         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 64        | 55.17%  |
| 2     | 26        | 22.41%  |
| 0     | 17        | 14.66%  |
| 3     | 8         | 6.9%    |
| 4     | 1         | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 87        | 51.79%  |
| Realtek Semiconductor             | 42        | 25%     |
| Broadcom                          | 9         | 5.36%   |
| Qualcomm Atheros                  | 7         | 4.17%   |
| Lenovo                            | 4         | 2.38%   |
| Broadcom Limited                  | 3         | 1.79%   |
| Samsung Electronics               | 2         | 1.19%   |
| ASIX Electronics                  | 2         | 1.19%   |
| Sierra Wireless                   | 1         | 0.6%    |
| Ralink Technology                 | 1         | 0.6%    |
| QLogic                            | 1         | 0.6%    |
| NetGear                           | 1         | 0.6%    |
| Mellanox Technologies             | 1         | 0.6%    |
| MediaTek                          | 1         | 0.6%    |
| Huawei Technologies               | 1         | 0.6%    |
| Fibocom                           | 1         | 0.6%    |
| Ericsson Business Mobile Networks | 1         | 0.6%    |
| Edimax Technology                 | 1         | 0.6%    |
| DisplayLink                       | 1         | 0.6%    |
| ASUSTek Computer                  | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 18        | 8.29%   |
| Intel Wireless 8265 / 8275                                             | 11        | 5.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 4.15%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 2.76%   |
| Intel 82574L Gigabit Network Connection                                | 6         | 2.76%   |
| Intel Wireless 7260                                                    | 5         | 2.3%    |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 1.84%   |
| Intel Wireless 8260                                                    | 4         | 1.84%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.84%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.84%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 1.38%   |
| Intel Wireless 7265                                                    | 3         | 1.38%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 1.38%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.38%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.38%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.38%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.38%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 0.92%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 2         | 0.92%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.92%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 0.92%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.92%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 72.34%  |
| Realtek Semiconductor | 8         | 8.51%   |
| Qualcomm Atheros      | 7         | 7.45%   |
| Broadcom Limited      | 2         | 2.13%   |
| Broadcom              | 2         | 2.13%   |
| Sierra Wireless       | 1         | 1.06%   |
| Ralink Technology     | 1         | 1.06%   |
| NetGear               | 1         | 1.06%   |
| MediaTek              | 1         | 1.06%   |
| Fibocom               | 1         | 1.06%   |
| Edimax Technology     | 1         | 1.06%   |
| ASUSTek Computer      | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 11        | 11.7%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 6         | 6.38%   |
| Intel Wireless 7260                                                  | 5         | 5.32%   |
| Intel Wireless 8260                                                  | 4         | 4.26%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 4.26%   |
| Intel Wireless 7265                                                  | 3         | 3.19%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 3         | 3.19%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 3.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 3.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 2.13%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2      | 2         | 2.13%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 2.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 2.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 2.13%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 2.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 2.13%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 2.13%   |
| Sierra Wireless EM7455                                               | 1         | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.06%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1         | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1         | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 1.06%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                      | 1         | 1.06%   |
| MediaTek Network controller                                          | 1         | 1.06%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.06%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1         | 1.06%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 1         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 1         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 50%     |
| Realtek Semiconductor | 38        | 32.76%  |
| Broadcom              | 7         | 6.03%   |
| Lenovo                | 4         | 3.45%   |
| Samsung Electronics   | 2         | 1.72%   |
| ASIX Electronics      | 2         | 1.72%   |
| QLogic                | 1         | 0.86%   |
| Mellanox Technologies | 1         | 0.86%   |
| Huawei Technologies   | 1         | 0.86%   |
| DisplayLink           | 1         | 0.86%   |
| Broadcom Limited      | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 18        | 14.75%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 8.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 7.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 4.92%   |
| Intel 82574L Gigabit Network Connection                                | 6         | 4.92%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 3.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 3.28%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 3.28%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 2.46%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.46%   |
| Intel Ethernet Controller I225-V                                       | 3         | 2.46%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 2.46%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2.46%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.64%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 1.64%   |
| Intel Ethernet Controller I226-V                                       | 2         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.64%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.64%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 1.64%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.64%   |
| Realtek Realtek Ethernet controller                                    | 1         | 0.82%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1         | 0.82%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1         | 0.82%   |
| Lenovo ThinkPad TBT3 LAN                                               | 1         | 0.82%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.82%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.82%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 0.82%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.82%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1         | 0.82%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.82%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.82%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 0.82%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                  | 1         | 0.82%   |
| Intel 82578DM Gigabit Network Connection                               | 1         | 0.82%   |
| Intel 82576 Gigabit Network Connection                                 | 1         | 0.82%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1         | 0.82%   |
| Intel 82571EB Gigabit Ethernet Controller                              | 1         | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 98        | 52.69%  |
| WiFi     | 87        | 46.77%  |
| Modem    | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 63        | 53.85%  |
| WiFi     | 54        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 66        | 58.41%  |
| 1     | 37        | 32.74%  |
| 6     | 3         | 2.65%   |
| 4     | 3         | 2.65%   |
| 3     | 3         | 2.65%   |
| 7     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 90        | 76.27%  |
| Yes  | 28        | 23.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 70.83%  |
| Qualcomm Atheros Communications | 6         | 8.33%   |
| Realtek Semiconductor           | 4         | 5.56%   |
| Broadcom                        | 3         | 4.17%   |
| Apple                           | 3         | 4.17%   |
| ASUSTek Computer                | 2         | 2.78%   |
| IMC Networks                    | 1         | 1.39%   |
| Foxconn / Hon Hai               | 1         | 1.39%   |
| Alps Electric                   | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 17        | 23.61%  |
| Intel AX201 Bluetooth                          | 10        | 13.89%  |
| Intel AX211 Bluetooth                          | 9         | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 8         | 11.11%  |
| Apple Bluetooth Host Controller                | 3         | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 2.78%   |
| Realtek Bluetooth Radio                        | 2         | 2.78%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 2.78%   |
| Qualcomm Atheros AR9462 Bluetooth              | 2         | 2.78%   |
| Intel Bluetooth Device                         | 2         | 2.78%   |
| Intel AX210 Bluetooth                          | 2         | 2.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 2         | 2.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 1.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 1.39%   |
| IMC Networks Bluetooth Radio                   | 1         | 1.39%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.39%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 1.39%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 1.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.39%   |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 92        | 58.97%  |
| Nvidia                 | 25        | 16.03%  |
| AMD                    | 15        | 9.62%   |
| Lenovo                 | 6         | 3.85%   |
| GN Netcom              | 5         | 3.21%   |
| Plantronics            | 2         | 1.28%   |
| Creative Technology    | 2         | 1.28%   |
| C-Media Electronics    | 2         | 1.28%   |
| Unknown                | 1         | 0.64%   |
| TEAC                   | 1         | 0.64%   |
| RME                    | 1         | 0.64%   |
| Realtek Semiconductor  | 1         | 0.64%   |
| M-Audio                | 1         | 0.64%   |
| JMTek                  | 1         | 0.64%   |
| AKAI Professional M.I. | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 7.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.27%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 4         | 2.27%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 3         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.7%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.7%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.7%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 1.7%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.7%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.14%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.14%   |
| Nvidia GF110 High Definition Audio Controller                                                     | 2         | 1.14%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 1.14%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 2         | 1.14%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 2         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.14%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.14%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 2         | 1.14%   |
| Creative Technology Sound BlasterX G1                                                             | 2         | 1.14%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.14%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.14%   |
| Unknown Definitive Sym1                                                                           | 1         | 0.57%   |
| TEAC US-2x2                                                                                       | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Micron Technology                       | 15        | 18.99%  |
| Samsung Electronics                     | 14        | 17.72%  |
| SK hynix                                | 12        | 15.19%  |
| Kingston                                | 7         | 8.86%   |
| Unknown                                 | 6         | 7.59%   |
| Unknown                                 | 5         | 6.33%   |
| Crucial                                 | 4         | 5.06%   |
| Corsair                                 | 3         | 3.8%    |
| Avant                                   | 2         | 2.53%   |
| Unknown (0x0C26)                        | 1         | 1.27%   |
| Unigen                                  | 1         | 1.27%   |
| Smart                                   | 1         | 1.27%   |
| Silicon Power Computer & Communications | 1         | 1.27%   |
| Patriot                                 | 1         | 1.27%   |
| Nanya Technology                        | 1         | 1.27%   |
| HPE                                     | 1         | 1.27%   |
| Hewlett-Packard                         | 1         | 1.27%   |
| AVEXIR                                  | 1         | 1.27%   |
| A-DATA Technology                       | 1         | 1.27%   |
| 4ea5                                    | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 6         | 6.9%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 3         | 3.45%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 2         | 2.3%    |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.15%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                     | 1         | 1.15%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 1         | 1.15%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                      | 1         | 1.15%   |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                  | 1         | 1.15%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                     | 1         | 1.15%   |
| Unknown (0x0C26) RAM TIMETEC-UD4-3200 32GB DIMM DDR4 3200MT/s | 1         | 1.15%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 1.15%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s         | 1         | 1.15%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                 | 1         | 1.15%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 1.15%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 1.15%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s            | 1         | 1.15%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s  | 1         | 1.15%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s  | 1         | 1.15%   |
| SK hynix RAM HMA84GR7AFR4N-UH 32GB DIMM DDR4 2400MT/s         | 1         | 1.15%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.15%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 1         | 1.15%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.15%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.15%   |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s           | 1         | 1.15%   |
| Silicon Power & RAM Module 16GB SODIMM DDR4 2667MT/s          | 1         | 1.15%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                   | 1         | 1.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.15%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 1         | 1.15%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.15%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.15%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 1.15%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.15%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s          | 1         | 1.15%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s          | 1         | 1.15%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s          | 1         | 1.15%   |
| Samsung RAM K3KL9L90CM-MGCT 8GB SODIMM LPDDR5 7500MT/s        | 1         | 1.15%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s               | 1         | 1.15%   |
| Nanya RAM NT8GA64D88AX3S-HR 8GB SODIMM DDR4 2667MT/s          | 1         | 1.15%   |
| Micron RAM MTC16C2085S1SC56BD1 32GB SODIMM DDR5 5600MT/s      | 1         | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 58.33%  |
| DDR3   | 20        | 27.78%  |
| LPDDR5 | 5         | 6.94%   |
| LPDDR4 | 2         | 2.78%   |
| DDR5   | 2         | 2.78%   |
| DRAM   | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 54.93%  |
| DIMM         | 24        | 33.8%   |
| Row Of Chips | 7         | 9.86%   |
| Unknown      | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 30        | 38.96%  |
| 16384 | 19        | 24.68%  |
| 4096  | 16        | 20.78%  |
| 32768 | 8         | 10.39%  |
| 2048  | 3         | 3.9%    |
| 1024  | 1         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 16        | 21.33%  |
| 3200    | 12        | 16%     |
| 1600    | 10        | 13.33%  |
| 1333    | 9         | 12%     |
| 2400    | 7         | 9.33%   |
| 2666    | 4         | 5.33%   |
| 6400    | 3         | 4%      |
| 3466    | 2         | 2.67%   |
| 7500    | 1         | 1.33%   |
| 7467    | 1         | 1.33%   |
| 5600    | 1         | 1.33%   |
| 4800    | 1         | 1.33%   |
| 4267    | 1         | 1.33%   |
| 2934    | 1         | 1.33%   |
| 2600    | 1         | 1.33%   |
| 2448    | 1         | 1.33%   |
| 2133    | 1         | 1.33%   |
| 1866    | 1         | 1.33%   |
| 800     | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 16        | 22.54%  |
| Microdia                               | 8         | 11.27%  |
| IMC Networks                           | 8         | 11.27%  |
| Realtek Semiconductor                  | 7         | 9.86%   |
| Logitech                               | 7         | 9.86%   |
| Suyin                                  | 3         | 4.23%   |
| Quanta                                 | 3         | 4.23%   |
| Luxvisions Innotech Limited            | 3         | 4.23%   |
| Lite-On Technology                     | 3         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.23%   |
| Bison Electronics                      | 3         | 4.23%   |
| Apple                                  | 2         | 2.82%   |
| Shinetech                              | 1         | 1.41%   |
| Samsung Electronics                    | 1         | 1.41%   |
| OPPO Electronics                       | 1         | 1.41%   |
| Microsoft                              | 1         | 1.41%   |
| Generalplus Technology                 | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 7         | 9.72%   |
| IMC Networks Integrated Camera                    | 4         | 5.56%   |
| Realtek Integrated_Webcam_FHD                     | 3         | 4.17%   |
| Microdia Webcam Vitade AF                         | 3         | 4.17%   |
| Microdia Integrated_Webcam_HD                     | 3         | 4.17%   |
| Realtek Integrated_Webcam_HD                      | 2         | 2.78%   |
| Quanta HP HD Camera                               | 2         | 2.78%   |
| Logitech BRIO Ultra HD Webcam                     | 2         | 2.78%   |
| Lite-On Integrated Camera                         | 2         | 2.78%   |
| IMC Networks VGA UVC WebCam                       | 2         | 2.78%   |
| Chicony Integrated Camera (1280x720@30)           | 2         | 2.78%   |
| Bison SunplusIT Integrated Camera                 | 2         | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 2         | 2.78%   |
| Suyin Integrated_Webcam_HD                        | 1         | 1.39%   |
| Suyin HP Truevision HD                            | 1         | 1.39%   |
| Suyin Asus Integrated Webcam                      | 1         | 1.39%   |
| Shinetech ASUS FHD webcam                         | 1         | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1         | 1.39%   |
| Realtek USB Camera                                | 1         | 1.39%   |
| Realtek EasyCamera                                | 1         | 1.39%   |
| Quanta HP Webcam                                  | 1         | 1.39%   |
| OPPO realme Phone                                 | 1         | 1.39%   |
| Microsoft LifeCam HD-3000                         | 1         | 1.39%   |
| Microdia Integrated_Webcam_FHD                    | 1         | 1.39%   |
| Microdia Dell Laptop Integrated Webcam HD         | 1         | 1.39%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.39%   |
| Luxvisions Innotech Limited HP 5MP Camera         | 1         | 1.39%   |
| Luxvisions Innotech Limited EasyCamera 1M         | 1         | 1.39%   |
| Logitech Webcam C920-C                            | 1         | 1.39%   |
| Logitech Webcam C270                              | 1         | 1.39%   |
| Logitech Logitech Webcam C925e                    | 1         | 1.39%   |
| Logitech HD Webcam C615                           | 1         | 1.39%   |
| Logitech HD Webcam C510                           | 1         | 1.39%   |
| Lite-On HP HD Camera                              | 1         | 1.39%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 1         | 1.39%   |
| IMC Networks SunplusIT Integrated Camera          | 1         | 1.39%   |
| Generalplus GENERAL WEBCAM                        | 1         | 1.39%   |
| Chicony USB2.0 VGA UVC WebCam                     | 1         | 1.39%   |
| Chicony TOSHIBA Web Camera - HD                   | 1         | 1.39%   |
| Chicony TOSHIBA Web Camera - FHD                  | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 73.33%  |
| Alcor Micro | 3         | 20%     |
| Lenovo      | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 8         | 53.33%  |
| Broadcom BCM5880 Secure Applications Processor | 3         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 13.33%  |
| Lenovo Integrated Smart Card Reader            | 1         | 6.67%   |
| Alcor Micro Watchdata W 1981                   | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 49        | 41.88%  |
| 1     | 46        | 39.32%  |
| 2     | 15        | 12.82%  |
| 3     | 6         | 5.13%   |
| 7     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 25        | 27.17%  |
| Graphics card            | 18        | 19.57%  |
| Net/wireless             | 13        | 14.13%  |
| Chipcard                 | 12        | 13.04%  |
| Unassigned class         | 5         | 5.43%   |
| Communication controller | 5         | 5.43%   |
| Card reader              | 3         | 3.26%   |
| Bluetooth                | 3         | 3.26%   |
| Storage                  | 2         | 2.17%   |
| Sound                    | 2         | 2.17%   |
| Multimedia controller    | 2         | 2.17%   |
| Net/ethernet             | 1         | 1.09%   |
| Firewire controller      | 1         | 1.09%   |

