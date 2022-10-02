Linux in Denmark - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

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

Total: 374

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MAG Z490 TOMAHAWK           | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| MSI           | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| Unknown       | TB-4000                     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Gigabyte      | P85-D3                      | [06b934d14f](https://linux-hardware.org/?probe=06b934d14f) | Aug 26, 2022 |
| Unknown       | TB-4000                     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Gigabyte      | B460M DS3H V2               | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Unknown       | TB-4000                     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| Gigabyte      | MJPLNAB-00                  | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| HP            | 805D                        | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b0c272ff93](https://linux-hardware.org/?probe=b0c272ff93) | Jun 26, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [eb7445dbdf](https://linux-hardware.org/?probe=eb7445dbdf) | Jun 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [d3fdbc7413](https://linux-hardware.org/?probe=d3fdbc7413) | Jun 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| Unknown       | TB-4000                     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| BESSTAR Te... | HM90                        | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| MSI           | 970A-G43                    | [92dd93dd78](https://linux-hardware.org/?probe=92dd93dd78) | May 24, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Unknown       | TB-4000                     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| MSI           | MS-1T11                     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [91aa85fff9](https://linux-hardware.org/?probe=91aa85fff9) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B250M-A               | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| ASUSTek       | PRIME A320M-K               | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| Dell          | 0KC9NP A01                  | [f9a0fa24f8](https://linux-hardware.org/?probe=f9a0fa24f8) | Feb 18, 2022 |
| ASRock        | FM2A55M-DGS                 | [efe38992bd](https://linux-hardware.org/?probe=efe38992bd) | Feb 15, 2022 |
| Dell          | 0GTK4K A02                  | [466029e620](https://linux-hardware.org/?probe=466029e620) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e63f72d407](https://linux-hardware.org/?probe=e63f72d407) | Feb 07, 2022 |
| Medion        | MS-7800                     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40ed6ce0c5](https://linux-hardware.org/?probe=40ed6ce0c5) | Feb 04, 2022 |
| Unknown       | TB-4000                     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b8f4a15736](https://linux-hardware.org/?probe=b8f4a15736) | Jan 25, 2022 |
| ASUSTek       | P8H67-M                     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| Gigabyte      | B460M AORUS PRO             | [1e301a4129](https://linux-hardware.org/?probe=1e301a4129) | Jan 19, 2022 |
| Acer          | Predator G6-710             | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASUSTek       | P8H67-M                     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| MSI           | A68HM GRENADE               | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| MSI           | X470 GAMING PRO             | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| HP            | 3031h                       | [8a8888c824](https://linux-hardware.org/?probe=8a8888c824) | Dec 17, 2021 |
| ABIT          | I-G31                       | [048b7bcf6a](https://linux-hardware.org/?probe=048b7bcf6a) | Dec 13, 2021 |
| Dell          | 0YXT71 A01                  | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| ASUSTek       | Z170-P                      | [6e857bc210](https://linux-hardware.org/?probe=6e857bc210) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASUSTek       | PRIME Z390-A                | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| HP            | 3031h                       | [68cf960e7f](https://linux-hardware.org/?probe=68cf960e7f) | Dec 02, 2021 |
| HP            | 3031h                       | [1c49cd6404](https://linux-hardware.org/?probe=1c49cd6404) | Dec 02, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Acer          | Aspire X3995                | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| ASRock        | Z170 Gaming K4              | [53281d6c95](https://linux-hardware.org/?probe=53281d6c95) | Nov 17, 2021 |
| Dell          | 0YXT71 A01                  | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| T-bao         | MINI PC V1.0                | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [be8c7e44de](https://linux-hardware.org/?probe=be8c7e44de) | Oct 23, 2021 |
| MSI           | Z77A-G45                    | [7a31ca9e22](https://linux-hardware.org/?probe=7a31ca9e22) | Oct 23, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [a36474b9ff](https://linux-hardware.org/?probe=a36474b9ff) | Oct 04, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASRock        | H470M-ITX/ac                | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [201176552b](https://linux-hardware.org/?probe=201176552b) | Sep 21, 2021 |
| Medion        | B360H4-EM V1.0              | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Dell          | 0XCR8D A02                  | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| ASRock        | P55M Pro                    | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASRock        | 980DE3/U3S3                 | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Medion        | MS-7616                     | [cbd20c24d8](https://linux-hardware.org/?probe=cbd20c24d8) | Aug 20, 2021 |
| HP            | 212B                        | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | P8B75-M                     | [4d29ffa0f7](https://linux-hardware.org/?probe=4d29ffa0f7) | Aug 03, 2021 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4135f29492](https://linux-hardware.org/?probe=4135f29492) | Aug 02, 2021 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [59cd9e3edd](https://linux-hardware.org/?probe=59cd9e3edd) | Aug 01, 2021 |
| Pegatron      | 2AB6                        | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | [51f83ebd4a](https://linux-hardware.org/?probe=51f83ebd4a) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Lenovo        | ThinkCentre Edge71 1577G... | [cf7f13e31c](https://linux-hardware.org/?probe=cf7f13e31c) | Jul 29, 2021 |
| ASRock        | H310CM-DVS                  | [5ae2994458](https://linux-hardware.org/?probe=5ae2994458) | Jul 28, 2021 |
| Medion        | Z370H4-EM                   | [f19570a630](https://linux-hardware.org/?probe=f19570a630) | Jul 24, 2021 |
| Shuttle       | FH67                        | [611a7c28dc](https://linux-hardware.org/?probe=611a7c28dc) | Jul 22, 2021 |
| Shuttle       | FH67                        | [3d3fb6c381](https://linux-hardware.org/?probe=3d3fb6c381) | Jul 22, 2021 |
| ASRock        | 980DE3/U3S3                 | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5fcfefa75a](https://linux-hardware.org/?probe=5fcfefa75a) | Jul 19, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [0c0d9cc784](https://linux-hardware.org/?probe=0c0d9cc784) | Jul 15, 2021 |
| ASUSTek       | PRIME Z370-A                | [208a9ee715](https://linux-hardware.org/?probe=208a9ee715) | Jun 23, 2021 |
| ASUSTek       | PRIME Z370-A                | [86fce52939](https://linux-hardware.org/?probe=86fce52939) | Jun 23, 2021 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [ca43a33e1d](https://linux-hardware.org/?probe=ca43a33e1d) | Jun 18, 2021 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [4a0a83693b](https://linux-hardware.org/?probe=4a0a83693b) | Jun 14, 2021 |
| ASRock        | P55M Pro                    | [cac3198045](https://linux-hardware.org/?probe=cac3198045) | Jun 14, 2021 |
| HP            | 212B                        | [b72ab2aea5](https://linux-hardware.org/?probe=b72ab2aea5) | Jun 09, 2021 |
| ASRock        | P55M Pro                    | [b994c1917a](https://linux-hardware.org/?probe=b994c1917a) | Jun 03, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| MSI           | Z87 MPOWER                  | [848def4822](https://linux-hardware.org/?probe=848def4822) | May 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [e0217f85a6](https://linux-hardware.org/?probe=e0217f85a6) | May 28, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| ASUSTek       | PRIME B450M-A               | [787c1b3a8c](https://linux-hardware.org/?probe=787c1b3a8c) | May 26, 2021 |
| ASUSTek       | B85M-G                      | [92f19ca1e6](https://linux-hardware.org/?probe=92f19ca1e6) | May 25, 2021 |
| ASUSTek       | NARRA2                      | [0b2cf24d70](https://linux-hardware.org/?probe=0b2cf24d70) | May 25, 2021 |
| Medion        | MS-7646                     | [799be90f9c](https://linux-hardware.org/?probe=799be90f9c) | May 11, 2021 |
| ASRock        | J4105-ITX                   | [2cb8135a58](https://linux-hardware.org/?probe=2cb8135a58) | May 08, 2021 |
| ASUSTek       | PRIME B450M-K               | [a8271c73ee](https://linux-hardware.org/?probe=a8271c73ee) | May 02, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9e0202e76a](https://linux-hardware.org/?probe=9e0202e76a) | Apr 27, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [31cb6e83ed](https://linux-hardware.org/?probe=31cb6e83ed) | Apr 19, 2021 |
| Acer          | Veriton M275                | [246a662951](https://linux-hardware.org/?probe=246a662951) | Apr 17, 2021 |
| Gigabyte      | B75M-D3H                    | [cd772af567](https://linux-hardware.org/?probe=cd772af567) | Apr 14, 2021 |
| Gigabyte      | EP35-DS4                    | [e37cf6fc8d](https://linux-hardware.org/?probe=e37cf6fc8d) | Apr 12, 2021 |
| MSI           | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09cf1ed052](https://linux-hardware.org/?probe=09cf1ed052) | Apr 08, 2021 |
| ASRock        | Z270 Pro4                   | [b90dd1b4d2](https://linux-hardware.org/?probe=b90dd1b4d2) | Apr 02, 2021 |
| Medion        | MS-7797                     | [947bc894eb](https://linux-hardware.org/?probe=947bc894eb) | Apr 01, 2021 |
| ASUSTek       | PRIME Z370-A                | [757d1d0707](https://linux-hardware.org/?probe=757d1d0707) | Mar 31, 2021 |
| ASUSTek       | PRIME Z370-A                | [eb1782ad49](https://linux-hardware.org/?probe=eb1782ad49) | Mar 31, 2021 |
| Dell          | 0CU409                      | [53a8c28aed](https://linux-hardware.org/?probe=53a8c28aed) | Mar 24, 2021 |
| Acer          | Aspire XC-605               | [f8ad366bd9](https://linux-hardware.org/?probe=f8ad366bd9) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [54288c23c9](https://linux-hardware.org/?probe=54288c23c9) | Mar 18, 2021 |
| ECS           | Nettle3                     | [f7ec16d7e7](https://linux-hardware.org/?probe=f7ec16d7e7) | Mar 16, 2021 |
| HP            | 3032h                       | [79b0bf2416](https://linux-hardware.org/?probe=79b0bf2416) | Mar 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [9ebf280981](https://linux-hardware.org/?probe=9ebf280981) | Mar 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | [efa91095ab](https://linux-hardware.org/?probe=efa91095ab) | Mar 05, 2021 |
| ASUSTek       | M4N75TD                     | [9daf1b6529](https://linux-hardware.org/?probe=9daf1b6529) | Feb 28, 2021 |
| ASUSTek       | P5P43TD                     | [3a2604a18a](https://linux-hardware.org/?probe=3a2604a18a) | Feb 27, 2021 |
| HP            | 1998                        | [43bd925171](https://linux-hardware.org/?probe=43bd925171) | Feb 27, 2021 |
| ASUSTek       | PRIME Z270-A                | [66ce820cff](https://linux-hardware.org/?probe=66ce820cff) | Feb 25, 2021 |
| ASRock        | QC5000-ITX/WiFi             | [d321b1eb90](https://linux-hardware.org/?probe=d321b1eb90) | Feb 21, 2021 |
| ASRock        | Z270 Pro4                   | [7114de29ed](https://linux-hardware.org/?probe=7114de29ed) | Feb 20, 2021 |
| Medion        | MS-7797                     | [3c4d9332e4](https://linux-hardware.org/?probe=3c4d9332e4) | Feb 19, 2021 |
| MSI           | B150M PRO-VH                | [255e61b850](https://linux-hardware.org/?probe=255e61b850) | Feb 13, 2021 |
| Medion        | MS-7797                     | [7e6811c842](https://linux-hardware.org/?probe=7e6811c842) | Feb 10, 2021 |
| Medion        | MS-7797                     | [394c3c87f4](https://linux-hardware.org/?probe=394c3c87f4) | Feb 10, 2021 |
| ASRock        | B550M-ITX/ac                | [909d040ae4](https://linux-hardware.org/?probe=909d040ae4) | Feb 07, 2021 |
| Medion        | MS-7708                     | [53ba901c28](https://linux-hardware.org/?probe=53ba901c28) | Feb 01, 2021 |
| Medion        | MS-7708                     | [8ef1638192](https://linux-hardware.org/?probe=8ef1638192) | Feb 01, 2021 |
| Lenovo        | ThinkServer TS140           | [8f911a91ca](https://linux-hardware.org/?probe=8f911a91ca) | Jan 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [34257c05a5](https://linux-hardware.org/?probe=34257c05a5) | Jan 27, 2021 |
| Gigabyte      | GA-780T-D3L                 | [2f2ede94cb](https://linux-hardware.org/?probe=2f2ede94cb) | Jan 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [fc3f785613](https://linux-hardware.org/?probe=fc3f785613) | Jan 15, 2021 |
| NEXCOM        | NDIS B322                   | [c2789ca746](https://linux-hardware.org/?probe=c2789ca746) | Jan 06, 2021 |
| Gigabyte      | B550M DS3H                  | [16d30d3356](https://linux-hardware.org/?probe=16d30d3356) | Dec 30, 2020 |
| Gigabyte      | B550M DS3H                  | [944fc761f4](https://linux-hardware.org/?probe=944fc761f4) | Dec 30, 2020 |
| ASUSTek       | Z97-K                       | [3eacdc5965](https://linux-hardware.org/?probe=3eacdc5965) | Dec 28, 2020 |
| MSI           | B150M PRO-VH                | [f225de5ed7](https://linux-hardware.org/?probe=f225de5ed7) | Dec 25, 2020 |
| MSI           | B150M PRO-VH                | [6971a673ec](https://linux-hardware.org/?probe=6971a673ec) | Dec 25, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [13d6a7172d](https://linux-hardware.org/?probe=13d6a7172d) | Dec 15, 2020 |
| Gigabyte      | J3455N-D3H                  | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [968983910f](https://linux-hardware.org/?probe=968983910f) | Dec 08, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [b3c78e0e70](https://linux-hardware.org/?probe=b3c78e0e70) | Dec 07, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [1a5eee726d](https://linux-hardware.org/?probe=1a5eee726d) | Dec 05, 2020 |
| MSI           | MPG Z490 GAMING PLUS        | [95b94bfe02](https://linux-hardware.org/?probe=95b94bfe02) | Dec 04, 2020 |
| MSI           | X570-A PRO                  | [0c57860179](https://linux-hardware.org/?probe=0c57860179) | Dec 02, 2020 |
| Medion        | B360H4-EM V1.0              | [718acb9fc0](https://linux-hardware.org/?probe=718acb9fc0) | Dec 02, 2020 |
| MSI           | B150M PRO-VH                | [ed280391f2](https://linux-hardware.org/?probe=ed280391f2) | Nov 30, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [f49b6c5048](https://linux-hardware.org/?probe=f49b6c5048) | Nov 27, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [ce4048d43f](https://linux-hardware.org/?probe=ce4048d43f) | Nov 24, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [9845e5eb1e](https://linux-hardware.org/?probe=9845e5eb1e) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [91207c72e3](https://linux-hardware.org/?probe=91207c72e3) | Nov 15, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [d2afbbe9f9](https://linux-hardware.org/?probe=d2afbbe9f9) | Nov 10, 2020 |
| Lenovo        | ThinkCentre Edge72 3484F... | [8864ed7825](https://linux-hardware.org/?probe=8864ed7825) | Nov 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [54f14d0d27](https://linux-hardware.org/?probe=54f14d0d27) | Nov 02, 2020 |
| ASRock        | Z170 OC Formula             | [067d0719a1](https://linux-hardware.org/?probe=067d0719a1) | Oct 30, 2020 |
| ASRock        | TRX40 Creator               | [3b1961ec14](https://linux-hardware.org/?probe=3b1961ec14) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2e111f0b77](https://linux-hardware.org/?probe=2e111f0b77) | Oct 29, 2020 |
| Dell          | 0CT017                      | [4f36a920b3](https://linux-hardware.org/?probe=4f36a920b3) | Oct 26, 2020 |
| ASRock        | B450M Pro4                  | [375a230939](https://linux-hardware.org/?probe=375a230939) | Oct 26, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [97ae9ff8fd](https://linux-hardware.org/?probe=97ae9ff8fd) | Oct 16, 2020 |
| ASUSTek       | PRIME B250M-A               | [afee01c14d](https://linux-hardware.org/?probe=afee01c14d) | Oct 11, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [734e996f73](https://linux-hardware.org/?probe=734e996f73) | Oct 07, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ce1874a3be](https://linux-hardware.org/?probe=ce1874a3be) | Oct 07, 2020 |
| ASRock        | Z170 Extreme4               | [39a631ad3c](https://linux-hardware.org/?probe=39a631ad3c) | Oct 06, 2020 |
| Pegatron      | 2AD5                        | [4d341edca9](https://linux-hardware.org/?probe=4d341edca9) | Oct 05, 2020 |
| MSI           | Z87 MPOWER                  | [c361400ba5](https://linux-hardware.org/?probe=c361400ba5) | Oct 02, 2020 |
| HP            | 3398                        | [95d758781c](https://linux-hardware.org/?probe=95d758781c) | Oct 01, 2020 |
| ASUSTek       | Z170-DELUXE                 | [619ac1f764](https://linux-hardware.org/?probe=619ac1f764) | Sep 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09b275ac93](https://linux-hardware.org/?probe=09b275ac93) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS PRO              | [1fd3e30c8e](https://linux-hardware.org/?probe=1fd3e30c8e) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5032W3M     | [b6dc69bcc6](https://linux-hardware.org/?probe=b6dc69bcc6) | Sep 23, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [4298ad10c2](https://linux-hardware.org/?probe=4298ad10c2) | Sep 05, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [d98e57a21a](https://linux-hardware.org/?probe=d98e57a21a) | Sep 05, 2020 |
| Gigabyte      | X570 GAMING X               | [9cd1bda591](https://linux-hardware.org/?probe=9cd1bda591) | Sep 04, 2020 |
| Medion        | MS-7366                     | [ff7271711d](https://linux-hardware.org/?probe=ff7271711d) | Aug 25, 2020 |
| HP            | 2AFA                        | [b60453f85a](https://linux-hardware.org/?probe=b60453f85a) | Aug 23, 2020 |
| HP            | 2AFA                        | [4c206cac6d](https://linux-hardware.org/?probe=4c206cac6d) | Aug 22, 2020 |
| ASUSTek       | Z170-PRO                    | [7a14a06010](https://linux-hardware.org/?probe=7a14a06010) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [9ac43f513b](https://linux-hardware.org/?probe=9ac43f513b) | Aug 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5c7a68d981](https://linux-hardware.org/?probe=5c7a68d981) | Aug 07, 2020 |
| Gigabyte      | Z77P-D3                     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| MSI           | B450 TOMAHAWK               | [c44d7421b8](https://linux-hardware.org/?probe=c44d7421b8) | Jul 24, 2020 |
| MSI           | X470 GAMING PRO             | [c12505e247](https://linux-hardware.org/?probe=c12505e247) | Jul 21, 2020 |
| MSI           | X470 GAMING PRO             | [ca1dac6b45](https://linux-hardware.org/?probe=ca1dac6b45) | Jul 21, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [861ca18aab](https://linux-hardware.org/?probe=861ca18aab) | Jul 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [ce07e0a768](https://linux-hardware.org/?probe=ce07e0a768) | Jul 14, 2020 |
| Lenovo        | ThinkCentre M58 7359WQR     | [73e0df5013](https://linux-hardware.org/?probe=73e0df5013) | Jul 09, 2020 |
| Gigabyte      | X570 UD                     | [ab1e04310e](https://linux-hardware.org/?probe=ab1e04310e) | Jul 07, 2020 |
| Gigabyte      | X570 UD                     | [319bbe63a2](https://linux-hardware.org/?probe=319bbe63a2) | Jul 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [1fa9af511a](https://linux-hardware.org/?probe=1fa9af511a) | Jul 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [57643353ce](https://linux-hardware.org/?probe=57643353ce) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9546ca8c2a](https://linux-hardware.org/?probe=9546ca8c2a) | Jun 29, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [b92d2bdb9d](https://linux-hardware.org/?probe=b92d2bdb9d) | Jun 28, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [8f5fc60880](https://linux-hardware.org/?probe=8f5fc60880) | Jun 20, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fdabb9483a](https://linux-hardware.org/?probe=fdabb9483a) | Jun 19, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [bef7a799cc](https://linux-hardware.org/?probe=bef7a799cc) | Jun 18, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [415c3a4a20](https://linux-hardware.org/?probe=415c3a4a20) | Jun 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [1bd41519c5](https://linux-hardware.org/?probe=1bd41519c5) | Jun 13, 2020 |
| ASUSTek       | Maximus VIII HERO           | [3e632a857d](https://linux-hardware.org/?probe=3e632a857d) | Jun 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [c83816398c](https://linux-hardware.org/?probe=c83816398c) | Jun 05, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [82591ffa30](https://linux-hardware.org/?probe=82591ffa30) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [637d3d6ccc](https://linux-hardware.org/?probe=637d3d6ccc) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bde3e045ca](https://linux-hardware.org/?probe=bde3e045ca) | May 31, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [58f57667ee](https://linux-hardware.org/?probe=58f57667ee) | May 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [8ab04c0e95](https://linux-hardware.org/?probe=8ab04c0e95) | May 22, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a1a244d013](https://linux-hardware.org/?probe=a1a244d013) | May 21, 2020 |
| AMI           | Cherry Trail FFD            | [2646be2c9b](https://linux-hardware.org/?probe=2646be2c9b) | May 17, 2020 |
| AMI           | Cherry Trail FFD            | [1abe48ca91](https://linux-hardware.org/?probe=1abe48ca91) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [aa8b123cdd](https://linux-hardware.org/?probe=aa8b123cdd) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [c6f0fde0d2](https://linux-hardware.org/?probe=c6f0fde0d2) | May 16, 2020 |
| Gigabyte      | GA-870A-UD3                 | [9d150cc443](https://linux-hardware.org/?probe=9d150cc443) | May 16, 2020 |
| ASUSTek       | B85M-G                      | [f575cb11cb](https://linux-hardware.org/?probe=f575cb11cb) | May 08, 2020 |
| ASRock        | B450 Gaming K4              | [d82dc4eb4f](https://linux-hardware.org/?probe=d82dc4eb4f) | May 01, 2020 |
| ASRock        | B450 Gaming K4              | [c08ec23742](https://linux-hardware.org/?probe=c08ec23742) | May 01, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [3d3bc60c59](https://linux-hardware.org/?probe=3d3bc60c59) | Apr 28, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [ed1abce019](https://linux-hardware.org/?probe=ed1abce019) | Apr 23, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [0cbe6fdb9b](https://linux-hardware.org/?probe=0cbe6fdb9b) | Apr 21, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [61d4286e96](https://linux-hardware.org/?probe=61d4286e96) | Apr 06, 2020 |
| ECS           | Nettle3                     | [51538f1902](https://linux-hardware.org/?probe=51538f1902) | Apr 02, 2020 |
| ECS           | Nettle3                     | [5a8f6b27a0](https://linux-hardware.org/?probe=5a8f6b27a0) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [fee80882b4](https://linux-hardware.org/?probe=fee80882b4) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [309423fc5a](https://linux-hardware.org/?probe=309423fc5a) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [cc7be1cc44](https://linux-hardware.org/?probe=cc7be1cc44) | Apr 02, 2020 |
| Dell          | 0F373D A00                  | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fbc59a267b](https://linux-hardware.org/?probe=fbc59a267b) | Mar 23, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [548b742928](https://linux-hardware.org/?probe=548b742928) | Mar 22, 2020 |
| HP            | ProLiant MicroServer        | [b8fc545d86](https://linux-hardware.org/?probe=b8fc545d86) | Mar 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [73276b8f74](https://linux-hardware.org/?probe=73276b8f74) | Mar 09, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [da8bd96ca5](https://linux-hardware.org/?probe=da8bd96ca5) | Mar 07, 2020 |
| ASUSTek       | Z97-A-USB31                 | [63b94ee87e](https://linux-hardware.org/?probe=63b94ee87e) | Mar 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [da2608360d](https://linux-hardware.org/?probe=da2608360d) | Feb 23, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [078b188645](https://linux-hardware.org/?probe=078b188645) | Feb 16, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [700eabb523](https://linux-hardware.org/?probe=700eabb523) | Feb 15, 2020 |
| HP            | 86D3                        | [83613548dc](https://linux-hardware.org/?probe=83613548dc) | Feb 13, 2020 |
| Alienware     | 06G6JW A00                  | [f3eab06bb2](https://linux-hardware.org/?probe=f3eab06bb2) | Feb 10, 2020 |
| MSI           | Z97-G43                     | [01c2993ade](https://linux-hardware.org/?probe=01c2993ade) | Jan 25, 2020 |
| HP            | ProLiant ML350 G6           | [3472820868](https://linux-hardware.org/?probe=3472820868) | Jan 17, 2020 |
| HP            | ProLiant ML350 G6           | [86fb31ed72](https://linux-hardware.org/?probe=86fb31ed72) | Jan 16, 2020 |
| ASUSTek       | M4A88T-M                    | [643a92956a](https://linux-hardware.org/?probe=643a92956a) | Jan 13, 2020 |
| Gigabyte      | EG41M-US2H                  | [697f2f05e2](https://linux-hardware.org/?probe=697f2f05e2) | Jan 12, 2020 |
| eMachines     | ET1850                      | [7c1a93e022](https://linux-hardware.org/?probe=7c1a93e022) | Dec 23, 2019 |
| Gigabyte      | Z77P-D3                     | [3de82df337](https://linux-hardware.org/?probe=3de82df337) | Dec 17, 2019 |
| Gigabyte      | H61N-USB3                   | [ee74c9e54c](https://linux-hardware.org/?probe=ee74c9e54c) | Dec 12, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | [44e3d900f5](https://linux-hardware.org/?probe=44e3d900f5) | Dec 02, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ed930b473b](https://linux-hardware.org/?probe=ed930b473b) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [e2bc0cfec5](https://linux-hardware.org/?probe=e2bc0cfec5) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [53e0ab44e0](https://linux-hardware.org/?probe=53e0ab44e0) | Nov 23, 2019 |
| Gigabyte      | Z77P-D3                     | [9a1e3d5db9](https://linux-hardware.org/?probe=9a1e3d5db9) | Nov 23, 2019 |
| Packard Be... | IMEDIA L4880                | [a9a53bf7f4](https://linux-hardware.org/?probe=a9a53bf7f4) | Nov 18, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [0029decba2](https://linux-hardware.org/?probe=0029decba2) | Nov 08, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6b013738c6](https://linux-hardware.org/?probe=6b013738c6) | Oct 24, 2019 |
| HP            | 3397                        | [27d2857bca](https://linux-hardware.org/?probe=27d2857bca) | Sep 30, 2019 |
| Gigabyte      | EG41M-US2H                  | [9717827455](https://linux-hardware.org/?probe=9717827455) | Sep 27, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [6298b19758](https://linux-hardware.org/?probe=6298b19758) | Sep 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [6d7e7fdc51](https://linux-hardware.org/?probe=6d7e7fdc51) | Sep 23, 2019 |
| ASUSTek       | Z10PA-D8 Series             | [7436c74dcb](https://linux-hardware.org/?probe=7436c74dcb) | Sep 11, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [340c34926f](https://linux-hardware.org/?probe=340c34926f) | Aug 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [d1e5249043](https://linux-hardware.org/?probe=d1e5249043) | Aug 19, 2019 |
| ASRock        | HM65-MXM                    | [0d687e29cb](https://linux-hardware.org/?probe=0d687e29cb) | Aug 12, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [fbdbd66417](https://linux-hardware.org/?probe=fbdbd66417) | Aug 11, 2019 |
| Dell          | 06X1TJ A01                  | [faf781dda9](https://linux-hardware.org/?probe=faf781dda9) | Aug 05, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [2ed5b5afc5](https://linux-hardware.org/?probe=2ed5b5afc5) | Jul 21, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [aa7226b798](https://linux-hardware.org/?probe=aa7226b798) | Jul 21, 2019 |
| Lenovo        | ThinkCentre M81 5032W3M     | [cb4983baf6](https://linux-hardware.org/?probe=cb4983baf6) | Jul 18, 2019 |
| ASRock        | FM2A78M-HD+                 | [4c45eb1803](https://linux-hardware.org/?probe=4c45eb1803) | Jul 10, 2019 |
| Intel         | DH77EB AAG39073-304         | [08b86f6f4c](https://linux-hardware.org/?probe=08b86f6f4c) | Jul 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [706e1e0baf](https://linux-hardware.org/?probe=706e1e0baf) | Jun 30, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [11a091fb81](https://linux-hardware.org/?probe=11a091fb81) | Jun 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [8fc47ce184](https://linux-hardware.org/?probe=8fc47ce184) | Jun 15, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [7ba347026e](https://linux-hardware.org/?probe=7ba347026e) | Jun 13, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3f7e0702b6](https://linux-hardware.org/?probe=3f7e0702b6) | Jun 12, 2019 |
| Dell          | 088DT1 A01                  | [5ea359299f](https://linux-hardware.org/?probe=5ea359299f) | Jun 11, 2019 |
| ASUSTek       | X99-A/USB                   | [d1e49be03d](https://linux-hardware.org/?probe=d1e49be03d) | Jun 11, 2019 |
| Gigabyte      | P85-D3                      | [16a7890585](https://linux-hardware.org/?probe=16a7890585) | Jun 09, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [9f8322e22a](https://linux-hardware.org/?probe=9f8322e22a) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [0c0c2eca20](https://linux-hardware.org/?probe=0c0c2eca20) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3608798d1a](https://linux-hardware.org/?probe=3608798d1a) | May 24, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e50d4d260b](https://linux-hardware.org/?probe=e50d4d260b) | May 23, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [1cbc7d5be7](https://linux-hardware.org/?probe=1cbc7d5be7) | May 16, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [cb3502a316](https://linux-hardware.org/?probe=cb3502a316) | May 09, 2019 |
| MSI           | B350 TOMAHAWK               | [3db9496e05](https://linux-hardware.org/?probe=3db9496e05) | May 08, 2019 |
| MSI           | B450 TOMAHAWK               | [0f966d6a2d](https://linux-hardware.org/?probe=0f966d6a2d) | May 08, 2019 |
| ASUSTek       | CROSSHAIR VI HERO           | [7653740066](https://linux-hardware.org/?probe=7653740066) | May 04, 2019 |
| HP            | 0A58h                       | [ec6b93d879](https://linux-hardware.org/?probe=ec6b93d879) | May 02, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [ca0ce2b4fc](https://linux-hardware.org/?probe=ca0ce2b4fc) | Apr 26, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e08bb193b2](https://linux-hardware.org/?probe=e08bb193b2) | Apr 24, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [79831da7d2](https://linux-hardware.org/?probe=79831da7d2) | Apr 15, 2019 |
| Dell          | 04JGCK A02                  | [fd0e8a37d1](https://linux-hardware.org/?probe=fd0e8a37d1) | Apr 09, 2019 |
| ASRock        | 4Core1600Twins-P35          | [a5f4c15c85](https://linux-hardware.org/?probe=a5f4c15c85) | Apr 07, 2019 |
| ASUSTek       | P7P55D                      | [b25ec7e75a](https://linux-hardware.org/?probe=b25ec7e75a) | Mar 18, 2019 |
| Shuttle       | FN68S V10                   | [10121de278](https://linux-hardware.org/?probe=10121de278) | Mar 04, 2019 |
| Shuttle       | FN68S V10                   | [d15d7c5f21](https://linux-hardware.org/?probe=d15d7c5f21) | Mar 04, 2019 |
| ASRock        | 4Core1600Twins-P35          | [98b19f2fc7](https://linux-hardware.org/?probe=98b19f2fc7) | Feb 25, 2019 |
| ASRock        | Z77 Pro4                    | [08a0af469d](https://linux-hardware.org/?probe=08a0af469d) | Feb 20, 2019 |
| ASRock        | 4Core1600Twins-P35          | [e94ef5e02e](https://linux-hardware.org/?probe=e94ef5e02e) | Feb 16, 2019 |
| ASRock        | Z77 Pro4                    | [ba845b8712](https://linux-hardware.org/?probe=ba845b8712) | Feb 15, 2019 |
| ASRock        | Z77 Pro4                    | [e104fbc941](https://linux-hardware.org/?probe=e104fbc941) | Feb 14, 2019 |
| Acer          | FMCP7A-ION                  | [22a3849e3a](https://linux-hardware.org/?probe=22a3849e3a) | Dec 05, 2018 |
| Medion        | MS-7646                     | [cb720a4df0](https://linux-hardware.org/?probe=cb720a4df0) | Nov 25, 2018 |
| Medion        | MS-7713                     | [94a415c6c3](https://linux-hardware.org/?probe=94a415c6c3) | Nov 23, 2018 |
| Medion        | MS-7646                     | [7ff447b20e](https://linux-hardware.org/?probe=7ff447b20e) | Nov 22, 2018 |
| Lenovo        | 5025a26                     | [75a078fe71](https://linux-hardware.org/?probe=75a078fe71) | Nov 15, 2018 |
| ASUSTek       | PRIME Z370-P                | [89bfd874c0](https://linux-hardware.org/?probe=89bfd874c0) | Nov 03, 2018 |
| MSI           | B75MA-E31                   | [b1600ef31c](https://linux-hardware.org/?probe=b1600ef31c) | Nov 02, 2018 |
| ASUSTek       | H81M-P PLUS                 | [67c13bd391](https://linux-hardware.org/?probe=67c13bd391) | Oct 25, 2018 |
| Pegatron      | 2AB5                        | [85d0b75160](https://linux-hardware.org/?probe=85d0b75160) | Oct 24, 2018 |
| Pegatron      | 2AB5                        | [25cf879f80](https://linux-hardware.org/?probe=25cf879f80) | Oct 24, 2018 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f67b4afee6](https://linux-hardware.org/?probe=f67b4afee6) | Aug 11, 2018 |
| HP            | 82FE 11                     | [bd284d1c9d](https://linux-hardware.org/?probe=bd284d1c9d) | Dec 11, 2017 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [0f0a556912](https://linux-hardware.org/?probe=0f0a556912) | Jul 03, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 41       | 15.53%  |
| Ubuntu 18.04      | 30       | 11.36%  |
| OpenMandriva 4.2  | 13       | 4.92%   |
| Zorin 16          | 11       | 4.17%   |
| Arch Rolling      | 9        | 3.41%   |
| Pop!_OS 21.04     | 7        | 2.65%   |
| Linux Mint 20.2   | 7        | 2.65%   |
| Manjaro           | 6        | 2.27%   |
| Ubuntu 20.10      | 5        | 1.89%   |
| Ubuntu 19.04      | 5        | 1.89%   |
| Pop!_OS 20.10     | 5        | 1.89%   |
| Linux Mint 20.3   | 5        | 1.89%   |
| Linux Mint 20.1   | 5        | 1.89%   |
| Zorin 15          | 4        | 1.52%   |
| Ubuntu 21.10      | 4        | 1.52%   |
| OpenMandriva 4.3  | 4        | 1.52%   |
| KDE neon 20.04    | 4        | 1.52%   |
| Ubuntu 19.10      | 3        | 1.14%   |
| Pop!_OS 22.04     | 3        | 1.14%   |
| Pop!_OS 21.10     | 3        | 1.14%   |
| Linux Mint 20     | 3        | 1.14%   |
| Fedora 32         | 3        | 1.14%   |
| Debian 11         | 3        | 1.14%   |
| Debian 10         | 3        | 1.14%   |
| Ubuntu MATE 20.04 | 2        | 0.76%   |
| Ubuntu 22.04      | 2        | 0.76%   |
| Ubuntu 16.04      | 2        | 0.76%   |
| Pop!_OS 20.04     | 2        | 0.76%   |
| Manjaro 21.2.0    | 2        | 0.76%   |
| Manjaro 20.0.3    | 2        | 0.76%   |
| Manjaro 20.0.1    | 2        | 0.76%   |
| Linux Mint 19.3   | 2        | 0.76%   |
| Linux Mint 19.2   | 2        | 0.76%   |
| Linux Mint 19.1   | 2        | 0.76%   |
| Kubuntu 20.04     | 2        | 0.76%   |
| Fedora 35         | 2        | 0.76%   |
| Fedora 34         | 2        | 0.76%   |
| Fedora 30         | 2        | 0.76%   |
| EndeavourOS       | 2        | 0.76%   |
| Debian Testing    | 2        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 91       | 36.25%  |
| Linux Mint   | 25       | 9.96%   |
| Pop!_OS      | 20       | 7.97%   |
| OpenMandriva | 18       | 7.17%   |
| Zorin        | 15       | 5.98%   |
| Manjaro      | 15       | 5.98%   |
| Fedora       | 12       | 4.78%   |
| Arch         | 11       | 4.38%   |
| Debian       | 9        | 3.59%   |
| Kubuntu      | 5        | 1.99%   |
| KDE neon     | 5        | 1.99%   |
| ROSA         | 3        | 1.2%    |
| EndeavourOS  | 3        | 1.2%    |
| ArcoLinux    | 3        | 1.2%    |
| Ubuntu MATE  | 2        | 0.8%    |
| MX           | 2        | 0.8%    |
| Gentoo       | 2        | 0.8%    |
| Xubuntu      | 1        | 0.4%    |
| Solus        | 1        | 0.4%    |
| Parrot       | 1        | 0.4%    |
| NixOS        | 1        | 0.4%    |
| Lubuntu      | 1        | 0.4%    |
| Garuda Linux | 1        | 0.4%    |
| Endless      | 1        | 0.4%    |
| Elementary   | 1        | 0.4%    |
| BlackPanther | 1        | 0.4%    |
| Anarchy      | 1        | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 11       | 3.87%   |
| 5.4.0-52-generic         | 6        | 2.11%   |
| 5.8.0-43-generic         | 4        | 1.41%   |
| 5.4.0-42-generic         | 4        | 1.41%   |
| 5.16.7-desktop-1omv4003  | 4        | 1.41%   |
| 4.15.0-48-generic        | 4        | 1.41%   |
| 5.8.5-arch1-1            | 3        | 1.06%   |
| 5.4.0-91-generic         | 3        | 1.06%   |
| 5.4.0-90-generic         | 3        | 1.06%   |
| 5.4.0-73-generic         | 3        | 1.06%   |
| 5.4.0-58-generic         | 3        | 1.06%   |
| 5.4.0-29-generic         | 3        | 1.06%   |
| 5.3.0-28-generic         | 3        | 1.06%   |
| 5.15.0-46-generic        | 3        | 1.06%   |
| 5.15.0-41-generic        | 3        | 1.06%   |
| 5.13.0-28-generic        | 3        | 1.06%   |
| 5.11.12-desktop-1omv4002 | 3        | 1.06%   |
| 5.11.0-7620-generic      | 3        | 1.06%   |
| 5.11.0-37-generic        | 3        | 1.06%   |
| 5.11.0-27-generic        | 3        | 1.06%   |
| 5.0.0-13-generic         | 3        | 1.06%   |
| 4.15.0-45-generic        | 3        | 1.06%   |
| 5.8.0-7642-generic       | 2        | 0.7%    |
| 5.8.0-63-generic         | 2        | 0.7%    |
| 5.8.0-41-generic         | 2        | 0.7%    |
| 5.6.15-1-MANJARO         | 2        | 0.7%    |
| 5.6.12-1-MANJARO         | 2        | 0.7%    |
| 5.4.18-1-MANJARO         | 2        | 0.7%    |
| 5.4.0-88-generic         | 2        | 0.7%    |
| 5.4.0-80-generic         | 2        | 0.7%    |
| 5.4.0-70-generic         | 2        | 0.7%    |
| 5.4.0-53-generic         | 2        | 0.7%    |
| 5.4.0-48-generic         | 2        | 0.7%    |
| 5.4.0-26-generic         | 2        | 0.7%    |
| 5.3.0-46-generic         | 2        | 0.7%    |
| 5.3.0-26-generic         | 2        | 0.7%    |
| 5.19.0-76051900-generic  | 2        | 0.7%    |
| 5.13.12-200.fc34.x86_64  | 2        | 0.7%    |
| 5.13.0-7620-generic      | 2        | 0.7%    |
| 5.13.0-7614-generic      | 2        | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 51       | 18.82%  |
| 4.15.0  | 28       | 10.33%  |
| 5.8.0   | 21       | 7.75%   |
| 5.13.0  | 18       | 6.64%   |
| 5.11.0  | 18       | 6.64%   |
| 5.3.0   | 11       | 4.06%   |
| 5.10.14 | 11       | 4.06%   |
| 5.15.0  | 8        | 2.95%   |
| 5.0.0   | 8        | 2.95%   |
| 4.18.0  | 5        | 1.85%   |
| 5.16.7  | 4        | 1.48%   |
| 5.10.0  | 4        | 1.48%   |
| 4.19.0  | 4        | 1.48%   |
| 5.8.5   | 3        | 1.11%   |
| 5.6.15  | 3        | 1.11%   |
| 5.11.12 | 3        | 1.11%   |
| 5.9.1   | 2        | 0.74%   |
| 5.8.18  | 2        | 0.74%   |
| 5.6.12  | 2        | 0.74%   |
| 5.4.18  | 2        | 0.74%   |
| 5.19.5  | 2        | 0.74%   |
| 5.19.0  | 2        | 0.74%   |
| 5.16.0  | 2        | 0.74%   |
| 5.13.12 | 2        | 0.74%   |
| 5.11.11 | 2        | 0.74%   |
| 5.9.0   | 1        | 0.37%   |
| 5.8.6   | 1        | 0.37%   |
| 5.8.4   | 1        | 0.37%   |
| 5.8.2   | 1        | 0.37%   |
| 5.8.12  | 1        | 0.37%   |
| 5.7.9   | 1        | 0.37%   |
| 5.7.8   | 1        | 0.37%   |
| 5.7.7   | 1        | 0.37%   |
| 5.7.6   | 1        | 0.37%   |
| 5.7.2   | 1        | 0.37%   |
| 5.7.0   | 1        | 0.37%   |
| 5.6.7   | 1        | 0.37%   |
| 5.6.14  | 1        | 0.37%   |
| 5.6.0   | 1        | 0.37%   |
| 5.4.38  | 1        | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 55       | 20.68%  |
| 5.8     | 30       | 11.28%  |
| 4.15    | 28       | 10.53%  |
| 5.11    | 25       | 9.4%    |
| 5.13    | 21       | 7.89%   |
| 5.10    | 17       | 6.39%   |
| 5.15    | 14       | 5.26%   |
| 5.3     | 11       | 4.14%   |
| 5.16    | 10       | 3.76%   |
| 5.0     | 8        | 3.01%   |
| 5.6     | 7        | 2.63%   |
| 5.7     | 5        | 1.88%   |
| 5.19    | 5        | 1.88%   |
| 4.19    | 5        | 1.88%   |
| 4.18    | 5        | 1.88%   |
| 5.17    | 4        | 1.5%    |
| 5.9     | 3        | 1.13%   |
| 5.14    | 3        | 1.13%   |
| 4.9     | 3        | 1.13%   |
| 5.12    | 2        | 0.75%   |
| 5.1     | 2        | 0.75%   |
| 5.2     | 1        | 0.38%   |
| 5.18    | 1        | 0.38%   |
| 4.17    | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 238      | 98.76%  |
| i686   | 3        | 1.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 106      | 41.57%  |
| Unknown       | 53       | 20.78%  |
| KDE5          | 39       | 15.29%  |
| X-Cinnamon    | 19       | 7.45%   |
| XFCE          | 15       | 5.88%   |
| KDE           | 7        | 2.75%   |
| Cinnamon      | 4        | 1.57%   |
| MATE          | 3        | 1.18%   |
| KDE4          | 2        | 0.78%   |
| Pantheon      | 1        | 0.39%   |
| openbox       | 1        | 0.39%   |
| LXDE          | 1        | 0.39%   |
| i3            | 1        | 0.39%   |
| enlightenment | 1        | 0.39%   |
| Deepin        | 1        | 0.39%   |
| bspwm         | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 209      | 84.27%  |
| Unknown | 23       | 9.27%   |
| Wayland | 12       | 4.84%   |
| Tty     | 4        | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 152      | 60.08%  |
| SDDM    | 36       | 14.23%  |
| GDM3    | 19       | 7.51%   |
| GDM     | 17       | 6.72%   |
| TDM     | 15       | 5.93%   |
| LightDM | 11       | 4.35%   |
| KDM     | 2        | 0.79%   |
| LXDM    | 1        | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 83       | 33.47%  |
| da_DK      | 75       | 30.24%  |
| Unknown    | 42       | 16.94%  |
| en_DK      | 31       | 12.5%   |
| en_GB      | 5        | 2.02%   |
| ru_RU      | 2        | 0.81%   |
| de_DE      | 2        | 0.81%   |
| C          | 2        | 0.81%   |
| pl_PL      | 1        | 0.4%    |
| it_IT      | 1        | 0.4%    |
| io_001     | 1        | 0.4%    |
| en_US.UTF8 | 1        | 0.4%    |
| en_IE      | 1        | 0.4%    |
| de_AT      | 1        | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 148      | 60.16%  |
| EFI  | 98       | 39.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 198      | 79.52%  |
| Overlay | 22       | 8.84%   |
| Unknown | 13       | 5.22%   |
| Btrfs   | 12       | 4.82%   |
| Zfs     | 2        | 0.8%    |
| Xfs     | 2        | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 163      | 64.94%  |
| GPT     | 64       | 25.5%   |
| MBR     | 24       | 9.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 78%     |
| Yes       | 55       | 22%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 176      | 71.84%  |
| Yes       | 69       | 28.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 76       | 31.54%  |
| Gigabyte Technology | 41       | 17.01%  |
| MSI                 | 24       | 9.96%   |
| ASRock              | 22       | 9.13%   |
| Lenovo              | 18       | 7.47%   |
| Hewlett-Packard     | 15       | 6.22%   |
| Medion              | 11       | 4.56%   |
| Dell                | 10       | 4.15%   |
| Acer                | 6        | 2.49%   |
| Shuttle             | 3        | 1.24%   |
| Pegatron            | 3        | 1.24%   |
| Intel               | 2        | 0.83%   |
| T-bao               | 1        | 0.41%   |
| Packard Bell        | 1        | 0.41%   |
| NEXCOM              | 1        | 0.41%   |
| eMachines           | 1        | 0.41%   |
| ECS                 | 1        | 0.41%   |
| BESSTAR Tech        | 1        | 0.41%   |
| AMI                 | 1        | 0.41%   |
| Alienware           | 1        | 0.41%   |
| ABIT                | 1        | 0.41%   |
| Unknown             | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS ROG STRIX B450-E GAMING | 5        | 2.07%   |
| ASUS All Series              | 5        | 2.07%   |
| MSI MS-7C37                  | 3        | 1.24%   |
| Dell OptiPlex 9020           | 3        | 1.24%   |
| ASUS Z170 PRO GAMING         | 3        | 1.24%   |
| ASUS ROG STRIX B550-F GAMING | 3        | 1.24%   |
| MSI MS-7B79                  | 2        | 0.83%   |
| Medion MS-7797               | 2        | 0.83%   |
| Medion MS-7646               | 2        | 0.83%   |
| Lenovo H30-05 90BJ00CNMT     | 2        | 0.83%   |
| Gigabyte X570 AORUS MASTER   | 2        | 0.83%   |
| Gigabyte P85-D3              | 2        | 0.83%   |
| ASUS TUF Gaming X570-PLUS    | 2        | 0.83%   |
| ASUS ROG STRIX X470-I GAMING | 2        | 0.83%   |
| ASUS PRIME Z370-P            | 2        | 0.83%   |
| ASUS PRIME Z370-A            | 2        | 0.83%   |
| ASUS PRIME B250M-A           | 2        | 0.83%   |
| ASUS M5A78L-M/USB3           | 2        | 0.83%   |
| ASUS CROSSHAIR VI HERO       | 2        | 0.83%   |
| T-bao MINI PC                | 1        | 0.41%   |
| Shuttle X50V2PLUS            | 1        | 0.41%   |
| Shuttle SN68S                | 1        | 0.41%   |
| Shuttle SH67H3               | 1        | 0.41%   |
| Pegatron HPE-532sc           | 1        | 0.41%   |
| Pegatron h8-1110sc           | 1        | 0.41%   |
| Pegatron 2AD5                | 1        | 0.41%   |
| Packard Bell IXTREME M5741   | 1        | 0.41%   |
| NEXCOM NDIS B322             | 1        | 0.41%   |
| MSI Vortex G65VR 6RE SLI     | 1        | 0.41%   |
| MSI MS-7C91                  | 1        | 0.41%   |
| MSI MS-7C83                  | 1        | 0.41%   |
| MSI MS-7C80                  | 1        | 0.41%   |
| MSI MS-7C75                  | 1        | 0.41%   |
| MSI MS-7C56                  | 1        | 0.41%   |
| MSI MS-7C02                  | 1        | 0.41%   |
| MSI MS-7B86                  | 1        | 0.41%   |
| MSI MS-7B50                  | 1        | 0.41%   |
| MSI MS-7A37                  | 1        | 0.41%   |
| MSI MS-7A34                  | 1        | 0.41%   |
| MSI MS-7A11                  | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 18       | 7.47%   |
| ASUS PRIME           | 16       | 6.64%   |
| Lenovo ThinkCentre   | 8        | 3.32%   |
| Gigabyte X570        | 7        | 2.9%    |
| ASUS TUF             | 6        | 2.49%   |
| HP Compaq            | 5        | 2.07%   |
| Dell OptiPlex        | 5        | 2.07%   |
| ASUS All             | 5        | 2.07%   |
| MSI MS-7C37          | 3        | 1.24%   |
| Lenovo ThinkStation  | 3        | 1.24%   |
| ASUS Z170            | 3        | 1.24%   |
| ASUS SABERTOOTH      | 3        | 1.24%   |
| ASUS M5A78L-M        | 3        | 1.24%   |
| ASRock Z170          | 3        | 1.24%   |
| Acer Aspire          | 3        | 1.24%   |
| MSI MS-7B79          | 2        | 0.83%   |
| Medion MS-7797       | 2        | 0.83%   |
| Medion MS-7646       | 2        | 0.83%   |
| Lenovo H30-05        | 2        | 0.83%   |
| HP ProLiant          | 2        | 0.83%   |
| HP EliteDesk         | 2        | 0.83%   |
| Gigabyte Z390        | 2        | 0.83%   |
| Gigabyte P85-D3      | 2        | 0.83%   |
| Gigabyte B550        | 2        | 0.83%   |
| Gigabyte A320M-S2H   | 2        | 0.83%   |
| ASUS CROSSHAIR       | 2        | 0.83%   |
| ASRock Z77           | 2        | 0.83%   |
| ASRock B450          | 2        | 0.83%   |
| T-bao MINI           | 1        | 0.41%   |
| Shuttle X50V2PLUS    | 1        | 0.41%   |
| Shuttle SN68S        | 1        | 0.41%   |
| Shuttle SH67H3       | 1        | 0.41%   |
| Pegatron HPE-532sc   | 1        | 0.41%   |
| Pegatron h8-1110sc   | 1        | 0.41%   |
| Pegatron 2AD5        | 1        | 0.41%   |
| Packard Bell IXTREME | 1        | 0.41%   |
| NEXCOM NDIS          | 1        | 0.41%   |
| MSI Vortex           | 1        | 0.41%   |
| MSI MS-7C91          | 1        | 0.41%   |
| MSI MS-7C83          | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 27       | 11.2%   |
| 2019 | 26       | 10.79%  |
| 2018 | 26       | 10.79%  |
| 2020 | 21       | 8.71%   |
| 2017 | 19       | 7.88%   |
| 2016 | 15       | 6.22%   |
| 2013 | 15       | 6.22%   |
| 2011 | 15       | 6.22%   |
| 2015 | 14       | 5.81%   |
| 2010 | 13       | 5.39%   |
| 2021 | 11       | 4.56%   |
| 2014 | 11       | 4.56%   |
| 2009 | 10       | 4.15%   |
| 2008 | 10       | 4.15%   |
| 2007 | 5        | 2.07%   |
| 2006 | 2        | 0.83%   |
| 2022 | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 241      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 240      | 99.59%  |
| Enabled  | 1        | 0.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 241      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 79       | 31.85%  |
| 8.01-16.0       | 48       | 19.35%  |
| 32.01-64.0      | 47       | 18.95%  |
| 3.01-4.0        | 26       | 10.48%  |
| 4.01-8.0        | 24       | 9.68%   |
| 64.01-256.0     | 12       | 4.84%   |
| 24.01-32.0      | 5        | 2.02%   |
| 1.01-2.0        | 4        | 1.61%   |
| 2.01-3.0        | 2        | 0.81%   |
| More than 256.0 | 1        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 98       | 36.16%  |
| 2.01-3.0   | 66       | 24.35%  |
| 4.01-8.0   | 42       | 15.5%   |
| 3.01-4.0   | 38       | 14.02%  |
| 8.01-16.0  | 10       | 3.69%   |
| 0.51-1.0   | 10       | 3.69%   |
| 0.01-0.5   | 3        | 1.11%   |
| 24.01-32.0 | 2        | 0.74%   |
| 32.01-64.0 | 1        | 0.37%   |
| 16.01-24.0 | 1        | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 37.6%   |
| 2      | 58       | 23.2%   |
| 3      | 49       | 19.6%   |
| 4      | 24       | 9.6%    |
| 5      | 14       | 5.6%    |
| 6      | 5        | 2%      |
| 0      | 3        | 1.2%    |
| 9      | 1        | 0.4%    |
| 8      | 1        | 0.4%    |
| 7      | 1        | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 53.09%  |
| Yes       | 114      | 46.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 240      | 99.59%  |
| No        | 1        | 0.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 53.47%  |
| Yes       | 114      | 46.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 68.6%   |
| Yes       | 76       | 31.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Denmark | 241      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Copenhagen               | 57       | 23.08%  |
| Odense                   | 14       | 5.67%   |
| Frederiksberg            | 14       | 5.67%   |
| Aarhus                   | 9        | 3.64%   |
| Slagelse                 | 6        | 2.43%   |
| Silkeborg                | 6        | 2.43%   |
| Bronshoj                 | 6        | 2.43%   |
| Aabenraa                 | 6        | 2.43%   |
| Aalborg                  | 5        | 2.02%   |
| Roskilde                 | 4        | 1.62%   |
| Herlev                   | 4        | 1.62%   |
| Esbjerg                  | 4        | 1.62%   |
| Albertslund Municipality | 4        | 1.62%   |
| Vejle                    | 3        | 1.21%   |
| Svendborg                | 3        | 1.21%   |
| Nyborg                   | 3        | 1.21%   |
| Hvidovre                 | 3        | 1.21%   |
| Horsens                  | 3        | 1.21%   |
| Allinge                  | 3        | 1.21%   |
| Aabybro                  | 3        | 1.21%   |
| Viby J                   | 2        | 0.81%   |
| Valby                    | 2        | 0.81%   |
| Trige                    | 2        | 0.81%   |
| Taastrup                 | 2        | 0.81%   |
| Stovring                 | 2        | 0.81%   |
| Soborg                   | 2        | 0.81%   |
| Skanderborg              | 2        | 0.81%   |
| Rødovre Municipality    | 2        | 0.81%   |
| Risskov                  | 2        | 0.81%   |
| Kolding                  | 2        | 0.81%   |
| Kastrup                  | 2        | 0.81%   |
| Hundested                | 2        | 0.81%   |
| Hjørring                | 2        | 0.81%   |
| Gentofte Municipality    | 2        | 0.81%   |
| Fredericia               | 2        | 0.81%   |
| Charlottenlund           | 2        | 0.81%   |
| Aars                     | 2        | 0.81%   |
| Vordingborg              | 1        | 0.4%    |
| Virum                    | 1        | 0.4%    |
| Vinderup                 | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 84       | 122    | 18.5%   |
| Samsung Electronics         | 84       | 151    | 18.5%   |
| WDC                         | 75       | 124    | 16.52%  |
| Kingston                    | 44       | 63     | 9.69%   |
| Crucial                     | 23       | 32     | 5.07%   |
| Toshiba                     | 18       | 24     | 3.96%   |
| SanDisk                     | 16       | 21     | 3.52%   |
| Intel                       | 12       | 14     | 2.64%   |
| Hitachi                     | 10       | 14     | 2.2%    |
| Corsair                     | 8        | 11     | 1.76%   |
| Phison                      | 7        | 10     | 1.54%   |
| Unknown                     | 6        | 7      | 1.32%   |
| Intenso                     | 6        | 9      | 1.32%   |
| A-DATA Technology           | 5        | 5      | 1.1%    |
| SK hynix                    | 4        | 4      | 0.88%   |
| PNY                         | 4        | 4      | 0.88%   |
| OCZ                         | 4        | 4      | 0.88%   |
| Micron Technology           | 3        | 4      | 0.66%   |
| HGST                        | 3        | 6      | 0.66%   |
| Unknown                     | 3        | 5      | 0.66%   |
| Verbatim                    | 2        | 5      | 0.44%   |
| Transcend                   | 2        | 2      | 0.44%   |
| Micron/Crucial Technology   | 2        | 2      | 0.44%   |
| Maxtor                      | 2        | 2      | 0.44%   |
| LITEON                      | 2        | 2      | 0.44%   |
| JMicron Technology          | 2        | 2      | 0.44%   |
| HUAWEI                      | 2        | 2      | 0.44%   |
| Fujitsu                     | 2        | 2      | 0.44%   |
| Apple                       | 2        | 5      | 0.44%   |
| XPG                         | 1        | 1      | 0.22%   |
| Unknown (CF)                | 1        | 1      | 0.22%   |
| Team                        | 1        | 1      | 0.22%   |
| Silicon Motion              | 1        | 1      | 0.22%   |
| Shark                       | 1        | 1      | 0.22%   |
| Realtek Semiconductor       | 1        | 2      | 0.22%   |
| Phison Electronics          | 1        | 2      | 0.22%   |
| LITEONIT                    | 1        | 1      | 0.22%   |
| Leven                       | 1        | 1      | 0.22%   |
| Kingston Technology Company | 1        | 1      | 0.22%   |
| INDMEM                      | 1        | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB     | 8        | 1.5%    |
| Samsung NVMe SSD Drive 1TB       | 7        | 1.31%   |
| Kingston SV300S37A120G 120GB SSD | 7        | 1.31%   |
| Kingston SA400S37240G 240GB SSD  | 7        | 1.31%   |
| Seagate ST2000DM001-1ER164 2TB   | 6        | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB   | 5        | 0.94%   |
| Samsung SSD 860 EVO 1TB          | 5        | 0.94%   |
| Samsung SSD 850 EVO 250GB        | 5        | 0.94%   |
| Samsung SSD 840 EVO 250GB        | 5        | 0.94%   |
| Crucial CT1000MX500SSD1 1TB      | 5        | 0.94%   |
| Unknown SD/MMC/MS PRO 2GB        | 4        | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 0.75%   |
| Seagate ST1000DM003-1SB102 1TB   | 4        | 0.75%   |
| Samsung SSD 860 QVO 1TB          | 4        | 0.75%   |
| Samsung SSD 860 EVO 500GB        | 4        | 0.75%   |
| Kingston SA400S37480G 480GB SSD  | 4        | 0.75%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 0.75%   |
| WDC WD20EARX-00PASB0 2TB         | 3        | 0.56%   |
| WDC WD1003FZEX-00K3CA0 1TB       | 3        | 0.56%   |
| Seagate ST4000VN008-2DR166 4TB   | 3        | 0.56%   |
| Seagate ST3250310AS 250GB        | 3        | 0.56%   |
| Seagate ST3000DM008-2DM166 3TB   | 3        | 0.56%   |
| Seagate ST1000DM003-1SB10C 1TB   | 3        | 0.56%   |
| SanDisk NVMe SSD Drive 1TB       | 3        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.56%   |
| Samsung SSD 970 EVO 1TB          | 3        | 0.56%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.56%   |
| Samsung SSD 840 EVO 500GB        | 3        | 0.56%   |
| Samsung NVMe SSD Drive 256GB     | 3        | 0.56%   |
| Samsung NVMe SSD Drive 250GB     | 3        | 0.56%   |
| Samsung HD103SJ 1TB              | 3        | 0.56%   |
| PNY CS900 120GB SSD              | 3        | 0.56%   |
| Kingston SV300S37A240G 240GB SSD | 3        | 0.56%   |
| Kingston SUV400S37240G 240GB SSD | 3        | 0.56%   |
| Kingston SA2000M81000G 1TB       | 3        | 0.56%   |
| Intenso SCSI 5TB                 | 3        | 0.56%   |
| Crucial CT250MX500SSD1 250GB     | 3        | 0.56%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 0.56%   |
| Crucial CT1000P1SSD8 1TB         | 3        | 0.56%   |
| Unknown                          | 3        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 81       | 118    | 40.7%   |
| WDC                 | 64       | 112    | 32.16%  |
| Toshiba             | 16       | 22     | 8.04%   |
| Samsung Electronics | 10       | 16     | 5.03%   |
| Hitachi             | 10       | 14     | 5.03%   |
| Unknown             | 4        | 5      | 2.01%   |
| HGST                | 3        | 6      | 1.51%   |
| Maxtor              | 2        | 2      | 1.01%   |
| Fujitsu             | 2        | 2      | 1.01%   |
| Apple               | 2        | 5      | 1.01%   |
| Unknown             | 2        | 4      | 1.01%   |
| Intenso             | 1        | 2      | 0.5%    |
| Hewlett-Packard     | 1        | 2      | 0.5%    |
| ASMT109x            | 1        | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 48       | 86     | 28.74%  |
| Kingston            | 37       | 50     | 22.16%  |
| Crucial             | 20       | 29     | 11.98%  |
| SanDisk             | 10       | 10     | 5.99%   |
| WDC                 | 6        | 6      | 3.59%   |
| Intel               | 5        | 6      | 2.99%   |
| PNY                 | 4        | 4      | 2.4%    |
| OCZ                 | 4        | 4      | 2.4%    |
| Corsair             | 4        | 5      | 2.4%    |
| A-DATA Technology   | 4        | 4      | 2.4%    |
| Micron Technology   | 3        | 4      | 1.8%    |
| Intenso             | 3        | 3      | 1.8%    |
| Verbatim            | 2        | 5      | 1.2%    |
| Transcend           | 2        | 2      | 1.2%    |
| LITEON              | 2        | 2      | 1.2%    |
| Unknown (CF)        | 1        | 1      | 0.6%    |
| Toshiba             | 1        | 1      | 0.6%    |
| Team                | 1        | 1      | 0.6%    |
| SK hynix            | 1        | 1      | 0.6%    |
| Shark               | 1        | 1      | 0.6%    |
| LITEONIT            | 1        | 1      | 0.6%    |
| Leven               | 1        | 1      | 0.6%    |
| INDMEM              | 1        | 1      | 0.6%    |
| FORESEE             | 1        | 1      | 0.6%    |
| AFOX                | 1        | 1      | 0.6%    |
| ADATA SU            | 1        | 1      | 0.6%    |
| 2-Power             | 1        | 2      | 0.6%    |
| Unknown             | 1        | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 149      | 311    | 39.73%  |
| SSD     | 137      | 234    | 36.53%  |
| NVMe    | 80       | 124    | 21.33%  |
| Unknown | 7        | 8      | 1.87%   |
| MMC     | 2        | 2      | 0.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 214      | 525    | 67.51%  |
| NVMe | 78       | 122    | 24.61%  |
| SAS  | 23       | 30     | 7.26%   |
| MMC  | 2        | 2      | 0.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 155      | 261    | 48.44%  |
| 0.51-1.0   | 84       | 127    | 26.25%  |
| 1.01-2.0   | 39       | 73     | 12.19%  |
| 2.01-3.0   | 15       | 26     | 4.69%   |
| 4.01-10.0  | 14       | 35     | 4.38%   |
| 3.01-4.0   | 10       | 15     | 3.13%   |
| 10.01-20.0 | 3        | 8      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 46       | 17.69%  |
| 501-1000       | 45       | 17.31%  |
| 251-500        | 43       | 16.54%  |
| 1001-2000      | 35       | 13.46%  |
| More than 3000 | 27       | 10.38%  |
| 2001-3000      | 19       | 7.31%   |
| 1-20           | 16       | 6.15%   |
| Unknown        | 13       | 5%      |
| 21-50          | 10       | 3.85%   |
| 51-100         | 6        | 2.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 82       | 31.3%   |
| 21-50          | 39       | 14.89%  |
| 101-250        | 32       | 12.21%  |
| 251-500        | 22       | 8.4%    |
| 501-1000       | 21       | 8.02%   |
| 51-100         | 21       | 8.02%   |
| 1001-2000      | 15       | 5.73%   |
| More than 3000 | 13       | 4.96%   |
| Unknown        | 13       | 4.96%   |
| 2001-3000      | 4        | 1.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Kingston SHPM2280P2H 480G SSD     | 2        | 2      | 7.14%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 3.57%   |
| WDC WD5000AADS-00S9B0 500GB       | 1        | 1      | 3.57%   |
| WDC WD10EZRX-00A8LB0 1TB          | 1        | 1      | 3.57%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 3.57%   |
| WDC WD10EURX-73FH1Y0 1TB          | 1        | 1      | 3.57%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 3.57%   |
| Seagate ST380013AS 80GB           | 1        | 1      | 3.57%   |
| Seagate ST3400633AS 400GB         | 1        | 1      | 3.57%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 3.57%   |
| Seagate ST320LT020-9YG142 320GB   | 1        | 1      | 3.57%   |
| Seagate ST3200822AS 200GB         | 1        | 1      | 3.57%   |
| Seagate ST31000524AS 1TB          | 1        | 1      | 3.57%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 3.57%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1      | 3.57%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 3.57%   |
| SanDisk SDSSDX240GG25 240GB       | 1        | 1      | 3.57%   |
| Samsung Electronics SP0812C 80GB  | 1        | 1      | 3.57%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 3.57%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 3.57%   |
| OCZ AGILITY3 240GB SSD            | 1        | 1      | 3.57%   |
| Leven JAJS300M480C 480GB SSD      | 1        | 1      | 3.57%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 3      | 3.57%   |
| Kingston SA400S37480G 480GB SSD   | 1        | 1      | 3.57%   |
| Intel SSDSC2BW480H6 480GB         | 1        | 1      | 3.57%   |
| Hitachi HDP725032GLA360 320GB     | 1        | 2      | 3.57%   |
| Unknown                           | 1        | 2      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 32%     |
| WDC                 | 5        | 6      | 20%     |
| Kingston            | 4        | 6      | 16%     |
| Samsung Electronics | 2        | 3      | 8%      |
| SanDisk             | 1        | 1      | 4%      |
| OCZ                 | 1        | 1      | 4%      |
| Leven               | 1        | 1      | 4%      |
| Intel               | 1        | 1      | 4%      |
| Hitachi             | 1        | 2      | 4%      |
| Unknown             | 1        | 2      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 47.06%  |
| WDC                 | 5        | 6      | 29.41%  |
| Samsung Electronics | 2        | 3      | 11.76%  |
| Hitachi             | 1        | 2      | 5.88%   |
| Unknown             | 1        | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 22     | 65%     |
| SSD  | 7        | 10     | 35%     |

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
| Detected | 174      | 446    | 62.82%  |
| Works    | 83       | 201    | 29.96%  |
| Malfunc  | 20       | 32     | 7.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 153      | 40.91%  |
| AMD                          | 84       | 22.46%  |
| Samsung Electronics          | 38       | 10.16%  |
| ASMedia Technology           | 19       | 5.08%   |
| Kingston Technology Company  | 13       | 3.48%   |
| Phison Electronics           | 12       | 3.21%   |
| JMicron Technology           | 10       | 2.67%   |
| SanDisk                      | 9        | 2.41%   |
| Nvidia                       | 8        | 2.14%   |
| Marvell Technology Group     | 8        | 2.14%   |
| Micron/Crucial Technology    | 5        | 1.34%   |
| SK hynix                     | 3        | 0.8%    |
| VIA Technologies             | 2        | 0.53%   |
| Seagate Technology           | 2        | 0.53%   |
| ADATA Technology             | 2        | 0.53%   |
| Toshiba America Info Systems | 1        | 0.27%   |
| Silicon Motion               | 1        | 0.27%   |
| Realtek Semiconductor        | 1        | 0.27%   |
| HighPoint Technologies       | 1        | 0.27%   |
| Hewlett-Packard              | 1        | 0.27%   |
| Broadcom / LSI               | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 56       | 12.07%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25       | 5.39%   |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 4.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 3.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 18       | 3.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17       | 3.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16       | 3.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 1.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.72%   |
| Kingston Company A2000 NVMe SSD                                                         | 8        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.72%   |
| Phison E12 NVMe Controller                                                              | 7        | 1.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 1.51%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.29%   |
| Intel SSD 660P Series                                                                   | 6        | 1.29%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.29%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.29%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 1.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.08%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.86%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 0.86%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.86%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 0.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3        | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.65%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 206      | 57.54%  |
| NVMe | 80       | 22.35%  |
| IDE  | 55       | 15.36%  |
| RAID | 16       | 4.47%   |
| SAS  | 1        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 152      | 63.07%  |
| AMD    | 89       | 36.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i7-6700K CPU @ 4.00GHz      | 7        | 2.89%   |
| AMD Ryzen 5 3600 6-Core Processor      | 7        | 2.89%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 6        | 2.48%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 6        | 2.48%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 6        | 2.48%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 5        | 2.07%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 5        | 2.07%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.65%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 4        | 1.65%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 4        | 1.65%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 4        | 1.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 3        | 1.24%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 3        | 1.24%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 3        | 1.24%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 3        | 1.24%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 3        | 1.24%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 1.24%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 2        | 0.83%   |
| Intel Core i7-4770S CPU @ 3.10GHz      | 2        | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 2        | 0.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 0.83%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 0.83%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 2        | 0.83%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 2        | 0.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 0.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 0.83%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 2        | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 2        | 0.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 0.83%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 2        | 0.83%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 2        | 0.83%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 2        | 0.83%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 2        | 0.83%   |
| Intel 12th Gen Core i9-12900K          | 2        | 0.83%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 2        | 0.83%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 2        | 0.83%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 2        | 0.83%   |
| AMD Ryzen 7 1800X Eight-Core Processor | 2        | 0.83%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 2        | 0.83%   |
| AMD Ryzen 3 1200 Quad-Core Processor   | 2        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 48       | 19.83%  |
| Intel Core i7           | 45       | 18.6%   |
| AMD Ryzen 7             | 24       | 9.92%   |
| AMD Ryzen 5             | 17       | 7.02%   |
| Intel Core i3           | 12       | 4.96%   |
| AMD Ryzen 9             | 12       | 4.96%   |
| Intel Xeon              | 11       | 4.55%   |
| Intel Core 2 Duo        | 9        | 3.72%   |
| AMD FX                  | 8        | 3.31%   |
| Other                   | 5        | 2.07%   |
| Intel Core 2 Quad       | 4        | 1.65%   |
| Intel Celeron           | 4        | 1.65%   |
| AMD Ryzen 3             | 4        | 1.65%   |
| AMD Phenom II X4        | 4        | 1.65%   |
| AMD Athlon 64 X2        | 4        | 1.65%   |
| Intel Core i9           | 3        | 1.24%   |
| Intel Atom              | 3        | 1.24%   |
| AMD Athlon II X4        | 3        | 1.24%   |
| AMD A8                  | 3        | 1.24%   |
| AMD A6                  | 3        | 1.24%   |
| Intel Pentium Dual-Core | 2        | 0.83%   |
| Intel Pentium           | 2        | 0.83%   |
| Intel Core 2            | 2        | 0.83%   |
| AMD Ryzen Threadripper  | 2        | 0.83%   |
| AMD A10                 | 2        | 0.83%   |
| Intel Pentium Silver    | 1        | 0.41%   |
| Intel Pentium Dual      | 1        | 0.41%   |
| AMD Phenom II X2        | 1        | 0.41%   |
| AMD E                   | 1        | 0.41%   |
| AMD Athlon II Neo       | 1        | 0.41%   |
| AMD A4                  | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 103      | 42.56%  |
| 2      | 49       | 20.25%  |
| 6      | 41       | 16.94%  |
| 8      | 30       | 12.4%   |
| 12     | 8        | 3.31%   |
| 16     | 7        | 2.89%   |
| 1      | 2        | 0.83%   |
| 64     | 1        | 0.41%   |
| 24     | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 239      | 99.17%  |
| 2      | 2        | 0.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 147      | 61%     |
| 1      | 94       | 39%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 237      | 97.13%  |
| Unknown        | 7        | 2.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 53       | 21.12%  |
| 0x306c3    | 18       | 7.17%   |
| 0x306a9    | 14       | 5.58%   |
| 0x206a7    | 14       | 5.58%   |
| 0x506e3    | 13       | 5.18%   |
| 0x0800820d | 10       | 3.98%   |
| 0x906ea    | 8        | 3.19%   |
| 0x1067a    | 8        | 3.19%   |
| 0x08701021 | 7        | 2.79%   |
| 0x08701013 | 7        | 2.79%   |
| 0x906e9    | 6        | 2.39%   |
| 0x08001138 | 6        | 2.39%   |
| 0x0a201009 | 5        | 1.99%   |
| 0x06000852 | 5        | 1.99%   |
| 0x010000c8 | 5        | 1.99%   |
| 0xa0653    | 4        | 1.59%   |
| 0x906ed    | 3        | 1.2%    |
| 0x6fd      | 3        | 1.2%    |
| 0x106e5    | 3        | 1.2%    |
| 0xa0671    | 2        | 0.8%    |
| 0xa0655    | 2        | 0.8%    |
| 0x906ec    | 2        | 0.8%    |
| 0x90672    | 2        | 0.8%    |
| 0x6f6      | 2        | 0.8%    |
| 0x206c2    | 2        | 0.8%    |
| 0x10676    | 2        | 0.8%    |
| 0x08600106 | 2        | 0.8%    |
| 0x08108109 | 2        | 0.8%    |
| 0x08001137 | 2        | 0.8%    |
| 0x08001129 | 2        | 0.8%    |
| 0x06001119 | 2        | 0.8%    |
| 0x0600063e | 2        | 0.8%    |
| 0x010000db | 2        | 0.8%    |
| 0x906eb    | 1        | 0.4%    |
| 0x906c0    | 1        | 0.4%    |
| 0x806ea    | 1        | 0.4%    |
| 0x706a1    | 1        | 0.4%    |
| 0x6fb      | 1        | 0.4%    |
| 0x506c9    | 1        | 0.4%    |
| 0x406f1    | 1        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 27       | 11.16%  |
| Haswell          | 26       | 10.74%  |
| Zen 2            | 25       | 10.33%  |
| IvyBridge        | 19       | 7.85%   |
| Skylake          | 17       | 7.02%   |
| SandyBridge      | 16       | 6.61%   |
| Zen+             | 13       | 5.37%   |
| Penryn           | 13       | 5.37%   |
| Zen              | 11       | 4.55%   |
| Zen 3            | 10       | 4.13%   |
| Piledriver       | 9        | 3.72%   |
| K10              | 9        | 3.72%   |
| Core             | 6        | 2.48%   |
| CometLake        | 6        | 2.48%   |
| Nehalem          | 5        | 2.07%   |
| Westmere         | 4        | 1.65%   |
| K8 Hammer        | 4        | 1.65%   |
| Steamroller      | 2        | 0.83%   |
| Puma             | 2        | 0.83%   |
| Icelake          | 2        | 0.83%   |
| Bulldozer        | 2        | 0.83%   |
| Broadwell        | 2        | 0.83%   |
| Bonnell          | 2        | 0.83%   |
| Alderlake Hybrid | 2        | 0.83%   |
| Unknown          | 2        | 0.83%   |
| Silvermont       | 1        | 0.41%   |
| Jaguar           | 1        | 0.41%   |
| Goldmont plus    | 1        | 0.41%   |
| Goldmont         | 1        | 0.41%   |
| Excavator        | 1        | 0.41%   |
| Bobcat           | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 142      | 53.38%  |
| AMD               | 66       | 24.81%  |
| Intel             | 57       | 21.43%  |
| ASPEED Technology | 1        | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 4.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 3.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 3.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 7        | 2.58%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 2.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 2.21%   |
| Intel HD Graphics 530                                                       | 6        | 2.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.21%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.85%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 1.48%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 1.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.48%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.48%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 1.48%   |
| Intel HD Graphics 630                                                       | 4        | 1.48%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1.11%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 1.11%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 3        | 1.11%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 1.11%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 1.11%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.11%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.11%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.11%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.11%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 3        | 1.11%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.11%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.74%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.74%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 2        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.74%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.74%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 130      | 53.5%   |
| 1 x AMD         | 56       | 23.05%  |
| 1 x Intel       | 39       | 16.05%  |
| Intel + Nvidia  | 6        | 2.47%   |
| 2 x AMD         | 3        | 1.23%   |
| Intel + AMD     | 3        | 1.23%   |
| AMD + Nvidia    | 3        | 1.23%   |
| 2 x Nvidia      | 2        | 0.82%   |
| Nvidia + ASPEED | 1        | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 157      | 62.8%   |
| Proprietary | 87       | 34.8%   |
| Unknown     | 6        | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 79       | 31.73%  |
| 1.01-2.0   | 53       | 21.29%  |
| 7.01-8.0   | 35       | 14.06%  |
| 5.01-6.0   | 20       | 8.03%   |
| 3.01-4.0   | 18       | 7.23%   |
| 0.01-0.5   | 17       | 6.83%   |
| 0.51-1.0   | 15       | 6.02%   |
| 8.01-16.0  | 10       | 4.02%   |
| 4.01-5.0   | 1        | 0.4%    |
| 2.01-3.0   | 1        | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 57       | 20.43%  |
| Dell                    | 24       | 8.6%    |
| Ancor Communications    | 21       | 7.53%   |
| AOC                     | 19       | 6.81%   |
| Philips                 | 17       | 6.09%   |
| Acer                    | 16       | 5.73%   |
| Hewlett-Packard         | 15       | 5.38%   |
| BenQ                    | 14       | 5.02%   |
| Goldstar                | 12       | 4.3%    |
| ASUSTek Computer        | 11       | 3.94%   |
| Lenovo                  | 9        | 3.23%   |
| Sony                    | 8        | 2.87%   |
| Unknown                 | 6        | 2.15%   |
| Medion                  | 5        | 1.79%   |
| Lenovo Group Limited    | 5        | 1.79%   |
| LG Electronics          | 4        | 1.43%   |
| ViewSonic               | 2        | 0.72%   |
| Vestel Elektronik       | 2        | 0.72%   |
| Tech Concepts           | 2        | 0.72%   |
| MSI                     | 2        | 0.72%   |
| Idek Iiyama             | 2        | 0.72%   |
| IBM                     | 2        | 0.72%   |
| Gigabyte Technology     | 2        | 0.72%   |
| Fujitsu Siemens         | 2        | 0.72%   |
| AUS                     | 2        | 0.72%   |
| Unknown                 | 2        | 0.72%   |
| Wacom                   | 1        | 0.36%   |
| Vestel                  | 1        | 0.36%   |
| TopView                 | 1        | 0.36%   |
| Pixio                   | 1        | 0.36%   |
| Pioneer                 | 1        | 0.36%   |
| Panasonic               | 1        | 0.36%   |
| Packard Bell            | 1        | 0.36%   |
| OTC                     | 1        | 0.36%   |
| OEM                     | 1        | 0.36%   |
| Iiyama                  | 1        | 0.36%   |
| IFS                     | 1        | 0.36%   |
| Eizo                    | 1        | 0.36%   |
| Chi Mei Optoelectronics | 1        | 0.36%   |
| AU Optronics            | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 1.91%   |
| Sony TV SNYEE01 1920x1080                                             | 3        | 0.96%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3        | 0.96%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 3        | 0.96%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                     | 3        | 0.96%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 2        | 0.64%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                      | 2        | 0.64%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch  | 2        | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.64%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 2        | 0.64%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.64%   |
| Medion MD20444 MED3661 1920x1080 521x293mm 23.5-inch                  | 2        | 0.64%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                | 2        | 0.64%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch       | 2        | 0.64%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                     | 2        | 0.64%   |
| Dell P1913 DELA089 1440x900 408x255mm 18.9-inch                       | 2        | 0.64%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 2        | 0.64%   |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                   | 2        | 0.64%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 2        | 0.64%   |
| ASUSTek Computer VA249 AUS24C1 1920x1080 527x296mm 23.8-inch          | 2        | 0.64%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 2        | 0.64%   |
| AOC 2450W AOC2450 1920x1080 520x290mm 23.4-inch                       | 2        | 0.64%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 2        | 0.64%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 0.64%   |
| Ancor Communications ASUS VP278 ACI27C8 1920x1080 598x336mm 27.0-inch | 2        | 0.64%   |
| Unknown                                                               | 2        | 0.64%   |
| Wacom Cintiq 16 WAC1064 1920x1080 344x193mm 15.5-inch                 | 1        | 0.32%   |
| ViewSonic VX2880ML VSCCE2F 3840x2160 621x341mm 27.9-inch              | 1        | 0.32%   |
| ViewSonic VG2236 SERIES VSCE726 1920x1080 477x268mm 21.5-inch         | 1        | 0.32%   |
| Vestel LCD Monitor 49UHD_LCD_TV 3840x2160                             | 1        | 0.32%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.32%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.32%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.32%   |
| Unknown LCD Monitor Nexgen MIRAI DML-517 1280x1024                    | 1        | 0.32%   |
| Unknown LCD Monitor Dell S2716DG 2560x1440                            | 1        | 0.32%   |
| Unknown LCD Monitor CHD PMOS320-IQC-1 4608x1440                       | 1        | 0.32%   |
| Unknown LCD Monitor CHD PMOS320-IQC-1                                 | 1        | 0.32%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                   | 1        | 0.32%   |
| Sony TV SNYD301 1360x768                                              | 1        | 0.32%   |
| Sony TV SNYA401 1920x1080                                             | 1        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 129      | 46.91%  |
| 3840x2160 (4K)     | 28       | 10.18%  |
| 2560x1440 (QHD)    | 28       | 10.18%  |
| Unknown            | 16       | 5.82%   |
| 1680x1050 (WSXGA+) | 14       | 5.09%   |
| 1280x1024 (SXGA)   | 11       | 4%      |
| 3840x1080          | 6        | 2.18%   |
| 3440x1440          | 6        | 2.18%   |
| 1600x900 (HD+)     | 5        | 1.82%   |
| 1440x900 (WXGA+)   | 5        | 1.82%   |
| 1920x1200 (WUXGA)  | 3        | 1.09%   |
| 1360x768           | 3        | 1.09%   |
| 3840x1200          | 2        | 0.73%   |
| 1920x540           | 2        | 0.73%   |
| 9840x3840          | 1        | 0.36%   |
| 6400x2160          | 1        | 0.36%   |
| 5760x1440          | 1        | 0.36%   |
| 5760x1080          | 1        | 0.36%   |
| 5120x1440          | 1        | 0.36%   |
| 4608x1440          | 1        | 0.36%   |
| 4480x1440          | 1        | 0.36%   |
| 3840x1600          | 1        | 0.36%   |
| 3200x1200          | 1        | 0.36%   |
| 3200x1080          | 1        | 0.36%   |
| 2560x1600          | 1        | 0.36%   |
| 2560x1080          | 1        | 0.36%   |
| 2560x1024          | 1        | 0.36%   |
| 2048x1152          | 1        | 0.36%   |
| 1600x1200          | 1        | 0.36%   |
| 1366x768 (WXGA)    | 1        | 0.36%   |
| 1360x765           | 1        | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 51       | 18.48%  |
| Unknown | 46       | 16.67%  |
| 24      | 44       | 15.94%  |
| 23      | 33       | 11.96%  |
| 31      | 18       | 6.52%   |
| 21      | 18       | 6.52%   |
| 19      | 11       | 3.99%   |
| 22      | 10       | 3.62%   |
| 20      | 9        | 3.26%   |
| 72      | 7        | 2.54%   |
| 34      | 6        | 2.17%   |
| 84      | 4        | 1.45%   |
| 15      | 3        | 1.09%   |
| 28      | 2        | 0.72%   |
| 17      | 2        | 0.72%   |
| 65      | 1        | 0.36%   |
| 60      | 1        | 0.36%   |
| 54      | 1        | 0.36%   |
| 48      | 1        | 0.36%   |
| 39      | 1        | 0.36%   |
| 38      | 1        | 0.36%   |
| 33      | 1        | 0.36%   |
| 32      | 1        | 0.36%   |
| 30      | 1        | 0.36%   |
| 29      | 1        | 0.36%   |
| 25      | 1        | 0.36%   |
| 18      | 1        | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 108      | 41.06%  |
| Unknown     | 46       | 17.49%  |
| 401-500     | 42       | 15.97%  |
| 601-700     | 30       | 11.41%  |
| 1501-2000   | 11       | 4.18%   |
| 701-800     | 8        | 3.04%   |
| 351-400     | 7        | 2.66%   |
| 301-350     | 5        | 1.9%    |
| 1001-1500   | 4        | 1.52%   |
| 801-900     | 2        | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 156      | 63.16%  |
| Unknown | 41       | 16.6%   |
| 16/10   | 28       | 11.34%  |
| 5/4     | 9        | 3.64%   |
| 21/9    | 8        | 3.24%   |
| 4/3     | 2        | 0.81%   |
| 32/9    | 2        | 0.81%   |
| 3/2     | 1        | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 84       | 31%     |
| 301-350        | 51       | 18.82%  |
| Unknown        | 46       | 16.97%  |
| 351-500        | 29       | 10.7%   |
| 151-200        | 24       | 8.86%   |
| 251-300        | 15       | 5.54%   |
| More than 1000 | 14       | 5.17%   |
| 501-1000       | 3        | 1.11%   |
| 141-150        | 2        | 0.74%   |
| 101-110        | 2        | 0.74%   |
| 111-120        | 1        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 146      | 57.71%  |
| Unknown | 46       | 18.18%  |
| 101-120 | 41       | 16.21%  |
| 1-50    | 9        | 3.56%   |
| 121-160 | 9        | 3.56%   |
| 161-240 | 2        | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 171      | 69.8%   |
| 2     | 54       | 22.04%  |
| 0     | 12       | 4.9%    |
| 3     | 8        | 3.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 147      | 42.24%  |
| Intel                           | 108      | 31.03%  |
| Qualcomm Atheros                | 13       | 3.74%   |
| Broadcom                        | 13       | 3.74%   |
| Nvidia                          | 8        | 2.3%    |
| Ralink                          | 6        | 1.72%   |
| TP-Link                         | 5        | 1.44%   |
| Ralink Technology               | 5        | 1.44%   |
| ASUSTek Computer                | 5        | 1.44%   |
| Qualcomm Atheros Communications | 4        | 1.15%   |
| IMC Networks                    | 4        | 1.15%   |
| Huawei Technologies             | 4        | 1.15%   |
| Aquantia                        | 4        | 1.15%   |
| OnePlus Technology (Shenzhen)   | 3        | 0.86%   |
| Edimax Technology               | 3        | 0.86%   |
| Microsoft                       | 2        | 0.57%   |
| MediaTek                        | 2        | 0.57%   |
| D-Link                          | 2        | 0.57%   |
| Texas Instruments               | 1        | 0.29%   |
| Solarflare Communications       | 1        | 0.29%   |
| Samsung Electronics             | 1        | 0.29%   |
| Linksys                         | 1        | 0.29%   |
| JMicron Technology              | 1        | 0.29%   |
| InterBiometrics                 | 1        | 0.29%   |
| ICS Advent                      | 1        | 0.29%   |
| HMD Global                      | 1        | 0.29%   |
| D-Link System                   | 1        | 0.29%   |
| ASIX Electronics                | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 118      | 29.5%   |
| Intel I211 Gigabit Network Connection                                                | 22       | 5.5%    |
| Intel Ethernet Connection (2) I219-V                                                 | 16       | 4%      |
| Realtek RTL8125 2.5GbE Controller                                                    | 13       | 3.25%   |
| Intel Wi-Fi 6 AX200                                                                  | 12       | 3%      |
| Intel Wireless-AC 9260                                                               | 7        | 1.75%   |
| Intel Ethernet Controller I225-V                                                     | 7        | 1.75%   |
| Intel Ethernet Connection I217-LM                                                    | 7        | 1.75%   |
| Intel Ethernet Connection (7) I219-V                                                 | 7        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 7        | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 7        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 6        | 1.5%    |
| Realtek 802.11ac NIC                                                                 | 4        | 1%      |
| Intel Ethernet Connection (2) I218-V                                                 | 4        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                                           | 4        | 1%      |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 1%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                    | 4        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3        | 0.75%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                      | 3        | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 0.75%   |
| OnePlus (Shenzhen) OnePlus                                                           | 3        | 0.75%   |
| Intel 82579V Gigabit Network Connection                                              | 3        | 0.75%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2        | 0.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 2        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 2        | 0.5%    |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 0.5%    |
| Ralink MT7601U Wireless Adapter                                                      | 2        | 0.5%    |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 0.5%    |
| Nvidia MCP73 Ethernet                                                                | 2        | 0.5%    |
| Nvidia MCP61 Ethernet                                                                | 2        | 0.5%    |
| Intel I210 Gigabit Network Connection                                                | 2        | 0.5%    |
| Intel Ethernet Connection I217-V                                                     | 2        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 37       | 30.83%  |
| Realtek Semiconductor           | 26       | 21.67%  |
| Broadcom                        | 10       | 8.33%   |
| Qualcomm Atheros                | 8        | 6.67%   |
| Ralink                          | 6        | 5%      |
| TP-Link                         | 5        | 4.17%   |
| Ralink Technology               | 5        | 4.17%   |
| ASUSTek Computer                | 5        | 4.17%   |
| Qualcomm Atheros Communications | 4        | 3.33%   |
| IMC Networks                    | 4        | 3.33%   |
| Edimax Technology               | 3        | 2.5%    |
| Microsoft                       | 2        | 1.67%   |
| D-Link                          | 2        | 1.67%   |
| MediaTek                        | 1        | 0.83%   |
| Linksys                         | 1        | 0.83%   |
| D-Link System                   | 1        | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 12       | 9.68%   |
| Intel Wireless-AC 9260                                                               | 7        | 5.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 7        | 5.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 7        | 5.65%   |
| Realtek 802.11ac NIC                                                                 | 4        | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 3.23%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3        | 2.42%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 2.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 2.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 2.42%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.61%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 1.61%   |
| Ralink MT7601U Wireless Adapter                                                      | 2        | 1.61%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 1.61%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 1.61%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.61%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 2        | 1.61%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.81%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1        | 0.81%   |
| TP-Link Archer T4U ver.3                                                             | 1        | 0.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1        | 0.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 1        | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.81%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.81%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 1        | 0.81%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                           | 1        | 0.81%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 1        | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.81%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 1        | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 1        | 0.81%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 0.81%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                            | 1        | 0.81%   |
| Ralink RT2800 802.11n PCI                                                            | 1        | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 1        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 136      | 51.71%  |
| Intel                         | 94       | 35.74%  |
| Nvidia                        | 8        | 3.04%   |
| Qualcomm Atheros              | 6        | 2.28%   |
| Aquantia                      | 4        | 1.52%   |
| OnePlus Technology (Shenzhen) | 3        | 1.14%   |
| Broadcom                      | 3        | 1.14%   |
| Huawei Technologies           | 2        | 0.76%   |
| Solarflare Communications     | 1        | 0.38%   |
| Samsung Electronics           | 1        | 0.38%   |
| MediaTek                      | 1        | 0.38%   |
| JMicron Technology            | 1        | 0.38%   |
| ICS Advent                    | 1        | 0.38%   |
| HMD Global                    | 1        | 0.38%   |
| ASIX Electronics              | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 118      | 43.38%  |
| Intel I211 Gigabit Network Connection                             | 22       | 8.09%   |
| Intel Ethernet Connection (2) I219-V                              | 16       | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 4.78%   |
| Intel Ethernet Controller I225-V                                  | 7        | 2.57%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.57%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 2.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 2.21%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.47%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 1.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.1%    |
| OnePlus (Shenzhen) OnePlus                                        | 3        | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.74%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.74%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.74%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.74%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.74%   |
| Huawei YAL-L21                                                    | 2        | 0.74%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.37%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.37%   |
| Nvidia MCP79 Ethernet                                             | 1        | 0.37%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.37%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.37%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.37%   |
| MediaTek Nokia 5.1 Plus                                           | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 240      | 67.04%  |
| WiFi     | 114      | 31.84%  |
| Modem    | 4        | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 192      | 76.19%  |
| WiFi     | 60       | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 143      | 59.34%  |
| 2     | 82       | 34.02%  |
| 3     | 13       | 5.39%   |
| 0     | 2        | 0.83%   |
| 4     | 1        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 233      | 96.28%  |
| Yes  | 9        | 3.72%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 36       | 45.57%  |
| Cambridge Silicon Radio         | 22       | 27.85%  |
| Qualcomm Atheros Communications | 4        | 5.06%   |
| Broadcom                        | 4        | 5.06%   |
| ASUSTek Computer                | 4        | 5.06%   |
| IMC Networks                    | 3        | 3.8%    |
| Belkin Components               | 2        | 2.53%   |
| Realtek Semiconductor           | 1        | 1.27%   |
| MediaTek                        | 1        | 1.27%   |
| HTC (High Tech Computer)        | 1        | 1.27%   |
| Edimax Technology               | 1        | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 22       | 27.85%  |
| Intel AX200 Bluetooth                                                | 11       | 13.92%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 8.86%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7        | 8.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 5.06%   |
| Intel Bluetooth wireless interface                                   | 3        | 3.8%    |
| IMC Networks Bluetooth Radio                                         | 3        | 3.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2        | 2.53%   |
| Intel AX201 Bluetooth                                                | 2        | 2.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 2.53%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 2.53%   |
| ASUS Bluetooth Radio                                                 | 2        | 2.53%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 1.27%   |
| MediaTek Wireless_Device                                             | 1        | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 1.27%   |
| Intel AX210 Bluetooth                                                | 1        | 1.27%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.27%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 1.27%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 1.27%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 1.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 1.27%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 140      | 30.17%  |
| Nvidia                  | 139      | 29.96%  |
| AMD                     | 107      | 23.06%  |
| SteelSeries ApS         | 14       | 3.02%   |
| Kingston Technology     | 9        | 1.94%   |
| C-Media Electronics     | 9        | 1.94%   |
| Creative Labs           | 6        | 1.29%   |
| Logitech                | 4        | 0.86%   |
| GN Netcom               | 4        | 0.86%   |
| Creative Technology     | 4        | 0.86%   |
| ASUSTek Computer        | 4        | 0.86%   |
| Yamaha                  | 2        | 0.43%   |
| VIA Technologies        | 2        | 0.43%   |
| Texas Instruments       | 2        | 0.43%   |
| Realtek Semiconductor   | 2        | 0.43%   |
| Razer USA               | 2        | 0.43%   |
| Unknown                 | 1        | 0.22%   |
| Turtle Beach            | 1        | 0.22%   |
| Tenx Technology         | 1        | 0.22%   |
| Syntek                  | 1        | 0.22%   |
| Shure                   | 1        | 0.22%   |
| RODE Microphones        | 1        | 0.22%   |
| ROCCAT                  | 1        | 0.22%   |
| JMTek                   | 1        | 0.22%   |
| Focusrite-Novation      | 1        | 0.22%   |
| Corsair                 | 1        | 0.22%   |
| BR25                    | 1        | 0.22%   |
| BEHRINGER International | 1        | 0.22%   |
| Audio-Technica          | 1        | 0.22%   |
| Astro Gaming            | 1        | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 5.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 20       | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19       | 3.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18       | 3.47%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16       | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 2.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 14       | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 2.31%   |
| AMD Navi 10 HDMI Audio                                                     | 12       | 2.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 2.12%   |
| Nvidia TU104 HD Audio Controller                                           | 10       | 1.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 9        | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 1.73%   |
| Nvidia GK104 HDMI Audio Controller                                         | 8        | 1.54%   |
| Kingston Technology HyperX 7.1 Audio                                       | 8        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 1.35%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.16%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 1.16%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 5        | 0.96%   |
| Nvidia GP102 HDMI Audio Controller                                         | 5        | 0.96%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 0.96%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 4        | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 0.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                   | 4        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 32       | 24.62%  |
| Kingston            | 22       | 16.92%  |
| G.Skill             | 19       | 14.62%  |
| Unknown             | 14       | 10.77%  |
| Samsung Electronics | 14       | 10.77%  |
| Crucial             | 10       | 7.69%   |
| Micron Technology   | 7        | 5.38%   |
| SK hynix            | 5        | 3.85%   |
| Ramaxel Technology  | 2        | 1.54%   |
| Nanya Technology    | 2        | 1.54%   |
| Unifosa             | 1        | 0.77%   |
| Elpida              | 1        | 0.77%   |
| Unknown             | 1        | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 7        | 5%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 4        | 2.86%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 3        | 2.14%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 2        | 1.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 2        | 1.43%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 2        | 1.43%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 2        | 1.43%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 2        | 1.43%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 1.43%   |
| Kingston RAM HP24D4U7S8MBP-8 8192MB DIMM DDR4 2400MT/s   | 2        | 1.43%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 2        | 1.43%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 1.43%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 2        | 1.43%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s   | 2        | 1.43%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 2        | 1.43%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                 | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                     | 1        | 0.71%   |
| Unknown RAM Module 4096MB DIMM                           | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.71%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 0.71%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s               | 1        | 0.71%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s       | 1        | 0.71%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s        | 1        | 0.71%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s    | 1        | 0.71%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.71%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 0.71%   |
| SK hynix RAM HMT325U6CFR8C-H9 2048MB DIMM DDR3 1333MT/s  | 1        | 0.71%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 1        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s | 1        | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.71%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 0.71%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 0.71%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 65       | 55.08%  |
| DDR3    | 34       | 28.81%  |
| Unknown | 11       | 9.32%   |
| SDRAM   | 6        | 5.08%   |
| DDR     | 2        | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 110      | 94.83%  |
| SODIMM | 6        | 5.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 57       | 45.97%  |
| 4096  | 26       | 20.97%  |
| 16384 | 19       | 15.32%  |
| 2048  | 15       | 12.1%   |
| 32768 | 4        | 3.23%   |
| 1024  | 2        | 1.61%   |
| 512   | 1        | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 17.83%  |
| 3600    | 14       | 10.85%  |
| 1333    | 14       | 10.85%  |
| 3200    | 13       | 10.08%  |
| 2400    | 9        | 6.98%   |
| 3466    | 6        | 4.65%   |
| 2667    | 6        | 4.65%   |
| 2933    | 5        | 3.88%   |
| 2133    | 5        | 3.88%   |
| 3400    | 4        | 3.1%    |
| 667     | 3        | 2.33%   |
| 3666    | 2        | 1.55%   |
| 3500    | 2        | 1.55%   |
| 3000    | 2        | 1.55%   |
| 2048    | 2        | 1.55%   |
| 1867    | 2        | 1.55%   |
| Unknown | 2        | 1.55%   |
| 20306   | 1        | 0.78%   |
| 4800    | 1        | 0.78%   |
| 4400    | 1        | 0.78%   |
| 4000    | 1        | 0.78%   |
| 3800    | 1        | 0.78%   |
| 3533    | 1        | 0.78%   |
| 3333    | 1        | 0.78%   |
| 3100    | 1        | 0.78%   |
| 2733    | 1        | 0.78%   |
| 1866    | 1        | 0.78%   |
| 1800    | 1        | 0.78%   |
| 1639    | 1        | 0.78%   |
| 1334    | 1        | 0.78%   |
| 1066    | 1        | 0.78%   |
| 533     | 1        | 0.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 53.85%  |
| Brother Industries  | 4        | 30.77%  |
| Prolific Technology | 1        | 7.69%   |
| Canon               | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port      | 1        | 7.69%   |
| HP LaserJet 1020                   | 1        | 7.69%   |
| HP ENVY Photo 6200 series          | 1        | 7.69%   |
| HP ENVY 4520 series                | 1        | 7.69%   |
| HP Deskjet D4300 series            | 1        | 7.69%   |
| HP DeskJet 5940                    | 1        | 7.69%   |
| HP DeskJet 5550                    | 1        | 7.69%   |
| HP DeskJet 2620 All-in-One Printer | 1        | 7.69%   |
| Canon iP7200 series                | 1        | 7.69%   |
| Brother HL-5250DN Printer          | 1        | 7.69%   |
| Brother HL-2240D series            | 1        | 7.69%   |
| Brother HL-2030 Laser Printer      | 1        | 7.69%   |
| Brother DCP-J140W                  | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP ScanJet 5470c/5490c | 1        | 50%     |
| HP PSC 1200            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 20       | 55.56%  |
| Trust                                  | 2        | 5.56%   |
| Sunplus Innovation Technology          | 2        | 5.56%   |
| Samsung Electronics                    | 2        | 5.56%   |
| Microsoft                              | 2        | 5.56%   |
| Quanta                                 | 1        | 2.78%   |
| Oculus VR                              | 1        | 2.78%   |
| Intel                                  | 1        | 2.78%   |
| Hewlett-Packard                        | 1        | 2.78%   |
| Cubeternet                             | 1        | 2.78%   |
| Creative Technology                    | 1        | 2.78%   |
| Chicony Electronics                    | 1        | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech StreamCam                                                   | 3        | 8.33%   |
| Logitech HD Webcam C525                                              | 3        | 8.33%   |
| Trust USB Camera                                                     | 2        | 5.56%   |
| Samsung Galaxy A5 (MTP)                                              | 2        | 5.56%   |
| Logitech Webcam C270                                                 | 2        | 5.56%   |
| Logitech HD Pro Webcam C920                                          | 2        | 5.56%   |
| Logitech C930c                                                       | 2        | 5.56%   |
| Sunplus SunplusIT PC Camera                                          | 1        | 2.78%   |
| Sunplus Sandberg USB Webcam Pro                                      | 1        | 2.78%   |
| Quanta FREETALK HD                                                   | 1        | 2.78%   |
| Oculus VR Quest 2                                                    | 1        | 2.78%   |
| Microsoft MicrosoftÂ LifeCam Studio                                 | 1        | 2.78%   |
| Microsoft LifeCam HD-3000                                            | 1        | 2.78%   |
| Logitech Webcam Pro 9000                                             | 1        | 2.78%   |
| Logitech Webcam C930e                                                | 1        | 2.78%   |
| Logitech Webcam C925e                                                | 1        | 2.78%   |
| Logitech QuickCam Pro 5000                                           | 1        | 2.78%   |
| Logitech QuickCam E 3500                                             | 1        | 2.78%   |
| Logitech HD Webcam C510                                              | 1        | 2.78%   |
| Logitech C922 Pro Stream Webcam                                      | 1        | 2.78%   |
| Logitech C670i FHD Webcam                                            | 1        | 2.78%   |
| Intel RealSense Camera SR300                                         | 1        | 2.78%   |
| HP HD-4110 Webcam                                                    | 1        | 2.78%   |
| Cubeternet USB2.0 Camera                                             | 1        | 2.78%   |
| Creative Live! Cam Sync 1080p                                        | 1        | 2.78%   |
| Chicony Gateway Webcam                                               | 1        | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 2.78%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Advanced Card Systems ACR1252 Dual Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 208      | 84.55%  |
| 1     | 26       | 10.57%  |
| 2     | 8        | 3.25%   |
| 3     | 2        | 0.81%   |
| 6     | 1        | 0.41%   |
| 4     | 1        | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 26.53%  |
| Graphics card            | 9        | 18.37%  |
| Multimedia controller    | 6        | 12.24%  |
| Sound                    | 5        | 10.2%   |
| Communication controller | 5        | 10.2%   |
| Unassigned class         | 4        | 8.16%   |
| Storage/raid             | 2        | 4.08%   |
| Unclassified device      | 1        | 2.04%   |
| Net/ethernet             | 1        | 2.04%   |
| Chipcard                 | 1        | 2.04%   |
| Card reader              | 1        | 2.04%   |
| Camera                   | 1        | 2.04%   |

