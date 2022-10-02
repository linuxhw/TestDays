ALT Linux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

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

Total: 218

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | NBD-WXX9                    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| ASUSTek       | T100TAM                     | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| HUAWEI        | BOD-WXX9                    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | X550ZE                      | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| HP            | Pavilion g7                 | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| Lenovo        | G570 20079                  | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| HP            | Pavilion dv7                | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| Kraftway      | ACCORD                      | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| Panasonic     | CF-20-1                     | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| ICL           | Unknown                     | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| Lenovo        | V130-15IKB 81HN             | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| Apple         | MacBook7,1                  | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Lenovo        | G570 20079                  | [db9d229530](https://linux-hardware.org/?probe=db9d229530) | May 19, 2022 |
| Sony          | SVE1512H1RB                 | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| ICL           | NJ50_70CU                   | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| Notebook      | NLx0MU                      | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Lenovo        | G570 20079                  | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| HP            | ZBook 17 G5                 | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| HP            | EliteBook 840 G4            | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| HP            | 250 G7 Notebook PC          | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| HP            | ProBook 440 G5              | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Timi          | TM1701                      | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| HP            | EliteBook 840 G4            | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Dell          | Latitude 3420               | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| Dell          | G5 5590                     | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| ASUSTek       | X200MA                      | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| Dell          | Latitude 3590               | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Samsung       | 750XDA                      | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASUSTek       | N46VZ                       | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Timi          | TM1701                      | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | N46VZ                       | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Durabook      | Z14                         | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| Aquarius      | NS585                       | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Dell          | G3 3779                     | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| HP            | EliteBook 8470p             | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Lenovo        | B50-10 80QR                 | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Acer          | NC-ES1-131-C1NL             | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| HP            | EliteBook 8470p             | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| HP            | Laptop 14s-dq1xxx           | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| Toshiba       | Satellite A100              | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| MSI           | X300/X340/X400 series       | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| ASUSTek       | N46VZ                       | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Samsung       | R510/P510                   | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire E1-571G              | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| HP            | Pavilion dv6700             | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| MSI           | MEGA BOOK S430              | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Lenovo        | G505s 20255                 | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| Samsung       | RV413/RV513/E3413           | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| Acer          | Aspire ES1-523              | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | 1001PXD                     | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Acer          | Aspire ES1-523              | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 54        | 33.75%  |
| ALT Linux 10.0     | 27        | 16.88%  |
| ALT Linux 9.1      | 22        | 13.75%  |
| ALT Linux 9.2      | 10        | 6.25%   |
| ALT Linux 10.1     | 10        | 6.25%   |
| ALT Linux 9.0      | 9         | 5.63%   |
| MOS 10             | 7         | 4.38%   |
| ALT Linux 10.0.900 | 3         | 1.88%   |
| ALT Linux P9       | 2         | 1.25%   |
| ALT Linux P8       | 2         | 1.25%   |
| ALT Linux 8.2      | 2         | 1.25%   |
| ALT Linux 20201124 | 2         | 1.25%   |
| ALT Linux 20191026 | 2         | 1.25%   |
| ALT Linux P10      | 1         | 0.63%   |
| ALT Linux 9        | 1         | 0.63%   |
| ALT Linux 8.990    | 1         | 0.63%   |
| ALT Linux 8.920    | 1         | 0.63%   |
| ALT Linux 8.3      | 1         | 0.63%   |
| ALT Linux 8.0.0    | 1         | 0.63%   |
| ALT Linux 20190624 | 1         | 0.63%   |
| ALT Linux          | 1         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 152       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.102-std-def-alt1    | 36        | 21.18%  |
| 5.10.109-std-def-alt1    | 19        | 11.18%  |
| 5.15.34-un-def-alt1      | 6         | 3.53%   |
| 5.10.88-std-def-alt1     | 6         | 3.53%   |
| 5.10.82-std-def-alt1     | 4         | 2.35%   |
| 5.10.123-std-def-alt1    | 4         | 2.35%   |
| 5.4.68-std-def-alt1.1    | 3         | 1.76%   |
| 5.4.28-std-def-alt1      | 3         | 1.76%   |
| 5.10.139-std-def-alt1    | 3         | 1.76%   |
| 5.4.62-std-def-alt1      | 2         | 1.18%   |
| 5.4.51-std-def-alt1      | 2         | 1.18%   |
| 5.15.52-un-def-alt1      | 2         | 1.18%   |
| 5.15.33-un-def-alt1      | 2         | 1.18%   |
| 5.15.25-un-def-alt1      | 2         | 1.18%   |
| 5.10.62-un-def-alt1      | 2         | 1.18%   |
| 5.10.61-un-def-alt1      | 2         | 1.18%   |
| 5.10.37-un-def-alt1      | 2         | 1.18%   |
| 5.10.32-un-def-alt1      | 2         | 1.18%   |
| 5.10.17-un-def-alt1      | 2         | 1.18%   |
| 5.10.113-std-def-alt1    | 2         | 1.18%   |
| 5.10.111-std-def-alt1    | 2         | 1.18%   |
| 4.19.79-std-def-alt1     | 2         | 1.18%   |
| 4.19.66-std-def-alt1     | 2         | 1.18%   |
| 4.19.102-std-def-alt1    | 2         | 1.18%   |
| 5.7.19-un-def-alt1       | 1         | 0.59%   |
| 5.4.98-std-def-alt1      | 1         | 0.59%   |
| 5.4.87-std-def-alt1      | 1         | 0.59%   |
| 5.4.85-std-def-alt1      | 1         | 0.59%   |
| 5.4.84-std-def-alt1      | 1         | 0.59%   |
| 5.4.44-std-def-alt1      | 1         | 0.59%   |
| 5.4.41-std-def-alt1      | 1         | 0.59%   |
| 5.4.3-un-def-alt1        | 1         | 0.59%   |
| 5.4.171-std-def-alt1     | 1         | 0.59%   |
| 5.4.144-std-def-alt1     | 1         | 0.59%   |
| 5.4.127-std-def-alt1     | 1         | 0.59%   |
| 5.4.117-std-def-alt1     | 1         | 0.59%   |
| 5.4.115-std-def-alt1     | 1         | 0.59%   |
| 5.4.107-std-def-alt1     | 1         | 0.59%   |
| 5.4.107-std-def-alt0.c9f | 1         | 0.59%   |
| 5.3.5-un-def-alt1        | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.102 | 36        | 21.18%  |
| 5.10.109 | 19        | 11.18%  |
| 5.15.34  | 6         | 3.53%   |
| 5.10.88  | 6         | 3.53%   |
| 5.10.82  | 4         | 2.35%   |
| 5.10.123 | 4         | 2.35%   |
| 5.4.68   | 3         | 1.76%   |
| 5.4.28   | 3         | 1.76%   |
| 5.10.139 | 3         | 1.76%   |
| 5.4.62   | 2         | 1.18%   |
| 5.4.51   | 2         | 1.18%   |
| 5.4.107  | 2         | 1.18%   |
| 5.15.52  | 2         | 1.18%   |
| 5.15.33  | 2         | 1.18%   |
| 5.15.25  | 2         | 1.18%   |
| 5.10.62  | 2         | 1.18%   |
| 5.10.61  | 2         | 1.18%   |
| 5.10.37  | 2         | 1.18%   |
| 5.10.32  | 2         | 1.18%   |
| 5.10.17  | 2         | 1.18%   |
| 5.10.118 | 2         | 1.18%   |
| 5.10.113 | 2         | 1.18%   |
| 5.10.111 | 2         | 1.18%   |
| 4.19.79  | 2         | 1.18%   |
| 4.19.66  | 2         | 1.18%   |
| 4.19.102 | 2         | 1.18%   |
| 5.7.19   | 1         | 0.59%   |
| 5.4.98   | 1         | 0.59%   |
| 5.4.87   | 1         | 0.59%   |
| 5.4.85   | 1         | 0.59%   |
| 5.4.84   | 1         | 0.59%   |
| 5.4.44   | 1         | 0.59%   |
| 5.4.41   | 1         | 0.59%   |
| 5.4.3    | 1         | 0.59%   |
| 5.4.171  | 1         | 0.59%   |
| 5.4.144  | 1         | 0.59%   |
| 5.4.127  | 1         | 0.59%   |
| 5.4.117  | 1         | 0.59%   |
| 5.4.115  | 1         | 0.59%   |
| 5.3.5    | 1         | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 98        | 61.64%  |
| 5.4     | 20        | 12.58%  |
| 5.15    | 19        | 11.95%  |
| 4.19    | 11        | 6.92%   |
| 4.9     | 3         | 1.89%   |
| 5.18    | 2         | 1.26%   |
| 5.13    | 2         | 1.26%   |
| 5.7     | 1         | 0.63%   |
| 5.3     | 1         | 0.63%   |
| 5.16    | 1         | 0.63%   |
| 4.4     | 1         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 145       | 95.39%  |
| i686   | 7         | 4.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 106       | 67.95%  |
| XFCE            | 20        | 12.82%  |
| Unknown         | 19        | 12.18%  |
| LXQt            | 4         | 2.56%   |
| GNOME           | 3         | 1.92%   |
| Cinnamon        | 3         | 1.92%   |
| GNOME Flashback | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 148       | 96.73%  |
| Wayland | 3         | 1.96%   |
| Tty     | 2         | 1.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 89        | 57.05%  |
| LightDM | 31        | 19.87%  |
| TDM     | 22        | 14.1%   |
| Unknown | 12        | 7.69%   |
| XDM     | 1         | 0.64%   |
| GDM     | 1         | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 123       | 78.34%  |
| Unknown | 26        | 16.56%  |
| en_US   | 6         | 3.82%   |
| POSIX   | 1         | 0.64%   |
| C       | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 116       | 75.32%  |
| BIOS | 38        | 24.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 134       | 87.58%  |
| Overlay | 14        | 9.15%   |
| Btrfs   | 3         | 1.96%   |
| Unknown | 2         | 1.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 113       | 73.38%  |
| MBR     | 26        | 16.88%  |
| Unknown | 15        | 9.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 146       | 94.81%  |
| Yes       | 8         | 5.19%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 54.25%  |
| Yes       | 70        | 45.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 53        | 34.87%  |
| Lenovo              | 19        | 12.5%   |
| ASUSTek Computer    | 17        | 11.18%  |
| Acer                | 11        | 7.24%   |
| ICL                 | 10        | 6.58%   |
| Dell                | 8         | 5.26%   |
| HUAWEI              | 7         | 4.61%   |
| 3Logic Group        | 4         | 2.63%   |
| Samsung Electronics | 3         | 1.97%   |
| MSI                 | 3         | 1.97%   |
| DEPO Computers      | 2         | 1.32%   |
| Apple               | 2         | 1.32%   |
| Toshiba             | 1         | 0.66%   |
| Timi                | 1         | 0.66%   |
| Sony                | 1         | 0.66%   |
| Panasonic           | 1         | 0.66%   |
| Kraftway            | 1         | 0.66%   |
| IP3 Technology      | 1         | 0.66%   |
| IP3 Tech            | 1         | 0.66%   |
| eMachines           | 1         | 0.66%   |
| Durabook            | 1         | 0.66%   |
| Compumax Computer   | 1         | 0.66%   |
| Clevo               | 1         | 0.66%   |
| Aquarius            | 1         | 0.66%   |
| Unknown             | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HP 250 G7 Notebook PC                     | 12        | 7.89%   |
| HP ZBook 17 G5                            | 9         | 5.92%   |
| HP ProBook 440 G5                         | 8         | 5.26%   |
| ICL RAYbook Si1512                        | 6         | 3.95%   |
| HP EliteBook 840 G4                       | 3         | 1.97%   |
| HP 250 G6 Notebook PC                     | 3         | 1.97%   |
| Dell Latitude 3420                        | 3         | 1.97%   |
| Unknown                                   | 3         | 1.97%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT      | 2         | 1.32%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 2         | 1.32%   |
| ICL NJ50_70CU                             | 2         | 1.32%   |
| HUAWEI NBD-WXX9                           | 2         | 1.32%   |
| HUAWEI KLVL-WXXW                          | 2         | 1.32%   |
| HP EliteBook 8470p                        | 2         | 1.32%   |
| DEPO Computers DPC156                     | 2         | 1.32%   |
| ASUS N46VZ                                | 2         | 1.32%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE | 2         | 1.32%   |
| Acer TravelMate 5760                      | 2         | 1.32%   |
| 3Logic Group Graviton N15i-K2             | 2         | 1.32%   |
| 3Logic Group Graviton N15i                | 2         | 1.32%   |
| Toshiba Satellite A100                    | 1         | 0.66%   |
| Timi TM1701                               | 1         | 0.66%   |
| Sony SVE1512H1RB                          | 1         | 0.66%   |
| Samsung RV413/RV513/E3413                 | 1         | 0.66%   |
| Samsung R510/P510                         | 1         | 0.66%   |
| Samsung 750XDA                            | 1         | 0.66%   |
| Panasonic CF-20-1                         | 1         | 0.66%   |
| MSI X300/X340/X400 series                 | 1         | 0.66%   |
| MSI MEGA BOOK S430                        | 1         | 0.66%   |
| MSI GE72 7RE                              | 1         | 0.66%   |
| Lenovo V510-15IKB 80WQ                    | 1         | 0.66%   |
| Lenovo V130-15IKB 81HN                    | 1         | 0.66%   |
| Lenovo ThinkPad X220 4291M85              | 1         | 0.66%   |
| Lenovo ThinkPad 13 2nd Gen 20J1S0EU00     | 1         | 0.66%   |
| Lenovo IdeaPad Y700-15ACZ 80NY            | 1         | 0.66%   |
| Lenovo IdeaPad 5 15IIL05 81YK             | 1         | 0.66%   |
| Lenovo IdeaPad 310-15ISK 80SM             | 1         | 0.66%   |
| Lenovo IdeaPad 3 15IIL05 81WE             | 1         | 0.66%   |
| Lenovo IdeaPad 3 15IGL05 81WQ             | 1         | 0.66%   |
| Lenovo G570 20079                         | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| HP 250                | 16        | 10.53%  |
| HP ProBook            | 10        | 6.58%   |
| HP ZBook              | 9         | 5.92%   |
| HP Pavilion           | 7         | 4.61%   |
| ICL RAYbook           | 6         | 3.95%   |
| Acer Aspire           | 6         | 3.95%   |
| Lenovo IdeaPad        | 5         | 3.29%   |
| HP EliteBook          | 5         | 3.29%   |
| Lenovo ThinkPad       | 4         | 2.63%   |
| HP Laptop             | 4         | 2.63%   |
| Dell Latitude         | 4         | 2.63%   |
| ASUS ASUS             | 4         | 2.63%   |
| 3Logic Group Graviton | 4         | 2.63%   |
| ASUS VivoBook         | 3         | 1.97%   |
| Unknown               | 3         | 1.97%   |
| Lenovo ThinkBook      | 2         | 1.32%   |
| ICL NJ50              | 2         | 1.32%   |
| HUAWEI NBD-WXX9       | 2         | 1.32%   |
| HUAWEI KLVL-WXXW      | 2         | 1.32%   |
| DEPO Computers DPC156 | 2         | 1.32%   |
| ASUS N46VZ            | 2         | 1.32%   |
| Acer TravelMate       | 2         | 1.32%   |
| Toshiba Satellite     | 1         | 0.66%   |
| Timi TM1701           | 1         | 0.66%   |
| Sony SVE1512H1RB      | 1         | 0.66%   |
| Samsung RV413         | 1         | 0.66%   |
| Samsung R510          | 1         | 0.66%   |
| Samsung 750XDA        | 1         | 0.66%   |
| Panasonic CF-20-1     | 1         | 0.66%   |
| MSI X300              | 1         | 0.66%   |
| MSI MEGA              | 1         | 0.66%   |
| MSI GE72              | 1         | 0.66%   |
| Lenovo V510-15IKB     | 1         | 0.66%   |
| Lenovo V130-15IKB     | 1         | 0.66%   |
| Lenovo G570           | 1         | 0.66%   |
| Lenovo G505s          | 1         | 0.66%   |
| Lenovo G460           | 1         | 0.66%   |
| Lenovo B590           | 1         | 0.66%   |
| Lenovo B50-10         | 1         | 0.66%   |
| Lenovo 3000           | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 26        | 17.11%  |
| 2021 | 23        | 15.13%  |
| 2017 | 19        | 12.5%   |
| 2020 | 16        | 10.53%  |
| 2019 | 16        | 10.53%  |
| 2011 | 9         | 5.92%   |
| 2016 | 6         | 3.95%   |
| 2012 | 6         | 3.95%   |
| 2010 | 6         | 3.95%   |
| 2022 | 5         | 3.29%   |
| 2014 | 5         | 3.29%   |
| 2008 | 4         | 2.63%   |
| 2015 | 3         | 1.97%   |
| 2009 | 3         | 1.97%   |
| 2013 | 2         | 1.32%   |
| 2007 | 2         | 1.32%   |
| 2006 | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 152       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 128       | 82.58%  |
| Enabled  | 27        | 17.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 86        | 56.21%  |
| 3.01-4.0   | 29        | 18.95%  |
| 16.01-24.0 | 19        | 12.42%  |
| 8.01-16.0  | 9         | 5.88%   |
| 1.01-2.0   | 8         | 5.23%   |
| 2.01-3.0   | 2         | 1.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 79        | 47.88%  |
| 2.01-3.0  | 30        | 18.18%  |
| 0.51-1.0  | 27        | 16.36%  |
| 3.01-4.0  | 14        | 8.48%   |
| 4.01-8.0  | 12        | 7.27%   |
| 0.01-0.5  | 2         | 1.21%   |
| 8.01-16.0 | 1         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 76.28%  |
| 2      | 32        | 20.51%  |
| 3      | 2         | 1.28%   |
| 0      | 2         | 1.28%   |
| 4      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 64.94%  |
| Yes       | 54        | 35.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 86.18%  |
| No        | 21        | 13.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 99.34%  |
| No        | 1         | 0.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 80.39%  |
| No        | 30        | 19.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Russia     | 142       | 93.42%  |
| Greece     | 3         | 1.97%   |
| Uzbekistan | 1         | 0.66%   |
| Ukraine    | 1         | 0.66%   |
| Egypt      | 1         | 0.66%   |
| Czechia    | 1         | 0.66%   |
| Costa Rica | 1         | 0.66%   |
| Colombia   | 1         | 0.66%   |
| Belarus    | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 97        | 62.18%  |
| St Petersburg     | 6         | 3.85%   |
| Barnaul           | 4         | 2.56%   |
| Samara            | 3         | 1.92%   |
| Astrakhan         | 3         | 1.92%   |
| Perm              | 2         | 1.28%   |
| Korolyov          | 2         | 1.28%   |
| Belgorod          | 2         | 1.28%   |
| Yekaterinburg     | 1         | 0.64%   |
| Voronezh          | 1         | 0.64%   |
| Vladimir          | 1         | 0.64%   |
| Verkhnyaya Pyshma | 1         | 0.64%   |
| Vergina           | 1         | 0.64%   |
| Tyumen            | 1         | 0.64%   |
| Troitsk           | 1         | 0.64%   |
| Thessaloniki      | 1         | 0.64%   |
| Tashkent          | 1         | 0.64%   |
| Surgut            | 1         | 0.64%   |
| Suez              | 1         | 0.64%   |
| Sevastopol        | 1         | 0.64%   |
| Saratov           | 1         | 0.64%   |
| San José         | 1         | 0.64%   |
| Rostov-on-Don     | 1         | 0.64%   |
| Prague            | 1         | 0.64%   |
| Omsk              | 1         | 0.64%   |
| Obninsk           | 1         | 0.64%   |
| Novosibirsk       | 1         | 0.64%   |
| Novichikha        | 1         | 0.64%   |
| Nizhny Tagil      | 1         | 0.64%   |
| Lesosibirsk       | 1         | 0.64%   |
| Krasnoyarsk       | 1         | 0.64%   |
| Kostroma          | 1         | 0.64%   |
| Kirov             | 1         | 0.64%   |
| Khabarovsk        | 1         | 0.64%   |
| Kemerovo          | 1         | 0.64%   |
| Kazan’          | 1         | 0.64%   |
| Kaluga            | 1         | 0.64%   |
| Kaliningrad       | 1         | 0.64%   |
| Hurghada          | 1         | 0.64%   |
| Gornoural'skiy    | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 25        | 30     | 13.74%  |
| Samsung Electronics         | 24        | 31     | 13.19%  |
| WDC                         | 21        | 25     | 11.54%  |
| Intel                       | 21        | 24     | 11.54%  |
| SK hynix                    | 18        | 18     | 9.89%   |
| Toshiba                     | 8         | 14     | 4.4%    |
| Foxline                     | 8         | 8      | 4.4%    |
| Phison                      | 6         | 6      | 3.3%    |
| Hitachi                     | 5         | 5      | 2.75%   |
| Kingston                    | 4         | 4      | 2.2%    |
| HGST                        | 4         | 4      | 2.2%    |
| A-DATA Technology           | 4         | 4      | 2.2%    |
| XPG                         | 3         | 4      | 1.65%   |
| Unknown                     | 3         | 3      | 1.65%   |
| Apacer                      | 3         | 3      | 1.65%   |
| SSSTC                       | 2         | 2      | 1.1%    |
| SanDisk                     | 2         | 2      | 1.1%    |
| Gigabyte Technology         | 2         | 2      | 1.1%    |
| Fujitsu                     | 2         | 2      | 1.1%    |
| Crucial                     | 2         | 2      | 1.1%    |
| BIWIN                       | 2         | 3      | 1.1%    |
| Yangtze Memory Technologies | 1         | 1      | 0.55%   |
| Transcend                   | 1         | 1      | 0.55%   |
| PNY                         | 1         | 1      | 0.55%   |
| Plextor                     | 1         | 1      | 0.55%   |
| Micron Technology           | 1         | 1      | 0.55%   |
| LuminouTek                  | 1         | 1      | 0.55%   |
| KIOXIA                      | 1         | 1      | 0.55%   |
| KingSpec                    | 1         | 1      | 0.55%   |
| KingDian                    | 1         | 1      | 0.55%   |
| BaseTech                    | 1         | 1      | 0.55%   |
| Apple                       | 1         | 1      | 0.55%   |
| AMD                         | 1         | 1      | 0.55%   |
| Unknown                     | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 12        | 6.42%   |
| Seagate ST1000LM049-2GH172 1TB          | 8         | 4.28%   |
| Intel SSDPEMKF256G8H 256GB              | 8         | 4.28%   |
| Intel SSDPEKKF256G7H 256GB              | 8         | 4.28%   |
| Foxline FLSSD256M80E13TCX5 256GB        | 8         | 4.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 2.14%   |
| Samsung MZALQ256HAJD-000L2 256GB        | 4         | 2.14%   |
| Phison 311CD0512GB                      | 4         | 2.14%   |
| XPG SPECTRIX S40G 256GB                 | 2         | 1.07%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 2         | 1.07%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 1.07%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.07%   |
| Toshiba KXG50ZNV256G 256GB              | 2         | 1.07%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB          | 2         | 1.07%   |
| Seagate ST9250315AS 250GB               | 2         | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 1.07%   |
| Samsung SSD 860 EVO M.2 250GB           | 2         | 1.07%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.07%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 1.07%   |
| Intel SSDPEKNW512G8H 512GB              | 2         | 1.07%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.07%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB        | 2         | 1.07%   |
| Crucial CT120BX500SSD1 120GB            | 2         | 1.07%   |
| BIWIN CE480T5D101-256 256GB             | 2         | 1.07%   |
| Yangtze Memory NVMe SSD Drive 256GB     | 1         | 0.53%   |
| XPG NVMe SSD Drive 256GB                | 1         | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.53%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.53%   |
| WDC WD5000LPZX-22Z10T0 500GB            | 1         | 0.53%   |
| WDC WD5000LPVX-80V0TT0 500GB            | 1         | 0.53%   |
| WDC WD5000LPVX-60V0TT0 500GB            | 1         | 0.53%   |
| WDC WD5000LPLX-60ZNTT1 500GB            | 1         | 0.53%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 0.53%   |
| WDC WD3200BEVT-22A23T0 320GB            | 1         | 0.53%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.53%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 0.53%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 30     | 44.64%  |
| WDC     | 14        | 15     | 25%     |
| Toshiba | 6         | 12     | 10.71%  |
| Hitachi | 5         | 5      | 8.93%   |
| HGST    | 4         | 4      | 7.14%   |
| Fujitsu | 2         | 2      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 25.71%  |
| WDC                 | 4         | 7      | 11.43%  |
| SK hynix            | 2         | 2      | 5.71%   |
| Kingston            | 2         | 2      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| A-DATA Technology   | 2         | 2      | 5.71%   |
| Transcend           | 1         | 1      | 2.86%   |
| SanDisk             | 1         | 1      | 2.86%   |
| PNY                 | 1         | 1      | 2.86%   |
| Plextor             | 1         | 1      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| LuminouTek          | 1         | 1      | 2.86%   |
| KingSpec            | 1         | 1      | 2.86%   |
| KingDian            | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| Foxline             | 1         | 1      | 2.86%   |
| BaseTech            | 1         | 1      | 2.86%   |
| Apacer              | 1         | 1      | 2.86%   |
| AMD                 | 1         | 1      | 2.86%   |
| Unknown             | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 84        | 98     | 47.19%  |
| HDD  | 55        | 68     | 30.9%   |
| SSD  | 34        | 38     | 19.1%   |
| MMC  | 5         | 5      | 2.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 84        | 98     | 49.7%   |
| SATA | 77        | 103    | 45.56%  |
| MMC  | 5         | 5      | 2.96%   |
| SAS  | 3         | 3      | 1.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 65     | 66.28%  |
| 0.51-1.0   | 27        | 39     | 31.4%   |
| 1.01-2.0   | 2         | 2      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 82        | 51.9%   |
| 251-500    | 27        | 17.09%  |
| 51-100     | 18        | 11.39%  |
| 21-50      | 10        | 6.33%   |
| 1-20       | 8         | 5.06%   |
| 501-1000   | 8         | 5.06%   |
| 1001-2000  | 4         | 2.53%   |
| 2001-3000  | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 99        | 61.49%  |
| 21-50     | 29        | 18.01%  |
| 101-250   | 12        | 7.45%   |
| 51-100    | 10        | 6.21%   |
| 251-500   | 6         | 3.73%   |
| 501-1000  | 3         | 1.86%   |
| 1001-2000 | 2         | 1.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB               | 2         | 2      | 12.5%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 7      | 12.5%   |
| WDC WD5000LPVX-60V0TT0 500GB            | 1         | 1      | 6.25%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 1         | 1      | 6.25%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 6.25%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 1         | 1      | 6.25%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 6.25%   |
| Seagate ST9640320AS 640GB               | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 6.25%   |
| Hitachi HTS725050A9A364 500GB           | 1         | 1      | 6.25%   |
| Hitachi HTS542525K9A300 250GB           | 1         | 1      | 6.25%   |
| Hitachi HTS541610J9SA00 100GB           | 1         | 1      | 6.25%   |
| HGST HTS545050A7E680 500GB              | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 11     | 37.5%   |
| WDC      | 3         | 3      | 18.75%  |
| Hitachi  | 3         | 3      | 18.75%  |
| SK hynix | 2         | 2      | 12.5%   |
| Toshiba  | 1         | 1      | 6.25%   |
| HGST     | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 11     | 42.86%  |
| WDC     | 3         | 3      | 21.43%  |
| Hitachi | 3         | 3      | 21.43%  |
| Toshiba | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 19     | 87.5%   |
| NVMe | 1         | 1      | 6.25%   |
| SSD  | 1         | 1      | 6.25%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 125       | 157    | 78.13%  |
| Detected | 19        | 31     | 11.88%  |
| Malfunc  | 16        | 21     | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 116       | 58%     |
| SK hynix                       | 15        | 7.5%    |
| Samsung Electronics            | 15        | 7.5%    |
| Phison Electronics             | 15        | 7.5%    |
| AMD                            | 14        | 7%      |
| SanDisk                        | 4         | 2%      |
| Nvidia                         | 3         | 1.5%    |
| Unknown                        | 2         | 1%      |
| Toshiba America Info Systems   | 2         | 1%      |
| Solid State Storage Technology | 2         | 1%      |
| Realtek Semiconductor          | 2         | 1%      |
| Kingston Technology Company    | 2         | 1%      |
| ADATA Technology               | 2         | 1%      |
| Yangtze Memory Technologies    | 1         | 0.5%    |
| VIA Technologies               | 1         | 0.5%    |
| Shenzhen Longsys Electronics   | 1         | 0.5%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.5%    |
| KIOXIA                         | 1         | 0.5%    |
| Apple                          | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 23        | 10.04%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 7.42%   |
| Phison PS5013 E13 NVMe Controller                                                | 14        | 6.11%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 13        | 5.68%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 5.24%   |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 4.8%    |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 4.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 10        | 4.37%   |
| Samsung NVMe SSD Controller 980                                                  | 9         | 3.93%   |
| Intel SSD 600P Series                                                            | 9         | 3.93%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 8         | 3.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 2.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 2.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.31%   |
| Unknown Non-Volatile memory controller                                           | 2         | 0.87%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.87%   |
| Solid State Storage Non-Volatile memory controller                               | 2         | 0.87%   |
| SK hynix BC511                                                                   | 2         | 0.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.87%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 2         | 0.87%   |
| Intel SSD 660P Series                                                            | 2         | 0.87%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.87%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 0.87%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.44%   |
| VIA VT8237/8251 Serial ATA Controller                                            | 1         | 0.44%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.44%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.44%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 0.44%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.44%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.44%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 108       | 48.21%  |
| NVMe | 84        | 37.5%   |
| RAID | 23        | 10.27%  |
| IDE  | 9         | 4.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 131       | 86.18%  |
| AMD          | 20        | 13.16%  |
| CentaurHauls | 1         | 0.66%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 9.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 8.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 6.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 6.58%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 5.92%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 3.95%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 4         | 2.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.97%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.97%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.97%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.32%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 2         | 1.32%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.32%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.32%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.32%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.32%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.32%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.32%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.32%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.66%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.66%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.66%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.66%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.66%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.66%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.66%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.66%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.66%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.66%   |
| Intel Core i5-1038NG7 CPU @ 2.00GHz           | 1         | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.66%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.66%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 0.66%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 46        | 30.26%  |
| Intel Core i3           | 28        | 18.42%  |
| Other                   | 18        | 11.84%  |
| Intel Core i7           | 17        | 11.18%  |
| Intel Celeron           | 6         | 3.95%   |
| AMD Ryzen 5             | 6         | 3.95%   |
| AMD Ryzen 7             | 4         | 2.63%   |
| Intel Core 2 Duo        | 3         | 1.97%   |
| Intel Atom              | 3         | 1.97%   |
| AMD A8                  | 3         | 1.97%   |
| Intel Pentium Silver    | 2         | 1.32%   |
| Intel Pentium Gold      | 2         | 1.32%   |
| Intel Pentium Dual-Core | 1         | 0.66%   |
| Intel Pentium           | 1         | 0.66%   |
| Intel Core m5           | 1         | 0.66%   |
| Intel Core Duo          | 1         | 0.66%   |
| Intel Core 2 Solo       | 1         | 0.66%   |
| Intel Celeron Dual-Core | 1         | 0.66%   |
| CentaurHauls VIA C7     | 1         | 0.66%   |
| AMD Turion 64 X2 Mobile | 1         | 0.66%   |
| AMD FX                  | 1         | 0.66%   |
| AMD E1                  | 1         | 0.66%   |
| AMD E                   | 1         | 0.66%   |
| AMD C-60                | 1         | 0.66%   |
| AMD Athlon 64 X2        | 1         | 0.66%   |
| AMD A6                  | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 44.08%  |
| 4      | 65        | 42.76%  |
| 6      | 13        | 8.55%   |
| 1      | 4         | 2.63%   |
| 8      | 3         | 1.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 152       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 126       | 82.89%  |
| 1      | 26        | 17.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 148       | 97.37%  |
| 32-bit         | 3         | 1.97%   |
| Unknown        | 1         | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 16.23%  |
| 0x806e9    | 16        | 10.39%  |
| 0x806c1    | 15        | 9.74%   |
| 0x806ec    | 13        | 8.44%   |
| 0x906ea    | 11        | 7.14%   |
| 0x806ea    | 11        | 7.14%   |
| 0xa0660    | 8         | 5.19%   |
| 0x306a9    | 6         | 3.9%    |
| 0x706e5    | 5         | 3.25%   |
| 0x406e3    | 4         | 2.6%    |
| 0x206a7    | 4         | 2.6%    |
| 0x1067a    | 4         | 2.6%    |
| 0x08600106 | 3         | 1.95%   |
| 0x08108109 | 3         | 1.95%   |
| 0x706a8    | 2         | 1.3%    |
| 0x40651    | 2         | 1.3%    |
| 0x30678    | 2         | 1.3%    |
| 0x08608102 | 2         | 1.3%    |
| 0xa0652    | 1         | 0.65%   |
| 0x806c2    | 1         | 0.65%   |
| 0x706a1    | 1         | 0.65%   |
| 0x6ec      | 1         | 0.65%   |
| 0x506c9    | 1         | 0.65%   |
| 0x406c3    | 1         | 0.65%   |
| 0x20655    | 1         | 0.65%   |
| 0x20652    | 1         | 0.65%   |
| 0x106ca    | 1         | 0.65%   |
| 0x106c2    | 1         | 0.65%   |
| 0x10676    | 1         | 0.65%   |
| 0x08600104 | 1         | 0.65%   |
| 0x08108102 | 1         | 0.65%   |
| 0x07030105 | 1         | 0.65%   |
| 0x0700010f | 1         | 0.65%   |
| 0x06003106 | 1         | 0.65%   |
| 0x06001119 | 1         | 0.65%   |
| 0x0300000f | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 58        | 38.16%  |
| TigerLake     | 19        | 12.5%   |
| CometLake     | 9         | 5.92%   |
| SandyBridge   | 7         | 4.61%   |
| IvyBridge     | 6         | 3.95%   |
| Penryn        | 5         | 3.29%   |
| IceLake       | 5         | 3.29%   |
| Zen+          | 4         | 2.63%   |
| Zen 2         | 4         | 2.63%   |
| Skylake       | 4         | 2.63%   |
| Silvermont    | 4         | 2.63%   |
| Goldmont plus | 4         | 2.63%   |
| Westmere      | 3         | 1.97%   |
| Unknown       | 3         | 1.97%   |
| K8 Hammer     | 2         | 1.32%   |
| Haswell       | 2         | 1.32%   |
| Bonnell       | 2         | 1.32%   |
| Bobcat        | 2         | 1.32%   |
| Steamroller   | 1         | 0.66%   |
| Puma          | 1         | 0.66%   |
| Piledriver    | 1         | 0.66%   |
| P6            | 1         | 0.66%   |
| K10 Llano     | 1         | 0.66%   |
| Jaguar        | 1         | 0.66%   |
| Goldmont      | 1         | 0.66%   |
| Excavator     | 1         | 0.66%   |
| Core          | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 124       | 69.27%  |
| Nvidia           | 32        | 17.88%  |
| AMD              | 22        | 12.29%  |
| VIA Technologies | 1         | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                     | 20        | 10.87%  |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 16        | 8.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 13        | 7.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 10        | 5.43%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                     | 9         | 4.89%   |
| Intel Comet Lake UHD Graphics                                             | 8         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 3.8%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 6         | 3.26%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.26%   |
| Intel UHD Graphics 620                                                    | 4         | 2.17%   |
| AMD Renoir                                                                | 4         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.17%   |
| Intel Tiger Lake UHD Graphics                                             | 3         | 1.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 1.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 1.09%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 2         | 1.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.09%   |
| Intel Iris Plus Graphics G7                                               | 2         | 1.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.09%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.09%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.09%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                     | 2         | 1.09%   |
| AMD Lucienne                                                              | 2         | 1.09%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]              | 2         | 1.09%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                         | 1         | 0.54%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.54%   |
| Nvidia TU117M                                                             | 1         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.54%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 0.54%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.54%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 0.54%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.54%   |
| Nvidia GP108BM [GeForce MX250]                                            | 1         | 0.54%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 100       | 65.79%  |
| Intel + Nvidia | 22        | 14.47%  |
| 1 x AMD        | 13        | 8.55%   |
| 1 x Nvidia     | 7         | 4.61%   |
| 2 x AMD        | 4         | 2.63%   |
| AMD + Nvidia   | 3         | 1.97%   |
| Intel + AMD    | 2         | 1.32%   |
| 1 x VIA        | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 141       | 91.56%  |
| Proprietary | 10        | 6.49%   |
| Unknown     | 3         | 1.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 77.42%  |
| 0.01-0.5   | 12        | 7.74%   |
| 3.01-4.0   | 10        | 6.45%   |
| 0.51-1.0   | 8         | 5.16%   |
| 1.01-2.0   | 5         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 45        | 27.95%  |
| Chimei Innolux          | 30        | 18.63%  |
| AU Optronics            | 26        | 16.15%  |
| LG Display              | 18        | 11.18%  |
| Samsung Electronics     | 10        | 6.21%   |
| Chi Mei Optoelectronics | 6         | 3.73%   |
| Sharp                   | 5         | 3.11%   |
| PANDA                   | 5         | 3.11%   |
| BenQ                    | 3         | 1.86%   |
| AOC                     | 3         | 1.86%   |
| Apple                   | 2         | 1.24%   |
| TR_                     | 1         | 0.62%   |
| STA                     | 1         | 0.62%   |
| PRM                     | 1         | 0.62%   |
| Panasonic               | 1         | 0.62%   |
| KDC                     | 1         | 0.62%   |
| Hitachi                 | 1         | 0.62%   |
| CS_                     | 1         | 0.62%   |
| Acer                    | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 12        | 7.41%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch     | 9         | 5.56%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                | 6         | 3.7%    |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch       | 5         | 3.09%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 3         | 1.85%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 3         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 1.85%   |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                | 3         | 1.85%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 3         | 1.85%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 3         | 1.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.85%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 2         | 1.23%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch     | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 2         | 1.23%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                | 2         | 1.23%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 2         | 1.23%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 2         | 1.23%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 1.23%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO133C 1366x768 309x173mm 13.9-inch        | 2         | 1.23%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                 | 1         | 0.62%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                | 1         | 0.62%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 1         | 0.62%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch               | 1         | 0.62%   |
| Samsung Electronics S24D590 SAM0B46 1920x1080 521x293mm 23.5-inch    | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4754 1280x800 261x163mm 12.1-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics F27G3xTF SAM710E 1920x1080 600x330mm 27.0-inch   | 1         | 0.62%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch   | 1         | 0.62%   |
| PRM 35 PRM2733 1280x1024                                             | 1         | 0.62%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch              | 1         | 0.62%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch              | 1         | 0.62%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 101       | 65.16%  |
| 1366x768 (WXGA)   | 32        | 20.65%  |
| 1600x900 (HD+)    | 6         | 3.87%   |
| 1280x800 (WXGA)   | 5         | 3.23%   |
| 2160x1440         | 2         | 1.29%   |
| 1440x900 (WXGA+)  | 2         | 1.29%   |
| 1280x1024 (SXGA)  | 2         | 1.29%   |
| 3200x1800 (QHD+)  | 1         | 0.65%   |
| 2560x1600         | 1         | 0.65%   |
| 2560x1440 (QHD)   | 1         | 0.65%   |
| 1920x1200 (WUXGA) | 1         | 0.65%   |
| 1400x1050         | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 77        | 47.83%  |
| 14      | 24        | 14.91%  |
| 13      | 20        | 12.42%  |
| 17      | 19        | 11.8%   |
| 24      | 4         | 2.48%   |
| 23      | 4         | 2.48%   |
| 11      | 4         | 2.48%   |
| 19      | 3         | 1.86%   |
| 27      | 2         | 1.24%   |
| 59      | 1         | 0.62%   |
| 12      | 1         | 0.62%   |
| 10      | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 69.57%  |
| 351-400     | 20        | 12.42%  |
| 201-300     | 15        | 9.32%   |
| 501-600     | 9         | 5.59%   |
| 401-500     | 2         | 1.24%   |
| 601-700     | 1         | 0.62%   |
| 1001-1500   | 1         | 0.62%   |
| Unknown     | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 138       | 89.61%  |
| 16/10 | 9         | 5.84%   |
| 3/2   | 4         | 2.6%    |
| 6/5   | 1         | 0.65%   |
| 5/4   | 1         | 0.65%   |
| 4/3   | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 47.83%  |
| 81-90          | 38        | 23.6%   |
| 121-130        | 18        | 11.18%  |
| 71-80          | 6         | 3.73%   |
| 201-250        | 6         | 3.73%   |
| 51-60          | 4         | 2.48%   |
| 151-200        | 3         | 1.86%   |
| 301-350        | 2         | 1.24%   |
| 251-300        | 2         | 1.24%   |
| More than 1000 | 1         | 0.62%   |
| 61-70          | 1         | 0.62%   |
| 41-50          | 1         | 0.62%   |
| 131-140        | 1         | 0.62%   |
| Unknown        | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 102       | 63.75%  |
| 101-120       | 31        | 19.38%  |
| 51-100        | 17        | 10.63%  |
| 161-240       | 7         | 4.38%   |
| More than 240 | 1         | 0.63%   |
| 1-50          | 1         | 0.63%   |
| Unknown       | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 141       | 91.56%  |
| 2     | 11        | 7.14%   |
| 3     | 1         | 0.65%   |
| 0     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 83        | 37.73%  |
| Realtek Semiconductor           | 75        | 34.09%  |
| Qualcomm Atheros                | 28        | 12.73%  |
| Broadcom                        | 14        | 6.36%   |
| D-Link                          | 6         | 2.73%   |
| Nvidia                          | 3         | 1.36%   |
| Marvell Technology Group        | 2         | 0.91%   |
| Sierra Wireless                 | 1         | 0.45%   |
| Ralink                          | 1         | 0.45%   |
| Qualcomm Atheros Communications | 1         | 0.45%   |
| Micro Star International        | 1         | 0.45%   |
| MediaTek                        | 1         | 0.45%   |
| JMicron Technology              | 1         | 0.45%   |
| Huawei Technologies             | 1         | 0.45%   |
| Broadcom Limited                | 1         | 0.45%   |
| ASUSTek Computer                | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 55        | 18.64%  |
| Intel Wi-Fi 6 AX201                                                     | 17        | 5.76%   |
| Intel Wireless 8265 / 8275                                              | 15        | 5.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 4.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 3.73%   |
| Intel Ethernet Connection (10) I219-V                                   | 10        | 3.39%   |
| Intel Ethernet Connection (7) I219-LM                                   | 9         | 3.05%   |
| Intel Ethernet Connection (13) I219-V                                   | 9         | 3.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 2.37%   |
| Intel Wireless 7265                                                     | 6         | 2.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.69%   |
| Intel Ethernet Connection (6) I219-V                                    | 5         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.36%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.36%   |
| D-Link DUB-1312                                                         | 4         | 1.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.68%   |
| Intel Wireless 3165                                                     | 2         | 0.68%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.68%   |
| Intel WiMAX Connection 2400m                                            | 2         | 0.68%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.68%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]            | 2         | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 51.92%  |
| Realtek Semiconductor           | 30        | 19.23%  |
| Qualcomm Atheros                | 26        | 16.67%  |
| Broadcom                        | 13        | 8.33%   |
| Sierra Wireless                 | 1         | 0.64%   |
| Ralink                          | 1         | 0.64%   |
| Qualcomm Atheros Communications | 1         | 0.64%   |
| Micro Star International        | 1         | 0.64%   |
| MediaTek                        | 1         | 0.64%   |
| ASUSTek Computer                | 1         | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 17        | 10.83%  |
| Intel Wireless 8265 / 8275                                              | 15        | 9.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 7.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 7.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 5.73%   |
| Intel Wireless 7265                                                     | 6         | 3.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 3.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.91%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.27%   |
| Intel Wireless 3165                                                     | 2         | 1.27%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.27%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.64%   |
| Realtek Realtek Network controller                                      | 1         | 0.64%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.64%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.64%   |
| Micro Star International RT2573                                         | 1         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.64%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.64%   |
| Intel Wireless 8260                                                     | 1         | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 47.79%  |
| Intel                    | 45        | 33.09%  |
| Qualcomm Atheros         | 9         | 6.62%   |
| D-Link                   | 6         | 4.41%   |
| Nvidia                   | 3         | 2.21%   |
| Broadcom                 | 3         | 2.21%   |
| Marvell Technology Group | 2         | 1.47%   |
| JMicron Technology       | 1         | 0.74%   |
| Huawei Technologies      | 1         | 0.74%   |
| Broadcom Limited         | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 39.86%  |
| Intel Ethernet Connection (10) I219-V                             | 10        | 7.25%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 6.52%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 6.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 5.07%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 3.62%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.9%    |
| D-Link DUB-1312                                                   | 4         | 2.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.45%   |
| Intel WiMAX Connection 2400m                                      | 2         | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.45%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 2         | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.72%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.72%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.72%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.72%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.72%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.72%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.72%   |
| Huawei YAL-L21                                                    | 1         | 0.72%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.72%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 53.55%  |
| Ethernet | 131       | 46.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 128       | 81.01%  |
| Ethernet | 30        | 18.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 123       | 80.92%  |
| 1     | 25        | 16.45%  |
| 0     | 3         | 1.97%   |
| 3     | 1         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 145       | 95.39%  |
| Yes  | 7         | 4.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 61.29%  |
| Realtek Semiconductor           | 9         | 7.26%   |
| IMC Networks                    | 7         | 5.65%   |
| Qualcomm Atheros Communications | 5         | 4.03%   |
| Lite-On Technology              | 5         | 4.03%   |
| Broadcom                        | 5         | 4.03%   |
| Realtek                         | 3         | 2.42%   |
| Hewlett-Packard                 | 3         | 2.42%   |
| Foxconn / Hon Hai               | 3         | 2.42%   |
| ASUSTek Computer                | 2         | 1.61%   |
| USI                             | 1         | 0.81%   |
| Toshiba                         | 1         | 0.81%   |
| Ralink                          | 1         | 0.81%   |
| Chicony Electronics             | 1         | 0.81%   |
| Cambridge Silicon Radio         | 1         | 0.81%   |
| Apple                           | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 26        | 20.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 18.55%  |
| Intel AX201 Bluetooth                               | 20        | 16.13%  |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 4.84%   |
| Realtek Bluetooth Radio                             | 5         | 4.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.23%   |
| Realtek Bluetooth Radio                             | 3         | 2.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.42%   |
| IMC Networks Bluetooth Device                       | 3         | 2.42%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 2.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.61%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.61%   |
| USI Bluetooth Module BCM92070                       | 1         | 0.81%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.81%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.81%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.81%   |
| Lite-On Bluetooth Radio                             | 1         | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.81%   |
| IMC Networks Wireless_Device                        | 1         | 0.81%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.81%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.81%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.81%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.81%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.81%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.81%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 0.81%   |
| Apple Bluetooth Host Controller                     | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 129       | 72.47%  |
| Nvidia                | 22        | 12.36%  |
| AMD                   | 20        | 11.24%  |
| C-Media Electronics   | 4         | 2.25%   |
| VIA Technologies      | 1         | 0.56%   |
| Realtek Semiconductor | 1         | 0.56%   |
| Apple                 | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 28        | 14.36%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 9.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 9.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 5.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 5.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 4.62%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 4.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 3.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 3.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 2.56%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 2.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.03%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.03%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.03%   |
| C-Media Electronics USB Advanced Audio Device                              | 2         | 1.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.03%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.51%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.51%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 0.51%   |
| Nvidia MCP51 High Definition Audio                                         | 1         | 0.51%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.51%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia Audio device                                                        | 1         | 0.51%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.51%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.51%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 29.29%  |
| SK hynix            | 35        | 25%     |
| Crucial             | 13        | 9.29%   |
| Unknown             | 10        | 7.14%   |
| Micron Technology   | 9         | 6.43%   |
| Kingston            | 9         | 6.43%   |
| Foxline             | 5         | 3.57%   |
| Elpida              | 3         | 2.14%   |
| A-DATA Technology   | 3         | 2.14%   |
| Unknown (ABCD)      | 2         | 1.43%   |
| Ramaxel Technology  | 2         | 1.43%   |
| ChangXin Memory     | 2         | 1.43%   |
| ACPI Digital        | 2         | 1.43%   |
| Unknown             | 2         | 1.43%   |
| SHARETRONIC         | 1         | 0.71%   |
| Patriot             | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 9.09%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 6.29%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 5         | 3.5%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 3.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.8%    |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 4         | 2.8%    |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 4         | 2.8%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 2.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 2.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 2.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 2.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 2.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 1.4%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.4%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.4%    |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s          | 2         | 1.4%    |
| Crucial RAM CT51264BF160BJ.M8F 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.4%    |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s              | 2         | 1.4%    |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 2         | 1.4%    |
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 2         | 1.4%    |
| Unknown                                                          | 2         | 1.4%    |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                     | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.7%    |
| Unknown RAM Module 4096MB SODIMM 800MT/s                         | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.7%    |
| Unknown RAM Module 1024MB SODIMM DDR2 333MT/s                    | 1         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s  | 1         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.7%    |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1333MT/s                  | 1         | 0.7%    |
| Samsung RAM U6E3S4AA-MGCR 4GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 92        | 68.66%  |
| DDR3    | 25        | 18.66%  |
| DDR2    | 8         | 5.97%   |
| LPDDR4  | 7         | 5.22%   |
| LPDDR3  | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 88.81%  |
| Row Of Chips | 14        | 10.45%  |
| DIMM         | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 62        | 45.26%  |
| 4096  | 45        | 32.85%  |
| 16384 | 14        | 10.22%  |
| 2048  | 10        | 7.3%    |
| 1024  | 4         | 2.92%   |
| 1536  | 1         | 0.73%   |
| 512   | 1         | 0.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 50        | 35.46%  |
| 3200    | 23        | 16.31%  |
| 1600    | 18        | 12.77%  |
| 2133    | 13        | 9.22%   |
| 2400    | 8         | 5.67%   |
| 1334    | 6         | 4.26%   |
| Unknown | 5         | 3.55%   |
| 3266    | 4         | 2.84%   |
| 667     | 3         | 2.13%   |
| 4267    | 2         | 1.42%   |
| 3733    | 2         | 1.42%   |
| 1333    | 2         | 1.42%   |
| 2933    | 1         | 0.71%   |
| 1867    | 1         | 0.71%   |
| 1067    | 1         | 0.71%   |
| 800     | 1         | 0.71%   |
| 333     | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Canon MF4010 series      | 1         | 50%     |
| Brother HL-L2300D series | 1         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 27.27%  |
| Cheng Uei Precision Industry (Foxlink) | 29        | 20.28%  |
| IMC Networks                           | 19        | 13.29%  |
| Sunplus Innovation Technology          | 9         | 6.29%   |
| Acer                                   | 9         | 6.29%   |
| Quanta                                 | 8         | 5.59%   |
| Suyin                                  | 5         | 3.5%    |
| Syntek                                 | 4         | 2.8%    |
| Realtek Semiconductor                  | 4         | 2.8%    |
| Microdia                               | 3         | 2.1%    |
| Lite-On Technology                     | 2         | 1.4%    |
| Z-Star Microelectronics                | 1         | 0.7%    |
| Y Media                                | 1         | 0.7%    |
| Unknown                                | 1         | 0.7%    |
| SunplusIT                              | 1         | 0.7%    |
| Sonix Technology                       | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Ricoh                                  | 1         | 0.7%    |
| Primax Electronics                     | 1         | 0.7%    |
| icSpring                               | 1         | 0.7%    |
| Apple                                  | 1         | 0.7%    |
| ALi                                    | 1         | 0.7%    |
| Alcor Micro                            | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 10.42%  |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 11        | 7.64%   |
| Chicony HP HD Camera                                           | 9         | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 4.17%   |
| Chicony USB2.0 Camera                                          | 6         | 4.17%   |
| Sunplus Integrated_Webcam_HD                                   | 5         | 3.47%   |
| IMC Networks Integrated Camera                                 | 4         | 2.78%   |
| IMC Networks HD Camera                                         | 4         | 2.78%   |
| Chicony USB camera                                             | 4         | 2.78%   |
| Acer BisonCam,NB Pro                                           | 4         | 2.78%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 2.08%   |
| Chicony Integrated Camera                                      | 3         | 2.08%   |
| Syntek Lenovo EasyCamera                                       | 2         | 1.39%   |
| Syntek Integrated Camera                                       | 2         | 1.39%   |
| Suyin 1.3M HD WebCam                                           | 2         | 1.39%   |
| Sunplus BKX Usb FHD Camera                                     | 2         | 1.39%   |
| Sunplus ASUS USB2.0 Webcam                                     | 2         | 1.39%   |
| Quanta ov9734_techfront_camera                                 | 2         | 1.39%   |
| Chicony VGA Webcam                                             | 2         | 1.39%   |
| Chicony Lenovo EasyCamera                                      | 2         | 1.39%   |
| Chicony HD WebCam                                              | 2         | 1.39%   |
| Acer BisonCam, NB Pro                                          | 2         | 1.39%   |
| Z-Star Vega USB 2.0 Camera                                     | 1         | 0.69%   |
| Y Media USB Camera                                             | 1         | 0.69%   |
| Unknown USB2.0 Webcam                                          | 1         | 0.69%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.69%   |
| Suyin HP Truevision HD                                         | 1         | 0.69%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.69%   |
| SunplusIT USB camera                                           | 1         | 0.69%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 0.69%   |
| Silicon Motion WebCam SC-0311139N                              | 1         | 0.69%   |
| Ricoh USB2.0 Camera                                            | 1         | 0.69%   |
| Realtek USB Camera                                             | 1         | 0.69%   |
| Realtek Lenovo EasyCamera                                      | 1         | 0.69%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 0.69%   |
| Realtek EasyCamera                                             | 1         | 0.69%   |
| Quanta VGA WebCam                                              | 1         | 0.69%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 0.69%   |
| Quanta HP Webcam                                               | 1         | 0.69%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 33.33%  |
| Shenzhen Goodix Technology | 6         | 33.33%  |
| Elan Microelectronics      | 3         | 16.67%  |
| Synaptics                  | 2         | 11.11%  |
| LighTuning Technology      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 6         | 33.33%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 11.11%  |
| Validity Sensors VFS491                           | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 11.11%  |
| Elan ELAN:Fingerprint                             | 2         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 5.56%   |
| Elan ELAN:ARM-M4                                  | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 117       | 75.48%  |
| 1     | 28        | 18.06%  |
| 2     | 9         | 5.81%   |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 41.86%  |
| Graphics card            | 7         | 16.28%  |
| Communication controller | 7         | 16.28%  |
| Net/ethernet             | 3         | 6.98%   |
| Chipcard                 | 3         | 6.98%   |
| Multimedia controller    | 2         | 4.65%   |
| Sound                    | 1         | 2.33%   |
| Camera                   | 1         | 2.33%   |
| Bluetooth                | 1         | 2.33%   |

