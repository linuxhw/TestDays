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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Kometa P10         | 54        | 39.42%  |
| ALT Linux 9.1      | 22        | 16.06%  |
| ALT Linux 10.0     | 18        | 13.14%  |
| ALT Linux 9.2      | 10        | 7.3%    |
| ALT Linux 9.0      | 9         | 6.57%   |
| ALT Linux 10.1     | 3         | 2.19%   |
| MOS 10             | 2         | 1.46%   |
| ALT Linux P9       | 2         | 1.46%   |
| ALT Linux P8       | 2         | 1.46%   |
| ALT Linux 8.2      | 2         | 1.46%   |
| ALT Linux 20201124 | 2         | 1.46%   |
| ALT Linux 20191026 | 2         | 1.46%   |
| ALT Linux P10      | 1         | 0.73%   |
| ALT Linux 9        | 1         | 0.73%   |
| ALT Linux 8.990    | 1         | 0.73%   |
| ALT Linux 8.920    | 1         | 0.73%   |
| ALT Linux 8.3      | 1         | 0.73%   |
| ALT Linux 8.0.0    | 1         | 0.73%   |
| ALT Linux 20190624 | 1         | 0.73%   |
| ALT Linux 10.0.900 | 1         | 0.73%   |
| ALT Linux          | 1         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 129       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.102-std-def-alt1       | 36        | 24.83%  |
| 5.10.109-std-def-alt1       | 19        | 13.1%   |
| 5.10.88-std-def-alt1        | 6         | 4.14%   |
| 5.4.68-std-def-alt1.1       | 3         | 2.07%   |
| 5.4.28-std-def-alt1         | 3         | 2.07%   |
| 5.10.82-std-def-alt1        | 3         | 2.07%   |
| 5.4.62-std-def-alt1         | 2         | 1.38%   |
| 5.4.51-std-def-alt1         | 2         | 1.38%   |
| 5.15.34-un-def-alt1         | 2         | 1.38%   |
| 5.15.33-un-def-alt1         | 2         | 1.38%   |
| 5.15.25-un-def-alt1         | 2         | 1.38%   |
| 5.10.62-un-def-alt1         | 2         | 1.38%   |
| 5.10.61-un-def-alt1         | 2         | 1.38%   |
| 5.10.37-un-def-alt1         | 2         | 1.38%   |
| 5.10.32-un-def-alt1         | 2         | 1.38%   |
| 5.10.17-un-def-alt1         | 2         | 1.38%   |
| 5.10.113-std-def-alt1       | 2         | 1.38%   |
| 5.10.111-std-def-alt1       | 2         | 1.38%   |
| 4.19.79-std-def-alt1        | 2         | 1.38%   |
| 4.19.66-std-def-alt1        | 2         | 1.38%   |
| 4.19.102-std-def-alt1       | 2         | 1.38%   |
| 5.7.19-un-def-alt1          | 1         | 0.69%   |
| 5.4.98-std-def-alt1         | 1         | 0.69%   |
| 5.4.87-std-def-alt1         | 1         | 0.69%   |
| 5.4.85-std-def-alt1         | 1         | 0.69%   |
| 5.4.84-std-def-alt1         | 1         | 0.69%   |
| 5.4.44-std-def-alt1         | 1         | 0.69%   |
| 5.4.41-std-def-alt1         | 1         | 0.69%   |
| 5.4.3-un-def-alt1           | 1         | 0.69%   |
| 5.4.171-std-def-alt1        | 1         | 0.69%   |
| 5.4.144-std-def-alt1        | 1         | 0.69%   |
| 5.4.127-std-def-alt1        | 1         | 0.69%   |
| 5.4.117-std-def-alt1        | 1         | 0.69%   |
| 5.4.115-std-def-alt1        | 1         | 0.69%   |
| 5.4.107-std-def-alt1        | 1         | 0.69%   |
| 5.4.107-std-def-alt0.c9f    | 1         | 0.69%   |
| 5.3.5-un-def-alt1           | 1         | 0.69%   |
| 5.16.5-un-def-alt1          | 1         | 0.69%   |
| 5.15.37-un-def-alt1         | 1         | 0.69%   |
| 5.15.23-un-def-alt1         | 1         | 0.69%   |
| 5.15.15-un-def-alt1         | 1         | 0.69%   |
| 5.13.19-un-def-alt1         | 1         | 0.69%   |
| 5.13.15-un-def-alt1         | 1         | 0.69%   |
| 5.10.93-std-def-alt1        | 1         | 0.69%   |
| 5.10.92-std-def-alt1        | 1         | 0.69%   |
| 5.10.69-std-def-alt1        | 1         | 0.69%   |
| 5.10.54-std-def-alt2        | 1         | 0.69%   |
| 5.10.52-un-def-alt1         | 1         | 0.69%   |
| 5.10.40-un-def-alt1         | 1         | 0.69%   |
| 5.10.35-std-def-alt1        | 1         | 0.69%   |
| 5.10.29-un-def-alt2         | 1         | 0.69%   |
| 5.10.27-un-def-alt1         | 1         | 0.69%   |
| 5.10.118-un-def-alt1        | 1         | 0.69%   |
| 5.10.118-std-def-alt1       | 1         | 0.69%   |
| 5.10.117-std-def-alt1       | 1         | 0.69%   |
| 5.10.10-un-def-alt1         | 1         | 0.69%   |
| 4.9.35-un-def-alt0.M80P.1   | 1         | 0.69%   |
| 4.9.145-std-def-alt0.M80P.1 | 1         | 0.69%   |
| 4.9.133-std-def-alt0.M80P.1 | 1         | 0.69%   |
| 4.9.131-std-def-alt0.M80P.1 | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.102 | 36        | 24.83%  |
| 5.10.109 | 19        | 13.1%   |
| 5.10.88  | 6         | 4.14%   |
| 5.4.68   | 3         | 2.07%   |
| 5.4.28   | 3         | 2.07%   |
| 5.10.82  | 3         | 2.07%   |
| 5.4.62   | 2         | 1.38%   |
| 5.4.51   | 2         | 1.38%   |
| 5.4.107  | 2         | 1.38%   |
| 5.15.34  | 2         | 1.38%   |
| 5.15.33  | 2         | 1.38%   |
| 5.15.25  | 2         | 1.38%   |
| 5.10.62  | 2         | 1.38%   |
| 5.10.61  | 2         | 1.38%   |
| 5.10.37  | 2         | 1.38%   |
| 5.10.32  | 2         | 1.38%   |
| 5.10.17  | 2         | 1.38%   |
| 5.10.118 | 2         | 1.38%   |
| 5.10.113 | 2         | 1.38%   |
| 5.10.111 | 2         | 1.38%   |
| 4.19.79  | 2         | 1.38%   |
| 4.19.66  | 2         | 1.38%   |
| 4.19.102 | 2         | 1.38%   |
| 5.7.19   | 1         | 0.69%   |
| 5.4.98   | 1         | 0.69%   |
| 5.4.87   | 1         | 0.69%   |
| 5.4.85   | 1         | 0.69%   |
| 5.4.84   | 1         | 0.69%   |
| 5.4.44   | 1         | 0.69%   |
| 5.4.41   | 1         | 0.69%   |
| 5.4.3    | 1         | 0.69%   |
| 5.4.171  | 1         | 0.69%   |
| 5.4.144  | 1         | 0.69%   |
| 5.4.127  | 1         | 0.69%   |
| 5.4.117  | 1         | 0.69%   |
| 5.4.115  | 1         | 0.69%   |
| 5.3.5    | 1         | 0.69%   |
| 5.16.5   | 1         | 0.69%   |
| 5.15.37  | 1         | 0.69%   |
| 5.15.23  | 1         | 0.69%   |
| 5.15.15  | 1         | 0.69%   |
| 5.13.19  | 1         | 0.69%   |
| 5.13.15  | 1         | 0.69%   |
| 5.10.93  | 1         | 0.69%   |
| 5.10.92  | 1         | 0.69%   |
| 5.10.69  | 1         | 0.69%   |
| 5.10.54  | 1         | 0.69%   |
| 5.10.52  | 1         | 0.69%   |
| 5.10.40  | 1         | 0.69%   |
| 5.10.35  | 1         | 0.69%   |
| 5.10.29  | 1         | 0.69%   |
| 5.10.27  | 1         | 0.69%   |
| 5.10.117 | 1         | 0.69%   |
| 5.10.10  | 1         | 0.69%   |
| 4.9.35   | 1         | 0.69%   |
| 4.9.145  | 1         | 0.69%   |
| 4.9.133  | 1         | 0.69%   |
| 4.9.131  | 1         | 0.69%   |
| 4.4.12   | 1         | 0.69%   |
| 4.19.95  | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 88        | 64.71%  |
| 5.4     | 20        | 14.71%  |
| 4.19    | 11        | 8.09%   |
| 5.15    | 8         | 5.88%   |
| 4.9     | 3         | 2.21%   |
| 5.13    | 2         | 1.47%   |
| 5.7     | 1         | 0.74%   |
| 5.3     | 1         | 0.74%   |
| 5.16    | 1         | 0.74%   |
| 4.4     | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 122       | 94.57%  |
| i686   | 7         | 5.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 92        | 69.17%  |
| XFCE            | 15        | 11.28%  |
| Unknown         | 15        | 11.28%  |
| LXQt            | 4         | 3.01%   |
| GNOME           | 3         | 2.26%   |
| Cinnamon        | 3         | 2.26%   |
| GNOME Flashback | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 125       | 96.15%  |
| Wayland | 3         | 2.31%   |
| Tty     | 2         | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 80        | 60.15%  |
| LightDM | 24        | 18.05%  |
| TDM     | 22        | 16.54%  |
| Unknown | 5         | 3.76%   |
| XDM     | 1         | 0.75%   |
| GDM     | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 101       | 75.37%  |
| Unknown | 26        | 19.4%   |
| en_US   | 5         | 3.73%   |
| POSIX   | 1         | 0.75%   |
| C       | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 102       | 77.86%  |
| BIOS | 29        | 22.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 112       | 86.15%  |
| Overlay | 13        | 10%     |
| Btrfs   | 3         | 2.31%   |
| Unknown | 2         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 100       | 76.34%  |
| MBR     | 24        | 18.32%  |
| Unknown | 7         | 5.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 124       | 94.66%  |
| Yes       | 7         | 5.34%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 50%     |
| No        | 65        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 51        | 39.53%  |
| Lenovo              | 17        | 13.18%  |
| ASUSTek Computer    | 15        | 11.63%  |
| Acer                | 10        | 7.75%   |
| ICL                 | 9         | 6.98%   |
| Dell                | 6         | 4.65%   |
| Samsung Electronics | 3         | 2.33%   |
| MSI                 | 3         | 2.33%   |
| Apple               | 2         | 1.55%   |
| 3Logic Group        | 2         | 1.55%   |
| Toshiba             | 1         | 0.78%   |
| Timi                | 1         | 0.78%   |
| Sony                | 1         | 0.78%   |
| Panasonic           | 1         | 0.78%   |
| Kraftway            | 1         | 0.78%   |
| IP3 Technology      | 1         | 0.78%   |
| HUAWEI              | 1         | 0.78%   |
| eMachines           | 1         | 0.78%   |
| Durabook            | 1         | 0.78%   |
| DEPO Computers      | 1         | 0.78%   |
| Aquarius            | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HP 250 G7 Notebook PC                     | 12        | 9.3%    |
| HP ZBook 17 G5                            | 9         | 6.98%   |
| HP ProBook 440 G5                         | 8         | 6.2%    |
| ICL RAYbook Si1512                        | 6         | 4.65%   |
| HP EliteBook 840 G4                       | 3         | 2.33%   |
| HP 250 G6 Notebook PC                     | 3         | 2.33%   |
| Dell Latitude 3420                        | 3         | 2.33%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT      | 2         | 1.55%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 2         | 1.55%   |
| ICL NJ50_70CU                             | 2         | 1.55%   |
| HP EliteBook 8470p                        | 2         | 1.55%   |
| ASUS N46VZ                                | 2         | 1.55%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE | 2         | 1.55%   |
| Acer TravelMate 5760                      | 2         | 1.55%   |
| 3Logic Group Graviton N15i-K2             | 2         | 1.55%   |
| Unknown                                   | 2         | 1.55%   |
| Toshiba Satellite A100                    | 1         | 0.78%   |
| Timi TM1701                               | 1         | 0.78%   |
| Sony SVE1512H1RB                          | 1         | 0.78%   |
| Samsung RV413/RV513/E3413                 | 1         | 0.78%   |
| Samsung R510/P510                         | 1         | 0.78%   |
| Samsung 750XDA                            | 1         | 0.78%   |
| Panasonic CF-20-1                         | 1         | 0.78%   |
| MSI X300/X340/X400 series                 | 1         | 0.78%   |
| MSI MEGA BOOK S430                        | 1         | 0.78%   |
| MSI GE72 7RE                              | 1         | 0.78%   |
| Lenovo V510-15IKB 80WQ                    | 1         | 0.78%   |
| Lenovo V130-15IKB 81HN                    | 1         | 0.78%   |
| Lenovo ThinkPad X220 4291M85              | 1         | 0.78%   |
| Lenovo ThinkPad 13 2nd Gen 20J1S0EU00     | 1         | 0.78%   |
| Lenovo IdeaPad 5 15IIL05 81YK             | 1         | 0.78%   |
| Lenovo IdeaPad 310-15ISK 80SM             | 1         | 0.78%   |
| Lenovo IdeaPad 3 15IIL05 81WE             | 1         | 0.78%   |
| Lenovo IdeaPad 3 15IGL05 81WQ             | 1         | 0.78%   |
| Lenovo G570 20079                         | 1         | 0.78%   |
| Lenovo G505s 20255                        | 1         | 0.78%   |
| Lenovo B590 20206                         | 1         | 0.78%   |
| Lenovo B50-10 80QR                        | 1         | 0.78%   |
| Lenovo 3000 G430 4153/200                 | 1         | 0.78%   |
| Kraftway ACCORD                           | 1         | 0.78%   |
| IP3 APN23                                 | 1         | 0.78%   |
| HUAWEI NBLK-WAX9X                         | 1         | 0.78%   |
| HP ProBook 450 G3                         | 1         | 0.78%   |
| HP Pavilion Laptop 15-cc5xx               | 1         | 0.78%   |
| HP Pavilion Gaming Laptop 17-cd2xxx       | 1         | 0.78%   |
| HP Pavilion Gaming Laptop 17-cd1xxx       | 1         | 0.78%   |
| HP Pavilion Gaming Laptop 15-ec1xxx       | 1         | 0.78%   |
| HP Pavilion dv7                           | 1         | 0.78%   |
| HP Pavilion dv6700                        | 1         | 0.78%   |
| HP Laptop 17-by0xxx                       | 1         | 0.78%   |
| HP Laptop 15s-fq2xxx                      | 1         | 0.78%   |
| HP Laptop 15s-fq0xxx                      | 1         | 0.78%   |
| HP Laptop 14s-dq1xxx                      | 1         | 0.78%   |
| HP 255 G2                                 | 1         | 0.78%   |
| HP 250 G3                                 | 1         | 0.78%   |
| eMachines eME728                          | 1         | 0.78%   |
| Durabook Z14                              | 1         | 0.78%   |
| DEPO Computers DPC156                     | 1         | 0.78%   |
| Dell Latitude 3590                        | 1         | 0.78%   |
| Dell Inspiron 3542                        | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| HP 250                | 16        | 12.4%   |
| HP ZBook              | 9         | 6.98%   |
| HP ProBook            | 9         | 6.98%   |
| ICL RAYbook           | 6         | 4.65%   |
| HP Pavilion           | 6         | 4.65%   |
| Acer Aspire           | 6         | 4.65%   |
| HP EliteBook          | 5         | 3.88%   |
| Lenovo ThinkPad       | 4         | 3.1%    |
| Lenovo IdeaPad        | 4         | 3.1%    |
| HP Laptop             | 4         | 3.1%    |
| Dell Latitude         | 4         | 3.1%    |
| ASUS ASUS             | 4         | 3.1%    |
| ASUS VivoBook         | 3         | 2.33%   |
| Lenovo ThinkBook      | 2         | 1.55%   |
| ICL NJ50              | 2         | 1.55%   |
| ASUS N46VZ            | 2         | 1.55%   |
| Acer TravelMate       | 2         | 1.55%   |
| 3Logic Group Graviton | 2         | 1.55%   |
| Unknown               | 2         | 1.55%   |
| Toshiba Satellite     | 1         | 0.78%   |
| Timi TM1701           | 1         | 0.78%   |
| Sony SVE1512H1RB      | 1         | 0.78%   |
| Samsung RV413         | 1         | 0.78%   |
| Samsung R510          | 1         | 0.78%   |
| Samsung 750XDA        | 1         | 0.78%   |
| Panasonic CF-20-1     | 1         | 0.78%   |
| MSI X300              | 1         | 0.78%   |
| MSI MEGA              | 1         | 0.78%   |
| MSI GE72              | 1         | 0.78%   |
| Lenovo V510-15IKB     | 1         | 0.78%   |
| Lenovo V130-15IKB     | 1         | 0.78%   |
| Lenovo G570           | 1         | 0.78%   |
| Lenovo G505s          | 1         | 0.78%   |
| Lenovo B590           | 1         | 0.78%   |
| Lenovo B50-10         | 1         | 0.78%   |
| Lenovo 3000           | 1         | 0.78%   |
| Kraftway ACCORD       | 1         | 0.78%   |
| IP3 APN23             | 1         | 0.78%   |
| HUAWEI NBLK-WAX9X     | 1         | 0.78%   |
| HP 255                | 1         | 0.78%   |
| eMachines eME728      | 1         | 0.78%   |
| Durabook Z14          | 1         | 0.78%   |
| DEPO Computers DPC156 | 1         | 0.78%   |
| Dell Inspiron         | 1         | 0.78%   |
| Dell G3               | 1         | 0.78%   |
| ASUS ZenBook          | 1         | 0.78%   |
| ASUS X510UNR          | 1         | 0.78%   |
| ASUS X200MA           | 1         | 0.78%   |
| ASUS K52JT            | 1         | 0.78%   |
| ASUS 1101HA           | 1         | 0.78%   |
| ASUS 1001PXD          | 1         | 0.78%   |
| Aquarius NS585        | 1         | 0.78%   |
| Apple MacBookPro16    | 1         | 0.78%   |
| Apple MacBook7        | 1         | 0.78%   |
| Acer Swift            | 1         | 0.78%   |
| Acer NC-ES1-131-C1NL  | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 26        | 20.16%  |
| 2017 | 19        | 14.73%  |
| 2020 | 16        | 12.4%   |
| 2019 | 15        | 11.63%  |
| 2021 | 14        | 10.85%  |
| 2011 | 7         | 5.43%   |
| 2012 | 6         | 4.65%   |
| 2016 | 5         | 3.88%   |
| 2010 | 5         | 3.88%   |
| 2008 | 4         | 3.1%    |
| 2014 | 3         | 2.33%   |
| 2015 | 2         | 1.55%   |
| 2013 | 2         | 1.55%   |
| 2009 | 2         | 1.55%   |
| 2007 | 2         | 1.55%   |
| 2006 | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 129       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 109       | 82.58%  |
| Enabled  | 23        | 17.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 129       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 75        | 57.69%  |
| 3.01-4.0   | 25        | 19.23%  |
| 16.01-24.0 | 16        | 12.31%  |
| 1.01-2.0   | 7         | 5.38%   |
| 8.01-16.0  | 5         | 3.85%   |
| 2.01-3.0   | 2         | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 67        | 47.52%  |
| 2.01-3.0  | 25        | 17.73%  |
| 0.51-1.0  | 25        | 17.73%  |
| 3.01-4.0  | 12        | 8.51%   |
| 4.01-8.0  | 9         | 6.38%   |
| 0.01-0.5  | 2         | 1.42%   |
| 8.01-16.0 | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 75.94%  |
| 2      | 28        | 21.05%  |
| 0      | 2         | 1.5%    |
| 4      | 1         | 0.75%   |
| 3      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 61.07%  |
| Yes       | 51        | 38.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 90.7%   |
| No        | 12        | 9.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 80%     |
| No        | 26        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Russia     | 120       | 93.02%  |
| Greece     | 3         | 2.33%   |
| Uzbekistan | 1         | 0.78%   |
| Ukraine    | 1         | 0.78%   |
| Egypt      | 1         | 0.78%   |
| Czechia    | 1         | 0.78%   |
| Costa Rica | 1         | 0.78%   |
| Belarus    | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 84        | 63.16%  |
| St Petersburg     | 5         | 3.76%   |
| Barnaul           | 4         | 3.01%   |
| Samara            | 3         | 2.26%   |
| Perm              | 2         | 1.5%    |
| Korolyov          | 2         | 1.5%    |
| Belgorod          | 2         | 1.5%    |
| Astrakhan         | 2         | 1.5%    |
| Yekaterinburg     | 1         | 0.75%   |
| Verkhnyaya Pyshma | 1         | 0.75%   |
| Vergina           | 1         | 0.75%   |
| Troitsk           | 1         | 0.75%   |
| Thessaloniki      | 1         | 0.75%   |
| Tashkent          | 1         | 0.75%   |
| Surgut            | 1         | 0.75%   |
| Suez              | 1         | 0.75%   |
| Sevastopol        | 1         | 0.75%   |
| Saratov           | 1         | 0.75%   |
| San José         | 1         | 0.75%   |
| Prague            | 1         | 0.75%   |
| Omsk              | 1         | 0.75%   |
| Obninsk           | 1         | 0.75%   |
| Novosibirsk       | 1         | 0.75%   |
| Novichikha        | 1         | 0.75%   |
| Nizhny Tagil      | 1         | 0.75%   |
| Lesosibirsk       | 1         | 0.75%   |
| Krasnoyarsk       | 1         | 0.75%   |
| Kostroma          | 1         | 0.75%   |
| Kirov             | 1         | 0.75%   |
| Khabarovsk        | 1         | 0.75%   |
| Kemerovo          | 1         | 0.75%   |
| Kazan’          | 1         | 0.75%   |
| Kaliningrad       | 1         | 0.75%   |
| Hurghada          | 1         | 0.75%   |
| Fedorovka         | 1         | 0.75%   |
| Edessa            | 1         | 0.75%   |
| Bratsk            | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 29     | 15.38%  |
| Samsung Electronics | 22        | 29     | 14.1%   |
| Intel               | 21        | 24     | 13.46%  |
| SK hynix            | 18        | 18     | 11.54%  |
| WDC                 | 17        | 21     | 10.9%   |
| Toshiba             | 8         | 12     | 5.13%   |
| Foxline             | 8         | 8      | 5.13%   |
| Hitachi             | 5         | 5      | 3.21%   |
| Kingston            | 4         | 4      | 2.56%   |
| HGST                | 4         | 4      | 2.56%   |
| A-DATA Technology   | 3         | 3      | 1.92%   |
| Unknown             | 2         | 2      | 1.28%   |
| SSSTC               | 2         | 2      | 1.28%   |
| SanDisk             | 2         | 2      | 1.28%   |
| Gigabyte Technology | 2         | 2      | 1.28%   |
| Fujitsu             | 2         | 2      | 1.28%   |
| Crucial             | 2         | 2      | 1.28%   |
| XPG                 | 1         | 2      | 0.64%   |
| Transcend           | 1         | 1      | 0.64%   |
| PNY                 | 1         | 1      | 0.64%   |
| Plextor             | 1         | 1      | 0.64%   |
| KingDian            | 1         | 1      | 0.64%   |
| BaseTech            | 1         | 1      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |
| Apacer              | 1         | 1      | 0.64%   |
| AMD                 | 1         | 1      | 0.64%   |
| Unknown             | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SK hynix BC501 HFM256GDJTNG-8310A 256GB   | 12        | 7.45%   |
| Seagate ST1000LM049-2GH172 1TB            | 8         | 4.97%   |
| Intel SSDPEMKF256G8H 256GB                | 8         | 4.97%   |
| Intel SSDPEKKF256G7H 256GB                | 8         | 4.97%   |
| Foxline FLSSD256M80E13TCX5 256GB          | 8         | 4.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 4         | 2.48%   |
| Samsung MZALQ256HAJD-000L2 256GB          | 4         | 2.48%   |
| WDC WD5000LPLX-60ZNTT2 500GB              | 2         | 1.24%   |
| WDC WD3200BPVT-22JJ5T0 320GB              | 2         | 1.24%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.24%   |
| Toshiba KXG50ZNV256G 256GB                | 2         | 1.24%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB            | 2         | 1.24%   |
| Seagate ST9250315AS 250GB                 | 2         | 1.24%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 1.24%   |
| Samsung SSD 860 EVO M.2 250GB             | 2         | 1.24%   |
| Samsung SSD 860 EVO 250GB                 | 2         | 1.24%   |
| Samsung NVMe SSD Drive 512GB              | 2         | 1.24%   |
| Intel SSDPEKNW512G8H 512GB                | 2         | 1.24%   |
| HGST HTS721010A9E630 1TB                  | 2         | 1.24%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 2         | 1.24%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 1.24%   |
| XPG NVMe SSD Drive 256GB                  | 1         | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 0.62%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 1         | 0.62%   |
| WDC WDS100T2B0B-00YS70 1TB SSD            | 1         | 0.62%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.62%   |
| WDC WD5000LPVX-80V0TT0 500GB              | 1         | 0.62%   |
| WDC WD5000LPVX-60V0TT0 500GB              | 1         | 0.62%   |
| WDC WD5000LPLX-60ZNTT1 500GB              | 1         | 0.62%   |
| WDC WD5000LPCX-24VHAT0 500GB              | 1         | 0.62%   |
| WDC WD3200BEVT-22A23T0 320GB              | 1         | 0.62%   |
| WDC WD1600BEVS-22RST0 160GB               | 1         | 0.62%   |
| WDC WD1200BEVS-60UST0 120GB               | 1         | 0.62%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB      | 1         | 0.62%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB      | 1         | 0.62%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 1         | 0.62%   |
| Unknown USDU1  32GB                       | 1         | 0.62%   |
| Unknown SDC  8GB                          | 1         | 0.62%   |
| Transcend TS240GSSD220S 240GB             | 1         | 0.62%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.62%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 0.62%   |
| Toshiba MK6465GSX 640GB                   | 1         | 0.62%   |
| Toshiba MK2576GSX 250GB                   | 1         | 0.62%   |
| Toshiba HDWL110 1TB                       | 1         | 0.62%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 0.62%   |
| SK hynix SC311 SATA 128GB SSD             | 1         | 0.62%   |
| SK hynix HFS128G39TND-N210A 128GB SSD     | 1         | 0.62%   |
| SK hynix HFM256GDJTNG-8310A 256GB         | 1         | 0.62%   |
| SK hynix HBG4e  32GB                      | 1         | 0.62%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB   | 1         | 0.62%   |
| Seagate ST9640320AS 640GB                 | 1         | 0.62%   |
| Seagate ST9500325AS 500GB                 | 1         | 0.62%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 0.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 0.62%   |
| Seagate ST2000LM007-1R8174 2TB            | 1         | 0.62%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 0.62%   |
| Seagate Expansion 1TB                     | 1         | 0.62%   |
| Seagate BUP Slim SL 1TB                   | 1         | 0.62%   |
| SanDisk SD8SN8U128G1002 128GB SSD         | 1         | 0.62%   |
| SanDisk NVMe SSD Drive 512GB              | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 24        | 29     | 46.15%  |
| WDC     | 11        | 12     | 21.15%  |
| Toshiba | 6         | 10     | 11.54%  |
| Hitachi | 5         | 5      | 9.62%   |
| HGST    | 4         | 4      | 7.69%   |
| Fujitsu | 2         | 2      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 27.59%  |
| WDC                 | 3         | 6      | 10.34%  |
| SK hynix            | 2         | 2      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| Crucial             | 2         | 2      | 6.9%    |
| A-DATA Technology   | 2         | 2      | 6.9%    |
| Transcend           | 1         | 1      | 3.45%   |
| SanDisk             | 1         | 1      | 3.45%   |
| PNY                 | 1         | 1      | 3.45%   |
| Plextor             | 1         | 1      | 3.45%   |
| KingDian            | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Foxline             | 1         | 1      | 3.45%   |
| BaseTech            | 1         | 1      | 3.45%   |
| AMD                 | 1         | 1      | 3.45%   |
| Unknown             | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 83     | 46.05%  |
| HDD  | 51        | 62     | 33.55%  |
| SSD  | 28        | 32     | 18.42%  |
| MMC  | 3         | 3      | 1.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 83     | 48.28%  |
| SATA | 69        | 91     | 47.59%  |
| SAS  | 3         | 3      | 2.07%   |
| MMC  | 3         | 3      | 2.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 57     | 64.47%  |
| 0.51-1.0   | 26        | 36     | 34.21%  |
| 1.01-2.0   | 1         | 1      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 70        | 51.85%  |
| 251-500    | 24        | 17.78%  |
| 51-100     | 17        | 12.59%  |
| 21-50      | 8         | 5.93%   |
| 1-20       | 7         | 5.19%   |
| 501-1000   | 6         | 4.44%   |
| 1001-2000  | 3         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 85        | 61.59%  |
| 21-50    | 25        | 18.12%  |
| 101-250  | 12        | 8.7%    |
| 51-100   | 9         | 6.52%   |
| 251-500  | 5         | 3.62%   |
| 501-1000 | 2         | 1.45%   |

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
| Works    | 110       | 140    | 80.88%  |
| Malfunc  | 16        | 21     | 11.76%  |
| Detected | 10        | 19     | 7.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 105       | 61.05%  |
| SK hynix                       | 15        | 8.72%   |
| Samsung Electronics            | 15        | 8.72%   |
| AMD                            | 11        | 6.4%    |
| Phison Electronics             | 9         | 5.23%   |
| SanDisk                        | 4         | 2.33%   |
| Nvidia                         | 3         | 1.74%   |
| Toshiba America Info Systems   | 2         | 1.16%   |
| Solid State Storage Technology | 2         | 1.16%   |
| Kingston Technology Company    | 2         | 1.16%   |
| VIA Technologies               | 1         | 0.58%   |
| Shenzhen Longsys Electronics   | 1         | 0.58%   |
| Apple                          | 1         | 0.58%   |
| ADATA Technology               | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 23        | 11.44%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 8.46%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 13        | 6.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 10        | 4.98%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 4.98%   |
| Samsung NVMe SSD Controller 980                                                        | 9         | 4.48%   |
| Phison PS5013 E13 NVMe Controller                                                      | 9         | 4.48%   |
| Intel SSD 600P Series                                                                  | 9         | 4.48%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 8         | 3.98%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 8         | 3.98%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 8         | 3.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 3.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 2.99%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 6         | 2.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 2.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 1.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.49%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 1%      |
| Solid State Storage Non-Volatile memory controller                                     | 2         | 1%      |
| SK hynix BC511                                                                         | 2         | 1%      |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 1%      |
| Intel SSD 660P Series                                                                  | 2         | 1%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 1%      |
| VIA VT8237/8251 Serial ATA Controller                                                  | 1         | 0.5%    |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                       | 1         | 0.5%    |
| Nvidia MCP89 SATA Controller                                                           | 1         | 0.5%    |
| Nvidia MCP67 IDE Controller                                                            | 1         | 0.5%    |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 0.5%    |
| Nvidia MCP51 Serial ATA Controller                                                     | 1         | 0.5%    |
| Nvidia MCP51 IDE                                                                       | 1         | 0.5%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.5%    |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.5%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 0.5%    |
| Intel Non-Volatile memory controller                                                   | 1         | 0.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 0.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 0.5%    |
| Intel Atom Processor E3800 Series SATA IDE Controller                                  | 1         | 0.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.5%    |
| Apple ANS2 NVMe Controller                                                             | 1         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.5%    |
| AMD FCH IDE Controller                                                                 | 1         | 0.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 94        | 47.96%  |
| NVMe | 70        | 35.71%  |
| RAID | 23        | 11.73%  |
| IDE  | 9         | 4.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 113       | 87.6%   |
| AMD          | 15        | 11.63%  |
| CentaurHauls | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 10.08%  |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 7.75%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 6.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 6.2%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 6.2%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 4.65%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 4         | 3.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 3.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.33%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.55%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.55%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.55%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.55%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.55%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.78%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.78%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.78%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.78%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.78%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.78%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.78%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 1         | 0.78%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.78%   |
| Intel Core i5-1038NG7 CPU @ 2.00GHz           | 1         | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.78%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.78%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 0.78%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 0.78%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 0.78%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 0.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 0.78%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 0.78%   |
| Intel Core Duo CPU T2250 @ 1.73GHz            | 1         | 0.78%   |
| Intel Core 2 Solo CPU U3500 @ 1.40GHz         | 1         | 0.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 0.78%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 0.78%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 0.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 0.78%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 0.78%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 0.78%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 0.78%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 0.78%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 0.78%   |
| CentaurHauls VIA C7-M Processor 1600MHz       | 1         | 0.78%   |
| AMD Turion 64 X2 Mobile Technology TL-58      | 1         | 0.78%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 0.78%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 0.78%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 1         | 0.78%   |
| AMD E-450 APU with Radeon HD Graphics         | 1         | 0.78%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-57    | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 32.56%  |
| Intel Core i3           | 26        | 20.16%  |
| Intel Core i7           | 16        | 12.4%   |
| Other                   | 11        | 8.53%   |
| Intel Celeron           | 4         | 3.1%    |
| AMD Ryzen 7             | 4         | 3.1%    |
| AMD Ryzen 5             | 4         | 3.1%    |
| Intel Pentium Silver    | 2         | 1.55%   |
| Intel Pentium Gold      | 2         | 1.55%   |
| Intel Core 2 Duo        | 2         | 1.55%   |
| Intel Atom              | 2         | 1.55%   |
| AMD A8                  | 2         | 1.55%   |
| Intel Pentium Dual-Core | 1         | 0.78%   |
| Intel Pentium           | 1         | 0.78%   |
| Intel Core m5           | 1         | 0.78%   |
| Intel Core Duo          | 1         | 0.78%   |
| Intel Core 2 Solo       | 1         | 0.78%   |
| Intel Celeron Dual-Core | 1         | 0.78%   |
| CentaurHauls VIA C7     | 1         | 0.78%   |
| AMD Turion 64 X2 Mobile | 1         | 0.78%   |
| AMD E1                  | 1         | 0.78%   |
| AMD E                   | 1         | 0.78%   |
| AMD Athlon 64 X2        | 1         | 0.78%   |
| AMD A6                  | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 44.19%  |
| 4      | 54        | 41.86%  |
| 6      | 11        | 8.53%   |
| 1      | 4         | 3.1%    |
| 8      | 3         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 129       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 108       | 83.72%  |
| 1      | 21        | 16.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 125       | 96.9%   |
| 32-bit         | 3         | 2.33%   |
| Unknown        | 1         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806e9    | 15        | 11.54%  |
| Unknown    | 15        | 11.54%  |
| 0x906ea    | 11        | 8.46%   |
| 0x806ec    | 11        | 8.46%   |
| 0x806ea    | 10        | 7.69%   |
| 0x806c1    | 10        | 7.69%   |
| 0xa0660    | 8         | 6.15%   |
| 0x306a9    | 6         | 4.62%   |
| 0x706e5    | 5         | 3.85%   |
| 0x406e3    | 4         | 3.08%   |
| 0x206a7    | 4         | 3.08%   |
| 0x1067a    | 4         | 3.08%   |
| 0x08600106 | 3         | 2.31%   |
| 0x08108109 | 3         | 2.31%   |
| 0x706a8    | 2         | 1.54%   |
| 0x40651    | 2         | 1.54%   |
| 0x30678    | 2         | 1.54%   |
| 0xa0652    | 1         | 0.77%   |
| 0x706a1    | 1         | 0.77%   |
| 0x6ec      | 1         | 0.77%   |
| 0x406c3    | 1         | 0.77%   |
| 0x20655    | 1         | 0.77%   |
| 0x20652    | 1         | 0.77%   |
| 0x106ca    | 1         | 0.77%   |
| 0x106c2    | 1         | 0.77%   |
| 0x10676    | 1         | 0.77%   |
| 0x08600104 | 1         | 0.77%   |
| 0x08108102 | 1         | 0.77%   |
| 0x07030105 | 1         | 0.77%   |
| 0x0700010f | 1         | 0.77%   |
| 0x06001119 | 1         | 0.77%   |
| 0x0300000f | 1         | 0.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 53        | 41.09%  |
| TigerLake     | 12        | 9.3%    |
| CometLake     | 9         | 6.98%   |
| SandyBridge   | 6         | 4.65%   |
| IvyBridge     | 6         | 4.65%   |
| Penryn        | 5         | 3.88%   |
| IceLake       | 5         | 3.88%   |
| Zen+          | 4         | 3.1%    |
| Zen 2         | 4         | 3.1%    |
| Skylake       | 4         | 3.1%    |
| Silvermont    | 3         | 2.33%   |
| Goldmont plus | 3         | 2.33%   |
| Westmere      | 2         | 1.55%   |
| K8 Hammer     | 2         | 1.55%   |
| Haswell       | 2         | 1.55%   |
| Bonnell       | 2         | 1.55%   |
| Puma          | 1         | 0.78%   |
| Piledriver    | 1         | 0.78%   |
| P6            | 1         | 0.78%   |
| K10 Llano     | 1         | 0.78%   |
| Jaguar        | 1         | 0.78%   |
| Bobcat        | 1         | 0.78%   |
| Unknown       | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 108       | 69.68%  |
| Nvidia           | 31        | 20%     |
| AMD              | 15        | 9.68%   |
| VIA Technologies | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 19        | 12.03%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 8.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 6.33%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 9         | 5.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 5.7%    |
| Intel Comet Lake UHD Graphics                                                            | 8         | 5.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 3.8%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 5         | 3.16%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.53%   |
| AMD Renoir                                                                               | 4         | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.53%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 1.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.27%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.27%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.27%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.27%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                    | 2         | 1.27%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.63%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.63%   |
| Nvidia TU117M                                                                            | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.63%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.63%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.63%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.63%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.63%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.63%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 0.63%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 0.63%   |
| Nvidia C51 [GeForce Go 6100]                                                             | 1         | 0.63%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 0.63%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.63%   |
| Intel HD Graphics 630                                                                    | 1         | 0.63%   |
| Intel HD Graphics 520                                                                    | 1         | 0.63%   |
| Intel HD Graphics 515                                                                    | 1         | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.63%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.63%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.63%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.63%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.63%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 0.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 0.63%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.63%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 85        | 65.89%  |
| Intel + Nvidia | 22        | 17.05%  |
| 1 x AMD        | 9         | 6.98%   |
| 1 x Nvidia     | 6         | 4.65%   |
| AMD + Nvidia   | 3         | 2.33%   |
| 2 x AMD        | 2         | 1.55%   |
| 1 x VIA        | 1         | 0.78%   |
| Intel + AMD    | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 118       | 90.08%  |
| Proprietary | 10        | 7.63%   |
| Unknown     | 3         | 2.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 99        | 75.57%  |
| 3.01-4.0   | 10        | 7.63%   |
| 0.01-0.5   | 10        | 7.63%   |
| 0.51-1.0   | 7         | 5.34%   |
| 1.01-2.0   | 5         | 3.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 36        | 26.28%  |
| Chimei Innolux          | 27        | 19.71%  |
| AU Optronics            | 24        | 17.52%  |
| LG Display              | 15        | 10.95%  |
| Samsung Electronics     | 10        | 7.3%    |
| Chi Mei Optoelectronics | 5         | 3.65%   |
| Sharp                   | 4         | 2.92%   |
| PANDA                   | 4         | 2.92%   |
| BenQ                    | 2         | 1.46%   |
| Apple                   | 2         | 1.46%   |
| AOC                     | 2         | 1.46%   |
| STA                     | 1         | 0.73%   |
| PRM                     | 1         | 0.73%   |
| Panasonic               | 1         | 0.73%   |
| KDC                     | 1         | 0.73%   |
| Hitachi                 | 1         | 0.73%   |
| Acer                    | 1         | 0.73%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 12        | 8.7%    |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch         | 9         | 6.52%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                    | 6         | 4.35%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch           | 5         | 3.62%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                  | 3         | 2.17%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 3         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 2.17%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 2.17%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 2.17%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 2         | 1.45%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch         | 2         | 1.45%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                    | 2         | 1.45%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO133C 1366x768 309x173mm 13.9-inch            | 2         | 1.45%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                    | 1         | 0.72%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch                   | 1         | 0.72%   |
| Samsung Electronics S24D590 SAM0B46 1920x1080 521x293mm 23.5-inch        | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4754 1280x800 261x163mm 12.1-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 261x163mm 12.1-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 1         | 0.72%   |
| Samsung Electronics F27G3xTF SAM710E 1920x1080 600x330mm 27.0-inch       | 1         | 0.72%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch       | 1         | 0.72%   |
| PRM 35 PRM2733 1280x1024                                                 | 1         | 0.72%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 1         | 0.72%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch                  | 1         | 0.72%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.72%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 0.72%   |
| Panasonic LCD Monitor YLT4100 1920x1200 216x135mm 10.0-inch              | 1         | 0.72%   |
| LG Display LP156WH3-TLA2 LGD0210 1366x768 345x194mm 15.6-inch            | 1         | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD05B5 1920x1080 382x215mm 17.3-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch             | 1         | 0.72%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 1         | 0.72%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 0.72%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 0.72%   |
| KDC LCD Monitor KDC0002 1920x1080 309x174mm 14.0-inch                    | 1         | 0.72%   |
| Hitachi Projector HTC66E4 1680x1050 1200x900mm 59.1-inch                 | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch          | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1375 1920x1080 293x165mm 13.2-inch         | 1         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 256x144mm 11.6-inch          | 1         | 0.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 0.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 87        | 65.41%  |
| 1366x768 (WXGA)   | 29        | 21.8%   |
| 1280x800 (WXGA)   | 5         | 3.76%   |
| 1600x900 (HD+)    | 4         | 3.01%   |
| 1440x900 (WXGA+)  | 2         | 1.5%    |
| 1280x1024 (SXGA)  | 2         | 1.5%    |
| 2560x1600         | 1         | 0.75%   |
| 2560x1440 (QHD)   | 1         | 0.75%   |
| 1920x1200 (WUXGA) | 1         | 0.75%   |
| 1400x1050         | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 71        | 51.82%  |
| 14      | 19        | 13.87%  |
| 17      | 16        | 11.68%  |
| 13      | 15        | 10.95%  |
| 23      | 3         | 2.19%   |
| 19      | 3         | 2.19%   |
| 11      | 3         | 2.19%   |
| 27      | 2         | 1.46%   |
| 59      | 1         | 0.73%   |
| 24      | 1         | 0.73%   |
| 12      | 1         | 0.73%   |
| 10      | 1         | 0.73%   |
| Unknown | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 72.26%  |
| 351-400     | 17        | 12.41%  |
| 201-300     | 11        | 8.03%   |
| 501-600     | 5         | 3.65%   |
| 401-500     | 2         | 1.46%   |
| 601-700     | 1         | 0.73%   |
| 1001-1500   | 1         | 0.73%   |
| Unknown     | 1         | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 120       | 90.91%  |
| 16/10 | 7         | 5.3%    |
| 3/2   | 2         | 1.52%   |
| 6/5   | 1         | 0.76%   |
| 5/4   | 1         | 0.76%   |
| 4/3   | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 51.82%  |
| 81-90          | 29        | 21.17%  |
| 121-130        | 16        | 11.68%  |
| 71-80          | 5         | 3.65%   |
| 201-250        | 4         | 2.92%   |
| 51-60          | 3         | 2.19%   |
| 151-200        | 3         | 2.19%   |
| 301-350        | 2         | 1.46%   |
| More than 1000 | 1         | 0.73%   |
| 61-70          | 1         | 0.73%   |
| 41-50          | 1         | 0.73%   |
| Unknown        | 1         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 89        | 65.44%  |
| 101-120 | 28        | 20.59%  |
| 51-100  | 12        | 8.82%   |
| 161-240 | 5         | 3.68%   |
| 1-50    | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 120       | 91.6%   |
| 2     | 9         | 6.87%   |
| 3     | 1         | 0.76%   |
| 0     | 1         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 37.7%   |
| Realtek Semiconductor           | 65        | 34.03%  |
| Qualcomm Atheros                | 24        | 12.57%  |
| Broadcom                        | 12        | 6.28%   |
| D-Link                          | 6         | 3.14%   |
| Nvidia                          | 3         | 1.57%   |
| Sierra Wireless                 | 1         | 0.52%   |
| Ralink                          | 1         | 0.52%   |
| Qualcomm Atheros Communications | 1         | 0.52%   |
| Micro Star International        | 1         | 0.52%   |
| MediaTek                        | 1         | 0.52%   |
| Marvell Technology Group        | 1         | 0.52%   |
| JMicron Technology              | 1         | 0.52%   |
| Broadcom Limited                | 1         | 0.52%   |
| ASUSTek Computer                | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 51        | 19.77%  |
| Intel Wireless 8265 / 8275                                              | 15        | 5.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 4.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 4.26%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.88%   |
| Intel Ethernet Connection (7) I219-LM                                   | 9         | 3.49%   |
| Intel Ethernet Connection (10) I219-V                                   | 8         | 3.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 3.1%    |
| Intel Ethernet Connection (13) I219-V                                   | 7         | 2.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.55%   |
| Intel Wireless 7265                                                     | 4         | 1.55%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 1.55%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.55%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                | 4         | 1.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.16%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.78%   |
| Intel Wireless 3165                                                     | 2         | 0.78%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.78%   |
| Intel WiMAX Connection 2400m                                            | 2         | 0.78%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.78%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]            | 2         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.78%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.39%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.39%   |
| Realtek Realtek Network controller                                      | 1         | 0.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.39%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.39%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 1         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.39%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 0.39%   |
| Nvidia MCP67 Ethernet                                                   | 1         | 0.39%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 0.39%   |
| Micro Star International RT2573                                         | 1         | 0.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.39%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 52.24%  |
| Realtek Semiconductor           | 25        | 18.66%  |
| Qualcomm Atheros                | 22        | 16.42%  |
| Broadcom                        | 11        | 8.21%   |
| Sierra Wireless                 | 1         | 0.75%   |
| Ralink                          | 1         | 0.75%   |
| Qualcomm Atheros Communications | 1         | 0.75%   |
| Micro Star International        | 1         | 0.75%   |
| MediaTek                        | 1         | 0.75%   |
| ASUSTek Computer                | 1         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 15        | 11.11%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 8.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 8.15%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 7.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 5.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.96%   |
| Intel Wireless 7265                                                     | 4         | 2.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 2.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 2.22%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.48%   |
| Intel Wireless 3165                                                     | 2         | 1.48%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 1.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.48%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.74%   |
| Realtek Realtek Network controller                                      | 1         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.74%   |
| Micro Star International RT2573                                         | 1         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.74%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.74%   |
| Intel Wireless 8260                                                     | 1         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.74%   |
| Intel Centrino Wireless-N 105                                           | 1         | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.74%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 0.74%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 0.74%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.74%   |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 0.74%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 47.93%  |
| Intel                    | 40        | 33.06%  |
| Qualcomm Atheros         | 8         | 6.61%   |
| D-Link                   | 6         | 4.96%   |
| Nvidia                   | 3         | 2.48%   |
| Broadcom                 | 3         | 2.48%   |
| Marvell Technology Group | 1         | 0.83%   |
| JMicron Technology       | 1         | 0.83%   |
| Broadcom Limited         | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 41.46%  |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 7.32%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 6.5%    |
| Intel Ethernet Connection (13) I219-V                             | 7         | 5.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.07%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 3.25%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 3.25%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.63%   |
| Intel WiMAX Connection 2400m                                      | 2         | 1.63%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.63%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 2         | 1.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.81%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.81%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.81%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.81%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.81%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.81%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 52.44%  |
| Ethernet | 117       | 47.56%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 80%     |
| Ethernet | 27        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 110       | 85.27%  |
| 1     | 18        | 13.95%  |
| 3     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 123       | 95.35%  |
| Yes  | 6         | 4.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 61.9%   |
| Realtek Semiconductor           | 8         | 7.62%   |
| IMC Networks                    | 6         | 5.71%   |
| Lite-On Technology              | 5         | 4.76%   |
| Qualcomm Atheros Communications | 4         | 3.81%   |
| Broadcom                        | 4         | 3.81%   |
| Foxconn / Hon Hai               | 3         | 2.86%   |
| Hewlett-Packard                 | 2         | 1.9%    |
| ASUSTek Computer                | 2         | 1.9%    |
| Toshiba                         | 1         | 0.95%   |
| Realtek                         | 1         | 0.95%   |
| Ralink                          | 1         | 0.95%   |
| Chicony Electronics             | 1         | 0.95%   |
| Cambridge Silicon Radio         | 1         | 0.95%   |
| Apple                           | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 24        | 22.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 20.95%  |
| Intel Bluetooth Device                              | 13        | 12.38%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.81%   |
| Realtek Bluetooth Radio                             | 4         | 3.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.86%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 2.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.9%    |
| IMC Networks Bluetooth Device                       | 2         | 1.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.9%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.95%   |
| Realtek Bluetooth Radio                             | 1         | 0.95%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.95%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.95%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.95%   |
| Lite-On Bluetooth Radio                             | 1         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.95%   |
| IMC Networks Wireless_Device                        | 1         | 0.95%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.95%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.95%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.95%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.95%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.95%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.95%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.95%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.95%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 0.95%   |
| Apple Bluetooth Host Controller                     | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 112       | 73.68%  |
| Nvidia                | 21        | 13.82%  |
| AMD                   | 14        | 9.21%   |
| C-Media Electronics   | 2         | 1.32%   |
| VIA Technologies      | 1         | 0.66%   |
| Realtek Semiconductor | 1         | 0.66%   |
| Apple                 | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 16.27%  |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 10.84%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 7.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 6.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 5.42%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 4.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 4.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 3.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 2.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.41%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.2%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.2%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.6%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia Audio device                                                                               | 1         | 0.6%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.6%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.6%    |
| Intel Audio device                                                                                | 1         | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.6%    |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.6%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.6%    |
| Apple Audio Device                                                                                | 1         | 0.6%    |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.6%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.6%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 31.2%   |
| SK hynix            | 35        | 28%     |
| Unknown             | 10        | 8%      |
| Crucial             | 10        | 8%      |
| Kingston            | 8         | 6.4%    |
| Micron Technology   | 7         | 5.6%    |
| Foxline             | 5         | 4%      |
| Elpida              | 3         | 2.4%    |
| A-DATA Technology   | 3         | 2.4%    |
| Ramaxel Technology  | 2         | 1.6%    |
| SHARETRONIC         | 1         | 0.8%    |
| Patriot             | 1         | 0.8%    |
| Unknown             | 1         | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 13        | 10.16%  |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                    | 9         | 7.03%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                    | 5         | 3.91%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 5         | 3.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 4         | 3.13%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s        | 4         | 3.13%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s             | 4         | 3.13%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s          | 4         | 3.13%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                   | 3         | 2.34%   |
| Unknown RAM Module 2048MB SODIMM DDR2                           | 3         | 2.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 2.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s       | 3         | 2.34%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 3         | 2.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 2         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s           | 2         | 1.56%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s        | 2         | 1.56%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8192MB SODIMM DDR4 2667MT/s      | 2         | 1.56%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s         | 2         | 1.56%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                    | 1         | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 0.78%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                        | 1         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2                              | 1         | 0.78%   |
| Unknown RAM Module 1024MB SODIMM DDR2 333MT/s                   | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 0.78%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s       | 1         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s          | 1         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-XN 4096MB Row Of Chips DDR4 3200MT/s | 1         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 0.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 0.78%   |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1333MT/s                 | 1         | 0.78%   |
| Samsung RAM U6E3S4AA-MGCR 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.78%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s           | 1         | 0.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s           | 1         | 0.78%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.78%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 0.78%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.78%   |
| Samsung RAM K4UBE3D4AA-MGCH 8192MB Row Of Chips LPDDR4 3200MT/s | 1         | 0.78%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s            | 1         | 0.78%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s         | 1         | 0.78%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s       | 1         | 0.78%   |
| Patriot RAM PSD44G213381S 4GB SODIMM DDR4 2133MT/s              | 1         | 0.78%   |
| Micron RAM Module 4096MB Row Of Chips DDR4 2400MT/s             | 1         | 0.78%   |
| Micron RAM Module 1GB SODIMM DDR3 1067MT/s                      | 1         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 1         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s           | 1         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s           | 1         | 0.78%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s           | 1         | 0.78%   |
| Kingston RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 0.78%   |
| Kingston RAM CBD24D4S7S8ME-8 8192MB SODIMM DDR4 2400MT/s        | 1         | 0.78%   |
| Kingston RAM ACR16D3LS1KDG/2G 2GB SODIMM DDR3 1600MT/s          | 1         | 0.78%   |
| Kingston RAM 99U5469-078.A00LF 4GB SODIMM DDR3 1600MT/s         | 1         | 0.78%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s         | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 70.59%  |
| DDR3    | 23        | 19.33%  |
| DDR2    | 8         | 6.72%   |
| LPDDR4  | 3         | 2.52%   |
| Unknown | 1         | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 92.5%   |
| Row Of Chips | 9         | 7.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 56        | 45.53%  |
| 4096  | 43        | 34.96%  |
| 2048  | 11        | 8.94%   |
| 16384 | 10        | 8.13%   |
| 1024  | 2         | 1.63%   |
| 512   | 1         | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 48        | 38.1%   |
| 3200    | 17        | 13.49%  |
| 1600    | 16        | 12.7%   |
| 2133    | 13        | 10.32%  |
| 2400    | 6         | 4.76%   |
| 1334    | 6         | 4.76%   |
| Unknown | 5         | 3.97%   |
| 3266    | 4         | 3.17%   |
| 667     | 3         | 2.38%   |
| 4267    | 2         | 1.59%   |
| 1333    | 2         | 1.59%   |
| 2933    | 1         | 0.79%   |
| 1067    | 1         | 0.79%   |
| 800     | 1         | 0.79%   |
| 333     | 1         | 0.79%   |

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
| Chicony Electronics                    | 34        | 27.87%  |
| Cheng Uei Precision Industry (Foxlink) | 28        | 22.95%  |
| IMC Networks                           | 16        | 13.11%  |
| Sunplus Innovation Technology          | 7         | 5.74%   |
| Acer                                   | 7         | 5.74%   |
| Quanta                                 | 6         | 4.92%   |
| Suyin                                  | 5         | 4.1%    |
| Syntek                                 | 3         | 2.46%   |
| Realtek Semiconductor                  | 3         | 2.46%   |
| Microdia                               | 2         | 1.64%   |
| Lite-On Technology                     | 2         | 1.64%   |
| Z-Star Microelectronics                | 1         | 0.82%   |
| Unknown                                | 1         | 0.82%   |
| SunplusIT                              | 1         | 0.82%   |
| Sonix Technology                       | 1         | 0.82%   |
| Silicon Motion                         | 1         | 0.82%   |
| Ricoh                                  | 1         | 0.82%   |
| Primax Electronics                     | 1         | 0.82%   |
| Apple                                  | 1         | 0.82%   |
| Alcor Micro                            | 1         | 0.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 12.2%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 12        | 9.76%   |
| Chicony HP HD Camera                                           | 9         | 7.32%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 4.88%   |
| Chicony USB2.0 Camera                                          | 6         | 4.88%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 3.25%   |
| IMC Networks Integrated Camera                                 | 4         | 3.25%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 2.44%   |
| Chicony Integrated Camera                                      | 3         | 2.44%   |
| Syntek Integrated Camera                                       | 2         | 1.63%   |
| Suyin 1.3M HD WebCam                                           | 2         | 1.63%   |
| Sunplus Asus Webcam                                            | 2         | 1.63%   |
| Chicony VGA Webcam                                             | 2         | 1.63%   |
| Chicony USB camera                                             | 2         | 1.63%   |
| Chicony HD WebCam                                              | 2         | 1.63%   |
| Acer BisonCam,NB Pro                                           | 2         | 1.63%   |
| Acer BisonCam, NB Pro                                          | 2         | 1.63%   |
| Z-Star Vega USB 2.0 Camera                                     | 1         | 0.81%   |
| Unknown USB2.0 Webcam                                          | 1         | 0.81%   |
| Syntek Lenovo EasyCamera                                       | 1         | 0.81%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.81%   |
| Suyin HP Truevision HD                                         | 1         | 0.81%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.81%   |
| SunplusIT MTD camera                                           | 1         | 0.81%   |
| Sunplus Integrated Camera                                      | 1         | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 0.81%   |
| Silicon Motion WebCam SC-0311139N                              | 1         | 0.81%   |
| Ricoh USB2.0 Camera                                            | 1         | 0.81%   |
| Realtek Lenovo EasyCamera                                      | 1         | 0.81%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 0.81%   |
| Realtek EasyCamera                                             | 1         | 0.81%   |
| Quanta VGA WebCam                                              | 1         | 0.81%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 0.81%   |
| Quanta HP Webcam                                               | 1         | 0.81%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 0.81%   |
| Microdia Webcam Vitade AF                                      | 1         | 0.81%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 0.81%   |
| Lite-On HP Wide Vision HD Camera                               | 1         | 0.81%   |
| Lite-On HP Webcam                                              | 1         | 0.81%   |
| IMC Networks VGA UVC WebCam                                    | 1         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 0.81%   |
| IMC Networks USB 2.0 Camera                                    | 1         | 0.81%   |
| IMC Networks ov9734_azurewave_camera                           | 1         | 0.81%   |
| IMC Networks HP TrueVision HD Camera                           | 1         | 0.81%   |
| IMC Networks HD Camera                                         | 1         | 0.81%   |
| Chicony XiaoMi USB 2.0 Webcam                                  | 1         | 0.81%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 0.81%   |
| Chicony USB 2.0 Webcam Device                                  | 1         | 0.81%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 0.81%   |
| Chicony Lenovo EasyCamera                                      | 1         | 0.81%   |
| Chicony Integrated HP HD Webcam                                | 1         | 0.81%   |
| Chicony HP Wide Vision HD Camera                               | 1         | 0.81%   |
| Chicony HD User Facing                                         | 1         | 0.81%   |
| Chicony CNF7070 Webcam                                         | 1         | 0.81%   |
| Chicony 1.3M HD WebCam                                         | 1         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 0.81%   |
| Apple Built-in iSight                                          | 1         | 0.81%   |
| Alcor Micro Acer Integrated Webcam                             | 1         | 0.81%   |
| Acer USB2.0 Camera                                             | 1         | 0.81%   |
| Acer USB HD Webcam                                             | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 46.15%  |
| Elan Microelectronics      | 3         | 23.08%  |
| Synaptics                  | 2         | 15.38%  |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| LighTuning Technology      | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 15.38%  |
| Validity Sensors VFS491                           | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 15.38%  |
| Elan ELAN:Fingerprint                             | 2         | 15.38%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner              | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 7.69%   |
| Elan ELAN:ARM-M4                                  | 1         | 7.69%   |

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
| 0     | 101       | 76.52%  |
| 1     | 22        | 16.67%  |
| 2     | 8         | 6.06%   |
| 3     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 36.11%  |
| Graphics card            | 7         | 19.44%  |
| Communication controller | 7         | 19.44%  |
| Chipcard                 | 3         | 8.33%   |
| Net/ethernet             | 2         | 5.56%   |
| Sound                    | 1         | 2.78%   |
| Multimedia controller    | 1         | 2.78%   |
| Camera                   | 1         | 2.78%   |
| Bluetooth                | 1         | 2.78%   |

