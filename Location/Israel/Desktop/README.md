Linux in Israel - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

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

Total: 397

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B660M-K D4            | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| Gigabyte      | H61M-DS2                    | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | PRIME B365M-K               | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| Gigabyte      | H61M-DS2                    | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| Huanan        | X79 V7.11                   | [79bbc880ba](https://linux-hardware.org/?probe=79bbc880ba) | Jun 03, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | H61M-S2PV                   | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [16d7a61394](https://linux-hardware.org/?probe=16d7a61394) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| Gigabyte      | H61M-DS2                    | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| MSI           | H61M-E23                    | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| MSI           | B450M MORTAR MAX            | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| Gigabyte      | Z97X-UD5H                   | [1cb8a5dfb4](https://linux-hardware.org/?probe=1cb8a5dfb4) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6d206f88cb](https://linux-hardware.org/?probe=6d206f88cb) | Apr 16, 2023 |
| Gigabyte      | B560M H                     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [c47d5d79fd](https://linux-hardware.org/?probe=c47d5d79fd) | Apr 13, 2023 |
| Intel         | D945GCCR AAD78647-301       | [fac1992089](https://linux-hardware.org/?probe=fac1992089) | Apr 13, 2023 |
| Gigabyte      | B560M H                     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | 8455                        | [a52e3d086a](https://linux-hardware.org/?probe=a52e3d086a) | Apr 04, 2023 |
| Dell          | 0GDG8Y A02                  | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| Intel         | DH77EB AAG39073-304         | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [4cfac9a162](https://linux-hardware.org/?probe=4cfac9a162) | Mar 30, 2023 |
| ASUSTek       | PRIME Z690-P                | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASUSTek       | PRIME H510M-D               | [c0e9304de5](https://linux-hardware.org/?probe=c0e9304de5) | Mar 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [7415192b86](https://linux-hardware.org/?probe=7415192b86) | Feb 20, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [e958da375f](https://linux-hardware.org/?probe=e958da375f) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [e47bb0ee84](https://linux-hardware.org/?probe=e47bb0ee84) | Feb 19, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| Gigabyte      | G1.Sniper 3                 | [f7f587188e](https://linux-hardware.org/?probe=f7f587188e) | Feb 03, 2023 |
| Gigabyte      | G31M-ES2L                   | [79a45b9ea0](https://linux-hardware.org/?probe=79a45b9ea0) | Jan 19, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [b6a8598370](https://linux-hardware.org/?probe=b6a8598370) | Jan 19, 2023 |
| Unknown       | Unknown                     | [78a20b41ee](https://linux-hardware.org/?probe=78a20b41ee) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9767004b24](https://linux-hardware.org/?probe=9767004b24) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [87c4201895](https://linux-hardware.org/?probe=87c4201895) | Jan 07, 2023 |
| ASUSTek       | PRIME Z390-P                | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Gigabyte      | B150M-D3H-CF                | [504222de34](https://linux-hardware.org/?probe=504222de34) | Nov 20, 2022 |
| Gigabyte      | B150M-D3H-CF                | [f685fd9050](https://linux-hardware.org/?probe=f685fd9050) | Nov 20, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [c22dce3d23](https://linux-hardware.org/?probe=c22dce3d23) | Nov 16, 2022 |
| HP            | 88BE                        | [1c03e5957d](https://linux-hardware.org/?probe=1c03e5957d) | Nov 13, 2022 |
| Gigabyte      | H110M-S2H-CF                | [da03d56b4e](https://linux-hardware.org/?probe=da03d56b4e) | Nov 07, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [4099d3c69b](https://linux-hardware.org/?probe=4099d3c69b) | Nov 05, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c35a514fe5](https://linux-hardware.org/?probe=c35a514fe5) | Nov 05, 2022 |
| Gigabyte      | Z170X-Gaming 7              | [be2ceae6ca](https://linux-hardware.org/?probe=be2ceae6ca) | Nov 05, 2022 |
| Gigabyte      | H97-HD3                     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Gigabyte      | H77-DS3H                    | [4457c6182e](https://linux-hardware.org/?probe=4457c6182e) | Oct 29, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| Gigabyte      | X79-UP4                     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | PRIME H270-PRO              | [b98f2dc115](https://linux-hardware.org/?probe=b98f2dc115) | Oct 08, 2022 |
| Dell          | 014GRG A01                  | [05a023826f](https://linux-hardware.org/?probe=05a023826f) | Oct 06, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| Dell          | 06D7TR A02                  | [a0d832ff6a](https://linux-hardware.org/?probe=a0d832ff6a) | Sep 28, 2022 |
| ASUSTek       | Rampage II Extreme          | [c996a3c4dd](https://linux-hardware.org/?probe=c996a3c4dd) | Sep 19, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [4d7948b375](https://linux-hardware.org/?probe=4d7948b375) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [1e4d0a6189](https://linux-hardware.org/?probe=1e4d0a6189) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | 0CRH6C A01                  | [d4a37f016b](https://linux-hardware.org/?probe=d4a37f016b) | Sep 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| HP            | 18E7                        | [f1c1f9c891](https://linux-hardware.org/?probe=f1c1f9c891) | Aug 12, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [06d2014c22](https://linux-hardware.org/?probe=06d2014c22) | Aug 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| ASUSTek       | P7H55-M PRO                 | [5708a69dc1](https://linux-hardware.org/?probe=5708a69dc1) | Jun 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [150ea72986](https://linux-hardware.org/?probe=150ea72986) | Jun 23, 2022 |
| MSI           | Z170A KRAIT GAMING          | [7f2adf56e4](https://linux-hardware.org/?probe=7f2adf56e4) | Jun 21, 2022 |
| Foxconn       | H81MXV FAB A                | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Lenovo        | ThinkCentre M81 5049W15     | [df4917e32f](https://linux-hardware.org/?probe=df4917e32f) | May 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [7ba08ba4b5](https://linux-hardware.org/?probe=7ba08ba4b5) | May 21, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [81aa40219e](https://linux-hardware.org/?probe=81aa40219e) | May 21, 2022 |
| HP            | 8298                        | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Gigabyte      | Z170X-Gaming 7              | [813349f89b](https://linux-hardware.org/?probe=813349f89b) | May 17, 2022 |
| Intel         | DH77EB AAG39073-304         | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| ASUSTek       | D540MA-C                    | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Lenovo        | NO DPK                      | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| MSI           | H61M-E22                    | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| ASUSTek       | Z97-DELUXE                  | [8b2771b584](https://linux-hardware.org/?probe=8b2771b584) | Mar 07, 2022 |
| ASUSTek       | H97M-E                      | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [1398ef93be](https://linux-hardware.org/?probe=1398ef93be) | Feb 22, 2022 |
| Dell          | 0WN7Y6 A01                  | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| ASRock        | B450 Pro4                   | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [9295ca6d10](https://linux-hardware.org/?probe=9295ca6d10) | Feb 13, 2022 |
| Gigabyte      | H55M-D2H                    | [f85ece5bf7](https://linux-hardware.org/?probe=f85ece5bf7) | Feb 12, 2022 |
| Gigabyte      | B460M DS3H                  | [136ea58ce8](https://linux-hardware.org/?probe=136ea58ce8) | Feb 11, 2022 |
| Shuttle       | FH87                        | [1588ed0352](https://linux-hardware.org/?probe=1588ed0352) | Feb 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518NR8    | [cc2ea0bba2](https://linux-hardware.org/?probe=cc2ea0bba2) | Feb 08, 2022 |
| HP            | 2B34                        | [a44a14f358](https://linux-hardware.org/?probe=a44a14f358) | Feb 08, 2022 |
| Alienware     | 07W25T A00                  | [0bd0a24a20](https://linux-hardware.org/?probe=0bd0a24a20) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | [852eb2b367](https://linux-hardware.org/?probe=852eb2b367) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M91p 4524B96    | [5a90acd016](https://linux-hardware.org/?probe=5a90acd016) | Jan 31, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| Gigabyte      | B460 HD3                    | [48e8e52d84](https://linux-hardware.org/?probe=48e8e52d84) | Jan 13, 2022 |
| ASUSTek       | PRIME B560M-K               | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Supermicro    | X9DAi                       | [0f78e87ab1](https://linux-hardware.org/?probe=0f78e87ab1) | Jan 03, 2022 |
| Supermicro    | X9DAi                       | [a86bdc7f4d](https://linux-hardware.org/?probe=a86bdc7f4d) | Jan 03, 2022 |
| Gigabyte      | B75M-D3V                    | [0f43701ca4](https://linux-hardware.org/?probe=0f43701ca4) | Dec 20, 2021 |
| Gigabyte      | P55-UD3L                    | [6d2be9add8](https://linux-hardware.org/?probe=6d2be9add8) | Dec 17, 2021 |
| AZW           | U59                         | [021639604a](https://linux-hardware.org/?probe=021639604a) | Dec 15, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| ASUSTek       | PRIME B560M-K               | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| Gigabyte      | H87-D3H-CF                  | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Gigabyte      | B460 HD3                    | [19bfb20536](https://linux-hardware.org/?probe=19bfb20536) | Nov 19, 2021 |
| ASRock        | H370M Pro4                  | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| Gigabyte      | B560M H                     | [358ab5a9fe](https://linux-hardware.org/?probe=358ab5a9fe) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| Gigabyte      | B560M DS3H                  | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek       | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
| Dell          | 0XHGV1 A00                  | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| Dell          | 0V8F20 A01                  | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| MSI           | G41TM-P33                   | [8216f8bfae](https://linux-hardware.org/?probe=8216f8bfae) | Oct 24, 2021 |
| Foxconn       | H81MXV FAB A                | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| ASUSTek       | Z170-K                      | [b39ed56cc9](https://linux-hardware.org/?probe=b39ed56cc9) | Oct 19, 2021 |
| Gigabyte      | G31M-ES2L                   | [aa3b1b645e](https://linux-hardware.org/?probe=aa3b1b645e) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | [e3149252a0](https://linux-hardware.org/?probe=e3149252a0) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | [b78fec94ab](https://linux-hardware.org/?probe=b78fec94ab) | Oct 16, 2021 |
| Dell          | 0XHGV1 A00                  | [853a82796c](https://linux-hardware.org/?probe=853a82796c) | Oct 15, 2021 |
| ASUSTek       | PRIME Z390-A                | [f86adc0f8d](https://linux-hardware.org/?probe=f86adc0f8d) | Oct 12, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| HP            | 1497                        | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| ASUSTek       | H81M-E R2.0                 | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| ITI LIMITE... | SMAASH XU3i                 | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| ASUSTek       | Z170-K                      | [e5e1953ed8](https://linux-hardware.org/?probe=e5e1953ed8) | Sep 05, 2021 |
| HP            | 158A                        | [6c22e51bfc](https://linux-hardware.org/?probe=6c22e51bfc) | Sep 04, 2021 |
| Dell          | 06X1TJ A00                  | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| ASUSTek       | PRIME Z370-P II             | [68213450a7](https://linux-hardware.org/?probe=68213450a7) | Aug 14, 2021 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| Gigabyte      | X58-USB3                    | [8a48f8d2bc](https://linux-hardware.org/?probe=8a48f8d2bc) | Jul 31, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| ASUSTek       | P8P67 DELUXE                | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| Dell          | 06X1TJ A00                  | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell          | 06X1TJ A00                  | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| Dell          | 06X1TJ A00                  | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell          | 0GMM0G A00                  | [2c9050ccd9](https://linux-hardware.org/?probe=2c9050ccd9) | Jul 03, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| Pegatron      | 2A94h                       | [5475faba11](https://linux-hardware.org/?probe=5475faba11) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| Gigabyte      | B360M HD3                   | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| ASUSTek       | PRIME Z490-P                | [59cf3396c0](https://linux-hardware.org/?probe=59cf3396c0) | Jun 13, 2021 |
| ASRock        | H370M Pro4                  | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| ASUSTek       | PRIME X470-PRO              | [aea7394e24](https://linux-hardware.org/?probe=aea7394e24) | Jun 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Intel         | DP55WB AAE64798-205         | [a760607f4e](https://linux-hardware.org/?probe=a760607f4e) | May 27, 2021 |
| Gigabyte      | B450 AORUS M                | [a7a67287a3](https://linux-hardware.org/?probe=a7a67287a3) | May 26, 2021 |
| Intel         | DP55WB AAE64798-205         | [7070bcfa9a](https://linux-hardware.org/?probe=7070bcfa9a) | May 24, 2021 |
| Gigabyte      | H61M-S1                     | [2f7da43eb2](https://linux-hardware.org/?probe=2f7da43eb2) | May 23, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
| Gigabyte      | H81M-S2PV                   | [c8a2e1e897](https://linux-hardware.org/?probe=c8a2e1e897) | May 06, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [e0e3552e96](https://linux-hardware.org/?probe=e0e3552e96) | Apr 28, 2021 |
| ASRock        | H370M Pro4                  | [be75ff3da4](https://linux-hardware.org/?probe=be75ff3da4) | Apr 25, 2021 |
| HP            | 3397                        | [08ea9bb12b](https://linux-hardware.org/?probe=08ea9bb12b) | Apr 22, 2021 |
| Gigabyte      | G41MT-S2                    | [0752e29519](https://linux-hardware.org/?probe=0752e29519) | Apr 21, 2021 |
| Gigabyte      | G41MT-S2                    | [6dd3daccc6](https://linux-hardware.org/?probe=6dd3daccc6) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| ASUSTek       | PRIME B365M-A               | [c5109bab9c](https://linux-hardware.org/?probe=c5109bab9c) | Apr 17, 2021 |
| ASUSTek       | PRIME B250M-A               | [95f2d11b2e](https://linux-hardware.org/?probe=95f2d11b2e) | Apr 16, 2021 |
| ASUSTek       | D540MA-C                    | [945b05bee8](https://linux-hardware.org/?probe=945b05bee8) | Apr 16, 2021 |
| ASRock        | H370M Pro4                  | [e6b5c6b72b](https://linux-hardware.org/?probe=e6b5c6b72b) | Apr 11, 2021 |
| ASUSTek       | H97M-E                      | [9881ce611d](https://linux-hardware.org/?probe=9881ce611d) | Apr 09, 2021 |
| ASUSTek       | M5A97 R2.0                  | [a5823c243c](https://linux-hardware.org/?probe=a5823c243c) | Apr 02, 2021 |
| MSI           | H87-G43 GAMING              | [5bd49fbcea](https://linux-hardware.org/?probe=5bd49fbcea) | Mar 28, 2021 |
| Gigabyte      | G31M-S2C                    | [8d84b967f2](https://linux-hardware.org/?probe=8d84b967f2) | Mar 25, 2021 |
| Gigabyte      | G31M-S2C                    | [91a8d56cfd](https://linux-hardware.org/?probe=91a8d56cfd) | Mar 25, 2021 |
| Gigabyte      | G41M-Combo                  | [feb8706c98](https://linux-hardware.org/?probe=feb8706c98) | Mar 18, 2021 |
| ASRock        | H71M-DGS                    | [30424c4317](https://linux-hardware.org/?probe=30424c4317) | Mar 18, 2021 |
| MSI           | H170A GAMING PRO            | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Gigabyte      | Z490M                       | [6eecc1d3cc](https://linux-hardware.org/?probe=6eecc1d3cc) | Mar 15, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | [0fbdab8514](https://linux-hardware.org/?probe=0fbdab8514) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | [7140c5ee85](https://linux-hardware.org/?probe=7140c5ee85) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | [93a598b2c2](https://linux-hardware.org/?probe=93a598b2c2) | Mar 11, 2021 |
| Intel         | DG43RK AAE78175-403         | [942660dca5](https://linux-hardware.org/?probe=942660dca5) | Mar 11, 2021 |
| Gigabyte      | G41M-Combo                  | [2d19cc5e17](https://linux-hardware.org/?probe=2d19cc5e17) | Mar 11, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | [99082a91ac](https://linux-hardware.org/?probe=99082a91ac) | Mar 11, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [1e4054e9fe](https://linux-hardware.org/?probe=1e4054e9fe) | Mar 09, 2021 |
| Gigabyte      | H81-D3                      | [d05b1b3efc](https://linux-hardware.org/?probe=d05b1b3efc) | Feb 22, 2021 |
| ASRock        | H77M                        | [eb7af012c2](https://linux-hardware.org/?probe=eb7af012c2) | Feb 19, 2021 |
| Gigabyte      | G31M-S2C                    | [c2bd3800b7](https://linux-hardware.org/?probe=c2bd3800b7) | Feb 18, 2021 |
| ASUSTek       | PRIME Z370-P II             | [95fc52db78](https://linux-hardware.org/?probe=95fc52db78) | Feb 17, 2021 |
| Dell          | 0M9KCM A02                  | [802f6994df](https://linux-hardware.org/?probe=802f6994df) | Feb 16, 2021 |
| ASUSTek       | P7H55-M PRO                 | [aead87bf38](https://linux-hardware.org/?probe=aead87bf38) | Feb 14, 2021 |
| Lenovo        | 3176 NOK                    | [c5216ce396](https://linux-hardware.org/?probe=c5216ce396) | Feb 14, 2021 |
| MSI           | B150M BAZOOKA               | [66af036f49](https://linux-hardware.org/?probe=66af036f49) | Feb 13, 2021 |
| MSI           | B150M BAZOOKA               | [749beaf127](https://linux-hardware.org/?probe=749beaf127) | Feb 13, 2021 |
| Gigabyte      | B460M D3H                   | [8cdafac5a3](https://linux-hardware.org/?probe=8cdafac5a3) | Feb 13, 2021 |
| ASUSTek       | H110M-A/M.2                 | [351477b72b](https://linux-hardware.org/?probe=351477b72b) | Feb 13, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [3e8ad6be09](https://linux-hardware.org/?probe=3e8ad6be09) | Feb 10, 2021 |
| ASRock        | Z490M-ITX/ac                | [586d4a5a82](https://linux-hardware.org/?probe=586d4a5a82) | Feb 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [017e9abf15](https://linux-hardware.org/?probe=017e9abf15) | Feb 04, 2021 |
| ASUSTek       | H81M-K                      | [e6be0abafb](https://linux-hardware.org/?probe=e6be0abafb) | Jan 28, 2021 |
| Gigabyte      | H97M-D3H                    | [cc4593764d](https://linux-hardware.org/?probe=cc4593764d) | Jan 18, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [725729e04e](https://linux-hardware.org/?probe=725729e04e) | Jan 13, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [9c40fd9781](https://linux-hardware.org/?probe=9c40fd9781) | Jan 13, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [4723903be4](https://linux-hardware.org/?probe=4723903be4) | Jan 11, 2021 |
| Gigabyte      | P55-UD3L                    | [8c6a5c5e60](https://linux-hardware.org/?probe=8c6a5c5e60) | Jan 10, 2021 |
| ASRock        | H97M Anniversary            | [b630702ecc](https://linux-hardware.org/?probe=b630702ecc) | Jan 10, 2021 |
| Gigabyte      | G41M-ES2L                   | [2583ebac59](https://linux-hardware.org/?probe=2583ebac59) | Jan 08, 2021 |
| Gigabyte      | H81M-D2V                    | [b7c82c53b6](https://linux-hardware.org/?probe=b7c82c53b6) | Jan 07, 2021 |
| Unknown       | G41 Series                  | [578bc526ef](https://linux-hardware.org/?probe=578bc526ef) | Jan 06, 2021 |
| Unknown       | G41 Series                  | [5a6543b6f1](https://linux-hardware.org/?probe=5a6543b6f1) | Jan 03, 2021 |
| Gigabyte      | Z390 UD                     | [b4ebedb0e2](https://linux-hardware.org/?probe=b4ebedb0e2) | Dec 18, 2020 |
| ASUSTek       | H97M-E                      | [4f0b22ee7f](https://linux-hardware.org/?probe=4f0b22ee7f) | Nov 30, 2020 |
| MSI           | X470 GAMING PLUS            | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| Gigabyte      | Z270X-UD5-CF                | [f65b9a326b](https://linux-hardware.org/?probe=f65b9a326b) | Nov 21, 2020 |
| Gigabyte      | Z270X-UD5-CF                | [8f674b7608](https://linux-hardware.org/?probe=8f674b7608) | Nov 21, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [c42752eed3](https://linux-hardware.org/?probe=c42752eed3) | Nov 19, 2020 |
| ASUSTek       | P9X79 LE                    | [1674d3318e](https://linux-hardware.org/?probe=1674d3318e) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | [0ae9d90f3f](https://linux-hardware.org/?probe=0ae9d90f3f) | Nov 18, 2020 |
| Gigabyte      | H61M-S2PV                   | [accc9c10e5](https://linux-hardware.org/?probe=accc9c10e5) | Nov 16, 2020 |
| Gigabyte      | H61M-S2PV                   | [1c3bd52baa](https://linux-hardware.org/?probe=1c3bd52baa) | Nov 05, 2020 |
| Gigabyte      | H61M-S2PV                   | [1b6972fae9](https://linux-hardware.org/?probe=1b6972fae9) | Nov 05, 2020 |
| Dell          | 0CU409                      | [6adb83b2e0](https://linux-hardware.org/?probe=6adb83b2e0) | Nov 04, 2020 |
| Lenovo        | ThinkCentre A58 751581G     | [987ed81d7d](https://linux-hardware.org/?probe=987ed81d7d) | Nov 03, 2020 |
| Dell          | 0KWVT8 A02                  | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| Dell          | 0DR845                      | [c59e7b1e56](https://linux-hardware.org/?probe=c59e7b1e56) | Nov 01, 2020 |
| ASUSTek       | H110M-A                     | [f8fa4c9c31](https://linux-hardware.org/?probe=f8fa4c9c31) | Nov 01, 2020 |
| Dell          | 0KP561                      | [da357993dd](https://linux-hardware.org/?probe=da357993dd) | Oct 31, 2020 |
| Dell          | 0KP561                      | [b14be76868](https://linux-hardware.org/?probe=b14be76868) | Oct 31, 2020 |
| HP            | 158A                        | [f83412f912](https://linux-hardware.org/?probe=f83412f912) | Oct 27, 2020 |
| ASUSTek       | PRIME X470-PRO              | [5bd58e33be](https://linux-hardware.org/?probe=5bd58e33be) | Oct 27, 2020 |
| HP            | 82B4                        | [d98d676e9c](https://linux-hardware.org/?probe=d98d676e9c) | Oct 26, 2020 |
| ASUSTek       | PRIME B350M-A               | [7c9e9b741c](https://linux-hardware.org/?probe=7c9e9b741c) | Oct 25, 2020 |
| ASUSTek       | PRIME X570-PRO              | [d3f4deffa5](https://linux-hardware.org/?probe=d3f4deffa5) | Oct 25, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [6ba76947d7](https://linux-hardware.org/?probe=6ba76947d7) | Oct 18, 2020 |
| ASUSTek       | PRIME Z490-P                | [44d70b326c](https://linux-hardware.org/?probe=44d70b326c) | Oct 13, 2020 |
| Gigabyte      | B360M HD3                   | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | [986a5e604f](https://linux-hardware.org/?probe=986a5e604f) | Oct 03, 2020 |
| ASRock        | X399 Taichi                 | [268a9d5625](https://linux-hardware.org/?probe=268a9d5625) | Oct 01, 2020 |
| ASUSTek       | P5G41C-M LX                 | [353229fd96](https://linux-hardware.org/?probe=353229fd96) | Sep 29, 2020 |
| Unknown       | Unknown                     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| ASRock        | H97M Anniversary            | [cc0e0f5c04](https://linux-hardware.org/?probe=cc0e0f5c04) | Sep 29, 2020 |
| MSI           | G41M-E43                    | [5a567b1f97](https://linux-hardware.org/?probe=5a567b1f97) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | [5d73c67b98](https://linux-hardware.org/?probe=5d73c67b98) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | [9c9f5b4cfa](https://linux-hardware.org/?probe=9c9f5b4cfa) | Sep 10, 2020 |
| Gigabyte      | B360M HD3                   | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| HP            | 339A                        | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [42deb7cee5](https://linux-hardware.org/?probe=42deb7cee5) | Sep 03, 2020 |
| ASUSTek       | PRIME Z370-P                | [5bfd2a1403](https://linux-hardware.org/?probe=5bfd2a1403) | Sep 03, 2020 |
| MSI           | 2A9Ch                       | [aa629696b3](https://linux-hardware.org/?probe=aa629696b3) | Aug 28, 2020 |
| MSI           | 2A9Ch                       | [0ece5d52d2](https://linux-hardware.org/?probe=0ece5d52d2) | Aug 27, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [56afe1e282](https://linux-hardware.org/?probe=56afe1e282) | Aug 27, 2020 |
| ASRock        | H97M Anniversary            | [613aba4134](https://linux-hardware.org/?probe=613aba4134) | Aug 23, 2020 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a114ae9c9c](https://linux-hardware.org/?probe=a114ae9c9c) | Aug 12, 2020 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | [1828dedb7f](https://linux-hardware.org/?probe=1828dedb7f) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | [0d864b4feb](https://linux-hardware.org/?probe=0d864b4feb) | Aug 08, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | [69e782093d](https://linux-hardware.org/?probe=69e782093d) | Aug 08, 2020 |
| Gigabyte      | Z270-HD3P-CF                | [3fe0ec39fc](https://linux-hardware.org/?probe=3fe0ec39fc) | Aug 07, 2020 |
| ASRock        | H55M                        | [f2d0fa78ac](https://linux-hardware.org/?probe=f2d0fa78ac) | Aug 06, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5c3dc530c3](https://linux-hardware.org/?probe=5c3dc530c3) | Aug 04, 2020 |
| Gigabyte      | Z97-HD3                     | [2e41ce3f03](https://linux-hardware.org/?probe=2e41ce3f03) | Jul 31, 2020 |
| Gigabyte      | Z97-HD3                     | [50888e0851](https://linux-hardware.org/?probe=50888e0851) | Jul 31, 2020 |
| ASRock        | H55M                        | [dcbc0735f5](https://linux-hardware.org/?probe=dcbc0735f5) | Jul 30, 2020 |
| ASUSTek       | P8H67-M PRO                 | [a7e0318966](https://linux-hardware.org/?probe=a7e0318966) | Jul 30, 2020 |
| ASUSTek       | AT3N7A-I                    | [57c3ce82b7](https://linux-hardware.org/?probe=57c3ce82b7) | Jul 29, 2020 |
| Hardkernel    | ODROID-H2                   | [c86e7dc968](https://linux-hardware.org/?probe=c86e7dc968) | Jul 23, 2020 |
| Gigabyte      | H61M-S1                     | [2a63a11959](https://linux-hardware.org/?probe=2a63a11959) | Jul 08, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte      | G31M-S2C                    | [da847897f9](https://linux-hardware.org/?probe=da847897f9) | Jun 15, 2020 |
| MSI           | G41M-E43                    | [4c72170ef6](https://linux-hardware.org/?probe=4c72170ef6) | Jun 06, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [48f5173ede](https://linux-hardware.org/?probe=48f5173ede) | May 27, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [72b226183e](https://linux-hardware.org/?probe=72b226183e) | May 27, 2020 |
| ASUSTek       | F2A85-M PRO                 | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [bd5ec5436e](https://linux-hardware.org/?probe=bd5ec5436e) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [355e03bb68](https://linux-hardware.org/?probe=355e03bb68) | May 15, 2020 |
| HP            | 339A                        | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [c815568345](https://linux-hardware.org/?probe=c815568345) | May 14, 2020 |
| ASUSTek       | F2A85-M PRO                 | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [fc58b96f3e](https://linux-hardware.org/?probe=fc58b96f3e) | May 01, 2020 |
| Gigabyte      | B450M S2H                   | [0fe3c99d58](https://linux-hardware.org/?probe=0fe3c99d58) | Apr 30, 2020 |
| MSI           | G41TM-P33                   | [d1078cd496](https://linux-hardware.org/?probe=d1078cd496) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | [3512230c03](https://linux-hardware.org/?probe=3512230c03) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | [a648a57d33](https://linux-hardware.org/?probe=a648a57d33) | Apr 28, 2020 |
| Gigabyte      | Z270XP-SLI-CF               | [20f18f18b8](https://linux-hardware.org/?probe=20f18f18b8) | Apr 27, 2020 |
| Dell          | 097YXY A00                  | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| MSI           | G41TM-P33                   | [d99b7f2578](https://linux-hardware.org/?probe=d99b7f2578) | Apr 22, 2020 |
| Gigabyte      | H61M-S1                     | [ade023408c](https://linux-hardware.org/?probe=ade023408c) | Mar 26, 2020 |
| MSI           | B450-A PRO                  | [f9c1a4dd5d](https://linux-hardware.org/?probe=f9c1a4dd5d) | Mar 25, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [e02dd36f39](https://linux-hardware.org/?probe=e02dd36f39) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [5c3ecb2c5b](https://linux-hardware.org/?probe=5c3ecb2c5b) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [1004ffcce5](https://linux-hardware.org/?probe=1004ffcce5) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [e0f2c8f133](https://linux-hardware.org/?probe=e0f2c8f133) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [03d86fb8e8](https://linux-hardware.org/?probe=03d86fb8e8) | Mar 21, 2020 |
| ASUSTek       | PRIME B450M-A               | [a53152418d](https://linux-hardware.org/?probe=a53152418d) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | [32428dda92](https://linux-hardware.org/?probe=32428dda92) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | [5d56415e4c](https://linux-hardware.org/?probe=5d56415e4c) | Mar 14, 2020 |
| Gigabyte      | Q87M-D2H                    | [48afe5fac3](https://linux-hardware.org/?probe=48afe5fac3) | Mar 08, 2020 |
| ASUSTek       | H81M-K                      | [08d45d3162](https://linux-hardware.org/?probe=08d45d3162) | Mar 07, 2020 |
| HP            | 1495                        | [ff4447983a](https://linux-hardware.org/?probe=ff4447983a) | Feb 22, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [72475e5edb](https://linux-hardware.org/?probe=72475e5edb) | Feb 22, 2020 |
| HP            | 1495                        | [e1d927d5ce](https://linux-hardware.org/?probe=e1d927d5ce) | Feb 16, 2020 |
| HP            | 1495                        | [c9e7f762e4](https://linux-hardware.org/?probe=c9e7f762e4) | Feb 16, 2020 |
| Gigabyte      | H110M-DS2 DDR3-CF           | [e2a558c35b](https://linux-hardware.org/?probe=e2a558c35b) | Feb 11, 2020 |
| MSI           | G41TM-P33                   | [524089d286](https://linux-hardware.org/?probe=524089d286) | Jan 29, 2020 |
| Pegatron      | NARRA5                      | [f0bd8ead24](https://linux-hardware.org/?probe=f0bd8ead24) | Jan 17, 2020 |
| ASRock        | H97M Anniversary            | [221a2cfac8](https://linux-hardware.org/?probe=221a2cfac8) | Jan 13, 2020 |
| Dell          | 0GM819                      | [d99391a30c](https://linux-hardware.org/?probe=d99391a30c) | Jan 06, 2020 |
| ASUSTek       | M2N-MX SE Plus              | [f3b22a675a](https://linux-hardware.org/?probe=f3b22a675a) | Dec 20, 2019 |
| ASUSTek       | A88XM-A/USB                 | [8f93bf715a](https://linux-hardware.org/?probe=8f93bf715a) | Dec 11, 2019 |
| ASRock        | H97M Anniversary            | [831ff4b7fc](https://linux-hardware.org/?probe=831ff4b7fc) | Dec 10, 2019 |
| Gigabyte      | F2A88XM-D3H                 | [8fbc16ebfa](https://linux-hardware.org/?probe=8fbc16ebfa) | Dec 03, 2019 |
| Gigabyte      | H170-HD3-CF                 | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASRock        | G41C-GS                     | [920a88f615](https://linux-hardware.org/?probe=920a88f615) | Nov 08, 2019 |
| HP            | 2B38                        | [8a919fff76](https://linux-hardware.org/?probe=8a919fff76) | Oct 26, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [6d5ea39af4](https://linux-hardware.org/?probe=6d5ea39af4) | Oct 26, 2019 |
| Dell          | 0GM819                      | [4468e2e57e](https://linux-hardware.org/?probe=4468e2e57e) | Oct 21, 2019 |
| Gigabyte      | Z87MX-D3H-CF                | [8a9e5f7293](https://linux-hardware.org/?probe=8a9e5f7293) | Oct 14, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [cafdeb1b3a](https://linux-hardware.org/?probe=cafdeb1b3a) | Oct 06, 2019 |
| HP            | 2B38                        | [f690313ecf](https://linux-hardware.org/?probe=f690313ecf) | Sep 30, 2019 |
| ASUSTek       | PRIME X370-PRO              | [2ad6f6b23d](https://linux-hardware.org/?probe=2ad6f6b23d) | Sep 25, 2019 |
| AMI           | Cherry Trail CR             | [0398059e29](https://linux-hardware.org/?probe=0398059e29) | Sep 16, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [3bfc472643](https://linux-hardware.org/?probe=3bfc472643) | Sep 15, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d90225cad7](https://linux-hardware.org/?probe=d90225cad7) | Sep 15, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [c090add0c0](https://linux-hardware.org/?probe=c090add0c0) | Sep 04, 2019 |
| Dell          | 0GM819                      | [863ec2a484](https://linux-hardware.org/?probe=863ec2a484) | Sep 02, 2019 |
| Dell          | 0GM819                      | [7bf21b409d](https://linux-hardware.org/?probe=7bf21b409d) | Sep 02, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [f6c7aa7735](https://linux-hardware.org/?probe=f6c7aa7735) | Sep 02, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | [b1fb625f3d](https://linux-hardware.org/?probe=b1fb625f3d) | Aug 26, 2019 |
| Dell          | 0CKCXH A04                  | [2679a50fe1](https://linux-hardware.org/?probe=2679a50fe1) | Aug 24, 2019 |
| Gigabyte      | H55M-S2H                    | [2479a0b0c9](https://linux-hardware.org/?probe=2479a0b0c9) | Aug 24, 2019 |
| Gigabyte      | J1800N-D2H                  | [616bb81d97](https://linux-hardware.org/?probe=616bb81d97) | Aug 17, 2019 |
| Foxconn       | 2A8C                        | [54cbeed66e](https://linux-hardware.org/?probe=54cbeed66e) | Jul 10, 2019 |
| ASUSTek       | TUF X470-PLUS GAMING        | [10a2ff392a](https://linux-hardware.org/?probe=10a2ff392a) | Jul 09, 2019 |
| Gigabyte      | H57M-USB3                   | [10ba468b45](https://linux-hardware.org/?probe=10ba468b45) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | [0b6b3550b5](https://linux-hardware.org/?probe=0b6b3550b5) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | [a920b40c9f](https://linux-hardware.org/?probe=a920b40c9f) | Jul 01, 2019 |
| Dell          | 0GDG8Y A00                  | [4f0fb75146](https://linux-hardware.org/?probe=4f0fb75146) | Jun 20, 2019 |
| ASRock        | H110M-ITX/ac                | [6f2ecbf51c](https://linux-hardware.org/?probe=6f2ecbf51c) | Jun 04, 2019 |
| Gigabyte      | H97-HD3                     | [64e47e9922](https://linux-hardware.org/?probe=64e47e9922) | May 28, 2019 |
| Gigabyte      | X58A-UD3R                   | [112dc8e71a](https://linux-hardware.org/?probe=112dc8e71a) | May 23, 2019 |
| ASUSTek       | H110M-K                     | [c736db6599](https://linux-hardware.org/?probe=c736db6599) | May 01, 2019 |
| ASUSTek       | H110M-K                     | [109947ebc6](https://linux-hardware.org/?probe=109947ebc6) | May 01, 2019 |
| ASUSTek       | H110M-A/M.2                 | [05fcc6199e](https://linux-hardware.org/?probe=05fcc6199e) | Apr 21, 2019 |
| ASUSTek       | P7H55-M PRO                 | [f8a69693bc](https://linux-hardware.org/?probe=f8a69693bc) | Mar 30, 2019 |
| Biostar       | H61MLV2                     | [19146b787b](https://linux-hardware.org/?probe=19146b787b) | Mar 28, 2019 |
| Gigabyte      | H97M-HD3                    | [a6818d6761](https://linux-hardware.org/?probe=a6818d6761) | Mar 20, 2019 |
| Gigabyte      | F2A88XM-HD3                 | [b1e21a522f](https://linux-hardware.org/?probe=b1e21a522f) | Feb 26, 2019 |
| ASUSTek       | H81M-K                      | [569fd85150](https://linux-hardware.org/?probe=569fd85150) | Dec 05, 2018 |
| Gigabyte      | H370 HD3-CF                 | [ac7a7dc15b](https://linux-hardware.org/?probe=ac7a7dc15b) | Nov 13, 2018 |
| ASUSTek       | Z87-K                       | [1d8a707c72](https://linux-hardware.org/?probe=1d8a707c72) | Sep 11, 2018 |
| Gigabyte      | Z170MX-Gaming 5             | [935991dc2b](https://linux-hardware.org/?probe=935991dc2b) | May 04, 2018 |
| ASUSTek       | P7H55-M PRO                 | [d147cce967](https://linux-hardware.org/?probe=d147cce967) | Dec 06, 2017 |
| ASUSTek       | M5A87                       | [242554d0b3](https://linux-hardware.org/?probe=242554d0b3) | Apr 27, 2017 |
| ASRock        | G41C-GS                     | [ff9333f313](https://linux-hardware.org/?probe=ff9333f313) | Apr 13, 2017 |
| ASUSTek       | M5A87                       | [bbe4de9927](https://linux-hardware.org/?probe=bbe4de9927) | Apr 07, 2017 |
| Gigabyte      | Z170MX-Gaming 5             | [10108844b5](https://linux-hardware.org/?probe=10108844b5) | Mar 17, 2017 |
| ASUSTek       | M5A87                       | [653cce33bd](https://linux-hardware.org/?probe=653cce33bd) | Mar 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | [c869336270](https://linux-hardware.org/?probe=c869336270) | Jan 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | [c7554e6e05](https://linux-hardware.org/?probe=c7554e6e05) | Jan 14, 2017 |
| MSI           | G41TM-P33                   | [dd04fa411c](https://linux-hardware.org/?probe=dd04fa411c) | Dec 12, 2016 |
| ASUSTek       | P7H55-M PRO                 | [0a729a3728](https://linux-hardware.org/?probe=0a729a3728) | Oct 07, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 52       | 17.57%  |
| Ubuntu 18.04                 | 24       | 8.11%   |
| OpenMandriva 4.2             | 14       | 4.73%   |
| OpenMandriva 4.3             | 11       | 3.72%   |
| ROSA R11                     | 9        | 3.04%   |
| Ubuntu 19.04                 | 8        | 2.7%    |
| Manjaro                      | 7        | 2.36%   |
| ROSA R11.1                   | 6        | 2.03%   |
| Ubuntu 20.10                 | 5        | 1.69%   |
| Debian 11                    | 5        | 1.69%   |
| Arch Rolling                 | 5        | 1.69%   |
| Ubuntu 22.04                 | 4        | 1.35%   |
| Pop!_OS 20.04                | 4        | 1.35%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.35%   |
| OpenMandriva 23.01           | 4        | 1.35%   |
| Linux Mint 20.3              | 4        | 1.35%   |
| Linux Mint 19.3              | 4        | 1.35%   |
| Kubuntu 20.04                | 4        | 1.35%   |
| Fedora 37                    | 4        | 1.35%   |
| Fedora 36                    | 4        | 1.35%   |
| ArcoLinux Rolling            | 4        | 1.35%   |
| Ubuntu 23.04                 | 3        | 1.01%   |
| Ubuntu 19.10                 | 3        | 1.01%   |
| Ubuntu 16.04                 | 3        | 1.01%   |
| ROSA R8.1                    | 3        | 1.01%   |
| ROSA R8                      | 3        | 1.01%   |
| ROSA R10                     | 3        | 1.01%   |
| Pop!_OS 21.10                | 3        | 1.01%   |
| Linux Mint 21.1              | 3        | 1.01%   |
| Linux Mint 20.2              | 3        | 1.01%   |
| Linux Mint 20.1              | 3        | 1.01%   |
| KDE neon 20.04               | 3        | 1.01%   |
| Zorin 16                     | 2        | 0.68%   |
| Xubuntu 20.04                | 2        | 0.68%   |
| Xubuntu 18.04                | 2        | 0.68%   |
| Ubuntu Unity 20.04           | 2        | 0.68%   |
| Ubuntu 21.10                 | 2        | 0.68%   |
| Ubuntu 21.04                 | 2        | 0.68%   |
| Rocky Linux 8.5              | 2        | 0.68%   |
| Pop!_OS 22.04                | 2        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 103      | 37.45%  |
| OpenMandriva  | 32       | 11.64%  |
| ROSA          | 21       | 7.64%   |
| Linux Mint    | 18       | 6.55%   |
| Manjaro       | 13       | 4.73%   |
| Fedora        | 13       | 4.73%   |
| Pop!_OS       | 11       | 4%      |
| Debian        | 10       | 3.64%   |
| Kubuntu       | 7        | 2.55%   |
| Arch          | 7        | 2.55%   |
| Xubuntu       | 6        | 2.18%   |
| openSUSE      | 4        | 1.45%   |
| ArcoLinux     | 4        | 1.45%   |
| Zorin         | 3        | 1.09%   |
| Ubuntu Unity  | 3        | 1.09%   |
| Rocky Linux   | 3        | 1.09%   |
| KDE neon      | 3        | 1.09%   |
| Ubuntu MATE   | 2        | 0.73%   |
| Gentoo        | 2        | 0.73%   |
| CentOS        | 2        | 0.73%   |
| Ubuntu Budgie | 1        | 0.36%   |
| SteamOS       | 1        | 0.36%   |
| Nobara        | 1        | 0.36%   |
| Garuda Linux  | 1        | 0.36%   |
| Endless       | 1        | 0.36%   |
| Elementary    | 1        | 0.36%   |
| Devuan        | 1        | 0.36%   |
| BlackPanther  | 1        | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 14       | 4.32%   |
| 5.4.0-42-generic                    | 13       | 4.01%   |
| 5.16.7-desktop-1omv4003             | 11       | 3.4%    |
| 4.15.0-desktop-45.1rosa-x86_64      | 6        | 1.85%   |
| 5.4.0-48-generic                    | 5        | 1.54%   |
| 5.11.0-37-generic                   | 5        | 1.54%   |
| 6.1.1-desktop-1omv2290              | 4        | 1.23%   |
| 5.4.0-52-generic                    | 4        | 1.23%   |
| 6.2.0-20-generic                    | 3        | 0.93%   |
| 5.8.0-55-generic                    | 3        | 0.93%   |
| 5.8.0-48-generic                    | 3        | 0.93%   |
| 5.4.0-72-generic                    | 3        | 0.93%   |
| 5.4.0-65-generic                    | 3        | 0.93%   |
| 5.15.0-47-generic                   | 3        | 0.93%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 3        | 0.93%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 3        | 0.93%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 3        | 0.93%   |
| 4.15.0-58-generic                   | 3        | 0.93%   |
| 4.15.0-50-generic                   | 3        | 0.93%   |
| 6.2.6-desktop-1omv2390              | 2        | 0.62%   |
| 5.8.0-43-generic                    | 2        | 0.62%   |
| 5.8.0-34-generic                    | 2        | 0.62%   |
| 5.8.0-25-generic                    | 2        | 0.62%   |
| 5.4.0-45-generic                    | 2        | 0.62%   |
| 5.4.0-37-generic                    | 2        | 0.62%   |
| 5.4.0-26-generic                    | 2        | 0.62%   |
| 5.4.0-131-generic                   | 2        | 0.62%   |
| 5.3.0-40-generic                    | 2        | 0.62%   |
| 5.3.0-28-generic                    | 2        | 0.62%   |
| 5.19.5-desktop-1omv4090             | 2        | 0.62%   |
| 5.16.19-76051619-generic            | 2        | 0.62%   |
| 5.15.0-60-generic                   | 2        | 0.62%   |
| 5.14.10-300.fc35.x86_64             | 2        | 0.62%   |
| 5.13.0-7620-generic                 | 2        | 0.62%   |
| 5.13.0-51-generic                   | 2        | 0.62%   |
| 5.13.0-28-generic                   | 2        | 0.62%   |
| 5.13.0-27-generic                   | 2        | 0.62%   |
| 5.11.0-40-generic                   | 2        | 0.62%   |
| 5.11.0-38-generic                   | 2        | 0.62%   |
| 5.11.0-27-generic                   | 2        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 53       | 17.67%  |
| 4.15.0  | 25       | 8.33%   |
| 5.8.0   | 20       | 6.67%   |
| 5.11.0  | 14       | 4.67%   |
| 5.10.14 | 14       | 4.67%   |
| 5.15.0  | 13       | 4.33%   |
| 5.0.0   | 13       | 4.33%   |
| 5.13.0  | 12       | 4%      |
| 5.16.7  | 11       | 3.67%   |
| 5.3.0   | 10       | 3.33%   |
| 5.10.0  | 5        | 1.67%   |
| 4.18.0  | 5        | 1.67%   |
| 6.1.1   | 4        | 1.33%   |
| 6.2.6   | 3        | 1%      |
| 6.2.0   | 3        | 1%      |
| 5.19.0  | 3        | 1%      |
| 4.9.60  | 3        | 1%      |
| 6.1.12  | 2        | 0.67%   |
| 5.9.16  | 2        | 0.67%   |
| 5.19.5  | 2        | 0.67%   |
| 5.16.19 | 2        | 0.67%   |
| 5.15.72 | 2        | 0.67%   |
| 5.14.10 | 2        | 0.67%   |
| 5.12.0  | 2        | 0.67%   |
| 5.10.74 | 2        | 0.67%   |
| 4.19.0  | 2        | 0.67%   |
| 4.1.38  | 2        | 0.67%   |
| 4.1.34  | 2        | 0.67%   |
| 3.10.0  | 2        | 0.67%   |
| 6.3.5   | 1        | 0.33%   |
| 6.2.9   | 1        | 0.33%   |
| 6.2.8   | 1        | 0.33%   |
| 6.2.15  | 1        | 0.33%   |
| 6.2.13  | 1        | 0.33%   |
| 6.1.8   | 1        | 0.33%   |
| 6.1.6   | 1        | 0.33%   |
| 6.1.31  | 1        | 0.33%   |
| 6.1.25  | 1        | 0.33%   |
| 6.1.21  | 1        | 0.33%   |
| 6.1.15  | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 18.64%  |
| 5.10    | 26       | 8.81%   |
| 4.15    | 25       | 8.47%   |
| 5.8     | 22       | 7.46%   |
| 5.15    | 22       | 7.46%   |
| 5.11    | 15       | 5.08%   |
| 5.16    | 14       | 4.75%   |
| 5.13    | 13       | 4.41%   |
| 5.0     | 13       | 4.41%   |
| 6.1     | 11       | 3.73%   |
| 6.2     | 10       | 3.39%   |
| 5.3     | 10       | 3.39%   |
| 5.9     | 6        | 2.03%   |
| 5.19    | 6        | 2.03%   |
| 4.9     | 6        | 2.03%   |
| 4.18    | 6        | 2.03%   |
| 6.0     | 5        | 1.69%   |
| 5.17    | 5        | 1.69%   |
| 4.19    | 5        | 1.69%   |
| 5.14    | 4        | 1.36%   |
| 5.12    | 4        | 1.36%   |
| 4.1     | 4        | 1.36%   |
| 3.10    | 2        | 0.68%   |
| 6.3     | 1        | 0.34%   |
| 5.7     | 1        | 0.34%   |
| 5.6     | 1        | 0.34%   |
| 5.5     | 1        | 0.34%   |
| 4.7     | 1        | 0.34%   |
| 4.4     | 1        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 261      | 98.86%  |
| i686   | 3        | 1.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| GNOME          | 105      | 37.37%  |
| KDE5           | 66       | 23.49%  |
| Unknown        | 37       | 13.17%  |
| X-Cinnamon     | 17       | 6.05%   |
| KDE4           | 17       | 6.05%   |
| XFCE           | 13       | 4.63%   |
| KDE            | 7        | 2.49%   |
| MATE           | 5        | 1.78%   |
| Unity          | 4        | 1.42%   |
| i3             | 3        | 1.07%   |
| Cinnamon       | 2        | 0.71%   |
| Pantheon       | 1        | 0.36%   |
| LXQt           | 1        | 0.36%   |
| i3-with-shmlog | 1        | 0.36%   |
| GNOME Classic  | 1        | 0.36%   |
| Budgie         | 1        | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 220      | 80.88%  |
| Wayland | 24       | 8.82%   |
| Unknown | 21       | 7.72%   |
| Tty     | 7        | 2.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 125      | 45.45%  |
| SDDM    | 57       | 20.73%  |
| GDM     | 28       | 10.18%  |
| GDM3    | 22       | 8%      |
| LightDM | 18       | 6.55%   |
| KDM     | 17       | 6.18%   |
| TDM     | 7        | 2.55%   |
| XDM     | 1        | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_IL      | 95       | 35.06%  |
| en_US      | 85       | 31.37%  |
| Unknown    | 41       | 15.13%  |
| ru_RU      | 19       | 7.01%   |
| he_IL      | 16       | 5.9%    |
| C          | 4        | 1.48%   |
| fr_FR      | 2        | 0.74%   |
| pt_BR      | 1        | 0.37%   |
| POSIX      | 1        | 0.37%   |
| es_ES      | 1        | 0.37%   |
| en_US.UTF8 | 1        | 0.37%   |
| en_GB      | 1        | 0.37%   |
| en_DK      | 1        | 0.37%   |
| en_AG      | 1        | 0.37%   |
| C.UTF8     | 1        | 0.37%   |
| aa_DJ      | 1        | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 151      | 55.31%  |
| EFI  | 122      | 44.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 195      | 71.69%  |
| Overlay | 31       | 11.4%   |
| Btrfs   | 25       | 9.19%   |
| Unknown | 9        | 3.31%   |
| Xfs     | 6        | 2.21%   |
| Tmpfs   | 3        | 1.1%    |
| Zfs     | 2        | 0.74%   |
| F2fs    | 1        | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 132      | 49.07%  |
| GPT     | 97       | 36.06%  |
| MBR     | 40       | 14.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 214      | 79.55%  |
| Yes       | 55       | 20.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 64.1%   |
| Yes       | 98       | 35.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 88       | 33.46%  |
| ASUSTek Computer    | 86       | 32.7%   |
| Dell                | 21       | 7.98%   |
| MSI                 | 13       | 4.94%   |
| Lenovo              | 12       | 4.56%   |
| Hewlett-Packard     | 12       | 4.56%   |
| ASRock              | 10       | 3.8%    |
| Intel               | 5        | 1.9%    |
| Unknown             | 3        | 1.14%   |
| Pegatron            | 2        | 0.76%   |
| Foxconn             | 2        | 0.76%   |
| Supermicro          | 1        | 0.38%   |
| Shuttle             | 1        | 0.38%   |
| ITI LIMITED         | 1        | 0.38%   |
| Huanan              | 1        | 0.38%   |
| Hardkernel          | 1        | 0.38%   |
| Biostar             | 1        | 0.38%   |
| AZW                 | 1        | 0.38%   |
| AMI                 | 1        | 0.38%   |
| Alienware           | 1        | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 9        | 3.42%   |
| MSI MS-7592                            | 3        | 1.14%   |
| Gigabyte H61M-S2PV                     | 3        | 1.14%   |
| Gigabyte H61M-S1                       | 3        | 1.14%   |
| Gigabyte G31M-ES2L                     | 3        | 1.14%   |
| ASUS P8H61-M LX R2.0                   | 3        | 1.14%   |
| ASUS H110M-A/M.2                       | 3        | 1.14%   |
| Unknown                                | 3        | 1.14%   |
| Intel DH77EB AAG39073-304              | 2        | 0.76%   |
| Gigabyte Z390 GAMING X                 | 2        | 0.76%   |
| Gigabyte X570 AORUS ULTRA              | 2        | 0.76%   |
| Gigabyte P55-UD3L                      | 2        | 0.76%   |
| Gigabyte H97-HD3                       | 2        | 0.76%   |
| Gigabyte H55M-D2H                      | 2        | 0.76%   |
| Gigabyte B460HD3                       | 2        | 0.76%   |
| Gigabyte B450M DS3H                    | 2        | 0.76%   |
| Dell OptiPlex 9020                     | 2        | 0.76%   |
| Dell OptiPlex 755                      | 2        | 0.76%   |
| Dell OptiPlex 7050                     | 2        | 0.76%   |
| ASUS TUF Gaming B550-PLUS              | 2        | 0.76%   |
| ASUS ROG STRIX Z390-E GAMING           | 2        | 0.76%   |
| ASUS ROG STRIX X570-F GAMING           | 2        | 0.76%   |
| ASUS PRIME Z490-P                      | 2        | 0.76%   |
| ASUS PRIME X470-PRO                    | 2        | 0.76%   |
| ASUS PRIME H310M-E R2.0                | 2        | 0.76%   |
| ASUS PRIME B560M-K                     | 2        | 0.76%   |
| ASUS H110M-K                           | 2        | 0.76%   |
| Supermicro X9DAi                       | 1        | 0.38%   |
| Shuttle SH87R                          | 1        | 0.38%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.38%   |
| Pegatron NC890AA-ABA a6803w            | 1        | 0.38%   |
| MSI MS-7B89                            | 1        | 0.38%   |
| MSI MS-7B86                            | 1        | 0.38%   |
| MSI MS-7B79                            | 1        | 0.38%   |
| MSI MS-7984                            | 1        | 0.38%   |
| MSI MS-7982                            | 1        | 0.38%   |
| MSI MS-7978                            | 1        | 0.38%   |
| MSI MS-7816                            | 1        | 0.38%   |
| MSI MS-7788                            | 1        | 0.38%   |
| MSI MS-7680                            | 1        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 32       | 12.17%  |
| Dell OptiPlex        | 12       | 4.56%   |
| ASUS ROG             | 11       | 4.18%   |
| ASUS All             | 9        | 3.42%   |
| Lenovo ThinkCentre   | 7        | 2.66%   |
| ASUS TUF             | 7        | 2.66%   |
| HP Compaq            | 4        | 1.52%   |
| Gigabyte Z690        | 4        | 1.52%   |
| Dell Vostro          | 4        | 1.52%   |
| ASUS H110M-A         | 4        | 1.52%   |
| MSI MS-7592          | 3        | 1.14%   |
| Lenovo V520-15IKL    | 3        | 1.14%   |
| Gigabyte Z390        | 3        | 1.14%   |
| Gigabyte X570        | 3        | 1.14%   |
| Gigabyte H61M-S2PV   | 3        | 1.14%   |
| Gigabyte H61M-S1     | 3        | 1.14%   |
| Gigabyte G31M-ES2L   | 3        | 1.14%   |
| Gigabyte B450M       | 3        | 1.14%   |
| Dell Precision       | 3        | 1.14%   |
| ASUS P8H61-M         | 3        | 1.14%   |
| Unknown              | 3        | 1.14%   |
| Intel DH77EB         | 2        | 0.76%   |
| HP Z2                | 2        | 0.76%   |
| HP ProDesk           | 2        | 0.76%   |
| Gigabyte P55-UD3L    | 2        | 0.76%   |
| Gigabyte H97-HD3     | 2        | 0.76%   |
| Gigabyte H55M-D2H    | 2        | 0.76%   |
| Gigabyte B560M       | 2        | 0.76%   |
| Gigabyte B460HD3     | 2        | 0.76%   |
| ASUS H110M-K         | 2        | 0.76%   |
| Supermicro X9DAi     | 1        | 0.38%   |
| Shuttle SH87R        | 1        | 0.38%   |
| Pegatron Pro         | 1        | 0.38%   |
| Pegatron NC890AA-ABA | 1        | 0.38%   |
| MSI MS-7B89          | 1        | 0.38%   |
| MSI MS-7B86          | 1        | 0.38%   |
| MSI MS-7B79          | 1        | 0.38%   |
| MSI MS-7984          | 1        | 0.38%   |
| MSI MS-7982          | 1        | 0.38%   |
| MSI MS-7978          | 1        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 30       | 11.41%  |
| 2012 | 29       | 11.03%  |
| 2021 | 23       | 8.75%   |
| 2020 | 20       | 7.6%    |
| 2019 | 20       | 7.6%    |
| 2014 | 20       | 7.6%    |
| 2013 | 18       | 6.84%   |
| 2010 | 17       | 6.46%   |
| 2011 | 16       | 6.08%   |
| 2017 | 15       | 5.7%    |
| 2015 | 15       | 5.7%    |
| 2016 | 14       | 5.32%   |
| 2009 | 12       | 4.56%   |
| 2008 | 5        | 1.9%    |
| 2007 | 5        | 1.9%    |
| 2022 | 3        | 1.14%   |
| 2006 | 1        | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 263      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 260      | 98.86%  |
| Enabled  | 3        | 1.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 263      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 69       | 25.46%  |
| 32.01-64.0  | 56       | 20.66%  |
| 8.01-16.0   | 51       | 18.82%  |
| 3.01-4.0    | 35       | 12.92%  |
| 4.01-8.0    | 31       | 11.44%  |
| 64.01-256.0 | 15       | 5.54%   |
| 1.01-2.0    | 9        | 3.32%   |
| 24.01-32.0  | 3        | 1.11%   |
| 2.01-3.0    | 2        | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 102      | 35.05%  |
| 2.01-3.0   | 55       | 18.9%   |
| 4.01-8.0   | 45       | 15.46%  |
| 3.01-4.0   | 32       | 11%     |
| 8.01-16.0  | 26       | 8.93%   |
| 0.51-1.0   | 22       | 7.56%   |
| 0.01-0.5   | 5        | 1.72%   |
| 24.01-32.0 | 2        | 0.69%   |
| 16.01-24.0 | 2        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 107      | 39.05%  |
| 2      | 78       | 28.47%  |
| 3      | 51       | 18.61%  |
| 4      | 19       | 6.93%   |
| 5      | 10       | 3.65%   |
| 6      | 3        | 1.09%   |
| 8      | 2        | 0.73%   |
| 7      | 2        | 0.73%   |
| 10     | 1        | 0.36%   |
| 0      | 1        | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 63.81%  |
| Yes       | 97       | 36.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 261      | 99.24%  |
| No        | 2        | 0.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 58.27%  |
| Yes       | 111      | 41.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 198      | 74.16%  |
| Yes       | 69       | 25.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Israel  | 263      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Tel Aviv            | 103      | 36.4%   |
| Ramat Gan           | 21       | 7.42%   |
| Haifa               | 21       | 7.42%   |
| Petaẖ Tiqwa       | 13       | 4.59%   |
| Rishon LeZiyyon     | 9        | 3.18%   |
| Jerusalem           | 8        | 2.83%   |
| Qiryat Ata          | 6        | 2.12%   |
| Holon               | 6        | 2.12%   |
| Rehovot             | 5        | 1.77%   |
| Ashdod              | 5        | 1.77%   |
| Ramat HaSharon      | 4        | 1.41%   |
| Netanya             | 4        | 1.41%   |
| Kfar Saba           | 4        | 1.41%   |
| Herzliya            | 4        | 1.41%   |
| Beersheba           | 4        | 1.41%   |
| Ashquelon           | 4        | 1.41%   |
| Petah Tikva         | 3        | 1.06%   |
| Ness Ziona          | 3        | 1.06%   |
| Nahariya            | 3        | 1.06%   |
| Givatayim           | 3        | 1.06%   |
| Bat Yam             | 3        | 1.06%   |
| Yehud               | 2        | 0.71%   |
| Yaqum               | 2        | 0.71%   |
| Rosh HaAyin         | 2        | 0.71%   |
| Raanana             | 2        | 0.71%   |
| Pardes Hanna Karkur | 2        | 0.71%   |
| Hod HaSharon        | 2        | 0.71%   |
| Be'er Ya'aqov       | 2        | 0.71%   |
| Afula               | 2        | 0.71%   |
| Ziqim               | 1        | 0.35%   |
| Tiberias            | 1        | 0.35%   |
| Tel Mond            | 1        | 0.35%   |
| Sderot              | 1        | 0.35%   |
| Ramla               | 1        | 0.35%   |
| Petaбє– Tiqwa   | 1        | 0.35%   |
| Petaáº– Tiqwa   | 1        | 0.35%   |
| Pardesiyya          | 1        | 0.35%   |
| Or Yehuda           | 1        | 0.35%   |
| Nazerat 'Illit      | 1        | 0.35%   |
| Meitar              | 1        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 114      | 200    | 23.12%  |
| Seagate                   | 65       | 110    | 13.18%  |
| Samsung Electronics       | 57       | 88     | 11.56%  |
| Hitachi                   | 38       | 63     | 7.71%   |
| Kingston                  | 35       | 45     | 7.1%    |
| SanDisk                   | 32       | 39     | 6.49%   |
| Toshiba                   | 22       | 27     | 4.46%   |
| Crucial                   | 18       | 31     | 3.65%   |
| Transcend                 | 12       | 15     | 2.43%   |
| Intel                     | 12       | 16     | 2.43%   |
| Corsair                   | 11       | 17     | 2.23%   |
| HGST                      | 8        | 10     | 1.62%   |
| Silicon Motion            | 6        | 6      | 1.22%   |
| XPG                       | 5        | 11     | 1.01%   |
| Phison                    | 5        | 6      | 1.01%   |
| Micron Technology         | 5        | 7      | 1.01%   |
| SK hynix                  | 4        | 4      | 0.81%   |
| A-DATA Technology         | 4        | 5      | 0.81%   |
| SPCC                      | 3        | 3      | 0.61%   |
| Micron/Crucial Technology | 3        | 3      | 0.61%   |
| China                     | 3        | 4      | 0.61%   |
| Unknown                   | 2        | 3      | 0.41%   |
| StoreJet                  | 2        | 2      | 0.41%   |
| Phison Electronics        | 2        | 3      | 0.41%   |
| OCZ                       | 2        | 2      | 0.41%   |
| Netac                     | 2        | 2      | 0.41%   |
| KIOXIA-EXCERIA            | 2        | 3      | 0.41%   |
| XrayDisk                  | 1        | 1      | 0.2%    |
| Verbatim                  | 1        | 1      | 0.2%    |
| USB3.0                    | 1        | 1      | 0.2%    |
| UMIS                      | 1        | 1      | 0.2%    |
| TPH01204000GB             | 1        | 1      | 0.2%    |
| PNY                       | 1        | 1      | 0.2%    |
| Plextor                   | 1        | 1      | 0.2%    |
| Patriot                   | 1        | 1      | 0.2%    |
| OCZ-VERTEX3               | 1        | 1      | 0.2%    |
| NGFF                      | 1        | 1      | 0.2%    |
| LS600                     | 1        | 1      | 0.2%    |
| KingSpec                  | 1        | 1      | 0.2%    |
| KingDian                  | 1        | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| SanDisk SSD PLUS 240GB           | 11       | 1.93%   |
| Hitachi HDS721050CLA362 500GB    | 10       | 1.75%   |
| WDC WD10EZEX-08WN4A0 1TB         | 8        | 1.4%    |
| Kingston SA400S37240G 240GB SSD  | 8        | 1.4%    |
| Samsung SSD 860 EVO 500GB        | 7        | 1.23%   |
| Toshiba DT01ACA100 1TB           | 6        | 1.05%   |
| Seagate ST500DM002-1BD142 500GB  | 6        | 1.05%   |
| Seagate ST2000DM008-2FR102 2TB   | 6        | 1.05%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.05%   |
| WDC WD20PURX-64P6ZY0 2TB         | 5        | 0.88%   |
| Samsung NVMe SSD Drive 500GB     | 5        | 0.88%   |
| Kingston SV300S37A120G 120GB SSD | 5        | 0.88%   |
| HGST HTS545050A7E680 500GB       | 5        | 0.88%   |
| WDC WD10EZEX-00BN5A0 1TB         | 4        | 0.7%    |
| Seagate ST2000DM001-1ER164 2TB   | 4        | 0.7%    |
| Seagate ST1000DM003-1SB102 1TB   | 4        | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 0.7%    |
| Samsung NVMe SSD Drive 1TB       | 4        | 0.7%    |
| WDC WD5000AAKX-60U6AA0 500GB     | 3        | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.53%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 3        | 0.53%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 3        | 0.53%   |
| WDC WD10EZEX-08M2NA0 1TB         | 3        | 0.53%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 0.53%   |
| WDC WD10EADS-00L5B1 1TB          | 3        | 0.53%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3        | 0.53%   |
| Toshiba DT01ACA050 500GB         | 3        | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 0.53%   |
| Seagate ST3500418AS 500GB        | 3        | 0.53%   |
| SanDisk SSD PLUS 480GB           | 3        | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.53%   |
| Samsung SSD 860 QVO 1TB          | 3        | 0.53%   |
| Kingston SUV400S37120G 120GB SSD | 3        | 0.53%   |
| Kingston SKC600256G 256GB SSD    | 3        | 0.53%   |
| Intel SSDPEKNW512G8 512GB        | 3        | 0.53%   |
| Hitachi HDS721050CLA360 500GB    | 3        | 0.53%   |
| Crucial CT250MX500SSD1 250GB     | 3        | 0.53%   |
| XPG NVMe SSD Drive 1024GB        | 2        | 0.35%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 2        | 0.35%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 2        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 107      | 186    | 43.32%  |
| Seagate             | 65       | 109    | 26.32%  |
| Hitachi             | 38       | 63     | 15.38%  |
| Toshiba             | 19       | 24     | 7.69%   |
| HGST                | 8        | 10     | 3.24%   |
| Samsung Electronics | 6        | 12     | 2.43%   |
| USB3.0              | 1        | 1      | 0.4%    |
| TPH01204000GB       | 1        | 1      | 0.4%    |
| IBM/Hitachi         | 1        | 1      | 0.4%    |
| Apple               | 1        | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 46     | 18.79%  |
| Kingston            | 29       | 36     | 17.58%  |
| SanDisk             | 25       | 32     | 15.15%  |
| Crucial             | 12       | 23     | 7.27%   |
| Transcend           | 11       | 14     | 6.67%   |
| Intel               | 9        | 11     | 5.45%   |
| Corsair             | 9        | 14     | 5.45%   |
| WDC                 | 6        | 6      | 3.64%   |
| Micron Technology   | 5        | 7      | 3.03%   |
| A-DATA Technology   | 4        | 5      | 2.42%   |
| China               | 3        | 4      | 1.82%   |
| SPCC                | 2        | 2      | 1.21%   |
| OCZ                 | 2        | 2      | 1.21%   |
| Netac               | 2        | 2      | 1.21%   |
| KIOXIA-EXCERIA      | 2        | 2      | 1.21%   |
| Verbatim            | 1        | 1      | 0.61%   |
| Toshiba             | 1        | 1      | 0.61%   |
| StoreJet            | 1        | 1      | 0.61%   |
| Seagate             | 1        | 1      | 0.61%   |
| PNY                 | 1        | 1      | 0.61%   |
| Plextor             | 1        | 1      | 0.61%   |
| Patriot             | 1        | 1      | 0.61%   |
| OCZ-VERTEX3         | 1        | 1      | 0.61%   |
| NGFF                | 1        | 1      | 0.61%   |
| LS600               | 1        | 1      | 0.61%   |
| KingSpec            | 1        | 1      | 0.61%   |
| KingDian            | 1        | 2      | 0.61%   |
| Apacer              | 1        | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 190      | 408    | 46.45%  |
| SSD     | 137      | 220    | 33.5%   |
| NVMe    | 77       | 111    | 18.83%  |
| Unknown | 4        | 5      | 0.98%   |
| MMC     | 1        | 1      | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 230      | 612    | 71.43%  |
| NVMe | 77       | 111    | 23.91%  |
| SAS  | 14       | 21     | 4.35%   |
| MMC  | 1        | 1      | 0.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 180      | 355    | 52.79%  |
| 0.51-1.0   | 85       | 134    | 24.93%  |
| 1.01-2.0   | 48       | 78     | 14.08%  |
| 3.01-4.0   | 11       | 32     | 3.23%   |
| 2.01-3.0   | 11       | 17     | 3.23%   |
| 4.01-10.0  | 5        | 7      | 1.47%   |
| 10.01-20.0 | 1        | 5      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 58       | 20.94%  |
| 251-500        | 52       | 18.77%  |
| 501-1000       | 39       | 14.08%  |
| 1001-2000      | 27       | 9.75%   |
| 2001-3000      | 26       | 9.39%   |
| More than 3000 | 24       | 8.66%   |
| 1-20           | 24       | 8.66%   |
| 21-50          | 11       | 3.97%   |
| 51-100         | 10       | 3.61%   |
| Unknown        | 6        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 120      | 41.67%  |
| 21-50          | 39       | 13.54%  |
| 101-250        | 26       | 9.03%   |
| 1001-2000      | 24       | 8.33%   |
| 251-500        | 23       | 7.99%   |
| 501-1000       | 15       | 5.21%   |
| 51-100         | 15       | 5.21%   |
| 2001-3000      | 12       | 4.17%   |
| More than 3000 | 8        | 2.78%   |
| Unknown        | 6        | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| HGST HTS545050A7E680 500GB              | 5        | 7      | 10.42%  |
| WDC WD10EARS-00Y5B1 1TB                 | 2        | 4      | 4.17%   |
| WDC WD10EADS-00L5B1 1TB                 | 2        | 2      | 4.17%   |
| Hitachi HDS721050DLE630 500GB           | 2        | 2      | 4.17%   |
| Hitachi HDS721050CLA362 500GB           | 2        | 3      | 4.17%   |
| WDC WDS240G1G0B-00RC30 240GB SSD        | 1        | 1      | 2.08%   |
| WDC WD5001AALS-00LWTA0 500GB            | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-60U6AA0 500GB            | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-221CA1 500GB             | 1        | 1      | 2.08%   |
| WDC WD5000AADS-00S9B0 500GB             | 1        | 1      | 2.08%   |
| WDC WD3200AAKS-00L9A0 320GB             | 1        | 1      | 2.08%   |
| WDC WD30PURX-64P6ZY0 3TB                | 1        | 1      | 2.08%   |
| WDC WD2500AAJS-00VTA0 250GB             | 1        | 1      | 2.08%   |
| WDC WD20EARS-00MVWB0 2TB                | 1        | 2      | 2.08%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1        | 1      | 2.08%   |
| WDC WD10EZEX-00ZF5A0 1TB                | 1        | 1      | 2.08%   |
| WDC WD10EZEX-00RKKA0 1TB                | 1        | 1      | 2.08%   |
| WDC WD10EZEX-00BN5A0 1TB                | 1        | 1      | 2.08%   |
| WDC WD1001FALS-00J7B1 1TB               | 1        | 1      | 2.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1        | 1      | 2.08%   |
| Seagate ST3750528AS 752GB               | 1        | 1      | 2.08%   |
| Seagate ST3500418AS 500GB               | 1        | 1      | 2.08%   |
| Seagate ST3250318AS 250GB               | 1        | 1      | 2.08%   |
| Seagate ST31000528AS 1TB                | 1        | 1      | 2.08%   |
| Seagate ST3000DM001-9YN166 3TB          | 1        | 1      | 2.08%   |
| Seagate ST2000DM001-1ER164 2TB          | 1        | 3      | 2.08%   |
| Seagate ST1000LM014-SSHD-8GB            | 1        | 1      | 2.08%   |
| Seagate ST1000DM003-1SB102 1TB          | 1        | 1      | 2.08%   |
| Seagate ST1000DM003-1CH162 1TB          | 1        | 1      | 2.08%   |
| Samsung Electronics HD502HJ 500GB       | 1        | 2      | 2.08%   |
| Hitachi HUA723020ALA640 2TB             | 1        | 3      | 2.08%   |
| Hitachi HTS545050B9A300 500GB           | 1        | 1      | 2.08%   |
| Hitachi HDS721050CLA360 500GB           | 1        | 1      | 2.08%   |
| Hitachi HDS721032CLA362 320GB           | 1        | 1      | 2.08%   |
| Hitachi HDP725050GLAT80 500GB           | 1        | 1      | 2.08%   |
| Hitachi HDP725050GLA360 500GB           | 1        | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB                | 1        | 1      | 2.08%   |
| Gigabyte Technology GP-GM30512G-G 512GB | 1        | 1      | 2.08%   |
| Corsair Neutron XT SSD 240GB            | 1        | 2      | 2.08%   |
| Corsair Neutron SSD 64GB                | 1        | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 21     | 36.17%  |
| Seagate             | 10       | 12     | 21.28%  |
| Hitachi             | 10       | 13     | 21.28%  |
| HGST                | 6        | 8      | 12.77%  |
| Corsair             | 2        | 3      | 4.26%   |
| Samsung Electronics | 1        | 2      | 2.13%   |
| Gigabyte Technology | 1        | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 20     | 37.21%  |
| Seagate             | 10       | 12     | 23.26%  |
| Hitachi             | 10       | 13     | 23.26%  |
| HGST                | 6        | 8      | 13.95%  |
| Samsung Electronics | 1        | 2      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 55     | 89.74%  |
| SSD  | 3        | 4      | 7.69%   |
| NVMe | 1        | 1      | 2.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Toshiba MK3256GSY 320GB         | 1        | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 33.33%  |
| Hitachi HTS547550A9E384 500GB   | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |
| Hitachi             | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 148      | 456    | 50.68%  |
| Works    | 105      | 225    | 35.96%  |
| Malfunc  | 37       | 60     | 12.67%  |
| Failed   | 2        | 4      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 218      | 58.29%  |
| AMD                          | 44       | 11.76%  |
| Samsung Electronics          | 27       | 7.22%   |
| SanDisk                      | 11       | 2.94%   |
| Micron/Crucial Technology    | 9        | 2.41%   |
| JMicron Technology           | 9        | 2.41%   |
| Phison Electronics           | 8        | 2.14%   |
| Kingston Technology Company  | 8        | 2.14%   |
| Silicon Motion               | 7        | 1.87%   |
| Marvell Technology Group     | 7        | 1.87%   |
| ASMedia Technology           | 6        | 1.6%    |
| ADATA Technology             | 6        | 1.6%    |
| SK hynix                     | 4        | 1.07%   |
| Nvidia                       | 3        | 0.8%    |
| Toshiba America Info Systems | 2        | 0.53%   |
| VIA Technologies             | 1        | 0.27%   |
| Union Memory (Shenzhen)      | 1        | 0.27%   |
| Transcend                    | 1        | 0.27%   |
| Realtek Semiconductor        | 1        | 0.27%   |
| KIOXIA                       | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 6.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24       | 5.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 4.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 4.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 3.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 3.35%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 14       | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14       | 3.13%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 2.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 12       | 2.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11       | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 2.46%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8        | 1.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 1.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 7        | 1.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 1.34%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 1.12%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.12%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.12%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.89%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 0.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.67%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 0.67%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 0.67%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.67%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.67%   |
| Intel SSD 660P Series                                                                   | 3        | 0.67%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 205      | 56.79%  |
| NVMe | 78       | 21.61%  |
| IDE  | 54       | 14.96%  |
| RAID | 22       | 6.09%   |
| SAS  | 2        | 0.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 217      | 82.51%  |
| AMD    | 46       | 17.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 3.38%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 8        | 3.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 1.88%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4        | 1.5%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 4        | 1.5%    |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 1.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 1.5%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 1.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 1.5%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4        | 1.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.5%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 1.5%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.5%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.5%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.5%    |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 3        | 1.13%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 1.13%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.13%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 1.13%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 1.13%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.13%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 3        | 1.13%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 1.13%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 1.13%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 1.13%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1.13%   |
| Intel 12th Gen Core i7-12700K               | 3        | 1.13%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 3        | 1.13%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.13%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.13%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.13%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 0.75%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 0.75%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 0.75%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.75%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.75%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 65       | 24.62%  |
| Intel Core i5           | 56       | 21.21%  |
| Intel Core i3           | 24       | 9.09%   |
| Other                   | 20       | 7.58%   |
| AMD Ryzen 5             | 14       | 5.3%    |
| Intel Pentium Dual-Core | 12       | 4.55%   |
| Intel Xeon              | 10       | 3.79%   |
| AMD Ryzen 7             | 10       | 3.79%   |
| Intel Pentium           | 9        | 3.41%   |
| AMD Ryzen 9             | 7        | 2.65%   |
| Intel Core 2 Duo        | 6        | 2.27%   |
| Intel Pentium Dual      | 4        | 1.52%   |
| Intel Celeron           | 3        | 1.14%   |
| AMD FX                  | 3        | 1.14%   |
| AMD A8                  | 3        | 1.14%   |
| Intel Pentium Gold      | 2        | 0.76%   |
| Intel Genuine           | 2        | 0.76%   |
| Intel Atom              | 2        | 0.76%   |
| Intel Pentium 4         | 1        | 0.38%   |
| Intel Core i9           | 1        | 0.38%   |
| Intel Core 2 Quad       | 1        | 0.38%   |
| AMD Ryzen Threadripper  | 1        | 0.38%   |
| AMD Ryzen 3 PRO         | 1        | 0.38%   |
| AMD Ryzen 3             | 1        | 0.38%   |
| AMD Phenom II X4        | 1        | 0.38%   |
| AMD Phenom              | 1        | 0.38%   |
| AMD Athlon II X3        | 1        | 0.38%   |
| AMD Athlon 64 X2        | 1        | 0.38%   |
| AMD A6                  | 1        | 0.38%   |
| AMD A10                 | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 108      | 40.91%  |
| 2      | 62       | 23.48%  |
| 6      | 38       | 14.39%  |
| 8      | 28       | 10.61%  |
| 12     | 14       | 5.3%    |
| 16     | 6        | 2.27%   |
| 10     | 3        | 1.14%   |
| 3      | 2        | 0.76%   |
| 1      | 2        | 0.76%   |
| 14     | 1        | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 261      | 99.24%  |
| 2      | 2        | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 157      | 59.47%  |
| 1      | 107      | 40.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 262      | 99.62%  |
| Unknown        | 1        | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 22.02%  |
| 0x306c3    | 25       | 9.03%   |
| 0x1067a    | 18       | 6.5%    |
| 0x906e9    | 16       | 5.78%   |
| 0x306a9    | 15       | 5.42%   |
| 0x206a7    | 14       | 5.05%   |
| 0x506e3    | 13       | 4.69%   |
| 0x906ea    | 10       | 3.61%   |
| 0x90672    | 8        | 2.89%   |
| 0xa0671    | 6        | 2.17%   |
| 0x906ed    | 6        | 2.17%   |
| 0xa0655    | 5        | 1.81%   |
| 0xa0653    | 5        | 1.81%   |
| 0x306e4    | 5        | 1.81%   |
| 0x106e5    | 5        | 1.81%   |
| 0x08701021 | 5        | 1.81%   |
| 0x08108109 | 5        | 1.81%   |
| 0x6fd      | 4        | 1.44%   |
| 0x0a201009 | 3        | 1.08%   |
| 0x08701013 | 3        | 1.08%   |
| 0x0800820d | 3        | 1.08%   |
| 0x906ec    | 2        | 0.72%   |
| 0x806ec    | 2        | 0.72%   |
| 0x206c2    | 2        | 0.72%   |
| 0x20652    | 2        | 0.72%   |
| 0x10676    | 2        | 0.72%   |
| 0x0a201016 | 2        | 0.72%   |
| 0x06003106 | 2        | 0.72%   |
| 0x06001119 | 2        | 0.72%   |
| 0x010000c8 | 2        | 0.72%   |
| 0x906eb    | 1        | 0.36%   |
| 0x906c0    | 1        | 0.36%   |
| 0x90675    | 1        | 0.36%   |
| 0x806ea    | 1        | 0.36%   |
| 0x706a1    | 1        | 0.36%   |
| 0x506e0    | 1        | 0.36%   |
| 0x406c4    | 1        | 0.36%   |
| 0x40671    | 1        | 0.36%   |
| 0x306d4    | 1        | 0.36%   |
| 0x30673    | 1        | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 47       | 17.74%  |
| Haswell          | 33       | 12.45%  |
| IvyBridge        | 24       | 9.06%   |
| Penryn           | 20       | 7.55%   |
| SandyBridge      | 18       | 6.79%   |
| Skylake          | 17       | 6.42%   |
| CometLake        | 13       | 4.91%   |
| Zen 2            | 12       | 4.53%   |
| Zen+             | 9        | 3.4%    |
| Nehalem          | 8        | 3.02%   |
| Alderlake Hybrid | 8        | 3.02%   |
| Unknown          | 8        | 3.02%   |
| Zen 3            | 7        | 2.64%   |
| Zen              | 6        | 2.26%   |
| Icelake          | 6        | 2.26%   |
| Westmere         | 5        | 1.89%   |
| Piledriver       | 4        | 1.51%   |
| Core             | 4        | 1.51%   |
| Steamroller      | 3        | 1.13%   |
| K10              | 3        | 1.13%   |
| Silvermont       | 2        | 0.75%   |
| Broadwell        | 2        | 0.75%   |
| Tremont          | 1        | 0.38%   |
| NetBurst         | 1        | 0.38%   |
| K8 Hammer        | 1        | 0.38%   |
| Goldmont plus    | 1        | 0.38%   |
| Bulldozer        | 1        | 0.38%   |
| Bonnell          | 1        | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 129      | 43.29%  |
| Intel  | 116      | 38.93%  |
| AMD    | 53       | 17.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 25       | 8.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 3.64%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 3.31%   |
| Intel HD Graphics 630                                                       | 10       | 3.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 3.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 2.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 2.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 2.32%   |
| Intel HD Graphics 530                                                       | 6        | 1.99%   |
| Nvidia GP107GL [Quadro P400]                                                | 5        | 1.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.66%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 1.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.66%   |
| Intel AlderLake-S GT1                                                       | 5        | 1.66%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 5        | 1.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.32%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.32%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.32%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.32%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.32%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.32%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.99%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.99%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.99%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.99%   |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 0.99%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.99%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 0.99%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 0.99%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.66%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.66%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 110      | 40.89%  |
| 1 x Intel      | 89       | 33.09%  |
| 1 x AMD        | 43       | 15.99%  |
| Intel + Nvidia | 17       | 6.32%   |
| Intel + AMD    | 4        | 1.49%   |
| AMD + Nvidia   | 4        | 1.49%   |
| 2 x AMD        | 2        | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 170      | 62.73%  |
| Proprietary | 85       | 31.37%  |
| Unknown     | 16       | 5.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 124      | 45.09%  |
| 1.01-2.0   | 46       | 16.73%  |
| 7.01-8.0   | 25       | 9.09%   |
| 0.51-1.0   | 24       | 8.73%   |
| 3.01-4.0   | 23       | 8.36%   |
| 0.01-0.5   | 13       | 4.73%   |
| 5.01-6.0   | 7        | 2.55%   |
| 8.01-16.0  | 7        | 2.55%   |
| 2.01-3.0   | 5        | 1.82%   |
| 16.01-24.0 | 1        | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 72       | 25.71%  |
| Dell                 | 47       | 16.79%  |
| Philips              | 23       | 8.21%   |
| Goldstar             | 21       | 7.5%    |
| AOC                  | 14       | 5%      |
| Ancor Communications | 10       | 3.57%   |
| Hewlett-Packard      | 9        | 3.21%   |
| ViewSonic            | 7        | 2.5%    |
| Lenovo               | 7        | 2.5%    |
| ASUSTek Computer     | 6        | 2.14%   |
| BenQ                 | 5        | 1.79%   |
| Acer                 | 5        | 1.79%   |
| Lenovo Group Limited | 4        | 1.43%   |
| Unknown              | 3        | 1.07%   |
| SANYO                | 3        | 1.07%   |
| Unknown              | 3        | 1.07%   |
| VIE                  | 2        | 0.71%   |
| Panasonic            | 2        | 0.71%   |
| NEX                  | 2        | 0.71%   |
| LG Electronics       | 2        | 0.71%   |
| Iiyama               | 2        | 0.71%   |
| Hyundai ImageQuest   | 2        | 0.71%   |
| HKC                  | 2        | 0.71%   |
| Hitachi              | 2        | 0.71%   |
| Gigabyte Technology  | 2        | 0.71%   |
| Eizo                 | 2        | 0.71%   |
| ___                  | 1        | 0.36%   |
| Xiaomi               | 1        | 0.36%   |
| Unknown (AAA)        | 1        | 0.36%   |
| Toshiba              | 1        | 0.36%   |
| SSD                  | 1        | 0.36%   |
| Sharp                | 1        | 0.36%   |
| Sceptre Tech         | 1        | 0.36%   |
| Plain Tree Systems   | 1        | 0.36%   |
| Pioneer              | 1        | 0.36%   |
| Optoma               | 1        | 0.36%   |
| NXG                  | 1        | 0.36%   |
| MStar                | 1        | 0.36%   |
| JRY                  | 1        | 0.36%   |
| HUAWEI               | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 5        | 1.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 4        | 1.34%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 4        | 1.34%   |
| Philips 222EL PHLC052 1920x1080 476x268mm 21.5-inch                  | 4        | 1.34%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 4        | 1.34%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                    | 4        | 1.34%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch | 3        | 1%      |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch | 3        | 1%      |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch  | 3        | 1%      |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 3        | 1%      |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                     | 3        | 1%      |
| Unknown                                                              | 3        | 1%      |
| SANYO LCD MONITOR SAN07BE 1280x1024 350x270mm 17.4-inch              | 2        | 0.67%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch | 2        | 0.67%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch    | 2        | 0.67%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch    | 2        | 0.67%   |
| Samsung Electronics LS27A80 SAM7184 3840x2160 597x336mm 27.0-inch    | 2        | 0.67%   |
| Samsung Electronics LCD Monitor SMBX2450 1920x1080                   | 2        | 0.67%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 2        | 0.67%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2        | 0.67%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 2        | 0.67%   |
| Lenovo Group Limited LCD Monitor L24q-10                             | 2        | 0.67%   |
| Hyundai ImageQuest L90D+ D-SUB HIQ91DA 1280x1024 376x301mm 19.0-inch | 2        | 0.67%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2        | 0.67%   |
| Hewlett-Packard 27cw HWP3195 1920x1080 598x336mm 27.0-inch           | 2        | 0.67%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                 | 2        | 0.67%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                    | 2        | 0.67%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 0.67%   |
| Dell S2721HGF DEL41E7 1920x1080 597x336mm 27.0-inch                  | 2        | 0.67%   |
| Dell P2714H DELD05E 1920x1080 598x336mm 27.0-inch                    | 2        | 0.67%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2        | 0.67%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                    | 2        | 0.67%   |
| ASUSTek Computer VG248 AUS24AB 1920x1080 531x299mm 24.0-inch         | 2        | 0.67%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 2        | 0.67%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                      | 2        | 0.67%   |
| ___ LCDTV16 ___0101 1920x1080                                        | 1        | 0.33%   |
| Xiaomi Mi TV XMD00E1 3840x2160 950x540mm 43.0-inch                   | 1        | 0.33%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch        | 1        | 0.33%   |
| ViewSonic VX2237 SERIES VSC2C24 1680x1050 474x296mm 22.0-inch        | 1        | 0.33%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch            | 1        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 153      | 55.64%  |
| 3840x2160 (4K)     | 18       | 6.55%   |
| 1680x1050 (WSXGA+) | 18       | 6.55%   |
| 1280x1024 (SXGA)   | 18       | 6.55%   |
| 2560x1440 (QHD)    | 16       | 5.82%   |
| 1920x1200 (WUXGA)  | 11       | 4%      |
| Unknown            | 8        | 2.91%   |
| 1440x900 (WXGA+)   | 6        | 2.18%   |
| 2560x1080          | 5        | 1.82%   |
| 3440x1440          | 4        | 1.45%   |
| 1600x900 (HD+)     | 3        | 1.09%   |
| 3840x1080          | 2        | 0.73%   |
| 1920x540           | 2        | 0.73%   |
| 1366x768 (WXGA)    | 2        | 0.73%   |
| 5360x1440          | 1        | 0.36%   |
| 5120x1440          | 1        | 0.36%   |
| 4480x1440          | 1        | 0.36%   |
| 3840x1200          | 1        | 0.36%   |
| 3520x1080          | 1        | 0.36%   |
| 2560x1600          | 1        | 0.36%   |
| 1360x768           | 1        | 0.36%   |
| 1280x768           | 1        | 0.36%   |
| 1024x768 (XGA)     | 1        | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 47       | 17.09%  |
| 24      | 44       | 16%     |
| 23      | 38       | 13.82%  |
| 27      | 37       | 13.45%  |
| Unknown | 27       | 9.82%   |
| 22      | 17       | 6.18%   |
| 19      | 13       | 4.73%   |
| 17      | 8        | 2.91%   |
| 34      | 7        | 2.55%   |
| 20      | 5        | 1.82%   |
| 72      | 4        | 1.45%   |
| 33      | 4        | 1.45%   |
| 31      | 4        | 1.45%   |
| 84      | 3        | 1.09%   |
| 18      | 3        | 1.09%   |
| 32      | 2        | 0.73%   |
| 65      | 1        | 0.36%   |
| 60      | 1        | 0.36%   |
| 54      | 1        | 0.36%   |
| 52      | 1        | 0.36%   |
| 49      | 1        | 0.36%   |
| 48      | 1        | 0.36%   |
| 42      | 1        | 0.36%   |
| 40      | 1        | 0.36%   |
| 29      | 1        | 0.36%   |
| 26      | 1        | 0.36%   |
| 16      | 1        | 0.36%   |
| 15      | 1        | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 111      | 41.73%  |
| 401-500     | 73       | 27.44%  |
| Unknown     | 27       | 10.15%  |
| 701-800     | 13       | 4.89%   |
| 351-400     | 10       | 3.76%   |
| 301-350     | 9        | 3.38%   |
| 601-700     | 8        | 3.01%   |
| 1501-2000   | 7        | 2.63%   |
| 1001-1500   | 6        | 2.26%   |
| 801-900     | 1        | 0.38%   |
| 901-1000    | 1        | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 166      | 63.85%  |
| 16/10   | 41       | 15.77%  |
| Unknown | 26       | 10%     |
| 5/4     | 14       | 5.38%   |
| 21/9    | 7        | 2.69%   |
| 4/3     | 4        | 1.54%   |
| 3/2     | 1        | 0.38%   |
| 1.96    | 1        | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 118      | 44.03%  |
| 301-350        | 38       | 14.18%  |
| 151-200        | 28       | 10.45%  |
| Unknown        | 27       | 10.07%  |
| 351-500        | 18       | 6.72%   |
| 251-300        | 14       | 5.22%   |
| More than 1000 | 12       | 4.48%   |
| 141-150        | 8        | 2.99%   |
| 501-1000       | 3        | 1.12%   |
| 131-140        | 1        | 0.37%   |
| 101-110        | 1        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 152      | 58.69%  |
| 101-120 | 59       | 22.78%  |
| Unknown | 27       | 10.42%  |
| 1-50    | 10       | 3.86%   |
| 121-160 | 7        | 2.7%    |
| 161-240 | 4        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 204      | 75.28%  |
| 2     | 47       | 17.34%  |
| 0     | 16       | 5.9%    |
| 3     | 3        | 1.11%   |
| 4     | 1        | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 163      | 42.78%  |
| Intel                           | 117      | 30.71%  |
| Qualcomm Atheros                | 26       | 6.82%   |
| Ralink Technology               | 14       | 3.67%   |
| TP-Link                         | 13       | 3.41%   |
| Edimax Technology               | 7        | 1.84%   |
| Broadcom                        | 5        | 1.31%   |
| Ralink                          | 3        | 0.79%   |
| ASIX Electronics                | 3        | 0.79%   |
| Xiaomi                          | 2        | 0.52%   |
| Qualcomm Atheros Communications | 2        | 0.52%   |
| Nvidia                          | 2        | 0.52%   |
| Microsoft                       | 2        | 0.52%   |
| Marvell Technology Group        | 2        | 0.52%   |
| D-Link                          | 2        | 0.52%   |
| Broadcom Limited                | 2        | 0.52%   |
| Aquantia                        | 2        | 0.52%   |
| VIA Technologies                | 1        | 0.26%   |
| U.S. Robotics                   | 1        | 0.26%   |
| Texas Instruments               | 1        | 0.26%   |
| STMicroelectronics              | 1        | 0.26%   |
| Samsung Electronics             | 1        | 0.26%   |
| ROCCAT                          | 1        | 0.26%   |
| Mellanox Technologies           | 1        | 0.26%   |
| MediaTek                        | 1        | 0.26%   |
| Huawei Technologies             | 1        | 0.26%   |
| Google                          | 1        | 0.26%   |
| GDMicroelectronics              | 1        | 0.26%   |
| Davicom Semiconductor           | 1        | 0.26%   |
| BUFFALO                         | 1        | 0.26%   |
| Accton Technology               | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 125      | 29.34%  |
| Intel Ethernet Connection (2) I219-V                              | 19       | 4.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 3.76%   |
| Intel I211 Gigabit Network Connection                             | 15       | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 3.05%   |
| Intel Wi-Fi 6 AX200                                               | 11       | 2.58%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 1.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 7        | 1.64%   |
| Realtek 802.11ac NIC                                              | 7        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.17%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 1.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5        | 1.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.94%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4        | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 4        | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                             | 4        | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 0.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3        | 0.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 3        | 0.7%    |
| TP-Link Archer T4U ver.3                                          | 3        | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3        | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.7%    |
| Intel Wireless-AC 9260                                            | 3        | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 0.7%    |
| Edimax RTL8192S WLAN Adapter                                      | 3        | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 2        | 0.47%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.47%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2        | 0.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 34       | 27.87%  |
| Realtek Semiconductor           | 28       | 22.95%  |
| Ralink Technology               | 14       | 11.48%  |
| TP-Link                         | 13       | 10.66%  |
| Qualcomm Atheros                | 11       | 9.02%   |
| Edimax Technology               | 7        | 5.74%   |
| Broadcom                        | 4        | 3.28%   |
| Ralink                          | 3        | 2.46%   |
| Qualcomm Atheros Communications | 2        | 1.64%   |
| Microsoft                       | 2        | 1.64%   |
| D-Link                          | 2        | 1.64%   |
| MediaTek                        | 1        | 0.82%   |
| BUFFALO                         | 1        | 0.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11       | 8.8%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 7        | 5.6%    |
| Realtek 802.11ac NIC                                           | 7        | 5.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 5        | 4%      |
| Ralink MT7601U Wireless Adapter                                | 4        | 3.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3        | 2.4%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 3        | 2.4%    |
| TP-Link Archer T4U ver.3                                       | 3        | 2.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3        | 2.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3        | 2.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3        | 2.4%    |
| Intel Wireless-AC 9260                                         | 3        | 2.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3        | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 2.4%    |
| Edimax RTL8192S WLAN Adapter                                   | 3        | 2.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 1.6%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 2        | 1.6%    |
| Ralink RT5370 Wireless Adapter                                 | 2        | 1.6%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2        | 1.6%    |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 1.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2        | 1.6%    |
| Microsoft Xbox 360 Wireless Adapter                            | 2        | 1.6%    |
| Intel Wireless 3165                                            | 2        | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2        | 1.6%    |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]       | 2        | 1.6%    |
| Edimax AC600 USB                                               | 2        | 1.6%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2        | 1.6%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1        | 0.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.8%    |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 0.8%    |
| TP-Link 802.11ac NIC                                           | 1        | 0.8%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.8%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 0.8%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 149      | 51.92%  |
| Intel                    | 101      | 35.19%  |
| Qualcomm Atheros         | 16       | 5.57%   |
| ASIX Electronics         | 3        | 1.05%   |
| Xiaomi                   | 2        | 0.7%    |
| Nvidia                   | 2        | 0.7%    |
| Marvell Technology Group | 2        | 0.7%    |
| Broadcom Limited         | 2        | 0.7%    |
| Aquantia                 | 2        | 0.7%    |
| VIA Technologies         | 1        | 0.35%   |
| Samsung Electronics      | 1        | 0.35%   |
| Mellanox Technologies    | 1        | 0.35%   |
| Huawei Technologies      | 1        | 0.35%   |
| Google                   | 1        | 0.35%   |
| Davicom Semiconductor    | 1        | 0.35%   |
| Broadcom                 | 1        | 0.35%   |
| Accton Technology        | 1        | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 125      | 42.23%  |
| Intel Ethernet Connection (2) I219-V                              | 19       | 6.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 5.41%   |
| Intel I211 Gigabit Network Connection                             | 15       | 5.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 4.39%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.69%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4        | 1.35%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.35%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 4        | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.68%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.68%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.68%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.68%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.68%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.68%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.34%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.34%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.34%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.34%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.34%   |
| Intel PRO/100 VE Network Connection                               | 1        | 0.34%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 261      | 69.23%  |
| WiFi     | 111      | 29.44%  |
| Modem    | 4        | 1.06%   |
| Unknown  | 1        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 208      | 75.64%  |
| WiFi     | 67       | 24.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 192      | 72.45%  |
| 2     | 58       | 21.89%  |
| 3     | 13       | 4.91%   |
| 0     | 2        | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 224      | 82.05%  |
| Yes  | 49       | 17.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 28       | 39.44%  |
| Cambridge Silicon Radio         | 24       | 33.8%   |
| Realtek Semiconductor           | 5        | 7.04%   |
| Qualcomm Atheros Communications | 4        | 5.63%   |
| ASUSTek Computer                | 3        | 4.23%   |
| Broadcom                        | 2        | 2.82%   |
| TP-Link                         | 1        | 1.41%   |
| Realtek                         | 1        | 1.41%   |
| Lite-On Technology              | 1        | 1.41%   |
| IMC Networks                    | 1        | 1.41%   |
| Apple                           | 1        | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24       | 33.8%   |
| Intel AX200 Bluetooth                               | 9        | 12.68%  |
| Realtek Bluetooth Radio                             | 5        | 7.04%   |
| Intel Bluetooth wireless interface                  | 5        | 7.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 5.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 4.23%   |
| Intel AX201 Bluetooth                               | 3        | 4.23%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 2.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 2.82%   |
| ASUS Bluetooth Adapter                              | 2        | 2.82%   |
| TP-Link UB500 Adapter                               | 1        | 1.41%   |
| Realtek Bluetooth Radio                             | 1        | 1.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.41%   |
| Lite-On Bluetooth Device                            | 1        | 1.41%   |
| Intel Bluetooth Device                              | 1        | 1.41%   |
| Intel AX210 Bluetooth                               | 1        | 1.41%   |
| IMC Networks Bluetooth Device                       | 1        | 1.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.41%   |
| ASUS BCM20702A0                                     | 1        | 1.41%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 208      | 45.02%  |
| Nvidia                                       | 124      | 26.84%  |
| AMD                                          | 69       | 14.94%  |
| C-Media Electronics                          | 10       | 2.16%   |
| Creative Labs                                | 7        | 1.52%   |
| XMOS                                         | 4        | 0.87%   |
| Logitech                                     | 4        | 0.87%   |
| Focusrite-Novation                           | 4        | 0.87%   |
| Creative Technology                          | 4        | 0.87%   |
| Texas Instruments                            | 3        | 0.65%   |
| JMTek                                        | 3        | 0.65%   |
| SteelSeries ApS                              | 2        | 0.43%   |
| Kingston Technology                          | 2        | 0.43%   |
| GN Netcom                                    | 2        | 0.43%   |
| Cambridge Silicon Radio                      | 2        | 0.43%   |
| Unknown                                      | 2        | 0.43%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.22%   |
| VIA Technologies                             | 1        | 0.22%   |
| Samson Technologies                          | 1        | 0.22%   |
| Razer USA                                    | 1        | 0.22%   |
| Microsoft                                    | 1        | 0.22%   |
| Meridian                                     | 1        | 0.22%   |
| iCreate Technologies                         | 1        | 0.22%   |
| Giga-Byte Technology                         | 1        | 0.22%   |
| Generalplus Technology                       | 1        | 0.22%   |
| FIFINE Microphones                           | 1        | 0.22%   |
| EGO SYStems                                  | 1        | 0.22%   |
| Areson Technology                            | 1        | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 27       | 5.22%   |
| Intel 200 Series PCH HD Audio                                              | 25       | 4.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22       | 4.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21       | 4.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 18       | 3.48%   |
| AMD Starship/Matisse HD Audio Controller                                   | 18       | 3.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 3.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 16       | 3.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 2.51%   |
| Intel Alder Lake-S HD Audio Controller                                     | 13       | 2.51%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13       | 2.51%   |
| Nvidia GP104 High Definition Audio Controller                              | 11       | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 1.55%   |
| Nvidia High Definition Audio Controller                                    | 8        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 1.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 1.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 1.16%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 1.16%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 0.97%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 0.97%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.97%   |
| AMD FCH Azalia Controller                                                  | 5        | 0.97%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 39       | 23.78%  |
| Unknown             | 24       | 14.63%  |
| Corsair             | 20       | 12.2%   |
| Crucial             | 18       | 10.98%  |
| G.Skill             | 16       | 9.76%   |
| SK hynix            | 12       | 7.32%   |
| Samsung Electronics | 10       | 6.1%    |
| Ramaxel Technology  | 6        | 3.66%   |
| Micron Technology   | 6        | 3.66%   |
| Transcend           | 3        | 1.83%   |
| Team                | 3        | 1.83%   |
| GeIL                | 2        | 1.22%   |
| A-DATA Technology   | 2        | 1.22%   |
| Unknown (09D5)      | 1        | 0.61%   |
| Patriot             | 1        | 0.61%   |
| KETECH              | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                        | 3        | 1.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s    | 3        | 1.68%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 3        | 1.68%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s       | 3        | 1.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 2        | 1.12%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2        | 1.12%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 2        | 1.12%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 2        | 1.12%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 2        | 1.12%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s     | 2        | 1.12%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 2        | 1.12%   |
| Kingston RAM KHX2400C15D4/4G 4096MB DIMM DDR4 3151MT/s     | 2        | 1.12%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s       | 2        | 1.12%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s        | 2        | 1.12%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s      | 2        | 1.12%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 2        | 1.12%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s      | 2        | 1.12%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 2        | 1.12%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s       | 2        | 1.12%   |
| Crucial RAM CT16G4DFD832A.C16FP 16384MB DIMM DDR4 3200MT/s | 2        | 1.12%   |
| Crucial RAM BL8G32C16U4B.M8FE1 8GB DIMM DDR4 3600MT/s      | 2        | 1.12%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s     | 2        | 1.12%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s      | 2        | 1.12%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 8GB DIMM                                | 1        | 0.56%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1        | 0.56%   |
| Unknown RAM Module 8192MB DIMM 800MT/s                     | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                   | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 667MT/s                        | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                   | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                     | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 84       | 57.14%  |
| DDR3    | 32       | 21.77%  |
| Unknown | 18       | 12.24%  |
| DDR2    | 7        | 4.76%   |
| SDRAM   | 4        | 2.72%   |
| DDR5    | 1        | 0.68%   |
| DDR     | 1        | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 144      | 97.96%  |
| SODIMM | 3        | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 47       | 29.38%  |
| 16384 | 41       | 25.63%  |
| 4096  | 40       | 25%     |
| 2048  | 19       | 11.88%  |
| 1024  | 7        | 4.38%   |
| 32768 | 6        | 3.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 21       | 12.8%   |
| 1600    | 21       | 12.8%   |
| 2133    | 13       | 7.93%   |
| 800     | 13       | 7.93%   |
| 1333    | 12       | 7.32%   |
| 2400    | 11       | 6.71%   |
| 3600    | 8        | 4.88%   |
| 2667    | 8        | 4.88%   |
| 3800    | 4        | 2.44%   |
| 1867    | 4        | 2.44%   |
| 667     | 4        | 2.44%   |
| Unknown | 4        | 2.44%   |
| 3466    | 3        | 1.83%   |
| 1866    | 3        | 1.83%   |
| 4800    | 2        | 1.22%   |
| 3933    | 2        | 1.22%   |
| 3666    | 2        | 1.22%   |
| 3534    | 2        | 1.22%   |
| 3533    | 2        | 1.22%   |
| 3266    | 2        | 1.22%   |
| 3151    | 2        | 1.22%   |
| 2933    | 2        | 1.22%   |
| 2000    | 2        | 1.22%   |
| 1800    | 2        | 1.22%   |
| 49926   | 1        | 0.61%   |
| 5600    | 1        | 0.61%   |
| 4400    | 1        | 0.61%   |
| 3733    | 1        | 0.61%   |
| 3400    | 1        | 0.61%   |
| 3334    | 1        | 0.61%   |
| 3066    | 1        | 0.61%   |
| 3000    | 1        | 0.61%   |
| 2800    | 1        | 0.61%   |
| 2666    | 1        | 0.61%   |
| 2134    | 1        | 0.61%   |
| 1648    | 1        | 0.61%   |
| 1400    | 1        | 0.61%   |
| 533     | 1        | 0.61%   |
| 400     | 1        | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 9        | 52.94%  |
| Samsung Electronics   | 3        | 17.65%  |
| Canon                 | 2        | 11.76%  |
| Lexmark International | 1        | 5.88%   |
| GODEX INTERNATIONAL   | 1        | 5.88%   |
| Brother Industries    | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP DeskJet 4670 series        | 3        | 17.65%  |
| Samsung M2070 Series          | 2        | 11.76%  |
| HP Officejet 4500 G510g-m     | 2        | 11.76%  |
| Samsung SCX-4623 Series       | 1        | 5.88%   |
| Lexmark International CS417dn | 1        | 5.88%   |
| HP Printing Support           | 1        | 5.88%   |
| HP OfficeJet 5600 (USBHUB)    | 1        | 5.88%   |
| HP LaserJet M14-M17           | 1        | 5.88%   |
| HP Deskjet 4640 series        | 1        | 5.88%   |
| GODEX INTERNATIONAL DT2       | 1        | 5.88%   |
| Canon TR7500 series           | 1        | 5.88%   |
| Canon PIXMA MX490 Series      | 1        | 5.88%   |
| Brother MFC-J497DW            | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 100 | 2        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 23       | 34.33%  |
| Microsoft                     | 17       | 25.37%  |
| Generalplus Technology        | 5        | 7.46%   |
| Samsung Electronics           | 4        | 5.97%   |
| Microdia                      | 3        | 4.48%   |
| IMC Networks                  | 2        | 2.99%   |
| Apple                         | 2        | 2.99%   |
| Xiaomi                        | 1        | 1.49%   |
| Sunplus Innovation Technology | 1        | 1.49%   |
| Realtek Semiconductor         | 1        | 1.49%   |
| Quanta                        | 1        | 1.49%   |
| Lenovo                        | 1        | 1.49%   |
| Jieli Technology              | 1        | 1.49%   |
| Hewlett-Packard               | 1        | 1.49%   |
| Chicony Electronics           | 1        | 1.49%   |
| Aveo Technology               | 1        | 1.49%   |
| Allwinner Technology          | 1        | 1.49%   |
| Alcor Micro                   | 1        | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                           | 12       | 17.91%  |
| Logitech Webcam C270                                | 5        | 7.46%   |
| Samsung Galaxy A5 (MTP)                             | 4        | 5.97%   |
| Logitech Webcam C310                                | 4        | 5.97%   |
| Generalplus GENERAL WEBCAM                          | 3        | 4.48%   |
| Microsoft MicrosoftÂ LifeCam Studio                | 2        | 2.99%   |
| Logitech C922 Pro Stream Webcam                     | 2        | 2.99%   |
| Generalplus WEB CAM                                 | 2        | 2.99%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                  | 1        | 1.49%   |
| Sunplus Camera                                      | 1        | 1.49%   |
| Realtek Web Camera                                  | 1        | 1.49%   |
| Quanta Astro HD Camera                              | 1        | 1.49%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 1.49%   |
| Microsoft MicrosoftÂ LifeCam Cinema                | 1        | 1.49%   |
| Microsoft LifeCam HD-5000                           | 1        | 1.49%   |
| Microdia REDRAGON Live Camera Audio                 | 1        | 1.49%   |
| Microdia Integrated Camera                          | 1        | 1.49%   |
| Microdia AUKEY-W1                                   | 1        | 1.49%   |
| Logitech Webcam C930e                               | 1        | 1.49%   |
| Logitech Webcam C925e                               | 1        | 1.49%   |
| Logitech Webcam C920-C                              | 1        | 1.49%   |
| Logitech Webcam C170                                | 1        | 1.49%   |
| Logitech QuickCam E 3500                            | 1        | 1.49%   |
| Logitech Mic (Fusion)                               | 1        | 1.49%   |
| Logitech HD Webcam C615                             | 1        | 1.49%   |
| Logitech HD Webcam C525                             | 1        | 1.49%   |
| Logitech HD Pro Webcam C920                         | 1        | 1.49%   |
| Logitech C930c                                      | 1        | 1.49%   |
| Logitech C920 PRO HD Webcam                         | 1        | 1.49%   |
| Logitech BRIO Ultra HD Webcam                       | 1        | 1.49%   |
| Lenovo 500 RGB Camera                               | 1        | 1.49%   |
| Jieli USB PHY 2.0                                   | 1        | 1.49%   |
| IMC Networks XHC Camera                             | 1        | 1.49%   |
| IMC Networks Integrated Camera                      | 1        | 1.49%   |
| HP Webcam HD 2300                                   | 1        | 1.49%   |
| Chicony Gateway Webcam                              | 1        | 1.49%   |
| Aveo UVC camera (Bresser microscope)                | 1        | 1.49%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1        | 1.49%   |
| Apple iPad 2 (3G; 64GB)                             | 1        | 1.49%   |
| Allwinner TP1005                                    | 1        | 1.49%   |

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
| 0     | 224      | 83.27%  |
| 1     | 40       | 14.87%  |
| 2     | 5        | 1.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 22       | 44.9%   |
| Net/wireless             | 17       | 34.69%  |
| Communication controller | 6        | 12.24%  |
| Camera                   | 3        | 6.12%   |
| Bluetooth                | 1        | 2.04%   |

