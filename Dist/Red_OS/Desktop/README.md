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

Total: 263

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | H97M-E                      | [090fcf5a52](https://linux-hardware.org/?probe=090fcf5a52) | Dec 21, 2023 |
| Lenovo        | ThinkCentre A70 7099L8G     | [9720608634](https://linux-hardware.org/?probe=9720608634) | Dec 20, 2023 |
| ASUSTek       | PRIME B360M-K               | [d52ec68e39](https://linux-hardware.org/?probe=d52ec68e39) | Dec 18, 2023 |
| Biostar       | H610MH                      | [6a0d454360](https://linux-hardware.org/?probe=6a0d454360) | Dec 18, 2023 |
| MSI           | A320M-A PRO                 | [0542ba556a](https://linux-hardware.org/?probe=0542ba556a) | Dec 10, 2023 |
| ASRock        | B365M-ITX/ac                | [01d47685dd](https://linux-hardware.org/?probe=01d47685dd) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ae4263fce1](https://linux-hardware.org/?probe=ae4263fce1) | Nov 28, 2023 |
| Gigabyte      | H410M S2H V2                | [07a85d20b8](https://linux-hardware.org/?probe=07a85d20b8) | Nov 27, 2023 |
| ASUSTek       | P8H61 PRO                   | [f5ae04b987](https://linux-hardware.org/?probe=f5ae04b987) | Nov 22, 2023 |
| Dell          | 0MGK50 A02                  | [44cca29f66](https://linux-hardware.org/?probe=44cca29f66) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | [e029a02461](https://linux-hardware.org/?probe=e029a02461) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | [966108e5dc](https://linux-hardware.org/?probe=966108e5dc) | Nov 21, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [b95aa31de0](https://linux-hardware.org/?probe=b95aa31de0) | Nov 21, 2023 |
| Gigabyte      | H61M-S1                     | [5b55e90cd2](https://linux-hardware.org/?probe=5b55e90cd2) | Nov 20, 2023 |
| ASUSTek       | Z87-A                       | [ef419190cb](https://linux-hardware.org/?probe=ef419190cb) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | [c492bd0c05](https://linux-hardware.org/?probe=c492bd0c05) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [05b1279d72](https://linux-hardware.org/?probe=05b1279d72) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | [d203bd1f2e](https://linux-hardware.org/?probe=d203bd1f2e) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | [3fb45b3fae](https://linux-hardware.org/?probe=3fb45b3fae) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | [1e85870bb4](https://linux-hardware.org/?probe=1e85870bb4) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d97ba119eb](https://linux-hardware.org/?probe=d97ba119eb) | Nov 20, 2023 |
| Unknown       | TA320 Series                | [2ba015f4da](https://linux-hardware.org/?probe=2ba015f4da) | Nov 20, 2023 |
| ASRock        | B365M-ITX/ac                | [d9aef8d62e](https://linux-hardware.org/?probe=d9aef8d62e) | Nov 20, 2023 |
| ONDA          | H410D4 IPC                  | [5ace66c92d](https://linux-hardware.org/?probe=5ace66c92d) | Nov 20, 2023 |
| BESHTAU       | B560RU V51                  | [188829d0c2](https://linux-hardware.org/?probe=188829d0c2) | Nov 20, 2023 |
| ICL           | H410SB-TM2                  | [d63641c6e3](https://linux-hardware.org/?probe=d63641c6e3) | Nov 17, 2023 |
| Gigabyte      | B75M-D3V                    | [2ca3738c72](https://linux-hardware.org/?probe=2ca3738c72) | Nov 17, 2023 |
| ASRock        | H81M-DG4                    | [089b0f3839](https://linux-hardware.org/?probe=089b0f3839) | Nov 17, 2023 |
| ASRock        | B365M Pro4-F                | [cc09f89cd0](https://linux-hardware.org/?probe=cc09f89cd0) | Nov 09, 2023 |
| ASRock        | B365M Pro4-F                | [17ec369170](https://linux-hardware.org/?probe=17ec369170) | Nov 09, 2023 |
| Gigabyte      | A320M-H-CF                  | [290c167538](https://linux-hardware.org/?probe=290c167538) | Nov 08, 2023 |
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
| Red OS 7.3   | 96       | 47.76%  |
| Red OS 7.3.1 | 49       | 24.38%  |
| Red OS 7.3.2 | 47       | 23.38%  |
| Red OS 7.2   | 8        | 3.98%   |
| Red OS 8.0   | 1        | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 191      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.15.87-1.el7.3.x86_64  | 26       | 12.32%  |
| 5.15.10-1.el7.x86_64    | 26       | 12.32%  |
| 5.10.29-1.el7.x86_64    | 24       | 11.37%  |
| 6.1.52-1.el7.3.x86_64   | 21       | 9.95%   |
| 5.15.35-5.el7.3.x86_64  | 19       | 9%      |
| 5.15.72-1.el7.3.x86_64  | 17       | 8.06%   |
| 5.15.78-2.el7.3.x86_64  | 11       | 5.21%   |
| 5.15.35-1.el7.3.x86_64  | 9        | 4.27%   |
| 5.14.9-1.el7.x86_64     | 8        | 3.79%   |
| 6.1.44-1.el7.3.x86_64   | 7        | 3.32%   |
| 5.15.35-4.el7.3.x86_64  | 7        | 3.32%   |
| 5.10.29-3.el7.x86_64    | 7        | 3.32%   |
| 4.19.79-1.el7.x86_64    | 6        | 2.84%   |
| 6.1.20-2.el7.3.x86_64   | 4        | 1.9%    |
| 5.15.131-1.el7.3.x86_64 | 4        | 1.9%    |
| 5.15.10-3.el7.x86_64    | 3        | 1.42%   |
| 5.15.10-2.el7.x86_64    | 3        | 1.42%   |
| 6.1.38-2.el7.3.x86_64   | 2        | 0.95%   |
| 6.1.52-1.red80.x86_64   | 1        | 0.47%   |
| 6.1.11-1.el7.3.x86_64   | 1        | 0.47%   |
| 5.10.24-3.el7.x86_64    | 1        | 0.47%   |
| 5.10.24-2.el7.x86_64    | 1        | 0.47%   |
| 5.10.1-1.el7.x86_64     | 1        | 0.47%   |
| 4.19.56-2.el7.x86_64    | 1        | 0.47%   |
| 4.19.204-1.el7.x86_64   | 1        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.35  | 32       | 15.38%  |
| 5.15.10  | 32       | 15.38%  |
| 5.10.29  | 31       | 14.9%   |
| 5.15.87  | 26       | 12.5%   |
| 6.1.52   | 22       | 10.58%  |
| 5.15.72  | 17       | 8.17%   |
| 5.15.78  | 11       | 5.29%   |
| 5.14.9   | 8        | 3.85%   |
| 6.1.44   | 7        | 3.37%   |
| 4.19.79  | 6        | 2.88%   |
| 6.1.20   | 4        | 1.92%   |
| 5.15.131 | 4        | 1.92%   |
| 6.1.38   | 2        | 0.96%   |
| 5.10.24  | 2        | 0.96%   |
| 6.1.11   | 1        | 0.48%   |
| 5.10.1   | 1        | 0.48%   |
| 4.19.56  | 1        | 0.48%   |
| 4.19.204 | 1        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 113      | 56.78%  |
| 6.1     | 36       | 18.09%  |
| 5.10    | 34       | 17.09%  |
| 5.14    | 8        | 4.02%   |
| 4.19    | 8        | 4.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 191      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 158      | 79.8%   |
| Cinnamon   | 27       | 13.64%  |
| X-Cinnamon | 7        | 3.54%   |
| Unknown    | 5        | 2.53%   |
| GNOME      | 1        | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 167      | 86.08%  |
| Tty     | 19       | 9.79%   |
| Wayland | 6        | 3.09%   |
| Unknown | 2        | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 180      | 93.75%  |
| Unknown | 7        | 3.65%   |
| LightDM | 3        | 1.56%   |
| SDDM    | 2        | 1.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 98       | 50%     |
| Unknown | 95       | 48.47%  |
| en_US   | 3        | 1.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 129      | 66.49%  |
| BIOS | 65       | 33.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 188      | 97.41%  |
| Btrfs   | 4        | 2.07%   |
| Unknown | 1        | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 129      | 66.84%  |
| MBR     | 61       | 31.61%  |
| Unknown | 3        | 1.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 180      | 92.78%  |
| Yes       | 14       | 7.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 151      | 78.24%  |
| Yes       | 42       | 21.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 55       | 28.8%   |
| ASUSTek Computer    | 35       | 18.32%  |
| ASRock              | 24       | 12.57%  |
| MSI                 | 18       | 9.42%   |
| Hewlett-Packard     | 8        | 4.19%   |
| DEPO Computers      | 8        | 4.19%   |
| Lenovo              | 7        | 3.66%   |
| Aquarius            | 7        | 3.66%   |
| Unknown             | 7        | 3.66%   |
| Intel               | 5        | 2.62%   |
| Dell                | 3        | 1.57%   |
| Biostar             | 3        | 1.57%   |
| ICL                 | 2        | 1.05%   |
| RDW                 | 1        | 0.52%   |
| Quanta              | 1        | 0.52%   |
| ONDA                | 1        | 0.52%   |
| iRU                 | 1        | 0.52%   |
| Foxconn             | 1        | 0.52%   |
| ECS                 | 1        | 0.52%   |
| Compal              | 1        | 0.52%   |
| Colorful Technology | 1        | 0.52%   |
| BESHTAU             | 1        | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 7        | 3.66%   |
| Gigabyte B365M DS3H             | 5        | 2.62%   |
| ASRock H510M-HVS R2.0           | 5        | 2.62%   |
| DEPO Computers DPH310T          | 4        | 2.09%   |
| ASUS All Series                 | 4        | 2.09%   |
| MSI MS-7D14                     | 3        | 1.57%   |
| MSI MS-7C51                     | 3        | 1.57%   |
| Intel D945GNT AAC96315-405      | 3        | 1.57%   |
| Gigabyte H110M-S2               | 3        | 1.57%   |
| Gigabyte A320M-S2H              | 3        | 1.57%   |
| DEPO Computers DPH410S          | 3        | 1.57%   |
| Biostar H610MH                  | 3        | 1.57%   |
| ASRock H61M-DGS                 | 3        | 1.57%   |
| ASRock B365M-ITX/ac             | 3        | 1.57%   |
| MSI MS-7D22                     | 2        | 1.05%   |
| Gigabyte H510M H                | 2        | 1.05%   |
| Gigabyte H270-HD3               | 2        | 1.05%   |
| Gigabyte B75M-D3V               | 2        | 1.05%   |
| Gigabyte B560M DS3H             | 2        | 1.05%   |
| Gigabyte B550 AORUS ELITE V2    | 2        | 1.05%   |
| Gigabyte B365M H                | 2        | 1.05%   |
| ASUS PRIME H510T2/CSM           | 2        | 1.05%   |
| ASUS PRIME H310M-R R2.0         | 2        | 1.05%   |
| ASUS PRIME B350M-K              | 2        | 1.05%   |
| ASUS PC                         | 2        | 1.05%   |
| ASUS P8H61 PRO                  | 2        | 1.05%   |
| ASUS MINIPC PB62                | 2        | 1.05%   |
| Aquarius P30 K44 R53            | 2        | 1.05%   |
| Aquarius AQB560M                | 2        | 1.05%   |
| RDW RDW-MB-B450M V.1            | 1        | 0.52%   |
| Quanta 120-1104er               | 1        | 0.52%   |
| ONDA H410D4 IPC                 | 1        | 0.52%   |
| MSI PRO H610 DP21 13M (MS-B0A4) | 1        | 0.52%   |
| MSI MS-7E07                     | 1        | 0.52%   |
| MSI MS-7D48                     | 1        | 0.52%   |
| MSI MS-7D46                     | 1        | 0.52%   |
| MSI MS-7D35                     | 1        | 0.52%   |
| MSI MS-7B86                     | 1        | 0.52%   |
| MSI MS-7636                     | 1        | 0.52%   |
| MSI MS-7592                     | 1        | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 13       | 6.81%   |
| Gigabyte B365M         | 7        | 3.66%   |
| Unknown                | 7        | 3.66%   |
| Gigabyte B560M         | 5        | 2.62%   |
| ASRock H510M-HVS       | 5        | 2.62%   |
| Gigabyte A320M-S2H     | 4        | 2.09%   |
| DEPO Computers DPH310T | 4        | 2.09%   |
| ASUS All               | 4        | 2.09%   |
| MSI MS-7D14            | 3        | 1.57%   |
| MSI MS-7C51            | 3        | 1.57%   |
| Lenovo ThinkCentre     | 3        | 1.57%   |
| Intel D945GNT          | 3        | 1.57%   |
| HP ProDesk             | 3        | 1.57%   |
| Gigabyte H510M         | 3        | 1.57%   |
| Gigabyte H410M         | 3        | 1.57%   |
| Gigabyte H110M-S2      | 3        | 1.57%   |
| Gigabyte B550          | 3        | 1.57%   |
| DEPO Computers DPH410S | 3        | 1.57%   |
| Dell OptiPlex          | 3        | 1.57%   |
| Biostar H610MH         | 3        | 1.57%   |
| ASRock H61M-DGS        | 3        | 1.57%   |
| ASRock B365M-ITX       | 3        | 1.57%   |
| MSI MS-7D22            | 2        | 1.05%   |
| ICL RAY                | 2        | 1.05%   |
| HP Compaq              | 2        | 1.05%   |
| Gigabyte H270-HD3      | 2        | 1.05%   |
| Gigabyte B75M-D3V      | 2        | 1.05%   |
| Gigabyte B450          | 2        | 1.05%   |
| ASUS PC                | 2        | 1.05%   |
| ASUS P8H61             | 2        | 1.05%   |
| ASUS MINIPC            | 2        | 1.05%   |
| Aquarius Pro           | 2        | 1.05%   |
| Aquarius P30           | 2        | 1.05%   |
| Aquarius AQB560M       | 2        | 1.05%   |
| RDW RDW-MB-B450M       | 1        | 0.52%   |
| Quanta 120-1104er      | 1        | 0.52%   |
| ONDA H410D4            | 1        | 0.52%   |
| MSI PRO                | 1        | 0.52%   |
| MSI MS-7E07            | 1        | 0.52%   |
| MSI MS-7D48            | 1        | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 44       | 23.04%  |
| 2022 | 23       | 12.04%  |
| 2019 | 22       | 11.52%  |
| 2018 | 15       | 7.85%   |
| 2020 | 14       | 7.33%   |
| 2012 | 13       | 6.81%   |
| 2011 | 10       | 5.24%   |
| 2016 | 8        | 4.19%   |
| 2017 | 7        | 3.66%   |
| 2013 | 7        | 3.66%   |
| 2010 | 6        | 3.14%   |
| 2014 | 5        | 2.62%   |
| 2015 | 4        | 2.09%   |
| 2007 | 4        | 2.09%   |
| 2009 | 3        | 1.57%   |
| 2006 | 3        | 1.57%   |
| 2023 | 2        | 1.05%   |
| 2008 | 1        | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 191      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 188      | 98.43%  |
| Enabled  | 3        | 1.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 191      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 68       | 35.6%   |
| 16.01-24.0  | 51       | 26.7%   |
| 3.01-4.0    | 27       | 14.14%  |
| 8.01-16.0   | 23       | 12.04%  |
| 32.01-64.0  | 7        | 3.66%   |
| 1.01-2.0    | 6        | 3.14%   |
| 24.01-32.0  | 3        | 1.57%   |
| 2.01-3.0    | 3        | 1.57%   |
| 64.01-256.0 | 1        | 0.52%   |
| 0.51-1.0    | 1        | 0.52%   |
| Unknown     | 1        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 87       | 42.86%  |
| 2.01-3.0  | 41       | 20.2%   |
| 4.01-8.0  | 26       | 12.81%  |
| 3.01-4.0  | 21       | 10.34%  |
| 0.51-1.0  | 18       | 8.87%   |
| 8.01-16.0 | 6        | 2.96%   |
| 0.01-0.5  | 3        | 1.48%   |
| Unknown   | 1        | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 130      | 66.33%  |
| 2      | 49       | 25%     |
| 3      | 11       | 5.61%   |
| 4      | 4        | 2.04%   |
| 5      | 2        | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 67.71%  |
| Yes       | 62       | 32.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 190      | 99.48%  |
| No        | 1        | 0.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 76.29%  |
| Yes       | 46       | 23.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 82.9%   |
| Yes       | 33       | 17.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 191      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 33       | 16.92%  |
| Salekhard         | 27       | 13.85%  |
| Murom             | 24       | 12.31%  |
| Novy Urengoy      | 14       | 7.18%   |
| Yekaterinburg     | 7        | 3.59%   |
| Perm              | 7        | 3.59%   |
| Zima              | 5        | 2.56%   |
| Labytnangi        | 5        | 2.56%   |
| Krasnodar         | 4        | 2.05%   |
| Volgograd         | 3        | 1.54%   |
| Tver              | 3        | 1.54%   |
| Stavropol         | 3        | 1.54%   |
| St Petersburg     | 3        | 1.54%   |
| Novosibirsk       | 3        | 1.54%   |
| Muromskiy         | 3        | 1.54%   |
| Bryansk           | 3        | 1.54%   |
| Balashikha        | 3        | 1.54%   |
| Veliky Novgorod   | 2        | 1.03%   |
| Tomsk             | 2        | 1.03%   |
| Penza             | 2        | 1.03%   |
| Nal'chik          | 2        | 1.03%   |
| Nadym             | 2        | 1.03%   |
| Kurgan            | 2        | 1.03%   |
| Kol'chugino       | 2        | 1.03%   |
| Kirov             | 2        | 1.03%   |
| Khabarovsk        | 2        | 1.03%   |
| Kaluga            | 2        | 1.03%   |
| Baksan            | 2        | 1.03%   |
| Yuzhno-Sakhalinsk | 1        | 0.51%   |
| Vladimir          | 1        | 0.51%   |
| Ulyanovsk         | 1        | 0.51%   |
| Tyumen            | 1        | 0.51%   |
| Svetlograd        | 1        | 0.51%   |
| Surgut            | 1        | 0.51%   |
| Shakhtersk        | 1        | 0.51%   |
| Rostov-on-Don     | 1        | 0.51%   |
| Pushkino          | 1        | 0.51%   |
| Nyandoma          | 1        | 0.51%   |
| Nyagan            | 1        | 0.51%   |
| Nizhniy Novgorod  | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 54       | 75     | 20.38%  |
| WDC                          | 39       | 49     | 14.72%  |
| Toshiba                      | 28       | 36     | 10.57%  |
| Kingston                     | 21       | 23     | 7.92%   |
| Samsung Electronics          | 19       | 26     | 7.17%   |
| A-DATA Technology            | 19       | 20     | 7.17%   |
| Apacer                       | 10       | 10     | 3.77%   |
| Foxline                      | 7        | 7      | 2.64%   |
| Crucial                      | 6        | 10     | 2.26%   |
| SanDisk                      | 5        | 8      | 1.89%   |
| Patriot                      | 5        | 5      | 1.89%   |
| KingSpec                     | 5        | 5      | 1.89%   |
| Hitachi                      | 5        | 5      | 1.89%   |
| Intel                        | 4        | 4      | 1.51%   |
| ExeGate                      | 4        | 5      | 1.51%   |
| Netac                        | 3        | 3      | 1.13%   |
| China                        | 3        | 3      | 1.13%   |
| AMD                          | 3        | 3      | 1.13%   |
| AGI                          | 3        | 3      | 1.13%   |
| SPCC                         | 2        | 2      | 0.75%   |
| Shenzhen Longsys Electronics | 2        | 2      | 0.75%   |
| Qumo                         | 2        | 2      | 0.75%   |
| KIOXIA-EXCERIA               | 2        | 2      | 0.75%   |
| HYDRA                        | 2        | 2      | 0.75%   |
| Unknown                      | 2        | 2      | 0.75%   |
| XPG                          | 1        | 1      | 0.38%   |
| Unknown                      | 1        | 1      | 0.38%   |
| Smartbuy                     | 1        | 1      | 0.38%   |
| Silicon Motion               | 1        | 1      | 0.38%   |
| Phison                       | 1        | 1      | 0.38%   |
| MSI                          | 1        | 1      | 0.38%   |
| HS-SSD-E100                  | 1        | 1      | 0.38%   |
| GOODRAM                      | 1        | 1      | 0.38%   |
| Dahua                        | 1        | 1      | 0.38%   |
| Corsair                      | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                  | 13       | 4.68%   |
| Seagate ST500DM002-1BD142 500GB      | 10       | 3.6%    |
| Seagate ST1000DM010-2EP102 1TB       | 7        | 2.52%   |
| Kingston SA400S37240G 240GB SSD      | 7        | 2.52%   |
| Toshiba DT01ACA100 1TB               | 6        | 2.16%   |
| A-DATA SX6000PNP 256GB               | 6        | 2.16%   |
| Seagate ST1000LM049-2GH172 1TB       | 5        | 1.8%    |
| Seagate ST3160811AS 160GB            | 4        | 1.44%   |
| Kingston SA400S37480G 480GB SSD      | 4        | 1.44%   |
| Apacer AS2280P4 256GB                | 4        | 1.44%   |
| Toshiba HDWL110 1TB                  | 3        | 1.08%   |
| Seagate ST1000DM010-2DM162 1TB       | 3        | 1.08%   |
| Samsung SSD 870 EVO 250GB            | 3        | 1.08%   |
| Kingston SA400S37120G 120GB SSD      | 3        | 1.08%   |
| Crucial CT240BX500SSD1 240GB         | 3        | 1.08%   |
| Apacer AS340 240GB SSD               | 3        | 1.08%   |
| AGI AGI512G16AI198 512GB             | 3        | 1.08%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2        | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2        | 0.72%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 2        | 0.72%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2        | 0.72%   |
| WDC WD10EZEX-00BBHA0 1TB             | 2        | 0.72%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB | 2        | 0.72%   |
| Toshiba HDWD105 500GB                | 2        | 0.72%   |
| Toshiba DT01ACA050 500GB             | 2        | 0.72%   |
| Seagate ST3500413AS 500GB            | 2        | 0.72%   |
| Seagate ST1000DM003-1SB10C 1TB       | 2        | 0.72%   |
| SanDisk SD8SBAT256G1122 256GB SSD    | 2        | 0.72%   |
| Samsung SSD 980 PRO 500GB            | 2        | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 0.72%   |
| Samsung SSD 860 EVO 250GB            | 2        | 0.72%   |
| Samsung HD161HJ 160GB                | 2        | 0.72%   |
| Patriot Burst Elite 240GB SSD        | 2        | 0.72%   |
| KIOXIA-EXCERIA SATA SSD 480GB        | 2        | 0.72%   |
| Kingston SNVS500G 500GB              | 2        | 0.72%   |
| Kingston OM8PCP3512F-A02 512GB       | 2        | 0.72%   |
| KingSpec P3-256 256GB SSD            | 2        | 0.72%   |
| HYDRA SSD 256G                       | 2        | 0.72%   |
| Foxline FLSSD240X5SE 240GB           | 2        | 0.72%   |
| ExeGate EX276690RUS(960G 960GB SSD   | 2        | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 53       | 74     | 44.17%  |
| WDC                 | 31       | 38     | 25.83%  |
| Toshiba             | 27       | 35     | 22.5%   |
| Hitachi             | 5        | 5      | 4.17%   |
| Samsung Electronics | 4        | 5      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 16       | 17     | 16.67%  |
| A-DATA Technology   | 9        | 9      | 9.38%   |
| Samsung Electronics | 8        | 10     | 8.33%   |
| WDC                 | 7        | 7      | 7.29%   |
| Foxline             | 6        | 6      | 6.25%   |
| Apacer              | 6        | 6      | 6.25%   |
| KingSpec            | 5        | 5      | 5.21%   |
| Crucial             | 5        | 9      | 5.21%   |
| SanDisk             | 4        | 7      | 4.17%   |
| Patriot             | 4        | 4      | 4.17%   |
| ExeGate             | 4        | 5      | 4.17%   |
| Intel               | 3        | 3      | 3.13%   |
| China               | 3        | 3      | 3.13%   |
| Qumo                | 2        | 2      | 2.08%   |
| KIOXIA-EXCERIA      | 2        | 2      | 2.08%   |
| HYDRA               | 2        | 2      | 2.08%   |
| Toshiba             | 1        | 1      | 1.04%   |
| SPCC                | 1        | 1      | 1.04%   |
| Smartbuy            | 1        | 1      | 1.04%   |
| Seagate             | 1        | 1      | 1.04%   |
| Netac               | 1        | 1      | 1.04%   |
| HS-SSD-E100         | 1        | 1      | 1.04%   |
| GOODRAM             | 1        | 1      | 1.04%   |
| Dahua               | 1        | 1      | 1.04%   |
| AMD                 | 1        | 1      | 1.04%   |
| Unknown             | 1        | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 108      | 157    | 43.2%   |
| SSD     | 91       | 107    | 36.4%   |
| NVMe    | 49       | 56     | 19.6%   |
| MMC     | 1        | 1      | 0.4%    |
| Unknown | 1        | 1      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 164      | 261    | 75.23%  |
| NVMe | 49       | 56     | 22.48%  |
| SAS  | 4        | 4      | 1.83%   |
| MMC  | 1        | 1      | 0.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 117      | 147    | 58.79%  |
| 0.51-1.0   | 69       | 100    | 34.67%  |
| 1.01-2.0   | 8        | 11     | 4.02%   |
| 3.01-4.0   | 3        | 3      | 1.51%   |
| 2.01-3.0   | 1        | 1      | 0.5%    |
| 4.01-10.0  | 1        | 2      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 67       | 34.01%  |
| 251-500        | 48       | 24.37%  |
| 501-1000       | 45       | 22.84%  |
| 1001-2000      | 19       | 9.64%   |
| 51-100         | 7        | 3.55%   |
| 2001-3000      | 5        | 2.54%   |
| More than 3000 | 3        | 1.52%   |
| 21-50          | 2        | 1.02%   |
| Unknown        | 1        | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 90       | 44.12%  |
| 21-50          | 49       | 24.02%  |
| 51-100         | 19       | 9.31%   |
| 101-250        | 18       | 8.82%   |
| 501-1000       | 11       | 5.39%   |
| 251-500        | 10       | 4.9%    |
| 1001-2000      | 3        | 1.47%   |
| More than 3000 | 2        | 0.98%   |
| 2001-3000      | 1        | 0.49%   |
| Unknown        | 1        | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 7        | 8      | 20.59%  |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 2      | 5.88%   |
| Seagate ST3500413AS 500GB         | 2        | 2      | 5.88%   |
| Seagate ST3160811AS 160GB         | 2        | 2      | 5.88%   |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 6      | 5.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 2.94%   |
| WDC WD7500BPVT-00HXZT3 752GB      | 1        | 1      | 2.94%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 2      | 2.94%   |
| WDC WD5000AAKS-00D2B0 500GB       | 1        | 1      | 2.94%   |
| WDC WD3200AAKX-001CA0 320GB       | 1        | 1      | 2.94%   |
| WDC WD10EZEX-75ZF5A0 1TB          | 1        | 2      | 2.94%   |
| WDC WD10EZEX-00WN4A0 1TB          | 1        | 1      | 2.94%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 1      | 2.94%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.94%   |
| SPCC M.2 PCIe SSD 512GB           | 1        | 1      | 2.94%   |
| Seagate ST9500423AS 500GB         | 1        | 1      | 2.94%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 2.94%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 2.94%   |
| Seagate ST31000524NS 1TB          | 1        | 1      | 2.94%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 2.94%   |
| Samsung Electronics HD400LJ 400GB | 1        | 1      | 2.94%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 2.94%   |
| Hitachi HTS543216L9A300 160GB     | 1        | 1      | 2.94%   |
| Hitachi HDS5C1050CLA382 500GB     | 1        | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 24     | 52.94%  |
| WDC                 | 11       | 13     | 32.35%  |
| Samsung Electronics | 2        | 2      | 5.88%   |
| Hitachi             | 2        | 2      | 5.88%   |
| SPCC                | 1        | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 24     | 56.25%  |
| WDC                 | 10       | 12     | 31.25%  |
| Samsung Electronics | 2        | 2      | 6.25%   |
| Hitachi             | 2        | 2      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 40     | 93.33%  |
| NVMe | 1        | 1      | 3.33%   |
| SSD  | 1        | 1      | 3.33%   |

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
| Works    | 170      | 269    | 81.73%  |
| Malfunc  | 30       | 42     | 14.42%  |
| Detected | 8        | 11     | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 154      | 62.35%  |
| AMD                          | 34       | 13.77%  |
| Samsung Electronics          | 9        | 3.64%   |
| Realtek Semiconductor        | 9        | 3.64%   |
| Phison Electronics           | 8        | 3.24%   |
| Silicon Motion               | 6        | 2.43%   |
| Kingston Technology Company  | 5        | 2.02%   |
| SanDisk                      | 4        | 1.62%   |
| Nvidia                       | 3        | 1.21%   |
| ADATA Technology             | 3        | 1.21%   |
| Shenzhen Longsys Electronics | 2        | 0.81%   |
| JMicron Technology           | 2        | 0.81%   |
| ASMedia Technology           | 2        | 0.81%   |
| VIA Technologies             | 1        | 0.4%    |
| ShenZhen TIGO Semiconductor  | 1        | 0.4%    |
| Netac Technology             | 1        | 0.4%    |
| Micron/Crucial Technology    | 1        | 0.4%    |
| MAXIO Technology (Hangzhou)  | 1        | 0.4%    |
| Marvell Technology Group     | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 38       | 13.01%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20       | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 19       | 6.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 4.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 3.77%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 3.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 10       | 3.42%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 3.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 3.08%   |
| AMD FCH SATA Controller D                                                               | 9        | 3.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 2.74%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 7        | 2.4%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 7        | 2.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 2.4%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6        | 2.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.03%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.03%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.03%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                       | 2        | 0.68%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 2        | 0.68%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 2        | 0.68%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                                  | 2        | 0.68%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.68%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 162      | 65.85%  |
| NVMe | 49       | 19.92%  |
| IDE  | 29       | 11.79%  |
| RAID | 6        | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 154      | 80.63%  |
| AMD    | 37       | 19.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz             | 15       | 7.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz            | 15       | 7.85%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 11       | 5.76%   |
| Intel Core i3-10105 CPU @ 3.70GHz            | 7        | 3.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 6        | 3.14%   |
| Intel Core i7-2600 CPU @ 3.40GHz             | 4        | 2.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 4        | 2.09%   |
| Intel Core i5-10500 CPU @ 3.10GHz            | 4        | 2.09%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics   | 4        | 2.09%   |
| Intel Pentium CPU G4500 @ 3.50GHz            | 3        | 1.57%   |
| Intel Pentium 4 CPU 3.06GHz                  | 3        | 1.57%   |
| Intel Core i7-10700K CPU @ 3.80GHz           | 3        | 1.57%   |
| Intel Core i5-9400F CPU @ 2.90GHz            | 3        | 1.57%   |
| Intel 12th Gen Core i5-12400                 | 3        | 1.57%   |
| Intel 12th Gen Core i3-12100                 | 3        | 1.57%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz       | 3        | 1.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics       | 3        | 1.57%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics  | 3        | 1.57%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 2        | 1.05%   |
| Intel Pentium CPU G630 @ 2.70GHz             | 2        | 1.05%   |
| Intel Core i7-7700 CPU @ 3.60GHz             | 2        | 1.05%   |
| Intel Core i7-4770 CPU @ 3.40GHz             | 2        | 1.05%   |
| Intel Core i5-4590 CPU @ 3.30GHz             | 2        | 1.05%   |
| Intel Core i3-6100 CPU @ 3.70GHz             | 2        | 1.05%   |
| Intel Core i3-4160 CPU @ 3.60GHz             | 2        | 1.05%   |
| Intel Celeron J4125 CPU @ 2.00GHz            | 2        | 1.05%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics   | 2        | 1.05%   |
| AMD Ryzen 5 5600G with Radeon Graphics       | 2        | 1.05%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics  | 2        | 1.05%   |
| AMD FX-4100 Quad-Core Processor              | 2        | 1.05%   |
| AMD Athlon 3000G with Radeon Vega Graphics   | 2        | 1.05%   |
| AMD A6-9500 RADEON R5, 8 COMPUTE CORES 2C+6G | 2        | 1.05%   |
| Intel Xeon CPU W3670 @ 3.20GHz               | 1        | 0.52%   |
| Intel Pentium Gold G7400                     | 1        | 0.52%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz       | 1        | 0.52%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz       | 1        | 0.52%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz       | 1        | 0.52%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz  | 1        | 0.52%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz       | 1        | 0.52%   |
| Intel Pentium CPU G4560 @ 3.50GHz            | 1        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 58       | 30.37%  |
| Intel Core i3           | 30       | 15.71%  |
| Other                   | 16       | 8.38%   |
| Intel Core i7           | 15       | 7.85%   |
| Intel Pentium           | 10       | 5.24%   |
| AMD Ryzen 5             | 10       | 5.24%   |
| Intel Celeron           | 8        | 4.19%   |
| Intel Pentium Gold      | 6        | 3.14%   |
| AMD Ryzen 7             | 5        | 2.62%   |
| AMD Ryzen 3             | 5        | 2.62%   |
| Intel Core 2 Duo        | 4        | 2.09%   |
| AMD Ryzen 5 PRO         | 4        | 2.09%   |
| Intel Pentium 4         | 3        | 1.57%   |
| AMD FX                  | 3        | 1.57%   |
| AMD Ryzen 7 PRO         | 2        | 1.05%   |
| AMD Athlon II X2        | 2        | 1.05%   |
| AMD Athlon              | 2        | 1.05%   |
| AMD A6                  | 2        | 1.05%   |
| Intel Xeon              | 1        | 0.52%   |
| Intel Pentium Dual-Core | 1        | 0.52%   |
| Intel Pentium Dual      | 1        | 0.52%   |
| Intel Core 2            | 1        | 0.52%   |
| AMD Ryzen 9             | 1        | 0.52%   |
| AMD Phenom              | 1        | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 73       | 38.22%  |
| 6      | 54       | 28.27%  |
| 2      | 40       | 20.94%  |
| 8      | 15       | 7.85%   |
| 1      | 6        | 3.14%   |
| 12     | 2        | 1.05%   |
| 3      | 1        | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 191      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 117      | 61.26%  |
| 1      | 74       | 38.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 190      | 99.48%  |
| Unknown        | 1        | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 41       | 21.35%  |
| 0x906ea    | 15       | 7.81%   |
| 0x306a9    | 12       | 6.25%   |
| 0x906ed    | 10       | 5.21%   |
| 0x306c3    | 10       | 5.21%   |
| 0x206a7    | 10       | 5.21%   |
| 0x90675    | 8        | 4.17%   |
| 0x506e3    | 8        | 4.17%   |
| 0xa0671    | 6        | 3.13%   |
| 0x08600106 | 6        | 3.13%   |
| 0x906e9    | 5        | 2.6%    |
| 0x08108109 | 5        | 2.6%    |
| 0xa0655    | 4        | 2.08%   |
| 0x1067a    | 4        | 2.08%   |
| 0x0a50000c | 4        | 2.08%   |
| 0xf49      | 3        | 1.56%   |
| 0x0810100b | 3        | 1.56%   |
| Unknown    | 3        | 1.56%   |
| 0x906eb    | 2        | 1.04%   |
| 0x90672    | 2        | 1.04%   |
| 0x706a8    | 2        | 1.04%   |
| 0x6fd      | 2        | 1.04%   |
| 0x0a50000d | 2        | 1.04%   |
| 0x08701021 | 2        | 1.04%   |
| 0x08101016 | 2        | 1.04%   |
| 0x06006118 | 2        | 1.04%   |
| 0x0600063e | 2        | 1.04%   |
| 0xb06f5    | 1        | 0.52%   |
| 0xa0654    | 1        | 0.52%   |
| 0xa0652    | 1        | 0.52%   |
| 0x6f6      | 1        | 0.52%   |
| 0x206c2    | 1        | 0.52%   |
| 0x20652    | 1        | 0.52%   |
| 0x106e5    | 1        | 0.52%   |
| 0x106a5    | 1        | 0.52%   |
| 0x10661    | 1        | 0.52%   |
| 0x0a201205 | 1        | 0.52%   |
| 0x0a201016 | 1        | 0.52%   |
| 0x0a201009 | 1        | 0.52%   |
| 0x08001138 | 1        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| CometLake        | 47       | 24.61%  |
| KabyLake         | 32       | 16.75%  |
| IvyBridge        | 12       | 6.28%   |
| SandyBridge      | 10       | 5.24%   |
| Haswell          | 10       | 5.24%   |
| Alderlake Hybrid | 10       | 5.24%   |
| Zen 3            | 9        | 4.71%   |
| Skylake          | 9        | 4.71%   |
| Zen 2            | 8        | 4.19%   |
| Zen+             | 6        | 3.14%   |
| Zen              | 6        | 3.14%   |
| Penryn           | 4        | 2.09%   |
| Core             | 4        | 2.09%   |
| Unknown          | 4        | 2.09%   |
| NetBurst         | 3        | 1.57%   |
| K10              | 3        | 1.57%   |
| Icelake          | 3        | 1.57%   |
| Westmere         | 2        | 1.05%   |
| Nehalem          | 2        | 1.05%   |
| Goldmont plus    | 2        | 1.05%   |
| Excavator        | 2        | 1.05%   |
| Bulldozer        | 2        | 1.05%   |
| Piledriver       | 1        | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 127      | 64.14%  |
| Nvidia           | 35       | 17.68%  |
| AMD              | 34       | 17.17%  |
| ATI Technologies | 2        | 1.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 38       | 19.1%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 19       | 9.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 4.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.02%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 7        | 3.52%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 3.02%   |
| Intel HD Graphics 530                                                       | 6        | 3.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.02%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 6        | 3.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 3.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 2.51%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.01%   |
| Intel HD Graphics 630                                                       | 4        | 2.01%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 2.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.01%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 1.51%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 3        | 1.51%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 1.51%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.51%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.01%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.01%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.01%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                            | 2        | 1.01%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.01%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1        | 0.5%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.5%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.5%    |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.5%    |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.5%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.5%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.5%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.5%    |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.5%    |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.5%    |
| Nvidia GF110 [GeForce GTX 570 Rev. 2]                                       | 1        | 0.5%    |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 121      | 63.35%  |
| 1 x AMD        | 34       | 17.8%   |
| 1 x Nvidia     | 32       | 16.75%  |
| Intel + Nvidia | 2        | 1.05%   |
| 2 x AMD        | 1        | 0.52%   |
| AMD + Nvidia   | 1        | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 152      | 79.17%  |
| Unknown     | 29       | 15.1%   |
| Proprietary | 11       | 5.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 134      | 70.16%  |
| 0.01-0.5   | 19       | 9.95%   |
| 1.01-2.0   | 16       | 8.38%   |
| 0.51-1.0   | 16       | 8.38%   |
| 3.01-4.0   | 3        | 1.57%   |
| 7.01-8.0   | 2        | 1.05%   |
| 2.01-3.0   | 1        | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 28       | 16.28%  |
| Philips              | 27       | 15.7%   |
| Acer                 | 19       | 11.05%  |
| ViewSonic            | 13       | 7.56%   |
| BenQ                 | 11       | 6.4%    |
| AOC                  | 11       | 6.4%    |
| Dell                 | 10       | 5.81%   |
| Goldstar             | 9        | 5.23%   |
| SGT                  | 7        | 4.07%   |
| Hewlett-Packard      | 6        | 3.49%   |
| Lenovo               | 3        | 1.74%   |
| CHD                  | 3        | 1.74%   |
| ASUSTek Computer     | 3        | 1.74%   |
| RTK                  | 2        | 1.16%   |
| OOO                  | 2        | 1.16%   |
| NEC Computers        | 2        | 1.16%   |
| CHR                  | 2        | 1.16%   |
| VIE                  | 1        | 0.58%   |
| Sony                 | 1        | 0.58%   |
| SKM                  | 1        | 0.58%   |
| Mi                   | 1        | 0.58%   |
| JRY                  | 1        | 0.58%   |
| ITE                  | 1        | 0.58%   |
| HUAWEI               | 1        | 0.58%   |
| Fujitsu Siemens      | 1        | 0.58%   |
| DOY                  | 1        | 0.58%   |
| Daewoo               | 1        | 0.58%   |
| BOE                  | 1        | 0.58%   |
| AVX                  | 1        | 0.58%   |
| Ancor Communications | 1        | 0.58%   |
| Unknown              | 1        | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 12       | 6.63%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 7        | 3.87%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch  | 6        | 3.31%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 5        | 2.76%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 2.76%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 4        | 2.21%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                   | 3        | 1.66%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2        | 1.1%    |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 2        | 1.1%    |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 2        | 1.1%    |
| Samsung Electronics S24B300 SAM08B3 1920x1080 520x290mm 23.4-inch     | 2        | 1.1%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 1.1%    |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 1.1%    |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                        | 2        | 1.1%    |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 1.1%    |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 2        | 1.1%    |
| CHD DM-MONB2401 CHD2380 1920x1080 527x296mm 23.8-inch                 | 2        | 1.1%    |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 2        | 1.1%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 1.1%    |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 2        | 1.1%    |
| Acer V233H ACR0090 1920x1080 510x287mm 23.0-inch                      | 2        | 1.1%    |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 2        | 1.1%    |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 0.55%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1        | 0.55%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1        | 0.55%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 1        | 0.55%   |
| VIE IM27VL1 VIE1919 1920x1080 600x330mm 27.0-inch                     | 1        | 0.55%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                    | 1        | 0.55%   |
| SKM T24 Air SKM9322 1920x1080 519x324mm 24.1-inch                     | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM02A0 1280x1024 376x301mm 19.0-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1        | 0.55%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.55%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1        | 0.55%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1        | 0.55%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1        | 0.55%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 0.55%   |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 1        | 0.55%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1        | 0.55%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 105      | 65.22%  |
| 1280x1024 (SXGA)  | 22       | 13.66%  |
| 2560x1440 (QHD)   | 11       | 6.83%   |
| 1600x900 (HD+)    | 9        | 5.59%   |
| 1920x1200 (WUXGA) | 4        | 2.48%   |
| 1366x768 (WXGA)   | 3        | 1.86%   |
| 3840x2160 (4K)    | 2        | 1.24%   |
| 3440x1440         | 1        | 0.62%   |
| 1600x1200         | 1        | 0.62%   |
| 1440x900 (WXGA+)  | 1        | 0.62%   |
| 1280x960          | 1        | 0.62%   |
| 1024x768 (XGA)    | 1        | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 43       | 24.86%  |
| 24     | 39       | 22.54%  |
| 21     | 26       | 15.03%  |
| 27     | 19       | 10.98%  |
| 19     | 13       | 7.51%   |
| 20     | 10       | 5.78%   |
| 17     | 10       | 5.78%   |
| 31     | 4        | 2.31%   |
| 18     | 3        | 1.73%   |
| 25     | 2        | 1.16%   |
| 15     | 2        | 1.16%   |
| 34     | 1        | 0.58%   |
| 32     | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 94       | 57.67%  |
| 401-500     | 38       | 23.31%  |
| 351-400     | 13       | 7.98%   |
| 301-350     | 12       | 7.36%   |
| 601-700     | 4        | 2.45%   |
| 701-800     | 2        | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 126      | 78.75%  |
| 5/4   | 23       | 14.38%  |
| 16/10 | 8        | 5%      |
| 4/3   | 2        | 1.25%   |
| 21/9  | 1        | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 86       | 51.81%  |
| 151-200        | 33       | 19.88%  |
| 301-350        | 19       | 11.45%  |
| 141-150        | 12       | 7.23%   |
| 251-300        | 8        | 4.82%   |
| 351-500        | 6        | 3.61%   |
| 101-110        | 2        | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 123      | 77.85%  |
| 101-120 | 35       | 22.15%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 141      | 71.21%  |
| 0     | 34       | 17.17%  |
| 2     | 23       | 11.62%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 140      | 62.5%   |
| Intel                    | 57       | 25.45%  |
| TP-Link                  | 3        | 1.34%   |
| Qualcomm Atheros         | 3        | 1.34%   |
| Nvidia                   | 3        | 1.34%   |
| Broadcom                 | 3        | 1.34%   |
| Samsung Electronics      | 2        | 0.89%   |
| Ralink Technology        | 2        | 0.89%   |
| Mercucys                 | 2        | 0.89%   |
| MediaTek                 | 2        | 0.89%   |
| VIA Technologies         | 1        | 0.45%   |
| Ralink                   | 1        | 0.45%   |
| Metrologic Instruments   | 1        | 0.45%   |
| Marvell Technology Group | 1        | 0.45%   |
| Huawei Technologies      | 1        | 0.45%   |
| Edimax Technology        | 1        | 0.45%   |
| ASIX Electronics         | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 124      | 49.6%   |
| Intel Ethernet Controller I225-V                                  | 8        | 3.2%    |
| Intel Ethernet Connection (14) I219-V                             | 8        | 3.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 2.8%    |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 2%      |
| Intel Ethernet Connection (17) I219-V                             | 5        | 2%      |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 1.6%    |
| Realtek 802.11ac NIC                                              | 3        | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 3        | 1.2%    |
| Intel Wireless 3165                                               | 3        | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.8%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.8%    |
| Mercucys 802.11n NIC                                              | 2        | 0.8%    |
| Intel Wireless 7265                                               | 2        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2        | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 2        | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.8%    |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.8%    |
| Intel Ethernet Connection (10) I219-V                             | 2        | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 0.8%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.4%    |
| TP-Link USB 10/100 LAN                                            | 1        | 0.4%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1        | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.4%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.4%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 43.48%  |
| Intel                 | 15       | 32.61%  |
| TP-Link               | 2        | 4.35%   |
| Ralink Technology     | 2        | 4.35%   |
| Mercucys              | 2        | 4.35%   |
| Broadcom              | 2        | 4.35%   |
| Ralink                | 1        | 2.17%   |
| MediaTek              | 1        | 2.17%   |
| Edimax Technology     | 1        | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 6        | 13.04%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 5        | 10.87%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 4        | 8.7%    |
| Realtek 802.11ac NIC                                            | 3        | 6.52%   |
| Intel Wireless 3165                                             | 3        | 6.52%   |
| Ralink MT7601U Wireless Adapter                                 | 2        | 4.35%   |
| Mercucys 802.11n NIC                                            | 2        | 4.35%   |
| Intel Wireless 7265                                             | 2        | 4.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 2        | 4.35%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 2        | 4.35%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                           | 1        | 2.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1        | 2.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 2.17%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 1        | 2.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1        | 2.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1        | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 1        | 2.17%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                       | 1        | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1        | 2.17%   |
| Intel Wireless 7260                                             | 1        | 2.17%   |
| Intel 700 Series Chipset Family Wi-Fi                           | 1        | 2.17%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 2.17%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter    | 1        | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 133      | 67.17%  |
| Intel                    | 51       | 25.76%  |
| Qualcomm Atheros         | 3        | 1.52%   |
| Nvidia                   | 3        | 1.52%   |
| VIA Technologies         | 1        | 0.51%   |
| TP-Link                  | 1        | 0.51%   |
| Samsung Electronics      | 1        | 0.51%   |
| MediaTek                 | 1        | 0.51%   |
| Marvell Technology Group | 1        | 0.51%   |
| Huawei Technologies      | 1        | 0.51%   |
| Broadcom                 | 1        | 0.51%   |
| ASIX Electronics         | 1        | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 124      | 61.39%  |
| Intel Ethernet Controller I225-V                                  | 8        | 3.96%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 3.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 3.47%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 3.47%   |
| Intel Ethernet Connection (17) I219-V                             | 5        | 2.48%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 1.98%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.99%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.99%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.99%   |
| Intel Ethernet Connection (10) I219-V                             | 2        | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 0.99%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.5%    |
| TP-Link USB 10/100 LAN                                            | 1        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.5%    |
| MediaTek M40Air_EEA                                               | 1        | 0.5%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 1        | 0.5%    |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.5%    |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 0.5%    |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.5%    |
| Huawei MAR-LX1M                                                   | 1        | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 190      | 79.83%  |
| WiFi     | 46       | 19.33%  |
| Modem    | 2        | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 182      | 94.3%   |
| WiFi     | 11       | 5.7%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 151      | 79.06%  |
| 2     | 39       | 20.42%  |
| 4     | 1        | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 189      | 98.95%  |
| Yes  | 2        | 1.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 15       | 45.45%  |
| Realtek Semiconductor   | 9        | 27.27%  |
| Cambridge Silicon Radio | 3        | 9.09%   |
| Broadcom                | 2        | 6.06%   |
| TP-Link                 | 1        | 3.03%   |
| MediaTek                | 1        | 3.03%   |
| IMC Networks            | 1        | 3.03%   |
| ASUSTek Computer        | 1        | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 9        | 27.27%  |
| Intel Bluetooth wireless interface                  | 6        | 18.18%  |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 12.12%  |
| Intel Bluetooth Device                              | 4        | 12.12%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 9.09%   |
| TP-Link UB500 Adapter                               | 1        | 3.03%   |
| MediaTek Wireless_Device                            | 1        | 3.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.03%   |
| IMC Networks Bluetooth Radio                        | 1        | 3.03%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 3.03%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 3.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 154      | 64.44%  |
| AMD                    | 41       | 17.15%  |
| Nvidia                 | 32       | 13.39%  |
| Texas Instruments      | 4        | 1.67%   |
| C-Media Electronics    | 3        | 1.26%   |
| Samson Technologies    | 1        | 0.42%   |
| Razer USA              | 1        | 0.42%   |
| Logitech               | 1        | 0.42%   |
| Generalplus Technology | 1        | 0.42%   |
| Creative Technology    | 1        | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Smart Sound Technology (SST) Audio Controller                        | 33       | 12.04%  |
| Intel 200 Series PCH HD Audio                                              | 22       | 8.03%   |
| AMD Family 17h/19h HD Audio Controller                                     | 22       | 8.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 6.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 12       | 4.38%   |
| Intel Comet Lake PCH-V cAVS                                                | 11       | 4.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 4.01%   |
| Intel Alder Lake-S HD Audio Controller                                     | 10       | 3.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 3.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 2.92%   |
| Nvidia High Definition Audio Controller                                    | 6        | 2.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 2.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 1.82%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4        | 1.46%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.73%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.73%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 0.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 0.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 0.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 0.73%   |
| Samson Technologies C01U Pro condenser microphone                          | 1        | 0.36%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.36%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.36%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.36%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Crucial                            | 37       | 18.41%  |
| Kingston                           | 24       | 11.94%  |
| Unknown                            | 23       | 11.44%  |
| Foxline                            | 16       | 7.96%   |
| Samsung Electronics                | 13       | 6.47%   |
| Apacer                             | 11       | 5.47%   |
| SK hynix                           | 10       | 4.98%   |
| Patriot                            | 10       | 4.98%   |
| AMD                                | 9        | 4.48%   |
| A-DATA Technology                  | 8        | 3.98%   |
| Unknown                            | 4        | 1.99%   |
| Elpida                             | 3        | 1.49%   |
| Corsair                            | 3        | 1.49%   |
| Unknown (ABCD)                     | 2        | 1%      |
| Silicon Power                      | 2        | 1%      |
| Neo Forza                          | 2        | 1%      |
| Micron Technology                  | 2        | 1%      |
| KingTiger                          | 2        | 1%      |
| HomeNet                            | 2        | 1%      |
| G.Skill                            | 2        | 1%      |
| Unknown (8AD6)                     | 1        | 0.5%    |
| Unknown (89F7)                     | 1        | 0.5%    |
| Unknown (0x0080)                   | 1        | 0.5%    |
| Transcend                          | 1        | 0.5%    |
| Shenzhen Micro Innovation Industry | 1        | 0.5%    |
| SHARETRONIC                        | 1        | 0.5%    |
| Qumo                               | 1        | 0.5%    |
| Patriot Memory (PDP Systems)       | 1        | 0.5%    |
| KingSpec                           | 1        | 0.5%    |
| Kingmax                            | 1        | 0.5%    |
| Innodisk                           | 1        | 0.5%    |
| Good Wealth                        | 1        | 0.5%    |
| Goldkey                            | 1        | 0.5%    |
| Golden Empire                      | 1        | 0.5%    |
| Gold Key                           | 1        | 0.5%    |
| ChangXin Memory                    | 1        | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s              | 6        | 2.9%    |
| Foxline RAM FL2666D4S19-8G ]. 8GB SODIMM DDR4 2667MT/s         | 5        | 2.42%   |
| Unknown                                                        | 4        | 1.93%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s            | 3        | 1.45%   |
| Patriot RAM PSD44G266681 4GB DIMM DDR4 2667MT/s                | 3        | 1.45%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s         | 3        | 1.45%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                    | 3        | 1.45%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 2        | 0.97%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                      | 2        | 0.97%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 0.97%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 2        | 0.97%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2        | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 0.97%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.97%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                       | 2        | 0.97%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                | 2        | 0.97%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s                | 2        | 0.97%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s          | 2        | 0.97%   |
| KingTiger RAM Module 2GB DIMM DDR3 1333MT/s                    | 2        | 0.97%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 2        | 0.97%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s          | 2        | 0.97%   |
| HomeNet RAM HN SO 8GB 8192MB SODIMM DDR4 3200MT/s              | 2        | 0.97%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 2        | 0.97%   |
| Foxline RAM FL2666D4S19S-16G 16GB SODIMM DDR4 2667MT/s         | 2        | 0.97%   |
| Crucial RAM ST51264BA1339.16FK 4GB DIMM DDR3 1333MT/s          | 2        | 0.97%   |
| Crucial RAM CT8G4SFRA32A.C16FG 8GB SODIMM DDR4 3200MT/s        | 2        | 0.97%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s           | 2        | 0.97%   |
| Crucial RAM CT8G4DFS824A.C8FHD1 8GB DIMM DDR4 3200MT/s         | 2        | 0.97%   |
| Crucial RAM CT8G4DFRA32A.M8FR 8192MB DIMM DDR4 3533MT/s        | 2        | 0.97%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2667MT/s           | 2        | 0.97%   |
| Crucial RAM CT8G4DFD8213.C16FHP 8GB DIMM DDR4 2133MT/s         | 2        | 0.97%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s         | 2        | 0.97%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 0.97%   |
| Apacer RAM D12.2324CH.002 8GB DIMM DDR4 3200MT/s               | 2        | 0.97%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                     | 2        | 0.97%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 0.97%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.48%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 1        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 130      | 69.52%  |
| DDR3    | 32       | 17.11%  |
| SDRAM   | 7        | 3.74%   |
| DDR2    | 7        | 3.74%   |
| Unknown | 6        | 3.21%   |
| LPDDR4  | 3        | 1.6%    |
| DDR5    | 1        | 0.53%   |
| DDR     | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 161      | 86.1%   |
| SODIMM | 26       | 13.9%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 102      | 51.26%  |
| 4096  | 39       | 19.6%   |
| 16384 | 23       | 11.56%  |
| 2048  | 20       | 10.05%  |
| 1024  | 8        | 4.02%   |
| 32768 | 6        | 3.02%   |
| 512   | 1        | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 50       | 25.51%  |
| 3200    | 35       | 17.86%  |
| 1333    | 20       | 10.2%   |
| 2400    | 13       | 6.63%   |
| 1600    | 11       | 5.61%   |
| 2133    | 8        | 4.08%   |
| 2666    | 7        | 3.57%   |
| 3600    | 5        | 2.55%   |
| 800     | 5        | 2.55%   |
| 2933    | 4        | 2.04%   |
| 2800    | 3        | 1.53%   |
| 1800    | 3        | 1.53%   |
| 533     | 3        | 1.53%   |
| Unknown | 3        | 1.53%   |
| 3866    | 2        | 1.02%   |
| 3533    | 2        | 1.02%   |
| 2934    | 2        | 1.02%   |
| 1866    | 2        | 1.02%   |
| 1066    | 2        | 1.02%   |
| 667     | 2        | 1.02%   |
| 333     | 2        | 1.02%   |
| 5200    | 1        | 0.51%   |
| 3800    | 1        | 0.51%   |
| 3733    | 1        | 0.51%   |
| 3466    | 1        | 0.51%   |
| 3266    | 1        | 0.51%   |
| 3000    | 1        | 0.51%   |
| 2866    | 1        | 0.51%   |
| 2733    | 1        | 0.51%   |
| 2187    | 1        | 0.51%   |
| 2134    | 1        | 0.51%   |
| 1648    | 1        | 0.51%   |
| 400     | 1        | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 5        | 55.56%  |
| Canon           | 2        | 22.22%  |
| Pantum          | 1        | 11.11%  |
| Kyocera         | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Pantum BM5100ADN series   | 1        | 11.11%  |
| Kyocera FS-1040           | 1        | 11.11%  |
| HP LaserJet Pro M428-M429 | 1        | 11.11%  |
| HP LaserJet P2055 series  | 1        | 11.11%  |
| HP LaserJet P2035         | 1        | 11.11%  |
| HP LaserJet M109-M112     | 1        | 11.11%  |
| HP LaserJet 1010          | 1        | 11.11%  |
| Canon MF440 Series        | 1        | 11.11%  |
| Canon MF410 Series        | 1        | 11.11%  |

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
| SunplusIT                     | 11       | 29.73%  |
| Realtek Semiconductor         | 5        | 13.51%  |
| Alcor Micro                   | 5        | 13.51%  |
| Microdia                      | 4        | 10.81%  |
| Logitech                      | 3        | 8.11%   |
| Chicony Electronics           | 2        | 5.41%   |
| Sunplus Innovation Technology | 1        | 2.7%    |
| lihappe8                      | 1        | 2.7%    |
| KYE Systems (Mouse Systems)   | 1        | 2.7%    |
| Creative Technology           | 1        | 2.7%    |
| Arkmicro Technologies         | 1        | 2.7%    |
| Apple                         | 1        | 2.7%    |
| AlcorMicroCorp                | 1        | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| SunplusIT USB Camera                      | 10       | 27.03%  |
| Microdia Camera                           | 4        | 10.81%  |
| Alcor Micro USB 2.0 PC Camera             | 4        | 10.81%  |
| Realtek USB Camera                        | 3        | 8.11%   |
| Logitech HD Webcam C615                   | 3        | 8.11%   |
| Realtek 1080p Camera                      | 2        | 5.41%   |
| SunplusIT MTD camera                      | 1        | 2.7%    |
| Sunplus USB Microphone                    | 1        | 2.7%    |
| lihappe8 USB 2.0 Camera                   | 1        | 2.7%    |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 2.7%    |
| Creative VF0530 Live! Cam Chat IM         | 1        | 2.7%    |
| Chicony HP High Definition 1MP Webcam     | 1        | 2.7%    |
| Chicony HP 0.3MP Webcam                   | 1        | 2.7%    |
| Arkmicro USB2.0 PC CAMERA                 | 1        | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE                 | 1        | 2.7%    |
| AlcorMicroCorp SHUNCCM                    | 1        | 2.7%    |
| Alcor Micro USB FHD Camera                | 1        | 2.7%    |

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
| Aladdin R.D. | 2        | 50%     |
| Aktiv        | 2        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Aktiv Rutoken lite                    | 2        | 50%     |
| Aladdin R.D. Smart card reader JCR721 | 1        | 25%     |
| Aladdin R.D. JaCarta                  | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 158      | 81.87%  |
| 1     | 32       | 16.58%  |
| 4     | 1        | 0.52%   |
| 3     | 1        | 0.52%   |
| 2     | 1        | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 28       | 68.29%  |
| Net/wireless             | 6        | 14.63%  |
| Communication controller | 3        | 7.32%   |
| Sound                    | 1        | 2.44%   |
| Network                  | 1        | 2.44%   |
| Net/ethernet             | 1        | 2.44%   |
| Chipcard                 | 1        | 2.44%   |

