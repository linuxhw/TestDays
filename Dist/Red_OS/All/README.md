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

Total: 287

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Red OS 7.3.1 | 95        | 46.34%  |
| Red OS 7.3   | 65        | 31.71%  |
| Red OS 7.3.2 | 37        | 18.05%  |
| Red OS 7.2   | 8         | 3.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Red OS | 192       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 50        | 23.36%  |
| 5.10.29-1.el7.x86_64   | 30        | 14.02%  |
| 5.15.72-1.el7.3.x86_64 | 25        | 11.68%  |
| 5.15.35-5.el7.3.x86_64 | 23        | 10.75%  |
| 5.15.35-4.el7.3.x86_64 | 19        | 8.88%   |
| 5.15.35-1.el7.3.x86_64 | 16        | 7.48%   |
| 5.15.78-2.el7.3.x86_64 | 13        | 6.07%   |
| 4.19.79-1.el7.x86_64   | 6         | 2.8%    |
| 5.15.10-2.el7.x86_64   | 5         | 2.34%   |
| 5.10.29-3.el7.x86_64   | 5         | 2.34%   |
| 5.15.10-3.el7.x86_64   | 4         | 1.87%   |
| 5.10.1-1.el7.x86_64    | 4         | 1.87%   |
| 5.10.24-2.el7.x86_64   | 3         | 1.4%    |
| 5.18.1-1.el7.x86_64    | 2         | 0.93%   |
| 5.15.10-4.el7.x86_64   | 2         | 0.93%   |
| 5.4.197-1.el7.aarch64  | 1         | 0.47%   |
| 5.14.9-1.el7.x86_64    | 1         | 0.47%   |
| 5.13.15-1.el7.x86_64   | 1         | 0.47%   |
| 5.10.24-3.el7.x86_64   | 1         | 0.47%   |
| 5.10.24-1.el7.x86_64   | 1         | 0.47%   |
| 4.19.56-2.el7.x86_64   | 1         | 0.47%   |
| 4.19.204-1.el7.x86_64  | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.10  | 61        | 29.05%  |
| 5.15.35  | 54        | 25.71%  |
| 5.10.29  | 35        | 16.67%  |
| 5.15.72  | 25        | 11.9%   |
| 5.15.78  | 13        | 6.19%   |
| 4.19.79  | 6         | 2.86%   |
| 5.10.24  | 5         | 2.38%   |
| 5.10.1   | 4         | 1.9%    |
| 5.18.1   | 2         | 0.95%   |
| 5.4.197  | 1         | 0.48%   |
| 5.14.9   | 1         | 0.48%   |
| 5.13.15  | 1         | 0.48%   |
| 4.19.56  | 1         | 0.48%   |
| 4.19.204 | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 145       | 72.14%  |
| 5.10    | 43        | 21.39%  |
| 4.19    | 8         | 3.98%   |
| 5.18    | 2         | 1%      |
| 5.4     | 1         | 0.5%    |
| 5.14    | 1         | 0.5%    |
| 5.13    | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 191       | 99.48%  |
| aarch64 | 1         | 0.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 160       | 80.4%   |
| Cinnamon   | 35        | 17.59%  |
| X-Cinnamon | 2         | 1.01%   |
| Unknown    | 2         | 1.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 184       | 93.88%  |
| Wayland | 11        | 5.61%   |
| Unknown | 1         | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 185       | 95.36%  |
| SDDM    | 5         | 2.58%   |
| Unknown | 4         | 2.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 186       | 96.37%  |
| ru_RU   | 6         | 3.11%   |
| en_US   | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 150       | 76.53%  |
| BIOS | 46        | 23.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 189       | 97.42%  |
| Btrfs   | 4         | 2.06%   |
| Unknown | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 151       | 77.84%  |
| MBR     | 40        | 20.62%  |
| Unknown | 3         | 1.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 88.66%  |
| Yes       | 22        | 11.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 73.71%  |
| Yes       | 51        | 26.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 42        | 21.88%  |
| Gigabyte Technology            | 31        | 16.15%  |
| ASUSTek Computer               | 27        | 14.06%  |
| Hewlett-Packard                | 16        | 8.33%   |
| ASRock                         | 12        | 6.25%   |
| MSI                            | 9         | 4.69%   |
| Aquarius                       | 9         | 4.69%   |
| DEPO Computers                 | 6         | 3.13%   |
| ICL                            | 5         | 2.6%    |
| HUAWEI                         | 4         | 2.08%   |
| Digma                          | 4         | 2.08%   |
| Acer                           | 3         | 1.56%   |
| Unknown                        | 3         | 1.56%   |
| Kraftway                       | 2         | 1.04%   |
| IP3 Technology                 | 2         | 1.04%   |
| Graviton                       | 2         | 1.04%   |
| 3Logic Group                   | 2         | 1.04%   |
| YADRO                          | 1         | 0.52%   |
| THUNDEROBOT                    | 1         | 0.52%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.52%   |
| RDW                            | 1         | 0.52%   |
| Pegatron                       | 1         | 0.52%   |
| NCI                            | 1         | 0.52%   |
| mtech                          | 1         | 0.52%   |
| iRU                            | 1         | 0.52%   |
| Intel                          | 1         | 0.52%   |
| HONOR                          | 1         | 0.52%   |
| ECS                            | 1         | 0.52%   |
| Dell                           | 1         | 0.52%   |
| Colorful Technology            | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                      | 17        | 8.85%   |
| Gigabyte B365M DS3H                      | 4         | 2.08%   |
| DEPO Computers DPH310T                   | 4         | 2.08%   |
| Unknown                                  | 4         | 2.08%   |
| ICL RAYbook Si1512                       | 3         | 1.56%   |
| HP Laptop 15s-eq1xxx                     | 3         | 1.56%   |
| Gigabyte H110M-S2                        | 3         | 1.56%   |
| MSI MS-7D14                              | 2         | 1.04%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 2         | 1.04%   |
| Kraftway ACCORD                          | 2         | 1.04%   |
| IP3 ACN30                                | 2         | 1.04%   |
| Gigabyte B560M DS3H                      | 2         | 1.04%   |
| Gigabyte B550 AORUS ELITE V2             | 2         | 1.04%   |
| DEPO Computers DPH410S                   | 2         | 1.04%   |
| ASUS PRIME H510T2/CSM                    | 2         | 1.04%   |
| ASUS PC                                  | 2         | 1.04%   |
| ASUS MINIPC PB62                         | 2         | 1.04%   |
| ASUS All Series                          | 2         | 1.04%   |
| ASRock H510M-HVS R2.0                    | 2         | 1.04%   |
| Aquarius P30 K44 R53                     | 2         | 1.04%   |
| YADRO VEGMAN S220 Server                 | 1         | 0.52%   |
| THUNDEROBOT 911AirD                      | 1         | 0.52%   |
| Shanghai Zhaoxin ZXE CRB                 | 1         | 0.52%   |
| RDW RDW-MB-B450M V.1                     | 1         | 0.52%   |
| Pegatron A35                             | 1         | 0.52%   |
| NCI PC BLICK101                          | 1         | 0.52%   |
| mtech MTL1578                            | 1         | 0.52%   |
| MSI Sword 15 A12UE                       | 1         | 0.52%   |
| MSI MS-7D48                              | 1         | 0.52%   |
| MSI MS-7D35                              | 1         | 0.52%   |
| MSI MS-7B86                              | 1         | 0.52%   |
| MSI MS-7636                              | 1         | 0.52%   |
| MSI FX610                                | 1         | 0.52%   |
| MSI Compaq dx2300 Microtower             | 1         | 0.52%   |
| Lenovo V50s-07IMB 11EF0011RU             | 1         | 0.52%   |
| Lenovo V130-15IKB 81HN                   | 1         | 0.52%   |
| Lenovo ThinkPad X220 4290RB3             | 1         | 0.52%   |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP     | 1         | 0.52%   |
| Lenovo ThinkCentre M75q Gen 2 11JNS02N00 | 1         | 0.52%   |
| Lenovo ThinkCentre M720q 10T8S08X00      | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo V15-IWL         | 17        | 8.85%   |
| Lenovo ThinkCentre     | 8         | 4.17%   |
| ASUS PRIME             | 7         | 3.65%   |
| Lenovo IdeaPad         | 6         | 3.13%   |
| Gigabyte B365M         | 5         | 2.6%    |
| ICL RAYbook            | 4         | 2.08%   |
| HP Laptop              | 4         | 2.08%   |
| DEPO Computers DPH310T | 4         | 2.08%   |
| Unknown                | 4         | 2.08%   |
| Lenovo ThinkBook       | 3         | 1.56%   |
| Lenovo IdeaCentre      | 3         | 1.56%   |
| Gigabyte H110M-S2      | 3         | 1.56%   |
| Gigabyte B560M         | 3         | 1.56%   |
| Digma EVE              | 3         | 1.56%   |
| MSI MS-7D14            | 2         | 1.04%   |
| Lenovo ThinkPad        | 2         | 1.04%   |
| Kraftway ACCORD        | 2         | 1.04%   |
| IP3 ACN30              | 2         | 1.04%   |
| HP ProOne              | 2         | 1.04%   |
| HP Pavilion            | 2         | 1.04%   |
| Gigabyte H410M         | 2         | 1.04%   |
| Gigabyte B550          | 2         | 1.04%   |
| DEPO Computers DPH410S | 2         | 1.04%   |
| ASUS PC                | 2         | 1.04%   |
| ASUS MINIPC            | 2         | 1.04%   |
| ASUS All               | 2         | 1.04%   |
| ASRock H510M-HVS       | 2         | 1.04%   |
| Aquarius Pro           | 2         | 1.04%   |
| Aquarius P30           | 2         | 1.04%   |
| Aquarius NS685U        | 2         | 1.04%   |
| Acer Aspire            | 2         | 1.04%   |
| YADRO VEGMAN           | 1         | 0.52%   |
| THUNDEROBOT 911AirD    | 1         | 0.52%   |
| Shanghai Zhaoxin ZXE   | 1         | 0.52%   |
| RDW RDW-MB-B450M       | 1         | 0.52%   |
| Pegatron A35           | 1         | 0.52%   |
| NCI PC                 | 1         | 0.52%   |
| mtech MTL1578          | 1         | 0.52%   |
| MSI Sword              | 1         | 0.52%   |
| MSI MS-7D48            | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 49        | 25.52%  |
| 2019 | 42        | 21.88%  |
| 2020 | 27        | 14.06%  |
| 2022 | 20        | 10.42%  |
| 2018 | 10        | 5.21%   |
| 2016 | 8         | 4.17%   |
| 2012 | 7         | 3.65%   |
| 2010 | 6         | 3.13%   |
| 2011 | 5         | 2.6%    |
| 2013 | 4         | 2.08%   |
| 2017 | 3         | 1.56%   |
| 2014 | 3         | 1.56%   |
| 2007 | 3         | 1.56%   |
| 2015 | 2         | 1.04%   |
| 2009 | 2         | 1.04%   |
| 2008 | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 97        | 50.52%  |
| Notebook       | 71        | 36.98%  |
| All in one     | 11        | 5.73%   |
| Mini pc        | 9         | 4.69%   |
| Server         | 2         | 1.04%   |
| System on chip | 1         | 0.52%   |
| Tablet         | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 192       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 192       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 96        | 50%     |
| 16.01-24.0      | 37        | 19.27%  |
| 8.01-16.0       | 23        | 11.98%  |
| 3.01-4.0        | 22        | 11.46%  |
| 32.01-64.0      | 4         | 2.08%   |
| 1.01-2.0        | 3         | 1.56%   |
| More than 256.0 | 2         | 1.04%   |
| 24.01-32.0      | 2         | 1.04%   |
| 2.01-3.0        | 1         | 0.52%   |
| 0.51-1.0        | 1         | 0.52%   |
| Unknown         | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 102       | 50.25%  |
| 2.01-3.0    | 32        | 15.76%  |
| 0.51-1.0    | 25        | 12.32%  |
| 3.01-4.0    | 22        | 10.84%  |
| 4.01-8.0    | 14        | 6.9%    |
| 8.01-16.0   | 5         | 2.46%   |
| 64.01-256.0 | 1         | 0.49%   |
| 0.01-0.5    | 1         | 0.49%   |
| Unknown     | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 143       | 71.86%  |
| 2      | 39        | 19.6%   |
| 3      | 9         | 4.52%   |
| 4      | 3         | 1.51%   |
| 12     | 1         | 0.5%    |
| 11     | 1         | 0.5%    |
| 7      | 1         | 0.5%    |
| 5      | 1         | 0.5%    |
| 0      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 76.17%  |
| Yes       | 46        | 23.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 83.33%  |
| No        | 32        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 58.25%  |
| No        | 81        | 41.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 50.26%  |
| Yes       | 96        | 49.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 191       | 99.48%  |
| Ukraine | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Salekhard        | 37        | 19.07%  |
| Murom            | 35        | 18.04%  |
| Moscow           | 32        | 16.49%  |
| Yekaterinburg    | 6         | 3.09%   |
| Novy Urengoy     | 6         | 3.09%   |
| Perm             | 4         | 2.06%   |
| Novosibirsk      | 4         | 2.06%   |
| Krasnodar        | 4         | 2.06%   |
| Khabarovsk       | 4         | 2.06%   |
| Veliky Novgorod  | 3         | 1.55%   |
| St Petersburg    | 3         | 1.55%   |
| Shakhtersk       | 3         | 1.55%   |
| Ryazan           | 3         | 1.55%   |
| Kursk            | 3         | 1.55%   |
| Kaluga           | 3         | 1.55%   |
| Balashikha       | 3         | 1.55%   |
| Vladimir         | 2         | 1.03%   |
| Ulyanovsk        | 2         | 1.03%   |
| Penza            | 2         | 1.03%   |
| Muromskiy        | 2         | 1.03%   |
| Labytnangi       | 2         | 1.03%   |
| Kurgan           | 2         | 1.03%   |
| Krasnoyarsk      | 2         | 1.03%   |
| Baksan           | 2         | 1.03%   |
| Yaroslavl        | 1         | 0.52%   |
| Yakutsk          | 1         | 0.52%   |
| Voronezh         | 1         | 0.52%   |
| Tomsk            | 1         | 0.52%   |
| Svetlograd       | 1         | 0.52%   |
| Surgut           | 1         | 0.52%   |
| Stavropol        | 1         | 0.52%   |
| Sevastopol       | 1         | 0.52%   |
| Saratov          | 1         | 0.52%   |
| Rostov-on-Don    | 1         | 0.52%   |
| Omsk             | 1         | 0.52%   |
| Noyabrsk         | 1         | 0.52%   |
| Nizhniy Novgorod | 1         | 0.52%   |
| Nadym            | 1         | 0.52%   |
| Magadan          | 1         | 0.52%   |
| Kovrov           | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 41        | 57     | 16.21%  |
| Samsung Electronics          | 36        | 52     | 14.23%  |
| WDC                          | 34        | 40     | 13.44%  |
| Toshiba                      | 15        | 22     | 5.93%   |
| A-DATA Technology            | 15        | 15     | 5.93%   |
| Kingston                     | 13        | 14     | 5.14%   |
| Foxline                      | 8         | 8      | 3.16%   |
| Apacer                       | 8         | 8      | 3.16%   |
| SK hynix                     | 7         | 7      | 2.77%   |
| SanDisk                      | 6         | 8      | 2.37%   |
| Intel                        | 5         | 11     | 1.98%   |
| Crucial                      | 5         | 8      | 1.98%   |
| Patriot                      | 4         | 4      | 1.58%   |
| KingSpec                     | 4         | 4      | 1.58%   |
| Unknown                      | 4         | 5      | 1.58%   |
| Unknown                      | 3         | 3      | 1.19%   |
| UMIS                         | 3         | 3      | 1.19%   |
| Transcend                    | 3         | 3      | 1.19%   |
| Silicon Motion               | 3         | 3      | 1.19%   |
| Phison                       | 3         | 3      | 1.19%   |
| Micron Technology            | 3         | 5      | 1.19%   |
| Hitachi                      | 3         | 3      | 1.19%   |
| KIOXIA-EXCERIA               | 2         | 2      | 0.79%   |
| HGST                         | 2         | 2      | 0.79%   |
| ExeGate                      | 2         | 3      | 0.79%   |
| China                        | 2         | 2      | 0.79%   |
| AMD                          | 2         | 2      | 0.79%   |
| AGI                          | 2         | 2      | 0.79%   |
| XPG                          | 1         | 1      | 0.4%    |
| SPCC Sol                     | 1         | 1      | 0.4%    |
| SPCC                         | 1         | 1      | 0.4%    |
| Smartbuy                     | 1         | 1      | 0.4%    |
| Shenzhen Longsys Electronics | 1         | 1      | 0.4%    |
| Plextor                      | 1         | 1      | 0.4%    |
| Netac                        | 1         | 1      | 0.4%    |
| LIO-ORG                      | 1         | 1      | 0.4%    |
| Lenovo                       | 1         | 16     | 0.4%    |
| Kimtigo                      | 1         | 2      | 0.4%    |
| JMicron Technology           | 1         | 1      | 0.4%    |
| ITHOO                        | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 17        | 6.49%   |
| Seagate ST1000LM049-2GH172 1TB         | 6         | 2.29%   |
| Seagate ST1000DM010-2EP102 1TB         | 6         | 2.29%   |
| Seagate ST500DM002-1BD142 500GB        | 5         | 1.91%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 1.91%   |
| Foxline FLSSD256M80E13TCX5 256GB       | 5         | 1.91%   |
| Toshiba HDWD110 1TB                    | 4         | 1.53%   |
| Apacer AS2280P4 256GB                  | 4         | 1.53%   |
| Unknown                                | 4         | 1.53%   |
| Seagate ST1000DM010-2DM162 1TB         | 3         | 1.15%   |
| SanDisk SD8SBAT256G1122 256GB SSD      | 3         | 1.15%   |
| Samsung SSD 860 EVO 250GB              | 3         | 1.15%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 1.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.76%   |
| WDC WD10EZEX-22MFCA0 1TB               | 2         | 0.76%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 0.76%   |
| Toshiba HDWD105 500GB                  | 2         | 0.76%   |
| Toshiba DT01ACA100 1TB                 | 2         | 0.76%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 0.76%   |
| SK hynix PC711 HFS512GDE9X073N 512GB   | 2         | 0.76%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 2         | 0.76%   |
| Seagate ST1000DM003-1SB10C 1TB         | 2         | 0.76%   |
| Samsung MZVLQ256HAJD-000H1 256GB       | 2         | 0.76%   |
| KIOXIA-EXCERIA SATA SSD 480GB          | 2         | 0.76%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.76%   |
| Kingston OM8PCP3512F-A02 512GB         | 2         | 0.76%   |
| KingSpec NT-256 256GB SSD              | 2         | 0.76%   |
| Foxline FLSSD240X5SE 240GB             | 2         | 0.76%   |
| ExeGate EX276690RUS(960G 960GB SSD     | 2         | 0.76%   |
| Apacer AS340 240GB SSD                 | 2         | 0.76%   |
| AGI AGI512G16AI198 512GB               | 2         | 0.76%   |
| A-DATA SX6000PNP 256GB                 | 2         | 0.76%   |
| A-DATA SU800 256GB SSD                 | 2         | 0.76%   |
| A-DATA SU650 240GB SSD                 | 2         | 0.76%   |
| A-DATA SU630 960GB SSD                 | 2         | 0.76%   |
| XPG GAMMIX S70 BLADE 2TB               | 1         | 0.38%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.38%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 1         | 0.38%   |
| WDC WD5000BPVT-55HXZT3 500GB           | 1         | 0.38%   |
| WDC WD5000AZLX-60K2TA0 500GB           | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 56     | 47.62%  |
| WDC                 | 22        | 28     | 26.19%  |
| Toshiba             | 12        | 19     | 14.29%  |
| Samsung Electronics | 3         | 4      | 3.57%   |
| Hitachi             | 3         | 3      | 3.57%   |
| HGST                | 2         | 2      | 2.38%   |
| LIO-ORG             | 1         | 1      | 1.19%   |
| Lenovo              | 1         | 16     | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 10        | 10     | 13.33%  |
| Kingston            | 9         | 9      | 12%     |
| Samsung Electronics | 6         | 13     | 8%      |
| WDC                 | 5         | 5      | 6.67%   |
| SanDisk             | 5         | 7      | 6.67%   |
| KingSpec            | 4         | 4      | 5.33%   |
| Crucial             | 4         | 7      | 5.33%   |
| Apacer              | 4         | 4      | 5.33%   |
| Transcend           | 3         | 3      | 4%      |
| Patriot             | 3         | 3      | 4%      |
| Intel               | 3         | 9      | 4%      |
| Foxline             | 3         | 3      | 4%      |
| KIOXIA-EXCERIA      | 2         | 2      | 2.67%   |
| ExeGate             | 2         | 3      | 2.67%   |
| China               | 2         | 2      | 2.67%   |
| Toshiba             | 1         | 1      | 1.33%   |
| SPCC Sol            | 1         | 1      | 1.33%   |
| Smartbuy            | 1         | 1      | 1.33%   |
| Seagate             | 1         | 1      | 1.33%   |
| Plextor             | 1         | 1      | 1.33%   |
| Micron Technology   | 1         | 1      | 1.33%   |
| JMicron Technology  | 1         | 1      | 1.33%   |
| GOODRAM             | 1         | 1      | 1.33%   |
| AMD                 | 1         | 1      | 1.33%   |
| Unknown             | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 86        | 100    | 35.98%  |
| HDD     | 76        | 129    | 31.8%   |
| SSD     | 71        | 94     | 29.71%  |
| MMC     | 5         | 6      | 2.09%   |
| Unknown | 1         | 1      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 122       | 219    | 56.22%  |
| NVMe | 86        | 100    | 39.63%  |
| MMC  | 5         | 6      | 2.3%    |
| SAS  | 4         | 5      | 1.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 111    | 57.24%  |
| 0.51-1.0   | 53        | 75     | 34.87%  |
| 1.01-2.0   | 8         | 25     | 5.26%   |
| 3.01-4.0   | 2         | 6      | 1.32%   |
| 2.01-3.0   | 1         | 1      | 0.66%   |
| 4.01-10.0  | 1         | 5      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 84        | 42.64%  |
| 251-500        | 40        | 20.3%   |
| 501-1000       | 33        | 16.75%  |
| 51-100         | 14        | 7.11%   |
| 1001-2000      | 12        | 6.09%   |
| 2001-3000      | 5         | 2.54%   |
| 21-50          | 4         | 2.03%   |
| More than 3000 | 2         | 1.02%   |
| 1-20           | 2         | 1.02%   |
| Unknown        | 1         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 131       | 64.53%  |
| 21-50          | 24        | 11.82%  |
| 51-100         | 12        | 5.91%   |
| 101-250        | 11        | 5.42%   |
| 501-1000       | 11        | 5.42%   |
| 251-500        | 6         | 2.96%   |
| 1001-2000      | 4         | 1.97%   |
| More than 3000 | 2         | 0.99%   |
| 2001-3000      | 1         | 0.49%   |
| Unknown        | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3         | 3      | 11.11%  |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 7.41%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 6      | 7.41%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 1      | 3.7%    |
| WDC WD5000AAKS-00D2B0 500GB         | 1         | 1      | 3.7%    |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 3.7%    |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 3.7%    |
| WDC WD10EZEX-75ZF5A0 1TB            | 1         | 1      | 3.7%    |
| WDC WD10EZEX-00WN4A0 1TB            | 1         | 1      | 3.7%    |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 3.7%    |
| Toshiba MQ01ABF050 500GB            | 1         | 6      | 3.7%    |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 3.7%    |
| SPCC M.2 PCIe SSD 512GB             | 1         | 1      | 3.7%    |
| Seagate ST9500423AS 500GB           | 1         | 1      | 3.7%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 3.7%    |
| Seagate ST3250823AS 250GB           | 1         | 1      | 3.7%    |
| Samsung Electronics HD400LJ 400GB   | 1         | 1      | 3.7%    |
| Kingston SHPM2280P2H 240G SSD       | 1         | 1      | 3.7%    |
| Hitachi HDS5C1050CLA382 500GB       | 1         | 1      | 3.7%    |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 3.7%    |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 3.7%    |
| Unknown                             | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 33.33%  |
| Seagate             | 9         | 13     | 33.33%  |
| Toshiba             | 2         | 7      | 7.41%   |
| SPCC                | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Kingston            | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |
| Unknown             | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 13     | 42.86%  |
| WDC                 | 7         | 7      | 33.33%  |
| Toshiba             | 2         | 7      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 30     | 78.26%  |
| SSD  | 4         | 5      | 17.39%  |
| NVMe | 1         | 1      | 4.35%   |

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
| Works    | 173       | 276    | 83.17%  |
| Malfunc  | 23        | 36     | 11.06%  |
| Detected | 12        | 18     | 5.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 154       | 56.83%  |
| Samsung Electronics          | 28        | 10.33%  |
| AMD                          | 21        | 7.75%   |
| Phison Electronics           | 14        | 5.17%   |
| SanDisk                      | 8         | 2.95%   |
| SK hynix                     | 7         | 2.58%   |
| Silicon Motion               | 6         | 2.21%   |
| Realtek Semiconductor        | 5         | 1.85%   |
| Kingston Technology Company  | 5         | 1.85%   |
| Union Memory (Shenzhen)      | 3         | 1.11%   |
| Nvidia                       | 3         | 1.11%   |
| Toshiba America Info Systems | 2         | 0.74%   |
| Micron Technology            | 2         | 0.74%   |
| JMicron Technology           | 2         | 0.74%   |
| ADATA Technology             | 2         | 0.74%   |
| Unknown                      | 2         | 0.74%   |
| Zhaoxin                      | 1         | 0.37%   |
| VIA Technologies             | 1         | 0.37%   |
| Shenzhen Longsys Electronics | 1         | 0.37%   |
| Netac Technology             | 1         | 0.37%   |
| Micron/Crucial Technology    | 1         | 0.37%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.37%   |
| LSI Logic / Symbios Logic    | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 28        | 9.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 27        | 9.15%   |
| Samsung NVMe SSD Controller 980                                                  | 25        | 8.47%   |
| Phison PS5013 E13 NVMe Controller                                                | 12        | 4.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 12        | 4.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 3.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 10        | 3.39%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 3.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 6         | 2.03%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 2.03%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 6         | 2.03%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 1.69%   |
| AMD 500 Series Chipset SATA Controller                                           | 5         | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 1.69%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 4         | 1.36%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.36%   |
| Realtek Realtek Non-Volatile memory controller                                   | 4         | 1.36%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 1.36%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.36%   |
| Nvidia MCP61 SATA Controller                                                     | 3         | 1.02%   |
| Nvidia MCP61 IDE                                                                 | 3         | 1.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.02%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.68%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.68%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.68%   |
| JMicron JMB368 IDE controller                                                    | 2         | 0.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 0.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 163       | 59.49%  |
| NVMe | 86        | 31.39%  |
| IDE  | 16        | 5.84%   |
| RAID | 8         | 2.92%   |
| SAS  | 1         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 157       | 81.77%  |
| AMD          | 33        | 17.19%  |
| CentaurHauls | 1         | 0.52%   |
| ARM          | 1         | 0.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 9.38%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 11        | 5.73%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 11        | 5.73%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 3.13%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 6         | 3.13%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 4         | 2.08%   |
| Intel Pentium CPU G4500 @ 3.50GHz             | 3         | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 1.56%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 3         | 1.56%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.56%   |
| Intel 12th Gen Core i5-12400                  | 3         | 1.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.56%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 1.56%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 2         | 1.04%   |
| Intel Core i5-8400T CPU @ 1.70GHz             | 2         | 1.04%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 2         | 1.04%   |
| Intel Core i5-10400T CPU @ 2.00GHz            | 2         | 1.04%   |
| Intel Core i3-8100T CPU @ 3.10GHz             | 2         | 1.04%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 1.04%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 1.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.04%   |
| Intel 12th Gen Core i3-12100                  | 2         | 1.04%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz        | 2         | 1.04%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.04%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2         | 1.04%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.04%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 2         | 1.04%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.04%   |
| AMD FX-4100 Quad-Core Processor               | 2         | 1.04%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz          | 1         | 0.52%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz            | 1         | 0.52%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1         | 0.52%   |
| Intel Pentium Gold G7400                      | 1         | 0.52%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1         | 0.52%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.52%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 0.52%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.52%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.52%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 70        | 36.46%  |
| Intel Core i3      | 31        | 16.15%  |
| Other              | 22        | 11.46%  |
| Intel Celeron      | 10        | 5.21%   |
| AMD Ryzen 5        | 10        | 5.21%   |
| Intel Core i7      | 8         | 4.17%   |
| AMD Ryzen 3        | 8         | 4.17%   |
| Intel Pentium      | 7         | 3.65%   |
| Intel Pentium Gold | 4         | 2.08%   |
| Intel Core 2 Duo   | 3         | 1.56%   |
| AMD FX             | 3         | 1.56%   |
| AMD Ryzen 7 PRO    | 2         | 1.04%   |
| AMD Ryzen 7        | 2         | 1.04%   |
| AMD Athlon II X2   | 2         | 1.04%   |
| Intel Xeon Silver  | 1         | 0.52%   |
| Intel Xeon Gold    | 1         | 0.52%   |
| Intel Xeon         | 1         | 0.52%   |
| Intel Core 2       | 1         | 0.52%   |
| AMD Ryzen 9        | 1         | 0.52%   |
| AMD Ryzen 5 PRO    | 1         | 0.52%   |
| AMD Ryzen 3 PRO    | 1         | 0.52%   |
| AMD Phenom II      | 1         | 0.52%   |
| AMD Phenom         | 1         | 0.52%   |
| AMD Athlon         | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 92        | 47.92%  |
| 2      | 42        | 21.88%  |
| 6      | 41        | 21.35%  |
| 8      | 9         | 4.69%   |
| 12     | 2         | 1.04%   |
| 3      | 2         | 1.04%   |
| 36     | 1         | 0.52%   |
| 24     | 1         | 0.52%   |
| 14     | 1         | 0.52%   |
| 10     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 190       | 98.96%  |
| 2      | 2         | 1.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 129       | 67.19%  |
| 1      | 63        | 32.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 191       | 99.48%  |
| Unknown        | 1         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0xa0653    | 28        | 14.43%  |
| 0x806ec    | 20        | 10.31%  |
| 0x806ea    | 10        | 5.15%   |
| 0x906ed    | 9         | 4.64%   |
| 0x906ea    | 9         | 4.64%   |
| 0x506e3    | 9         | 4.64%   |
| 0x806c1    | 7         | 3.61%   |
| 0x08600106 | 7         | 3.61%   |
| 0x90675    | 6         | 3.09%   |
| 0x306c3    | 6         | 3.09%   |
| 0x906eb    | 5         | 2.58%   |
| 0x306a9    | 5         | 2.58%   |
| 0x206a7    | 5         | 2.58%   |
| 0x0a50000c | 4         | 2.06%   |
| 0x08108109 | 4         | 2.06%   |
| Unknown    | 4         | 2.06%   |
| 0xa0671    | 3         | 1.55%   |
| 0xa0655    | 3         | 1.55%   |
| 0x906e9    | 3         | 1.55%   |
| 0x0a50000d | 3         | 1.55%   |
| 0x806d1    | 2         | 1.03%   |
| 0x706a8    | 2         | 1.03%   |
| 0x506ca    | 2         | 1.03%   |
| 0x506c9    | 2         | 1.03%   |
| 0x50657    | 2         | 1.03%   |
| 0x406c4    | 2         | 1.03%   |
| 0x1067a    | 2         | 1.03%   |
| 0x08608103 | 2         | 1.03%   |
| 0x08108102 | 2         | 1.03%   |
| 0x0600063e | 2         | 1.03%   |
| 0x010000c8 | 2         | 1.03%   |
| 0xa0654    | 1         | 0.52%   |
| 0x906a4    | 1         | 0.52%   |
| 0x906a3    | 1         | 0.52%   |
| 0x90672    | 1         | 0.52%   |
| 0x806eb    | 1         | 0.52%   |
| 0x706e5    | 1         | 0.52%   |
| 0x6fa      | 1         | 0.52%   |
| 0x6f6      | 1         | 0.52%   |
| 0x406e3    | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 58        | 30.21%  |
| CometLake        | 32        | 16.67%  |
| Skylake          | 12        | 6.25%   |
| Zen 2            | 9         | 4.69%   |
| Zen 3            | 8         | 4.17%   |
| Alderlake Hybrid | 8         | 4.17%   |
| Unknown          | 8         | 4.17%   |
| TigerLake        | 7         | 3.65%   |
| Haswell          | 7         | 3.65%   |
| Zen+             | 6         | 3.13%   |
| SandyBridge      | 5         | 2.6%    |
| IvyBridge        | 5         | 2.6%    |
| K10              | 4         | 2.08%   |
| Goldmont         | 4         | 2.08%   |
| Icelake          | 3         | 1.56%   |
| Westmere         | 2         | 1.04%   |
| Silvermont       | 2         | 1.04%   |
| Penryn           | 2         | 1.04%   |
| Nehalem          | 2         | 1.04%   |
| Goldmont plus    | 2         | 1.04%   |
| Core             | 2         | 1.04%   |
| Bulldozer        | 2         | 1.04%   |
| Zen              | 1         | 0.52%   |
| Piledriver       | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 142       | 68.27%  |
| AMD               | 36        | 17.31%  |
| Nvidia            | 27        | 12.98%  |
| ASPEED Technology | 2         | 0.96%   |
| Zhaoxin           | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 27        | 12.8%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 9%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 19        | 9%      |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 10        | 4.74%   |
| AMD Renoir                                                                               | 8         | 3.79%   |
| Intel HD Graphics 530                                                                    | 6         | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.84%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 5         | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.9%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 1.42%   |
| Intel HD Graphics 500                                                                    | 3         | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.95%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 2         | 0.95%   |
| Intel HD Graphics 630                                                                    | 2         | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.95%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                                 | 2         | 0.95%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.95%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.95%   |
| AMD Lucienne                                                                             | 2         | 0.95%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.47%   |
| Nvidia TU117M [GeForce MX550]                                                            | 1         | 0.47%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.47%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.47%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.47%   |
| Nvidia NV43 [GeForce 6600 GT]                                                            | 1         | 0.47%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.47%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.47%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.47%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.47%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 127       | 66.15%  |
| 1 x AMD        | 29        | 15.1%   |
| 1 x Nvidia     | 14        | 7.29%   |
| Intel + Nvidia | 11        | 5.73%   |
| Intel + AMD    | 3         | 1.56%   |
| 2 x AMD        | 2         | 1.04%   |
| 1 x ASPEED     | 2         | 1.04%   |
| AMD + Nvidia   | 2         | 1.04%   |
| Other          | 1         | 0.52%   |
| 1 x Zhaoxin    | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 157       | 80.93%  |
| Unknown     | 31        | 15.98%  |
| Proprietary | 6         | 3.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 72.68%  |
| 1.01-2.0   | 20        | 10.31%  |
| 0.01-0.5   | 13        | 6.7%    |
| 0.51-1.0   | 11        | 5.67%   |
| 3.01-4.0   | 8         | 4.12%   |
| 2.01-3.0   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 38        | 20.99%  |
| Samsung Electronics  | 21        | 11.6%   |
| Philips              | 17        | 9.39%   |
| Acer                 | 13        | 7.18%   |
| ViewSonic            | 11        | 6.08%   |
| LG Display           | 9         | 4.97%   |
| BenQ                 | 8         | 4.42%   |
| Chimei Innolux       | 7         | 3.87%   |
| Lenovo               | 6         | 3.31%   |
| AOC                  | 6         | 3.31%   |
| Hewlett-Packard      | 5         | 2.76%   |
| AU Optronics         | 5         | 2.76%   |
| Goldstar             | 4         | 2.21%   |
| Dell                 | 4         | 2.21%   |
| SGT                  | 3         | 1.66%   |
| PANDA                | 3         | 1.66%   |
| ASUSTek Computer     | 3         | 1.66%   |
| Ancor Communications | 3         | 1.66%   |
| NLE                  | 2         | 1.1%    |
| HUAWEI               | 2         | 1.1%    |
| XSP                  | 1         | 0.55%   |
| WYT                  | 1         | 0.55%   |
| Toshiba              | 1         | 0.55%   |
| Sony                 | 1         | 0.55%   |
| RGT                  | 1         | 0.55%   |
| ITE                  | 1         | 0.55%   |
| Iiyama               | 1         | 0.55%   |
| DOY                  | 1         | 0.55%   |
| Daewoo               | 1         | 0.55%   |
| CHR                  | 1         | 0.55%   |
| CHD                  | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 17        | 9.09%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 8         | 4.28%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x195mm 15.6-inch                 | 8         | 4.28%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 4         | 2.14%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 3         | 1.6%    |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 3         | 1.6%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 3         | 1.6%    |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 3         | 1.6%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 1.6%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 1.6%    |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2         | 1.07%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 2         | 1.07%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2         | 1.07%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2         | 1.07%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                     | 2         | 1.07%   |
| Lenovo TIO22Gen4 LEN111A 1920x1080 476x268mm 21.5-inch                | 2         | 1.07%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.07%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 2         | 1.07%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.07%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2         | 1.07%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 2         | 1.07%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 2         | 1.07%   |
| XSP Digital XSP2380 1920x1080 520x310mm 23.8-inch                     | 1         | 0.53%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                  | 1         | 0.53%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1         | 0.53%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1         | 0.53%   |
| ViewSonic PJ VSC9B34 1920x1080                                        | 1         | 0.53%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch              | 1         | 0.53%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                    | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM02A0 1280x1024 376x301mm 19.0-inch  | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.53%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1         | 0.53%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1         | 0.53%   |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 1         | 0.53%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 1         | 0.53%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.53%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 129       | 75.88%  |
| 1280x1024 (SXGA)  | 9         | 5.29%   |
| 2560x1440 (QHD)   | 8         | 4.71%   |
| 1366x768 (WXGA)   | 6         | 3.53%   |
| 1600x900 (HD+)    | 5         | 2.94%   |
| 3840x2160 (4K)    | 4         | 2.35%   |
| 1920x1200 (WUXGA) | 2         | 1.18%   |
| 3440x1440         | 1         | 0.59%   |
| 2560x1080         | 1         | 0.59%   |
| 2240x1400         | 1         | 0.59%   |
| 1600x1200         | 1         | 0.59%   |
| 1440x900 (WXGA+)  | 1         | 0.59%   |
| 1280x800 (WXGA)   | 1         | 0.59%   |
| 1024x768 (XGA)    | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 55        | 30.22%  |
| 23      | 28        | 15.38%  |
| 24      | 26        | 14.29%  |
| 21      | 19        | 10.44%  |
| 27      | 12        | 6.59%   |
| 19      | 6         | 3.3%    |
| 20      | 5         | 2.75%   |
| 17      | 5         | 2.75%   |
| 13      | 4         | 2.2%    |
| 31      | 3         | 1.65%   |
| 84      | 2         | 1.1%    |
| 40      | 2         | 1.1%    |
| 14      | 2         | 1.1%    |
| 12      | 2         | 1.1%    |
| Unknown | 2         | 1.1%    |
| 54      | 1         | 0.55%   |
| 34      | 1         | 0.55%   |
| 32      | 1         | 0.55%   |
| 26      | 1         | 0.55%   |
| 25      | 1         | 0.55%   |
| 22      | 1         | 0.55%   |
| 18      | 1         | 0.55%   |
| 16      | 1         | 0.55%   |
| 11      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 64        | 36.36%  |
| 301-350     | 64        | 36.36%  |
| 401-500     | 24        | 13.64%  |
| 351-400     | 9         | 5.11%   |
| 601-700     | 3         | 1.7%    |
| 201-300     | 3         | 1.7%    |
| 701-800     | 2         | 1.14%   |
| 1501-2000   | 2         | 1.14%   |
| 901-1000    | 2         | 1.14%   |
| Unknown     | 2         | 1.14%   |
| 1001-1500   | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 146       | 87.95%  |
| 5/4   | 8         | 4.82%   |
| 16/10 | 6         | 3.61%   |
| 21/9  | 3         | 1.81%   |
| 4/3   | 2         | 1.2%    |
| 6/5   | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 62        | 35.03%  |
| 101-110        | 55        | 31.07%  |
| 151-200        | 17        | 9.6%    |
| 301-350        | 13        | 7.34%   |
| 81-90          | 6         | 3.39%   |
| 351-500        | 5         | 2.82%   |
| More than 1000 | 3         | 1.69%   |
| 251-300        | 3         | 1.69%   |
| 121-130        | 3         | 1.69%   |
| 61-70          | 2         | 1.13%   |
| 141-150        | 2         | 1.13%   |
| 501-1000       | 2         | 1.13%   |
| Unknown        | 2         | 1.13%   |
| 51-60          | 1         | 0.56%   |
| 131-140        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 73        | 43.2%   |
| 121-160 | 58        | 34.32%  |
| 101-120 | 33        | 19.53%  |
| 161-240 | 2         | 1.18%   |
| Unknown | 2         | 1.18%   |
| 1-50    | 1         | 0.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 143       | 72.59%  |
| 0     | 34        | 17.26%  |
| 2     | 20        | 10.15%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 136       | 55.28%  |
| Intel                    | 70        | 28.46%  |
| Qualcomm Atheros         | 7         | 2.85%   |
| Broadcom                 | 6         | 2.44%   |
| TP-Link                  | 5         | 2.03%   |
| MediaTek                 | 4         | 1.63%   |
| Samsung Electronics      | 3         | 1.22%   |
| Nvidia                   | 3         | 1.22%   |
| Mercucys                 | 2         | 0.81%   |
| Xiaomi                   | 1         | 0.41%   |
| VIA Technologies         | 1         | 0.41%   |
| Ralink Technology        | 1         | 0.41%   |
| Ralink                   | 1         | 0.41%   |
| OPPO Electronics         | 1         | 0.41%   |
| OKB SAPR                 | 1         | 0.41%   |
| Mellanox Technologies    | 1         | 0.41%   |
| Marvell Technology Group | 1         | 0.41%   |
| Edimax Technology        | 1         | 0.41%   |
| ASIX Electronics         | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 95        | 31.99%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 28        | 9.43%   |
| Intel Wireless 7265                                               | 12        | 4.04%   |
| Intel Ethernet Controller I225-V                                  | 8         | 2.69%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 2.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 2.36%   |
| Intel Ethernet Connection (14) I219-V                             | 6         | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.68%   |
| Intel Wireless 3165                                               | 5         | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.35%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.35%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 1.01%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 1.01%   |
| Intel Ethernet Connection (17) I219-V                             | 3         | 1.01%   |
| Intel Ethernet Connection (11) I219-V                             | 3         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3         | 1.01%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2         | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.67%   |
| Mercucys 802.11n NIC                                              | 2         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.67%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.34%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.34%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.34%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.34%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 52        | 44.07%  |
| Intel                 | 46        | 38.98%  |
| Qualcomm Atheros      | 5         | 4.24%   |
| TP-Link               | 4         | 3.39%   |
| Broadcom              | 4         | 3.39%   |
| Mercucys              | 2         | 1.69%   |
| MediaTek              | 2         | 1.69%   |
| Ralink Technology     | 1         | 0.85%   |
| Ralink                | 1         | 0.85%   |
| Edimax Technology     | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 28        | 23.33%  |
| Intel Wireless 7265                                           | 12        | 10%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 7         | 5.83%   |
| Intel Wireless 3165                                           | 5         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4         | 3.33%   |
| Intel Wi-Fi 6 AX201                                           | 4         | 3.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 4         | 3.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 3         | 2.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                | 3         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 3         | 2.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                              | 3         | 2.5%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 2         | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 1.67%   |
| Mercucys 802.11n NIC                                          | 2         | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.67%   |
| Intel Wireless 8265 / 8275                                    | 2         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 1.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.83%   |
| TP-Link 802.11n NIC                                           | 1         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.83%   |
| Realtek 802.11ac NIC                                          | 1         | 0.83%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 0.83%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                          | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 104       | 60.47%  |
| Intel                    | 48        | 27.91%  |
| Samsung Electronics      | 3         | 1.74%   |
| Nvidia                   | 3         | 1.74%   |
| Qualcomm Atheros         | 2         | 1.16%   |
| MediaTek                 | 2         | 1.16%   |
| Broadcom                 | 2         | 1.16%   |
| Xiaomi                   | 1         | 0.58%   |
| VIA Technologies         | 1         | 0.58%   |
| TP-Link                  | 1         | 0.58%   |
| OPPO Electronics         | 1         | 0.58%   |
| OKB SAPR                 | 1         | 0.58%   |
| Mellanox Technologies    | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| ASIX Electronics         | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 95        | 53.67%  |
| Intel Ethernet Controller I225-V                                  | 8         | 4.52%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 4.52%   |
| Intel Ethernet Connection (14) I219-V                             | 6         | 3.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.26%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 2.26%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.69%   |
| Intel Ethernet Connection (17) I219-V                             | 3         | 1.69%   |
| Intel Ethernet Connection (11) I219-V                             | 3         | 1.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.56%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.56%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.56%   |
| OPPO SDM710-MTP _SN:2396E2D4                                      | 1         | 0.56%   |
| OKB SAPR Ethernet controller                                      | 1         | 0.56%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 0.56%   |
| MediaTek TECNO CAMON 18P                                          | 1         | 0.56%   |
| MediaTek File-CD Gadget                                           | 1         | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.56%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 0.56%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1         | 0.56%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.56%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 160       | 58.61%  |
| WiFi     | 113       | 41.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 136       | 69.74%  |
| WiFi     | 59        | 30.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 57.29%  |
| 2     | 75        | 39.06%  |
| 0     | 5         | 2.6%    |
| 7     | 1         | 0.52%   |
| 4     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 187       | 96.89%  |
| Yes  | 6         | 3.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 44.79%  |
| Realtek Semiconductor           | 32        | 33.33%  |
| Broadcom                        | 6         | 6.25%   |
| IMC Networks                    | 4         | 4.17%   |
| Realtek                         | 2         | 2.08%   |
| Qualcomm Atheros Communications | 2         | 2.08%   |
| Cambridge Silicon Radio         | 2         | 2.08%   |
| TP-Link                         | 1         | 1.04%   |
| Ralink                          | 1         | 1.04%   |
| Lite-On Technology              | 1         | 1.04%   |
| Foxconn / Hon Hai               | 1         | 1.04%   |
| ASUSTek Computer                | 1         | 1.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 28        | 29.17%  |
| Intel Bluetooth wireless interface                  | 22        | 22.92%  |
| Intel Bluetooth Device                              | 14        | 14.58%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.17%   |
| Realtek Bluetooth Radio                             | 2         | 2.08%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.08%   |
| IMC Networks Bluetooth Device                       | 2         | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.08%   |
| TP-Link TPuLink UB500 Adapter                       | 1         | 1.04%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.04%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.04%   |
| Lite-On Wireless_Device                             | 1         | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.04%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.04%   |
| Broadcom HP Portable Valentine                      | 1         | 1.04%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.04%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1         | 1.04%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.04%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.04%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 155       | 69.51%  |
| AMD                  | 36        | 16.14%  |
| Nvidia               | 20        | 8.97%   |
| Lenovo               | 3         | 1.35%   |
| C-Media Electronics  | 3         | 1.35%   |
| Texas Instruments    | 2         | 0.9%    |
| Zhaoxin              | 1         | 0.45%   |
| Razer USA            | 1         | 0.45%   |
| MosArt Semiconductor | 1         | 0.45%   |
| Creative Technology  | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 29        | 11.33%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 8.98%   |
| Intel Audio device                                                                                | 22        | 8.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 6.25%   |
| Intel 200 Series PCH HD Audio                                                                     | 12        | 4.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 4.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 4.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.73%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 7         | 2.73%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 6         | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.95%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 1.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.56%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.17%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.17%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Lenovo ThinkCentre TIO22Gen4 for USB Audio                                                        | 2         | 0.78%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.78%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.78%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.39%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 1         | 0.39%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.39%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 22.89%  |
| Crucial             | 26        | 12.94%  |
| SK hynix            | 18        | 8.96%   |
| Foxline             | 18        | 8.96%   |
| Kingston            | 17        | 8.46%   |
| Unknown             | 15        | 7.46%   |
| Ramaxel Technology  | 8         | 3.98%   |
| Micron Technology   | 6         | 2.99%   |
| AMD                 | 6         | 2.99%   |
| Unknown (ABCD)      | 5         | 2.49%   |
| Patriot             | 5         | 2.49%   |
| Unknown             | 5         | 2.49%   |
| Elpida              | 4         | 1.99%   |
| Apacer              | 4         | 1.99%   |
| A-DATA Technology   | 3         | 1.49%   |
| Qumo                | 2         | 1%      |
| Neo Forza           | 2         | 1%      |
| Corsair             | 2         | 1%      |
| ChangXin Memory     | 2         | 1%      |
| Unknown (BA8A)      | 1         | 0.5%    |
| Unknown (89F7)      | 1         | 0.5%    |
| King Tiger          | 1         | 0.5%    |
| GOODRAM             | 1         | 0.5%    |
| Good Wealth         | 1         | 0.5%    |
| Golden Empire       | 1         | 0.5%    |
| <Invalid>           | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 8.21%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 7         | 3.38%   |
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s                | 5         | 2.42%   |
| Unknown                                                          | 5         | 2.42%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.45%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 1.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.45%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 3         | 1.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.45%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 3         | 1.45%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 3         | 1.45%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                      | 3         | 1.45%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 2         | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s              | 2         | 0.97%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                  | 2         | 0.97%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s            | 2         | 0.97%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 0.97%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s            | 2         | 0.97%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 2         | 0.97%   |
| Crucial RAM CT8G4SFRA32A.C16FG 8GB SODIMM DDR4 3200MT/s          | 2         | 0.97%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s             | 2         | 0.97%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s           | 2         | 0.97%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR 1066MT/s                         | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 400MT/s                              | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 147       | 78.61%  |
| DDR3    | 20        | 10.7%   |
| LPDDR4  | 6         | 3.21%   |
| Unknown | 6         | 3.21%   |
| SDRAM   | 4         | 2.14%   |
| DDR2    | 3         | 1.6%    |
| DDR     | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 50.53%  |
| DIMM         | 86        | 45.26%  |
| Row Of Chips | 8         | 4.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 120       | 60.61%  |
| 4096  | 40        | 20.2%   |
| 16384 | 13        | 6.57%   |
| 2048  | 13        | 6.57%   |
| 1024  | 6         | 3.03%   |
| 32768 | 5         | 2.53%   |
| 65536 | 1         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 67        | 34.54%  |
| 3200    | 49        | 25.26%  |
| 2400    | 15        | 7.73%   |
| 1600    | 11        | 5.67%   |
| 1333    | 9         | 4.64%   |
| 2666    | 6         | 3.09%   |
| 2133    | 5         | 2.58%   |
| 2933    | 3         | 1.55%   |
| 1066    | 3         | 1.55%   |
| 3466    | 2         | 1.03%   |
| 3266    | 2         | 1.03%   |
| 2934    | 2         | 1.03%   |
| 2800    | 2         | 1.03%   |
| 800     | 2         | 1.03%   |
| 667     | 2         | 1.03%   |
| Unknown | 2         | 1.03%   |
| 4800    | 1         | 0.52%   |
| 3733    | 1         | 0.52%   |
| 3533    | 1         | 0.52%   |
| 3400    | 1         | 0.52%   |
| 3000    | 1         | 0.52%   |
| 2866    | 1         | 0.52%   |
| 2733    | 1         | 0.52%   |
| 1866    | 1         | 0.52%   |
| 1800    | 1         | 0.52%   |
| 1334    | 1         | 0.52%   |
| 400     | 1         | 0.52%   |
| 333     | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Pantum | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Pantum BM5100ADN series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Syntek                                 | 21        | 20.19%  |
| Chicony Electronics                    | 19        | 18.27%  |
| IMC Networks                           | 11        | 10.58%  |
| SunplusIT                              | 6         | 5.77%   |
| Quanta                                 | 6         | 5.77%   |
| Alcor Micro                            | 6         | 5.77%   |
| Acer                                   | 4         | 3.85%   |
| Realtek Semiconductor                  | 3         | 2.88%   |
| Microdia                               | 3         | 2.88%   |
| Luxvisions Innotech Limited            | 3         | 2.88%   |
| Logitech                               | 3         | 2.88%   |
| Unknown                                | 3         | 2.88%   |
| Z-Star Microelectronics                | 2         | 1.92%   |
| USB Camera CS                          | 2         | 1.92%   |
| Suyin                                  | 2         | 1.92%   |
| Sunplus Innovation Technology          | 2         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.92%   |
| Sonix Technology                       | 1         | 0.96%   |
| Lite-On Technology                     | 1         | 0.96%   |
| Creative Technology                    | 1         | 0.96%   |
| Arkmicro Technologies                  | 1         | 0.96%   |
| Apple                                  | 1         | 0.96%   |
| AlcorMicroCorp                         | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 18        | 17.31%  |
| Chicony USB camera                                  | 9         | 8.65%   |
| SunplusIT USB Camera                                | 5         | 4.81%   |
| Alcor Micro USB 2.0 PC Camera                       | 4         | 3.85%   |
| Logitech HD Webcam C615                             | 3         | 2.88%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 2.88%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 2.88%   |
| IMC Networks Integrated Camera                      | 3         | 2.88%   |
| Acer Integrated Camera                              | 3         | 2.88%   |
| Unknown                                             | 3         | 2.88%   |
| USB Camera CS USB Camera CS                         | 2         | 1.92%   |
| Realtek 1080p Camera                                | 2         | 1.92%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.92%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 1.92%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 1.92%   |
| Chicony HD User Facing                              | 2         | 1.92%   |
| Z-Star Lenovo USB2.0 UVC Camera                     | 1         | 0.96%   |
| Z-Star Lenovo IdeaCentre Web Camera                 | 1         | 0.96%   |
| Syntek LENOVO LBG 720P CAM                          | 1         | 0.96%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.96%   |
| Syntek Integrated RGB Camera                        | 1         | 0.96%   |
| Suyin HP Truevision HD                              | 1         | 0.96%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.96%   |
| SunplusIT USB 2.0 Camera                            | 1         | 0.96%   |
| Sunplus BKX Usb FHD Camera                          | 1         | 0.96%   |
| Sunplus Asus Webcam                                 | 1         | 0.96%   |
| Sonix USB 2.0 Camera                                | 1         | 0.96%   |
| Realtek USB Camera                                  | 1         | 0.96%   |
| Quanta USB HD Webcam                                | 1         | 0.96%   |
| Quanta HP 5MP Camera                                | 1         | 0.96%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 0.96%   |
| Quanta HD Camera                                    | 1         | 0.96%   |
| Microdia Webcam Vitade AF                           | 1         | 0.96%   |
| Microdia USB 2.0 Camera                             | 1         | 0.96%   |
| Microdia Camera                                     | 1         | 0.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.96%   |
| Lite-On HP 2.0MP High Definition Webcam             | 1         | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.96%   |
| IMC Networks HD Camera                              | 1         | 0.96%   |
| Creative VF0530 Live! Cam Chat IM                   | 1         | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 6         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device | 6         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Aladdin R.D. | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Aladdin R.D. JaCarta | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 147       | 75%     |
| 1     | 38        | 19.39%  |
| 2     | 7         | 3.57%   |
| 4     | 2         | 1.02%   |
| 3     | 2         | 1.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 31        | 50%     |
| Net/wireless             | 8         | 12.9%   |
| Fingerprint reader       | 6         | 9.68%   |
| Communication controller | 5         | 8.06%   |
| Unassigned class         | 3         | 4.84%   |
| Sound                    | 2         | 3.23%   |
| Net/ethernet             | 2         | 3.23%   |
| Network                  | 1         | 1.61%   |
| Multimedia controller    | 1         | 1.61%   |
| Chipcard                 | 1         | 1.61%   |
| Camera                   | 1         | 1.61%   |
| Bluetooth                | 1         | 1.61%   |

