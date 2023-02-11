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

Total: 138

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Red OS 7.3.1 | 42       | 40%     |
| Red OS 7.3   | 37       | 35.24%  |
| Red OS 7.3.2 | 18       | 17.14%  |
| Red OS 7.2   | 8        | 7.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 97       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.10-1.el7.x86_64   | 21       | 19.09%  |
| 5.10.29-1.el7.x86_64   | 19       | 17.27%  |
| 5.15.35-5.el7.3.x86_64 | 17       | 15.45%  |
| 5.15.72-1.el7.3.x86_64 | 10       | 9.09%   |
| 5.15.78-2.el7.3.x86_64 | 9        | 8.18%   |
| 5.15.35-1.el7.3.x86_64 | 8        | 7.27%   |
| 5.15.35-4.el7.3.x86_64 | 7        | 6.36%   |
| 4.19.79-1.el7.x86_64   | 6        | 5.45%   |
| 5.15.10-3.el7.x86_64   | 3        | 2.73%   |
| 5.15.10-2.el7.x86_64   | 3        | 2.73%   |
| 5.14.9-1.el7.x86_64    | 1        | 0.91%   |
| 5.10.29-3.el7.x86_64   | 1        | 0.91%   |
| 5.10.24-3.el7.x86_64   | 1        | 0.91%   |
| 5.10.24-2.el7.x86_64   | 1        | 0.91%   |
| 5.10.1-1.el7.x86_64    | 1        | 0.91%   |
| 4.19.56-2.el7.x86_64   | 1        | 0.91%   |
| 4.19.204-1.el7.x86_64  | 1        | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.35  | 29       | 27.1%   |
| 5.15.10  | 27       | 25.23%  |
| 5.10.29  | 20       | 18.69%  |
| 5.15.72  | 10       | 9.35%   |
| 5.15.78  | 9        | 8.41%   |
| 4.19.79  | 6        | 5.61%   |
| 5.10.24  | 2        | 1.87%   |
| 5.14.9   | 1        | 0.93%   |
| 5.10.1   | 1        | 0.93%   |
| 4.19.56  | 1        | 0.93%   |
| 4.19.204 | 1        | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 71       | 68.93%  |
| 5.10    | 23       | 22.33%  |
| 4.19    | 8        | 7.77%   |
| 5.14    | 1        | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 97       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 79       | 77.45%  |
| Cinnamon   | 20       | 19.61%  |
| Unknown    | 2        | 1.96%   |
| X-Cinnamon | 1        | 0.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 93       | 93%     |
| Wayland | 6        | 6%      |
| Unknown | 1        | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 93       | 94.9%   |
| Unknown | 3        | 3.06%   |
| SDDM    | 2        | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 93       | 94.9%   |
| ru_RU   | 5        | 5.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 66       | 66%     |
| BIOS | 34       | 34%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 94       | 95.92%  |
| Btrfs   | 3        | 3.06%   |
| Unknown | 1        | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 67       | 67.68%  |
| MBR     | 30       | 30.3%   |
| Unknown | 2        | 2.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 88.89%  |
| Yes       | 11       | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 74.49%  |
| Yes       | 25       | 25.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 30       | 30.93%  |
| ASUSTek Computer    | 22       | 22.68%  |
| ASRock              | 12       | 12.37%  |
| MSI                 | 7        | 7.22%   |
| DEPO Computers      | 6        | 6.19%   |
| Hewlett-Packard     | 5        | 5.15%   |
| Aquarius            | 5        | 5.15%   |
| Lenovo              | 3        | 3.09%   |
| Unknown             | 3        | 3.09%   |
| RDW                 | 1        | 1.03%   |
| ECS                 | 1        | 1.03%   |
| Dell                | 1        | 1.03%   |
| Colorful Technology | 1        | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Gigabyte B365M DS3H                    | 4        | 4.12%   |
| DEPO Computers DPH310T                 | 4        | 4.12%   |
| Gigabyte H110M-S2                      | 3        | 3.09%   |
| Unknown                                | 3        | 3.09%   |
| MSI MS-7D14                            | 2        | 2.06%   |
| Gigabyte B560M DS3H                    | 2        | 2.06%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 2.06%   |
| DEPO Computers DPH410S                 | 2        | 2.06%   |
| ASUS PRIME H510T2/CSM                  | 2        | 2.06%   |
| ASUS PC                                | 2        | 2.06%   |
| ASUS MINIPC PB62                       | 2        | 2.06%   |
| ASUS All Series                        | 2        | 2.06%   |
| ASRock H510M-HVS R2.0                  | 2        | 2.06%   |
| Aquarius P30 K44 R53                   | 2        | 2.06%   |
| RDW RDW-MB-B450M V.1                   | 1        | 1.03%   |
| MSI MS-7D48                            | 1        | 1.03%   |
| MSI MS-7D35                            | 1        | 1.03%   |
| MSI MS-7B86                            | 1        | 1.03%   |
| MSI MS-7636                            | 1        | 1.03%   |
| MSI Compaq dx2300 Microtower           | 1        | 1.03%   |
| Lenovo V50s-07IMB 11EF0011RU           | 1        | 1.03%   |
| Lenovo ThinkCentre M70e 0851RZ3        | 1        | 1.03%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS | 1        | 1.03%   |
| HP Z400 Workstation                    | 1        | 1.03%   |
| HP ProOne 400 G1 AiO                   | 1        | 1.03%   |
| HP ProDesk 400 G6 MT                   | 1        | 1.03%   |
| HP EliteDesk 800 G1 TWR                | 1        | 1.03%   |
| HP Compaq 8200 Elite SFF PC            | 1        | 1.03%   |
| Gigabyte X58-USB3                      | 1        | 1.03%   |
| Gigabyte X570S UD                      | 1        | 1.03%   |
| Gigabyte M61SME-S2                     | 1        | 1.03%   |
| Gigabyte H610M S2H DDR4                | 1        | 1.03%   |
| Gigabyte H510M S2H                     | 1        | 1.03%   |
| Gigabyte H410M S2H V3                  | 1        | 1.03%   |
| Gigabyte H410M H V3                    | 1        | 1.03%   |
| Gigabyte H110M-M.2                     | 1        | 1.03%   |
| Gigabyte GA-880GM-D2H                  | 1        | 1.03%   |
| Gigabyte B75M-D3V                      | 1        | 1.03%   |
| Gigabyte B75M-D2V                      | 1        | 1.03%   |
| Gigabyte B560M H                       | 1        | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 7        | 7.22%   |
| Gigabyte B365M         | 5        | 5.15%   |
| DEPO Computers DPH310T | 4        | 4.12%   |
| Gigabyte H110M-S2      | 3        | 3.09%   |
| Gigabyte B560M         | 3        | 3.09%   |
| Unknown                | 3        | 3.09%   |
| MSI MS-7D14            | 2        | 2.06%   |
| Gigabyte H410M         | 2        | 2.06%   |
| Gigabyte B550          | 2        | 2.06%   |
| DEPO Computers DPH410S | 2        | 2.06%   |
| ASUS PC                | 2        | 2.06%   |
| ASUS MINIPC            | 2        | 2.06%   |
| ASUS All               | 2        | 2.06%   |
| ASRock H510M-HVS       | 2        | 2.06%   |
| Aquarius P30           | 2        | 2.06%   |
| RDW RDW-MB-B450M       | 1        | 1.03%   |
| MSI MS-7D48            | 1        | 1.03%   |
| MSI MS-7D35            | 1        | 1.03%   |
| MSI MS-7B86            | 1        | 1.03%   |
| MSI MS-7636            | 1        | 1.03%   |
| MSI Compaq             | 1        | 1.03%   |
| Lenovo V50s-07IMB      | 1        | 1.03%   |
| Lenovo ThinkCentre     | 1        | 1.03%   |
| Lenovo IdeaCentre      | 1        | 1.03%   |
| HP Z400                | 1        | 1.03%   |
| HP ProOne              | 1        | 1.03%   |
| HP ProDesk             | 1        | 1.03%   |
| HP EliteDesk           | 1        | 1.03%   |
| HP Compaq              | 1        | 1.03%   |
| Gigabyte X58-USB3      | 1        | 1.03%   |
| Gigabyte X570S         | 1        | 1.03%   |
| Gigabyte M61SME-S2     | 1        | 1.03%   |
| Gigabyte H610M         | 1        | 1.03%   |
| Gigabyte H510M         | 1        | 1.03%   |
| Gigabyte H110M-M.2     | 1        | 1.03%   |
| Gigabyte GA-880GM-D2H  | 1        | 1.03%   |
| Gigabyte B75M-D3V      | 1        | 1.03%   |
| Gigabyte B75M-D2V      | 1        | 1.03%   |
| Gigabyte B450M         | 1        | 1.03%   |
| Gigabyte B450          | 1        | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 26       | 26.8%   |
| 2020 | 12       | 12.37%  |
| 2019 | 11       | 11.34%  |
| 2022 | 10       | 10.31%  |
| 2016 | 7        | 7.22%   |
| 2018 | 6        | 6.19%   |
| 2010 | 5        | 5.15%   |
| 2013 | 4        | 4.12%   |
| 2012 | 4        | 4.12%   |
| 2011 | 3        | 3.09%   |
| 2014 | 2        | 2.06%   |
| 2009 | 2        | 2.06%   |
| 2007 | 2        | 2.06%   |
| 2017 | 1        | 1.03%   |
| 2015 | 1        | 1.03%   |
| 2008 | 1        | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 97       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 97       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 34       | 35.05%  |
| 16.01-24.0 | 27       | 27.84%  |
| 8.01-16.0  | 15       | 15.46%  |
| 3.01-4.0   | 11       | 11.34%  |
| 32.01-64.0 | 4        | 4.12%   |
| 24.01-32.0 | 2        | 2.06%   |
| 1.01-2.0   | 2        | 2.06%   |
| 0.51-1.0   | 1        | 1.03%   |
| Unknown    | 1        | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 44       | 42.31%  |
| 3.01-4.0  | 14       | 13.46%  |
| 2.01-3.0  | 14       | 13.46%  |
| 4.01-8.0  | 13       | 12.5%   |
| 0.51-1.0  | 12       | 11.54%  |
| 8.01-16.0 | 5        | 4.81%   |
| 0.01-0.5  | 1        | 0.96%   |
| Unknown   | 1        | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 62%     |
| 2      | 29       | 29%     |
| 3      | 5        | 5%      |
| 4      | 3        | 3%      |
| 5      | 1        | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 69.39%  |
| Yes       | 30       | 30.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 98.97%  |
| No        | 1        | 1.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 75.76%  |
| Yes       | 24       | 24.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 81.63%  |
| Yes       | 18       | 18.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 97       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Murom           | 19       | 19.59%  |
| Salekhard       | 16       | 16.49%  |
| Moscow          | 15       | 15.46%  |
| Yekaterinburg   | 4        | 4.12%   |
| Novy Urengoy    | 3        | 3.09%   |
| Novosibirsk     | 3        | 3.09%   |
| Veliky Novgorod | 2        | 2.06%   |
| Perm            | 2        | 2.06%   |
| Penza           | 2        | 2.06%   |
| Kurgan          | 2        | 2.06%   |
| Khabarovsk      | 2        | 2.06%   |
| Kaluga          | 2        | 2.06%   |
| Balashikha      | 2        | 2.06%   |
| Baksan          | 2        | 2.06%   |
| Ulyanovsk       | 1        | 1.03%   |
| Tomsk           | 1        | 1.03%   |
| Svetlograd      | 1        | 1.03%   |
| Surgut          | 1        | 1.03%   |
| Stavropol       | 1        | 1.03%   |
| St Petersburg   | 1        | 1.03%   |
| Shakhtersk      | 1        | 1.03%   |
| Rostov-on-Don   | 1        | 1.03%   |
| Nadym           | 1        | 1.03%   |
| Muromskiy       | 1        | 1.03%   |
| Magadan         | 1        | 1.03%   |
| Kursk           | 1        | 1.03%   |
| Krasnoyarsk     | 1        | 1.03%   |
| Krasnodar       | 1        | 1.03%   |
| Kovrov          | 1        | 1.03%   |
| Kol'chugino     | 1        | 1.03%   |
| Kirov           | 1        | 1.03%   |
| Kholmsk         | 1        | 1.03%   |
| Bryansk         | 1        | 1.03%   |
| Arzamas         | 1        | 1.03%   |
| Arkhangelsk     | 1        | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 33       | 49     | 23.57%  |
| WDC                          | 20       | 24     | 14.29%  |
| Toshiba                      | 11       | 13     | 7.86%   |
| Samsung Electronics          | 10       | 14     | 7.14%   |
| Kingston                     | 10       | 11     | 7.14%   |
| A-DATA Technology            | 8        | 8      | 5.71%   |
| Apacer                       | 6        | 6      | 4.29%   |
| SanDisk                      | 5        | 7      | 3.57%   |
| Crucial                      | 4        | 7      | 2.86%   |
| Patriot                      | 3        | 3      | 2.14%   |
| KingSpec                     | 3        | 3      | 2.14%   |
| Hitachi                      | 3        | 3      | 2.14%   |
| Foxline                      | 3        | 3      | 2.14%   |
| KIOXIA-EXCERIA               | 2        | 2      | 1.43%   |
| Intel                        | 2        | 2      | 1.43%   |
| ExeGate                      | 2        | 3      | 1.43%   |
| AMD                          | 2        | 2      | 1.43%   |
| AGI                          | 2        | 2      | 1.43%   |
| XPG                          | 1        | 1      | 0.71%   |
| Unknown                      | 1        | 1      | 0.71%   |
| SPCC                         | 1        | 1      | 0.71%   |
| Smartbuy                     | 1        | 1      | 0.71%   |
| Silicon Motion               | 1        | 1      | 0.71%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.71%   |
| Phison                       | 1        | 1      | 0.71%   |
| Netac                        | 1        | 1      | 0.71%   |
| GOODRAM                      | 1        | 1      | 0.71%   |
| Corsair                      | 1        | 1      | 0.71%   |
| China                        | 1        | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB     | 6        | 4.08%   |
| Seagate ST500DM002-1BD142 500GB    | 5        | 3.4%    |
| Toshiba HDWD110 1TB                | 4        | 2.72%   |
| Seagate ST1000LM049-2GH172 1TB     | 4        | 2.72%   |
| Kingston SA400S37240G 240GB SSD    | 4        | 2.72%   |
| Apacer AS2280P4 256GB              | 4        | 2.72%   |
| Seagate ST1000DM010-2DM162 1TB     | 3        | 2.04%   |
| Crucial CT240BX500SSD1 240GB       | 3        | 2.04%   |
| WDC WD10EZEX-22MFCA0 1TB           | 2        | 1.36%   |
| Toshiba HDWD105 500GB              | 2        | 1.36%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.36%   |
| Seagate ST1000DM003-1SB10C 1TB     | 2        | 1.36%   |
| SanDisk SD8SBAT256G1122 256GB SSD  | 2        | 1.36%   |
| Samsung SSD 860 EVO 250GB          | 2        | 1.36%   |
| KIOXIA-EXCERIA SATA SSD 480GB      | 2        | 1.36%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.36%   |
| Kingston OM8PCP3512F-A02 512GB     | 2        | 1.36%   |
| Foxline FLSSD240X5SE 240GB         | 2        | 1.36%   |
| ExeGate EX276690RUS(960G 960GB SSD | 2        | 1.36%   |
| AGI AGI512G16AI198 512GB           | 2        | 1.36%   |
| A-DATA SX6000PNP 256GB             | 2        | 1.36%   |
| XPG GAMMIX S70 BLADE 2TB           | 1        | 0.68%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.68%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 1        | 0.68%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 0.68%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1        | 0.68%   |
| WDC WD5000AAKS-00D2B0 500GB        | 1        | 0.68%   |
| WDC WD40PURZ-85TTDY0 4TB           | 1        | 0.68%   |
| WDC WD3200AAKX-001CA0 320GB        | 1        | 0.68%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 0.68%   |
| WDC WD25 00LPCX-24C6HT0 250GB      | 1        | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 0.68%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.68%   |
| WDC WD15EARS-19MVWB0 1TB           | 1        | 0.68%   |
| WDC WD10SPZX-22Z10T1 1TB           | 1        | 0.68%   |
| WDC WD10EZEX-75ZF5A0 1TB           | 1        | 0.68%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1        | 0.68%   |
| WDC WD10EZEX-00BBHA0 1TB           | 1        | 0.68%   |
| WDC WD10EARX-00N0YB0 1TB           | 1        | 0.68%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 32       | 48     | 49.23%  |
| WDC                 | 17       | 21     | 26.15%  |
| Toshiba             | 10       | 12     | 15.38%  |
| Samsung Electronics | 3        | 4      | 4.62%   |
| Hitachi             | 3        | 3      | 4.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 7      | 15.22%  |
| A-DATA Technology   | 5        | 5      | 10.87%  |
| SanDisk             | 4        | 6      | 8.7%    |
| Samsung Electronics | 4        | 5      | 8.7%    |
| KingSpec            | 3        | 3      | 6.52%   |
| Foxline             | 3        | 3      | 6.52%   |
| Crucial             | 3        | 6      | 6.52%   |
| WDC                 | 2        | 2      | 4.35%   |
| Patriot             | 2        | 2      | 4.35%   |
| KIOXIA-EXCERIA      | 2        | 2      | 4.35%   |
| ExeGate             | 2        | 3      | 4.35%   |
| Apacer              | 2        | 2      | 4.35%   |
| Toshiba             | 1        | 1      | 2.17%   |
| Smartbuy            | 1        | 1      | 2.17%   |
| Seagate             | 1        | 1      | 2.17%   |
| Intel               | 1        | 1      | 2.17%   |
| GOODRAM             | 1        | 1      | 2.17%   |
| China               | 1        | 1      | 2.17%   |
| AMD                 | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 59       | 88     | 45.38%  |
| SSD  | 43       | 53     | 33.08%  |
| NVMe | 28       | 32     | 21.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 83       | 140    | 74.11%  |
| NVMe | 28       | 32     | 25%     |
| SAS  | 1        | 1      | 0.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 56       | 69     | 52.83%  |
| 0.51-1.0   | 42       | 62     | 39.62%  |
| 1.01-2.0   | 6        | 8      | 5.66%   |
| 3.01-4.0   | 1        | 1      | 0.94%   |
| 2.01-3.0   | 1        | 1      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 31       | 31%     |
| 501-1000       | 26       | 26%     |
| 251-500        | 22       | 22%     |
| 1001-2000      | 7        | 7%      |
| 51-100         | 6        | 6%      |
| 2001-3000      | 5        | 5%      |
| More than 3000 | 1        | 1%      |
| 21-50          | 1        | 1%      |
| Unknown        | 1        | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 51.43%  |
| 21-50          | 15       | 14.29%  |
| 51-100         | 10       | 9.52%   |
| 501-1000       | 9        | 8.57%   |
| 101-250        | 7        | 6.67%   |
| 251-500        | 4        | 3.81%   |
| 1001-2000      | 3        | 2.86%   |
| More than 3000 | 1        | 0.95%   |
| 2001-3000      | 1        | 0.95%   |
| Unknown        | 1        | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3        | 3      | 17.65%  |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 6      | 11.76%  |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 5.88%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 1      | 5.88%   |
| WDC WD5000AAKS-00D2B0 500GB       | 1        | 1      | 5.88%   |
| WDC WD3200AAKX-001CA0 320GB       | 1        | 1      | 5.88%   |
| WDC WD10EZEX-75ZF5A0 1TB          | 1        | 1      | 5.88%   |
| WDC WD10EZEX-00WN4A0 1TB          | 1        | 1      | 5.88%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 5.88%   |
| SPCC M.2 PCIe SSD 512GB           | 1        | 1      | 5.88%   |
| Seagate ST9500423AS 500GB         | 1        | 1      | 5.88%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 5.88%   |
| Samsung Electronics HD400LJ 400GB | 1        | 1      | 5.88%   |
| Hitachi HDS5C1050CLA382 500GB     | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 41.18%  |
| Seagate             | 7        | 11     | 41.18%  |
| SPCC                | 1        | 1      | 5.88%   |
| Samsung Electronics | 1        | 1      | 5.88%   |
| Hitachi             | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 11     | 46.67%  |
| WDC                 | 6        | 6      | 40%     |
| Samsung Electronics | 1        | 1      | 6.67%   |
| Hitachi             | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 19     | 85.71%  |
| NVMe | 1        | 1      | 7.14%   |
| SSD  | 1        | 1      | 7.14%   |

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
| Works    | 88       | 145    | 83.02%  |
| Malfunc  | 14       | 21     | 13.21%  |
| Detected | 4        | 7      | 3.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 79       | 61.24%  |
| AMD                          | 15       | 11.63%  |
| Phison Electronics           | 6        | 4.65%   |
| Silicon Motion               | 4        | 3.1%    |
| Samsung Electronics          | 4        | 3.1%    |
| Realtek Semiconductor        | 4        | 3.1%    |
| Nvidia                       | 3        | 2.33%   |
| Kingston Technology Company  | 3        | 2.33%   |
| SanDisk                      | 2        | 1.55%   |
| JMicron Technology           | 2        | 1.55%   |
| VIA Technologies             | 1        | 0.78%   |
| Shenzhen Longsys Electronics | 1        | 0.78%   |
| Netac Technology             | 1        | 0.78%   |
| Micron/Crucial Technology    | 1        | 0.78%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.78%   |
| ADATA Technology             | 1        | 0.78%   |
| Unknown                      | 1        | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 24       | 16.44%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 12       | 8.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9        | 6.16%   |
| Phison PS5013 E13 NVMe Controller                                              | 5        | 3.42%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 3.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5        | 3.42%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 3.42%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 3.42%   |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 3.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4        | 2.74%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 2.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 2.74%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 2.05%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3        | 2.05%   |
| Nvidia MCP61 SATA Controller                                                   | 3        | 2.05%   |
| Nvidia MCP61 IDE                                                               | 3        | 2.05%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 2.05%   |
| JMicron JMB368 IDE controller                                                  | 2        | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.37%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.68%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1        | 0.68%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 0.68%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.68%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.68%   |
| Netac Non-Volatile memory controller                                           | 1        | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.68%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.68%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.68%   |
| Intel Non-Volatile memory controller                                           | 1        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 84       | 65.12%  |
| NVMe | 28       | 21.71%  |
| IDE  | 14       | 10.85%  |
| RAID | 3        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 79       | 81.44%  |
| AMD    | 18       | 18.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz           | 11       | 11.34%  |
| Intel Core i3-10100 CPU @ 3.60GHz          | 10       | 10.31%  |
| Intel Core i5-10400 CPU @ 2.90GHz          | 6        | 6.19%   |
| Intel Pentium CPU G4500 @ 3.50GHz          | 3        | 3.09%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 3        | 3.09%   |
| Intel Core i3-10105 CPU @ 3.70GHz          | 3        | 3.09%   |
| Intel Core i7-10700K CPU @ 3.80GHz         | 2        | 2.06%   |
| Intel Core i5-10500 CPU @ 3.10GHz          | 2        | 2.06%   |
| Intel Core i3-6100 CPU @ 3.70GHz           | 2        | 2.06%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 2        | 2.06%   |
| Intel 12th Gen Core i5-12400               | 2        | 2.06%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz     | 2        | 2.06%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics | 2        | 2.06%   |
| AMD FX-4100 Quad-Core Processor            | 2        | 2.06%   |
| Intel Xeon CPU W3670 @ 3.20GHz             | 1        | 1.03%   |
| Intel Pentium Gold G7400                   | 1        | 1.03%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz     | 1        | 1.03%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz     | 1        | 1.03%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz     | 1        | 1.03%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 1        | 1.03%   |
| Intel Pentium CPU G4400 @ 3.30GHz          | 1        | 1.03%   |
| Intel Core i7-4790T CPU @ 2.70GHz          | 1        | 1.03%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 1        | 1.03%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 1        | 1.03%   |
| Intel Core i7-10700 CPU @ 2.90GHz          | 1        | 1.03%   |
| Intel Core i7 CPU 950 @ 3.07GHz            | 1        | 1.03%   |
| Intel Core i5-9500 CPU @ 3.00GHz           | 1        | 1.03%   |
| Intel Core i5-9400F CPU @ 2.90GHz          | 1        | 1.03%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 1        | 1.03%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 1        | 1.03%   |
| Intel Core i5-10600K CPU @ 4.10GHz         | 1        | 1.03%   |
| Intel Core i5 CPU 750 @ 2.67GHz            | 1        | 1.03%   |
| Intel Core i5 CPU 650 @ 3.20GHz            | 1        | 1.03%   |
| Intel Core i3-8100 CPU @ 3.60GHz           | 1        | 1.03%   |
| Intel Core i3-10100F CPU @ 3.60GHz         | 1        | 1.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 1        | 1.03%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz       | 1        | 1.03%   |
| Intel Core 2 CPU 6600 @ 2.40GHz            | 1        | 1.03%   |
| Intel Celeron J4125 CPU @ 2.00GHz          | 1        | 1.03%   |
| Intel Celeron G5925 CPU @ 3.60GHz          | 1        | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 29       | 29.9%   |
| Intel Core i3      | 19       | 19.59%  |
| Intel Core i7      | 7        | 7.22%   |
| Other              | 6        | 6.19%   |
| Intel Pentium      | 5        | 5.15%   |
| Intel Celeron      | 5        | 5.15%   |
| AMD Ryzen 5        | 5        | 5.15%   |
| Intel Pentium Gold | 4        | 4.12%   |
| AMD FX             | 3        | 3.09%   |
| Intel Core 2 Duo   | 2        | 2.06%   |
| AMD Ryzen 7 PRO    | 2        | 2.06%   |
| AMD Athlon II X2   | 2        | 2.06%   |
| Intel Xeon         | 1        | 1.03%   |
| Intel Core 2       | 1        | 1.03%   |
| AMD Ryzen 9        | 1        | 1.03%   |
| AMD Ryzen 7        | 1        | 1.03%   |
| AMD Ryzen 5 PRO    | 1        | 1.03%   |
| AMD Ryzen 3        | 1        | 1.03%   |
| AMD Phenom         | 1        | 1.03%   |
| AMD Athlon         | 1        | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 31       | 31.96%  |
| 6      | 30       | 30.93%  |
| 2      | 26       | 26.8%   |
| 8      | 8        | 8.25%   |
| 12     | 1        | 1.03%   |
| 3      | 1        | 1.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 97       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 60       | 61.86%  |
| 1      | 37       | 38.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 96       | 98.97%  |
| Unknown        | 1        | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 24       | 24.49%  |
| 0x906ed    | 9        | 9.18%   |
| 0x506e3    | 8        | 8.16%   |
| 0x906ea    | 6        | 6.12%   |
| 0x306c3    | 5        | 5.1%    |
| 0x90675    | 4        | 4.08%   |
| 0x306a9    | 4        | 4.08%   |
| 0xa0671    | 3        | 3.06%   |
| 0xa0655    | 3        | 3.06%   |
| 0x08600106 | 3        | 3.06%   |
| 0x08108109 | 3        | 3.06%   |
| 0x906eb    | 2        | 2.04%   |
| 0x1067a    | 2        | 2.04%   |
| 0x0a50000d | 2        | 2.04%   |
| 0x0600063e | 2        | 2.04%   |
| 0xa0654    | 1        | 1.02%   |
| 0x906e9    | 1        | 1.02%   |
| 0x706a8    | 1        | 1.02%   |
| 0x6f6      | 1        | 1.02%   |
| 0x206c2    | 1        | 1.02%   |
| 0x206a7    | 1        | 1.02%   |
| 0x20652    | 1        | 1.02%   |
| 0x106e5    | 1        | 1.02%   |
| 0x106a5    | 1        | 1.02%   |
| 0x0a201205 | 1        | 1.02%   |
| 0x0a201016 | 1        | 1.02%   |
| 0x08701021 | 1        | 1.02%   |
| 0x08101016 | 1        | 1.02%   |
| 0x06000852 | 1        | 1.02%   |
| 0x010000c8 | 1        | 1.02%   |
| 0x010000c7 | 1        | 1.02%   |
| 0x01000083 | 1        | 1.02%   |
| Unknown    | 1        | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| CometLake        | 28       | 28.87%  |
| KabyLake         | 18       | 18.56%  |
| Skylake          | 8        | 8.25%   |
| Haswell          | 5        | 5.15%   |
| Zen 3            | 4        | 4.12%   |
| Zen 2            | 4        | 4.12%   |
| IvyBridge        | 4        | 4.12%   |
| Unknown          | 4        | 4.12%   |
| Zen+             | 3        | 3.09%   |
| K10              | 3        | 3.09%   |
| Alderlake Hybrid | 3        | 3.09%   |
| Westmere         | 2        | 2.06%   |
| Penryn           | 2        | 2.06%   |
| Nehalem          | 2        | 2.06%   |
| Bulldozer        | 2        | 2.06%   |
| Zen              | 1        | 1.03%   |
| SandyBridge      | 1        | 1.03%   |
| Piledriver       | 1        | 1.03%   |
| Goldmont plus    | 1        | 1.03%   |
| Core             | 1        | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 67       | 67%     |
| AMD    | 18       | 18%     |
| Nvidia | 15       | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 23       | 22.77%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13       | 12.87%  |
| Intel HD Graphics 530                                                       | 5        | 4.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 3.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 2.97%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 3        | 2.97%   |
| AMD Renoir                                                                  | 3        | 2.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.98%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.98%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 2        | 1.98%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.98%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.99%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.99%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.99%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.99%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.99%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.99%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.99%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.99%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 0.99%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 0.99%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 0.99%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.99%   |
| Intel HD Graphics 610                                                       | 1        | 0.99%   |
| Intel HD Graphics 510                                                       | 1        | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.99%   |
| Intel Alder Lake-S GT1 [UHD Graphics 710]                                   | 1        | 0.99%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 0.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 0.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 0.99%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 0.99%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 0.99%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                       | 1        | 0.99%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                   | 1        | 0.99%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 65       | 67.01%  |
| 1 x AMD        | 16       | 16.49%  |
| 1 x Nvidia     | 13       | 13.4%   |
| 2 x AMD        | 1        | 1.03%   |
| Intel + Nvidia | 1        | 1.03%   |
| AMD + Nvidia   | 1        | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 72       | 74.23%  |
| Unknown     | 21       | 21.65%  |
| Proprietary | 4        | 4.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 73.2%   |
| 1.01-2.0   | 10       | 10.31%  |
| 0.01-0.5   | 7        | 7.22%   |
| 0.51-1.0   | 6        | 6.19%   |
| 3.01-4.0   | 2        | 2.06%   |
| 2.01-3.0   | 1        | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 15.48%  |
| Philips              | 13       | 15.48%  |
| Acer                 | 12       | 14.29%  |
| ViewSonic            | 10       | 11.9%   |
| BenQ                 | 8        | 9.52%   |
| AOC                  | 6        | 7.14%   |
| Goldstar             | 4        | 4.76%   |
| Dell                 | 4        | 4.76%   |
| SGT                  | 3        | 3.57%   |
| Hewlett-Packard      | 2        | 2.38%   |
| Sony                 | 1        | 1.19%   |
| Lenovo               | 1        | 1.19%   |
| HUAWEI               | 1        | 1.19%   |
| DOY                  | 1        | 1.19%   |
| Daewoo               | 1        | 1.19%   |
| CHR                  | 1        | 1.19%   |
| CHD                  | 1        | 1.19%   |
| ASUSTek Computer     | 1        | 1.19%   |
| Ancor Communications | 1        | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 7.78%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 4        | 4.44%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 3        | 3.33%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2        | 2.22%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 2        | 2.22%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2        | 2.22%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 2.22%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 2.22%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 2        | 2.22%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 2.22%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 2        | 2.22%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 2        | 2.22%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 1.11%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1        | 1.11%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                    | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM02A0 1280x1024 376x301mm 19.0-inch  | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 1.11%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch     | 1        | 1.11%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 1.11%   |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 1        | 1.11%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1        | 1.11%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1        | 1.11%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch    | 1        | 1.11%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1        | 1.11%   |
| Philips PHL 241E1 PHLC207 1920x1080 527x296mm 23.8-inch               | 1        | 1.11%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch              | 1        | 1.11%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 1.11%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 1        | 1.11%   |
| Philips 206VL PHLC08C 1600x900 443x249mm 20.0-inch                    | 1        | 1.11%   |
| Philips 190VL PHLC080 1440x900 408x255mm 18.9-inch                    | 1        | 1.11%   |
| Lenovo S24e-20 LEN62AE 1920x1080 527x296mm 23.8-inch                  | 1        | 1.11%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                   | 1        | 1.11%   |
| Hewlett-Packard Z22i HWP308E 1920x1080 477x268mm 21.5-inch            | 1        | 1.11%   |
| Hewlett-Packard LP2065 HWP0A71 1600x1200 408x306mm 20.1-inch          | 1        | 1.11%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 1        | 1.11%   |
| Goldstar E2250 GSM578E 1920x1080 477x268mm 21.5-inch                  | 1        | 1.11%   |
| Goldstar D2342P GSM5842 1920x1080 510x290mm 23.1-inch                 | 1        | 1.11%   |
| Goldstar 2D HD LG TV GSM59CA 1366x768 510x290mm 23.1-inch             | 1        | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 55       | 69.62%  |
| 2560x1440 (QHD)   | 8        | 10.13%  |
| 1280x1024 (SXGA)  | 7        | 8.86%   |
| 1600x900 (HD+)    | 3        | 3.8%    |
| 1920x1200 (WUXGA) | 2        | 2.53%   |
| 3840x2160 (4K)    | 1        | 1.27%   |
| 1600x1200         | 1        | 1.27%   |
| 1440x900 (WXGA+)  | 1        | 1.27%   |
| 1024x768 (XGA)    | 1        | 1.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 22       | 25.58%  |
| 23     | 20       | 23.26%  |
| 21     | 15       | 17.44%  |
| 27     | 11       | 12.79%  |
| 19     | 5        | 5.81%   |
| 20     | 4        | 4.65%   |
| 31     | 3        | 3.49%   |
| 17     | 2        | 2.33%   |
| 32     | 1        | 1.16%   |
| 25     | 1        | 1.16%   |
| 18     | 1        | 1.16%   |
| 15     | 1        | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 49       | 61.25%  |
| 401-500     | 19       | 23.75%  |
| 351-400     | 5        | 6.25%   |
| 601-700     | 3        | 3.75%   |
| 301-350     | 3        | 3.75%   |
| 701-800     | 1        | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 65       | 83.33%  |
| 5/4   | 7        | 8.97%   |
| 16/10 | 4        | 5.13%   |
| 4/3   | 2        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 47       | 58.02%  |
| 151-200        | 13       | 16.05%  |
| 301-350        | 11       | 13.58%  |
| 351-500        | 4        | 4.94%   |
| 251-300        | 3        | 3.7%    |
| 141-150        | 2        | 2.47%   |
| 101-110        | 1        | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 73.68%  |
| 101-120 | 20       | 26.32%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 67.33%  |
| 0     | 21       | 20.79%  |
| 2     | 12       | 11.88%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 75       | 63.03%  |
| Intel                    | 25       | 21.01%  |
| Nvidia                   | 3        | 2.52%   |
| Broadcom                 | 3        | 2.52%   |
| TP-Link                  | 2        | 1.68%   |
| Samsung Electronics      | 2        | 1.68%   |
| Mercucys                 | 2        | 1.68%   |
| VIA Technologies         | 1        | 0.84%   |
| Ralink Technology        | 1        | 0.84%   |
| Qualcomm Atheros         | 1        | 0.84%   |
| MediaTek                 | 1        | 0.84%   |
| Marvell Technology Group | 1        | 0.84%   |
| Edimax Technology        | 1        | 0.84%   |
| ASIX Electronics         | 1        | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66       | 50.77%  |
| Intel Ethernet Connection (14) I219-V                             | 6        | 4.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 3.85%   |
| Intel Ethernet Controller I225-V                                  | 5        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 3.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 3.08%   |
| Nvidia MCP61 Ethernet                                             | 3        | 2.31%   |
| Mercucys 802.11n NIC                                              | 2        | 1.54%   |
| Intel Wireless 7265                                               | 2        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.54%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.77%   |
| TP-Link USB 10/100 LAN                                            | 1        | 0.77%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.77%   |
| Realtek 802.11ac NIC                                              | 1        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.77%   |
| MediaTek File-CD Gadget                                           | 1        | 0.77%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.77%   |
| Intel Wireless 3165                                               | 1        | 0.77%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.77%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.77%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.77%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 0.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.77%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                              | 1        | 0.77%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.77%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 0.77%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 45.83%  |
| Intel                 | 6        | 25%     |
| Mercucys              | 2        | 8.33%   |
| Broadcom              | 2        | 8.33%   |
| TP-Link               | 1        | 4.17%   |
| Ralink Technology     | 1        | 4.17%   |
| Edimax Technology     | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 4        | 16.67%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 4        | 16.67%  |
| Mercucys 802.11n NIC                                     | 2        | 8.33%   |
| Intel Wireless 7265                                      | 2        | 8.33%   |
| Intel Tiger Lake PCH CNVi WiFi                           | 2        | 8.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                      | 1        | 4.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter          | 1        | 4.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                   | 1        | 4.17%   |
| Realtek 802.11ac NIC                                     | 1        | 4.17%   |
| Ralink MT7601U Wireless Adapter                          | 1        | 4.17%   |
| Intel Wireless 3165                                      | 1        | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]         | 1        | 4.17%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                     | 1        | 4.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter       | 1        | 4.17%   |
| Broadcom BCM43228 802.11a/b/g/n                          | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 70       | 67.96%  |
| Intel                    | 21       | 20.39%  |
| Nvidia                   | 3        | 2.91%   |
| Samsung Electronics      | 2        | 1.94%   |
| VIA Technologies         | 1        | 0.97%   |
| TP-Link                  | 1        | 0.97%   |
| Qualcomm Atheros         | 1        | 0.97%   |
| MediaTek                 | 1        | 0.97%   |
| Marvell Technology Group | 1        | 0.97%   |
| Broadcom                 | 1        | 0.97%   |
| ASIX Electronics         | 1        | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66       | 62.26%  |
| Intel Ethernet Connection (14) I219-V                             | 6        | 5.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 4.72%   |
| Intel Ethernet Controller I225-V                                  | 5        | 4.72%   |
| Nvidia MCP61 Ethernet                                             | 3        | 2.83%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.89%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.94%   |
| TP-Link USB 10/100 LAN                                            | 1        | 0.94%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.94%   |
| MediaTek File-CD Gadget                                           | 1        | 0.94%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.94%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.94%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.94%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.94%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.94%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 80%     |
| WiFi     | 24       | 20%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 92       | 93.88%  |
| WiFi     | 6        | 6.12%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 77       | 79.38%  |
| 2     | 20       | 20.62%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 96       | 98.97%  |
| Yes  | 1        | 1.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Realtek Semiconductor   | 6        | 33.33%  |
| Intel                   | 6        | 33.33%  |
| Cambridge Silicon Radio | 2        | 11.11%  |
| Broadcom                | 2        | 11.11%  |
| TP-Link                 | 1        | 5.56%   |
| ASUSTek Computer        | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 6        | 33.33%  |
| Intel Bluetooth wireless interface                  | 3        | 16.67%  |
| Intel Bluetooth Device                              | 2        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 11.11%  |
| TP-Link TPuLink UB500 Adapter                       | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.56%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 5.56%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 5.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 79       | 65.83%  |
| AMD                 | 21       | 17.5%   |
| Nvidia              | 13       | 10.83%  |
| C-Media Electronics | 3        | 2.5%    |
| Texas Instruments   | 2        | 1.67%   |
| Razer USA           | 1        | 0.83%   |
| Creative Technology | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Audio device                                                         | 21       | 15.44%  |
| Intel 200 Series PCH HD Audio                                              | 12       | 8.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 6.62%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 6.62%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 4.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 3.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 2.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.94%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 2.21%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 2.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.21%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.21%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.47%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.47%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.74%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.74%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.74%   |
| Creative Technology Sound Blaster Play! 3                                  | 1        | 0.74%   |
| C-Media Electronics USB PnP Sound Device                                   | 1        | 0.74%   |
| C-Media Electronics USB Audio Device                                       | 1        | 0.74%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 19       | 19%     |
| Kingston            | 14       | 14%     |
| Unknown             | 13       | 13%     |
| Foxline             | 9        | 9%      |
| Samsung Electronics | 7        | 7%      |
| AMD                 | 6        | 6%      |
| SK hynix            | 5        | 5%      |
| Patriot             | 5        | 5%      |
| Apacer              | 4        | 4%      |
| Unknown             | 4        | 4%      |
| Neo Forza           | 2        | 2%      |
| Elpida              | 2        | 2%      |
| Corsair             | 2        | 2%      |
| A-DATA Technology   | 2        | 2%      |
| Unknown (ABCD)      | 1        | 1%      |
| Unknown (89F7)      | 1        | 1%      |
| Qumo                | 1        | 1%      |
| Good Wealth         | 1        | 1%      |
| Golden Empire       | 1        | 1%      |
| ChangXin Memory     | 1        | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s            | 5        | 4.85%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s          | 4        | 3.88%   |
| Unknown                                                      | 4        | 3.88%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                  | 3        | 2.91%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 2        | 1.94%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s          | 2        | 1.94%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s              | 2        | 1.94%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s        | 2        | 1.94%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2        | 1.94%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s        | 2        | 1.94%   |
| Crucial RAM CT8G4SFRA32A.C16FG 8GB SODIMM DDR4 3200MT/s      | 2        | 1.94%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s         | 2        | 1.94%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s       | 2        | 1.94%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                    | 1        | 0.97%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 0.97%   |
| Unknown RAM Module 4GB DIMM DDR 1066MT/s                     | 1        | 0.97%   |
| Unknown RAM Module 4GB DIMM 800MT/s                          | 1        | 0.97%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.97%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 0.97%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1        | 0.97%   |
| Unknown RAM Module 2GB DIMM 400MT/s                          | 1        | 0.97%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.97%   |
| Unknown RAM Module 1GB DIMM SDRAM 1066MT/s                   | 1        | 0.97%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 0.97%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 0.97%   |
| Unknown (89F7) RAM Module 8192MB DIMM DDR4 2667MT/s          | 1        | 0.97%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 0.97%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.97%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.97%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s         | 1        | 0.97%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s         | 1        | 0.97%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                    | 1        | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1        | 0.97%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s          | 1        | 0.97%   |
| Samsung RAM M378B5273DH0 4GB DIMM DDR3 1333MT/s              | 1        | 0.97%   |
| Qumo RAM QUM4U-4G2133KK15 4GB DIMM DDR4 2133MT/s             | 1        | 0.97%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s              | 1        | 0.97%   |
| Patriot RAM PSD416G320081 16GB DIMM DDR4 3200MT/s            | 1        | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 71       | 75.53%  |
| DDR3    | 10       | 10.64%  |
| Unknown | 5        | 5.32%   |
| SDRAM   | 4        | 4.26%   |
| DDR2    | 2        | 2.13%   |
| LPDDR4  | 1        | 1.06%   |
| DDR     | 1        | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 78       | 82.98%  |
| SODIMM | 16       | 17.02%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 57       | 56.44%  |
| 4096  | 21       | 20.79%  |
| 16384 | 8        | 7.92%   |
| 2048  | 8        | 7.92%   |
| 1024  | 4        | 3.96%   |
| 32768 | 3        | 2.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 28       | 28.28%  |
| 3200    | 20       | 20.2%   |
| 1333    | 9        | 9.09%   |
| 2400    | 6        | 6.06%   |
| 2133    | 5        | 5.05%   |
| 2666    | 4        | 4.04%   |
| 1600    | 4        | 4.04%   |
| 2934    | 2        | 2.02%   |
| 2933    | 2        | 2.02%   |
| 2800    | 2        | 2.02%   |
| 1066    | 2        | 2.02%   |
| 800     | 2        | 2.02%   |
| Unknown | 2        | 2.02%   |
| 3533    | 1        | 1.01%   |
| 3466    | 1        | 1.01%   |
| 3400    | 1        | 1.01%   |
| 3266    | 1        | 1.01%   |
| 3000    | 1        | 1.01%   |
| 2866    | 1        | 1.01%   |
| 2733    | 1        | 1.01%   |
| 1800    | 1        | 1.01%   |
| 667     | 1        | 1.01%   |
| 400     | 1        | 1.01%   |
| 333     | 1        | 1.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Pantum | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Pantum BM5100ADN series | 1        | 100%    |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SunplusIT             | 5        | 23.81%  |
| Alcor Micro           | 4        | 19.05%  |
| Realtek Semiconductor | 3        | 14.29%  |
| Logitech              | 3        | 14.29%  |
| Microdia              | 1        | 4.76%   |
| Creative Technology   | 1        | 4.76%   |
| Chicony Electronics   | 1        | 4.76%   |
| Arkmicro Technologies | 1        | 4.76%   |
| Apple                 | 1        | 4.76%   |
| AlcorMicroCorp        | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| SunplusIT USB Camera                  | 5        | 23.81%  |
| Alcor Micro USB 2.0 PC Camera         | 4        | 19.05%  |
| Logitech HD Webcam C615               | 3        | 14.29%  |
| Realtek 1080p Camera                  | 2        | 9.52%   |
| Realtek USB Camera                    | 1        | 4.76%   |
| Microdia Camera                       | 1        | 4.76%   |
| Creative VF0530 Live! Cam Chat IM     | 1        | 4.76%   |
| Chicony HP High Definition 1MP Webcam | 1        | 4.76%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 4.76%   |
| Apple iPhone 5/5C/5S/6/SE             | 1        | 4.76%   |
| AlcorMicroCorp SHUNCCM                | 1        | 4.76%   |

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
| Aladdin R.D. | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Aladdin R.D. JaCarta | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 76       | 76.77%  |
| 1     | 20       | 20.2%   |
| 4     | 1        | 1.01%   |
| 3     | 1        | 1.01%   |
| 2     | 1        | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 68.97%  |
| Communication controller | 3        | 10.34%  |
| Net/wireless             | 2        | 6.9%    |
| Sound                    | 1        | 3.45%   |
| Network                  | 1        | 3.45%   |
| Net/ethernet             | 1        | 3.45%   |
| Chipcard                 | 1        | 3.45%   |

