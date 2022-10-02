Linux in Indonesia - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 334

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 198E                        | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| ECS           | A55F2-M4                    | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| Gigabyte      | H81M-S2PV                   | [e1b3cac9d8](https://linux-hardware.org/?probe=e1b3cac9d8) | Sep 07, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Gigabyte      | H170-D3H-CF                 | [75a6e1e9a1](https://linux-hardware.org/?probe=75a6e1e9a1) | Aug 29, 2022 |
| Intel         | H61                         | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| ECS           | H61H2-MV                    | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [903fda443e](https://linux-hardware.org/?probe=903fda443e) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ECS           | H61H2-MV                    | [21fadb20ca](https://linux-hardware.org/?probe=21fadb20ca) | Aug 09, 2022 |
| ECS           | H61H2-MV                    | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| ECS           | H61H2-MV                    | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| Unknown       | Unknown                     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| Gigabyte      | B365M H                     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| MSI           | 2A9C                        | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASUSTek       | H110M-A/DP                  | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Biostar       | A68N-5600E                  | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| ASUSTek       | P5GC-MX/1333                | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| MSI           | 2A9C                        | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| Wearnes       | T1550-A1                    | [b131cd7e0d](https://linux-hardware.org/?probe=b131cd7e0d) | Jun 16, 2022 |
| Wearnes       | T1550-A1                    | [002ebf8c70](https://linux-hardware.org/?probe=002ebf8c70) | Jun 15, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| ASRock        | A88M-G                      | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASRock        | A88M-G                      | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| Unknown       | Unknown                     | [19345cd924](https://linux-hardware.org/?probe=19345cd924) | May 10, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | H55M-P33                    | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Unknown       | Unknown                     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| HP            | 3641h                       | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Koloe         | X58                         | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Intel         | H55                         | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| ZYREX COMP... | TACTICAL                    | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| MSI           | 2A9C                        | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| Dell          | 02YYK5 A01                  | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [3b3c38ec7d](https://linux-hardware.org/?probe=3b3c38ec7d) | Feb 24, 2022 |
| Acer          | Aspire M3970                | [ba6546f689](https://linux-hardware.org/?probe=ba6546f689) | Feb 24, 2022 |
| Intel         | X79G V2.x                   | [cdc3afd163](https://linux-hardware.org/?probe=cdc3afd163) | Feb 24, 2022 |
| Dell          | 0GM819                      | [28011d003e](https://linux-hardware.org/?probe=28011d003e) | Feb 23, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Dell          | 0VRWRC A00                  | [1e54431036](https://linux-hardware.org/?probe=1e54431036) | Feb 15, 2022 |
| ECS           | A58F2P-M4                   | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Dell          | 0Y7WYT A00                  | [3a6bb92957](https://linux-hardware.org/?probe=3a6bb92957) | Feb 13, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [276233dff5](https://linux-hardware.org/?probe=276233dff5) | Feb 11, 2022 |
| Biostar       | A68MHE                      | [d66f9ea911](https://linux-hardware.org/?probe=d66f9ea911) | Feb 10, 2022 |
| Biostar       | A68MHE                      | [edc710a49e](https://linux-hardware.org/?probe=edc710a49e) | Feb 10, 2022 |
| Biostar       | H81MHV3                     | [897c4f4fa5](https://linux-hardware.org/?probe=897c4f4fa5) | Jan 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [af3d4f8c4d](https://linux-hardware.org/?probe=af3d4f8c4d) | Jan 02, 2022 |
| ASUSTek       | Z97-C                       | [2956508483](https://linux-hardware.org/?probe=2956508483) | Dec 31, 2021 |
| ECS           | H61H2-MV                    | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| Foxconn       | 17A0                        | [f3b593c1cf](https://linux-hardware.org/?probe=f3b593c1cf) | Dec 04, 2021 |
| Foxconn       | 17A0                        | [9683f8f23c](https://linux-hardware.org/?probe=9683f8f23c) | Nov 29, 2021 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [f5f0997eca](https://linux-hardware.org/?probe=f5f0997eca) | Nov 28, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [6d67037961](https://linux-hardware.org/?probe=6d67037961) | Nov 16, 2021 |
| Foxconn       | 17A0                        | [ed1128211e](https://linux-hardware.org/?probe=ed1128211e) | Nov 14, 2021 |
| Foxconn       | 17A0                        | [17ff85bc35](https://linux-hardware.org/?probe=17ff85bc35) | Nov 09, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| ASUSTek       | PRIME H310M-K               | [a6cafee332](https://linux-hardware.org/?probe=a6cafee332) | Nov 02, 2021 |
| MSI           | B350M MORTAR                | [bab0e06723](https://linux-hardware.org/?probe=bab0e06723) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | [4fa9117126](https://linux-hardware.org/?probe=4fa9117126) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | [e4fc3665f7](https://linux-hardware.org/?probe=e4fc3665f7) | Oct 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [93b56b7543](https://linux-hardware.org/?probe=93b56b7543) | Oct 29, 2021 |
| MSI           | B350M MORTAR                | [e94404d654](https://linux-hardware.org/?probe=e94404d654) | Oct 26, 2021 |
| Pegatron      | 2AD4                        | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| Gigabyte      | EP45-UD3R                   | [ee1862fa4f](https://linux-hardware.org/?probe=ee1862fa4f) | Oct 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [9d1380f4a8](https://linux-hardware.org/?probe=9d1380f4a8) | Oct 15, 2021 |
| Dell          | 0773VG A01                  | [84fc704eaa](https://linux-hardware.org/?probe=84fc704eaa) | Oct 09, 2021 |
| Lenovo        | H310                        | [ce491df5a4](https://linux-hardware.org/?probe=ce491df5a4) | Oct 06, 2021 |
| ASRock        | AB350 Pro4                  | [4038d4a0a6](https://linux-hardware.org/?probe=4038d4a0a6) | Sep 29, 2021 |
| ASRock        | AB350 Pro4                  | [5854a1e114](https://linux-hardware.org/?probe=5854a1e114) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| ASUSTek       | PRIME H510M-D               | [f8fd88bca1](https://linux-hardware.org/?probe=f8fd88bca1) | Sep 26, 2021 |
| ASRock        | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Foxconn       | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| Gigabyte      | P31-ES3G                    | [5d60817fb5](https://linux-hardware.org/?probe=5d60817fb5) | Sep 11, 2021 |
| Dell          | 0T10XW A00                  | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| ASUSTek       | H61M-K                      | [541ab60180](https://linux-hardware.org/?probe=541ab60180) | Sep 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [9ab0b9612a](https://linux-hardware.org/?probe=9ab0b9612a) | Aug 30, 2021 |
| ASUSTek       | Z97-C                       | [924e556648](https://linux-hardware.org/?probe=924e556648) | Aug 28, 2021 |
| ASRock        | X300M-STX                   | [246709cb9b](https://linux-hardware.org/?probe=246709cb9b) | Aug 27, 2021 |
| ASUSTek       | H81M-C                      | [83393788bf](https://linux-hardware.org/?probe=83393788bf) | Aug 26, 2021 |
| Gigabyte      | EP45-DS3                    | [a2a6e3ee32](https://linux-hardware.org/?probe=a2a6e3ee32) | Aug 24, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [781fc26452](https://linux-hardware.org/?probe=781fc26452) | Aug 23, 2021 |
| ECS           | A960M-MV                    | [684f50eff8](https://linux-hardware.org/?probe=684f50eff8) | Aug 18, 2021 |
| HP            | 2B3C                        | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2aa00ea596](https://linux-hardware.org/?probe=2aa00ea596) | Aug 15, 2021 |
| ASRock        | AB350 Pro4                  | [2da83ae7b5](https://linux-hardware.org/?probe=2da83ae7b5) | Aug 12, 2021 |
| ASRock        | B450 Pro4                   | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [b4a1e99fc0](https://linux-hardware.org/?probe=b4a1e99fc0) | Jul 28, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [cc1c71078c](https://linux-hardware.org/?probe=cc1c71078c) | Jul 28, 2021 |
| ASRock        | A320M-HDV                   | [20dc9f0df4](https://linux-hardware.org/?probe=20dc9f0df4) | Jul 27, 2021 |
| ASUSTek       | P5G41T-M LX3                | [85fddcd068](https://linux-hardware.org/?probe=85fddcd068) | Jul 26, 2021 |
| Acer          | Veriton L4630G V:1.0        | [c486fbf03f](https://linux-hardware.org/?probe=c486fbf03f) | Jul 25, 2021 |
| Gigabyte      | B460M DS3H                  | [c989b48f08](https://linux-hardware.org/?probe=c989b48f08) | Jul 24, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Gigabyte      | H61M-DS2                    | [fec68f6675](https://linux-hardware.org/?probe=fec68f6675) | Jul 23, 2021 |
| ECS           | G41T-M12                    | [bc6dbc46b6](https://linux-hardware.org/?probe=bc6dbc46b6) | Jul 23, 2021 |
| Biostar       | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek       | H110M-E/M.2                 | [7f0ce9114c](https://linux-hardware.org/?probe=7f0ce9114c) | Jul 21, 2021 |
| Dell          | 0YXT71 A03                  | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | [533da05156](https://linux-hardware.org/?probe=533da05156) | Jul 12, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9765ba93ab](https://linux-hardware.org/?probe=9765ba93ab) | Jul 10, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [064817cd28](https://linux-hardware.org/?probe=064817cd28) | Jul 05, 2021 |
| MSI           | 870A-G54                    | [b1b8e74ea3](https://linux-hardware.org/?probe=b1b8e74ea3) | Jun 16, 2021 |
| Biostar       | TA870+                      | [c86568a140](https://linux-hardware.org/?probe=c86568a140) | Jun 09, 2021 |
| Lenovo        | SHARKBAY NOK                | [a3cef73da9](https://linux-hardware.org/?probe=a3cef73da9) | Jun 09, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | [414008f0a3](https://linux-hardware.org/?probe=414008f0a3) | Jun 08, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | [744392b18f](https://linux-hardware.org/?probe=744392b18f) | Jun 08, 2021 |
| MSI           | Z97-G43 GAMING              | [0a074f7196](https://linux-hardware.org/?probe=0a074f7196) | Jun 02, 2021 |
| HP            | 1906                        | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| ECS           | G41T-M12                    | [086ce490f7](https://linux-hardware.org/?probe=086ce490f7) | May 29, 2021 |
| ECS           | A55F2-M4                    | [b08197df02](https://linux-hardware.org/?probe=b08197df02) | May 29, 2021 |
| Gigabyte      | P85-D3                      | [a85613d8a6](https://linux-hardware.org/?probe=a85613d8a6) | May 24, 2021 |
| ECS           | H61H2-M2                    | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| Dell          | 0GDG8Y A00                  | [c75161deac](https://linux-hardware.org/?probe=c75161deac) | May 20, 2021 |
| Gigabyte      | B450M DS3H V2               | [8f39af876c](https://linux-hardware.org/?probe=8f39af876c) | May 19, 2021 |
| ASRock        | H81M-VG4 R2.0               | [80070c566e](https://linux-hardware.org/?probe=80070c566e) | May 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [f900105a8a](https://linux-hardware.org/?probe=f900105a8a) | May 09, 2021 |
| Acer          | Veriton M2611 v1.0          | [82b2ea1868](https://linux-hardware.org/?probe=82b2ea1868) | May 06, 2021 |
| Acer          | Veriton M2611 v1.0          | [218de62b27](https://linux-hardware.org/?probe=218de62b27) | May 06, 2021 |
| Unknown       | Unknown                     | [327d214403](https://linux-hardware.org/?probe=327d214403) | May 04, 2021 |
| Gigabyte      | H81M-DS2                    | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| ECS           | 945GCT-M2                   | [3f73514b16](https://linux-hardware.org/?probe=3f73514b16) | Apr 26, 2021 |
| ECS           | 945GCT-M2                   | [289b6cba53](https://linux-hardware.org/?probe=289b6cba53) | Apr 25, 2021 |
| MSI           | Z97-G43 GAMING              | [ca62d8f11b](https://linux-hardware.org/?probe=ca62d8f11b) | Apr 21, 2021 |
| MSI           | Z97-G43 GAMING              | [f71c55764e](https://linux-hardware.org/?probe=f71c55764e) | Apr 21, 2021 |
| Lenovo        | ThinkCentre A70 7099S3A     | [2fd4915fe8](https://linux-hardware.org/?probe=2fd4915fe8) | Apr 16, 2021 |
| ASRock        | B560M Pro4                  | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASRock        | B450 Pro4                   | [e83e7312c9](https://linux-hardware.org/?probe=e83e7312c9) | Apr 08, 2021 |
| MSI           | B85M GAMING                 | [bf0490433a](https://linux-hardware.org/?probe=bf0490433a) | Apr 07, 2021 |
| MSI           | B550-A PRO                  | [f7ddac6f83](https://linux-hardware.org/?probe=f7ddac6f83) | Apr 02, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [a5d5c057c0](https://linux-hardware.org/?probe=a5d5c057c0) | Mar 24, 2021 |
| MSI           | B460M PRO                   | [3a26303ce0](https://linux-hardware.org/?probe=3a26303ce0) | Mar 21, 2021 |
| MSI           | B460M PRO                   | [82bf6fd41b](https://linux-hardware.org/?probe=82bf6fd41b) | Mar 21, 2021 |
| ASRock        | B450 Pro4                   | [ed1a952ed3](https://linux-hardware.org/?probe=ed1a952ed3) | Mar 17, 2021 |
| Unknown       | Unknown                     | [b4b92701a0](https://linux-hardware.org/?probe=b4b92701a0) | Mar 05, 2021 |
| Biostar       | H61MGV3                     | [85e0a1cacc](https://linux-hardware.org/?probe=85e0a1cacc) | Mar 01, 2021 |
| ASUSTek       | H61M-K                      | [b59c5fdb8a](https://linux-hardware.org/?probe=b59c5fdb8a) | Feb 28, 2021 |
| ASRock        | FM2A68M-HD+                 | [95c5fe898a](https://linux-hardware.org/?probe=95c5fe898a) | Feb 27, 2021 |
| Lenovo        | Unknown                     | [0ca27a0ce2](https://linux-hardware.org/?probe=0ca27a0ce2) | Feb 24, 2021 |
| Gigabyte      | B460M DS3H                  | [fe95f7aef8](https://linux-hardware.org/?probe=fe95f7aef8) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | [b1edb9db86](https://linux-hardware.org/?probe=b1edb9db86) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | [abc0ef8bc7](https://linux-hardware.org/?probe=abc0ef8bc7) | Feb 19, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [502bc7eb2a](https://linux-hardware.org/?probe=502bc7eb2a) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | [8d369a84ce](https://linux-hardware.org/?probe=8d369a84ce) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | [95883e3fff](https://linux-hardware.org/?probe=95883e3fff) | Feb 04, 2021 |
| HP            | 834F                        | [c849bbc95a](https://linux-hardware.org/?probe=c849bbc95a) | Jan 14, 2021 |
| Lenovo        | 36EB SDK0Q55726 WIN 3273... | [ace52f974e](https://linux-hardware.org/?probe=ace52f974e) | Jan 13, 2021 |
| Gigabyte      | A320M-DS2-CF                | [414638f163](https://linux-hardware.org/?probe=414638f163) | Jan 07, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [9fe6d5b992](https://linux-hardware.org/?probe=9fe6d5b992) | Jan 02, 2021 |
| MSI           | G41M-P26                    | [8d7a10a828](https://linux-hardware.org/?probe=8d7a10a828) | Dec 31, 2020 |
| MSI           | 760GM-P23                   | [9ea9c09319](https://linux-hardware.org/?probe=9ea9c09319) | Dec 27, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [405b8ef206](https://linux-hardware.org/?probe=405b8ef206) | Dec 25, 2020 |
| MSI           | 870A-G54                    | [479ee62f9f](https://linux-hardware.org/?probe=479ee62f9f) | Dec 21, 2020 |
| HP            | 1497                        | [1bfa453ea4](https://linux-hardware.org/?probe=1bfa453ea4) | Dec 19, 2020 |
| HP            | 1497                        | [9b292e4071](https://linux-hardware.org/?probe=9b292e4071) | Dec 19, 2020 |
| MSI           | B360 GAMING PLUS            | [7a77cc7ec2](https://linux-hardware.org/?probe=7a77cc7ec2) | Dec 12, 2020 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [3e44b38d7f](https://linux-hardware.org/?probe=3e44b38d7f) | Dec 03, 2020 |
| ASRock        | H67M                        | [11ccd3281d](https://linux-hardware.org/?probe=11ccd3281d) | Nov 28, 2020 |
| Acer          | Aspire M3970                | [7350b05e56](https://linux-hardware.org/?probe=7350b05e56) | Nov 25, 2020 |
| Acer          | Aspire M3970                | [f380a566c2](https://linux-hardware.org/?probe=f380a566c2) | Nov 25, 2020 |
| Acer          | Veriton X4610G              | [e9ace7d042](https://linux-hardware.org/?probe=e9ace7d042) | Nov 24, 2020 |
| Dell          | 08HPGT A01                  | [d5ae57d261](https://linux-hardware.org/?probe=d5ae57d261) | Nov 20, 2020 |
| ASRock        | B450 Pro4                   | [f24f7ba17e](https://linux-hardware.org/?probe=f24f7ba17e) | Nov 13, 2020 |
| Dell          | 0GY6Y8 A00                  | [613e036e8d](https://linux-hardware.org/?probe=613e036e8d) | Nov 11, 2020 |
| MSI           | H410M PRO-VH                | [e5603638aa](https://linux-hardware.org/?probe=e5603638aa) | Nov 10, 2020 |
| MSI           | 870A-G54                    | [d14df17124](https://linux-hardware.org/?probe=d14df17124) | Nov 08, 2020 |
| HP            | 304Ah                       | [530cc628fb](https://linux-hardware.org/?probe=530cc628fb) | Nov 07, 2020 |
| HP            | 304Ah                       | [0ed06ad934](https://linux-hardware.org/?probe=0ed06ad934) | Nov 04, 2020 |
| Gigabyte      | H81M-Gaming 3               | [8d7b38dbf3](https://linux-hardware.org/?probe=8d7b38dbf3) | Nov 03, 2020 |
| Gigabyte      | H81M-Gaming 3               | [0c6140c86e](https://linux-hardware.org/?probe=0c6140c86e) | Nov 03, 2020 |
| MSI           | B85M GAMING                 | [b2b720adf7](https://linux-hardware.org/?probe=b2b720adf7) | Oct 28, 2020 |
| HP            | 1493                        | [cf9c3c195a](https://linux-hardware.org/?probe=cf9c3c195a) | Oct 24, 2020 |
| Quanta        | 2B03 110                    | [afa8ef9dda](https://linux-hardware.org/?probe=afa8ef9dda) | Oct 20, 2020 |
| ASRock        | X99 Taichi                  | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| Lenovo        | SKYBAY NOK                  | [f02492e188](https://linux-hardware.org/?probe=f02492e188) | Oct 08, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [805323645e](https://linux-hardware.org/?probe=805323645e) | Oct 04, 2020 |
| ASUSTek       | H110M-E/M.2                 | [e937cdfcbc](https://linux-hardware.org/?probe=e937cdfcbc) | Sep 28, 2020 |
| MSI           | B360 GAMING PLUS            | [6b3915fc77](https://linux-hardware.org/?probe=6b3915fc77) | Sep 28, 2020 |
| ASRock        | B365M Phantom Gaming 4      | [9f213e1442](https://linux-hardware.org/?probe=9f213e1442) | Sep 25, 2020 |
| Lenovo        | ThinkCentre M57p 9193A11    | [4d8a70073f](https://linux-hardware.org/?probe=4d8a70073f) | Sep 25, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [8be0a34480](https://linux-hardware.org/?probe=8be0a34480) | Sep 16, 2020 |
| Gigabyte      | H81M-S2PH                   | [b5438c62fc](https://linux-hardware.org/?probe=b5438c62fc) | Sep 16, 2020 |
| ECS           | Z97M-PK                     | [888e740324](https://linux-hardware.org/?probe=888e740324) | Sep 13, 2020 |
| MSI           | B360 GAMING PLUS            | [6c5d768e02](https://linux-hardware.org/?probe=6c5d768e02) | Sep 10, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [c363153de4](https://linux-hardware.org/?probe=c363153de4) | Sep 08, 2020 |
| MSI           | B350M MORTAR                | [ebcd809d62](https://linux-hardware.org/?probe=ebcd809d62) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6d06e18252](https://linux-hardware.org/?probe=6d06e18252) | Aug 30, 2020 |
| MSI           | B75MA-P33                   | [05483ed2c3](https://linux-hardware.org/?probe=05483ed2c3) | Aug 28, 2020 |
| MSI           | 870A-G54                    | [727980a18d](https://linux-hardware.org/?probe=727980a18d) | Aug 23, 2020 |
| SPECTRUM U... | VA 880G                     | [ef0b289382](https://linux-hardware.org/?probe=ef0b289382) | Aug 21, 2020 |
| ASRock        | A300M-STX                   | [0aeef3e18b](https://linux-hardware.org/?probe=0aeef3e18b) | Aug 19, 2020 |
| Lenovo        | SHARKBAY NOK                | [f205ba371e](https://linux-hardware.org/?probe=f205ba371e) | Aug 19, 2020 |
| MSI           | 870A-G54                    | [292a02f724](https://linux-hardware.org/?probe=292a02f724) | Aug 17, 2020 |
| Biostar       | H310MHC                     | [4331ff5e27](https://linux-hardware.org/?probe=4331ff5e27) | Aug 14, 2020 |
| Dell          | 0D28YY A01                  | [6740e51a94](https://linux-hardware.org/?probe=6740e51a94) | Aug 14, 2020 |
| NEC Comput... | MS-7264LW                   | [63f1552717](https://linux-hardware.org/?probe=63f1552717) | Aug 09, 2020 |
| NEC Comput... | MS-7264LW                   | [bc4eab7fa3](https://linux-hardware.org/?probe=bc4eab7fa3) | Aug 09, 2020 |
| MSI           | B85M GAMING                 | [984c0ed0a7](https://linux-hardware.org/?probe=984c0ed0a7) | Aug 07, 2020 |
| ASRock        | A320M-HDV R4.0              | [87a26416b1](https://linux-hardware.org/?probe=87a26416b1) | Aug 06, 2020 |
| MSI           | H81M-P33                    | [f9cb52c02a](https://linux-hardware.org/?probe=f9cb52c02a) | Aug 05, 2020 |
| ASUSTek       | PRIME H410M-E               | [ecd5a9cdd0](https://linux-hardware.org/?probe=ecd5a9cdd0) | Aug 01, 2020 |
| ASUSTek       | PRIME H410M-E               | [f95e229d75](https://linux-hardware.org/?probe=f95e229d75) | Aug 01, 2020 |
| MSI           | B85M GAMING                 | [ca027f475e](https://linux-hardware.org/?probe=ca027f475e) | Jul 28, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [5a271f15c2](https://linux-hardware.org/?probe=5a271f15c2) | Jul 28, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [f34a4c062d](https://linux-hardware.org/?probe=f34a4c062d) | Jul 26, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [1d18d6d402](https://linux-hardware.org/?probe=1d18d6d402) | Jul 25, 2020 |
| MSI           | B85M GAMING                 | [29191c1b1e](https://linux-hardware.org/?probe=29191c1b1e) | Jul 24, 2020 |
| OEM           | G41 775 ICH7 8712           | [bdbd588c54](https://linux-hardware.org/?probe=bdbd588c54) | Jul 24, 2020 |
| MSI           | 870A-G54                    | [74d1532bd8](https://linux-hardware.org/?probe=74d1532bd8) | Jul 15, 2020 |
| MSI           | 870A-G54                    | [9110e601b2](https://linux-hardware.org/?probe=9110e601b2) | Jul 15, 2020 |
| MSI           | 870A-G54                    | [ce919dba00](https://linux-hardware.org/?probe=ce919dba00) | Jul 09, 2020 |
| Intel         | Unknown                     | [9224b78dd5](https://linux-hardware.org/?probe=9224b78dd5) | Jul 07, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [21af10b11c](https://linux-hardware.org/?probe=21af10b11c) | Jul 03, 2020 |
| Nvidia        | NF-MCP68                    | [6b42b5244e](https://linux-hardware.org/?probe=6b42b5244e) | Jun 23, 2020 |
| Unknown       | G41 Series                  | [5f2347032e](https://linux-hardware.org/?probe=5f2347032e) | Jun 16, 2020 |
| MSI           | 870A-G54                    | [4c34d33e03](https://linux-hardware.org/?probe=4c34d33e03) | Jun 15, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [5bb6af2e45](https://linux-hardware.org/?probe=5bb6af2e45) | Jun 14, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [c06f108477](https://linux-hardware.org/?probe=c06f108477) | Jun 14, 2020 |
| MSI           | 870A-G54                    | [8f14b79b6a](https://linux-hardware.org/?probe=8f14b79b6a) | Jun 14, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [ab1f7a9baa](https://linux-hardware.org/?probe=ab1f7a9baa) | Jun 11, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [e30aeca065](https://linux-hardware.org/?probe=e30aeca065) | Jun 11, 2020 |
| ASRock        | G41M-VS3                    | [8918ed5ee1](https://linux-hardware.org/?probe=8918ed5ee1) | May 29, 2020 |
| ASRock        | FM2A68M-DG3+                | [34ec73be33](https://linux-hardware.org/?probe=34ec73be33) | May 29, 2020 |
| ASRock        | FM2A68M-DG3+                | [f56d577ca6](https://linux-hardware.org/?probe=f56d577ca6) | May 29, 2020 |
| Gigabyte      | EP45-DS3LR                  | [1aa541af52](https://linux-hardware.org/?probe=1aa541af52) | May 29, 2020 |
| ECS           | P43G                        | [61bbe10085](https://linux-hardware.org/?probe=61bbe10085) | May 28, 2020 |
| ECS           | P43G                        | [13a37c39ae](https://linux-hardware.org/?probe=13a37c39ae) | May 28, 2020 |
| MSI           | B85M GAMING                 | [ce4c6b31d7](https://linux-hardware.org/?probe=ce4c6b31d7) | May 24, 2020 |
| ASRock        | G41M-VS3                    | [b8573ae92c](https://linux-hardware.org/?probe=b8573ae92c) | May 23, 2020 |
| MSI           | B85M GAMING                 | [aba32f928c](https://linux-hardware.org/?probe=aba32f928c) | May 17, 2020 |
| Gigabyte      | H61M-DS2                    | [16bcd5ac39](https://linux-hardware.org/?probe=16bcd5ac39) | May 02, 2020 |
| MSI           | P55-CD53                    | [afb112f2e5](https://linux-hardware.org/?probe=afb112f2e5) | May 02, 2020 |
| Gigabyte      | H61M-DS2                    | [e16a4f321c](https://linux-hardware.org/?probe=e16a4f321c) | Apr 29, 2020 |
| MSI           | 970A-G45                    | [6ac0a4fa90](https://linux-hardware.org/?probe=6ac0a4fa90) | Apr 26, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [6adbd75b76](https://linux-hardware.org/?probe=6adbd75b76) | Apr 24, 2020 |
| Biostar       | H310MHC                     | [49ba466f80](https://linux-hardware.org/?probe=49ba466f80) | Apr 17, 2020 |
| Biostar       | H310MHC                     | [b7a62e3806](https://linux-hardware.org/?probe=b7a62e3806) | Apr 17, 2020 |
| ECS           | H61H2-M12                   | [ae9b0e4fc7](https://linux-hardware.org/?probe=ae9b0e4fc7) | Apr 15, 2020 |
| ECS           | H61H2-M12                   | [de706540bb](https://linux-hardware.org/?probe=de706540bb) | Apr 15, 2020 |
| ECS           | H61H2-M12                   | [e7b1567091](https://linux-hardware.org/?probe=e7b1567091) | Apr 15, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS            | [de7c9abd9e](https://linux-hardware.org/?probe=de7c9abd9e) | Apr 14, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS            | [39347abd01](https://linux-hardware.org/?probe=39347abd01) | Apr 07, 2020 |
| Inventec      | DQ Class A02                | [8b47d0dec9](https://linux-hardware.org/?probe=8b47d0dec9) | Apr 07, 2020 |
| Inventec      | DQ Class A02                | [de75fa5904](https://linux-hardware.org/?probe=de75fa5904) | Apr 06, 2020 |
| ASRock        | X570 Steel Legend           | [9ebe70290a](https://linux-hardware.org/?probe=9ebe70290a) | Apr 05, 2020 |
| Biostar       | X370GT3                     | [1eba7843c7](https://linux-hardware.org/?probe=1eba7843c7) | Apr 03, 2020 |
| Biostar       | X370GT3                     | [4a91b87778](https://linux-hardware.org/?probe=4a91b87778) | Apr 03, 2020 |
| Dell          | 07C0H8 A00                  | [6863933279](https://linux-hardware.org/?probe=6863933279) | Mar 18, 2020 |
| ASUSTek       | CG8580                      | [a2755006be](https://linux-hardware.org/?probe=a2755006be) | Feb 22, 2020 |
| ASUSTek       | CG8580                      | [ca764ea79e](https://linux-hardware.org/?probe=ca764ea79e) | Feb 22, 2020 |
| ASUSTek       | H81M-E                      | [d4fc5bee1a](https://linux-hardware.org/?probe=d4fc5bee1a) | Feb 21, 2020 |
| ASUSTek       | H81M-E                      | [ee2cf3834b](https://linux-hardware.org/?probe=ee2cf3834b) | Feb 21, 2020 |
| ASUSTek       | H97M-E                      | [583ff222dc](https://linux-hardware.org/?probe=583ff222dc) | Feb 20, 2020 |
| Intel         | Unknown                     | [ed1af52d9b](https://linux-hardware.org/?probe=ed1af52d9b) | Feb 14, 2020 |
| Dell          | 09KPNV A00                  | [a242b5b90b](https://linux-hardware.org/?probe=a242b5b90b) | Feb 07, 2020 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [ef5e60b804](https://linux-hardware.org/?probe=ef5e60b804) | Feb 06, 2020 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [e2ad5e1470](https://linux-hardware.org/?probe=e2ad5e1470) | Feb 06, 2020 |
| Biostar       | B45M2                       | [d5e8a2ad7a](https://linux-hardware.org/?probe=d5e8a2ad7a) | Jan 18, 2020 |
| Biostar       | B45M2                       | [8fde9c57e5](https://linux-hardware.org/?probe=8fde9c57e5) | Jan 18, 2020 |
| MSI           | 2A78h                       | [275a99a2fe](https://linux-hardware.org/?probe=275a99a2fe) | Jan 06, 2020 |
| Intel         | DG31PR AAD97573-306         | [7f477da95d](https://linux-hardware.org/?probe=7f477da95d) | Dec 12, 2019 |
| Biostar       | H310MHC                     | [a2ad758a5a](https://linux-hardware.org/?probe=a2ad758a5a) | Oct 29, 2019 |
| Biostar       | H310MHC                     | [3b6265a2aa](https://linux-hardware.org/?probe=3b6265a2aa) | Oct 29, 2019 |
| Dell          | 0T656F A01                  | [7a0f0d92a8](https://linux-hardware.org/?probe=7a0f0d92a8) | Oct 18, 2019 |
| ECS           | A785GM-AD3                  | [69dee2c465](https://linux-hardware.org/?probe=69dee2c465) | Oct 10, 2019 |
| ASUSTek       | M4A785TD-V EVO              | [85e109926e](https://linux-hardware.org/?probe=85e109926e) | Sep 20, 2019 |
| Intel         | DX58SO AAE29331-703         | [8a2de6109c](https://linux-hardware.org/?probe=8a2de6109c) | Sep 17, 2019 |
| Intel         | DG31PR AAD97573-306         | [1b36a15fbc](https://linux-hardware.org/?probe=1b36a15fbc) | Sep 17, 2019 |
| Intel         | DX58SO AAE29331-703         | [bc3adc24d0](https://linux-hardware.org/?probe=bc3adc24d0) | Sep 12, 2019 |
| ASUSTek       | P5KPL-AM                    | [7da787439e](https://linux-hardware.org/?probe=7da787439e) | Sep 11, 2019 |
| Gigabyte      | H310M S2P                   | [6fffbe0439](https://linux-hardware.org/?probe=6fffbe0439) | Sep 02, 2019 |
| Intel         | D525MW AAE93082-400         | [89a1e0ba41](https://linux-hardware.org/?probe=89a1e0ba41) | Sep 01, 2019 |
| ASUSTek       | P5KPL-AM                    | [11025c5412](https://linux-hardware.org/?probe=11025c5412) | Aug 27, 2019 |
| MSI           | 0AB8                        | [1728939e55](https://linux-hardware.org/?probe=1728939e55) | Aug 22, 2019 |
| ASUSTek       | P5KPL-AM EPU                | [4272d3a201](https://linux-hardware.org/?probe=4272d3a201) | Aug 22, 2019 |
| ASRock        | A320M-HDV R4.0              | [cce7f9292d](https://linux-hardware.org/?probe=cce7f9292d) | Jul 23, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f664fb0c42](https://linux-hardware.org/?probe=f664fb0c42) | Jul 22, 2019 |
| MSI           | H110M PRO-VH PLUS           | [cdce9b48f0](https://linux-hardware.org/?probe=cdce9b48f0) | Jul 20, 2019 |
| Dell          | 02YRK5 A02                  | [18212fdd56](https://linux-hardware.org/?probe=18212fdd56) | Jul 11, 2019 |
| Dell          | 02YRK5 A02                  | [9fa1b2681a](https://linux-hardware.org/?probe=9fa1b2681a) | Jul 10, 2019 |
| Jetway        | TA55MG2-OC                  | [f2e67158f7](https://linux-hardware.org/?probe=f2e67158f7) | Jul 06, 2019 |
| Jetway        | TA55MG2-OC                  | [7ac413972b](https://linux-hardware.org/?probe=7ac413972b) | Jul 06, 2019 |
| Biostar       | R690A-M2T                   | [6c00967a8c](https://linux-hardware.org/?probe=6c00967a8c) | Jul 03, 2019 |
| ASRock        | H61M-VS3                    | [1192feeead](https://linux-hardware.org/?probe=1192feeead) | Jun 20, 2019 |
| HP            | 2B60 MVB                    | [931efec797](https://linux-hardware.org/?probe=931efec797) | Jun 11, 2019 |
| Biostar       | TB250-BTC PRO               | [56d589996a](https://linux-hardware.org/?probe=56d589996a) | May 23, 2019 |
| Biostar       | TB250-BTC PRO               | [41c5a400a2](https://linux-hardware.org/?probe=41c5a400a2) | May 23, 2019 |
| Biostar       | TB250-BTC PRO               | [e5699ad7bf](https://linux-hardware.org/?probe=e5699ad7bf) | May 23, 2019 |
| Biostar       | G31M+                       | [ee05f6ce67](https://linux-hardware.org/?probe=ee05f6ce67) | May 20, 2019 |
| Gigabyte      | H310M DS2                   | [229e72bc4f](https://linux-hardware.org/?probe=229e72bc4f) | May 20, 2019 |
| Lenovo        | MAHOBAY NOK                 | [2e7abfe281](https://linux-hardware.org/?probe=2e7abfe281) | May 18, 2019 |
| Dell          | 0WR7PY A02                  | [6e00c71124](https://linux-hardware.org/?probe=6e00c71124) | May 14, 2019 |
| ASUSTek       | P8H67-V                     | [f39c397507](https://linux-hardware.org/?probe=f39c397507) | May 09, 2019 |
| Intel         | Unknown                     | [a467374ecd](https://linux-hardware.org/?probe=a467374ecd) | Apr 25, 2019 |
| ASUSTek       | P5G41C-M LX                 | [e4433722a7](https://linux-hardware.org/?probe=e4433722a7) | Feb 24, 2019 |
| ASUSTek       | P5G41C-M LX                 | [7e4001ef6e](https://linux-hardware.org/?probe=7e4001ef6e) | Feb 24, 2019 |
| MSI           | 785GM-E51                   | [06046973d6](https://linux-hardware.org/?probe=06046973d6) | Jan 08, 2019 |
| ASRock        | Z77 Professional            | [8bc3d31d80](https://linux-hardware.org/?probe=8bc3d31d80) | Dec 03, 2018 |
| ASRock        | Z77 Professional            | [243ff79ac2](https://linux-hardware.org/?probe=243ff79ac2) | Nov 30, 2018 |
| Dell          | 0J3C2F A02                  | [3b377580ad](https://linux-hardware.org/?probe=3b377580ad) | Nov 07, 2018 |
| Dell          | 0J3C2F A02                  | [17cec4b4ca](https://linux-hardware.org/?probe=17cec4b4ca) | Nov 06, 2018 |
| Intel         | DG31PR AAD97573-306         | [cf36e3e24d](https://linux-hardware.org/?probe=cf36e3e24d) | Oct 20, 2018 |
| ASRock        | G41M-VS3                    | [7bb4fff693](https://linux-hardware.org/?probe=7bb4fff693) | Sep 25, 2018 |
| ASUSTek       | P5QPL-VM EPU                | [6c4195dd46](https://linux-hardware.org/?probe=6c4195dd46) | Jul 30, 2018 |
| ASUSTek       | F1A55-M LX PLUS             | [bd4bad9fd4](https://linux-hardware.org/?probe=bd4bad9fd4) | Apr 23, 2017 |
| ASUSTek       | P5KPL-AM SE                 | [5128fdeca3](https://linux-hardware.org/?probe=5128fdeca3) | Dec 07, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 40       | 16.19%  |
| Ubuntu 18.04                 | 31       | 12.55%  |
| OpenMandriva 4.3             | 14       | 5.67%   |
| Zorin 15                     | 10       | 4.05%   |
| OpenMandriva 4.2             | 8        | 3.24%   |
| KDE neon 20.04               | 7        | 2.83%   |
| Elementary 6.1               | 6        | 2.43%   |
| Linux Mint 19.3              | 5        | 2.02%   |
| Xubuntu 20.04                | 4        | 1.62%   |
| Pop!_OS 20.04                | 4        | 1.62%   |
| Fedora 35                    | 4        | 1.62%   |
| Fedora 33                    | 4        | 1.62%   |
| Fedora 32                    | 4        | 1.62%   |
| Arch                         | 4        | 1.62%   |
| Ubuntu Unity 20.04           | 3        | 1.21%   |
| Ubuntu 21.10                 | 3        | 1.21%   |
| Ubuntu 20.10                 | 3        | 1.21%   |
| OpenMandriva 4.50            | 3        | 1.21%   |
| Linux Mint 20.1              | 3        | 1.21%   |
| Linux Mint 20                | 3        | 1.21%   |
| Fedora 36                    | 3        | 1.21%   |
| Elementary 6                 | 3        | 1.21%   |
| ArcoLinux Rolling            | 3        | 1.21%   |
| Zorin 16                     | 2        | 0.81%   |
| Ubuntu 21.04                 | 2        | 0.81%   |
| Ubuntu 19.10                 | 2        | 0.81%   |
| Sparky 6.2                   | 2        | 0.81%   |
| ROSA R10                     | 2        | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.81%   |
| Linux Mint 20.3              | 2        | 0.81%   |
| Linux Mint 20.2              | 2        | 0.81%   |
| Fedora 34                    | 2        | 0.81%   |
| Endless 3.9.4                | 2        | 0.81%   |
| Debian 10                    | 2        | 0.81%   |
| CentOS 8                     | 2        | 0.81%   |
| Zorin 12                     | 1        | 0.4%    |
| Xubuntu 22.04                | 1        | 0.4%    |
| Xubuntu 16.04                | 1        | 0.4%    |
| UbuntuDDE 20.04              | 1        | 0.4%    |
| Ubuntu Unity 18.04           | 1        | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 84       | 35.15%  |
| OpenMandriva | 25       | 10.46%  |
| Linux Mint   | 16       | 6.69%   |
| Fedora       | 15       | 6.28%   |
| Zorin        | 13       | 5.44%   |
| Elementary   | 11       | 4.6%    |
| Endless      | 9        | 3.77%   |
| KDE neon     | 7        | 2.93%   |
| Xubuntu      | 6        | 2.51%   |
| Pop!_OS      | 6        | 2.51%   |
| Manjaro      | 6        | 2.51%   |
| Arch         | 5        | 2.09%   |
| ROSA         | 4        | 1.67%   |
| Ubuntu Unity | 3        | 1.26%   |
| Kali         | 3        | 1.26%   |
| Debian       | 3        | 1.26%   |
| Clear Linux  | 3        | 1.26%   |
| ArcoLinux    | 3        | 1.26%   |
| Sparky       | 2        | 0.84%   |
| openSUSE     | 2        | 0.84%   |
| MX           | 2        | 0.84%   |
| CentOS       | 2        | 0.84%   |
| UbuntuDDE    | 1        | 0.42%   |
| RHEL         | 1        | 0.42%   |
| Peux OS      | 1        | 0.42%   |
| Lubuntu      | 1        | 0.42%   |
| Lilidog      | 1        | 0.42%   |
| Kubuntu      | 1        | 0.42%   |
| Funtoo       | 1        | 0.42%   |
| Deepin       | 1        | 0.42%   |
| Alpine       | 1        | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 13       | 4.89%   |
| 5.4.0-42-generic         | 10       | 3.76%   |
| 5.4.0-52-generic         | 7        | 2.63%   |
| 5.4.0-26-generic         | 6        | 2.26%   |
| 5.4.0-58-generic         | 5        | 1.88%   |
| 5.10.14-desktop-1omv4002 | 5        | 1.88%   |
| 5.8.0-14-generic         | 4        | 1.5%    |
| 5.4.0-80-generic         | 4        | 1.5%    |
| 5.3.0-28-generic         | 4        | 1.5%    |
| 5.4.0-81-generic         | 3        | 1.13%   |
| 5.13.0-41-generic        | 3        | 1.13%   |
| 5.11.12-desktop-1omv4002 | 3        | 1.13%   |
| 5.11.0-43-generic        | 3        | 1.13%   |
| 5.8.0-53-generic         | 2        | 0.75%   |
| 5.8.0-45-generic         | 2        | 0.75%   |
| 5.4.0-77-generic         | 2        | 0.75%   |
| 5.4.0-7642-generic       | 2        | 0.75%   |
| 5.4.0-74-generic         | 2        | 0.75%   |
| 5.4.0-65-generic         | 2        | 0.75%   |
| 5.4.0-53-generic         | 2        | 0.75%   |
| 5.4.0-48-generic         | 2        | 0.75%   |
| 5.4.0-37-generic         | 2        | 0.75%   |
| 5.4.0-33-generic         | 2        | 0.75%   |
| 5.3.0-46-generic         | 2        | 0.75%   |
| 5.3.0-45-generic         | 2        | 0.75%   |
| 5.3.0-40-generic         | 2        | 0.75%   |
| 5.19.5-desktop-1omv4090  | 2        | 0.75%   |
| 5.13.0-40-generic        | 2        | 0.75%   |
| 5.13.0-35-generic        | 2        | 0.75%   |
| 5.11.0-40-generic        | 2        | 0.75%   |
| 5.11.0-37-generic        | 2        | 0.75%   |
| 5.11.0-34-generic        | 2        | 0.75%   |
| 5.11.0-27-generic        | 2        | 0.75%   |
| 5.0.0-32-generic         | 2        | 0.75%   |
| 5.0.0-31-generic         | 2        | 0.75%   |
| 5.0.0-27-generic         | 2        | 0.75%   |
| 5.0.0-25-generic         | 2        | 0.75%   |
| 4.18.0-25-generic        | 2        | 0.75%   |
| 4.18.0-20-generic        | 2        | 0.75%   |
| 4.18.0-15-generic        | 2        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 59       | 23.32%  |
| 5.8.0   | 16       | 6.32%   |
| 4.15.0  | 16       | 6.32%   |
| 5.11.0  | 15       | 5.93%   |
| 5.3.0   | 14       | 5.53%   |
| 5.16.7  | 14       | 5.53%   |
| 5.13.0  | 13       | 5.14%   |
| 4.18.0  | 13       | 5.14%   |
| 5.0.0   | 10       | 3.95%   |
| 5.15.0  | 5        | 1.98%   |
| 5.10.14 | 5        | 1.98%   |
| 5.10.0  | 5        | 1.98%   |
| 5.9.16  | 3        | 1.19%   |
| 5.14.0  | 3        | 1.19%   |
| 5.11.12 | 3        | 1.19%   |
| 5.8.12  | 2        | 0.79%   |
| 5.19.5  | 2        | 0.79%   |
| 5.17.5  | 2        | 0.79%   |
| 5.16.12 | 2        | 0.79%   |
| 5.13.4  | 2        | 0.79%   |
| 4.19.0  | 2        | 0.79%   |
| 5.8.6   | 1        | 0.4%    |
| 5.7.16  | 1        | 0.4%    |
| 5.7.15  | 1        | 0.4%    |
| 5.7.0   | 1        | 0.4%    |
| 5.6.6   | 1        | 0.4%    |
| 5.6.2   | 1        | 0.4%    |
| 5.6.0   | 1        | 0.4%    |
| 5.4.2   | 1        | 0.4%    |
| 5.2.11  | 1        | 0.4%    |
| 5.18.16 | 1        | 0.4%    |
| 5.18.10 | 1        | 0.4%    |
| 5.18.0  | 1        | 0.4%    |
| 5.17.4  | 1        | 0.4%    |
| 5.17.2  | 1        | 0.4%    |
| 5.17.0  | 1        | 0.4%    |
| 5.16.13 | 1        | 0.4%    |
| 5.15.32 | 1        | 0.4%    |
| 5.15.10 | 1        | 0.4%    |
| 5.14.18 | 1        | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 60       | 24%     |
| 5.10    | 21       | 8.4%    |
| 5.11    | 20       | 8%      |
| 5.8     | 19       | 7.6%    |
| 5.16    | 17       | 6.8%    |
| 5.13    | 16       | 6.4%    |
| 4.15    | 16       | 6.4%    |
| 5.3     | 14       | 5.6%    |
| 4.18    | 13       | 5.2%    |
| 5.0     | 10       | 4%      |
| 5.15    | 7        | 2.8%    |
| 5.14    | 5        | 2%      |
| 5.17    | 4        | 1.6%    |
| 5.12    | 4        | 1.6%    |
| 5.9     | 3        | 1.2%    |
| 5.7     | 3        | 1.2%    |
| 5.6     | 3        | 1.2%    |
| 5.18    | 3        | 1.2%    |
| 4.9     | 3        | 1.2%    |
| 5.19    | 2        | 0.8%    |
| 4.19    | 2        | 0.8%    |
| 5.2     | 1        | 0.4%    |
| 5.1     | 1        | 0.4%    |
| 4.4     | 1        | 0.4%    |
| 4.3     | 1        | 0.4%    |
| 4.17    | 1        | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 228      | 97.02%  |
| i686   | 7        | 2.98%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 101      | 42.08%  |
| KDE5              | 40       | 16.67%  |
| Unknown           | 39       | 16.25%  |
| XFCE              | 16       | 6.67%   |
| X-Cinnamon        | 10       | 4.17%   |
| Pantheon          | 10       | 4.17%   |
| Unity             | 3        | 1.25%   |
| MATE              | 3        | 1.25%   |
| Deepin            | 3        | 1.25%   |
| KDE4              | 2        | 0.83%   |
| KDE               | 2        | 0.83%   |
| Cinnamon          | 2        | 0.83%   |
| Yaru:ubuntu:GNOME | 1        | 0.42%   |
| Peux Gnome        | 1        | 0.42%   |
| lightdm-xsession  | 1        | 0.42%   |
| ICEWM             | 1        | 0.42%   |
| i3                | 1        | 0.42%   |
| GNOME Flashback   | 1        | 0.42%   |
| DWM               | 1        | 0.42%   |
| Cutefish          | 1        | 0.42%   |
| Bspwm             | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 185      | 77.73%  |
| Unknown | 27       | 11.34%  |
| Wayland | 24       | 10.08%  |
| Tty     | 2        | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 150      | 62.76%  |
| SDDM    | 38       | 15.9%   |
| GDM     | 25       | 10.46%  |
| LightDM | 11       | 4.6%    |
| GDM3    | 7        | 2.93%   |
| TDM     | 6        | 2.51%   |
| KDM     | 2        | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 177      | 74.37%  |
| Unknown | 34       | 14.29%  |
| id_ID   | 18       | 7.56%   |
| C       | 4        | 1.68%   |
| en_GB   | 2        | 0.84%   |
| it_IT   | 1        | 0.42%   |
| en_AG   | 1        | 0.42%   |
| Default | 1        | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 165      | 68.75%  |
| EFI  | 75       | 31.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 185      | 78.39%  |
| Overlay | 22       | 9.32%   |
| Btrfs   | 12       | 5.08%   |
| Unknown | 11       | 4.66%   |
| Xfs     | 5        | 2.12%   |
| Zfs     | 1        | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 156      | 66.1%   |
| GPT     | 45       | 19.07%  |
| MBR     | 35       | 14.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 207      | 87.34%  |
| Yes       | 30       | 12.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 58.16%  |
| Yes       | 100      | 41.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUSTek Computer       | 38       | 16.17%  |
| Gigabyte Technology    | 33       | 14.04%  |
| MSI                    | 28       | 11.91%  |
| ASRock                 | 28       | 11.91%  |
| Dell                   | 17       | 7.23%   |
| Biostar                | 17       | 7.23%   |
| ECS                    | 16       | 6.81%   |
| Lenovo                 | 14       | 5.96%   |
| Hewlett-Packard        | 10       | 4.26%   |
| Intel                  | 9        | 3.83%   |
| Acer                   | 5        | 2.13%   |
| Unknown                | 3        | 1.28%   |
| Pegatron               | 2        | 0.85%   |
| LORD ELECTRONICS       | 2        | 0.85%   |
| Foxconn                | 2        | 0.85%   |
| ZYREX COMPUTER SYSTEMS | 1        | 0.43%   |
| Wearnes                | 1        | 0.43%   |
| SPECTRUM UTAMA         | 1        | 0.43%   |
| Quanta                 | 1        | 0.43%   |
| OEM                    | 1        | 0.43%   |
| Nvidia                 | 1        | 0.43%   |
| NEC Computers          | 1        | 0.43%   |
| Koloe                  | 1        | 0.43%   |
| Jetway                 | 1        | 0.43%   |
| Inventec               | 1        | 0.43%   |
| Colorful Technology    | 1        | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 6        | 2.55%   |
| ASUS All Series                                   | 5        | 2.13%   |
| Dell OptiPlex 7010                                | 4        | 1.7%    |
| ECS H61H2-MV                                      | 3        | 1.28%   |
| ASUS P5KPL-AM SE                                  | 3        | 1.28%   |
| ASRock B450 Pro4                                  | 3        | 1.28%   |
| MSI MS-7B22                                       | 2        | 0.85%   |
| MSI MS-7A37                                       | 2        | 0.85%   |
| MSI MS-7823                                       | 2        | 0.85%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 2        | 0.85%   |
| Intel H61                                         | 2        | 0.85%   |
| Gigabyte H61M-DS2                                 | 2        | 0.85%   |
| Gigabyte GA-78LMT-USB3 6.0                        | 2        | 0.85%   |
| Gigabyte B460MDS3H                                | 2        | 0.85%   |
| Foxconn Pro 3330 MT                               | 2        | 0.85%   |
| ECS G41T-M12                                      | 2        | 0.85%   |
| ECS A55F2-M4                                      | 2        | 0.85%   |
| Dell OptiPlex 790                                 | 2        | 0.85%   |
| Biostar H310MHC                                   | 2        | 0.85%   |
| ASUS P5GC-MX/1333                                 | 2        | 0.85%   |
| ASUS H61M-K                                       | 2        | 0.85%   |
| ASUS H110M-E/M.2                                  | 2        | 0.85%   |
| ASRock G41M-VS3                                   | 2        | 0.85%   |
| ASRock FM2A68M-DG3+                               | 2        | 0.85%   |
| ASRock AB350 Pro4                                 | 2        | 0.85%   |
| ASRock A88M-G                                     | 2        | 0.85%   |
| ASRock A320M-HDV R4.0                             | 2        | 0.85%   |
| ASRock A320M-HDV                                  | 2        | 0.85%   |
| Acer Aspire M3970                                 | 2        | 0.85%   |
| ZYREX COMPUTER SYSTEMS TACTICAL                   | 1        | 0.43%   |
| Wearnes POS T-1550                                | 1        | 0.43%   |
| SPECTRUM UTAMA VA 880G                            | 1        | 0.43%   |
| Quanta 20-a200l                                   | 1        | 0.43%   |
| Pegatron p2-1110l                                 | 1        | 0.43%   |
| Pegatron IPMSB-VH1/HDMI/ODM                       | 1        | 0.43%   |
| OEM G41 775 ICH7 8712                             | 1        | 0.43%   |
| Nvidia NF-MCP68                                   | 1        | 0.43%   |
| NEC Computers PC-MY26XEZE1                        | 1        | 0.43%   |
| MSI MS-7D43                                       | 1        | 0.43%   |
| MSI MS-7C96                                       | 1        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Dell OptiPlex                   | 12       | 5.11%   |
| Lenovo ThinkCentre              | 9        | 3.83%   |
| Unknown                         | 6        | 2.55%   |
| ASUS PRIME                      | 5        | 2.13%   |
| ASUS P5KPL-AM                   | 5        | 2.13%   |
| ASUS All                        | 5        | 2.13%   |
| ASRock A320M-HDV                | 4        | 1.7%    |
| HP Compaq                       | 3        | 1.28%   |
| Gigabyte GA-78LMT-USB3          | 3        | 1.28%   |
| ECS H61H2-MV                    | 3        | 1.28%   |
| ASUS ROG                        | 3        | 1.28%   |
| ASRock B450                     | 3        | 1.28%   |
| Acer Veriton                    | 3        | 1.28%   |
| MSI MS-7B22                     | 2        | 0.85%   |
| MSI MS-7A37                     | 2        | 0.85%   |
| MSI MS-7823                     | 2        | 0.85%   |
| MSI Compaq                      | 2        | 0.85%   |
| LORD ELECTRONICS LORD           | 2        | 0.85%   |
| Lenovo IdeaCentre               | 2        | 0.85%   |
| Intel H61                       | 2        | 0.85%   |
| Gigabyte H61M-DS2               | 2        | 0.85%   |
| Gigabyte B460MDS3H              | 2        | 0.85%   |
| Foxconn Pro                     | 2        | 0.85%   |
| ECS G41T-M12                    | 2        | 0.85%   |
| ECS A55F2-M4                    | 2        | 0.85%   |
| Dell Precision                  | 2        | 0.85%   |
| Dell Inspiron                   | 2        | 0.85%   |
| Biostar H310MHC                 | 2        | 0.85%   |
| ASUS P8H61-M                    | 2        | 0.85%   |
| ASUS P5GC-MX                    | 2        | 0.85%   |
| ASUS H61M-K                     | 2        | 0.85%   |
| ASUS H110M-E                    | 2        | 0.85%   |
| ASRock G41M-VS3                 | 2        | 0.85%   |
| ASRock FM2A68M-DG3+             | 2        | 0.85%   |
| ASRock AB350                    | 2        | 0.85%   |
| ASRock A88M-G                   | 2        | 0.85%   |
| Acer Aspire                     | 2        | 0.85%   |
| ZYREX COMPUTER SYSTEMS TACTICAL | 1        | 0.43%   |
| Wearnes POS                     | 1        | 0.43%   |
| SPECTRUM UTAMA VA               | 1        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 34       | 14.47%  |
| 2011 | 25       | 10.64%  |
| 2010 | 20       | 8.51%   |
| 2014 | 19       | 8.09%   |
| 2012 | 18       | 7.66%   |
| 2019 | 17       | 7.23%   |
| 2020 | 15       | 6.38%   |
| 2017 | 15       | 6.38%   |
| 2018 | 14       | 5.96%   |
| 2008 | 14       | 5.96%   |
| 2016 | 13       | 5.53%   |
| 2015 | 11       | 4.68%   |
| 2009 | 10       | 4.26%   |
| 2007 | 6        | 2.55%   |
| 2021 | 4        | 1.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 235      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 231      | 98.3%   |
| Enabled  | 4        | 1.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 235      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 69       | 28.99%  |
| 8.01-16.0   | 54       | 22.69%  |
| 4.01-8.0    | 46       | 19.33%  |
| 16.01-24.0  | 42       | 17.65%  |
| 32.01-64.0  | 11       | 4.62%   |
| 1.01-2.0    | 9        | 3.78%   |
| 2.01-3.0    | 3        | 1.26%   |
| 24.01-32.0  | 2        | 0.84%   |
| 64.01-256.0 | 2        | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 109      | 41.76%  |
| 2.01-3.0   | 69       | 26.44%  |
| 3.01-4.0   | 32       | 12.26%  |
| 4.01-8.0   | 26       | 9.96%   |
| 0.51-1.0   | 19       | 7.28%   |
| 16.01-24.0 | 2        | 0.77%   |
| 8.01-16.0  | 2        | 0.77%   |
| 0.01-0.5   | 2        | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 53.31%  |
| 2      | 73       | 30.17%  |
| 3      | 25       | 10.33%  |
| 4      | 9        | 3.72%   |
| 5      | 3        | 1.24%   |
| 0      | 2        | 0.83%   |
| 15     | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 156      | 65%     |
| Yes       | 84       | 35%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 230      | 97.87%  |
| No        | 5        | 2.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 128      | 53.56%  |
| No        | 111      | 46.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 79.83%  |
| Yes       | 48       | 20.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Indonesia | 235      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Jakarta                | 77       | 30.8%   |
| Bandung                | 24       | 9.6%    |
| Surabaya               | 17       | 6.8%    |
| Yogyakarta             | 13       | 5.2%    |
| Tangerang              | 10       | 4%      |
| Medan                  | 10       | 4%      |
| Malang                 | 7        | 2.8%    |
| South Tangerang        | 5        | 2%      |
| Bogor                  | 5        | 2%      |
| Semarang               | 4        | 1.6%    |
| Palembang              | 4        | 1.6%    |
| Bekasi                 | 4        | 1.6%    |
| Banjarmasin            | 4        | 1.6%    |
| Sleman                 | 3        | 1.2%    |
| Salatiga               | 3        | 1.2%    |
| Gresik                 | 3        | 1.2%    |
| Depok                  | 3        | 1.2%    |
| Tasikmalaya            | 2        | 0.8%    |
| Tanjung Pinang         | 2        | 0.8%    |
| Sukabumi               | 2        | 0.8%    |
| Pasuruan               | 2        | 0.8%    |
| Makassar               | 2        | 0.8%    |
| Denpasar               | 2        | 0.8%    |
| Batam                  | 2        | 0.8%    |
| Bantabantaeng          | 2        | 0.8%    |
| Balikpapan             | 2        | 0.8%    |
| Wates                  | 1        | 0.4%    |
| Ulee Gle               | 1        | 0.4%    |
| Tanjung Balai          | 1        | 0.4%    |
| Surakarta              | 1        | 0.4%    |
| South Jakarta          | 1        | 0.4%    |
| Sidoarjo               | 1        | 0.4%    |
| Serang                 | 1        | 0.4%    |
| Randuagung             | 1        | 0.4%    |
| Purwokerto             | 1        | 0.4%    |
| Pontianak              | 1        | 0.4%    |
| Pati                   | 1        | 0.4%    |
| Pancur Biru Lestari II | 1        | 0.4%    |
| Mataram                | 1        | 0.4%    |
| Manado                 | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 116      | 152    | 32.22%  |
| WDC                   | 70       | 102    | 19.44%  |
| Samsung Electronics   | 30       | 40     | 8.33%   |
| Toshiba               | 17       | 19     | 4.72%   |
| Hitachi               | 12       | 13     | 3.33%   |
| A-DATA Technology     | 11       | 13     | 3.06%   |
| V-GeN                 | 10       | 11     | 2.78%   |
| SanDisk               | 10       | 12     | 2.78%   |
| Unknown               | 7        | 12     | 1.94%   |
| China                 | 7        | 7      | 1.94%   |
| XPG                   | 5        | 8      | 1.39%   |
| Silicon Motion        | 5        | 5      | 1.39%   |
| Transcend             | 4        | 7      | 1.11%   |
| Patriot               | 4        | 6      | 1.11%   |
| MidasForce            | 4        | 4      | 1.11%   |
| Kingston              | 4        | 5      | 1.11%   |
| HGST                  | 4        | 6      | 1.11%   |
| Apacer                | 4        | 5      | 1.11%   |
| Pioneer               | 3        | 3      | 0.83%   |
| OCZ                   | 3        | 3      | 0.83%   |
| Maxtor                | 3        | 3      | 0.83%   |
| Biostar               | 3        | 4      | 0.83%   |
| JMicron Technology    | 2        | 2      | 0.56%   |
| Intel                 | 2        | 2      | 0.56%   |
| Unknown               | 2        | 2      | 0.56%   |
| Verbatim              | 1        | 1      | 0.28%   |
| TO Exter              | 1        | 1      | 0.28%   |
| Team                  | 1        | 1      | 0.28%   |
| SPCC                  | 1        | 1      | 0.28%   |
| Smart                 | 1        | 1      | 0.28%   |
| RX7                   | 1        | 1      | 0.28%   |
| Realtek Semiconductor | 1        | 1      | 0.28%   |
| Phison                | 1        | 1      | 0.28%   |
| Memory                | 1        | 1      | 0.28%   |
| Kingmax               | 1        | 1      | 0.28%   |
| Hoodisk               | 1        | 4      | 0.28%   |
| Hewlett-Packard       | 1        | 1      | 0.28%   |
| Green House           | 1        | 1      | 0.28%   |
| Gigabyte Technology   | 1        | 1      | 0.28%   |
| GALAX                 | 1        | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 16       | 3.91%   |
| Seagate ST3500312CS 500GB        | 16       | 3.91%   |
| Seagate ST1000DM010-2EP102 1TB   | 9        | 2.2%    |
| Seagate ST3250318AS 250GB        | 8        | 1.96%   |
| A-DATA SU650 120GB SSD           | 6        | 1.47%   |
| Toshiba DT01ACA200 2TB           | 5        | 1.22%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 1.22%   |
| Seagate ST1000DM003-1ER162 1TB   | 5        | 1.22%   |
| WDC WD10EZEX-00WN4A0 1TB         | 4        | 0.98%   |
| Seagate ST3500418AS 500GB        | 4        | 0.98%   |
| Seagate ST3500413AS 500GB        | 4        | 0.98%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 0.98%   |
| SanDisk SSD PLUS 240GB           | 4        | 0.98%   |
| Samsung SSD 850 120GB            | 4        | 0.98%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.73%   |
| WDC WD1600AVVS-63L2B0 160GB      | 3        | 0.73%   |
| Toshiba HDWD110 1TB              | 3        | 0.73%   |
| Toshiba DT01ACA050 500GB         | 3        | 0.73%   |
| Seagate ST3160815AS 160GB        | 3        | 0.73%   |
| Seagate ST3160318AS 160GB        | 3        | 0.73%   |
| Samsung SSD 860 EVO 250GB        | 3        | 0.73%   |
| Samsung SSD 850 EVO 250GB        | 3        | 0.73%   |
| MidasForce SSD 120GB             | 3        | 0.73%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.73%   |
| Hitachi HTS545032B9A300 320GB    | 3        | 0.73%   |
| Apacer AS340 240GB SSD           | 3        | 0.73%   |
| XPG NVMe SSD Drive 512GB         | 2        | 0.49%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 2        | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2        | 0.49%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 2        | 0.49%   |
| WDC WD5000AAKX-083CA1 500GB      | 2        | 0.49%   |
| WDC WD3200AVJS-63B6A0 320GB      | 2        | 0.49%   |
| WDC WD3200AAJS-00L7A0 320GB      | 2        | 0.49%   |
| WDC WD20EZRX-00DC0B0 2TB         | 2        | 0.49%   |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 0.49%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.49%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.49%   |
| WDC WD1003FZEX-00RLFA0 1TB       | 2        | 0.49%   |
| Transcend TS120GSSD220S 120GB    | 2        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 115      | 150    | 51.57%  |
| WDC                 | 62       | 92     | 27.8%   |
| Toshiba             | 16       | 18     | 7.17%   |
| Hitachi             | 12       | 13     | 5.38%   |
| Samsung Electronics | 8        | 8      | 3.59%   |
| HGST                | 4        | 6      | 1.79%   |
| Maxtor              | 3        | 3      | 1.35%   |
| Unknown             | 1        | 1      | 0.45%   |
| Hewlett-Packard     | 1        | 1      | 0.45%   |
| ExcelStor           | 1        | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 26     | 18.63%  |
| WDC                 | 9        | 9      | 8.82%   |
| A-DATA Technology   | 9        | 10     | 8.82%   |
| SanDisk             | 8        | 9      | 7.84%   |
| China               | 7        | 7      | 6.86%   |
| V-GeN               | 4        | 5      | 3.92%   |
| Patriot             | 4        | 6      | 3.92%   |
| MidasForce          | 4        | 4      | 3.92%   |
| Kingston            | 4        | 5      | 3.92%   |
| Apacer              | 4        | 5      | 3.92%   |
| Unknown             | 3        | 4      | 2.94%   |
| Transcend           | 3        | 6      | 2.94%   |
| Pioneer             | 3        | 3      | 2.94%   |
| OCZ                 | 3        | 3      | 2.94%   |
| Seagate             | 2        | 2      | 1.96%   |
| Biostar             | 2        | 3      | 1.96%   |
| Unknown             | 2        | 2      | 1.96%   |
| Verbatim            | 1        | 1      | 0.98%   |
| Toshiba             | 1        | 1      | 0.98%   |
| TO Exter            | 1        | 1      | 0.98%   |
| Team                | 1        | 1      | 0.98%   |
| SPCC                | 1        | 1      | 0.98%   |
| Memory              | 1        | 1      | 0.98%   |
| Kingmax             | 1        | 1      | 0.98%   |
| Intel               | 1        | 1      | 0.98%   |
| Hoodisk             | 1        | 4      | 0.98%   |
| Green House         | 1        | 1      | 0.98%   |
| Gigabyte Technology | 1        | 1      | 0.98%   |
| GALAX               | 1        | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 185      | 293    | 60.06%  |
| SSD     | 87       | 124    | 28.25%  |
| NVMe    | 24       | 34     | 7.79%   |
| Unknown | 11       | 12     | 3.57%   |
| MMC     | 1        | 4      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 226      | 419    | 87.6%   |
| NVMe | 22       | 32     | 8.53%   |
| SAS  | 9        | 12     | 3.49%   |
| MMC  | 1        | 4      | 0.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 183      | 298    | 66.3%   |
| 0.51-1.0   | 60       | 79     | 21.74%  |
| 1.01-2.0   | 23       | 28     | 8.33%   |
| 3.01-4.0   | 5        | 7      | 1.81%   |
| 2.01-3.0   | 3        | 3      | 1.09%   |
| 4.01-10.0  | 2        | 2      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 71       | 29.34%  |
| 251-500        | 56       | 23.14%  |
| 51-100         | 26       | 10.74%  |
| 1-20           | 23       | 9.5%    |
| 501-1000       | 23       | 9.5%    |
| 1001-2000      | 14       | 5.79%   |
| 21-50          | 13       | 5.37%   |
| 2001-3000      | 8        | 3.31%   |
| More than 3000 | 6        | 2.48%   |
| Unknown        | 2        | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 119      | 48.18%  |
| 21-50          | 38       | 15.38%  |
| 101-250        | 24       | 9.72%   |
| 51-100         | 23       | 9.31%   |
| 251-500        | 17       | 6.88%   |
| 501-1000       | 13       | 5.26%   |
| 1001-2000      | 8        | 3.24%   |
| More than 3000 | 2        | 0.81%   |
| Unknown        | 2        | 0.81%   |
| 2001-3000      | 1        | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 6        | 8      | 12.24%  |
| Seagate ST9250410AS 250GB         | 2        | 2      | 4.08%   |
| WDC WD7500BPVT-55HXZT4 752GB      | 1        | 1      | 2.04%   |
| WDC WD6400AADS-00M2B0 640GB       | 1        | 1      | 2.04%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1        | 1      | 2.04%   |
| WDC WD5000AZLX-00JKKA0 500GB      | 1        | 1      | 2.04%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 1      | 2.04%   |
| WDC WD5000AAKX-083CA1 500GB       | 1        | 1      | 2.04%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 2.04%   |
| WDC WD5000AACS-00G8B0 500GB       | 1        | 1      | 2.04%   |
| WDC WD40EZRX-00SPEB0 4TB          | 1        | 1      | 2.04%   |
| WDC WD3200JS-63PDB1 320GB         | 1        | 1      | 2.04%   |
| WDC WD3200BPVT-00HXZT1 320GB      | 1        | 1      | 2.04%   |
| WDC WD3200AVJS-63B6A0 320GB       | 1        | 1      | 2.04%   |
| WDC WD3200AAJS-08B4A0 320GB       | 1        | 1      | 2.04%   |
| WDC WD30EZRZ-00Z5HB0 3TB          | 1        | 1      | 2.04%   |
| WDC WD30EFRX-68AX9N0 3TB          | 1        | 1      | 2.04%   |
| WDC WD1600AVVS-63L2B0 160GB       | 1        | 1      | 2.04%   |
| WDC WD1600AAJS-00Z4A0 160GB       | 1        | 1      | 2.04%   |
| WDC WD10EZEX-08M2NA0 1TB          | 1        | 1      | 2.04%   |
| Toshiba DT01ACA200 2TB            | 1        | 1      | 2.04%   |
| Seagate ST9500420AS 500GB         | 1        | 1      | 2.04%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 2.04%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 2.04%   |
| Seagate ST3500413AS 500GB         | 1        | 1      | 2.04%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 2.04%   |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 2.04%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 2.04%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 2.04%   |
| SanDisk SSD PLUS 240GB            | 1        | 1      | 2.04%   |
| Samsung Electronics SV0412H 40GB  | 1        | 1      | 2.04%   |
| Samsung Electronics HD161GJ 160GB | 1        | 1      | 2.04%   |
| Maxtor STM380815AS 80GB           | 1        | 1      | 2.04%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 2.04%   |
| Hitachi HTS545016B9A300 160GB     | 1        | 1      | 2.04%   |
| Hitachi HTS542512K9SA00 120GB     | 1        | 1      | 2.04%   |
| Hitachi HDS721050CLA660 500GB     | 1        | 1      | 2.04%   |
| Hitachi HDS5C1050CLA382 500GB     | 1        | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 38.64%  |
| WDC                 | 14       | 18     | 31.82%  |
| Hitachi             | 4        | 4      | 9.09%   |
| Samsung Electronics | 2        | 2      | 4.55%   |
| Toshiba             | 1        | 1      | 2.27%   |
| SanDisk             | 1        | 1      | 2.27%   |
| Maxtor              | 1        | 1      | 2.27%   |
| Kingston            | 1        | 1      | 2.27%   |
| HGST                | 1        | 1      | 2.27%   |
| China               | 1        | 1      | 2.27%   |
| Apacer              | 1        | 2      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 20     | 42.5%   |
| WDC                 | 14       | 18     | 35%     |
| Hitachi             | 4        | 4      | 10%     |
| Samsung Electronics | 2        | 2      | 5%      |
| Toshiba             | 1        | 1      | 2.5%    |
| Maxtor              | 1        | 1      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 34       | 47     | 91.89%  |
| SSD  | 3        | 5      | 8.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3250318AS 250GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 162      | 291    | 61.13%  |
| Works    | 65       | 123    | 24.53%  |
| Malfunc  | 37       | 52     | 13.96%  |
| Failed   | 1        | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 174      | 62.59%  |
| AMD                      | 59       | 21.22%  |
| ASMedia Technology       | 8        | 2.88%   |
| Silicon Motion           | 7        | 2.52%   |
| ADATA Technology         | 6        | 2.16%   |
| JMicron Technology       | 5        | 1.8%    |
| VIA Technologies         | 4        | 1.44%   |
| Samsung Electronics      | 4        | 1.44%   |
| SanDisk                  | 3        | 1.08%   |
| Nvidia                   | 3        | 1.08%   |
| Realtek Semiconductor    | 2        | 0.72%   |
| Marvell Technology Group | 2        | 0.72%   |
| Phison Electronics       | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 32       | 8.44%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 7.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 25       | 6.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 6.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20       | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14       | 3.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14       | 3.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 3.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 2.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9        | 2.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 2.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.11%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 8        | 2.11%   |
| AMD FCH IDE Controller                                                                  | 7        | 1.85%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.58%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 1.58%   |
| AMD FCH SATA Controller D                                                               | 6        | 1.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 1.58%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.32%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 1.06%   |
| JMicron JMB368 IDE controller                                                           | 4        | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.06%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.79%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.79%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 0.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.53%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.53%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.53%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 168      | 58.33%  |
| IDE  | 91       | 31.6%   |
| NVMe | 22       | 7.64%   |
| RAID | 6        | 2.08%   |
| SAS  | 1        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 173      | 73.62%  |
| AMD    | 62       | 26.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 9        | 3.81%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 7        | 2.97%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 7        | 2.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 2.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 1.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 1.69%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 4        | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.69%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 4        | 1.69%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 4        | 1.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 1.69%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 1.69%   |
| AMD Phenom II X6 1055T Processor            | 4        | 1.69%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 1.27%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.27%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.27%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.27%   |
| AMD A6-6400K APU with Radeon HD Graphics    | 3        | 1.27%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 0.85%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 0.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.85%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.85%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 2        | 0.85%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.85%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.85%   |
| Intel Core i5-4460T CPU @ 1.90GHz           | 2        | 0.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.85%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 0.85%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.85%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.85%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.85%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 0.85%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.85%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.85%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 0.85%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 46       | 19.49%  |
| Intel Core i3           | 34       | 14.41%  |
| Intel Core i7           | 29       | 12.29%  |
| Intel Core 2 Duo        | 23       | 9.75%   |
| AMD Ryzen 5             | 14       | 5.93%   |
| Intel Pentium           | 9        | 3.81%   |
| Intel Core 2 Quad       | 8        | 3.39%   |
| AMD Ryzen 3             | 8        | 3.39%   |
| Intel Xeon              | 6        | 2.54%   |
| AMD Athlon II X2        | 6        | 2.54%   |
| Other                   | 5        | 2.12%   |
| Intel Pentium Dual-Core | 5        | 2.12%   |
| AMD A6                  | 5        | 2.12%   |
| AMD Phenom II X6        | 4        | 1.69%   |
| AMD A8                  | 4        | 1.69%   |
| Intel Atom              | 3        | 1.27%   |
| AMD Phenom II X4        | 3        | 1.27%   |
| AMD FX                  | 3        | 1.27%   |
| Intel Core 2            | 2        | 0.85%   |
| AMD Ryzen 9             | 2        | 0.85%   |
| AMD Athlon X4           | 2        | 0.85%   |
| AMD A10                 | 2        | 0.85%   |
| Intel Pentium Gold      | 1        | 0.42%   |
| Intel Pentium D         | 1        | 0.42%   |
| Intel Genuine           | 1        | 0.42%   |
| Intel Core 2 Extreme    | 1        | 0.42%   |
| Intel Celeron           | 1        | 0.42%   |
| AMD Ryzen 7             | 1        | 0.42%   |
| AMD Ryzen 3 PRO         | 1        | 0.42%   |
| AMD PRO A8              | 1        | 0.42%   |
| AMD Phenom              | 1        | 0.42%   |
| AMD GX                  | 1        | 0.42%   |
| AMD Athlon 64 X2        | 1        | 0.42%   |
| AMD Athlon              | 1        | 0.42%   |
| AMD A4                  | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 97       | 41.1%   |
| 4      | 96       | 40.68%  |
| 6      | 25       | 10.59%  |
| 8      | 8        | 3.39%   |
| 1      | 5        | 2.12%   |
| 12     | 3        | 1.27%   |
| 3      | 2        | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 235      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 51.49%  |
| 2      | 114      | 48.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 229      | 97.45%  |
| Unknown        | 5        | 2.13%   |
| 32-bit         | 1        | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 14.11%  |
| 0x306c3    | 28       | 11.62%  |
| 0x1067a    | 26       | 10.79%  |
| 0x306a9    | 20       | 8.3%    |
| 0x206a7    | 19       | 7.88%   |
| 0x906e9    | 9        | 3.73%   |
| 0x906ea    | 6        | 2.49%   |
| 0x6fb      | 5        | 2.07%   |
| 0x506e3    | 5        | 2.07%   |
| 0x010000c8 | 5        | 2.07%   |
| 0x20652    | 4        | 1.66%   |
| 0x08701021 | 4        | 1.66%   |
| 0x08001137 | 4        | 1.66%   |
| 0x06003106 | 4        | 1.66%   |
| 0x010000dc | 4        | 1.66%   |
| 0xa0671    | 3        | 1.24%   |
| 0xa0653    | 3        | 1.24%   |
| 0x6fd      | 3        | 1.24%   |
| 0x106e5    | 3        | 1.24%   |
| 0x106a5    | 3        | 1.24%   |
| 0x10676    | 3        | 1.24%   |
| 0x08101007 | 3        | 1.24%   |
| 0x06001119 | 3        | 1.24%   |
| 0x010000c7 | 3        | 1.24%   |
| 0xa0655    | 2        | 0.83%   |
| 0x906ed    | 2        | 0.83%   |
| 0x906eb    | 2        | 0.83%   |
| 0x6f6      | 2        | 0.83%   |
| 0x206d7    | 2        | 0.83%   |
| 0x106ca    | 2        | 0.83%   |
| 0x08108102 | 2        | 0.83%   |
| 0x08101016 | 2        | 0.83%   |
| 0x0810100b | 2        | 0.83%   |
| 0x0800820d | 2        | 0.83%   |
| 0xf62      | 1        | 0.41%   |
| 0x90675    | 1        | 0.41%   |
| 0x706a8    | 1        | 0.41%   |
| 0x306f2    | 1        | 0.41%   |
| 0x0a201016 | 1        | 0.41%   |
| 0x08108109 | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 32       | 13.62%  |
| Penryn           | 29       | 12.34%  |
| SandyBridge      | 26       | 11.06%  |
| IvyBridge        | 23       | 9.79%   |
| KabyLake         | 21       | 8.94%   |
| K10              | 14       | 5.96%   |
| Zen              | 13       | 5.53%   |
| Core             | 10       | 4.26%   |
| Zen 2            | 8        | 3.4%    |
| Piledriver       | 7        | 2.98%   |
| Skylake          | 6        | 2.55%   |
| Nehalem          | 6        | 2.55%   |
| CometLake        | 6        | 2.55%   |
| Zen+             | 5        | 2.13%   |
| Westmere         | 5        | 2.13%   |
| Steamroller      | 5        | 2.13%   |
| Excavator        | 3        | 1.28%   |
| Bonnell          | 3        | 1.28%   |
| K10 Llano        | 2        | 0.85%   |
| Unknown          | 2        | 0.85%   |
| Zen 3            | 1        | 0.43%   |
| Puma             | 1        | 0.43%   |
| NetBurst         | 1        | 0.43%   |
| K8 Hammer        | 1        | 0.43%   |
| Jaguar           | 1        | 0.43%   |
| Icelake          | 1        | 0.43%   |
| Goldmont plus    | 1        | 0.43%   |
| Bulldozer        | 1        | 0.43%   |
| Alderlake Hybrid | 1        | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 106      | 41.73%  |
| AMD    | 84       | 33.07%  |
| Nvidia | 64       | 25.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16       | 6.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15       | 5.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 14       | 5.43%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 4.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 3.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 3.1%    |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.71%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 2.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.71%   |
| Intel HD Graphics 630                                                       | 6        | 2.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 6        | 2.33%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 1.94%   |
| Nvidia GF108 [GeForce GT 730]                                               | 5        | 1.94%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 5        | 1.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.55%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.55%   |
| Intel HD Graphics 530                                                       | 3        | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 1.16%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 3        | 1.16%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.16%   |
| AMD Richland [Radeon HD 8470D]                                              | 3        | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.16%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.78%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.78%   |
| Nvidia GK208B [GeForce GT 720]                                              | 2        | 0.78%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 0.78%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 2        | 0.78%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 0.78%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 2        | 0.78%   |
| AMD RV730 XT [Radeon HD 4670]                                               | 2        | 0.78%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 2        | 0.78%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 91       | 38.4%   |
| 1 x AMD                | 76       | 32.07%  |
| 1 x Nvidia             | 58       | 24.47%  |
| Intel + AMD            | 4        | 1.69%   |
| 2 x AMD                | 3        | 1.27%   |
| Intel + Nvidia         | 3        | 1.27%   |
| 1 x Intel + 4 x Nvidia | 1        | 0.42%   |
| AMD + Nvidia           | 1        | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 200      | 82.64%  |
| Proprietary | 36       | 14.88%  |
| Unknown     | 6        | 2.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 102      | 42.86%  |
| 1.01-2.0   | 43       | 18.07%  |
| 0.51-1.0   | 37       | 15.55%  |
| 0.01-0.5   | 25       | 10.5%   |
| 3.01-4.0   | 17       | 7.14%   |
| 7.01-8.0   | 6        | 2.52%   |
| 5.01-6.0   | 4        | 1.68%   |
| 8.01-16.0  | 3        | 1.26%   |
| 2.01-3.0   | 1        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 53       | 24.65%  |
| Samsung Electronics  | 32       | 14.88%  |
| Dell                 | 31       | 14.42%  |
| Hewlett-Packard      | 15       | 6.98%   |
| AOC                  | 12       | 5.58%   |
| Philips              | 10       | 4.65%   |
| Lenovo               | 9        | 4.19%   |
| Acer                 | 8        | 3.72%   |
| LG Electronics       | 7        | 3.26%   |
| ViewSonic            | 5        | 2.33%   |
| Toshiba              | 5        | 2.33%   |
| Ancor Communications | 5        | 2.33%   |
| BenQ                 | 4        | 1.86%   |
| Unknown              | 2        | 0.93%   |
| Sharp                | 2        | 0.93%   |
| RTK                  | 2        | 0.93%   |
| GDH                  | 2        | 0.93%   |
| ASUSTek Computer     | 2        | 0.93%   |
| Xiaomi               | 1        | 0.47%   |
| Tech Concepts        | 1        | 0.47%   |
| SPC                  | 1        | 0.47%   |
| S2-Tek               | 1        | 0.47%   |
| PiLot                | 1        | 0.47%   |
| Panasonic            | 1        | 0.47%   |
| HRX                  | 1        | 0.47%   |
| Haier                | 1        | 0.47%   |
| Gateway              | 1        | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 8        | 3.57%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 7        | 3.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6        | 2.68%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch              | 4        | 1.79%   |
| Toshiba LCD-MONITOR LCD1560 1366x768 344x194mm 15.5-inch             | 3        | 1.34%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 3        | 1.34%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch              | 3        | 1.34%   |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                     | 3        | 1.34%   |
| Dell E1912H DELF03E 1366x768 410x230mm 18.5-inch                     | 3        | 1.34%   |
| Unknown LCD Monitor AcerMFMAV 1440x900                               | 2        | 0.89%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                      | 2        | 0.89%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 2        | 0.89%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 0.89%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2        | 0.89%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch     | 2        | 0.89%   |
| Samsung Electronics LCD Monitor S19D300 1366x768                     | 2        | 0.89%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 2        | 0.89%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2        | 0.89%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                   | 2        | 0.89%   |
| LG Electronics LCD Monitor LG IPS WSXGA 1440x900                     | 2        | 0.89%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch            | 2        | 0.89%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                 | 2        | 0.89%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2        | 0.89%   |
| Goldstar LG HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch             | 2        | 0.89%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 0.89%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch               | 2        | 0.89%   |
| Goldstar 16EN33 GSM3E8F 1366x768 344x194mm 15.5-inch                 | 2        | 0.89%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                    | 2        | 0.89%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 2        | 0.89%   |
| Acer X163WL ACR022E 1366x768 344x193mm 15.5-inch                     | 2        | 0.89%   |
| Xiaomi Mi TV XMD004A 3840x2160 1110x620mm 50.1-inch                  | 1        | 0.45%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch            | 1        | 0.45%   |
| ViewSonic VA2219 Series VSC7932 1920x1080 477x268mm 21.5-inch        | 1        | 0.45%   |
| ViewSonic VA1936 SERIES VSC9A28 1366x768 410x230mm 18.5-inch         | 1        | 0.45%   |
| ViewSonic VA1931 Series VSC5826 1366x768 410x230mm 18.5-inch         | 1        | 0.45%   |
| ViewSonic LCD Monitor VA2249 Series 3840x1080                        | 1        | 0.45%   |
| Unknown LCD Monitor AcerMFMAV 1680x1050                              | 1        | 0.45%   |
| Toshiba TV TSB010F 1920x1080 882x498mm 39.9-inch                     | 1        | 0.45%   |
| Toshiba 15.6W LCD2009 1360x768 340x190mm 15.3-inch                   | 1        | 0.45%   |
| Tech Concepts LCD Monitor MS3663 1366x768                            | 1        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 76       | 36.19%  |
| 1366x768 (WXGA)    | 69       | 32.86%  |
| 3840x2160 (4K)     | 14       | 6.67%   |
| 1440x900 (WXGA+)   | 12       | 5.71%   |
| 1600x900 (HD+)     | 8        | 3.81%   |
| 1360x768           | 6        | 2.86%   |
| 1280x1024 (SXGA)   | 6        | 2.86%   |
| 1024x768 (XGA)     | 3        | 1.43%   |
| 3840x1080          | 2        | 0.95%   |
| 3440x1440          | 2        | 0.95%   |
| 2560x1440 (QHD)    | 2        | 0.95%   |
| 2560x1080          | 2        | 0.95%   |
| Unknown            | 2        | 0.95%   |
| 640x480            | 1        | 0.48%   |
| 5760x2160          | 1        | 0.48%   |
| 1680x1050 (WSXGA+) | 1        | 0.48%   |
| 1600x1200          | 1        | 0.48%   |
| 1280x960           | 1        | 0.48%   |
| 1280x720 (HD)      | 1        | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 48       | 22.86%  |
| 21      | 38       | 18.1%   |
| 23      | 21       | 10%     |
| Unknown | 20       | 9.52%   |
| 15      | 18       | 8.57%   |
| 19      | 15       | 7.14%   |
| 24      | 11       | 5.24%   |
| 27      | 8        | 3.81%   |
| 17      | 5        | 2.38%   |
| 31      | 3        | 1.43%   |
| 40      | 2        | 0.95%   |
| 37      | 2        | 0.95%   |
| 34      | 2        | 0.95%   |
| 20      | 2        | 0.95%   |
| 16      | 2        | 0.95%   |
| 13      | 2        | 0.95%   |
| 84      | 1        | 0.48%   |
| 65      | 1        | 0.48%   |
| 60      | 1        | 0.48%   |
| 52      | 1        | 0.48%   |
| 48      | 1        | 0.48%   |
| 46      | 1        | 0.48%   |
| 42      | 1        | 0.48%   |
| 39      | 1        | 0.48%   |
| 35      | 1        | 0.48%   |
| 32      | 1        | 0.48%   |
| 22      | 1        | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 99       | 47.6%   |
| 501-600     | 39       | 18.75%  |
| 301-350     | 21       | 10.1%   |
| Unknown     | 20       | 9.62%   |
| 351-400     | 7        | 3.37%   |
| 801-900     | 6        | 2.88%   |
| 1001-1500   | 5        | 2.4%    |
| 601-700     | 4        | 1.92%   |
| 701-800     | 3        | 1.44%   |
| 201-300     | 2        | 0.96%   |
| 1501-2000   | 1        | 0.48%   |
| 901-1000    | 1        | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 161      | 78.54%  |
| Unknown | 19       | 9.27%   |
| 16/10   | 12       | 5.85%   |
| 5/4     | 6        | 2.93%   |
| 4/3     | 4        | 1.95%   |
| 21/9    | 3        | 1.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 55       | 26.19%  |
| 141-150        | 51       | 24.29%  |
| 151-200        | 30       | 14.29%  |
| Unknown        | 20       | 9.52%   |
| 101-110        | 17       | 8.1%    |
| 301-350        | 8        | 3.81%   |
| 351-500        | 7        | 3.33%   |
| 501-1000       | 7        | 3.33%   |
| More than 1000 | 5        | 2.38%   |
| 251-300        | 4        | 1.9%    |
| 81-90          | 2        | 0.95%   |
| 111-120        | 2        | 0.95%   |
| 131-140        | 1        | 0.48%   |
| 91-100         | 1        | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 121      | 57.89%  |
| 101-120 | 58       | 27.75%  |
| Unknown | 20       | 9.57%   |
| 1-50    | 9        | 4.31%   |
| 161-240 | 1        | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 205      | 86.13%  |
| 2     | 18       | 7.56%   |
| 0     | 15       | 6.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 178      | 48.9%   |
| Intel                           | 56       | 15.38%  |
| Qualcomm Atheros                | 27       | 7.42%   |
| Ralink Technology               | 24       | 6.59%   |
| TP-Link                         | 18       | 4.95%   |
| Xiaomi                          | 11       | 3.02%   |
| Samsung Electronics             | 7        | 1.92%   |
| Broadcom                        | 7        | 1.92%   |
| Qualcomm Atheros Communications | 6        | 1.65%   |
| Ralink                          | 5        | 1.37%   |
| D-Link System                   | 4        | 1.1%    |
| D-Link                          | 3        | 0.82%   |
| ASIX Electronics                | 3        | 0.82%   |
| Qualcomm                        | 2        | 0.55%   |
| Nvidia                          | 2        | 0.55%   |
| HMD Global                      | 2        | 0.55%   |
| AboCom Systems                  | 2        | 0.55%   |
| vivo                            | 1        | 0.27%   |
| VIA Technologies                | 1        | 0.27%   |
| QinHeng Electronics             | 1        | 0.27%   |
| OPPO Electronics                | 1        | 0.27%   |
| Marvell Technology Group        | 1        | 0.27%   |
| Huawei Technologies             | 1        | 0.27%   |
| Broadcom Limited                | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133      | 32.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27       | 6.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 18       | 4.39%   |
| Ralink MT7601U Wireless Adapter                                   | 13       | 3.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 12       | 2.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 2.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 1.95%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 7        | 1.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 6        | 1.46%   |
| Qualcomm Atheros AR9271 802.11n                                   | 6        | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6        | 1.46%   |
| Intel I211 Gigabit Network Connection                             | 6        | 1.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5        | 1.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5        | 1.22%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3        | 0.73%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 3        | 0.73%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 3        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.73%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.73%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.73%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.49%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 2        | 0.49%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 2        | 0.49%   |
| Qualcomm Mobile Router                                            | 2        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.49%   |
| Intel Wireless 3160                                               | 2        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 43       | 32.58%  |
| Ralink Technology               | 24       | 18.18%  |
| Intel                           | 18       | 13.64%  |
| TP-Link                         | 17       | 12.88%  |
| Qualcomm Atheros                | 8        | 6.06%   |
| Qualcomm Atheros Communications | 6        | 4.55%   |
| Ralink                          | 5        | 3.79%   |
| D-Link                          | 3        | 2.27%   |
| Broadcom                        | 3        | 2.27%   |
| D-Link System                   | 2        | 1.52%   |
| AboCom Systems                  | 2        | 1.52%   |
| Broadcom Limited                | 1        | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 18       | 13.43%  |
| Ralink MT7601U Wireless Adapter                            | 13       | 9.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 12       | 8.96%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 7        | 5.22%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 6        | 4.48%   |
| Qualcomm Atheros AR9271 802.11n                            | 6        | 4.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 6        | 4.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 5        | 3.73%   |
| Intel Wi-Fi 6 AX200                                        | 5        | 3.73%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 3        | 2.24%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter    | 3        | 2.24%   |
| Ralink RT5370 Wireless Adapter                             | 3        | 2.24%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 3        | 2.24%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 2        | 1.49%   |
| Ralink RT2501/RT2573 Wireless Adapter                      | 2        | 1.49%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 2        | 1.49%   |
| Intel Wireless 3160                                        | 2        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 2        | 1.49%   |
| D-Link WLAN controller                                     | 2        | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                              | 2        | 1.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 0.75%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                      | 1        | 0.75%   |
| TP-Link 802.11n NIC                                        | 1        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1        | 0.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1        | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1        | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1        | 0.75%   |
| Realtek RTL8187 Wireless Adapter                           | 1        | 0.75%   |
| Realtek 802.11ac NIC                                       | 1        | 0.75%   |
| Ralink RT2070 Wireless Adapter                             | 1        | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 1        | 0.75%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                       | 1        | 0.75%   |
| Ralink RT2561/RT61 802.11g PCI                             | 1        | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 0.75%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 0.75%   |
| Intel Wireless-AC 9260                                     | 1        | 0.75%   |
| Intel Wireless 7265                                        | 1        | 0.75%   |
| Intel Wireless 7260                                        | 1        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 167      | 61.85%  |
| Intel                    | 44       | 16.3%   |
| Qualcomm Atheros         | 19       | 7.04%   |
| Xiaomi                   | 11       | 4.07%   |
| Samsung Electronics      | 7        | 2.59%   |
| Broadcom                 | 4        | 1.48%   |
| ASIX Electronics         | 3        | 1.11%   |
| Qualcomm                 | 2        | 0.74%   |
| Nvidia                   | 2        | 0.74%   |
| HMD Global               | 2        | 0.74%   |
| D-Link System            | 2        | 0.74%   |
| vivo                     | 1        | 0.37%   |
| VIA Technologies         | 1        | 0.37%   |
| TP-Link                  | 1        | 0.37%   |
| QinHeng Electronics      | 1        | 0.37%   |
| OPPO Electronics         | 1        | 0.37%   |
| Marvell Technology Group | 1        | 0.37%   |
| Huawei Technologies      | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133      | 48.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27       | 9.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 3.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 2.9%    |
| Intel I211 Gigabit Network Connection                             | 6        | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5        | 1.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 1.45%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.45%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3        | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.09%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 1.09%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.72%   |
| Qualcomm Mobile Router                                            | 2        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.72%   |
| HMD Global SDM439-QRD _SN:AD4F5FBB                                | 2        | 0.72%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.72%   |
| vivo 1806                                                         | 1        | 0.36%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.36%   |
| QinHeng CH9200 USB Ethernet Adapter                               | 1        | 0.36%   |
| OPPO RMX2117                                                      | 1        | 0.36%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 230      | 64.25%  |
| WiFi     | 128      | 35.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 146      | 61.86%  |
| WiFi     | 90       | 38.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 177      | 75.32%  |
| 2     | 49       | 20.85%  |
| 3     | 6        | 2.55%   |
| 0     | 2        | 0.85%   |
| 4     | 1        | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 229      | 97.45%  |
| Yes  | 6        | 2.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 23       | 46.94%  |
| Intel                           | 17       | 34.69%  |
| Realtek Semiconductor           | 3        | 6.12%   |
| Qualcomm Atheros Communications | 3        | 6.12%   |
| Broadcom                        | 3        | 6.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23       | 46.94%  |
| Intel Bluetooth wireless interface                  | 7        | 14.29%  |
| Intel AX200 Bluetooth                               | 5        | 10.2%   |
| Realtek Bluetooth Radio                             | 2        | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4.08%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2        | 4.08%   |
| Realtek RTL8723B Bluetooth                          | 1        | 2.04%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 2.04%   |
| Qualcomm Atheros Bluetooth                          | 1        | 2.04%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 2.04%   |
| Intel AX201 Bluetooth                               | 1        | 2.04%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 172      | 50.74%  |
| AMD                    | 91       | 26.84%  |
| Nvidia                 | 58       | 17.11%  |
| Generalplus Technology | 5        | 1.47%   |
| C-Media Electronics    | 5        | 1.47%   |
| JMTek                  | 2        | 0.59%   |
| Creative Labs          | 2        | 0.59%   |
| Texas Instruments      | 1        | 0.29%   |
| SteelSeries ApS        | 1        | 0.29%   |
| Hewlett-Packard        | 1        | 0.29%   |
| Creative Technology    | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 36       | 8.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 32       | 7.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26       | 6.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17       | 4.23%   |
| AMD FCH Azalia Controller                                                  | 17       | 4.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15       | 3.73%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 3.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 2.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 2.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10       | 2.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 2.49%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10       | 2.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 1.99%   |
| Intel 200 Series PCH HD Audio                                              | 8        | 1.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 1.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 8        | 1.99%   |
| Nvidia High Definition Audio Controller                                    | 7        | 1.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 7        | 1.74%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 1.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 6        | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 1.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 1.24%   |
| Generalplus Technology Usb Audio Device                                    | 5        | 1.24%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1%      |
| AMD Trinity HDMI Audio Controller                                          | 4        | 1%      |
| AMD Kabini HDMI/DP Audio                                                   | 4        | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.75%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.5%    |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 27       | 21.95%  |
| SK hynix            | 16       | 13.01%  |
| Kingston            | 15       | 12.2%   |
| Corsair             | 14       | 11.38%  |
| Samsung Electronics | 13       | 10.57%  |
| Micron Technology   | 6        | 4.88%   |
| Team                | 5        | 4.07%   |
| G.Skill             | 5        | 4.07%   |
| Unknown             | 4        | 3.25%   |
| V-GeN               | 3        | 2.44%   |
| Elpida              | 3        | 2.44%   |
| Ramaxel Technology  | 2        | 1.63%   |
| Crucial             | 2        | 1.63%   |
| Visipro             | 1        | 0.81%   |
| Transcend           | 1        | 0.81%   |
| Super Talent        | 1        | 0.81%   |
| Patriot             | 1        | 0.81%   |
| Nanya Technology    | 1        | 0.81%   |
| Essencore           | 1        | 0.81%   |
| A-DATA Technology   | 1        | 0.81%   |
| 04?@                | 1        | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown                                                   | 4        | 3.03%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 3        | 2.27%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s    | 3        | 2.27%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 2        | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                  | 2        | 1.52%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2        | 1.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 2        | 1.52%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                  | 2        | 1.52%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s        | 2        | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2        | 1.52%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2        | 1.52%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s       | 2        | 1.52%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 2        | 1.52%   |
| Samsung RAM M378B5173EB0-CK0 4096MB DIMM DDR3 1600MT/s    | 2        | 1.52%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s      | 2        | 1.52%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 2        | 1.52%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 2        | 1.52%   |
| Visipro RAM T4G86U1-H9H 4096MB DIMM DDR3 1067MT/s         | 1        | 0.76%   |
| V-GeN RAM D4S16GL32A8TS 16384MB DIMM DDR4 3200MT/s        | 1        | 0.76%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s             | 1        | 0.76%   |
| V-GeN RAM D4H8GL24A8 8GB DIMM DDR4 2400MT/s               | 1        | 0.76%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 0.76%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s                | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1066MT/s             | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM SDRAM                      | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                    | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s                | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                 | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM 667MT/s                       | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                | 1        | 0.76%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 46       | 44.66%  |
| DDR4    | 31       | 30.1%   |
| DDR2    | 9        | 8.74%   |
| Unknown | 9        | 8.74%   |
| SDRAM   | 7        | 6.8%    |
| DDR     | 1        | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 93       | 92.08%  |
| SODIMM | 8        | 7.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 43       | 37.39%  |
| 2048  | 29       | 25.22%  |
| 8192  | 26       | 22.61%  |
| 16384 | 10       | 8.7%    |
| 1024  | 6        | 5.22%   |
| 32768 | 1        | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 26.89%  |
| 1333    | 22       | 18.49%  |
| 3200    | 7        | 5.88%   |
| 800     | 7        | 5.88%   |
| 2667    | 6        | 5.04%   |
| 2400    | 6        | 5.04%   |
| 667     | 4        | 3.36%   |
| 3600    | 3        | 2.52%   |
| 2133    | 3        | 2.52%   |
| 1800    | 3        | 2.52%   |
| 1067    | 3        | 2.52%   |
| Unknown | 3        | 2.52%   |
| 3151    | 2        | 1.68%   |
| 3000    | 2        | 1.68%   |
| 2666    | 2        | 1.68%   |
| 1867    | 2        | 1.68%   |
| 1066    | 2        | 1.68%   |
| 333     | 2        | 1.68%   |
| 4040    | 1        | 0.84%   |
| 3866    | 1        | 0.84%   |
| 3466    | 1        | 0.84%   |
| 2934    | 1        | 0.84%   |
| 2733    | 1        | 0.84%   |
| 2465    | 1        | 0.84%   |
| 2200    | 1        | 0.84%   |
| 1866    | 1        | 0.84%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 13       | 72.22%  |
| Hewlett-Packard    | 3        | 16.67%  |
| STMicroelectronics | 1        | 5.56%   |
| Fuji Xerox         | 1        | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson L120 Series          | 5        | 27.78%  |
| Seiko Epson L222 Series          | 3        | 16.67%  |
| Seiko Epson L3110 Series         | 2        | 11.11%  |
| STMicroelectronics JRSVC Printer | 1        | 5.56%   |
| Seiko Epson L312 Series          | 1        | 5.56%   |
| Seiko Epson L300 Series          | 1        | 5.56%   |
| Seiko Epson L1300 Series         | 1        | 5.56%   |
| HP LaserJet P1102                | 1        | 5.56%   |
| HP LaserJet P1006                | 1        | 5.56%   |
| HP DeskJet 5820 series           | 1        | 5.56%   |
| Fuji Xerox DocuPrint M205 b      | 1        | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Chicony Electronics           | 5        | 14.71%  |
| Microdia                      | 4        | 11.76%  |
| Logitech                      | 4        | 11.76%  |
| Generalplus Technology        | 3        | 8.82%   |
| Jieli Technology              | 2        | 5.88%   |
| IMC Networks                  | 2        | 5.88%   |
| GEMBIRD                       | 2        | 5.88%   |
| Cubeternet                    | 2        | 5.88%   |
| Z-Star Microelectronics       | 1        | 2.94%   |
| WCM_USB                       | 1        | 2.94%   |
| Sunplus Innovation Technology | 1        | 2.94%   |
| Realtek Semiconductor         | 1        | 2.94%   |
| MacroSilicon                  | 1        | 2.94%   |
| Huawei Technologies           | 1        | 2.94%   |
| Arkmicro Technologies         | 1        | 2.94%   |
| Apple                         | 1        | 2.94%   |
| ANYKA                         | 1        | 2.94%   |
| A4Tech                        | 1        | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microdia Integrated Camera                        | 2        | 5.88%   |
| Jieli USB PHY 2.0                                 | 2        | 5.88%   |
| Generalplus GENERAL WEBCAM                        | 2        | 5.88%   |
| Chicony HP High Definition 1MP Webcam             | 2        | 5.88%   |
| Z-Star Sirius USB2.0 Camera                       | 1        | 2.94%   |
| WCM_USB WEB CAM                                   | 1        | 2.94%   |
| Sunplus PAPALOOK_229AF                            | 1        | 2.94%   |
| Realtek NexiGo N660P FHD Webcam                   | 1        | 2.94%   |
| Microdia USB camera                               | 1        | 2.94%   |
| Microdia Integrated_Webcam_HD                     | 1        | 2.94%   |
| MacroSilicon USB Video                            | 1        | 2.94%   |
| Logitech Webcam C170                              | 1        | 2.94%   |
| Logitech Webcam C110                              | 1        | 2.94%   |
| Logitech Logitech Webcam C160                     | 1        | 2.94%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 2.94%   |
| IMC Networks XHC Camera                           | 1        | 2.94%   |
| IMC Networks USB2.0 UVC HD Webcam                 | 1        | 2.94%   |
| Huawei HiCamera                                   | 1        | 2.94%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 2.94%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 2.94%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.94%   |
| Cubeternet WebCam                                 | 1        | 2.94%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 1        | 2.94%   |
| Chicony USB 2.0 Camera                            | 1        | 2.94%   |
| Chicony Integrated Camera                         | 1        | 2.94%   |
| Chicony HP Integrated Webcam                      | 1        | 2.94%   |
| Arkmicro USB2.0 PC CAMERA                         | 1        | 2.94%   |
| Apple iPhone5/5C/5S/6                             | 1        | 2.94%   |
| ANYKA V380 FHD Camera                             | 1        | 2.94%   |
| A4Tech Full HD 720P PC Camera                     | 1        | 2.94%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 216      | 91.14%  |
| 1     | 17       | 7.17%   |
| 2     | 3        | 1.27%   |
| 3     | 1        | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 9        | 36%     |
| Graphics card            | 9        | 36%     |
| Communication controller | 2        | 8%      |
| Wireless                 | 1        | 4%      |
| Unassigned class         | 1        | 4%      |
| Storage/ide              | 1        | 4%      |
| Net/ethernet             | 1        | 4%      |
| Camera                   | 1        | 4%      |

