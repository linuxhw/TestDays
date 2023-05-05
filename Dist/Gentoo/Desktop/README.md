Gentoo - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Gentoo.

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

Total: 1160

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PLUS        | [2a2bf698ed](https://linux-hardware.org/?probe=2a2bf698ed) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f3b21405ff](https://linux-hardware.org/?probe=f3b21405ff) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| ASRock        | B550M Pro4                  | [b53354af62](https://linux-hardware.org/?probe=b53354af62) | Apr 25, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [0f7e30ded3](https://linux-hardware.org/?probe=0f7e30ded3) | Apr 23, 2023 |
| ASUSTek       | M3A78-CM                    | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Gigabyte      | B460 HD3                    | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [80ead18196](https://linux-hardware.org/?probe=80ead18196) | Apr 21, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0f17162503](https://linux-hardware.org/?probe=0f17162503) | Apr 21, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [056db62b47](https://linux-hardware.org/?probe=056db62b47) | Apr 20, 2023 |
| Intel         | D510MO AAE76523-401         | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [0a544df503](https://linux-hardware.org/?probe=0a544df503) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cb21111c89](https://linux-hardware.org/?probe=cb21111c89) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3faf4e88e1](https://linux-hardware.org/?probe=3faf4e88e1) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [c8bf9d49d4](https://linux-hardware.org/?probe=c8bf9d49d4) | Apr 15, 2023 |
| ASRock        | B450M Steel Legend          | [6b71471847](https://linux-hardware.org/?probe=6b71471847) | Apr 15, 2023 |
| HP            | ProLiant MicroServer Gen... | [d00ebfbc62](https://linux-hardware.org/?probe=d00ebfbc62) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [8b0e1ffa20](https://linux-hardware.org/?probe=8b0e1ffa20) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [3b2ac9206c](https://linux-hardware.org/?probe=3b2ac9206c) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [16ee5e0082](https://linux-hardware.org/?probe=16ee5e0082) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [1b21351033](https://linux-hardware.org/?probe=1b21351033) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [f6f55c801f](https://linux-hardware.org/?probe=f6f55c801f) | Apr 14, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [7f20e3160b](https://linux-hardware.org/?probe=7f20e3160b) | Apr 13, 2023 |
| ASUSTek       | Z87-PLUS                    | [1b44c95410](https://linux-hardware.org/?probe=1b44c95410) | Apr 13, 2023 |
| ASUSTek       | Maximus VI HERO             | [f46283dc4c](https://linux-hardware.org/?probe=f46283dc4c) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f5241c853f](https://linux-hardware.org/?probe=f5241c853f) | Apr 12, 2023 |
| ASRock        | X370 Gaming X               | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f85fdf6564](https://linux-hardware.org/?probe=f85fdf6564) | Apr 09, 2023 |
| HPE           | ProLiant MicroServer Gen... | [e378272577](https://linux-hardware.org/?probe=e378272577) | Apr 08, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [97e76297c9](https://linux-hardware.org/?probe=97e76297c9) | Apr 08, 2023 |
| ASUSTek       | M3A78-CM                    | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2fccbc61e2](https://linux-hardware.org/?probe=2fccbc61e2) | Apr 04, 2023 |
| Gigabyte      | B450M DS3H V2               | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d19221e116](https://linux-hardware.org/?probe=d19221e116) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| ASUSTek       | M3A78-CM                    | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| ASRock        | AM1H-ITX                    | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [f2b287b461](https://linux-hardware.org/?probe=f2b287b461) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | [72f90312db](https://linux-hardware.org/?probe=72f90312db) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [dac7782920](https://linux-hardware.org/?probe=dac7782920) | Mar 24, 2023 |
| HPE           | ProLiant MicroServer Gen... | [2c8daaa4f2](https://linux-hardware.org/?probe=2c8daaa4f2) | Mar 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [4bf7fa5f9c](https://linux-hardware.org/?probe=4bf7fa5f9c) | Mar 23, 2023 |
| ASUSTek       | M3A78-CM                    | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| MSI           | 990FXA-GD80                 | [e79acda971](https://linux-hardware.org/?probe=e79acda971) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7e11b106d7](https://linux-hardware.org/?probe=7e11b106d7) | Mar 17, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [fab37d7522](https://linux-hardware.org/?probe=fab37d7522) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [4d5bb23ec0](https://linux-hardware.org/?probe=4d5bb23ec0) | Mar 15, 2023 |
| ASUSTek       | M3A78-CM                    | [8c2507428d](https://linux-hardware.org/?probe=8c2507428d) | Mar 15, 2023 |
| ASRock        | H81M-HDS                    | [58f8534073](https://linux-hardware.org/?probe=58f8534073) | Mar 14, 2023 |
| Foxconn       | TPS01                       | [60ae6d3891](https://linux-hardware.org/?probe=60ae6d3891) | Mar 14, 2023 |
| Fujitsu Si... | D1547 S26361-D1547          | [95a9c8655d](https://linux-hardware.org/?probe=95a9c8655d) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [06d54f03f9](https://linux-hardware.org/?probe=06d54f03f9) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [540bfa93eb](https://linux-hardware.org/?probe=540bfa93eb) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [0932f02541](https://linux-hardware.org/?probe=0932f02541) | Mar 12, 2023 |
| ASRock        | AM1H-ITX                    | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| ASRock        | H170 Pro4                   | [7d749add31](https://linux-hardware.org/?probe=7d749add31) | Mar 07, 2023 |
| ASRock        | X570 Taichi                 | [4d48b829ca](https://linux-hardware.org/?probe=4d48b829ca) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6493617e39](https://linux-hardware.org/?probe=6493617e39) | Mar 07, 2023 |
| Unknown       | Unknown                     | [ffd546b665](https://linux-hardware.org/?probe=ffd546b665) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [5f35f09385](https://linux-hardware.org/?probe=5f35f09385) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [ccca18039f](https://linux-hardware.org/?probe=ccca18039f) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9a42993edb](https://linux-hardware.org/?probe=9a42993edb) | Mar 03, 2023 |
| Huanan        | X99-F8D V2.4                | [e260724901](https://linux-hardware.org/?probe=e260724901) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| ASUSTek       | PRIME B450M-A               | [373f4f8123](https://linux-hardware.org/?probe=373f4f8123) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| Lenovo        | 1048 SDK0T08861 WIN 3305... | [e6b48cdec4](https://linux-hardware.org/?probe=e6b48cdec4) | Feb 26, 2023 |
| ASRock        | AM1H-ITX                    | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| ASRock        | X370 Professional Gaming    | [cff46cb07b](https://linux-hardware.org/?probe=cff46cb07b) | Feb 24, 2023 |
| ASUSTek       | P10S-I Series               | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| Gigabyte      | Z590 UD                     | [a8da25537c](https://linux-hardware.org/?probe=a8da25537c) | Feb 21, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| ASUSTek       | M3A78-CM                    | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [a526504d18](https://linux-hardware.org/?probe=a526504d18) | Feb 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [46289356fa](https://linux-hardware.org/?probe=46289356fa) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [fa6a3fe6e3](https://linux-hardware.org/?probe=fa6a3fe6e3) | Feb 17, 2023 |
| ASUSTek       | M3A78-CM                    | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| ASUSTek       | M3A78-CM                    | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [469eaa6fba](https://linux-hardware.org/?probe=469eaa6fba) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [4998be684f](https://linux-hardware.org/?probe=4998be684f) | Feb 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2cfb05371e](https://linux-hardware.org/?probe=2cfb05371e) | Feb 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [4468518165](https://linux-hardware.org/?probe=4468518165) | Feb 09, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [f09cd898c8](https://linux-hardware.org/?probe=f09cd898c8) | Feb 09, 2023 |
| ASUSTek       | M3A78-CM                    | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| ASRock        | B550M Steel Legend          | [83b847229c](https://linux-hardware.org/?probe=83b847229c) | Feb 08, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [bc0593280c](https://linux-hardware.org/?probe=bc0593280c) | Feb 05, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [e12e1d2598](https://linux-hardware.org/?probe=e12e1d2598) | Feb 04, 2023 |
| MSI           | PRO X670-P WIFI             | [be3ef90301](https://linux-hardware.org/?probe=be3ef90301) | Feb 04, 2023 |
| ASUSTek       | PRIME X570-P                | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0cf18835cc](https://linux-hardware.org/?probe=0cf18835cc) | Feb 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9fb41ee5bc](https://linux-hardware.org/?probe=9fb41ee5bc) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4bb9990abe](https://linux-hardware.org/?probe=4bb9990abe) | Feb 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [c93e84b79b](https://linux-hardware.org/?probe=c93e84b79b) | Jan 29, 2023 |
| ASUSTek       | PRIME Z390-A                | [a30690db0c](https://linux-hardware.org/?probe=a30690db0c) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| Gigabyte      | Z370P D3-CF                 | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | [6a876fb2b4](https://linux-hardware.org/?probe=6a876fb2b4) | Jan 23, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | [287d005187](https://linux-hardware.org/?probe=287d005187) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [69bf20ee28](https://linux-hardware.org/?probe=69bf20ee28) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [dfd88e113a](https://linux-hardware.org/?probe=dfd88e113a) | Jan 21, 2023 |
| ASUSTek       | M3A78-CM                    | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| ASUSTek       | X99-A/USB                   | [0d5c9f7a33](https://linux-hardware.org/?probe=0d5c9f7a33) | Jan 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [5e6192ed2b](https://linux-hardware.org/?probe=5e6192ed2b) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| ASUSTek       | M3A78-CM                    | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [306315e4d8](https://linux-hardware.org/?probe=306315e4d8) | Jan 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| ASUSTek       | PRIME B460M-A               | [b5dd8ee9f3](https://linux-hardware.org/?probe=b5dd8ee9f3) | Jan 07, 2023 |
| Dell          | 0J3C2F A02                  | [0944e31ade](https://linux-hardware.org/?probe=0944e31ade) | Jan 06, 2023 |
| HP            | 212A                        | [21acb67653](https://linux-hardware.org/?probe=21acb67653) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| ASRock        | AM1H-ITX                    | [3b32e784a3](https://linux-hardware.org/?probe=3b32e784a3) | Jan 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| Phoenix       | 945GM                       | [d391eaf6e2](https://linux-hardware.org/?probe=d391eaf6e2) | Dec 31, 2022 |
| ASUSTek       | M3A78-CM                    | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| Unknown       | Freecom Silverstore HNCN... | [723fbcd23f](https://linux-hardware.org/?probe=723fbcd23f) | Dec 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| Supermicro    | X10DSC+                     | [cf559d5e84](https://linux-hardware.org/?probe=cf559d5e84) | Dec 24, 2022 |
| ASUSTek       | M3A78-CM                    | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| HP            | 0980h                       | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| HP            | 0980h                       | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| HP            | 83E9                        | [02e854bd7c](https://linux-hardware.org/?probe=02e854bd7c) | Dec 20, 2022 |
| HP            | 0B4Ch D                     | [2318fda45f](https://linux-hardware.org/?probe=2318fda45f) | Dec 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| HP            | 83E9                        | [cdf4ff19a6](https://linux-hardware.org/?probe=cdf4ff19a6) | Dec 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [d8774d83a7](https://linux-hardware.org/?probe=d8774d83a7) | Dec 16, 2022 |
| HP            | 83E9                        | [53f1974d93](https://linux-hardware.org/?probe=53f1974d93) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3807037a5c](https://linux-hardware.org/?probe=3807037a5c) | Dec 15, 2022 |
| HP            | 212A                        | [c21bb6d20d](https://linux-hardware.org/?probe=c21bb6d20d) | Dec 14, 2022 |
| Gigabyte      | B550M DS3H                  | [8370a57760](https://linux-hardware.org/?probe=8370a57760) | Dec 12, 2022 |
| Gigabyte      | B650 AORUS PRO AX           | [b7374c7211](https://linux-hardware.org/?probe=b7374c7211) | Dec 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| MSI           | K9N2 Diamond                | [0a42d5e656](https://linux-hardware.org/?probe=0a42d5e656) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | [6dd02812db](https://linux-hardware.org/?probe=6dd02812db) | Dec 10, 2022 |
| HP            | 0B4Ch D                     | [bede7701b9](https://linux-hardware.org/?probe=bede7701b9) | Dec 08, 2022 |
| ASUSTek       | PRIME X470-PRO              | [26f56cc499](https://linux-hardware.org/?probe=26f56cc499) | Dec 08, 2022 |
| Gigabyte      | B650 AORUS PRO AX           | [15f27b7ac6](https://linux-hardware.org/?probe=15f27b7ac6) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| ASRock        | AB350M                      | [95a14fd558](https://linux-hardware.org/?probe=95a14fd558) | Dec 07, 2022 |
| Gigabyte      | Z370P D3-CF                 | [13ac8bc162](https://linux-hardware.org/?probe=13ac8bc162) | Dec 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | [c3510d4787](https://linux-hardware.org/?probe=c3510d4787) | Dec 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ccf3e1f074](https://linux-hardware.org/?probe=ccf3e1f074) | Dec 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [60b1be0a32](https://linux-hardware.org/?probe=60b1be0a32) | Dec 05, 2022 |
| Gigabyte      | B650M DS3H                  | [73b49404f9](https://linux-hardware.org/?probe=73b49404f9) | Dec 05, 2022 |
| ASUSTek       | PRIME X570-PRO              | [22fc01fd20](https://linux-hardware.org/?probe=22fc01fd20) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A               | [debbc3f9ff](https://linux-hardware.org/?probe=debbc3f9ff) | Dec 03, 2022 |
| ASUSTek       | P8Z68-V PRO                 | [2adb8631b0](https://linux-hardware.org/?probe=2adb8631b0) | Dec 03, 2022 |
| Pegatron      | 2AC2                        | [29d43d4af8](https://linux-hardware.org/?probe=29d43d4af8) | Dec 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee24c782fa](https://linux-hardware.org/?probe=ee24c782fa) | Dec 02, 2022 |
| Pegatron      | 2AC2                        | [3d92c6cbc8](https://linux-hardware.org/?probe=3d92c6cbc8) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e3f55c7b9d](https://linux-hardware.org/?probe=e3f55c7b9d) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [54407c7caa](https://linux-hardware.org/?probe=54407c7caa) | Nov 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| Gigabyte      | Z370P D3-CF                 | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Apple         | Mac-F221BEC8                | [f2fe1d140e](https://linux-hardware.org/?probe=f2fe1d140e) | Nov 26, 2022 |
| ASUSTek       | M3A78-CM                    | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| MSI           | TRX40 PRO WIFI              | [3617f324a2](https://linux-hardware.org/?probe=3617f324a2) | Nov 24, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [16fc755db2](https://linux-hardware.org/?probe=16fc755db2) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| Unknown       | QNAP TS-221                 | [b9ff535a3f](https://linux-hardware.org/?probe=b9ff535a3f) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [45fbc31f55](https://linux-hardware.org/?probe=45fbc31f55) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a5eb8c6aaa](https://linux-hardware.org/?probe=a5eb8c6aaa) | Nov 17, 2022 |
| MSI           | MEG X570 GODLIKE            | [de10599614](https://linux-hardware.org/?probe=de10599614) | Nov 15, 2022 |
| ASUSTek       | PRIME X570-PRO              | [642a889fcc](https://linux-hardware.org/?probe=642a889fcc) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| Apple         | Mac-F221BEC8                | [cd18d68895](https://linux-hardware.org/?probe=cd18d68895) | Nov 13, 2022 |
| ASUSTek       | PRIME Z370-P II             | [7a41c26bea](https://linux-hardware.org/?probe=7a41c26bea) | Nov 09, 2022 |
| ASUSTek       | M3A78-CM                    | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| ASRock        | B550 Extreme4               | [16154018bb](https://linux-hardware.org/?probe=16154018bb) | Nov 06, 2022 |
| Unknown       | X79-P3                      | [f069ed7bd9](https://linux-hardware.org/?probe=f069ed7bd9) | Nov 04, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [953e399168](https://linux-hardware.org/?probe=953e399168) | Nov 03, 2022 |
| ASRock        | N68C-GS UCC                 | [9430ecf81c](https://linux-hardware.org/?probe=9430ecf81c) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| MSI           | MEG X570 UNIFY              | [1a88842782](https://linux-hardware.org/?probe=1a88842782) | Nov 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [966eb5bb18](https://linux-hardware.org/?probe=966eb5bb18) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [860f45c4c1](https://linux-hardware.org/?probe=860f45c4c1) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [98fe919d0e](https://linux-hardware.org/?probe=98fe919d0e) | Oct 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9a6e9239e1](https://linux-hardware.org/?probe=9a6e9239e1) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [836d9e4de1](https://linux-hardware.org/?probe=836d9e4de1) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [b7b7481628](https://linux-hardware.org/?probe=b7b7481628) | Oct 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [c1ce4e70e0](https://linux-hardware.org/?probe=c1ce4e70e0) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [64e6199c96](https://linux-hardware.org/?probe=64e6199c96) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [cc2fc1e863](https://linux-hardware.org/?probe=cc2fc1e863) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | [16f90b14dc](https://linux-hardware.org/?probe=16f90b14dc) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b89b177dd7](https://linux-hardware.org/?probe=b89b177dd7) | Oct 22, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [d066cccd5a](https://linux-hardware.org/?probe=d066cccd5a) | Oct 19, 2022 |
| ASRock        | X670E Steel Legend          | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | [71ab3d919c](https://linux-hardware.org/?probe=71ab3d919c) | Oct 18, 2022 |
| ASUSTek       | M3A78-CM                    | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d2b5d08432](https://linux-hardware.org/?probe=d2b5d08432) | Oct 15, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [843e47e886](https://linux-hardware.org/?probe=843e47e886) | Oct 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f57f16d11b](https://linux-hardware.org/?probe=f57f16d11b) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [55e6578ade](https://linux-hardware.org/?probe=55e6578ade) | Oct 13, 2022 |
| Gigabyte      | H81M-H                      | [63731688d0](https://linux-hardware.org/?probe=63731688d0) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [11fb952122](https://linux-hardware.org/?probe=11fb952122) | Oct 10, 2022 |
| ASUSTek       | M3A78-CM                    | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| MSI           | X470 GAMING PLUS            | [cbac2de735](https://linux-hardware.org/?probe=cbac2de735) | Oct 08, 2022 |
| ASUSTek       | M3A78-CM                    | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [ae88619ae9](https://linux-hardware.org/?probe=ae88619ae9) | Oct 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| ASRock        | J3160M                      | [c9cc54f48e](https://linux-hardware.org/?probe=c9cc54f48e) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | AM1M-A                      | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Gigabyte      | Z590 UD                     | [475ed7f917](https://linux-hardware.org/?probe=475ed7f917) | Sep 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7ad1180946](https://linux-hardware.org/?probe=7ad1180946) | Sep 14, 2022 |
| ASUSTek       | M3A78-CM                    | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| ASRock        | Z390 Phantom Gaming 4S      | [146e7ebf49](https://linux-hardware.org/?probe=146e7ebf49) | Sep 08, 2022 |
| Gigabyte      | B660 GAMING X AX DDR4       | [3d12a72937](https://linux-hardware.org/?probe=3d12a72937) | Sep 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [cc1fde17e8](https://linux-hardware.org/?probe=cc1fde17e8) | Sep 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| ASUSTek       | M3A78-CM                    | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock        | X370 Gaming X               | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [7e810b23be](https://linux-hardware.org/?probe=7e810b23be) | Aug 26, 2022 |
| Gigabyte      | Z77X-D3H                    | [294fe7d6c8](https://linux-hardware.org/?probe=294fe7d6c8) | Aug 24, 2022 |
| Gigabyte      | Z77X-D3H                    | [2952e542e1](https://linux-hardware.org/?probe=2952e542e1) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0df091061c](https://linux-hardware.org/?probe=0df091061c) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c80683e2a](https://linux-hardware.org/?probe=0c80683e2a) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | [8445aa0041](https://linux-hardware.org/?probe=8445aa0041) | Aug 20, 2022 |
| ASUSTek       | M3A78-CM                    | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | B450 GAMING X               | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK               | [8d95c82a1d](https://linux-hardware.org/?probe=8d95c82a1d) | Aug 12, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [7d7ceef044](https://linux-hardware.org/?probe=7d7ceef044) | Aug 12, 2022 |
| Unknown       | QNAP TS-221                 | [8d3f7ca9cf](https://linux-hardware.org/?probe=8d3f7ca9cf) | Aug 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [2781a13b80](https://linux-hardware.org/?probe=2781a13b80) | Aug 10, 2022 |
| ASRock        | P67 Extreme4 Gen3           | [b94e1be5ab](https://linux-hardware.org/?probe=b94e1be5ab) | Aug 09, 2022 |
| ASUSTek       | M3A78-CM                    | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3e7a65077d](https://linux-hardware.org/?probe=3e7a65077d) | Aug 06, 2022 |
| Gigabyte      | B450 GAMING X               | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| Gigabyte      | B550M DS3H                  | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| ASRock        | B75M-GL R2.0                | [eed9f05678](https://linux-hardware.org/?probe=eed9f05678) | Aug 01, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [effa59ed64](https://linux-hardware.org/?probe=effa59ed64) | Aug 01, 2022 |
| ASRock        | B550M Steel Legend          | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f22250f00c](https://linux-hardware.org/?probe=f22250f00c) | Jul 31, 2022 |
| ASUSTek       | M3A78-CM                    | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| Gigabyte      | 970A-DS3                    | [78f00bd2aa](https://linux-hardware.org/?probe=78f00bd2aa) | Jul 30, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [d3d824f468](https://linux-hardware.org/?probe=d3d824f468) | Jul 29, 2022 |
| MSI           | B450M MORTAR                | [29a26324b9](https://linux-hardware.org/?probe=29a26324b9) | Jul 29, 2022 |
| Intel         | D54250WYK H13922-303        | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [dc7eff27cf](https://linux-hardware.org/?probe=dc7eff27cf) | Jul 26, 2022 |
| ASRock        | X399 Taichi                 | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [c98fed5f84](https://linux-hardware.org/?probe=c98fed5f84) | Jul 25, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [dae325b47b](https://linux-hardware.org/?probe=dae325b47b) | Jul 25, 2022 |
| ASUSTek       | M3A78-CM                    | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Unknown       | QNAP TS-221                 | [fb3741faab](https://linux-hardware.org/?probe=fb3741faab) | Jul 21, 2022 |
| ASRock        | X570 Taichi                 | [56d5853243](https://linux-hardware.org/?probe=56d5853243) | Jul 19, 2022 |
| MSI           | MEG X570 UNIFY              | [d3d26541f1](https://linux-hardware.org/?probe=d3d26541f1) | Jul 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e6b6d3b5e6](https://linux-hardware.org/?probe=e6b6d3b5e6) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [93f8a4ce9f](https://linux-hardware.org/?probe=93f8a4ce9f) | Jul 16, 2022 |
| Gigabyte      | Z590 UD                     | [e9e0b50bbb](https://linux-hardware.org/?probe=e9e0b50bbb) | Jul 15, 2022 |
| MSI           | Z87-G45 GAMING              | [8602f7246a](https://linux-hardware.org/?probe=8602f7246a) | Jul 12, 2022 |
| Gigabyte      | B450 AORUS M                | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Dell          | 0J3C2F A02                  | [dccb88852f](https://linux-hardware.org/?probe=dccb88852f) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Dell          | 0J3C2F A02                  | [aa87616696](https://linux-hardware.org/?probe=aa87616696) | Jul 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [685e3d36bc](https://linux-hardware.org/?probe=685e3d36bc) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b436712f17](https://linux-hardware.org/?probe=b436712f17) | Jul 04, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [d442c531e8](https://linux-hardware.org/?probe=d442c531e8) | Jul 03, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [cf8784ac23](https://linux-hardware.org/?probe=cf8784ac23) | Jul 03, 2022 |
| ASUSTek       | PRIME Z390-A                | [1af80d1cdb](https://linux-hardware.org/?probe=1af80d1cdb) | Jul 01, 2022 |
| ASUSTek       | M3A78-CM                    | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [f03dcf744a](https://linux-hardware.org/?probe=f03dcf744a) | Jun 26, 2022 |
| Gigabyte      | Z590 UD                     | [74060af6fc](https://linux-hardware.org/?probe=74060af6fc) | Jun 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| ASRock        | B450 Pro4                   | [9d03e8cba7](https://linux-hardware.org/?probe=9d03e8cba7) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek       | M3A78-CM                    | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Pegatron      | 2ACE                        | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Unknown       | Unknown                     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| Unknown       | Unknown                     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| MSI           | X570-A PRO                  | [102ed915c5](https://linux-hardware.org/?probe=102ed915c5) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| ASUSTek       | Z170-A                      | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| ASUSTek       | Z170-A                      | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| MSI           | PRO Z690-A DDR4             | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| Intel         | D54250WYK H13922-303        | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| ASRockRack    | E3C232D2I                   | [0442460b97](https://linux-hardware.org/?probe=0442460b97) | May 24, 2022 |
| Unknown       | Unknown                     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| Apple         | Mac-F221BEC8                | [e254f29ffd](https://linux-hardware.org/?probe=e254f29ffd) | May 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| ASUSTek       | Rampage V EXTREME           | [ce350dd874](https://linux-hardware.org/?probe=ce350dd874) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek       | PRIME X570-PRO              | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| ASUSTek       | M3A78-CM                    | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [818ee286b7](https://linux-hardware.org/?probe=818ee286b7) | May 17, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [9afc74ed46](https://linux-hardware.org/?probe=9afc74ed46) | May 16, 2022 |
| MSI           | X570-A PRO                  | [28b47bc364](https://linux-hardware.org/?probe=28b47bc364) | May 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [49a3292018](https://linux-hardware.org/?probe=49a3292018) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| Dell          | 0J3C2F A02                  | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [df570dd8e0](https://linux-hardware.org/?probe=df570dd8e0) | May 12, 2022 |
| Gigabyte      | Z590 UD                     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| HP            | 8704                        | [b66f290b02](https://linux-hardware.org/?probe=b66f290b02) | May 09, 2022 |
| Dell          | 0J3C2F A02                  | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| ASRock        | A320M Pro4                  | [b51c7ae18b](https://linux-hardware.org/?probe=b51c7ae18b) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Gigabyte      | GA-970A-D3                  | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| ASRock        | X370 Gaming X               | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [970d30df6d](https://linux-hardware.org/?probe=970d30df6d) | Apr 29, 2022 |
| ASRock        | A520M Pro4                  | [45630a42df](https://linux-hardware.org/?probe=45630a42df) | Apr 29, 2022 |
| Dell          | 0J37VM A00                  | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [82b11931ed](https://linux-hardware.org/?probe=82b11931ed) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI           | Z390-A PRO                  | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [fb3e0b6b22](https://linux-hardware.org/?probe=fb3e0b6b22) | Apr 18, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [fa96d5405d](https://linux-hardware.org/?probe=fa96d5405d) | Apr 17, 2022 |
| ASRockRack    | X470D4U                     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [474bb81b18](https://linux-hardware.org/?probe=474bb81b18) | Apr 15, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [f6a1a50a75](https://linux-hardware.org/?probe=f6a1a50a75) | Apr 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d14605acc1](https://linux-hardware.org/?probe=d14605acc1) | Apr 15, 2022 |
| ASUSTek       | Z97-K/USB                   | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASRock        | A320M-ITX                   | [eaf6bbd74e](https://linux-hardware.org/?probe=eaf6bbd74e) | Apr 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI           | B450-A PRO MAX              | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [68dd0c90a1](https://linux-hardware.org/?probe=68dd0c90a1) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| ASRock        | Z390 Extreme4               | [1bd70fbd59](https://linux-hardware.org/?probe=1bd70fbd59) | Apr 09, 2022 |
| Gigabyte      | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| MSI           | MAG B550 TORPEDO            | [ce26da001a](https://linux-hardware.org/?probe=ce26da001a) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [8aad15d96c](https://linux-hardware.org/?probe=8aad15d96c) | Apr 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [5bcff46ee9](https://linux-hardware.org/?probe=5bcff46ee9) | Apr 04, 2022 |
| ASUSTek       | PRIME X570-PRO              | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| Gigabyte      | X570 GAMING X               | [348ccc5750](https://linux-hardware.org/?probe=348ccc5750) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | [32eabd9ac8](https://linux-hardware.org/?probe=32eabd9ac8) | Apr 01, 2022 |
| ASRock        | Z170A-X1                    | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI           | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| Gigabyte      | Z590 UD                     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| MSI           | MAG B550M MORTAR            | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [a2b06f49d3](https://linux-hardware.org/?probe=a2b06f49d3) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [9e32abccd6](https://linux-hardware.org/?probe=9e32abccd6) | Mar 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| MSI           | B560M PRO-VDH WIFI          | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| ASUSTek       | PRIME J4005I-C              | [707cb5ce3b](https://linux-hardware.org/?probe=707cb5ce3b) | Mar 14, 2022 |
| Intel         | DH61WW AAG23116-302         | [20682db2fa](https://linux-hardware.org/?probe=20682db2fa) | Mar 14, 2022 |
| Alienware     | 0TYR0X A00                  | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| Dell          | 0J37VM A00                  | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| ASRock        | A300M-STX                   | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Alienware     | 0TYR0X A00                  | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4c3afa7f](https://linux-hardware.org/?probe=6d4c3afa7f) | Feb 27, 2022 |
| Gigabyte      | Z590 UD                     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Gigabyte      | Z590 UD                     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| Alienware     | 0TYR0X A00                  | [892e886901](https://linux-hardware.org/?probe=892e886901) | Feb 23, 2022 |
| Alienware     | 0TYR0X A00                  | [71cac3ebdd](https://linux-hardware.org/?probe=71cac3ebdd) | Feb 22, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [6d5688db26](https://linux-hardware.org/?probe=6d5688db26) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| MSI           | H81I                        | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [1429fd9ed5](https://linux-hardware.org/?probe=1429fd9ed5) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | [859adc5b97](https://linux-hardware.org/?probe=859adc5b97) | Feb 19, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [eddf69336b](https://linux-hardware.org/?probe=eddf69336b) | Feb 18, 2022 |
| Gigabyte      | B460 HD3                    | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| YANYU         | H17SL                       | [0a6638d9c9](https://linux-hardware.org/?probe=0a6638d9c9) | Feb 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| ASRock        | B450 Pro4                   | [9f05ddfb03](https://linux-hardware.org/?probe=9f05ddfb03) | Feb 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| YANYU         | H17SL                       | [cd763ca612](https://linux-hardware.org/?probe=cd763ca612) | Feb 06, 2022 |
| Supermicro    | A1SRM-2758F                 | [33b8806332](https://linux-hardware.org/?probe=33b8806332) | Feb 05, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [59d4e2a5b2](https://linux-hardware.org/?probe=59d4e2a5b2) | Feb 04, 2022 |
| Gigabyte      | Z490 UD                     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| ASUSTek       | PRIME B450M-K               | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASRock        | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| ASRock        | A88M-G                      | [bb3847af5e](https://linux-hardware.org/?probe=bb3847af5e) | Jan 27, 2022 |
| ASRock        | A88M-G                      | [7f86f91b8f](https://linux-hardware.org/?probe=7f86f91b8f) | Jan 27, 2022 |
| Gigabyte      | B450M S2H                   | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [db8b77c1ff](https://linux-hardware.org/?probe=db8b77c1ff) | Jan 23, 2022 |
| Gigabyte      | Z490 UD                     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| ASUSTek       | PRIME B450M-K               | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | [d1697052d6](https://linux-hardware.org/?probe=d1697052d6) | Jan 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | [81642886bd](https://linux-hardware.org/?probe=81642886bd) | Jan 17, 2022 |
| ASRock        | AM1H-ITX                    | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | [73773b7de6](https://linux-hardware.org/?probe=73773b7de6) | Jan 16, 2022 |
| Lenovo        | 0B98401 PRO                 | [a3711dfcf9](https://linux-hardware.org/?probe=a3711dfcf9) | Jan 15, 2022 |
| Lenovo        | 0B98401 PRO                 | [c973a9bc0d](https://linux-hardware.org/?probe=c973a9bc0d) | Jan 15, 2022 |
| ASRock        | AM1H-ITX                    | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| ASRock        | Q1900-ITX                   | [a0983541e3](https://linux-hardware.org/?probe=a0983541e3) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [596fafa091](https://linux-hardware.org/?probe=596fafa091) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [d4b7cd87ac](https://linux-hardware.org/?probe=d4b7cd87ac) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | [e7b19454b7](https://linux-hardware.org/?probe=e7b19454b7) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [519b9f223e](https://linux-hardware.org/?probe=519b9f223e) | Jan 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [87bdd946c8](https://linux-hardware.org/?probe=87bdd946c8) | Jan 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [cd39962883](https://linux-hardware.org/?probe=cd39962883) | Jan 02, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| EVGA          | Z390 DARK                   | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [53288b1a8b](https://linux-hardware.org/?probe=53288b1a8b) | Dec 23, 2021 |
| Dell          | 0J3C2F A02                  | [a450e584b2](https://linux-hardware.org/?probe=a450e584b2) | Dec 22, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Dell          | 0J3C2F A02                  | [b6d326beab](https://linux-hardware.org/?probe=b6d326beab) | Dec 16, 2021 |
| MSI           | Z87-G45 GAMING              | [882428b431](https://linux-hardware.org/?probe=882428b431) | Dec 15, 2021 |
| ASUSTek       | M3N78-EM                    | [bf180c5c33](https://linux-hardware.org/?probe=bf180c5c33) | Dec 11, 2021 |
| MSI           | B450 TOMAHAWK               | [4b39700892](https://linux-hardware.org/?probe=4b39700892) | Dec 09, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [87c78340f0](https://linux-hardware.org/?probe=87c78340f0) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| Dell          | 0J584C A00                  | [d443412bd4](https://linux-hardware.org/?probe=d443412bd4) | Dec 03, 2021 |
| ASRock        | H110M-HDV R3.0              | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b0329b0b3f](https://linux-hardware.org/?probe=b0329b0b3f) | Nov 25, 2021 |
| MSI           | MEG X570 UNIFY              | [4492677869](https://linux-hardware.org/?probe=4492677869) | Nov 24, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [8145468390](https://linux-hardware.org/?probe=8145468390) | Nov 22, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [ddb6ba2a2b](https://linux-hardware.org/?probe=ddb6ba2a2b) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | [f8501c9239](https://linux-hardware.org/?probe=f8501c9239) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [734028d2b9](https://linux-hardware.org/?probe=734028d2b9) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | [d8c73031f1](https://linux-hardware.org/?probe=d8c73031f1) | Nov 20, 2021 |
| Gigabyte      | H310M S2H x.x               | [10578c9535](https://linux-hardware.org/?probe=10578c9535) | Nov 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6d93d44cf9](https://linux-hardware.org/?probe=6d93d44cf9) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| ASUSTek       | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASRock        | B550M Steel Legend          | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| ASUSTek       | PRIME X570-P                | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| MSI           | H110M PRO-D                 | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek       | Z170-A                      | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| Gigabyte      | B460 HD3                    | [d3aa74a821](https://linux-hardware.org/?probe=d3aa74a821) | Oct 29, 2021 |
| ASRock        | B550M Steel Legend          | [df8ab9effb](https://linux-hardware.org/?probe=df8ab9effb) | Oct 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| HP            | 0B4Ch D                     | [eb0c052885](https://linux-hardware.org/?probe=eb0c052885) | Oct 26, 2021 |
| ASUSTek       | PRIME A520M-K               | [740c97fb1c](https://linux-hardware.org/?probe=740c97fb1c) | Oct 26, 2021 |
| ASUSTek       | M3A78-CM                    | [aa48dedaf3](https://linux-hardware.org/?probe=aa48dedaf3) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASRock        | X570 Pro4                   | [ba339b925b](https://linux-hardware.org/?probe=ba339b925b) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | [7ffce9bbc2](https://linux-hardware.org/?probe=7ffce9bbc2) | Oct 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [21110235eb](https://linux-hardware.org/?probe=21110235eb) | Oct 18, 2021 |
| ASRock        | X370 Killer SLI/ac          | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [8b5c674cb9](https://linux-hardware.org/?probe=8b5c674cb9) | Oct 17, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [38a6005914](https://linux-hardware.org/?probe=38a6005914) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [a6457a6f8e](https://linux-hardware.org/?probe=a6457a6f8e) | Oct 15, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [5d6b978099](https://linux-hardware.org/?probe=5d6b978099) | Oct 14, 2021 |
| ASRock        | Z390 Extreme4               | [2da9a06ef2](https://linux-hardware.org/?probe=2da9a06ef2) | Oct 11, 2021 |
| MSI           | MEG X570 UNIFY              | [2e312a734f](https://linux-hardware.org/?probe=2e312a734f) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [8319b2b5c6](https://linux-hardware.org/?probe=8319b2b5c6) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H V2               | [233f451319](https://linux-hardware.org/?probe=233f451319) | Oct 06, 2021 |
| HP            | 0B4Ch D                     | [02b5492901](https://linux-hardware.org/?probe=02b5492901) | Oct 06, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [67fc73c11e](https://linux-hardware.org/?probe=67fc73c11e) | Oct 04, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| MSI           | Z370-A PRO                  | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [5ce182d7ae](https://linux-hardware.org/?probe=5ce182d7ae) | Oct 01, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [4044b3b3b2](https://linux-hardware.org/?probe=4044b3b3b2) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [6b625a8736](https://linux-hardware.org/?probe=6b625a8736) | Oct 01, 2021 |
| ASUSTek       | Maximus VIII HERO           | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [87f779767d](https://linux-hardware.org/?probe=87f779767d) | Oct 01, 2021 |
| Acer          | Aspire XC-780               | [f723ac396a](https://linux-hardware.org/?probe=f723ac396a) | Oct 01, 2021 |
| ASRock        | H170 Pro4                   | [a0d0f5002e](https://linux-hardware.org/?probe=a0d0f5002e) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | [5a3652f38b](https://linux-hardware.org/?probe=5a3652f38b) | Sep 29, 2021 |
| Gigabyte      | 990FXA-UD5                  | [c3bb6d3afa](https://linux-hardware.org/?probe=c3bb6d3afa) | Sep 29, 2021 |
| Dell          | 0J3C2F A02                  | [88104169a4](https://linux-hardware.org/?probe=88104169a4) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [241866fa37](https://linux-hardware.org/?probe=241866fa37) | Sep 26, 2021 |
| ASRock        | X370 Professional Gaming    | [546f692061](https://linux-hardware.org/?probe=546f692061) | Sep 23, 2021 |
| Intel         | DG31PR AAD97573-205         | [2c022c21f0](https://linux-hardware.org/?probe=2c022c21f0) | Sep 22, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [86d356f643](https://linux-hardware.org/?probe=86d356f643) | Sep 16, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Dell          | 0YJPT1 A00                  | [69d571e9f5](https://linux-hardware.org/?probe=69d571e9f5) | Sep 15, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [308d39b0dc](https://linux-hardware.org/?probe=308d39b0dc) | Sep 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [19555ed132](https://linux-hardware.org/?probe=19555ed132) | Sep 07, 2021 |
| ASRock        | B450M-HDV R4.0              | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | P5P41C                      | [e68f372c7b](https://linux-hardware.org/?probe=e68f372c7b) | Sep 05, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [f63a2003ab](https://linux-hardware.org/?probe=f63a2003ab) | Sep 05, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [40d01ef03e](https://linux-hardware.org/?probe=40d01ef03e) | Aug 31, 2021 |
| Packard Be... | FMCP7AM                     | [6872ae9fb4](https://linux-hardware.org/?probe=6872ae9fb4) | Aug 31, 2021 |
| Gigabyte      | EP43-DS3                    | [0eaf518e06](https://linux-hardware.org/?probe=0eaf518e06) | Aug 29, 2021 |
| Dell          | 0U1325                      | [0a58fab188](https://linux-hardware.org/?probe=0a58fab188) | Aug 28, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [00b0f43680](https://linux-hardware.org/?probe=00b0f43680) | Aug 28, 2021 |
| Packard Be... | FMCP7AM                     | [07fb4f5678](https://linux-hardware.org/?probe=07fb4f5678) | Aug 28, 2021 |
| MSI           | MS-7369                     | [0c6668dee5](https://linux-hardware.org/?probe=0c6668dee5) | Aug 28, 2021 |
| Dell          | 0U1325                      | [1b5dfb4b59](https://linux-hardware.org/?probe=1b5dfb4b59) | Aug 28, 2021 |
| ASUSTek       | P9X79 WS                    | [0569365ea0](https://linux-hardware.org/?probe=0569365ea0) | Aug 26, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f521a0c69c](https://linux-hardware.org/?probe=f521a0c69c) | Aug 25, 2021 |
| MSI           | B450M PRO-M2 MAX            | [c09944da60](https://linux-hardware.org/?probe=c09944da60) | Aug 24, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | [c6aaf9451f](https://linux-hardware.org/?probe=c6aaf9451f) | Aug 22, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [ae02b6e88b](https://linux-hardware.org/?probe=ae02b6e88b) | Aug 19, 2021 |
| ASUSTek       | P5P41C                      | [0eb4111089](https://linux-hardware.org/?probe=0eb4111089) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [4eb4c77752](https://linux-hardware.org/?probe=4eb4c77752) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5ffe57957d](https://linux-hardware.org/?probe=5ffe57957d) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [40f0739800](https://linux-hardware.org/?probe=40f0739800) | Aug 17, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [211803a510](https://linux-hardware.org/?probe=211803a510) | Aug 15, 2021 |
| MSI           | B550-A PRO                  | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| HP            | 158B                        | [d47aa82b20](https://linux-hardware.org/?probe=d47aa82b20) | Aug 12, 2021 |
| Unknown       | Unknown                     | [711599ea49](https://linux-hardware.org/?probe=711599ea49) | Aug 11, 2021 |
| Intel         | D525MW AAE93082-301         | [fc72f0a0ea](https://linux-hardware.org/?probe=fc72f0a0ea) | Aug 11, 2021 |
| ASUSTek       | PRIME X470-PRO              | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [d74d9e37ce](https://linux-hardware.org/?probe=d74d9e37ce) | Aug 10, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [33fffaf1c3](https://linux-hardware.org/?probe=33fffaf1c3) | Aug 07, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [ef7a0635f4](https://linux-hardware.org/?probe=ef7a0635f4) | Aug 04, 2021 |
| ASUSTek       | P6T DELUXE V2               | [51a1b8132e](https://linux-hardware.org/?probe=51a1b8132e) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| Dell          | 09WH54 A00                  | [9885d45d4f](https://linux-hardware.org/?probe=9885d45d4f) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [46b71409d7](https://linux-hardware.org/?probe=46b71409d7) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| Gigabyte      | 990FXA-UD5                  | [5a32ec902e](https://linux-hardware.org/?probe=5a32ec902e) | Jul 22, 2021 |
| Gigabyte      | H110-D3-CF                  | [7d25217f50](https://linux-hardware.org/?probe=7d25217f50) | Jul 22, 2021 |
| Gigabyte      | B460 HD3                    | [a43624a24b](https://linux-hardware.org/?probe=a43624a24b) | Jul 18, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [9356542b15](https://linux-hardware.org/?probe=9356542b15) | Jul 12, 2021 |
| ASRock        | B550M Steel Legend          | [4d378eb681](https://linux-hardware.org/?probe=4d378eb681) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| ASRock        | B550M Steel Legend          | [ab93056d13](https://linux-hardware.org/?probe=ab93056d13) | Jul 08, 2021 |
| MSI           | Z590-A PRO                  | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [4ef1e3ccac](https://linux-hardware.org/?probe=4ef1e3ccac) | Jul 03, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e618f85f9](https://linux-hardware.org/?probe=4e618f85f9) | Jul 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a2acbde7fd](https://linux-hardware.org/?probe=a2acbde7fd) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| MSI           | B450 TOMAHAWK               | [ac2a4b3aea](https://linux-hardware.org/?probe=ac2a4b3aea) | Jul 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8cc7c380d](https://linux-hardware.org/?probe=b8cc7c380d) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2831e5a8cf](https://linux-hardware.org/?probe=2831e5a8cf) | Jun 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d442a66371](https://linux-hardware.org/?probe=d442a66371) | Jun 27, 2021 |
| Apple         | Mac-F221BEC8                | [84bf6743c1](https://linux-hardware.org/?probe=84bf6743c1) | Jun 25, 2021 |
| Apple         | Mac-F221BEC8                | [ced7e0d00d](https://linux-hardware.org/?probe=ced7e0d00d) | Jun 25, 2021 |
| ASUSTek       | Rampage V EXTREME           | [4add1f32e4](https://linux-hardware.org/?probe=4add1f32e4) | Jun 23, 2021 |
| Unknown       | Unknown                     | [bb64d32fdf](https://linux-hardware.org/?probe=bb64d32fdf) | Jun 21, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f0c7a3a628](https://linux-hardware.org/?probe=f0c7a3a628) | Jun 15, 2021 |
| ASUSTek       | P7P55D-E PRO                | [9a91c78c7a](https://linux-hardware.org/?probe=9a91c78c7a) | Jun 14, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [704bf0bba3](https://linux-hardware.org/?probe=704bf0bba3) | Jun 12, 2021 |
| MSI           | Z97 PC Mate                 | [73ece6c322](https://linux-hardware.org/?probe=73ece6c322) | Jun 02, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [a04eb698f8](https://linux-hardware.org/?probe=a04eb698f8) | May 30, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [2767965856](https://linux-hardware.org/?probe=2767965856) | May 27, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [843f1d9b38](https://linux-hardware.org/?probe=843f1d9b38) | May 25, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [5794d366c2](https://linux-hardware.org/?probe=5794d366c2) | May 25, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [49458a2df1](https://linux-hardware.org/?probe=49458a2df1) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [73ff247804](https://linux-hardware.org/?probe=73ff247804) | May 24, 2021 |
| MSI           | X570-A PRO                  | [61a5d17b5b](https://linux-hardware.org/?probe=61a5d17b5b) | May 22, 2021 |
| MSI           | Z590-A PRO                  | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Unknown       | Cubietech Cubieboard2       | [d777d4b535](https://linux-hardware.org/?probe=d777d4b535) | May 22, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [95fb77ceae](https://linux-hardware.org/?probe=95fb77ceae) | May 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [1c2f94847e](https://linux-hardware.org/?probe=1c2f94847e) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | [5104abb7a7](https://linux-hardware.org/?probe=5104abb7a7) | May 20, 2021 |
| HP            | 8643 SMVB                   | [b183baddef](https://linux-hardware.org/?probe=b183baddef) | May 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4f3165b957](https://linux-hardware.org/?probe=4f3165b957) | May 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2679a5931a](https://linux-hardware.org/?probe=2679a5931a) | May 19, 2021 |
| ASRock        | B450 Pro4                   | [7ae6a0f74b](https://linux-hardware.org/?probe=7ae6a0f74b) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| MSI           | Z590-A PRO                  | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| ASUSTek       | PRIME X470-PRO              | [065d69be16](https://linux-hardware.org/?probe=065d69be16) | May 13, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| ASUSTek       | M3A78-CM                    | [e305a7301f](https://linux-hardware.org/?probe=e305a7301f) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| ASUSTek       | PRIME B450M-K               | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [aff27ae264](https://linux-hardware.org/?probe=aff27ae264) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | [fe32c3d470](https://linux-hardware.org/?probe=fe32c3d470) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | [ff1723016b](https://linux-hardware.org/?probe=ff1723016b) | Apr 27, 2021 |
| Unknown       | Freecom Silverstore HNCN... | [c54d9f2c0c](https://linux-hardware.org/?probe=c54d9f2c0c) | Apr 23, 2021 |
| Unknown       | Unknown                     | [160f692db0](https://linux-hardware.org/?probe=160f692db0) | Apr 23, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [0db8148a33](https://linux-hardware.org/?probe=0db8148a33) | Apr 17, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5bc34889b8](https://linux-hardware.org/?probe=5bc34889b8) | Apr 17, 2021 |
| MSI           | H310M PRO-VD PLUS           | [de7b86720f](https://linux-hardware.org/?probe=de7b86720f) | Apr 10, 2021 |
| ASRock        | C2550D4I                    | [c881809c02](https://linux-hardware.org/?probe=c881809c02) | Apr 09, 2021 |
| ASRockRack    | E3C232D2I                   | [5f8788ee08](https://linux-hardware.org/?probe=5f8788ee08) | Apr 09, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [07427b8218](https://linux-hardware.org/?probe=07427b8218) | Apr 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [ab8b789fc2](https://linux-hardware.org/?probe=ab8b789fc2) | Apr 06, 2021 |
| Gigabyte      | B450M AORUS ELITE           | [62a8a899ed](https://linux-hardware.org/?probe=62a8a899ed) | Apr 05, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1f560968ab](https://linux-hardware.org/?probe=1f560968ab) | Apr 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | [d51b8b7f04](https://linux-hardware.org/?probe=d51b8b7f04) | Apr 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| ASUSTek       | P8H67-M PRO                 | [95722413a6](https://linux-hardware.org/?probe=95722413a6) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [65b87ee7d8](https://linux-hardware.org/?probe=65b87ee7d8) | Mar 29, 2021 |
| ASRock        | 970 Pro3 R2.0               | [58e2163a18](https://linux-hardware.org/?probe=58e2163a18) | Mar 29, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f4da24790d](https://linux-hardware.org/?probe=f4da24790d) | Mar 27, 2021 |
| BESSTAR Te... | DMAF5 V1.0                  | [ea2ebcb877](https://linux-hardware.org/?probe=ea2ebcb877) | Mar 26, 2021 |
| ASRock        | Z68 Pro3                    | [8b7e56f2db](https://linux-hardware.org/?probe=8b7e56f2db) | Mar 25, 2021 |
| ASRock        | Z68 Pro3                    | [b0ddd79606](https://linux-hardware.org/?probe=b0ddd79606) | Mar 24, 2021 |
| ASUSTek       | M4N78-VM                    | [b3d61c6fbd](https://linux-hardware.org/?probe=b3d61c6fbd) | Mar 24, 2021 |
| MSI           | Z390-A PRO                  | [85f1a92a8a](https://linux-hardware.org/?probe=85f1a92a8a) | Mar 24, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [b89f0d11bd](https://linux-hardware.org/?probe=b89f0d11bd) | Mar 23, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [c17cb184a4](https://linux-hardware.org/?probe=c17cb184a4) | Mar 22, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [26b5c18aba](https://linux-hardware.org/?probe=26b5c18aba) | Mar 22, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| ASRock        | B450M Pro4                  | [41c48a20a2](https://linux-hardware.org/?probe=41c48a20a2) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASRock        | B450M Pro4                  | [b075ade19c](https://linux-hardware.org/?probe=b075ade19c) | Mar 18, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | [003b473b29](https://linux-hardware.org/?probe=003b473b29) | Mar 17, 2021 |
| ASUSTek       | P5Q-E                       | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| ASUSTek       | B85M-E                      | [46c2411987](https://linux-hardware.org/?probe=46c2411987) | Mar 17, 2021 |
| ASRock        | X370 Professional Gaming    | [677c76f624](https://linux-hardware.org/?probe=677c76f624) | Mar 17, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [fb88aba821](https://linux-hardware.org/?probe=fb88aba821) | Mar 17, 2021 |
| MSI           | B450I GAMING PLUS AC        | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| ASUSTek       | PRIME X570-P                | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [bf856bd378](https://linux-hardware.org/?probe=bf856bd378) | Mar 11, 2021 |
| MSI           | X570-A PRO                  | [c19dde029b](https://linux-hardware.org/?probe=c19dde029b) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [0c34f3246f](https://linux-hardware.org/?probe=0c34f3246f) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [fb91319fa1](https://linux-hardware.org/?probe=fb91319fa1) | Mar 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [9f55c5ece0](https://linux-hardware.org/?probe=9f55c5ece0) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [927ea68f9f](https://linux-hardware.org/?probe=927ea68f9f) | Mar 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [413e1f3dd7](https://linux-hardware.org/?probe=413e1f3dd7) | Mar 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [44904f3de6](https://linux-hardware.org/?probe=44904f3de6) | Mar 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [6cd953f597](https://linux-hardware.org/?probe=6cd953f597) | Mar 02, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [d7a5611d8a](https://linux-hardware.org/?probe=d7a5611d8a) | Feb 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d854654bad](https://linux-hardware.org/?probe=d854654bad) | Feb 23, 2021 |
| MSI           | 970 GAMING                  | [062ccac9ff](https://linux-hardware.org/?probe=062ccac9ff) | Feb 22, 2021 |
| ASUSTek       | PRIME H470M-PLUS            | [0e4ce5d923](https://linux-hardware.org/?probe=0e4ce5d923) | Feb 22, 2021 |
| ASUSTek       | M3A78-CM                    | [ae309000e1](https://linux-hardware.org/?probe=ae309000e1) | Feb 22, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [ede7d0e26c](https://linux-hardware.org/?probe=ede7d0e26c) | Feb 21, 2021 |
| ASRock        | X370 Gaming X               | [97b686fad6](https://linux-hardware.org/?probe=97b686fad6) | Feb 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f9639ea950](https://linux-hardware.org/?probe=f9639ea950) | Feb 20, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [ac8250480a](https://linux-hardware.org/?probe=ac8250480a) | Feb 16, 2021 |
| MSI           | B450-A PRO                  | [211cb068ce](https://linux-hardware.org/?probe=211cb068ce) | Feb 16, 2021 |
| MSI           | MEG X570 UNIFY              | [8565fa7232](https://linux-hardware.org/?probe=8565fa7232) | Feb 15, 2021 |
| MSI           | B350M BAZOOKA               | [19cf6a4def](https://linux-hardware.org/?probe=19cf6a4def) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V LX                  | [47dbd40dae](https://linux-hardware.org/?probe=47dbd40dae) | Feb 13, 2021 |
| ASUSTek       | PRIME H470M-PLUS            | [925a360f1f](https://linux-hardware.org/?probe=925a360f1f) | Feb 12, 2021 |
| ASRock        | AM1H-ITX                    | [a1c5772342](https://linux-hardware.org/?probe=a1c5772342) | Feb 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0d787440f2](https://linux-hardware.org/?probe=0d787440f2) | Feb 01, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [ec933f8e8a](https://linux-hardware.org/?probe=ec933f8e8a) | Jan 31, 2021 |
| ASUSTek       | PRIME X570-P                | [d566b4292e](https://linux-hardware.org/?probe=d566b4292e) | Jan 30, 2021 |
| Gigabyte      | MZBSWAP-00                  | [970493cf1b](https://linux-hardware.org/?probe=970493cf1b) | Jan 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6d86921fcf](https://linux-hardware.org/?probe=6d86921fcf) | Jan 26, 2021 |
| ASRock        | X370 Gaming X               | [8f0d93f4e1](https://linux-hardware.org/?probe=8f0d93f4e1) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [1b3702adc5](https://linux-hardware.org/?probe=1b3702adc5) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [8eb3edac54](https://linux-hardware.org/?probe=8eb3edac54) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [dc087e0399](https://linux-hardware.org/?probe=dc087e0399) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [de171f7a35](https://linux-hardware.org/?probe=de171f7a35) | Jan 24, 2021 |
| MSI           | Z170-A PRO                  | [6c8926dc8c](https://linux-hardware.org/?probe=6c8926dc8c) | Jan 23, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [23602ad020](https://linux-hardware.org/?probe=23602ad020) | Jan 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [b5f6cc5993](https://linux-hardware.org/?probe=b5f6cc5993) | Jan 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8c1e988f7e](https://linux-hardware.org/?probe=8c1e988f7e) | Jan 18, 2021 |
| MSI           | MEG X570 GODLIKE            | [5964a40d34](https://linux-hardware.org/?probe=5964a40d34) | Jan 17, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [25fb58cc9f](https://linux-hardware.org/?probe=25fb58cc9f) | Jan 16, 2021 |
| Gigabyte      | Z170X-Gaming 3              | [e4ab17605e](https://linux-hardware.org/?probe=e4ab17605e) | Jan 13, 2021 |
| ASRock        | J3455-ITX                   | [89257face1](https://linux-hardware.org/?probe=89257face1) | Jan 12, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [38332ee350](https://linux-hardware.org/?probe=38332ee350) | Jan 11, 2021 |
| HP            | 158B                        | [6bc73950dd](https://linux-hardware.org/?probe=6bc73950dd) | Jan 10, 2021 |
| ASRock        | B450 Pro4                   | [1b9975eef6](https://linux-hardware.org/?probe=1b9975eef6) | Jan 08, 2021 |
| ASRock        | X570 Steel Legend           | [48d53df339](https://linux-hardware.org/?probe=48d53df339) | Jan 08, 2021 |
| HP            | 1495                        | [ffb9d2f433](https://linux-hardware.org/?probe=ffb9d2f433) | Jan 08, 2021 |
| MSI           | 990FXA-GD80                 | [cc4b365068](https://linux-hardware.org/?probe=cc4b365068) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| ASRock        | AB350M Pro4                 | [b75dcb6545](https://linux-hardware.org/?probe=b75dcb6545) | Jan 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6f95de2b32](https://linux-hardware.org/?probe=6f95de2b32) | Jan 05, 2021 |
| ASUSTek       | P5Q-E                       | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a011c9b38f](https://linux-hardware.org/?probe=a011c9b38f) | Jan 02, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [182deb31fb](https://linux-hardware.org/?probe=182deb31fb) | Jan 02, 2021 |
| ASRock        | Q1900-ITX                   | [78f7e1012f](https://linux-hardware.org/?probe=78f7e1012f) | Jan 02, 2021 |
| ASRock        | 970 Pro3 R2.0               | [b83ea4b5b3](https://linux-hardware.org/?probe=b83ea4b5b3) | Jan 02, 2021 |
| ASRock        | AM1H-ITX                    | [2bd69bdc3e](https://linux-hardware.org/?probe=2bd69bdc3e) | Dec 27, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [87e72db668](https://linux-hardware.org/?probe=87e72db668) | Dec 23, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d00787942f](https://linux-hardware.org/?probe=d00787942f) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| Unknown       | Cubietech Cubieboard2       | [62e837d6a6](https://linux-hardware.org/?probe=62e837d6a6) | Dec 20, 2020 |
| ASRock        | X570 Taichi                 | [29d14ce28a](https://linux-hardware.org/?probe=29d14ce28a) | Dec 19, 2020 |
| MSI           | B350M BAZOOKA               | [4ceacadb9f](https://linux-hardware.org/?probe=4ceacadb9f) | Dec 17, 2020 |
| HP            | 3033h                       | [ff36d785e1](https://linux-hardware.org/?probe=ff36d785e1) | Dec 14, 2020 |
| ASRock        | X570 Phantom Gaming X       | [c1777903bd](https://linux-hardware.org/?probe=c1777903bd) | Dec 14, 2020 |
| ASRock        | H170M Pro4S                 | [debbcde352](https://linux-hardware.org/?probe=debbcde352) | Dec 11, 2020 |
| Acer          | Aspire TC-605               | [844d2c69e2](https://linux-hardware.org/?probe=844d2c69e2) | Dec 07, 2020 |
| MSI           | 970A SLI Krait Edition      | [1bec700189](https://linux-hardware.org/?probe=1bec700189) | Dec 07, 2020 |
| MSI           | 970A SLI Krait Edition      | [8d56de5850](https://linux-hardware.org/?probe=8d56de5850) | Dec 07, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [e8e2d0cdfc](https://linux-hardware.org/?probe=e8e2d0cdfc) | Dec 05, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3dc100c9a1](https://linux-hardware.org/?probe=3dc100c9a1) | Dec 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [50917002e1](https://linux-hardware.org/?probe=50917002e1) | Dec 01, 2020 |
| MSI           | B450M PRO-VDH MAX           | [03753743e7](https://linux-hardware.org/?probe=03753743e7) | Nov 30, 2020 |
| Gigabyte      | EP45T-DS3                   | [45142a6931](https://linux-hardware.org/?probe=45142a6931) | Nov 30, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7eeb446aee](https://linux-hardware.org/?probe=7eeb446aee) | Nov 30, 2020 |
| ASUSTek       | P9X79 WS                    | [24cfa19ea6](https://linux-hardware.org/?probe=24cfa19ea6) | Nov 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ba86d65e42](https://linux-hardware.org/?probe=ba86d65e42) | Nov 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78d68d35d8](https://linux-hardware.org/?probe=78d68d35d8) | Nov 26, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [35233c6000](https://linux-hardware.org/?probe=35233c6000) | Nov 26, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dcaf1f3521](https://linux-hardware.org/?probe=dcaf1f3521) | Nov 24, 2020 |
| ASUSTek       | P8Z77-V LX                  | [af91f8b0d0](https://linux-hardware.org/?probe=af91f8b0d0) | Nov 24, 2020 |
| MSI           | B350 GAMING PLUS            | [3e9e5d4c8d](https://linux-hardware.org/?probe=3e9e5d4c8d) | Nov 22, 2020 |
| MSI           | B350 GAMING PLUS            | [6692a5c759](https://linux-hardware.org/?probe=6692a5c759) | Nov 22, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | [9b888a1a9c](https://linux-hardware.org/?probe=9b888a1a9c) | Nov 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [a6ab09a54b](https://linux-hardware.org/?probe=a6ab09a54b) | Nov 19, 2020 |
| ASRock        | X570 Pro4                   | [963200e763](https://linux-hardware.org/?probe=963200e763) | Nov 18, 2020 |
| ASUSTek       | PRIME X370-PRO              | [04abcfd451](https://linux-hardware.org/?probe=04abcfd451) | Nov 18, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [7ac134ec7a](https://linux-hardware.org/?probe=7ac134ec7a) | Nov 18, 2020 |
| ASUSTek       | PRIME X470-PRO              | [a4bdac2cea](https://linux-hardware.org/?probe=a4bdac2cea) | Nov 18, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | [d46b466047](https://linux-hardware.org/?probe=d46b466047) | Nov 15, 2020 |
| ASRock        | B450 Pro4                   | [c920df4f73](https://linux-hardware.org/?probe=c920df4f73) | Nov 13, 2020 |
| MSI           | Z97-G43                     | [5f93bb3faa](https://linux-hardware.org/?probe=5f93bb3faa) | Nov 13, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | [2c09ef9780](https://linux-hardware.org/?probe=2c09ef9780) | Nov 10, 2020 |
| MSI           | B450-A PRO                  | [00aeeab6da](https://linux-hardware.org/?probe=00aeeab6da) | Nov 08, 2020 |
| MSI           | B450-A PRO                  | [cd67b65826](https://linux-hardware.org/?probe=cd67b65826) | Nov 06, 2020 |
| ASUSTek       | A88XM-A                     | [45cf973d9c](https://linux-hardware.org/?probe=45cf973d9c) | Oct 31, 2020 |
| MSI           | Z170-A PRO                  | [6f36f04e56](https://linux-hardware.org/?probe=6f36f04e56) | Oct 31, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | [539bba5a4d](https://linux-hardware.org/?probe=539bba5a4d) | Oct 26, 2020 |
| ASRock        | AM1H-ITX                    | [4a6634694e](https://linux-hardware.org/?probe=4a6634694e) | Oct 25, 2020 |
| ASRock        | X370 Gaming X               | [7b50c1e794](https://linux-hardware.org/?probe=7b50c1e794) | Oct 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e24f7d7cf7](https://linux-hardware.org/?probe=e24f7d7cf7) | Oct 24, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | EB1012G                     | [95a54c7d29](https://linux-hardware.org/?probe=95a54c7d29) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-PRO              | [3a4156ad86](https://linux-hardware.org/?probe=3a4156ad86) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [3264edefe8](https://linux-hardware.org/?probe=3264edefe8) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [49f9ade50f](https://linux-hardware.org/?probe=49f9ade50f) | Oct 17, 2020 |
| Gigabyte      | H110M-S2V-CF                | [2fe8128b94](https://linux-hardware.org/?probe=2fe8128b94) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0ff8e9dda5](https://linux-hardware.org/?probe=0ff8e9dda5) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5f53a7b654](https://linux-hardware.org/?probe=5f53a7b654) | Oct 15, 2020 |
| HP            | 8643 SMVB                   | [b1ebd820ea](https://linux-hardware.org/?probe=b1ebd820ea) | Oct 14, 2020 |
| ASRock        | N3150-ITX                   | [50872ff699](https://linux-hardware.org/?probe=50872ff699) | Oct 14, 2020 |
| MSI           | Z370 PC PRO                 | [6fdfdd701e](https://linux-hardware.org/?probe=6fdfdd701e) | Oct 14, 2020 |
| Dell          | 0PC5F7 A02                  | [0b4436db73](https://linux-hardware.org/?probe=0b4436db73) | Oct 14, 2020 |
| Entroware     | Nyx                         | [e349c62572](https://linux-hardware.org/?probe=e349c62572) | Oct 14, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [bb7e9817f3](https://linux-hardware.org/?probe=bb7e9817f3) | Oct 13, 2020 |
| ASUSTek       | H97M-PLUS                   | [979e26a9ff](https://linux-hardware.org/?probe=979e26a9ff) | Oct 13, 2020 |
| Gigabyte      | H110M-S2V-CF                | [e13bfd8911](https://linux-hardware.org/?probe=e13bfd8911) | Oct 13, 2020 |
| ASRock        | X570M Pro4                  | [11624f2e68](https://linux-hardware.org/?probe=11624f2e68) | Oct 12, 2020 |
| ASRock        | X370 Professional Gaming    | [2b432df0be](https://linux-hardware.org/?probe=2b432df0be) | Oct 12, 2020 |
| ASUSTek       | P6X58D PREMIUM              | [9b3c10083c](https://linux-hardware.org/?probe=9b3c10083c) | Oct 11, 2020 |
| MSI           | MEG X570 UNIFY              | [bc040e4fa3](https://linux-hardware.org/?probe=bc040e4fa3) | Oct 08, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [4c9fc71c64](https://linux-hardware.org/?probe=4c9fc71c64) | Oct 06, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f3201a0e2c](https://linux-hardware.org/?probe=f3201a0e2c) | Oct 06, 2020 |
| MSI           | H310M PRO-VD PLUS           | [90021d6e51](https://linux-hardware.org/?probe=90021d6e51) | Oct 05, 2020 |
| ASUSTek       | H61M-K                      | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| MSI           | X370 XPOWER GAMING TITAN... | [f09de8f7dc](https://linux-hardware.org/?probe=f09de8f7dc) | Oct 01, 2020 |
| MSI           | X99A SLI PLUS               | [c77d27bdcd](https://linux-hardware.org/?probe=c77d27bdcd) | Sep 29, 2020 |
| Unknown       | Intel X79                   | [3849825892](https://linux-hardware.org/?probe=3849825892) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [b048626385](https://linux-hardware.org/?probe=b048626385) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [e26cc6bcb0](https://linux-hardware.org/?probe=e26cc6bcb0) | Sep 29, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6cbcba7414](https://linux-hardware.org/?probe=6cbcba7414) | Sep 28, 2020 |
| ASUSTek       | P9X79                       | [662a97173c](https://linux-hardware.org/?probe=662a97173c) | Sep 28, 2020 |
| MSI           | 970A-G43                    | [f71dd78128](https://linux-hardware.org/?probe=f71dd78128) | Sep 27, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [c8d28c60cd](https://linux-hardware.org/?probe=c8d28c60cd) | Sep 27, 2020 |
| ASRock        | Z170 OC Formula             | [b478607fef](https://linux-hardware.org/?probe=b478607fef) | Sep 26, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [0997ff40b0](https://linux-hardware.org/?probe=0997ff40b0) | Sep 26, 2020 |
| MSI           | X99A SLI PLUS               | [d0cf13bbc8](https://linux-hardware.org/?probe=d0cf13bbc8) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [00290a5d85](https://linux-hardware.org/?probe=00290a5d85) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [449d8022e1](https://linux-hardware.org/?probe=449d8022e1) | Sep 26, 2020 |
| MSI           | X58 Pro-E                   | [1ecbc5ccba](https://linux-hardware.org/?probe=1ecbc5ccba) | Sep 25, 2020 |
| ASUSTek       | H81M-PLUS                   | [87f345b258](https://linux-hardware.org/?probe=87f345b258) | Sep 24, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [644c742328](https://linux-hardware.org/?probe=644c742328) | Sep 23, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [aac147ef3c](https://linux-hardware.org/?probe=aac147ef3c) | Sep 22, 2020 |
| ASRock        | AB350M Pro4                 | [6cd6f20aef](https://linux-hardware.org/?probe=6cd6f20aef) | Sep 22, 2020 |
| ASUSTek       | Z97-A                       | [5104e708b9](https://linux-hardware.org/?probe=5104e708b9) | Sep 20, 2020 |
| ASUSTek       | Z97-A                       | [6505c46aec](https://linux-hardware.org/?probe=6505c46aec) | Sep 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f2bdd44684](https://linux-hardware.org/?probe=f2bdd44684) | Sep 18, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [15e4e278e8](https://linux-hardware.org/?probe=15e4e278e8) | Sep 18, 2020 |
| ASUSTek       | P5K-V                       | [04e5e2e796](https://linux-hardware.org/?probe=04e5e2e796) | Sep 17, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [cc1af2a4aa](https://linux-hardware.org/?probe=cc1af2a4aa) | Sep 16, 2020 |
| ASRock        | 970A-G                      | [c76564a1e5](https://linux-hardware.org/?probe=c76564a1e5) | Sep 16, 2020 |
| Unknown       | Unknown                     | [23a8f5bbfb](https://linux-hardware.org/?probe=23a8f5bbfb) | Sep 14, 2020 |
| Unknown       | Unknown                     | [47de429737](https://linux-hardware.org/?probe=47de429737) | Sep 07, 2020 |
| MSI           | Z170A GAMING PRO            | [a23e1ab6f7](https://linux-hardware.org/?probe=a23e1ab6f7) | Sep 06, 2020 |
| MSI           | Z170A GAMING PRO            | [e12a573590](https://linux-hardware.org/?probe=e12a573590) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a1cc53584d](https://linux-hardware.org/?probe=a1cc53584d) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d3510ce4e2](https://linux-hardware.org/?probe=d3510ce4e2) | Sep 04, 2020 |
| ASRock        | B450M-HDV R4.0              | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [4a62067798](https://linux-hardware.org/?probe=4a62067798) | Sep 03, 2020 |
| Gigabyte      | Z77X-UD5H                   | [ced4076cfe](https://linux-hardware.org/?probe=ced4076cfe) | Sep 03, 2020 |
| MSI           | B450M MORTAR MAX            | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [3aacd1b61b](https://linux-hardware.org/?probe=3aacd1b61b) | Sep 03, 2020 |
| MSI           | Z97-G45 GAMING              | [e86bf6dfb8](https://linux-hardware.org/?probe=e86bf6dfb8) | Sep 03, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4bf504d82b](https://linux-hardware.org/?probe=4bf504d82b) | Sep 03, 2020 |
| MSI           | X99A XPOWER GAMING TITAN... | [2c3ca5276b](https://linux-hardware.org/?probe=2c3ca5276b) | Sep 03, 2020 |
| MSI           | X470 GAMING PLUS            | [84aef475d9](https://linux-hardware.org/?probe=84aef475d9) | Sep 02, 2020 |
| ASUSTek       | Rampage V EXTREME           | [2669865bf9](https://linux-hardware.org/?probe=2669865bf9) | Aug 31, 2020 |
| ASUSTek       | M5A97                       | [8388fbe3b4](https://linux-hardware.org/?probe=8388fbe3b4) | Aug 31, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [804af7bd77](https://linux-hardware.org/?probe=804af7bd77) | Aug 29, 2020 |
| MSI           | Z77IA-E53                   | [bf99082e95](https://linux-hardware.org/?probe=bf99082e95) | Aug 28, 2020 |
| ASUSTek       | Z170-A                      | [af1f86e610](https://linux-hardware.org/?probe=af1f86e610) | Aug 25, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d17e5bf1f8](https://linux-hardware.org/?probe=d17e5bf1f8) | Aug 25, 2020 |
| ASUSTek       | PRIME X370-PRO              | [a0e30e712f](https://linux-hardware.org/?probe=a0e30e712f) | Aug 23, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [7152566435](https://linux-hardware.org/?probe=7152566435) | Aug 23, 2020 |
| Supermicro    | A1SRM-2758F                 | [b91457fee4](https://linux-hardware.org/?probe=b91457fee4) | Aug 22, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [1575c94669](https://linux-hardware.org/?probe=1575c94669) | Aug 20, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| Unknown       | Unknown                     | [41ab260322](https://linux-hardware.org/?probe=41ab260322) | Aug 20, 2020 |
| Unknown       | Unknown                     | [6a7fc0088c](https://linux-hardware.org/?probe=6a7fc0088c) | Aug 19, 2020 |
| MSI           | B350 GAMING PRO CARBON      | [762b0fed7b](https://linux-hardware.org/?probe=762b0fed7b) | Aug 18, 2020 |
| ASUSTek       | Z97-DELUXE                  | [766495711b](https://linux-hardware.org/?probe=766495711b) | Aug 17, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [32ae11e70f](https://linux-hardware.org/?probe=32ae11e70f) | Aug 15, 2020 |
| Unknown       | Unknown                     | [3d3ed1b8ce](https://linux-hardware.org/?probe=3d3ed1b8ce) | Aug 15, 2020 |
| Unknown       | Unknown                     | [55f1b3cdce](https://linux-hardware.org/?probe=55f1b3cdce) | Aug 15, 2020 |
| ASUSTek       | PRIME X370-PRO              | [7d01f814d5](https://linux-hardware.org/?probe=7d01f814d5) | Aug 10, 2020 |
| MSI           | B450I GAMING PLUS AC        | [d6a59a4350](https://linux-hardware.org/?probe=d6a59a4350) | Aug 10, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| ASUSTek       | P6X58D-E                    | [3db01937e1](https://linux-hardware.org/?probe=3db01937e1) | Aug 05, 2020 |
| Unknown       | Unknown                     | [978fcb3a51](https://linux-hardware.org/?probe=978fcb3a51) | Jul 31, 2020 |
| ASRock        | B85M-HDS                    | [7e7ad89d55](https://linux-hardware.org/?probe=7e7ad89d55) | Jul 29, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [9f29db1cee](https://linux-hardware.org/?probe=9f29db1cee) | Jul 28, 2020 |
| ASUSTek       | Rampage V EXTREME           | [554fbd9b8d](https://linux-hardware.org/?probe=554fbd9b8d) | Jul 28, 2020 |
| ASRock        | X570M Pro4                  | [9d082a4d26](https://linux-hardware.org/?probe=9d082a4d26) | Jul 24, 2020 |
| ASRock        | X370 Taichi                 | [e08f62cb80](https://linux-hardware.org/?probe=e08f62cb80) | Jul 23, 2020 |
| Unknown       | Unknown                     | [3ab679a1a1](https://linux-hardware.org/?probe=3ab679a1a1) | Jul 22, 2020 |
| ASUSTek       | X99-M WS                    | [7a813c93b0](https://linux-hardware.org/?probe=7a813c93b0) | Jul 15, 2020 |
| Unknown       | Unknown                     | [d83097e656](https://linux-hardware.org/?probe=d83097e656) | Jul 13, 2020 |
| ASRock        | Z170 Pro4S                  | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASUSTek       | GRYPHON Z97                 | [e7b3ad7e11](https://linux-hardware.org/?probe=e7b3ad7e11) | Jul 07, 2020 |
| ASRock        | Z170 Pro4S                  | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| ASUSTek       | PRIME X570-PRO              | [ce72513578](https://linux-hardware.org/?probe=ce72513578) | Jul 06, 2020 |
| ASUSTek       | M5A97 R2.0                  | [9e43a872bf](https://linux-hardware.org/?probe=9e43a872bf) | Jul 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | [cca87001ef](https://linux-hardware.org/?probe=cca87001ef) | Jul 03, 2020 |
| ASUSTek       | PRIME X570-PRO              | [dd3e957888](https://linux-hardware.org/?probe=dd3e957888) | Jul 03, 2020 |
| MSI           | B450M MORTAR MAX            | [856df3e013](https://linux-hardware.org/?probe=856df3e013) | Jul 01, 2020 |
| ASUSTek       | PRIME X570-P                | [d7dfd2a0d2](https://linux-hardware.org/?probe=d7dfd2a0d2) | Jun 30, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [f54a86a6b4](https://linux-hardware.org/?probe=f54a86a6b4) | Jun 30, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [c9529f922d](https://linux-hardware.org/?probe=c9529f922d) | Jun 29, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [911703286c](https://linux-hardware.org/?probe=911703286c) | Jun 29, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [9ff481d661](https://linux-hardware.org/?probe=9ff481d661) | Jun 29, 2020 |
| ASRockRack    | C226M WS                    | [adb729fe45](https://linux-hardware.org/?probe=adb729fe45) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [12ca04e727](https://linux-hardware.org/?probe=12ca04e727) | Jun 27, 2020 |
| ASUSTek       | M3A78-CM                    | [32ad3b2344](https://linux-hardware.org/?probe=32ad3b2344) | Jun 27, 2020 |
| Dell          | 0NK70N A03                  | [19fb02ca4e](https://linux-hardware.org/?probe=19fb02ca4e) | Jun 25, 2020 |
| ASUSTek       | PRIME X370-A                | [a2df61648b](https://linux-hardware.org/?probe=a2df61648b) | Jun 24, 2020 |
| ASUSTek       | PRIME X570-P                | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASUSTek       | PRIME X570-P                | [392a2f214f](https://linux-hardware.org/?probe=392a2f214f) | Jun 20, 2020 |
| ASRock        | X370 Killer SLI             | [e68e55ff91](https://linux-hardware.org/?probe=e68e55ff91) | Jun 20, 2020 |
| Gigabyte      | H310M S2H x.x               | [7ec1b97719](https://linux-hardware.org/?probe=7ec1b97719) | Jun 20, 2020 |
| Gigabyte      | H310M S2H x.x               | [26018540a4](https://linux-hardware.org/?probe=26018540a4) | Jun 18, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a91b7a6ef3](https://linux-hardware.org/?probe=a91b7a6ef3) | Jun 16, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [78a788e5aa](https://linux-hardware.org/?probe=78a788e5aa) | Jun 14, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [d1c9757c3c](https://linux-hardware.org/?probe=d1c9757c3c) | Jun 11, 2020 |
| MSI           | Z97-G43                     | [1134683267](https://linux-hardware.org/?probe=1134683267) | Jun 11, 2020 |
| MSI           | X570-A PRO                  | [d330af6317](https://linux-hardware.org/?probe=d330af6317) | Jun 09, 2020 |
| ASUSTek       | Z170-A                      | [81dbec3df4](https://linux-hardware.org/?probe=81dbec3df4) | Jun 09, 2020 |
| ASRock        | B450 Pro4                   | [d57c4c6597](https://linux-hardware.org/?probe=d57c4c6597) | Jun 09, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [40b9dbe4a5](https://linux-hardware.org/?probe=40b9dbe4a5) | Jun 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [50cf5c19df](https://linux-hardware.org/?probe=50cf5c19df) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | UN65U                       | [12d0edec81](https://linux-hardware.org/?probe=12d0edec81) | Jun 07, 2020 |
| ASUSTek       | WS X299 SAGE                | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [9c7b7cde1e](https://linux-hardware.org/?probe=9c7b7cde1e) | Jun 04, 2020 |
| ASRock        | B150M Pro4                  | [d704cdc9e0](https://linux-hardware.org/?probe=d704cdc9e0) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [e64653b77c](https://linux-hardware.org/?probe=e64653b77c) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | [ff470637f1](https://linux-hardware.org/?probe=ff470637f1) | Jun 04, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [cb3e54a9ea](https://linux-hardware.org/?probe=cb3e54a9ea) | Jun 04, 2020 |
| ASUSTek       | PRIME B450M-A               | [38d7220c47](https://linux-hardware.org/?probe=38d7220c47) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [b379b98120](https://linux-hardware.org/?probe=b379b98120) | Jun 04, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7ec054401d](https://linux-hardware.org/?probe=7ec054401d) | Jun 04, 2020 |
| Gigabyte      | X570 AORUS XTREME           | [cf5cf7d297](https://linux-hardware.org/?probe=cf5cf7d297) | Jun 04, 2020 |
| ASUSTek       | P6X58D-E                    | [219e253757](https://linux-hardware.org/?probe=219e253757) | Jun 04, 2020 |
| ASUSTek       | PRIME X370-PRO              | [725e4103b2](https://linux-hardware.org/?probe=725e4103b2) | Jun 04, 2020 |
| Gigabyte      | B450 AORUS M                | [8311b78871](https://linux-hardware.org/?probe=8311b78871) | Jun 04, 2020 |
| MSI           | X470 GAMING PLUS            | [713a47cd93](https://linux-hardware.org/?probe=713a47cd93) | Jun 04, 2020 |
| ASUSTek       | PRIME X370-PRO              | [66b855cb1f](https://linux-hardware.org/?probe=66b855cb1f) | Jun 04, 2020 |
| ASUSTek       | P8H67-M PRO                 | [3eeead93cd](https://linux-hardware.org/?probe=3eeead93cd) | Jun 03, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [19202ed9bc](https://linux-hardware.org/?probe=19202ed9bc) | Jun 03, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [781f2cda04](https://linux-hardware.org/?probe=781f2cda04) | Jun 03, 2020 |
| HP            | 3396                        | [59e4e46994](https://linux-hardware.org/?probe=59e4e46994) | Jun 03, 2020 |
| Acer          | Aspire X1800                | [f558e48348](https://linux-hardware.org/?probe=f558e48348) | Jun 03, 2020 |
| Intel         | DQ77MK AAG39642-302         | [dee8f8adaa](https://linux-hardware.org/?probe=dee8f8adaa) | Jun 03, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [03524be236](https://linux-hardware.org/?probe=03524be236) | Jun 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ed28ebb0ff](https://linux-hardware.org/?probe=ed28ebb0ff) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [4f2cd8d224](https://linux-hardware.org/?probe=4f2cd8d224) | Jun 03, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [452ae63632](https://linux-hardware.org/?probe=452ae63632) | Jun 03, 2020 |
| Intel         | DH77KC AAG39641-400         | [c70d57d5e5](https://linux-hardware.org/?probe=c70d57d5e5) | Jun 03, 2020 |
| ASRock        | X570 Creator                | [ae5e24adcc](https://linux-hardware.org/?probe=ae5e24adcc) | Jun 03, 2020 |
| ASRock        | X399 Taichi                 | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [656aaf0582](https://linux-hardware.org/?probe=656aaf0582) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [4b6b3bf141](https://linux-hardware.org/?probe=4b6b3bf141) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [e69d1396bf](https://linux-hardware.org/?probe=e69d1396bf) | Jun 03, 2020 |
| MSI           | X570-A PRO                  | [aeb2569425](https://linux-hardware.org/?probe=aeb2569425) | Jun 03, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Gentoo 2.7    | 271      | 37.48%  |
| Gentoo 2.6    | 181      | 25.03%  |
| Gentoo 2.8    | 117      | 16.18%  |
| Gentoo 2.9    | 70       | 9.68%   |
| Gentoo 2.13   | 58       | 8.02%   |
| Gentoo 2.4.1  | 9        | 1.24%   |
| Gentoo 2.3    | 5        | 0.69%   |
| Gentoo        | 4        | 0.55%   |
| Gentoo 2.2    | 3        | 0.41%   |
| Gentoo 22.0.1 | 2        | 0.28%   |
| Gentoo 1      | 2        | 0.28%   |
| Gentoo 13.0   | 1        | 0.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Gentoo | 639      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.38-gentoo            | 14       | 1.62%   |
| 6.1.12-gentoo            | 10       | 1.16%   |
| 5.7.0-gentoo             | 9        | 1.04%   |
| 5.4.97-gentoo            | 9        | 1.04%   |
| 5.4.28-gentoo            | 9        | 1.04%   |
| 5.15.80-gentoo           | 9        | 1.04%   |
| 5.15.32-gentoo-r1        | 8        | 0.93%   |
| 5.10.61-gentoo           | 8        | 0.93%   |
| 5.10.27-gentoo           | 8        | 0.93%   |
| 6.1.19-gentoo            | 7        | 0.81%   |
| 5.4.38-gentoo-x86_64     | 7        | 0.81%   |
| 5.15.88-gentoo           | 7        | 0.81%   |
| 5.10.27-gentoo-x86_64    | 7        | 0.81%   |
| 6.1.19-gentoo-x86_64     | 6        | 0.69%   |
| 6.1.12-gentoo-x86_64     | 6        | 0.69%   |
| 5.4.60-gentoo            | 6        | 0.69%   |
| 5.15.59-gentoo           | 6        | 0.69%   |
| 5.15.23-gentoo           | 6        | 0.69%   |
| 5.10.61-gentoo-x86_64    | 6        | 0.69%   |
| 5.6.15-gentoo            | 5        | 0.58%   |
| 5.6.11-gentoo            | 5        | 0.58%   |
| 5.4.80-gentoo-r1         | 5        | 0.58%   |
| 5.4.66-gentoo-x86_64     | 5        | 0.58%   |
| 5.4.66-gentoo            | 5        | 0.58%   |
| 5.4.48-gentoo            | 5        | 0.58%   |
| 5.15.80-gentoo-x86_64    | 5        | 0.58%   |
| 5.15.75-gentoo-x86_64    | 5        | 0.58%   |
| 5.15.52-gentoo-x86_64    | 5        | 0.58%   |
| 5.15.41-gentoo           | 5        | 0.58%   |
| 5.15.32-gentoo-r1-x86_64 | 5        | 0.58%   |
| 5.10.52-gentoo           | 5        | 0.58%   |
| 4.19.86-gentoo           | 5        | 0.58%   |
| 6.2.11-gentoo            | 4        | 0.46%   |
| 5.9.11-gentoo            | 4        | 0.46%   |
| 5.4.80-gentoo-r1-x86_64  | 4        | 0.46%   |
| 5.4.48-gentoo-x86_64     | 4        | 0.46%   |
| 5.17.1-gentoo-r1         | 4        | 0.46%   |
| 5.15.59-gentoo-x86_64    | 4        | 0.46%   |
| 5.15.52-gentoo           | 4        | 0.46%   |
| 5.15.41-gentoo-x86_64    | 4        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.38  | 28       | 3.24%   |
| 6.1.12  | 19       | 2.2%    |
| 5.15.32 | 19       | 2.2%    |
| 5.10.27 | 19       | 2.2%    |
| 5.10.61 | 16       | 1.85%   |
| 6.1.19  | 15       | 1.74%   |
| 5.15.80 | 15       | 1.74%   |
| 5.4.97  | 14       | 1.62%   |
| 5.4.28  | 14       | 1.62%   |
| 5.7.0   | 13       | 1.5%    |
| 5.15.75 | 13       | 1.5%    |
| 5.4.48  | 12       | 1.39%   |
| 5.15.52 | 12       | 1.39%   |
| 5.6.15  | 11       | 1.27%   |
| 5.4.66  | 11       | 1.27%   |
| 5.15.59 | 11       | 1.27%   |
| 5.15.41 | 11       | 1.27%   |
| 5.10.52 | 11       | 1.27%   |
| 5.10.76 | 10       | 1.16%   |
| 5.9.11  | 9        | 1.04%   |
| 5.4.80  | 9        | 1.04%   |
| 5.4.60  | 9        | 1.04%   |
| 5.17.1  | 8        | 0.93%   |
| 5.15.88 | 8        | 0.93%   |
| 5.15.11 | 8        | 0.93%   |
| 6.2.11  | 7        | 0.81%   |
| 5.15.23 | 7        | 0.81%   |
| 4.19.86 | 7        | 0.81%   |
| 5.9.8   | 6        | 0.69%   |
| 5.8.10  | 6        | 0.69%   |
| 5.6.11  | 6        | 0.69%   |
| 5.4.72  | 6        | 0.69%   |
| 5.15.74 | 6        | 0.69%   |
| 5.15.26 | 6        | 0.69%   |
| 5.11.6  | 6        | 0.69%   |
| 5.6.14  | 5        | 0.58%   |
| 5.6.13  | 5        | 0.58%   |
| 5.19.0  | 5        | 0.58%   |
| 5.15.69 | 5        | 0.58%   |
| 5.15.0  | 5        | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 131      | 16.42%  |
| 5.4     | 117      | 14.66%  |
| 5.10    | 95       | 11.9%   |
| 6.1     | 52       | 6.52%   |
| 5.6     | 38       | 4.76%   |
| 5.8     | 33       | 4.14%   |
| 5.9     | 29       | 3.63%   |
| 5.7     | 29       | 3.63%   |
| 4.19    | 26       | 3.26%   |
| 6.2     | 24       | 3.01%   |
| 5.14    | 23       | 2.88%   |
| 5.17    | 22       | 2.76%   |
| 5.19    | 20       | 2.51%   |
| 5.11    | 20       | 2.51%   |
| 5.13    | 19       | 2.38%   |
| 6.0     | 16       | 2.01%   |
| 5.18    | 16       | 2.01%   |
| 5.16    | 15       | 1.88%   |
| 5.12    | 13       | 1.63%   |
| 5.5     | 9        | 1.13%   |
| 4.14    | 9        | 1.13%   |
| 5.2     | 8        | 1%      |
| 5.0     | 6        | 0.75%   |
| 5.1     | 5        | 0.63%   |
| 4.9     | 5        | 0.63%   |
| 4.18    | 4        | 0.5%    |
| 4.4     | 3        | 0.38%   |
| 6.3     | 2        | 0.25%   |
| 5.3     | 2        | 0.25%   |
| 4.6     | 1        | 0.13%   |
| 4.20    | 1        | 0.13%   |
| 4.16    | 1        | 0.13%   |
| 4.13    | 1        | 0.13%   |
| 4.12    | 1        | 0.13%   |
| 4.10    | 1        | 0.13%   |
| 3.18    | 1        | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 621      | 97.18%  |
| i686     | 8        | 1.25%   |
| ppc      | 4        | 0.63%   |
| armv7l   | 2        | 0.31%   |
| armv5tel | 2        | 0.31%   |
| ppc64le  | 1        | 0.16%   |
| ppc64    | 1        | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 295      | 43.07%  |
| KDE5          | 147      | 21.46%  |
| GNOME         | 86       | 12.55%  |
| XFCE          | 63       | 9.2%    |
| KDE           | 31       | 4.53%   |
| MATE          | 18       | 2.63%   |
| X-Cinnamon    | 7        | 1.02%   |
| DWM           | 7        | 1.02%   |
| LXQt          | 6        | 0.88%   |
| i3            | 5        | 0.73%   |
| sway          | 4        | 0.58%   |
| Enlightenment | 3        | 0.44%   |
| Cinnamon      | 3        | 0.44%   |
| LXDE          | 2        | 0.29%   |
| awesome       | 2        | 0.29%   |
| XSession      | 1        | 0.15%   |
| Unity         | 1        | 0.15%   |
| sussy_bspwm   | 1        | 0.15%   |
| openbox       | 1        | 0.15%   |
| Hyprland      | 1        | 0.15%   |
| GNOME Classic | 1        | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 362      | 53%     |
| Unknown | 147      | 21.52%  |
| Tty     | 113      | 16.54%  |
| Wayland | 61       | 8.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 335      | 50.07%  |
| SDDM    | 164      | 24.51%  |
| LightDM | 72       | 10.76%  |
| GDM     | 59       | 8.82%   |
| SLiM    | 13       | 1.94%   |
| XDM     | 11       | 1.64%   |
| LXDM    | 10       | 1.49%   |
| GREETD  | 3        | 0.45%   |
| TDM     | 2        | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| en_US            | 242      | 36.23%  |
| Unknown          | 98       | 14.67%  |
| C.UTF8           | 51       | 7.63%   |
| en_GB            | 49       | 7.34%   |
| de_DE            | 46       | 6.89%   |
| ru_RU            | 30       | 4.49%   |
| C                | 20       | 2.99%   |
| es_ES            | 14       | 2.1%    |
| en_CA            | 13       | 1.95%   |
| fr_FR            | 12       | 1.8%    |
| pl_PL            | 10       | 1.5%    |
| it_IT            | 7        | 1.05%   |
| cs_CZ            | 6        | 0.9%    |
| ru_RU.UTF8       | 5        | 0.75%   |
| pt_BR            | 5        | 0.75%   |
| en_IE            | 5        | 0.75%   |
| sv_SE            | 4        | 0.6%    |
| fi_FI            | 4        | 0.6%    |
| en_AU            | 4        | 0.6%    |
| nl_NL            | 3        | 0.45%   |
| en_US.UTF8       | 3        | 0.45%   |
| ca_ES            | 3        | 0.45%   |
| zh_TW            | 2        | 0.3%    |
| ro_RO            | 2        | 0.3%    |
| pt_PT            | 2        | 0.3%    |
| nl_BE            | 2        | 0.3%    |
| ja_JP            | 2        | 0.3%    |
| en_DK            | 2        | 0.3%    |
| zh_CN            | 1        | 0.15%   |
| uk_UA            | 1        | 0.15%   |
| spanish          | 1        | 0.15%   |
| sl_SI            | 1        | 0.15%   |
| ru_UA            | 1        | 0.15%   |
| hu_HU            | 1        | 0.15%   |
| fr_FR.UTF8       | 1        | 0.15%   |
| fr_CA            | 1        | 0.15%   |
| et_EE            | 1        | 0.15%   |
| es_MX            | 1        | 0.15%   |
| es_ES.ISO-8859-1 | 1        | 0.15%   |
| es_AR            | 1        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 431      | 66.1%   |
| BIOS | 221      | 33.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 395      | 60.03%  |
| Btrfs    | 141      | 21.43%  |
| F2fs     | 28       | 4.26%   |
| Xfs      | 27       | 4.1%    |
| Zfs      | 26       | 3.95%   |
| Unknown  | 22       | 3.34%   |
| Reiserfs | 10       | 1.52%   |
| XXXXXXX  | 5        | 0.76%   |
| XXX      | 2        | 0.3%    |
| Jfs      | 1        | 0.15%   |
| Ext3     | 1        | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 528      | 81.11%  |
| MBR     | 79       | 12.14%  |
| Unknown | 44       | 6.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 406      | 59.79%  |
| Yes       | 273      | 40.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 416      | 63.51%  |
| Yes       | 239      | 36.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 244      | 38.18%  |
| MSI                 | 98       | 15.34%  |
| Gigabyte Technology | 92       | 14.4%   |
| ASRock              | 84       | 13.15%  |
| Hewlett-Packard     | 19       | 2.97%   |
| Unknown             | 19       | 2.97%   |
| Dell                | 14       | 2.19%   |
| Intel               | 11       | 1.72%   |
| Lenovo              | 7        | 1.1%    |
| Fujitsu             | 7        | 1.1%    |
| Acer                | 6        | 0.94%   |
| ASRockRack          | 5        | 0.78%   |
| Apple               | 4        | 0.63%   |
| Tekram Technology   | 3        | 0.47%   |
| Supermicro          | 3        | 0.47%   |
| Pegatron            | 3        | 0.47%   |
| Foxconn             | 3        | 0.47%   |
| Huanan              | 2        | 0.31%   |
| ZOTAC               | 1        | 0.16%   |
| YANYU               | 1        | 0.16%   |
| Sun Microsystems    | 1        | 0.16%   |
| Shuttle             | 1        | 0.16%   |
| QDI                 | 1        | 0.16%   |
| Phoenix             | 1        | 0.16%   |
| Packard Bell        | 1        | 0.16%   |
| NZXT                | 1        | 0.16%   |
| Medion              | 1        | 0.16%   |
| HPE                 | 1        | 0.16%   |
| Fujitsu Siemens     | 1        | 0.16%   |
| EVGA                | 1        | 0.16%   |
| Entroware           | 1        | 0.16%   |
| BESSTAR Tech        | 1        | 0.16%   |
| Alienware           | 1        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 21       | 3.29%   |
| Unknown                           | 19       | 2.97%   |
| ASUS TUF Gaming X570-PLUS         | 11       | 1.72%   |
| ASUS PRIME X570-PRO               | 8        | 1.25%   |
| ASUS PRIME X470-PRO               | 7        | 1.1%    |
| MSI MS-7C02                       | 6        | 0.94%   |
| MSI MS-7A38                       | 6        | 0.94%   |
| ASUS ROG STRIX X570-E GAMING      | 6        | 0.94%   |
| MSI MS-7C37                       | 5        | 0.78%   |
| MSI MS-7C35                       | 5        | 0.78%   |
| ASUS TUF Gaming B550-PLUS         | 5        | 0.78%   |
| ASUS ROG CROSSHAIR VIII HERO      | 5        | 0.78%   |
| ASUS PRIME X370-PRO               | 5        | 0.78%   |
| ASRock B450 Pro4                  | 5        | 0.78%   |
| MSI MS-7C91                       | 4        | 0.63%   |
| MSI MS-7B89                       | 4        | 0.63%   |
| MSI MS-7B86                       | 4        | 0.63%   |
| MSI MS-7B79                       | 4        | 0.63%   |
| ASUS Z170 PRO GAMING              | 4        | 0.63%   |
| ASUS ROG STRIX B550-F GAMING      | 4        | 0.63%   |
| ASUS ROG STRIX B450-F GAMING      | 4        | 0.63%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 4        | 0.63%   |
| ASUS ROG CROSSHAIR VII HERO       | 4        | 0.63%   |
| ASUS PRIME X570-P                 | 4        | 0.63%   |
| ASUS PRIME B450M-A                | 4        | 0.63%   |
| ASRock B550M Steel Legend         | 4        | 0.63%   |
| Tekram P6B40-A4X-i440BX Rev       | 3        | 0.47%   |
| MSI MS-7C34                       | 3        | 0.47%   |
| MSI MS-7693                       | 3        | 0.47%   |
| HP ProLiant MicroServer Gen8      | 3        | 0.47%   |
| Gigabyte X570 AORUS ELITE         | 3        | 0.47%   |
| Gigabyte B450M DS3H               | 3        | 0.47%   |
| Fujitsu D3401-H1                  | 3        | 0.47%   |
| Dell OptiPlex 790                 | 3        | 0.47%   |
| ASUS ROG STRIX X570-I GAMING      | 3        | 0.47%   |
| ASUS ROG STRIX X470-F GAMING      | 3        | 0.47%   |
| ASUS M4A89GTD-PRO/USB3            | 3        | 0.47%   |
| ASUS M3A78-CM                     | 3        | 0.47%   |
| ASRock Z390 Extreme4              | 3        | 0.47%   |
| ASRock X399 Taichi                | 3        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 63       | 9.86%   |
| ASUS PRIME              | 53       | 8.29%   |
| ASUS TUF                | 37       | 5.79%   |
| ASUS All                | 21       | 3.29%   |
| Unknown                 | 19       | 2.97%   |
| Gigabyte X570           | 11       | 1.72%   |
| ASRock X570             | 10       | 1.56%   |
| Gigabyte B450M          | 8        | 1.25%   |
| Gigabyte B450           | 8        | 1.25%   |
| Dell OptiPlex           | 8        | 1.25%   |
| ASRock X370             | 8        | 1.25%   |
| MSI MS-7C02             | 6        | 0.94%   |
| MSI MS-7A38             | 6        | 0.94%   |
| ASRock B450             | 6        | 0.94%   |
| Acer Aspire             | 6        | 0.94%   |
| MSI MS-7C37             | 5        | 0.78%   |
| MSI MS-7C35             | 5        | 0.78%   |
| HP ProLiant             | 5        | 0.78%   |
| HP Compaq               | 5        | 0.78%   |
| ASRock B550M            | 5        | 0.78%   |
| MSI MS-7C91             | 4        | 0.63%   |
| MSI MS-7B89             | 4        | 0.63%   |
| MSI MS-7B86             | 4        | 0.63%   |
| MSI MS-7B79             | 4        | 0.63%   |
| Gigabyte B550M          | 4        | 0.63%   |
| ASUS Z170               | 4        | 0.63%   |
| ASUS SABERTOOTH         | 4        | 0.63%   |
| ASUS M5A97              | 4        | 0.63%   |
| ASRock Z390             | 4        | 0.63%   |
| Tekram P6B40-A4X-i440BX | 3        | 0.47%   |
| MSI MS-7C34             | 3        | 0.47%   |
| MSI MS-7693             | 3        | 0.47%   |
| Lenovo ThinkStation     | 3        | 0.47%   |
| Lenovo ThinkCentre      | 3        | 0.47%   |
| Gigabyte AB350-Gaming   | 3        | 0.47%   |
| Fujitsu D3401-H1        | 3        | 0.47%   |
| Dell Precision          | 3        | 0.47%   |
| ASUS P8Z77-V            | 3        | 0.47%   |
| ASUS Maximus            | 3        | 0.47%   |
| ASUS M4A89GTD-PRO       | 3        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 104      | 16.28%  |
| 2018    | 95       | 14.87%  |
| 2020    | 76       | 11.89%  |
| 2017    | 49       | 7.67%   |
| 2021    | 42       | 6.57%   |
| 2015    | 34       | 5.32%   |
| 2013    | 33       | 5.16%   |
| 2012    | 33       | 5.16%   |
| 2016    | 27       | 4.23%   |
| 2010    | 24       | 3.76%   |
| 2009    | 23       | 3.6%    |
| 2011    | 22       | 3.44%   |
| 2022    | 20       | 3.13%   |
| 2014    | 17       | 2.66%   |
| 2008    | 15       | 2.35%   |
| Unknown | 10       | 1.56%   |
| 2007    | 5        | 0.78%   |
| 2000    | 3        | 0.47%   |
| 2005    | 2        | 0.31%   |
| 2004    | 2        | 0.31%   |
| 2003    | 2        | 0.31%   |
| 2023    | 1        | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 639      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 629      | 97.98%  |
| Enabled  | 13       | 2.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 639      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 220      | 33.33%  |
| 16.01-24.0      | 162      | 24.55%  |
| 64.01-256.0     | 108      | 16.36%  |
| 8.01-16.0       | 56       | 8.48%   |
| 24.01-32.0      | 31       | 4.7%    |
| 4.01-8.0        | 28       | 4.24%   |
| 3.01-4.0        | 28       | 4.24%   |
| 1.01-2.0        | 12       | 1.82%   |
| 0.51-1.0        | 8        | 1.21%   |
| 2.01-3.0        | 4        | 0.61%   |
| More than 256.0 | 2        | 0.3%    |
| 0.01-0.5        | 1        | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 164      | 21.38%  |
| 2.01-3.0    | 133      | 17.34%  |
| 1.01-2.0    | 119      | 15.51%  |
| 8.01-16.0   | 100      | 13.04%  |
| 3.01-4.0    | 81       | 10.56%  |
| 0.01-0.5    | 63       | 8.21%   |
| 0.51-1.0    | 49       | 6.39%   |
| 16.01-24.0  | 36       | 4.69%   |
| 32.01-64.0  | 10       | 1.3%    |
| 24.01-32.0  | 7        | 0.91%   |
| 64.01-256.0 | 3        | 0.39%   |
| 0           | 2        | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 178      | 25.87%  |
| 3      | 150      | 21.8%   |
| 1      | 126      | 18.31%  |
| 4      | 89       | 12.94%  |
| 5      | 63       | 9.16%   |
| 6      | 32       | 4.65%   |
| 7      | 24       | 3.49%   |
| 8      | 11       | 1.6%    |
| 9      | 4        | 0.58%   |
| 0      | 3        | 0.44%   |
| 13     | 2        | 0.29%   |
| 12     | 2        | 0.29%   |
| 18     | 1        | 0.15%   |
| 17     | 1        | 0.15%   |
| 11     | 1        | 0.15%   |
| 10     | 1        | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 462      | 70.43%  |
| Yes       | 194      | 29.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 629      | 98.44%  |
| No        | 10       | 1.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 392      | 60.59%  |
| Yes       | 255      | 39.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 388      | 59.88%  |
| Yes       | 260      | 40.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 145      | 22.52%  |
| Germany     | 101      | 15.68%  |
| Russia      | 59       | 9.16%   |
| UK          | 40       | 6.21%   |
| France      | 27       | 4.19%   |
| Spain       | 26       | 4.04%   |
| Canada      | 26       | 4.04%   |
| Poland      | 21       | 3.26%   |
| Finland     | 16       | 2.48%   |
| Sweden      | 14       | 2.17%   |
| Czechia     | 14       | 2.17%   |
| Italy       | 11       | 1.71%   |
| Australia   | 11       | 1.71%   |
| Ukraine     | 10       | 1.55%   |
| Brazil      | 9        | 1.4%    |
| Switzerland | 7        | 1.09%   |
| Netherlands | 7        | 1.09%   |
| China       | 7        | 1.09%   |
| Belgium     | 6        | 0.93%   |
| Romania     | 5        | 0.78%   |
| Norway      | 5        | 0.78%   |
| Mexico      | 5        | 0.78%   |
| Greece      | 5        | 0.78%   |
| Austria     | 5        | 0.78%   |
| Hungary     | 4        | 0.62%   |
| Estonia     | 4        | 0.62%   |
| Belarus     | 4        | 0.62%   |
| Vietnam     | 3        | 0.47%   |
| Slovenia    | 3        | 0.47%   |
| Slovakia    | 3        | 0.47%   |
| Japan       | 3        | 0.47%   |
| Hong Kong   | 3        | 0.47%   |
| Denmark     | 3        | 0.47%   |
| Bulgaria    | 3        | 0.47%   |
| Argentina   | 3        | 0.47%   |
| Tunisia     | 2        | 0.31%   |
| Taiwan      | 2        | 0.31%   |
| Jamaica     | 2        | 0.31%   |
| Ireland     | 2        | 0.31%   |
| India       | 2        | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Berlin               | 17       | 2.43%   |
| Moscow               | 16       | 2.29%   |
| St Petersburg        | 11       | 1.57%   |
| Warsaw               | 7        | 1%      |
| Vladivostok          | 6        | 0.86%   |
| Paris                | 6        | 0.86%   |
| Ottawa               | 6        | 0.86%   |
| Los Angeles          | 6        | 0.86%   |
| Helsinki             | 6        | 0.86%   |
| Frankfurt am Main    | 6        | 0.86%   |
| Wuelfrath            | 5        | 0.72%   |
| Vancouver            | 5        | 0.72%   |
| Sydney               | 5        | 0.72%   |
| Oulu                 | 5        | 0.72%   |
| Munich               | 5        | 0.72%   |
| Combrit              | 5        | 0.72%   |
| Athens               | 5        | 0.72%   |
| Zurich               | 4        | 0.57%   |
| Swansea              | 4        | 0.57%   |
| Sterling             | 4        | 0.57%   |
| Seattle              | 4        | 0.57%   |
| Ponetovice           | 4        | 0.57%   |
| Kyiv                 | 4        | 0.57%   |
| Freiburg im Breisgau | 4        | 0.57%   |
| Falkenstein          | 4        | 0.57%   |
| Dienheim             | 4        | 0.57%   |
| Cieszyn              | 4        | 0.57%   |
| Bucharest            | 4        | 0.57%   |
| Yekaterinburg        | 3        | 0.43%   |
| Woolwich             | 3        | 0.43%   |
| Vitkov               | 3        | 0.43%   |
| Tallinn              | 3        | 0.43%   |
| Sofia                | 3        | 0.43%   |
| Sao Paulo            | 3        | 0.43%   |
| San Antonio          | 3        | 0.43%   |
| Nuremberg            | 3        | 0.43%   |
| Monroe               | 3        | 0.43%   |
| Manitowoc            | 3        | 0.43%   |
| Leeds                | 3        | 0.43%   |
| Houston              | 3        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 293      | 660    | 21.28%  |
| WDC                       | 285      | 679    | 20.7%   |
| Seagate                   | 218      | 496    | 15.83%  |
| Kingston                  | 77       | 115    | 5.59%   |
| SanDisk                   | 60       | 90     | 4.36%   |
| Toshiba                   | 57       | 105    | 4.14%   |
| Crucial                   | 50       | 84     | 3.63%   |
| Intel                     | 47       | 68     | 3.41%   |
| Hitachi                   | 42       | 126    | 3.05%   |
| A-DATA Technology         | 27       | 35     | 1.96%   |
| HGST                      | 22       | 48     | 1.6%    |
| Phison                    | 17       | 27     | 1.23%   |
| Corsair                   | 16       | 30     | 1.16%   |
| Phison Electronics        | 14       | 19     | 1.02%   |
| OCZ                       | 12       | 14     | 0.87%   |
| GOODRAM                   | 8        | 39     | 0.58%   |
| Unknown                   | 6        | 8      | 0.44%   |
| PNY                       | 6        | 9      | 0.44%   |
| Patriot                   | 6        | 9      | 0.44%   |
| Micron/Crucial Technology | 6        | 8      | 0.44%   |
| China                     | 6        | 13     | 0.44%   |
| XPG                       | 5        | 11     | 0.36%   |
| Transcend                 | 5        | 7      | 0.36%   |
| Silicon Motion            | 5        | 12     | 0.36%   |
| Plextor                   | 5        | 6      | 0.36%   |
| IBM                       | 5        | 6      | 0.36%   |
| SPCC                      | 4        | 4      | 0.29%   |
| SK hynix                  | 4        | 6      | 0.29%   |
| Mushkin                   | 4        | 4      | 0.29%   |
| Micron Technology         | 4        | 6      | 0.29%   |
| Apacer                    | 4        | 6      | 0.29%   |
| Realtek Semiconductor     | 3        | 7      | 0.22%   |
| LITEONIT                  | 3        | 3      | 0.22%   |
| Gigabyte Technology       | 3        | 4      | 0.22%   |
| ADATA Technology          | 3        | 3      | 0.22%   |
| TO Exter                  | 2        | 2      | 0.15%   |
| Team                      | 2        | 8      | 0.15%   |
| T-FORCE                   | 2        | 7      | 0.15%   |
| MDT                       | 2        | 2      | 0.15%   |
| LaCie                     | 2        | 12     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 23       | 1.29%   |
| Samsung SSD 860 EVO 1TB                            | 22       | 1.24%   |
| Samsung SSD 850 EVO 250GB                          | 21       | 1.18%   |
| Samsung SSD 850 EVO 500GB                          | 20       | 1.12%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 18       | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 18       | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB                     | 16       | 0.9%    |
| Samsung SSD 860 EVO 250GB                          | 15       | 0.84%   |
| Samsung SSD 860 EVO 500GB                          | 14       | 0.79%   |
| Kingston SA400S37240G 240GB SSD                    | 14       | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 13       | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB                     | 13       | 0.73%   |
| Samsung SSD 970 EVO 500GB                          | 13       | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB                     | 12       | 0.67%   |
| Seagate ST2000DM001-1ER164 2TB                     | 12       | 0.67%   |
| WDC WD40EZRZ-00GXCB0 4TB                           | 11       | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB                     | 11       | 0.62%   |
| Samsung SSD 980 PRO 1TB                            | 11       | 0.62%   |
| Samsung SSD 970 EVO Plus 1TB                       | 11       | 0.62%   |
| Seagate ST500DM002-1BD142 500GB                    | 10       | 0.56%   |
| Seagate ST3500418AS 500GB                          | 10       | 0.56%   |
| Samsung SSD 970 EVO 250GB                          | 10       | 0.56%   |
| Samsung SSD 970 EVO 1TB                            | 10       | 0.56%   |
| Samsung SSD 840 EVO 120GB                          | 10       | 0.56%   |
| Crucial CT1000MX500SSD1 1TB                        | 10       | 0.56%   |
| WDC WD40EFRX-68WT0N0 4TB                           | 9        | 0.51%   |
| Samsung SSD 980 1TB                                | 9        | 0.51%   |
| Samsung SSD 840 EVO 250GB                          | 9        | 0.51%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 8        | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB                           | 8        | 0.45%   |
| WDC WD20EFRX-68EUZN0 2TB                           | 8        | 0.45%   |
| Toshiba DT01ACA100 1TB                             | 8        | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB                     | 8        | 0.45%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 7        | 0.39%   |
| WDC WD20EARX-00PASB0 2TB                           | 7        | 0.39%   |
| Seagate ST4000DM000-1F2168 4TB                     | 7        | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB                     | 7        | 0.39%   |
| Samsung SSD 970 PRO 512GB                          | 7        | 0.39%   |
| Samsung SSD 960 EVO 500GB                          | 7        | 0.39%   |
| Samsung SSD 850 EVO 1TB                            | 7        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 254      | 608    | 40.71%  |
| Seagate             | 213      | 488    | 34.13%  |
| Toshiba             | 51       | 96     | 8.17%   |
| Hitachi             | 42       | 126    | 6.73%   |
| Samsung Electronics | 23       | 33     | 3.69%   |
| HGST                | 22       | 48     | 3.53%   |
| IBM                 | 5        | 6      | 0.8%    |
| Unknown             | 3        | 4      | 0.48%   |
| MDT                 | 2        | 2      | 0.32%   |
| LaCie               | 2        | 12     | 0.32%   |
| Maxtor              | 1        | 1      | 0.16%   |
| Hewlett-Packard     | 1        | 2      | 0.16%   |
| Fujitsu             | 1        | 2      | 0.16%   |
| FNK TECH            | 1        | 1      | 0.16%   |
| Dyconn H            | 1        | 1      | 0.16%   |
| ASMedia             | 1        | 1      | 0.16%   |
| AFAYA               | 1        | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 172      | 323    | 35.46%  |
| Kingston            | 62       | 90     | 12.78%  |
| Crucial             | 46       | 73     | 9.48%   |
| SanDisk             | 44       | 70     | 9.07%   |
| WDC                 | 30       | 35     | 6.19%   |
| Intel               | 20       | 27     | 4.12%   |
| A-DATA Technology   | 13       | 15     | 2.68%   |
| OCZ                 | 11       | 13     | 2.27%   |
| Corsair             | 10       | 16     | 2.06%   |
| GOODRAM             | 8        | 39     | 1.65%   |
| China               | 6        | 13     | 1.24%   |
| PNY                 | 5        | 8      | 1.03%   |
| Transcend           | 4        | 6      | 0.82%   |
| Plextor             | 4        | 4      | 0.82%   |
| Patriot             | 4        | 7      | 0.82%   |
| Toshiba             | 3        | 4      | 0.62%   |
| SPCC                | 3        | 3      | 0.62%   |
| Mushkin             | 3        | 3      | 0.62%   |
| Micron Technology   | 3        | 4      | 0.62%   |
| LITEONIT            | 3        | 3      | 0.62%   |
| Apacer              | 3        | 5      | 0.62%   |
| TO Exter            | 2        | 2      | 0.41%   |
| T-FORCE             | 2        | 7      | 0.41%   |
| KingSpec            | 2        | 3      | 0.41%   |
| Intenso             | 2        | 3      | 0.41%   |
| V-GeN               | 1        | 1      | 0.21%   |
| Unknown             | 1        | 1      | 0.21%   |
| Team                | 1        | 2      | 0.21%   |
| Smartbuy            | 1        | 1      | 0.21%   |
| OWC                 | 1        | 1      | 0.21%   |
| OCZ-VERTEX          | 1        | 1      | 0.21%   |
| LITEON              | 1        | 1      | 0.21%   |
| Linux               | 1        | 1      | 0.21%   |
| Leven               | 1        | 2      | 0.21%   |
| KingDian            | 1        | 1      | 0.21%   |
| Kingchuxing         | 1        | 2      | 0.21%   |
| Hewlett-Packard     | 1        | 1      | 0.21%   |
| EMTEC               | 1        | 3      | 0.21%   |
| Dogfish             | 1        | 1      | 0.21%   |
| CT2000MX            | 1        | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 455      | 1432   | 39.22%  |
| SSD     | 379      | 803    | 32.67%  |
| NVMe    | 321      | 610    | 27.67%  |
| Unknown | 4        | 4      | 0.34%   |
| MMC     | 1        | 2      | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 565      | 2190   | 61.88%  |
| NVMe | 321      | 610    | 35.16%  |
| SAS  | 26       | 49     | 2.85%   |
| MMC  | 1        | 2      | 0.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 377      | 802    | 37.48%  |
| 0.51-1.0   | 273      | 502    | 27.14%  |
| 1.01-2.0   | 149      | 312    | 14.81%  |
| 3.01-4.0   | 90       | 206    | 8.95%   |
| 4.01-10.0  | 51       | 209    | 5.07%   |
| 2.01-3.0   | 50       | 160    | 4.97%   |
| 10.01-20.0 | 15       | 43     | 1.49%   |
| 20.01-50.0 | 1        | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 142      | 20.34%  |
| 501-1000       | 111      | 15.9%   |
| 1001-2000      | 105      | 15.04%  |
| 251-500        | 91       | 13.04%  |
| 101-250        | 89       | 12.75%  |
| 2001-3000      | 62       | 8.88%   |
| Unknown        | 34       | 4.87%   |
| 1-20           | 28       | 4.01%   |
| 51-100         | 26       | 3.72%   |
| 21-50          | 10       | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 113      | 15.65%  |
| 101-250        | 96       | 13.3%   |
| 251-500        | 90       | 12.47%  |
| 501-1000       | 85       | 11.77%  |
| 1001-2000      | 80       | 11.08%  |
| More than 3000 | 73       | 10.11%  |
| 21-50          | 68       | 9.42%   |
| 51-100         | 51       | 7.06%   |
| Unknown        | 34       | 4.71%   |
| 2001-3000      | 32       | 4.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                    | 6        | 7      | 3.13%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 4        | 14     | 2.08%   |
| Seagate ST500DM002-1BD142 500GB              | 4        | 4      | 2.08%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 3        | 4      | 1.56%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 3        | 6      | 1.56%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3        | 15     | 1.56%   |
| Seagate ST500DM002-1BC142 500GB              | 3        | 3      | 1.56%   |
| Samsung Electronics SSD 980 1TB              | 3        | 3      | 1.56%   |
| IBM DJSA-220 12GB                            | 3        | 3      | 1.56%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 2        | 5      | 1.04%   |
| WDC WD40EFRX-68N32N0 4TB                     | 2        | 2      | 1.04%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 2        | 3      | 1.04%   |
| WDC WD20EARS-00MVWB0 2TB                     | 2        | 2      | 1.04%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 2        | 2      | 1.04%   |
| WDC WD15EARS-00Z5B1 1TB                      | 2        | 2      | 1.04%   |
| Seagate ST4000DM000-1F2168 4TB               | 2        | 2      | 1.04%   |
| Seagate ST31000340NS 1TB                     | 2        | 3      | 1.04%   |
| Seagate ST3000DM001-9YN166 3TB               | 2        | 3      | 1.04%   |
| Seagate ST2000DX002-2DV164 2TB               | 2        | 2      | 1.04%   |
| Seagate ST2000DL003-9VT166 2TB               | 2        | 3      | 1.04%   |
| Seagate ST1000NM0011 1TB                     | 2        | 6      | 1.04%   |
| SanDisk SSD PLUS 1000GB                      | 2        | 2      | 1.04%   |
| Samsung Electronics SSD 870 EVO 500GB        | 2        | 3      | 1.04%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2        | 4      | 1.04%   |
| Samsung Electronics HD103UJ 1TB              | 2        | 2      | 1.04%   |
| MDT MD2000KS-00MJB0 200GB                    | 2        | 2      | 1.04%   |
| Hitachi HDS722020ALA330 2TB                  | 2        | 16     | 1.04%   |
| Crucial CT525MX300SSD1 528GB                 | 2        | 2      | 1.04%   |
| WDC WD80EFZX-68UW8N0 8TB                     | 1        | 2      | 0.52%   |
| WDC WD7501AALS-00J7B0 752GB                  | 1        | 1      | 0.52%   |
| WDC WD6400AAKS-65A7B2 640GB                  | 1        | 1      | 0.52%   |
| WDC WD6400AAKS-65A7B0 640GB                  | 1        | 1      | 0.52%   |
| WDC WD60PURZ-85ZUFY1 6TB                     | 1        | 1      | 0.52%   |
| WDC WD60EZRX-00MVLB1 6TB                     | 1        | 1      | 0.52%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 18     | 0.52%   |
| WDC WD60EFAX-68SHWN0 6TB                     | 1        | 3      | 0.52%   |
| WDC WD5000BEVT-22ZAT0 500GB                  | 1        | 1      | 0.52%   |
| WDC WD5000AZRX-00A8LB0 500GB                 | 1        | 1      | 0.52%   |
| WDC WD5000AAVS-22G9B1 500GB                  | 1        | 1      | 0.52%   |
| WDC WD5000AAKX-753CA1 500GB                  | 1        | 1      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 51       | 96     | 28.33%  |
| Seagate               | 48       | 78     | 26.67%  |
| Samsung Electronics   | 24       | 37     | 13.33%  |
| Hitachi               | 10       | 24     | 5.56%   |
| Toshiba               | 8        | 9      | 4.44%   |
| Crucial               | 6        | 6      | 3.33%   |
| SanDisk               | 5        | 6      | 2.78%   |
| IBM                   | 4        | 4      | 2.22%   |
| Kingston              | 3        | 3      | 1.67%   |
| Realtek Semiconductor | 2        | 5      | 1.11%   |
| Plextor               | 2        | 2      | 1.11%   |
| OCZ                   | 2        | 2      | 1.11%   |
| MDT                   | 2        | 2      | 1.11%   |
| Intel                 | 2        | 3      | 1.11%   |
| HGST                  | 2        | 3      | 1.11%   |
| Corsair               | 2        | 5      | 1.11%   |
| China                 | 2        | 2      | 1.11%   |
| Transcend             | 1        | 1      | 0.56%   |
| PNY                   | 1        | 1      | 0.56%   |
| Mushkin               | 1        | 1      | 0.56%   |
| Maxtor                | 1        | 1      | 0.56%   |
| EMTEC                 | 1        | 2      | 0.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 51       | 96     | 39.23%  |
| Seagate             | 48       | 78     | 36.92%  |
| Hitachi             | 10       | 24     | 7.69%   |
| Toshiba             | 8        | 9      | 6.15%   |
| Samsung Electronics | 4        | 5      | 3.08%   |
| IBM                 | 4        | 4      | 3.08%   |
| MDT                 | 2        | 2      | 1.54%   |
| HGST                | 2        | 3      | 1.54%   |
| Maxtor              | 1        | 1      | 0.77%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 120      | 222    | 70.59%  |
| SSD  | 35       | 48     | 20.59%  |
| NVMe | 15       | 23     | 8.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                     | 1        | 1      | 16.67%  |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 2      | 16.67%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1        | 1      | 16.67%  |
| Seagate ST3500630AS 500GB                        | 1        | 2      | 16.67%  |
| Seagate ST31500341AS 1TB                         | 1        | 1      | 16.67%  |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1        | 2      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 3      | 33.33%  |
| Seagate             | 2        | 3      | 33.33%  |
| Toshiba             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 2      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 577      | 2342   | 70.19%  |
| Malfunc  | 160      | 293    | 19.46%  |
| Detected | 79       | 207    | 9.61%   |
| Failed   | 6        | 9      | 0.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 315      | 28.4%   |
| Intel                            | 298      | 26.87%  |
| Samsung Electronics              | 169      | 15.24%  |
| ASMedia Technology               | 65       | 5.86%   |
| Phison Electronics               | 41       | 3.7%    |
| SanDisk                          | 40       | 3.61%   |
| Marvell Technology Group         | 31       | 2.8%    |
| ADATA Technology                 | 19       | 1.71%   |
| Nvidia                           | 18       | 1.62%   |
| Kingston Technology Company      | 17       | 1.53%   |
| JMicron Technology               | 15       | 1.35%   |
| Micron/Crucial Technology        | 11       | 0.99%   |
| Silicon Motion                   | 9        | 0.81%   |
| Broadcom / LSI                   | 8        | 0.72%   |
| Toshiba America Info Systems     | 6        | 0.54%   |
| Realtek Semiconductor            | 6        | 0.54%   |
| LSI Logic / Symbios Logic        | 6        | 0.54%   |
| Adaptec                          | 6        | 0.54%   |
| Silicon Image                    | 5        | 0.45%   |
| Seagate Technology               | 5        | 0.45%   |
| SK hynix                         | 4        | 0.36%   |
| KIOXIA                           | 2        | 0.18%   |
| INNOGRIT                         | 2        | 0.18%   |
| 3ware                            | 2        | 0.18%   |
| VIA Technologies                 | 1        | 0.09%   |
| Solid State Storage Technology   | 1        | 0.09%   |
| Silicon Integrated Systems [SiS] | 1        | 0.09%   |
| OCZ Technology Group             | 1        | 0.09%   |
| Micron Technology                | 1        | 0.09%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.09%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.09%   |
| Integrated Technology Express    | 1        | 0.09%   |
| Broadcom                         | 1        | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 229      | 17.08%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 106      | 7.9%    |
| AMD 400 Series Chipset SATA Controller                                         | 92       | 6.86%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 59       | 4.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 43       | 3.21%   |
| AMD 500 Series Chipset SATA Controller                                         | 37       | 2.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 34       | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 32       | 2.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 25       | 1.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 21       | 1.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21       | 1.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21       | 1.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19       | 1.42%   |
| AMD X370 Series Chipset SATA Controller                                        | 19       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 18       | 1.34%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 17       | 1.27%   |
| Phison E16 PCIe4 NVMe Controller                                               | 16       | 1.19%   |
| Phison E12 NVMe Controller                                                     | 16       | 1.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 16       | 1.19%   |
| Samsung NVMe SSD Controller 980                                                | 14       | 1.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 14       | 1.04%   |
| Intel SATA Controller [RAID mode]                                              | 13       | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 13       | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13       | 0.97%   |
| AMD 300 Series Chipset SATA Controller                                         | 13       | 0.97%   |
| Intel SSD 660P Series                                                          | 12       | 0.89%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 12       | 0.89%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 11       | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10       | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                | 10       | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9        | 0.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 9        | 0.67%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 8        | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                             | 8        | 0.6%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 8        | 0.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8        | 0.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7        | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 7        | 0.52%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 7        | 0.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 580      | 56.26%  |
| NVMe | 322      | 31.23%  |
| IDE  | 72       | 6.98%   |
| RAID | 39       | 3.78%   |
| SAS  | 11       | 1.07%   |
| SCSI | 7        | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 334      | 52.27%  |
| Intel                    | 295      | 46.17%  |
| Marvell Semiconductor    | 3        | 0.47%   |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.16%   |
| PowerMac8,1              | 1        | 0.16%   |
| PowerMac3,6              | 1        | 0.16%   |
| PowerMac10,2             | 1        | 0.16%   |
| PowerBook6,7             | 1        | 0.16%   |
| PowerBook5,5             | 1        | 0.16%   |
| ARM                      | 1        | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 28       | 4.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 20       | 3.07%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 18       | 2.76%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 16       | 2.46%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 16       | 2.46%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 16       | 2.46%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 15       | 2.3%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 14       | 2.15%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 13       | 2%      |
| AMD Ryzen 5 2600 Six-Core Processor         | 12       | 1.84%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 11       | 1.69%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 10       | 1.54%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 10       | 1.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 9        | 1.38%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 9        | 1.38%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 1.23%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 7        | 1.08%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 7        | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 0.92%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 6        | 0.92%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 6        | 0.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.77%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.77%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5        | 0.77%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 5        | 0.77%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 5        | 0.77%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 0.77%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 4        | 0.61%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 4        | 0.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 4        | 0.61%   |
| Intel 12th Gen Core i9-12900K               | 4        | 0.61%   |
| Intel 12th Gen Core i7-12700K               | 4        | 0.61%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.61%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.61%   |
| Intel Pentium III (Katmai)                  | 3        | 0.46%   |
| Intel Pentium 4 CPU 3.20GHz                 | 3        | 0.46%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.46%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 0.46%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 3        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 100      | 15.46%  |
| AMD Ryzen 7             | 100      | 15.46%  |
| AMD Ryzen 5             | 84       | 12.98%  |
| AMD Ryzen 9             | 73       | 11.28%  |
| Intel Core i5           | 60       | 9.27%   |
| Intel Xeon              | 38       | 5.87%   |
| Other                   | 34       | 5.26%   |
| AMD FX                  | 21       | 3.25%   |
| Intel Core i9           | 12       | 1.85%   |
| Intel Atom              | 10       | 1.55%   |
| Intel Pentium           | 9        | 1.39%   |
| Intel Core 2 Quad       | 9        | 1.39%   |
| AMD Ryzen Threadripper  | 9        | 1.39%   |
| AMD Phenom II X4        | 9        | 1.39%   |
| Intel Core i3           | 8        | 1.24%   |
| Intel Celeron           | 8        | 1.24%   |
| AMD Ryzen 3             | 8        | 1.24%   |
| Intel Core 2 Duo        | 7        | 1.08%   |
| Intel Pentium 4         | 6        | 0.93%   |
| AMD Phenom II X6        | 6        | 0.93%   |
| AMD Ryzen 7 PRO         | 5        | 0.77%   |
| AMD Sempron             | 4        | 0.62%   |
| Intel Pentium III       | 3        | 0.46%   |
| AMD Athlon II X3        | 3        | 0.46%   |
| AMD Athlon 64 X2        | 3        | 0.46%   |
| AMD Athlon              | 3        | 0.46%   |
| AMD A10                 | 3        | 0.46%   |
| Intel Core 2            | 2        | 0.31%   |
| AMD Ryzen 5 PRO         | 2        | 0.31%   |
| AMD E                   | 2        | 0.31%   |
| Intel Pentium Dual-Core | 1        | 0.15%   |
| ARM Allwinner           | 1        | 0.15%   |
| AMD Turion II Neo       | 1        | 0.15%   |
| AMD Phenom              | 1        | 0.15%   |
| AMD Athlon X4           | 1        | 0.15%   |
| AMD A6                  | 1        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 175      | 27.09%  |
| 8       | 139      | 21.52%  |
| 6       | 139      | 21.52%  |
| 2       | 51       | 7.89%   |
| 12      | 50       | 7.74%   |
| 16      | 46       | 7.12%   |
| 1       | 20       | 3.1%    |
| 3       | 7        | 1.08%   |
| 10      | 6        | 0.93%   |
| Unknown | 3        | 0.46%   |
| 28      | 2        | 0.31%   |
| 24      | 2        | 0.31%   |
| 64      | 1        | 0.15%   |
| 44      | 1        | 0.15%   |
| 32      | 1        | 0.15%   |
| 22      | 1        | 0.15%   |
| 18      | 1        | 0.15%   |
| 14      | 1        | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 625      | 97.81%  |
| 2       | 12       | 1.88%   |
| Unknown | 2        | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 482      | 74.84%  |
| 1       | 158      | 24.53%  |
| Unknown | 3        | 0.47%   |
| 4       | 1        | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 623      | 97.5%   |
| 32-bit         | 10       | 1.56%   |
| Unknown        | 6        | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 107      | 15.88%  |
| 0x08701021 | 60       | 8.9%    |
| 0x0800820d | 39       | 5.79%   |
| 0x08701013 | 34       | 5.04%   |
| 0x506e3    | 31       | 4.6%    |
| 0x0a201016 | 27       | 4.01%   |
| 0x306c3    | 26       | 3.86%   |
| 0x306a9    | 23       | 3.41%   |
| 0x0a201009 | 20       | 2.97%   |
| 0x08001138 | 20       | 2.97%   |
| 0x906e9    | 17       | 2.52%   |
| 0x906ea    | 16       | 2.37%   |
| 0x0a601203 | 12       | 1.78%   |
| 0x1067a    | 11       | 1.63%   |
| 0xa0655    | 10       | 1.48%   |
| 0x906ed    | 10       | 1.48%   |
| 0xa0671    | 9        | 1.34%   |
| 0x90672    | 9        | 1.34%   |
| 0x306f2    | 9        | 1.34%   |
| 0x0a20120a | 9        | 1.34%   |
| 0x206c2    | 8        | 1.19%   |
| 0x206a7    | 8        | 1.19%   |
| 0x906ec    | 6        | 0.89%   |
| 0x406f1    | 6        | 0.89%   |
| 0x306e4    | 6        | 0.89%   |
| 0x06000822 | 5        | 0.74%   |
| 0x00000000 | 5        | 0.74%   |
| 0xa0653    | 4        | 0.59%   |
| 0x50654    | 4        | 0.59%   |
| 0x106a5    | 4        | 0.59%   |
| 0x0a50000c | 4        | 0.59%   |
| 0x0a201204 | 4        | 0.59%   |
| 0x08600106 | 4        | 0.59%   |
| 0x08301039 | 4        | 0.59%   |
| 0x0810100b | 4        | 0.59%   |
| 0x0800820b | 4        | 0.59%   |
| 0x06000852 | 4        | 0.59%   |
| 0x010000c8 | 4        | 0.59%   |
| 0x010000bf | 4        | 0.59%   |
| 0x673      | 3        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 111      | 17.13%  |
| Zen 3            | 72       | 11.11%  |
| KabyLake         | 57       | 8.8%    |
| Zen+             | 53       | 8.18%   |
| Haswell          | 41       | 6.33%   |
| Skylake          | 35       | 5.4%    |
| Zen              | 34       | 5.25%   |
| IvyBridge        | 32       | 4.94%   |
| Unknown          | 32       | 4.94%   |
| Piledriver       | 19       | 2.93%   |
| K10              | 19       | 2.93%   |
| CometLake        | 17       | 2.62%   |
| SandyBridge      | 16       | 2.47%   |
| Penryn           | 13       | 2.01%   |
| Alderlake Hybrid | 12       | 1.85%   |
| Westmere         | 10       | 1.54%   |
| Nehalem          | 9        | 1.39%   |
| Broadwell        | 8        | 1.23%   |
| Bonnell          | 8        | 1.23%   |
| Icelake          | 7        | 1.08%   |
| Core             | 7        | 1.08%   |
| Silvermont       | 6        | 0.93%   |
| NetBurst         | 6        | 0.93%   |
| K8 Hammer        | 5        | 0.77%   |
| Bulldozer        | 5        | 0.77%   |
| P6               | 3        | 0.46%   |
| Jaguar           | 3        | 0.46%   |
| Goldmont         | 2        | 0.31%   |
| Bobcat           | 2        | 0.31%   |
| TigerLake        | 1        | 0.15%   |
| Steamroller      | 1        | 0.15%   |
| Goldmont plus    | 1        | 0.15%   |
| Excavator        | 1        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 284      | 41.52%  |
| Nvidia                           | 282      | 41.23%  |
| Intel                            | 99       | 14.47%  |
| ASPEED Technology                | 12       | 1.75%   |
| Matrox Electronics Systems       | 6        | 0.88%   |
| Silicon Integrated Systems [SiS] | 1        | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 78       | 10.88%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 30       | 4.18%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 19       | 2.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15       | 2.09%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13       | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 1.81%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 13       | 1.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12       | 1.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 12       | 1.67%   |
| Intel HD Graphics 530                                                       | 12       | 1.67%   |
| ASPEED Technology ASPEED Graphics Family                                    | 12       | 1.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 1.53%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 11       | 1.53%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 1.39%   |
| AMD Raphael                                                                 | 10       | 1.39%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 9        | 1.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 1.26%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 9        | 1.26%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 9        | 1.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 1.12%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 8        | 1.12%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 7        | 0.98%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 0.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 0.98%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7        | 0.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 0.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 0.84%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 0.84%   |
| Nvidia GF119 [GeForce GT 610]                                               | 6        | 0.84%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 6        | 0.84%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 0.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 0.7%    |
| AMD Renoir                                                                  | 5        | 0.7%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x AMD                  | 252      | 38.65%  |
| 1 x Nvidia               | 249      | 38.19%  |
| 1 x Intel                | 76       | 11.66%  |
| AMD + Nvidia             | 16       | 2.45%   |
| 1 x ASPEED               | 11       | 1.69%   |
| 2 x AMD                  | 10       | 1.53%   |
| Other                    | 8        | 1.23%   |
| Intel + Nvidia           | 8        | 1.23%   |
| 2 x Nvidia               | 6        | 0.92%   |
| Intel + AMD              | 5        | 0.77%   |
| 1 x Matrox               | 4        | 0.61%   |
| 2 x Intel                | 1        | 0.15%   |
| 1 x SiS                  | 1        | 0.15%   |
| Nvidia + Matrox          | 1        | 0.15%   |
| Intel + 2 x Nvidia       | 1        | 0.15%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.15%   |
| AMD + Matrox             | 1        | 0.15%   |
| AMD + ASPEED             | 1        | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 403      | 61.25%  |
| Proprietary | 195      | 29.64%  |
| Unknown     | 60       | 9.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 201      | 29.73%  |
| 7.01-8.0   | 149      | 22.04%  |
| 1.01-2.0   | 64       | 9.47%   |
| 3.01-4.0   | 62       | 9.17%   |
| 8.01-16.0  | 56       | 8.28%   |
| 0.01-0.5   | 45       | 6.66%   |
| 0.51-1.0   | 44       | 6.51%   |
| 5.01-6.0   | 36       | 5.33%   |
| 2.01-3.0   | 11       | 1.63%   |
| 16.01-24.0 | 6        | 0.89%   |
| 4.01-5.0   | 2        | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 98       | 13.48%  |
| Dell                    | 89       | 12.24%  |
| Goldstar                | 62       | 8.53%   |
| AOC                     | 48       | 6.6%    |
| BenQ                    | 45       | 6.19%   |
| Ancor Communications    | 45       | 6.19%   |
| Hewlett-Packard         | 39       | 5.36%   |
| Acer                    | 38       | 5.23%   |
| ViewSonic               | 26       | 3.58%   |
| Iiyama                  | 26       | 3.58%   |
| ASUSTek Computer        | 25       | 3.44%   |
| Philips                 | 23       | 3.16%   |
| Lenovo                  | 18       | 2.48%   |
| LG Electronics          | 12       | 1.65%   |
| Eizo                    | 11       | 1.51%   |
| Unknown                 | 8        | 1.1%    |
| Fujitsu Siemens         | 7        | 0.96%   |
| MSI                     | 6        | 0.83%   |
| Idek Iiyama             | 6        | 0.83%   |
| Gigabyte Technology     | 6        | 0.83%   |
| Apple                   | 6        | 0.83%   |
| NEC Computers           | 5        | 0.69%   |
| Unknown                 | 4        | 0.55%   |
| Sony                    | 3        | 0.41%   |
| Panasonic               | 3        | 0.41%   |
| HVR                     | 3        | 0.41%   |
| HannStar                | 3        | 0.41%   |
| Envision Peripherals    | 3        | 0.41%   |
| AUS                     | 3        | 0.41%   |
| Yamaha                  | 2        | 0.28%   |
| Toshiba                 | 2        | 0.28%   |
| Sceptre Tech            | 2        | 0.28%   |
| PNP                     | 2        | 0.28%   |
| Onkyo                   | 2        | 0.28%   |
| KTC                     | 2        | 0.28%   |
| HJW                     | 2        | 0.28%   |
| Hitachi                 | 2        | 0.28%   |
| Gateway                 | 2        | 0.28%   |
| Chimei Innolux          | 2        | 0.28%   |
| Chi Mei Optoelectronics | 2        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 7        | 0.87%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 6        | 0.75%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                   | 6        | 0.75%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                   | 5        | 0.62%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 5        | 0.62%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch        | 4        | 0.5%    |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                       | 4        | 0.5%    |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                      | 4        | 0.5%    |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                        | 4        | 0.5%    |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch        | 4        | 0.5%    |
| Unknown                                                                 | 4        | 0.5%    |
| Samsung Electronics LCD Monitor SAM7003 3840x2160 1872x1053mm 84.6-inch | 3        | 0.37%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 3        | 0.37%   |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 598x336mm 27.0-inch       | 3        | 0.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3        | 0.37%   |
| LG Electronics LCD Monitor LG HDR 4K 7680x2160                          | 3        | 0.37%   |
| LG Electronics LCD Monitor LG HDR 4K                                    | 3        | 0.37%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 3        | 0.37%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch            | 3        | 0.37%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch                | 3        | 0.37%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 677x290mm 29.0-inch                | 3        | 0.37%   |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch      | 3        | 0.37%   |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                       | 3        | 0.37%   |
| Dell U2720Q DEL41B3 3840x2160 597x336mm 27.0-inch                       | 3        | 0.37%   |
| BenQ LCD BNQ801E 3840x2160 596x335mm 26.9-inch                          | 3        | 0.37%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 3        | 0.37%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                         | 3        | 0.37%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch   | 3        | 0.37%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 528x310mm 24.1-inch   | 3        | 0.37%   |
| Yamaha HTR-6064 YMH3169 1920x540                                        | 2        | 0.25%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch              | 2        | 0.25%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 2        | 0.25%   |
| Sony LCD Monitor TV  *00 3840x2160                                      | 2        | 0.25%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch    | 2        | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.25%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 2        | 0.25%   |
| Samsung Electronics S22C350 SAM0A32 1920x1080 477x268mm 21.5-inch       | 2        | 0.25%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 2        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 280      | 39.27%  |
| 2560x1440 (QHD)    | 97       | 13.6%   |
| 3840x2160 (4K)     | 82       | 11.5%   |
| 1920x1200 (WUXGA)  | 32       | 4.49%   |
| 1280x1024 (SXGA)   | 31       | 4.35%   |
| Unknown            | 29       | 4.07%   |
| 1680x1050 (WSXGA+) | 28       | 3.93%   |
| 3440x1440          | 26       | 3.65%   |
| 3840x1080          | 15       | 2.1%    |
| 2560x1080          | 15       | 2.1%    |
| 1440x900 (WXGA+)   | 11       | 1.54%   |
| 1600x900 (HD+)     | 10       | 1.4%    |
| 1366x768 (WXGA)    | 10       | 1.4%    |
| 3840x1200          | 4        | 0.56%   |
| 1600x1200          | 4        | 0.56%   |
| 7680x2160          | 3        | 0.42%   |
| 2160x1200          | 3        | 0.42%   |
| 1280x960           | 3        | 0.42%   |
| 2560x1600          | 2        | 0.28%   |
| 2288x1287          | 2        | 0.28%   |
| 2048x1152          | 2        | 0.28%   |
| 1920x540           | 2        | 0.28%   |
| 1360x768           | 2        | 0.28%   |
| 1280x720 (HD)      | 2        | 0.28%   |
| 1024x768 (XGA)     | 2        | 0.28%   |
| 6720x2160          | 1        | 0.14%   |
| 6400x2160          | 1        | 0.14%   |
| 6400x1440          | 1        | 0.14%   |
| 5760x2160          | 1        | 0.14%   |
| 5120x1600          | 1        | 0.14%   |
| 4880x1080          | 1        | 0.14%   |
| 400x1280           | 1        | 0.14%   |
| 4000x2560          | 1        | 0.14%   |
| 3926x1440          | 1        | 0.14%   |
| 3840x1600          | 1        | 0.14%   |
| 3640x1080          | 1        | 0.14%   |
| 3600x1200          | 1        | 0.14%   |
| 3600x1080          | 1        | 0.14%   |
| 3440x2880          | 1        | 0.14%   |
| 1400x1050          | 1        | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 154      | 21.51%  |
| 24      | 115      | 16.06%  |
| 23      | 95       | 13.27%  |
| Unknown | 80       | 11.17%  |
| 21      | 60       | 8.38%   |
| 34      | 34       | 4.75%   |
| 19      | 27       | 3.77%   |
| 22      | 20       | 2.79%   |
| 17      | 20       | 2.79%   |
| 31      | 18       | 2.51%   |
| 32      | 10       | 1.4%    |
| 25      | 10       | 1.4%    |
| 20      | 10       | 1.4%    |
| 84      | 9        | 1.26%   |
| 48      | 7        | 0.98%   |
| 18      | 7        | 0.98%   |
| 72      | 4        | 0.56%   |
| 26      | 4        | 0.56%   |
| 15      | 4        | 0.56%   |
| 14      | 4        | 0.56%   |
| 54      | 3        | 0.42%   |
| 40      | 3        | 0.42%   |
| 142     | 2        | 0.28%   |
| 49      | 2        | 0.28%   |
| 47      | 2        | 0.28%   |
| 28      | 2        | 0.28%   |
| 11      | 2        | 0.28%   |
| 50      | 1        | 0.14%   |
| 43      | 1        | 0.14%   |
| 42      | 1        | 0.14%   |
| 41      | 1        | 0.14%   |
| 35      | 1        | 0.14%   |
| 33      | 1        | 0.14%   |
| 29      | 1        | 0.14%   |
| 12      | 1        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 317      | 46.82%  |
| 401-500        | 105      | 15.51%  |
| Unknown        | 80       | 11.82%  |
| 701-800        | 45       | 6.65%   |
| 601-700        | 44       | 6.5%    |
| 351-400        | 22       | 3.25%   |
| 301-350        | 22       | 3.25%   |
| 1001-1500      | 15       | 2.22%   |
| 1501-2000      | 13       | 1.92%   |
| 201-300        | 5        | 0.74%   |
| 801-900        | 4        | 0.59%   |
| 901-1000       | 3        | 0.44%   |
| More than 2000 | 2        | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 396      | 62.46%  |
| 16/10   | 82       | 12.93%  |
| Unknown | 67       | 10.57%  |
| 21/9    | 35       | 5.52%   |
| 5/4     | 31       | 4.89%   |
| 32/9    | 9        | 1.42%   |
| 4/3     | 8        | 1.26%   |
| 1.00    | 3        | 0.47%   |
| 6/5     | 1        | 0.16%   |
| 3/2     | 1        | 0.16%   |
| 0.31    | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 212      | 30.46%  |
| 301-350        | 156      | 22.41%  |
| Unknown        | 80       | 11.49%  |
| 351-500        | 64       | 9.2%    |
| 251-300        | 61       | 8.76%   |
| 151-200        | 51       | 7.33%   |
| 141-150        | 22       | 3.16%   |
| More than 1000 | 21       | 3.02%   |
| 501-1000       | 15       | 2.16%   |
| 101-110        | 4        | 0.57%   |
| 81-90          | 2        | 0.29%   |
| 51-60          | 2        | 0.29%   |
| 131-140        | 2        | 0.29%   |
| 71-80          | 1        | 0.14%   |
| 121-130        | 1        | 0.14%   |
| 111-120        | 1        | 0.14%   |
| 91-100         | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 341      | 52.46%  |
| 101-120 | 150      | 23.08%  |
| Unknown | 80       | 12.31%  |
| 121-160 | 42       | 6.46%   |
| 161-240 | 22       | 3.38%   |
| 1-50    | 15       | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 403      | 60.06%  |
| 2     | 152      | 22.65%  |
| 0     | 81       | 12.07%  |
| 3     | 28       | 4.17%   |
| 4     | 7        | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 366      | 41.17%  |
| Realtek Semiconductor           | 321      | 36.11%  |
| Qualcomm Atheros                | 38       | 4.27%   |
| Broadcom                        | 38       | 4.27%   |
| Aquantia                        | 19       | 2.14%   |
| Nvidia                          | 15       | 1.69%   |
| MediaTek                        | 11       | 1.24%   |
| Marvell Technology Group        | 8        | 0.9%    |
| TP-Link                         | 6        | 0.67%   |
| Microsoft                       | 6        | 0.67%   |
| ASIX Electronics                | 6        | 0.67%   |
| Apple                           | 5        | 0.56%   |
| Ralink                          | 4        | 0.45%   |
| Qualcomm Atheros Communications | 4        | 0.45%   |
| Ralink Technology               | 3        | 0.34%   |
| STMicroelectronics              | 2        | 0.22%   |
| Sigma Designs                   | 2        | 0.22%   |
| OpenMoko                        | 2        | 0.22%   |
| Netchip Technology              | 2        | 0.22%   |
| Metrologic Instruments          | 2        | 0.22%   |
| Huawei Technologies             | 2        | 0.22%   |
| Dresden Elektronik              | 2        | 0.22%   |
| DisplayLink                     | 2        | 0.22%   |
| D-Link System                   | 2        | 0.22%   |
| D-Link                          | 2        | 0.22%   |
| 3Com                            | 2        | 0.22%   |
| Texas Instruments               | 1        | 0.11%   |
| Senao                           | 1        | 0.11%   |
| Raspberry Pi                    | 1        | 0.11%   |
| QLogic                          | 1        | 0.11%   |
| QinHeng Electronics             | 1        | 0.11%   |
| Pulse-Eight                     | 1        | 0.11%   |
| Oculus VR                       | 1        | 0.11%   |
| NetGear                         | 1        | 0.11%   |
| Kyocera                         | 1        | 0.11%   |
| InterBiometrics                 | 1        | 0.11%   |
| Input Club                      | 1        | 0.11%   |
| ICS Advent                      | 1        | 0.11%   |
| Hewlett-Packard                 | 1        | 0.11%   |
| Davicom Semiconductor           | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 254      | 24.24%  |
| Intel I211 Gigabit Network Connection                                         | 109      | 10.4%   |
| Intel Wi-Fi 6 AX200                                                           | 69       | 6.58%   |
| Realtek RTL8125 2.5GbE Controller                                             | 54       | 5.15%   |
| Intel Ethernet Controller I225-V                                              | 38       | 3.63%   |
| Intel Ethernet Connection (2) I219-V                                          | 30       | 2.86%   |
| Intel 82574L Gigabit Network Connection                                       | 22       | 2.1%    |
| Intel Wireless-AC 9260                                                        | 18       | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                          | 18       | 1.72%   |
| Intel I210 Gigabit Network Connection                                         | 13       | 1.24%   |
| Intel Ethernet Connection (2) I218-V                                          | 13       | 1.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 12       | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 12       | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                                         | 10       | 0.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 0.95%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 10       | 0.95%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 9        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 8        | 0.76%   |
| Intel 82579V Gigabit Network Connection                                       | 8        | 0.76%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 8        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 7        | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 7        | 0.67%   |
| Nvidia MCP77 Ethernet                                                         | 7        | 0.67%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 7        | 0.67%   |
| Intel Wireless 8260                                                           | 6        | 0.57%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 0.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 0.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 5        | 0.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5        | 0.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 5        | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 5        | 0.48%   |
| Intel Ethernet Connection I217-V                                              | 5        | 0.48%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 5        | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 4        | 0.38%   |
| Qualcomm Atheros AR9271 802.11n                                               | 4        | 0.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4        | 0.38%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 4        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 157      | 58.58%  |
| Qualcomm Atheros                | 27       | 10.07%  |
| Broadcom                        | 24       | 8.96%   |
| Realtek Semiconductor           | 20       | 7.46%   |
| MediaTek                        | 10       | 3.73%   |
| TP-Link                         | 6        | 2.24%   |
| Microsoft                       | 6        | 2.24%   |
| Ralink                          | 4        | 1.49%   |
| Qualcomm Atheros Communications | 4        | 1.49%   |
| Ralink Technology               | 3        | 1.12%   |
| D-Link                          | 2        | 0.75%   |
| Texas Instruments               | 1        | 0.37%   |
| Senao                           | 1        | 0.37%   |
| NetGear                         | 1        | 0.37%   |
| D-Link System                   | 1        | 0.37%   |
| Broadcom Limited                | 1        | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 69       | 25.65%  |
| Intel Wireless-AC 9260                                              | 18       | 6.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 12       | 4.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 12       | 4.46%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 10       | 3.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 8        | 2.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 7        | 2.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 7        | 2.6%    |
| Intel Wireless 8260                                                 | 6        | 2.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 5        | 1.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 5        | 1.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 5        | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 5        | 1.86%   |
| Qualcomm Atheros AR9271 802.11n                                     | 4        | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 4        | 1.49%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 4        | 1.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 4        | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 4        | 1.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 3        | 1.12%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 3        | 1.12%   |
| Intel Wireless 7265                                                 | 3        | 1.12%   |
| Intel Wireless 7260                                                 | 3        | 1.12%   |
| Intel Wireless 3165                                                 | 3        | 1.12%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection            | 3        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 3        | 1.12%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                  | 3        | 1.12%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 2        | 0.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 2        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2        | 0.74%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 0.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 2        | 0.74%   |
| Microsoft Wireless XBox Controller Dongle                           | 2        | 0.74%   |
| Intel Wireless 8265 / 8275                                          | 2        | 0.74%   |
| Broadcom Network controller                                         | 2        | 0.74%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 2        | 0.74%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.37%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 1        | 0.37%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                 | 1        | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 318      | 44.66%  |
| Intel                    | 303      | 42.56%  |
| Aquantia                 | 19       | 2.67%   |
| Nvidia                   | 15       | 2.11%   |
| Broadcom                 | 14       | 1.97%   |
| Qualcomm Atheros         | 13       | 1.83%   |
| Marvell Technology Group | 8        | 1.12%   |
| ASIX Electronics         | 6        | 0.84%   |
| Apple                    | 5        | 0.7%    |
| DisplayLink              | 2        | 0.28%   |
| 3Com                     | 2        | 0.28%   |
| QLogic                   | 1        | 0.14%   |
| MediaTek                 | 1        | 0.14%   |
| ICS Advent               | 1        | 0.14%   |
| Hewlett-Packard          | 1        | 0.14%   |
| Davicom Semiconductor    | 1        | 0.14%   |
| D-Link System            | 1        | 0.14%   |
| American Megatrends      | 1        | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 254      | 33.55%  |
| Intel I211 Gigabit Network Connection                                         | 109      | 14.4%   |
| Realtek RTL8125 2.5GbE Controller                                             | 54       | 7.13%   |
| Intel Ethernet Controller I225-V                                              | 38       | 5.02%   |
| Intel Ethernet Connection (2) I219-V                                          | 30       | 3.96%   |
| Intel 82574L Gigabit Network Connection                                       | 22       | 2.91%   |
| Intel Ethernet Connection (7) I219-V                                          | 18       | 2.38%   |
| Intel I210 Gigabit Network Connection                                         | 13       | 1.72%   |
| Intel Ethernet Connection (2) I218-V                                          | 13       | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                                         | 10       | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 1.32%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 9        | 1.19%   |
| Intel 82579V Gigabit Network Connection                                       | 8        | 1.06%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 8        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 7        | 0.92%   |
| Nvidia MCP77 Ethernet                                                         | 7        | 0.92%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 0.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 5        | 0.66%   |
| Intel Ethernet Connection I217-V                                              | 5        | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 4        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4        | 0.53%   |
| Nvidia MCP61 Ethernet                                                         | 4        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 0.53%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]           | 4        | 0.53%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 4        | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 3        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.4%    |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.4%    |
| Intel Ethernet Connection (11) I219-V                                         | 3        | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3        | 0.4%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.4%    |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.4%    |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2        | 0.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 2        | 0.26%   |
| Nvidia MCP79 Ethernet                                                         | 2        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 629      | 69.66%  |
| WiFi     | 254      | 28.13%  |
| Modem    | 20       | 2.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 546      | 83.23%  |
| WiFi     | 110      | 16.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 335      | 51.38%  |
| 2     | 225      | 34.51%  |
| 3     | 61       | 9.36%   |
| 4     | 12       | 1.84%   |
| 0     | 8        | 1.23%   |
| 5     | 6        | 0.92%   |
| 6     | 3        | 0.46%   |
| 12    | 1        | 0.15%   |
| 9     | 1        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 550      | 83.21%  |
| Yes  | 111      | 16.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 156      | 56.93%  |
| Cambridge Silicon Radio         | 44       | 16.06%  |
| ASUSTek Computer                | 17       | 6.2%    |
| Realtek Semiconductor           | 13       | 4.74%   |
| Apple                           | 11       | 4.01%   |
| Broadcom                        | 10       | 3.65%   |
| MediaTek                        | 6        | 2.19%   |
| Qualcomm Atheros Communications | 4        | 1.46%   |
| Foxconn / Hon Hai               | 4        | 1.46%   |
| HTC (High Tech Computer)        | 3        | 1.09%   |
| Belkin Components               | 3        | 1.09%   |
| IMC Networks                    | 2        | 0.73%   |
| Dynex                           | 1        | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 74       | 27.01%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 44       | 16.06%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 19       | 6.93%   |
| Intel Bluetooth wireless interface                                   | 16       | 5.84%   |
| Intel AX201 Bluetooth                                                | 13       | 4.74%   |
| Intel AX210 Bluetooth                                                | 12       | 4.38%   |
| Realtek Bluetooth Radio                                              | 11       | 4.01%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 11       | 4.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 8        | 2.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 8        | 2.92%   |
| MediaTek Wireless_Device                                             | 6        | 2.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 1.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5        | 1.82%   |
| Intel Bluetooth Device                                               | 3        | 1.09%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 1.09%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3        | 1.09%   |
| ASUS Bluetooth Radio                                                 | 3        | 1.09%   |
| Apple Bluetooth Host Controller                                      | 3        | 1.09%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.73%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 2        | 0.73%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                   | 2        | 0.73%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 0.73%   |
| ASUS BCM20702A0                                                      | 2        | 0.73%   |
| ASUS ASUS USB-BT500                                                  | 2        | 0.73%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.36%   |
| Realtek Bluetooth 5.1 Radio                                          | 1        | 0.36%   |
| IMC Networks Wireless_Device                                         | 1        | 0.36%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.36%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                      | 1        | 0.36%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.36%   |
| Broadcom BCM20702A0                                                  | 1        | 0.36%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                 | 1        | 0.36%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.36%   |
| Belkin Components Bluetooth Device with trace filter                 | 1        | 0.36%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.36%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.36%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 1        | 0.36%   |
| Apple Bluetooth HCI                                                  | 1        | 0.36%   |
| Apple Bluetooth Device                                               | 1        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 377      | 32.17%  |
| Nvidia                                          | 263      | 22.44%  |
| Intel                                           | 239      | 20.39%  |
| C-Media Electronics                             | 44       | 3.75%   |
| Logitech                                        | 23       | 1.96%   |
| Creative Labs                                   | 20       | 1.71%   |
| ASUSTek Computer                                | 16       | 1.37%   |
| SteelSeries ApS                                 | 14       | 1.19%   |
| Creative Technology                             | 12       | 1.02%   |
| Texas Instruments                               | 11       | 0.94%   |
| Focusrite-Novation                              | 9        | 0.77%   |
| Razer USA                                       | 7        | 0.6%    |
| JMTek                                           | 7        | 0.6%    |
| Thesycon Systemsoftware & Consulting            | 6        | 0.51%   |
| Kingston Technology                             | 6        | 0.51%   |
| Realtek Semiconductor                           | 5        | 0.43%   |
| GYROCOM C&C                                     | 5        | 0.43%   |
| Corsair                                         | 5        | 0.43%   |
| Blue Microphones                                | 5        | 0.43%   |
| BEHRINGER International                         | 5        | 0.43%   |
| Solid State Logic                               | 4        | 0.34%   |
| Samson Technologies                             | 4        | 0.34%   |
| RODE Microphones                                | 4        | 0.34%   |
| GN Netcom                                       | 4        | 0.34%   |
| AudioQuest                                      | 4        | 0.34%   |
| Trust                                           | 3        | 0.26%   |
| Sony                                            | 3        | 0.26%   |
| Sennheiser Communications                       | 3        | 0.26%   |
| Plantronics                                     | 3        | 0.26%   |
| Generalplus Technology                          | 3        | 0.26%   |
| Audient                                         | 3        | 0.26%   |
| Yamaha                                          | 2        | 0.17%   |
| TEAC                                            | 2        | 0.17%   |
| SAVITECH                                        | 2        | 0.17%   |
| Nektar                                          | 2        | 0.17%   |
| Microsoft                                       | 2        | 0.17%   |
| Micro Star International                        | 2        | 0.17%   |
| MAG Technology                                  | 2        | 0.17%   |
| M-Audio                                         | 2        | 0.17%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 153      | 10.8%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 81       | 5.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 72       | 5.08%   |
| AMD Navi 10 HDMI Audio                                                     | 38       | 2.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 34       | 2.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 32       | 2.26%   |
| AMD Family 17h/19h HD Audio Controller                                     | 29       | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 28       | 1.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 23       | 1.62%   |
| Intel 200 Series PCH HD Audio                                              | 22       | 1.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 21       | 1.48%   |
| Nvidia GA102 High Definition Audio Controller                              | 20       | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 20       | 1.41%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 19       | 1.34%   |
| Nvidia TU104 HD Audio Controller                                           | 17       | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 17       | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                              | 16       | 1.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16       | 1.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16       | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16       | 1.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 16       | 1.13%   |
| Nvidia GM204 High Definition Audio Controller                              | 15       | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14       | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14       | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14       | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 13       | 0.92%   |
| Nvidia GP102 HDMI Audio Controller                                         | 13       | 0.92%   |
| ASUSTek Computer USB Audio                                                 | 13       | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                              | 12       | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 0.85%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 12       | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 12       | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 11       | 0.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 11       | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 10       | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10       | 0.71%   |
| Nvidia GA106 High Definition Audio Controller                              | 10       | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10       | 0.71%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 10       | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 130      | 20.16%  |
| Corsair             | 124      | 19.22%  |
| G.Skill             | 108      | 16.74%  |
| Unknown             | 75       | 11.63%  |
| Crucial             | 74       | 11.47%  |
| Samsung Electronics | 35       | 5.43%   |
| SK hynix            | 20       | 3.1%    |
| Micron Technology   | 16       | 2.48%   |
| Team                | 9        | 1.4%    |
| Patriot             | 8        | 1.24%   |
| A-DATA Technology   | 7        | 1.09%   |
| Nanya Technology    | 4        | 0.62%   |
| GOODRAM             | 4        | 0.62%   |
| Transcend           | 3        | 0.47%   |
| Ramaxel Technology  | 3        | 0.47%   |
| Unknown             | 3        | 0.47%   |
| Toshiba             | 2        | 0.31%   |
| AMD                 | 2        | 0.31%   |
| Thermaltake         | 1        | 0.16%   |
| T-FORCE             | 1        | 0.16%   |
| Qumo                | 1        | 0.16%   |
| PUSKILL             | 1        | 0.16%   |
| PNY                 | 1        | 0.16%   |
| Patriot Memory      | 1        | 0.16%   |
| Kllisre             | 1        | 0.16%   |
| KLEVV               | 1        | 0.16%   |
| HPE                 | 1        | 0.16%   |
| Hikvision           | 1        | 0.16%   |
| Hewlett-Packard     | 1        | 0.16%   |
| Golden Empire       | 1        | 0.16%   |
| GeIL                | 1        | 0.16%   |
| Exceleram           | 1        | 0.16%   |
| Chun Well           | 1        | 0.16%   |
| Asgard              | 1        | 0.16%   |
| Apacer              | 1        | 0.16%   |
| A Force             | 1        | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 12       | 1.72%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 10       | 1.43%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 9        | 1.29%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 8        | 1.14%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 7        | 1%      |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s  | 7        | 1%      |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 6        | 0.86%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 6        | 0.86%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 6        | 0.86%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 6        | 0.86%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 5        | 0.72%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 5        | 0.72%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s        | 5        | 0.72%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 4        | 0.57%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s       | 4        | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 4        | 0.57%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s     | 4        | 0.57%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM 6400MT/s           | 4        | 0.57%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s      | 4        | 0.57%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s        | 4        | 0.57%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s    | 4        | 0.57%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s    | 4        | 0.57%   |
| Corsair RAM CMK32GX4M2B3000C15 16384MB DIMM DDR4 3000MT/s | 4        | 0.57%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s     | 4        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 3        | 0.43%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 3        | 0.43%   |
| Unknown RAM Module 512MB DIMM SDRAM                       | 3        | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 3        | 0.43%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 3        | 0.43%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 3        | 0.43%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s       | 3        | 0.43%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 3        | 0.43%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s    | 3        | 0.43%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s     | 3        | 0.43%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 3        | 0.43%   |
| G.Skill RAM F4-3200C16-16GTZ 16GB DIMM DDR4 3200MT/s      | 3        | 0.43%   |
| G.Skill RAM F4-3200C14-8GTZ 8GB DIMM DDR4 3733MT/s        | 3        | 0.43%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3200MT/s     | 3        | 0.43%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s      | 3        | 0.43%   |
| Crucial RAM CT4G4DFS8213.C8FAD11 4GB DIMM DDR4 2133MT/s   | 3        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 387      | 64.61%  |
| DDR3    | 125      | 20.87%  |
| DDR2    | 29       | 4.84%   |
| Unknown | 23       | 3.84%   |
| DDR5    | 18       | 3.01%   |
| SDRAM   | 13       | 2.17%   |
| DDR     | 4        | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 583      | 97.65%  |
| SODIMM | 13       | 2.18%   |
| RIMM   | 1        | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 242      | 37.64%  |
| 16384 | 190      | 29.55%  |
| 4096  | 86       | 13.37%  |
| 32768 | 62       | 9.64%   |
| 2048  | 44       | 6.84%   |
| 1024  | 15       | 2.33%   |
| 512   | 3        | 0.47%   |
| 256   | 1        | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 86       | 13.13%  |
| 3600    | 80       | 12.21%  |
| 1600    | 62       | 9.47%   |
| 1333    | 43       | 6.56%   |
| 2400    | 42       | 6.41%   |
| 2133    | 38       | 5.8%    |
| 2667    | 27       | 4.12%   |
| 3000    | 23       | 3.51%   |
| 800     | 23       | 3.51%   |
| 3400    | 21       | 3.21%   |
| 3733    | 20       | 3.05%   |
| 3466    | 18       | 2.75%   |
| 667     | 18       | 2.75%   |
| 3800    | 12       | 1.83%   |
| 2933    | 12       | 1.83%   |
| 2666    | 12       | 1.83%   |
| Unknown | 10       | 1.53%   |
| 3866    | 8        | 1.22%   |
| 1866    | 8        | 1.22%   |
| 1867    | 7        | 1.07%   |
| 3534    | 6        | 0.92%   |
| 2800    | 6        | 0.92%   |
| 1066    | 6        | 0.92%   |
| 6400    | 5        | 0.76%   |
| 6000    | 5        | 0.76%   |
| 4800    | 5        | 0.76%   |
| 3666    | 5        | 0.76%   |
| 4000    | 4        | 0.61%   |
| 3933    | 4        | 0.61%   |
| 3333    | 4        | 0.61%   |
| 3066    | 4        | 0.61%   |
| 400     | 4        | 0.61%   |
| 5200    | 3        | 0.46%   |
| 3100    | 3        | 0.46%   |
| 2048    | 3        | 0.46%   |
| 3334    | 2        | 0.31%   |
| 3266    | 2        | 0.31%   |
| 2465    | 2        | 0.31%   |
| 2134    | 2        | 0.31%   |
| 3500    | 1        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 6        | 42.86%  |
| Brother Industries    | 3        | 21.43%  |
| Samsung Electronics   | 2        | 14.29%  |
| Seiko Epson           | 1        | 7.14%   |
| Lexmark International | 1        | 7.14%   |
| Canon                 | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson WF-3520 Series           | 1        | 7.14%   |
| Samsung ML-1630 Series               | 1        | 7.14%   |
| Samsung C460 Series                  | 1        | 7.14%   |
| Lexmark International Lexmark E352dn | 1        | 7.14%   |
| HP PhotoSmart 130                    | 1        | 7.14%   |
| HP LaserJet M14-M17                  | 1        | 7.14%   |
| HP LaserJet 1020                     | 1        | 7.14%   |
| HP LaserJet 1018                     | 1        | 7.14%   |
| HP LaserJet 1010                     | 1        | 7.14%   |
| HP Deskjet 2050 J510                 | 1        | 7.14%   |
| Canon LiDE 400                       | 1        | 7.14%   |
| Brother MFC-L2700DW                  | 1        | 7.14%   |
| Brother MFC-9340CDW                  | 1        | 7.14%   |
| Brother MFC-9130CW                   | 1        | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 5        | 83.33%  |
| AGFA-Gevaert NV | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 2        | 33.33%  |
| Canon CanoScan LiDE 600F      | 1        | 16.67%  |
| Canon CanoScan LiDE 220       | 1        | 16.67%  |
| Canon CanoScan LiDE 110       | 1        | 16.67%  |
| AGFA-Gevaert NV SnapScan e20  | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 85       | 56.67%  |
| Microdia                      | 12       | 8%      |
| Sunplus Innovation Technology | 6        | 4%      |
| Samsung Electronics           | 6        | 4%      |
| Z-Star Microelectronics       | 5        | 3.33%   |
| Realtek Semiconductor         | 3        | 2%      |
| MacroSilicon                  | 3        | 2%      |
| Generalplus Technology        | 3        | 2%      |
| Creative Technology           | 3        | 2%      |
| Chicony Electronics           | 3        | 2%      |
| AVerMedia Technologies        | 3        | 2%      |
| ARC International             | 3        | 2%      |
| Apple                         | 3        | 2%      |
| YGTek                         | 1        | 0.67%   |
| Xiaomi                        | 1        | 0.67%   |
| WaveRider Communications      | 1        | 0.67%   |
| Valve Software                | 1        | 0.67%   |
| SiGma Micro                   | 1        | 0.67%   |
| Ruision                       | 1        | 0.67%   |
| Razer USA                     | 1        | 0.67%   |
| KYE Systems (Mouse Systems)   | 1        | 0.67%   |
| GEMBIRD                       | 1        | 0.67%   |
| Cubeternet                    | 1        | 0.67%   |
| A4Tech                        | 1        | 0.67%   |
| 2M UVC CAMERA                 | 1        | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                 | 19       | 12.26%  |
| Logitech Webcam C270                        | 17       | 10.97%  |
| Microdia USB 2.0 Camera                     | 7        | 4.52%   |
| Samsung Galaxy series, misc. (MTP mode)     | 6        | 3.87%   |
| Logitech C922 Pro Stream Webcam             | 6        | 3.87%   |
| Logitech BRIO Ultra HD Webcam               | 6        | 3.87%   |
| Logitech Webcam C310                        | 5        | 3.23%   |
| Logitech C920 PRO HD Webcam                 | 4        | 2.58%   |
| Z-Star Venus USB2.0 Camera                  | 3        | 1.94%   |
| Microdia Camera                             | 3        | 1.94%   |
| MacroSilicon USB Video                      | 3        | 1.94%   |
| Logitech Webcam C925e                       | 3        | 1.94%   |
| Logitech HD Webcam C615                     | 3        | 1.94%   |
| Logitech HD Webcam C510                     | 3        | 1.94%   |
| Logitech B525 HD Webcam                     | 3        | 1.94%   |
| ARC International Camera                    | 3        | 1.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X             | 3        | 1.94%   |
| Z-Star Vimicro USB Camera (Altair)          | 2        | 1.29%   |
| Sunplus MiraBox Video Capture               | 2        | 1.29%   |
| Sunplus Canyon CNS-CWC5 Webcam              | 2        | 1.29%   |
| Realtek FULL HD 1080P Webcam                | 2        | 1.29%   |
| Logitech Webcam C930e                       | 2        | 1.29%   |
| Logitech Webcam C200                        | 2        | 1.29%   |
| Logitech HD Webcam C525                     | 2        | 1.29%   |
| Logitech BRIO 4K Stream Edition             | 2        | 1.29%   |
| Chicony Gateway Webcam                      | 2        | 1.29%   |
| AVerMedia USB Device                        | 2        | 1.29%   |
| YGTek Webcam                                | 1        | 0.65%   |
| Xiaomi Mi 9 Lite                            | 1        | 0.65%   |
| WaveRider USB 2.0 Camera                    | 1        | 0.65%   |
| Valve Software 3D Camera                    | 1        | 0.65%   |
| Sunplus FHD Camera Microphone               | 1        | 0.65%   |
| Sunplus Aluratek UHD 4K Camera              | 1        | 0.65%   |
| SiGma Micro Micro USB Web Camera            | 1        | 0.65%   |
| Ruision UVC Camera                          | 1        | 0.65%   |
| Realtek Full HD webcam                      | 1        | 0.65%   |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 0.65%   |
| Microdia Webcam Vitade AF                   | 1        | 0.65%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 0.65%   |
| MacroSilicon ShadowCast                     | 1        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| SCM Microsystems                  | 4        | 22.22%  |
| Clay Logic                        | 4        | 22.22%  |
| Yubico.com                        | 3        | 16.67%  |
| Advanced Card Systems             | 2        | 11.11%  |
| VASCO Data Security International | 1        | 5.56%   |
| Hewlett-Packard                   | 1        | 5.56%   |
| Gemalto (was Gemplus)             | 1        | 5.56%   |
| Bit4id                            | 1        | 5.56%   |
| Aktiv                             | 1        | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 4        | 22.22%  |
| Clay Logic Nitrokey Pro                                | 4        | 22.22%  |
| Yubico.com Yubikey 4/5 CCID                            | 2        | 11.11%  |
| Yubico.com Yubikey 4 U2F+CCID                          | 1        | 5.56%   |
| VASCO Data Security International DIGIPASS 870         | 1        | 5.56%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)          | 1        | 5.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 5.56%   |
| Bit4id miniLector-s                                    | 1        | 5.56%   |
| Aktiv Rutoken lite                                     | 1        | 5.56%   |
| Advanced Card Systems ACR38 SmartCard Reader           | 1        | 5.56%   |
| Advanced Card Systems ACR122U                          | 1        | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 374      | 53.74%  |
| 1     | 201      | 28.88%  |
| 2     | 77       | 11.06%  |
| 3     | 27       | 3.88%   |
| 4     | 9        | 1.29%   |
| 6     | 3        | 0.43%   |
| 5     | 3        | 0.43%   |
| 7     | 2        | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 102      | 22.77%  |
| Graphics card            | 77       | 17.19%  |
| Sound                    | 51       | 11.38%  |
| Net/wireless             | 48       | 10.71%  |
| Bluetooth                | 48       | 10.71%  |
| Firewire controller      | 18       | 4.02%   |
| Unassigned class         | 15       | 3.35%   |
| Network                  | 15       | 3.35%   |
| Camera                   | 13       | 2.9%    |
| Storage/ide              | 12       | 2.68%   |
| Chipcard                 | 9        | 2.01%   |
| Net/ethernet             | 8        | 1.79%   |
| Storage/raid             | 6        | 1.34%   |
| Multimedia controller    | 6        | 1.34%   |
| Modem                    | 5        | 1.12%   |
| Tv card                  | 4        | 0.89%   |
| Storage/ata              | 3        | 0.67%   |
| Card reader              | 3        | 0.67%   |
| Fingerprint reader       | 2        | 0.45%   |
| Storage/nvme             | 1        | 0.22%   |
| Storage                  | 1        | 0.22%   |
| Dvb card                 | 1        | 0.22%   |

