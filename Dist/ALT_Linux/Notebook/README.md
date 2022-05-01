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

Total: 181

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G570 20079                  | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ce4196dac6](https://linux-hardware.org/?probe=ce4196dac6) | Apr 28, 2022 |
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
| HP            | Pavilion Gaming Laptop 1... | [55533901d3](https://linux-hardware.org/?probe=55533901d3) | Mar 11, 2022 |
| Dell          | G5 5590                     | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f0c89a4e5b](https://linux-hardware.org/?probe=f0c89a4e5b) | Feb 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cf41cc6ddb](https://linux-hardware.org/?probe=cf41cc6ddb) | Feb 15, 2022 |
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
| ASUSTek       | N46VZ                       | [62c6944a06](https://linux-hardware.org/?probe=62c6944a06) | May 19, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| HP            | EliteBook 8470p             | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| ASUSTek       | N46VZ                       | [af521df7b9](https://linux-hardware.org/?probe=af521df7b9) | Jan 16, 2021 |
| Lenovo        | B50-10 80QR                 | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Acer          | NC-ES1-131-C1NL             | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| HP            | EliteBook 8470p             | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| ASUSTek       | N46VZ                       | [d17038f482](https://linux-hardware.org/?probe=d17038f482) | Dec 17, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| HP            | Laptop 14s-dq1xxx           | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| Toshiba       | Satellite A100              | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| MSI           | X300/X340/X400 series       | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| ASUSTek       | N46VZ                       | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [0ac9b22881](https://linux-hardware.org/?probe=0ac9b22881) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [0a8a235308](https://linux-hardware.org/?probe=0a8a235308) | Aug 24, 2020 |
| ASUSTek       | N46VZ                       | [c1e8898d0b](https://linux-hardware.org/?probe=c1e8898d0b) | Aug 24, 2020 |
| ASUSTek       | N46VZ                       | [1c45537256](https://linux-hardware.org/?probe=1c45537256) | Aug 14, 2020 |
| ASUSTek       | N46VZ                       | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| ASUSTek       | N46VZ                       | [a7c66e41c7](https://linux-hardware.org/?probe=a7c66e41c7) | Aug 14, 2020 |
| Samsung       | R510/P510                   | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| ASUSTek       | N46VZ                       | [fca4008513](https://linux-hardware.org/?probe=fca4008513) | May 23, 2020 |
| Acer          | Aspire E1-571G              | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| HP            | Pavilion dv6700             | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | [00c438c052](https://linux-hardware.org/?probe=00c438c052) | Nov 01, 2019 |
| ASUSTek       | N46VZ                       | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| ASUSTek       | N46VZ                       | [0974f428e0](https://linux-hardware.org/?probe=0974f428e0) | Sep 28, 2019 |
| MSI           | MEGA BOOK S430              | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Lenovo        | G505s 20255                 | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [8fc1a0caf2](https://linux-hardware.org/?probe=8fc1a0caf2) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | [731932629b](https://linux-hardware.org/?probe=731932629b) | Aug 15, 2019 |
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
| Kometa P10         | 48        | 39.67%  |
| ALT Linux 9.1      | 20        | 16.53%  |
| ALT Linux 10.0     | 13        | 10.74%  |
| ALT Linux 9.0      | 9         | 7.44%   |
| ALT Linux 9.2      | 8         | 6.61%   |
| ALT Linux 5.0.0    | 4         | 3.31%   |
| ALT Linux P9       | 2         | 1.65%   |
| ALT Linux P8       | 2         | 1.65%   |
| ALT Linux 20201124 | 2         | 1.65%   |
| ALT Linux 20191026 | 2         | 1.65%   |
| ALT Linux P10      | 1         | 0.83%   |
| ALT Linux 9        | 1         | 0.83%   |
| ALT Linux 8.990    | 1         | 0.83%   |
| ALT Linux 8.920    | 1         | 0.83%   |
| ALT Linux 8.3      | 1         | 0.83%   |
| ALT Linux 8.2      | 1         | 0.83%   |
| ALT Linux 8.0.0    | 1         | 0.83%   |
| ALT Linux 8        | 1         | 0.83%   |
| ALT Linux 4.0      | 1         | 0.83%   |
| ALT Linux 20190624 | 1         | 0.83%   |
| ALT Linux          | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 114       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.102-std-def-alt1       | 32        | 23.88%  |
| 5.10.109-std-def-alt1       | 17        | 12.69%  |
| 5.10.88-std-def-alt1        | 6         | 4.48%   |
| 5.4.68-std-def-alt1.1       | 3         | 2.24%   |
| 5.4.28-std-def-alt1         | 3         | 2.24%   |
| 5.4.62-std-def-alt1         | 2         | 1.49%   |
| 5.4.51-std-def-alt1         | 2         | 1.49%   |
| 5.15.25-un-def-alt1         | 2         | 1.49%   |
| 5.10.82-std-def-alt1        | 2         | 1.49%   |
| 5.10.62-un-def-alt1         | 2         | 1.49%   |
| 5.10.61-un-def-alt1         | 2         | 1.49%   |
| 5.10.37-un-def-alt1         | 2         | 1.49%   |
| 5.10.32-un-def-alt1         | 2         | 1.49%   |
| 5.10.17-un-def-alt1         | 2         | 1.49%   |
| 4.19.79-std-def-alt1        | 2         | 1.49%   |
| 4.19.66-std-def-alt1        | 2         | 1.49%   |
| 4.19.102-std-def-alt1       | 2         | 1.49%   |
| 5.7.19-un-def-alt1          | 1         | 0.75%   |
| 5.7.14-un-def-alt1          | 1         | 0.75%   |
| 5.4.98-std-def-alt1         | 1         | 0.75%   |
| 5.4.87-std-def-alt1         | 1         | 0.75%   |
| 5.4.85-std-def-alt1         | 1         | 0.75%   |
| 5.4.84-std-def-alt1         | 1         | 0.75%   |
| 5.4.81-std-def-alt1         | 1         | 0.75%   |
| 5.4.44-std-def-alt1         | 1         | 0.75%   |
| 5.4.41-std-def-alt1         | 1         | 0.75%   |
| 5.4.40-std-def-alt1         | 1         | 0.75%   |
| 5.4.3-un-def-alt1           | 1         | 0.75%   |
| 5.4.171-std-def-alt1        | 1         | 0.75%   |
| 5.4.144-std-def-alt1        | 1         | 0.75%   |
| 5.4.127-std-def-alt1        | 1         | 0.75%   |
| 5.4.117-std-def-alt1        | 1         | 0.75%   |
| 5.4.115-std-def-alt1        | 1         | 0.75%   |
| 5.4.107-std-def-alt1        | 1         | 0.75%   |
| 5.4.107-std-def-alt0.c9f    | 1         | 0.75%   |
| 5.3.6-un-def-alt1           | 1         | 0.75%   |
| 5.3.5-un-def-alt1           | 1         | 0.75%   |
| 5.2.17-un-def-alt1          | 1         | 0.75%   |
| 5.16.5-un-def-alt1          | 1         | 0.75%   |
| 5.15.34-un-def-alt1         | 1         | 0.75%   |
| 5.15.33-un-def-alt1         | 1         | 0.75%   |
| 5.15.23-un-def-alt1         | 1         | 0.75%   |
| 5.15.15-un-def-alt1         | 1         | 0.75%   |
| 5.13.19-un-def-alt1         | 1         | 0.75%   |
| 5.13.15-un-def-alt1         | 1         | 0.75%   |
| 5.10.93-std-def-alt1        | 1         | 0.75%   |
| 5.10.92-std-def-alt1        | 1         | 0.75%   |
| 5.10.69-std-def-alt1        | 1         | 0.75%   |
| 5.10.54-std-def-alt2        | 1         | 0.75%   |
| 5.10.52-un-def-alt1         | 1         | 0.75%   |
| 5.10.40-un-def-alt1         | 1         | 0.75%   |
| 5.10.35-std-def-alt1        | 1         | 0.75%   |
| 5.10.29-un-def-alt2         | 1         | 0.75%   |
| 5.10.27-un-def-alt1         | 1         | 0.75%   |
| 5.10.111-std-def-alt1       | 1         | 0.75%   |
| 5.10.10-un-def-alt1         | 1         | 0.75%   |
| 4.9.35-un-def-alt0.M80P.1   | 1         | 0.75%   |
| 4.9.145-std-def-alt0.M80P.1 | 1         | 0.75%   |
| 4.9.133-std-def-alt0.M80P.1 | 1         | 0.75%   |
| 4.9.131-std-def-alt0.M80P.1 | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.102 | 32        | 23.88%  |
| 5.10.109 | 17        | 12.69%  |
| 5.10.88  | 6         | 4.48%   |
| 5.4.68   | 3         | 2.24%   |
| 5.4.28   | 3         | 2.24%   |
| 5.4.62   | 2         | 1.49%   |
| 5.4.51   | 2         | 1.49%   |
| 5.4.107  | 2         | 1.49%   |
| 5.15.25  | 2         | 1.49%   |
| 5.10.82  | 2         | 1.49%   |
| 5.10.62  | 2         | 1.49%   |
| 5.10.61  | 2         | 1.49%   |
| 5.10.37  | 2         | 1.49%   |
| 5.10.32  | 2         | 1.49%   |
| 5.10.17  | 2         | 1.49%   |
| 4.19.79  | 2         | 1.49%   |
| 4.19.66  | 2         | 1.49%   |
| 4.19.102 | 2         | 1.49%   |
| 5.7.19   | 1         | 0.75%   |
| 5.7.14   | 1         | 0.75%   |
| 5.4.98   | 1         | 0.75%   |
| 5.4.87   | 1         | 0.75%   |
| 5.4.85   | 1         | 0.75%   |
| 5.4.84   | 1         | 0.75%   |
| 5.4.81   | 1         | 0.75%   |
| 5.4.44   | 1         | 0.75%   |
| 5.4.41   | 1         | 0.75%   |
| 5.4.40   | 1         | 0.75%   |
| 5.4.3    | 1         | 0.75%   |
| 5.4.171  | 1         | 0.75%   |
| 5.4.144  | 1         | 0.75%   |
| 5.4.127  | 1         | 0.75%   |
| 5.4.117  | 1         | 0.75%   |
| 5.4.115  | 1         | 0.75%   |
| 5.3.6    | 1         | 0.75%   |
| 5.3.5    | 1         | 0.75%   |
| 5.2.17   | 1         | 0.75%   |
| 5.16.5   | 1         | 0.75%   |
| 5.15.34  | 1         | 0.75%   |
| 5.15.33  | 1         | 0.75%   |
| 5.15.23  | 1         | 0.75%   |
| 5.15.15  | 1         | 0.75%   |
| 5.13.19  | 1         | 0.75%   |
| 5.13.15  | 1         | 0.75%   |
| 5.10.93  | 1         | 0.75%   |
| 5.10.92  | 1         | 0.75%   |
| 5.10.69  | 1         | 0.75%   |
| 5.10.54  | 1         | 0.75%   |
| 5.10.52  | 1         | 0.75%   |
| 5.10.40  | 1         | 0.75%   |
| 5.10.35  | 1         | 0.75%   |
| 5.10.29  | 1         | 0.75%   |
| 5.10.27  | 1         | 0.75%   |
| 5.10.111 | 1         | 0.75%   |
| 5.10.10  | 1         | 0.75%   |
| 4.9.35   | 1         | 0.75%   |
| 4.9.145  | 1         | 0.75%   |
| 4.9.133  | 1         | 0.75%   |
| 4.9.131  | 1         | 0.75%   |
| 4.4.12   | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 77        | 61.6%   |
| 5.4     | 20        | 16%     |
| 4.19    | 11        | 8.8%    |
| 5.15    | 5         | 4%      |
| 4.9     | 3         | 2.4%    |
| 5.7     | 2         | 1.6%    |
| 5.3     | 2         | 1.6%    |
| 5.13    | 2         | 1.6%    |
| 5.2     | 1         | 0.8%    |
| 5.16    | 1         | 0.8%    |
| 4.4     | 1         | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 93.86%  |
| i686   | 7         | 6.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 81        | 68.64%  |
| Unknown         | 14        | 11.86%  |
| XFCE            | 13        | 11.02%  |
| LXQt            | 4         | 3.39%   |
| Cinnamon        | 3         | 2.54%   |
| GNOME           | 2         | 1.69%   |
| GNOME Flashback | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 112       | 97.39%  |
| Tty     | 2         | 1.74%   |
| Wayland | 1         | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 70        | 59.32%  |
| TDM     | 22        | 18.64%  |
| LightDM | 20        | 16.95%  |
| Unknown | 4         | 3.39%   |
| XDM     | 1         | 0.85%   |
| GDM     | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 86        | 72.27%  |
| Unknown | 26        | 21.85%  |
| en_US   | 5         | 4.2%    |
| POSIX   | 1         | 0.84%   |
| C       | 1         | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 91        | 78.45%  |
| BIOS | 25        | 21.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 99        | 86.09%  |
| Overlay | 11        | 9.57%   |
| Btrfs   | 3         | 2.61%   |
| Unknown | 2         | 1.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 90        | 77.59%  |
| MBR     | 21        | 18.1%   |
| Unknown | 5         | 4.31%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 96.55%  |
| Yes       | 4         | 3.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 51.3%   |
| No        | 56        | 48.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 46        | 40.35%  |
| Lenovo              | 16        | 14.04%  |
| ASUSTek Computer    | 15        | 13.16%  |
| Acer                | 10        | 8.77%   |
| ICL                 | 7         | 6.14%   |
| Dell                | 6         | 5.26%   |
| Samsung Electronics | 3         | 2.63%   |
| MSI                 | 3         | 2.63%   |
| Toshiba             | 1         | 0.88%   |
| Timi                | 1         | 0.88%   |
| HUAWEI              | 1         | 0.88%   |
| eMachines           | 1         | 0.88%   |
| Durabook            | 1         | 0.88%   |
| DEPO Computers      | 1         | 0.88%   |
| Aquarius            | 1         | 0.88%   |
| 3Logic Group        | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP 250 G7 Notebook PC                      | 12        | 10.53%  |
| HP ProBook 440 G5                          | 8         | 7.02%   |
| ICL RAYbook Si1512                         | 6         | 5.26%   |
| HP ZBook 17 G5                             | 6         | 5.26%   |
| HP EliteBook 840 G4                        | 3         | 2.63%   |
| HP 250 G6 Notebook PC                      | 3         | 2.63%   |
| Dell Latitude 3420                         | 3         | 2.63%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT       | 2         | 1.75%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 1.75%   |
| HP EliteBook 8470p                         | 2         | 1.75%   |
| ASUS N46VZ                                 | 2         | 1.75%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE  | 2         | 1.75%   |
| Acer TravelMate 5760                       | 2         | 1.75%   |
| Toshiba Satellite A100                     | 1         | 0.88%   |
| Timi TM1701                                | 1         | 0.88%   |
| Samsung RV413/RV513/E3413                  | 1         | 0.88%   |
| Samsung R510/P510                          | 1         | 0.88%   |
| Samsung 750XDA                             | 1         | 0.88%   |
| MSI X300/X340/X400 series                  | 1         | 0.88%   |
| MSI MEGA BOOK S430                         | 1         | 0.88%   |
| MSI GE72 7RE                               | 1         | 0.88%   |
| Lenovo V510-15IKB 80WQ                     | 1         | 0.88%   |
| Lenovo ThinkPad X220 4291M85               | 1         | 0.88%   |
| Lenovo ThinkPad 13 2nd Gen 20J1S0EU00      | 1         | 0.88%   |
| Lenovo IdeaPad 5 15IIL05 81YK              | 1         | 0.88%   |
| Lenovo IdeaPad 310-15ISK 80SM              | 1         | 0.88%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 1         | 0.88%   |
| Lenovo IdeaPad 3 15IGL05 81WQ              | 1         | 0.88%   |
| Lenovo G570 20079                          | 1         | 0.88%   |
| Lenovo G505s 20255                         | 1         | 0.88%   |
| Lenovo B590 20206                          | 1         | 0.88%   |
| Lenovo B50-10 80QR                         | 1         | 0.88%   |
| Lenovo 3000 G430 4153/200                  | 1         | 0.88%   |
| ICL NJ50_70CU                              | 1         | 0.88%   |
| HUAWEI NBLK-WAX9X                          | 1         | 0.88%   |
| HP ProBook 450 G3                          | 1         | 0.88%   |
| HP Pavilion Laptop 15-cc5xx                | 1         | 0.88%   |
| HP Pavilion Gaming Laptop 17-cd1xxx        | 1         | 0.88%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 1         | 0.88%   |
| HP Pavilion dv6700                         | 1         | 0.88%   |
| HP Laptop 17-by0xxx                        | 1         | 0.88%   |
| HP Laptop 15s-fq2xxx                       | 1         | 0.88%   |
| HP Laptop 15s-fq0xxx                       | 1         | 0.88%   |
| HP Laptop 14s-dq1xxx                       | 1         | 0.88%   |
| HP 255 G2                                  | 1         | 0.88%   |
| HP 250 G3                                  | 1         | 0.88%   |
| eMachines eME728                           | 1         | 0.88%   |
| Durabook Z14                               | 1         | 0.88%   |
| DEPO Computers DPC156                      | 1         | 0.88%   |
| Dell Latitude 3590                         | 1         | 0.88%   |
| Dell Inspiron 3542                         | 1         | 0.88%   |
| Dell G3 3779                               | 1         | 0.88%   |
| ASUS ZenBook UX431DA_UM431DA               | 1         | 0.88%   |
| ASUS X510UNR                               | 1         | 0.88%   |
| ASUS X200MA                                | 1         | 0.88%   |
| ASUS VivoBook_ASUSLaptop X421IA_M433IA     | 1         | 0.88%   |
| ASUS VivoBook_ASUSLaptop X421DA_M413DA     | 1         | 0.88%   |
| ASUS VivoBook 15_ASUS Laptop X507MA_X507MA | 1         | 0.88%   |
| ASUS K52JT                                 | 1         | 0.88%   |
| ASUS ASUS TUF Gaming A17 FA706IC_FA706IC   | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| HP 250                | 16        | 14.04%  |
| HP ProBook            | 9         | 7.89%   |
| ICL RAYbook           | 6         | 5.26%   |
| HP ZBook              | 6         | 5.26%   |
| Acer Aspire           | 6         | 5.26%   |
| HP EliteBook          | 5         | 4.39%   |
| Lenovo ThinkPad       | 4         | 3.51%   |
| Lenovo IdeaPad        | 4         | 3.51%   |
| HP Pavilion           | 4         | 3.51%   |
| HP Laptop             | 4         | 3.51%   |
| Dell Latitude         | 4         | 3.51%   |
| ASUS ASUS             | 4         | 3.51%   |
| ASUS VivoBook         | 3         | 2.63%   |
| Lenovo ThinkBook      | 2         | 1.75%   |
| ASUS N46VZ            | 2         | 1.75%   |
| Acer TravelMate       | 2         | 1.75%   |
| Toshiba Satellite     | 1         | 0.88%   |
| Timi TM1701           | 1         | 0.88%   |
| Samsung RV413         | 1         | 0.88%   |
| Samsung R510          | 1         | 0.88%   |
| Samsung 750XDA        | 1         | 0.88%   |
| MSI X300              | 1         | 0.88%   |
| MSI MEGA              | 1         | 0.88%   |
| MSI GE72              | 1         | 0.88%   |
| Lenovo V510-15IKB     | 1         | 0.88%   |
| Lenovo G570           | 1         | 0.88%   |
| Lenovo G505s          | 1         | 0.88%   |
| Lenovo B590           | 1         | 0.88%   |
| Lenovo B50-10         | 1         | 0.88%   |
| Lenovo 3000           | 1         | 0.88%   |
| ICL NJ50              | 1         | 0.88%   |
| HUAWEI NBLK-WAX9X     | 1         | 0.88%   |
| HP 255                | 1         | 0.88%   |
| eMachines eME728      | 1         | 0.88%   |
| Durabook Z14          | 1         | 0.88%   |
| DEPO Computers DPC156 | 1         | 0.88%   |
| Dell Inspiron         | 1         | 0.88%   |
| Dell G3               | 1         | 0.88%   |
| ASUS ZenBook          | 1         | 0.88%   |
| ASUS X510UNR          | 1         | 0.88%   |
| ASUS X200MA           | 1         | 0.88%   |
| ASUS K52JT            | 1         | 0.88%   |
| ASUS 1101HA           | 1         | 0.88%   |
| ASUS 1001PXD          | 1         | 0.88%   |
| Aquarius NS585        | 1         | 0.88%   |
| Acer Swift            | 1         | 0.88%   |
| Acer NC-ES1-131-C1NL  | 1         | 0.88%   |
| 3Logic Group Graviton | 1         | 0.88%   |
| Unknown               | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 22        | 19.3%   |
| 2017 | 18        | 15.79%  |
| 2020 | 16        | 14.04%  |
| 2019 | 13        | 11.4%   |
| 2021 | 9         | 7.89%   |
| 2011 | 7         | 6.14%   |
| 2016 | 5         | 4.39%   |
| 2012 | 5         | 4.39%   |
| 2010 | 4         | 3.51%   |
| 2014 | 3         | 2.63%   |
| 2008 | 3         | 2.63%   |
| 2015 | 2         | 1.75%   |
| 2013 | 2         | 1.75%   |
| 2009 | 2         | 1.75%   |
| 2007 | 2         | 1.75%   |
| 2006 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 114       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 98        | 83.76%  |
| Enabled  | 19        | 16.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 68        | 59.13%  |
| 3.01-4.0   | 23        | 20%     |
| 16.01-24.0 | 11        | 9.57%   |
| 1.01-2.0   | 6         | 5.22%   |
| 8.01-16.0  | 5         | 4.35%   |
| 2.01-3.0   | 2         | 1.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 60        | 48.78%  |
| 0.51-1.0  | 22        | 17.89%  |
| 2.01-3.0  | 20        | 16.26%  |
| 3.01-4.0  | 11        | 8.94%   |
| 4.01-8.0  | 7         | 5.69%   |
| 0.01-0.5  | 2         | 1.63%   |
| 8.01-16.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 77.12%  |
| 2      | 23        | 19.49%  |
| 0      | 2         | 1.69%   |
| 4      | 1         | 0.85%   |
| 3      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 62.93%  |
| Yes       | 43        | 37.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 89.47%  |
| No        | 12        | 10.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 78.26%  |
| No        | 25        | 21.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Russia     | 105       | 92.11%  |
| Greece     | 3         | 2.63%   |
| Uzbekistan | 1         | 0.88%   |
| Ukraine    | 1         | 0.88%   |
| Egypt      | 1         | 0.88%   |
| Czechia    | 1         | 0.88%   |
| Costa Rica | 1         | 0.88%   |
| Belarus    | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 74        | 61.16%  |
| St Petersburg | 4         | 3.31%   |
| Barnaul       | 4         | 3.31%   |
| Perm          | 2         | 1.65%   |
| Novyy Oskol   | 2         | 1.65%   |
| Novoaltaysk   | 2         | 1.65%   |
| Yekaterinburg | 1         | 0.83%   |
| Vergina       | 1         | 0.83%   |
| Thessaloniki  | 1         | 0.83%   |
| Tashkent      | 1         | 0.83%   |
| Surgut        | 1         | 0.83%   |
| Sredneuralsk  | 1         | 0.83%   |
| Sevastopol    | 1         | 0.83%   |
| Saratov       | 1         | 0.83%   |
| San JosГ©   | 1         | 0.83%   |
| Samara        | 1         | 0.83%   |
| Rubtsovsk     | 1         | 0.83%   |
| Prague        | 1         | 0.83%   |
| Omsk          | 1         | 0.83%   |
| Obninsk       | 1         | 0.83%   |
| Novosibirsk   | 1         | 0.83%   |
| Novoburanovo  | 1         | 0.83%   |
| Nizhny Tagil  | 1         | 0.83%   |
| Lesosibirsk   | 1         | 0.83%   |
| Krasnoyarsk   | 1         | 0.83%   |
| Krasnodar     | 1         | 0.83%   |
| Kostroma      | 1         | 0.83%   |
| Korolyov      | 1         | 0.83%   |
| Kirov         | 1         | 0.83%   |
| Khabarovsk    | 1         | 0.83%   |
| Kemerovo      | 1         | 0.83%   |
| KazanвЂ™  | 1         | 0.83%   |
| Kaliningrad   | 1         | 0.83%   |
| Hurghada      | 1         | 0.83%   |
| Edessa        | 1         | 0.83%   |
| Cairo         | 1         | 0.83%   |
| Bratsk        | 1         | 0.83%   |
| Berlezh       | 1         | 0.83%   |
| Astrakhan     | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 33     | 15.33%  |
| Intel               | 19        | 22     | 13.87%  |
| SK Hynix            | 18        | 18     | 13.14%  |
| Samsung Electronics | 18        | 23     | 13.14%  |
| WDC                 | 16        | 20     | 11.68%  |
| Toshiba             | 8         | 10     | 5.84%   |
| FOXLINE             | 7         | 7      | 5.11%   |
| Kingston            | 4         | 4      | 2.92%   |
| Hitachi             | 3         | 3      | 2.19%   |
| HGST                | 3         | 3      | 2.19%   |
| A-DATA Technology   | 3         | 3      | 2.19%   |
| Unknown             | 2         | 2      | 1.46%   |
| SSSTC               | 2         | 2      | 1.46%   |
| SanDisk             | 2         | 2      | 1.46%   |
| Fujitsu             | 2         | 2      | 1.46%   |
| Crucial             | 2         | 2      | 1.46%   |
| XPG                 | 1         | 2      | 0.73%   |
| Transcend           | 1         | 1      | 0.73%   |
| PNY                 | 1         | 1      | 0.73%   |
| KingDian            | 1         | 1      | 0.73%   |
| Gigabyte Technology | 1         | 1      | 0.73%   |
| Apacer              | 1         | 1      | 0.73%   |
| AMD                 | 1         | 1      | 0.73%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB   | 12        | 8.51%   |
| Intel SSDPEKKF256G7H 256GB                | 8         | 5.67%   |
| FOXLINE FLSSD256M80E13TCX5 256GB          | 7         | 4.96%   |
| Seagate ST1000LM049-2GH172 1TB            | 6         | 4.26%   |
| Intel SSDPEMKF256G8H 256GB                | 6         | 4.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 4         | 2.84%   |
| Samsung MZALQ256HAJD-000L2 256GB          | 4         | 2.84%   |
| WDC WD5000LPLX-60ZNTT2 500GB              | 2         | 1.42%   |
| WDC WD3200BPVT-22JJ5T0 320GB              | 2         | 1.42%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.42%   |
| Toshiba KXG50ZNV256G 256GB                | 2         | 1.42%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB            | 2         | 1.42%   |
| Seagate ST9250315AS 250GB                 | 2         | 1.42%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 1.42%   |
| Samsung SSD 860 EVO 250GB                 | 2         | 1.42%   |
| Intel SSDPEKNW512G8H 512GB                | 2         | 1.42%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 1.42%   |
| XPG NVMe SSD Drive 256GB                  | 1         | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 0.71%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 1         | 0.71%   |
| WDC WDS100T2B0B-00YS70 1TB SSD            | 1         | 0.71%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.71%   |
| WDC WD5000LPVX-80V0TT0 500GB              | 1         | 0.71%   |
| WDC WD5000LPVX-60V0TT0 500GB              | 1         | 0.71%   |
| WDC WD5000LPLX-60ZNTT1 500GB              | 1         | 0.71%   |
| WDC WD3200BEVT-22A23T0 320GB              | 1         | 0.71%   |
| WDC WD1600BEVS-22RST0 160GB               | 1         | 0.71%   |
| WDC WD1200BEVS-60UST0 120GB               | 1         | 0.71%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB      | 1         | 0.71%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB      | 1         | 0.71%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 1         | 0.71%   |
| Unknown USDU1  32GB                       | 1         | 0.71%   |
| Unknown SDC  8GB                          | 1         | 0.71%   |
| Transcend TS240GSSD220S 240GB             | 1         | 0.71%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.71%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 0.71%   |
| Toshiba MK6465GSX 640GB                   | 1         | 0.71%   |
| Toshiba MK2576GSX 250GB                   | 1         | 0.71%   |
| Toshiba HDWL110 1TB                       | 1         | 0.71%   |
| SK Hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 0.71%   |
| SK Hynix SC311 SATA 128GB SSD             | 1         | 0.71%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD     | 1         | 0.71%   |
| SK Hynix HFM256GDJTNG-8310A 256GB         | 1         | 0.71%   |
| SK Hynix HBG4e  32GB                      | 1         | 0.71%   |
| SK Hynix BC511 HFM512GDJTNI-82A0A 512GB   | 1         | 0.71%   |
| Seagate ST9640320AS 640GB                 | 1         | 0.71%   |
| Seagate ST9500325AS 500GB                 | 1         | 0.71%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 0.71%   |
| Seagate ST2000LM007-1R8174 2TB            | 1         | 0.71%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 0.71%   |
| Seagate Expansion+ 2TB                    | 1         | 0.71%   |
| Seagate BUP Slim SL 1TB                   | 1         | 0.71%   |
| SanDisk SD8SN8U128G1002 128GB SSD         | 1         | 0.71%   |
| Sandisk NVMe SSD Drive 512GB              | 1         | 0.71%   |
| Samsung SSD 970 EVO 250GB                 | 1         | 0.71%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 0.71%   |
| Samsung PM991a NVMe 256GB                 | 1         | 0.71%   |
| Samsung NVMe SSD Drive 512GB              | 1         | 0.71%   |
| Samsung NVMe SSD Drive 1TB                | 1         | 0.71%   |
| Samsung MZYTY128HDHP-000L2 128GB SSD      | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 21        | 33     | 46.67%  |
| WDC     | 10        | 11     | 22.22%  |
| Toshiba | 6         | 8      | 13.33%  |
| Hitachi | 3         | 3      | 6.67%   |
| HGST    | 3         | 3      | 6.67%   |
| Fujitsu | 2         | 2      | 4.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 22.73%  |
| WDC                 | 3         | 6      | 13.64%  |
| SK Hynix            | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| Crucial             | 2         | 2      | 9.09%   |
| A-DATA Technology   | 2         | 2      | 9.09%   |
| Transcend           | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| PNY                 | 1         | 1      | 4.55%   |
| KingDian            | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| AMD                 | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 64        | 76     | 48.48%  |
| HDD  | 44        | 60     | 33.33%  |
| SSD  | 21        | 25     | 15.91%  |
| MMC  | 3         | 3      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 64        | 76     | 50.79%  |
| SATA | 56        | 82     | 44.44%  |
| SAS  | 3         | 3      | 2.38%   |
| MMC  | 3         | 3      | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 47     | 63.49%  |
| 0.51-1.0   | 21        | 36     | 33.33%  |
| 1.01-2.0   | 2         | 2      | 3.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 62        | 52.1%   |
| 251-500    | 21        | 17.65%  |
| 51-100     | 14        | 11.76%  |
| 1-20       | 7         | 5.88%   |
| 21-50      | 6         | 5.04%   |
| 501-1000   | 6         | 5.04%   |
| 1001-2000  | 3         | 2.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 73        | 58.87%  |
| 21-50    | 24        | 19.35%  |
| 101-250  | 11        | 8.87%   |
| 51-100   | 9         | 7.26%   |
| 251-500  | 5         | 4.03%   |
| 501-1000 | 2         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB               | 2         | 2      | 13.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 14     | 13.33%  |
| WDC WD5000LPVX-60V0TT0 500GB            | 1         | 1      | 6.67%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 1         | 1      | 6.67%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 6.67%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 1         | 1      | 6.67%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB               | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 6.67%   |
| Hitachi HTS542525K9A300 250GB           | 1         | 1      | 6.67%   |
| Hitachi HTS541610J9SA00 100GB           | 1         | 1      | 6.67%   |
| HGST HTS545050A7E680 500GB              | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 18     | 40%     |
| WDC      | 3         | 3      | 20%     |
| SK Hynix | 2         | 2      | 13.33%  |
| Hitachi  | 2         | 2      | 13.33%  |
| Toshiba  | 1         | 1      | 6.67%   |
| HGST     | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 18     | 46.15%  |
| WDC     | 3         | 3      | 23.08%  |
| Hitachi | 2         | 2      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 25     | 86.67%  |
| NVMe | 1         | 1      | 6.67%   |
| SSD  | 1         | 1      | 6.67%   |

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
| Works    | 97        | 122    | 80.17%  |
| Malfunc  | 15        | 27     | 12.4%   |
| Detected | 9         | 15     | 7.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 94        | 61.04%  |
| SK Hynix                       | 15        | 9.74%   |
| Samsung Electronics            | 13        | 8.44%   |
| AMD                            | 9         | 5.84%   |
| Phison Electronics             | 8         | 5.19%   |
| Sandisk                        | 4         | 2.6%    |
| Toshiba America Info Systems   | 2         | 1.3%    |
| Solid State Storage Technology | 2         | 1.3%    |
| Nvidia                         | 2         | 1.3%    |
| Kingston Technology Company    | 2         | 1.3%    |
| VIA Technologies               | 1         | 0.65%   |
| Shenzhen Longsys Electronics   | 1         | 0.65%   |
| ADATA Technology               | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 21        | 11.73%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 9.5%    |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 13        | 7.26%   |
| Intel SSD 600P Series                                                                  | 9         | 5.03%   |
| Samsung NVMe SSD Controller 980                                                        | 8         | 4.47%   |
| Phison PS5013 E13 NVMe Controller                                                      | 8         | 4.47%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 8         | 4.47%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 7         | 3.91%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 7         | 3.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 7         | 3.91%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 6         | 3.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 3.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 2.79%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 2.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 2.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.68%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 1.12%   |
| Solid State Storage Non-Volatile memory controller                                     | 2         | 1.12%   |
| SK Hynix BC511                                                                         | 2         | 1.12%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 2         | 1.12%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 1.12%   |
| Intel SSD 660P Series                                                                  | 2         | 1.12%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.12%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 1.12%   |
| VIA VT8237/8251 Serial ATA Controller                                                  | 1         | 0.56%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                       | 1         | 0.56%   |
| Nvidia MCP67 IDE Controller                                                            | 1         | 0.56%   |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 0.56%   |
| Nvidia MCP51 Serial ATA Controller                                                     | 1         | 0.56%   |
| Nvidia MCP51 IDE                                                                       | 1         | 0.56%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.56%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.56%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 0.56%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 0.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 0.56%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                  | 1         | 0.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 81        | 46.55%  |
| NVMe | 64        | 36.78%  |
| RAID | 22        | 12.64%  |
| IDE  | 7         | 4.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 100       | 87.72%  |
| AMD          | 13        | 11.4%   |
| CentaurHauls | 1         | 0.88%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 11.4%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 7.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 7.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 6.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 6.14%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 5         | 4.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 3.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.63%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.75%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 1.75%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.75%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.75%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.75%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.88%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.88%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.88%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.88%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.88%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.88%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.88%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.88%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.88%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.88%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 0.88%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 0.88%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 0.88%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 0.88%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 0.88%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 0.88%   |
| Intel Core Duo CPU T2250 @ 1.73GHz            | 1         | 0.88%   |
| Intel Core 2 Solo CPU U3500 @ 1.40GHz         | 1         | 0.88%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 0.88%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 0.88%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 0.88%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 0.88%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 0.88%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 0.88%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 0.88%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 0.88%   |
| CentaurHauls VIA C7-M Processor 1600MHz       | 1         | 0.88%   |
| AMD Turion 64 X2 Mobile Technology TL-58      | 1         | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 0.88%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 1         | 0.88%   |
| AMD E-450 APU with Radeon HD Graphics         | 1         | 0.88%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-57    | 1         | 0.88%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 0.88%   |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 32.46%  |
| Intel Core i3           | 24        | 21.05%  |
| Intel Core i7           | 13        | 11.4%   |
| Other                   | 10        | 8.77%   |
| Intel Celeron           | 4         | 3.51%   |
| AMD Ryzen 5             | 4         | 3.51%   |
| AMD Ryzen 7             | 3         | 2.63%   |
| Intel Pentium Silver    | 2         | 1.75%   |
| Intel Pentium Gold      | 2         | 1.75%   |
| Intel Atom              | 2         | 1.75%   |
| AMD A8                  | 2         | 1.75%   |
| Intel Pentium Dual-Core | 1         | 0.88%   |
| Intel Pentium           | 1         | 0.88%   |
| Intel Core Duo          | 1         | 0.88%   |
| Intel Core 2 Solo       | 1         | 0.88%   |
| Intel Core 2 Duo        | 1         | 0.88%   |
| Intel Celeron Dual-Core | 1         | 0.88%   |
| CentaurHauls VIA C7     | 1         | 0.88%   |
| AMD Turion 64 X2 Mobile | 1         | 0.88%   |
| AMD E1                  | 1         | 0.88%   |
| AMD E                   | 1         | 0.88%   |
| AMD Athlon 64 X2        | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 46.49%  |
| 4      | 46        | 40.35%  |
| 6      | 8         | 7.02%   |
| 1      | 4         | 3.51%   |
| 8      | 3         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 95        | 83.33%  |
| 1      | 19        | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 110       | 96.49%  |
| 32-bit         | 3         | 2.63%   |
| Unknown        | 1         | 0.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806e9    | 15        | 13.04%  |
| Unknown    | 14        | 12.17%  |
| 0x806ec    | 11        | 9.57%   |
| 0x806c1    | 10        | 8.7%    |
| 0x906ea    | 8         | 6.96%   |
| 0xa0660    | 7         | 6.09%   |
| 0x806ea    | 6         | 5.22%   |
| 0x306a9    | 5         | 4.35%   |
| 0x706e5    | 4         | 3.48%   |
| 0x206a7    | 4         | 3.48%   |
| 0x406e3    | 3         | 2.61%   |
| 0x1067a    | 3         | 2.61%   |
| 0x08600106 | 3         | 2.61%   |
| 0x706a8    | 2         | 1.74%   |
| 0x40651    | 2         | 1.74%   |
| 0x30678    | 2         | 1.74%   |
| 0x08108109 | 2         | 1.74%   |
| 0xa0652    | 1         | 0.87%   |
| 0x706a1    | 1         | 0.87%   |
| 0x6ec      | 1         | 0.87%   |
| 0x406c3    | 1         | 0.87%   |
| 0x20655    | 1         | 0.87%   |
| 0x20652    | 1         | 0.87%   |
| 0x106ca    | 1         | 0.87%   |
| 0x106c2    | 1         | 0.87%   |
| 0x10676    | 1         | 0.87%   |
| 0x08600104 | 1         | 0.87%   |
| 0x08108102 | 1         | 0.87%   |
| 0x07030105 | 1         | 0.87%   |
| 0x0700010f | 1         | 0.87%   |
| 0x06001119 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 46        | 40.35%  |
| TigerLake     | 11        | 9.65%   |
| CometLake     | 8         | 7.02%   |
| SandyBridge   | 6         | 5.26%   |
| IvyBridge     | 5         | 4.39%   |
| Zen 2         | 4         | 3.51%   |
| Penryn        | 4         | 3.51%   |
| IceLake       | 4         | 3.51%   |
| Zen+          | 3         | 2.63%   |
| Skylake       | 3         | 2.63%   |
| Silvermont    | 3         | 2.63%   |
| Goldmont plus | 3         | 2.63%   |
| Westmere      | 2         | 1.75%   |
| K8 Hammer     | 2         | 1.75%   |
| Haswell       | 2         | 1.75%   |
| Bonnell       | 2         | 1.75%   |
| Puma          | 1         | 0.88%   |
| Piledriver    | 1         | 0.88%   |
| P6            | 1         | 0.88%   |
| Jaguar        | 1         | 0.88%   |
| Bobcat        | 1         | 0.88%   |
| Unknown       | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 96        | 70.59%  |
| Nvidia           | 26        | 19.12%  |
| AMD              | 13        | 9.56%   |
| VIA Technologies | 1         | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 18        | 13.04%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 9.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 5.8%    |
| Intel Comet Lake UHD Graphics                                                            | 7         | 5.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 5.07%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 6         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 3.62%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.9%    |
| AMD Renoir                                                                               | 4         | 2.9%    |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 2.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.17%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.45%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.45%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.45%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 2         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.45%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                    | 2         | 1.45%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.72%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia TU117M                                                                            | 1         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.72%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.72%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.72%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.72%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.72%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 0.72%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 0.72%   |
| Nvidia C51 [GeForce Go 6100]                                                             | 1         | 0.72%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.72%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.72%   |
| Intel HD Graphics 630                                                                    | 1         | 0.72%   |
| Intel HD Graphics 520                                                                    | 1         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.72%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.72%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 0.72%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.72%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 67.54%  |
| Intel + Nvidia | 18        | 15.79%  |
| 1 x AMD        | 8         | 7.02%   |
| 1 x Nvidia     | 5         | 4.39%   |
| AMD + Nvidia   | 3         | 2.63%   |
| 2 x AMD        | 1         | 0.88%   |
| 1 x VIA        | 1         | 0.88%   |
| Intel + AMD    | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 105       | 89.74%  |
| Proprietary | 9         | 7.69%   |
| Unknown     | 3         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 77.59%  |
| 0.01-0.5   | 8         | 6.9%    |
| 3.01-4.0   | 7         | 6.03%   |
| 0.51-1.0   | 7         | 6.03%   |
| 1.01-2.0   | 4         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 31        | 25.41%  |
| Chimei Innolux          | 24        | 19.67%  |
| AU Optronics            | 22        | 18.03%  |
| LG Display              | 15        | 12.3%   |
| Samsung Electronics     | 10        | 8.2%    |
| Sharp                   | 4         | 3.28%   |
| Chi Mei Optoelectronics | 4         | 3.28%   |
| PANDA                   | 3         | 2.46%   |
| BenQ                    | 2         | 1.64%   |
| AOC                     | 2         | 1.64%   |
| STA                     | 1         | 0.82%   |
| PRM                     | 1         | 0.82%   |
| KDC                     | 1         | 0.82%   |
| Hitachi                 | 1         | 0.82%   |
| Acer                    | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 12        | 9.76%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch         | 6         | 4.88%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                    | 6         | 4.88%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch           | 5         | 4.07%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 3         | 2.44%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 3         | 2.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 2.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 2.44%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 2         | 1.63%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch         | 2         | 1.63%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                    | 2         | 1.63%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO133C 1366x768 309x173mm 13.9-inch            | 2         | 1.63%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                    | 1         | 0.81%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch                   | 1         | 0.81%   |
| Samsung Electronics S24D590 SAM0B46 1920x1080 521x293mm 23.5-inch        | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4754 1280x800 261x163mm 12.1-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 1         | 0.81%   |
| Samsung Electronics F27G3xTF SAM710E 1920x1080 600x330mm 27.0-inch       | 1         | 0.81%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch       | 1         | 0.81%   |
| PRM 35 PRM2733 1280x1024                                                 | 1         | 0.81%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch                  | 1         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.81%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 0.81%   |
| LG Display LP156WH3-TLA2 LGD0210 1366x768 345x194mm 15.6-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD05B5 1920x1080 382x215mm 17.3-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 0.81%   |
| KDC LCD Monitor KDC0002 1920x1080 309x174mm 14.0-inch                    | 1         | 0.81%   |
| Hitachi Projector HTC66E4 1680x1050 1200x900mm 59.1-inch                 | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch          | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1375 1920x1080 293x165mm 13.2-inch         | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 256x144mm 11.6-inch          | 1         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO1424 1280x800 303x190mm 14.1-inch | 1         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO1316 1366x768 296x166mm 13.4-inch | 1         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 1         | 0.81%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                    | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 77        | 65.25%  |
| 1366x768 (WXGA)  | 27        | 22.88%  |
| 1600x900 (HD+)   | 4         | 3.39%   |
| 1280x800 (WXGA)  | 4         | 3.39%   |
| 1440x900 (WXGA+) | 2         | 1.69%   |
| 1280x1024 (SXGA) | 2         | 1.69%   |
| 2560x1440 (QHD)  | 1         | 0.85%   |
| 1400x1050        | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 63        | 51.64%  |
| 14      | 19        | 15.57%  |
| 13      | 13        | 10.66%  |
| 17      | 12        | 9.84%   |
| 23      | 3         | 2.46%   |
| 19      | 3         | 2.46%   |
| 11      | 3         | 2.46%   |
| 27      | 2         | 1.64%   |
| 59      | 1         | 0.82%   |
| 24      | 1         | 0.82%   |
| 12      | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 74.59%  |
| 351-400     | 13        | 10.66%  |
| 201-300     | 8         | 6.56%   |
| 501-600     | 5         | 4.1%    |
| 401-500     | 2         | 1.64%   |
| 601-700     | 1         | 0.82%   |
| 1001-1500   | 1         | 0.82%   |
| Unknown     | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 108       | 92.31%  |
| 16/10 | 4         | 3.42%   |
| 3/2   | 2         | 1.71%   |
| 6/5   | 1         | 0.85%   |
| 5/4   | 1         | 0.85%   |
| 4/3   | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 51.64%  |
| 81-90          | 28        | 22.95%  |
| 121-130        | 12        | 9.84%   |
| 71-80          | 4         | 3.28%   |
| 201-250        | 4         | 3.28%   |
| 51-60          | 3         | 2.46%   |
| 151-200        | 3         | 2.46%   |
| 301-350        | 2         | 1.64%   |
| More than 1000 | 1         | 0.82%   |
| 61-70          | 1         | 0.82%   |
| Unknown        | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 79        | 65.29%  |
| 101-120 | 25        | 20.66%  |
| 51-100  | 12        | 9.92%   |
| 161-240 | 3         | 2.48%   |
| 1-50    | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 105       | 90.52%  |
| 2     | 9         | 7.76%   |
| 3     | 1         | 0.86%   |
| 0     | 1         | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 37.13%  |
| Realtek Semiconductor           | 58        | 34.73%  |
| Qualcomm Atheros                | 23        | 13.77%  |
| Broadcom                        | 9         | 5.39%   |
| D-Link                          | 5         | 2.99%   |
| Nvidia                          | 2         | 1.2%    |
| Ralink                          | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Micro Star International        | 1         | 0.6%    |
| MEDIATEK                        | 1         | 0.6%    |
| Marvell Technology Group        | 1         | 0.6%    |
| JMicron Technology              | 1         | 0.6%    |
| Broadcom Limited                | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 46        | 20.35%  |
| Intel Wireless 8265 / 8275                                              | 15        | 6.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 5.31%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 4.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 3.54%   |
| Intel Ethernet Connection (13) I219-V                                   | 7         | 3.1%    |
| Intel Ethernet Connection (10) I219-V                                   | 7         | 3.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 3.1%    |
| Intel Ethernet Connection (7) I219-LM                                   | 6         | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.77%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.33%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                | 3         | 1.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.33%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.88%   |
| Intel Wireless 7265                                                     | 2         | 0.88%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.88%   |
| Intel WiMAX Connection 2400m                                            | 2         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.88%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]            | 2         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.44%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.44%   |
| Nvidia MCP67 Ethernet                                                   | 1         | 0.44%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 0.44%   |
| Micro Star International RT2573                                         | 1         | 0.44%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.44%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.44%   |
| Intel Wireless 3165                                                     | 1         | 0.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.44%   |
| Intel PRO/100 VE Network Connection                                     | 1         | 0.44%   |
| Intel I210 Gigabit Network Connection                                   | 1         | 0.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 50.85%  |
| Realtek Semiconductor           | 24        | 20.34%  |
| Qualcomm Atheros                | 21        | 17.8%   |
| Broadcom                        | 8         | 6.78%   |
| Ralink                          | 1         | 0.85%   |
| Qualcomm Atheros Communications | 1         | 0.85%   |
| Micro Star International        | 1         | 0.85%   |
| MEDIATEK                        | 1         | 0.85%   |
| ASUSTek Computer                | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 15        | 12.4%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 9.92%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 8.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 6.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 5.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 4.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 4.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2.48%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 2.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 2.48%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.65%   |
| Intel Wireless 7265                                                     | 2         | 1.65%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 1.65%   |
| Intel WiMAX Connection 2400m                                            | 2         | 1.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.83%   |
| Micro Star International RT2573                                         | 1         | 0.83%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.83%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.83%   |
| Intel Wireless 3165                                                     | 1         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.83%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.83%   |
| Intel Centrino Wireless-N 105                                           | 1         | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.83%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.83%   |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 0.83%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 51        | 49.51%  |
| Intel                    | 31        | 30.1%   |
| Qualcomm Atheros         | 8         | 7.77%   |
| D-Link                   | 5         | 4.85%   |
| Broadcom                 | 3         | 2.91%   |
| Nvidia                   | 2         | 1.94%   |
| Marvell Technology Group | 1         | 0.97%   |
| JMicron Technology       | 1         | 0.97%   |
| Broadcom Limited         | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 43.81%  |
| Intel Ethernet Connection (13) I219-V                             | 7         | 6.67%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 6.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 5.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.76%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 3.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.86%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 3         | 2.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.9%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.9%    |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 2         | 1.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.95%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.95%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.95%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.95%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.95%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.95%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 52.78%  |
| Ethernet | 102       | 47.22%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 79.03%  |
| Ethernet | 26        | 20.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 96        | 84.21%  |
| 1     | 17        | 14.91%  |
| 3     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 94.74%  |
| Yes  | 6         | 5.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 60.44%  |
| Realtek Semiconductor           | 7         | 7.69%   |
| IMC Networks                    | 6         | 6.59%   |
| Lite-On Technology              | 5         | 5.49%   |
| Qualcomm Atheros Communications | 4         | 4.4%    |
| Broadcom                        | 3         | 3.3%    |
| Hewlett-Packard                 | 2         | 2.2%    |
| Foxconn / Hon Hai               | 2         | 2.2%    |
| ASUSTek Computer                | 2         | 2.2%    |
| Toshiba                         | 1         | 1.1%    |
| Realtek                         | 1         | 1.1%    |
| Ralink                          | 1         | 1.1%    |
| Chicony Electronics             | 1         | 1.1%    |
| Cambridge Silicon Radio         | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 20.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 18.68%  |
| Intel Bluetooth Device                              | 13        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 5.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.4%    |
| Realtek Bluetooth Radio                             | 3         | 3.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.3%    |
| Lite-On Bluetooth Device                            | 2         | 2.2%    |
| IMC Networks Bluetooth Device                       | 2         | 2.2%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 2.2%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 2.2%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.1%    |
| Realtek Bluetooth Radio                             | 1         | 1.1%    |
| Ralink RT3290 Bluetooth                             | 1         | 1.1%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.1%    |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.1%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.1%    |
| Lite-On Bluetooth Radio                             | 1         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.1%    |
| IMC Networks Wireless_Device                        | 1         | 1.1%    |
| IMC Networks Bluetooth Radio                        | 1         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.1%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.1%    |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 1.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.1%    |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.1%    |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.1%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.1%    |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.1%    |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 75.19%  |
| Nvidia                | 17        | 12.78%  |
| AMD                   | 12        | 9.02%   |
| C-Media Electronics   | 2         | 1.5%    |
| VIA Technologies      | 1         | 0.75%   |
| Realtek Semiconductor | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 17.24%  |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 10.34%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 7.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 5.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 4.83%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 4.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 4.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 3.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 2.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.07%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.38%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.38%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.69%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.69%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia Audio device                                                                               | 1         | 0.69%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.69%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.69%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.69%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 35        | 31.53%  |
| Samsung Electronics | 34        | 30.63%  |
| Unknown             | 9         | 8.11%   |
| Kingston            | 8         | 7.21%   |
| Crucial             | 8         | 7.21%   |
| Micron Technology   | 6         | 5.41%   |
| Elpida              | 3         | 2.7%    |
| A-DATA Technology   | 3         | 2.7%    |
| Ramaxel Technology  | 2         | 1.8%    |
| Foxline             | 2         | 1.8%    |
| SHARETRONIC         | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 13        | 11.4%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                    | 6         | 5.26%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                    | 5         | 4.39%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 5         | 4.39%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s        | 4         | 3.51%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s        | 4         | 3.51%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s          | 4         | 3.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 3         | 2.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2                           | 3         | 2.63%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 2.63%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 3         | 2.63%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 3         | 2.63%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.75%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s             | 2         | 1.75%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s           | 2         | 1.75%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s         | 2         | 1.75%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                    | 1         | 0.88%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                        | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2                              | 1         | 0.88%   |
| Unknown RAM Module 1024MB SODIMM DDR2 333MT/s                   | 1         | 0.88%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s       | 1         | 0.88%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s       | 1         | 0.88%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s          | 1         | 0.88%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s    | 1         | 0.88%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 0.88%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s       | 1         | 0.88%   |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1333MT/s                 | 1         | 0.88%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.88%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s        | 1         | 0.88%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s           | 1         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 0.88%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.88%   |
| Samsung RAM K4UBE3D4AA-MGCH 8192MB Row Of Chips LPDDR4 3200MT/s | 1         | 0.88%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s            | 1         | 0.88%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.88%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s       | 1         | 0.88%   |
| Micron RAM Module 4096MB Row Of Chips DDR4 2400MT/s             | 1         | 0.88%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 1         | 0.88%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s           | 1         | 0.88%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s           | 1         | 0.88%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s           | 1         | 0.88%   |
| Kingston RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 0.88%   |
| Kingston RAM CBD24D4S7S8ME-8 8192MB SODIMM DDR4 2400MT/s        | 1         | 0.88%   |
| Kingston RAM ACR16D3LS1KDG/2G 2GB SODIMM DDR3 1600MT/s          | 1         | 0.88%   |
| Kingston RAM 99U5469-078.A00LF 4GB SODIMM DDR3 1600MT/s         | 1         | 0.88%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s      | 1         | 0.88%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s         | 1         | 0.88%   |
| Kingston RAM 9905700-094.A00G 16GB SODIMM DDR4 2933MT/s         | 1         | 0.88%   |
| Elpida RAM EDJ4216EFBG-GNL-F 4GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s         | 1         | 0.88%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s         | 1         | 0.88%   |
| A-DATA RAM AO1P26KC4U1-BXOS 4096MB SODIMM DDR4 2667MT/s         | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 70.75%  |
| DDR3    | 20        | 18.87%  |
| DDR2    | 8         | 7.55%   |
| LPDDR4  | 2         | 1.89%   |
| Unknown | 1         | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 92.52%  |
| Row Of Chips | 8         | 7.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 51        | 46.36%  |
| 4096  | 39        | 35.45%  |
| 2048  | 11        | 10%     |
| 16384 | 7         | 6.36%   |
| 1024  | 1         | 0.91%   |
| 512   | 1         | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 41        | 36.61%  |
| 3200    | 17        | 15.18%  |
| 1600    | 15        | 13.39%  |
| 2133    | 12        | 10.71%  |
| 1334    | 6         | 5.36%   |
| 3266    | 4         | 3.57%   |
| 2400    | 4         | 3.57%   |
| Unknown | 4         | 3.57%   |
| 667     | 3         | 2.68%   |
| 1333    | 2         | 1.79%   |
| 4267    | 1         | 0.89%   |
| 2933    | 1         | 0.89%   |
| 800     | 1         | 0.89%   |
| 333     | 1         | 0.89%   |

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
| Chicony Electronics                    | 33        | 30.56%  |
| Cheng Uei Precision Industry (Foxlink) | 25        | 23.15%  |
| IMC Networks                           | 16        | 14.81%  |
| Sunplus Innovation Technology          | 6         | 5.56%   |
| Quanta                                 | 6         | 5.56%   |
| Suyin                                  | 4         | 3.7%    |
| Acer                                   | 4         | 3.7%    |
| Syntek                                 | 3         | 2.78%   |
| Realtek Semiconductor                  | 3         | 2.78%   |
| Z-Star Microelectronics                | 1         | 0.93%   |
| Unknown                                | 1         | 0.93%   |
| Sonix Technology                       | 1         | 0.93%   |
| Silicon Motion                         | 1         | 0.93%   |
| Primax Electronics                     | 1         | 0.93%   |
| Microdia                               | 1         | 0.93%   |
| Lite-On Technology                     | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 13.89%  |
| Chicony HP HD Camera                                           | 9         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 8         | 7.41%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 5.56%   |
| Chicony USB2.0 Camera                                          | 6         | 5.56%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 3.7%    |
| IMC Networks Integrated Camera                                 | 4         | 3.7%    |
| Quanta HP TrueVision HD Camera                                 | 3         | 2.78%   |
| Chicony Integrated Camera                                      | 3         | 2.78%   |
| Syntek Integrated Camera                                       | 2         | 1.85%   |
| Suyin 1.3M HD WebCam                                           | 2         | 1.85%   |
| Sunplus Asus Webcam                                            | 2         | 1.85%   |
| Chicony VGA Webcam                                             | 2         | 1.85%   |
| Chicony HD WebCam                                              | 2         | 1.85%   |
| Acer BisonCam, NB Pro                                          | 2         | 1.85%   |
| Z-Star Vega USB 2.0 Camera                                     | 1         | 0.93%   |
| Unknown USB2.0 Webcam                                          | 1         | 0.93%   |
| Syntek Lenovo EasyCamera                                       | 1         | 0.93%   |
| Suyin HP Truevision HD                                         | 1         | 0.93%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.93%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 0.93%   |
| Silicon Motion WebCam SC-0311139N                              | 1         | 0.93%   |
| Realtek Lenovo EasyCamera                                      | 1         | 0.93%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 0.93%   |
| Realtek EasyCamera                                             | 1         | 0.93%   |
| Quanta VGA WebCam                                              | 1         | 0.93%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 0.93%   |
| Quanta HP Webcam                                               | 1         | 0.93%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 0.93%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 0.93%   |
| Lite-On HP Webcam                                              | 1         | 0.93%   |
| IMC Networks VGA UVC WebCam                                    | 1         | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 0.93%   |
| IMC Networks USB 2.0 Camera                                    | 1         | 0.93%   |
| IMC Networks ov9734_azurewave_camera                           | 1         | 0.93%   |
| IMC Networks HP TrueVision HD Camera                           | 1         | 0.93%   |
| IMC Networks HD Camera                                         | 1         | 0.93%   |
| Chicony XiaoMi USB 2.0 Webcam                                  | 1         | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 0.93%   |
| Chicony USB camera                                             | 1         | 0.93%   |
| Chicony USB 2.0 Webcam Device                                  | 1         | 0.93%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 0.93%   |
| Chicony Lenovo EasyCamera                                      | 1         | 0.93%   |
| Chicony Integrated HP HD Webcam                                | 1         | 0.93%   |
| Chicony HP Wide Vision HD Camera                               | 1         | 0.93%   |
| Chicony HD User Facing                                         | 1         | 0.93%   |
| Chicony CNF7070 Webcam                                         | 1         | 0.93%   |
| Chicony 1.3M HD WebCam                                         | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 0.93%   |
| Alcor Micro Acer Integrated Webcam                             | 1         | 0.93%   |
| Acer EasyCamera                                                | 1         | 0.93%   |
| Acer BisonCam,NB Pro                                           | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 41.67%  |
| Elan Microelectronics      | 3         | 25%     |
| Synaptics                  | 2         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| LighTuning Technology      | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 16.67%  |
| Validity Sensors VFS491                           | 2         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 16.67%  |
| Elan ELAN:Fingerprint                             | 2         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 8.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 8.33%   |
| Elan ELAN:ARM-M4                                  | 1         | 8.33%   |

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
| 0     | 88        | 75.21%  |
| 1     | 21        | 17.95%  |
| 2     | 7         | 5.98%   |
| 3     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 12        | 35.29%  |
| Graphics card            | 8         | 23.53%  |
| Communication controller | 6         | 17.65%  |
| Chipcard                 | 3         | 8.82%   |
| Net/ethernet             | 2         | 5.88%   |
| Multimedia controller    | 1         | 2.94%   |
| Camera                   | 1         | 2.94%   |
| Bluetooth                | 1         | 2.94%   |

