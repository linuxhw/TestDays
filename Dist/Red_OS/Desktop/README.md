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

Total: 232

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B75M-D3V                    | [c6d1fc4965](https://linux-hardware.org/?probe=c6d1fc4965) | Oct 31, 2023 |
| Gigabyte      | H510M H                     | [d89e17690d](https://linux-hardware.org/?probe=d89e17690d) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [893389d935](https://linux-hardware.org/?probe=893389d935) | Oct 25, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [9bf87234d6](https://linux-hardware.org/?probe=9bf87234d6) | Oct 23, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [d1f56e838d](https://linux-hardware.org/?probe=d1f56e838d) | Oct 23, 2023 |
| MSI           | A320M-A PRO                 | [6290cec60c](https://linux-hardware.org/?probe=6290cec60c) | Oct 20, 2023 |
| MSI           | A320M-A PRO                 | [287fa14302](https://linux-hardware.org/?probe=287fa14302) | Oct 20, 2023 |
| Gigabyte      | B75M-D3V                    | [0fd9732532](https://linux-hardware.org/?probe=0fd9732532) | Oct 19, 2023 |
| Unknown       | Unknown                     | [9947f3f38b](https://linux-hardware.org/?probe=9947f3f38b) | Oct 17, 2023 |
| ASRock        | H510M-HVS R2.0              | [83c36787ea](https://linux-hardware.org/?probe=83c36787ea) | Oct 17, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6457a793cd](https://linux-hardware.org/?probe=6457a793cd) | Oct 14, 2023 |
| Lenovo        | 3752 NOK                    | [e3eda8aae7](https://linux-hardware.org/?probe=e3eda8aae7) | Oct 10, 2023 |
| Lenovo        | 3752 NOK                    | [5e3d37b336](https://linux-hardware.org/?probe=5e3d37b336) | Oct 05, 2023 |
| Gigabyte      | H61M-DS2H                   | [f3e31ed154](https://linux-hardware.org/?probe=f3e31ed154) | Sep 22, 2023 |
| Unknown       | DMB-A520-MCA01              | [a959513e7c](https://linux-hardware.org/?probe=a959513e7c) | Sep 18, 2023 |
| Gigabyte      | H110M-H-CF                  | [5eadb71ae4](https://linux-hardware.org/?probe=5eadb71ae4) | Sep 15, 2023 |
| ASRock        | H510M-HVS R2.0              | [018a3b8abe](https://linux-hardware.org/?probe=018a3b8abe) | Sep 08, 2023 |
| MSI           | MS-B0A41                    | [c93409061c](https://linux-hardware.org/?probe=c93409061c) | Sep 06, 2023 |
| DEPO Compu... | DPH410S                     | [88076446b3](https://linux-hardware.org/?probe=88076446b3) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | [201a0612e4](https://linux-hardware.org/?probe=201a0612e4) | Aug 18, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [fb99152b24](https://linux-hardware.org/?probe=fb99152b24) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [5aeb5ebcbf](https://linux-hardware.org/?probe=5aeb5ebcbf) | Aug 09, 2023 |
| Gigabyte      | B360HD3                     | [4dc4fb1691](https://linux-hardware.org/?probe=4dc4fb1691) | Aug 08, 2023 |
| Gigabyte      | B360HD3                     | [b297b777be](https://linux-hardware.org/?probe=b297b777be) | Jul 25, 2023 |
| Biostar       | H610MH                      | [ba1951d1fa](https://linux-hardware.org/?probe=ba1951d1fa) | Jun 19, 2023 |
| ASRock        | A320M-HDV R4.0              | [2a3c6cf0ab](https://linux-hardware.org/?probe=2a3c6cf0ab) | Jun 14, 2023 |
| Gigabyte      | H510M H                     | [337e4a106e](https://linux-hardware.org/?probe=337e4a106e) | Jun 13, 2023 |
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
| Red OS 7.3   | 72       | 41.38%  |
| Red OS 7.3.2 | 47       | 27.01%  |
| Red OS 7.3.1 | 47       | 27.01%  |
| Red OS 7.2   | 8        | 4.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 165      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.10-1.el7.x86_64   | 26       | 14.21%  |
| 5.10.29-1.el7.x86_64   | 24       | 13.11%  |
| 5.15.87-1.el7.3.x86_64 | 23       | 12.57%  |
| 5.15.35-5.el7.3.x86_64 | 19       | 10.38%  |
| 5.15.72-1.el7.3.x86_64 | 17       | 9.29%   |
| 5.15.78-2.el7.3.x86_64 | 11       | 6.01%   |
| 5.15.35-1.el7.3.x86_64 | 9        | 4.92%   |
| 5.14.9-1.el7.x86_64    | 8        | 4.37%   |
| 6.1.52-1.el7.3.x86_64  | 7        | 3.83%   |
| 5.15.35-4.el7.3.x86_64 | 7        | 3.83%   |
| 4.19.79-1.el7.x86_64   | 6        | 3.28%   |
| 6.1.44-1.el7.3.x86_64  | 5        | 2.73%   |
| 6.1.20-2.el7.3.x86_64  | 4        | 2.19%   |
| 5.15.10-3.el7.x86_64   | 3        | 1.64%   |
| 5.15.10-2.el7.x86_64   | 3        | 1.64%   |
| 5.10.29-3.el7.x86_64   | 3        | 1.64%   |
| 6.1.38-2.el7.3.x86_64  | 2        | 1.09%   |
| 6.1.11-1.el7.3.x86_64  | 1        | 0.55%   |
| 5.10.24-3.el7.x86_64   | 1        | 0.55%   |
| 5.10.24-2.el7.x86_64   | 1        | 0.55%   |
| 5.10.1-1.el7.x86_64    | 1        | 0.55%   |
| 4.19.56-2.el7.x86_64   | 1        | 0.55%   |
| 4.19.204-1.el7.x86_64  | 1        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.35  | 32       | 17.78%  |
| 5.15.10  | 32       | 17.78%  |
| 5.10.29  | 27       | 15%     |
| 5.15.87  | 23       | 12.78%  |
| 5.15.72  | 17       | 9.44%   |
| 5.15.78  | 11       | 6.11%   |
| 5.14.9   | 8        | 4.44%   |
| 6.1.52   | 7        | 3.89%   |
| 4.19.79  | 6        | 3.33%   |
| 6.1.44   | 5        | 2.78%   |
| 6.1.20   | 4        | 2.22%   |
| 6.1.38   | 2        | 1.11%   |
| 5.10.24  | 2        | 1.11%   |
| 6.1.11   | 1        | 0.56%   |
| 5.10.1   | 1        | 0.56%   |
| 4.19.56  | 1        | 0.56%   |
| 4.19.204 | 1        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 106      | 61.99%  |
| 5.10    | 30       | 17.54%  |
| 6.1     | 19       | 11.11%  |
| 5.14    | 8        | 4.68%   |
| 4.19    | 8        | 4.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 165      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 137      | 80.12%  |
| Cinnamon   | 26       | 15.2%   |
| X-Cinnamon | 5        | 2.92%   |
| Unknown    | 3        | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 154      | 91.67%  |
| Wayland | 6        | 3.57%   |
| Tty     | 6        | 3.57%   |
| Unknown | 2        | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 156      | 93.98%  |
| Unknown | 5        | 3.01%   |
| LightDM | 3        | 1.81%   |
| SDDM    | 2        | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 95       | 56.21%  |
| ru_RU   | 71       | 42.01%  |
| en_US   | 3        | 1.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 111      | 66.07%  |
| BIOS | 57       | 33.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 161      | 96.99%  |
| Btrfs   | 4        | 2.41%   |
| Unknown | 1        | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 110      | 65.87%  |
| MBR     | 54       | 32.34%  |
| Unknown | 3        | 1.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 92.22%  |
| Yes       | 13       | 7.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 76.65%  |
| Yes       | 39       | 23.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 47       | 28.48%  |
| ASUSTek Computer    | 28       | 16.97%  |
| ASRock              | 21       | 12.73%  |
| MSI                 | 17       | 10.3%   |
| Hewlett-Packard     | 8        | 4.85%   |
| DEPO Computers      | 8        | 4.85%   |
| Aquarius            | 7        | 4.24%   |
| Lenovo              | 6        | 3.64%   |
| Unknown             | 6        | 3.64%   |
| Intel               | 5        | 3.03%   |
| Dell                | 2        | 1.21%   |
| Biostar             | 2        | 1.21%   |
| RDW                 | 1        | 0.61%   |
| Quanta              | 1        | 0.61%   |
| iRU                 | 1        | 0.61%   |
| ICL                 | 1        | 0.61%   |
| Foxconn             | 1        | 0.61%   |
| ECS                 | 1        | 0.61%   |
| Compal              | 1        | 0.61%   |
| Colorful Technology | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 6        | 3.64%   |
| Gigabyte B365M DS3H                 | 5        | 3.03%   |
| ASRock H510M-HVS R2.0               | 5        | 3.03%   |
| DEPO Computers DPH310T              | 4        | 2.42%   |
| MSI MS-7D14                         | 3        | 1.82%   |
| Intel D945GNT AAC96315-405          | 3        | 1.82%   |
| Gigabyte H110M-S2                   | 3        | 1.82%   |
| DEPO Computers DPH410S              | 3        | 1.82%   |
| ASRock H61M-DGS                     | 3        | 1.82%   |
| MSI MS-7D22                         | 2        | 1.21%   |
| MSI MS-7C51                         | 2        | 1.21%   |
| Gigabyte H510M H                    | 2        | 1.21%   |
| Gigabyte B75M-D3V                   | 2        | 1.21%   |
| Gigabyte B560M DS3H                 | 2        | 1.21%   |
| Gigabyte B550 AORUS ELITE V2        | 2        | 1.21%   |
| Gigabyte B365M H                    | 2        | 1.21%   |
| Biostar H610MH                      | 2        | 1.21%   |
| ASUS PRIME H510T2/CSM               | 2        | 1.21%   |
| ASUS PRIME H310M-R R2.0             | 2        | 1.21%   |
| ASUS PC                             | 2        | 1.21%   |
| ASUS MINIPC PB62                    | 2        | 1.21%   |
| ASUS All Series                     | 2        | 1.21%   |
| Aquarius P30 K44 R53                | 2        | 1.21%   |
| Aquarius AQB560M                    | 2        | 1.21%   |
| RDW RDW-MB-B450M V.1                | 1        | 0.61%   |
| Quanta 120-1104er                   | 1        | 0.61%   |
| MSI PRO H610 DP21 13M (MS-B0A4)     | 1        | 0.61%   |
| MSI MS-7E07                         | 1        | 0.61%   |
| MSI MS-7D48                         | 1        | 0.61%   |
| MSI MS-7D46                         | 1        | 0.61%   |
| MSI MS-7D35                         | 1        | 0.61%   |
| MSI MS-7B86                         | 1        | 0.61%   |
| MSI MS-7636                         | 1        | 0.61%   |
| MSI MS-7592                         | 1        | 0.61%   |
| MSI MS-7529                         | 1        | 0.61%   |
| MSI Compaq dx2300 Microtower        | 1        | 0.61%   |
| Lenovo V55t Gen 2-13ACN 11RR001BRU  | 1        | 0.61%   |
| Lenovo V50s-07IMB 11EF0011RU        | 1        | 0.61%   |
| Lenovo ThinkStation P350 30E5000BRU | 1        | 0.61%   |
| Lenovo ThinkCentre M91p 4524PL4     | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 10       | 6.06%   |
| Gigabyte B365M         | 7        | 4.24%   |
| Unknown                | 6        | 3.64%   |
| Gigabyte B560M         | 5        | 3.03%   |
| ASRock H510M-HVS       | 5        | 3.03%   |
| DEPO Computers DPH310T | 4        | 2.42%   |
| MSI MS-7D14            | 3        | 1.82%   |
| Intel D945GNT          | 3        | 1.82%   |
| HP ProDesk             | 3        | 1.82%   |
| Gigabyte H510M         | 3        | 1.82%   |
| Gigabyte H110M-S2      | 3        | 1.82%   |
| Gigabyte B550          | 3        | 1.82%   |
| DEPO Computers DPH410S | 3        | 1.82%   |
| ASRock H61M-DGS        | 3        | 1.82%   |
| MSI MS-7D22            | 2        | 1.21%   |
| MSI MS-7C51            | 2        | 1.21%   |
| Lenovo ThinkCentre     | 2        | 1.21%   |
| HP Compaq              | 2        | 1.21%   |
| Gigabyte H410M         | 2        | 1.21%   |
| Gigabyte B75M-D3V      | 2        | 1.21%   |
| Gigabyte B450          | 2        | 1.21%   |
| Gigabyte A320M-S2H     | 2        | 1.21%   |
| Dell OptiPlex          | 2        | 1.21%   |
| Biostar H610MH         | 2        | 1.21%   |
| ASUS PC                | 2        | 1.21%   |
| ASUS MINIPC            | 2        | 1.21%   |
| ASUS All               | 2        | 1.21%   |
| Aquarius Pro           | 2        | 1.21%   |
| Aquarius P30           | 2        | 1.21%   |
| Aquarius AQB560M       | 2        | 1.21%   |
| RDW RDW-MB-B450M       | 1        | 0.61%   |
| Quanta 120-1104er      | 1        | 0.61%   |
| MSI PRO                | 1        | 0.61%   |
| MSI MS-7E07            | 1        | 0.61%   |
| MSI MS-7D48            | 1        | 0.61%   |
| MSI MS-7D46            | 1        | 0.61%   |
| MSI MS-7D35            | 1        | 0.61%   |
| MSI MS-7B86            | 1        | 0.61%   |
| MSI MS-7636            | 1        | 0.61%   |
| MSI MS-7592            | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 42       | 25.45%  |
| 2022 | 21       | 12.73%  |
| 2019 | 19       | 11.52%  |
| 2020 | 14       | 8.48%   |
| 2018 | 12       | 7.27%   |
| 2012 | 12       | 7.27%   |
| 2011 | 7        | 4.24%   |
| 2016 | 6        | 3.64%   |
| 2013 | 6        | 3.64%   |
| 2010 | 5        | 3.03%   |
| 2015 | 4        | 2.42%   |
| 2007 | 4        | 2.42%   |
| 2014 | 3        | 1.82%   |
| 2009 | 3        | 1.82%   |
| 2006 | 3        | 1.82%   |
| 2017 | 2        | 1.21%   |
| 2023 | 1        | 0.61%   |
| 2008 | 1        | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 165      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 162      | 98.18%  |
| Enabled  | 3        | 1.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 165      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 54       | 32.73%  |
| 16.01-24.0  | 47       | 28.48%  |
| 3.01-4.0    | 22       | 13.33%  |
| 8.01-16.0   | 21       | 12.73%  |
| 32.01-64.0  | 7        | 4.24%   |
| 1.01-2.0    | 5        | 3.03%   |
| 24.01-32.0  | 3        | 1.82%   |
| 2.01-3.0    | 3        | 1.82%   |
| 64.01-256.0 | 1        | 0.61%   |
| 0.51-1.0    | 1        | 0.61%   |
| Unknown     | 1        | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 81       | 46.02%  |
| 2.01-3.0  | 33       | 18.75%  |
| 4.01-8.0  | 18       | 10.23%  |
| 3.01-4.0  | 18       | 10.23%  |
| 0.51-1.0  | 17       | 9.66%   |
| 8.01-16.0 | 6        | 3.41%   |
| 0.01-0.5  | 2        | 1.14%   |
| Unknown   | 1        | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 111      | 65.68%  |
| 2      | 44       | 26.04%  |
| 3      | 8        | 4.73%   |
| 4      | 4        | 2.37%   |
| 5      | 2        | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 65.66%  |
| Yes       | 57       | 34.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 99.39%  |
| No        | 1        | 0.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 76.79%  |
| Yes       | 39       | 23.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 83.23%  |
| Yes       | 28       | 16.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 165      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 31       | 18.45%  |
| Salekhard         | 24       | 14.29%  |
| Murom             | 23       | 13.69%  |
| Yekaterinburg     | 7        | 4.17%   |
| Perm              | 6        | 3.57%   |
| Zima              | 5        | 2.98%   |
| Novy Urengoy      | 5        | 2.98%   |
| Krasnodar         | 4        | 2.38%   |
| Volgograd         | 3        | 1.79%   |
| Stavropol         | 3        | 1.79%   |
| Novosibirsk       | 3        | 1.79%   |
| Bryansk           | 3        | 1.79%   |
| Balashikha        | 3        | 1.79%   |
| Veliky Novgorod   | 2        | 1.19%   |
| Tver              | 2        | 1.19%   |
| Tomsk             | 2        | 1.19%   |
| St Petersburg     | 2        | 1.19%   |
| Penza             | 2        | 1.19%   |
| Nal'chik          | 2        | 1.19%   |
| Muromskiy         | 2        | 1.19%   |
| Kurgan            | 2        | 1.19%   |
| Kol'chugino       | 2        | 1.19%   |
| Khabarovsk        | 2        | 1.19%   |
| Kaluga            | 2        | 1.19%   |
| Baksan            | 2        | 1.19%   |
| Yuzhno-Sakhalinsk | 1        | 0.6%    |
| Vladimir          | 1        | 0.6%    |
| Ulyanovsk         | 1        | 0.6%    |
| Tyumen            | 1        | 0.6%    |
| Svetlograd        | 1        | 0.6%    |
| Surgut            | 1        | 0.6%    |
| Shakhtersk        | 1        | 0.6%    |
| Rostov-on-Don     | 1        | 0.6%    |
| Pushkino          | 1        | 0.6%    |
| Nyandoma          | 1        | 0.6%    |
| Nyagan            | 1        | 0.6%    |
| Nizhniy Novgorod  | 1        | 0.6%    |
| Nadym             | 1        | 0.6%    |
| Magadan           | 1        | 0.6%    |
| Labytnangi        | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 50       | 70     | 21.74%  |
| WDC                          | 33       | 42     | 14.35%  |
| Toshiba                      | 24       | 30     | 10.43%  |
| Samsung Electronics          | 16       | 23     | 6.96%   |
| Kingston                     | 16       | 17     | 6.96%   |
| A-DATA Technology            | 15       | 16     | 6.52%   |
| Apacer                       | 10       | 10     | 4.35%   |
| Foxline                      | 7        | 7      | 3.04%   |
| SanDisk                      | 5        | 8      | 2.17%   |
| KingSpec                     | 5        | 5      | 2.17%   |
| Hitachi                      | 5        | 5      | 2.17%   |
| Patriot                      | 4        | 4      | 1.74%   |
| Intel                        | 4        | 4      | 1.74%   |
| ExeGate                      | 4        | 5      | 1.74%   |
| Crucial                      | 4        | 7      | 1.74%   |
| China                        | 3        | 3      | 1.3%    |
| AMD                          | 3        | 3      | 1.3%    |
| AGI                          | 3        | 3      | 1.3%    |
| Shenzhen Longsys Electronics | 2        | 2      | 0.87%   |
| Qumo                         | 2        | 2      | 0.87%   |
| KIOXIA-EXCERIA               | 2        | 2      | 0.87%   |
| Unknown                      | 2        | 2      | 0.87%   |
| XPG                          | 1        | 1      | 0.43%   |
| Unknown                      | 1        | 1      | 0.43%   |
| SPCC                         | 1        | 1      | 0.43%   |
| Smartbuy                     | 1        | 1      | 0.43%   |
| Silicon Motion               | 1        | 1      | 0.43%   |
| Phison                       | 1        | 1      | 0.43%   |
| Netac                        | 1        | 1      | 0.43%   |
| HS-SSD-E100                  | 1        | 1      | 0.43%   |
| GOODRAM                      | 1        | 1      | 0.43%   |
| Dahua                        | 1        | 1      | 0.43%   |
| Corsair                      | 1        | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                  | 12       | 4.96%   |
| Seagate ST500DM002-1BD142 500GB      | 10       | 4.13%   |
| Seagate ST1000DM010-2EP102 1TB       | 7        | 2.89%   |
| Kingston SA400S37240G 240GB SSD      | 6        | 2.48%   |
| Toshiba DT01ACA100 1TB               | 5        | 2.07%   |
| Seagate ST1000LM049-2GH172 1TB       | 5        | 2.07%   |
| Seagate ST3160811AS 160GB            | 4        | 1.65%   |
| Apacer AS2280P4 256GB                | 4        | 1.65%   |
| A-DATA SX6000PNP 256GB               | 4        | 1.65%   |
| Seagate ST1000DM010-2DM162 1TB       | 3        | 1.24%   |
| Samsung SSD 870 EVO 250GB            | 3        | 1.24%   |
| Kingston SA400S37120G 120GB SSD      | 3        | 1.24%   |
| Crucial CT240BX500SSD1 240GB         | 3        | 1.24%   |
| Apacer AS340 240GB SSD               | 3        | 1.24%   |
| AGI AGI512G16AI198 512GB             | 3        | 1.24%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2        | 0.83%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 2        | 0.83%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2        | 0.83%   |
| WDC WD10EZEX-00BBHA0 1TB             | 2        | 0.83%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB | 2        | 0.83%   |
| Toshiba HDWD105 500GB                | 2        | 0.83%   |
| Toshiba DT01ACA050 500GB             | 2        | 0.83%   |
| Seagate ST3500413AS 500GB            | 2        | 0.83%   |
| Seagate ST1000DM003-1SB10C 1TB       | 2        | 0.83%   |
| SanDisk SD8SBAT256G1122 256GB SSD    | 2        | 0.83%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 0.83%   |
| Samsung SSD 860 EVO 250GB            | 2        | 0.83%   |
| Patriot Burst Elite 240GB SSD        | 2        | 0.83%   |
| KIOXIA-EXCERIA SATA SSD 480GB        | 2        | 0.83%   |
| Kingston SA400S37480G 480GB SSD      | 2        | 0.83%   |
| Kingston OM8PCP3512F-A02 512GB       | 2        | 0.83%   |
| KingSpec P3-256 256GB                | 2        | 0.83%   |
| Foxline FLSSD240X5SE 240GB           | 2        | 0.83%   |
| ExeGate EX276690RUS(960G 960GB SSD   | 2        | 0.83%   |
| Apacer AS350 256GB SSD               | 2        | 0.83%   |
| A-DATA SU800 256GB SSD               | 2        | 0.83%   |
| A-DATA SU650 120GB SSD               | 2        | 0.83%   |
| Unknown                              | 2        | 0.83%   |
| XPG GAMMIX S70 BLADE 2TB             | 1        | 0.41%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 49       | 69     | 45.79%  |
| WDC                 | 27       | 33     | 25.23%  |
| Toshiba             | 23       | 29     | 21.5%   |
| Hitachi             | 5        | 5      | 4.67%   |
| Samsung Electronics | 3        | 4      | 2.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 12       | 12     | 14.81%  |
| A-DATA Technology   | 8        | 8      | 9.88%   |
| Samsung Electronics | 7        | 9      | 8.64%   |
| Foxline             | 6        | 6      | 7.41%   |
| Apacer              | 6        | 6      | 7.41%   |
| WDC                 | 5        | 5      | 6.17%   |
| KingSpec            | 5        | 5      | 6.17%   |
| SanDisk             | 4        | 7      | 4.94%   |
| ExeGate             | 4        | 5      | 4.94%   |
| Patriot             | 3        | 3      | 3.7%    |
| Intel               | 3        | 3      | 3.7%    |
| Crucial             | 3        | 6      | 3.7%    |
| China               | 3        | 3      | 3.7%    |
| Qumo                | 2        | 2      | 2.47%   |
| KIOXIA-EXCERIA      | 2        | 2      | 2.47%   |
| Toshiba             | 1        | 1      | 1.23%   |
| Smartbuy            | 1        | 1      | 1.23%   |
| Seagate             | 1        | 1      | 1.23%   |
| HS-SSD-E100         | 1        | 1      | 1.23%   |
| GOODRAM             | 1        | 1      | 1.23%   |
| Dahua               | 1        | 1      | 1.23%   |
| AMD                 | 1        | 1      | 1.23%   |
| Unknown             | 1        | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 97       | 140    | 44.7%   |
| SSD  | 76       | 90     | 35.02%  |
| NVMe | 43       | 50     | 19.82%  |
| MMC  | 1        | 1      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 141      | 227    | 75%     |
| NVMe | 43       | 50     | 22.87%  |
| SAS  | 3        | 3      | 1.6%    |
| MMC  | 1        | 1      | 0.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 100      | 125    | 57.8%   |
| 0.51-1.0   | 63       | 92     | 36.42%  |
| 1.01-2.0   | 6        | 9      | 3.47%   |
| 3.01-4.0   | 3        | 3      | 1.73%   |
| 2.01-3.0   | 1        | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 58       | 33.92%  |
| 501-1000       | 43       | 25.15%  |
| 251-500        | 40       | 23.39%  |
| 1001-2000      | 15       | 8.77%   |
| 51-100         | 6        | 3.51%   |
| 2001-3000      | 5        | 2.92%   |
| 21-50          | 2        | 1.17%   |
| More than 3000 | 1        | 0.58%   |
| Unknown        | 1        | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 84       | 47.46%  |
| 21-50          | 39       | 22.03%  |
| 101-250        | 17       | 9.6%    |
| 51-100         | 14       | 7.91%   |
| 501-1000       | 10       | 5.65%   |
| 251-500        | 7        | 3.95%   |
| 1001-2000      | 3        | 1.69%   |
| More than 3000 | 1        | 0.56%   |
| 2001-3000      | 1        | 0.56%   |
| Unknown        | 1        | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 7        | 8      | 22.58%  |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 2      | 6.45%   |
| Seagate ST3500413AS 500GB         | 2        | 2      | 6.45%   |
| Seagate ST3160811AS 160GB         | 2        | 2      | 6.45%   |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 6      | 6.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 3.23%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 2      | 3.23%   |
| WDC WD5000AAKS-00D2B0 500GB       | 1        | 1      | 3.23%   |
| WDC WD3200AAKX-001CA0 320GB       | 1        | 1      | 3.23%   |
| WDC WD10EZEX-75ZF5A0 1TB          | 1        | 2      | 3.23%   |
| WDC WD10EZEX-00WN4A0 1TB          | 1        | 1      | 3.23%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1      | 3.23%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 3.23%   |
| SPCC M.2 PCIe SSD 512GB           | 1        | 1      | 3.23%   |
| Seagate ST9500423AS 500GB         | 1        | 1      | 3.23%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 3.23%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 3.23%   |
| Seagate ST31000524NS 1TB          | 1        | 1      | 3.23%   |
| Samsung Electronics HD400LJ 400GB | 1        | 1      | 3.23%   |
| Hitachi HTS543216L9A300 160GB     | 1        | 1      | 3.23%   |
| Hitachi HDS5C1050CLA382 500GB     | 1        | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 23     | 54.84%  |
| WDC                 | 10       | 12     | 32.26%  |
| Hitachi             | 2        | 2      | 6.45%   |
| SPCC                | 1        | 1      | 3.23%   |
| Samsung Electronics | 1        | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 23     | 58.62%  |
| WDC                 | 9        | 11     | 31.03%  |
| Hitachi             | 2        | 2      | 6.9%    |
| Samsung Electronics | 1        | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 37     | 92.59%  |
| NVMe | 1        | 1      | 3.7%    |
| SSD  | 1        | 1      | 3.7%    |

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
| Works    | 145      | 232    | 81.01%  |
| Malfunc  | 27       | 39     | 15.08%  |
| Detected | 7        | 10     | 3.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 135      | 63.38%  |
| AMD                          | 27       | 12.68%  |
| Samsung Electronics          | 8        | 3.76%   |
| Realtek Semiconductor        | 7        | 3.29%   |
| Phison Electronics           | 7        | 3.29%   |
| Silicon Motion               | 6        | 2.82%   |
| SanDisk                      | 4        | 1.88%   |
| Kingston Technology Company  | 4        | 1.88%   |
| Nvidia                       | 3        | 1.41%   |
| Shenzhen Longsys Electronics | 2        | 0.94%   |
| JMicron Technology           | 2        | 0.94%   |
| ADATA Technology             | 2        | 0.94%   |
| VIA Technologies             | 1        | 0.47%   |
| ShenZhen TIGO Semiconductor  | 1        | 0.47%   |
| Netac Technology             | 1        | 0.47%   |
| Micron/Crucial Technology    | 1        | 0.47%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.47%   |
| Marvell Technology Group     | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 37       | 14.98%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 6.48%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 4.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 4.05%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 4.05%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 3.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 3.24%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8        | 3.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 2.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6        | 2.43%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 6        | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 2.43%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 2.43%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 5        | 2.02%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.21%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.21%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.21%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                       | 2        | 0.81%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 2        | 0.81%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 2        | 0.81%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.81%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.4%    |
| ShenZhen TIGO kimtigo NVMe SSD (DRAM-less)                                              | 1        | 0.4%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 139      | 65.57%  |
| NVMe | 43       | 20.28%  |
| IDE  | 24       | 11.32%  |
| RAID | 6        | 2.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 135      | 81.82%  |
| AMD    | 30       | 18.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-10100 CPU @ 3.60GHz           | 14       | 8.48%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 13       | 7.88%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 9        | 5.45%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 7        | 4.24%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 3.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.42%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 4        | 2.42%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 3        | 1.82%   |
| Intel Pentium 4 CPU 3.06GHz                 | 3        | 1.82%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 3        | 1.82%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 3        | 1.82%   |
| Intel 12th Gen Core i5-12400                | 3        | 1.82%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 3        | 1.82%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1.82%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 1.21%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 1.21%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 1.21%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.21%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.21%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.21%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 1.21%   |
| Intel 12th Gen Core i3-12100                | 2        | 1.21%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 2        | 1.21%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.21%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.21%   |
| AMD FX-4100 Quad-Core Processor             | 2        | 1.21%   |
| Intel Xeon CPU W3670 @ 3.20GHz              | 1        | 0.61%   |
| Intel Pentium Gold G7400                    | 1        | 0.61%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.61%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1        | 0.61%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.61%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.61%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.61%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.61%   |
| Intel Pentium CPU G2130 @ 3.20GHz           | 1        | 0.61%   |
| Intel Core i7-4790T CPU @ 2.70GHz           | 1        | 0.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.61%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 50       | 30.3%   |
| Intel Core i3      | 29       | 17.58%  |
| Other              | 15       | 9.09%   |
| Intel Core i7      | 9        | 5.45%   |
| Intel Pentium      | 8        | 4.85%   |
| Intel Celeron      | 8        | 4.85%   |
| AMD Ryzen 5        | 8        | 4.85%   |
| Intel Pentium Gold | 6        | 3.64%   |
| AMD Ryzen 7        | 5        | 3.03%   |
| Intel Core 2 Duo   | 4        | 2.42%   |
| AMD Ryzen 5 PRO    | 4        | 2.42%   |
| Intel Pentium 4    | 3        | 1.82%   |
| AMD Ryzen 3        | 3        | 1.82%   |
| AMD FX             | 3        | 1.82%   |
| AMD Ryzen 7 PRO    | 2        | 1.21%   |
| AMD Athlon II X2   | 2        | 1.21%   |
| Intel Xeon         | 1        | 0.61%   |
| Intel Pentium Dual | 1        | 0.61%   |
| Intel Core 2       | 1        | 0.61%   |
| AMD Ryzen 9        | 1        | 0.61%   |
| AMD Phenom         | 1        | 0.61%   |
| AMD Athlon         | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 59       | 35.76%  |
| 6      | 48       | 29.09%  |
| 2      | 36       | 21.82%  |
| 8      | 15       | 9.09%   |
| 1      | 4        | 2.42%   |
| 12     | 2        | 1.21%   |
| 3      | 1        | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 165      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 101      | 61.21%  |
| 1      | 64       | 38.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 164      | 99.39%  |
| Unknown        | 1        | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 37       | 22.29%  |
| 0x906ea    | 12       | 7.23%   |
| 0x306a9    | 11       | 6.63%   |
| 0x906ed    | 10       | 6.02%   |
| 0x506e3    | 8        | 4.82%   |
| 0x90675    | 7        | 4.22%   |
| 0x306c3    | 7        | 4.22%   |
| 0x206a7    | 7        | 4.22%   |
| 0xa0671    | 6        | 3.61%   |
| 0x08600106 | 6        | 3.61%   |
| 0xa0655    | 4        | 2.41%   |
| 0x0a50000c | 4        | 2.41%   |
| 0xf49      | 3        | 1.81%   |
| 0x906e9    | 3        | 1.81%   |
| 0x1067a    | 3        | 1.81%   |
| 0x08108109 | 3        | 1.81%   |
| 0x906eb    | 2        | 1.2%    |
| 0x90672    | 2        | 1.2%    |
| 0x706a8    | 2        | 1.2%    |
| 0x6fd      | 2        | 1.2%    |
| 0x0a50000d | 2        | 1.2%    |
| 0x08701021 | 2        | 1.2%    |
| 0x08101016 | 2        | 1.2%    |
| 0x0600063e | 2        | 1.2%    |
| Unknown    | 2        | 1.2%    |
| 0xb06f5    | 1        | 0.6%    |
| 0xa0654    | 1        | 0.6%    |
| 0xa0652    | 1        | 0.6%    |
| 0x6f6      | 1        | 0.6%    |
| 0x206c2    | 1        | 0.6%    |
| 0x20652    | 1        | 0.6%    |
| 0x106e5    | 1        | 0.6%    |
| 0x106a5    | 1        | 0.6%    |
| 0x10661    | 1        | 0.6%    |
| 0x0a201205 | 1        | 0.6%    |
| 0x0a201016 | 1        | 0.6%    |
| 0x0a201009 | 1        | 0.6%    |
| 0x0810100b | 1        | 0.6%    |
| 0x06000852 | 1        | 0.6%    |
| 0x010000c8 | 1        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| CometLake        | 43       | 26.06%  |
| KabyLake         | 27       | 16.36%  |
| IvyBridge        | 11       | 6.67%   |
| Zen 3            | 9        | 5.45%   |
| Alderlake Hybrid | 9        | 5.45%   |
| Zen 2            | 8        | 4.85%   |
| Skylake          | 8        | 4.85%   |
| SandyBridge      | 7        | 4.24%   |
| Haswell          | 7        | 4.24%   |
| Zen+             | 4        | 2.42%   |
| Core             | 4        | 2.42%   |
| Unknown          | 4        | 2.42%   |
| Zen              | 3        | 1.82%   |
| Penryn           | 3        | 1.82%   |
| NetBurst         | 3        | 1.82%   |
| K10              | 3        | 1.82%   |
| Icelake          | 3        | 1.82%   |
| Westmere         | 2        | 1.21%   |
| Nehalem          | 2        | 1.21%   |
| Goldmont plus    | 2        | 1.21%   |
| Bulldozer        | 2        | 1.21%   |
| Piledriver       | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 112      | 65.5%   |
| AMD    | 30       | 17.54%  |
| Nvidia | 29       | 16.96%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 34       | 19.77%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 9.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 4.65%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 6        | 3.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.49%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 6        | 3.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 3.49%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 2.91%   |
| Intel HD Graphics 530                                                       | 5        | 2.91%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 2.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.74%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 1.74%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 3        | 1.74%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.74%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 1.16%   |
| Intel HD Graphics 630                                                       | 2        | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.16%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.16%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.16%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1        | 0.58%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.58%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.58%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.58%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.58%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.58%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.58%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.58%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.58%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 0.58%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.58%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.58%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 107      | 64.85%  |
| 1 x AMD        | 28       | 16.97%  |
| 1 x Nvidia     | 26       | 15.76%  |
| Intel + Nvidia | 2        | 1.21%   |
| 2 x AMD        | 1        | 0.61%   |
| AMD + Nvidia   | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 127      | 76.51%  |
| Unknown     | 29       | 17.47%  |
| Proprietary | 10       | 6.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 119      | 72.12%  |
| 0.01-0.5   | 16       | 9.7%    |
| 1.01-2.0   | 12       | 7.27%   |
| 0.51-1.0   | 12       | 7.27%   |
| 3.01-4.0   | 3        | 1.82%   |
| 7.01-8.0   | 2        | 1.21%   |
| 2.01-3.0   | 1        | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 26       | 17.57%  |
| Philips              | 23       | 15.54%  |
| Acer                 | 17       | 11.49%  |
| ViewSonic            | 13       | 8.78%   |
| BenQ                 | 10       | 6.76%   |
| AOC                  | 10       | 6.76%   |
| Dell                 | 8        | 5.41%   |
| Goldstar             | 7        | 4.73%   |
| Hewlett-Packard      | 6        | 4.05%   |
| SGT                  | 4        | 2.7%    |
| Lenovo               | 3        | 2.03%   |
| ASUSTek Computer     | 3        | 2.03%   |
| RTK                  | 2        | 1.35%   |
| CHD                  | 2        | 1.35%   |
| Sony                 | 1        | 0.68%   |
| OOO                  | 1        | 0.68%   |
| NEC Computers        | 1        | 0.68%   |
| Mi                   | 1        | 0.68%   |
| JRY                  | 1        | 0.68%   |
| ITE                  | 1        | 0.68%   |
| HUAWEI               | 1        | 0.68%   |
| DOY                  | 1        | 0.68%   |
| Daewoo               | 1        | 0.68%   |
| CHR                  | 1        | 0.68%   |
| BOE                  | 1        | 0.68%   |
| AVX                  | 1        | 0.68%   |
| Ancor Communications | 1        | 0.68%   |
| Unknown              | 1        | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 11       | 7.01%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 5        | 3.18%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 5        | 3.18%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 4        | 2.55%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 4        | 2.55%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                   | 3        | 1.91%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2        | 1.27%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 2        | 1.27%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 2        | 1.27%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 520x290mm 23.4-inch     | 2        | 1.27%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 1.27%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 1.27%   |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                        | 2        | 1.27%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 1.27%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 1.27%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 2        | 1.27%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                     | 2        | 1.27%   |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 2        | 1.27%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 2        | 1.27%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 0.64%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1        | 0.64%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1        | 0.64%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 1        | 0.64%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM06A3 1360x768 410x230mm 18.5-inch   | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM02A0 1280x1024 376x301mm 19.0-inch  | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.64%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1        | 0.64%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1        | 0.64%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1        | 0.64%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 0.64%   |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 1        | 0.64%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1        | 0.64%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 0.64%   |
| Samsung Electronics S24B300 SAM08B2 1920x1080 531x299mm 24.0-inch     | 1        | 0.64%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch     | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1        | 0.64%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch    | 1        | 0.64%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 89       | 64.49%  |
| 1280x1024 (SXGA)  | 16       | 11.59%  |
| 2560x1440 (QHD)   | 10       | 7.25%   |
| 1600x900 (HD+)    | 9        | 6.52%   |
| 1920x1200 (WUXGA) | 4        | 2.9%    |
| 1366x768 (WXGA)   | 3        | 2.17%   |
| 3840x2160 (4K)    | 2        | 1.45%   |
| 3440x1440         | 1        | 0.72%   |
| 1600x1200         | 1        | 0.72%   |
| 1440x900 (WXGA+)  | 1        | 0.72%   |
| 1280x960          | 1        | 0.72%   |
| 1024x768 (XGA)    | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 35       | 23.33%  |
| 23     | 33       | 22%     |
| 21     | 24       | 16%     |
| 27     | 18       | 12%     |
| 20     | 10       | 6.67%   |
| 19     | 10       | 6.67%   |
| 17     | 7        | 4.67%   |
| 31     | 4        | 2.67%   |
| 18     | 3        | 2%      |
| 25     | 2        | 1.33%   |
| 15     | 2        | 1.33%   |
| 34     | 1        | 0.67%   |
| 32     | 1        | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 79       | 56.43%  |
| 401-500     | 36       | 25.71%  |
| 351-400     | 10       | 7.14%   |
| 301-350     | 9        | 6.43%   |
| 601-700     | 4        | 2.86%   |
| 701-800     | 2        | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 111      | 81.02%  |
| 5/4   | 17       | 12.41%  |
| 16/10 | 6        | 4.38%   |
| 4/3   | 2        | 1.46%   |
| 21/9  | 1        | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 73       | 51.05%  |
| 151-200        | 29       | 20.28%  |
| 301-350        | 18       | 12.59%  |
| 141-150        | 9        | 6.29%   |
| 351-500        | 6        | 4.2%    |
| 251-300        | 6        | 4.2%    |
| 101-110        | 2        | 1.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 103      | 75.74%  |
| 101-120 | 33       | 24.26%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 120      | 69.77%  |
| 0     | 31       | 18.02%  |
| 2     | 21       | 12.21%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 119      | 60.71%  |
| Intel                    | 51       | 26.02%  |
| Qualcomm Atheros         | 3        | 1.53%   |
| Nvidia                   | 3        | 1.53%   |
| Broadcom                 | 3        | 1.53%   |
| TP-Link                  | 2        | 1.02%   |
| Samsung Electronics      | 2        | 1.02%   |
| Ralink Technology        | 2        | 1.02%   |
| Mercucys                 | 2        | 1.02%   |
| MediaTek                 | 2        | 1.02%   |
| VIA Technologies         | 1        | 0.51%   |
| Ralink                   | 1        | 0.51%   |
| Metrologic Instruments   | 1        | 0.51%   |
| Marvell Technology Group | 1        | 0.51%   |
| Huawei Technologies      | 1        | 0.51%   |
| Edimax Technology        | 1        | 0.51%   |
| ASIX Electronics         | 1        | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 104      | 47.93%  |
| Intel Ethernet Controller I225-V                                  | 8        | 3.69%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 3.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 2.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2.3%    |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 1.84%   |
| Intel Ethernet Connection (17) I219-V                             | 4        | 1.84%   |
| Realtek 802.11ac NIC                                              | 3        | 1.38%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.92%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.92%   |
| Mercucys 802.11n NIC                                              | 2        | 0.92%   |
| Intel Wireless 7265                                               | 2        | 0.92%   |
| Intel Wireless 3165                                               | 2        | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2        | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.92%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.92%   |
| Intel Ethernet Connection (10) I219-V                             | 2        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 0.92%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.46%   |
| TP-Link USB 10/100 LAN                                            | 1        | 0.46%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.46%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1        | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.46%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.46%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 43.59%  |
| Intel                 | 12       | 30.77%  |
| Ralink Technology     | 2        | 5.13%   |
| Mercucys              | 2        | 5.13%   |
| Broadcom              | 2        | 5.13%   |
| TP-Link               | 1        | 2.56%   |
| Ralink                | 1        | 2.56%   |
| MediaTek              | 1        | 2.56%   |
| Edimax Technology     | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 5        | 12.82%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 5        | 12.82%  |
| Realtek 802.11ac NIC                                            | 3        | 7.69%   |
| Ralink MT7601U Wireless Adapter                                 | 2        | 5.13%   |
| Mercucys 802.11n NIC                                            | 2        | 5.13%   |
| Intel Wireless 7265                                             | 2        | 5.13%   |
| Intel Wireless 3165                                             | 2        | 5.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 2        | 5.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 5.13%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 2        | 5.13%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 2.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 2.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 2.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1        | 2.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1        | 2.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                       | 1        | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1        | 2.56%   |
| Intel Wireless 7260                                             | 1        | 2.56%   |
| Intel 700 Series Chipset Family Wi-Fi                           | 1        | 2.56%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 2.56%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter    | 1        | 2.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 1        | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 112      | 64.74%  |
| Intel                    | 46       | 26.59%  |
| Qualcomm Atheros         | 3        | 1.73%   |
| Nvidia                   | 3        | 1.73%   |
| Samsung Electronics      | 2        | 1.16%   |
| VIA Technologies         | 1        | 0.58%   |
| TP-Link                  | 1        | 0.58%   |
| MediaTek                 | 1        | 0.58%   |
| Marvell Technology Group | 1        | 0.58%   |
| Huawei Technologies      | 1        | 0.58%   |
| Broadcom                 | 1        | 0.58%   |
| ASIX Electronics         | 1        | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 104      | 58.76%  |
| Intel Ethernet Controller I225-V                                  | 8        | 4.52%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 4.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 3.39%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 2.26%   |
| Intel Ethernet Connection (17) I219-V                             | 4        | 2.26%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.69%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.13%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.13%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.13%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.13%   |
| Intel Ethernet Connection (10) I219-V                             | 2        | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.13%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.56%   |
| TP-Link USB 10/100 LAN                                            | 1        | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.56%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.56%   |
| MediaTek Wiko U316AT                                              | 1        | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.56%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.56%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 0.56%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.56%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.56%   |
| Huawei ALP-AL00                                                   | 1        | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 80.39%  |
| WiFi     | 39       | 19.12%  |
| Modem    | 1        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 157      | 94.01%  |
| WiFi     | 10       | 5.99%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 131      | 79.39%  |
| 2     | 33       | 20%     |
| 4     | 1        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 163      | 98.79%  |
| Yes  | 2        | 1.21%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 12       | 42.86%  |
| Realtek Semiconductor   | 8        | 28.57%  |
| Cambridge Silicon Radio | 3        | 10.71%  |
| Broadcom                | 2        | 7.14%   |
| TP-Link                 | 1        | 3.57%   |
| MediaTek                | 1        | 3.57%   |
| ASUSTek Computer        | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 8        | 28.57%  |
| Intel Bluetooth wireless interface                  | 5        | 17.86%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 10.71%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 7.14%   |
| Intel Bluetooth Device                              | 2        | 7.14%   |
| Intel AX201 Bluetooth                               | 2        | 7.14%   |
| TP-Link UB500 Adapter                               | 1        | 3.57%   |
| MediaTek Wireless_Device                            | 1        | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.57%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 3.57%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 3.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 135      | 64.9%   |
| AMD                    | 34       | 16.35%  |
| Nvidia                 | 27       | 12.98%  |
| Texas Instruments      | 4        | 1.92%   |
| C-Media Electronics    | 3        | 1.44%   |
| Samson Technologies    | 1        | 0.48%   |
| Razer USA              | 1        | 0.48%   |
| Logitech               | 1        | 0.48%   |
| Generalplus Technology | 1        | 0.48%   |
| Creative Technology    | 1        | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Smart Sound Technology (SST) Audio Controller                        | 32       | 13.5%   |
| Intel 200 Series PCH HD Audio                                              | 18       | 7.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 18       | 7.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 5.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12       | 5.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 4.22%   |
| Intel Comet Lake PCH-V cAVS                                                | 9        | 3.8%    |
| Intel Alder Lake-S HD Audio Controller                                     | 9        | 3.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 3.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.53%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 2.53%   |
| Nvidia High Definition Audio Controller                                    | 5        | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 2.11%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.11%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4        | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.69%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.27%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 0.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 0.84%   |
| Samson Technologies C01U Pro condenser microphone                          | 1        | 0.42%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.42%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.42%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.42%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.42%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.42%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.42%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Crucial                            | 30       | 17.54%  |
| Kingston                           | 21       | 12.28%  |
| Unknown                            | 18       | 10.53%  |
| Foxline                            | 15       | 8.77%   |
| Samsung Electronics                | 12       | 7.02%   |
| SK hynix                           | 10       | 5.85%   |
| Apacer                             | 10       | 5.85%   |
| AMD                                | 9        | 5.26%   |
| Patriot                            | 7        | 4.09%   |
| A-DATA Technology                  | 6        | 3.51%   |
| Unknown                            | 4        | 2.34%   |
| Elpida                             | 3        | 1.75%   |
| Corsair                            | 3        | 1.75%   |
| Unknown (ABCD)                     | 2        | 1.17%   |
| Neo Forza                          | 2        | 1.17%   |
| Micron Technology                  | 2        | 1.17%   |
| HomeNet                            | 2        | 1.17%   |
| Unknown (8AD6)                     | 1        | 0.58%   |
| Unknown (89F7)                     | 1        | 0.58%   |
| Unknown (0x0080)                   | 1        | 0.58%   |
| Shenzhen Micro Innovation Industry | 1        | 0.58%   |
| SHARETRONIC                        | 1        | 0.58%   |
| Qumo                               | 1        | 0.58%   |
| Patriot Memory (PDP Systems)       | 1        | 0.58%   |
| KingSpec                           | 1        | 0.58%   |
| Innodisk                           | 1        | 0.58%   |
| Good Wealth                        | 1        | 0.58%   |
| Goldkey                            | 1        | 0.58%   |
| Golden Empire                      | 1        | 0.58%   |
| Gold Key                           | 1        | 0.58%   |
| G.Skill                            | 1        | 0.58%   |
| ChangXin Memory                    | 1        | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s              | 6        | 3.39%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s            | 5        | 2.82%   |
| Unknown                                                        | 4        | 2.26%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s            | 3        | 1.69%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                    | 3        | 1.69%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 2        | 1.13%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 1.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 1.13%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 1.13%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                       | 2        | 1.13%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                | 2        | 1.13%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s          | 2        | 1.13%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 1.13%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s          | 2        | 1.13%   |
| HomeNet RAM HN SO 8GB 8192MB SODIMM DDR4 3200MT/s              | 2        | 1.13%   |
| Crucial RAM ST51264BA1339.16FK 4GB DIMM DDR3 1067MT/s          | 2        | 1.13%   |
| Crucial RAM CT8G4SFRA32A.C16FG 8GB SODIMM DDR4 3200MT/s        | 2        | 1.13%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s         | 2        | 1.13%   |
| Crucial RAM CT8G4DFRA32A.M8FR 8192MB DIMM DDR4 3533MT/s        | 2        | 1.13%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2667MT/s           | 2        | 1.13%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s         | 2        | 1.13%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 1.13%   |
| Apacer RAM D12.2324CH.002 8GB DIMM DDR4 3200MT/s               | 2        | 1.13%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 1.13%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 0.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.56%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR 1066MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                      | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.56%   |
| Unknown RAM Module 1GB DIMM SDRAM 1066MT/s                     | 1        | 0.56%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 113      | 70.19%  |
| DDR3    | 25       | 15.53%  |
| DDR2    | 7        | 4.35%   |
| SDRAM   | 6        | 3.73%   |
| Unknown | 5        | 3.11%   |
| LPDDR4  | 3        | 1.86%   |
| DDR5    | 1        | 0.62%   |
| DDR     | 1        | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 139      | 86.34%  |
| SODIMM | 22       | 13.66%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 89       | 51.74%  |
| 4096  | 34       | 19.77%  |
| 16384 | 20       | 11.63%  |
| 2048  | 14       | 8.14%   |
| 1024  | 8        | 4.65%   |
| 32768 | 6        | 3.49%   |
| 512   | 1        | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 44       | 25.88%  |
| 3200    | 31       | 18.24%  |
| 1333    | 13       | 7.65%   |
| 2400    | 12       | 7.06%   |
| 1600    | 8        | 4.71%   |
| 2133    | 6        | 3.53%   |
| 2666    | 5        | 2.94%   |
| 2933    | 4        | 2.35%   |
| 800     | 4        | 2.35%   |
| 3600    | 3        | 1.76%   |
| 2800    | 3        | 1.76%   |
| 1800    | 3        | 1.76%   |
| 533     | 3        | 1.76%   |
| Unknown | 3        | 1.76%   |
| 3533    | 2        | 1.18%   |
| 3266    | 2        | 1.18%   |
| 2934    | 2        | 1.18%   |
| 1866    | 2        | 1.18%   |
| 1067    | 2        | 1.18%   |
| 1066    | 2        | 1.18%   |
| 667     | 2        | 1.18%   |
| 333     | 2        | 1.18%   |
| 5200    | 1        | 0.59%   |
| 3866    | 1        | 0.59%   |
| 3800    | 1        | 0.59%   |
| 3733    | 1        | 0.59%   |
| 3466    | 1        | 0.59%   |
| 3000    | 1        | 0.59%   |
| 2866    | 1        | 0.59%   |
| 2733    | 1        | 0.59%   |
| 2187    | 1        | 0.59%   |
| 2134    | 1        | 0.59%   |
| 1648    | 1        | 0.59%   |
| 400     | 1        | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 50%     |
| Pantum          | 1        | 25%     |
| Kyocera         | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Pantum BM5100ADN series  | 1        | 25%     |
| Kyocera FS-1040          | 1        | 25%     |
| HP LaserJet P2055 series | 1        | 25%     |
| HP LaserJet M109-M112    | 1        | 25%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| SunplusIT                     | 8        | 26.67%  |
| Alcor Micro                   | 5        | 16.67%  |
| Realtek Semiconductor         | 3        | 10%     |
| Microdia                      | 3        | 10%     |
| Logitech                      | 3        | 10%     |
| Chicony Electronics           | 2        | 6.67%   |
| Sunplus Innovation Technology | 1        | 3.33%   |
| KYE Systems (Mouse Systems)   | 1        | 3.33%   |
| Creative Technology           | 1        | 3.33%   |
| Arkmicro Technologies         | 1        | 3.33%   |
| Apple                         | 1        | 3.33%   |
| AlcorMicroCorp                | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| SunplusIT USB Camera                      | 7        | 23.33%  |
| Alcor Micro USB 2.0 PC Camera             | 4        | 13.33%  |
| Microdia Camera                           | 3        | 10%     |
| Logitech HD Webcam C615                   | 3        | 10%     |
| Realtek 1080p Camera                      | 2        | 6.67%   |
| SunplusIT AEEVISION Camera                | 1        | 3.33%   |
| Sunplus USB Microphone                    | 1        | 3.33%   |
| Realtek USB Camera                        | 1        | 3.33%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 3.33%   |
| Creative VF0530 Live! Cam Chat IM         | 1        | 3.33%   |
| Chicony HP High Definition 1MP Webcam     | 1        | 3.33%   |
| Chicony HP 0.3MP Webcam                   | 1        | 3.33%   |
| Arkmicro USB2.0 PC CAMERA                 | 1        | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 1        | 3.33%   |
| AlcorMicroCorp SHUNCCM                    | 1        | 3.33%   |
| Alcor Micro USB FHD Camera                | 1        | 3.33%   |

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
| 0     | 132      | 78.57%  |
| 1     | 33       | 19.64%  |
| 4     | 1        | 0.6%    |
| 3     | 1        | 0.6%    |
| 2     | 1        | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 31       | 73.81%  |
| Net/wireless             | 4        | 9.52%   |
| Communication controller | 3        | 7.14%   |
| Sound                    | 1        | 2.38%   |
| Network                  | 1        | 2.38%   |
| Net/ethernet             | 1        | 2.38%   |
| Chipcard                 | 1        | 2.38%   |

