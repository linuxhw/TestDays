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

Total: 319

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| ASUSTek    | TUF GAMING X570-PLUS        | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| Gigabyte   | B560M DS3H                  | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek    | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek    | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| ASUSTek    | TUF GAMING B550-PLUS        | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
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
| ASUSTek    | TUF GAMING X570-PLUS        | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASRock     | H370M Pro4                  | [2865692c58](https://linux-hardware.org/?probe=2865692c58) | Oct 05, 2021 |
| ASUSTek    | P8H61-M LX R2.0             | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| HP         | 1497                        | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| ASUSTek    | H81M-E R2.0                 | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| ASUSTek    | Z170-K                      | [e5e1953ed8](https://linux-hardware.org/?probe=e5e1953ed8) | Sep 05, 2021 |
| HP         | 158A                        | [6c22e51bfc](https://linux-hardware.org/?probe=6c22e51bfc) | Sep 04, 2021 |
| Dell       | 06X1TJ A00                  | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [535deb980c](https://linux-hardware.org/?probe=535deb980c) | Aug 17, 2021 |
| ASUSTek    | PRIME Z370-P II             | [68213450a7](https://linux-hardware.org/?probe=68213450a7) | Aug 14, 2021 |
| Lenovo     | 3102 SDK0K13476 WIN 3306... | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| ASUSTek    | PRIME Z370-P II             | [94cfaf19af](https://linux-hardware.org/?probe=94cfaf19af) | Aug 14, 2021 |
| Gigabyte   | X58-USB3                    | [8a48f8d2bc](https://linux-hardware.org/?probe=8a48f8d2bc) | Jul 31, 2021 |
| Gigabyte   | Z270XP-SLI-CF               | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| ASUSTek    | P8P67 DELUXE                | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| ASUSTek    | P7H55-M PRO                 | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| Dell       | 06X1TJ A00                  | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell       | 06X1TJ A00                  | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| Dell       | 06X1TJ A00                  | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell       | 0GMM0G A00                  | [2c9050ccd9](https://linux-hardware.org/?probe=2c9050ccd9) | Jul 03, 2021 |
| Gigabyte   | Z270XP-SLI-CF               | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| Pegatron   | 2A94h                       | [5475faba11](https://linux-hardware.org/?probe=5475faba11) | Jun 19, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| Gigabyte   | B360M HD3                   | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| Gigabyte   | B360M HD3                   | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| ASUSTek    | PRIME Z490-P                | [59cf3396c0](https://linux-hardware.org/?probe=59cf3396c0) | Jun 13, 2021 |
| ASRock     | H370M Pro4                  | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [d68abf1123](https://linux-hardware.org/?probe=d68abf1123) | Jun 04, 2021 |
| ASUSTek    | PRIME X470-PRO              | [aea7394e24](https://linux-hardware.org/?probe=aea7394e24) | Jun 01, 2021 |
| ASUSTek    | H110M-A/M.2                 | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Intel      | DP55WB AAE64798-205         | [a760607f4e](https://linux-hardware.org/?probe=a760607f4e) | May 27, 2021 |
| Gigabyte   | B450 AORUS M                | [a7a67287a3](https://linux-hardware.org/?probe=a7a67287a3) | May 26, 2021 |
| Intel      | DP55WB AAE64798-205         | [7070bcfa9a](https://linux-hardware.org/?probe=7070bcfa9a) | May 24, 2021 |
| Gigabyte   | H61M-S1                     | [2f7da43eb2](https://linux-hardware.org/?probe=2f7da43eb2) | May 23, 2021 |
| ASRock     | H370M Pro4                  | [72deada743](https://linux-hardware.org/?probe=72deada743) | May 23, 2021 |
| ASUSTek    | PRIME Z590M-PLUS            | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
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
| MSI        | G41TM-P33                   | [693f769d44](https://linux-hardware.org/?probe=693f769d44) | Mar 15, 2021 |
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
| Lenovo     | Board                       | [987ed81d7d](https://linux-hardware.org/?probe=987ed81d7d) | Nov 03, 2020 |
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
| ASUSTek    | ROG STRIX Z390-E GAMING     | [1ac84abaa8](https://linux-hardware.org/?probe=1ac84abaa8) | Oct 19, 2020 |
| ASUSTek    | ROG STRIX Z390-E GAMING     | [6ba76947d7](https://linux-hardware.org/?probe=6ba76947d7) | Oct 18, 2020 |
| ASUSTek    | PRIME Z490-P                | [44d70b326c](https://linux-hardware.org/?probe=44d70b326c) | Oct 13, 2020 |
| Gigabyte   | B360M HD3                   | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Lenovo     | Board                       | [986a5e604f](https://linux-hardware.org/?probe=986a5e604f) | Oct 03, 2020 |
| ASRock     | X399 Taichi                 | [268a9d5625](https://linux-hardware.org/?probe=268a9d5625) | Oct 01, 2020 |
| ASUSTek    | P5G41C-M LX                 | [353229fd96](https://linux-hardware.org/?probe=353229fd96) | Sep 29, 2020 |
| Unknown    | Unknown                     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| ASRock     | H97M Anniversary            | [cc0e0f5c04](https://linux-hardware.org/?probe=cc0e0f5c04) | Sep 29, 2020 |
| MSI        | G41M-E43                    | [5a567b1f97](https://linux-hardware.org/?probe=5a567b1f97) | Sep 28, 2020 |
| Lenovo     | Board                       | [5d73c67b98](https://linux-hardware.org/?probe=5d73c67b98) | Sep 28, 2020 |
| Lenovo     | Board                       | [9c9f5b4cfa](https://linux-hardware.org/?probe=9c9f5b4cfa) | Sep 10, 2020 |
| Gigabyte   | B360M HD3                   | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| HP         | 339A                        | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| ASUSTek    | ROG Maximus XI HERO         | [42deb7cee5](https://linux-hardware.org/?probe=42deb7cee5) | Sep 03, 2020 |
| ASUSTek    | PRIME Z370-P                | [5bfd2a1403](https://linux-hardware.org/?probe=5bfd2a1403) | Sep 03, 2020 |
| MSI        | 2A9Ch                       | [aa629696b3](https://linux-hardware.org/?probe=aa629696b3) | Aug 28, 2020 |
| MSI        | 2A9Ch                       | [0ece5d52d2](https://linux-hardware.org/?probe=0ece5d52d2) | Aug 27, 2020 |
| ASUSTek    | P8H61-M LX R2.0             | [56afe1e282](https://linux-hardware.org/?probe=56afe1e282) | Aug 27, 2020 |
| ASRock     | H97M Anniversary            | [613aba4134](https://linux-hardware.org/?probe=613aba4134) | Aug 23, 2020 |
| ASUSTek    | TUF GAMING B550-PLUS        | [a114ae9c9c](https://linux-hardware.org/?probe=a114ae9c9c) | Aug 12, 2020 |
| Lenovo     | SHARKBAY SDK0E50519 WIN     | [1828dedb7f](https://linux-hardware.org/?probe=1828dedb7f) | Aug 10, 2020 |
| MSI        | G41M-E43                    | [14b52bd540](https://linux-hardware.org/?probe=14b52bd540) | Aug 08, 2020 |
| ASUSTek    | TUF GAMING B460-PLUS        | [0d864b4feb](https://linux-hardware.org/?probe=0d864b4feb) | Aug 08, 2020 |
| ASUSTek    | TUF GAMING B460-PLUS        | [69e782093d](https://linux-hardware.org/?probe=69e782093d) | Aug 08, 2020 |
| Gigabyte   | Z270-HD3P-CF                | [3fe0ec39fc](https://linux-hardware.org/?probe=3fe0ec39fc) | Aug 07, 2020 |
| ASRock     | H55M                        | [f2d0fa78ac](https://linux-hardware.org/?probe=f2d0fa78ac) | Aug 06, 2020 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [5c3dc530c3](https://linux-hardware.org/?probe=5c3dc530c3) | Aug 04, 2020 |
| Gigabyte   | Z97-HD3                     | [2e41ce3f03](https://linux-hardware.org/?probe=2e41ce3f03) | Jul 31, 2020 |
| Gigabyte   | Z97-HD3                     | [50888e0851](https://linux-hardware.org/?probe=50888e0851) | Jul 31, 2020 |
| ASRock     | H55M                        | [dcbc0735f5](https://linux-hardware.org/?probe=dcbc0735f5) | Jul 30, 2020 |
| ASUSTek    | P8H67-M PRO                 | [a7e0318966](https://linux-hardware.org/?probe=a7e0318966) | Jul 30, 2020 |
| ASUSTek    | AT3N7A-I                    | [57c3ce82b7](https://linux-hardware.org/?probe=57c3ce82b7) | Jul 29, 2020 |
| HARDKERNEL | ODROID-H2                   | [c86e7dc968](https://linux-hardware.org/?probe=c86e7dc968) | Jul 23, 2020 |
| MSI        | G41M-E43                    | [afffd4f5c3](https://linux-hardware.org/?probe=afffd4f5c3) | Jul 17, 2020 |
| Gigabyte   | H61M-S1                     | [2a63a11959](https://linux-hardware.org/?probe=2a63a11959) | Jul 08, 2020 |
| ASRock     | H97M Anniversary            | [5cddf51d89](https://linux-hardware.org/?probe=5cddf51d89) | Jul 03, 2020 |
| ASUSTek    | P8Z68-V PRO GEN3            | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte   | G31M-S2C                    | [da847897f9](https://linux-hardware.org/?probe=da847897f9) | Jun 15, 2020 |
| MSI        | G41M-E43                    | [4c72170ef6](https://linux-hardware.org/?probe=4c72170ef6) | Jun 06, 2020 |
| ASUSTek    | PRIME H310M-E R2.0          | [48f5173ede](https://linux-hardware.org/?probe=48f5173ede) | May 27, 2020 |
| ASUSTek    | PRIME H310M-E R2.0          | [72b226183e](https://linux-hardware.org/?probe=72b226183e) | May 27, 2020 |
| ASUSTek    | F2A85-M PRO                 | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| ASUSTek    | F2A85-M PRO                 | [0a1818bac0](https://linux-hardware.org/?probe=0a1818bac0) | May 19, 2020 |
| Gigabyte   | F2A88XM-DS2                 | [bd5ec5436e](https://linux-hardware.org/?probe=bd5ec5436e) | May 15, 2020 |
| Gigabyte   | F2A88XM-DS2                 | [355e03bb68](https://linux-hardware.org/?probe=355e03bb68) | May 15, 2020 |
| HP         | 339A                        | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| ASUSTek    | F2A85-M PRO                 | [fe8f4ead98](https://linux-hardware.org/?probe=fe8f4ead98) | May 14, 2020 |
| ASUSTek    | P8H61-M LX R2.0             | [c815568345](https://linux-hardware.org/?probe=c815568345) | May 14, 2020 |
| ASUSTek    | F2A85-M PRO                 | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Gigabyte   | F2A88XM-D3H                 | [fc58b96f3e](https://linux-hardware.org/?probe=fc58b96f3e) | May 01, 2020 |
| Gigabyte   | B450M S2H                   | [0fe3c99d58](https://linux-hardware.org/?probe=0fe3c99d58) | Apr 30, 2020 |
| MSI        | G41TM-P33                   | [d1078cd496](https://linux-hardware.org/?probe=d1078cd496) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [8397339175](https://linux-hardware.org/?probe=8397339175) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [8140f69046](https://linux-hardware.org/?probe=8140f69046) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [24b18bdc0f](https://linux-hardware.org/?probe=24b18bdc0f) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [0ce02733c1](https://linux-hardware.org/?probe=0ce02733c1) | Apr 29, 2020 |
| Gigabyte   | B450M S2H                   | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| MSI        | G41TM-P33                   | [3512230c03](https://linux-hardware.org/?probe=3512230c03) | Apr 28, 2020 |
| MSI        | G41TM-P33                   | [a648a57d33](https://linux-hardware.org/?probe=a648a57d33) | Apr 28, 2020 |
| Gigabyte   | Z270XP-SLI-CF               | [20f18f18b8](https://linux-hardware.org/?probe=20f18f18b8) | Apr 27, 2020 |
| Dell       | 097YXY A00                  | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| MSI        | G41TM-P33                   | [5e14d58ed9](https://linux-hardware.org/?probe=5e14d58ed9) | Apr 22, 2020 |
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
| HP         | 1495                        | [d367e6dcf0](https://linux-hardware.org/?probe=d367e6dcf0) | Feb 16, 2020 |
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
| Ubuntu 20.04                 | 49       | 21.59%  |
| Ubuntu 18.04                 | 24       | 10.57%  |
| OpenMandriva 4.2             | 14       | 6.17%   |
| ROSA R11                     | 9        | 3.96%   |
| Ubuntu 19.04                 | 8        | 3.52%   |
| OpenMandriva 4.3             | 7        | 3.08%   |
| ROSA R11.1                   | 6        | 2.64%   |
| Ubuntu 20.10                 | 5        | 2.2%    |
| Manjaro                      | 5        | 2.2%    |
| Ubuntu 16.04                 | 4        | 1.76%   |
| Pop!_OS 20.04                | 4        | 1.76%   |
| Linux Mint 19.3              | 4        | 1.76%   |
| Kubuntu 20.04                | 4        | 1.76%   |
| Ubuntu 19.10                 | 3        | 1.32%   |
| ROSA R8.1                    | 3        | 1.32%   |
| ROSA R8                      | 3        | 1.32%   |
| ROSA R10                     | 3        | 1.32%   |
| Pop!_OS 21.10                | 3        | 1.32%   |
| Linux Mint 20.2              | 3        | 1.32%   |
| Linux Mint 20.1              | 3        | 1.32%   |
| ArcoLinux Rolling            | 3        | 1.32%   |
| Xubuntu 20.04                | 2        | 0.88%   |
| Xubuntu 18.04                | 2        | 0.88%   |
| Ubuntu 21.10                 | 2        | 0.88%   |
| Ubuntu 21.04                 | 2        | 0.88%   |
| Rocky Linux 8.5              | 2        | 0.88%   |
| Pop!_OS 21.04                | 2        | 0.88%   |
| KDE neon 20.04               | 2        | 0.88%   |
| Fedora 35                    | 2        | 0.88%   |
| Fedora 33                    | 2        | 0.88%   |
| Debian 11                    | 2        | 0.88%   |
| Arch Rolling                 | 2        | 0.88%   |
| Arch                         | 2        | 0.88%   |
| Zorin 16                     | 1        | 0.44%   |
| Zorin 15                     | 1        | 0.44%   |
| Xubuntu 20.10                | 1        | 0.44%   |
| Xubuntu 19.04                | 1        | 0.44%   |
| Ubuntu MATE 18.04            | 1        | 0.44%   |
| Ubuntu Budgie 20.04          | 1        | 0.44%   |
| ROSA R9                      | 1        | 0.44%   |
| ROSA 12.1                    | 1        | 0.44%   |
| Rocky Linux 8.4              | 1        | 0.44%   |
| Pop!_OS 22.04                | 1        | 0.44%   |
| openSUSE Tumbleweed-20211111 | 1        | 0.44%   |
| openSUSE Tumbleweed-20210929 | 1        | 0.44%   |
| openSUSE Tumbleweed-20210605 | 1        | 0.44%   |
| openSUSE Tumbleweed-20210521 | 1        | 0.44%   |
| openSUSE Tumbleweed-20210420 | 1        | 0.44%   |
| openSUSE 20210508            | 1        | 0.44%   |
| openSUSE 20200422            | 1        | 0.44%   |
| Manjaro 21.1.4               | 1        | 0.44%   |
| Manjaro 21.0.5               | 1        | 0.44%   |
| Manjaro 20.1                 | 1        | 0.44%   |
| Manjaro 18.0.4               | 1        | 0.44%   |
| Linux Mint 20                | 1        | 0.44%   |
| Linux Mint 19.2              | 1        | 0.44%   |
| Kubuntu 21.10                | 1        | 0.44%   |
| Kubuntu 20.10                | 1        | 0.44%   |
| Gentoo 2.6                   | 1        | 0.44%   |
| Fedora 34                    | 1        | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 94       | 44.76%  |
| OpenMandriva  | 21       | 10%     |
| ROSA          | 20       | 9.52%   |
| Pop!_OS       | 10       | 4.76%   |
| Manjaro       | 9        | 4.29%   |
| Linux Mint    | 9        | 4.29%   |
| Xubuntu       | 6        | 2.86%   |
| Kubuntu       | 6        | 2.86%   |
| Fedora        | 6        | 2.86%   |
| Debian        | 5        | 2.38%   |
| Arch          | 4        | 1.9%    |
| Rocky Linux   | 3        | 1.43%   |
| openSUSE      | 3        | 1.43%   |
| ArcoLinux     | 3        | 1.43%   |
| Zorin         | 2        | 0.95%   |
| KDE neon      | 2        | 0.95%   |
| Ubuntu MATE   | 1        | 0.48%   |
| Ubuntu Budgie | 1        | 0.48%   |
| Gentoo        | 1        | 0.48%   |
| Endless       | 1        | 0.48%   |
| Devuan        | 1        | 0.48%   |
| CentOS        | 1        | 0.48%   |
| BlackPanther  | 1        | 0.48%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 14       | 5.56%   |
| 5.4.0-42-generic                    | 13       | 5.16%   |
| 5.16.7-desktop-1omv4003             | 7        | 2.78%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6        | 2.38%   |
| 5.4.0-48-generic                    | 5        | 1.98%   |
| 5.4.0-52-generic                    | 4        | 1.59%   |
| 5.11.0-37-generic                   | 4        | 1.59%   |
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
| 5.4.0-66-generic                    | 2        | 0.79%   |
| 5.4.0-45-generic                    | 2        | 0.79%   |
| 5.4.0-37-generic                    | 2        | 0.79%   |
| 5.4.0-26-generic                    | 2        | 0.79%   |
| 5.3.0-40-generic                    | 2        | 0.79%   |
| 5.3.0-28-generic                    | 2        | 0.79%   |
| 5.16.19-76051619-generic            | 2        | 0.79%   |
| 5.14.10-300.fc35.x86_64             | 2        | 0.79%   |
| 5.13.0-7620-generic                 | 2        | 0.79%   |
| 5.11.0-40-generic                   | 2        | 0.79%   |
| 5.11.0-38-generic                   | 2        | 0.79%   |
| 5.11.0-27-generic                   | 2        | 0.79%   |
| 5.11.0-25-generic                   | 2        | 0.79%   |
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

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 49       | 21.4%   |
| 4.15.0  | 25       | 10.92%  |
| 5.8.0   | 20       | 8.73%   |
| 5.10.14 | 14       | 6.11%   |
| 5.11.0  | 13       | 5.68%   |
| 5.0.0   | 13       | 5.68%   |
| 5.3.0   | 10       | 4.37%   |
| 5.13.0  | 8        | 3.49%   |
| 5.16.7  | 7        | 3.06%   |
| 4.18.0  | 5        | 2.18%   |
| 4.9.60  | 3        | 1.31%   |
| 5.9.16  | 2        | 0.87%   |
| 5.16.19 | 2        | 0.87%   |
| 5.14.10 | 2        | 0.87%   |
| 5.12.0  | 2        | 0.87%   |
| 5.10.0  | 2        | 0.87%   |
| 4.19.0  | 2        | 0.87%   |
| 4.1.38  | 2        | 0.87%   |
| 4.1.34  | 2        | 0.87%   |
| 5.9.9   | 1        | 0.44%   |
| 5.9.8   | 1        | 0.44%   |
| 5.9.14  | 1        | 0.44%   |
| 5.9.1   | 1        | 0.44%   |
| 5.8.5   | 1        | 0.44%   |
| 5.8.18  | 1        | 0.44%   |
| 5.7.16  | 1        | 0.44%   |
| 5.6.4   | 1        | 0.44%   |
| 5.5.0   | 1        | 0.44%   |
| 5.4.32  | 1        | 0.44%   |
| 5.4.19  | 1        | 0.44%   |
| 5.17.1  | 1        | 0.44%   |
| 5.16.11 | 1        | 0.44%   |
| 5.15.5  | 1        | 0.44%   |
| 5.15.32 | 1        | 0.44%   |
| 5.15.28 | 1        | 0.44%   |
| 5.15.11 | 1        | 0.44%   |
| 5.14.6  | 1        | 0.44%   |
| 5.14.16 | 1        | 0.44%   |
| 5.14.14 | 1        | 0.44%   |
| 5.13.16 | 1        | 0.44%   |
| 5.12.9  | 1        | 0.44%   |
| 5.12.8  | 1        | 0.44%   |
| 5.12.3  | 1        | 0.44%   |
| 5.11.15 | 1        | 0.44%   |
| 5.10.74 | 1        | 0.44%   |
| 5.10.68 | 1        | 0.44%   |
| 5.10.5  | 1        | 0.44%   |
| 5.10.43 | 1        | 0.44%   |
| 5.10.42 | 1        | 0.44%   |
| 5.10.36 | 1        | 0.44%   |
| 5.10.34 | 1        | 0.44%   |
| 4.9.9   | 1        | 0.44%   |
| 4.9.20  | 1        | 0.44%   |
| 4.9.155 | 1        | 0.44%   |
| 4.7.6   | 1        | 0.44%   |
| 4.4.0   | 1        | 0.44%   |
| 4.19.93 | 1        | 0.44%   |
| 4.19.88 | 1        | 0.44%   |
| 4.19.66 | 1        | 0.44%   |
| 4.19.45 | 1        | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 51       | 22.87%  |
| 4.15    | 25       | 11.21%  |
| 5.10    | 23       | 10.31%  |
| 5.8     | 22       | 9.87%   |
| 5.11    | 14       | 6.28%   |
| 5.0     | 13       | 5.83%   |
| 5.3     | 10       | 4.48%   |
| 5.16    | 10       | 4.48%   |
| 5.13    | 9        | 4.04%   |
| 5.9     | 6        | 2.69%   |
| 4.9     | 6        | 2.69%   |
| 4.18    | 6        | 2.69%   |
| 4.19    | 5        | 2.24%   |
| 5.15    | 4        | 1.79%   |
| 5.14    | 4        | 1.79%   |
| 5.12    | 4        | 1.79%   |
| 4.1     | 4        | 1.79%   |
| 5.7     | 1        | 0.45%   |
| 5.6     | 1        | 0.45%   |
| 5.5     | 1        | 0.45%   |
| 5.17    | 1        | 0.45%   |
| 4.7     | 1        | 0.45%   |
| 4.4     | 1        | 0.45%   |
| 3.10    | 1        | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 203      | 99.02%  |
| i686   | 2        | 0.98%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 86       | 40%     |
| KDE5       | 41       | 19.07%  |
| Unknown    | 35       | 16.28%  |
| KDE4       | 17       | 7.91%   |
| XFCE       | 9        | 4.19%   |
| X-Cinnamon | 7        | 3.26%   |
| KDE        | 7        | 3.26%   |
| Unity      | 4        | 1.86%   |
| MATE       | 4        | 1.86%   |
| i3         | 2        | 0.93%   |
| Cinnamon   | 2        | 0.93%   |
| Budgie     | 1        | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 173      | 83.57%  |
| Unknown | 20       | 9.66%   |
| Wayland | 8        | 3.86%   |
| Tty     | 6        | 2.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 107      | 50.95%  |
| SDDM    | 37       | 17.62%  |
| GDM     | 26       | 12.38%  |
| KDM     | 17       | 8.1%    |
| GDM3    | 11       | 5.24%   |
| TDM     | 8        | 3.81%   |
| LightDM | 3        | 1.43%   |
| XDM     | 1        | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_IL      | 70       | 33.65%  |
| en_US      | 62       | 29.81%  |
| Unknown    | 41       | 19.71%  |
| ru_RU      | 13       | 6.25%   |
| he_IL      | 13       | 6.25%   |
| C          | 4        | 1.92%   |
| fr_FR      | 2        | 0.96%   |
| POSIX      | 1        | 0.48%   |
| en_US.UTF8 | 1        | 0.48%   |
| C.UTF8     | 1        | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 126      | 60.58%  |
| EFI  | 82       | 39.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 159      | 75.71%  |
| Overlay | 23       | 10.95%  |
| Btrfs   | 12       | 5.71%   |
| Unknown | 9        | 4.29%   |
| Xfs     | 4        | 1.9%    |
| Zfs     | 1        | 0.48%   |
| Tmpfs   | 1        | 0.48%   |
| F2fs    | 1        | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 113      | 54.59%  |
| GPT     | 57       | 27.54%  |
| MBR     | 37       | 17.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 81.25%  |
| Yes       | 39       | 18.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 64.59%  |
| Yes       | 74       | 35.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 67       | 32.84%  |
| Gigabyte Technology | 66       | 32.35%  |
| Dell                | 17       | 8.33%   |
| Lenovo              | 11       | 5.39%   |
| MSI                 | 10       | 4.9%    |
| ASRock              | 10       | 4.9%    |
| Hewlett-Packard     | 8        | 3.92%   |
| Pegatron            | 2        | 0.98%   |
| Intel               | 2        | 0.98%   |
| Foxconn             | 2        | 0.98%   |
| Unknown             | 2        | 0.98%   |
| Supermicro          | 1        | 0.49%   |
| Shuttle             | 1        | 0.49%   |
| HARDKERNEL          | 1        | 0.49%   |
| Biostar             | 1        | 0.49%   |
| AZW                 | 1        | 0.49%   |
| AMI                 | 1        | 0.49%   |
| Alienware           | 1        | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 9        | 4.41%   |
| MSI MS-7592                            | 3        | 1.47%   |
| Gigabyte H61M-S1                       | 3        | 1.47%   |
| ASUS P8H61-M LX R2.0                   | 3        | 1.47%   |
| ASUS H110M-A/M.2                       | 3        | 1.47%   |
| Gigabyte Z390 GAMING X                 | 2        | 0.98%   |
| Gigabyte X570 AORUS ULTRA              | 2        | 0.98%   |
| Gigabyte P55-UD3L                      | 2        | 0.98%   |
| Gigabyte H61M-S2PV                     | 2        | 0.98%   |
| Gigabyte H55M-D2H                      | 2        | 0.98%   |
| Gigabyte B460HD3                       | 2        | 0.98%   |
| Dell OptiPlex 755                      | 2        | 0.98%   |
| Dell OptiPlex 7050                     | 2        | 0.98%   |
| ASUS TUF GAMING B550-PLUS              | 2        | 0.98%   |
| ASUS ROG STRIX Z390-E GAMING           | 2        | 0.98%   |
| ASUS PRIME Z490-P                      | 2        | 0.98%   |
| ASUS PRIME X470-PRO                    | 2        | 0.98%   |
| ASUS PRIME H310M-E R2.0                | 2        | 0.98%   |
| ASUS PRIME B560M-K                     | 2        | 0.98%   |
| Unknown                                | 2        | 0.98%   |
| Supermicro X9DAi                       | 1        | 0.49%   |
| Shuttle SH87R                          | 1        | 0.49%   |
| Pegatron Pro 3010 Small Form Factor PC | 1        | 0.49%   |
| Pegatron NC890AA-ABA a6803w            | 1        | 0.49%   |
| MSI MS-7B86                            | 1        | 0.49%   |
| MSI MS-7B79                            | 1        | 0.49%   |
| MSI MS-7982                            | 1        | 0.49%   |
| MSI MS-7978                            | 1        | 0.49%   |
| MSI MS-7816                            | 1        | 0.49%   |
| MSI MS-7788                            | 1        | 0.49%   |
| MSI Elite 7100 Microtower PC           | 1        | 0.49%   |
| Lenovo V530-15ICR 11BH0032IV           | 1        | 0.49%   |
| Lenovo V520-15IKL 10NKS05400           | 1        | 0.49%   |
| Lenovo V520-15IKL 10NK003KIV           | 1        | 0.49%   |
| Lenovo V520-15IKL 10NK001XIV           | 1        | 0.49%   |
| Lenovo ThinkCentre M93p 10A7S02D00     | 1        | 0.49%   |
| Lenovo ThinkCentre M91p 4524B96        | 1        | 0.49%   |
| Lenovo ThinkCentre M91p 4518NR8        | 1        | 0.49%   |
| Lenovo ThinkCentre M81 5049W15         | 1        | 0.49%   |
| Lenovo ThinkCentre M81 5049PA4         | 1        | 0.49%   |
| Lenovo ThinkCentre Edge72 3484BTG      | 1        | 0.49%   |
| Lenovo ThinkCentre A58 751581G         | 1        | 0.49%   |
| Intel DP55WB AAE64798-205              | 1        | 0.49%   |
| Intel DG43RK AAE78175-403              | 1        | 0.49%   |
| HP Z620 Workstation                    | 1        | 0.49%   |
| HP ProDesk 600 G3 SFF                  | 1        | 0.49%   |
| HP Compaq Pro 6300 MT                  | 1        | 0.49%   |
| HP Compaq Elite 8300 MT                | 1        | 0.49%   |
| HP Compaq 8200 Elite SFF PC            | 1        | 0.49%   |
| HP Compaq 6200 Pro MT PC               | 1        | 0.49%   |
| HP 300-1xx                             | 1        | 0.49%   |
| HP 280 G1 MT                           | 1        | 0.49%   |
| HARDKERNEL ODROID-H2                   | 1        | 0.49%   |
| Gigabyte Z97X-Gaming 5                 | 1        | 0.49%   |
| Gigabyte Z97-HD3                       | 1        | 0.49%   |
| Gigabyte Z97-D3H                       | 1        | 0.49%   |
| Gigabyte Z87MX-D3H                     | 1        | 0.49%   |
| Gigabyte Z490M                         | 1        | 0.49%   |
| Gigabyte Z390 UD                       | 1        | 0.49%   |
| Gigabyte Z370 AORUS Gaming K3          | 1        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 21       | 10.29%  |
| Dell OptiPlex          | 10       | 4.9%    |
| ASUS All               | 9        | 4.41%   |
| Lenovo ThinkCentre     | 7        | 3.43%   |
| ASUS ROG               | 7        | 3.43%   |
| ASUS TUF               | 6        | 2.94%   |
| HP Compaq              | 4        | 1.96%   |
| Dell Vostro            | 4        | 1.96%   |
| ASUS H110M-A           | 4        | 1.96%   |
| MSI MS-7592            | 3        | 1.47%   |
| Lenovo V520-15IKL      | 3        | 1.47%   |
| Gigabyte Z390          | 3        | 1.47%   |
| Gigabyte H61M-S1       | 3        | 1.47%   |
| ASUS P8H61-M           | 3        | 1.47%   |
| Gigabyte X570          | 2        | 0.98%   |
| Gigabyte P55-UD3L      | 2        | 0.98%   |
| Gigabyte H61M-S2PV     | 2        | 0.98%   |
| Gigabyte H55M-D2H      | 2        | 0.98%   |
| Gigabyte B560M         | 2        | 0.98%   |
| Gigabyte B460HD3       | 2        | 0.98%   |
| Gigabyte B450M         | 2        | 0.98%   |
| Dell Precision         | 2        | 0.98%   |
| Unknown                | 2        | 0.98%   |
| Supermicro X9DAi       | 1        | 0.49%   |
| Shuttle SH87R          | 1        | 0.49%   |
| Pegatron Pro           | 1        | 0.49%   |
| Pegatron NC890AA-ABA   | 1        | 0.49%   |
| MSI MS-7B86            | 1        | 0.49%   |
| MSI MS-7B79            | 1        | 0.49%   |
| MSI MS-7982            | 1        | 0.49%   |
| MSI MS-7978            | 1        | 0.49%   |
| MSI MS-7816            | 1        | 0.49%   |
| MSI MS-7788            | 1        | 0.49%   |
| MSI Elite              | 1        | 0.49%   |
| Lenovo V530-15ICR      | 1        | 0.49%   |
| Intel DP55WB           | 1        | 0.49%   |
| Intel DG43RK           | 1        | 0.49%   |
| HP Z620                | 1        | 0.49%   |
| HP ProDesk             | 1        | 0.49%   |
| HP 300-1xx             | 1        | 0.49%   |
| HP 280                 | 1        | 0.49%   |
| HARDKERNEL ODROID-H2   | 1        | 0.49%   |
| Gigabyte Z97X-Gaming   | 1        | 0.49%   |
| Gigabyte Z97-HD3       | 1        | 0.49%   |
| Gigabyte Z97-D3H       | 1        | 0.49%   |
| Gigabyte Z87MX-D3H     | 1        | 0.49%   |
| Gigabyte Z490M         | 1        | 0.49%   |
| Gigabyte Z370          | 1        | 0.49%   |
| Gigabyte Z270X-UD5     | 1        | 0.49%   |
| Gigabyte Z270-HD3P     | 1        | 0.49%   |
| Gigabyte Z170XP-SLI    | 1        | 0.49%   |
| Gigabyte Z170MX-Gaming | 1        | 0.49%   |
| Gigabyte X58A-UD3R     | 1        | 0.49%   |
| Gigabyte X58-USB3      | 1        | 0.49%   |
| Gigabyte X299          | 1        | 0.49%   |
| Gigabyte Q87M-D2H      | 1        | 0.49%   |
| Gigabyte J1800N-D2H    | 1        | 0.49%   |
| Gigabyte H97M-HD3      | 1        | 0.49%   |
| Gigabyte H97M-D3H      | 1        | 0.49%   |
| Gigabyte H97-HD3       | 1        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 25       | 12.25%  |
| 2013 | 19       | 9.31%   |
| 2012 | 19       | 9.31%   |
| 2014 | 18       | 8.82%   |
| 2010 | 18       | 8.82%   |
| 2020 | 16       | 7.84%   |
| 2019 | 13       | 6.37%   |
| 2017 | 13       | 6.37%   |
| 2021 | 11       | 5.39%   |
| 2016 | 11       | 5.39%   |
| 2015 | 11       | 5.39%   |
| 2011 | 11       | 5.39%   |
| 2009 | 11       | 5.39%   |
| 2007 | 4        | 1.96%   |
| 2008 | 3        | 1.47%   |
| 2006 | 1        | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 204      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 203      | 99.51%  |
| Enabled  | 1        | 0.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 204      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 50       | 24.04%  |
| 8.01-16.0   | 41       | 19.71%  |
| 32.01-64.0  | 37       | 17.79%  |
| 3.01-4.0    | 33       | 15.87%  |
| 4.01-8.0    | 26       | 12.5%   |
| 64.01-256.0 | 10       | 4.81%   |
| 1.01-2.0    | 7        | 3.37%   |
| 24.01-32.0  | 3        | 1.44%   |
| 2.01-3.0    | 1        | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 82       | 35.81%  |
| 2.01-3.0   | 44       | 19.21%  |
| 4.01-8.0   | 31       | 13.54%  |
| 3.01-4.0   | 26       | 11.35%  |
| 0.51-1.0   | 21       | 9.17%   |
| 8.01-16.0  | 19       | 8.3%    |
| 0.01-0.5   | 4        | 1.75%   |
| 16.01-24.0 | 2        | 0.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 85       | 40.28%  |
| 2      | 62       | 29.38%  |
| 3      | 37       | 17.54%  |
| 4      | 11       | 5.21%   |
| 5      | 8        | 3.79%   |
| 6      | 3        | 1.42%   |
| 7      | 2        | 0.95%   |
| 10     | 1        | 0.47%   |
| 8      | 1        | 0.47%   |
| 0      | 1        | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 127      | 61.35%  |
| Yes       | 80       | 38.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 202      | 99.02%  |
| No        | 2        | 0.98%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 60.98%  |
| Yes       | 80       | 39.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 76.7%   |
| Yes       | 48       | 23.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Israel  | 204      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Tel Aviv              | 101      | 46.76%  |
| Haifa                 | 19       | 8.8%    |
| Ramat Gan             | 15       | 6.94%   |
| Jerusalem             | 10       | 4.63%   |
| Rishon LeZiyyon       | 6        | 2.78%   |
| Herzliya              | 6        | 2.78%   |
| Beersheba             | 6        | 2.78%   |
| Rehovot               | 4        | 1.85%   |
| Petaбє– Tiqwa     | 4        | 1.85%   |
| Petaáº– Tiqwa     | 4        | 1.85%   |
| Nahariya              | 4        | 1.85%   |
| Hod HaSharon          | 4        | 1.85%   |
| Givatayim             | 4        | 1.85%   |
| Netanya               | 3        | 1.39%   |
| Raanana               | 2        | 0.93%   |
| Ofakim                | 2        | 0.93%   |
| Kiryat Ono            | 2        | 0.93%   |
| Holon                 | 2        | 0.93%   |
| Yoqne'am 'Illit       | 1        | 0.46%   |
| Yehud                 | 1        | 0.46%   |
| Sharona               | 1        | 0.46%   |
| Rosh HaAyin           | 1        | 0.46%   |
| Ramat HaSharon        | 1        | 0.46%   |
| Qiryat Moбє•qin   | 1        | 0.46%   |
| Qiryat Ata            | 1        | 0.46%   |
| Pardes Hanna Karkur   | 1        | 0.46%   |
| Or Yehuda             | 1        | 0.46%   |
| Nazerat 'Illit        | 1        | 0.46%   |
| Modiin Makkabbim Reut | 1        | 0.46%   |
| Migdal HaEmeq         | 1        | 0.46%   |
| Giv'at Hayyim Ihud    | 1        | 0.46%   |
| Elifelet              | 1        | 0.46%   |
| Be'er Ya'aqov         | 1        | 0.46%   |
| Azor                  | 1        | 0.46%   |
| Almagor               | 1        | 0.46%   |
| Unknown               | 1        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 87       | 158    | 23.45%  |
| Seagate                   | 48       | 83     | 12.94%  |
| Samsung Electronics       | 42       | 69     | 11.32%  |
| Hitachi                   | 33       | 57     | 8.89%   |
| SanDisk                   | 25       | 30     | 6.74%   |
| Kingston                  | 25       | 28     | 6.74%   |
| Toshiba                   | 21       | 29     | 5.66%   |
| Crucial                   | 12       | 24     | 3.23%   |
| Transcend                 | 10       | 13     | 2.7%    |
| Intel                     | 9        | 12     | 2.43%   |
| HGST                      | 8        | 10     | 2.16%   |
| Corsair                   | 8        | 12     | 2.16%   |
| XPG                       | 5        | 12     | 1.35%   |
| Micron Technology         | 4        | 5      | 1.08%   |
| A-DATA Technology         | 4        | 5      | 1.08%   |
| SK Hynix                  | 3        | 3      | 0.81%   |
| Silicon Motion            | 3        | 3      | 0.81%   |
| Phison                    | 3        | 4      | 0.81%   |
| SPCC                      | 2        | 2      | 0.54%   |
| OCZ                       | 2        | 2      | 0.54%   |
| Netac                     | 2        | 2      | 0.54%   |
| Micron/Crucial Technology | 2        | 2      | 0.54%   |
| USB3.0                    | 1        | 1      | 0.27%   |
| Unknown                   | 1        | 2      | 0.27%   |
| TPH01204000GB             | 1        | 1      | 0.27%   |
| StoreJet                  | 1        | 1      | 0.27%   |
| PLEXTOR                   | 1        | 1      | 0.27%   |
| Patriot                   | 1        | 1      | 0.27%   |
| OCZ-VERTEX3               | 1        | 1      | 0.27%   |
| NGFF                      | 1        | 1      | 0.27%   |
| LS600                     | 1        | 1      | 0.27%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.27%   |
| KingSpec                  | 1        | 1      | 0.27%   |
| IBM/Hitachi               | 1        | 1      | 0.27%   |
| Apple                     | 1        | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| SanDisk SSD PLUS 240GB            | 9        | 2.12%   |
| Hitachi HDS721050CLA362 500GB     | 9        | 2.12%   |
| Kingston SA400S37240G 240GB SSD   | 7        | 1.65%   |
| Toshiba DT01ACA100 1TB            | 6        | 1.41%   |
| Samsung SSD 860 EVO 500GB         | 6        | 1.41%   |
| WDC WD20PURX-64P6ZY0 2TB          | 5        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB   | 5        | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB    | 5        | 1.18%   |
| Samsung NVMe SSD Drive 500GB      | 5        | 1.18%   |
| HGST HTS545050A7E680 500GB        | 5        | 1.18%   |
| WDC WD10EZEX-08WN4A0 1TB          | 4        | 0.94%   |
| Samsung SSD 850 EVO 250GB         | 4        | 0.94%   |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.71%   |
| WDC WD10EARS-00Y5B1 1TB           | 3        | 0.71%   |
| WDC WD10EADS-00L5B1 1TB           | 3        | 0.71%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 3        | 0.71%   |
| Toshiba DT01ACA050 500GB          | 3        | 0.71%   |
| Seagate ST2000DM001-1ER164 2TB    | 3        | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB    | 3        | 0.71%   |
| Samsung SSD 970 EVO Plus 500GB    | 3        | 0.71%   |
| Samsung SSD 860 QVO 1TB           | 3        | 0.71%   |
| Samsung NVMe SSD Drive 1TB        | 3        | 0.71%   |
| Kingston SV300S37A120G 120GB SSD  | 3        | 0.71%   |
| Hitachi HDS721050CLA360 500GB     | 3        | 0.71%   |
| XPG NVMe SSD Drive 1024GB         | 2        | 0.47%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD  | 2        | 0.47%   |
| WDC WDS100T3X0C-00SJG0 1TB        | 2        | 0.47%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 0.47%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 2        | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB       | 2        | 0.47%   |
| WDC WD3200AAKS-00L9A0 320GB       | 2        | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 2        | 0.47%   |
| WDC WD20EZAZ-00GGJB0 2TB          | 2        | 0.47%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 0.47%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 2        | 0.47%   |
| WDC WD10EZRX-00A8LB0 1TB          | 2        | 0.47%   |
| Transcend TS128GSSD370 128GB      | 2        | 0.47%   |
| Transcend TS128GSSD230S 128GB     | 2        | 0.47%   |
| Toshiba DT01ACA200 2TB            | 2        | 0.47%   |
| Seagate ST500DM002-1SB10A 500GB   | 2        | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB    | 2        | 0.47%   |
| Seagate ST3500418AS 500GB         | 2        | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB    | 2        | 0.47%   |
| Seagate Expansion Desk 3TB        | 2        | 0.47%   |
| SanDisk SSD PLUS 480GB            | 2        | 0.47%   |
| SanDisk Extreme SSD 1TB           | 2        | 0.47%   |
| Samsung SSD 860 EVO 1TB           | 2        | 0.47%   |
| Samsung SSD 850 EVO 500GB         | 2        | 0.47%   |
| Samsung NVMe SSD Drive 250GB      | 2        | 0.47%   |
| Samsung HD103SJ 1TB               | 2        | 0.47%   |
| Netac SSD 240GB                   | 2        | 0.47%   |
| Micron/Crucial NVMe SSD Drive 1TB | 2        | 0.47%   |
| Kingston SUV400S37240G 240GB SSD  | 2        | 0.47%   |
| Kingston SUV400S37120G 120GB SSD  | 2        | 0.47%   |
| Kingston SA400S37120G 120GB SSD   | 2        | 0.47%   |
| Intel SSDPEKNW512G8 512GB         | 2        | 0.47%   |
| Hitachi HTS547550A9E384 500GB     | 2        | 0.47%   |
| Hitachi HDS728080PLA380 80GB      | 2        | 0.47%   |
| Hitachi HDP725050GLA360 500GB     | 2        | 0.47%   |
| Crucial CT120BX500SSD1 120GB      | 2        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 82       | 146    | 41%     |
| Seagate             | 48       | 82     | 24%     |
| Hitachi             | 33       | 57     | 16.5%   |
| Toshiba             | 19       | 27     | 9.5%    |
| HGST                | 8        | 10     | 4%      |
| Samsung Electronics | 6        | 12     | 3%      |
| USB3.0              | 1        | 1      | 0.5%    |
| TPH01204000GB       | 1        | 1      | 0.5%    |
| IBM/Hitachi         | 1        | 1      | 0.5%    |
| Apple               | 1        | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 37     | 18.03%  |
| Kingston            | 22       | 25     | 18.03%  |
| SanDisk             | 21       | 26     | 17.21%  |
| Transcend           | 10       | 13     | 8.2%    |
| Intel               | 7        | 8      | 5.74%   |
| Crucial             | 7        | 18     | 5.74%   |
| Corsair             | 7        | 10     | 5.74%   |
| WDC                 | 5        | 5      | 4.1%    |
| Micron Technology   | 4        | 5      | 3.28%   |
| A-DATA Technology   | 4        | 5      | 3.28%   |
| OCZ                 | 2        | 2      | 1.64%   |
| Netac               | 2        | 2      | 1.64%   |
| SPCC                | 1        | 1      | 0.82%   |
| Seagate             | 1        | 1      | 0.82%   |
| PLEXTOR             | 1        | 1      | 0.82%   |
| Patriot             | 1        | 1      | 0.82%   |
| OCZ-VERTEX3         | 1        | 1      | 0.82%   |
| NGFF                | 1        | 1      | 0.82%   |
| LS600               | 1        | 1      | 0.82%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.82%   |
| KingSpec            | 1        | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 151      | 338    | 48.87%  |
| SSD     | 105      | 165    | 33.98%  |
| NVMe    | 50       | 72     | 16.18%  |
| Unknown | 2        | 3      | 0.65%   |
| MMC     | 1        | 1      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 182      | 492    | 74.9%   |
| NVMe | 50       | 72     | 20.58%  |
| SAS  | 10       | 14     | 4.12%   |
| MMC  | 1        | 1      | 0.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 142      | 282    | 52.59%  |
| 0.51-1.0   | 68       | 107    | 25.19%  |
| 1.01-2.0   | 37       | 57     | 13.7%   |
| 2.01-3.0   | 11       | 14     | 4.07%   |
| 3.01-4.0   | 8        | 31     | 2.96%   |
| 4.01-10.0  | 3        | 7      | 1.11%   |
| 10.01-20.0 | 1        | 5      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 43       | 20.28%  |
| 101-250        | 39       | 18.4%   |
| 501-1000       | 33       | 15.57%  |
| 1001-2000      | 24       | 11.32%  |
| More than 3000 | 18       | 8.49%   |
| 2001-3000      | 17       | 8.02%   |
| 1-20           | 16       | 7.55%   |
| 21-50          | 11       | 5.19%   |
| 51-100         | 6        | 2.83%   |
| Unknown        | 5        | 2.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 92       | 42.01%  |
| 21-50          | 31       | 14.16%  |
| 101-250        | 21       | 9.59%   |
| 1001-2000      | 19       | 8.68%   |
| 251-500        | 16       | 7.31%   |
| 51-100         | 11       | 5.02%   |
| 501-1000       | 10       | 4.57%   |
| More than 3000 | 7        | 3.2%    |
| 2001-3000      | 7        | 3.2%    |
| Unknown        | 5        | 2.28%   |

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
| Detected | 118      | 379    | 52.44%  |
| Works    | 77       | 155    | 34.22%  |
| Malfunc  | 28       | 41     | 12.44%  |
| Failed   | 2        | 4      | 0.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 168      | 60.87%  |
| AMD                          | 34       | 12.32%  |
| Samsung Electronics          | 18       | 6.52%   |
| JMicron Technology           | 9        | 3.26%   |
| Sandisk                      | 8        | 2.9%    |
| Micron/Crucial Technology    | 7        | 2.54%   |
| Phison Electronics           | 5        | 1.81%   |
| ADATA Technology             | 5        | 1.81%   |
| ASMedia Technology           | 4        | 1.45%   |
| SK Hynix                     | 3        | 1.09%   |
| Silicon Motion               | 3        | 1.09%   |
| Nvidia                       | 3        | 1.09%   |
| Marvell Technology Group     | 3        | 1.09%   |
| Kingston Technology Company  | 3        | 1.09%   |
| Toshiba America Info Systems | 2        | 0.72%   |
| VIA Technologies             | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 7.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 19       | 5.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 5.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 4.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 4.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 3.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 3.59%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 2.99%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.99%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 2.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.4%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 1.8%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 1.8%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 1.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.2%    |
| Micron/Crucial Non-Volatile memory controller                                           | 4        | 1.2%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.2%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 1.2%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.9%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.9%    |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.9%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.6%    |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.6%    |
| JMicron JMB368 IDE controller                                                           | 2        | 0.6%    |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.6%    |
| Intel SSD 660P Series                                                                   | 2        | 0.6%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.6%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.6%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.6%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.6%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.6%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1        | 0.3%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.3%    |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 0.3%    |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.3%    |
| SK Hynix BC511                                                                          | 1        | 0.3%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.3%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.3%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.3%    |
| Sandisk WD Black NVMe SSD                                                               | 1        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 155      | 58.05%  |
| NVMe | 51       | 19.1%   |
| IDE  | 47       | 17.6%   |
| RAID | 12       | 4.49%   |
| SAS  | 2        | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 168      | 82.35%  |
| AMD    | 36       | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 3.86%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7        | 3.38%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4        | 1.93%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 1.93%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 1.93%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 1.93%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4        | 1.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.93%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.93%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.93%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.93%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.93%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 1.45%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.45%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.45%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.45%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 3        | 1.45%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 1.45%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 1.45%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.45%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.45%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 2        | 0.97%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 0.97%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 0.97%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 0.97%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.97%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.97%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.97%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 0.97%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.97%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 0.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.97%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.97%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 0.97%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.97%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.97%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.97%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2        | 0.97%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.97%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 0.97%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.97%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 0.97%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 0.97%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 0.97%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.97%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 0.48%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.48%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.48%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1        | 0.48%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 0.48%   |
| Intel Xeon CPU E3-1265L v4 @ 2.30GHz        | 1        | 0.48%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1        | 0.48%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1        | 0.48%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.48%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.48%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.48%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 50       | 24.39%  |
| Intel Core i5           | 45       | 21.95%  |
| Intel Core i3           | 23       | 11.22%  |
| Intel Pentium Dual-Core | 11       | 5.37%   |
| AMD Ryzen 5             | 11       | 5.37%   |
| Intel Pentium           | 8        | 3.9%    |
| Intel Xeon              | 7        | 3.41%   |
| Other                   | 6        | 2.93%   |
| Intel Core 2 Duo        | 6        | 2.93%   |
| AMD Ryzen 9             | 6        | 2.93%   |
| AMD Ryzen 7             | 5        | 2.44%   |
| Intel Celeron           | 3        | 1.46%   |
| AMD A8                  | 3        | 1.46%   |
| Intel Pentium Dual      | 2        | 0.98%   |
| Intel Genuine           | 2        | 0.98%   |
| Intel Atom              | 2        | 0.98%   |
| AMD FX                  | 2        | 0.98%   |
| Intel Pentium Gold      | 1        | 0.49%   |
| Intel Pentium 4         | 1        | 0.49%   |
| Intel Core i9           | 1        | 0.49%   |
| Intel Core 2 Quad       | 1        | 0.49%   |
| AMD Ryzen Threadripper  | 1        | 0.49%   |
| AMD Ryzen 3 PRO         | 1        | 0.49%   |
| AMD Ryzen 3             | 1        | 0.49%   |
| AMD Phenom II X4        | 1        | 0.49%   |
| AMD Phenom              | 1        | 0.49%   |
| AMD Athlon II X3        | 1        | 0.49%   |
| AMD Athlon 64 X2        | 1        | 0.49%   |
| AMD A6                  | 1        | 0.49%   |
| AMD A10                 | 1        | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 86       | 41.95%  |
| 2      | 56       | 27.32%  |
| 6      | 27       | 13.17%  |
| 8      | 20       | 9.76%   |
| 12     | 8        | 3.9%    |
| 16     | 3        | 1.46%   |
| 3      | 2        | 0.98%   |
| 1      | 2        | 0.98%   |
| 10     | 1        | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 202      | 99.02%  |
| 2      | 2        | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 117      | 57.07%  |
| 1      | 88       | 42.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 203      | 99.51%  |
| Unknown        | 1        | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 17.84%  |
| 0x306c3    | 22       | 10.33%  |
| 0x1067a    | 17       | 7.98%   |
| 0x906e9    | 13       | 6.1%    |
| 0x206a7    | 13       | 6.1%    |
| 0x306a9    | 12       | 5.63%   |
| 0x906ea    | 10       | 4.69%   |
| 0x506e3    | 9        | 4.23%   |
| 0xa0655    | 5        | 2.35%   |
| 0xa0653    | 5        | 2.35%   |
| 0x106e5    | 5        | 2.35%   |
| 0x08108109 | 5        | 2.35%   |
| 0xa0671    | 4        | 1.88%   |
| 0x906ed    | 4        | 1.88%   |
| 0x306e4    | 4        | 1.88%   |
| 0x08701021 | 4        | 1.88%   |
| 0x08701013 | 3        | 1.41%   |
| 0x0800820d | 3        | 1.41%   |
| 0x6fd      | 2        | 0.94%   |
| 0x20652    | 2        | 0.94%   |
| 0x10676    | 2        | 0.94%   |
| 0x06003106 | 2        | 0.94%   |
| 0x06001119 | 2        | 0.94%   |
| 0x010000c8 | 2        | 0.94%   |
| 0x906ec    | 1        | 0.47%   |
| 0x906eb    | 1        | 0.47%   |
| 0x906c0    | 1        | 0.47%   |
| 0x90672    | 1        | 0.47%   |
| 0x806ea    | 1        | 0.47%   |
| 0x706a1    | 1        | 0.47%   |
| 0x506e0    | 1        | 0.47%   |
| 0x406c4    | 1        | 0.47%   |
| 0x40671    | 1        | 0.47%   |
| 0x306d4    | 1        | 0.47%   |
| 0x30673    | 1        | 0.47%   |
| 0x206c2    | 1        | 0.47%   |
| 0x106c2    | 1        | 0.47%   |
| 0x106a5    | 1        | 0.47%   |
| 0x0a50000c | 1        | 0.47%   |
| 0x0a201016 | 1        | 0.47%   |
| 0x0a201009 | 1        | 0.47%   |
| 0x0810100b | 1        | 0.47%   |
| 0x08008206 | 1        | 0.47%   |
| 0x08001129 | 1        | 0.47%   |
| 0x08001105 | 1        | 0.47%   |
| 0x06003104 | 1        | 0.47%   |
| 0x06000852 | 1        | 0.47%   |
| 0x06000629 | 1        | 0.47%   |
| 0x01000083 | 1        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 37       | 18.05%  |
| Haswell       | 29       | 14.15%  |
| Penryn        | 19       | 9.27%   |
| IvyBridge     | 17       | 8.29%   |
| SandyBridge   | 14       | 6.83%   |
| CometLake     | 13       | 6.34%   |
| Skylake       | 12       | 5.85%   |
| Zen 2         | 9        | 4.39%   |
| Zen+          | 8        | 3.9%    |
| Nehalem       | 8        | 3.9%    |
| Zen           | 5        | 2.44%   |
| Westmere      | 4        | 1.95%   |
| Zen 3         | 3        | 1.46%   |
| Steamroller   | 3        | 1.46%   |
| Piledriver    | 3        | 1.46%   |
| K10           | 3        | 1.46%   |
| Icelake       | 3        | 1.46%   |
| Unknown       | 3        | 1.46%   |
| Silvermont    | 2        | 0.98%   |
| Core          | 2        | 0.98%   |
| Broadwell     | 2        | 0.98%   |
| Tremont       | 1        | 0.49%   |
| NetBurst      | 1        | 0.49%   |
| K8 Hammer     | 1        | 0.49%   |
| Goldmont plus | 1        | 0.49%   |
| Bulldozer     | 1        | 0.49%   |
| Bonnell       | 1        | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 100      | 43.29%  |
| Intel  | 93       | 40.26%  |
| AMD    | 38       | 16.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 9.05%   |
| Intel HD Graphics 630                                                       | 10       | 4.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 4.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 4.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 3.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 3.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 3.02%   |
| Intel HD Graphics 530                                                       | 6        | 2.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.59%   |
| Nvidia GP107GL [Quadro P400]                                                | 5        | 2.16%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 2.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 2.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 2.16%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.29%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.29%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.29%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 1.29%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.86%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.86%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.86%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.86%   |
| Nvidia GT216 [GeForce GT 220]                                               | 2        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.86%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.86%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.86%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.86%   |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 0.86%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 0.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.86%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.86%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 0.86%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 0.86%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 0.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.43%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.43%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.43%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.43%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.43%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.43%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.43%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.43%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 0.43%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.43%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.43%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.43%   |
| Nvidia GK210GL [Tesla K80]                                                  | 1        | 0.43%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.43%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.43%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.43%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 85       | 41.06%  |
| 1 x Intel      | 72       | 34.78%  |
| 1 x AMD        | 32       | 15.46%  |
| Intel + Nvidia | 12       | 5.8%    |
| AMD + Nvidia   | 3        | 1.45%   |
| Intel + AMD    | 2        | 0.97%   |
| 2 x AMD        | 1        | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 135      | 63.98%  |
| Proprietary | 64       | 30.33%  |
| Unknown     | 12       | 5.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 95       | 44.6%   |
| 1.01-2.0   | 40       | 18.78%  |
| 0.51-1.0   | 23       | 10.8%   |
| 3.01-4.0   | 16       | 7.51%   |
| 7.01-8.0   | 15       | 7.04%   |
| 0.01-0.5   | 12       | 5.63%   |
| 5.01-6.0   | 5        | 2.35%   |
| 2.01-3.0   | 3        | 1.41%   |
| 8.01-16.0  | 3        | 1.41%   |
| 16.01-24.0 | 1        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 53       | 25.12%  |
| Dell                    | 36       | 17.06%  |
| Philips                 | 19       | 9%      |
| Goldstar                | 14       | 6.64%   |
| AOC                     | 11       | 5.21%   |
| Ancor Communications    | 8        | 3.79%   |
| ViewSonic               | 7        | 3.32%   |
| ASUSTek Computer        | 6        | 2.84%   |
| Lenovo                  | 5        | 2.37%   |
| Hewlett-Packard         | 5        | 2.37%   |
| BenQ                    | 4        | 1.9%    |
| Unknown                 | 3        | 1.42%   |
| Sanyo                   | 3        | 1.42%   |
| Lenovo Group Limited    | 3        | 1.42%   |
| Acer                    | 3        | 1.42%   |
| Panasonic               | 2        | 0.95%   |
| NEX                     | 2        | 0.95%   |
| LG Electronics          | 2        | 0.95%   |
| HKC                     | 2        | 0.95%   |
| Eizo                    | 2        | 0.95%   |
| Unknown                 | 2        | 0.95%   |
| ___                     | 1        | 0.47%   |
| VIE                     | 1        | 0.47%   |
| Unknown (AAA)           | 1        | 0.47%   |
| Toshiba                 | 1        | 0.47%   |
| SSD                     | 1        | 0.47%   |
| Sharp                   | 1        | 0.47%   |
| Sceptre Tech            | 1        | 0.47%   |
| Plain Tree Systems      | 1        | 0.47%   |
| Pioneer                 | 1        | 0.47%   |
| NXG                     | 1        | 0.47%   |
| MStar                   | 1        | 0.47%   |
| JRY                     | 1        | 0.47%   |
| Iiyama                  | 1        | 0.47%   |
| Hitachi                 | 1        | 0.47%   |
| HannStar Display        | 1        | 0.47%   |
| Fujitsu Siemens         | 1        | 0.47%   |
| CVT                     | 1        | 0.47%   |
| Chi Mei Optoelectronics | 1        | 0.47%   |
| AUS                     | 1        | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4        | 1.8%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 4        | 1.8%    |
| Philips LCD Monitor PHLC052 1920x1080 480x270mm 21.7-inch             | 4        | 1.8%    |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 4        | 1.8%    |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 4        | 1.8%    |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch  | 3        | 1.35%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 3        | 1.35%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 600x340mm 27.2-inch               | 3        | 1.35%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 3        | 1.35%   |
| Sanyo LCD MONITOR SAN07BE 1280x1024 350x270mm 17.4-inch               | 2        | 0.9%    |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch  | 2        | 0.9%    |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch  | 2        | 0.9%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 2        | 0.9%    |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch     | 2        | 0.9%    |
| Samsung Electronics LCD Monitor SMBX2450 1920x1080                    | 2        | 0.9%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch     | 2        | 0.9%    |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                    | 2        | 0.9%    |
| Lenovo Group Limited LCD Monitor L24q-10                              | 2        | 0.9%    |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 2        | 0.9%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.9%    |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                     | 2        | 0.9%    |
| ASUSTek Computer VG248 AUS24AB 1920x1080 531x299mm 24.0-inch          | 2        | 0.9%    |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2        | 0.9%    |
| Unknown                                                               | 2        | 0.9%    |
| ___ LCDTV16 ___0101 1360x768                                          | 1        | 0.45%   |
| ViewSonic VX2770 SERIES VSC3A2C 1920x1080 597x336mm 27.0-inch         | 1        | 0.45%   |
| ViewSonic VX2237 SERIES VSC2C24 1680x1050 474x296mm 22.0-inch         | 1        | 0.45%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch             | 1        | 0.45%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 0.45%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                 | 1        | 0.45%   |
| ViewSonic PJ VSC2D36 3840x2160                                        | 1        | 0.45%   |
| ViewSonic LCD Monitor VSCC132 1920x1080 600x340mm 27.2-inch           | 1        | 0.45%   |
| ViewSonic LCD Monitor VA2719 Series                                   | 1        | 0.45%   |
| VIE M2487HVB VIE1919 1920x1080 520x310mm 23.8-inch                    | 1        | 0.45%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                    | 1        | 0.45%   |
| Unknown LCD Monitor SAMSUNG 3520x1080                                 | 1        | 0.45%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.45%   |
| Unknown (AAA) smart tv AAA0001 1920x1080 1600x900mm 72.3-inch         | 1        | 0.45%   |
| Toshiba LCD Monitor TV                                                | 1        | 0.45%   |
| SSD HDTV SSD0001 1360x768 708x398mm 32.0-inch                         | 1        | 0.45%   |
| Sharp HDMI SHP4176 1920x1080 1210x680mm 54.6-inch                     | 1        | 0.45%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                | 1        | 0.45%   |
| Sanyo LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch               | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0571 1920x1080 510x287mm 23.0-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM043F 1920x1200 518x324mm 24.1-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0379 1680x1050 433x271mm 20.1-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 459x296mm 21.5-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM01B9 1280x1024 338x270mm 17.0-inch  | 1        | 0.45%   |
| Samsung Electronics SMS19A200 SAM0830 1440x900 408x255mm 18.9-inch    | 1        | 0.45%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1        | 0.45%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1        | 0.45%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch     | 1        | 0.45%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1        | 0.45%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 0.45%   |
| Samsung Electronics S27E391 SAM0C16 1920x1080 598x336mm 27.0-inch     | 1        | 0.45%   |
| Samsung Electronics S27E332 SAM0F60 1920x1080 598x336mm 27.0-inch     | 1        | 0.45%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch     | 1        | 0.45%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 1        | 0.45%   |
| Samsung Electronics S24E650 SAM0CC2 1920x1200 518x324mm 24.1-inch     | 1        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 120      | 58.25%  |
| 1680x1050 (WSXGA+) | 15       | 7.28%   |
| 1280x1024 (SXGA)   | 11       | 5.34%   |
| 2560x1440 (QHD)    | 10       | 4.85%   |
| 1920x1200 (WUXGA)  | 10       | 4.85%   |
| 3840x2160 (4K)     | 9        | 4.37%   |
| Unknown            | 7        | 3.4%    |
| 1440x900 (WXGA+)   | 5        | 2.43%   |
| 1600x900 (HD+)     | 3        | 1.46%   |
| 3840x1080          | 2        | 0.97%   |
| 2560x1080          | 2        | 0.97%   |
| 1920x540           | 2        | 0.97%   |
| 1366x768 (WXGA)    | 2        | 0.97%   |
| 5360x1440          | 1        | 0.49%   |
| 5120x1440          | 1        | 0.49%   |
| 4480x1440          | 1        | 0.49%   |
| 3520x1080          | 1        | 0.49%   |
| 3440x1440          | 1        | 0.49%   |
| 2560x1600          | 1        | 0.49%   |
| 1360x768           | 1        | 0.49%   |
| 1280x768           | 1        | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 42       | 20.39%  |
| 24      | 37       | 17.96%  |
| 23      | 27       | 13.11%  |
| Unknown | 23       | 11.17%  |
| 27      | 22       | 10.68%  |
| 22      | 14       | 6.8%    |
| 17      | 7        | 3.4%    |
| 19      | 6        | 2.91%   |
| 20      | 5        | 2.43%   |
| 72      | 3        | 1.46%   |
| 18      | 3        | 1.46%   |
| 84      | 2        | 0.97%   |
| 54      | 2        | 0.97%   |
| 33      | 2        | 0.97%   |
| 32      | 2        | 0.97%   |
| 31      | 2        | 0.97%   |
| 60      | 1        | 0.49%   |
| 52      | 1        | 0.49%   |
| 49      | 1        | 0.49%   |
| 48      | 1        | 0.49%   |
| 34      | 1        | 0.49%   |
| 29      | 1        | 0.49%   |
| 16      | 1        | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 82       | 40.8%   |
| 401-500     | 64       | 31.84%  |
| Unknown     | 23       | 11.44%  |
| 301-350     | 7        | 3.48%   |
| 1001-1500   | 6        | 2.99%   |
| 701-800     | 5        | 2.49%   |
| 601-700     | 5        | 2.49%   |
| 1501-2000   | 5        | 2.49%   |
| 351-400     | 4        | 1.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 126      | 63.96%  |
| 16/10   | 36       | 18.27%  |
| Unknown | 22       | 11.17%  |
| 5/4     | 7        | 3.55%   |
| 4/3     | 4        | 2.03%   |
| 21/9    | 1        | 0.51%   |
| 1.96    | 1        | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 93       | 46.04%  |
| 151-200        | 23       | 11.39%  |
| Unknown        | 23       | 11.39%  |
| 301-350        | 22       | 10.89%  |
| 251-300        | 14       | 6.93%   |
| More than 1000 | 10       | 4.95%   |
| 351-500        | 8        | 3.96%   |
| 141-150        | 7        | 3.47%   |
| 131-140        | 1        | 0.5%    |
| 501-1000       | 1        | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 110      | 55.84%  |
| 101-120 | 48       | 24.37%  |
| Unknown | 23       | 11.68%  |
| 1-50    | 11       | 5.58%   |
| 121-160 | 4        | 2.03%   |
| 161-240 | 1        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 159      | 76.81%  |
| 2     | 33       | 15.94%  |
| 0     | 14       | 6.76%   |
| 4     | 1        | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 130      | 44.98%  |
| Intel                           | 83       | 28.72%  |
| Qualcomm Atheros                | 21       | 7.27%   |
| Ralink Technology               | 11       | 3.81%   |
| TP-Link                         | 6        | 2.08%   |
| Edimax Technology               | 6        | 2.08%   |
| Ralink                          | 3        | 1.04%   |
| ASIX Electronics                | 3        | 1.04%   |
| Xiaomi                          | 2        | 0.69%   |
| Qualcomm Atheros Communications | 2        | 0.69%   |
| Nvidia                          | 2        | 0.69%   |
| Marvell Technology Group        | 2        | 0.69%   |
| D-Link                          | 2        | 0.69%   |
| Broadcom Limited                | 2        | 0.69%   |
| Broadcom                        | 2        | 0.69%   |
| U.S. Robotics                   | 1        | 0.35%   |
| Texas Instruments               | 1        | 0.35%   |
| STMicroelectronics              | 1        | 0.35%   |
| ROCCAT                          | 1        | 0.35%   |
| Microsoft                       | 1        | 0.35%   |
| Mellanox Technologies           | 1        | 0.35%   |
| MediaTek                        | 1        | 0.35%   |
| Huawei Technologies             | 1        | 0.35%   |
| GDMicroelectronics              | 1        | 0.35%   |
| Davicom Semiconductor           | 1        | 0.35%   |
| BUFFALO                         | 1        | 0.35%   |
| Accton Technology               | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 106      | 33.13%  |
| Intel Ethernet Connection (2) I219-V                                                          | 13       | 4.06%   |
| Intel I211 Gigabit Network Connection                                                         | 12       | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 11       | 3.44%   |
| Intel Ethernet Connection (7) I219-V                                                          | 8        | 2.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 7        | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 7        | 2.19%   |
| Intel Wi-Fi 6 AX200                                                                           | 7        | 2.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 4        | 1.25%   |
| Realtek 802.11ac NIC                                                                          | 4        | 1.25%   |
| Intel Ethernet Connection I217-LM                                                             | 4        | 1.25%   |
| Intel Ethernet Connection (14) I219-V                                                         | 4        | 1.25%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 3        | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3        | 0.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 0.94%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 3        | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3        | 0.94%   |
| Intel Wireless-AC 9260                                                                        | 3        | 0.94%   |
| Intel Ethernet Connection I217-V                                                              | 3        | 0.94%   |
| Intel Ethernet Connection (5) I219-LM                                                         | 3        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 3        | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                                                 | 3        | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 0.63%   |
| TP-Link Archer T4U ver.3                                                                      | 2        | 0.63%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2        | 0.63%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 0.63%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 2        | 0.63%   |
| Nvidia MCP61 Ethernet                                                                         | 2        | 0.63%   |
| Intel Wireless 3165                                                                           | 2        | 0.63%   |
| Intel Ethernet Connection (12) I219-V                                                         | 2        | 0.63%   |
| Intel Ethernet Connection (11) I219-V                                                         | 2        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2        | 0.63%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 0.63%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2        | 0.63%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 2        | 0.63%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                      | 2        | 0.63%   |
| Edimax AC600 USB                                                                              | 2        | 0.63%   |
| U.S. Robotics USR5637 56K Faxmodem                                                            | 1        | 0.31%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.31%   |
| Texas Instruments CC2531 ZigBee                                                               | 1        | 0.31%   |
| STMicroelectronics Virtual COM Port                                                           | 1        | 0.31%   |
| ROCCAT OSA Express Network card                                                               | 1        | 0.31%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.31%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.31%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.31%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.31%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1        | 0.31%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.31%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 22       | 25%     |
| Intel                           | 21       | 23.86%  |
| Ralink Technology               | 11       | 12.5%   |
| Qualcomm Atheros                | 10       | 11.36%  |
| TP-Link                         | 6        | 6.82%   |
| Edimax Technology               | 6        | 6.82%   |
| Ralink                          | 3        | 3.41%   |
| Qualcomm Atheros Communications | 2        | 2.27%   |
| D-Link                          | 2        | 2.27%   |
| Broadcom                        | 2        | 2.27%   |
| Microsoft                       | 1        | 1.14%   |
| MediaTek                        | 1        | 1.14%   |
| BUFFALO                         | 1        | 1.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 7        | 7.87%   |
| Intel Wi-Fi 6 AX200                                                                           | 7        | 7.87%   |
| Realtek 802.11ac NIC                                                                          | 4        | 4.49%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 3        | 3.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3        | 3.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 3.37%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 3.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 3.37%   |
| Intel Wireless-AC 9260                                                                        | 3        | 3.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 3        | 3.37%   |
| TP-Link Archer T4U ver.3                                                                      | 2        | 2.25%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 2.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 2.25%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2        | 2.25%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 2.25%   |
| Intel Wireless 3165                                                                           | 2        | 2.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 2.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2        | 2.25%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 2        | 2.25%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                      | 2        | 2.25%   |
| Edimax AC600 USB                                                                              | 2        | 2.25%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.12%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.12%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 1.12%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.12%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.12%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.12%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.12%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 1.12%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.12%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 1.12%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.12%   |
| Ralink RT2600 802.11 MIMO                                                                     | 1        | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1        | 1.12%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.12%   |
| MediaTek WiFi                                                                                 | 1        | 1.12%   |
| Intel Wireless 3160                                                                           | 1        | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1        | 1.12%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]                          | 1        | 1.12%   |
| D-Link DWA-160 Xtreme N Dual Band USB Adapter(rev.C1)                                         | 1        | 1.12%   |
| BUFFALO Sony UWA-BR100 802.11abgn Wireless Adapter [Atheros AR7010+AR9280]                    | 1        | 1.12%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1        | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 120      | 54.79%  |
| Intel                    | 73       | 33.33%  |
| Qualcomm Atheros         | 11       | 5.02%   |
| ASIX Electronics         | 3        | 1.37%   |
| Xiaomi                   | 2        | 0.91%   |
| Nvidia                   | 2        | 0.91%   |
| Marvell Technology Group | 2        | 0.91%   |
| Broadcom Limited         | 2        | 0.91%   |
| Mellanox Technologies    | 1        | 0.46%   |
| Huawei Technologies      | 1        | 0.46%   |
| Davicom Semiconductor    | 1        | 0.46%   |
| Accton Technology        | 1        | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106      | 46.9%   |
| Intel Ethernet Connection (2) I219-V                              | 13       | 5.75%   |
| Intel I211 Gigabit Network Connection                             | 12       | 5.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 4.87%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 3.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.77%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 1.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3        | 1.33%   |
| Intel Ethernet Connection I217-V                                  | 3        | 1.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 3        | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.88%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.88%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.88%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.88%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.88%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.44%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.44%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.44%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.44%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 0.44%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.44%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.44%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.44%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.44%   |
| Huawei E353/E3131                                                 | 1        | 0.44%   |
| Davicom ST268                                                     | 1        | 0.44%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.44%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1        | 0.44%   |
| Accton EN-1216 Ethernet Adapter                                   | 1        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 202      | 70.38%  |
| WiFi     | 80       | 27.87%  |
| Modem    | 4        | 1.39%   |
| Unknown  | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 172      | 75.11%  |
| WiFi     | 57       | 24.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 152      | 74.15%  |
| 2     | 43       | 20.98%  |
| 3     | 8        | 3.9%    |
| 0     | 2        | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 180      | 86.12%  |
| Yes  | 29       | 13.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 20       | 40.82%  |
| Intel                           | 19       | 38.78%  |
| Qualcomm Atheros Communications | 4        | 8.16%   |
| ASUSTek Computer                | 3        | 6.12%   |
| Realtek Semiconductor           | 1        | 2.04%   |
| IMC Networks                    | 1        | 2.04%   |
| Broadcom                        | 1        | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 40.82%  |
| Intel AX200 Bluetooth                               | 6        | 12.24%  |
| Intel Bluetooth wireless interface                  | 5        | 10.2%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 6.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 6.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4.08%   |
| ASUS Bluetooth Adapter                              | 2        | 4.08%   |
| Realtek Bluetooth Radio                             | 1        | 2.04%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2.04%   |
| IMC Networks Bluetooth Device                       | 1        | 2.04%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.04%   |
| ASUS BCM20702A0                                     | 1        | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 161      | 47.92%  |
| Nvidia               | 96       | 28.57%  |
| AMD                  | 50       | 14.88%  |
| C-Media Electronics  | 6        | 1.79%   |
| Creative Labs        | 5        | 1.49%   |
| Focusrite-Novation   | 3        | 0.89%   |
| Creative Technology  | 3        | 0.89%   |
| XMOS                 | 1        | 0.3%    |
| VIA Technologies     | 1        | 0.3%    |
| Texas Instruments    | 1        | 0.3%    |
| Razer USA            | 1        | 0.3%    |
| Microsoft            | 1        | 0.3%    |
| Meridian             | 1        | 0.3%    |
| Logitech             | 1        | 0.3%    |
| Kingston Technology  | 1        | 0.3%    |
| JMTek                | 1        | 0.3%    |
| iCreate Technologies | 1        | 0.3%    |
| GN Netcom            | 1        | 0.3%    |
| EGO SYStems          | 1        | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22       | 5.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19       | 5.01%   |
| Intel 200 Series PCH HD Audio                                              | 19       | 5.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18       | 4.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15       | 3.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14       | 3.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13       | 3.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 2.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 11       | 2.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 2.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 2.37%   |
| Nvidia High Definition Audio Controller                                    | 8        | 2.11%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 2.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 2.11%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 1.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 1.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 1.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 1.32%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.32%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.06%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.06%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1.06%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 1.06%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.06%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.79%   |
| Intel Audio device                                                         | 3        | 0.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.79%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.79%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 3        | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 0.79%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 0.53%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.53%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2        | 0.53%   |
| Intel Broadwell-U Audio Controller                                         | 2        | 0.53%   |
| C-Media Electronics Redragon Gaming Headset                                | 2        | 0.53%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 0.53%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 0.53%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1        | 0.26%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 0.26%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.26%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1        | 0.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.26%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.26%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.26%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 21.49%  |
| Unknown             | 20       | 16.53%  |
| Crucial             | 16       | 13.22%  |
| Corsair             | 12       | 9.92%   |
| G.Skill             | 11       | 9.09%   |
| SK Hynix            | 8        | 6.61%   |
| Samsung Electronics | 8        | 6.61%   |
| Micron Technology   | 6        | 4.96%   |
| Team                | 3        | 2.48%   |
| Ramaxel Technology  | 3        | 2.48%   |
| Transcend           | 2        | 1.65%   |
| GeIL                | 2        | 1.65%   |
| Unknown (09D5)      | 1        | 0.83%   |
| Patriot             | 1        | 0.83%   |
| KETECH              | 1        | 0.83%   |
| A-DATA Technology   | 1        | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s    | 3        | 2.27%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 2        | 1.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2        | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 2        | 1.52%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 2        | 1.52%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 2        | 1.52%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s        | 2        | 1.52%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s       | 2        | 1.52%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 2        | 1.52%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s      | 2        | 1.52%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s       | 2        | 1.52%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s         | 2        | 1.52%   |
| Crucial RAM CT16G4DFD832A.C16FP 16384MB DIMM DDR4 3200MT/s | 2        | 1.52%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1        | 0.76%   |
| Unknown RAM Module 8192MB DIMM 800MT/s                     | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                   | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM 667MT/s                        | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                   | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                     | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1        | 0.76%   |
| Unknown RAM Module 1GB DIMM 800MT/s                        | 1        | 0.76%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                     | 1        | 0.76%   |
| Unknown (09D5) RAM Module 8GB DIMM DDR4 2400MT/s           | 1        | 0.76%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s           | 1        | 0.76%   |
| Transcend RAM JM2666HLE-16G 16GB DIMM DDR4 2667MT/s        | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s         | 1        | 0.76%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                 | 1        | 0.76%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                 | 1        | 0.76%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s      | 1        | 0.76%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1        | 0.76%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1        | 0.76%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s    | 1        | 0.76%   |
| SK Hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s       | 1        | 0.76%   |
| SK Hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s      | 1        | 0.76%   |
| SK Hynix RAM HMA451U6AFR8N-TF 4096MB DIMM DDR4 2133MT/s    | 1        | 0.76%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 0.76%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s        | 1        | 0.76%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s       | 1        | 0.76%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s        | 1        | 0.76%   |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s        | 1        | 0.76%   |
| Samsung RAM ARM Ltd:R00MM0M006 2048MB DIMM DDR2 800MT/s    | 1        | 0.76%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s    | 1        | 0.76%   |
| Ramaxel RAM RMUA5110KE68H9F-2400 4GB DIMM DDR4 2400MT/s    | 1        | 0.76%   |
| Ramaxel RAM RMR5030KD68F9F1600 4GB DIMM DDR3 1600MT/s      | 1        | 0.76%   |
| Patriot RAM 1600EL Series 4GB DIMM DDR3 1600MT/s           | 1        | 0.76%   |
| Micron RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 0.76%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s         | 1        | 0.76%   |
| Micron RAM 16HTF25664AY-800J1 2GB DIMM DDR2 800MT/s        | 1        | 0.76%   |
| Micron RAM 16HTF25664AY-1GAE1 2048MB DIMM DDR2 667MT/s     | 1        | 0.76%   |
| Kingston RAM XVTW4H-MIE 32GB DIMM DDR4 3200MT/s            | 1        | 0.76%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s     | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 60       | 55.05%  |
| DDR3    | 26       | 23.85%  |
| Unknown | 12       | 11.01%  |
| DDR2    | 6        | 5.5%    |
| SDRAM   | 4        | 3.67%   |
| DDR     | 1        | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 107      | 98.17%  |
| SODIMM | 2        | 1.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 28.81%  |
| 4096  | 34       | 28.81%  |
| 16384 | 24       | 20.34%  |
| 2048  | 18       | 15.25%  |
| 32768 | 4        | 3.39%   |
| 1024  | 4        | 3.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 15.83%  |
| 3200    | 14       | 11.67%  |
| 800     | 11       | 9.17%   |
| 2400    | 10       | 8.33%   |
| 2133    | 10       | 8.33%   |
| 1333    | 10       | 8.33%   |
| 3600    | 6        | 5%      |
| 2667    | 6        | 5%      |
| 3466    | 3        | 2.5%    |
| 2933    | 3        | 2.5%    |
| 1867    | 3        | 2.5%    |
| 667     | 3        | 2.5%    |
| Unknown | 3        | 2.5%    |
| 3151    | 2        | 1.67%   |
| 2000    | 2        | 1.67%   |
| 1866    | 2        | 1.67%   |
| 1400    | 2        | 1.67%   |
| 49926   | 1        | 0.83%   |
| 4400    | 1        | 0.83%   |
| 3800    | 1        | 0.83%   |
| 3733    | 1        | 0.83%   |
| 3400    | 1        | 0.83%   |
| 3066    | 1        | 0.83%   |
| 3000    | 1        | 0.83%   |
| 2800    | 1        | 0.83%   |
| 2134    | 1        | 0.83%   |
| 1800    | 1        | 0.83%   |
| 400     | 1        | 0.83%   |

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

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

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
| Generalplus GENERAL WEBCAM                          | 3        | 5.88%   |
| Logitech Webcam C310                                | 2        | 3.92%   |
| Logitech C922 Pro Stream Webcam                     | 2        | 3.92%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                  | 1        | 1.96%   |
| Realtek Web Camera                                  | 1        | 1.96%   |
| Quanta Astro HD Camera                              | 1        | 1.96%   |
| Microsoft MicrosoftÃ‚ LifeCam Cinema             | 1        | 1.96%   |
| Microsoft MicrosoftÂ LifeCam Studio                | 1        | 1.96%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 1.96%   |
| Microdia USB 2.0 Camera                             | 1        | 1.96%   |
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
| Generalplus USB WEBCAM                              | 1        | 1.96%   |
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
| 0     | 178      | 85.17%  |
| 1     | 26       | 12.44%  |
| 2     | 5        | 2.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 17       | 47.22%  |
| Net/wireless             | 12       | 33.33%  |
| Communication controller | 4        | 11.11%  |
| Camera                   | 3        | 8.33%   |

