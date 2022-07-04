Garuda Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

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

Total: 153

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | PRIME B550-PLUS AC-HES      | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASRock    | Z87M Extreme4               | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte  | Z77X-UD3H                   | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI       | B550-A PRO                  | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| MSI       | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| T-bao     | MINI PC V1.0                | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock    | Z87M Extreme4               | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| ASRock    | X470 Taichi                 | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Lenovo    | 3716 SDK0T76463 WIN 3422... | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo    | 3716 SDK0T76463 WIN 3422... | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Gigabyte  | B450 I AORUS PRO WIFI-CF    | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| ASRock    | X470 Taichi                 | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| Dell      | 0WR7PY A01                  | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| ASRock    | B550M Pro4                  | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| ASRock    | X99X Killer                 | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek   | Z97-P                       | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| ASRock    | X99X Killer                 | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASRock    | X470 Taichi                 | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek   | P8B75-M                     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HP        | 8433 11                     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| MSI       | B450-A PRO MAX              | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte  | B550 GAMING X V2            | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| ASUSTek   | A68HM-PLUS                  | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| ASRock    | X470 Taichi                 | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| MSI       | MPG B550 GAMING CARBON W... | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| MSI       | MAG B550 TOMAHAWK           | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock    | B450 Gaming K4              | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| ASUSTek   | TUF Gaming X570-PLUS        | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek   | A68HM-PLUS                  | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek   | ProArt X570-CREATOR WIFI    | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek   | M4A89TD PRO USB3            | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| ASRock    | X470 Taichi                 | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| HP        | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek   | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP        | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek   | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock    | B450M Pro4                  | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| Lenovo    | 31900058 STD                | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| ASRock    | X470 Taichi                 | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Gigabyte  | MFLP3AP-00\2.x              | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| ASRock    | X470 Taichi                 | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte  | B85-HD3                     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| ASRock    | 970M Pro3                   | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek   | ROG Maximus X CODE          | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI       | Z270 GAMING M5              | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| ASUSTek   | TUF Gaming X570-PLUS        | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Pegatron  | 2AD5                        | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| Gigabyte  | B460M DS3H                  | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Gigabyte  | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASUSTek   | TUF Gaming X570-PLUS        | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Gigabyte  | X570 AORUS ELITE WIFI       | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| ASRock    | H77M-ITX                    | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock    | B450M Pro4                  | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo    | ThinkStation S20 4105O1U    | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| ASUSTek   | TUF Gaming X570-PLUS        | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| Acer      | Aspire TC-895 V:1.0         | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek   | H87M-E                      | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek   | H87M-E                      | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo    | ThinkStation S20 4105O1U    | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo    | ThinkStation S20 4105O1U    | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| ASRock    | X470 Taichi                 | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASUSTek   | Rampage IV EXTREME          | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| ASUSTek   | TUF Gaming X570-PLUS        | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASRock    | X470 Taichi                 | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| ASUSTek   | P8B75-M                     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| MSI       | Z77A-G43                    | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI       | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI       | B450M-A PRO MAX             | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| ASRock    | X470 Taichi                 | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Fujitsu   | D3120-A1 S26361-D3120-A1    | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu   | D3120-A1 S26361-D3120-A1    | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek   | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| MSI       | H310M PRO-VDH PLUS          | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware | 0TYR0X A00                  | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock    | X399 Professional Gaming    | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Medion    | H110H4-EM2                  | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| ASRock    | X470 Taichi                 | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI       | Z97 MPOWER                  | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI       | Z97 MPOWER                  | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Gigabyte  | X470 AORUS ULTRA GAMING-... | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar   | H310MHP                     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI       | A320M-HDV R4.0              | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI       | A320M-HDV R4.0              | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI       | A320M-HDV R4.0              | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI       | A320M-HDV R4.0              | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| MSI       | X370 GAMING PRO CARBON      | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte  | B550I AORUS PRO AX          | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| ASUSTek   | ROG CROSSHAIR VII HERO      | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI       | B350M GAMING PRO            | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell      | 0D28YY A02                  | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| Gigabyte  | A320M-S2H-CF                | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP        | 844C                        | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP        | 844C                        | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| ASUSTek   | PRIME Z590-A                | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte  | P67A-UD3-B3                 | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| MSI       | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASRock    | AB350M-HDV                  | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock    | AB350M-HDV                  | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell      | 07KY25 A01                  | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Dell      | 07KY25 A01                  | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Gigabyte  | B450 AORUS M                | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte  | B450 AORUS M                | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| HP        | 2AF7                        | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP        | 2AF7                        | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte  | GA-MA790FXT-UD5P            | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| ASRock    | FM2A88X Extreme6+           | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Dell      | 0C2KJT A00                  | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek   | PRIME B360M-K               | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP        | 1825                        | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP        | 1825                        | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| ASRock    | X470 Master SLI             | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock    | X470 Master SLI             | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek   | ROG STRIX X570-E GAMING     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| ASUSTek   | PRIME H270-PLUS             | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo    | SHARKBAY 0B98401 PRO        | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| MSI       | X399 SLI PLUS               | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek   | CM5671                      | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| MSI       | B85-G43 GAMING              | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| ASRock    | G41M-VS3                    | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Pegatron  | 2AC2A                       | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron  | 2AC2A                       | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| ASUSTek   | PRIME Z370-P                | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| MSI       | Z390-A PRO                  | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP        | 8643 SMVB                   | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte  | B450 AORUS ELITE            | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI       | Z390-A PRO                  | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| MSI       | Z390-A PRO                  | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek   | M5A97 LE R2.0               | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Gigabyte  | B450 AORUS M                | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte  | B450 AORUS M                | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte  | X570 AORUS PRO WIFI         | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| HP        | 18E7                        | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte  | X570 AORUS PRO WIFI         | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte  | X570 AORUS PRO WIFI         | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI       | MPG B550 GAMING EDGE WIF... | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek   | PRIME X399-A                | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell      | 0R6JMP A00                  | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM       | Unknown                     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo    | ThinkCentre M91p 7033CG1    | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| ASUSTek   | Maximus VIII FORMULA        | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek   | Maximus VIII FORMULA        | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Garuda Linux Soaring | 52       | 49.06%  |
| Garuda Linux         | 49       | 46.23%  |
| Garuda Linux Rolling | 5        | 4.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Garuda Linux | 103      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.17.1-zen1-1-zen      | 6        | 4.96%   |
| 5.15.7-zen1-1-zen      | 4        | 3.31%   |
| 5.10.4-107-tkg-bmq     | 4        | 3.31%   |
| 5.9.1-zen2-1-zen       | 3        | 2.48%   |
| 5.18.1-zen1-1-zen      | 3        | 2.48%   |
| 5.16.4-zen1-1-zen      | 3        | 2.48%   |
| 5.15.2-zen1-1-zen      | 3        | 2.48%   |
| 5.15.13-zen1-1-zen     | 3        | 2.48%   |
| 5.11.16-zen1-1-zen     | 3        | 2.48%   |
| 5.9.11-zen2-1-zen      | 2        | 1.65%   |
| 5.9.10-zen1-1-zen      | 2        | 1.65%   |
| 5.8.14-zen1-1-zen      | 2        | 1.65%   |
| 5.16.8-zen1-1-zen      | 2        | 1.65%   |
| 5.16.11-zen1-1-zen     | 2        | 1.65%   |
| 5.16.10-zen1-1-zen     | 2        | 1.65%   |
| 5.16.0-zen1-1-zen      | 2        | 1.65%   |
| 5.15.12-zen1-1-zen     | 2        | 1.65%   |
| 5.15.10-zen1-1-zen     | 2        | 1.65%   |
| 5.13.9-zen1-1-zen      | 2        | 1.65%   |
| 5.13.12-zen1-1-zen     | 2        | 1.65%   |
| 5.12.4-zen1-2-zen      | 2        | 1.65%   |
| 5.10.8-112-tkg-bmq     | 2        | 1.65%   |
| 5.9.8-zen1-1-zen       | 1        | 0.83%   |
| 5.9.6-zen1-1-zen       | 1        | 0.83%   |
| 5.9.4-zen1-1-zen       | 1        | 0.83%   |
| 5.9.2-zen1-1-zen       | 1        | 0.83%   |
| 5.9.14-99-tkg-bmq      | 1        | 0.83%   |
| 5.8.5-zen1-1-zen       | 1        | 0.83%   |
| 5.8.10-zen1-1-zen      | 1        | 0.83%   |
| 5.8.0-xanmod1-1-xanmod | 1        | 0.83%   |
| 5.18.6-zen1-1-zen      | 1        | 0.83%   |
| 5.18.5-zen1-1-zen      | 1        | 0.83%   |
| 5.18.3-zen1-1-zen      | 1        | 0.83%   |
| 5.17.5-zen1-2-zen      | 1        | 0.83%   |
| 5.17.5-zen1-1-zen      | 1        | 0.83%   |
| 5.17.5-256-tkg-pds     | 1        | 0.83%   |
| 5.17.3-zen1-1-zen      | 1        | 0.83%   |
| 5.17.3-256-tkg-cfs     | 1        | 0.83%   |
| 5.17.1-249-tkg-pds     | 1        | 0.83%   |
| 5.17.0-249-tkg-pds     | 1        | 0.83%   |
| 5.16.5-zen1-1-zen      | 1        | 0.83%   |
| 5.16.5-243-tkg-pds     | 1        | 0.83%   |
| 5.16.2-zen1-1-zen      | 1        | 0.83%   |
| 5.16.2-238-tkg-pds     | 1        | 0.83%   |
| 5.16.15-zen1-1-zen     | 1        | 0.83%   |
| 5.16.14-zen1-1-zen     | 1        | 0.83%   |
| 5.15.6-zen2-1-zen      | 1        | 0.83%   |
| 5.15.5-zen1-1-zen      | 1        | 0.83%   |
| 5.15.5-222-tkg-pds     | 1        | 0.83%   |
| 5.15.35-1-lts          | 1        | 0.83%   |
| 5.14.5-zen1-1-zen      | 1        | 0.83%   |
| 5.14.15-zen1-1-zen     | 1        | 0.83%   |
| 5.14.14-zen1-1-zen     | 1        | 0.83%   |
| 5.14.12-zen1-1-zen     | 1        | 0.83%   |
| 5.14.12-207-tkg-cacule | 1        | 0.83%   |
| 5.14.11-206-tkg-pds    | 1        | 0.83%   |
| 5.13.8-zen1-1-zen      | 1        | 0.83%   |
| 5.13.19-204-tkg-muqss  | 1        | 0.83%   |
| 5.13.10-190-tkg-bmq    | 1        | 0.83%   |
| 5.12.7-zen1-1-zen      | 1        | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 7        | 5.79%   |
| 5.15.7  | 4        | 3.31%   |
| 5.10.4  | 4        | 3.31%   |
| 5.9.1   | 3        | 2.48%   |
| 5.18.1  | 3        | 2.48%   |
| 5.17.5  | 3        | 2.48%   |
| 5.16.4  | 3        | 2.48%   |
| 5.15.2  | 3        | 2.48%   |
| 5.15.13 | 3        | 2.48%   |
| 5.12.13 | 3        | 2.48%   |
| 5.11.16 | 3        | 2.48%   |
| 5.9.11  | 2        | 1.65%   |
| 5.9.10  | 2        | 1.65%   |
| 5.8.14  | 2        | 1.65%   |
| 5.17.3  | 2        | 1.65%   |
| 5.16.8  | 2        | 1.65%   |
| 5.16.5  | 2        | 1.65%   |
| 5.16.2  | 2        | 1.65%   |
| 5.16.11 | 2        | 1.65%   |
| 5.16.10 | 2        | 1.65%   |
| 5.16.0  | 2        | 1.65%   |
| 5.15.5  | 2        | 1.65%   |
| 5.15.12 | 2        | 1.65%   |
| 5.15.10 | 2        | 1.65%   |
| 5.14.12 | 2        | 1.65%   |
| 5.13.9  | 2        | 1.65%   |
| 5.13.12 | 2        | 1.65%   |
| 5.12.4  | 2        | 1.65%   |
| 5.12.12 | 2        | 1.65%   |
| 5.10.8  | 2        | 1.65%   |
| 5.9.8   | 1        | 0.83%   |
| 5.9.6   | 1        | 0.83%   |
| 5.9.4   | 1        | 0.83%   |
| 5.9.2   | 1        | 0.83%   |
| 5.9.14  | 1        | 0.83%   |
| 5.8.5   | 1        | 0.83%   |
| 5.8.10  | 1        | 0.83%   |
| 5.8.0   | 1        | 0.83%   |
| 5.18.6  | 1        | 0.83%   |
| 5.18.5  | 1        | 0.83%   |
| 5.18.3  | 1        | 0.83%   |
| 5.17.0  | 1        | 0.83%   |
| 5.16.15 | 1        | 0.83%   |
| 5.16.14 | 1        | 0.83%   |
| 5.15.6  | 1        | 0.83%   |
| 5.15.35 | 1        | 0.83%   |
| 5.14.5  | 1        | 0.83%   |
| 5.14.15 | 1        | 0.83%   |
| 5.14.14 | 1        | 0.83%   |
| 5.14.11 | 1        | 0.83%   |
| 5.13.8  | 1        | 0.83%   |
| 5.13.19 | 1        | 0.83%   |
| 5.13.10 | 1        | 0.83%   |
| 5.12.7  | 1        | 0.83%   |
| 5.12.3  | 1        | 0.83%   |
| 5.12.14 | 1        | 0.83%   |
| 5.12.10 | 1        | 0.83%   |
| 5.11.8  | 1        | 0.83%   |
| 5.11.6  | 1        | 0.83%   |
| 5.11.5  | 1        | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 18       | 15.79%  |
| 5.16    | 16       | 14.04%  |
| 5.10    | 16       | 14.04%  |
| 5.17    | 11       | 9.65%   |
| 5.12    | 10       | 8.77%   |
| 5.11    | 10       | 8.77%   |
| 5.9     | 9        | 7.89%   |
| 5.13    | 7        | 6.14%   |
| 5.18    | 6        | 5.26%   |
| 5.14    | 6        | 5.26%   |
| 5.8     | 5        | 4.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 103      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 66       | 62.86%  |
| KDE        | 19       | 18.1%   |
| GNOME      | 14       | 13.33%  |
| XFCE       | 1        | 0.95%   |
| X-Cinnamon | 1        | 0.95%   |
| LXQt       | 1        | 0.95%   |
| i3         | 1        | 0.95%   |
| Deepin     | 1        | 0.95%   |
| Unknown    | 1        | 0.95%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 98       | 95.15%  |
| Wayland | 3        | 2.91%   |
| Tty     | 1        | 0.97%   |
| Unknown | 1        | 0.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 47.57%  |
| SDDM    | 47       | 45.63%  |
| LightDM | 5        | 4.85%   |
| GDM     | 2        | 1.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 51       | 49.51%  |
| de_DE | 12       | 11.65%  |
| en_GB | 9        | 8.74%   |
| en_AU | 4        | 3.88%   |
| es_ES | 3        | 2.91%   |
| en_CA | 3        | 2.91%   |
| ru_RU | 2        | 1.94%   |
| pt_BR | 2        | 1.94%   |
| nl_NL | 2        | 1.94%   |
| it_IT | 2        | 1.94%   |
| fr_BE | 2        | 1.94%   |
| sv_SE | 1        | 0.97%   |
| sk_SK | 1        | 0.97%   |
| nb_NO | 1        | 0.97%   |
| iu_CA | 1        | 0.97%   |
| fr_FR | 1        | 0.97%   |
| es_VE | 1        | 0.97%   |
| es_AR | 1        | 0.97%   |
| en_ZA | 1        | 0.97%   |
| en_IN | 1        | 0.97%   |
| el_GR | 1        | 0.97%   |
| da_DK | 1        | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 58       | 56.31%  |
| BIOS | 45       | 43.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 101      | 98.06%  |
| Ext4  | 2        | 1.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 51       | 49.04%  |
| Unknown | 49       | 47.12%  |
| MBR     | 4        | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 80%     |
| Yes       | 21       | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 67.62%  |
| Yes       | 34       | 32.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 27       | 26.21%  |
| MSI                 | 18       | 17.48%  |
| Gigabyte Technology | 18       | 17.48%  |
| ASRock              | 12       | 11.65%  |
| Hewlett-Packard     | 7        | 6.8%    |
| Lenovo              | 6        | 5.83%   |
| Dell                | 6        | 5.83%   |
| Pegatron            | 2        | 1.94%   |
| T-bao               | 1        | 0.97%   |
| OEM                 | 1        | 0.97%   |
| Medion              | 1        | 0.97%   |
| Fujitsu             | 1        | 0.97%   |
| Biostar             | 1        | 0.97%   |
| Alienware           | 1        | 0.97%   |
| Acer                | 1        | 0.97%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS            | 3        | 2.91%   |
| MSI MS-7C91                          | 2        | 1.94%   |
| Gigabyte AB350-Gaming 3              | 2        | 1.94%   |
| Dell Inspiron 3668                   | 2        | 1.94%   |
| ASUS ROG STRIX B550-F GAMING         | 2        | 1.94%   |
| ASUS All Series                      | 2        | 1.94%   |
| T-bao MINI PC                        | 1        | 0.97%   |
| Pegatron p7-1030                     | 1        | 0.97%   |
| Pegatron h9-1301es                   | 1        | 0.97%   |
| MSI MS-7C90                          | 1        | 0.97%   |
| MSI MS-7C83                          | 1        | 0.97%   |
| MSI MS-7C56                          | 1        | 0.97%   |
| MSI MS-7C52                          | 1        | 0.97%   |
| MSI MS-7C09                          | 1        | 0.97%   |
| MSI MS-7B98                          | 1        | 0.97%   |
| MSI MS-7B89                          | 1        | 0.97%   |
| MSI MS-7B86                          | 1        | 0.97%   |
| MSI MS-7B09                          | 1        | 0.97%   |
| MSI MS-7A78                          | 1        | 0.97%   |
| MSI MS-7A39                          | 1        | 0.97%   |
| MSI MS-7A32                          | 1        | 0.97%   |
| MSI MS-7818                          | 1        | 0.97%   |
| MSI MS-7816                          | 1        | 0.97%   |
| MSI MS-7758                          | 1        | 0.97%   |
| MSI A320M-HDV R4.0                   | 1        | 0.97%   |
| Medion Akoya P5238 F/C395            | 1        | 0.97%   |
| Lenovo ThinkStation S20 4105O1U      | 1        | 0.97%   |
| Lenovo ThinkCentre M93p 10A90048US   | 1        | 0.97%   |
| Lenovo ThinkCentre M93p 10A90016US   | 1        | 0.97%   |
| Lenovo ThinkCentre M91p 7033CG1      | 1        | 0.97%   |
| Lenovo Legion T5 26AMR5 90RC018LBX   | 1        | 0.97%   |
| Lenovo K450e 10181                   | 1        | 0.97%   |
| HP ProDesk 600 G1 SFF                | 1        | 0.97%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 0.97%   |
| HP Pavilion Gaming Desktop 790-00xx  | 1        | 0.97%   |
| HP Pavilion Gaming Desktop 690-00xx  | 1        | 0.97%   |
| HP EliteDesk 800 G1 DM               | 1        | 0.97%   |
| HP Desktop M01-F0xxx                 | 1        | 0.97%   |
| HP 500-439                           | 1        | 0.97%   |
| Gigabyte Z77X-UD3H                   | 1        | 0.97%   |
| Gigabyte X570 AORUS PRO WIFI         | 1        | 0.97%   |
| Gigabyte X570 AORUS ELITE WIFI       | 1        | 0.97%   |
| Gigabyte X470 AORUS ULTRA GAMING     | 1        | 0.97%   |
| Gigabyte P67A-UD3-B3                 | 1        | 0.97%   |
| Gigabyte GB-BKi3(H)A-7100            | 1        | 0.97%   |
| Gigabyte GA-MA790FXT-UD5P            | 1        | 0.97%   |
| Gigabyte B85-HD3                     | 1        | 0.97%   |
| Gigabyte B550I AORUS PRO AX          | 1        | 0.97%   |
| Gigabyte B550 GAMING X V2            | 1        | 0.97%   |
| Gigabyte B550 AORUS PRO AC           | 1        | 0.97%   |
| Gigabyte B460MDS3H                   | 1        | 0.97%   |
| Gigabyte B450 I AORUS PRO WIFI       | 1        | 0.97%   |
| Gigabyte B450 AORUS M                | 1        | 0.97%   |
| Gigabyte B450 AORUS ELITE            | 1        | 0.97%   |
| Gigabyte A320M-S2H                   | 1        | 0.97%   |
| Fujitsu ESPRIMO E410                 | 1        | 0.97%   |
| Dell OptiPlex 790                    | 1        | 0.97%   |
| Dell OptiPlex 7010                   | 1        | 0.97%   |
| Dell Inspiron 580                    | 1        | 0.97%   |
| Dell Inspiron 3670                   | 1        | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS ROG                  | 7        | 6.8%    |
| ASUS PRIME                | 7        | 6.8%    |
| Dell Inspiron             | 4        | 3.88%   |
| Lenovo ThinkCentre        | 3        | 2.91%   |
| HP Pavilion               | 3        | 2.91%   |
| Gigabyte B450             | 3        | 2.91%   |
| ASUS TUF                  | 3        | 2.91%   |
| MSI MS-7C91               | 2        | 1.94%   |
| Gigabyte X570             | 2        | 1.94%   |
| Gigabyte B550             | 2        | 1.94%   |
| Gigabyte AB350-Gaming     | 2        | 1.94%   |
| Dell OptiPlex             | 2        | 1.94%   |
| ASUS All                  | 2        | 1.94%   |
| ASRock X470               | 2        | 1.94%   |
| T-bao MINI                | 1        | 0.97%   |
| Pegatron p7-1030          | 1        | 0.97%   |
| Pegatron h9-1301es        | 1        | 0.97%   |
| MSI MS-7C90               | 1        | 0.97%   |
| MSI MS-7C83               | 1        | 0.97%   |
| MSI MS-7C56               | 1        | 0.97%   |
| MSI MS-7C52               | 1        | 0.97%   |
| MSI MS-7C09               | 1        | 0.97%   |
| MSI MS-7B98               | 1        | 0.97%   |
| MSI MS-7B89               | 1        | 0.97%   |
| MSI MS-7B86               | 1        | 0.97%   |
| MSI MS-7B09               | 1        | 0.97%   |
| MSI MS-7A78               | 1        | 0.97%   |
| MSI MS-7A39               | 1        | 0.97%   |
| MSI MS-7A32               | 1        | 0.97%   |
| MSI MS-7818               | 1        | 0.97%   |
| MSI MS-7816               | 1        | 0.97%   |
| MSI MS-7758               | 1        | 0.97%   |
| MSI A320M-HDV             | 1        | 0.97%   |
| Medion Akoya              | 1        | 0.97%   |
| Lenovo ThinkStation       | 1        | 0.97%   |
| Lenovo Legion             | 1        | 0.97%   |
| Lenovo K450e              | 1        | 0.97%   |
| HP ProDesk                | 1        | 0.97%   |
| HP EliteDesk              | 1        | 0.97%   |
| HP Desktop                | 1        | 0.97%   |
| HP 500-439                | 1        | 0.97%   |
| Gigabyte Z77X-UD3H        | 1        | 0.97%   |
| Gigabyte X470             | 1        | 0.97%   |
| Gigabyte P67A-UD3-B3      | 1        | 0.97%   |
| Gigabyte GB-BKi3(H)A-7100 | 1        | 0.97%   |
| Gigabyte GA-MA790FXT-UD5P | 1        | 0.97%   |
| Gigabyte B85-HD3          | 1        | 0.97%   |
| Gigabyte B550I            | 1        | 0.97%   |
| Gigabyte B460MDS3H        | 1        | 0.97%   |
| Gigabyte A320M-S2H        | 1        | 0.97%   |
| Fujitsu ESPRIMO           | 1        | 0.97%   |
| Biostar H310MHP           | 1        | 0.97%   |
| ASUS Rampage              | 1        | 0.97%   |
| ASUS ProArt               | 1        | 0.97%   |
| ASUS P8B75-M              | 1        | 0.97%   |
| ASUS Maximus              | 1        | 0.97%   |
| ASUS M5A97                | 1        | 0.97%   |
| ASUS M4A89TD              | 1        | 0.97%   |
| ASUS CM5671               | 1        | 0.97%   |
| ASUS A68HM-PLUS           | 1        | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 16       | 15.53%  |
| 2020 | 15       | 14.56%  |
| 2019 | 15       | 14.56%  |
| 2017 | 12       | 11.65%  |
| 2013 | 9        | 8.74%   |
| 2021 | 8        | 7.77%   |
| 2014 | 8        | 7.77%   |
| 2012 | 6        | 5.83%   |
| 2011 | 4        | 3.88%   |
| 2010 | 4        | 3.88%   |
| 2016 | 2        | 1.94%   |
| 2015 | 2        | 1.94%   |
| 2009 | 2        | 1.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 103      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 103      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 103      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 30       | 28.85%  |
| 16.01-24.0  | 30       | 28.85%  |
| 8.01-16.0   | 17       | 16.35%  |
| 4.01-8.0    | 11       | 10.58%  |
| 24.01-32.0  | 8        | 7.69%   |
| 64.01-256.0 | 6        | 5.77%   |
| 3.01-4.0    | 2        | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 43       | 39.81%  |
| 3.01-4.0   | 21       | 19.44%  |
| 8.01-16.0  | 19       | 17.59%  |
| 2.01-3.0   | 15       | 13.89%  |
| 16.01-24.0 | 5        | 4.63%   |
| 1.01-2.0   | 4        | 3.7%    |
| 32.01-64.0 | 1        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 28       | 26.17%  |
| 3      | 25       | 23.36%  |
| 4      | 19       | 17.76%  |
| 1      | 17       | 15.89%  |
| 5      | 11       | 10.28%  |
| 9      | 3        | 2.8%    |
| 6      | 3        | 2.8%    |
| 14     | 1        | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 70.19%  |
| Yes       | 31       | 29.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 101      | 98.06%  |
| No        | 2        | 1.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 56.07%  |
| No        | 47       | 43.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 50.48%  |
| Yes       | 52       | 49.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 36       | 34.95%  |
| Germany      | 13       | 12.62%  |
| UK           | 5        | 4.85%   |
| Italy        | 4        | 3.88%   |
| Canada       | 4        | 3.88%   |
| Australia    | 4        | 3.88%   |
| Sweden       | 3        | 2.91%   |
| Spain        | 3        | 2.91%   |
| Russia       | 3        | 2.91%   |
| Netherlands  | 3        | 2.91%   |
| Romania      | 2        | 1.94%   |
| Puerto Rico  | 2        | 1.94%   |
| Latvia       | 2        | 1.94%   |
| France       | 2        | 1.94%   |
| Brazil       | 2        | 1.94%   |
| Belgium      | 2        | 1.94%   |
| Venezuela    | 1        | 0.97%   |
| Ukraine      | 1        | 0.97%   |
| South Africa | 1        | 0.97%   |
| Slovakia     | 1        | 0.97%   |
| Poland       | 1        | 0.97%   |
| Philippines  | 1        | 0.97%   |
| Norway       | 1        | 0.97%   |
| India        | 1        | 0.97%   |
| Iceland      | 1        | 0.97%   |
| Greece       | 1        | 0.97%   |
| Denmark      | 1        | 0.97%   |
| Chile        | 1        | 0.97%   |
| Argentina    | 1        | 0.97%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Wasmes                  | 2        | 1.89%   |
| Sydney                  | 2        | 1.89%   |
| Riga                    | 2        | 1.89%   |
| Oklahoma City           | 2        | 1.89%   |
| Melbourne               | 2        | 1.89%   |
| Kingsport               | 2        | 1.89%   |
| Weiterstadt             | 1        | 0.94%   |
| Weilen unter den Rinnen | 1        | 0.94%   |
| Voronezh                | 1        | 0.94%   |
| Volzhskiy               | 1        | 0.94%   |
| Västerås              | 1        | 0.94%   |
| Valence                 | 1        | 0.94%   |
| Urbandale               | 1        | 0.94%   |
| Ullerslev               | 1        | 0.94%   |
| Timișoara              | 1        | 0.94%   |
| Taunusstein             | 1        | 0.94%   |
| Stockholm               | 1        | 0.94%   |
| Stavropol               | 1        | 0.94%   |
| Stanley                 | 1        | 0.94%   |
| St Louis                | 1        | 0.94%   |
| Sindelfingen            | 1        | 0.94%   |
| Shreveport              | 1        | 0.94%   |
| Satu Mare               | 1        | 0.94%   |
| Sarasota                | 1        | 0.94%   |
| Sao Paulo               | 1        | 0.94%   |
| Santa Cruz de Tenerife  | 1        | 0.94%   |
| San Juan                | 1        | 0.94%   |
| San Jose                | 1        | 0.94%   |
| Reykjavik               | 1        | 0.94%   |
| Reston                  | 1        | 0.94%   |
| Regina                  | 1        | 0.94%   |
| Pune                    | 1        | 0.94%   |
| Providencia             | 1        | 0.94%   |
| Portland                | 1        | 0.94%   |
| Plymouth                | 1        | 0.94%   |
| Perkasie                | 1        | 0.94%   |
| Pauls Valley            | 1        | 0.94%   |
| Orlando                 | 1        | 0.94%   |
| Omaha                   | 1        | 0.94%   |
| Noss                    | 1        | 0.94%   |
| Nijmegen                | 1        | 0.94%   |
| Nashua                  | 1        | 0.94%   |
| Mount Vernon            | 1        | 0.94%   |
| Montreal                | 1        | 0.94%   |
| Montevarchi             | 1        | 0.94%   |
| Minden                  | 1        | 0.94%   |
| Milwaukee               | 1        | 0.94%   |
| Milton                  | 1        | 0.94%   |
| Milan                   | 1        | 0.94%   |
| Miengo                  | 1        | 0.94%   |
| Miami                   | 1        | 0.94%   |
| Martigues               | 1        | 0.94%   |
| Mannheim                | 1        | 0.94%   |
| Los Angeles             | 1        | 0.94%   |
| London                  | 1        | 0.94%   |
| Langhorne               | 1        | 0.94%   |
| Laguna Beach            | 1        | 0.94%   |
| Kyiv                    | 1        | 0.94%   |
| Krakow                  | 1        | 0.94%   |
| Kokomo                  | 1        | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 46       | 66     | 18.04%  |
| Seagate                   | 46       | 72     | 18.04%  |
| Samsung Electronics       | 44       | 94     | 17.25%  |
| Toshiba                   | 16       | 18     | 6.27%   |
| Crucial                   | 15       | 21     | 5.88%   |
| Kingston                  | 12       | 19     | 4.71%   |
| SanDisk                   | 11       | 16     | 4.31%   |
| Phison                    | 7        | 8      | 2.75%   |
| Hitachi                   | 7        | 7      | 2.75%   |
| A-DATA Technology         | 5        | 8      | 1.96%   |
| Intel                     | 4        | 5      | 1.57%   |
| XPG                       | 3        | 4      | 1.18%   |
| Silicon Motion            | 3        | 3      | 1.18%   |
| PNY                       | 3        | 3      | 1.18%   |
| Unknown                   | 2        | 2      | 0.78%   |
| Transcend                 | 2        | 2      | 0.78%   |
| Team                      | 2        | 3      | 0.78%   |
| SPCC                      | 2        | 2      | 0.78%   |
| OCZ                       | 2        | 2      | 0.78%   |
| China                     | 2        | 4      | 0.78%   |
| WD MediaMax               | 1        | 1      | 0.39%   |
| USB30                     | 1        | 2      | 0.39%   |
| TO Exter                  | 1        | 1      | 0.39%   |
| T-FORCE                   | 1        | 1      | 0.39%   |
| SK hynix                  | 1        | 1      | 0.39%   |
| Qumo                      | 1        | 1      | 0.39%   |
| Plextor                   | 1        | 1      | 0.39%   |
| Mushkin                   | 1        | 1      | 0.39%   |
| Micron/Crucial Technology | 1        | 2      | 0.39%   |
| Micron Technology         | 1        | 1      | 0.39%   |
| LITEONIT                  | 1        | 1      | 0.39%   |
| Intenso                   | 1        | 2      | 0.39%   |
| Inateck                   | 1        | 1      | 0.39%   |
| HS-SSD-E100               | 1        | 1      | 0.39%   |
| HGST                      | 1        | 1      | 0.39%   |
| Hewlett-Packard           | 1        | 1      | 0.39%   |
| EMTEC                     | 1        | 1      | 0.39%   |
| Corsair                   | 1        | 4      | 0.39%   |
| ASMedia                   | 1        | 2      | 0.39%   |
| Apacer                    | 1        | 1      | 0.39%   |
| Unknown                   | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB              | 6        | 1.96%   |
| Samsung NVMe SSD Drive 1TB             | 6        | 1.96%   |
| Seagate ST2000DM008-2FR102 2TB         | 5        | 1.63%   |
| Samsung SSD 970 EVO Plus 500GB         | 5        | 1.63%   |
| Samsung SSD 860 EVO 500GB              | 5        | 1.63%   |
| Crucial CT1000MX500SSD1 1TB            | 5        | 1.63%   |
| Seagate ST1000DM010-2EP102 1TB         | 4        | 1.31%   |
| WDC WD10EZEX-60WN4A0 1TB               | 3        | 0.98%   |
| Toshiba DT01ACA100 1TB                 | 3        | 0.98%   |
| Seagate ST4000DM004-2CV104 4TB         | 3        | 0.98%   |
| SanDisk SSD PLUS 1000GB                | 3        | 0.98%   |
| Samsung SSD 970 EVO 250GB              | 3        | 0.98%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 3        | 0.98%   |
| XPG NVMe SSD Drive 512GB               | 2        | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2        | 0.65%   |
| WDC WDS100T2B0C-00PXH0 1TB             | 2        | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 2        | 0.65%   |
| WDC WD20EARX-00PASB0 2TB               | 2        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2        | 0.65%   |
| Toshiba HDWD110 1TB                    | 2        | 0.65%   |
| SPCC Solid State Disk 512GB            | 2        | 0.65%   |
| Seagate ST3320820AS 320GB              | 2        | 0.65%   |
| Seagate ST3000DM001-1ER166 3TB         | 2        | 0.65%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2        | 0.65%   |
| Seagate ST2000DM001-1ER164 2TB         | 2        | 0.65%   |
| Seagate ST2000DL003-9VT166 2TB         | 2        | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB         | 2        | 0.65%   |
| Seagate Portable 1TB                   | 2        | 0.65%   |
| Seagate Expansion+ Desk 4TB            | 2        | 0.65%   |
| Seagate Backup+ Hub BK 8TB             | 2        | 0.65%   |
| SanDisk NVMe SSD Drive 500GB           | 2        | 0.65%   |
| SanDisk NVMe SSD Drive 1TB             | 2        | 0.65%   |
| Samsung SSD 980 PRO 500GB              | 2        | 0.65%   |
| Samsung SSD 970 EVO 500GB              | 2        | 0.65%   |
| Samsung SSD 860 EVO 250GB              | 2        | 0.65%   |
| Samsung SSD 860 EVO 1TB                | 2        | 0.65%   |
| Samsung SSD 850 EVO 500GB              | 2        | 0.65%   |
| Samsung NVMe SSD Drive 250GB           | 2        | 0.65%   |
| Samsung NVMe SSD Drive 1024GB          | 2        | 0.65%   |
| Phison NVMe SSD Drive 2TB              | 2        | 0.65%   |
| Kingston SV300S37A120G 120GB SSD       | 2        | 0.65%   |
| Kingston SA400S37240G 240GB SSD        | 2        | 0.65%   |
| Crucial CT1000P1SSD8 1TB               | 2        | 0.65%   |
| XPG SPECTRIX S20G 500GB                | 1        | 0.33%   |
| WDC WDS500G2X0C-00L350 500GB           | 1        | 0.33%   |
| WDC WDS500G2B0C-00PXH0 500GB           | 1        | 0.33%   |
| WDC WDS500G2B0B 500GB SSD              | 1        | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.33%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 1        | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1        | 0.33%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 1        | 0.33%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 1        | 0.33%   |
| WDC WD800BEVS-07RST0 80GB              | 1        | 0.33%   |
| WDC WD6400AAKS-75A7B2 640GB            | 1        | 0.33%   |
| WDC WD6400AAKS-65A7B2 640GB            | 1        | 0.33%   |
| WDC WD6003FZBX-00K5WB0 6TB             | 1        | 0.33%   |
| WDC WD5000LPCX-22VHAT1 500GB           | 1        | 0.33%   |
| WDC WD5000AZRX-00L4HB0 500GB           | 1        | 0.33%   |
| WDC WD5000AZRX-00A8LB0 500GB           | 1        | 0.33%   |
| WDC WD5000AAKS-00E4A0 500GB            | 1        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 45       | 70     | 41.67%  |
| WDC                 | 36       | 53     | 33.33%  |
| Toshiba             | 13       | 14     | 12.04%  |
| Hitachi             | 7        | 7      | 6.48%   |
| Samsung Electronics | 4        | 4      | 3.7%    |
| Intenso             | 1        | 2      | 0.93%   |
| Inateck             | 1        | 1      | 0.93%   |
| HGST                | 1        | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 36     | 24.44%  |
| Crucial             | 12       | 16     | 13.33%  |
| Kingston            | 11       | 17     | 12.22%  |
| WDC                 | 7        | 7      | 7.78%   |
| SanDisk             | 7        | 11     | 7.78%   |
| A-DATA Technology   | 5        | 8      | 5.56%   |
| Transcend           | 2        | 2      | 2.22%   |
| Toshiba             | 2        | 3      | 2.22%   |
| Team                | 2        | 3      | 2.22%   |
| SPCC                | 2        | 2      | 2.22%   |
| PNY                 | 2        | 2      | 2.22%   |
| OCZ                 | 2        | 2      | 2.22%   |
| China               | 2        | 4      | 2.22%   |
| USB30               | 1        | 2      | 1.11%   |
| Unknown             | 1        | 1      | 1.11%   |
| TO Exter            | 1        | 1      | 1.11%   |
| T-FORCE             | 1        | 1      | 1.11%   |
| SK hynix            | 1        | 1      | 1.11%   |
| Qumo                | 1        | 1      | 1.11%   |
| Plextor             | 1        | 1      | 1.11%   |
| Mushkin             | 1        | 1      | 1.11%   |
| Micron Technology   | 1        | 1      | 1.11%   |
| LITEONIT            | 1        | 1      | 1.11%   |
| EMTEC               | 1        | 1      | 1.11%   |
| ASMedia             | 1        | 2      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 78       | 152    | 38.81%  |
| SSD     | 63       | 127    | 31.34%  |
| NVMe    | 53       | 101    | 26.37%  |
| Unknown | 7        | 7      | 3.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 93       | 258    | 58.13%  |
| NVMe | 53       | 101    | 33.13%  |
| SAS  | 14       | 28     | 8.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 64       | 122    | 36.36%  |
| 0.51-1.0   | 52       | 71     | 29.55%  |
| 1.01-2.0   | 32       | 49     | 18.18%  |
| 3.01-4.0   | 11       | 13     | 6.25%   |
| 2.01-3.0   | 8        | 13     | 4.55%   |
| 4.01-10.0  | 7        | 8      | 3.98%   |
| 10.01-20.0 | 2        | 3      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 47       | 44.76%  |
| 1001-2000      | 21       | 20%     |
| 2001-3000      | 16       | 15.24%  |
| 501-1000       | 11       | 10.48%  |
| 251-500        | 7        | 6.67%   |
| Unknown        | 2        | 1.9%    |
| 101-250        | 1        | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 18       | 16.67%  |
| 1001-2000      | 17       | 15.74%  |
| 251-500        | 16       | 14.81%  |
| 101-250        | 16       | 14.81%  |
| 2001-3000      | 13       | 12.04%  |
| More than 3000 | 12       | 11.11%  |
| 51-100         | 10       | 9.26%   |
| 21-50          | 3        | 2.78%   |
| Unknown        | 2        | 1.85%   |
| 1-20           | 1        | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00E4A0 500GB           | 1        | 1      | 5.26%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1        | 1      | 5.26%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 5.26%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1        | 1      | 5.26%   |
| WDC WD10EADS-22M2B0 1TB               | 1        | 1      | 5.26%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 5.26%   |
| Seagate ST9250827AS 250GB             | 1        | 1      | 5.26%   |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 1      | 5.26%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1        | 1      | 5.26%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 980 1TB       | 1        | 3      | 5.26%   |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 5      | 5.26%   |
| OCZ TRION100 480GB SSD                | 1        | 1      | 5.26%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 5.26%   |
| Kingston SH103S3240G 240GB SSD        | 1        | 1      | 5.26%   |
| Hitachi HTS543216L9A300 160GB         | 1        | 1      | 5.26%   |
| Hewlett-Packard SSD EX900 500GB       | 1        | 1      | 5.26%   |
| Crucial CT960M500SSD1 960GB           | 1        | 1      | 5.26%   |
| A-DATA Technology SU800 1TB SSD       | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 33.33%  |
| Seagate             | 3        | 3      | 16.67%  |
| Kingston            | 2        | 2      | 11.11%  |
| SanDisk             | 1        | 1      | 5.56%   |
| Samsung Electronics | 1        | 8      | 5.56%   |
| OCZ                 | 1        | 1      | 5.56%   |
| Hitachi             | 1        | 1      | 5.56%   |
| Hewlett-Packard     | 1        | 1      | 5.56%   |
| Crucial             | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 6      | 60%     |
| Seagate | 3        | 3      | 30%     |
| Hitachi | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 10     | 52.94%  |
| SSD  | 6        | 6      | 35.29%  |
| NVMe | 2        | 9      | 11.76%  |

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
| Detected | 59       | 193    | 46.46%  |
| Works    | 52       | 169    | 40.94%  |
| Malfunc  | 16       | 25     | 12.6%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 53       | 31.18%  |
| Intel                        | 50       | 29.41%  |
| Samsung Electronics          | 25       | 14.71%  |
| SanDisk                      | 9        | 5.29%   |
| Phison Electronics           | 8        | 4.71%   |
| ASMedia Technology           | 5        | 2.94%   |
| Silicon Motion               | 4        | 2.35%   |
| Micron/Crucial Technology    | 3        | 1.76%   |
| Marvell Technology Group     | 3        | 1.76%   |
| Kingston Technology Company  | 2        | 1.18%   |
| JMicron Technology           | 2        | 1.18%   |
| ADATA Technology             | 2        | 1.18%   |
| Union Memory (Shenzhen)      | 1        | 0.59%   |
| Toshiba America Info Systems | 1        | 0.59%   |
| Shenzhen Longsys Electronics | 1        | 0.59%   |
| Realtek Semiconductor        | 1        | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 14.95%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23       | 10.75%  |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 7.01%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 5.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 5.14%   |
| Phison E12 NVMe Controller                                                              | 6        | 2.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.34%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.87%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3        | 1.4%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 1.4%    |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.4%    |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.4%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.93%   |
| Micron/Crucial NVMe Controller                                                          | 2        | 0.93%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.93%   |
| Intel SSD 660P Series                                                                   | 2        | 0.93%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 2        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 0.93%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.93%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.93%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1        | 0.47%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 0.47%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.47%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                             | 1        | 0.47%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.47%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 0.47%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.47%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.47%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.47%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.47%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.47%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.47%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.47%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.47%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 0.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.47%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.47%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.47%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.47%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 0.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 92       | 56.79%  |
| NVMe | 54       | 33.33%  |
| IDE  | 10       | 6.17%   |
| RAID | 6        | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 53       | 51.46%  |
| Intel  | 50       | 48.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor              | 6        | 5.83%   |
| AMD Ryzen 5 3600 6-Core Processor               | 4        | 3.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 3        | 2.91%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 3        | 2.91%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 2.91%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 3        | 2.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 2        | 1.94%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 2        | 1.94%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 2        | 1.94%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 1.94%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 2        | 1.94%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 2        | 1.94%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 2        | 1.94%   |
| AMD FX-8350 Eight-Core Processor                | 2        | 1.94%   |
| Intel Xeon CPU W3550 @ 3.07GHz                  | 1        | 0.97%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz             | 1        | 0.97%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz             | 1        | 0.97%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 0.97%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 0.97%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 0.97%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1        | 0.97%   |
| Intel Core i7-6850K CPU @ 3.60GHz               | 1        | 0.97%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 0.97%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 0.97%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 0.97%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 0.97%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1        | 0.97%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 0.97%   |
| Intel Core i7-10700F CPU @ 2.90GHz              | 1        | 0.97%   |
| Intel Core i5-9600KF CPU @ 3.70GHz              | 1        | 0.97%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 0.97%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 0.97%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 0.97%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1        | 0.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1        | 0.97%   |
| Intel Core i5-4690K CPU @ 3.50GHz               | 1        | 0.97%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 0.97%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 0.97%   |
| Intel Core i5-3570K CPU @ 3.40GHz               | 1        | 0.97%   |
| Intel Core i5-3475S CPU @ 2.90GHz               | 1        | 0.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 0.97%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 1        | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 0.97%   |
| Intel Core i5-10600K CPU @ 4.10GHz              | 1        | 0.97%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 0.97%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 0.97%   |
| Intel Core i3-9100F CPU @ 3.60GHz               | 1        | 0.97%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 0.97%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1        | 0.97%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 0.97%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 0.97%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 1        | 0.97%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz           | 1        | 0.97%   |
| Intel Celeron CPU G3900 @ 2.80GHz               | 1        | 0.97%   |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz        | 1        | 0.97%   |
| AMD Ryzen Threadripper 2970WX 24-Core Processor | 1        | 0.97%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1        | 0.97%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor  | 1        | 0.97%   |
| AMD Ryzen 9 5900 12-Core Processor              | 1        | 0.97%   |
| AMD Ryzen 7 5800 8-Core Processor               | 1        | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 19       | 18.45%  |
| AMD Ryzen 7             | 16       | 15.53%  |
| AMD Ryzen 5             | 15       | 14.56%  |
| Intel Core i7           | 13       | 12.62%  |
| Intel Core i3           | 10       | 9.71%   |
| AMD Ryzen 9             | 7        | 6.8%    |
| AMD Ryzen 3             | 5        | 4.85%   |
| Intel Xeon              | 3        | 2.91%   |
| AMD Ryzen Threadripper  | 3        | 2.91%   |
| AMD FX                  | 2        | 1.94%   |
| Other                   | 1        | 0.97%   |
| Intel Pentium Dual-Core | 1        | 0.97%   |
| Intel Core i9           | 1        | 0.97%   |
| Intel Core 2 Quad       | 1        | 0.97%   |
| Intel Celeron           | 1        | 0.97%   |
| AMD Phenom II X6        | 1        | 0.97%   |
| AMD Phenom II X4        | 1        | 0.97%   |
| AMD Phenom II X2        | 1        | 0.97%   |
| AMD A8                  | 1        | 0.97%   |
| AMD A10                 | 1        | 0.97%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 36       | 34.95%  |
| 6      | 24       | 23.3%   |
| 8      | 18       | 17.48%  |
| 2      | 14       | 13.59%  |
| 12     | 5        | 4.85%   |
| 16     | 4        | 3.88%   |
| 24     | 1        | 0.97%   |
| 10     | 1        | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 103      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 76       | 73.79%  |
| 1      | 27       | 26.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 103      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 49       | 47.12%  |
| 0x306c3    | 7        | 6.73%   |
| 0x08701021 | 7        | 6.73%   |
| 0x0800820d | 6        | 5.77%   |
| 0x306a9    | 4        | 3.85%   |
| 0x906ea    | 3        | 2.88%   |
| 0x206a7    | 3        | 2.88%   |
| 0x506e3    | 2        | 1.92%   |
| 0x0a50000c | 2        | 1.92%   |
| 0x0810100b | 2        | 1.92%   |
| 0x08001137 | 2        | 1.92%   |
| 0xa0655    | 1        | 0.96%   |
| 0xa0653    | 1        | 0.96%   |
| 0x906ed    | 1        | 0.96%   |
| 0x906ec    | 1        | 0.96%   |
| 0x906eb    | 1        | 0.96%   |
| 0x906e9    | 1        | 0.96%   |
| 0x106a5    | 1        | 0.96%   |
| 0x1067a    | 1        | 0.96%   |
| 0x0a201204 | 1        | 0.96%   |
| 0x0a201016 | 1        | 0.96%   |
| 0x0a201009 | 1        | 0.96%   |
| 0x08701013 | 1        | 0.96%   |
| 0x08108109 | 1        | 0.96%   |
| 0x08101016 | 1        | 0.96%   |
| 0x06003106 | 1        | 0.96%   |
| 0x06000852 | 1        | 0.96%   |
| 0x010000dc | 1        | 0.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 16       | 15.53%  |
| KabyLake    | 13       | 12.62%  |
| Zen+        | 12       | 11.65%  |
| Haswell     | 12       | 11.65%  |
| Zen 3       | 10       | 9.71%   |
| Zen         | 8        | 7.77%   |
| IvyBridge   | 7        | 6.8%    |
| SandyBridge | 5        | 4.85%   |
| CometLake   | 5        | 4.85%   |
| Piledriver  | 3        | 2.91%   |
| K10         | 3        | 2.91%   |
| Skylake     | 2        | 1.94%   |
| Penryn      | 2        | 1.94%   |
| Westmere    | 1        | 0.97%   |
| Steamroller | 1        | 0.97%   |
| Nehalem     | 1        | 0.97%   |
| Broadwell   | 1        | 0.97%   |
| Unknown     | 1        | 0.97%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 49       | 42.24%  |
| AMD    | 45       | 38.79%  |
| Intel  | 22       | 18.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 8.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 6.78%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 4        | 3.39%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 4        | 3.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 3.39%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 2.54%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 2.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.54%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.54%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 2.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.69%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.69%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.69%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.69%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.69%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.69%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.69%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.69%   |
| Intel HD Graphics 630                                                       | 2        | 1.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.69%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.85%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.85%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.85%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.85%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.85%   |
| Nvidia GK106 [GeForce GTX 650 OEM]                                          | 1        | 0.85%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.85%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.85%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.85%   |
| Nvidia GF104 [GeForce GTX 460 SE]                                           | 1        | 0.85%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.85%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.85%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 0.85%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 0.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.85%   |
| Intel HD Graphics 620                                                       | 1        | 0.85%   |
| Intel HD Graphics 510                                                       | 1        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 0.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 0.85%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 0.85%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 0.85%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 0.85%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 0.85%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 0.85%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 0.85%   |
| AMD Fiji [Radeon R9 FURY / NANO Series]                                     | 1        | 0.85%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 43       | 41.75%  |
| 1 x AMD        | 41       | 39.81%  |
| 1 x Intel      | 12       | 11.65%  |
| 2 x Nvidia     | 2        | 1.94%   |
| Intel + Nvidia | 2        | 1.94%   |
| AMD + Nvidia   | 2        | 1.94%   |
| Intel + AMD    | 1        | 0.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 62       | 59.62%  |
| Proprietary | 42       | 40.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 37       | 35.24%  |
| 7.01-8.0   | 20       | 19.05%  |
| 3.01-4.0   | 12       | 11.43%  |
| 1.01-2.0   | 11       | 10.48%  |
| 5.01-6.0   | 6        | 5.71%   |
| 8.01-16.0  | 6        | 5.71%   |
| 0.51-1.0   | 6        | 5.71%   |
| 0.01-0.5   | 4        | 3.81%   |
| 2.01-3.0   | 2        | 1.9%    |
| 16.01-24.0 | 1        | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 23       | 16.55%  |
| Dell                 | 15       | 10.79%  |
| Acer                 | 15       | 10.79%  |
| Goldstar             | 12       | 8.63%   |
| AOC                  | 9        | 6.47%   |
| BenQ                 | 8        | 5.76%   |
| Ancor Communications | 8        | 5.76%   |
| Hewlett-Packard      | 7        | 5.04%   |
| Unknown              | 6        | 4.32%   |
| ASUSTek Computer     | 4        | 2.88%   |
| MSI                  | 3        | 2.16%   |
| Gigabyte Technology  | 3        | 2.16%   |
| Vizio                | 2        | 1.44%   |
| Sony                 | 2        | 1.44%   |
| Philips              | 2        | 1.44%   |
| NEC Computers        | 2        | 1.44%   |
| Iiyama               | 2        | 1.44%   |
| ViewSonic            | 1        | 0.72%   |
| Toshiba              | 1        | 0.72%   |
| ONN                  | 1        | 0.72%   |
| MiTAC                | 1        | 0.72%   |
| Mi                   | 1        | 0.72%   |
| LTM                  | 1        | 0.72%   |
| LG Electronics       | 1        | 0.72%   |
| Lenovo Group Limited | 1        | 0.72%   |
| Lenovo               | 1        | 0.72%   |
| Insignia             | 1        | 0.72%   |
| HPN                  | 1        | 0.72%   |
| HKC                  | 1        | 0.72%   |
| Fujitsu Siemens      | 1        | 0.72%   |
| Element              | 1        | 0.72%   |
| AOpen                | 1        | 0.72%   |
| Alba                 | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 1.99%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.32%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 1.32%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 1.32%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 1.32%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.66%   |
| Vizio E320-A1 VIZ0095 1360x768 697x392mm 31.5-inch                     | 1        | 0.66%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1        | 0.66%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.66%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.66%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.66%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.66%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.66%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1        | 0.66%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                       | 1        | 0.66%   |
| Sony TV SNY1802 1920x1080                                              | 1        | 0.66%   |
| Sony TV SNY0801 1360x768                                               | 1        | 0.66%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1        | 0.66%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.66%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM04D5 1920x540                        | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1        | 0.66%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 530x300mm 24.0-inch   | 1        | 0.66%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1        | 0.66%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1        | 0.66%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1        | 0.66%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SAM0FBE 3840x2160 950x540mm 43.0-inch  | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 480x270mm 21.7-inch  | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch  | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.66%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                      | 1        | 0.66%   |
| Samsung Electronics LCD Monitor C32R50x                                | 1        | 0.66%   |
| Samsung Electronics LCD Monitor C27F390 3840x1080                      | 1        | 0.66%   |
| Samsung Electronics LCD Monitor C27F390 1920x1080                      | 1        | 0.66%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 1        | 0.66%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.66%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.66%   |
| Philips LCD Monitor 221E 1920x1080                                     | 1        | 0.66%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                    | 1        | 0.66%   |
| NEC Computers EA243WM NEC6866 1920x1200 519x324mm 24.1-inch            | 1        | 0.66%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch            | 1        | 0.66%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch             | 1        | 0.66%   |
| MSI Optix MAG24C MSI1462 1920x1080 520x290mm 23.4-inch                 | 1        | 0.66%   |
| MSI G273Q MSI3CA8 2560x1440 597x336mm 27.0-inch                        | 1        | 0.66%   |
| MSI G273 MSI3CA7 1920x1080 597x336mm 27.0-inch                         | 1        | 0.66%   |
| MiTAC LCD MONITOR MTC03D7 1920x1080 410x256mm 19.0-inch                | 1        | 0.66%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 0.66%   |
| LTM LCD_VGA LTM0659 1024x768 880x500mm 39.8-inch                       | 1        | 0.66%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 0.66%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1        | 0.66%   |
| Lenovo Group Limited LCD Monitor LEN S27q-10                           | 1        | 0.66%   |
| Insignia NS32D200NA14 BBY32D2 1680x1050 698x392mm 31.5-inch            | 1        | 0.66%   |
| Iiyama PL2790 IVM6616 1920x1080 598x336mm 27.0-inch                    | 1        | 0.66%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                   | 1        | 0.66%   |
| HPN LCD Monitor HP Z27 7680x2160                                       | 1        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 61       | 45.52%  |
| 3840x2160 (4K)     | 15       | 11.19%  |
| Unknown            | 9        | 6.72%   |
| 2560x1440 (QHD)    | 6        | 4.48%   |
| 3840x1080          | 5        | 3.73%   |
| 3440x1440          | 4        | 2.99%   |
| 2560x1080          | 4        | 2.99%   |
| 1680x1050 (WSXGA+) | 4        | 2.99%   |
| 1366x768 (WXGA)    | 4        | 2.99%   |
| 1280x1024 (SXGA)   | 4        | 2.99%   |
| 1600x900 (HD+)     | 3        | 2.24%   |
| 1440x900 (WXGA+)   | 3        | 2.24%   |
| 7680x2160          | 2        | 1.49%   |
| 1920x1200 (WUXGA)  | 2        | 1.49%   |
| 1360x768           | 2        | 1.49%   |
| 9600x2160          | 1        | 0.75%   |
| 4480x1440          | 1        | 0.75%   |
| 3840x1200          | 1        | 0.75%   |
| 2048x1152          | 1        | 0.75%   |
| 1920x540           | 1        | 0.75%   |
| 1024x768 (XGA)     | 1        | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 26       | 20%     |
| 24      | 21       | 16.15%  |
| Unknown | 21       | 16.15%  |
| 23      | 15       | 11.54%  |
| 19      | 7        | 5.38%   |
| 21      | 6        | 4.62%   |
| 34      | 5        | 3.85%   |
| 22      | 5        | 3.85%   |
| 72      | 3        | 2.31%   |
| 49      | 3        | 2.31%   |
| 31      | 3        | 2.31%   |
| 20      | 3        | 2.31%   |
| 40      | 2        | 1.54%   |
| 28      | 2        | 1.54%   |
| 54      | 1        | 0.77%   |
| 48      | 1        | 0.77%   |
| 43      | 1        | 0.77%   |
| 39      | 1        | 0.77%   |
| 33      | 1        | 0.77%   |
| 32      | 1        | 0.77%   |
| 25      | 1        | 0.77%   |
| 17      | 1        | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 53       | 42.74%  |
| Unknown     | 21       | 16.94%  |
| 401-500     | 17       | 13.71%  |
| 601-700     | 10       | 8.06%   |
| 701-800     | 7        | 5.65%   |
| 1001-1500   | 5        | 4.03%   |
| 801-900     | 3        | 2.42%   |
| 351-400     | 3        | 2.42%   |
| 1501-2000   | 3        | 2.42%   |
| 301-350     | 1        | 0.81%   |
| 901-1000    | 1        | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 71       | 61.21%  |
| Unknown | 19       | 16.38%  |
| 16/10   | 13       | 11.21%  |
| 21/9    | 6        | 5.17%   |
| 5/4     | 4        | 3.45%   |
| 32/9    | 3        | 2.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 35       | 28.23%  |
| 301-350        | 26       | 20.97%  |
| Unknown        | 21       | 16.94%  |
| 351-500        | 11       | 8.87%   |
| 151-200        | 10       | 8.06%   |
| 251-300        | 8        | 6.45%   |
| More than 1000 | 6        | 4.84%   |
| 501-1000       | 6        | 4.84%   |
| 141-150        | 1        | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 63       | 54.78%  |
| Unknown | 21       | 18.26%  |
| 101-120 | 17       | 14.78%  |
| 1-50    | 6        | 5.22%   |
| 121-160 | 6        | 5.22%   |
| 161-240 | 2        | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 57.28%  |
| 2     | 32       | 31.07%  |
| 3     | 10       | 9.71%   |
| 0     | 2        | 1.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 65       | 40.88%  |
| Intel                 | 48       | 30.19%  |
| Qualcomm Atheros      | 10       | 6.29%   |
| Ralink Technology     | 4        | 2.52%   |
| NetGear               | 4        | 2.52%   |
| Broadcom              | 4        | 2.52%   |
| TP-Link               | 3        | 1.89%   |
| Microsoft             | 3        | 1.89%   |
| Linksys               | 3        | 1.89%   |
| Aquantia              | 3        | 1.89%   |
| Ralink                | 2        | 1.26%   |
| MediaTek              | 2        | 1.26%   |
| Samsung Electronics   | 1        | 0.63%   |
| InterBiometrics       | 1        | 0.63%   |
| Holtek Semiconductor  | 1        | 0.63%   |
| DisplayLink           | 1        | 0.63%   |
| Belkin Components     | 1        | 0.63%   |
| ASIX Electronics      | 1        | 0.63%   |
| Alteon Networks       | 1        | 0.63%   |
| Accton Technology     | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 53       | 28.96%  |
| Intel I211 Gigabit Network Connection                                     | 13       | 7.1%    |
| Realtek RTL8125 2.5GbE Controller                                         | 7        | 3.83%   |
| Intel Wi-Fi 6 AX200                                                       | 7        | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 6        | 3.28%   |
| Intel Wireless-AC 9260                                                    | 6        | 3.28%   |
| Intel Ethernet Controller I225-V                                          | 6        | 3.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6        | 3.28%   |
| Intel Ethernet Connection I217-LM                                         | 4        | 2.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 1.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 3        | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 3        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3        | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 2        | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 2        | 1.09%   |
| NetGear A6210                                                             | 2        | 1.09%   |
| Microsoft XBOX ACC                                                        | 2        | 1.09%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                                      | 2        | 1.09%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]         | 2        | 1.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 1        | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1        | 0.55%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1        | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1        | 0.55%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1        | 0.55%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 0.55%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 0.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 1        | 0.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1        | 0.55%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1        | 0.55%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 0.55%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 1        | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1        | 0.55%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 0.55%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 0.55%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 0.55%   |
| MediaTek TECNO SPARK 6 Go                                                 | 1        | 0.55%   |
| MediaTek TECNO SPARK 3                                                    | 1        | 0.55%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 0.55%   |
| InterBiometrics Dygma Shortcut Keyboard                                   | 1        | 0.55%   |
| Intel Wireless 7265                                                       | 1        | 0.55%   |
| Intel Ethernet Connection I217-V                                          | 1        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                      | 1        | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                      | 1        | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1        | 0.55%   |
| Intel Centrino Wireless-N 2230                                            | 1        | 0.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 1        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                   | 1        | 0.55%   |
| Holtek SKILLER SGM1                                                       | 1        | 0.55%   |
| DisplayLink ThinkPad USB 3.0 Dock                                         | 1        | 0.55%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                   | 1        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 26       | 39.39%  |
| Realtek Semiconductor | 15       | 22.73%  |
| Ralink Technology     | 4        | 6.06%   |
| NetGear               | 4        | 6.06%   |
| TP-Link               | 3        | 4.55%   |
| Qualcomm Atheros      | 3        | 4.55%   |
| Microsoft             | 3        | 4.55%   |
| Linksys               | 3        | 4.55%   |
| Ralink                | 2        | 3.03%   |
| Broadcom              | 2        | 3.03%   |
| Accton Technology     | 1        | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 7        | 10.61%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 6        | 9.09%   |
| Intel Wireless-AC 9260                                                    | 6        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6        | 9.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 3        | 4.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 2        | 3.03%   |
| NetGear A6210                                                             | 2        | 3.03%   |
| Microsoft XBOX ACC                                                        | 2        | 3.03%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2        | 3.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 1        | 1.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1        | 1.52%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1        | 1.52%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1        | 1.52%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 1.52%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.52%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1        | 1.52%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.52%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 1.52%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 1.52%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.52%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 1.52%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 1.52%   |
| Intel Wireless 7265                                                       | 1        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1        | 1.52%   |
| Intel Centrino Wireless-N 2230                                            | 1        | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 1        | 1.52%   |
| Broadcom Network controller                                               | 1        | 1.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 1        | 1.52%   |
| Accton SMCWUSB-G 802.11bg                                                 | 1        | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 61       | 53.98%  |
| Intel                 | 32       | 28.32%  |
| Qualcomm Atheros      | 8        | 7.08%   |
| Aquantia              | 3        | 2.65%   |
| MediaTek              | 2        | 1.77%   |
| Broadcom              | 2        | 1.77%   |
| Samsung Electronics   | 1        | 0.88%   |
| DisplayLink           | 1        | 0.88%   |
| Belkin Components     | 1        | 0.88%   |
| ASIX Electronics      | 1        | 0.88%   |
| Alteon Networks       | 1        | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 53       | 46.09%  |
| Intel I211 Gigabit Network Connection                               | 13       | 11.3%   |
| Realtek RTL8125 2.5GbE Controller                                   | 7        | 6.09%   |
| Intel Ethernet Controller I225-V                                    | 6        | 5.22%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 3.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 2.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                | 2        | 1.74%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.87%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.87%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.87%   |
| MediaTek TECNO SPARK 6 Go                                           | 1        | 0.87%   |
| MediaTek TECNO SPARK 3                                              | 1        | 0.87%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                | 1        | 0.87%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 0.87%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 0.87%   |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1        | 0.87%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1        | 0.87%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1        | 0.87%   |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1        | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.87%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.87%   |
| Alteon Networks Ethernet controller                                 | 1        | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 101      | 62.35%  |
| WiFi     | 59       | 36.42%  |
| Modem    | 1        | 0.62%   |
| Unknown  | 1        | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 70.19%  |
| WiFi     | 31       | 29.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 54.81%  |
| 2     | 38       | 36.54%  |
| 3     | 6        | 5.77%   |
| 0     | 2        | 1.92%   |
| 4     | 1        | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 83       | 79.81%  |
| Yes  | 21       | 20.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 44.23%  |
| Cambridge Silicon Radio         | 9        | 17.31%  |
| Realtek Semiconductor           | 8        | 15.38%  |
| Qualcomm Atheros Communications | 4        | 7.69%   |
| ASUSTek Computer                | 3        | 5.77%   |
| Broadcom                        | 2        | 3.85%   |
| IMC Networks                    | 1        | 1.92%   |
| Edimax Technology               | 1        | 1.92%   |
| Dynex                           | 1        | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 17.31%  |
| Intel AX200 Bluetooth                               | 7        | 13.46%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6        | 11.54%  |
| Intel Wireless-AC 3168 Bluetooth                    | 6        | 11.54%  |
| Realtek Bluetooth Radio                             | 5        | 9.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 5.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 5.77%   |
| Intel AX210 Bluetooth                               | 2        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 3.85%   |
| ASUS Bluetooth Radio                                | 2        | 3.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.92%   |
| Intel Bluetooth Device                              | 1        | 1.92%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.92%   |
| Edimax Bluetooth Device                             | 1        | 1.92%   |
| Dynex BCM20702A0                                    | 1        | 1.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 62       | 30.69%  |
| Intel                     | 50       | 24.75%  |
| Nvidia                    | 49       | 24.26%  |
| C-Media Electronics       | 9        | 4.46%   |
| Logitech                  | 6        | 2.97%   |
| Sony                      | 2        | 0.99%   |
| Sennheiser Communications | 2        | 0.99%   |
| Kingston Technology       | 2        | 0.99%   |
| Generalplus Technology    | 2        | 0.99%   |
| Creative Labs             | 2        | 0.99%   |
| Blue Microphones          | 2        | 0.99%   |
| Yamaha                    | 1        | 0.5%    |
| Trust                     | 1        | 0.5%    |
| Texas Instruments         | 1        | 0.5%    |
| Tenx Technology           | 1        | 0.5%    |
| SteelSeries ApS           | 1        | 0.5%    |
| RODE Microphones          | 1        | 0.5%    |
| Plantronics               | 1        | 0.5%    |
| JMTek                     | 1        | 0.5%    |
| Hewlett-Packard           | 1        | 0.5%    |
| Focusrite-Novation        | 1        | 0.5%    |
| EVGA                      | 1        | 0.5%    |
| DigiTech                  | 1        | 0.5%    |
| Creative Technology       | 1        | 0.5%    |
| Audio-Technica            | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 24       | 9.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 5.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 4.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 3.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 3.66%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 3.25%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8        | 3.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 3.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.44%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 2.44%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 2.03%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 2.03%   |
| C-Media Electronics USB Audio Device                                       | 5        | 2.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 2.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.63%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 4        | 1.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.63%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.22%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.22%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 1.22%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.22%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.81%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.81%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.81%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.81%   |
| Logitech G933 Wireless Headset Dongle                                      | 2        | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.81%   |
| Generalplus Technology IMYB 7.1 Channel                                    | 2        | 0.81%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 0.81%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 0.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 0.81%   |
| Yamaha Steinberg UR22mkII                                                  | 1        | 0.41%   |
| Trust GXT 363 headset                                                      | 1        | 0.41%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.41%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.41%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1        | 0.41%   |
| Sony Wireless Controller                                                   | 1        | 0.41%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.41%   |
| Sennheiser Communications Sennheiser Main Audio                            | 1        | 0.41%   |
| Sennheiser Communications EPOS GSA 70                                      | 1        | 0.41%   |
| RODE Microphones RODE NT-USB                                               | 1        | 0.41%   |
| Plantronics Blackwire 3220 Series                                          | 1        | 0.41%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.41%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.41%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.41%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.41%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.41%   |
| Nvidia Audio device                                                        | 1        | 0.41%   |
| Logitech Headset H390                                                      | 1        | 0.41%   |
| Logitech H600 [Wireless Headset]                                           | 1        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 16       | 25.81%  |
| Corsair             | 8        | 12.9%   |
| Samsung Electronics | 7        | 11.29%  |
| Patriot             | 6        | 9.68%   |
| SK hynix            | 5        | 8.06%   |
| Kingston            | 5        | 8.06%   |
| Crucial             | 5        | 8.06%   |
| Unknown             | 3        | 4.84%   |
| Team                | 3        | 4.84%   |
| Ramaxel Technology  | 1        | 1.61%   |
| Micron Technology   | 1        | 1.61%   |
| Apacer              | 1        | 1.61%   |
| A-DATA Technology   | 1        | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 6        | 8.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s | 3        | 4.23%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 2.82%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s  | 2        | 2.82%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s       | 2        | 2.82%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 2.82%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 2.82%   |
| Corsair RAM CMK32GX4M4B3200C16 8192MB DIMM DDR4 3600MT/s | 2        | 2.82%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 1.41%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                     | 1        | 1.41%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                     | 1        | 1.41%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s    | 1        | 1.41%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 1        | 1.41%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s      | 1        | 1.41%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s       | 1        | 1.41%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 1.41%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 1.41%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s               | 1        | 1.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Samsung RAM M379B5273DH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Samsung RAM M379B5273DH0-YK 4GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s      | 1        | 1.41%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.41%   |
| Patriot RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 1.41%   |
| Patriot RAM 4000 C19 Series 8GB DIMM DDR4 4200MT/s       | 1        | 1.41%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s      | 1        | 1.41%   |
| Patriot RAM 1600 CL10 Series 4GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Micron RAM 4ATF51264HZ-2G6B1 4GB SODIMM DDR4 1200MT/s    | 1        | 1.41%   |
| Kingston RAM X2YH1K-MIE 16GB DIMM DDR4 3200MT/s          | 1        | 1.41%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s   | 1        | 1.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 1        | 1.41%   |
| Kingston RAM KHX2400C11D3/8GX 8192MB DIMM DDR3 2400MT/s  | 1        | 1.41%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 1        | 1.41%   |
| Kingston RAM 9965643-006.A01G 8GB DIMM DDR4 2400MT/s     | 1        | 1.41%   |
| G.Skill RAM F4-4000C18-8GTZRB 8GB DIMM DDR4 4000MT/s     | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s      | 1        | 1.41%   |
| G.Skill RAM F4-3200C14-8GVK 8GB DIMM DDR4 3200MT/s       | 1        | 1.41%   |
| G.Skill RAM F4-2666C19-8GVR 8GB DIMM DDR4 2666MT/s       | 1        | 1.41%   |
| G.Skill RAM F4-2400C15-8GFXR 8GB DIMM DDR4 2666MT/s      | 1        | 1.41%   |
| G.Skill RAM F3-12800CL9-4GBSR0 4GB DIMM 800MT/s          | 1        | 1.41%   |
| Crucial RAM CT51264BA160B.C16F 4096MB DIMM DDR3 1600MT/s | 1        | 1.41%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 1.41%   |
| Crucial RAM BLS8G4D240FSC.16FBD2 8GB DIMM DDR4 2400MT/s  | 1        | 1.41%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 1.41%   |
| Crucial RAM BLE8G4D40BEEAK.M8FE1 8GB DIMM DDR4 2133MT/s  | 1        | 1.41%   |
| Crucial RAM BL8G32C16U4B.M8FE 8192MB DIMM DDR4 3600MT/s  | 1        | 1.41%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 1        | 1.41%   |
| Corsair RAM CMX4GX3M1A1600C11 4GB DIMM DDR3 1600MT/s     | 1        | 1.41%   |
| Corsair RAM CMW32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s   | 1        | 1.41%   |
| Corsair RAM CMK8GX4M2A2133C13 4GB DIMM DDR4 2933MT/s     | 1        | 1.41%   |
| Corsair RAM CMK16GX4M2D3600C18 8192MB DIMM DDR4 3600MT/s | 1        | 1.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 1.41%   |
| Apacer RAM D12.2356WS.001 8GB DIMM DDR4 2667MT/s         | 1        | 1.41%   |
| A-DATA RAM DDR4 3000 8192MB DIMM DDR4 3600MT/s           | 1        | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 38       | 70.37%  |
| DDR3    | 13       | 24.07%  |
| Unknown | 3        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 52       | 96.3%   |
| SODIMM | 2        | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 50.79%  |
| 16384 | 15       | 23.81%  |
| 4096  | 11       | 17.46%  |
| 32768 | 3        | 4.76%   |
| 2048  | 1        | 1.59%   |
| 1024  | 1        | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 13       | 20.31%  |
| 1600  | 9        | 14.06%  |
| 3200  | 8        | 12.5%   |
| 2400  | 6        | 9.38%   |
| 2667  | 5        | 7.81%   |
| 3466  | 4        | 6.25%   |
| 2666  | 3        | 4.69%   |
| 3866  | 2        | 3.13%   |
| 2133  | 2        | 3.13%   |
| 1800  | 2        | 3.13%   |
| 4200  | 1        | 1.56%   |
| 4000  | 1        | 1.56%   |
| 3733  | 1        | 1.56%   |
| 3067  | 1        | 1.56%   |
| 2933  | 1        | 1.56%   |
| 2200  | 1        | 1.56%   |
| 1333  | 1        | 1.56%   |
| 1200  | 1        | 1.56%   |
| 1066  | 1        | 1.56%   |
| 800   | 1        | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Fuji Xerox         | 1        | 20%     |
| Dymo-CoStar        | 1        | 20%     |
| Brother Industries | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP OfficeJet Pro 8020 series     | 1        | 20%     |
| HP DeskJet Plus 4100 series      | 1        | 20%     |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 20%     |
| Dymo-CoStar LabelWriter 450      | 1        | 20%     |
| Brother HL-5370DW series         | 1        | 20%     |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 15       | 60%     |
| Microsoft               | 4        | 16%     |
| Jieli Technology        | 2        | 8%      |
| Z-Star Microelectronics | 1        | 4%      |
| Realtek Semiconductor   | 1        | 4%      |
| Razer USA               | 1        | 4%      |
| MacroSilicon            | 1        | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Logitech Webcam C270              | 3        | 12%     |
| Microsoft LifeCam HD-5000         | 2        | 8%      |
| Logitech Webcam C930e             | 2        | 8%      |
| Logitech HD Webcam C910           | 2        | 8%      |
| Logitech HD Pro Webcam C920       | 2        | 8%      |
| Logitech C922 Pro Stream Webcam   | 2        | 8%      |
| Logitech BRIO Ultra HD Webcam     | 2        | 8%      |
| Jieli USB PHY 2.0                 | 2        | 8%      |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 4%      |
| Realtek FULL HD 1080P Webcam      | 1        | 4%      |
| Razer USA Razer Kiyo Pro          | 1        | 4%      |
| Microsoft Xbox NUI Camera         | 1        | 4%      |
| Microsoft LifeCam HD-3000         | 1        | 4%      |
| MacroSilicon MiraBox Capture      | 1        | 4%      |
| Logitech Webcam C925e             | 1        | 4%      |
| Logitech HD Webcam C510           | 1        | 4%      |

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
| 0     | 51       | 48.11%  |
| 1     | 48       | 45.28%  |
| 2     | 6        | 5.66%   |
| 3     | 1        | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 44       | 70.97%  |
| Net/wireless             | 9        | 14.52%  |
| Graphics card            | 5        | 8.06%   |
| Net/ethernet             | 3        | 4.84%   |
| Unassigned class         | 1        | 1.61%   |

