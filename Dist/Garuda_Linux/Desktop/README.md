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

Total: 169

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI       | H510I PRO WIFI              | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Dell      | 0K3CM7 A00                  | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell      | 0K3CM7 A00                  | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP        | 8767 A                      | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Gigabyte  | 990FXA-UD3                  | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell      | 0K3CM7 A00                  | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| HP        | 2B2C                        | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| ASUSTek   | PRIME X570-P                | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer      | Aspire TC-780               | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek   | PRIME X570-P                | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte  | B550 AORUS ELITE V2         | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| ASUSTek   | PRIME X570-P                | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek   | TUF Gaming X570-PLUS        | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASRock    | A320M-HDV R4.0              | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock    | A320M-HDV R4.0              | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| Gigabyte  | F2A88XM-HD3                 | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| MSI       | B450 TOMAHAWK MAX II        | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| ASUSTek   | PRIME X570-P                | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek   | PRIME X570-P                | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| MSI       | A68HM-E33 V2                | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock    | A520M-HDV                   | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| ASUSTek   | Maximus IX FORMULA          | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| MSI       | B450M PRO-VDH MAX           | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI       | B450 TOMAHAWK MAX II        | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte  | X570 AORUS PRO WIFI         | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| ASUSTek   | ROG STRIX X570-E GAMING     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek   | PRIME B550-PLUS AC-HES      | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASRock    | Z87M Extreme4               | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte  | Z77X-UD3H                   | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI       | B550-A PRO                  | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| MSI       | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| T-bao     | MINI PC V1.0                | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock    | Z87M Extreme4               | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Lenovo    | 3716 SDK0T76463 WIN 3422... | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo    | 3716 SDK0T76463 WIN 3422... | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Gigabyte  | B450 I AORUS PRO WIFI-CF    | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| Dell      | 0WR7PY A01                  | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| ASRock    | B550M Pro4                  | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| ASRock    | X99X Killer                 | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek   | Z97-P                       | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| ASRock    | X99X Killer                 | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek   | P8B75-M                     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HP        | 8433 11                     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| MSI       | B450-A PRO MAX              | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte  | B550 GAMING X V2            | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| ASUSTek   | A68HM-PLUS                  | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| MSI       | MPG B550 GAMING CARBON W... | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| MSI       | MAG B550 TOMAHAWK           | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock    | B450 Gaming K4              | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| ASUSTek   | TUF Gaming X570-PLUS        | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek   | A68HM-PLUS                  | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek   | ProArt X570-CREATOR WIFI    | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek   | M4A89TD PRO USB3            | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP        | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek   | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP        | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek   | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock    | B450M Pro4                  | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| Lenovo    | 31900058 STD                | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| Gigabyte  | MFLP3AP-00\2.x              | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
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
| ASUSTek   | Rampage IV EXTREME          | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| ASUSTek   | TUF Gaming X570-PLUS        | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek   | P8B75-M                     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| MSI       | Z77A-G43                    | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI       | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI       | B450M-A PRO MAX             | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Fujitsu   | D3120-A1 S26361-D3120-A1    | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu   | D3120-A1 S26361-D3120-A1    | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek   | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| MSI       | H310M PRO-VDH PLUS          | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware | 0TYR0X A00                  | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock    | X399 Professional Gaming    | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Medion    | H110H4-EM2                  | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
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
| Garuda Linux Soaring | 58       | 47.54%  |
| Garuda Linux         | 54       | 44.26%  |
| Garuda Linux Rolling | 10       | 8.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Garuda Linux | 118      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.17.1-zen1-1-zen      | 6        | 4.48%   |
| 5.15.7-zen1-1-zen      | 4        | 2.99%   |
| 5.10.4-107-tkg-bmq     | 4        | 2.99%   |
| 5.9.1-zen2-1-zen       | 3        | 2.24%   |
| 5.18.12-zen1-1-zen     | 3        | 2.24%   |
| 5.18.1-zen1-1-zen      | 3        | 2.24%   |
| 5.16.4-zen1-1-zen      | 3        | 2.24%   |
| 5.15.2-zen1-1-zen      | 3        | 2.24%   |
| 5.15.13-zen1-1-zen     | 3        | 2.24%   |
| 5.11.16-zen1-1-zen     | 3        | 2.24%   |
| 6.0.8-zen1-1-zen       | 2        | 1.49%   |
| 6.0.2-zen1-1-zen       | 2        | 1.49%   |
| 5.9.11-zen2-1-zen      | 2        | 1.49%   |
| 5.9.10-zen1-1-zen      | 2        | 1.49%   |
| 5.8.14-zen1-1-zen      | 2        | 1.49%   |
| 5.19.9-zen1-1-zen      | 2        | 1.49%   |
| 5.19.5-zen1-1-zen      | 2        | 1.49%   |
| 5.18.16-zen1-1-zen     | 2        | 1.49%   |
| 5.16.8-zen1-1-zen      | 2        | 1.49%   |
| 5.16.11-zen1-1-zen     | 2        | 1.49%   |
| 5.16.10-zen1-1-zen     | 2        | 1.49%   |
| 5.16.0-zen1-1-zen      | 2        | 1.49%   |
| 5.15.12-zen1-1-zen     | 2        | 1.49%   |
| 5.15.10-zen1-1-zen     | 2        | 1.49%   |
| 5.13.9-zen1-1-zen      | 2        | 1.49%   |
| 5.13.12-zen1-1-zen     | 2        | 1.49%   |
| 5.12.4-zen1-2-zen      | 2        | 1.49%   |
| 5.10.8-112-tkg-bmq     | 2        | 1.49%   |
| 6.0.9-zen1-1-zen       | 1        | 0.75%   |
| 6.0.1-zen2-1-zen       | 1        | 0.75%   |
| 5.9.8-zen1-1-zen       | 1        | 0.75%   |
| 5.9.6-zen1-1-zen       | 1        | 0.75%   |
| 5.9.4-zen1-1-zen       | 1        | 0.75%   |
| 5.9.2-zen1-1-zen       | 1        | 0.75%   |
| 5.9.14-99-tkg-bmq      | 1        | 0.75%   |
| 5.8.5-zen1-1-zen       | 1        | 0.75%   |
| 5.8.10-zen1-1-zen      | 1        | 0.75%   |
| 5.8.0-xanmod1-1-xanmod | 1        | 0.75%   |
| 5.19.7-zen2-1-zen      | 1        | 0.75%   |
| 5.19.2-zen1-1-zen      | 1        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 6        | 4.48%   |
| 5.15.7  | 4        | 2.99%   |
| 5.10.4  | 4        | 2.99%   |
| 5.9.1   | 3        | 2.24%   |
| 5.18.12 | 3        | 2.24%   |
| 5.18.1  | 3        | 2.24%   |
| 5.16.4  | 3        | 2.24%   |
| 5.15.2  | 3        | 2.24%   |
| 5.15.13 | 3        | 2.24%   |
| 5.12.13 | 3        | 2.24%   |
| 5.11.16 | 3        | 2.24%   |
| 6.0.8   | 2        | 1.49%   |
| 6.0.2   | 2        | 1.49%   |
| 5.9.11  | 2        | 1.49%   |
| 5.9.10  | 2        | 1.49%   |
| 5.8.14  | 2        | 1.49%   |
| 5.19.9  | 2        | 1.49%   |
| 5.19.5  | 2        | 1.49%   |
| 5.18.16 | 2        | 1.49%   |
| 5.17.5  | 2        | 1.49%   |
| 5.17.3  | 2        | 1.49%   |
| 5.16.8  | 2        | 1.49%   |
| 5.16.11 | 2        | 1.49%   |
| 5.16.10 | 2        | 1.49%   |
| 5.16.0  | 2        | 1.49%   |
| 5.15.12 | 2        | 1.49%   |
| 5.15.10 | 2        | 1.49%   |
| 5.14.12 | 2        | 1.49%   |
| 5.13.9  | 2        | 1.49%   |
| 5.13.12 | 2        | 1.49%   |
| 5.12.4  | 2        | 1.49%   |
| 5.12.12 | 2        | 1.49%   |
| 5.10.8  | 2        | 1.49%   |
| 6.0.9   | 1        | 0.75%   |
| 6.0.1   | 1        | 0.75%   |
| 5.9.8   | 1        | 0.75%   |
| 5.9.6   | 1        | 0.75%   |
| 5.9.4   | 1        | 0.75%   |
| 5.9.2   | 1        | 0.75%   |
| 5.9.14  | 1        | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 17       | 13.08%  |
| 5.10    | 16       | 12.31%  |
| 5.16    | 15       | 11.54%  |
| 5.18    | 14       | 10.77%  |
| 5.17    | 10       | 7.69%   |
| 5.12    | 10       | 7.69%   |
| 5.11    | 10       | 7.69%   |
| 5.9     | 9        | 6.92%   |
| 5.19    | 7        | 5.38%   |
| 6.0     | 6        | 4.62%   |
| 5.13    | 6        | 4.62%   |
| 5.8     | 5        | 3.85%   |
| 5.14    | 5        | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 118      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 78       | 64.46%  |
| KDE        | 19       | 15.7%   |
| GNOME      | 16       | 13.22%  |
| XFCE       | 1        | 0.83%   |
| X-Cinnamon | 1        | 0.83%   |
| sway       | 1        | 0.83%   |
| LXQt       | 1        | 0.83%   |
| i3         | 1        | 0.83%   |
| Deepin     | 1        | 0.83%   |
| Cinnamon   | 1        | 0.83%   |
| Unknown    | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 110      | 92.44%  |
| Wayland | 4        | 3.36%   |
| Unknown | 3        | 2.52%   |
| Tty     | 2        | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 58       | 48.74%  |
| SDDM    | 50       | 42.02%  |
| LightDM | 6        | 5.04%   |
| GDM     | 4        | 3.36%   |
| GREETD  | 1        | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 57       | 48.31%  |
| de_DE | 14       | 11.86%  |
| en_GB | 11       | 9.32%   |
| es_ES | 4        | 3.39%   |
| en_CA | 4        | 3.39%   |
| en_AU | 4        | 3.39%   |
| pt_BR | 3        | 2.54%   |
| ru_RU | 2        | 1.69%   |
| nl_NL | 2        | 1.69%   |
| it_IT | 2        | 1.69%   |
| fr_BE | 2        | 1.69%   |
| sv_SE | 1        | 0.85%   |
| sk_SK | 1        | 0.85%   |
| nl_BE | 1        | 0.85%   |
| nb_NO | 1        | 0.85%   |
| iu_CA | 1        | 0.85%   |
| fr_FR | 1        | 0.85%   |
| es_VE | 1        | 0.85%   |
| es_AR | 1        | 0.85%   |
| en_ZA | 1        | 0.85%   |
| en_IN | 1        | 0.85%   |
| en_DE | 1        | 0.85%   |
| el_GR | 1        | 0.85%   |
| da_DK | 1        | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 64       | 54.24%  |
| BIOS | 54       | 45.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 116      | 98.31%  |
| Ext4  | 2        | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 58       | 48.74%  |
| GPT     | 57       | 47.9%   |
| MBR     | 4        | 3.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 95       | 79.17%  |
| Yes       | 25       | 20.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 68.07%  |
| Yes       | 38       | 31.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 31       | 26.27%  |
| MSI                 | 22       | 18.64%  |
| Gigabyte Technology | 22       | 18.64%  |
| ASRock              | 13       | 11.02%  |
| Hewlett-Packard     | 8        | 6.78%   |
| Lenovo              | 6        | 5.08%   |
| Dell                | 6        | 5.08%   |
| Pegatron            | 2        | 1.69%   |
| Acer                | 2        | 1.69%   |
| T-bao               | 1        | 0.85%   |
| OEM                 | 1        | 0.85%   |
| Medion              | 1        | 0.85%   |
| Fujitsu             | 1        | 0.85%   |
| Biostar             | 1        | 0.85%   |
| Alienware           | 1        | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS            | 4        | 3.39%   |
| MSI MS-7C91                          | 2        | 1.69%   |
| Gigabyte X570 AORUS PRO WIFI         | 2        | 1.69%   |
| Gigabyte AB350-Gaming 3              | 2        | 1.69%   |
| Dell Inspiron 3668                   | 2        | 1.69%   |
| ASUS ROG STRIX X570-E GAMING         | 2        | 1.69%   |
| ASUS ROG STRIX B550-F GAMING         | 2        | 1.69%   |
| ASUS All Series                      | 2        | 1.69%   |
| T-bao MINI PC                        | 1        | 0.85%   |
| Pegatron p7-1030                     | 1        | 0.85%   |
| Pegatron h9-1301es                   | 1        | 0.85%   |
| MSI MS-7D16                          | 1        | 0.85%   |
| MSI MS-7C90                          | 1        | 0.85%   |
| MSI MS-7C83                          | 1        | 0.85%   |
| MSI MS-7C56                          | 1        | 0.85%   |
| MSI MS-7C52                          | 1        | 0.85%   |
| MSI MS-7C09                          | 1        | 0.85%   |
| MSI MS-7C02                          | 1        | 0.85%   |
| MSI MS-7B98                          | 1        | 0.85%   |
| MSI MS-7B89                          | 1        | 0.85%   |
| MSI MS-7B86                          | 1        | 0.85%   |
| MSI MS-7B09                          | 1        | 0.85%   |
| MSI MS-7A78                          | 1        | 0.85%   |
| MSI MS-7A39                          | 1        | 0.85%   |
| MSI MS-7A38                          | 1        | 0.85%   |
| MSI MS-7A32                          | 1        | 0.85%   |
| MSI MS-7818                          | 1        | 0.85%   |
| MSI MS-7816                          | 1        | 0.85%   |
| MSI MS-7758                          | 1        | 0.85%   |
| MSI MS-7721                          | 1        | 0.85%   |
| MSI A320M-HDV R4.0                   | 1        | 0.85%   |
| Medion Akoya P5238 F/C395            | 1        | 0.85%   |
| Lenovo ThinkStation S20 4105O1U      | 1        | 0.85%   |
| Lenovo ThinkCentre M93p 10A90048US   | 1        | 0.85%   |
| Lenovo ThinkCentre M93p 10A90016US   | 1        | 0.85%   |
| Lenovo ThinkCentre M91p 7033CG1      | 1        | 0.85%   |
| Lenovo Legion T5 26AMR5 90RC018LBX   | 1        | 0.85%   |
| Lenovo K450e 10181                   | 1        | 0.85%   |
| HP ProDesk 600 G1 SFF                | 1        | 0.85%   |
| HP Pavilion Gaming Desktop TG01-1xxx | 1        | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 8        | 6.78%   |
| ASUS PRIME            | 8        | 6.78%   |
| Dell Inspiron         | 4        | 3.39%   |
| ASUS TUF              | 4        | 3.39%   |
| Lenovo ThinkCentre    | 3        | 2.54%   |
| HP Pavilion           | 3        | 2.54%   |
| Gigabyte X570         | 3        | 2.54%   |
| Gigabyte B550         | 3        | 2.54%   |
| Gigabyte B450         | 3        | 2.54%   |
| MSI MS-7C91           | 2        | 1.69%   |
| Gigabyte AB350-Gaming | 2        | 1.69%   |
| Dell OptiPlex         | 2        | 1.69%   |
| ASUS Maximus          | 2        | 1.69%   |
| ASUS All              | 2        | 1.69%   |
| Acer Aspire           | 2        | 1.69%   |
| T-bao MINI            | 1        | 0.85%   |
| Pegatron p7-1030      | 1        | 0.85%   |
| Pegatron h9-1301es    | 1        | 0.85%   |
| MSI MS-7D16           | 1        | 0.85%   |
| MSI MS-7C90           | 1        | 0.85%   |
| MSI MS-7C83           | 1        | 0.85%   |
| MSI MS-7C56           | 1        | 0.85%   |
| MSI MS-7C52           | 1        | 0.85%   |
| MSI MS-7C09           | 1        | 0.85%   |
| MSI MS-7C02           | 1        | 0.85%   |
| MSI MS-7B98           | 1        | 0.85%   |
| MSI MS-7B89           | 1        | 0.85%   |
| MSI MS-7B86           | 1        | 0.85%   |
| MSI MS-7B09           | 1        | 0.85%   |
| MSI MS-7A78           | 1        | 0.85%   |
| MSI MS-7A39           | 1        | 0.85%   |
| MSI MS-7A38           | 1        | 0.85%   |
| MSI MS-7A32           | 1        | 0.85%   |
| MSI MS-7818           | 1        | 0.85%   |
| MSI MS-7816           | 1        | 0.85%   |
| MSI MS-7758           | 1        | 0.85%   |
| MSI MS-7721           | 1        | 0.85%   |
| MSI A320M-HDV         | 1        | 0.85%   |
| Medion Akoya          | 1        | 0.85%   |
| Lenovo ThinkStation   | 1        | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 19       | 16.1%   |
| 2020 | 18       | 15.25%  |
| 2018 | 16       | 13.56%  |
| 2017 | 14       | 11.86%  |
| 2013 | 11       | 9.32%   |
| 2021 | 9        | 7.63%   |
| 2014 | 8        | 6.78%   |
| 2012 | 6        | 5.08%   |
| 2015 | 4        | 3.39%   |
| 2011 | 4        | 3.39%   |
| 2010 | 4        | 3.39%   |
| 2016 | 3        | 2.54%   |
| 2009 | 2        | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 118      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 118      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 118      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 35       | 29.41%  |
| 16.01-24.0  | 34       | 28.57%  |
| 8.01-16.0   | 18       | 15.13%  |
| 4.01-8.0    | 14       | 11.76%  |
| 24.01-32.0  | 9        | 7.56%   |
| 64.01-256.0 | 7        | 5.88%   |
| 3.01-4.0    | 2        | 1.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 49       | 39.52%  |
| 3.01-4.0   | 24       | 19.35%  |
| 8.01-16.0  | 21       | 16.94%  |
| 2.01-3.0   | 18       | 14.52%  |
| 16.01-24.0 | 6        | 4.84%   |
| 1.01-2.0   | 5        | 4.03%   |
| 32.01-64.0 | 1        | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 33       | 26.83%  |
| 3      | 30       | 24.39%  |
| 4      | 21       | 17.07%  |
| 1      | 17       | 13.82%  |
| 5      | 13       | 10.57%  |
| 6      | 4        | 3.25%   |
| 9      | 3        | 2.44%   |
| 14     | 1        | 0.81%   |
| 7      | 1        | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 69.75%  |
| Yes       | 36       | 30.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 116      | 98.31%  |
| No        | 2        | 1.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 55.37%  |
| No        | 54       | 44.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 50%     |
| No        | 60       | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 39       | 33.05%  |
| Germany      | 16       | 13.56%  |
| UK           | 6        | 5.08%   |
| Italy        | 6        | 5.08%   |
| Canada       | 5        | 4.24%   |
| Spain        | 4        | 3.39%   |
| Brazil       | 4        | 3.39%   |
| Australia    | 4        | 3.39%   |
| Sweden       | 3        | 2.54%   |
| Russia       | 3        | 2.54%   |
| Romania      | 3        | 2.54%   |
| Netherlands  | 3        | 2.54%   |
| Belgium      | 3        | 2.54%   |
| Puerto Rico  | 2        | 1.69%   |
| Latvia       | 2        | 1.69%   |
| France       | 2        | 1.69%   |
| Venezuela    | 1        | 0.85%   |
| Ukraine      | 1        | 0.85%   |
| South Africa | 1        | 0.85%   |
| Slovakia     | 1        | 0.85%   |
| Poland       | 1        | 0.85%   |
| Philippines  | 1        | 0.85%   |
| Norway       | 1        | 0.85%   |
| India        | 1        | 0.85%   |
| Iceland      | 1        | 0.85%   |
| Greece       | 1        | 0.85%   |
| Denmark      | 1        | 0.85%   |
| Chile        | 1        | 0.85%   |
| Argentina    | 1        | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Milan                   | 3        | 2.42%   |
| Wasmes                  | 2        | 1.61%   |
| Sydney                  | 2        | 1.61%   |
| St Louis                | 2        | 1.61%   |
| Sao Paulo               | 2        | 1.61%   |
| Riga                    | 2        | 1.61%   |
| Oklahoma City           | 2        | 1.61%   |
| Melbourne               | 2        | 1.61%   |
| Kingsport               | 2        | 1.61%   |
| Dallas                  | 2        | 1.61%   |
| Berlin                  | 2        | 1.61%   |
| York                    | 1        | 0.81%   |
| Weiterstadt             | 1        | 0.81%   |
| Weilen unter den Rinnen | 1        | 0.81%   |
| Voronezh                | 1        | 0.81%   |
| Volzhskiy               | 1        | 0.81%   |
| Västerås              | 1        | 0.81%   |
| Valence                 | 1        | 0.81%   |
| Urbandale               | 1        | 0.81%   |
| Ullerslev               | 1        | 0.81%   |
| Timișoara              | 1        | 0.81%   |
| Taunusstein             | 1        | 0.81%   |
| Stockholm               | 1        | 0.81%   |
| Stavropol               | 1        | 0.81%   |
| Stanley                 | 1        | 0.81%   |
| Sindelfingen            | 1        | 0.81%   |
| Shreveport              | 1        | 0.81%   |
| Sherwood Park           | 1        | 0.81%   |
| Satu Mare               | 1        | 0.81%   |
| Sarasota                | 1        | 0.81%   |
| Santa Cruz de Tenerife  | 1        | 0.81%   |
| San Juan                | 1        | 0.81%   |
| San Jose                | 1        | 0.81%   |
| Reykjavik               | 1        | 0.81%   |
| Reston                  | 1        | 0.81%   |
| Regina                  | 1        | 0.81%   |
| Pune                    | 1        | 0.81%   |
| Providencia             | 1        | 0.81%   |
| Portland                | 1        | 0.81%   |
| Plymouth                | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 58       | 87     | 19.21%  |
| Seagate                     | 50       | 72     | 16.56%  |
| Samsung Electronics         | 49       | 91     | 16.23%  |
| Toshiba                     | 18       | 22     | 5.96%   |
| Crucial                     | 18       | 25     | 5.96%   |
| SanDisk                     | 13       | 20     | 4.3%    |
| Kingston                    | 13       | 21     | 4.3%    |
| Phison                      | 7        | 8      | 2.32%   |
| Hitachi                     | 7        | 7      | 2.32%   |
| Silicon Motion              | 5        | 5      | 1.66%   |
| Intel                       | 5        | 7      | 1.66%   |
| A-DATA Technology           | 5        | 8      | 1.66%   |
| Unknown                     | 4        | 4      | 1.32%   |
| XPG                         | 3        | 4      | 0.99%   |
| SPCC                        | 3        | 3      | 0.99%   |
| PNY                         | 3        | 3      | 0.99%   |
| OCZ                         | 3        | 3      | 0.99%   |
| Micron/Crucial Technology   | 3        | 6      | 0.99%   |
| China                       | 3        | 5      | 0.99%   |
| Transcend                   | 2        | 2      | 0.66%   |
| Team                        | 2        | 3      | 0.66%   |
| Emtec                       | 2        | 4      | 0.66%   |
| WD MediaMax                 | 1        | 1      | 0.33%   |
| USB30                       | 1        | 2      | 0.33%   |
| TO Exter                    | 1        | 1      | 0.33%   |
| T-FORCE                     | 1        | 1      | 0.33%   |
| SK hynix                    | 1        | 1      | 0.33%   |
| Qumo                        | 1        | 1      | 0.33%   |
| Plextor                     | 1        | 1      | 0.33%   |
| Patriot                     | 1        | 1      | 0.33%   |
| Mushkin                     | 1        | 1      | 0.33%   |
| Micron Technology           | 1        | 1      | 0.33%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.33%   |
| LITEONIT                    | 1        | 1      | 0.33%   |
| LITEON                      | 1        | 1      | 0.33%   |
| Intenso                     | 1        | 2      | 0.33%   |
| Inateck                     | 1        | 1      | 0.33%   |
| HS-SSD-E100                 | 1        | 1      | 0.33%   |
| HS-SSD-C100                 | 1        | 1      | 0.33%   |
| HGST                        | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                         | 6        | 1.65%   |
| Samsung NVMe SSD Drive 1TB                        | 6        | 1.65%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5        | 1.38%   |
| Samsung SSD 970 EVO Plus 500GB                    | 5        | 1.38%   |
| Samsung SSD 860 EVO 500GB                         | 5        | 1.38%   |
| Crucial CT1000MX500SSD1 1TB                       | 5        | 1.38%   |
| Seagate ST1000DM010-2EP102 1TB                    | 4        | 1.1%    |
| Samsung NVMe SSD Drive 500GB                      | 4        | 1.1%    |
| WDC WD10EZEX-60WN4A0 1TB                          | 3        | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3        | 0.83%   |
| Toshiba DT01ACA100 1TB                            | 3        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB                    | 3        | 0.83%   |
| Seagate ST3000DM001-1ER166 3TB                    | 3        | 0.83%   |
| Seagate ST2000DL003-9VT166 2TB                    | 3        | 0.83%   |
| SanDisk SSD PLUS 1000GB                           | 3        | 0.83%   |
| SanDisk NVMe SSD Drive 1TB                        | 3        | 0.83%   |
| Samsung SSD 860 EVO 1TB                           | 3        | 0.83%   |
| Samsung SSD 850 EVO 500GB                         | 3        | 0.83%   |
| XPG NVMe SSD Drive 512GB                          | 2        | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2        | 0.55%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                  | 2        | 0.55%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 2        | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 2        | 0.55%   |
| WDC WD20EARX-00PASB0 2TB                          | 2        | 0.55%   |
| WDC WD10EARS-00Y5B1 1TB                           | 2        | 0.55%   |
| WDC WD10EALX-009BA0 1TB                           | 2        | 0.55%   |
| WDC WD10EADS-00M2B0 1TB                           | 2        | 0.55%   |
| Unknown SD/MMC/MS PRO 8GB                         | 2        | 0.55%   |
| Toshiba HDWD110 1TB                               | 2        | 0.55%   |
| Toshiba DT01ACA300 3TB                            | 2        | 0.55%   |
| SPCC Solid State Disk 512GB                       | 2        | 0.55%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 2        | 0.55%   |
| Seagate ST3320820AS 320GB                         | 2        | 0.55%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 2        | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                    | 2        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2        | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB                    | 2        | 0.55%   |
| Seagate Portable 5TB                              | 2        | 0.55%   |
| Seagate Expansion Desk 8TB                        | 2        | 0.55%   |
| Seagate Backup+ Hub BK 8TB                        | 2        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 49       | 70     | 38.89%  |
| WDC                 | 47       | 73     | 37.3%   |
| Toshiba             | 14       | 15     | 11.11%  |
| Hitachi             | 7        | 7      | 5.56%   |
| Samsung Electronics | 4        | 4      | 3.17%   |
| Unknown             | 2        | 2      | 1.59%   |
| Intenso             | 1        | 2      | 0.79%   |
| Inateck             | 1        | 1      | 0.79%   |
| HGST                | 1        | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 42     | 23.81%  |
| Crucial             | 14       | 19     | 13.33%  |
| Kingston            | 11       | 17     | 10.48%  |
| WDC                 | 8        | 8      | 7.62%   |
| SanDisk             | 8        | 12     | 7.62%   |
| A-DATA Technology   | 5        | 8      | 4.76%   |
| Toshiba             | 3        | 6      | 2.86%   |
| SPCC                | 3        | 3      | 2.86%   |
| OCZ                 | 3        | 3      | 2.86%   |
| China               | 3        | 5      | 2.86%   |
| Transcend           | 2        | 2      | 1.9%    |
| Team                | 2        | 3      | 1.9%    |
| PNY                 | 2        | 2      | 1.9%    |
| Emtec               | 2        | 4      | 1.9%    |
| USB30               | 1        | 2      | 0.95%   |
| Unknown             | 1        | 1      | 0.95%   |
| TO Exter            | 1        | 1      | 0.95%   |
| T-FORCE             | 1        | 1      | 0.95%   |
| SK hynix            | 1        | 1      | 0.95%   |
| Qumo                | 1        | 1      | 0.95%   |
| Plextor             | 1        | 1      | 0.95%   |
| Mushkin             | 1        | 1      | 0.95%   |
| Micron Technology   | 1        | 1      | 0.95%   |
| LITEONIT            | 1        | 1      | 0.95%   |
| LITEON              | 1        | 1      | 0.95%   |
| HS-SSD-C100         | 1        | 1      | 0.95%   |
| ASMedia             | 1        | 2      | 0.95%   |
| ADATA SU            | 1        | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 90       | 175    | 38.3%   |
| SSD     | 75       | 150    | 31.91%  |
| NVMe    | 63       | 111    | 26.81%  |
| Unknown | 7        | 7      | 2.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 108      | 300    | 57.14%  |
| NVMe | 63       | 111    | 33.33%  |
| SAS  | 18       | 32     | 9.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 75       | 145    | 36.59%  |
| 0.51-1.0   | 63       | 91     | 30.73%  |
| 1.01-2.0   | 35       | 45     | 17.07%  |
| 2.01-3.0   | 11       | 18     | 5.37%   |
| 3.01-4.0   | 9        | 11     | 4.39%   |
| 4.01-10.0  | 9        | 10     | 4.39%   |
| 10.01-20.0 | 3        | 5      | 1.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 55       | 45.83%  |
| 1001-2000      | 23       | 19.17%  |
| 2001-3000      | 20       | 16.67%  |
| 501-1000       | 11       | 9.17%   |
| 251-500        | 8        | 6.67%   |
| Unknown        | 2        | 1.67%   |
| 101-250        | 1        | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 21       | 16.94%  |
| 501-1000       | 21       | 16.94%  |
| 101-250        | 19       | 15.32%  |
| 1001-2000      | 18       | 14.52%  |
| 2001-3000      | 15       | 12.1%   |
| More than 3000 | 14       | 11.29%  |
| 51-100         | 10       | 8.06%   |
| 21-50          | 3        | 2.42%   |
| Unknown        | 2        | 1.61%   |
| 1-20           | 1        | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00E4A0 500GB        | 1        | 1      | 5%      |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 1      | 5%      |
| WDC WD20EARX-00PASB0 2TB           | 1        | 1      | 5%      |
| WDC WD10EZEX-60ZF5A0 1TB           | 1        | 1      | 5%      |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 5%      |
| WDC WD10EALX-009BA0 1TB            | 1        | 1      | 5%      |
| WDC WD10EADS-22M2B0 1TB            | 1        | 1      | 5%      |
| WDC WD10EADS-00M2B0 1TB            | 1        | 1      | 5%      |
| Seagate ST9250827AS 250GB          | 1        | 1      | 5%      |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1      | 5%      |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 5%      |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 1      | 5%      |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 5%      |
| OCZ TRION100 480GB SSD             | 1        | 1      | 5%      |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 5%      |
| Kingston SH103S3240G 240GB SSD     | 1        | 1      | 5%      |
| Hitachi HTS543216L9A300 160GB      | 1        | 1      | 5%      |
| Hewlett-Packard SSD EX900 500GB    | 1        | 1      | 5%      |
| Crucial CT960M500SSD1 960GB        | 1        | 1      | 5%      |
| A-DATA Technology SU800 1TB SSD    | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 8        | 8      | 40%     |
| Seagate           | 4        | 4      | 20%     |
| Kingston          | 2        | 2      | 10%     |
| SanDisk           | 1        | 1      | 5%      |
| OCZ               | 1        | 1      | 5%      |
| Hitachi           | 1        | 1      | 5%      |
| Hewlett-Packard   | 1        | 1      | 5%      |
| Crucial           | 1        | 1      | 5%      |
| A-DATA Technology | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 8        | 8      | 61.54%  |
| Seagate | 4        | 4      | 30.77%  |
| Hitachi | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 13     | 63.16%  |
| SSD  | 6        | 6      | 31.58%  |
| NVMe | 1        | 1      | 5.26%   |

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
| Detected | 72       | 249    | 48.65%  |
| Works    | 58       | 174    | 39.19%  |
| Malfunc  | 18       | 20     | 12.16%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 64       | 32.32%  |
| Intel                        | 55       | 27.78%  |
| Samsung Electronics          | 27       | 13.64%  |
| SanDisk                      | 10       | 5.05%   |
| Phison Electronics           | 8        | 4.04%   |
| Silicon Motion               | 7        | 3.54%   |
| Micron/Crucial Technology    | 6        | 3.03%   |
| Marvell Technology Group     | 4        | 2.02%   |
| ASMedia Technology           | 4        | 2.02%   |
| Kingston Technology Company  | 3        | 1.52%   |
| ADATA Technology             | 3        | 1.52%   |
| JMicron Technology           | 2        | 1.01%   |
| Union Memory (Shenzhen)      | 1        | 0.51%   |
| Toshiba America Info Systems | 1        | 0.51%   |
| Shenzhen Longsys Electronics | 1        | 0.51%   |
| Realtek Semiconductor        | 1        | 0.51%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 38       | 15.64%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24       | 9.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 16       | 6.58%   |
| AMD 500 Series Chipset SATA Controller                                         | 14       | 5.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12       | 4.94%   |
| Phison E12 NVMe Controller                                                     | 6        | 2.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 2.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 2.06%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4        | 1.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4        | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 1.65%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4        | 1.65%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 1.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 3        | 1.23%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.23%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3        | 1.23%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.23%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.23%   |
| AMD FCH SATA Controller D                                                      | 3        | 1.23%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2        | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.82%   |
| Micron/Crucial NVMe Controller                                                 | 2        | 0.82%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2        | 0.82%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2        | 0.82%   |
| Kingston Company A2000 NVMe SSD                                                | 2        | 0.82%   |
| Intel SSD 660P Series                                                          | 2        | 0.82%   |
| Intel PROSet/Wireless WiFi Software extension                                  | 2        | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 2        | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 2        | 0.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 0.82%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                               | 2        | 0.82%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 106      | 56.68%  |
| NVMe | 64       | 34.22%  |
| IDE  | 10       | 5.35%   |
| RAID | 7        | 3.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 64       | 54.24%  |
| Intel  | 54       | 45.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 5.08%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 4.24%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 4.24%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.54%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 2.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 2.54%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 2.54%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.69%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.69%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.69%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.69%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.69%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.69%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.69%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.69%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.69%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.69%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.69%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.85%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz         | 1        | 0.85%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 0.85%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.85%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.85%   |
| Intel Core i7-6850K CPU @ 3.60GHz           | 1        | 0.85%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.85%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.85%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.85%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.85%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.85%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 0.85%   |
| Intel Core i5-9600KF CPU @ 3.70GHz          | 1        | 0.85%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.85%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.85%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.85%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.85%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 16.95%  |
| AMD Ryzen 7             | 19       | 16.1%   |
| AMD Ryzen 5             | 18       | 15.25%  |
| Intel Core i7           | 14       | 11.86%  |
| Intel Core i3           | 12       | 10.17%  |
| AMD Ryzen 9             | 9        | 7.63%   |
| AMD Ryzen 3             | 5        | 4.24%   |
| Intel Xeon              | 3        | 2.54%   |
| AMD Ryzen Threadripper  | 3        | 2.54%   |
| AMD FX                  | 3        | 2.54%   |
| AMD A10                 | 2        | 1.69%   |
| Other                   | 1        | 0.85%   |
| Intel Pentium Dual-Core | 1        | 0.85%   |
| Intel Core i9           | 1        | 0.85%   |
| Intel Core 2 Quad       | 1        | 0.85%   |
| Intel Celeron           | 1        | 0.85%   |
| AMD Phenom II X6        | 1        | 0.85%   |
| AMD Phenom II X4        | 1        | 0.85%   |
| AMD Phenom II X2        | 1        | 0.85%   |
| AMD Athlon X4           | 1        | 0.85%   |
| AMD A8                  | 1        | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 42       | 35.59%  |
| 6      | 25       | 21.19%  |
| 8      | 21       | 17.8%   |
| 2      | 17       | 14.41%  |
| 12     | 7        | 5.93%   |
| 16     | 4        | 3.39%   |
| 24     | 1        | 0.85%   |
| 10     | 1        | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 118      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 90       | 76.27%  |
| 1      | 28       | 23.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 118      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 50.83%  |
| 0x08701021 | 9        | 7.5%    |
| 0x306c3    | 7        | 5.83%   |
| 0x0800820d | 5        | 4.17%   |
| 0x306a9    | 4        | 3.33%   |
| 0x906ea    | 3        | 2.5%    |
| 0x206a7    | 3        | 2.5%    |
| 0xa0653    | 2        | 1.67%   |
| 0x506e3    | 2        | 1.67%   |
| 0x0a50000c | 2        | 1.67%   |
| 0x08108109 | 2        | 1.67%   |
| 0x0810100b | 2        | 1.67%   |
| 0x08001137 | 2        | 1.67%   |
| 0xa0655    | 1        | 0.83%   |
| 0x906ed    | 1        | 0.83%   |
| 0x906ec    | 1        | 0.83%   |
| 0x906eb    | 1        | 0.83%   |
| 0x906e9    | 1        | 0.83%   |
| 0x106a5    | 1        | 0.83%   |
| 0x1067a    | 1        | 0.83%   |
| 0x0a201204 | 1        | 0.83%   |
| 0x0a201016 | 1        | 0.83%   |
| 0x0a201009 | 1        | 0.83%   |
| 0x08701013 | 1        | 0.83%   |
| 0x08101016 | 1        | 0.83%   |
| 0x06003106 | 1        | 0.83%   |
| 0x06000852 | 1        | 0.83%   |
| 0x010000dc | 1        | 0.83%   |
| 0x00000000 | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 20       | 16.95%  |
| KabyLake    | 14       | 11.86%  |
| Zen+        | 13       | 11.02%  |
| Zen 3       | 13       | 11.02%  |
| Haswell     | 13       | 11.02%  |
| Zen         | 8        | 6.78%   |
| IvyBridge   | 7        | 5.93%   |
| CometLake   | 6        | 5.08%   |
| SandyBridge | 5        | 4.24%   |
| Piledriver  | 4        | 3.39%   |
| Steamroller | 3        | 2.54%   |
| Skylake     | 3        | 2.54%   |
| K10         | 3        | 2.54%   |
| Penryn      | 2        | 1.69%   |
| Westmere    | 1        | 0.85%   |
| Nehalem     | 1        | 0.85%   |
| Broadwell   | 1        | 0.85%   |
| Unknown     | 1        | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 54       | 41.22%  |
| AMD    | 54       | 41.22%  |
| Intel  | 23       | 17.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 13       | 9.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 5.93%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 3.7%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.96%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 4        | 2.96%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 2.96%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 2.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.22%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 2.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.48%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.48%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.48%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.48%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.48%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.48%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.48%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 1.48%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.48%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.48%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.48%   |
| Intel HD Graphics 630                                                       | 2        | 1.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.48%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 2        | 1.48%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.48%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1.48%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.74%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.74%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.74%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 50       | 41.67%  |
| 1 x Nvidia     | 47       | 39.17%  |
| 1 x Intel      | 13       | 10.83%  |
| AMD + Nvidia   | 3        | 2.5%    |
| 2 x Nvidia     | 2        | 1.67%   |
| 2 x AMD        | 2        | 1.67%   |
| Intel + Nvidia | 2        | 1.67%   |
| Intel + AMD    | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 61.34%  |
| Proprietary | 46       | 38.66%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 37.5%   |
| 7.01-8.0   | 22       | 18.33%  |
| 3.01-4.0   | 15       | 12.5%   |
| 1.01-2.0   | 11       | 9.17%   |
| 8.01-16.0  | 7        | 5.83%   |
| 0.51-1.0   | 7        | 5.83%   |
| 5.01-6.0   | 6        | 5%      |
| 0.01-0.5   | 4        | 3.33%   |
| 2.01-3.0   | 2        | 1.67%   |
| 16.01-24.0 | 1        | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 27       | 17.31%  |
| Dell                 | 16       | 10.26%  |
| Acer                 | 16       | 10.26%  |
| Goldstar             | 13       | 8.33%   |
| AOC                  | 10       | 6.41%   |
| Hewlett-Packard      | 9        | 5.77%   |
| Ancor Communications | 9        | 5.77%   |
| BenQ                 | 8        | 5.13%   |
| Unknown              | 6        | 3.85%   |
| MSI                  | 4        | 2.56%   |
| Gigabyte Technology  | 4        | 2.56%   |
| ASUSTek Computer     | 4        | 2.56%   |
| Philips              | 3        | 1.92%   |
| Vizio                | 2        | 1.28%   |
| Sony                 | 2        | 1.28%   |
| NEC Computers        | 2        | 1.28%   |
| Iiyama               | 2        | 1.28%   |
| Xiaomi               | 1        | 0.64%   |
| ViewSonic            | 1        | 0.64%   |
| Toshiba              | 1        | 0.64%   |
| ONN                  | 1        | 0.64%   |
| MiTAC                | 1        | 0.64%   |
| Microstep            | 1        | 0.64%   |
| Mi                   | 1        | 0.64%   |
| LTM                  | 1        | 0.64%   |
| LG Electronics       | 1        | 0.64%   |
| Lenovo Group Limited | 1        | 0.64%   |
| Lenovo               | 1        | 0.64%   |
| Insignia             | 1        | 0.64%   |
| HPN                  | 1        | 0.64%   |
| HKC                  | 1        | 0.64%   |
| Fujitsu Siemens      | 1        | 0.64%   |
| Element              | 1        | 0.64%   |
| AOpen                | 1        | 0.64%   |
| Alba                 | 1        | 0.64%   |
| Unknown              | 1        | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 3        | 1.75%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 2        | 1.17%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 1.17%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.17%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 1.17%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 1.17%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 1.17%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                     | 1        | 0.58%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.58%   |
| Vizio D24h-C1 VIZ0095 1360x768 521x293mm 23.5-inch                     | 1        | 0.58%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1        | 0.58%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.58%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.58%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.58%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.58%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.58%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1        | 0.58%   |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch                        | 1        | 0.58%   |
| Sony TV SNY1802 1920x1080                                              | 1        | 0.58%   |
| Sony TV SNY0801 1360x768                                               | 1        | 0.58%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch      | 1        | 0.58%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1        | 0.58%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 1        | 0.58%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM04D5 1920x540                        | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1        | 0.58%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1        | 0.58%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1        | 0.58%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1        | 0.58%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.58%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch    | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 890x500mm 40.2-inch  | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM07D6 1920x1080 530x300mm 24.0-inch  | 1        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.58%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                      | 1        | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 45.03%  |
| 3840x2160 (4K)     | 17       | 11.26%  |
| Unknown            | 9        | 5.96%   |
| 3440x1440          | 8        | 5.3%    |
| 2560x1440 (QHD)    | 8        | 5.3%    |
| 3840x1080          | 5        | 3.31%   |
| 2560x1080          | 5        | 3.31%   |
| 1680x1050 (WSXGA+) | 5        | 3.31%   |
| 1366x768 (WXGA)    | 5        | 3.31%   |
| 1280x1024 (SXGA)   | 4        | 2.65%   |
| 1600x900 (HD+)     | 3        | 1.99%   |
| 1440x900 (WXGA+)   | 3        | 1.99%   |
| 7680x2160          | 2        | 1.32%   |
| 1920x1200 (WUXGA)  | 2        | 1.32%   |
| 1360x768           | 2        | 1.32%   |
| 9600x2160          | 1        | 0.66%   |
| 4480x1440          | 1        | 0.66%   |
| 3840x1200          | 1        | 0.66%   |
| 2048x1152          | 1        | 0.66%   |
| 1920x540           | 1        | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 30       | 20.27%  |
| 24      | 24       | 16.22%  |
| Unknown | 24       | 16.22%  |
| 23      | 16       | 10.81%  |
| 34      | 8        | 5.41%   |
| 19      | 7        | 4.73%   |
| 22      | 6        | 4.05%   |
| 21      | 6        | 4.05%   |
| 31      | 5        | 3.38%   |
| 72      | 3        | 2.03%   |
| 49      | 3        | 2.03%   |
| 20      | 3        | 2.03%   |
| 40      | 2        | 1.35%   |
| 28      | 2        | 1.35%   |
| 58      | 1        | 0.68%   |
| 54      | 1        | 0.68%   |
| 48      | 1        | 0.68%   |
| 33      | 1        | 0.68%   |
| 32      | 1        | 0.68%   |
| 26      | 1        | 0.68%   |
| 25      | 1        | 0.68%   |
| 18      | 1        | 0.68%   |
| 17      | 1        | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 61       | 43.26%  |
| Unknown     | 24       | 17.02%  |
| 401-500     | 19       | 13.48%  |
| 601-700     | 12       | 8.51%   |
| 701-800     | 10       | 7.09%   |
| 1001-1500   | 6        | 4.26%   |
| 351-400     | 3        | 2.13%   |
| 1501-2000   | 3        | 2.13%   |
| 801-900     | 2        | 1.42%   |
| 301-350     | 1        | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 80       | 60.61%  |
| Unknown | 22       | 16.67%  |
| 16/10   | 14       | 10.61%  |
| 21/9    | 9        | 6.82%   |
| 5/4     | 4        | 3.03%   |
| 32/9    | 3        | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 40       | 28.17%  |
| 301-350        | 31       | 21.83%  |
| Unknown        | 24       | 16.9%   |
| 351-500        | 16       | 11.27%  |
| 151-200        | 10       | 7.04%   |
| 251-300        | 8        | 5.63%   |
| More than 1000 | 7        | 4.93%   |
| 501-1000       | 4        | 2.82%   |
| 141-150        | 2        | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 70       | 53.85%  |
| Unknown | 24       | 18.46%  |
| 101-120 | 19       | 14.62%  |
| 121-160 | 8        | 6.15%   |
| 1-50    | 6        | 4.62%   |
| 161-240 | 3        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 70       | 58.33%  |
| 2     | 36       | 30%     |
| 3     | 11       | 9.17%   |
| 0     | 3        | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 79       | 43.65%  |
| Intel                 | 54       | 29.83%  |
| Qualcomm Atheros      | 11       | 6.08%   |
| Broadcom              | 5        | 2.76%   |
| Ralink Technology     | 4        | 2.21%   |
| NetGear               | 4        | 2.21%   |
| TP-Link               | 3        | 1.66%   |
| Microsoft             | 3        | 1.66%   |
| Linksys               | 3        | 1.66%   |
| Aquantia              | 3        | 1.66%   |
| Ralink                | 2        | 1.1%    |
| MediaTek              | 2        | 1.1%    |
| Samsung Electronics   | 1        | 0.55%   |
| InterBiometrics       | 1        | 0.55%   |
| Holtek Semiconductor  | 1        | 0.55%   |
| DisplayLink           | 1        | 0.55%   |
| Belkin Components     | 1        | 0.55%   |
| ASIX Electronics      | 1        | 0.55%   |
| Alteon Networks       | 1        | 0.55%   |
| Accton Technology     | 1        | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 64       | 31.07%  |
| Intel I211 Gigabit Network Connection                               | 14       | 6.8%    |
| Realtek RTL8125 2.5GbE Controller                                   | 10       | 4.85%   |
| Intel Wi-Fi 6 AX200                                                 | 9        | 4.37%   |
| Intel Wireless-AC 9260                                              | 7        | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6        | 2.91%   |
| Intel Ethernet Controller I225-V                                    | 6        | 2.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 5        | 2.43%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3        | 1.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 3        | 1.46%   |
| Intel Ethernet Connection (2) I219-V                                | 3        | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.97%   |
| NetGear A6210                                                       | 2        | 0.97%   |
| Microsoft XBOX ACC                                                  | 2        | 0.97%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2        | 0.97%   |
| Intel Wireless 7265                                                 | 2        | 0.97%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.49%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1        | 0.49%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.49%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.49%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                              | 1        | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.49%   |
| Ralink Wireless Adapter Canyon CN-WF511                             | 1        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.49%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter              | 1        | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 31       | 42.47%  |
| Realtek Semiconductor | 15       | 20.55%  |
| Ralink Technology     | 4        | 5.48%   |
| Qualcomm Atheros      | 4        | 5.48%   |
| NetGear               | 4        | 5.48%   |
| TP-Link               | 3        | 4.11%   |
| Microsoft             | 3        | 4.11%   |
| Linksys               | 3        | 4.11%   |
| Broadcom              | 3        | 4.11%   |
| Ralink                | 2        | 2.74%   |
| Accton Technology     | 1        | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 9        | 12.33%  |
| Intel Wireless-AC 9260                                                    | 7        | 9.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 6        | 8.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 5        | 6.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 4.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 3        | 4.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 2        | 2.74%   |
| NetGear A6210                                                             | 2        | 2.74%   |
| Microsoft XBOX ACC                                                        | 2        | 2.74%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2        | 2.74%   |
| Intel Wireless 7265                                                       | 2        | 2.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 1        | 1.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1        | 1.37%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 1.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1        | 1.37%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1        | 1.37%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 1.37%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.37%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1        | 1.37%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 1        | 1.37%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 1.37%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 1.37%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.37%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 1.37%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 1.37%   |
| Intel Wireless 3165                                                       | 1        | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1        | 1.37%   |
| Intel Centrino Wireless-N 2230                                            | 1        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 1        | 1.37%   |
| Broadcom Network controller                                               | 1        | 1.37%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                        | 1        | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1        | 1.37%   |
| Accton SMCWUSB-G 802.11bg                                                 | 1        | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 75       | 58.14%  |
| Intel                 | 34       | 26.36%  |
| Qualcomm Atheros      | 8        | 6.2%    |
| Aquantia              | 3        | 2.33%   |
| MediaTek              | 2        | 1.55%   |
| Broadcom              | 2        | 1.55%   |
| Samsung Electronics   | 1        | 0.78%   |
| DisplayLink           | 1        | 0.78%   |
| Belkin Components     | 1        | 0.78%   |
| ASIX Electronics      | 1        | 0.78%   |
| Alteon Networks       | 1        | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 64       | 48.85%  |
| Intel I211 Gigabit Network Connection                               | 14       | 10.69%  |
| Realtek RTL8125 2.5GbE Controller                                   | 10       | 7.63%   |
| Intel Ethernet Controller I225-V                                    | 6        | 4.58%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 3.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 2.29%   |
| Intel Ethernet Connection (2) I219-V                                | 3        | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 2.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 1.53%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.76%   |
| MediaTek TECNO F1                                                   | 1        | 0.76%   |
| MediaTek N152DL                                                     | 1        | 0.76%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                | 1        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 0.76%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 0.76%   |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1        | 0.76%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1        | 0.76%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1        | 0.76%   |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.76%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.76%   |
| Alteon Networks Ethernet controller                                 | 1        | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 63.04%  |
| WiFi     | 66       | 35.87%  |
| Modem    | 1        | 0.54%   |
| Unknown  | 1        | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 71.07%  |
| WiFi     | 35       | 28.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 63       | 53.39%  |
| 2     | 45       | 38.14%  |
| 3     | 7        | 5.93%   |
| 0     | 2        | 1.69%   |
| 4     | 1        | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 78.81%  |
| Yes  | 25       | 21.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 28       | 46.67%  |
| Cambridge Silicon Radio         | 10       | 16.67%  |
| Realtek Semiconductor           | 9        | 15%     |
| Qualcomm Atheros Communications | 4        | 6.67%   |
| ASUSTek Computer                | 4        | 6.67%   |
| Broadcom                        | 3        | 5%      |
| IMC Networks                    | 1        | 1.67%   |
| Dynex                           | 1        | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 10       | 16.67%  |
| Intel AX200 Bluetooth                                    | 9        | 15%     |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 7        | 11.67%  |
| Realtek Bluetooth Radio                                  | 6        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                         | 5        | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 5%      |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 5%      |
| Intel Bluetooth wireless interface                       | 2        | 3.33%   |
| Intel AX210 Bluetooth                                    | 2        | 3.33%   |
| Intel AX201 Bluetooth                                    | 2        | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 3.33%   |
| ASUS Bluetooth Radio                                     | 2        | 3.33%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.67%   |
| IMC Networks Bluetooth Radio                             | 1        | 1.67%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.67%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1        | 1.67%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 1.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 74       | 32.03%  |
| Nvidia                    | 54       | 23.38%  |
| Intel                     | 54       | 23.38%  |
| C-Media Electronics       | 9        | 3.9%    |
| Logitech                  | 6        | 2.6%    |
| Kingston Technology       | 3        | 1.3%    |
| Blue Microphones          | 3        | 1.3%    |
| Trust                     | 2        | 0.87%   |
| Sony                      | 2        | 0.87%   |
| JMTek                     | 2        | 0.87%   |
| Generalplus Technology    | 2        | 0.87%   |
| Creative Labs             | 2        | 0.87%   |
| Yamaha                    | 1        | 0.43%   |
| Texas Instruments         | 1        | 0.43%   |
| Tenx Technology           | 1        | 0.43%   |
| SteelSeries ApS           | 1        | 0.43%   |
| Sennheiser Communications | 1        | 0.43%   |
| Samson Technologies       | 1        | 0.43%   |
| RODE Microphones          | 1        | 0.43%   |
| ROCCAT                    | 1        | 0.43%   |
| Plantronics               | 1        | 0.43%   |
| Hewlett-Packard           | 1        | 0.43%   |
| Harman International      | 1        | 0.43%   |
| Focusrite-Novation        | 1        | 0.43%   |
| EVGA                      | 1        | 0.43%   |
| DSEA A/S                  | 1        | 0.43%   |
| DigiTech                  | 1        | 0.43%   |
| Creative Technology       | 1        | 0.43%   |
| Audio-Technica            | 1        | 0.43%   |
| Alesis                    | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 10.45%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 4.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 4.18%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 3.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 3.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 3.48%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10       | 3.48%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 2.44%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.09%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 1.74%   |
| C-Media Electronics USB Audio Device                                       | 5        | 1.74%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 5        | 1.74%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.05%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 1.05%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 1.05%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.05%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3        | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.05%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.05%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2        | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 2        | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.7%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.7%    |
| Kingston Technology HyperX QuadCast                                        | 2        | 0.7%    |
| JMTek USB PnP Audio Device                                                 | 2        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| G.Skill                      | 18       | 26.47%  |
| Corsair                      | 9        | 13.24%  |
| Samsung Electronics          | 7        | 10.29%  |
| SK hynix                     | 6        | 8.82%   |
| Patriot                      | 6        | 8.82%   |
| Kingston                     | 6        | 8.82%   |
| Crucial                      | 5        | 7.35%   |
| Unknown                      | 3        | 4.41%   |
| Team                         | 2        | 2.94%   |
| Ramaxel Technology           | 1        | 1.47%   |
| Patriot Memory (PDP Systems) | 1        | 1.47%   |
| Micron Technology            | 1        | 1.47%   |
| Apacer                       | 1        | 1.47%   |
| A-DATA Technology            | 1        | 1.47%   |
| Unknown                      | 1        | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                    | 6        | 7.79%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                     | 3        | 3.9%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s                   | 3        | 3.9%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s                 | 2        | 2.6%    |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                    | 2        | 2.6%    |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s                      | 2        | 2.6%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s                   | 2        | 2.6%    |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s                   | 2        | 2.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                   | 2        | 2.6%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 1.3%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                                    | 1        | 1.3%    |
| Unknown RAM Module 1GB DIMM 1066MT/s                                    | 1        | 1.3%    |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                   | 1        | 1.3%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s                     | 1        | 1.3%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s                     | 1        | 1.3%    |
| SK hynix RAM HMT41GU6BFR8C-PB 8192MB DIMM DDR3 1600MT/s                 | 1        | 1.3%    |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s                   | 1        | 1.3%    |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                               | 1        | 1.3%    |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                              | 1        | 1.3%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                   | 1        | 1.3%    |
| Samsung RAM M379B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1.3%    |
| Samsung RAM M379B5273DH0-YK 4GB DIMM DDR3 1600MT/s                      | 1        | 1.3%    |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s                  | 1        | 1.3%    |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1.3%    |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                     | 1        | 1.3%    |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s                     | 1        | 1.3%    |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s                   | 1        | 1.3%    |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                          | 1        | 1.3%    |
| Patriot RAM Module 8GB DIMM DDR4 2666MT/s                               | 1        | 1.3%    |
| Patriot RAM 4000 C19 Series 8GB DIMM DDR4 4200MT/s                      | 1        | 1.3%    |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s                     | 1        | 1.3%    |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s                     | 1        | 1.3%    |
| Patriot Memory (PDP Systems) RAM 2666 C16 Series 8GB DIMM DDR4 2133MT/s | 1        | 1.3%    |
| Micron RAM 4ATF51264HZ-2G6B1 4GB SODIMM DDR4 1200MT/s                   | 1        | 1.3%    |
| Kingston RAM X2YH1K-MIE 16GB DIMM DDR4 3200MT/s                         | 1        | 1.3%    |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s                  | 1        | 1.3%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                       | 1        | 1.3%    |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s                    | 1        | 1.3%    |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s                     | 1        | 1.3%    |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s                  | 1        | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 44       | 72.13%  |
| DDR3    | 14       | 22.95%  |
| Unknown | 3        | 4.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 59       | 96.72%  |
| SODIMM | 2        | 3.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 37       | 52.86%  |
| 16384 | 17       | 24.29%  |
| 4096  | 11       | 15.71%  |
| 32768 | 3        | 4.29%   |
| 2048  | 1        | 1.43%   |
| 1024  | 1        | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 17       | 24.29%  |
| 1600  | 9        | 12.86%  |
| 3200  | 7        | 10%     |
| 2400  | 6        | 8.57%   |
| 2667  | 5        | 7.14%   |
| 3466  | 4        | 5.71%   |
| 2666  | 4        | 5.71%   |
| 3866  | 2        | 2.86%   |
| 2133  | 2        | 2.86%   |
| 1800  | 2        | 2.86%   |
| 4200  | 1        | 1.43%   |
| 4000  | 1        | 1.43%   |
| 3800  | 1        | 1.43%   |
| 3733  | 1        | 1.43%   |
| 3000  | 1        | 1.43%   |
| 2933  | 1        | 1.43%   |
| 2200  | 1        | 1.43%   |
| 1867  | 1        | 1.43%   |
| 1333  | 1        | 1.43%   |
| 1200  | 1        | 1.43%   |
| 1066  | 1        | 1.43%   |
| 800   | 1        | 1.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 33.33%  |
| Dymo-CoStar        | 2        | 33.33%  |
| Fuji Xerox         | 1        | 16.67%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Dymo-CoStar LabelWriter 450      | 2        | 33.33%  |
| HP OfficeJet Pro 8020 series     | 1        | 16.67%  |
| HP DeskJet Plus 4100 series      | 1        | 16.67%  |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 16.67%  |
| Brother HL-5370DW series         | 1        | 16.67%  |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 17       | 60.71%  |
| Microsoft                     | 4        | 14.29%  |
| Jieli Technology              | 2        | 7.14%   |
| Z-Star Microelectronics       | 1        | 3.57%   |
| Sunplus Innovation Technology | 1        | 3.57%   |
| Realtek Semiconductor         | 1        | 3.57%   |
| Razer USA                     | 1        | 3.57%   |
| MacroSilicon                  | 1        | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Logitech Webcam C270              | 3        | 10.71%  |
| Logitech BRIO                     | 3        | 10.71%  |
| Microsoft LifeCam HD-5000         | 2        | 7.14%   |
| Logitech Webcam C930e             | 2        | 7.14%   |
| Logitech HD Webcam C910           | 2        | 7.14%   |
| Logitech HD Pro Webcam C920       | 2        | 7.14%   |
| Logitech C922 Pro Stream Webcam   | 2        | 7.14%   |
| Jieli USB PHY 2.0                 | 2        | 7.14%   |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 3.57%   |
| Sunplus AUSDOM FHD Camera         | 1        | 3.57%   |
| Realtek HD webcam                 | 1        | 3.57%   |
| Razer USA Razer Kiyo Pro          | 1        | 3.57%   |
| Microsoft Xbox NUI Camera         | 1        | 3.57%   |
| Microsoft LifeCam HD-3000         | 1        | 3.57%   |
| MacroSilicon USB Video            | 1        | 3.57%   |
| Logitech Webcam C925e             | 1        | 3.57%   |
| Logitech HD Webcam C510           | 1        | 3.57%   |
| Logitech C920 PRO HD Webcam       | 1        | 3.57%   |

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
| 0     | 61       | 50.83%  |
| 1     | 52       | 43.33%  |
| 2     | 6        | 5%      |
| 3     | 1        | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 49       | 73.13%  |
| Net/wireless             | 9        | 13.43%  |
| Graphics card            | 5        | 7.46%   |
| Net/ethernet             | 3        | 4.48%   |
| Unassigned class         | 1        | 1.49%   |

