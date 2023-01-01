OpenMandriva 4.2 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.2/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.2/Notebook/README.md).

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

Total: 4716

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [4ab759533b](https://linux-hardware.org/?probe=4ab759533b) | Dec 25, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | M51Vr                       | Notebook    | [ffc48a52ea](https://linux-hardware.org/?probe=ffc48a52ea) | Dec 22, 2022 |
| Gigabyte      | EP43-DS3                    | Desktop     | [d0f0cd82f9](https://linux-hardware.org/?probe=d0f0cd82f9) | Dec 22, 2022 |
| HP            | Presario CQ62               | Notebook    | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| HP            | Compaq 6735s                | Notebook    | [72d29aa11f](https://linux-hardware.org/?probe=72d29aa11f) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| ASRock        | M3A770DE                    | Desktop     | [2e6b1f9c2d](https://linux-hardware.org/?probe=2e6b1f9c2d) | Dec 13, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [85794e606c](https://linux-hardware.org/?probe=85794e606c) | Dec 08, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [57e0d3651c](https://linux-hardware.org/?probe=57e0d3651c) | Dec 08, 2022 |
| Gigabyte      | GA-MA770-ES3                | Desktop     | [70c1a43352](https://linux-hardware.org/?probe=70c1a43352) | Dec 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a4a8d6dcec](https://linux-hardware.org/?probe=a4a8d6dcec) | Dec 03, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| ASUSTek       | K70IJ                       | Notebook    | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3f2ef35b32](https://linux-hardware.org/?probe=3f2ef35b32) | Nov 04, 2022 |
| MSI           | Z97-G43                     | Desktop     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9f10f8922](https://linux-hardware.org/?probe=a9f10f8922) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| VS Company    | G31T-M                      | Desktop     | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| HP            | G72                         | Notebook    | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [6b01f2f498](https://linux-hardware.org/?probe=6b01f2f498) | Oct 27, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ec46b18fd5](https://linux-hardware.org/?probe=ec46b18fd5) | Oct 25, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a995e58f10](https://linux-hardware.org/?probe=a995e58f10) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [69327d2615](https://linux-hardware.org/?probe=69327d2615) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| Sony          | VPCEB1S1R                   | Notebook    | [1e64f5427a](https://linux-hardware.org/?probe=1e64f5427a) | Oct 21, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [60e6bd1280](https://linux-hardware.org/?probe=60e6bd1280) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| HP            | Notebook                    | Notebook    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [69db41a0b6](https://linux-hardware.org/?probe=69db41a0b6) | Oct 06, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| HP            | 1998                        | Desktop     | [f8399e0d3a](https://linux-hardware.org/?probe=f8399e0d3a) | Sep 22, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [07477a078f](https://linux-hardware.org/?probe=07477a078f) | Sep 22, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [d55d9fad24](https://linux-hardware.org/?probe=d55d9fad24) | Sep 17, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [a790b35cc1](https://linux-hardware.org/?probe=a790b35cc1) | Sep 17, 2022 |
| Intel         | H61                         | Desktop     | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| HP            | 82F2 A01                    | Desktop     | [f97faeff54](https://linux-hardware.org/?probe=f97faeff54) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [d88e0026dc](https://linux-hardware.org/?probe=d88e0026dc) | Sep 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| HP            | 3396                        | Desktop     | [964f32cccf](https://linux-hardware.org/?probe=964f32cccf) | Sep 10, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| ASUSTek       | ET2040I                     | Desktop     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5ba20eb04b](https://linux-hardware.org/?probe=5ba20eb04b) | Sep 01, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| Lenovo        | ThinkCentre M58e 7408BA5    | Desktop     | [4384314f98](https://linux-hardware.org/?probe=4384314f98) | Sep 01, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [09ffe165d3](https://linux-hardware.org/?probe=09ffe165d3) | Aug 30, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| HP            | 82B4                        | Desktop     | [e3200ae579](https://linux-hardware.org/?probe=e3200ae579) | Aug 22, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [36a4120390](https://linux-hardware.org/?probe=36a4120390) | Aug 20, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [b05fac6451](https://linux-hardware.org/?probe=b05fac6451) | Aug 19, 2022 |
| Packard Be... | EasyNote TK37               | Notebook    | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Dell          | 0GM819                      | Desktop     | [f7745d3d3a](https://linux-hardware.org/?probe=f7745d3d3a) | Aug 16, 2022 |
| HP            | Notebook                    | Notebook    | [975f3e38e3](https://linux-hardware.org/?probe=975f3e38e3) | Aug 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [32bf5bd8b8](https://linux-hardware.org/?probe=32bf5bd8b8) | Aug 13, 2022 |
| Intel         | NUC7JYB J67967-405          | Mini pc     | [06fdb19375](https://linux-hardware.org/?probe=06fdb19375) | Aug 08, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e78351999](https://linux-hardware.org/?probe=9e78351999) | Aug 04, 2022 |
| MSI           | GE62VR 7RF                  | Notebook    | [e5f6f7e14c](https://linux-hardware.org/?probe=e5f6f7e14c) | Aug 03, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [cb93c45a3a](https://linux-hardware.org/?probe=cb93c45a3a) | Jul 31, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [2c1dddeaea](https://linux-hardware.org/?probe=2c1dddeaea) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d85cd905fd](https://linux-hardware.org/?probe=d85cd905fd) | Jul 28, 2022 |
| Dell          | 0P301D A00                  | Desktop     | [48d1ed3099](https://linux-hardware.org/?probe=48d1ed3099) | Jul 28, 2022 |
| HP            | 1495                        | Desktop     | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Dell          | 04GJJT A00                  | Desktop     | [ab730a80b3](https://linux-hardware.org/?probe=ab730a80b3) | Jul 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [2f0de52d8e](https://linux-hardware.org/?probe=2f0de52d8e) | Jul 08, 2022 |
| Gateway       | NE56R                       | Notebook    | [69f2805432](https://linux-hardware.org/?probe=69f2805432) | Jul 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [4160bc427a](https://linux-hardware.org/?probe=4160bc427a) | Jul 03, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [f5da6492ca](https://linux-hardware.org/?probe=f5da6492ca) | Jul 03, 2022 |
| Dell          | 0WPG9H A01                  | All in one  | [f554b4aa06](https://linux-hardware.org/?probe=f554b4aa06) | Jul 03, 2022 |
| Dell          | Latitude D630               | Notebook    | [df3001a64d](https://linux-hardware.org/?probe=df3001a64d) | Jul 02, 2022 |
| Notebook      | MIM 2200                    | Notebook    | [85748618b6](https://linux-hardware.org/?probe=85748618b6) | Jul 02, 2022 |
| Medion        | E2292                       | Convertible | [155434e3b5](https://linux-hardware.org/?probe=155434e3b5) | Jul 01, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [0924d664a1](https://linux-hardware.org/?probe=0924d664a1) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Dell          | Latitude E7250              | Notebook    | [790850da0b](https://linux-hardware.org/?probe=790850da0b) | Jun 22, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [98b2b138f4](https://linux-hardware.org/?probe=98b2b138f4) | Jun 20, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [8113862978](https://linux-hardware.org/?probe=8113862978) | Jun 18, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [6926193d76](https://linux-hardware.org/?probe=6926193d76) | Jun 18, 2022 |
| HP            | Pavilion dv6                | Notebook    | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Sony          | VGN-NW310F                  | Notebook    | [318b17f951](https://linux-hardware.org/?probe=318b17f951) | Jun 17, 2022 |
| HP            | Pavilion g4                 | Notebook    | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Extensa 5220                | Notebook    | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| Gigabyte      | H61M-HD2                    | Desktop     | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [2dd49013ff](https://linux-hardware.org/?probe=2dd49013ff) | Jun 10, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [a4587cc1de](https://linux-hardware.org/?probe=a4587cc1de) | Jun 10, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [17752552c6](https://linux-hardware.org/?probe=17752552c6) | Jun 02, 2022 |
| MSI           | MS-7255                     | Desktop     | [772cf64635](https://linux-hardware.org/?probe=772cf64635) | Jun 02, 2022 |
| ECS           | A58F2P-M4                   | Desktop     | [295c085967](https://linux-hardware.org/?probe=295c085967) | Jun 01, 2022 |
| Medion        | E7220                       | Notebook    | [d4a700af57](https://linux-hardware.org/?probe=d4a700af57) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Medion        | E2292                       | Convertible | [85296d99ac](https://linux-hardware.org/?probe=85296d99ac) | Jun 01, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [2966cd34b8](https://linux-hardware.org/?probe=2966cd34b8) | May 31, 2022 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [63747954e9](https://linux-hardware.org/?probe=63747954e9) | May 29, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| Clevo         | W55xEU                      | Notebook    | [c5fd2417f4](https://linux-hardware.org/?probe=c5fd2417f4) | May 25, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [bc39db0484](https://linux-hardware.org/?probe=bc39db0484) | May 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| MSI           | B150M BAZOOKA               | Desktop     | [b8ec3bee43](https://linux-hardware.org/?probe=b8ec3bee43) | May 22, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| Acer          | Aspire 5332                 | Notebook    | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [063aeed1a1](https://linux-hardware.org/?probe=063aeed1a1) | May 19, 2022 |
| Gigabyte      | GA-E6010N                   | Desktop     | [679cd1e540](https://linux-hardware.org/?probe=679cd1e540) | May 18, 2022 |
| Gigabyte      | X38-DQ6                     | Desktop     | [653ffc4014](https://linux-hardware.org/?probe=653ffc4014) | May 16, 2022 |
| Toshiba       | Satellite C670D-126         | Notebook    | [9df3447b21](https://linux-hardware.org/?probe=9df3447b21) | May 14, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [f3180b0817](https://linux-hardware.org/?probe=f3180b0817) | May 13, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9f28ef42a4](https://linux-hardware.org/?probe=9f28ef42a4) | May 11, 2022 |
| ASUSTek       | CROSSHAIR                   | Desktop     | [39f623cf4d](https://linux-hardware.org/?probe=39f623cf4d) | May 08, 2022 |
| Positivo      | POS-PARS760GCD              | Desktop     | [dfc00dfd71](https://linux-hardware.org/?probe=dfc00dfd71) | May 05, 2022 |
| Toshiba       | Satellite C645D             | Notebook    | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [f571b0dc6f](https://linux-hardware.org/?probe=f571b0dc6f) | May 02, 2022 |
| Medion        | E2292                       | Convertible | [6823c98493](https://linux-hardware.org/?probe=6823c98493) | May 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [53f6946eba](https://linux-hardware.org/?probe=53f6946eba) | May 01, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ea3bd2e330](https://linux-hardware.org/?probe=ea3bd2e330) | May 01, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [2e44e9228e](https://linux-hardware.org/?probe=2e44e9228e) | Apr 28, 2022 |
| PC Special... | NJ50_70CU                   | Notebook    | [a9b4399cad](https://linux-hardware.org/?probe=a9b4399cad) | Apr 26, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0e266b4987](https://linux-hardware.org/?probe=0e266b4987) | Apr 25, 2022 |
| Foxconn       | 945 7AD Series              | Desktop     | [04346c58f5](https://linux-hardware.org/?probe=04346c58f5) | Apr 23, 2022 |
| Pegatron      | EVANS                       | Desktop     | [118f512619](https://linux-hardware.org/?probe=118f512619) | Apr 21, 2022 |
| HP            | 304Ah                       | Desktop     | [08fbf0f311](https://linux-hardware.org/?probe=08fbf0f311) | Apr 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [9cabfec30b](https://linux-hardware.org/?probe=9cabfec30b) | Apr 19, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [80943ca395](https://linux-hardware.org/?probe=80943ca395) | Apr 18, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [4e70c05231](https://linux-hardware.org/?probe=4e70c05231) | Apr 17, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [1785652200](https://linux-hardware.org/?probe=1785652200) | Apr 16, 2022 |
| HP            | Pavilion dv6                | Notebook    | [639a7422d8](https://linux-hardware.org/?probe=639a7422d8) | Apr 16, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e9a5e187ad](https://linux-hardware.org/?probe=e9a5e187ad) | Apr 15, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| HP            | 2215                        | Desktop     | [5acea5fa0a](https://linux-hardware.org/?probe=5acea5fa0a) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| HP            | ProBook 470 G3              | Notebook    | [5c65c7eedd](https://linux-hardware.org/?probe=5c65c7eedd) | Apr 10, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [94fccb48fd](https://linux-hardware.org/?probe=94fccb48fd) | Apr 10, 2022 |
| Intel         | H81                         | Desktop     | [ffcfab5f12](https://linux-hardware.org/?probe=ffcfab5f12) | Apr 08, 2022 |
| ASRock        | Z270 Extreme4               | Desktop     | [526a5a16bd](https://linux-hardware.org/?probe=526a5a16bd) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ECS           | Nettle2                     | Desktop     | [65cedbb00d](https://linux-hardware.org/?probe=65cedbb00d) | Apr 07, 2022 |
| HP            | Pavilion dv6                | Notebook    | [209dbfbea6](https://linux-hardware.org/?probe=209dbfbea6) | Apr 06, 2022 |
| Medion        | E2292                       | Convertible | [3302d8f658](https://linux-hardware.org/?probe=3302d8f658) | Apr 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c5c24ea4c2](https://linux-hardware.org/?probe=c5c24ea4c2) | Apr 06, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [dff8141976](https://linux-hardware.org/?probe=dff8141976) | Apr 06, 2022 |
| Unknown       | P4M800CE-8237               | Desktop     | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| Packard Be... | EasyNote TJ71               | Notebook    | [9afad803e0](https://linux-hardware.org/?probe=9afad803e0) | Apr 05, 2022 |
| Dell          | 0CT017                      | Desktop     | [27bdeec11d](https://linux-hardware.org/?probe=27bdeec11d) | Apr 04, 2022 |
| Sony          | VGN-FZ31M                   | Notebook    | [5e1ef6c19a](https://linux-hardware.org/?probe=5e1ef6c19a) | Apr 03, 2022 |
| MSI           | X58M                        | Desktop     | [7484dce6ce](https://linux-hardware.org/?probe=7484dce6ce) | Apr 03, 2022 |
| Acer          | Aspire F5-571               | Notebook    | [68cb5f9f95](https://linux-hardware.org/?probe=68cb5f9f95) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [bd717d57c2](https://linux-hardware.org/?probe=bd717d57c2) | Apr 02, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [1aff91c424](https://linux-hardware.org/?probe=1aff91c424) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | Notebook    | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| HP            | 355 G2                      | Notebook    | [5a5271a7df](https://linux-hardware.org/?probe=5a5271a7df) | Mar 29, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [1991a3f990](https://linux-hardware.org/?probe=1991a3f990) | Mar 28, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [996a5d269c](https://linux-hardware.org/?probe=996a5d269c) | Mar 28, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3839ca9677](https://linux-hardware.org/?probe=3839ca9677) | Mar 27, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [3313178485](https://linux-hardware.org/?probe=3313178485) | Mar 25, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [0d7d21ac36](https://linux-hardware.org/?probe=0d7d21ac36) | Mar 24, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [f9fb419fef](https://linux-hardware.org/?probe=f9fb419fef) | Mar 23, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [91d5c07184](https://linux-hardware.org/?probe=91d5c07184) | Mar 22, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [44d6d432f9](https://linux-hardware.org/?probe=44d6d432f9) | Mar 21, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [50fd3adf1a](https://linux-hardware.org/?probe=50fd3adf1a) | Mar 21, 2022 |
| HP            | 81B3                        | Desktop     | [1924290221](https://linux-hardware.org/?probe=1924290221) | Mar 17, 2022 |
| Gigabyte      | GA-A75M-DS2                 | Desktop     | [7e23b31c1b](https://linux-hardware.org/?probe=7e23b31c1b) | Mar 17, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [0480518e2e](https://linux-hardware.org/?probe=0480518e2e) | Mar 15, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [9cad95edc1](https://linux-hardware.org/?probe=9cad95edc1) | Mar 12, 2022 |
| ASRock        | FM2A55M-VG3                 | Desktop     | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [dfa0722637](https://linux-hardware.org/?probe=dfa0722637) | Mar 12, 2022 |
| HP            | ENVY Notebook               | Notebook    | [591f84e3bb](https://linux-hardware.org/?probe=591f84e3bb) | Mar 11, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [83a319f258](https://linux-hardware.org/?probe=83a319f258) | Mar 11, 2022 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [8762e9c632](https://linux-hardware.org/?probe=8762e9c632) | Mar 10, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [1a3f77be23](https://linux-hardware.org/?probe=1a3f77be23) | Mar 09, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [9bcfd85a21](https://linux-hardware.org/?probe=9bcfd85a21) | Mar 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [74e5474a84](https://linux-hardware.org/?probe=74e5474a84) | Mar 05, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [bb9daa5ab1](https://linux-hardware.org/?probe=bb9daa5ab1) | Mar 05, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [18b982d433](https://linux-hardware.org/?probe=18b982d433) | Mar 05, 2022 |
| HP            | Pavilion dv5                | Notebook    | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [16ba341ccd](https://linux-hardware.org/?probe=16ba341ccd) | Mar 03, 2022 |
| Dell          | Inspiron 1420               | Notebook    | [30424b62be](https://linux-hardware.org/?probe=30424b62be) | Mar 03, 2022 |
| Medion        | E2292                       | Convertible | [e7fb0bbd0d](https://linux-hardware.org/?probe=e7fb0bbd0d) | Mar 01, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [fde5cc4a6c](https://linux-hardware.org/?probe=fde5cc4a6c) | Mar 01, 2022 |
| Foxconn       | 2A92                        | Desktop     | [d41fb8dda1](https://linux-hardware.org/?probe=d41fb8dda1) | Feb 28, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [a757f64435](https://linux-hardware.org/?probe=a757f64435) | Feb 28, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [40f6802b71](https://linux-hardware.org/?probe=40f6802b71) | Feb 27, 2022 |
| Acer          | RS880M05                    | Desktop     | [53e88a31a0](https://linux-hardware.org/?probe=53e88a31a0) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| MSI           | H410M PRO                   | Desktop     | [60cb5eed90](https://linux-hardware.org/?probe=60cb5eed90) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | Notebook    | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| MSI           | KA780G                      | Desktop     | [f6bc0eda57](https://linux-hardware.org/?probe=f6bc0eda57) | Feb 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| ASRock        | Q1900M                      | Desktop     | [428eb82cd0](https://linux-hardware.org/?probe=428eb82cd0) | Feb 23, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [99c0e6257f](https://linux-hardware.org/?probe=99c0e6257f) | Feb 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [0fd5d9a994](https://linux-hardware.org/?probe=0fd5d9a994) | Feb 20, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [ceceebf84f](https://linux-hardware.org/?probe=ceceebf84f) | Feb 19, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e9d45ff571](https://linux-hardware.org/?probe=e9d45ff571) | Feb 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [e8a3ceb5a9](https://linux-hardware.org/?probe=e8a3ceb5a9) | Feb 18, 2022 |
| Acer          | One Z1402                   | Notebook    | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [87de36a11b](https://linux-hardware.org/?probe=87de36a11b) | Feb 17, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [740ff0ffcc](https://linux-hardware.org/?probe=740ff0ffcc) | Feb 17, 2022 |
| ASRock        | N68-GS                      | Desktop     | [06e4bc5238](https://linux-hardware.org/?probe=06e4bc5238) | Feb 16, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | Notebook    | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Lenovo        | ThinkCentre M58p 7630A38    | Desktop     | [5317cf122d](https://linux-hardware.org/?probe=5317cf122d) | Feb 15, 2022 |
| Huanan        | X79-ZD3 V2.3                | Desktop     | [c20523ee1f](https://linux-hardware.org/?probe=c20523ee1f) | Feb 15, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [34d933c2f3](https://linux-hardware.org/?probe=34d933c2f3) | Feb 15, 2022 |
| Dell          | 0TT708 A01                  | Desktop     | [4f615ac094](https://linux-hardware.org/?probe=4f615ac094) | Feb 15, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [ab6cd0396d](https://linux-hardware.org/?probe=ab6cd0396d) | Feb 14, 2022 |
| Philco        | 10D                         | Desktop     | [2efb7555a1](https://linux-hardware.org/?probe=2efb7555a1) | Feb 14, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [64c37730f6](https://linux-hardware.org/?probe=64c37730f6) | Feb 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [1bade168b7](https://linux-hardware.org/?probe=1bade168b7) | Feb 13, 2022 |
| Acer          | Extensa 2519                | Notebook    | [4da8d63710](https://linux-hardware.org/?probe=4da8d63710) | Feb 13, 2022 |
| Sony          | SVF1521G6EW                 | Notebook    | [365ef21d2a](https://linux-hardware.org/?probe=365ef21d2a) | Feb 13, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [85b90b81ce](https://linux-hardware.org/?probe=85b90b81ce) | Feb 13, 2022 |
| Acer          | Aspire V5-122               | Notebook    | [d516569472](https://linux-hardware.org/?probe=d516569472) | Feb 13, 2022 |
| Acer          | Aspire E1-530               | Notebook    | [21e2a6f70a](https://linux-hardware.org/?probe=21e2a6f70a) | Feb 13, 2022 |
| HP            | 1998                        | Desktop     | [6b68df0b96](https://linux-hardware.org/?probe=6b68df0b96) | Feb 12, 2022 |
| ASUSTek       | K52F                        | Notebook    | [46e3780be8](https://linux-hardware.org/?probe=46e3780be8) | Feb 12, 2022 |
| Intel         | DG45ID AAE27729-308         | Desktop     | [91f90c2997](https://linux-hardware.org/?probe=91f90c2997) | Feb 12, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b229af38f0](https://linux-hardware.org/?probe=b229af38f0) | Feb 12, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5356027467](https://linux-hardware.org/?probe=5356027467) | Feb 12, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [d9dbe1d02f](https://linux-hardware.org/?probe=d9dbe1d02f) | Feb 11, 2022 |
| MouseCompu... | B75H2-M2                    | Desktop     | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| Dell          | 06NWYK A00                  | Desktop     | [a4654ee182](https://linux-hardware.org/?probe=a4654ee182) | Feb 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [285b0fc2fd](https://linux-hardware.org/?probe=285b0fc2fd) | Feb 11, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5182b3bbf6](https://linux-hardware.org/?probe=5182b3bbf6) | Feb 10, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [bdda853706](https://linux-hardware.org/?probe=bdda853706) | Feb 09, 2022 |
| Acer          | Aspire 6935                 | Notebook    | [d0dd380298](https://linux-hardware.org/?probe=d0dd380298) | Feb 08, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bf3e4dae03](https://linux-hardware.org/?probe=bf3e4dae03) | Feb 08, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [9aa6cb1e41](https://linux-hardware.org/?probe=9aa6cb1e41) | Feb 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [6754affc30](https://linux-hardware.org/?probe=6754affc30) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b23b568543](https://linux-hardware.org/?probe=b23b568543) | Feb 08, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | Notebook    | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [485e063883](https://linux-hardware.org/?probe=485e063883) | Feb 07, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [54ebd54640](https://linux-hardware.org/?probe=54ebd54640) | Feb 07, 2022 |
| ASUSTek       | P7H55                       | Desktop     | [1ac17e6259](https://linux-hardware.org/?probe=1ac17e6259) | Feb 07, 2022 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [efb562bd96](https://linux-hardware.org/?probe=efb562bd96) | Feb 07, 2022 |
| Toshiba       | Satellite C855-22N          | Notebook    | [e8a4451a9d](https://linux-hardware.org/?probe=e8a4451a9d) | Feb 06, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [2e55ebbf9f](https://linux-hardware.org/?probe=2e55ebbf9f) | Feb 06, 2022 |
| MSI           | 760GA-P43                   | Desktop     | [6212c219c8](https://linux-hardware.org/?probe=6212c219c8) | Feb 06, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [f7d707147c](https://linux-hardware.org/?probe=f7d707147c) | Feb 06, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [f6bb9b0ffd](https://linux-hardware.org/?probe=f6bb9b0ffd) | Feb 06, 2022 |
| HP            | 3397                        | Desktop     | [5e842a74ac](https://linux-hardware.org/?probe=5e842a74ac) | Feb 06, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [3c1c6e0805](https://linux-hardware.org/?probe=3c1c6e0805) | Feb 06, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [261fb2f356](https://linux-hardware.org/?probe=261fb2f356) | Feb 06, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [a5db2b8436](https://linux-hardware.org/?probe=a5db2b8436) | Feb 06, 2022 |
| Dell          | G3 3779                     | Notebook    | [c9185bcf1f](https://linux-hardware.org/?probe=c9185bcf1f) | Feb 06, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [fb82e73470](https://linux-hardware.org/?probe=fb82e73470) | Feb 06, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f00c7a8507](https://linux-hardware.org/?probe=f00c7a8507) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9c87bc4fca](https://linux-hardware.org/?probe=9c87bc4fca) | Feb 05, 2022 |
| Acer          | Acadia V1.40                | Notebook    | [b18e761c0f](https://linux-hardware.org/?probe=b18e761c0f) | Feb 05, 2022 |
| Medion        | MS-7800                     | Desktop     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [61007dacfd](https://linux-hardware.org/?probe=61007dacfd) | Feb 05, 2022 |
| ASUSTek       | M4N68T                      | Desktop     | [5052fa9dac](https://linux-hardware.org/?probe=5052fa9dac) | Feb 05, 2022 |
| Acer          | Extensa 5620                | Notebook    | [d5048cae9a](https://linux-hardware.org/?probe=d5048cae9a) | Feb 05, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [fef25611fb](https://linux-hardware.org/?probe=fef25611fb) | Feb 05, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [10c9ca0b26](https://linux-hardware.org/?probe=10c9ca0b26) | Feb 05, 2022 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [895bbcb050](https://linux-hardware.org/?probe=895bbcb050) | Feb 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [80996b75ff](https://linux-hardware.org/?probe=80996b75ff) | Feb 04, 2022 |
| MSI           | MS-7392                     | Desktop     | [e8f489c1fc](https://linux-hardware.org/?probe=e8f489c1fc) | Feb 04, 2022 |
| HP            | Pavilion dm1                | Notebook    | [4b0fcd3df5](https://linux-hardware.org/?probe=4b0fcd3df5) | Feb 04, 2022 |
| Dell          | 09PV3R A00                  | Desktop     | [23a9613450](https://linux-hardware.org/?probe=23a9613450) | Feb 04, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [a9613de1e1](https://linux-hardware.org/?probe=a9613de1e1) | Feb 04, 2022 |
| HP            | 355 G2                      | Notebook    | [2a05eb0f1c](https://linux-hardware.org/?probe=2a05eb0f1c) | Feb 04, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [378fec89b1](https://linux-hardware.org/?probe=378fec89b1) | Feb 04, 2022 |
| Medion        | E2292                       | Convertible | [10a64531f1](https://linux-hardware.org/?probe=10a64531f1) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [5d9fd312b4](https://linux-hardware.org/?probe=5d9fd312b4) | Feb 03, 2022 |
| Clevo         | P150HMx                     | Notebook    | [8f04d16711](https://linux-hardware.org/?probe=8f04d16711) | Feb 03, 2022 |
| Inventec      | Z CLASS A02                 | Desktop     | [32bbd0c80c](https://linux-hardware.org/?probe=32bbd0c80c) | Feb 03, 2022 |
| Dell          | 0773VG A01                  | Desktop     | [b1c8ece218](https://linux-hardware.org/?probe=b1c8ece218) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [63c15e2642](https://linux-hardware.org/?probe=63c15e2642) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [67e8645c04](https://linux-hardware.org/?probe=67e8645c04) | Feb 03, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [b8645533ae](https://linux-hardware.org/?probe=b8645533ae) | Feb 02, 2022 |
| HP            | 8105                        | Desktop     | [8e49155614](https://linux-hardware.org/?probe=8e49155614) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | H61M-E                      | Desktop     | [6075abc821](https://linux-hardware.org/?probe=6075abc821) | Feb 02, 2022 |
| Dell          | Latitude D630               | Notebook    | [f7a31d8e3e](https://linux-hardware.org/?probe=f7a31d8e3e) | Feb 02, 2022 |
| Unknown       | X99H                        | Desktop     | [29bd27d08f](https://linux-hardware.org/?probe=29bd27d08f) | Feb 02, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [71569beb05](https://linux-hardware.org/?probe=71569beb05) | Feb 02, 2022 |
| Lenovo        | ThinkPad W700 27526LG       | Notebook    | [06b01ba136](https://linux-hardware.org/?probe=06b01ba136) | Feb 02, 2022 |
| HP            | 355 G2                      | Notebook    | [96a86baab9](https://linux-hardware.org/?probe=96a86baab9) | Feb 02, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [bdb825e963](https://linux-hardware.org/?probe=bdb825e963) | Feb 02, 2022 |
| MSI           | VR201                       | Notebook    | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [5e92f5c961](https://linux-hardware.org/?probe=5e92f5c961) | Feb 01, 2022 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [6ad345c1a5](https://linux-hardware.org/?probe=6ad345c1a5) | Feb 01, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | Notebook    | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Sony          | VGN-FE31H                   | Notebook    | [a7185cc26a](https://linux-hardware.org/?probe=a7185cc26a) | Feb 01, 2022 |
| Toshiba       | Satellite Pro R850          | Notebook    | [8d5f88157a](https://linux-hardware.org/?probe=8d5f88157a) | Feb 01, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [ead4c2c3fb](https://linux-hardware.org/?probe=ead4c2c3fb) | Feb 01, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [b08503a021](https://linux-hardware.org/?probe=b08503a021) | Feb 01, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [e8c4b3dfce](https://linux-hardware.org/?probe=e8c4b3dfce) | Jan 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [5d06ba826f](https://linux-hardware.org/?probe=5d06ba826f) | Jan 31, 2022 |
| Teclast       | F15S                        | Notebook    | [f3161d72b0](https://linux-hardware.org/?probe=f3161d72b0) | Jan 30, 2022 |
| HP            | ProBook 6470b               | Notebook    | [86ba660bb5](https://linux-hardware.org/?probe=86ba660bb5) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [a909d3702b](https://linux-hardware.org/?probe=a909d3702b) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [b02315f2c0](https://linux-hardware.org/?probe=b02315f2c0) | Jan 30, 2022 |
| Gigabyte      | H81N                        | Desktop     | [9f53b79a7f](https://linux-hardware.org/?probe=9f53b79a7f) | Jan 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [83fbdbf54b](https://linux-hardware.org/?probe=83fbdbf54b) | Jan 29, 2022 |
| Acer          | Aspire V5-571               | Notebook    | [9c1e6c6a9e](https://linux-hardware.org/?probe=9c1e6c6a9e) | Jan 29, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ddf886b767](https://linux-hardware.org/?probe=ddf886b767) | Jan 29, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [f024dd97a0](https://linux-hardware.org/?probe=f024dd97a0) | Jan 29, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [33d0a3b270](https://linux-hardware.org/?probe=33d0a3b270) | Jan 29, 2022 |
| ASRock        | ION3D-HT                    | Desktop     | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| Toshiba       | Satellite Pro P200          | Notebook    | [2edecbff69](https://linux-hardware.org/?probe=2edecbff69) | Jan 29, 2022 |
| ASUSTek       | P5G41T-M LX PLUS            | Desktop     | [f3a447ef83](https://linux-hardware.org/?probe=f3a447ef83) | Jan 29, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [36fa473b25](https://linux-hardware.org/?probe=36fa473b25) | Jan 29, 2022 |
| IBM           | PCI-Express Riser Card, ... | Server      | [701b89ac2e](https://linux-hardware.org/?probe=701b89ac2e) | Jan 29, 2022 |
| Acer          | Aspire 8942G                | Notebook    | [97a7a92547](https://linux-hardware.org/?probe=97a7a92547) | Jan 28, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [9770dbdaeb](https://linux-hardware.org/?probe=9770dbdaeb) | Jan 28, 2022 |
| ASUSTek       | P8H67-I PRO                 | Desktop     | [640b7e8450](https://linux-hardware.org/?probe=640b7e8450) | Jan 28, 2022 |
| Dell          | Wolf                        | Notebook    | [8fc168eba7](https://linux-hardware.org/?probe=8fc168eba7) | Jan 27, 2022 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [044e014d11](https://linux-hardware.org/?probe=044e014d11) | Jan 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e96d993823](https://linux-hardware.org/?probe=e96d993823) | Jan 26, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [55f310b74b](https://linux-hardware.org/?probe=55f310b74b) | Jan 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [e3308423e5](https://linux-hardware.org/?probe=e3308423e5) | Jan 26, 2022 |
| HP            | ProBook 6550b               | Notebook    | [02d7f3125e](https://linux-hardware.org/?probe=02d7f3125e) | Jan 26, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [4df21e66db](https://linux-hardware.org/?probe=4df21e66db) | Jan 25, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| HP            | 655                         | Notebook    | [68e37d8274](https://linux-hardware.org/?probe=68e37d8274) | Jan 25, 2022 |
| Dell          | Latitude E5410              | Notebook    | [074ed63eb9](https://linux-hardware.org/?probe=074ed63eb9) | Jan 25, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| Timi          | TM1801                      | Notebook    | [349fdb5215](https://linux-hardware.org/?probe=349fdb5215) | Jan 25, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [0210b11791](https://linux-hardware.org/?probe=0210b11791) | Jan 25, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e0eb175311](https://linux-hardware.org/?probe=e0eb175311) | Jan 25, 2022 |
| Positivo      | Mobile                      | Notebook    | [9b53719e46](https://linux-hardware.org/?probe=9b53719e46) | Jan 25, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [6210f4db07](https://linux-hardware.org/?probe=6210f4db07) | Jan 25, 2022 |
| Acer          | V5-131                      | Notebook    | [ac6664dce9](https://linux-hardware.org/?probe=ac6664dce9) | Jan 25, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [71c6779d52](https://linux-hardware.org/?probe=71c6779d52) | Jan 24, 2022 |
| Acer          | Extensa 2540                | Notebook    | [27a41f2533](https://linux-hardware.org/?probe=27a41f2533) | Jan 24, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [a212372095](https://linux-hardware.org/?probe=a212372095) | Jan 24, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [154348ae3a](https://linux-hardware.org/?probe=154348ae3a) | Jan 24, 2022 |
| Lenovo        | ThinkPad T520 4242NS9       | Notebook    | [100812fcd9](https://linux-hardware.org/?probe=100812fcd9) | Jan 24, 2022 |
| ASRock        | AM1B-ITX                    | Desktop     | [5f089eb5bf](https://linux-hardware.org/?probe=5f089eb5bf) | Jan 24, 2022 |
| MSI           | X58M                        | Desktop     | [cf092b7735](https://linux-hardware.org/?probe=cf092b7735) | Jan 24, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [46a5cef815](https://linux-hardware.org/?probe=46a5cef815) | Jan 23, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [20a42368f1](https://linux-hardware.org/?probe=20a42368f1) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | Notebook    | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [e018d5506c](https://linux-hardware.org/?probe=e018d5506c) | Jan 23, 2022 |
| Acer          | Extensa 4630Z               | Notebook    | [40d8b3d26c](https://linux-hardware.org/?probe=40d8b3d26c) | Jan 23, 2022 |
| Eii           | WSA116                      | Notebook    | [ecff258a89](https://linux-hardware.org/?probe=ecff258a89) | Jan 23, 2022 |
| Medion        | MS-7713                     | Desktop     | [e3eb63e81f](https://linux-hardware.org/?probe=e3eb63e81f) | Jan 22, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [c51916b063](https://linux-hardware.org/?probe=c51916b063) | Jan 22, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [5c8ac15198](https://linux-hardware.org/?probe=5c8ac15198) | Jan 22, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [93a2a7dea6](https://linux-hardware.org/?probe=93a2a7dea6) | Jan 22, 2022 |
| Foxconn       | ALOE                        | Desktop     | [a1c7a071c6](https://linux-hardware.org/?probe=a1c7a071c6) | Jan 22, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [cf464f5bce](https://linux-hardware.org/?probe=cf464f5bce) | Jan 22, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [eebb00a00f](https://linux-hardware.org/?probe=eebb00a00f) | Jan 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [d2c416e76d](https://linux-hardware.org/?probe=d2c416e76d) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [963e5b822d](https://linux-hardware.org/?probe=963e5b822d) | Jan 21, 2022 |
| Foxconn       | A76GMV                      | Desktop     | [c25b49803b](https://linux-hardware.org/?probe=c25b49803b) | Jan 21, 2022 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [515ba182ff](https://linux-hardware.org/?probe=515ba182ff) | Jan 21, 2022 |
| Philco        | 14I                         | Notebook    | [5006ca52e2](https://linux-hardware.org/?probe=5006ca52e2) | Jan 21, 2022 |
| Dell          | Latitude 3540               | Notebook    | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [bac342fc0f](https://linux-hardware.org/?probe=bac342fc0f) | Jan 21, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [7023fd83fc](https://linux-hardware.org/?probe=7023fd83fc) | Jan 21, 2022 |
| Sony          | VPCEB18FD                   | Notebook    | [5fbd1a31a6](https://linux-hardware.org/?probe=5fbd1a31a6) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | 339A                        | Desktop     | [9a1c8ec615](https://linux-hardware.org/?probe=9a1c8ec615) | Jan 21, 2022 |
| Dell          | Inspiron 3482               | Notebook    | [f13427c9b0](https://linux-hardware.org/?probe=f13427c9b0) | Jan 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d70ebfd602](https://linux-hardware.org/?probe=d70ebfd602) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [e94ba1d4f2](https://linux-hardware.org/?probe=e94ba1d4f2) | Jan 20, 2022 |
| Acer          | WMCP78M                     | Desktop     | [96428e77d6](https://linux-hardware.org/?probe=96428e77d6) | Jan 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [2a013fff75](https://linux-hardware.org/?probe=2a013fff75) | Jan 20, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [6907df60fb](https://linux-hardware.org/?probe=6907df60fb) | Jan 20, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [e47bd66b78](https://linux-hardware.org/?probe=e47bd66b78) | Jan 20, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [08e0b12a83](https://linux-hardware.org/?probe=08e0b12a83) | Jan 19, 2022 |
| Acer          | Aspire TC-390               | Desktop     | [a6a7896071](https://linux-hardware.org/?probe=a6a7896071) | Jan 19, 2022 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | Notebook    | [e9bebad8ef](https://linux-hardware.org/?probe=e9bebad8ef) | Jan 19, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [3caf7fb5f2](https://linux-hardware.org/?probe=3caf7fb5f2) | Jan 19, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [c00b17efdc](https://linux-hardware.org/?probe=c00b17efdc) | Jan 19, 2022 |
| HP            | 3029h                       | Desktop     | [21048ac4b2](https://linux-hardware.org/?probe=21048ac4b2) | Jan 19, 2022 |
| Alienware     | 2                           | Desktop     | [e149bdddfa](https://linux-hardware.org/?probe=e149bdddfa) | Jan 18, 2022 |
| Dell          | MXG071                      | Notebook    | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | V-P5G31                     | Desktop     | [ab3ad44c74](https://linux-hardware.org/?probe=ab3ad44c74) | Jan 18, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [95bbde94a9](https://linux-hardware.org/?probe=95bbde94a9) | Jan 18, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| Samsung       | R410P                       | Notebook    | [7837bc7c5f](https://linux-hardware.org/?probe=7837bc7c5f) | Jan 17, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [e88e9c2f3d](https://linux-hardware.org/?probe=e88e9c2f3d) | Jan 17, 2022 |
| ASUSTek       | P5K-VM                      | Desktop     | [8b7c021ac4](https://linux-hardware.org/?probe=8b7c021ac4) | Jan 17, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [005887e692](https://linux-hardware.org/?probe=005887e692) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [fd321a896a](https://linux-hardware.org/?probe=fd321a896a) | Jan 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [5baec4640b](https://linux-hardware.org/?probe=5baec4640b) | Jan 16, 2022 |
| ASUSTek       | K53U                        | Notebook    | [7e754deb91](https://linux-hardware.org/?probe=7e754deb91) | Jan 16, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d6d4dbbb78](https://linux-hardware.org/?probe=d6d4dbbb78) | Jan 16, 2022 |
| Lenovo        | ThinkPad T420 4236LP7       | Notebook    | [92673f1d6e](https://linux-hardware.org/?probe=92673f1d6e) | Jan 16, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [a83705b242](https://linux-hardware.org/?probe=a83705b242) | Jan 16, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [b59d482466](https://linux-hardware.org/?probe=b59d482466) | Jan 16, 2022 |
| Dell          | 0KC9NP A00                  | Desktop     | [9cc01ad5c0](https://linux-hardware.org/?probe=9cc01ad5c0) | Jan 15, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [6da7af33f8](https://linux-hardware.org/?probe=6da7af33f8) | Jan 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [671180553c](https://linux-hardware.org/?probe=671180553c) | Jan 14, 2022 |
| MSI           | 2A9C                        | Desktop     | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [7ca6a7c129](https://linux-hardware.org/?probe=7ca6a7c129) | Jan 14, 2022 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [27f00874af](https://linux-hardware.org/?probe=27f00874af) | Jan 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Fujitsu Si... | D2464-B1 S26361-D2464-B1    | Desktop     | [962a3a8bb0](https://linux-hardware.org/?probe=962a3a8bb0) | Jan 14, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [ccee69eba1](https://linux-hardware.org/?probe=ccee69eba1) | Jan 14, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [6b023312e7](https://linux-hardware.org/?probe=6b023312e7) | Jan 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [972630705f](https://linux-hardware.org/?probe=972630705f) | Jan 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5724c20f52](https://linux-hardware.org/?probe=5724c20f52) | Jan 14, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [f6b8d075cf](https://linux-hardware.org/?probe=f6b8d075cf) | Jan 13, 2022 |
| MSI           | MS-B0961                    | All in one  | [de1e024cad](https://linux-hardware.org/?probe=de1e024cad) | Jan 13, 2022 |
| MSI           | MS-7A66                     | Desktop     | [fcddf8cda4](https://linux-hardware.org/?probe=fcddf8cda4) | Jan 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ad49cdde74](https://linux-hardware.org/?probe=ad49cdde74) | Jan 13, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [4fae921f3e](https://linux-hardware.org/?probe=4fae921f3e) | Jan 13, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [6dbf0bdf2f](https://linux-hardware.org/?probe=6dbf0bdf2f) | Jan 13, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cee1b9aefb](https://linux-hardware.org/?probe=cee1b9aefb) | Jan 13, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [59338f2a1a](https://linux-hardware.org/?probe=59338f2a1a) | Jan 12, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5f8ab9c9ce](https://linux-hardware.org/?probe=5f8ab9c9ce) | Jan 11, 2022 |
| Samsung       | N100SP                      | Notebook    | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| Sony          | VPCEH1S1E                   | Notebook    | [854163fb58](https://linux-hardware.org/?probe=854163fb58) | Jan 10, 2022 |
| MSI           | A68HM GRENADE               | Desktop     | [0f44471905](https://linux-hardware.org/?probe=0f44471905) | Jan 10, 2022 |
| Gigabyte      | M52S-S3P                    | Desktop     | [5bdd85e9b5](https://linux-hardware.org/?probe=5bdd85e9b5) | Jan 10, 2022 |
| Medion        | E2292                       | Convertible | [b3b81f7289](https://linux-hardware.org/?probe=b3b81f7289) | Jan 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [053236f8c0](https://linux-hardware.org/?probe=053236f8c0) | Jan 09, 2022 |
| System76      | Galago Pro                  | Notebook    | [1295378270](https://linux-hardware.org/?probe=1295378270) | Jan 09, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [f3ebd22f2f](https://linux-hardware.org/?probe=f3ebd22f2f) | Jan 08, 2022 |
| Wortmann      | TERRA_PC                    | Desktop     | [16239fb870](https://linux-hardware.org/?probe=16239fb870) | Jan 08, 2022 |
| ASRock        | G31M-S                      | Desktop     | [30212e6fd6](https://linux-hardware.org/?probe=30212e6fd6) | Jan 08, 2022 |
| HP            | G62                         | Notebook    | [aacfc1cff1](https://linux-hardware.org/?probe=aacfc1cff1) | Jan 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0c29e5ae78](https://linux-hardware.org/?probe=0c29e5ae78) | Jan 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| Acer          | Aspire 1510                 | Notebook    | [26c825b4a7](https://linux-hardware.org/?probe=26c825b4a7) | Jan 07, 2022 |
| MSI           | H61M-P25                    | Desktop     | [f5060a86a8](https://linux-hardware.org/?probe=f5060a86a8) | Jan 07, 2022 |
| ASUSTek       | All Series                  | Notebook    | [951c8c3ffc](https://linux-hardware.org/?probe=951c8c3ffc) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [53e9ec174a](https://linux-hardware.org/?probe=53e9ec174a) | Jan 06, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [6ef0cffa6b](https://linux-hardware.org/?probe=6ef0cffa6b) | Jan 06, 2022 |
| HP            | 8309                        | Desktop     | [3cee70d4fc](https://linux-hardware.org/?probe=3cee70d4fc) | Jan 06, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [2cb2bbbfc6](https://linux-hardware.org/?probe=2cb2bbbfc6) | Jan 06, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [42710e0964](https://linux-hardware.org/?probe=42710e0964) | Jan 06, 2022 |
| Dell          | XPS L521X                   | Notebook    | [204c990a51](https://linux-hardware.org/?probe=204c990a51) | Jan 06, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [c4aed880fb](https://linux-hardware.org/?probe=c4aed880fb) | Jan 05, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7a0e13a7c1](https://linux-hardware.org/?probe=7a0e13a7c1) | Jan 05, 2022 |
| Dell          | Latitude 3301               | Notebook    | [e00b2dbfbc](https://linux-hardware.org/?probe=e00b2dbfbc) | Jan 05, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [b34e6337ae](https://linux-hardware.org/?probe=b34e6337ae) | Jan 05, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [073f2c3d43](https://linux-hardware.org/?probe=073f2c3d43) | Jan 05, 2022 |
| HP            | ProBook 4530s               | Notebook    | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | Notebook    | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b6c0836e89](https://linux-hardware.org/?probe=b6c0836e89) | Jan 04, 2022 |
| HP            | 635                         | Notebook    | [aafd01b4db](https://linux-hardware.org/?probe=aafd01b4db) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001DPB     | Notebook    | [cb0f7db023](https://linux-hardware.org/?probe=cb0f7db023) | Jan 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [665bf5dae7](https://linux-hardware.org/?probe=665bf5dae7) | Jan 04, 2022 |
| HP            | Pavilion m6                 | Notebook    | [be191c0d05](https://linux-hardware.org/?probe=be191c0d05) | Jan 04, 2022 |
| Gateway       | DX4320                      | Desktop     | [64fc897aa2](https://linux-hardware.org/?probe=64fc897aa2) | Jan 04, 2022 |
| MSI           | 880G-E45                    | Desktop     | [b45f683278](https://linux-hardware.org/?probe=b45f683278) | Jan 04, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [95f33224e9](https://linux-hardware.org/?probe=95f33224e9) | Jan 04, 2022 |
| ASUSTek       | H81T                        | Desktop     | [fb5cc5d8e3](https://linux-hardware.org/?probe=fb5cc5d8e3) | Jan 03, 2022 |
| Sony          | VGN-NW2SRF_S                | Notebook    | [e1e99e3e88](https://linux-hardware.org/?probe=e1e99e3e88) | Jan 03, 2022 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [7b813765f3](https://linux-hardware.org/?probe=7b813765f3) | Jan 03, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [a1905b9b4a](https://linux-hardware.org/?probe=a1905b9b4a) | Jan 03, 2022 |
| ASUSTek       | CM1735                      | Desktop     | [92165700b1](https://linux-hardware.org/?probe=92165700b1) | Jan 02, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b4d1a18243](https://linux-hardware.org/?probe=b4d1a18243) | Jan 02, 2022 |
| Lenovo        | 3181 SDK0J40697 WIN 3305... | Mini pc     | [56f9a83d77](https://linux-hardware.org/?probe=56f9a83d77) | Jan 02, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [bc3cdc4e31](https://linux-hardware.org/?probe=bc3cdc4e31) | Jan 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [edfbd4eb1c](https://linux-hardware.org/?probe=edfbd4eb1c) | Jan 02, 2022 |
| HP            | Notebook                    | Notebook    | [48f175a513](https://linux-hardware.org/?probe=48f175a513) | Jan 02, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [393b7857f2](https://linux-hardware.org/?probe=393b7857f2) | Jan 02, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | Notebook    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b1e6f7cd7c](https://linux-hardware.org/?probe=b1e6f7cd7c) | Jan 01, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [616c133c6e](https://linux-hardware.org/?probe=616c133c6e) | Jan 01, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [2126000e67](https://linux-hardware.org/?probe=2126000e67) | Jan 01, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2a3dbdc07a](https://linux-hardware.org/?probe=2a3dbdc07a) | Jan 01, 2022 |
| eMachines     | E525                        | Notebook    | [192bbb8b30](https://linux-hardware.org/?probe=192bbb8b30) | Jan 01, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [a073f421c1](https://linux-hardware.org/?probe=a073f421c1) | Jan 01, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [428a598475](https://linux-hardware.org/?probe=428a598475) | Dec 31, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [820456adab](https://linux-hardware.org/?probe=820456adab) | Dec 31, 2021 |
| HP            | 83E8                        | Desktop     | [c79a0cc45e](https://linux-hardware.org/?probe=c79a0cc45e) | Dec 31, 2021 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f7f99c478d](https://linux-hardware.org/?probe=f7f99c478d) | Dec 31, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [667da7e2b7](https://linux-hardware.org/?probe=667da7e2b7) | Dec 31, 2021 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [469127a5f9](https://linux-hardware.org/?probe=469127a5f9) | Dec 31, 2021 |
| Dell          | Latitude E6230              | Notebook    | [45bd8ebfa3](https://linux-hardware.org/?probe=45bd8ebfa3) | Dec 31, 2021 |
| Toshiba       | Satellite C870D-119         | Notebook    | [2731f273f4](https://linux-hardware.org/?probe=2731f273f4) | Dec 30, 2021 |
| Samsung       | R540/SA41/E452              | Notebook    | [5e1fcfa3a5](https://linux-hardware.org/?probe=5e1fcfa3a5) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| ASRock        | 945GCM-S                    | Desktop     | [b089710f53](https://linux-hardware.org/?probe=b089710f53) | Dec 30, 2021 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [428d5b007d](https://linux-hardware.org/?probe=428d5b007d) | Dec 30, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [da7dd95049](https://linux-hardware.org/?probe=da7dd95049) | Dec 29, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [b699cbc873](https://linux-hardware.org/?probe=b699cbc873) | Dec 29, 2021 |
| Lenovo        | IdeaPad P500 20210          | Notebook    | [395d599207](https://linux-hardware.org/?probe=395d599207) | Dec 29, 2021 |
| ASRock        | B85M-HDS                    | Desktop     | [8806a9db07](https://linux-hardware.org/?probe=8806a9db07) | Dec 29, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [204ffe4516](https://linux-hardware.org/?probe=204ffe4516) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | Desktop     | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [3550171788](https://linux-hardware.org/?probe=3550171788) | Dec 29, 2021 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [f87be438d3](https://linux-hardware.org/?probe=f87be438d3) | Dec 29, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [50ccc07d3e](https://linux-hardware.org/?probe=50ccc07d3e) | Dec 29, 2021 |
| Biostar       | A960D+V2                    | Desktop     | [447fc7af58](https://linux-hardware.org/?probe=447fc7af58) | Dec 29, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [aad84241ca](https://linux-hardware.org/?probe=aad84241ca) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [461677d69d](https://linux-hardware.org/?probe=461677d69d) | Dec 28, 2021 |
| ASRock        | H61MV-ITX                   | Desktop     | [be772b3f4a](https://linux-hardware.org/?probe=be772b3f4a) | Dec 28, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [509959fdd1](https://linux-hardware.org/?probe=509959fdd1) | Dec 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [0f2350ed15](https://linux-hardware.org/?probe=0f2350ed15) | Dec 28, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | Desktop     | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [8b9308b9a4](https://linux-hardware.org/?probe=8b9308b9a4) | Dec 28, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [6587985fe7](https://linux-hardware.org/?probe=6587985fe7) | Dec 28, 2021 |
| MSI           | A68HM GRENADE               | Desktop     | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| MSI           | MS-7922                     | Desktop     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| ASUSTek       | X45U                        | Notebook    | [55d2da3313](https://linux-hardware.org/?probe=55d2da3313) | Dec 27, 2021 |
| Sony          | SVT11125CBS                 | Notebook    | [961f242a60](https://linux-hardware.org/?probe=961f242a60) | Dec 27, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [e3c3ae36a2](https://linux-hardware.org/?probe=e3c3ae36a2) | Dec 27, 2021 |
| HP            | 0AA0h                       | Desktop     | [8786bc36f4](https://linux-hardware.org/?probe=8786bc36f4) | Dec 27, 2021 |
| HP            | EliteBook 8740w             | Notebook    | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| ZOTAC         | H55                         | Desktop     | [08e8c1aff2](https://linux-hardware.org/?probe=08e8c1aff2) | Dec 27, 2021 |
| HP            | Notebook                    | Notebook    | [d496159ad3](https://linux-hardware.org/?probe=d496159ad3) | Dec 26, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [28aad352f5](https://linux-hardware.org/?probe=28aad352f5) | Dec 26, 2021 |
| Dell          | Inspiron 3451               | Notebook    | [d0340265ee](https://linux-hardware.org/?probe=d0340265ee) | Dec 26, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [24ba3bb7a0](https://linux-hardware.org/?probe=24ba3bb7a0) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | Notebook    | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [4c00491c87](https://linux-hardware.org/?probe=4c00491c87) | Dec 25, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [f06229224a](https://linux-hardware.org/?probe=f06229224a) | Dec 25, 2021 |
| LEADER        | NH5BT11                     | Notebook    | [763efa7eb2](https://linux-hardware.org/?probe=763efa7eb2) | Dec 25, 2021 |
| HP            | 650                         | Notebook    | [339ab3e2d2](https://linux-hardware.org/?probe=339ab3e2d2) | Dec 25, 2021 |
| Lenovo        | ThinkPad T500 2087A75       | Notebook    | [6a1f2d337c](https://linux-hardware.org/?probe=6a1f2d337c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [840f7b0eff](https://linux-hardware.org/?probe=840f7b0eff) | Dec 25, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| Dell          | Inspiron 3451               | Notebook    | [73576a9684](https://linux-hardware.org/?probe=73576a9684) | Dec 24, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8e6899196e](https://linux-hardware.org/?probe=8e6899196e) | Dec 24, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [bf8476146c](https://linux-hardware.org/?probe=bf8476146c) | Dec 24, 2021 |
| Acer          | Extensa 215-51K             | Notebook    | [eb7ebb463b](https://linux-hardware.org/?probe=eb7ebb463b) | Dec 23, 2021 |
| Toshiba       | Satellite L355              | Notebook    | [63c919a1ed](https://linux-hardware.org/?probe=63c919a1ed) | Dec 23, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2797b5bd37](https://linux-hardware.org/?probe=2797b5bd37) | Dec 23, 2021 |
| MSI           | 0A90                        | Desktop     | [b08d40599d](https://linux-hardware.org/?probe=b08d40599d) | Dec 23, 2021 |
| Gigabyte      | MJPLNCB-00                  | Desktop     | [fe81720eae](https://linux-hardware.org/?probe=fe81720eae) | Dec 23, 2021 |
| Fujitsu       | FMVNA7BEC                   | Notebook    | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [4b36ec9c1a](https://linux-hardware.org/?probe=4b36ec9c1a) | Dec 23, 2021 |
| ASRock        | Q1900M                      | Desktop     | [627eef9622](https://linux-hardware.org/?probe=627eef9622) | Dec 22, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [a6fc4a2adb](https://linux-hardware.org/?probe=a6fc4a2adb) | Dec 22, 2021 |
| HP            | 198E                        | Desktop     | [bb9b36a65b](https://linux-hardware.org/?probe=bb9b36a65b) | Dec 22, 2021 |
| HP            | 2B47                        | Desktop     | [64a4b36df8](https://linux-hardware.org/?probe=64a4b36df8) | Dec 22, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [2c859e7444](https://linux-hardware.org/?probe=2c859e7444) | Dec 22, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [146165d8d1](https://linux-hardware.org/?probe=146165d8d1) | Dec 22, 2021 |
| Lenovo        | M30-70 20446                | Notebook    | [127f503834](https://linux-hardware.org/?probe=127f503834) | Dec 22, 2021 |
| Biostar       | A68N-5600E                  | Desktop     | [9ed7856f41](https://linux-hardware.org/?probe=9ed7856f41) | Dec 22, 2021 |
| Dell          | Latitude E6510              | Notebook    | [e637c26490](https://linux-hardware.org/?probe=e637c26490) | Dec 21, 2021 |
| Acer          | Aspire One 522              | Notebook    | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [729cb86592](https://linux-hardware.org/?probe=729cb86592) | Dec 21, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d9ca1d1db](https://linux-hardware.org/?probe=5d9ca1d1db) | Dec 21, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | Notebook    | [0b0d4dd23f](https://linux-hardware.org/?probe=0b0d4dd23f) | Dec 21, 2021 |
| Acer          | TravelMate P259-MG          | Notebook    | [e589fbcecc](https://linux-hardware.org/?probe=e589fbcecc) | Dec 20, 2021 |
| HP            | 8158 A01                    | Mini pc     | [85ef8f7dba](https://linux-hardware.org/?probe=85ef8f7dba) | Dec 20, 2021 |
| Dell          | G5 5590                     | Notebook    | [d548c52867](https://linux-hardware.org/?probe=d548c52867) | Dec 20, 2021 |
| Itautec       | AL 2022 AL 2022 Padrao 0... | All in one  | [9defc41ed2](https://linux-hardware.org/?probe=9defc41ed2) | Dec 20, 2021 |
| eMachines     | Unknown                     | Notebook    | [6b9767faba](https://linux-hardware.org/?probe=6b9767faba) | Dec 20, 2021 |
| Dell          | Latitude E5400              | Notebook    | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [dd3539200c](https://linux-hardware.org/?probe=dd3539200c) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [899ca3371c](https://linux-hardware.org/?probe=899ca3371c) | Dec 20, 2021 |
| Acer          | TP-W701P-53334G1            | Notebook    | [674f2996b5](https://linux-hardware.org/?probe=674f2996b5) | Dec 19, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [61993c502d](https://linux-hardware.org/?probe=61993c502d) | Dec 19, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [af2a2e4db9](https://linux-hardware.org/?probe=af2a2e4db9) | Dec 19, 2021 |
| HP            | Notebook                    | Notebook    | [5aaca3e01e](https://linux-hardware.org/?probe=5aaca3e01e) | Dec 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [90575747f7](https://linux-hardware.org/?probe=90575747f7) | Dec 18, 2021 |
| Dell          | 0478VN A00                  | Desktop     | [67955910cb](https://linux-hardware.org/?probe=67955910cb) | Dec 18, 2021 |
| ASUSTek       | P5B-MX/WiFi-AP              | Desktop     | [97a556a1b1](https://linux-hardware.org/?probe=97a556a1b1) | Dec 18, 2021 |
| Dell          | 0J468K A00                  | Desktop     | [8233d2b0d6](https://linux-hardware.org/?probe=8233d2b0d6) | Dec 18, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [19694f0921](https://linux-hardware.org/?probe=19694f0921) | Dec 18, 2021 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fda86b8b4a](https://linux-hardware.org/?probe=fda86b8b4a) | Dec 18, 2021 |
| Toshiba       | Satellite C855D             | Notebook    | [daee1ba27b](https://linux-hardware.org/?probe=daee1ba27b) | Dec 18, 2021 |
| Samsung       | 550XDA                      | Notebook    | [6b3fd04b47](https://linux-hardware.org/?probe=6b3fd04b47) | Dec 18, 2021 |
| Dell          | Inspiron 3451               | Notebook    | [bd37d8fdf8](https://linux-hardware.org/?probe=bd37d8fdf8) | Dec 18, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [3854ed74f2](https://linux-hardware.org/?probe=3854ed74f2) | Dec 17, 2021 |
| Sony          | VPCEF3E1E                   | Notebook    | [f26bff938f](https://linux-hardware.org/?probe=f26bff938f) | Dec 17, 2021 |
| HP            | 0A00h                       | Desktop     | [56585a2839](https://linux-hardware.org/?probe=56585a2839) | Dec 17, 2021 |
| MSI           | G31TM-P35                   | Desktop     | [320ad12871](https://linux-hardware.org/?probe=320ad12871) | Dec 17, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [972c765b35](https://linux-hardware.org/?probe=972c765b35) | Dec 17, 2021 |
| MSI           | 2AE0                        | Desktop     | [f40b9dbbbe](https://linux-hardware.org/?probe=f40b9dbbbe) | Dec 16, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [52dca5cabc](https://linux-hardware.org/?probe=52dca5cabc) | Dec 16, 2021 |
| ASUSTek       | K53SJ                       | Notebook    | [1ffcc2cfda](https://linux-hardware.org/?probe=1ffcc2cfda) | Dec 16, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [70801591a7](https://linux-hardware.org/?probe=70801591a7) | Dec 16, 2021 |
| Positivo      | S14BW01                     | Notebook    | [94de31910c](https://linux-hardware.org/?probe=94de31910c) | Dec 16, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [64d0453982](https://linux-hardware.org/?probe=64d0453982) | Dec 15, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [061faf00df](https://linux-hardware.org/?probe=061faf00df) | Dec 15, 2021 |
| ASUSTek       | H81-GAMER                   | Desktop     | [74658e6a83](https://linux-hardware.org/?probe=74658e6a83) | Dec 15, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [926db6c655](https://linux-hardware.org/?probe=926db6c655) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | Notebook    | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [81c28c074e](https://linux-hardware.org/?probe=81c28c074e) | Dec 14, 2021 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [4575aea29e](https://linux-hardware.org/?probe=4575aea29e) | Dec 14, 2021 |
| Acer          | Aspire A315-54K             | Notebook    | [56741904bd](https://linux-hardware.org/?probe=56741904bd) | Dec 13, 2021 |
| ASUSTek       | UL30A                       | Notebook    | [3f3677f6ee](https://linux-hardware.org/?probe=3f3677f6ee) | Dec 13, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| HP            | 18E9                        | Desktop     | [870f4a67a7](https://linux-hardware.org/?probe=870f4a67a7) | Dec 13, 2021 |
| MSI           | A88XM-E35 V2                | Desktop     | [ecd99b833d](https://linux-hardware.org/?probe=ecd99b833d) | Dec 13, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Dell          | 0HJ781                      | Desktop     | [acac78cc8a](https://linux-hardware.org/?probe=acac78cc8a) | Dec 12, 2021 |
| ASRock        | N68-S3 FX                   | Desktop     | [3cbe6d3002](https://linux-hardware.org/?probe=3cbe6d3002) | Dec 12, 2021 |
| Pegatron      | Benicia                     | Desktop     | [500489691f](https://linux-hardware.org/?probe=500489691f) | Dec 11, 2021 |
| Lenovo        | Unknown                     | Convertible | [fac9e252e4](https://linux-hardware.org/?probe=fac9e252e4) | Dec 11, 2021 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [d533c4790e](https://linux-hardware.org/?probe=d533c4790e) | Dec 10, 2021 |
| HP            | Pavilion 15                 | Notebook    | [99645415a4](https://linux-hardware.org/?probe=99645415a4) | Dec 10, 2021 |
| Lenovo        | ThinkPad T410 2537Z7A       | Notebook    | [d6ddba3925](https://linux-hardware.org/?probe=d6ddba3925) | Dec 10, 2021 |
| Sony          | SVE1513B1EW                 | Notebook    | [094d9138e5](https://linux-hardware.org/?probe=094d9138e5) | Dec 10, 2021 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | Notebook    | [e5a940ffdf](https://linux-hardware.org/?probe=e5a940ffdf) | Dec 10, 2021 |
| HP            | 0A54h                       | Desktop     | [417e076869](https://linux-hardware.org/?probe=417e076869) | Dec 10, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3b955f362a](https://linux-hardware.org/?probe=3b955f362a) | Dec 10, 2021 |
| Toshiba       | TE5                         | Notebook    | [fb39721f00](https://linux-hardware.org/?probe=fb39721f00) | Dec 10, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [bc8f942a1a](https://linux-hardware.org/?probe=bc8f942a1a) | Dec 10, 2021 |
| LG Electro... | A410-G.BC49P1               | Notebook    | [5f952dc625](https://linux-hardware.org/?probe=5f952dc625) | Dec 09, 2021 |
| Lenovo        | ThinkPad E550 20DF002YUS    | Notebook    | [1533118145](https://linux-hardware.org/?probe=1533118145) | Dec 09, 2021 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [730046deb9](https://linux-hardware.org/?probe=730046deb9) | Dec 09, 2021 |
| eMachines     | D520 V1.04                  | Notebook    | [932e776d87](https://linux-hardware.org/?probe=932e776d87) | Dec 08, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [fe423d9f2d](https://linux-hardware.org/?probe=fe423d9f2d) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [9df7c17faf](https://linux-hardware.org/?probe=9df7c17faf) | Dec 08, 2021 |
| Acer          | M945G                       | Desktop     | [5c72066083](https://linux-hardware.org/?probe=5c72066083) | Dec 08, 2021 |
| HP            | 620                         | Notebook    | [7612676b9a](https://linux-hardware.org/?probe=7612676b9a) | Dec 08, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [96f8dadd49](https://linux-hardware.org/?probe=96f8dadd49) | Dec 08, 2021 |
| Biostar       | NF520-A2 TE                 | Desktop     | [5878187120](https://linux-hardware.org/?probe=5878187120) | Dec 07, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [e96b1f7f6b](https://linux-hardware.org/?probe=e96b1f7f6b) | Dec 07, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [319b95b99d](https://linux-hardware.org/?probe=319b95b99d) | Dec 07, 2021 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [db3905e629](https://linux-hardware.org/?probe=db3905e629) | Dec 07, 2021 |
| Dell          | Inspiron 7773               | Notebook    | [2f7c3c0c0b](https://linux-hardware.org/?probe=2f7c3c0c0b) | Dec 07, 2021 |
| OEM           | B75                         | Desktop     | [d6a1e29a32](https://linux-hardware.org/?probe=d6a1e29a32) | Dec 07, 2021 |
| eMachines     | E525                        | Notebook    | [eb1ee3fb6c](https://linux-hardware.org/?probe=eb1ee3fb6c) | Dec 07, 2021 |
| MSI           | H61M-P20                    | Desktop     | [614ffcb196](https://linux-hardware.org/?probe=614ffcb196) | Dec 07, 2021 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [add6c240f9](https://linux-hardware.org/?probe=add6c240f9) | Dec 07, 2021 |
| Huanan        | B85                         | Desktop     | [d2b55c013c](https://linux-hardware.org/?probe=d2b55c013c) | Dec 07, 2021 |
| Chuwi         | LapBook Pro                 | Notebook    | [ad5d162393](https://linux-hardware.org/?probe=ad5d162393) | Dec 06, 2021 |
| Gateway       | DT55                        | Desktop     | [efc935f11c](https://linux-hardware.org/?probe=efc935f11c) | Dec 06, 2021 |
| Positivo      | J14AL11                     | Notebook    | [2e5fd22945](https://linux-hardware.org/?probe=2e5fd22945) | Dec 06, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [5a00aff0fc](https://linux-hardware.org/?probe=5a00aff0fc) | Dec 06, 2021 |
| Unknown       | Phitronics PN73PVS-M        | Desktop     | [f64b92d5b2](https://linux-hardware.org/?probe=f64b92d5b2) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [17c270ac38](https://linux-hardware.org/?probe=17c270ac38) | Dec 06, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [75933dd4ba](https://linux-hardware.org/?probe=75933dd4ba) | Dec 06, 2021 |
| Acer          | Aspire E1-421               | Notebook    | [a7c18d534d](https://linux-hardware.org/?probe=a7c18d534d) | Dec 06, 2021 |
| RM            | NOTEBOOK 320                | Notebook    | [6998aef680](https://linux-hardware.org/?probe=6998aef680) | Dec 06, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | Notebook    | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [960d7d5035](https://linux-hardware.org/?probe=960d7d5035) | Dec 05, 2021 |
| HP            | Notebook                    | Notebook    | [d7c2bef552](https://linux-hardware.org/?probe=d7c2bef552) | Dec 05, 2021 |
| Dell          | Latitude E6430              | Notebook    | [eee07229a4](https://linux-hardware.org/?probe=eee07229a4) | Dec 05, 2021 |
| Dell          | Latitude E6410              | Notebook    | [07ca5fc75a](https://linux-hardware.org/?probe=07ca5fc75a) | Dec 05, 2021 |
| ASUSTek       | K84L                        | Notebook    | [dce2044275](https://linux-hardware.org/?probe=dce2044275) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | Notebook    | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| HP            | Pavilion g7                 | Notebook    | [795980ab4c](https://linux-hardware.org/?probe=795980ab4c) | Dec 04, 2021 |
| Gigabyte      | Z590 VISION G               | Desktop     | [51e33fc095](https://linux-hardware.org/?probe=51e33fc095) | Dec 03, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [89a5a0d5ac](https://linux-hardware.org/?probe=89a5a0d5ac) | Dec 03, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [b71a9c285d](https://linux-hardware.org/?probe=b71a9c285d) | Dec 03, 2021 |
| Medion        | E2292                       | Convertible | [956ff1bc48](https://linux-hardware.org/?probe=956ff1bc48) | Dec 03, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [5df988dd63](https://linux-hardware.org/?probe=5df988dd63) | Dec 03, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [615600f1dc](https://linux-hardware.org/?probe=615600f1dc) | Dec 03, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [bbdfd3b78e](https://linux-hardware.org/?probe=bbdfd3b78e) | Dec 02, 2021 |
| Medion        | Akoya E1317T                | Notebook    | [0d8103d7b7](https://linux-hardware.org/?probe=0d8103d7b7) | Dec 02, 2021 |
| Positivo      | H14BT58                     | Notebook    | [7e692b3a7a](https://linux-hardware.org/?probe=7e692b3a7a) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| MSI           | GE72 2QC                    | Notebook    | [db92825225](https://linux-hardware.org/?probe=db92825225) | Dec 02, 2021 |
| Philco        | 14F                         | Notebook    | [ab69e64295](https://linux-hardware.org/?probe=ab69e64295) | Dec 02, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [b6ee8bc974](https://linux-hardware.org/?probe=b6ee8bc974) | Dec 01, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [f69fadfb4b](https://linux-hardware.org/?probe=f69fadfb4b) | Dec 01, 2021 |
| Dell          | Latitude E6510              | Notebook    | [cef6e43321](https://linux-hardware.org/?probe=cef6e43321) | Dec 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [ca8a5a1ea8](https://linux-hardware.org/?probe=ca8a5a1ea8) | Dec 01, 2021 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [13325b986f](https://linux-hardware.org/?probe=13325b986f) | Dec 01, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [ddcca3f92c](https://linux-hardware.org/?probe=ddcca3f92c) | Dec 01, 2021 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [89046e697d](https://linux-hardware.org/?probe=89046e697d) | Nov 30, 2021 |
| ASUSTek       | M2N                         | Desktop     | [8f674fd086](https://linux-hardware.org/?probe=8f674fd086) | Nov 30, 2021 |
| HP            | 2215                        | Desktop     | [a9a43dfbe0](https://linux-hardware.org/?probe=a9a43dfbe0) | Nov 30, 2021 |
| LattePanda    | Delta CDJQ-BI-7-S70GR200... | Desktop     | [25d7f6e054](https://linux-hardware.org/?probe=25d7f6e054) | Nov 30, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [59da226d80](https://linux-hardware.org/?probe=59da226d80) | Nov 30, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [c935a13f9f](https://linux-hardware.org/?probe=c935a13f9f) | Nov 29, 2021 |
| Intel         | H61                         | Desktop     | [e4a2b68a1b](https://linux-hardware.org/?probe=e4a2b68a1b) | Nov 29, 2021 |
| ASRock        | FM2A78M-DG3+                | Desktop     | [72dfdf487b](https://linux-hardware.org/?probe=72dfdf487b) | Nov 29, 2021 |
| Sony          | VPCEB1E9R                   | Notebook    | [28655d3e4d](https://linux-hardware.org/?probe=28655d3e4d) | Nov 29, 2021 |
| Lenovo        | ThinkPad L530 24792T1       | Notebook    | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [30820af902](https://linux-hardware.org/?probe=30820af902) | Nov 29, 2021 |
| Lenovo        | H420                        | Desktop     | [46b2e4c604](https://linux-hardware.org/?probe=46b2e4c604) | Nov 29, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| HP            | 14                          | Notebook    | [d7cb66a845](https://linux-hardware.org/?probe=d7cb66a845) | Nov 28, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [7c5fdbe652](https://linux-hardware.org/?probe=7c5fdbe652) | Nov 28, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [aab55d2e9a](https://linux-hardware.org/?probe=aab55d2e9a) | Nov 28, 2021 |
| Acer          | P4LJ0                       | Notebook    | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [d5d420fbf8](https://linux-hardware.org/?probe=d5d420fbf8) | Nov 27, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [18f091832c](https://linux-hardware.org/?probe=18f091832c) | Nov 27, 2021 |
| Acer          | Ferrari One 200             | Notebook    | [57001d93d1](https://linux-hardware.org/?probe=57001d93d1) | Nov 27, 2021 |
| ASUSTek       | M3A32-MVP DELUXE            | Desktop     | [2b259d6d47](https://linux-hardware.org/?probe=2b259d6d47) | Nov 27, 2021 |
| HP            | 3047h                       | Desktop     | [4ccf9bec03](https://linux-hardware.org/?probe=4ccf9bec03) | Nov 27, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [1a6e8764f5](https://linux-hardware.org/?probe=1a6e8764f5) | Nov 27, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [53441b22f8](https://linux-hardware.org/?probe=53441b22f8) | Nov 27, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [94bbae91a2](https://linux-hardware.org/?probe=94bbae91a2) | Nov 27, 2021 |
| ASUSTek       | PN40                        | Mini pc     | [3d309b05a0](https://linux-hardware.org/?probe=3d309b05a0) | Nov 26, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [448bb6c3ec](https://linux-hardware.org/?probe=448bb6c3ec) | Nov 26, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [20e8f6655f](https://linux-hardware.org/?probe=20e8f6655f) | Nov 26, 2021 |
| Dell          | 0WG864                      | Desktop     | [0c33b47ccd](https://linux-hardware.org/?probe=0c33b47ccd) | Nov 26, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c62dc3b138](https://linux-hardware.org/?probe=c62dc3b138) | Nov 25, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [4305ff478f](https://linux-hardware.org/?probe=4305ff478f) | Nov 25, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [b6d30a2918](https://linux-hardware.org/?probe=b6d30a2918) | Nov 25, 2021 |
| HP            | Compaq 15                   | Notebook    | [8aede4cf2d](https://linux-hardware.org/?probe=8aede4cf2d) | Nov 25, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [5af76e9a00](https://linux-hardware.org/?probe=5af76e9a00) | Nov 25, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0e8b0ffebd](https://linux-hardware.org/?probe=0e8b0ffebd) | Nov 25, 2021 |
| HP            | 245 G6                      | Notebook    | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| ASUSTek       | K50IN                       | Notebook    | [b3baa5bea0](https://linux-hardware.org/?probe=b3baa5bea0) | Nov 24, 2021 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [ee1c5bfbac](https://linux-hardware.org/?probe=ee1c5bfbac) | Nov 24, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c487bf6a9c](https://linux-hardware.org/?probe=c487bf6a9c) | Nov 24, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [7d66f3183b](https://linux-hardware.org/?probe=7d66f3183b) | Nov 24, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e558eb1777](https://linux-hardware.org/?probe=e558eb1777) | Nov 24, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [54c37833db](https://linux-hardware.org/?probe=54c37833db) | Nov 23, 2021 |
| Toshiba       | STI 012887                  | Desktop     | [f021a9f7a7](https://linux-hardware.org/?probe=f021a9f7a7) | Nov 23, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [dd276cffaa](https://linux-hardware.org/?probe=dd276cffaa) | Nov 23, 2021 |
| Acer          | Aspire 5338                 | Notebook    | [db097f4f70](https://linux-hardware.org/?probe=db097f4f70) | Nov 23, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [3eb9def4af](https://linux-hardware.org/?probe=3eb9def4af) | Nov 23, 2021 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [138f5b0109](https://linux-hardware.org/?probe=138f5b0109) | Nov 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ef65932064](https://linux-hardware.org/?probe=ef65932064) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [42e20a3566](https://linux-hardware.org/?probe=42e20a3566) | Nov 22, 2021 |
| Sony          | SVT13115FGS                 | Notebook    | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8fb57be688](https://linux-hardware.org/?probe=8fb57be688) | Nov 22, 2021 |
| Lenovo        | ThinkPad T430 2347CL1       | Notebook    | [c13939a100](https://linux-hardware.org/?probe=c13939a100) | Nov 22, 2021 |
| HP            | 1998                        | Desktop     | [258c0fce4a](https://linux-hardware.org/?probe=258c0fce4a) | Nov 22, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [860506d6bd](https://linux-hardware.org/?probe=860506d6bd) | Nov 22, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [a87c6cfa14](https://linux-hardware.org/?probe=a87c6cfa14) | Nov 21, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e8c286f335](https://linux-hardware.org/?probe=e8c286f335) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c0960ee402](https://linux-hardware.org/?probe=c0960ee402) | Nov 21, 2021 |
| ASUSTek       | ET2002G                     | All in one  | [a31ccc8a05](https://linux-hardware.org/?probe=a31ccc8a05) | Nov 21, 2021 |
| Dell          | G5 5590                     | Notebook    | [7704b7b3ea](https://linux-hardware.org/?probe=7704b7b3ea) | Nov 21, 2021 |
| Medion        | Akoya P6638                 | Notebook    | [dca71e6592](https://linux-hardware.org/?probe=dca71e6592) | Nov 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [423bdd7d74](https://linux-hardware.org/?probe=423bdd7d74) | Nov 21, 2021 |
| Acer          | Aspire E5-432G              | Notebook    | [d6fe7992f3](https://linux-hardware.org/?probe=d6fe7992f3) | Nov 21, 2021 |
| Acer          | Aspire V5-471P              | Notebook    | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6d6e422cfc](https://linux-hardware.org/?probe=6d6e422cfc) | Nov 20, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4c179204f8](https://linux-hardware.org/?probe=4c179204f8) | Nov 20, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [1a5ca1d992](https://linux-hardware.org/?probe=1a5ca1d992) | Nov 20, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [c5dc9a3bde](https://linux-hardware.org/?probe=c5dc9a3bde) | Nov 20, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [ccd5a782d0](https://linux-hardware.org/?probe=ccd5a782d0) | Nov 20, 2021 |
| Acer          | TravelMate B311-31          | Notebook    | [75d144f180](https://linux-hardware.org/?probe=75d144f180) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | Notebook    | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [adc3036124](https://linux-hardware.org/?probe=adc3036124) | Nov 19, 2021 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [b63110a5f3](https://linux-hardware.org/?probe=b63110a5f3) | Nov 19, 2021 |
| Lenovo        | ThinkPad T520 4243ED3       | Notebook    | [973921bfad](https://linux-hardware.org/?probe=973921bfad) | Nov 19, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [be19e72980](https://linux-hardware.org/?probe=be19e72980) | Nov 19, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [28722b08e1](https://linux-hardware.org/?probe=28722b08e1) | Nov 19, 2021 |
| Supermicro    | C2SBX Hewlett               | Desktop     | [478694e0e0](https://linux-hardware.org/?probe=478694e0e0) | Nov 19, 2021 |
| ASUSTek       | K73SD                       | Notebook    | [75b029cf30](https://linux-hardware.org/?probe=75b029cf30) | Nov 19, 2021 |
| Medion        | A17                         | Notebook    | [55d3f6120b](https://linux-hardware.org/?probe=55d3f6120b) | Nov 19, 2021 |
| ASUSTek       | P5VD2-MX SE                 | Desktop     | [bf34c9fbca](https://linux-hardware.org/?probe=bf34c9fbca) | Nov 19, 2021 |
| HP            | Notebook                    | Notebook    | [b93914e090](https://linux-hardware.org/?probe=b93914e090) | Nov 18, 2021 |
| AMD           | AOPW-PLUS                   | Server      | [4a83a85932](https://linux-hardware.org/?probe=4a83a85932) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [1cd779bd1d](https://linux-hardware.org/?probe=1cd779bd1d) | Nov 18, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [1a1f1149c1](https://linux-hardware.org/?probe=1a1f1149c1) | Nov 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [bb94961cc9](https://linux-hardware.org/?probe=bb94961cc9) | Nov 18, 2021 |
| Lenovo        | 36FF No DPK                 | All in one  | [9aa68c7a65](https://linux-hardware.org/?probe=9aa68c7a65) | Nov 18, 2021 |
| CSL-Comput... | R Evolve C14i               | Notebook    | [7efef38952](https://linux-hardware.org/?probe=7efef38952) | Nov 18, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [9523e1fbb6](https://linux-hardware.org/?probe=9523e1fbb6) | Nov 18, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [63290c282b](https://linux-hardware.org/?probe=63290c282b) | Nov 18, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [0415c0798f](https://linux-hardware.org/?probe=0415c0798f) | Nov 18, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [9e28f131eb](https://linux-hardware.org/?probe=9e28f131eb) | Nov 18, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [3528c3828b](https://linux-hardware.org/?probe=3528c3828b) | Nov 18, 2021 |
| Lenovo        | G475 20080                  | Notebook    | [98bc985284](https://linux-hardware.org/?probe=98bc985284) | Nov 18, 2021 |
| Lenovo        | ThinkPad T520 42433VG       | Notebook    | [529262c2e4](https://linux-hardware.org/?probe=529262c2e4) | Nov 17, 2021 |
| Acer          | Predator PH315-51           | Notebook    | [77c52e9cd3](https://linux-hardware.org/?probe=77c52e9cd3) | Nov 17, 2021 |
| Biostar       | TH67B                       | Desktop     | [5d655fd2bd](https://linux-hardware.org/?probe=5d655fd2bd) | Nov 17, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| HP            | 0A58h                       | Desktop     | [caecb0c75f](https://linux-hardware.org/?probe=caecb0c75f) | Nov 17, 2021 |
| Dell          | Latitude E5520              | Notebook    | [4cdf5273ab](https://linux-hardware.org/?probe=4cdf5273ab) | Nov 16, 2021 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [5b90bc1ed9](https://linux-hardware.org/?probe=5b90bc1ed9) | Nov 16, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [f5a7f54888](https://linux-hardware.org/?probe=f5a7f54888) | Nov 16, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [198dd099be](https://linux-hardware.org/?probe=198dd099be) | Nov 16, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [665b5517a8](https://linux-hardware.org/?probe=665b5517a8) | Nov 16, 2021 |
| HP            | 8054                        | Desktop     | [9f5560c4b7](https://linux-hardware.org/?probe=9f5560c4b7) | Nov 16, 2021 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [203c43fc12](https://linux-hardware.org/?probe=203c43fc12) | Nov 15, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [79030e87e9](https://linux-hardware.org/?probe=79030e87e9) | Nov 15, 2021 |
| MSI           | MS-7529                     | Desktop     | [d6f55ff177](https://linux-hardware.org/?probe=d6f55ff177) | Nov 15, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [c057cfbdb4](https://linux-hardware.org/?probe=c057cfbdb4) | Nov 15, 2021 |
| ASUSTek       | P5KPL                       | Desktop     | [6e52b269ee](https://linux-hardware.org/?probe=6e52b269ee) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4b7d36666a](https://linux-hardware.org/?probe=4b7d36666a) | Nov 15, 2021 |
| ASRock        | H470M-HDV                   | Desktop     | [09b482f622](https://linux-hardware.org/?probe=09b482f622) | Nov 15, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [58809fa055](https://linux-hardware.org/?probe=58809fa055) | Nov 14, 2021 |
| Dell          | Latitude E6420              | Notebook    | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [cf6f4d66a4](https://linux-hardware.org/?probe=cf6f4d66a4) | Nov 14, 2021 |
| SLIMBOOK      | PRO                         | Notebook    | [7aafeb8c15](https://linux-hardware.org/?probe=7aafeb8c15) | Nov 14, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5120795ac2](https://linux-hardware.org/?probe=5120795ac2) | Nov 14, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [29d6ad8b6f](https://linux-hardware.org/?probe=29d6ad8b6f) | Nov 14, 2021 |
| Dell          | Latitude E6320              | Notebook    | [2eebab8f3a](https://linux-hardware.org/?probe=2eebab8f3a) | Nov 14, 2021 |
| Medion        | ERAZER X7857 MD60893        | Notebook    | [2f979af179](https://linux-hardware.org/?probe=2f979af179) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [09a1713d46](https://linux-hardware.org/?probe=09a1713d46) | Nov 14, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [58ba001f88](https://linux-hardware.org/?probe=58ba001f88) | Nov 14, 2021 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [fed47693de](https://linux-hardware.org/?probe=fed47693de) | Nov 14, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [7df7f1e92d](https://linux-hardware.org/?probe=7df7f1e92d) | Nov 14, 2021 |
| MSI           | H81M-P33                    | Desktop     | [76d3a6ff1e](https://linux-hardware.org/?probe=76d3a6ff1e) | Nov 13, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [3fd5da133f](https://linux-hardware.org/?probe=3fd5da133f) | Nov 13, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [cfd9893fd8](https://linux-hardware.org/?probe=cfd9893fd8) | Nov 13, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| Dell          | Inspiron 5379               | Notebook    | [691dab9bbc](https://linux-hardware.org/?probe=691dab9bbc) | Nov 13, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [59ca43cb01](https://linux-hardware.org/?probe=59ca43cb01) | Nov 12, 2021 |
| MSI           | B450M PRO-M2                | Desktop     | [dcf52c1b26](https://linux-hardware.org/?probe=dcf52c1b26) | Nov 12, 2021 |
| Alienware     | 01NYPT A00                  | Desktop     | [995985affc](https://linux-hardware.org/?probe=995985affc) | Nov 12, 2021 |
| HP            | 0A54h                       | Desktop     | [5573fe7b98](https://linux-hardware.org/?probe=5573fe7b98) | Nov 12, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| ASUSTek       | X75VC                       | Notebook    | [39352780e5](https://linux-hardware.org/?probe=39352780e5) | Nov 12, 2021 |
| ASUSTek       | P5VD2-MX                    | Desktop     | [2159202a53](https://linux-hardware.org/?probe=2159202a53) | Nov 12, 2021 |
| Lenovo        | ThinkPad T460 MFG_IN_GO     | Notebook    | [91bd573a72](https://linux-hardware.org/?probe=91bd573a72) | Nov 12, 2021 |
| Gigabyte      | GA-E6010N                   | Desktop     | [7bd45525ce](https://linux-hardware.org/?probe=7bd45525ce) | Nov 12, 2021 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [a81b523565](https://linux-hardware.org/?probe=a81b523565) | Nov 12, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [ed4570b3c1](https://linux-hardware.org/?probe=ed4570b3c1) | Nov 11, 2021 |
| Gigabyte      | P41T-D3P                    | Desktop     | [54a25af09a](https://linux-hardware.org/?probe=54a25af09a) | Nov 11, 2021 |
| HP            | 2000                        | Notebook    | [8ba69b64fe](https://linux-hardware.org/?probe=8ba69b64fe) | Nov 11, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [98ee61cefe](https://linux-hardware.org/?probe=98ee61cefe) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | Notebook    | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| Dell          | 0GM819                      | Desktop     | [4f630535ad](https://linux-hardware.org/?probe=4f630535ad) | Nov 11, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | Notebook    | [0cbad8aae1](https://linux-hardware.org/?probe=0cbad8aae1) | Nov 11, 2021 |
| Acer          | Aspire X3995                | Desktop     | [351c694ae4](https://linux-hardware.org/?probe=351c694ae4) | Nov 11, 2021 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [468d100cf4](https://linux-hardware.org/?probe=468d100cf4) | Nov 11, 2021 |
| INTELBRAS     | IE-G31TM7                   | Desktop     | [1b854398a1](https://linux-hardware.org/?probe=1b854398a1) | Nov 11, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [fe8ba3f801](https://linux-hardware.org/?probe=fe8ba3f801) | Nov 11, 2021 |
| ASUSTek       | P5G41-M LX                  | Desktop     | [05de777705](https://linux-hardware.org/?probe=05de777705) | Nov 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [afe9c5ca6f](https://linux-hardware.org/?probe=afe9c5ca6f) | Nov 10, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [20aa404ab6](https://linux-hardware.org/?probe=20aa404ab6) | Nov 10, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [9a8f9d0864](https://linux-hardware.org/?probe=9a8f9d0864) | Nov 10, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [312e04d7f9](https://linux-hardware.org/?probe=312e04d7f9) | Nov 09, 2021 |
| Samsung       | R530/R730/R540              | Notebook    | [a9360a0208](https://linux-hardware.org/?probe=a9360a0208) | Nov 09, 2021 |
| ASUSTek       | B85-PLUS                    | Desktop     | [c98055d3a7](https://linux-hardware.org/?probe=c98055d3a7) | Nov 09, 2021 |
| Acer          | Aspire E5-771               | Notebook    | [dd11733c60](https://linux-hardware.org/?probe=dd11733c60) | Nov 09, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [e89b41000d](https://linux-hardware.org/?probe=e89b41000d) | Nov 09, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [ab82eb7e00](https://linux-hardware.org/?probe=ab82eb7e00) | Nov 09, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [32ffc2e9a5](https://linux-hardware.org/?probe=32ffc2e9a5) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [9154e175ad](https://linux-hardware.org/?probe=9154e175ad) | Nov 09, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [1c8aa481f0](https://linux-hardware.org/?probe=1c8aa481f0) | Nov 09, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [fbc9822ad6](https://linux-hardware.org/?probe=fbc9822ad6) | Nov 09, 2021 |
| Lenovo        | ThinkCentre M90p 5450A26    | Desktop     | [53642a2043](https://linux-hardware.org/?probe=53642a2043) | Nov 09, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [e2c43ab9cf](https://linux-hardware.org/?probe=e2c43ab9cf) | Nov 08, 2021 |
| Acer          | AO725                       | Notebook    | [e39e3a5527](https://linux-hardware.org/?probe=e39e3a5527) | Nov 08, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [4abd5bf630](https://linux-hardware.org/?probe=4abd5bf630) | Nov 08, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [49de67bc9e](https://linux-hardware.org/?probe=49de67bc9e) | Nov 08, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [40aaa618d3](https://linux-hardware.org/?probe=40aaa618d3) | Nov 08, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| Alienware     | 07W25T A00                  | Desktop     | [c08c87521f](https://linux-hardware.org/?probe=c08c87521f) | Nov 08, 2021 |
| Dell          | Latitude E5470              | Notebook    | [affe63217a](https://linux-hardware.org/?probe=affe63217a) | Nov 07, 2021 |
| MSI           | X370 GAMING PLUS            | Desktop     | [f04a2bdf6e](https://linux-hardware.org/?probe=f04a2bdf6e) | Nov 07, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [ccfbf09818](https://linux-hardware.org/?probe=ccfbf09818) | Nov 07, 2021 |
| Lenovo        | ThinkPad T460 20FMS78014    | Notebook    | [415b6db3da](https://linux-hardware.org/?probe=415b6db3da) | Nov 07, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [1fb0114a05](https://linux-hardware.org/?probe=1fb0114a05) | Nov 07, 2021 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [aa6e9ba312](https://linux-hardware.org/?probe=aa6e9ba312) | Nov 06, 2021 |
| HP            | 15                          | Notebook    | [48da1734b3](https://linux-hardware.org/?probe=48da1734b3) | Nov 06, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [effc5cc35d](https://linux-hardware.org/?probe=effc5cc35d) | Nov 06, 2021 |
| HP            | 255 G1                      | Notebook    | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| Biostar       | TA990FXE                    | Desktop     | [09deaa1d44](https://linux-hardware.org/?probe=09deaa1d44) | Nov 06, 2021 |
| SIEMENS       | SIMATIC Field PG M5         | Notebook    | [8ef86a348c](https://linux-hardware.org/?probe=8ef86a348c) | Nov 06, 2021 |
| HP            | ENVY Notebook               | Notebook    | [bd814d20f6](https://linux-hardware.org/?probe=bd814d20f6) | Nov 05, 2021 |
| Lenovo        | V155-15API 81V5             | Notebook    | [b4eb5bdc7f](https://linux-hardware.org/?probe=b4eb5bdc7f) | Nov 05, 2021 |
| Fujitsu       | LIFEBOOK A555/G             | Notebook    | [4312be5851](https://linux-hardware.org/?probe=4312be5851) | Nov 05, 2021 |
| HP            | Pavilion dv4                | Notebook    | [d37c348339](https://linux-hardware.org/?probe=d37c348339) | Nov 04, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [1cc559bf54](https://linux-hardware.org/?probe=1cc559bf54) | Nov 04, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8fc8e01a40](https://linux-hardware.org/?probe=8fc8e01a40) | Nov 04, 2021 |
| Biostar       | H81MHV3                     | Desktop     | [e7d8efbecf](https://linux-hardware.org/?probe=e7d8efbecf) | Nov 04, 2021 |
| Medion        | MS-7621                     | Desktop     | [4a17d1e125](https://linux-hardware.org/?probe=4a17d1e125) | Nov 04, 2021 |
| ASUSTek       | A85XM-A                     | Desktop     | [f28dea1e67](https://linux-hardware.org/?probe=f28dea1e67) | Nov 03, 2021 |
| HP            | 3031h                       | Desktop     | [9803321690](https://linux-hardware.org/?probe=9803321690) | Nov 03, 2021 |
| Acer          | RS740DVF                    | Desktop     | [2828e1ed3e](https://linux-hardware.org/?probe=2828e1ed3e) | Nov 03, 2021 |
| HP            | 82FE 11                     | Desktop     | [948a167989](https://linux-hardware.org/?probe=948a167989) | Nov 03, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [7295833004](https://linux-hardware.org/?probe=7295833004) | Nov 03, 2021 |
| PERSONA       | MYBOOK 14                   | Notebook    | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Medion        | E2292                       | Convertible | [27672f72a8](https://linux-hardware.org/?probe=27672f72a8) | Nov 03, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [75a7ea92de](https://linux-hardware.org/?probe=75a7ea92de) | Nov 03, 2021 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [c8ce4a9635](https://linux-hardware.org/?probe=c8ce4a9635) | Nov 02, 2021 |
| Gigabyte      | H55M-S2                     | Desktop     | [a28dd690ca](https://linux-hardware.org/?probe=a28dd690ca) | Nov 02, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [cc32b13112](https://linux-hardware.org/?probe=cc32b13112) | Nov 02, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [33b288d9d0](https://linux-hardware.org/?probe=33b288d9d0) | Nov 01, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [b061e6ba62](https://linux-hardware.org/?probe=b061e6ba62) | Nov 01, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [11d4cc5eda](https://linux-hardware.org/?probe=11d4cc5eda) | Nov 01, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [7dc6485880](https://linux-hardware.org/?probe=7dc6485880) | Nov 01, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [692df23ac8](https://linux-hardware.org/?probe=692df23ac8) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [d935909503](https://linux-hardware.org/?probe=d935909503) | Nov 01, 2021 |
| Gigabyte      | PH67A-UD3-B3                | Desktop     | [91347848ea](https://linux-hardware.org/?probe=91347848ea) | Nov 01, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d0a4db1348](https://linux-hardware.org/?probe=d0a4db1348) | Nov 01, 2021 |
| Gateway       | NV42                        | Notebook    | [8f46bc202f](https://linux-hardware.org/?probe=8f46bc202f) | Nov 01, 2021 |
| ASRock        | N68-S                       | Desktop     | [eac798f714](https://linux-hardware.org/?probe=eac798f714) | Nov 01, 2021 |
| MSI           | GE70 2QE                    | Notebook    | [36acedb60b](https://linux-hardware.org/?probe=36acedb60b) | Nov 01, 2021 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [24974be67e](https://linux-hardware.org/?probe=24974be67e) | Oct 31, 2021 |
| eMachines     | E720                        | Notebook    | [82e0c7193f](https://linux-hardware.org/?probe=82e0c7193f) | Oct 31, 2021 |
| Toshiba       | IS 1412                     | Notebook    | [c0faa178a2](https://linux-hardware.org/?probe=c0faa178a2) | Oct 31, 2021 |
| MSI           | 760GM-P34                   | Desktop     | [1161af8368](https://linux-hardware.org/?probe=1161af8368) | Oct 31, 2021 |
| HP            | 3048h                       | Desktop     | [b62359fcb1](https://linux-hardware.org/?probe=b62359fcb1) | Oct 31, 2021 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [091f7c8fae](https://linux-hardware.org/?probe=091f7c8fae) | Oct 31, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [4e4e73ba37](https://linux-hardware.org/?probe=4e4e73ba37) | Oct 30, 2021 |
| Dell          | Vostro A860                 | Notebook    | [55832dd912](https://linux-hardware.org/?probe=55832dd912) | Oct 30, 2021 |
| MSI           | H87M-G43                    | Desktop     | [aecd71ac63](https://linux-hardware.org/?probe=aecd71ac63) | Oct 30, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [bb6de8b3e0](https://linux-hardware.org/?probe=bb6de8b3e0) | Oct 30, 2021 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [767eb7c6d3](https://linux-hardware.org/?probe=767eb7c6d3) | Oct 30, 2021 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4639f065c8](https://linux-hardware.org/?probe=4639f065c8) | Oct 29, 2021 |
| MSI           | P55-CD53                    | Desktop     | [d342f4e0a4](https://linux-hardware.org/?probe=d342f4e0a4) | Oct 29, 2021 |
| Medion        | WIM2180                     | Notebook    | [a1f9398a77](https://linux-hardware.org/?probe=a1f9398a77) | Oct 29, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [8272a05168](https://linux-hardware.org/?probe=8272a05168) | Oct 29, 2021 |
| Lenovo        | ThinkPad R400 7438T6U       | Notebook    | [8c2d9e608c](https://linux-hardware.org/?probe=8c2d9e608c) | Oct 28, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [7e7d21d8ae](https://linux-hardware.org/?probe=7e7d21d8ae) | Oct 28, 2021 |
| MSI           | Z97M GAMING                 | Desktop     | [3aeeebeb96](https://linux-hardware.org/?probe=3aeeebeb96) | Oct 28, 2021 |
| Dell          | Inspiron 3520               | Notebook    | [60a030aed3](https://linux-hardware.org/?probe=60a030aed3) | Oct 28, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [d1b1b0530d](https://linux-hardware.org/?probe=d1b1b0530d) | Oct 28, 2021 |
| HP            | 3048h                       | Desktop     | [8473fdedb7](https://linux-hardware.org/?probe=8473fdedb7) | Oct 27, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a377d34c0d](https://linux-hardware.org/?probe=a377d34c0d) | Oct 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [51b5e6cb3f](https://linux-hardware.org/?probe=51b5e6cb3f) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [05766074d7](https://linux-hardware.org/?probe=05766074d7) | Oct 26, 2021 |
| HP            | Laptop 14-bs0xx             | Notebook    | [c25df06e57](https://linux-hardware.org/?probe=c25df06e57) | Oct 26, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [b42bc6ee49](https://linux-hardware.org/?probe=b42bc6ee49) | Oct 25, 2021 |
| MSI           | H81M-P33                    | Desktop     | [0420edf711](https://linux-hardware.org/?probe=0420edf711) | Oct 25, 2021 |
| Lenovo        | ThinkPad W520 42844DG       | Notebook    | [90895aab86](https://linux-hardware.org/?probe=90895aab86) | Oct 25, 2021 |
| Lenovo        | ThinkPad P70 20ERS00500     | Notebook    | [6988796caf](https://linux-hardware.org/?probe=6988796caf) | Oct 25, 2021 |
| ASUSTek       | A_F_K31AN                   | Desktop     | [ebd51400e3](https://linux-hardware.org/?probe=ebd51400e3) | Oct 25, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3b40847ac4](https://linux-hardware.org/?probe=3b40847ac4) | Oct 25, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [102ed51abd](https://linux-hardware.org/?probe=102ed51abd) | Oct 25, 2021 |
| Dell          | Vostro 1400                 | Notebook    | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| ASUSTek       | P5Q3                        | Desktop     | [5dcfd80741](https://linux-hardware.org/?probe=5dcfd80741) | Oct 24, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0036c99447](https://linux-hardware.org/?probe=0036c99447) | Oct 24, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Samsung       | R530/R730/R540              | Notebook    | [cae9eeef46](https://linux-hardware.org/?probe=cae9eeef46) | Oct 24, 2021 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [3b7bf6fdeb](https://linux-hardware.org/?probe=3b7bf6fdeb) | Oct 24, 2021 |
| Acer          | FIH57                       | Desktop     | [719b6ffbe5](https://linux-hardware.org/?probe=719b6ffbe5) | Oct 24, 2021 |
| Sony          | VGN-FW270J                  | Notebook    | [dbfd29f616](https://linux-hardware.org/?probe=dbfd29f616) | Oct 24, 2021 |
| PANSHI        | B85-S1 V1.0                 | Desktop     | [963f2f28d4](https://linux-hardware.org/?probe=963f2f28d4) | Oct 24, 2021 |
| HP            | G70                         | Notebook    | [9ed49ae55e](https://linux-hardware.org/?probe=9ed49ae55e) | Oct 23, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [780e40d828](https://linux-hardware.org/?probe=780e40d828) | Oct 23, 2021 |
| HP            | ProBook 6460b               | Notebook    | [317c62df4b](https://linux-hardware.org/?probe=317c62df4b) | Oct 23, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [879759ba36](https://linux-hardware.org/?probe=879759ba36) | Oct 23, 2021 |
| HP            | 18E7                        | Desktop     | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| Acer          | Aspire E5-575T              | Notebook    | [a03fc24624](https://linux-hardware.org/?probe=a03fc24624) | Oct 23, 2021 |
| Lenovo        | ThinkPad X121e 3051RT2      | Notebook    | [29fef13a3a](https://linux-hardware.org/?probe=29fef13a3a) | Oct 22, 2021 |
| Positivo      | S14BW01                     | Notebook    | [6b146fc86e](https://linux-hardware.org/?probe=6b146fc86e) | Oct 22, 2021 |
| MSI           | A75A-G35                    | Desktop     | [7223bfa184](https://linux-hardware.org/?probe=7223bfa184) | Oct 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [19f7ba4a63](https://linux-hardware.org/?probe=19f7ba4a63) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [703d0f2090](https://linux-hardware.org/?probe=703d0f2090) | Oct 21, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| ASRock        | E350M1                      | Desktop     | [84353af140](https://linux-hardware.org/?probe=84353af140) | Oct 21, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [63f68846bb](https://linux-hardware.org/?probe=63f68846bb) | Oct 21, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [74a6f72f79](https://linux-hardware.org/?probe=74a6f72f79) | Oct 21, 2021 |
| Dell          | Latitude E6500              | Notebook    | [84217e1781](https://linux-hardware.org/?probe=84217e1781) | Oct 21, 2021 |
| ASUSTek       | M51Vr                       | Notebook    | [843c7a8519](https://linux-hardware.org/?probe=843c7a8519) | Oct 20, 2021 |
| Dell          | 0TP412                      | Desktop     | [61643a7463](https://linux-hardware.org/?probe=61643a7463) | Oct 20, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a79f5ef1cf](https://linux-hardware.org/?probe=a79f5ef1cf) | Oct 20, 2021 |
| MSI           | H97M-G43                    | Desktop     | [48617be8f2](https://linux-hardware.org/?probe=48617be8f2) | Oct 20, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [96ecc9f1bd](https://linux-hardware.org/?probe=96ecc9f1bd) | Oct 20, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [de600dc6cc](https://linux-hardware.org/?probe=de600dc6cc) | Oct 20, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.2/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 4405      | 95.28%  |
| 5.11.12-desktop-1omv4002       | 190       | 4.11%   |
| 5.11.0-desktop-clang-1omv4002  | 10        | 0.22%   |
| 5.10.13-desktop-1omv4002       | 4         | 0.09%   |
| 5.9.12-desktop-1omv4002        | 2         | 0.04%   |
| 5.8.13-desktop-clang-1omv4002  | 1         | 0.02%   |
| 5.8.13-desktop-1omv4002        | 1         | 0.02%   |
| 5.11.1-desktop-74.1.1bomv4002  | 1         | 0.02%   |
| 5.11.0-desktop-1omv4002        | 1         | 0.02%   |
| 5.11.0-desktop-0.rc4.1omv4002  | 1         | 0.02%   |
| 5.10.9-desktop-1omv4002        | 1         | 0.02%   |
| 5.10.7-desktop-1omv4002        | 1         | 0.02%   |
| 5.10.3-desktop-2omv4002        | 1         | 0.02%   |
| 5.10.2-desktop-clang-1omv4002  | 1         | 0.02%   |
| 5.10.15-desktop-1omv4002       | 1         | 0.02%   |
| 5.10.12-desktop-clang-1omv4002 | 1         | 0.02%   |
| Unknown                        | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.14 | 4405      | 95.28%  |
| 5.11.12 | 190       | 4.11%   |
| 5.11.0  | 12        | 0.26%   |
| 5.10.13 | 4         | 0.09%   |
| 5.9.12  | 2         | 0.04%   |
| 5.8.13  | 2         | 0.04%   |
| 5.11.1  | 1         | 0.02%   |
| 5.10.9  | 1         | 0.02%   |
| 5.10.7  | 1         | 0.02%   |
| 5.10.3  | 1         | 0.02%   |
| 5.10.2  | 1         | 0.02%   |
| 5.10.15 | 1         | 0.02%   |
| 5.10.12 | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4415      | 95.5%   |
| 5.11    | 203       | 4.39%   |
| 5.9     | 2         | 0.04%   |
| 5.8     | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4576      | 99.98%  |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 4570      | 99.83%  |
| LXQt     | 3         | 0.07%   |
| Cinnamon | 2         | 0.04%   |
| KDE      | 1         | 0.02%   |
| GNOME    | 1         | 0.02%   |
| Unknown  | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4558      | 99.58%  |
| Wayland | 18        | 0.39%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 4576      | 99.98%  |
| Unknown | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2316      | 50.4%   |
| de_DE   | 374       | 8.14%   |
| ru_RU   | 306       | 6.66%   |
| fr_FR   | 289       | 6.29%   |
| pl_PL   | 225       | 4.9%    |
| pt_BR   | 206       | 4.48%   |
| es_ES   | 131       | 2.85%   |
| it_IT   | 126       | 2.74%   |
| cs_CZ   | 93        | 2.02%   |
| en_GB   | 78        | 1.7%    |
| es_MX   | 41        | 0.89%   |
| es_AR   | 41        | 0.89%   |
| hu_HU   | 36        | 0.78%   |
| de_AT   | 27        | 0.59%   |
| en_AU   | 24        | 0.52%   |
| nl_NL   | 21        | 0.46%   |
| ru_UA   | 18        | 0.39%   |
| fr_BE   | 17        | 0.37%   |
| fr_CA   | 16        | 0.35%   |
| es_CO   | 14        | 0.3%    |
| da_DK   | 14        | 0.3%    |
| ro_RO   | 13        | 0.28%   |
| es_CL   | 12        | 0.26%   |
| en_CA   | 11        | 0.24%   |
| de_CH   | 11        | 0.24%   |
| pt_PT   | 10        | 0.22%   |
| nl_BE   | 10        | 0.22%   |
| en_IN   | 9         | 0.2%    |
| it_CH   | 7         | 0.15%   |
| fr_CH   | 7         | 0.15%   |
| es_PE   | 7         | 0.15%   |
| en_HK   | 7         | 0.15%   |
| nb_NO   | 6         | 0.13%   |
| es_VE   | 6         | 0.13%   |
| Unknown | 6         | 0.13%   |
| uk_UA   | 5         | 0.11%   |
| en_ZA   | 5         | 0.11%   |
| en_IL   | 5         | 0.11%   |
| es_SV   | 4         | 0.09%   |
| es_EC   | 4         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2775      | 60.58%  |
| EFI  | 1806      | 39.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Overlay | 3672      | 79.5%   |
| Ext4    | 893       | 19.33%  |
| Btrfs   | 28        | 0.61%   |
| F2fs    | 7         | 0.15%   |
| Ext3    | 6         | 0.13%   |
| Ext2    | 6         | 0.13%   |
| Xfs     | 4         | 0.09%   |
| Jfs     | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2582      | 56.25%  |
| MBR     | 1998      | 43.53%  |
| Unknown | 10        | 0.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2625      | 57.05%  |
| No        | 1976      | 42.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2389      | 52.12%  |
| Yes       | 2195      | 47.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 853       | 18.64%  |
| Hewlett-Packard     | 586       | 12.8%   |
| Lenovo              | 511       | 11.16%  |
| Dell                | 508       | 11.1%   |
| Gigabyte Technology | 401       | 8.76%   |
| Acer                | 314       | 6.86%   |
| MSI                 | 270       | 5.9%    |
| ASRock              | 206       | 4.5%    |
| Toshiba             | 117       | 2.56%   |
| Intel               | 80        | 1.75%   |
| Sony                | 67        | 1.46%   |
| Apple               | 59        | 1.29%   |
| Samsung Electronics | 56        | 1.22%   |
| Medion              | 56        | 1.22%   |
| Fujitsu             | 50        | 1.09%   |
| Pegatron            | 32        | 0.7%    |
| Biostar             | 29        | 0.63%   |
| Positivo            | 28        | 0.61%   |
| Foxconn             | 27        | 0.59%   |
| Unknown             | 27        | 0.59%   |
| Packard Bell        | 26        | 0.57%   |
| ECS                 | 18        | 0.39%   |
| eMachines           | 15        | 0.33%   |
| Philco              | 13        | 0.28%   |
| Notebook            | 13        | 0.28%   |
| HUAWEI              | 13        | 0.28%   |
| Fujitsu Siemens     | 11        | 0.24%   |
| LG Electronics      | 8         | 0.17%   |
| Gateway             | 8         | 0.17%   |
| Chuwi               | 8         | 0.17%   |
| Microsoft           | 7         | 0.15%   |
| Supermicro          | 6         | 0.13%   |
| Shuttle             | 6         | 0.13%   |
| PCWare              | 6         | 0.13%   |
| Clevo               | 6         | 0.13%   |
| ZOTAC               | 5         | 0.11%   |
| TUXEDO              | 5         | 0.11%   |
| Timi                | 5         | 0.11%   |
| System76            | 5         | 0.11%   |
| Itautec             | 5         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUS All Series             | 53        | 1.16%   |
| ASUS UX31E                  | 44        | 0.96%   |
| Unknown                     | 42        | 0.92%   |
| Dell Inspiron 3451          | 32        | 0.7%    |
| HP Notebook                 | 24        | 0.52%   |
| Dell OptiPlex 780           | 24        | 0.52%   |
| Dell OptiPlex 7010          | 16        | 0.35%   |
| Medion E2292                | 13        | 0.28%   |
| HP Pavilion g6              | 13        | 0.28%   |
| ASUS PRIME A320M-K          | 13        | 0.28%   |
| Gigabyte 970A-DS3P          | 12        | 0.26%   |
| MSI MS-7817                 | 11        | 0.24%   |
| Dell Latitude E6430         | 11        | 0.24%   |
| HP Pavilion dv6             | 10        | 0.22%   |
| Gigabyte B450M DS3H         | 10        | 0.22%   |
| Gigabyte A320M-S2H          | 10        | 0.22%   |
| Dell Latitude D630          | 10        | 0.22%   |
| ASUS PRIME B450M-A          | 10        | 0.22%   |
| HP EliteDesk 800 G1 SFF     | 9         | 0.2%    |
| HP Compaq Pro 6300 SFF      | 9         | 0.2%    |
| Dell OptiPlex 9020          | 9         | 0.2%    |
| Dell OptiPlex 3020          | 9         | 0.2%    |
| Toshiba Satellite A300      | 8         | 0.17%   |
| MSI MS-7641                 | 8         | 0.17%   |
| Intel H61                   | 8         | 0.17%   |
| HP Compaq 8200 Elite SFF PC | 8         | 0.17%   |
| Gigabyte G31M-ES2L          | 8         | 0.17%   |
| Gigabyte B75M-D3H           | 8         | 0.17%   |
| MSI MS-7C52                 | 7         | 0.15%   |
| MSI MS-7721                 | 7         | 0.15%   |
| HP Pavilion 15              | 7         | 0.15%   |
| HP EliteBook 8440p          | 7         | 0.15%   |
| Gigabyte H61M-DS2           | 7         | 0.15%   |
| Dell OptiPlex 790           | 7         | 0.15%   |
| Dell Latitude E6420         | 7         | 0.15%   |
| Dell Latitude E6410         | 7         | 0.15%   |
| Dell Inspiron 15-3567       | 7         | 0.15%   |
| ASUS M5A97 R2.0             | 7         | 0.15%   |
| ASRock G31M-S               | 7         | 0.15%   |
| MSI MS-7B86                 | 6         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 233       | 5.09%   |
| Lenovo ThinkPad       | 159       | 3.47%   |
| Dell Inspiron         | 145       | 3.17%   |
| Dell Latitude         | 136       | 2.97%   |
| Dell OptiPlex         | 134       | 2.93%   |
| Lenovo IdeaPad        | 130       | 2.84%   |
| HP Compaq             | 103       | 2.25%   |
| HP Pavilion           | 97        | 2.12%   |
| Toshiba Satellite     | 96        | 2.1%    |
| ASUS PRIME            | 89        | 1.94%   |
| HP Laptop             | 56        | 1.22%   |
| Lenovo ThinkCentre    | 54        | 1.18%   |
| ASUS All              | 53        | 1.16%   |
| HP EliteBook          | 51        | 1.11%   |
| ASUS UX31E            | 44        | 0.96%   |
| Unknown               | 42        | 0.92%   |
| HP ProBook            | 38        | 0.83%   |
| ASUS ROG              | 37        | 0.81%   |
| Dell Vostro           | 29        | 0.63%   |
| HP EliteDesk          | 27        | 0.59%   |
| ASUS VivoBook         | 27        | 0.59%   |
| ASUS M5A78L-M         | 27        | 0.59%   |
| Fujitsu ESPRIMO       | 25        | 0.55%   |
| ASUS TUF              | 25        | 0.55%   |
| HP Notebook           | 24        | 0.52%   |
| Lenovo IdeaCentre     | 23        | 0.5%    |
| Dell Precision        | 20        | 0.44%   |
| ASUS P8Z77-V          | 20        | 0.44%   |
| ASUS P8H61-M          | 20        | 0.44%   |
| HP ProDesk            | 19        | 0.42%   |
| Gigabyte B450M        | 19        | 0.42%   |
| Fujitsu LIFEBOOK      | 19        | 0.42%   |
| Acer Extensa          | 19        | 0.42%   |
| Packard Bell EasyNote | 17        | 0.37%   |
| Acer TravelMate       | 17        | 0.37%   |
| HP ENVY               | 14        | 0.31%   |
| Gigabyte B450         | 14        | 0.31%   |
| Medion E2292          | 13        | 0.28%   |
| Gigabyte A320M-S2H    | 13        | 0.28%   |
| Gigabyte X570         | 12        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 506       | 11.06%  |
| 2011    | 489       | 10.68%  |
| 2013    | 398       | 8.7%    |
| 2014    | 364       | 7.95%   |
| 2010    | 356       | 7.78%   |
| 2018    | 311       | 6.79%   |
| 2019    | 308       | 6.73%   |
| 2008    | 297       | 6.49%   |
| 2017    | 275       | 6.01%   |
| 2009    | 274       | 5.99%   |
| 2015    | 252       | 5.51%   |
| 2016    | 225       | 4.92%   |
| 2020    | 211       | 4.61%   |
| 2007    | 167       | 3.65%   |
| 2021    | 61        | 1.33%   |
| 2006    | 60        | 1.31%   |
| 2005    | 15        | 0.33%   |
| 2004    | 6         | 0.13%   |
| Unknown | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 2233      | 48.79%  |
| Notebook    | 2168      | 47.37%  |
| All in one  | 71        | 1.55%   |
| Mini pc     | 45        | 0.98%   |
| Convertible | 41        | 0.9%    |
| Tablet      | 13        | 0.28%   |
| Server      | 6         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4577      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4574      | 99.93%  |
| Yes  | 3         | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1491      | 32.53%  |
| 4.01-8.0        | 1135      | 24.77%  |
| 8.01-16.0       | 858       | 18.72%  |
| 16.01-24.0      | 575       | 12.55%  |
| 1.01-2.0        | 217       | 4.73%   |
| 32.01-64.0      | 171       | 3.73%   |
| 2.01-3.0        | 68        | 1.48%   |
| 24.01-32.0      | 36        | 0.79%   |
| 64.01-256.0     | 21        | 0.46%   |
| 0.51-1.0        | 9         | 0.2%    |
| More than 256.0 | 1         | 0.02%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 3576      | 77.57%  |
| 0.51-1.0  | 629       | 13.64%  |
| 2.01-3.0  | 264       | 5.73%   |
| 0.01-0.5  | 114       | 2.47%   |
| 3.01-4.0  | 15        | 0.33%   |
| 4.01-8.0  | 9         | 0.2%    |
| 8.01-16.0 | 2         | 0.04%   |
| Unknown   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2839      | 61.95%  |
| 2      | 1062      | 23.17%  |
| 3      | 347       | 7.57%   |
| 4      | 157       | 3.43%   |
| 0      | 70        | 1.53%   |
| 5      | 60        | 1.31%   |
| 6      | 21        | 0.46%   |
| 7      | 13        | 0.28%   |
| 8      | 11        | 0.24%   |
| 9      | 2         | 0.04%   |
| 18     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2841      | 62.02%  |
| No        | 1740      | 37.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4323      | 94.45%  |
| No        | 254       | 5.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3016      | 65.88%  |
| No        | 1562      | 34.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2549      | 55.68%  |
| Yes       | 2029      | 44.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 553       | 12.08%  |
| USA          | 450       | 9.83%   |
| Russia       | 395       | 8.63%   |
| France       | 353       | 7.71%   |
| Brazil       | 335       | 7.32%   |
| Poland       | 316       | 6.9%    |
| Italy        | 212       | 4.63%   |
| Spain        | 181       | 3.95%   |
| UK           | 131       | 2.86%   |
| Czechia      | 115       | 2.51%   |
| Canada       | 115       | 2.51%   |
| Mexico       | 89        | 1.94%   |
| Ukraine      | 73        | 1.59%   |
| Hungary      | 58        | 1.27%   |
| India        | 56        | 1.22%   |
| Australia    | 56        | 1.22%   |
| Argentina    | 56        | 1.22%   |
| Netherlands  | 54        | 1.18%   |
| Romania      | 44        | 0.96%   |
| Belgium      | 43        | 0.94%   |
| Austria      | 40        | 0.87%   |
| Sweden       | 39        | 0.85%   |
| Portugal     | 36        | 0.79%   |
| Greece       | 36        | 0.79%   |
| Japan        | 35        | 0.76%   |
| Finland      | 33        | 0.72%   |
| Indonesia    | 32        | 0.7%    |
| Switzerland  | 30        | 0.66%   |
| Bulgaria     | 29        | 0.63%   |
| Slovakia     | 26        | 0.57%   |
| Serbia       | 25        | 0.55%   |
| Denmark      | 25        | 0.55%   |
| Belarus      | 24        | 0.52%   |
| Norway       | 20        | 0.44%   |
| China        | 20        | 0.44%   |
| Chile        | 19        | 0.42%   |
| South Africa | 17        | 0.37%   |
| Colombia     | 17        | 0.37%   |
| Thailand     | 16        | 0.35%   |
| Israel       | 16        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 65        | 1.41%   |
| Prague           | 59        | 1.28%   |
| Warsaw           | 47        | 1.02%   |
| Paris            | 39        | 0.85%   |
| Krakow           | 39        | 0.85%   |
| Berlin           | 38        | 0.83%   |
| St Petersburg    | 35        | 0.76%   |
| Sao Paulo        | 35        | 0.76%   |
| Rome             | 27        | 0.59%   |
| Milan            | 27        | 0.59%   |
| Mexico City      | 27        | 0.59%   |
| Rio de Janeiro   | 26        | 0.56%   |
| Munich           | 21        | 0.46%   |
| Stuttgart        | 18        | 0.39%   |
| Helsinki         | 18        | 0.39%   |
| Porto Alegre     | 17        | 0.37%   |
| Krasnodar        | 17        | 0.37%   |
| Yekaterinburg    | 16        | 0.35%   |
| Vienna           | 16        | 0.35%   |
| Madrid           | 16        | 0.35%   |
| Budapest         | 15        | 0.33%   |
| Wroclaw          | 14        | 0.3%    |
| Melbourne        | 14        | 0.3%    |
| Hamburg          | 14        | 0.3%    |
| Wettringen       | 13        | 0.28%   |
| Poznan           | 13        | 0.28%   |
| Nuremberg        | 13        | 0.28%   |
| Sydney           | 12        | 0.26%   |
| Novosibirsk      | 12        | 0.26%   |
| Buenos Aires     | 12        | 0.26%   |
| Barcelona        | 12        | 0.26%   |
| Athens           | 12        | 0.26%   |
| Queens           | 11        | 0.24%   |
| Mannheim         | 11        | 0.24%   |
| Lisbon           | 11        | 0.24%   |
| Cologne          | 11        | 0.24%   |
| Nizhniy Novgorod | 10        | 0.22%   |
| Montreal         | 10        | 0.22%   |
| Minsk            | 10        | 0.22%   |
| Kyiv             | 10        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1292      | 1543   | 20.38%  |
| Seagate             | 1238      | 1448   | 19.52%  |
| Samsung Electronics | 718       | 868    | 11.32%  |
| Toshiba             | 502       | 537    | 7.92%   |
| Kingston            | 371       | 403    | 5.85%   |
| Hitachi             | 298       | 313    | 4.7%    |
| SanDisk             | 243       | 254    | 3.83%   |
| Crucial             | 226       | 259    | 3.56%   |
| Unknown             | 175       | 196    | 2.76%   |
| A-DATA Technology   | 115       | 123    | 1.81%   |
| HGST                | 103       | 108    | 1.62%   |
| Intel               | 90        | 102    | 1.42%   |
| China               | 66        | 70     | 1.04%   |
| SK hynix            | 59        | 60     | 0.93%   |
| GOODRAM             | 53        | 59     | 0.84%   |
| Intenso             | 47        | 52     | 0.74%   |
| Maxtor              | 44        | 48     | 0.69%   |
| Patriot             | 41        | 44     | 0.65%   |
| PNY                 | 40        | 41     | 0.63%   |
| SPCC                | 33        | 33     | 0.52%   |
| Fujitsu             | 32        | 32     | 0.5%    |
| OCZ                 | 29        | 30     | 0.46%   |
| Micron Technology   | 28        | 29     | 0.44%   |
| Apple               | 28        | 33     | 0.44%   |
| Apacer              | 27        | 29     | 0.43%   |
| JMicron Technology  | 24        | 24     | 0.38%   |
| Transcend           | 23        | 23     | 0.36%   |
| Phison              | 21        | 23     | 0.33%   |
| Hewlett-Packard     | 19        | 21     | 0.3%    |
| Corsair             | 19        | 20     | 0.3%    |
| Plextor             | 16        | 18     | 0.25%   |
| LITEON              | 13        | 13     | 0.21%   |
| LITEONIT            | 11        | 12     | 0.17%   |
| KingSpec            | 11        | 11     | 0.17%   |
| Team                | 10        | 11     | 0.16%   |
| KingDian            | 8         | 8      | 0.13%   |
| SABRENT             | 7         | 9      | 0.11%   |
| Netac               | 7         | 7      | 0.11%   |
| Gigabyte Technology | 7         | 7      | 0.11%   |
| Colorful            | 7         | 7      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 82        | 1.19%   |
| Seagate ST500DM002-1BD142 500GB     | 81        | 1.17%   |
| Kingston SA400S37240G 240GB SSD     | 79        | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB      | 62        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 55        | 0.8%    |
| Toshiba DT01ACA100 1TB              | 54        | 0.78%   |
| Toshiba MQ01ABF050 500GB            | 49        | 0.71%   |
| Kingston SA400S37120G 120GB SSD     | 47        | 0.68%   |
| SanDisk SSD U100 256GB              | 44        | 0.64%   |
| Samsung SSD 860 EVO 500GB           | 43        | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB      | 42        | 0.61%   |
| Kingston SV300S37A120G 120GB SSD    | 41        | 0.59%   |
| Toshiba DT01ACA050 500GB            | 40        | 0.58%   |
| Seagate ST3500418AS 500GB           | 40        | 0.58%   |
| Unknown SD/MMC/MS PRO 64GB          | 39        | 0.57%   |
| Toshiba MQ01ABD100 1TB              | 38        | 0.55%   |
| Kingston SA400S37480G 480GB SSD     | 37        | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB            | 36        | 0.52%   |
| Seagate ST9500325AS 500GB           | 33        | 0.48%   |
| Samsung SSD 850 EVO 250GB           | 32        | 0.46%   |
| Crucial CT240BX500SSD1 240GB        | 32        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 31        | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB      | 30        | 0.43%   |
| Samsung SSD 850 EVO 500GB           | 30        | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB            | 28        | 0.41%   |
| Toshiba HDWD110 1TB                 | 28        | 0.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 28        | 0.41%   |
| Samsung SSD 860 EVO 250GB           | 28        | 0.41%   |
| Crucial CT500MX500SSD1 500GB        | 28        | 0.41%   |
| HGST HTS721010A9E630 1TB            | 27        | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 26        | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB      | 26        | 0.38%   |
| Toshiba MQ04ABF100 1TB              | 24        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB      | 24        | 0.35%   |
| Seagate ST3500413AS 500GB           | 23        | 0.33%   |
| Toshiba DT01ACA200 2TB              | 21        | 0.3%    |
| Seagate ST1000DM003-1SB102 1TB      | 21        | 0.3%    |
| Seagate ST500LT012-9WS142 500GB     | 20        | 0.29%   |
| WDC WD10EZEX-00BN5A0 1TB            | 19        | 0.28%   |
| Seagate ST3160815AS 160GB           | 19        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1228      | 1434   | 34.65%  |
| WDC                 | 1101      | 1297   | 31.07%  |
| Toshiba             | 444       | 473    | 12.53%  |
| Hitachi             | 298       | 313    | 8.41%   |
| Samsung Electronics | 200       | 221    | 5.64%   |
| HGST                | 103       | 108    | 2.91%   |
| Maxtor              | 43        | 47     | 1.21%   |
| Unknown             | 40        | 40     | 1.13%   |
| Fujitsu             | 32        | 32     | 0.9%    |
| Apple               | 14        | 14     | 0.4%    |
| Hewlett-Packard     | 5         | 5      | 0.14%   |
| ASMT                | 5         | 5      | 0.14%   |
| WD MediaMax         | 4         | 4      | 0.11%   |
| Quantum             | 3         | 3      | 0.08%   |
| IBM/Hitachi         | 3         | 3      | 0.08%   |
| SABRENT             | 2         | 3      | 0.06%   |
| MDT                 | 2         | 2      | 0.06%   |
| ExcelStor           | 2         | 2      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| USB3.0              | 1         | 1      | 0.03%   |
| USB                 | 1         | 1      | 0.03%   |
| TPH00800640GB       | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| IB                  | 1         | 2      | 0.03%   |
| HPE                 | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| FC-1307             | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| ASMT106x            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 395       | 459    | 17.92%  |
| Kingston            | 330       | 357    | 14.97%  |
| SanDisk             | 232       | 241    | 10.53%  |
| Crucial             | 205       | 235    | 9.3%    |
| WDC                 | 150       | 156    | 6.81%   |
| A-DATA Technology   | 106       | 113    | 4.81%   |
| China               | 65        | 69     | 2.95%   |
| GOODRAM             | 52        | 58     | 2.36%   |
| Intel               | 47        | 51     | 2.13%   |
| Intenso             | 45        | 50     | 2.04%   |
| Toshiba             | 43        | 45     | 1.95%   |
| PNY                 | 38        | 39     | 1.72%   |
| Patriot             | 38        | 41     | 1.72%   |
| OCZ                 | 29        | 30     | 1.32%   |
| SK hynix            | 28        | 29     | 1.27%   |
| SPCC                | 27        | 27     | 1.23%   |
| Apacer              | 25        | 27     | 1.13%   |
| Unknown             | 22        | 23     | 1%      |
| Transcend           | 22        | 22     | 1%      |
| Micron Technology   | 22        | 23     | 1%      |
| JMicron Technology  | 15        | 15     | 0.68%   |
| Plextor             | 14        | 16     | 0.64%   |
| Corsair             | 12        | 13     | 0.54%   |
| LITEONIT            | 11        | 12     | 0.5%    |
| LITEON              | 11        | 11     | 0.5%    |
| KingSpec            | 11        | 11     | 0.5%    |
| Hewlett-Packard     | 11        | 11     | 0.5%    |
| Apple               | 11        | 11     | 0.5%    |
| Team                | 9         | 10     | 0.41%   |
| KingDian            | 8         | 8      | 0.36%   |
| Netac               | 7         | 7      | 0.32%   |
| Colorful            | 7         | 7      | 0.32%   |
| Seagate             | 6         | 6      | 0.27%   |
| Unknown             | 6         | 6      | 0.27%   |
| Verbatim            | 5         | 5      | 0.23%   |
| Teclast             | 5         | 5      | 0.23%   |
| Gigabyte Technology | 5         | 5      | 0.23%   |
| XrayDisk            | 4         | 4      | 0.18%   |
| Leven               | 4         | 4      | 0.18%   |
| KingFast            | 4         | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3008      | 4022   | 53.76%  |
| SSD     | 1935      | 2384   | 34.58%  |
| NVMe    | 489       | 583    | 8.74%   |
| MMC     | 118       | 128    | 2.11%   |
| Unknown | 45        | 57     | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4192      | 6198   | 83.56%  |
| NVMe | 481       | 570    | 9.59%   |
| SAS  | 226       | 278    | 4.5%    |
| MMC  | 118       | 128    | 2.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3351      | 4309   | 65.54%  |
| 0.51-1.0   | 1282      | 1513   | 25.07%  |
| 1.01-2.0   | 289       | 347    | 5.65%   |
| 3.01-4.0   | 77        | 99     | 1.51%   |
| 2.01-3.0   | 63        | 81     | 1.23%   |
| 4.01-10.0  | 45        | 51     | 0.88%   |
| 10.01-20.0 | 6         | 6      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2298      | 49.73%  |
| Unknown        | 639       | 13.83%  |
| 101-250        | 603       | 13.05%  |
| 251-500        | 431       | 9.33%   |
| 501-1000       | 204       | 4.41%   |
| 51-100         | 200       | 4.33%   |
| 21-50          | 155       | 3.35%   |
| 1001-2000      | 60        | 1.3%    |
| 2001-3000      | 20        | 0.43%   |
| More than 3000 | 11        | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3609      | 78.17%  |
| Unknown        | 639       | 13.84%  |
| 21-50          | 97        | 2.1%    |
| 101-250        | 87        | 1.88%   |
| 51-100         | 70        | 1.52%   |
| 251-500        | 57        | 1.23%   |
| 501-1000       | 34        | 0.74%   |
| 1001-2000      | 16        | 0.35%   |
| More than 3000 | 4         | 0.09%   |
| 2001-3000      | 3         | 0.06%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB             | 44        | 44     | 3.03%   |
| Seagate ST500DM002-1BD142 500GB    | 33        | 33     | 2.28%   |
| Seagate ST9500325AS 500GB          | 28        | 30     | 1.93%   |
| Seagate ST500LT012-1DG142 500GB    | 23        | 23     | 1.59%   |
| Seagate ST3500418AS 500GB          | 20        | 21     | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 19        | 19     | 1.31%   |
| Seagate ST500LT012-9WS142 500GB    | 17        | 18     | 1.17%   |
| Toshiba MQ01ABF050 500GB           | 14        | 14     | 0.97%   |
| Toshiba DT01ACA100 1TB             | 11        | 11     | 0.76%   |
| Seagate ST9320325AS 320GB          | 11        | 11     | 0.76%   |
| Hitachi HTS545050A7E380 500GB      | 11        | 11     | 0.76%   |
| Kingston SV300S37A120G 120GB SSD   | 10        | 10     | 0.69%   |
| HGST HTS545050A7E680 500GB         | 10        | 10     | 0.69%   |
| Toshiba DT01ACA050 500GB           | 9         | 9      | 0.62%   |
| Hitachi HTS547550A9E384 500GB      | 9         | 10     | 0.62%   |
| WDC WD5000AAKX-003CA0 500GB        | 8         | 8      | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB           | 8         | 8      | 0.55%   |
| Seagate ST500LM021-1KJ152 500GB    | 8         | 8      | 0.55%   |
| HGST HTS541010A9E680 1TB           | 8         | 8      | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB        | 7         | 8      | 0.48%   |
| Toshiba MQ01ABD100 1TB             | 7         | 7      | 0.48%   |
| Toshiba MQ01ABD050 500GB           | 7         | 7      | 0.48%   |
| Toshiba MK3265GSX 320GB            | 7         | 7      | 0.48%   |
| Seagate ST9500420AS 500GB          | 7         | 7      | 0.48%   |
| Seagate ST31000524AS 1TB           | 7         | 7      | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB     | 7         | 7      | 0.48%   |
| Samsung Electronics HD103SJ 1TB    | 7         | 8      | 0.48%   |
| Hitachi HTS545025B9A300 250GB      | 7         | 7      | 0.48%   |
| HGST HTS721010A9E630 1TB           | 7         | 7      | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 6         | 6      | 0.41%   |
| WDC WD10EADS-00L5B1 1TB            | 6         | 6      | 0.41%   |
| Seagate ST3250310AS 250GB          | 6         | 6      | 0.41%   |
| Seagate ST31000528AS 1TB           | 6         | 6      | 0.41%   |
| Samsung Electronics HM641JI 640GB  | 6         | 6      | 0.41%   |
| Samsung Electronics HD161HJ 160GB  | 6         | 6      | 0.41%   |
| Hitachi HTS547564A9E384 640GB      | 6         | 6      | 0.41%   |
| HGST HTS545050A7E380 500GB         | 6         | 6      | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 5         | 5      | 0.34%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 5         | 6      | 0.34%   |
| WDC WD3200BEVT-60A23T0 320GB       | 5         | 5      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 400       | 426    | 28.51%  |
| WDC                 | 364       | 400    | 25.94%  |
| Hitachi             | 141       | 148    | 10.05%  |
| Toshiba             | 122       | 124    | 8.7%    |
| Samsung Electronics | 117       | 124    | 8.34%   |
| SanDisk             | 62        | 62     | 4.42%   |
| HGST                | 44        | 44     | 3.14%   |
| Kingston            | 34        | 36     | 2.42%   |
| Maxtor              | 25        | 25     | 1.78%   |
| Intel               | 12        | 12     | 0.86%   |
| Fujitsu             | 11        | 11     | 0.78%   |
| Crucial             | 11        | 11     | 0.78%   |
| China               | 7         | 7      | 0.5%    |
| A-DATA Technology   | 7         | 7      | 0.5%    |
| SK hynix            | 6         | 6      | 0.43%   |
| OCZ                 | 5         | 5      | 0.36%   |
| Intenso             | 3         | 3      | 0.21%   |
| Colorful            | 2         | 2      | 0.14%   |
| Apacer              | 2         | 3      | 0.14%   |
| XPG                 | 1         | 1      | 0.07%   |
| WD MediaMax         | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |
| Transcend           | 1         | 1      | 0.07%   |
| Team                | 1         | 1      | 0.07%   |
| SPCC                | 1         | 1      | 0.07%   |
| Quantum             | 1         | 1      | 0.07%   |
| QIANGHE             | 1         | 1      | 0.07%   |
| Plextor             | 1         | 1      | 0.07%   |
| Platinet            | 1         | 1      | 0.07%   |
| Netac               | 1         | 1      | 0.07%   |
| Neo Forza           | 1         | 1      | 0.07%   |
| Micron Technology   | 1         | 1      | 0.07%   |
| LITEONIT            | 1         | 1      | 0.07%   |
| LITEON              | 1         | 1      | 0.07%   |
| KingSpec            | 1         | 1      | 0.07%   |
| KingDian            | 1         | 1      | 0.07%   |
| IBM/Hitachi         | 1         | 1      | 0.07%   |
| IB                  | 1         | 1      | 0.07%   |
| Hewlett-Packard     | 1         | 1      | 0.07%   |
| Goodram             | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 400       | 426    | 33.33%  |
| WDC                 | 350       | 385    | 29.17%  |
| Hitachi             | 141       | 148    | 11.75%  |
| Toshiba             | 122       | 124    | 10.17%  |
| Samsung Electronics | 99        | 106    | 8.25%   |
| HGST                | 44        | 44     | 3.67%   |
| Maxtor              | 25        | 25     | 2.08%   |
| Fujitsu             | 11        | 11     | 0.92%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| Quantum             | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| IB                  | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 1      | 0.08%   |
| China               | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| Apple               | 1         | 1      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1116      | 1277   | 84.55%  |
| SSD  | 196       | 199    | 14.85%  |
| NVMe | 8         | 8      | 0.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 6.06%   |
| WDC WD20EZRX-00D8PB0 2TB              | 2         | 2      | 6.06%   |
| Seagate ST3500418AS 500GB             | 2         | 3      | 6.06%   |
| Seagate ST3250318AS 250GB             | 2         | 2      | 6.06%   |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 6.06%   |
| WDC WD800JD-75MSA3 80GB               | 1         | 1      | 3.03%   |
| WDC WD800JD-00LSA0 80GB               | 1         | 1      | 3.03%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 3.03%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 3.03%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 3.03%   |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 3.03%   |
| WDC WD10EALX-759BA1 1TB               | 1         | 1      | 3.03%   |
| TPH00800640GB 640GB                   | 1         | 1      | 3.03%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 3.03%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 3.03%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 3.03%   |
| Seagate STM3250318AS 250GB            | 1         | 1      | 3.03%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 3.03%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 3.03%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 3.03%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 3.03%   |
| Samsung Electronics HD501LJ 500GB     | 1         | 1      | 3.03%   |
| Maxtor STM3500320AS 500GB             | 1         | 1      | 3.03%   |
| Kingston SMS200S360G 64GB SSD         | 1         | 1      | 3.03%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 3.03%   |
| Hitachi HDS721010CLA332 1TB           | 1         | 1      | 3.03%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 3.03%   |
| Apple HDD HTS541010A9E662 1TB         | 1         | 1      | 3.03%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 33.33%  |
| Seagate             | 7         | 8      | 21.21%  |
| Samsung Electronics | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Hitachi             | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| TPH00800640GB       | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Maxtor              | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3366      | 4985   | 64.71%  |
| Malfunc  | 1295      | 1484   | 24.89%  |
| Detected | 508       | 671    | 9.77%   |
| Failed   | 33        | 34     | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3328      | 63.49%  |
| AMD                              | 1020      | 19.46%  |
| Samsung Electronics              | 174       | 3.32%   |
| Nvidia                           | 118       | 2.25%   |
| JMicron Technology               | 85        | 1.62%   |
| SanDisk                          | 82        | 1.56%   |
| Marvell Technology Group         | 75        | 1.43%   |
| ASMedia Technology               | 71        | 1.35%   |
| Kingston Technology Company      | 46        | 0.88%   |
| Phison Electronics               | 44        | 0.84%   |
| VIA Technologies                 | 33        | 0.63%   |
| SK hynix                         | 26        | 0.5%    |
| Micron/Crucial Technology        | 22        | 0.42%   |
| Toshiba America Info Systems     | 18        | 0.34%   |
| Silicon Motion                   | 15        | 0.29%   |
| Silicon Image                    | 10        | 0.19%   |
| Micron Technology                | 8         | 0.15%   |
| ADATA Technology                 | 8         | 0.15%   |
| KIOXIA                           | 7         | 0.13%   |
| Union Memory (Shenzhen)          | 6         | 0.11%   |
| LSI Logic / Symbios Logic        | 6         | 0.11%   |
| Realtek Semiconductor            | 5         | 0.1%    |
| Seagate Technology               | 4         | 0.08%   |
| Adaptec                          | 4         | 0.08%   |
| Lite-On Technology               | 3         | 0.06%   |
| Lite-On IT Corp. / Plextor       | 3         | 0.06%   |
| Broadcom / LSI                   | 3         | 0.06%   |
| Apple                            | 3         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 617       | 9.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 246       | 3.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 238       | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 221       | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 209       | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 189       | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 187       | 2.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 169       | 2.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 165       | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 147       | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 132       | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 131       | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 121       | 1.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 117       | 1.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 115       | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 113       | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 110       | 1.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 99        | 1.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 94        | 1.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 93        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 93        | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 92        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 81        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 81        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 81        | 1.25%   |
| Intel SATA Controller [RAID mode]                                                       | 77        | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 72        | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 71        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 67        | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 66        | 1.02%   |
| AMD FCH SATA Controller D                                                               | 62        | 0.96%   |
| Nvidia MCP61 SATA Controller                                                            | 50        | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 50        | 0.77%   |
| Nvidia MCP61 IDE                                                                        | 49        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 48        | 0.74%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 47        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 43        | 0.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 42        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 41        | 0.63%   |
| AMD FCH IDE Controller                                                                  | 40        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3617      | 66.77%  |
| IDE  | 1058      | 19.53%  |
| NVMe | 480       | 8.86%   |
| RAID | 249       | 4.6%    |
| SCSI | 7         | 0.13%   |
| SAS  | 6         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3430      | 74.94%  |
| AMD    | 1147      | 25.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 1.05%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 44        | 0.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 44        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 39        | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 36        | 0.79%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 30        | 0.66%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 29        | 0.63%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 29        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 27        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 27        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 26        | 0.57%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 0.57%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 26        | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 25        | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 25        | 0.55%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 25        | 0.55%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 25        | 0.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.52%   |
| AMD FX-8350 Eight-Core Processor              | 24        | 0.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 23        | 0.5%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 23        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 0.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.48%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 21        | 0.46%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 21        | 0.46%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 20        | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 19        | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 19        | 0.42%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 19        | 0.42%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.42%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.42%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.42%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 18        | 0.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 18        | 0.39%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 18        | 0.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 17        | 0.37%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 930       | 20.32%  |
| Intel Core i3           | 565       | 12.34%  |
| Intel Core i7           | 555       | 12.13%  |
| Intel Core 2 Duo        | 366       | 8%      |
| Intel Celeron           | 323       | 7.06%   |
| Intel Pentium           | 216       | 4.72%   |
| AMD Ryzen 5             | 175       | 3.82%   |
| Intel Pentium Dual-Core | 116       | 2.53%   |
| AMD FX                  | 102       | 2.23%   |
| AMD Ryzen 7             | 83        | 1.81%   |
| AMD A8                  | 71        | 1.55%   |
| AMD Ryzen 3             | 65        | 1.42%   |
| Intel Core 2 Quad       | 64        | 1.4%    |
| AMD A4                  | 55        | 1.2%    |
| Intel Xeon              | 54        | 1.18%   |
| AMD A6                  | 51        | 1.11%   |
| AMD A10                 | 49        | 1.07%   |
| Intel Pentium Dual      | 48        | 1.05%   |
| AMD Athlon II X2        | 48        | 1.05%   |
| Other                   | 45        | 0.98%   |
| Intel Core 2            | 45        | 0.98%   |
| AMD Athlon 64 X2        | 43        | 0.94%   |
| AMD E                   | 41        | 0.9%    |
| AMD Athlon              | 39        | 0.85%   |
| AMD Phenom II X4        | 37        | 0.81%   |
| Intel Atom              | 36        | 0.79%   |
| AMD E1                  | 31        | 0.68%   |
| AMD Ryzen 9             | 25        | 0.55%   |
| AMD Athlon II X4        | 24        | 0.52%   |
| AMD E2                  | 23        | 0.5%    |
| AMD Phenom II X6        | 17        | 0.37%   |
| Intel Pentium 4         | 16        | 0.35%   |
| Intel Pentium Silver    | 15        | 0.33%   |
| Intel Pentium Gold      | 13        | 0.28%   |
| AMD Phenom              | 13        | 0.28%   |
| Intel Pentium D         | 12        | 0.26%   |
| AMD Sempron             | 12        | 0.26%   |
| AMD C-60                | 11        | 0.24%   |
| AMD Athlon II X3        | 10        | 0.22%   |
| Intel Celeron Dual-Core | 9         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2652      | 57.94%  |
| 4      | 1386      | 30.28%  |
| 6      | 223       | 4.87%   |
| 1      | 127       | 2.77%   |
| 8      | 112       | 2.45%   |
| 3      | 39        | 0.85%   |
| 12     | 23        | 0.5%    |
| 16     | 7         | 0.15%   |
| 10     | 5         | 0.11%   |
| 24     | 1         | 0.02%   |
| 14     | 1         | 0.02%   |
| 5      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4569      | 99.83%  |
| 2      | 8         | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2352      | 51.39%  |
| 1      | 2225      | 48.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4575      | 99.96%  |
| Unknown        | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 467       | 10.2%   |
| 0x306a9    | 423       | 9.24%   |
| 0x1067a    | 364       | 7.95%   |
| 0x306c3    | 309       | 6.75%   |
| Unknown    | 144       | 3.14%   |
| 0x20655    | 133       | 2.9%    |
| 0x6fd      | 120       | 2.62%   |
| 0x40651    | 119       | 2.6%    |
| 0x506e3    | 97        | 2.12%   |
| 0x406e3    | 95        | 2.07%   |
| 0x806e9    | 87        | 1.9%    |
| 0x10676    | 86        | 1.88%   |
| 0x30678    | 85        | 1.86%   |
| 0x906ea    | 82        | 1.79%   |
| 0x306d4    | 81        | 1.77%   |
| 0x906e9    | 76        | 1.66%   |
| 0x06001119 | 68        | 1.48%   |
| 0x010000c8 | 65        | 1.42%   |
| 0x806ea    | 64        | 1.4%    |
| 0x08701021 | 64        | 1.4%    |
| 0x08108109 | 60        | 1.31%   |
| 0x706a1    | 59        | 1.29%   |
| 0x406c4    | 50        | 1.09%   |
| 0x6fb      | 49        | 1.07%   |
| 0x20652    | 45        | 0.98%   |
| 0x08101016 | 45        | 0.98%   |
| 0x806ec    | 44        | 0.96%   |
| 0x0800820d | 41        | 0.9%    |
| 0x506c9    | 38        | 0.83%   |
| 0x07030105 | 36        | 0.79%   |
| 0x06006705 | 34        | 0.74%   |
| 0x106e5    | 31        | 0.68%   |
| 0x0500010d | 30        | 0.66%   |
| 0x010000b6 | 30        | 0.66%   |
| 0x706e5    | 29        | 0.63%   |
| 0x08108102 | 29        | 0.63%   |
| 0x06003106 | 28        | 0.61%   |
| 0x6f6      | 27        | 0.59%   |
| 0x06000822 | 26        | 0.57%   |
| 0xa0653    | 25        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 481       | 10.51%  |
| Penryn          | 464       | 10.14%  |
| Haswell         | 440       | 9.61%   |
| IvyBridge       | 430       | 9.39%   |
| KabyLake        | 410       | 8.96%   |
| Core            | 237       | 5.18%   |
| Skylake         | 201       | 4.39%   |
| K10             | 187       | 4.09%   |
| Westmere        | 184       | 4.02%   |
| Silvermont      | 165       | 3.6%    |
| Piledriver      | 163       | 3.56%   |
| Zen+            | 151       | 3.3%    |
| Zen             | 116       | 2.53%   |
| Zen 2           | 115       | 2.51%   |
| Broadwell       | 85        | 1.86%   |
| Bobcat          | 81        | 1.77%   |
| Goldmont plus   | 77        | 1.68%   |
| Excavator       | 75        | 1.64%   |
| K8 Hammer       | 66        | 1.44%   |
| Puma            | 58        | 1.27%   |
| CometLake       | 54        | 1.18%   |
| Nehalem         | 48        | 1.05%   |
| Goldmont        | 41        | 0.9%    |
| Steamroller     | 36        | 0.79%   |
| NetBurst        | 32        | 0.7%    |
| IceLake         | 30        | 0.66%   |
| Bonnell         | 29        | 0.63%   |
| Jaguar          | 28        | 0.61%   |
| Bulldozer       | 26        | 0.57%   |
| K10 Llano       | 24        | 0.52%   |
| TigerLake       | 13        | 0.28%   |
| Unknown         | 11        | 0.24%   |
| Zen 3           | 9         | 0.2%    |
| K8 & K10 hybrid | 9         | 0.2%    |
| Tremont         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2496      | 49.39%  |
| Nvidia                           | 1335      | 26.41%  |
| AMD                              | 1215      | 24.04%  |
| VIA Technologies                 | 3         | 0.06%   |
| Matrox Electronics Systems       | 3         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 367       | 7.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 207       | 3.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 146       | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 134       | 2.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 125       | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 118       | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 98        | 1.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 92        | 1.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 90        | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 89        | 1.71%   |
| Intel HD Graphics 620                                                                    | 88        | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 82        | 1.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 74        | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 74        | 1.42%   |
| Intel HD Graphics 5500                                                                   | 72        | 1.38%   |
| Nvidia GT218 [GeForce 210]                                                               | 69        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 67        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 65        | 1.25%   |
| Intel HD Graphics 530                                                                    | 65        | 1.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 64        | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 1.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 54        | 1.03%   |
| Intel UHD Graphics 620                                                                   | 53        | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 0.96%   |
| Intel HD Graphics 630                                                                    | 46        | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 43        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 41        | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 40        | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 39        | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 33        | 0.63%   |
| Intel HD Graphics 500                                                                    | 33        | 0.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 33        | 0.63%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 31        | 0.59%   |
| AMD Renoir                                                                               | 31        | 0.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 0.57%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 30        | 0.57%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 29        | 0.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 28        | 0.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 2051      | 44.81%  |
| 1 x AMD         | 1022      | 22.33%  |
| 1 x Nvidia      | 962       | 21.02%  |
| Intel + Nvidia  | 334       | 7.3%    |
| 2 x AMD         | 82        | 1.79%   |
| Intel + AMD     | 81        | 1.77%   |
| AMD + Nvidia    | 30        | 0.66%   |
| 2 x Nvidia      | 8         | 0.17%   |
| 1 x VIA         | 3         | 0.07%   |
| 1 x Matrox      | 2         | 0.04%   |
| 1 x SiS         | 1         | 0.02%   |
| Nvidia + Matrox | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4491      | 98.1%   |
| Unknown     | 82        | 1.79%   |
| Proprietary | 5         | 0.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2123      | 46.37%  |
| 0.01-0.5   | 751       | 16.4%   |
| 1.01-2.0   | 668       | 14.59%  |
| 0.51-1.0   | 626       | 13.67%  |
| 3.01-4.0   | 209       | 4.57%   |
| 7.01-8.0   | 99        | 2.16%   |
| 5.01-6.0   | 66        | 1.44%   |
| 2.01-3.0   | 29        | 0.63%   |
| 8.01-16.0  | 6         | 0.13%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 739       | 16.32%  |
| AU Optronics            | 480       | 10.6%   |
| LG Display              | 383       | 8.46%   |
| Goldstar                | 313       | 6.91%   |
| BOE                     | 296       | 6.54%   |
| Chimei Innolux          | 286       | 6.32%   |
| Hewlett-Packard         | 198       | 4.37%   |
| Dell                    | 195       | 4.31%   |
| Acer                    | 184       | 4.06%   |
| Philips                 | 143       | 3.16%   |
| BenQ                    | 116       | 2.56%   |
| AOC                     | 116       | 2.56%   |
| Ancor Communications    | 103       | 2.28%   |
| Lenovo                  | 101       | 2.23%   |
| Chi Mei Optoelectronics | 100       | 2.21%   |
| Iiyama                  | 61        | 1.35%   |
| CPT                     | 57        | 1.26%   |
| Apple                   | 54        | 1.19%   |
| ViewSonic               | 48        | 1.06%   |
| LG Philips              | 38        | 0.84%   |
| Sony                    | 32        | 0.71%   |
| Fujitsu Siemens         | 30        | 0.66%   |
| PANDA                   | 27        | 0.6%    |
| NEC Computers           | 26        | 0.57%   |
| ASUSTek Computer        | 26        | 0.57%   |
| Eizo                    | 24        | 0.53%   |
| Sharp                   | 20        | 0.44%   |
| HannStar                | 20        | 0.44%   |
| InfoVision              | 18        | 0.4%    |
| Toshiba                 | 14        | 0.31%   |
| Vizio                   | 12        | 0.27%   |
| Vestel Elektronik       | 12        | 0.27%   |
| Medion                  | 12        | 0.27%   |
| Unknown                 | 11        | 0.24%   |
| Panasonic               | 11        | 0.24%   |
| Belinea                 | 10        | 0.22%   |
| Sceptre Tech            | 9         | 0.2%    |
| MStar                   | 9         | 0.2%    |
| InnoLux Display         | 9         | 0.2%    |
| RTK                     | 8         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 44        | 0.96%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 32        | 0.7%    |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 25        | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 20        | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 19        | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 18        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 17        | 0.37%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 16        | 0.35%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 15        | 0.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 14        | 0.31%   |
| PANDA LM116LF3L01 NCP000A 1920x1080 256x144mm 11.6-inch                  | 14        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 14        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 13        | 0.28%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 12        | 0.26%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 12        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 11        | 0.24%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 11        | 0.24%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 10        | 0.22%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 10        | 0.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.22%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 10        | 0.22%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 10        | 0.22%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 9         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1684      | 37.66%  |
| 1366x768 (WXGA)    | 1197      | 26.77%  |
| 1600x900 (HD+)     | 302       | 6.75%   |
| 1280x1024 (SXGA)   | 259       | 5.79%   |
| 1680x1050 (WSXGA+) | 208       | 4.65%   |
| 1440x900 (WXGA+)   | 172       | 3.85%   |
| 1280x800 (WXGA)    | 160       | 3.58%   |
| 3840x2160 (4K)     | 151       | 3.38%   |
| 2560x1440 (QHD)    | 81        | 1.81%   |
| 1920x1200 (WUXGA)  | 67        | 1.5%    |
| 1360x768           | 47        | 1.05%   |
| 2560x1080          | 20        | 0.45%   |
| 1024x768 (XGA)     | 18        | 0.4%    |
| 1920x540           | 16        | 0.36%   |
| 1024x600           | 11        | 0.25%   |
| 3440x1440          | 9         | 0.2%    |
| 2560x1600          | 9         | 0.2%    |
| 1600x1200          | 8         | 0.18%   |
| 1680x945           | 5         | 0.11%   |
| 1280x960           | 5         | 0.11%   |
| 2880x1800          | 4         | 0.09%   |
| 1280x720 (HD)      | 4         | 0.09%   |
| 3200x1800 (QHD+)   | 3         | 0.07%   |
| 2736x1824          | 3         | 0.07%   |
| 2160x1440          | 3         | 0.07%   |
| 2048x1152          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 1280x768           | 3         | 0.07%   |
| 3840x1080          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 1152x864           | 2         | 0.04%   |
| 3840x2400          | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 3840x1100          | 1         | 0.02%   |
| 3300x2200          | 1         | 0.02%   |
| 3000x2000          | 1         | 0.02%   |
| 2880x1920          | 1         | 0.02%   |
| 2304x1440          | 1         | 0.02%   |
| 2256x1504          | 1         | 0.02%   |
| 2048x1536          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1139      | 25.1%   |
| 23      | 388       | 8.55%   |
| 17      | 371       | 8.18%   |
| 21      | 358       | 7.89%   |
| 13      | 345       | 7.6%    |
| 24      | 266       | 5.86%   |
| 14      | 265       | 5.84%   |
| 27      | 235       | 5.18%   |
| 19      | 223       | 4.91%   |
| 18      | 190       | 4.19%   |
| 22      | 134       | 2.95%   |
| 20      | 109       | 2.4%    |
| 31      | 84        | 1.85%   |
| 12      | 69        | 1.52%   |
| 11      | 57        | 1.26%   |
| 84      | 28        | 0.62%   |
| 34      | 27        | 0.59%   |
| 32      | 27        | 0.59%   |
| Unknown | 27        | 0.59%   |
| 54      | 26        | 0.57%   |
| 72      | 24        | 0.53%   |
| 26      | 17        | 0.37%   |
| 25      | 15        | 0.33%   |
| 10      | 15        | 0.33%   |
| 52      | 11        | 0.24%   |
| 16      | 10        | 0.22%   |
| 40      | 8         | 0.18%   |
| 28      | 8         | 0.18%   |
| 46      | 6         | 0.13%   |
| 48      | 5         | 0.11%   |
| 29      | 5         | 0.11%   |
| 74      | 4         | 0.09%   |
| 65      | 4         | 0.09%   |
| 60      | 4         | 0.09%   |
| 58      | 4         | 0.09%   |
| 39      | 4         | 0.09%   |
| 37      | 4         | 0.09%   |
| 49      | 3         | 0.07%   |
| 42      | 3         | 0.07%   |
| 142     | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1683      | 37.45%  |
| 401-500        | 889       | 19.78%  |
| 501-600        | 856       | 19.05%  |
| 351-400        | 420       | 9.35%   |
| 201-300        | 291       | 6.48%   |
| 601-700        | 123       | 2.74%   |
| 1001-1500      | 68        | 1.51%   |
| 1501-2000      | 57        | 1.27%   |
| 701-800        | 56        | 1.25%   |
| Unknown        | 27        | 0.6%    |
| 801-900        | 17        | 0.38%   |
| 901-1000       | 5         | 0.11%   |
| More than 2000 | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3369      | 77.08%  |
| 16/10   | 621       | 14.21%  |
| 5/4     | 253       | 5.79%   |
| 4/3     | 48        | 1.1%    |
| 3/2     | 36        | 0.82%   |
| 21/9    | 27        | 0.62%   |
| 6/5     | 7         | 0.16%   |
| 32/9    | 4         | 0.09%   |
| 1.00    | 2         | 0.05%   |
| 3.40    | 1         | 0.02%   |
| 2.01    | 1         | 0.02%   |
| 0.75    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1127      | 24.97%  |
| 201-250        | 954       | 21.13%  |
| 81-90          | 477       | 10.57%  |
| 151-200        | 469       | 10.39%  |
| 141-150        | 285       | 6.31%   |
| 301-350        | 249       | 5.52%   |
| 121-130        | 192       | 4.25%   |
| 351-500        | 146       | 3.23%   |
| 71-80          | 131       | 2.9%    |
| More than 1000 | 117       | 2.59%   |
| 251-300        | 96        | 2.13%   |
| 61-70          | 64        | 1.42%   |
| 51-60          | 59        | 1.31%   |
| 131-140        | 46        | 1.02%   |
| 501-1000       | 35        | 0.78%   |
| Unknown        | 27        | 0.6%    |
| 41-50          | 14        | 0.31%   |
| 111-120        | 13        | 0.29%   |
| 91-100         | 13        | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1949      | 43.76%  |
| 101-120       | 1559      | 35%     |
| 121-160       | 691       | 15.51%  |
| 1-50          | 115       | 2.58%   |
| 161-240       | 94        | 2.11%   |
| Unknown       | 27        | 0.61%   |
| More than 240 | 19        | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4254      | 92.92%  |
| 2     | 269       | 5.88%   |
| 0     | 39        | 0.85%   |
| 3     | 11        | 0.24%   |
| 6     | 2         | 0.04%   |
| 4     | 2         | 0.04%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2705      | 40%     |
| Intel                             | 1609      | 23.79%  |
| Qualcomm Atheros                  | 1100      | 16.26%  |
| Broadcom                          | 350       | 5.18%   |
| Marvell Technology Group          | 110       | 1.63%   |
| Ralink                            | 98        | 1.45%   |
| Nvidia                            | 97        | 1.43%   |
| Broadcom Limited                  | 95        | 1.4%    |
| Ralink Technology                 | 84        | 1.24%   |
| Samsung Electronics               | 61        | 0.9%    |
| Huawei Technologies               | 46        | 0.68%   |
| TP-Link                           | 42        | 0.62%   |
| JMicron Technology                | 34        | 0.5%    |
| Qualcomm Atheros Communications   | 32        | 0.47%   |
| Dell                              | 21        | 0.31%   |
| D-Link                            | 20        | 0.3%    |
| D-Link System                     | 18        | 0.27%   |
| Ericsson Business Mobile Networks | 17        | 0.25%   |
| VIA Technologies                  | 15        | 0.22%   |
| MediaTek                          | 15        | 0.22%   |
| NetGear                           | 12        | 0.18%   |
| ZTE WCDMA Technologies MSM        | 11        | 0.16%   |
| Xiaomi                            | 11        | 0.16%   |
| Microsoft                         | 11        | 0.16%   |
| ASUSTek Computer                  | 11        | 0.16%   |
| Motorola PCS                      | 9         | 0.13%   |
| ASIX Electronics                  | 9         | 0.13%   |
| 3Com                              | 8         | 0.12%   |
| IMC Networks                      | 7         | 0.1%    |
| Edimax Technology                 | 7         | 0.1%    |
| DisplayLink                       | 7         | 0.1%    |
| Sierra Wireless                   | 6         | 0.09%   |
| Linksys                           | 6         | 0.09%   |
| Belkin Components                 | 6         | 0.09%   |
| Aquantia                          | 5         | 0.07%   |
| Sitecom Europe                    | 4         | 0.06%   |
| OPPO Electronics                  | 4         | 0.06%   |
| Hewlett-Packard                   | 4         | 0.06%   |
| Qualcomm                          | 3         | 0.04%   |
| Mercucys                          | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2006      | 25.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 429       | 5.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 193       | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 184       | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 180       | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 151       | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 139       | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 85        | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 79        | 1.02%   |
| Intel Wireless 7265                                                     | 75        | 0.97%   |
| Intel Wi-Fi 6 AX200                                                     | 73        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 72        | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 66        | 0.85%   |
| Intel Ethernet Connection I217-LM                                       | 64        | 0.83%   |
| Intel Wireless 7260                                                     | 62        | 0.8%    |
| Intel I211 Gigabit Network Connection                                   | 62        | 0.8%    |
| Intel Ethernet Connection (2) I219-V                                    | 58        | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 57        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 55        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 54        | 0.7%    |
| Intel 82579V Gigabit Network Connection                                 | 53        | 0.69%   |
| Intel WiFi Link 5100                                                    | 49        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 47        | 0.61%   |
| Nvidia MCP61 Ethernet                                                   | 46        | 0.59%   |
| Intel Wireless 8265 / 8275                                              | 45        | 0.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 43        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                                | 43        | 0.56%   |
| Intel Wireless 8260                                                     | 42        | 0.54%   |
| Ralink MT7601U Wireless Adapter                                         | 41        | 0.53%   |
| Intel Wireless 3165                                                     | 41        | 0.53%   |
| Intel 82567LM Gigabit Network Connection                                | 41        | 0.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 40        | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 39        | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 39        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 0.5%    |
| Huawei E353/E3131                                                       | 39        | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 0.49%   |
| Intel Centrino Advanced-N 6200                                          | 38        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1069      | 34.38%  |
| Qualcomm Atheros                | 869       | 27.95%  |
| Realtek Semiconductor           | 565       | 18.17%  |
| Broadcom                        | 186       | 5.98%   |
| Ralink                          | 98        | 3.15%   |
| Ralink Technology               | 84        | 2.7%    |
| Broadcom Limited                | 39        | 1.25%   |
| TP-Link                         | 38        | 1.22%   |
| Qualcomm Atheros Communications | 32        | 1.03%   |
| D-Link                          | 17        | 0.55%   |
| Dell                            | 11        | 0.35%   |
| ASUSTek Computer                | 11        | 0.35%   |
| NetGear                         | 10        | 0.32%   |
| Microsoft                       | 10        | 0.32%   |
| D-Link System                   | 8         | 0.26%   |
| MediaTek                        | 7         | 0.23%   |
| IMC Networks                    | 7         | 0.23%   |
| Edimax Technology               | 7         | 0.23%   |
| Sierra Wireless                 | 6         | 0.19%   |
| Belkin Components               | 6         | 0.19%   |
| Linksys                         | 5         | 0.16%   |
| Marvell Technology Group        | 4         | 0.13%   |
| Sitecom Europe                  | 3         | 0.1%    |
| Mercucys                        | 3         | 0.1%    |
| AVM                             | 3         | 0.1%    |
| Wilocity                        | 2         | 0.06%   |
| Wacom                           | 2         | 0.06%   |
| Guillemot                       | 2         | 0.06%   |
| ZyXEL Communications            | 1         | 0.03%   |
| ZyDAS                           | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Fibocom                         | 1         | 0.03%   |
| BUFFALO                         | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 184       | 5.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 180       | 5.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 151       | 4.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 139       | 4.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 85        | 2.72%   |
| Intel Wireless 7265                                                     | 75        | 2.4%    |
| Intel Wi-Fi 6 AX200                                                     | 73        | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 72        | 2.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 66        | 2.12%   |
| Intel Wireless 7260                                                     | 62        | 1.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 54        | 1.73%   |
| Intel WiFi Link 5100                                                    | 49        | 1.57%   |
| Intel Wireless 8265 / 8275                                              | 45        | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 43        | 1.38%   |
| Intel Wireless 8260                                                     | 42        | 1.35%   |
| Ralink MT7601U Wireless Adapter                                         | 41        | 1.31%   |
| Intel Wireless 3165                                                     | 41        | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 40        | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 39        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 39        | 1.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 1.22%   |
| Intel Centrino Advanced-N 6200                                          | 38        | 1.22%   |
| Intel Wireless 3160                                                     | 37        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 34        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 34        | 1.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 32        | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 30        | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 30        | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                         | 29        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 29        | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 29        | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 0.9%    |
| Intel Wireless-AC 9260                                                  | 27        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 27        | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2539      | 56.26%  |
| Intel                             | 900       | 19.94%  |
| Qualcomm Atheros                  | 346       | 7.67%   |
| Broadcom                          | 199       | 4.41%   |
| Marvell Technology Group          | 106       | 2.35%   |
| Nvidia                            | 96        | 2.13%   |
| Samsung Electronics               | 61        | 1.35%   |
| Broadcom Limited                  | 58        | 1.29%   |
| Huawei Technologies               | 44        | 0.97%   |
| JMicron Technology                | 34        | 0.75%   |
| VIA Technologies                  | 13        | 0.29%   |
| Xiaomi                            | 11        | 0.24%   |
| ZTE WCDMA Technologies MSM        | 10        | 0.22%   |
| D-Link System                     | 10        | 0.22%   |
| ASIX Electronics                  | 9         | 0.2%    |
| MediaTek                          | 8         | 0.18%   |
| 3Com                              | 8         | 0.18%   |
| DisplayLink                       | 7         | 0.16%   |
| Motorola PCS                      | 6         | 0.13%   |
| TP-Link                           | 5         | 0.11%   |
| Aquantia                          | 5         | 0.11%   |
| OPPO Electronics                  | 4         | 0.09%   |
| Qualcomm                          | 3         | 0.07%   |
| ICS Advent                        | 3         | 0.07%   |
| D-Link                            | 3         | 0.07%   |
| Apple                             | 3         | 0.07%   |
| T & A Mobile Phones               | 2         | 0.04%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.04%   |
| NetGear                           | 2         | 0.04%   |
| HMD Global                        | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Sitecom Europe                    | 1         | 0.02%   |
| Microsoft                         | 1         | 0.02%   |
| Linksys                           | 1         | 0.02%   |
| LG Electronics                    | 1         | 0.02%   |
| Lenovo                            | 1         | 0.02%   |
| IBM                               | 1         | 0.02%   |
| Hewlett-Packard                   | 1         | 0.02%   |
| Google                            | 1         | 0.02%   |
| Foxconn / Hon Hai                 | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2006      | 43.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 429       | 9.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 193       | 4.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 79        | 1.73%   |
| Intel Ethernet Connection I217-LM                                 | 64        | 1.4%    |
| Intel I211 Gigabit Network Connection                             | 62        | 1.36%   |
| Intel Ethernet Connection (2) I219-V                              | 58        | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 57        | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 55        | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 53        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 47        | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 46        | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 43        | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 41        | 0.9%    |
| Huawei E353/E3131                                                 | 39        | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 37        | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 36        | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 35        | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 33        | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 30        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 25        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 23        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 19        | 0.42%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 19        | 0.42%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 19        | 0.42%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 18        | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 17        | 0.37%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.35%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.33%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 14        | 0.31%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 14        | 0.31%   |
| Intel 82566MM Gigabit Network Connection                          | 14        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4322      | 58.47%  |
| WiFi     | 3017      | 40.81%  |
| Modem    | 44        | 0.6%    |
| Unknown  | 9         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2646      | 58.83%  |
| WiFi     | 1852      | 41.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2435      | 53.2%   |
| 1     | 2061      | 45.03%  |
| 3     | 49        | 1.07%   |
| 0     | 27        | 0.59%   |
| 4     | 3         | 0.07%   |
| 7     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3626      | 79.08%  |
| Yes     | 958       | 20.89%  |
| Unknown | 1         | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 665       | 32.65%  |
| Qualcomm Atheros Communications | 250       | 12.27%  |
| Realtek Semiconductor           | 211       | 10.36%  |
| Cambridge Silicon Radio         | 170       | 8.35%   |
| Broadcom                        | 152       | 7.46%   |
| Lite-On Technology              | 125       | 6.14%   |
| IMC Networks                    | 78        | 3.83%   |
| Foxconn / Hon Hai               | 69        | 3.39%   |
| Apple                           | 56        | 2.75%   |
| Dell                            | 52        | 2.55%   |
| ASUSTek Computer                | 42        | 2.06%   |
| Toshiba                         | 40        | 1.96%   |
| Hewlett-Packard                 | 32        | 1.57%   |
| Ralink                          | 23        | 1.13%   |
| Realtek                         | 11        | 0.54%   |
| Foxconn International           | 10        | 0.49%   |
| Chicony Electronics             | 8         | 0.39%   |
| Alps Electric                   | 7         | 0.34%   |
| Ralink Technology               | 6         | 0.29%   |
| Marvell Semiconductor           | 6         | 0.29%   |
| Integrated System Solution      | 6         | 0.29%   |
| Belkin Components               | 4         | 0.2%    |
| Askey Computer                  | 4         | 0.2%    |
| Taiyo Yuden                     | 2         | 0.1%    |
| Micro Star International        | 2         | 0.1%    |
| Dynex                           | 2         | 0.1%    |
| Unknown                         | 1         | 0.05%   |
| MediaTek                        | 1         | 0.05%   |
| i.Tech Dynamic Limited          | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 328       | 16.1%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 170       | 8.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 124       | 6.09%   |
| Realtek Bluetooth Radio                                                             | 121       | 5.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 95        | 4.66%   |
| Intel AX200 Bluetooth                                                               | 67        | 3.29%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 58        | 2.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 55        | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 50        | 2.45%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 44        | 2.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 42        | 2.06%   |
| Intel AX201 Bluetooth                                                               | 36        | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 35        | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 34        | 1.67%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 32        | 1.57%   |
| IMC Networks Bluetooth Device                                                       | 28        | 1.37%   |
| Lite-On Bluetooth Device                                                            | 27        | 1.33%   |
| IMC Networks Bluetooth Radio                                                        | 27        | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 25        | 1.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 24        | 1.18%   |
| Apple Bluetooth Host Controller                                                     | 24        | 1.18%   |
| Ralink RT3290 Bluetooth                                                             | 23        | 1.13%   |
| Dell DW375 Bluetooth Module                                                         | 23        | 1.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 22        | 1.08%   |
| Realtek RTL8723B Bluetooth                                                          | 20        | 0.98%   |
| Apple Bluetooth USB Host Controller                                                 | 19        | 0.93%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 17        | 0.83%   |
| Toshiba Bluetooth Device                                                            | 16        | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 16        | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 16        | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 16        | 0.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 16        | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 0.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 15        | 0.74%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.64%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 13        | 0.64%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.59%   |
| Realtek RTL8821A Bluetooth                                                          | 11        | 0.54%   |
| Realtek Bluetooth Radio                                                             | 11        | 0.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 11        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 3337      | 55.47%  |
| AMD                                             | 1318      | 21.91%  |
| Nvidia                                          | 1040      | 17.29%  |
| C-Media Electronics                             | 73        | 1.21%   |
| Creative Labs                                   | 62        | 1.03%   |
| Logitech                                        | 19        | 0.32%   |
| VIA Technologies                                | 18        | 0.3%    |
| JMTek                                           | 16        | 0.27%   |
| Texas Instruments                               | 15        | 0.25%   |
| Creative Technology                             | 10        | 0.17%   |
| Generalplus Technology                          | 8         | 0.13%   |
| ASUSTek Computer                                | 8         | 0.13%   |
| Tenx Technology                                 | 5         | 0.08%   |
| Yamaha                                          | 4         | 0.07%   |
| Razer USA                                       | 4         | 0.07%   |
| M-Audio                                         | 4         | 0.07%   |
| Bose                                            | 4         | 0.07%   |
| GN Netcom                                       | 3         | 0.05%   |
| Giga-Byte Technology                            | 3         | 0.05%   |
| Focusrite-Novation                              | 3         | 0.05%   |
| Ensoniq                                         | 3         | 0.05%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.03%   |
| Syntek                                          | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]                | 2         | 0.03%   |
| SAVITECH                                        | 2         | 0.03%   |
| Samson Technologies                             | 2         | 0.03%   |
| ROCCAT                                          | 2         | 0.03%   |
| Realtek Semiconductor                           | 2         | 0.03%   |
| PreSonus Audio Electronics                      | 2         | 0.03%   |
| Meizu                                           | 2         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.03%   |
| Dell                                            | 2         | 0.03%   |
| XMOS                                            | 1         | 0.02%   |
| UCQ01000                                        | 1         | 0.02%   |
| Turtle Beach                                    | 1         | 0.02%   |
| TerraTec Electronic                             | 1         | 0.02%   |
| TEAC                                            | 1         | 0.02%   |
| SteelSeries ApS                                 | 1         | 0.02%   |
| Sony                                            | 1         | 0.02%   |
| QinHeng Electronics                             | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 465       | 6.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 420       | 5.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 315       | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 270       | 3.76%   |
| AMD FCH Azalia Controller                                                                         | 260       | 3.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 250       | 3.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 248       | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 207       | 2.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 205       | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 203       | 2.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 198       | 2.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 147       | 2.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 145       | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 120       | 1.67%   |
| Nvidia High Definition Audio Controller                                                           | 119       | 1.66%   |
| Intel 8 Series HD Audio Controller                                                                | 119       | 1.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 117       | 1.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 116       | 1.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 111       | 1.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 109       | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 98        | 1.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 95        | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 88        | 1.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 85        | 1.18%   |
| Intel Broadwell-U Audio Controller                                                                | 82        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 81        | 1.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 81        | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 76        | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 76        | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 74        | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 67        | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 65        | 0.91%   |
| AMD Wrestler HDMI Audio                                                                           | 64        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 62        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 60        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 60        | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 58        | 0.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 53        | 0.74%   |
| AMD Trinity HDMI Audio Controller                                                                 | 52        | 0.72%   |
| Nvidia MCP61 High Definition Audio                                                                | 48        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 992       | 18.47%  |
| Unknown             | 877       | 16.33%  |
| SK hynix            | 758       | 14.11%  |
| Kingston            | 747       | 13.91%  |
| Micron Technology   | 360       | 6.7%    |
| Crucial             | 259       | 4.82%   |
| Corsair             | 220       | 4.1%    |
| Elpida              | 162       | 3.02%   |
| G.Skill             | 129       | 2.4%    |
| Nanya Technology    | 116       | 2.16%   |
| A-DATA Technology   | 110       | 2.05%   |
| Ramaxel Technology  | 94        | 1.75%   |
| Smart               | 55        | 1.02%   |
| Unknown (ABCD)      | 47        | 0.87%   |
| Patriot             | 40        | 0.74%   |
| GOODRAM             | 31        | 0.58%   |
| Team                | 29        | 0.54%   |
| Transcend           | 28        | 0.52%   |
| Apacer              | 27        | 0.5%    |
| AMD                 | 20        | 0.37%   |
| Unknown             | 18        | 0.34%   |
| ASint Technology    | 16        | 0.3%    |
| Kingmax             | 14        | 0.26%   |
| Toshiba             | 13        | 0.24%   |
| Teikon              | 13        | 0.24%   |
| High Bridge         | 13        | 0.24%   |
| Silicon Power       | 11        | 0.2%    |
| Qimonda             | 11        | 0.2%    |
| GeIL                | 10        | 0.19%   |
| Unifosa             | 8         | 0.15%   |
| Avant               | 8         | 0.15%   |
| PNY                 | 7         | 0.13%   |
| TakeMS              | 5         | 0.09%   |
| Smart Brazil        | 5         | 0.09%   |
| Multilaser          | 5         | 0.09%   |
| Unknown (AB)        | 4         | 0.07%   |
| SHARETRONIC         | 4         | 0.07%   |
| Qumo                | 4         | 0.07%   |
| Kreton              | 4         | 0.07%   |
| Atermiter           | 4         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 57        | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 54        | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 47        | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 47        | 0.8%    |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 46        | 0.79%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 46        | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 43        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 43        | 0.73%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 0.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 39        | 0.67%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 38        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 37        | 0.63%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 36        | 0.62%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 34        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 34        | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 33        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 31        | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 28        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 26        | 0.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.43%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 24        | 0.41%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 23        | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 22        | 0.38%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 22        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 20        | 0.34%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 20        | 0.34%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 20        | 0.34%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 19        | 0.32%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 18        | 0.31%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.31%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 18        | 0.31%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s           | 18        | 0.31%   |
| Unknown                                                          | 18        | 0.31%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 17        | 0.29%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 17        | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 16        | 0.27%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 16        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 2315      | 50.21%  |
| DDR4    | 1128      | 24.46%  |
| DDR2    | 472       | 10.24%  |
| Unknown | 286       | 6.2%    |
| SDRAM   | 259       | 5.62%   |
| LPDDR4  | 76        | 1.65%   |
| DDR     | 47        | 1.02%   |
| LPDDR3  | 21        | 0.46%   |
| DRAM    | 7         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2296      | 50.97%  |
| DIMM         | 2142      | 47.55%  |
| Row Of Chips | 53        | 1.18%   |
| Chip         | 7         | 0.16%   |
| RIMM         | 3         | 0.07%   |
| Unknown      | 3         | 0.07%   |
| FB-DIMM      | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 2041      | 40.13%  |
| 2048  | 1270      | 24.97%  |
| 8192  | 1181      | 23.22%  |
| 1024  | 318       | 6.25%   |
| 16384 | 215       | 4.23%   |
| 512   | 31        | 0.61%   |
| 32768 | 26        | 0.51%   |
| 3072  | 1         | 0.02%   |
| 256   | 1         | 0.02%   |
| 64    | 1         | 0.02%   |
| 32    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1405      | 27.27%  |
| 1333    | 665       | 12.91%  |
| 2667    | 415       | 8.05%   |
| 2400    | 323       | 6.27%   |
| 1334    | 277       | 5.38%   |
| 667     | 275       | 5.34%   |
| 800     | 255       | 4.95%   |
| Unknown | 186       | 3.61%   |
| 2133    | 170       | 3.3%    |
| 3200    | 151       | 2.93%   |
| 1067    | 122       | 2.37%   |
| 1867    | 84        | 1.63%   |
| 1066    | 70        | 1.36%   |
| 3600    | 68        | 1.32%   |
| 4199    | 54        | 1.05%   |
| 1866    | 47        | 0.91%   |
| 2048    | 45        | 0.87%   |
| 533     | 45        | 0.87%   |
| 3266    | 43        | 0.83%   |
| 400     | 39        | 0.76%   |
| 1800    | 34        | 0.66%   |
| 975     | 30        | 0.58%   |
| 3400    | 29        | 0.56%   |
| 2933    | 28        | 0.54%   |
| 3466    | 25        | 0.49%   |
| 2666    | 24        | 0.47%   |
| 3000    | 23        | 0.45%   |
| 2800    | 16        | 0.31%   |
| 333     | 14        | 0.27%   |
| 3733    | 12        | 0.23%   |
| 2000    | 10        | 0.19%   |
| 1648    | 10        | 0.19%   |
| 1639    | 10        | 0.19%   |
| 3866    | 9         | 0.17%   |
| 2200    | 9         | 0.17%   |
| 49926   | 8         | 0.16%   |
| 3800    | 8         | 0.16%   |
| 3066    | 8         | 0.16%   |
| 3151    | 7         | 0.14%   |
| 4267    | 6         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 78        | 45.88%  |
| Brother Industries    | 28        | 16.47%  |
| Canon                 | 21        | 12.35%  |
| Samsung Electronics   | 19        | 11.18%  |
| Seiko Epson           | 16        | 9.41%   |
| Lexmark International | 2         | 1.18%   |
| Dymo-CoStar           | 2         | 1.18%   |
| Xerox                 | 1         | 0.59%   |
| Ricoh                 | 1         | 0.59%   |
| Prolific Technology   | 1         | 0.59%   |
| Oki Data              | 1         | 0.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP DeskJet 3630 series                                     | 6         | 3.49%   |
| HP DeskJet 2620 All-in-One Printer                         | 5         | 2.91%   |
| Samsung ML-1640 Series Laser Printer                       | 4         | 2.33%   |
| HP LaserJet P1006                                          | 4         | 2.33%   |
| Samsung M2020 Series                                       | 3         | 1.74%   |
| HP LaserJet 1020                                           | 3         | 1.74%   |
| HP ENVY 4520 series                                        | 3         | 1.74%   |
| HP DeskJet 2130 series                                     | 3         | 1.74%   |
| Seiko Epson XP-243 245 247 Series                          | 2         | 1.16%   |
| Samsung M2070 Series                                       | 2         | 1.16%   |
| HP OfficeJet Pro 6960                                      | 2         | 1.16%   |
| HP LaserJet P1102                                          | 2         | 1.16%   |
| HP ENVY Photo 6200 series                                  | 2         | 1.16%   |
| HP Deskjet F4500 series                                    | 2         | 1.16%   |
| HP DeskJet 916C                                            | 2         | 1.16%   |
| HP DeskJet 845c                                            | 2         | 1.16%   |
| HP Deskjet 3520 series                                     | 2         | 1.16%   |
| HP DeskJet 2700 series                                     | 2         | 1.16%   |
| Canon PIXMA MX920 Series                                   | 2         | 1.16%   |
| Canon PIXMA MX530 Series                                   | 2         | 1.16%   |
| Canon PIXMA MG3600 Series                                  | 2         | 1.16%   |
| Canon PIXMA MG3500 Series                                  | 2         | 1.16%   |
| Brother Printer                                            | 2         | 1.16%   |
| Brother DCP-L3550CDW series                                | 2         | 1.16%   |
| Xerox Phaser 6000B                                         | 1         | 0.58%   |
| Seiko Epson XP-4100 Series                                 | 1         | 0.58%   |
| Seiko Epson WF-2530 Series                                 | 1         | 0.58%   |
| Seiko Epson WF-2510 Series                                 | 1         | 0.58%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                      | 1         | 0.58%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F     | 1         | 0.58%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series              | 1         | 0.58%   |
| Seiko Epson L375 Series                                    | 1         | 0.58%   |
| Seiko Epson L365 Series                                    | 1         | 0.58%   |
| Seiko Epson L312 Series                                    | 1         | 0.58%   |
| Seiko Epson L220 Series                                    | 1         | 0.58%   |
| Seiko Epson L210 Series                                    | 1         | 0.58%   |
| Seiko Epson L120 Series                                    | 1         | 0.58%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 0.58%   |
| Seiko Epson ET-2600 Series                                 | 1         | 0.58%   |
| Samsung Xerox Phaser 3117 Laser Printer                    | 1         | 0.58%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 21        | 46.67%  |
| Hewlett-Packard             | 11        | 24.44%  |
| Seiko Epson                 | 5         | 11.11%  |
| Mustek Systems              | 4         | 8.89%   |
| AGFA-Gevaert NV             | 2         | 4.44%   |
| Plustek                     | 1         | 2.22%   |
| KYE Systems (Mouse Systems) | 1         | 2.22%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 11.11%  |
| Canon CanoScan LiDE 110                                  | 3         | 6.67%   |
| Mustek Systems ScanExpress 1200 UB                       | 2         | 4.44%   |
| HP ScanJet 5590                                          | 2         | 4.44%   |
| HP ScanJet 4500C/5550C                                   | 2         | 4.44%   |
| Canon CanoScan LIDE 25                                   | 2         | 4.44%   |
| Canon CanoScan LiDE 120                                  | 2         | 4.44%   |
| Canon CanoScan LiDE 100                                  | 2         | 4.44%   |
| Seiko Epson Scanner                                      | 1         | 2.22%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1         | 2.22%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 2.22%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 2.22%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1         | 2.22%   |
| Plustek 600DPI USB Scanner                               | 1         | 2.22%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1         | 2.22%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1         | 2.22%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 2.22%   |
| HP ScanJet G4010                                         | 1         | 2.22%   |
| HP ScanJet 4370                                          | 1         | 2.22%   |
| HP ScanJet 3800c                                         | 1         | 2.22%   |
| HP ScanJet 3670                                          | 1         | 2.22%   |
| HP ScanJet 2300c                                         | 1         | 2.22%   |
| HP ScanJet 2200c                                         | 1         | 2.22%   |
| HP PSC 1200                                              | 1         | 2.22%   |
| Canon CanoScan N650U/N656U                               | 1         | 2.22%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 2.22%   |
| Canon CanoScan LiDE 700F                                 | 1         | 2.22%   |
| Canon CanoScan LiDE 70                                   | 1         | 2.22%   |
| Canon CanoScan LiDE 500F                                 | 1         | 2.22%   |
| Canon CanoScan LiDE 220                                  | 1         | 2.22%   |
| Canon CanoScan LiDE 200                                  | 1         | 2.22%   |
| AGFA-Gevaert NV SnapScan Touch                           | 1         | 2.22%   |
| AGFA-Gevaert NV SnapScan e20                             | 1         | 2.22%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 552       | 24.48%  |
| Suyin                                  | 173       | 7.67%   |
| Microdia                               | 160       | 7.1%    |
| Realtek Semiconductor                  | 156       | 6.92%   |
| IMC Networks                           | 148       | 6.56%   |
| Acer                                   | 146       | 6.47%   |
| Logitech                               | 111       | 4.92%   |
| Sunplus Innovation Technology          | 100       | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 84        | 3.73%   |
| Quanta                                 | 71        | 3.15%   |
| Syntek                                 | 70        | 3.1%    |
| Alcor Micro                            | 51        | 2.26%   |
| Apple                                  | 46        | 2.04%   |
| Silicon Motion                         | 44        | 1.95%   |
| Ricoh                                  | 39        | 1.73%   |
| Lite-On Technology                     | 38        | 1.69%   |
| Microsoft                              | 28        | 1.24%   |
| Z-Star Microelectronics                | 23        | 1.02%   |
| Lenovo                                 | 23        | 1.02%   |
| Importek                               | 15        | 0.67%   |
| Primax Electronics                     | 14        | 0.62%   |
| GEMBIRD                                | 13        | 0.58%   |
| OmniVision Technologies                | 9         | 0.4%    |
| Luxvisions Innotech Limited            | 9         | 0.4%    |
| DigiTech                               | 9         | 0.4%    |
| Aveo Technology                        | 9         | 0.4%    |
| ALi                                    | 9         | 0.4%    |
| Creative Technology                    | 8         | 0.35%   |
| Samsung Electronics                    | 7         | 0.31%   |
| Cubeternet                             | 7         | 0.31%   |
| KYE Systems (Mouse Systems)            | 5         | 0.22%   |
| Huawei Technologies                    | 5         | 0.22%   |
| Genesys Logic                          | 5         | 0.22%   |
| Generalplus Technology                 | 5         | 0.22%   |
| ARC International                      | 5         | 0.22%   |
| Pixart Imaging                         | 4         | 0.18%   |
| Unknown                                | 3         | 0.13%   |
| Trust                                  | 3         | 0.13%   |
| Jieli Technology                       | 3         | 0.13%   |
| Intel                                  | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 55        | 2.43%   |
| Chicony Integrated Camera                               | 45        | 1.99%   |
| Suyin Integrated_Webcam_HD                              | 34        | 1.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 34        | 1.5%    |
| Realtek Integrated_Webcam_HD                            | 33        | 1.46%   |
| Chicony USB 2.0 Camera                                  | 33        | 1.46%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 32        | 1.42%   |
| Alcor Micro USB 2.0 Camera                              | 28        | 1.24%   |
| Acer Lenovo EasyCamera                                  | 27        | 1.19%   |
| Acer Integrated Camera                                  | 27        | 1.19%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 26        | 1.15%   |
| Chicony USB2.0 HD UVC WebCam                            | 26        | 1.15%   |
| Microdia Integrated_Webcam_HD                           | 25        | 1.11%   |
| Logitech Webcam C270                                    | 25        | 1.11%   |
| Chicony VGA Webcam                                      | 23        | 1.02%   |
| Sunplus Integrated_Webcam_HD                            | 22        | 0.97%   |
| Realtek USB Camera                                      | 22        | 0.97%   |
| Syntek Lenovo EasyCamera                                | 21        | 0.93%   |
| Syntek Integrated Camera                                | 21        | 0.93%   |
| Chicony HP TrueVision HD                                | 21        | 0.93%   |
| Chicony EasyCamera                                      | 21        | 0.93%   |
| Quanta HP Webcam                                        | 20        | 0.88%   |
| Apple Built-in iSight                                   | 20        | 0.88%   |
| Microdia USB 2.0 Camera                                 | 19        | 0.84%   |
| Microdia Integrated Webcam                              | 19        | 0.84%   |
| Sunplus HD WebCam                                       | 18        | 0.8%    |
| Chicony TOSHIBA Web Camera - HD                         | 18        | 0.8%    |
| Chicony Lenovo EasyCamera                               | 18        | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 18        | 0.8%    |
| Acer EasyCamera                                         | 17        | 0.75%   |
| Logitech Webcam C310                                    | 16        | 0.71%   |
| Lite-On Integrated Camera                               | 16        | 0.71%   |
| Suyin HP Truevision HD                                  | 15        | 0.66%   |
| Logitech HD Pro Webcam C920                             | 15        | 0.66%   |
| IMC Networks UVC VGA Webcam                             | 15        | 0.66%   |
| IMC Networks Integrated Camera                          | 15        | 0.66%   |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.66%   |
| Chicony Acer CrystalEye Webcam                          | 15        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 15        | 0.66%   |
| Acer Lenovo Integrated Webcam                           | 15        | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 100       | 38.31%  |
| AuthenTec                  | 47        | 18.01%  |
| Upek                       | 32        | 12.26%  |
| Synaptics                  | 20        | 7.66%   |
| Shenzhen Goodix Technology | 20        | 7.66%   |
| STMicroelectronics         | 14        | 5.36%   |
| LighTuning Technology      | 14        | 5.36%   |
| Elan Microelectronics      | 13        | 4.98%   |
| Focal-systems.Corp         | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 10.73%  |
| AuthenTec AES2810                                                          | 20        | 7.66%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 6.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 5.75%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 5.75%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 5.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 4.6%    |
| Elan ELAN:Fingerprint                                                      | 12        | 4.6%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 4.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 3.45%   |
| Synaptics  WBDI                                                            | 9         | 3.45%   |
| Validity Sensors VFS491                                                    | 7         | 2.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 2.68%   |
| AuthenTec AES1600                                                          | 7         | 2.68%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.92%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.53%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.53%   |
| Unknown                                                                    | 4         | 1.53%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.15%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.77%   |
| Synaptics WBDI Device                                                      | 2         | 0.77%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.77%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.38%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.38%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.38%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.38%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 70        | 48.95%  |
| O2 Micro                          | 21        | 14.69%  |
| Alcor Micro                       | 21        | 14.69%  |
| Lenovo                            | 13        | 9.09%   |
| Upek                              | 7         | 4.9%    |
| OmniKey                           | 3         | 2.1%    |
| SCM Microsystems                  | 2         | 1.4%    |
| VASCO Data Security International | 1         | 0.7%    |
| Reiner SCT Kartensysteme          | 1         | 0.7%    |
| Microchip Technology              | 1         | 0.7%    |
| Fujitsu Siemens Computers         | 1         | 0.7%    |
| BIT4ID                            | 1         | 0.7%    |
| Advanced Card Systems             | 1         | 0.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 45        | 31.47%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 14.69%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 13.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 12.59%  |
| Lenovo Integrated Smart Card Reader                                          | 13        | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.9%    |
| Broadcom 5880                                                                | 7         | 4.9%    |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.4%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.7%    |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.7%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.7%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.7%    |
| OmniKey CardMan 4321                                                         | 1         | 0.7%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.7%    |
| OmniKey CardMan 1021                                                         | 1         | 0.7%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.7%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.7%    |
| BIT4ID miniLector EVO                                                        | 1         | 0.7%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3909      | 85.39%  |
| 1     | 590       | 12.89%  |
| 2     | 77        | 1.68%   |
| 3     | 2         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 261       | 35.13%  |
| Chipcard                 | 140       | 18.84%  |
| Graphics card            | 116       | 15.61%  |
| Net/wireless             | 77        | 10.36%  |
| Storage                  | 34        | 4.58%   |
| Multimedia controller    | 28        | 3.77%   |
| Bluetooth                | 26        | 3.5%    |
| Communication controller | 17        | 2.29%   |
| Camera                   | 13        | 1.75%   |
| Unassigned class         | 11        | 1.48%   |
| Card reader              | 6         | 0.81%   |
| Sound                    | 3         | 0.4%    |
| Network                  | 3         | 0.4%    |
| Modem                    | 3         | 0.4%    |
| Storage/ata              | 2         | 0.27%   |
| Unclassified device      | 1         | 0.13%   |
| Net/ethernet             | 1         | 0.13%   |
| Flash memory             | 1         | 0.13%   |

