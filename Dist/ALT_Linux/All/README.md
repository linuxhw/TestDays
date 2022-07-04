ALT Linux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ALT Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ALT_Linux/Desktop/README.md) and [notebooks](/Dist/ALT_Linux/Notebook/README.md).

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

Total: 516

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | H510SB-TM v2.0              | All in one  | [8598f1f5ee](https://linux-hardware.org/?probe=8598f1f5ee) | Jun 30, 2022 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [7411d7a561](https://linux-hardware.org/?probe=7411d7a561) | Jun 23, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2724c1558a](https://linux-hardware.org/?probe=2724c1558a) | Jun 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [8fe4a74fa3](https://linux-hardware.org/?probe=8fe4a74fa3) | Jun 10, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [31ab5150ea](https://linux-hardware.org/?probe=31ab5150ea) | Jun 06, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4fa81ba66a](https://linux-hardware.org/?probe=4fa81ba66a) | Jun 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [fb935ea1d0](https://linux-hardware.org/?probe=fb935ea1d0) | Jun 03, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [7bfddcecee](https://linux-hardware.org/?probe=7bfddcecee) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| Panasonic     | CF-20-1                     | Notebook    | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| ICL           | Unknown                     | Notebook    | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [db9d229530](https://linux-hardware.org/?probe=db9d229530) | May 19, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| iRU           | LPGR.469559.012             | Desktop     | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ICL           | H310SB-TM                   | All in one  | [72c2889a81](https://linux-hardware.org/?probe=72c2889a81) | May 18, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [ac65146c38](https://linux-hardware.org/?probe=ac65146c38) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | Desktop     | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [96e5d68181](https://linux-hardware.org/?probe=96e5d68181) | May 06, 2022 |
| ASRock        | H61M-GE                     | Desktop     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| ICL           | H310SB-TM                   | All in one  | [8aca897292](https://linux-hardware.org/?probe=8aca897292) | May 05, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| ICL           | H310SB-TM                   | All in one  | [5e24e4a45d](https://linux-hardware.org/?probe=5e24e4a45d) | May 04, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| Lenovo        | NOK                         | Desktop     | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| ICL           | H310SB-TM                   | All in one  | [11db07be56](https://linux-hardware.org/?probe=11db07be56) | Apr 25, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [651d569b66](https://linux-hardware.org/?probe=651d569b66) | Apr 18, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b97ab9e5ca](https://linux-hardware.org/?probe=b97ab9e5ca) | Apr 18, 2022 |
| ICL           | H310SB-TM                   | All in one  | [75dab395ac](https://linux-hardware.org/?probe=75dab395ac) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [faeb46556e](https://linux-hardware.org/?probe=faeb46556e) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [1ec31e58eb](https://linux-hardware.org/?probe=1ec31e58eb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [558e7d71c5](https://linux-hardware.org/?probe=558e7d71c5) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [58d8d12597](https://linux-hardware.org/?probe=58d8d12597) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [352ed8f1aa](https://linux-hardware.org/?probe=352ed8f1aa) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [f23db30412](https://linux-hardware.org/?probe=f23db30412) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3fa8965015](https://linux-hardware.org/?probe=3fa8965015) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [287eb4cfbb](https://linux-hardware.org/?probe=287eb4cfbb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [8c69097ae0](https://linux-hardware.org/?probe=8c69097ae0) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| Timi          | TM1701                      | Notebook    | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [567d83946c](https://linux-hardware.org/?probe=567d83946c) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [84e70046d5](https://linux-hardware.org/?probe=84e70046d5) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [92f6d24bde](https://linux-hardware.org/?probe=92f6d24bde) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [8e924a50c1](https://linux-hardware.org/?probe=8e924a50c1) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [99d19658b8](https://linux-hardware.org/?probe=99d19658b8) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b6bcbc6a65](https://linux-hardware.org/?probe=b6bcbc6a65) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3e7d8951a2](https://linux-hardware.org/?probe=3e7d8951a2) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [71dfb9a346](https://linux-hardware.org/?probe=71dfb9a346) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [7cf5bcdb89](https://linux-hardware.org/?probe=7cf5bcdb89) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [6aaab98810](https://linux-hardware.org/?probe=6aaab98810) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [dde0916ae5](https://linux-hardware.org/?probe=dde0916ae5) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [68041f0a96](https://linux-hardware.org/?probe=68041f0a96) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [87858c448c](https://linux-hardware.org/?probe=87858c448c) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a7e615a620](https://linux-hardware.org/?probe=a7e615a620) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [5b340e2b7f](https://linux-hardware.org/?probe=5b340e2b7f) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a20cfb8d86](https://linux-hardware.org/?probe=a20cfb8d86) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [19d0ee846e](https://linux-hardware.org/?probe=19d0ee846e) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [9e2f7749b8](https://linux-hardware.org/?probe=9e2f7749b8) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [a473baa2ff](https://linux-hardware.org/?probe=a473baa2ff) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [12009b21d8](https://linux-hardware.org/?probe=12009b21d8) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [3f2bf77788](https://linux-hardware.org/?probe=3f2bf77788) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| Acer          | Aspire 5745G                | Notebook    | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | Notebook    | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| HP            | 250 G3                      | Notebook    | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [83881d4eb6](https://linux-hardware.org/?probe=83881d4eb6) | Mar 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [2379c7546f](https://linux-hardware.org/?probe=2379c7546f) | Mar 09, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [92fc99440a](https://linux-hardware.org/?probe=92fc99440a) | Mar 08, 2022 |
| Dell          | G5 5590                     | Notebook    | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [4f93db2c52](https://linux-hardware.org/?probe=4f93db2c52) | Mar 05, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [04a1a09e43](https://linux-hardware.org/?probe=04a1a09e43) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [f7f470651e](https://linux-hardware.org/?probe=f7f470651e) | Feb 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| Gigabyte      | X79-UD3                     | Desktop     | [452ebf6a67](https://linux-hardware.org/?probe=452ebf6a67) | Feb 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [921e224ec5](https://linux-hardware.org/?probe=921e224ec5) | Feb 12, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | Notebook    | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| T-Platform... | TF307-MB                    | Soc         | [c34cd190e4](https://linux-hardware.org/?probe=c34cd190e4) | Feb 01, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [351b2e5344](https://linux-hardware.org/?probe=351b2e5344) | Jan 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [481e745592](https://linux-hardware.org/?probe=481e745592) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [8c31667834](https://linux-hardware.org/?probe=8c31667834) | Jan 20, 2022 |
| ASRock        | A520M-HDVP/DASH             | Desktop     | [edd6464f18](https://linux-hardware.org/?probe=edd6464f18) | Jan 19, 2022 |
| ASRock        | A520M-HDVP/DASH             | Desktop     | [93fef2e073](https://linux-hardware.org/?probe=93fef2e073) | Jan 19, 2022 |
| Dell          | Latitude 3590               | Notebook    | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| MSI           | MS-AC16 100                 | All in one  | [3a3bfc48f7](https://linux-hardware.org/?probe=3a3bfc48f7) | Jan 17, 2022 |
| MSI           | A68HM-P33 V2                | Desktop     | [98e05db690](https://linux-hardware.org/?probe=98e05db690) | Jan 17, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [0c802de596](https://linux-hardware.org/?probe=0c802de596) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c8ff16f0ed](https://linux-hardware.org/?probe=c8ff16f0ed) | Dec 24, 2021 |
| Supermicro    | X11SDW-14CNT-TP13F          | Desktop     | [4d8499f8ba](https://linux-hardware.org/?probe=4d8499f8ba) | Dec 23, 2021 |
| Supermicro    | X10SDV-TP8F                 | Server      | [adc426b903](https://linux-hardware.org/?probe=adc426b903) | Dec 23, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9180a824d8](https://linux-hardware.org/?probe=9180a824d8) | Dec 23, 2021 |
| Samsung       | 750XDA                      | Notebook    | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [7ef05a32a9](https://linux-hardware.org/?probe=7ef05a32a9) | Dec 17, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [2aff2121af](https://linux-hardware.org/?probe=2aff2121af) | Dec 16, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [30eab5f54f](https://linux-hardware.org/?probe=30eab5f54f) | Dec 15, 2021 |
| Unknown       | Baikal Electronics Baika... | Soc         | [b4e6606b42](https://linux-hardware.org/?probe=b4e6606b42) | Dec 10, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [c853f62ddd](https://linux-hardware.org/?probe=c853f62ddd) | Dec 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [0f5c69902a](https://linux-hardware.org/?probe=0f5c69902a) | Dec 01, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [68a1f83b4f](https://linux-hardware.org/?probe=68a1f83b4f) | Nov 28, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [058d8a0404](https://linux-hardware.org/?probe=058d8a0404) | Nov 19, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [70ee05a53e](https://linux-hardware.org/?probe=70ee05a53e) | Oct 28, 2021 |
| HUAWEI        | BC11SPSCB0 V100R005         | Server      | [ad903545ce](https://linux-hardware.org/?probe=ad903545ce) | Oct 14, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9dd1b763b](https://linux-hardware.org/?probe=d9dd1b763b) | Oct 08, 2021 |
| Dell          | 0U649C                      | Desktop     | [80e138d949](https://linux-hardware.org/?probe=80e138d949) | Sep 24, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [92829c951d](https://linux-hardware.org/?probe=92829c951d) | Sep 21, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [da7d22c384](https://linux-hardware.org/?probe=da7d22c384) | Sep 16, 2021 |
| Timi          | TM1701                      | Notebook    | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | Notebook    | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [132286ab64](https://linux-hardware.org/?probe=132286ab64) | Aug 17, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [85ce2f74c4](https://linux-hardware.org/?probe=85ce2f74c4) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [624e92e15e](https://linux-hardware.org/?probe=624e92e15e) | Aug 11, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | Notebook    | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [db68dde16d](https://linux-hardware.org/?probe=db68dde16d) | Aug 04, 2021 |
| Durabook      | Z14                         | Notebook    | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b01641d467](https://linux-hardware.org/?probe=b01641d467) | Jul 25, 2021 |
| Aquarius      | NS483                       | Convertible | [bc5d045def](https://linux-hardware.org/?probe=bc5d045def) | Jul 20, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [8687a8809b](https://linux-hardware.org/?probe=8687a8809b) | Jul 14, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [05be9fcdec](https://linux-hardware.org/?probe=05be9fcdec) | Jul 03, 2021 |
| Aquarius      | NS585                       | Notebook    | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [24bd5ac93f](https://linux-hardware.org/?probe=24bd5ac93f) | Jun 27, 2021 |
| Kraftway      | KWH310                      | Desktop     | [f470a86a1c](https://linux-hardware.org/?probe=f470a86a1c) | Jun 26, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [87ab7018c4](https://linux-hardware.org/?probe=87ab7018c4) | Jun 24, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [d31e4518a6](https://linux-hardware.org/?probe=d31e4518a6) | Jun 22, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [21a019dcb3](https://linux-hardware.org/?probe=21a019dcb3) | Jun 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [8325754280](https://linux-hardware.org/?probe=8325754280) | Jun 13, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [96cc5b470f](https://linux-hardware.org/?probe=96cc5b470f) | Jun 12, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [cfeb0493d3](https://linux-hardware.org/?probe=cfeb0493d3) | Jun 11, 2021 |
| Dell          | G3 3779                     | Notebook    | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | Notebook    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [13396a7347](https://linux-hardware.org/?probe=13396a7347) | May 19, 2021 |
| DEPO Compu... | T09-D                       | Stick pc    | [678542f4fe](https://linux-hardware.org/?probe=678542f4fe) | May 18, 2021 |
| DEPO Compu... | DPH410S                     | Desktop     | [0d1000e904](https://linux-hardware.org/?probe=0d1000e904) | May 14, 2021 |
| DEPO Compu... | DPA320S G10g                | Desktop     | [5ecc011c34](https://linux-hardware.org/?probe=5ecc011c34) | May 14, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [97b70c1bac](https://linux-hardware.org/?probe=97b70c1bac) | Apr 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| Lenovo        | 3184 No DPK                 | All in one  | [bd5551c49a](https://linux-hardware.org/?probe=bd5551c49a) | Mar 31, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [34997240d5](https://linux-hardware.org/?probe=34997240d5) | Mar 30, 2021 |
| ECS           | BAT-I2                      | Desktop     | [037e6e58e6](https://linux-hardware.org/?probe=037e6e58e6) | Mar 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [f0c7659cf9](https://linux-hardware.org/?probe=f0c7659cf9) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [8e53d68603](https://linux-hardware.org/?probe=8e53d68603) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [7467b59c82](https://linux-hardware.org/?probe=7467b59c82) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| iRU           | IRUB365M                    | Desktop     | [b7d5dda036](https://linux-hardware.org/?probe=b7d5dda036) | Mar 11, 2021 |
| Dell          | 04G47W A00                  | All in one  | [3a565370de](https://linux-hardware.org/?probe=3a565370de) | Feb 15, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [6651c76da3](https://linux-hardware.org/?probe=6651c76da3) | Feb 07, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [d63a1e9eef](https://linux-hardware.org/?probe=d63a1e9eef) | Feb 02, 2021 |
| ASUSTek       | P5B                         | Desktop     | [e0fc318a34](https://linux-hardware.org/?probe=e0fc318a34) | Jan 28, 2021 |
| Supermicro    | X11DPH-i                    | Server      | [8d109ac7b4](https://linux-hardware.org/?probe=8d109ac7b4) | Jan 26, 2021 |
| EPoX Compu... | GeForce6100 + nForce410 ... | Desktop     | [99f734d52e](https://linux-hardware.org/?probe=99f734d52e) | Jan 18, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [38ae5dd532](https://linux-hardware.org/?probe=38ae5dd532) | Jan 14, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [593a489e8d](https://linux-hardware.org/?probe=593a489e8d) | Jan 13, 2021 |
| Intel         | B75                         | Desktop     | [34d29fb066](https://linux-hardware.org/?probe=34d29fb066) | Jan 12, 2021 |
| Acer          | NC-ES1-131-C1NL             | Notebook    | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [2c49129777](https://linux-hardware.org/?probe=2c49129777) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [31d84f6485](https://linux-hardware.org/?probe=31d84f6485) | Dec 31, 2020 |
| Irbis         | TW100                       | Tablet      | [23c593482c](https://linux-hardware.org/?probe=23c593482c) | Dec 28, 2020 |
| SYS           | H310SB                      | Desktop     | [ba93a151f2](https://linux-hardware.org/?probe=ba93a151f2) | Dec 24, 2020 |
| HP            | 877E A                      | Desktop     | [4456ec4081](https://linux-hardware.org/?probe=4456ec4081) | Dec 23, 2020 |
| MSI           | MS-AC16 100                 | All in one  | [8df63d744b](https://linux-hardware.org/?probe=8df63d744b) | Dec 23, 2020 |
| HP            | 877E A                      | Desktop     | [145b54d631](https://linux-hardware.org/?probe=145b54d631) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | Notebook    | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Irbis         | TW100                       | Tablet      | [5ebe1b6e89](https://linux-hardware.org/?probe=5ebe1b6e89) | Dec 19, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [dbc40fef9d](https://linux-hardware.org/?probe=dbc40fef9d) | Dec 18, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bb4bd8f82f](https://linux-hardware.org/?probe=bb4bd8f82f) | Dec 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5cf089cfa1](https://linux-hardware.org/?probe=5cf089cfa1) | Dec 07, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [fdfcfb17c6](https://linux-hardware.org/?probe=fdfcfb17c6) | Dec 03, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [98800b881c](https://linux-hardware.org/?probe=98800b881c) | Dec 03, 2020 |
| Gigabyte      | H310N x.x                   | Desktop     | [b0ca19ee36](https://linux-hardware.org/?probe=b0ca19ee36) | Dec 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4ec24e5c24](https://linux-hardware.org/?probe=4ec24e5c24) | Nov 27, 2020 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [2758f1ff94](https://linux-hardware.org/?probe=2758f1ff94) | Nov 21, 2020 |
| Acer          | Veriton Z4860G              | All in one  | [8adebb44d3](https://linux-hardware.org/?probe=8adebb44d3) | Nov 20, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ab7e110c9a](https://linux-hardware.org/?probe=ab7e110c9a) | Nov 17, 2020 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ed5fee32dd](https://linux-hardware.org/?probe=ed5fee32dd) | Nov 13, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c878b046bc](https://linux-hardware.org/?probe=c878b046bc) | Nov 13, 2020 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [5ad12e4b3b](https://linux-hardware.org/?probe=5ad12e4b3b) | Nov 12, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [e25041fb04](https://linux-hardware.org/?probe=e25041fb04) | Nov 09, 2020 |
| ASUSTek       | A8N-E                       | Desktop     | [f716673893](https://linux-hardware.org/?probe=f716673893) | Oct 24, 2020 |
| ASUSTek       | P5B-MX                      | Desktop     | [0779d0f18c](https://linux-hardware.org/?probe=0779d0f18c) | Oct 24, 2020 |
| MSI           | X300/X340/X400 series       | Notebook    | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [f587011ab7](https://linux-hardware.org/?probe=f587011ab7) | Sep 10, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [fb4e557598](https://linux-hardware.org/?probe=fb4e557598) | Aug 16, 2020 |
| ASRock        | 4CoreN73PV-HD720p           | Desktop     | [ac70970005](https://linux-hardware.org/?probe=ac70970005) | Aug 16, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [4c98d77a2f](https://linux-hardware.org/?probe=4c98d77a2f) | Aug 07, 2020 |
| Samsung       | R510/P510                   | Notebook    | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [cee7ed2ce9](https://linux-hardware.org/?probe=cee7ed2ce9) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [f31ffbf544](https://linux-hardware.org/?probe=f31ffbf544) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [72c1d1ffca](https://linux-hardware.org/?probe=72c1d1ffca) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [298376a45e](https://linux-hardware.org/?probe=298376a45e) | Jun 23, 2020 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [b03abee3fb](https://linux-hardware.org/?probe=b03abee3fb) | Jun 12, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [70139de021](https://linux-hardware.org/?probe=70139de021) | Jun 10, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ee83d50faa](https://linux-hardware.org/?probe=ee83d50faa) | Jun 10, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [c4c8bad6ca](https://linux-hardware.org/?probe=c4c8bad6ca) | May 31, 2020 |
| HP            | 255 G2                      | Notebook    | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [74899486ac](https://linux-hardware.org/?probe=74899486ac) | May 26, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [861b6c69a0](https://linux-hardware.org/?probe=861b6c69a0) | May 21, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ae09cd2a40](https://linux-hardware.org/?probe=ae09cd2a40) | May 21, 2020 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Acer          | Aspire E1-571G              | Notebook    | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | Notebook    | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a644a3a3ad](https://linux-hardware.org/?probe=a644a3a3ad) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | Notebook    | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| HP            | 09F0h                       | Desktop     | [7f6c26af5d](https://linux-hardware.org/?probe=7f6c26af5d) | Oct 25, 2019 |
| HUAWEI        | BC11HGSB0 V100R003          | Server      | [5eb4dfc951](https://linux-hardware.org/?probe=5eb4dfc951) | Oct 22, 2019 |
| Dell          | 0F96C8 A00                  | All in one  | [29d0ad2441](https://linux-hardware.org/?probe=29d0ad2441) | Oct 22, 2019 |
| MSI           | B350M PRO-VDH               | Desktop     | [525f09653e](https://linux-hardware.org/?probe=525f09653e) | Oct 08, 2019 |
| MSI           | MEGA BOOK S430              | Notebook    | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Gigabyte      | GA-890XA-UD3                | Desktop     | [1536999c3e](https://linux-hardware.org/?probe=1536999c3e) | Sep 13, 2019 |
| ASRock        | Z77 Pro3                    | Desktop     | [a1db2eb143](https://linux-hardware.org/?probe=a1db2eb143) | Sep 13, 2019 |
| ASRock        | B85M                        | Desktop     | [5a36ce2620](https://linux-hardware.org/?probe=5a36ce2620) | Sep 13, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | Notebook    | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [68dbf33470](https://linux-hardware.org/?probe=68dbf33470) | Aug 03, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [5814b6a2af](https://linux-hardware.org/?probe=5814b6a2af) | Mar 28, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [34b40d93fc](https://linux-hardware.org/?probe=34b40d93fc) | Oct 30, 2018 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [d55532d7a9](https://linux-hardware.org/?probe=d55532d7a9) | Oct 29, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Biostar       | NF720D A2G+                 | Desktop     | [ef09cb18cc](https://linux-hardware.org/?probe=ef09cb18cc) | Oct 29, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [572c918e8a](https://linux-hardware.org/?probe=572c918e8a) | Oct 27, 2018 |
| Acer          | Aspire ES1-523              | Notebook    | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | Notebook    | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 165       | 44.24%  |
| ALT Linux 9.1      | 65        | 17.43%  |
| ALT Linux 10.0     | 39        | 10.46%  |
| ALT Linux 9.0      | 31        | 8.31%   |
| ALT Linux 9.2      | 18        | 4.83%   |
| MOS 10             | 7         | 1.88%   |
| ALT Linux 10.1     | 6         | 1.61%   |
| ALT Linux P8       | 5         | 1.34%   |
| ALT Linux 8.2      | 5         | 1.34%   |
| ALT Linux P9       | 4         | 1.07%   |
| ALT Linux 8.4      | 4         | 1.07%   |
| ALT Linux 20201124 | 3         | 0.8%    |
| ALT Linux P10      | 2         | 0.54%   |
| ALT Linux 7.0.5    | 2         | 0.54%   |
| ALT Linux 20191026 | 2         | 0.54%   |
| ALT Linux 10.0.900 | 2         | 0.54%   |
| ALT Linux 9.1.990  | 1         | 0.27%   |
| ALT Linux 9        | 1         | 0.27%   |
| ALT Linux 8.990    | 1         | 0.27%   |
| ALT Linux 8.93     | 1         | 0.27%   |
| ALT Linux 8.920    | 1         | 0.27%   |
| ALT Linux 8.3      | 1         | 0.27%   |
| ALT Linux 8.2.0    | 1         | 0.27%   |
| ALT Linux 8.0.0    | 1         | 0.27%   |
| ALT Linux 8.0      | 1         | 0.27%   |
| ALT Linux 20190624 | 1         | 0.27%   |
| ALT Linux 20190303 | 1         | 0.27%   |
| ALT Linux 10.0.910 | 1         | 0.27%   |
| ALT Linux          | 1         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ALT Linux | 356       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.10.109-std-def-alt1       | 85        | 22.02%  |
| 5.10.102-std-def-alt1       | 78        | 20.21%  |
| 5.4.51-std-def-alt1         | 12        | 3.11%   |
| 5.10.82-std-def-alt1        | 12        | 3.11%   |
| 4.19.79-std-def-alt1        | 11        | 2.85%   |
| 5.4.68-std-def-alt1.1       | 10        | 2.59%   |
| 5.10.88-std-def-alt1        | 8         | 2.07%   |
| 5.4.28-std-def-alt1         | 6         | 1.55%   |
| 5.15.34-un-def-alt1         | 5         | 1.3%    |
| 5.15.32-un-def-alt1         | 5         | 1.3%    |
| 5.10.93-std-def-alt1        | 5         | 1.3%    |
| 5.10.32-un-def-alt1         | 5         | 1.3%    |
| 5.7.19-un-def-alt1          | 4         | 1.04%   |
| 5.4.62-std-def-alt1         | 4         | 1.04%   |
| 5.4.41-std-def-alt1         | 4         | 1.04%   |
| 5.10.35-un-def-alt1         | 4         | 1.04%   |
| 5.10.17-un-def-alt1         | 4         | 1.04%   |
| 5.4.85-std-def-alt1         | 3         | 0.78%   |
| 5.4.127-std-def-alt1        | 3         | 0.78%   |
| 5.15.15-un-def-alt1         | 3         | 0.78%   |
| 5.10.83-std-def-alt0.c9f.2  | 3         | 0.78%   |
| 5.10.113-std-def-alt1       | 3         | 0.78%   |
| 5.10.111-std-def-alt1       | 3         | 0.78%   |
| 5.4.181-std-def-alt1        | 2         | 0.52%   |
| 5.2.10-un-def-alt1          | 2         | 0.52%   |
| 5.15.37-un-def-alt1         | 2         | 0.52%   |
| 5.15.33-un-def-alt1         | 2         | 0.52%   |
| 5.15.25-un-def-alt1         | 2         | 0.52%   |
| 5.15.14-un-def-alt1         | 2         | 0.52%   |
| 5.10.72-std-def-alt1        | 2         | 0.52%   |
| 5.10.62-un-def-alt1         | 2         | 0.52%   |
| 5.10.61-un-def-alt1         | 2         | 0.52%   |
| 5.10.54-std-def-alt2        | 2         | 0.52%   |
| 5.10.52-un-def-alt1         | 2         | 0.52%   |
| 5.10.37-un-def-alt1         | 2         | 0.52%   |
| 5.10.117-std-def-alt1       | 2         | 0.52%   |
| 4.9.133-std-def-alt0.M80P.1 | 2         | 0.52%   |
| 4.19.66-std-def-alt1        | 2         | 0.52%   |
| 4.19.102-std-def-alt1       | 2         | 0.52%   |
| 5.9.8-un-def-alt1           | 1         | 0.26%   |
| 5.7.14-un-def-alt1          | 1         | 0.26%   |
| 5.4.98-std-def-alt1         | 1         | 0.26%   |
| 5.4.94-std-def-alt1         | 1         | 0.26%   |
| 5.4.92-std-def-alt1         | 1         | 0.26%   |
| 5.4.91-elbrus-def-alt2.12.1 | 1         | 0.26%   |
| 5.4.87-std-def-alt1         | 1         | 0.26%   |
| 5.4.84-std-def-alt1         | 1         | 0.26%   |
| 5.4.81-std-def-alt1         | 1         | 0.26%   |
| 5.4.77-std-def-alt1         | 1         | 0.26%   |
| 5.4.58-elbrus-def-alt1.7.0  | 1         | 0.26%   |
| 5.4.44-std-def-alt1         | 1         | 0.26%   |
| 5.4.35-std-def-alt1         | 1         | 0.26%   |
| 5.4.3-un-def-alt1           | 1         | 0.26%   |
| 5.4.171-std-def-alt1        | 1         | 0.26%   |
| 5.4.144-std-def-alt1        | 1         | 0.26%   |
| 5.4.134-std-def-alt1        | 1         | 0.26%   |
| 5.4.131-std-def-alt1        | 1         | 0.26%   |
| 5.4.123-std-def-alt1        | 1         | 0.26%   |
| 5.4.117-std-def-alt1        | 1         | 0.26%   |
| 5.4.115-std-def-alt1        | 1         | 0.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.109 | 85        | 22.02%  |
| 5.10.102 | 78        | 20.21%  |
| 5.4.51   | 12        | 3.11%   |
| 5.10.82  | 12        | 3.11%   |
| 4.19.79  | 11        | 2.85%   |
| 5.4.68   | 10        | 2.59%   |
| 5.10.88  | 8         | 2.07%   |
| 5.4.28   | 6         | 1.55%   |
| 5.15.34  | 5         | 1.3%    |
| 5.15.32  | 5         | 1.3%    |
| 5.10.93  | 5         | 1.3%    |
| 5.10.35  | 5         | 1.3%    |
| 5.10.32  | 5         | 1.3%    |
| 5.7.19   | 4         | 1.04%   |
| 5.4.62   | 4         | 1.04%   |
| 5.4.41   | 4         | 1.04%   |
| 5.10.17  | 4         | 1.04%   |
| 5.4.85   | 3         | 0.78%   |
| 5.4.127  | 3         | 0.78%   |
| 5.15.15  | 3         | 0.78%   |
| 5.10.83  | 3         | 0.78%   |
| 5.10.54  | 3         | 0.78%   |
| 5.10.113 | 3         | 0.78%   |
| 5.10.111 | 3         | 0.78%   |
| 5.4.181  | 2         | 0.52%   |
| 5.4.107  | 2         | 0.52%   |
| 5.2.10   | 2         | 0.52%   |
| 5.15.37  | 2         | 0.52%   |
| 5.15.33  | 2         | 0.52%   |
| 5.15.25  | 2         | 0.52%   |
| 5.15.14  | 2         | 0.52%   |
| 5.14.21  | 2         | 0.52%   |
| 5.10.72  | 2         | 0.52%   |
| 5.10.62  | 2         | 0.52%   |
| 5.10.61  | 2         | 0.52%   |
| 5.10.52  | 2         | 0.52%   |
| 5.10.37  | 2         | 0.52%   |
| 5.10.118 | 2         | 0.52%   |
| 5.10.117 | 2         | 0.52%   |
| 5.10.110 | 2         | 0.52%   |
| 4.9.133  | 2         | 0.52%   |
| 4.19.66  | 2         | 0.52%   |
| 4.19.102 | 2         | 0.52%   |
| 5.9.8    | 1         | 0.26%   |
| 5.7.14   | 1         | 0.26%   |
| 5.4.98   | 1         | 0.26%   |
| 5.4.94   | 1         | 0.26%   |
| 5.4.92   | 1         | 0.26%   |
| 5.4.91   | 1         | 0.26%   |
| 5.4.87   | 1         | 0.26%   |
| 5.4.84   | 1         | 0.26%   |
| 5.4.81   | 1         | 0.26%   |
| 5.4.77   | 1         | 0.26%   |
| 5.4.58   | 1         | 0.26%   |
| 5.4.44   | 1         | 0.26%   |
| 5.4.35   | 1         | 0.26%   |
| 5.4.3    | 1         | 0.26%   |
| 5.4.171  | 1         | 0.26%   |
| 5.4.144  | 1         | 0.26%   |
| 5.4.134  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 236       | 63.61%  |
| 5.4     | 63        | 16.98%  |
| 4.19    | 25        | 6.74%   |
| 5.15    | 19        | 5.12%   |
| 4.9     | 7         | 1.89%   |
| 5.7     | 5         | 1.35%   |
| 5.2     | 3         | 0.81%   |
| 5.13    | 3         | 0.81%   |
| 5.14    | 2         | 0.54%   |
| 4.14    | 2         | 0.54%   |
| 5.9     | 1         | 0.27%   |
| 5.3     | 1         | 0.27%   |
| 5.16    | 1         | 0.27%   |
| 5.12    | 1         | 0.27%   |
| 4.4     | 1         | 0.27%   |
| 4.20    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 340       | 95.51%  |
| i686    | 11        | 3.09%   |
| aarch64 | 3         | 0.84%   |
| e2k     | 2         | 0.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 250       | 68.68%  |
| Unknown         | 49        | 13.46%  |
| XFCE            | 47        | 12.91%  |
| MATE            | 4         | 1.1%    |
| LXQt            | 4         | 1.1%    |
| Cinnamon        | 4         | 1.1%    |
| GNOME           | 3         | 0.82%   |
| KDE             | 2         | 0.55%   |
| GNOME Flashback | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 344       | 96.36%  |
| Unknown | 7         | 1.96%   |
| Wayland | 3         | 0.84%   |
| Tty     | 3         | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 225       | 61.98%  |
| TDM     | 62        | 17.08%  |
| LightDM | 55        | 15.15%  |
| Unknown | 19        | 5.23%   |
| XDM     | 1         | 0.28%   |
| GDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| ru_RU   | 282       | 77.05%  |
| Unknown | 74        | 20.22%  |
| en_US   | 6         | 1.64%   |
| POSIX   | 2         | 0.55%   |
| el_GR   | 1         | 0.27%   |
| C       | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 250       | 69.64%  |
| BIOS | 109       | 30.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 321       | 89.66%  |
| Overlay | 30        | 8.38%   |
| Btrfs   | 5         | 1.4%    |
| Unknown | 2         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 257       | 71.59%  |
| MBR     | 82        | 22.84%  |
| Unknown | 20        | 5.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 325       | 90.78%  |
| Yes       | 33        | 9.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 214       | 59.44%  |
| Yes       | 146       | 40.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 54        | 15.17%  |
| Intel               | 46        | 12.92%  |
| ASUSTek Computer    | 46        | 12.92%  |
| Lenovo              | 34        | 9.55%   |
| Acer                | 27        | 7.58%   |
| Gigabyte Technology | 23        | 6.46%   |
| 3Logic Group        | 23        | 6.46%   |
| ASRock              | 18        | 5.06%   |
| ICL                 | 12        | 3.37%   |
| MSI                 | 10        | 2.81%   |
| Unknown             | 10        | 2.81%   |
| Dell                | 9         | 2.53%   |
| DEPO Computers      | 4         | 1.12%   |
| Supermicro          | 3         | 0.84%   |
| Samsung Electronics | 3         | 0.84%   |
| MAINBRD             | 3         | 0.84%   |
| iRU                 | 3         | 0.84%   |
| HUAWEI              | 3         | 0.84%   |
| Aquarius            | 3         | 0.84%   |
| Kraftway            | 2         | 0.56%   |
| Irbis               | 2         | 0.56%   |
| Apple               | 2         | 0.56%   |
| VIA Technologies    | 1         | 0.28%   |
| Toshiba             | 1         | 0.28%   |
| Timi                | 1         | 0.28%   |
| T-Platforms         | 1         | 0.28%   |
| SYS                 | 1         | 0.28%   |
| Sony                | 1         | 0.28%   |
| Panasonic           | 1         | 0.28%   |
| IP3 Technology      | 1         | 0.28%   |
| Foxconn             | 1         | 0.28%   |
| EPoX Computer       | 1         | 0.28%   |
| eMachines           | 1         | 0.28%   |
| Edelweiss           | 1         | 0.28%   |
| ECS                 | 1         | 0.28%   |
| Durabook            | 1         | 0.28%   |
| Biostar             | 1         | 0.28%   |
| AMI                 | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Intel SKYBAY                              | 43        | 12.08%  |
| 3Logic Group Graviton                     | 20        | 5.62%   |
| HP 250 G7 Notebook PC                     | 12        | 3.37%   |
| ASUS PRIME B450-PLUS                      | 12        | 3.37%   |
| Unknown                                   | 12        | 3.37%   |
| Lenovo V540-24IWL AIO 10YS0031RU          | 10        | 2.81%   |
| Acer Veriton X2640G                       | 10        | 2.81%   |
| HP ZBook 17 G5                            | 9         | 2.53%   |
| HP ProBook 440 G5                         | 8         | 2.25%   |
| ICL RAYbook Si1512                        | 6         | 1.69%   |
| Lenovo ThinkSystem SR590 -[7X99CTO1WW]-   | 5         | 1.4%    |
| Gigabyte H110M-S2H                        | 4         | 1.12%   |
| MAINBRD OPS62A-SHA                        | 3         | 0.84%   |
| ICL RAY S122.Mi                           | 3         | 0.84%   |
| HP EliteBook 840 G4                       | 3         | 0.84%   |
| HP 250 G6 Notebook PC                     | 3         | 0.84%   |
| Dell Latitude 3420                        | 3         | 0.84%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT      | 2         | 0.56%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 2         | 0.56%   |
| iRU 515                                   | 2         | 0.56%   |
| Irbis TW100                               | 2         | 0.56%   |
| ICL NJ50_70CU                             | 2         | 0.56%   |
| HP EliteBook 8470p                        | 2         | 0.56%   |
| Gigabyte H77M-D3H                         | 2         | 0.56%   |
| ASUS N46VZ                                | 2         | 0.56%   |
| ASUS H110M-R                              | 2         | 0.56%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE | 2         | 0.56%   |
| Acer Veriton Z4820G                       | 2         | 0.56%   |
| Acer Veriton ES2710G                      | 2         | 0.56%   |
| Acer TravelMate 5760                      | 2         | 0.56%   |
| 3Logic Group Graviton N15i-K2             | 2         | 0.56%   |
| VIA P4M266A-8235                          | 1         | 0.28%   |
| Toshiba Satellite A100                    | 1         | 0.28%   |
| Timi TM1701                               | 1         | 0.28%   |
| T-Platforms TF307-MB                      | 1         | 0.28%   |
| SYS RAY B101                              | 1         | 0.28%   |
| Supermicro SYS-5018D-FN8T                 | 1         | 0.28%   |
| Supermicro SYS-1019D-14CN-FHN13TP         | 1         | 0.28%   |
| Supermicro Super Server                   | 1         | 0.28%   |
| Sony SVE1512H1RB                          | 1         | 0.28%   |
| Samsung RV413/RV513/E3413                 | 1         | 0.28%   |
| Samsung R510/P510                         | 1         | 0.28%   |
| Samsung 750XDA                            | 1         | 0.28%   |
| Panasonic CF-20-1                         | 1         | 0.28%   |
| MSI X300/X340/X400 series                 | 1         | 0.28%   |
| MSI MS-AC16                               | 1         | 0.28%   |
| MSI MS-7A38                               | 1         | 0.28%   |
| MSI MS-7996                               | 1         | 0.28%   |
| MSI MS-7895                               | 1         | 0.28%   |
| MSI MS-7758                               | 1         | 0.28%   |
| MSI MS-7721                               | 1         | 0.28%   |
| MSI MPG B560 Trident A (MS-B926)          | 1         | 0.28%   |
| MSI MEGA BOOK S430                        | 1         | 0.28%   |
| MSI GE72 7RE                              | 1         | 0.28%   |
| Lenovo V510-15IKB 80WQ                    | 1         | 0.28%   |
| Lenovo V50a-24IMB 11FK002KRU              | 1         | 0.28%   |
| Lenovo V130-15IKB 81HN                    | 1         | 0.28%   |
| Lenovo ThinkPad X220 4291M85              | 1         | 0.28%   |
| Lenovo ThinkPad 13 2nd Gen 20J1S0EU00     | 1         | 0.28%   |
| Lenovo ThinkCentre M73 10B1S15000         | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel SKYBAY                      | 43        | 12.08%  |
| 3Logic Group Graviton             | 23        | 6.46%   |
| ASUS PRIME                        | 17        | 4.78%   |
| HP 250                            | 16        | 4.49%   |
| Acer Veriton                      | 15        | 4.21%   |
| Unknown                           | 12        | 3.37%   |
| Lenovo V540-24IWL                 | 10        | 2.81%   |
| HP ZBook                          | 9         | 2.53%   |
| HP ProBook                        | 9         | 2.53%   |
| Acer Aspire                       | 8         | 2.25%   |
| ICL RAYbook                       | 6         | 1.69%   |
| HP Pavilion                       | 6         | 1.69%   |
| Lenovo ThinkSystem                | 5         | 1.4%    |
| HP EliteBook                      | 5         | 1.4%    |
| Lenovo ThinkPad                   | 4         | 1.12%   |
| Lenovo IdeaPad                    | 4         | 1.12%   |
| HP Laptop                         | 4         | 1.12%   |
| Gigabyte H110M-S2H                | 4         | 1.12%   |
| Dell Latitude                     | 4         | 1.12%   |
| ASUS ASUS                         | 4         | 1.12%   |
| MAINBRD OPS62A-SHA                | 3         | 0.84%   |
| ICL RAY                           | 3         | 0.84%   |
| Dell OptiPlex                     | 3         | 0.84%   |
| ASUS VivoBook                     | 3         | 0.84%   |
| Lenovo ThinkBook                  | 2         | 0.56%   |
| iRU 515                           | 2         | 0.56%   |
| Irbis TW100                       | 2         | 0.56%   |
| ICL NJ50                          | 2         | 0.56%   |
| Gigabyte H77M-D3H                 | 2         | 0.56%   |
| ASUS N46VZ                        | 2         | 0.56%   |
| ASUS H110M-R                      | 2         | 0.56%   |
| Acer TravelMate                   | 2         | 0.56%   |
| VIA P4M266A-8235                  | 1         | 0.28%   |
| Toshiba Satellite                 | 1         | 0.28%   |
| Timi TM1701                       | 1         | 0.28%   |
| T-Platforms TF307-MB              | 1         | 0.28%   |
| SYS RAY                           | 1         | 0.28%   |
| Supermicro SYS-5018D-FN8T         | 1         | 0.28%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1         | 0.28%   |
| Supermicro Super                  | 1         | 0.28%   |
| Sony SVE1512H1RB                  | 1         | 0.28%   |
| Samsung RV413                     | 1         | 0.28%   |
| Samsung R510                      | 1         | 0.28%   |
| Samsung 750XDA                    | 1         | 0.28%   |
| Panasonic CF-20-1                 | 1         | 0.28%   |
| MSI X300                          | 1         | 0.28%   |
| MSI MS-AC16                       | 1         | 0.28%   |
| MSI MS-7A38                       | 1         | 0.28%   |
| MSI MS-7996                       | 1         | 0.28%   |
| MSI MS-7895                       | 1         | 0.28%   |
| MSI MS-7758                       | 1         | 0.28%   |
| MSI MS-7721                       | 1         | 0.28%   |
| MSI MPG                           | 1         | 0.28%   |
| MSI MEGA                          | 1         | 0.28%   |
| MSI GE72                          | 1         | 0.28%   |
| Lenovo V510-15IKB                 | 1         | 0.28%   |
| Lenovo V50a-24IMB                 | 1         | 0.28%   |
| Lenovo V130-15IKB                 | 1         | 0.28%   |
| Lenovo ThinkCentre                | 1         | 0.28%   |
| Lenovo G570                       | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 74        | 20.79%  |
| 2017    | 52        | 14.61%  |
| 2020    | 50        | 14.04%  |
| 2019    | 36        | 10.11%  |
| 2021    | 30        | 8.43%   |
| 2016    | 26        | 7.3%    |
| 2012    | 12        | 3.37%   |
| 2011    | 11        | 3.09%   |
| 2015    | 9         | 2.53%   |
| 2008    | 9         | 2.53%   |
| 2014    | 8         | 2.25%   |
| 2010    | 8         | 2.25%   |
| 2022    | 6         | 1.69%   |
| 2009    | 6         | 1.69%   |
| 2007    | 5         | 1.4%    |
| 2013    | 4         | 1.12%   |
| 2006    | 3         | 0.84%   |
| 2005    | 3         | 0.84%   |
| Unknown | 3         | 0.84%   |
| 2003    | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 168       | 47.19%  |
| Notebook       | 129       | 36.24%  |
| All in one     | 40        | 11.24%  |
| Server         | 9         | 2.53%   |
| System on chip | 3         | 0.84%   |
| Tablet         | 2         | 0.56%   |
| Convertible    | 2         | 0.56%   |
| Mini pc        | 2         | 0.56%   |
| Stick pc       | 1         | 0.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 325       | 90.53%  |
| Enabled  | 34        | 9.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 356       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 134       | 37.54%  |
| 8.01-16.0       | 84        | 23.53%  |
| 3.01-4.0        | 57        | 15.97%  |
| 16.01-24.0      | 50        | 14.01%  |
| 1.01-2.0        | 13        | 3.64%   |
| 64.01-256.0     | 9         | 2.52%   |
| 2.01-3.0        | 4         | 1.12%   |
| 32.01-64.0      | 3         | 0.84%   |
| 0.51-1.0        | 2         | 0.56%   |
| More than 256.0 | 1         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 191       | 50.93%  |
| 0.51-1.0  | 62        | 16.53%  |
| 2.01-3.0  | 55        | 14.67%  |
| 4.01-8.0  | 30        | 8%      |
| 3.01-4.0  | 27        | 7.2%    |
| 8.01-16.0 | 5         | 1.33%   |
| 0.01-0.5  | 5         | 1.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 271       | 74.66%  |
| 2       | 70        | 19.28%  |
| 3       | 11        | 3.03%   |
| 4       | 4         | 1.1%    |
| 0       | 4         | 1.1%    |
| 8       | 1         | 0.28%   |
| 5       | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 228       | 63.69%  |
| Yes       | 130       | 36.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 337       | 94.66%  |
| No        | 19        | 5.34%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 55.9%   |
| No        | 157       | 44.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 195       | 54.47%  |
| Yes       | 163       | 45.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Russia     | 341       | 95.79%  |
| Greece     | 5         | 1.4%    |
| Ukraine    | 2         | 0.56%   |
| Belarus    | 2         | 0.56%   |
| Uzbekistan | 1         | 0.28%   |
| Kazakhstan | 1         | 0.28%   |
| Egypt      | 1         | 0.28%   |
| Czechia    | 1         | 0.28%   |
| Costa Rica | 1         | 0.28%   |
| China      | 1         | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Moscow                   | 241       | 66.03%  |
| St Petersburg            | 21        | 5.75%   |
| Samara                   | 9         | 2.47%   |
| Barnaul                  | 8         | 2.19%   |
| Irkutsk                  | 4         | 1.1%    |
| Saratov                  | 3         | 0.82%   |
| Perm                     | 3         | 0.82%   |
| Obninsk                  | 3         | 0.82%   |
| Korolyov                 | 3         | 0.82%   |
| Kaliningrad              | 3         | 0.82%   |
| Belgorod                 | 3         | 0.82%   |
| Yekaterinburg            | 2         | 0.55%   |
| Verkhnyaya Pyshma        | 2         | 0.55%   |
| Vergina                  | 2         | 0.55%   |
| Thessaloniki             | 2         | 0.55%   |
| Sevastopol               | 2         | 0.55%   |
| Novosibirsk              | 2         | 0.55%   |
| Krasnoyarsk              | 2         | 0.55%   |
| Kostroma                 | 2         | 0.55%   |
| Kirov                    | 2         | 0.55%   |
| Astrakhan                | 2         | 0.55%   |
| Zelenodolsk              | 1         | 0.27%   |
| Vologda                  | 1         | 0.27%   |
| Vladivostok              | 1         | 0.27%   |
| Valuyki                  | 1         | 0.27%   |
| Tula                     | 1         | 0.27%   |
| Troitsk                  | 1         | 0.27%   |
| Tashkent                 | 1         | 0.27%   |
| Taraz                    | 1         | 0.27%   |
| Tambov                   | 1         | 0.27%   |
| Surgut                   | 1         | 0.27%   |
| Suez                     | 1         | 0.27%   |
| Shenzhen                 | 1         | 0.27%   |
| San José                | 1         | 0.27%   |
| Rostov-on-Don            | 1         | 0.27%   |
| Pushchino                | 1         | 0.27%   |
| Prague                   | 1         | 0.27%   |
| Polyarnyy                | 1         | 0.27%   |
| Petropavlovsk-Kamchatsky | 1         | 0.27%   |
| Omsk                     | 1         | 0.27%   |
| Novichikha               | 1         | 0.27%   |
| Nizhnyaya Poyma          | 1         | 0.27%   |
| Nizhny Tagil             | 1         | 0.27%   |
| Nizhniy Novgorod         | 1         | 0.27%   |
| Murmansk                 | 1         | 0.27%   |
| Monchegorsk              | 1         | 0.27%   |
| Mogilev                  | 1         | 0.27%   |
| Lipetsk                  | 1         | 0.27%   |
| Lesosibirsk              | 1         | 0.27%   |
| Kyzyl                    | 1         | 0.27%   |
| Krasnokamensk            | 1         | 0.27%   |
| Krasnogorsk              | 1         | 0.27%   |
| Krasnodar                | 1         | 0.27%   |
| Kirovsk                  | 1         | 0.27%   |
| Khabarovsk               | 1         | 0.27%   |
| Kemerovo                 | 1         | 0.27%   |
| Kazan’                 | 1         | 0.27%   |
| Ivanovo                  | 1         | 0.27%   |
| Hurghada                 | 1         | 0.27%   |
| Fedorovka                | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 65        | 89     | 15.55%  |
| Seagate             | 52        | 72     | 12.44%  |
| Samsung Electronics | 50        | 62     | 11.96%  |
| Toshiba             | 36        | 55     | 8.61%   |
| SK hynix            | 27        | 27     | 6.46%   |
| AXIOMTEK            | 26        | 26     | 6.22%   |
| Kingston            | 23        | 25     | 5.5%    |
| Intel               | 23        | 30     | 5.5%    |
| Apacer              | 20        | 22     | 4.78%   |
| Hitachi             | 10        | 11     | 2.39%   |
| Foxline             | 9         | 9      | 2.15%   |
| A-DATA Technology   | 9         | 10     | 2.15%   |
| China               | 8         | 8      | 1.91%   |
| Crucial             | 7         | 8      | 1.67%   |
| SanDisk             | 5         | 5      | 1.2%    |
| HGST                | 5         | 5      | 1.2%    |
| Unknown             | 4         | 6      | 0.96%   |
| Gigabyte Technology | 3         | 3      | 0.72%   |
| XPG                 | 2         | 3      | 0.48%   |
| Transcend           | 2         | 3      | 0.48%   |
| SSSTC               | 2         | 2      | 0.48%   |
| PNY                 | 2         | 2      | 0.48%   |
| Plextor             | 2         | 2      | 0.48%   |
| Phison              | 2         | 2      | 0.48%   |
| Micron Technology   | 2         | 7      | 0.48%   |
| Fujitsu             | 2         | 2      | 0.48%   |
| DEPO                | 2         | 2      | 0.48%   |
| AMD                 | 2         | 2      | 0.48%   |
| TMI                 | 1         | 1      | 0.24%   |
| SPCC                | 1         | 1      | 0.24%   |
| SP-8                | 1         | 1      | 0.24%   |
| Smartbuy            | 1         | 1      | 0.24%   |
| SINTECHI            | 1         | 1      | 0.24%   |
| Patriot             | 1         | 1      | 0.24%   |
| OCZ                 | 1         | 1      | 0.24%   |
| Netac               | 1         | 1      | 0.24%   |
| LITEON              | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 1      | 0.24%   |
| KingDian            | 1         | 1      | 0.24%   |
| JMicron Technology  | 1         | 1      | 0.24%   |
| HEORIADY            | 1         | 1      | 0.24%   |
| BaseTech            | 1         | 1      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |
| Unknown             | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD      | 26        | 5.94%   |
| Samsung MZVLW128HEGR-00000 128GB          | 17        | 3.88%   |
| Apacer AS2280P4 256GB                     | 15        | 3.42%   |
| Toshiba HDWD120 2TB                       | 13        | 2.97%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB   | 12        | 2.74%   |
| WDC WD5000AZLX-21K2TA0 500GB              | 10        | 2.28%   |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB | 9         | 2.05%   |
| Seagate ST1000LM049-2GH172 1TB            | 9         | 2.05%   |
| Intel SSDPEMKF256G8H 256GB                | 8         | 1.83%   |
| Intel SSDPEKKF256G7H 256GB                | 8         | 1.83%   |
| Foxline FLSSD256M80E13TCX5 256GB          | 8         | 1.83%   |
| Toshiba HDWD110 1TB                       | 5         | 1.14%   |
| Kingston RBUSC180S37256GJ 256GB SSD       | 5         | 1.14%   |
| Toshiba DT01ACA100 1TB                    | 4         | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 4         | 0.91%   |
| Samsung SSD 860 EVO 250GB                 | 4         | 0.91%   |
| Samsung MZALQ256HAJD-000L2 256GB          | 4         | 0.91%   |
| Kingston SA400S37240G 240GB SSD           | 4         | 0.91%   |
| Crucial CT240BX500SSD1 240GB              | 4         | 0.91%   |
| WDC WDS240G1G0A-00SS50 240GB SSD          | 3         | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 3         | 0.68%   |
| Seagate ST9250315AS 250GB                 | 3         | 0.68%   |
| Seagate ST380815AS 80GB                   | 3         | 0.68%   |
| Samsung SSD 860 EVO M.2 250GB             | 3         | 0.68%   |
| Kingston SV300S37A120G 120GB SSD          | 3         | 0.68%   |
| Kingston SA400S37120G 120GB SSD           | 3         | 0.68%   |
| HGST HTS721010A9E630 1TB                  | 3         | 0.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 2         | 0.46%   |
| WDC WD5000LPLX-60ZNTT2 500GB              | 2         | 0.46%   |
| WDC WD3200BPVT-22JJ5T0 320GB              | 2         | 0.46%   |
| WDC WD10PURZ-85U8XY0 1TB                  | 2         | 0.46%   |
| Unknown SLD64G  64GB                      | 2         | 0.46%   |
| Unknown SD128  128GB                      | 2         | 0.46%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.46%   |
| Toshiba MQ01ACF050 500GB                  | 2         | 0.46%   |
| Toshiba KXG50ZNV256G 256GB                | 2         | 0.46%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB            | 2         | 0.46%   |
| Seagate ST500LM030-2E717D 500GB           | 2         | 0.46%   |
| Seagate ST500DM002-1BC142 500GB           | 2         | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB            | 2         | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB            | 2         | 0.46%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 0.46%   |
| Samsung NVMe SSD Drive 512GB              | 2         | 0.46%   |
| Samsung MZVLB256HBHQ-000L7 256GB          | 2         | 0.46%   |
| Phison M.2 128GB SSO128GTLCG-SBC-2 SSD    | 2         | 0.46%   |
| Intel SSDPEKNW512G8H 512GB                | 2         | 0.46%   |
| Hitachi HDS721025CLA382 165GB             | 2         | 0.46%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 2         | 0.46%   |
| DEPO SM3DT-120 120GB SSD                  | 2         | 0.46%   |
| Crucial CT120BX500SSD1 120GB              | 2         | 0.46%   |
| China SSD 128GB                           | 2         | 0.46%   |
| Apacer AS350 256GB SSD                    | 2         | 0.46%   |
| A-DATA SU650 120GB SSD                    | 2         | 0.46%   |
| XPG NVMe SSD Drive 256GB                  | 1         | 0.23%   |
| XPG GAMMIX S5 1TB                         | 1         | 0.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 0.23%   |
| WDC WDS100T2B0B-00YS70 1TB SSD            | 1         | 0.23%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.23%   |
| WDC WD800AAJS-00WAA0 80GB                 | 1         | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 50        | 70     | 32.68%  |
| Seagate            | 50        | 67     | 32.68%  |
| Toshiba            | 34        | 53     | 22.22%  |
| Hitachi            | 10        | 11     | 6.54%   |
| HGST               | 5         | 5      | 3.27%   |
| Fujitsu            | 2         | 2      | 1.31%   |
| SINTECHI           | 1         | 1      | 0.65%   |
| JMicron Technology | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| AXIOMTEK            | 26        | 26     | 19.7%   |
| Kingston            | 19        | 20     | 14.39%  |
| Samsung Electronics | 14        | 16     | 10.61%  |
| WDC                 | 10        | 13     | 7.58%   |
| China               | 8         | 8      | 6.06%   |
| Crucial             | 7         | 8      | 5.3%    |
| A-DATA Technology   | 7         | 8      | 5.3%    |
| Apacer              | 4         | 6      | 3.03%   |
| SanDisk             | 3         | 3      | 2.27%   |
| Transcend           | 2         | 3      | 1.52%   |
| SK hynix            | 2         | 2      | 1.52%   |
| Seagate             | 2         | 5      | 1.52%   |
| PNY                 | 2         | 2      | 1.52%   |
| Plextor             | 2         | 2      | 1.52%   |
| Phison              | 2         | 2      | 1.52%   |
| Intel               | 2         | 5      | 1.52%   |
| Foxline             | 2         | 2      | 1.52%   |
| DEPO                | 2         | 2      | 1.52%   |
| AMD                 | 2         | 2      | 1.52%   |
| TMI                 | 1         | 1      | 0.76%   |
| SP-8                | 1         | 1      | 0.76%   |
| Smartbuy            | 1         | 1      | 0.76%   |
| Patriot             | 1         | 1      | 0.76%   |
| OCZ                 | 1         | 1      | 0.76%   |
| Netac               | 1         | 1      | 0.76%   |
| Micron Technology   | 1         | 6      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| KingDian            | 1         | 1      | 0.76%   |
| HEORIADY            | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| BaseTech            | 1         | 1      | 0.76%   |
| Unknown             | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 141       | 210    | 35.16%  |
| NVMe | 127       | 144    | 31.67%  |
| SSD  | 127       | 154    | 31.67%  |
| MMC  | 6         | 8      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 235       | 360    | 63.17%  |
| NVMe | 127       | 144    | 34.14%  |
| MMC  | 6         | 8      | 1.61%   |
| SAS  | 4         | 4      | 1.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 182       | 226    | 67.66%  |
| 0.51-1.0   | 61        | 92     | 22.68%  |
| 1.01-2.0   | 24        | 43     | 8.92%   |
| 2.01-3.0   | 2         | 3      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 190       | 52.05%  |
| 251-500        | 55        | 15.07%  |
| 1001-2000      | 28        | 7.67%   |
| 51-100         | 28        | 7.67%   |
| 21-50          | 20        | 5.48%   |
| 1-20           | 18        | 4.93%   |
| 501-1000       | 18        | 4.93%   |
| More than 3000 | 4         | 1.1%    |
| 2001-3000      | 3         | 0.82%   |
| Unknown        | 1         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 242       | 65.23%  |
| 21-50          | 52        | 14.02%  |
| 101-250        | 28        | 7.55%   |
| 51-100         | 23        | 6.2%    |
| 251-500        | 11        | 2.96%   |
| 501-1000       | 10        | 2.7%    |
| 1001-2000      | 2         | 0.54%   |
| More than 3000 | 1         | 0.27%   |
| 2001-3000      | 1         | 0.27%   |
| Unknown        | 1         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB               | 3         | 3      | 8.57%   |
| Seagate ST380815AS 80GB                 | 2         | 2      | 5.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 7      | 5.71%   |
| WDC WD7501AALS-00E3A0 752GB             | 1         | 1      | 2.86%   |
| WDC WD5000LPVX-60V0TT0 500GB            | 1         | 1      | 2.86%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 1         | 1      | 2.86%   |
| WDC WD3200AAKS-00V1A0 320GB             | 1         | 1      | 2.86%   |
| WDC WD2500KS-00MJB0 250GB               | 1         | 1      | 2.86%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 3      | 2.86%   |
| WDC WD20EARX-008FB0 2TB                 | 1         | 1      | 2.86%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 2.86%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 1         | 1      | 2.86%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 2.86%   |
| Seagate ST9640320AS 640GB               | 1         | 1      | 2.86%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 2.86%   |
| Seagate ST380811AS 80GB                 | 1         | 1      | 2.86%   |
| Seagate ST3320418AS 320GB               | 1         | 1      | 2.86%   |
| Seagate ST3000DM001-1CH166 3TB          | 1         | 1      | 2.86%   |
| Seagate ST250DM000-1BD141 250GB         | 1         | 2      | 2.86%   |
| Samsung Electronics SSD 870 EVO 500GB   | 1         | 1      | 2.86%   |
| Hitachi HUA722010CLA330 1TB             | 1         | 1      | 2.86%   |
| Hitachi HTS725050A9A364 500GB           | 1         | 1      | 2.86%   |
| Hitachi HTS545050KTA300 500GB           | 1         | 2      | 2.86%   |
| Hitachi HTS542525K9A300 250GB           | 1         | 1      | 2.86%   |
| Hitachi HTS541610J9SA00 100GB           | 1         | 1      | 2.86%   |
| Hitachi HDS723020BLA642 2TB             | 1         | 1      | 2.86%   |
| Hitachi HDS721025CLA382 165GB           | 1         | 1      | 2.86%   |
| HGST HTS721010A9E630 1TB                | 1         | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB              | 1         | 1      | 2.86%   |
| DEPO SM3DT-120 120GB SSD                | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 19     | 37.14%  |
| WDC                 | 8         | 10     | 22.86%  |
| Hitachi             | 7         | 8      | 20%     |
| SK hynix            | 2         | 2      | 5.71%   |
| HGST                | 2         | 2      | 5.71%   |
| Toshiba             | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| DEPO                | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 19     | 41.94%  |
| WDC     | 8         | 10     | 25.81%  |
| Hitachi | 7         | 8      | 22.58%  |
| HGST    | 2         | 2      | 6.45%   |
| Toshiba | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 40     | 88.24%  |
| SSD  | 3         | 3      | 8.82%   |
| NVMe | 1         | 1      | 2.94%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5001AALS-00E3A0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 301       | 408    | 81.35%  |
| Detected | 34        | 63     | 9.19%   |
| Malfunc  | 34        | 44     | 9.19%   |
| Failed   | 1         | 1      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 282       | 60%     |
| AMD                            | 47        | 10%     |
| Samsung Electronics            | 37        | 7.87%   |
| SK hynix                       | 24        | 5.11%   |
| Phison Electronics             | 24        | 5.11%   |
| Nvidia                         | 10        | 2.13%   |
| SanDisk                        | 7         | 1.49%   |
| Broadcom / LSI                 | 7         | 1.49%   |
| JMicron Technology             | 6         | 1.28%   |
| Kingston Technology Company    | 5         | 1.06%   |
| VIA Technologies               | 2         | 0.43%   |
| Toshiba America Info Systems   | 2         | 0.43%   |
| Solid State Storage Technology | 2         | 0.43%   |
| Realtek Semiconductor          | 2         | 0.43%   |
| MCST                           | 2         | 0.43%   |
| Marvell Technology Group       | 2         | 0.43%   |
| LSI Logic / Symbios Logic      | 2         | 0.43%   |
| ASMedia Technology             | 2         | 0.43%   |
| Silicon Motion                 | 1         | 0.21%   |
| Shenzhen Longsys Electronics   | 1         | 0.21%   |
| Micron Technology              | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |
| ADATA Technology               | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 66        | 11.93%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 39        | 7.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 29        | 5.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 29        | 5.24%   |
| Phison PS5013 E13 NVMe Controller                                                | 24        | 4.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 17        | 3.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 3.07%   |
| AMD 400 Series Chipset SATA Controller                                           | 16        | 2.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 15        | 2.71%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 13        | 2.35%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 12        | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 1.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 10        | 1.81%   |
| SK hynix Non-Volatile memory controller                                          | 9         | 1.63%   |
| Samsung NVMe SSD Controller 980                                                  | 9         | 1.63%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 9         | 1.63%   |
| Intel SSD 600P Series                                                            | 9         | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                            | 9         | 1.63%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 8         | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.27%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 7         | 1.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 1.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 6         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                               | 4         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 0.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 0.72%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.72%   |
| Broadcom / LSI MegaRAID Tri-Mode SAS3516                                         | 4         | 0.72%   |
| AMD FCH SATA Controller D                                                        | 4         | 0.72%   |
| Nvidia MCP51 Serial ATA Controller                                               | 3         | 0.54%   |
| Nvidia MCP51 IDE                                                                 | 3         | 0.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 3         | 0.54%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 3         | 0.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.54%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 0.54%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.36%   |
| Solid State Storage Non-Volatile memory controller                               | 2         | 0.36%   |
| SK hynix BC511                                                                   | 2         | 0.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.36%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.36%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2         | 0.36%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                     | 2         | 0.36%   |
| MCST SATA                                                                        | 2         | 0.36%   |
| MCST IDE controller                                                              | 2         | 0.36%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                          | 2         | 0.36%   |
| JMicron JMB368 IDE controller                                                    | 2         | 0.36%   |
| Intel SSD 660P Series                                                            | 2         | 0.36%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.36%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 295       | 59.6%   |
| NVMe | 127       | 25.66%  |
| IDE  | 40        | 8.08%   |
| RAID | 33        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 293       | 82.3%   |
| AMD          | 57        | 16.01%  |
| ARM          | 3         | 0.84%   |
| E8C/EATX     | 1         | 0.28%   |
| E8C-SWTX     | 1         | 0.28%   |
| CentaurHauls | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz            | 43        | 12.01%  |
| Intel Core i5-8265U CPU @ 1.60GHz             | 23        | 6.42%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 19        | 5.31%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 13        | 3.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 3.07%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 10        | 2.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 2.79%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 2.51%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 2.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 2.23%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 1.68%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz          | 5         | 1.4%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 4         | 1.12%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 4         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.12%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 4         | 1.12%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 3         | 0.84%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3         | 0.84%   |
| Intel Celeron CPU G3900 @ 2.80GHz             | 3         | 0.84%   |
| ARM Processor                                 | 3         | 0.84%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.84%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3         | 0.84%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 2         | 0.56%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 2         | 0.56%   |
| Intel Genuine CPU 0000 @ 2.40GHz              | 2         | 0.56%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.56%   |
| Intel Core i5-7600 CPU @ 3.50GHz              | 2         | 0.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.56%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.56%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 2         | 0.56%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 0.56%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.56%   |
| Intel Core i3-10100T CPU @ 3.00GHz            | 2         | 0.56%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.56%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.56%   |
| Intel Celeron CPU N3150 @ 1.60GHz             | 2         | 0.56%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.56%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+    | 2         | 0.56%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+    | 2         | 0.56%   |
| AMD Athlon 3000G with Radeon Vega Graphics    | 2         | 0.56%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz         | 1         | 0.28%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz            | 1         | 0.28%   |
| Intel Xeon D-2177NT CPU @ 1.90GHz             | 1         | 0.28%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.28%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz           | 1         | 0.28%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz           | 1         | 0.28%   |
| Intel Xeon CPU D-1518 @ 2.20GHz               | 1         | 0.28%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.28%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.28%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz        | 1         | 0.28%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.28%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.28%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1         | 0.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 92        | 25.77%  |
| Intel Core i3           | 86        | 24.09%  |
| Other                   | 22        | 6.16%   |
| AMD Ryzen 5             | 21        | 5.88%   |
| Intel Core i7           | 19        | 5.32%   |
| Intel Pentium           | 16        | 4.48%   |
| Intel Celeron           | 16        | 4.48%   |
| AMD Ryzen 7             | 8         | 2.24%   |
| Intel Xeon Silver       | 6         | 1.68%   |
| Intel Pentium Gold      | 6         | 1.68%   |
| Intel Pentium Dual-Core | 6         | 1.68%   |
| Intel Core 2 Duo        | 6         | 1.68%   |
| Intel Xeon              | 5         | 1.4%    |
| AMD Athlon 64 X2        | 5         | 1.4%    |
| AMD A8                  | 5         | 1.4%    |
| Intel Atom              | 3         | 0.84%   |
| Intel Pentium Silver    | 2         | 0.56%   |
| Intel Genuine           | 2         | 0.56%   |
| Intel Core i9           | 2         | 0.56%   |
| Intel Core 2 Quad       | 2         | 0.56%   |
| AMD Ryzen 3             | 2         | 0.56%   |
| AMD Phenom II X4        | 2         | 0.56%   |
| AMD FX                  | 2         | 0.56%   |
| AMD Athlon              | 2         | 0.56%   |
| AMD A6                  | 2         | 0.56%   |
| AMD A10                 | 2         | 0.56%   |
| Intel Xeon Gold         | 1         | 0.28%   |
| Intel Pentium D         | 1         | 0.28%   |
| Intel Pentium 4         | 1         | 0.28%   |
| Intel Core m5           | 1         | 0.28%   |
| Intel Core Duo          | 1         | 0.28%   |
| Intel Core 2 Solo       | 1         | 0.28%   |
| Intel Celeron Dual-Core | 1         | 0.28%   |
| CentaurHauls VIA C7     | 1         | 0.28%   |
| AMD Turion 64 X2 Mobile | 1         | 0.28%   |
| AMD Sempron             | 1         | 0.28%   |
| AMD Ryzen 7 PRO         | 1         | 0.28%   |
| AMD Ryzen 5 PRO         | 1         | 0.28%   |
| AMD E1                  | 1         | 0.28%   |
| AMD E                   | 1         | 0.28%   |
| AMD Athlon II X4        | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 156       | 43.7%   |
| 4      | 112       | 31.37%  |
| 6      | 54        | 15.13%  |
| 8      | 14        | 3.92%   |
| 1      | 7         | 1.96%   |
| 20     | 5         | 1.4%    |
| 32     | 2         | 0.56%   |
| 16     | 2         | 0.56%   |
| 3      | 2         | 0.56%   |
| 18     | 1         | 0.28%   |
| 14     | 1         | 0.28%   |
| 10     | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 345       | 96.91%  |
| 2      | 9         | 2.53%   |
| 4      | 2         | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 251       | 70.51%  |
| 1      | 105       | 29.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 347       | 97.47%  |
| Unknown        | 5         | 1.4%    |
| 32-bit         | 4         | 1.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x506e3    | 49        | 13.65%  |
| Unknown    | 48        | 13.37%  |
| 0x906ea    | 31        | 8.64%   |
| 0x806e9    | 18        | 5.01%   |
| 0x806c1    | 14        | 3.9%    |
| 0x906e9    | 13        | 3.62%   |
| 0x1067a    | 13        | 3.62%   |
| 0x08001138 | 13        | 3.62%   |
| 0x806ec    | 12        | 3.34%   |
| 0x806ea    | 11        | 3.06%   |
| 0x806eb    | 10        | 2.79%   |
| 0xa0653    | 9         | 2.51%   |
| 0x306a9    | 9         | 2.51%   |
| 0xa0660    | 8         | 2.23%   |
| 0x50657    | 8         | 2.23%   |
| 0x08108109 | 7         | 1.95%   |
| 0x906eb    | 6         | 1.67%   |
| 0x206a7    | 6         | 1.67%   |
| 0x906ed    | 5         | 1.39%   |
| 0x706e5    | 5         | 1.39%   |
| 0x506c9    | 4         | 1.11%   |
| 0x406e3    | 4         | 1.11%   |
| 0x08600106 | 3         | 0.84%   |
| 0x06001119 | 3         | 0.84%   |
| 0xa0671    | 2         | 0.56%   |
| 0x706a8    | 2         | 0.56%   |
| 0x406c4    | 2         | 0.56%   |
| 0x406c3    | 2         | 0.56%   |
| 0x40651    | 2         | 0.56%   |
| 0x306c3    | 2         | 0.56%   |
| 0x30679    | 2         | 0.56%   |
| 0x30678    | 2         | 0.56%   |
| 0x08701021 | 2         | 0.56%   |
| 0x08108102 | 2         | 0.56%   |
| 0x010000db | 2         | 0.56%   |
| 0xf47      | 1         | 0.28%   |
| 0xf29      | 1         | 0.28%   |
| 0xa0652    | 1         | 0.28%   |
| 0x706a1    | 1         | 0.28%   |
| 0x6fb      | 1         | 0.28%   |
| 0x6ec      | 1         | 0.28%   |
| 0x506e8    | 1         | 0.28%   |
| 0x50654    | 1         | 0.28%   |
| 0x306f2    | 1         | 0.28%   |
| 0x306e4    | 1         | 0.28%   |
| 0x206c2    | 1         | 0.28%   |
| 0x20655    | 1         | 0.28%   |
| 0x20652    | 1         | 0.28%   |
| 0x106ca    | 1         | 0.28%   |
| 0x106c2    | 1         | 0.28%   |
| 0x10676    | 1         | 0.28%   |
| 0x10661    | 1         | 0.28%   |
| 0x0a50000c | 1         | 0.28%   |
| 0x08600104 | 1         | 0.28%   |
| 0x0810100b | 1         | 0.28%   |
| 0x0800820d | 1         | 0.28%   |
| 0x08001129 | 1         | 0.28%   |
| 0x07030105 | 1         | 0.28%   |
| 0x0700010f | 1         | 0.28%   |
| 0x06000852 | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 118       | 33.15%  |
| Skylake       | 65        | 18.26%  |
| CometLake     | 19        | 5.34%   |
| TigerLake     | 16        | 4.49%   |
| Zen           | 15        | 4.21%   |
| Penryn        | 15        | 4.21%   |
| Zen+          | 11        | 3.09%   |
| IvyBridge     | 11        | 3.09%   |
| Silvermont    | 9         | 2.53%   |
| SandyBridge   | 9         | 2.53%   |
| Unknown       | 8         | 2.25%   |
| Zen 2         | 7         | 1.97%   |
| K8 Hammer     | 7         | 1.97%   |
| Piledriver    | 6         | 1.69%   |
| Haswell       | 6         | 1.69%   |
| IceLake       | 5         | 1.4%    |
| Goldmont      | 4         | 1.12%   |
| Westmere      | 3         | 0.84%   |
| K10           | 3         | 0.84%   |
| Goldmont plus | 3         | 0.84%   |
| Steamroller   | 2         | 0.56%   |
| NetBurst      | 2         | 0.56%   |
| K10 Llano     | 2         | 0.56%   |
| Core          | 2         | 0.56%   |
| Bonnell       | 2         | 0.56%   |
| Zen 3         | 1         | 0.28%   |
| Puma          | 1         | 0.28%   |
| P6            | 1         | 0.28%   |
| Jaguar        | 1         | 0.28%   |
| Broadwell     | 1         | 0.28%   |
| Bobcat        | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 256       | 66.32%  |
| Nvidia                     | 78        | 20.21%  |
| AMD                        | 38        | 9.84%   |
| Matrox Electronics Systems | 5         | 1.3%    |
| ASPEED Technology          | 4         | 1.04%   |
| Silicon Motion             | 2         | 0.52%   |
| Huawei Technologies        | 2         | 0.52%   |
| VIA Technologies           | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                     | Computers | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                                                     | 45        | 11.48%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                 | 29        | 7.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                | 24        | 6.12%   |
| Intel HD Graphics 620                                                                     | 24        | 6.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                        | 16        | 4.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                 | 13        | 3.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                 | 11        | 2.81%   |
| Intel HD Graphics 610                                                                     | 10        | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                      | 10        | 2.55%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                     | 9         | 2.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                  | 9         | 2.3%    |
| Intel Comet Lake UHD Graphics                                                             | 8         | 2.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                 | 8         | 2.04%   |
| Intel HD Graphics 510                                                                     | 6         | 1.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                          | 6         | 1.53%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                         | 5         | 1.28%   |
| Intel UHD Graphics 620                                                                    | 5         | 1.28%   |
| Intel HD Graphics 630                                                                     | 5         | 1.28%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                          | 5         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller  | 5         | 1.28%   |
| AMD Renoir                                                                                | 5         | 1.28%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                 | 4         | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                              | 4         | 1.02%   |
| ASPEED Technology ASPEED Graphics Family                                                  | 4         | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                                            | 3         | 0.77%   |
| Nvidia GF108 [GeForce GT 630]                                                             | 3         | 0.77%   |
| Intel Tiger Lake UHD Graphics                                                             | 3         | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                    | 3         | 0.77%   |
| Intel HD Graphics 500                                                                     | 3         | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                 | 3         | 0.77%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                         | 3         | 0.77%   |
| Silicon Motion SM718 LynxSE+                                                              | 2         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                                | 2         | 0.51%   |
| Nvidia GM108M [GeForce 940MX]                                                             | 2         | 0.51%   |
| Nvidia GK107M [GeForce GT 650M]                                                           | 2         | 0.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                       | 2         | 0.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                              | 2         | 0.51%   |
| Intel Iris Plus Graphics G7                                                               | 2         | 0.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                          | 2         | 0.51%   |
| Intel GeminiLake [UHD Graphics 605]                                                       | 2         | 0.51%   |
| Huawei Technologies Hi171x Series [iBMC Intelligent Management system chip w/VGA support] | 2         | 0.51%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                     | 2         | 0.51%   |
| AMD Kaveri [Radeon R7 Graphics]                                                           | 2         | 0.51%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                         | 1         | 0.26%   |
| Nvidia TU117M [GeForce MX450]                                                             | 1         | 0.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                                | 1         | 0.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                           | 1         | 0.26%   |
| Nvidia TU117M                                                                             | 1         | 0.26%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                     | 1         | 0.26%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                   | 1         | 0.26%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                     | 1         | 0.26%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                      | 1         | 0.26%   |
| Nvidia MCP89 [GeForce 320M]                                                               | 1         | 0.26%   |
| Nvidia GT218 [GeForce 210]                                                                | 1         | 0.26%   |
| Nvidia GT216M [GeForce GT 330M]                                                           | 1         | 0.26%   |
| Nvidia GP108M [GeForce MX330]                                                             | 1         | 0.26%   |
| Nvidia GP108M [GeForce MX150]                                                             | 1         | 0.26%   |
| Nvidia GP108BM [GeForce MX250]                                                            | 1         | 0.26%   |
| Nvidia GP107 [GeForce GTX 1050]                                                           | 1         | 0.26%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                       | 1         | 0.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 227       | 63.76%  |
| 1 x Nvidia              | 50        | 14.04%  |
| 1 x AMD                 | 28        | 7.87%   |
| Intel + Nvidia          | 25        | 7.02%   |
| 1 x Matrox              | 5         | 1.4%    |
| 2 x AMD                 | 4         | 1.12%   |
| 1 x ASPEED              | 4         | 1.12%   |
| Other                   | 3         | 0.84%   |
| AMD + Nvidia            | 3         | 0.84%   |
| 1 x Silicon Motion      | 2         | 0.56%   |
| Intel + AMD             | 2         | 0.56%   |
| 1 x Huawei Technologies | 2         | 0.56%   |
| 1 x VIA                 | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 298       | 83.01%  |
| Proprietary | 44        | 12.26%  |
| Unknown     | 17        | 4.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 267       | 74.37%  |
| 3.01-4.0   | 29        | 8.08%   |
| 0.01-0.5   | 23        | 6.41%   |
| 0.51-1.0   | 20        | 5.57%   |
| 1.01-2.0   | 16        | 4.46%   |
| 7.01-8.0   | 1         | 0.28%   |
| 5.01-6.0   | 1         | 0.28%   |
| 2.01-3.0   | 1         | 0.28%   |
| 8.01-16.0  | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| HHT                     | 43        | 11.94%  |
| BOE                     | 37        | 10.28%  |
| Samsung Electronics     | 30        | 8.33%   |
| Chimei Innolux          | 27        | 7.5%    |
| Acer                    | 26        | 7.22%   |
| AU Optronics            | 24        | 6.67%   |
| AOC                     | 23        | 6.39%   |
| ECS                     | 21        | 5.83%   |
| BenQ                    | 21        | 5.83%   |
| LG Display              | 16        | 4.44%   |
| Lenovo                  | 12        | 3.33%   |
| ViewSonic               | 8         | 2.22%   |
| Goldstar                | 8         | 2.22%   |
| Dell                    | 7         | 1.94%   |
| Philips                 | 5         | 1.39%   |
| Chi Mei Optoelectronics | 5         | 1.39%   |
| Sharp                   | 4         | 1.11%   |
| PRW                     | 4         | 1.11%   |
| PANDA                   | 4         | 1.11%   |
| WBT                     | 3         | 0.83%   |
| LG Electronics          | 3         | 0.83%   |
| Apple                   | 3         | 0.83%   |
| Ancor Communications    | 3         | 0.83%   |
| STD                     | 2         | 0.56%   |
| JRY                     | 2         | 0.56%   |
| Hewlett-Packard         | 2         | 0.56%   |
| CHR                     | 2         | 0.56%   |
| VIE                     | 1         | 0.28%   |
| Toshiba                 | 1         | 0.28%   |
| STA                     | 1         | 0.28%   |
| SKG                     | 1         | 0.28%   |
| RTK                     | 1         | 0.28%   |
| PRM                     | 1         | 0.28%   |
| Panasonic               | 1         | 0.28%   |
| KDC                     | 1         | 0.28%   |
| Iiyama                  | 1         | 0.28%   |
| Hitachi                 | 1         | 0.28%   |
| HIB                     | 1         | 0.28%   |
| HannStar                | 1         | 0.28%   |
| DZW                     | 1         | 0.28%   |
| ASUSTek Computer        | 1         | 0.28%   |
| Unknown                 | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| HHT ActviPanel V5 HHT0030 3840x2160 944x398mm 40.3-inch              | 43        | 11.72%  |
| ECS AIO PC ECS2486 1920x1080 520x300mm 23.6-inch                     | 21        | 5.72%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 12        | 3.27%   |
| AOC LCD Monitor 2778X 2560x1440                                      | 11        | 3%      |
| Lenovo LEN-V5S5W-B-A LENE288 1920x1080 527x296mm 23.8-inch           | 10        | 2.72%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                    | 10        | 2.72%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch     | 9         | 2.45%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                       | 8         | 2.18%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                | 6         | 1.63%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 5         | 1.36%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 5         | 1.36%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch       | 5         | 1.36%   |
| PRW AP7_Titanium PRW4200 3840x2160                                   | 4         | 1.09%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                     | 3         | 0.82%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch        | 3         | 0.82%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 3         | 0.82%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 3         | 0.82%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 3         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 0.82%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.82%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                     | 3         | 0.82%   |
| Acer AIO LCD ACRF132 1920x1080 509x286mm 23.0-inch                   | 3         | 0.82%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch        | 2         | 0.54%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch          | 2         | 0.54%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                        | 2         | 0.54%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch    | 2         | 0.54%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 2         | 0.54%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch               | 2         | 0.54%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                    | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch     | 2         | 0.54%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                | 2         | 0.54%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.54%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                   | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO133C 1366x768 309x173mm 13.9-inch        | 2         | 0.54%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                      | 2         | 0.54%   |
| ViewSonic VA1916wSERIES VSCF91F 1440x900 410x256mm 19.0-inch         | 1         | 0.27%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                | 1         | 0.27%   |
| Toshiba LCD Monitor TV 1920x1080                                     | 1         | 0.27%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                | 1         | 0.27%   |
| SKG 86 Monitor SKG8600 3840x2160 1650x928mm 74.5-inch                | 1         | 0.27%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch               | 1         | 0.27%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch | 1         | 0.27%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 0.27%   |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 459x296mm 21.5-inch  | 1         | 0.27%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch    | 1         | 0.27%   |
| Samsung Electronics S24D590 SAM0B46 1920x1080 521x293mm 23.5-inch    | 1         | 0.27%   |
| Samsung Electronics S24B370 SAM08DE 1920x1080 531x299mm 24.0-inch    | 1         | 0.27%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch    | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SEC4754 1280x800 261x163mm 12.1-inch | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 261x163mm 12.1-inch | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 0.27%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch | 1         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 196       | 55.52%  |
| 3840x2160 (4K)     | 52        | 14.73%  |
| 1366x768 (WXGA)    | 31        | 8.78%   |
| 2560x1440 (QHD)    | 25        | 7.08%   |
| 1280x1024 (SXGA)   | 20        | 5.67%   |
| 1600x900 (HD+)     | 8         | 2.27%   |
| 1440x900 (WXGA+)   | 5         | 1.42%   |
| 1280x800 (WXGA)    | 5         | 1.42%   |
| 1680x1050 (WSXGA+) | 3         | 0.85%   |
| 1920x1200 (WUXGA)  | 2         | 0.57%   |
| Unknown            | 2         | 0.57%   |
| 4480x1440          | 1         | 0.28%   |
| 2560x1600          | 1         | 0.28%   |
| 1400x1050          | 1         | 0.28%   |
| 1360x768           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 72        | 20.11%  |
| 23      | 56        | 15.64%  |
| 40      | 43        | 12.01%  |
| 24      | 33        | 9.22%   |
| 17      | 27        | 7.54%   |
| Unknown | 25        | 6.98%   |
| 14      | 20        | 5.59%   |
| 21      | 17        | 4.75%   |
| 13      | 15        | 4.19%   |
| 19      | 13        | 3.63%   |
| 27      | 9         | 2.51%   |
| 26      | 6         | 1.68%   |
| 31      | 4         | 1.12%   |
| 11      | 3         | 0.84%   |
| 22      | 2         | 0.56%   |
| 20      | 2         | 0.56%   |
| 12      | 2         | 0.56%   |
| 74      | 1         | 0.28%   |
| 72      | 1         | 0.28%   |
| 59      | 1         | 0.28%   |
| 46      | 1         | 0.28%   |
| 33      | 1         | 0.28%   |
| 32      | 1         | 0.28%   |
| 28      | 1         | 0.28%   |
| 18      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 31.64%  |
| 501-600     | 101       | 28.53%  |
| 901-1000    | 43        | 12.15%  |
| 401-500     | 27        | 7.63%   |
| Unknown     | 25        | 7.06%   |
| 351-400     | 22        | 6.21%   |
| 201-300     | 12        | 3.39%   |
| 601-700     | 6         | 1.69%   |
| 701-800     | 2         | 0.56%   |
| 1501-2000   | 2         | 0.56%   |
| 1001-1500   | 2         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 240       | 69.57%  |
| 21/9    | 43        | 12.46%  |
| Unknown | 20        | 5.8%    |
| 16/10   | 19        | 5.51%   |
| 5/4     | 17        | 4.93%   |
| 3/2     | 3         | 0.87%   |
| 4/3     | 2         | 0.58%   |
| 6/5     | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 98        | 27.61%  |
| 101-110        | 72        | 20.28%  |
| 501-1000       | 44        | 12.39%  |
| 81-90          | 30        | 8.45%   |
| Unknown        | 25        | 7.04%   |
| 151-200        | 18        | 5.07%   |
| 121-130        | 16        | 4.51%   |
| 301-350        | 15        | 4.23%   |
| 141-150        | 12        | 3.38%   |
| 351-500        | 7         | 1.97%   |
| 71-80          | 5         | 1.41%   |
| 251-300        | 4         | 1.13%   |
| More than 1000 | 3         | 0.85%   |
| 51-60          | 3         | 0.85%   |
| 61-70          | 2         | 0.56%   |
| 41-50          | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 124       | 35.13%  |
| 121-160 | 102       | 28.9%   |
| 101-120 | 91        | 25.78%  |
| Unknown | 25        | 7.08%   |
| 161-240 | 6         | 1.7%    |
| 1-50    | 5         | 1.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 317       | 88.06%  |
| 2     | 24        | 6.67%   |
| 0     | 17        | 4.72%   |
| 3     | 2         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 248       | 46.97%  |
| Intel                           | 186       | 35.23%  |
| Qualcomm Atheros                | 34        | 6.44%   |
| Broadcom                        | 12        | 2.27%   |
| Nvidia                          | 9         | 1.7%    |
| D-Link                          | 8         | 1.52%   |
| IBM                             | 5         | 0.95%   |
| Ralink                          | 3         | 0.57%   |
| Microchip Technology            | 3         | 0.57%   |
| Ralink Technology               | 2         | 0.38%   |
| MCST                            | 2         | 0.38%   |
| Broadcom Limited                | 2         | 0.38%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.19%   |
| Xiaomi                          | 1         | 0.19%   |
| Vimtron Electronics             | 1         | 0.19%   |
| VIA Technologies                | 1         | 0.19%   |
| TP-Link                         | 1         | 0.19%   |
| Sierra Wireless                 | 1         | 0.19%   |
| Qualcomm Atheros Communications | 1         | 0.19%   |
| Micro Star International        | 1         | 0.19%   |
| MediaTek                        | 1         | 0.19%   |
| Marvell Technology Group        | 1         | 0.19%   |
| JMicron Technology              | 1         | 0.19%   |
| Exar                            | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |
| ASIX Electronics                | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 176       | 27.72%  |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 43        | 6.77%   |
| Intel Ethernet Connection I219-LM                                       | 33        | 5.2%    |
| Intel Ethernet Connection (2) I219-LM                                   | 17        | 2.68%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.52%   |
| Intel Wireless 8265 / 8275                                              | 15        | 2.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 1.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.73%   |
| Intel Wireless 3165                                                     | 10        | 1.57%   |
| Intel Ethernet Connection (13) I219-V                                   | 10        | 1.57%   |
| Intel Ethernet Connection (7) I219-LM                                   | 9         | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 1.26%   |
| Intel Ethernet Connection (10) I219-V                                   | 8         | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 1.1%    |
| Intel Wireless 7265                                                     | 7         | 1.1%    |
| Intel Ethernet Connection X722 for 1GbE                                 | 7         | 1.1%    |
| Intel Ethernet Connection X722 for 10GBASE-T                            | 6         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.79%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 0.79%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                           | 5         | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.79%   |
| IBM RNDIS/CDC ETHER                                                     | 5         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.63%   |
| Intel I350 Gigabit Network Connection                                   | 4         | 0.63%   |
| Intel I210 Gigabit Network Connection                                   | 4         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.63%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                | 4         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.47%   |
| Nvidia MCP51 Ethernet Controller                                        | 3         | 0.47%   |
| Microchip MCP2221 USB-I2C/UART Combo                                    | 3         | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.47%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                   | 3         | 0.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.47%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]            | 3         | 0.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.31%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.31%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.31%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.31%   |
| MCST Gigabit Ethernet Controller                                        | 2         | 0.31%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.31%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.31%   |
| Intel WiMAX Connection 2400m                                            | 2         | 0.31%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                           | 2         | 0.31%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 58.05%  |
| Realtek Semiconductor           | 38        | 18.54%  |
| Qualcomm Atheros                | 25        | 12.2%   |
| Broadcom                        | 11        | 5.37%   |
| Ralink                          | 3         | 1.46%   |
| Ralink Technology               | 2         | 0.98%   |
| TP-Link                         | 1         | 0.49%   |
| Sierra Wireless                 | 1         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| Micro Star International        | 1         | 0.49%   |
| MediaTek                        | 1         | 0.49%   |
| D-Link                          | 1         | 0.49%   |
| ASUSTek Computer                | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 16        | 7.77%   |
| Intel Wireless 8265 / 8275                                              | 15        | 7.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 5.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 5.83%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 5.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 5.34%   |
| Intel Wireless 3165                                                     | 10        | 4.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 3.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 3.88%   |
| Intel Wireless 7265                                                     | 7         | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.46%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.97%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.97%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.97%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.49%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.49%   |
| Realtek Realtek Network controller                                      | 1         | 0.49%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.49%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.49%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.49%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.49%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1         | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.49%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.49%   |
| Micro Star International RT2573                                         | 1         | 0.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.49%   |
| Intel Wireless 8260                                                     | 1         | 0.49%   |
| Intel Wireless 7260                                                     | 1         | 0.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.49%   |
| Intel Centrino Wireless-N 105                                           | 1         | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.49%   |
| D-Link DWL-G132 [Atheros AR5523]                                        | 1         | 0.49%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 0.49%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 0.49%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.49%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.49%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 238       | 59.2%   |
| Intel                      | 114       | 28.36%  |
| Qualcomm Atheros           | 15        | 3.73%   |
| Nvidia                     | 9         | 2.24%   |
| D-Link                     | 7         | 1.74%   |
| IBM                        | 5         | 1.24%   |
| Broadcom                   | 3         | 0.75%   |
| MCST                       | 2         | 0.5%    |
| Broadcom Limited           | 2         | 0.5%    |
| ZTE WCDMA Technologies MSM | 1         | 0.25%   |
| Xiaomi                     | 1         | 0.25%   |
| Vimtron Electronics        | 1         | 0.25%   |
| VIA Technologies           | 1         | 0.25%   |
| Marvell Technology Group   | 1         | 0.25%   |
| JMicron Technology         | 1         | 0.25%   |
| ASIX Electronics           | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 176       | 41.41%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43        | 10.12%  |
| Intel Ethernet Connection I219-LM                                 | 33        | 7.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 4%      |
| Intel Ethernet Connection (13) I219-V                             | 10        | 2.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.88%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 1.65%   |
| Intel Ethernet Connection X722 for 1GbE                           | 7         | 1.65%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 6         | 1.41%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 5         | 1.18%   |
| IBM RNDIS/CDC ETHER                                               | 5         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.94%   |
| Intel I350 Gigabit Network Connection                             | 4         | 0.94%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.94%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 0.94%   |
| Nvidia MCP51 Ethernet Controller                                  | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.71%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.71%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 3         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.47%   |
| MCST Gigabit Ethernet Controller                                  | 2         | 0.47%   |
| Intel WiMAX Connection 2400m                                      | 2         | 0.47%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 2         | 0.47%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 2         | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.47%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 1         | 0.24%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.24%   |
| Vimtron Mobile Composite Device Bus                               | 1         | 0.24%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.24%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.24%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.24%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.24%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.24%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.24%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.24%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.24%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.24%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.24%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.24%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.24%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.24%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 0.24%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.24%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.24%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.24%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.24%   |
| Intel Ethernet Connection X552 10 GbE SFP+                        | 1         | 0.24%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.24%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 337       | 62.41%  |
| WiFi     | 199       | 36.85%  |
| Modem    | 4         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 200       | 55.71%  |
| WiFi     | 159       | 44.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 171       | 48.03%  |
| 1     | 166       | 46.63%  |
| 0     | 6         | 1.69%   |
| 6     | 5         | 1.4%    |
| 4     | 3         | 0.84%   |
| 3     | 2         | 0.56%   |
| 13    | 1         | 0.28%   |
| 12    | 1         | 0.28%   |
| 8     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 344       | 96.63%  |
| Yes  | 12        | 3.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 68.48%  |
| Realtek Semiconductor           | 11        | 6.67%   |
| IMC Networks                    | 7         | 4.24%   |
| Cambridge Silicon Radio         | 6         | 3.64%   |
| Broadcom                        | 6         | 3.64%   |
| Lite-On Technology              | 5         | 3.03%   |
| Qualcomm Atheros Communications | 4         | 2.42%   |
| Foxconn / Hon Hai               | 3         | 1.82%   |
| Hewlett-Packard                 | 2         | 1.21%   |
| ASUSTek Computer                | 2         | 1.21%   |
| Toshiba                         | 1         | 0.61%   |
| Realtek                         | 1         | 0.61%   |
| Ralink                          | 1         | 0.61%   |
| Logitech                        | 1         | 0.61%   |
| Chicony Electronics             | 1         | 0.61%   |
| Apple                           | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 23.03%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 33        | 20%     |
| Intel AX200 Bluetooth                               | 16        | 9.7%    |
| Intel Bluetooth Device                              | 15        | 9.09%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 4.85%   |
| Realtek Bluetooth Radio                             | 6         | 3.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 3.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 1.82%   |
| IMC Networks Bluetooth Device                       | 3         | 1.82%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.21%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.21%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.61%   |
| Realtek Bluetooth Radio                             | 1         | 0.61%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.61%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.61%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.61%   |
| Lite-On Bluetooth Radio                             | 1         | 0.61%   |
| Intel AX210 Bluetooth                               | 1         | 0.61%   |
| IMC Networks Wireless_Device                        | 1         | 0.61%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.61%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.61%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.61%   |
| Broadcom Bluetooth dongle                           | 1         | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.61%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.61%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.61%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.61%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.61%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 0.61%   |
| Apple Bluetooth Host Controller                     | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 278       | 66.99%  |
| Nvidia                 | 63        | 15.18%  |
| AMD                    | 54        | 13.01%  |
| C-Media Electronics    | 6         | 1.45%   |
| VIA Technologies       | 2         | 0.48%   |
| Realtek Semiconductor  | 2         | 0.48%   |
| MCST                   | 2         | 0.48%   |
| Apple                  | 2         | 0.48%   |
| JMTek                  | 1         | 0.24%   |
| Generalplus Technology | 1         | 0.24%   |
| EasyPass Industrial    | 1         | 0.24%   |
| Creative Technology    | 1         | 0.24%   |
| Creative Labs          | 1         | 0.24%   |
| A4Tech                 | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 66        | 14.77%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 7.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 29        | 6.49%   |
| Intel 200 Series PCH HD Audio                                                                     | 29        | 6.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 26        | 5.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 3.8%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 3.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 3.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 3.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 2.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.46%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 1.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.12%   |
| Intel Audio device                                                                                | 5         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.89%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.89%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 0.89%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 0.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.67%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.45%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.45%   |
| Nvidia MCP51 High Definition Audio                                                                | 2         | 0.45%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Nvidia Audio device                                                                               | 2         | 0.45%   |
| MCST HD Audio                                                                                     | 2         | 0.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.45%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.45%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.45%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.45%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.22%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.22%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.22%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.22%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.22%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.22%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.22%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.22%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.22%   |
| Nvidia MCP51 AC97 Audio Controller                                                                | 1         | 0.22%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 19.67%  |
| Crucial             | 59        | 19.34%  |
| SK hynix            | 44        | 14.43%  |
| Kingston            | 30        | 9.84%   |
| Unknown             | 29        | 9.51%   |
| Micron Technology   | 23        | 7.54%   |
| Ramaxel Technology  | 14        | 4.59%   |
| Foxline             | 10        | 3.28%   |
| Apacer              | 5         | 1.64%   |
| A-DATA Technology   | 5         | 1.64%   |
| Elpida              | 4         | 1.31%   |
| Patriot             | 3         | 0.98%   |
| Unknown (ABCD)      | 2         | 0.66%   |
| Goodram             | 2         | 0.66%   |
| Goldkey             | 2         | 0.66%   |
| Corsair             | 2         | 0.66%   |
| Unknown             | 2         | 0.66%   |
| Unknown (0x0B7A)    | 1         | 0.33%   |
| tigo                | 1         | 0.33%   |
| Shenzhen Longsys    | 1         | 0.33%   |
| SHARETRONIC         | 1         | 0.33%   |
| Qumo                | 1         | 0.33%   |
| Juhor               | 1         | 0.33%   |
| G.Skill             | 1         | 0.33%   |
| ATLA                | 1         | 0.33%   |
| AMD                 | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFRA266.M8FRS 8192MB SODIMM DDR4 2667MT/s          | 17        | 5.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 13        | 4.06%   |
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s                | 13        | 4.06%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 10        | 3.13%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                            | 10        | 3.13%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 9         | 2.81%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s                 | 7         | 2.19%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 5         | 1.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 5         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 1.25%   |
| Samsung RAM M393A2K43CB2-CVF 16384MB DIMM DDR4 2933MT/s             | 4         | 1.25%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s              | 4         | 1.25%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s              | 4         | 1.25%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 3         | 0.94%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 3         | 0.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 0.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.94%   |
| Crucial RAM CT8G4SFRA266.C16FG 8GB SODIMM DDR4 2667MT/s             | 3         | 0.94%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s              | 3         | 0.94%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 2         | 0.63%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 2         | 0.63%   |
| Unknown RAM Module 1024MB DIMM                                      | 2         | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.63%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 2         | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 0.63%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 2933MT/s                 | 2         | 0.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 0.63%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s               | 2         | 0.63%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s             | 2         | 0.63%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s            | 2         | 0.63%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s              | 2         | 0.63%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s             | 2         | 0.63%   |
| Unknown                                                             | 2         | 0.63%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                        | 1         | 0.31%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                        | 1         | 0.31%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                           | 1         | 0.31%   |
| Unknown RAM Module 512MB DIMM 400MT/s                               | 1         | 0.31%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.31%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                            | 1         | 0.31%   |
| Unknown RAM Module 4096MB DIMM 333MT/s                              | 1         | 0.31%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 1         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.31%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s                        | 1         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 1         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                         | 1         | 0.31%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 1         | 0.31%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                 | 1         | 0.31%   |
| Unknown RAM Module 1024MB SODIMM DDR2 333MT/s                       | 1         | 0.31%   |
| Unknown RAM Module 1024MB DIMM SDRAM 533MT/s                        | 1         | 0.31%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                | 1         | 0.31%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                         | 1         | 0.31%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                          | 1         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 208       | 71.23%  |
| DDR3    | 48        | 16.44%  |
| DDR2    | 12        | 4.11%   |
| Unknown | 12        | 4.11%   |
| LPDDR4  | 7         | 2.4%    |
| SDRAM   | 3         | 1.03%   |
| DRAM    | 1         | 0.34%   |
| DDR     | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 171       | 58.36%  |
| DIMM         | 113       | 38.57%  |
| Row Of Chips | 9         | 3.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 137       | 45.51%  |
| 4096  | 104       | 34.55%  |
| 2048  | 21        | 6.98%   |
| 16384 | 20        | 6.64%   |
| 1024  | 12        | 3.99%   |
| 512   | 4         | 1.33%   |
| 32768 | 2         | 0.66%   |
| 65536 | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 92        | 30.07%  |
| 2400    | 51        | 16.67%  |
| 1600    | 34        | 11.11%  |
| 3200    | 28        | 9.15%   |
| 2133    | 23        | 7.52%   |
| 2933    | 12        | 3.92%   |
| Unknown | 9         | 2.94%   |
| 1333    | 8         | 2.61%   |
| 667     | 7         | 2.29%   |
| 1334    | 6         | 1.96%   |
| 3266    | 5         | 1.63%   |
| 800     | 5         | 1.63%   |
| 400     | 3         | 0.98%   |
| 333     | 3         | 0.98%   |
| 4267    | 2         | 0.65%   |
| 2866    | 2         | 0.65%   |
| 2666    | 2         | 0.65%   |
| 533     | 2         | 0.65%   |
| 4333    | 1         | 0.33%   |
| 3534    | 1         | 0.33%   |
| 3533    | 1         | 0.33%   |
| 3466    | 1         | 0.33%   |
| 3333    | 1         | 0.33%   |
| 3151    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 1867    | 1         | 0.33%   |
| 1866    | 1         | 0.33%   |
| 1067    | 1         | 0.33%   |
| 1066    | 1         | 0.33%   |
| 32      | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 33.33%  |
| Hewlett-Packard     | 3         | 25%     |
| Canon               | 2         | 16.67%  |
| QinHeng Electronics | 1         | 8.33%   |
| Pantum              | 1         | 8.33%   |
| Brother Industries  | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| HP LaserJet P1102              | 2         | 16.67%  |
| Samsung SCX-4200 series        | 1         | 8.33%   |
| Samsung SCX-3400 Series        | 1         | 8.33%   |
| Samsung SCX-3200 Series        | 1         | 8.33%   |
| Samsung M332x 382x 402x Series | 1         | 8.33%   |
| QinHeng CH340S                 | 1         | 8.33%   |
| Pantum P2200 series            | 1         | 8.33%   |
| HP LaserJet M402dn             | 1         | 8.33%   |
| Canon MF4410                   | 1         | 8.33%   |
| Canon MF4010 series            | 1         | 8.33%   |
| Brother HL-L2300D series       | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 48        | 25.26%  |
| Cheng Uei Precision Industry (Foxlink) | 28        | 14.74%  |
| Alcor Micro                            | 24        | 12.63%  |
| IMC Networks                           | 16        | 8.42%   |
| Logitech                               | 14        | 7.37%   |
| Sunplus Innovation Technology          | 8         | 4.21%   |
| Acer                                   | 8         | 4.21%   |
| Realtek Semiconductor                  | 7         | 3.68%   |
| Quanta                                 | 6         | 3.16%   |
| Suyin                                  | 5         | 2.63%   |
| Microdia                               | 5         | 2.63%   |
| Syntek                                 | 3         | 1.58%   |
| lihappe8                               | 3         | 1.58%   |
| Apple                                  | 3         | 1.58%   |
| Z-Star Microelectronics                | 2         | 1.05%   |
| Lite-On Technology                     | 2         | 1.05%   |
| Unknown                                | 1         | 0.53%   |
| SunplusIT                              | 1         | 0.53%   |
| Sonix Technology                       | 1         | 0.53%   |
| Silicon Motion                         | 1         | 0.53%   |
| Ricoh                                  | 1         | 0.53%   |
| Primax Electronics                     | 1         | 0.53%   |
| Microsoft                              | 1         | 0.53%   |
| Hewlett-Packard                        | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 PC Camera                                  | 21        | 10.88%  |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 7.77%   |
| Chicony Integrated Camera                                      | 14        | 7.25%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 12        | 6.22%   |
| Logitech Webcam C270                                           | 9         | 4.66%   |
| Chicony HP HD Camera                                           | 9         | 4.66%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 3.11%   |
| Chicony USB2.0 Camera                                          | 6         | 3.11%   |
| Sunplus Integrated_Webcam_HD                                   | 5         | 2.59%   |
| Microdia Webcam Vitade AF                                      | 4         | 2.07%   |
| IMC Networks Integrated Camera                                 | 4         | 2.07%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.55%   |
| lihappe8 USB 2.0 Camera                                        | 3         | 1.55%   |
| Chicony USB2.0 FHD Camera                                      | 3         | 1.55%   |
| Acer BisonCam, NB Pro                                          | 3         | 1.55%   |
| Syntek Integrated Camera                                       | 2         | 1.04%   |
| Suyin 1.3M HD WebCam                                           | 2         | 1.04%   |
| Sunplus Asus Webcam                                            | 2         | 1.04%   |
| Microdia JOYACCESS JA-Webcam                                   | 2         | 1.04%   |
| Chicony VGA Webcam                                             | 2         | 1.04%   |
| Chicony USB camera                                             | 2         | 1.04%   |
| Chicony HD WebCam                                              | 2         | 1.04%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.04%   |
| Acer BisonCam,NB Pro                                           | 2         | 1.04%   |
| Z-Star Venus USB2.0 Camera                                     | 1         | 0.52%   |
| Z-Star Vega USB 2.0 Camera                                     | 1         | 0.52%   |
| Unknown USB2.0 Webcam                                          | 1         | 0.52%   |
| Syntek Lenovo EasyCamera                                       | 1         | 0.52%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.52%   |
| Suyin HP Truevision HD                                         | 1         | 0.52%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.52%   |
| SunplusIT MTD camera                                           | 1         | 0.52%   |
| Sunplus Integrated Camera                                      | 1         | 0.52%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 0.52%   |
| Silicon Motion WebCam SC-0311139N                              | 1         | 0.52%   |
| Ricoh USB2.0 Camera                                            | 1         | 0.52%   |
| Realtek USB2.0 camera                                          | 1         | 0.52%   |
| Realtek USB Camera                                             | 1         | 0.52%   |
| Realtek Lenovo EasyCamera                                      | 1         | 0.52%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 0.52%   |
| Realtek Integrated_Webcam_FHD                                  | 1         | 0.52%   |
| Realtek HP Wide Vision FHD Camera                              | 1         | 0.52%   |
| Realtek EasyCamera                                             | 1         | 0.52%   |
| Quanta VGA WebCam                                              | 1         | 0.52%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 0.52%   |
| Quanta HP Webcam                                               | 1         | 0.52%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 0.52%   |
| Microsoft LifeCam VX-700                                       | 1         | 0.52%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 0.52%   |
| Logitech Webcam C930e                                          | 1         | 0.52%   |
| Logitech HD Webcam C525                                        | 1         | 0.52%   |
| Logitech HD Pro Webcam C920                                    | 1         | 0.52%   |
| Logitech C505 HD Webcam                                        | 1         | 0.52%   |
| Logitech B525 HD Webcam                                        | 1         | 0.52%   |
| Lite-On HP Wide Vision HD Camera                               | 1         | 0.52%   |
| Lite-On HP Webcam                                              | 1         | 0.52%   |
| IMC Networks VGA UVC WebCam                                    | 1         | 0.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 1         | 0.52%   |
| IMC Networks USB 2.0 Camera                                    | 1         | 0.52%   |
| IMC Networks ov9734_azurewave_camera                           | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
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


| Model                                             | Computers | Percent |
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


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 75%     |
| Aktiv       | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 75%     |
| Aktiv Rutoken lite                  | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 304       | 83.98%  |
| 1     | 36        | 9.94%   |
| 2     | 10        | 2.76%   |
| 4     | 6         | 1.66%   |
| 5     | 4         | 1.1%    |
| 3     | 2         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 25        | 30.12%  |
| Graphics card            | 17        | 20.48%  |
| Fingerprint reader       | 13        | 15.66%  |
| Unassigned class         | 9         | 10.84%  |
| Multimedia controller    | 4         | 4.82%   |
| Chipcard                 | 4         | 4.82%   |
| Net/ethernet             | 3         | 3.61%   |
| Sound                    | 2         | 2.41%   |
| Net/wireless             | 2         | 2.41%   |
| Camera                   | 2         | 2.41%   |
| Bluetooth                | 2         | 2.41%   |

