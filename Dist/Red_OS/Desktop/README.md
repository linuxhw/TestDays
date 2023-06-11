Red OS - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 205

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0VNM11 A01                  | [df3c87a033](https://linux-hardware.org/?probe=df3c87a033) | Jun 02, 2023 |
| Dell          | 0VNM11 A01                  | [308b943182](https://linux-hardware.org/?probe=308b943182) | Jun 01, 2023 |
| Gigabyte      | B450 GAMING X               | [b92d2128ad](https://linux-hardware.org/?probe=b92d2128ad) | Jun 01, 2023 |
| Gigabyte      | B560M D3H                   | [8579e0281a](https://linux-hardware.org/?probe=8579e0281a) | May 30, 2023 |
| HP            | 83F0                        | [77cfad8631](https://linux-hardware.org/?probe=77cfad8631) | May 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | [a98cdfee26](https://linux-hardware.org/?probe=a98cdfee26) | May 25, 2023 |
| Gigabyte      | Z77-DS3H                    | [1e1fb2110f](https://linux-hardware.org/?probe=1e1fb2110f) | May 24, 2023 |
| MSI           | H510M-A PRO                 | [c5f452ea28](https://linux-hardware.org/?probe=c5f452ea28) | May 18, 2023 |
| Aquarius      | AQH410T                     | [aeeb40c393](https://linux-hardware.org/?probe=aeeb40c393) | May 04, 2023 |
| Unknown       | Unknown                     | [3522381ca7](https://linux-hardware.org/?probe=3522381ca7) | May 02, 2023 |
| Unknown       | Unknown                     | [4ec0da1442](https://linux-hardware.org/?probe=4ec0da1442) | May 02, 2023 |
| MSI           | A520M PRO                   | [6d37fb0e46](https://linux-hardware.org/?probe=6d37fb0e46) | May 02, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [41d545e4d7](https://linux-hardware.org/?probe=41d545e4d7) | Apr 28, 2023 |
| ASRock        | B365M-ITX/ac                | [e4c8218911](https://linux-hardware.org/?probe=e4c8218911) | Apr 27, 2023 |
| Gigabyte      | B365M H                     | [aca220e594](https://linux-hardware.org/?probe=aca220e594) | Apr 22, 2023 |
| Gigabyte      | H310M S2H x.x               | [eec2055c19](https://linux-hardware.org/?probe=eec2055c19) | Apr 20, 2023 |
| Intel         | DH61BF AAG81311-101         | [a9329736fb](https://linux-hardware.org/?probe=a9329736fb) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | [e2ed275252](https://linux-hardware.org/?probe=e2ed275252) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | [a6aaf5f17a](https://linux-hardware.org/?probe=a6aaf5f17a) | Apr 19, 2023 |
| MSI           | G41M-P33 Combo              | [d2623477d9](https://linux-hardware.org/?probe=d2623477d9) | Apr 10, 2023 |
| Intel         | D945GNT AAC96315-405        | [cdfdfbcda4](https://linux-hardware.org/?probe=cdfdfbcda4) | Apr 07, 2023 |
| Intel         | DH61BF AAG81311-101         | [49921908d1](https://linux-hardware.org/?probe=49921908d1) | Apr 06, 2023 |
| MSI           | PRO Z790-A WIFI             | [5fd883493a](https://linux-hardware.org/?probe=5fd883493a) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | [44b5c81131](https://linux-hardware.org/?probe=44b5c81131) | Apr 03, 2023 |
| Quanta        | 2AC5 100                    | [7f253a82dc](https://linux-hardware.org/?probe=7f253a82dc) | Mar 31, 2023 |
| MSI           | G31TM-P21                   | [7404d94ca4](https://linux-hardware.org/?probe=7404d94ca4) | Mar 31, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [3ad3c5e45c](https://linux-hardware.org/?probe=3ad3c5e45c) | Mar 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [8400d48ed0](https://linux-hardware.org/?probe=8400d48ed0) | Mar 29, 2023 |
| MSI           | G41M-P33 Combo              | [ea8ce90ed5](https://linux-hardware.org/?probe=ea8ce90ed5) | Mar 27, 2023 |
| HP            | 0AA4h                       | [a77b084eba](https://linux-hardware.org/?probe=a77b084eba) | Mar 25, 2023 |
| Intel         | D945GNT AAC96315-405        | [fcc7a18f89](https://linux-hardware.org/?probe=fcc7a18f89) | Mar 24, 2023 |
| DEPO Compu... | MS-7846                     | [baaaef2394](https://linux-hardware.org/?probe=baaaef2394) | Mar 22, 2023 |
| Intel         | D945GNT AAC96315-405        | [58c99c07a6](https://linux-hardware.org/?probe=58c99c07a6) | Mar 17, 2023 |
| Biostar       | H610MH                      | [6b367d747d](https://linux-hardware.org/?probe=6b367d747d) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [9e172b266b](https://linux-hardware.org/?probe=9e172b266b) | Mar 16, 2023 |
| HP            | 0B4Ch D                     | [a26dff699b](https://linux-hardware.org/?probe=a26dff699b) | Mar 14, 2023 |
| ASRock        | H61M-DGS                    | [47b6690dc8](https://linux-hardware.org/?probe=47b6690dc8) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | [7c7bdc15fe](https://linux-hardware.org/?probe=7c7bdc15fe) | Mar 13, 2023 |
| Gigabyte      | B560M AORUS PRO             | [9442ced293](https://linux-hardware.org/?probe=9442ced293) | Mar 09, 2023 |
| HP            | 8599                        | [2b9bd0b4a7](https://linux-hardware.org/?probe=2b9bd0b4a7) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX/1333                | [ccb99906a8](https://linux-hardware.org/?probe=ccb99906a8) | Mar 06, 2023 |
| MSI           | G41M-P33 Combo              | [a78a4114e6](https://linux-hardware.org/?probe=a78a4114e6) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [388d4b38c1](https://linux-hardware.org/?probe=388d4b38c1) | Mar 06, 2023 |
| ASUSTek       | P5GC-MX/1333                | [6d97e48a7e](https://linux-hardware.org/?probe=6d97e48a7e) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [8741c0e2f1](https://linux-hardware.org/?probe=8741c0e2f1) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-K               | [9e1f0243d7](https://linux-hardware.org/?probe=9e1f0243d7) | Mar 06, 2023 |
| Intel         | D945GNT AAC96315-405        | [0d02616013](https://linux-hardware.org/?probe=0d02616013) | Mar 03, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [2485632618](https://linux-hardware.org/?probe=2485632618) | Mar 02, 2023 |
| ASRock        | H510M-HVS R2.0              | [9acee9d7d4](https://linux-hardware.org/?probe=9acee9d7d4) | Mar 02, 2023 |
| Aquarius      | AQB560M                     | [fedd6483cd](https://linux-hardware.org/?probe=fedd6483cd) | Mar 01, 2023 |
| Aquarius      | AQB560M                     | [ee0c530562](https://linux-hardware.org/?probe=ee0c530562) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | [d6eb6b4839](https://linux-hardware.org/?probe=d6eb6b4839) | Feb 28, 2023 |
| Gigabyte      | B365M H                     | [dbb3e73c89](https://linux-hardware.org/?probe=dbb3e73c89) | Feb 27, 2023 |
| Intel         | DH61CR AAG14064-204         | [f511e61852](https://linux-hardware.org/?probe=f511e61852) | Feb 21, 2023 |
| Lenovo        | ThinkCentre M91p 4524PL4    | [5cda5522e8](https://linux-hardware.org/?probe=5cda5522e8) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | [eec6e2f905](https://linux-hardware.org/?probe=eec6e2f905) | Feb 21, 2023 |
| HP            | 18E7                        | [2c779d2395](https://linux-hardware.org/?probe=2c779d2395) | Feb 17, 2023 |
| iRU           | v1.0                        | [9d70818485](https://linux-hardware.org/?probe=9d70818485) | Feb 17, 2023 |
| ICL           | H410SB                      | [e994f10643](https://linux-hardware.org/?probe=e994f10643) | Feb 14, 2023 |
| MSI           | PRO B660M-E DDR4            | [aab30259f8](https://linux-hardware.org/?probe=aab30259f8) | Feb 13, 2023 |
| Gigabyte      | B560M DS3H V2               | [2512d8d9ab](https://linux-hardware.org/?probe=2512d8d9ab) | Feb 10, 2023 |
| MSI           | H510M-A PRO                 | [dea6a1a077](https://linux-hardware.org/?probe=dea6a1a077) | Feb 09, 2023 |
| Gigabyte      | B365M DS3H                  | [4bc9beae71](https://linux-hardware.org/?probe=4bc9beae71) | Feb 07, 2023 |
| Gigabyte      | M61SME-S2                   | [395b6fa893](https://linux-hardware.org/?probe=395b6fa893) | Feb 06, 2023 |
| Lenovo        | 3708 NOK                    | [b306f4c9dc](https://linux-hardware.org/?probe=b306f4c9dc) | Feb 06, 2023 |
| Compal        | DIP00                       | [fc6de899ba](https://linux-hardware.org/?probe=fc6de899ba) | Feb 06, 2023 |
| ASRock        | H61M-VG4                    | [b2fec94855](https://linux-hardware.org/?probe=b2fec94855) | Feb 05, 2023 |
| HP            | 8599                        | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| HP            | 8599                        | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| Gigabyte      | B365M H                     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| DEPO Compu... | DPH410S                     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | H81M-K                      | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| HP            | 18E4                        | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Gigabyte      | H610M S2H DDR4              | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| MSI           | PRO H610M-E DDR4            | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| Unknown       | T310D11                     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Gigabyte      | B360HD3                     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | PRIME B365M-A               | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| DEPO Compu... | DPH410S                     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| MSI           | B450-A PRO MAX              | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Gigabyte      | M61SME-S2                   | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| MSI           | B450-A PRO MAX              | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| ASUSTek       | PB62                        | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| ASUSTek       | PB62                        | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Gigabyte      | B365M DS3H                  | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| ASUSTek       | P7H55-M                     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| ASRock        | H510M-HVS R2.0              | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| Gigabyte      | B365M DS3H                  | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Gigabyte      | X570S UD                    | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| ASUSTek       | PRIME Z590-P                | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| Gigabyte      | B365M DS3H                  | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| Unknown       | P43Twins1600                | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASRock        | H310CM-DVS                  | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| HP            | 2179                        | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| ASRock        | H61M-VG4                    | [63f5fe9444](https://linux-hardware.org/?probe=63f5fe9444) | Nov 04, 2022 |
| Gigabyte      | A520M DS3H                  | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Gigabyte      | B560M H                     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| ASUSTek       | H81M-K                      | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | 3708 NOK                    | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Gigabyte      | H510M S2H                   | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| ASUSTek       | H81M-K                      | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| HP            | 1495                        | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| MSI           | H55M-E33                    | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| ASRock        | B360M-HDV                   | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| RDW           | MB-B450M V.1                | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| Gigabyte      | H110M-S2-CF                 | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Unknown       | Unknown                     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| ASRock        | N68-VS3 FX                  | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| ASRock        | H110M-DVS R2.0              | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Dell          | 040DDP A00                  | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| DEPO Compu... | DPH310T                     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Gigabyte      | 970A-D3                     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| ASUSTek       | M2N68-AM Plus               | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| MSI           | A520M PRO                   | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| Gigabyte      | B365M H                     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| ASUSTek       | H81M-K                      | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASRock        | B560 Pro4                   | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Gigabyte      | B75M-D3V                    | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek       | H110-PLUS                   | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Gigabyte      | B560M DS3H                  | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | PRIME H510M-K               | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| Aquarius      | AQB560M                     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ASRock        | H470M-HDV                   | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| ASUSTek       | H110-PLUS                   | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| Gigabyte      | B365M DS3H                  | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| ASUSTek       | H81M-K                      | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Red OS 7.3   | 57       | 37.01%  |
| Red OS 7.3.1 | 47       | 30.52%  |
| Red OS 7.3.2 | 42       | 27.27%  |
| Red OS 7.2   | 8        | 5.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 145      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.10-1.el7.x86_64   | 26       | 15.95%  |
| 5.10.29-1.el7.x86_64   | 24       | 14.72%  |
| 5.15.87-1.el7.3.x86_64 | 21       | 12.88%  |
| 5.15.35-5.el7.3.x86_64 | 19       | 11.66%  |
| 5.15.72-1.el7.3.x86_64 | 15       | 9.2%    |
| 5.15.78-2.el7.3.x86_64 | 11       | 6.75%   |
| 5.15.35-1.el7.3.x86_64 | 9        | 5.52%   |
| 5.14.9-1.el7.x86_64    | 8        | 4.91%   |
| 5.15.35-4.el7.3.x86_64 | 7        | 4.29%   |
| 4.19.79-1.el7.x86_64   | 6        | 3.68%   |
| 6.1.20-2.el7.3.x86_64  | 3        | 1.84%   |
| 5.15.10-3.el7.x86_64   | 3        | 1.84%   |
| 5.15.10-2.el7.x86_64   | 3        | 1.84%   |
| 5.10.29-3.el7.x86_64   | 2        | 1.23%   |
| 6.1.11-1.el7.3.x86_64  | 1        | 0.61%   |
| 5.10.24-3.el7.x86_64   | 1        | 0.61%   |
| 5.10.24-2.el7.x86_64   | 1        | 0.61%   |
| 5.10.1-1.el7.x86_64    | 1        | 0.61%   |
| 4.19.56-2.el7.x86_64   | 1        | 0.61%   |
| 4.19.204-1.el7.x86_64  | 1        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.35  | 32       | 20%     |
| 5.15.10  | 32       | 20%     |
| 5.10.29  | 26       | 16.25%  |
| 5.15.87  | 21       | 13.13%  |
| 5.15.72  | 15       | 9.38%   |
| 5.15.78  | 11       | 6.88%   |
| 5.14.9   | 8        | 5%      |
| 4.19.79  | 6        | 3.75%   |
| 6.1.20   | 3        | 1.88%   |
| 5.10.24  | 2        | 1.25%   |
| 6.1.11   | 1        | 0.63%   |
| 5.10.1   | 1        | 0.63%   |
| 4.19.56  | 1        | 0.63%   |
| 4.19.204 | 1        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 102      | 67.55%  |
| 5.10    | 29       | 19.21%  |
| 5.14    | 8        | 5.3%    |
| 4.19    | 8        | 5.3%    |
| 6.1     | 4        | 2.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 145      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 120      | 79.47%  |
| Cinnamon   | 24       | 15.89%  |
| X-Cinnamon | 4        | 2.65%   |
| Unknown    | 3        | 1.99%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 136      | 91.89%  |
| Wayland | 6        | 4.05%   |
| Tty     | 4        | 2.7%    |
| Unknown | 2        | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 137      | 93.84%  |
| Unknown | 5        | 3.42%   |
| SDDM    | 2        | 1.37%   |
| LightDM | 2        | 1.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 95       | 63.76%  |
| ru_RU   | 53       | 35.57%  |
| en_US   | 1        | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 95       | 64.19%  |
| BIOS | 53       | 35.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 141      | 96.58%  |
| Btrfs   | 4        | 2.74%   |
| Unknown | 1        | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 95       | 64.63%  |
| MBR     | 49       | 33.33%  |
| Unknown | 3        | 2.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 91.84%  |
| Yes       | 12       | 8.16%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 112      | 76.19%  |
| Yes       | 35       | 23.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 42       | 28.97%  |
| ASUSTek Computer    | 26       | 17.93%  |
| ASRock              | 17       | 11.72%  |
| MSI                 | 14       | 9.66%   |
| Hewlett-Packard     | 8        | 5.52%   |
| DEPO Computers      | 7        | 4.83%   |
| Aquarius            | 7        | 4.83%   |
| Intel               | 5        | 3.45%   |
| Lenovo              | 4        | 2.76%   |
| Unknown             | 4        | 2.76%   |
| Dell                | 2        | 1.38%   |
| RDW                 | 1        | 0.69%   |
| Quanta              | 1        | 0.69%   |
| iRU                 | 1        | 0.69%   |
| ICL                 | 1        | 0.69%   |
| Foxconn             | 1        | 0.69%   |
| ECS                 | 1        | 0.69%   |
| Compal              | 1        | 0.69%   |
| Colorful Technology | 1        | 0.69%   |
| Biostar             | 1        | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Gigabyte B365M DS3H                    | 5        | 3.45%   |
| DEPO Computers DPH310T                 | 4        | 2.76%   |
| Unknown                                | 4        | 2.76%   |
| MSI MS-7D14                            | 3        | 2.07%   |
| Intel D945GNT AAC96315-405             | 3        | 2.07%   |
| Gigabyte H110M-S2                      | 3        | 2.07%   |
| ASRock H61M-DGS                        | 3        | 2.07%   |
| ASRock H510M-HVS R2.0                  | 3        | 2.07%   |
| MSI MS-7D22                            | 2        | 1.38%   |
| Gigabyte B560M DS3H                    | 2        | 1.38%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 1.38%   |
| Gigabyte B365M H                       | 2        | 1.38%   |
| DEPO Computers DPH410S                 | 2        | 1.38%   |
| ASUS PRIME H510T2/CSM                  | 2        | 1.38%   |
| ASUS PRIME H310M-R R2.0                | 2        | 1.38%   |
| ASUS PC                                | 2        | 1.38%   |
| ASUS MINIPC PB62                       | 2        | 1.38%   |
| ASUS All Series                        | 2        | 1.38%   |
| Aquarius P30 K44 R53                   | 2        | 1.38%   |
| Aquarius AQB560M                       | 2        | 1.38%   |
| RDW RDW-MB-B450M V.1                   | 1        | 0.69%   |
| Quanta 120-1104er                      | 1        | 0.69%   |
| MSI MS-7E07                            | 1        | 0.69%   |
| MSI MS-7D48                            | 1        | 0.69%   |
| MSI MS-7D46                            | 1        | 0.69%   |
| MSI MS-7D35                            | 1        | 0.69%   |
| MSI MS-7B86                            | 1        | 0.69%   |
| MSI MS-7636                            | 1        | 0.69%   |
| MSI MS-7592                            | 1        | 0.69%   |
| MSI MS-7529                            | 1        | 0.69%   |
| MSI Compaq dx2300 Microtower           | 1        | 0.69%   |
| Lenovo V50s-07IMB 11EF0011RU           | 1        | 0.69%   |
| Lenovo ThinkCentre M91p 4524PL4        | 1        | 0.69%   |
| Lenovo ThinkCentre M70e 0851RZ3        | 1        | 0.69%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS | 1        | 0.69%   |
| iRU 311                                | 1        | 0.69%   |
| Intel DH61CR AAG14064-204              | 1        | 0.69%   |
| Intel DH61BF AAG81311-101              | 1        | 0.69%   |
| ICL RAY B102                           | 1        | 0.69%   |
| HP Z400 Workstation                    | 1        | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 10       | 6.9%    |
| Gigabyte B365M         | 7        | 4.83%   |
| Gigabyte B560M         | 5        | 3.45%   |
| DEPO Computers DPH310T | 4        | 2.76%   |
| Unknown                | 4        | 2.76%   |
| MSI MS-7D14            | 3        | 2.07%   |
| Intel D945GNT          | 3        | 2.07%   |
| HP ProDesk             | 3        | 2.07%   |
| Gigabyte H110M-S2      | 3        | 2.07%   |
| Gigabyte B550          | 3        | 2.07%   |
| ASRock H61M-DGS        | 3        | 2.07%   |
| ASRock H510M-HVS       | 3        | 2.07%   |
| MSI MS-7D22            | 2        | 1.38%   |
| Lenovo ThinkCentre     | 2        | 1.38%   |
| HP Compaq              | 2        | 1.38%   |
| Gigabyte H410M         | 2        | 1.38%   |
| Gigabyte B450          | 2        | 1.38%   |
| Gigabyte A320M-S2H     | 2        | 1.38%   |
| DEPO Computers DPH410S | 2        | 1.38%   |
| Dell OptiPlex          | 2        | 1.38%   |
| ASUS PC                | 2        | 1.38%   |
| ASUS MINIPC            | 2        | 1.38%   |
| ASUS All               | 2        | 1.38%   |
| Aquarius Pro           | 2        | 1.38%   |
| Aquarius P30           | 2        | 1.38%   |
| Aquarius AQB560M       | 2        | 1.38%   |
| RDW RDW-MB-B450M       | 1        | 0.69%   |
| Quanta 120-1104er      | 1        | 0.69%   |
| MSI MS-7E07            | 1        | 0.69%   |
| MSI MS-7D48            | 1        | 0.69%   |
| MSI MS-7D46            | 1        | 0.69%   |
| MSI MS-7D35            | 1        | 0.69%   |
| MSI MS-7B86            | 1        | 0.69%   |
| MSI MS-7636            | 1        | 0.69%   |
| MSI MS-7592            | 1        | 0.69%   |
| MSI MS-7529            | 1        | 0.69%   |
| MSI Compaq             | 1        | 0.69%   |
| Lenovo V50s-07IMB      | 1        | 0.69%   |
| Lenovo IdeaCentre      | 1        | 0.69%   |
| iRU 311                | 1        | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 35       | 24.14%  |
| 2022 | 17       | 11.72%  |
| 2019 | 16       | 11.03%  |
| 2020 | 14       | 9.66%   |
| 2018 | 11       | 7.59%   |
| 2012 | 9        | 6.21%   |
| 2011 | 7        | 4.83%   |
| 2013 | 6        | 4.14%   |
| 2016 | 5        | 3.45%   |
| 2010 | 5        | 3.45%   |
| 2015 | 4        | 2.76%   |
| 2007 | 4        | 2.76%   |
| 2014 | 3        | 2.07%   |
| 2009 | 3        | 2.07%   |
| 2006 | 3        | 2.07%   |
| 2017 | 2        | 1.38%   |
| 2008 | 1        | 0.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 145      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 144      | 99.31%  |
| Enabled  | 1        | 0.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 145      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 46       | 31.72%  |
| 16.01-24.0 | 42       | 28.97%  |
| 3.01-4.0   | 20       | 13.79%  |
| 8.01-16.0  | 18       | 12.41%  |
| 32.01-64.0 | 7        | 4.83%   |
| 1.01-2.0   | 5        | 3.45%   |
| 2.01-3.0   | 3        | 2.07%   |
| 24.01-32.0 | 2        | 1.38%   |
| 0.51-1.0   | 1        | 0.69%   |
| Unknown    | 1        | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 71       | 45.51%  |
| 2.01-3.0  | 26       | 16.67%  |
| 3.01-4.0  | 17       | 10.9%   |
| 0.51-1.0  | 17       | 10.9%   |
| 4.01-8.0  | 16       | 10.26%  |
| 8.01-16.0 | 6        | 3.85%   |
| 0.01-0.5  | 2        | 1.28%   |
| Unknown   | 1        | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 65.77%  |
| 2      | 40       | 26.85%  |
| 3      | 7        | 4.7%    |
| 4      | 3        | 2.01%   |
| 5      | 1        | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 64.38%  |
| Yes       | 52       | 35.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 144      | 99.31%  |
| No        | 1        | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 75%     |
| Yes       | 37       | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 82.31%  |
| Yes       | 26       | 17.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 145      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 26       | 17.57%  |
| Salekhard         | 22       | 14.86%  |
| Murom             | 22       | 14.86%  |
| Yekaterinburg     | 7        | 4.73%   |
| Zima              | 5        | 3.38%   |
| Perm              | 4        | 2.7%    |
| Novy Urengoy      | 4        | 2.7%    |
| Novosibirsk       | 3        | 2.03%   |
| Krasnodar         | 3        | 2.03%   |
| Balashikha        | 3        | 2.03%   |
| Volgograd         | 2        | 1.35%   |
| Veliky Novgorod   | 2        | 1.35%   |
| Tomsk             | 2        | 1.35%   |
| Stavropol         | 2        | 1.35%   |
| Penza             | 2        | 1.35%   |
| Nal'chik          | 2        | 1.35%   |
| Muromskiy         | 2        | 1.35%   |
| Kurgan            | 2        | 1.35%   |
| Khabarovsk        | 2        | 1.35%   |
| Kaluga            | 2        | 1.35%   |
| Baksan            | 2        | 1.35%   |
| Yuzhno-Sakhalinsk | 1        | 0.68%   |
| Vladimir          | 1        | 0.68%   |
| Ulyanovsk         | 1        | 0.68%   |
| Tyumen            | 1        | 0.68%   |
| Svetlograd        | 1        | 0.68%   |
| Surgut            | 1        | 0.68%   |
| St Petersburg     | 1        | 0.68%   |
| Shakhtersk        | 1        | 0.68%   |
| Rostov-on-Don     | 1        | 0.68%   |
| Pushkino          | 1        | 0.68%   |
| Nyandoma          | 1        | 0.68%   |
| Nyagan            | 1        | 0.68%   |
| Nizhniy Novgorod  | 1        | 0.68%   |
| Nadym             | 1        | 0.68%   |
| Magadan           | 1        | 0.68%   |
| Labytnangi        | 1        | 0.68%   |
| Kursk             | 1        | 0.68%   |
| Kurkimakhi        | 1        | 0.68%   |
| Krasnoyarsk       | 1        | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 46       | 65     | 22.89%  |
| WDC                          | 29       | 36     | 14.43%  |
| Toshiba                      | 21       | 25     | 10.45%  |
| A-DATA Technology            | 14       | 15     | 6.97%   |
| Samsung Electronics          | 13       | 19     | 6.47%   |
| Kingston                     | 13       | 14     | 6.47%   |
| Foxline                      | 6        | 6      | 2.99%   |
| Apacer                       | 6        | 6      | 2.99%   |
| SanDisk                      | 5        | 8      | 2.49%   |
| Hitachi                      | 5        | 5      | 2.49%   |
| Patriot                      | 4        | 4      | 1.99%   |
| KingSpec                     | 4        | 4      | 1.99%   |
| Crucial                      | 4        | 7      | 1.99%   |
| Intel                        | 3        | 3      | 1.49%   |
| ExeGate                      | 3        | 4      | 1.49%   |
| AMD                          | 3        | 3      | 1.49%   |
| AGI                          | 3        | 3      | 1.49%   |
| Qumo                         | 2        | 2      | 1%      |
| KIOXIA-EXCERIA               | 2        | 2      | 1%      |
| China                        | 2        | 2      | 1%      |
| Unknown                      | 2        | 2      | 1%      |
| XPG                          | 1        | 1      | 0.5%    |
| Unknown                      | 1        | 1      | 0.5%    |
| SPCC                         | 1        | 1      | 0.5%    |
| Smartbuy                     | 1        | 1      | 0.5%    |
| Silicon Motion               | 1        | 1      | 0.5%    |
| Shenzhen Longsys Electronics | 1        | 1      | 0.5%    |
| Phison                       | 1        | 1      | 0.5%    |
| Netac                        | 1        | 1      | 0.5%    |
| GOODRAM                      | 1        | 1      | 0.5%    |
| Dahua                        | 1        | 1      | 0.5%    |
| Corsair                      | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                | 10       | 4.78%   |
| Seagate ST500DM002-1BD142 500GB    | 9        | 4.31%   |
| Seagate ST1000DM010-2EP102 1TB     | 7        | 3.35%   |
| Kingston SA400S37240G 240GB SSD    | 5        | 2.39%   |
| Toshiba DT01ACA100 1TB             | 4        | 1.91%   |
| Seagate ST3160811AS 160GB          | 4        | 1.91%   |
| Seagate ST1000LM049-2GH172 1TB     | 4        | 1.91%   |
| Apacer AS2280P4 256GB              | 4        | 1.91%   |
| A-DATA SX6000PNP 256GB             | 4        | 1.91%   |
| Seagate ST1000DM010-2DM162 1TB     | 3        | 1.44%   |
| Kingston SA400S37120G 120GB SSD    | 3        | 1.44%   |
| Crucial CT240BX500SSD1 240GB       | 3        | 1.44%   |
| AGI AGI512G16AI198 512GB           | 3        | 1.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2        | 0.96%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 2        | 0.96%   |
| WDC WD10EZEX-22MFCA0 1TB           | 2        | 0.96%   |
| Toshiba HDWD105 500GB              | 2        | 0.96%   |
| Toshiba DT01ACA050 500GB           | 2        | 0.96%   |
| Seagate ST1000DM003-1SB10C 1TB     | 2        | 0.96%   |
| SanDisk SD8SBAT256G1122 256GB SSD  | 2        | 0.96%   |
| Samsung SSD 970 EVO Plus 1TB       | 2        | 0.96%   |
| Samsung SSD 860 EVO 250GB          | 2        | 0.96%   |
| Patriot Burst Elite 240GB SSD      | 2        | 0.96%   |
| KIOXIA-EXCERIA SATA SSD 480GB      | 2        | 0.96%   |
| Kingston OM8PCP3512F-A02 512GB     | 2        | 0.96%   |
| Foxline FLSSD240X5SE 240GB         | 2        | 0.96%   |
| ExeGate EX276690RUS(960G 960GB SSD | 2        | 0.96%   |
| A-DATA SU800 256GB SSD             | 2        | 0.96%   |
| Unknown                            | 2        | 0.96%   |
| XPG GAMMIX S70 BLADE 2TB           | 1        | 0.48%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1        | 0.48%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 1        | 0.48%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 0.48%   |
| WDC WD5000AAKX-083CA1 500GB        | 1        | 0.48%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1        | 0.48%   |
| WDC WD5000AAKS-00D2B0 500GB        | 1        | 0.48%   |
| WDC WD40PURZ-85TTDY0 4TB           | 1        | 0.48%   |
| WDC WD40PURZ-85AKKY0 4TB           | 1        | 0.48%   |
| WDC WD40PURX-78AKYY0 4TB           | 1        | 0.48%   |
| WDC WD3200AAKX-001CA0 320GB        | 1        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 45       | 64     | 46.88%  |
| WDC                 | 23       | 29     | 23.96%  |
| Toshiba             | 20       | 24     | 20.83%  |
| Hitachi             | 5        | 5      | 5.21%   |
| Samsung Electronics | 3        | 4      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 10       | 10     | 15.63%  |
| A-DATA Technology   | 7        | 7      | 10.94%  |
| Foxline             | 5        | 5      | 7.81%   |
| WDC                 | 4        | 4      | 6.25%   |
| SanDisk             | 4        | 7      | 6.25%   |
| Samsung Electronics | 4        | 6      | 6.25%   |
| KingSpec            | 4        | 4      | 6.25%   |
| Patriot             | 3        | 3      | 4.69%   |
| ExeGate             | 3        | 4      | 4.69%   |
| Crucial             | 3        | 6      | 4.69%   |
| Qumo                | 2        | 2      | 3.13%   |
| KIOXIA-EXCERIA      | 2        | 2      | 3.13%   |
| Intel               | 2        | 2      | 3.13%   |
| China               | 2        | 2      | 3.13%   |
| Apacer              | 2        | 2      | 3.13%   |
| Toshiba             | 1        | 1      | 1.56%   |
| Smartbuy            | 1        | 1      | 1.56%   |
| Seagate             | 1        | 1      | 1.56%   |
| GOODRAM             | 1        | 1      | 1.56%   |
| Dahua               | 1        | 1      | 1.56%   |
| AMD                 | 1        | 1      | 1.56%   |
| Unknown             | 1        | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 88       | 126    | 46.56%  |
| SSD  | 61       | 73     | 32.28%  |
| NVMe | 39       | 46     | 20.63%  |
| MMC  | 1        | 1      | 0.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 123      | 197    | 74.55%  |
| NVMe | 39       | 46     | 23.64%  |
| SAS  | 2        | 2      | 1.21%   |
| MMC  | 1        | 1      | 0.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 83       | 104    | 55.33%  |
| 0.51-1.0   | 57       | 82     | 38%     |
| 1.01-2.0   | 6        | 9      | 4%      |
| 3.01-4.0   | 3        | 3      | 2%      |
| 2.01-3.0   | 1        | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 47       | 31.13%  |
| 501-1000       | 39       | 25.83%  |
| 251-500        | 36       | 23.84%  |
| 1001-2000      | 14       | 9.27%   |
| 51-100         | 6        | 3.97%   |
| 2001-3000      | 5        | 3.31%   |
| 21-50          | 2        | 1.32%   |
| More than 3000 | 1        | 0.66%   |
| Unknown        | 1        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 75       | 48.08%  |
| 21-50          | 34       | 21.79%  |
| 101-250        | 14       | 8.97%   |
| 51-100         | 11       | 7.05%   |
| 501-1000       | 10       | 6.41%   |
| 251-500        | 6        | 3.85%   |
| 1001-2000      | 3        | 1.92%   |
| More than 3000 | 1        | 0.64%   |
| 2001-3000      | 1        | 0.64%   |
| Unknown        | 1        | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 6        | 7      | 21.43%  |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 2      | 7.14%   |
| Seagate ST3160811AS 160GB         | 2        | 2      | 7.14%   |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 6      | 7.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 3.57%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 2      | 3.57%   |
| WDC WD5000AAKS-00D2B0 500GB       | 1        | 1      | 3.57%   |
| WDC WD3200AAKX-001CA0 320GB       | 1        | 1      | 3.57%   |
| WDC WD10EZEX-75ZF5A0 1TB          | 1        | 2      | 3.57%   |
| WDC WD10EZEX-00WN4A0 1TB          | 1        | 1      | 3.57%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 3.57%   |
| SPCC M.2 PCIe SSD 512GB           | 1        | 1      | 3.57%   |
| Seagate ST9500423AS 500GB         | 1        | 1      | 3.57%   |
| Seagate ST3500413AS 500GB         | 1        | 1      | 3.57%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 3.57%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 3.57%   |
| Seagate ST31000524NS 1TB          | 1        | 1      | 3.57%   |
| Samsung Electronics HD400LJ 400GB | 1        | 1      | 3.57%   |
| Hitachi HTS543216L9A300 160GB     | 1        | 1      | 3.57%   |
| Hitachi HDS5C1050CLA382 500GB     | 1        | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 21     | 53.57%  |
| WDC                 | 9        | 11     | 32.14%  |
| Hitachi             | 2        | 2      | 7.14%   |
| SPCC                | 1        | 1      | 3.57%   |
| Samsung Electronics | 1        | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 21     | 57.69%  |
| WDC                 | 8        | 10     | 30.77%  |
| Hitachi             | 2        | 2      | 7.69%   |
| Samsung Electronics | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 34     | 91.67%  |
| NVMe | 1        | 1      | 4.17%   |
| SSD  | 1        | 1      | 4.17%   |

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
| Works    | 126      | 200    | 80.25%  |
| Malfunc  | 24       | 36     | 15.29%  |
| Detected | 7        | 10     | 4.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 122      | 64.89%  |
| AMD                          | 20       | 10.64%  |
| Samsung Electronics          | 7        | 3.72%   |
| Realtek Semiconductor        | 7        | 3.72%   |
| Phison Electronics           | 7        | 3.72%   |
| Silicon Motion               | 6        | 3.19%   |
| SanDisk                      | 3        | 1.6%    |
| Nvidia                       | 3        | 1.6%    |
| Kingston Technology Company  | 3        | 1.6%    |
| JMicron Technology           | 2        | 1.06%   |
| ADATA Technology             | 2        | 1.06%   |
| VIA Technologies             | 1        | 0.53%   |
| ShenZhen TIGO Semiconductor  | 1        | 0.53%   |
| Shenzhen Longsys Electronics | 1        | 0.53%   |
| Netac Technology             | 1        | 0.53%   |
| Micron/Crucial Technology    | 1        | 0.53%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 33       | 15.14%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 7.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 4.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 4.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 3.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 3.67%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 7        | 3.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 3.21%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 3.21%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 3.21%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 2.75%   |
| Realtek NVMe Controller                                                                 | 6        | 2.75%   |
| Phison PS5013 E13 NVMe Controller                                                       | 6        | 2.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 2.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.38%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.38%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.38%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.38%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.92%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2        | 0.92%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.92%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.46%   |
| ShenZhen TIGO Non-Volatile memory controller                                            | 1        | 0.46%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                             | 1        | 0.46%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 1        | 0.46%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1        | 0.46%   |
| SanDisk NVMe Controller                                                                 | 1        | 0.46%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 121      | 64.36%  |
| NVMe | 39       | 20.74%  |
| IDE  | 23       | 12.23%  |
| RAID | 5        | 2.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 122      | 84.14%  |
| AMD    | 23       | 15.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-10100 CPU @ 3.60GHz           | 14       | 9.66%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 13       | 8.97%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 7        | 4.83%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 6        | 4.14%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 3.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.76%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 3        | 2.07%   |
| Intel Pentium 4 CPU 3.06GHz                 | 3        | 2.07%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 3        | 2.07%   |
| Intel 12th Gen Core i5-12400                | 3        | 2.07%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 1.38%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 1.38%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 1.38%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.38%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.38%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 1.38%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.38%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 2        | 1.38%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.38%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2        | 1.38%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.38%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.38%   |
| AMD FX-4100 Quad-Core Processor             | 2        | 1.38%   |
| Intel Xeon CPU W3670 @ 3.20GHz              | 1        | 0.69%   |
| Intel Pentium Gold G7400                    | 1        | 0.69%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1        | 0.69%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.69%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.69%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.69%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.69%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.69%   |
| Intel Pentium CPU G2130 @ 3.20GHz           | 1        | 0.69%   |
| Intel Core i7-4790T CPU @ 2.70GHz           | 1        | 0.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.69%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.69%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.69%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 0.69%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 45       | 31.03%  |
| Intel Core i3      | 28       | 19.31%  |
| Other              | 12       | 8.28%   |
| Intel Celeron      | 8        | 5.52%   |
| AMD Ryzen 5        | 8        | 5.52%   |
| Intel Pentium      | 7        | 4.83%   |
| Intel Core i7      | 7        | 4.83%   |
| Intel Pentium Gold | 5        | 3.45%   |
| Intel Core 2 Duo   | 4        | 2.76%   |
| Intel Pentium 4    | 3        | 2.07%   |
| AMD FX             | 3        | 2.07%   |
| AMD Ryzen 7 PRO    | 2        | 1.38%   |
| AMD Ryzen 7        | 2        | 1.38%   |
| AMD Ryzen 5 PRO    | 2        | 1.38%   |
| AMD Athlon II X2   | 2        | 1.38%   |
| Intel Xeon         | 1        | 0.69%   |
| Intel Pentium Dual | 1        | 0.69%   |
| Intel Core 2       | 1        | 0.69%   |
| AMD Ryzen 9        | 1        | 0.69%   |
| AMD Ryzen 3        | 1        | 0.69%   |
| AMD Phenom         | 1        | 0.69%   |
| AMD Athlon         | 1        | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 50       | 34.48%  |
| 6      | 44       | 30.34%  |
| 2      | 34       | 23.45%  |
| 8      | 10       | 6.9%    |
| 1      | 4        | 2.76%   |
| 12     | 2        | 1.38%   |
| 3      | 1        | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 145      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 85       | 58.62%  |
| 1      | 60       | 41.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 144      | 99.31%  |
| Unknown        | 1        | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 33       | 22.6%   |
| 0x906ea    | 12       | 8.22%   |
| 0x906ed    | 10       | 6.85%   |
| 0x306a9    | 9        | 6.16%   |
| 0x506e3    | 8        | 5.48%   |
| 0x306c3    | 7        | 4.79%   |
| 0x90675    | 6        | 4.11%   |
| 0x206a7    | 6        | 4.11%   |
| 0xa0671    | 5        | 3.42%   |
| 0x08600106 | 4        | 2.74%   |
| 0xf49      | 3        | 2.05%   |
| 0xa0655    | 3        | 2.05%   |
| 0x1067a    | 3        | 2.05%   |
| 0x08108109 | 3        | 2.05%   |
| 0x906eb    | 2        | 1.37%   |
| 0x906e9    | 2        | 1.37%   |
| 0x90672    | 2        | 1.37%   |
| 0x706a8    | 2        | 1.37%   |
| 0x6fd      | 2        | 1.37%   |
| 0x0a50000d | 2        | 1.37%   |
| 0x0a50000c | 2        | 1.37%   |
| 0x0600063e | 2        | 1.37%   |
| Unknown    | 2        | 1.37%   |
| 0xa0654    | 1        | 0.68%   |
| 0x6f6      | 1        | 0.68%   |
| 0x206c2    | 1        | 0.68%   |
| 0x20652    | 1        | 0.68%   |
| 0x106e5    | 1        | 0.68%   |
| 0x106a5    | 1        | 0.68%   |
| 0x10661    | 1        | 0.68%   |
| 0x0a201205 | 1        | 0.68%   |
| 0x0a201016 | 1        | 0.68%   |
| 0x08701021 | 1        | 0.68%   |
| 0x08101016 | 1        | 0.68%   |
| 0x0810100b | 1        | 0.68%   |
| 0x06000852 | 1        | 0.68%   |
| 0x010000c8 | 1        | 0.68%   |
| 0x010000c7 | 1        | 0.68%   |
| 0x01000083 | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| CometLake        | 37       | 25.52%  |
| KabyLake         | 26       | 17.93%  |
| IvyBridge        | 9        | 6.21%   |
| Skylake          | 8        | 5.52%   |
| Haswell          | 7        | 4.83%   |
| Alderlake Hybrid | 7        | 4.83%   |
| Zen 3            | 6        | 4.14%   |
| SandyBridge      | 6        | 4.14%   |
| Zen 2            | 5        | 3.45%   |
| Zen+             | 4        | 2.76%   |
| Core             | 4        | 2.76%   |
| Unknown          | 4        | 2.76%   |
| Penryn           | 3        | 2.07%   |
| NetBurst         | 3        | 2.07%   |
| K10              | 3        | 2.07%   |
| Zen              | 2        | 1.38%   |
| Westmere         | 2        | 1.38%   |
| Nehalem          | 2        | 1.38%   |
| Icelake          | 2        | 1.38%   |
| Goldmont plus    | 2        | 1.38%   |
| Bulldozer        | 2        | 1.38%   |
| Piledriver       | 1        | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 101      | 67.33%  |
| Nvidia | 25       | 16.67%  |
| AMD    | 24       | 16%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 31       | 20.53%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 11.26%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 4.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.31%   |
| Intel HD Graphics 530                                                       | 5        | 3.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.31%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 2.65%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 4        | 2.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 2.65%   |
| AMD Renoir                                                                  | 4        | 2.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.65%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.99%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.99%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 1.32%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.32%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 2        | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.32%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.66%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.66%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.66%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.66%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.66%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 0.66%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.66%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.66%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 0.66%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 0.66%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.66%   |
| Intel HD Graphics 630                                                       | 1        | 0.66%   |
| Intel HD Graphics 610                                                       | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 97       | 66.9%   |
| 1 x Nvidia     | 23       | 15.86%  |
| 1 x AMD        | 22       | 15.17%  |
| 2 x AMD        | 1        | 0.69%   |
| Intel + Nvidia | 1        | 0.69%   |
| AMD + Nvidia   | 1        | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 111      | 76.03%  |
| Unknown     | 27       | 18.49%  |
| Proprietary | 8        | 5.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 108      | 74.48%  |
| 0.01-0.5   | 12       | 8.28%   |
| 1.01-2.0   | 11       | 7.59%   |
| 0.51-1.0   | 10       | 6.9%    |
| 3.01-4.0   | 2        | 1.38%   |
| 7.01-8.0   | 1        | 0.69%   |
| 2.01-3.0   | 1        | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 23       | 18.25%  |
| Philips              | 20       | 15.87%  |
| Acer                 | 16       | 12.7%   |
| ViewSonic            | 12       | 9.52%   |
| BenQ                 | 8        | 6.35%   |
| AOC                  | 8        | 6.35%   |
| Goldstar             | 7        | 5.56%   |
| Hewlett-Packard      | 6        | 4.76%   |
| Dell                 | 5        | 3.97%   |
| SGT                  | 4        | 3.17%   |
| Lenovo               | 3        | 2.38%   |
| ASUSTek Computer     | 3        | 2.38%   |
| Sony                 | 1        | 0.79%   |
| OOO                  | 1        | 0.79%   |
| Mi                   | 1        | 0.79%   |
| JRY                  | 1        | 0.79%   |
| HUAWEI               | 1        | 0.79%   |
| DOY                  | 1        | 0.79%   |
| Daewoo               | 1        | 0.79%   |
| CHR                  | 1        | 0.79%   |
| CHD                  | 1        | 0.79%   |
| Ancor Communications | 1        | 0.79%   |
| Unknown              | 1        | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 9        | 6.77%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 5        | 3.76%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 4        | 3.01%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 4        | 3.01%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 4        | 3.01%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                   | 3        | 2.26%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2        | 1.5%    |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 2        | 1.5%    |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 2        | 1.5%    |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2        | 1.5%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 440x250mm 19.9-inch      | 2        | 1.5%    |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 1.5%    |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 1.5%    |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 2        | 1.5%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 1.5%    |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 2        | 1.5%    |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 2        | 1.5%    |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 0.75%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1        | 0.75%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1        | 0.75%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                    | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM02A0 1280x1024 376x301mm 19.0-inch  | 1        | 0.75%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.75%   |
| Samsung Electronics SME1920N SAM06A3 1360x768 410x230mm 18.5-inch     | 1        | 0.75%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 440x250mm 19.9-inch     | 1        | 0.75%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 0.75%   |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 1        | 0.75%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1        | 0.75%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 0.75%   |
| Samsung Electronics S24B300 SAM08B2 1920x1080 531x299mm 24.0-inch     | 1        | 0.75%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1        | 0.75%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch    | 1        | 0.75%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 0.75%   |
| Philips PHL 252B9 PHL092C 1920x1080 535x339mm 24.9-inch               | 1        | 0.75%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 521x293mm 23.5-inch               | 1        | 0.75%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1        | 0.75%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 0.75%   |
| Philips PHL 241E1 PHLC207 1920x1080 527x296mm 23.8-inch               | 1        | 0.75%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch              | 1        | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 74       | 62.18%  |
| 1280x1024 (SXGA)  | 14       | 11.76%  |
| 2560x1440 (QHD)   | 10       | 8.4%    |
| 1600x900 (HD+)    | 9        | 7.56%   |
| 1920x1200 (WUXGA) | 3        | 2.52%   |
| 1366x768 (WXGA)   | 3        | 2.52%   |
| 3840x2160 (4K)    | 1        | 0.84%   |
| 3440x1440         | 1        | 0.84%   |
| 1600x1200         | 1        | 0.84%   |
| 1440x900 (WXGA+)  | 1        | 0.84%   |
| 1280x960          | 1        | 0.84%   |
| 1024x768 (XGA)    | 1        | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 30       | 23.44%  |
| 23     | 28       | 21.88%  |
| 21     | 17       | 13.28%  |
| 27     | 15       | 11.72%  |
| 20     | 10       | 7.81%   |
| 19     | 9        | 7.03%   |
| 17     | 6        | 4.69%   |
| 31     | 4        | 3.13%   |
| 18     | 3        | 2.34%   |
| 25     | 2        | 1.56%   |
| 15     | 2        | 1.56%   |
| 34     | 1        | 0.78%   |
| 32     | 1        | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 69       | 57.02%  |
| 401-500     | 29       | 23.97%  |
| 351-400     | 9        | 7.44%   |
| 301-350     | 8        | 6.61%   |
| 601-700     | 4        | 3.31%   |
| 701-800     | 2        | 1.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 95       | 80.51%  |
| 5/4   | 15       | 12.71%  |
| 16/10 | 5        | 4.24%   |
| 4/3   | 2        | 1.69%   |
| 21/9  | 1        | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 61       | 50%     |
| 151-200        | 25       | 20.49%  |
| 301-350        | 15       | 12.3%   |
| 141-150        | 8        | 6.56%   |
| 351-500        | 6        | 4.92%   |
| 251-300        | 5        | 4.1%    |
| 101-110        | 2        | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 91       | 77.78%  |
| 101-120 | 26       | 22.22%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 106      | 70.2%   |
| 0     | 29       | 19.21%  |
| 2     | 16       | 10.6%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 102      | 58.62%  |
| Intel                    | 46       | 26.44%  |
| Qualcomm Atheros         | 3        | 1.72%   |
| Nvidia                   | 3        | 1.72%   |
| Broadcom                 | 3        | 1.72%   |
| TP-Link                  | 2        | 1.15%   |
| Samsung Electronics      | 2        | 1.15%   |
| Ralink Technology        | 2        | 1.15%   |
| Mercucys                 | 2        | 1.15%   |
| MediaTek                 | 2        | 1.15%   |
| VIA Technologies         | 1        | 0.57%   |
| Ralink                   | 1        | 0.57%   |
| Metrologic Instruments   | 1        | 0.57%   |
| Marvell Technology Group | 1        | 0.57%   |
| Huawei Technologies      | 1        | 0.57%   |
| Edimax Technology        | 1        | 0.57%   |
| ASIX Electronics         | 1        | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88       | 45.13%  |
| Intel Ethernet Controller I225-V                                  | 8        | 4.1%    |
| Intel Ethernet Connection (14) I219-V                             | 8        | 4.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 3.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 2.05%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 2.05%   |
| Realtek 802.11ac NIC                                              | 3        | 1.54%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.54%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.03%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.03%   |
| Mercucys 802.11n NIC                                              | 2        | 1.03%   |
| Intel Wireless 7265                                               | 2        | 1.03%   |
| Intel Wireless 3165                                               | 2        | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2        | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.03%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.03%   |
| Intel Ethernet Connection (10) I219-V                             | 2        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.03%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.51%   |
| TP-Link USB 10/100 LAN                                            | 1        | 0.51%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1        | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.51%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.51%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.51%   |
| Metrologic Instruments 7580                                       | 1        | 0.51%   |
| MediaTek TECNO SPARK 9T                                           | 1        | 0.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 43.24%  |
| Intel                 | 11       | 29.73%  |
| Ralink Technology     | 2        | 5.41%   |
| Mercucys              | 2        | 5.41%   |
| Broadcom              | 2        | 5.41%   |
| TP-Link               | 1        | 2.7%    |
| Ralink                | 1        | 2.7%    |
| MediaTek              | 1        | 2.7%    |
| Edimax Technology     | 1        | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 5        | 13.51%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 4        | 10.81%  |
| Realtek 802.11ac NIC                                            | 3        | 8.11%   |
| Ralink MT7601U Wireless Adapter                                 | 2        | 5.41%   |
| Mercucys 802.11n NIC                                            | 2        | 5.41%   |
| Intel Wireless 7265                                             | 2        | 5.41%   |
| Intel Wireless 3165                                             | 2        | 5.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 2        | 5.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 5.41%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                           | 1        | 2.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 2.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 2.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1        | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1        | 2.7%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                       | 1        | 2.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1        | 2.7%    |
| Intel Wireless 7260                                             | 1        | 2.7%    |
| Intel Alder Lake-S PCH CNVi WiFi                                | 1        | 2.7%    |
| Intel 700 Series Chipset Family Wi-Fi                           | 1        | 2.7%    |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 2.7%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter              | 1        | 2.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                 | 1        | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 96       | 63.16%  |
| Intel                    | 42       | 27.63%  |
| Qualcomm Atheros         | 3        | 1.97%   |
| Nvidia                   | 3        | 1.97%   |
| VIA Technologies         | 1        | 0.66%   |
| TP-Link                  | 1        | 0.66%   |
| Samsung Electronics      | 1        | 0.66%   |
| MediaTek                 | 1        | 0.66%   |
| Marvell Technology Group | 1        | 0.66%   |
| Huawei Technologies      | 1        | 0.66%   |
| Broadcom                 | 1        | 0.66%   |
| ASIX Electronics         | 1        | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88       | 56.41%  |
| Intel Ethernet Controller I225-V                                  | 8        | 5.13%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 5.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 3.85%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 2.56%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.92%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.28%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.28%   |
| Intel Ethernet Connection (10) I219-V                             | 2        | 1.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.28%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.64%   |
| TP-Link USB 10/100 LAN                                            | 1        | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.64%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.64%   |
| MediaTek TECNO SPARK 9T                                           | 1        | 0.64%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.64%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.64%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.64%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.64%   |
| Huawei ANE-LX1                                                    | 1        | 0.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 144      | 78.69%  |
| WiFi     | 37       | 20.22%  |
| Modem    | 2        | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 93.84%  |
| WiFi     | 9        | 6.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 79.31%  |
| 2     | 29       | 20%     |
| 4     | 1        | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 143      | 98.62%  |
| Yes  | 2        | 1.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 42.31%  |
| Realtek Semiconductor   | 7        | 26.92%  |
| Cambridge Silicon Radio | 3        | 11.54%  |
| Broadcom                | 2        | 7.69%   |
| TP-Link                 | 1        | 3.85%   |
| MediaTek                | 1        | 3.85%   |
| ASUSTek Computer        | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 7        | 26.92%  |
| Intel Bluetooth wireless interface                  | 5        | 19.23%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 11.54%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 7.69%   |
| Intel Bluetooth Device                              | 2        | 7.69%   |
| Intel AX201 Bluetooth                               | 2        | 7.69%   |
| TP-Link UB500 Adapter                               | 1        | 3.85%   |
| MediaTek Wireless_Device                            | 1        | 3.85%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 3.85%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 122      | 66.67%  |
| AMD                    | 27       | 14.75%  |
| Nvidia                 | 23       | 12.57%  |
| Texas Instruments      | 4        | 2.19%   |
| C-Media Electronics    | 3        | 1.64%   |
| Razer USA              | 1        | 0.55%   |
| Logitech               | 1        | 0.55%   |
| Generalplus Technology | 1        | 0.55%   |
| Creative Technology    | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Smart Sound Technology (SST) Audio Controller                        | 28       | 13.59%  |
| Intel 200 Series PCH HD Audio                                              | 18       | 8.74%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 6.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 5.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 4.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 3.88%   |
| Intel Comet Lake PCH-V cAVS                                                | 8        | 3.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 3.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 7        | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.91%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 2.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.43%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4        | 1.94%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.94%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.46%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 1.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 0.97%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.49%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.49%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.49%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.49%   |
| Logitech 960 Headset                                                       | 1        | 0.49%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.49%   |
| Intel CM238 HD Audio Controller                                            | 1        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Crucial                            | 25       | 16.67%  |
| Kingston                           | 20       | 13.33%  |
| Unknown                            | 17       | 11.33%  |
| Foxline                            | 15       | 10%     |
| Samsung Electronics                | 11       | 7.33%   |
| SK hynix                           | 9        | 6%      |
| Patriot                            | 7        | 4.67%   |
| Apacer                             | 7        | 4.67%   |
| AMD                                | 7        | 4.67%   |
| A-DATA Technology                  | 6        | 4%      |
| Elpida                             | 3        | 2%      |
| Unknown (ABCD)                     | 2        | 1.33%   |
| Neo Forza                          | 2        | 1.33%   |
| Micron Technology                  | 2        | 1.33%   |
| HomeNet                            | 2        | 1.33%   |
| Corsair                            | 2        | 1.33%   |
| Unknown                            | 2        | 1.33%   |
| Unknown (89F7)                     | 1        | 0.67%   |
| Unknown (0x0080)                   | 1        | 0.67%   |
| Shenzhen Micro Innovation Industry | 1        | 0.67%   |
| SHARETRONIC                        | 1        | 0.67%   |
| Qumo                               | 1        | 0.67%   |
| Innodisk                           | 1        | 0.67%   |
| Good Wealth                        | 1        | 0.67%   |
| Goldkey                            | 1        | 0.67%   |
| Golden Empire                      | 1        | 0.67%   |
| Gold Key                           | 1        | 0.67%   |
| ChangXin Memory                    | 1        | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s              | 6        | 3.87%   |
| Foxline RAM FL2666D4S19-8G 8192MB SODIMM DDR4 2667MT/s         | 5        | 3.23%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                    | 3        | 1.94%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 2        | 1.29%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 1.29%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 1.29%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 1.29%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                       | 2        | 1.29%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s            | 2        | 1.29%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                | 2        | 1.29%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s          | 2        | 1.29%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 1.29%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s          | 2        | 1.29%   |
| HomeNet RAM HN SO 8GB 8192MB SODIMM DDR4 3200MT/s              | 2        | 1.29%   |
| Crucial RAM ST51264BA1339.16FK 4GB DIMM DDR3 1067MT/s          | 2        | 1.29%   |
| Crucial RAM CT8G4SFRA32A.C16FG 8GB SODIMM DDR4 3200MT/s        | 2        | 1.29%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s         | 2        | 1.29%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s           | 2        | 1.29%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s         | 2        | 1.29%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 1.29%   |
| Apacer RAM D12.2324CH.002 8GB DIMM DDR4 2667MT/s               | 2        | 1.29%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 1.29%   |
| Unknown                                                        | 2        | 1.29%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.65%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR 1066MT/s                       | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                      | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.65%   |
| Unknown RAM Module 1GB DIMM SDRAM 1066MT/s                     | 1        | 0.65%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.65%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 0.65%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                       | 1        | 0.65%   |
| Unknown (89F7) RAM Module 8192MB DIMM DDR4 2667MT/s            | 1        | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 97       | 68.79%  |
| DDR3    | 22       | 15.6%   |
| DDR2    | 7        | 4.96%   |
| SDRAM   | 6        | 4.26%   |
| Unknown | 5        | 3.55%   |
| LPDDR4  | 2        | 1.42%   |
| DDR5    | 1        | 0.71%   |
| DDR     | 1        | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 121      | 85.82%  |
| SODIMM | 20       | 14.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 74       | 48.68%  |
| 4096  | 32       | 21.05%  |
| 16384 | 19       | 12.5%   |
| 2048  | 14       | 9.21%   |
| 1024  | 8        | 5.26%   |
| 32768 | 4        | 2.63%   |
| 512   | 1        | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 38       | 25.68%  |
| 3200    | 25       | 16.89%  |
| 1333    | 12       | 8.11%   |
| 2400    | 10       | 6.76%   |
| 2666    | 6        | 4.05%   |
| 2133    | 6        | 4.05%   |
| 1600    | 6        | 4.05%   |
| 800     | 4        | 2.7%    |
| 3600    | 3        | 2.03%   |
| 2800    | 3        | 2.03%   |
| 533     | 3        | 2.03%   |
| Unknown | 3        | 2.03%   |
| 3266    | 2        | 1.35%   |
| 2934    | 2        | 1.35%   |
| 2933    | 2        | 1.35%   |
| 1866    | 2        | 1.35%   |
| 1800    | 2        | 1.35%   |
| 1067    | 2        | 1.35%   |
| 1066    | 2        | 1.35%   |
| 667     | 2        | 1.35%   |
| 333     | 2        | 1.35%   |
| 5200    | 1        | 0.68%   |
| 3800    | 1        | 0.68%   |
| 3533    | 1        | 0.68%   |
| 3466    | 1        | 0.68%   |
| 3000    | 1        | 0.68%   |
| 2866    | 1        | 0.68%   |
| 2733    | 1        | 0.68%   |
| 2187    | 1        | 0.68%   |
| 2134    | 1        | 0.68%   |
| 1648    | 1        | 0.68%   |
| 400     | 1        | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Pantum  | 1        | 50%     |
| Kyocera | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Pantum BM5100ADN series | 1        | 50%     |
| Kyocera FS-1040         | 1        | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet Pro 2000 s2  | 1        | 33.33%  |
| Canon CanoScan LIDE 25  | 1        | 33.33%  |
| Canon CanoScan LiDE 110 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| SunplusIT                   | 6        | 22.22%  |
| Alcor Micro                 | 5        | 18.52%  |
| Realtek Semiconductor       | 3        | 11.11%  |
| Microdia                    | 3        | 11.11%  |
| Logitech                    | 3        | 11.11%  |
| Chicony Electronics         | 2        | 7.41%   |
| KYE Systems (Mouse Systems) | 1        | 3.7%    |
| Creative Technology         | 1        | 3.7%    |
| Arkmicro Technologies       | 1        | 3.7%    |
| Apple                       | 1        | 3.7%    |
| AlcorMicroCorp              | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| SunplusIT USB Camera                      | 6        | 22.22%  |
| Alcor Micro USB 2.0 PC Camera             | 4        | 14.81%  |
| Realtek USB Camera                        | 3        | 11.11%  |
| Microdia Camera                           | 3        | 11.11%  |
| Logitech HD Webcam C615                   | 3        | 11.11%  |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 3.7%    |
| Creative VF0530 Live! Cam Chat IM         | 1        | 3.7%    |
| Chicony HP High Definition 1MP Webcam     | 1        | 3.7%    |
| Chicony HP 0.3MP Webcam                   | 1        | 3.7%    |
| Arkmicro USB2.0 PC CAMERA                 | 1        | 3.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 1        | 3.7%    |
| AlcorMicroCorp SHUNCCM                    | 1        | 3.7%    |
| Alcor Micro USB FHD Camera                | 1        | 3.7%    |

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


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Aladdin R.D. | 2        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Aladdin R.D. Smart card reader JCR721 | 1        | 50%     |
| Aladdin R.D. JaCarta                  | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 116      | 78.38%  |
| 1     | 29       | 19.59%  |
| 2     | 2        | 1.35%   |
| 4     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 70.27%  |
| Net/wireless             | 4        | 10.81%  |
| Communication controller | 3        | 8.11%   |
| Sound                    | 1        | 2.7%    |
| Network                  | 1        | 2.7%    |
| Net/ethernet             | 1        | 2.7%    |
| Chipcard                 | 1        | 2.7%    |

