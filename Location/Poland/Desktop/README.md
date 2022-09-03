Linux in Poland - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 2311

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | P5K/EPU                     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock        | N68C-S UCC                  | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Unknown       | Unknown                     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| ASRock        | X370 Gaming X               | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [72c01f3cf1](https://linux-hardware.org/?probe=72c01f3cf1) | Aug 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3b245a809d](https://linux-hardware.org/?probe=3b245a809d) | Aug 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [dcb225651d](https://linux-hardware.org/?probe=dcb225651d) | Aug 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| ASUSTek       | G15DK                       | [231c2674a6](https://linux-hardware.org/?probe=231c2674a6) | Aug 28, 2022 |
| ASUSTek       | P8B WS                      | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| HP            | 8054                        | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| ASRock        | N68C-GS4 FX                 | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | P5B                         | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| ASUSTek       | P7P55D-E                    | [7c83845247](https://linux-hardware.org/?probe=7c83845247) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [d39161dc13](https://linux-hardware.org/?probe=d39161dc13) | Aug 19, 2022 |
| ASUSTek       | A88XM-E                     | [04d716a25d](https://linux-hardware.org/?probe=04d716a25d) | Aug 19, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3d5404aaff](https://linux-hardware.org/?probe=3d5404aaff) | Aug 18, 2022 |
| ASRock        | H81M                        | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| ASUSTek       | M3A78-CM                    | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| ASUSTek       | P5K-E                       | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Gigabyte      | B460M DS3H V2               | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| Gigabyte      | H270-Gaming 3               | [434ba505a3](https://linux-hardware.org/?probe=434ba505a3) | Aug 12, 2022 |
| MSI           | B365M PRO-VDH               | [213778bd3c](https://linux-hardware.org/?probe=213778bd3c) | Aug 10, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [f3dcea80d5](https://linux-hardware.org/?probe=f3dcea80d5) | Aug 10, 2022 |
| ASUSTek       | A88XM-E                     | [f496954b96](https://linux-hardware.org/?probe=f496954b96) | Aug 08, 2022 |
| ASUSTek       | A88XM-E                     | [84dcf54ab8](https://linux-hardware.org/?probe=84dcf54ab8) | Aug 08, 2022 |
| Unknown       | Unknown                     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| ASUSTek       | M3A78-CM                    | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| MSI           | A320M PRO-M2                | [43f6f3c828](https://linux-hardware.org/?probe=43f6f3c828) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Gigabyte      | B550 GAMING X               | [b158696344](https://linux-hardware.org/?probe=b158696344) | Aug 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | [70d84ddbc1](https://linux-hardware.org/?probe=70d84ddbc1) | Aug 05, 2022 |
| Gigabyte      | B550M DS3H                  | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| ASUSTek       | M3A78-CM                    | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [13eff519f6](https://linux-hardware.org/?probe=13eff519f6) | Jul 30, 2022 |
| HP            | 21B4 A01                    | [474779f0b9](https://linux-hardware.org/?probe=474779f0b9) | Jul 30, 2022 |
| MSI           | X470 GAMING PLUS            | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | [cb1458b51e](https://linux-hardware.org/?probe=cb1458b51e) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | [7940deabb7](https://linux-hardware.org/?probe=7940deabb7) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | [711602c0ac](https://linux-hardware.org/?probe=711602c0ac) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | [48e8d6fba9](https://linux-hardware.org/?probe=48e8d6fba9) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| MSI           | B250 PC MATE                | [dda7519d05](https://linux-hardware.org/?probe=dda7519d05) | Jul 27, 2022 |
| Dell          | 0G261D A00                  | [f7cb8645af](https://linux-hardware.org/?probe=f7cb8645af) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| ASUSTek       | M3A78-CM                    | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Gigabyte      | Z97M-DS3H                   | [542296a447](https://linux-hardware.org/?probe=542296a447) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Gigabyte      | Z97M-DS3H                   | [570348c3f5](https://linux-hardware.org/?probe=570348c3f5) | Jul 23, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [63d34f24b6](https://linux-hardware.org/?probe=63d34f24b6) | Jul 20, 2022 |
| Gigabyte      | Z97M-DS3H                   | [ae8bbea84b](https://linux-hardware.org/?probe=ae8bbea84b) | Jul 19, 2022 |
| ASUSTek       | P5K-E                       | [68023f05e9](https://linux-hardware.org/?probe=68023f05e9) | Jul 18, 2022 |
| Gigabyte      | Z590 GAMING X               | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| Intel         | DG31PR AAD97573-301         | [0ac01b7529](https://linux-hardware.org/?probe=0ac01b7529) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [75e4cc3704](https://linux-hardware.org/?probe=75e4cc3704) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [c5695a430f](https://linux-hardware.org/?probe=c5695a430f) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [0a0ad06ece](https://linux-hardware.org/?probe=0a0ad06ece) | Jul 15, 2022 |
| ASUSTek       | M4A78 PRO                   | [119c291cd5](https://linux-hardware.org/?probe=119c291cd5) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| MSI           | B250M PRO-VH                | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| MSI           | H81M-P33                    | [05099f85ea](https://linux-hardware.org/?probe=05099f85ea) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| Gigabyte      | Z97M-DS3H                   | [fd9365ab43](https://linux-hardware.org/?probe=fd9365ab43) | Jul 11, 2022 |
| HP            | 0B4Ch D                     | [f49fb95b26](https://linux-hardware.org/?probe=f49fb95b26) | Jul 10, 2022 |
| Lenovo        | SKYBAY NOK                  | [5e8f90f865](https://linux-hardware.org/?probe=5e8f90f865) | Jul 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c350afe818](https://linux-hardware.org/?probe=c350afe818) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| MSI           | B250M BAZOOKA               | [e04f1fc85c](https://linux-hardware.org/?probe=e04f1fc85c) | Jul 07, 2022 |
| ASRock        | P67 Pro3                    | [b70f0fde7a](https://linux-hardware.org/?probe=b70f0fde7a) | Jul 07, 2022 |
| Dell          | 09KPNV A00                  | [7eb69e794e](https://linux-hardware.org/?probe=7eb69e794e) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| Gigabyte      | Z97M-DS3H                   | [6ffcfe37d6](https://linux-hardware.org/?probe=6ffcfe37d6) | Jul 03, 2022 |
| ASUSTek       | M4A78 PRO                   | [d76404df8d](https://linux-hardware.org/?probe=d76404df8d) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c8b31466ed](https://linux-hardware.org/?probe=c8b31466ed) | Jul 02, 2022 |
| ASRock        | P67 Pro3                    | [9f1ed28d62](https://linux-hardware.org/?probe=9f1ed28d62) | Jul 02, 2022 |
| Dell          | 09KPNV A00                  | [163fad4354](https://linux-hardware.org/?probe=163fad4354) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [403db88011](https://linux-hardware.org/?probe=403db88011) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [4ba5c0b79e](https://linux-hardware.org/?probe=4ba5c0b79e) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [632dbea587](https://linux-hardware.org/?probe=632dbea587) | Jul 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | [aaf8589ded](https://linux-hardware.org/?probe=aaf8589ded) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | [bdecafbe1d](https://linux-hardware.org/?probe=bdecafbe1d) | Jun 29, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f188fe2a3d](https://linux-hardware.org/?probe=f188fe2a3d) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [0ea209fffe](https://linux-hardware.org/?probe=0ea209fffe) | Jun 28, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d399933441](https://linux-hardware.org/?probe=d399933441) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Gigabyte      | Z97M-DS3H                   | [f90172a9f9](https://linux-hardware.org/?probe=f90172a9f9) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| MSI           | H81M-P33                    | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| MSI           | H81M-P33                    | [9ba6c64800](https://linux-hardware.org/?probe=9ba6c64800) | Jun 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [fe8f74c9c1](https://linux-hardware.org/?probe=fe8f74c9c1) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| Unknown       | K8NF3-VSTA                  | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [6a5e82663e](https://linux-hardware.org/?probe=6a5e82663e) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Dell          | 0HY9JP A00                  | [92c1597a97](https://linux-hardware.org/?probe=92c1597a97) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [08e5f734f9](https://linux-hardware.org/?probe=08e5f734f9) | Jun 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [95d5fd3cd1](https://linux-hardware.org/?probe=95d5fd3cd1) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | B85M-E45                    | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| MSI           | B450-A PRO MAX              | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [b9c65b6182](https://linux-hardware.org/?probe=b9c65b6182) | Jun 18, 2022 |
| ASRock        | P67 Pro3                    | [9804004de5](https://linux-hardware.org/?probe=9804004de5) | Jun 18, 2022 |
| Gigabyte      | Z97M-DS3H                   | [67757f27f2](https://linux-hardware.org/?probe=67757f27f2) | Jun 18, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a6cb0e21fc](https://linux-hardware.org/?probe=a6cb0e21fc) | Jun 17, 2022 |
| Dell          | 0P9XHK A00                  | [e167c05dd2](https://linux-hardware.org/?probe=e167c05dd2) | Jun 17, 2022 |
| ASRock        | P67 Pro3                    | [2c0a807c9c](https://linux-hardware.org/?probe=2c0a807c9c) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [83733f81bd](https://linux-hardware.org/?probe=83733f81bd) | Jun 17, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| ASRock        | P67 Pro3                    | [d56de69a04](https://linux-hardware.org/?probe=d56de69a04) | Jun 14, 2022 |
| Gigabyte      | Z97M-DS3H                   | [695e3a37d4](https://linux-hardware.org/?probe=695e3a37d4) | Jun 13, 2022 |
| ASRock        | P67 Pro3                    | [48cc60a732](https://linux-hardware.org/?probe=48cc60a732) | Jun 13, 2022 |
| ASUSTek       | M3A78-CM                    | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| HP            | 3396                        | [4c0f1563a7](https://linux-hardware.org/?probe=4c0f1563a7) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [4e830e41ec](https://linux-hardware.org/?probe=4e830e41ec) | Jun 11, 2022 |
| MSI           | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b0e6137115](https://linux-hardware.org/?probe=b0e6137115) | Jun 11, 2022 |
| Gigabyte      | Z97M-DS3H                   | [1698782254](https://linux-hardware.org/?probe=1698782254) | Jun 11, 2022 |
| Acer          | WG43M                       | [bdd6d72374](https://linux-hardware.org/?probe=bdd6d72374) | Jun 10, 2022 |
| Gigabyte      | Z97M-DS3H                   | [377aa877fc](https://linux-hardware.org/?probe=377aa877fc) | Jun 09, 2022 |
| Gigabyte      | H410M S2H V3                | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| Acer          | WG43M                       | [70d3c85c47](https://linux-hardware.org/?probe=70d3c85c47) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ffceb89203](https://linux-hardware.org/?probe=ffceb89203) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [74c4c38cae](https://linux-hardware.org/?probe=74c4c38cae) | Jun 07, 2022 |
| ASRock        | P67 Pro3                    | [30155bb328](https://linux-hardware.org/?probe=30155bb328) | Jun 06, 2022 |
| ASRock        | P67 Pro3                    | [a0cc6d57b8](https://linux-hardware.org/?probe=a0cc6d57b8) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [aca6d1da03](https://linux-hardware.org/?probe=aca6d1da03) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [c0eb59d595](https://linux-hardware.org/?probe=c0eb59d595) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [80832b1c72](https://linux-hardware.org/?probe=80832b1c72) | Jun 05, 2022 |
| Gigabyte      | B85M-D3H                    | [51074b5c43](https://linux-hardware.org/?probe=51074b5c43) | Jun 05, 2022 |
| Unknown       | Unknown                     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| ASUSTek       | M5A97 R2.0                  | [07468743a9](https://linux-hardware.org/?probe=07468743a9) | Jun 04, 2022 |
| Unknown       | Unknown                     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| HP            | 8056                        | [a52dec67e2](https://linux-hardware.org/?probe=a52dec67e2) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [4d3213676b](https://linux-hardware.org/?probe=4d3213676b) | Jun 04, 2022 |
| Gigabyte      | F2A88X-D3H                  | [5b7b255faf](https://linux-hardware.org/?probe=5b7b255faf) | Jun 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8ac5eb21ad](https://linux-hardware.org/?probe=8ac5eb21ad) | Jun 04, 2022 |
| ASRock        | P67 Pro3                    | [be79ac4787](https://linux-hardware.org/?probe=be79ac4787) | Jun 02, 2022 |
| Dell          | 0GDG8Y A00                  | [ae659a73f9](https://linux-hardware.org/?probe=ae659a73f9) | Jun 02, 2022 |
| ASRock        | P67 Pro3                    | [cd48749015](https://linux-hardware.org/?probe=cd48749015) | Jun 01, 2022 |
| Huanan        | X99-F8 NALEX                | [5c3c77a5a0](https://linux-hardware.org/?probe=5c3c77a5a0) | May 31, 2022 |
| Huanan        | X99-F8 NALEX                | [11d242c4f4](https://linux-hardware.org/?probe=11d242c4f4) | May 31, 2022 |
| ASRock        | P67 Pro3                    | [0494b65f2c](https://linux-hardware.org/?probe=0494b65f2c) | May 31, 2022 |
| Dell          | 0J3C2F A02                  | [9ff329a1fd](https://linux-hardware.org/?probe=9ff329a1fd) | May 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Gigabyte      | EP45C-DS3R                  | [dc6dbe40d9](https://linux-hardware.org/?probe=dc6dbe40d9) | May 30, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| Huanan        | X99-F8 NALEX                | [d6de670b16](https://linux-hardware.org/?probe=d6de670b16) | May 30, 2022 |
| Gigabyte      | Z97M-DS3H                   | [3192e3b512](https://linux-hardware.org/?probe=3192e3b512) | May 30, 2022 |
| Dell          | 0GWHMW A01                  | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| ASRock        | P67 Pro3                    | [e01dc9eb3d](https://linux-hardware.org/?probe=e01dc9eb3d) | May 30, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| ASRock        | P67 Pro3                    | [40ac10c85e](https://linux-hardware.org/?probe=40ac10c85e) | May 29, 2022 |
| ASRock        | P67 Pro3                    | [bd8541bdaa](https://linux-hardware.org/?probe=bd8541bdaa) | May 28, 2022 |
| ASRock        | P67 Pro3                    | [79a9263b65](https://linux-hardware.org/?probe=79a9263b65) | May 28, 2022 |
| ASRock        | Z87 Extreme4                | [d3315c5c94](https://linux-hardware.org/?probe=d3315c5c94) | May 27, 2022 |
| Dell          | 09M8Y8 A01                  | [7514f64b6e](https://linux-hardware.org/?probe=7514f64b6e) | May 26, 2022 |
| Dell          | 0MY171 A01                  | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ea24b77e94](https://linux-hardware.org/?probe=ea24b77e94) | May 25, 2022 |
| Dell          | 0DT029 A00                  | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| Acer          | WG43M                       | [ae5adc512f](https://linux-hardware.org/?probe=ae5adc512f) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| ASUSTek       | B150M-A/M.2                 | [3aea6596c6](https://linux-hardware.org/?probe=3aea6596c6) | May 23, 2022 |
| Unknown       | Unknown                     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [f9e86bb522](https://linux-hardware.org/?probe=f9e86bb522) | May 23, 2022 |
| HP            | 1495                        | [adf94f2549](https://linux-hardware.org/?probe=adf94f2549) | May 23, 2022 |
| HP            | 1495                        | [be2c2cbd65](https://linux-hardware.org/?probe=be2c2cbd65) | May 23, 2022 |
| HP            | 1495                        | [9d476ad9d1](https://linux-hardware.org/?probe=9d476ad9d1) | May 23, 2022 |
| HP            | 1495                        | [61f2119a07](https://linux-hardware.org/?probe=61f2119a07) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| MSI           | MS-7235                     | [cb9b6ded76](https://linux-hardware.org/?probe=cb9b6ded76) | May 22, 2022 |
| ASRock        | P67 Pro3                    | [6bb8448487](https://linux-hardware.org/?probe=6bb8448487) | May 22, 2022 |
| Gigabyte      | Z97M-DS3H                   | [ebf2b174b8](https://linux-hardware.org/?probe=ebf2b174b8) | May 22, 2022 |
| MSI           | MS-7235                     | [4dfaad64fd](https://linux-hardware.org/?probe=4dfaad64fd) | May 21, 2022 |
| ASRock        | P67 Pro3                    | [855045a0fa](https://linux-hardware.org/?probe=855045a0fa) | May 21, 2022 |
| ASRock        | P67 Pro3                    | [1cbf12b67a](https://linux-hardware.org/?probe=1cbf12b67a) | May 21, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| Gigabyte      | Z97M-DS3H                   | [72747e63e5](https://linux-hardware.org/?probe=72747e63e5) | May 18, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| Gigabyte      | Z97M-DS3H                   | [1c9a384e09](https://linux-hardware.org/?probe=1c9a384e09) | May 17, 2022 |
| ASUSTek       | M3A78-CM                    | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [528659dab4](https://linux-hardware.org/?probe=528659dab4) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| Dell          | 0HY9JP A02                  | [5f98aaf42c](https://linux-hardware.org/?probe=5f98aaf42c) | May 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [1e1a8e1815](https://linux-hardware.org/?probe=1e1a8e1815) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [56fc7bcca2](https://linux-hardware.org/?probe=56fc7bcca2) | May 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [bad0e8ce3b](https://linux-hardware.org/?probe=bad0e8ce3b) | May 10, 2022 |
| ASRock        | B660M-ITX/ac                | [88d7b71293](https://linux-hardware.org/?probe=88d7b71293) | May 10, 2022 |
| Dell          | 07T4MC A06                  | [34e338f194](https://linux-hardware.org/?probe=34e338f194) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | H270M Pro4                  | [7fb19cf73f](https://linux-hardware.org/?probe=7fb19cf73f) | May 07, 2022 |
| ASRock        | H270M Pro4                  | [1b6f35a5d0](https://linux-hardware.org/?probe=1b6f35a5d0) | May 07, 2022 |
| MSI           | A320M-A PRO MAX             | [ccb1cda445](https://linux-hardware.org/?probe=ccb1cda445) | May 06, 2022 |
| MSI           | A320M-A PRO MAX             | [adf601077e](https://linux-hardware.org/?probe=adf601077e) | May 06, 2022 |
| MSI           | B450-A PRO                  | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| HP            | 0B4Ch D                     | [47982d615d](https://linux-hardware.org/?probe=47982d615d) | May 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| Dell          | 0WR7PY A01                  | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [d0b7db5920](https://linux-hardware.org/?probe=d0b7db5920) | May 02, 2022 |
| ASRock        | X370 Gaming X               | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| Gigabyte      | H310M S2P                   | [c5303ab540](https://linux-hardware.org/?probe=c5303ab540) | May 01, 2022 |
| Lenovo        | ThinkCentre M58 7627AD5     | [05a686b922](https://linux-hardware.org/?probe=05a686b922) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [c2096251fc](https://linux-hardware.org/?probe=c2096251fc) | Apr 30, 2022 |
| Gigabyte      | B85M-D3H                    | [aab74c31b9](https://linux-hardware.org/?probe=aab74c31b9) | Apr 30, 2022 |
| Lenovo        | ThinkCentre M57 6072A5G     | [373677ac37](https://linux-hardware.org/?probe=373677ac37) | Apr 28, 2022 |
| ASRock        | G31M-S                      | [296df4a9d4](https://linux-hardware.org/?probe=296df4a9d4) | Apr 28, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [2999ff1487](https://linux-hardware.org/?probe=2999ff1487) | Apr 28, 2022 |
| Dell          | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [d354934f98](https://linux-hardware.org/?probe=d354934f98) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f37918f4d4](https://linux-hardware.org/?probe=f37918f4d4) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASRock        | X570 Pro4                   | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| ASUSTek       | H81M-V3                     | [4d87f6f113](https://linux-hardware.org/?probe=4d87f6f113) | Apr 25, 2022 |
| MSI           | Z390-A PRO                  | [d4a06d7bbe](https://linux-hardware.org/?probe=d4a06d7bbe) | Apr 24, 2022 |
| Gigabyte      | H310M H                     | [5c94950753](https://linux-hardware.org/?probe=5c94950753) | Apr 24, 2022 |
| MSI           | Z390-A PRO                  | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| HP            | 821D                        | [6a70c646a5](https://linux-hardware.org/?probe=6a70c646a5) | Apr 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2b65eeae8d](https://linux-hardware.org/?probe=2b65eeae8d) | Apr 24, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [e17b0d706a](https://linux-hardware.org/?probe=e17b0d706a) | Apr 23, 2022 |
| Gigabyte      | B450M GAMING                | [bf31ebdabe](https://linux-hardware.org/?probe=bf31ebdabe) | Apr 21, 2022 |
| Gigabyte      | Z170-Gaming K3              | [e21b7b0696](https://linux-hardware.org/?probe=e21b7b0696) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI           | Z170A GAMING M3             | [84f6645ca5](https://linux-hardware.org/?probe=84f6645ca5) | Apr 20, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [7beb17ef96](https://linux-hardware.org/?probe=7beb17ef96) | Apr 20, 2022 |
| Gigabyte      | H310M H                     | [9a462cda5a](https://linux-hardware.org/?probe=9a462cda5a) | Apr 20, 2022 |
| Gigabyte      | MZAPLBP-00                  | [62b2cada75](https://linux-hardware.org/?probe=62b2cada75) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [a92dda8ded](https://linux-hardware.org/?probe=a92dda8ded) | Apr 20, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [d162e9aa70](https://linux-hardware.org/?probe=d162e9aa70) | Apr 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [66ac59c0a3](https://linux-hardware.org/?probe=66ac59c0a3) | Apr 18, 2022 |
| Huanan        | X79 249PC V2.2              | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASUSTek       | P8Z77-V LX                  | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| MSI           | B450-A PRO MAX              | [9ce44bf30d](https://linux-hardware.org/?probe=9ce44bf30d) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3                    | [1785652200](https://linux-hardware.org/?probe=1785652200) | Apr 16, 2022 |
| Gigabyte      | EP31-DS3L                   | [a0a68f0980](https://linux-hardware.org/?probe=a0a68f0980) | Apr 15, 2022 |
| Gigabyte      | H370M DS3H-CF               | [c3eadb27ad](https://linux-hardware.org/?probe=c3eadb27ad) | Apr 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | [8f490a29f3](https://linux-hardware.org/?probe=8f490a29f3) | Apr 15, 2022 |
| ASUSTek       | H61M-K                      | [b8da99fd26](https://linux-hardware.org/?probe=b8da99fd26) | Apr 14, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [0f449aecbc](https://linux-hardware.org/?probe=0f449aecbc) | Apr 13, 2022 |
| ASRock        | H97M Anniversary            | [4a73af14bf](https://linux-hardware.org/?probe=4a73af14bf) | Apr 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [40d527cfe8](https://linux-hardware.org/?probe=40d527cfe8) | Apr 12, 2022 |
| Gigabyte      | B450M DS3H-CF               | [91037ebcec](https://linux-hardware.org/?probe=91037ebcec) | Apr 10, 2022 |
| Dell          | 0HY9JP A02                  | [84b46b3236](https://linux-hardware.org/?probe=84b46b3236) | Apr 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [799106d1e6](https://linux-hardware.org/?probe=799106d1e6) | Apr 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [d42f8f3535](https://linux-hardware.org/?probe=d42f8f3535) | Apr 08, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [cdf784520e](https://linux-hardware.org/?probe=cdf784520e) | Apr 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| Intel         | DH55TC AAE70932-204         | [336fcaa613](https://linux-hardware.org/?probe=336fcaa613) | Apr 05, 2022 |
| Dell          | 0HY9JP A02                  | [ed1cda9998](https://linux-hardware.org/?probe=ed1cda9998) | Apr 05, 2022 |
| Gigabyte      | G31M-S2L                    | [7842a96018](https://linux-hardware.org/?probe=7842a96018) | Apr 05, 2022 |
| Gigabyte      | H97M-HD3                    | [fc7b16c289](https://linux-hardware.org/?probe=fc7b16c289) | Apr 05, 2022 |
| Gigabyte      | H410M H V3                  | [afc10b77f7](https://linux-hardware.org/?probe=afc10b77f7) | Apr 04, 2022 |
| Dell          | 0NDYHG A01                  | [26629406de](https://linux-hardware.org/?probe=26629406de) | Apr 03, 2022 |
| Gigabyte      | B450M S2H V2                | [f3fde51c72](https://linux-hardware.org/?probe=f3fde51c72) | Apr 03, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [01c14c16ca](https://linux-hardware.org/?probe=01c14c16ca) | Apr 03, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASRock        | X370 Killer SLI             | [ffb866117c](https://linux-hardware.org/?probe=ffb866117c) | Apr 02, 2022 |
| ASUSTek       | H81M-PLUS                   | [bd717d57c2](https://linux-hardware.org/?probe=bd717d57c2) | Apr 02, 2022 |
| ASRock        | Z390 Taichi                 | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| Intel         | DH55TC AAE70932-204         | [5b54f9a1e1](https://linux-hardware.org/?probe=5b54f9a1e1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [405fedcff9](https://linux-hardware.org/?probe=405fedcff9) | Mar 28, 2022 |
| ASUSTek       | P7H55                       | [12a9db8849](https://linux-hardware.org/?probe=12a9db8849) | Mar 27, 2022 |
| Dell          | 0HY9JP A02                  | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | M61VME-S2                   | [4e68853105](https://linux-hardware.org/?probe=4e68853105) | Mar 27, 2022 |
| AMD           | 970A-D3                     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [fb365f1b1e](https://linux-hardware.org/?probe=fb365f1b1e) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [c53b2decec](https://linux-hardware.org/?probe=c53b2decec) | Mar 26, 2022 |
| ASRock        | P67 Pro3                    | [515f03c954](https://linux-hardware.org/?probe=515f03c954) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [d8b099aefa](https://linux-hardware.org/?probe=d8b099aefa) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [023e66a08d](https://linux-hardware.org/?probe=023e66a08d) | Mar 25, 2022 |
| Dell          | 00V62H A01                  | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [2a51a62d10](https://linux-hardware.org/?probe=2a51a62d10) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b2d23b47a5](https://linux-hardware.org/?probe=b2d23b47a5) | Mar 22, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |
| MSI           | B560-A PRO                  | [70f24bb773](https://linux-hardware.org/?probe=70f24bb773) | Mar 21, 2022 |
| HP            | 802E                        | [b15f756d65](https://linux-hardware.org/?probe=b15f756d65) | Mar 21, 2022 |
| Gigabyte      | P35-DS3P                    | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| MSI           | H81M-E34                    | [2278c36b03](https://linux-hardware.org/?probe=2278c36b03) | Mar 20, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d64fc66c4](https://linux-hardware.org/?probe=9d64fc66c4) | Mar 19, 2022 |
| Dell          | 0P611C A00                  | [0c433bca90](https://linux-hardware.org/?probe=0c433bca90) | Mar 18, 2022 |
| Gigabyte      | A520I AC                    | [5a27854c64](https://linux-hardware.org/?probe=5a27854c64) | Mar 18, 2022 |
| Dell          | 0P611C A00                  | [72593cf88a](https://linux-hardware.org/?probe=72593cf88a) | Mar 16, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [3563d1c4c9](https://linux-hardware.org/?probe=3563d1c4c9) | Mar 16, 2022 |
| MSI           | H110M PRO-D                 | [f7eac945c2](https://linux-hardware.org/?probe=f7eac945c2) | Mar 16, 2022 |
| MSI           | H110M PRO-D                 | [d31414b37d](https://linux-hardware.org/?probe=d31414b37d) | Mar 16, 2022 |
| MSI           | A88XM-E35 V2                | [4c836d3202](https://linux-hardware.org/?probe=4c836d3202) | Mar 16, 2022 |
| Dell          | 0HY9JP A02                  | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [314443b85b](https://linux-hardware.org/?probe=314443b85b) | Mar 14, 2022 |
| Intel         | DP43TF AAE34878-403         | [72da5eadd9](https://linux-hardware.org/?probe=72da5eadd9) | Mar 13, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [a504948f7f](https://linux-hardware.org/?probe=a504948f7f) | Mar 13, 2022 |
| MSI           | H81M-P33                    | [138594b67f](https://linux-hardware.org/?probe=138594b67f) | Mar 12, 2022 |
| MSI           | B560-A PRO                  | [b3b7fa5c21](https://linux-hardware.org/?probe=b3b7fa5c21) | Mar 12, 2022 |
| MSI           | A68HM-E33 V2                | [dfa0722637](https://linux-hardware.org/?probe=dfa0722637) | Mar 12, 2022 |
| ASUSTek       | P8Q77-M                     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [2032fbba77](https://linux-hardware.org/?probe=2032fbba77) | Mar 09, 2022 |
| Acer          | WG43M                       | [874dcfa2a0](https://linux-hardware.org/?probe=874dcfa2a0) | Mar 08, 2022 |
| Dell          | 0P611C A00                  | [8acced42b7](https://linux-hardware.org/?probe=8acced42b7) | Mar 06, 2022 |
| Gigabyte      | G41M-Combo                  | [21e65fb534](https://linux-hardware.org/?probe=21e65fb534) | Mar 04, 2022 |
| ASUSTek       | M2N-CM DVI                  | [499346b7ab](https://linux-hardware.org/?probe=499346b7ab) | Mar 04, 2022 |
| ASRock        | B450M-HDV R4.0              | [ddb21aba7b](https://linux-hardware.org/?probe=ddb21aba7b) | Mar 04, 2022 |
| HP            | 18E7                        | [795f8bd0ed](https://linux-hardware.org/?probe=795f8bd0ed) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [53dd60c906](https://linux-hardware.org/?probe=53dd60c906) | Mar 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [01922bdee0](https://linux-hardware.org/?probe=01922bdee0) | Mar 02, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [61f787045c](https://linux-hardware.org/?probe=61f787045c) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [e6bb78efda](https://linux-hardware.org/?probe=e6bb78efda) | Mar 02, 2022 |
| ASRock        | N68C-GS4 FX                 | [a6b02e2f3b](https://linux-hardware.org/?probe=a6b02e2f3b) | Mar 02, 2022 |
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| ASRock        | N68-S                       | [56c03860e3](https://linux-hardware.org/?probe=56c03860e3) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| Acer          | RS880M05                    | [53e88a31a0](https://linux-hardware.org/?probe=53e88a31a0) | Feb 27, 2022 |
| Intel         | X99                         | [9cc44f0705](https://linux-hardware.org/?probe=9cc44f0705) | Feb 26, 2022 |
| ASUSTek       | AM1M-A                      | [6926e87bd5](https://linux-hardware.org/?probe=6926e87bd5) | Feb 26, 2022 |
| ASRock        | B450M-HDV R4.0              | [70fa55ac83](https://linux-hardware.org/?probe=70fa55ac83) | Feb 26, 2022 |
| MSI           | H410M PRO                   | [60cb5eed90](https://linux-hardware.org/?probe=60cb5eed90) | Feb 26, 2022 |
| HP            | 0AA0h                       | [eaf5cda818](https://linux-hardware.org/?probe=eaf5cda818) | Feb 24, 2022 |
| ASUSTek       | PRIME X470-PRO              | [7e4b379590](https://linux-hardware.org/?probe=7e4b379590) | Feb 22, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [77ab4a5017](https://linux-hardware.org/?probe=77ab4a5017) | Feb 22, 2022 |
| ASRock        | B450M Pro4                  | [5825d4fcaf](https://linux-hardware.org/?probe=5825d4fcaf) | Feb 22, 2022 |
| ASRock        | Z97 Pro4                    | [857a676f79](https://linux-hardware.org/?probe=857a676f79) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5b8dafb532](https://linux-hardware.org/?probe=5b8dafb532) | Feb 20, 2022 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [f5befc40e5](https://linux-hardware.org/?probe=f5befc40e5) | Feb 19, 2022 |
| Gigabyte      | Z97-HD3                     | [e9d45ff571](https://linux-hardware.org/?probe=e9d45ff571) | Feb 18, 2022 |
| ASUSTek       | H110M-R                     | [d3787fdf74](https://linux-hardware.org/?probe=d3787fdf74) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| HP            | 18E4                        | [1ddb4ff651](https://linux-hardware.org/?probe=1ddb4ff651) | Feb 18, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [d2088e6244](https://linux-hardware.org/?probe=d2088e6244) | Feb 18, 2022 |
| ABIT          | IP35-E                      | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| HP            | 821D                        | [f059d8132b](https://linux-hardware.org/?probe=f059d8132b) | Feb 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Dell          | 00V62H A01                  | [7e2f445655](https://linux-hardware.org/?probe=7e2f445655) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [47ff2c9673](https://linux-hardware.org/?probe=47ff2c9673) | Feb 15, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [9ca035e8ea](https://linux-hardware.org/?probe=9ca035e8ea) | Feb 14, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [a53c16de6d](https://linux-hardware.org/?probe=a53c16de6d) | Feb 14, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [aad23e9c01](https://linux-hardware.org/?probe=aad23e9c01) | Feb 14, 2022 |
| Lenovo        | ThinkCentre M58 7360WYV     | [dc7929d9bd](https://linux-hardware.org/?probe=dc7929d9bd) | Feb 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | [1bade168b7](https://linux-hardware.org/?probe=1bade168b7) | Feb 13, 2022 |
| MSI           | Z590 PRO WIFI               | [121d08a889](https://linux-hardware.org/?probe=121d08a889) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [91d1953478](https://linux-hardware.org/?probe=91d1953478) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [119cc6c1b1](https://linux-hardware.org/?probe=119cc6c1b1) | Feb 13, 2022 |
| HP            | 1825                        | [0e6723f81a](https://linux-hardware.org/?probe=0e6723f81a) | Feb 13, 2022 |
| Gigabyte      | 945GCMX-S2                  | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Gigabyte      | B85M-D3H                    | [02643059e9](https://linux-hardware.org/?probe=02643059e9) | Feb 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b8658db7ef](https://linux-hardware.org/?probe=b8658db7ef) | Feb 12, 2022 |
| ASRock        | 970 Pro3 R2.0               | [e9838d6bb3](https://linux-hardware.org/?probe=e9838d6bb3) | Feb 12, 2022 |
| Gigabyte      | B75M-D3V                    | [84ebaedb6c](https://linux-hardware.org/?probe=84ebaedb6c) | Feb 12, 2022 |
| HP            | 18E4                        | [ef8e0ed69f](https://linux-hardware.org/?probe=ef8e0ed69f) | Feb 11, 2022 |
| ASRock        | Q1900-ITX                   | [606783a7c4](https://linux-hardware.org/?probe=606783a7c4) | Feb 11, 2022 |
| Gigabyte      | GA-970A-UD3                 | [c68353f191](https://linux-hardware.org/?probe=c68353f191) | Feb 10, 2022 |
| HP            | 212B                        | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| ASUSTek       | PRIME B250M-K               | [6f66651cd1](https://linux-hardware.org/?probe=6f66651cd1) | Feb 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [efd6cf168c](https://linux-hardware.org/?probe=efd6cf168c) | Feb 10, 2022 |
| ASRock        | B450 Pro4                   | [9758db6134](https://linux-hardware.org/?probe=9758db6134) | Feb 09, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b01520659c](https://linux-hardware.org/?probe=b01520659c) | Feb 09, 2022 |
| ASRock        | H370M Pro4                  | [acd8487e01](https://linux-hardware.org/?probe=acd8487e01) | Feb 09, 2022 |
| Intel         | DH61WW AAG23116-204         | [638abe9878](https://linux-hardware.org/?probe=638abe9878) | Feb 09, 2022 |
| ASUSTek       | Z97I-PLUS                   | [3df98a2c5e](https://linux-hardware.org/?probe=3df98a2c5e) | Feb 09, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [c904b1a608](https://linux-hardware.org/?probe=c904b1a608) | Feb 09, 2022 |
| ASUSTek       | M5A78L-M LE                 | [03c0e0a702](https://linux-hardware.org/?probe=03c0e0a702) | Feb 09, 2022 |
| MSI           | H110M PRO-D 2017-09-06      | [441f4bb2f9](https://linux-hardware.org/?probe=441f4bb2f9) | Feb 09, 2022 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [e19a7be811](https://linux-hardware.org/?probe=e19a7be811) | Feb 09, 2022 |
| Gigabyte      | H310M M.2 x.x               | [cdb7b11995](https://linux-hardware.org/?probe=cdb7b11995) | Feb 09, 2022 |
| ASRock        | B450M Steel Legend          | [f81e6843ba](https://linux-hardware.org/?probe=f81e6843ba) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASRock        | FM2A68M-HD+                 | [8545c3246e](https://linux-hardware.org/?probe=8545c3246e) | Feb 08, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [4ae22f289a](https://linux-hardware.org/?probe=4ae22f289a) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-A               | [59e0e72397](https://linux-hardware.org/?probe=59e0e72397) | Feb 08, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [c71df10fb4](https://linux-hardware.org/?probe=c71df10fb4) | Feb 07, 2022 |
| ASRock        | Z170 Extreme4               | [7586ccd3c6](https://linux-hardware.org/?probe=7586ccd3c6) | Feb 07, 2022 |
| HP            | 0AACh                       | [489486e81b](https://linux-hardware.org/?probe=489486e81b) | Feb 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [e21a51339e](https://linux-hardware.org/?probe=e21a51339e) | Feb 06, 2022 |
| Acer          | Predator G3120              | [d002f5e1b6](https://linux-hardware.org/?probe=d002f5e1b6) | Feb 06, 2022 |
| MSI           | Z97 GAMING 3                | [b4feb3ee6c](https://linux-hardware.org/?probe=b4feb3ee6c) | Feb 05, 2022 |
| MSI           | MS-7392                     | [e8f489c1fc](https://linux-hardware.org/?probe=e8f489c1fc) | Feb 04, 2022 |
| MSI           | X470 GAMING PLUS            | [b0c6fdf764](https://linux-hardware.org/?probe=b0c6fdf764) | Feb 04, 2022 |
| HP            | 0A80h                       | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| Acer          | Revo RN86                   | [d0b5fa877f](https://linux-hardware.org/?probe=d0b5fa877f) | Feb 04, 2022 |
| Foxconn       | 2A8Ch                       | [a4978d8283](https://linux-hardware.org/?probe=a4978d8283) | Feb 03, 2022 |
| Foxconn       | 2A8Ch                       | [1e60876b1e](https://linux-hardware.org/?probe=1e60876b1e) | Feb 03, 2022 |
| Inventec      | Z CLASS A02                 | [32bbd0c80c](https://linux-hardware.org/?probe=32bbd0c80c) | Feb 03, 2022 |
| MSI           | X570-A PRO                  | [df3c56c53c](https://linux-hardware.org/?probe=df3c56c53c) | Feb 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [813bec5fe7](https://linux-hardware.org/?probe=813bec5fe7) | Feb 02, 2022 |
| Dell          | 0MN1TX A02                  | [c22ec93e89](https://linux-hardware.org/?probe=c22ec93e89) | Feb 01, 2022 |
| ASRock        | X370 Gaming X               | [67d9bb3ace](https://linux-hardware.org/?probe=67d9bb3ace) | Jan 30, 2022 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [69b300dfb1](https://linux-hardware.org/?probe=69b300dfb1) | Jan 29, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| MSI           | B75MA-P45                   | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| Dell          | 0M9KCM A00                  | [8ce5fcb03f](https://linux-hardware.org/?probe=8ce5fcb03f) | Jan 27, 2022 |
| Acer          | Revo RN86                   | [ce1dd8b1f9](https://linux-hardware.org/?probe=ce1dd8b1f9) | Jan 27, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e422d19fb3](https://linux-hardware.org/?probe=e422d19fb3) | Jan 27, 2022 |
| Gigabyte      | M61VME-S2                   | [c91d9663e8](https://linux-hardware.org/?probe=c91d9663e8) | Jan 26, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [d0dde4a553](https://linux-hardware.org/?probe=d0dde4a553) | Jan 24, 2022 |
| Gigabyte      | 965P-S3                     | [9e4aca104e](https://linux-hardware.org/?probe=9e4aca104e) | Jan 24, 2022 |
| Gigabyte      | 945G-S3                     | [9adb1e8380](https://linux-hardware.org/?probe=9adb1e8380) | Jan 23, 2022 |
| MSI           | Z170A PC MATE               | [dd98b6fbca](https://linux-hardware.org/?probe=dd98b6fbca) | Jan 23, 2022 |
| HP            | 2215                        | [336671cc36](https://linux-hardware.org/?probe=336671cc36) | Jan 23, 2022 |
| HP            | 1998                        | [e728021985](https://linux-hardware.org/?probe=e728021985) | Jan 23, 2022 |
| ASRock        | H510M-ITX/ac                | [606c183545](https://linux-hardware.org/?probe=606c183545) | Jan 23, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [7f92d6ff46](https://linux-hardware.org/?probe=7f92d6ff46) | Jan 22, 2022 |
| MSI           | H110M PRO-VD PLUS           | [c51916b063](https://linux-hardware.org/?probe=c51916b063) | Jan 22, 2022 |
| ASRock        | P4i945GC                    | [b4ed754106](https://linux-hardware.org/?probe=b4ed754106) | Jan 22, 2022 |
| ASRock        | Z87 Killer                  | [0be767a418](https://linux-hardware.org/?probe=0be767a418) | Jan 22, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [fc20f2e1e3](https://linux-hardware.org/?probe=fc20f2e1e3) | Jan 22, 2022 |
| ASUSTek       | PRIME X470-PRO              | [6f8113e04c](https://linux-hardware.org/?probe=6f8113e04c) | Jan 21, 2022 |
| Foxconn       | A76GMV                      | [c25b49803b](https://linux-hardware.org/?probe=c25b49803b) | Jan 21, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c7f152495b](https://linux-hardware.org/?probe=c7f152495b) | Jan 21, 2022 |
| HP            | 339A                        | [9a1c8ec615](https://linux-hardware.org/?probe=9a1c8ec615) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [1b1004081a](https://linux-hardware.org/?probe=1b1004081a) | Jan 21, 2022 |
| HP            | 1998                        | [d5e17cefbb](https://linux-hardware.org/?probe=d5e17cefbb) | Jan 20, 2022 |
| ASRock        | G31M-S                      | [9d338d58c9](https://linux-hardware.org/?probe=9d338d58c9) | Jan 20, 2022 |
| Medion        | H110H4-EM                   | [64a2a3257d](https://linux-hardware.org/?probe=64a2a3257d) | Jan 20, 2022 |
| MSI           | B450-A PRO MAX              | [72415f94c8](https://linux-hardware.org/?probe=72415f94c8) | Jan 19, 2022 |
| Medion        | H110H4-EM                   | [6eab6bd21a](https://linux-hardware.org/?probe=6eab6bd21a) | Jan 19, 2022 |
| Dell          | 0F6X5P A00                  | [3caf7fb5f2](https://linux-hardware.org/?probe=3caf7fb5f2) | Jan 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [01e009ebd0](https://linux-hardware.org/?probe=01e009ebd0) | Jan 18, 2022 |
| ASUSTek       | P9X79                       | [bfb8f77808](https://linux-hardware.org/?probe=bfb8f77808) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [e3f87f47e8](https://linux-hardware.org/?probe=e3f87f47e8) | Jan 18, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [2fdc6503ab](https://linux-hardware.org/?probe=2fdc6503ab) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Gigabyte      | GA-970A-UD3                 | [b123404920](https://linux-hardware.org/?probe=b123404920) | Jan 17, 2022 |
| MSI           | B450-A PRO MAX              | [5baec4640b](https://linux-hardware.org/?probe=5baec4640b) | Jan 16, 2022 |
| Gigabyte      | 970A-DS3P                   | [d6d4dbbb78](https://linux-hardware.org/?probe=d6d4dbbb78) | Jan 16, 2022 |
| ASRock        | AM1H-ITX                    | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Acer          | Veriton X6620G v1.0         | [8ef5b3632a](https://linux-hardware.org/?probe=8ef5b3632a) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | [9324cf10f9](https://linux-hardware.org/?probe=9324cf10f9) | Jan 15, 2022 |
| ASRock        | B550 Taichi                 | [7fca8e1118](https://linux-hardware.org/?probe=7fca8e1118) | Jan 15, 2022 |
| Dell          | 0D6H9T A00                  | [cd0c65171a](https://linux-hardware.org/?probe=cd0c65171a) | Jan 15, 2022 |
| Dell          | 0D6H9T A00                  | [77239f8808](https://linux-hardware.org/?probe=77239f8808) | Jan 15, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [5212a5cb92](https://linux-hardware.org/?probe=5212a5cb92) | Jan 13, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [63db02d0e6](https://linux-hardware.org/?probe=63db02d0e6) | Jan 13, 2022 |
| ASRock        | P67 Pro3                    | [12708e4124](https://linux-hardware.org/?probe=12708e4124) | Jan 11, 2022 |
| ASRock        | AM1H-ITX                    | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| ASRock        | ALiveNF6G-GLAN              | [004087e9c8](https://linux-hardware.org/?probe=004087e9c8) | Jan 09, 2022 |
| ASRock        | Z590 Phantom Gaming 4       | [2213b9d944](https://linux-hardware.org/?probe=2213b9d944) | Jan 09, 2022 |
| ASUSTek       | P5B-VM SE                   | [70d1a7ddc8](https://linux-hardware.org/?probe=70d1a7ddc8) | Jan 09, 2022 |
| ASUSTek       | P5B-VM SE                   | [6a043eb515](https://linux-hardware.org/?probe=6a043eb515) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [30212e6fd6](https://linux-hardware.org/?probe=30212e6fd6) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [52a27d926e](https://linux-hardware.org/?probe=52a27d926e) | Jan 07, 2022 |
| HP            | 1497                        | [adfca54c7c](https://linux-hardware.org/?probe=adfca54c7c) | Jan 07, 2022 |
| Dell          | 0WR7PY A01                  | [87ab60ffc4](https://linux-hardware.org/?probe=87ab60ffc4) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [b3d984f6a4](https://linux-hardware.org/?probe=b3d984f6a4) | Jan 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | [711a037e72](https://linux-hardware.org/?probe=711a037e72) | Jan 07, 2022 |
| Gigabyte      | Z97N-WIFI                   | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Gigabyte      | B460M GAMING HD             | [4cfe82fefd](https://linux-hardware.org/?probe=4cfe82fefd) | Jan 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| ASRock        | P67 Pro3                    | [db27d8ec7a](https://linux-hardware.org/?probe=db27d8ec7a) | Jan 06, 2022 |
| MSI           | B450M MORTAR MAX            | [da41cecf9e](https://linux-hardware.org/?probe=da41cecf9e) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| Dell          | 0D28YY A00                  | [8525880542](https://linux-hardware.org/?probe=8525880542) | Jan 04, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [3e37ded7e2](https://linux-hardware.org/?probe=3e37ded7e2) | Jan 04, 2022 |
| Lenovo        | SKYBAY NOK                  | [7d5840e2c1](https://linux-hardware.org/?probe=7d5840e2c1) | Jan 03, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [b924f29b41](https://linux-hardware.org/?probe=b924f29b41) | Jan 02, 2022 |
| ASUSTek       | CM1735                      | [92165700b1](https://linux-hardware.org/?probe=92165700b1) | Jan 02, 2022 |
| HP            | 2179                        | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| HP            | 2179                        | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASRock        | 945GCM-S                    | [b089710f53](https://linux-hardware.org/?probe=b089710f53) | Dec 30, 2021 |
| Dell          | 0G919G A00                  | [afdc58ebbb](https://linux-hardware.org/?probe=afdc58ebbb) | Dec 29, 2021 |
| ASUSTek       | P5QPL-AM                    | [f87be438d3](https://linux-hardware.org/?probe=f87be438d3) | Dec 29, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [bc579cd171](https://linux-hardware.org/?probe=bc579cd171) | Dec 29, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [df438ad11a](https://linux-hardware.org/?probe=df438ad11a) | Dec 29, 2021 |
| Gigabyte      | TRX40 AORUS XTREME          | [cbf9ee4a86](https://linux-hardware.org/?probe=cbf9ee4a86) | Dec 28, 2021 |
| MSI           | B150M PRO-VDH               | [6af03f4abc](https://linux-hardware.org/?probe=6af03f4abc) | Dec 28, 2021 |
| MSI           | X470 GAMING PLUS            | [e599511f33](https://linux-hardware.org/?probe=e599511f33) | Dec 28, 2021 |
| Gigabyte      | M61VME-S2                   | [c8f8be20da](https://linux-hardware.org/?probe=c8f8be20da) | Dec 28, 2021 |
| ASUSTek       | P5G41T-M/USB3               | [2948415606](https://linux-hardware.org/?probe=2948415606) | Dec 28, 2021 |
| ASRock        | B85 Pro4                    | [33433ec5e1](https://linux-hardware.org/?probe=33433ec5e1) | Dec 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5b7f950dfe](https://linux-hardware.org/?probe=5b7f950dfe) | Dec 27, 2021 |
| Gigabyte      | M68M-S2P                    | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [b097a62c18](https://linux-hardware.org/?probe=b097a62c18) | Dec 22, 2021 |
| MSI           | B360M PRO-VD 2019-01-24     | [7ded80ebab](https://linux-hardware.org/?probe=7ded80ebab) | Dec 22, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | [51a7e08e9a](https://linux-hardware.org/?probe=51a7e08e9a) | Dec 22, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [e26f76134b](https://linux-hardware.org/?probe=e26f76134b) | Dec 20, 2021 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7dc1a10587](https://linux-hardware.org/?probe=7dc1a10587) | Dec 18, 2021 |
| MSI           | B450M PRO-VDH MAX           | [3879747d77](https://linux-hardware.org/?probe=3879747d77) | Dec 18, 2021 |
| MSI           | X399 SLI PLUS               | [08c23ed037](https://linux-hardware.org/?probe=08c23ed037) | Dec 17, 2021 |
| Foxconn       | 9657AA FAB1.2               | [8a1a367aa8](https://linux-hardware.org/?probe=8a1a367aa8) | Dec 17, 2021 |
| Foxconn       | 9657AA FAB1.2               | [1e4d8c2a75](https://linux-hardware.org/?probe=1e4d8c2a75) | Dec 17, 2021 |
| Gigabyte      | H270-HD3-CF                 | [03d816dffc](https://linux-hardware.org/?probe=03d816dffc) | Dec 17, 2021 |
| MSI           | B450M PRO-VDH MAX           | [4995f4578e](https://linux-hardware.org/?probe=4995f4578e) | Dec 16, 2021 |
| Lenovo        | 3098 SDK0E50510 WIN         | [de9106e830](https://linux-hardware.org/?probe=de9106e830) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| ASUSTek       | Z170-P                      | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| ASRock        | AB350 Pro4                  | [783c3be01f](https://linux-hardware.org/?probe=783c3be01f) | Dec 16, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [45a411c9fe](https://linux-hardware.org/?probe=45a411c9fe) | Dec 15, 2021 |
| MSI           | MS-B0501 100                | [ca4048db98](https://linux-hardware.org/?probe=ca4048db98) | Dec 14, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [d0889ec2eb](https://linux-hardware.org/?probe=d0889ec2eb) | Dec 14, 2021 |
| MSI           | B450M PRO-VDH MAX           | [99b31d7eec](https://linux-hardware.org/?probe=99b31d7eec) | Dec 14, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [53523a4ea7](https://linux-hardware.org/?probe=53523a4ea7) | Dec 14, 2021 |
| Dell          | 0T1D10 A01                  | [78db9d87b2](https://linux-hardware.org/?probe=78db9d87b2) | Dec 13, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [3030fcf474](https://linux-hardware.org/?probe=3030fcf474) | Dec 13, 2021 |
| ASUSTek       | M5A78L-M LX3                | [43dc5e9e17](https://linux-hardware.org/?probe=43dc5e9e17) | Dec 11, 2021 |
| MSI           | X470 GAMING PLUS            | [7319c92561](https://linux-hardware.org/?probe=7319c92561) | Dec 10, 2021 |
| Gigabyte      | X570 GAMING X               | [d0f4c6c32f](https://linux-hardware.org/?probe=d0f4c6c32f) | Dec 09, 2021 |
| Gigabyte      | X570 GAMING X               | [c7c63c686c](https://linux-hardware.org/?probe=c7c63c686c) | Dec 09, 2021 |
| Acer          | WG43M                       | [9cafb5a511](https://linux-hardware.org/?probe=9cafb5a511) | Dec 09, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [9aaf751364](https://linux-hardware.org/?probe=9aaf751364) | Dec 09, 2021 |
| ASRock        | P67 Pro3                    | [7d033ae039](https://linux-hardware.org/?probe=7d033ae039) | Dec 09, 2021 |
| ASRock        | TRX40 Creator               | [b24408a4d1](https://linux-hardware.org/?probe=b24408a4d1) | Dec 09, 2021 |
| Dell          | 08WKV3 A00                  | [1bb7cb432f](https://linux-hardware.org/?probe=1bb7cb432f) | Dec 08, 2021 |
| ASUSTek       | Maximus V EXTREME           | [db3905e629](https://linux-hardware.org/?probe=db3905e629) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [50ea30a8b4](https://linux-hardware.org/?probe=50ea30a8b4) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| MSI           | X470 GAMING PLUS            | [8a01b0cd81](https://linux-hardware.org/?probe=8a01b0cd81) | Dec 06, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9c4308e5f7](https://linux-hardware.org/?probe=9c4308e5f7) | Dec 05, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [f7dc703699](https://linux-hardware.org/?probe=f7dc703699) | Dec 05, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [85e67dc7fc](https://linux-hardware.org/?probe=85e67dc7fc) | Dec 04, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [3c693abd6e](https://linux-hardware.org/?probe=3c693abd6e) | Dec 04, 2021 |
| ASRock        | Z370 Pro4                   | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| Dell          | 0J584C A00                  | [d443412bd4](https://linux-hardware.org/?probe=d443412bd4) | Dec 03, 2021 |
| ASUSTek       | H81M-K                      | [615600f1dc](https://linux-hardware.org/?probe=615600f1dc) | Dec 03, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| Gigabyte      | A320M-S2H-CF                | [55a4727c30](https://linux-hardware.org/?probe=55a4727c30) | Dec 01, 2021 |
| ASRock        | G31M-S                      | [48ad510e26](https://linux-hardware.org/?probe=48ad510e26) | Nov 29, 2021 |
| ASRock        | G31M-S                      | [5f87bf3b90](https://linux-hardware.org/?probe=5f87bf3b90) | Nov 28, 2021 |
| MSI           | H81M-P33                    | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | [17bd2e3558](https://linux-hardware.org/?probe=17bd2e3558) | Nov 28, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [feb01c3dfa](https://linux-hardware.org/?probe=feb01c3dfa) | Nov 27, 2021 |
| MSI           | B450-A PRO MAX              | [d949cb9963](https://linux-hardware.org/?probe=d949cb9963) | Nov 27, 2021 |
| HP            | 3047h                       | [4ccf9bec03](https://linux-hardware.org/?probe=4ccf9bec03) | Nov 27, 2021 |
| Gigabyte      | GA-MA770-UD3                | [551c45ed6b](https://linux-hardware.org/?probe=551c45ed6b) | Nov 26, 2021 |
| Gigabyte      | GA-MA770-UD3                | [58da56c671](https://linux-hardware.org/?probe=58da56c671) | Nov 26, 2021 |
| MSI           | B460M PRO-VDH               | [4c7d18cb37](https://linux-hardware.org/?probe=4c7d18cb37) | Nov 26, 2021 |
| MSI           | A88XM-E35                   | [46d27320e4](https://linux-hardware.org/?probe=46d27320e4) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [511ebdb8bb](https://linux-hardware.org/?probe=511ebdb8bb) | Nov 25, 2021 |
| Dell          | 06390H A01                  | [2cd7410eaf](https://linux-hardware.org/?probe=2cd7410eaf) | Nov 25, 2021 |
| ASUSTek       | PRIME B450M-A               | [10a2275459](https://linux-hardware.org/?probe=10a2275459) | Nov 24, 2021 |
| ASUSTek       | PRIME B450M-A               | [999042ac63](https://linux-hardware.org/?probe=999042ac63) | Nov 24, 2021 |
| ASRock        | H110M-DVS R3.0              | [b6bbedf1ac](https://linux-hardware.org/?probe=b6bbedf1ac) | Nov 23, 2021 |
| MSI           | B360M PRO-VD                | [e1f68c6698](https://linux-hardware.org/?probe=e1f68c6698) | Nov 22, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [9fca12db52](https://linux-hardware.org/?probe=9fca12db52) | Nov 22, 2021 |
| Dell          | 03NVJ6 A02                  | [8996f56926](https://linux-hardware.org/?probe=8996f56926) | Nov 21, 2021 |
| ASUSTek       | P5L-VM 1394                 | [a43426b94f](https://linux-hardware.org/?probe=a43426b94f) | Nov 21, 2021 |
| ASUSTek       | M2N                         | [06bba5770c](https://linux-hardware.org/?probe=06bba5770c) | Nov 21, 2021 |
| ASUSTek       | M2N                         | [dfc5087439](https://linux-hardware.org/?probe=dfc5087439) | Nov 20, 2021 |
| ASRock        | AB350 Pro4                  | [44b253c551](https://linux-hardware.org/?probe=44b253c551) | Nov 19, 2021 |
| ASRock        | AB350 Pro4                  | [504b7aca94](https://linux-hardware.org/?probe=504b7aca94) | Nov 19, 2021 |
| HP            | 18E4                        | [bc3a8efa45](https://linux-hardware.org/?probe=bc3a8efa45) | Nov 18, 2021 |
| Gigabyte      | B75M-D2V                    | [3528c3828b](https://linux-hardware.org/?probe=3528c3828b) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [8377977aee](https://linux-hardware.org/?probe=8377977aee) | Nov 17, 2021 |
| ASRock        | Q1900M                      | [f2676fac87](https://linux-hardware.org/?probe=f2676fac87) | Nov 17, 2021 |
| MSI           | H310M PRO-VDH               | [645d9fd97e](https://linux-hardware.org/?probe=645d9fd97e) | Nov 17, 2021 |
| MSI           | H310M PRO-VDH               | [d4f2aa5324](https://linux-hardware.org/?probe=d4f2aa5324) | Nov 17, 2021 |
| ASUSTek       | PRIME B450M-K               | [6444d420e3](https://linux-hardware.org/?probe=6444d420e3) | Nov 16, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [68024e0eba](https://linux-hardware.org/?probe=68024e0eba) | Nov 15, 2021 |
| Gigabyte      | B450M S2H                   | [67a90a8265](https://linux-hardware.org/?probe=67a90a8265) | Nov 14, 2021 |
| ASUSTek       | PRIME B450M-K               | [2c7f2bbe1e](https://linux-hardware.org/?probe=2c7f2bbe1e) | Nov 14, 2021 |
| ASUSTek       | P8H61                       | [dac2d8a7ac](https://linux-hardware.org/?probe=dac2d8a7ac) | Nov 14, 2021 |
| ASUSTek       | P8H61                       | [26718af2a1](https://linux-hardware.org/?probe=26718af2a1) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| MSI           | H81M-P33                    | [76d3a6ff1e](https://linux-hardware.org/?probe=76d3a6ff1e) | Nov 13, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [698e22c7f3](https://linux-hardware.org/?probe=698e22c7f3) | Nov 13, 2021 |
| ASRock        | Z87 Killer                  | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| ASRock        | 970 Extreme4                | [a39bc6cd00](https://linux-hardware.org/?probe=a39bc6cd00) | Nov 11, 2021 |
| Dell          | 0GM819                      | [4f630535ad](https://linux-hardware.org/?probe=4f630535ad) | Nov 11, 2021 |
| ASUSTek       | M5A97 R2.0                  | [3d5a6a79f2](https://linux-hardware.org/?probe=3d5a6a79f2) | Nov 10, 2021 |
| ASUSTek       | H97-PRO                     | [198d888b77](https://linux-hardware.org/?probe=198d888b77) | Nov 10, 2021 |
| ASRock        | N68C-GS FX                  | [ab82eb7e00](https://linux-hardware.org/?probe=ab82eb7e00) | Nov 09, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [c75ffcf988](https://linux-hardware.org/?probe=c75ffcf988) | Nov 09, 2021 |
| MSI           | X470 GAMING PLUS            | [ac741fe858](https://linux-hardware.org/?probe=ac741fe858) | Nov 08, 2021 |
| ASRock        | P67 Pro3                    | [093415210f](https://linux-hardware.org/?probe=093415210f) | Nov 07, 2021 |
| Gigabyte      | H410M S2H V3                | [48ffd402a1](https://linux-hardware.org/?probe=48ffd402a1) | Nov 06, 2021 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [0e2e55a9ee](https://linux-hardware.org/?probe=0e2e55a9ee) | Nov 06, 2021 |
| Dell          | 0WWJRX A01                  | [4fa10e9d4b](https://linux-hardware.org/?probe=4fa10e9d4b) | Nov 06, 2021 |
| Gigabyte      | G41MT-S2P                   | [cb6063a277](https://linux-hardware.org/?probe=cb6063a277) | Nov 06, 2021 |
| Gigabyte      | B365M DS3H                  | [8e3176012c](https://linux-hardware.org/?probe=8e3176012c) | Nov 05, 2021 |
| Gigabyte      | B365M DS3H                  | [d6e0b55e4c](https://linux-hardware.org/?probe=d6e0b55e4c) | Nov 04, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [13718086c3](https://linux-hardware.org/?probe=13718086c3) | Nov 04, 2021 |
| MSI           | B450 TOMAHAWK               | [7e09d7d036](https://linux-hardware.org/?probe=7e09d7d036) | Nov 04, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [290c114444](https://linux-hardware.org/?probe=290c114444) | Nov 02, 2021 |
| Dell          | 0WWJRX A01                  | [a03dcb58fb](https://linux-hardware.org/?probe=a03dcb58fb) | Nov 01, 2021 |
| MSI           | B460M PRO                   | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [93de1508cb](https://linux-hardware.org/?probe=93de1508cb) | Oct 31, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [5b55e39c35](https://linux-hardware.org/?probe=5b55e39c35) | Oct 31, 2021 |
| HP            | 3048h                       | [b62359fcb1](https://linux-hardware.org/?probe=b62359fcb1) | Oct 31, 2021 |
| MSI           | Z170A SLI PLUS              | [2d4144d0b9](https://linux-hardware.org/?probe=2d4144d0b9) | Oct 30, 2021 |
| Gigabyte      | 945GCM-S2L                  | [35d876d2dc](https://linux-hardware.org/?probe=35d876d2dc) | Oct 30, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [307da27696](https://linux-hardware.org/?probe=307da27696) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| Gigabyte      | G41MT-S2                    | [f493a9d83b](https://linux-hardware.org/?probe=f493a9d83b) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | [4f7e3472c2](https://linux-hardware.org/?probe=4f7e3472c2) | Oct 28, 2021 |
| MSI           | B450-A PRO                  | [f17090e5d2](https://linux-hardware.org/?probe=f17090e5d2) | Oct 27, 2021 |
| MSI           | B450-A PRO                  | [9654efcb43](https://linux-hardware.org/?probe=9654efcb43) | Oct 27, 2021 |
| ASRock        | P67 Pro3                    | [8753243650](https://linux-hardware.org/?probe=8753243650) | Oct 27, 2021 |
| MSI           | H61M-P31                    | [e5bf692305](https://linux-hardware.org/?probe=e5bf692305) | Oct 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | [10373a3fda](https://linux-hardware.org/?probe=10373a3fda) | Oct 26, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [f5ede0a97c](https://linux-hardware.org/?probe=f5ede0a97c) | Oct 25, 2021 |
| ASRock        | P67 Pro3                    | [547cf0429d](https://linux-hardware.org/?probe=547cf0429d) | Oct 25, 2021 |
| ASRock        | G41M-VS3                    | [452a28e8fa](https://linux-hardware.org/?probe=452a28e8fa) | Oct 25, 2021 |
| ASUSTek       | M3A78-CM                    | [aa48dedaf3](https://linux-hardware.org/?probe=aa48dedaf3) | Oct 25, 2021 |
| Gigabyte      | B450 AORUS M                | [93ec7f3964](https://linux-hardware.org/?probe=93ec7f3964) | Oct 24, 2021 |
| ASUSTek       | P5Q3                        | [5dcfd80741](https://linux-hardware.org/?probe=5dcfd80741) | Oct 24, 2021 |
| ASUSTek       | P8Z77-V LX                  | [5bd168595f](https://linux-hardware.org/?probe=5bd168595f) | Oct 24, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | [61823fb44e](https://linux-hardware.org/?probe=61823fb44e) | Oct 22, 2021 |
| MSI           | B450M PRO-VDH MAX           | [b914028ca9](https://linux-hardware.org/?probe=b914028ca9) | Oct 20, 2021 |
| Gigabyte      | B75M-D2V                    | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| ASUSTek       | P7P55 LX                    | [d2e3eb969f](https://linux-hardware.org/?probe=d2e3eb969f) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [92647c0170](https://linux-hardware.org/?probe=92647c0170) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [c7372168fd](https://linux-hardware.org/?probe=c7372168fd) | Oct 18, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [c3c2bded72](https://linux-hardware.org/?probe=c3c2bded72) | Oct 18, 2021 |
| Gigabyte      | Z270N-WIFI-CF               | [5fce73702a](https://linux-hardware.org/?probe=5fce73702a) | Oct 18, 2021 |
| HP            | 0AA0h                       | [fcd03cf9f8](https://linux-hardware.org/?probe=fcd03cf9f8) | Oct 18, 2021 |
| Gigabyte      | H61M-S2PV                   | [d08969a0a4](https://linux-hardware.org/?probe=d08969a0a4) | Oct 17, 2021 |
| Nvidia        | NFORCE 790i ULTRA SLI 2     | [0722780e26](https://linux-hardware.org/?probe=0722780e26) | Oct 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [35b768567f](https://linux-hardware.org/?probe=35b768567f) | Oct 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Gigabyte      | B450M GAMING                | [4e08da267c](https://linux-hardware.org/?probe=4e08da267c) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| ASUSTek       | M4A79XTD EVO                | [9bf523cac3](https://linux-hardware.org/?probe=9bf523cac3) | Oct 15, 2021 |
| Dell          | 0D6H9T A03                  | [77bb1e0ae4](https://linux-hardware.org/?probe=77bb1e0ae4) | Oct 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e2538800e5](https://linux-hardware.org/?probe=e2538800e5) | Oct 15, 2021 |
| ASUSTek       | M4A79XTD EVO                | [9c4214d1c5](https://linux-hardware.org/?probe=9c4214d1c5) | Oct 14, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [0cb83b4b82](https://linux-hardware.org/?probe=0cb83b4b82) | Oct 14, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [1d5dc0eb72](https://linux-hardware.org/?probe=1d5dc0eb72) | Oct 14, 2021 |
| ASRock        | Z370 Extreme4               | [48560dd08a](https://linux-hardware.org/?probe=48560dd08a) | Oct 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Dell          | 0P611C A00                  | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| Dell          | 0P611C A00                  | [0693495a61](https://linux-hardware.org/?probe=0693495a61) | Oct 11, 2021 |
| Gigabyte      | B150M-D3H-CF                | [98fb2fe756](https://linux-hardware.org/?probe=98fb2fe756) | Oct 11, 2021 |
| Gigabyte      | B150M-D3H-CF                | [44c782c730](https://linux-hardware.org/?probe=44c782c730) | Oct 11, 2021 |
| ASRock        | Z390 Extreme4               | [2da9a06ef2](https://linux-hardware.org/?probe=2da9a06ef2) | Oct 11, 2021 |
| ASUSTek       | PRIME H410M-E               | [b79b71ae45](https://linux-hardware.org/?probe=b79b71ae45) | Oct 11, 2021 |
| ASUSTek       | M2A-MX                      | [6301dbd834](https://linux-hardware.org/?probe=6301dbd834) | Oct 11, 2021 |
| Gigabyte      | M61PME-S2P                  | [ea3f4620bf](https://linux-hardware.org/?probe=ea3f4620bf) | Oct 10, 2021 |
| Dell          | 0PU052                      | [42be865dc0](https://linux-hardware.org/?probe=42be865dc0) | Oct 10, 2021 |
| Dell          | 0PU052                      | [ec8f46ab8b](https://linux-hardware.org/?probe=ec8f46ab8b) | Oct 10, 2021 |
| ASUSTek       | M2N                         | [f319cddaf6](https://linux-hardware.org/?probe=f319cddaf6) | Oct 09, 2021 |
| MSI           | H310M PRO-VH                | [64f79e5d38](https://linux-hardware.org/?probe=64f79e5d38) | Oct 08, 2021 |
| MSI           | Z170A SLI PLUS              | [ca217e43ff](https://linux-hardware.org/?probe=ca217e43ff) | Oct 07, 2021 |
| HP            | 0B4Ch D                     | [b3870611eb](https://linux-hardware.org/?probe=b3870611eb) | Oct 07, 2021 |
| MSI           | B450 TOMAHAWK               | [f50b61b450](https://linux-hardware.org/?probe=f50b61b450) | Oct 06, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [372dc0e0aa](https://linux-hardware.org/?probe=372dc0e0aa) | Oct 06, 2021 |
| Gigabyte      | H61M-S2PV                   | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| MSI           | B450I GAMING PLUS AC        | [1ca6c5085e](https://linux-hardware.org/?probe=1ca6c5085e) | Oct 04, 2021 |
| MSI           | B150M PRO-VDH               | [b895ca1b63](https://linux-hardware.org/?probe=b895ca1b63) | Oct 04, 2021 |
| MSI           | B360M PRO-VD                | [5d1fb1f342](https://linux-hardware.org/?probe=5d1fb1f342) | Oct 04, 2021 |
| HP            | 212B                        | [322371cc6a](https://linux-hardware.org/?probe=322371cc6a) | Oct 04, 2021 |
| Gigabyte      | GA-970A-UD3                 | [3d18262d97](https://linux-hardware.org/?probe=3d18262d97) | Oct 03, 2021 |
| MSI           | B360M PRO-VD                | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| Gigabyte      | B85M-D3H                    | [c264fff200](https://linux-hardware.org/?probe=c264fff200) | Oct 01, 2021 |
| Gigabyte      | M61VME-S2                   | [51f657f344](https://linux-hardware.org/?probe=51f657f344) | Oct 01, 2021 |
| Gigabyte      | M61VME-S2                   | [a9ce018e0a](https://linux-hardware.org/?probe=a9ce018e0a) | Oct 01, 2021 |
| Gigabyte      | Z97N-WIFI                   | [539316ac91](https://linux-hardware.org/?probe=539316ac91) | Sep 30, 2021 |
| Gigabyte      | Z97N-WIFI                   | [95ae5d0e04](https://linux-hardware.org/?probe=95ae5d0e04) | Sep 29, 2021 |
| Gigabyte      | 945G-S3                     | [53e0a8820c](https://linux-hardware.org/?probe=53e0a8820c) | Sep 28, 2021 |
| HP            | 0B4Ch D                     | [559af7bff6](https://linux-hardware.org/?probe=559af7bff6) | Sep 28, 2021 |
| HP            | 0B4Ch D                     | [2faf81d586](https://linux-hardware.org/?probe=2faf81d586) | Sep 28, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [37d30a84ca](https://linux-hardware.org/?probe=37d30a84ca) | Sep 27, 2021 |
| MSI           | X399 SLI PLUS               | [4d6c77accb](https://linux-hardware.org/?probe=4d6c77accb) | Sep 26, 2021 |
| HP            | 18E7                        | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| MSI           | MAG B550M BAZOOKA           | [d06dd7e0ec](https://linux-hardware.org/?probe=d06dd7e0ec) | Sep 25, 2021 |
| HP            | 18E7                        | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| HP            | 18E7                        | [4c52ebef48](https://linux-hardware.org/?probe=4c52ebef48) | Sep 22, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [8d112d9531](https://linux-hardware.org/?probe=8d112d9531) | Sep 21, 2021 |
| Dell          | 040DDP A01                  | [f2e1fbb30c](https://linux-hardware.org/?probe=f2e1fbb30c) | Sep 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [b767020eb6](https://linux-hardware.org/?probe=b767020eb6) | Sep 21, 2021 |
| Intel         | DP55WB AAE64798-204         | [d4b171dc3d](https://linux-hardware.org/?probe=d4b171dc3d) | Sep 19, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5b1bf150bb](https://linux-hardware.org/?probe=5b1bf150bb) | Sep 19, 2021 |
| Hampoo        | Cherry Trail CR             | [a059116962](https://linux-hardware.org/?probe=a059116962) | Sep 18, 2021 |
| Gigabyte      | AX370-Gaming 5              | [5608b1aae3](https://linux-hardware.org/?probe=5608b1aae3) | Sep 18, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [a428f57f6a](https://linux-hardware.org/?probe=a428f57f6a) | Sep 17, 2021 |
| Gigabyte      | X99-UD3-CF                  | [c70024afd4](https://linux-hardware.org/?probe=c70024afd4) | Sep 16, 2021 |
| ASRock        | B85 Pro4                    | [fd3e875a73](https://linux-hardware.org/?probe=fd3e875a73) | Sep 14, 2021 |
| MSI           | H61M-P20                    | [5c930b615e](https://linux-hardware.org/?probe=5c930b615e) | Sep 14, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [51a17a84a4](https://linux-hardware.org/?probe=51a17a84a4) | Sep 13, 2021 |
| ASUSTek       | Z170-P                      | [35710b3bec](https://linux-hardware.org/?probe=35710b3bec) | Sep 13, 2021 |
| Gigabyte      | H61MA-D2V                   | [df2e5620c6](https://linux-hardware.org/?probe=df2e5620c6) | Sep 11, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [55cce80c82](https://linux-hardware.org/?probe=55cce80c82) | Sep 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [0e6deb049c](https://linux-hardware.org/?probe=0e6deb049c) | Sep 09, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [b6b99a61a3](https://linux-hardware.org/?probe=b6b99a61a3) | Sep 07, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [e6b54f6ad3](https://linux-hardware.org/?probe=e6b54f6ad3) | Sep 07, 2021 |
| HP            | 82F1                        | [d7aab7611a](https://linux-hardware.org/?probe=d7aab7611a) | Sep 07, 2021 |
| HP            | 82F1                        | [5f01149ce6](https://linux-hardware.org/?probe=5f01149ce6) | Sep 07, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [d0654a3b7f](https://linux-hardware.org/?probe=d0654a3b7f) | Sep 07, 2021 |
| Fujitsu Si... | D2451-A2 S26361-D2451-A2    | [7106ac4458](https://linux-hardware.org/?probe=7106ac4458) | Sep 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [19555ed132](https://linux-hardware.org/?probe=19555ed132) | Sep 07, 2021 |
| Lenovo        | MAHOBAY                     | [768a809221](https://linux-hardware.org/?probe=768a809221) | Sep 06, 2021 |
| Fujitsu Si... | MS-7504VP-PV                | [53c7457a1d](https://linux-hardware.org/?probe=53c7457a1d) | Sep 06, 2021 |
| Intel         | DP55WB AAE64798-204         | [abc17b67fe](https://linux-hardware.org/?probe=abc17b67fe) | Sep 03, 2021 |
| HP            | 3047h                       | [1fe7c1728e](https://linux-hardware.org/?probe=1fe7c1728e) | Sep 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3fffe95986](https://linux-hardware.org/?probe=3fffe95986) | Sep 02, 2021 |
| HP            | 1998                        | [585ff46bb3](https://linux-hardware.org/?probe=585ff46bb3) | Sep 01, 2021 |
| ASRock        | Z370 Extreme4               | [274aa69a6b](https://linux-hardware.org/?probe=274aa69a6b) | Aug 31, 2021 |
| ASUSTek       | P7P55D-E                    | [4c05b36e94](https://linux-hardware.org/?probe=4c05b36e94) | Aug 31, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [078613f010](https://linux-hardware.org/?probe=078613f010) | Aug 31, 2021 |
| Gigabyte      | H97-HD3                     | [c72a8f9c61](https://linux-hardware.org/?probe=c72a8f9c61) | Aug 29, 2021 |
| MSI           | H170 GAMING M3              | [7affee0cde](https://linux-hardware.org/?probe=7affee0cde) | Aug 28, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [9c8cf8ff6a](https://linux-hardware.org/?probe=9c8cf8ff6a) | Aug 27, 2021 |
| HP            | 3396                        | [35b0f473e3](https://linux-hardware.org/?probe=35b0f473e3) | Aug 27, 2021 |
| MSI           | H61M-P20                    | [a4322b4668](https://linux-hardware.org/?probe=a4322b4668) | Aug 27, 2021 |
| Intel         | DP55WB AAE64798-204         | [2584a3d10e](https://linux-hardware.org/?probe=2584a3d10e) | Aug 26, 2021 |
| Gigabyte      | H97-HD3                     | [43d70d4502](https://linux-hardware.org/?probe=43d70d4502) | Aug 26, 2021 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [9f13d9bb73](https://linux-hardware.org/?probe=9f13d9bb73) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| Lenovo        | ThinkCentre M57 6072A5G     | [6c4905a177](https://linux-hardware.org/?probe=6c4905a177) | Aug 25, 2021 |
| Dell          | 040DDP A01                  | [557d74beb9](https://linux-hardware.org/?probe=557d74beb9) | Aug 25, 2021 |
| Gigabyte      | GA-MA790X-UD3P              | [91083a6c1a](https://linux-hardware.org/?probe=91083a6c1a) | Aug 23, 2021 |
| ASUSTek       | PRIME B450M-K               | [1e43a5f2a3](https://linux-hardware.org/?probe=1e43a5f2a3) | Aug 22, 2021 |
| ASUSTek       | PRIME B450M-K               | [c7aac1aef0](https://linux-hardware.org/?probe=c7aac1aef0) | Aug 22, 2021 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [443f040d6b](https://linux-hardware.org/?probe=443f040d6b) | Aug 20, 2021 |
| Dell          | 0HY9JP A02                  | [8da5fad507](https://linux-hardware.org/?probe=8da5fad507) | Aug 20, 2021 |
| ASRock        | P67 Pro3                    | [9d78fc5336](https://linux-hardware.org/?probe=9d78fc5336) | Aug 20, 2021 |
| Dell          | 0P611C A00                  | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| ASUSTek       | B150M-A/M.2                 | [17dcdbd10b](https://linux-hardware.org/?probe=17dcdbd10b) | Aug 19, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [574d8376d0](https://linux-hardware.org/?probe=574d8376d0) | Aug 19, 2021 |
| ASUSTek       | B150M-A/M.2                 | [4689c50342](https://linux-hardware.org/?probe=4689c50342) | Aug 19, 2021 |
| ASUSTek       | M4N68T V2                   | [6441a522b9](https://linux-hardware.org/?probe=6441a522b9) | Aug 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [eb1e9924f7](https://linux-hardware.org/?probe=eb1e9924f7) | Aug 18, 2021 |
| ASUSTek       | Z170-WS                     | [ac73f29c0f](https://linux-hardware.org/?probe=ac73f29c0f) | Aug 18, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [5f48acede8](https://linux-hardware.org/?probe=5f48acede8) | Aug 15, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [f13ee3f357](https://linux-hardware.org/?probe=f13ee3f357) | Aug 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [2af094f75d](https://linux-hardware.org/?probe=2af094f75d) | Aug 10, 2021 |
| Lenovo        | NO DPK                      | [cd3eba7a96](https://linux-hardware.org/?probe=cd3eba7a96) | Aug 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [8ad0df4157](https://linux-hardware.org/?probe=8ad0df4157) | Aug 09, 2021 |
| MSI           | B360M PRO-VD 2019-01-24     | [8168eff4f5](https://linux-hardware.org/?probe=8168eff4f5) | Aug 08, 2021 |
| Gigabyte      | P35-DS3L                    | [8ec91a1fba](https://linux-hardware.org/?probe=8ec91a1fba) | Aug 08, 2021 |
| Gigabyte      | P35-DS3L                    | [a05d48ccf2](https://linux-hardware.org/?probe=a05d48ccf2) | Aug 08, 2021 |
| ASRock        | P67 Pro3                    | [3eca7094db](https://linux-hardware.org/?probe=3eca7094db) | Aug 08, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [c149c02018](https://linux-hardware.org/?probe=c149c02018) | Aug 06, 2021 |
| ASRock        | B450 Pro4                   | [1de50a3b72](https://linux-hardware.org/?probe=1de50a3b72) | Aug 05, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [0601acbf37](https://linux-hardware.org/?probe=0601acbf37) | Aug 05, 2021 |
| HP            | 1497                        | [20ebab5f20](https://linux-hardware.org/?probe=20ebab5f20) | Aug 04, 2021 |
| MSI           | B450 TOMAHAWK               | [ebd09ec38b](https://linux-hardware.org/?probe=ebd09ec38b) | Aug 02, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [4e92657f52](https://linux-hardware.org/?probe=4e92657f52) | Aug 02, 2021 |
| Gigabyte      | B450M S2H V2                | [73249b9da9](https://linux-hardware.org/?probe=73249b9da9) | Aug 01, 2021 |
| ASRock        | H81M-HDS                    | [f6d31fab90](https://linux-hardware.org/?probe=f6d31fab90) | Aug 01, 2021 |
| Lenovo        | SKYBAY NOK                  | [91c5b3d4cc](https://linux-hardware.org/?probe=91c5b3d4cc) | Jul 31, 2021 |
| MSI           | G31TM-P21                   | [024df6a0c1](https://linux-hardware.org/?probe=024df6a0c1) | Jul 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [41c1c2551d](https://linux-hardware.org/?probe=41c1c2551d) | Jul 29, 2021 |
| ASRock        | P67 Pro3                    | [75da5ecc21](https://linux-hardware.org/?probe=75da5ecc21) | Jul 28, 2021 |
| Lenovo        | ThinkCentre M91p 7033DE6    | [aa42758551](https://linux-hardware.org/?probe=aa42758551) | Jul 27, 2021 |
| Lenovo        | ThinkCentre M91p 7033DE6    | [ea9486d3cb](https://linux-hardware.org/?probe=ea9486d3cb) | Jul 27, 2021 |
| Foxconn       | 2AAF                        | [9eb5763b8d](https://linux-hardware.org/?probe=9eb5763b8d) | Jul 27, 2021 |
| ASRock        | G31M-GS                     | [1ed49dd5fd](https://linux-hardware.org/?probe=1ed49dd5fd) | Jul 26, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [50053faafe](https://linux-hardware.org/?probe=50053faafe) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Gigabyte      | B560M D3H                   | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| ASUSTek       | P7H55-USB3                  | [cd727a9f3d](https://linux-hardware.org/?probe=cd727a9f3d) | Jul 22, 2021 |
| Dell          | 0W0CHX A01                  | [d4f3e21abc](https://linux-hardware.org/?probe=d4f3e21abc) | Jul 22, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [f00892d38b](https://linux-hardware.org/?probe=f00892d38b) | Jul 22, 2021 |
| Gigabyte      | B460M DS3H                  | [f51701bc3a](https://linux-hardware.org/?probe=f51701bc3a) | Jul 21, 2021 |
| ASRock        | 880GM-LE FX                 | [19b241a883](https://linux-hardware.org/?probe=19b241a883) | Jul 18, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [9ceb18858a](https://linux-hardware.org/?probe=9ceb18858a) | Jul 16, 2021 |
| MSI           | X399 SLI PLUS               | [00b0b9f630](https://linux-hardware.org/?probe=00b0b9f630) | Jul 15, 2021 |
| Dell          | 0V8WGR A00                  | [e8fe0e62a8](https://linux-hardware.org/?probe=e8fe0e62a8) | Jul 15, 2021 |
| Dell          | 0V8WGR A00                  | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| Gigabyte      | G31M-S2L                    | [8dbd5a3bee](https://linux-hardware.org/?probe=8dbd5a3bee) | Jul 13, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [b31915ba25](https://linux-hardware.org/?probe=b31915ba25) | Jul 13, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f60f031bde](https://linux-hardware.org/?probe=f60f031bde) | Jul 13, 2021 |
| ASRock        | B450M Pro4                  | [a7a2abffd6](https://linux-hardware.org/?probe=a7a2abffd6) | Jul 12, 2021 |
| HP            | 3047h                       | [27e2083302](https://linux-hardware.org/?probe=27e2083302) | Jul 12, 2021 |
| HP            | 3047h                       | [dd341bf85a](https://linux-hardware.org/?probe=dd341bf85a) | Jul 12, 2021 |
| ASRock        | P67 Pro3                    | [f2c66dab20](https://linux-hardware.org/?probe=f2c66dab20) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [fe6c28a62e](https://linux-hardware.org/?probe=fe6c28a62e) | Jul 11, 2021 |
| AMD           | 970A-D3                     | [95fa7132e5](https://linux-hardware.org/?probe=95fa7132e5) | Jul 09, 2021 |
| ASRock        | 880GM-LE FX                 | [ed6f3d1c5f](https://linux-hardware.org/?probe=ed6f3d1c5f) | Jul 08, 2021 |
| MSI           | H110M PRO-D 2018-01-02      | [28f5eab76c](https://linux-hardware.org/?probe=28f5eab76c) | Jul 08, 2021 |
| ASRock        | B150 Gaming K4/Hyper        | [f5a867e446](https://linux-hardware.org/?probe=f5a867e446) | Jul 07, 2021 |
| Gigabyte      | M61PME-S2                   | [8c1e919c7b](https://linux-hardware.org/?probe=8c1e919c7b) | Jul 07, 2021 |
| HP            | 3397                        | [10586fd6fe](https://linux-hardware.org/?probe=10586fd6fe) | Jul 07, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [f8e4042adf](https://linux-hardware.org/?probe=f8e4042adf) | Jul 07, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [26c314a246](https://linux-hardware.org/?probe=26c314a246) | Jul 07, 2021 |
| ASRock        | P67 Pro3                    | [0a78c8bdc4](https://linux-hardware.org/?probe=0a78c8bdc4) | Jul 06, 2021 |
| ASUSTek       | B85M-G                      | [56c6bcf36b](https://linux-hardware.org/?probe=56c6bcf36b) | Jul 04, 2021 |
| Gigabyte      | B360M D3H-CF                | [68d69df57d](https://linux-hardware.org/?probe=68d69df57d) | Jul 03, 2021 |
| ASRock        | B450 Gaming K4              | [efb2ed36b3](https://linux-hardware.org/?probe=efb2ed36b3) | Jul 02, 2021 |
| Gigabyte      | GA-MA770T-UD3P              | [ce2833b036](https://linux-hardware.org/?probe=ce2833b036) | Jul 02, 2021 |
| MSI           | MAG B550M BAZOOKA           | [4b5c67ca01](https://linux-hardware.org/?probe=4b5c67ca01) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a37dd487ac](https://linux-hardware.org/?probe=a37dd487ac) | Jun 30, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [721a62cb48](https://linux-hardware.org/?probe=721a62cb48) | Jun 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a8268a0c9d](https://linux-hardware.org/?probe=a8268a0c9d) | Jun 29, 2021 |
| MSI           | B85M-G43                    | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| MSI           | B75MA-E33                   | [6711bba80c](https://linux-hardware.org/?probe=6711bba80c) | Jun 27, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | [cabbfc392e](https://linux-hardware.org/?probe=cabbfc392e) | Jun 27, 2021 |
| ASRock        | H310CM-DVS                  | [f8e9ea8ffa](https://linux-hardware.org/?probe=f8e9ea8ffa) | Jun 26, 2021 |
| Lenovo        | SKYBAY NOK                  | [34c78b88c0](https://linux-hardware.org/?probe=34c78b88c0) | Jun 26, 2021 |
| Lenovo        | SKYBAY NOK                  | [0331a8d6fb](https://linux-hardware.org/?probe=0331a8d6fb) | Jun 26, 2021 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [b372f153bc](https://linux-hardware.org/?probe=b372f153bc) | Jun 25, 2021 |
| ASRock        | X399 Taichi                 | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| Hardkernel    | ODROID-H2                   | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| MSI           | X470 GAMING PLUS            | [6e3bc83381](https://linux-hardware.org/?probe=6e3bc83381) | Jun 23, 2021 |
| Dell          | 06D7TR A00                  | [9d37088823](https://linux-hardware.org/?probe=9d37088823) | Jun 23, 2021 |
| HP            | ProLiant ML150 G5           | [dd931cb4e6](https://linux-hardware.org/?probe=dd931cb4e6) | Jun 21, 2021 |
| ASRock        | Z97 Extreme4                | [9974950d4a](https://linux-hardware.org/?probe=9974950d4a) | Jun 21, 2021 |
| MSI           | Z170A GAMING M3             | [813c6365dd](https://linux-hardware.org/?probe=813c6365dd) | Jun 21, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a7bf20a30a](https://linux-hardware.org/?probe=a7bf20a30a) | Jun 21, 2021 |
| HP            | 1495                        | [03ab704550](https://linux-hardware.org/?probe=03ab704550) | Jun 20, 2021 |
| ASUSTek       | P9X79                       | [7c86a49663](https://linux-hardware.org/?probe=7c86a49663) | Jun 20, 2021 |
| ASRock        | X300M-STX                   | [e1d7a4d7d9](https://linux-hardware.org/?probe=e1d7a4d7d9) | Jun 19, 2021 |
| ASUSTek       | PRIME A320M-E               | [edb0b62fe0](https://linux-hardware.org/?probe=edb0b62fe0) | Jun 19, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [ed109bbeda](https://linux-hardware.org/?probe=ed109bbeda) | Jun 19, 2021 |
| Gigabyte      | GA-770T-USB3                | [ecf185efee](https://linux-hardware.org/?probe=ecf185efee) | Jun 19, 2021 |
| HP            | 3396                        | [8ba99c8dc7](https://linux-hardware.org/?probe=8ba99c8dc7) | Jun 19, 2021 |
| ASUSTek       | P5K                         | [34ef967bda](https://linux-hardware.org/?probe=34ef967bda) | Jun 19, 2021 |
| Gateway       | DT55                        | [9fb46dff42](https://linux-hardware.org/?probe=9fb46dff42) | Jun 18, 2021 |
| ASUSTek       | P7P55D-E                    | [af93741579](https://linux-hardware.org/?probe=af93741579) | Jun 17, 2021 |
| ASUSTek       | P7P55D-E                    | [deda35b200](https://linux-hardware.org/?probe=deda35b200) | Jun 17, 2021 |
| Gigabyte      | P31-DS3L                    | [5b93bcdc50](https://linux-hardware.org/?probe=5b93bcdc50) | Jun 17, 2021 |
| Gigabyte      | Z97-HD3                     | [c9eaba9715](https://linux-hardware.org/?probe=c9eaba9715) | Jun 17, 2021 |
| Gigabyte      | Z97-HD3                     | [8462db65b3](https://linux-hardware.org/?probe=8462db65b3) | Jun 17, 2021 |
| HP            | 3396                        | [9ab143ae50](https://linux-hardware.org/?probe=9ab143ae50) | Jun 16, 2021 |
| ASRock        | B560M-ITX/ac                | [2284cea3c5](https://linux-hardware.org/?probe=2284cea3c5) | Jun 14, 2021 |
| Acer          | Aspire XC-885 V:1.1         | [1dc96e4cb2](https://linux-hardware.org/?probe=1dc96e4cb2) | Jun 14, 2021 |
| Gigabyte      | G31M-S2L                    | [320f226d6b](https://linux-hardware.org/?probe=320f226d6b) | Jun 13, 2021 |
| ASUSTek       | F1A55-M LX                  | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Acer          | Aspire XC-885 V:1.1         | [d59e07968c](https://linux-hardware.org/?probe=d59e07968c) | Jun 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | [85b8628f9c](https://linux-hardware.org/?probe=85b8628f9c) | Jun 10, 2021 |
| HP            | 8055                        | [99139c7f32](https://linux-hardware.org/?probe=99139c7f32) | Jun 10, 2021 |
| Dell          | 03X0YG A00                  | [b8b1d9b51f](https://linux-hardware.org/?probe=b8b1d9b51f) | Jun 10, 2021 |
| Dell          | 03X0YG A00                  | [5b7a69b168](https://linux-hardware.org/?probe=5b7a69b168) | Jun 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [85ad270405](https://linux-hardware.org/?probe=85ad270405) | Jun 09, 2021 |
| MSI           | Z170A GAMING M3             | [2f2598fde1](https://linux-hardware.org/?probe=2f2598fde1) | Jun 09, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [7b820949e3](https://linux-hardware.org/?probe=7b820949e3) | Jun 07, 2021 |
| ASUSTek       | Maximus VII RANGER          | [4552fd3861](https://linux-hardware.org/?probe=4552fd3861) | Jun 05, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [5f64f722de](https://linux-hardware.org/?probe=5f64f722de) | Jun 04, 2021 |
| HP            | 0A80h                       | [ffbf3f551c](https://linux-hardware.org/?probe=ffbf3f551c) | Jun 04, 2021 |
| Gigabyte      | F2A88XM-HD3P                | [19bf6ac286](https://linux-hardware.org/?probe=19bf6ac286) | Jun 02, 2021 |
| ASUSTek       | M2N                         | [f5537f32f6](https://linux-hardware.org/?probe=f5537f32f6) | Jun 02, 2021 |
| HP            | 18E7                        | [ac4f9cd1e4](https://linux-hardware.org/?probe=ac4f9cd1e4) | Jun 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ad37db1da8](https://linux-hardware.org/?probe=ad37db1da8) | Jun 01, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [20115ee05d](https://linux-hardware.org/?probe=20115ee05d) | May 31, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ea164260eb](https://linux-hardware.org/?probe=ea164260eb) | May 30, 2021 |
| ASUSTek       | P5Q                         | [102c78ca6b](https://linux-hardware.org/?probe=102c78ca6b) | May 30, 2021 |
| ASUSTek       | H110M-K                     | [8b94f08ea9](https://linux-hardware.org/?probe=8b94f08ea9) | May 30, 2021 |
| Gigabyte      | F2A68HM-DS2                 | [d37ffbb64d](https://linux-hardware.org/?probe=d37ffbb64d) | May 30, 2021 |
| HP            | 1825                        | [2efdb3364c](https://linux-hardware.org/?probe=2efdb3364c) | May 29, 2021 |
| ASUSTek       | P6X58D PREMIUM              | [04bc38919d](https://linux-hardware.org/?probe=04bc38919d) | May 27, 2021 |
| ASUSTek       | Z170-A                      | [5a56ed934e](https://linux-hardware.org/?probe=5a56ed934e) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Hardkernel    | ODROID-H2                   | [f1c998fd68](https://linux-hardware.org/?probe=f1c998fd68) | May 27, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [7b080b315d](https://linux-hardware.org/?probe=7b080b315d) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [49458a2df1](https://linux-hardware.org/?probe=49458a2df1) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [73ff247804](https://linux-hardware.org/?probe=73ff247804) | May 24, 2021 |
| Gigabyte      | G41M-ES2L                   | [862a8136da](https://linux-hardware.org/?probe=862a8136da) | May 23, 2021 |
| HP            | 21B4 A01                    | [b2a7cbbc72](https://linux-hardware.org/?probe=b2a7cbbc72) | May 23, 2021 |
| MSI           | B450M PRO-VDH MAX           | [c13d9f5b1c](https://linux-hardware.org/?probe=c13d9f5b1c) | May 23, 2021 |
| ASRock        | P67 Extreme4 Gen3           | [7c88cbaca4](https://linux-hardware.org/?probe=7c88cbaca4) | May 22, 2021 |
| ASRock        | X370 Gaming K4              | [4945bb80f6](https://linux-hardware.org/?probe=4945bb80f6) | May 22, 2021 |
| Gigabyte      | B450M DS3H V2               | [fb56f8288c](https://linux-hardware.org/?probe=fb56f8288c) | May 20, 2021 |
| Dell          | 0MN1TX A02                  | [3649e87174](https://linux-hardware.org/?probe=3649e87174) | May 20, 2021 |
| MSI           | Z490-A PRO                  | [099f671965](https://linux-hardware.org/?probe=099f671965) | May 20, 2021 |
| Dell          | 07T4MC A06                  | [a897526e05](https://linux-hardware.org/?probe=a897526e05) | May 20, 2021 |
| ASRock        | B450M-HDV R4.0              | [ddfe84cf8f](https://linux-hardware.org/?probe=ddfe84cf8f) | May 19, 2021 |
| HP            | 21B4 A01                    | [45752d3232](https://linux-hardware.org/?probe=45752d3232) | May 18, 2021 |
| Dell          | 077RRV A00                  | [c9ed9d5dfa](https://linux-hardware.org/?probe=c9ed9d5dfa) | May 17, 2021 |
| Gigabyte      | A320M-H-CF                  | [dbe2caea58](https://linux-hardware.org/?probe=dbe2caea58) | May 17, 2021 |
| Lenovo        | SKYBAY NOK                  | [c98ff79ae8](https://linux-hardware.org/?probe=c98ff79ae8) | May 16, 2021 |
| Gigabyte      | 945GCM-S2L                  | [c431100fe6](https://linux-hardware.org/?probe=c431100fe6) | May 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [c49097ec08](https://linux-hardware.org/?probe=c49097ec08) | May 13, 2021 |
| ASUSTek       | P9X79 DELUXE                | [f759ad1793](https://linux-hardware.org/?probe=f759ad1793) | May 13, 2021 |
| ASUSTek       | P9X79 DELUXE                | [f28f1ea67d](https://linux-hardware.org/?probe=f28f1ea67d) | May 13, 2021 |
| Gigabyte      | M61PME-S2P                  | [547d15d845](https://linux-hardware.org/?probe=547d15d845) | May 12, 2021 |
| Gigabyte      | 945GCM-S2L                  | [ca35acdb46](https://linux-hardware.org/?probe=ca35acdb46) | May 11, 2021 |
| Gigabyte      | 945GCM-S2L                  | [39e3ca7ab0](https://linux-hardware.org/?probe=39e3ca7ab0) | May 11, 2021 |
| ASRock        | Z370 Pro4                   | [f088e82ae8](https://linux-hardware.org/?probe=f088e82ae8) | May 11, 2021 |
| HP            | 0B4Ch D                     | [83c114d947](https://linux-hardware.org/?probe=83c114d947) | May 11, 2021 |
| Gigabyte      | B365M DS3H                  | [740af6c089](https://linux-hardware.org/?probe=740af6c089) | May 10, 2021 |
| Gigabyte      | H81M-DS2                    | [a7eee355c3](https://linux-hardware.org/?probe=a7eee355c3) | May 10, 2021 |
| Gigabyte      | H81M-DS2                    | [fe0d3c24c8](https://linux-hardware.org/?probe=fe0d3c24c8) | May 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [df8b93d84c](https://linux-hardware.org/?probe=df8b93d84c) | May 10, 2021 |
| Gigabyte      | B85M-HD3 R4                 | [0950e49e1a](https://linux-hardware.org/?probe=0950e49e1a) | May 09, 2021 |
| HP            | 21B4 A01                    | [d0c8bf4fec](https://linux-hardware.org/?probe=d0c8bf4fec) | May 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2b614a90fc](https://linux-hardware.org/?probe=2b614a90fc) | May 08, 2021 |
| HP            | 3029h                       | [dfcd82490e](https://linux-hardware.org/?probe=dfcd82490e) | May 08, 2021 |
| HP            | 3029h                       | [f54bf8eeb9](https://linux-hardware.org/?probe=f54bf8eeb9) | May 08, 2021 |
| ASUSTek       | Rampage III Extreme         | [673401ac14](https://linux-hardware.org/?probe=673401ac14) | May 07, 2021 |
| Gigabyte      | B365M DS3H                  | [31732d19ac](https://linux-hardware.org/?probe=31732d19ac) | May 07, 2021 |
| ASUSTek       | M3A78-CM                    | [e305a7301f](https://linux-hardware.org/?probe=e305a7301f) | May 05, 2021 |
| MSI           | Z97-G43                     | [c46c37e02c](https://linux-hardware.org/?probe=c46c37e02c) | May 04, 2021 |
| MSI           | P55-GD80                    | [e9002ad1ad](https://linux-hardware.org/?probe=e9002ad1ad) | May 04, 2021 |
| MSI           | B450 GAMING PLUS            | [45f40c1d2b](https://linux-hardware.org/?probe=45f40c1d2b) | May 04, 2021 |
| Dell          | 0MN1TX A02                  | [e71f0f6329](https://linux-hardware.org/?probe=e71f0f6329) | May 03, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [c9f5d6fdd0](https://linux-hardware.org/?probe=c9f5d6fdd0) | May 03, 2021 |
| ASUSTek       | Maximus VII RANGER          | [75ba67766b](https://linux-hardware.org/?probe=75ba67766b) | May 02, 2021 |
| ASUSTek       | Maximus VII RANGER          | [b970eca514](https://linux-hardware.org/?probe=b970eca514) | May 02, 2021 |
| Intel         | DH67BL AAG10189-209         | [61ae6af54a](https://linux-hardware.org/?probe=61ae6af54a) | May 01, 2021 |
| MSI           | P55-GD80                    | [a950a914fc](https://linux-hardware.org/?probe=a950a914fc) | May 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e019fb0b7a](https://linux-hardware.org/?probe=e019fb0b7a) | May 01, 2021 |
| Huanan        | X79-ZD3 INTEL (INTEL Xeo... | [242451df87](https://linux-hardware.org/?probe=242451df87) | May 01, 2021 |
| HP            | 339A                        | [51ca5c6660](https://linux-hardware.org/?probe=51ca5c6660) | Apr 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ac1ae66d11](https://linux-hardware.org/?probe=ac1ae66d11) | Apr 29, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [9337626cbe](https://linux-hardware.org/?probe=9337626cbe) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | [fe32c3d470](https://linux-hardware.org/?probe=fe32c3d470) | Apr 29, 2021 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [69827caaf1](https://linux-hardware.org/?probe=69827caaf1) | Apr 28, 2021 |
| HP            | 0B4Ch D                     | [38245f30c8](https://linux-hardware.org/?probe=38245f30c8) | Apr 28, 2021 |
| ASUSTek       | M2N68 Plus                  | [2b058a72c6](https://linux-hardware.org/?probe=2b058a72c6) | Apr 27, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [eef5b9201a](https://linux-hardware.org/?probe=eef5b9201a) | Apr 27, 2021 |
| ASRock        | ConRoe1333-D667             | [4d5ee48016](https://linux-hardware.org/?probe=4d5ee48016) | Apr 27, 2021 |
| ASRock        | 970M Pro3                   | [39f22700f1](https://linux-hardware.org/?probe=39f22700f1) | Apr 26, 2021 |
| ASRock        | 970M Pro3                   | [dcb079576e](https://linux-hardware.org/?probe=dcb079576e) | Apr 26, 2021 |
| ASRock        | ConRoe1333-D667             | [d2b25b94ef](https://linux-hardware.org/?probe=d2b25b94ef) | Apr 26, 2021 |
| Dell          | 03NVJ6 A01                  | [7469d666a9](https://linux-hardware.org/?probe=7469d666a9) | Apr 26, 2021 |
| Gigabyte      | B85M-D3H                    | [b6e69804f3](https://linux-hardware.org/?probe=b6e69804f3) | Apr 26, 2021 |
| ASUSTek       | Maximus VII RANGER          | [e6db3b7986](https://linux-hardware.org/?probe=e6db3b7986) | Apr 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | [ee47b44b11](https://linux-hardware.org/?probe=ee47b44b11) | Apr 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | [5323cfbbab](https://linux-hardware.org/?probe=5323cfbbab) | Apr 26, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [b31d4b72ea](https://linux-hardware.org/?probe=b31d4b72ea) | Apr 25, 2021 |
| Dell          | 0GM819                      | [9be2fda568](https://linux-hardware.org/?probe=9be2fda568) | Apr 25, 2021 |
| MSI           | Z77A-GD55                   | [4ae20b53ca](https://linux-hardware.org/?probe=4ae20b53ca) | Apr 25, 2021 |
| MSI           | H81M-P33                    | [2156497a05](https://linux-hardware.org/?probe=2156497a05) | Apr 24, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [5ebc04c3d2](https://linux-hardware.org/?probe=5ebc04c3d2) | Apr 24, 2021 |
| HP            | 1497                        | [cfa3220a15](https://linux-hardware.org/?probe=cfa3220a15) | Apr 23, 2021 |
| HP            | 1497                        | [6d68a38b71](https://linux-hardware.org/?probe=6d68a38b71) | Apr 23, 2021 |
| Gigabyte      | 970A-DS3P                   | [befb86f02f](https://linux-hardware.org/?probe=befb86f02f) | Apr 23, 2021 |
| Biostar       | A55MD2                      | [8cd08a4c83](https://linux-hardware.org/?probe=8cd08a4c83) | Apr 23, 2021 |
| Gigabyte      | GA-990XA-UD3                | [4180e4357f](https://linux-hardware.org/?probe=4180e4357f) | Apr 22, 2021 |
| Biostar       | A55MD2                      | [2cc54cd731](https://linux-hardware.org/?probe=2cc54cd731) | Apr 22, 2021 |
| HP            | 21B4 A01                    | [399b0bbaf6](https://linux-hardware.org/?probe=399b0bbaf6) | Apr 22, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [1da5ed3876](https://linux-hardware.org/?probe=1da5ed3876) | Apr 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | [220e356f41](https://linux-hardware.org/?probe=220e356f41) | Apr 22, 2021 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [81a9cbc511](https://linux-hardware.org/?probe=81a9cbc511) | Apr 22, 2021 |
| HP            | 3047h                       | [a99069fd7d](https://linux-hardware.org/?probe=a99069fd7d) | Apr 21, 2021 |
| ECS           | H61H2-M6                    | [2702c2cc08](https://linux-hardware.org/?probe=2702c2cc08) | Apr 21, 2021 |
| ECS           | H61H2-M6                    | [4ed3daaf89](https://linux-hardware.org/?probe=4ed3daaf89) | Apr 21, 2021 |
| Medion        | H77H2-EM V1.0               | [5ccf7b1dd8](https://linux-hardware.org/?probe=5ccf7b1dd8) | Apr 19, 2021 |
| ASRock        | B560M-ITX/ac                | [adc5d5d836](https://linux-hardware.org/?probe=adc5d5d836) | Apr 19, 2021 |
| HP            | 3397                        | [8634cd9219](https://linux-hardware.org/?probe=8634cd9219) | Apr 19, 2021 |
| ASUSTek       | F2A85-M PRO                 | [285fc011a7](https://linux-hardware.org/?probe=285fc011a7) | Apr 18, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [d3d9c37ec8](https://linux-hardware.org/?probe=d3d9c37ec8) | Apr 18, 2021 |
| Gigabyte      | Z97X-Gaming 5               | [7b7d660348](https://linux-hardware.org/?probe=7b7d660348) | Apr 18, 2021 |
| ASUSTek       | F2A85-M PRO                 | [24cda07874](https://linux-hardware.org/?probe=24cda07874) | Apr 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [728e0dcc58](https://linux-hardware.org/?probe=728e0dcc58) | Apr 18, 2021 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [fec7a58b0e](https://linux-hardware.org/?probe=fec7a58b0e) | Apr 18, 2021 |
| MSI           | X370 GAMING PLUS            | [4b65b5304b](https://linux-hardware.org/?probe=4b65b5304b) | Apr 18, 2021 |
| Gigabyte      | G31M-ES2C                   | [1b5a4441c9](https://linux-hardware.org/?probe=1b5a4441c9) | Apr 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [8d55a77677](https://linux-hardware.org/?probe=8d55a77677) | Apr 18, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [8db146ea9f](https://linux-hardware.org/?probe=8db146ea9f) | Apr 18, 2021 |
| MSI           | 970A-G43                    | [028c87678a](https://linux-hardware.org/?probe=028c87678a) | Apr 17, 2021 |
| Acer          | Nitro N50-610               | [d526120c36](https://linux-hardware.org/?probe=d526120c36) | Apr 17, 2021 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [13b77cfa53](https://linux-hardware.org/?probe=13b77cfa53) | Apr 16, 2021 |
| Gigabyte      | B365M DS3H                  | [1749421eaa](https://linux-hardware.org/?probe=1749421eaa) | Apr 16, 2021 |
| Gigabyte      | VM900M                      | [80cc3448b0](https://linux-hardware.org/?probe=80cc3448b0) | Apr 15, 2021 |
| Gigabyte      | GA-MA790XT-UD4P             | [9383f87d8a](https://linux-hardware.org/?probe=9383f87d8a) | Apr 15, 2021 |
| ASRock        | B560M-ITX/ac                | [fa71cac850](https://linux-hardware.org/?probe=fa71cac850) | Apr 14, 2021 |
| Dell          | 0GXM1W A00                  | [f89ce77b43](https://linux-hardware.org/?probe=f89ce77b43) | Apr 14, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [74863db223](https://linux-hardware.org/?probe=74863db223) | Apr 14, 2021 |
| Pegatron      | Benicia                     | [44a36a56ec](https://linux-hardware.org/?probe=44a36a56ec) | Apr 14, 2021 |
| Gigabyte      | X99-UD4-CF                  | [8e1aa2c9ab](https://linux-hardware.org/?probe=8e1aa2c9ab) | Apr 13, 2021 |
| Lenovo        | ThinkCentre M58 7360AEG     | [d1f16010f7](https://linux-hardware.org/?probe=d1f16010f7) | Apr 13, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [22d3682bc9](https://linux-hardware.org/?probe=22d3682bc9) | Apr 13, 2021 |
| ASUSTek       | Rampage III Extreme         | [fb1a69c0f1](https://linux-hardware.org/?probe=fb1a69c0f1) | Apr 12, 2021 |
| Gigabyte      | EP35-DS4                    | [e4af9801ed](https://linux-hardware.org/?probe=e4af9801ed) | Apr 12, 2021 |
| ASUSTek       | Rampage III Extreme         | [e480eb37d7](https://linux-hardware.org/?probe=e480eb37d7) | Apr 12, 2021 |
| ASUSTek       | M2NPV-VM                    | [88db2a30aa](https://linux-hardware.org/?probe=88db2a30aa) | Apr 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| ASUSTek       | P9X79 DELUXE                | [e4a2bb911d](https://linux-hardware.org/?probe=e4a2bb911d) | Apr 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [564a68e751](https://linux-hardware.org/?probe=564a68e751) | Apr 11, 2021 |
| Gigabyte      | X399 AORUS Gaming 7         | [61f0309c59](https://linux-hardware.org/?probe=61f0309c59) | Apr 11, 2021 |
| Gigabyte      | F2A68HM-S1                  | [2c5644ed9f](https://linux-hardware.org/?probe=2c5644ed9f) | Apr 10, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [6af96b8b4e](https://linux-hardware.org/?probe=6af96b8b4e) | Apr 10, 2021 |
| Gigabyte      | B460M D3H                   | [cb1573e77c](https://linux-hardware.org/?probe=cb1573e77c) | Apr 08, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [bf850e3791](https://linux-hardware.org/?probe=bf850e3791) | Apr 08, 2021 |
| MSI           | MS-7360                     | [4fddba3fda](https://linux-hardware.org/?probe=4fddba3fda) | Apr 07, 2021 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [10498e9d12](https://linux-hardware.org/?probe=10498e9d12) | Apr 07, 2021 |
| HP            | 1632                        | [e40860e952](https://linux-hardware.org/?probe=e40860e952) | Apr 06, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [0baaf1410f](https://linux-hardware.org/?probe=0baaf1410f) | Apr 06, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9adc44600c](https://linux-hardware.org/?probe=9adc44600c) | Apr 06, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d517dc305d](https://linux-hardware.org/?probe=d517dc305d) | Apr 05, 2021 |
| Lenovo        | SKYBAY NOK                  | [66b696e9a1](https://linux-hardware.org/?probe=66b696e9a1) | Apr 04, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [7f921e9742](https://linux-hardware.org/?probe=7f921e9742) | Apr 03, 2021 |
| ASUSTek       | P5G41T-M LX                 | [88a775161e](https://linux-hardware.org/?probe=88a775161e) | Apr 03, 2021 |
| HP            | 3047h                       | [549bfffbe7](https://linux-hardware.org/?probe=549bfffbe7) | Apr 03, 2021 |
| AMD           | 970A-D3                     | [bc3361f320](https://linux-hardware.org/?probe=bc3361f320) | Apr 02, 2021 |
| MSI           | MS-B9181                    | [7c467c7f2b](https://linux-hardware.org/?probe=7c467c7f2b) | Apr 02, 2021 |
| MSI           | MS-B9181                    | [5ed3225348](https://linux-hardware.org/?probe=5ed3225348) | Apr 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [8f496b4f1c](https://linux-hardware.org/?probe=8f496b4f1c) | Apr 02, 2021 |
| Gigabyte      | B450M S2H                   | [a36cdead97](https://linux-hardware.org/?probe=a36cdead97) | Apr 01, 2021 |
| HP            | 1632                        | [c6df0e432e](https://linux-hardware.org/?probe=c6df0e432e) | Mar 31, 2021 |
| ASUSTek       | P5G41T-M LX                 | [25e78c811a](https://linux-hardware.org/?probe=25e78c811a) | Mar 31, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [44a5d6634f](https://linux-hardware.org/?probe=44a5d6634f) | Mar 30, 2021 |
| HP            | 1632                        | [8cbfb13fbc](https://linux-hardware.org/?probe=8cbfb13fbc) | Mar 30, 2021 |
| HP            | 1632                        | [50fc7fcff6](https://linux-hardware.org/?probe=50fc7fcff6) | Mar 30, 2021 |
| Gigabyte      | 970A-DS3P                   | [fa469a0435](https://linux-hardware.org/?probe=fa469a0435) | Mar 30, 2021 |
| Dell          | 0YP693 A00                  | [d93369f8d6](https://linux-hardware.org/?probe=d93369f8d6) | Mar 30, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [d888cc04a1](https://linux-hardware.org/?probe=d888cc04a1) | Mar 30, 2021 |
| ASRock        | K10N78D                     | [500f4c7c38](https://linux-hardware.org/?probe=500f4c7c38) | Mar 29, 2021 |
| Dell          | 0MN1TX A02                  | [e8a9989d59](https://linux-hardware.org/?probe=e8a9989d59) | Mar 29, 2021 |
| Gigabyte      | M68M-S2P                    | [7048a5521e](https://linux-hardware.org/?probe=7048a5521e) | Mar 29, 2021 |
| ASUSTek       | P5G41T-M LX                 | [22aa359673](https://linux-hardware.org/?probe=22aa359673) | Mar 28, 2021 |
| ASUSTek       | P5G41T-M LX                 | [bc3cceab26](https://linux-hardware.org/?probe=bc3cceab26) | Mar 28, 2021 |
| ASUSTek       | P5G41T-M LX                 | [981ef499d5](https://linux-hardware.org/?probe=981ef499d5) | Mar 28, 2021 |
| ASUSTek       | P5G41T-M LX                 | [f5335bcba5](https://linux-hardware.org/?probe=f5335bcba5) | Mar 28, 2021 |
| MSI           | 970A-G43                    | [a76657cb4a](https://linux-hardware.org/?probe=a76657cb4a) | Mar 27, 2021 |
| MSI           | 970A-G43                    | [b07f9d715f](https://linux-hardware.org/?probe=b07f9d715f) | Mar 27, 2021 |
| Gigabyte      | H87-HD3                     | [f6a1129d52](https://linux-hardware.org/?probe=f6a1129d52) | Mar 27, 2021 |
| Gigabyte      | Z490 GAMING X               | [f37546f14b](https://linux-hardware.org/?probe=f37546f14b) | Mar 26, 2021 |
| MSI           | B450-A PRO MAX              | [7934f42516](https://linux-hardware.org/?probe=7934f42516) | Mar 26, 2021 |
| Dell          | 0TP412                      | [14bfa58cce](https://linux-hardware.org/?probe=14bfa58cce) | Mar 25, 2021 |
| Gigabyte      | B450M GAMING                | [ce5e898db9](https://linux-hardware.org/?probe=ce5e898db9) | Mar 25, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [f032f846be](https://linux-hardware.org/?probe=f032f846be) | Mar 25, 2021 |
| HP            | 3032h                       | [9194ca17d2](https://linux-hardware.org/?probe=9194ca17d2) | Mar 25, 2021 |
| HP            | 3047h                       | [54170cbd89](https://linux-hardware.org/?probe=54170cbd89) | Mar 25, 2021 |
| ECS           | H67H2-M                     | [be2c22f48c](https://linux-hardware.org/?probe=be2c22f48c) | Mar 24, 2021 |
| Dell          | 0F5C5X A00                  | [dae2cd7252](https://linux-hardware.org/?probe=dae2cd7252) | Mar 23, 2021 |
| Dell          | 0WJ771                      | [aa18fb386c](https://linux-hardware.org/?probe=aa18fb386c) | Mar 23, 2021 |
| MSI           | MAG Z390 TOMAHAWK           | [76d43984b4](https://linux-hardware.org/?probe=76d43984b4) | Mar 23, 2021 |
| Dell          | 0F373D A00                  | [69d783f71b](https://linux-hardware.org/?probe=69d783f71b) | Mar 23, 2021 |
| MSI           | B450M PRO-VDH MAX           | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| MSI           | B150 PC MATE                | [b3eab0c7ac](https://linux-hardware.org/?probe=b3eab0c7ac) | Mar 22, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [9820a77c00](https://linux-hardware.org/?probe=9820a77c00) | Mar 22, 2021 |
| Medion        | MS-7728                     | [45b65ef256](https://linux-hardware.org/?probe=45b65ef256) | Mar 22, 2021 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | [3876e9ed84](https://linux-hardware.org/?probe=3876e9ed84) | Mar 21, 2021 |
| ASUSTek       | P5B-Premium                 | [ff8752a29b](https://linux-hardware.org/?probe=ff8752a29b) | Mar 21, 2021 |
| HP            | 3032h                       | [0e1292c34d](https://linux-hardware.org/?probe=0e1292c34d) | Mar 21, 2021 |
| Gigabyte      | P61-S3                      | [b146f03965](https://linux-hardware.org/?probe=b146f03965) | Mar 20, 2021 |
| Gigabyte      | MZBSWBP-00                  | [e0a36977d5](https://linux-hardware.org/?probe=e0a36977d5) | Mar 20, 2021 |
| ASUSTek       | P5B-Premium                 | [f91df49a9b](https://linux-hardware.org/?probe=f91df49a9b) | Mar 20, 2021 |
| ASUSTek       | PRIME X370-PRO              | [ccdc5f822c](https://linux-hardware.org/?probe=ccdc5f822c) | Mar 20, 2021 |
| Gigabyte      | EP31-DS3L                   | [4941011667](https://linux-hardware.org/?probe=4941011667) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [f3603f07d8](https://linux-hardware.org/?probe=f3603f07d8) | Mar 20, 2021 |
| Gigabyte      | B450M GAMING                | [4bc74bbe96](https://linux-hardware.org/?probe=4bc74bbe96) | Mar 20, 2021 |
| ASRock        | H87 Performance             | [2fea563289](https://linux-hardware.org/?probe=2fea563289) | Mar 18, 2021 |
| Inventec      | Z CLASS A02                 | [c7ae0f501c](https://linux-hardware.org/?probe=c7ae0f501c) | Mar 18, 2021 |
| Gigabyte      | H110M-S2H-CF                | [17fcafc529](https://linux-hardware.org/?probe=17fcafc529) | Mar 18, 2021 |
| ASRock        | B450M-HDV R4.0              | [f4c6bd4b6d](https://linux-hardware.org/?probe=f4c6bd4b6d) | Mar 18, 2021 |
| ASUSTek       | PRIME B450M-A               | [62042d8665](https://linux-hardware.org/?probe=62042d8665) | Mar 17, 2021 |
| Intel         | X99 V102A                   | [dae376d5ef](https://linux-hardware.org/?probe=dae376d5ef) | Mar 17, 2021 |
| ASRock        | B450 Gaming K4              | [7a547ffb71](https://linux-hardware.org/?probe=7a547ffb71) | Mar 17, 2021 |
| MSI           | 945GCM5-F V2                | [5dab57f432](https://linux-hardware.org/?probe=5dab57f432) | Mar 17, 2021 |
| HP            | 21B4 A01                    | [bab965c49d](https://linux-hardware.org/?probe=bab965c49d) | Mar 17, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [58e931b96a](https://linux-hardware.org/?probe=58e931b96a) | Mar 17, 2021 |
| Dell          | 0MN1TX A02                  | [f6a2473651](https://linux-hardware.org/?probe=f6a2473651) | Mar 16, 2021 |
| ASUSTek       | P8H77-M                     | [75989f5524](https://linux-hardware.org/?probe=75989f5524) | Mar 16, 2021 |
| ASUSTek       | P8H77-M                     | [a5d30fdac8](https://linux-hardware.org/?probe=a5d30fdac8) | Mar 16, 2021 |
| MSI           | MEG X570 UNIFY              | [4f9e368a0f](https://linux-hardware.org/?probe=4f9e368a0f) | Mar 15, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [35db155267](https://linux-hardware.org/?probe=35db155267) | Mar 15, 2021 |
| Inventec      | Z CLASS A02                 | [a29159a3a6](https://linux-hardware.org/?probe=a29159a3a6) | Mar 14, 2021 |
| Gigabyte      | B365M DS3H                  | [50735eb518](https://linux-hardware.org/?probe=50735eb518) | Mar 13, 2021 |
| MSI           | B150 PC MATE                | [42f0be9696](https://linux-hardware.org/?probe=42f0be9696) | Mar 13, 2021 |
| Dell          | 0D28YY A02                  | [cda9ac1dba](https://linux-hardware.org/?probe=cda9ac1dba) | Mar 12, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [33fda2d090](https://linux-hardware.org/?probe=33fda2d090) | Mar 12, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [5aa5df277a](https://linux-hardware.org/?probe=5aa5df277a) | Mar 12, 2021 |
| MSI           | Z370-A PRO                  | [ad1db00b2c](https://linux-hardware.org/?probe=ad1db00b2c) | Mar 12, 2021 |
| Gigabyte      | B450M DS3H V2               | [4fee2aa408](https://linux-hardware.org/?probe=4fee2aa408) | Mar 10, 2021 |
| Dell          | 0YXT71 A03                  | [fe91abca73](https://linux-hardware.org/?probe=fe91abca73) | Mar 10, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [f0d57310c5](https://linux-hardware.org/?probe=f0d57310c5) | Mar 10, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [33471c1927](https://linux-hardware.org/?probe=33471c1927) | Mar 10, 2021 |
| HP            | 1494                        | [e36f7358a7](https://linux-hardware.org/?probe=e36f7358a7) | Mar 10, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [72c59ec3d1](https://linux-hardware.org/?probe=72c59ec3d1) | Mar 10, 2021 |
| ASRock        | Z87 Killer                  | [df4c49375e](https://linux-hardware.org/?probe=df4c49375e) | Mar 10, 2021 |
| Gigabyte      | X570 AORUS PRO              | [7b470b3a42](https://linux-hardware.org/?probe=7b470b3a42) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [d2da9f1e4d](https://linux-hardware.org/?probe=d2da9f1e4d) | Mar 08, 2021 |
| Gigabyte      | GA-MA69VM-S2                | [3fa7fe2918](https://linux-hardware.org/?probe=3fa7fe2918) | Mar 08, 2021 |
| ASRock        | 960GC-GS FX                 | [2acce8dc12](https://linux-hardware.org/?probe=2acce8dc12) | Mar 08, 2021 |
| ASRock        | 960GC-GS FX                 | [d1c997cd5f](https://linux-hardware.org/?probe=d1c997cd5f) | Mar 08, 2021 |
| Gigabyte      | 970-GAMING                  | [f05a49c047](https://linux-hardware.org/?probe=f05a49c047) | Mar 08, 2021 |
| ASUSTek       | P5E-VM HDMI                 | [9979340d3f](https://linux-hardware.org/?probe=9979340d3f) | Mar 07, 2021 |
| MSI           | A68HM-E33 V2                | [509aee7a35](https://linux-hardware.org/?probe=509aee7a35) | Mar 07, 2021 |
| MSI           | A68HM-E33 V2                | [56c8a3336b](https://linux-hardware.org/?probe=56c8a3336b) | Mar 07, 2021 |
| HP            | 3032h                       | [b5d2eac6a8](https://linux-hardware.org/?probe=b5d2eac6a8) | Mar 06, 2021 |
| Gigabyte      | P31-DS3L                    | [45f0c2ac56](https://linux-hardware.org/?probe=45f0c2ac56) | Mar 05, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [415981e811](https://linux-hardware.org/?probe=415981e811) | Mar 05, 2021 |
| Gigabyte      | B365M DS3H                  | [d63ded0915](https://linux-hardware.org/?probe=d63ded0915) | Mar 05, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f2f5b34cba](https://linux-hardware.org/?probe=f2f5b34cba) | Mar 04, 2021 |
| Intel         | DG31PR AAD97573-301         | [bde1812ae9](https://linux-hardware.org/?probe=bde1812ae9) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [ad390daa6b](https://linux-hardware.org/?probe=ad390daa6b) | Mar 04, 2021 |
| Gigabyte      | H55M-USB3                   | [041e0131e2](https://linux-hardware.org/?probe=041e0131e2) | Mar 04, 2021 |
| MSI           | A68HM-E33 V2                | [dc44683476](https://linux-hardware.org/?probe=dc44683476) | Mar 04, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [fa49dca039](https://linux-hardware.org/?probe=fa49dca039) | Mar 03, 2021 |
| Lenovo        | ThinkCentre M58 7360AEG     | [2567067c7d](https://linux-hardware.org/?probe=2567067c7d) | Mar 03, 2021 |
| MSI           | B85-G43 GAMING              | [ff7c42f22d](https://linux-hardware.org/?probe=ff7c42f22d) | Mar 03, 2021 |
| Dell          | 03NVJ6 A01                  | [2265f87681](https://linux-hardware.org/?probe=2265f87681) | Mar 02, 2021 |
| Gigabyte      | Z77X-UD3H                   | [08b38a0202](https://linux-hardware.org/?probe=08b38a0202) | Mar 02, 2021 |
| Gigabyte      | GA-M56S-S3                  | [d6a37febf5](https://linux-hardware.org/?probe=d6a37febf5) | Mar 02, 2021 |
| HP            | 0A68h                       | [185af633ab](https://linux-hardware.org/?probe=185af633ab) | Mar 01, 2021 |
| Lenovo        | ThinkStation C20 4263BA7    | [540e259415](https://linux-hardware.org/?probe=540e259415) | Mar 01, 2021 |
| ASUSTek       | P8B75-M LX                  | [9fb20c11d3](https://linux-hardware.org/?probe=9fb20c11d3) | Mar 01, 2021 |
| MSI           | B450M PRO-VDH MAX           | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| Dell          | 0MGK50 A02                  | [2a9c7c67dc](https://linux-hardware.org/?probe=2a9c7c67dc) | Feb 28, 2021 |
| Gigabyte      | H81M-HD3                    | [1eca782ae1](https://linux-hardware.org/?probe=1eca782ae1) | Feb 28, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [bd17bcec26](https://linux-hardware.org/?probe=bd17bcec26) | Feb 28, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [3e501bf682](https://linux-hardware.org/?probe=3e501bf682) | Feb 28, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [79a437a7fa](https://linux-hardware.org/?probe=79a437a7fa) | Feb 28, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [4d037602af](https://linux-hardware.org/?probe=4d037602af) | Feb 28, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [6b1084fddf](https://linux-hardware.org/?probe=6b1084fddf) | Feb 28, 2021 |
| Dell          | DXC061                      | [a77c182e24](https://linux-hardware.org/?probe=a77c182e24) | Feb 27, 2021 |
| ASRock        | A320M-HDV R3.0              | [8c447608d7](https://linux-hardware.org/?probe=8c447608d7) | Feb 27, 2021 |
| ASUSTek       | Maximus Formula             | [0e0500065a](https://linux-hardware.org/?probe=0e0500065a) | Feb 27, 2021 |
| MSI           | MS-163B Ver                 | [0eb235a494](https://linux-hardware.org/?probe=0eb235a494) | Feb 26, 2021 |
| MSI           | MS-163B Ver                 | [500bece661](https://linux-hardware.org/?probe=500bece661) | Feb 26, 2021 |
| Dell          | 0MN1TX A02                  | [3ad6cb2899](https://linux-hardware.org/?probe=3ad6cb2899) | Feb 25, 2021 |
| ASUSTek       | P5B                         | [8ef0467d76](https://linux-hardware.org/?probe=8ef0467d76) | Feb 25, 2021 |
| HP            | 1494                        | [f42ec29805](https://linux-hardware.org/?probe=f42ec29805) | Feb 25, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [39950827bc](https://linux-hardware.org/?probe=39950827bc) | Feb 25, 2021 |
| Dell          | 0WF810                      | [729c977194](https://linux-hardware.org/?probe=729c977194) | Feb 25, 2021 |
| Gigabyte      | GA-78LMT-S2PT               | [84982803f8](https://linux-hardware.org/?probe=84982803f8) | Feb 25, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6b721d56ba](https://linux-hardware.org/?probe=6b721d56ba) | Feb 25, 2021 |
| MSI           | 970A-G43                    | [5c188af375](https://linux-hardware.org/?probe=5c188af375) | Feb 25, 2021 |
| ASUSTek       | M2N-CM DVI                  | [9c85aa9838](https://linux-hardware.org/?probe=9c85aa9838) | Feb 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | [18a30198e5](https://linux-hardware.org/?probe=18a30198e5) | Feb 23, 2021 |
| Dell          | 03NVJ6 A01                  | [393a29bf7a](https://linux-hardware.org/?probe=393a29bf7a) | Feb 23, 2021 |
| Gigabyte      | Z77X-UD3H                   | [2b8986d140](https://linux-hardware.org/?probe=2b8986d140) | Feb 23, 2021 |
| Gigabyte      | Z77X-UD3H                   | [f0c59c70a1](https://linux-hardware.org/?probe=f0c59c70a1) | Feb 23, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [3d0fb6587f](https://linux-hardware.org/?probe=3d0fb6587f) | Feb 22, 2021 |
| ASUSTek       | M3A78-CM                    | [ae309000e1](https://linux-hardware.org/?probe=ae309000e1) | Feb 22, 2021 |
| MSI           | Z87I                        | [3bd10e1f76](https://linux-hardware.org/?probe=3bd10e1f76) | Feb 21, 2021 |
| ASRock        | X370 Gaming X               | [97b686fad6](https://linux-hardware.org/?probe=97b686fad6) | Feb 21, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1314989a9a](https://linux-hardware.org/?probe=1314989a9a) | Feb 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f9639ea950](https://linux-hardware.org/?probe=f9639ea950) | Feb 20, 2021 |
| Gigabyte      | M61VME-S2                   | [93e9a961df](https://linux-hardware.org/?probe=93e9a961df) | Feb 20, 2021 |
| Gigabyte      | M61VME-S2                   | [ab1bcee66d](https://linux-hardware.org/?probe=ab1bcee66d) | Feb 20, 2021 |
| Gigabyte      | M61VME-S2                   | [9f696723cc](https://linux-hardware.org/?probe=9f696723cc) | Feb 20, 2021 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [c81d067d76](https://linux-hardware.org/?probe=c81d067d76) | Feb 19, 2021 |
| MSI           | B150M PRO-VD                | [6d13f9c5f7](https://linux-hardware.org/?probe=6d13f9c5f7) | Feb 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [60fd38b68c](https://linux-hardware.org/?probe=60fd38b68c) | Feb 19, 2021 |
| ASRock        | H55M-LE                     | [34c66b2293](https://linux-hardware.org/?probe=34c66b2293) | Feb 19, 2021 |
| Gigabyte      | PH67-DS3-B3                 | [bc80a6485e](https://linux-hardware.org/?probe=bc80a6485e) | Feb 18, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ab88da63cd](https://linux-hardware.org/?probe=ab88da63cd) | Feb 18, 2021 |
| HP            | 1497                        | [94691dc0d4](https://linux-hardware.org/?probe=94691dc0d4) | Feb 18, 2021 |
| MSI           | B450M-A PRO MAX             | [25bd50f7cc](https://linux-hardware.org/?probe=25bd50f7cc) | Feb 18, 2021 |
| ASUSTek       | PRIME B450M-A               | [b64095c22b](https://linux-hardware.org/?probe=b64095c22b) | Feb 17, 2021 |
| Gigabyte      | H81M-S1                     | [9f76940797](https://linux-hardware.org/?probe=9f76940797) | Feb 17, 2021 |
| ASUSTek       | P8H77-M                     | [1f0567bc6e](https://linux-hardware.org/?probe=1f0567bc6e) | Feb 17, 2021 |
| MSI           | H310M PRO-VDH               | [e3633e95cd](https://linux-hardware.org/?probe=e3633e95cd) | Feb 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | [345a062971](https://linux-hardware.org/?probe=345a062971) | Feb 17, 2021 |
| ASUSTek       | P8H61-M LX                  | [0f5221a11b](https://linux-hardware.org/?probe=0f5221a11b) | Feb 16, 2021 |
| HP            | 21B4 A01                    | [0dab6984ed](https://linux-hardware.org/?probe=0dab6984ed) | Feb 16, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5cef878cd5](https://linux-hardware.org/?probe=5cef878cd5) | Feb 16, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [5015d9c262](https://linux-hardware.org/?probe=5015d9c262) | Feb 16, 2021 |
| HP            | 3397                        | [ba21eb1e9b](https://linux-hardware.org/?probe=ba21eb1e9b) | Feb 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [2d77c772d6](https://linux-hardware.org/?probe=2d77c772d6) | Feb 16, 2021 |
| Gigabyte      | H81M-S1                     | [a48e3f8e35](https://linux-hardware.org/?probe=a48e3f8e35) | Feb 15, 2021 |
| Gigabyte      | G41M-ES2L                   | [328ec77dd8](https://linux-hardware.org/?probe=328ec77dd8) | Feb 15, 2021 |
| HEDYCOMPUT... | OEM V1.0                    | [0b7c832d3c](https://linux-hardware.org/?probe=0b7c832d3c) | Feb 15, 2021 |
| ASRock        | H61M-DG3/USB3               | [6482ac68ac](https://linux-hardware.org/?probe=6482ac68ac) | Feb 15, 2021 |
| ASRock        | ConRoe1333-D667             | [f919a6006e](https://linux-hardware.org/?probe=f919a6006e) | Feb 15, 2021 |
| Dell          | 07T4MC A06                  | [ae053aa0ed](https://linux-hardware.org/?probe=ae053aa0ed) | Feb 15, 2021 |
| ASRock        | H55M-LE                     | [0ff078185a](https://linux-hardware.org/?probe=0ff078185a) | Feb 15, 2021 |
| Gigabyte      | P31-DS3L                    | [a26423d066](https://linux-hardware.org/?probe=a26423d066) | Feb 15, 2021 |
| HP            | 8266                        | [e903e5b250](https://linux-hardware.org/?probe=e903e5b250) | Feb 14, 2021 |
| Dell          | 0WMJ54 A01                  | [3be9cf8ea6](https://linux-hardware.org/?probe=3be9cf8ea6) | Feb 14, 2021 |
| ASRock        | AB350M Pro4                 | [e2dc3ef1ca](https://linux-hardware.org/?probe=e2dc3ef1ca) | Feb 14, 2021 |
| MSI           | 785G-E53                    | [186805415c](https://linux-hardware.org/?probe=186805415c) | Feb 14, 2021 |
| ASRock        | FM2A88X Extreme6+           | [39899b06fa](https://linux-hardware.org/?probe=39899b06fa) | Feb 14, 2021 |
| ASUSTek       | M5A78L-M LX3                | [cbf28f35f1](https://linux-hardware.org/?probe=cbf28f35f1) | Feb 14, 2021 |
| ASRock        | FM2A88X Extreme6+           | [a9eee5568c](https://linux-hardware.org/?probe=a9eee5568c) | Feb 14, 2021 |
| ASRock        | A88M-G                      | [f8751e82d0](https://linux-hardware.org/?probe=f8751e82d0) | Feb 14, 2021 |
| HP            | 8266                        | [03c55828d2](https://linux-hardware.org/?probe=03c55828d2) | Feb 13, 2021 |
| HP            | 8266                        | [71772ab5cc](https://linux-hardware.org/?probe=71772ab5cc) | Feb 13, 2021 |
| Dell          | 0MGK50 A01                  | [9e95b96d22](https://linux-hardware.org/?probe=9e95b96d22) | Feb 13, 2021 |
| ASUSTek       | P7P55D-E                    | [c74c010c1b](https://linux-hardware.org/?probe=c74c010c1b) | Feb 13, 2021 |
| ASUSTek       | P7P55D-E                    | [366bf9e761](https://linux-hardware.org/?probe=366bf9e761) | Feb 13, 2021 |
| Acer          | Aspire XC-886 V:2.0         | [6ef24a6ac7](https://linux-hardware.org/?probe=6ef24a6ac7) | Feb 13, 2021 |
| HP            | 843C                        | [8286fe4f06](https://linux-hardware.org/?probe=8286fe4f06) | Feb 12, 2021 |
| ASUSTek       | P5B                         | [d2dd1a0470](https://linux-hardware.org/?probe=d2dd1a0470) | Feb 09, 2021 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [4d1748c7f4](https://linux-hardware.org/?probe=4d1748c7f4) | Feb 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fc619720c8](https://linux-hardware.org/?probe=fc619720c8) | Feb 09, 2021 |
| ASUSTek       | P7P55D-E                    | [1980557f48](https://linux-hardware.org/?probe=1980557f48) | Feb 08, 2021 |
| Gigabyte      | 990FXA-UD3                  | [eb718361d4](https://linux-hardware.org/?probe=eb718361d4) | Feb 08, 2021 |
| MSI           | B450M PRO-VDH MAX           | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [cb81228b5f](https://linux-hardware.org/?probe=cb81228b5f) | Feb 07, 2021 |
| MSI           | B450M PRO-VDH MAX           | [03c94ea254](https://linux-hardware.org/?probe=03c94ea254) | Feb 06, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [22640643b3](https://linux-hardware.org/?probe=22640643b3) | Feb 05, 2021 |
| ASUSTek       | P5VD2-MX                    | [f0f594baaf](https://linux-hardware.org/?probe=f0f594baaf) | Feb 04, 2021 |
| Acer          | Aspire XC-886 V:2.0         | [9b4519158f](https://linux-hardware.org/?probe=9b4519158f) | Feb 04, 2021 |
| MSI           | B460M PRO                   | [9fcc385df9](https://linux-hardware.org/?probe=9fcc385df9) | Feb 04, 2021 |
| MSI           | B250M PRO-VH                | [6c54b0786f](https://linux-hardware.org/?probe=6c54b0786f) | Feb 03, 2021 |
| ASRock        | AM1H-ITX                    | [a1c5772342](https://linux-hardware.org/?probe=a1c5772342) | Feb 03, 2021 |
| ASRock        | P67 Pro3                    | [5d7941849f](https://linux-hardware.org/?probe=5d7941849f) | Feb 03, 2021 |
| Gigabyte      | Z77-DS3H                    | [a9d31a9e64](https://linux-hardware.org/?probe=a9d31a9e64) | Feb 02, 2021 |
| MSI           | B550-A PRO                  | [289898c068](https://linux-hardware.org/?probe=289898c068) | Jan 31, 2021 |
| Gigabyte      | GA-G41M-ES2L                | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| ASUSTek       | P5B-VM                      | [3f0ab2a823](https://linux-hardware.org/?probe=3f0ab2a823) | Jan 30, 2021 |
| ASRock        | X370 Gaming X               | [8f0d93f4e1](https://linux-hardware.org/?probe=8f0d93f4e1) | Jan 25, 2021 |
| Dell          | 03NVJ6 A01                  | [6e2b81d521](https://linux-hardware.org/?probe=6e2b81d521) | Jan 23, 2021 |
| MSI           | Z97 GAMING 5                | [4504e288f2](https://linux-hardware.org/?probe=4504e288f2) | Jan 22, 2021 |
| Intel         | DG41RQ AAE54511-203         | [fc928f4e01](https://linux-hardware.org/?probe=fc928f4e01) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| ASUSTek       | PRIME Q270M-C               | [c485dcca0d](https://linux-hardware.org/?probe=c485dcca0d) | Jan 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3f5115f156](https://linux-hardware.org/?probe=3f5115f156) | Jan 19, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [50a23ca7a6](https://linux-hardware.org/?probe=50a23ca7a6) | Jan 18, 2021 |
| MSI           | Z97 GAMING 5                | [dafd82bca6](https://linux-hardware.org/?probe=dafd82bca6) | Jan 18, 2021 |
| Gigabyte      | GA-MA770T-UD3P              | [b48c163a55](https://linux-hardware.org/?probe=b48c163a55) | Jan 17, 2021 |
| Gigabyte      | H81M-S2H                    | [bdcbf02e56](https://linux-hardware.org/?probe=bdcbf02e56) | Jan 17, 2021 |
| MSI           | B450M PRO-VDH MAX           | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Dell          | 0TT708 A01                  | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [7b44659e6f](https://linux-hardware.org/?probe=7b44659e6f) | Jan 15, 2021 |
| Gigabyte      | GA-MA770T-UD3P              | [893a38628c](https://linux-hardware.org/?probe=893a38628c) | Jan 15, 2021 |
| Dell          | OptiPlex 580                | [ee7a969dba](https://linux-hardware.org/?probe=ee7a969dba) | Jan 14, 2021 |
| Gigabyte      | X570 AORUS PRO              | [07dfac2f92](https://linux-hardware.org/?probe=07dfac2f92) | Jan 14, 2021 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [40e5b67358](https://linux-hardware.org/?probe=40e5b67358) | Jan 14, 2021 |
| Dell          | 0TT708 A01                  | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Gigabyte      | Z170X-Gaming 3              | [e4ab17605e](https://linux-hardware.org/?probe=e4ab17605e) | Jan 13, 2021 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [94546682e2](https://linux-hardware.org/?probe=94546682e2) | Jan 13, 2021 |
| Gigabyte      | EX58-UD4P                   | [72ae7fc6e2](https://linux-hardware.org/?probe=72ae7fc6e2) | Jan 13, 2021 |
| Gigabyte      | GA-MA770-UD3                | [6b9e20079b](https://linux-hardware.org/?probe=6b9e20079b) | Jan 13, 2021 |
| Gigabyte      | GA-MA770-UD3                | [cbbb4ea83c](https://linux-hardware.org/?probe=cbbb4ea83c) | Jan 13, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [106b086cb1](https://linux-hardware.org/?probe=106b086cb1) | Jan 13, 2021 |
| HP            | 3047h                       | [971be1b408](https://linux-hardware.org/?probe=971be1b408) | Jan 12, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [4152d7a631](https://linux-hardware.org/?probe=4152d7a631) | Jan 11, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [db5b30e98c](https://linux-hardware.org/?probe=db5b30e98c) | Jan 11, 2021 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [4e128ed0ae](https://linux-hardware.org/?probe=4e128ed0ae) | Jan 11, 2021 |
| Gigabyte      | H270-HD3-CF                 | [9b5ea6cf78](https://linux-hardware.org/?probe=9b5ea6cf78) | Jan 10, 2021 |
| HP            | 3047h                       | [8426396aa6](https://linux-hardware.org/?probe=8426396aa6) | Jan 10, 2021 |
| ASUSTek       | Rampage V EXTREME           | [c60231f337](https://linux-hardware.org/?probe=c60231f337) | Jan 10, 2021 |
| HP            | 3047h                       | [220e8e47e6](https://linux-hardware.org/?probe=220e8e47e6) | Jan 09, 2021 |
| Gigabyte      | 945GZM-S2                   | [bdd445b4ec](https://linux-hardware.org/?probe=bdd445b4ec) | Jan 08, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [01d6bc5782](https://linux-hardware.org/?probe=01d6bc5782) | Jan 08, 2021 |
| MSI           | P35 Platinum                | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| ASUSTek       | P5Q-PRO                     | [c270aa43e0](https://linux-hardware.org/?probe=c270aa43e0) | Jan 07, 2021 |
| ASRock        | P67 Pro3                    | [c2a69803bb](https://linux-hardware.org/?probe=c2a69803bb) | Jan 07, 2021 |
| HP            | 18E7                        | [e4889724c6](https://linux-hardware.org/?probe=e4889724c6) | Jan 07, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [1ea76621ef](https://linux-hardware.org/?probe=1ea76621ef) | Jan 07, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [0ce209900e](https://linux-hardware.org/?probe=0ce209900e) | Jan 07, 2021 |
| Gigabyte      | 970A-UD3P                   | [aa0ef0d07e](https://linux-hardware.org/?probe=aa0ef0d07e) | Jan 06, 2021 |
| ASUSTek       | B85M-G                      | [2bc064730b](https://linux-hardware.org/?probe=2bc064730b) | Jan 06, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6f95de2b32](https://linux-hardware.org/?probe=6f95de2b32) | Jan 05, 2021 |
| ASUSTek       | M5A97                       | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [746286d315](https://linux-hardware.org/?probe=746286d315) | Jan 03, 2021 |
| Lenovo        | SHARKBAY NOK                | [4cf58c8a8c](https://linux-hardware.org/?probe=4cf58c8a8c) | Jan 02, 2021 |
| ASUSTek       | H81M-P                      | [8357877ce0](https://linux-hardware.org/?probe=8357877ce0) | Jan 02, 2021 |
| ASUSTek       | H81M-P                      | [e532649d15](https://linux-hardware.org/?probe=e532649d15) | Dec 30, 2020 |
| MSI           | B450M PRO-VDH MAX           | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Gigabyte      | P61-S3                      | [cdc3efaa7d](https://linux-hardware.org/?probe=cdc3efaa7d) | Dec 29, 2020 |
| ASUSTek       | M5A97                       | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| HP            | 843C                        | [42dc66cc7d](https://linux-hardware.org/?probe=42dc66cc7d) | Dec 29, 2020 |
| Gigabyte      | 965P-DS3                    | [f15691ab91](https://linux-hardware.org/?probe=f15691ab91) | Dec 28, 2020 |
| ASUSTek       | PRIME A320M-K               | [281ddba4d1](https://linux-hardware.org/?probe=281ddba4d1) | Dec 28, 2020 |
| ASUSTek       | PRIME A320M-A               | [320746cf4f](https://linux-hardware.org/?probe=320746cf4f) | Dec 28, 2020 |
| ASRock        | AM1H-ITX                    | [2bd69bdc3e](https://linux-hardware.org/?probe=2bd69bdc3e) | Dec 27, 2020 |
| MSI           | B450M PRO-VDH MAX           | [af6f0d4f11](https://linux-hardware.org/?probe=af6f0d4f11) | Dec 26, 2020 |
| ASUSTek       | P8P67 LE                    | [627ed8e703](https://linux-hardware.org/?probe=627ed8e703) | Dec 25, 2020 |
| MSI           | B450M PRO-VDH MAX           | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| ASRock        | A75M-HVS                    | [10d8a7d471](https://linux-hardware.org/?probe=10d8a7d471) | Dec 24, 2020 |
| Lenovo        | SKYBAY NOK                  | [1f2d140a80](https://linux-hardware.org/?probe=1f2d140a80) | Dec 24, 2020 |
| MSI           | H81M-P33                    | [73342ba685](https://linux-hardware.org/?probe=73342ba685) | Dec 23, 2020 |
| MSI           | H81M-P33                    | [ce959f9cb1](https://linux-hardware.org/?probe=ce959f9cb1) | Dec 23, 2020 |
| Dell          | 0D441T A01                  | [5244982406](https://linux-hardware.org/?probe=5244982406) | Dec 23, 2020 |
| MSI           | B550-A PRO                  | [958ddd697e](https://linux-hardware.org/?probe=958ddd697e) | Dec 23, 2020 |
| Gigabyte      | X570 GAMING X               | [01355fa7e2](https://linux-hardware.org/?probe=01355fa7e2) | Dec 20, 2020 |
| Lenovo        | ThinkCentre Edge91 1855A... | [d35a3f1c77](https://linux-hardware.org/?probe=d35a3f1c77) | Dec 19, 2020 |
| Gigabyte      | B550 AORUS ELITE V2         | [1540ecf29c](https://linux-hardware.org/?probe=1540ecf29c) | Dec 19, 2020 |
| ASRock        | Q1900M                      | [bf7250aaf5](https://linux-hardware.org/?probe=bf7250aaf5) | Dec 18, 2020 |
| Gigabyte      | GA-770T-D3L                 | [f819b316d4](https://linux-hardware.org/?probe=f819b316d4) | Dec 17, 2020 |
| ASRock        | Q1900M                      | [6781c8fc16](https://linux-hardware.org/?probe=6781c8fc16) | Dec 17, 2020 |
| Gigabyte      | H81M-S2PV                   | [791fb06fd1](https://linux-hardware.org/?probe=791fb06fd1) | Dec 16, 2020 |
| Fujitsu Si... | D2348-A3 S26361-D2348-A3    | [d66bc8959a](https://linux-hardware.org/?probe=d66bc8959a) | Dec 16, 2020 |
| ASRock        | B75M                        | [970b005473](https://linux-hardware.org/?probe=970b005473) | Dec 15, 2020 |
| Gigabyte      | A320M-S2H-CF                | [9c339444b9](https://linux-hardware.org/?probe=9c339444b9) | Dec 15, 2020 |
| Lenovo        | MAHOBAY NOK                 | [ded83d24e1](https://linux-hardware.org/?probe=ded83d24e1) | Dec 14, 2020 |
| Dell          | 0NY776                      | [96c413429a](https://linux-hardware.org/?probe=96c413429a) | Dec 14, 2020 |
| Dell          | 0NY776                      | [a3b83d4eeb](https://linux-hardware.org/?probe=a3b83d4eeb) | Dec 14, 2020 |
| Gigabyte      | A320M-S2H-CF                | [19d625a9b1](https://linux-hardware.org/?probe=19d625a9b1) | Dec 14, 2020 |
| MSI           | 760GM-P34                   | [28704208e4](https://linux-hardware.org/?probe=28704208e4) | Dec 13, 2020 |
| MSI           | 760GM-P34                   | [17e008e904](https://linux-hardware.org/?probe=17e008e904) | Dec 13, 2020 |
| ASRock        | Q1900B-ITX                  | [d64557ca52](https://linux-hardware.org/?probe=d64557ca52) | Dec 12, 2020 |
| ASUSTek       | M4A79XTD EVO                | [50ca008a49](https://linux-hardware.org/?probe=50ca008a49) | Dec 12, 2020 |
| AMI           | Cherry Trail CR             | [6ed2c82a03](https://linux-hardware.org/?probe=6ed2c82a03) | Dec 11, 2020 |
| Gigabyte      | B450 GAMING X               | [84fcdb4340](https://linux-hardware.org/?probe=84fcdb4340) | Dec 10, 2020 |
| Gigabyte      | B450 GAMING X               | [5b6ec837e3](https://linux-hardware.org/?probe=5b6ec837e3) | Dec 10, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [66e73ff3a5](https://linux-hardware.org/?probe=66e73ff3a5) | Dec 10, 2020 |
| Gigabyte      | H55M-S2H                    | [9c5f8b71c6](https://linux-hardware.org/?probe=9c5f8b71c6) | Dec 09, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [dc49d62741](https://linux-hardware.org/?probe=dc49d62741) | Dec 09, 2020 |
| MSI           | B450M PRO-VDH MAX           | [67d8647df7](https://linux-hardware.org/?probe=67d8647df7) | Dec 08, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [6e816b21f1](https://linux-hardware.org/?probe=6e816b21f1) | Dec 08, 2020 |
| ASRock        | Z490 Steel Legend           | [62201590bf](https://linux-hardware.org/?probe=62201590bf) | Dec 08, 2020 |
| Gigabyte      | B85M-D3H                    | [8fd1e57a93](https://linux-hardware.org/?probe=8fd1e57a93) | Dec 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [23588a99c8](https://linux-hardware.org/?probe=23588a99c8) | Dec 06, 2020 |
| Dell          | 042P49 A01                  | [2b287ec16a](https://linux-hardware.org/?probe=2b287ec16a) | Dec 06, 2020 |
| HP            | 3047h                       | [aece6415ff](https://linux-hardware.org/?probe=aece6415ff) | Dec 06, 2020 |
| Gigabyte      | 990FXA-UD3                  | [239b17299b](https://linux-hardware.org/?probe=239b17299b) | Dec 04, 2020 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | [70ab40ca28](https://linux-hardware.org/?probe=70ab40ca28) | Dec 04, 2020 |
| MSI           | X399 SLI PLUS               | [4c70339407](https://linux-hardware.org/?probe=4c70339407) | Dec 03, 2020 |
| Gigabyte      | B75M-D2V                    | [827e9f1654](https://linux-hardware.org/?probe=827e9f1654) | Dec 03, 2020 |
| Gigabyte      | B75M-D2V                    | [5a9e7c8135](https://linux-hardware.org/?probe=5a9e7c8135) | Dec 03, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [3ec7b8c5aa](https://linux-hardware.org/?probe=3ec7b8c5aa) | Dec 03, 2020 |
| Acer          | RS780DV                     | [26cb303009](https://linux-hardware.org/?probe=26cb303009) | Dec 02, 2020 |
| Acer          | RS780DV                     | [5bf74a9c54](https://linux-hardware.org/?probe=5bf74a9c54) | Dec 02, 2020 |
| ASUSTek       | P5B-V                       | [6df82236dd](https://linux-hardware.org/?probe=6df82236dd) | Dec 02, 2020 |
| ASUSTek       | P4P800-VM                   | [bbddf74019](https://linux-hardware.org/?probe=bbddf74019) | Dec 02, 2020 |
| ASUSTek       | P4P800-VM                   | [a41a6916b2](https://linux-hardware.org/?probe=a41a6916b2) | Dec 02, 2020 |
| Gigabyte      | B360M DS3H                  | [a89e36e427](https://linux-hardware.org/?probe=a89e36e427) | Dec 01, 2020 |
| MSI           | H81M-E34                    | [37c90096f4](https://linux-hardware.org/?probe=37c90096f4) | Nov 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [aaae63991f](https://linux-hardware.org/?probe=aaae63991f) | Nov 29, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [9d3034263e](https://linux-hardware.org/?probe=9d3034263e) | Nov 28, 2020 |
| Unknown       | Intel X79                   | [292eec0743](https://linux-hardware.org/?probe=292eec0743) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [9f01fc9e95](https://linux-hardware.org/?probe=9f01fc9e95) | Nov 27, 2020 |
| Gigabyte      | B250M-D3H-CF                | [3e05e13e7f](https://linux-hardware.org/?probe=3e05e13e7f) | Nov 27, 2020 |
| ASUSTek       | P6T SE                      | [c62207d36c](https://linux-hardware.org/?probe=c62207d36c) | Nov 27, 2020 |
| ASUSTek       | M5A97 R2.0                  | [b6c7ac6dff](https://linux-hardware.org/?probe=b6c7ac6dff) | Nov 24, 2020 |
| Gigabyte      | H270-HD3-CF                 | [1ddf3dcb25](https://linux-hardware.org/?probe=1ddf3dcb25) | Nov 24, 2020 |
| ASRock        | B450 Steel Legend           | [5603e263b8](https://linux-hardware.org/?probe=5603e263b8) | Nov 24, 2020 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | [b9d2416a7e](https://linux-hardware.org/?probe=b9d2416a7e) | Nov 24, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [bcc51eabd1](https://linux-hardware.org/?probe=bcc51eabd1) | Nov 23, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [91e9f98b3c](https://linux-hardware.org/?probe=91e9f98b3c) | Nov 23, 2020 |
| Gigabyte      | Z170X-Gaming 5              | [0c626e3392](https://linux-hardware.org/?probe=0c626e3392) | Nov 22, 2020 |
| MSI           | B360M PRO-VDH               | [7f138ba71c](https://linux-hardware.org/?probe=7f138ba71c) | Nov 22, 2020 |
| ASUSTek       | M5A88-M EVO                 | [fedc059c3e](https://linux-hardware.org/?probe=fedc059c3e) | Nov 22, 2020 |
| Gigabyte      | EP45C-DS3R                  | [78a9c315ef](https://linux-hardware.org/?probe=78a9c315ef) | Nov 22, 2020 |
| ASUSTek       | M5A97 R2.0                  | [0d17290871](https://linux-hardware.org/?probe=0d17290871) | Nov 22, 2020 |
| MSI           | MS-7312                     | [3b58a0d7bd](https://linux-hardware.org/?probe=3b58a0d7bd) | Nov 21, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9bdb49d52d](https://linux-hardware.org/?probe=9bdb49d52d) | Nov 21, 2020 |
| ASRock        | Q1900B-ITX                  | [5dadcfe11e](https://linux-hardware.org/?probe=5dadcfe11e) | Nov 20, 2020 |
| Gigabyte      | H81M-S2H                    | [0c4dc064f7](https://linux-hardware.org/?probe=0c4dc064f7) | Nov 19, 2020 |
| Gigabyte      | EX38-DS5                    | [96e4034e9f](https://linux-hardware.org/?probe=96e4034e9f) | Nov 18, 2020 |
| Gigabyte      | Z77X-D3H                    | [fa405571bd](https://linux-hardware.org/?probe=fa405571bd) | Nov 18, 2020 |
| MSI           | MS-7312                     | [a67947a5d9](https://linux-hardware.org/?probe=a67947a5d9) | Nov 18, 2020 |
| MSI           | B360M PRO-VDH               | [2a8111d3e1](https://linux-hardware.org/?probe=2a8111d3e1) | Nov 18, 2020 |
| ASUSTek       | H81M-P                      | [32ccf4d815](https://linux-hardware.org/?probe=32ccf4d815) | Nov 18, 2020 |
| MSI           | MS-7312                     | [c204652324](https://linux-hardware.org/?probe=c204652324) | Nov 17, 2020 |
| ASUSTek       | P9X79 DELUXE                | [8f43095eb5](https://linux-hardware.org/?probe=8f43095eb5) | Nov 17, 2020 |
| ASUSTek       | P5E                         | [71702174cf](https://linux-hardware.org/?probe=71702174cf) | Nov 17, 2020 |
| ASUSTek       | P5E                         | [cd94dff4ea](https://linux-hardware.org/?probe=cd94dff4ea) | Nov 16, 2020 |
| ASUSTek       | PRIME X370-PRO              | [70fc4e5649](https://linux-hardware.org/?probe=70fc4e5649) | Nov 16, 2020 |
| HP            | 1587h                       | [4b1f2221ee](https://linux-hardware.org/?probe=4b1f2221ee) | Nov 16, 2020 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | [13e1369910](https://linux-hardware.org/?probe=13e1369910) | Nov 15, 2020 |
| ASRock        | Q1900B-ITX                  | [dbbdca15af](https://linux-hardware.org/?probe=dbbdca15af) | Nov 15, 2020 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [879e66e1a0](https://linux-hardware.org/?probe=879e66e1a0) | Nov 15, 2020 |
| Gigabyte      | 965P-S3                     | [a282bda32f](https://linux-hardware.org/?probe=a282bda32f) | Nov 15, 2020 |
| ASUSTek       | P8H77-V LE                  | [e0115794e1](https://linux-hardware.org/?probe=e0115794e1) | Nov 15, 2020 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | [b1f9452aba](https://linux-hardware.org/?probe=b1f9452aba) | Nov 15, 2020 |
| MSI           | H310M PRO-VH                | [5e5c8b98fc](https://linux-hardware.org/?probe=5e5c8b98fc) | Nov 14, 2020 |
| Gigabyte      | Z97M-D3H                    | [8b5f342bb5](https://linux-hardware.org/?probe=8b5f342bb5) | Nov 14, 2020 |
| Intel         | DG31PR AAD97573-301         | [154991bcce](https://linux-hardware.org/?probe=154991bcce) | Nov 11, 2020 |
| Inventec      | Z CLASS A02                 | [eb06b75703](https://linux-hardware.org/?probe=eb06b75703) | Nov 11, 2020 |
| Acer          | Veriton M430G               | [52a2057281](https://linux-hardware.org/?probe=52a2057281) | Nov 10, 2020 |
| MSI           | MAG Z490 TOMAHAWK           | [62b36ce80c](https://linux-hardware.org/?probe=62b36ce80c) | Nov 10, 2020 |
| Gigabyte      | H67N-USB3-B3                | [69aa804c1d](https://linux-hardware.org/?probe=69aa804c1d) | Nov 09, 2020 |
| MSI           | MS-7253                     | [3bb0c14e23](https://linux-hardware.org/?probe=3bb0c14e23) | Nov 08, 2020 |
| Gigabyte      | H67N-USB3-B3                | [f4dc6dd150](https://linux-hardware.org/?probe=f4dc6dd150) | Nov 07, 2020 |
| MSI           | Z170A PC MATE               | [8a2ac91a66](https://linux-hardware.org/?probe=8a2ac91a66) | Nov 07, 2020 |
| ASUSTek       | P5Q-PRO                     | [f15dc4da9f](https://linux-hardware.org/?probe=f15dc4da9f) | Nov 06, 2020 |
| MSI           | Z170A PC MATE               | [dd70e404e0](https://linux-hardware.org/?probe=dd70e404e0) | Nov 06, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [9217160c02](https://linux-hardware.org/?probe=9217160c02) | Nov 06, 2020 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [98362ae4f3](https://linux-hardware.org/?probe=98362ae4f3) | Nov 06, 2020 |
| MSI           | B450M PRO-VDH MAX           | [8b60ff74dc](https://linux-hardware.org/?probe=8b60ff74dc) | Nov 05, 2020 |
| MSI           | 760GM-P33                   | [e1fafe06d7](https://linux-hardware.org/?probe=e1fafe06d7) | Nov 04, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [012b402eac](https://linux-hardware.org/?probe=012b402eac) | Nov 04, 2020 |
| MSI           | B75MA-P45                   | [46dff28904](https://linux-hardware.org/?probe=46dff28904) | Nov 03, 2020 |
| ASUSTek       | P5B-Premium                 | [f10b2f44f1](https://linux-hardware.org/?probe=f10b2f44f1) | Nov 03, 2020 |
| Gigabyte      | H61M-D2H                    | [4bd428dfd2](https://linux-hardware.org/?probe=4bd428dfd2) | Nov 03, 2020 |
| ASUSTek       | P5B-Premium                 | [fa647c4278](https://linux-hardware.org/?probe=fa647c4278) | Nov 02, 2020 |
| Gigabyte      | 8I945GMF                    | [384f5ef489](https://linux-hardware.org/?probe=384f5ef489) | Nov 01, 2020 |
| HP            | 3047h                       | [3227f997d2](https://linux-hardware.org/?probe=3227f997d2) | Nov 01, 2020 |
| Lenovo        | SKYBAY NOK                  | [12275da1a1](https://linux-hardware.org/?probe=12275da1a1) | Nov 01, 2020 |
| Lenovo        | SKYBAY NOK                  | [0f0df8b1b5](https://linux-hardware.org/?probe=0f0df8b1b5) | Oct 31, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [5c28024ff3](https://linux-hardware.org/?probe=5c28024ff3) | Oct 31, 2020 |
| HP            | 3047h                       | [a486fb85f3](https://linux-hardware.org/?probe=a486fb85f3) | Oct 30, 2020 |
| Gigabyte      | GA-MA785GMT-UD2H            | [f1f52464f4](https://linux-hardware.org/?probe=f1f52464f4) | Oct 29, 2020 |
| Gigabyte      | H61M-D2H                    | [08ff3c6d26](https://linux-hardware.org/?probe=08ff3c6d26) | Oct 29, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [9918cd246d](https://linux-hardware.org/?probe=9918cd246d) | Oct 29, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [edd6b994ed](https://linux-hardware.org/?probe=edd6b994ed) | Oct 29, 2020 |
| Gigabyte      | H61M-D2H                    | [178f7a1504](https://linux-hardware.org/?probe=178f7a1504) | Oct 29, 2020 |
| ASUSTek       | P9X79 DELUXE                | [00a751b7fe](https://linux-hardware.org/?probe=00a751b7fe) | Oct 28, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [a13afb5c54](https://linux-hardware.org/?probe=a13afb5c54) | Oct 27, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6dc4099928](https://linux-hardware.org/?probe=6dc4099928) | Oct 27, 2020 |
| MSI           | B450M PRO-VDH MAX           | [57b37f655a](https://linux-hardware.org/?probe=57b37f655a) | Oct 26, 2020 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [e35d245839](https://linux-hardware.org/?probe=e35d245839) | Oct 26, 2020 |
| HP            | 3047h                       | [a854e09145](https://linux-hardware.org/?probe=a854e09145) | Oct 26, 2020 |
| Gigabyte      | AB350-Gaming-CF             | [c8262b0785](https://linux-hardware.org/?probe=c8262b0785) | Oct 25, 2020 |
| ASRock        | AM1H-ITX                    | [4a6634694e](https://linux-hardware.org/?probe=4a6634694e) | Oct 25, 2020 |
| ASRock        | X370 Gaming X               | [7b50c1e794](https://linux-hardware.org/?probe=7b50c1e794) | Oct 25, 2020 |
| Dell          | 0PTTT9 A01                  | [103a67b98a](https://linux-hardware.org/?probe=103a67b98a) | Oct 24, 2020 |
| ITSUMI        | ADAX INCOM                  | [c8a6ba510c](https://linux-hardware.org/?probe=c8a6ba510c) | Oct 24, 2020 |
| HP            | 805D                        | [0ae5965b1a](https://linux-hardware.org/?probe=0ae5965b1a) | Oct 24, 2020 |
| Gigabyte      | H81M-S2H                    | [5b74e56d8d](https://linux-hardware.org/?probe=5b74e56d8d) | Oct 23, 2020 |
| Gigabyte      | M68M-S2P                    | [404b30c107](https://linux-hardware.org/?probe=404b30c107) | Oct 23, 2020 |
| ITSUMI        | ADAX INCOM                  | [d295c4075c](https://linux-hardware.org/?probe=d295c4075c) | Oct 23, 2020 |
| Gigabyte      | G33M-S2                     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| Gigabyte      | G33M-S2                     | [4d9dc543e1](https://linux-hardware.org/?probe=4d9dc543e1) | Oct 21, 2020 |
| ASRock        | Z87 Killer                  | [d1f9b90a92](https://linux-hardware.org/?probe=d1f9b90a92) | Oct 21, 2020 |
| Gigabyte      | M52LT-D3                    | [b7b9c983f1](https://linux-hardware.org/?probe=b7b9c983f1) | Oct 20, 2020 |
| Gigabyte      | Z77X-UD3H                   | [d3725d6ed3](https://linux-hardware.org/?probe=d3725d6ed3) | Oct 19, 2020 |
| Gigabyte      | Z270-HD3P-CF                | [e2cdf98b5c](https://linux-hardware.org/?probe=e2cdf98b5c) | Oct 18, 2020 |
| ASUSTek       | P5W DH Deluxe               | [483b23b6d8](https://linux-hardware.org/?probe=483b23b6d8) | Oct 18, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e5aa6a33a6](https://linux-hardware.org/?probe=e5aa6a33a6) | Oct 18, 2020 |
| Gigabyte      | B450M DS3H-CF               | [c8801fb018](https://linux-hardware.org/?probe=c8801fb018) | Oct 18, 2020 |
| ASUSTek       | PRIME X470-PRO              | [8b1721fd05](https://linux-hardware.org/?probe=8b1721fd05) | Oct 18, 2020 |
| HP            | 2240                        | [0ca04dd4bb](https://linux-hardware.org/?probe=0ca04dd4bb) | Oct 18, 2020 |
| MSI           | MEG X570 UNIFY              | [71c037fd25](https://linux-hardware.org/?probe=71c037fd25) | Oct 18, 2020 |
| MSI           | B75MA-P45                   | [98e864cdd7](https://linux-hardware.org/?probe=98e864cdd7) | Oct 17, 2020 |
| Gigabyte      | B450M DS3H-CF               | [0df8d108e2](https://linux-hardware.org/?probe=0df8d108e2) | Oct 17, 2020 |
| HP            | 2240                        | [2bf5cef2cb](https://linux-hardware.org/?probe=2bf5cef2cb) | Oct 17, 2020 |
| MSI           | B85I                        | [15145b6aa5](https://linux-hardware.org/?probe=15145b6aa5) | Oct 15, 2020 |
| ASRock        | Q1900B-ITX                  | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| ASRock        | ALiveNF6G-GLAN              | [8c04dd6ae3](https://linux-hardware.org/?probe=8c04dd6ae3) | Oct 15, 2020 |
| ASUSTek       | M4N78 SE                    | [370a099d8f](https://linux-hardware.org/?probe=370a099d8f) | Oct 14, 2020 |
| MSI           | P35 Platinum                | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI           | B350 TOMAHAWK PLUS          | [75ac83a928](https://linux-hardware.org/?probe=75ac83a928) | Oct 14, 2020 |
| ASRock        | 970 Pro3 R2.0               | [9a27d9f2e3](https://linux-hardware.org/?probe=9a27d9f2e3) | Oct 13, 2020 |
| ASRock        | 970 Pro3 R2.0               | [5eac047586](https://linux-hardware.org/?probe=5eac047586) | Oct 13, 2020 |
| AAEON         | UP-APL01 V0.4               | [1f4d8df21a](https://linux-hardware.org/?probe=1f4d8df21a) | Oct 13, 2020 |
| AAEON         | UP-APL01 V0.4               | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON         | UP-APL01 V0.4               | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| Lenovo        | ThinkCentre M58 6258W1M     | [db91d3db97](https://linux-hardware.org/?probe=db91d3db97) | Oct 12, 2020 |
| MSI           | G41M-P23                    | [8a22019afa](https://linux-hardware.org/?probe=8a22019afa) | Oct 10, 2020 |
| Gigabyte      | GA-M56S-S3                  | [e817d06c95](https://linux-hardware.org/?probe=e817d06c95) | Oct 10, 2020 |
| MSI           | Z170A SLI PLUS              | [21cc5cccfe](https://linux-hardware.org/?probe=21cc5cccfe) | Oct 08, 2020 |
| Intel         | DH67BL AAG10189-211         | [32e899affd](https://linux-hardware.org/?probe=32e899affd) | Oct 08, 2020 |
| MSI           | MEG X570 UNIFY              | [bc040e4fa3](https://linux-hardware.org/?probe=bc040e4fa3) | Oct 08, 2020 |
| Gigabyte      | GA-M56S-S3                  | [e030408c02](https://linux-hardware.org/?probe=e030408c02) | Oct 05, 2020 |
| Gigabyte      | GA-M56S-S3                  | [a1fd718909](https://linux-hardware.org/?probe=a1fd718909) | Oct 05, 2020 |
| Gigabyte      | GA-M56S-S3                  | [29d2801ce1](https://linux-hardware.org/?probe=29d2801ce1) | Oct 04, 2020 |
| AMD           | 970A-D3                     | [b9b0c00b44](https://linux-hardware.org/?probe=b9b0c00b44) | Oct 04, 2020 |
| ASUSTek       | M5A78L/USB3                 | [978a7d0ce3](https://linux-hardware.org/?probe=978a7d0ce3) | Oct 04, 2020 |
| HP            | 843C                        | [44d0a4a392](https://linux-hardware.org/?probe=44d0a4a392) | Oct 03, 2020 |
| Gigabyte      | H81M-S2H                    | [db89bbaf17](https://linux-hardware.org/?probe=db89bbaf17) | Oct 02, 2020 |
| ASUSTek       | P5VD2-VM/SI                 | [6238bafc54](https://linux-hardware.org/?probe=6238bafc54) | Oct 01, 2020 |
| Gigabyte      | H81M-S2H                    | [8f76f0ded1](https://linux-hardware.org/?probe=8f76f0ded1) | Oct 01, 2020 |
| Gigabyte      | H81M-S2H                    | [3694cb0a17](https://linux-hardware.org/?probe=3694cb0a17) | Sep 30, 2020 |
| ASUSTek       | P5Q-PRO                     | [2b140526a7](https://linux-hardware.org/?probe=2b140526a7) | Sep 29, 2020 |
| ASRock        | P67 Pro3                    | [74e75615d2](https://linux-hardware.org/?probe=74e75615d2) | Sep 29, 2020 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [a0274682d1](https://linux-hardware.org/?probe=a0274682d1) | Sep 29, 2020 |
| MSI           | X470 GAMING PLUS            | [cfb285ef78](https://linux-hardware.org/?probe=cfb285ef78) | Sep 29, 2020 |
| MSI           | B150M MORTAR                | [be4753fd6a](https://linux-hardware.org/?probe=be4753fd6a) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d7a42f600d](https://linux-hardware.org/?probe=d7a42f600d) | Sep 28, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b49235a2e5](https://linux-hardware.org/?probe=b49235a2e5) | Sep 28, 2020 |
| MSI           | B450M MORTAR                | [e75e5bb91f](https://linux-hardware.org/?probe=e75e5bb91f) | Sep 28, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [80ab27cc07](https://linux-hardware.org/?probe=80ab27cc07) | Sep 28, 2020 |
| ASUSTek       | M4N68T-M                    | [8e9c1a631b](https://linux-hardware.org/?probe=8e9c1a631b) | Sep 28, 2020 |
| ASUSTek       | M5A78L/USB3                 | [ecf2bea799](https://linux-hardware.org/?probe=ecf2bea799) | Sep 27, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [73e8eb3027](https://linux-hardware.org/?probe=73e8eb3027) | Sep 27, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [2c46451b47](https://linux-hardware.org/?probe=2c46451b47) | Sep 27, 2020 |
| Gigabyte      | H81M-S2H                    | [85a0eccdb7](https://linux-hardware.org/?probe=85a0eccdb7) | Sep 26, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1774bd11c3](https://linux-hardware.org/?probe=1774bd11c3) | Sep 24, 2020 |
| ASUSTek       | P5G41C-M LX                 | [1865dce38e](https://linux-hardware.org/?probe=1865dce38e) | Sep 24, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [c2bf86aa14](https://linux-hardware.org/?probe=c2bf86aa14) | Sep 23, 2020 |
| Foxconn       | 2ABF                        | [adc420dcad](https://linux-hardware.org/?probe=adc420dcad) | Sep 22, 2020 |
| MSI           | Z170A KRAIT GAMING          | [30c68f5c5e](https://linux-hardware.org/?probe=30c68f5c5e) | Sep 21, 2020 |
| Gigabyte      | G31M-ES2L                   | [3af6acd1df](https://linux-hardware.org/?probe=3af6acd1df) | Sep 20, 2020 |
| Lenovo        | ThinkStation C20 4263BA7    | [a354af27e4](https://linux-hardware.org/?probe=a354af27e4) | Sep 20, 2020 |
| MSI           | B350M PRO-VDH               | [ced45325dc](https://linux-hardware.org/?probe=ced45325dc) | Sep 19, 2020 |
| MSI           | B350M PRO-VDH               | [2a4719e003](https://linux-hardware.org/?probe=2a4719e003) | Sep 19, 2020 |
| HP            | 1497                        | [611acad193](https://linux-hardware.org/?probe=611acad193) | Sep 19, 2020 |
| Gigabyte      | B450M DS3H-CF               | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [dc32fe8000](https://linux-hardware.org/?probe=dc32fe8000) | Sep 14, 2020 |
| ASUSTek       | PRIME X370-A                | [e45c4f7e70](https://linux-hardware.org/?probe=e45c4f7e70) | Sep 14, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [5047e4c334](https://linux-hardware.org/?probe=5047e4c334) | Sep 14, 2020 |
| HP            | 0A50h                       | [ace0e3fed5](https://linux-hardware.org/?probe=ace0e3fed5) | Sep 13, 2020 |
| HP            | 0A50h                       | [f70b1ce07f](https://linux-hardware.org/?probe=f70b1ce07f) | Sep 12, 2020 |
| HP            | 2240                        | [8fbd5845f3](https://linux-hardware.org/?probe=8fbd5845f3) | Sep 12, 2020 |
| Gigabyte      | F2A88XM-DS2P                | [179e7be1c6](https://linux-hardware.org/?probe=179e7be1c6) | Sep 11, 2020 |
| ASUSTek       | PRIME X470-PRO              | [d28e3a4f5d](https://linux-hardware.org/?probe=d28e3a4f5d) | Sep 11, 2020 |
| MSI           | Z87-G45 GAMING              | [0f381ed88e](https://linux-hardware.org/?probe=0f381ed88e) | Sep 10, 2020 |
| Gigabyte      | M52L-S3                     | [0bdee55e37](https://linux-hardware.org/?probe=0bdee55e37) | Sep 10, 2020 |
| Gigabyte      | M52L-S3                     | [fce64501f5](https://linux-hardware.org/?probe=fce64501f5) | Sep 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | [044c2421f2](https://linux-hardware.org/?probe=044c2421f2) | Sep 10, 2020 |
| Gigabyte      | X570 UD                     | [a4c0edaf41](https://linux-hardware.org/?probe=a4c0edaf41) | Sep 09, 2020 |
| ASUSTek       | M5A78L/USB3                 | [cc2950dc5b](https://linux-hardware.org/?probe=cc2950dc5b) | Sep 09, 2020 |
| MSI           | B250M PRO-VDH               | [1b69ed3219](https://linux-hardware.org/?probe=1b69ed3219) | Sep 08, 2020 |
| MSI           | B85M-E45                    | [f36b064cb9](https://linux-hardware.org/?probe=f36b064cb9) | Sep 08, 2020 |
| MSI           | B450-A PRO MAX              | [3e61f07444](https://linux-hardware.org/?probe=3e61f07444) | Sep 05, 2020 |
| ASUSTek       | P5G41C-M LX                 | [ae07f658e9](https://linux-hardware.org/?probe=ae07f658e9) | Sep 04, 2020 |
| Gigabyte      | H87M-D3H                    | [23dab48c31](https://linux-hardware.org/?probe=23dab48c31) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [fb867ae10c](https://linux-hardware.org/?probe=fb867ae10c) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [55f4f61fbc](https://linux-hardware.org/?probe=55f4f61fbc) | Sep 03, 2020 |
| MSI           | B150M MORTAR                | [e6350e9205](https://linux-hardware.org/?probe=e6350e9205) | Sep 03, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [8cdb04e64c](https://linux-hardware.org/?probe=8cdb04e64c) | Sep 03, 2020 |
| Gigabyte      | X570 UD                     | [2ad8aec7ee](https://linux-hardware.org/?probe=2ad8aec7ee) | Sep 03, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [74cf5edb6d](https://linux-hardware.org/?probe=74cf5edb6d) | Sep 02, 2020 |
| Dell          | 0YP696 A02                  | [77d0cc1ee4](https://linux-hardware.org/?probe=77d0cc1ee4) | Sep 02, 2020 |
| Dell          | 0YP696 A02                  | [e578dd14a0](https://linux-hardware.org/?probe=e578dd14a0) | Sep 02, 2020 |
| Acer          | Batman A01                  | [e9d0e3d9d4](https://linux-hardware.org/?probe=e9d0e3d9d4) | Sep 02, 2020 |
| Dell          | 03NVJ6 A02                  | [1fcccf5bc4](https://linux-hardware.org/?probe=1fcccf5bc4) | Sep 02, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [4013c22706](https://linux-hardware.org/?probe=4013c22706) | Sep 02, 2020 |
| HP            | 1850                        | [9c88f16de6](https://linux-hardware.org/?probe=9c88f16de6) | Sep 01, 2020 |
| Gigabyte      | 990FXA-UD3                  | [41125363e5](https://linux-hardware.org/?probe=41125363e5) | Aug 31, 2020 |
| MSI           | Z370 TOMAHAWK               | [f13c27fe18](https://linux-hardware.org/?probe=f13c27fe18) | Aug 30, 2020 |
| MSI           | Z370 TOMAHAWK               | [6c84875b30](https://linux-hardware.org/?probe=6c84875b30) | Aug 30, 2020 |
| MSI           | B450M PRO-VDH MAX           | [cb2e998b69](https://linux-hardware.org/?probe=cb2e998b69) | Aug 30, 2020 |
| Fujitsu Si... | D2348-A3 S26361-D2348-A3    | [843ea33bcc](https://linux-hardware.org/?probe=843ea33bcc) | Aug 30, 2020 |
| HP            | 1495                        | [afcb8a85c9](https://linux-hardware.org/?probe=afcb8a85c9) | Aug 30, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [95132af36e](https://linux-hardware.org/?probe=95132af36e) | Aug 29, 2020 |
| ASRock        | X370 Gaming K4              | [7e1bcf3383](https://linux-hardware.org/?probe=7e1bcf3383) | Aug 28, 2020 |
| Gigabyte      | F2A88XM-DS2P                | [3ca5f733b0](https://linux-hardware.org/?probe=3ca5f733b0) | Aug 27, 2020 |
| Gigabyte      | F2A88XM-DS2P                | [809e5ab17a](https://linux-hardware.org/?probe=809e5ab17a) | Aug 27, 2020 |
| ASUSTek       | STRIX X99 GAMING            | [ab28370173](https://linux-hardware.org/?probe=ab28370173) | Aug 26, 2020 |
| ASRock        | X370 Gaming K4              | [cdfc54e628](https://linux-hardware.org/?probe=cdfc54e628) | Aug 26, 2020 |
| ASRock        | H110M-DGS R3.0              | [daab7de51d](https://linux-hardware.org/?probe=daab7de51d) | Aug 25, 2020 |
| ASRock        | H110M-DGS R3.0              | [7afc23ec6c](https://linux-hardware.org/?probe=7afc23ec6c) | Aug 25, 2020 |
| MSI           | MS-B0501 100                | [12c7b9ccc6](https://linux-hardware.org/?probe=12c7b9ccc6) | Aug 22, 2020 |
| HP            | 2240                        | [d4722ade59](https://linux-hardware.org/?probe=d4722ade59) | Aug 22, 2020 |
| Gigabyte      | H87M-D3H                    | [61fcafb419](https://linux-hardware.org/?probe=61fcafb419) | Aug 20, 2020 |
| ASRock        | B450 Pro4                   | [3434bf2783](https://linux-hardware.org/?probe=3434bf2783) | Aug 19, 2020 |
| Gigabyte      | M68M-S2P                    | [864f6a380e](https://linux-hardware.org/?probe=864f6a380e) | Aug 19, 2020 |
| MSI           | B450-A PRO MAX              | [a8bb7acbbc](https://linux-hardware.org/?probe=a8bb7acbbc) | Aug 19, 2020 |
| ASRock        | X370 Gaming K4              | [7b4ed35198](https://linux-hardware.org/?probe=7b4ed35198) | Aug 19, 2020 |
| Dell          | 0MN1TX A02                  | [bc4ae8b00c](https://linux-hardware.org/?probe=bc4ae8b00c) | Aug 17, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [d0171086f1](https://linux-hardware.org/?probe=d0171086f1) | Aug 17, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [316ac04cd7](https://linux-hardware.org/?probe=316ac04cd7) | Aug 17, 2020 |
| HP            | 09F0h                       | [7005371be0](https://linux-hardware.org/?probe=7005371be0) | Aug 17, 2020 |
| ASUSTek       | PRIME B450M-A               | [2455aa7a9f](https://linux-hardware.org/?probe=2455aa7a9f) | Aug 17, 2020 |
| Dell          | 0KC9NP A00                  | [e84942b68d](https://linux-hardware.org/?probe=e84942b68d) | Aug 16, 2020 |
| Dell          | 0KC9NP A00                  | [279f80cb24](https://linux-hardware.org/?probe=279f80cb24) | Aug 16, 2020 |
| Gigabyte      | GA-MA770T-UD3               | [624afc19f2](https://linux-hardware.org/?probe=624afc19f2) | Aug 15, 2020 |
| ASUSTek       | PRIME B450M-A               | [c2ea56de38](https://linux-hardware.org/?probe=c2ea56de38) | Aug 15, 2020 |
| Gigabyte      | GA-MA770T-UD3               | [f6e1f27631](https://linux-hardware.org/?probe=f6e1f27631) | Aug 13, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [10cf6b4f29](https://linux-hardware.org/?probe=10cf6b4f29) | Aug 13, 2020 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [a0a33387d6](https://linux-hardware.org/?probe=a0a33387d6) | Aug 12, 2020 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [7666590fc7](https://linux-hardware.org/?probe=7666590fc7) | Aug 12, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [ff30cd0d5c](https://linux-hardware.org/?probe=ff30cd0d5c) | Aug 12, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [4219c82d3b](https://linux-hardware.org/?probe=4219c82d3b) | Aug 12, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [503010a607](https://linux-hardware.org/?probe=503010a607) | Aug 11, 2020 |
| Gigabyte      | 965P-S3                     | [650a84fcd6](https://linux-hardware.org/?probe=650a84fcd6) | Aug 10, 2020 |
| Dell          | 0T1D10 A01                  | [b0f8e1915c](https://linux-hardware.org/?probe=b0f8e1915c) | Aug 10, 2020 |
| HP            | 2240                        | [f64ce7b7e2](https://linux-hardware.org/?probe=f64ce7b7e2) | Aug 10, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1c6f36de59](https://linux-hardware.org/?probe=1c6f36de59) | Aug 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |
| MSI           | Z97 GAMING 5                | [1db1a6d546](https://linux-hardware.org/?probe=1db1a6d546) | Aug 09, 2020 |
| ASRock        | B85M DASH/OL R2.0           | [e65b4ae161](https://linux-hardware.org/?probe=e65b4ae161) | Aug 09, 2020 |
| Dell          | 0XFWHV A00                  | [4051125129](https://linux-hardware.org/?probe=4051125129) | Aug 08, 2020 |
| MSI           | X470 GAMING PLUS            | [16a2e20150](https://linux-hardware.org/?probe=16a2e20150) | Aug 07, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [0d8218d292](https://linux-hardware.org/?probe=0d8218d292) | Aug 06, 2020 |
| Gigabyte      | M57SLI-S4                   | [21aa6f708e](https://linux-hardware.org/?probe=21aa6f708e) | Aug 04, 2020 |
| ASUSTek       | PRIME X470-PRO              | [3bdf9f57dc](https://linux-hardware.org/?probe=3bdf9f57dc) | Aug 04, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [3db3d5cbc4](https://linux-hardware.org/?probe=3db3d5cbc4) | Aug 03, 2020 |
| ASUSTek       | P8H77-M                     | [88086cbdff](https://linux-hardware.org/?probe=88086cbdff) | Aug 03, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [cc1c13114f](https://linux-hardware.org/?probe=cc1c13114f) | Aug 03, 2020 |
| ASRock        | Z87 Extreme4                | [2e74988e53](https://linux-hardware.org/?probe=2e74988e53) | Aug 03, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [03139226e0](https://linux-hardware.org/?probe=03139226e0) | Aug 02, 2020 |
| ASUSTek       | P8B75-M                     | [2fb6b6f2c3](https://linux-hardware.org/?probe=2fb6b6f2c3) | Jul 30, 2020 |
| ASRock        | B250M Pro4                  | [5aed8654f2](https://linux-hardware.org/?probe=5aed8654f2) | Jul 29, 2020 |
| ASRock        | Z97X Killer                 | [865b4caecf](https://linux-hardware.org/?probe=865b4caecf) | Jul 28, 2020 |
| ASRock        | Z97X Killer                 | [e4b1700411](https://linux-hardware.org/?probe=e4b1700411) | Jul 28, 2020 |
| Gigabyte      | GA-78LMT-S2P                | [18aad26af0](https://linux-hardware.org/?probe=18aad26af0) | Jul 26, 2020 |
| Medion        | H77H2-EM V1.0               | [44e6cc21d7](https://linux-hardware.org/?probe=44e6cc21d7) | Jul 24, 2020 |
| Gigabyte      | H67MA-USB3-B3               | [1679b55773](https://linux-hardware.org/?probe=1679b55773) | Jul 22, 2020 |
| HP            | 1495                        | [ce754c6fe9](https://linux-hardware.org/?probe=ce754c6fe9) | Jul 21, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [292d396a46](https://linux-hardware.org/?probe=292d396a46) | Jul 21, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [4762cecc62](https://linux-hardware.org/?probe=4762cecc62) | Jul 20, 2020 |
| ASRock        | B450 Pro4                   | [86d8d2d1d2](https://linux-hardware.org/?probe=86d8d2d1d2) | Jul 19, 2020 |
| Gigabyte      | EP31-DS3L                   | [c801d8c7ae](https://linux-hardware.org/?probe=c801d8c7ae) | Jul 18, 2020 |
| ASUSTek       | PRIME X370-PRO              | [82a1036558](https://linux-hardware.org/?probe=82a1036558) | Jul 18, 2020 |
| ASRock        | B450 Pro4                   | [c50250c87f](https://linux-hardware.org/?probe=c50250c87f) | Jul 18, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [c4f3acfd2e](https://linux-hardware.org/?probe=c4f3acfd2e) | Jul 16, 2020 |
| MSI           | X570-A PRO                  | [ba532a609b](https://linux-hardware.org/?probe=ba532a609b) | Jul 16, 2020 |
| Gigabyte      | G41MT-USB3                  | [7bfebb0ad7](https://linux-hardware.org/?probe=7bfebb0ad7) | Jul 14, 2020 |
| Gigabyte      | A55M-DS2                    | [d3706ceaaf](https://linux-hardware.org/?probe=d3706ceaaf) | Jul 14, 2020 |
| Gigabyte      | A55M-DS2                    | [6efbf84a78](https://linux-hardware.org/?probe=6efbf84a78) | Jul 14, 2020 |
| Gigabyte      | B85M-D3H                    | [6871649bc8](https://linux-hardware.org/?probe=6871649bc8) | Jul 13, 2020 |
| Gigabyte      | H81M-S2H                    | [35f073d05f](https://linux-hardware.org/?probe=35f073d05f) | Jul 13, 2020 |
| Gigabyte      | H61M-D2-B3                  | [3657d59de2](https://linux-hardware.org/?probe=3657d59de2) | Jul 13, 2020 |
| MSI           | X570-A PRO                  | [dbd78b73af](https://linux-hardware.org/?probe=dbd78b73af) | Jul 13, 2020 |
| ASUSTek       | PRIME X570-P                | [bbde45673d](https://linux-hardware.org/?probe=bbde45673d) | Jul 13, 2020 |
| Gigabyte      | H81M-S2H                    | [67b29f4df3](https://linux-hardware.org/?probe=67b29f4df3) | Jul 12, 2020 |
| ASUSTek       | H110M-D                     | [9fbb496ae7](https://linux-hardware.org/?probe=9fbb496ae7) | Jul 12, 2020 |
| Gigabyte      | P41-ES3G                    | [b14f991de8](https://linux-hardware.org/?probe=b14f991de8) | Jul 12, 2020 |
| Gigabyte      | A320M-S2H-CF                | [114afa46c6](https://linux-hardware.org/?probe=114afa46c6) | Jul 12, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [3ef930f230](https://linux-hardware.org/?probe=3ef930f230) | Jul 11, 2020 |
| ASUSTek       | PRIME B450M-A               | [9f7ee8f663](https://linux-hardware.org/?probe=9f7ee8f663) | Jul 11, 2020 |
| Gigabyte      | GA-770T-USB3                | [6852cfce63](https://linux-hardware.org/?probe=6852cfce63) | Jul 11, 2020 |
| HP            | 1495                        | [6d66650388](https://linux-hardware.org/?probe=6d66650388) | Jul 10, 2020 |
| HP            | 1497                        | [a8d914dfb1](https://linux-hardware.org/?probe=a8d914dfb1) | Jul 09, 2020 |
| MSI           | G41M-P33 Combo              | [eb330d82bf](https://linux-hardware.org/?probe=eb330d82bf) | Jul 09, 2020 |
| Fujitsu Si... | D2581-A1 S26361-D2581-A1    | [d300426e5f](https://linux-hardware.org/?probe=d300426e5f) | Jul 08, 2020 |
| HP            | 1497                        | [89fa314487](https://linux-hardware.org/?probe=89fa314487) | Jul 08, 2020 |
| Dell          | 0YXT71 A02                  | [0d249e4d90](https://linux-hardware.org/?probe=0d249e4d90) | Jul 08, 2020 |
| Gigabyte      | Z270X-Gaming 7              | [845d870d68](https://linux-hardware.org/?probe=845d870d68) | Jul 08, 2020 |
| Lenovo        | Annapurna CRB 0B98405 ST... | [1f90a5a2c6](https://linux-hardware.org/?probe=1f90a5a2c6) | Jul 06, 2020 |
| Lenovo        | Annapurna CRB 0B98405 ST... | [b11a5615d7](https://linux-hardware.org/?probe=b11a5615d7) | Jul 06, 2020 |
| ASRock        | Z97 Extreme3                | [c355461508](https://linux-hardware.org/?probe=c355461508) | Jul 06, 2020 |
| ECS           | H61H2-MV                    | [d6e984cc6e](https://linux-hardware.org/?probe=d6e984cc6e) | Jul 05, 2020 |
| ASUSTek       | P5G41T-M LX                 | [2d0245b35c](https://linux-hardware.org/?probe=2d0245b35c) | Jul 04, 2020 |
| ASUSTek       | P5G41T-M LX                 | [660941c728](https://linux-hardware.org/?probe=660941c728) | Jul 04, 2020 |
| MSI           | MS-B9181                    | [0b2f242937](https://linux-hardware.org/?probe=0b2f242937) | Jul 03, 2020 |
| Gigabyte      | B150M-D3H-CF                | [852c6a3f91](https://linux-hardware.org/?probe=852c6a3f91) | Jul 03, 2020 |
| MSI           | G41M-P33 Combo              | [f4d356b23c](https://linux-hardware.org/?probe=f4d356b23c) | Jul 01, 2020 |
| MSI           | G41M-P33 Combo              | [aff1817a63](https://linux-hardware.org/?probe=aff1817a63) | Jul 01, 2020 |
| ASUSTek       | F2A85-V PRO                 | [ed44c9592d](https://linux-hardware.org/?probe=ed44c9592d) | Jun 30, 2020 |
| ASUSTek       | F2A85-V PRO                 | [a15c9a6410](https://linux-hardware.org/?probe=a15c9a6410) | Jun 30, 2020 |
| Dell          | 0D441T A01                  | [ce62457cdc](https://linux-hardware.org/?probe=ce62457cdc) | Jun 30, 2020 |
| ASUSTek       | PRIME A320M-K               | [b17ab3f32f](https://linux-hardware.org/?probe=b17ab3f32f) | Jun 30, 2020 |
| ASUSTek       | PRIME A320M-K               | [5b2ac771a1](https://linux-hardware.org/?probe=5b2ac771a1) | Jun 30, 2020 |
| MSI           | G41M-P33 Combo              | [0ee105915b](https://linux-hardware.org/?probe=0ee105915b) | Jun 30, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [dece2951c4](https://linux-hardware.org/?probe=dece2951c4) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c1d0ef500e](https://linux-hardware.org/?probe=c1d0ef500e) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6a9b477b88](https://linux-hardware.org/?probe=6a9b477b88) | Jun 29, 2020 |
| MSI           | B450M PRO-VDH MAX           | [de72f9930d](https://linux-hardware.org/?probe=de72f9930d) | Jun 28, 2020 |
| MSI           | B450M PRO-VDH MAX           | [9159f538a0](https://linux-hardware.org/?probe=9159f538a0) | Jun 28, 2020 |
| ASRock        | X370M Pro4                  | [dee76dc3cf](https://linux-hardware.org/?probe=dee76dc3cf) | Jun 28, 2020 |
| Gigabyte      | B450M DS3H-CF               | [58c7a4a657](https://linux-hardware.org/?probe=58c7a4a657) | Jun 27, 2020 |
| MSI           | G41M-P33 Combo              | [ba89294f76](https://linux-hardware.org/?probe=ba89294f76) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS4    | [371f1b5b54](https://linux-hardware.org/?probe=371f1b5b54) | Jun 25, 2020 |
| ASRock        | H55M-LE                     | [2096c3a907](https://linux-hardware.org/?probe=2096c3a907) | Jun 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | [aac509f3f8](https://linux-hardware.org/?probe=aac509f3f8) | Jun 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | [3b6e0e7a35](https://linux-hardware.org/?probe=3b6e0e7a35) | Jun 25, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [a08e7f3fed](https://linux-hardware.org/?probe=a08e7f3fed) | Jun 24, 2020 |
| Gigabyte      | B365M DS3H                  | [e5a5391106](https://linux-hardware.org/?probe=e5a5391106) | Jun 23, 2020 |
| ECS           | H61H2-MV                    | [da2c202d40](https://linux-hardware.org/?probe=da2c202d40) | Jun 23, 2020 |
| HP            | 0AA8h                       | [b482d40ce1](https://linux-hardware.org/?probe=b482d40ce1) | Jun 22, 2020 |
| MSI           | Z97 GAMING 5                | [31cd425087](https://linux-hardware.org/?probe=31cd425087) | Jun 21, 2020 |
| ASUSTek       | M2N                         | [f3cfc308e4](https://linux-hardware.org/?probe=f3cfc308e4) | Jun 21, 2020 |
| MSI           | G41M-P33 Combo              | [bd024d4ce2](https://linux-hardware.org/?probe=bd024d4ce2) | Jun 20, 2020 |
| ASRock        | ALiveNF6G-VSTA              | [32c169cd3e](https://linux-hardware.org/?probe=32c169cd3e) | Jun 20, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [17fd512f14](https://linux-hardware.org/?probe=17fd512f14) | Jun 20, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0486440597](https://linux-hardware.org/?probe=0486440597) | Jun 20, 2020 |
| MSI           | G41M-P33 Combo              | [4569a83fa0](https://linux-hardware.org/?probe=4569a83fa0) | Jun 20, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [9b7c9e5940](https://linux-hardware.org/?probe=9b7c9e5940) | Jun 20, 2020 |
| Gigabyte      | B365M DS3H                  | [3c311dbb3d](https://linux-hardware.org/?probe=3c311dbb3d) | Jun 20, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [e9e5ee4413](https://linux-hardware.org/?probe=e9e5ee4413) | Jun 19, 2020 |
| HP            | 3047h                       | [0e5402cd3f](https://linux-hardware.org/?probe=0e5402cd3f) | Jun 19, 2020 |
| Lenovo        | ThinkCentre M90 Twardzie... | [d7b806d870](https://linux-hardware.org/?probe=d7b806d870) | Jun 19, 2020 |
| Lenovo        | ThinkCentre M90 Twardzie... | [89d58fee8b](https://linux-hardware.org/?probe=89d58fee8b) | Jun 19, 2020 |
| HP            | 3396                        | [7a1159789f](https://linux-hardware.org/?probe=7a1159789f) | Jun 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [cb0f4c9548](https://linux-hardware.org/?probe=cb0f4c9548) | Jun 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [129777670e](https://linux-hardware.org/?probe=129777670e) | Jun 18, 2020 |
| ECS           | H61H2-MV                    | [0dffa34f7a](https://linux-hardware.org/?probe=0dffa34f7a) | Jun 17, 2020 |
| ASUSTek       | PRIME X370-PRO              | [f99d436199](https://linux-hardware.org/?probe=f99d436199) | Jun 17, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4d47959be2](https://linux-hardware.org/?probe=4d47959be2) | Jun 17, 2020 |
| ASUSTek       | A88XM-E                     | [8c73a2a31b](https://linux-hardware.org/?probe=8c73a2a31b) | Jun 17, 2020 |
| ASUSTek       | P5Q-PRO                     | [8d2a8addb6](https://linux-hardware.org/?probe=8d2a8addb6) | Jun 17, 2020 |
| ASRock        | P67 Pro3                    | [23d97a5ed9](https://linux-hardware.org/?probe=23d97a5ed9) | Jun 17, 2020 |
| ASUSTek       | M4A77                       | [af3b0ac4b6](https://linux-hardware.org/?probe=af3b0ac4b6) | Jun 17, 2020 |
| Dell          | 03NVJ6 A00                  | [a129d8050e](https://linux-hardware.org/?probe=a129d8050e) | Jun 16, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [6e7f34f58c](https://linux-hardware.org/?probe=6e7f34f58c) | Jun 15, 2020 |
| MSI           | Z97 GAMING 5                | [5e7b32bf97](https://linux-hardware.org/?probe=5e7b32bf97) | Jun 15, 2020 |
| Gigabyte      | H81M-D2V                    | [e6cb18dc5d](https://linux-hardware.org/?probe=e6cb18dc5d) | Jun 15, 2020 |
| Gigabyte      | B365M DS3H                  | [13f8a3088a](https://linux-hardware.org/?probe=13f8a3088a) | Jun 15, 2020 |
| ASUSTek       | PRIME X470-PRO              | [226499bbd2](https://linux-hardware.org/?probe=226499bbd2) | Jun 14, 2020 |
| ASUSTek       | P5G41T-M LX                 | [6611975036](https://linux-hardware.org/?probe=6611975036) | Jun 13, 2020 |
| MSI           | 970 GAMING                  | [259376d581](https://linux-hardware.org/?probe=259376d581) | Jun 13, 2020 |
| HP            | 3396                        | [fa40c2d283](https://linux-hardware.org/?probe=fa40c2d283) | Jun 10, 2020 |
| ASUSTek       | Z97-K                       | [d32c688bb4](https://linux-hardware.org/?probe=d32c688bb4) | Jun 09, 2020 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [0addfe754c](https://linux-hardware.org/?probe=0addfe754c) | Jun 09, 2020 |
| ASUSTek       | K8N4-E Deluxe               | [0908450cf0](https://linux-hardware.org/?probe=0908450cf0) | Jun 08, 2020 |
| Gigabyte      | Z270P-D3-CF                 | [dcc91af2c6](https://linux-hardware.org/?probe=dcc91af2c6) | Jun 08, 2020 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [0f34427953](https://linux-hardware.org/?probe=0f34427953) | Jun 07, 2020 |
| Gigabyte      | P61-S3                      | [6074b50487](https://linux-hardware.org/?probe=6074b50487) | Jun 07, 2020 |
| Gigabyte      | 970A-DS3                    | [fafed886c2](https://linux-hardware.org/?probe=fafed886c2) | Jun 07, 2020 |
| MSI           | A320M GRENADE               | [b8cc6a4383](https://linux-hardware.org/?probe=b8cc6a4383) | Jun 07, 2020 |
| ASUSTek       | P5K                         | [54ca96462b](https://linux-hardware.org/?probe=54ca96462b) | Jun 06, 2020 |
| ASUSTek       | P5K                         | [79b55ede60](https://linux-hardware.org/?probe=79b55ede60) | Jun 06, 2020 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [0dc515a4e8](https://linux-hardware.org/?probe=0dc515a4e8) | Jun 06, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [056b34567f](https://linux-hardware.org/?probe=056b34567f) | Jun 06, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [5d852ecca8](https://linux-hardware.org/?probe=5d852ecca8) | Jun 06, 2020 |
| ASRock        | H81M-ITX/WiFi               | [6c43933a02](https://linux-hardware.org/?probe=6c43933a02) | Jun 05, 2020 |
| ASRock        | Z390 Extreme4               | [e64653b77c](https://linux-hardware.org/?probe=e64653b77c) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | [ff470637f1](https://linux-hardware.org/?probe=ff470637f1) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [b379b98120](https://linux-hardware.org/?probe=b379b98120) | Jun 04, 2020 |
| Dell          | 0GM819                      | [7ad58ffbd2](https://linux-hardware.org/?probe=7ad58ffbd2) | Jun 02, 2020 |
| Gigabyte      | Z77X-D3H                    | [6e6aca8da0](https://linux-hardware.org/?probe=6e6aca8da0) | Jun 02, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [d3ffbfc9c0](https://linux-hardware.org/?probe=d3ffbfc9c0) | Jun 02, 2020 |
| Dell          | 0200DY A03                  | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| MSI           | A55M-P33                    | [2f8eadddc4](https://linux-hardware.org/?probe=2f8eadddc4) | May 31, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [d4c935a726](https://linux-hardware.org/?probe=d4c935a726) | May 30, 2020 |
| Dell          | 00F82W A00                  | [a99361ae4c](https://linux-hardware.org/?probe=a99361ae4c) | May 26, 2020 |
| MSI           | B450M PRO-VDH MAX           | [0e7c8d0cdc](https://linux-hardware.org/?probe=0e7c8d0cdc) | May 25, 2020 |
| MSI           | Z170-A PRO                  | [366c5faefa](https://linux-hardware.org/?probe=366c5faefa) | May 25, 2020 |
| MSI           | B450M PRO-VDH MAX           | [d3ee84bb57](https://linux-hardware.org/?probe=d3ee84bb57) | May 25, 2020 |
| Dell          | 0YXT71 A02                  | [e3f86df812](https://linux-hardware.org/?probe=e3f86df812) | May 25, 2020 |
| Dell          | 0C27VV A01                  | [1192d26033](https://linux-hardware.org/?probe=1192d26033) | May 25, 2020 |
| ASUSTek       | P5B-Deluxe                  | [08c406ee91](https://linux-hardware.org/?probe=08c406ee91) | May 24, 2020 |
| ASUSTek       | P5B-Deluxe                  | [a2da27e331](https://linux-hardware.org/?probe=a2da27e331) | May 24, 2020 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | [e525642f48](https://linux-hardware.org/?probe=e525642f48) | May 24, 2020 |
| Dell          | 0X231R A01                  | [cb7598899f](https://linux-hardware.org/?probe=cb7598899f) | May 23, 2020 |
| Dell          | 0X231R A01                  | [64a3bff575](https://linux-hardware.org/?probe=64a3bff575) | May 23, 2020 |
| Gigabyte      | GA-MA790X-UD4               | [9bcde1cfdc](https://linux-hardware.org/?probe=9bcde1cfdc) | May 23, 2020 |
| Gigabyte      | GA-MA790X-UD4               | [de315a2148](https://linux-hardware.org/?probe=de315a2148) | May 23, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [eff53b8d38](https://linux-hardware.org/?probe=eff53b8d38) | May 22, 2020 |
| Dell          | 0VRWRC A00                  | [34d429ad82](https://linux-hardware.org/?probe=34d429ad82) | May 21, 2020 |
| Dell          | 042P49 A00                  | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [6c4da588ea](https://linux-hardware.org/?probe=6c4da588ea) | May 21, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [8de5cb83eb](https://linux-hardware.org/?probe=8de5cb83eb) | May 21, 2020 |
| Gigabyte      | B450M DS3H-CF               | [7d6cda7b8e](https://linux-hardware.org/?probe=7d6cda7b8e) | May 21, 2020 |
| Dell          | 042P49 A00                  | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| Dell          | 00V62H A01                  | [45a19f2bb0](https://linux-hardware.org/?probe=45a19f2bb0) | May 19, 2020 |
| ASUSTek       | A88XM-A                     | [1128ac3406](https://linux-hardware.org/?probe=1128ac3406) | May 18, 2020 |
| Dell          | 0WF810                      | [24f1a1287d](https://linux-hardware.org/?probe=24f1a1287d) | May 17, 2020 |
| Dell          | 0WF810                      | [6ae0e21069](https://linux-hardware.org/?probe=6ae0e21069) | May 17, 2020 |
| Dell          | 0WF810                      | [e6f27fd467](https://linux-hardware.org/?probe=e6f27fd467) | May 17, 2020 |
| MSI           | G41M-P23                    | [06b16a5d5c](https://linux-hardware.org/?probe=06b16a5d5c) | May 16, 2020 |
| ASUSTek       | P5Q-PRO                     | [efcafb7e58](https://linux-hardware.org/?probe=efcafb7e58) | May 16, 2020 |
| ASUSTek       | P5Q-PRO                     | [9b99fdbc9a](https://linux-hardware.org/?probe=9b99fdbc9a) | May 16, 2020 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [82470b81ba](https://linux-hardware.org/?probe=82470b81ba) | May 15, 2020 |
| Dell          | 0T1D10 A01                  | [d258c7fd84](https://linux-hardware.org/?probe=d258c7fd84) | May 14, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [f69adb8baa](https://linux-hardware.org/?probe=f69adb8baa) | May 12, 2020 |
| ASUSTek       | P5RD2-VM                    | [13ca73b9a3](https://linux-hardware.org/?probe=13ca73b9a3) | May 12, 2020 |
| Gigabyte      | B150M-D3H-CF                | [f3e3d83b6a](https://linux-hardware.org/?probe=f3e3d83b6a) | May 11, 2020 |
| HP            | 1791                        | [b17481269e](https://linux-hardware.org/?probe=b17481269e) | May 10, 2020 |
| HP            | 1791                        | [70ee49d239](https://linux-hardware.org/?probe=70ee49d239) | May 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | [0644d9b289](https://linux-hardware.org/?probe=0644d9b289) | May 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | [cef1d33982](https://linux-hardware.org/?probe=cef1d33982) | May 09, 2020 |
| Dell          | 0YU822 A00                  | [7e198436d5](https://linux-hardware.org/?probe=7e198436d5) | May 09, 2020 |
| ASUSTek       | M4A89GTD-PRO                | [007fc73986](https://linux-hardware.org/?probe=007fc73986) | May 09, 2020 |
| ASRock        | B450M Pro4                  | [3e8a9279fc](https://linux-hardware.org/?probe=3e8a9279fc) | May 08, 2020 |
| MSI           | B250M PRO-VH                | [7240ad99bc](https://linux-hardware.org/?probe=7240ad99bc) | May 08, 2020 |
| MSI           | FM2-A55-G43                 | [8e60f2ff47](https://linux-hardware.org/?probe=8e60f2ff47) | May 08, 2020 |
| ASUSTek       | PRIME X370-PRO              | [6b703d1e7c](https://linux-hardware.org/?probe=6b703d1e7c) | May 08, 2020 |
| ASUSTek       | PRIME X370-PRO              | [937949ede6](https://linux-hardware.org/?probe=937949ede6) | May 08, 2020 |
| ASUSTek       | P7P55D-E                    | [6dabe7aafb](https://linux-hardware.org/?probe=6dabe7aafb) | May 08, 2020 |
| ASUSTek       | P7P55D-E                    | [6e27d6b28b](https://linux-hardware.org/?probe=6e27d6b28b) | May 08, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [3ef92a08e3](https://linux-hardware.org/?probe=3ef92a08e3) | May 07, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ab56bbe7cc](https://linux-hardware.org/?probe=ab56bbe7cc) | May 06, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d446520bef](https://linux-hardware.org/?probe=d446520bef) | May 06, 2020 |
| MSI           | B450-A PRO                  | [a47c3cdd42](https://linux-hardware.org/?probe=a47c3cdd42) | May 06, 2020 |
| Gigabyte      | M61SME-S2                   | [e29bc9ac9d](https://linux-hardware.org/?probe=e29bc9ac9d) | May 06, 2020 |
| ASUSTek       | C8HM70-I/HDMI               | [1bce8d72b4](https://linux-hardware.org/?probe=1bce8d72b4) | May 04, 2020 |
| Dell          | 0X231R A01                  | [6c175fc28c](https://linux-hardware.org/?probe=6c175fc28c) | May 04, 2020 |
| Gigabyte      | GA-MA69GM-S2H               | [ceaa808c4b](https://linux-hardware.org/?probe=ceaa808c4b) | May 03, 2020 |
| Gigabyte      | C1037UN-EU                  | [eeaaeddfde](https://linux-hardware.org/?probe=eeaaeddfde) | May 02, 2020 |
| ASUSTek       | P8P67 LE                    | [2701a098f7](https://linux-hardware.org/?probe=2701a098f7) | May 02, 2020 |
| Supermicro    | C2SBX                       | [2abe7e149c](https://linux-hardware.org/?probe=2abe7e149c) | May 01, 2020 |
| ASUSTek       | P5Q SE2                     | [99af8e5613](https://linux-hardware.org/?probe=99af8e5613) | May 01, 2020 |
| Gigabyte      | M61SME-S2                   | [dd84ddfb9e](https://linux-hardware.org/?probe=dd84ddfb9e) | Apr 30, 2020 |
| Gigabyte      | G31M-ES2L                   | [8288de4299](https://linux-hardware.org/?probe=8288de4299) | Apr 29, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [a13089eb47](https://linux-hardware.org/?probe=a13089eb47) | Apr 29, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [93a67bd2b4](https://linux-hardware.org/?probe=93a67bd2b4) | Apr 28, 2020 |
| Gigabyte      | 8I945GMF                    | [063c8b6c69](https://linux-hardware.org/?probe=063c8b6c69) | Apr 26, 2020 |
| Gigabyte      | 8I945GMF                    | [754314fbc1](https://linux-hardware.org/?probe=754314fbc1) | Apr 26, 2020 |
| Gigabyte      | H270-HD3-CF                 | [3cf8beef7b](https://linux-hardware.org/?probe=3cf8beef7b) | Apr 26, 2020 |
| Lenovo        | MAHOBAY NOK                 | [655aa23e68](https://linux-hardware.org/?probe=655aa23e68) | Apr 25, 2020 |
| ASUSTek       | P8Z68-V                     | [a5d4bc9b8a](https://linux-hardware.org/?probe=a5d4bc9b8a) | Apr 25, 2020 |
| ASUSTek       | B85M-G                      | [edad421acd](https://linux-hardware.org/?probe=edad421acd) | Apr 25, 2020 |
| Acer          | WMCP78M                     | [67b7a38a19](https://linux-hardware.org/?probe=67b7a38a19) | Apr 25, 2020 |
| Medion        | H77H2-EM V1.0               | [a5fa29ebeb](https://linux-hardware.org/?probe=a5fa29ebeb) | Apr 25, 2020 |
| ASUSTek       | PRIME A320M-A               | [34f9e16f16](https://linux-hardware.org/?probe=34f9e16f16) | Apr 23, 2020 |
| Unknown       | Unknown                     | [1507290efa](https://linux-hardware.org/?probe=1507290efa) | Apr 22, 2020 |
| Gigabyte      | H270-HD3-CF                 | [7426d75e03](https://linux-hardware.org/?probe=7426d75e03) | Apr 21, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [e261349550](https://linux-hardware.org/?probe=e261349550) | Apr 21, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [82e563c55a](https://linux-hardware.org/?probe=82e563c55a) | Apr 21, 2020 |
| ASUSTek       | P5Q                         | [cf20e92a38](https://linux-hardware.org/?probe=cf20e92a38) | Apr 20, 2020 |
| ASUSTek       | Rampage V EXTREME           | [51940accec](https://linux-hardware.org/?probe=51940accec) | Apr 20, 2020 |
| Unknown       | Unknown                     | [08a75c2f44](https://linux-hardware.org/?probe=08a75c2f44) | Apr 19, 2020 |
| Unknown       | Unknown                     | [3b78d2f31b](https://linux-hardware.org/?probe=3b78d2f31b) | Apr 19, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [8625c51506](https://linux-hardware.org/?probe=8625c51506) | Apr 19, 2020 |
| MSI           | H81M-P33                    | [bb31e70f75](https://linux-hardware.org/?probe=bb31e70f75) | Apr 19, 2020 |
| Acer          | Veriton X2610G              | [09dc97ef3b](https://linux-hardware.org/?probe=09dc97ef3b) | Apr 18, 2020 |
| ASUSTek       | H110I-PLUS                  | [3687635ac0](https://linux-hardware.org/?probe=3687635ac0) | Apr 18, 2020 |
| ASUSTek       | P5G41T-M LX                 | [195cae09f7](https://linux-hardware.org/?probe=195cae09f7) | Apr 18, 2020 |
| ASRock        | J4205-ITX                   | [dc69381f3e](https://linux-hardware.org/?probe=dc69381f3e) | Apr 18, 2020 |
| Dell          | 0YU822 A00                  | [36be05488e](https://linux-hardware.org/?probe=36be05488e) | Apr 17, 2020 |
| Dell          | 0YU822 A00                  | [4f28b56e77](https://linux-hardware.org/?probe=4f28b56e77) | Apr 17, 2020 |
| Dell          | 018D1Y A00                  | [3ee0b2160d](https://linux-hardware.org/?probe=3ee0b2160d) | Apr 16, 2020 |
| Apple         | Mac-F221BEC8                | [418a4061c0](https://linux-hardware.org/?probe=418a4061c0) | Apr 15, 2020 |
| Apple         | Mac-F221BEC8                | [1733a76525](https://linux-hardware.org/?probe=1733a76525) | Apr 14, 2020 |
| Lenovo        | ThinkCentre M58p 7483W4N    | [91a94f04d9](https://linux-hardware.org/?probe=91a94f04d9) | Apr 14, 2020 |
| ASRock        | G31M-GS                     | [32ffa1664e](https://linux-hardware.org/?probe=32ffa1664e) | Apr 14, 2020 |
| Gigabyte      | P61-S3                      | [5b4be824a5](https://linux-hardware.org/?probe=5b4be824a5) | Apr 14, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [1969b17a11](https://linux-hardware.org/?probe=1969b17a11) | Apr 13, 2020 |
| Dell          | 0YXT71 A02                  | [f454033e1f](https://linux-hardware.org/?probe=f454033e1f) | Apr 13, 2020 |
| Dell          | 018D1Y A00                  | [ae16855d0c](https://linux-hardware.org/?probe=ae16855d0c) | Apr 13, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [167bbcb78f](https://linux-hardware.org/?probe=167bbcb78f) | Apr 13, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | [5ed9957756](https://linux-hardware.org/?probe=5ed9957756) | Apr 12, 2020 |
| MSI           | Z87-G45 GAMING              | [458cb841c7](https://linux-hardware.org/?probe=458cb841c7) | Apr 11, 2020 |
| ASRock        | G31M-GS                     | [c23ffe87ef](https://linux-hardware.org/?probe=c23ffe87ef) | Apr 11, 2020 |
| Gigabyte      | Z270-HD3P-CF                | [834963c17d](https://linux-hardware.org/?probe=834963c17d) | Apr 11, 2020 |
| Apple         | Mac-F221BEC8                | [c873663869](https://linux-hardware.org/?probe=c873663869) | Apr 11, 2020 |
| MSI           | B250M PRO-VH                | [2b7d8dae00](https://linux-hardware.org/?probe=2b7d8dae00) | Apr 09, 2020 |
| ASRock        | J4205-ITX                   | [8d1dd21c38](https://linux-hardware.org/?probe=8d1dd21c38) | Apr 08, 2020 |
| Dell          | 0N867P A02                  | [c2cf52f287](https://linux-hardware.org/?probe=c2cf52f287) | Apr 08, 2020 |
| ASUSTek       | PRIME X470-PRO              | [04a89c7155](https://linux-hardware.org/?probe=04a89c7155) | Apr 07, 2020 |
| Unknown       | Unknown                     | [671ed0e49c](https://linux-hardware.org/?probe=671ed0e49c) | Apr 07, 2020 |
| Gigabyte      | B75-D3V                     | [835d444163](https://linux-hardware.org/?probe=835d444163) | Apr 07, 2020 |
| MSI           | MS-B9181                    | [408a1c614d](https://linux-hardware.org/?probe=408a1c614d) | Apr 06, 2020 |
| ASUSTek       | M3A78-EM                    | [4e37c25a2d](https://linux-hardware.org/?probe=4e37c25a2d) | Apr 06, 2020 |
| ASUSTek       | PRIME A320M-K               | [bfbc451982](https://linux-hardware.org/?probe=bfbc451982) | Apr 05, 2020 |
| ASUSTek       | P5Q DELUXE                  | [dd0881a919](https://linux-hardware.org/?probe=dd0881a919) | Apr 04, 2020 |
| ASUSTek       | PRIME A320M-K               | [7b94a837ac](https://linux-hardware.org/?probe=7b94a837ac) | Apr 03, 2020 |
| MSI           | G41M-SP20                   | [7736f96e23](https://linux-hardware.org/?probe=7736f96e23) | Apr 02, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [bb982dda2a](https://linux-hardware.org/?probe=bb982dda2a) | Apr 01, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [ca5f32ba81](https://linux-hardware.org/?probe=ca5f32ba81) | Apr 01, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [9b55fb9abe](https://linux-hardware.org/?probe=9b55fb9abe) | Mar 31, 2020 |
| Dell          | 0RW199                      | [04980fad83](https://linux-hardware.org/?probe=04980fad83) | Mar 30, 2020 |
| Dell          | 0RW199                      | [18c0019a9a](https://linux-hardware.org/?probe=18c0019a9a) | Mar 30, 2020 |
| Dell          | 0XCR8D A01                  | [0ff015af0d](https://linux-hardware.org/?probe=0ff015af0d) | Mar 28, 2020 |
| MSI           | A88XM-E35 V2                | [d0ae6be7fe](https://linux-hardware.org/?probe=d0ae6be7fe) | Mar 28, 2020 |
| Gigabyte      | 945GCM-S2L                  | [548577276f](https://linux-hardware.org/?probe=548577276f) | Mar 27, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [ace4842891](https://linux-hardware.org/?probe=ace4842891) | Mar 27, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [92ff7bfbc1](https://linux-hardware.org/?probe=92ff7bfbc1) | Mar 27, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [cbd5b29f8a](https://linux-hardware.org/?probe=cbd5b29f8a) | Mar 26, 2020 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [3bd3302735](https://linux-hardware.org/?probe=3bd3302735) | Mar 26, 2020 |
| ECS           | K8M890M-M                   | [93490e7142](https://linux-hardware.org/?probe=93490e7142) | Mar 24, 2020 |
| Gigabyte      | P31-DS3L                    | [8c22f7fc72](https://linux-hardware.org/?probe=8c22f7fc72) | Mar 24, 2020 |
| Gigabyte      | P31-DS3L                    | [f57d071485](https://linux-hardware.org/?probe=f57d071485) | Mar 24, 2020 |
| ASRock        | Z390 Taichi                 | [69e2eeb45f](https://linux-hardware.org/?probe=69e2eeb45f) | Mar 24, 2020 |
| Gigabyte      | B85-HD3-A                   | [72a529e646](https://linux-hardware.org/?probe=72a529e646) | Mar 24, 2020 |
| Intel         | DG31PR AAD97573-301         | [fe80a363e4](https://linux-hardware.org/?probe=fe80a363e4) | Mar 23, 2020 |
| MSI           | B250M PRO-VH                | [1bc40868f9](https://linux-hardware.org/?probe=1bc40868f9) | Mar 22, 2020 |
| ASUSTek       | P5LD2-VM                    | [6dccd8d0e9](https://linux-hardware.org/?probe=6dccd8d0e9) | Mar 20, 2020 |
| ASUSTek       | M3A78-CM                    | [1e9b01c58c](https://linux-hardware.org/?probe=1e9b01c58c) | Mar 20, 2020 |
| Shuttle       | FG33 V10                    | [f6717fb029](https://linux-hardware.org/?probe=f6717fb029) | Mar 19, 2020 |
| Gateway       | DT71                        | [e14a8952e5](https://linux-hardware.org/?probe=e14a8952e5) | Mar 19, 2020 |
| Gigabyte      | Z87X-OC-CF                  | [09c3d10620](https://linux-hardware.org/?probe=09c3d10620) | Mar 18, 2020 |
| Gigabyte      | 965P-DS3                    | [7d0c982dc1](https://linux-hardware.org/?probe=7d0c982dc1) | Mar 16, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [26b6ac3832](https://linux-hardware.org/?probe=26b6ac3832) | Mar 15, 2020 |
| Gigabyte      | M57SLI-S4                   | [41200af591](https://linux-hardware.org/?probe=41200af591) | Mar 15, 2020 |
| ASRock        | ALiveNF6G-VSTA              | [f4b63b6485](https://linux-hardware.org/?probe=f4b63b6485) | Mar 13, 2020 |
| ASUSTek       | Z97-P                       | [ac2df152b8](https://linux-hardware.org/?probe=ac2df152b8) | Mar 12, 2020 |
| ASUSTek       | PRIME X370-PRO              | [ff59f10036](https://linux-hardware.org/?probe=ff59f10036) | Mar 10, 2020 |
| Dell          | 09KPNV A01                  | [f7ee0efa1b](https://linux-hardware.org/?probe=f7ee0efa1b) | Mar 07, 2020 |
| MSI           | Z170A TOMAHAWK              | [0fa979bbfb](https://linux-hardware.org/?probe=0fa979bbfb) | Mar 07, 2020 |
| Gigabyte      | P55-UD3L                    | [92d3e969bb](https://linux-hardware.org/?probe=92d3e969bb) | Mar 05, 2020 |
| HP            | 18E5                        | [3dfda2b919](https://linux-hardware.org/?probe=3dfda2b919) | Mar 05, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [27550891b3](https://linux-hardware.org/?probe=27550891b3) | Mar 03, 2020 |
| ASUSTek       | P7P55D-E                    | [abcbeb58ff](https://linux-hardware.org/?probe=abcbeb58ff) | Mar 02, 2020 |
| ASUSTek       | PRIME X470-PRO              | [f091a59e95](https://linux-hardware.org/?probe=f091a59e95) | Mar 01, 2020 |
| Gigabyte      | M61SME-S2L                  | [645548327a](https://linux-hardware.org/?probe=645548327a) | Mar 01, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [2f2913c34c](https://linux-hardware.org/?probe=2f2913c34c) | Mar 01, 2020 |
| Gigabyte      | EP43-UD3L                   | [8ee76fb844](https://linux-hardware.org/?probe=8ee76fb844) | Feb 29, 2020 |
| ASUSTek       | F1A75-V PRO                 | [96d7d2a200](https://linux-hardware.org/?probe=96d7d2a200) | Feb 28, 2020 |
| MSI           | Z87-G45 GAMING              | [5af7c9aa0f](https://linux-hardware.org/?probe=5af7c9aa0f) | Feb 26, 2020 |
| Dell          | 08HPGT A01                  | [0e4ca5d5c4](https://linux-hardware.org/?probe=0e4ca5d5c4) | Feb 26, 2020 |
| Gigabyte      | B85M-D3H                    | [00442cfd17](https://linux-hardware.org/?probe=00442cfd17) | Feb 25, 2020 |
| MSI           | B360M PRO-VDH               | [f199e6ecca](https://linux-hardware.org/?probe=f199e6ecca) | Feb 24, 2020 |
| ASRock        | Z170 Gaming K4              | [fb5c561a90](https://linux-hardware.org/?probe=fb5c561a90) | Feb 21, 2020 |
| ASUSTek       | PRIME A320M-K               | [8692e1abf5](https://linux-hardware.org/?probe=8692e1abf5) | Feb 20, 2020 |
| ASUSTek       | PRIME A320M-K               | [6e4dc51e58](https://linux-hardware.org/?probe=6e4dc51e58) | Feb 20, 2020 |
| MSI           | B450 TOMAHAWK               | [68b11281a5](https://linux-hardware.org/?probe=68b11281a5) | Feb 17, 2020 |
| Medion        | H77H2-EM V1.0               | [fb9778d550](https://linux-hardware.org/?probe=fb9778d550) | Feb 17, 2020 |
| ASUSTek       | PRIME X470-PRO              | [ff3873f74c](https://linux-hardware.org/?probe=ff3873f74c) | Feb 14, 2020 |
| Medion        | H77H2-EM V1.0               | [bd7f65d0e4](https://linux-hardware.org/?probe=bd7f65d0e4) | Feb 13, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [d411dcff31](https://linux-hardware.org/?probe=d411dcff31) | Feb 13, 2020 |
| Lenovo        | 31900058 STD                | [0e46896c98](https://linux-hardware.org/?probe=0e46896c98) | Feb 13, 2020 |
| Lenovo        | 0B98401 PRO                 | [e0a073ae39](https://linux-hardware.org/?probe=e0a073ae39) | Feb 13, 2020 |
| Supermicro    | X9DAi                       | [f2d07088c6](https://linux-hardware.org/?probe=f2d07088c6) | Feb 12, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [0d093f4497](https://linux-hardware.org/?probe=0d093f4497) | Feb 10, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [825d8feb67](https://linux-hardware.org/?probe=825d8feb67) | Feb 10, 2020 |
| Gigabyte      | G31M-S2L                    | [130edb3885](https://linux-hardware.org/?probe=130edb3885) | Feb 10, 2020 |
| Gigabyte      | Z77X-D3H                    | [e36ceea7b3](https://linux-hardware.org/?probe=e36ceea7b3) | Feb 10, 2020 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | [4b6ab99884](https://linux-hardware.org/?probe=4b6ab99884) | Feb 09, 2020 |
| Dell          | 08NPPY A00                  | [480ab0830d](https://linux-hardware.org/?probe=480ab0830d) | Feb 08, 2020 |
| MSI           | MS-7360                     | [6d12cb13d4](https://linux-hardware.org/?probe=6d12cb13d4) | Feb 06, 2020 |
| MSI           | B85M-E45                    | [6aac2c165e](https://linux-hardware.org/?probe=6aac2c165e) | Feb 05, 2020 |
| ASUSTek       | PRIME X470-PRO              | [59ac1d5f74](https://linux-hardware.org/?probe=59ac1d5f74) | Feb 03, 2020 |
| ASUSTek       | Z87-A                       | [6cb00762ec](https://linux-hardware.org/?probe=6cb00762ec) | Feb 02, 2020 |
| Dell          | 0HX340 A01                  | [9f87c05c90](https://linux-hardware.org/?probe=9f87c05c90) | Feb 02, 2020 |
| ASUSTek       | P5QPL-AM                    | [521ef4834a](https://linux-hardware.org/?probe=521ef4834a) | Feb 02, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [4befe3bf1d](https://linux-hardware.org/?probe=4befe3bf1d) | Feb 01, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [03eef2b7d3](https://linux-hardware.org/?probe=03eef2b7d3) | Feb 01, 2020 |
| Gigabyte      | PH67A-UD3-B3                | [4007156b8e](https://linux-hardware.org/?probe=4007156b8e) | Jan 31, 2020 |
| ASRock        | N68C-GS FX                  | [576343ca8d](https://linux-hardware.org/?probe=576343ca8d) | Jan 31, 2020 |
| ASRock        | N68C-GS FX                  | [2a1a6c61ee](https://linux-hardware.org/?probe=2a1a6c61ee) | Jan 30, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [94b280c39d](https://linux-hardware.org/?probe=94b280c39d) | Jan 30, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [87a31ff7ed](https://linux-hardware.org/?probe=87a31ff7ed) | Jan 30, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [cd4d0236ad](https://linux-hardware.org/?probe=cd4d0236ad) | Jan 30, 2020 |
| Dell          | 0T1D10 A01                  | [54eeecd7a0](https://linux-hardware.org/?probe=54eeecd7a0) | Jan 29, 2020 |
| Gigabyte      | F2A85X-D3H                  | [cbcbcb0872](https://linux-hardware.org/?probe=cbcbcb0872) | Jan 28, 2020 |
| ASUSTek       | M4A78LT-M-LE                | [e8d18b3fba](https://linux-hardware.org/?probe=e8d18b3fba) | Jan 27, 2020 |
| MSI           | 990FXA-GD65                 | [8548f870a3](https://linux-hardware.org/?probe=8548f870a3) | Jan 26, 2020 |
| ASRock        | Z390 Taichi                 | [ef7ddebc0d](https://linux-hardware.org/?probe=ef7ddebc0d) | Jan 25, 2020 |
| ASUSTek       | P7P55D-E                    | [711e4aa65e](https://linux-hardware.org/?probe=711e4aa65e) | Jan 25, 2020 |
| ASUSTek       | PRIME Z270-A                | [d1613f9b2d](https://linux-hardware.org/?probe=d1613f9b2d) | Jan 24, 2020 |
| MSI           | Z87-G45 GAMING              | [b66cdafdac](https://linux-hardware.org/?probe=b66cdafdac) | Jan 24, 2020 |
| MSI           | Z87-G45 GAMING              | [6bcb6b60ce](https://linux-hardware.org/?probe=6bcb6b60ce) | Jan 24, 2020 |
| ASUSTek       | P8Z77-M PRO                 | [d084db3066](https://linux-hardware.org/?probe=d084db3066) | Jan 23, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [2f657d538c](https://linux-hardware.org/?probe=2f657d538c) | Jan 23, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [159fceeec5](https://linux-hardware.org/?probe=159fceeec5) | Jan 23, 2020 |
| Intel         | ChiefRiver                  | [1ca590a614](https://linux-hardware.org/?probe=1ca590a614) | Jan 22, 2020 |
| Dell          | 0PTTT9 A01                  | [05da5b32f8](https://linux-hardware.org/?probe=05da5b32f8) | Jan 21, 2020 |
| ASRock        | Z390 Taichi                 | [04dbe838b3](https://linux-hardware.org/?probe=04dbe838b3) | Jan 19, 2020 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [27560c373b](https://linux-hardware.org/?probe=27560c373b) | Jan 19, 2020 |
| Gigabyte      | B85M-D3H                    | [069f9ac608](https://linux-hardware.org/?probe=069f9ac608) | Jan 17, 2020 |
| ASUSTek       | P5KPL-AM                    | [67c51708ab](https://linux-hardware.org/?probe=67c51708ab) | Jan 17, 2020 |
| Gigabyte      | B85M-D3H                    | [a0ed0d7f8e](https://linux-hardware.org/?probe=a0ed0d7f8e) | Jan 17, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [0219c1dc48](https://linux-hardware.org/?probe=0219c1dc48) | Jan 14, 2020 |
| ASUSTek       | M3N-HD/HDMI                 | [7f2cba39a5](https://linux-hardware.org/?probe=7f2cba39a5) | Jan 14, 2020 |
| Gigabyte      | B85M-D3H                    | [ac08521cef](https://linux-hardware.org/?probe=ac08521cef) | Jan 14, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dcf27c8d23](https://linux-hardware.org/?probe=dcf27c8d23) | Jan 11, 2020 |
| ASUSTek       | Rampage V EXTREME           | [b487206c43](https://linux-hardware.org/?probe=b487206c43) | Jan 10, 2020 |
| Fujitsu Si... | D2581-A1 S26361-D2581-A1    | [27ad843ce3](https://linux-hardware.org/?probe=27ad843ce3) | Jan 09, 2020 |
| Fujitsu Si... | D2581-A1 S26361-D2581-A1    | [d0268d6a0c](https://linux-hardware.org/?probe=d0268d6a0c) | Jan 09, 2020 |
| Gigabyte      | G31M-S2L                    | [3c21c67618](https://linux-hardware.org/?probe=3c21c67618) | Jan 08, 2020 |
| ASUSTek       | P7P55D-E                    | [795480f461](https://linux-hardware.org/?probe=795480f461) | Jan 06, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [4028f40ac4](https://linux-hardware.org/?probe=4028f40ac4) | Jan 05, 2020 |
| HP            | 2B01                        | [8d9a5cce89](https://linux-hardware.org/?probe=8d9a5cce89) | Jan 04, 2020 |
| HP            | 2B01                        | [651f886232](https://linux-hardware.org/?probe=651f886232) | Jan 03, 2020 |
| HP            | 2B01                        | [032985947c](https://linux-hardware.org/?probe=032985947c) | Jan 02, 2020 |
| ASUSTek       | M2N32-SLI DELUXE            | [b2766b9d53](https://linux-hardware.org/?probe=b2766b9d53) | Jan 02, 2020 |
| Gigabyte      | G31M-ES2L                   | [f9ee03cbed](https://linux-hardware.org/?probe=f9ee03cbed) | Dec 30, 2019 |
| ASUSTek       | P5GC-MX/GBL                 | [26b4b8de78](https://linux-hardware.org/?probe=26b4b8de78) | Dec 30, 2019 |
| Gigabyte      | GA-MA69VM-S2                | [4f7d79e3fc](https://linux-hardware.org/?probe=4f7d79e3fc) | Dec 29, 2019 |
| ASUSTek       | P7P55D-E                    | [e40b76e473](https://linux-hardware.org/?probe=e40b76e473) | Dec 26, 2019 |
| Gigabyte      | F2A85X-D3H                  | [e4c8f4fee7](https://linux-hardware.org/?probe=e4c8f4fee7) | Dec 25, 2019 |
| MSI           | B150M PRO-VDH               | [90b3457f58](https://linux-hardware.org/?probe=90b3457f58) | Dec 21, 2019 |
| Gigabyte      | G31M-S2L                    | [2b3693c8f3](https://linux-hardware.org/?probe=2b3693c8f3) | Dec 20, 2019 |
| ASUSTek       | M2N32-SLI DELUXE            | [064dd1ccbf](https://linux-hardware.org/?probe=064dd1ccbf) | Dec 18, 2019 |
| EVGA          | X58 SLI Classified Tyler... | [0c951a796f](https://linux-hardware.org/?probe=0c951a796f) | Dec 17, 2019 |
| Gigabyte      | Z170-HD3-CF                 | [1081e64e2c](https://linux-hardware.org/?probe=1081e64e2c) | Dec 17, 2019 |
| ASUSTek       | PRIME X470-PRO              | [d9fbc4674d](https://linux-hardware.org/?probe=d9fbc4674d) | Dec 17, 2019 |
| Dell          | 06FW8P A01                  | [82f1fbfa97](https://linux-hardware.org/?probe=82f1fbfa97) | Dec 16, 2019 |
| Gigabyte      | G31M-S2L                    | [8664a00435](https://linux-hardware.org/?probe=8664a00435) | Dec 16, 2019 |
| Lenovo        | ThinkStation E30 7783A61    | [926a3919e3](https://linux-hardware.org/?probe=926a3919e3) | Dec 15, 2019 |
| Lenovo        | ThinkStation E30 7783A61    | [8f7f713748](https://linux-hardware.org/?probe=8f7f713748) | Dec 15, 2019 |
| Lenovo        | ThinkStation E30 7783A61    | [ee2db0e18c](https://linux-hardware.org/?probe=ee2db0e18c) | Dec 15, 2019 |
| ASUSTek       | P5GC-MX/GBL                 | [689cfcef10](https://linux-hardware.org/?probe=689cfcef10) | Dec 13, 2019 |
| ASUSTek       | P5GC-MX/GBL                 | [0522d9276c](https://linux-hardware.org/?probe=0522d9276c) | Dec 13, 2019 |
| Gigabyte      | P31-DS3L                    | [449c4794df](https://linux-hardware.org/?probe=449c4794df) | Dec 11, 2019 |
| Gigabyte      | F2A88XM-DS2                 | [2097c940b1](https://linux-hardware.org/?probe=2097c940b1) | Dec 10, 2019 |
| Gigabyte      | G33M-S2                     | [2febf6828e](https://linux-hardware.org/?probe=2febf6828e) | Dec 07, 2019 |
| Gigabyte      | G33M-S2                     | [e9230bf4e9](https://linux-hardware.org/?probe=e9230bf4e9) | Dec 07, 2019 |
| ASRock        | X399 Taichi                 | [4fabc3ea5d](https://linux-hardware.org/?probe=4fabc3ea5d) | Dec 05, 2019 |
| MSI           | X470 GAMING PLUS            | [326e45e1ef](https://linux-hardware.org/?probe=326e45e1ef) | Dec 04, 2019 |
| ASUSTek       | P5RD2-VM                    | [f7e572bd46](https://linux-hardware.org/?probe=f7e572bd46) | Dec 02, 2019 |
| ASUSTek       | TUF X470-PLUS GAMING        | [73d66bb071](https://linux-hardware.org/?probe=73d66bb071) | Dec 02, 2019 |
| Gigabyte      | GA-MA74GMT-S2               | [6f2de6cd54](https://linux-hardware.org/?probe=6f2de6cd54) | Nov 26, 2019 |
| Gigabyte      | P31-DS3L                    | [4135dd0448](https://linux-hardware.org/?probe=4135dd0448) | Nov 25, 2019 |
| ASRock        | FM2A88X+ Killer             | [009dcd4a93](https://linux-hardware.org/?probe=009dcd4a93) | Nov 21, 2019 |
| ASRock        | FM2A88X+ Killer             | [755723aea3](https://linux-hardware.org/?probe=755723aea3) | Nov 21, 2019 |
| MSI           | B360M PRO-VD 2019-01-24     | [b9128a7474](https://linux-hardware.org/?probe=b9128a7474) | Nov 19, 2019 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [90d4c18bf2](https://linux-hardware.org/?probe=90d4c18bf2) | Nov 19, 2019 |
| MSI           | B360M PRO-VD 2019-01-24     | [c95ecee677](https://linux-hardware.org/?probe=c95ecee677) | Nov 17, 2019 |
| Dell          | 07T4MC A06                  | [8fba67a719](https://linux-hardware.org/?probe=8fba67a719) | Nov 14, 2019 |
| Gigabyte      | 990FXA-UD3                  | [5a0429083b](https://linux-hardware.org/?probe=5a0429083b) | Nov 13, 2019 |
| Gigabyte      | H270-HD3-CF                 | [bd4ac127d9](https://linux-hardware.org/?probe=bd4ac127d9) | Nov 12, 2019 |
| ASUSTek       | PRIME B450M-A               | [012744737a](https://linux-hardware.org/?probe=012744737a) | Nov 11, 2019 |
| MSI           | H81M-P33                    | [3b77cf40ef](https://linux-hardware.org/?probe=3b77cf40ef) | Nov 10, 2019 |
| Gigabyte      | H270-HD3-CF                 | [ad535d2ec9](https://linux-hardware.org/?probe=ad535d2ec9) | Nov 10, 2019 |
| Gigabyte      | H270-HD3-CF                 | [cedefbfa42](https://linux-hardware.org/?probe=cedefbfa42) | Nov 10, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [098f1b8445](https://linux-hardware.org/?probe=098f1b8445) | Nov 07, 2019 |
| Gigabyte      | B450 AORUS PRO-CF           | [cf32e4bed9](https://linux-hardware.org/?probe=cf32e4bed9) | Nov 02, 2019 |
| ASUSTek       | X99-A/USB                   | [99326cbc53](https://linux-hardware.org/?probe=99326cbc53) | Nov 02, 2019 |
| Gigabyte      | Z77X-UD5H                   | [e0f00ff32b](https://linux-hardware.org/?probe=e0f00ff32b) | Oct 30, 2019 |
| MSI           | MS-B9181                    | [5e3f6064b0](https://linux-hardware.org/?probe=5e3f6064b0) | Oct 28, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [76cc90ebc0](https://linux-hardware.org/?probe=76cc90ebc0) | Oct 27, 2019 |
| ASRock        | ConRoe1333-DVI/H            | [950859dd95](https://linux-hardware.org/?probe=950859dd95) | Oct 24, 2019 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [e64f670e53](https://linux-hardware.org/?probe=e64f670e53) | Oct 20, 2019 |
| ASRock        | Z77 Pro4                    | [c712073369](https://linux-hardware.org/?probe=c712073369) | Oct 20, 2019 |
| ASUSTek       | P5G41C-M LX                 | [c5d230b5e0](https://linux-hardware.org/?probe=c5d230b5e0) | Oct 13, 2019 |
| ASUSTek       | M5A97 EVO R2.0              | [b9352ae61b](https://linux-hardware.org/?probe=b9352ae61b) | Oct 12, 2019 |
| Gigabyte      | B85M-D3H                    | [be59695b73](https://linux-hardware.org/?probe=be59695b73) | Oct 12, 2019 |
| HP            | 3031h                       | [b518a96c90](https://linux-hardware.org/?probe=b518a96c90) | Oct 11, 2019 |
| Gigabyte      | Z77-HD4                     | [7671a123ed](https://linux-hardware.org/?probe=7671a123ed) | Oct 10, 2019 |
| Gigabyte      | M1689D                      | [72cd950417](https://linux-hardware.org/?probe=72cd950417) | Oct 10, 2019 |
| ASUSTek       | WS C422 PRO_SE              | [dacec1ae2c](https://linux-hardware.org/?probe=dacec1ae2c) | Oct 10, 2019 |
| Gigabyte      | B85M-D3H                    | [8023b18f9d](https://linux-hardware.org/?probe=8023b18f9d) | Oct 09, 2019 |
| MSI           | B360M PRO-VDH               | [210523a1f4](https://linux-hardware.org/?probe=210523a1f4) | Oct 09, 2019 |
| HP            | 3031h                       | [f111b9318b](https://linux-hardware.org/?probe=f111b9318b) | Oct 09, 2019 |
| ASUSTek       | WS C422 PRO_SE              | [ee954cd456](https://linux-hardware.org/?probe=ee954cd456) | Oct 07, 2019 |
| Intel         | DG31PR AAD97573-301         | [87fa03e3e5](https://linux-hardware.org/?probe=87fa03e3e5) | Oct 07, 2019 |
| ASRock        | Z87 Killer                  | [b758c35ee7](https://linux-hardware.org/?probe=b758c35ee7) | Oct 02, 2019 |
| Intel         | DG31PR AAD97573-301         | [2de2120c3e](https://linux-hardware.org/?probe=2de2120c3e) | Oct 01, 2019 |
| ASRock        | B450M Steel Legend          | [2cb00f1d45](https://linux-hardware.org/?probe=2cb00f1d45) | Sep 27, 2019 |
| ASRock        | B450M Steel Legend          | [6bcde89bf5](https://linux-hardware.org/?probe=6bcde89bf5) | Sep 27, 2019 |
| Dell          | 0R230R A00                  | [01e74e239d](https://linux-hardware.org/?probe=01e74e239d) | Sep 27, 2019 |
| Dell          | 0R230R A00                  | [d42c7a796b](https://linux-hardware.org/?probe=d42c7a796b) | Sep 27, 2019 |
| Gigabyte      | P61-S3                      | [00d47659d2](https://linux-hardware.org/?probe=00d47659d2) | Sep 22, 2019 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [63203f7db7](https://linux-hardware.org/?probe=63203f7db7) | Sep 18, 2019 |
| Dell          | 0GDG8Y A00                  | [d0e099041b](https://linux-hardware.org/?probe=d0e099041b) | Sep 13, 2019 |
| Dell          | 0FH884                      | [6874580091](https://linux-hardware.org/?probe=6874580091) | Sep 12, 2019 |
| Foxconn       | 2AAF                        | [dd389756dc](https://linux-hardware.org/?probe=dd389756dc) | Sep 11, 2019 |
| Gigabyte      | P55-UD3L                    | [b6ab673257](https://linux-hardware.org/?probe=b6ab673257) | Sep 09, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [170f03d4fb](https://linux-hardware.org/?probe=170f03d4fb) | Sep 08, 2019 |
| ASUSTek       | K8N4-E Deluxe               | [dee3d2bdaa](https://linux-hardware.org/?probe=dee3d2bdaa) | Sep 04, 2019 |
| ASUSTek       | P5G41C-M LX                 | [fd71965896](https://linux-hardware.org/?probe=fd71965896) | Sep 02, 2019 |
| Biostar       | A55MD2                      | [988caa3ed1](https://linux-hardware.org/?probe=988caa3ed1) | Sep 02, 2019 |
| ASUSTek       | K8N4-E Deluxe               | [cfaaae942a](https://linux-hardware.org/?probe=cfaaae942a) | Aug 27, 2019 |
| MSI           | B350 TOMAHAWK               | [de397f9040](https://linux-hardware.org/?probe=de397f9040) | Aug 22, 2019 |
| ASUSTek       | P5LD2-VM                    | [e9e46f952b](https://linux-hardware.org/?probe=e9e46f952b) | Aug 15, 2019 |
| Gigabyte      | Z97M-D3H                    | [fd5e835d23](https://linux-hardware.org/?probe=fd5e835d23) | Aug 15, 2019 |
| ABIT          | KN9                         | [28a03d04ef](https://linux-hardware.org/?probe=28a03d04ef) | Aug 11, 2019 |
| MSI           | B75A-G43                    | [97a5fa814d](https://linux-hardware.org/?probe=97a5fa814d) | Aug 10, 2019 |
| ASRock        | EP2C602                     | [1fe7eac8e2](https://linux-hardware.org/?probe=1fe7eac8e2) | Aug 07, 2019 |
| MSI           | B450M MORTAR                | [fe6ee1f7d7](https://linux-hardware.org/?probe=fe6ee1f7d7) | Aug 06, 2019 |
| MSI           | H61MA-E35                   | [4305baddd7](https://linux-hardware.org/?probe=4305baddd7) | Aug 05, 2019 |
| Intel         | DH55HC AAE70933-501         | [5e8b3939d1](https://linux-hardware.org/?probe=5e8b3939d1) | Aug 04, 2019 |
| Intel         | DH55HC AAE70933-501         | [d96cf96c3e](https://linux-hardware.org/?probe=d96cf96c3e) | Aug 04, 2019 |
| MSI           | Z390-A PRO                  | [21f5eef1ab](https://linux-hardware.org/?probe=21f5eef1ab) | Jul 23, 2019 |
| MSI           | X470 GAMING PLUS            | [aa73e69ee4](https://linux-hardware.org/?probe=aa73e69ee4) | Jul 23, 2019 |
| Gigabyte      | EP45C-DS3R                  | [1039518044](https://linux-hardware.org/?probe=1039518044) | Jul 16, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [ca3961ebdb](https://linux-hardware.org/?probe=ca3961ebdb) | Jul 09, 2019 |
| Intel         | DQ45CB AAE30148-206         | [53c6c139da](https://linux-hardware.org/?probe=53c6c139da) | Jul 09, 2019 |
| Gigabyte      | F2A68HM-DS2                 | [77fdde1684](https://linux-hardware.org/?probe=77fdde1684) | Jul 07, 2019 |
| Gigabyte      | 945GCM-S2L                  | [c95bb86669](https://linux-hardware.org/?probe=c95bb86669) | Jul 06, 2019 |
| Lenovo        | ThinkCentre XXXX 89857VG    | [f9823e634a](https://linux-hardware.org/?probe=f9823e634a) | Jul 06, 2019 |
| Gigabyte      | 945GCM-S2L                  | [fa717e3de2](https://linux-hardware.org/?probe=fa717e3de2) | Jul 06, 2019 |
| ASUSTek       | H81M-PLUS                   | [2656a5f4e6](https://linux-hardware.org/?probe=2656a5f4e6) | Jul 05, 2019 |
| Dell          | 0C27VV A02                  | [5ac3726e86](https://linux-hardware.org/?probe=5ac3726e86) | Jul 04, 2019 |
| ASUSTek       | P5G41T-M LX                 | [11ed96b300](https://linux-hardware.org/?probe=11ed96b300) | Jun 30, 2019 |
| ASUSTek       | P5G41T-M LX                 | [79f9859b8f](https://linux-hardware.org/?probe=79f9859b8f) | Jun 30, 2019 |
| Lenovo        | 31900006 STD                | [92a61c8b37](https://linux-hardware.org/?probe=92a61c8b37) | Jun 23, 2019 |
| MSI           | 870S-C45                    | [308392f74d](https://linux-hardware.org/?probe=308392f74d) | Jun 23, 2019 |
| ACTION        | ACTINA SIERRA               | [c58feb4f91](https://linux-hardware.org/?probe=c58feb4f91) | Jun 21, 2019 |
| ASUSTek       | P5L1394                     | [95d420f37f](https://linux-hardware.org/?probe=95d420f37f) | Jun 20, 2019 |
| ASRock        | Z87 Killer                  | [07aaf50a3e](https://linux-hardware.org/?probe=07aaf50a3e) | Jun 19, 2019 |
| ASRock        | Z87 Killer                  | [26275205a1](https://linux-hardware.org/?probe=26275205a1) | Jun 18, 2019 |
| Gigabyte      | M68M-S2P                    | [bbf6b6f632](https://linux-hardware.org/?probe=bbf6b6f632) | Jun 18, 2019 |
| ASRock        | Z87 Killer                  | [ad5008edfc](https://linux-hardware.org/?probe=ad5008edfc) | Jun 17, 2019 |
| Dell          | 0R230R A00                  | [edda2e2fa4](https://linux-hardware.org/?probe=edda2e2fa4) | Jun 15, 2019 |
| Lenovo        | ThinkCentre M71e 3167C67    | [dde51ecd79](https://linux-hardware.org/?probe=dde51ecd79) | Jun 14, 2019 |
| Lenovo        | ThinkCentre M71e 3167C67    | [26cbaff8a8](https://linux-hardware.org/?probe=26cbaff8a8) | Jun 14, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [651bc0a585](https://linux-hardware.org/?probe=651bc0a585) | Jun 11, 2019 |
| Dell          | 042P49 A01                  | [112c1293e1](https://linux-hardware.org/?probe=112c1293e1) | Jun 09, 2019 |
| Biostar       | A55MD2                      | [ccfd99009f](https://linux-hardware.org/?probe=ccfd99009f) | Jun 05, 2019 |
| ASUSTek       | Z87-A                       | [c93b20f11a](https://linux-hardware.org/?probe=c93b20f11a) | Jun 04, 2019 |
| Lenovo        | MAHOBAY NOK                 | [77269244bd](https://linux-hardware.org/?probe=77269244bd) | Jun 02, 2019 |
| Gigabyte      | P31-DS3L                    | [61ff9dc7d0](https://linux-hardware.org/?probe=61ff9dc7d0) | May 30, 2019 |
| Gigabyte      | Z68XP-UD4                   | [16c1886248](https://linux-hardware.org/?probe=16c1886248) | May 30, 2019 |
| MSI           | GF615M-P33                  | [c749d298b7](https://linux-hardware.org/?probe=c749d298b7) | May 30, 2019 |
| Gigabyte      | M1689D                      | [5ea26c8567](https://linux-hardware.org/?probe=5ea26c8567) | May 26, 2019 |
| ASUSTek       | P6T DELUXE V2               | [fb0f30cb65](https://linux-hardware.org/?probe=fb0f30cb65) | May 25, 2019 |
| MSI           | Z270 TOMAHAWK               | [bbf5e4385f](https://linux-hardware.org/?probe=bbf5e4385f) | May 22, 2019 |
| Gigabyte      | Z68XP-UD4                   | [977aa3868a](https://linux-hardware.org/?probe=977aa3868a) | May 22, 2019 |
| Gigabyte      | M1689D                      | [119dcf1a1d](https://linux-hardware.org/?probe=119dcf1a1d) | May 21, 2019 |
| HP            | 1589                        | [a29a428aba](https://linux-hardware.org/?probe=a29a428aba) | May 18, 2019 |
| Dell          | 0F373D A00                  | [0ad11f58b0](https://linux-hardware.org/?probe=0ad11f58b0) | May 17, 2019 |
| Lenovo        | MAHOBAY NOK                 | [0185439cb4](https://linux-hardware.org/?probe=0185439cb4) | May 16, 2019 |
| Gigabyte      | M1689D                      | [183e443b2b](https://linux-hardware.org/?probe=183e443b2b) | May 13, 2019 |
| Dell          | 0DFRFW A01                  | [5626faabd8](https://linux-hardware.org/?probe=5626faabd8) | May 13, 2019 |
| Gigabyte      | G31M-ES2L                   | [6d73a3442b](https://linux-hardware.org/?probe=6d73a3442b) | May 12, 2019 |
| HP            | 158B                        | [d082929a57](https://linux-hardware.org/?probe=d082929a57) | May 08, 2019 |
| Gigabyte      | Z390 GAMING X-CF            | [69f2264d39](https://linux-hardware.org/?probe=69f2264d39) | May 08, 2019 |
| Gigabyte      | P31-DS3L                    | [9b10e09791](https://linux-hardware.org/?probe=9b10e09791) | May 08, 2019 |
| ASUSTek       | 2A73h                       | [beb8ca4ddc](https://linux-hardware.org/?probe=beb8ca4ddc) | May 03, 2019 |
| ASRock        | X470 Taichi                 | [2d89ce8933](https://linux-hardware.org/?probe=2d89ce8933) | May 01, 2019 |
| ASRock        | N68C-GS4 FX                 | [424906a943](https://linux-hardware.org/?probe=424906a943) | Apr 28, 2019 |
| Gigabyte      | B450M DS3H-CF               | [941367d018](https://linux-hardware.org/?probe=941367d018) | Apr 27, 2019 |
| ASRock        | N68C-GS4 FX                 | [e170e231e0](https://linux-hardware.org/?probe=e170e231e0) | Apr 25, 2019 |
| Gigabyte      | B450M DS3H-CF               | [b58b4f3e1e](https://linux-hardware.org/?probe=b58b4f3e1e) | Apr 25, 2019 |
| Gigabyte      | B450M DS3H-CF               | [102b015a34](https://linux-hardware.org/?probe=102b015a34) | Apr 25, 2019 |
| ASUSTek       | P7H55-USB3                  | [207fede762](https://linux-hardware.org/?probe=207fede762) | Apr 23, 2019 |
| ASUSTek       | P7P55D                      | [076e194b08](https://linux-hardware.org/?probe=076e194b08) | Apr 22, 2019 |
| MSI           | 785GT-E63                   | [d6c98da284](https://linux-hardware.org/?probe=d6c98da284) | Apr 22, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [8c36482836](https://linux-hardware.org/?probe=8c36482836) | Apr 21, 2019 |
| MSI           | 785GT-E63                   | [39047a23e9](https://linux-hardware.org/?probe=39047a23e9) | Apr 21, 2019 |
| Lenovo        | MAHOBAY NOK                 | [604fbb2928](https://linux-hardware.org/?probe=604fbb2928) | Apr 21, 2019 |
| Gigabyte      | G41M-ES2L                   | [0335fbd981](https://linux-hardware.org/?probe=0335fbd981) | Apr 18, 2019 |
| ASUSTek       | M5A97 R2.0                  | [5c0aeb1814](https://linux-hardware.org/?probe=5c0aeb1814) | Apr 10, 2019 |
| Gigabyte      | Z270-Gaming K3              | [ae754fab2e](https://linux-hardware.org/?probe=ae754fab2e) | Apr 10, 2019 |
| Dell          | 0TP412                      | [6829098df3](https://linux-hardware.org/?probe=6829098df3) | Apr 10, 2019 |
| ASUSTek       | P7H55-USB3                  | [dd9601c159](https://linux-hardware.org/?probe=dd9601c159) | Apr 09, 2019 |
| ASRock        | N68C-S UCC                  | [77fda1b520](https://linux-hardware.org/?probe=77fda1b520) | Apr 07, 2019 |
| ASRock        | N68C-S UCC                  | [261c564caa](https://linux-hardware.org/?probe=261c564caa) | Apr 07, 2019 |
| ASUSTek       | P8B75-M                     | [e24b9ff7cd](https://linux-hardware.org/?probe=e24b9ff7cd) | Apr 05, 2019 |
| Gigabyte      | X58A-UD3R                   | [32880fbf88](https://linux-hardware.org/?probe=32880fbf88) | Apr 02, 2019 |
| MSI           | B450M PRO-M2                | [c860cd2e3c](https://linux-hardware.org/?probe=c860cd2e3c) | Apr 01, 2019 |
| Gigabyte      | AX370-Gaming K5-CF          | [d4fda27667](https://linux-hardware.org/?probe=d4fda27667) | Mar 31, 2019 |
| Gigabyte      | H81M-DS2                    | [2a7eccf613](https://linux-hardware.org/?probe=2a7eccf613) | Mar 29, 2019 |
| MSI           | B150M PRO-VDH               | [234631d29f](https://linux-hardware.org/?probe=234631d29f) | Mar 26, 2019 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [51a3b7bcf7](https://linux-hardware.org/?probe=51a3b7bcf7) | Mar 25, 2019 |
| Gigabyte      | P85-D3                      | [dc0931ecd2](https://linux-hardware.org/?probe=dc0931ecd2) | Mar 22, 2019 |
| Gigabyte      | P85-D3                      | [8519f221a7](https://linux-hardware.org/?probe=8519f221a7) | Mar 22, 2019 |
| Gigabyte      | Z97M-D3H                    | [1087f10dcd](https://linux-hardware.org/?probe=1087f10dcd) | Mar 22, 2019 |
| MSI           | K9N6PGM2-V2                 | [714849d3cf](https://linux-hardware.org/?probe=714849d3cf) | Mar 20, 2019 |
| ASUSTek       | B150 PRO GAMING/AURA        | [34098b6492](https://linux-hardware.org/?probe=34098b6492) | Mar 20, 2019 |
| ASRock        | G41M-VS3                    | [8c1597598d](https://linux-hardware.org/?probe=8c1597598d) | Mar 18, 2019 |
| Gigabyte      | P35-DS3L                    | [4ddffd5967](https://linux-hardware.org/?probe=4ddffd5967) | Mar 17, 2019 |
| ASRock        | FM2A88X Extreme6+           | [b37596b758](https://linux-hardware.org/?probe=b37596b758) | Mar 17, 2019 |
| ASUSTek       | Z87-A                       | [2896ee87af](https://linux-hardware.org/?probe=2896ee87af) | Mar 16, 2019 |
| ASRock        | P67 Pro3                    | [d03e4ae8dc](https://linux-hardware.org/?probe=d03e4ae8dc) | Mar 13, 2019 |
| MSI           | G41M-P23                    | [deabfe7945](https://linux-hardware.org/?probe=deabfe7945) | Mar 12, 2019 |
| MSI           | G41M-P23                    | [bb8d550f36](https://linux-hardware.org/?probe=bb8d550f36) | Mar 12, 2019 |
| Gigabyte      | GA-MA770T-UD3P              | [92182de640](https://linux-hardware.org/?probe=92182de640) | Mar 11, 2019 |
| Foxconn       | 2ABF                        | [16cf5f0b96](https://linux-hardware.org/?probe=16cf5f0b96) | Feb 26, 2019 |
| Dell          | 0DT031 A00                  | [dabc6bc882](https://linux-hardware.org/?probe=dabc6bc882) | Feb 18, 2019 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [08338fd621](https://linux-hardware.org/?probe=08338fd621) | Feb 17, 2019 |
| ASUSTek       | M5A97 EVO R2.0              | [f3a6e07a5e](https://linux-hardware.org/?probe=f3a6e07a5e) | Feb 16, 2019 |
| ASRock        | B360M Pro4                  | [9cb261390b](https://linux-hardware.org/?probe=9cb261390b) | Feb 12, 2019 |
| Gigabyte      | P61-S3                      | [7612974eb9](https://linux-hardware.org/?probe=7612974eb9) | Feb 09, 2019 |
| Dell          | 0FH884                      | [50263811c9](https://linux-hardware.org/?probe=50263811c9) | Feb 09, 2019 |
| Gigabyte      | Z97-HD3                     | [e4d05d3f5c](https://linux-hardware.org/?probe=e4d05d3f5c) | Feb 05, 2019 |
| ASUSTek       | F1A55-M LE                  | [c152daf649](https://linux-hardware.org/?probe=c152daf649) | Feb 04, 2019 |
| Gigabyte      | M61P-S3                     | [08eab4a3c5](https://linux-hardware.org/?probe=08eab4a3c5) | Feb 01, 2019 |
| Gigabyte      | G31M-S2L                    | [4e06379130](https://linux-hardware.org/?probe=4e06379130) | Jan 24, 2019 |
| Gigabyte      | Z77X-UD5H                   | [2de85a1eaf](https://linux-hardware.org/?probe=2de85a1eaf) | Jan 23, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [9aa70c74b3](https://linux-hardware.org/?probe=9aa70c74b3) | Jan 20, 2019 |
| ASUSTek       | M5A97 EVO R2.0              | [b46ccd2e25](https://linux-hardware.org/?probe=b46ccd2e25) | Jan 18, 2019 |
| Gigabyte      | EP45C-DS3R                  | [5226fb3b62](https://linux-hardware.org/?probe=5226fb3b62) | Jan 16, 2019 |
| Intel         | DG31PR AAD97573-301         | [ccd2031e68](https://linux-hardware.org/?probe=ccd2031e68) | Jan 08, 2019 |
| ASUSTek       | Rampage V EXTREME           | [572227f219](https://linux-hardware.org/?probe=572227f219) | Jan 08, 2019 |
| Intel         | DG31PR AAD97573-301         | [84c3697acf](https://linux-hardware.org/?probe=84c3697acf) | Jan 06, 2019 |
| ASUSTek       | Rampage V EXTREME           | [65e82e5298](https://linux-hardware.org/?probe=65e82e5298) | Jan 06, 2019 |
| Intel         | ChiefRiver                  | [4a667900e8](https://linux-hardware.org/?probe=4a667900e8) | Jan 06, 2019 |
| MSI           | MS-7327                     | [a3b1cea686](https://linux-hardware.org/?probe=a3b1cea686) | Jan 03, 2019 |
| Intel         | ChiefRiver                  | [0aab6a1df7](https://linux-hardware.org/?probe=0aab6a1df7) | Jan 01, 2019 |
| Dell          | 03NVJ6 A02                  | [a845c43ac6](https://linux-hardware.org/?probe=a845c43ac6) | Dec 28, 2018 |
| MSI           | B350M MORTAR ARCTIC         | [f90c616415](https://linux-hardware.org/?probe=f90c616415) | Dec 28, 2018 |
| MSI           | P55-GD65                    | [574f52d952](https://linux-hardware.org/?probe=574f52d952) | Dec 12, 2018 |
| ASUSTek       | P8H77-M                     | [6e296b15a6](https://linux-hardware.org/?probe=6e296b15a6) | Dec 10, 2018 |
| MSI           | Z87-G45 GAMING              | [724db4ba95](https://linux-hardware.org/?probe=724db4ba95) | Dec 08, 2018 |
| HP            | 3647h                       | [c95d48db93](https://linux-hardware.org/?probe=c95d48db93) | Dec 06, 2018 |
| ASRock        | B75M                        | [787d7e2126](https://linux-hardware.org/?probe=787d7e2126) | Dec 05, 2018 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [57b1bcac00](https://linux-hardware.org/?probe=57b1bcac00) | Dec 01, 2018 |
| Gigabyte      | P67X-UD3-B3                 | [4c459b6411](https://linux-hardware.org/?probe=4c459b6411) | Nov 29, 2018 |
| OPTIMUS       | VT82C694T                   | [55ec1147ba](https://linux-hardware.org/?probe=55ec1147ba) | Nov 26, 2018 |
| Lenovo        | MAHOBAY NOK                 | [b7e5c7cacd](https://linux-hardware.org/?probe=b7e5c7cacd) | Nov 22, 2018 |
| Gigabyte      | H61M-S1                     | [ccabb3422c](https://linux-hardware.org/?probe=ccabb3422c) | Nov 14, 2018 |
| Gigabyte      | H61M-S1                     | [83f674bdff](https://linux-hardware.org/?probe=83f674bdff) | Nov 14, 2018 |
| Lenovo        | MAHOBAY NOK                 | [98e56b1b1b](https://linux-hardware.org/?probe=98e56b1b1b) | Nov 13, 2018 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [7abaa62352](https://linux-hardware.org/?probe=7abaa62352) | Nov 12, 2018 |
| ASUSTek       | P8Z68-V GEN3                | [93495fbb9b](https://linux-hardware.org/?probe=93495fbb9b) | Nov 11, 2018 |
| HP            | 0A68h                       | [e9cb4e2169](https://linux-hardware.org/?probe=e9cb4e2169) | Nov 05, 2018 |
| ASUSTek       | Rampage II GENE             | [3d29671592](https://linux-hardware.org/?probe=3d29671592) | Nov 03, 2018 |
| Gigabyte      | EP45-UD3R                   | [ebd8a5801d](https://linux-hardware.org/?probe=ebd8a5801d) | Nov 02, 2018 |
| Gigabyte      | EP45-UD3R                   | [83e30730ba](https://linux-hardware.org/?probe=83e30730ba) | Oct 30, 2018 |
| MSI           | B350M MORTAR ARCTIC         | [78d3bb1bba](https://linux-hardware.org/?probe=78d3bb1bba) | Oct 30, 2018 |
| ASUSTek       | P8P67                       | [203bffa98f](https://linux-hardware.org/?probe=203bffa98f) | Oct 24, 2018 |
| ASUSTek       | P7P55D EVO                  | [8cf76a4ccf](https://linux-hardware.org/?probe=8cf76a4ccf) | Oct 23, 2018 |
| Gigabyte      | GA-E350N-USB3               | [112082369c](https://linux-hardware.org/?probe=112082369c) | Sep 27, 2018 |
| MSI           | MS-7350                     | [92728c6648](https://linux-hardware.org/?probe=92728c6648) | Sep 03, 2018 |
| HP            | 1497                        | [0b516c586c](https://linux-hardware.org/?probe=0b516c586c) | Aug 21, 2018 |
| HP            | 1497                        | [1134722652](https://linux-hardware.org/?probe=1134722652) | Aug 21, 2018 |
| Gigabyte      | EP31-DS3L                   | [d69b0fb65c](https://linux-hardware.org/?probe=d69b0fb65c) | Aug 19, 2018 |
| Gigabyte      | GA-MA785GM-US2H             | [3d552f4288](https://linux-hardware.org/?probe=3d552f4288) | Aug 18, 2018 |
| Gigabyte      | P55M-UD2                    | [f59f5d1d80](https://linux-hardware.org/?probe=f59f5d1d80) | Aug 15, 2018 |
| MSI           | H81M-E34                    | [05a5d6db67](https://linux-hardware.org/?probe=05a5d6db67) | Aug 09, 2018 |
| ASUSTek       | 2A73h                       | [6b3f83d42d](https://linux-hardware.org/?probe=6b3f83d42d) | Jul 22, 2018 |
| Gigabyte      | AB350-Gaming-CF             | [f920ce8fe1](https://linux-hardware.org/?probe=f920ce8fe1) | Jul 15, 2018 |
| MSI           | B350M MORTAR ARCTIC         | [a25ed9c8bd](https://linux-hardware.org/?probe=a25ed9c8bd) | Jul 12, 2018 |
| Gigabyte      | EP31-DS3L                   | [37d3303805](https://linux-hardware.org/?probe=37d3303805) | Jul 04, 2018 |
| ASUSTek       | P8Z77-V PRO                 | [ca4df9b969](https://linux-hardware.org/?probe=ca4df9b969) | Jun 30, 2018 |
| ASUSTek       | P8Z77-V PRO                 | [1af1655b40](https://linux-hardware.org/?probe=1af1655b40) | Jun 29, 2018 |
| ASRock        | Z97 Extreme4                | [f599eb6750](https://linux-hardware.org/?probe=f599eb6750) | Jun 28, 2018 |
| Gigabyte      | GA-MA785GM-US2H             | [01a2ae6ed6](https://linux-hardware.org/?probe=01a2ae6ed6) | Jun 24, 2018 |
| Gigabyte      | P67X-UD3-B3                 | [5ff6d0fcc0](https://linux-hardware.org/?probe=5ff6d0fcc0) | Jun 21, 2018 |
| Pegatron      | 2A73h                       | [f54ceaa474](https://linux-hardware.org/?probe=f54ceaa474) | Jun 20, 2018 |
| HP            | 1905                        | [51f73cb55b](https://linux-hardware.org/?probe=51f73cb55b) | Jun 07, 2018 |
| HP            | 1905                        | [8e1b5fd11d](https://linux-hardware.org/?probe=8e1b5fd11d) | Jun 07, 2018 |
| HP            | 3033h                       | [628f536295](https://linux-hardware.org/?probe=628f536295) | Jun 04, 2018 |
| Dell          | 0U1325                      | [5603cb43b5](https://linux-hardware.org/?probe=5603cb43b5) | May 29, 2018 |
| HP            | 2B05                        | [5fef16fa7e](https://linux-hardware.org/?probe=5fef16fa7e) | May 27, 2018 |
| ASRock        | AM1B-ITX                    | [d24680ba88](https://linux-hardware.org/?probe=d24680ba88) | May 22, 2018 |
| Gigabyte      | M59SLI-S5                   | [a61b9f2144](https://linux-hardware.org/?probe=a61b9f2144) | May 21, 2018 |
| ASUSTek       | P8Z77-V PRO                 | [eee61ef2d9](https://linux-hardware.org/?probe=eee61ef2d9) | May 19, 2018 |
| ASUSTek       | P8Z77-V PRO                 | [aa79c6d3af](https://linux-hardware.org/?probe=aa79c6d3af) | May 09, 2018 |
| Gigabyte      | M61P-S3                     | [dbb434a1c4](https://linux-hardware.org/?probe=dbb434a1c4) | Apr 28, 2018 |
| ASRock        | FM2A68M-DG3+                | [85ff8c6337](https://linux-hardware.org/?probe=85ff8c6337) | Apr 21, 2018 |
| HP            | 3647h                       | [b3c52d0d45](https://linux-hardware.org/?probe=b3c52d0d45) | Mar 24, 2018 |
| Gigabyte      | AB350-Gaming-CF             | [ead8d3c927](https://linux-hardware.org/?probe=ead8d3c927) | Mar 21, 2018 |
| Gigabyte      | GA-E350N-USB3               | [92a07a4975](https://linux-hardware.org/?probe=92a07a4975) | Mar 21, 2018 |
| ASUSTek       | P5GC-MX/NTT/SI              | [53d57ef2b3](https://linux-hardware.org/?probe=53d57ef2b3) | Mar 21, 2018 |
| Gigabyte      | GA-E350N-USB3               | [44d3cc27a2](https://linux-hardware.org/?probe=44d3cc27a2) | Mar 20, 2018 |
| ASUSTek       | P5GC-MX/NTT/SI              | [d41b43489e](https://linux-hardware.org/?probe=d41b43489e) | Mar 20, 2018 |
| Gigabyte      | GA-E350N-USB3               | [6ca28591ff](https://linux-hardware.org/?probe=6ca28591ff) | Mar 18, 2018 |
| Dell          | 0XR1GT A00                  | [add56ad914](https://linux-hardware.org/?probe=add56ad914) | Mar 09, 2018 |
| ASUSTek       | A8N-VM CSM                  | [ab7b26b325](https://linux-hardware.org/?probe=ab7b26b325) | Feb 22, 2018 |
| Gigabyte      | B85M-D3H-A                  | [6b2eb9bf4c](https://linux-hardware.org/?probe=6b2eb9bf4c) | Feb 12, 2018 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [3302c0e3b0](https://linux-hardware.org/?probe=3302c0e3b0) | Feb 04, 2018 |
| ASRock        | G41M-VS3                    | [a71103c460](https://linux-hardware.org/?probe=a71103c460) | Feb 02, 2018 |
| ASUSTek       | M5A78L-M LX3                | [f4821b4e35](https://linux-hardware.org/?probe=f4821b4e35) | Feb 01, 2018 |
| MSI           | MS-7369                     | [5c16632da8](https://linux-hardware.org/?probe=5c16632da8) | Feb 01, 2018 |
| ASUSTek       | M5A78L-M LX3                | [7911abc2c0](https://linux-hardware.org/?probe=7911abc2c0) | Jan 30, 2018 |
| Gigabyte      | M1689D                      | [fb0b2bdd59](https://linux-hardware.org/?probe=fb0b2bdd59) | Jan 29, 2018 |
| Gigabyte      | M1689D                      | [4965cb77bf](https://linux-hardware.org/?probe=4965cb77bf) | Jan 25, 2018 |
| ASUSTek       | M5A97                       | [bafd5362b1](https://linux-hardware.org/?probe=bafd5362b1) | Jan 24, 2018 |
| Gigabyte      | EP31-DS3L                   | [71fd8e09b9](https://linux-hardware.org/?probe=71fd8e09b9) | Jan 19, 2018 |
| ASRock        | A88M-G                      | [006cc8353f](https://linux-hardware.org/?probe=006cc8353f) | Jan 19, 2018 |
| Gigabyte      | EP31-DS3L                   | [8fff86ab2c](https://linux-hardware.org/?probe=8fff86ab2c) | Jan 07, 2018 |
| Fujitsu Si... | D1607 S26361-D1607          | [d2e8e4ca3d](https://linux-hardware.org/?probe=d2e8e4ca3d) | Dec 31, 2017 |
| Gigabyte      | GA-970A-UD3                 | [87fe77e917](https://linux-hardware.org/?probe=87fe77e917) | Dec 31, 2017 |
| HP            | 0AA0h                       | [397da3fe27](https://linux-hardware.org/?probe=397da3fe27) | Dec 28, 2017 |
| Acer          | TDPS05                      | [55f672b92c](https://linux-hardware.org/?probe=55f672b92c) | Dec 22, 2017 |
| Gigabyte      | M59SLI-S5                   | [58df7e0cda](https://linux-hardware.org/?probe=58df7e0cda) | Dec 18, 2017 |
| ASRock        | FM2A88X Extreme6+           | [af939ebba6](https://linux-hardware.org/?probe=af939ebba6) | Dec 15, 2017 |
| ASRock        | FM2A88X Extreme6+           | [f6eb63516e](https://linux-hardware.org/?probe=f6eb63516e) | Dec 15, 2017 |
| HP            | 0AA0h                       | [080b517174](https://linux-hardware.org/?probe=080b517174) | Dec 14, 2017 |
| Dell          | 0200DY A01                  | [6251298cd5](https://linux-hardware.org/?probe=6251298cd5) | Dec 10, 2017 |
| ASUSTek       | M5A97 EVO R2.0              | [dfd0fe4cbb](https://linux-hardware.org/?probe=dfd0fe4cbb) | Dec 08, 2017 |
| ASUSTek       | Z170-A                      | [66dd24e328](https://linux-hardware.org/?probe=66dd24e328) | Dec 06, 2017 |
| Intel         | SHARKBAY                    | [01fe7c5779](https://linux-hardware.org/?probe=01fe7c5779) | Dec 06, 2017 |
| Gigabyte      | B85M-D3H-A                  | [f9fd23b19b](https://linux-hardware.org/?probe=f9fd23b19b) | Dec 03, 2017 |
| Gigabyte      | G31M-S2L                    | [e945000144](https://linux-hardware.org/?probe=e945000144) | Nov 29, 2017 |
| HP            | 2B05                        | [86e34f7a6b](https://linux-hardware.org/?probe=86e34f7a6b) | Nov 17, 2017 |
| Medion        | MS-7857                     | [a5661ee7e6](https://linux-hardware.org/?probe=a5661ee7e6) | Nov 17, 2017 |
| Gigabyte      | 965GM-S2                    | [989bcbe469](https://linux-hardware.org/?probe=989bcbe469) | Oct 22, 2017 |
| Gigabyte      | 965GM-S2                    | [4eb4ae5af1](https://linux-hardware.org/?probe=4eb4ae5af1) | Oct 21, 2017 |
| ASUSTek       | M5A97 EVO R2.0              | [55b0325b6f](https://linux-hardware.org/?probe=55b0325b6f) | Oct 07, 2017 |
| ASRock        | G41C-GS                     | [379a12cb66](https://linux-hardware.org/?probe=379a12cb66) | Oct 03, 2017 |
| ASUSTek       | A8V-MX                      | [c58ecafe7e](https://linux-hardware.org/?probe=c58ecafe7e) | Sep 11, 2017 |
| ASUSTek       | P5Q-EM                      | [19330d1a41](https://linux-hardware.org/?probe=19330d1a41) | Sep 10, 2017 |
| Gigabyte      | G33M-DS2R                   | [2665f02584](https://linux-hardware.org/?probe=2665f02584) | Sep 03, 2017 |
| Gigabyte      | 970A-DS3P                   | [9d5d27128b](https://linux-hardware.org/?probe=9d5d27128b) | Aug 22, 2017 |
| Gigabyte      | GA-E350N-USB3               | [5a79b2a200](https://linux-hardware.org/?probe=5a79b2a200) | Aug 20, 2017 |
| Gigabyte      | B85M-D3H-A                  | [10d71bf804](https://linux-hardware.org/?probe=10d71bf804) | Aug 19, 2017 |
| MSI           | P35 Platinum                | [fd08bd3a81](https://linux-hardware.org/?probe=fd08bd3a81) | Aug 16, 2017 |
| Dell          | 09KPNV A01                  | [4213886ca6](https://linux-hardware.org/?probe=4213886ca6) | Aug 04, 2017 |
| Gigabyte      | GA-MA785GM-US2H             | [8957081c99](https://linux-hardware.org/?probe=8957081c99) | Aug 03, 2017 |
| MSI           | B85-G43                     | [fcc198d63d](https://linux-hardware.org/?probe=fcc198d63d) | Jul 27, 2017 |
| Gigabyte      | GA-MA785GM-US2H             | [c223e28ed8](https://linux-hardware.org/?probe=c223e28ed8) | Jul 21, 2017 |
| ASRock        | 960GM-GS3 FX                | [43ce4b4850](https://linux-hardware.org/?probe=43ce4b4850) | Jul 15, 2017 |
| ASUSTek       | P8H61-MX R2.0               | [dd88ae9c46](https://linux-hardware.org/?probe=dd88ae9c46) | Jul 13, 2017 |
| Gigabyte      | M720-US3                    | [87624c4b7c](https://linux-hardware.org/?probe=87624c4b7c) | Jul 11, 2017 |
| HP            | 3646h                       | [aee911aa78](https://linux-hardware.org/?probe=aee911aa78) | Jul 09, 2017 |
| Gigabyte      | GA-880GM-D2H                | [2d46c47e9b](https://linux-hardware.org/?probe=2d46c47e9b) | Jun 30, 2017 |
| Gigabyte      | M59SLI-S5                   | [66a9ec9c2f](https://linux-hardware.org/?probe=66a9ec9c2f) | Jun 21, 2017 |
| ASUSTek       | P5RD2-VM                    | [563829cd41](https://linux-hardware.org/?probe=563829cd41) | Jun 19, 2017 |
| MSI           | B350M MORTAR ARCTIC         | [072ae0845d](https://linux-hardware.org/?probe=072ae0845d) | Jun 17, 2017 |
| MSI           | MS-7369                     | [bf11a92a7c](https://linux-hardware.org/?probe=bf11a92a7c) | Jun 13, 2017 |
| ASUSTek       | M4A78 PRO                   | [409f834b7e](https://linux-hardware.org/?probe=409f834b7e) | Jun 10, 2017 |
| MSI           | MS-7369                     | [a2f2d9141a](https://linux-hardware.org/?probe=a2f2d9141a) | Jun 07, 2017 |
| MSI           | MS-7369                     | [484c26a275](https://linux-hardware.org/?probe=484c26a275) | Jun 04, 2017 |
| ASUSTek       | P5Q-EM                      | [785dd593f5](https://linux-hardware.org/?probe=785dd593f5) | May 28, 2017 |
| ASRock        | G41C-GS                     | [9db614a74d](https://linux-hardware.org/?probe=9db614a74d) | May 25, 2017 |
| Gigabyte      | M61PME-S2                   | [9a6b7f3201](https://linux-hardware.org/?probe=9a6b7f3201) | May 25, 2017 |
| Gigabyte      | M61PME-S2                   | [fa5d52de80](https://linux-hardware.org/?probe=fa5d52de80) | May 23, 2017 |
| Gigabyte      | GA-990XA-UD3                | [856e392cdd](https://linux-hardware.org/?probe=856e392cdd) | May 22, 2017 |
| ASUSTek       | P5B                         | [f6871debe4](https://linux-hardware.org/?probe=f6871debe4) | May 21, 2017 |
| Dell          | 0200DY A01                  | [3f5c9524f1](https://linux-hardware.org/?probe=3f5c9524f1) | May 16, 2017 |
| ASUSTek       | P5Q-PRO                     | [4eec4c16ff](https://linux-hardware.org/?probe=4eec4c16ff) | May 15, 2017 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [37bab08507](https://linux-hardware.org/?probe=37bab08507) | May 07, 2017 |
| Gigabyte      | M52LT-D3                    | [aa5a9ec459](https://linux-hardware.org/?probe=aa5a9ec459) | May 02, 2017 |
| Gigabyte      | M52LT-D3                    | [ad0497dbed](https://linux-hardware.org/?probe=ad0497dbed) | Apr 30, 2017 |
| ASUSTek       | M4A78-E                     | [22731b0ddb](https://linux-hardware.org/?probe=22731b0ddb) | Apr 26, 2017 |
| HP            | 2B05                        | [c7d8167dfa](https://linux-hardware.org/?probe=c7d8167dfa) | Apr 26, 2017 |
| Gigabyte      | 8IPE1000P3                  | [11049388ec](https://linux-hardware.org/?probe=11049388ec) | Apr 20, 2017 |
| ASUSTek       | P5RD2-VM                    | [4fa8c1dd47](https://linux-hardware.org/?probe=4fa8c1dd47) | Apr 09, 2017 |
| ASUSTek       | P9X79                       | [3c898693e3](https://linux-hardware.org/?probe=3c898693e3) | Apr 09, 2017 |
| Gigabyte      | 970A-UD3P                   | [6baddb92db](https://linux-hardware.org/?probe=6baddb92db) | Apr 08, 2017 |
| Gigabyte      | P31-DS3L                    | [52c673c782](https://linux-hardware.org/?probe=52c673c782) | Mar 22, 2017 |
| ABIT          | LG-95C                      | [af0d08e9b1](https://linux-hardware.org/?probe=af0d08e9b1) | Mar 21, 2017 |
| Dell          | 03NVJ6 A03                  | [9abad08d6e](https://linux-hardware.org/?probe=9abad08d6e) | Mar 21, 2017 |
| Gigabyte      | M59SLI-S5                   | [b05b1e933f](https://linux-hardware.org/?probe=b05b1e933f) | Mar 18, 2017 |
| ASUSTek       | M2N-E                       | [cb0eca0e69](https://linux-hardware.org/?probe=cb0eca0e69) | Mar 12, 2017 |
| ASUSTek       | M2N-E                       | [42a0efeb3d](https://linux-hardware.org/?probe=42a0efeb3d) | Mar 10, 2017 |
| Gigabyte      | M52LT-D3                    | [4f47b42b4a](https://linux-hardware.org/?probe=4f47b42b4a) | Mar 06, 2017 |
| Gigabyte      | M52LT-D3                    | [c447df364b](https://linux-hardware.org/?probe=c447df364b) | Mar 06, 2017 |
| Dell          | 09KPNV A01                  | [5c42874ea0](https://linux-hardware.org/?probe=5c42874ea0) | Feb 20, 2017 |
| ASUSTek       | M2N-E                       | [72bad117af](https://linux-hardware.org/?probe=72bad117af) | Feb 17, 2017 |
| ASUSTek       | P5K-E                       | [0739cabb5d](https://linux-hardware.org/?probe=0739cabb5d) | Feb 16, 2017 |
| MSI           | Z97 PC Mate                 | [bfc712ce29](https://linux-hardware.org/?probe=bfc712ce29) | Feb 12, 2017 |
| Gigabyte      | P85-D3                      | [224211f189](https://linux-hardware.org/?probe=224211f189) | Jan 18, 2017 |
| Gigabyte      | P85-D3                      | [4cdee41148](https://linux-hardware.org/?probe=4cdee41148) | Jan 17, 2017 |
| ASUSTek       | M4A78LT-M-LE                | [eb6352777a](https://linux-hardware.org/?probe=eb6352777a) | Jan 16, 2017 |
| ASUSTek       | Z170-A                      | [1539a69d00](https://linux-hardware.org/?probe=1539a69d00) | Jan 15, 2017 |
| ASUSTek       | Z170-A                      | [c507f4b6ae](https://linux-hardware.org/?probe=c507f4b6ae) | Jan 15, 2017 |
| Gigabyte      | 970A-UD3P                   | [1dc633e68b](https://linux-hardware.org/?probe=1dc633e68b) | Jan 13, 2017 |
| Gigabyte      | GA-970A-UD3                 | [f471d47889](https://linux-hardware.org/?probe=f471d47889) | Jan 07, 2017 |
| ASUSTek       | M4A78-E                     | [fda7fbdbef](https://linux-hardware.org/?probe=fda7fbdbef) | Dec 20, 2016 |
| ASRock        | AM2NF6G-VSTA                | [50d8c5da3a](https://linux-hardware.org/?probe=50d8c5da3a) | Dec 20, 2016 |
| Gigabyte      | EP43-DS3L                   | [2c31c57563](https://linux-hardware.org/?probe=2c31c57563) | Dec 16, 2016 |
| ASRock        | G41M-VS3                    | [2373813a72](https://linux-hardware.org/?probe=2373813a72) | Dec 02, 2016 |
| ASUSTek       | M2N-MX                      | [e4d0d751b8](https://linux-hardware.org/?probe=e4d0d751b8) | Nov 20, 2016 |
| Gigabyte      | 945GZM-S2                   | [af1e0a0d7b](https://linux-hardware.org/?probe=af1e0a0d7b) | Nov 12, 2016 |
| ASUSTek       | P5Q-EM                      | [8823a9193a](https://linux-hardware.org/?probe=8823a9193a) | Nov 10, 2016 |
| Dell          | 0YKH50 A01                  | [006a6d6472](https://linux-hardware.org/?probe=006a6d6472) | Nov 04, 2016 |
| Dell          | 0YKH50 A01                  | [c3e82b4783](https://linux-hardware.org/?probe=c3e82b4783) | Oct 29, 2016 |
| Gigabyte      | 970A-UD3P                   | [a82ce44539](https://linux-hardware.org/?probe=a82ce44539) | Oct 25, 2016 |
| Gigabyte      | 970A-UD3P                   | [158beb8157](https://linux-hardware.org/?probe=158beb8157) | Oct 25, 2016 |
| MSI           | 770-G45                     | [2513d9d968](https://linux-hardware.org/?probe=2513d9d968) | Feb 11, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 214      | 13.65%  |
| OpenMandriva 4.2             | 126      | 8.04%   |
| Ubuntu 18.04                 | 109      | 6.95%   |
| OpenMandriva 4.3             | 78       | 4.97%   |
| ROSA R10                     | 47       | 3%      |
| Arch Rolling                 | 42       | 2.68%   |
| ROSA R11                     | 39       | 2.49%   |
| ROSA R9                      | 31       | 1.98%   |
| ROSA R11.1                   | 26       | 1.66%   |
| Linux Mint 20.1              | 24       | 1.53%   |
| Arch                         | 24       | 1.53%   |
| Manjaro                      | 23       | 1.47%   |
| Debian 11                    | 22       | 1.4%    |
| Linux Mint 20                | 21       | 1.34%   |
| KDE neon 20.04               | 21       | 1.34%   |
| Zorin 16                     | 20       | 1.28%   |
| Ubuntu 20.10                 | 20       | 1.28%   |
| Linux Mint 20.3              | 20       | 1.28%   |
| ROSA R8.1                    | 19       | 1.21%   |
| Ubuntu 19.10                 | 18       | 1.15%   |
| Ubuntu 22.04                 | 17       | 1.08%   |
| Ubuntu 19.04                 | 17       | 1.08%   |
| ROSA R8                      | 17       | 1.08%   |
| Linux Mint 20.2              | 17       | 1.08%   |
| Fedora 35                    | 17       | 1.08%   |
| Fedora 34                    | 17       | 1.08%   |
| Ubuntu 21.04                 | 16       | 1.02%   |
| Ubuntu 21.10                 | 15       | 0.96%   |
| Pop!_OS 20.04                | 15       | 0.96%   |
| Linux Mint 19.3              | 15       | 0.96%   |
| Kubuntu 20.04                | 15       | 0.96%   |
| Fedora 36                    | 14       | 0.89%   |
| Fedora 33                    | 14       | 0.89%   |
| Gentoo 2.7                   | 13       | 0.83%   |
| Fedora 31                    | 13       | 0.83%   |
| Debian 10                    | 13       | 0.83%   |
| Xubuntu 20.04                | 12       | 0.77%   |
| Fedora 32                    | 12       | 0.77%   |
| Pop!_OS 21.10                | 11       | 0.7%    |
| BlackPanther 18.1            | 11       | 0.7%    |
| Ubuntu 18.10                 | 10       | 0.64%   |
| OpenMandriva 4.50            | 10       | 0.64%   |
| Pop!_OS 21.04                | 9        | 0.57%   |
| Pop!_OS 20.10                | 9        | 0.57%   |
| Zorin 15                     | 8        | 0.51%   |
| Linux Mint 19.2              | 8        | 0.51%   |
| Linux Mint 19.1              | 8        | 0.51%   |
| Gentoo 2.8                   | 8        | 0.51%   |
| ArcoLinux Rolling            | 8        | 0.51%   |
| openSUSE Tumbleweed-XXXXXXXX | 7        | 0.45%   |
| EndeavourOS Rolling          | 7        | 0.45%   |
| ROSA 12.2                    | 6        | 0.38%   |
| Kubuntu 22.04                | 6        | 0.38%   |
| Debian Testing               | 6        | 0.38%   |
| CentOS 8                     | 6        | 0.38%   |
| Ubuntu 16.04                 | 5        | 0.32%   |
| Manjaro 21.0.7               | 5        | 0.32%   |
| Manjaro 20.1                 | 5        | 0.32%   |
| LMDE 4                       | 5        | 0.32%   |
| Xubuntu 18.04                | 4        | 0.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 415      | 28.82%  |
| OpenMandriva     | 217      | 15.07%  |
| ROSA             | 146      | 10.14%  |
| Linux Mint       | 111      | 7.71%   |
| Fedora           | 76       | 5.28%   |
| Manjaro          | 65       | 4.51%   |
| Arch             | 65       | 4.51%   |
| Pop!_OS          | 44       | 3.06%   |
| Debian           | 43       | 2.99%   |
| Kubuntu          | 31       | 2.15%   |
| Zorin            | 29       | 2.01%   |
| KDE neon         | 22       | 1.53%   |
| Xubuntu          | 19       | 1.32%   |
| Gentoo           | 18       | 1.25%   |
| openSUSE         | 11       | 0.76%   |
| Endless          | 11       | 0.76%   |
| BlackPanther     | 11       | 0.76%   |
| EndeavourOS      | 8        | 0.56%   |
| Elementary       | 8        | 0.56%   |
| ArcoLinux        | 8        | 0.56%   |
| Ubuntu MATE      | 7        | 0.49%   |
| LMDE             | 7        | 0.49%   |
| CentOS           | 7        | 0.49%   |
| Clear Linux      | 6        | 0.42%   |
| MX               | 5        | 0.35%   |
| Void Linux       | 4        | 0.28%   |
| Lubuntu          | 4        | 0.28%   |
| Kali             | 4        | 0.28%   |
| Ubuntu Budgie    | 3        | 0.21%   |
| NixOS            | 3        | 0.21%   |
| Xero             | 2        | 0.14%   |
| RHEL             | 2        | 0.14%   |
| org.kde.Platform | 2        | 0.14%   |
| LinuxFX          | 2        | 0.14%   |
| Linux Lite       | 2        | 0.14%   |
| Devuan           | 2        | 0.14%   |
| Artix            | 2        | 0.14%   |
| antiX            | 2        | 0.14%   |
| UbuntuDDE        | 1        | 0.07%   |
| SteamOS          | 1        | 0.07%   |
| Solus            | 1        | 0.07%   |
| Sandomierz       | 1        | 0.07%   |
| Rocky Linux      | 1        | 0.07%   |
| Puppy            | 1        | 0.07%   |
| Peppermint       | 1        | 0.07%   |
| PCLinuxOS        | 1        | 0.07%   |
| Parrot           | 1        | 0.07%   |
| Mageia           | 1        | 0.07%   |
| Mabox            | 1        | 0.07%   |
| Garuda Linux     | 1        | 0.07%   |
| Deepin           | 1        | 0.07%   |
| BuildRoot        | 1        | 0.07%   |
| antergos         | 1        | 0.07%   |
| Alpine           | 1        | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 122      | 6.85%   |
| 5.16.7-desktop-1omv4003             | 70       | 3.93%   |
| 5.4.0-42-generic                    | 34       | 1.91%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 30       | 1.68%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 27       | 1.52%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 22       | 1.24%   |
| 5.4.0-26-generic                    | 19       | 1.07%   |
| 5.4.0-52-generic                    | 15       | 0.84%   |
| 5.4.0-58-generic                    | 13       | 0.73%   |
| 5.8.0-48-generic                    | 12       | 0.67%   |
| 5.4.0-72-generic                    | 12       | 0.67%   |
| 5.4.0-54-generic                    | 12       | 0.67%   |
| 5.4.0-48-generic                    | 12       | 0.67%   |
| 5.4.0-40-generic                    | 12       | 0.67%   |
| 5.4.0-66-generic                    | 11       | 0.62%   |
| 5.3.0-46-generic                    | 11       | 0.62%   |
| 5.13.0-39-generic                   | 11       | 0.62%   |
| 5.8.0-43-generic                    | 10       | 0.56%   |
| 5.4.0-56-generic                    | 10       | 0.56%   |
| 5.4.0-29-generic                    | 10       | 0.56%   |
| 5.13.0-40-generic                   | 10       | 0.56%   |
| 5.13.0-27-generic                   | 10       | 0.56%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 10       | 0.56%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 10       | 0.56%   |
| 5.4.0-81-generic                    | 9        | 0.51%   |
| 5.4.0-65-generic                    | 9        | 0.51%   |
| 5.4.0-47-generic                    | 9        | 0.51%   |
| 5.4.0-37-generic                    | 9        | 0.51%   |
| 4.18.16-desktop-1bP                 | 9        | 0.51%   |
| 5.8.0-53-generic                    | 8        | 0.45%   |
| 5.8.0-50-generic                    | 8        | 0.45%   |
| 5.8.0-44-generic                    | 8        | 0.45%   |
| 5.4.0-53-generic                    | 8        | 0.45%   |
| 5.3.0-42-generic                    | 8        | 0.45%   |
| 5.3.0-28-generic                    | 8        | 0.45%   |
| 5.11.0-37-generic                   | 8        | 0.45%   |
| 5.11.0-27-generic                   | 8        | 0.45%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 8        | 0.45%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 8        | 0.45%   |
| 5.4.32-generic-2rosa-x86_64         | 7        | 0.39%   |
| 5.4.0-91-generic                    | 7        | 0.39%   |
| 5.16.13-desktop-1omv4003            | 7        | 0.39%   |
| 5.11.0-40-generic                   | 7        | 0.39%   |
| 5.11.0-38-generic                   | 7        | 0.39%   |
| 5.8.0-14-generic                    | 6        | 0.34%   |
| 5.4.0-90-generic                    | 6        | 0.34%   |
| 5.4.0-7634-generic                  | 6        | 0.34%   |
| 5.4.0-74-generic                    | 6        | 0.34%   |
| 5.4.0-39-generic                    | 6        | 0.34%   |
| 5.4.0-33-generic                    | 6        | 0.34%   |
| 5.4.0-31-generic                    | 6        | 0.34%   |
| 5.13.0-30-generic                   | 6        | 0.34%   |
| 5.12.4-desktop-1omv4050             | 6        | 0.34%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 6        | 0.34%   |
| 5.0.0-32-generic                    | 6        | 0.34%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 6        | 0.34%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 6        | 0.34%   |
| 4.18.0-15-generic                   | 6        | 0.34%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 6        | 0.34%   |
| 5.8.0-25-generic                    | 5        | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 283      | 17.12%  |
| 4.15.0  | 129      | 7.8%    |
| 5.10.14 | 123      | 7.44%   |
| 5.8.0   | 84       | 5.08%   |
| 5.16.7  | 72       | 4.36%   |
| 5.11.0  | 70       | 4.23%   |
| 5.13.0  | 65       | 3.93%   |
| 5.3.0   | 56       | 3.39%   |
| 5.0.0   | 37       | 2.24%   |
| 4.9.60  | 33       | 2%      |
| 5.15.0  | 31       | 1.88%   |
| 4.18.0  | 30       | 1.81%   |
| 4.9.20  | 27       | 1.63%   |
| 5.10.0  | 26       | 1.57%   |
| 4.19.0  | 19       | 1.15%   |
| 4.1.38  | 14       | 0.85%   |
| 4.9.124 | 10       | 0.6%    |
| 4.1.34  | 10       | 0.6%    |
| 4.18.16 | 9        | 0.54%   |
| 5.17.5  | 8        | 0.48%   |
| 4.9.76  | 8        | 0.48%   |
| 4.9.155 | 8        | 0.48%   |
| 5.6.0   | 7        | 0.42%   |
| 5.4.32  | 7        | 0.42%   |
| 5.16.13 | 7        | 0.42%   |
| 5.9.16  | 6        | 0.36%   |
| 5.9.0   | 6        | 0.36%   |
| 5.15.12 | 6        | 0.36%   |
| 5.12.4  | 6        | 0.36%   |
| 5.10.74 | 6        | 0.36%   |
| 4.9.95  | 6        | 0.36%   |
| 5.9.1   | 5        | 0.3%    |
| 5.4.83  | 5        | 0.3%    |
| 5.17.9  | 5        | 0.3%    |
| 5.15.6  | 5        | 0.3%    |
| 5.15.15 | 5        | 0.3%    |
| 5.14.14 | 5        | 0.3%    |
| 5.12.9  | 5        | 0.3%    |
| 5.11.6  | 5        | 0.3%    |
| 5.11.16 | 5        | 0.3%    |
| 5.11.12 | 5        | 0.3%    |
| 4.4.0   | 5        | 0.3%    |
| 5.4.12  | 4        | 0.24%   |
| 5.18.6  | 4        | 0.24%   |
| 5.18.5  | 4        | 0.24%   |
| 5.15.32 | 4        | 0.24%   |
| 4.1.25  | 4        | 0.24%   |
| 5.8.6   | 3        | 0.18%   |
| 5.8.3   | 3        | 0.18%   |
| 5.8.18  | 3        | 0.18%   |
| 5.7.11  | 3        | 0.18%   |
| 5.6.6   | 3        | 0.18%   |
| 5.6.19  | 3        | 0.18%   |
| 5.4.8   | 3        | 0.18%   |
| 5.4.40  | 3        | 0.18%   |
| 5.4.15  | 3        | 0.18%   |
| 5.3.18  | 3        | 0.18%   |
| 5.18.16 | 3        | 0.18%   |
| 5.18.12 | 3        | 0.18%   |
| 5.17.3  | 3        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 321      | 20.15%  |
| 5.10    | 196      | 12.3%   |
| 4.15    | 129      | 8.1%    |
| 5.8     | 105      | 6.59%   |
| 5.16    | 100      | 6.28%   |
| 5.11    | 96       | 6.03%   |
| 5.15    | 82       | 5.15%   |
| 4.9     | 78       | 4.9%    |
| 5.13    | 77       | 4.83%   |
| 5.3     | 62       | 3.89%   |
| 5.0     | 41       | 2.57%   |
| 4.18    | 39       | 2.45%   |
| 5.12    | 31       | 1.95%   |
| 5.18    | 28       | 1.76%   |
| 4.1     | 28       | 1.76%   |
| 5.9     | 27       | 1.69%   |
| 5.17    | 27       | 1.69%   |
| 5.6     | 24       | 1.51%   |
| 5.14    | 23       | 1.44%   |
| 4.19    | 23       | 1.44%   |
| 5.5     | 16       | 1%      |
| 5.7     | 13       | 0.82%   |
| 4.4     | 6        | 0.38%   |
| 5.19    | 4        | 0.25%   |
| 4.16    | 3        | 0.19%   |
| 5.1     | 2        | 0.13%   |
| 4.8     | 2        | 0.13%   |
| 4.20    | 2        | 0.13%   |
| 5.2     | 1        | 0.06%   |
| 4.7     | 1        | 0.06%   |
| 4.14    | 1        | 0.06%   |
| 4.13    | 1        | 0.06%   |
| 4.12    | 1        | 0.06%   |
| 3.16    | 1        | 0.06%   |
| 3.13    | 1        | 0.06%   |
| 3.10    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1342     | 97.04%  |
| i686   | 39       | 2.82%   |
| ppc64  | 1        | 0.07%   |
| ppc    | 1        | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 483      | 32.83%  |
| KDE5            | 401      | 27.26%  |
| Unknown         | 166      | 11.28%  |
| XFCE            | 94       | 6.39%   |
| KDE4            | 77       | 5.23%   |
| X-Cinnamon      | 69       | 4.69%   |
| KDE             | 50       | 3.4%    |
| MATE            | 39       | 2.65%   |
| Cinnamon        | 19       | 1.29%   |
| i3              | 13       | 0.88%   |
| LXQt            | 10       | 0.68%   |
| Unity           | 9        | 0.61%   |
| Pantheon        | 8        | 0.54%   |
| LXDE            | 8        | 0.54%   |
| Deepin          | 6        | 0.41%   |
| GNOME Flashback | 4        | 0.27%   |
| Budgie          | 4        | 0.27%   |
| qtile           | 2        | 0.14%   |
| GNOME Classic   | 2        | 0.14%   |
| awesome         | 2        | 0.14%   |
| openbox         | 1        | 0.07%   |
| jwm             | 1        | 0.07%   |
| ICEWM           | 1        | 0.07%   |
| fluxbox         | 1        | 0.07%   |
| DWM             | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1214     | 85.31%  |
| Wayland | 104      | 7.31%   |
| Unknown | 72       | 5.06%   |
| Tty     | 33       | 2.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 656      | 45.09%  |
| SDDM    | 376      | 25.84%  |
| GDM     | 118      | 8.11%   |
| LightDM | 96       | 6.6%    |
| KDM     | 85       | 5.84%   |
| GDM3    | 62       | 4.26%   |
| TDM     | 53       | 3.64%   |
| XDM     | 4        | 0.27%   |
| SLIMSKI | 1        | 0.07%   |
| SLiM    | 1        | 0.07%   |
| MDM     | 1        | 0.07%   |
| Ly      | 1        | 0.07%   |
| LXDM    | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| pl_PL      | 811      | 55.93%  |
| en_US      | 298      | 20.55%  |
| Unknown    | 255      | 17.59%  |
| en_GB      | 39       | 2.69%   |
| C          | 22       | 1.52%   |
| ru_RU      | 6        | 0.41%   |
| en_CA      | 6        | 0.41%   |
| szl_PL     | 3        | 0.21%   |
| ru_UA      | 2        | 0.14%   |
| uk_UA      | 1        | 0.07%   |
| sv_SE      | 1        | 0.07%   |
| fr_FR      | 1        | 0.07%   |
| en_US.UTF8 | 1        | 0.07%   |
| en_IN      | 1        | 0.07%   |
| en_IE      | 1        | 0.07%   |
| en_DK      | 1        | 0.07%   |
| en_AG      | 1        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 908      | 64.08%  |
| EFI  | 509      | 35.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 952      | 65.88%  |
| Overlay  | 224      | 15.5%   |
| Unknown  | 116      | 8.03%   |
| Btrfs    | 110      | 7.61%   |
| Xfs      | 19       | 1.31%   |
| Zfs      | 7        | 0.48%   |
| F2fs     | 5        | 0.35%   |
| Tmpfs    | 4        | 0.28%   |
| Ext3     | 3        | 0.21%   |
| Ext2     | 2        | 0.14%   |
| SquXshfs | 1        | 0.07%   |
| Jfs      | 1        | 0.07%   |
| Aufs     | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 751      | 52.3%   |
| GPT     | 395      | 27.51%  |
| MBR     | 290      | 20.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1072     | 75.23%  |
| Yes       | 353      | 24.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 855      | 60.13%  |
| Yes       | 567      | 39.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 348      | 25.25%  |
| ASUSTek Computer    | 300      | 21.77%  |
| MSI                 | 230      | 16.69%  |
| ASRock              | 135      | 9.8%    |
| Dell                | 109      | 7.91%   |
| Hewlett-Packard     | 86       | 6.24%   |
| Lenovo              | 48       | 3.48%   |
| Fujitsu             | 22       | 1.6%    |
| Intel               | 17       | 1.23%   |
| Acer                | 15       | 1.09%   |
| Fujitsu Siemens     | 10       | 0.73%   |
| Unknown             | 9        | 0.65%   |
| Foxconn             | 8        | 0.58%   |
| Medion              | 4        | 0.29%   |
| ECS                 | 4        | 0.29%   |
| Inventec            | 3        | 0.22%   |
| Huanan              | 3        | 0.22%   |
| ABIT                | 3        | 0.22%   |
| Supermicro          | 2        | 0.15%   |
| Pegatron            | 2        | 0.15%   |
| Hardkernel          | 2        | 0.15%   |
| Gateway             | 2        | 0.15%   |
| Apple               | 2        | 0.15%   |
| Wortmann AG         | 1        | 0.07%   |
| WeiBu               | 1        | 0.07%   |
| Shuttle             | 1        | 0.07%   |
| OPTIMUS             | 1        | 0.07%   |
| Nvidia              | 1        | 0.07%   |
| ITSUMI              | 1        | 0.07%   |
| HEDYCOMPUTER        | 1        | 0.07%   |
| Hampoo              | 1        | 0.07%   |
| EVGA                | 1        | 0.07%   |
| Biostar             | 1        | 0.07%   |
| AMI                 | 1        | 0.07%   |
| AMD                 | 1        | 0.07%   |
| ACTION              | 1        | 0.07%   |
| AAEON               | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS All Series             | 25       | 1.81%   |
| ASUS SABERTOOTH Z77         | 17       | 1.23%   |
| MSI MS-7817                 | 15       | 1.09%   |
| Gigabyte B450M DS3H         | 15       | 1.09%   |
| MSI MS-7B86                 | 14       | 1.02%   |
| Dell OptiPlex 780           | 13       | 0.94%   |
| MSI MS-7C02                 | 10       | 0.73%   |
| Unknown                     | 9        | 0.65%   |
| MSI MS-7B79                 | 8        | 0.58%   |
| Gigabyte B85M-D3H           | 8        | 0.58%   |
| Gigabyte B450 AORUS ELITE   | 8        | 0.58%   |
| ASUS TUF Gaming X570-PLUS   | 8        | 0.58%   |
| MSI MS-7A38                 | 7        | 0.51%   |
| Dell OptiPlex 7010          | 7        | 0.51%   |
| MSI MS-7C37                 | 6        | 0.44%   |
| MSI MS-7721                 | 6        | 0.44%   |
| Gigabyte 970A-DS3P          | 6        | 0.44%   |
| Dell OptiPlex 790           | 6        | 0.44%   |
| ASUS PRIME X470-PRO         | 6        | 0.44%   |
| ASUS PRIME B450M-A          | 6        | 0.44%   |
| MSI MS-7C80                 | 5        | 0.36%   |
| MSI MS-7B89                 | 5        | 0.36%   |
| HP t620 Quad Core TC        | 5        | 0.36%   |
| Gigabyte P31-DS3L           | 5        | 0.36%   |
| Gigabyte GA-MA770T-UD3P     | 5        | 0.36%   |
| Gigabyte G31M-S2L           | 5        | 0.36%   |
| Gigabyte A320M-S2H          | 5        | 0.36%   |
| Dell OptiPlex 9020          | 5        | 0.36%   |
| ASUS PRIME B350-PLUS        | 5        | 0.36%   |
| ASUS P5G41T-M LX            | 5        | 0.36%   |
| MSI MS-7C52                 | 4        | 0.29%   |
| MSI MS-7C08                 | 4        | 0.29%   |
| MSI MS-7996                 | 4        | 0.29%   |
| MSI MS-7693                 | 4        | 0.29%   |
| HP Compaq Elite 8300 CMT    | 4        | 0.29%   |
| HP Compaq 8200 Elite SFF PC | 4        | 0.29%   |
| HP Compaq 6200 Pro SFF PC   | 4        | 0.29%   |
| Gigabyte X570 GAMING X      | 4        | 0.29%   |
| Gigabyte M68M-S2P           | 4        | 0.29%   |
| Gigabyte GA-78LMT-USB3 6.0  | 4        | 0.29%   |
| Gigabyte G31M-ES2L          | 4        | 0.29%   |
| Dell OptiPlex 760           | 4        | 0.29%   |
| Dell OptiPlex 3010          | 4        | 0.29%   |
| ASUS PRIME X370-PRO         | 4        | 0.29%   |
| ASUS M5A97 R2.0             | 4        | 0.29%   |
| ASRock FM2A88X Extreme6+    | 4        | 0.29%   |
| ASRock B450 Pro4            | 4        | 0.29%   |
| MSI MS-7D25                 | 3        | 0.22%   |
| MSI MS-7C95                 | 3        | 0.22%   |
| MSI MS-7C91                 | 3        | 0.22%   |
| MSI MS-7B93                 | 3        | 0.22%   |
| MSI MS-7B84                 | 3        | 0.22%   |
| MSI MS-7B53                 | 3        | 0.22%   |
| MSI MS-7A34                 | 3        | 0.22%   |
| MSI MS-7982                 | 3        | 0.22%   |
| MSI MS-7978                 | 3        | 0.22%   |
| MSI MS-7971                 | 3        | 0.22%   |
| MSI MS-7816                 | 3        | 0.22%   |
| MSI MS-7592                 | 3        | 0.22%   |
| Inventec Z CLASS            | 3        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 74       | 5.37%   |
| ASUS PRIME              | 40       | 2.9%    |
| HP Compaq               | 36       | 2.61%   |
| Lenovo ThinkCentre      | 34       | 2.47%   |
| ASUS TUF                | 26       | 1.89%   |
| ASUS All                | 25       | 1.81%   |
| Gigabyte B450M          | 22       | 1.6%    |
| ASUS ROG                | 19       | 1.38%   |
| ASUS SABERTOOTH         | 18       | 1.31%   |
| Dell Precision          | 17       | 1.23%   |
| MSI MS-7817             | 15       | 1.09%   |
| Fujitsu ESPRIMO         | 15       | 1.09%   |
| MSI MS-7B86             | 14       | 1.02%   |
| HP EliteDesk            | 14       | 1.02%   |
| Gigabyte X570           | 13       | 0.94%   |
| Gigabyte B450           | 12       | 0.87%   |
| MSI MS-7C02             | 10       | 0.73%   |
| ASUS M5A97              | 9        | 0.65%   |
| Unknown                 | 9        | 0.65%   |
| MSI MS-7B79             | 8        | 0.58%   |
| Gigabyte B85M-D3H       | 8        | 0.58%   |
| ASRock B450             | 8        | 0.58%   |
| MSI MS-7A38             | 7        | 0.51%   |
| Lenovo IdeaCentre       | 7        | 0.51%   |
| Gigabyte GA-78LMT-USB3  | 7        | 0.51%   |
| Gigabyte B550           | 7        | 0.51%   |
| Dell Vostro             | 7        | 0.51%   |
| ASUS P5G41T-M           | 7        | 0.51%   |
| MSI MS-7C37             | 6        | 0.44%   |
| MSI MS-7721             | 6        | 0.44%   |
| Gigabyte Z390           | 6        | 0.44%   |
| Gigabyte 970A-DS3P      | 6        | 0.44%   |
| Fujitsu Siemens ESPRIMO | 6        | 0.44%   |
| ASUS M5A78L-M           | 6        | 0.44%   |
| Acer Veriton            | 6        | 0.44%   |
| MSI MS-7C80             | 5        | 0.36%   |
| MSI MS-7B89             | 5        | 0.36%   |
| Lenovo ThinkStation     | 5        | 0.36%   |
| HP t620                 | 5        | 0.36%   |
| HP ProDesk              | 5        | 0.36%   |
| Gigabyte P31-DS3L       | 5        | 0.36%   |
| Gigabyte GA-MA770T-UD3P | 5        | 0.36%   |
| Gigabyte G31M-S2L       | 5        | 0.36%   |
| Gigabyte A320M-S2H      | 5        | 0.36%   |
| ASUS P8Z77-V            | 5        | 0.36%   |
| ASUS P8H61-M            | 5        | 0.36%   |
| ASRock X370             | 5        | 0.36%   |
| ASRock B450M            | 5        | 0.36%   |
| Acer Aspire             | 5        | 0.36%   |
| MSI MS-7C52             | 4        | 0.29%   |
| MSI MS-7C08             | 4        | 0.29%   |
| MSI MS-7996             | 4        | 0.29%   |
| MSI MS-7693             | 4        | 0.29%   |
| Gigabyte M68M-S2P       | 4        | 0.29%   |
| Gigabyte G31M-ES2L      | 4        | 0.29%   |
| Fujitsu CELSIUS         | 4        | 0.29%   |
| ASUS Maximus            | 4        | 0.29%   |
| ASRock Z97              | 4        | 0.29%   |
| ASRock Z87              | 4        | 0.29%   |
| ASRock Z390             | 4        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 154      | 11.18%  |
| 2012    | 137      | 9.94%   |
| 2013    | 131      | 9.51%   |
| 2011    | 101      | 7.33%   |
| 2009    | 96       | 6.97%   |
| 2019    | 94       | 6.82%   |
| 2014    | 89       | 6.46%   |
| 2017    | 83       | 6.02%   |
| 2007    | 81       | 5.88%   |
| 2010    | 75       | 5.44%   |
| 2020    | 72       | 5.22%   |
| 2008    | 70       | 5.08%   |
| 2015    | 59       | 4.28%   |
| 2016    | 50       | 3.63%   |
| 2021    | 35       | 2.54%   |
| 2006    | 35       | 2.54%   |
| 2005    | 6        | 0.44%   |
| 2004    | 4        | 0.29%   |
| Unknown | 4        | 0.29%   |
| 2022    | 1        | 0.07%   |
| 2001    | 1        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1378     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1360     | 98.34%  |
| Enabled  | 23       | 1.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1377     | 99.93%  |
| Yes  | 1        | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 322      | 22.71%  |
| 16.01-24.0  | 305      | 21.51%  |
| 3.01-4.0    | 235      | 16.57%  |
| 4.01-8.0    | 220      | 15.51%  |
| 32.01-64.0  | 175      | 12.34%  |
| 64.01-256.0 | 50       | 3.53%   |
| 1.01-2.0    | 48       | 3.39%   |
| 24.01-32.0  | 32       | 2.26%   |
| 2.01-3.0    | 22       | 1.55%   |
| 0.51-1.0    | 9        | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 639      | 39.94%  |
| 2.01-3.0   | 294      | 18.38%  |
| 4.01-8.0   | 200      | 12.5%   |
| 0.51-1.0   | 179      | 11.19%  |
| 3.01-4.0   | 158      | 9.88%   |
| 8.01-16.0  | 63       | 3.94%   |
| 0.01-0.5   | 36       | 2.25%   |
| 16.01-24.0 | 23       | 1.44%   |
| 24.01-32.0 | 5        | 0.31%   |
| 32.01-64.0 | 2        | 0.13%   |
| Unknown    | 1        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 528      | 35.97%  |
| 2      | 436      | 29.7%   |
| 3      | 262      | 17.85%  |
| 4      | 119      | 8.11%   |
| 5      | 55       | 3.75%   |
| 6      | 23       | 1.57%   |
| 0      | 21       | 1.43%   |
| 7      | 11       | 0.75%   |
| 8      | 6        | 0.41%   |
| 9      | 3        | 0.2%    |
| 11     | 2        | 0.14%   |
| 10     | 2        | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 743      | 52.92%  |
| No        | 661      | 47.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1363     | 98.91%  |
| No        | 15       | 1.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 870      | 61.79%  |
| Yes       | 538      | 38.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1081     | 77.32%  |
| Yes       | 317      | 22.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 1378     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Warsaw                 | 283      | 18.72%  |
| Krakow                 | 103      | 6.81%   |
| Wroclaw                | 89       | 5.89%   |
| Poznan                 | 65       | 4.3%    |
| Gdansk                 | 45       | 2.98%   |
| Katowice               | 40       | 2.65%   |
| Lodz                   | 34       | 2.25%   |
| Gdynia                 | 21       | 1.39%   |
| Lublin                 | 18       | 1.19%   |
| Strzyzow               | 17       | 1.12%   |
| Szczecin               | 14       | 0.93%   |
| Gliwice                | 13       | 0.86%   |
| Częstochowa           | 13       | 0.86%   |
| Bialystok              | 13       | 0.86%   |
| Płock                 | 12       | 0.79%   |
| Radom                  | 11       | 0.73%   |
| Torun                  | 10       | 0.66%   |
| Rzeszów               | 10       | 0.66%   |
| Rybnik                 | 10       | 0.66%   |
| Bielsko-Biala          | 10       | 0.66%   |
| Sosnowiec              | 9        | 0.6%    |
| Bytom                  | 9        | 0.6%    |
| Bydgoszcz              | 8        | 0.53%   |
| Siemianowice Śląskie | 7        | 0.46%   |
| Ruda Śląska          | 7        | 0.46%   |
| Debica                 | 7        | 0.46%   |
| Zabrze                 | 6        | 0.4%    |
| Wołomin               | 6        | 0.4%    |
| Tychy                  | 6        | 0.4%    |
| Legnica                | 6        | 0.4%    |
| Cieszyn                | 6        | 0.4%    |
| Chorzów               | 6        | 0.4%    |
| Będzin                | 6        | 0.4%    |
| Zdunska Wola           | 5        | 0.33%   |
| Wodzisław Śląski    | 5        | 0.33%   |
| Słupsk                | 5        | 0.33%   |
| Swidnica               | 5        | 0.33%   |
| Starachowice           | 5        | 0.33%   |
| Piaseczno              | 5        | 0.33%   |
| Koszalin               | 5        | 0.33%   |
| Kielce                 | 5        | 0.33%   |
| Jaworzno               | 5        | 0.33%   |
| Elblag                 | 5        | 0.33%   |
| Zielona Góra          | 4        | 0.26%   |
| Zgorzelec              | 4        | 0.26%   |
| Wałbrzych             | 4        | 0.26%   |
| Tarnów                | 4        | 0.26%   |
| Rypin                  | 4        | 0.26%   |
| Rudzica                | 4        | 0.26%   |
| Pilawa Gorna           | 4        | 0.26%   |
| Pabianice              | 4        | 0.26%   |
| Opole                  | 4        | 0.26%   |
| Olsztyn                | 4        | 0.26%   |
| Lubin                  | 4        | 0.26%   |
| Kozieglowy             | 4        | 0.26%   |
| Kalisz                 | 4        | 0.26%   |
| Jelenia Góra          | 4        | 0.26%   |
| Jastrzębie Zdrój     | 4        | 0.26%   |
| Żory                  | 3        | 0.2%    |
| Zagnansk               | 3        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 474      | 822    | 18.23%  |
| WDC                       | 462      | 789    | 17.77%  |
| Samsung Electronics       | 325      | 579    | 12.5%   |
| GOODRAM                   | 175      | 275    | 6.73%   |
| Toshiba                   | 161      | 281    | 6.19%   |
| Crucial                   | 111      | 198    | 4.27%   |
| Kingston                  | 108      | 161    | 4.15%   |
| A-DATA Technology         | 108      | 172    | 4.15%   |
| Hitachi                   | 84       | 126    | 3.23%   |
| SanDisk                   | 70       | 111    | 2.69%   |
| Patriot                   | 41       | 53     | 1.58%   |
| XPG                       | 33       | 46     | 1.27%   |
| SPCC                      | 33       | 49     | 1.27%   |
| Intel                     | 33       | 55     | 1.27%   |
| Plextor                   | 30       | 35     | 1.15%   |
| HGST                      | 24       | 33     | 0.92%   |
| Phison                    | 22       | 32     | 0.85%   |
| PNY                       | 19       | 22     | 0.73%   |
| Corsair                   | 19       | 25     | 0.73%   |
| OCZ                       | 18       | 20     | 0.69%   |
| Apacer                    | 18       | 29     | 0.69%   |
| Unknown                   | 17       | 28     | 0.65%   |
| Maxtor                    | 17       | 17     | 0.65%   |
| Micron Technology         | 16       | 23     | 0.62%   |
| Realtek Semiconductor     | 12       | 21     | 0.46%   |
| Lite-On                   | 12       | 14     | 0.46%   |
| Fujitsu                   | 12       | 15     | 0.46%   |
| ASMT                      | 12       | 13     | 0.46%   |
| SK hynix                  | 11       | 20     | 0.42%   |
| China                     | 10       | 10     | 0.38%   |
| Transcend                 | 6        | 6      | 0.23%   |
| Silicon Motion            | 6        | 7      | 0.23%   |
| LITEON                    | 6        | 11     | 0.23%   |
| JMicron Technology        | 6        | 7      | 0.23%   |
| Micron/Crucial Technology | 5        | 5      | 0.19%   |
| KIOXIA-EXCERIA            | 5        | 9      | 0.19%   |
| Intenso                   | 5        | 10     | 0.19%   |
| HUAWEI                    | 5        | 5      | 0.19%   |
| KIOXIA                    | 4        | 5      | 0.15%   |
| Hewlett-Packard           | 4        | 4      | 0.15%   |
| Team                      | 3        | 8      | 0.12%   |
| KingSpec                  | 3        | 3      | 0.12%   |
| sobetter                  | 2        | 2      | 0.08%   |
| MDT                       | 2        | 4      | 0.08%   |
| LITEONIT                  | 2        | 2      | 0.08%   |
| Lexar                     | 2        | 2      | 0.08%   |
| KingFast                  | 2        | 2      | 0.08%   |
| Kingchuxing               | 2        | 7      | 0.08%   |
| Gigabyte Technology       | 2        | 4      | 0.08%   |
| BIWIN                     | 2        | 2      | 0.08%   |
| ASMedia                   | 2        | 3      | 0.08%   |
| Unknown                   | 2        | 2      | 0.08%   |
| ZTE                       | 1        | 1      | 0.04%   |
| XrayDisk                  | 1        | 1      | 0.04%   |
| WDC WDS2                  | 1        | 1      | 0.04%   |
| WD MediaMax               | 1        | 2      | 0.04%   |
| Union Memory (Shenzhen)   | 1        | 1      | 0.04%   |
| T-FORCE                   | 1        | 1      | 0.04%   |
| Synology                  | 1        | 1      | 0.04%   |
| SSSTC                     | 1        | 1      | 0.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                | 46       | 1.53%   |
| Seagate ST500DM002-1BD142 500GB    | 33       | 1.1%    |
| Samsung SSD 850 EVO 250GB          | 29       | 0.97%   |
| Seagate ST3500418AS 500GB          | 26       | 0.87%   |
| Crucial CT500MX500SSD1 500GB       | 26       | 0.87%   |
| Samsung NVMe SSD Drive 500GB       | 25       | 0.83%   |
| Seagate ST1000DM003-1ER162 1TB     | 24       | 0.8%    |
| Samsung HD502HJ 500GB              | 22       | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB     | 21       | 0.7%    |
| Samsung SSD 860 EVO 250GB          | 21       | 0.7%    |
| Kingston SV300S37A120G 120GB SSD   | 21       | 0.7%    |
| GOODRAM SSD 120GB                  | 21       | 0.7%    |
| Toshiba DT01ACA100 1TB             | 20       | 0.67%   |
| GOODRAM SSDPR-CX400-512 512GB      | 19       | 0.63%   |
| Samsung SSD 860 EVO 500GB          | 18       | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB     | 17       | 0.57%   |
| GOODRAM SSD 240GB                  | 17       | 0.57%   |
| Crucial CT1000MX500SSD1 1TB        | 17       | 0.57%   |
| Toshiba HDWD130 3TB                | 16       | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB     | 15       | 0.5%    |
| GOODRAM SSDPR-CL100-120-G2 120GB   | 14       | 0.47%   |
| A-DATA SU800 256GB SSD             | 14       | 0.47%   |
| SPCC Solid State Disk 120GB        | 13       | 0.43%   |
| Seagate ST3250410AS 250GB          | 13       | 0.43%   |
| Samsung HD103SJ 1TB                | 13       | 0.43%   |
| Patriot Burst 120GB SSD            | 13       | 0.43%   |
| Kingston SA400S37480G 480GB SSD    | 13       | 0.43%   |
| A-DATA SX8200PNP 512GB             | 13       | 0.43%   |
| Toshiba HDWD120 2TB                | 12       | 0.4%    |
| SanDisk SDSSDA240G 240GB           | 12       | 0.4%    |
| Samsung NVMe SSD Drive 1TB         | 12       | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 12       | 0.4%    |
| A-DATA SU650 240GB SSD             | 12       | 0.4%    |
| Seagate ST3250310AS 250GB          | 11       | 0.37%   |
| Seagate ST3160318AS 160GB          | 11       | 0.37%   |
| Seagate ST250DM000-1BD141 250GB    | 11       | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11       | 0.37%   |
| Samsung SSD 840 EVO 120GB          | 11       | 0.37%   |
| GOODRAM SSDPR-CX400-256 256GB      | 11       | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB           | 10       | 0.33%   |
| Toshiba DT01ACA200 2TB             | 10       | 0.33%   |
| Seagate ST3500312CS 500GB          | 10       | 0.33%   |
| Seagate ST3160815AS 160GB          | 10       | 0.33%   |
| GOODRAM SSDPR-CX400-512-G2 512GB   | 10       | 0.33%   |
| A-DATA SU630 240GB SSD             | 10       | 0.33%   |
| WDC WD20EFRX-68EUZN0 2TB           | 9        | 0.3%    |
| WDC WD10EZEX-00BN5A0 1TB           | 9        | 0.3%    |
| Seagate ST3500413AS 500GB          | 9        | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB     | 9        | 0.3%    |
| Seagate ST2000DM001-1CH164 2TB     | 9        | 0.3%    |
| Seagate ST1000LM035-1RK172 1TB     | 9        | 0.3%    |
| Samsung SSD 860 EVO 1TB            | 9        | 0.3%    |
| Kingston SA400S37240G 240GB SSD    | 9        | 0.3%    |
| XPG GAMMIX S11 Pro 1TB             | 8        | 0.27%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 8        | 0.27%   |
| Seagate ST3320620AS 320GB          | 8        | 0.27%   |
| Seagate ST31000528AS 1TB           | 8        | 0.27%   |
| Seagate Expansion 500GB            | 8        | 0.27%   |
| SanDisk SSD PLUS 240GB             | 8        | 0.27%   |
| Samsung SSD 970 EVO Plus 500GB     | 8        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 474      | 822    | 35.72%  |
| WDC                 | 438      | 741    | 33.01%  |
| Toshiba             | 150      | 269    | 11.3%   |
| Samsung Electronics | 113      | 177    | 8.52%   |
| Hitachi             | 84       | 126    | 6.33%   |
| HGST                | 24       | 33     | 1.81%   |
| Maxtor              | 16       | 16     | 1.21%   |
| Fujitsu             | 12       | 15     | 0.9%    |
| ASMT                | 4        | 5      | 0.3%    |
| ASMedia             | 2        | 3      | 0.15%   |
| WD MediaMax         | 1        | 2      | 0.08%   |
| Unknown             | 1        | 1      | 0.08%   |
| Synology            | 1        | 1      | 0.08%   |
| MARVELL             | 1        | 1      | 0.08%   |
| IBM/Hitachi         | 1        | 1      | 0.08%   |
| HPE                 | 1        | 1      | 0.08%   |
| Hewlett-Packard     | 1        | 1      | 0.08%   |
| ExcelStor           | 1        | 1      | 0.08%   |
| ASMT109x            | 1        | 1      | 0.08%   |
| Unknown             | 1        | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| GOODRAM             | 171      | 265    | 18.71%  |
| Samsung Electronics | 142      | 218    | 15.54%  |
| Crucial             | 107      | 193    | 11.71%  |
| A-DATA Technology   | 86       | 133    | 9.41%   |
| Kingston            | 79       | 114    | 8.64%   |
| SanDisk             | 61       | 98     | 6.67%   |
| Patriot             | 35       | 47     | 3.83%   |
| SPCC                | 29       | 43     | 3.17%   |
| Plextor             | 24       | 29     | 2.63%   |
| WDC                 | 23       | 29     | 2.52%   |
| OCZ                 | 18       | 20     | 1.97%   |
| Apacer              | 17       | 28     | 1.86%   |
| Intel               | 14       | 19     | 1.53%   |
| PNY                 | 13       | 16     | 1.42%   |
| Micron Technology   | 13       | 19     | 1.42%   |
| Toshiba             | 10       | 11     | 1.09%   |
| China               | 9        | 9      | 0.98%   |
| Corsair             | 8        | 9      | 0.88%   |
| ASMT                | 8        | 8      | 0.88%   |
| Transcend           | 6        | 6      | 0.66%   |
| LITEON              | 6        | 11     | 0.66%   |
| KIOXIA-EXCERIA      | 3        | 6      | 0.33%   |
| KingSpec            | 3        | 3      | 0.33%   |
| Intenso             | 3        | 8      | 0.33%   |
| Team                | 2        | 2      | 0.22%   |
| LITEONIT            | 2        | 2      | 0.22%   |
| JMicron Technology  | 2        | 2      | 0.22%   |
| BIWIN               | 2        | 2      | 0.22%   |
| XrayDisk            | 1        | 1      | 0.11%   |
| WDC WDS2            | 1        | 1      | 0.11%   |
| Unknown             | 1        | 1      | 0.11%   |
| T-FORCE             | 1        | 1      | 0.11%   |
| SSSTC               | 1        | 1      | 0.11%   |
| SK hynix            | 1        | 1      | 0.11%   |
| Phison              | 1        | 1      | 0.11%   |
| Origin              | 1        | 1      | 0.11%   |
| OCZ-AGIL            | 1        | 1      | 0.11%   |
| Maxtor              | 1        | 1      | 0.11%   |
| Lexar               | 1        | 1      | 0.11%   |
| KingDian            | 1        | 1      | 0.11%   |
| Kingchuxing         | 1        | 1      | 0.11%   |
| Hewlett-Packard     | 1        | 1      | 0.11%   |
| FORESEE             | 1        | 1      | 0.11%   |
| Apple               | 1        | 1      | 0.11%   |
| AMD-RAID            | 1        | 2      | 0.11%   |
| ADATA SU            | 1        | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1013     | 2218   | 47.36%  |
| SSD     | 759      | 1369   | 35.48%  |
| NVMe    | 326      | 580    | 15.24%  |
| Unknown | 33       | 55     | 1.54%   |
| MMC     | 8        | 8      | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1274     | 3527   | 75.65%  |
| NVMe | 326      | 580    | 19.36%  |
| SAS  | 76       | 115    | 4.51%   |
| MMC  | 8        | 8      | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1070     | 2162   | 58.25%  |
| 0.51-1.0   | 485      | 888    | 26.4%   |
| 1.01-2.0   | 151      | 269    | 8.22%   |
| 3.01-4.0   | 52       | 99     | 2.83%   |
| 2.01-3.0   | 50       | 103    | 2.72%   |
| 4.01-10.0  | 25       | 57     | 1.36%   |
| 10.01-20.0 | 4        | 9      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 378      | 24.75%  |
| 251-500        | 215      | 14.08%  |
| 501-1000       | 183      | 11.98%  |
| 1-20           | 167      | 10.94%  |
| 1001-2000      | 153      | 10.02%  |
| 51-100         | 122      | 7.99%   |
| More than 3000 | 98       | 6.42%   |
| Unknown        | 77       | 5.04%   |
| 21-50          | 75       | 4.91%   |
| 2001-3000      | 59       | 3.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 599      | 38.32%  |
| 21-50          | 198      | 12.67%  |
| 101-250        | 162      | 10.36%  |
| 51-100         | 135      | 8.64%   |
| 251-500        | 123      | 7.87%   |
| 501-1000       | 119      | 7.61%   |
| 1001-2000      | 81       | 5.18%   |
| Unknown        | 77       | 4.93%   |
| More than 3000 | 36       | 2.3%    |
| 2001-3000      | 33       | 2.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB           | 8        | 11     | 2.72%   |
| Seagate ST500DM002-1BD142 500GB     | 5        | 5      | 1.7%    |
| GOODRAM SSD 120GB                   | 5        | 5      | 1.7%    |
| Seagate ST9500325AS 500GB           | 4        | 7      | 1.36%   |
| Seagate ST92505610AS 250GB          | 4        | 4      | 1.36%   |
| Seagate ST1000DM003-9YN162 1TB      | 4        | 4      | 1.36%   |
| ASMT 2135 120GB SSD                 | 4        | 4      | 1.36%   |
| Seagate ST3500312CS 500GB           | 3        | 3      | 1.02%   |
| Seagate ST3250410AS 250GB           | 3        | 3      | 1.02%   |
| Seagate ST31500341AS 1TB            | 3        | 4      | 1.02%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 3      | 1.02%   |
| WDC WD5002ABYS-01B1B0 500GB         | 2        | 14     | 0.68%   |
| WDC WD5000AVDS-63U7B1 500GB         | 2        | 2      | 0.68%   |
| WDC WD5000AACS-00G8B1 500GB         | 2        | 2      | 0.68%   |
| WDC WD3200AAJS-00B4A0 320GB         | 2        | 4      | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 10     | 0.68%   |
| WDC WD15EARS-00Z5B1 1TB             | 2        | 2      | 0.68%   |
| WDC WD10EADS-22M2B0 1TB             | 2        | 4      | 0.68%   |
| Toshiba MQ04ABF100 1TB              | 2        | 3      | 0.68%   |
| Toshiba MK2546GSX 250GB             | 2        | 2      | 0.68%   |
| Toshiba DT01ACA100 1TB              | 2        | 2      | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 2      | 0.68%   |
| Seagate ST3500320AS 500GB           | 2        | 2      | 0.68%   |
| Seagate ST3320620AS 320GB           | 2        | 2      | 0.68%   |
| Seagate ST3320613AS 320GB           | 2        | 2      | 0.68%   |
| Seagate ST3320418AS 320GB           | 2        | 2      | 0.68%   |
| Seagate ST3200826AS 200GB           | 2        | 2      | 0.68%   |
| Seagate ST31000528AS 1TB            | 2        | 2      | 0.68%   |
| Seagate ST2000DX002-2DV164 2TB      | 2        | 4      | 0.68%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 2      | 0.68%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 2      | 0.68%   |
| Seagate ST1000DX001-1NS162 1TB      | 2        | 4      | 0.68%   |
| Seagate ST1000DX001-1CM162 1TB      | 2        | 5      | 0.68%   |
| SanDisk SDSSDA120G 120GB            | 2        | 3      | 0.68%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 2        | 3      | 0.68%   |
| Samsung Electronics HD502HJ 500GB   | 2        | 2      | 0.68%   |
| Samsung Electronics HD322HJ 320GB   | 2        | 2      | 0.68%   |
| Samsung Electronics HD321KJ 320GB   | 2        | 2      | 0.68%   |
| Samsung Electronics HD160JJ 160GB   | 2        | 2      | 0.68%   |
| Samsung Electronics HD103UJ 1TB     | 2        | 2      | 0.68%   |
| Kingston SA400S37480G 480GB SSD     | 2        | 2      | 0.68%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 2      | 0.68%   |
| Fujitsu MHZ2160BH G2 160GB          | 2        | 4      | 0.68%   |
| A-DATA Technology SU800 256GB SSD   | 2        | 3      | 0.68%   |
| XPG SPECTRIX S40G 256GB             | 1        | 1      | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 2      | 0.34%   |
| WDC WDS2 40G2G0A-00JH 240GB SSD     | 1        | 1      | 0.34%   |
| WDC WD800JD-22JNC0 80GB             | 1        | 1      | 0.34%   |
| WDC WD800JD-00JNC0 80GB             | 1        | 1      | 0.34%   |
| WDC WD800JB-00JJA0 80GB             | 1        | 1      | 0.34%   |
| WDC WD800JB-00ETA0 80GB             | 1        | 1      | 0.34%   |
| WDC WD800BB-00JHC0 80GB             | 1        | 1      | 0.34%   |
| WDC WD5003ABYX-01WERA1 500GB        | 1        | 1      | 0.34%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1        | 1      | 0.34%   |
| WDC WD5000BPVT-24HXZT3 500GB        | 1        | 1      | 0.34%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1        | 1      | 0.34%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 2      | 0.34%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 0.34%   |
| WDC WD5000AAKX-07U6AA0 500GB        | 1        | 1      | 0.34%   |
| WDC WD5000AAKX-004EA0 500GB         | 1        | 1      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 91       | 125    | 33.46%  |
| WDC                   | 69       | 118    | 25.37%  |
| Samsung Electronics   | 24       | 29     | 8.82%   |
| Hitachi               | 15       | 22     | 5.51%   |
| Toshiba               | 11       | 12     | 4.04%   |
| A-DATA Technology     | 9        | 10     | 3.31%   |
| SanDisk               | 8        | 10     | 2.94%   |
| Kingston              | 7        | 7      | 2.57%   |
| GOODRAM               | 7        | 7      | 2.57%   |
| ASMT                  | 5        | 6      | 1.84%   |
| Fujitsu               | 4        | 6      | 1.47%   |
| Maxtor                | 3        | 3      | 1.1%    |
| Hewlett-Packard       | 3        | 3      | 1.1%    |
| SPCC                  | 2        | 2      | 0.74%   |
| HGST                  | 2        | 2      | 0.74%   |
| Apacer                | 2        | 4      | 0.74%   |
| XPG                   | 1        | 1      | 0.37%   |
| WDC WDS2              | 1        | 1      | 0.37%   |
| WD MediaMax           | 1        | 2      | 0.37%   |
| SSSTC                 | 1        | 1      | 0.37%   |
| Realtek Semiconductor | 1        | 1      | 0.37%   |
| LITEONIT              | 1        | 1      | 0.37%   |
| LITEON                | 1        | 1      | 0.37%   |
| Intel                 | 1        | 1      | 0.37%   |
| Corsair               | 1        | 2      | 0.37%   |
| Unknown               | 1        | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 91       | 125    | 41.55%  |
| WDC                 | 68       | 116    | 31.05%  |
| Samsung Electronics | 21       | 26     | 9.59%   |
| Hitachi             | 15       | 22     | 6.85%   |
| Toshiba             | 11       | 12     | 5.02%   |
| Fujitsu             | 4        | 6      | 1.83%   |
| Maxtor              | 3        | 3      | 1.37%   |
| HGST                | 2        | 2      | 0.91%   |
| WD MediaMax         | 1        | 2      | 0.46%   |
| Hewlett-Packard     | 1        | 1      | 0.46%   |
| ASMT                | 1        | 2      | 0.46%   |
| Unknown             | 1        | 1      | 0.46%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 194      | 318    | 78.54%  |
| SSD  | 47       | 54     | 19.03%  |
| NVMe | 6        | 6      | 2.43%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB       | 1        | 1      | 16.67%  |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 16.67%  |
| Toshiba DT01ACA100 1TB            | 1        | 2      | 16.67%  |
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 16.67%  |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 16.67%  |
| OCZ-AGIL ITY3 120GB SSD           | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 33.33%  |
| Toshiba             | 1        | 2      | 16.67%  |
| Seagate             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| OCZ-AGIL            | 1        | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 734      | 2145   | 45.99%  |
| Works    | 617      | 1700   | 38.66%  |
| Malfunc  | 239      | 378    | 14.97%  |
| Failed   | 6        | 7      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 839      | 42.63%  |
| AMD                            | 462      | 23.48%  |
| Samsung Electronics            | 113      | 5.74%   |
| JMicron Technology             | 81       | 4.12%   |
| ASMedia Technology             | 78       | 3.96%   |
| Nvidia                         | 66       | 3.35%   |
| ADATA Technology               | 55       | 2.79%   |
| Phison Electronics             | 49       | 2.49%   |
| Marvell Technology Group       | 39       | 1.98%   |
| Kingston Technology Company    | 32       | 1.63%   |
| SanDisk                        | 21       | 1.07%   |
| Realtek Semiconductor          | 19       | 0.97%   |
| Silicon Motion                 | 18       | 0.91%   |
| Lite-On Technology             | 16       | 0.81%   |
| VIA Technologies               | 15       | 0.76%   |
| LSI Logic / Symbios Logic      | 9        | 0.46%   |
| SK hynix                       | 8        | 0.41%   |
| Micron/Crucial Technology      | 8        | 0.41%   |
| Shenzhen Longsys Electronics   | 7        | 0.36%   |
| KIOXIA                         | 7        | 0.36%   |
| Silicon Image                  | 5        | 0.25%   |
| Micron Technology              | 4        | 0.2%    |
| Broadcom / LSI                 | 3        | 0.15%   |
| Unknown                        | 2        | 0.1%    |
| Union Memory (Shenzhen)        | 2        | 0.1%    |
| ULi Electronics                | 2        | 0.1%    |
| Solid State Storage Technology | 2        | 0.1%    |
| Toshiba America Info Systems   | 1        | 0.05%   |
| Tekram Technology              | 1        | 0.05%   |
| Lite-On IT Corp. / Plextor     | 1        | 0.05%   |
| Integrated Technology Express  | 1        | 0.05%   |
| Hewlett-Packard                | 1        | 0.05%   |
| Broadcom                       | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 264      | 10.25%  |
| AMD 400 Series Chipset SATA Controller                                                  | 130      | 5.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 110      | 4.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 84       | 3.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 80       | 3.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 76       | 2.95%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 76       | 2.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 71       | 2.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 69       | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 67       | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 66       | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 61       | 2.37%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 58       | 2.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 54       | 2.1%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 53       | 2.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 48       | 1.86%   |
| Intel SATA Controller [RAID mode]                                                       | 43       | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 42       | 1.63%   |
| Nvidia MCP61 SATA Controller                                                            | 37       | 1.44%   |
| Nvidia MCP61 IDE                                                                        | 36       | 1.4%    |
| AMD 500 Series Chipset SATA Controller                                                  | 32       | 1.24%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 30       | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 28       | 1.09%   |
| Phison E12 NVMe Controller                                                              | 26       | 1.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 22       | 0.85%   |
| Kingston Company A2000 NVMe SSD                                                         | 21       | 0.82%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 21       | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 20       | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20       | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20       | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                                  | 19       | 0.74%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 18       | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 17       | 0.66%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 16       | 0.62%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 16       | 0.62%   |
| AMD FCH SATA Controller D                                                               | 16       | 0.62%   |
| JMicron JMB368 IDE controller                                                           | 15       | 0.58%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 15       | 0.58%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 15       | 0.58%   |
| AMD X370 Series Chipset SATA Controller                                                 | 15       | 0.58%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 15       | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 14       | 0.54%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 14       | 0.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 14       | 0.54%   |
| Lite-On Non-Volatile memory controller                                                  | 13       | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 13       | 0.5%    |
| AMD FCH IDE Controller                                                                  | 13       | 0.5%    |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 12       | 0.47%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 12       | 0.47%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 12       | 0.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 12       | 0.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 12       | 0.47%   |
| Samsung NVMe SSD Controller 980                                                         | 11       | 0.43%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 11       | 0.43%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 10       | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 10       | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 10       | 0.39%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 9        | 0.35%   |
| Nvidia MCP55 SATA Controller                                                            | 9        | 0.35%   |
| Nvidia MCP55 IDE                                                                        | 9        | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1053     | 54.42%  |
| IDE  | 465      | 24.03%  |
| NVMe | 333      | 17.21%  |
| RAID | 66       | 3.41%   |
| SAS  | 10       | 0.52%   |
| SCSI | 8        | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 848      | 61.54%  |
| AMD          | 528      | 38.32%  |
| PowerMac11,2 | 1        | 0.07%   |
| PowerBook6,7 | 1        | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 31       | 2.23%   |
| AMD Ryzen 5 3600 6-Core Processor           | 31       | 2.23%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 23       | 1.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 21       | 1.51%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 19       | 1.37%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 17       | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 1.15%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 16       | 1.15%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 16       | 1.15%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 16       | 1.15%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 15       | 1.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15       | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 14       | 1.01%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 13       | 0.94%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 13       | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 13       | 0.94%   |
| AMD Phenom II X4 955 Processor              | 13       | 0.94%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 12       | 0.86%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 10       | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 10       | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 10       | 0.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 10       | 0.72%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 10       | 0.72%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 10       | 0.72%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 10       | 0.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 0.65%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 9        | 0.65%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 9        | 0.65%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 9        | 0.65%   |
| AMD FX-8350 Eight-Core Processor            | 9        | 0.65%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 8        | 0.58%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 0.58%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 8        | 0.58%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 8        | 0.58%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 8        | 0.58%   |
| AMD FX-8300 Eight-Core Processor            | 8        | 0.58%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 7        | 0.5%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 7        | 0.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 7        | 0.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 7        | 0.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 7        | 0.5%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 7        | 0.5%    |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 7        | 0.5%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 7        | 0.5%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 7        | 0.5%    |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 7        | 0.5%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 7        | 0.5%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 6        | 0.43%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 6        | 0.43%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 0.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 6        | 0.43%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 6        | 0.43%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 6        | 0.43%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 6        | 0.43%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 6        | 0.43%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 6        | 0.43%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 6        | 0.43%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 6        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 260      | 18.75%  |
| Intel Core i7           | 134      | 9.66%   |
| AMD Ryzen 5             | 129      | 9.3%    |
| Intel Core i3           | 83       | 5.98%   |
| Intel Xeon              | 71       | 5.12%   |
| Intel Core 2 Duo        | 69       | 4.97%   |
| AMD Ryzen 7             | 65       | 4.69%   |
| Intel Core 2 Quad       | 53       | 3.82%   |
| AMD FX                  | 46       | 3.32%   |
| Intel Pentium           | 39       | 2.81%   |
| Intel Celeron           | 36       | 2.6%    |
| AMD Ryzen 9             | 33       | 2.38%   |
| AMD Phenom II X4        | 32       | 2.31%   |
| AMD Athlon 64 X2        | 30       | 2.16%   |
| AMD Ryzen 3             | 28       | 2.02%   |
| Intel Pentium Dual-Core | 27       | 1.95%   |
| AMD Athlon II X2        | 26       | 1.87%   |
| Other                   | 20       | 1.44%   |
| Intel Core 2            | 20       | 1.44%   |
| AMD Athlon II X4        | 16       | 1.15%   |
| AMD A10                 | 16       | 1.15%   |
| AMD A8                  | 14       | 1.01%   |
| Intel Pentium Dual      | 13       | 0.94%   |
| Intel Core i9           | 10       | 0.72%   |
| AMD A6                  | 10       | 0.72%   |
| AMD Ryzen Threadripper  | 9        | 0.65%   |
| AMD Athlon              | 8        | 0.58%   |
| Intel Pentium D         | 7        | 0.5%    |
| AMD GX                  | 7        | 0.5%    |
| AMD Athlon 64           | 7        | 0.5%    |
| Intel Pentium 4         | 6        | 0.43%   |
| AMD Sempron             | 6        | 0.43%   |
| AMD Phenom II X6        | 6        | 0.43%   |
| AMD A4                  | 6        | 0.43%   |
| AMD Phenom II X2        | 5        | 0.36%   |
| AMD Athlon II X3        | 5        | 0.36%   |
| AMD Athlon Dual Core    | 5        | 0.36%   |
| Intel Pentium Gold      | 4        | 0.29%   |
| AMD Phenom              | 4        | 0.29%   |
| Intel Atom              | 3        | 0.22%   |
| AMD Ryzen 5 PRO         | 3        | 0.22%   |
| AMD G                   | 3        | 0.22%   |
| AMD E                   | 3        | 0.22%   |
| Intel Genuine           | 2        | 0.14%   |
| Intel Core 2 Extreme    | 1        | 0.07%   |
| AMD Turion 64 X2 Mobile | 1        | 0.07%   |
| AMD Ryzen 3 PRO         | 1        | 0.07%   |
| AMD PRO A10             | 1        | 0.07%   |
| AMD Phenom II X3        | 1        | 0.07%   |
| AMD E1                  | 1        | 0.07%   |
| AMD Athlon X4           | 1        | 0.07%   |
| AMD Athlon X2           | 1        | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 573      | 40.96%  |
| 2       | 371      | 26.52%  |
| 6       | 198      | 14.15%  |
| 8       | 102      | 7.29%   |
| Unknown | 45       | 3.22%   |
| 12      | 36       | 2.57%   |
| 1       | 33       | 2.36%   |
| 3       | 19       | 1.36%   |
| 16      | 11       | 0.79%   |
| 10      | 7        | 0.5%    |
| 32      | 2        | 0.14%   |
| 24      | 2        | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1361     | 98.69%  |
| 2      | 18       | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 734      | 52.65%  |
| 2       | 615      | 44.12%  |
| Unknown | 45       | 3.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1360     | 98.34%  |
| Unknown        | 17       | 1.23%   |
| 32-bit         | 6        | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 258      | 17.98%  |
| 0x306c3    | 132      | 9.2%    |
| 0x1067a    | 95       | 6.62%   |
| 0x306a9    | 90       | 6.27%   |
| 0x206a7    | 69       | 4.81%   |
| 0x0800820d | 56       | 3.9%    |
| 0x506e3    | 49       | 3.41%   |
| 0x08701021 | 45       | 3.14%   |
| 0x010000c8 | 44       | 3.07%   |
| 0x906ea    | 35       | 2.44%   |
| 0x906e9    | 35       | 2.44%   |
| 0x08701013 | 25       | 1.74%   |
| 0x06000852 | 22       | 1.53%   |
| 0x6fb      | 21       | 1.46%   |
| 0x10676    | 20       | 1.39%   |
| 0x08001138 | 20       | 1.39%   |
| 0x06001119 | 20       | 1.39%   |
| 0x6fd      | 16       | 1.11%   |
| 0x106e5    | 15       | 1.05%   |
| 0x10677    | 15       | 1.05%   |
| 0xa0653    | 14       | 0.98%   |
| 0x6f6      | 14       | 0.98%   |
| 0x06003106 | 14       | 0.98%   |
| 0x206c2    | 13       | 0.91%   |
| 0x0a201016 | 11       | 0.77%   |
| 0x08108109 | 11       | 0.77%   |
| 0x08101016 | 11       | 0.77%   |
| 0xa0655    | 10       | 0.7%    |
| 0x08001137 | 10       | 0.7%    |
| 0x010000db | 10       | 0.7%    |
| 0xa0671    | 9        | 0.63%   |
| 0x0a201009 | 9        | 0.63%   |
| 0x206d7    | 8        | 0.56%   |
| 0x906ec    | 7        | 0.49%   |
| 0x906eb    | 7        | 0.49%   |
| 0x6f2      | 7        | 0.49%   |
| 0x306e4    | 7        | 0.49%   |
| 0x010000c7 | 7        | 0.49%   |
| 0x010000b6 | 7        | 0.49%   |
| 0x906ed    | 6        | 0.42%   |
| 0x306f2    | 6        | 0.42%   |
| 0x0810100b | 6        | 0.42%   |
| 0x0700010f | 6        | 0.42%   |
| 0x0600063e | 6        | 0.42%   |
| 0x03000027 | 6        | 0.42%   |
| 0x90672    | 5        | 0.35%   |
| 0x08001129 | 5        | 0.35%   |
| 0x010000dc | 5        | 0.35%   |
| 0x106a5    | 4        | 0.28%   |
| 0x0a50000c | 4        | 0.28%   |
| 0x0600084f | 4        | 0.28%   |
| 0xf29      | 3        | 0.21%   |
| 0x706a1    | 3        | 0.21%   |
| 0x506c9    | 3        | 0.21%   |
| 0x406f1    | 3        | 0.21%   |
| 0x406c3    | 3        | 0.21%   |
| 0x20655    | 3        | 0.21%   |
| 0x0800820b | 3        | 0.21%   |
| 0x08008206 | 3        | 0.21%   |
| 0x0700010b | 3        | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 153      | 11.02%  |
| Penryn           | 137      | 9.87%   |
| KabyLake         | 106      | 7.64%   |
| IvyBridge        | 106      | 7.64%   |
| K10              | 95       | 6.84%   |
| Zen 2            | 94       | 6.77%   |
| SandyBridge      | 90       | 6.48%   |
| Zen+             | 84       | 6.05%   |
| Core             | 71       | 5.12%   |
| Skylake          | 63       | 4.54%   |
| Zen              | 61       | 4.39%   |
| Piledriver       | 56       | 4.03%   |
| K8 Hammer        | 50       | 3.6%    |
| Zen 3            | 31       | 2.23%   |
| CometLake        | 27       | 1.95%   |
| Nehalem          | 24       | 1.73%   |
| Westmere         | 20       | 1.44%   |
| NetBurst         | 15       | 1.08%   |
| Unknown          | 15       | 1.08%   |
| Steamroller      | 14       | 1.01%   |
| Jaguar           | 12       | 0.86%   |
| Bulldozer        | 11       | 0.79%   |
| Silvermont       | 10       | 0.72%   |
| K10 Llano        | 7        | 0.5%    |
| Bobcat           | 7        | 0.5%    |
| Icelake          | 6        | 0.43%   |
| Alderlake Hybrid | 6        | 0.43%   |
| Goldmont plus    | 4        | 0.29%   |
| Broadwell        | 4        | 0.29%   |
| Goldmont         | 3        | 0.22%   |
| Excavator        | 3        | 0.22%   |
| Puma             | 2        | 0.14%   |
| P6               | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 674      | 45.98%  |
| AMD                        | 450      | 30.7%   |
| Intel                      | 339      | 23.12%  |
| S3 Graphics                | 1        | 0.07%   |
| Matrox Electronics Systems | 1        | 0.07%   |
| ASPEED Technology          | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 78       | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 72       | 4.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 47       | 3.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 34       | 2.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 34       | 2.24%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 33       | 2.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 31       | 2.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 28       | 1.84%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 26       | 1.71%   |
| Intel HD Graphics 530                                                       | 24       | 1.58%   |
| Nvidia GK208B [GeForce GT 710]                                              | 23       | 1.51%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 23       | 1.51%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 22       | 1.45%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 20       | 1.32%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 18       | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 18       | 1.18%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 17       | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 17       | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 17       | 1.12%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 16       | 1.05%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 16       | 1.05%   |
| Nvidia GF119 [GeForce GT 610]                                               | 15       | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 15       | 0.99%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 15       | 0.99%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 14       | 0.92%   |
| Intel HD Graphics 630                                                       | 14       | 0.92%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 14       | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 13       | 0.86%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 13       | 0.86%   |
| Nvidia GF108 [GeForce GT 630]                                               | 12       | 0.79%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 12       | 0.79%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 12       | 0.79%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 11       | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 11       | 0.72%   |
| AMD RS780L [Radeon 3000]                                                    | 11       | 0.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 11       | 0.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 10       | 0.66%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 10       | 0.66%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 10       | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 9        | 0.59%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 9        | 0.59%   |
| AMD RS880 [Radeon HD 4200]                                                  | 9        | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 8        | 0.53%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 8        | 0.53%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 8        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 7        | 0.46%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 7        | 0.46%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 7        | 0.46%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 7        | 0.46%   |
| Nvidia GF108 [GeForce GT 430]                                               | 7        | 0.46%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 0.46%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 7        | 0.46%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 7        | 0.46%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 7        | 0.46%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 6        | 0.39%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 6        | 0.39%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 0.39%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 6        | 0.39%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 6        | 0.39%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 6        | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 638      | 45.34%  |
| 1 x AMD         | 415      | 29.5%   |
| 1 x Intel       | 285      | 20.26%  |
| Intel + Nvidia  | 19       | 1.35%   |
| 2 x AMD         | 17       | 1.21%   |
| AMD + Nvidia    | 12       | 0.85%   |
| Intel + AMD     | 9        | 0.64%   |
| 2 x Nvidia      | 4        | 0.28%   |
| 3 x AMD         | 2        | 0.14%   |
| 2 x Intel       | 2        | 0.14%   |
| Other           | 1        | 0.07%   |
| 1 x S3 Graphics | 1        | 0.07%   |
| Nvidia + ASPEED | 1        | 0.07%   |
| 1 x Matrox      | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1006     | 70.65%  |
| Proprietary | 350      | 24.58%  |
| Unknown     | 68       | 4.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 454      | 31.25%  |
| 1.01-2.0   | 227      | 15.62%  |
| 0.51-1.0   | 215      | 14.8%   |
| 0.01-0.5   | 211      | 14.52%  |
| 7.01-8.0   | 134      | 9.22%   |
| 3.01-4.0   | 118      | 8.12%   |
| 5.01-6.0   | 60       | 4.13%   |
| 8.01-16.0  | 22       | 1.51%   |
| 2.01-3.0   | 10       | 0.69%   |
| 16.01-24.0 | 2        | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 253      | 17.14%  |
| Goldstar                | 173      | 11.72%  |
| Dell                    | 151      | 10.23%  |
| Philips                 | 100      | 6.78%   |
| Iiyama                  | 84       | 5.69%   |
| BenQ                    | 83       | 5.62%   |
| Hewlett-Packard         | 82       | 5.56%   |
| Acer                    | 80       | 5.42%   |
| AOC                     | 60       | 4.07%   |
| Eizo                    | 47       | 3.18%   |
| NEC Computers           | 45       | 3.05%   |
| Ancor Communications    | 40       | 2.71%   |
| LG Electronics          | 29       | 1.96%   |
| Fujitsu Siemens         | 24       | 1.63%   |
| Sony                    | 22       | 1.49%   |
| Lenovo                  | 21       | 1.42%   |
| Unknown                 | 15       | 1.02%   |
| ASUSTek Computer        | 12       | 0.81%   |
| Idek Iiyama             | 11       | 0.75%   |
| ViewSonic               | 10       | 0.68%   |
| Toshiba                 | 8        | 0.54%   |
| Panasonic               | 8        | 0.54%   |
| Hyundai ImageQuest      | 7        | 0.47%   |
| Gateway                 | 7        | 0.47%   |
| Medion                  | 6        | 0.41%   |
| Belinea                 | 6        | 0.41%   |
| MSI                     | 5        | 0.34%   |
| Vestel Elektronik       | 4        | 0.27%   |
| IBM                     | 4        | 0.27%   |
| Gigabyte Technology     | 4        | 0.27%   |
| Vestel                  | 3        | 0.2%    |
| TCL                     | 3        | 0.2%    |
| Sharp                   | 3        | 0.2%    |
| RTK                     | 3        | 0.2%    |
| Onkyo                   | 3        | 0.2%    |
| Xiaomi                  | 2        | 0.14%   |
| Valve                   | 2        | 0.14%   |
| Tech Concepts           | 2        | 0.14%   |
| S2-Tek                  | 2        | 0.14%   |
| Plain Tree Systems      | 2        | 0.14%   |
| Packard Bell            | 2        | 0.14%   |
| OEM                     | 2        | 0.14%   |
| KTC                     | 2        | 0.14%   |
| INFOTRONIC              | 2        | 0.14%   |
| Huion                   | 2        | 0.14%   |
| HJW                     | 2        | 0.14%   |
| Hitachi                 | 2        | 0.14%   |
| FUS                     | 2        | 0.14%   |
| Chi Mei Optoelectronics | 2        | 0.14%   |
| Arnos Instruments       | 2        | 0.14%   |
| AGO                     | 2        | 0.14%   |
| Unknown                 | 2        | 0.14%   |
| YOC                     | 1        | 0.07%   |
| Unknown (XXX)           | 1        | 0.07%   |
| UMC                     | 1        | 0.07%   |
| Sunplus                 | 1        | 0.07%   |
| Sceptre Tech            | 1        | 0.07%   |
| Orion                   | 1        | 0.07%   |
| OPT                     | 1        | 0.07%   |
| NECCI                   | 1        | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                  | 13       | 0.82%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 9        | 0.56%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 9        | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 8        | 0.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 7        | 0.44%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 7        | 0.44%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 6        | 0.38%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 6        | 0.38%   |
| Eizo EV2316W ENC2394 1920x1080 510x287mm 23.0-inch                     | 6        | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 6        | 0.38%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                     | 6        | 0.38%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 5        | 0.31%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch                | 5        | 0.31%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                  | 5        | 0.31%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 509x286mm 23.0-inch           | 5        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 5        | 0.31%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 5        | 0.31%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                   | 5        | 0.31%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 5        | 0.31%   |
| Dell U2212HM DELD047 1920x1080 475x267mm 21.5-inch                     | 5        | 0.31%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 5        | 0.31%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 4        | 0.25%   |
| Toshiba TV TSB0108 1920x1080 708x398mm 32.0-inch                       | 4        | 0.25%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch      | 4        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 4        | 0.25%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                      | 4        | 0.25%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 4        | 0.25%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 4        | 0.25%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 4        | 0.25%   |
| NEC Computers EA223WM NEC6890 1680x1050 474x296mm 22.0-inch            | 4        | 0.25%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 4        | 0.25%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                    | 4        | 0.25%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                   | 4        | 0.25%   |
| Goldstar 24MP55 GSM5A20 1920x1080 510x290mm 23.1-inch                  | 4        | 0.25%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                      | 4        | 0.25%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 4        | 0.25%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                      | 4        | 0.25%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 4        | 0.25%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                       | 3        | 0.19%   |
| Sony TV SNY6604 1920x1080                                              | 3        | 0.19%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch   | 3        | 0.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 3        | 0.19%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch    | 3        | 0.19%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch     | 3        | 0.19%   |
| Samsung Electronics SMEX2220 SAM0685 1920x1080 477x268mm 21.5-inch     | 3        | 0.19%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch     | 3        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 3        | 0.19%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 3        | 0.19%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                 | 3        | 0.19%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 509x286mm 23.0-inch                | 3        | 0.19%   |
| Philips 200VW PHL0852 1680x1050 474x296mm 22.0-inch                    | 3        | 0.19%   |
| NEC Computers LCD73V NEC66C2 1280x1024 338x270mm 17.0-inch             | 3        | 0.19%   |
| NEC Computers LCD22WV NEC671E 1680x1050 465x290mm 21.6-inch            | 3        | 0.19%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch           | 3        | 0.19%   |
| NEC Computers EA244WMi NEC68D5 1920x1200 519x324mm 24.1-inch           | 3        | 0.19%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 3        | 0.19%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                     | 3        | 0.19%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch              | 3        | 0.19%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 510x290mm 23.1-inch               | 3        | 0.19%   |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                  | 3        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 655      | 45.2%   |
| 1280x1024 (SXGA)   | 158      | 10.9%   |
| 1680x1050 (WSXGA+) | 108      | 7.45%   |
| 2560x1440 (QHD)    | 92       | 6.35%   |
| 3840x2160 (4K)     | 83       | 5.73%   |
| 1920x1200 (WUXGA)  | 72       | 4.97%   |
| 1440x900 (WXGA+)   | 60       | 4.14%   |
| 1366x768 (WXGA)    | 31       | 2.14%   |
| Unknown            | 31       | 2.14%   |
| 2560x1080          | 21       | 1.45%   |
| 3440x1440          | 18       | 1.24%   |
| 1600x1200          | 16       | 1.1%    |
| 3840x1080          | 15       | 1.04%   |
| 1360x768           | 15       | 1.04%   |
| 1024x768 (XGA)     | 13       | 0.9%    |
| 1600x900 (HD+)     | 9        | 0.62%   |
| 1920x540           | 7        | 0.48%   |
| 2048x1152          | 4        | 0.28%   |
| 5120x1440          | 3        | 0.21%   |
| 3200x1080          | 3        | 0.21%   |
| 2560x1600          | 3        | 0.21%   |
| 1280x960           | 3        | 0.21%   |
| 1280x720 (HD)      | 3        | 0.21%   |
| 3840x1200          | 2        | 0.14%   |
| 3600x1080          | 2        | 0.14%   |
| 2288x1287          | 2        | 0.14%   |
| 720x576            | 1        | 0.07%   |
| 720x480            | 1        | 0.07%   |
| 6400x1440          | 1        | 0.07%   |
| 5760x1200          | 1        | 0.07%   |
| 5120x2160          | 1        | 0.07%   |
| 5120x1080          | 1        | 0.07%   |
| 5040x1050          | 1        | 0.07%   |
| 4920x1200          | 1        | 0.07%   |
| 4480x1600          | 1        | 0.07%   |
| 4480x1440          | 1        | 0.07%   |
| 4480x1200          | 1        | 0.07%   |
| 3840x1600          | 1        | 0.07%   |
| 3600x1200          | 1        | 0.07%   |
| 3200x1200          | 1        | 0.07%   |
| 3040x1050          | 1        | 0.07%   |
| 2640x1024          | 1        | 0.07%   |
| 2384x768           | 1        | 0.07%   |
| 1400x1050          | 1        | 0.07%   |
| 1280x800 (WXGA)    | 1        | 0.07%   |
| 1280x768           | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 210      | 14.21%  |
| 21      | 191      | 12.92%  |
| 23      | 182      | 12.31%  |
| Unknown | 166      | 11.23%  |
| 27      | 164      | 11.1%   |
| 19      | 127      | 8.59%   |
| 17      | 73       | 4.94%   |
| 22      | 72       | 4.87%   |
| 18      | 45       | 3.04%   |
| 31      | 34       | 2.3%    |
| 34      | 30       | 2.03%   |
| 20      | 30       | 2.03%   |
| 72      | 17       | 1.15%   |
| 32      | 15       | 1.01%   |
| 15      | 15       | 1.01%   |
| 84      | 14       | 0.95%   |
| 25      | 14       | 0.95%   |
| 54      | 13       | 0.88%   |
| 65      | 7        | 0.47%   |
| 49      | 6        | 0.41%   |
| 46      | 5        | 0.34%   |
| 42      | 5        | 0.34%   |
| 40      | 5        | 0.34%   |
| 33      | 5        | 0.34%   |
| 28      | 5        | 0.34%   |
| 39      | 4        | 0.27%   |
| 48      | 3        | 0.2%    |
| 14      | 3        | 0.2%    |
| 142     | 2        | 0.14%   |
| 55      | 2        | 0.14%   |
| 50      | 2        | 0.14%   |
| 37      | 2        | 0.14%   |
| 35      | 2        | 0.14%   |
| 29      | 2        | 0.14%   |
| 26      | 2        | 0.14%   |
| 59      | 1        | 0.07%   |
| 52      | 1        | 0.07%   |
| 47      | 1        | 0.07%   |
| 12      | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 527      | 36.62%  |
| 401-500        | 379      | 26.34%  |
| Unknown        | 166      | 11.54%  |
| 351-400        | 86       | 5.98%   |
| 301-350        | 85       | 5.91%   |
| 601-700        | 51       | 3.54%   |
| 701-800        | 50       | 3.47%   |
| 1001-1500      | 40       | 2.78%   |
| 1501-2000      | 31       | 2.15%   |
| 801-900        | 13       | 0.9%    |
| 901-1000       | 5        | 0.35%   |
| 201-300        | 4        | 0.28%   |
| More than 2000 | 2        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 767      | 55.42%  |
| 16/10   | 223      | 16.11%  |
| Unknown | 153      | 11.05%  |
| 5/4     | 146      | 10.55%  |
| 21/9    | 34       | 2.46%   |
| 4/3     | 30       | 2.17%   |
| 3/2     | 16       | 1.16%   |
| 32/9    | 9        | 0.65%   |
| 6/5     | 4        | 0.29%   |
| 1.00    | 2        | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 510      | 35.1%   |
| 151-200        | 213      | 14.66%  |
| 301-350        | 166      | 11.42%  |
| Unknown        | 166      | 11.42%  |
| 141-150        | 101      | 6.95%   |
| 251-300        | 97       | 6.68%   |
| 351-500        | 91       | 6.26%   |
| More than 1000 | 61       | 4.2%    |
| 501-1000       | 29       | 2%      |
| 101-110        | 12       | 0.83%   |
| 111-120        | 3        | 0.21%   |
| 91-100         | 3        | 0.21%   |
| 71-80          | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 847      | 61.38%  |
| 101-120 | 257      | 18.62%  |
| Unknown | 166      | 12.03%  |
| 1-50    | 58       | 4.2%    |
| 121-160 | 34       | 2.46%   |
| 161-240 | 18       | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1122     | 79.57%  |
| 2     | 192      | 13.62%  |
| 0     | 64       | 4.54%   |
| 3     | 26       | 1.84%   |
| 4     | 6        | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 834      | 42.55%  |
| Intel                                  | 460      | 23.47%  |
| Qualcomm Atheros                       | 158      | 8.06%   |
| Broadcom                               | 65       | 3.32%   |
| TP-Link                                | 52       | 2.65%   |
| Nvidia                                 | 49       | 2.5%    |
| Ralink Technology                      | 47       | 2.4%    |
| Qualcomm Atheros Communications        | 32       | 1.63%   |
| Ralink                                 | 31       | 1.58%   |
| Microsoft                              | 25       | 1.28%   |
| Huawei Technologies                    | 23       | 1.17%   |
| Marvell Technology Group               | 22       | 1.12%   |
| Broadcom Limited                       | 18       | 0.92%   |
| ASUSTek Computer                       | 18       | 0.92%   |
| Xiaomi                                 | 16       | 0.82%   |
| Samsung Electronics                    | 13       | 0.66%   |
| D-Link                                 | 8        | 0.41%   |
| Aquantia                               | 8        | 0.41%   |
| Edimax Technology                      | 7        | 0.36%   |
| VIA Technologies                       | 6        | 0.31%   |
| Motorola PCS                           | 5        | 0.26%   |
| Sony Ericsson Mobile Communications AB | 4        | 0.2%    |
| Realtek                                | 4        | 0.2%    |
| NetGear                                | 4        | 0.2%    |
| MediaTek                               | 4        | 0.2%    |
| Sagem                                  | 3        | 0.15%   |
| D-Link System                          | 3        | 0.15%   |
| ZyXEL Communications                   | 2        | 0.1%    |
| ZyDAS                                  | 2        | 0.1%    |
| Research In Motion                     | 2        | 0.1%    |
| QLogic                                 | 2        | 0.1%    |
| OnePlus Technology (Shenzhen)          | 2        | 0.1%    |
| Loupedeck                              | 2        | 0.1%    |
| HTC (High Tech Computer)               | 2        | 0.1%    |
| Apple                                  | 2        | 0.1%    |
| 3Com                                   | 2        | 0.1%    |
| ZTE WCDMA Technologies MSM             | 1        | 0.05%   |
| Wacom                                  | 1        | 0.05%   |
| Texas Instruments                      | 1        | 0.05%   |
| Seeed Technology                       | 1        | 0.05%   |
| Raspberry Pi                           | 1        | 0.05%   |
| OPPO Electronics                       | 1        | 0.05%   |
| NetXen Incorporated                    | 1        | 0.05%   |
| Mellanox Technologies                  | 1        | 0.05%   |
| Linksys                                | 1        | 0.05%   |
| Lenovo                                 | 1        | 0.05%   |
| IMC Networks                           | 1        | 0.05%   |
| IBM                                    | 1        | 0.05%   |
| GreenWave Reality                      | 1        | 0.05%   |
| Google                                 | 1        | 0.05%   |
| Foxconn / Hon Hai                      | 1        | 0.05%   |
| Cisco Systems                          | 1        | 0.05%   |
| Belkin Components                      | 1        | 0.05%   |
| AVM                                    | 1        | 0.05%   |
| ASIX Electronics                       | 1        | 0.05%   |
| Arduino SA                             | 1        | 0.05%   |
| AMD                                    | 1        | 0.05%   |
| ADMtek                                 | 1        | 0.05%   |
| Accton Technology                      | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 689      | 32.27%  |
| Intel I211 Gigabit Network Connection                                         | 65       | 3.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 65       | 3.04%   |
| Intel Ethernet Connection (2) I219-V                                          | 46       | 2.15%   |
| Intel Wi-Fi 6 AX200                                                           | 39       | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                             | 38       | 1.78%   |
| Intel 82579V Gigabit Network Connection                                       | 34       | 1.59%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 34       | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 31       | 1.45%   |
| Nvidia MCP61 Ethernet                                                         | 30       | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 29       | 1.36%   |
| Intel Ethernet Connection I217-LM                                             | 29       | 1.36%   |
| Intel Ethernet Connection (7) I219-V                                          | 27       | 1.26%   |
| TP-Link TL-WN722N v2                                                          | 24       | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                               | 23       | 1.08%   |
| Ralink MT7601U Wireless Adapter                                               | 20       | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 20       | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 19       | 0.89%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 18       | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 17       | 0.8%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 17       | 0.8%    |
| Intel Wireless-AC 9260                                                        | 17       | 0.8%    |
| Intel Ethernet Connection (2) I218-V                                          | 16       | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 14       | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 14       | 0.66%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 14       | 0.66%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 13       | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 12       | 0.56%   |
| Ralink RT5370 Wireless Adapter                                                | 12       | 0.56%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 12       | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 12       | 0.56%   |
| Intel Ethernet Connection I217-V                                              | 12       | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 12       | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 11       | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 11       | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 11       | 0.52%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 11       | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 10       | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 10       | 0.47%   |
| Intel Ethernet Controller I225-V                                              | 10       | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 10       | 0.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 10       | 0.47%   |
| Intel 82574L Gigabit Network Connection                                       | 9        | 0.42%   |
| Huawei Modem/Networkcard                                                      | 9        | 0.42%   |
| Huawei E353/E3131                                                             | 9        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 9        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 8        | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 8        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 8        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 8        | 0.37%   |
| Intel Wireless 7260                                                           | 8        | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 7        | 0.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 7        | 0.33%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 7        | 0.33%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 7        | 0.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7        | 0.33%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 7        | 0.33%   |
| Nvidia MCP55 Ethernet                                                         | 7        | 0.33%   |
| Intel Ethernet Connection (14) I219-V                                         | 7        | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 7        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 119      | 20.73%  |
| Realtek Semiconductor           | 114      | 19.86%  |
| Qualcomm Atheros                | 74       | 12.89%  |
| TP-Link                         | 51       | 8.89%   |
| Ralink Technology               | 47       | 8.19%   |
| Qualcomm Atheros Communications | 32       | 5.57%   |
| Ralink                          | 31       | 5.4%    |
| Microsoft                       | 25       | 4.36%   |
| Broadcom                        | 20       | 3.48%   |
| ASUSTek Computer                | 18       | 3.14%   |
| D-Link                          | 8        | 1.39%   |
| Edimax Technology               | 7        | 1.22%   |
| Realtek                         | 4        | 0.7%    |
| NetGear                         | 4        | 0.7%    |
| Sagem                           | 3        | 0.52%   |
| MediaTek                        | 3        | 0.52%   |
| ZyXEL Communications            | 2        | 0.35%   |
| ZyDAS                           | 2        | 0.35%   |
| D-Link System                   | 2        | 0.35%   |
| Broadcom Limited                | 2        | 0.35%   |
| Wacom                           | 1        | 0.17%   |
| Linksys                         | 1        | 0.17%   |
| IMC Networks                    | 1        | 0.17%   |
| Belkin Components               | 1        | 0.17%   |
| AVM                             | 1        | 0.17%   |
| Accton Technology               | 1        | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 39       | 6.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 29       | 5.03%   |
| TP-Link TL-WN722N v2                                                          | 24       | 4.16%   |
| Qualcomm Atheros AR9271 802.11n                                               | 23       | 3.99%   |
| Ralink MT7601U Wireless Adapter                                               | 20       | 3.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 20       | 3.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 19       | 3.29%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 18       | 3.12%   |
| Intel Wireless-AC 9260                                                        | 17       | 2.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 14       | 2.43%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 14       | 2.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 13       | 2.25%   |
| Ralink RT5370 Wireless Adapter                                                | 12       | 2.08%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 12       | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 12       | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 10       | 1.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 10       | 1.73%   |
| Intel Wireless 7260                                                           | 8        | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 7        | 1.21%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 7        | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7        | 1.21%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 7        | 1.21%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 6        | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6        | 1.04%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 6        | 1.04%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 6        | 1.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 5        | 0.87%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 5        | 0.87%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 5        | 0.87%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 5        | 0.87%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 5        | 0.87%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 5        | 0.87%   |
| Microsoft XBOX ACC                                                            | 5        | 0.87%   |
| Intel Wireless 8260                                                           | 5        | 0.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 5        | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 4        | 0.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 4        | 0.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4        | 0.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 4        | 0.69%   |
| Realtek RTL8187 Wireless Adapter                                              | 4        | 0.69%   |
| Realtek 802.11ac NIC                                                          | 4        | 0.69%   |
| Realtek 802.11ac NIC                                                          | 4        | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 4        | 0.69%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 4        | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4        | 0.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 0.69%   |
| Sagem XG-76NA 802.11bg                                                        | 3        | 0.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 3        | 0.52%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 3        | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3        | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3        | 0.52%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                      | 3        | 0.52%   |
| Edimax 802.11ac WLAN Adapter                                                  | 3        | 0.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 0.52%   |
| ZyDAS ZD1211B 802.11g                                                         | 2        | 0.35%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 2        | 0.35%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                    | 2        | 0.35%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 2        | 0.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 0.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 2        | 0.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 784      | 52.41%  |
| Intel                                  | 404      | 27.01%  |
| Qualcomm Atheros                       | 89       | 5.95%   |
| Nvidia                                 | 49       | 3.28%   |
| Broadcom                               | 45       | 3.01%   |
| Marvell Technology Group               | 22       | 1.47%   |
| Xiaomi                                 | 16       | 1.07%   |
| Broadcom Limited                       | 16       | 1.07%   |
| Samsung Electronics                    | 13       | 0.87%   |
| Huawei Technologies                    | 13       | 0.87%   |
| Aquantia                               | 8        | 0.53%   |
| VIA Technologies                       | 6        | 0.4%    |
| Sony Ericsson Mobile Communications AB | 4        | 0.27%   |
| Motorola PCS                           | 4        | 0.27%   |
| TP-Link                                | 2        | 0.13%   |
| Research In Motion                     | 2        | 0.13%   |
| QLogic                                 | 2        | 0.13%   |
| HTC (High Tech Computer)               | 2        | 0.13%   |
| Apple                                  | 2        | 0.13%   |
| 3Com                                   | 2        | 0.13%   |
| OPPO Electronics                       | 1        | 0.07%   |
| NetXen Incorporated                    | 1        | 0.07%   |
| Mellanox Technologies                  | 1        | 0.07%   |
| MediaTek                               | 1        | 0.07%   |
| Lenovo                                 | 1        | 0.07%   |
| Google                                 | 1        | 0.07%   |
| Foxconn / Hon Hai                      | 1        | 0.07%   |
| D-Link System                          | 1        | 0.07%   |
| ASIX Electronics                       | 1        | 0.07%   |
| AMD                                    | 1        | 0.07%   |
| ADMtek                                 | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 689      | 44.92%  |
| Intel I211 Gigabit Network Connection                                         | 65       | 4.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 65       | 4.24%   |
| Intel Ethernet Connection (2) I219-V                                          | 46       | 3%      |
| Realtek RTL8125 2.5GbE Controller                                             | 38       | 2.48%   |
| Intel 82579V Gigabit Network Connection                                       | 34       | 2.22%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 34       | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 31       | 2.02%   |
| Nvidia MCP61 Ethernet                                                         | 30       | 1.96%   |
| Intel Ethernet Connection I217-LM                                             | 29       | 1.89%   |
| Intel Ethernet Connection (7) I219-V                                          | 27       | 1.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 17       | 1.11%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 17       | 1.11%   |
| Intel Ethernet Connection (2) I218-V                                          | 16       | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 14       | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 12       | 0.78%   |
| Intel Ethernet Connection I217-V                                              | 12       | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                         | 12       | 0.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 11       | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 11       | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 11       | 0.72%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 11       | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 10       | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 10       | 0.65%   |
| Intel Ethernet Controller I225-V                                              | 10       | 0.65%   |
| Intel 82574L Gigabit Network Connection                                       | 9        | 0.59%   |
| Huawei E353/E3131                                                             | 9        | 0.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 9        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 8        | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 8        | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 8        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 8        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 7        | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 7        | 0.46%   |
| Nvidia MCP55 Ethernet                                                         | 7        | 0.46%   |
| Intel Ethernet Connection (14) I219-V                                         | 7        | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 7        | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 6        | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 6        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 6        | 0.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 6        | 0.39%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express               | 5        | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 4        | 0.26%   |
| Nvidia MCP77 Ethernet                                                         | 4        | 0.26%   |
| Motorola PCS Moto E (4) Plus                                                  | 4        | 0.26%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 4        | 0.26%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 4        | 0.26%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 4        | 0.26%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express               | 4        | 0.26%   |
| Nvidia MCP51 Ethernet Controller                                              | 3        | 0.2%    |
| Intel I210 Gigabit Network Connection                                         | 3        | 0.2%    |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 0.2%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 0.2%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3        | 0.2%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 3        | 0.2%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 3        | 0.2%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 3        | 0.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]               | 2        | 0.13%   |
| Research In Motion BlackBerry                                                 | 2        | 0.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 2        | 0.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1362     | 70.86%  |
| WiFi     | 537      | 27.94%  |
| Modem    | 18       | 0.94%   |
| Unknown  | 5        | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1084     | 77.93%  |
| WiFi     | 306      | 22%     |
| Modem    | 1        | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1007     | 72.45%  |
| 2     | 320      | 23.02%  |
| 3     | 43       | 3.09%   |
| 0     | 10       | 0.72%   |
| 4     | 5        | 0.36%   |
| 5     | 2        | 0.14%   |
| 17    | 1        | 0.07%   |
| 9     | 1        | 0.07%   |
| 6     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1314     | 94.87%  |
| Yes  | 71       | 5.13%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 112      | 34.15%  |
| Cambridge Silicon Radio         | 105      | 32.01%  |
| ASUSTek Computer                | 54       | 16.46%  |
| Broadcom                        | 16       | 4.88%   |
| Realtek Semiconductor           | 11       | 3.35%   |
| Qualcomm Atheros Communications | 9        | 2.74%   |
| Integrated System Solution      | 4        | 1.22%   |
| Edimax Technology               | 4        | 1.22%   |
| Apple                           | 4        | 1.22%   |
| Lite-On Technology              | 2        | 0.61%   |
| Conwise Technology              | 2        | 0.61%   |
| TP-Link                         | 1        | 0.3%    |
| SINO WEALTH                     | 1        | 0.3%    |
| MediaTek                        | 1        | 0.3%    |
| Logitech                        | 1        | 0.3%    |
| Unknown                         | 1        | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 105      | 32.01%  |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 41       | 12.5%   |
| Intel AX200 Bluetooth                                 | 39       | 11.89%  |
| Intel Wireless-AC 3168 Bluetooth                      | 18       | 5.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 16       | 4.88%   |
| Intel Bluetooth wireless interface                    | 16       | 4.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 11       | 3.35%   |
| Realtek Bluetooth Radio                               | 10       | 3.05%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 6        | 1.83%   |
| Intel AX201 Bluetooth                                 | 6        | 1.83%   |
| ASUS ASUS USB-BT500                                   | 6        | 1.83%   |
| Intel AX210 Bluetooth                                 | 4        | 1.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 1.22%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.91%   |
| Broadcom HP Portable Bumble Bee                       | 3        | 0.91%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 3        | 0.91%   |
| Broadcom BCM2045 Bluetooth                            | 3        | 0.91%   |
| Edimax Bluetooth Adapter                              | 2        | 0.61%   |
| Conwise CW6622                                        | 2        | 0.61%   |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 0.61%   |
| ASUS BCM20702A0                                       | 2        | 0.61%   |
| TP-Link UB500 Adapter                                 | 1        | 0.3%    |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.3%    |
| Realtek RTL8821A Bluetooth                            | 1        | 0.3%    |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.3%    |
| Qualcomm Atheros AR3012 Bluetooth                     | 1        | 0.3%    |
| MediaTek Wireless_Device                              | 1        | 0.3%    |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 0.3%    |
| Lite-On Bluetooth Radio                               | 1        | 0.3%    |
| Lite-On Bluetooth Device                              | 1        | 0.3%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 0.3%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1        | 0.3%    |
| Integrated System Solution Bluetooth Device           | 1        | 0.3%    |
| Edimax Wi-Fi N150 Bluetooth4.0 USB Adapter            | 1        | 0.3%    |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter           | 1        | 0.3%    |
| Broadcom Bluetooth 3.0 Device                         | 1        | 0.3%    |
| Broadcom Bluetooth 2.0+eDR dongle                     | 1        | 0.3%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 1        | 0.3%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.3%    |
| ASUS Bluetooth Radio                                  | 1        | 0.3%    |
| ASUS 2045 Bluetooth 2.0 Device with trace filter      | 1        | 0.3%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 0.3%    |
| Apple Bluetooth USB Host Controller                   | 1        | 0.3%    |
| Apple Bluetooth HCI MacBookPro (HID mode)             | 1        | 0.3%    |
| Apple Bluetooth HCI                                   | 1        | 0.3%    |
| Unknown                                               | 1        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 806      | 34.4%   |
| AMD                                  | 617      | 26.33%  |
| Nvidia                               | 589      | 25.14%  |
| Creative Labs                        | 75       | 3.2%    |
| C-Media Electronics                  | 56       | 2.39%   |
| Creative Technology                  | 23       | 0.98%   |
| VIA Technologies                     | 14       | 0.6%    |
| Texas Instruments                    | 12       | 0.51%   |
| Logitech                             | 12       | 0.51%   |
| JMTek                                | 12       | 0.51%   |
| GYROCOM C&C                          | 9        | 0.38%   |
| SteelSeries ApS                      | 6        | 0.26%   |
| Plantronics                          | 6        | 0.26%   |
| SAVITECH                             | 5        | 0.21%   |
| Realtek Semiconductor                | 5        | 0.21%   |
| Kingston Technology                  | 5        | 0.21%   |
| Generalplus Technology               | 5        | 0.21%   |
| ASUSTek Computer                     | 5        | 0.21%   |
| Valve Software                       | 4        | 0.17%   |
| Razer USA                            | 4        | 0.17%   |
| Dell                                 | 4        | 0.17%   |
| BEHRINGER International              | 4        | 0.17%   |
| PreSonus Audio Electronics           | 3        | 0.13%   |
| Focusrite-Novation                   | 3        | 0.13%   |
| Corsair                              | 3        | 0.13%   |
| XMOS                                 | 2        | 0.09%   |
| ULi Electronics                      | 2        | 0.09%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.09%   |
| Sony                                 | 2        | 0.09%   |
| SM900T Microphone                    | 2        | 0.09%   |
| Samson Technologies                  | 2        | 0.09%   |
| RODE Microphones                     | 2        | 0.09%   |
| M-Audio                              | 2        | 0.09%   |
| Giga-Byte Technology                 | 2        | 0.09%   |
| AudioQuest                           | 2        | 0.09%   |
| AOKEO                                | 2        | 0.09%   |
| A4Tech                               | 2        | 0.09%   |
| Vitana                               | 1        | 0.04%   |
| Unknown                              | 1        | 0.04%   |
| Turtle Beach                         | 1        | 0.04%   |
| Trust                                | 1        | 0.04%   |
| Superlux digit                       | 1        | 0.04%   |
| Solid State System                   | 1        | 0.04%   |
| Sennheiser Communications            | 1        | 0.04%   |
| Roland                               | 1        | 0.04%   |
| ROCCAT                               | 1        | 0.04%   |
| QinHeng Electronics                  | 1        | 0.04%   |
| Panasonic (Matsushita)               | 1        | 0.04%   |
| Nordic Semiconductor ASA             | 1        | 0.04%   |
| Nektar                               | 1        | 0.04%   |
| Midiplus                             | 1        | 0.04%   |
| Micro Star International             | 1        | 0.04%   |
| KYE Systems (Mouse Systems)          | 1        | 0.04%   |
| Holtek Semiconductor                 | 1        | 0.04%   |
| Hewlett-Packard                      | 1        | 0.04%   |
| Guillemot                            | 1        | 0.04%   |
| FIFINE Microphones                   | 1        | 0.04%   |
| Ensoniq                              | 1        | 0.04%   |
| DEXP BK-20                           | 1        | 0.04%   |
| DCMT Technology                      | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 127      | 4.7%    |
| AMD Starship/Matisse HD Audio Controller                                          | 118      | 4.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 109      | 4.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 102      | 3.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 89       | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 88       | 3.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 81       | 3%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 78       | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 77       | 2.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 72       | 2.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 57       | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 56       | 2.07%   |
| AMD FCH Azalia Controller                                                         | 54       | 2%      |
| Intel 200 Series PCH HD Audio                                                     | 51       | 1.89%   |
| Nvidia GP106 High Definition Audio Controller                                     | 44       | 1.63%   |
| Intel Cannon Lake PCH cAVS                                                        | 44       | 1.63%   |
| Nvidia GP104 High Definition Audio Controller                                     | 43       | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                            | 43       | 1.59%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 38       | 1.41%   |
| Nvidia High Definition Audio Controller                                           | 37       | 1.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 36       | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 36       | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 35       | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                     | 35       | 1.3%    |
| Nvidia MCP61 High Definition Audio                                                | 33       | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 31       | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                                | 30       | 1.11%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 29       | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                                     | 28       | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 28       | 1.04%   |
| Nvidia GP108 High Definition Audio Controller                                     | 26       | 0.96%   |
| AMD Navi 10 HDMI Audio                                                            | 26       | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 24       | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 22       | 0.81%   |
| Nvidia GF119 HDMI Audio Controller                                                | 21       | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 21       | 0.78%   |
| Nvidia TU104 HD Audio Controller                                                  | 20       | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                                     | 18       | 0.67%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 18       | 0.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 17       | 0.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 16       | 0.59%   |
| Nvidia GM206 High Definition Audio Controller                                     | 15       | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                | 15       | 0.56%   |
| Nvidia GK104 HDMI Audio Controller                                                | 15       | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                                     | 15       | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                          | 15       | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 14       | 0.52%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 14       | 0.52%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 14       | 0.52%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 13       | 0.48%   |
| AMD Trinity HDMI Audio Controller                                                 | 13       | 0.48%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 13       | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                                     | 12       | 0.44%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 12       | 0.44%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 12       | 0.44%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 11       | 0.41%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 11       | 0.41%   |
| Nvidia GF116 High Definition Audio Controller                                     | 10       | 0.37%   |
| Intel Audio device                                                                | 10       | 0.37%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 10       | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 209      | 22.47%  |
| Kingston                     | 178      | 19.14%  |
| GOODRAM                      | 76       | 8.17%   |
| Samsung Electronics          | 75       | 8.06%   |
| G.Skill                      | 74       | 7.96%   |
| SK hynix                     | 68       | 7.31%   |
| Crucial                      | 57       | 6.13%   |
| Corsair                      | 55       | 5.91%   |
| Patriot                      | 26       | 2.8%    |
| A-DATA Technology            | 20       | 2.15%   |
| Micron Technology            | 18       | 1.94%   |
| Nanya Technology             | 13       | 1.4%    |
| Elpida                       | 9        | 0.97%   |
| Wilk Elektronik              | 8        | 0.86%   |
| GeIL                         | 8        | 0.86%   |
| Apacer                       | 5        | 0.54%   |
| Unknown                      | 5        | 0.54%   |
| Unknown (ABCD)               | 3        | 0.32%   |
| OCZ                          | 3        | 0.32%   |
| Wilk                         | 2        | 0.22%   |
| Silicon Power                | 2        | 0.22%   |
| Qimonda                      | 2        | 0.22%   |
| Patriot Memory (PDP Systems) | 2        | 0.22%   |
| ASint Technology             | 2        | 0.22%   |
| Unifosa                      | 1        | 0.11%   |
| Transcend                    | 1        | 0.11%   |
| tigo                         | 1        | 0.11%   |
| Team                         | 1        | 0.11%   |
| Ramaxel Technology           | 1        | 0.11%   |
| ISD Technology Limited       | 1        | 0.11%   |
| Golden Empire                | 1        | 0.11%   |
| AMD                          | 1        | 0.11%   |
| Aeneon                       | 1        | 0.11%   |
| 48spaces                     | 1        | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 18       | 1.69%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s           | 18       | 1.69%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                         | 13       | 1.22%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 12       | 1.12%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s              | 12       | 1.12%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s             | 11       | 1.03%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s             | 10       | 0.94%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 9        | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                        | 8        | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 8        | 0.75%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                          | 8        | 0.75%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s             | 8        | 0.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s             | 8        | 0.75%   |
| GOODRAM RAM GR1600D364L11/8G 8GB DIMM DDR3 1600MT/s             | 8        | 0.75%   |
| Goodram RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s              | 8        | 0.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM                            | 7        | 0.66%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 7        | 0.66%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s               | 7        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 6        | 0.56%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s          | 6        | 0.56%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s             | 6        | 0.56%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s             | 6        | 0.56%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s           | 6        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 5        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 5        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                      | 5        | 0.47%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                          | 5        | 0.47%   |
| Unknown RAM Module 1GB DIMM 800MT/s                             | 5        | 0.47%   |
| Unknown RAM Module 1024MB DIMM SDRAM                            | 5        | 0.47%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                          | 5        | 0.47%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s           | 5        | 0.47%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 5        | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 5        | 0.47%   |
| Samsung RAM M378B5673FH0-CH9 2048MB DIMM DDR3 1600MT/s          | 5        | 0.47%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s             | 5        | 0.47%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 5        | 0.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 5        | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s           | 5        | 0.47%   |
| Unknown                                                         | 5        | 0.47%   |
| Wilk Elektronik RAM IRP3600D4V64L17/16G 16GB DIMM DDR4 3600MT/s | 4        | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                       | 4        | 0.37%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s            | 4        | 0.37%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s             | 4        | 0.37%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s             | 4        | 0.37%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s          | 4        | 0.37%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s             | 4        | 0.37%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s            | 4        | 0.37%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s               | 4        | 0.37%   |
| GOODRAM RAM IR2400D464L15S/4G 4GB DIMM DDR4 2866MT/s            | 4        | 0.37%   |
| GeIL RAM CL11-11-11 D3-1600 8GB DIMM DDR3 1600MT/s              | 4        | 0.37%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s           | 4        | 0.37%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s           | 4        | 0.37%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s           | 4        | 0.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 4        | 0.37%   |
| Wilk Elektronik RAM IRP3600D4V64L17S/8G 8GB DIMM DDR4 3600MT/s  | 3        | 0.28%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                       | 3        | 0.28%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                            | 3        | 0.28%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                    | 3        | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                       | 3        | 0.28%   |
| Unknown RAM Module 2GB DIMM 400MT/s                             | 3        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 313      | 37.67%  |
| DDR3    | 273      | 32.85%  |
| Unknown | 111      | 13.36%  |
| DDR2    | 62       | 7.46%   |
| SDRAM   | 46       | 5.54%   |
| DDR     | 22       | 2.65%   |
| LPDDR4  | 3        | 0.36%   |
| DRAM    | 1        | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 786      | 96.44%  |
| SODIMM | 28       | 3.44%   |
| RIMM   | 1        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 281      | 30.41%  |
| 4096  | 213      | 23.05%  |
| 2048  | 198      | 21.43%  |
| 16384 | 92       | 9.96%   |
| 1024  | 79       | 8.55%   |
| 32768 | 41       | 4.44%   |
| 512   | 17       | 1.84%   |
| 1536  | 1        | 0.11%   |
| 256   | 1        | 0.11%   |
| 64    | 1        | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 175      | 19.08%  |
| 1333    | 106      | 11.56%  |
| 3200    | 84       | 9.16%   |
| 800     | 79       | 8.62%   |
| 3600    | 58       | 6.32%   |
| 2400    | 48       | 5.23%   |
| 667     | 41       | 4.47%   |
| 2667    | 39       | 4.25%   |
| 2133    | 23       | 2.51%   |
| 3466    | 21       | 2.29%   |
| 2933    | 21       | 2.29%   |
| Unknown | 21       | 2.29%   |
| 3000    | 18       | 1.96%   |
| 1867    | 16       | 1.74%   |
| 1067    | 15       | 1.64%   |
| 1066    | 14       | 1.53%   |
| 1866    | 13       | 1.42%   |
| 400     | 13       | 1.42%   |
| 1800    | 12       | 1.31%   |
| 3400    | 10       | 1.09%   |
| 3733    | 9        | 0.98%   |
| 533     | 9        | 0.98%   |
| 3800    | 7        | 0.76%   |
| 1334    | 6        | 0.65%   |
| 333     | 6        | 0.65%   |
| 2866    | 5        | 0.55%   |
| 2666    | 5        | 0.55%   |
| 49926   | 4        | 0.44%   |
| 2800    | 4        | 0.44%   |
| 3866    | 3        | 0.33%   |
| 2000    | 3        | 0.33%   |
| 1332    | 3        | 0.33%   |
| 3334    | 2        | 0.22%   |
| 3333    | 2        | 0.22%   |
| 3066    | 2        | 0.22%   |
| 1639    | 2        | 0.22%   |
| 266     | 2        | 0.22%   |
| 41632   | 1        | 0.11%   |
| 33859   | 1        | 0.11%   |
| 19791   | 1        | 0.11%   |
| 4800    | 1        | 0.11%   |
| 4400    | 1        | 0.11%   |
| 4266    | 1        | 0.11%   |
| 4000    | 1        | 0.11%   |
| 3151    | 1        | 0.11%   |
| 2733    | 1        | 0.11%   |
| 2200    | 1        | 0.11%   |
| 2176    | 1        | 0.11%   |
| 2132    | 1        | 0.11%   |
| 2048    | 1        | 0.11%   |
| 1162    | 1        | 0.11%   |
| 200     | 1        | 0.11%   |
| 66      | 1        | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 31       | 45.59%  |
| Brother Industries    | 10       | 14.71%  |
| Samsung Electronics   | 9        | 13.24%  |
| Prolific Technology   | 5        | 7.35%   |
| Canon                 | 5        | 7.35%   |
| Seiko Epson           | 4        | 5.88%   |
| Zebra                 | 1        | 1.47%   |
| Xerox                 | 1        | 1.47%   |
| Lexmark International | 1        | 1.47%   |
| Datamax-O'Neil        | 1        | 1.47%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port          | 5        | 7.14%   |
| HP LaserJet 1020                       | 3        | 4.29%   |
| Canon iP7200 series                    | 3        | 4.29%   |
| Samsung ML-216x Series Laser Printer   | 2        | 2.86%   |
| Samsung ML-2010P Mono Laser Printer    | 2        | 2.86%   |
| HP LaserJet M14-M17                    | 2        | 2.86%   |
| HP Deskjet F4500 series                | 2        | 2.86%   |
| HP DeskJet F4100 Printer series        | 2        | 2.86%   |
| HP DeskJet 845c                        | 2        | 2.86%   |
| HP DeskJet 3700 series                 | 2        | 2.86%   |
| HP Deskjet 1050 J410                   | 2        | 2.86%   |
| Brother DCP-J105                       | 2        | 2.86%   |
| Zebra LP2844 Printer                   | 1        | 1.43%   |
| Xerox WorkCentre PE16                  | 1        | 1.43%   |
| Seiko Epson Stylus NX230/SX235W Series | 1        | 1.43%   |
| Seiko Epson L405 Series                | 1        | 1.43%   |
| Seiko Epson L3150 Series               | 1        | 1.43%   |
| Seiko Epson L1110 Series               | 1        | 1.43%   |
| Samsung SCX-4300 Series                | 1        | 1.43%   |
| Samsung SCX-4200 series                | 1        | 1.43%   |
| Samsung SCX-3400 Series                | 1        | 1.43%   |
| Samsung ML-3050/ML-3051 Laser Printer  | 1        | 1.43%   |
| Samsung ML-2540 Series Laser Printer   | 1        | 1.43%   |
| Lexmark International Lexmark E352dn   | 1        | 1.43%   |
| HP Smart Tank 510 series               | 1        | 1.43%   |
| HP Printing Support                    | 1        | 1.43%   |
| HP LaserJet P2015 series               | 1        | 1.43%   |
| HP LaserJet P1102                      | 1        | 1.43%   |
| HP LaserJet M101-M106                  | 1        | 1.43%   |
| HP LaserJet CM1415fnw                  | 1        | 1.43%   |
| HP LaserJet 3030                       | 1        | 1.43%   |
| HP LaserJet 1320                       | 1        | 1.43%   |
| HP LaserJet 1022                       | 1        | 1.43%   |
| HP DeskJet 840c                        | 1        | 1.43%   |
| HP DeskJet 4530 series                 | 1        | 1.43%   |
| HP DeskJet 2620 All-in-One Printer     | 1        | 1.43%   |
| HP Deskjet 2540 series                 | 1        | 1.43%   |
| HP DeskJet 2130 series                 | 1        | 1.43%   |
| HP Deskjet 2050 J510                   | 1        | 1.43%   |
| HP Color LaserJet CP1215               | 1        | 1.43%   |
| Datamax-O'Neil Datamax E-4304          | 1        | 1.43%   |
| Canon TS3100 series                    | 1        | 1.43%   |
| Canon MG5600 series                    | 1        | 1.43%   |
| Canon iP4800 series                    | 1        | 1.43%   |
| Canon G1010 series                     | 1        | 1.43%   |
| Brother HL-5150D series                | 1        | 1.43%   |
| Brother DCP-T500W                      | 1        | 1.43%   |
| Brother DCP-L2540DN                    | 1        | 1.43%   |
| Brother DCP-J525W                      | 1        | 1.43%   |
| Brother DCP-9020CDW                    | 1        | 1.43%   |
| Brother DCP-7055W                      | 1        | 1.43%   |
| Brother DCP-7030                       | 1        | 1.43%   |
| Brother DCP-1610W                      | 1        | 1.43%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 7        | 58.33%  |
| Seiko Epson                 | 2        | 16.67%  |
| Ultima Electronics          | 1        | 8.33%   |
| Plustek                     | 1        | 8.33%   |
| Acer Peripherals (now BenQ) | 1        | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 3        | 25%     |
| Ultima Artec E+ 48U                                      | 1        | 8.33%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1        | 8.33%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 8.33%   |
| Plustek OpticPro 1248U Scanner #2                        | 1        | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 8.33%   |
| Canon CanoScan LIDE 25                                   | 1        | 8.33%   |
| Canon CanoScan LiDE 120                                  | 1        | 8.33%   |
| Canon CanoScan LiDE 110                                  | 1        | 8.33%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1        | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 55       | 31.07%  |
| Creative Technology                    | 22       | 12.43%  |
| Microdia                               | 18       | 10.17%  |
| Microsoft                              | 12       | 6.78%   |
| Samsung Electronics                    | 9        | 5.08%   |
| Z-Star Microelectronics                | 8        | 4.52%   |
| Hewlett-Packard                        | 5        | 2.82%   |
| Cubeternet                             | 5        | 2.82%   |
| Aveo Technology                        | 4        | 2.26%   |
| Xiongmai                               | 3        | 1.69%   |
| Generalplus Technology                 | 3        | 1.69%   |
| GEMBIRD                                | 3        | 1.69%   |
| Chicony Electronics                    | 3        | 1.69%   |
| Valve Software                         | 2        | 1.13%   |
| Trust                                  | 2        | 1.13%   |
| Realtek Semiconductor                  | 2        | 1.13%   |
| Pixart Imaging                         | 2        | 1.13%   |
| LG Electronics                         | 2        | 1.13%   |
| Jieli Technology                       | 2        | 1.13%   |
| Apple                                  | 2        | 1.13%   |
| Alcor Micro                            | 2        | 1.13%   |
| YJX                                    | 1        | 0.56%   |
| Sunplus Innovation Technology          | 1        | 0.56%   |
| Razer USA                              | 1        | 0.56%   |
| MacroSilicon                           | 1        | 0.56%   |
| KYE Systems (Mouse Systems)            | 1        | 0.56%   |
| Huawei Technologies                    | 1        | 0.56%   |
| Google                                 | 1        | 0.56%   |
| Etron Technology                       | 1        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.56%   |
| Asuscom Network                        | 1        | 0.56%   |
| Arkmicro Technologies                  | 1        | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Creative Live! Cam Sync HD [VF0770]               | 12       | 6.74%   |
| Logitech Webcam C270                              | 11       | 6.18%   |
| Logitech HD Pro Webcam C920                       | 9        | 5.06%   |
| Samsung Galaxy series, misc. (MTP mode)           | 8        | 4.49%   |
| Logitech Webcam C310                              | 7        | 3.93%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 3.37%   |
| Microdia USB 2.0 Camera                           | 5        | 2.81%   |
| Logitech Webcam C170                              | 5        | 2.81%   |
| Microsoft LifeCam HD-3000                         | 4        | 2.25%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 2.25%   |
| Cubeternet USB2.0 Camera                          | 4        | 2.25%   |
| Creative Live! Cam Chat HD [VF0700]               | 4        | 2.25%   |
| Xiongmai web camera                               | 3        | 1.69%   |
| Microdia Webcam Vitade AF                         | 3        | 1.69%   |
| Microdia Integrated Camera                        | 3        | 1.69%   |
| Logitech Webcam C120                              | 3        | 1.69%   |
| HP Webcam HD 2300                                 | 3        | 1.69%   |
| Generalplus GENERAL WEBCAM                        | 3        | 1.69%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 1.69%   |
| Creative Live! Cam Optia                          | 3        | 1.69%   |
| Aveo USB2.0 Camera                                | 3        | 1.69%   |
| Valve Software 3D Camera                          | 2        | 1.12%   |
| Pixart Imaging USB2.0_Camera                      | 2        | 1.12%   |
| Microsoft LifeCam VX-500 [1357]                   | 2        | 1.12%   |
| Microsoft LifeCam NX-6000                         | 2        | 1.12%   |
| Microsoft LifeCam HD-5000                         | 2        | 1.12%   |
| Microdia Camera                                   | 2        | 1.12%   |
| Logitech Webcam C930e                             | 2        | 1.12%   |
| Logitech StreamCam                                | 2        | 1.12%   |
| Logitech QuickCam Pro 9000                        | 2        | 1.12%   |
| Logitech Logitech Webcam C100                     | 2        | 1.12%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 1.12%   |
| Jieli USB PHY 2.0                                 | 2        | 1.12%   |
| Creative Live! Cam Sync 1080p                     | 2        | 1.12%   |
| Chicony FULL HD 5MP Webcam                        | 2        | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE                         | 2        | 1.12%   |
| Alcor Micro USB 2.0 PC Camera                     | 2        | 1.12%   |
| Z-Star Integrated Camera                          | 1        | 0.56%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 1        | 0.56%   |
| YJX USB Camera                                    | 1        | 0.56%   |
| Trust USB Camera                                  | 1        | 0.56%   |
| Trust Full HD Webcam                              | 1        | 0.56%   |
| Sunplus HD 720P webcam                            | 1        | 0.56%   |
| Samsung Galaxy (PTP mode)                         | 1        | 0.56%   |
| Realtek USB Camera                                | 1        | 0.56%   |
| Realtek Thronmax StreamGo Webcam                  | 1        | 0.56%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 0.56%   |
| Razer USA Gaming Webcam [Kiyo]                    | 1        | 0.56%   |
| Microsoft MicrosoftÂ LifeCam Studio              | 1        | 0.56%   |
| Microsoft Kinect for Windows NUI Camera           | 1        | 0.56%   |
| Microdia Defender G-Lens 2577 HD720p Camera       | 1        | 0.56%   |
| MacroSilicon USB Video                            | 1        | 0.56%   |
| Logitech Webcam Pro 9000                          | 1        | 0.56%   |
| Logitech Webcam C250                              | 1        | 0.56%   |
| Logitech Webcam C200                              | 1        | 0.56%   |
| Logitech Webcam B500                              | 1        | 0.56%   |
| Logitech QuickCam Vision Pro                      | 1        | 0.56%   |
| Logitech Quickcam 3000 For Business               | 1        | 0.56%   |
| Logitech HD Webcam C615                           | 1        | 0.56%   |
| Logitech HD Webcam C525                           | 1        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 1        | 25%     |
| STMicroelectronics    | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |
| AuthenTec             | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 25%     |
| STMicroelectronics Fingerprint Reader        | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 25%     |
| AuthenTec AES1600                            | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| OmniKey               | 2        | 28.57%  |
| SCM Microsystems      | 1        | 14.29%  |
| Gemalto (was Gemplus) | 1        | 14.29%  |
| Cherry                | 1        | 14.29%  |
| Alcor Micro           | 1        | 14.29%  |
| Advanced Card Systems | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                      | 2        | 28.57%  |
| SCM Microsystems SCR333 SmartCard Reader         | 1        | 14.29%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1        | 14.29%  |
| Cherry SmartCard Reader Keyboard KC 1000 SC      | 1        | 14.29%  |
| Alcor Micro Watchdata W 1981                     | 1        | 14.29%  |
| Advanced Card Systems ACR39U                     | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1213     | 85.54%  |
| 1     | 184      | 12.98%  |
| 2     | 15       | 1.06%   |
| 3     | 4        | 0.28%   |
| 4     | 2        | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 94       | 42.34%  |
| Net/wireless             | 39       | 17.57%  |
| Communication controller | 16       | 7.21%   |
| Multimedia controller    | 13       | 5.86%   |
| Unassigned class         | 12       | 5.41%   |
| Sound                    | 8        | 3.6%    |
| Camera                   | 7        | 3.15%   |
| Bluetooth                | 6        | 2.7%    |
| Network                  | 5        | 2.25%   |
| Storage/ide              | 4        | 1.8%    |
| Fingerprint reader       | 4        | 1.8%    |
| Chipcard                 | 4        | 1.8%    |
| Storage/raid             | 3        | 1.35%   |
| Storage                  | 2        | 0.9%    |
| Net/ethernet             | 2        | 0.9%    |
| Modem                    | 1        | 0.45%   |
| Firewire controller      | 1        | 0.45%   |
| Dvb card                 | 1        | 0.45%   |

