Red OS - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Red OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Red_OS/Desktop/README.md) and [notebooks](/Dist/Red_OS/Notebook/README.md).

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

Total: 362

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Quanta        | 2AC5 100                    | Desktop     | [7f253a82dc](https://linux-hardware.org/?probe=7f253a82dc) | Mar 31, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [36b3103f3f](https://linux-hardware.org/?probe=36b3103f3f) | Mar 31, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [7404d94ca4](https://linux-hardware.org/?probe=7404d94ca4) | Mar 31, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [3ad3c5e45c](https://linux-hardware.org/?probe=3ad3c5e45c) | Mar 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [8400d48ed0](https://linux-hardware.org/?probe=8400d48ed0) | Mar 29, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [ea8ce90ed5](https://linux-hardware.org/?probe=ea8ce90ed5) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [deb6990c19](https://linux-hardware.org/?probe=deb6990c19) | Mar 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [ef91ef3645](https://linux-hardware.org/?probe=ef91ef3645) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [eded7b36b1](https://linux-hardware.org/?probe=eded7b36b1) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [9ee3ca41c8](https://linux-hardware.org/?probe=9ee3ca41c8) | Mar 27, 2023 |
| HP            | 0AA4h                       | Desktop     | [a77b084eba](https://linux-hardware.org/?probe=a77b084eba) | Mar 25, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [fcc7a18f89](https://linux-hardware.org/?probe=fcc7a18f89) | Mar 24, 2023 |
| iRU           | P231                        | All in one  | [98e5c0ba37](https://linux-hardware.org/?probe=98e5c0ba37) | Mar 23, 2023 |
| DEPO Compu... | MS-7846                     | Desktop     | [baaaef2394](https://linux-hardware.org/?probe=baaaef2394) | Mar 22, 2023 |
| MSI           | Sword 15 A12UE              | Notebook    | [f4341a491a](https://linux-hardware.org/?probe=f4341a491a) | Mar 21, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [be9b767d92](https://linux-hardware.org/?probe=be9b767d92) | Mar 20, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [58c99c07a6](https://linux-hardware.org/?probe=58c99c07a6) | Mar 17, 2023 |
| Biostar       | H610MH                      | Desktop     | [6b367d747d](https://linux-hardware.org/?probe=6b367d747d) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [9e172b266b](https://linux-hardware.org/?probe=9e172b266b) | Mar 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [a26dff699b](https://linux-hardware.org/?probe=a26dff699b) | Mar 14, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [47b6690dc8](https://linux-hardware.org/?probe=47b6690dc8) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [7c7bdc15fe](https://linux-hardware.org/?probe=7c7bdc15fe) | Mar 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [b473b68faf](https://linux-hardware.org/?probe=b473b68faf) | Mar 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [4a8589fbdf](https://linux-hardware.org/?probe=4a8589fbdf) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [9442ced293](https://linux-hardware.org/?probe=9442ced293) | Mar 09, 2023 |
| HP            | 8599                        | Desktop     | [2b9bd0b4a7](https://linux-hardware.org/?probe=2b9bd0b4a7) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [ccb99906a8](https://linux-hardware.org/?probe=ccb99906a8) | Mar 06, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [a78a4114e6](https://linux-hardware.org/?probe=a78a4114e6) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [388d4b38c1](https://linux-hardware.org/?probe=388d4b38c1) | Mar 06, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [6d97e48a7e](https://linux-hardware.org/?probe=6d97e48a7e) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [8741c0e2f1](https://linux-hardware.org/?probe=8741c0e2f1) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [9e1f0243d7](https://linux-hardware.org/?probe=9e1f0243d7) | Mar 06, 2023 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [0d02616013](https://linux-hardware.org/?probe=0d02616013) | Mar 03, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2485632618](https://linux-hardware.org/?probe=2485632618) | Mar 02, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [9acee9d7d4](https://linux-hardware.org/?probe=9acee9d7d4) | Mar 02, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [fedd6483cd](https://linux-hardware.org/?probe=fedd6483cd) | Mar 01, 2023 |
| ASUSTek       | V241DA                      | All in one  | [0779deca8b](https://linux-hardware.org/?probe=0779deca8b) | Feb 28, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [4c3b90ede8](https://linux-hardware.org/?probe=4c3b90ede8) | Feb 28, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [ee0c530562](https://linux-hardware.org/?probe=ee0c530562) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d6eb6b4839](https://linux-hardware.org/?probe=d6eb6b4839) | Feb 28, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [98eee7b827](https://linux-hardware.org/?probe=98eee7b827) | Feb 28, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [dbb3e73c89](https://linux-hardware.org/?probe=dbb3e73c89) | Feb 27, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b116afe451](https://linux-hardware.org/?probe=b116afe451) | Feb 27, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [8fe15f2f2b](https://linux-hardware.org/?probe=8fe15f2f2b) | Feb 22, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [f511e61852](https://linux-hardware.org/?probe=f511e61852) | Feb 21, 2023 |
| Lenovo        | ThinkCentre M91p 4524PL4    | Desktop     | [5cda5522e8](https://linux-hardware.org/?probe=5cda5522e8) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [eec6e2f905](https://linux-hardware.org/?probe=eec6e2f905) | Feb 21, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [e3156cc208](https://linux-hardware.org/?probe=e3156cc208) | Feb 20, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [243ef00f70](https://linux-hardware.org/?probe=243ef00f70) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [10e9491ee4](https://linux-hardware.org/?probe=10e9491ee4) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [a3b352975c](https://linux-hardware.org/?probe=a3b352975c) | Feb 17, 2023 |
| HP            | 18E7                        | Desktop     | [2c779d2395](https://linux-hardware.org/?probe=2c779d2395) | Feb 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [4d9144193f](https://linux-hardware.org/?probe=4d9144193f) | Feb 17, 2023 |
| iRU           | v1.0                        | Desktop     | [9d70818485](https://linux-hardware.org/?probe=9d70818485) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [9de0373acc](https://linux-hardware.org/?probe=9de0373acc) | Feb 16, 2023 |
| Lenovo        | 31A7 NOK                    | Mini pc     | [17f1e0f135](https://linux-hardware.org/?probe=17f1e0f135) | Feb 16, 2023 |
| iRU           | P231                        | All in one  | [4aa7858493](https://linux-hardware.org/?probe=4aa7858493) | Feb 14, 2023 |
| ICL           | H410SB                      | Desktop     | [e994f10643](https://linux-hardware.org/?probe=e994f10643) | Feb 14, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [aab30259f8](https://linux-hardware.org/?probe=aab30259f8) | Feb 13, 2023 |
| HP            | 895F                        | All in one  | [0c23df771f](https://linux-hardware.org/?probe=0c23df771f) | Feb 13, 2023 |
| Acer          | Aspire C27-1655             | All in one  | [4fe6ca7f88](https://linux-hardware.org/?probe=4fe6ca7f88) | Feb 13, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [2512d8d9ab](https://linux-hardware.org/?probe=2512d8d9ab) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [09073fcfc8](https://linux-hardware.org/?probe=09073fcfc8) | Feb 10, 2023 |
| HP            | G62                         | Notebook    | [8bc9454fb1](https://linux-hardware.org/?probe=8bc9454fb1) | Feb 10, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [dea6a1a077](https://linux-hardware.org/?probe=dea6a1a077) | Feb 09, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d3b63de821](https://linux-hardware.org/?probe=d3b63de821) | Feb 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4bc9beae71](https://linux-hardware.org/?probe=4bc9beae71) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a2172caf56](https://linux-hardware.org/?probe=a2172caf56) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [77faeb6b52](https://linux-hardware.org/?probe=77faeb6b52) | Feb 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [395b6fa893](https://linux-hardware.org/?probe=395b6fa893) | Feb 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [eb37d7677c](https://linux-hardware.org/?probe=eb37d7677c) | Feb 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [b306f4c9dc](https://linux-hardware.org/?probe=b306f4c9dc) | Feb 06, 2023 |
| Compal        | DIP00                       | Desktop     | [fc6de899ba](https://linux-hardware.org/?probe=fc6de899ba) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [bb0481d7a8](https://linux-hardware.org/?probe=bb0481d7a8) | Feb 06, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [b2fec94855](https://linux-hardware.org/?probe=b2fec94855) | Feb 05, 2023 |
| HP            | 8599                        | Desktop     | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [c53133f306](https://linux-hardware.org/?probe=c53133f306) | Jan 31, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [9721d24c04](https://linux-hardware.org/?probe=9721d24c04) | Jan 31, 2023 |
| HP            | 8599                        | Desktop     | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| Intel         | S2600WFT H48104-854         | Server      | [68791b3635](https://linux-hardware.org/?probe=68791b3635) | Jan 30, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | Desktop     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | Desktop     | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [87c61b6748](https://linux-hardware.org/?probe=87c61b6748) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [186aef8e0c](https://linux-hardware.org/?probe=186aef8e0c) | Jan 24, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| HP            | 18E4                        | Desktop     | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [a74a5b3b7b](https://linux-hardware.org/?probe=a74a5b3b7b) | Jan 20, 2023 |
| ASUSTek       | V241FA                      | All in one  | [24ed481783](https://linux-hardware.org/?probe=24ed481783) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8472d89767](https://linux-hardware.org/?probe=8472d89767) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7d95709d81](https://linux-hardware.org/?probe=7d95709d81) | Jan 19, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [03c97b653e](https://linux-hardware.org/?probe=03c97b653e) | Jan 18, 2023 |
| NCI           | PC BLICK101                 | Soc         | [018eb0b0bb](https://linux-hardware.org/?probe=018eb0b0bb) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [35cae36101](https://linux-hardware.org/?probe=35cae36101) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Unknown       | T310D11                     | Desktop     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [aea58aa72f](https://linux-hardware.org/?probe=aea58aa72f) | Jan 16, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| HP            | 82DC 1000                   | All in one  | [12c8c204ff](https://linux-hardware.org/?probe=12c8c204ff) | Dec 30, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a05251fd39](https://linux-hardware.org/?probe=a05251fd39) | Dec 29, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [fe79eba13b](https://linux-hardware.org/?probe=fe79eba13b) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| HP            | 895F                        | All in one  | [670e3fa0fa](https://linux-hardware.org/?probe=670e3fa0fa) | Dec 26, 2022 |
| HP            | Notebook                    | Notebook    | [10dfda9549](https://linux-hardware.org/?probe=10dfda9549) | Dec 24, 2022 |
| HP            | 895F                        | All in one  | [8e512dfec4](https://linux-hardware.org/?probe=8e512dfec4) | Dec 23, 2022 |
| HP            | 895F                        | All in one  | [0360aa0d07](https://linux-hardware.org/?probe=0360aa0d07) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| DEPO Compu... | DPH410S                     | Desktop     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [4c1ad2ea2e](https://linux-hardware.org/?probe=4c1ad2ea2e) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [a199d930ff](https://linux-hardware.org/?probe=a199d930ff) | Dec 18, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [20ce0a7f23](https://linux-hardware.org/?probe=20ce0a7f23) | Dec 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | Desktop     | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| ASUSTek       | PB62                        | Desktop     | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| ASUSTek       | PB62                        | Desktop     | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [6cedae9702](https://linux-hardware.org/?probe=6cedae9702) | Dec 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [311f47baef](https://linux-hardware.org/?probe=311f47baef) | Dec 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [79a0f9e73a](https://linux-hardware.org/?probe=79a0f9e73a) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c1cd524970](https://linux-hardware.org/?probe=c1cd524970) | Dec 08, 2022 |
| Aquarius      | NS685U R11                  | Notebook    | [c0dff8c525](https://linux-hardware.org/?probe=c0dff8c525) | Dec 08, 2022 |
| Lenovo        | 10088                       | All in one  | [5fe857bab3](https://linux-hardware.org/?probe=5fe857bab3) | Dec 07, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [b8c52ae5cb](https://linux-hardware.org/?probe=b8c52ae5cb) | Dec 06, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [0cd3371014](https://linux-hardware.org/?probe=0cd3371014) | Dec 05, 2022 |
| MSI           | Sword 15 A12UE              | Notebook    | [32df733b5e](https://linux-hardware.org/?probe=32df733b5e) | Dec 04, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| HP            | 84EE 1100                   | All in one  | [7efea8ad7f](https://linux-hardware.org/?probe=7efea8ad7f) | Dec 01, 2022 |
| Lenovo        | Aptio CRB No DPK            | Mini pc     | [eeddc09936](https://linux-hardware.org/?probe=eeddc09936) | Nov 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ddb1791ff6](https://linux-hardware.org/?probe=ddb1791ff6) | Nov 28, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d9ae3d1795](https://linux-hardware.org/?probe=d9ae3d1795) | Nov 27, 2022 |
| Gigabyte      | X570S UD                    | Desktop     | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| Lenovo        | 31900059 STD                | All in one  | [812cce763f](https://linux-hardware.org/?probe=812cce763f) | Nov 25, 2022 |
| Lenovo        | 31900059 STD                | All in one  | [bfe8939ffc](https://linux-hardware.org/?probe=bfe8939ffc) | Nov 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ff3d0a1ecf](https://linux-hardware.org/?probe=ff3d0a1ecf) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [f86569d54b](https://linux-hardware.org/?probe=f86569d54b) | Nov 24, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [a54f42b51e](https://linux-hardware.org/?probe=a54f42b51e) | Nov 18, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [faa0deab8f](https://linux-hardware.org/?probe=faa0deab8f) | Nov 18, 2022 |
| Unknown       | P43Twins1600                | Desktop     | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| HP            | 2179                        | Desktop     | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| Lenovo        | ThinkPad X220 4290RB3       | Notebook    | [37959973aa](https://linux-hardware.org/?probe=37959973aa) | Nov 11, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3fd33e6782](https://linux-hardware.org/?probe=3fd33e6782) | Nov 09, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [e525d01069](https://linux-hardware.org/?probe=e525d01069) | Nov 08, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [b74787fe62](https://linux-hardware.org/?probe=b74787fe62) | Nov 08, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [63f5fe9444](https://linux-hardware.org/?probe=63f5fe9444) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [dba14315ca](https://linux-hardware.org/?probe=dba14315ca) | Nov 03, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [4776ed964f](https://linux-hardware.org/?probe=4776ed964f) | Nov 03, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [2c20efc0df](https://linux-hardware.org/?probe=2c20efc0df) | Nov 03, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | Desktop     | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | Desktop     | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| Lenovo        | 3708 NOK                    | Desktop     | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [4887ba4bfa](https://linux-hardware.org/?probe=4887ba4bfa) | Oct 21, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | Desktop     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [39838b7f39](https://linux-hardware.org/?probe=39838b7f39) | Oct 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [1011557c31](https://linux-hardware.org/?probe=1011557c31) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [f81210f730](https://linux-hardware.org/?probe=f81210f730) | Oct 18, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [7fa3948164](https://linux-hardware.org/?probe=7fa3948164) | Oct 17, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| HP            | 1495                        | Desktop     | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [97b57f8628](https://linux-hardware.org/?probe=97b57f8628) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [f74f853f54](https://linux-hardware.org/?probe=f74f853f54) | Oct 12, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| MSI           | H55M-E33                    | Desktop     | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASUSTek       | X540NV                      | Notebook    | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | Desktop     | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Lenovo        | 32E4 NOK                    | Mini pc     | [f49f7ba847](https://linux-hardware.org/?probe=f49f7ba847) | Oct 03, 2022 |
| Digma         | EVE 11 C408                 | Notebook    | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| ASRock        | B360M-HDV                   | Desktop     | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| RDW           | MB-B450M V.1                | Desktop     | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [0b610b66a9](https://linux-hardware.org/?probe=0b610b66a9) | Sep 20, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | Desktop     | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [713797403a](https://linux-hardware.org/?probe=713797403a) | Sep 09, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [af9694cea8](https://linux-hardware.org/?probe=af9694cea8) | Sep 06, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [03f14a115d](https://linux-hardware.org/?probe=03f14a115d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| MSI           | FX610                       | Notebook    | [a822818a58](https://linux-hardware.org/?probe=a822818a58) | Sep 03, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | Desktop     | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [e25ed534c0](https://linux-hardware.org/?probe=e25ed534c0) | Aug 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [a42c4dc65a](https://linux-hardware.org/?probe=a42c4dc65a) | Aug 09, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Digma         | EVE 15 P417 ES5063EW        | Notebook    | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [3bfcedd5c8](https://linux-hardware.org/?probe=3bfcedd5c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [c49282206c](https://linux-hardware.org/?probe=c49282206c) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d598c4587d](https://linux-hardware.org/?probe=d598c4587d) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [5b1e962751](https://linux-hardware.org/?probe=5b1e962751) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4e120b3b63](https://linux-hardware.org/?probe=4e120b3b63) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [2d5bedf224](https://linux-hardware.org/?probe=2d5bedf224) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [297ce5144e](https://linux-hardware.org/?probe=297ce5144e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [84b7cd1115](https://linux-hardware.org/?probe=84b7cd1115) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [a92b6c5d73](https://linux-hardware.org/?probe=a92b6c5d73) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [51ebd271c8](https://linux-hardware.org/?probe=51ebd271c8) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [44ad7f7d47](https://linux-hardware.org/?probe=44ad7f7d47) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [49068a26b5](https://linux-hardware.org/?probe=49068a26b5) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [62ce596bf3](https://linux-hardware.org/?probe=62ce596bf3) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [812db8ad6f](https://linux-hardware.org/?probe=812db8ad6f) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d4c2b5ffad](https://linux-hardware.org/?probe=d4c2b5ffad) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4c0179b60e](https://linux-hardware.org/?probe=4c0179b60e) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8601888983](https://linux-hardware.org/?probe=8601888983) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [1d505390d6](https://linux-hardware.org/?probe=1d505390d6) | Jul 22, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [5b3340311a](https://linux-hardware.org/?probe=5b3340311a) | Jul 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [154c254eac](https://linux-hardware.org/?probe=154c254eac) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [60921a7ff6](https://linux-hardware.org/?probe=60921a7ff6) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [c24f8b4ba6](https://linux-hardware.org/?probe=c24f8b4ba6) | Jul 19, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [4f1a1bfb2d](https://linux-hardware.org/?probe=4f1a1bfb2d) | Jul 19, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [fe971bb8c3](https://linux-hardware.org/?probe=fe971bb8c3) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2835672840](https://linux-hardware.org/?probe=2835672840) | Jul 07, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| Aquarius      | NS685U                      | Notebook    | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| ICL           | Unknown                     | Notebook    | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| iRU           | v1.0                        | Mini pc     | [845212ce42](https://linux-hardware.org/?probe=845212ce42) | Jun 02, 2022 |
| iRU           | v1.0                        | Mini pc     | [15b125fb9e](https://linux-hardware.org/?probe=15b125fb9e) | May 31, 2022 |
| iRU           | v1.0                        | Mini pc     | [991e061d78](https://linux-hardware.org/?probe=991e061d78) | May 31, 2022 |
| MSI           | A520M PRO                   | Desktop     | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | Desktop     | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | Desktop     | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| ASUSTek       | V241IC-R                    | All in one  | [48add8dc01](https://linux-hardware.org/?probe=48add8dc01) | May 19, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| mtech         | MTL1578                     | Notebook    | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [eefe92e281](https://linux-hardware.org/?probe=eefe92e281) | May 04, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| Aquarius      | NS585 R32                   | Notebook    | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e76e5359b7](https://linux-hardware.org/?probe=e76e5359b7) | Mar 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | Notebook    | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | All in one  | [4d3df118f0](https://linux-hardware.org/?probe=4d3df118f0) | Mar 01, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [bf51c93832](https://linux-hardware.org/?probe=bf51c93832) | Feb 22, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [a831ba5c10](https://linux-hardware.org/?probe=a831ba5c10) | Feb 22, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ICL           | RAYbook Si1514              | Notebook    | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| ASRock        | H470M-HDV                   | Desktop     | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | H110-PLUS                   | Desktop     | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | Desktop     | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| Pegatron      | A35                         | Notebook    | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Red OS 7.3.1 | 99        | 38.82%  |
| Red OS 7.3   | 81        | 31.76%  |
| Red OS 7.3.2 | 67        | 26.27%  |
| Red OS 7.2   | 8         | 3.14%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Red OS | 239       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 54        | 19.93%  |
| 5.15.72-1.el7.3.x86_64 | 36        | 13.28%  |
| 5.10.29-1.el7.x86_64   | 32        | 11.81%  |
| 5.15.87-1.el7.3.x86_64 | 24        | 8.86%   |
| 5.15.35-5.el7.3.x86_64 | 24        | 8.86%   |
| 5.15.35-4.el7.3.x86_64 | 19        | 7.01%   |
| 5.15.78-2.el7.3.x86_64 | 18        | 6.64%   |
| 5.15.35-1.el7.3.x86_64 | 16        | 5.9%    |
| 5.14.9-1.el7.x86_64    | 7         | 2.58%   |
| 5.10.29-3.el7.x86_64   | 7         | 2.58%   |
| 4.19.79-1.el7.x86_64   | 6         | 2.21%   |
| 5.15.10-2.el7.x86_64   | 5         | 1.85%   |
| 5.15.10-3.el7.x86_64   | 4         | 1.48%   |
| 5.10.1-1.el7.x86_64    | 4         | 1.48%   |
| 5.10.24-2.el7.x86_64   | 3         | 1.11%   |
| 6.1.11-1.el7.3.x86_64  | 2         | 0.74%   |
| 5.18.1-1.el7.x86_64    | 2         | 0.74%   |
| 5.15.10-4.el7.x86_64   | 2         | 0.74%   |
| 5.4.197-1.el7.aarch64  | 1         | 0.37%   |
| 5.13.15-1.el7.x86_64   | 1         | 0.37%   |
| 5.10.24-3.el7.x86_64   | 1         | 0.37%   |
| 5.10.24-1.el7.x86_64   | 1         | 0.37%   |
| 4.19.56-2.el7.x86_64   | 1         | 0.37%   |
| 4.19.204-1.el7.x86_64  | 1         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.10  | 65        | 24.34%  |
| 5.15.35  | 55        | 20.6%   |
| 5.10.29  | 39        | 14.61%  |
| 5.15.72  | 36        | 13.48%  |
| 5.15.87  | 24        | 8.99%   |
| 5.15.78  | 18        | 6.74%   |
| 5.14.9   | 7         | 2.62%   |
| 4.19.79  | 6         | 2.25%   |
| 5.10.24  | 5         | 1.87%   |
| 5.10.1   | 4         | 1.5%    |
| 6.1.11   | 2         | 0.75%   |
| 5.18.1   | 2         | 0.75%   |
| 5.4.197  | 1         | 0.37%   |
| 5.13.15  | 1         | 0.37%   |
| 4.19.56  | 1         | 0.37%   |
| 4.19.204 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 182       | 72.8%   |
| 5.10    | 47        | 18.8%   |
| 4.19    | 8         | 3.2%    |
| 5.14    | 7         | 2.8%    |
| 6.1     | 2         | 0.8%    |
| 5.18    | 2         | 0.8%    |
| 5.4     | 1         | 0.4%    |
| 5.13    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 238       | 99.58%  |
| aarch64 | 1         | 0.42%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 203       | 82.19%  |
| Cinnamon   | 38        | 15.38%  |
| X-Cinnamon | 3         | 1.21%   |
| Unknown    | 3         | 1.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 227       | 93.03%  |
| Wayland | 12        | 4.92%   |
| Tty     | 4         | 1.64%   |
| Unknown | 1         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 229       | 94.63%  |
| Unknown | 6         | 2.48%   |
| SDDM    | 5         | 2.07%   |
| LightDM | 2         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 189       | 76.52%  |
| ru_RU   | 56        | 22.67%  |
| en_US   | 2         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 181       | 74.18%  |
| BIOS | 63        | 25.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 234       | 97.1%   |
| Btrfs   | 5         | 2.07%   |
| Overlay | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 183       | 75.62%  |
| MBR     | 55        | 22.73%  |
| Unknown | 4         | 1.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 218       | 90.08%  |
| Yes       | 24        | 9.92%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 187       | 76.64%  |
| Yes       | 57        | 23.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 50        | 20.92%  |
| Gigabyte Technology            | 36        | 15.06%  |
| ASUSTek Computer               | 31        | 12.97%  |
| Hewlett-Packard                | 20        | 8.37%   |
| ASRock                         | 16        | 6.69%   |
| MSI                            | 14        | 5.86%   |
| Aquarius                       | 10        | 4.18%   |
| DEPO Computers                 | 7         | 2.93%   |
| ICL                            | 6         | 2.51%   |
| iRU                            | 4         | 1.67%   |
| Intel                          | 4         | 1.67%   |
| HUAWEI                         | 4         | 1.67%   |
| Graviton                       | 4         | 1.67%   |
| Digma                          | 4         | 1.67%   |
| Acer                           | 4         | 1.67%   |
| Kraftway                       | 3         | 1.26%   |
| Unknown                        | 3         | 1.26%   |
| IP3 Technology                 | 2         | 0.84%   |
| 3Logic Group                   | 2         | 0.84%   |
| YADRO                          | 1         | 0.42%   |
| THUNDEROBOT                    | 1         | 0.42%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.42%   |
| RDW                            | 1         | 0.42%   |
| Quanta                         | 1         | 0.42%   |
| Pegatron                       | 1         | 0.42%   |
| NCI                            | 1         | 0.42%   |
| mtech                          | 1         | 0.42%   |
| HONOR                          | 1         | 0.42%   |
| Foxconn                        | 1         | 0.42%   |
| ECS                            | 1         | 0.42%   |
| Dell                           | 1         | 0.42%   |
| Compal                         | 1         | 0.42%   |
| Colorful Technology            | 1         | 0.42%   |
| Biostar                        | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE             | 17        | 7.11%   |
| Gigabyte B365M DS3H             | 5         | 2.09%   |
| DEPO Computers DPH310T          | 4         | 1.67%   |
| Unknown                         | 4         | 1.67%   |
| Kraftway ACCORD                 | 3         | 1.26%   |
| ICL RAYbook Si1512              | 3         | 1.26%   |
| HP Laptop 15s-eq1xxx            | 3         | 1.26%   |
| Graviton M52i                   | 3         | 1.26%   |
| Gigabyte H110M-S2               | 3         | 1.26%   |
| ASRock H61M-DGS                 | 3         | 1.26%   |
| ASRock H510M-HVS R2.0           | 3         | 1.26%   |
| MSI MS-7D14                     | 2         | 0.84%   |
| Lenovo ThinkBook 15 G3 ACL 21A4 | 2         | 0.84%   |
| iRU P2320P                      | 2         | 0.84%   |
| IP3 ACN30                       | 2         | 0.84%   |
| Intel D945GNT AAC96315-405      | 2         | 0.84%   |
| Gigabyte B560M DS3H             | 2         | 0.84%   |
| Gigabyte B550 AORUS ELITE V2    | 2         | 0.84%   |
| DEPO Computers DPH410S          | 2         | 0.84%   |
| ASUS PRIME H510T2/CSM           | 2         | 0.84%   |
| ASUS PC                         | 2         | 0.84%   |
| ASUS MINIPC PB62                | 2         | 0.84%   |
| ASUS All Series                 | 2         | 0.84%   |
| Aquarius P30 K44 R53            | 2         | 0.84%   |
| Aquarius AQB560M                | 2         | 0.84%   |
| YADRO VEGMAN S220 Server        | 1         | 0.42%   |
| THUNDEROBOT 911AirD             | 1         | 0.42%   |
| Shanghai Zhaoxin ZXE CRB        | 1         | 0.42%   |
| RDW RDW-MB-B450M V.1            | 1         | 0.42%   |
| Quanta 120-1104er               | 1         | 0.42%   |
| Pegatron A35                    | 1         | 0.42%   |
| NCI PC BLICK101                 | 1         | 0.42%   |
| mtech MTL1578                   | 1         | 0.42%   |
| MSI Sword 15 A12UE              | 1         | 0.42%   |
| MSI MS-7D48                     | 1         | 0.42%   |
| MSI MS-7D46                     | 1         | 0.42%   |
| MSI MS-7D35                     | 1         | 0.42%   |
| MSI MS-7D22                     | 1         | 0.42%   |
| MSI MS-7B86                     | 1         | 0.42%   |
| MSI MS-7636                     | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo V15-IWL         | 17        | 7.11%   |
| Lenovo ThinkCentre     | 10        | 4.18%   |
| ASUS PRIME             | 9         | 3.77%   |
| Lenovo IdeaPad         | 8         | 3.35%   |
| Gigabyte B365M         | 6         | 2.51%   |
| Gigabyte B560M         | 5         | 2.09%   |
| Lenovo ThinkPad        | 4         | 1.67%   |
| Lenovo ThinkBook       | 4         | 1.67%   |
| ICL RAYbook            | 4         | 1.67%   |
| HP Laptop              | 4         | 1.67%   |
| DEPO Computers DPH310T | 4         | 1.67%   |
| Unknown                | 4         | 1.67%   |
| Lenovo IdeaCentre      | 3         | 1.26%   |
| Kraftway ACCORD        | 3         | 1.26%   |
| HP Pavilion            | 3         | 1.26%   |
| Graviton M52i          | 3         | 1.26%   |
| Gigabyte H110M-S2      | 3         | 1.26%   |
| Gigabyte B550          | 3         | 1.26%   |
| Digma EVE              | 3         | 1.26%   |
| ASRock H61M-DGS        | 3         | 1.26%   |
| ASRock H510M-HVS       | 3         | 1.26%   |
| Acer Aspire            | 3         | 1.26%   |
| MSI MS-7D14            | 2         | 0.84%   |
| iRU P2320P             | 2         | 0.84%   |
| IP3 ACN30              | 2         | 0.84%   |
| Intel D945GNT          | 2         | 0.84%   |
| HP ProOne              | 2         | 0.84%   |
| HP ProDesk             | 2         | 0.84%   |
| HP Compaq              | 2         | 0.84%   |
| Gigabyte H410M         | 2         | 0.84%   |
| DEPO Computers DPH410S | 2         | 0.84%   |
| ASUS PC                | 2         | 0.84%   |
| ASUS MINIPC            | 2         | 0.84%   |
| ASUS All               | 2         | 0.84%   |
| Aquarius Pro           | 2         | 0.84%   |
| Aquarius P30           | 2         | 0.84%   |
| Aquarius NS685U        | 2         | 0.84%   |
| Aquarius AQB560M       | 2         | 0.84%   |
| YADRO VEGMAN           | 1         | 0.42%   |
| THUNDEROBOT 911AirD    | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 62        | 25.94%  |
| 2019 | 44        | 18.41%  |
| 2020 | 30        | 12.55%  |
| 2022 | 28        | 11.72%  |
| 2018 | 13        | 5.44%   |
| 2012 | 11        | 4.6%    |
| 2011 | 9         | 3.77%   |
| 2016 | 7         | 2.93%   |
| 2013 | 7         | 2.93%   |
| 2010 | 7         | 2.93%   |
| 2007 | 5         | 2.09%   |
| 2015 | 4         | 1.67%   |
| 2017 | 3         | 1.26%   |
| 2014 | 3         | 1.26%   |
| 2009 | 3         | 1.26%   |
| 2006 | 2         | 0.84%   |
| 2008 | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 127       | 53.14%  |
| Notebook       | 81        | 33.89%  |
| All in one     | 17        | 7.11%   |
| Mini pc        | 10        | 4.18%   |
| Server         | 2         | 0.84%   |
| System on chip | 1         | 0.42%   |
| Tablet         | 1         | 0.42%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 238       | 99.58%  |
| Enabled  | 1         | 0.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 239       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 113       | 47.28%  |
| 16.01-24.0      | 47        | 19.67%  |
| 3.01-4.0        | 31        | 12.97%  |
| 8.01-16.0       | 26        | 10.88%  |
| 32.01-64.0      | 6         | 2.51%   |
| 1.01-2.0        | 6         | 2.51%   |
| 2.01-3.0        | 4         | 1.67%   |
| More than 256.0 | 2         | 0.84%   |
| 24.01-32.0      | 2         | 0.84%   |
| 0.51-1.0        | 1         | 0.42%   |
| Unknown         | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 133       | 51.95%  |
| 2.01-3.0    | 41        | 16.02%  |
| 0.51-1.0    | 30        | 11.72%  |
| 3.01-4.0    | 24        | 9.38%   |
| 4.01-8.0    | 18        | 7.03%   |
| 8.01-16.0   | 6         | 2.34%   |
| 0.01-0.5    | 2         | 0.78%   |
| 64.01-256.0 | 1         | 0.39%   |
| Unknown     | 1         | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 185       | 74.9%   |
| 2      | 44        | 17.81%  |
| 3      | 10        | 4.05%   |
| 4      | 3         | 1.21%   |
| 12     | 1         | 0.4%    |
| 11     | 1         | 0.4%    |
| 7      | 1         | 0.4%    |
| 5      | 1         | 0.4%    |
| 0      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 174       | 72.2%   |
| Yes       | 67        | 27.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 86.61%  |
| No        | 32        | 13.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 57.44%  |
| No        | 103       | 42.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 52.7%   |
| Yes       | 114       | 47.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 238       | 99.58%  |
| Ukraine | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Moscow          | 43        | 17.62%  |
| Salekhard       | 42        | 17.21%  |
| Murom           | 38        | 15.57%  |
| Krasnodar       | 10        | 4.1%    |
| Yekaterinburg   | 7         | 2.87%   |
| Perm            | 6         | 2.46%   |
| Novy Urengoy    | 6         | 2.46%   |
| Baksan          | 5         | 2.05%   |
| Shakhtersk      | 4         | 1.64%   |
| Ryazan          | 4         | 1.64%   |
| Novosibirsk     | 4         | 1.64%   |
| Khabarovsk      | 4         | 1.64%   |
| Balashikha      | 4         | 1.64%   |
| Vladimir        | 3         | 1.23%   |
| Veliky Novgorod | 3         | 1.23%   |
| St Petersburg   | 3         | 1.23%   |
| Samara          | 3         | 1.23%   |
| Muromskiy       | 3         | 1.23%   |
| Labytnangi      | 3         | 1.23%   |
| Kursk           | 3         | 1.23%   |
| Kaluga          | 3         | 1.23%   |
| Ulyanovsk       | 2         | 0.82%   |
| Svetlograd      | 2         | 0.82%   |
| Penza           | 2         | 0.82%   |
| Kurgan          | 2         | 0.82%   |
| Krasnoyarsk     | 2         | 0.82%   |
| Kol'chugino     | 2         | 0.82%   |
| Yaroslavl       | 1         | 0.41%   |
| Yakutsk         | 1         | 0.41%   |
| Voronezh        | 1         | 0.41%   |
| Volgograd       | 1         | 0.41%   |
| Tver            | 1         | 0.41%   |
| Tomsk           | 1         | 0.41%   |
| Surgut          | 1         | 0.41%   |
| Strezhevoy      | 1         | 0.41%   |
| Stavropol       | 1         | 0.41%   |
| Seversk         | 1         | 0.41%   |
| Sevastopol      | 1         | 0.41%   |
| Saratov         | 1         | 0.41%   |
| Rostov-on-Don   | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 50        | 68     | 16.34%  |
| Samsung Electronics          | 40        | 61     | 13.07%  |
| WDC                          | 38        | 47     | 12.42%  |
| Toshiba                      | 23        | 36     | 7.52%   |
| Kingston                     | 18        | 19     | 5.88%   |
| A-DATA Technology            | 18        | 19     | 5.88%   |
| SK hynix                     | 10        | 12     | 3.27%   |
| Foxline                      | 9         | 9      | 2.94%   |
| Apacer                       | 8         | 9      | 2.61%   |
| SanDisk                      | 6         | 9      | 1.96%   |
| Intel                        | 6         | 12     | 1.96%   |
| Hitachi                      | 5         | 5      | 1.63%   |
| Crucial                      | 5         | 8      | 1.63%   |
| AGI                          | 5         | 5      | 1.63%   |
| Unknown                      | 5         | 6      | 1.63%   |
| UMIS                         | 4         | 4      | 1.31%   |
| Phison                       | 4         | 4      | 1.31%   |
| Patriot                      | 4         | 4      | 1.31%   |
| KingSpec                     | 4         | 4      | 1.31%   |
| HGST                         | 4         | 4      | 1.31%   |
| Unknown                      | 3         | 3      | 0.98%   |
| Transcend                    | 3         | 3      | 0.98%   |
| Silicon Motion               | 3         | 3      | 0.98%   |
| Micron Technology            | 3         | 6      | 0.98%   |
| ExeGate                      | 3         | 4      | 0.98%   |
| Qumo                         | 2         | 2      | 0.65%   |
| KIOXIA-EXCERIA               | 2         | 2      | 0.65%   |
| Gigabyte Technology          | 2         | 2      | 0.65%   |
| China                        | 2         | 2      | 0.65%   |
| AMD                          | 2         | 2      | 0.65%   |
| XPG                          | 1         | 1      | 0.33%   |
| SPCC Sol                     | 1         | 1      | 0.33%   |
| SPCC                         | 1         | 1      | 0.33%   |
| Smartbuy                     | 1         | 1      | 0.33%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.33%   |
| Plextor                      | 1         | 1      | 0.33%   |
| Netac                        | 1         | 1      | 0.33%   |
| LIO-ORG                      | 1         | 1      | 0.33%   |
| Lenovo                       | 1         | 16     | 0.33%   |
| Kimtigo                      | 1         | 2      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 18        | 5.66%   |
| Seagate ST500DM002-1BD142 500GB        | 9         | 2.83%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 2.52%   |
| Toshiba HDWD110 1TB                    | 7         | 2.2%    |
| Seagate ST1000LM049-2GH172 1TB         | 6         | 1.89%   |
| Seagate ST1000DM010-2EP102 1TB         | 6         | 1.89%   |
| Foxline FLSSD256M80E13TCX5 256GB       | 5         | 1.57%   |
| AGI AGI512G16AI198 512GB               | 5         | 1.57%   |
| Unknown                                | 5         | 1.57%   |
| Toshiba DT01ACA100 1TB                 | 4         | 1.26%   |
| Apacer AS2280P4 256GB                  | 4         | 1.26%   |
| Seagate ST3160811AS 160GB              | 3         | 0.94%   |
| Seagate ST1000DM010-2DM162 1TB         | 3         | 0.94%   |
| SanDisk SD8SBAT256G1122 256GB SSD      | 3         | 0.94%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.94%   |
| Kingston SA400S37120G 120GB SSD        | 3         | 0.94%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 0.94%   |
| A-DATA SX6000PNP 256GB                 | 3         | 0.94%   |
| A-DATA SU800 256GB SSD                 | 3         | 0.94%   |
| A-DATA SU650 240GB SSD                 | 3         | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.63%   |
| WDC WD10EZEX-22MFCA0 1TB               | 2         | 0.63%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 0.63%   |
| UMIS RPIRJ256VME2MWD 256GB             | 2         | 0.63%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.63%   |
| Toshiba MK5075GSX 500GB                | 2         | 0.63%   |
| Toshiba HDWD105 500GB                  | 2         | 0.63%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 0.63%   |
| SK hynix PC711 HFS512GDE9X073N 512GB   | 2         | 0.63%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 2         | 0.63%   |
| Seagate ST1000DM003-1SB10C 1TB         | 2         | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB           | 2         | 0.63%   |
| Samsung MZVLQ256HAJD-000H1 256GB       | 2         | 0.63%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 0.63%   |
| KIOXIA-EXCERIA SATA SSD 480GB          | 2         | 0.63%   |
| Kingston OM8PCP3512F-A02 512GB         | 2         | 0.63%   |
| KingSpec NT-256 256GB SSD              | 2         | 0.63%   |
| Intel SSDSC2KI512G8 512GB              | 2         | 0.63%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB       | 2         | 0.63%   |
| Foxline FLSSD240X5SE 240GB             | 2         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 67     | 45.37%  |
| WDC                 | 26        | 34     | 24.07%  |
| Toshiba             | 19        | 31     | 17.59%  |
| Hitachi             | 5         | 5      | 4.63%   |
| HGST                | 4         | 4      | 3.7%    |
| Samsung Electronics | 3         | 4      | 2.78%   |
| LIO-ORG             | 1         | 1      | 0.93%   |
| Lenovo              | 1         | 16     | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 14     | 15.91%  |
| A-DATA Technology   | 12        | 12     | 13.64%  |
| Samsung Electronics | 6         | 14     | 6.82%   |
| WDC                 | 5         | 5      | 5.68%   |
| SanDisk             | 5         | 8      | 5.68%   |
| KingSpec            | 4         | 4      | 4.55%   |
| Intel               | 4         | 10     | 4.55%   |
| Foxline             | 4         | 4      | 4.55%   |
| Crucial             | 4         | 7      | 4.55%   |
| Apacer              | 4         | 5      | 4.55%   |
| Transcend           | 3         | 3      | 3.41%   |
| Patriot             | 3         | 3      | 3.41%   |
| ExeGate             | 3         | 4      | 3.41%   |
| Qumo                | 2         | 2      | 2.27%   |
| KIOXIA-EXCERIA      | 2         | 2      | 2.27%   |
| China               | 2         | 2      | 2.27%   |
| Toshiba             | 1         | 1      | 1.14%   |
| SPCC Sol            | 1         | 1      | 1.14%   |
| Smartbuy            | 1         | 1      | 1.14%   |
| Seagate             | 1         | 1      | 1.14%   |
| Plextor             | 1         | 1      | 1.14%   |
| Micron Technology   | 1         | 1      | 1.14%   |
| JMicron Technology  | 1         | 1      | 1.14%   |
| GOODRAM             | 1         | 1      | 1.14%   |
| Dahua               | 1         | 1      | 1.14%   |
| AMD                 | 1         | 1      | 1.14%   |
| Unknown             | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 101       | 125    | 34.71%  |
| HDD     | 99        | 162    | 34.02%  |
| SSD     | 84        | 110    | 28.87%  |
| MMC     | 6         | 7      | 2.06%   |
| Unknown | 1         | 1      | 0.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 155       | 268    | 58.27%  |
| NVMe | 101       | 125    | 37.97%  |
| MMC  | 6         | 7      | 2.26%   |
| SAS  | 4         | 5      | 1.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 111       | 143    | 59.04%  |
| 0.51-1.0   | 63        | 89     | 33.51%  |
| 1.01-2.0   | 8         | 26     | 4.26%   |
| 3.01-4.0   | 4         | 8      | 2.13%   |
| 2.01-3.0   | 1         | 1      | 0.53%   |
| 4.01-10.0  | 1         | 5      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 107       | 43.15%  |
| 251-500        | 56        | 22.58%  |
| 501-1000       | 41        | 16.53%  |
| 1001-2000      | 15        | 6.05%   |
| 51-100         | 14        | 5.65%   |
| 2001-3000      | 5         | 2.02%   |
| 21-50          | 4         | 1.61%   |
| 1-20           | 3         | 1.21%   |
| More than 3000 | 2         | 0.81%   |
| Unknown        | 1         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 160       | 62.75%  |
| 21-50          | 41        | 16.08%  |
| 101-250        | 15        | 5.88%   |
| 501-1000       | 12        | 4.71%   |
| 51-100         | 12        | 4.71%   |
| 251-500        | 7         | 2.75%   |
| 1001-2000      | 4         | 1.57%   |
| More than 3000 | 2         | 0.78%   |
| 2001-3000      | 1         | 0.39%   |
| Unknown        | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 6         | 7      | 16.22%  |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 5.41%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 6      | 5.41%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 1      | 2.7%    |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 2      | 2.7%    |
| WDC WD5000AAKS-00D2B0 500GB         | 1         | 1      | 2.7%    |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 2.7%    |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 2.7%    |
| WDC WD10EZEX-75ZF5A0 1TB            | 1         | 2      | 2.7%    |
| WDC WD10EZEX-00WN4A0 1TB            | 1         | 1      | 2.7%    |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 2.7%    |
| Toshiba MQ01ABF050 500GB            | 1         | 7      | 2.7%    |
| Toshiba MK5075GSX 500GB             | 1         | 1      | 2.7%    |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 2.7%    |
| SPCC M.2 PCIe SSD 512GB             | 1         | 1      | 2.7%    |
| Seagate ST9500423AS 500GB           | 1         | 1      | 2.7%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 2.7%    |
| Seagate ST3500413AS 500GB           | 1         | 1      | 2.7%    |
| Seagate ST3250823AS 250GB           | 1         | 1      | 2.7%    |
| Seagate ST3250318AS 250GB           | 1         | 1      | 2.7%    |
| Seagate ST3160811AS 160GB           | 1         | 1      | 2.7%    |
| Samsung Electronics HD400LJ 400GB   | 1         | 1      | 2.7%    |
| Kingston SUV400S37120G 120GB SSD    | 1         | 1      | 2.7%    |
| Kingston SHPM2280P2H 240G SSD       | 1         | 1      | 2.7%    |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 2.7%    |
| Hitachi HDS5C1050CLA382 500GB       | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 2.7%    |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 2.7%    |
| Unknown                             | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 20     | 41.67%  |
| WDC                 | 10        | 12     | 27.78%  |
| Toshiba             | 2         | 9      | 5.56%   |
| Kingston            | 2         | 2      | 5.56%   |
| Hitachi             | 2         | 2      | 5.56%   |
| SPCC                | 1         | 1      | 2.78%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |
| Unknown             | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 20     | 51.72%  |
| WDC                 | 8         | 10     | 27.59%  |
| Toshiba             | 2         | 9      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |
| Samsung Electronics | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 43     | 81.25%  |
| SSD  | 5         | 6      | 15.63%  |
| NVMe | 1         | 1      | 3.13%   |

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
| Works    | 211       | 334    | 82.42%  |
| Malfunc  | 32        | 50     | 12.5%   |
| Detected | 13        | 21     | 5.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 190       | 57.58%  |
| Samsung Electronics          | 32        | 9.7%    |
| AMD                          | 29        | 8.79%   |
| Phison Electronics           | 16        | 4.85%   |
| SK hynix                     | 10        | 3.03%   |
| Silicon Motion               | 9         | 2.73%   |
| SanDisk                      | 8         | 2.42%   |
| Realtek Semiconductor        | 6         | 1.82%   |
| Kingston Technology Company  | 5         | 1.52%   |
| Union Memory (Shenzhen)      | 4         | 1.21%   |
| Toshiba America Info Systems | 3         | 0.91%   |
| Nvidia                       | 3         | 0.91%   |
| ShenZhen TIGO Semiconductor  | 2         | 0.61%   |
| Micron Technology            | 2         | 0.61%   |
| JMicron Technology           | 2         | 0.61%   |
| ADATA Technology             | 2         | 0.61%   |
| Zhaoxin                      | 1         | 0.3%    |
| VIA Technologies             | 1         | 0.3%    |
| Shenzhen Longsys Electronics | 1         | 0.3%    |
| Netac Technology             | 1         | 0.3%    |
| Micron/Crucial Technology    | 1         | 0.3%    |
| MAXIO Technology (Hangzhou)  | 1         | 0.3%    |
| LSI Logic / Symbios Logic    | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 34        | 9.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 29        | 7.99%   |
| Samsung NVMe SSD Controller 980                                                | 27        | 7.44%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 4.68%   |
| Phison PS5013 E13 NVMe Controller                                              | 14        | 3.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 14        | 3.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 11        | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 2.75%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 10        | 2.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 9         | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 2.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 6         | 1.65%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.65%   |
| Realtek NVMe Controller                                                        | 5         | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 1.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.83%   |
| Nvidia MCP61 SATA Controller                                                   | 3         | 0.83%   |
| Nvidia MCP61 IDE                                                               | 3         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.83%   |
| Union Memory (Shenzhen) NVMe 256G SSD device                                   | 2         | 0.55%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.55%   |
| ShenZhen TIGO Non-Volatile memory controller                                   | 2         | 0.55%   |
| SanDisk NVMe Controller                                                        | 2         | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.55%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.55%   |
| Micron NVMe Storage Controller                                                 | 2         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 200       | 60.06%  |
| NVMe | 101       | 30.33%  |
| IDE  | 23        | 6.91%   |
| RAID | 8         | 2.4%    |
| SAS  | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 196       | 82.01%  |
| AMD          | 41        | 17.15%  |
| CentaurHauls | 1         | 0.42%   |
| ARM          | 1         | 0.42%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 7.53%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 14        | 5.86%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 12        | 5.02%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 7         | 2.93%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 2.51%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 2.09%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 5         | 2.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.67%   |
| Intel 12th Gen Core i5-12400                  | 4         | 1.67%   |
| Intel 12th Gen Core i3-12100                  | 4         | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.67%   |
| Intel Pentium CPU G4500 @ 3.50GHz             | 3         | 1.26%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 1.26%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 3         | 1.26%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.26%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1.26%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.26%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 1.26%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 1.26%   |
| Intel Pentium 4 CPU 3.06GHz                   | 2         | 0.84%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 2         | 0.84%   |
| Intel Core i5-8400T CPU @ 1.70GHz             | 2         | 0.84%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.84%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 2         | 0.84%   |
| Intel Core i5-10400T CPU @ 2.00GHz            | 2         | 0.84%   |
| Intel Core i3-8100T CPU @ 3.10GHz             | 2         | 0.84%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 0.84%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.84%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz        | 2         | 0.84%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2         | 0.84%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.84%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 2         | 0.84%   |
| AMD Ryzen 3 3200GE with Radeon Vega Graphics  | 2         | 0.84%   |
| AMD FX-4100 Quad-Core Processor               | 2         | 0.84%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz          | 1         | 0.42%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz            | 1         | 0.42%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1         | 0.42%   |
| Intel Pentium Gold G7400                      | 1         | 0.42%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 81        | 33.89%  |
| Intel Core i3      | 41        | 17.15%  |
| Other              | 31        | 12.97%  |
| AMD Ryzen 5        | 14        | 5.86%   |
| Intel Celeron      | 13        | 5.44%   |
| AMD Ryzen 3        | 11        | 4.6%    |
| Intel Pentium      | 8         | 3.35%   |
| Intel Core i7      | 8         | 3.35%   |
| Intel Core 2 Duo   | 5         | 2.09%   |
| Intel Pentium Gold | 4         | 1.67%   |
| AMD Ryzen 7        | 3         | 1.26%   |
| AMD FX             | 3         | 1.26%   |
| Intel Pentium 4    | 2         | 0.84%   |
| AMD Ryzen 7 PRO    | 2         | 0.84%   |
| AMD Athlon II X2   | 2         | 0.84%   |
| Intel Xeon Silver  | 1         | 0.42%   |
| Intel Xeon Gold    | 1         | 0.42%   |
| Intel Xeon         | 1         | 0.42%   |
| Intel Pentium Dual | 1         | 0.42%   |
| Intel Core 2       | 1         | 0.42%   |
| AMD Ryzen 9        | 1         | 0.42%   |
| AMD Ryzen 5 PRO    | 1         | 0.42%   |
| AMD Ryzen 3 PRO    | 1         | 0.42%   |
| AMD Phenom II      | 1         | 0.42%   |
| AMD Phenom         | 1         | 0.42%   |
| AMD Athlon         | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 115       | 48.12%  |
| 2      | 52        | 21.76%  |
| 6      | 48        | 20.08%  |
| 8      | 11        | 4.6%    |
| 12     | 4         | 1.67%   |
| 1      | 3         | 1.26%   |
| 3      | 2         | 0.84%   |
| 36     | 1         | 0.42%   |
| 24     | 1         | 0.42%   |
| 14     | 1         | 0.42%   |
| 10     | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 237       | 99.16%  |
| 2      | 2         | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 157       | 65.69%  |
| 1      | 82        | 34.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 238       | 99.58%  |
| Unknown        | 1         | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0xa0653    | 35        | 14.52%  |
| 0x806ec    | 20        | 8.3%    |
| 0x806ea    | 11        | 4.56%   |
| 0x906ed    | 10        | 4.15%   |
| 0x906ea    | 10        | 4.15%   |
| 0x206a7    | 10        | 4.15%   |
| 0x90675    | 9         | 3.73%   |
| 0x506e3    | 9         | 3.73%   |
| 0x806c1    | 8         | 3.32%   |
| 0x306c3    | 8         | 3.32%   |
| 0x306a9    | 8         | 3.32%   |
| 0x08600106 | 8         | 3.32%   |
| 0x08108109 | 7         | 2.9%    |
| 0x906eb    | 5         | 2.07%   |
| 0x0a50000c | 5         | 2.07%   |
| Unknown    | 5         | 2.07%   |
| 0xa0671    | 4         | 1.66%   |
| 0x906e9    | 4         | 1.66%   |
| 0xa0655    | 3         | 1.24%   |
| 0x906a3    | 3         | 1.24%   |
| 0x706a8    | 3         | 1.24%   |
| 0x1067a    | 3         | 1.24%   |
| 0x0a50000d | 3         | 1.24%   |
| 0x08608103 | 3         | 1.24%   |
| 0xf49      | 2         | 0.83%   |
| 0x906a4    | 2         | 0.83%   |
| 0x90672    | 2         | 0.83%   |
| 0x806d1    | 2         | 0.83%   |
| 0x6fd      | 2         | 0.83%   |
| 0x506ca    | 2         | 0.83%   |
| 0x506c9    | 2         | 0.83%   |
| 0x50657    | 2         | 0.83%   |
| 0x406c4    | 2         | 0.83%   |
| 0x40651    | 2         | 0.83%   |
| 0x20652    | 2         | 0.83%   |
| 0x08108102 | 2         | 0.83%   |
| 0x0600063e | 2         | 0.83%   |
| 0x010000c8 | 2         | 0.83%   |
| 0xa0654    | 1         | 0.41%   |
| 0x806eb    | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 62        | 25.94%  |
| CometLake        | 39        | 16.32%  |
| Alderlake Hybrid | 15        | 6.28%   |
| Skylake          | 12        | 5.02%   |
| Zen+             | 10        | 4.18%   |
| Zen 2            | 10        | 4.18%   |
| SandyBridge      | 10        | 4.18%   |
| Haswell          | 10        | 4.18%   |
| Zen 3            | 9         | 3.77%   |
| Unknown          | 9         | 3.77%   |
| TigerLake        | 8         | 3.35%   |
| IvyBridge        | 8         | 3.35%   |
| Core             | 5         | 2.09%   |
| K10              | 4         | 1.67%   |
| IceLake          | 4         | 1.67%   |
| Goldmont         | 4         | 1.67%   |
| Westmere         | 3         | 1.26%   |
| Penryn           | 3         | 1.26%   |
| Goldmont plus    | 3         | 1.26%   |
| Zen              | 2         | 0.84%   |
| Silvermont       | 2         | 0.84%   |
| NetBurst         | 2         | 0.84%   |
| Nehalem          | 2         | 0.84%   |
| Bulldozer        | 2         | 0.84%   |
| Piledriver       | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 176       | 67.69%  |
| AMD               | 46        | 17.69%  |
| Nvidia            | 35        | 13.46%  |
| ASPEED Technology | 2         | 0.77%   |
| Zhaoxin           | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 34        | 12.88%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20        | 7.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 7.2%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 11        | 4.17%   |
| AMD Renoir                                                                               | 9         | 3.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 3.41%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 8         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.27%   |
| Intel HD Graphics 530                                                                    | 6         | 2.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.89%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.52%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.14%   |
| Intel HD Graphics 630                                                                    | 3         | 1.14%   |
| Intel HD Graphics 500                                                                    | 3         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.14%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.14%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 3         | 1.14%   |
| AMD Lucienne                                                                             | 3         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 2         | 0.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 2         | 0.76%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 0.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.76%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.76%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.76%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.38%   |
| Nvidia TU117M [GeForce MX550]                                                            | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 156       | 65.27%  |
| 1 x AMD        | 37        | 15.48%  |
| 1 x Nvidia     | 19        | 7.95%   |
| Intel + Nvidia | 14        | 5.86%   |
| Intel + AMD    | 4         | 1.67%   |
| 2 x AMD        | 3         | 1.26%   |
| 1 x ASPEED     | 2         | 0.84%   |
| AMD + Nvidia   | 2         | 0.84%   |
| Other          | 1         | 0.42%   |
| 1 x Zhaoxin    | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 195       | 80.58%  |
| Unknown     | 40        | 16.53%  |
| Proprietary | 7         | 2.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 71.07%  |
| 1.01-2.0   | 28        | 11.57%  |
| 0.01-0.5   | 18        | 7.44%   |
| 0.51-1.0   | 14        | 5.79%   |
| 3.01-4.0   | 8         | 3.31%   |
| 7.01-8.0   | 1         | 0.41%   |
| 2.01-3.0   | 1         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 40        | 18.18%  |
| Samsung Electronics  | 29        | 13.18%  |
| Philips              | 20        | 9.09%   |
| Acer                 | 14        | 6.36%   |
| ViewSonic            | 13        | 5.91%   |
| LG Display           | 11        | 5%      |
| Chimei Innolux       | 9         | 4.09%   |
| Hewlett-Packard      | 8         | 3.64%   |
| BenQ                 | 8         | 3.64%   |
| AU Optronics         | 8         | 3.64%   |
| Lenovo               | 7         | 3.18%   |
| Goldstar             | 7         | 3.18%   |
| AOC                  | 7         | 3.18%   |
| Dell                 | 5         | 2.27%   |
| ASUSTek Computer     | 5         | 2.27%   |
| SGT                  | 3         | 1.36%   |
| PANDA                | 3         | 1.36%   |
| Ancor Communications | 3         | 1.36%   |
| SKM                  | 2         | 0.91%   |
| NLE                  | 2         | 0.91%   |
| Iiyama               | 2         | 0.91%   |
| HUAWEI               | 2         | 0.91%   |
| XSP                  | 1         | 0.45%   |
| WYT                  | 1         | 0.45%   |
| Toshiba              | 1         | 0.45%   |
| Sony                 | 1         | 0.45%   |
| RGT                  | 1         | 0.45%   |
| OOO                  | 1         | 0.45%   |
| JRY                  | 1         | 0.45%   |
| ITE                  | 1         | 0.45%   |
| DOY                  | 1         | 0.45%   |
| Daewoo               | 1         | 0.45%   |
| CHR                  | 1         | 0.45%   |
| CHD                  | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 17        | 7.52%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 9         | 3.98%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x195mm 15.6-inch                | 9         | 3.98%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch            | 5         | 2.21%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                      | 3         | 1.33%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 3         | 1.33%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch              | 3         | 1.33%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch         | 3         | 1.33%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                  | 3         | 1.33%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch     | 3         | 1.33%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 3         | 1.33%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 3         | 1.33%   |
| AU Optronics LCD Monitor AUO0100 1920x1080                           | 3         | 1.33%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch        | 2         | 0.88%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch        | 2         | 0.88%   |
| SKM LCD Monitor SKM9322 1920x1080 527x296mm 23.8-inch                | 2         | 0.88%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 2         | 0.88%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch    | 2         | 0.88%   |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch    | 2         | 0.88%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                    | 2         | 0.88%   |
| Lenovo TIO22Gen4 LEN111A 1920x1080 476x268mm 21.5-inch               | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.88%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                     | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.88%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 2         | 0.88%   |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                    | 2         | 0.88%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                    | 2         | 0.88%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                   | 2         | 0.88%   |
| XSP Digital XSP2380 1920x1080 520x310mm 23.8-inch                    | 1         | 0.44%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                 | 1         | 0.44%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                 | 1         | 0.44%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch        | 1         | 0.44%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch           | 1         | 0.44%   |
| ViewSonic PJ VSC9B34 1920x1080                                       | 1         | 0.44%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch             | 1         | 0.44%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM02A0 1280x1024 376x301mm 19.0-inch | 1         | 0.44%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch    | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 148       | 71.15%  |
| 1280x1024 (SXGA)  | 13        | 6.25%   |
| 1366x768 (WXGA)   | 12        | 5.77%   |
| 2560x1440 (QHD)   | 10        | 4.81%   |
| 1600x900 (HD+)    | 10        | 4.81%   |
| 3840x2160 (4K)    | 4         | 1.92%   |
| 1920x1200 (WUXGA) | 3         | 1.44%   |
| 3440x1440         | 1         | 0.48%   |
| 2560x1080         | 1         | 0.48%   |
| 2240x1400         | 1         | 0.48%   |
| 1600x1200         | 1         | 0.48%   |
| 1440x900 (WXGA+)  | 1         | 0.48%   |
| 1280x960          | 1         | 0.48%   |
| 1280x800 (WXGA)   | 1         | 0.48%   |
| 1024x768 (XGA)    | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 64        | 28.96%  |
| 24      | 32        | 14.48%  |
| 23      | 32        | 14.48%  |
| 21      | 21        | 9.5%    |
| 27      | 14        | 6.33%   |
| 20      | 10        | 4.52%   |
| 19      | 8         | 3.62%   |
| 17      | 8         | 3.62%   |
| 31      | 4         | 1.81%   |
| 13      | 4         | 1.81%   |
| Unknown | 4         | 1.81%   |
| 18      | 3         | 1.36%   |
| 84      | 2         | 0.9%    |
| 40      | 2         | 0.9%    |
| 25      | 2         | 0.9%    |
| 14      | 2         | 0.9%    |
| 12      | 2         | 0.9%    |
| 54      | 1         | 0.45%   |
| 34      | 1         | 0.45%   |
| 32      | 1         | 0.45%   |
| 26      | 1         | 0.45%   |
| 22      | 1         | 0.45%   |
| 16      | 1         | 0.45%   |
| 11      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 76        | 35.51%  |
| 301-350     | 76        | 35.51%  |
| 401-500     | 33        | 15.42%  |
| 351-400     | 11        | 5.14%   |
| 601-700     | 4         | 1.87%   |
| Unknown     | 4         | 1.87%   |
| 201-300     | 3         | 1.4%    |
| 701-800     | 2         | 0.93%   |
| 1501-2000   | 2         | 0.93%   |
| 901-1000    | 2         | 0.93%   |
| 1001-1500   | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 176       | 86.27%  |
| 5/4   | 13        | 6.37%   |
| 16/10 | 9         | 4.41%   |
| 21/9  | 3         | 1.47%   |
| 4/3   | 2         | 0.98%   |
| 6/5   | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 70        | 32.56%  |
| 101-110        | 64        | 29.77%  |
| 151-200        | 25        | 11.63%  |
| 301-350        | 15        | 6.98%   |
| 141-150        | 7         | 3.26%   |
| 81-90          | 6         | 2.79%   |
| 351-500        | 6         | 2.79%   |
| 251-300        | 6         | 2.79%   |
| Unknown        | 4         | 1.86%   |
| More than 1000 | 3         | 1.4%    |
| 121-130        | 3         | 1.4%    |
| 61-70          | 2         | 0.93%   |
| 501-1000       | 2         | 0.93%   |
| 51-60          | 1         | 0.47%   |
| 131-140        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 97        | 46.86%  |
| 121-160 | 63        | 30.43%  |
| 101-120 | 40        | 19.32%  |
| Unknown | 4         | 1.93%   |
| 161-240 | 2         | 0.97%   |
| 1-50    | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 180       | 72.87%  |
| 0     | 46        | 18.62%  |
| 2     | 21        | 8.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 164       | 53.25%  |
| Intel                    | 93        | 30.19%  |
| Qualcomm Atheros         | 9         | 2.92%   |
| Broadcom                 | 7         | 2.27%   |
| TP-Link                  | 5         | 1.62%   |
| MediaTek                 | 5         | 1.62%   |
| Samsung Electronics      | 4         | 1.3%    |
| Ralink Technology        | 3         | 0.97%   |
| Ralink                   | 3         | 0.97%   |
| Nvidia                   | 3         | 0.97%   |
| Mercucys                 | 2         | 0.65%   |
| Xiaomi                   | 1         | 0.32%   |
| VIA Technologies         | 1         | 0.32%   |
| OPPO Electronics         | 1         | 0.32%   |
| OKB SAPR                 | 1         | 0.32%   |
| Metrologic Instruments   | 1         | 0.32%   |
| Mellanox Technologies    | 1         | 0.32%   |
| Marvell Technology Group | 1         | 0.32%   |
| Huawei Technologies      | 1         | 0.32%   |
| Edimax Technology        | 1         | 0.32%   |
| ASIX Electronics         | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 114       | 30.48%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 32        | 8.56%   |
| Intel Wireless 7265                                               | 12        | 3.21%   |
| Intel Ethernet Controller I225-V                                  | 10        | 2.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8         | 2.14%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 2.14%   |
| Intel Ethernet Connection (14) I219-V                             | 8         | 2.14%   |
| Intel Ethernet Connection (17) I219-V                             | 7         | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 1.6%    |
| Intel Wireless 3165                                               | 6         | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 1.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.07%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 0.8%    |
| Realtek 802.11ac NIC                                              | 3         | 0.8%    |
| Nvidia MCP61 Ethernet                                             | 3         | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.8%    |
| Intel NM10/ICH7 Family LAN Controller                             | 3         | 0.8%    |
| Intel Ethernet Connection (11) I219-V                             | 3         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3         | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.8%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.53%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.53%   |
| Mercucys 802.11n NIC                                              | 2         | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.53%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.53%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 63        | 43.45%  |
| Intel                 | 55        | 37.93%  |
| Qualcomm Atheros      | 6         | 4.14%   |
| Broadcom              | 5         | 3.45%   |
| TP-Link               | 4         | 2.76%   |
| Ralink Technology     | 3         | 2.07%   |
| Ralink                | 3         | 2.07%   |
| MediaTek              | 3         | 2.07%   |
| Mercucys              | 2         | 1.38%   |
| Edimax Technology     | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 32        | 21.77%  |
| Intel Wireless 7265                                           | 12        | 8.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 8         | 5.44%   |
| Intel Wireless 3165                                           | 6         | 4.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 3.4%    |
| Intel Wi-Fi 6 AX201                                           | 5         | 3.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                              | 5         | 3.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 4         | 2.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 4         | 2.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 3         | 2.04%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 3         | 2.04%   |
| Realtek 802.11ac NIC                                          | 3         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                | 3         | 2.04%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 3         | 2.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 2         | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 1.36%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 2         | 1.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 1.36%   |
| Mercucys 802.11n NIC                                          | 2         | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.36%   |
| Intel Wireless 8265 / 8275                                    | 2         | 1.36%   |
| Intel Wi-Fi 6 AX200                                           | 2         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                 | 2         | 1.36%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.68%   |
| TP-Link 802.11n NIC                                           | 1         | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.68%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 129       | 58.64%  |
| Intel                    | 68        | 30.91%  |
| Samsung Electronics      | 4         | 1.82%   |
| Qualcomm Atheros         | 3         | 1.36%   |
| Nvidia                   | 3         | 1.36%   |
| MediaTek                 | 2         | 0.91%   |
| Broadcom                 | 2         | 0.91%   |
| Xiaomi                   | 1         | 0.45%   |
| VIA Technologies         | 1         | 0.45%   |
| TP-Link                  | 1         | 0.45%   |
| OPPO Electronics         | 1         | 0.45%   |
| OKB SAPR                 | 1         | 0.45%   |
| Mellanox Technologies    | 1         | 0.45%   |
| Marvell Technology Group | 1         | 0.45%   |
| Huawei Technologies      | 1         | 0.45%   |
| ASIX Electronics         | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 114       | 50.44%  |
| Intel Ethernet Controller I225-V                                  | 10        | 4.42%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 3.54%   |
| Intel Ethernet Connection (14) I219-V                             | 8         | 3.54%   |
| Intel Ethernet Connection (17) I219-V                             | 7         | 3.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.77%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.33%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.33%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3         | 1.33%   |
| Intel Ethernet Connection (11) I219-V                             | 3         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.33%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.88%   |
| Intel Ethernet Controller I225-LM                                 | 2         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.88%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.88%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.44%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.44%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.44%   |
| OPPO RMX3263                                                      | 1         | 0.44%   |
| OKB SAPR Ethernet controller                                      | 1         | 0.44%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 0.44%   |
| MediaTek U318AA                                                   | 1         | 0.44%   |
| MediaTek KINGKONG_MINI                                            | 1         | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.44%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 0.44%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1         | 0.44%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 207       | 59.65%  |
| WiFi     | 139       | 40.06%  |
| Modem    | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 174       | 71.9%   |
| WiFi     | 68        | 28.1%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 137       | 57.32%  |
| 2     | 94        | 39.33%  |
| 0     | 5         | 2.09%   |
| 4     | 2         | 0.84%   |
| 7     | 1         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 233       | 96.68%  |
| Yes  | 8         | 3.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 45.61%  |
| Realtek Semiconductor           | 36        | 31.58%  |
| IMC Networks                    | 6         | 5.26%   |
| Broadcom                        | 6         | 5.26%   |
| Cambridge Silicon Radio         | 3         | 2.63%   |
| Realtek                         | 2         | 1.75%   |
| Ralink                          | 2         | 1.75%   |
| Qualcomm Atheros Communications | 2         | 1.75%   |
| TP-Link                         | 1         | 0.88%   |
| MediaTek                        | 1         | 0.88%   |
| Lite-On Technology              | 1         | 0.88%   |
| Foxconn / Hon Hai               | 1         | 0.88%   |
| ASUSTek Computer                | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 32        | 28.07%  |
| Intel Bluetooth wireless interface                  | 24        | 21.05%  |
| Intel AX201 Bluetooth                               | 14        | 12.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 6.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.51%   |
| Intel Bluetooth Device                              | 4         | 3.51%   |
| IMC Networks Bluetooth Radio                        | 4         | 3.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.63%   |
| Realtek Bluetooth Radio                             | 2         | 1.75%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.75%   |
| Intel AX200 Bluetooth                               | 2         | 1.75%   |
| IMC Networks Bluetooth Device                       | 2         | 1.75%   |
| TP-Link UB500 Adapter                               | 1         | 0.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.88%   |
| MediaTek Wireless_Device                            | 1         | 0.88%   |
| Lite-On Wireless_Device                             | 1         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.88%   |
| Broadcom HP Portable Valentine                      | 1         | 0.88%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.88%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.88%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 194       | 69.29%  |
| AMD                  | 46        | 16.43%  |
| Nvidia               | 25        | 8.93%   |
| Texas Instruments    | 3         | 1.07%   |
| Lenovo               | 3         | 1.07%   |
| C-Media Electronics  | 3         | 1.07%   |
| Logitech             | 2         | 0.71%   |
| Zhaoxin              | 1         | 0.36%   |
| Razer USA            | 1         | 0.36%   |
| MosArt Semiconductor | 1         | 0.36%   |
| Creative Technology  | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 9.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 9.26%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 28        | 8.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 5.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.4%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 11        | 3.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 3.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 3.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.16%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 7         | 2.16%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 1.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.54%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.23%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 3         | 0.93%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 0.93%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Logitech 960 Headset                                                                              | 2         | 0.62%   |
| Lenovo ThinkCentre TIO22Gen4 for USB Audio                                                        | 2         | 0.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 0.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.62%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.62%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 55        | 22%     |
| Crucial                            | 32        | 12.8%   |
| Kingston                           | 24        | 9.6%    |
| Foxline                            | 22        | 8.8%    |
| SK hynix                           | 21        | 8.4%    |
| Unknown                            | 19        | 7.6%    |
| Ramaxel Technology                 | 9         | 3.6%    |
| Micron Technology                  | 8         | 3.2%    |
| Unknown (ABCD)                     | 6         | 2.4%    |
| Apacer                             | 6         | 2.4%    |
| AMD                                | 6         | 2.4%    |
| Patriot                            | 5         | 2%      |
| Elpida                             | 5         | 2%      |
| A-DATA Technology                  | 5         | 2%      |
| Unknown                            | 3         | 1.2%    |
| SHARETRONIC                        | 2         | 0.8%    |
| Qumo                               | 2         | 0.8%    |
| Neo Forza                          | 2         | 0.8%    |
| HomeNet                            | 2         | 0.8%    |
| Corsair                            | 2         | 0.8%    |
| ChangXin Memory                    | 2         | 0.8%    |
| Unknown (BA8A)                     | 1         | 0.4%    |
| Unknown (89F7)                     | 1         | 0.4%    |
| Unknown (0x0080)                   | 1         | 0.4%    |
| Shenzhen Micro Innovation Industry | 1         | 0.4%    |
| King Tiger                         | 1         | 0.4%    |
| Innodisk                           | 1         | 0.4%    |
| GOODRAM                            | 1         | 0.4%    |
| Good Wealth                        | 1         | 0.4%    |
| Goldkey                            | 1         | 0.4%    |
| Golden Empire                      | 1         | 0.4%    |
| Gold Key                           | 1         | 0.4%    |
| <Invalid>                          | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 6.54%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 7         | 2.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 2.31%   |
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s                | 6         | 2.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.15%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 3         | 1.15%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 1.15%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.15%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.15%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.15%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.15%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 1.15%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.15%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 3         | 1.15%   |
| Foxline RAM FL2400D4S17S-8G 8192MB SODIMM DDR4 2400MT/s          | 3         | 1.15%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 3         | 1.15%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                      | 3         | 1.15%   |
| Unknown                                                          | 3         | 1.15%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 2         | 0.77%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.77%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s              | 2         | 0.77%   |
| Ramaxel RAM RMSA3320MR78HAF-3200 8GB SODIMM DDR4 3200MT/s        | 2         | 0.77%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                  | 2         | 0.77%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s            | 2         | 0.77%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 0.77%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s            | 2         | 0.77%   |
| Kingston RAM 9905711-027.A00G 4GB SODIMM DDR4 2667MT/s           | 2         | 0.77%   |
| HomeNet RAM HN SO 8GB 8192MB SODIMM DDR4 3200MT/s                | 2         | 0.77%   |
| Crucial RAM ST51264BA1339.16FK 4GB DIMM DDR3 1067MT/s            | 2         | 0.77%   |
| Crucial RAM CT8G4SFRA32A.C16FG 8GB SODIMM DDR4 3200MT/s          | 2         | 0.77%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s             | 2         | 0.77%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s           | 2         | 0.77%   |
| Crucial RAM CT16G4SFS832A.C8FE 16GB SODIMM DDR4 3200MT/s         | 2         | 0.77%   |
| Apacer RAM D12.2324CH.002 8GB DIMM DDR4 2667MT/s                 | 2         | 0.77%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 175       | 74.79%  |
| DDR3    | 32        | 13.68%  |
| LPDDR4  | 7         | 2.99%   |
| DDR2    | 7         | 2.99%   |
| SDRAM   | 6         | 2.56%   |
| Unknown | 6         | 2.56%   |
| DDR     | 1         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 115       | 48.32%  |
| SODIMM       | 114       | 47.9%   |
| Row Of Chips | 9         | 3.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 132       | 53.23%  |
| 4096  | 57        | 22.98%  |
| 16384 | 23        | 9.27%   |
| 2048  | 19        | 7.66%   |
| 1024  | 10        | 4.03%   |
| 32768 | 5         | 2.02%   |
| 65536 | 1         | 0.4%    |
| 512   | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 75        | 30.74%  |
| 3200    | 59        | 24.18%  |
| 2400    | 20        | 8.2%    |
| 1600    | 14        | 5.74%   |
| 1333    | 13        | 5.33%   |
| 2666    | 8         | 3.28%   |
| 2133    | 6         | 2.46%   |
| 800     | 4         | 1.64%   |
| 3266    | 3         | 1.23%   |
| 2933    | 3         | 1.23%   |
| 2800    | 3         | 1.23%   |
| 1066    | 3         | 1.23%   |
| 667     | 3         | 1.23%   |
| Unknown | 3         | 1.23%   |
| 3466    | 2         | 0.82%   |
| 2934    | 2         | 0.82%   |
| 2866    | 2         | 0.82%   |
| 1866    | 2         | 0.82%   |
| 1334    | 2         | 0.82%   |
| 1067    | 2         | 0.82%   |
| 533     | 2         | 0.82%   |
| 333     | 2         | 0.82%   |
| 4800    | 1         | 0.41%   |
| 3800    | 1         | 0.41%   |
| 3733    | 1         | 0.41%   |
| 3600    | 1         | 0.41%   |
| 3533    | 1         | 0.41%   |
| 3400    | 1         | 0.41%   |
| 3000    | 1         | 0.41%   |
| 2733    | 1         | 0.41%   |
| 1800    | 1         | 0.41%   |
| 1648    | 1         | 0.41%   |
| 400     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Pantum  | 1         | 50%     |
| Kyocera | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Pantum BM5100ADN series | 1         | 50%     |
| Kyocera FS-1040         | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP ScanJet Pro 2000 s2  | 1         | 33.33%  |
| Canon CanoScan LIDE 25  | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 22        | 18.03%  |
| Syntek                                 | 21        | 17.21%  |
| IMC Networks                           | 11        | 9.02%   |
| Alcor Micro                            | 9         | 7.38%   |
| Quanta                                 | 7         | 5.74%   |
| Acer                                   | 7         | 5.74%   |
| SunplusIT                              | 6         | 4.92%   |
| Realtek Semiconductor                  | 6         | 4.92%   |
| Microdia                               | 4         | 3.28%   |
| Luxvisions Innotech Limited            | 3         | 2.46%   |
| Logitech                               | 3         | 2.46%   |
| Z-Star Microelectronics                | 2         | 1.64%   |
| USB Camera CS                          | 2         | 1.64%   |
| Suyin                                  | 2         | 1.64%   |
| Sunplus Innovation Technology          | 2         | 1.64%   |
| Sonix Technology                       | 2         | 1.64%   |
| Hopewin Electronic Material            | 2         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.64%   |
| Bison Electronics                      | 2         | 1.64%   |
| Lite-On Technology                     | 1         | 0.82%   |
| KYE Systems (Mouse Systems)            | 1         | 0.82%   |
| Creative Technology                    | 1         | 0.82%   |
| Arkmicro Technologies                  | 1         | 0.82%   |
| Apple                                  | 1         | 0.82%   |
| AlcorMicroCorp                         | 1         | 0.82%   |
| Unknown                                | 1         | 0.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Syntek Integrated Camera                      | 18        | 14.75%  |
| Chicony USB camera                            | 9         | 7.38%   |
| SunplusIT USB Camera                          | 6         | 4.92%   |
| Alcor Micro USB 2.0 PC Camera                 | 6         | 4.92%   |
| Logitech HD Webcam C615                       | 3         | 2.46%   |
| IMC Networks USB2.0 HD UVC WebCam             | 3         | 2.46%   |
| IMC Networks ov9734_azurewave_camera          | 3         | 2.46%   |
| IMC Networks Integrated Camera                | 3         | 2.46%   |
| Chicony Integrated Camera                     | 3         | 2.46%   |
| Acer Integrated Camera                        | 3         | 2.46%   |
| USB Camera CS USB Camera CS                   | 2         | 1.64%   |
| Sonix USB 2.0 Camera                          | 2         | 1.64%   |
| Realtek 1080p Camera                          | 2         | 1.64%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.64%   |
| Microdia Camera                               | 2         | 1.64%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.64%   |
| Hopewin Electronic Material Integrated Camera | 2         | 1.64%   |
| Chicony HP High Definition 1MP Webcam         | 2         | 1.64%   |
| Chicony HD User Facing                        | 2         | 1.64%   |
| Bison Integrated Camera                       | 2         | 1.64%   |
| Alcor Micro USB FHD Camera                    | 2         | 1.64%   |
| Z-Star Lenovo USB2.0 UVC Camera               | 1         | 0.82%   |
| Z-Star Lenovo IdeaCentre Web Camera           | 1         | 0.82%   |
| Syntek LENOVO LBG 720P CAM                    | 1         | 0.82%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.82%   |
| Syntek Integrated RGB Camera                  | 1         | 0.82%   |
| Suyin HP Truevision HD                        | 1         | 0.82%   |
| Suyin Acer CrystalEye Webcam                  | 1         | 0.82%   |
| Sunplus BKX Usb FHD Camera                    | 1         | 0.82%   |
| Sunplus Asus Webcam                           | 1         | 0.82%   |
| Realtek USB2.0-Camera                         | 1         | 0.82%   |
| Realtek USB2.0 camera                         | 1         | 0.82%   |
| Realtek USB Camera                            | 1         | 0.82%   |
| Realtek HP Truevision HD                      | 1         | 0.82%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 0.82%   |
| Quanta USB HD Webcam                          | 1         | 0.82%   |
| Quanta HP 5MP Camera                          | 1         | 0.82%   |
| Quanta HP 2.0MP High Definition Webcam        | 1         | 0.82%   |
| Quanta HD Camera                              | 1         | 0.82%   |
| Microdia Webcam Vitade AF                     | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 6         | 75%     |
| Synaptics                  | 2         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device | 6         | 75%     |
| Synaptics UWP WBDI Device           | 2         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Aladdin R.D. | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Aladdin R.D. Smart card reader JCR721 | 1         | 50%     |
| Aladdin R.D. JaCarta                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 179       | 73.06%  |
| 1     | 52        | 21.22%  |
| 2     | 10        | 4.08%   |
| 4     | 2         | 0.82%   |
| 3     | 2         | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 42        | 51.85%  |
| Net/wireless             | 13        | 16.05%  |
| Fingerprint reader       | 8         | 9.88%   |
| Communication controller | 5         | 6.17%   |
| Unassigned class         | 3         | 3.7%    |
| Sound                    | 2         | 2.47%   |
| Net/ethernet             | 2         | 2.47%   |
| Bluetooth                | 2         | 2.47%   |
| Network                  | 1         | 1.23%   |
| Multimedia controller    | 1         | 1.23%   |
| Chipcard                 | 1         | 1.23%   |
| Camera                   | 1         | 1.23%   |

