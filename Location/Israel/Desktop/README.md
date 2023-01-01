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

Total: 350

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 50       | 19.01%  |
| Ubuntu 18.04                 | 24       | 9.13%   |
| OpenMandriva 4.2             | 14       | 5.32%   |
| OpenMandriva 4.3             | 11       | 4.18%   |
| ROSA R11                     | 9        | 3.42%   |
| Ubuntu 19.04                 | 8        | 3.04%   |
| ROSA R11.1                   | 6        | 2.28%   |
| Ubuntu 20.10                 | 5        | 1.9%    |
| Manjaro                      | 5        | 1.9%    |
| Pop!_OS 20.04                | 4        | 1.52%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.52%   |
| Linux Mint 20.3              | 4        | 1.52%   |
| Linux Mint 19.3              | 4        | 1.52%   |
| Kubuntu 20.04                | 4        | 1.52%   |
| Fedora 36                    | 4        | 1.52%   |
| Debian 11                    | 4        | 1.52%   |
| ArcoLinux Rolling            | 4        | 1.52%   |
| Ubuntu 22.04                 | 3        | 1.14%   |
| Ubuntu 19.10                 | 3        | 1.14%   |
| Ubuntu 16.04                 | 3        | 1.14%   |
| ROSA R8.1                    | 3        | 1.14%   |
| ROSA R8                      | 3        | 1.14%   |
| ROSA R10                     | 3        | 1.14%   |
| Pop!_OS 21.10                | 3        | 1.14%   |
| Linux Mint 20.2              | 3        | 1.14%   |
| Linux Mint 20.1              | 3        | 1.14%   |
| KDE neon 20.04               | 3        | 1.14%   |
| Arch Rolling                 | 3        | 1.14%   |
| Zorin 16                     | 2        | 0.76%   |
| Xubuntu 20.04                | 2        | 0.76%   |
| Xubuntu 18.04                | 2        | 0.76%   |
| Ubuntu Unity 20.04           | 2        | 0.76%   |
| Ubuntu 21.10                 | 2        | 0.76%   |
| Ubuntu 21.04                 | 2        | 0.76%   |
| Rocky Linux 8.5              | 2        | 0.76%   |
| Pop!_OS 21.04                | 2        | 0.76%   |
| Manjaro 22.0.0               | 2        | 0.76%   |
| Linux Mint 21                | 2        | 0.76%   |
| Linux Mint 20                | 2        | 0.76%   |
| Fedora 35                    | 2        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 96       | 39.18%  |
| OpenMandriva  | 26       | 10.61%  |
| ROSA          | 20       | 8.16%   |
| Linux Mint    | 15       | 6.12%   |
| Manjaro       | 11       | 4.49%   |
| Pop!_OS       | 10       | 4.08%   |
| Fedora        | 10       | 4.08%   |
| Debian        | 8        | 3.27%   |
| Kubuntu       | 7        | 2.86%   |
| Xubuntu       | 6        | 2.45%   |
| Arch          | 5        | 2.04%   |
| openSUSE      | 4        | 1.63%   |
| ArcoLinux     | 4        | 1.63%   |
| Zorin         | 3        | 1.22%   |
| Ubuntu Unity  | 3        | 1.22%   |
| Rocky Linux   | 3        | 1.22%   |
| KDE neon      | 3        | 1.22%   |
| Ubuntu MATE   | 2        | 0.82%   |
| CentOS        | 2        | 0.82%   |
| Ubuntu Budgie | 1        | 0.41%   |
| Gentoo        | 1        | 0.41%   |
| Garuda Linux  | 1        | 0.41%   |
| Endless       | 1        | 0.41%   |
| Elementary    | 1        | 0.41%   |
| Devuan        | 1        | 0.41%   |
| BlackPanther  | 1        | 0.41%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 14       | 4.88%   |
| 5.4.0-42-generic                    | 13       | 4.53%   |
| 5.16.7-desktop-1omv4003             | 11       | 3.83%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6        | 2.09%   |
| 5.4.0-48-generic                    | 5        | 1.74%   |
| 5.11.0-37-generic                   | 5        | 1.74%   |
| 5.4.0-52-generic                    | 4        | 1.39%   |
| 5.8.0-55-generic                    | 3        | 1.05%   |
| 5.8.0-48-generic                    | 3        | 1.05%   |
| 5.4.0-72-generic                    | 3        | 1.05%   |
| 5.4.0-65-generic                    | 3        | 1.05%   |
| 5.15.0-47-generic                   | 3        | 1.05%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 3        | 1.05%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 3        | 1.05%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 3        | 1.05%   |
| 4.15.0-58-generic                   | 3        | 1.05%   |
| 4.15.0-50-generic                   | 3        | 1.05%   |
| 5.8.0-43-generic                    | 2        | 0.7%    |
| 5.8.0-34-generic                    | 2        | 0.7%    |
| 5.8.0-25-generic                    | 2        | 0.7%    |
| 5.4.0-45-generic                    | 2        | 0.7%    |
| 5.4.0-37-generic                    | 2        | 0.7%    |
| 5.4.0-26-generic                    | 2        | 0.7%    |
| 5.4.0-131-generic                   | 2        | 0.7%    |
| 5.3.0-40-generic                    | 2        | 0.7%    |
| 5.3.0-28-generic                    | 2        | 0.7%    |
| 5.16.19-76051619-generic            | 2        | 0.7%    |
| 5.14.10-300.fc35.x86_64             | 2        | 0.7%    |
| 5.13.0-7620-generic                 | 2        | 0.7%    |
| 5.13.0-51-generic                   | 2        | 0.7%    |
| 5.13.0-28-generic                   | 2        | 0.7%    |
| 5.13.0-27-generic                   | 2        | 0.7%    |
| 5.11.0-40-generic                   | 2        | 0.7%    |
| 5.11.0-38-generic                   | 2        | 0.7%    |
| 5.11.0-27-generic                   | 2        | 0.7%    |
| 5.10.74-generic-2rosa2021.1-x86_64  | 2        | 0.7%    |
| 5.0.0-38-generic                    | 2        | 0.7%    |
| 5.0.0-29-generic                    | 2        | 0.7%    |
| 5.0.0-25-generic                    | 2        | 0.7%    |
| 5.0.0-20-generic                    | 2        | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 53       | 20%     |
| 4.15.0  | 25       | 9.43%   |
| 5.8.0   | 20       | 7.55%   |
| 5.11.0  | 14       | 5.28%   |
| 5.10.14 | 14       | 5.28%   |
| 5.0.0   | 13       | 4.91%   |
| 5.13.0  | 12       | 4.53%   |
| 5.16.7  | 11       | 4.15%   |
| 5.3.0   | 10       | 3.77%   |
| 5.15.0  | 8        | 3.02%   |
| 4.18.0  | 5        | 1.89%   |
| 5.10.0  | 4        | 1.51%   |
| 4.9.60  | 3        | 1.13%   |
| 5.9.16  | 2        | 0.75%   |
| 5.16.19 | 2        | 0.75%   |
| 5.15.72 | 2        | 0.75%   |
| 5.14.10 | 2        | 0.75%   |
| 5.12.0  | 2        | 0.75%   |
| 5.10.74 | 2        | 0.75%   |
| 4.19.0  | 2        | 0.75%   |
| 4.1.38  | 2        | 0.75%   |
| 4.1.34  | 2        | 0.75%   |
| 3.10.0  | 2        | 0.75%   |
| 6.0.8   | 1        | 0.38%   |
| 6.0.7   | 1        | 0.38%   |
| 6.0.3   | 1        | 0.38%   |
| 6.0.11  | 1        | 0.38%   |
| 6.0.0   | 1        | 0.38%   |
| 5.9.9   | 1        | 0.38%   |
| 5.9.8   | 1        | 0.38%   |
| 5.9.14  | 1        | 0.38%   |
| 5.9.1   | 1        | 0.38%   |
| 5.8.5   | 1        | 0.38%   |
| 5.8.18  | 1        | 0.38%   |
| 5.7.16  | 1        | 0.38%   |
| 5.6.4   | 1        | 0.38%   |
| 5.5.0   | 1        | 0.38%   |
| 5.4.32  | 1        | 0.38%   |
| 5.4.19  | 1        | 0.38%   |
| 5.19.7  | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 21.07%  |
| 5.10    | 25       | 9.58%   |
| 4.15    | 25       | 9.58%   |
| 5.8     | 22       | 8.43%   |
| 5.15    | 15       | 5.75%   |
| 5.11    | 15       | 5.75%   |
| 5.16    | 14       | 5.36%   |
| 5.13    | 13       | 4.98%   |
| 5.0     | 13       | 4.98%   |
| 5.3     | 10       | 3.83%   |
| 5.9     | 6        | 2.3%    |
| 4.9     | 6        | 2.3%    |
| 4.18    | 6        | 2.3%    |
| 6.0     | 5        | 1.92%   |
| 5.17    | 5        | 1.92%   |
| 4.19    | 5        | 1.92%   |
| 5.14    | 4        | 1.53%   |
| 5.12    | 4        | 1.53%   |
| 4.1     | 4        | 1.53%   |
| 5.19    | 2        | 0.77%   |
| 3.10    | 2        | 0.77%   |
| 5.7     | 1        | 0.38%   |
| 5.6     | 1        | 0.38%   |
| 5.5     | 1        | 0.38%   |
| 4.7     | 1        | 0.38%   |
| 4.4     | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 234      | 99.15%  |
| i686   | 2        | 0.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 95       | 38.15%  |
| KDE5       | 53       | 21.29%  |
| Unknown    | 36       | 14.46%  |
| KDE4       | 17       | 6.83%   |
| X-Cinnamon | 14       | 5.62%   |
| XFCE       | 12       | 4.82%   |
| KDE        | 7        | 2.81%   |
| MATE       | 5        | 2.01%   |
| Unity      | 4        | 1.61%   |
| i3         | 2        | 0.8%    |
| Cinnamon   | 2        | 0.8%    |
| Pantheon   | 1        | 0.4%    |
| Budgie     | 1        | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 199      | 82.57%  |
| Unknown | 21       | 8.71%   |
| Wayland | 15       | 6.22%   |
| Tty     | 6        | 2.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 116      | 47.35%  |
| SDDM    | 47       | 19.18%  |
| GDM     | 28       | 11.43%  |
| KDM     | 17       | 6.94%   |
| GDM3    | 16       | 6.53%   |
| LightDM | 13       | 5.31%   |
| TDM     | 7        | 2.86%   |
| XDM     | 1        | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_IL      | 84       | 34.85%  |
| en_US      | 75       | 31.12%  |
| Unknown    | 41       | 17.01%  |
| he_IL      | 15       | 6.22%   |
| ru_RU      | 14       | 5.81%   |
| C          | 4        | 1.66%   |
| fr_FR      | 2        | 0.83%   |
| pt_BR      | 1        | 0.41%   |
| POSIX      | 1        | 0.41%   |
| en_US.UTF8 | 1        | 0.41%   |
| en_GB      | 1        | 0.41%   |
| en_AG      | 1        | 0.41%   |
| C.UTF8     | 1        | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 137      | 57.08%  |
| EFI  | 103      | 42.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 179      | 73.66%  |
| Overlay | 27       | 11.11%  |
| Btrfs   | 19       | 7.82%   |
| Unknown | 9        | 3.7%    |
| Xfs     | 6        | 2.47%   |
| Zfs     | 1        | 0.41%   |
| Tmpfs   | 1        | 0.41%   |
| F2fs    | 1        | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 124      | 51.88%  |
| GPT     | 78       | 32.64%  |
| MBR     | 37       | 15.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 193      | 80.42%  |
| Yes       | 47       | 19.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 157      | 64.08%  |
| Yes       | 88       | 35.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 78       | 33.19%  |
| ASUSTek Computer    | 75       | 31.91%  |
| Dell                | 20       | 8.51%   |
| Lenovo              | 12       | 5.11%   |
| MSI                 | 11       | 4.68%   |
| Hewlett-Packard     | 11       | 4.68%   |
| ASRock              | 10       | 4.26%   |
| Intel               | 4        | 1.7%    |
| Pegatron            | 2        | 0.85%   |
| Foxconn             | 2        | 0.85%   |
| Unknown             | 2        | 0.85%   |
| Supermicro          | 1        | 0.43%   |
| Shuttle             | 1        | 0.43%   |
| ITI LIMITED         | 1        | 0.43%   |
| Hardkernel          | 1        | 0.43%   |
| Biostar             | 1        | 0.43%   |
| AZW                 | 1        | 0.43%   |
| AMI                 | 1        | 0.43%   |
| Alienware           | 1        | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 9        | 3.83%   |
| MSI MS-7592                            | 3        | 1.28%   |
| Gigabyte H61M-S1                       | 3        | 1.28%   |
| ASUS P8H61-M LX R2.0                   | 3        | 1.28%   |
| ASUS H110M-A/M.2                       | 3        | 1.28%   |
| Intel DH77EB AAG39073-304              | 2        | 0.85%   |
| Gigabyte Z390 GAMING X                 | 2        | 0.85%   |
| Gigabyte X570 AORUS ULTRA              | 2        | 0.85%   |
| Gigabyte P55-UD3L                      | 2        | 0.85%   |
| Gigabyte H97-HD3                       | 2        | 0.85%   |
| Gigabyte H61M-S2PV                     | 2        | 0.85%   |
| Gigabyte H55M-D2H                      | 2        | 0.85%   |
| Gigabyte B460HD3                       | 2        | 0.85%   |
| Gigabyte B450M DS3H                    | 2        | 0.85%   |
| Dell OptiPlex 9020                     | 2        | 0.85%   |
| Dell OptiPlex 755                      | 2        | 0.85%   |
| Dell OptiPlex 7050                     | 2        | 0.85%   |
| ASUS TUF Gaming B550-PLUS              | 2        | 0.85%   |
| ASUS ROG STRIX Z390-E GAMING           | 2        | 0.85%   |
| ASUS PRIME Z490-P                      | 2        | 0.85%   |
| ASUS PRIME X470-PRO                    | 2        | 0.85%   |
| ASUS PRIME H310M-E R2.0                | 2        | 0.85%   |
| ASUS PRIME B560M-K                     | 2        | 0.85%   |
| ASUS H110M-K                           | 2        | 0.85%   |
| Unknown                                | 2        | 0.85%   |
| Supermicro X9DAi                       | 1        | 0.43%   |
| Shuttle SH87R                          | 1        | 0.43%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.43%   |
| Pegatron NC890AA-ABA a6803w            | 1        | 0.43%   |
| MSI MS-7B86                            | 1        | 0.43%   |
| MSI MS-7B79                            | 1        | 0.43%   |
| MSI MS-7984                            | 1        | 0.43%   |
| MSI MS-7982                            | 1        | 0.43%   |
| MSI MS-7978                            | 1        | 0.43%   |
| MSI MS-7816                            | 1        | 0.43%   |
| MSI MS-7788                            | 1        | 0.43%   |
| MSI Elite 7100 Microtower PC           | 1        | 0.43%   |
| Lenovo V530-15ICR 11BH0032IV           | 1        | 0.43%   |
| Lenovo V520-15IKL 10NKS05400           | 1        | 0.43%   |
| Lenovo V520-15IKL 10NK003KIV           | 1        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 26       | 11.06%  |
| Dell OptiPlex        | 12       | 5.11%   |
| ASUS All             | 9        | 3.83%   |
| Lenovo ThinkCentre   | 7        | 2.98%   |
| ASUS ROG             | 7        | 2.98%   |
| ASUS TUF             | 6        | 2.55%   |
| HP Compaq            | 4        | 1.7%    |
| Gigabyte Z690        | 4        | 1.7%    |
| Dell Vostro          | 4        | 1.7%    |
| ASUS H110M-A         | 4        | 1.7%    |
| MSI MS-7592          | 3        | 1.28%   |
| Lenovo V520-15IKL    | 3        | 1.28%   |
| Gigabyte Z390        | 3        | 1.28%   |
| Gigabyte X570        | 3        | 1.28%   |
| Gigabyte H61M-S1     | 3        | 1.28%   |
| Gigabyte B450M       | 3        | 1.28%   |
| Dell Precision       | 3        | 1.28%   |
| ASUS P8H61-M         | 3        | 1.28%   |
| Intel DH77EB         | 2        | 0.85%   |
| HP ProDesk           | 2        | 0.85%   |
| Gigabyte P55-UD3L    | 2        | 0.85%   |
| Gigabyte H97-HD3     | 2        | 0.85%   |
| Gigabyte H61M-S2PV   | 2        | 0.85%   |
| Gigabyte H55M-D2H    | 2        | 0.85%   |
| Gigabyte B560M       | 2        | 0.85%   |
| Gigabyte B460HD3     | 2        | 0.85%   |
| ASUS H110M-K         | 2        | 0.85%   |
| Unknown              | 2        | 0.85%   |
| Supermicro X9DAi     | 1        | 0.43%   |
| Shuttle SH87R        | 1        | 0.43%   |
| Pegatron Pro         | 1        | 0.43%   |
| Pegatron NC890AA-ABA | 1        | 0.43%   |
| MSI MS-7B86          | 1        | 0.43%   |
| MSI MS-7B79          | 1        | 0.43%   |
| MSI MS-7984          | 1        | 0.43%   |
| MSI MS-7982          | 1        | 0.43%   |
| MSI MS-7978          | 1        | 0.43%   |
| MSI MS-7816          | 1        | 0.43%   |
| MSI MS-7788          | 1        | 0.43%   |
| MSI Elite            | 1        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 28       | 11.91%  |
| 2012 | 24       | 10.21%  |
| 2014 | 19       | 8.09%   |
| 2013 | 19       | 8.09%   |
| 2021 | 17       | 7.23%   |
| 2020 | 17       | 7.23%   |
| 2010 | 17       | 7.23%   |
| 2019 | 16       | 6.81%   |
| 2016 | 16       | 6.81%   |
| 2011 | 14       | 5.96%   |
| 2017 | 13       | 5.53%   |
| 2015 | 13       | 5.53%   |
| 2009 | 12       | 5.11%   |
| 2007 | 4        | 1.7%    |
| 2008 | 3        | 1.28%   |
| 2022 | 2        | 0.85%   |
| 2006 | 1        | 0.43%   |

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
| Disabled | 233      | 99.15%  |
| Enabled  | 2        | 0.85%   |

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
| 16.01-24.0  | 61       | 25.21%  |
| 32.01-64.0  | 46       | 19.01%  |
| 8.01-16.0   | 46       | 19.01%  |
| 3.01-4.0    | 35       | 14.46%  |
| 4.01-8.0    | 30       | 12.4%   |
| 64.01-256.0 | 13       | 5.37%   |
| 1.01-2.0    | 7        | 2.89%   |
| 24.01-32.0  | 3        | 1.24%   |
| 2.01-3.0    | 1        | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 95       | 36.4%   |
| 2.01-3.0   | 50       | 19.16%  |
| 4.01-8.0   | 39       | 14.94%  |
| 3.01-4.0   | 25       | 9.58%   |
| 8.01-16.0  | 24       | 9.2%    |
| 0.51-1.0   | 21       | 8.05%   |
| 0.01-0.5   | 4        | 1.53%   |
| 16.01-24.0 | 2        | 0.77%   |
| 24.01-32.0 | 1        | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 39.84%  |
| 2      | 67       | 27.24%  |
| 3      | 47       | 19.11%  |
| 4      | 16       | 6.5%    |
| 5      | 9        | 3.66%   |
| 6      | 3        | 1.22%   |
| 8      | 2        | 0.81%   |
| 7      | 2        | 0.81%   |
| 10     | 1        | 0.41%   |
| 0      | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 150      | 62.76%  |
| Yes       | 89       | 37.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 233      | 99.15%  |
| No        | 2        | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 141      | 59.24%  |
| Yes       | 97       | 40.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 179      | 74.9%   |
| Yes       | 60       | 25.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Israel  | 235      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Tel Aviv            | 93       | 37.5%   |
| Haifa               | 21       | 8.47%   |
| Ramat Gan           | 20       | 8.06%   |
| Petaẖ Tiqwa       | 13       | 5.24%   |
| Rishon LeZiyyon     | 9        | 3.63%   |
| Jerusalem           | 8        | 3.23%   |
| Qiryat Ata          | 6        | 2.42%   |
| Rehovot             | 4        | 1.61%   |
| Ramat HaSharon      | 4        | 1.61%   |
| Holon               | 4        | 1.61%   |
| Herzliya            | 4        | 1.61%   |
| Ashdod              | 4        | 1.61%   |
| Netanya             | 3        | 1.21%   |
| Nahariya            | 3        | 1.21%   |
| Kfar Saba           | 3        | 1.21%   |
| Givatayim           | 3        | 1.21%   |
| Rosh HaAyin         | 2        | 0.81%   |
| Raanana             | 2        | 0.81%   |
| Pardes Hanna Karkur | 2        | 0.81%   |
| Ness Ziona          | 2        | 0.81%   |
| Hod HaSharon        | 2        | 0.81%   |
| Beersheba           | 2        | 0.81%   |
| Be'er Ya'aqov       | 2        | 0.81%   |
| Bat Yam             | 2        | 0.81%   |
| Ashquelon           | 2        | 0.81%   |
| Afula               | 2        | 0.81%   |
| Yehud               | 1        | 0.4%    |
| Tiberias            | 1        | 0.4%    |
| Tel Mond            | 1        | 0.4%    |
| Ramla               | 1        | 0.4%    |
| Petaбє– Tiqwa   | 1        | 0.4%    |
| Petaáº– Tiqwa   | 1        | 0.4%    |
| Pardesiyya          | 1        | 0.4%    |
| Or Yehuda           | 1        | 0.4%    |
| Nazerat 'Illit      | 1        | 0.4%    |
| Meitar              | 1        | 0.4%    |
| Lod                 | 1        | 0.4%    |
| Lapid               | 1        | 0.4%    |
| Kiryat Tiv'on       | 1        | 0.4%    |
| Kiryat Ono          | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 103      | 182    | 23.57%  |
| Seagate                   | 57       | 94     | 13.04%  |
| Samsung Electronics       | 50       | 79     | 11.44%  |
| Hitachi                   | 34       | 57     | 7.78%   |
| Kingston                  | 33       | 39     | 7.55%   |
| SanDisk                   | 27       | 33     | 6.18%   |
| Toshiba                   | 22       | 27     | 5.03%   |
| Crucial                   | 18       | 30     | 4.12%   |
| Transcend                 | 11       | 14     | 2.52%   |
| Intel                     | 10       | 13     | 2.29%   |
| Corsair                   | 10       | 14     | 2.29%   |
| HGST                      | 8        | 10     | 1.83%   |
| XPG                       | 5        | 11     | 1.14%   |
| Micron Technology         | 5        | 7      | 1.14%   |
| SK hynix                  | 4        | 4      | 0.92%   |
| Phison                    | 4        | 5      | 0.92%   |
| A-DATA Technology         | 4        | 5      | 0.92%   |
| Silicon Motion            | 3        | 3      | 0.69%   |
| Unknown                   | 2        | 3      | 0.46%   |
| SPCC                      | 2        | 2      | 0.46%   |
| OCZ                       | 2        | 2      | 0.46%   |
| Netac                     | 2        | 2      | 0.46%   |
| Micron/Crucial Technology | 2        | 2      | 0.46%   |
| China                     | 2        | 2      | 0.46%   |
| XrayDisk                  | 1        | 1      | 0.23%   |
| USB3.0                    | 1        | 1      | 0.23%   |
| UMIS                      | 1        | 1      | 0.23%   |
| TPH01204000GB             | 1        | 1      | 0.23%   |
| StoreJet                  | 1        | 1      | 0.23%   |
| Plextor                   | 1        | 1      | 0.23%   |
| Patriot                   | 1        | 1      | 0.23%   |
| OCZ-VERTEX3               | 1        | 1      | 0.23%   |
| NGFF                      | 1        | 1      | 0.23%   |
| LS600                     | 1        | 1      | 0.23%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.23%   |
| KingSpec                  | 1        | 1      | 0.23%   |
| KingDian                  | 1        | 2      | 0.23%   |
| IBM/Hitachi               | 1        | 1      | 0.23%   |
| Apple                     | 1        | 1      | 0.23%   |
| Apacer                    | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| SanDisk SSD PLUS 240GB           | 9        | 1.78%   |
| Hitachi HDS721050CLA362 500GB    | 9        | 1.78%   |
| WDC WD10EZEX-08WN4A0 1TB         | 8        | 1.58%   |
| Kingston SA400S37240G 240GB SSD  | 8        | 1.58%   |
| Samsung SSD 860 EVO 500GB        | 7        | 1.38%   |
| Toshiba DT01ACA100 1TB           | 6        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB  | 6        | 1.18%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.18%   |
| WDC WD20PURX-64P6ZY0 2TB         | 5        | 0.99%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 0.99%   |
| Samsung NVMe SSD Drive 500GB     | 5        | 0.99%   |
| Kingston SV300S37A120G 120GB SSD | 5        | 0.99%   |
| HGST HTS545050A7E680 500GB       | 5        | 0.99%   |
| Samsung NVMe SSD Drive 1TB       | 4        | 0.79%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.59%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 3        | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3        | 0.59%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 0.59%   |
| WDC WD10EADS-00L5B1 1TB          | 3        | 0.59%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 3        | 0.59%   |
| Toshiba DT01ACA050 500GB         | 3        | 0.59%   |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 0.59%   |
| Seagate ST3500418AS 500GB        | 3        | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.59%   |
| Seagate ST1000DM003-1SB102 1TB   | 3        | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.59%   |
| SanDisk SSD PLUS 480GB           | 3        | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.59%   |
| Samsung SSD 860 QVO 1TB          | 3        | 0.59%   |
| Kingston SUV400S37120G 120GB SSD | 3        | 0.59%   |
| Intel SSDPEKNW512G8 512GB        | 3        | 0.59%   |
| Hitachi HDS721050CLA360 500GB    | 3        | 0.59%   |
| Crucial CT250MX500SSD1 250GB     | 3        | 0.59%   |
| XPG NVMe SSD Drive 1024GB        | 2        | 0.39%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 2        | 0.39%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 2        | 0.39%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 2        | 0.39%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 0.39%   |
| WDC WD5000AAKX-221CA1 500GB      | 2        | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 97       | 169    | 43.11%  |
| Seagate             | 57       | 93     | 25.33%  |
| Hitachi             | 34       | 57     | 15.11%  |
| Toshiba             | 19       | 24     | 8.44%   |
| HGST                | 8        | 10     | 3.56%   |
| Samsung Electronics | 6        | 12     | 2.67%   |
| USB3.0              | 1        | 1      | 0.44%   |
| TPH01204000GB       | 1        | 1      | 0.44%   |
| IBM/Hitachi         | 1        | 1      | 0.44%   |
| Apple               | 1        | 1      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 29       | 43     | 19.33%  |
| Kingston            | 28       | 33     | 18.67%  |
| SanDisk             | 22       | 28     | 14.67%  |
| Crucial             | 12       | 22     | 8%      |
| Transcend           | 11       | 14     | 7.33%   |
| Corsair             | 9        | 12     | 6%      |
| Intel               | 7        | 8      | 4.67%   |
| WDC                 | 5        | 5      | 3.33%   |
| Micron Technology   | 5        | 7      | 3.33%   |
| A-DATA Technology   | 4        | 5      | 2.67%   |
| OCZ                 | 2        | 2      | 1.33%   |
| Netac               | 2        | 2      | 1.33%   |
| China               | 2        | 2      | 1.33%   |
| Toshiba             | 1        | 1      | 0.67%   |
| SPCC                | 1        | 1      | 0.67%   |
| Seagate             | 1        | 1      | 0.67%   |
| Plextor             | 1        | 1      | 0.67%   |
| Patriot             | 1        | 1      | 0.67%   |
| OCZ-VERTEX3         | 1        | 1      | 0.67%   |
| NGFF                | 1        | 1      | 0.67%   |
| LS600               | 1        | 1      | 0.67%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.67%   |
| KingSpec            | 1        | 1      | 0.67%   |
| KingDian            | 1        | 2      | 0.67%   |
| Apacer              | 1        | 1      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 172      | 369    | 47.38%  |
| SSD     | 124      | 196    | 34.16%  |
| NVMe    | 63       | 88     | 17.36%  |
| Unknown | 3        | 4      | 0.83%   |
| MMC     | 1        | 1      | 0.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 207      | 555    | 73.67%  |
| NVMe | 63       | 88     | 22.42%  |
| SAS  | 10       | 14     | 3.56%   |
| MMC  | 1        | 1      | 0.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 164      | 323    | 52.56%  |
| 0.51-1.0   | 77       | 118    | 24.68%  |
| 1.01-2.0   | 44       | 65     | 14.1%   |
| 2.01-3.0   | 11       | 17     | 3.53%   |
| 3.01-4.0   | 10       | 30     | 3.21%   |
| 4.01-10.0  | 5        | 7      | 1.6%    |
| 10.01-20.0 | 1        | 5      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 50       | 20.08%  |
| 101-250        | 48       | 19.28%  |
| 501-1000       | 37       | 14.86%  |
| 1001-2000      | 25       | 10.04%  |
| More than 3000 | 23       | 9.24%   |
| 2001-3000      | 23       | 9.24%   |
| 1-20           | 20       | 8.03%   |
| 21-50          | 11       | 4.42%   |
| 51-100         | 7        | 2.81%   |
| Unknown        | 5        | 2.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 108      | 42.19%  |
| 21-50          | 33       | 12.89%  |
| 101-250        | 24       | 9.38%   |
| 1001-2000      | 21       | 8.2%    |
| 251-500        | 19       | 7.42%   |
| 51-100         | 14       | 5.47%   |
| 501-1000       | 13       | 5.08%   |
| 2001-3000      | 11       | 4.3%    |
| More than 3000 | 8        | 3.13%   |
| Unknown        | 5        | 1.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| HGST HTS545050A7E680 500GB          | 5        | 7      | 12.2%   |
| WDC WD10EARS-00Y5B1 1TB             | 2        | 2      | 4.88%   |
| WDC WD10EADS-00L5B1 1TB             | 2        | 2      | 4.88%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 3      | 4.88%   |
| WDC WD5001AALS-00LWTA0 500GB        | 1        | 1      | 2.44%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 2.44%   |
| WDC WD5000AAKX-221CA1 500GB         | 1        | 1      | 2.44%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 1      | 2.44%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 2.44%   |
| WDC WD30PURX-64P6ZY0 3TB            | 1        | 1      | 2.44%   |
| WDC WD2500AAJS-00VTA0 250GB         | 1        | 1      | 2.44%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 2      | 2.44%   |
| WDC WD10EZEX-00ZF5A0 1TB            | 1        | 1      | 2.44%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1      | 2.44%   |
| WDC WD1001FALS-00J7B1 1TB           | 1        | 1      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 2.44%   |
| Seagate ST3750528AS 752GB           | 1        | 1      | 2.44%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 2.44%   |
| Seagate ST31000528AS 1TB            | 1        | 1      | 2.44%   |
| Seagate ST3000DM001-9YN166 3TB      | 1        | 1      | 2.44%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1      | 2.44%   |
| Seagate ST1000LM014-SSHD-8GB        | 1        | 1      | 2.44%   |
| Seagate ST1000DM003-1SB102 1TB      | 1        | 1      | 2.44%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 2.44%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 2      | 2.44%   |
| Hitachi HUA723020ALA640 2TB         | 1        | 1      | 2.44%   |
| Hitachi HTS545050B9A300 500GB       | 1        | 1      | 2.44%   |
| Hitachi HDS721050CLA360 500GB       | 1        | 1      | 2.44%   |
| Hitachi HDS721032CLA362 320GB       | 1        | 1      | 2.44%   |
| Hitachi HDP725050GLAT80 500GB       | 1        | 1      | 2.44%   |
| Hitachi HDP725050GLA360 500GB       | 1        | 1      | 2.44%   |
| HGST HTS721010A9E630 1TB            | 1        | 1      | 2.44%   |
| Corsair Neutron XT SSD 240GB        | 1        | 1      | 2.44%   |
| Corsair Neutron SSD 64GB            | 1        | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 35%     |
| Seagate             | 9        | 9      | 22.5%   |
| Hitachi             | 8        | 9      | 20%     |
| HGST                | 6        | 8      | 15%     |
| Corsair             | 2        | 2      | 5%      |
| Samsung Electronics | 1        | 2      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 36.84%  |
| Seagate             | 9        | 9      | 23.68%  |
| Hitachi             | 8        | 9      | 21.05%  |
| HGST                | 6        | 8      | 15.79%  |
| Samsung Electronics | 1        | 2      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 44     | 93.75%  |
| SSD  | 2        | 2      | 6.25%   |

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
| Detected | 133      | 412    | 51.15%  |
| Works    | 94       | 196    | 36.15%  |
| Malfunc  | 31       | 46     | 11.92%  |
| Failed   | 2        | 4      | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 196      | 60.12%  |
| AMD                          | 38       | 11.66%  |
| Samsung Electronics          | 21       | 6.44%   |
| SanDisk                      | 10       | 3.07%   |
| JMicron Technology           | 9        | 2.76%   |
| Micron/Crucial Technology    | 8        | 2.45%   |
| Phison Electronics           | 6        | 1.84%   |
| Kingston Technology Company  | 6        | 1.84%   |
| ASMedia Technology           | 6        | 1.84%   |
| ADATA Technology             | 6        | 1.84%   |
| Marvell Technology Group     | 5        | 1.53%   |
| SK hynix                     | 4        | 1.23%   |
| Silicon Motion               | 3        | 0.92%   |
| Nvidia                       | 3        | 0.92%   |
| Toshiba America Info Systems | 2        | 0.61%   |
| VIA Technologies             | 1        | 0.31%   |
| Union Memory (Shenzhen)      | 1        | 0.31%   |
| Transcend                    | 1        | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29       | 7.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 5.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 4.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 4.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 3.34%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 3.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 3.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 3.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 11       | 2.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 2.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.06%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.54%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.29%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.29%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.29%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.03%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.77%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.77%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.77%   |
| Intel SSD 660P Series                                                                   | 3        | 0.77%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 0.77%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 0.77%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.77%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 183      | 58.28%  |
| NVMe | 64       | 20.38%  |
| IDE  | 48       | 15.29%  |
| RAID | 17       | 5.41%   |
| SAS  | 2        | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 195      | 82.98%  |
| AMD    | 40       | 17.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 3.78%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7        | 2.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 2.1%    |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4        | 1.68%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 1.68%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 1.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 1.68%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4        | 1.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.68%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.68%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.68%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.68%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 1.26%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.26%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 1.26%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 1.26%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 1.26%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.26%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 3        | 1.26%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 1.26%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 1.26%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 1.26%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1.26%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.26%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 3        | 1.26%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.26%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.26%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 2        | 0.84%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 0.84%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 0.84%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 0.84%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.84%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.84%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.84%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.84%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.84%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.84%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 0.84%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 60       | 25.42%  |
| Intel Core i5           | 51       | 21.61%  |
| Intel Core i3           | 23       | 9.75%   |
| Other                   | 13       | 5.51%   |
| AMD Ryzen 5             | 12       | 5.08%   |
| Intel Pentium Dual-Core | 11       | 4.66%   |
| Intel Xeon              | 9        | 3.81%   |
| Intel Pentium           | 9        | 3.81%   |
| AMD Ryzen 7             | 7        | 2.97%   |
| Intel Core 2 Duo        | 6        | 2.54%   |
| AMD Ryzen 9             | 6        | 2.54%   |
| Intel Celeron           | 3        | 1.27%   |
| AMD FX                  | 3        | 1.27%   |
| AMD A8                  | 3        | 1.27%   |
| Intel Pentium Gold      | 2        | 0.85%   |
| Intel Pentium Dual      | 2        | 0.85%   |
| Intel Genuine           | 2        | 0.85%   |
| Intel Atom              | 2        | 0.85%   |
| Intel Pentium 4         | 1        | 0.42%   |
| Intel Core i9           | 1        | 0.42%   |
| Intel Core 2 Quad       | 1        | 0.42%   |
| AMD Ryzen Threadripper  | 1        | 0.42%   |
| AMD Ryzen 3 PRO         | 1        | 0.42%   |
| AMD Ryzen 3             | 1        | 0.42%   |
| AMD Phenom II X4        | 1        | 0.42%   |
| AMD Phenom              | 1        | 0.42%   |
| AMD Athlon II X3        | 1        | 0.42%   |
| AMD Athlon 64 X2        | 1        | 0.42%   |
| AMD A6                  | 1        | 0.42%   |
| AMD A10                 | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 101      | 42.8%   |
| 2      | 58       | 24.58%  |
| 6      | 32       | 13.56%  |
| 8      | 23       | 9.75%   |
| 12     | 10       | 4.24%   |
| 16     | 6        | 2.54%   |
| 10     | 2        | 0.85%   |
| 3      | 2        | 0.85%   |
| 1      | 2        | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 233      | 99.15%  |
| 2      | 2        | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 138      | 58.47%  |
| 1      | 98       | 41.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 234      | 99.57%  |
| Unknown        | 1        | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 19.11%  |
| 0x306c3    | 25       | 10.16%  |
| 0x1067a    | 17       | 6.91%   |
| 0x906e9    | 15       | 6.1%    |
| 0x306a9    | 14       | 5.69%   |
| 0x506e3    | 13       | 5.28%   |
| 0x206a7    | 13       | 5.28%   |
| 0x906ea    | 10       | 4.07%   |
| 0x90672    | 6        | 2.44%   |
| 0xa0671    | 5        | 2.03%   |
| 0xa0655    | 5        | 2.03%   |
| 0xa0653    | 5        | 2.03%   |
| 0x306e4    | 5        | 2.03%   |
| 0x106e5    | 5        | 2.03%   |
| 0x08108109 | 5        | 2.03%   |
| 0x906ed    | 4        | 1.63%   |
| 0x08701021 | 4        | 1.63%   |
| 0x08701013 | 3        | 1.22%   |
| 0x0800820d | 3        | 1.22%   |
| 0x906ec    | 2        | 0.81%   |
| 0x6fd      | 2        | 0.81%   |
| 0x206c2    | 2        | 0.81%   |
| 0x20652    | 2        | 0.81%   |
| 0x10676    | 2        | 0.81%   |
| 0x0a201009 | 2        | 0.81%   |
| 0x06003106 | 2        | 0.81%   |
| 0x06001119 | 2        | 0.81%   |
| 0x010000c8 | 2        | 0.81%   |
| 0x906eb    | 1        | 0.41%   |
| 0x906c0    | 1        | 0.41%   |
| 0x90675    | 1        | 0.41%   |
| 0x806ec    | 1        | 0.41%   |
| 0x806ea    | 1        | 0.41%   |
| 0x706a1    | 1        | 0.41%   |
| 0x506e0    | 1        | 0.41%   |
| 0x406c4    | 1        | 0.41%   |
| 0x40671    | 1        | 0.41%   |
| 0x306d4    | 1        | 0.41%   |
| 0x30673    | 1        | 0.41%   |
| 0x106c2    | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 42       | 17.8%   |
| Haswell          | 32       | 13.56%  |
| IvyBridge        | 21       | 8.9%    |
| Penryn           | 19       | 8.05%   |
| Skylake          | 17       | 7.2%    |
| SandyBridge      | 15       | 6.36%   |
| CometLake        | 13       | 5.51%   |
| Zen 2            | 10       | 4.24%   |
| Zen+             | 9        | 3.81%   |
| Nehalem          | 8        | 3.39%   |
| Zen              | 5        | 2.12%   |
| Westmere         | 5        | 2.12%   |
| Alderlake Hybrid | 5        | 2.12%   |
| Unknown          | 5        | 2.12%   |
| Zen 3            | 4        | 1.69%   |
| Piledriver       | 4        | 1.69%   |
| Icelake          | 4        | 1.69%   |
| Steamroller      | 3        | 1.27%   |
| K10              | 3        | 1.27%   |
| Silvermont       | 2        | 0.85%   |
| Core             | 2        | 0.85%   |
| Broadwell        | 2        | 0.85%   |
| Tremont          | 1        | 0.42%   |
| NetBurst         | 1        | 0.42%   |
| K8 Hammer        | 1        | 0.42%   |
| Goldmont plus    | 1        | 0.42%   |
| Bulldozer        | 1        | 0.42%   |
| Bonnell          | 1        | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 117      | 44.15%  |
| Intel  | 103      | 38.87%  |
| AMD    | 45       | 16.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 24       | 8.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 3.75%   |
| Intel HD Graphics 630                                                       | 10       | 3.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 3.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 3.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.62%   |
| Intel HD Graphics 530                                                       | 6        | 2.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 2.25%   |
| Nvidia GP107GL [Quadro P400]                                                | 5        | 1.87%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 1.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.87%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.5%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.5%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.12%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.12%   |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 1.12%   |
| Intel AlderLake-S GT1                                                       | 3        | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.12%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.12%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 1.12%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.75%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 0.75%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.75%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.75%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.75%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.75%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.75%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 100      | 41.84%  |
| 1 x Intel      | 81       | 33.89%  |
| 1 x AMD        | 36       | 15.06%  |
| Intel + Nvidia | 13       | 5.44%   |
| AMD + Nvidia   | 4        | 1.67%   |
| Intel + AMD    | 3        | 1.26%   |
| 2 x AMD        | 2        | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 153      | 62.96%  |
| Proprietary | 76       | 31.28%  |
| Unknown     | 14       | 5.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 109      | 44.49%  |
| 1.01-2.0   | 43       | 17.55%  |
| 3.01-4.0   | 23       | 9.39%   |
| 0.51-1.0   | 23       | 9.39%   |
| 7.01-8.0   | 19       | 7.76%   |
| 0.01-0.5   | 13       | 5.31%   |
| 5.01-6.0   | 6        | 2.45%   |
| 2.01-3.0   | 4        | 1.63%   |
| 8.01-16.0  | 4        | 1.63%   |
| 16.01-24.0 | 1        | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 64       | 25.7%   |
| Dell                 | 40       | 16.06%  |
| Philips              | 21       | 8.43%   |
| Goldstar             | 18       | 7.23%   |
| AOC                  | 13       | 5.22%   |
| Ancor Communications | 10       | 4.02%   |
| Hewlett-Packard      | 8        | 3.21%   |
| ViewSonic            | 7        | 2.81%   |
| Lenovo               | 6        | 2.41%   |
| ASUSTek Computer     | 6        | 2.41%   |
| BenQ                 | 4        | 1.61%   |
| Acer                 | 4        | 1.61%   |
| Unknown              | 3        | 1.2%    |
| SANYO                | 3        | 1.2%    |
| Lenovo Group Limited | 3        | 1.2%    |
| Unknown              | 3        | 1.2%    |
| Panasonic            | 2        | 0.8%    |
| NEX                  | 2        | 0.8%    |
| LG Electronics       | 2        | 0.8%    |
| HKC                  | 2        | 0.8%    |
| Hitachi              | 2        | 0.8%    |
| Gigabyte Technology  | 2        | 0.8%    |
| Eizo                 | 2        | 0.8%    |
| ___                  | 1        | 0.4%    |
| Xiaomi               | 1        | 0.4%    |
| VIE                  | 1        | 0.4%    |
| Unknown (AAA)        | 1        | 0.4%    |
| Toshiba              | 1        | 0.4%    |
| SSD                  | 1        | 0.4%    |
| Sharp                | 1        | 0.4%    |
| Sceptre Tech         | 1        | 0.4%    |
| Plain Tree Systems   | 1        | 0.4%    |
| Pioneer              | 1        | 0.4%    |
| NXG                  | 1        | 0.4%    |
| MStar                | 1        | 0.4%    |
| JRY                  | 1        | 0.4%    |
| Iiyama               | 1        | 0.4%    |
| HUAWEI               | 1        | 0.4%    |
| HannStar Display     | 1        | 0.4%    |
| Fujitsu Siemens      | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 5        | 1.89%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 4        | 1.52%   |
| Philips 222EL PHLC052 1920x1080 476x268mm 21.5-inch                  | 4        | 1.52%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 4        | 1.52%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                    | 4        | 1.52%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch | 3        | 1.14%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch | 3        | 1.14%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 3        | 1.14%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch  | 3        | 1.14%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 3        | 1.14%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                     | 3        | 1.14%   |
| Unknown                                                              | 3        | 1.14%   |
| SANYO LCD MONITOR SAN07BE 1280x1024 350x270mm 17.4-inch              | 2        | 0.76%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch | 2        | 0.76%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch    | 2        | 0.76%   |
| Samsung Electronics LCD Monitor SMBX2450 1920x1080                   | 2        | 0.76%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 2        | 0.76%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 2        | 0.76%   |
| Lenovo Group Limited LCD Monitor L24q-10                             | 2        | 0.76%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2        | 0.76%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                 | 2        | 0.76%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                    | 2        | 0.76%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 0.76%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2        | 0.76%   |
| ASUSTek Computer VG248 AUS24AB 1920x1080 531x299mm 24.0-inch         | 2        | 0.76%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                      | 2        | 0.76%   |
| ___ LCDTV16 ___0101 1920x1080                                        | 1        | 0.38%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                    | 1        | 0.38%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch        | 1        | 0.38%   |
| ViewSonic VX2237 SERIES VSC2C24 1680x1050 474x296mm 22.0-inch        | 1        | 0.38%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch            | 1        | 0.38%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch             | 1        | 0.38%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                | 1        | 0.38%   |
| ViewSonic PJ VSC2D36 3840x2160                                       | 1        | 0.38%   |
| ViewSonic LCD Monitor VSCC132 1920x1080 600x340mm 27.2-inch          | 1        | 0.38%   |
| ViewSonic LCD Monitor VA2719 Series                                  | 1        | 0.38%   |
| VIE M2487HVB VIE1919 1920x1080 520x310mm 23.8-inch                   | 1        | 0.38%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                   | 1        | 0.38%   |
| Unknown LCD Monitor SAMSUNG 3520x1080                                | 1        | 0.38%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 138      | 56.79%  |
| 1680x1050 (WSXGA+) | 16       | 6.58%   |
| 3840x2160 (4K)     | 14       | 5.76%   |
| 1280x1024 (SXGA)   | 14       | 5.76%   |
| 2560x1440 (QHD)    | 13       | 5.35%   |
| 1920x1200 (WUXGA)  | 11       | 4.53%   |
| Unknown            | 7        | 2.88%   |
| 1440x900 (WXGA+)   | 6        | 2.47%   |
| 2560x1080          | 4        | 1.65%   |
| 3440x1440          | 3        | 1.23%   |
| 1600x900 (HD+)     | 3        | 1.23%   |
| 3840x1080          | 2        | 0.82%   |
| 1920x540           | 2        | 0.82%   |
| 1366x768 (WXGA)    | 2        | 0.82%   |
| 5360x1440          | 1        | 0.41%   |
| 5120x1440          | 1        | 0.41%   |
| 4480x1440          | 1        | 0.41%   |
| 3520x1080          | 1        | 0.41%   |
| 2560x1600          | 1        | 0.41%   |
| 1360x768           | 1        | 0.41%   |
| 1280x768           | 1        | 0.41%   |
| 1024x768 (XGA)     | 1        | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 46       | 18.78%  |
| 24      | 41       | 16.73%  |
| 23      | 32       | 13.06%  |
| 27      | 29       | 11.84%  |
| Unknown | 25       | 10.2%   |
| 22      | 15       | 6.12%   |
| 19      | 9        | 3.67%   |
| 17      | 7        | 2.86%   |
| 34      | 5        | 2.04%   |
| 20      | 5        | 2.04%   |
| 18      | 4        | 1.63%   |
| 84      | 3        | 1.22%   |
| 72      | 3        | 1.22%   |
| 33      | 3        | 1.22%   |
| 31      | 3        | 1.22%   |
| 54      | 2        | 0.82%   |
| 32      | 2        | 0.82%   |
| 60      | 1        | 0.41%   |
| 52      | 1        | 0.41%   |
| 49      | 1        | 0.41%   |
| 48      | 1        | 0.41%   |
| 43      | 1        | 0.41%   |
| 42      | 1        | 0.41%   |
| 40      | 1        | 0.41%   |
| 29      | 1        | 0.41%   |
| 26      | 1        | 0.41%   |
| 16      | 1        | 0.41%   |
| 15      | 1        | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 97       | 40.76%  |
| 401-500     | 70       | 29.41%  |
| Unknown     | 25       | 10.5%   |
| 701-800     | 10       | 4.2%    |
| 301-350     | 8        | 3.36%   |
| 351-400     | 7        | 2.94%   |
| 601-700     | 6        | 2.52%   |
| 1501-2000   | 6        | 2.52%   |
| 1001-1500   | 6        | 2.52%   |
| 901-1000    | 2        | 0.84%   |
| 801-900     | 1        | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 149      | 64.22%  |
| 16/10   | 39       | 16.81%  |
| Unknown | 24       | 10.34%  |
| 5/4     | 10       | 4.31%   |
| 21/9    | 5        | 2.16%   |
| 4/3     | 4        | 1.72%   |
| 1.96    | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 108      | 45%     |
| 301-350        | 30       | 12.5%   |
| 151-200        | 25       | 10.42%  |
| Unknown        | 25       | 10.42%  |
| 351-500        | 14       | 5.83%   |
| 251-300        | 14       | 5.83%   |
| More than 1000 | 11       | 4.58%   |
| 141-150        | 7        | 2.92%   |
| 501-1000       | 4        | 1.67%   |
| 131-140        | 1        | 0.42%   |
| 101-110        | 1        | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 131      | 56.71%  |
| 101-120 | 56       | 24.24%  |
| Unknown | 25       | 10.82%  |
| 1-50    | 11       | 4.76%   |
| 121-160 | 5        | 2.16%   |
| 161-240 | 3        | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 183      | 75.93%  |
| 2     | 41       | 17.01%  |
| 0     | 15       | 6.22%   |
| 4     | 1        | 0.41%   |
| 3     | 1        | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 150      | 44.12%  |
| Intel                           | 102      | 30%     |
| Qualcomm Atheros                | 23       | 6.76%   |
| Ralink Technology               | 13       | 3.82%   |
| TP-Link                         | 9        | 2.65%   |
| Edimax Technology               | 6        | 1.76%   |
| Broadcom                        | 4        | 1.18%   |
| Ralink                          | 3        | 0.88%   |
| ASIX Electronics                | 3        | 0.88%   |
| Xiaomi                          | 2        | 0.59%   |
| Qualcomm Atheros Communications | 2        | 0.59%   |
| Nvidia                          | 2        | 0.59%   |
| Marvell Technology Group        | 2        | 0.59%   |
| D-Link                          | 2        | 0.59%   |
| Broadcom Limited                | 2        | 0.59%   |
| Aquantia                        | 2        | 0.59%   |
| U.S. Robotics                   | 1        | 0.29%   |
| Texas Instruments               | 1        | 0.29%   |
| STMicroelectronics              | 1        | 0.29%   |
| Samsung Electronics             | 1        | 0.29%   |
| ROCCAT                          | 1        | 0.29%   |
| Microsoft                       | 1        | 0.29%   |
| Mellanox Technologies           | 1        | 0.29%   |
| MediaTek                        | 1        | 0.29%   |
| Huawei Technologies             | 1        | 0.29%   |
| GDMicroelectronics              | 1        | 0.29%   |
| Davicom Semiconductor           | 1        | 0.29%   |
| BUFFALO                         | 1        | 0.29%   |
| Accton Technology               | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 115      | 30.5%   |
| Intel Ethernet Connection (2) I219-V                              | 17       | 4.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 13       | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 3.45%   |
| Intel Wi-Fi 6 AX200                                               | 9        | 2.39%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 2.12%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 7        | 1.86%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.59%   |
| Realtek 802.11ac NIC                                              | 5        | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                             | 4        | 1.06%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 3        | 0.8%    |
| TP-Link Archer T4U ver.3                                          | 3        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3        | 0.8%    |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3        | 0.8%    |
| Intel Wireless-AC 9260                                            | 3        | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 3        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.53%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 2        | 0.53%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.53%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2        | 0.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.53%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 29       | 27.36%  |
| Realtek Semiconductor           | 26       | 24.53%  |
| Ralink Technology               | 13       | 12.26%  |
| Qualcomm Atheros                | 10       | 9.43%   |
| TP-Link                         | 9        | 8.49%   |
| Edimax Technology               | 6        | 5.66%   |
| Ralink                          | 3        | 2.83%   |
| Broadcom                        | 3        | 2.83%   |
| Qualcomm Atheros Communications | 2        | 1.89%   |
| D-Link                          | 2        | 1.89%   |
| Microsoft                       | 1        | 0.94%   |
| MediaTek                        | 1        | 0.94%   |
| BUFFALO                         | 1        | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 9        | 8.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 7        | 6.48%   |
| Realtek 802.11ac NIC                                                                          | 5        | 4.63%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 3        | 2.78%   |
| TP-Link Archer T4U ver.3                                                                      | 3        | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3        | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 2.78%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 2.78%   |
| Intel Wireless-AC 9260                                                                        | 3        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 3        | 2.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 3        | 2.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 1.85%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 1.85%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 1.85%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 1.85%   |
| Intel Wireless 3165                                                                           | 2        | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2        | 1.85%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 2        | 1.85%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                      | 2        | 1.85%   |
| Edimax AC600 USB                                                                              | 2        | 1.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.93%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.93%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.93%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.93%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 0.93%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.93%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.93%   |
| Ralink RT3572 Wireless Adapter                                                                | 1        | 0.93%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 0.93%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 136      | 53.13%  |
| Intel                    | 88       | 34.38%  |
| Qualcomm Atheros         | 13       | 5.08%   |
| ASIX Electronics         | 3        | 1.17%   |
| Xiaomi                   | 2        | 0.78%   |
| Nvidia                   | 2        | 0.78%   |
| Marvell Technology Group | 2        | 0.78%   |
| Broadcom Limited         | 2        | 0.78%   |
| Aquantia                 | 2        | 0.78%   |
| Samsung Electronics      | 1        | 0.39%   |
| Mellanox Technologies    | 1        | 0.39%   |
| Huawei Technologies      | 1        | 0.39%   |
| Davicom Semiconductor    | 1        | 0.39%   |
| Broadcom                 | 1        | 0.39%   |
| Accton Technology        | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 115      | 43.56%  |
| Intel Ethernet Connection (2) I219-V                              | 17       | 6.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 4.92%   |
| Intel I211 Gigabit Network Connection                             | 13       | 4.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13       | 4.92%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 4        | 1.52%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3        | 1.14%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.14%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.76%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.76%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.76%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.76%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.38%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.38%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.38%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.38%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.38%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.38%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 233      | 69.55%  |
| WiFi     | 97       | 28.96%  |
| Modem    | 4        | 1.19%   |
| Unknown  | 1        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 188      | 75.81%  |
| WiFi     | 60       | 24.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 172      | 72.57%  |
| 2     | 52       | 21.94%  |
| 3     | 11       | 4.64%   |
| 0     | 2        | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 205      | 84.02%  |
| Yes  | 39       | 15.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 40.32%  |
| Cambridge Silicon Radio         | 22       | 35.48%  |
| Qualcomm Atheros Communications | 4        | 6.45%   |
| Realtek Semiconductor           | 3        | 4.84%   |
| ASUSTek Computer                | 3        | 4.84%   |
| Broadcom                        | 2        | 3.23%   |
| TP-Link                         | 1        | 1.61%   |
| Realtek                         | 1        | 1.61%   |
| IMC Networks                    | 1        | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22       | 35.48%  |
| Intel AX200 Bluetooth                               | 8        | 12.9%   |
| Intel Bluetooth wireless interface                  | 5        | 8.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 6.45%   |
| Realtek Bluetooth Radio                             | 3        | 4.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 4.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 3.23%   |
| ASUS Bluetooth Adapter                              | 2        | 3.23%   |
| TP-Link UB500 Adapter                               | 1        | 1.61%   |
| Realtek Bluetooth Radio                             | 1        | 1.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.61%   |
| Intel Bluetooth Device                              | 1        | 1.61%   |
| Intel AX210 Bluetooth                               | 1        | 1.61%   |
| Intel AX201 Bluetooth                               | 1        | 1.61%   |
| IMC Networks Bluetooth Device                       | 1        | 1.61%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.61%   |
| ASUS BCM20702A0                                     | 1        | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 187      | 45.95%  |
| Nvidia                  | 112      | 27.52%  |
| AMD                     | 59       | 14.5%   |
| C-Media Electronics     | 9        | 2.21%   |
| Creative Labs           | 6        | 1.47%   |
| XMOS                    | 4        | 0.98%   |
| Creative Technology     | 4        | 0.98%   |
| Texas Instruments       | 3        | 0.74%   |
| Focusrite-Novation      | 3        | 0.74%   |
| Logitech                | 2        | 0.49%   |
| Kingston Technology     | 2        | 0.49%   |
| Cambridge Silicon Radio | 2        | 0.49%   |
| VIA Technologies        | 1        | 0.25%   |
| SteelSeries ApS         | 1        | 0.25%   |
| Samson Technologies     | 1        | 0.25%   |
| Razer USA               | 1        | 0.25%   |
| Microsoft               | 1        | 0.25%   |
| Meridian                | 1        | 0.25%   |
| JMTek                   | 1        | 0.25%   |
| iCreate Technologies    | 1        | 0.25%   |
| GN Netcom               | 1        | 0.25%   |
| Giga-Byte Technology    | 1        | 0.25%   |
| Generalplus Technology  | 1        | 0.25%   |
| FIFINE Microphones      | 1        | 0.25%   |
| EGO SYStems             | 1        | 0.25%   |
| Unknown                 | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23       | 5.05%   |
| Intel 200 Series PCH HD Audio                                              | 22       | 4.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21       | 4.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21       | 4.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 3.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 15       | 3.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 3.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 13       | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 12       | 2.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 12       | 2.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 2.42%   |
| Nvidia GP104 High Definition Audio Controller                              | 9        | 1.98%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 1.76%   |
| Nvidia High Definition Audio Controller                                    | 8        | 1.76%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 1.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 1.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 1.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 1.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.32%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 1.32%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                         | 5        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 5        | 1.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.1%    |
| AMD FCH Azalia Controller                                                  | 5        | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 0.88%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 0.88%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 4        | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 33       | 22.92%  |
| Unknown             | 21       | 14.58%  |
| Corsair             | 17       | 11.81%  |
| Crucial             | 16       | 11.11%  |
| G.Skill             | 14       | 9.72%   |
| SK hynix            | 10       | 6.94%   |
| Samsung Electronics | 9        | 6.25%   |
| Ramaxel Technology  | 6        | 4.17%   |
| Micron Technology   | 6        | 4.17%   |
| Transcend           | 3        | 2.08%   |
| Team                | 3        | 2.08%   |
| GeIL                | 2        | 1.39%   |
| Unknown (09D5)      | 1        | 0.69%   |
| Patriot             | 1        | 0.69%   |
| KETECH              | 1        | 0.69%   |
| A-DATA Technology   | 1        | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 3        | 1.92%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s       | 3        | 1.92%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 2        | 1.28%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2        | 1.28%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 2        | 1.28%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s    | 2        | 1.28%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 2        | 1.28%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 2        | 1.28%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s        | 2        | 1.28%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s          | 2        | 1.28%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s     | 2        | 1.28%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 2        | 1.28%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s      | 2        | 1.28%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 2        | 1.28%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s       | 2        | 1.28%   |
| Crucial RAM CT16G4DFD832A.C16FP 16384MB DIMM DDR4 3200MT/s | 2        | 1.28%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s      | 2        | 1.28%   |
| Unknown RAM Module 8GB DIMM                                | 1        | 0.64%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1        | 0.64%   |
| Unknown RAM Module 8192MB DIMM 800MT/s                     | 1        | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                   | 1        | 0.64%   |
| Unknown RAM Module 4GB DIMM 667MT/s                        | 1        | 0.64%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 0.64%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 1        | 0.64%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 1        | 0.64%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                   | 1        | 0.64%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                     | 1        | 0.64%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1        | 0.64%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 1        | 0.64%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                     | 1        | 0.64%   |
| Unknown (09D5) RAM Module 8GB DIMM DDR4 2400MT/s           | 1        | 0.64%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s           | 1        | 0.64%   |
| Transcend RAM JM2666HLE-16G 16GB DIMM DDR4 2667MT/s        | 1        | 0.64%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM 1600MT/s               | 1        | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 72       | 56.25%  |
| DDR3    | 30       | 23.44%  |
| Unknown | 15       | 11.72%  |
| DDR2    | 6        | 4.69%   |
| SDRAM   | 4        | 3.13%   |
| DDR     | 1        | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 125      | 97.66%  |
| SODIMM | 3        | 2.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 41       | 29.93%  |
| 4096  | 37       | 27.01%  |
| 16384 | 33       | 24.09%  |
| 2048  | 18       | 13.14%  |
| 32768 | 4        | 2.92%   |
| 1024  | 4        | 2.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 14.69%  |
| 3200    | 18       | 12.59%  |
| 2133    | 13       | 9.09%   |
| 2400    | 12       | 8.39%   |
| 800     | 11       | 7.69%   |
| 1333    | 10       | 6.99%   |
| 3600    | 7        | 4.9%    |
| 2667    | 7        | 4.9%    |
| 3466    | 5        | 3.5%    |
| Unknown | 4        | 2.8%    |
| 1867    | 3        | 2.1%    |
| 667     | 3        | 2.1%    |
| 3800    | 2        | 1.4%    |
| 3151    | 2        | 1.4%    |
| 2933    | 2        | 1.4%    |
| 2000    | 2        | 1.4%    |
| 1866    | 2        | 1.4%    |
| 1800    | 2        | 1.4%    |
| 49926   | 1        | 0.7%    |
| 5600    | 1        | 0.7%    |
| 4800    | 1        | 0.7%    |
| 4400    | 1        | 0.7%    |
| 3733    | 1        | 0.7%    |
| 3666    | 1        | 0.7%    |
| 3400    | 1        | 0.7%    |
| 3334    | 1        | 0.7%    |
| 3266    | 1        | 0.7%    |
| 3066    | 1        | 0.7%    |
| 3000    | 1        | 0.7%    |
| 2800    | 1        | 0.7%    |
| 2666    | 1        | 0.7%    |
| 2134    | 1        | 0.7%    |
| 1648    | 1        | 0.7%    |
| 1400    | 1        | 0.7%    |
| 400     | 1        | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 7        | 50%     |
| Samsung Electronics   | 2        | 14.29%  |
| Canon                 | 2        | 14.29%  |
| Lexmark International | 1        | 7.14%   |
| GODEX INTERNATIONAL   | 1        | 7.14%   |
| Brother Industries    | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung M2070 Series          | 2        | 14.29%  |
| HP Officejet 4500 G510g-m     | 2        | 14.29%  |
| HP DeskJet 4670 series        | 2        | 14.29%  |
| Lexmark International CS417dn | 1        | 7.14%   |
| HP Printing Support           | 1        | 7.14%   |
| HP LaserJet M14-M17           | 1        | 7.14%   |
| HP Deskjet 4640 series        | 1        | 7.14%   |
| GODEX INTERNATIONAL DT2       | 1        | 7.14%   |
| Canon TR7500 series           | 1        | 7.14%   |
| Canon PIXMA MX490 Series      | 1        | 7.14%   |
| Brother MFC-J497DW            | 1        | 7.14%   |

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
| Logitech                      | 20       | 33.33%  |
| Microsoft                     | 15       | 25%     |
| Generalplus Technology        | 5        | 8.33%   |
| Samsung Electronics           | 4        | 6.67%   |
| Microdia                      | 3        | 5%      |
| IMC Networks                  | 2        | 3.33%   |
| Apple                         | 2        | 3.33%   |
| Xiaomi                        | 1        | 1.67%   |
| Sunplus Innovation Technology | 1        | 1.67%   |
| Realtek Semiconductor         | 1        | 1.67%   |
| Quanta                        | 1        | 1.67%   |
| Jieli Technology              | 1        | 1.67%   |
| Hewlett-Packard               | 1        | 1.67%   |
| Chicony Electronics           | 1        | 1.67%   |
| Aveo Technology               | 1        | 1.67%   |
| Alcor Micro                   | 1        | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                           | 12       | 20%     |
| Samsung Galaxy A5 (MTP)                             | 4        | 6.67%   |
| Logitech Webcam C310                                | 3        | 5%      |
| Logitech Webcam C270                                | 3        | 5%      |
| Generalplus GENERAL WEBCAM                          | 3        | 5%      |
| Microdia USB 2.0 Camera                             | 2        | 3.33%   |
| Logitech C922 Pro Stream Webcam                     | 2        | 3.33%   |
| Generalplus 2K HD Camera                            | 2        | 3.33%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                  | 1        | 1.67%   |
| Sunplus HD WebCam                                   | 1        | 1.67%   |
| Realtek Web Camera                                  | 1        | 1.67%   |
| Quanta Astro HD Camera                              | 1        | 1.67%   |
| Microsoft MicrosoftÂ LifeCam Studio                | 1        | 1.67%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 1.67%   |
| Microsoft MicrosoftÂ LifeCam Cinema                | 1        | 1.67%   |
| Microdia Integrated Camera                          | 1        | 1.67%   |
| Logitech Webcam C930e                               | 1        | 1.67%   |
| Logitech Webcam C925e                               | 1        | 1.67%   |
| Logitech Webcam C920-C                              | 1        | 1.67%   |
| Logitech Webcam C170                                | 1        | 1.67%   |
| Logitech QuickCam E 3500                            | 1        | 1.67%   |
| Logitech Mic (Fusion)                               | 1        | 1.67%   |
| Logitech HD Webcam C615                             | 1        | 1.67%   |
| Logitech HD Webcam C525                             | 1        | 1.67%   |
| Logitech HD Pro Webcam C920                         | 1        | 1.67%   |
| Logitech C930c                                      | 1        | 1.67%   |
| Logitech C920 PRO HD Webcam                         | 1        | 1.67%   |
| Logitech BRIO Ultra HD Webcam                       | 1        | 1.67%   |
| Jieli USB PHY 2.0                                   | 1        | 1.67%   |
| IMC Networks XHC Camera                             | 1        | 1.67%   |
| IMC Networks Integrated Camera                      | 1        | 1.67%   |
| HP Webcam HD 2300                                   | 1        | 1.67%   |
| Chicony Gateway Webcam                              | 1        | 1.67%   |
| Aveo UVC camera (Bresser microscope)                | 1        | 1.67%   |
| Apple iPhone5/5C/5S/6                               | 1        | 1.67%   |
| Apple iPad 2 (3G; 64GB)                             | 1        | 1.67%   |
| Alcor Micro USB 2.0 PC Camera                       | 1        | 1.67%   |

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
| 0     | 202      | 83.82%  |
| 1     | 34       | 14.11%  |
| 2     | 5        | 2.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 46.51%  |
| Net/wireless             | 13       | 30.23%  |
| Communication controller | 6        | 13.95%  |
| Camera                   | 3        | 6.98%   |
| Bluetooth                | 1        | 2.33%   |

