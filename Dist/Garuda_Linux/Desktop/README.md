Garuda Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | A68HM-PLUS                  | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek   | ProArt X570-CREATOR WIFI    | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek   | M4A89TD PRO USB3            | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| ASRock    | X470 Taichi                 | [acb2659ec1](https://linux-hardware.org/?probe=acb2659ec1) | Feb 19, 2022 |
| ASRock    | X470 Taichi                 | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| HP        | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek   | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP        | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek   | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock    | X470 Taichi                 | [e2b8b640f8](https://linux-hardware.org/?probe=e2b8b640f8) | Feb 11, 2022 |
| ASRock    | B450M Pro4                  | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| ASRock    | B450M Pro4                  | [1b98c3db08](https://linux-hardware.org/?probe=1b98c3db08) | Feb 11, 2022 |
| Lenovo    | 31900058 STD                | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| ASRock    | X470 Taichi                 | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Gigabyte  | MFLP3AP-00\2.x              | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| ASRock    | X470 Taichi                 | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte  | B85-HD3                     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| ASRock    | X470 Taichi                 | [2227a23892](https://linux-hardware.org/?probe=2227a23892) | Jan 20, 2022 |
| ASRock    | 970M Pro3                   | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASRock    | X470 Taichi                 | [6261484b31](https://linux-hardware.org/?probe=6261484b31) | Jan 17, 2022 |
| ASUSTek   | ROG Maximus X CODE          | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI       | Z270 GAMING M5              | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Gigabyte  | AB350-Gaming 3-CF           | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| ASUSTek   | TUF GAMING X570-PLUS        | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Pegatron  | 2AD5                        | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| Gigabyte  | B460M DS3H                  | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| ASRock    | X470 Taichi                 | [37dc48f3f3](https://linux-hardware.org/?probe=37dc48f3f3) | Jan 02, 2022 |
| ASRock    | X470 Taichi                 | [f506cf2d37](https://linux-hardware.org/?probe=f506cf2d37) | Jan 02, 2022 |
| Gigabyte  | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASRock    | X470 Taichi                 | [8d397e7af8](https://linux-hardware.org/?probe=8d397e7af8) | Dec 19, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Gigabyte  | X570 AORUS ELITE WIFI       | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| ASRock    | H77M-ITX                    | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock    | B450M Pro4                  | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo    | ThinkStation S20 4105O1U    | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| Acer      | Aspire TC-895 V:1.0         | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek   | H87M-E                      | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek   | H87M-E                      | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo    | ThinkStation S20 4105O1U    | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo    | ThinkStation S20 4105O1U    | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| ASRock    | X470 Taichi                 | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASRock    | X470 Taichi                 | [dd3bc71908](https://linux-hardware.org/?probe=dd3bc71908) | Nov 26, 2021 |
| ASRock    | X470 Taichi                 | [0f3490892c](https://linux-hardware.org/?probe=0f3490892c) | Nov 14, 2021 |
| ASUSTek   | Rampage IV EXTREME          | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASRock    | X470 Taichi                 | [5ae2157abe](https://linux-hardware.org/?probe=5ae2157abe) | Nov 04, 2021 |
| ASRock    | X470 Taichi                 | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| ASRock    | X470 Taichi                 | [e153488f12](https://linux-hardware.org/?probe=e153488f12) | Oct 28, 2021 |
| ASUSTek   | P8B75-M                     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| ASRock    | X470 Taichi                 | [ec046ac486](https://linux-hardware.org/?probe=ec046ac486) | Oct 24, 2021 |
| MSI       | Z77A-G43                    | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI       | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| ASRock    | X470 Taichi                 | [9b9f21a8eb](https://linux-hardware.org/?probe=9b9f21a8eb) | Oct 19, 2021 |
| MSI       | B450M-A PRO MAX             | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| ASRock    | X470 Taichi                 | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| ASRock    | X470 Taichi                 | [1963eb2e26](https://linux-hardware.org/?probe=1963eb2e26) | Sep 28, 2021 |
| Fujitsu   | D3120-A1 S26361-D3120-A1    | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu   | D3120-A1 S26361-D3120-A1    | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek   | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| MSI       | H310M PRO-VDH PLUS          | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware | 0TYR0X A00                  | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock    | X399 Professional Gaming    | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| ASRock    | X470 Taichi                 | [c18bca5109](https://linux-hardware.org/?probe=c18bca5109) | Aug 16, 2021 |
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
| ASUSTek   | ROG STRIX B550-F GAMING     | [8a7a518013](https://linux-hardware.org/?probe=8a7a518013) | Jun 15, 2021 |
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
| ASRock    | AB350M-HDV                  | [8cc9da4310](https://linux-hardware.org/?probe=8cc9da4310) | Apr 01, 2021 |
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
| ASUSTek   | ROG STRIX B550-F GAMING     | [51244d0897](https://linux-hardware.org/?probe=51244d0897) | Feb 18, 2021 |
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
| Gigabyte  | X570 AORUS PRO WIFI         | [428abb1a9b](https://linux-hardware.org/?probe=428abb1a9b) | Oct 31, 2020 |
| Gigabyte  | X570 AORUS PRO WIFI         | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI       | MPG B550 GAMING EDGE WIF... | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek   | PRIME X399-A                | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell      | 0R6JMP A00                  | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM       | Unknown                     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo    | Board                       | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| ASUSTek   | Maximus VIII FORMULA        | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek   | Maximus VIII FORMULA        | [e8a88c2b81](https://linux-hardware.org/?probe=e8a88c2b81) | Aug 12, 2020 |
| ASUSTek   | Maximus VIII FORMULA        | [7380887fb8](https://linux-hardware.org/?probe=7380887fb8) | Aug 09, 2020 |
| ASUSTek   | Maximus VIII FORMULA        | [faac6d06ac](https://linux-hardware.org/?probe=faac6d06ac) | Aug 09, 2020 |
| ASUSTek   | Maximus VIII FORMULA        | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.4-107-tkg-bmq             | 4        | 4.08%   |
| 5.9.1-zen2-1-zen               | 3        | 3.06%   |
| 5.15.7-zen1-1-zen              | 3        | 3.06%   |
| 5.15.2-zen1-1-zen              | 3        | 3.06%   |
| 5.15.13-zen1-1-zen             | 3        | 3.06%   |
| 5.11.16-zen1-1-zen             | 3        | 3.06%   |
| 5.9.11-zen2-1-zen              | 2        | 2.04%   |
| 5.9.10-zen1-1-zen              | 2        | 2.04%   |
| 5.8.14-zen1-1-zen              | 2        | 2.04%   |
| 5.16.8-zen1-1-zen              | 2        | 2.04%   |
| 5.16.4-zen1-1-zen              | 2        | 2.04%   |
| 5.16.10-zen1-1-zen             | 2        | 2.04%   |
| 5.16.0-zen1-1-zen              | 2        | 2.04%   |
| 5.15.12-zen1-1-zen             | 2        | 2.04%   |
| 5.15.10-zen1-1-zen             | 2        | 2.04%   |
| 5.13.9-zen1-1-zen              | 2        | 2.04%   |
| 5.13.12-zen1-1-zen             | 2        | 2.04%   |
| 5.12.4-zen1-2-zen              | 2        | 2.04%   |
| 5.10.8-112-tkg-bmq             | 2        | 2.04%   |
| 5.9.8-zen1-1-zen               | 1        | 1.02%   |
| 5.9.6-zen1-1-zen               | 1        | 1.02%   |
| 5.9.4-zen1-1-zen               | 1        | 1.02%   |
| 5.9.2-zen1-1-zen               | 1        | 1.02%   |
| 5.9.14-99-tkg-bmq              | 1        | 1.02%   |
| 5.8.5-zen1-1-zen               | 1        | 1.02%   |
| 5.8.10-zen1-1-zen              | 1        | 1.02%   |
| 5.8.0-xanmod1-1-xanmod         | 1        | 1.02%   |
| 5.16.5-zen1-1-zen              | 1        | 1.02%   |
| 5.16.5-243-tkg-pds             | 1        | 1.02%   |
| 5.16.2-zen1-1-zen              | 1        | 1.02%   |
| 5.16.11-zen1-1-zen             | 1        | 1.02%   |
| 5.15.6-zen2-1-zen              | 1        | 1.02%   |
| 5.15.6-225-tkg-pds             | 1        | 1.02%   |
| 5.15.5-zen1-1-zen              | 1        | 1.02%   |
| 5.15.10-229-tkg-pds            | 1        | 1.02%   |
| 5.15.0-212-tkg-pds             | 1        | 1.02%   |
| 5.14.5-zen1-1-zen              | 1        | 1.02%   |
| 5.14.15-zen1-1-zen             | 1        | 1.02%   |
| 5.14.14-zen1-1-zen             | 1        | 1.02%   |
| 5.14.12-zen1-1-zen             | 1        | 1.02%   |
| 5.14.12-207-tkg-cacule         | 1        | 1.02%   |
| 5.14.11-206-tkg-pds            | 1        | 1.02%   |
| 5.13.8-zen1-1-zen              | 1        | 1.02%   |
| 5.13.19-204-tkg-muqss          | 1        | 1.02%   |
| 5.13.19-203-tkg-muqss          | 1        | 1.02%   |
| 5.13.10-190-tkg-bmq            | 1        | 1.02%   |
| 5.12.7-zen1-1-zen              | 1        | 1.02%   |
| 5.12.3-zen1-1-zen              | 1        | 1.02%   |
| 5.12.14-zen1-1-zen             | 1        | 1.02%   |
| 5.12.13-zen1-2-zen             | 1        | 1.02%   |
| 5.12.13-zen1-1-zen             | 1        | 1.02%   |
| 5.12.13-170-tkg-muqss          | 1        | 1.02%   |
| 5.12.12-zen1-1-zen             | 1        | 1.02%   |
| 5.12.12-AMD-znver2             | 1        | 1.02%   |
| 5.12.10-zen1-1-zen             | 1        | 1.02%   |
| 5.11.8-zen1-1-zen              | 1        | 1.02%   |
| 5.11.6-zen1-1-zen              | 1        | 1.02%   |
| 5.11.5-zen1-1-zen              | 1        | 1.02%   |
| 5.11.3-xanmod1-cacule-1-cacule | 1        | 1.02%   |
| 5.11.11-zen1-1-zen             | 1        | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.4  | 4        | 4.08%   |
| 5.9.1   | 3        | 3.06%   |
| 5.15.7  | 3        | 3.06%   |
| 5.15.2  | 3        | 3.06%   |
| 5.15.13 | 3        | 3.06%   |
| 5.15.10 | 3        | 3.06%   |
| 5.12.13 | 3        | 3.06%   |
| 5.11.16 | 3        | 3.06%   |
| 5.9.11  | 2        | 2.04%   |
| 5.9.10  | 2        | 2.04%   |
| 5.8.14  | 2        | 2.04%   |
| 5.16.8  | 2        | 2.04%   |
| 5.16.5  | 2        | 2.04%   |
| 5.16.4  | 2        | 2.04%   |
| 5.16.10 | 2        | 2.04%   |
| 5.16.0  | 2        | 2.04%   |
| 5.15.6  | 2        | 2.04%   |
| 5.15.12 | 2        | 2.04%   |
| 5.14.12 | 2        | 2.04%   |
| 5.13.9  | 2        | 2.04%   |
| 5.13.19 | 2        | 2.04%   |
| 5.13.12 | 2        | 2.04%   |
| 5.12.4  | 2        | 2.04%   |
| 5.12.12 | 2        | 2.04%   |
| 5.10.8  | 2        | 2.04%   |
| 5.9.8   | 1        | 1.02%   |
| 5.9.6   | 1        | 1.02%   |
| 5.9.4   | 1        | 1.02%   |
| 5.9.2   | 1        | 1.02%   |
| 5.9.14  | 1        | 1.02%   |
| 5.8.5   | 1        | 1.02%   |
| 5.8.10  | 1        | 1.02%   |
| 5.8.0   | 1        | 1.02%   |
| 5.16.2  | 1        | 1.02%   |
| 5.16.11 | 1        | 1.02%   |
| 5.15.5  | 1        | 1.02%   |
| 5.15.0  | 1        | 1.02%   |
| 5.14.5  | 1        | 1.02%   |
| 5.14.15 | 1        | 1.02%   |
| 5.14.14 | 1        | 1.02%   |
| 5.14.11 | 1        | 1.02%   |
| 5.13.8  | 1        | 1.02%   |
| 5.13.10 | 1        | 1.02%   |
| 5.12.7  | 1        | 1.02%   |
| 5.12.3  | 1        | 1.02%   |
| 5.12.14 | 1        | 1.02%   |
| 5.12.10 | 1        | 1.02%   |
| 5.11.8  | 1        | 1.02%   |
| 5.11.6  | 1        | 1.02%   |
| 5.11.5  | 1        | 1.02%   |
| 5.11.3  | 1        | 1.02%   |
| 5.11.11 | 1        | 1.02%   |
| 5.11.1  | 1        | 1.02%   |
| 5.11.0  | 1        | 1.02%   |
| 5.10.7  | 1        | 1.02%   |
| 5.10.34 | 1        | 1.02%   |
| 5.10.3  | 1        | 1.02%   |
| 5.10.27 | 1        | 1.02%   |
| 5.10.2  | 1        | 1.02%   |
| 5.10.16 | 1        | 1.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 17.58%  |
| 5.10    | 16       | 17.58%  |
| 5.16    | 12       | 13.19%  |
| 5.12    | 10       | 10.99%  |
| 5.11    | 10       | 10.99%  |
| 5.9     | 9        | 9.89%   |
| 5.13    | 7        | 7.69%   |
| 5.14    | 6        | 6.59%   |
| 5.8     | 5        | 5.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 84       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 52       | 60.47%  |
| KDE     | 19       | 22.09%  |
| GNOME   | 11       | 12.79%  |
| XFCE    | 1        | 1.16%   |
| LXQt    | 1        | 1.16%   |
| i3      | 1        | 1.16%   |
| Unknown | 1        | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 83       | 98.81%  |
| Wayland | 1        | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 51.19%  |
| SDDM    | 36       | 42.86%  |
| LightDM | 3        | 3.57%   |
| GDM     | 2        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 41       | 48.81%  |
| de_DE | 9        | 10.71%  |
| en_GB | 7        | 8.33%   |
| es_ES | 3        | 3.57%   |
| en_AU | 3        | 3.57%   |
| ru_RU | 2        | 2.38%   |
| nl_NL | 2        | 2.38%   |
| fr_BE | 2        | 2.38%   |
| en_CA | 2        | 2.38%   |
| sv_SE | 1        | 1.19%   |
| sk_SK | 1        | 1.19%   |
| pt_BR | 1        | 1.19%   |
| nb_NO | 1        | 1.19%   |
| iu_CA | 1        | 1.19%   |
| it_IT | 1        | 1.19%   |
| fr_FR | 1        | 1.19%   |
| es_VE | 1        | 1.19%   |
| es_AR | 1        | 1.19%   |
| en_ZA | 1        | 1.19%   |
| en_IN | 1        | 1.19%   |
| el_GR | 1        | 1.19%   |
| da_DK | 1        | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 46       | 54.76%  |
| BIOS | 38       | 45.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 82       | 97.62%  |
| Ext4  | 2        | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 42       | 49.41%  |
| GPT     | 39       | 45.88%  |
| MBR     | 4        | 4.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 87.36%  |
| Yes       | 11       | 12.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 69.41%  |
| Yes       | 26       | 30.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 24       | 28.57%  |
| Gigabyte Technology | 15       | 17.86%  |
| MSI                 | 13       | 15.48%  |
| ASRock              | 8        | 9.52%   |
| Hewlett-Packard     | 6        | 7.14%   |
| Lenovo              | 5        | 5.95%   |
| Dell                | 5        | 5.95%   |
| Pegatron            | 2        | 2.38%   |
| OEM                 | 1        | 1.19%   |
| Medion              | 1        | 1.19%   |
| Fujitsu             | 1        | 1.19%   |
| Biostar             | 1        | 1.19%   |
| Alienware           | 1        | 1.19%   |
| Acer                | 1        | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS TUF GAMING X570-PLUS            | 3        | 3.57%   |
| Gigabyte AB350-Gaming 3              | 2        | 2.38%   |
| Dell Inspiron 3668                   | 2        | 2.38%   |
| ASUS ROG STRIX B550-F GAMING         | 2        | 2.38%   |
| Pegatron p7-1030                     | 1        | 1.19%   |
| Pegatron h9-1301es                   | 1        | 1.19%   |
| MSI MS-7C91                          | 1        | 1.19%   |
| MSI MS-7C83                          | 1        | 1.19%   |
| MSI MS-7C52                          | 1        | 1.19%   |
| MSI MS-7C09                          | 1        | 1.19%   |
| MSI MS-7B98                          | 1        | 1.19%   |
| MSI MS-7B09                          | 1        | 1.19%   |
| MSI MS-7A78                          | 1        | 1.19%   |
| MSI MS-7A39                          | 1        | 1.19%   |
| MSI MS-7A32                          | 1        | 1.19%   |
| MSI MS-7818                          | 1        | 1.19%   |
| MSI MS-7816                          | 1        | 1.19%   |
| MSI MS-7758                          | 1        | 1.19%   |
| MSI A320M-HDV R4.0                   | 1        | 1.19%   |
| Medion Akoya P5238 F/C395            | 1        | 1.19%   |
| Lenovo ThinkStation S20 4105O1U      | 1        | 1.19%   |
| Lenovo ThinkCentre M93p 10A90048US   | 1        | 1.19%   |
| Lenovo ThinkCentre M93p 10A90016US   | 1        | 1.19%   |
| Lenovo ThinkCentre M91p 7033CG1      | 1        | 1.19%   |
| Lenovo K450e 10181                   | 1        | 1.19%   |
| HP ProDesk 600 G1 SFF                | 1        | 1.19%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 1.19%   |
| HP Pavilion Gaming Desktop 790-00xx  | 1        | 1.19%   |
| HP EliteDesk 800 G1 DM               | 1        | 1.19%   |
| HP Desktop M01-F0xxx                 | 1        | 1.19%   |
| HP 500-439                           | 1        | 1.19%   |
| Gigabyte X570 AORUS PRO WIFI         | 1        | 1.19%   |
| Gigabyte X570 AORUS ELITE WIFI       | 1        | 1.19%   |
| Gigabyte X470 AORUS ULTRA GAMING     | 1        | 1.19%   |
| Gigabyte P67A-UD3-B3                 | 1        | 1.19%   |
| Gigabyte GB-BKi3(H)A-7100            | 1        | 1.19%   |
| Gigabyte GA-MA790FXT-UD5P            | 1        | 1.19%   |
| Gigabyte B85-HD3                     | 1        | 1.19%   |
| Gigabyte B550I AORUS PRO AX          | 1        | 1.19%   |
| Gigabyte B550 AORUS PRO AC           | 1        | 1.19%   |
| Gigabyte B460MDS3H                   | 1        | 1.19%   |
| Gigabyte B450 AORUS M                | 1        | 1.19%   |
| Gigabyte B450 AORUS ELITE            | 1        | 1.19%   |
| Gigabyte A320M-S2H                   | 1        | 1.19%   |
| Fujitsu ESPRIMO E410                 | 1        | 1.19%   |
| Dell OptiPlex 790                    | 1        | 1.19%   |
| Dell Inspiron 580                    | 1        | 1.19%   |
| Dell Inspiron 3670                   | 1        | 1.19%   |
| Biostar H310MHP                      | 1        | 1.19%   |
| ASUS ROG STRIX X570-E GAMING         | 1        | 1.19%   |
| ASUS ROG Maximus XII FORMULA         | 1        | 1.19%   |
| ASUS ROG Maximus X CODE              | 1        | 1.19%   |
| ASUS ROG CROSSHAIR VII HERO          | 1        | 1.19%   |
| ASUS Rampage IV EXTREME              | 1        | 1.19%   |
| ASUS ProArt X570-CREATOR WIFI        | 1        | 1.19%   |
| ASUS PRIME Z590-A                    | 1        | 1.19%   |
| ASUS PRIME Z370-P                    | 1        | 1.19%   |
| ASUS PRIME X399-A                    | 1        | 1.19%   |
| ASUS PRIME H270-PLUS                 | 1        | 1.19%   |
| ASUS PRIME B450M-K                   | 1        | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS ROG                  | 6        | 7.14%   |
| ASUS PRIME                | 6        | 7.14%   |
| Dell Inspiron             | 4        | 4.76%   |
| Lenovo ThinkCentre        | 3        | 3.57%   |
| ASUS TUF                  | 3        | 3.57%   |
| HP Pavilion               | 2        | 2.38%   |
| Gigabyte X570             | 2        | 2.38%   |
| Gigabyte B450             | 2        | 2.38%   |
| Gigabyte AB350-Gaming     | 2        | 2.38%   |
| ASRock X470               | 2        | 2.38%   |
| Pegatron p7-1030          | 1        | 1.19%   |
| Pegatron h9-1301es        | 1        | 1.19%   |
| MSI MS-7C91               | 1        | 1.19%   |
| MSI MS-7C83               | 1        | 1.19%   |
| MSI MS-7C52               | 1        | 1.19%   |
| MSI MS-7C09               | 1        | 1.19%   |
| MSI MS-7B98               | 1        | 1.19%   |
| MSI MS-7B09               | 1        | 1.19%   |
| MSI MS-7A78               | 1        | 1.19%   |
| MSI MS-7A39               | 1        | 1.19%   |
| MSI MS-7A32               | 1        | 1.19%   |
| MSI MS-7818               | 1        | 1.19%   |
| MSI MS-7816               | 1        | 1.19%   |
| MSI MS-7758               | 1        | 1.19%   |
| MSI A320M-HDV             | 1        | 1.19%   |
| Medion Akoya              | 1        | 1.19%   |
| Lenovo ThinkStation       | 1        | 1.19%   |
| Lenovo K450e              | 1        | 1.19%   |
| HP ProDesk                | 1        | 1.19%   |
| HP EliteDesk              | 1        | 1.19%   |
| HP Desktop                | 1        | 1.19%   |
| HP 500-439                | 1        | 1.19%   |
| Gigabyte X470             | 1        | 1.19%   |
| Gigabyte P67A-UD3-B3      | 1        | 1.19%   |
| Gigabyte GB-BKi3(H)A-7100 | 1        | 1.19%   |
| Gigabyte GA-MA790FXT-UD5P | 1        | 1.19%   |
| Gigabyte B85-HD3          | 1        | 1.19%   |
| Gigabyte B550I            | 1        | 1.19%   |
| Gigabyte B550             | 1        | 1.19%   |
| Gigabyte B460MDS3H        | 1        | 1.19%   |
| Gigabyte A320M-S2H        | 1        | 1.19%   |
| Fujitsu ESPRIMO           | 1        | 1.19%   |
| Dell OptiPlex             | 1        | 1.19%   |
| Biostar H310MHP           | 1        | 1.19%   |
| ASUS Rampage              | 1        | 1.19%   |
| ASUS ProArt               | 1        | 1.19%   |
| ASUS P8B75-M              | 1        | 1.19%   |
| ASUS Maximus              | 1        | 1.19%   |
| ASUS M5A97                | 1        | 1.19%   |
| ASUS M4A89TD              | 1        | 1.19%   |
| ASUS CM5671               | 1        | 1.19%   |
| ASUS All                  | 1        | 1.19%   |
| ASUS A68HM-PLUS           | 1        | 1.19%   |
| ASRock X399               | 1        | 1.19%   |
| ASRock H77M-ITX           | 1        | 1.19%   |
| ASRock G41M-VS3           | 1        | 1.19%   |
| ASRock FM2A88X            | 1        | 1.19%   |
| ASRock B450M              | 1        | 1.19%   |
| ASRock 970M               | 1        | 1.19%   |
| Alienware Aurora          | 1        | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 13       | 15.48%  |
| 2018 | 13       | 15.48%  |
| 2017 | 12       | 14.29%  |
| 2020 | 9        | 10.71%  |
| 2013 | 7        | 8.33%   |
| 2014 | 6        | 7.14%   |
| 2021 | 5        | 5.95%   |
| 2012 | 5        | 5.95%   |
| 2010 | 5        | 5.95%   |
| 2011 | 4        | 4.76%   |
| 2016 | 2        | 2.38%   |
| 2015 | 2        | 2.38%   |
| 2009 | 1        | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 84       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 84       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 24       | 28.57%  |
| 16.01-24.0  | 24       | 28.57%  |
| 8.01-16.0   | 15       | 17.86%  |
| 4.01-8.0    | 10       | 11.9%   |
| 24.01-32.0  | 6        | 7.14%   |
| 64.01-256.0 | 3        | 3.57%   |
| 3.01-4.0    | 2        | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 32       | 37.21%  |
| 3.01-4.0   | 18       | 20.93%  |
| 8.01-16.0  | 17       | 19.77%  |
| 2.01-3.0   | 12       | 13.95%  |
| 1.01-2.0   | 4        | 4.65%   |
| 16.01-24.0 | 3        | 3.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 31.03%  |
| 3      | 18       | 20.69%  |
| 1      | 15       | 17.24%  |
| 4      | 14       | 16.09%  |
| 5      | 7        | 8.05%   |
| 9      | 3        | 3.45%   |
| 6      | 3        | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 65.88%  |
| Yes       | 29       | 34.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 97.62%  |
| No        | 2        | 2.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 55.17%  |
| No        | 39       | 44.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 52.33%  |
| Yes       | 41       | 47.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 29       | 34.52%  |
| Germany      | 10       | 11.9%   |
| UK           | 5        | 5.95%   |
| Spain        | 3        | 3.57%   |
| Russia       | 3        | 3.57%   |
| Italy        | 3        | 3.57%   |
| Canada       | 3        | 3.57%   |
| Australia    | 3        | 3.57%   |
| Sweden       | 2        | 2.38%   |
| Romania      | 2        | 2.38%   |
| Puerto Rico  | 2        | 2.38%   |
| Netherlands  | 2        | 2.38%   |
| France       | 2        | 2.38%   |
| Belgium      | 2        | 2.38%   |
| Venezuela    | 1        | 1.19%   |
| South Africa | 1        | 1.19%   |
| Slovakia     | 1        | 1.19%   |
| Philippines  | 1        | 1.19%   |
| Norway       | 1        | 1.19%   |
| Latvia       | 1        | 1.19%   |
| India        | 1        | 1.19%   |
| Iceland      | 1        | 1.19%   |
| Greece       | 1        | 1.19%   |
| Denmark      | 1        | 1.19%   |
| Chile        | 1        | 1.19%   |
| Brazil       | 1        | 1.19%   |
| Argentina    | 1        | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 2        | 2.3%    |
| Oklahoma City          | 2        | 2.3%    |
| Kingsport              | 2        | 2.3%    |
| Windermere             | 1        | 1.15%   |
| West Des Moines        | 1        | 1.15%   |
| Volzhskiy              | 1        | 1.15%   |
| Volgograd              | 1        | 1.15%   |
| Valence                | 1        | 1.15%   |
| TimiÈ™oara          | 1        | 1.15%   |
| Tekoa                  | 1        | 1.15%   |
| Tampa                  | 1        | 1.15%   |
| Stuttgart              | 1        | 1.15%   |
| Stockton-on-Tees       | 1        | 1.15%   |
| Stockholm              | 1        | 1.15%   |
| Stavropol              | 1        | 1.15%   |
| St Louis               | 1        | 1.15%   |
| Shreveport             | 1        | 1.15%   |
| Satu Mare              | 1        | 1.15%   |
| Sarasota               | 1        | 1.15%   |
| Santa Cruz de Tenerife | 1        | 1.15%   |
| San Juan               | 1        | 1.15%   |
| San Jose               | 1        | 1.15%   |
| Salto da Divisa        | 1        | 1.15%   |
| Riga                   | 1        | 1.15%   |
| Regina                 | 1        | 1.15%   |
| Portland               | 1        | 1.15%   |
| Perth                  | 1        | 1.15%   |
| Orrefors               | 1        | 1.15%   |
| Omaha                  | 1        | 1.15%   |
| Ocean Springs          | 1        | 1.15%   |
| Nunoa                  | 1        | 1.15%   |
| Noss                   | 1        | 1.15%   |
| Norman                 | 1        | 1.15%   |
| Nijmegen               | 1        | 1.15%   |
| Nashua                 | 1        | 1.15%   |
| Naranjito              | 1        | 1.15%   |
| Mumbai                 | 1        | 1.15%   |
| Montevarchi            | 1        | 1.15%   |
| Minden                 | 1        | 1.15%   |
| Milan                  | 1        | 1.15%   |
| Miami                  | 1        | 1.15%   |
| Martigues              | 1        | 1.15%   |
| Marslev                | 1        | 1.15%   |
| Mannheim               | 1        | 1.15%   |
| Ludwigshafen am Rhein  | 1        | 1.15%   |
| Los Angeles            | 1        | 1.15%   |
| London                 | 1        | 1.15%   |
| Leichlingen            | 1        | 1.15%   |
| Langhorne              | 1        | 1.15%   |
| Laguna Hills           | 1        | 1.15%   |
| Kokomo                 | 1        | 1.15%   |
| Kitchener              | 1        | 1.15%   |
| Kings Lynn             | 1        | 1.15%   |
| Karlsruhe              | 1        | 1.15%   |
| Jonesboro              | 1        | 1.15%   |
| Jemappes               | 1        | 1.15%   |
| Illertissen            | 1        | 1.15%   |
| Hamburg                | 1        | 1.15%   |
| Groningen              | 1        | 1.15%   |
| Geneva                 | 1        | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 36       | 56     | 18.09%  |
| WDC                       | 35       | 47     | 17.59%  |
| Samsung Electronics       | 34       | 76     | 17.09%  |
| Toshiba                   | 14       | 16     | 7.04%   |
| Crucial                   | 13       | 17     | 6.53%   |
| Kingston                  | 10       | 16     | 5.03%   |
| Sandisk                   | 8        | 10     | 4.02%   |
| Phison                    | 6        | 7      | 3.02%   |
| Hitachi                   | 4        | 4      | 2.01%   |
| A-DATA Technology         | 4        | 7      | 2.01%   |
| XPG                       | 3        | 4      | 1.51%   |
| Intel                     | 3        | 4      | 1.51%   |
| Unknown                   | 2        | 2      | 1.01%   |
| Transcend                 | 2        | 2      | 1.01%   |
| SPCC                      | 2        | 2      | 1.01%   |
| PNY                       | 2        | 2      | 1.01%   |
| China                     | 2        | 4      | 1.01%   |
| WD MediaMax               | 1        | 1      | 0.5%    |
| USB30                     | 1        | 2      | 0.5%    |
| TO Exter                  | 1        | 1      | 0.5%    |
| SK Hynix                  | 1        | 1      | 0.5%    |
| Silicon Motion            | 1        | 1      | 0.5%    |
| QUMO                      | 1        | 1      | 0.5%    |
| OCZ                       | 1        | 1      | 0.5%    |
| Mushkin                   | 1        | 1      | 0.5%    |
| Micron/Crucial Technology | 1        | 2      | 0.5%    |
| Micron Technology         | 1        | 1      | 0.5%    |
| LITEONIT                  | 1        | 1      | 0.5%    |
| Intenso                   | 1        | 1      | 0.5%    |
| Inateck                   | 1        | 1      | 0.5%    |
| HS-SSD-E100               | 1        | 1      | 0.5%    |
| HGST                      | 1        | 1      | 0.5%    |
| EMTEC                     | 1        | 1      | 0.5%    |
| Corsair                   | 1        | 4      | 0.5%    |
| ASMedia                   | 1        | 2      | 0.5%    |
| Unknown                   | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 970 EVO Plus 500GB   | 5        | 2.14%   |
| Samsung SSD 850 EVO 250GB        | 5        | 2.14%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 1.71%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.28%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 1.28%   |
| Samsung SSD 860 EVO 500GB        | 3        | 1.28%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 1.28%   |
| Samsung NVMe SSD Drive 1TB       | 3        | 1.28%   |
| XPG NVMe SSD Drive 512GB         | 2        | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 0.85%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.85%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 0.85%   |
| Toshiba HDWD110 1TB              | 2        | 0.85%   |
| SPCC Solid State Disk 512GB      | 2        | 0.85%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.85%   |
| Seagate ST3320820AS 320GB        | 2        | 0.85%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.85%   |
| Seagate ST2000DL003-9VT166 2TB   | 2        | 0.85%   |
| Seagate Portable 1TB             | 2        | 0.85%   |
| Seagate Expansion Desk 8TB       | 2        | 0.85%   |
| Seagate Backup+ Hub BK 8TB       | 2        | 0.85%   |
| SanDisk SSD PLUS 1000GB          | 2        | 0.85%   |
| Sandisk NVMe SSD Drive 500GB     | 2        | 0.85%   |
| Samsung SSD 970 EVO 250GB        | 2        | 0.85%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.85%   |
| Samsung NVMe SSD Drive 250GB     | 2        | 0.85%   |
| Phison NVMe SSD Drive 2TB        | 2        | 0.85%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.85%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 0.85%   |
| Crucial CT1000P1SSD8 1TB         | 2        | 0.85%   |
| XPG SPECTRIX S20G 1TB            | 1        | 0.43%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 0.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.43%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1        | 0.43%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1        | 0.43%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1        | 0.43%   |
| WDC WD800BEVS-07RST0 80GB        | 1        | 0.43%   |
| WDC WD6400AAKS-75A7B2 640GB      | 1        | 0.43%   |
| WDC WD6400AAKS-65A7B2 640GB      | 1        | 0.43%   |
| WDC WD5000LPCX-22VHAT1 500GB     | 1        | 0.43%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 1        | 0.43%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 1        | 0.43%   |
| WDC WD5000AAKS-00E4A0 500GB      | 1        | 0.43%   |
| WDC WD4001FAEX-00MJRA0 4TB       | 1        | 0.43%   |
| WDC WD3200AAKS-75L9A0 320GB      | 1        | 0.43%   |
| WDC WD3200AAJS-55B4A0 320GB      | 1        | 0.43%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 1        | 0.43%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1        | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB         | 1        | 0.43%   |
| WDC WD2500JS-55NCB1 250GB        | 1        | 0.43%   |
| WDC WD2500AAKX-75U6AA0 250GB     | 1        | 0.43%   |
| WDC WD2500AAJS-00RYA0 250GB      | 1        | 0.43%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1        | 0.43%   |
| WDC WD20EURS-73TLHY0 2TB         | 1        | 0.43%   |
| WDC WD20EFRX-68AX9N0 2TB         | 1        | 0.43%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 0.43%   |
| WDC WD2000F9YZ-09N20L1 2TB       | 1        | 0.43%   |
| WDC WD1600ADFD-60NLR5 160GB      | 1        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 54     | 40.23%  |
| WDC                 | 28       | 38     | 32.18%  |
| Toshiba             | 12       | 13     | 13.79%  |
| Samsung Electronics | 4        | 4      | 4.6%    |
| Hitachi             | 4        | 4      | 4.6%    |
| Intenso             | 1        | 1      | 1.15%   |
| Inateck             | 1        | 1      | 1.15%   |
| HGST                | 1        | 1      | 1.15%   |
| ASMedia             | 1        | 2      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 28     | 25%     |
| Crucial             | 10       | 12     | 14.71%  |
| Kingston            | 9        | 15     | 13.24%  |
| WDC                 | 5        | 5      | 7.35%   |
| SanDisk             | 5        | 6      | 7.35%   |
| A-DATA Technology   | 4        | 7      | 5.88%   |
| Transcend           | 2        | 2      | 2.94%   |
| SPCC                | 2        | 2      | 2.94%   |
| China               | 2        | 4      | 2.94%   |
| USB30               | 1        | 2      | 1.47%   |
| Unknown             | 1        | 1      | 1.47%   |
| Toshiba             | 1        | 2      | 1.47%   |
| TO Exter            | 1        | 1      | 1.47%   |
| SK Hynix            | 1        | 1      | 1.47%   |
| QUMO                | 1        | 1      | 1.47%   |
| PNY                 | 1        | 1      | 1.47%   |
| OCZ                 | 1        | 1      | 1.47%   |
| Mushkin             | 1        | 1      | 1.47%   |
| Micron Technology   | 1        | 1      | 1.47%   |
| LITEONIT            | 1        | 1      | 1.47%   |
| EMTEC               | 1        | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 62       | 118    | 39.49%  |
| SSD     | 50       | 95     | 31.85%  |
| NVMe    | 38       | 81     | 24.2%   |
| Unknown | 7        | 7      | 4.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 76       | 193    | 59.38%  |
| NVMe | 38       | 81     | 29.69%  |
| SAS  | 14       | 27     | 10.94%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 51       | 95     | 37.5%   |
| 0.51-1.0   | 39       | 51     | 28.68%  |
| 1.01-2.0   | 26       | 39     | 19.12%  |
| 4.01-10.0  | 7        | 10     | 5.15%   |
| 3.01-4.0   | 6        | 7      | 4.41%   |
| 2.01-3.0   | 6        | 10     | 4.41%   |
| 10.01-20.0 | 1        | 1      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 35       | 41.18%  |
| 1001-2000      | 17       | 20%     |
| 2001-3000      | 15       | 17.65%  |
| 501-1000       | 9        | 10.59%  |
| 251-500        | 6        | 7.06%   |
| Unknown        | 2        | 2.35%   |
| 101-250        | 1        | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 17       | 19.1%   |
| 101-250        | 15       | 16.85%  |
| 251-500        | 14       | 15.73%  |
| 501-1000       | 12       | 13.48%  |
| More than 3000 | 9        | 10.11%  |
| 2001-3000      | 9        | 10.11%  |
| 51-100         | 7        | 7.87%   |
| 21-50          | 3        | 3.37%   |
| Unknown        | 2        | 2.25%   |
| 1-20           | 1        | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00E4A0 500GB           | 1        | 1      | 7.69%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1        | 1      | 7.69%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 7.69%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1        | 1      | 7.69%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 7.69%   |
| Seagate ST9250827AS 250GB             | 1        | 1      | 7.69%   |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 7      | 7.69%   |
| OCZ TRION100 480GB SSD                | 1        | 1      | 7.69%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 7.69%   |
| Kingston SH103S3240G 240GB SSD        | 1        | 1      | 7.69%   |
| Hitachi HTS543216L9A300 160GB         | 1        | 1      | 7.69%   |
| Crucial CT960M500SSD1 960GB           | 1        | 1      | 7.69%   |
| A-DATA Technology SU800 1TB SSD       | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 38.46%  |
| Kingston            | 2        | 2      | 15.38%  |
| Seagate             | 1        | 1      | 7.69%   |
| Samsung Electronics | 1        | 7      | 7.69%   |
| OCZ                 | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |
| Crucial             | 1        | 1      | 7.69%   |
| A-DATA Technology   | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 71.43%  |
| Seagate | 1        | 1      | 14.29%  |
| Hitachi | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 7      | 53.85%  |
| SSD  | 5        | 5      | 38.46%  |
| NVMe | 1        | 7      | 7.69%   |

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
| Detected | 52       | 148    | 49.52%  |
| Works    | 40       | 134    | 38.1%   |
| Malfunc  | 13       | 19     | 12.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 45       | 34.09%  |
| AMD                          | 39       | 29.55%  |
| Samsung Electronics          | 18       | 13.64%  |
| Phison Electronics           | 7        | 5.3%    |
| Sandisk                      | 6        | 4.55%   |
| ASMedia Technology           | 4        | 3.03%   |
| Micron/Crucial Technology    | 3        | 2.27%   |
| JMicron Technology           | 2        | 1.52%   |
| ADATA Technology             | 2        | 1.52%   |
| Union Memory (Shenzhen)      | 1        | 0.76%   |
| Toshiba America Info Systems | 1        | 0.76%   |
| Silicon Motion               | 1        | 0.76%   |
| Realtek Semiconductor        | 1        | 0.76%   |
| Marvell Technology Group     | 1        | 0.76%   |
| Kingston Technology Company  | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 15.98%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 9.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 6.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 5.92%   |
| Phison E12 NVMe Controller                                                              | 6        | 3.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.96%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 5        | 2.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 2.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 2.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.37%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 1.78%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.78%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 1.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.78%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.18%   |
| Micron/Crucial NVMe Controller                                                          | 2        | 1.18%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 2        | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.18%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.18%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 1.18%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1        | 0.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 0.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.59%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.59%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.59%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.59%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.59%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.59%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.59%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.59%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.59%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.59%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.59%   |
| Intel SSD 660P Series                                                                   | 1        | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.59%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 0.59%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.59%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.59%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 0.59%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.59%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.59%   |
| Intel 300 Series Chipset Family SATA RAID Controller                                    | 1        | 0.59%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.59%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                                        | 1        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 75       | 58.59%  |
| NVMe | 39       | 30.47%  |
| IDE  | 9        | 7.03%   |
| RAID | 5        | 3.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 45       | 53.57%  |
| AMD    | 39       | 46.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor              | 5        | 5.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 3        | 3.57%   |
| AMD Ryzen 5 3600 6-Core Processor               | 3        | 3.57%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 2        | 2.38%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 2        | 2.38%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 2        | 2.38%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2        | 2.38%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 2.38%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 2        | 2.38%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 2        | 2.38%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 2        | 2.38%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 2        | 2.38%   |
| AMD FX-8350 Eight-Core Processor                | 2        | 2.38%   |
| Intel Xeon CPU W3550 @ 3.07GHz                  | 1        | 1.19%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz             | 1        | 1.19%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 1.19%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 1.19%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 1.19%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1        | 1.19%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 1.19%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 1.19%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1.19%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 1.19%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1        | 1.19%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 1.19%   |
| Intel Core i7-10700F CPU @ 2.90GHz              | 1        | 1.19%   |
| Intel Core i5-9600KF CPU @ 3.70GHz              | 1        | 1.19%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.19%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 1.19%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 1.19%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1        | 1.19%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1        | 1.19%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 1.19%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.19%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 1        | 1.19%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 1.19%   |
| Intel Core i5-10600K CPU @ 4.10GHz              | 1        | 1.19%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 1.19%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 1.19%   |
| Intel Core i3-9100F CPU @ 3.60GHz               | 1        | 1.19%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 1.19%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1        | 1.19%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 1.19%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 1.19%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 1        | 1.19%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz           | 1        | 1.19%   |
| Intel Celeron CPU G3900 @ 2.80GHz               | 1        | 1.19%   |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz        | 1        | 1.19%   |
| AMD Ryzen Threadripper 2970WX 24-Core Processor | 1        | 1.19%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1        | 1.19%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor  | 1        | 1.19%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 1        | 1.19%   |
| AMD Ryzen 9 5900 12-Core Processor              | 1        | 1.19%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 1        | 1.19%   |
| AMD Ryzen 7 1800X Eight-Core Processor          | 1        | 1.19%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 1        | 1.19%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 1.19%   |
| AMD Ryzen 5 1600X Six-Core Processor            | 1        | 1.19%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 16       | 19.05%  |
| Intel Core i7           | 12       | 14.29%  |
| AMD Ryzen 7             | 11       | 13.1%   |
| AMD Ryzen 5             | 11       | 13.1%   |
| Intel Core i3           | 10       | 11.9%   |
| AMD Ryzen 9             | 4        | 4.76%   |
| AMD Ryzen Threadripper  | 3        | 3.57%   |
| AMD Ryzen 3             | 3        | 3.57%   |
| Intel Xeon              | 2        | 2.38%   |
| AMD FX                  | 2        | 2.38%   |
| Other                   | 1        | 1.19%   |
| Intel Pentium Dual-Core | 1        | 1.19%   |
| Intel Core i9           | 1        | 1.19%   |
| Intel Core 2 Quad       | 1        | 1.19%   |
| Intel Celeron           | 1        | 1.19%   |
| AMD Phenom II X6        | 1        | 1.19%   |
| AMD Phenom II X4        | 1        | 1.19%   |
| AMD Phenom II X2        | 1        | 1.19%   |
| AMD A8                  | 1        | 1.19%   |
| AMD A10                 | 1        | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 30       | 35.71%  |
| 6      | 20       | 23.81%  |
| 8      | 13       | 15.48%  |
| 2      | 13       | 15.48%  |
| 12     | 4        | 4.76%   |
| 16     | 2        | 2.38%   |
| 24     | 1        | 1.19%   |
| 10     | 1        | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 84       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 60       | 71.43%  |
| 1      | 24       | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 84       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 42       | 48.84%  |
| 0x08701021 | 6        | 6.98%   |
| 0x306c3    | 5        | 5.81%   |
| 0x0800820d | 5        | 5.81%   |
| 0x906ea    | 3        | 3.49%   |
| 0x206a7    | 3        | 3.49%   |
| 0x506e3    | 2        | 2.33%   |
| 0x306a9    | 2        | 2.33%   |
| 0x08001137 | 2        | 2.33%   |
| 0xa0655    | 1        | 1.16%   |
| 0xa0653    | 1        | 1.16%   |
| 0x906ed    | 1        | 1.16%   |
| 0x906ec    | 1        | 1.16%   |
| 0x906eb    | 1        | 1.16%   |
| 0x906e9    | 1        | 1.16%   |
| 0x106a5    | 1        | 1.16%   |
| 0x1067a    | 1        | 1.16%   |
| 0x0a201204 | 1        | 1.16%   |
| 0x0a201016 | 1        | 1.16%   |
| 0x08701013 | 1        | 1.16%   |
| 0x08101016 | 1        | 1.16%   |
| 0x0810100b | 1        | 1.16%   |
| 0x06003106 | 1        | 1.16%   |
| 0x06000852 | 1        | 1.16%   |
| 0x010000dc | 1        | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 13       | 15.48%  |
| Zen 2       | 12       | 14.29%  |
| Haswell     | 10       | 11.9%   |
| Zen+        | 9        | 10.71%  |
| Zen         | 7        | 8.33%   |
| SandyBridge | 5        | 5.95%   |
| IvyBridge   | 5        | 5.95%   |
| CometLake   | 5        | 5.95%   |
| Zen 3       | 4        | 4.76%   |
| Piledriver  | 3        | 3.57%   |
| K10         | 3        | 3.57%   |
| Skylake     | 2        | 2.38%   |
| Penryn      | 2        | 2.38%   |
| Westmere    | 1        | 1.19%   |
| Steamroller | 1        | 1.19%   |
| Nehalem     | 1        | 1.19%   |
| Unknown     | 1        | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 43       | 46.24%  |
| AMD    | 32       | 34.41%  |
| Intel  | 18       | 19.35%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 7.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 6.32%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 4        | 4.21%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 3.16%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 3.16%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2.11%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 2.11%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.11%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 2.11%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.11%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 2.11%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 2.11%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 2.11%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.11%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 2.11%   |
| Intel HD Graphics 630                                                       | 2        | 2.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.11%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.11%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.05%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.05%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.05%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 1.05%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 1.05%   |
| Nvidia GK106 [GeForce GTX 650 OEM]                                          | 1        | 1.05%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.05%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.05%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.05%   |
| Nvidia GF104 [GeForce GTX 460 SE]                                           | 1        | 1.05%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.05%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.05%   |
| Intel HD Graphics 620                                                       | 1        | 1.05%   |
| Intel HD Graphics 510                                                       | 1        | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.05%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.05%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.05%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.05%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.05%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 1.05%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.05%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 1.05%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                | 1        | 1.05%   |
| AMD Fiji [Radeon R9 FURY / NANO Series]                                     | 1        | 1.05%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 1.05%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 1.05%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.05%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 1.05%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 37       | 44.05%  |
| 1 x AMD        | 29       | 34.52%  |
| 1 x Intel      | 11       | 13.1%   |
| 2 x Nvidia     | 2        | 2.38%   |
| Intel + Nvidia | 2        | 2.38%   |
| AMD + Nvidia   | 2        | 2.38%   |
| Intel + AMD    | 1        | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 48       | 57.14%  |
| Proprietary | 36       | 42.86%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 34.12%  |
| 7.01-8.0   | 16       | 18.82%  |
| 3.01-4.0   | 11       | 12.94%  |
| 1.01-2.0   | 9        | 10.59%  |
| 0.51-1.0   | 6        | 7.06%   |
| 5.01-6.0   | 5        | 5.88%   |
| 8.01-16.0  | 4        | 4.71%   |
| 2.01-3.0   | 2        | 2.35%   |
| 0.01-0.5   | 2        | 2.35%   |
| 16.01-24.0 | 1        | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 17.12%  |
| Dell                 | 13       | 11.71%  |
| Goldstar             | 11       | 9.91%   |
| Acer                 | 10       | 9.01%   |
| Hewlett-Packard      | 7        | 6.31%   |
| BenQ                 | 7        | 6.31%   |
| AOC                  | 7        | 6.31%   |
| Unknown              | 6        | 5.41%   |
| Ancor Communications | 5        | 4.5%    |
| MSI                  | 3        | 2.7%    |
| ASUSTek Computer     | 3        | 2.7%    |
| Vizio                | 2        | 1.8%    |
| Sony                 | 2        | 1.8%    |
| Iiyama               | 2        | 1.8%    |
| Philips              | 1        | 0.9%    |
| ONN                  | 1        | 0.9%    |
| MiTAC                | 1        | 0.9%    |
| Mi                   | 1        | 0.9%    |
| LG Electronics       | 1        | 0.9%    |
| Lenovo Group Limited | 1        | 0.9%    |
| Lenovo               | 1        | 0.9%    |
| Insignia             | 1        | 0.9%    |
| HPN                  | 1        | 0.9%    |
| HKC                  | 1        | 0.9%    |
| Gigabyte Technology  | 1        | 0.9%    |
| Fujitsu Siemens      | 1        | 0.9%    |
| AOpen                | 1        | 0.9%    |
| Alba                 | 1        | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 2.56%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2        | 1.71%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 1.71%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 1.71%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 1.71%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.85%   |
| Vizio D28h-C1 VIZ0095 1360x768 607x345mm 27.5-inch                     | 1        | 0.85%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.85%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.85%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.85%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.85%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.85%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1        | 0.85%   |
| Sony TV SNY1802 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.85%   |
| Sony TV SNY0801 1360x768 1600x900mm 72.3-inch                          | 1        | 0.85%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1        | 0.85%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1        | 0.85%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1        | 0.85%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1        | 0.85%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1        | 0.85%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SAM0FBE 3840x2160 950x540mm 43.0-inch  | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch  | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1        | 0.85%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.85%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                      | 1        | 0.85%   |
| Samsung Electronics LCD Monitor C32R50x                                | 1        | 0.85%   |
| Samsung Electronics LCD Monitor C27F390 3840x1080                      | 1        | 0.85%   |
| Samsung Electronics LCD Monitor C27F390 1920x1080                      | 1        | 0.85%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 1        | 0.85%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1        | 0.85%   |
| Philips LCD Monitor 221E 1920x1080                                     | 1        | 0.85%   |
| ONN ONA18HO015 ONN0101 1920x1080 470x290mm 21.7-inch                   | 1        | 0.85%   |
| MSI MAG341CQ MSI1462 3440x1440 800x330mm 34.1-inch                     | 1        | 0.85%   |
| MSI MAG274R MSI3CA7 1920x1080 597x336mm 27.0-inch                      | 1        | 0.85%   |
| MSI MAG272QR MSI3CA8 2560x1440 597x336mm 27.0-inch                     | 1        | 0.85%   |
| MiTAC KOGAN TV MTC03D7 1920x1080 410x256mm 19.0-inch                   | 1        | 0.85%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 0.85%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 0.85%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1        | 0.85%   |
| Lenovo Group Limited LCD Monitor LEN S27q-10                           | 1        | 0.85%   |
| Insignia NS32D200NA14 BBY32D2 1680x1050 698x392mm 31.5-inch            | 1        | 0.85%   |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                  | 1        | 0.85%   |
| Iiyama PL2790 IVM6616 1920x1080 598x336mm 27.0-inch                    | 1        | 0.85%   |
| HPN LCD Monitor HP Z27 7680x2160                                       | 1        | 0.85%   |
| HPN LCD Monitor HP Z27                                                 | 1        | 0.85%   |
| HKC Checksum: 0x34 (valid) HKC2160 1920x1080 480x270mm 21.7-inch       | 1        | 0.85%   |
| Hewlett-Packard V27e HPN36B1 1920x1080 598x336mm 27.0-inch             | 1        | 0.85%   |
| Hewlett-Packard LCD Monitor LP2475w 3840x1200                          | 1        | 0.85%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch             | 1        | 0.85%   |
| Hewlett-Packard 27w HPN3495 1920x1080 598x336mm 27.0-inch              | 1        | 0.85%   |
| Hewlett-Packard 27o HPN342B 1920x1080 600x340mm 27.2-inch              | 1        | 0.85%   |
| Hewlett-Packard 27mx HPN359E 1920x1080 600x340mm 27.2-inch             | 1        | 0.85%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 1        | 0.85%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch               | 1        | 0.85%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 1        | 0.85%   |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch               | 1        | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 47       | 43.93%  |
| 3840x2160 (4K)     | 12       | 11.21%  |
| Unknown            | 8        | 7.48%   |
| 3840x1080          | 5        | 4.67%   |
| 2560x1440 (QHD)    | 5        | 4.67%   |
| 3440x1440          | 4        | 3.74%   |
| 2560x1080          | 4        | 3.74%   |
| 1680x1050 (WSXGA+) | 3        | 2.8%    |
| 1600x900 (HD+)     | 3        | 2.8%    |
| 1440x900 (WXGA+)   | 3        | 2.8%    |
| 1366x768 (WXGA)    | 3        | 2.8%    |
| 7680x2160          | 2        | 1.87%   |
| 1360x768           | 2        | 1.87%   |
| 1280x1024 (SXGA)   | 2        | 1.87%   |
| 4480x1440          | 1        | 0.93%   |
| 3840x1200          | 1        | 0.93%   |
| 2048x1152          | 1        | 0.93%   |
| 1920x1200 (WUXGA)  | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 20       | 19.61%  |
| Unknown | 19       | 18.63%  |
| 24      | 13       | 12.75%  |
| 23      | 11       | 10.78%  |
| 34      | 5        | 4.9%    |
| 22      | 5        | 4.9%    |
| 19      | 5        | 4.9%    |
| 21      | 4        | 3.92%   |
| 49      | 3        | 2.94%   |
| 40      | 3        | 2.94%   |
| 31      | 3        | 2.94%   |
| 72      | 2        | 1.96%   |
| 28      | 2        | 1.96%   |
| 20      | 2        | 1.96%   |
| 48      | 1        | 0.98%   |
| 43      | 1        | 0.98%   |
| 33      | 1        | 0.98%   |
| 25      | 1        | 0.98%   |
| 17      | 1        | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 39       | 39.8%   |
| Unknown     | 19       | 19.39%  |
| 401-500     | 14       | 14.29%  |
| 601-700     | 8        | 8.16%   |
| 701-800     | 6        | 6.12%   |
| 1001-1500   | 4        | 4.08%   |
| 801-900     | 3        | 3.06%   |
| 1501-2000   | 2        | 2.04%   |
| 351-400     | 1        | 1.02%   |
| 301-350     | 1        | 1.02%   |
| 901-1000    | 1        | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 55       | 59.78%  |
| Unknown | 18       | 19.57%  |
| 16/10   | 9        | 9.78%   |
| 21/9    | 6        | 6.52%   |
| 5/4     | 2        | 2.17%   |
| 32/9    | 2        | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 27.27%  |
| 301-350        | 20       | 20.2%   |
| Unknown        | 19       | 19.19%  |
| 351-500        | 10       | 10.1%   |
| 151-200        | 7        | 7.07%   |
| 501-1000       | 6        | 6.06%   |
| 251-300        | 5        | 5.05%   |
| More than 1000 | 4        | 4.04%   |
| 141-150        | 1        | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 49       | 53.26%  |
| Unknown | 19       | 20.65%  |
| 101-120 | 14       | 15.22%  |
| 1-50    | 4        | 4.35%   |
| 121-160 | 4        | 4.35%   |
| 161-240 | 2        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 51       | 60.71%  |
| 2     | 25       | 29.76%  |
| 3     | 7        | 8.33%   |
| 0     | 1        | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 51       | 38.64%  |
| Intel                 | 41       | 31.06%  |
| Qualcomm Atheros      | 8        | 6.06%   |
| Ralink Technology     | 4        | 3.03%   |
| NetGear               | 4        | 3.03%   |
| Broadcom              | 4        | 3.03%   |
| Linksys               | 3        | 2.27%   |
| Aquantia              | 3        | 2.27%   |
| TP-Link               | 2        | 1.52%   |
| Ralink                | 2        | 1.52%   |
| Samsung Electronics   | 1        | 0.76%   |
| Microsoft             | 1        | 0.76%   |
| MediaTek              | 1        | 0.76%   |
| InterBiometrics       | 1        | 0.76%   |
| Holtek Semiconductor  | 1        | 0.76%   |
| DisplayLink           | 1        | 0.76%   |
| Belkin Components     | 1        | 0.76%   |
| ASIX Electronics      | 1        | 0.76%   |
| Alteon Networks       | 1        | 0.76%   |
| Accton Technology     | 1        | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 41       | 27.7%   |
| Intel I211 Gigabit Network Connection                                     | 11       | 7.43%   |
| Intel Ethernet Controller I225-V                                          | 6        | 4.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6        | 4.05%   |
| Intel Wireless-AC 9260                                                    | 5        | 3.38%   |
| Intel Wi-Fi 6 AX200                                                       | 5        | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 4        | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                         | 4        | 2.7%    |
| Intel Ethernet Connection I217-LM                                         | 4        | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 2.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 2        | 1.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 2        | 1.35%   |
| NetGear A6210                                                             | 2        | 1.35%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2        | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 2        | 1.35%   |
| Intel Ethernet Connection (2) I219-V                                      | 2        | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 2        | 1.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]         | 2        | 1.35%   |
| TP-Link TL WN823N RTL8192EU                                               | 1        | 0.68%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1        | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 0.68%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 0.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 1        | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1        | 0.68%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1        | 0.68%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 0.68%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 1        | 0.68%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1        | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1        | 0.68%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 0.68%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 0.68%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 0.68%   |
| MediaTek Wiko U316AT                                                      | 1        | 0.68%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 0.68%   |
| InterBiometrics Dygma Shortcut Keyboard                                   | 1        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                      | 1        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1        | 0.68%   |
| Intel Centrino Wireless-N 2230                                            | 1        | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 1        | 0.68%   |
| Intel 82579V Gigabit Network Connection                                   | 1        | 0.68%   |
| Holtek SKILLER SGM1                                                       | 1        | 0.68%   |
| DisplayLink ThinkPad USB 3.0 Dock                                         | 1        | 0.68%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                   | 1        | 0.68%   |
| Broadcom Network controller                                               | 1        | 0.68%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                           | 1        | 0.68%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 1        | 0.68%   |
| Belkin Components F5D5050 100Mbps Ethernet                                | 1        | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                             | 1        | 0.68%   |
| Aquantia Ethernet controller                                              | 1        | 0.68%   |
| Alteon Networks Ethernet controller                                       | 1        | 0.68%   |
| Accton SMCWUSB-G 802.11bg                                                 | 1        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 38.89%  |
| Realtek Semiconductor | 11       | 20.37%  |
| Ralink Technology     | 4        | 7.41%   |
| NetGear               | 4        | 7.41%   |
| Qualcomm Atheros      | 3        | 5.56%   |
| Linksys               | 3        | 5.56%   |
| TP-Link               | 2        | 3.7%    |
| Ralink                | 2        | 3.7%    |
| Broadcom              | 2        | 3.7%    |
| Microsoft             | 1        | 1.85%   |
| Accton Technology     | 1        | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6        | 11.11%  |
| Intel Wireless-AC 9260                                                    | 5        | 9.26%   |
| Intel Wi-Fi 6 AX200                                                       | 5        | 9.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 4        | 7.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 5.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 2        | 3.7%    |
| NetGear A6210                                                             | 2        | 3.7%    |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2        | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 2        | 3.7%    |
| TP-Link TL WN823N RTL8192EU                                               | 1        | 1.85%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 1.85%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 1.85%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1        | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.85%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1        | 1.85%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.85%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 1.85%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 1.85%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.85%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 1.85%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1        | 1.85%   |
| Intel Centrino Wireless-N 2230                                            | 1        | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 1        | 1.85%   |
| Broadcom Network controller                                               | 1        | 1.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 1        | 1.85%   |
| Accton SMCWUSB-G 802.11bg                                                 | 1        | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 47       | 51.65%  |
| Intel                 | 27       | 29.67%  |
| Qualcomm Atheros      | 6        | 6.59%   |
| Aquantia              | 3        | 3.3%    |
| Broadcom              | 2        | 2.2%    |
| Samsung Electronics   | 1        | 1.1%    |
| MediaTek              | 1        | 1.1%    |
| DisplayLink           | 1        | 1.1%    |
| Belkin Components     | 1        | 1.1%    |
| ASIX Electronics      | 1        | 1.1%    |
| Alteon Networks       | 1        | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41       | 44.57%  |
| Intel I211 Gigabit Network Connection                             | 11       | 11.96%  |
| Intel Ethernet Controller I225-V                                  | 6        | 6.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 4.35%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 4.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.09%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.09%   |
| MediaTek Wiko U316AT                                              | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.09%   |
| DisplayLink ThinkPad USB 3.0 Dock                                 | 1        | 1.09%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 1.09%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.09%   |
| Belkin Components F5D5050 100Mbps Ethernet                        | 1        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.09%   |
| Aquantia Ethernet controller                                      | 1        | 1.09%   |
| Alteon Networks Ethernet controller                               | 1        | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 62.6%   |
| WiFi     | 47       | 35.88%  |
| Modem    | 1        | 0.76%   |
| Unknown  | 1        | 0.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 71       | 68.93%  |
| WiFi     | 31       | 30.1%   |
| Unknown  | 1        | 0.97%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 48       | 56.47%  |
| 2     | 29       | 34.12%  |
| 3     | 5        | 5.88%   |
| 0     | 2        | 2.35%   |
| 4     | 1        | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 80.95%  |
| Yes  | 16       | 19.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 47.5%   |
| Realtek Semiconductor           | 6        | 15%     |
| Cambridge Silicon Radio         | 6        | 15%     |
| Qualcomm Atheros Communications | 4        | 10%     |
| ASUSTek Computer                | 3        | 7.5%    |
| Dynex                           | 1        | 2.5%    |
| Broadcom                        | 1        | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 15%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 6        | 15%     |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 5        | 12.5%   |
| Intel AX200 Bluetooth                                    | 5        | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 7.5%    |
| Realtek Bluetooth Radio                                  | 3        | 7.5%    |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 7.5%    |
| ASUS Bluetooth Radio                                     | 2        | 5%      |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 2.5%    |
| Intel Bluetooth Device                                   | 1        | 2.5%    |
| Intel AX201 Bluetooth                                    | 1        | 2.5%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 1        | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 47       | 27.65%  |
| Intel                     | 44       | 25.88%  |
| Nvidia                    | 43       | 25.29%  |
| C-Media Electronics       | 7        | 4.12%   |
| Logitech                  | 6        | 3.53%   |
| Sony                      | 2        | 1.18%   |
| Sennheiser Communications | 2        | 1.18%   |
| Generalplus Technology    | 2        | 1.18%   |
| Creative Labs             | 2        | 1.18%   |
| Yamaha                    | 1        | 0.59%   |
| Trust                     | 1        | 0.59%   |
| Texas Instruments         | 1        | 0.59%   |
| Tenx Technology           | 1        | 0.59%   |
| SteelSeries ApS           | 1        | 0.59%   |
| RODE Microphones          | 1        | 0.59%   |
| Plantronics               | 1        | 0.59%   |
| Kingston Technology       | 1        | 0.59%   |
| JMTek                     | 1        | 0.59%   |
| Hewlett-Packard           | 1        | 0.59%   |
| Focusrite-Novation        | 1        | 0.59%   |
| EVGA                      | 1        | 0.59%   |
| DigiTech                  | 1        | 0.59%   |
| Creative Technology       | 1        | 0.59%   |
| Blue Microphones          | 1        | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 8.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11       | 5.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 3.52%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 3.02%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 3.02%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 2.51%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 2.51%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.01%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 2.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.01%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 4        | 2.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.01%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 4        | 2.01%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.51%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 1.51%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.51%   |
| C-Media Electronics SADES Hammer                                           | 3        | 1.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.51%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.51%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.01%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.01%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.01%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.01%   |
| Logitech G933 Wireless Headset Dongle                                      | 2        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.01%   |
| Generalplus Technology USB Audio Device                                    | 2        | 1.01%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2        | 1.01%   |
| Yamaha Steinberg UR22mkII                                                  | 1        | 0.5%    |
| Trust GXT 363 headset                                                      | 1        | 0.5%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.5%    |
| Tenx Technology USB AUDIO                                                  | 1        | 0.5%    |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1        | 0.5%    |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.5%    |
| Sony DualSense wireless controller (PS5)                                   | 1        | 0.5%    |
| Sennheiser Communications Sennheiser Main Audio                            | 1        | 0.5%    |
| Sennheiser Communications EPOS GSA 70                                      | 1        | 0.5%    |
| RODE Microphones RODE NT-USB                                               | 1        | 0.5%    |
| Plantronics Blackwire 3220 Series                                          | 1        | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.5%    |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.5%    |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.5%    |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.5%    |
| Logitech Headset H390                                                      | 1        | 0.5%    |
| Logitech H600 [Wireless Headset]                                           | 1        | 0.5%    |
| Logitech Blue Snowball                                                     | 1        | 0.5%    |
| Logitech Blue Microphones                                                  | 1        | 0.5%    |
| Kingston Technology HyperX Cloud Alpha S                                   | 1        | 0.5%    |
| JMTek USB PnP Audio Device                                                 | 1        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 10       | 20.41%  |
| Corsair             | 7        | 14.29%  |
| Samsung Electronics | 6        | 12.24%  |
| SK Hynix            | 5        | 10.2%   |
| Patriot             | 5        | 10.2%   |
| Kingston            | 4        | 8.16%   |
| Crucial             | 4        | 8.16%   |
| Unknown             | 3        | 6.12%   |
| Team                | 2        | 4.08%   |
| Ramaxel Technology  | 1        | 2.04%   |
| Apacer              | 1        | 2.04%   |
| A-DATA Technology   | 1        | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 4        | 7.02%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s    | 3        | 5.26%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 3.51%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s     | 2        | 3.51%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s       | 2        | 3.51%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 3.51%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 3.51%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 1.75%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                     | 1        | 1.75%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                     | 1        | 1.75%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s    | 1        | 1.75%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s      | 1        | 1.75%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s       | 1        | 1.75%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 1.75%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 1.75%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s               | 1        | 1.75%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s    | 1        | 1.75%   |
| Samsung RAM M379B5273DH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.75%   |
| Samsung RAM M379B5273DH0-YK 4GB DIMM DDR3 1600MT/s       | 1        | 1.75%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s   | 1        | 1.75%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 1.75%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 1.75%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s    | 1        | 1.75%   |
| Patriot RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 1.75%   |
| Patriot RAM 4000 C19 Series 8GB DIMM DDR4 4200MT/s       | 1        | 1.75%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s      | 1        | 1.75%   |
| Kingston RAM X2YH1K-MIE 16GB DIMM DDR4 3200MT/s          | 1        | 1.75%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s   | 1        | 1.75%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s        | 1        | 1.75%   |
| Kingston RAM KHX1866C10D3/4G 4096MB DIMM DDR3 1867MT/s   | 1        | 1.75%   |
| Kingston RAM 9965643-006.A01G 8GB DIMM DDR4 2400MT/s     | 1        | 1.75%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s      | 1        | 1.75%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 1.75%   |
| G.Skill RAM F4-2666C19-8GVR 8GB DIMM DDR4 2666MT/s       | 1        | 1.75%   |
| G.Skill RAM F3-12800CL9-4GBSR0 4GB DIMM 800MT/s          | 1        | 1.75%   |
| Crucial RAM CT51264BA160B.C16F 4096MB DIMM DDR3 1600MT/s | 1        | 1.75%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 1.75%   |
| Crucial RAM BLS8G4D240FSC.16FBD2 8GB DIMM DDR4 2400MT/s  | 1        | 1.75%   |
| Crucial RAM BLE8G4D40BEEAK.M8FE1 8GB DIMM DDR4 2133MT/s  | 1        | 1.75%   |
| Crucial RAM BL8G32C16U4B.M8FE 8GB DIMM DDR4 3600MT/s     | 1        | 1.75%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 1        | 1.75%   |
| Corsair RAM CMX4GX3M1A1600C11 4096MB DIMM DDR3 1600MT/s  | 1        | 1.75%   |
| Corsair RAM CMK8GX4M2A2133C13 4096MB DIMM DDR4 2933MT/s  | 1        | 1.75%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s    | 1        | 1.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 1        | 1.75%   |
| Apacer RAM D12.2356WS.001 8192MB DIMM DDR4 2667MT/s      | 1        | 1.75%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s              | 1        | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 30       | 71.43%  |
| DDR3    | 9        | 21.43%  |
| Unknown | 3        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 41       | 97.62%  |
| SODIMM | 1        | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 49.02%  |
| 16384 | 13       | 25.49%  |
| 4096  | 9        | 17.65%  |
| 32768 | 2        | 3.92%   |
| 2048  | 1        | 1.96%   |
| 1024  | 1        | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 11       | 21.57%  |
| 3200  | 6        | 11.76%  |
| 1600  | 6        | 11.76%  |
| 2667  | 5        | 9.8%    |
| 2400  | 5        | 9.8%    |
| 3466  | 3        | 5.88%   |
| 3866  | 2        | 3.92%   |
| 2666  | 2        | 3.92%   |
| 2133  | 2        | 3.92%   |
| 1800  | 2        | 3.92%   |
| 4200  | 1        | 1.96%   |
| 3067  | 1        | 1.96%   |
| 2933  | 1        | 1.96%   |
| 2200  | 1        | 1.96%   |
| 1333  | 1        | 1.96%   |
| 1066  | 1        | 1.96%   |
| 800   | 1        | 1.96%   |

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
| Logitech                | 10       | 50%     |
| Microsoft               | 4        | 20%     |
| Jieli Technology        | 2        | 10%     |
| Z-Star Microelectronics | 1        | 5%      |
| Realtek Semiconductor   | 1        | 5%      |
| Razer USA               | 1        | 5%      |
| MacroSilicon            | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Microsoft LifeCam HD-5000       | 2        | 10%     |
| Logitech Webcam C930e           | 2        | 10%     |
| Logitech Webcam C270            | 2        | 10%     |
| Logitech HD Webcam C910         | 2        | 10%     |
| Jieli USB PHY 2.0               | 2        | 10%     |
| Z-Star A4 TECH USB 2.0 Camera J | 1        | 5%      |
| Realtek FULL HD 1080P Webcam    | 1        | 5%      |
| Razer USA Razer Kiyo Pro        | 1        | 5%      |
| Microsoft Xbox NUI Camera       | 1        | 5%      |
| Microsoft LifeCam HD-3000       | 1        | 5%      |
| MacroSilicon USB Video          | 1        | 5%      |
| Logitech Webcam C925e           | 1        | 5%      |
| Logitech HD Webcam C510         | 1        | 5%      |
| Logitech HD Pro Webcam C920     | 1        | 5%      |
| Logitech C922 Pro Stream Webcam | 1        | 5%      |

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
| 1     | 42       | 49.41%  |
| 0     | 39       | 45.88%  |
| 2     | 3        | 3.53%   |
| 3     | 1        | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 41       | 80.39%  |
| Net/wireless             | 5        | 9.8%    |
| Graphics card            | 3        | 5.88%   |
| Net/ethernet             | 2        | 3.92%   |

