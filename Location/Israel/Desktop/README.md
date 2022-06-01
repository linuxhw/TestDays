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

Total: 310

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo     | ThinkCentre M81 5049W15     | [df4917e32f](https://linux-hardware.org/?probe=df4917e32f) | May 28, 2022 |
| ASUSTek    | ProArt Z690-CREATOR WIFI    | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Gigabyte   | Z690 AORUS ELITE AX DDR4    | [7ba08ba4b5](https://linux-hardware.org/?probe=7ba08ba4b5) | May 21, 2022 |
| Gigabyte   | Z690 AORUS ELITE AX DDR4    | [81aa40219e](https://linux-hardware.org/?probe=81aa40219e) | May 21, 2022 |
| HP         | 8298                        | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| Intel      | DH77EB AAG39073-304         | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Gigabyte   | Z170X-Gaming 7              | [813349f89b](https://linux-hardware.org/?probe=813349f89b) | May 17, 2022 |
| Intel      | DH77EB AAG39073-304         | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel      | DH77EB AAG39073-304         | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Lenovo     | 3102 NOK                    | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| ASUSTek    | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| Gigabyte   | B450M DS3H-CF               | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| ASUSTek    | D540MA-C                    | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Gigabyte   | AB350M-Gaming 3-CF          | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Lenovo     | NO DPK                      | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| ASUSTek    | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek    | ROG STRIX Z390-E GAMING     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| MSI        | H61M-E22                    | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| ASUSTek    | PRIME Z690M-PLUS D4         | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| ASUSTek    | Z97-DELUXE                  | [8b2771b584](https://linux-hardware.org/?probe=8b2771b584) | Mar 07, 2022 |
| ASUSTek    | H97M-E                      | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| Gigabyte   | GA-880GM-UD2H               | [1398ef93be](https://linux-hardware.org/?probe=1398ef93be) | Feb 22, 2022 |
| Dell       | 0WN7Y6 A01                  | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| ASRock     | B450 Pro4                   | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASRock     | B450 Pro4                   | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| ASUSTek    | M5A78L-M LX3 PLUS           | [9295ca6d10](https://linux-hardware.org/?probe=9295ca6d10) | Feb 13, 2022 |
| Gigabyte   | H55M-D2H                    | [f85ece5bf7](https://linux-hardware.org/?probe=f85ece5bf7) | Feb 12, 2022 |
| Gigabyte   | B460M DS3H                  | [136ea58ce8](https://linux-hardware.org/?probe=136ea58ce8) | Feb 11, 2022 |
| Shuttle    | FH87                        | [1588ed0352](https://linux-hardware.org/?probe=1588ed0352) | Feb 09, 2022 |
| Lenovo     | ThinkCentre M91p 4518NR8    | [cc2ea0bba2](https://linux-hardware.org/?probe=cc2ea0bba2) | Feb 08, 2022 |
| HP         | 2B34                        | [a44a14f358](https://linux-hardware.org/?probe=a44a14f358) | Feb 08, 2022 |
| Alienware  | 07W25T A00                  | [0bd0a24a20](https://linux-hardware.org/?probe=0bd0a24a20) | Feb 02, 2022 |
| Alienware  | 07W25T A00                  | [852eb2b367](https://linux-hardware.org/?probe=852eb2b367) | Feb 02, 2022 |
| Lenovo     | ThinkCentre M91p 4524B96    | [5a90acd016](https://linux-hardware.org/?probe=5a90acd016) | Jan 31, 2022 |
| Gigabyte   | Z97X-Gaming 5               | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| Gigabyte   | B460 HD3                    | [48e8e52d84](https://linux-hardware.org/?probe=48e8e52d84) | Jan 13, 2022 |
| ASUSTek    | PRIME B560M-K               | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Supermicro | X9DAi                       | [0f78e87ab1](https://linux-hardware.org/?probe=0f78e87ab1) | Jan 03, 2022 |
| Supermicro | X9DAi                       | [a86bdc7f4d](https://linux-hardware.org/?probe=a86bdc7f4d) | Jan 03, 2022 |
| Gigabyte   | B75M-D3V                    | [0f43701ca4](https://linux-hardware.org/?probe=0f43701ca4) | Dec 20, 2021 |
| Gigabyte   | P55-UD3L                    | [6d2be9add8](https://linux-hardware.org/?probe=6d2be9add8) | Dec 17, 2021 |
| AZW        | U59                         | [021639604a](https://linux-hardware.org/?probe=021639604a) | Dec 15, 2021 |
| Gigabyte   | Z270XP-SLI-CF               | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Gigabyte   | Z97-D3H-CF                  | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| ASUSTek    | PRIME B560M-K               | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| Gigabyte   | H87-D3H-CF                  | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Gigabyte   | B460 HD3                    | [19bfb20536](https://linux-hardware.org/?probe=19bfb20536) | Nov 19, 2021 |
| ASRock     | H370M Pro4                  | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| Gigabyte   | B560M H                     | [358ab5a9fe](https://linux-hardware.org/?probe=358ab5a9fe) | Nov 15, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| Gigabyte   | B560M DS3H                  | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek    | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek    | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| ASUSTek    | TUF Gaming B550-PLUS        | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
| Dell       | 0XHGV1 A00                  | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| Dell       | 0V8F20 A01                  | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| MSI        | G41TM-P33                   | [8216f8bfae](https://linux-hardware.org/?probe=8216f8bfae) | Oct 24, 2021 |
| Foxconn    | H81MXV FAB A                | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| ASUSTek    | Z170-K                      | [b39ed56cc9](https://linux-hardware.org/?probe=b39ed56cc9) | Oct 19, 2021 |
| Gigabyte   | G31M-ES2L                   | [aa3b1b645e](https://linux-hardware.org/?probe=aa3b1b645e) | Oct 16, 2021 |
| ASUSTek    | Rampage II Extreme          | [e3149252a0](https://linux-hardware.org/?probe=e3149252a0) | Oct 16, 2021 |
| ASUSTek    | Rampage II Extreme          | [b78fec94ab](https://linux-hardware.org/?probe=b78fec94ab) | Oct 16, 2021 |
| Dell       | 0XHGV1 A00                  | [853a82796c](https://linux-hardware.org/?probe=853a82796c) | Oct 15, 2021 |
| ASUSTek    | PRIME Z390-A                | [f86adc0f8d](https://linux-hardware.org/?probe=f86adc0f8d) | Oct 12, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASUSTek    | P8H61-M LX R2.0             | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| HP         | 1497                        | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| ASUSTek    | H81M-E R2.0                 | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| ASUSTek    | Z170-K                      | [e5e1953ed8](https://linux-hardware.org/?probe=e5e1953ed8) | Sep 05, 2021 |
| HP         | 158A                        | [6c22e51bfc](https://linux-hardware.org/?probe=6c22e51bfc) | Sep 04, 2021 |
| Dell       | 06X1TJ A00                  | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| ASUSTek    | PRIME Z370-P II             | [68213450a7](https://linux-hardware.org/?probe=68213450a7) | Aug 14, 2021 |
| Lenovo     | 3102 SDK0K13476 WIN 3306... | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| Gigabyte   | X58-USB3                    | [8a48f8d2bc](https://linux-hardware.org/?probe=8a48f8d2bc) | Jul 31, 2021 |
| Gigabyte   | Z270XP-SLI-CF               | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| ASUSTek    | P8P67 DELUXE                | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| ASUSTek    | P7H55-M PRO                 | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| Dell       | 06X1TJ A00                  | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell       | 06X1TJ A00                  | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| Dell       | 06X1TJ A00                  | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell       | 0GMM0G A00                  | [2c9050ccd9](https://linux-hardware.org/?probe=2c9050ccd9) | Jul 03, 2021 |
| Gigabyte   | Z270XP-SLI-CF               | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| Pegatron   | 2A94h                       | [5475faba11](https://linux-hardware.org/?probe=5475faba11) | Jun 19, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| Gigabyte   | B360M HD3                   | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| Gigabyte   | B360M HD3                   | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| ASUSTek    | PRIME Z490-P                | [59cf3396c0](https://linux-hardware.org/?probe=59cf3396c0) | Jun 13, 2021 |
| ASRock     | H370M Pro4                  | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| ASUSTek    | PRIME X470-PRO              | [aea7394e24](https://linux-hardware.org/?probe=aea7394e24) | Jun 01, 2021 |
| ASUSTek    | H110M-A/M.2                 | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Intel      | DP55WB AAE64798-205         | [a760607f4e](https://linux-hardware.org/?probe=a760607f4e) | May 27, 2021 |
| Gigabyte   | B450 AORUS M                | [a7a67287a3](https://linux-hardware.org/?probe=a7a67287a3) | May 26, 2021 |
| Intel      | DP55WB AAE64798-205         | [7070bcfa9a](https://linux-hardware.org/?probe=7070bcfa9a) | May 24, 2021 |
| Gigabyte   | H61M-S1                     | [2f7da43eb2](https://linux-hardware.org/?probe=2f7da43eb2) | May 23, 2021 |
| ASUSTek    | PRIME Z590M-PLUS            | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
| Gigabyte   | H81M-S2PV                   | [c8a2e1e897](https://linux-hardware.org/?probe=c8a2e1e897) | May 06, 2021 |
| Lenovo     | 3102 SDK0J40697 WIN 3305... | [e0e3552e96](https://linux-hardware.org/?probe=e0e3552e96) | Apr 28, 2021 |
| ASRock     | H370M Pro4                  | [be75ff3da4](https://linux-hardware.org/?probe=be75ff3da4) | Apr 25, 2021 |
| HP         | 3397                        | [08ea9bb12b](https://linux-hardware.org/?probe=08ea9bb12b) | Apr 22, 2021 |
| Gigabyte   | G41MT-S2                    | [0752e29519](https://linux-hardware.org/?probe=0752e29519) | Apr 21, 2021 |
| Gigabyte   | G41MT-S2                    | [6dd3daccc6](https://linux-hardware.org/?probe=6dd3daccc6) | Apr 21, 2021 |
| Dell       | 0J37VM A01                  | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell       | 0J37VM A01                  | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| ASUSTek    | PRIME B365M-A               | [c5109bab9c](https://linux-hardware.org/?probe=c5109bab9c) | Apr 17, 2021 |
| ASUSTek    | PRIME B250M-A               | [95f2d11b2e](https://linux-hardware.org/?probe=95f2d11b2e) | Apr 16, 2021 |
| ASUSTek    | D540MA-C                    | [945b05bee8](https://linux-hardware.org/?probe=945b05bee8) | Apr 16, 2021 |
| ASRock     | H370M Pro4                  | [e6b5c6b72b](https://linux-hardware.org/?probe=e6b5c6b72b) | Apr 11, 2021 |
| ASUSTek    | H97M-E                      | [9881ce611d](https://linux-hardware.org/?probe=9881ce611d) | Apr 09, 2021 |
| ASUSTek    | M5A97 R2.0                  | [a5823c243c](https://linux-hardware.org/?probe=a5823c243c) | Apr 02, 2021 |
| MSI        | H87-G43 GAMING              | [5bd49fbcea](https://linux-hardware.org/?probe=5bd49fbcea) | Mar 28, 2021 |
| Gigabyte   | G31M-S2C                    | [8d84b967f2](https://linux-hardware.org/?probe=8d84b967f2) | Mar 25, 2021 |
| Gigabyte   | G31M-S2C                    | [91a8d56cfd](https://linux-hardware.org/?probe=91a8d56cfd) | Mar 25, 2021 |
| Gigabyte   | G41M-Combo                  | [feb8706c98](https://linux-hardware.org/?probe=feb8706c98) | Mar 18, 2021 |
| ASRock     | H71M-DGS                    | [30424c4317](https://linux-hardware.org/?probe=30424c4317) | Mar 18, 2021 |
| MSI        | H170A GAMING PRO            | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Gigabyte   | Z490M                       | [6eecc1d3cc](https://linux-hardware.org/?probe=6eecc1d3cc) | Mar 15, 2021 |
| Lenovo     | ThinkCentre M81 5049PA4     | [0fbdab8514](https://linux-hardware.org/?probe=0fbdab8514) | Mar 11, 2021 |
| Gigabyte   | G31M-S2C                    | [7140c5ee85](https://linux-hardware.org/?probe=7140c5ee85) | Mar 11, 2021 |
| Gigabyte   | G31M-S2C                    | [93a598b2c2](https://linux-hardware.org/?probe=93a598b2c2) | Mar 11, 2021 |
| Intel      | DG43RK AAE78175-403         | [942660dca5](https://linux-hardware.org/?probe=942660dca5) | Mar 11, 2021 |
| Gigabyte   | G41M-Combo                  | [2d19cc5e17](https://linux-hardware.org/?probe=2d19cc5e17) | Mar 11, 2021 |
| Lenovo     | ThinkCentre M81 5049PA4     | [99082a91ac](https://linux-hardware.org/?probe=99082a91ac) | Mar 11, 2021 |
| ASUSTek    | TUF X470-PLUS GAMING        | [1e4054e9fe](https://linux-hardware.org/?probe=1e4054e9fe) | Mar 09, 2021 |
| Gigabyte   | H81-D3                      | [d05b1b3efc](https://linux-hardware.org/?probe=d05b1b3efc) | Feb 22, 2021 |
| ASRock     | H77M                        | [eb7af012c2](https://linux-hardware.org/?probe=eb7af012c2) | Feb 19, 2021 |
| Gigabyte   | G31M-S2C                    | [c2bd3800b7](https://linux-hardware.org/?probe=c2bd3800b7) | Feb 18, 2021 |
| ASUSTek    | PRIME Z370-P II             | [95fc52db78](https://linux-hardware.org/?probe=95fc52db78) | Feb 17, 2021 |
| Dell       | 0M9KCM A02                  | [802f6994df](https://linux-hardware.org/?probe=802f6994df) | Feb 16, 2021 |
| ASUSTek    | P7H55-M PRO                 | [aead87bf38](https://linux-hardware.org/?probe=aead87bf38) | Feb 14, 2021 |
| Lenovo     | 3176 NOK                    | [c5216ce396](https://linux-hardware.org/?probe=c5216ce396) | Feb 14, 2021 |
| MSI        | B150M BAZOOKA               | [66af036f49](https://linux-hardware.org/?probe=66af036f49) | Feb 13, 2021 |
| MSI        | B150M BAZOOKA               | [749beaf127](https://linux-hardware.org/?probe=749beaf127) | Feb 13, 2021 |
| Gigabyte   | B460M D3H                   | [8cdafac5a3](https://linux-hardware.org/?probe=8cdafac5a3) | Feb 13, 2021 |
| ASUSTek    | H110M-A/M.2                 | [351477b72b](https://linux-hardware.org/?probe=351477b72b) | Feb 13, 2021 |
| Gigabyte   | Z390 GAMING X-CF            | [3e8ad6be09](https://linux-hardware.org/?probe=3e8ad6be09) | Feb 10, 2021 |
| ASRock     | Z490M-ITX/ac                | [586d4a5a82](https://linux-hardware.org/?probe=586d4a5a82) | Feb 04, 2021 |
| Gigabyte   | B150M-D3H-CF                | [017e9abf15](https://linux-hardware.org/?probe=017e9abf15) | Feb 04, 2021 |
| ASUSTek    | H81M-K                      | [e6be0abafb](https://linux-hardware.org/?probe=e6be0abafb) | Jan 28, 2021 |
| Gigabyte   | H97M-D3H                    | [cc4593764d](https://linux-hardware.org/?probe=cc4593764d) | Jan 18, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [725729e04e](https://linux-hardware.org/?probe=725729e04e) | Jan 13, 2021 |
| Gigabyte   | Z390 GAMING X-CF            | [9c40fd9781](https://linux-hardware.org/?probe=9c40fd9781) | Jan 13, 2021 |
| Gigabyte   | Z370 AORUS Gaming K3-CF     | [4723903be4](https://linux-hardware.org/?probe=4723903be4) | Jan 11, 2021 |
| Gigabyte   | P55-UD3L                    | [8c6a5c5e60](https://linux-hardware.org/?probe=8c6a5c5e60) | Jan 10, 2021 |
| ASRock     | H97M Anniversary            | [b630702ecc](https://linux-hardware.org/?probe=b630702ecc) | Jan 10, 2021 |
| Gigabyte   | G41M-ES2L                   | [2583ebac59](https://linux-hardware.org/?probe=2583ebac59) | Jan 08, 2021 |
| Gigabyte   | H81M-D2V                    | [b7c82c53b6](https://linux-hardware.org/?probe=b7c82c53b6) | Jan 07, 2021 |
| Unknown    | G41 Series                  | [578bc526ef](https://linux-hardware.org/?probe=578bc526ef) | Jan 06, 2021 |
| Unknown    | G41 Series                  | [5a6543b6f1](https://linux-hardware.org/?probe=5a6543b6f1) | Jan 03, 2021 |
| Gigabyte   | Z390 UD                     | [b4ebedb0e2](https://linux-hardware.org/?probe=b4ebedb0e2) | Dec 18, 2020 |
| ASUSTek    | H97M-E                      | [4f0b22ee7f](https://linux-hardware.org/?probe=4f0b22ee7f) | Nov 30, 2020 |
| MSI        | X470 GAMING PLUS            | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| Gigabyte   | Z270X-UD5-CF                | [f65b9a326b](https://linux-hardware.org/?probe=f65b9a326b) | Nov 21, 2020 |
| Gigabyte   | Z270X-UD5-CF                | [8f674b7608](https://linux-hardware.org/?probe=8f674b7608) | Nov 21, 2020 |
| ASUSTek    | ROG STRIX Z390-E GAMING     | [c42752eed3](https://linux-hardware.org/?probe=c42752eed3) | Nov 19, 2020 |
| ASUSTek    | P9X79 LE                    | [1674d3318e](https://linux-hardware.org/?probe=1674d3318e) | Nov 18, 2020 |
| ASUSTek    | P9X79 LE                    | [0ae9d90f3f](https://linux-hardware.org/?probe=0ae9d90f3f) | Nov 18, 2020 |
| Gigabyte   | H61M-S2PV                   | [accc9c10e5](https://linux-hardware.org/?probe=accc9c10e5) | Nov 16, 2020 |
| Gigabyte   | H61M-S2PV                   | [1c3bd52baa](https://linux-hardware.org/?probe=1c3bd52baa) | Nov 05, 2020 |
| Gigabyte   | H61M-S2PV                   | [1b6972fae9](https://linux-hardware.org/?probe=1b6972fae9) | Nov 05, 2020 |
| Dell       | 0CU409                      | [6adb83b2e0](https://linux-hardware.org/?probe=6adb83b2e0) | Nov 04, 2020 |
| Lenovo     | ThinkCentre A58 751581G     | [987ed81d7d](https://linux-hardware.org/?probe=987ed81d7d) | Nov 03, 2020 |
| Dell       | 0KWVT8 A02                  | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| Dell       | 0DR845                      | [c59e7b1e56](https://linux-hardware.org/?probe=c59e7b1e56) | Nov 01, 2020 |
| ASUSTek    | H110M-A                     | [f8fa4c9c31](https://linux-hardware.org/?probe=f8fa4c9c31) | Nov 01, 2020 |
| Dell       | 0KP561                      | [da357993dd](https://linux-hardware.org/?probe=da357993dd) | Oct 31, 2020 |
| Dell       | 0KP561                      | [b14be76868](https://linux-hardware.org/?probe=b14be76868) | Oct 31, 2020 |
| HP         | 158A                        | [f83412f912](https://linux-hardware.org/?probe=f83412f912) | Oct 27, 2020 |
| ASUSTek    | PRIME X470-PRO              | [5bd58e33be](https://linux-hardware.org/?probe=5bd58e33be) | Oct 27, 2020 |
| HP         | 82B4                        | [d98d676e9c](https://linux-hardware.org/?probe=d98d676e9c) | Oct 26, 2020 |
| ASUSTek    | PRIME B350M-A               | [7c9e9b741c](https://linux-hardware.org/?probe=7c9e9b741c) | Oct 25, 2020 |
| ASUSTek    | PRIME X570-PRO              | [d3f4deffa5](https://linux-hardware.org/?probe=d3f4deffa5) | Oct 25, 2020 |
| ASUSTek    | ROG STRIX Z390-E GAMING     | [6ba76947d7](https://linux-hardware.org/?probe=6ba76947d7) | Oct 18, 2020 |
| ASUSTek    | PRIME Z490-P                | [44d70b326c](https://linux-hardware.org/?probe=44d70b326c) | Oct 13, 2020 |
| Gigabyte   | B360M HD3                   | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Lenovo     | ThinkCentre M81 5049W15     | [986a5e604f](https://linux-hardware.org/?probe=986a5e604f) | Oct 03, 2020 |
| ASRock     | X399 Taichi                 | [268a9d5625](https://linux-hardware.org/?probe=268a9d5625) | Oct 01, 2020 |
| ASUSTek    | P5G41C-M LX                 | [353229fd96](https://linux-hardware.org/?probe=353229fd96) | Sep 29, 2020 |
| Unknown    | Unknown                     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| ASRock     | H97M Anniversary            | [cc0e0f5c04](https://linux-hardware.org/?probe=cc0e0f5c04) | Sep 29, 2020 |
| MSI        | G41M-E43                    | [5a567b1f97](https://linux-hardware.org/?probe=5a567b1f97) | Sep 28, 2020 |
| Lenovo     | ThinkCentre M81 5049W15     | [5d73c67b98](https://linux-hardware.org/?probe=5d73c67b98) | Sep 28, 2020 |
| Lenovo     | ThinkCentre M81 5049W15     | [9c9f5b4cfa](https://linux-hardware.org/?probe=9c9f5b4cfa) | Sep 10, 2020 |
| Gigabyte   | B360M HD3                   | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| HP         | 339A                        | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| ASUSTek    | ROG Maximus XI HERO         | [42deb7cee5](https://linux-hardware.org/?probe=42deb7cee5) | Sep 03, 2020 |
| ASUSTek    | PRIME Z370-P                | [5bfd2a1403](https://linux-hardware.org/?probe=5bfd2a1403) | Sep 03, 2020 |
| MSI        | 2A9Ch                       | [aa629696b3](https://linux-hardware.org/?probe=aa629696b3) | Aug 28, 2020 |
| MSI        | 2A9Ch                       | [0ece5d52d2](https://linux-hardware.org/?probe=0ece5d52d2) | Aug 27, 2020 |
| ASUSTek    | P8H61-M LX R2.0             | [56afe1e282](https://linux-hardware.org/?probe=56afe1e282) | Aug 27, 2020 |
| ASRock     | H97M Anniversary            | [613aba4134](https://linux-hardware.org/?probe=613aba4134) | Aug 23, 2020 |
| ASUSTek    | TUF Gaming B550-PLUS        | [a114ae9c9c](https://linux-hardware.org/?probe=a114ae9c9c) | Aug 12, 2020 |
| Lenovo     | SHARKBAY SDK0E50519 WIN     | [1828dedb7f](https://linux-hardware.org/?probe=1828dedb7f) | Aug 10, 2020 |
| ASUSTek    | TUF Gaming B460-PLUS        | [0d864b4feb](https://linux-hardware.org/?probe=0d864b4feb) | Aug 08, 2020 |
| ASUSTek    | TUF Gaming B460-PLUS        | [69e782093d](https://linux-hardware.org/?probe=69e782093d) | Aug 08, 2020 |
| Gigabyte   | Z270-HD3P-CF                | [3fe0ec39fc](https://linux-hardware.org/?probe=3fe0ec39fc) | Aug 07, 2020 |
| ASRock     | H55M                        | [f2d0fa78ac](https://linux-hardware.org/?probe=f2d0fa78ac) | Aug 06, 2020 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [5c3dc530c3](https://linux-hardware.org/?probe=5c3dc530c3) | Aug 04, 2020 |
| Gigabyte   | Z97-HD3                     | [2e41ce3f03](https://linux-hardware.org/?probe=2e41ce3f03) | Jul 31, 2020 |
| Gigabyte   | Z97-HD3                     | [50888e0851](https://linux-hardware.org/?probe=50888e0851) | Jul 31, 2020 |
| ASRock     | H55M                        | [dcbc0735f5](https://linux-hardware.org/?probe=dcbc0735f5) | Jul 30, 2020 |
| ASUSTek    | P8H67-M PRO                 | [a7e0318966](https://linux-hardware.org/?probe=a7e0318966) | Jul 30, 2020 |
| ASUSTek    | AT3N7A-I                    | [57c3ce82b7](https://linux-hardware.org/?probe=57c3ce82b7) | Jul 29, 2020 |
| HARDKERNEL | ODROID-H2                   | [c86e7dc968](https://linux-hardware.org/?probe=c86e7dc968) | Jul 23, 2020 |
| Gigabyte   | H61M-S1                     | [2a63a11959](https://linux-hardware.org/?probe=2a63a11959) | Jul 08, 2020 |
| ASUSTek    | P8Z68-V PRO GEN3            | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte   | G31M-S2C                    | [da847897f9](https://linux-hardware.org/?probe=da847897f9) | Jun 15, 2020 |
| MSI        | G41M-E43                    | [4c72170ef6](https://linux-hardware.org/?probe=4c72170ef6) | Jun 06, 2020 |
| ASUSTek    | PRIME H310M-E R2.0          | [48f5173ede](https://linux-hardware.org/?probe=48f5173ede) | May 27, 2020 |
| ASUSTek    | PRIME H310M-E R2.0          | [72b226183e](https://linux-hardware.org/?probe=72b226183e) | May 27, 2020 |
| ASUSTek    | F2A85-M PRO                 | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| Gigabyte   | F2A88XM-DS2                 | [bd5ec5436e](https://linux-hardware.org/?probe=bd5ec5436e) | May 15, 2020 |
| Gigabyte   | F2A88XM-DS2                 | [355e03bb68](https://linux-hardware.org/?probe=355e03bb68) | May 15, 2020 |
| HP         | 339A                        | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| ASUSTek    | P8H61-M LX R2.0             | [c815568345](https://linux-hardware.org/?probe=c815568345) | May 14, 2020 |
| ASUSTek    | F2A85-M PRO                 | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Gigabyte   | F2A88XM-D3H                 | [fc58b96f3e](https://linux-hardware.org/?probe=fc58b96f3e) | May 01, 2020 |
| Gigabyte   | B450M S2H                   | [0fe3c99d58](https://linux-hardware.org/?probe=0fe3c99d58) | Apr 30, 2020 |
| MSI        | G41TM-P33                   | [d1078cd496](https://linux-hardware.org/?probe=d1078cd496) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| MSI        | G41TM-P33                   | [3512230c03](https://linux-hardware.org/?probe=3512230c03) | Apr 28, 2020 |
| MSI        | G41TM-P33                   | [a648a57d33](https://linux-hardware.org/?probe=a648a57d33) | Apr 28, 2020 |
| Gigabyte   | Z270XP-SLI-CF               | [20f18f18b8](https://linux-hardware.org/?probe=20f18f18b8) | Apr 27, 2020 |
| Dell       | 097YXY A00                  | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| MSI        | G41TM-P33                   | [d99b7f2578](https://linux-hardware.org/?probe=d99b7f2578) | Apr 22, 2020 |
| Gigabyte   | H61M-S1                     | [ade023408c](https://linux-hardware.org/?probe=ade023408c) | Mar 26, 2020 |
| MSI        | B450-A PRO                  | [f9c1a4dd5d](https://linux-hardware.org/?probe=f9c1a4dd5d) | Mar 25, 2020 |
| Gigabyte   | F2A88XM-D3H                 | [e02dd36f39](https://linux-hardware.org/?probe=e02dd36f39) | Mar 22, 2020 |
| Gigabyte   | B150M-D3H-CF                | [5c3ecb2c5b](https://linux-hardware.org/?probe=5c3ecb2c5b) | Mar 22, 2020 |
| Gigabyte   | B150M-D3H-CF                | [1004ffcce5](https://linux-hardware.org/?probe=1004ffcce5) | Mar 22, 2020 |
| Gigabyte   | B150M-D3H-CF                | [e0f2c8f133](https://linux-hardware.org/?probe=e0f2c8f133) | Mar 22, 2020 |
| Gigabyte   | B150M-D3H-CF                | [03d86fb8e8](https://linux-hardware.org/?probe=03d86fb8e8) | Mar 21, 2020 |
| ASUSTek    | PRIME B450M-A               | [a53152418d](https://linux-hardware.org/?probe=a53152418d) | Mar 14, 2020 |
| ASUSTek    | PRIME B450M-A               | [32428dda92](https://linux-hardware.org/?probe=32428dda92) | Mar 14, 2020 |
| ASUSTek    | PRIME B450M-A               | [5d56415e4c](https://linux-hardware.org/?probe=5d56415e4c) | Mar 14, 2020 |
| Gigabyte   | Q87M-D2H                    | [48afe5fac3](https://linux-hardware.org/?probe=48afe5fac3) | Mar 08, 2020 |
| ASUSTek    | H81M-K                      | [08d45d3162](https://linux-hardware.org/?probe=08d45d3162) | Mar 07, 2020 |
| HP         | 1495                        | [ff4447983a](https://linux-hardware.org/?probe=ff4447983a) | Feb 22, 2020 |
| ASUSTek    | PRIME H310M-E R2.0          | [72475e5edb](https://linux-hardware.org/?probe=72475e5edb) | Feb 22, 2020 |
| HP         | 1495                        | [e1d927d5ce](https://linux-hardware.org/?probe=e1d927d5ce) | Feb 16, 2020 |
| HP         | 1495                        | [c9e7f762e4](https://linux-hardware.org/?probe=c9e7f762e4) | Feb 16, 2020 |
| Gigabyte   | H110M-DS2 DDR3-CF           | [e2a558c35b](https://linux-hardware.org/?probe=e2a558c35b) | Feb 11, 2020 |
| MSI        | G41TM-P33                   | [524089d286](https://linux-hardware.org/?probe=524089d286) | Jan 29, 2020 |
| Pegatron   | NARRA5                      | [f0bd8ead24](https://linux-hardware.org/?probe=f0bd8ead24) | Jan 17, 2020 |
| ASRock     | H97M Anniversary            | [221a2cfac8](https://linux-hardware.org/?probe=221a2cfac8) | Jan 13, 2020 |
| Dell       | 0GM819                      | [d99391a30c](https://linux-hardware.org/?probe=d99391a30c) | Jan 06, 2020 |
| ASUSTek    | M2N-MX SE Plus              | [f3b22a675a](https://linux-hardware.org/?probe=f3b22a675a) | Dec 20, 2019 |
| ASUSTek    | A88XM-A/USB                 | [8f93bf715a](https://linux-hardware.org/?probe=8f93bf715a) | Dec 11, 2019 |
| ASRock     | H97M Anniversary            | [831ff4b7fc](https://linux-hardware.org/?probe=831ff4b7fc) | Dec 10, 2019 |
| Gigabyte   | F2A88XM-D3H                 | [8fbc16ebfa](https://linux-hardware.org/?probe=8fbc16ebfa) | Dec 03, 2019 |
| Gigabyte   | H170-HD3-CF                 | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASRock     | G41C-GS                     | [920a88f615](https://linux-hardware.org/?probe=920a88f615) | Nov 08, 2019 |
| HP         | 2B38                        | [8a919fff76](https://linux-hardware.org/?probe=8a919fff76) | Oct 26, 2019 |
| Gigabyte   | AB350N-Gaming WIFI-CF       | [6d5ea39af4](https://linux-hardware.org/?probe=6d5ea39af4) | Oct 26, 2019 |
| Dell       | 0GM819                      | [4468e2e57e](https://linux-hardware.org/?probe=4468e2e57e) | Oct 21, 2019 |
| Gigabyte   | Z87MX-D3H-CF                | [8a9e5f7293](https://linux-hardware.org/?probe=8a9e5f7293) | Oct 14, 2019 |
| Gigabyte   | AB350N-Gaming WIFI-CF       | [cafdeb1b3a](https://linux-hardware.org/?probe=cafdeb1b3a) | Oct 06, 2019 |
| HP         | 2B38                        | [f690313ecf](https://linux-hardware.org/?probe=f690313ecf) | Sep 30, 2019 |
| ASUSTek    | PRIME X370-PRO              | [2ad6f6b23d](https://linux-hardware.org/?probe=2ad6f6b23d) | Sep 25, 2019 |
| AMI        | Cherry Trail CR             | [0398059e29](https://linux-hardware.org/?probe=0398059e29) | Sep 16, 2019 |
| Gigabyte   | AB350N-Gaming WIFI-CF       | [3bfc472643](https://linux-hardware.org/?probe=3bfc472643) | Sep 15, 2019 |
| Gigabyte   | AB350N-Gaming WIFI-CF       | [d90225cad7](https://linux-hardware.org/?probe=d90225cad7) | Sep 15, 2019 |
| ASUSTek    | ROG Maximus X HERO          | [c090add0c0](https://linux-hardware.org/?probe=c090add0c0) | Sep 04, 2019 |
| Dell       | 0GM819                      | [863ec2a484](https://linux-hardware.org/?probe=863ec2a484) | Sep 02, 2019 |
| Dell       | 0GM819                      | [7bf21b409d](https://linux-hardware.org/?probe=7bf21b409d) | Sep 02, 2019 |
| ASUSTek    | ROG Maximus X HERO          | [f6c7aa7735](https://linux-hardware.org/?probe=f6c7aa7735) | Sep 02, 2019 |
| Gigabyte   | X299 UD4 Pro-CF             | [b1fb625f3d](https://linux-hardware.org/?probe=b1fb625f3d) | Aug 26, 2019 |
| Dell       | 0CKCXH A04                  | [2679a50fe1](https://linux-hardware.org/?probe=2679a50fe1) | Aug 24, 2019 |
| Gigabyte   | H55M-S2H                    | [2479a0b0c9](https://linux-hardware.org/?probe=2479a0b0c9) | Aug 24, 2019 |
| Gigabyte   | J1800N-D2H                  | [616bb81d97](https://linux-hardware.org/?probe=616bb81d97) | Aug 17, 2019 |
| Foxconn    | 2A8C                        | [54cbeed66e](https://linux-hardware.org/?probe=54cbeed66e) | Jul 10, 2019 |
| ASUSTek    | TUF X470-PLUS GAMING        | [10a2ff392a](https://linux-hardware.org/?probe=10a2ff392a) | Jul 09, 2019 |
| Gigabyte   | H57M-USB3                   | [10ba468b45](https://linux-hardware.org/?probe=10ba468b45) | Jul 01, 2019 |
| Dell       | 03NVJ6 A02                  | [0b6b3550b5](https://linux-hardware.org/?probe=0b6b3550b5) | Jul 01, 2019 |
| Dell       | 03NVJ6 A02                  | [a920b40c9f](https://linux-hardware.org/?probe=a920b40c9f) | Jul 01, 2019 |
| Dell       | 0GDG8Y A00                  | [4f0fb75146](https://linux-hardware.org/?probe=4f0fb75146) | Jun 20, 2019 |
| ASRock     | H110M-ITX/ac                | [6f2ecbf51c](https://linux-hardware.org/?probe=6f2ecbf51c) | Jun 04, 2019 |
| Gigabyte   | H97-HD3                     | [64e47e9922](https://linux-hardware.org/?probe=64e47e9922) | May 28, 2019 |
| Gigabyte   | X58A-UD3R                   | [112dc8e71a](https://linux-hardware.org/?probe=112dc8e71a) | May 23, 2019 |
| ASUSTek    | H110M-K                     | [c736db6599](https://linux-hardware.org/?probe=c736db6599) | May 01, 2019 |
| ASUSTek    | H110M-K                     | [109947ebc6](https://linux-hardware.org/?probe=109947ebc6) | May 01, 2019 |
| ASUSTek    | H110M-A/M.2                 | [05fcc6199e](https://linux-hardware.org/?probe=05fcc6199e) | Apr 21, 2019 |
| ASUSTek    | P7H55-M PRO                 | [f8a69693bc](https://linux-hardware.org/?probe=f8a69693bc) | Mar 30, 2019 |
| Biostar    | H61MLV2                     | [19146b787b](https://linux-hardware.org/?probe=19146b787b) | Mar 28, 2019 |
| Gigabyte   | H97M-HD3                    | [a6818d6761](https://linux-hardware.org/?probe=a6818d6761) | Mar 20, 2019 |
| Gigabyte   | F2A88XM-HD3                 | [b1e21a522f](https://linux-hardware.org/?probe=b1e21a522f) | Feb 26, 2019 |
| ASUSTek    | H81M-K                      | [569fd85150](https://linux-hardware.org/?probe=569fd85150) | Dec 05, 2018 |
| Gigabyte   | H370 HD3-CF                 | [ac7a7dc15b](https://linux-hardware.org/?probe=ac7a7dc15b) | Nov 13, 2018 |
| ASUSTek    | Z87-K                       | [1d8a707c72](https://linux-hardware.org/?probe=1d8a707c72) | Sep 11, 2018 |
| Gigabyte   | Z170MX-Gaming 5             | [935991dc2b](https://linux-hardware.org/?probe=935991dc2b) | May 04, 2018 |
| ASUSTek    | P7H55-M PRO                 | [d147cce967](https://linux-hardware.org/?probe=d147cce967) | Dec 06, 2017 |
| ASUSTek    | M5A87                       | [242554d0b3](https://linux-hardware.org/?probe=242554d0b3) | Apr 27, 2017 |
| ASRock     | G41C-GS                     | [ff9333f313](https://linux-hardware.org/?probe=ff9333f313) | Apr 13, 2017 |
| ASUSTek    | M5A87                       | [bbe4de9927](https://linux-hardware.org/?probe=bbe4de9927) | Apr 07, 2017 |
| Gigabyte   | Z170MX-Gaming 5             | [10108844b5](https://linux-hardware.org/?probe=10108844b5) | Mar 17, 2017 |
| ASUSTek    | M5A87                       | [653cce33bd](https://linux-hardware.org/?probe=653cce33bd) | Mar 17, 2017 |
| Gigabyte   | H110M-S2H-CF                | [c869336270](https://linux-hardware.org/?probe=c869336270) | Jan 17, 2017 |
| Gigabyte   | H110M-S2H-CF                | [c7554e6e05](https://linux-hardware.org/?probe=c7554e6e05) | Jan 14, 2017 |
| MSI        | G41TM-P33                   | [dd04fa411c](https://linux-hardware.org/?probe=dd04fa411c) | Dec 12, 2016 |
| ASUSTek    | P7H55-M PRO                 | [0a729a3728](https://linux-hardware.org/?probe=0a729a3728) | Oct 07, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 49       | 21.3%   |
| Ubuntu 18.04                 | 24       | 10.43%  |
| OpenMandriva 4.2             | 14       | 6.09%   |
| ROSA R11                     | 9        | 3.91%   |
| Ubuntu 19.04                 | 8        | 3.48%   |
| OpenMandriva 4.3             | 7        | 3.04%   |
| ROSA R11.1                   | 6        | 2.61%   |
| Ubuntu 20.10                 | 5        | 2.17%   |
| Manjaro                      | 5        | 2.17%   |
| Ubuntu 16.04                 | 4        | 1.74%   |
| Pop!_OS 20.04                | 4        | 1.74%   |
| Linux Mint 19.3              | 4        | 1.74%   |
| Kubuntu 20.04                | 4        | 1.74%   |
| Ubuntu 19.10                 | 3        | 1.3%    |
| ROSA R8.1                    | 3        | 1.3%    |
| ROSA R8                      | 3        | 1.3%    |
| ROSA R10                     | 3        | 1.3%    |
| Pop!_OS 21.10                | 3        | 1.3%    |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.3%    |
| Linux Mint 20.2              | 3        | 1.3%    |
| Linux Mint 20.1              | 3        | 1.3%    |
| Fedora 36                    | 3        | 1.3%    |
| Debian 11                    | 3        | 1.3%    |
| ArcoLinux Rolling            | 3        | 1.3%    |
| Xubuntu 20.04                | 2        | 0.87%   |
| Xubuntu 18.04                | 2        | 0.87%   |
| Ubuntu 21.10                 | 2        | 0.87%   |
| Ubuntu 21.04                 | 2        | 0.87%   |
| Rocky Linux 8.5              | 2        | 0.87%   |
| Pop!_OS 21.04                | 2        | 0.87%   |
| Linux Mint 20.3              | 2        | 0.87%   |
| Linux Mint 20                | 2        | 0.87%   |
| KDE neon 20.04               | 2        | 0.87%   |
| Fedora 35                    | 2        | 0.87%   |
| Fedora 33                    | 2        | 0.87%   |
| Arch Rolling                 | 2        | 0.87%   |
| Arch                         | 2        | 0.87%   |
| Zorin 16                     | 1        | 0.43%   |
| Zorin 15                     | 1        | 0.43%   |
| Xubuntu 20.10                | 1        | 0.43%   |
| Xubuntu 19.04                | 1        | 0.43%   |
| Ubuntu MATE 18.04            | 1        | 0.43%   |
| Ubuntu Budgie 20.04          | 1        | 0.43%   |
| ROSA R9                      | 1        | 0.43%   |
| ROSA 12.1                    | 1        | 0.43%   |
| Rocky Linux 8.4              | 1        | 0.43%   |
| Pop!_OS 22.04                | 1        | 0.43%   |
| Manjaro 21.1.4               | 1        | 0.43%   |
| Manjaro 21.0.5               | 1        | 0.43%   |
| Manjaro 20.1                 | 1        | 0.43%   |
| Manjaro 18.0.4               | 1        | 0.43%   |
| Linux Mint 19.2              | 1        | 0.43%   |
| Kubuntu 21.10                | 1        | 0.43%   |
| Kubuntu 20.10                | 1        | 0.43%   |
| Gentoo 2.6                   | 1        | 0.43%   |
| Fedora 34                    | 1        | 0.43%   |
| Fedora 31                    | 1        | 0.43%   |
| Endless 3.7.8                | 1        | 0.43%   |
| Devuan 1.0.0                 | 1        | 0.43%   |
| Debian Unstable              | 1        | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 94       | 43.32%  |
| OpenMandriva  | 21       | 9.68%   |
| ROSA          | 20       | 9.22%   |
| Linux Mint    | 12       | 5.53%   |
| Pop!_OS       | 10       | 4.61%   |
| Manjaro       | 9        | 4.15%   |
| Fedora        | 9        | 4.15%   |
| Xubuntu       | 6        | 2.76%   |
| Kubuntu       | 6        | 2.76%   |
| Debian        | 6        | 2.76%   |
| Arch          | 4        | 1.84%   |
| Rocky Linux   | 3        | 1.38%   |
| openSUSE      | 3        | 1.38%   |
| ArcoLinux     | 3        | 1.38%   |
| Zorin         | 2        | 0.92%   |
| KDE neon      | 2        | 0.92%   |
| Ubuntu MATE   | 1        | 0.46%   |
| Ubuntu Budgie | 1        | 0.46%   |
| Gentoo        | 1        | 0.46%   |
| Endless       | 1        | 0.46%   |
| Devuan        | 1        | 0.46%   |
| CentOS        | 1        | 0.46%   |
| BlackPanther  | 1        | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 14       | 5.53%   |
| 5.4.0-42-generic                    | 13       | 5.14%   |
| 5.16.7-desktop-1omv4003             | 7        | 2.77%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6        | 2.37%   |
| 5.4.0-48-generic                    | 5        | 1.98%   |
| 5.4.0-52-generic                    | 4        | 1.58%   |
| 5.11.0-37-generic                   | 4        | 1.58%   |
| 5.8.0-55-generic                    | 3        | 1.19%   |
| 5.8.0-48-generic                    | 3        | 1.19%   |
| 5.4.0-72-generic                    | 3        | 1.19%   |
| 5.4.0-65-generic                    | 3        | 1.19%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 3        | 1.19%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 3        | 1.19%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 3        | 1.19%   |
| 4.15.0-58-generic                   | 3        | 1.19%   |
| 4.15.0-50-generic                   | 3        | 1.19%   |
| 5.8.0-43-generic                    | 2        | 0.79%   |
| 5.8.0-34-generic                    | 2        | 0.79%   |
| 5.8.0-25-generic                    | 2        | 0.79%   |
| 5.4.0-45-generic                    | 2        | 0.79%   |
| 5.4.0-37-generic                    | 2        | 0.79%   |
| 5.4.0-26-generic                    | 2        | 0.79%   |
| 5.3.0-40-generic                    | 2        | 0.79%   |
| 5.3.0-28-generic                    | 2        | 0.79%   |
| 5.16.19-76051619-generic            | 2        | 0.79%   |
| 5.14.10-300.fc35.x86_64             | 2        | 0.79%   |
| 5.13.0-7620-generic                 | 2        | 0.79%   |
| 5.13.0-27-generic                   | 2        | 0.79%   |
| 5.11.0-40-generic                   | 2        | 0.79%   |
| 5.11.0-38-generic                   | 2        | 0.79%   |
| 5.11.0-27-generic                   | 2        | 0.79%   |
| 5.0.0-38-generic                    | 2        | 0.79%   |
| 5.0.0-29-generic                    | 2        | 0.79%   |
| 5.0.0-25-generic                    | 2        | 0.79%   |
| 5.0.0-20-generic                    | 2        | 0.79%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 2        | 0.79%   |
| 5.9.9-arch1-1                       | 1        | 0.4%    |
| 5.9.8-200.fc33.x86_64               | 1        | 0.4%    |
| 5.9.16-1-MANJARO                    | 1        | 0.4%    |
| 5.9.16-050916-generic               | 1        | 0.4%    |
| 5.9.14-arch1-1                      | 1        | 0.4%    |
| 5.9.1-050901-generic                | 1        | 0.4%    |
| 5.8.5-1-MANJARO                     | 1        | 0.4%    |
| 5.8.18-300.fc33.x86_64              | 1        | 0.4%    |
| 5.8.0-7642-generic                  | 1        | 0.4%    |
| 5.8.0-7630-generic                  | 1        | 0.4%    |
| 5.8.0-53-generic                    | 1        | 0.4%    |
| 5.8.0-50-generic                    | 1        | 0.4%    |
| 5.8.0-49-generic                    | 1        | 0.4%    |
| 5.8.0-41-generic                    | 1        | 0.4%    |
| 5.8.0-36-generic                    | 1        | 0.4%    |
| 5.8.0-29-generic                    | 1        | 0.4%    |
| 5.8.0-1-amd64                       | 1        | 0.4%    |
| 5.7.16-xanmod2                      | 1        | 0.4%    |
| 5.6.4-1-default                     | 1        | 0.4%    |
| 5.5.0-2-amd64                       | 1        | 0.4%    |
| 5.4.32-generic-2rosa-x86_64         | 1        | 0.4%    |
| 5.4.19-200.fc31.x86_64              | 1        | 0.4%    |
| 5.4.0-97-generic                    | 1        | 0.4%    |
| 5.4.0-89-generic                    | 1        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 50       | 21.55%  |
| 4.15.0  | 25       | 10.78%  |
| 5.8.0   | 20       | 8.62%   |
| 5.10.14 | 14       | 6.03%   |
| 5.11.0  | 13       | 5.6%    |
| 5.0.0   | 13       | 5.6%    |
| 5.3.0   | 10       | 4.31%   |
| 5.13.0  | 9        | 3.88%   |
| 5.16.7  | 7        | 3.02%   |
| 4.18.0  | 5        | 2.16%   |
| 5.10.0  | 3        | 1.29%   |
| 4.9.60  | 3        | 1.29%   |
| 5.9.16  | 2        | 0.86%   |
| 5.16.19 | 2        | 0.86%   |
| 5.14.10 | 2        | 0.86%   |
| 5.12.0  | 2        | 0.86%   |
| 4.19.0  | 2        | 0.86%   |
| 4.1.38  | 2        | 0.86%   |
| 4.1.34  | 2        | 0.86%   |
| 5.9.9   | 1        | 0.43%   |
| 5.9.8   | 1        | 0.43%   |
| 5.9.14  | 1        | 0.43%   |
| 5.9.1   | 1        | 0.43%   |
| 5.8.5   | 1        | 0.43%   |
| 5.8.18  | 1        | 0.43%   |
| 5.7.16  | 1        | 0.43%   |
| 5.6.4   | 1        | 0.43%   |
| 5.5.0   | 1        | 0.43%   |
| 5.4.32  | 1        | 0.43%   |
| 5.4.19  | 1        | 0.43%   |
| 5.17.9  | 1        | 0.43%   |
| 5.17.7  | 1        | 0.43%   |
| 5.17.6  | 1        | 0.43%   |
| 5.17.1  | 1        | 0.43%   |
| 5.16.11 | 1        | 0.43%   |
| 5.15.5  | 1        | 0.43%   |
| 5.15.32 | 1        | 0.43%   |
| 5.15.28 | 1        | 0.43%   |
| 5.15.11 | 1        | 0.43%   |
| 5.14.16 | 1        | 0.43%   |
| 5.14.14 | 1        | 0.43%   |
| 5.13.16 | 1        | 0.43%   |
| 5.12.9  | 1        | 0.43%   |
| 5.12.8  | 1        | 0.43%   |
| 5.11.11 | 1        | 0.43%   |
| 5.10.74 | 1        | 0.43%   |
| 5.10.68 | 1        | 0.43%   |
| 5.10.5  | 1        | 0.43%   |
| 5.10.43 | 1        | 0.43%   |
| 5.10.42 | 1        | 0.43%   |
| 5.10.36 | 1        | 0.43%   |
| 5.10.34 | 1        | 0.43%   |
| 4.9.9   | 1        | 0.43%   |
| 4.9.20  | 1        | 0.43%   |
| 4.9.155 | 1        | 0.43%   |
| 4.7.6   | 1        | 0.43%   |
| 4.4.0   | 1        | 0.43%   |
| 4.19.93 | 1        | 0.43%   |
| 4.19.88 | 1        | 0.43%   |
| 4.19.66 | 1        | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 52       | 22.71%  |
| 4.15    | 25       | 10.92%  |
| 5.10    | 24       | 10.48%  |
| 5.8     | 22       | 9.61%   |
| 5.11    | 14       | 6.11%   |
| 5.0     | 13       | 5.68%   |
| 5.3     | 10       | 4.37%   |
| 5.16    | 10       | 4.37%   |
| 5.13    | 10       | 4.37%   |
| 5.9     | 6        | 2.62%   |
| 4.9     | 6        | 2.62%   |
| 4.18    | 6        | 2.62%   |
| 4.19    | 5        | 2.18%   |
| 5.17    | 4        | 1.75%   |
| 5.15    | 4        | 1.75%   |
| 5.14    | 4        | 1.75%   |
| 5.12    | 4        | 1.75%   |
| 4.1     | 4        | 1.75%   |
| 5.7     | 1        | 0.44%   |
| 5.6     | 1        | 0.44%   |
| 5.5     | 1        | 0.44%   |
| 4.7     | 1        | 0.44%   |
| 4.4     | 1        | 0.44%   |
| 3.10    | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 209      | 99.05%  |
| i686   | 2        | 0.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 87       | 39.19%  |
| KDE5       | 44       | 19.82%  |
| Unknown    | 35       | 15.77%  |
| KDE4       | 17       | 7.66%   |
| X-Cinnamon | 10       | 4.5%    |
| XFCE       | 9        | 4.05%   |
| KDE        | 7        | 3.15%   |
| Unity      | 4        | 1.8%    |
| MATE       | 4        | 1.8%    |
| i3         | 2        | 0.9%    |
| Cinnamon   | 2        | 0.9%    |
| Budgie     | 1        | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 177      | 83.1%   |
| Unknown | 20       | 9.39%   |
| Wayland | 10       | 4.69%   |
| Tty     | 6        | 2.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 112      | 51.85%  |
| SDDM    | 37       | 17.13%  |
| GDM     | 26       | 12.04%  |
| KDM     | 17       | 7.87%   |
| GDM3    | 11       | 5.09%   |
| TDM     | 8        | 3.7%    |
| LightDM | 4        | 1.85%   |
| XDM     | 1        | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_IL      | 71       | 33.18%  |
| en_US      | 66       | 30.84%  |
| Unknown    | 41       | 19.16%  |
| he_IL      | 14       | 6.54%   |
| ru_RU      | 13       | 6.07%   |
| C          | 4        | 1.87%   |
| fr_FR      | 2        | 0.93%   |
| POSIX      | 1        | 0.47%   |
| en_US.UTF8 | 1        | 0.47%   |
| C.UTF8     | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 129      | 60.28%  |
| EFI  | 85       | 39.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 162      | 75%     |
| Overlay | 23       | 10.65%  |
| Btrfs   | 15       | 6.94%   |
| Unknown | 9        | 4.17%   |
| Xfs     | 4        | 1.85%   |
| Zfs     | 1        | 0.46%   |
| Tmpfs   | 1        | 0.46%   |
| F2fs    | 1        | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 118      | 55.4%   |
| GPT     | 58       | 27.23%  |
| MBR     | 37       | 17.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 174      | 81.31%  |
| Yes       | 40       | 18.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 65.74%  |
| Yes       | 74       | 34.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 68       | 32.38%  |
| ASUSTek Computer    | 68       | 32.38%  |
| Dell                | 17       | 8.1%    |
| Lenovo              | 11       | 5.24%   |
| MSI                 | 10       | 4.76%   |
| ASRock              | 10       | 4.76%   |
| Hewlett-Packard     | 9        | 4.29%   |
| Intel               | 4        | 1.9%    |
| Pegatron            | 2        | 0.95%   |
| Foxconn             | 2        | 0.95%   |
| Unknown             | 2        | 0.95%   |
| Supermicro          | 1        | 0.48%   |
| Shuttle             | 1        | 0.48%   |
| HARDKERNEL          | 1        | 0.48%   |
| Biostar             | 1        | 0.48%   |
| AZW                 | 1        | 0.48%   |
| AMI                 | 1        | 0.48%   |
| Alienware           | 1        | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 9        | 4.29%   |
| MSI MS-7592                            | 3        | 1.43%   |
| Gigabyte H61M-S1                       | 3        | 1.43%   |
| ASUS P8H61-M LX R2.0                   | 3        | 1.43%   |
| ASUS H110M-A/M.2                       | 3        | 1.43%   |
| Intel DH77EB AAG39073-304              | 2        | 0.95%   |
| Gigabyte Z390 GAMING X                 | 2        | 0.95%   |
| Gigabyte X570 AORUS ULTRA              | 2        | 0.95%   |
| Gigabyte P55-UD3L                      | 2        | 0.95%   |
| Gigabyte H61M-S2PV                     | 2        | 0.95%   |
| Gigabyte H55M-D2H                      | 2        | 0.95%   |
| Gigabyte B460HD3                       | 2        | 0.95%   |
| Dell OptiPlex 755                      | 2        | 0.95%   |
| Dell OptiPlex 7050                     | 2        | 0.95%   |
| ASUS TUF Gaming B550-PLUS              | 2        | 0.95%   |
| ASUS ROG STRIX Z390-E GAMING           | 2        | 0.95%   |
| ASUS PRIME Z490-P                      | 2        | 0.95%   |
| ASUS PRIME X470-PRO                    | 2        | 0.95%   |
| ASUS PRIME H310M-E R2.0                | 2        | 0.95%   |
| ASUS PRIME B560M-K                     | 2        | 0.95%   |
| Unknown                                | 2        | 0.95%   |
| Supermicro X9DAi                       | 1        | 0.48%   |
| Shuttle SH87R                          | 1        | 0.48%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.48%   |
| Pegatron NC890AA-ABA a6803w            | 1        | 0.48%   |
| MSI MS-7B86                            | 1        | 0.48%   |
| MSI MS-7B79                            | 1        | 0.48%   |
| MSI MS-7982                            | 1        | 0.48%   |
| MSI MS-7978                            | 1        | 0.48%   |
| MSI MS-7816                            | 1        | 0.48%   |
| MSI MS-7788                            | 1        | 0.48%   |
| MSI Elite 7100 Microtower PC           | 1        | 0.48%   |
| Lenovo V530-15ICR 11BH0032IV           | 1        | 0.48%   |
| Lenovo V520-15IKL 10NKS05400           | 1        | 0.48%   |
| Lenovo V520-15IKL 10NK003KIV           | 1        | 0.48%   |
| Lenovo V520-15IKL 10NK001XIV           | 1        | 0.48%   |
| Lenovo ThinkCentre M93p 10A7S02D00     | 1        | 0.48%   |
| Lenovo ThinkCentre M91p 4524B96        | 1        | 0.48%   |
| Lenovo ThinkCentre M91p 4518NR8        | 1        | 0.48%   |
| Lenovo ThinkCentre M81 5049W15         | 1        | 0.48%   |
| Lenovo ThinkCentre M81 5049PA4         | 1        | 0.48%   |
| Lenovo ThinkCentre Edge72 3484BTG      | 1        | 0.48%   |
| Lenovo ThinkCentre A58 751581G         | 1        | 0.48%   |
| Intel DP55WB AAE64798-205              | 1        | 0.48%   |
| Intel DG43RK AAE78175-403              | 1        | 0.48%   |
| HP Z620 Workstation                    | 1        | 0.48%   |
| HP ProDesk 600 G3 SFF                  | 1        | 0.48%   |
| HP EliteDesk 800 G3 TWR                | 1        | 0.48%   |
| HP Compaq Pro 6300 MT                  | 1        | 0.48%   |
| HP Compaq Elite 8300 MT                | 1        | 0.48%   |
| HP Compaq 8200 Elite SFF PC            | 1        | 0.48%   |
| HP Compaq 6200 Pro MT PC               | 1        | 0.48%   |
| HP 300-1xx                             | 1        | 0.48%   |
| HP 280 G1 MT                           | 1        | 0.48%   |
| HARDKERNEL ODROID-H2                   | 1        | 0.48%   |
| Gigabyte Z97X-Gaming 5                 | 1        | 0.48%   |
| Gigabyte Z97-HD3                       | 1        | 0.48%   |
| Gigabyte Z97-D3H                       | 1        | 0.48%   |
| Gigabyte Z87MX-D3H                     | 1        | 0.48%   |
| Gigabyte Z690 AORUS ELITE AX DDR4      | 1        | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 21       | 10%     |
| Dell OptiPlex          | 10       | 4.76%   |
| ASUS All               | 9        | 4.29%   |
| Lenovo ThinkCentre     | 7        | 3.33%   |
| ASUS ROG               | 7        | 3.33%   |
| ASUS TUF               | 6        | 2.86%   |
| HP Compaq              | 4        | 1.9%    |
| Dell Vostro            | 4        | 1.9%    |
| ASUS H110M-A           | 4        | 1.9%    |
| MSI MS-7592            | 3        | 1.43%   |
| Lenovo V520-15IKL      | 3        | 1.43%   |
| Gigabyte Z390          | 3        | 1.43%   |
| Gigabyte H61M-S1       | 3        | 1.43%   |
| ASUS P8H61-M           | 3        | 1.43%   |
| Intel DH77EB           | 2        | 0.95%   |
| Gigabyte X570          | 2        | 0.95%   |
| Gigabyte P55-UD3L      | 2        | 0.95%   |
| Gigabyte H61M-S2PV     | 2        | 0.95%   |
| Gigabyte H55M-D2H      | 2        | 0.95%   |
| Gigabyte B560M         | 2        | 0.95%   |
| Gigabyte B460HD3       | 2        | 0.95%   |
| Gigabyte B450M         | 2        | 0.95%   |
| Dell Precision         | 2        | 0.95%   |
| Unknown                | 2        | 0.95%   |
| Supermicro X9DAi       | 1        | 0.48%   |
| Shuttle SH87R          | 1        | 0.48%   |
| Pegatron Pro           | 1        | 0.48%   |
| Pegatron NC890AA-ABA   | 1        | 0.48%   |
| MSI MS-7B86            | 1        | 0.48%   |
| MSI MS-7B79            | 1        | 0.48%   |
| MSI MS-7982            | 1        | 0.48%   |
| MSI MS-7978            | 1        | 0.48%   |
| MSI MS-7816            | 1        | 0.48%   |
| MSI MS-7788            | 1        | 0.48%   |
| MSI Elite              | 1        | 0.48%   |
| Lenovo V530-15ICR      | 1        | 0.48%   |
| Intel DP55WB           | 1        | 0.48%   |
| Intel DG43RK           | 1        | 0.48%   |
| HP Z620                | 1        | 0.48%   |
| HP ProDesk             | 1        | 0.48%   |
| HP EliteDesk           | 1        | 0.48%   |
| HP 300-1xx             | 1        | 0.48%   |
| HP 280                 | 1        | 0.48%   |
| HARDKERNEL ODROID-H2   | 1        | 0.48%   |
| Gigabyte Z97X-Gaming   | 1        | 0.48%   |
| Gigabyte Z97-HD3       | 1        | 0.48%   |
| Gigabyte Z97-D3H       | 1        | 0.48%   |
| Gigabyte Z87MX-D3H     | 1        | 0.48%   |
| Gigabyte Z690          | 1        | 0.48%   |
| Gigabyte Z490M         | 1        | 0.48%   |
| Gigabyte Z370          | 1        | 0.48%   |
| Gigabyte Z270X-UD5     | 1        | 0.48%   |
| Gigabyte Z270-HD3P     | 1        | 0.48%   |
| Gigabyte Z170XP-SLI    | 1        | 0.48%   |
| Gigabyte Z170X-Gaming  | 1        | 0.48%   |
| Gigabyte Z170MX-Gaming | 1        | 0.48%   |
| Gigabyte X58A-UD3R     | 1        | 0.48%   |
| Gigabyte X58-USB3      | 1        | 0.48%   |
| Gigabyte X299          | 1        | 0.48%   |
| Gigabyte Q87M-D2H      | 1        | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 26       | 12.38%  |
| 2012 | 21       | 10%     |
| 2013 | 19       | 9.05%   |
| 2014 | 18       | 8.57%   |
| 2010 | 17       | 8.1%    |
| 2020 | 16       | 7.62%   |
| 2017 | 14       | 6.67%   |
| 2021 | 13       | 6.19%   |
| 2019 | 13       | 6.19%   |
| 2009 | 12       | 5.71%   |
| 2016 | 11       | 5.24%   |
| 2015 | 11       | 5.24%   |
| 2011 | 11       | 5.24%   |
| 2007 | 4        | 1.9%    |
| 2008 | 3        | 1.43%   |
| 2006 | 1        | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 210      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 209      | 99.52%  |
| Enabled  | 1        | 0.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 210      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 54       | 25.23%  |
| 8.01-16.0   | 41       | 19.16%  |
| 32.01-64.0  | 38       | 17.76%  |
| 3.01-4.0    | 33       | 15.42%  |
| 4.01-8.0    | 26       | 12.15%  |
| 64.01-256.0 | 11       | 5.14%   |
| 1.01-2.0    | 7        | 3.27%   |
| 24.01-32.0  | 3        | 1.4%    |
| 2.01-3.0    | 1        | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 84       | 36.05%  |
| 2.01-3.0   | 44       | 18.88%  |
| 4.01-8.0   | 33       | 14.16%  |
| 3.01-4.0   | 24       | 10.3%   |
| 0.51-1.0   | 21       | 9.01%   |
| 8.01-16.0  | 20       | 8.58%   |
| 0.01-0.5   | 4        | 1.72%   |
| 16.01-24.0 | 2        | 0.86%   |
| 24.01-32.0 | 1        | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 40.09%  |
| 2      | 62       | 28.57%  |
| 3      | 38       | 17.51%  |
| 4      | 14       | 6.45%   |
| 5      | 8        | 3.69%   |
| 6      | 3        | 1.38%   |
| 7      | 2        | 0.92%   |
| 10     | 1        | 0.46%   |
| 8      | 1        | 0.46%   |
| 0      | 1        | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 134      | 62.62%  |
| Yes       | 80       | 37.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 208      | 99.05%  |
| No        | 2        | 0.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 128      | 60.66%  |
| Yes       | 83       | 39.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 77%     |
| Yes       | 49       | 23%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Israel  | 210      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Tel Aviv            | 80       | 36.87%  |
| Haifa               | 20       | 9.22%   |
| Ramat Gan           | 15       | 6.91%   |
| Petaẖ Tiqwa       | 11       | 5.07%   |
| Rishon LeZiyyon     | 8        | 3.69%   |
| Jerusalem           | 7        | 3.23%   |
| Qiryat Ata          | 6        | 2.76%   |
| Rehovot             | 4        | 1.84%   |
| Holon               | 4        | 1.84%   |
| Herzliya            | 4        | 1.84%   |
| Ashdod              | 4        | 1.84%   |
| Netanya             | 3        | 1.38%   |
| Nahariya            | 3        | 1.38%   |
| Kfar Saba           | 3        | 1.38%   |
| Givatayim           | 3        | 1.38%   |
| Ramat HaSharon      | 2        | 0.92%   |
| Raanana             | 2        | 0.92%   |
| Pardes Hanna Karkur | 2        | 0.92%   |
| Ness Ziona          | 2        | 0.92%   |
| Hod HaSharon        | 2        | 0.92%   |
| Beersheba           | 2        | 0.92%   |
| Bat Yam             | 2        | 0.92%   |
| Afula               | 2        | 0.92%   |
| Yehud               | 1        | 0.46%   |
| Tiberias            | 1        | 0.46%   |
| Tel Mond            | 1        | 0.46%   |
| Rosh HaAyin         | 1        | 0.46%   |
| Petaбє– Tiqwa   | 1        | 0.46%   |
| Petaáº– Tiqwa   | 1        | 0.46%   |
| Pardesiyya          | 1        | 0.46%   |
| Or Yehuda           | 1        | 0.46%   |
| Nazerat 'Illit      | 1        | 0.46%   |
| Meitar              | 1        | 0.46%   |
| Lod                 | 1        | 0.46%   |
| Lapid               | 1        | 0.46%   |
| Kiryat Tiv'on       | 1        | 0.46%   |
| Kiryat Ono          | 1        | 0.46%   |
| Kiryat Gat          | 1        | 0.46%   |
| Karmi’el          | 1        | 0.46%   |
| I'billin            | 1        | 0.46%   |
| Hanita              | 1        | 0.46%   |
| Giv'at Hayyim Ihud  | 1        | 0.46%   |
| Bnei Brak           | 1        | 0.46%   |
| Binyamina           | 1        | 0.46%   |
| Bet Shemesh         | 1        | 0.46%   |
| Be'er Ya'aqov       | 1        | 0.46%   |
| Azor                | 1        | 0.46%   |
| Almagor             | 1        | 0.46%   |
| Unknown             | 1        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 91       | 157    | 23.45%  |
| Seagate                   | 49       | 81     | 12.63%  |
| Samsung Electronics       | 46       | 69     | 11.86%  |
| Hitachi                   | 34       | 57     | 8.76%   |
| Kingston                  | 26       | 29     | 6.7%    |
| SanDisk                   | 25       | 30     | 6.44%   |
| Toshiba                   | 21       | 25     | 5.41%   |
| Crucial                   | 15       | 26     | 3.87%   |
| Transcend                 | 11       | 14     | 2.84%   |
| Corsair                   | 10       | 14     | 2.58%   |
| Intel                     | 9        | 12     | 2.32%   |
| HGST                      | 8        | 10     | 2.06%   |
| XPG                       | 5        | 11     | 1.29%   |
| Micron Technology         | 4        | 5      | 1.03%   |
| A-DATA Technology         | 4        | 5      | 1.03%   |
| SK Hynix                  | 3        | 3      | 0.77%   |
| Silicon Motion            | 3        | 3      | 0.77%   |
| Phison                    | 3        | 4      | 0.77%   |
| SPCC                      | 2        | 2      | 0.52%   |
| OCZ                       | 2        | 2      | 0.52%   |
| Netac                     | 2        | 2      | 0.52%   |
| Micron/Crucial Technology | 2        | 2      | 0.52%   |
| USB3.0                    | 1        | 1      | 0.26%   |
| Unknown                   | 1        | 2      | 0.26%   |
| TPH01204000GB             | 1        | 1      | 0.26%   |
| StoreJet                  | 1        | 1      | 0.26%   |
| PLEXTOR                   | 1        | 1      | 0.26%   |
| Patriot                   | 1        | 1      | 0.26%   |
| OCZ-VERTEX3               | 1        | 1      | 0.26%   |
| NGFF                      | 1        | 1      | 0.26%   |
| LS600                     | 1        | 1      | 0.26%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.26%   |
| KingSpec                  | 1        | 1      | 0.26%   |
| IBM/Hitachi               | 1        | 1      | 0.26%   |
| Apple                     | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| SanDisk SSD PLUS 240GB            | 9        | 2.03%   |
| Hitachi HDS721050CLA362 500GB     | 9        | 2.03%   |
| Kingston SA400S37240G 240GB SSD   | 7        | 1.58%   |
| Toshiba DT01ACA100 1TB            | 6        | 1.35%   |
| Samsung SSD 860 EVO 500GB         | 6        | 1.35%   |
| Samsung SSD 850 EVO 250GB         | 6        | 1.35%   |
| WDC WD20PURX-64P6ZY0 2TB          | 5        | 1.13%   |
| WDC WD10EZEX-08WN4A0 1TB          | 5        | 1.13%   |
| Seagate ST500DM002-1BD142 500GB   | 5        | 1.13%   |
| Seagate ST2000DM008-2FR102 2TB    | 5        | 1.13%   |
| Samsung NVMe SSD Drive 500GB      | 5        | 1.13%   |
| HGST HTS545050A7E680 500GB        | 5        | 1.13%   |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.68%   |
| WDC WD10EARS-00Y5B1 1TB           | 3        | 0.68%   |
| WDC WD10EADS-00L5B1 1TB           | 3        | 0.68%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 3        | 0.68%   |
| Toshiba DT01ACA050 500GB          | 3        | 0.68%   |
| Seagate ST2000DM001-1ER164 2TB    | 3        | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB    | 3        | 0.68%   |
| Samsung SSD 970 EVO Plus 500GB    | 3        | 0.68%   |
| Samsung SSD 860 QVO 1TB           | 3        | 0.68%   |
| Samsung NVMe SSD Drive 1TB        | 3        | 0.68%   |
| Kingston SV300S37A120G 120GB SSD  | 3        | 0.68%   |
| Hitachi HDS721050CLA360 500GB     | 3        | 0.68%   |
| XPG NVMe SSD Drive 1024GB         | 2        | 0.45%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD  | 2        | 0.45%   |
| WDC WDS100T3X0C-00SJG0 1TB        | 2        | 0.45%   |
| WDC WD5000AZRX-00A8LB0 500GB      | 2        | 0.45%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 0.45%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 2        | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB       | 2        | 0.45%   |
| WDC WD3200AAKS-00L9A0 320GB       | 2        | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 2        | 0.45%   |
| WDC WD20EZAZ-00GGJB0 2TB          | 2        | 0.45%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.45%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 2        | 0.45%   |
| WDC WD10EZRX-00A8LB0 1TB          | 2        | 0.45%   |
| Transcend TS128GSSD370 128GB      | 2        | 0.45%   |
| Transcend TS128GSSD230S 128GB     | 2        | 0.45%   |
| Toshiba DT01ACA200 2TB            | 2        | 0.45%   |
| Seagate ST500DM002-1SB10A 500GB   | 2        | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB    | 2        | 0.45%   |
| Seagate ST3500418AS 500GB         | 2        | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.45%   |
| Seagate ST1000DM003-1SB102 1TB    | 2        | 0.45%   |
| Seagate Expansion Desk 10TB       | 2        | 0.45%   |
| SanDisk SSD PLUS 480GB            | 2        | 0.45%   |
| SanDisk Extreme SSD 500GB         | 2        | 0.45%   |
| Samsung SSD 860 EVO 1TB           | 2        | 0.45%   |
| Samsung SSD 850 EVO 500GB         | 2        | 0.45%   |
| Samsung NVMe SSD Drive 250GB      | 2        | 0.45%   |
| Samsung HD103SJ 1TB               | 2        | 0.45%   |
| Netac SSD 240GB                   | 2        | 0.45%   |
| Micron/Crucial NVMe SSD Drive 1TB | 2        | 0.45%   |
| Kingston SUV400S37240G 240GB SSD  | 2        | 0.45%   |
| Kingston SUV400S37120G 120GB SSD  | 2        | 0.45%   |
| Kingston SA400S37480G 480GB SSD   | 2        | 0.45%   |
| Kingston SA400S37120G 120GB SSD   | 2        | 0.45%   |
| Intel SSDPEKNW512G8 512GB         | 2        | 0.45%   |
| Hitachi HTS547550A9E384 500GB     | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 85       | 144    | 41.46%  |
| Seagate             | 49       | 80     | 23.9%   |
| Hitachi             | 34       | 57     | 16.59%  |
| Toshiba             | 19       | 23     | 9.27%   |
| HGST                | 8        | 10     | 3.9%    |
| Samsung Electronics | 6        | 12     | 2.93%   |
| USB3.0              | 1        | 1      | 0.49%   |
| TPH01204000GB       | 1        | 1      | 0.49%   |
| IBM/Hitachi         | 1        | 1      | 0.49%   |
| Apple               | 1        | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 36     | 18.94%  |
| Kingston            | 23       | 26     | 17.42%  |
| SanDisk             | 21       | 26     | 15.91%  |
| Transcend           | 11       | 14     | 8.33%   |
| Crucial             | 10       | 20     | 7.58%   |
| Corsair             | 9        | 12     | 6.82%   |
| Intel               | 7        | 8      | 5.3%    |
| WDC                 | 5        | 5      | 3.79%   |
| Micron Technology   | 4        | 5      | 3.03%   |
| A-DATA Technology   | 4        | 5      | 3.03%   |
| OCZ                 | 2        | 2      | 1.52%   |
| Netac               | 2        | 2      | 1.52%   |
| SPCC                | 1        | 1      | 0.76%   |
| Seagate             | 1        | 1      | 0.76%   |
| PLEXTOR             | 1        | 1      | 0.76%   |
| Patriot             | 1        | 1      | 0.76%   |
| OCZ-VERTEX3         | 1        | 1      | 0.76%   |
| NGFF                | 1        | 1      | 0.76%   |
| LS600               | 1        | 1      | 0.76%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.76%   |
| KingSpec            | 1        | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 155      | 330    | 48.44%  |
| SSD     | 110      | 170    | 34.38%  |
| NVMe    | 52       | 73     | 16.25%  |
| Unknown | 2        | 3      | 0.63%   |
| MMC     | 1        | 1      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 186      | 489    | 74.7%   |
| NVMe | 52       | 73     | 20.88%  |
| SAS  | 10       | 14     | 4.02%   |
| MMC  | 1        | 1      | 0.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 147      | 285    | 53.26%  |
| 0.51-1.0   | 67       | 105    | 24.28%  |
| 1.01-2.0   | 39       | 58     | 14.13%  |
| 2.01-3.0   | 9        | 12     | 3.26%   |
| 3.01-4.0   | 8        | 28     | 2.9%    |
| 4.01-10.0  | 5        | 7      | 1.81%   |
| 10.01-20.0 | 1        | 5      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 45       | 20.55%  |
| 101-250        | 40       | 18.26%  |
| 501-1000       | 33       | 15.07%  |
| 1001-2000      | 25       | 11.42%  |
| More than 3000 | 19       | 8.68%   |
| 2001-3000      | 19       | 8.68%   |
| 1-20           | 16       | 7.31%   |
| 21-50          | 11       | 5.02%   |
| 51-100         | 6        | 2.74%   |
| Unknown        | 5        | 2.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 94       | 41.41%  |
| 21-50          | 32       | 14.1%   |
| 101-250        | 22       | 9.69%   |
| 1001-2000      | 20       | 8.81%   |
| 251-500        | 16       | 7.05%   |
| 501-1000       | 12       | 5.29%   |
| 51-100         | 11       | 4.85%   |
| 2001-3000      | 8        | 3.52%   |
| More than 3000 | 7        | 3.08%   |
| Unknown        | 5        | 2.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| HGST HTS545050A7E680 500GB          | 5        | 7      | 13.89%  |
| WDC WD10EARS-00Y5B1 1TB             | 2        | 2      | 5.56%   |
| WDC WD10EADS-00L5B1 1TB             | 2        | 2      | 5.56%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 3      | 5.56%   |
| WDC WD5001AALS-00LWTA0 500GB        | 1        | 1      | 2.78%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 2.78%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 2.78%   |
| WDC WD2500AAJS-00VTA0 250GB         | 1        | 1      | 2.78%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 2      | 2.78%   |
| WDC WD10EZEX-00ZF5A0 1TB            | 1        | 1      | 2.78%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1      | 2.78%   |
| WDC WD1001FALS-00J7B1 1TB           | 1        | 1      | 2.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 2.78%   |
| Seagate ST3750528AS 752GB           | 1        | 1      | 2.78%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 2.78%   |
| Seagate ST31000528AS 1TB            | 1        | 1      | 2.78%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1      | 2.78%   |
| Seagate ST1000LM014-SSHD-8GB        | 1        | 1      | 2.78%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 2.78%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 2      | 2.78%   |
| Hitachi HUA723020ALA640 2TB         | 1        | 1      | 2.78%   |
| Hitachi HTS545050B9A300 500GB       | 1        | 1      | 2.78%   |
| Hitachi HDS721050CLA360 500GB       | 1        | 1      | 2.78%   |
| Hitachi HDS721032CLA362 320GB       | 1        | 1      | 2.78%   |
| Hitachi HDP725050GLAT80 500GB       | 1        | 1      | 2.78%   |
| Hitachi HDP725050GLA360 500GB       | 1        | 1      | 2.78%   |
| HGST HTS721010A9E630 1TB            | 1        | 1      | 2.78%   |
| Corsair Neutron XT SSD 240GB        | 1        | 1      | 2.78%   |
| Corsair Neutron SSD 64GB            | 1        | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 13     | 31.43%  |
| Hitachi             | 8        | 9      | 22.86%  |
| Seagate             | 7        | 7      | 20%     |
| HGST                | 6        | 8      | 17.14%  |
| Corsair             | 2        | 2      | 5.71%   |
| Samsung Electronics | 1        | 2      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 13     | 33.33%  |
| Hitachi             | 8        | 9      | 24.24%  |
| Seagate             | 7        | 7      | 21.21%  |
| HGST                | 6        | 8      | 18.18%  |
| Samsung Electronics | 1        | 2      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 39     | 93.1%   |
| SSD  | 2        | 2      | 6.9%    |

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
| Detected | 123      | 376    | 53.25%  |
| Works    | 78       | 156    | 33.77%  |
| Malfunc  | 28       | 41     | 12.12%  |
| Failed   | 2        | 4      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 174      | 61.05%  |
| AMD                          | 34       | 11.93%  |
| Samsung Electronics          | 19       | 6.67%   |
| Sandisk                      | 9        | 3.16%   |
| JMicron Technology           | 9        | 3.16%   |
| Micron/Crucial Technology    | 7        | 2.46%   |
| Phison Electronics           | 5        | 1.75%   |
| ASMedia Technology           | 5        | 1.75%   |
| ADATA Technology             | 5        | 1.75%   |
| SK Hynix                     | 3        | 1.05%   |
| Silicon Motion               | 3        | 1.05%   |
| Nvidia                       | 3        | 1.05%   |
| Marvell Technology Group     | 3        | 1.05%   |
| Kingston Technology Company  | 3        | 1.05%   |
| Toshiba America Info Systems | 2        | 0.7%    |
| VIA Technologies             | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 7.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 19       | 5.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 4.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 4.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 4.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 3.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 3.49%   |
| Intel SATA Controller [RAID mode]                                                       | 10       | 2.91%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 2.91%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.33%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 1.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 1.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.16%   |
| Micron/Crucial Non-Volatile memory controller                                           | 4        | 1.16%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.16%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 1.16%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.87%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 0.87%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.87%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.58%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.58%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.58%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.58%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.58%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.58%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.58%   |
| Intel SSD 660P Series                                                                   | 2        | 0.58%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.58%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.58%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.58%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.58%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.58%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.58%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.58%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.58%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.29%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1        | 0.29%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.29%   |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 0.29%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.29%   |
| SK Hynix BC511                                                                          | 1        | 0.29%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 160      | 57.97%  |
| NVMe | 53       | 19.2%   |
| IDE  | 47       | 17.03%  |
| RAID | 14       | 5.07%   |
| SAS  | 2        | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 174      | 82.86%  |
| AMD    | 36       | 17.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 3.76%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7        | 3.29%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 2.35%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4        | 1.88%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 1.88%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 1.88%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 1.88%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4        | 1.88%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.88%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.88%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.88%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 1.41%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.41%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 1.41%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.41%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 3        | 1.41%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 1.41%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 1.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1.41%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.41%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.41%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 2        | 0.94%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 0.94%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 0.94%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 0.94%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.94%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.94%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.94%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.94%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.94%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.94%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.94%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.94%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 0.94%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.94%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.94%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.94%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.94%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2        | 0.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.94%   |
| Intel 12th Gen Core i9-12900K               | 2        | 0.94%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 0.94%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 0.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 0.94%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 0.94%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.94%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 0.47%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.47%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.47%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 0.47%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 0.47%   |
| Intel Xeon CPU E3-1265L v4 @ 2.30GHz        | 1        | 0.47%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.47%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.47%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.47%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 54       | 25.59%  |
| Intel Core i5           | 45       | 21.33%  |
| Intel Core i3           | 23       | 10.9%   |
| Intel Pentium Dual-Core | 11       | 5.21%   |
| AMD Ryzen 5             | 11       | 5.21%   |
| Other                   | 8        | 3.79%   |
| Intel Pentium           | 8        | 3.79%   |
| Intel Xeon              | 7        | 3.32%   |
| Intel Core 2 Duo        | 6        | 2.84%   |
| AMD Ryzen 9             | 6        | 2.84%   |
| AMD Ryzen 7             | 5        | 2.37%   |
| Intel Celeron           | 3        | 1.42%   |
| AMD A8                  | 3        | 1.42%   |
| Intel Pentium Dual      | 2        | 0.95%   |
| Intel Genuine           | 2        | 0.95%   |
| Intel Atom              | 2        | 0.95%   |
| AMD FX                  | 2        | 0.95%   |
| Intel Pentium Gold      | 1        | 0.47%   |
| Intel Pentium 4         | 1        | 0.47%   |
| Intel Core i9           | 1        | 0.47%   |
| Intel Core 2 Quad       | 1        | 0.47%   |
| AMD Ryzen Threadripper  | 1        | 0.47%   |
| AMD Ryzen 3 PRO         | 1        | 0.47%   |
| AMD Ryzen 3             | 1        | 0.47%   |
| AMD Phenom II X4        | 1        | 0.47%   |
| AMD Phenom              | 1        | 0.47%   |
| AMD Athlon II X3        | 1        | 0.47%   |
| AMD Athlon 64 X2        | 1        | 0.47%   |
| AMD A6                  | 1        | 0.47%   |
| AMD A10                 | 1        | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 90       | 42.65%  |
| 2      | 56       | 26.54%  |
| 6      | 27       | 12.8%   |
| 8      | 20       | 9.48%   |
| 12     | 9        | 4.27%   |
| 16     | 4        | 1.9%    |
| 3      | 2        | 0.95%   |
| 1      | 2        | 0.95%   |
| 10     | 1        | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 208      | 99.05%  |
| 2      | 2        | 0.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 122      | 57.82%  |
| 1      | 89       | 42.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 209      | 99.52%  |
| Unknown        | 1        | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 17.81%  |
| 0x306c3    | 22       | 10.05%  |
| 0x1067a    | 17       | 7.76%   |
| 0x906e9    | 14       | 6.39%   |
| 0x306a9    | 14       | 6.39%   |
| 0x206a7    | 13       | 5.94%   |
| 0x906ea    | 10       | 4.57%   |
| 0x506e3    | 10       | 4.57%   |
| 0xa0655    | 5        | 2.28%   |
| 0xa0653    | 5        | 2.28%   |
| 0x106e5    | 5        | 2.28%   |
| 0x08108109 | 5        | 2.28%   |
| 0xa0671    | 4        | 1.83%   |
| 0x906ed    | 4        | 1.83%   |
| 0x306e4    | 4        | 1.83%   |
| 0x08701021 | 4        | 1.83%   |
| 0x08701013 | 3        | 1.37%   |
| 0x0800820d | 3        | 1.37%   |
| 0x90672    | 2        | 0.91%   |
| 0x6fd      | 2        | 0.91%   |
| 0x20652    | 2        | 0.91%   |
| 0x10676    | 2        | 0.91%   |
| 0x06003106 | 2        | 0.91%   |
| 0x06001119 | 2        | 0.91%   |
| 0x010000c8 | 2        | 0.91%   |
| 0x906ec    | 1        | 0.46%   |
| 0x906eb    | 1        | 0.46%   |
| 0x906c0    | 1        | 0.46%   |
| 0x806ea    | 1        | 0.46%   |
| 0x706a1    | 1        | 0.46%   |
| 0x506e0    | 1        | 0.46%   |
| 0x406c4    | 1        | 0.46%   |
| 0x40671    | 1        | 0.46%   |
| 0x306d4    | 1        | 0.46%   |
| 0x30673    | 1        | 0.46%   |
| 0x206c2    | 1        | 0.46%   |
| 0x106c2    | 1        | 0.46%   |
| 0x106a5    | 1        | 0.46%   |
| 0x0a50000c | 1        | 0.46%   |
| 0x0a201016 | 1        | 0.46%   |
| 0x0a201009 | 1        | 0.46%   |
| 0x0810100b | 1        | 0.46%   |
| 0x08008206 | 1        | 0.46%   |
| 0x08001129 | 1        | 0.46%   |
| 0x08001105 | 1        | 0.46%   |
| 0x06003104 | 1        | 0.46%   |
| 0x06000852 | 1        | 0.46%   |
| 0x06000629 | 1        | 0.46%   |
| 0x01000083 | 1        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 38       | 18.01%  |
| Haswell          | 29       | 13.74%  |
| Penryn           | 19       | 9%      |
| IvyBridge        | 19       | 9%      |
| SandyBridge      | 14       | 6.64%   |
| Skylake          | 13       | 6.16%   |
| CometLake        | 13       | 6.16%   |
| Zen 2            | 9        | 4.27%   |
| Zen+             | 8        | 3.79%   |
| Nehalem          | 8        | 3.79%   |
| Zen              | 5        | 2.37%   |
| Westmere         | 4        | 1.9%    |
| Unknown          | 4        | 1.9%    |
| Zen 3            | 3        | 1.42%   |
| Steamroller      | 3        | 1.42%   |
| Piledriver       | 3        | 1.42%   |
| K10              | 3        | 1.42%   |
| Icelake          | 3        | 1.42%   |
| Silvermont       | 2        | 0.95%   |
| Core             | 2        | 0.95%   |
| Broadwell        | 2        | 0.95%   |
| Tremont          | 1        | 0.47%   |
| NetBurst         | 1        | 0.47%   |
| K8 Hammer        | 1        | 0.47%   |
| Goldmont plus    | 1        | 0.47%   |
| Bulldozer        | 1        | 0.47%   |
| Bonnell          | 1        | 0.47%   |
| Alderlake Hybrid | 1        | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 105      | 44.3%   |
| Intel  | 94       | 39.66%  |
| AMD    | 38       | 16.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 8.82%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 4.2%    |
| Intel HD Graphics 630                                                       | 10       | 4.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 4.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 4.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 3.36%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.94%   |
| Intel HD Graphics 530                                                       | 6        | 2.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.52%   |
| Nvidia GP107GL [Quadro P400]                                                | 5        | 2.1%    |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 2.1%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.1%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 2.1%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.26%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.26%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.26%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.26%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.26%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 1.26%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.84%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.84%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.84%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.84%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.84%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.84%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.84%   |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 0.84%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.84%   |
| Intel AlderLake-S GT1                                                       | 2        | 0.84%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 0.84%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 0.84%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.42%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.42%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.42%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.42%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.42%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 0.42%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.42%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.42%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.42%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 0.42%   |
| Nvidia GK210GL [Tesla K80]                                                  | 1        | 0.42%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.42%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 89       | 41.98%  |
| 1 x Intel      | 73       | 34.43%  |
| 1 x AMD        | 32       | 15.09%  |
| Intel + Nvidia | 12       | 5.66%   |
| AMD + Nvidia   | 3        | 1.42%   |
| Intel + AMD    | 2        | 0.94%   |
| 2 x AMD        | 1        | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 136      | 62.67%  |
| Proprietary | 69       | 31.8%   |
| Unknown     | 12       | 5.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 95       | 43.58%  |
| 1.01-2.0   | 41       | 18.81%  |
| 0.51-1.0   | 23       | 10.55%  |
| 3.01-4.0   | 19       | 8.72%   |
| 7.01-8.0   | 16       | 7.34%   |
| 0.01-0.5   | 12       | 5.5%    |
| 5.01-6.0   | 5        | 2.29%   |
| 2.01-3.0   | 3        | 1.38%   |
| 8.01-16.0  | 3        | 1.38%   |
| 16.01-24.0 | 1        | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 54       | 24.88%  |
| Dell                    | 37       | 17.05%  |
| Philips                 | 19       | 8.76%   |
| Goldstar                | 14       | 6.45%   |
| AOC                     | 11       | 5.07%   |
| Ancor Communications    | 8        | 3.69%   |
| ViewSonic               | 7        | 3.23%   |
| Hewlett-Packard         | 7        | 3.23%   |
| ASUSTek Computer        | 6        | 2.76%   |
| Lenovo                  | 5        | 2.3%    |
| BenQ                    | 4        | 1.84%   |
| Unknown                 | 3        | 1.38%   |
| Sanyo                   | 3        | 1.38%   |
| Lenovo Group Limited    | 3        | 1.38%   |
| Acer                    | 3        | 1.38%   |
| Unknown                 | 3        | 1.38%   |
| Panasonic               | 2        | 0.92%   |
| NEX                     | 2        | 0.92%   |
| LG Electronics          | 2        | 0.92%   |
| HKC                     | 2        | 0.92%   |
| Eizo                    | 2        | 0.92%   |
| ___                     | 1        | 0.46%   |
| VIE                     | 1        | 0.46%   |
| Unknown (AAA)           | 1        | 0.46%   |
| Toshiba                 | 1        | 0.46%   |
| SSD                     | 1        | 0.46%   |
| Sharp                   | 1        | 0.46%   |
| Sceptre Tech            | 1        | 0.46%   |
| Plain Tree Systems      | 1        | 0.46%   |
| Pioneer                 | 1        | 0.46%   |
| NXG                     | 1        | 0.46%   |
| MStar                   | 1        | 0.46%   |
| JRY                     | 1        | 0.46%   |
| Iiyama                  | 1        | 0.46%   |
| Hitachi                 | 1        | 0.46%   |
| HannStar Display        | 1        | 0.46%   |
| Fujitsu Siemens         | 1        | 0.46%   |
| CVT                     | 1        | 0.46%   |
| Chi Mei Optoelectronics | 1        | 0.46%   |
| AUS                     | 1        | 0.46%   |
| AGO                     | 1        | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4        | 1.75%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 4        | 1.75%   |
| Philips LCD Monitor PHLC052 1920x1080 480x270mm 21.7-inch             | 4        | 1.75%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 4        | 1.75%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 4        | 1.75%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch  | 3        | 1.32%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 3        | 1.32%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 3        | 1.32%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 3        | 1.32%   |
| Unknown                                                               | 3        | 1.32%   |
| Sanyo LCD MONITOR SAN07BE 1280x1024 350x270mm 17.4-inch               | 2        | 0.88%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch  | 2        | 0.88%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch  | 2        | 0.88%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.88%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch     | 2        | 0.88%   |
| Samsung Electronics LCD Monitor SMBX2450 1920x1080                    | 2        | 0.88%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch     | 2        | 0.88%   |
| Panasonic TV MEIA296 1360x768                                         | 2        | 0.88%   |
| Lenovo Group Limited LCD Monitor L24q-10                              | 2        | 0.88%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 2        | 0.88%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 2        | 0.88%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.88%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 2        | 0.88%   |
| ASUSTek Computer VG248 AUS24AB 1920x1080 531x299mm 24.0-inch          | 2        | 0.88%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2        | 0.88%   |
| ___ LCDTV14 ___0101 1920x1080                                         | 1        | 0.44%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch         | 1        | 0.44%   |
| ViewSonic VX2237 SERIES VSC2C24 1680x1050 474x296mm 22.0-inch         | 1        | 0.44%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch             | 1        | 0.44%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 0.44%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                 | 1        | 0.44%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1        | 0.44%   |
| ViewSonic PJ VSC2D36 3840x2160                                        | 1        | 0.44%   |
| ViewSonic LCD Monitor VA2719 Series                                   | 1        | 0.44%   |
| VIE M2487HVB VIE1919 1920x1080 520x310mm 23.8-inch                    | 1        | 0.44%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                    | 1        | 0.44%   |
| Unknown LCD Monitor SAMSUNG 3520x1080                                 | 1        | 0.44%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.44%   |
| Unknown (AAA) smart tv AAA0001 1920x1080 1600x900mm 72.3-inch         | 1        | 0.44%   |
| Toshiba LCD Monitor TV                                                | 1        | 0.44%   |
| SSD HDTV SSD0001 1360x768 708x398mm 32.0-inch                         | 1        | 0.44%   |
| Sharp HDMI SHP4176 1920x1080 1210x680mm 54.6-inch                     | 1        | 0.44%   |
| Sceptre Tech Sceptre E22 SPT08D5 1920x1080 470x300mm 22.0-inch        | 1        | 0.44%   |
| Sanyo LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch               | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM0571 1920x1080 510x287mm 23.0-inch  | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch  | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM043F 1920x1200 518x324mm 24.1-inch  | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM0379 1680x1050 433x271mm 20.1-inch  | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 459x296mm 21.5-inch  | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM01B9 1280x1024 338x270mm 17.0-inch  | 1        | 0.44%   |
| Samsung Electronics SMS19A200 SAM0830 1440x900 408x255mm 18.9-inch    | 1        | 0.44%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1        | 0.44%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1        | 0.44%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch     | 1        | 0.44%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1        | 0.44%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 0.44%   |
| Samsung Electronics S27E391 SAM0C16 1920x1080 598x336mm 27.0-inch     | 1        | 0.44%   |
| Samsung Electronics S27E332 SAM0F60 1920x1080 598x336mm 27.0-inch     | 1        | 0.44%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch     | 1        | 0.44%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 1        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 123      | 58.02%  |
| 1680x1050 (WSXGA+) | 15       | 7.08%   |
| 3840x2160 (4K)     | 11       | 5.19%   |
| 1280x1024 (SXGA)   | 11       | 5.19%   |
| 2560x1440 (QHD)    | 10       | 4.72%   |
| 1920x1200 (WUXGA)  | 10       | 4.72%   |
| Unknown            | 7        | 3.3%    |
| 1440x900 (WXGA+)   | 5        | 2.36%   |
| 1600x900 (HD+)     | 3        | 1.42%   |
| 3840x1080          | 2        | 0.94%   |
| 2560x1080          | 2        | 0.94%   |
| 1920x540           | 2        | 0.94%   |
| 1366x768 (WXGA)    | 2        | 0.94%   |
| 5360x1440          | 1        | 0.47%   |
| 5120x1440          | 1        | 0.47%   |
| 4480x1440          | 1        | 0.47%   |
| 3520x1080          | 1        | 0.47%   |
| 3440x1440          | 1        | 0.47%   |
| 2560x1600          | 1        | 0.47%   |
| 1360x768           | 1        | 0.47%   |
| 1280x768           | 1        | 0.47%   |
| 1024x768 (XGA)     | 1        | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 42       | 19.81%  |
| 24      | 39       | 18.4%   |
| 23      | 27       | 12.74%  |
| Unknown | 25       | 11.79%  |
| 27      | 22       | 10.38%  |
| 22      | 14       | 6.6%    |
| 17      | 7        | 3.3%    |
| 19      | 6        | 2.83%   |
| 20      | 5        | 2.36%   |
| 84      | 3        | 1.42%   |
| 72      | 3        | 1.42%   |
| 18      | 3        | 1.42%   |
| 54      | 2        | 0.94%   |
| 33      | 2        | 0.94%   |
| 32      | 2        | 0.94%   |
| 31      | 2        | 0.94%   |
| 60      | 1        | 0.47%   |
| 52      | 1        | 0.47%   |
| 49      | 1        | 0.47%   |
| 48      | 1        | 0.47%   |
| 42      | 1        | 0.47%   |
| 34      | 1        | 0.47%   |
| 29      | 1        | 0.47%   |
| 16      | 1        | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 84       | 40.58%  |
| 401-500     | 64       | 30.92%  |
| Unknown     | 25       | 12.08%  |
| 301-350     | 7        | 3.38%   |
| 1501-2000   | 6        | 2.9%    |
| 1001-1500   | 6        | 2.9%    |
| 701-800     | 5        | 2.42%   |
| 601-700     | 5        | 2.42%   |
| 351-400     | 4        | 1.93%   |
| 901-1000    | 1        | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 129      | 63.86%  |
| 16/10   | 36       | 17.82%  |
| Unknown | 24       | 11.88%  |
| 5/4     | 7        | 3.47%   |
| 4/3     | 4        | 1.98%   |
| 21/9    | 1        | 0.5%    |
| 1.96    | 1        | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 95       | 45.67%  |
| Unknown        | 25       | 12.02%  |
| 151-200        | 23       | 11.06%  |
| 301-350        | 22       | 10.58%  |
| 251-300        | 14       | 6.73%   |
| More than 1000 | 11       | 5.29%   |
| 351-500        | 8        | 3.85%   |
| 141-150        | 7        | 3.37%   |
| 501-1000       | 2        | 0.96%   |
| 131-140        | 1        | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 113      | 55.67%  |
| 101-120 | 49       | 24.14%  |
| Unknown | 25       | 12.32%  |
| 1-50    | 11       | 5.42%   |
| 121-160 | 4        | 1.97%   |
| 161-240 | 1        | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 165      | 77.46%  |
| 2     | 33       | 15.49%  |
| 0     | 14       | 6.57%   |
| 4     | 1        | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 133      | 44.33%  |
| Intel                           | 88       | 29.33%  |
| Qualcomm Atheros                | 22       | 7.33%   |
| Ralink Technology               | 11       | 3.67%   |
| TP-Link                         | 7        | 2.33%   |
| Edimax Technology               | 6        | 2%      |
| Ralink                          | 3        | 1%      |
| ASIX Electronics                | 3        | 1%      |
| Xiaomi                          | 2        | 0.67%   |
| Qualcomm Atheros Communications | 2        | 0.67%   |
| Nvidia                          | 2        | 0.67%   |
| Marvell Technology Group        | 2        | 0.67%   |
| D-Link                          | 2        | 0.67%   |
| Broadcom Limited                | 2        | 0.67%   |
| Broadcom                        | 2        | 0.67%   |
| U.S. Robotics                   | 1        | 0.33%   |
| Texas Instruments               | 1        | 0.33%   |
| STMicroelectronics              | 1        | 0.33%   |
| ROCCAT                          | 1        | 0.33%   |
| Microsoft                       | 1        | 0.33%   |
| Mellanox Technologies           | 1        | 0.33%   |
| MediaTek                        | 1        | 0.33%   |
| Huawei Technologies             | 1        | 0.33%   |
| GDMicroelectronics              | 1        | 0.33%   |
| Davicom Semiconductor           | 1        | 0.33%   |
| BUFFALO                         | 1        | 0.33%   |
| Aquantia                        | 1        | 0.33%   |
| Accton Technology               | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 106      | 31.93%  |
| Intel Ethernet Connection (2) I219-V                                                          | 14       | 4.22%   |
| Intel I211 Gigabit Network Connection                                                         | 12       | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 11       | 3.31%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 10       | 3.01%   |
| Intel Ethernet Connection (7) I219-V                                                          | 8        | 2.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 7        | 2.11%   |
| Intel Wi-Fi 6 AX200                                                                           | 7        | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 4        | 1.2%    |
| Realtek 802.11ac NIC                                                                          | 4        | 1.2%    |
| Intel Ethernet Connection I217-LM                                                             | 4        | 1.2%    |
| Intel Ethernet Connection (5) I219-LM                                                         | 4        | 1.2%    |
| Intel Ethernet Connection (14) I219-V                                                         | 4        | 1.2%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 3        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3        | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 0.9%    |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 3        | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3        | 0.9%    |
| Intel Wireless-AC 9260                                                                        | 3        | 0.9%    |
| Intel Ethernet Connection I217-V                                                              | 3        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 3        | 0.9%    |
| Intel 82579V Gigabit Network Connection                                                       | 3        | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                                                 | 3        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 0.6%    |
| TP-Link Archer T4U ver.3                                                                      | 2        | 0.6%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 0.6%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 2        | 0.6%    |
| Nvidia MCP61 Ethernet                                                                         | 2        | 0.6%    |
| Intel Wireless 3165                                                                           | 2        | 0.6%    |
| Intel Ethernet Connection (12) I219-V                                                         | 2        | 0.6%    |
| Intel Ethernet Connection (11) I219-V                                                         | 2        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2        | 0.6%    |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2        | 0.6%    |
| Edimax RTL8192S WLAN Adapter                                                                  | 2        | 0.6%    |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                      | 2        | 0.6%    |
| Edimax AC600 USB                                                                              | 2        | 0.6%    |
| U.S. Robotics USR5637 56K Faxmodem                                                            | 1        | 0.3%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.3%    |
| TP-Link 802.11ac NIC                                                                          | 1        | 0.3%    |
| Texas Instruments CC2531 ZigBee                                                               | 1        | 0.3%    |
| STMicroelectronics Virtual COM Port                                                           | 1        | 0.3%    |
| ROCCAT OSA Express Network card                                                               | 1        | 0.3%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.3%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.3%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.3%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.3%    |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1        | 0.3%    |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 25.27%  |
| Realtek Semiconductor           | 22       | 24.18%  |
| Ralink Technology               | 11       | 12.09%  |
| Qualcomm Atheros                | 10       | 10.99%  |
| TP-Link                         | 7        | 7.69%   |
| Edimax Technology               | 6        | 6.59%   |
| Ralink                          | 3        | 3.3%    |
| Qualcomm Atheros Communications | 2        | 2.2%    |
| D-Link                          | 2        | 2.2%    |
| Broadcom                        | 2        | 2.2%    |
| Microsoft                       | 1        | 1.1%    |
| MediaTek                        | 1        | 1.1%    |
| BUFFALO                         | 1        | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 7        | 7.61%   |
| Intel Wi-Fi 6 AX200                                                                           | 7        | 7.61%   |
| Realtek 802.11ac NIC                                                                          | 4        | 4.35%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 3        | 3.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3        | 3.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 3.26%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 3.26%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 3.26%   |
| Intel Wireless-AC 9260                                                                        | 3        | 3.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 3        | 3.26%   |
| TP-Link Archer T4U ver.3                                                                      | 2        | 2.17%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 2.17%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 2.17%   |
| Intel Wireless 3165                                                                           | 2        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2        | 2.17%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 2        | 2.17%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                      | 2        | 2.17%   |
| Edimax AC600 USB                                                                              | 2        | 2.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.09%   |
| TP-Link 802.11ac NIC                                                                          | 1        | 1.09%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 1.09%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.09%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.09%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.09%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.09%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 1.09%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.09%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 1.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.09%   |
| Ralink RT2600 802.11 MIMO                                                                     | 1        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1        | 1.09%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.09%   |
| MediaTek WiFi                                                                                 | 1        | 1.09%   |
| Intel Wireless 3160                                                                           | 1        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1        | 1.09%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1        | 1.09%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 1.09%   |
| D-Link DWA-160 Xtreme N Dual Band USB Adapter(rev.C1)                                         | 1        | 1.09%   |
| D-Link 802.11n WLAN Adapter                                                                   | 1        | 1.09%   |
| BUFFALO Sony UWA-BR100 802.11abgn Wireless Adapter [Atheros AR7010+AR9280]                    | 1        | 1.09%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1        | 1.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 123      | 53.95%  |
| Intel                    | 77       | 33.77%  |
| Qualcomm Atheros         | 12       | 5.26%   |
| ASIX Electronics         | 3        | 1.32%   |
| Xiaomi                   | 2        | 0.88%   |
| Nvidia                   | 2        | 0.88%   |
| Marvell Technology Group | 2        | 0.88%   |
| Broadcom Limited         | 2        | 0.88%   |
| Mellanox Technologies    | 1        | 0.44%   |
| Huawei Technologies      | 1        | 0.44%   |
| Davicom Semiconductor    | 1        | 0.44%   |
| Aquantia                 | 1        | 0.44%   |
| Accton Technology        | 1        | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 106      | 45.11%  |
| Intel Ethernet Connection (2) I219-V                                | 14       | 5.96%   |
| Intel I211 Gigabit Network Connection                               | 12       | 5.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 11       | 4.68%   |
| Realtek RTL8125 2.5GbE Controller                                   | 10       | 4.26%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 3.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 4        | 1.7%    |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.7%    |
| Intel Ethernet Connection (5) I219-LM                               | 4        | 1.7%    |
| Intel Ethernet Connection (14) I219-V                               | 4        | 1.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 3        | 1.28%   |
| Intel Ethernet Connection I217-V                                    | 3        | 1.28%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                       | 3        | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.85%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                       | 2        | 0.85%   |
| Nvidia MCP61 Ethernet                                               | 2        | 0.85%   |
| Intel Ethernet Connection (12) I219-V                               | 2        | 0.85%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 2        | 0.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                              | 1        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.43%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]               | 1        | 0.43%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller             | 1        | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller             | 1        | 0.43%   |
| Intel I350 Gigabit Network Connection                               | 1        | 0.43%   |
| Intel I210 Gigabit Fiber Network Connection                         | 1        | 0.43%   |
| Intel Ethernet Controller I225-V                                    | 1        | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 0.43%   |
| Intel Ethernet Connection (17) I219-V                               | 1        | 0.43%   |
| Intel Ethernet Connection (11) I219-LM                              | 1        | 0.43%   |
| Intel 82578DC Gigabit Network Connection                            | 1        | 0.43%   |
| Intel 82576 Gigabit Network Connection                              | 1        | 0.43%   |
| Intel 82574L Gigabit Network Connection                             | 1        | 0.43%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 1        | 0.43%   |
| Intel 82562V-2 10/100 Network Connection                            | 1        | 0.43%   |
| Intel 82541PI Gigabit Ethernet Controller                           | 1        | 0.43%   |
| Huawei E353/E3131                                                   | 1        | 0.43%   |
| Davicom ST268                                                       | 1        | 0.43%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express       | 1        | 0.43%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe             | 1        | 0.43%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.43%   |
| Accton EN-1216 Ethernet Adapter                                     | 1        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 208      | 70.27%  |
| WiFi     | 83       | 28.04%  |
| Modem    | 4        | 1.35%   |
| Unknown  | 1        | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 171      | 77.38%  |
| WiFi     | 50       | 22.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 155      | 73.46%  |
| 2     | 45       | 21.33%  |
| 3     | 9        | 4.27%   |
| 0     | 2        | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 185      | 85.65%  |
| Yes  | 31       | 14.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 40%     |
| Cambridge Silicon Radio         | 20       | 40%     |
| Qualcomm Atheros Communications | 4        | 8%      |
| ASUSTek Computer                | 3        | 6%      |
| Realtek Semiconductor           | 1        | 2%      |
| IMC Networks                    | 1        | 2%      |
| Broadcom                        | 1        | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 40%     |
| Intel AX200 Bluetooth                               | 6        | 12%     |
| Intel Bluetooth wireless interface                  | 5        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 6%      |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4%      |
| ASUS Bluetooth Adapter                              | 2        | 4%      |
| Realtek Bluetooth Radio                             | 1        | 2%      |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2%      |
| Intel AX210 Bluetooth                               | 1        | 2%      |
| IMC Networks Bluetooth Device                       | 1        | 2%      |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2%      |
| ASUS BCM20702A0                                     | 1        | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 167      | 47.71%  |
| Nvidia               | 101      | 28.86%  |
| AMD                  | 50       | 14.29%  |
| C-Media Electronics  | 7        | 2%      |
| Creative Labs        | 5        | 1.43%   |
| XMOS                 | 3        | 0.86%   |
| Focusrite-Novation   | 3        | 0.86%   |
| Creative Technology  | 3        | 0.86%   |
| VIA Technologies     | 1        | 0.29%   |
| Texas Instruments    | 1        | 0.29%   |
| Razer USA            | 1        | 0.29%   |
| Microsoft            | 1        | 0.29%   |
| Meridian             | 1        | 0.29%   |
| Logitech             | 1        | 0.29%   |
| Kingston Technology  | 1        | 0.29%   |
| JMTek                | 1        | 0.29%   |
| iCreate Technologies | 1        | 0.29%   |
| GN Netcom            | 1        | 0.29%   |
| EGO SYStems          | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22       | 5.6%    |
| Intel 200 Series PCH HD Audio                                              | 20       | 5.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19       | 4.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18       | 4.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 15       | 3.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 3.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14       | 3.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 2.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 11       | 2.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 2.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 2.29%   |
| Nvidia High Definition Audio Controller                                    | 8        | 2.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 2.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 1.78%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 1.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.27%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 1.27%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.02%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.02%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.02%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1.02%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 1.02%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.02%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.76%   |
| Intel Audio device                                                         | 3        | 0.76%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.76%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3        | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.76%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 3        | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 0.76%   |
| XMOS AIRPULSE A100                                                         | 2        | 0.51%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 0.51%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2        | 0.51%   |
| Intel Broadwell-U Audio Controller                                         | 2        | 0.51%   |
| C-Media Electronics SADES Luna                                             | 2        | 0.51%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 0.51%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 0.51%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1        | 0.25%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 0.25%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.25%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1        | 0.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.25%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 21.31%  |
| Unknown             | 20       | 16.39%  |
| Crucial             | 16       | 13.11%  |
| Corsair             | 13       | 10.66%  |
| G.Skill             | 11       | 9.02%   |
| SK Hynix            | 8        | 6.56%   |
| Samsung Electronics | 8        | 6.56%   |
| Micron Technology   | 6        | 4.92%   |
| Team                | 3        | 2.46%   |
| Ramaxel Technology  | 3        | 2.46%   |
| Transcend           | 2        | 1.64%   |
| GeIL                | 2        | 1.64%   |
| Unknown (09D5)      | 1        | 0.82%   |
| Patriot             | 1        | 0.82%   |
| KETECH              | 1        | 0.82%   |
| A-DATA Technology   | 1        | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s    | 3        | 2.26%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 2        | 1.5%    |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2        | 1.5%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 2        | 1.5%    |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 2        | 1.5%    |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s     | 2        | 1.5%    |
| Kingston RAM KHX2400C15D4/4G 4096MB DIMM DDR4 3151MT/s     | 2        | 1.5%    |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s       | 2        | 1.5%    |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 2        | 1.5%    |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s      | 2        | 1.5%    |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s       | 2        | 1.5%    |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 2        | 1.5%    |
| Crucial RAM CT16G4DFD832A.C16FP 16384MB DIMM DDR4 3200MT/s | 2        | 1.5%    |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1        | 0.75%   |
| Unknown RAM Module 8192MB DIMM 800MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                   | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 667MT/s                        | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                   | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                     | 1        | 0.75%   |
| Unknown (09D5) RAM Module 8GB DIMM DDR4 2400MT/s           | 1        | 0.75%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s           | 1        | 0.75%   |
| Transcend RAM JM2666HLE-16G 16GB DIMM DDR4 2667MT/s        | 1        | 0.75%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s         | 1        | 0.75%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                 | 1        | 0.75%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                 | 1        | 0.75%   |
| SK Hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s   | 1        | 0.75%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1        | 0.75%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s    | 1        | 0.75%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s    | 1        | 0.75%   |
| SK Hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s       | 1        | 0.75%   |
| SK Hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s      | 1        | 0.75%   |
| SK Hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s       | 1        | 0.75%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 0.75%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s        | 1        | 0.75%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s       | 1        | 0.75%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s        | 1        | 0.75%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s     | 1        | 0.75%   |
| Samsung RAM ARM Ltd:R00MM0M006 2048MB DIMM DDR2 800MT/s    | 1        | 0.75%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s    | 1        | 0.75%   |
| Ramaxel RAM RMUA5110KE68H9F-2400 4GB DIMM DDR4 2400MT/s    | 1        | 0.75%   |
| Ramaxel RAM RMR5030KD68F9F1600 4GB DIMM DDR3 1600MT/s      | 1        | 0.75%   |
| Patriot RAM 1600EL Series 4GB DIMM DDR3 1600MT/s           | 1        | 0.75%   |
| Micron RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 0.75%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s         | 1        | 0.75%   |
| Micron RAM 16HTF25664AY-800J1 2GB DIMM DDR2 800MT/s        | 1        | 0.75%   |
| Micron RAM 16HTF25664AY-1GAE1 2048MB DIMM DDR2 667MT/s     | 1        | 0.75%   |
| Kingston RAM XVTW4H-MIE 32GB DIMM DDR4 3200MT/s            | 1        | 0.75%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s     | 1        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 61       | 55.45%  |
| DDR3    | 26       | 23.64%  |
| Unknown | 12       | 10.91%  |
| DDR2    | 6        | 5.45%   |
| SDRAM   | 4        | 3.64%   |
| DDR     | 1        | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 108      | 98.18%  |
| SODIMM | 2        | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 28.57%  |
| 4096  | 34       | 28.57%  |
| 16384 | 25       | 21.01%  |
| 2048  | 18       | 15.13%  |
| 32768 | 4        | 3.36%   |
| 1024  | 4        | 3.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 15.57%  |
| 3200    | 16       | 13.11%  |
| 800     | 11       | 9.02%   |
| 2400    | 10       | 8.2%    |
| 2133    | 10       | 8.2%    |
| 1333    | 10       | 8.2%    |
| 3600    | 6        | 4.92%   |
| 2667    | 6        | 4.92%   |
| 3466    | 3        | 2.46%   |
| 2933    | 3        | 2.46%   |
| 1867    | 3        | 2.46%   |
| 667     | 3        | 2.46%   |
| Unknown | 3        | 2.46%   |
| 3151    | 2        | 1.64%   |
| 2000    | 2        | 1.64%   |
| 1866    | 2        | 1.64%   |
| 1400    | 2        | 1.64%   |
| 49926   | 1        | 0.82%   |
| 4400    | 1        | 0.82%   |
| 3800    | 1        | 0.82%   |
| 3733    | 1        | 0.82%   |
| 3400    | 1        | 0.82%   |
| 3066    | 1        | 0.82%   |
| 3000    | 1        | 0.82%   |
| 2800    | 1        | 0.82%   |
| 2134    | 1        | 0.82%   |
| 1800    | 1        | 0.82%   |
| 400     | 1        | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 6        | 46.15%  |
| Samsung Electronics   | 2        | 15.38%  |
| Canon                 | 2        | 15.38%  |
| Lexmark International | 1        | 7.69%   |
| GODEX INTERNATIONAL   | 1        | 7.69%   |
| Brother Industries    | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung M2070 Series          | 2        | 15.38%  |
| HP Officejet 4500 G510g-m     | 2        | 15.38%  |
| Lexmark International CS417dn | 1        | 7.69%   |
| HP Printing Support           | 1        | 7.69%   |
| HP LaserJet M14-M17           | 1        | 7.69%   |
| HP DeskJet 4670 series        | 1        | 7.69%   |
| HP Deskjet 4640 series        | 1        | 7.69%   |
| GODEX INTERNATIONAL DT2       | 1        | 7.69%   |
| Canon TR7500 series           | 1        | 7.69%   |
| Canon PIXMA MX490 Series      | 1        | 7.69%   |
| Brother MFC-J497DW            | 1        | 7.69%   |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 16       | 31.37%  |
| Microsoft              | 15       | 29.41%  |
| Samsung Electronics    | 4        | 7.84%   |
| Generalplus Technology | 4        | 7.84%   |
| Apple                  | 2        | 3.92%   |
| Xiaomi                 | 1        | 1.96%   |
| Realtek Semiconductor  | 1        | 1.96%   |
| Quanta                 | 1        | 1.96%   |
| Microdia               | 1        | 1.96%   |
| Jieli Technology       | 1        | 1.96%   |
| IMC Networks           | 1        | 1.96%   |
| Hewlett-Packard        | 1        | 1.96%   |
| Chicony Electronics    | 1        | 1.96%   |
| Aveo Technology        | 1        | 1.96%   |
| Alcor Micro            | 1        | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                           | 12       | 23.53%  |
| Samsung Galaxy A5 (MTP)                             | 4        | 7.84%   |
| Logitech Webcam C270                                | 3        | 5.88%   |
| Generalplus CAMERA - UVC                            | 3        | 5.88%   |
| Logitech Webcam C310                                | 2        | 3.92%   |
| Logitech C922 Pro Stream Webcam                     | 2        | 3.92%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                  | 1        | 1.96%   |
| Realtek Web Camera                                  | 1        | 1.96%   |
| Quanta Astro HD Camera                              | 1        | 1.96%   |
| Microsoft MicrosoftÂ LifeCam Studio                | 1        | 1.96%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 1.96%   |
| Microsoft MicrosoftÂ LifeCam Cinema                | 1        | 1.96%   |
| Microdia USB Camera                                 | 1        | 1.96%   |
| Logitech Webcam C930e                               | 1        | 1.96%   |
| Logitech Webcam C925e                               | 1        | 1.96%   |
| Logitech Webcam C920-C                              | 1        | 1.96%   |
| Logitech Webcam C170                                | 1        | 1.96%   |
| Logitech QuickCam E 3500                            | 1        | 1.96%   |
| Logitech Mic (Fusion)                               | 1        | 1.96%   |
| Logitech HD Webcam C615                             | 1        | 1.96%   |
| Logitech C930c                                      | 1        | 1.96%   |
| Logitech BRIO Ultra HD Webcam                       | 1        | 1.96%   |
| Jieli USB PHY 2.0                                   | 1        | 1.96%   |
| IMC Networks XHC Camera                             | 1        | 1.96%   |
| HP Webcam HD 2300                                   | 1        | 1.96%   |
| Generalplus WEB CAM                                 | 1        | 1.96%   |
| Chicony Gateway Webcam                              | 1        | 1.96%   |
| Aveo UVC camera (Bresser microscope)                | 1        | 1.96%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1        | 1.96%   |
| Apple iPad 2 (3G; 64GB)                             | 1        | 1.96%   |
| Alcor Micro USB 2.0 PC Camera                       | 1        | 1.96%   |

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
| 0     | 183      | 85.12%  |
| 1     | 27       | 12.56%  |
| 2     | 5        | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 17       | 45.95%  |
| Net/wireless             | 13       | 35.14%  |
| Communication controller | 4        | 10.81%  |
| Camera                   | 3        | 8.11%   |

